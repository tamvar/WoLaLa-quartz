---
title: Source - What Do NMT Models Learn About Morphology
type: source
status: active
updated: 2026-04-23
tags:
  - source
  - probing
  - nmt
  - morphology
---

## Summary
Belinkov, Durrani, Dalvi, Sajjad, and Glass analyze what neural machine translation models learn about word morphology. They freeze trained attention-based LSTM encoder-decoder NMT systems, extract encoder or decoder representations, and train simple classifiers for POS and morphological tagging. The source extends the current probing cluster from sentence/BERT analysis into NMT representation analysis.

## Key Points
- Source fact: the authors train NMT systems on parallel corpora, freeze them, extract word representations, and use a feed-forward classifier to predict POS or morphological tags.
- Source fact: character-based source representations outperform word-based representations for morphology, especially on rare and unseen words.
- Source fact: lower encoder layers are better for POS and morphological tagging than higher encoder layers, even though deeper models improve BLEU.
- Source fact: changing the target language affects the quality of source-side morphological representations; translating into morphologically poorer English produced better source representations than translating into richer Hebrew or German in the Arabic experiments.
- Source fact: decoder representations contain much less word-structure information than encoder representations.
- Source fact: removing attention decreases encoder representation quality but improves decoder representation quality, suggesting attention changes the division of labor between encoder and decoder.
- Source fact: the authors explicitly frame classifier performance as a proxy for representation quality, not as a state-of-the-art tagging objective.

## Details
The paper uses POS and full morphological tagging as diagnostic tasks for representations learned during NMT training. It compares several factors: word-based vs. character-based representations, encoder depth, target language, encoder vs. decoder representations, and attention vs. no attention.

The clearest result is that character-level modeling helps NMT learn morphology, especially for low-frequency and out-of-vocabulary words. The layer result also aligns with later probing work on contextual representations: lower layers tend to preserve local form or word-structure information, while higher layers appear more task- or meaning-oriented.

The decoder finding is important because it complicates the idea that all NMT components learn similar linguistic structure. In attention-based systems, the encoder carries more useful morphology for diagnostic classifiers, while the decoder can rely on attention and language modeling rather than robust target-side word-structure representations.

## Synthesis / Interpretation
This source broadens the wiki's probing cluster in a controlled way. It shows that diagnostic classifiers were already being used to ask representation questions before BERT-focused probing, and that architectural location matters: encoder vs. decoder, lower vs. upper layer, and word vs. character representation all change what is extractable.

The claims should remain extractability claims. The paper shows that POS and morphology can be predicted from certain NMT representations better than others; it does not by itself prove exactly how the translation model uses those morphological features during decoding.

Within `neural_nlp_probing`, this source functions as a narrow historical and architectural extension rather than a separate cluster. It should not be treated as mechanistic circuit evidence.

## Related Pages
- [[../concepts/Probing Classifiers|Probing Classifiers]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]

## Source Identification
- Authors: Yonatan Belinkov, Nadir Durrani, Fahim Dalvi, Hassan Sajjad, and James Glass
- Title: *What Do Neural Machine Translation Models Learn About Morphology?*

## Open Questions
- How do these LSTM NMT findings transfer to transformer-based NMT and modern multilingual encoder-decoder models?
- Should the wiki later create a dedicated NMT representation probing concept if more NMT sources are ingested?
