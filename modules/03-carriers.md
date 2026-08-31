# 03. Carriers

A carrier is the physical thing that moves information from one place to
another. The same information can ride on many carriers, but each carrier has
different constraints.

## Carrier Table

| Carrier | Where It Fits | Strength | Limit |
| --- | --- | --- | --- |
| Electron beam | CRT vacuum tube | Precise scanning in a controlled tube. | Not suitable as a free-space biological carrier. |
| Visible light | Natural vision and optics | Native input to the retina. | Blocked by tissue and requires line-of-sight optics. |
| Infrared light | Sensing and optical communication | Useful for devices and some imaging. | Not visible without conversion. |
| Ultraviolet light | Phosphor excitation | Can convert through phosphors. | Tissue hazard; not a normal safe visual carrier. |
| Electric current | Electrodes | Direct local stimulation. | Needs contact, implant, or conductive path. |
| Magnetic field | TMS and induction | Can act through skull noninvasively. | Coarse spatial control and individual variability. |
| RF/microwave | Wireless power or communication | Can reach electronics and some tissue regions. | Does not directly encode safe high-resolution vision. |
| Ultrasound | Focused acoustic stimulation | Can be focused deeper than light. | Safety and mechanism questions remain. |
| Chemical state | Biological modulation | Can change cell behavior. | Slow and difficult to address at display speeds. |
| Neural spikes | Native nervous-system signals | The brain already uses them. | Hard to write precise patterns safely. |

## Carrier Versus Transducer

Separate the carrier from the effect.

```text
RF signal -> implanted receiver -> electrical stimulation
```

is not the same as:

```text
RF signal -> brain receives image directly
```

The first path has a concrete local transducer. The second is usually a vague
claim unless it specifies a biological mechanism, addressing method, and safety
model.

## Creative Carrier Architectures

| Architecture | Conceptual Use |
| --- | --- |
| RF-powered implant | RF supplies power or data; the implant performs local stimulation. |
| Optical data link | Light sends information to a wearable, lens, or implant. |
| Ultrasound selection | Sound focuses on a region while a second mechanism controls signal content. |
| Magnetic wake/sync | Magnetic fields synchronize or gate a local device rather than encode an image. |
| Multi-carrier redundancy | Vision-like information is split across light, sound, and touch. |
| Passive environmental tagging | Objects emit or reflect codes that an assistive device translates into cues. |

## Plausibility Filter

For any carrier-based proposal, ask:

- What physical quantity carries the information?
- How is it modulated?
- What receives it?
- What converts it into neural or optical effect?
- How is the target selected spatially?
- What prevents heating, damage, overstimulation, or false perception?
- Can the user turn it off?

## Related Entries

- [04. Transducers](04-transducers.md)
- [08. Neural Interfaces](08-neural-interfaces.md)
- [11. Safety And Ethics](11-safety-and-ethics.md)
