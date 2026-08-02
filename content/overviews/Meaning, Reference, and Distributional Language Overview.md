---
title: Meaning, Reference, and Distributional Language Overview
type: overview
status: active
updated: 2026-08-02
tags:
  - overview
  - meaning
  - reference
  - distributional-language
  - wolala
---

## Summary
This overview maps a WoLaLa strand focused on meaning, reference, and distributional language. It is not about generic LLM performance. It is about how language models bear on claims about meaning, grounding, understanding, agency, and the relation between language use, internal structure, and world modeling. Its role is to map the main literature families and their points of contact, while leaving key notions to [[../concepts/Meaning and Reference in Language Models|the concept page]] and evidential tests to [[../analyses/What Would Count as Meaning or Reference in a Language Model|the analysis page]].

This page is the canonical top-level overview for Meaning, Reference, and Distributional Language (strand 3) in the nine-strand WoLaLa map.

## Key Points
- the strand contains several distinct but overlapping literature families: distributional semantics, grounding and reference, logical and compositional semantics, communicative use, language understanding, and lexical or conceptual representation
- the central debate is not simply whether LLMs `have meaning`, but which semantic claims are being made and what evidence could support them
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]] now carries the main vocabulary of distinctions
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]] now carries the evidential and argumentative tests
- this overview should therefore function as a strand map rather than a sequential source commentary

## Topic Map
- Core concept: [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- Core analysis: [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]

## Four Connected Questions

Four questions recur across the strand but should not be used as substitutes for one another.

| Question | Primary target | What evidence would not settle it |
| --- | --- | --- |
| Lexical and compositional meaning | Internal resources that distinguish readings, constrain use, and combine systematically | Stable reference is not required for every meaningful distinction; distributional association alone does not establish productive composition |
| Reference | Relations among speakers or systems, expressions, circumstances, and worldly targets | Internal semantic organization does not by itself fix reference; failure of fixed lexical extension does not show that acts of reference are impossible |
| Pragmatic interpretation | Inference from encoded material and context to an intended interpretation | Linguistic decoding or context-sensitive output can occur without evidence of mindreading or communicative intention |
| Intentionality | Whether states are genuinely about something under an aspect and can succeed, fail, or misrepresent | Behavioral aboutness and theorist-relative interpretation do not by themselves establish content-bearing states for the system |

[[../sources/Source - Chomsky on Meaning and Reference|Pietroski]] supplies the internalist meaning/reference distinction; [[../sources/Source - Chomsky on Semantics|Glanzberg]] separates semantic evidence from truth-conditional architecture; [[../sources/Source - Chomsky and Pragmatics|Allott and Wilson]] separate decoding from inferential recovery of communicator meaning; and [[../sources/Source - Chomsky and Intentionality|Collins and Rey]] expose the unresolved choice between intentional and nonintentional accounts of linguistic representation. Together they sharpen the vocabulary of the strand without yielding a single Chomskyan solution.

[[../sources/Source - Chomsky on the Evolution of the Language Faculty|Reboul]] adds a distinct evolutionary proposal: human concepts may be strongly decoupled from immediate perception and action, and the central innovation may be the interface between Merge and a conceptual-intentional system. This does not solve reference or grounding, but it identifies action-independence and counterfactual or fictional content as a separate target from communicative fluency.

## Literature Families

### Distributional and usage-based semantics

This family asks what semantic structure can be learned from language-use statistics and how far a usage-based program can be extended.

- main anchors:
  - [[../sources/Source - Distributional Models of Word Meaning|Distributional Models of Word Meaning]]
  - [[../sources/Source - Distributional Semantics|Distributional Semantics]]
  - [[../sources/Source - From Frequency to Meaning|From Frequency to Meaning]]
  - [[../sources/Source - Semantic Structure in Deep Learning|Semantic Structure in Deep Learning]]
  - [[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Meaning as Use: from Wittgenstein to Google's Word2vec]]
- constructive bridge:
  - [[../sources/Source - Frege in Space|Frege in Space]]
  - [[../sources/Source - Distributional Memory|Distributional Memory]]

### Reference and grounding

This family asks what kind of world-link, natural history, or interaction would justify reference claims.

- main anchors:
  - [[../sources/Source - Do Language Models Refer|Do Language Models Refer?]]
  - [[../sources/Source - The Vector Grounding Problem|The Vector Grounding Problem]]
  - [[../sources/Source - Are LLMs Like Libraries or Librarians|Are LLMs Like Libraries or Librarians]]
- related bridge:
  - [[../sources/Source - Chomsky on Meaning and Reference|Chomsky on Meaning and Reference]]
  - [[../sources/Source - Mapping Language Models to Grounded Conceptual Spaces|Mapping Language Models to Grounded Conceptual Spaces]]
  - [[../sources/Source - Learning Semantic Correspondences with Less Supervision|Learning Semantic Correspondences with Less Supervision]]

### Conceptual-role and lexical-semantic structure

This family asks whether internal relational or inferential organization is already enough for a meaningful semantic claim.

- main anchors:
  - [[../sources/Source - Meaning Without Reference in Large Language Models|Meaning Without Reference in Large Language Models]]
  - [[../sources/Source - Lexical Competence|Lexical Competence]]
  - [[../sources/Source - Lexical Semantics with Large Language Models|Lexical Semantics with Large Language Models]]
- supporting bridge:
  - [[../sources/Source - On the Universal Structure of Human Lexical Semantics|On the Universal Structure of Human Lexical Semantics]]

### Structuralist and matrix-model reinterpretations

This family asks what picture of language is implicitly carried by vector and embedding methods, and whether their success fits a structuralist or distributionalist conception better than a reference-first picture.

- main anchors:
  - [[../sources/Source - Why Can Computers Understand Natural Language|Why Can Computers Understand Natural Language]]
- supporting bridge:
  - [[../sources/Source - From Frequency to Meaning|From Frequency to Meaning]]

### Communicative use and understanding

This family asks how meaning claims connect to communicative intent, discourse use, and stronger language-understanding claims.

- main anchors:
  - [[../sources/Source - Chomsky and Pragmatics|Chomsky and Pragmatics]]
  - [[../sources/Source - Climbing Towards NLU|Climbing Towards NLU]]
  - [[../sources/Source - Human and Machine Language Understanding|Human and Machine Language Understanding]]
  - [[../sources/Source - The Generative AI Paradox|The Generative AI Paradox]]
  - [[../sources/Source - Language Models Mostly Know What They Know|Language Models Mostly Know What They Know]]
- functional bridge:
  - [[../sources/Source - The Communicative Function of Ambiguity in Language|The Communicative Function of Ambiguity in Language]]

### Logical, ontological, and world-model proposals

This family contains the most constructive attempts to move beyond simple next-token interpretation.

- main anchors:
  - [[../sources/Source - Language, Logic and Ontology|Language, Logic and Ontology]]
  - [[../sources/Source - From Word Models to World Models|From Word Models to World Models]]
  - [[../sources/Source - Quantifiers Satisfying Semantic Universals are Simpler|Quantifiers Satisfying Semantic Universals are Simpler]]
- historical background:
  - [[../sources/Source - Chomsky on Semantics|Chomsky on Semantics]]
  - [[../sources/Source - Chomsky and Intentionality|Chomsky and Intentionality]]
  - [[../sources/Source - Meaning and Use|Meaning and Use]]
  - [[../sources/Source - Intentionality and the Use of Language|Intentionality and the Use of Language]]
  - selected chapters in [[../sources/Source - Mind Design III|Mind Design III]]

### Bridges to neighboring strands

- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Dissociating Language and Thought in Large Language Models]] connects semantics to the language-thought divide in strand 5.
- [[../sources/Source - Human and Machine Language Understanding|Human and Machine Language Understanding]] connects semantics to disciplinary differences about understanding.
- [[../sources/Source - Frege in Space|Frege in Space]] and [[../sources/Source - Lexical Semantics with Large Language Models|Lexical Semantics with Large Language Models]] connect semantics to strand 4.

This strand should remain distinct from [[Neural NLP Probing Overview]] and [[Induction Heads and In-Context Learning Overview]]. Those clusters ask what linguistic information is extractable from representations and what mechanisms implement context-sensitive behavior. This cluster asks what kinds of semantic or cognitive claims those successes do or do not justify.

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
- [[../sources/Source - Chomsky on Meaning and Reference|Chomsky on Meaning and Reference]] — `existing_deep`; foundational; central; high. Internalist reconstruction separating systematic meaning and conditions on reference from fixed lexical extensions.
- [[../sources/Source - Chomsky on Semantics|Chomsky on Semantics]] — `existing_deep`; survey; central; high. Historical and architectural map separating semantic evidence, syntactic autonomy, interface interpretation, and truth-conditional semantics.
- [[../sources/Source - Chomsky and Pragmatics|Chomsky and Pragmatics]] — `existing_deep`; bridge; central; high. Cognitive-pragmatic account distinguishing encoded meaning from context-sensitive inference and overt communicative intention.
- [[../sources/Source - Chomsky and Intentionality|Chomsky and Intentionality]] — `existing_deep`; foundational; central; high. Internal dispute over intentional versus nonintentional representation and the common-currency problem across cognitive interfaces.
- [[../sources/Source - Climbing Towards NLU|Climbing Towards NLU]] — `existing_deep`; critical; central; high. Strong caution standard for meaning and understanding claims.
- [[../sources/Source - Distributional Models of Word Meaning|Distributional Models of Word Meaning]] — `existing_deep`; foundational; central; high. Core distributional-semantics anchor.
- [[../sources/Source - Do Language Models Refer|Do Language Models Refer?]] — `existing_deep`; critical; central; high. Narrows the reference dispute through historical inheritance arguments.
- [[../sources/Source - Meaning Without Reference in Large Language Models|Meaning Without Reference in Large Language Models]] — `existing_deep`; bridge; central; high. Conceptual-role defense for meaning without settled reference.
- [[../sources/Source - The Vector Grounding Problem|The Vector Grounding Problem]] — `existing_deep`; critical; central; high. Refines the grounding debate around referential grounding.
- [[../sources/Source - Are LLMs Like Libraries or Librarians|Are LLMs Like Libraries or Librarians]] — `existing_deep`; bridge; central; high. Limited-agency and derivative-meaning interpretation of LLM semantics.
- [[../sources/Source - From Word Models to World Models|From Word Models to World Models]] — `existing_deep`; bridge; central; high. Constructive world-model proposal linking language to structured reasoning.
- [[../sources/Source - Distributional Semantics|Distributional Semantics]] — `existing_deep`; survey; central; high. Broader program-level defense and extension of distributional semantics.
- [[../sources/Source - Frege in Space|Frege in Space]] — `existing_deep`; bridge; central; high. Programmatic attempt to combine vector-based lexical meaning with formal compositional semantics.
- [[../sources/Source - Lexical Competence|Lexical Competence]] — `existing_deep`; foundational; central; high. Sharpens inferential versus referential competence.
- [[../sources/Source - Meaning as Use from Wittgenstein to Google's Word2vec|Meaning as Use: from Wittgenstein to Google's Word2vec]] — `existing_deep`; bridge; supporting; medium. Historical philosophy-of-language bridge.
- [[../sources/Source - Meaning and Use|Meaning and Use]] — `existing_deep`; foundational; supporting; medium. Selective deep collection on meaning, use, reference, intentionality, and semantic method.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Dissociating Language and Thought in Large Language Models]] — `existing_deep`; bridge; supporting; medium. Helps separate semantic debates from broader cognition debates.
- [[../sources/Source - Human and Machine Language Understanding|Human and Machine Language Understanding]] — `existing_deep`; survey; supporting; medium. Clarifies disciplinary ambiguity around understanding claims.
- [[../sources/Source - Mind Design III|Mind Design III]] — `existing_deep`; foundational; supporting; medium. Historical container on intentionality and computation/content.
- [[../sources/Source - From a Logical Point of View|From a Logical Point of View]] — `existing_deep`; foundational; supporting; medium. Selective deep Quine background on analyticity, ontology, and the problem of meaning in linguistics.
- [[../sources/Source - The Generative AI Paradox|The Generative AI Paradox]] — `existing_deep`; recent; supporting; medium. Reinforces caution about fluent generation and understanding.
- [[../sources/Source - Language Models Mostly Know What They Know|Language Models Mostly Know What They Know]] — `existing_deep`; recent; supporting; medium. Qualification source on self-knowledge and calibrated confidence.
- [[../sources/Source - No Place for Semantics|No Place for Semantics]] — `existing_deep`; critical; central; high. Meaning-as-role argument denying an autonomous theoretical semantics and claiming that linguistically expressible semantic differences must be formally representable, with present language-model relevance requiring separate interpretation.
- [[../sources/Source - Do Language Models Understand Us|Do Language Models Understand Us?]] — `existing_deep`; critical; central; high. Strong affirmative bridge source on whether statistical language learning can amount to understanding in a public, falsifiable sense.
- [[../sources/Source - LLMs Are Semantic Reasoners Rather than Symbolic Reasoners|LLMs Are Semantic Reasoners Rather than Symbolic Reasoners]] — `existing_brief`; recent; supporting; medium. Sharpens the distinction between semantics-supported reasoning and stronger symbolic-reasoning claims.
- [[../sources/Source - Semantic Structure in Deep Learning|Semantic Structure in Deep Learning]] — `existing_deep`; survey; central; high. Review-level map of how deep-learning representations bear on lexical semantics, world knowledge, and composition.
- [[../sources/Source - The Communicative Function of Ambiguity in Language|The Communicative Function of Ambiguity in Language]] — `existing_deep`; bridge; supporting; high. Information-theoretic functionalist account arguing that ambiguity can improve communicative efficiency.
- [[../sources/Source - Language, Logic and Ontology|Language, Logic and Ontology]] — `existing_brief`; bridge; supporting; medium. Commonsense-ontology proposal treating natural language as evidence for the typed background structure semantics requires.
- [[../sources/Source - Quantifiers Satisfying Semantic Universals are Simpler|Quantifiers Satisfying Semantic Universals are Simpler]] — `existing_brief`; bridge; supporting; medium. Formal-semantics and complexity source connecting quantifier universals to description-length simplicity rather than to arbitrary stipulation alone.
- [[../sources/Source - Intentionality and the Use of Language|Intentionality and the Use of Language]] — `existing_brief`; historical; supporting; medium. Philosophy-of-language distinction between intensionality and intentionality that remains relevant to meaning and understanding claims.
- [[../sources/Source - Lexical Semantics with Large Language Models|Lexical Semantics with Large Language Models]] — `existing_brief`; bridge; supporting; medium. Theory-facing case study showing how LLMs can support lexical-semantic analysis.
- [[../sources/Source - Learning Semantic Correspondences with Less Supervision|Learning Semantic Correspondences with Less Supervision]] — `existing_brief`; bridge; supporting; medium. Grounded-language-learning source linking semantic correspondence to world-state alignment under weak supervision.
- [[../sources/Source - Mapping Language Models to Grounded Conceptual Spaces|Mapping Language Models to Grounded Conceptual Spaces]] — `existing_brief`; bridge; supporting; medium. Constrained grounding result suggesting that pretrained conceptual structure can support data-efficient alignment to bounded world-linked domains.

## Open Questions
- Which semantic claim is best supported by current evidence: derivative meaning, grounded reference, conceptual-role meaning, limited agency, or language-guided world modeling?
- Does this strand still hang together as one topic, or will the distributional-semantics side eventually justify a separate but linked subtopic?
