# Research Map

This page grounds the encyclopedia in existing research areas before branching
into speculative design space.

## 0. Historical Pattern: Radio To Perception

The historical spine of the project starts with early radio: a message leaves
its original physical form, travels through an invisible carrier, and returns
through a receiver as something a human can interpret. That same pattern
reappears in television, radar, transistors, image sensors, cochlear implants,
retinal prostheses, sensory substitution, and semantic AI.

```text
known physics
-> carrier
-> transducer
-> encoding
-> receiver
-> learned interpretation
```

This history does not prove that every screenless-perception concept will work.
It gives the project a fairer test than reflexive dismissal. Instead of asking
only "does this sound strange?" ask which layer is missing, weak, or testable.

For the full timeline and argument, see
[Historical Context: From Radio To Screenless Perception](HISTORICAL_CONTEXT.md).

## 1. CRT And Display Physics

CRT televisions demonstrate a complete analog transduction chain:

```text
signal timing
-> electron emission
-> beam acceleration
-> beam steering
-> phosphor emission
-> photons
-> visual system
```

The research value is conceptual. The CRT shows that a display can be treated as
a controlled physical stimulus, not merely a flat picture. Its key abstractions
are scanning, addressing, modulation, transduction, persistence, and perception.

### Expansion Questions

- What is the minimum controlled stimulus needed to create a useful percept?
- Can scanning beat static array addressing for low-channel interfaces?
- What is the biological equivalent of phosphor persistence?
- Can temporal integration in the nervous system be exploited safely?

## 2. Retinal Projection And Near-Eye Displays

Retinal projection keeps the biological visual system mostly intact. The screen
is removed, but light still enters the eye.

```text
image data
-> light source
-> scanning optics or waveguide
-> retina
-> normal visual pathway
```

This is among the most concrete "screenless" branches because it does not need
to write neural codes directly. It instead treats the retina as the projection
surface.

### Research Anchors

- Virtual retinal display and retinal scanning display work.
- Near-eye display and waveguide optics.
- Foveated near-eye displays.
- Pupil-tracked retinal projection.

### Expansion Questions

- Can retinal projection become comfortable enough for long sessions?
- Can eye tracking make foveated projection stable?
- Can retinal projection assist low-vision users without replacing natural
  vision?
- Can an optical display become more useful by adding semantic overlays instead
  of full video?

## 3. Retinal Prostheses

Retinal prostheses move the interface inside the biological visual chain.

```text
camera or sensor
-> processor
-> retinal stimulation
-> optic nerve
-> visual cortex
-> learned percept
```

The main families include epiretinal, subretinal, suprachoroidal, and
photovoltaic approaches. They aim to create usable artificial vision, often
through phosphenes or low-resolution form cues.

### Research Anchors

- Epiretinal implants such as Argus-style systems.
- Subretinal and photovoltaic implants such as PRIMA-style systems.
- Studies on improving phosphene localization and spatial resolution.
- Clinical and engineering reviews of retinal prosthesis limitations.

### Expansion Questions

- Should the encoder mimic retinal cell types or use an artificial learned
  language?
- Can sequential stimulation make shapes clearer than static stimulation?
- How should systems handle eye movement?
- How should users train with a limited perceptual vocabulary?

## 4. Optogenetic Vision Restoration

Optogenetics attempts to make surviving retinal cells responsive to light.

```text
gene therapy or cell modification
-> engineered light sensitivity
-> special optical stimulation
-> retinal output
-> visual pathway
```

This branch is important because it replaces electrode stimulation with
biological light sensitivity. It still requires careful image processing,
special goggles or illumination, and clinical oversight.

### Research Anchors

- Human case reports of partial visual function recovery after optogenetic
  therapy.
- Reviews on vision restoration through optogenetic therapy and gene delivery.

### Expansion Questions

- Which retinal cells should become light-sensitive?
- How bright must the stimulating image be?
- Can optogenetic response speed support useful motion?
- How should camera input be transformed for modified retinal cells?

## 5. Cortical Visual Prostheses

Cortical prostheses bypass the eye and retina by stimulating visual cortex.

```text
camera or scene data
-> encoder
-> cortical stimulation
-> phosphenes or traced forms
-> perception
```

V1 is attractive because it has retinotopic organization, but retinotopy is not
a flat pixel map. Electrical stimulation can evoke phosphenes; dynamic
stimulation has been studied as a way to produce recognizable forms.

### Research Anchors

- Electrical stimulation of visual cortex.
- Dynamic cortical stimulation producing form vision.
- Early feasibility studies of cortical prosthesis systems.

### Expansion Questions

- Should cortical systems draw dots, lines, symbols, or semantic cues?
- How stable are percepts across time and electrode locations?
- Can motion or tracing help the brain bind signals into recognizable forms?
- Can a personal cortical map become a stable user interface?

## 6. Noninvasive Neuromodulation

Magnetic and ultrasound methods are interesting because they can act without an
open implanted electrode array, but their precision and reliability are major
limitations.

```text
external field or acoustic source
-> tissue interaction
-> neural modulation
-> percept or changed processing
```

### TMS

Transcranial magnetic stimulation can evoke visual sensations in some settings
and is used in research on visual cortex excitability. Its targeting is coarse
relative to implanted electrodes, so it should not be treated as a practical
image-writing channel.

### Focused Ultrasound

Focused ultrasound can modulate neural tissue and has been studied in relation
to visual cortex. It may be more focusable than broad magnetic stimulation, but
it still faces safety, mechanism, targeting, and repeatability questions.

### Expansion Questions

- Are these methods better for modulation or cueing than for image formation?
- Can noninvasive methods provide useful binary or low-symbol cues?
- How do safety limits constrain bandwidth?
- Can a wearable system combine noninvasive modulation with ordinary sensory
  cues?

## 7. Sensory Substitution

Sensory substitution avoids the hardest neural-writing problem by translating
visual information into another sense.

```text
camera
-> processor
-> sound or touch pattern
-> training
-> learned spatial interpretation
```

This does not recreate normal sight, but it can create useful perception-like
function through learning and brain plasticity.

### Research Anchors

- Tactile vision substitution systems.
- Tongue-based and forehead-based tactile devices.
- Audio-based visual substitution.
- Training studies in blind and sighted users.

### Expansion Questions

- Which visual features are easiest to learn through touch or sound?
- Can semantic AI labels reduce training burden?
- Can tactile cues handle depth and motion better than object identity?
- What does "seeing" mean when interpretation comes through another sense?

## 8. AI, Event-Based, And Semantic Encoding

Modern sensors and AI can change the problem. Instead of asking the human
interface to carry a full image, the front end can reduce the world into useful
signals.

```text
camera or sensor suite
-> AI perception
-> compressed cue set
-> visual, tactile, audio, or neural interface
```

### Useful Compression Targets

- Obstacles
- Doorways
- Stairs
- Faces
- Text blocks
- Motion vectors
- Collision risk
- Reachable objects
- Confidence and uncertainty

### Expansion Questions

- Can an artificial visual system be task-first instead of image-first?
- How should errors and uncertainty be shown to the user?
- Can event cameras provide better motion-first information than ordinary
  frame cameras?
- Can a system preserve user agency when AI decides what matters?

## Perception-As-Medium Project Direction

This is the current center of gravity for the project: cut out the middle
medium when it does not help. A conventional display preserves the image until
light reaches the eye. A perception-as-medium system preserves only what the
person can learn to use.

```text
world
-> extracted feature, event, relation, or meaning
-> cue
-> active exploration
-> learned perceptual skill
```

The device does less rendering. The person does more meaningful completion.
That does not mean the system can be vague. It means the engineering problem
changes from "send the whole picture" to "choose the smallest reliable cue that
lets the user perceive, decide, or act."

### Research Anchors

- Sensory substitution and the role of training, action, and tool fluency.
- Sensorimotor accounts of perception.
- Predictive coding and perception as inference from cues and error signals.
- Extended cognition and transparent tools.
- Prosthetic vision work showing that phosphenes are not simple pixels.

### Project Questions

- What middle layers can be removed: screen, pixel grid, frame stream,
  photorealism, single-sense output, or universal mapping?
- Which cue grammars become fluent through training?
- How much active control does the user need for a cue to become perception-like?
- When is a symbol, edge, motion event, or label better than a dim image?
- How should confidence and uncertainty stay visible without overwhelming the
  user?
- Can project prototypes be built with ordinary screens, audio, haptics, and
  paper studies before any medical or neural claim is made?

## 9. Memory-Adjacent Research Frontier

Memory is not a display target. It is a distributed reconstructive process.

```text
experience
-> attention
-> association
-> consolidation
-> later reconstruction
```

The practical direction is voluntary memory support:

- Photos
- Narration
- Spaced review
- Context cues
- Multisensory prompts
- Journaling
- Assistive recall tools

The far-edge branch includes direct memory writing, arbitrary memory insertion,
or remote implantation of visual memories. Those should be handled as open
hypotheses unless the evidence landscape changes dramatically.

## 10. Research-To-Concept Bridge

The strongest encyclopedia entries should follow this bridge:

```text
known science
-> existing limitation
-> conceptual workaround
-> plausible interface
-> scope note
-> open question
```

Example:

```text
cortical phosphenes exist
-> phosphenes are not clean pixels
-> use a phosphene font
-> train stable symbols
-> avoid procedural stimulation guidance
-> ask which symbols are reliable across users
```
