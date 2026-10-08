# Mor-Son Construction — homepage concept

A redesigned homepage for [Mor-Son Construction Inc.](https://www.morsonconstruction.com/), a family-run builder in San Clemente, CA, prepared by OakSpin AI as a pitch concept.

**Live preview:** https://oakspin-ai.github.io/morson-construction-homepage/

## What changed from the current site

- **Real work only.** Every project photo comes from Mor-Son's own site; the stock "workers in hard hats" image was dropped.
- **Brand kept, used better.** The original logo stays. Its sun yellow becomes an accent (the rising sun in the hero) against calm coastal neutrals instead of filling the page.
- **Owner-led positioning.** Copy is rebuilt from verified facts and client reviews: Bob Morris runs every job, roots back to 1974, CA License B-849299, BBB A+.
- **A working inquiry flow.** The old "Get A Quote" button linked to `#`. The new form asks for project type, location, timing and contact details, and opens a pre-filled email to the owner.
- **Mobile first.** Sticky call / start-a-project bar, readable type, no horizontal scroll.

## Stack

A single static `index.html` with inline CSS and a little vanilla JS. Fonts: Archivo (display and UI) and Source Serif 4 (reading text) from Google Fonts. Images are optimized WebP with JPEG fallbacks in `assets/img/`.

Run locally:

```bash
python3 -m http.server 8743
```
