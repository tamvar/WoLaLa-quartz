---
title: Meaning and Reference in Language Models
type: concept
status: active
updated: 2026-05-04
tags:
  - concept
  - meaning
  - reference
  - philosophy-of-language
  - llms
---

## Summary
This concept page tracks a crucial WoLaLa distinction: claims about linguistic meaning, reference, grounding, and understanding should not be collapsed into one another. The literature discussed here distinguishes form-only learning, formal linguistic competence, functional linguistic competence, inferential lexical competence, derivative meaning, usage-based distributional meaning, conceptual-role meaning, grounded referential success, limited agency, and language-guided world modeling. The competence distinctions matter here because arguments about meaning and reference often turn on whether a model merely gets linguistic form right, can use language in world-involving ways, or does something stronger still.

## Key Points
- [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that training on form alone cannot in principle yield meaning understood as a relation between form and communicative intent.
- [[../sources/Source - Distributional Models of Word Meaning|Lenci]] argues that distributional evidence captures important aspects of lexical meaning, while also falling short of full inferential and compositional semantics.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] argue that strong formal linguistic competence should be separated from broader functional competence involving reasoning, world knowledge, and pragmatics.
- [[../sources/Source - Human and Machine Language Understanding|Wang et al.]] argue that human and machine `language understanding` are often defined against different research aims and methods.
- Selected chapters in [[../sources/Source - Mind Design III|Mind Design III]] make explicit older disagreements about intentional attribution, strong AI, and whether formal computation can support semantically contentful explanation.
- [[../sources/Source - The Generative AI Paradox|West et al.]] argue that expert-like generation can outrun understanding, so output quality should not be treated as a direct proxy for semantic grasp.
- [[../sources/Source - Language Models Mostly Know What They Know|Kadavath et al.]] argue that models can sometimes track their own likely correctness through calibration and self-evaluation, even though that does not amount to full understanding.
- [[../sources/Source - Lexical Competence|Marconi]] argues that lexical competence has partly independent inferential and referential aspects, so meaning should not be reduced either to encyclopedic knowledge or to a single world-word relation.
- [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] argue that distributional semantics remains a viable semantic research program, but only if it grows toward multimodality, incrementality, and inferential integration.
- [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] argue that LM words may still refer if the training strings have the right natural histories and external links.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] argue that meaning may arise from conceptual role and internal relational structure even without direct reference.
- [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] argue that referential grounding is the central grounding issue for LLMs, and that it can in some cases be achieved without requiring embodiment.
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] argue that novel reference creates pressure to move beyond purely derivative library-like accounts of LLM semantics.
- [[../sources/Source - From Word Models to World Models|Wong et al.]] propose a richer architecture in which language is translated into a probabilistic language of thought and used for structured world modeling.
- this literature supports keeping at least three claims distinct:
  - usage-sensitive semantic structure
  - referential contact
  - fuller language-guided understanding or world-informed reasoning

## Details
[[../sources/Source - Climbing Towards NLU|Bender and Koller]] supply the strongest explicit caution in the current batch. They distinguish linguistic form from meaning and communicative intent, and argue that systems trained only on form cannot by themselves learn the world-linked relation needed for strong meaning claims.

[[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] refine that caution in a useful way. They argue that a model can have substantial formal linguistic competence without thereby possessing the broader capacities involved in real-world language use. This blocks a simple move from fluent performance to thought, but it also blocks the reverse move from failures in reasoning or planning to the conclusion that the model has learned nothing linguistically significant.

[[../sources/Source - Human and Machine Language Understanding|Wang et al.]] add a disciplinary clarification. In computer science, `language understanding` often tracks whether a system can support practical tasks. In cognitive science, the same phrase more often concerns the neural and behavioral mechanisms that make human language comprehension possible. That clarification matters here because disputes about meaning and reference are often overstated when task-level success, linguistic competence, and richer human-like understanding are treated as if they were the same achievement.

[[../sources/Source - The Generative AI Paradox|West et al.]] add a more pointed warning. Their claim is that generative models may acquire output abilities that exceed their ability to understand those same outputs. That matters here because many strong semantic claims still lean too heavily on production quality as if fluent creation settled questions about grasp, content, or intelligence.

[[../sources/Source - Language Models Mostly Know What They Know|Kadavath et al.]] qualify that picture in a narrower way. They show that models can sometimes estimate when their own answers are likely to be correct. This is not equivalent to meaning or reference, but it does suggest that some forms of self-evaluation can be present even when broader understanding remains unsettled.

Selected chapters in [[../sources/Source - Mind Design III|Mind Design III]] show that these tensions are not new. Dennett makes room for intentional attribution at the level of predictive practice; Searle denies that program execution alone could therefore amount to understanding; Boden contests the strength of that denial; and Egan argues that formal computational description and semantic content need not compete for the same explanatory role. Later chapters by Haugeland, Brooks, and Webb add a second caution: world-involving intelligence need not always take the form of rich inner symbolic modeling, since some capacities may depend more on embodied coupling, lightweight control, or task-specific mechanisms. Together these chapters help explain why present disputes over meaning, reference, and understanding so often mix several different questions at once.

[[../sources/Source - Distributional Models of Word Meaning|Lenci]] complicates any simple dismissal of text-derived semantics. On his account, linguistic distributions are not irrelevant surface noise; they are a serious source of evidence about lexical meaning. At the same time, he treats compositionality and inference as major limits, so distributional success should not be mistaken for semantic completeness.

[[../sources/Source - Lexical Competence|Marconi]] adds a useful distinction at this point. He argues that lexical understanding involves both inferential competence and referential competence, and that these abilities are connected without being identical. That makes it easier to say why some systems can look semantically articulate in one respect while still falling short in another.

[[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] extend this point by directly answering contemporary critiques. Their position is that distributional semantics is not refuted by current limitations, but must be connected to better data, multimodality, and the inferential and interactive structure of communication.

[[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Skelac and Jandrić]] then sharpen what `use` means in this area. Their chapter argues that Word2vec genuinely realizes a context-sensitive picture of meaning, but only in a restricted sense: nearby lexical context is not yet the same as Wittgensteinian language use embedded in forms of life.

[[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] target a narrower question. They do not claim that language models thereby understand language in a rich human sense. Instead, they argue that the standard grounding objection is too crude: reference may depend on historical and social embedding rather than on rich internal beliefs or experiences.

[[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] separate meaning from reference in a different way again. Their claim is not mainly externalist but internal-relational: meaning depends on conceptual role, so the key empirical question is whether a model's representational geometry and state transitions instantiate the right kinds of structure.

[[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] refine the issue further by distinguishing grounding from stronger mental notions. Their argument implies that some disputes presented as all-or-nothing clashes over meaning may actually be narrower disputes about which world-linking relations are required.

[[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] then raise the pressure point of novel reference. If some outputs are better explained by limited agency than by derivative transmission alone, then the distinction between meaning, reference, grounding, and agency must be kept even sharper.

[[../sources/Source - From Word Models to World Models|Wong et al.]] move in a different direction again. They treat language and thought as distinct but interacting systems, and propose translating language into structured probabilistic representations that can support inference over world models.

Taken together, these sources argue against treating `meaning` or `understanding` as single yes-or-no properties. A model may have formal linguistic competence without functional competence; distributionally structured lexical content without full reference; reference without rich communicative understanding; or a richer architecture that still falls short of human-like language use.

## Related Pages
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]

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
- Can a model refer without understanding in the stronger communicative-intent sense?
- Is derivative meaning best understood as a genuine semantic achievement, or only as borrowed content transmission?
- How much distributional or conceptual-role structure should count as meaning before grounding enters the picture?
- What kind of world-link or interaction would justify moving from reference claims to stronger meaning claims?
- How should language-guided reasoning architectures be distinguished from ordinary form-only LMs?
