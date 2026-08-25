# 3DCC™ Hero Film Bible
## FWA / FOTD Production Guide

> **You are not looking at the map.  
> You are inside it.**

This document defines how 3DCC should be presented in motion.

The goal is not to make a futuristic film about 3DCC. The goal is to let the viewer understand 3DCC by experiencing the shift in point of view.

**The product is real. The film must prove it.**

---

## 1. Core proposition

3DCC places the observer at the coordinate origin.

**@ = YOU**

The decisive visual event is not the appearance of the spheres, the grid, or the neon vector.

It is the moment the viewer crosses @ and the coordinate changes from something seen from outside into something experienced from within.

**3DCC is a cognitive reach.**

---

## 2. Production principle

### Real interface first

Any shot that shows the actual product must come from the live Three.js experience.

This includes:

- tapping a sphere
- the neon reach vector
- the sphere response
- entering @
- the internal first-person coordinate view
- TAKE OFF
- the 27-zone field
- labels, axis behavior, and all UI states

AI-generated video must **not** attempt to redraw or simulate the 3DCC interface.

Generative material is permitted only as atmosphere, texture, or transitional material that contains no recognizable product UI.

> **AI is atmosphere, not authorship.**

If an AI-generated shot could be mistaken for the actual product, do not use it.

---

## 3. Visual character

The film should feel:

**dark · quiet · precise · human-centered · spatial · restrained · contemplative**

Avoid conventional sci-fi spectacle.

No hyperspace tunnels. No HUD clutter. No particle storms. No cyberpunk city language. No gratuitous lens flare. No fast camera moves.

The visual hierarchy is:

**observer → space → relationship → object**

not

**effect → spectacle → interface**

---

## 4. 60-second hero film

### 00:00–00:05 — BEFORE THE MAP

Black.

Almost silence.

Text:

> **For centuries, maps have placed us outside the world.**

A faint warm point appears at the centre.

Purpose: establish the conventional point of view before 3DCC changes it.

Production: typography + optional atmospheric AI background.

---

### 00:05–00:10 — THE OBJECT

Live 3DCC exterior view.

The 27-zone field emerges in darkness. The coordinate exists as an object in front of the viewer.

Text:

> **What if the observer became the origin?**

The central @ breathes quietly.

Production: live Three.js capture only.

---

### 00:10–00:15 — @ = YOU

Camera and cursor settle on @.

Text:

> **@ = YOU**

Click.

At the click, sound briefly falls away.

Production: live Three.js capture.

---

### 00:15–00:20 — ENTER

@ expands.

The image becomes white.

The whiteout is not a visual trick; it is the boundary between an external and internal point of view.

Production: live interface transition is primary. Optional AI membrane texture may be composited extremely lightly if needed.

---

### 00:20–00:27 — THE ORIGIN

White recedes.

The viewer is now inside the coordinate.

There is no visible @ marker because the camera itself occupies the origin.

Text:

> **You are the origin.**

Hold long enough for the viewer to feel the spatial reversal.

Production: live Three.js first-person capture only.

---

### 00:27–00:34 — THE COORDINATE

The viewer looks gently through the three axes and the surrounding field.

Text:

> **Three axes.  
> Twenty-seven cognitive zones.**

Axis language may appear briefly:

**Hard ↕ Light**  
**Crisp ↔ Creamy**  
**Dry ↔ Sweet**

Production: live Three.js capture + restrained typography.

---

### 00:34–00:42 — REACH

Select one sphere — preferably Negroni.

A neon vector travels from the observer's seat to the object.

Text:

> **Every perception begins here.**

Then show the selected coordinate / sensory position.

This is the film's second key event after entering @.

Production: live Three.js capture only. Glow may be subtly reinforced in compositing, but the path must remain the real interface path.

---

### 00:42–00:51 — THE FIELD

Reveal nearby objects and spatial relationships.

Text, one beat at a time:

> **Not a list.**

> **A field.**

> **A space of relationships.**

Optional final implication:

**WINE · SAKE · FOOD · FRAGRANCE · MUSIC · …**

Then:

> **Cocktails are only the beginning.**

These categories are conceptual future domains, not claims of completed implementations.

---

### 00:51–00:56 — TAKE OFF

The user selects:

**↑ TAKE OFF**

Reverse transition through white.

The coordinate becomes external again.

Production: live Three.js capture.

---

### 00:56–01:00 — THE PROPOSITION

Near-black.

A small @ remains.

Text:

> **You are not looking at the map.  
> You are inside it.**

Then:

# **3DCC™**

*The Three-Dimensional Cognitive Coordinate*

> **A cognitive reach.**

Fade to black.

---

## 5. AI atmosphere prompt library

### Global rule

**Never generate the product.**

Do not generate the 3DCC grid, interface, @ transition, spheres as product objects, neon selection behavior, internal coordinate, or TAKE OFF sequence.

Recommended settings: 16:9 for the master film; create separate vertical variants only when needed. 5–8 seconds per atmospheric shot. Low-to-medium motion. Fixed seed where available. Grade everything back into the live interface palette.

---

### Prompt 01 — Deep-space darkness

```text
A vast, near-black void in deep space. Extremely fine particles of dust drift slowly. A single faint warm-gold mote of light rests at the exact centre, softly pulsing. Volumetric darkness, subtle depth haze. Cinematic, minimal, contemplative. Very slow push-in. Shallow depth of field, subtle 24fps film grain, deep blacks.
Avoid: text, logos, UI, cubes, lens flare storms, fast motion, cartoon, oversaturation.
```

Use: cold open background.

---

### Prompt 02 — Glass macro beauty

```text
Extreme macro of a single translucent glass marble on pure black. A pearlescent thin-film iridescence shifts across its surface as the view slowly orbits. One soft studio key light creates a crisp specular highlight and a luminous coloured rim. Wet, jewel-like, high-craft. Slow rotation, no background clutter.
Avoid: multiple objects, hands, text, reflections of a room, plastic look, harsh light, fast spin.
```

Use: material / texture insert only. Never imply this is the actual 3DCC sphere rendering.

---

### Prompt 03 — Iridescent shimmer

```text
Abstract close-up of an iridescent oil-film on black water, gentle ripples sending waves of shifting spectral colour — teal, magenta, gold — across the frame. Slow, hypnotic, seamless. Designed as a subtle transition texture. Dark base, luminous highlights.
Avoid: text, objects, faces, logos, strobing, rapid colour flashing.
```

Use: very subtle transition overlay.

---

### Prompt 04 — Passing through light

```text
First-person camera drifting toward a blooming point of pure white light in darkness, the light softly expanding to fill the frame, then receding. Smooth, weightless, a sense of passing through a membrane. Warm-to-white gradient, no hard flash.
Avoid: text, tunnels of logos, sci-fi HUD, harsh strobe, fast speed lines.
```

Use: optional support texture for X cutdowns. The live whiteout remains the master transition.

---

### Prompt 05 — Deep atmospheric chamber

```text
Slow-moving volumetric fog in a dark chamber, faint god rays of dim warm light passing through, motes suspended and drifting. Meditative, spacious, almost still. Low, heavy atmosphere. Extremely slow drift.
Avoid: text, characters, buildings, bright colours, fast motion.
```

Use: closing ambience or black-space transition.

---

### Prompt 06 — Points appearing in darkness

```text
In total darkness, a scattering of small jewel-coloured points of light quietly ignite one by one at different depths, like a constellation forming. Soft glow, gentle bloom, calm rhythm. Abstract, elegant, dark background.
Avoid: text, grids, cubes, connecting lines, UI, fast appearance, chaotic motion.
```

Use: teaser only, immediately followed by the real product build. Do not allow the abstract points to be mistaken for the real sphere field.

---

### Prompt 07 — Human breath

```text
A completely dark screen. Almost imperceptible movement, as if the camera itself is breathing. Tiny suspended dust particles drift in warm darkness. A distant point of soft gold light brightens with each breath. Slow inhale, slow exhale. Quiet anticipation. Human presence without showing a human body. Minimal cinematic realism.
Avoid: faces, eyes, silhouettes, heartbeat graphics, text, sci-fi interface.
```

Use: immediately before entering @, if the cut needs more human presence.

---

### Prompt 08 — Memory of light

```text
Very faint trails of warm gold and soft cyan light suspended in black space, slowly fading as if someone reached toward invisible points moments ago. Spatial depth, elegant persistence, almost imperceptible motion. Calm, meditative.
Avoid: lasers, explosions, particles everywhere, text, UI.
```

Use: optional low-opacity overlay after the live neon reach.

---

### Prompt 09 — Perception field

```text
A dark infinite field where subtle luminous points appear suspended in three-dimensional depth. No grid. No connecting lines. No recognizable objects. Distances between lights create an invisible spatial structure that the viewer gradually begins to perceive. Calm, elegant, almost scientific.
Avoid: constellation drawings, cubes, HUD, text, planets.
```

Use: abstract conceptual bridge only. The actual 3DCC field must remain live capture.

---

### Prompt 10 — Return to self

```text
Pure white slowly dissolves into near-black darkness. The central warm point of light returns, now smaller and quieter than before. Dust continues drifting. The viewer feels they have returned from somewhere rather than arrived somewhere.
Avoid: tunnel effects, dramatic flash, text, portals.
```

Use: optional atmospheric layer after TAKE OFF.

---

## 6. Sound design bible

The film should not behave like a trailer with a conventional score.

The space itself should appear to produce the sound.

| Time | Sound intention |
| --- | --- |
| 00–05 | Almost silence. Deep room tone. A distant low-frequency drone. |
| 05–12 | Very soft crystalline harmonics emerge with the field. |
| 12–15 | Reduce sound toward silence as the cursor reaches @. |
| @ click | Brief silence. The click becomes a perceptual boundary. |
| 15–20 | Air / soft broadband rise into white, never a harsh whoosh. |
| 20–34 | Large, sparse spatial ambience. Vast but quiet. |
| 34–42 | Reach vector produces one pure, short tonal event. |
| 42–51 | Residual harmonic tail; no rhythmic music. |
| 51–56 | TAKE OFF produces a restrained ascending return tone. |
| 56–60 | Collapse gradually back into silence. |

The user should feel scale through space and silence, not volume.

---

## 7. Color bible

The master film should be graded around four anchors:

| Function | Color |
| --- | --- |
| Background black | `#050506` |
| Primary warm gold | `#D7A441` |
| Neon pink | `#FF5DA8` |
| Neon cyan | `#43D9FF` |

These are grading anchors, not a requirement to recolor the actual live product away from its authentic rendering.

Live capture has priority.

Keep highlights below hard white except during the deliberate whiteout transition.

---

## 8. Typography

Typography should feel editorial rather than technological.

Short statements only.

No explanatory paragraphs in the hero film.

Preferred key lines:

> **What if the observer became the origin?**

> **@ = YOU**

> **You are the origin.**

> **Every perception begins here.**

> **Not a list. A field.**

> **You are not looking at the map. You are inside it.**

> **A cognitive reach.**

Typography must never compete with the 3D space.

---

## 9. X / social cutdown — 15–20 seconds

The social cut is a hook, not an explanation.

Recommended sequence:

**00–03** — @ in darkness  
**03–07** — axes form  
**07–11** — field emerges  
**11–14** — click @ / white  
**14–17** — internal view or reach  
**17–20** — `3DCC™ / A cognitive reach.`

If the internal-view footage is not yet ready, use the authentic startup build and finish on:

> **@ = YOU**

> **3DCC™**

> **A cognitive reach.**

Never replace missing product footage with generated pseudo-3DCC imagery.

---

## 10. Capture requirements

Capture the real browser experience cleanly and at the highest practical resolution.

Master preference: **16:9, 1920×1080 or higher**.

Capture separate clean takes for:

- startup from @ to full field
- exterior slow rotation
- pointer approaching @
- @ click and live whiteout
- first internal reveal
- internal look-around
- Negroni selection / reach
- readout response
- TAKE OFF
- external return

Record longer handles before and after each action. Do not try to perform the entire hero film as one perfect live take.

---

## 11. Compositing rules

AI texture may be composited with Screen / Add / Lighten-style blending at low opacity where appropriate.

The effect should be felt before it is consciously noticed.

If a generated layer changes the identity, geometry, number, placement, or behavior of product elements, remove it.

If a generated layer makes the product look more spectacular but less truthful, remove it.

When in doubt, use the live interface alone.

---

## 12. FOTD rules

1. **Never explain before the viewer feels it.**
2. **The first emotional event is entering @.**
3. **Every AI shot must disappear into the real interface.**
4. **Silence is part of the interface.**
5. **AI is atmosphere, not authorship.**
6. **The observer is the protagonist.**
7. **Do not turn 3DCC into generic sci-fi.**
8. **Do not fake functionality for the film.**
9. **The live browser experience must be at least as compelling as the hero film.**
10. **If a shot does not strengthen the idea of the observer as origin, remove it.**

---

## 13. Final acceptance test

Before export, watch the film once with no sound and once with no text.

With no sound, the point-of-view reversal should still be understandable.

With no text, entering @ and reaching toward a sphere should still communicate the core idea.

Then ask one question:

> **Does the viewer understand that @ is not a marker they are looking at, but a position they can become?**

If yes, the film is doing its job.

---

## 14. Deliverables

Master hero film: **60 sec / 16:9**  
FWA submission cut: **60 sec / 16:9**  
X hero cut: **15–20 sec**  
Silent autoplay variant: **15–20 sec**  
Poster frame / thumbnail: **@ + field, minimal typography**

---

## 15. Working status

The core 3DCC browser experience is the source of truth.

AI atmosphere generation is optional and secondary.

If the film can be completed convincingly with live footage, typography, grading, and sound alone, that is preferable to adding generated imagery simply because it is available.

---

# **3DCC™**
## *The Three-Dimensional Cognitive Coordinate*

**The observer remains the origin.**

### A cognitive reach.
