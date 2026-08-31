# 45. Neural CRT

- Status: Frontier
- Interface point: Retina, optic nerve, or visual cortex
- Carrier: Depends on future interface
- Transducer: Retinal, cortical, optical, acoustic, magnetic, or local converter
- Encoding style: Scanned stimulus over time
- Addressing method: Raster, spiral, saccade-linked, or feature-trace scanning
- Expected percept: A temporally built artificial percept
- Related modules: [CRT Baseline](../modules/00-crt-baseline.md), [Creative Engineering](../modules/13-creative-engineering.md)

## Summary

The neural CRT is the central analogy pushed to its frontier form. A CRT scans
an electron beam across phosphor. A neural CRT would scan a controlled stimulus
across a biological or prosthetic target and rely on perception to integrate the
sequence.

## Chain Map

```text
encoded image or cue
-> scanning controller
-> biological/prosthetic target
-> temporal integration
-> perceived pattern
```

## Scanning Patterns

| Pattern | Possible Use |
| --- | --- |
| Raster | Direct CRT analogy; line-by-line update. |
| Spiral | Fovea-first or center-out cueing. |
| Edge trace | Draw object outlines only. |
| Symbol trace | Draw glyphs, arrows, or warning icons. |
| Motion trace | Emphasize movement direction. |
| Attention trace | Scan only the task-relevant region. |

## Expansion Ideas

- Compare raster scanning with shape tracing.
- Use event-based input so only changed regions are scanned.
- Build a software simulator for scanned phosphene fields.
- Design a phosphene font optimized for scanning.
- Use gaze to steer the scan path.

## Research Questions

- What scan speed feels continuous?
- Does temporal tracing improve form recognition?
- Is raster scanning wasteful compared with feature tracing?
- Can the brain learn an artificial scan grammar?

