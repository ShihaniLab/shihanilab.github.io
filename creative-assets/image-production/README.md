# Image production — HUMAN SYSTEMS
How images for the website are made, checked and added.

1. **Concepts** — `IMAGE_CONCEPTS.md`: the approved list, split into A Photography (real), B AI conceptual images, C native graphics (built in code, no files).
2. **Prompts** — `IMAGE_GENERATION_PROMPTS.md`: one production-ready prompt per AI asset (B), and a shoot / selection brief for real photos (A). Every block starts with its asset ID and website section.
3. **Generate** — Soufiane generates each B image with his image tool (one image per prompt, same tool for the whole set). Real photos: one photoshoot covers HS-001, HS-012, HS-013.
4. **Deliver** — send full-resolution files named by asset ID (`HS-002.png`). Generate 2–4 variations and choose the best, or send all and Claude helps choose.
5. **Check** — Claude inspects each file: matches the concept, B&W and lighting consistent with the set, no AI artefacts (hands, text, faces), right ratio. Rejected files are marked ❌ in the tracker with the reason.
6. **Optimise & place** — Claude converts to webp (desktop ≤ 2000px wide, mobile crop ≤ 1000px), places it in `/assets/images/`, and updates `IMAGE_ASSET_TRACKER.md`.
7. **Missing assets** are never replaced silently: Claude reports them and asks: placeholder or wait.

Recommended order: real photoshoot → HS-002 + HS-014 → HS-003/004/005 (as one set) → HS-007, HS-008 → HS-006 only if needed → HS-015 after HS-001 is approved.
No website coding starts until the approved images are received.
