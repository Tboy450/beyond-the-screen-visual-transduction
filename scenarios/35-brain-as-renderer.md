# 35. Brain-As-Renderer

- Status: Frontier
- Interface point: Whole perceptual system
- Carrier: Sparse sensory, symbolic, or neural cues
- Transducer: Any interface that can produce reliable cues
- Encoding style: Sparse prompts and reconstruction triggers
- Addressing method: Attention, learned association, and context
- Expected percept: User-generated reconstruction from minimal inputs
- Related modules: [Perceptual Rendering](../modules/09-perceptual-rendering.md), [Memory Branch](../modules/10-memory-branch.md)

## Summary

The brain-as-renderer concept asks whether a device can stop carrying the whole
scene and instead provide prompts that the user turns into a usable mental
model. It is less like streaming a movie and more like giving the brain a small
set of coordinates, labels, and motion cues.

## Chain Map

```text
world
-> compressed cue set
-> user expectation and memory
-> reconstructed scene model
-> action
```

## Grounded Examples

- A map lets someone imagine a place without seeing it.
- A few lines can imply a full object.
- A sound can locate a moving source.
- A label can change what a person notices.
- A memory cue can reconstruct a vivid scene.

## Expansion Ideas

- Use scene skeletons as external scaffolds for internal reconstruction.
- Use semantic labels as "rendering hints."
- Use motion and depth cues to constrain the user's mental model.
- Use personal memory of familiar places to fill in missing detail.
- Combine with a confidence grammar so uncertain reconstructions stay flexible.

## Research Questions

- How sparse can cues be before usefulness collapses?
- Which cue combinations produce the most accurate reconstruction?
- Can training make sparse cues feel immediate?
- How do memory and expectation help or distort the result?

