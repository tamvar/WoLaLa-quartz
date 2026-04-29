---
title: Source - What Does BERT Learn About the Structure of Language
type: source
status: active
updated: 2026-04-23
tags:
  - source
  - bert
  - probing
  - syntax
---

## Summary
Jawahar, Sagot, and Seddah probe BERT-base layer by layer and argue that BERT captures a hierarchy of linguistic signals: lower layers emphasize surface and phrase-level information, middle layers encode syntactic information, and upper layers encode more semantic information. They also test subject-verb agreement and compositional structure.

## Key Points
- the paper studies `bert-base-uncased` across its 12 layers.
- lower BERT layers cluster phrase-level span representations better than higher layers in the authors' chunking-based analysis.
- using the Conneau et al. probing tasks, the authors report surface features strongest in lower layers, syntactic features strongest in middle layers, and semantic features strongest in higher layers.
- subject-verb agreement performance is strongest in middle layers for many cases, with deeper layers helping when long-distance dependencies and more attractors are involved.
- using Tensor Product Decomposition Networks, the authors report that tree-based role schemes best approximate BERT representations across many layers.
- the paper concludes that BERT captures structural properties of English and a compositional pattern with parallels to traditional syntactic analysis.

## Details
This paper uses several complementary probes: span clustering for phrase-level information, SentEval probing tasks for linguistic hierarchy, subject-verb agreement stimuli for syntactic dependency tracking, and TPDN approximation for compositional role schemes.

It partly overlaps with the Tenney et al. paper in supporting a layerwise hierarchy, but uses simpler sentence-level probing tasks and additional tests for subject-verb agreement and compositional structure.

## Interpretation
This source reinforces the idea that BERT's layers differ systematically in the kind of linguistic information that is extractable. It also broadens the evidence beyond edge probing by adding phrase clustering, agreement tests, and compositional approximation.

Within `neural_nlp_probing`, this source complements the Tenney et al. page by widening the evidence types while staying within the same extractability frame.

## Related Pages
- [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]]
- [[../concepts/Sentence Embedding Probing|Sentence Embedding Probing]]
- [[../concepts/Representation Geometry|Representation Geometry]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]

## Source Identification
- Authors: Ganesh Jawahar, Benoît Sagot, and Djamé Seddah
- Title: *What Does BERT Learn About the Structure of Language?*

## Open Questions
- Do the reported lower/middle/upper layer patterns persist in larger, decoder-only, or multilingual transformer models?
- How should TPDN-style compositional evidence be integrated with structural-probe evidence?
