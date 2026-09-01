---
name: Chloe Rong Portfolio
description: An airy digital sketchbook where flat paper collage and purposeful interaction frame Chloe's work.
colors:
  browser-white: "#FCFCFA"
  soft-carbon: "#242528"
  lottery-pink: "#FF4FA3"
  screen-blue: "#1B82FF"
  portal-cyan: "#46D9E8"
  prize-lime: "#D6EE45"
  powder-blue: "color-mix(in srgb, #1B82FF 34%, #FCFCFA)"
  warm-tape: "color-mix(in srgb, #FCFCFA 76%, #242528)"
  muted-text: "color-mix(in srgb, #242528 72%, #FCFCFA)"
  hairline: "color-mix(in srgb, #242528 24%, #FCFCFA)"
typography:
  display:
    fontFamily: "Gabarito, system-ui, sans-serif"
    fontSize: "clamp(3rem, 6vw, 5.25rem)"
    fontWeight: 850
    lineHeight: 0.9
    letterSpacing: "-0.035em"
  section:
    fontFamily: "Gabarito, system-ui, sans-serif"
    fontSize: "clamp(2.75rem, 7vw, 5.75rem)"
    fontWeight: 850
    lineHeight: 0.9
    letterSpacing: "-0.035em"
  title:
    fontFamily: "Gabarito, system-ui, sans-serif"
    fontSize: "2rem"
    fontWeight: 750
    lineHeight: 1.18
    letterSpacing: "-0.035em"
  body:
    fontFamily: "Courier Prime, Courier New, monospace"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Courier Prime, Courier New, monospace"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.18
rounded:
  none: "0"
  sm: "0.25rem"
  md: "0.5rem"
spacing:
  2xs: "0.25rem"
  xs: "0.5rem"
  sm: "0.75rem"
  md: "1rem"
  lg: "1.5rem"
  xl: "3rem"
  2xl: "6rem"
  3xl: "8rem"
  section: "clamp(5rem, 12vw, 10rem)"
components:
  navigation:
    backgroundColor: "{colors.browser-white}"
    textColor: "{colors.soft-carbon}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0"
  identity-paper:
    backgroundColor: "{colors.lottery-pink}"
    textColor: "{colors.soft-carbon}"
    typography: "{typography.display}"
    rounded: "{rounded.none}"
    padding: "3rem"
  work-paper-product:
    backgroundColor: "{colors.prize-lime}"
    textColor: "{colors.soft-carbon}"
    typography: "{typography.title}"
    rounded: "{rounded.none}"
    padding: "3rem 1.5rem"
  work-paper-games:
    backgroundColor: "{colors.portal-cyan}"
    textColor: "{colors.soft-carbon}"
    typography: "{typography.title}"
    rounded: "{rounded.none}"
    padding: "3rem 1.5rem"
  work-paper-art:
    backgroundColor: "{colors.powder-blue}"
    textColor: "{colors.soft-carbon}"
    typography: "{typography.title}"
    rounded: "{rounded.none}"
    padding: "3rem 1.5rem"
  project-slip:
    backgroundColor: "{colors.browser-white}"
    textColor: "{colors.soft-carbon}"
    typography: "{typography.label}"
    rounded: "{rounded.none}"
    padding: "0.75rem 1rem"
  project-note:
    backgroundColor: "{colors.lottery-pink}"
    textColor: "{colors.soft-carbon}"
    typography: "{typography.body}"
    rounded: "{rounded.none}"
    padding: "1.5rem"
  footer-note:
    backgroundColor: "{colors.lottery-pink}"
    textColor: "{colors.soft-carbon}"
    typography: "{typography.section}"
    rounded: "{rounded.none}"
    padding: "6rem"
---

# Design System: Chloe Rong Portfolio

## Overview

**Creative North Star: "The Interactive Digital Sketchbook"**

The portfolio feels like a bright browser canvas where Chloe has arranged paper studies, project fragments, handwritten-interface notes, and small ASCII marks. It is airy and object-driven rather than dense: personality concentrates in a few overlapping clusters while Browser White preserves room around them.

The system combines playful direct manipulation with editorial restraint. Personal and navigation surfaces can behave like movable collage; project evidence remains legible, structured, and dominant. Every interaction requires deliberate input, and every destination remains usable without moving an object.

**Key Characteristics:**

- Flat digital papers with crisp cut edges and no printed grain.
- Asymmetric composition with generous negative space and controlled overlap.
- Gabarito display statements paired with Courier Prime information and notes.
- Saturated accent fields used as objects, not scattered decoration.
- Purposeful drag, keyboard, hover, and focus states without ambient animation.

## Colors

Browser White and Soft Carbon form the neutral field. Lottery Pink leads expressive identity moments; Screen Blue, Portal Cyan, Prize Lime, and Powder Blue distinguish work categories and supporting notes. Warm Tape, Muted Text, and Hairline are quieter structural roles.

**The Flat Field Rule.** Accent colors appear as decisive, solid paper surfaces or compact labels; do not turn them into gradients, glows, or decorative noise.

**The Carbon Focus Rule.** Global links use Screen Blue focus, while focus on colored papers switches to Soft Carbon for reliable contrast.

## Typography

**Display Font:** Gabarito with a system sans-serif fallback

**Body and Label Font:** Courier Prime with Courier New and monospace fallbacks

Gabarito carries names, major headings, paper titles, and project titles with compact, confident weight. Courier Prime carries slogans, navigation, metadata, descriptions, work indexes, and interaction instructions, giving the digital collage a note-like editorial voice.

- **Display:** Extra-bold, tightly tracked, and nearly flat-leading for the identity statement.
- **Section:** Extra-bold and responsive for major editorial transitions.
- **Title:** Bold display type for project and category names.
- **Body:** Regular Courier Prime with normal reading rhythm and a maximum reading measure of 72 characters where long copy appears.
- **Label:** Small Courier Prime, frequently uppercase for metadata and instructions.

**The Two-Voice Rule.** Gabarito makes the statement; Courier Prime explains, labels, and guides.

## Layout

The shared shell centers content within the page maximum, while the collage homepage can expand to the wider hero maximum. The spacing scale progresses from compact quarter-rem adjustments to large six- and eight-rem separations; section rhythm uses a responsive five-to-ten-rem interval.

Desktop uses asymmetric grids, rotated papers, overlap, and movable coordinates. Movable papers remain bounded to the homepage hero and Escape resets all three at once. Tablet tightens the two-column composition. Mobile changes the broader page to a one-column reading flow while retaining the overlapping three-paper stack inside its dedicated hero stage.

**The Concentrated Cluster Rule.** Keep large areas quiet, then group related papers, captions, or images closely enough to read as one authored object.

## Elevation & Depth

The system is flat in color but physically layered through two offset, softly blurred shadows. Resting paper uses the standard paper shadow; hover, keyboard focus, and active dragging use the larger hover shadow. Media zoom is restrained and does not add a second elevation language.

**The One Shadow Rule.** A paper receives one soft offset shadow and no simultaneous border, glow, or glass treatment.

## Shapes

Signature papers, slips, media frames, navigation bars, and footer notes use square corners. Small and medium radius tokens remain available for secondary system utilities, but the calibrated homepage's collage components use the zero-radius token. Rotation, overlap, tape, and clean rectangular silhouettes provide character instead of rounded-card styling.

## Components

### Shared Navigation

A white, hairline-separated bar pairs the uppercase Gabarito name with compact Courier Prime links. The current page receives a Lottery Pink underline; hover uses the darker Screen Blue role; keyboard focus uses the global focus ring.

### Identity Paper

The hero identity is a slightly rotated Lottery Pink sheet with translucent tape, an extra-bold uppercase name, a thin Carbon rule, and a Courier Prime slogan. It uses the standard paper shadow and square edges.

### Movable Work Paper

Product, Games, and Graphics + Art use Prize Lime, Portal Cyan, and Powder Blue respectively. Each paper carries a Gabarito category title and white project slips, accepts pointer drag and arrow keys, stays bounded within the hero on desktop, and joins the global Escape reset.

### Project Slip and Work Index

Project slips are white, compact, slightly rotated Courier Prime labels layered over colored papers. The work index repeats destinations in a structured, hairline-separated grid so navigation never depends on dragging.

### Collage Media Frame and Project Note

Project media sits on a flat accent backing with one paper shadow and a restrained image-scale hover. Separate colored notes overlap or trail the media, pairing metadata, titles, and compact project writing.

### Shared Footer

The shared footer closes with a large rotated Lottery Pink note, translucent tape, an oversized Gabarito invitation, Courier Prime links, a quiet metadata divider, and one small Screen Blue ASCII fish.

## Do's and Don'ts

### Do:

- **Do** use flat accent papers, decisive scale changes, and generous Browser White space.
- **Do** keep project media and imported writing primary when extending the system to work pages.
- **Do** preserve semantic structure, descriptive alt text, keyboard access, reduced-motion behavior, and redundant link access for draggable content.
- **Do** use only named tokens from `src/styles/tokens.css` for color, type size, spacing, radius, shadow, and motion.

### Don't:

- **Don't** add paper grain, gradients, glass, glossy effects, or generic rounded cards to calibrated collage components.
- **Don't** revive retro program windows, selection handles, doubled frame layers, or dark desktop chrome.
- **Don't** add ambient drifting or automatic decorative motion; interaction begins with intentional user input.
- **Don't** copy composition, imagery, or typography literally from reference images or generated mockups when it is absent from the implemented system.
