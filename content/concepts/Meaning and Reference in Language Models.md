---
title: Meaning and Reference in Language Models
type: concept
status: active
updated: 2026-04-26
tags:
  - concept
  - meaning
  - reference
  - philosophy-of-language
  - llms
---

## Summary
This concept page tracks a crucial WoLaLa distinction: claims about linguistic meaning, reference, grounding, and understanding should not be collapsed into one another. The literature sharpened here separates form-only learning, derivative meaning, usage-based distributional meaning, conceptual-role meaning, grounded referential success, limited agency, and language-guided world modeling.

## Key Points
- Source fact: [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that training on form alone cannot in principle yield meaning understood as a relation between form and communicative intent.
- Source fact: [[../sources/Source - Distributional Models of Word Meaning|Lenci]] argues that distributional evidence captures important aspects of lexical meaning, while also falling short of full inferential and compositional semantics.
- Source fact: [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] argue that distributional semantics remains a viable semantic research program, but only if it grows toward multimodality, incrementality, and inferential integration.
- Source fact: [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] argue that LM words may still refer if the training strings have the right natural histories and external links.
- Source fact: [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] argue that meaning may arise from conceptual role and internal relational structure even without direct reference.
- Source fact: [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] argue that referential grounding is the central grounding issue for LLMs, and that it can in some cases be achieved without requiring embodiment.
- Source fact: [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] argue that novel reference creates pressure to move beyond purely derivative library-like accounts of LLM semantics.
- Source fact: [[../sources/Source - From Word Models to World Models|Wong et al.]] propose a richer architecture in which language is translated into a probabilistic language of thought and used for structured world modeling.
- Interpretation: this literature supports keeping at least three claims distinct:
  - usage-sensitive semantic structure
  - referential contact
  - fuller language-guided understanding or world-informed reasoning

## Details
[[../sources/Source - Climbing Towards NLU|Bender and Koller]] supply the strongest explicit caution in the current batch. They distinguish linguistic form from meaning and communicative intent, and argue that systems trained only on form cannot by themselves learn the world-linked relation needed for strong meaning claims.

[[../sources/Source - Distributional Models of Word Meaning|Lenci]] complicates any simple dismissal of text-derived semantics. On his account, linguistic distributions are not irrelevant surface noise; they are a serious source of evidence about lexical meaning. At the same time, he treats compositionality and inference as major limits, so distributional success should not be mistaken for semantic completeness.

[[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] extend this point by directly answering contemporary critiques. Their position is that distributional semantics is not refuted by current limitations, but must be connected to better data, multimodality, and the inferential and interactive structure of communication.

[[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Skelac and Jandrić]] then sharpen what `use` means in this area. Their chapter argues that Word2vec genuinely realizes a context-sensitive picture of meaning, but only in a restricted sense: nearby lexical context is not yet the same as Wittgensteinian language use embedded in forms of life.

[[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] target a narrower question. They do not claim that language models thereby understand language in a rich human sense. Instead, they argue that the standard grounding objection is too crude: reference may depend on historical and social embedding rather than on rich internal beliefs or experiences.

[[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] separate meaning from reference in a different way again. Their claim is not mainly externalist but internal-relational: meaning depends on conceptual role, so the key empirical question is whether a model's representational geometry and state transitions instantiate the right kinds of structure.

[[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] refine the issue further by distinguishing grounding from stronger mental notions. Their argument implies that some disputes presented as all-or-nothing clashes over meaning may actually be narrower disputes about which world-linking relations are required.

[[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] then raise the pressure point of novel reference. If some outputs are better explained by limited agency than by derivative transmission alone, then the distinction between meaning, reference, grounding, and agency must be kept even sharper.

[[../sources/Source - From Word Models to World Models|Wong et al.]] move in a different direction again. They treat language and thought as distinct but interacting systems, and propose translating language into structured probabilistic representations that can support inference over world models.

Taken together, these sources argue against treating "meaning" as a single yes-or-no property. A model may have distributionally structured lexical content without full reference; may support reference without rich communicative understanding; or may need a richer architecture before stronger semantic claims become credible.

## Related Pages
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]
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
- Can a model refer without understanding in the stronger communicative-intent sense?
- Is derivative meaning best understood as a genuine semantic achievement, or only as borrowed content transmission?
- How much distributional or conceptual-role structure should count as meaning before grounding enters the picture?
- What kind of world-link or interaction would justify moving from reference claims to stronger meaning claims?
- How should language-guided reasoning architectures be distinguished from ordinary form-only LMs?
