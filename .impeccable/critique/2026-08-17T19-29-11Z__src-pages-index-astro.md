---
target: the homepage calibration surface
total_score: 18
max_score: 28
na_heuristics: 7,9,10
p0_count: 0
p1_count: 3
timestamp: 2026-08-17T19-29-11Z
slug: src-pages-index-astro
---
# Homepage calibration-surface critique

## Alignment scorecard

| Reference | Score | Assessment |
|---|---:|---|
| PRODUCT.md as written | 2/10 | The file is still a blank starter worksheet, so it cannot serve as durable approved product context. |
| Approved product decisions recoverable from the project | 7/10 | The page communicates Chloe's people-centered, playful perspective and prioritizes POYjector, but the visible role proposition and recruiter conversion path are weak. |
| Approved direction | 9/10 | The flat digital-paper collage, Gabarito/Courier pairing, palette, tape, fish, asymmetry, and direct manipulation are carried through coherently. |
| Live token system | 9/10 | The page consistently uses named tokens and the locked palette/type system; the main weakness is focus contrast on colored papers. |

## Design Health Score

| # | Heuristic | Score | Key Issue |
|---|---|---:|---|
| 1 | Visibility of System Status | 2 | Movement responds immediately, but moved state and reset are not visibly communicated. |
| 2 | Match System / Real World | 3 | The paper metaphor is legible; “Current portfolio” is confusing on the current portfolio. |
| 3 | User Control and Freedom | 2 | Escape resets for keyboard users, but pointer users have no reset and movement is unbounded. |
| 4 | Consistency and Standards | 3 | Strong visual consistency, with a few naming and navigation mismatches. |
| 5 | Error Prevention | 2 | Papers can cover links or move off-stage; drag surfaces create mobile gesture risk. |
| 6 | Recognition Rather Than Recall | 3 | Labels are visible, but the unconventional hero still needs instructions. |
| 7 | Flexibility and Efficiency | n/a | Not material for this Experience-mode portfolio. |
| 8 | Aesthetic and Minimalist Design | 3 | Authored and spacious, but destinations repeat before work evidence appears. |
| 9 | Error Recovery | n/a | No transactional workflow exists. |
| 10 | Help and Documentation | n/a | Not material for this portfolio surface. |
| **Total** | | **18/28** | **Acceptable, with three P1 calibration flaws** |

## Design Specificity Verdict

Highly authored visually; under-specific professionally. The paper collage, saturated flat colors, typography, tape, ASCII fish, and direct manipulation clearly belong to Chloe's chosen world. The first viewport, however, foregrounds the portfolio interaction metaphor over Chloe's product-design evidence and distinct professional proposition.

The deterministic scan returned zero primary or advisory findings for `src/pages/index.astro`. Manual browser evidence caught issues outside that scan: 28 of 43 measured links or focusable elements had at least one dimension below 44 CSS pixels, including the header links at roughly 21 pixels high. No horizontal overflow or console errors appeared at desktop, tablet, or mobile widths.

No reliable user-visible detector overlay was created because the available browser evaluation surface did not permit the required mutable script-injection preflight.

## Overall Impression

The visual identity is already unusually memorable and coherent. The single biggest opportunity is to make the same first impression prove Chloe's product-design value, rather than primarily proving that the portfolio itself is playful.

## What's Working

- The visual language has real authorship and remains coherent from the hero through the footer.
- POYjector receives a clear featured treatment, and the lower-page asymmetry feels curated rather than templated.
- The semantic base is thoughtful: headings, landmarks, descriptive alt text, skip navigation, keyboard-operable papers, visible focus, and reduced-motion support are present.

## Priority Issues

### [P1] Work evidence does not lead the first viewport

The desktop hero is identity, category papers, and a repeated text index; the first artifact appears below the fold. Recruiters meet the navigation concept before seeing evidence of product-design ability.

**Fix:** Keep the approved collage identity, but introduce a strong POYjector artifact or outcome crop as the dominant proof within or immediately adjacent to the hero, with movable papers as secondary navigation.

**Suggested command:** `$impeccable layout homepage hero`

### [P1] Responsive interaction favors the concept over touch usability

Tablet slips obscure parts of category titles; mobile becomes a long hero sequence. Twenty-eight of 43 measured interactive elements fall below a 44-pixel target in at least one dimension, and drag surfaces can interfere with coarse-pointer scrolling. Drag is unbounded and has no visible pointer reset.

**Fix:** Give navigation links 44-pixel targets, disable or simplify drag for coarse pointers, preserve legible paper labels at tablet widths, constrain movement, and expose a reset control only after movement.

**Suggested command:** `$impeccable adapt homepage hero`

### [P1] Recruiter conversion is incomplete

Contact reaches a polished footer but offers only Instagram and “Current portfolio.” There is no direct email or professional contact route, and the external-portfolio label makes this site feel provisional.

**Fix:** Add Chloe's approved professional contact destination; rename or remove “Current portfolio”; add a résumé or professional profile only if Chloe supplies it.

**Suggested command:** `$impeccable clarify homepage footer`

### [P2] The visible positioning is too generic

“Designing for people, stories, and human connection” expresses values but not Chloe's specific product-design strength. The case-study preview names generic sections instead of previewing actual contribution or learning.

**Fix:** Add one verified, concrete product-design descriptor and replace generic case-study anatomy with supported evidence from POYjector.

**Suggested command:** `$impeccable clarify homepage`

### [P2] Repeated navigation delays evaluation

The paper stack and work index repeat the same destinations before POYjector, and later links repeat them again. This particularly lengthens mobile scanning.

**Fix:** Give each layer one job: disciplines in the stack, individual work in the project sections, and one compact path to the full index.

**Suggested command:** `$impeccable distill homepage`

## Persona Red Flags

**Mina, recruiter:** The first ten seconds establish taste but not role scope, impact, résumé, availability, or direct contact. The wide discipline list may read as unfocused before POYjector supplies context.

**Jordan, first-time visitor:** The stack, slips, work index, and full-work link offer overlapping paths. It is unclear which is the intended route, and Escape-to-reset is undisclosed.

**Casey, distracted mobile visitor:** Small header targets, a long pre-project hero, and drag-sensitive surfaces make quick one-handed evaluation harder than necessary.

## Minor Observations

- The blue focus ring is strong on white but can fall below 3:1 against pink, cyan, lime, and powder papers.
- “Product designer” appears in metadata but not visibly in the hero.
- “Show” is less descriptive than the graphic-design project it labels.
- The footer composition is strong; its destination choices are the issue.
- `PRODUCT.md` must eventually be restored with the approved audience, goals, voice, and success criteria before another page inherits incomplete context.

## Questions to Consider

- Should the approved hero remain artifact-free, or may POYjector evidence enter the first viewport?
- Is drag a core expression of Chloe's interaction practice, or a personality layer that can disappear on touch devices?
- What verified sentence could describe Chloe but not any thoughtful multidisciplinary designer?
- Which destination should be the authoritative professional contact and portfolio?
