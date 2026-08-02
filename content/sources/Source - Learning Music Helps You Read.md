---
title: Source - Learning Music Helps You Read
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - syntax
  - transfer
  - structure
  - language-models
---

## Summary
Isabel Papadimitriou and Dan Jurafsky use transfer learning to ask what kinds of non-linguistic structure help recurrent language models learn natural-language syntax. They show that pretraining on music, code, and even simple artificial symbol systems can improve later language-model performance, and that cross-lingual transfer tracks typological syntactic similarity. For WoLaLa, the paper matters because it reframes syntactic evidence around transferable structural bias rather than around a single benchmark or probing score.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)

## WoLaLa Relevance
This source is useful because it separates several questions that are often run together. Better transfer from structured pretraining data does not by itself show human-like grammar, but it does suggest that language models benefit from abstract relational organization that is not reducible to shared vocabulary. The comparison between nested-parentheses and flat paired-dependency languages is especially important because it blocks an overly simple conclusion that only full hierarchical recursion matters.

The paper also bears on acquisition-style debates. Its cross-linguistic result suggests that syntactic similarity can matter independently of lexical overlap, which makes transfer performance relevant to questions about what kind of structural bias a learner can acquire from experience. That is a weaker claim than proving a linguistically explicit internal grammar, but it is stronger than saying that language-model pretraining only memorizes local surface statistics.

## Key Points
- The paper uses transfer from non-linguistic and cross-linguistic pretraining data to test what abstract structure benefits language modeling.
- Music, code, and artificial symbol systems with latent relational structure improve downstream natural-language perplexity.
- A flat paired-dependency artificial language helps nearly as much as a recursive one, so the result is about abstract structure more generally, not recursion alone.
- Cross-lingual zero-shot transfer correlates with typological syntactic similarity, linking transfer behavior to structural properties of languages.

## Limitation Or Open Question
The evidence is still indirect: improved transfer shows that certain structural regularities are useful to the model, but it does not by itself identify the internal representation format or prove that the model has acquired syntax in the same explanatory sense that linguistic theory often seeks.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../sources/Source - Can Neural Networks Acquire a Structural Bias from Raw Linguistic Data|Source - Can Neural Networks Acquire a Structural Bias from Raw Linguistic Data]]
- [[../sources/Source - Colorless Green Recurrent Networks Dream Hierarchically|Source - Colorless Green Recurrent Networks Dream Hierarchically]]

## Source Identification
- Authors: Isabel Papadimitriou and Dan Jurafsky
- Title: *Learning Music Helps You Read: Using Transfer to Study Linguistic Structure in Language Models*
- Year: 2020
- Source type: conference paper
- Publication: *Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing*, pages 6829-6839
- DOI: `10.18653/v1/2020.emnlp-main.554`

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2020.emnlp-main.554/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/2020.emnlp-main.554)
