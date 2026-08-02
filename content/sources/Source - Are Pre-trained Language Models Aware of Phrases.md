---
title: Source - Are Pre-trained Language Models Aware of Phrases
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - syntax
  - constituency
  - grammar-induction
  - language-models
---

## Summary
Taeuk Kim, Jihun Choi, Daniel Edmiston, and Sang-goo Lee ask whether pretrained language models contain constituency information that can be recovered without task-specific training. Their method extracts constituency trees directly from pretrained representations and shows that several language models induce phrase structure competitively with dedicated grammar-induction systems. For WoLaLa, the paper matters because it turns phrase awareness into a theory-facing structural question rather than only a downstream parsing result.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is a useful bridge between grammar induction and representation analysis. It does not claim that pretrained models literally implement a symbolic grammar formalism, but it does show that constituency-sensitive organization is accessible in the representations without fine-tuning a parser. That makes the result stronger than a mere downstream transfer success and more specific than generic claims that large language models contain "some syntax."

The paper is also methodologically restrained in a helpful way. Recoverable phrase structure is evidence for extractable hierarchical organization, not a complete account of how models process sentences. The result therefore belongs with other structure-sensitive competence sources, while still requiring the evidential caution emphasized by the probing and evaluation analyses elsewhere in WoLaLa.

## Key Points
- The paper proposes a training-free method for extracting constituency trees from pretrained language-model representations.
- Several pretrained models induce phrase structure competitively with dedicated grammar-induction approaches.
- The results are especially notable on phrase boundaries such as adverb phrases, where some pretrained models outperform prior baselines.
- The contribution is about recoverable constituency information, not about proving that the model computes with explicit phrase-structure rules.

## Limitation Or Open Question
The paper establishes that phrase structure is recoverable from the representations, but not whether the model causally relies on that same structure during ordinary prediction or reasoning. That keeps the result on the extractability side of the evidential ladder.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - Compound Probabilistic Context-Free Grammars for Grammar Induction|Source - Compound Probabilistic Context-Free Grammars for Grammar Induction]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]

## Source Identification
- Authors: Taeuk Kim, Jihun Choi, Daniel Edmiston, and Sang-goo Lee
- Title: *Are Pre-trained Language Models Aware of Phrases? Simple but Strong Baselines for Grammar Induction*
- Year: 2020
- Source type: conference paper
- Publication: *International Conference on Learning Representations (ICLR 2020)*

## Source Access
- Public source: [OpenReview page](https://openreview.net/forum?id=H1xPR3NtPB)
