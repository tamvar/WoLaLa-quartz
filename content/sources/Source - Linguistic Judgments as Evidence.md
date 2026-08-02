---
title: Source - Linguistic Judgments as Evidence
type: source
status: active
updated: 2026-08-02
ingestion_depth: deep
tags:
  - source
  - deep
  - linguistic-judgments
  - acceptability
  - evidence
  - methodology
---

## Summary

Steven Gross examines why metalinguistic judgments became central evidence in generative linguistics, which objections they face, and what formal experiments show about their reliability. Acceptability, ambiguity, coreference, entailment, truth, pronunciation, and related responses provide efficient access to rare or impossible cases. They are observations to be explained, not direct readings of grammatical structure.

The chapter defends a continued role for judgment data while rejecting methodological complacency. Informal judgments have often proved highly replicable, but task design, participant population, context, gradience, processing, and theory contamination still matter. Formal experiments can measure and control some of these influences; they do not automatically identify the linguistic cause of a response or make one elicitation task universally superior.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Critical bridge: [[../overviews/Critical and Skeptical Perspectives Overview|Critical and Skeptical Perspectives]] (strand 2)

## What Judgment Data Are

Judgment data are metalinguistic responses to linguistic items. They include judgments about acceptability, coreference, ambiguity, pronounceability, truth, entailment, frequency, and preference. They may be expressed categorically, on Likert scales, through magnitude estimation, or by forced choice.

Not every metalinguistic statement is a datum. Saying that an expression violates a theoretical constraint is normally an explanation of a response, not the response itself. The distinction is especially important for grammaticality. In the technical I-language sense, grammaticality is a property assigned by a theory; acceptability is a speaker's observable response. When linguists act as their own participants, datum and analysis can easily be conflated.

This separation gives judgments a clear evidential role without treating speakers as introspecting a grammar. A judgment can be caused by grammatical knowledge while also being affected by memory, processing, pragmatics, lexical awkwardness, and experimental context.

## Why Linguists Use Judgments

Corpora record what was produced, not the full space of what speakers could produce or understand. Absence from a corpus is weak evidence of impossibility, especially for rare combinations. A controlled judgment can test a negative case directly and can vary one factor across a minimal pair while holding others relatively constant.

This efficiency made judgments particularly important after Chomsky's mentalist reconception of linguistics. If the target is an internal capacity generating indefinitely many possible expressions, actual utterance counts cannot exhaust the evidence. Judgment data allow researchers to investigate productivity, ambiguity, and structural constraints beyond ordinary frequency.

The argument is not that judgments are the only legitimate evidence. Corpora, acquisition, language deficits, production, reading times, eye movements, and neural measures can all constrain linguistic hypotheses. Their evidential value depends on how clearly each connects observations to the target explanation.

## Intuition and Introspection

Gross resists treating all linguistic judgments as mysterious intuitions or introspection. Participants judge sentences or interpretations, not necessarily their own mental states. Some responses are immediate; others require reflection, comparison, or contextual support. Their psychological etiology may vary and is not fully understood.

Different philosophies of language also change what judgments are supposed to reveal. A Chomskyan mentalist treats them as effects of I-language. Katz's abstract-object view invites a more a priori interpretation. Devitt's externalist view treats them as evidence about public conventions or usage. The same response can therefore support different higher-level inferences depending on the ontology of language.

This makes an evidentially modest formulation preferable: judgments are reproducible behavioral data whose relation to grammar must be modeled. Calling them direct intuitions of grammatical facts prejudges the explanation.

## Objections to Informal Practice

Critics note that linguists often report their own responses, use small samples, provide little information about context or elicitation, and risk confirmation bias. Informal examples may be difficult to reproduce, and a theoretically trained participant may hear the intended contrast differently from a naïve speaker.

Defenders reply that many examples are transparently checkable, circulate through a research community, and appear in systematic paradigms rather than isolation. Minimal pairs and variants can make an effect robust even when no formal experiment is reported. Readers themselves supply a form of replication.

These defenses are empirical, not absolute. Informal practice may be sufficient for a large, stable contrast and inadequate for a subtle gradient interaction, dialect difference, subgroup effect, or theoretically decisive null result. The cost of formalization should be matched to the inferential burden.

## Formal Methods and Replication

The chapter reviews large-scale tests of published judgments. Sprouse and Almeida tested 469 textbook sentence types with 440 naïve participants and reported replication of roughly 98 percent of the original contrasts. A later random sample of 300 judgments from *Linguistic Inquiry*, tested with three tasks, replicated roughly 95 percent. Sign reversals were rare, around one to two percent, and there was little evidence that informal practice produced pervasive confirmation bias.

These results undermine the strongest claim that generative syntax rests on generally unreliable intuitions. Their scope is narrower than all of linguistics. The studies emphasize English acceptability judgments and mostly established published contrasts. They do not establish equal reliability across languages, populations, semantic judgments, subtle interactions, or disputed examples.

Formalization also introduces choices. Instructions, presentation order, scale anchoring, context, filler items, and participant recruitment can change responses. Magnitude estimation may not yield genuine ratio measurements simply because it assigns numbers. Forced choice can be statistically efficient—Gross reports that strong effects may reach 80 percent power with about eleven participants—but it suppresses ties and gradience unless the design represents them.

## Calibration and Converging Evidence

Judgments become more informative when calibrated against other measures. Classic processing work shows why convergence matters: the Derivational Theory of Complexity failed when processing cost did not track transformational complexity as expected, while filler-gap reading-time effects supplied independent evidence relevant to island constraints.

Convergence does not mean that all measures should agree perfectly. Acceptability, processing difficulty, corpus frequency, and grammatical status are different variables. Divergence can reveal an incorrect auxiliary theory, population variation, a grammatical illusion, or a task artifact. The goal is an explicit account of why a measure should respond to the proposed structure.

Future work should compare elicitation tasks, focus formal studies on difficult or disputed cases, represent gradience and subgroup variation, and develop better models of how grammar, processing, context, and response formation interact.

## Relation to Language Models

Model probabilities and prompted preferences can be compared with human judgments, but they are not judgments in the human psychological sense. Their values depend on tokenization, prompt wording, templates, context windows, training contamination, post-training, and calibration. A forced choice may reflect the relative probability of answer labels rather than the linguistic contrast.

The chapter's methodology supports controlled model evaluation: define the phenomenon, distinguish acceptability from theoretical grammaticality, use multiple formulations, report variation, and compare against naïve human participants. Agreement can demonstrate behavioral alignment under those conditions. It does not establish that the model has human I-language, uses the same representation, or reaches the result through the same mechanism.

Disagreement is equally ambiguous. It may reveal a competence difference, a prompt artifact, a lexical-frequency effect, or a mismatch between probability and the human task. Model–human judgment research should therefore treat elicitation as part of the measurement model rather than as a transparent window into competence.

## Limitations and Interpretive Cautions

- High replication rates for sampled English acceptability contrasts do not validate every linguistic judgment or theory.
- Acceptability responses are evidence; grammaticality and structural constraints are explanatory constructs.
- Formal experiments reduce some biases while adding task, sampling, and analysis choices.
- Linguists' expertise can improve discrimination while also increasing theoretical contamination.
- Converging evidence is needed when claims concern processing, acquisition, mechanism, or population generality.
- Model probabilities and outputs should not be anthropomorphized as human intuitions.

## Related Pages

- [[Source - Chomsky's Galilean Explanatory Style|Source - Chomsky's Galilean Explanatory Style]]
- [[Source - Neural Network Acceptability Judgments|Source - Neural Network Acceptability Judgments]]
- [[Source - Language Models Align with Human Judgments on Key Grammatical Constructions|Source - Language Models Align with Human Judgments on Key Grammatical Constructions]]
- [[Source - Targeted Syntactic Evaluation of Language Models|Source - Targeted Syntactic Evaluation of Language Models]]
- [[Source - Investigating BERT's Knowledge of Language|Source - Investigating BERT's Knowledge of Language]]
- [[Source - Structural, Functional, and Processing Perspectives on Linguistic Island Effects|Source - Structural, Functional, and Processing Perspectives on Linguistic Island Effects]]

## Source Identification

- Author: Steven Gross
- Chapter: "Linguistic Judgments as Evidence"
- Year: 2021
- Parent volume: *A Companion to Chomsky*
- Editors: Nicholas Allott, Terje Lohndal, and Georges Rey
- Publisher: Wiley-Blackwell / John Wiley & Sons
- Edition: First edition
- Chapter number: 35
- Printed pages: 544–556
- PDF pages: 561–573
- Parent source ID: `src_companion_chomsky_2021_container`
- Component source ID: `src_companion_chomsky_2021_ch35`
- DOI: `10.1002/9781119598732.ch35`

## Source Access

- Public source: [Wiley chapter page](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119598732.ch35)
- DOI / publisher: [DOI landing page](https://doi.org/10.1002/9781119598732.ch35)

## Open Questions

- How far do the replication results extend beyond English acceptability contrasts?
- Which elicitation methods best distinguish stable competence effects from processing and task effects?
- How should model–human comparisons represent prompt sensitivity, gradience, and population variation?
