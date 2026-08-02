---
title: Source - Deep Contextualized Word Representations
type: source
status: active
updated: 2026-07-29
ingestion_depth: deep
tags:
  - source
  - deep
  - elmo
  - contextual-representations
  - pretraining
  - history
---

## Summary
Matthew Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark, Kenton Lee, and Luke Zettlemoyer introduce ELMo, contextualized word representations derived from a deep bidirectional language model. The paper is historically important for WoLaLa because it demonstrates that token meaning should be modeled as context-sensitive and task-adaptable rather than as a single static vector per word type. It also helps explain why later pretraining work shifted attention away from task-specific handcrafted features and toward reusable contextual encoders.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)

## Key Points
- ELMo builds token representations from the internal states of a large bidirectional language model rather than from static word-type embeddings.
- The paper argues that contextualization is needed both for polysemy and for richer syntactic-semantic signal.
- Downstream models improve when they can mix information from different internal layers of the pretrained network rather than using only the top state.
- The contribution is historically transitional: it is still based on recurrent language modeling, but it already treats large-scale pretraining as reusable linguistic infrastructure.
- The paper shows that contextual representations can improve a wide range of tasks without claiming that those gains amount to understanding or explanation.

## Details
Before ELMo, much NLP practice relied on static embeddings such as word2vec or GloVe, possibly supplemented by task-specific recurrent encoders. ELMo changes the picture by making the representation of a token a function of its sentence context and by exposing multiple internal layers of a pretrained model to downstream tasks. This matters because words do not behave like fixed containers of meaning. Their interpretation varies with local syntax, selectional context, discourse role, and lexical sense. ELMo treats that variability as a core representational requirement rather than a downstream afterthought.

The paper is also important methodologically. It shows that pretrained internal states can be mixed in task-specific ways, which encourages the later idea that models may distribute different kinds of linguistic information across layers. That provides a direct historical bridge to the BERT-analysis literature summarized in [[../sources/Source - A Primer in BERTology|A Primer in BERTology]]. It also helps explain why questions about where syntax, semantics, and polysemy live inside a network became central in the first place.

For WoLaLa, ELMo is not mainly a performance story. Its value is that it reframes word representation as context-sensitive, layered, and reusable. That puts it at a crucial point in the methodological path from classical distributional embeddings to transformer-era language models. It therefore belongs in the historical and competence genealogy even though later architectures quickly surpassed it.

## Interpretation
ELMo should be read as a foundational contextual-representation source rather than as a full theory of language. It shows that powerful contextual token modeling can be learned from large corpora and transferred broadly, but it does not by itself settle what kinds of linguistic structure are represented or how deeply those representations support semantics and reasoning. Its importance is to make those later questions possible in a new form.

## WoLaLa Relevance
This source primarily supports [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] and secondarily [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]]. It is especially useful for:

- marking the pre-BERT transition from static word embeddings to contextualized token representations;
- explaining why later probing work cares about layerwise linguistic structure;
- showing how transfer learning in NLP began to depend on reusable pretrained language representations.

## Limitation Or Open Question
ELMo is a recurrent contextual model rather than a transformer, so it does not answer later questions about attention-only architectures or in-context learning. The continuing question is which of its apparent linguistic gains came from contextualization in general and which depended on the specific biLM setup that later models replaced.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling Overview]]
- [[../sources/Source - A Primer in BERTology|Source - A Primer in BERTology]]
- [[../sources/Source - BERT|Source - BERT]]
- [[../sources/Source - T5|Source - T5]]

## Source Identification
- Authors: Matthew E. Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark, Kenton Lee, and Luke Zettlemoyer
- Title: *Deep Contextualized Word Representations*
- Year: 2018
- Source type: conference paper
- Publication: *Proceedings of NAACL-HLT 2018*

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/N18-1202/)
