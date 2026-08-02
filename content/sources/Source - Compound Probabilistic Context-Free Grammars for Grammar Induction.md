---
title: Source - Compound Probabilistic Context-Free Grammars for Grammar Induction
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - grammar-induction
  - pcfg
  - syntax
  - latent-structure
---

## Summary
Yoon Kim, Chris Dyer, and Alexander Rush revisit unsupervised grammar induction by using a compound PCFG whose rule probabilities are modulated by a continuous latent variable. The paper matters for WoLaLa because it offers a modern probabilistic route back into explicit latent syntax: rather than abandoning grammar induction in favor of black-box sequence modeling, it asks how far improved parameterization and inference can recover hierarchical structure from raw text.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## WoLaLa Relevance
This source is valuable as a bridge between classical formal grammar and contemporary neural learning. It suggests that explicit latent tree structure remains a live modeling object, even inside neural and variational frameworks. That keeps open a more structured alternative to the idea that successful language modeling should simply bypass grammar induction altogether.

## Key Points
- The model uses a continuous latent variable to relax some strict independence assumptions of standard PCFGs.
- Inference combines amortized variational methods with exact dynamic programming over trees.
- The paper improves unsupervised parsing results for English and Chinese.
- It shows that explicit grammar induction remains technically active within modern neural NLP.

## Limitation Or Open Question
Improved unsupervised parsing does not by itself show that induced trees match linguistically explanatory structure in the stronger theoretical sense. The source is therefore best read as a modern structural-modeling bridge rather than as a decisive vindication of any one grammar theory.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - Three Models for the Description of Language|Source - Three Models for the Description of Language]]
- [[../sources/Source - Neural Networks and the Chomsky Hierarchy|Source - Neural Networks and the Chomsky Hierarchy]]

## Source Identification
- Authors: Yoon Kim, Chris Dyer, and Alexander M. Rush
- Title: "Compound Probabilistic Context-Free Grammars for Grammar Induction"
- Year: 2019
- Source type: conference paper
- Publication: ACL 2019

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/P19-1228/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/P19-1228)
