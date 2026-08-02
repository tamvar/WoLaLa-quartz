---
title: What Would Count as Meaning or Reference in a Language Model
type: analysis
status: active
updated: 2026-08-02
tags:
  - analysis
  - meaning
  - reference
  - llms
  - wolala
---

## Summary
The sources considered here support a differentiated evidential picture. Fluency or task success does not by itself establish meaning. But semantic assessment also should not be reduced to direct reference alone. The strongest supported conclusion is that claims about meaning or reference need to be tested separately across formal competence, functional competence, distributional structure, conceptual role, grounding, reference, derivative meaning, agency-like behavior, and world-linked understanding.

## Key Points
- [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that form-only training cannot, in principle, learn meaning understood as a relation between form and communicative intent.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] show why formal competence and broader functional competence must be separated.
- [[../sources/Source - Distributional Models of Word Meaning|Lenci]], [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]], and [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] keep distributional or conceptual-role meaning distinct from stronger reference claims.
- [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]], [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]], and [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] show that grounding, reference, derivative meaning, and limited agency are not the same issue.
- [[../sources/Source - Mapping Language Models to Grounded Conceptual Spaces|Patel and Pavlick]] provide a bounded positive case where a text-trained model can be aligned to a grounded conceptual domain with only a small amount of world-linked supervision.
- [[../sources/Source - From Word Models to World Models|Wong et al.]] provide the clearest constructive path toward stronger meaning claims.
- the strongest supported move is not "LLMs understand language" but "the space of semantic claims needs to be disaggregated."

## Evidential Questions

### Which claim is the evidence meant to support?

The four Companion chapters add a prior diagnostic step. Before ranking evidence as weak or strong, identify its target.

- Evidence that a model distinguishes ambiguous structures, tracks lexical constraints, or composes interpretations bears on internal semantic organization. [[../sources/Source - Chomsky on Meaning and Reference|Pietroski]] shows why this target need not be defined through fixed extensions.
- Evidence that outputs are reliably linked to objects, histories, or environments bears on reference. It does not follow merely from internal semantic sensitivity, and [[../sources/Source - Chomsky on Semantics|Glanzberg]] shows why truth-conditional interpretation remains an additional theoretical commitment.
- Evidence that a model disambiguates, enriches, or derives implicatures in context bears on pragmatic competence. [[../sources/Source - Chomsky and Pragmatics|Allott and Wilson]] make mindreading and overt communicative intention stronger claims than context sensitivity alone.
- Evidence that internal states coordinate perception, language, thought, and action around the same targets may support a representational explanation. [[../sources/Source - Chomsky and Intentionality|Collins and Rey]] show that theorist-relative representation, causal sensitivity, and genuine intentional content remain competing interpretations.

This structure is not a ladder on which every higher item entails the lower ones. A system may exhibit substantial internal semantic organization without settled reference, or participate in externally anchored reference without human-like pragmatic or intentional organization.

### What defeats a simple fluency-based inference?

- [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that meaning tied to communicative intent is not recoverable from form alone.
- [[../sources/Source - The Generative AI Paradox|West et al.]] show that generation can exceed understanding.
- [[../sources/Source - Human and Machine Language Understanding|Wang et al.]] show that `understanding` is itself discipline-relative.

Together these sources show that fluent output or task success is not enough.

### What counts as semantic organization short of full reference?

- [[../sources/Source - Distributional Models of Word Meaning|Lenci]] and [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] support usage-based semantic structure.
- [[../sources/Source - Lexical Competence|Marconi]] clarifies inferential versus referential competence.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] support a conceptual-role route.
- [[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Skelac and Jandrić]] caution that thin contextual use is not yet full social use.

These sources support meaningful intermediate claims, but not all the same intermediate claim.

### What would support reference or grounding?

- [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] argue that reference may depend on external history rather than rich internal grasp.
- [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] narrow grounding to more specific referential standards.
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] show that derivative meaning may become unstable in cases of novel reference.
- [[../sources/Source - Mapping Language Models to Grounded Conceptual Spaces|Patel and Pavlick]] show that richer text-trained conceptual organization may make some grounded alignment tasks substantially easier once small world-linked examples are available.

This means reference questions should be asked separately from richer understanding questions.

### What would count as stronger understanding?

- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] distinguish formal from functional competence.
- [[../sources/Source - Language Models Mostly Know What They Know|Kadavath et al.]] add bounded self-evaluation as one limited positive result.
- selected chapters in [[../sources/Source - Mind Design III|Mind Design III]] show why predictive stance, computation, embodiment, and semantic explanation should not be collapsed.
- [[../sources/Source - From Word Models to World Models|Wong et al.]] provide the clearest constructive path toward a stronger architecture.

## Interpretation
Semantic claims about language models should be phrased along more than one dimension, not as one simple ladder.

One dimension concerns linguistic competence:
- safest: the model captures or exploits statistical regularities in linguistic form
- stronger on that same dimension: the model exhibits substantial formal linguistic competence across syntax-sensitive or abstraction-heavy language tasks
- distinct rather than simply higher: the model shows some degree of functional linguistic competence in domains such as discourse tracking, pragmatics, reasoning, or social inference

Another dimension concerns semantic status:
- inferential lexical-semantic structure without settled reference
- distributional semantic organization
- derivative meaning inherited from human linguistic practice
- conceptual-role meaning grounded in internal relational organization
- referential grounding or externalist reference
- limited agency-like semantic behavior
- grounded, communicative, human-analogous understanding

The constructive lesson matters as well. If stronger semantic claims are to be made, these sources suggest they will more plausibly come from architectures that integrate language with explicit world models, reasoning procedures, or social-interaction structure than from string prediction alone.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

## Sources
- [[../sources/Source - Chomsky on Meaning and Reference|Source - Chomsky on Meaning and Reference]]
- [[../sources/Source - Chomsky on Semantics|Source - Chomsky on Semantics]]
- [[../sources/Source - Chomsky and Pragmatics|Source - Chomsky and Pragmatics]]
- [[../sources/Source - Chomsky and Intentionality|Source - Chomsky and Intentionality]]
- [[../sources/Source - Climbing Towards NLU|Source - Climbing Towards NLU]]
- [[../sources/Source - Do Language Models Refer|Source - Do Language Models Refer]]
- [[../sources/Source - From Word Models to World Models|Source - From Word Models to World Models]]
- [[../sources/Source - Distributional Models of Word Meaning|Source - Distributional Models of Word Meaning]]
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Source - Dissociating Language and Thought in Large Language Models]]
- [[../sources/Source - Human and Machine Language Understanding|Source - Human and Machine Language Understanding]]
- [[../sources/Source - Mind Design III|Source - Mind Design III]]
- [[../sources/Source - The Generative AI Paradox|Source - The Generative AI Paradox]]
- [[../sources/Source - Language Models Mostly Know What They Know|Source - Language Models Mostly Know What They Know]]
- [[../sources/Source - Lexical Competence|Source - Lexical Competence]]
- [[../sources/Source - Distributional Semantics|Source - Distributional Semantics]]
- [[../sources/Source - Meaning Without Reference in Large Language Models|Source - Meaning Without Reference in Large Language Models]]
- [[../sources/Source - The Vector Grounding Problem|Source - The Vector Grounding Problem]]
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Source - Are LLMs Like Libraries or Librarians]]
- [[../sources/Source - Mapping Language Models to Grounded Conceptual Spaces|Source - Mapping Language Models to Grounded Conceptual Spaces]]
- [[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Source - Meaning as Use from Wittgenstein to Google's Word2vec]]

## Open Questions
- Is reference enough to count as a genuine semantic achievement for WoLaLa purposes, or only one component of it?
- Are derivative meaning and limited agency best treated as different dimensions rather than as a simple ranking?
- When should distributional or conceptual-role structure count as semantic evidence rather than only as a precursor to semantics?
- Which future sources best test whether language can be integrated with world models in a way that supports stronger understanding claims?
