# Crown Listings — Master Blueprint & Multi-Agent Operating Guide

## 1. Core Mission & Philosophy
**Signal Over Noise. Visual Orientation for the Eye and Heart.**

Thailand's physical living spaces—luxury condominiums, gated neighborhoods, townhouses, and affordable resort residences—are world-class, yet 95% of online property listings present them with low-resolution images, intrusive center-screen watermarks, missing floor plans, and walls of unstructured text.

**Crown Listings** bridges that gap through two connected pillars:
1. **The Listing Enhancement & Clean-Up Agency (B2B for Agents, Owners & Property Managers)**
   - Led and researched on the ground by our Thai co-founder (finding high-potential listings across condos, houses, townhouses, gated communities, and resorts with presentation flaws).
   - We proactively produce **pre-made listing clean-ups** and reach out to agents/managers with an interactive **side-by-side Before/After Slider** showing their current listing vs. the Crown Listings enhanced version:
     - Razor-sharp, de-noised, architectural-grade photography.
     - Intrusive center watermarks and hashtags removed (or tucked discreetly into a silent corner).
     - Final gallery slides dedicated to **real informational support**: clean floor plans, neighborhood orientation maps, BTS/MRT & key lifestyle connections, and clear tenant guidance.
2. **The Dream Home Visual Discovery Platform (B2C for Searchers & Expats/Locals)**
   - Instead of overwhelming searchers with cluttered portals and noisy metrics, we guide them visually through the extraordinary lifestyles affordably available in Thailand.

---

## 2. Reference Links (Hark Seeds)
- **Homepage Draft (Dream Home Searchers & Listers):** https://hark.com/site/fdd8b142-8fa0-41f3-8a9b-efcdea293ff5?hark_region=us
- **Pitch Deck Draft (For Listing Managers & Agents):** https://hark.com/site/a06bc9d3-f6e2-49ea-a4a0-ed2fd8225f69?hark_region=us

---

## 3. Canonical Folder & Naming Architecture
Every listing processed by any agent (Antigravity, Hark, Claude, Cursor, Grok) MUST follow this exact directory hierarchy inside `Crown Listings/`:

```text
Crown Listings/
└── <Head District (Khet)>/                      # e.g., Watthana, Khlong Toei, Sathon, Pathum Wan
    └── <Sub-District / Neighborhood>/           # e.g., Thonglor, Ekkamai, Phrom Phong, Asok
        └── <Project Facility Name>/             # e.g., Noble Form Thonglor
            └── Listing XXXX (<Project Name>)/   # Global sequential counter across all listings ever touched
                ├── Original Assets/             # All raw, original images & source files from the listing
                ├── Enhanced Shoot/              # Upscaled, watermark-cleaned photos + info/map/floorplan slides
                └── Listing XXXX (<Project Name>).md  # Complete structured listing data, source URL & outreach notes
```

### Global Listing Counter Rules
- Every new listing we ever touch increments the global 4-digit counter: `Listing 0001`, `Listing 0002`, `Listing 0003`, etc.
- Always append the facility/project name in parentheses: `Listing 0001 (Noble Form Thonglor)`.
- If we cover another unit inside the same building later (e.g., our 14th listing overall is another unit in Noble Form Thonglor), it goes inside the existing `Watthana/Thonglor/Noble Form Thonglor/` folder as `Listing 0014 (Noble Form Thonglor)`.

---

## 4. Image Enhancement & Asset Standards
For every listing folder:
1. **Preserve Architectural Truth:** Keep exact room geometry, materials, furniture, and lighting faithful to the real property.
2. **Eliminate Visual Friction:** Remove center-spanning agent watermarks, phone numbers, Line IDs, and washed-out screen glare. Relocate original credit/attribution into a quiet, low-opacity bottom-right corner if appropriate.
3. **Upscale to Magazine Grade:** Sharpen wood grain, fabric weave, stone textures, and architectural lighting.
4. **Tail-End Informational Slides:** Append high-clarity visual support cards at the end of the gallery (clean floor plan, transit/BTS proximity map, neighborhood lifestyle highlights).

---

## 5. Active Listings Registry
| Global ID | District | Neighborhood | Project Facility | Source URL | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Listing 0001** | Watthana | Thonglor | Noble Form Thonglor | [DDproperty #500712119](https://www.ddproperty.com/property/noble-form-thonglor-%E0%B9%82%E0%B8%99%E0%B9%80%E0%B8%9A%E0%B8%B4%E0%B8%A5-%E0%B8%9F%E0%B8%AD%E0%B8%A3%E0%B9%8C%E0%B8%A1-%E0%B8%97%E0%B8%AD%E0%B8%87%E0%B8%AB%E0%B8%A5%E0%B9%88%E0%B8%AD-%E0%B8%81%E0%B8%A3%E0%B8%B8%E0%B8%87%E0%B9%80%E0%B8%97%E0%B8%9E-%E0%B9%83%E0%B8%AB%E0%B9%89%E0%B9%80%E0%B8%8A%E0%B9%88%E0%B8%B2-500712119#) | In Progress (Image 01 Enhanced) |
