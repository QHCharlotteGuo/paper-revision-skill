---
name: "paper_revision"
description: "Draft, develop, revise, or refine academic manuscripts in Industrial Engineering, Operations Research, applied statistics, and public health. Precise analytical prose where each sentence advances the argument: no over-defensive or template-like writing, problem–method fit justification, controlled claim strength, and section-level guidance for literature review, Methods, Results, and Discussion. Trigger when Charlotte asks to draft, revise, polish, or rewrite paper text ('revise this paragraph', 'polish this section', 'draft from these notes', '改这段', '润色', '帮我写一段')."
---

# Academic Manuscript Writing and Revision

Use this skill to draft, develop, revise, or refine academic manuscripts in Industrial Engineering, Operations Research, applied statistics, and public health.

The goal is not to make the writing sound maximally academic. The goal is to communicate a precise scientific argument efficiently, with each sentence performing a clear analytical function.

> Guiding insight: the real danger of AI-like prose is not a few template words. It is the structure of writing that keeps explaining why it is right instead of advancing the analysis.

## 1. Preserve the research logic

When revising existing text, preserve the author's substantive argument, technical terminology, methodological choices, findings, and intended contribution unless a substantive problem is identified.

When drafting new text, do not invent motivations, mechanisms, methodological advantages, literature gaps, results, limitations, or contributions merely to create a complete-sounding narrative. Build the argument only from information and evidence that are actually available.

Do not turn the research into a different paper for the sake of producing a cleaner narrative.

## 2. Write from analytical logic, not academic templates

Before drafting a paragraph, determine what that paragraph must establish and how it advances the manuscript.

Prefer analytical progression such as:

**claim → evidence or reason → mechanism or explanation → implication**

For methodological reasoning, prefer:

**problem characteristic → analytical requirement → methodological capability → consequence for the study**

For literature-based arguments, establish:

**what is known → what remains unresolved → why the unresolved issue matters → what the present study addresses**

These are reasoning principles, not mandatory paragraph templates. Do not mechanically force every paragraph into the same structure.

## 3. Make each sentence advance the analysis

Each sentence should contribute new information, reasoning, evidence, interpretation, or methodological detail.

Avoid sentences whose primary function is to:

- announce that something is important;
- repeat the preceding claim in different words;
- praise the method;
- reassure the reader that a methodological choice is reasonable;
- preempt every possible objection;
- provide a generic transition;
- summarize an implication that is already obvious.

If removing a sentence does not reduce the substantive content or logical continuity of the paragraph, consider removing it.

## 4. Avoid overdefensive writing

Do not write the manuscript as a continuous response to hypothetical reviewers.

Avoid repeatedly relying on structures such as:

- "X is not A, but rather B";
- "This does not mean that...";
- "Instead...";
- "Rather than...";
- "It is important to note that...";
- "Although X..., this does not...";
- repeated qualifications followed by qualifications of those qualifications.

These constructions are acceptable when a genuine scientific distinction must be made. They should not become the organizing logic of a paragraph.

A manuscript should primarily explain what the study does, why the research problem creates particular analytical requirements, what the evidence shows, and what follows from those findings.

When incorporating reviewer feedback, absorb the underlying clarification into the scientific argument. Do not make the manuscript read like a rebuttal letter.

**Diagnostic (deletion test):** temporarily remove "not / rather than / instead / however / although / importantly" from the paragraph. If almost no substantive content remains, the paragraph is defense, not analysis — rebuild it around what the study does and why the problem requires it. These words are fine in isolation; the problem is a paragraph whose logic depends on them to survive.

## 5. Use problem–method fit for methodological justification

Do not begin with a method and then generate generic reasons why it is appropriate.

Start from the research problem.

Identify the relevant characteristics of the data, estimand, decision problem, uncertainty, or downstream analysis. Then determine what capabilities the method must provide and explain how the selected method provides them.

Do not justify a method mainly by listing why other methods are inferior.

Discuss alternatives only when comparison is necessary to understand the methodological choice, contribution, or limitation.

For example, if a stochastic optimization model requires joint municipality-level demand scenarios, explain why the downstream model requires joint scenarios, what dependence and uncertainty must therefore be represented, and how the statistical model generates the required scenarios. Do not construct an unnecessary sequence of defenses against ARIMA, LSTM, bootstrap, copulas, and other possible methods.

## 6. Show rather than tell

Demonstrate methodological suitability through concrete properties of the research problem.

Avoid generic statements such as:

"The proposed framework is well suited to sparse small-area data."

Prefer substantive explanation such as:

"With only 20 quarterly observations per municipality, independently estimating municipality-specific demand processes would produce unstable estimates. Hierarchical partial pooling allows information to be shared across municipalities while retaining municipality-level heterogeneity."

Similarly, do not call an approach "comprehensive," "robust," "effective," "novel," or "appropriate" when the underlying analysis can demonstrate the relevant property directly.

## 7. Avoid template-like academic prose

Use natural, publication-quality academic English appropriate for Industrial Engineering / Operations Research and public-health research. Preserve necessary technical terminology, but avoid both overly conversational language and inflated academic prose.

Remove or avoid unnecessary:

- repetition;
- inflated wording;
- generic academic filler;
- conversational phrasing;
- excessive signposting;
- rhetorical emphasis;
- vague statements of importance.

**Vague evaluative adjectives.** Words such as *substantial, significant, considerable, notable, meaningful, robust, comprehensive, critical, crucial, compelling, nuanced,* and *multifaceted* are not prohibited, but use them only when they convey a specific and justified meaning. Prefer reporting the actual magnitude, pattern, or result instead of relying on vague evaluative adjectives.

**Transition and emphasis words.** Avoid excessive use of *notably, importantly, moreover, furthermore, additionally,* and *indeed*, especially at the beginning of paragraphs or sentences. Use transitions only when they clarify the logical relationship between ideas.

**Formulaic interpretive verbs and phrases.** Be especially cautious with *underscore, highlight, reinforce, showcase, highlight the importance of,* and *underscore the need for*. Do not add sentences merely to tell the reader that a finding is "important." State what the finding actually means for the research question, mechanism, method, or application.

**Generic academic phrases.** Avoid phrases that add little substantive content, including *complex interplay, multifaceted nature, broader implications, valuable insights, nuanced understanding, comprehensive framework, holistic approach, critical role, key driver, growing body of literature,* and *meaningful contribution*. Replace them with specific descriptions of the variables, relationships, findings, methodological contribution, or unresolved problem.

**Template-like constructions.** Avoid *It is important to note that...*, *It is worth noting that...*, *Taken together, these findings suggest that...*, *These results underscore the need for...*, and *This study contributes to the growing body of literature...* unless the sentence adds information that cannot be stated more directly.

Do not substitute obscure vocabulary for ordinary precise language merely to make the prose sound sophisticated.

Prioritize precise, concrete academic prose. Each sentence should advance the argument, report evidence, explain a methodological choice, interpret a specific result, or establish a research gap. Do not use academic-sounding language merely to make the writing appear sophisticated. If an adjective, adverb, transition, or interpretive sentence can be removed without changing the scientific meaning, remove it.

## 8. Control claim strength

Match every claim to the evidence supporting it.

Do not turn:

- association into causation;
- prediction into explanation;
- feature importance into causal importance;
- model output into empirical fact;
- methodological convenience into methodological superiority;
- observed patterns into established mechanisms;
- lack of statistical significance into evidence of no relationship.

Use qualifications when scientifically required, but do not overqualify claims that are already appropriately bounded.

## 9. Build literature reviews through synthesis

Do not write literature reviews as sequences of paper summaries.

Organize the literature around the scientific problem, methodological issue, empirical finding, or unresolved question.

Use individual studies as evidence within that structure.

A research gap must follow from the literature rather than being manufactured through statements such as "few studies have..." or "no study has comprehensively..." without adequate support.

Distinguish between:

- something that has not been studied;
- something that has been studied but not resolved;
- a methodological limitation of existing studies;
- a different research question;
- a different dataset or population.

Do not call every difference from prior work a research gap.

## 10. Write Methods around reproducible analytical decisions

Methods writing should explain what was done and provide the information necessary to understand or reproduce the analysis.

Explain methodological choices when the choice affects interpretation, identification, uncertainty, optimization behavior, or reproducibility.

Do not defend every standard modeling decision.

When a method is unfamiliar or central to the contribution, explain its role in the study before introducing technical detail.

Maintain clear distinctions among data, assumptions, parameters, decision variables, estimands, objectives, constraints, statistical models, uncertainty representations, algorithms, and evaluation procedures.

## 11. Write Results as results

Report findings directly and precisely.

Do not repeatedly explain why the findings are important or restate the Methods.

Separate empirical findings from interpretation when appropriate.

Avoid converting every numerical result into a rhetorical claim.

Report uncertainty, effect size, model performance, or optimization outcomes in the form appropriate to the analysis.

Do not selectively strengthen favorable results or defensively explain unfavorable ones.

## 12. Write Discussion as interpretation rather than repetition

Use the Discussion to explain what the findings mean in relation to the research question and existing evidence.

Develop plausible explanations only when they are supported by evidence or clearly identified as interpretations.

Do not repeat the Results section paragraph by paragraph.

Do not manufacture broad policy implications from narrow empirical findings.

Limitations should identify actual inferential or practical constraints and explain their consequences. Do not produce a generic checklist of limitations, and do not defend each limitation immediately after acknowledging it.

## 13. Maintain paragraph-level coherence

A paragraph should have one primary analytical purpose, although it may contain several related ideas needed to develop that purpose.

The opening sentence should establish the issue when necessary, not merely announce the topic.

The middle of the paragraph should develop the reasoning or evidence.

Do not automatically add a final sentence that restates the paragraph or says that the findings "highlight the importance" of something.

Use transitions only when they represent a genuine logical relationship.

## 14. Prefer concise scientific prose

Use the shortest formulation that preserves the necessary scientific meaning.

Conciseness does not mean removing methodological detail, evidence, uncertainty, or qualifications required for scientific accuracy.

Remove rhetorical excess rather than substantive information.

When two sentences make essentially the same point, consolidate them.

When a sentence merely announces what the next sentence will say, remove it unless the signposting is genuinely useful.

## 15. Separate writing problems from research problems

When revising or drafting, distinguish between language issues and substantive scientific issues.

If the issue is wording, fix the wording.

If there is a potential:

- methodological inconsistency;
- unsupported claim;
- citation mismatch;
- mismatch between the described and implemented analysis;
- interpretation unsupported by the results;
- unclear estimand;
- unjustified assumption;
- inconsistency in terminology with substantive consequences;
- gap that is not established by the literature;

identify it separately.

Do not hide a substantive problem through elegant rewriting.

Do not invent a methodological solution when the available information is insufficient.

## 16. When drafting from notes or an outline

Do not simply expand every bullet into several academic-sounding sentences.

First identify the logical relationships among the supplied ideas.

Combine overlapping points, remove points that do not advance the argument, and determine what evidence is required for each substantive claim.

Draft only what is supported by the supplied information.

If an essential logical step is missing, identify the missing step rather than filling it with generic prose.

The resulting text should read as an argument developed by a researcher who understands the problem, not as an expanded version of an outline.

## 17. Default workflow

For new writing:

1. Determine what the section or paragraph must establish.
2. Identify the evidence, methodological reasoning, or results available to support it.
3. Establish the logical progression before drafting.
4. Draft concise academic prose around that progression.
5. Remove sentences that merely announce importance, repeat claims, or defend against hypothetical objections.
6. Check claim strength and terminology.
7. Identify any missing evidence or substantive logical gaps separately.

For revision:

1. Identify the original analytical purpose.
2. Preserve substantive content and technical meaning.
3. Remove redundancy, template language, conversational wording, and unnecessary self-defense.
4. Reorganize the passage when necessary to improve analytical progression.
5. Improve grammar, tense, voice, transitions, and terminology consistency.
6. Check whether claims remain supported.
7. Flag substantive problems separately rather than silently rewriting around them.

The final manuscript should sound direct, technically precise, and analytically developed. It should not sound as though the author is trying to convince the reader that every methodological decision is correct. The reasoning and evidence should provide that justification.

## 18. Output contract

For revision tasks, deliver:

1. The revised passage (same meaning, terminology, and arguments as the original).
2. A short list of the wording-level changes made and why.
3. A separate list of any substantive issues found (per section 15) — flagged, never silently rewritten.

For drafting tasks, deliver:

1. The drafted text, built only from the supplied information and evidence.
2. A separate list of missing logical steps, missing evidence, or substantive gaps identified (per section 16) — flagged, never filled with generic prose.

## References

- `references/examples.md` — worked examples: the self-defense vs analytical rewrite, the full problem–requirement–method fit chain, and digesting reviewer feedback into the manuscript.
