---
title: Source - Analysis Methods in Neural Language Processing
type: source
status: active
updated: 2026-07-25
ingestion_depth: deep
tags:
  - source
  - deep
  - methodology
  - evaluation
  - neural-nlp
---

## Summary
Yonatan Belinkov and James Glass survey the main traditions for analyzing neural NLP systems and, more importantly, distinguish what kinds of conclusions those methods can and cannot support. The paper is deep for WoLaLa not because it exhausts all later LLM-era methodology, but because it organizes a durable evidential problem: researchers often want to move from probes, visualizations, challenge sets, or attribution methods to stronger claims about what a model represents, knows, or understands. Belinkov and Glass provide a structured map of those tools, their strengths, and their interpretive limits. That makes the paper a methodological anchor for strands 6 and 1 rather than a merely supporting survey.

## Key Points

- The survey groups neural NLP analysis methods into a family of distinct evidential tools rather than one unified paradigm.
- Probing, visualization, challenge sets, adversarial testing, and explanation methods answer different questions and license different inferences.
- The paper repeatedly cautions against overreading analysis outputs as direct evidence of linguistic competence or explanatory understanding.
- Its enduring value for WoLaLa lies in evidence standards: not every interesting diagnostic result is a strong claim about model knowledge.
- The source broadens the existing probing cluster without collapsing probing, analysis, and causal explanation into one category.

## Strand Connections

- Primary: [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] (strand 6)
- Secondary: [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]] (strand 1)

## Details
Belinkov and Glass start from a basic but still central problem: neural NLP systems became successful before they became easily interpretable. That shift generated a secondary literature devoted to asking what models encode, how they process language, and how researchers should examine their internal states and outputs. The survey maps that literature into a set of recurring method families rather than treating interpretability as one homogeneous task.

Among the most important families are auxiliary prediction methods such as probing, visualization techniques, challenge-set style behavioral analysis, adversarial examples, erasure and attribution approaches, and broader diagnostic evaluations. The paper's value is not simply descriptive. It stresses that each method exposes a different slice of model behavior. A probing result may show extractability under a flexible readout; a challenge set may reveal a competence or failure pattern; a saliency method may highlight sensitivity; a visualization may suggest structure. None of those automatically settles what internal representation means, whether a capacity is robustly deployed, or whether a model is using the linguistically interesting feature in the intended way.

That distinction is exactly why the source deserves deep treatment in WoLaLa. Much of the repository's current evidence base already relies on representational analysis, especially within [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]. Belinkov and Glass widen the frame. They show that probing is one method among several, and that interpretive caution should apply across the whole family. This is especially helpful for the applications-and-best-practices strand, where the real issue is often not whether a tool is interesting but whether it is being used responsibly and reproducibly to support a claim.

The survey also helps maintain a three-way distinction that matters throughout the wiki. Analysis methods are not identical with probing methods. Neither is identical with causal or mechanistic evidence. A model may score well on diagnostic tests or show interpretable internal correlations without that amounting to a mechanistic explanation of how the behavior is produced. The paper does not fully solve this problem, especially relative to newer LLM work, but it gives a clear early map of why these evidential levels should be separated.

## Interpretation
This source primarily supports [[../overviews/Applications and Best Practices Overview|Applications and Best Practices]] and secondarily [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations]]. It is best read as a methodology-and-evidence anchor. Its strongest contribution is not one preferred tool, but a disciplined way of asking what a given tool actually shows.

For WoLaLa, that matters in at least three places. First, it strengthens caution around competence claims: a diagnostic success should not be confused with broad linguistic understanding. Second, it disciplines interpretability rhetoric: model analysis can illuminate behavior without yet amounting to explanation. Third, it gives strand 6 a more precise methodological center, one tied to language-focused analysis practice rather than to generic AI deployment.

The paper also sits productively beside [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Belinkov]]'s later probing-focused review. That source sharpens one subliterature in depth; this survey provides the wider analytical map in which probing is only one instrument. Read together, they help the wiki resist two temptations at once: treating probing as the whole evidential story, and treating any method that touches model internals as if it already delivered causal understanding.

## WoLaLa Relevance
The source helps structure recurring WoLaLa questions about:

- which analysis results support claims about linguistic competence rather than mere extractability;
- how to distinguish descriptive diagnostics from stronger explanatory claims;
- what responsible methodological use of analysis tools should look like in language-centered research;
- why evidence standards matter when evaluating claims about language-model knowledge.

## Limitation Or Open Question
The survey belongs to the pre-chatbot neural NLP analysis era, so it does not directly settle how its method families transfer to present large language models, multimodal systems, or more intervention-heavy interpretability work. The open question is which parts of its evidential map remain stable across scale changes and which now require new categories, especially around causal analysis, workflow reproducibility, and model-assisted research practice.

## Related Pages
- [[../overviews/Applications and Best Practices Overview|Applications and Best Practices Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../analyses/What Probing Evidence Can Support|What Probing Evidence Can Support]]
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Source - Probing Classifiers Promises Shortcomings and Advances]]

## Source Identification
- Authors: Yonatan Belinkov and James Glass
- Title: *Analysis Methods in Neural Language Processing: A Survey*
- Year: 2019
- Source type: survey article
- Publication: *Transactions of the Association for Computational Linguistics* 7, 49-72

## Source Access
- Public source: [MIT Press / TACL article page](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00254/43503/Analysis-Methods-in-Neural-Language-Processing-A)
- DOI / publisher: [DOI landing page](https://doi.org/10.1162/tacl_a_00254)

## Open Questions
- Which of the survey's analysis categories still function well at contemporary LLM scale, and which are now too weak without intervention-based support?
- How should strand 6 distinguish language-oriented methodological best practice from the broader interpretability literature?
- When does an analysis method support a claim about competence, and when does it only support a weaker claim about accessible information?
