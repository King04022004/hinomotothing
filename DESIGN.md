# DESIGN

## Direction

Mobile-first landing page for a local air-conditioner installation company. The page should feel trustworthy, direct, and easy to act on after a TikTok visit. Visual reference: Webflow-like CTA rhythm for clear conversion flow, with Notion-like calm spacing and readable hierarchy.

## Palette

- Base: `#ffffff`
- Text: `#202124`
- Muted text: `#5f6368`
- Border: `#dfe3e7`
- Brand navy: `#1f3a66`
- Brand red: `#b83a3d`
- LINE green: `#43b149`
- Warm section: `#f7f4ef`
- Footer navy: `#23395f`

## Typography

Use system sans-serif. Headings are bold and compact, but not oversized. Body text should remain legible on mobile. Letter spacing stays at `0`.

## Layout

- Build the page for mobile first, with a centered max-width shell on large screens.
- Header stays simple: logo mark text, service area strip, and contact buttons.
- Primary CTA appears early and again near the bottom.
- Sections should be full-width bands with constrained content, not nested cards.
- Cards are only for repeated services and contact/info blocks.

## Components

- CTA buttons use solid color, clear icons, and stable height.
- LINE actions use green; phone actions use brand navy or red depending on prominence.
- Cards use 8px radius, thin borders, and soft shadows only when useful.
- Footer is dense and practical, matching a local service business.

## Responsive Behavior

- On mobile, sticky bottom actions remain visible.
- On desktop, the page appears as a polished centered landing page with generous side background.
- Text must wrap cleanly in buttons and cards.

## Do

- Make company name and service area immediately visible.
- Keep contact placeholders obvious but non-blocking.
- Make instructions for adding LINE visually scannable.
- Include address, business hours, service list, and marketplace mention.

## Do Not

- Do not create a marketing-only hero with vague copy.
- Do not rely on purple/blue gradients or decorative blobs.
- Do not hide the practical contact path behind long explanation.
