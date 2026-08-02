---
title: Source - How to Grow a Mind
type: source
status: active
updated: 2026-07-25
ingestion_depth: deep
tags:
  - source
  - deep
  - cognition
  - abstraction
  - bayesian-models
---

## Summary
Joshua B. Tenenbaum, Charles Kemp, Thomas L. Griffiths, and Noah D. Goodman present a compact but programmatic case for Bayesian cognitive science. Their central claim is that human learning achieves strong generalization from sparse and noisy evidence because it operates over structured hypotheses, abstract representations, and probabilistic inference rather than over flat association alone. The paper moves from concept learning and causal induction to language and intuitive theory-building, using these cases to argue that cognition should be understood as inference over rich internal models of the world. For WoLaLa, the source is not just background. It is a deep methodological anchor for disputes about whether human-like learning requires structured inductive bias, what counts as explanation in reverse engineering the mind, and how far broad statistical success can stand in for richer cognitive modeling.

## Key Points

- The paper frames cognition through the problem of getting rich generalizations from sparse data.
- Its answer is that learners rely on prior structure, abstraction, and probabilistic inference over hypotheses.
- Bayesian modeling is presented less as a single trick than as a reverse-engineering framework for cognition.
- Language learning matters centrally because it sharpens the poverty-of-the-stimulus problem and the role of inductive bias.
- The source is especially useful for WoLaLa because it articulates a clear alternative to scale-only pictures of intelligence without rejecting statistical learning.

## Strand Connections

- Primary: [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] (strand 5)
- Secondary: [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]] (strand 7)

## Details
The paper opens from a broad cognitive-science question: how do minds get so much from so little? Tenenbaum and colleagues treat that question as a version of the classic problem of induction. Learners routinely move far beyond the data they have actually observed, whether in concept learning, causal reasoning, language acquisition, or theory construction. The authors argue that this feat cannot be explained by data accumulation alone. Some prior structure must narrow the space of live hypotheses and make certain generalizations more compelling than others.

Their positive proposal is that Bayesian inference offers a principled way to combine sparse evidence with structured prior knowledge. The point is not simply that learners assign probabilities. It is that they infer over richly organized representations: trees for taxonomic concepts, causal graphs for causal knowledge, grammars and other structured symbolic systems for language, and more abstract theories for domains such as intuitive physics or psychology. In this picture, abstraction is not a decorative extra. It is what makes strong generalization computationally possible.

The paper uses language as one of its clearest pressure points. It treats word learning, grammar acquisition, and poverty-of-the-stimulus style problems as cases where the data available to learners appear radically underdetermining unless some structured prior knowledge is brought to bear. This makes language a central case for their broader methodological claim: reverse engineering the mind requires specifying the representational form of what is learned, not only the amount of data or the optimization process.

For WoLaLa, the most important feature of the paper is its explicit relation between cognitive explanation and AI. The authors treat cognitive science as a reverse-engineering project adjacent to AI but not reducible to it. AI provides computational tools and hypotheses, yet the explanatory target remains human intelligence. That distinction matters because it resists an easy slide from empirical language-model performance to conclusions about human cognition. The source therefore helps sharpen a live contrast in the wiki: scalable statistical success may reveal something important about learning, but that does not eliminate questions about structured representation, abstraction, or what sort of model of mind an artificial system actually is.

## Interpretation
This source primarily supports [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives]] and secondarily [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering]]. Its main value is methodological. It gives one of the clearest compact statements of why many cognition-facing researchers insist that explanation requires more than impressive output behavior or broad pattern extraction. The paper does not deny the importance of statistical learning. Instead, it argues that the right way to understand successful learning is as probabilistic inference over structured hypotheses.

That makes the source especially useful beside [[../sources/Source - The Bitter Lesson|The Bitter Lesson]]. Sutton emphasizes the long-run power of general compute-leveraging methods; Tenenbaum and colleagues emphasize the explanatory importance of abstraction and structured inductive bias. Together they help define a productive WoLaLa tension rather than a simple opposition. The resulting question is not whether learning is statistical or structured, but what kinds of structure must be represented, learned, or discovered for a model to count as a serious account of language-capable intelligence.

## WoLaLa Relevance
The paper helps frame several recurring WoLaLa disputes:

- whether broad pattern-learning success is enough to explain language-relevant cognition;
- whether inductive bias and structured representation remain necessary explanatory commitments;
- whether reverse engineering should target human-like learning from limited data rather than only high aggregate performance;
- whether language-learning arguments still constrain what counts as a plausible cognitive model in the era of large-scale language models.

## Limitation Or Open Question
This is a broad review and manifesto for a research program, not a direct empirical confrontation with current LLMs. It therefore does not by itself show which parts of the structured-probabilistic framework remain indispensable under contemporary large-scale training regimes. The main open question is how much of the paper's picture should be preserved as an explanatory constraint on language-model interpretation, and how much should be treated as a historically important alternative research program whose strongest challenges now need to be reformulated.

## Related Pages
- [[../overviews/Cultural, Cognitive, and SSH Perspectives Overview|Cultural, Cognitive, and SSH Perspectives Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]
- [[../sources/Source - The Child as Hacker|Source - The Child as Hacker]]
- [[../sources/Source - The Bitter Lesson|Source - The Bitter Lesson]]

## Source Identification
- Authors: Joshua B. Tenenbaum, Charles Kemp, Thomas L. Griffiths, and Noah D. Goodman
- Title: *How to Grow a Mind: Statistics, Structure, and Abstraction*
- Year: 2011
- Source type: review article
- Publication: *Science* 331(6022), 1279-1285

## Source Access
- DOI / publisher: [Science article page](https://www.science.org/doi/10.1126/science.1192788)

## Open Questions
- How far should structured inductive bias be treated as a real constraint on language-model interpretation, rather than as a historical research preference?
- Can modern large-scale models be understood as discovering some of the structure this paper treats as cognitively central, or do they leave its core explanatory challenge intact?
- Which parts of the Bayesian cognitive-science program are best read as claims about human cognition, and which as claims about rational learning more generally?
