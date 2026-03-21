# Remon Alberts — Portfolio Website Brief

## Status
Version 1 (warm/parchment direction) was built and rejected. Version 2 is ready to build once photos are gathered.

---

## Client
**Name:** Remon Alberts  
**Credentials:** AIA | LEED AP | CPHD  
**Location:** New York City  
**Goal:** Portfolio website to apply for architecture and sustainable design practice roles

---

## Design Direction — Version 2

### Aesthetic
Modern, fresh, minimal. Inspired by:
- **De Zwarte Hond** — https://dezwartehond.nl/projecten/gilde-vakcollege-2/
- **Herzog & de Meuron** — https://herzogdemeuron.com
- **Solid Objectives** — https://solidobjectives.com
- **Bergen Brooklyn** — https://bergenbrooklyn.com

### What these sites share (the target aesthetic)
- White or near-white backgrounds — not warm, not cream
- One or two typefaces maximum, both contemporary sans-serifs
- Photography does all the heavy lifting on personality
- Navigation is minimal and fixed
- Project grids are clean, not decorative
- Zero ornamentation

### Typography
Contemporary grotesque. Using **Syne** (display/headings) + **Plus Jakarta Sans** (body) from Google Fonts — closest accessible equivalents to Neue Haas Grotesk / ABC Whyte.

### Color palette
- Background: pure white `#FFFFFF`
- Type: near-black charcoal `#1A1A1A`
- Accent: one subtle tone TBD (possibly a cool slate or warm stone — let photography guide it)
- No decorative color

### What to avoid
- Warm/parchment/cream tones (that was v1 — rejected)
- Serif display fonts (Cormorant, etc.)
- Grain textures, retro details
- Overlaid text cards on project images (use hover reveals instead)

---

## Site Structure

### Pages / Sections
1. **Hero** — Name, credentials, one strong image or full-screen project photo, minimal nav
2. **Work** — Project grid, 5–8 projects, photography-first, hover to reveal title/type
3. **About** — Bio, design philosophy, portrait photo
4. **CV** — Clean layout, downloadable PDF link

### Navigation
Fixed, minimal. Initials "RA" as logo mark + four links: Work · About · CV · Contact

---

## Projects (5–8 planned)

| # | Project | Type | MAP Category |
|---|---------|------|-------------|
| 01 | Hudson Valley Residence | Single-family, Passive House | Ecosystem Health |
| 02 | Park Slope Brownstone | Renovation | Circular Economy |
| 03 | Brooklyn Mass Timber Mid-Rise | Multi-family | Human Health |
| 04 | Midtown Manhattan Commercial TI | Office | Social Health & Equity |
| 05 | South Bronx / East New York Mixed-Use | Housing + Retail | Climate Health |

*Note: These map directly to Remon's "Materials in Practice" Substack research series (AIA MAP framework). A subtle link between the two could be a nice touch on the About page.*

---

## Image Folder Structure

```
portfolio-images/
  hero/
    hero-main.jpg          ← landscape, strong single subject
  projects/
    01-hudson-valley/
      cover.jpg            ← landscape 3:2, this is the grid card image
      detail-1.jpg
      detail-2.jpg
    02-park-slope/
      cover.jpg
    03-brooklyn-midrise/
      cover.jpg
    04-midtown-ti/
      cover.jpg
    05-south-bronx/
      cover.jpg
  about/
    portrait.jpg
```

### Image specs
- Minimum 2000px wide
- JPG at 85% quality
- Landscape 3:2 for grid covers
- Consistent color grading across the set

### If professional photos aren't available
Good alternatives (in order of preference):
1. High-quality renders
2. Well-composed iPhone shots in good light
3. Architectural drawings / sections / axonometrics as hero images

---

## Technical Approach
- Single-file HTML (self-contained, no build step, works anywhere)
- Google Fonts via CDN
- CSS custom properties for theming
- Subtle scroll-triggered animations
- Hover-reveal project titles on grid
- Mobile responsive

### Next steps after images are gathered
1. Drop images + this brief into Cowork
2. Tell Claude: *"Continue building my portfolio — read portfolio-brief.md first"*
3. Build v2 hero + design system
4. Build project grid with real images
5. Build About section
6. Build CV section
7. Export final HTML file

---

## Notes
- All-electric systems and passive house performance treated as baseline (not novelty)
- Net-positive design is the north star: buildings that sequester carbon, clean exhaust air, improve water quality
- Tone: confident, grounded, not self-promotional
