# Design brief

Source: the interview, without Stitch
Mood: focused, technical, direct. Crisp Paul Graham-inspired minimalism with code-editor metadata and monospace typography.

## Style

- Style: Technical.
- Feel: focused, technical, direct.
- Personal detail: subtle code syntax lines and monospace metadata accents (`// `, `const`, line-numbered styling) framing key sections.
- Motion: crisp and functional: instantaneous state changes, no decorative bouncing. When the visitor prefers reduced motion, nothing moves.

## Colours

| Token | Light | Dark | Used for |
|---|---|---|---|
| background | #f6f7f9 | #0d1117 | page background: crisp cool off-white with faint dot grid |
| surface | #ffffff | #161b22 | cards, panels and highlighted blocks |
| text | #000000 | #f0f6fc | headings and body text |
| muted | #57606a | #8b949e | dates, labels, file names, borders |
| accent | #0969da | #4493f8 | links, focus ring: terminal blue |
| on-accent | #ffffff | #0d1117 | text on an accent-coloured button |

## Type

| Role | Font | Size | Weight |
|---|---|---|---|
| headings | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | name 2rem, section 1.125rem, card 1rem | 600 |
| body | "IBM Plex Sans", system-ui, sans-serif | 1rem, line height 1.6 | 400 |
| details | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | dates and labels 0.875rem | 400 |

## Shapes

- Corner radius: none: pure square corners, cards, buttons and badges.
- Borders: 1px solid in muted colour thinned out (`#d0d7de` light, `#30363d` dark), around cards.
- Shadows: none.

## Layout

- One column, at most 46rem, centred, with 1.25rem space at the sides on phones; faint technical grid background.
- 2.5rem between sections, 1rem between items in a list.
- Experience and highlights: clean structured vertical layout with 1px hairline dividers.

## Components

- Links: accent colour, underlined; keyboard focus shows a 2px accent ring.
- Cards: surface background, 1px border, 1.25rem inner space, titles in monospace heading font.
- Skills: monospace list styled like a code array: `[ "AI", "B2B SaaS", "Automation" ]`.
- Section headings: in heading font, prefixed with `// ` comment syntax.

## Signature

- Move: Other cards step back on hover and focus
- Guide: guides/css/child-state-based-styling.md
- Where: the experience and highlight cards: while one is pointed at or focused, the others dim subtly.

## Sections

1. `bio`: the name, headline, pitch, availability, and bio.
2. `links`: GitHub, Email, Instagram, Nurlify, Naluprep.
3. `cv`: startup founder experience, lead engineering background, and skills array.
4. `events`: DevFest Almaty '26 workshop participation.
