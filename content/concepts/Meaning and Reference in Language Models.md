---
title: Meaning and Reference in Language Models
type: concept
status: active
updated: 2026-08-02
tags:
  - concept
  - meaning
  - reference
  - philosophy-of-language
  - llms
---

## Summary
This concept page tracks a central WoLaLa distinction: claims about meaning, reference, grounding, use, and understanding should not be collapsed into one another. The current literature distinguishes form-only learning, formal linguistic competence, inferential lexical competence, distributional semantic structure, conceptual-role meaning, grounded reference, derivative meaning, limited agency, and language-guided world modeling. The concept page organizes those notions. The analysis page asks what evidence would count for any of them.

## Key Points
- [[../sources/Source - Climbing Towards NLU|Bender and Koller]] argue that form-only training cannot yield meaning in the strong sense tied to communicative intent.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] show why formal linguistic competence and broader functional competence must be separated.
- [[../sources/Source - Lexical Competence|Marconi]] distinguishes inferential from referential competence.
- [[../sources/Source - Distributional Models of Word Meaning|Lenci]] and [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] defend a serious usage-based semantic program while emphasizing its limits.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] argue for a conceptual-role route to meaning.
- [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]], [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]], and [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] keep reference, grounding, derivative meaning, and limited agency distinct.
- [[../sources/Source - Mapping Language Models to Grounded Conceptual Spaces|Patel and Pavlick]] provide a narrower constructive case in which text-trained conceptual structure can be aligned to grounded domains with a small amount of world-linked supervision.
- [[../sources/Source - From Word Models to World Models|Wong et al.]] provide the clearest constructive world-model direction.

## Core Distinctions

### Meaning, reference, pragmatics, and intentionality

- [[../sources/Source - Chomsky on Meaning and Reference|Pietroski]] treats lexical and compositional meanings as internal resources that constrain interpretation, use, and possible reference without being fixed extensions.
- [[../sources/Source - Chomsky on Semantics|Glanzberg]] distinguishes using semantic facts as evidence from adopting a truth-conditional semantic architecture. Internal semantic features, syntactic autonomy, and reference-first semantics are separate commitments.
- [[../sources/Source - Chomsky and Pragmatics|Allott and Wilson]] distinguish encoded linguistic meaning from disambiguation, reference resolution, enrichment, implicature, and inference about communicative intentions.
- [[../sources/Source - Chomsky and Intentionality|Collins and Rey]] ask whether linguistic representations possess content for the system or merely provide a theorist's formal classification of internal states.

These distinctions prevent four invalid inferences: semantic structure does not guarantee reference; reference does not guarantee understanding; context-sensitive performance does not guarantee communicative intention; and behavior that observers can interpret as about something does not guarantee system-level intentionality.

### Form, competence, and understanding

- [[../sources/Source - Climbing Towards NLU|Bender and Koller]] distinguish linguistic form from meaning tied to communicative intent.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Mahowald et al.]] distinguish formal linguistic competence from broader functional competence.
- [[../sources/Source - Human and Machine Language Understanding|Wang et al.]] show that `understanding` itself varies across disciplines and research aims.

These distinctions block the move from fluent output directly to strong semantic or cognitive conclusions.

### Inferential versus referential competence

- [[../sources/Source - Lexical Competence|Marconi]] is the clearest anchor here.
- A system can track inferential relations among words without yet settling stronger questions about world-directed reference.

This is one reason why semantic success should not be treated as a single ladder.

### Distribution, use, and conceptual role

- [[../sources/Source - Distributional Models of Word Meaning|Lenci]] and [[../sources/Source - Distributional Semantics|Lenci and Sahlgren]] defend usage-based semantic structure while emphasizing its limits for richer inference and composition.
- [[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Skelac and Jandrić]] make clear that contextual vector use is not yet full social-practical language use.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Piantadosi and Hill]] push the internal-relational or conceptual-role side of the debate.

### Reference, grounding, and derivative meaning

- [[../sources/Source - Do Language Models Refer|Mandelkern and Linzen]] argue that reference may depend on historical or external relations rather than rich inner grasp.
- [[../sources/Source - The Vector Grounding Problem|Coelho Mollo and Millière]] narrow the grounding issue to more specific world-linking relations.
- [[../sources/Source - Mapping Language Models to Grounded Conceptual Spaces|Patel and Pavlick]] show one limited route from text-trained structure toward grounded alignment without claiming that text alone already yields full reference.
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Lederman and Mahowald]] show why derivative or transmissive meaning may be too weak in cases of novel reference.

### Agency and world-model integration

- [[../sources/Source - From Word Models to World Models|Wong et al.]] provide the constructive world-model direction.
- [[../sources/Source - Mapping Language Models to Grounded Conceptual Spaces|Patel and Pavlick]] provide a narrower positive case where world-linked examples activate structured conceptual organization already present in a text-trained model.
- [[../sources/Source - The Generative AI Paradox|West et al.]] and [[../sources/Source - Language Models Mostly Know What They Know|Kadavath et al.]] help separate output fluency, self-evaluation, and stronger understanding claims.
- selected chapters in [[../sources/Source - Mind Design III|Mind Design III]] show that these distinctions inherit older disagreements about intentional stance, computation, and semantic content.

## Conceptual Map

- `distributional meaning`: semantic organization supported by patterns of language use
- `meaning as use`: a broader social-practical account not reducible to local co-occurrence
- `conceptual-role meaning`: meaning grounded in inferential or relational organization among internal states
- `referential grounding`: a world-linking relation sufficient for some reference claims
- `derivative meaning`: meaning inherited from human linguistic practice without full independent agency
- `limited agency`: a stronger interpretation where novel reference or action-like semantic behavior becomes explanatory
- `world-model integration`: a constructive architecture in which language interfaces with richer inferential structure
- `pragmatic interpretation`: context-sensitive inference from encoded material toward an intended interpretation, including disambiguation, enrichment, and implicature
- `intentionality`: aboutness under an aspect, including conditions of correctness and the possibility of misrepresentation

The analysis page [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]] asks what evidence would justify any of these moves. The strand overview [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]] maps the literature families in which they recur.

## Related Pages
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]

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
- Can a model refer without understanding in the stronger communicative-intent sense?
- Should derivative meaning and limited agency be treated as separate semantic statuses or as stages along one scale?
- How much distributional or conceptual-role structure should count as meaning before grounding enters the picture?
- What kind of world-link or interaction would justify moving from reference claims to stronger meaning claims?
- How should language-guided reasoning architectures be distinguished from ordinary form-only LMs?
