---
title: Sentence Embedding Probing
type: concept
status: active
updated: 2026-04-23
tags:
  - concept
  - probing
  - sentence-embeddings
---

## Summary
Sentence embedding probing uses diagnostic tasks to test what information is readable from fixed-size sentence vectors. The Conneau et al. task suite probes surface, syntactic, and semantic properties while requiring only a single sentence embedding as input.

## Key Points
- Conneau et al. introduce ten probing tasks spanning sentence length, word content, word order, tree depth, top constituents, tense, subject/object number, semantic odd-man-out, and coordination inversion.
- the tasks are designed to be architecture-agnostic and to avoid requiring token-level representations.
- strong bag-of-vectors and untrained-encoder results show that lexical and architectural priors can explain some probe success.
- Jawahar et al. reuse these tasks to analyze BERT layer by layer.

## Details
[[../sources/Source - What You Can Cram Into a Single Vector|Conneau et al.]] make sentence embedding probing useful for comparing encoders, but the paper also shows that its claims are limited by task design and baselines. A classifier that recovers word content or tense from a sentence vector does not necessarily show that the encoder has human-like grammatical knowledge.

The Conneau et al. suite becomes a bridge across this literature: first introduced for sentence embeddings generally, then reused by [[../sources/Source - What Does BERT Learn About the Structure of Language|Jawahar et al.]] to study BERT's layerwise organization.

Even when reused in later transformer work, this remains a probing framework for readable properties rather than a mechanistic account of how a model implements behavior.

## Related Pages
- [[Probing Classifiers]]
- [[Linguistic Knowledge in BERT]]
- [[../sources/Source - What You Can Cram Into a Single Vector|Source - What You Can Cram Into a Single Vector]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]

## Sources
- [[../sources/Source - What You Can Cram Into a Single Vector|Source - What You Can Cram Into a Single Vector]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]

## Open Questions
- Which sentence-level probing tasks are most robust to lexical shortcuts?
- How should sentence embedding probing be integrated with token-level and span-level probing?
