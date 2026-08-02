---
title: Source - Three Models for the Description of Language
type: source
status: active
updated: 2026-07-27
ingestion_depth: deep
tags:
  - source
  - deep
  - chomsky
  - formal-language-theory
  - theoretical-linguistics
  - history
---

## Summary
Noam Chomsky's 1956 article "Three Models for the Description of Language" is a compact but foundational formal-language paper comparing three model classes for syntax: finite-state Markov processes, phrase-structure grammars, and transformational grammars. Its central claim is not merely that one can generate strings in different ways, but that the choice of formal model matters for linguistic adequacy. Chomsky argues that finite-state models are too weak for natural-language syntax, that phrase-structure grammars improve expressive adequacy, and that transformational analysis is needed to capture deeper structural relations economically. For WoLaLa, the paper matters because it anchors one of the oldest still-live questions in [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4): what kind of formal system is needed to model human language well, and what follows when successful language models do not look like the symbolic formalisms that earlier theory treated as indispensable?

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling]] (strand 9)

## Key Points
- The article compares finite-state, phrase-structure, and transformational models as distinct formal descriptions of language.
- Chomsky argues that finite-state Markov models are too weak to characterize important natural-language dependencies.
- Phrase-structure grammars improve descriptive power by building hierarchical constituency rather than only sequential transitions.
- Transformational grammar is introduced as a way to relate structurally connected sentence types without brute-force enumeration.
- The paper is centrally about formal generative capacity and linguistic adequacy, not about language acquisition, psycholinguistics, or neural modeling.
- It is historically important for current LLM debates because it established a classic anti-finite-state challenge that later statistical and neural work is often taken either to pressure or to evade.

## Details
The article is organized around a clear comparative question: what sort of formal device can describe the set of sentences in a natural language in a way that is both mathematically explicit and linguistically adequate? Chomsky's answer proceeds by contrast.

Finite-state Markov models treat language as a process moving through a bounded set of states and emitting one symbol after another according to transition probabilities or transition rules. Chomsky's critique is that this sequential architecture cannot capture important long-distance and hierarchical dependencies in natural language except by resorting to ad hoc machinery that undermines the formal simplicity that made the model attractive in the first place. The paper is therefore one of the canonical early arguments that language cannot be modeled adequately as mere local sequencing.

Phrase-structure grammars improve on this by representing sentences in terms of hierarchical constituency. Instead of only predicting the next symbol from the previous state, the grammar derives sentences through rule-based expansion of categories and subcategories. This makes it possible to represent structural relations that finite-state descriptions handle poorly or not at all. But phrase-structure grammars are still not presented as the final answer.

Transformational grammar enters because Chomsky wants a model that can relate sentence forms that appear structurally connected while preserving a more economical underlying description. The point is not only to generate more sentences, but to explain systematic correspondences among them. In that sense, the paper already distinguishes sheer coverage from explanatory usefulness: a model should not merely list or overgenerate strings, but should capture the right structural generalizations.

That is where the paper's importance for WoLaLa lies. The article is often remembered as an anti-finite-state argument, and that memory is broadly correct, but incomplete. Its deeper contribution is to connect formal expressiveness with linguistic adequacy. A model of language should be judged not only by whether it can output well-formed sentences, but by whether it captures the relevant structural organization economically and systematically.

This matters for current language-model debates because modern neural systems complicate the old contrast. Large language models are not hand-built phrase-structure or transformational grammars, yet they can display striking competence on many syntax-sensitive tasks. That does not retroactively erase Chomsky's 1956 argument. It instead raises a more precise question: if finite-state-style local sequencing was not enough, what exactly have modern distributed predictive systems learned that allows them to succeed where simpler sequence models were supposed to fail? The paper remains useful because it keeps the target clear: linguistic success is not only a matter of surface string generation, but of what structural relations a model can represent and generalize.

## Interpretation
This source should not be collapsed into the later and broader symbolic program of generative grammar, and it should not be treated as identical with *Syntactic Structures*. The local file used here is specifically the 1956 IEEE article "Three Models for the Description of Language." It predates the mature textbook-style role that *Syntactic Structures* later played, and it is narrower in focus: a formal comparison of model classes for describing language.

That distinction matters. If current LLMs are said to `refute Chomsky`, one needs to ask which claim is being targeted. This 1956 article is mainly a formal and methodological claim about the inadequacy of finite-state descriptions and the need for richer structure. Modern language models do not straightforwardly vindicate or overturn it. They instead force a harder question about whether distributed predictive systems can realize structure-sensitive generalization without explicitly instantiating the symbolic formalisms that Chomsky argued for.

The article is therefore best read as a historical anchor and a conceptual standard-setter. It does not show that neural language models are impossible, but it does explain why arguments about surface sequence modeling versus hierarchical structure became central in the first place. It also shows why formal generative capacity and linguistic adequacy should not be treated as interchangeable notions.

## Related Pages
- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../overviews/Historical Perspectives on Language, Mind, and Modeling Overview|Historical Perspectives on Language, Mind, and Modeling Overview]]
- [[../sources/Source - Modern Language Models Refute Chomsky|Source - Modern Language Models Refute Chomsky]]
- [[../sources/Source - Why Large Language Models Are Poor Theories of Human Linguistic Cognition|Source - Why Large Language Models Are Poor Theories of Human Linguistic Cognition]]
- [[../sources/Source - Emergent Linguistic Structure in Artificial Neural Networks Trained by Self-Supervision|Source - Emergent Linguistic Structure in Artificial Neural Networks Trained by Self-Supervision]]

## Source Identification
- Author: Noam Chomsky
- Title: "Three models for the description of language"
- Year: 1956
- Source type: journal article
- Publication: *IEEE Transactions on Information Theory* 2(3), 113-124
- DOI: `10.1109/TIT.1956.1056813`
- Note on identity: this page covers the 1956 article only. It is not a page for *Syntactic Structures*, which was not locally available in this intake wave and was not ingested here.

## Source Access
- DOI / publisher: [DOI landing page](https://doi.org/10.1109/TIT.1956.1056813)
- Public source: [IEEE Xplore article page](http://ieeexplore.ieee.org/document/1056813/)

## Open Questions
- Which current language-model results bear most directly on the original anti-finite-state argument, as opposed to on later and broader Chomskyan claims?
- Can modern distributed models be said to realize phrase-structure-like or transformation-sensitive generalization without explicit symbolic encoding?
- How should the distinction between formal generative capacity and linguistic adequacy be reframed for neural models that succeed behaviorally without matching classical grammar formalisms?
