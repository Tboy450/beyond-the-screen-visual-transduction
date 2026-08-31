# 37. Scene Skeleton

- Status: Speculative/prototype
- Interface point: Assistive perception layer
- Carrier: Visual overlay, audio, tactile cue, or future prosthetic symbol
- Transducer: Depends on output channel
- Encoding style: Spatial graph
- Addressing method: Object and surface layout
- Expected percept: Navigable structure rather than a full image
- Related modules: [Perceptual Rendering](../modules/09-perceptual-rendering.md), [Creative Engineering](../modules/13-creative-engineering.md)

## Summary

The scene skeleton converts the world into a simplified structure. Instead of
asking what the scene looks like, it asks what the user can do inside it.

## Chain Map

```text
sensor input
-> surfaces and objects
-> paths and hazards
-> simplified scene graph
-> cue output
-> user action
```

## Scene Elements

| Element | Meaning |
| --- | --- |
| Free path | Where movement is likely possible. |
| Barrier | Wall, furniture, closed door, or obstacle. |
| Drop or step | Elevation change. |
| Moving agent | Person, pet, vehicle, cart, or bicycle. |
| Goal | Door, chair, counter, handle, sign, or object. |
| Hazard | Heat, sharp object, traffic, edge, or collision risk. |
| Uncertainty | Region where the system is unsure. |

## Expansion Ideas

- Map room geometry into a small set of directional cues.
- Encode near-field obstacles through a vibration belt.
- Use spatial audio for moving objects.
- Use a near-eye overlay for doorways and edges.
- Add a "question mode" where the user asks what is ahead.

## Research Questions

- What is the minimum scene graph needed for safe navigation?
- Should the system describe objects or paths first?
- Can a user build trust without overtrusting the system?
- How should uncertain regions be represented?

