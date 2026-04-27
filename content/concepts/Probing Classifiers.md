---
title: Probing Classifiers
type: concept
status: active
updated: 2026-04-23
tags:
  - concept
  - probing
  - interpretability
---

# Probing Classifiers

## Summary
A probing classifier is an auxiliary model trained to predict a target property from representations produced by another model. In neural NLP interpretability, probes are used to ask whether linguistic properties are readable or extractable from learned representations.

## Key Points
- Source fact: Belinkov defines probing as a framework involving an original model/task/dataset and a separate probing model/task/dataset.
- Source fact: Belinkov et al. use POS and morphological tagging classifiers to evaluate representations extracted from frozen NMT encoders and decoders.
- Source fact: Conneau et al. use probing tasks to diagnose sentence embeddings across surface, syntactic, and semantic properties.
- Source fact: Tenney et al. use edge probing to convert multiple structured linguistic tasks into a common span-labeling or span-pair-labeling format.
- Source fact: Belinkov emphasizes that probe accuracy alone does not show that the original model uses the probed property.

## Details
[[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Belinkov]] frames probes broadly: they can be simple linear classifiers, more expressive neural classifiers, parameter-free analyses, or constrained models such as structural probes. The interpretability question changes with the probe: a high-capacity probe may reveal information in principle, while a simpler probe may better support claims about easy extractability.

[[../sources/Source - What Do NMT Models Learn About Morphology|Belinkov et al. on NMT morphology]] show the same basic pattern in early NMT probing work: train a translation model, freeze it, extract internal representations, and train a separate classifier for a linguistic task. This makes it possible to compare representation types and architectural locations without claiming that the classifier is part of the translation model.

[[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Tenney et al.]] extend the basic probing idea into edge probing over span representations, while [[../sources/Source - What You Can Cram Into a Single Vector|Conneau et al.]] adapt it to fixed-size sentence embeddings. These are still probing-style readout methods, not mechanistic circuit analyses.

Common methodological concerns:
- baselines and skylines
- control tasks or control functions
- probe complexity and selectivity
- dataset artifacts
- correlation versus causation
- whether the probed property was predefined and available as annotation

## Related Pages
- [[Structural Probes]]
- [[Sentence Embedding Probing]]
- [[Linguistic Knowledge in BERT]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]

## Sources
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Source - Probing Classifiers Promises Shortcomings and Advances]]
- [[../sources/Source - What Do NMT Models Learn About Morphology|Source - What Do NMT Models Learn About Morphology]]
- [[../sources/Source - What You Can Cram Into a Single Vector|Source - What You Can Cram Into a Single Vector]]
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Source - BERT Rediscovers the Classical NLP Pipeline]]

## Open Questions
- What should count as a minimally adequate probe control for wiki claims?
- Should future pages reserve "encoded" for extractability and use "used" only with causal or intervention evidence?
