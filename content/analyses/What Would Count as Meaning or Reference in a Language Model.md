---
title: What Would Count as Meaning or Reference in a Language Model
type: analysis
status: active
updated: 2026-04-26
tags:
  - analysis
  - meaning
  - reference
  - llms
  - wolala
---

## Summary
The sources considered here support a more differentiated picture than a simple three-way contrast. Fluency or task success does not by itself establish meaning. But semantic assessment also should not be reduced to direct reference alone. The strongest supported conclusion is that meaning claims need to be graded across derivative meaning, distributional structure, grounding, conceptual role, reference, agency-like behavior, and world-linked understanding.

## Key Points
- [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that form-only training cannot, in principle, learn meaning understood as a relation between form and communicative intent.
- [[../sources/Source - Distributional Models of Word Meaning|Lenci]] argues that distributional structure captures important aspects of lexical meaning, while remaining limited for inference and compositionality.
- [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] argue that distributional semantics should be extended rather than abandoned, especially through multimodality and inferential integration.
- [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] argue that reference may not require the internal beliefs, experiences, or capacities often assumed by grounding objections.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] argue that meaning may be partially constituted by conceptual role and internal relational structure even without settled reference.
- [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] argue that referential grounding is the crucial grounding notion for LLMs, and that it may arise through fine-tuning or even, in limited domains, pre-training alone.
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] argue that derivative-meaning models of LLMs face a challenge from novel reference and may underexplain agent-like semantic behavior.
- [[../sources/Source - From Word Models to World Models|Wong et al.]] propose a path beyond form-only models by translating language into a structured probabilistic language of thought for world-guided inference.
- the strongest supported move is not "LLMs understand language" but "the space of semantic claims needs to be disaggregated."

## Evidence
The skeptical side of the batch is clear. [[../sources/Source - Climbing Towards NLU|Bender and Koller]] give an explicit argument that meaning is not recoverable from form alone, because meaning involves communicative intent and world-linked use. On this view, performance on apparently meaning-sensitive tasks may still reflect successful exploitation of form.

The distributional side shows why the issue is not exhausted by that critique. [[../sources/Source - Distributional Models of Word Meaning|Lenci]] treats language-use statistics as semantically informative rather than as meaningless residue. His review supports a serious usage-based semantics, but one that remains coarse and incomplete. That matters for WoLaLa because it blocks both a naive dismissive view and a naive triumphalist one.

[[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] reinforce that point at a larger scale. Their view is that the limitations of current distributional models do not show that the program is misguided; they show that richer forms of data, learning, and inference are needed if the program is to climb farther.

[[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Skelac and Jandrić]] add a useful clarification here. Even if one accepts a meaning-as-use tradition, it does not follow that any contextual embedding model has captured meaning in the full Wittgensteinian sense. Word2vec operationalizes one thin slice of use, not the whole social-practical structure of language games.

The referential side is also clear, but narrower. [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] focus on reference rather than full understanding. Their argument is that if reference depends on external historical relations rather than rich internal grasp, then text-trained systems may still produce genuinely referring uses.

[[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] offer a different positive route. They argue that internal conceptual organization may already underwrite meaning in some sense, even where reference is absent, partial, or not yet demonstrated. That puts pressure on any criterion that treats direct grounding as the only route to semantics.

[[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] make that pressure more precise. Their contribution is to separate grounding from several other things it is often made to cover. If referential grounding is the relevant standard, then some anti-LLM arguments may overstate what is missing.

[[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] complicate matters differently. They argue that some LLM outputs may be derivatively meaningful in a library-like way, but that novel reference creates a harder problem. At that point, the best explanation may begin to look intentional rather than merely transmissive.

The constructive side comes from [[../sources/Source - From Word Models to World Models|Wong et al.]], who treat language as an interface into richer cognitive representations. Their proposal suggests that one route to stronger meaning claims is not to inflate what next-token models already do, but to connect language to explicit world modeling and inference.

## Interpretation
Semantic claims about language models should be phrased in a graded way:
- Safest: the model captures or exploits statistical regularities in linguistic form.
- Stronger in a limited transmissive sense: the model produces derivatively meaningful outputs that inherit content from human linguistic practice.
- Stronger: the model captures distributionally meaningful lexical structure.
- Stronger again: the model achieves some form of referential grounding.
- Stronger again but theoretically contested: the model instantiates conceptual-role structure that supports meaning-like organization.
- Stronger but still narrower than full understanding: some outputs may sustain reference under an externalist account.
- Stronger still and more controversial: some behavior may be best explained by limited agency-like states such as beliefs, desires, and intentions.
- Strongest and least supported by these sources alone: the model understands language in a grounded, communicative, human-analogous sense.

The constructive lesson is also important. If stronger semantic claims are to be made, these sources suggest they will more plausibly come from architectures that integrate language with explicit world models, reasoning procedures, or social-interaction structures than from string prediction alone.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

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
- Is reference enough to count as a genuine semantic achievement for WoLaLa purposes, or only one component of it?
- Is referential grounding stronger than derivative meaning in the right way for WoLaLa's purposes, or are they different dimensions rather than a simple ranking?
- When should distributional or conceptual-role structure count as semantic evidence rather than only as a precursor to semantics?
- Which future sources best test whether language can be integrated with world models in a way that supports stronger understanding claims?
