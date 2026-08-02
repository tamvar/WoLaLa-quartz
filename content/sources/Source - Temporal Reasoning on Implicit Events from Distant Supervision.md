---
title: Source - Temporal Reasoning on Implicit Events from Distant Supervision
type: source
status: active
updated: 2026-07-27
ingestion_depth: brief
tags:
  - source
  - brief
  - evaluation
  - temporal-reasoning
  - commonsense
  - benchmark
---

## Summary
Ben Zhou, Kyle Richardson, Qiang Ning, Tushar Khot, Ashish Sabharwal, and Dan Roth's "Temporal Reasoning on Implicit Events from Distant Supervision" introduces TRACIE, a dataset for temporal reasoning that requires systems to infer events not explicitly stated in the text. The paper matters for WoLaLa because it sharpens a recurring point in language-model evaluation: fluent surface processing is not enough when the task requires implicit-event reconstruction, commonsense temporal inference, and rule-guided reasoning across stated and unstated events.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)

## WoLaLa Relevance
This source primarily supports [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] and secondarily [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]]. It gives a concrete evaluation case where reasoning about language depends on inferred events rather than only lexical overlap or explicit propositions, which makes it useful for judging stronger claims about model understanding.

## Limitation Or Open Question
The paper is task- and dataset-focused, so its conclusions are bounded by the benchmark design. It shows that implicit-event temporal reasoning is hard and that neuro-symbolic methods can help, but it does not establish how general those gains are outside the benchmark or whether they reflect broader language understanding.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../sources/Source - CommonsenseQA|Source - CommonsenseQA]]
- [[../sources/Source - The Defeat of the Winograd Schema Challenge|Source - The Defeat of the Winograd Schema Challenge]]
- [[../sources/Source - Language Models Show Human-Like Content Effects on Reasoning Tasks|Source - Language Models Show Human-Like Content Effects on Reasoning Tasks]]

## Source Identification
- Authors: Ben Zhou, Kyle Richardson, Qiang Ning, Tushar Khot, Ashish Sabharwal, and Dan Roth
- Title: "Temporal Reasoning on Implicit Events from Distant Supervision"
- Year: 2021
- Source type: benchmark / method paper
- Publication: *Proceedings of NAACL-HLT 2021*, 1361-1371
- DOI: `10.18653/v1/2021.naacl-main.107`

## Source Access
- Public source: [ACL Anthology page](https://aclanthology.org/2021.naacl-main.107/)
- DOI / publisher: [DOI landing page](https://doi.org/10.18653/v1/2021.naacl-main.107)
