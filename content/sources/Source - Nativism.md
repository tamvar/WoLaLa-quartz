---
title: Source - Nativism
type: source
status: active
updated: 2026-08-02
ingestion_depth: brief
tags:
  - source
  - brief
  - nativism
  - language-acquisition
  - statistical-learning
---

## Summary

Georges Rey reconstructs linguistic nativism while criticizing arguments that obscure its strongest form. Innateness and learning are not opposites: experience may select, trigger, or tune a system whose hypothesis space and operating principles are biologically constrained. The deepest dispute with general statistical learning is therefore not whether statistics are used, but whether surface distributions and domain-general procedures can determine the predicates, modal exclusions, and hidden structures that characterize human grammar.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## Clarifying the Claim

Rey rejects rhetorical shortcuts such as suggesting that denial of UG erases all differences among humans, animals, and rocks. The real issue is which species-specific initial structures explain language acquisition. He also qualifies the comparison with rationalist knowledge of mathematics. Grammar is not a set of a priori truths derived by reason. Nor is language acquisition exactly like the maturation of teeth: arbitrary lexical forms and language-specific variation plainly depend on experience.

For cognitive purposes, innateness can be treated as a species-wide initial state that develops into stable competence under input. On Chomsky’s view, UG characterizes that initial state and constrains the function mapping experience to I-language. This formulation leaves room for learning mechanisms.

## Innate and Learned

Early Chomskyan acquisition models resemble constrained hypothesis testing: the learner represents input, represents structural analyses, considers a delimited class of grammars, determines their consequences, and selects among compatible candidates. A grammar can therefore be both innate as a possibility and learned as the attained state. Experience selects or occasions one organization from a prior space.

The relevant contrast is with construction from sensory data by unconstrained association or induction. Statistical inference can set parameters or choose hypotheses while presupposing linguistic categories and priors. The question becomes how those categories and constraints originate.

## Three Problems for General Statistics

Goodman’s “grue” problem shows that any finite observations support indefinitely many unnatural generalizations. Statistical learning therefore requires a privileged vocabulary of projectible predicates. Bayesian models make this explicit through priors and likelihoods; they may be `predicate nativist` even when they reject a fully specified UG.

Modal knowledge creates a second problem. Grammar concerns what is possible or impossible, not just what is frequent. Children encounter countless absent but grammatical sentences and may hear malformed strings, so nonoccurrence alone does not distinguish impossibility from accident.

Finally, superficial distributions underdetermine whether difficulty belongs to grammar, parsing, phonology, meaning, or world knowledge. Rey argues for process nativism: some principles are not hypotheses confirmed by the child but constraints governing how a specialized faculty operates.

## WoLaLa Interpretation

The chapter is especially relevant to claims that language models settle the nativism debate. A model trained by statistical optimization still contains architecture, tokenization, objective, data selection, and optimization biases. Calling the result “learned from data” does not show that domain-general statistics alone explain the attained representations.

Conversely, successful neural learning can constrain claims about which priors are necessary. The informative question is comparative: what inductive biases, data, and objectives are sufficient for the target generalization, and do they reproduce human modal judgments and error patterns?

## Limitations

- Rey develops a philosophical argument rather than a quantitative acquisition model.
- `Process nativism` identifies an explanatory position but does not specify a complete neural or computational implementation.
- Claims about unavailable evidence require corpus and developmental verification case by case.
- The chapter does not directly test modern language models.

## Related Pages

- [[Source - How Statistical Learning Can Play Well with Universal Grammar]]
- [[Source - Universal Grammar and Language Acquisition]]
- [[Source - The Deep Forces That Shape Language and the Poverty of the Stimulus]]
- [[Source - Chomsky and Usage-Based Linguistics]]

## Source Identification

- Author: Georges Rey
- Chapter: “Nativism”
- Year: 2021
- Parent volume: *A Companion to Chomsky*
- Editors: Nicholas Allott, Terje Lohndal, and Georges Rey
- Publisher: Wiley-Blackwell / John Wiley & Sons
- Edition: First edition
- Chapter number: 28
- Printed pages: 451–461
- PDF pages: 468–478
- Parent source ID: `src_companion_chomsky_2021_container`
- Component source ID: `src_companion_chomsky_2021_ch28`
- DOI: `10.1002/9781119598732.ch28`

## Source Access

- Public source: [Wiley chapter page](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119598732.ch28)
- DOI: [DOI landing page](https://doi.org/10.1002/9781119598732.ch28)

## Open Questions

- Which linguistic predicates and modal constraints must be supplied by a learner’s architecture rather than induced from input?
- What model comparisons can identify necessary bias without treating any successful architecture as a theory of human acquisition?
