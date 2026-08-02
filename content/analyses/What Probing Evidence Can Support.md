---
title: What Probing Evidence Can Support
type: analysis
status: active
updated: 2026-07-29
tags:
  - analysis
  - probing
  - interpretability
---

## Summary
The sources considered here support a graded interpretation of internal-evidence claims. Ordinary probe success most safely supports the claim that a property is extractable from a representation under a particular probe, dataset, and training setup. Stronger claims about encoded structure, behavioral relevance, causal contribution, mechanistic explanation, or linguistic-theoretical significance require additional controls, interventions, comparisons, and links to independent evidence.

## Key Points
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Belinkov]] argues that probe accuracy alone is difficult to interpret without baselines, controls, probe complexity accounting, and clear target definitions.
- [[../sources/Source - Analysis Methods in Neural Language Processing|Belinkov and Glass]] situate probing among a broader family of analysis tools, making clear that different methods justify different strengths of inference.
- [[../sources/Source - What Do NMT Models Learn About Morphology|Belinkov et al. on NMT morphology]] show how diagnostic classifiers can compare where and how linguistic information is extractable across model components.
- [[../sources/Source - What You Can Cram Into a Single Vector|Conneau et al.]] show that sentence embedding probes can reveal many readable properties, but also that surprisingly weak baselines can perform well.
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Hewitt and Manning]] support a narrower geometric claim: parse-tree distances and depths are recoverable after a linear transformation.
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Tenney et al.]], [[../sources/Source - What Does BERT Learn About the Structure of Language|Jawahar et al.]], [[../sources/Source - Open Sesame|Lin et al.]], and [[../sources/Source - Visualizing and Measuring the Geometry of BERT|Coenen et al.]] extend the evidence from simple readout success toward layerwise organization, hierarchy-sensitive diagnostics, and geometric structure.
- [[../sources/Source - Investigating BERT's Knowledge of Language|Warstadt et al. on NPIs]] show that probing can diverge from acceptability, minimal-pair, and cloze-style evidence even when the grammatical phenomenon is held fixed.
- [[../sources/Source - Probing What Different NLP Tasks Teach Machines about Function Word Comprehension|Kim et al. on function-word comprehension]] show that challenge-task results can differ sharply across pretraining objectives even when architecture is held fixed.
- convergent evidence across probe types strengthens confidence that models contain usable internal structure, but it still does not by itself show that the same structure is causally deployed during task behavior.

## Claim Types

The current WoLaLa probing cluster supports several different kinds of claim, which should not be collapsed into one another.

- `Extractability`: a probe can recover property X from representation Y under a specified dataset and readout.
- `Encoded information`: the representation itself contains information about property X in a comparatively robust way across tasks, probes, or layers.
- `Usable representation`: the encoded structure is plausibly available to the model in a way that could matter for downstream behavior.
- `Behavioral relevance`: systems that expose or manipulate this structure also show corresponding behavioral differences on controlled tasks.
- `Causal contribution`: interventions on the representation, component, or circuit alter the relevant behavior in systematic ways.
- `Mechanistic explanation`: the property is not only causally involved but placed inside a broader account of how the system computes the behavior.
- `Theoretical interpretation`: the internal result bears on a claim from linguistics, cognition, or philosophy rather than remaining only a model-internal description.

## Evidence Families

The sources differ in what they actually test.

- sentence embedding probing asks whether global sentence vectors retain surface, syntactic, or semantic properties
- structural probing asks whether token geometry can encode tree distance, depth, or other formal structure
- edge or span probing asks whether contextual token vectors expose localized labels and relations
- layerwise BERT studies ask whether different linguistic properties appear at different depths
- representation-geometry studies ask whether neighborhoods, axes, or transformations reveal semantic or syntactic organization
- architectural comparison studies ask where a property is more or less available across components, languages, or training regimes
- method-comparison studies ask how far conclusions depend on whether the evidence comes from probing, behavior, cloze prediction, or gradient contrasts
- pretraining-objective comparison studies ask which linguistic subskills vary with training signal even when model architecture remains constant

These methods are related, but they do not license equally strong conclusions.

## What Probe Results Most Safely Support

- Ordinary probe success most safely supports: "property X is extractable from representation Y under probe Z."
- Stronger but still cautious comparative claims can be supported when multiple controlled probes converge or when a source compares layers, modules, or architectures under matched conditions.
- [[../sources/Source - What Do NMT Models Learn About Morphology|Belinkov et al. on NMT morphology]] therefore supports claims like "these layers expose more morphology than those layers in these experiments" more strongly than broad claims about how translation is computed.
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Hewitt and Manning]] support a more specific geometric statement than generic edge probing does, but they still do not by themselves show that the model uses tree structure as an explicit causal object.

## What Probe Results Do Not Establish By Themselves

- that the model relies on property X during real task behavior
- that the structure is causally necessary for the behavior
- that the system possesses human-like grammar, semantics, or understanding in a stronger explanatory sense
- that an interpretable axis, layer pattern, or visualization already amounts to a mechanism
- that a linguistic interpretation is uniquely correct among several representational descriptions

This is the main boundary with [[../overviews/Induction Heads and In-Context Learning Overview|the induction-head cluster]]. Probing and related readout methods are primarily evidence about readable structure. Induction-head and circuit work is primarily evidence about implemented behavior and causal contribution.

## What Strengthens A Stronger Claim

Stronger claims need additional evidence such as:

- constrained baselines and complexity controls
- selective and control probes
- convergent results across probe families
- targeted behavioral tests aimed at the same property
- cross-lingual or cross-architecture comparisons
- counterfactual representations or ablations
- interventions on components or activations
- independent theoretical argument about what the discovered structure would mean

This is why probing belongs in a graded evidential map rather than a simple yes-or-no judgment.

## Interpretation
Probing claims should be phrased at the strongest level the evidence actually supports.

- Prefer: "property X is extractable from representation Y under probe Z."
- Use with caution: "model Y encodes X" or "representation Y contains information about X."
- Reserve for stronger multi-method cases: "X is behaviorally relevant to the system's success on task T."
- Avoid without intervention or mechanism evidence: "model Y uses X", "model Y has learned grammar", or "model Y reasons with syntax."

Theoretical interpretation is an additional step again. A probe result can matter for linguistic theory or cognitive modeling, but only after the evidential status of the internal claim itself is made explicit.

## Related Pages
- [[../concepts/Probing Classifiers|Probing Classifiers]]
- [[../concepts/Structural Probes|Structural Probes]]
- [[../concepts/Sentence Embedding Probing|Sentence Embedding Probing]]
- [[../concepts/Linguistic Knowledge in BERT|Linguistic Knowledge in BERT]]
- [[../concepts/Representation Geometry|Representation Geometry]]
- [[../overviews/Neural NLP Probing Overview|Neural NLP Probing Overview]]
- [[../overviews/Linguistic Competence and Limitations Overview|Linguistic Competence and Limitations Overview]]
- [[../overviews/Mind Design and Reverse Engineering Overview|Mind Design and Reverse Engineering Overview]]

## Sources
- [[../sources/Source - Analysis Methods in Neural Language Processing|Source - Analysis Methods in Neural Language Processing]]
- [[../sources/Source - Probing Classifiers Promises Shortcomings and Advances|Source - Probing Classifiers Promises Shortcomings and Advances]]
- [[../sources/Source - What Do NMT Models Learn About Morphology|Source - What Do NMT Models Learn About Morphology]]
- [[../sources/Source - What You Can Cram Into a Single Vector|Source - What You Can Cram Into a Single Vector]]
- [[../sources/Source - A Structural Probe for Finding Syntax in Word Representations|Source - A Structural Probe for Finding Syntax in Word Representations]]
- [[../sources/Source - BERT Rediscovers the Classical NLP Pipeline|Source - BERT Rediscovers the Classical NLP Pipeline]]
- [[../sources/Source - What Does BERT Learn About the Structure of Language|Source - What Does BERT Learn About the Structure of Language]]
- [[../sources/Source - Open Sesame|Source - Open Sesame]]
- [[../sources/Source - Visualizing and Measuring the Geometry of BERT|Source - Visualizing and Measuring the Geometry of BERT]]
- [[../sources/Source - Investigating BERT's Knowledge of Language|Source - Investigating BERT's Knowledge of Language]]
- [[../sources/Source - Probing What Different NLP Tasks Teach Machines about Function Word Comprehension|Source - Probing What Different NLP Tasks Teach Machines about Function Word Comprehension]]

## Open Questions
- What should count as enough convergent evidence to move from extractability to behavioral relevance?
- When does a probing result plus intervention evidence become a mechanistic explanation rather than only a stronger internal-evidence claim?
- Which future sources best connect representation probing to causal or circuit-level explanation without collapsing the distinction?
