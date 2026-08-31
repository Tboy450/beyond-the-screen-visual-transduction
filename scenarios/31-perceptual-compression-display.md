# 31. Perceptual Compression Display

- Status: Speculative
- Interface point: Perception or assistive interface
- Carrier: Any usable sensory or neural channel
- Transducer: Display, audio, haptic, retinal, or neural interface
- Encoding style: Compressed perceptual features
- Addressing method: Task-aware cue placement
- Expected percept: Useful awareness rather than full image reconstruction
- Related modules: [Signal Encoding](../modules/02-signal-encoding.md), [Perceptual Rendering](../modules/09-perceptual-rendering.md)

## Summary

A perceptual compression display asks: what can be removed from a visual scene
while still preserving usefulness?

It treats artificial vision as a codec problem. The system may not transmit
color, texture, or every object. It may transmit only the features needed for a
task.

The stronger version treats the user's perception as part of the medium. The
device does not need to carry the whole image if the person can learn a stable
cue grammar and use movement, attention, and context to complete the scene.

## Chain Map

```text
scene
-> feature extraction
-> compression by task
-> cue vocabulary
-> learned perception
```

## Compression Targets

| Target | Useful For |
| --- | --- |
| Edges | Object boundaries and reading support. |
| Motion | Moving people, vehicles, and hazards. |
| Depth | Navigation and reaching. |
| Object labels | Recognition and task support. |
| Salience | Attention guidance. |
| Confidence | Knowing when the system might be wrong. |

## Expansion Ideas

- Encode a room as five cues or fewer.
- Switch cue vocabulary based on user task.
- Use high detail only around gaze.
- Pair weak visual cues with spoken semantic labels.
- Let the user tune what matters.
- Compare passive cue viewing with active exploration.
- Keep uncertainty visible as part of the cue, not as a hidden machine state.

## Research Questions

- Which compressed cues are most useful for each task?
- When does less information outperform more confusing information?
- How should uncertainty be represented?
- Can users become fluent in a compressed visual language?
- Which middle layer is being removed: pixel grid, frame stream, screen, or
  photorealism?

