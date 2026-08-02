---
title: Source - Attention Is All You Need
type: source
status: active
updated: 2026-07-29
ingestion_depth: deep
tags:
  - source
  - deep
  - transformers
  - architecture
  - attention
  - history
---

## Summary
Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, and Illia Polosukhin introduce the Transformer as a sequence model built entirely around attention, without recurrence or convolution. The paper is historically decisive for WoLaLa because it changes the architectural starting point for nearly every later large language model. Its immediate experiments are machine translation and constituency parsing, not general language understanding, but the paper matters because it makes a new kind of language-capable system scalable, parallelizable, and comparatively unconstrained by hand-built sequential biases.

## Strand Connections

- Primary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)
- Secondary: [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling]] (strand 9)

## Key Points
- The paper replaces recurrent and convolutional sequence-processing cores with self-attention plus positional encoding.
- Multi-head attention lets the model attend to different relational patterns in parallel rather than forcing all sequence information through one hidden-state stream.
- The authors argue that the new architecture is both more parallelizable and better at capturing long-range dependencies than earlier seq2seq systems.
- The paper's empirical successes are translation and parsing, but its deeper importance is architectural: it provides the template that later pretrained language models scale up.
- The source should not be mistaken for a theory of linguistic competence or cognition. It is an architecture paper whose long-run theoretical relevance comes from what later work built on top of it.

## Details
The paper's central move is strikingly simple in retrospect: sequence transduction does not require recurrence if pairwise token relations can be modeled directly through attention. The Transformer keeps an encoder-decoder design, but its core operations are self-attention, cross-attention, feedforward blocks, residual connections, and positional encodings. That bundle yields faster training and stronger parallelization than RNN-heavy systems, while also improving performance on the translation tasks the paper studies.

For WoLaLa, the paper matters less as a benchmark win than as an architectural hinge. It helps explain why later LLM debates look the way they do. Once attention-based models became the default language backbone, older assumptions about what sort of inductive bias a successful language system must contain became less secure. The paper therefore belongs beside later sources like [[../sources/Source - BERT|BERT]], [[../sources/Source - T5|T5]], and [[../sources/Source - Language Models are Few-Shot Learners|Language Models are Few-Shot Learners]] as part of the methodological history that made present competence, scaling, and mechanistic questions possible.

The source also matters for the mind-design strand because it exemplifies a recurring WoLaLa pattern: an apparently engineering-driven design change can later become theoretically important because it alters what kinds of representational and behavioral questions are worth asking. The paper does not itself claim that attention solves meaning, explanation, or human-like cognition. But once the architecture became dominant, those questions had to be asked about systems with very different internal organization from classical symbolic or recurrent models.

## Interpretation
This paper should be read as a foundational architectural source, not as a standalone argument about language or intelligence. Its long-run significance lies in enabling a family of models whose behavior then became the object of WoLaLa's central disputes. In that sense it is historical and methodological at once: it marks the moment when attention-based sequence modeling became the main hardware of later arguments about competence, scale, interpretability, and understanding.

## WoLaLa Relevance
This source primarily supports [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] and secondarily [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling]]. It is especially useful for:

- explaining why later LLMs share a common architectural backbone;
- distinguishing architecture from interpretation, since the paper changes the former without settling the latter;
- locating modern language-model debates in a specific post-2017 historical shift rather than treating current systems as conceptually inevitable.

## Limitation Or Open Question
The paper's evidence is still narrow relative to what later users wanted from Transformers. It demonstrates strong translation and parsing performance, but it does not by itself establish broad linguistic competence, semantic understanding, or cognitive plausibility. A continuing question for WoLaLa is which later claims about model behavior depend on the architecture itself and which depend more on scale, data, training objective, or post-training.

## Related Pages
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling Overview]]
- [[../sources/Source - BERT|Source - BERT]]
- [[../sources/Source - T5|Source - T5]]
- [[../sources/Source - Language Models are Few-Shot Learners|Source - Language Models are Few-Shot Learners]]
- [[../sources/Source - The Bitter Lesson|Source - The Bitter Lesson]]

## Source Identification
- Authors: Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, and Illia Polosukhin
- Title: *Attention Is All You Need*
- Year: 2017
- Source type: conference paper
- Publication: *Advances in Neural Information Processing Systems 30 (NeurIPS 2017)*

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/1706.03762)
- DOI / publisher: [NeurIPS proceedings page](https://papers.neurips.cc/paper/7181-attention-is-all-you-need)
