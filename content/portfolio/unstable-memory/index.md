---
title: "Unstable Memory"
summary: "A browser-based glitch instrument exploring instability, fragmentation, and audiovisual noise systems."
weight: 0
tags: ["Experimental Tools", "Game Audio", "Glitch Systems"]
featured: true
image: featured.png
---

## Unstable Memory  
*Interactive Glitch Instrument / Installation*

**Unstable Memory** is an interactive audiovisual experiment exploring fragmentation, decay, and the aesthetics of corrupted media. Developed alongside my Touch Designer, p5.js and other creative coding work, it functions as both a **playable sound instrument** and a **visual installation**, designed for fullscreen kiosk mode, exhibition contexts, and mobile interaction.

The project invites users to trigger controlled chaos through touch input, sliders, and audio samples. Sound and image destabilise together, evoking the feeling of glitching signals, broken formats, and unreliable signals.

Originally conceived as a small prototype, Unstable Memory is now in its **third iteration (v0.3)**. It has already been used in exhibition-style contexts and continues to evolve as a platform for experimenting with interactive sound as a form of intervention.

### Project Origins

The project began with an interest in **lost media, corrupted recordings, and the fragility of lost memories**. Drawing inspiration from glitch art, haunted tapes, VHS artefacts, and browser-based synthesis, the early prototypes focused on minimal interaction and degraded playback.

Over time, the system expanded into a fully interactive audiovisual canvas, balancing unpredictability with just enough control to allow moments of eerie clarity to emerge.

### Core Concept

Unstable Memory is intentionally unstable.

Users are encouraged to search for fleeting “sweet spots”, hallucinatory moments where fragments briefly align before dissolving again. The experience sits somewhere between an instrument, a broken machine, and a memory artifact.

### Interaction & Audio System

The interface allows users to blend **two looping audio channels (A and B)** using an XY interaction plane and a control panel. Movement across the screen influences pitch, volume, stereo balance, and glitch intensity in real time.

Although chaotic by design, the system includes fine-tuning controls that allow careful alignment between samples, producing unexpected harmonies, dissonance, and rhythmic drift.

Audio is powered by **p5.sound**, with global effects applied across both channels.

### Key Features

#### Sample Selection
Users can choose from a curated library of sounds, including:
- Environmental recordings
- Musical fragments
- Chiptune elements
- A dedicated **Corrupted Sample**, which triggers glitch artefacts and false error messages

#### XY Plane Interaction
- Vertical movement controls pitch and glitch intensity  
- Horizontal movement affects volume and stereo balance  
- Touch or mouse input drives both sound and visual behaviour

#### Effects Panel
- Reverb  
- Echo / Delay  
- Filter Sweep  
- RGB Pulse distortion  
- Crackle & Pop noise layer  
- Working **Toggle Glitch** control  

A full reset button returns the system to a known state, allowing repeated exploration.

#### Audio Sync Engine
Pitch fine-tuning allows alignment between Sample A and B, despite differing source material. This encourages emergent musical relationships rather than fixed playback.

### Visual Design

The visual layer reacts directly to audio behaviour:

- **Dynamic Glitch Waveforms**  
  Audio-reactive waveforms pulse and distort, driven by pitch, noise, and glitch parameters.

- **VHS / CRT Influences**  
  Optional scanlines, warping, and colour flicker evoke degraded analogue displays.

- **Custom UI Design**  
  Neon sliders, monospace typography, and bold layouts reinforce the broken-machine aesthetic.

### Accessibility & Deployment

- Touchscreen support on Smart Board displays and mobile devices  
- Slider hitboxes were expanded to improve touch accuracy  
- Designed for fullscreen browser kiosk mode, with a downloadable web app Version 0.3 as its current iteration

### Known Issues & Ongoing Development

- Occasional pitch resets when loading new samples (state handling issue)  
- Some background touch interactions persist, partially mitigated  
- Bitcrusher not very responsive

### Thematic Intent

Unstable Memory explores:
- Media decay and data corruption  
- Collective memory and loss  
- Human–machine interaction  
- Glitch as both failure and aesthetic language  

The project sits somewhere between **sound design, experimental music, interaction design, and installation art**, and continues to compliment my wider work in immersive audio and audiovisual systems.

### Prototype Access

A live prototype of **Unstable Memory v0.3** is available to explore here:

https://shedtronic.gumroad.com/l/unstablememory