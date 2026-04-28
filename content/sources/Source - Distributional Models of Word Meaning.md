---
title: Source - Distributional Models of Word Meaning
type: source
status: active
updated: 2026-04-25
tags:
  - source
  - distributional-semantics
  - meaning
  - philosophy-of-language
---

## Summary
Alessandro Lenci reviews distributional semantics as a usage-based model of lexical meaning built from linguistic co-occurrence patterns. The paper is a major pre-LLM anchor for the distributional side of this literature: it explains what distributional models can capture well, where they remain semantically coarse, and why richer accounts of meaning likely require integration with symbolic or experiential structure.

## Key Points
- Source fact: the paper presents distributional semantics as a usage-based model of meaning grounded in the distributional hypothesis that lexemes with similar contexts have similar meanings.
- Source fact: it reviews major design choices in distributional semantic models, including context type, weighting, explicit versus implicit vectors, and count versus prediction-based methods.
- Source fact: it argues that distributional models are especially strong for lexical similarity, semantic plasticity, and corpus-based analysis of usage.
- Source fact: it also argues that distributional models remain weak at fine-grained semantic relation discrimination, logical inference, and full semantic compositionality.
- Source fact: the paper ends by advocating a pluralist picture in which distributional statistics, extralinguistic experience, and symbolic structure are integrated rather than treated as mutually exclusive.

## Details
Lenci frames distributional semantics as a model of lexical meaning derived from usage. The core idea is that corpus distributions are not merely engineering features; they are evidence about semantic behavior. This makes distributional semantics relevant to WoLaLa not only as a technical precursor to embeddings, but as a substantive claim about how language use bears on meaning.

The review distinguishes major model families and parameter choices. It compares window-based, syntactic, and region-style context definitions; count-based matrix models and prediction models; and explicit co-occurrence vectors versus dense latent representations. Across these choices, Lenci treats the central question as semantic adequacy rather than leaderboard performance.

The paper is notably balanced about limits. Lenci argues that standard distributional models tend to recover broad semantic relatedness more easily than sharply typed lexical relations such as hypernymy or antonymy. He also presents compositionality as a major bottleneck: vector combination methods can be useful, but sentence-level meaning and inference are not straightforwardly captured by similarity in a vector space.

The closing position is not anti-distributional. Instead, Lenci argues for representational pluralism: distributional information matters, but human semantic competence likely depends on interaction between distributional, symbolic, and experiential resources.

## Synthesis / Interpretation
This source helps discipline both overclaiming and underclaiming. It supports taking distributional evidence seriously as evidence about meaning, while also resisting the jump from distributional success to a complete theory of meaning or inference.

It therefore sits in productive tension with both [[Source - Climbing Towards NLU|Bender and Koller]] and [[Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]]. Lenci provides a historically and linguistically grounded account of why usage patterns matter; the other papers argue over whether that kind of structure is enough for meaning, reference, or understanding in contemporary language models.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

## Source Identification
- Author: Alessandro Lenci
- Title: *Distributional Models of Word Meaning*

## Open Questions
- Which parts of the distributional-semantics tradition transfer cleanly to transformer-era language models, and which depend on a narrower lexical-semantic framing?
- Does representational pluralism support a hybrid LLM account, or does it show that text-only systems remain semantically incomplete?
