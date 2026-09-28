# Academic Manuscript Writing and Revision

A writing skill for drafting, developing, revising, and refining academic manuscripts in Industrial Engineering, Operations Research, applied statistics, and public health.

The goal is not to make writing sound maximally academic. The goal is to communicate a precise scientific argument efficiently, with each sentence performing a clear analytical function.

## Core principles

- **Analytical development over self-defense.** Every sentence should advance the analysis (claim → evidence/reason → mechanism → implication), not spend words defending the claim against imaginary misunderstandings.
- **Problem–method fit.** Justify methods from the research problem: data structure → downstream requirement → statistical requirement → model choice → what the model produces — not by listing why every alternative is wrong.
- **Show, don't tell.** Demonstrate suitability through concrete properties of the problem; don't assert it with adjectives.
- **Digest reviewer feedback.** Absorb the underlying clarification into the scientific argument; never write the rebuttal into the manuscript.
- **Control claim strength.** Match every claim to its evidence.
- **Separate writing problems from research problems.** Fix wording directly; flag methodological inconsistencies, unsupported claims, or citation mismatches separately — never hide them with elegant rewriting.

## Contents

- `SKILL.md` — the full skill: 18 sections covering analytical logic, over-defensive writing, problem–method fit, claim strength, literature synthesis, Methods / Results / Discussion guidance, drafting from notes, and default workflows for new writing and revision.
- `references/examples.md` — worked examples: a self-defense vs analytical rewrite, a full problem–requirement–method fit chain for Bayesian spatiotemporal modeling feeding a two-stage stochastic program, and digesting reviewer feedback into the manuscript.

## Use

Copy this directory into your agent's skills folder (e.g. `~/workspace/skills/paper-revision/`), then ask the agent to draft, revise, or polish paper text. See `SKILL.md` for trigger phrases and the output contract.
