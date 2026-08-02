---
title: Source - ByT5
type: source
status: active
updated: 2026-07-26
ingestion_depth: brief
tags:
  - source
  - brief
  - byte-level
  - tokenization
  - multilinguality
---

## Summary
Linting Xue, Aditya Barua, Noah Constant, Rami Al-Rfou, Sharan Narang, Mihir Kale, Adam Roberts, and Colin Raffel present ByT5 as a byte-to-byte alternative to token-based pretraining. The source matters for WoLaLa because it turns a background engineering choice into a theory-relevant one: if strong language modeling can be done directly over bytes, then many claims that depend on fixed tokenization schemes need to be phrased more carefully.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]]. It is especially useful because it tests whether the benefits traditionally attributed to subword tokenization can be matched or replaced by byte-level models that avoid handcrafted segmentation boundaries. That bears directly on multilinguality, robustness, and the interpretation of learned linguistic units.

## Limitation Or Open Question
The paper does not by itself settle whether byte-level models are theoretically preferable, only whether they are practically competitive. The open question is when token-free modeling clarifies linguistic competence and when it simply shifts complexity elsewhere.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - CharBERT|Source - CharBERT]]
- [[../sources/Source - Neural Machine Translation of Rare Words with Subword Units|Source - Neural Machine Translation of Rare Words with Subword Units]]

## Source Identification
- Authors: Linting Xue, Aditya Barua, Noah Constant, Rami Al-Rfou, Sharan Narang, Mihir Kale, Adam Roberts, and Colin Raffel
- Title: *ByT5: Towards a Token-Free Future with Pre-trained Byte-to-Byte Models*
- Year: 2022
- Source type: conference paper

