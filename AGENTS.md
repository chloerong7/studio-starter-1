# House Rules

This is a student portfolio site for the AI-Native Design Studio course.

- Every color, font size, spacing, and radius value comes from `src/styles/tokens.css` via `var(--*)`. Never hardcode hex colors or px sizes in page styles.
- No CSS frameworks, no JS frameworks. Vanilla HTML/CSS/JS inside Astro.
- `PRODUCT.md` and `DESIGN.md` at the repo root describe what this site is and how it should look. Read them before any design work.
- Full rules (images, assets, accessibility) live in `.claude/skills/design-rules/SKILL.md` — they are mandatory.
- Semantic HTML, mobile-first, WCAG AA contrast.

## GitHub and Vercel workflow

- Never make project changes directly on `main`.
- For every change, create a `codex/` branch, commit the completed work with a clear message, push the branch to GitHub, and open a pull request targeting `main`.
- Use the pull request's Vercel Preview deployment to verify the change before merging.
- Treat merging the pull request as the production deployment step; the connected Vercel project deploys `main` automatically.
- Do not bypass the pull request workflow unless Chloe explicitly asks for an exception.
