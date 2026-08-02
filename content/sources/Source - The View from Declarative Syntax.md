---
title: Source - The View from Declarative Syntax
type: source
status: active
updated: 2026-08-02
ingestion_depth: deep
tags:
  - source
  - deep
  - theoretical-linguistics
  - declarative-syntax
  - hpsg
  - lfg
---

## Summary

Peter Sells compares the Minimalist Program with two declarative grammatical frameworks, Head-Driven Phrase Structure Grammar (HPSG) and Lexical-Functional Grammar (LFG). He argues that declarative syntax preserves central ambitions associated with generative linguistics—explicit formalization, hierarchical structure, abstract representation, and an account of linguistic knowledge—while rejecting derivations as the core explanatory device. HPSG and LFG characterize well-formed linguistic structures through constraints over interrelated representations rather than through ordered operations that transform one representation into another.

The chapter is therefore not a contrast between formal grammar and an informal alternative. HPSG is an important non-Chomskyan, constraint-based formal counterweight to transformational generative linguistics. Sells presents declarative frameworks as descendants of Chomsky's foundational demand for explicit theories of linguistic knowledge, but as theories with different commitments about representation, lexical information, movement, and the relation between syntactic dimensions.

## Strand Connections

- Primary: [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models]] (strand 4)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## Central Thesis

Declarative frameworks ask what grammatical information is true of a well-formed expression, not what sequence of operations must occur to produce it. For Sells, the difference is architectural. A Minimalist derivation builds and alters representations through operations such as Merge, Agree, and movement. A declarative grammar states monotonic constraints whose simultaneous satisfaction licenses a structure. Relations such as agreement or argument realization are represented directly, often through lexical information and feature sharing, rather than established by a directional procedure.

Sells nevertheless resists treating the two traditions as wholly unrelated. Both pursue explicit accounts of linguistic knowledge, use abstract hierarchical structure, and seek explanatory adequacy. Some representational devices developed in Minimalism have long-standing declarative counterparts. The dispute concerns which properties are fundamental and whether procedural machinery is required.

## Declarative Grammar and Constraint-Based Representation

The chapter uses `declarative` in the logical sense: a grammar specifies conditions that a model must satisfy. Phrase-structure rules can be interpreted as node-admissibility conditions on trees rather than instructions for rewriting symbols. HPSG and LFG accordingly belong to model-theoretic syntax, in contrast with a generative-enumerative conception in which a procedure defines the expressions of a language.

Feature structures are central to this approach. They represent structured grammatical information through attribute–value relations and permit information to be shared across a structure. In HPSG, feature structures characterize words, phrases, valence requirements, and modes of combination. In LFG, constituent structure and functional structure are distinct but systematically related dimensions. Equations constrain how information contributed by words and positions is assembled into a grammatical representation.

These constraints are monotonic: adding information narrows what is licensed but does not destroy already established information. Sells treats this as an intrinsic analogue of the Minimalist No Tampering Condition. From his perspective, a system that can delete, overwrite, or duplicate syntactic substance must add restrictions to prevent overgeneration, whereas a declarative system begins with nondestructive information accumulation.

## Multidimensional Structure

Declarative frameworks factor linguistic organization into dimensions that need not be isomorphic. Phrase structure, grammatical functions, argument structure, lexical information, and linear order can be represented separately and connected by constraints. This permits the same clausal information to receive different surface realizations without treating one as the procedural source of another.

HPSG separates immediate dominance from linear precedence and licenses local structures according to the valence requirements of heads. A finite auxiliary can combine with its dependents through different surface configurations. LFG separates constituent structure from functional structure: a verb may occur in different structural positions while contributing the same information to the clause's functional representation. The analysis of head mobility therefore does not require the head to occupy a series of positions in a derivation.

Sells uses Mandarin verb copying and English coordination to argue that phrase structure is not identical to abstract clausal information. A predicate's relations to arguments and adjuncts may remain stable even when surface structure contains duplicated verbal material or places restrictions on what can appear in a single phrase. Declarative descriptions can represent shared information without assuming that every informational dependency is a movement relation among copies of syntactic substance.

## Movement, Features, and the Lexicon

Movement receives a sharply different treatment. In a derivational account, an expression is associated with successive structural positions; copy theory represents multiple occurrences and determines which are pronounced. In a declarative account, the grammar directly constrains the relation between an overt expression and the information associated with it. Apparent displacement can involve correspondence across dimensions, alternative positions, or feature sharing without a transformational history.

The contrast extends to features. Minimalist features can represent information, establish relations, and trigger operations; some must be uninterpretable or deleted before an interface representation is legitimate. Declarative frameworks use features to state coherent information and compatibility requirements. Agreement is checked by shared or compatible specifications rather than by first introducing a locally defective feature that initiates an operation.

Lexicalism is another genuine difference. HPSG and LFG locate substantial grammatical information in lexical entries and preserve lexical integrity. Sells uses agreement, auxiliary, passivization, and coordination phenomena to motivate this choice. The chapter does not claim that every analysis must be lexical, but it argues that direct lexical encoding avoids derivational mechanisms whose power then requires independent restriction.

## Shared Commitments and Genuine Differences

The comparison should not be reduced to `generative versus non-generative` in an unqualified sense. HPSG and LFG do not generate expressions by a sequence of operations, but they remain rigorous formal grammars that characterize an unbounded set of structured expressions. They share with generative linguistics:

- an explicit theory of grammatical knowledge;
- hierarchical and abstract structure beyond surface strings;
- formal constraints on possible linguistic representations;
- concern with crosslinguistic explanation and learnability;
- an interest in economy and domain-general `third factor` considerations.

The deeper differences concern:

- procedural derivation versus simultaneous constraint satisfaction;
- transformation or copying versus direct representation of correspondence;
- a single derivational structure versus linked representational dimensions;
- operation-triggering features versus informational features;
- the amount and status of lexically encoded grammatical information.

These differences are not merely notational. They change the hypothesis space in which an analysis is stated and therefore what counts as a learnability problem. Sells's treatment of English auxiliary questions, for example, frames acquisition as recognizing alternative ways a main-clause head combines with its dependents, not as learning which auxiliary must move across intervening material.

## WoLaLa Interpretation

The chapter supplies a needed formal alternative to comparisons that oppose generative linguistics only to usage-based learning or neural sequence models. It shows that rejecting transformations does not entail rejecting hierarchy, abstraction, grammatical constraints, or precise symbolic representation. For language-model research, that widens the space of possible explanatory targets: evidence of hierarchical generalization need not by itself discriminate between derivational syntax, constraint-based syntax, or other structured formalisms.

This implication is comparative rather than direct. Sells does not analyze neural language models, and the chapter does not show that HPSG or LFG describes their internal representations. It instead clarifies questions that model evidence would have to answer: whether a system represents grammatical information in separable dimensions, whether observed dependencies require procedural histories, and whether feature relations are better understood as operations or as constraints.

## Limitations and Scope Conditions

- The chapter is an advocate's comparison from a declarative perspective, not a framework-neutral empirical adjudication.
- Its examples demonstrate how declarative analyses can be formulated and where Sells sees derivational burdens; they do not prove that every derivational account is empirically inferior.
- HPSG and LFG differ from one another, especially in phrase structure and representational architecture, and should not be collapsed into one theory.
- The discussion is principally syntactic. It does not evaluate acquisition experiments, psycholinguistic processing models, or neural representations directly.

## Related Pages

- [[../overviews/Theoretical Linguistics and Language Models Overview|Theoretical Linguistics and Language Models Overview]]
- [[../sources/Source - Three Models for the Description of Language|Source - Three Models for the Description of Language]]
- [[../sources/Source - Structural, Functional, and Processing Perspectives on Linguistic Island Effects|Source - Structural, Functional, and Processing Perspectives on Linguistic Island Effects]]
- [[../sources/Source - Chomsky and Usage-Based Linguistics|Source - Chomsky and Usage-Based Linguistics]]
- [[../sources/Source - How Statistical Learning Can Play Well with Universal Grammar|Source - How Statistical Learning Can Play Well with Universal Grammar]]

## Source Identification

- Author: Peter Sells
- Chapter: "The View from Declarative Syntax"
- Year: 2021
- Parent volume: *A Companion to Chomsky*
- Editors: Nicholas Allott, Terje Lohndal, and Georges Rey
- Publisher: Wiley-Blackwell / John Wiley & Sons
- Edition: First edition
- Chapter number: 16
- Printed pages: 245–266
- PDF pages: 262–283
- Parent source ID: `src_companion_chomsky_2021_container`
- Component source ID: `src_companion_chomsky_2021_ch16`
- DOI: `10.1002/9781119598732.ch16`

## Source Access

- Public source: [Wiley chapter page](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119598732.ch16)
- DOI / publisher: [DOI landing page](https://doi.org/10.1002/9781119598732.ch16)

## Open Questions

- Which behavioral or representational tests could distinguish derivational from declarative accounts of a language model's grammatical generalization?
- Can multidimensional constraint-based representations provide better explanatory interfaces for neural analysis than a movement-centered vocabulary?
- How should learnability comparisons control for differences in the representational primitives supplied by competing frameworks?
