---
title: Source - CulturaX
type: source
status: active
updated: 2026-07-28
ingestion_depth: brief
tags:
  - source
  - brief
  - multilingual
  - data
  - pretraining
  - transparency
---

## Summary
Thuat Nguyen and colleagues introduce CulturaX, a large cleaned and deduplicated multilingual dataset for language-model training covering 167 languages. The paper matters for WoLaLa because it pushes multilingual discussion away from model outputs alone and toward the training-data layer: language coverage, cleaning, deduplication, and public accessibility are treated as first-class determinants of what multilingual systems can plausibly learn.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)

## WoLaLa Relevance
The source is useful as a corrective to model-centric narratives. It argues that open multilingual progress depends not only on architecture and scale, but on whether the data itself is transparent, cleaned, and broadly available. That matters for replication, bias analysis, and any claim about what a multilingual model has actually been exposed to.

## Key Points
- CulturaX provides a large multilingual training corpus with extensive cleaning, filtering, and deduplication.
- The paper frames data transparency as essential for diagnosing hallucination, bias, and reproducibility problems.
- It highlights the mismatch between public claims about multilingual modeling and the opacity of many high-performing training corpora.
- The source belongs in WoLaLa because multilingual competence claims depend on what data was available in the first place.

## Limitation Or Open Question
Dataset scale and cleaning do not guarantee balanced or theoretically meaningful multilingual competence. The open question is how far better multilingual corpora improve downstream claims about structure, understanding, and linguistic diversity rather than only benchmark scores.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../sources/Source - mT5|Source - mT5]]
- [[../sources/Source - Unsupervised Cross-lingual Representation Learning at Scale|Source - Unsupervised Cross-lingual Representation Learning at Scale]]

## Source Identification
- Authors: Thuat Nguyen, Chien Van Nguyen, Viet Dac Lai, Hieu Man, Nghia Trung Ngo, Franck Dernoncourt, Ryan A. Rossi, and Thien Huu Nguyen
- Title: "CulturaX: A Cleaned, Enormous, and Multilingual Dataset for Large Language Models in 167 Languages"
- Year: 2023
- Source type: dataset / paper
- Publication context: arXiv preprint with public dataset release

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2309.09400)
- DOI / publisher: [Hugging Face dataset page](https://huggingface.co/datasets/uonlp/CulturaX)
