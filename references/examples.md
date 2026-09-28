# Worked Examples for paper_revision

## 1. Self-defense writing vs analytical development

Self-defense writing follows the pattern: claim → hedge against misunderstanding → restate claim → hedge against another misunderstanding.

**Self-defense version (do not write like this):**

> The Bayesian model is not used because Bayesian methods are inherently superior to machine learning. Rather, it is used because it provides a posterior predictive distribution. This does not mean that machine learning cannot quantify uncertainty. Instead, the key distinction is...

It looks rigorous, but it only answers "that is not what I mean." The reader is left asking: so what? Why does the posterior predictive distribution matter for the actual problem?

**Analytical version (write like this):**

> The downstream stochastic program requires joint municipality-level demand scenarios rather than point forecasts. The Bayesian spatiotemporal model estimates a joint posterior predictive distribution while partially pooling information across municipalities with sparse quarterly counts. Posterior predictive draws therefore preserve both parameter uncertainty and the dependence structure required to construct coherent demand scenarios for optimization.

Every sentence moves forward: downstream requirement → data structure → methodological capability → consequence for scenario generation.

**Show, don't tell.** Not:

> Our method is appropriate for sparse small-area data.

But:

> With only 20 quarterly EMS observations per municipality, estimating municipality-specific demand processes independently would produce unstable estimates. Hierarchical partial pooling allows information to be shared across municipalities while retaining municipality-level heterogeneity.

The reader concludes "this method fits" on their own.

## 2. The problem–requirement–method fit chain

Methodology justification should be one clean chain, not a sequence of defenses against alternatives (not LSTM, not ARIMA, not copula, not bootstrap...).

**Data structure**
municipality-level + quarterly + sparse counts + spatial/temporal dependence + multiple related overdose indicators

↓

**Downstream requirement**
The stochastic program needs joint scenarios
D^(s) = (D_{1,1}^(s), ..., D_{351,4}^(s)),
not point forecasts for each municipality.

↓

**Statistical requirement**
The model must therefore handle, simultaneously:
- count nature of the data
- small-area instability
- spatial/temporal structure
- predictive uncertainty
- joint posterior predictive sampling

↓

**Model choice**
hierarchical Bayesian spatiotemporal count model

↓

**Scenario generation**
posterior predictive draws

↓

**Optimization input**
a finite scenario set for the two-stage stochastic program.

The chain itself is the justification.

## 3. Digest reviewer feedback; do not write the rebuttal into the paper

Suppose a reviewer writes: "The rationale for using annual mortality data alongside quarterly EMS data is unclear."

**Rebuttal-in-manuscript (do not write like this):**

> Although mortality data are annual rather than quarterly, this does not mean that they cannot provide useful information. Rather, mortality data capture another dimension of opioid burden...

This visibly answers the reviewer.

**Digested (write like this):**

> EMS incidents provide temporally resolved observations of acute overdose activity, whereas mortality records capture a more severe downstream outcome at a coarser temporal resolution. The two outcomes are linked through a shared latent municipality-level overdose burden, allowing annual mortality observations to inform estimation of the underlying process without treating deaths as quarterly observations.

The reviewer's question is resolved, but the text shows no trace of being an answer to a reviewer.
