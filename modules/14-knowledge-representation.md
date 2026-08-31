# 14. Knowledge Representation And Provenance

The encyclopedia has two audiences: people who need readable explanations and
systems that need consistent records for retrieval, comparison, model
development, and analysis. Those needs can coexist without turning every page
into a database form.

The human-readable page remains primary. A structured record is a companion
index that makes the page easier to compare and inspect. It must never make a
claim seem more certain merely because the claim has been placed in a neat
format.

The record can live in prose, a notebook, index cards, a table, or a
machine-readable file. The medium used to keep the record is separate from the
quality of its definitions and sources.

## Record Units

Keep different kinds of statements separate:

| Record kind | Meaning |
| --- | --- |
| Observation | Something a source directly reports or measures. |
| Interpretation | A reasoned reading of an observation. |
| Proposal | A suggested architecture or mechanism that is not yet established. |
| Question | A problem the project is intentionally leaving open. |
| Constraint | A safety, ethical, physical, biological, or practical limit. |

One record should have one primary claim. A page may contain several records,
but a source observation should not quietly become an engineering proposal in
the same field.

## Core Record

The following is a compact record format, not a mandatory vocabulary for every
idea. Omit fields that do not apply and mark important absences explicitly.

```yaml
record_id: scenario-27
title: Focused-ultrasound vision interface
record_kind: research_summary
primary_claim: Acoustic stimulation has produced reported visual sensations or neural effects in limited studies.

scope:
  system: human visual cortex or nearby tissue
  population: specify participants, animal model, or device-only study
  setting: specify laboratory, clinical, simulation, or conceptual setting
  date_or_version: specify the source or record version

mechanism:
  input: electrical drive
  carrier: focused acoustic pressure
  source_transducer: piezoelectric ultrasound device
  biological_coupling_or_effect: ultrasound-mediated neural modulation
  representation: modulation or cue, not assumed to be an image
  addressing: acoustic focus; perceptual selectivity unresolved

evidence:
  status: research
  relationship_to_claim: direct
  sources:
    - source_id: lee-2016
      supports: reported study result
      limitation: perceptual resolution and generality remain unresolved

evaluation:
  useful_outcome: independently defined perceptual or task measure
  comparison: baseline or sham condition where appropriate
  failure_condition: no reliable effect, poor selectivity, adverse effect, or unusable cue
  safety_boundary: no unsupervised stimulation procedure

open_questions:
  - What can be addressed reliably?
  - Which reported effect is perceptual and which is only physiological?
```

The example is intentionally incomplete in places. `specify`, `unknown`,
`unresolved`, and `not_applicable` are valid values. A missing value should not
be silently filled with an assumption.

## Provenance

Every factual record should retain enough information for another reader to
find and reinterpret its source:

- author, organization, or laboratory
- title, date, DOI, or stable URL
- source type: primary study, review, textbook, technical documentation,
  commentary, or project note
- population, device, task, and relevant setting
- the exact claim the source supports
- important limitations and competing interpretations
- date the record was last reviewed

Generated summaries, extracted labels, and model suggestions are not primary
sources. They can assist organization, but their provenance must point back to
the underlying page or publication.

## Relationships Without Forced Classification

Records may point to one another using ordinary relationships such as:

```yaml
relations:
  depends_on: [module-04-transducers]
  contrasts_with: [scenario-31]
  extends: [hypothesis-011]
  raises_question: [question-visual-selectivity]
```

These links describe how ideas interact; they do not require every idea to
belong to one final category. A record can remain partly specified while its
useful relationships are documented.

## Versioning And Review

Do not overwrite an earlier interpretation when new evidence changes the
picture. Preserve the original claim, record the revision, and state whether
the change is:

- a correction to a factual description
- a narrower scope
- a change in evidence status
- a new interpretation
- a new proposal derived from older material

The purpose of structure is traceability. If the record cannot show where a
statement came from, what kind of statement it is, and what would weaken it,
the structure is not yet doing useful work.
