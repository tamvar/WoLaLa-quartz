---
title: Source - How Much Do Language Models Memorize
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - memorization
  - evaluation
  - capacity
  - methodology
---

## Summary
Morris and colleagues propose a way to estimate how much specific training information a language model stores, while separating unintended memorization from broader generalization. Their central claim is that model capacity can be measured in information-theoretic terms and that memorization does not simply rise without bound: as dataset size passes capacity, models shift away from memorization toward generalization. For WoLaLa, the paper matters because it sharpens debates about training-data leakage, benchmark contamination, and scholarly misuse of apparently knowledgeable outputs.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)

## WoLaLa Relevance
This source gives the memorization debate a more formal and operational shape than casual worries about regurgitation. That is useful both for evaluation methodology and for SSH-facing caution, since questions about what a model `knows` are central to literary analysis, corpus use, and claims about linguistic competence.

## Key Points
- The paper distinguishes unintended memorization from generalization to an underlying data-generating process.
- It proposes a method for estimating total memorization and model capacity.
- The results suggest a nontrivial relation between dataset size, model scale, and double-descent-like behavior.
- The work is relevant to contamination and data-exposure arguments, not just to privacy in the narrow sense.

## Limitation Or Open Question
The method is ambitious and still depends on modeling assumptions about how to isolate memorization from generalization. An open question is how cleanly the framework carries over to messy real-world corpora and culturally significant long-tail text.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../sources/Source - Speak, Memory|Source - Speak, Memory]]
- [[../sources/Source - The Generative AI Paradox|Source - The Generative AI Paradox]]

## Source Identification
- Authors: John X. Morris, Chawin Sitawarin, Chuan Guo, Narine Kokhlikyan, G. Edward Suh, Alexander M. Rush, Kamalika Chaudhuri, and Saeed Mahloujifar
- Title: "How much do language models memorize?"
- Year: 2025
- Source type: preprint
- Publication context: arXiv `2505.24832`

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2505.24832)
