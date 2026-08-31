# 05. Eye Optics

The eye is already a precise optical system. Many "screenless" ideas do not
remove the screen by entering the brain; they move the image source into the
optical path.

## Natural Optical Pipeline

```text
external light
-> cornea
-> aqueous humor
-> pupil
-> lens
-> vitreous body
-> retina
```

## Optical Variables

| Variable | Why It Matters |
| --- | --- |
| Focus | A retinal display must stay sharp as the eye changes accommodation. |
| Eye motion | The eye constantly moves; projection must track it or use it. |
| Pupil size | Light level and aperture change with environment. |
| Field of view | A useful display needs enough coverage for the task. |
| Brightness | Too dim is useless; too bright is hazardous or uncomfortable. |
| Distortion | Real eyes are not identical lenses. |
| Latency | Slow projection can feel unstable or nauseating. |

## Screenless Optical Scenarios

| Scenario | Concept |
| --- | --- |
| Retinal projection | Project an image directly onto the retina. |
| Retinal scanning | Scan a beam across the retina like a tiny CRT. |
| Waveguide display | Route light through glasses toward the eye. |
| Contact-lens display | Put a tiny display system on the eye. |
| Adaptive optics display | Correct individual optical distortions. |
| Foveated projection | Put detail where gaze is pointed. |

## Creative Workaround: Use The Eye's Motion

A normal display fights eye movement by refreshing a stable external surface.
A screenless system could instead exploit movement:

- Let microsaccades help sample sparse information.
- Use gaze to request higher detail.
- Display coarse peripheral motion cues and high-detail central cues.
- Refresh symbols only when fixation stabilizes.

This turns the eye from a problem into part of the addressing system.

## Related Entries

- [02. Signal Encoding](02-signal-encoding.md)
- [06. Retina](06-retina.md)
- [09. Perceptual Rendering](09-perceptual-rendering.md)

