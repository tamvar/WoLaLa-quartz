---
title: What Would Count as Meaning or Reference in a Language Model
type: analysis
status: active
updated: 2026-05-04
tags:
  - analysis
  - meaning
  - reference
  - llms
  - wolala
---

## Summary
The sources considered here support a more differentiated picture than a simple three-way contrast. Fluency or task success does not by itself establish meaning. But semantic assessment also should not be reduced to direct reference alone. The strongest supported conclusion is that meaning and understanding claims need to be graded across formal linguistic competence, functional linguistic competence, derivative meaning, distributional structure, grounding, conceptual role, reference, agency-like behavior, and world-linked understanding.

## Key Points
- [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that form-only training cannot, in principle, learn meaning understood as a relation between form and communicative intent.
- [[../sources/Source - Distributional Models of Word Meaning|Lenci]] argues that distributional structure captures important aspects of lexical meaning, while remaining limited for inference and compositionality.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] argue that formal linguistic competence should be separated from functional competence, and that current LLMs are much stronger on the former.
- [[../sources/Source - Human and Machine Language Understanding|Wang et al.]] argue that `language understanding` itself is framed differently in cognitive science and computer science.
- Selected chapters in [[../sources/Source - Mind Design III|Mind Design III]] show that current disputes also inherit older disagreements about intentional stance, strong AI, and the explanatory relation between computation and content.
- [[../sources/Source - The Generative AI Paradox|West et al.]] argue that generative models may produce expert-like outputs without corresponding understanding, so generation and understanding should be evaluated separately.
- [[../sources/Source - Language Models Mostly Know What They Know|Kadavath et al.]] argue that models can show useful calibration and self-evaluation, but that this ability remains task-sensitive and narrower than full understanding.
- [[../sources/Source - Lexical Competence|Marconi]] argues that lexical competence has inferential and referential aspects that should not be collapsed into a single criterion of semantic success.
- [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] argue that distributional semantics should be extended rather than abandoned, especially through multimodality and inferential integration.
- [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] argue that reference may not require the internal beliefs, experiences, or capacities often assumed by grounding objections.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] argue that meaning may be partially constituted by conceptual role and internal relational structure even without settled reference.
- [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] argue that referential grounding is the crucial grounding notion for LLMs, and that it may arise through fine-tuning or even, in limited domains, pre-training alone.
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] argue that derivative-meaning models of LLMs face a challenge from novel reference and may underexplain agent-like semantic behavior.
- [[../sources/Source - From Word Models to World Models|Wong et al.]] propose a path beyond form-only models by translating language into a structured probabilistic language of thought for world-guided inference.
- the strongest supported move is not "LLMs understand language" but "the space of semantic claims needs to be disaggregated."

## Evidence
The skeptical side of the batch is clear. [[../sources/Source - Climbing Towards NLU|Bender and Koller]] give an explicit argument that meaning is not recoverable from form alone, because meaning involves communicative intent and world-linked use. On this view, performance on apparently meaning-sensitive tasks may still reflect successful exploitation of form.

[[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] complicate that picture in a productive way. They argue that text-trained LLMs may still be strong models of formal linguistic competence even if they remain weak on broader reasoning, pragmatics, and situation modeling. That matters because it blocks the common slide from `not much thought` to `not much language competence`.

[[../sources/Source - Human and Machine Language Understanding|Wang et al.]] show why some disputes here become unstable so quickly. In one disciplinary setting, `understanding` means successful language processing for applications; in another, it means explaining the behavioral and neural basis of human language comprehension. If those senses are not kept apart, benchmark success and mechanistic understanding get conflated.

Selected chapters in [[../sources/Source - Mind Design III|Mind Design III]] add a historical clarification. Dennett suggests that intentional attribution may be justified by predictive success, while Searle denies that formal program execution alone therefore amounts to understanding. Boden and Egan then show two different ways of resisting the strongest anti-computational conclusion: one by challenging Searle’s assumptions about computation, the other by arguing that formal computational individuation and semantic explanation need not be the same thing. Later chapters by Haugeland, Brooks, and Webb extend the point further by showing that stronger worldly competence need not imply one single representational recipe: some intelligent success may depend on embodied organization, close world-coupling, or lightweight task-specific mechanisms rather than explicit inner models. This helps explain why current arguments about LLM meaning often shuttle between stance-level interpretation, architectural claims, and stronger claims about genuine understanding.

[[../sources/Source - The Generative AI Paradox|West et al.]] make that warning more concrete in current model terms. Their claim is that generation can exceed understanding, so strong performance at producing answers, stories, or images should not by itself be treated as evidence that the system could selectively justify, interrogate, or robustly explain what it has produced.

[[../sources/Source - Language Models Mostly Know What They Know|Kadavath et al.]] then add a narrower positive result. Models can often estimate whether their own answers are correct, and larger models can show useful calibration on some tasks. That matters because it suggests that self-evaluation belongs on the evidential map, but only as one bounded ability among others rather than as a shortcut to a full understanding claim.

The distributional side shows why the issue is not exhausted by that critique. [[../sources/Source - Distributional Models of Word Meaning|Lenci]] treats language-use statistics as semantically informative rather than as meaningless residue. His review supports a serious usage-based semantics, but one that remains coarse and incomplete. That matters for WoLaLa because it blocks both a naive dismissive view and a naive triumphalist one.

[[../sources/Source - Lexical Competence|Marconi]] adds a more explicit competence vocabulary. His inferential-versus-referential distinction helps explain why some evidence may support semantic organization, paraphrase, or word-use sensitivity without yet supporting a strong claim about world-directed reference. That is useful here because it gives a cleaner way to separate different kinds of apparent semantic success.

[[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] reinforce that point at a larger scale. Their view is that the limitations of current distributional models do not show that the program is misguided; they show that richer forms of data, learning, and inference are needed if the program is to climb farther.

[[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Skelac and Jandrić]] add a useful clarification here. Even if one accepts a meaning-as-use tradition, it does not follow that any contextual embedding model has captured meaning in the full Wittgensteinian sense. Word2vec operationalizes one thin slice of use, not the whole social-practical structure of language games.

The referential side is also clear, but narrower. [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] focus on reference rather than full understanding. Their argument is that if reference depends on external historical relations rather than rich internal grasp, then text-trained systems may still produce genuinely referring uses.

[[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] offer a different positive route. They argue that internal conceptual organization may already underwrite meaning in some sense, even where reference is absent, partial, or not yet demonstrated. That puts pressure on any criterion that treats direct grounding as the only route to semantics.

[[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] make that pressure more precise. Their contribution is to separate grounding from several other things it is often made to cover. If referential grounding is the relevant standard, then some anti-LLM arguments may overstate what is missing.

[[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] complicate matters differently. They argue that some LLM outputs may be derivatively meaningful in a library-like way, but that novel reference creates a harder problem. At that point, the best explanation may begin to look intentional rather than merely transmissive.

The constructive side comes from [[../sources/Source - From Word Models to World Models|Wong et al.]], who treat language as an interface into richer cognitive representations. Their proposal suggests that one route to stronger meaning claims is not to inflate what next-token models already do, but to connect language to explicit world modeling and inference.

## Interpretation
Semantic claims about language models should be phrased along more than one dimension, not as one simple ladder.

One dimension concerns linguistic competence:
- Safest: the model captures or exploits statistical regularities in linguistic form.
- Stronger on that same dimension: the model exhibits substantial formal linguistic competence across syntax-sensitive or abstraction-heavy language tasks.
- Distinct rather than simply higher: the model shows some degree of functional linguistic competence in domains such as discourse tracking, pragmatics, reasoning, or social inference.

Another dimension concerns semantic status:
- Stronger in an inferential lexical-semantic sense: the model supports stable word-to-word relations, paraphrase-sensitive structure, or semantically relevant inferences without yet securing reference.
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
- [[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Source - Meaning as Use from Wittgenstein to Google's Word2vec]]

## Open Questions
- Is reference enough to count as a genuine semantic achievement for WoLaLa purposes, or only one component of it?
- Is referential grounding stronger than derivative meaning in the right way for WoLaLa's purposes, or are they different dimensions rather than a simple ranking?
- When should distributional or conceptual-role structure count as semantic evidence rather than only as a precursor to semantics?
- Which future sources best test whether language can be integrated with world models in a way that supports stronger understanding claims?
