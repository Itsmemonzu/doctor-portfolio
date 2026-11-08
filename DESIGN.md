---
name: Dr. Amina Rahim, Neurologist
description: A one-page practice portfolio set in a dark reading room, where only the film viewers give off light.
colors:
  room: "#0a0c0d"
  room-line: "#232a2e"
  room-line-2: "#303a3f"
  on-room: "#e4eaec"
  on-room-2: "#94a2a7"
  on-room-3: "#7a888d"
  glass-off: "#161b1e"
  bezel-top: "#1f2528"
  bezel-bottom: "#141819"
  opal: "#e3eaeb"
  opal-hi: "#f4f8f8"
  opal-lo: "#c9d4d6"
  clip-steel: "#5d686c"
  film-black: "#070809"
  film-blue-base: "rgba(118, 160, 178, .55)"
  ink: "#0f1416"
  ink-2: "#44515a"
  grease: "#f2cf3a"
typography:
  display:
    fontFamily: "Host Grotesk, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(3.6rem, 7.4vw, 8.5rem)"
    fontWeight: 300
    lineHeight: 0.88
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Host Grotesk, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(2.6rem, 5.4vw, 5rem)"
    fontWeight: 300
    lineHeight: 0.95
    letterSpacing: "-0.04em"
  statement:
    fontFamily: "Host Grotesk, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(1.6rem, 3vw, 2.7rem)"
    fontWeight: 300
    lineHeight: 1.2
    letterSpacing: "-0.028em"
  title:
    fontFamily: "Host Grotesk, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(1.6rem, 2.4vw, 2.2rem)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "-0.03em"
  lead:
    fontFamily: "Host Grotesk, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "clamp(1.1rem, 1.4vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.42
    letterSpacing: "-0.012em"
  body:
    fontFamily: "Host Grotesk, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "-0.006em"
  label:
    fontFamily: "Host Grotesk, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "-0.01em"
  small:
    fontFamily: "Host Grotesk, Helvetica Neue, Helvetica, Arial, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.6
  edge-print:
    fontFamily: "Azeret Mono, ui-monospace, Menlo, monospace"
    fontSize: "0.625rem"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.08em"
rounded:
  hairline: "1px"
  pin: "2px"
  film: "3px"
  panel: "4px"
  bezel: "10px"
  dot: "50%"
spacing:
  bezel: "11px"
  bezel-narrow: "8px"
  gutter: "clamp(1rem, 3.2vw, 3rem)"
  column-gap: "clamp(1.5rem, 4vw, 4rem)"
  section: "clamp(5rem, 11vw, 10rem)"
  title-gap: "clamp(2rem, 4vw, 3.5rem)"
components:
  button-lit:
    backgroundColor: "{colors.opal}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.panel}"
    padding: "0 1.4rem"
    height: "3.25rem"
  button-lit-hover:
    backgroundColor: "{colors.opal-hi}"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.on-room}"
    typography: "{typography.label}"
    rounded: "{rounded.panel}"
    padding: "0 1.4rem"
    height: "3.25rem"
  bezel:
    backgroundColor: "{colors.bezel-bottom}"
    rounded: "{rounded.bezel}"
    padding: "{spacing.bezel}"
  opal-viewer:
    backgroundColor: "{colors.opal}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "clamp(1.75rem, 3.5vw, 3rem)"
  office-viewer-off:
    backgroundColor: "{colors.glass-off}"
    textColor: "{colors.on-room}"
    rounded: "{rounded.panel}"
    padding: "clamp(1.5rem, 3vw, 2.5rem)"
  office-viewer-lit:
    backgroundColor: "{colors.opal}"
    textColor: "{colors.ink}"
    rounded: "{rounded.panel}"
    padding: "clamp(1.5rem, 3vw, 2.5rem)"
  film-plate-dark:
    backgroundColor: "{colors.film-black}"
    rounded: "{rounded.film}"
    padding: "10px 10px 24px"
  film-plate-portrait:
    backgroundColor: "{colors.film-blue-base}"
    rounded: "{rounded.film}"
    padding: "14px 14px 26px"
  film-clip:
    backgroundColor: "{colors.clip-steel}"
    width: "44px"
    height: "20px"
  reader-tab:
    backgroundColor: "transparent"
    textColor: "{colors.on-room-3}"
    padding: "1.05rem .9rem 1.05rem 0"
  reader-tab-selected:
    textColor: "{colors.on-room}"
    padding: "1.05rem .9rem 1.05rem .9rem"
  find-row:
    backgroundColor: "transparent"
    textColor: "{colors.on-room}"
    rounded: "{rounded.panel}"
    padding: "clamp(1rem, 2vw, 1.5rem) clamp(.75rem, 1.5vw, 1.25rem)"
  find-row-lit:
    backgroundColor: "{colors.opal}"
    textColor: "{colors.ink}"
  status-dot-open:
    backgroundColor: "{colors.grease}"
    rounded: "{rounded.dot}"
    size: "0.55rem"
---

# Design System: Dr. Amina Rahim, Neurologist

## Overview

**Creative North Star: "The Reading Room"**

The whole page is a darkened consultation room. Nothing on it is bright except the hardware that is meant to be: opal lightbox panels in steel bezels, with faint fluorescent tube banding showing through the diffuser. Film plates are clipped to those panels with flat steel clips and carry monospace edge printing. Everything else (headings, lists, the training strip) sits on the dark room in pale grey type and hairline rules. Light is how this world signals what matters. A viewer is lit because it holds evidence, because an office is open right now, or because a row is under the pointer.

Type is one sans in two working weights: Light 300 for anything at display scale, Regular 400 for reading, Medium 500 only for button labels and small inline labels. Display tracking is tight (-0.04em). The mono face shows up only as edge printing on film. Grease-pencil yellow is the single chromatic accent. It never decorates. It marks state: availability, the selected condition, an open office, keyboard focus, text selection, and the viewer's power lamp.

Density is calm and generous. Sections are separated by a large fluid gap rather than dividers, and content lives in asymmetric grids that put the lit viewer on the wider side.

**Key Characteristics:**
- Dark room ground; light comes only from viewers and lit rows.
- Opal-in-bezel hardware is the one container idiom.
- Raster film plates (toned photography and scans) with mono edge printing, held by flat clips.
- One sans, Light at scale, tight negative tracking.
- Yellow grease pencil is a state signal, never ornament.
- Hairline rules (1px) in two room-line greys carry the structure.

## Colors

A near-black, slightly blue-green room with cool opal light and a single warm yellow for state.

### Primary
- **Opal Light** (opal, with opal-hi for the hot centre and opal-lo for the falloff): the lit diffuser surface of every viewer, the lit button, and the lit Find-me row. It is the brightest surface in the system and means "lit".

### Secondary
- **Grease Pencil Yellow** (grease): state only. The hand-drawn loop around "Accepting new patients", the selected reader tab's arrow (and its underline on mobile), the open-office status dot with a 3px 35% halo, the focus ring, `::selection`, and the bezel's power lamp.

### Neutral
- **Reading Room Black** (room): page ground, plus `theme-color` and the scrollbar track.
- **Room Line** (room-line): 1px rules between list rows (reader, writing, find).
- **Room Line Raised** (room-line-2): outline buttons, the clock divider, the training strip's film-edge ticks, and the scrollbar thumb.
- **Pale Room Text** (on-room): primary text on the dark room.
- **Room Text Secondary** (on-room-2): nav, lead copy, handles, venues, socials.
- **Room Text Tertiary** (on-room-3): dimmed statement clause, unselected tabs, clock, registration line, colophon.
- **Switched-Off Glass** (glass-off): the dark diffuser of a closed office viewer. Its radial centre is #1a2023.
- **Bezel Steel** (bezel-top to bezel-bottom): the 180-degree gradient of viewer bezels.
- **Clip Steel** (clip-steel): flat film clips.
- **Film Black** (film-black) and **Blue-Base Film** (film-blue-base): plate surrounds for scans and for the portrait.
- **Viewer Ink** (ink) and **Viewer Ink Secondary** (ink-2): text on lit opal.

### Named Rules
**The Grease Is State Rule.** Yellow appears only where something is true right now: available, selected, open, focused, powered. If removing the yellow would lose no information, it does not belong there.

**The Lit Means Opal Rule.** A surface turns opal only when it is a viewer, or when it lights up in response to state or interaction. Plain content never sits on a light card.

## Typography

**Display Font:** Host Grotesk (with Helvetica Neue, Helvetica, Arial)
**Body Font:** Host Grotesk
**Label/Mono Font:** Azeret Mono, for film edge printing only

**Character:** A single humanist grotesk carries everything. Light weight at large sizes gives the quiet, single-weight look. Tight tracking keeps headlines dense, and the mono edge printing reads as something stamped on the film, not written in the interface.

### Hierarchy
- **Display** (300, clamp 3.6–8.5rem, 0.88): the name in the hero only. It is set on two lines, with the second line indented 1.15em. On phones it is clamp(3rem, 15.5vw, 4.4rem).
- **Headline** (300, clamp 2.6–5rem, 0.95): section titles. The closing title steps up to clamp(3.2rem, 7vw, 6rem) at 0.9.
- **Statement** (300, clamp 1.6–2.7rem, 1.2): one large paragraph per section at most, max 26em, with an optional dimmed trailing clause in on-room-3.
- **Title** (400, clamp 1.6–2.2rem, 1.05): heading inside a lit viewer. Office names and Find-me network names use Light 300 at larger clamps (up to 3.2rem) with -0.035 to -0.04em tracking.
- **Lead** (400, clamp 1.1–1.3rem, 1.42): the role line under the name, max 25em.
- **Body** (400, 1.0625rem, 1.6): reading copy. Inside viewers it is ink-2 at 1.02rem/1.55, max 36–38ch.
- **Label** (500, 1rem, 1): button labels. Medium 500 is also used for small inline labels such as "First visit".
- **Small** (400, 0.85–0.95rem): nav, socials, venues, colophon, transit.
- **Edge print** (Azeret Mono 400, 0.625rem, +0.08em, uppercase content): film edge printing only.

### Named Rules
**The One Voice Rule.** One sans family. Weight and size create the hierarchy; no second display face.

**The Mono Is Film Rule.** Azeret Mono is printed on film plates and appears nowhere else.

**The Tabular Facts Rule.** Clock, phone numbers, hours, years and registration numbers use `font-variant-numeric: tabular-nums`.

## Layout

A full-bleed page with a fluid side gutter (gutter) and a large fluid gap between sections (section). There is no max-width container. Grids are asymmetric and built on fr ratios: the hero is 5fr text to 7fr viewer, the case reader is 4fr list to 8fr viewer, offices are two equal columns, training is four columns, and Find-me rows are 4fr / 7fr / auto. Column gaps use the column-gap clamp throughout.

The hero is a full viewport height (100svh). Text is bottom-aligned in the left column and the viewer fills the right column at full height. Section titles sit flush left. The statement paragraph is pushed right with `margin-left: auto` and a fluid left inset.

At 960px or narrower, every grid collapses to one column: the hero viewer moves above the text at min(52svh, 40rem), section nav links hide, training goes to two columns, and Find-me rows become name over handle with the arrow on the right. At 520px or narrower, the case-reader list becomes a horizontally scrolling tab row, training goes to one column, hero buttons stretch to share the row, and the inline phone number in the call button hides.

## Elevation & Depth

Depth here is physical, not decorative: viewers are lit boxes in a dark room. A bezel is lifted by a 1px inner top highlight, a tight contact shadow, and a broad cool glow (the glow token) that reads as light spilling from the panel. The opal surface has inner shading so it falls off toward the edges. Film plates cast soft, low shadows on the opal. Rows on the dark room are flat until they light up. A fixed fractal-noise grain at 7% overlay sits over the whole room.

### Shadow Vocabulary
- **Viewer glow** (`box-shadow: 0 40px 120px -40px rgba(196, 222, 232, .32)`): light spill under a lit viewer. Closed office viewers drop it.
- **Bezel body** (`box-shadow: inset 0 1px 0 rgba(255,255,255,.06), 0 2px 6px rgba(0,0,0,.6)`): every bezel, lit or not.
- **Opal falloff** (`box-shadow: inset 0 0 0 1px rgba(0,0,0,.3), inset 0 0 70px rgba(120,145,152,.45)`): lit diffuser vignette.
- **Plate on glass** (`box-shadow: 0 18px 30px -18px rgba(0,0,0,.5–.6)`): film resting on opal.
- **Clip** (`box-shadow: 0 2px 3px rgba(0,0,0,.35)`): film clips.
- **Lit lift** (`box-shadow: 0 10px 24px -14px rgba(0,0,0,.8)` for rows, `0 6px 14px -8px rgba(0,0,0,.7)` for the lit button): soft lift under an opal surface on the dark room.

### Named Rules
**The Light Has A Source Rule.** Glow appears only under a lit viewer. When a viewer switches off, its glow goes with it.

## Shapes

Corners are small and mechanical: 10px on bezels, 4px on opal panels, buttons and lit rows, 3px on film plates (1px on the image inside), and 2px on pins and the lamp. Film clips are flat tabs with a squared top and slightly rounded bottom (2px 2px 5px 5px), centred and overhanging the plate's top edge by 13px. Film plates leave a deeper margin at the bottom for edge printing, and are rotated slightly (+1.2deg for the hero scan, -0.8deg for the reader film). Structure on the dark room is 1px hairlines. The training strip's top rule carries 1px ticks every 24px, like a film edge. Circles are used only for the status dot.

## Components

### Buttons
Solid, quiet and squared, like switches on a panel.
- **Shape:** gently squared (panel radius), 3.25rem tall, 1.4rem side padding, icon gap 0.6rem.
- **Lit (primary):** opal fill, ink text, lit-lift shadow. An inline tabular phone number sits after a 1px ink divider in ink-2.
- **Hover / Active:** lit brightens to opal-hi. Every button presses down 1px when active. Transitions run 0.25s on the shared easing.
- **Line (secondary):** transparent with a 1px inset ring in room-line-2. On hover the ring lifts to on-room-2.

### Viewer (bezel and opal)
The signature container. A steel bezel (11px padding, 8px on mobile) holds an opal diffuser with vertical tube banding: a repeating 90-degree gradient whose white bands peak at 50% every 25%, over a radial opal-hi to opal-lo falloff. Content on the opal uses ink. On load, the hero viewer switches on with a two-beat fluorescent stutter (brightness keyframes over 1.25s), and the room-light spill behind it stutters in step.

### Film Plate and Clip
A raster image in a plate. Dark plates (film-black, 10px sides and 24px bottom) hold scans. The portrait plate is blue-base film (14px sides and 26px bottom) with a 1px inset tint ring. Edge printing sits in the bottom margin: the edge-print style at 55% pale tint on dark plates, and dark teal at 70% on the blue base. Each plate hangs from one clip. The toning is in the image itself, not added with CSS filters.

### Case Reader Tabs
A vertical tablist next to a lit viewer. Rows are separated by room-line hairlines and use on-room-3 text. The selected tab moves to on-room, indents 0.9rem, and shows a grease-yellow arrow that slides in from -6px. On mobile it becomes a horizontal scrolling row with no arrows, and the selected tab gets a 2px grease underline. Changing tabs swaps the film and text with a 0.6s "develop" fade from a 3px blur, staggered by 0.05s.

### Office Viewer (off / lit)
A bezel and opal card that lights up only while that office is open (the open state is computed against New York time).
- **Off:** switched-off glass with the tube banding still faintly visible (4.5% white), a dark inner vignette, on-room text, no glow, and a status ring drawn as a 1.5px currentColor outline.
- **Lit:** full opal, ink text, viewer glow restored, and a solid grease status dot with a 3px 35% grease halo.
- Inside: Light 300 office name, address at 78% opacity, a tabular hours table with row headers at 65%, links pushed to the bottom, and transit at 60%.

### Find Rows
Full-width contact rows between room-line hairlines: Light network name, secondary handle, and an arrow. On hover, focus-visible or active, the row lights to opal with ink text and a soft lit lift, the handle and arrow shift to ink-2, the arrow nudges 3px up and to the right, and the adjacent hairlines disappear. Transitions run 0.35s on the shared easing. The row bleeds its padding into the gutter with a negative margin, so the text stays aligned.

### Navigation
A top bar inside the hero. On the left, the practice line with a live tabular clock behind a 1px divider. On the right, small on-room-2 section links that brighten to on-room on hover. The links are hidden at 960px or narrower.

## Do's and Don'ts

### Do:
- **Do** keep the whole page on the room ground and get light only from viewers or lit-on-interaction rows.
- **Do** put any new evidence or media surface in the bezel and opal viewer, with film plates hung by a single clip.
- **Do** use grease yellow only to mark live state (available, selected, open, focus, powered).
- **Do** set display-scale type in Host Grotesk Light 300 with -0.04em tracking.
- **Do** use 1px room-line hairlines for structure, and tabular numerals for facts and times.
- **Do** honour `prefers-reduced-motion`: the switch-on, draw and develop animations all drop to static.

### Don't:
- **Don't** put ordinary content on light cards; opal means lit.
- **Don't** use grease yellow as a fill, a background block, or an ornament.
- **Don't** use Azeret Mono outside film edge printing.
- **Don't** fake film toning with CSS filters; plates are toned raster images.
- **Don't** add glow under a viewer that is switched off.
- **Don't** use the look this world rejects: teal gradients, stock stethoscope imagery, icon-tile grids.
