---
title: Meaning, Reference, and Distributional Language Overview
type: overview
status: active
updated: 2026-04-26
tags:
  - overview
  - meaning
  - reference
  - distributional-language
  - wolala
---

# Meaning, Reference, and Distributional Language Overview

## Summary
This overview maps a WoLaLa strand focused on meaning, reference, and distributional language. It is not about generic LLM performance. It is about how language models bear on claims about meaning, grounding, understanding, agency, and the relation between language use, internal structure, and world modeling.

## Key Points
- Source-grounded finding: [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that form-only training is insufficient for meaning or understanding in the strong sense tied to communicative intent.
- Source-grounded finding: [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] argue that LM words may still refer if their training strings inherit the right natural histories.
- Source-grounded finding: [[../sources/Source - Distributional Models of Word Meaning|Lenci]] presents distributional semantics as a serious usage-based model of lexical meaning, but also emphasizes its limits for fine-grained relations, inference, and full compositionality.
- Source-grounded finding: [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] defend distributional semantics as a broad research program while arguing that richer data, multimodality, and inferential integration are needed to extend its semantic reach.
- Source-grounded finding: [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] argue that meaning may arise from conceptual role and internal relational structure even where direct reference is absent or incomplete.
- Source-grounded finding: [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] argue that the crucial grounding issue for LLMs is referential grounding, and that it may be achievable without treating embodiment as necessary.
- Source-grounded finding: [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] argue that novel reference pressures purely library-like interpretations of LLMs and may support attributing limited agency.
- Source-grounded finding: [[../sources/Source - From Word Models to World Models|Wong et al.]] propose a more structured architecture in which language is translated into a probabilistic language of thought for world modeling and reasoning.
- Synthesis: the literature supports a richer contrast between form-only skepticism, derivative meaning, grounding, externalist reference, conceptual-role meaning, usage-based distributional semantics, limited-agency interpretations, and constructive world-model integration.

## Topic Map
- Core concept: [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- Core analysis: [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]

## Details
This strand sits alongside questions about linguistic probing and mechanistic explanation, but its central question is different: what kinds of semantic or cognitive claims language-model success does or does not justify.

[[../sources/Source - Climbing Towards NLU|Bender and Koller]] set the cluster's caution standard. They argue that progress on form-sensitive tasks should not be redescribed as meaning or understanding unless the relation to communicative intent and world grounding is made explicit.

[[../sources/Source - Distributional Models of Word Meaning|Lenci]] supplies the historical and linguistic anchor for why language-use statistics matter at all. The paper treats distributional semantics as a real model of lexical meaning, while also emphasizing that semantic relatedness, compositionality, and inference create limits for purely distributional accounts.

[[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] broaden that picture into a larger program. They explicitly engage current objections about grounding and understanding, defend distributional approaches against blanket dismissal, and argue for multimodal, incremental, and inference-aware extensions rather than abandonment.

[[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] narrow the dispute. They do not defend a broad understanding claim, but they do argue that reference may be easier than many critics assume, because reference can depend on external historical relations rather than rich internal grasp.

[[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] push further in a different direction. Rather than defending reference first, they argue that meaning may be grounded in conceptual role: the organization of internal representational states and their relations to one another. This makes them a bridge between distributional traditions and contemporary LLM semantics.

[[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] sharpen the grounding debate by distinguishing several notions often run together. Their paper suggests that grounding should be asked about more narrowly than many critiques suppose, and that referential grounding may already be partially available in some models.

[[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] push on a different seam in the cluster. They ask whether library-like metaphors are enough to explain LLM semantics, or whether cases of novel reference push us toward attributing a limited form of agency.

[[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Skelac and Jandrić]] make the philosophy-of-language bridge explicit. They argue that Word2vec inherits an important context-sensitive picture of meaning from Wittgenstein and Firth, while also showing that vector context is narrower than full language-game use.

[[../sources/Source - From Word Models to World Models|Wong et al.]] provide the most ambitious constructive proposal in this set. Instead of treating next-token prediction as sufficient, they connect language to structured probabilistic reasoning over world models.

This strand should remain distinct from neighboring literatures on linguistic probing and mechanistic explanation of context-sensitive behavior. Those literatures ask what information is extractable from representations and what mechanisms implement specific behaviors. This strand asks what kinds of semantic or cognitive claims those successes do or do not justify.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]

## Sources
- [[../sources/Source - Climbing Towards NLU|Source - Climbing Towards NLU]]
- [[../sources/Source - Do Language Models Refer|Source - Do Language Models Refer]]
- [[../sources/Source - From Word Models to World Models|Source - From Word Models to World Models]]
- [[../sources/Source - Distributional Models of Word Meaning|Source - Distributional Models of Word Meaning]]
- [[../sources/Source - Distributional Semantics|Source - Distributional Semantics]]
- [[../sources/Source - Meaning Without Reference in Large Language Models|Source - Meaning Without Reference in Large Language Models]]
- [[../sources/Source - The Vector Grounding Problem|Source - The Vector Grounding Problem]]
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Source - Are LLMs Like Libraries or Librarians]]
- [[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Source - Meaning as Use from Wittgenstein to Google's Word2vec]]

## Open Questions
- Which semantic claim is best supported by current evidence: derivative meaning, grounded reference, conceptual-role meaning, limited agency, or language-guided world modeling?
- Does this strand still hang together as one topic, or will the distributional-semantics side eventually justify a separate but linked subtopic?
