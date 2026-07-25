---
title: Source - Language Models Mostly Know What They Know
type: source
status: active
updated: 2026-05-04
tags:
  - source
  - llms
  - calibration
  - self-evaluation
  - honesty
---

## Summary
Saurav Kadavath and collaborators study whether language models can estimate when their own answers are likely to be correct. The paper's central result is more cautious than its title can sound: larger models are often well calibrated on appropriately formatted multiple-choice and true/false questions, and they can give useful self-evaluations such as `P(True)` and `P(IK)`, but this ability is uneven and only partly generalizes across tasks. The paper is therefore relevant not because it settles understanding claims, but because it shows that some forms of metacognitive self-assessment are available without licensing a broad jump to human-like semantic grasp.

## Key Points
- the paper asks whether language models can evaluate the validity of their own claims and predict which questions they can answer correctly.
- it reports that larger models can be well calibrated on some multiple-choice and true/false tasks when the format is appropriate.
- it studies `P(True)`, the probability that a proposed answer is correct, as one route to self-evaluation on open-ended tasks.
- it also studies `P(IK)`, the probability that the model knows the answer to a question without first committing to a particular answer.
- it finds encouraging performance and scaling trends, but also partial rather than complete generalization across tasks.
- it treats better self-evaluation as groundwork for more honest systems rather than as proof of strong understanding.

## Details
The paper is organized around a narrower question than most philosophical debates about meaning or understanding. Instead of asking whether a model genuinely understands language, it asks whether a model can tell when its own answers are likely to be right or wrong.

That narrower framing is valuable because it separates self-evaluation from both raw generation quality and broad human-analogous intelligence claims. Kadavath et al. show that large models can often assign useful confidence estimates when questions are posed in suitable formats. In particular, they report good calibration on diverse multiple-choice and true/false tasks, and they use this as a basis for asking models to estimate `P(True)` for their own answers on more open-ended tasks.

The paper also goes beyond answer-specific confidence by studying `P(IK)`, the probability that the model knows the answer to a question without reference to one particular proposed answer. That is a more ambitious form of self-assessment, and the results are correspondingly more limited. The paper reports partial cross-task generalization and difficulties with calibration on new tasks, even where the basic approach remains promising.

This makes the source especially useful as a limit-and-capability paper. It argues neither that models are hopelessly unaware nor that they possess rich introspective understanding. Instead, it shows that self-evaluation can be elicited and improved in some settings, while still remaining fragile, format-sensitive, and narrower than the strongest claims about understanding or honesty might suggest.

## Interpretation
This source is a supporting qualification inside the current WoLaLa cluster. It pushes against a crude picture on both sides: models are not simply blind to their own correctness, but their ability to know when they know is still task-bound enough that it should not be mistaken for full semantic understanding.

It pairs naturally with [[Source - The Generative AI Paradox|West et al.]]. West et al. argue that generation can outrun understanding; Kadavath et al. show that models can nevertheless recover some self-evaluative grip on correctness in constrained settings. Taken together, the two papers sharpen the difference between fluent production, selective understanding, and metacognitive calibration.

## Related Pages
- [[../concepts/Meaning and Reference in Language Models|Meaning and Reference in Language Models]]
- [[../analyses/What Would Count as Meaning or Reference in a Language Model|What Would Count as Meaning or Reference in a Language Model]]
- [[../overviews/Meaning, Reference, and Distributional Language Overview|Meaning, Reference, and Distributional Language Overview]]

## Source Identification
- Authors: Saurav Kadavath, Tom Conerly, Amanda Askell, Tom Henighan, Dawn Drain, Ethan Perez, Nicholas Schiefer, Zac Hatfield-Dodds, Nova DasSarma, Eli Tran-Johnson, Scott Johnston, Sheer El-Showk, Andy Jones, Nelson Elhage, Tristan Hume, Anna Chen, Yuntao Bai, Sam Bowman, Stanislav Fort, Deep Ganguli, Danny Hernandez, Josh Jacobson, Jackson Kernion, Shauna Kravec, Liane Lovitt, Kamal Ndousse, Catherine Olsson, Sam Ringer, Dario Amodei, Tom Brown, Jack Clark, Nicholas Joseph, Ben Mann, Sam McCandlish, Chris Olah, and Jared Kaplan
- Title: *Language Models (Mostly) Know What They Know*
- Source type: paper

## Open Questions
- How far can self-evaluation improve without changes to the model's underlying representational or reasoning abilities?
- Does good calibration on constrained tasks support any stronger claim about semantic competence, or only about answer-quality prediction?
- In what settings does `P(IK)` reveal a real metacognitive ability rather than a learned pattern over task formats?
