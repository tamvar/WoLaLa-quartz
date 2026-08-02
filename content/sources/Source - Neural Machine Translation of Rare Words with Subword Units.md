---
title: Source - Neural Machine Translation of Rare Words with Subword Units
type: source
status: active
updated: 2026-07-26
ingestion_depth: brief
tags:
  - source
  - brief
  - subword
  - tokenization
  - nmt
---

## Summary
Rico Sennrich, Barry Haddow, and Alexandra Birch argue that neural machine translation can handle open-vocabulary behavior more effectively by decomposing rare words into subword units rather than relying only on fixed vocabularies and dictionary backoff. The paper is a key historical bridge for WoLaLa's tokenization strand because it helps explain why subword segmentation became such a central design choice in later language models. It is less about LLMs directly than about a now-basic representational compromise between word-level meaning and character-level flexibility.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]]. It matters because tokenization choices shape what counts as a linguistic unit for a model, and that in turn affects later claims about morphology, lexical structure, multilinguality, and generalization. The paper is therefore useful historical scaffolding for interpreting subword-based competence claims rather than taking tokenization as a neutral implementation detail.

## Limitation Or Open Question
The paper is about NMT rather than present frontier LLMs, so its relevance is architectural and historical rather than directly evidential about current models. The open question is whether subword segmentation should still be treated as the best compromise now that strong byte- and character-level alternatives exist.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - ByT5|Source - ByT5]]

## Source Identification
- Authors: Rico Sennrich, Barry Haddow, and Alexandra Birch
- Title: *Neural Machine Translation of Rare Words with Subword Units*
- Year: 2016
- Source type: conference paper

