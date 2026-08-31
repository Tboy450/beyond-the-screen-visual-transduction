# Project Tracks: Perception As The Medium

This page sharpens the practical direction of the encyclopedia. The central
move is to test which middle media between information and useful experience
should be removed, compressed, rerouted, or retained.

The historical pattern behind this move is developed in
[Historical Context: From Radio To Screenless Perception](HISTORICAL_CONTEXT.md).
Radio cut the wire, television cut the still image into scan lines, radar cut
visible light out of long-range detection, and sensory substitution cuts the
eye out of some visual-information tasks.

The goal is not to force a full image through every layer. The goal is to ask
which parts of the display chain can be removed, compressed, or shifted into
the user's trained perceptual loop.

```text
world or signal
-> feature, event, or meaning extraction
-> minimal cue
-> active exploration and learning
-> useful perception
```

In this framing, the human mind is not just the final receiver. Perception is
part of the medium. A device may provide only a cue, but the trained person
completes the representation through attention, movement, memory, expectation,
and learned interpretation.

## Design Rule

For every proposed system, ask:

```text
What middle layer does this remove?
What does the user learn to complete?
What stays visible when the system is uncertain?
```

If a proposed carrier, screen, image format, or prosthetic code does not improve
safety, learnability, agency, bandwidth, or reliability, it may be an extra
middle layer rather than a useful bridge.

Standards should be used as reference loops, not cages. First understand the
established chain, then ask which part exists because older tools needed it and
which part actually serves the user.

## Middle Layers To Remove Or Compress

| Middle Layer | Replace Or Compress It With | Why It Matters |
| --- | --- | --- |
| Full pixel grid | Edges, motion, depth, labels, or symbols | Lowers bandwidth and may reduce confusion. |
| External screen | Retinal projection, wearable cueing, audio, touch, or symbolic output | Removes the fixed glass surface from the chain. |
| Photorealism | Task-first cues | A useful warning can matter more than a blurry image. |
| Passive viewing | Active scanning and user control | Perception improves when action helps structure the cue. |
| Universal map | Personal percept map | Biological and learned mappings differ by person. |
| One weak channel | Cross-modal cue grammar | Audio, touch, and residual vision can share the load. |
| Continuous video | Event stream plus object memory | Changes often carry more practical value than repeated frames. |
| Opaque AI decision | Confidence-visible cue | The user needs to know when a cue is uncertain. |
| Direct memory fantasy | Voluntary cueing, rehearsal, and recall scaffolds | Keeps memory work ethical and grounded. |

## Project Track 1: Perceptual Codec Bench

- Question: What is the smallest cue set that still supports a task?
- Build as: A safe software or paper prototype using ordinary images, videos,
  diagrams, or captions.
- Test by comparing: low-resolution images, edge maps, motion cues, depth cues,
  semantic labels, and scene graphs.
- Success looks like: users answer practical questions faster or more reliably
  with fewer cues than with noisy full images.

This track treats perception like a codec. The encoder discards anything that
does not help the user act, decide, orient, or ask for more detail.

## Project Track 2: Scene Skeleton Navigator

- Question: Can layout replace imagery for mobility and orientation?
- Build as: A photo or video annotator that converts scenes into paths,
  barriers, openings, objects, moving agents, hazards, and uncertainty zones.
- Output through: simple diagrams, spatial audio, tactile patterns, or overlay
  icons.
- Success looks like: the user can answer "where can I go?" and "what matters
  first?" without needing a full picture.

This track removes surface texture, color, and decorative detail. It keeps the
action structure of the scene.

## Project Track 3: Phosphene Font Trainer

- Question: Can artificial visual symbols become more useful than crude pixels?
- Build as: A normal-screen simulator of sparse dots, flashes, sweeps, and
  simple glyphs. Do not treat it as stimulation guidance.
- Train on: arrows, warnings, letters, object categories, confidence marks, and
  motion cues.
- Success looks like: recognition improves with practice and remains stable
  under noise, delay, or partial occlusion.

This track accepts that artificial percepts may not look natural. It turns that
limitation into a language-design problem.

## Project Track 4: Personal Percept Map

- Question: Is the user-specific perceptual map the real display surface?
- Build as: A diary or calibration table where a person records what each safe
  cue or simulated cue feels like, where it seems located, and how stable it is.
- Track: location, intensity, shape, confidence, fatigue, confusion, and task
  usefulness.
- Success looks like: the interface adapts to the person instead of assuming a
  clean universal grid.

This track shifts the medium from a hardware surface to a learned relationship
between cue, action, and perception.

## Project Track 5: Event-First Interface

- Question: Can changes carry more usable information than frames?
- Build as: An event-stream demo that reports only motion, edge changes,
  appearing objects, disappearing objects, and approaching hazards.
- Add: an object memory layer so important static objects do not vanish after
  their first event.
- Success looks like: lower cognitive load with better awareness of change,
  motion, and risk.

This track cuts out repeated frame data. It treats time and change as the main
signal.

## Project Track 6: Artificial Fovea

- Question: Can attention decide where detail belongs?
- Build as: A foveated mockup where the center of gaze or current task gets
  detail while the periphery gets only motion, depth, or hazard cues.
- Test modes: walking, reading, cooking, workshop, social, and search.
- Success looks like: useful detail appears where the user needs it without
  overwhelming the whole field.

This track replaces uniform image delivery with attention-shaped delivery.

## Project Track 7: Cross-Modal Cue Grammar

- Question: What information should go through sight, sound, touch, or symbols?
- Build as: A cue grammar that assigns feature types to output channels.
- Example mapping: collision risk to touch, object identity to speech, moving
  direction to spatial audio, readable text to voice, and confidence to tone or
  pulse style.
- Success looks like: the user learns one coherent interface rather than a pile
  of separate alerts.

This track cuts out the assumption that all visual information must stay visual.

## Project Track 8: Memory-Safe Cue Companion

- Question: How far can memory-adjacent ideas go without pretending to write
  memories?
- Build as: voluntary cue cards, image prompts, narration, spaced review,
  location tags, and recall notes.
- Track: vividness, accuracy, confidence, emotional weight, and later recall.
- Success looks like: better self-directed recall without false claims of
  direct memory insertion.

This track keeps the memory branch grounded in cueing, imagery, association,
and consent.

## Evaluation Questions

- Does this project remove or compress a middle layer?
- Does it give the user agency over what is emphasized?
- Can it be prototyped with ordinary, reversible tools?
- Does it make uncertainty visible?
- Does it support active exploration rather than passive reception?
- Does it build a stable cue language over time?
- Does it measure usefulness by action and understanding, not image fidelity
  alone?

## Source Anchors

These tracks are especially connected to research on sensory substitution,
sensorimotor accounts of perception, predictive coding, extended cognition,
retinal and cortical prostheses, and event-based sensing. See the expanded
[bibliography](sources/bibliography.md) and
[annotated research notes](sources/annotated-research-notes.md).
