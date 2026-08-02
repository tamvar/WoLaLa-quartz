---
title: Source - A Probabilistic Model of Syntactic and Semantic Acquisition
type: source
status: active
updated: 2026-07-27
ingestion_depth: deep
tags:
  - source
  - deep
  - acquisition
  - syntax
  - semantics
  - probabilistic-modeling
---

## Summary
Kwiatkowski, Goldwater, Zettlemoyer, and Steedman present an incremental probabilistic learner that acquires syntactic and semantic structure from child-directed utterances paired with candidate meanings. Using a CCG framework, a non-parametric Bayesian grammar model, and online variational learning, they argue that a learner can acquire compositional syntax-semantics mappings without strong language-specific innate structure or batch training procedures. For WoLaLa, the paper matters as a compact but substantial acquisition bridge between probabilistic modeling, formal grammar, and debates about learnability.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## Key Points
- The learner is designed to be incremental and comparatively cognitively plausible rather than a convenience-optimized batch system.
- It learns both syntactic and semantic structure from utterances plus meaning candidates rather than from pre-labeled parses.
- The paper uses probabilistic CCG rather than a richly pre-specified principles-and-parameters framework.
- The result is offered as a counterexample to strong claims that statistical learners cannot capture abrupt acquisition-like changes or compositional syntax-semantics mapping.
- The paper is relevant to WoLaLa because it shows one way probabilistic learning and explicit compositional structure can be combined rather than opposed.

## Details
The paper is built around a classic acquisition problem: children hear utterances in context, but they do not receive explicit parse trees or word-to-meaning dictionaries. Kwiatkowski and colleagues model this by pairing child-directed utterances with sets of candidate meaning representations. The learner must infer the lexicon, syntactic categories, and parsing model that best explain the data.

What makes the paper especially useful is the combination of commitments it tries to hold together. It does not assume a highly language-specific innate grammar, but it also does not reduce language learning to unconstrained sequence statistics. Instead, it works inside a formal compositional framework, probabilistic Combinatory Categorial Grammar, and uses Bayesian machinery to learn both syntax and semantics incrementally.

That combination matters for WoLaLa because the paper is neither a simple nativist defense nor a simple anti-structure argument. It is a concrete model showing how rich compositional targets can be learned with relatively general probabilistic resources, given the right representational setup. In this respect it sits usefully between stronger poverty-of-the-stimulus rhetoric and looser appeals to pure large-scale statistical learning.

The source also belongs in a broader methodological lineage. It treats learnability claims as something that should be tested with explicit models rather than settled by intuition alone. That aligns it with later work, including [[../sources/Source - What Artificial Neural Networks Can Tell Us About Human Language Acquisition|What Artificial Neural Networks Can Tell Us About Human Language Acquisition]], that calls for model-based pressure on acquisition arguments.

## Interpretation
This paper is an important bridge source because it shows that probabilistic learning can coexist with explicit syntactic and semantic structure. For WoLaLa, that makes it a useful corrective to debates that present formal grammar and statistical learning as mutually exclusive options. It also provides a stronger acquisition example than vague talk about models "learning from data," because it specifies the representational and inferential machinery in detail.

Its limits are also important. The learner uses structured meaning representations and a formal grammar framework that are themselves substantial assumptions. So the source does not prove that human language acquisition is easy or fully domain-general. What it does show is that strong anti-statistical arguments need to engage with explicit hybrid models rather than with a caricature of statistical learning.

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - What Artificial Neural Networks Can Tell Us About Human Language Acquisition|Source - What Artificial Neural Networks Can Tell Us About Human Language Acquisition]]
- [[../sources/Source - Bayesian Models of Cognition|Source - Bayesian Models of Cognition]]

## Source Identification
- Authors: Tom Kwiatkowski, Sharon Goldwater, Luke Zettlemoyer, and Mark Steedman
- Title: "A Probabilistic Model of Syntactic and Semantic Acquisition from Child-Directed Utterances and their Meanings"
- Year: 2012
- Source type: conference paper
- Publication: *Proceedings of EACL 2012*, pages 234-244

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/E12-1024/)

## Open Questions
- Which of the model's structured assumptions are psychologically realistic, and which are mainly computational conveniences?
- How far can this style of hybrid probabilistic-structural model scale to broader acquisition phenomena?
