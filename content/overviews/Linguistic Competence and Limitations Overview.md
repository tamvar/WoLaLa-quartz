---
title: Linguistic Competence and Limitations Overview
type: overview
status: active
updated: 2026-08-02
tags:
  - overview
  - strand-1
  - competence
  - limitations
  - wolala
---

## Summary

This strand tracks what language models do or do not appear to know about language. It gathers evidence about syntactic structure, lexical behavior, multilinguality, tokenization, linguistic evaluation, and failure modes without treating any one technical literature as the whole strand.

## Scope

This overview is the top-level map for Linguistic Competence and Limitations (strand 1). It includes both behavioral and representation-focused evidence about linguistic competence, while keeping distinct the neighboring questions of semantic interpretation, mechanistic explanation, and broader cognition.

The existing probing cluster is a major subordinate map rather than a replacement for the strand:

- [[Neural NLP Probing Overview]]

Mechanistic work on induction heads is also relevant where it bears on context-sensitive linguistic behavior, but its main home remains [[Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7):

- [[Mind Design and Reverse Engineering Overview]]
- [[Induction Heads and In-Context Learning Overview]]

## Central Questions

- What kinds of linguistic structure are extractable from language-model representations?
- Which competence claims survive stronger evidence standards, controls, or cross-task comparison?
- How far do current competence results extend across syntax, morphology, lexical semantics, multilinguality, and discourse-sensitive behavior?
- Which limitations look like genuine linguistic limits, and which reflect evaluation design?

## Principal Subtopics

- probing and structural evidence about linguistic information in representations
- BERT-era layerwise studies of syntax and linguistic hierarchy
- sentence embedding and representation geometry work
- multilingual competence and transfer
- tokenization, character-level, and subword-sensitive competence
- limits on self-knowledge, robustness, and generalization

## Major Positions or Debates

- extractability versus actual deployed competence
- probing as evidence about structure versus probing as an artifact of flexible readout
- whether strong benchmark or grammatical-judgment performance supports human-like linguistic generalization
- whether multilingual and token-free models strengthen or weaken claims about abstract linguistic knowledge

## Current WoLaLa Coverage

Coverage is substantial but uneven.

- Strongest existing subordinate map: [[Neural NLP Probing Overview]]
- Existing concept pages:
  - [[../concepts/Probing Classifiers|Probing Classifiers]]
  - [[../concepts/Structural Probes|Structural Probes]]
  - [[../concepts/Sentence Embedding Probing|Sentence Embedding Probing]]
  - [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]]
  - [[../concepts/Representation Geometry|Representation Geometry]]
- Existing analysis:
  - [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- Existing bridge sources already represented elsewhere in the wiki:
  - [[../sources/Source - Dissociating Language and Thought in Large Language Models|Dissociating Language and Thought in Large Language Models]]
  - [[../sources/Source - Language Models Mostly Know What They Know|Language Models Mostly Know What They Know]]

Current coverage is strongest on probing, BERT, and evidence standards. The key methodological safeguard is that internal results should now be read through [[../analyses/What Probing Evidence Can Support|the graded probing-evidence analysis]] rather than treated as direct proofs of deployed competence or theory-level explanation. [[../sources/Source - Linguistic Judgments as Evidence|Gross]] adds the parallel distinction between observable acceptability and theoretical grammaticality, while [[../sources/Source - The Deep Forces That Shape Language and the Poverty of the Stimulus|Crain, Giblin, and Thornton]] make the premises of a strong acquisition argument explicit. Language-focused evaluation is now better represented by targeted syntax, scaling-profile, contextual-representation, and psycholinguistic-bridge sources, while multilingual, discourse/pragmatics, and broader failure-mode coverage remain thinner.

The new brief chapters strengthen the human comparison baseline without turning it into a model verdict. [[../sources/Source - Sentence Processing and Syntactic Theory|Kush and Dillon]] separate grammatical representations from incremental parsing and linking hypotheses; [[../sources/Source - Universal Grammar and Language Acquisition|Crain and Thornton]] test a structure-sensitive interpretive exclusion across multiple constructions; and [[../sources/Source - Multilingualism and Chomsky's Generative Grammar|Kupisch et al.]] distinguish stable transfer from context-dependent cross-linguistic influence. [[../sources/Source - Atypical Acquisition|Smith and Tsimpli]] add dissociations among formal language, communication, and general cognition. Together they require competence evaluations to state whether the target is representation, processing, acquisition, or use.

## Representative Sources

- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Probing Classifiers: Promises, Shortcomings, and Advances]] — `existing_deep`; foundational; central; high. Methodology anchor for cautious interpretation of probing evidence.
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|A Structural Probe for Finding Syntax in Word Representations]] — `existing_deep`; foundational; central; high. Core syntax-focused structural-evidence source.
- [[../sources/Source - What You Can Cram Into a Single Vector|What You Can Cram Into a Single Vector]] — `existing_deep`; foundational; supporting; high. Establishes sentence-level probing tasks across surface, syntactic, and semantic properties.
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|BERT Rediscovers the Classical NLP Pipeline]] — `existing_deep`; foundational; central; high. Major layerwise competence map for BERT.
- [[../sources/Source - What Does BERT Learn About the Structure of Language|What Does BERT Learn About the Structure of Language]] — `existing_deep`; foundational; central; high. Strong structure-focused complement to Tenney et al.
- [[../sources/Source - What Do NMT Models Learn About Morphology|What Do NMT Models Learn About Morphology]] — `existing_deep`; bridge; supporting; medium. Extends competence questions beyond BERT to NMT morphology.
- [[../sources/Source - Dissociating Language and Thought in Large Language Models|Dissociating Language and Thought in Large Language Models]] — `existing_deep`; critical; central; high. Separates formal linguistic competence from broader functional language use.
- [[../sources/Source - BERT|BERT]] — `existing_deep`; foundational; supporting; high. Core bidirectional pretraining source behind much of the strand's later probing and syntax-sensitive evaluation work.
- [[../sources/Source - Deep Contextualized Word Representations|Deep Contextualized Word Representations]] — `existing_deep`; historical; supporting; high. Pre-BERT contextualization anchor showing why token meaning became a layerwise context-sensitive representation problem.
- [[../sources/Source - A Primer in BERTology|A Primer in BERTology]] — `existing_deep`; survey; central; high. Organizes the early BERT-analysis literature while keeping extractability distinct from explanation.
- [[../sources/Source - Language Models are Few-Shot Learners|Language Models are Few-Shot Learners]] — `existing_deep`; foundational; supporting; high. Scaling-era anchor on few-shot prompting and broad task behavior without parameter updates.
- [[../sources/Source - T5|T5]] — `existing_brief`; methodological; supporting; medium. Unified text-to-text transfer framework reminding us that task interface and evaluation setup partly shape apparent competence.
- [[../sources/Source - Scaling Language Models from Gopher|Scaling Language Models: Methods, Analysis & Insights from Training Gopher]] — `existing_brief`; methodological; supporting; high. Large-scale capability profile showing that scaling improves some language tasks much more than others.
- [[../sources/Source - InstructGPT|InstructGPT]] — `existing_deep`; bridge; supporting; medium. Important post-training anchor for separating base-model competence from aligned interaction behavior.
- [[../sources/Source - Language Models Mostly Know What They Know|Language Models Mostly Know What They Know]] — `existing_deep`; recent; supporting; medium. Adds bounded self-evaluation and confidence calibration to competence assessment.
- [[../sources/Source - A Systematic Assessment of Syntactic Generalization in Neural Language Models|A Systematic Assessment of Syntactic Generalization in Neural Language Models]] — `existing_deep`; methodological; central; high. Strong targeted-evaluation anchor showing that perplexity and syntactic generalization can diverge.
- [[../sources/Source - Neural Network Acceptability Judgments|Neural Network Acceptability Judgments]] — `existing_brief`; methodological; supporting; high. Acceptability-judgment benchmark source showing that neural models capture some grammar but remain well below human performance.
- [[../sources/Source - Linguistic Judgments as Evidence|Linguistic Judgments as Evidence]] — `existing_deep`; methodological; central; high. Separates observable judgment data from grammatical explanation and assesses the reliability and limits of informal and formal elicitation.
- [[../sources/Source - The Deep Forces That Shape Language and the Poverty of the Stimulus|The Deep Forces That Shape Language and the Poverty of the Stimulus]] — `existing_deep`; foundational; central; high. Explicit nativist acquisition case whose crosslinguistic evidence sharpens, but does not uniquely settle, learnability and inductive-bias questions.
- [[../sources/Source - Sentence Processing and Syntactic Theory|Sentence Processing and Syntactic Theory]] — `existing_brief`; methodological; supporting; high. Psycholinguistic bridge distinguishing grammatical commitments from their resource-bounded real-time implementation.
- [[../sources/Source - Universal Grammar and Language Acquisition|Universal Grammar and Language Acquisition]] — `existing_brief`; empirical; supporting; high. Cross-construction Principle C experiments centered on unavailable interpretations and hierarchical structure.
- [[../sources/Source - Multilingualism and Chomsky's Generative Grammar|Multilingualism and Chomsky's Generative Grammar]] — `existing_brief`; bridge; supporting; medium. Methodological separation of representational transfer from performance-level cross-linguistic influence.
- [[../sources/Source - Atypical Acquisition|Atypical Acquisition]] — `existing_brief`; bridge; supporting; medium. Acquisition and dissociation cases separating accessible input, linguistic structure, communication, and general cognition.
- [[../sources/Source - SyntaxGym|SyntaxGym]] — `existing_brief`; methodological; supporting; medium. Reusable evaluation platform for controlled syntax-sensitive testing.
- [[../sources/Source - Open Sesame|Open Sesame]] — `existing_brief`; bridge; supporting; high. Hierarchy-sensitive BERT study separating lower-layer positional coding from higher-layer structural encoding.
- [[../sources/Source - Visualizing and Measuring the Geometry of BERT|Visualizing and Measuring the Geometry of BERT]] — `existing_brief`; bridge; supporting; medium. Geometry-oriented account of semantic and syntactic structure inside BERT representations.
- [[../sources/Source - Neural Language Models as Psycholinguistic Subjects|Neural Language Models as Psycholinguistic Subjects]] — `existing_brief`; bridge; supporting; high. Psycholinguistic-method bridge on syntactic-state representations.
- [[../sources/Source - Linguistic Knowledge and Transferability of Contextual Representations|Linguistic Knowledge and Transferability of Contextual Representations]] — `existing_brief`; bridge; supporting; high. Natural extension of the current probing/BERT thread, now represented as a brief transferability-focused source page.
- *BERT is not an interlingua* — `index_only`; critical; supporting; high. Candidate multilingual bridge on whether shared representations imply deeper cross-lingual linguistic structure.
- [[../sources/Source - How Multilingual Is Multilingual BERT|How Multilingual Is Multilingual BERT]] — `existing_brief`; bridge; supporting; high. Early multilingual probing anchor showing real cross-lingual representation sharing along with typological limits.
- [[../sources/Source - It's Not Greek to mBERT|It's Not Greek to mBERT]] — `existing_brief`; bridge; supporting; high. Word-level translation probe clarifying what kind of multilingual information mBERT actually encodes.
- [[../sources/Source - On the Multilingual Capabilities of Very Large-Scale English Language Models|On the Multilingual Capabilities of Very Large-Scale English Language Models]] — `existing_brief`; recent; supporting; medium. Multilingual competence bridge on zero-shot transfer from overwhelmingly English pretraining.
- [[../sources/Source - Language Models are Multilingual Chain-of-Thought Reasoners|Language Models are Multilingual Chain-of-Thought Reasoners]] — `existing_brief`; bridge; supporting; medium. Multilingual reasoning benchmark showing that chain-of-thought prompting can transfer across typologically diverse languages.
- [[../sources/Source - Deep Subjecthood|Deep Subjecthood]] — `existing_brief`; bridge; supporting; high. Multilingual subjecthood study showing that higher-order grammatical organization is at least partly recoverable from mBERT representations across languages.
- [[../sources/Source - Investigating BERT's Knowledge of Language|Investigating BERT's Knowledge of Language]] — `existing_brief`; methodological; supporting; high. NPI-method comparison showing that one model can look differently knowledgeable depending on whether we probe, classify, compare minimal pairs, or inspect cloze preferences.
- [[../sources/Source - Are Pre-trained Language Models Aware of Phrases|Are Pre-trained Language Models Aware of Phrases]] — `existing_brief`; bridge; supporting; medium. Constituency-recovery result showing that phrase structure is recoverable from pretrained representations without parser fine-tuning.
- [[../sources/Source - Probing What Different NLP Tasks Teach Machines about Function Word Comprehension|Probing What Different NLP Tasks Teach Machines about Function Word Comprehension]] — `existing_brief`; methodological; supporting; medium. Function-word challenge-task source showing that grammatical subskills vary with pretraining objective rather than collapsing into one global competence score.
- [[../sources/Source - Colorless Green Recurrent Networks Dream Hierarchically|Colorless Green Recurrent Networks Dream Hierarchically]] — `existing_brief`; bridge; supporting; high. Nonce-sentence agreement result arguing that strong syntax-sensitive behavior can persist when lexical-semantic cues are stripped away.
- [[../sources/Source - Can Neural Networks Acquire a Structural Bias from Raw Linguistic Data|Can Neural Networks Acquire a Structural Bias from Raw Linguistic Data]] — `existing_brief`; bridge; supporting; high. BERT structural-bias study showing real structure-sensitive generalization together with one important failure case.
- [[../sources/Source - What Does BERT Look At|What Does BERT Look At?]] — `existing_brief`; supporting; supporting; medium. Attention-pattern analysis source between descriptive probing and stronger mechanistic explanation.
- [[../sources/Source - What Do You Learn from Context|What Do You Learn from Context?]] — `existing_brief`; supporting; supporting; medium. Context-sensitive sentence-structure probing bridge for contextual representations.
- [[../sources/Source - Fine-grained Analysis of Sentence Embeddings|Fine-grained Analysis of Sentence Embeddings]] — `existing_brief`; supporting; supporting; medium. Early sentence-embedding diagnostic source on recoverable structural information.
- [[../sources/Source - Does BERT Rediscover a Classical NLP Pipeline|Does BERT Rediscover a Classical NLP Pipeline?]] — `existing_brief`; critical; supporting; medium. Direct caution against overreading the standard layerwise pipeline story about BERT.
- [[../sources/Source - Analysis Methods in Neural Language Processing|Analysis Methods in Neural Language Processing]] — `existing_deep`; survey; supporting; medium. General methods anchor for evaluating competence claims without overreading a single analysis tool.
- [[../sources/Source - Neural Machine Translation of Rare Words with Subword Units|Neural Machine Translation of Rare Words with Subword Units]] — `existing_brief`; bridge; supporting; medium. Historical subword anchor on open-vocabulary modeling and segmentation strategy.
- [[../sources/Source - Subword Language Modelling|Subword Language Modelling]] — `existing_brief`; bridge; supporting; medium. Early language-modeling source on the tradeoffs among character-, word-, and subword-level units.
- [[../sources/Source - ByT5|ByT5]] — `existing_brief`; recent; supporting; medium. Token-free candidate relevant to whether competence depends on subword segmentation.
- [[../sources/Source - CharBERT|CharBERT]] — `existing_brief`; supporting; supporting; low. Character-aware alternative relevant to tokenization and representation questions.
- [[../sources/Source - CharacterBERT|CharacterBERT]] — `existing_brief`; bridge; supporting; medium. Word-level open-vocabulary alternative showing that strong contextual modeling need not inherit fixed wordpiece vocabularies.
- [[../sources/Source - How to Get Past Sesame Street|How to Get Past Sesame Street]] — `existing_brief`; methodological; supporting; medium. Large pretraining-task comparison clarifying that competence profiles depend on the route into transfer, not only on architecture.
- [[../sources/Source - Finding Universal Grammatical Relations in Multilingual BERT|Finding Universal Grammatical Relations in Multilingual BERT]] — `existing_brief`; bridge; supporting; high. Strong multilingual structural-relations source that sharpens competence claims across languages.
- [[../sources/Source - Emergent Linguistic Structure in Artificial Neural Networks Trained by Self-Supervision|Emergent Linguistic Structure in Artificial Neural Networks Trained by Self-Supervision]] — `existing_brief`; bridge; supporting; high. Important bridge from competence evidence to stronger claims about learned linguistic organization.

## Gaps and Next Priorities

- multilingual competence is materially better represented than before, but still lacks a deeper synthesis tying transfer, alignment, and structural evidence together
- tokenization and character-level threads are visible through CharBERT, CharacterBERT, ByT5, and subword-sensitive background sources, but they are not yet mapped into a dedicated subtopic
- competence limits beyond probing, calibration, and targeted syntax remain thinner than the syntax-focused material
- discourse, pragmatics, and richer evaluation design remain much thinner than syntax and probing
- the next deep ingests for this strand should probably come from the multilingual or linguistic-theory bridge candidates rather than from more probing papers
- post-training and interface design are now more visible as interpretive complications, but they still need tighter synthesis with the core competence literature

## Related Strands and Pages

- [[Critical and Skeptical Perspectives Overview]]
- [[Meaning, Reference, and Distributional Language Overview]]
- [[Theoretical Linguistics and Language Models Overview]]
- [[Mind Design and Reverse Engineering Overview]]
- [[Neural NLP Probing Overview]]
- [[Induction Heads and In-Context Learning Overview]]
