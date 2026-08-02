---
title: Source - On the Multilingual Capabilities of Very Large-Scale English Language Models
type: source
status: active
updated: 2026-07-25
ingestion_depth: brief
tags:
  - source
  - brief
  - multilinguality
  - zero-shot
  - gpt-3
---

## Summary
Jordi Armengol-Estape, Ona de Gibert Bonet, and Maite Melero investigate how far GPT-3's multilingual abilities extend when the model has been trained overwhelmingly on English. Focusing on Catalan as a low-resource case in GPT-3's pretraining mix, they report especially strong zero-shot performance on generative tasks, with weaker but still notable results on language-understanding tasks such as extractive question answering. The paper's core importance for WoLaLa is not just multilingual benchmarking. It is a theory-relevant bridge about transfer: broad language-model training can support meaningful crosslingual behavior even without dedicated multilingual training, but the resulting competence is uneven and task-sensitive. The authors also treat scale as a major variable in how far this transfer goes.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source primarily supports [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] and secondarily [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]]. It matters because multilingual transfer bears directly on what kinds of abstraction language models may acquire. For WoLaLa, the paper helps sharpen a live question: when an English-dominant model performs nontrivially in another language, does that support stronger claims about generalized linguistic structure, or does it mainly show broad but partial transfer under scale? The paper is most useful as a bridge source precisely because its answer is mixed.

## Limitation Or Open Question
The study is centered on GPT-3 and a Catalan-focused zero-shot setting, so it should not be generalized into a complete picture of multilingual competence. The open question is how far the observed transfer supports deeper theory claims about shared linguistic abstraction, rather than a narrower claim about large-scale crosslingual pattern reuse.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - BERT Is Not an Interlingua|Source - BERT Is Not an Interlingua]]

## Source Identification
- Authors: Jordi Armengol-Estape, Ona de Gibert Bonet, and Maite Melero
- Title: *On the Multilingual Capabilities of Very Large-Scale English Language Models*
- Year: 2022
- Source type: proceedings article
- Publication: *Proceedings of the Language Resources and Evaluation Conference* (LREC 2022), 3056-3068
- Note: the local repository copy is the 2021 arXiv preprint version; the work later appeared in the 2022 LREC proceedings.

## Source Access
- Public source: [LREC 2022 article page](https://lrec.elra.info/lrec2022-main-327)
- Earlier preprint: [arXiv abstract page](https://arxiv.org/abs/2108.13349)
