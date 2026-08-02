---
title: Source - Recursive Neural Networks Can Learn Logical Semantics
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - semantics
  - logical-inference
  - recursive-networks
  - compositionality
---

## Summary
Samuel Bowman, Christopher Potts, and Christopher Manning test whether tree-structured recursive neural networks can learn representations rich enough to support logical inference, including entailment, contradiction, recursion, and quantification. For WoLaLa, the paper matters because it is a bounded but important counterexample to the idea that neural sentence models can only capture shallow distributional similarity: it explicitly asks whether learned representations can support structure-sensitive semantic reasoning.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language]] (strand 3)

## WoLaLa Relevance
The paper is useful because it narrows a big theoretical question into a testable case. Rather than asking whether neural models understand meaning in general, it asks whether recursive representations can support formal semantic relations under controlled logical conditions and then on a naturalistic entailment task.

## Key Points
- Tree-structured neural networks are tested on logical relations such as entailment and contradiction.
- The controlled artificial-data experiments target recursion, quantification, and natural-logic style inference.
- The models perform competitively on SICK as well as on the synthetic logical tasks.
- The paper is an early bridge between formal semantics and learned neural sentence representations.

## Limitation Or Open Question
Success on these tasks does not show that neural models solve open-ended semantics or explain human meaning. The source is best treated as a focused existence proof that some neural architectures can learn more structure-sensitive semantic behavior than a shallow baseline picture would predict.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]
- [[../sources/Source - Neural Networks and the Chomsky Hierarchy|Source - Neural Networks and the Chomsky Hierarchy]]
- [[../sources/Source - Lexical Semantics with Large Language Models|Source - Lexical Semantics with Large Language Models]]

## Source Identification
- Authors: Samuel R. Bowman, Christopher Potts, and Christopher D. Manning
- Title: "Recursive Neural Networks Can Learn Logical Semantics"
- Year: 2015
- Source type: workshop paper
- Publication: Proceedings of the 3rd Workshop on Continuous Vector Space Models and their Compositionality

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/W15-4002/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/W15-4002)
