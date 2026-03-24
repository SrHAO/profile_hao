# Task: Fix LinkedIn SVG size in footer to match other icons

## Information Gathered:
- Footer.astro: LinkedIn SVG has width/height=\"256\", others \"24\". CSS: .social-link svg {width:40px; height:40px}
- footer.css: Forces 40px size, but large viewBox may distort.
- public/images/linkedin.svg: Large SVG (256x256), inline 256x256 likely causes sizing issue despite CSS.

## Plan:
1. Update LinkedIn <svg> in Footer.astro to width/height=\"24\" to match GitHub/Email/WhatsApp.
2. Ensure preserveAspectRatio if needed.

## Steps:
- [x] Create TODO
- [ ] Edit Footer.astro
- [ ] Verify
- [ ] Complete

Step 1 done.
