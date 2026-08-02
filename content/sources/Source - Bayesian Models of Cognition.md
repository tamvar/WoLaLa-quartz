---
title: Source - Bayesian Models of Cognition
type: source
status: active
updated: 2026-07-25
ingestion_depth: deep
tags:
  - source
  - deep
  - cognition
  - bayesian-models
  - reverse-engineering
---

## Summary
*Bayesian Models of Cognition: Reverse Engineering the Mind* is a broad 2024 volume edited by Thomas L. Griffiths, Nick Chater, and Joshua B. Tenenbaum. This source page treats it selectively rather than comprehensively. The book matters for WoLaLa because it presents Bayesian cognitive science not as a narrow statistical trick but as a large reverse-engineering program for explaining learning, concept formation, causal inference, rational action, language processing, and structured thought. Used selectively, it gives a strong methodological bridge between cognitive explanation and present debates about language models: what kind of structure must be represented, inferred, discovered, or learned for a system to count as a plausible model of language-capable intelligence?

## Selective Scope
This page does not summarize every chapter. It focuses on the parts of the volume most relevant to current WoLaLa questions:

- Bayesian cognitive science as reverse engineering
- hierarchical and nonparametric Bayesian modeling
- structured representations, concepts, and causal inference
- resource-rational analysis and bounded cognition
- language processing and language learning
- probabilistic programs, inference over programs, and language-of-thought style modeling

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Key Points
- The volume treats cognition as a reverse-engineering problem: explain intelligent behavior by specifying the latent hypotheses, representational structures, and inference procedures that could generate it.
- Bayesian models are presented as a family of explanatory tools for learning under uncertainty, not as a claim that minds literally implement one simple formula everywhere.
- The strongest WoLaLa payoff comes from the combination of structure and uncertainty. The book repeatedly argues that explanation requires identifying what sort of representational space a learner searches over, not only what outputs it eventually produces.
- Language is part of the core program rather than a peripheral application. The table of contents includes explicit treatment of language processing and language learning, logical representations, and probabilistic programs as a unifying language-of-thought style framework.
- The source is especially useful as a counterweight to scale-only interpretations of intelligence. It does not deny the value of broad statistical learning, but it insists that explanation often depends on structured priors, compositional hypotheses, and interpretable model classes.

## Details
The preface frames the book as both a snapshot and a defense of Bayesian cognitive science. Its organizing claim is that cognition can often be illuminated by identifying the hidden variables, hypothesis spaces, and inductive assumptions that let agents move from limited evidence to surprisingly rich beliefs and behaviors. That program is explicitly reverse-engineering in spirit: begin from what minds can do, then work backward toward computationally and explanatorily adequate models.

The visible table of contents shows that the volume ranges from foundations to applications. Early chapters cover Bayesian basics, then the book moves into hierarchical Bayesian models, nonparametric Bayesian models, neural-network relations, resource-rational analysis, theory of mind and inverse planning, intuitive physics, language processing and language learning, Bayesian inference over logical representations, probabilistic programs as a unifying language of thought, learning as Bayesian inference over programs, cognitive development, and the limits of inference. For WoLaLa, that breadth matters less as a reason to summarize everything than as evidence that the volume offers a coherent methodological bridge across several strands.

Two aspects are especially important. First, the volume insists that successful cognition often depends on the structure of the hypothesis space, not only on more data or more compute. This aligns with compact sources such as [[../sources/Source - How to Grow a Mind|How to Grow a Mind]], but the book gives a much wider field map. Second, the book keeps explanation and performance distinct. A model can match behavior in some domain without yet telling us which abstractions, causal assumptions, or compositional resources underwrite that success.

That distinction is highly relevant to language models. LLMs can display broad linguistic and inferential behavior, but the explanatory question remains open: are they best understood as search over richly structured implicit representations, as broad statistical compressors, as approximate program learners, or as something hybrid? The book does not answer that directly, but it supplies a vocabulary for asking the question more precisely. Chapters on language, logical representation, and probabilistic programs are especially useful for keeping alive the idea that linguistic or cognitive explanation may require explicit attention to structured inference rather than to output quality alone.

The volume also belongs naturally in the mind-design strand. Bayesian cognitive science is not only a theory of human thought; it is also a family of proposals about what kind of architecture can support robust generalization from limited evidence. In that sense it provides a constructive foil to [[../sources/Source - The Bitter Lesson|The Bitter Lesson]]. Sutton warns that knowledge-heavy hand design tends to lose to more general compute-leveraging methods. This volume shows why many cognitive scientists still think explanatory progress depends on identifying structured inductive constraints, whether hand-built, learned, or discovered by a more general system.

## Interpretation
This source should be read as a selective deep methodological anchor, not as a verdict that Bayesian cognitive science has already solved the relation between cognition and language models. Its main value is that it clarifies what a serious explanatory alternative to behavior-first interpretation looks like. The book keeps asking what latent structures, priors, and inferential resources make rich generalization possible. That is exactly the sort of question that current LLM debates can lose when they move too quickly from large-scale success to claims about understanding, reasoning, or human-like cognition.

## WoLaLa Relevance
This source primarily supports [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] and secondarily [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]]. It helps the wiki hold together several threads that are otherwise easy to separate:

- cognitive explanation versus performance matching
- structure-sensitive learning versus scale-only narratives
- reverse engineering the mind versus evaluating a benchmark system
- language learning as part of a wider theory of abstract concept formation and inference

It is also valuable because it can later support deeper comparison pages without forcing them yet. The source makes it easier to compare Bayesian cognitive science with scale-centered AI methodology, usage-based linguistic perspectives, and mechanistic reverse-engineering ambitions.

## Limitation Or Open Question
This is a large edited volume, and the current note is intentionally selective. It should not be read as a unified endorsement of every Bayesian approach or as a claim that the whole volume bears equally on WoLaLa. The main open question is how much of the book's explanatory program should be treated as a live alternative to current LLM interpretation, and how much should instead be mined selectively for specific tools, distinctions, or historical background.

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - How to Grow a Mind|Source - How to Grow a Mind]]
- [[../sources/Source - The Child as Hacker|Source - The Child as Hacker]]
- [[../sources/Source - The Bitter Lesson|Source - The Bitter Lesson]]

## Source Identification
- Editors: Thomas L. Griffiths, Nick Chater, and Joshua B. Tenenbaum
- Title: *Bayesian Models of Cognition: Reverse Engineering the Mind*
- Year: 2024
- Source type: edited volume
- Publication: MIT Press

## Source Access
- Public source: [MIT Press book page](https://mitpress.mit.edu/9780262049412/bayesian-models-of-cognition/)

## Open Questions
- Which chapters in the volume should later be split out for more focused comparison with language-model claims about abstraction, reasoning, or language learning?
- How much structured prior knowledge can modern large-scale models discover for themselves, and how much still needs to be specified to produce explanatory traction?
- Is the strongest contemporary role for Bayesian cognitive science contrastive, constructive, or mainly historical in relation to current LLM research?
