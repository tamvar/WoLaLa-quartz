---
title: Source - What You Can Cram Into a Single Vector
type: source
status: active
updated: 2026-04-23
tags:
  - source
  - probing
  - sentence-embeddings
---

# Source - What You Can Cram Into a Single Vector

## Summary
Conneau, Kruszewski, Lample, Barrault, and Baroni introduce ten probing tasks for diagnosing what linguistic properties are readable from sentence embeddings. The paper systematizes sentence-level probing across surface, syntactic, and semantic properties and compares encoders, architectures, and training objectives.

## Key Points
- Source fact: the paper introduces ten probing tasks: SentLen, WC, BShift, TreeDepth, TopConst, Tense, SubjNum, ObjNum, SOMO, and CoordInv.
- Source fact: the tasks are grouped into surface, syntactic, and semantic categories, though the paper notes the syntax/semantics boundary is partly arbitrary for some tasks.
- Source fact: all tasks are designed to require only a single sentence embedding as input, improving comparability across encoder architectures.
- Source fact: the authors evaluate BiLSTM, gated ConvNet, bag-of-vectors, and multiple training objectives including NMT, autoencoding, SkipThought, Seq2Tree, NLI, and untrained encoders.
- Source fact: bag-of-vectors baselines capture surprisingly much sentence-level information, and untrained BiLSTM-max also performs well on several tasks.
- Source fact: word-content performance correlates strongly with many downstream tasks, suggesting that some downstream evaluations may reward lexical retention more than abstract linguistic structure.

## Details
The paper motivates probing because downstream task success is too coarse to reveal what a sentence embedding contains. It constructs controlled classification tasks over sentences from the Toronto Book Corpus and uses them to compare encoders without depending on architecture-specific introspection.

Its results show that probing itself needs careful baselines: simple bag-of-vectors and untrained models can perform unexpectedly well. This reinforces the caution from Belinkov's review.

## Synthesis / Interpretation
This source provides the reusable task vocabulary that later BERT papers reuse to study layerwise linguistic hierarchy. It also warns against interpreting probe success as necessarily deep linguistic abstraction, since lexical and architectural priors can carry substantial signal.

Within `neural_nlp_probing`, this source anchors the sentence-level probing branch of the cluster. Its role is methodological and comparative, not mechanistic.

## Related Pages
- [[../concepts/Probing Classifiers|Probing Classifiers]]
- [[../concepts/Sentence Embedding Probing|Sentence Embedding Probing]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]

## Source Identification
- Authors: Alexis Conneau, Germán Kruszewski, Guillaume Lample, Loïc Barrault, and Marco Baroni
- Title: *What You Can Cram into a Single $&!#* Vector: Probing Sentence Embeddings for Linguistic Properties*

## Open Questions
- Which of these ten tasks should become local reference tasks for future wiki comparisons?
- How much downstream benchmark performance is explained by lexical retention rather than compositional or structural representation?
