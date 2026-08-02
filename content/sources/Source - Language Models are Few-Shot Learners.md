---
title: Source - Language Models are Few-Shot Learners
type: source
status: active
updated: 2026-07-28
ingestion_depth: deep
tags:
  - source
  - deep
  - gpt-3
  - in-context-learning
  - scaling
  - prompting
---

## Summary
Tom Brown and colleagues argue that large-scale autoregressive language modeling can produce broad few-shot and zero-shot task performance without gradient-based fine-tuning. GPT-3 is presented as a model that can be steered by textual instructions and examples alone across translation, question answering, cloze completion, commonsense, and several synthetic tasks. For WoLaLa, the paper is foundational because it made in-context learning a central research object and turned prompting from an auxiliary interface into part of the model's apparent competence profile.

## Strand Connections

- Primary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Key Points
- GPT-3 scales the autoregressive pretraining program to 175 billion parameters and evaluates it in zero-shot, one-shot, and few-shot prompting settings.
- The core claim is that task behavior can be conditioned through text alone, without parameter updates on the target task.
- The paper treats scale as a driver of emergent task generality, but it also records persistent failures, contamination risks, and uneven reasoning performance.
- Few-shot prompting becomes an epistemic issue as well as an engineering trick: one must ask what the prompt is eliciting, simulating, or reconfiguring inside the model.
- The source is historically central because later debates on prompting, in-context learning, and `foundation models` presuppose this shift.

## Details
GPT-3 generalizes the GPT-2 picture in two linked ways. First, it scales the model and training regime dramatically. Second, it formalizes evaluation around textual conditioning rather than fine-tuning. Tasks are specified by prompts, examples, or instructions placed into the model's context window, and the model completes the pattern.

This matters because it alters what counts as success. Under a fine-tuning regime, good performance can always be attributed partly to task-specific supervised adaptation. GPT-3 instead suggests that a large amount of task structure can be induced from context at inference time. The model looks less like a frozen feature extractor and more like a system whose behavior can be reconfigured by examples.

The paper also helps explain why later LLM debates became so unstable. GPT-3 performs strongly on many tasks, including some that look reasoning-like, but it also exhibits obvious fragilities, benchmark contamination concerns, and failures on tasks that require more than pattern extension from examples. As a result, the source simultaneously empowered strong claims about emergent generality and strong cautions about over-interpretation.

For WoLaLa, GPT-3 is especially important at the junction of competence and mind-design questions. It raises the possibility that flexible language behavior can arise from a single predictive architecture under scale, but it does not by itself explain what internal mechanisms support that flexibility. Later reverse-engineering work and skeptical theory-facing work both start from this gap.

## Interpretation
This paper should not be read as showing that scale alone solves understanding, explanation, or grounding. Its strongest and most durable contribution is methodological: it establishes prompting and few-shot conditioning as central phenomena that any theory of modern language models must account for.

That makes it a key companion to both optimistic and skeptical sources. It strengthens scaling-based arguments that many tasks can be learned implicitly from text, but it also sharpens the need for careful evaluation, contamination analysis, and mechanistic interpretation. If GPT-3 appears to perform a task from examples alone, the remaining question is what exactly the examples are doing.

## Related Pages
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - Language Models are Unsupervised Multitask Learners|Source - Language Models are Unsupervised Multitask Learners]]
- [[../sources/Source - The Bitter Lesson|Source - The Bitter Lesson]]
- [[../sources/Source - When Do You Need Billions of Words of Pretraining Data|Source - When Do You Need Billions of Words of Pretraining Data]]

## Source Identification
- Authors: Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, and many others
- Title: "Language Models are Few-Shot Learners"
- Year: 2020
- Source type: journal-preprint / technical report
- Publication context: arXiv preprint from OpenAI

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2005.14165)
- DOI / publisher: [OpenAI PDF mirror is cited through arXiv record](https://arxiv.org/pdf/2005.14165)

## Open Questions
- Which apparent few-shot capabilities are best explained as pattern completion, and which require richer task abstraction?
- How should in-context learning be compared with explicit parameter updating as a learning mechanism?
