# Idea Expansions

This notebook expands the creative engineering side of the encyclopedia. Each
idea is written as a concept card rather than a procedure.

## Attitude Toward Speculation

Many serious research directions start as strange analogies: the eye as a
screen, the cortex as a phosphor field, memory as reconstruction instead of
storage, or a prosthesis as a learned language instead of a camera replacement.

The useful move is not to ask only "is this real today?" The better sequence is:

```text
What is the wild version?
What is the closest known science?
What is the missing transducer or code?
What harmless model could represent the idea?
What test would make it less vague?
What would make it unsafe or unethical?
```

That keeps imagination active while still making the idea sharper.

## Core Direction: Perception As The Medium

The strongest screenless systems may carry less image and ask more of trained
perception.

```text
world
-> selected cue
-> active exploration
-> learned interpretation
-> useful action
```

The "medium" is not just glass, phosphor, light, current, sound, or touch. It
can become the stable relationship between cue and person. The device emits a
compressed sign. The user learns how that sign behaves when they move, ask,
reach, navigate, or remember.

Design challenge:

- remove the screen when it is only a habit
- remove pixels when features are enough
- remove photorealism when action structure matters more
- remove passive viewing when active scanning teaches the code
- remove universal mappings when a personal percept map is more honest
- remove direct memory claims when voluntary cueing is the grounded version

The companion roadmap for turning this into prototypes lives in
[Project Tracks: Perception As The Medium](PROJECT_TRACKS.md).

## Near-Term Assistive Concepts

### 1. Scene Skeleton

The scene skeleton converts a camera feed into a sparse map:

```text
open floor
walls
doors
stairs
people
moving objects
reachable objects
hazards
```

The output could be visual overlay, spatial audio, tactile feedback, or a future
prosthetic cue. It does not try to reproduce surfaces, colors, or textures. It
tries to answer "where can I go and what matters?"

### 2. Depth-First Vision

Depth-first vision prioritizes distance and collision risk before identity.

Useful channels:

- Near obstacle
- Drop-off or step
- Doorway
- Approaching motion
- Reachable object
- Free path

This is less glamorous than restored sight, but it targets immediate mobility
value.

### 3. Edge Lantern

The edge lantern extracts object boundaries and projects or encodes them as
high-contrast cues. It could be useful for low vision because edges often matter
more than texture.

Possible outputs:

- Bright outlines in a near-eye display
- Tactile pulses for edge direction
- Audio sweeps for object contour
- Sparse phosphene tracing in a future prosthesis

### 4. Motion-Only Eye

Motion-only vision ignores static detail and reports change.

Why it matters:

- Motion is behaviorally important.
- Event cameras naturally encode change.
- Lower bandwidth may be enough for avoiding moving hazards.
- Peripheral human vision is already motion-sensitive.

### 5. Confidence-Aware Assistive Vision

Any AI-assisted interface should encode uncertainty. A wrong confident cue can
be worse than no cue.

Possible confidence cues:

- Strong versus weak tactile pulse
- Clear versus soft tone
- Solid versus dashed overlay
- Repeated confirmation before high-risk labels

## Mid-Term Prosthetic Concepts

### 6. Phosphene Font

A phosphene font is a learned alphabet of artificial visual sensations. It may
include arrows, dots, lines, pulses, sweeps, and simple glyphs.

The concept accepts that phosphenes are not pixels. It asks which percepts are
stable enough to become symbols.

### 7. Artificial Fovea

An artificial fovea uses gaze or attention to decide where high information
density goes. The periphery receives only motion, hazard, and orientation cues.

This mirrors natural vision:

```text
central high acuity + coarse periphery + active eye movement
```

### 8. Retinal Interpreter

A retinal interpreter preprocesses sensor data into signals that resemble useful
retinal operations:

- Contrast enhancement
- Edge detection
- Motion onset
- Center-surround structure
- Brightness adaptation
- Temporal filtering

It does not need to perfectly copy biology. It only needs to give the remaining
visual pathway a more usable signal.

### 9. Cortical Handwriting

Cortical handwriting uses time as a binding mechanism. Instead of presenting a
shape all at once, it traces the shape.

```text
letter A
-> left stroke
-> right stroke
-> crossbar
-> perceived form
```

This borrows from handwriting, gesture, and raster scanning.

### 10. Personal Percept Map

A personal percept map records what each stimulation or cue pattern feels like
to one person.

Map fields:

- Perceived location
- Shape
- Brightness
- color-like quality, if any
- stability
- fatigue
- confusion with other cues
- emotional or attentional side effects

The map becomes the display surface.

## Hybrid And Workaround Concepts

### 11. Cross-Modal HUD

A cross-modal HUD divides information across channels:

| Feature | Channel |
| --- | --- |
| Collision risk | Tactile |
| Object identity | Speech or audio icon |
| Direction | Spatial audio |
| Text | Spoken output |
| Motion | Peripheral visual or tactile pulse |
| Confidence | Tone quality or pulse strength |

The goal is not to force every feature through one weak channel.

### 12. Visual Prosthesis Plus Semantic Narrator

A low-resolution prosthesis may show a vague object while an AI narrator labels
it. The user receives both:

```text
where it is + what it probably is
```

This could make low-resolution visual cues more useful without pretending they
are high-resolution images.

### 13. Training Game For Artificial Vision

A prosthetic or substitution system could include games that train:

- locating a cue
- identifying a direction
- recognizing a symbol
- following motion
- distinguishing confidence
- combining audio and tactile cues

This treats training as part of the interface, not an afterthought.

### 14. Task Modes

Different tasks need different encodings.

| Mode | Priorities |
| --- | --- |
| Walking | path, obstacles, stairs, moving objects |
| Reading | text line, character shape, OCR confidence |
| Faces | face location, identity if known and permitted, expression confidence |
| Kitchen | hot objects, edges, containers, labels |
| Workshop | tool location, sharp edges, hand proximity |
| Outdoors | vehicles, curbs, traffic direction, signs |

## Speculative But More Concrete Concepts

### 15. RF-Powered Local Transducer

RF is weak as a direct "send images into the brain" explanation. It becomes more
concrete when treated as a power or communication link to a local transducer.

```text
external controller
-> RF power/data
-> implanted receiver
-> local optical/electrical/acoustic output
-> target tissue
```

This still has hard implant and safety problems, but the mechanism is clearer.

### 16. Ultrasound-Gated Cue

Ultrasound may be more interesting as a selector or modulator than as a full
image carrier.

Concept:

```text
low-bandwidth cue
-> focused ultrasound target
-> temporary modulation
-> paired audio/tactile/visual cue
```

The idea is to coordinate channels, not create a high-resolution sonic TV in the
brain.

### 17. Magnetic-To-Local Conversion

Remote magnetic fields are spatially coarse. A local converter would shift the
hard part:

```text
magnetic field
-> local magnetoelectric or inductive receiver
-> local signal
```

This belongs in speculative transducer design, not direct remote memory or
image insertion.

### 18. Biological Phosphor

A biological phosphor is a conceptual target that lights, signals, or changes
state when stimulated. The closest real families are optogenetics, fluorescent
markers, and light-sensitive biological tools.

The speculative version asks whether tissue-compatible materials could become
safe intermediate converters between external energy and neural activity.

### 19. Neural Shadow Mask

A display shadow mask ensures each channel reaches the intended output region.
A neural shadow mask would be any structure or algorithm that prevents
stimulation from spreading to the wrong perceptual channel.

Possible forms:

- physical spacing
- local transducer selectivity
- timing separation
- inhibitory gating
- computational cancellation
- user-specific calibration

### 20. Brain-As-Renderer

This is a frontier concept. The grounded version is sparse cueing:

```text
small cue set -> user interpretation -> useful behavior
```

The far-edge version is arbitrary rich image or memory generation without a
clear mechanism yet.

## Fiction-Safe Ideas

These are good for speculative writing or future-facing diagrams, but should be
marked clearly:

- Dream cinema: voluntary dream-like replay triggered by ordinary cues.
- Cortical constellation: sparse dots that the user learns as a symbolic sky.
- Memory lantern: a device that presents multisensory cues to help recall.
- Perception compass: direction and salience only, no image.
- Synthetic aura: an artificial peripheral awareness field for hazards.
- Cognitive subtitle track: meaning-level labels layered over perception.

## Evaluation Questions

For any idea, ask:

- Does it preserve consent?
- Does it have a real carrier?
- Does it specify a transducer?
- Is the interface point clear?
- Does it need pixels, symbols, features, or semantics?
- What training burden does it create?
- What happens when it is wrong?
- What makes it more than a metaphor?
