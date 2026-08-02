---
title: Source - A Systematic Assessment of Syntactic Generalization in Neural Language Models
type: source
status: active
updated: 2026-07-27
ingestion_depth: deep
tags:
  - source
  - deep
  - syntax
  - evaluation
  - competence
---

## Summary
Hu et al. provide one of the clearest large-scale tests of whether language-model perplexity tracks human-like syntactic generalization. It does not. Across 20 model-and-dataset conditions and 34 targeted English test suites, the paper finds that architecture matters more than training-corpus size for the syntactic behaviors examined, and that lower perplexity does not reliably predict better syntactic generalization. For WoLaLa, this is a major anchor because it separates broad predictive success from linguistically diagnostic success.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)

## Key Points
- The paper treats syntactic generalization as a targeted evaluation problem rather than a byproduct of generic language-model success.
- It compares model architecture and training-data size directly instead of assuming more data explains everything.
- It argues that perplexity and syntactic generalization can come apart in important ways.
- The paper scales targeted syntax evaluation by organizing many test suites in a common framework.
- Its results motivate tools such as [[../sources/Source - SyntaxGym|SyntaxGym]] and support a more discriminating notion of linguistic evaluation.

## Details
The paper's core question is simple but important: if a model gets better at next-word prediction in the broad sense measured by perplexity, should we expect it also to generalize more human-like on syntax? Hu et al. show that this expectation is too crude. Their experiments compare multiple architectures and training regimes on a battery of targeted syntactic tests rather than only on aggregate predictive metrics.

That design matters for WoLaLa because it operationalizes a distinction that recurs across the wiki: broad behavioral success is not the same thing as competence on theoretically revealing cases. The paper studies subject-verb agreement, filler-gap dependencies, and other syntactic constructions through carefully controlled contrasts. In doing so, it makes visible differences that generic benchmark summaries can hide.

One of the paper's strongest findings is that architecture matters more than corpus size for the testbed examined. Sequential models underperform some alternatives on syntactic generalization, and the relation between perplexity and syntax is not monotonic. This is important for present LLM debates because it pushes against the assumption that better broad predictive compression automatically yields better linguistic structure sensitivity.

The paper is also methodologically important. It helps normalize targeted syntactic evaluation as a scalable practice and therefore sits naturally beside [[../sources/Source - SyntaxGym|SyntaxGym]], which turns that practice into reusable infrastructure. Together they strengthen strand 1 by showing that competence claims require targeted diagnostics, not only impressive aggregate numbers.

## Interpretation
This source is a deep anchor for language-focused evaluation because it directly addresses one of the most persistent WoLaLa tensions: whether general language-model improvement should be taken as evidence of deeper linguistic competence. Hu et al. do not deny that broad training matters, but they show that the evaluation question must be asked more carefully and more structurally.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../sources/Source - SyntaxGym|Source - SyntaxGym]]
- [[../sources/Source - Neural Language Models as Psycholinguistic Subjects|Source - Neural Language Models as Psycholinguistic Subjects]]

## Source Identification
- Authors: Jennifer Hu, Jon Gauthier, Peng Qian, Ethan Wilcox, Roger P. Levy
- Title: "A Systematic Assessment of Syntactic Generalization in Neural Language Models"
- Year: 2020
- Source type: conference paper
- Publication: Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2020.acl-main.158/)
- Public source: [arXiv abstract page](https://arxiv.org/abs/2005.03692)

## Open Questions
- Which targeted syntactic evaluations from this paper remain most diagnostic for current large autoregressive models?
- How far can targeted syntax results be integrated with broader competence claims without collapsing back into perplexity-style summary metrics?
