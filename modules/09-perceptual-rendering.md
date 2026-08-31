# 09. Perceptual Rendering

Perceptual rendering asks whether a system must reproduce an image, or whether
it can create useful perception by encoding a smaller set of features.

## Pixel Display Versus Perceptual Display

| Pixel Display | Perceptual Display |
| --- | --- |
| Sends color and brightness for each pixel. | Sends cues the user can interpret. |
| Optimized for screens. | Optimized for a person, task, and sensory channel. |
| High bandwidth. | Potentially lower bandwidth. |
| Familiar visual output. | May require training. |
| Requires dense spatial addressing. | Can use symbols, sound, touch, or sparse phosphenes. |

## Candidate Cues

- Edges
- Corners
- Motion direction
- Optical flow
- Depth
- Surface boundaries
- Text location
- Face location
- Door and stair location
- Hazard direction
- Object category
- Confidence or uncertainty

## Creative Architecture: Scene Skeleton

The scene skeleton idea compresses the environment into a sparse graph:

```text
room outline
-> open paths
-> obstacles
-> moving agents
-> labeled objects
-> warnings
```

This is not photorealistic, but it may be usable. For mobility or tool use, the
right sparse cue at the right time can matter more than a blurry full image.

## Creative Architecture: Semantic Visual Interface

A semantic visual interface does not ask "what should each pixel look like?"
It asks "what does the user need to know?"

Examples:

- "Door, left, two meters."
- "Step down ahead."
- "Person approaching from right."
- "Text line centered."
- "Cup on table, reachable."

Those messages could be visual icons, speech, spatial audio, tactile pulses, or
simple neural percepts if such interfaces mature.

## Risk

Every compression can hide information. A system that decides what matters can
be wrong. A responsible encyclopedia entry should always ask how errors are
represented to the user.

## Related Entries

- [02. Signal Encoding](02-signal-encoding.md)
- [07. Visual Pathway](07-visual-pathway.md)
- [10. Memory Branch](10-memory-branch.md)

