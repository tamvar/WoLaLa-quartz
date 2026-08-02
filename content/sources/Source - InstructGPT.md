---
title: Source - InstructGPT
type: source
status: active
updated: 2026-07-29
ingestion_depth: deep
tags:
  - source
  - deep
  - rlhf
  - alignment
  - instruction-following
  - openai
---

## Summary
Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, and Ryan Lowe argue that bigger language models are not automatically better at following user intent. Their solution is instruction tuning plus reinforcement learning from human feedback, yielding InstructGPT models that human raters prefer to much larger base GPT-3 models. For WoLaLa, the paper is a major methodological anchor because it shows that post-training can materially reshape model behavior and evaluation outcomes. That makes it crucial for interpreting what later conversational fluency and helpfulness do or do not reveal about the underlying language model.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## Key Points
- The paper explicitly rejects a simple "scale alone fixes interaction quality" view: raw next-token models are often unhelpful, toxic, or misaligned with user intent.
- Its training pipeline separates three stages: supervised demonstrations, a reward model trained on ranked outputs, and PPO fine-tuning against that reward signal.
- Human preference can make a smaller model outperform a much larger base model on judged helpfulness.
- The source therefore distinguishes base-model competence from post-training behavior more sharply than many downstream discussions do.
- It also connects model evaluation to data collection and human preference design rather than only to public benchmark scores.

## Details
The paper starts from a simple but important complaint: the standard language-model objective does not directly optimize for what users actually want. A model can be strong at continuation while still failing at instruction following, harmlessness, truthfulness, or useful interaction. InstructGPT is presented as a way to shift the target. Demonstration data teaches the model the rough behavioral format, a reward model learns which outputs humans prefer, and reinforcement learning further tunes behavior toward those preferences.

The empirical headline is that a 1.3B InstructGPT model can be preferred by human raters over the untuned 175B GPT-3 baseline. That result matters for WoLaLa not as a simple product story, but as a warning about interpretation. If post-training changes user-facing behavior this much, then strong conversational performance should not be read as a transparent window onto the competencies of the underlying pretraining objective alone. Later claims about understanding, reasoning, or helpfulness may depend heavily on alignment procedures, demonstration distributions, and reward-model choices.

This gives the paper a dual significance. In strand 6, it is a best-practices and methodology anchor because it turns evaluation toward user-centered objectives and exposes the importance of preference data. In strand 1, it is a competence-interpretation caution because it shows that surface helpfulness can be strongly shaped after pretraining. A model may appear more aligned, more truthful, or more responsive without that amounting to a straightforward gain in all underlying forms of linguistic or semantic competence.

## Interpretation
This source does not show that RLHF solves the alignment problem or that human preference is an adequate final target for language-model quality. Its stronger contribution is methodological: it demonstrates that post-training is a major causal layer in how modern LLMs behave. For WoLaLa, that means later performance claims need to ask not only what the base model learned from text, but what the alignment pipeline taught it to display, avoid, or smooth over in interaction.

## WoLaLa Relevance
This source primarily supports [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] and secondarily [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]]. It is especially valuable for:

- distinguishing pretraining competence from aligned interaction behavior;
- clarifying why human evaluation and reward modeling become part of the language-model method stack;
- keeping later chat-style performance claims from being read as if they came only from base language modeling.

## Limitation Or Open Question
The evaluation distribution is still tied to the authors' prompt data and preference protocol, so the paper leaves open how broadly these improvements transfer and what costs accompany them. A continuing WoLaLa question is whether RLHF mainly improves interaction quality, hides failure modes, or in some cases genuinely supports more reliable use of latent model capabilities.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../sources/Source - Language Models are Few-Shot Learners|Source - Language Models are Few-Shot Learners]]
- [[../sources/Source - Learning to Summarize from Human Feedback|Source - Learning to Summarize from Human Feedback]]
- [[../sources/Source - FACTOOL|Source - FACTOOL]]

## Source Identification
- Authors: Long Ouyang, Jeff Wu, Xu Jiang, Diogo Almeida, Carroll L. Wainwright, Pamela Mishkin, Chong Zhang, Sandhini Agarwal, Katarina Slama, Alex Ray, John Schulman, Jacob Hilton, Fraser Kelton, Luke Miller, Maddie Simens, Amanda Askell, Peter Welinder, Paul Christiano, Jan Leike, and Ryan Lowe
- Title: *Training Language Models to Follow Instructions with Human Feedback*
- Year: 2022
- Source type: research paper / arXiv preprint
- Publication context: OpenAI research paper

## Source Access
- Public source: [arXiv abstract page](https://arxiv.org/abs/2203.02155)
