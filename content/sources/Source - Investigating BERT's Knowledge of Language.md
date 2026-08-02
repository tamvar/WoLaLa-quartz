---
title: Source - Investigating BERT's Knowledge of Language
type: source
status: active
updated: 2026-07-29
ingestion_depth: brief
tags:
  - source
  - brief
  - bert
  - probing
  - syntax
  - evaluation
---

## Summary
Alex Warstadt and a large NYU collaboration compare five different ways of testing one grammatical phenomenon in BERT: Boolean acceptability classification, absolute minimal pairs, gradient minimal pairs, cloze testing, and probing, all centered on negative polarity item licensing. Their central finding is not that one method wins, but that the methods reveal different aspects of grammatical knowledge and can support meaningfully different conclusions. For WoLaLa, the paper is important because it directly supports the repository's insistence that probing, behavior, and theoretical interpretation must be kept distinct.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## WoLaLa Relevance
This source is especially valuable because it holds the linguistic phenomenon fixed while varying the analysis method. That design makes it unusually good evidence about methodology itself. On NPIs, BERT appears knowledgeable in some task formats and much less so in others. The result is a strong argument against treating one diagnostic family as the whole story about linguistic competence.

The paper also connects naturally to the probing architecture already built in WoLaLa. It does not reject probing, but it shows that probing results need to be interpreted alongside behavioral and minimally contrasted evidence. That is exactly the distinction the repository now tries to preserve between extractability, deployed competence, and stronger explanatory claims.

## Key Points
- The paper compares five evaluation methods on one grammar phenomenon rather than one method on many phenomena.
- BERT shows substantial knowledge of NPI licensing, but that knowledge appears differently across task formats.
- Gradient measures can reveal distinctions that absolute acceptability decisions obscure.
- Probing contributes evidence, but it is not sufficient on its own to characterize grammatical knowledge.

## Limitation Or Open Question
The study centers on one phenomenon, negative polarity item licensing, so it does not prove that the same method divergence holds everywhere in syntax. The open question is which kinds of phenomena are most sensitive to evaluation format and which methods best track behaviorally meaningful grammatical competence.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]

## Source Identification
- Authors: Alex Warstadt, Yu Cao, Ioana Grosu, Wei Peng, Hagen Blix, Yining Nie, Anna Alsop, Shikha Bordia, Haokun Liu, Alicia Parrish, Sheng-Fu Wang, Jason Phang, Anhad Mohananey, Phu Mon Htut, Paloma Jeretic, and Samuel R. Bowman
- Title: *Investigating BERT's Knowledge of Language: Five Analysis Methods with NPIs*
- Year: 2019
- Source type: conference paper
- Publication: *Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing*, pages 2877-2887
- DOI: `10.18653/v1/D19-1286`

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/D19-1286/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/D19-1286)
