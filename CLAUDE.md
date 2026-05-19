# Eficas Consulting site — agent notes

## Project
Marketing site for Eficas Consulting, a general vendor for state, county,
and local government. Single-file static site (index.html) plus a
capabilities statement PDF.

## Style rules
- Editorial institutional aesthetic. Navy + ivory + ochre palette.
- Fonts: Fraunces (display) + IBM Plex Sans (body) + IBM Plex Mono (kickers).
- Tone: serious, plainspoken, procurement-officer-friendly. Avoid marketing
  clichés ("disrupt," "world-class," "revolutionary").
- Accessibility is non-negotiable. WCAG AA contrast, semantic HTML, visible
  focus rings, prefers-reduced-motion respected.

## Don'ts
- No tracking scripts (Google Analytics, Meta Pixel) without asking.
- No build step or framework. This is intentionally a single static HTML file.
- Don't reformat unchanged sections when making targeted edits.

## Deploy
Cloudflare Pages, connected to the main branch of this repo.
