---
title: Source - BERT Rediscovers the Classical NLP Pipeline
type: source
status: active
updated: 2026-04-23
tags:
  - source
  - bert
  - probing
  - linguistic-hierarchy
---

## Summary
Tenney, Das, and Pavlick use edge probing to study where linguistic information appears across BERT layers. They report that BERT's layerwise organization resembles the traditional NLP pipeline: POS tagging appears earliest, followed by parsing, named entities, semantic roles, and coreference, while individual examples can be revised dynamically across layers.

## Key Points
- Source fact: the paper freezes pretrained BERT and trains probing classifiers over span representations, using an edge-probing format.
- Source fact: the tasks include POS, constituents, dependencies, entities, semantic role labeling, coreference, semantic proto-roles, and relation classification.
- Source fact: the authors use scalar mixing weights and cumulative scoring to estimate where tasks are represented across layers.
- Source fact: syntactic information is more localized in specific layers, while semantic tasks such as relations and semantic proto-roles are more spread across the network.
- Source fact: the aggregate layer order resembles a classical NLP pipeline: POS, constituents/dependencies, entities, semantic roles, then coreference.
- Source fact: per-example analysis shows BERT can revise lower-level decisions after higher-level information becomes available, so the pipeline metaphor is approximate rather than rigid.
- Source fact: the paper emphasizes probing limitations: absence of a pattern does not prove absence of information, and observed information does not show how it is used.

## Details
Edge probing converts structured prediction tasks into a common span or span-pair labeling format. BERT is analyzed as a frozen encoder, so the experiments investigate information made available by pretraining rather than fine-tuning.

Two complementary metrics matter. Scalar mixing weights show which layers a trained probe uses. Cumulative scoring estimates how much each newly available layer improves task performance. Together, they support the claim that BERT contains a layered organization of linguistic abstractions.

## Synthesis / Interpretation
This source strengthens the batch's emerging view that BERT representations are not uniform across depth. However, the paper's own caveats keep the result in the domain of inspectable/extractable information, not full causal explanation.

Within `neural_nlp_probing`, this page is the main edge-probing and layer-order source. It should stay on the probing side of the wiki boundary rather than being folded into `induction_heads_icl`.

## Related Pages
- [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]]
- [[../concepts/Probing Classifiers|Probing Classifiers]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]

## Source Identification
- Authors: Ian Tenney, Dipanjan Das, and Ellie Pavlick
- Title: *BERT Rediscovers the Classical NLP Pipeline*

## Open Questions
- Does the same layer ordering hold in later transformer families and multilingual models?
- How much of the apparent pipeline organization survives fine-tuning?
