# 15. Evaluation And Model Methods

Formal methods help the encyclopedia compare ideas without pretending that a
single number captures perception. They are useful for safe toy models,
ordinary-interface studies, source-grounding audits, AI-assisted analysis, and
future research planning.

The method must follow the claim. A mechanism claim, a perceptual claim, a task
claim, a learning claim, and a safety claim need different outcomes.

## Evaluation Card

Before modeling or comparing an idea, write a short evaluation card:

```yaml
evaluation_id: scene-skeleton-navigation-001
question: Can a sparse scene representation support safer route decisions than a noisy image cue?
claim_type: task_performance
methods:
  - manual
  - analog
unit_of_analysis: participant-trial
population: specify users and relevant visual or sensory experience
input_or_intervention: scene skeleton cue
baseline: blurred image, ordinary description, or current aid
primary_outcome: correctly completed route decisions
secondary_outcomes: response time, workload, confidence calibration, retention
controls: matched scenes, counterbalanced order, cue exposure time
confounds: prior familiarity, training order, device latency, experimenter cueing
failure_condition: no improvement, missed hazards, or unjustified confidence
safe_boundary: ordinary-screen, audio, or tactile study before any clinical use
```

This card makes the test independent of the vocabulary used to describe the
idea. “It felt more meaningful” may be worth recording, but it is not the same
as a predefined performance measure.

## Method Families

| Method | Best use | Main caution |
| --- | --- | --- |
| Source-grounding audit | Check whether a sentence is supported by its cited source. | A citation can be relevant without proving the whole sentence. |
| Manual source ledger | Track claims, sources, definitions, and contradictions on paper or in a simple table. | Handwritten or copied errors still need a second review. |
| Analog model or physical mockup | Explore spatial layout, timing, scale, routing, noise, or user interaction with cards, grids, light, sound, objects, or other ordinary materials. | Similar behavior in a mockup does not establish the same mechanism in tissue or a device. |
| Hand-calculated model | Check units, bounds, ratios, sensitivity, and small examples without software. | A clean calculation can still be based on a poor assumption. |
| Toy model | Explore encoding, timing, noise, crosstalk, or bandwidth. | A successful simulation is not evidence of biological success. |
| Ordinary-interface study | Compare visual, audio, tactile, or semantic cue designs safely. | Learned performance may depend on training and transfer. |
| Computational model | Test explicit assumptions about representation or decoding. | Model output inherits the assumptions and data of the model. |
| Controlled human comparison | Measure a defined task, percept, or decision outcome. | Avoid small-sample overclaiming, order effects, and unblinded cueing. |
| Longitudinal learning study | Measure calibration, retention, fluency, and transfer. | Familiarity can be mistaken for general usefulness. |

## Manual And Analog Work

These are complete methods in their own right. They are often the best first
step because they expose an assumption before time is spent building software
or hardware.

Useful examples include:

- Draw a route by hand and mark each conversion, loss, delay, and unknown.
- Use index cards or physical tokens to represent objects, hazards, cues,
  memory, attention, and user choices.
- Build a nonclinical mockup with paper, strings, lenses, lights, speakers,
  or tactile objects to examine geometry, timing, and workload.
- Calculate a small case by hand, then vary one parameter at a time and record
  the result in a table.
- Use dimensional analysis to catch impossible combinations of distance,
  time, frequency, energy, bandwidth, or probability.
- Compare the manual result with a computational result and investigate any
  disagreement instead of choosing the more elaborate answer automatically.

An analog or manual model is not merely an illustration. It can test a defined
relationship. Its limits must still be written down: what is represented,
what is omitted, what is continuous or discrete, and which real-world effect it
cannot reproduce.

An analogy is different. It may generate a question, but resemblance alone is
not a measurement or a mechanism.

## Measures And Formulae

Simple measures are useful when their denominator, unit, and scope are stated.
For example:

```text
success rate = successful trials / valid trials

change from baseline = score with cue - score with baseline

relative change = (score with cue - score with baseline) / score with baseline

false-assurance rate = confident incorrect decisions / all confident decisions

compression ratio = source representation size / delivered representation size

cue efficiency = successful task decisions / delivered cue events
```

These are definitions for particular studies, not universal laws. Use a ratio
only when its denominator is valid and meaningful. A higher compression ratio
does not imply a better percept, and a lower cue count does not imply a safer
or more useful interface. Always report the units, missing trials, exclusions,
uncertainty, and the comparison condition.

For learning, report performance at more than one time point. A cue that works
once but fails after delay or transfer has a different value from a cue that
remains useful across tasks and contexts.

## Records For Model Development

When records are used to develop or assess an AI or statistical model, keep
these layers distinct:

```text
source page or paper
-> extracted claim
-> human-reviewed label or relation
-> model input
-> model output
-> independent evaluation
```

Do not use a generated summary as if it were an independent source. Keep near-
duplicate passages, versions of the same paper, and records from the same
experiment in the same partition. For meaningful generalization tests, hold
out entire scenario families, sources, or time periods rather than only random
sentences.

Labels should describe the record, not reward confident writing. Useful labels
include claim kind, evidence status, source type, population, target, carrier,
representation, and whether the statement is direct, inferred, analogical, or
proposed.

## AI-Assisted Use

AI systems are optional. They can help with retrieval, deduplication,
terminology alignment, comparison tables, contradiction finding, candidate
questions, and drafts of toy-model code. Each output requires a return path to
the source and a human review appropriate to the risk.

An AI system must not be treated as evidence because it produces a coherent
explanation. It should not silently upgrade a frontier idea to research status,
fill an unresolved field, or cite its own earlier output as confirmation.

## Independent Checks

Every model or comparison should include at least one check that can disagree
with the proposed explanation:

- a baseline or negative control
- a held-out source, scenario family, or task
- an alternative representation
- a blinded or counterbalanced condition where practical
- a predeclared failure condition
- a reviewer who can trace the claim back to its source

If the only successful test is a restatement of the project's own categories,
the test has measured organization, not the phenomenon under discussion.
