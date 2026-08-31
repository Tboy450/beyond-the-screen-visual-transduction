# 18. Cortical Form Tracing

- Status: Research
- Interface point: Visual cortex
- Carrier: Electrical stimulation in research/clinical settings
- Transducer: Electrode-tissue interface
- Encoding style: Dynamic strokes instead of static dot fields
- Addressing method: Mapped stimulation sites in visual cortex
- Expected percept: Recognizable traced forms, letters, or line-like percepts
- Related modules: [Visual Pathway](../modules/07-visual-pathway.md), [Perceptual Rendering](../modules/09-perceptual-rendering.md)

## Summary

Cortical form tracing asks whether visual cortex stimulation works better when
it moves. Instead of trying to light up a whole artificial image at once, a
system traces a shape through time, closer to handwriting or a CRT sweep.

## Chain Map

```text
shape
-> stroke path
-> timed stimulation sequence
-> dynamic phosphene pattern
-> perceived form
```

## Why It Is Important

If separate phosphenes do not combine naturally into a clear image, temporal
motion might help the brain bind them. The concept shifts the goal from "neural
pixels" to "neural strokes."

## Expansion Ideas

- Phosphene handwriting: letters are drawn as sequences.
- Icon tracing: arrows, warning signs, doors, stairs, or object outlines.
- Motion grammar: different trace speeds or directions carry different
  meanings.
- Shape simplification: complex camera input becomes a few meaningful strokes.
- Training loop: users learn a stable set of trace patterns.

## Research Questions

- Which shapes are easiest to recognize from dynamic stimulation?
- Does tracing scale beyond letters?
- How does timing affect perceived continuity?
- Can tracing combine with semantic labels?

## Sources

- Beauchamp et al., "Dynamic Stimulation of Visual Cortex Produces Form
  Vision":
  https://pmc.ncbi.nlm.nih.gov/articles/PMC7331799/
- Bosking et al., "Electrical Stimulation of Visual Cortex: Relevance for
  Visual Cortical Prosthetics":
  https://pmc.ncbi.nlm.nih.gov/articles/PMC6916716/

