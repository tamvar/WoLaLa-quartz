---
title: Source - Distributional Memory
type: source
status: active
updated: 2026-07-31
ingestion_depth: brief
tags:
  - source
  - brief
  - distributional-semantics
  - lexical-semantics
  - corpus-methods
  - syntax-semantics
---

## Summary
Marco Baroni and Alessandro Lenci propose Distributional Memory as a general corpus-based framework that stores weighted word-link-word tuples in a third-order tensor and derives multiple semantic spaces from that shared structure. The paper is important because it pushes beyond a one-task-one-model view of distributional semantics. Instead of building separate distributional models for similarity, analogy, selectional preference, relation classification, or concept properties, it argues that one richer relational memory can support many of them. For WoLaLa, the source is a strong bridge between lexical semantics, relational structure, and theory-facing questions about what distributional representations can and cannot encode.

## Strand Connections

- Primary: [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language]] (strand 3)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## Key Points
- The paper rejects a narrow task-specific view of corpus semantics in favor of a shared multi-purpose representational substrate.
- Distributional Memory stores relational information as weighted word-link-word tuples rather than only as simple word-context counts.
- Different matrix slices derived from the tensor support different semantic tasks, including similarity, relation modeling, and selectional preference.
- The framework therefore expands what a distributional representation can plausibly be used for.
- For WoLaLa, it matters because it strengthens the case that distributional structure can encode richer semantic organization than bag-of-context similarity alone.

## Details
Baroni and Lenci begin from a practical and conceptual frustration. Much corpus-based semantics work had developed specialized models for specific tasks, as if similarity judgments, relation extraction, analogy solving, property prediction, and selectional preferences were unrelated problems. Distributional Memory argues that this fragmentation is unnecessary.

The proposed alternative is to extract rich distributional information once, in the form of a tensor whose entries encode word-link-word relations. From that common store, the system derives different views suited to different problems. This means that the same underlying corpus evidence can support both attributional and relational semantics, as well as property-like or predicate-argument uses.

That move matters conceptually because it broadens the meaning of distributional representation. The paper does not claim that semantics reduces fully to one tensor. But it does claim that a well-designed relational distributional memory can support a wider variety of semantically meaningful tasks than simpler models suggested.

## Interpretation
This source is a brief but important bridge note. It helps explain why later embedding and representation debates should not treat all distributional methods as equivalent to flat word-neighborhood similarity. Distributional Memory is still corpus-based and usage-derived, yet it aims to preserve structured relational information that matters for syntax-semantics interfaces and semantic inference tasks.

## Limits or Open Questions
The paper expands the reach of corpus semantics, but it does not by itself answer grounding, reference, or full compositional-understanding objections. Its strongest contribution is representational and methodological rather than philosophical.

## Related Pages
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - Distributional Models of Word Meaning|Source - Distributional Models of Word Meaning]]
- [[../sources/Source - Distributional Semantics|Source - Distributional Semantics]]

## Source Identification
- Authors: Marco Baroni and Alessandro Lenci
- Title: *Distributional Memory: A General Framework for Corpus-Based Semantics*
- Year: 2010
- Work type: journal article

