# Design

## Overall Direction

Minimal personal page inspired by a plain text profile: a narrow reading column on an off-white canvas, dark neutral text, restrained inline links, and no decorative sections.

## Color

- Background: `oklch(97% 0.006 255)`
- Primary text: `oklch(20% 0.01 255)`
- Secondary text: `oklch(38% 0.018 255)`
- Muted mark: `oklch(78% 0.015 255)`
- Link: `oklch(25% 0.018 255)`
- Link hover: `oklch(15% 0.012 255)`

## Typography

Use the system sans stack for fast loading and a quiet, utilitarian feel. The name is the only heading. Body copy should sit around 17px with generous line height and a maximum line length near 65 characters.

## Layout

Single column, left aligned, visually similar to a personal note rather than a landing page. On desktop, the content starts slightly above vertical center and stays narrow. On mobile, it uses comfortable edge padding and keeps the same reading rhythm.

## Components

- Inline links use subtle underline treatment and darken on hover.
- Footer/social links remain inside the final paragraph.
- A small text mark near the bottom gives the page a quiet personal signature.

## Motion

No required motion. Hover and focus transitions may be subtle and should respect reduced-motion preferences.
