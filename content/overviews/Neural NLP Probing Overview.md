---
title: Neural NLP Probing Overview
type: overview
status: active
updated: 2026-07-29
tags:
  - overview
  - probing
  - interpretability
---

## Summary
This overview maps a source-grounded topic on neural NLP probing. The topic focuses on what linguistic information is extractable from NMT representations, sentence embeddings, contextual token representations, and BERT layers, while preserving a graded distinction among extractability, encoded information, behavioral relevance, causal contribution, and mechanistic explanation.

This page is a subordinate technical cluster overview within the broader strand map:

- [[Linguistic Competence and Limitations Overview]]

## Key Points
- Belinkov et al. use POS and morphological tagging probes to compare word/character representations, encoder depth, target language, encoder vs. decoder representations, and attention in NMT systems.
- Conneau et al. introduce sentence-level probing tasks for surface, syntactic, and semantic properties.
- Hewitt and Manning introduce a structural probe for recovering parse-tree distances and depths from transformed contextual word representations.
- Tenney et al. and Jawahar et al. both report layerwise linguistic organization in BERT.
- Rogers et al. organize the broader BERT-analysis literature and make its unresolved methodological questions explicit.
- Lin et al. and Coenen et al. extend BERT probing into hierarchy-sensitive diagnostics and representation geometry.
- Belinkov reviews probing limitations and argues for controls, complexity-aware metrics, and interventions for stronger claims.
- Warstadt et al. on NPIs show that probing should be interpreted alongside behavioral and minimal-pair methods rather than treated as a self-sufficient diagnostic.
- Kim et al. on function-word comprehension show that probing-style challenge tasks can reveal objective-specific grammatical strengths without amounting to a full theory of competence.
- the cluster supports a cautious picture of neural NLP systems as containing extractable linguistic structure, not a settled claim that they use explicit linguistic rules.

## Topic Map
- Core concepts: [[../concepts/Probing Classifiers|Probing Classifiers]], [[../concepts/Structural Probes|Structural Probes]], [[../concepts/Sentence Embedding Probing|Sentence Embedding Probing]], [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]], [[../concepts/Representation Geometry|Representation Geometry]]
- Relevant analysis: [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- Source set: probing and BERT sources plus the NMT morphology extension listed below

## Details
[[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Belinkov]] is the cluster's methodological anchor: it supplies the evidence standard that keeps probe results framed as extractability claims unless stronger controls or interventions are present. [[../sources/Source - Analysis Methods in Neural Language Processing|Belinkov and Glass's survey]] broadens that methodological picture by situating probing among a wider family of neural NLP analysis methods and by emphasizing that different tools justify different strengths of inference. [[../sources/Source - A Primer in BERTology|Rogers et al.]] then turn a large early BERT-analysis literature into one readable checkpoint, making clear both how much had been learned and how much still depended on indirect evidence. The main division of labor is now explicit: [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]] handles the graded evidential ladder, while this overview maps the literature families that generate those claims.

[[../sources/Source - What You Can Cram Into a Single Vector|Conneau et al.]] establish sentence-level probing tasks, [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Hewitt and Manning]] test a narrower geometric syntax hypothesis, and [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Tenney et al.]] plus [[../sources/Source - What Does BERT Learn About the Structure of Language|Jawahar et al.]] extend the cluster into layerwise BERT analysis. [[../sources/Source - Open Sesame|Lin et al.]] sharpen the hierarchy-versus-linearity question inside BERT itself, while [[../sources/Source - Visualizing and Measuring the Geometry of BERT|Coenen et al.]] add a geometric view of semantic and syntactic structure that is richer than standard probe accuracy alone. [[../sources/Source - What Do NMT Models Learn About Morphology|Belinkov et al. on NMT morphology]] broadens the cluster historically and architecturally without changing its main question.

The cluster boundary with [[Induction Heads and In-Context Learning Overview]] should remain explicit. Neural NLP probing asks what information is readable from representations under controlled probes or related analyses. The induction-head cluster asks what transformer circuits implement behavior and what causal evidence supports that claim.

Adjacent evaluation work now sharpens this cluster from the outside. [[../sources/Source - Assessing BERT's Syntactic Abilities|Assessing BERT's Syntactic Abilities]] and [[../sources/Source - Targeted Syntactic Evaluation of Language Models|Targeted Syntactic Evaluation of Language Models]] do not belong to probing proper, but they provide controlled competence tests that help interpret what probe-style extractability claims should and should not be taken to show. [[../sources/Source - Investigating BERT's Knowledge of Language|Warstadt et al. on NPIs]] make that methodological point explicit by comparing probing directly with acceptability, minimal-pair, and cloze-style evidence on one linguistic phenomenon.

[[../sources/Source - Probing What Different NLP Tasks Teach Machines about Function Word Comprehension|Kim et al. on function-word comprehension]] extend that caution in a different direction. By holding architecture fixed while varying pretraining objective, they show that probing-style challenge tasks can expose distinct grammatical strengths across objectives without licensing a single global claim that one encoder "has" or "lacks" function-word understanding.

## Related Pages
- [[Linguistic Competence and Limitations Overview]]
- [[Induction Heads and In-Context Learning Overview]]
- [[../concepts/Probing Classifiers|Probing Classifiers]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]

## Sources
- [[../sources/Source - What Do NMT Models Learn About Morphology|Source - What Do NMT Models Learn About Morphology]]
- [[../sources/Source - Analysis Methods in Neural Language Processing|Source - Analysis Methods in Neural Language Processing]]
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Source - Probing Classifiers Promises Shortcomings and Advances]]
- [[../sources/Source - A Primer in BERTology|Source - A Primer in BERTology]]
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Source - A Structural Probe for Finding Syntax in Word Representations]]
- [[../sources/Source - What You Can Cram Into a Single Vector|Source - What You Can Cram Into a Single Vector]]
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Source - BERT Rediscovers the Classical NLP Pipeline]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]
- [[../sources/Source - Open Sesame|Source - Open Sesame]]
- [[../sources/Source - Visualizing and Measuring the Geometry of BERT|Source - Visualizing and Measuring the Geometry of BERT]]
- [[../sources/Source - Investigating BERT's Knowledge of Language|Source - Investigating BERT's Knowledge of Language]]
- [[../sources/Source - Probing What Different NLP Tasks Teach Machines about Function Word Comprehension|Source - Probing What Different NLP Tasks Teach Machines about Function Word Comprehension]]

## Open Questions
- Which probing standards should the wiki apply before treating a claim as strong evidence?
- How much of the BERT-era probing literature transfers to current LLMs?
- How much of the NMT morphology evidence transfers from LSTM encoder-decoder systems to transformer NMT?
- Which future sources genuinely bridge linguistic probing and mechanistic interpretability, rather than merely sharing an interpretability label?
