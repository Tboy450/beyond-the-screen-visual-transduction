# 01. Display Physics

Display technologies are different answers to one question: how can electrical
information become a controlled field of light?

## Baseline Families

| Display | Route | Screen Role |
| --- | --- | --- |
| CRT | Electron beam -> phosphor -> light | The screen is an active conversion surface. |
| Plasma | Gas discharge -> UV -> phosphor -> light | Gas and phosphor cooperate to produce pixels. |
| LCD | Backlight -> polarizer -> liquid crystal -> filter | The panel blocks or passes light. |
| OLED | Current -> emissive organic layer -> light | Each pixel emits its own light. |
| MicroLED | Current -> microscopic LED -> light | Each pixel is a tiny inorganic emitter. |
| Projector | Light source -> modulator -> optics -> surface | The image forms on a separate reflective screen. |
| Retinal projector | Light source -> optics -> retina | The image forms on the biological sensor. |

## Emission Versus Modulation

Displays either make light or control light that already exists.

| Mode | Examples | Implication |
| --- | --- | --- |
| Direct emission | CRT phosphor, OLED, MicroLED | The display creates photons at each addressed point. |
| Light modulation | LCD, DLP projection, shutters | A separate light source is shaped into an image. |
| Conversion emission | Plasma, fluorescence | One form of excitation becomes visible light. |
| Scanned emission | CRT, laser projector, retinal scanner | A moving spot becomes an image over time. |

## Why This Matters For The Encyclopedia

If a phosphor screen can be replaced by a different transducer, the endpoint can
move:

```text
electrical signal -> transducer -> light -> eye
```

can become:

```text
electrical signal -> transducer -> retina
```

or:

```text
electrical signal -> transducer -> visual cortex
```

The problem becomes less about building "a screen" and more about choosing a
safe, addressable, learnable conversion layer.

## Display-To-Biology Translation Table

| Display Concept | Biological Analogue |
| --- | --- |
| Pixel | Phosphene, receptive field, feature unit, or learned symbol. |
| Refresh rate | Neural timing, adaptation, persistence, and attention. |
| Brightness | Perceived intensity, salience, or confidence. |
| Color channel | Feature channel or cell-class channel. |
| Resolution | Number of stable, distinguishable percepts. |
| Contrast | Difference that the nervous system can reliably detect. |
| Calibration | Personal mapping between input and perception. |

## Expansion Ideas

- Compare displays by their carrier and transducer, not only by consumer
  category.
- Add diagrams showing where each technology enters the master chain.
- Build a table of "screen replacements": cornea, retina, electrode array,
  visual cortex, learned sensory language, and semantic cue system.
- Track whether a system preserves normal optics or bypasses them.

## Related Entries

- [00. CRT Baseline](00-crt-baseline.md)
- [04. Transducers](04-transducers.md)
- [05. Eye Optics](05-eye-optics.md)
- [08. Neural Interfaces](08-neural-interfaces.md)

