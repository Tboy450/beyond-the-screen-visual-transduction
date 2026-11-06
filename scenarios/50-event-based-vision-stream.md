# 50. Event-Based Vision Stream

[Scenario index](README.md) · [Book contents](../CONTENTS.md) · [Evidence guide](../sources/evidence-guide.md)

- Status: Proposed assistive interface; established sensor principle
- Interface point: Assistive display, sensory substitution, or prosthetic front end
- Carrier: Any output channel
- Transducer: Display, audio, haptic, retinal, or neural interface
- Encoding style: Events instead of frames
- Addressing method: Change location and timing
- Expected percept: Motion-first awareness and change detection
- Related modules: [Signal Encoding](../modules/02-signal-encoding.md), [Creative Engineering](../modules/13-creative-engineering.md)

## Summary

Event-based vision streams send changes rather than complete images. This is
useful for low-bandwidth interfaces because much of a video frame is redundant.

## Chain Map

```text
visual change
-> event sensor or change detector
-> event stream
-> compressed cue
-> learned perception
```

## Sensor Events and Interpreted Events

In a dynamic vision sensor, an event reports a local brightness change at a
pixel. It does not directly mean “door opens” or “obstacle approaches.” Those
descriptions require further processing. Event rate also varies with the
scene, motion, noise, and sensor settings; it is not a guaranteed reduction
in data under every condition.
[Delbruck, Graca, and Paluch (2021)](https://arxiv.org/abs/2105.00409) examine
event-rate and noise control at the sensor level.

| Level | Example | What must be added |
| --- | --- | --- |
| Sensor event | Brightness increased at a pixel. | Timing and spatial information from the sensor. |
| Derived feature | A moving edge or motion estimate. | Processing of multiple events and explicit assumptions. |
| Semantic event | A door is opening. | Recognition, context, and an uncertainty estimate. |
| User cue | An opening is on the left. | A selected message and a learnable output channel. |

The assistive route proposed here still needs evaluation with a defined task
and intended users. Sensor performance alone does not establish usefulness
as a perceptual interface.

## Expansion Ideas

- Motion-only prosthetic mode.
- Event-to-audio sweep.
- Event-to-tactile peripheral cue.
- Event-driven phosphene flash.
- Scene memory that keeps static objects present after the event.

## Research Questions

- Can event streams reduce cognitive overload?
- How should static but important objects remain represented?
- Which tasks benefit most: mobility, sports, reading, tool use, or social
  interaction?
- Can event streams be combined with semantic object memory?

## Sources

- Tayarani-Najaran and Schmuker, "Event-Based Sensing and Signal Processing in
  the Visual, Auditory, and Olfactory Domain":
  https://pmc.ncbi.nlm.nih.gov/articles/PMC8203204/
