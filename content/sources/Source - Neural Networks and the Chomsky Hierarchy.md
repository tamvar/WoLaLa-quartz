---
title: Source - Neural Networks and the Chomsky Hierarchy
type: source
status: active
updated: 2026-07-28
ingestion_depth: deep
tags:
  - source
  - deep
  - formal-language-theory
  - generalization
  - chomsky-hierarchy
  - neural-networks
---

## Summary
Gregoire Deletang and colleagues investigate how far different neural architectures can generalize on sequence tasks organized by the Chomsky hierarchy. Their central claim is sharply negative for many familiar architectures: RNNs and Transformers may fit training data on harder formal-language tasks, but they fail to generalize out of distribution in the way stronger automata would predict. For WoLaLa, the paper matters because it reconnects current neural-model evaluation to an older formal-language question about computational class, memory structure, and the difference between in-distribution fit and rule-governed generalization.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Key Points
- The paper organizes sequence-generalization tasks by the Chomsky hierarchy and compares neural architectures against those levels.
- It argues that architectural memory constraints matter strongly for out-of-distribution generalization.
- Standard RNNs and Transformers do not reliably generalize on non-regular tasks in the studied setup.
- LSTMs do better on some counter-language cases, while stack- or tape-augmented systems are needed for stronger classes.
- The source is important because it separates expressive capacity in principle from practical generalization under training.

## Details
The paper starts from a recurring ambiguity in neural-language-model debates. Researchers often say that a model is `Turing complete` or has enough capacity in principle to represent some computation. But practical generalization is a different matter. Deletang and colleagues therefore ask a more operational question: when models are trained on bounded sequence lengths and then tested on longer or structurally harder examples, which kinds of formal-language regularities do they actually generalize?

Their answer is that the Chomsky hierarchy remains a useful organizing lens. Not because neural networks literally instantiate classical automata, but because differences in memory access and controller structure still predict what sorts of rule systems can be generalized reliably. In the reported experiments, plain RNNs and Transformers do not show robust generalization on non-regular tasks, even when they fit the training data. LSTMs perform somewhat better on counter-language problems, and architectures with explicit stack or tape mechanisms are needed for stronger formal classes.

For WoLaLa, the importance of this result is twofold. First, it offers a more disciplined way to interpret claims that neural sequence models have overcome old formal objections. Second, it sharpens the difference between surface task success and the possession of reusable structural competence. A model can produce good benchmark behavior while still failing the kind of extrapolative generalization that classical theory would treat as decisive.

## Interpretation
This source should not be overread as a final verdict on language models as such. Its tasks are stylized, and natural language is not exhausted by the formal-language cases used here. But the paper does reintroduce an important constraint: architecture and memory matter, and empirical success on bounded data does not automatically answer older questions about rule-governed generalization.

That makes it a strong companion to both [[../sources/Source - Three Models for the Description of Language|Three Models for the Description of Language]] and newer probing or syntactic-evaluation work. It does not say that modern language models are useless for linguistic questions. It says that claims about structural generalization should be made with explicit attention to what class of behavior is actually being tested.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - Three Models for the Description of Language|Source - Three Models for the Description of Language]]
- [[../sources/Source - Recursive Neural Networks Can Learn Logical Semantics|Source - Recursive Neural Networks Can Learn Logical Semantics]]
- [[../sources/Source - What Do RNN Language Models Learn About Filler-Gap Dependencies|Source - What Do RNN Language Models Learn About Filler-Gap Dependencies]]

## Source Identification
- Authors: Gregoire Deletang, Anian Ruoss, Jordi Grau-Moya, Tim Genewein, Li Kevin Wenliang, Elliot Catt, Chris Cundy, Marcus Hutter, Shane Legg, Joel Veness, and Pedro A. Ortega
- Title: "Neural Networks and the Chomsky Hierarchy"
- Year: 2023
- Source type: conference paper
- Publication: ICLR 2023

## Source Access
- Public source: [OpenReview page](https://openreview.net/forum?id=WbxHAzkeQcn)
- DOI / publisher: [arXiv abstract page](https://arxiv.org/abs/2207.02098)

## Open Questions
- How far do these formal-language results transfer to richer natural-language tasks?
- Which language-model behaviors really require stronger memory structure, and which can be explained by weaker but data-rich heuristics?
