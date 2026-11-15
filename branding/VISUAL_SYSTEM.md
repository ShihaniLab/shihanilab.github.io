# Visual system
## Colour (5 colours, nothing else)
| Token | Hex | Use |
|---|---|---|
| --hs-bg | #EAEAE8 | Page background (editorial light grey) |
| --hs-ink | #111111 | Typography, black panels, buttons |
| --hs-red | #C92720 | Signal only: markers, numbers, key words, CTAs, crop marks |
| White | #FFFFFF | Cards and reading surfaces |
| --hs-navy | #1F2A44 | Ink navy, the 5th colour: annotations, nodes, Thinking Engine panels (fit test, call facts, method foundation) |
| --hs-line | rgba(31,42,68,.22) | Hairlines, dividers, grid lines |

## Typography
1. Statement: DM Sans 800, tight tracking (−0.045em), large.
2. Information: DM Sans 400/500, 15–18px.
3. Annotation (`.fig`): DM Sans 600, 10.5px caps, +0.16em tracking, navy.
4. Editorial accent: Instrument Serif italic, one phrase per section at most ("Decode systems.", signature).
5. Numbers: Anton (section numbers, nodes, big facts).
Arabic: Cairo for all layers; annotations Cairo 600 12px, no tracking; serif accents become Cairo 700.

## Grid and spacing
- Content width 1080px. Desktop (≥1024px) uses a 12-column logic: 5/7 splits (image/text), 4/8 (journey).
- A 1px navy hairline marks the left grid edge of every section on desktop (right edge in Arabic).
- Section rhythm: 60px top/bottom on desktop; mobile keeps its own spacing.

## Photography
B&W, one directional light, deep blacks, fine grain. Images are converted to grayscale in CSS (`filter:grayscale(1)`), so colour originals can be used. Crops: 4:3 / 4:5 / 16:9 / 21:9 depending on section.

## Graphic elements
Crop marks (`.crop.tl/.tr/.bl/.br`, red 1.5px) · figure labels (`.fig`) · nodes (`.hsn`, navy circle with Anton number; `.hsn.r` red) · hairline dividers · eye-line node on the hero portrait.
