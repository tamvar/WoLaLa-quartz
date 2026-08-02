---
title: Source - The Chomsky Hierarchy
type: source
status: active
updated: 2026-08-02
ingestion_depth: brief
tags:
  - source
  - brief
  - formal-language-theory
  - grammar
  - computation
---

## Summary

Tim Hunter reinterprets the Chomsky hierarchy as a theory of categorization, substitution, and memory rather than only a ranking of string languages. Grammar is possible because a system treats some expressions as interchangeable while retaining distinctions relevant to combination. Too much memory reduces grammar to a list of complete expressions; too little produces unconstrained combination. The productive middle ground is selective forgetting: categories preserve exactly the information that affects what may combine next or around an expression.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## From Rewriting Systems to Memory

The hierarchy classifies restrictions on rewriting grammars. Type 0 systems are unrestricted and computationally equivalent in power to Turing machines. Type 1 systems impose context-sensitive restrictions. Type 2, or context-free, grammars rewrite a single nonterminal independently of its surroundings. Type 3, or finite-state, grammars impose still tighter rule forms corresponding to finite-state automata. Each restriction changes which distinctions a grammar can preserve and therefore which patterns it can generate.

Hunter explains finite-state memory through forward sets: two prefixes are equivalent when they make the same continuations possible. A finite-state grammar has only finitely many such states, so it cannot preserve an unbounded number of distinctions such as the count needed for matching `aⁿbⁿ`. Context-free grammar gains power by categorizing infixes according to what may surround them. Constituents and nonterminals thus encode intersubstitutability in a more structurally flexible way.

Moving beyond context-free systems requires richer ways of composing or coordinating categorized expressions. The important lesson is not that natural languages should simply be placed at one rung. It is that formal restrictions expose relationships among generative capacity, representation, composition, and memory.

## Constrained Productivity

The chapter’s most general contribution is a continuum between memorization and indiscriminate generalization. A system that remembers every detail cannot generalize beyond stored expressions. A system that forgets every difference generalizes without constraint. A grammar supports constrained productivity by tracking some distinctions—categories, states, structural relations—while ignoring others.

This perspective separates a grammar’s extension from its mechanism. Different formalisms can generate the same strings while organizing representations and memory differently. Conversely, string-generating results can illuminate tree-based or other grammatical theories without reducing natural language to a set of strings.

## WoLaLa Interpretation

The memory interpretation is directly useful for thinking about neural language models, but it should not be overextended. A model’s success on formal-language tasks can reveal what distinctions its architecture and training preserve under controlled conditions. It does not automatically locate natural language on the classical hierarchy or identify the model’s representations with symbolic grammar states.

The chapter also sharpens the question of generalization: useful linguistic learning requires neither pure memorization nor unrestricted analogy, but an inductive bias about which differences matter. Formal-language tests are most informative when they manipulate memory demand, structural composition, and out-of-distribution length separately.

## Limitations

- The presentation deliberately emphasizes intuitions rather than providing a complete mathematical treatment.
- Classical weak generative capacity is not a full theory of linguistic representation, processing, or learnability.
- The chapter offers conceptual tools for model analysis but no direct experiments on neural networks.

## Related Pages

- [[Source - The Architecture of the Computation]]
- [[Source - Neural Networks and the Chomsky Hierarchy]]
- [[Source - Three Models for the Description of Language]]
- [[Source - Recursive Neural Networks Can Learn Logical Semantics]]

## Source Identification

- Author: Tim Hunter
- Chapter: “The Chomsky Hierarchy”
- Year: 2021
- Parent volume: *A Companion to Chomsky*
- Editors: Nicholas Allott, Terje Lohndal, and Georges Rey
- Publisher: Wiley-Blackwell / John Wiley & Sons
- Edition: First edition
- Chapter number: 5
- Printed pages: 74–95
- PDF pages: 91–112
- Parent source ID: `src_companion_chomsky_2021_container`
- Component source ID: `src_companion_chomsky_2021_ch05`
- DOI: `10.1002/9781119598732.ch5`

## Source Access

- Public source: [Wiley chapter page](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119598732.ch5)
- DOI: [DOI landing page](https://doi.org/10.1002/9781119598732.ch5)

## Open Questions

- Which formal-language tasks isolate memory architecture from training-distribution effects in neural models?
- How should tree-generating and representation-sensitive capacities supplement classical string-language comparisons?
