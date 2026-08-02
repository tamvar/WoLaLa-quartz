---
title: Source - Sentence Processing and Syntactic Theory
type: source
status: active
updated: 2026-08-02
ingestion_depth: brief
tags:
  - source
  - brief
  - sentence-processing
  - syntax
  - competence-performance
---

## Summary

Dave Kush and Brian Dillon show how grammatical theory informs models of real-time sentence processing without requiring a one-to-one mapping between grammatical derivations and parsing steps. Through garden paths, filler-gap dependencies, and anaphora, they argue that formal analyses specify the representations and relations a parser must eventually compute. Psycholinguistic evidence then tests when and how those commitments are implemented under memory, expectation, and incremental uncertainty.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## Competence and Processing

Chomsky’s competence–performance distinction does not make grammar irrelevant to performance. A competence grammar characterizes well-formed representations while abstracting from memory limits, attention, errors, and use. A parser must construct interpretations over time under precisely those constraints. The same grammar can be compatible with multiple processing algorithms, so an experiment typically evaluates a grammar together with linking hypotheses rather than adjudicating a formalism directly.

The failed Derivational Theory of Complexity is an important caution. Early work predicted that more grammatical transformations should produce longer whole-sentence processing times. Negative results did not logically refute transformational grammar because the mapping from formal derivations to temporal operations was itself an additional hypothesis.

## Three Model Systems

Garden-path sentences show that a grammatical string can initially seem unacceptable because the parser commits to a locally preferred analysis and must revise it. Competing models differ over serial versus parallel analyses, probabilistic expectation, and how syntactic, semantic, and contextual information guide reanalysis. All presuppose some account of the alternative structures.

Filler-gap dependencies reveal active prediction. Readers often posit a gap at the earliest grammatically licensed position, producing a filled-gap slowdown when an overt object appears instead. Island constraints restrict where gaps are anticipated, while some grammaticality illusions show that processing can imperfectly enforce the grammar. These results connect structural constraints with working-memory management.

Anaphora research asks how reflexives, pronouns, and names retrieve antecedents under Binding constraints. Grammatical structure sharply limits candidate antecedents, but experiments debate whether illicit feature-matching distractors briefly interfere. The dispute concerns the timing and priority of constraints more than whether syntactic structure matters.

## WoLaLa Interpretation

The chapter supplies a framework for interpreting language-model behavior. A model can produce an apparently grammatical continuation while relying on expectations that diverge from a competence description. Surprisal and next-token probabilities are processing-like measures; they do not directly reveal the full set of structures a system can represent.

Strong comparisons should combine carefully controlled grammatical contrasts with incremental measures and explicit linking hypotheses. Garden paths, active gap filling, islands, and anaphoric interference can test whether model expectations respect structure, but behavioral alignment should not be equated with the human parser or a specific grammar.

## Limitations

- The survey is selective and focuses on three well-developed English-centered literatures.
- Current linking hypotheses cannot resolve many fine-grained differences among grammatical formalisms.
- Processing evidence can reflect interacting syntactic, semantic, contextual, and memory effects.
- No direct tests of transformer language models are reported.

## Related Pages

- [[Source - The Enduring Discoveries of Generative Syntax]]
- [[Source - The Architecture of the Computation]]
- [[Source - Linguistic Judgments as Evidence]]
- [[Source - From the Origins of Government and Binding to the Current State of Minimalism]]

## Source Identification

- Authors: Dave Kush and Brian Dillon
- Chapter: “Sentence Processing and Syntactic Theory”
- Year: 2021
- Parent volume: *A Companion to Chomsky*
- Editors: Nicholas Allott, Terje Lohndal, and Georges Rey
- Publisher: Wiley-Blackwell / John Wiley & Sons
- Edition: First edition
- Chapter number: 19
- Printed pages: 307–324
- PDF pages: 324–341
- Parent source ID: `src_companion_chomsky_2021_container`
- Component source ID: `src_companion_chomsky_2021_ch19`
- DOI: `10.1002/9781119598732.ch19`

## Source Access

- Public source: [Wiley chapter page](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119598732.ch19)
- DOI: [DOI landing page](https://doi.org/10.1002/9781119598732.ch19)

## Open Questions

- Which linking hypotheses make human reading-time and model-surprisal comparisons theoretically informative?
- Where do models show grammar-sensitive prediction versus superficial expectation or repair?
