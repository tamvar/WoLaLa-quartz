---
title: What Probing Evidence Can Support
type: analysis
status: active
updated: 2026-04-23
tags:
  - analysis
  - probing
  - interpretability
---

## Summary
The sources considered here support a graded interpretation of probing evidence. Ordinary probe success most safely supports "the property is extractable from the representation under this probe and dataset." Stronger claims about model use, causality, or human-like structure require additional controls, interventions, behavioral tests, or constrained hypotheses.

## Key Points
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Belinkov]] argues that probe accuracy alone is difficult to interpret without baselines, controls, probe complexity accounting, and clear definitions.
- [[../sources/Source - What Do NMT Models Learn About Morphology|Belinkov et al. on NMT morphology]] show how diagnostic classifiers can compare where and how linguistic information is extractable across model components, such as encoder vs. decoder and lower vs. higher layers.
- [[../sources/Source - What You Can Cram Into a Single Vector|Conneau et al.]] show that sentence embedding probes can reveal many readable properties, but also that bag-of-vectors and untrained encoders can perform surprisingly well.
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Hewitt and Manning]] support a more specific geometric claim: parse-tree distances and depths are recoverable after a linear transformation.
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Tenney et al.]] and [[../sources/Source - What Does BERT Learn About the Structure of Language|Jawahar et al.]] independently report layerwise linguistic organization in BERT, but both remain within an inspectability/probing frame.
- convergent evidence across probe types strengthens confidence that BERT contains extractable linguistic structure, but does not settle whether BERT uses that structure causally.

## Evidence
The sources differ in what they test:
- sentence embedding probing tests whether global sentence vectors retain simple linguistic properties
- structural probing tests whether token representation geometry can encode parse-tree structure
- edge probing tests whether span-level labels and relations are recoverable from contextual vectors
- BERT layer analyses test whether different linguistic properties are concentrated at different depths

They also share limitations. Probe success depends on task design, training data, baselines, and probe capacity. Some sources explicitly show that shallow or random baselines can carry useful signal.

The NMT morphology source adds an architectural-comparison use case for probing. It does not merely ask whether morphology is extractable; it compares which internal components expose it better. That supports relative claims such as "NMT encoder layer 1 exposes more morphology than layer 2 in these experiments" more strongly than broad claims about how translation is performed.

This analysis belongs to the probing cluster rather than [[../overviews/Induction Heads and In-Context Learning Overview|the induction-head cluster]]. It evaluates readout evidence and evidence standards, not circuit-level mechanisms or causal ablations.

## Interpretation
Probing claims of this kind should be phrased cautiously:
- Prefer: "property X is extractable/readable from representation Y under probe Z."
- Use with caution: "model Y encodes X."
- Avoid without stronger evidence: "model Y uses X", "model Y has learned grammar", or "model Y reasons with syntax."

Stronger evidence can come from interventions, counterfactual representations, behavioral tests targeted at the same property, or convergent results from constrained probes.

## Related Pages
- [[../concepts/Probing Classifiers|Probing Classifiers]]
- [[../concepts/Structural Probes|Structural Probes]]
- [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]

## Sources
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Source - Probing Classifiers Promises Shortcomings and Advances]]
- [[../sources/Source - What Do NMT Models Learn About Morphology|Source - What Do NMT Models Learn About Morphology]]
- [[../sources/Source - What You Can Cram Into a Single Vector|Source - What You Can Cram Into a Single Vector]]
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Source - A Structural Probe for Finding Syntax in Word Representations]]
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Source - BERT Rediscovers the Classical NLP Pipeline]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]

## Open Questions
- What is the wiki's threshold for upgrading an extractability claim into a model-use claim?
- Should future ingestion track probe controls in a standardized field on source pages?
