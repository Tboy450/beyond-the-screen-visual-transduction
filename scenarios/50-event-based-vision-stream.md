# 50. Event-Based Vision Stream

- Status: Prototype
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

## What Counts As An Event?

- Edge appears
- Edge disappears
- Object moves
- Brightness changes
- Obstacle approaches
- Door opens
- Hand enters field
- Text region appears

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

