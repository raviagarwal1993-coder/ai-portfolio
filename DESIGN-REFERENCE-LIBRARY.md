# AI Portfolio — Design Reference Library

This file is a lightweight reference library for the visual direction of the portfolio. It is intentionally documentation-only: the live site remains plain HTML/CSS so it stays fast and easy to maintain.

## Primary design references

### Taste Skill
https://github.com/Leonxlnx/taste-skill

Use for: anti-generic design direction, stronger typography, spacing, layout variance, restrained motion, and avoiding AI-generated "template slop". The current v2 skill explicitly tunes variance, motion, and density and includes a redesign-audit workflow.

**Portfolio application:** use its principles, not its runtime. Keep the page calm, editorial, and distinctive without adding unnecessary animation.

### Impeccable
https://github.com/pbakaus/impeccable

Use for: frontend critique, hierarchy, typography, spacing, responsive behavior, accessibility, motion, UX writing, and anti-pattern detection.

**Portfolio application:** treat the site as an "Experience" surface: the work should lead and the interface should recede. Use critique/audit/polish principles when making future changes.

### 21st.dev
https://github.com/21st-dev/21st

Use for: modern component and portfolio inspiration, especially hero layouts, project showcases, navigation, and visual composition.

**Portfolio application:** borrow visual ideas selectively; do not introduce a React/Tailwind dependency just to use a component.

### Magic UI
https://github.com/magicuidesign/magicui

Use for: subtle visual anchors, text motion, grid/dot patterns, bento layouts, hover states, and restrained ambient effects.

**Portfolio application:** at most one or two subtle effects. Avoid particles, animated backgrounds, and multiple competing effects.

### RetroUI
https://github.com/Dksie09/RetroUI

Use for: pixel/retro visual language and component inspiration.

**Portfolio application:** reference only. The retro style is not appropriate for the primary professional identity, but selected ideas may be useful later for an experimental AI lab page.

### Retro UI — vanilla HTML/CSS implementation
https://github.com/chriscow/retro-ui

Useful because it demonstrates that a visual system can work without React or a build step. This is a reference for the low-code constraint, not a recommendation to make the main portfolio retro.

## Theme / token reference

### TweakCN
https://github.com/jnsahaj/tweakcn

Use for: exploring theme/token combinations and avoiding default shadcn visual sameness.

**Portfolio application:** use as visual inspiration for neutral tones, borders, radius, typography scale, and accent choices. No dependency required.

## Current visual rules for this portfolio

1. Professional, editorial, and technical — not "AI landing page" cliché.
2. White/neutral base with one restrained accent.
3. Strong typography and whitespace do most of the visual work.
4. No purple-blue gradient by default.
5. No excessive rounded cards.
6. No animated background competing with the content.
7. Motion should communicate hierarchy or interaction, never decoration for its own sake.
8. Mobile layout must remain as good as desktop.
9. Keep implementation dependency-free unless a dependency creates a clear, durable benefit.
10. New components should earn their place by improving recruiter comprehension or project presentation.

## Reference hierarchy

**Taste Skill + Impeccable** → design judgment and critique

**21st.dev** → composition and component inspiration

**Magic UI** → optional subtle motion/effects

**TweakCN** → visual token exploration

**RetroUI** → experimental reference only

## Maintenance rule

When the portfolio gets a new project, improve the content first. Only change the visual system when the current design prevents the new work from being presented clearly.
