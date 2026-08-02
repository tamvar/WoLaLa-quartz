---
title: Source - A Deep Learning Framework for Neuroscience
type: source
status: active
updated: 2026-07-27
ingestion_depth: deep
tags:
  - source
  - deep
  - neuroscience
  - deep-learning
  - reverse-engineering
  - methodology
---

## Summary
Richards, Lillicrap, Beaudoin, Bengio, Bogacz, Christensen, Clopath, Ponte Costa, de Berker, Ganguli, Gillon, Hafner, Kepecs, Kriegeskorte, Latham, Lindsay, Miller, Naud, Pack, Poirazi, Roelfsema, Sacramento, Saxe, Scellier, Schapiro, Senn, Wayne, Yamins, Zenke, Zylberberg, Therien, and Kording argue that systems neuroscience can benefit from adopting the same three design axes that organize deep learning: objective functions, learning rules, and architectures. Their claim is not that brains are literally deep networks, but that neuroscience should increasingly ask what optimization target a system serves, what architecture constrains it, and what learning process builds it. For WoLaLa, this is a foundational reverse-engineering bridge because it gives strand 8 and strand 7 a shared methodological vocabulary for comparing brains and artificial systems.

## Strand Connections

- Primary: [[../overviews/Neuroscientific Perspectives Overview|Neuroscientific Perspectives]] (strand 8)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Key Points
- The paper proposes that neuroscience should analyze systems in terms of objective functions, learning rules, and architectures.
- It treats deep learning as a productive source of computational hypotheses rather than as a literal template to be copied uncritically onto the brain.
- The framework is optimization-centered: understanding a system means asking what it is optimized to do, how it learns, and what structural constraints it has.
- The source matters for WoLaLa because it offers a principled way to compare model success, neural explanation, and reverse engineering without collapsing them into one thing.
- It is a methodological anchor rather than a direct language paper, but it bears directly on how language-model-to-brain comparisons should be interpreted.

## Details
The paper starts from a structural analogy between two research programs that often proceed separately. Systems neuroscience aims to explain how brains solve perceptual, cognitive, and motor tasks, while artificial intelligence designs systems that solve tasks under chosen constraints. In modern deep learning, three design elements have become especially central: the objective function, the learning rule, and the architecture. Richards and colleagues argue that these same three elements can organize neuroscience more productively than a narrow focus on unit-by-unit description alone.

That shift matters because it reframes what counts as explanation. A system is not fully understood merely because its local activity patterns are measured or because an input-output mapping has been fit. One also wants to know what the system is optimizing, what mechanisms of plasticity or training shape it, and what architectural organization constrains the possible solutions. In this respect the paper is methodologically close to strand-7 reverse-engineering work: it asks for decompositions that are abstract enough to travel across biological and artificial cases, but concrete enough to guide experimental inquiry.

For WoLaLa, the paper is useful even though it is not specifically about language. It helps discipline model-brain comparison claims by making clear what a serious neuroscience-relevant comparison would involve. Saying that a language model predicts neural data is not yet enough. One should also ask whether the model and the brain are plausibly aligned in the functions they optimize, the architectural constraints they operate under, and the learning processes that shaped them.

The source also pairs well with [[../sources/Source - Shared Computational Principles for Language Processing in Humans and Deep Language Models|Shared Computational Principles for Language Processing in Humans and Deep Language Models]] and [[../sources/Source - Deep Language Algorithms Predict Semantic Comprehension from Brain Activity|Deep Language Algorithms Predict Semantic Comprehension from Brain Activity]]. Those papers provide narrower language-specific alignment claims, while Richards and colleagues provide a broader framework for judging when such alignments begin to count as explanatory progress rather than mere correlation.

## Interpretation
This paper is best treated as a methodological anchor for model-brain and reverse-engineering work. It does not show that deep learning already explains the brain, and it does not imply that optimization language by itself settles questions of cognition or understanding. Its strength lies in specifying a productive research stance: compare systems at the level of objectives, learning, and architecture, and use those comparisons to generate tractable explanatory hypotheses.

That makes it especially valuable for strand 8, which remains intentionally skeletal. The paper expands the strand's methodological backbone without forcing a premature neuroscience subtopic split.

## Related Pages
- [[../overviews/Neuroscientific Perspectives Overview|Neuroscientific Perspectives Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - Shared Computational Principles for Language Processing in Humans and Deep Language Models|Source - Shared Computational Principles for Language Processing in Humans and Deep Language Models]]
- [[../sources/Source - Deep Language Algorithms Predict Semantic Comprehension from Brain Activity|Source - Deep Language Algorithms Predict Semantic Comprehension from Brain Activity]]
- [[../sources/Source - Parallel Distributed Processing Volume 2|Source - Parallel Distributed Processing Volume 2]]

## Source Identification
- Authors: Blake A. Richards, Timothy P. Lillicrap, Philippe Beaudoin, Yoshua Bengio, Rafal Bogacz, Amelia Christensen, Claudia Clopath, Rui Ponte Costa, Archy de Berker, Surya Ganguli, Colleen J. Gillon, Danijar Hafner, Adam Kepecs, Nikolaus Kriegeskorte, Peter Latham, Grace W. Lindsay, Kenneth D. Miller, Richard Naud, Christopher C. Pack, Panayiota Poirazi, Pieter Roelfsema, Joao Sacramento, Andrew Saxe, Benjamin Scellier, Anna C. Schapiro, Walter Senn, Greg Wayne, Daniel Yamins, Friedemann Zenke, Joel Zylberberg, Denis Therien, and Konrad P. Kording
- Title: "A deep learning framework for neuroscience"
- Year: 2019
- Source type: perspective article
- Publication: *Nature Neuroscience* 22(11), 1761-1770
- DOI: `10.1038/s41593-019-0520-2`

## Source Access
- Public source: [Nature Neuroscience article page](https://www.nature.com/articles/s41593-019-0520-2)
- DOI / publisher: [DOI landing page](https://doi.org/10.1038/s41593-019-0520-2)

## Open Questions
- How often do successful model-brain comparisons in language actually line up at the level of objective function rather than only at the level of representational fit?
- Which language-related neuroscience papers in the repository are strong enough to operationalize this framework more directly?
