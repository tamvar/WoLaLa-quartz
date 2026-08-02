---
title: Source - Word Meaning in Minds and Machines
type: source
status: active
updated: 2026-07-27
ingestion_depth: deep
tags:
  - source
  - deep
  - semantics
  - cognition
  - grounding
  - word-meaning
---

## Summary
Lake and Murphy compare psychological theories of word meaning with contemporary NLP representations and argue for a mixed verdict. Distributional and neural models capture some important human similarity judgments, but they remain too dependent on text statistics and too weakly connected to goals, beliefs, perception, action, and flexible compositional conceptual structure. For WoLaLa, this is a major anchor because it gives a careful, non-polemical account of exactly where text-trained models illuminate human semantics and where they still fall short.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language]] (strand 3)

## Key Points
- The paper distinguishes engineering success in NLP from success as a psychological theory of semantics.
- Current models do relatively well on word similarity and association, but that is not enough for a full account of human meaning.
- Human word meaning is tied to beliefs, desires, goals, perception, action, and flexible concept composition.
- The paper argues that stronger grounding and more human-like conceptual organization are needed if models are to count as theories of psychological semantics.
- It is a productive middle position: neither dismissive of NLP progress nor willing to equate distributional success with human semantic competence.

## Details
The paper asks a question that is central to WoLaLa but often handled too quickly: when should progress in NLP count as progress in modeling human meaning? Lake and Murphy's answer is deliberately selective. They acknowledge that contemporary language models and earlier distributional approaches capture some aspects of human semantic behavior surprisingly well, especially in tasks involving similarity, association, and lexical proximity. Those are real achievements and should not be dismissed.

But the paper insists that these successes cover only part of what a theory of word meaning must explain. Human semantics is not exhausted by co-occurrence structure or by performance on downstream NLP tasks. Word meanings are tied to perception and action, to goals and beliefs, to event knowledge, and to the capacity to combine concepts flexibly in context. A system that is powerful at text prediction may therefore succeed at some semantic proxies while still failing to model the conceptual organization that makes human meaning possible.

This gives the paper a useful shape for WoLaLa. It is not a simple anti-LLM document. It allows that engineering-oriented NLP can be highly successful without being psychologically realistic, and it leaves open the possibility that more grounded or conceptually richer architectures could narrow the gap. The critique is targeted: current systems remain overly text-bound and insufficiently grounded.

The source also helps bridge strands 3 and 5. It sits between philosophy-of-language and cognitive-semantics disputes about meaning, while also bearing directly on how language-model evidence should be interpreted. It complements [[../sources/Source - Distributional Models of Word Meaning|Distributional Models of Word Meaning]] and [[../sources/Source - Meaning Without Reference in Large Language Models|Meaning without reference in large language models]] by clarifying why distributional success may be genuine but still incomplete.

## Interpretation
This is one of the clearest current sources for a moderate position on language models and meaning. It avoids the false choice between saying that text-trained models tell us nothing about semantics and saying that strong performance already amounts to a theory of human conceptual meaning. Its practical value for WoLaLa is that it specifies which semantic capacities are better modeled by current systems and which remain weakly captured.

The paper also sharpens a recurrent methodological distinction. A model can be useful as an engineering system, useful as a source of behavioral comparison, and still inadequate as a cognitive theory. That layered distinction is important across many WoLaLa debates.

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]
- [[../sources/Source - Distributional Models of Word Meaning|Source - Distributional Models of Word Meaning]]
- [[../sources/Source - Distributional Semantics|Source - Distributional Semantics]]
- [[../sources/Source - Meaning Without Reference in Large Language Models|Source - Meaning without Reference in Large Language Models]]

## Source Identification
- Authors: Brenden M. Lake and Gregory L. Murphy
- Title: "Word meaning in minds and machines"
- Year: 2023 journal version; local preprint version 2021
- Source type: journal article
- Publication: *Psychological Review* 130(2), 401-431

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2008.01766)
- DOI / publisher: [APA PsycNet article page](https://doi.org/10.1037/rev0000297)

## Open Questions
- Which components of human semantic competence are most plausible to approximate with text-trained models alone?
- What kinds of perceptual, embodied, or goal-directed grounding would most improve the psychological realism of current NLP systems?
