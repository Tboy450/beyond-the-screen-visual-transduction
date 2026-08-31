# 32. Predictive-Coding Display

- Status: Speculative
- Interface point: Perception and cognition
- Carrier: Any usable sensory, prosthetic, or symbolic channel
- Transducer: Display, speaker, haptic array, or future neural interface
- Encoding style: Cues that guide expectation and error correction
- Addressing method: Attention, salience, and mismatch
- Expected percept: A user-guided reconstruction rather than a rendered image
- Related modules: [Perceptual Rendering](../modules/09-perceptual-rendering.md), [Memory Branch](../modules/10-memory-branch.md)

## Summary

A predictive-coding display uses the brain's tendency to predict and fill in
missing information. Instead of sending everything, it sends strategically
chosen cues that help the user infer the rest.

## Chain Map

```text
scene
-> predicted structure
-> mismatch or important feature
-> cue
-> user reconstruction
```

## Example

For navigation, the system may not need to display every chair leg and table
edge. It might cue:

```text
open path center
chair left
person moving right
step down ahead
```

The user's own perception and memory fill in a usable model of the space.

## Expansion Ideas

- Prediction-first scene compression.
- Cue only what changed since the last moment.
- Encode surprise: new object, motion, obstacle, or mismatch.
- Let the user ask for detail when prediction is uncertain.
- Combine with memory of familiar rooms.

## Research Questions

- Which cues best support reconstruction?
- Can too much prediction cause false confidence?
- How should the system show surprise or uncertainty?
- Can a user learn to interact with a predictive cue stream fluidly?

