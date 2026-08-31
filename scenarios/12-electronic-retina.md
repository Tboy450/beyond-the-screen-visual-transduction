# 12. Electronic Retina

- Status: Research
- Interface point: Retina
- Carrier: Electrical current from an implanted device
- Transducer: Electrode array
- Encoding style: Reduced visual signal, contrast map, edges, or pulse train
- Addressing method: Electrode position and stimulation timing
- Expected percept: Phosphenes, light patterns, crude form or motion cues
- Main limitations: Resolution, retinal disease state, percept distortion,
  long-term stability, surgery

## Summary

An electronic retina attempts to bypass damaged photoreceptors or retinal input
stages by stimulating surviving retinal neurons. The user does not receive a
normal image. They receive artificial visual sensations that may become useful
through training.

## Chain Map

```text
camera or image source
-> processor
-> electrode array
-> retinal neurons
-> optic nerve
-> visual cortex
-> learned percept
```

## Engineering Workarounds

- Encode edges and motion instead of raw pixels.
- Calibrate each electrode to the user's reported percept.
- Use sequential stimulation to reduce percept merging.
- Add audio or tactile confirmation for uncertain object recognition.
- Keep the artificial cue language small and learnable.

## Open Questions

- Which retinal cells remain usable in a given disease?
- How should stimulation mimic retinal preprocessing?
- How stable are phosphene maps over months or years?
- When is a semantic cue more useful than a noisy spatial percept?

## Expansion Notes

Good expansion paths include epiretinal versus subretinal approaches,
photovoltaic designs, percept mapping, training systems, and feature-first
encoding.
