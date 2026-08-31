# 41. Tactile-Visual Substitution

- Status: Research
- Interface point: Touch
- Carrier: Pressure, vibration, or electrotactile pattern
- Transducer: Tactile actuator array
- Encoding style: Spatial, symbolic, or event-based tactile cues
- Addressing method: Body map, tongue map, fingertip map, belt, or patch
- Expected percept: Learned spatial awareness through touch
- Related modules: [Signal Encoding](../modules/02-signal-encoding.md), [Perceptual Rendering](../modules/09-perceptual-rendering.md)

## Summary

Tactile-visual substitution sends visual information through the sense of touch.
The user learns to interpret patterns as spatial structure, object outlines, or
navigation cues.

## Chain Map

```text
camera
-> visual feature extraction
-> tactile pattern
-> touch
-> learned spatial interpretation
```

## Encoding Possibilities

| Visual Feature | Tactile Mapping |
| --- | --- |
| Object position | Actuator position. |
| Distance | Pulse frequency or pressure strength. |
| Motion | Moving vibration pattern. |
| Edge | Line of activated points. |
| Hazard | Distinct warning pulse. |
| Direction | Belt or patch location. |

## Expansion Ideas

- Use touch for immediate hazards and audio for object identity.
- Use a body-centered map for navigation.
- Use fingertip or tongue interfaces for fine shape exploration.
- Use a wearable belt as synthetic peripheral awareness.
- Build training games for cue fluency.

## Research Questions

- Which body surface gives the best mix of resolution and comfort?
- How quickly can users learn spatial interpretation?
- Which features should be tactile rather than auditory?
- How can the system avoid overload during complex scenes?

## Sources

- Bach-y-Rita et al., "Vision Substitution by Tactile Image Projection":
  https://pubmed.ncbi.nlm.nih.gov/5818337/
- Nau et al., "Acquisition of Visual Perception in Blind Adults Using the
  BrainPort Artificial Vision Device":
  https://pmc.ncbi.nlm.nih.gov/articles/PMC4281706/

