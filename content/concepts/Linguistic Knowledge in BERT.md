---
title: Linguistic Knowledge in BERT
type: concept
status: active
updated: 2026-04-23
tags:
  - concept
  - bert
  - probing
  - linguistic-hierarchy
---

# Linguistic Knowledge in BERT

## Summary
Across the ingested probing sources, BERT appears to expose different kinds of linguistic information at different depths: lower layers tend to carry surface or phrase-level information, middle layers syntactic information, and higher layers more semantic or discourse-linked information. These are extractability claims, not automatic claims about causal use.

## Key Points
- Source fact: Hewitt and Manning report recoverable dependency-tree geometry from BERT representations.
- Source fact: Tenney et al. report a layerwise ordering resembling a classical NLP pipeline: POS, parsing, entities, semantic roles, then coreference.
- Source fact: Jawahar et al. report lower-layer phrase information, middle-layer syntactic information, upper-layer semantic information, and deeper-layer help for harder subject-verb agreement cases.
- Source fact: both Tenney et al. and Belinkov emphasize that probing observations do not by themselves establish how information is used in downstream predictions.

## Details
The current evidence points to a convergent but cautious picture. [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Hewitt and Manning]], [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Tenney et al.]], and [[../sources/Source - What Does BERT Learn About the Structure of Language|Jawahar et al.]] all find structured linguistic information in BERT, but they do so at different levels of granularity:
- structural probes focus on geometric recovery of parse distances and depths
- edge probing focuses on span and span-pair linguistic labels
- sentence-level probing tasks compare layers across broad linguistic properties
- agreement and TPDN analyses add tests for long-distance dependency and compositional structure

The agreement between these sources strengthens the claim that BERT representations are linguistically organized, but not the stronger claim that BERT reasons with explicit symbolic syntax.

This page should remain separate from the induction-head cluster. It summarizes layered linguistic extractability in BERT, not circuit-level explanations of in-context learning behavior.

## Related Pages
- [[Probing Classifiers]]
- [[Structural Probes]]
- [[Sentence Embedding Probing]]
- [[Representation Geometry]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]

## Sources
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Source - A Structural Probe for Finding Syntax in Word Representations]]
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Source - BERT Rediscovers the Classical NLP Pipeline]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Source - Probing Classifiers Promises Shortcomings and Advances]]

## Open Questions
- Which findings transfer to decoder-only LLMs?
- Which findings survive fine-tuning, instruction tuning, or RLHF-style post-training?
