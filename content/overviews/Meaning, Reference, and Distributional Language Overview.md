---
title: Meaning, Reference, and Distributional Language Overview
type: overview
status: active
updated: 2026-05-04
tags:
  - overview
  - meaning
  - reference
  - distributional-language
  - wolala
---

## Summary
This overview maps a WoLaLa strand focused on meaning, reference, and distributional language. It is not about generic LLM performance. It is about how language models bear on claims about meaning, grounding, understanding, agency, and the relation between language use, internal structure, and world modeling. Its later bridge material extends that core by asking how distinctions in linguistic competence and disciplinary uses of `understanding` affect the force of those semantic claims.

This page is the canonical top-level overview for Meaning, Reference, and Distributional Language (strand 3) in the nine-strand WoLaLa map.

## Key Points
- [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that form-only training is insufficient for meaning or understanding in the strong sense tied to communicative intent.
- [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] argue that LM words may still refer if their training strings inherit the right natural histories.
- [[../sources/Source - Distributional Models of Word Meaning|Lenci]] presents distributional semantics as a serious usage-based model of lexical meaning, but also emphasizes its limits for fine-grained relations, inference, and full compositionality.
- [[../sources/Source - Lexical Competence|Marconi]] distinguishes inferential competence from referential competence, sharpening the difference between word-to-word semantic structure and world-directed application.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] distinguish formal linguistic competence from functional linguistic competence and argue that LLMs are much stronger on the former than the latter.
- [[../sources/Source - Human and Machine Language Understanding|Wang et al.]] argue that `language understanding` already names different projects in cognitive science and computer science, so evaluation standards must be stated explicitly.
- Selected chapters in [[../sources/Source - Mind Design III|Mind Design III]] show that current LLM disputes inherit older arguments about intentional attribution, strong AI, and the relation between formal computation and semantic content.
- [[../sources/Source - The Generative AI Paradox|West et al.]] argue that generative capability can outrun understanding capability, so impressive outputs should not be read straightforwardly as evidence of human-like intelligence.
- [[../sources/Source - Language Models Mostly Know What They Know|Kadavath et al.]] argue that models can show meaningful self-evaluation and calibration in some settings, but this remains narrower than a broad understanding claim.
- [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] defend distributional semantics as a broad research program while arguing that richer data, multimodality, and inferential integration are needed to extend its semantic reach.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] argue that meaning may arise from conceptual role and internal relational structure even where direct reference is absent or incomplete.
- [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] argue that the crucial grounding issue for LLMs is referential grounding, and that it may be achievable without treating embodiment as necessary.
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] argue that novel reference pressures purely library-like interpretations of LLMs and may support attributing limited agency.
- [[../sources/Source - From Word Models to World Models|Wong et al.]] propose a more structured architecture in which language is translated into a probabilistic language of thought for world modeling and reasoning.
- the literature supports a richer contrast between form-only skepticism, derivative meaning, grounding, externalist reference, conceptual-role meaning, usage-based distributional semantics, limited-agency interpretations, and constructive world-model integration.

## Topic Map
- Core concept: [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- Core analysis: [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]

## Details
This strand sits alongside questions about linguistic probing and mechanistic explanation, but its central question is different: what kinds of semantic or cognitive claims language-model success does or does not justify.

[[../sources/Source - Climbing Towards NLU|Bender and Koller]] set the cluster's caution standard. They argue that progress on form-sensitive tasks should not be redescribed as meaning or understanding unless the relation to communicative intent and world grounding is made explicit.

[[../sources/Source - Distributional Models of Word Meaning|Lenci]] supplies the historical and linguistic anchor for why language-use statistics matter at all. The paper treats distributional semantics as a real model of lexical meaning, while also emphasizing that semantic relatedness, compositionality, and inference create limits for purely distributional accounts.

[[../sources/Source - Lexical Competence|Marconi]] deepens the competence side of the strand. His inferential-versus-referential distinction helps explain why semantic assessment cannot be reduced either to distributional relations among words or to a single externalist verdict about whether reference succeeds. It also connects the cluster more directly to older questions about what would count as genuine understanding in an artificial system.

[[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] extend that question into a bridge area between semantics and language-cognition. By separating formal linguistic competence from functional linguistic competence, they show why some disputes that look like disputes about meaning or understanding are partly disputes about which kind of linguistic success is actually under discussion. Their paper argues that contemporary LLMs may already be good models of some linguistically central abilities even when they remain weak or inconsistent on reasoning, pragmatics, situation modeling, and other parts of real-world language use.

[[../sources/Source - Human and Machine Language Understanding|Wang et al.]] make a different but complementary bridge point. They show that the phrase `language understanding` is used differently across cognitive science and computer science, with one side asking about mechanisms in the brain and the other often asking about performance in downstream applications. That difference helps explain why debates about LLM understanding so often slide past each other, and why this cluster now needs an explicit bridge from semantic questions to language-cognition ones.

Selected chapters in [[../sources/Source - Mind Design III|Mind Design III]] provide historical depth for that bridge. Dennett supplies a background for intentional-stance and limited-agency thinking; Searle states the strongest classic case against treating program execution as understanding; Boden resists turning that case into a rejection of computational explanation; and Egan clarifies how formal computation and semantic content may play different explanatory roles. Later chapters by Haugeland, Brooks, and Webb extend that background into embodiment, world-coupled intelligence, and caution about assuming that stronger worldly competence must always come from one uniform kind of inner representation. These older disputes do not settle current LLM questions, but they do show that the bridge from semantics to language-cognition has longstanding fault lines.

[[../sources/Source - The Generative AI Paradox|West et al.]] add a current critical framing that fits this bridge closely. Their argument is that generative fluency may outrun selective or interrogative understanding, so model outputs can look expert even when the underlying grasp remains brittle. This sharpens the cluster's caution against reading production quality as understanding.

[[../sources/Source - Language Models Mostly Know What They Know|Kadavath et al.]] qualify that caution in a narrower direction. They show that some models can still give useful self-evaluations and calibrated confidence judgments under the right task formats. That does not collapse the generation-understanding distinction, but it does show that self-assessment and metacognitive honesty are part of the same evidential terrain.

[[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] broaden that picture into a larger program. They explicitly engage current objections about grounding and understanding, defend distributional approaches against blanket dismissal, and argue for multimodal, incremental, and inference-aware extensions rather than abandonment.

[[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] narrow the dispute. They do not defend a broad understanding claim, but they do argue that reference may be easier than many critics assume, because reference can depend on external historical relations rather than rich internal grasp.

[[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] push further in a different direction. Rather than defending reference first, they argue that meaning may be grounded in conceptual role: the organization of internal representational states and their relations to one another. This makes them a bridge between distributional traditions and contemporary LLM semantics.

[[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] sharpen the grounding debate by distinguishing several notions often run together. Their paper suggests that grounding should be asked about more narrowly than many critiques suppose, and that referential grounding may already be partially available in some models.

[[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] push on a different seam in the cluster. They ask whether library-like metaphors are enough to explain LLM semantics, or whether cases of novel reference push us toward attributing a limited form of agency.

[[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Skelac and Jandrić]] make the philosophy-of-language bridge explicit. They argue that Word2vec inherits an important context-sensitive picture of meaning from Wittgenstein and Firth, while also showing that vector context is narrower than full language-game use.

[[../sources/Source - From Word Models to World Models|Wong et al.]] provide the most ambitious constructive proposal in this set. Instead of treating next-token prediction as sufficient, they connect language to structured probabilistic reasoning over world models.

This strand should remain distinct from neighboring literatures on linguistic probing and mechanistic explanation of context-sensitive behavior. Those literatures ask what information is extractable from representations and what mechanisms implement specific behaviors. This strand asks what kinds of semantic or cognitive claims those successes do or do not justify.

## Related Pages
- [[Critical and Skeptical Perspectives Overview]]
- [[Theoretical Linguistics and Language Models Overview]]
- [[Cultural, Cognitive, and SSH Perspectives Overview]]
- [[Historical Perspectives on Language, Mind, and Modeling Overview]]
- [[Neural NLP Probing Overview]]
- [[Induction Heads and In-Context Learning Overview]]
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]

## Sources
- [[../sources/Source - Climbing Towards NLU|Climbing Towards NLU]] — `existing_deep`; critical; central; high. Strong caution standard for meaning and understanding claims.
- [[../sources/Source - Distributional Models of Word Meaning|Distributional Models of Word Meaning]] — `existing_deep`; foundational; central; high. Core distributional-semantics anchor.
- [[../sources/Source - Do Language Models Refer|Do Language Models Refer?]] — `existing_deep`; critical; central; high. Narrows the reference dispute through historical inheritance arguments.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Meaning Without Reference in Large Language Models]] — `existing_deep`; bridge; central; high. Conceptual-role defense for meaning without settled reference.
- [[../sources/Source - The Vector Grounding Problem|The Vector Grounding Problem]] — `existing_deep`; critical; central; high. Refines the grounding debate around referential grounding.
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Are LLMs Like Libraries or Librarians]] — `existing_deep`; bridge; central; high. Limited-agency and derivative-meaning interpretation of LLM semantics.
- [[../sources/Source - From Word Models to World Models|From Word Models to World Models]] — `existing_deep`; bridge; central; high. Constructive world-model proposal linking language to structured reasoning.
- [[../sources/Source - Distributional Semantics|Distributional Semantics]] — `existing_deep`; survey; central; high. Broader program-level defense and extension of distributional semantics.
- [[../sources/Source - Lexical Competence|Lexical Competence]] — `existing_deep`; foundational; central; high. Sharpens inferential versus referential competence.
- [[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Meaning as Use: from Wittgenstein to Google's Word2vec]] — `existing_deep`; bridge; supporting; medium. Historical philosophy-of-language bridge.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Dissociating Language and Thought in Large Language Models]] — `existing_deep`; bridge; supporting; medium. Helps separate semantic debates from broader cognition debates.
- [[../sources/Source - Human and Machine Language Understanding|Human and Machine Language Understanding]] — `existing_deep`; survey; supporting; medium. Clarifies disciplinary ambiguity around understanding claims.
- [[../sources/Source - Mind Design III|Mind Design III]] — `existing_deep`; foundational; supporting; medium. Historical container on intentionality and computation/content.
- [[../sources/Source - The Generative AI Paradox|The Generative AI Paradox]] — `existing_deep`; recent; supporting; medium. Reinforces caution about fluent generation and understanding.
- [[../sources/Source - Language Models Mostly Know What They Know|Language Models Mostly Know What They Know]] — `existing_deep`; recent; supporting; medium. Qualification source on self-knowledge and calibrated confidence.
- *No Place for Semantics* — `index_only`; critical; central; high. Strong semantics-skeptical candidate already marked near-term relevant.
- *Do Language Models Understand Us?* — `index_only`; critical; central; high. Likely bridge between semantics and language-understanding debates.

## Open Questions
- Which semantic claim is best supported by current evidence: derivative meaning, grounded reference, conceptual-role meaning, limited agency, or language-guided world modeling?
- Does this strand still hang together as one topic, or will the distributional-semantics side eventually justify a separate but linked subtopic?
