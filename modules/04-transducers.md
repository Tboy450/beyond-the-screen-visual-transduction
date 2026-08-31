# 04. Transducers

A transducer converts information from one physical form into another. The CRT
phosphor screen is the classic example: electron impact becomes visible light.

## Core Transducer Types

| Transducer | Input | Output |
| --- | --- | --- |
| Phosphor | Electron impact or ultraviolet light | Visible light |
| Liquid crystal | Electric field | Changed polarization and light transmission |
| OLED material | Electric current | Visible light |
| LED junction | Electric current | Visible light |
| Retina | Photons | Neural signals |
| Electrode | Voltage or current | Local tissue depolarization |
| Optogenetic protein | Light | Cell activity change |
| Magnetic coil | Current | Changing magnetic field and induced electric field |
| Piezoelectric material | Electric field | Mechanical vibration, or the reverse |
| Magnetoelectric material | Magnetic field | Local electric effect |

## Transducer Placement

| Placement | Example | Meaning |
| --- | --- | --- |
| External screen | CRT, LCD, OLED | The body receives ordinary light. |
| Near-eye | Headset, waveguide, retinal projector | The display moves close to the receiver. |
| On-eye | Contact-lens display | Optics become wearable. |
| In-eye | Retinal implant | The device enters the biological visual chain. |
| On-cortex | Cortical prosthesis | The device bypasses eye and optic nerve. |
| Cross-modal | Audio or tactile device | The signal enters a different sense and is learned. |

## Design Tensions

| Tension | Explanation |
| --- | --- |
| Resolution versus safety | More channels can improve detail but increase complexity and risk. |
| Invasiveness versus precision | Implants can target more precisely but carry surgical risk. |
| Naturalness versus learnability | Natural-looking vision may be harder than a stable artificial code. |
| Bandwidth versus usefulness | A low-bandwidth cue can still be valuable if it is task-relevant. |
| Stability versus adaptation | Biological response changes over time; the interface must adapt. |

## Creative Workaround: Secondary Transducers

Some speculative routes become more plausible when the remote carrier is not
asked to stimulate tissue directly.

Instead of:

```text
remote field -> precise image in brain
```

use:

```text
remote field -> local receiver/transducer -> controlled local signal
```

This still does not make the idea easy or safe, but it gives the concept a real
engineering shape. The hard problems move to implant safety, localization,
power, heat, biocompatibility, and control.

## Related Entries

- [01. Display Physics](01-display-physics.md)
- [03. Carriers](03-carriers.md)
- [08. Neural Interfaces](08-neural-interfaces.md)

