---
title: Source - Colorless Green Recurrent Networks Dream Hierarchically
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - syntax
  - hierarchy
  - rnn
  - multilinguality
---

## Summary
Kristina Gulordava, Piotr Bojanowski, Edouard Grave, Tal Linzen, and Marco Baroni test whether language-model-trained RNNs can track hierarchical syntax rather than only lexical or semantic shortcuts. Their key move is to evaluate long-distance agreement not only on ordinary corpus sentences but also on grammatical nonsense sentences that remove plausible meaning-based cues. Across English, Italian, Hebrew, and Russian, the models perform strongly, and for Italian their judgments come close to human behavior. For WoLaLa, the paper matters because it became one of the strongest early arguments that generic language-model training can induce nontrivial syntactic generalization.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is central to debates about whether neural sequence models are only shallow statistical pattern matchers. The nonce-sentence design is important because it reduces the force of an easy rebuttal: that models may simply prefer verbs that fit the semantic content of a sentence. Strong performance on semantically degraded examples does not settle the syntax question, but it raises the evidential bar for dismissing hierarchical generalization altogether.

The multilingual scope also matters. Agreement is tested across languages with richer morphology than English, which makes the result harder to explain away as one narrow benchmark artifact. At the same time, the paper stays focused on one family of syntactic dependencies, so its importance is as a strong case study rather than a complete theory of grammatical competence.

## Key Points
- The paper uses nonce sentences to reduce lexical-semantic and collocational shortcuts.
- RNN language models perform well on long-distance agreement in four languages.
- Italian human judgments provide a direct comparison point rather than a purely model-internal metric.
- Stronger language-model perplexity correlates with stronger agreement accuracy, linking broad modeling quality to syntax-sensitive behavior.

## Limitation Or Open Question
The study focuses on agreement phenomena in RNNs rather than the full range of syntax or newer transformer-based models. The open question is how far this kind of evidence generalizes across phenomena, architectures, and stricter tests of structural competence.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - Assessing BERT's Syntactic Abilities|Source - Assessing BERT's Syntactic Abilities]]
- [[../sources/Source - Targeted Syntactic Evaluation of Language Models|Source - Targeted Syntactic Evaluation of Language Models]]

## Source Identification
- Authors: Kristina Gulordava, Piotr Bojanowski, Edouard Grave, Tal Linzen, and Marco Baroni
- Title: *Colorless Green Recurrent Networks Dream Hierarchically*
- Year: 2018
- Source type: conference paper
- Publication: *Proceedings of NAACL-HLT 2018*, pages 1195-1205
- DOI: `10.18653/v1/N18-1108`

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/N18-1108/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/N18-1108)
