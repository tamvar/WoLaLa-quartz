---
title: Neural NLP Probing Overview
type: overview
status: active
updated: 2026-04-23
tags:
  - overview
  - probing
  - interpretability
---

## Summary
This overview maps a source-grounded topic on neural NLP probing. The topic focuses on what linguistic information is extractable from NMT representations, sentence embeddings, contextual token representations, and BERT layers, while preserving methodological caution about what probing can and cannot prove.

## Key Points
- Belinkov et al. use POS and morphological tagging probes to compare word/character representations, encoder depth, target language, encoder vs. decoder representations, and attention in NMT systems.
- Conneau et al. introduce sentence-level probing tasks for surface, syntactic, and semantic properties.
- Hewitt and Manning introduce a structural probe for recovering parse-tree distances and depths from transformed contextual word representations.
- Tenney et al. and Jawahar et al. both report layerwise linguistic organization in BERT.
- Belinkov reviews probing limitations and argues for controls, complexity-aware metrics, and interventions for stronger claims.
- the cluster supports a cautious picture of neural NLP systems as containing extractable linguistic structure, not a settled claim that they use explicit linguistic rules.

## Topic Map
- Core concepts: [[../concepts/Probing Classifiers|Probing Classifiers]], [[../concepts/Structural Probes|Structural Probes]], [[../concepts/Sentence Embedding Probing|Sentence Embedding Probing]], [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]], [[../concepts/Representation Geometry|Representation Geometry]]
- Relevant analysis: [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- Source set: probing and BERT sources plus the NMT morphology extension listed below

## Details
[[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Belinkov]] is the cluster's methodological anchor: it supplies the evidence standard that keeps probe results framed as extractability claims unless stronger controls or interventions are present.

[[../sources/Source - What You Can Cram Into a Single Vector|Conneau et al.]] establish sentence-level probing tasks, [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Hewitt and Manning]] test a narrower geometric syntax hypothesis, and [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Tenney et al.]] plus [[../sources/Source - What Does BERT Learn About the Structure of Language|Jawahar et al.]] extend the cluster into layerwise BERT analysis. [[../sources/Source - What Do NMT Models Learn About Morphology|Belinkov et al. on NMT morphology]] broadens the cluster historically and architecturally without changing its main question.

The cluster boundary with [[Induction Heads and In-Context Learning Overview]] should remain explicit. Neural NLP probing asks what information is readable from representations under controlled probes or related analyses. The induction-head cluster asks what transformer circuits implement behavior and what causal evidence supports that claim.

## Related Pages
- [[Induction Heads and In-Context Learning Overview]]
- [[../concepts/Probing Classifiers|Probing Classifiers]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]

## Sources
- [[../sources/Source - What Do NMT Models Learn About Morphology|Source - What Do NMT Models Learn About Morphology]]
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Source - Probing Classifiers Promises Shortcomings and Advances]]
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Source - A Structural Probe for Finding Syntax in Word Representations]]
- [[../sources/Source - What You Can Cram Into a Single Vector|Source - What You Can Cram Into a Single Vector]]
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Source - BERT Rediscovers the Classical NLP Pipeline]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]

## Open Questions
- Which probing standards should the wiki apply before treating a claim as strong evidence?
- How much of the BERT-era probing literature transfers to current LLMs?
- How much of the NMT morphology evidence transfers from LSTM encoder-decoder systems to transformer NMT?
- Which future sources genuinely bridge linguistic probing and mechanistic interpretability, rather than merely sharing an interpretability label?
