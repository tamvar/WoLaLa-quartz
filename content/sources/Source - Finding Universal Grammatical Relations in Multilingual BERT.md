---
title: Source - Finding Universal Grammatical Relations in Multilingual BERT
type: source
status: active
updated: 2026-07-27
ingestion_depth: brief
tags:
  - source
  - brief
  - theoretical-linguistics
  - multilinguality
  - bert
---

## Summary
Ethan A. Chi, John Hewitt, and Christopher D. Manning argue that multilingual BERT encodes grammatical relations in a way that can be aligned across typologically different languages. The paper matters for WoLaLa because it turns multilingual transfer into a theory-facing question: not just whether mBERT works across languages, but whether its internal geometry supports a partially language-general representation of grammatical relations. That makes it useful to [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4) and, more cautiously, to [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1).

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is a strong multilingual bridge because it asks a narrower and more linguistically interpretable question than generic cross-lingual benchmark work. If grammatical relations occupy partially aligned directions across languages in mBERT, then multilingual pretraining is not only memorizing task-specific transfer tricks. It is learning some cross-linguistically reusable structural organization. For WoLaLa, that is useful evidence against simple claims that neural multilinguality is only superficial pattern matching.

At the same time, the paper should not be overstated. Evidence that grammatical relations can be recovered or aligned inside mBERT is not evidence that the model has discovered linguistic universals in the stronger theoretical sense, nor does it show that the model's internal organization matches human grammatical theory one-to-one. Its main value is that it creates a disciplined middle ground between dismissing multilingual neural models as structure-free and treating them as straightforward confirmations of universal grammar.

## Limitation Or Open Question
The main caution is inferential scale. Recoverable cross-lingual regularities in representation space do not by themselves establish explanatory adequacy, human-like grammatical knowledge, or a settled theory of universals. The open question is which kinds of cross-linguistic alignment are robust enough to matter for theoretical linguistics rather than only for multilingual engineering.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - BERT Is Not an Interlingua|Source - BERT Is Not an Interlingua]]
- [[../sources/Source - On the Multilingual Capabilities of Very Large-Scale English Language Models|Source - On the Multilingual Capabilities of Very Large-Scale English Language Models]]

## Source Identification
- Authors: Ethan A. Chi, John Hewitt, and Christopher D. Manning
- Title: *Finding Universal Grammatical Relations in Multilingual BERT*
- Year: 2020
- Source type: conference paper
- Publication: *Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics*, pages 5564-5577
- DOI: `10.18653/v1/2020.acl-main.493`

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2020.acl-main.493/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/2020.acl-main.493)
