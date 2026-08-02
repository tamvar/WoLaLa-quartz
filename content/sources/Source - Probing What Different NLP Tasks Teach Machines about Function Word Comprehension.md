---
title: Source - Probing What Different NLP Tasks Teach Machines about Function Word Comprehension
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - probing
  - function-words
  - pretraining
  - evaluation
---

## Summary
Najoung Kim and collaborators introduce nine challenge tasks for function-word comprehension and use them to compare sentence encoders trained with different pretraining objectives. Language modeling performs best on average, but natural-language inference and CCG supertagging help on some specific phenomena, especially negation and sentence-boundary-sensitive items. For WoLaLa, the paper matters because it shows that grammatical subskills can depend on pretraining objective and evaluation design rather than collapsing into a single notion of "linguistic knowledge."

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)

## WoLaLa Relevance
This source is valuable because function words sit close to core grammatical organization while still being easy to overread. The paper's design keeps architecture fixed and varies the pretraining objective, which makes it a cleaner test of what different objectives encourage models to encode. That gives WoLaLa a source about grammatical competence that is simultaneously methodological.

It also sharpens the repository's distinction between task performance and theory-facing interpretation. Better scores on these challenge tasks do not by themselves prove semantic or syntactic mastery, but they do reveal which training objectives support different kinds of function-word sensitivity. The paper therefore belongs both in the theory-facing structure batch and in the broader methodological conversation about what evaluations actually measure.

## Key Points
- The paper builds nine challenge tasks by structurally mutating existing datasets to isolate function-word phenomena.
- Language-model pretraining performs best on average, but no single objective dominates every task.
- Natural-language inference especially helps negation-related behavior, while CCG supertagging helps some structurally delimited phenomena.
- The result supports a differentiated view of pretraining objectives rather than a single global measure of linguistic competence.

## Limitation Or Open Question
The tasks are still probing-style diagnostics rather than direct causal tests of model computation. The main open question is how these objective-specific differences line up with stronger behavioral evidence and with more explicit syntactic or semantic analyses.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]

## Source Identification
- Authors: Najoung Kim, Roma Patel, Adam Poliak, Alex Wang, Patrick Xia, R. Thomas McCoy, Ian Tenney, Alexis Ross, Tal Linzen, Benjamin Van Durme, Samuel R. Bowman, and Ellie Pavlick
- Title: *Probing What Different NLP Tasks Teach Machines about Function Word Comprehension*
- Year: 2019
- Source type: workshop paper
- Publication: *Proceedings of the Student Research Workshop Associated with RANLP 2019*, pages 155-163
- DOI: `10.18653/v1/S19-1026`

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/S19-1026/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/S19-1026)
