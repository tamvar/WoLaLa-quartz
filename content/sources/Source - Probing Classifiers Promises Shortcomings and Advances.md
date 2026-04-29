---
title: Source - Probing Classifiers Promises Shortcomings and Advances
type: source
status: active
updated: 2026-04-23
tags:
  - source
  - probing
  - interpretability
---

## Summary
Yonatan Belinkov's 2021 Computational Linguistics squib reviews probing classifiers as a method for analyzing neural NLP representations. It is a methodological anchor for the topic: probing can show that a property is extractable from representations, but ordinary probe accuracy alone does not establish that the original model uses that property.

## Key Points
- a probing classifier maps an intermediate representation from an original model to a target property, often a linguistic property such as part of speech, morphology, syntax, or sentence length.
- the paper separates the original task/model/dataset from the probing task/classifier/dataset, making clear that probe results depend on all of these choices.
- the review identifies major methodological concerns: baselines, control tasks, probe complexity, correlation vs. causation, dataset effects, and the need to predefine probed properties.
- proposed improvements include control tasks, control functions, selectivity, minimum description length, accuracy-complexity trade-offs, parameter-free probes, and interventions.
- the paper argues that better-controlled probing can support relative claims about extractability, while causal claims require interventions or related evidence.

## Details
Belinkov frames probing as a useful but nontrivial analysis framework. A successful probe may indicate that information is present, readable, or extractable, but these notions are often conflated. The paper stresses that high probe accuracy may reflect the probe's own capacity or memorization rather than the representation's linguistic structure.

Important controls include random or simpler representation baselines, skyline models, control tasks with randomized labels, control functions, and control datasets. The review also distinguishes probing for information in a representation from showing that the original model uses that information to make predictions.

## Interpretation
This source should constrain interpretation of the other probing sources. Claims such as "BERT encodes syntax" or "sentence embeddings store tense" should be read as extractability claims unless the source includes stronger causal or behavioral evidence.

This source is the evidence-policy anchor for probing-oriented pages. It helps keep probing distinct from mechanistic-induction-head claims, where the main question is not readout quality but mechanism and causal importance.

## Related Pages
- [[../concepts/Probing Classifiers|Probing Classifiers]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]

## Source Identification
- Author: Yonatan Belinkov
- Title: *Probing Classifiers: Promises, Shortcomings, and Advances*

## Open Questions
- Which probe controls should be required before treating an interpretability claim as strong evidence?
- How should "encoded", "extractable", "used", and "causally relevant" be distinguished in future discussions?
