# Hypothesis Registry

This registry turns broad ideas into researchable or modelable hypotheses. It
does not ask whether an idea is "allowed" to exist. It asks how to sharpen it.

## Maturity Scale

| Level | Name | Meaning |
| --- | --- | --- |
| H0 | Metaphor | Useful analogy, not yet a mechanism. |
| H1 | Mechanism Sketch | Names a target, carrier, and transducer. |
| H2 | Toy Model | Can be represented in diagrams, simulations, or human-interface demos. |
| H3 | Prototype Analogue | Can be explored with ordinary screens, audio, haptics, or nonclinical devices. |
| H4 | Research Parallel | Resembles active scientific or clinical research. |
| H5 | Translation Candidate | Could become a practical system if major engineering and evidence gaps close. |

## Core Hypotheses

| ID | Hypothesis | Level | How To Make It Sharper |
| --- | --- | --- | --- |
| H-001 | A scanned stimulus can produce useful perception without a conventional screen. | H4 | Compare CRT raster scanning, retinal scanning displays, and cortical shape tracing. |
| H-002 | Artificial vision may work better as a learned language than as bad natural vision. | H3 | Build symbol sets, train users, and compare recognition speed. |
| H-003 | Sparse semantic cues can outperform low-resolution images for navigation tasks. | H3 | Test scene skeletons against blurred video and audio descriptions. |
| H-004 | A personal percept map is the real display surface in neural prosthetics. | H4 | Track perceived location, shape, and stability over time. |
| H-005 | Event-based sensing is a natural fit for low-bandwidth visual substitution. | H3 | Compare frame-based versus motion-change cue streams. |
| H-006 | Foveated artificial vision can reduce bandwidth without losing task usefulness. | H3 | Use gaze or attention models to allocate detail. |
| H-007 | A phosphene font can make prosthetic percepts more useful than pixel imitation. | H2 | Define a symbol vocabulary and train recognition. |
| H-008 | A retinal interpreter should mimic useful retinal transformations, not raw pixels. | H2 | Encode contrast, edges, motion onset, and adaptation. |
| H-009 | Cortical stimulation may benefit from temporal tracing rather than static patterns. | H4 | Compare static symbols with traced shapes in literature and simulations. |
| H-010 | Cross-modal redundancy can make weak visual channels more reliable. | H3 | Pair visual-like cues with audio or tactile confirmation. |
| H-011 | Remote carriers become more plausible when they communicate with local transducers. | H1 | Specify the local receiver, conversion mechanism, and addressing model. |
| H-012 | Memory-adjacent systems should begin as voluntary cueing systems. | H3 | Compare images, narration, location, and repetition as recall supports. |
| H-013 | A "neural shadow mask" can be modeled as crosstalk control. | H2 | Simulate spread, overlap, and separation in a percept grid. |
| H-014 | Biological-phosphor concepts become sharper when classified by input/output conversion. | H1 | Compare phosphors, optogenetic proteins, fluorescence, and implantable converters. |
| H-015 | A semantic subtitle track may be the most practical near-term screenless layer. | H3 | Rank cue types by usefulness, interruption cost, and error risk. |

## Hypothesis Expansion Template

```markdown
## H-000: Hypothesis Name

- Maturity:
- Related scenarios:
- Closest known science:
- Target:
- Carrier:
- Transducer:
- Encoding:
- Toy model:
- What would count as progress:
- What would falsify or weaken it:
- Open questions:
```

## Toy Model Ideas

Toy models are useful because they let the project explore bold ideas without
waiting for future hardware.

| Toy Model | What It Tests |
| --- | --- |
| Low-resolution phosphene simulator | Whether sparse light dots can support recognition. |
| Shape-tracing simulator | Whether temporal drawing beats static dot patterns. |
| Scene skeleton annotator | Whether sparse spatial graphs answer practical navigation questions. |
| Phosphene font trainer | Whether a small artificial alphabet becomes fluent. |
| Event-stream visualizer | Whether changes and motion carry enough information. |
| Cross-modal cue trainer | Whether audio and tactile cues improve weak visual symbols. |
| Memory lantern card | Which voluntary cues support later recall. |
| Retinotopic bus diagram | How location, feature, timing, and confidence might be separated. |
| Neural shadow-mask simulator | How crosstalk control changes symbol clarity. |

## High-Value Research Questions

- What is the smallest artificial visual vocabulary that becomes useful?
- Do users learn sparse symbolic cues faster than noisy low-resolution images?
- Can event-based signals reduce perceptual overload?
- What cue types are easiest to combine across sight, sound, and touch?
- What does a stable personal percept map look like over weeks or months?
- Can shape tracing turn phosphene dots into recognizable forms more reliably?
- Can semantic cues compensate for prosthetic resolution limits?
- What is the best way to encode uncertainty in an assistive perception system?
- Which parts of the visual pathway behave most like an addressable map, and
  which behave more like feature processors?
- How can memory-related ideas be explored through cueing, imagery, and recall
  without pretending memory is a video file?

