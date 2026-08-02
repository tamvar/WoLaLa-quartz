---
title: Source - The Roles of English in Evaluating Multilingual Language Models
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - multilinguality
  - evaluation
  - methodology
  - prompting
---

## Summary
Wessel Poelman and Miryam de Lhoneux distinguish two very different uses of English in multilingual language-model evaluation: English as an interface for eliciting better task performance, and English as a natural language whose understanding is itself under test. Their argument is methodological rather than anti-multilingual. The problem is that mixed-prompt or English-mediated evaluation can improve scores while making it less clear whether a model actually understands the target language. For WoLaLa, the paper matters because it turns a common multilingual practice into an explicit evidential caution.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## WoLaLa Relevance
This source is valuable because it draws a clean distinction between multilingual evaluation as task engineering and multilingual evaluation as evidence about language understanding. If a benchmark uses English instructions or English-heavy prompts to stabilize performance, the result may still be useful for application design, but it becomes weaker evidence about competence in the target language. That makes the paper a good bridge between strand 6 methodology and strand 4 questions about what multilingual performance should count for theoretically.

The paper is especially useful next to multilingual competence sources such as [[Source - Language Models are Multilingual Chain-of-Thought Reasoners]] and [[Source - Deep Subjecthood|Deep Subjecthood]]. Those sources ask what multilingual models can do or represent; Poelman and de Lhoneux ask how easily evaluation design can blur what exactly is being tested.

## Key Points
- The paper distinguishes English as an interface from English as an object of natural-language understanding.
- It argues that multilingual prompting practices often optimize task performance rather than target-language understanding.
- Mixed-language prompts can therefore confound what multilingual benchmark success means.
- The paper recommends shifting multilingual evaluation toward setups that test language understanding more directly and less English-mediated convenience.

## Limitation Or Open Question
The paper is a position paper rather than a large empirical benchmark study. Its strength is conceptual clarification, not a definitive quantitative alternative. The open question is which multilingual evaluation designs best preserve comparability across languages without falling back on English as a hidden scaffold.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - Language Models are Multilingual Chain-of-Thought Reasoners|Source - Language Models are Multilingual Chain-of-Thought Reasoners]]
- [[../sources/Source - Deep Subjecthood|Source - Deep Subjecthood]]

## Source Identification
- Authors: Wessel Poelman and Miryam de Lhoneux
- Title: *The Roles of English in Evaluating Multilingual Language Models*
- Year: 2025
- Source type: conference position paper
- Publication: *Proceedings of the Joint 25th Nordic Conference on Computational Linguistics and 11th Baltic Conference on Human Language Technologies (NoDaLiDa/Baltic-HLT 2025)*, pages 492-498

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2025.nodalida-1.53/)
- Public source: [arXiv abstract page](https://arxiv.org/abs/2412.08392)
