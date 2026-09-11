# At a Glance: Signals to Perception

[Book home](README.md) · [Contents](CONTENTS.md) · [Introduction](INTRODUCTION.md)

This is the encyclopedia's condensed reference chapter. It preserves the
original overview tables for readers who want to scan the whole subject.
For fuller explanations, follow the [chapter contents](CONTENTS.md); for the
maintained entry list and page availability, use the [scenario index](scenarios/README.md).

## The Organizing Model

```text
information -> encoding -> carrier -> transducer -> sensory interface
            -> neural processing -> perception -> interpretation or action
```

The arrows identify transformations to investigate. They simplify systems
that may contain parallel pathways, feedback, and repeated conversions.
Memory can influence perception and can follow experience; it is not a
mandatory final stage of every display chain.

## Interface Families

These are different routes through the subject, not steps on a single scale
of scientific progress. An ordinary audio cue can be more mature than an
implant even though its meaning is more abstract.

| Family | Where information enters | Reading route |
| --- | --- | --- |
| Conventional and near-eye displays | Light reaches the eye and functioning photoreceptors. | [Display physics](modules/01-display-physics.md), [eye optics](modules/05-eye-optics.md) |
| Retinal interfaces | Artificial input acts on surviving or modified retinal cells. | [Retina](modules/06-retina.md), [electronic retina](scenarios/12-electronic-retina.md) |
| Visual-pathway interfaces | Input targets neural structures beyond the retina. | [Visual pathway](modules/07-visual-pathway.md), [neural interfaces](modules/08-neural-interfaces.md) |
| Sensory substitution and cue systems | Sound, touch, or remaining vision carries selected information. | [Perceptual rendering](modules/09-perceptual-rendering.md) |
| Memory and imagery concepts | Ordinary recall cues or explicitly hypothetical interfaces. | [Memory branch](modules/10-memory-branch.md) |

Use the [evidence guide](sources/evidence-guide.md) to distinguish an established
component, a reported study, and a proposed complete system.

## 00. Display Transduction Foundations

A useful visual technology can be treated as a chain: signal, carrier,
conversion layer, receiver, and learned interpretation. A CRT gives one
concrete route through that chain.

| Stage | Function |
| --- | --- |
| Signal input | The incoming video signal encodes brightness and timing. |
| Electron gun | A heated cathode emits electrons into a vacuum tube. |
| Acceleration | High voltage accelerates electrons toward the screen. |
| Deflection | Electric or magnetic fields steer the beam. |
| Raster scan | The beam draws the image line by line. |
| Phosphor | The screen coating glows when struck by electrons. |
| Persistence | The phosphor glow and the eye's temporal integration smooth the scan into an image. |
| Color CRT | Separate red, green, and blue phosphors are addressed through beam control and mask geometry. |

Key insight: the useful object is not just a screen. It is a coordinated
signal-to-perception chain. A small controlled event can be addressed over time
and integrated by the visual system into a stable experience.

## 01. Display Physics Routes

| Technology | Signal Route | Lesson |
| --- | --- | --- |
| CRT | Electrical signal -> electron beam -> phosphor -> light | A scanned beam can become a full image. |
| Plasma display | Electrical signal -> gas discharge -> ultraviolet -> phosphor -> light | Display chains can include gas and UV stages before visible light. |
| LCD | Electrical signal -> liquid-crystal orientation -> polarization control -> filtered backlight | Some displays modulate existing light rather than emit it. |
| OLED | Electrical current -> organic emissive material -> light | Each pixel can be a self-emitting source. |
| MicroLED | Electrical current -> microscopic LED emitters -> light | Dense direct emitters can replace scanned beams and backlights. |

## 02. Signal Encoding

Visual information can be represented as:

- Analog voltage over time.
- Raster scan timing.
- Digital pixels.
- Pulse trains.
- Frequency, phase, or timing codes.
- Edge, contrast, motion, depth, or object features.
- Semantic descriptions such as "face," "door," "motion left," or "hazard."
- Memory cues or associative prompts.

The deeper question is whether a screenless interface must reproduce pixels, or
whether it can transmit a more compact representation that the visual system can
learn to interpret.

## 03. Carriers

| Carrier | Role | Notes |
| --- | --- | --- |
| Electron beam | Scanned display and vacuum-tube carrier | Precise in a tube, not a practical free-space biological carrier. |
| Visible light | Normal vision and projection | The safest familiar route when sent through the eye. |
| Infrared | Optical carrier outside visible range | Requires conversion or a biological/technical detector. |
| Ultraviolet | Can excite phosphors | Hazardous to tissue and not a normal vision route. |
| Electric current | Electrode-based stimulation | Requires contact or implanted interfaces for precision. |
| Magnetic field | Can induce neural effects | Noninvasive but spatially coarse compared with implants. |
| RF/microwave | Field-based energy carrier | Not a magic visual channel; would need a plausible transducer. |
| Ultrasound | Acoustic pressure carrier | Can be focused, but neural effects and safety remain research topics. |
| Chemical/molecular state | Biological transduction route | Slow compared with display refresh; relevant to optogenetics and biology. |
| Neural spikes | Native nervous-system carrier | The brain's own signaling format, not a simple pixel bus. |

## 04. Transducers

A phosphor screen is one familiar example of a transducer.

| Transducer | Converts | Example |
| --- | --- | --- |
| Phosphor | Electron or UV excitation -> visible light | CRT and plasma-style display logic. |
| Liquid crystal | Electric field -> optical polarization change | LCD. |
| Organic semiconductor | Electric current -> photons | OLED. |
| LED junction | Electric current -> photons | LED and MicroLED. |
| Retina | Photons -> neural signals | Natural vision. |
| Electrode | Circuit signal -> local tissue stimulation | Retinal or cortical prostheses. |
| Optogenetic cell | Light -> neural activity | Research and experimental prosthetic concepts. |
| Focused ultrasound | Acoustic energy -> neural modulation | Noninvasive neuromodulation research. |
| Magnetic coil | Changing magnetic field -> induced electric field | TMS and phosphene research. |

## 05. Eye Optics

Before any retinal or neural interface, normal vision passes through optical
preprocessing:

- Cornea bends incoming light.
- Lens changes focus.
- Pupil controls light level.
- Eye movement constantly samples the world.
- The retinal image is inverted and distorted by real optics.
- The brain stabilizes and interprets the result.

Screenless optical systems can still use the eye, for example by projecting
light onto the retina, using near-eye displays, or scanning controlled light
through optics. These do not remove biology; they move the display closer to the
biological receiver.

## 06. Retina

The retina is not just a passive camera sensor. It performs early computation.

| Layer | Role |
| --- | --- |
| Rods and cones | Convert light into biological signals. |
| Bipolar cells | Relay and shape signals from photoreceptors. |
| Horizontal cells | Support lateral interactions and contrast effects. |
| Amacrine cells | Contribute temporal and motion-related processing. |
| Ganglion cells | Send spike trains into the optic nerve. |

Retinal prostheses try to use surviving retinal circuitry when photoreceptors
or other parts of the retina have degenerated. The challenge is that stimulating
one physical point does not necessarily create one clean visual pixel.

## 07. Visual Pathway

The standard visual route is:

```text
retina
-> ganglion cell axons
-> optic nerve
-> optic chiasm
-> optic tract
-> lateral geniculate nucleus
-> optic radiations
-> primary visual cortex
-> higher visual areas
```

Each stage changes the representation. By the time visual information reaches
conscious perception, it has been filtered, routed, compared, interpreted, and
combined with attention and memory.

## 08. Neural Interface Families

| Interface | Status | Description | Main Limitation |
| --- | --- | --- | --- |
| Retinal projection | Research | Send controlled light to the retina without a wall screen. | Eye tracking, safety, focus, field of view. |
| Retinal prosthesis | Research | Electrically stimulate retinal neurons. | Low resolution and complex retinal coding. |
| Optogenetic retina | Research | Make cells light responsive and stimulate them optically. | Gene delivery, brightness, safety, latency. |
| Optic-nerve interface | Research/speculative | Stimulate the visual signal cable after the retina. | Fibers are densely mixed and hard to address. |
| LGN interface | Speculative | Target the thalamic visual relay. | Deep target, complex relay function. |
| Cortical visual prosthesis | Research | Stimulate visual cortex to create phosphenes or patterns. | Phosphenes are not clean pixels; surgery and coding are hard. |
| TMS phosphene interface | Research | Use magnetic stimulation to evoke visual percepts. | Coarse targeting, variability, not image-level control. |
| Focused ultrasound interface | Research | Use acoustic energy to modulate visual cortex. | Safety, precision, repeatability, and interpretation. |
| Sensory substitution | Research | Translate visual information into sound or touch. | Requires learning and does not directly create normal sight. |

## Creative Engineering Concepts And Workarounds

These concepts are intentionally framed as research directions or design
patterns, not build instructions. Their value is that they show ways around the
naive "make neural pixels" problem.

| Concept | Plausibility | Workaround | Main Limit |
| --- | --- | --- | --- |
| Foveated Prosthetic Vision | Proposed | Put the highest information density where gaze or attention is directed and use lower-detail cues in the periphery. | Requires eye tracking, fast adaptation, and careful user calibration. |
| Event-Camera Encoder | Proposed | Send only changes, motion, flashes, and edges instead of full video frames. | Static scenes may lose detail unless paired with scanning or semantic cues. |
| Phosphene Font | Research/speculative | Design a small alphabet of stimulation patterns that users can reliably recognize, rather than trying to create natural images. | It becomes an artificial language, not normal vision. |
| Personal Retinotopic Map | Research | Build a user-specific map from stimulation sites to perceived locations and shapes. | Maps can drift over time and may change with attention, fatigue, or tissue response. |
| Closed-Loop Percept Calibrator | Proposed | The user reports what they perceive, and the system adjusts encoding until percepts become stable. | Requires feedback, training, and long-term recalibration. |
| Hybrid Optical-Neural Overlay | Speculative | Use normal or remaining vision for what still works, then add artificial cues only where information is missing. | Needs reliable detection of missing or degraded visual regions. |
| Semantic Safety Overlay | Proposed | Prioritize useful labels like obstacle, stairs, face, text, vehicle, door, or motion direction over photorealistic detail. | Less immersive, but potentially more useful for navigation. |
| Depth-First Vision | Proposed | Encode depth, collision risk, edges, and motion before color or texture. | Sacrifices visual richness for practical spatial awareness. |
| Attention-Guided Display | Speculative | Use gaze, task, or context to decide what information deserves bandwidth. | Wrong attention estimates could hide important details. |
| Multi-Sense Redundancy | Proposed | Pair weak visual percepts with audio or tactile confirmation so the user does not depend on one fragile channel. | Training burden and sensory overload. |
| Learned Visual Language | Proposed | Treat the interface like learning Braille or a new instrument: consistent symbols become useful through practice. | It may never feel like natural sight. |
| Cortical Shape Tracing | Research | Trace shapes dynamically across cortical stimulation sites instead of flashing isolated dots. | Requires stable percept mapping and invasive hardware. |
| Retinal Preprocessor | Speculative | Convert camera data into signals that mimic retinal contrast, motion, and edge processing before stimulation. | Retinal codes differ by cell type and disease state. |
| AI Scene Compressor | Proposed | Use computer vision to reduce a scene into the few cues most relevant to the task. | Model errors become perceptual errors. |
| Virtual Cane Display | Proposed | Encode near-field obstacles and surface changes as simple visual, audio, or tactile cues. | Useful for mobility, not a replacement for full vision. |
| Peripheral Motion Radar | Speculative | Give the user coarse motion awareness around the visual field while central detail comes from another channel. | Peripheral cue placement and false alarms are hard. |
| RF-Powered Local Transducer | Speculative | RF is used only to power or communicate with a local transducer; the local device performs the actual stimulation. | Still requires a safe, implanted, addressable transducer. |
| Ultrasound-Gated Neural Pixel | Speculative | Ultrasound selects a region while another mechanism provides the effective stimulation signal. | Coupling, targeting, safety, and coding are unresolved. |
| Magnetic-To-Local Conversion | Speculative | External magnetic fields influence a local implanted converter rather than trying to write images remotely. | Requires an implant and strong safety validation. |
| Memory Cue Companion | Proposed | Use ordinary sensory prompts, labels, images, or spatial cues to support recall without pretending to write memories. | Supports memory retrieval; does not create memories directly. |

### Workarounds By Bottleneck

| Bottleneck | Workaround Direction |
| --- | --- |
| Low resolution | Use symbols, edges, motion, depth, or scene labels instead of full images. |
| Poor targeting | Calibrate each user's percept map and avoid assuming anatomy is a clean grid. |
| Limited bandwidth | Use event-based sensing, foveation, compression, and task-aware filtering. |
| Unstable percepts | Keep a closed feedback loop and update the map over time. |
| Slow adaptation | Build a learnable visual language with consistent cues. |
| Safety risk | Prefer external, reversible, low-power, clinically supervised designs. |
| Ambiguous perception | Pair artificial visual cues with audio, tactile, or text feedback. |
| Memory interface frontier | Split memory ideas into cueing, imagery, recall support, and direct-write hypotheses. |

### Unique Concept Seeds

These are deliberately creative and should be treated as prompts for research
notes, fiction, or future scenario pages.

| Seed | Idea |
| --- | --- |
| The Phosphene Typewriter | A minimal cortical or retinal alphabet for letters, arrows, and warnings. |
| The Artificial Fovea | A wearable system that gives high-detail artificial cues only at the user's current point of interest. |
| The Scene Skeleton | A display that encodes walls, doors, stairs, people, and moving objects as a sparse navigational graph. |
| The Motion-Only Eye | A prosthetic mode that ignores texture and color and reports movement vectors across the field. |
| The Edge Lantern | A system that lights up boundaries and object outlines while leaving detail to residual vision or other senses. |
| The Perceptual Codec | A compression system designed around what the visual system can learn, not what a camera records. |
| The Retinal Interpreter | A front-end model that converts camera images into retina-like contrast and timing signals. |
| The Cross-Modal HUD | A headset that combines tiny visual cues, spatial audio, and touch pulses into one learned interface. |
| The Dream Rehearsal Notebook | A noninvasive memory-support concept that uses images, narration, and repetition to strengthen voluntary recall. |
| The Consent-Locked Interface | Any neural or cognitive interface requires active, continuous user authorization before stimulation or data capture. |

## 09. Scenario Library

The statuses below describe the listed concepts. Proposed extensions are not
validated by research on a neighboring component. For study boundaries, see
the [evidence guide](sources/evidence-guide.md).

The full scenario index lives in [scenarios/README.md](scenarios/README.md).

### Conventional Display Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 01 | Electron-To-Phosphor CRT | Established | A steered electron beam scans a phosphor-coated screen. |
| 02 | Gas-To-Phosphor Plasma Display | Established | Ionized gas and UV excite phosphors to produce visible pixels. |
| 03 | Liquid-Crystal Light Valve | Established | Electric fields rotate liquid crystals to modulate a backlight. |
| 04 | Self-Emissive OLED | Established | Current-driven organic layers emit light directly. |
| 05 | MicroLED Photon Array | Established | Dense microscopic LED emitters form a direct pixel array. |

### Screenless Optical Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 06 | [Retinal Projection](scenarios/06-retinal-projection.md) | Research | Image light is projected onto the retina instead of a physical screen. |
| 07 | Retinal Scanner | Research | A controlled beam scans the retina using scanned-display logic. |
| 08 | Retinal Waveguide | Proposed | A wearable or lens routes image light into the eye. |
| 09 | Retinal Holograph | Speculative | Phase-controlled light forms structured retinal patterns. |
| 10 | Virtual Phosphor | Speculative | A temporary or biological-adjacent layer replaces the fixed screen phosphor. |

### Retina And Optic-Nerve Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 11 | Photoreceptor Interface | Research | Input targets rods, cones, or restored light-sensitive cells. |
| 12 | [Electronic Retina](scenarios/12-electronic-retina.md) | Research | Electrode arrays stimulate retinal neurons. |
| 13 | [Optogenetic Retina](scenarios/13-optogenetic-retina.md) | Research | Engineered cells convert light into neural activity. |
| 14 | [Ganglion-Cell Encoder](scenarios/14-ganglion-cell-encoder.md) | Speculative | The system targets retinal output cells directly. |
| 15 | Optic-Nerve Interface | Research/speculative | Visual data enters through stimulation of optic nerve fibers. |

### Cortex And Higher-Vision Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 16 | Cortical Phosphor | Research | Visual cortex becomes the target that evokes light-like percepts. |
| 17 | [V1 Neural Display](scenarios/17-v1-neural-display.md) | Research | Retinotopic visual cortex is stimulated as a crude display surface. |
| 18 | [Cortical Form Tracing](scenarios/18-cortical-form-tracing.md) | Research | Dynamic stimulation attempts to create coherent shapes from phosphene sequences. |
| 19 | Feature-Space Display | Speculative | The interface encodes edges, colors, motion, or depth rather than pixels. |
| 20 | Object-Space Display | Speculative | The system transmits object-level percepts instead of a full image. |
| 21 | Scene-Space Display | Speculative | The system encodes navigation, layout, and salience. |

### Alternative Carrier Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 22 | Electrical-To-Neural | Research | Electrodes deliver structured stimulation to target tissue. |
| 23 | Optical-To-Neural | Research | Light becomes the carrier for biological or optogenetic targets. |
| 24 | [Magnetic Phosphene System](scenarios/24-magnetic-phosphene-system.md) | Research | Time-varying magnetic fields can evoke visual sensations. |
| 25 | Spatial Magnetic Array | Speculative | Multiple magnetic sources attempt more detailed targeting. |
| 26 | RF-To-Transducer-To-Neural | Speculative | RF powers or controls a local transducer rather than directly "sending images." |
| 27 | [Focused-Ultrasound Vision Interface](scenarios/27-focused-ultrasound-vision-interface.md) | Research on stimulation; speculative display | Acoustic focus modulates visual regions. |
| 28 | Acoustic Hologram | Speculative | Interference of sound fields creates spatial stimulation patterns. |
| 29 | [RF-Powered Local Transducer](scenarios/29-rf-powered-local-transducer.md) | Speculative | RF powers or communicates with an implanted local converter rather than directly carrying vision into the brain. |
| 30 | Magnetic-To-Local Conversion | Speculative | A local transducer converts external magnetic influence into a local neural signal under controlled conditions. |

### Perceptual And Semantic Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 31 | [Perceptual Compression Display](scenarios/31-perceptual-compression-display.md) | Speculative | Only useful features are transmitted, not every pixel. |
| 32 | [Predictive-Coding Display](scenarios/32-predictive-coding-display.md) | Speculative | The interface nudges brain predictions and lets perception fill in gaps. |
| 33 | Neural Texture Engine | Speculative | A system evokes surfaces, motion, or scene texture directly. |
| 34 | [Semantic Visual Interface](scenarios/34-semantic-visual-interface.md) | Speculative | The system sends meanings like "person ahead" instead of a picture. |
| 35 | [Brain-As-Renderer](scenarios/35-brain-as-renderer.md) | Frontier | The brain reconstructs scenes from sparse prompts; the challenge is turning that into a real interface. |
| 36 | AI Scene Compressor | Proposed | Computer vision chooses the few cues most useful for the user's current task. |
| 37 | [Scene Skeleton](scenarios/37-scene-skeleton.md) | Speculative | The environment is encoded as a sparse graph of surfaces, openings, obstacles, and moving agents. |
| 38 | Depth-First Vision | Proposed | Depth and collision risk are prioritized ahead of color and texture. |
| 39 | [Phosphene Font](scenarios/39-phosphene-font.md) | Research/speculative | A small set of learned phosphene symbols carries text, arrows, warnings, or object classes. |

### Cross-Modal Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 40 | [Audio-Visual Substitution](scenarios/40-audio-visual-substitution.md) | Research | Visual data is translated into sound patterns. |
| 41 | [Tactile-Visual Substitution](scenarios/41-tactile-visual-substitution.md) | Research | Visual data becomes vibration or pressure patterns. |
| 42 | Multisensory Display | Speculative | Sound, touch, vestibular cues, and visual cues combine into a learned scene model. |
| 43 | Cross-Modal HUD | Proposed | A wearable interface splits information across small visual, audio, and tactile cues. |
| 44 | Virtual Cane Display | Proposed | Near-field obstacles and surface changes are translated into simple learned cues. |

### Temporal Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 45 | [Neural Scanning Interface](scenarios/45-neural-scanning-interface.md) | Speculative | A scanned neural stimulus updates perception over time like a raster beam. |
| 46 | Temporal Multiplexing | Speculative | One channel addresses many perceptual points at different times. |
| 47 | Spike-Timing Display | Speculative | Fine spike timing carries the representational signal. |
| 48 | Population-Code Display | Speculative | Patterns across many neurons carry the signal. |
| 49 | [Oscillatory Display](scenarios/49-oscillatory-display.md) | Speculative | Brain rhythm phase or frequency becomes part of the encoding scheme. |
| 50 | [Event-Based Vision Stream](scenarios/50-event-based-vision-stream.md) | Proposed | Sensor brightness-change events are processed into selected user cues. |
| 51 | [Cortical Shape Tracing — see 18](scenarios/18-cortical-form-tracing.md) | Research | Sequential stimulation attempts to trace recognizable forms instead of isolated dots. |

### Memory Branch Scenarios

| ID | Title | Status | Short Description |
| --- | --- | --- | --- |
| 52 | Percept-To-Memory | Established concept | Real perception can become memory through attention and consolidation. |
| 53 | Memory Cue Interface | Research concept | A partial cue can help reconstruct a remembered image or scene. |
| 54 | [Associative Reconstruction](scenarios/54-associative-reconstruction.md) | Research concept | Memory recall uses fragments, context, and association rather than stored pixels. |
| 55 | [Dream Rehearsal Notebook](scenarios/55-dream-rehearsal-notebook.md) | Proposed | Ordinary images, narration, and repetition are proposed as recall prompts; benefit requires evaluation. |
| 56 | [Memory-State Interface](scenarios/56-memory-state-interface.md) | Frontier | Direct memory writing is not established, but the idea can be broken into cueing, imagery, recall, and consolidation mechanisms. |
| 57 | [Conceptual Injection](scenarios/57-conceptual-injection.md) | Frontier | Remote arbitrary memory insertion is a far-edge scenario for exposing missing carriers, targets, and transducers. |

## 10. Memory Branch

The memory branch should stay separate from visual prosthetics.

Visual prosthetics ask:

```text
Can a device create useful visual percepts?
```

Memory implantation asks something much harder:

```text
Can a device create a durable, personally integrated memory with context,
meaning, confidence, emotion, and recall behavior?
```

A visual percept is a present experience. A memory is a distributed,
reconstructive state involving perception, attention, hippocampal systems,
association, consolidation, and later recall. Display analogies become weakest
here because the brain is not a video recorder.

## 11. Open Problems

- Phosphenes are not clean pixels.
- Biological maps are distorted, adaptive, and person-specific.
- High spatial resolution is hard without invasive interfaces.
- Noninvasive stimulation is generally less spatially precise.
- The retina preprocesses information before the brain sees it.
- V1 is retinotopic, but not a simple display panel.
- Higher visual perception includes prediction, attention, and meaning.
- Any implant raises safety, durability, infection, consent, and ethics issues.
- Remote-field ideas need clear physical mechanisms and strong safety limits.
- Memory-level claims should be decomposed into cueing, imagery, recall,
  consolidation, and direct-write hypotheses.

## Continue Reading

- [Full chapter contents](CONTENTS.md)
- [Scenario index and entry template](scenarios/README.md)
- [Original diagrams](modules/12-gallery.md)
- [Bibliography](sources/bibliography.md)
