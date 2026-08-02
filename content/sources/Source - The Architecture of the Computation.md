---
title: Source - The Architecture of the Computation
type: source
status: active
updated: 2026-08-02
ingestion_depth: brief
tags:
  - source
  - brief
  - syntax
  - computation
  - minimalism
---

## Summary

David Adger analyzes syntactic theory as an architecture with three separable components: a device, a procedure, and a memory. Human syntax requires a procedure that builds unbounded hierarchical structures and relates form to meaning. Generative theories have repeatedly simplified the stated device—from separate phrase-structure and transformational systems to Merge—but a simpler operation can license more computations unless its use is restricted. Recent work therefore shifts explanatory pressure toward memory and locality.

## Strand Connections

- Primary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## Device, Procedure, and Memory

Adger begins from the persistent observation that linguistic form is hierarchical and combinatorial. A computational account must specify the symbols or structures being manipulated, the operations that manipulate them, and what the system retains while operating. Early generative grammar used phrase-structure rules to build an initial structure and transformations to alter it. Later GB architectures mapped structures to Logical Form and Phonetic Form while distributing restrictions across modules and filters.

Minimalism replaces these multiple construction systems with Merge. External Merge combines separate objects; Internal Merge reuses an object contained within an existing structure, yielding displacement. This unification removes a stipulated difference between structure building and transformation. Yet a bare definition of Merge can permit unwanted operations, including combinations of objects selected from different parts of a workspace. Simplicity of the operation is therefore not the same as restrictiveness of the resulting computation.

## Locality as Memory Minimization

The chapter explores an architectural alternative in which a computational procedure has tightly limited access to prior material. Dependencies are local because the system minimizes what remains active in memory; apparent long-distance dependencies arise when an item is deliberately retained across successive local steps. Where such retention is impossible, the dependency is blocked.

This reframes grammatical constraints as consequences of the relation among procedure and memory rather than as independent filters. It also explains why changing memory assumptions changes what an otherwise simple operation can do. Architectural explanation requires all three components, not only a named operation.

## WoLaLa Interpretation

This decomposition is a useful reverse-engineering template for language models. Describing a transformer as performing composition is insufficient unless an analysis specifies its representational objects, update procedure, and accessible memory. Conversely, finding a correlate of hierarchical structure does not show that the model implements Merge or Minimalist derivations.

The chapter suggests more precise comparisons: which dependencies remain local, what information must be maintained, how access changes with context length, and whether the same computation produces both ordinary and displaced structures. These questions connect behavioral evaluation to architectural explanation without assuming symbolic identity.

## Limitations

- The memory-based proposal is programmatic and does not settle all empirical locality phenomena.
- The chapter works inside generative syntactic assumptions and does not compare competing grammatical architectures systematically.
- Its relevance to neural models is inferential; no transformer experiments are reported.

## Related Pages

- [[Source - From the Origins of Government and Binding to the Current State of Minimalism]]
- [[Source - The Chomsky Hierarchy]]
- [[Source - Chomsky and Fodor on Modularity]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing]]

## Source Identification

- Author: David Adger
- Chapter: “The Architecture of the Computation”
- Year: 2021
- Parent volume: *A Companion to Chomsky*
- Editors: Nicholas Allott, Terje Lohndal, and Georges Rey
- Publisher: Wiley-Blackwell / John Wiley & Sons
- Edition: First edition
- Chapter number: 8
- Printed pages: 125–139
- PDF pages: 142–156
- Parent source ID: `src_companion_chomsky_2021_container`
- Component source ID: `src_companion_chomsky_2021_ch08`
- DOI: `10.1002/9781119598732.ch8`

## Source Access

- Public source: [Wiley chapter page](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119598732.ch8)
- DOI: [DOI landing page](https://doi.org/10.1002/9781119598732.ch8)

## Open Questions

- Can locality effects in language models be decomposed into representational, procedural, and memory constraints?
- Which empirical restrictions follow from memory minimization rather than language-specific filters?
