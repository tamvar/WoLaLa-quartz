---
title: Source - BERT
type: source
status: active
updated: 2026-07-28
ingestion_depth: deep
tags:
  - source
  - deep
  - bert
  - bidirectional
  - pretraining
  - syntax
---

## Summary
Jacob Devlin, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova introduce BERT as a deeply bidirectional pretrained Transformer that can be fine-tuned with minimal architectural change across a wide range of NLP tasks. Its core technical move is masked language modeling, paired in this version with next-sentence prediction, which allows the model to condition on both left and right context during pretraining. For WoLaLa, the paper matters because BERT became the main empirical object for a large wave of linguistic-probing, syntactic-evaluation, and transferability arguments about what pretrained models know about language structure.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## Key Points
- BERT replaces purely left-to-right pretraining with masked language modeling, enabling bidirectional contextual representations.
- The paper argues that broad pretraining can support both sentence-level and token-level tasks through simple fine-tuning.
- BERT is historically decisive because it made pretrained Transformer encoders the default object of linguistic probing and syntactic evaluation.
- The model's success does not directly answer whether it represents linguistic structure in a theory-relevant way, but it makes that question unavoidable.
- BERT also serves as the background against which multilingual BERT, XLM-R, and later encoder-style transfer results are interpreted.

## Details
The immediate technical point of BERT is simple: contextual word representations should not be built only from left-to-right prediction. By masking tokens inside a sentence and training the model to recover them, BERT can use both left and right context to build its representations. This design choice proved powerful across question answering, natural-language inference, and many token-level tasks.

Its broader importance for WoLaLa lies elsewhere. BERT became one of the main test cases for asking whether strong benchmark success correlates with syntactic knowledge, hierarchical structure, transferable linguistic information, and layer-specific organization. Many of the repository's existing probing sources use BERT precisely because it offered striking empirical success while leaving open the theoretical interpretation of that success.

This makes BERT a hinge between engineering and theory. On the one hand, it helps show that large gains in NLP can come from generic pretraining rather than task-specific architecture design. On the other hand, its very success generated a wave of questions about whether such systems merely exploit surface statistics or whether they encode enough structure to pressure older anti-statistical arguments in linguistics.

## Interpretation
BERT should not be treated as a direct theory of human linguistic cognition. But it is a crucial empirical counterpoint to any view that powerful linguistic behavior requires explicit symbolic grammar machinery in the model's architecture. It is therefore one of the central sources for the strand-4 question: what follows when successful language models do not resemble classical linguistic formalisms, yet still support impressive structure-sensitive behavior?

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Source - BERT Rediscovers the Classical NLP Pipeline]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]
- [[../sources/Source - How Multilingual Is Multilingual BERT|Source - How Multilingual Is Multilingual BERT]]

## Source Identification
- Authors: Jacob Devlin, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova
- Title: "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding"
- Year: 2019
- Source type: conference paper / arXiv preprint
- Publication context: NAACL-HLT 2019

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/1810.04805)
- DOI / publisher: [NAACL paper PDF](https://aclanthology.org/N19-1423.pdf)

## Open Questions
- Which BERT behaviors genuinely depend on hierarchical structure rather than strong local heuristics?
- How much of the later `BERT knows syntax` literature is really about BERT, and how much is about the probing methods applied to it?
