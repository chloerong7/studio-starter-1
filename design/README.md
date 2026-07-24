# Design workspace

Use `design/inspiration/` for private visual references. Keep palettes and generated mockups in `design/directions/`. Production-ready site assets belong in `src/assets/`.

These notes identify the approved visual direction and its implementation boundaries. The selected mock is a design contract, not a pixel-perfect screenshot to reproduce.

## Selected direction

- **Status:** Approved by Chloe for implementation.
- **Selected mock:** `design/directions/01-direction.png`
- **Direction name:** Window Cascade
- **Locked palette artifact:** `design/directions/00-palette.png`
- **Locked palette:** Graphite Desktop `#25272C`, Ink Black `#15171B`, Canvas White `#F4F3EE`, Hot Pixel Pink `#FF2D9A`, and Cursor Blue `#4385FF`.
- **Locked typography:** Hanken Grotesk for expressive display type and Recursive Mono for interface labels, metadata, and supporting copy.

## Implementation handoff

### Composition

- Build the homepage as a dark desktop containing distinct, light retro-program windows rather than conventional stacked website cards.
- Keep the first-view arrangement: identity window dominant at upper left, featured Poyjector window dominant at upper right, compact contact window below the identity window, and a wide Work Browser beginning the second fold.
- Preserve the controlled overlap, asymmetry, and breathing room that make the layout feel like an authored workspace.
- Adapt the composition responsively; preserve the reading order and relative emphasis instead of forcing desktop coordinates onto narrow screens.

### Hierarchy

- The identity statement is the primary verbal focal point and should communicate Chloe’s people-centered product-design perspective immediately.
- Poyjector is the primary work focal point and must visibly lead into context, process, and outcomes.
- The contact panel is a persistent but secondary invitation, with Email, LinkedIn, and Instagram presented as direct actions.
- Product work leads the Work Browser; Games and Graphics remain clearly accessible through deliberate tab controls.

### Imagery

- Use Chloe’s original production-quality project assets from `src/assets/`; do not rasterize or crop the generated mock into the site.
- Let one strong Poyjector process composition carry the featured window, with enough scale to show the project’s playful system and human-centered process.
- Project imagery should remain the most visually detailed material inside otherwise restrained window frames.
- Preserve original aspect ratios, supply descriptive alt text, and avoid decorative stock imagery or hotlinked media.

### Typography

- Use Hanken Grotesk at large scale for the identity statement, project names, and major section headings.
- Use Recursive Mono for title bars, navigation, metadata, category tabs, buttons, contact rows, and concise supporting copy.
- Maintain the contrast between editorial-scale humanist headlines and compact technical interface language.
- Keep line lengths and responsive type scaling readable; the mock’s exact line breaks are not mandatory.

### Palette

- Graphite Desktop is the page-level background and establishes the dark-site atmosphere.
- Canvas White is the primary window surface; Ink Black carries text, outlines, and interface structure.
- Hot Pixel Pink marks selected, active, and actionable states such as underlines, tabs, selection handles, and compact indicators.
- Cursor Blue remains a secondary accent for carefully chosen active-interface moments, not the cursor itself.
- The retro pointer uses a white fill with a crisp black pixel outline.

### Distinctive details

- Construct single-layer retro window frames with beveled edges, active and inactive title bars, compact controls, inset workspaces, and restrained status strips.
- Keep the pink editable-selection box around “interaction,” as the identity window’s signature visual moment.
- Make Work Browser tabs real keyboard-accessible controls with visible selected, hover, and focus states.
- Treat window and tab interactions as intentional responses to user input; avoid ambient motion that competes with the work.
- Use compact pink action indicators in the contact rows without inventing social-media logos or usernames.
- Preserve semantic structure, WCAG AA contrast, visible focus treatment, reduced-motion support, and a logical mobile reading order.

## Inspiration, not literal specification

- Do not copy the mock’s exact pixel coordinates, fixed window dimensions, desktop-only overlaps, or cropped fold.
- Do not use the mock PNG, its generated Poyjector collage, or its partially visible project thumbnails as production assets; rebuild with approved originals.
- Do not reproduce incidental rendering artifacts, simulated font shapes, or exact line wrapping from image generation.
- Do not make minimize, maximize, close, resize, or title-bar controls appear functional unless they have an intentional accessible behavior.
- Do not invent contact values, project claims, dates, outcomes, or social handles to match the mock.
- Do not turn every section into decorative operating-system chrome; the window system should clarify content hierarchy and interaction.
- Do not copy the source references’ exact compositions, navigation syntax, palettes, artwork, or biographical language.

## Confirmed direction inputs

- **Visual lane:** Playful tactile collage leads personal areas of the portfolio; cinematic editorial poster qualities shape the presentation of work.
- **Color strategy:** A dark Graphite Desktop surrounds light Canvas White retro windows with Ink Black content, while Hot Pixel Pink and Cursor Blue carry the colorful accents.
- **Atmosphere:** Experimental and playful without becoming overly energetic.
- **Interaction:** Interactions should feel intentional and respond to deliberate user input rather than animate constantly or compete for attention.
- **Section grammar:** Distinct content areas should use single, accurately constructed light retro-computer windows on a dark desktop: beveled frames, active and inactive title bars, compact controls, inset workspaces, and status strips without doubled backing layers.
- **Homepage composition:** Use `01-direction.png` (“Window Cascade”) as the selected layout, with separate overlapping windows establishing the hierarchy.
- **About treatment:** Carry the editable-selection box from `02-direction.png` into the identity/about statement as a focused pink selection state.
- **Tabs:** Treat the Work Browser tabs as intentional interactive controls, not decorative labels.
- **Cursor:** Render the retro pointer with a white fill and crisp black pixel outline; keep Cursor Blue available as a broader accent color.
- **Contact panel:** Use a compact desktop-style list for Email, LinkedIn, and Instagram instead of a generic “Let’s Talk” callout.

## `emmi-wu-homepage.png`

- **Source URL:** https://emmiwu.com/
- **Composition:** A large quiet field focuses attention on one off-center cluster of overlapping, rotated elements.
- **Typography:** Editorial serif copy contrasts with compact monospaced navigation and annotations.
- **Color temperature:** A warm neutral ground supports hot orange, peach, lime, and cool pale blue.
- **Texture:** Flat paper-like shapes, ruled marks, doodles, and folded corners suggest physical ephemera.
- **Density:** Most of the viewport is spacious; personality is concentrated in a small, lively area.
- **Mood:** Personal, playful, tactile, and confidently informal.
- **Do not copy literally:** The exact note-card composition, rotations, orange-and-lime palette, flower doodle, navigation labels, or biographical copy.

## `haoqi-design-work-grid.png`

- **Source URL:** https://haoqi.design/
- **Composition:** A strict coordinate grid organizes projects while deliberate cropping makes the system feel larger than the viewport.
- **Typography:** Pixel-style labels and technical metadata contrast with clean project titles.
- **Color temperature:** A cool near-black field with white type and tightly controlled acid-lime accents.
- **Texture:** Fine construction lines, crosshairs, coordinates, and terminal-like details create a schematic interface.
- **Density:** Medium-high information density remains legible because every item follows a consistent spatial system.
- **Mood:** Precise, technical, experimental, and design-engineering driven.
- **Do not copy literally:** The exact grid and crosshair system, terminal status readouts, acid-lime project tags, pixel font, navigation syntax, or project-card arrangement.

## `visual-amnesia-poster.png`

- **Source:** Variant.com; no specific source-page URL is available.
- **Composition:** Oversized type, an asymmetrical title block, and one dominant horizontal artwork create a poster-like reading sequence.
- **Typography:** A neutral grotesk shifts dramatically in scale while retaining a stripped-back typographic voice.
- **Color temperature:** Black, white, and cool gray produce a stark, gallery-like monochrome field.
- **Texture:** Glossy droplets and translucent organic forms provide a tactile counterpoint to the flat typography.
- **Density:** Large areas of black space alternate with an optically dense artwork and monumental lettering.
- **Mood:** Cinematic, severe, atmospheric, and deliberately enigmatic.
- **Do not copy literally:** The exhibition title, dates, address, exact black-and-white poster layout, line breaks, or the specific droplet artwork.
