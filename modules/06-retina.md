# 06. Retina

The retina is a layered neural processor. It is not just film at the back of the
eye.

## Simplified Route

```text
photons
-> rods and cones
-> bipolar, horizontal, and amacrine cells
-> ganglion cells
-> optic nerve
```

## Layers And Functions

| Layer Or Cell Type | Function |
| --- | --- |
| Rods | High sensitivity, low-light vision. |
| Cones | Color and high-acuity vision. |
| Bipolar cells | Relay signals from photoreceptors. |
| Horizontal cells | Support contrast and lateral interactions. |
| Amacrine cells | Shape timing, motion, and local signaling. |
| Ganglion cells | Encode retinal output as spike trains. |

## Interface Points

| Interface Point | What It Tries To Do |
| --- | --- |
| Photoreceptor replacement | Restore or mimic damaged light-sensitive cells. |
| Subretinal implant | Stimulate near the photoreceptor/bipolar layer. |
| Epiretinal implant | Stimulate near ganglion cells on the retinal surface. |
| Optogenetic retina | Make remaining cells light responsive. |
| Retinal projection | Use existing photoreceptors with a synthetic image source. |

## Why Retina Is Hard

- The retina compresses and transforms information before the brain.
- Many ganglion cell types encode different features.
- Disease changes what tissue remains usable.
- Eye movements alter the relationship between device and world.
- A stimulated spot may produce an elongated, distorted, or moving phosphene.
- The perceptual result is personal and must be calibrated.

## Creative Workaround: Retina-Matched Encoding

Instead of driving every electrode as if it were a pixel, a retinal system could
preprocess camera data into retina-like signals:

- Contrast changes
- Motion onset
- Edges
- Center-surround patterns
- Coarse object boundaries
- Brightness adaptation

The goal is not to mimic the whole retina perfectly. The goal is to give the
remaining circuitry signals it can use more naturally.

## Related Entries

- [05. Eye Optics](05-eye-optics.md)
- [07. Visual Pathway](07-visual-pathway.md)
- [08. Neural Interfaces](08-neural-interfaces.md)

