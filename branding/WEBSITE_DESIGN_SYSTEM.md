# Website design system
## Page order
Nav · Hero (01) · Observation band · How I think · Method · Growth loop · Customer journey · Selected work · Services · About · Fit test · Diagnosis call + form · Footer. Section numbers are automatic (CSS counter on `.band`).

## Navigation
Name · Approach · Work · Services · About · Book a Diagnosis Call (red) · language switch. Sticky, compact.

## Buttons
Square black button with red arrow box (`.btn.sqb`), white variant on red/navy surfaces. Every contact CTA goes to the form (#form or #call); no bare WhatsApp links.

## Components
- `.obs`: full-bleed cinematic band, gradient only at the bottom for legibility.
- `.sysg` / `.loop`: image + 5 numbered nodes on a vertical connector + red "back to understanding" node.
- `.jhg`: eye image + journey rows.
- `.bsr`: case file, B&W image, "Case file 0X" navy label, logo, challenge / my work / focus. No results unless verified.
- Services `.pyp`: two-model selector. A = Growth Partnership (red panel: label, headline, description, 3-month minimum, CTA · right: 5 work areas + "Good to know" conditions). B = Strategic Projects (red panel · right: 4 categories A–D × 2 services with descriptions + "How projects work" conditions). No prices, no tiers.
- `.about`: portrait with crop marks, story, 3 principles, 46K+ stat, serif signature.
- `.fx`: fit test on navy, puzzle ME/YOU.
- Call: HS-014 image, navy facts box, agenda, form (tiles → fields → WhatsApp + email + Google Sheet).
## Responsive
Desktop ≥1024px: 5/7 and 4/8 grids, hairline grid edge, size system (H2 ≈46px, lead 18px). Mobile: single column, images first, no horizontal overflow (tested at 375px). Tablet uses the mobile stack with wider measure.
