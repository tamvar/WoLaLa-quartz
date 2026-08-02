---
title: Source - Chomsky and Pragmatics
type: source
status: active
updated: 2026-08-02
ingestion_depth: deep
tags:
  - source
  - deep
  - pragmatics
  - communication
  - relevance-theory
  - cognitive-science
---

## Summary

Nicholas Allott and Deirdre Wilson assess Chomsky's skepticism about pragmatics and argue that a narrower, cognitively explicit research program is compatible with much of his methodology. They define pragmatics as the study of cognitive systems beyond I-language and parsing that enable communicators and audiences to coordinate on an intended interpretation. Linguistic decoding supplies evidence, but communicated content routinely requires disambiguation, reference resolution, lexical adjustment, contextual enrichment, and implicature.

The authors accept Chomsky's demand for idealization, explicit mechanisms, and tractable explanation while rejecting his suggestion that pragmatic interpretation collapses into the study of everything. Their relevance-theoretic alternative treats comprehension as fast, risky, nondemonstrative inference guided by expectations of relevance and mindreading capacities. This is a critical reconstruction, not an account endorsed by Chomsky.

## Strand Connections

- Primary: [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language]] (strand 3)
- Secondary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Linguistic bridge: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)

## Pragmatics as Cognitive Psychology

The chapter distinguishes broad and narrow senses of pragmatics. Broadly, pragmatics can cover almost every relation between linguistic structure and use. More narrowly, it concerns the cognitive processes involved in overt intentional communication: how an audience moves from an encoded linguistic signal to the interpretation a communicator intends it to recover.

Allott and Wilson adopt the narrower target. Pragmatic systems are not part of I-language itself, and they are not exhausted by the parser. They draw on contextual information, memory, perception, social cognition, and hypotheses about intentions. Their explanandum is coordination on an interpretation, not every effect of every linguistic act.

This framing preserves Chomsky's distinction between grammatical competence and broader pragmatic competence while refusing to leave the latter unanalyzed. It also avoids defining pragmatics as a list of residual phenomena. A common inferential task connects disambiguation, reference assignment, implicature, and contextual enrichment.

## Encoded Meaning and Communicated Content

The chapter emphasizes that sentences typically underdetermine what speakers communicate. Linguistic decoding may identify candidate word senses, syntactic structures, and semantic material, but audiences often need to infer more:

- which ambiguous structure or lexical sense is intended;
- whom a pronoun or description concerns;
- whether a word is being narrowed, broadened, or used approximately;
- which unarticulated constituents complete a proposition;
- which implicatures the speaker intends to convey.

These processes should not be conflated. Reference resolution and lexical adjustment can contribute to explicitly communicated content, while implicatures add conclusions that are communicated without being encoded. The boundary between semantics and pragmatics is therefore not identical to a boundary between truth-conditional content and optional conversational effects.

The distinctions matter because a model can decode conventional linguistic information without recovering speaker meaning, or infer a likely intention without representing the same linguistic decomposition as a human listener.

## Chomsky's Pragmatic Competence

Chomsky has used `pragmatic competence` for knowledge of conditions and appropriate use. He separates this capacity from grammatical competence and treats the systems as at least partly dissociable. Language use also includes internal thought, self-directed speech, play, social positioning, and other activities that are not simply transfers of information.

Allott and Wilson regard this breadth as insightful but too wide for one theory. A theory of overt communication need not explain all language use, just as a grammar need not explain every act in which grammar participates. Scientific progress depends on choosing a constrained subsystem and idealizing away from some interactions.

The authors also distinguish linguistic productivity from Chomsky's notion of creative use. Grammar explains how an unbounded range of expressions can be formed and understood. Chomsky's stronger idea that speakers act appropriately yet without being caused by circumstances raises issues of agency and free action that the chapter does not try to solve. Comprehension can be studied without resolving the metaphysics of creative action.

## Why Chomsky Was Skeptical

Chomsky doubts that an interpreter can be isolated from the entirety of a person's beliefs, goals, and situation. Context seems unbounded, and ordinary communication does not resemble deterministic decoding from a fixed code. If successful interpretation requires inspecting everything an agent knows, pragmatics may be computationally intractable and scientifically shapeless.

Allott and Wilson argue that this objection assumes the wrong model. Comprehension is not a proof that surveys all potentially relevant evidence. It is a fallible inference process that exploits accessibility, expectations, and cues to communicative intention. Human listeners often reach an interpretation quickly, sometimes incorrectly, without globally optimizing over all beliefs.

This response also addresses Fodor's concern that central inference is global and therefore resistant to modular computational explanation. A heuristic process can be constrained and empirically studied even when it draws on heterogeneous information.

## Ostensive Communication and Relevance

The chapter's positive framework is relevance theory. An ostensive act openly provides evidence of an intention to inform. The audience recognizes that the communicator is deliberately directing attention and infers what the act was intended to make manifest. Verbal utterances are one form of ostension; gesture and other nonverbal behavior can serve the same function.

Relevance is analyzed through cognitive effects and processing effort. Human cognition tends to allocate attention toward inputs expected to yield worthwhile effects, while an ostensive act carries a presumption that it is relevant enough to process. The resulting comprehension heuristic follows a path of least effort through accessible interpretations and stops at the first overall interpretation that satisfies the audience's expectations of relevance.

This is not a claim that interpreters calculate numerical utilities or examine every possible context. It is a proposed description of a psychologically realized search procedure. Developmental evidence about mindreading, gaze, pointing, and sensitivity to communicative cues supports the broader picture in which specialized social-cognitive capacities guide interpretation.

## Communication Is Not All Language Use

The authors agree with Chomsky that language should not be defined solely as communication. Internal thought and other noncommunicative uses remain important. They disagree with a restrictive conception of communication as successful transmission of propositional information.

Phatic speech, politeness, social positioning, and relational effects can be overtly communicative even when they do not transfer a discrete fact. Gricean speaker meaning and relevance-theoretic ostension offer ways to analyze these cases through recognizable intentions rather than through information transfer alone.

The chapter's target is consequently narrower than all pragmatically appropriate action but broader than literal proposition exchange. This boundary is crucial when the framework is applied to machine-generated language.

## Relation to Language Models

The chapter does not discuss LLMs. It nevertheless supplies a useful decomposition for model evaluation. Performance on pragmatic benchmarks can reflect at least four different achievements: recovering encoded meaning, selecting a contextually appropriate interpretation, attributing communicative intent, and producing behavior that merely resembles the output of such attribution.

Text-only benchmark items often specify an artificial context and a desired answer. Success may show sensitivity to discourse cues or regularities in human interpretations without establishing participation in ostensive communication. A deployed conversational system may also affect users socially without possessing the intentions that relevance theory assigns to communicators.

Stronger claims would require tests that vary contextual accessibility, separate lexical adjustment from implicature, track reference across discourse, and distinguish modeled speaker beliefs from surface associations. Even then, behavioral evidence about inferential competence should be separated from claims about a dedicated pragmatic mechanism or genuine communicative agency.

## Limitations and Interpretive Cautions

- The chapter advocates a relevance-theoretic conception of pragmatics; competing pragmatic frameworks divide the field differently.
- Its account is designed for human cognition and should not be transferred to LLMs without independent evidence.
- Chomsky's broad remarks about language use are not equivalent to the narrower theory of ostensive communication assessed here.
- The proposed heuristic is fallible and nondemonstrative; successful interpretation does not guarantee that the inferred intention was correct.
- Pragmatic enrichment, speaker meaning, social effect, and language use are related but non-identical categories.

## Related Pages

- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[Source - Chomsky on Meaning and Reference|Source - Chomsky on Meaning and Reference]]
- [[Source - Chomsky on Semantics|Source - Chomsky on Semantics]]
- [[Source - Chomsky and Intentionality|Source - Chomsky and Intentionality]]
- [[Source - Origins of Human Communication|Source - Origins of Human Communication]]
- [[Source - Climbing Towards NLU|Source - Climbing Towards NLU]]
- [[Source - Human and Machine Language Understanding|Source - Human and Machine Language Understanding]]

## Source Identification

- Authors: Nicholas Allott and Deirdre Wilson
- Chapter: "Chomsky and Pragmatics"
- Year: 2021
- Parent volume: *A Companion to Chomsky*
- Editors: Nicholas Allott, Terje Lohndal, and Georges Rey
- Publisher: Wiley-Blackwell / John Wiley & Sons
- Edition: First edition
- Chapter number: 27
- Printed pages: 433–448
- PDF pages: 450–465
- Note: printed page 448 is a blank terminal page before Part VI; the substantive chapter and references end on printed page 447.
- Parent source ID: `src_companion_chomsky_2021_container`
- Component source ID: `src_companion_chomsky_2021_ch27`
- DOI: `10.1002/9781119598732.ch27`

## Source Access

- Public source: [Wiley chapter page](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119598732.ch27)
- DOI / publisher: [DOI landing page](https://doi.org/10.1002/9781119598732.ch27)

## Open Questions

- Which pragmatic benchmark designs can distinguish linguistic decoding, contextual enrichment, mindreading, and output imitation?
- Does successful conversational coordination require the system itself to possess communicative intentions, or can those intentions remain derivative from users and designers?
- Which parts of relevance-theoretic comprehension can be operationalized without assuming a specifically human cognitive architecture?
