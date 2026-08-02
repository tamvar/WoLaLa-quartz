---
title: Source - Building Machines That Learn and Think Like People
type: source
status: active
updated: 2026-07-27
ingestion_depth: deep
tags:
  - source
  - deep
  - cognition
  - reverse-engineering
  - causal-models
  - compositionality
---

## Summary
Lake, Ullman, Tenenbaum, and Gershman argue that genuinely human-like AI will require more than end-to-end statistical success on benchmark tasks. Their proposal centers on three demands: systems should build causal models of the world, rely on intuitive theories such as folk physics and psychology, and support compositionality plus learning-to-learn for fast generalization from sparse data. For WoLaLa, the paper is a major cross-strand anchor because it directly challenges the idea that current scaling trends alone provide an adequate route to human-like language-capable intelligence.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Key Points
- The paper argues that human-like intelligence depends on more than performance optimization over large datasets.
- Causal modeling matters because intelligent systems should explain and understand the world, not merely recognize patterns.
- Intuitive theories of physics and psychology are presented as central background structures for human learning and generalization.
- Compositionality and learning-to-learn are treated as key mechanisms for rapid acquisition and transfer.
- The paper explicitly seeks a route that combines neural-network strengths with more structured cognitive models.

## Details
The paper opens from a familiar contrast. Deep neural systems have achieved striking successes in object recognition, speech, games, and control, but the authors argue that these gains still leave important gaps relative to human intelligence. Their concern is not only that current systems make errors. It is that they often solve tasks without the kinds of structured world models and rapid concept acquisition that characterize human cognition.

The first major requirement is causal modeling. Systems should not merely map inputs to outputs or compress statistical regularities. They should represent how the world works in a way that supports explanation, counterfactual reasoning, and flexible inference. This matters for WoLaLa because many current disputes about language models turn on whether successful text behavior is enough, or whether robust language understanding requires a richer model of agents, events, causes, and situations.

The second requirement is intuitive theory structure. The authors argue that people learn on top of frameworks resembling intuitive physics and intuitive psychology. These frameworks constrain hypotheses and make sparse-data learning possible. In WoLaLa terms, this is one of the clearest modern defenses of structured inductive bias against the view that broad statistical learning alone is the whole story.

The third requirement is compositionality with learning-to-learn. Human learners can recombine familiar pieces into new representations and adapt quickly from small numbers of examples. The paper treats this as a central reason current engineering systems remain cognitively unlike people even when they perform well on specific tasks.

Importantly, the paper is not anti-neural or anti-learning. It proposes combining the strengths of recent neural advances with more structured cognitive models. That makes it a productive counterpart to [[../sources/Source - The Bitter Lesson|The Bitter Lesson]] rather than a simple rejection of it. Sutton emphasizes the long-run power of general compute-leveraging methods; Lake and colleagues emphasize what kinds of representational and inferential structure human-like intelligence appears to need.

## Interpretation
This source is one of the clearest anchors for the cognition side of WoLaLa. It does not show that language models cannot develop more human-like capacities, but it argues that success will depend on richer structure than current benchmark triumphalism often assumes. It is therefore a direct challenge to any easy slide from scale-driven performance gains to claims of human-like thought.

At the same time, the paper should not be read as proving that all required structure must be hand-built. Its constructive force lies in identifying functional demands, not in fixing one final implementation recipe. That leaves open a live WoLaLa question: which of these demands might emerge from large-scale learning, and which require more explicit architectural or representational commitments?

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - How to Grow a Mind|Source - How to Grow a Mind]]
- [[../sources/Source - Bayesian Models of Cognition|Source - Bayesian Models of Cognition]]
- [[../sources/Source - The Bitter Lesson|Source - The Bitter Lesson]]

## Source Identification
- Authors: Brenden M. Lake, Tomer D. Ullman, Joshua B. Tenenbaum, and Samuel J. Gershman
- Title: "Building Machines That Learn and Think Like People"
- Year: 2017
- Source type: journal article
- Publication: *Behavioral and Brain Sciences* 40:e253

## Source Access
- DOI / publisher: [Cambridge Core / Behavioral and Brain Sciences](https://doi.org/10.1017/S0140525X16001837)

## Open Questions
- Which of the paper's four pressures on current AI are most relevant to language models specifically: causal models, intuitive theories, compositionality, or learning-to-learn?
- How should this structured-cognition program be related to later scaling-based arguments such as [[../sources/Source - The Bitter Lesson|The Bitter Lesson]]?
