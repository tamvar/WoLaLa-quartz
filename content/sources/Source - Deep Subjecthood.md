---
title: Source - Deep Subjecthood
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - multilinguality
  - grammar
  - bert
  - subjecthood
---

## Summary
Isabel Papadimitriou, Ethan A. Chi, Richard Futrell, and Kyle Mahowald test whether multilingual BERT represents a higher-order grammatical notion of subjecthood rather than only local word-level cues. They train classifiers to distinguish transitive subjects from objects and then evaluate those classifiers on intransitive subjects within and across 24 languages. The main result is that the classifiers' zero-shot behavior reflects the morphosyntactic alignment of the training language, suggesting that mBERT encodes more abstract grammatical structure than any single sentence directly reveals. For WoLaLa, the paper matters because it turns multilingual BERT into evidence about typology-sensitive grammar rather than only transfer performance.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is useful because it asks a stronger theoretical question than many multilingual benchmark papers do. The issue is not just whether multilingual BERT transfers across languages, but whether its representations reflect language-specific theories of what counts as a subject. That makes the paper a bridge between multilingual representation studies and theoretical linguistics.

The paper is also cautious in a way that matters for WoLaLa. The authors do not claim that mBERT has discovered a discrete universal subject category in the strongest possible sense. Their analysis instead suggests that subjecthood in the model is continuous and shaped by case, animacy, passive voice, and discourse-sensitive cues. That keeps the paper from collapsing multilingual structural evidence into a simple victory claim for abstract syntax alone.

## Key Points
- The paper tests whether mBERT captures morphosyntactic alignment, not only sentence-local labels.
- Classifiers trained on transitive subject/object distinctions behave differently on intransitive subjects depending on the alignment system of the training language.
- Cross-lingual results suggest that higher-order grammatical regularities are present in multilingual contextual embeddings.
- Subjecthood in the model appears graded and partly influenced by semantic and discourse factors, not purely discrete syntax.

## Limitation Or Open Question
The paper still relies on classifier-based evidence about representations rather than direct causal intervention. It therefore supports a strong extractability and organization claim, but not a full mechanistic or explanatory account of how multilingual BERT uses subjecthood during downstream behavior.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - Finding Universal Grammatical Relations in Multilingual BERT|Source - Finding Universal Grammatical Relations in Multilingual BERT]]
- [[../sources/Source - How Multilingual Is Multilingual BERT|Source - How Multilingual Is Multilingual BERT]]

## Source Identification
- Authors: Isabel Papadimitriou, Ethan A. Chi, Richard Futrell, and Kyle Mahowald
- Title: *Deep Subjecthood: Higher-Order Grammatical Features in Multilingual BERT*
- Year: 2021
- Source type: conference paper
- Publication: *Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics*, pages 2522-2532
- DOI: `10.18653/v1/2021.eacl-main.215`

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2021.eacl-main.215/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/2021.eacl-main.215)
