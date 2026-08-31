# 40. Audio-Visual Substitution

- Status: Research
- Interface point: Hearing and learned interpretation
- Carrier: Sound
- Transducer: Speaker, headphones, or bone conduction
- Encoding style: Visual features translated into auditory patterns
- Addressing method: pitch, time, stereo position, rhythm, or timbre
- Expected percept: Learned spatial understanding through sound
- Related modules: [Signal Encoding](../modules/02-signal-encoding.md), [Perceptual Rendering](../modules/09-perceptual-rendering.md)

## Summary

Audio-visual substitution translates visual information into sound. It does not
create normal sight, but it can give access to spatial or object information
through training.

## Chain Map

```text
camera
-> visual feature extraction
-> sound mapping
-> hearing
-> learned spatial interpretation
```

## Encoding Possibilities

| Visual Feature | Audio Mapping |
| --- | --- |
| Horizontal position | Stereo pan or time position. |
| Vertical position | Pitch. |
| Brightness | Loudness or harmonic richness. |
| Motion | Sweep or rhythm. |
| Object class | Earcon or spoken label. |
| Distance | Reverberation, pitch shift, or pulse rate. |

## Expansion Ideas

- Use musical intervals for object height.
- Use spatialized sound for direction.
- Add spoken labels only when confidence is high.
- Use event-based audio so only changes make sound.
- Combine audio scene skeletons with tactile hazard cues.

## Research Questions

- Which mappings are easiest to learn?
- Can trained users experience the audio as spatial rather than merely sound?
- How much detail becomes overwhelming?
- Can AI labels reduce the learning burden?

