# 02. Signal Encoding

Signal encoding is the form visual information takes before it reaches a
physical display or biological interface.

## Common Encodings

| Encoding | Description | Example |
| --- | --- | --- |
| Analog waveform | Continuous voltage changes over time. | Broadcast TV brightness signal. |
| Raster scan | A time sequence mapped to screen position. | CRT scanning lines. |
| Pixel framebuffer | Digital array of color and brightness values. | LCD, OLED, phone screens. |
| Pulse train | Information carried by pulse timing and amplitude. | Neural stimulation patterns. |
| Event stream | Only changes are transmitted. | Event cameras and motion-first sensing. |
| Feature code | Edges, orientation, motion, color, depth, or texture. | Vision models and biological receptive fields. |
| Semantic code | Objects, labels, hazards, spatial commands. | Assistive navigation systems. |
| Memory cue | Prompt that triggers recall rather than a direct image. | Photos, labels, narration, location cues. |

## Why Pixel Encoding May Be The Wrong Goal

Natural displays use pixels because screens are surfaces. The visual system does
not receive pixels internally. It receives transformed signals: contrast,
timing, receptive-field activity, motion, color opponency, attention, and
prediction.

A screenless interface may become more practical by sending less:

```text
full image -> edges + movement + depth + hazards
```

or:

```text
full image -> person, doorway, stairs, text, vehicle, motion direction
```

This is not as cinematic as a normal picture, but it may be more useful.

## Encoding Design Patterns

| Pattern | Purpose |
| --- | --- |
| Foveated encoding | Spend most bandwidth on the attended region. |
| Peripheral alerting | Use coarse cues for motion and hazards outside focus. |
| Edge-first encoding | Prioritize contours and object boundaries. |
| Depth-first encoding | Prioritize distance and collision risk. |
| Symbol encoding | Use learned glyphs instead of photorealism. |
| Task-aware encoding | Change what is sent based on reading, walking, faces, or tools. |
| Confidence encoding | Signal uncertainty so the user can distrust weak recognitions. |
| Adaptive encoding | Recalibrate to the user's reported percepts over time. |

## Creative Workaround: The Perceptual Codec

A perceptual codec is a hypothetical compression system designed around the
user's actual perceptual interface. It would not optimize for image quality on a
monitor. It would optimize for:

- Distinguishable percepts
- Learnability
- Low fatigue
- Fast recognition
- Low false alarms
- Stable mapping over weeks or months

The output might look like a small vocabulary of visual-like sensations, sounds,
or tactile cues rather than a normal video image.

## Questions For Scenario Pages

- Does the scenario need full frames or only changes?
- Does it need spatial detail or object meaning?
- Does the code match retina, optic nerve, V1, or learned cross-modal cues?
- Can the user train on it?
- Can the system represent uncertainty?
- What happens when the model or sensor is wrong?

## Related Entries

- [06. Retina](06-retina.md)
- [08. Neural Interfaces](08-neural-interfaces.md)
- [09. Perceptual Rendering](09-perceptual-rendering.md)
- [10. Memory Branch](10-memory-branch.md)

