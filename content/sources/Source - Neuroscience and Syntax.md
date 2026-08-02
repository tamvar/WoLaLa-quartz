---
title: Source - Neuroscience and Syntax
type: source
status: active
updated: 2026-08-02
ingestion_depth: deep
tags:
  - source
  - deep
  - neuroscience
  - syntax
  - hierarchy
  - generative-linguistics
---

## Summary

Emiliano Zaccarella and Patrick C. Trettenbrein review lesion, neuroimaging, connectivity, developmental, and comparative evidence about the neural basis of syntax from an explicitly generative and Minimalist perspective. They argue that hierarchical structure building, especially the operation Merge, supplies a productive organizing hypothesis for a left-lateralized network involving inferior frontal and posterior temporal regions and their connecting pathways.

The chapter is most valuable as a map from formal syntactic distinctions to neuroscience experiments. Its strongest evidence concerns neural sensitivity to constituent structure, dependency formation, and hierarchical complexity. That evidence does not by itself identify Merge as the brain's implemented algorithm, validate Universal Grammar, or establish that a localized response is uniquely syntactic. The relevant experiments remain dependent on task contrasts, linguistic assumptions, lesion granularity, and alternative processing explanations.

## Strand Connections

- Primary: [[../overviews/Neuroscientific Perspectives Overview|Neuroscientific Perspectives]] (strand 8)
- Secondary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Explanatory bridge: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Hierarchy as the Explanatory Target

The chapter begins from the generative claim that sentences are not merely linear word sequences. Constituent relations and c-command organize dependencies that cannot be stated adequately over adjacency alone. Minimalism compresses this commitment into Merge, a recursive set-forming operation that combines syntactic objects and can apply to its own output.

This framing also separates an internal system connecting language and thought from externalization through speech or sign. The neuroscience question is therefore not simply where words are processed, but which neural systems support hierarchical composition and dependency formation. The chapter treats this formal characterization as an experimental advantage: explicit linguistic hypotheses can determine contrasts and predicted computations.

That advantage is also a source of underdetermination. Evidence that a neural signal tracks constituency or hierarchy supports structure-sensitive processing more directly than it supports a particular derivational operation or a full Minimalist architecture.

## From Lesions to Networks

The historical Broca–Wernicke–Lichtheim–Geschwind picture linked production and comprehension deficits to a few cortical centers. Later work made that map less secure. Broca's aphasia is not a unitary grammatical deficit, lesions are rarely confined to one cytoarchitectonic area, and Broca's region is internally heterogeneous. Early trace-deletion accounts connected movement deficits to Broca's area, but the linguistic theory changed and the anatomical inference was too coarse to sustain a simple syntax-center claim.

The chapter accordingly shifts from isolated centers to distributed networks. Left inferior frontal areas, especially BA44, and posterior superior temporal regions recur across structure-sensitive tasks, but they contribute differently across experiments. The review presents posterior temporal regions as important for lexical–argument-structure information and inferior frontal regions as especially important for hierarchical combination and complex dependency processing.

This network view is more plausible than a single-center story, but the functional labels remain hypotheses. Activation can reflect working memory, controlled retrieval, sequencing, or task difficulty as well as a linguistically defined computation.

## Neuroimaging Evidence

Several experiment families organize the review:

- Artificial-grammar studies compare rules compatible with proposed Universal Grammar constraints against rules described as impossible. Increased responses in Broca's area for the former are presented as evidence that the brain distinguishes linguistically natural structure from arbitrary pattern learning.
- Constituent-size studies find increasing activity in left posterior temporal and inferior frontal regions as phrases become structurally larger, including in pseudoword materials designed to reduce lexical-semantic support.
- Movement and long-distance-dependency studies implicate inferior frontal and posterior temporal regions under contrasts intended to isolate syntactic dependency formation.
- Recursion studies compare finite-state and phrase-structure grammars, nested dependencies, or minimally composed word pairs. BA44 is repeatedly associated with the more hierarchical conditions.
- Model-based analyses report that hierarchy-sensitive parsing predictors explain neural variance beyond linear predictors.

Together these results make a serious case that human language networks are sensitive to hierarchical organization. They are less decisive about whether Merge is the unique description of that organization. Artificial grammars may differ in learnability or memory load; constituent-size effects can covary with integration demands; and formal predictors inherit choices about the grammar used to annotate or model the input.

## Connectivity, Development, and Evolution

Functional-connectivity analyses in the chapter distinguish frontal contributions to syntactic combination from posterior temporal contributions to lexical and argument-structure processing. Structural-connectivity studies add a dorsal pathway between BA44 and posterior temporal cortex, contrasted with ventral routes associated more strongly with semantic processing. These anatomical distinctions are treated as a basis for a syntax network rather than as mere coactivation.

Developmental evidence complicates a static localization. Posterior temporal engagement appears earlier, while BA44 specialization and left-lateralized connectivity mature gradually. The dorsal pathway associated with complex syntax develops relatively late, and its myelination correlates with complex sentence processing. Earlier ventral and premotor routes may support more local combinations before mature recursive processing is available.

Comparative discussion emphasizes that nonhuman primates can learn linear sequence regularities but have not been shown to possess the full human capacity for linguistic hierarchy. Differences in dorsal connectivity and hemispheric asymmetry are presented as possible biological preconditions. This is a phylogenetic hypothesis, not a direct demonstration that one tract caused the emergence of human syntax.

## What the Evidence Supports

The chapter supports a graded conclusion:

- Strongest: human language processing recruits a distributed left-lateralized network that is sensitive to constituent structure, dependency formation, and hierarchical complexity.
- Plausible: inferior frontal and posterior temporal regions make partly distinct contributions, and dorsal connectivity is important for mature complex syntax.
- More theory-dependent: BA44 implements Merge or a specifically Minimalist computation.
- Not established by the reviewed evidence alone: that hierarchy-sensitive activation proves Universal Grammar, that syntax is neurally autonomous in a strong modular sense, or that competing sequential and processing accounts have been eliminated.

The authors describe the converging findings as compelling support for core aspects of generative linguistics. That is their interpretation of the evidence. The experiments are informative precisely because theory shapes their contrasts, but this makes theory-neutral inference impossible.

## Relation to Language Models

The chapter does not test contemporary LLMs. It nonetheless supplies useful constraints on model–human comparisons. A model can show hierarchy-sensitive behavior without sharing the biological implementation reviewed here, and a representational similarity between a model and brain activity does not establish mechanistic equivalence.

Conversely, a lack of BA44-like localization would not show that a model lacks syntactic competence. The appropriate comparison depends on the level of explanation: behavioral generalization, representational organization, implemented computation, and biological realization should be tested separately.

Language-model work can contribute by contrasting hierarchical and linear predictors, testing dependencies under controlled lexical conditions, and generating explicit computational alternatives. It cannot turn a correlational neural match into a unique theory of human syntax without intervention, competing models, and evidence linking the measured representation to behavior.

## Limitations and Interpretive Cautions

- The review is written from within generative linguistics and uses Merge as its preferred explanatory vocabulary.
- Broca's area and BA44 are not homogeneous syntax modules, and lesion evidence is anatomically coarse.
- Neuroimaging contrasts operationalize theoretical constructs rather than observing them directly.
- Much of the evidence is correlational; localization and connectivity do not alone specify a mechanism.
- Electrophysiological work is mentioned but is less fully reviewed than lesions, fMRI, connectivity, and development.
- Hierarchy sensitivity does not uniquely distinguish Minimalism from other hierarchical or constraint-based theories.

## Related Pages

- [[Source - A Deep Learning Framework for Neuroscience|Source - A Deep Learning Framework for Neuroscience]]
- [[Source - Shared Computational Principles for Language Processing in Humans and Deep Language Models|Source - Shared Computational Principles for Language Processing in Humans and Deep Language Models]]
- [[Source - Deep Language Algorithms Predict Semantic Comprehension from Brain Activity|Source - Deep Language Algorithms Predict Semantic Comprehension from Brain Activity]]
- [[Source - Dissociating Language and Thought in Large Language Models|Source - Dissociating Language and Thought in Large Language Models]]
- [[Source - The View from Declarative Syntax|Source - The View from Declarative Syntax]]

## Source Identification

- Authors: Emiliano Zaccarella and Patrick C. Trettenbrein
- Chapter: "Neuroscience and Syntax"
- Year: 2021
- Parent volume: *A Companion to Chomsky*
- Editors: Nicholas Allott, Terje Lohndal, and Georges Rey
- Publisher: Wiley-Blackwell / John Wiley & Sons
- Edition: First edition
- Chapter number: 20
- Printed pages: 325–347
- PDF pages: 342–364
- Parent source ID: `src_companion_chomsky_2021_container`
- Component source ID: `src_companion_chomsky_2021_ch20`
- DOI: `10.1002/9781119598732.ch20`

## Source Access

- Public source: [Wiley chapter page](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119598732.ch20)
- DOI / publisher: [DOI landing page](https://doi.org/10.1002/9781119598732.ch20)

## Open Questions

- Which experiments discriminate Merge from other hierarchical descriptions rather than merely from linear baselines?
- How can task demands, working memory, and syntactic computation be separated more decisively?
- Which model–brain comparisons connect representational alignment to causal contribution and behavior?
