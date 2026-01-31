# Orbit Sling Brand Guidelines

## Brand Intent
Orbit Sling should feel real, technical, and trustworthy. The visual system is high‑contrast, bold, and modern. Clarity beats cleverness.

## Logo
Primary logo: `brandassets/Gradient Logo.png`

Rules:
- Use the gradient logo on dark backgrounds when possible.
- Minimum clear space: the height of the “O” around all sides.
- Minimum size (screen): 120px wide.
- Do not stretch, skew, rotate, or alter colors.

## Color Palette
Core colors:
- Black: `#000000`
- Primary 1 (Indigo): `#6360f9`
- Accent 1 (Magenta): `#e01a4f`
- Accent 2 (Amber): `#f0a202`
- White (Text): `#ffffff`

Usage guidance:
- Base background: Black (`#000000`).
- Primary CTA: Indigo (`#6360f9`) with white text.
- Highlights/alerts: Magenta (`#e01a4f`).
- Secondary highlights: Amber (`#f0a202`).
- Maintain strong contrast; avoid light text on amber unless weight/size are high.
- Gradients are encouraged; use a smooth blend of Indigo → Magenta → Amber for hero accents, section dividers, and subtle backgrounds.

Suggested balance (approx.):
- 70% black / neutral space
- 20% indigo primary
- 10% accents (magenta + amber)

## Typography
Fonts:
- Headings: Inter **Bold**
- Body: Inter **Regular**
- Tertiary (labels, tags, small UI): Poppins **Regular**

CSS recommendations:
- Base font size: 16–18px
- Heading sizes: 40–56px (H1), 28–36px (H2), 20–24px (H3)
- Line height: 1.4–1.6 for body, 1.1–1.3 for headings
- Letter spacing: -0.01em to 0 for large headings

## Layout & Spacing
- Use generous spacing; avoid dense blocks of text.
- Prefer left‑aligned content for readability.
- 8px spacing grid; primary sections in 48–96px vertical rhythm.

## Imagery & Graphics
- Use real product, team, or facility images when possible.
- Avoid generic stock; if needed, keep it monochrome or high‑contrast.
- Gradients can be used subtly as background accents, but keep the page legible.

## Cosmic Theme Effects
The cosmic vibe is subtle and clean, not sci‑fi busy. Key cues from the sample:
- Large soft "planet" orb using the Indigo → Magenta → Amber gradient.
- Thin orbit lines (1px) in white at low opacity.
- Small star dots and subtle 6‑sided sparkles (hexes, JWST‑style), also low opacity.
- White headline with a soft glow (blurred shadow), not neon.
- Subtle grain/noise overlay across dark backgrounds.

CSS ideas:
- Headline glow: `text-shadow: 0 0 18px rgba(255,255,255,0.35), 0 0 36px rgba(99,96,249,0.25);`
- Planet orb: `background: radial-gradient(circle at 35% 40%, #6360f9 0%, #e01a4f 45%, #f0a202 75%, rgba(240,162,2,0) 100%);`
- Orbit lines: `border: 1px solid rgba(255,255,255,0.35);`
- Grain overlay: use a low‑opacity noise PNG or CSS `background-image` noise with `opacity: 0.05`–`0.1`.

## Buttons & Links
- Primary button: Indigo background, white text, rounded 8–12px.
- Secondary button: Transparent with white border and white text.
- Links in body: White text with underline on hover.

## Icons & Favicons
Favicons and app icons are in `brandassets/`.

## Voice
- Clear, direct, minimal hype.
- Emphasize reliability and real‑world delivery.
- Keep sentences short; avoid jargon without explanation.

## Content Guidelines (Tone, Grammar, Formatting)
- No em dashes. Use periods or commas instead.
- Casual, founder‑to‑founder tone. Spoken, not corporate.
- Clear, concise language. Prefer short sentences.
- No flowery or “buttery” language. Be direct, but make the point land.

## Power Phrases
Use these as repeated anchors across the site, headlines, and CTAs.

Primary (positioning):
- Clarity and predictability for your pipeline.
- A pipeline you can understand, measure, and repeat.
- Simple systems. Real conversations.

Supporting (how it works):
- Signal‑based outreach that connects with ideal buyers.
- Tool‑agnostic systems built from first principles.
- Automation where it helps, humans where it matters.

Outcome‑focused:
- More qualified conversations, less noise.
- Reliable pipeline performance without the busywork.
