---
title: Linguistic Competence and Limitations Overview
type: overview
status: active
updated: 2026-07-24
tags:
  - overview
  - strand-1
  - competence
  - limitations
  - wolala
---

## Summary

This strand tracks what language models do or do not appear to know about language. It gathers evidence about syntactic structure, lexical behavior, multilinguality, tokenization, linguistic evaluation, and failure modes without treating any one technical literature as the whole strand.

## Scope

This overview is the top-level map for Linguistic Competence and Limitations (strand 1). It includes both behavioral and representation-focused evidence about linguistic competence, while keeping distinct the neighboring questions of semantic interpretation, mechanistic explanation, and broader cognition.

The existing probing cluster is a major subordinate map rather than a replacement for the strand:

- [[Neural NLP Probing Overview]]

Mechanistic work on induction heads is also relevant where it bears on context-sensitive linguistic behavior, but its main home remains [[Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7):

- [[Mind Design and Reverse Engineering Overview]]
- [[Induction Heads and In-Context Learning Overview]]

## Central Questions

- What kinds of linguistic structure are extractable from language-model representations?
- Which competence claims survive stronger evidence standards, controls, or cross-task comparison?
- How far do current competence results extend across syntax, morphology, lexical semantics, multilinguality, and discourse-sensitive behavior?
- Which limitations look like genuine linguistic limits, and which reflect evaluation design?

## Principal Subtopics

- probing and structural evidence about linguistic information in representations
- BERT-era layerwise studies of syntax and linguistic hierarchy
- sentence embedding and representation geometry work
- multilingual competence and transfer
- tokenization, character-level, and subword-sensitive competence
- limits on self-knowledge, robustness, and generalization

## Major Positions or Debates

- extractability versus actual deployed competence
- probing as evidence about structure versus probing as an artifact of flexible readout
- whether strong benchmark or grammatical-judgment performance supports human-like linguistic generalization
- whether multilingual and token-free models strengthen or weaken claims about abstract linguistic knowledge

## Current WoLaLa Coverage

Coverage is substantial but uneven.

- Strongest existing subordinate map: [[Neural NLP Probing Overview]]
- Existing concept pages:
  - [[../concepts/Probing Classifiers|Probing Classifiers]]
  - [[../concepts/Structural Probes|Structural Probes]]
  - [[../concepts/Sentence Embedding Probing|Sentence Embedding Probing]]
  - [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]]
  - [[../concepts/Representation Geometry|Representation Geometry]]
- Existing analysis:
  - [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- Existing bridge sources already represented elsewhere in the wiki:
  - [[../sources/Source - Dissociating Language and Thought in Large Language Models|Dissociating Language and Thought in Large Language Models]]
  - [[../sources/Source - Language Models Mostly Know What They Know|Language Models Mostly Know What They Know]]

Current coverage is strongest on probing, BERT, and evidence standards. Multilingual, tokenization, and broader failure-mode coverage are present mainly as indexed candidates rather than deeply integrated notes.

## Representative Sources

- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Probing Classifiers: Promises, Shortcomings, and Advances]] — `existing_deep`; foundational; central; high. Methodology anchor for cautious interpretation of probing evidence.
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|A Structural Probe for Finding Syntax in Word Representations]] — `existing_deep`; foundational; central; high. Core syntax-focused structural-evidence source.
- [[../sources/Source - What You Can Cram Into a Single Vector|What You Can Cram Into a Single Vector]] — `existing_deep`; foundational; supporting; high. Establishes sentence-level probing tasks across surface, syntactic, and semantic properties.
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|BERT Rediscovers the Classical NLP Pipeline]] — `existing_deep`; foundational; central; high. Major layerwise competence map for BERT.
- [[../sources/Source - What Does BERT Learn About the Structure of Language|What Does BERT Learn About the Structure of Language]] — `existing_deep`; foundational; central; high. Strong structure-focused complement to Tenney et al.
- [[../sources/Source - What Do NMT Models Learn About Morphology|What Do NMT Models Learn About Morphology]] — `existing_deep`; bridge; supporting; medium. Extends competence questions beyond BERT to NMT morphology.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Dissociating Language and Thought in Large Language Models]] — `existing_deep`; critical; central; high. Separates formal linguistic competence from broader functional language use.
- [[../sources/Source - Language Models Mostly Know What They Know|Language Models Mostly Know What They Know]] — `existing_deep`; recent; supporting; medium. Adds bounded self-evaluation and confidence calibration to competence assessment.
- *Linguistic knowledge and transferability of contextual representations* — `index_only`; bridge; supporting; high. Natural extension of the current probing/BERT thread.
- *BERT is not an interlingua* — `index_only`; critical; supporting; high. Candidate multilingual bridge on whether shared representations imply deeper cross-lingual linguistic structure.
- *On the Multilingual Capabilities of Very Large-Scale English Language Models* — `index_only`; recent; supporting; medium. Candidate for multilingual competence without dedicated multilingual training.
- *What does BERT look at?* — `index_only`; supporting; supporting; medium. Probing-adjacent candidate for attention and representation analysis.
- *What do you learn from context?* — `index_only`; supporting; supporting; medium. Context-sensitive competence candidate adjacent to the probing cluster.
- *Fine-grained Analysis of Sentence Embeddings* — `index_only`; supporting; supporting; medium. Extends the sentence-embedding part of the strand.
- *Analysis Methods in NLP* — `index_only`; survey; supporting; medium. General methods background for evaluating competence claims.
- *Subword Language Modelling* — `index_only`; bridge; supporting; medium. Tokenization-sensitive competence candidate.
- *ByT5-token-free models* — `index_only`; recent; supporting; medium. Token-free candidate relevant to whether competence depends on subword segmentation.
- *charbert* — `index_only`; supporting; supporting; low. Character-level alternative relevant to tokenization and representation questions.

## Gaps and Next Priorities

- multilingual competence is still represented mostly by inventory entries rather than wiki synthesis
- tokenization and character-level threads are visible but not yet mapped into a dedicated subtopic
- competence limits beyond probing and calibration remain thinner than the syntax-focused material
- discourse, pragmatics, and richer evaluation design remain much thinner than syntax and probing
- the next deep ingests for this strand should probably come from the multilingual or linguistic-theory bridge candidates rather than from more probing papers

## Related Strands and Pages

- [[Critical and Skeptical Perspectives Overview]]
- [[Meaning, Reference, and Distributional Language Overview]]
- [[Theoretical Linguistics and Language Models Overview]]
- [[Mind Design and Reverse Engineering Overview]]
- [[Neural NLP Probing Overview]]
- [[Induction Heads and In-Context Learning Overview]]
