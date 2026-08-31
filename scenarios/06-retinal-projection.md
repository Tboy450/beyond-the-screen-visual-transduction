# 06. Retinal Projection

- Status: Research
- Interface point: Eye and retina
- Carrier: Visible light
- Transducer: Natural photoreceptors
- Encoding style: Pixel, scan, or feature-enhanced optical image
- Addressing method: Optics, gaze tracking, scanning, or waveguides
- Expected percept: Ordinary visual input if optics and retina remain functional
- Main limitations: Eye motion, focus, brightness, field of view, safety, latency

## Summary

Retinal projection removes the wall or handheld screen but keeps the eye as the
receiver. Instead of making light on a nearby surface, a device sends controlled
light into the eye so the image forms on the retina.

## Chain Map

```text
image data
-> light source
-> optics or scanner
-> retina
-> visual pathway
-> perception
```

## Engineering Workarounds

- Use foveated rendering so high detail follows gaze.
- Use low-brightness overlays rather than full-scene replacement.
- Stabilize the image against eye motion.
- Prefer symbolic or edge overlays when full imagery is not needed.

## Open Questions

- How wide can the field of view be while staying comfortable?
- How stable can the image remain during eye movement?
- Can brightness adapt safely across environments?
- Is the best use full vision, augmented vision, or task-specific cueing?

