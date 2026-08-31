# 08. Neural Interfaces

Neural interfaces try to introduce information into the nervous system directly
or indirectly. In this encyclopedia they are organized by interface point,
carrier, and evidence level.

## Interface Families

| Family | Target | Status | Typical Percept |
| --- | --- | --- | --- |
| Retinal prosthesis | Retina | Research | Spots, light patterns, crude form cues. |
| Optogenetic visual therapy | Modified retinal cells | Research | Partial restored visual behavior with special goggles. |
| Optic-nerve interface | Optic nerve | Research/speculative | Phosphenes or coarse visual sensations. |
| Cortical visual prosthesis | Visual cortex | Research | Phosphenes and traced forms. |
| TMS | Cortex via magnetic induction | Research | Phosphenes under some conditions. |
| Focused ultrasound | Brain tissue | Research | Modulation or phosphene reports in studies. |
| Sensory substitution | Touch or hearing | Research | Learned spatial interpretation, not direct sight. |

## Why "Neural Pixels" Are Difficult

- A neuron is not a pixel.
- One electrode can affect many cells.
- One percept can be shaped by multiple sites.
- Tissue changes with time.
- Stimulation can spread.
- Perception depends on state, attention, and learning.
- Natural vision is processed before it becomes conscious.

## More Plausible Engineering Direction

The most realistic path is layered:

```text
sensors
-> AI or signal preprocessor
-> compressed task-relevant code
-> calibrated stimulation or cross-modal output
-> user training
-> feedback and recalibration
```

This is less dramatic than "uploading images," but far more coherent.

## Creative Concepts

| Concept | Description |
| --- | --- |
| Closed-loop phosphene mapper | The user reports percepts, and the system updates its stimulation map. |
| Cortical handwriting | Dynamic stimulation traces lines, letters, or shapes over time. |
| Phosphene icon set | A small vocabulary of reliable visual symbols. |
| Hybrid residual-vision overlay | Adds artificial cues only where natural vision is missing. |
| Semantic prosthesis | Uses object detection to communicate meaning through simple cues. |
| Training-first interface | Treats the device like a new sensory language rather than failed normal vision. |

## Scope

This module stays at the level of concepts, research summaries, interfaces,
encoding strategies, and open problems. The useful contribution is the map:
where the signal enters, what code it carries, and what kind of perception it
might support.

## Related Entries

- [03. Carriers](03-carriers.md)
- [04. Transducers](04-transducers.md)
- [06. Retina](06-retina.md)
- [07. Visual Pathway](07-visual-pathway.md)
- [11. Safety And Ethics](11-safety-and-ethics.md)
