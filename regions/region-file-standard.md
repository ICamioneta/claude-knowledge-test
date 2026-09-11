---
title: Region file standard
description: A standard to hold my region pages to.
---


# Region File Standard

A template for documenting the geo-cultural regions of the world. Each region file should follow this structure so entries stay consistent for readers and easy to maintain as the map grows. Sections marked _(optional)_ only appear when relevant to that region — don't force them.

---

## 1. Title & Tagline

The region's name, plus a one-line tagline that captures its character in a phrase (the way a map legend or chapter title would). This is the first thing a reader sees.

> **The Ashenmoor Reach** _Where the peat-smoke never quite clears._

---

## 2. Quick Facts

A compact infobox-style block — the scannable summary before the prose. Useful both for readers and for pulling into your Leaflet map's popup/tooltip.

| Field                             | Notes                                                                                                                                                                                                     |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Climate**                       | Dominant/defining climate character — a broad label, not exhaustive. Variation across the region belongs in Section 4, not here.                                                                          |
| **General development**           | Overall level of development and self-sufficiency (e.g. "largely agrarian and self-sufficient, with pockets of early mechanization").                                                                     |
| **Hegemonic nations**             | Which nation(s) or polities hold power or influence across the region — since a region this size will often span, or be contested by, more than one. One line; the geopolitical detail belongs elsewhere. |
| **Dominant peoples**              | Link out to culture page(s) — don't describe here                                                                                                                                                         |
| **Magic/supernatural prevalence** | _(optional)_ None / Latent / Present / Saturated — however you grade it elsewhere                                                                                                                         |
| **Area / population**             | Given the scale involved, worth including as a matter of course rather than optional — it does real work orienting the reader (e.g. "670,000 km²")                                                        |
| **Map reference**                 | Polygon ID / coordinates for the Leaflet map integration                                                                                                                                                  |

---

## 3. Overview

2–4 sentences. Not a summary of the sections below — an evocative hook. What does this region _feel_ like to move through? This is the paragraph that sells the place.

---

## 4. Geography & Climate

The load-bearing section, since climate is your primary descriptor, and the only place terrain gets described in full — at this scale, terrain is too varied for a one-line infobox field. Covers:

- Physical geography: the terrain features that matter, elevation, coastlines, rivers, natural boundaries — organized by area if the region is large enough to vary significantly
- Climate pattern across the year: seasons, prevailing weather, extremes, and how it varies across the region's size
- How climate shapes life here (what grows, what's hard, what's abundant)

This section should do most of the work of explaining _why_ the sub-regions and culture-adjacent notes below look the way they do.

---

## 5. Sub-Regions

Your existing core content — keep it, standardize the format. A table or bulleted list, each entry 1–3 sentences, with a link out if a sub-region has grown into its own page.

|Sub-region|Description|
|---|---|
|Name|1–3 sentence description|

---

## 6. Land & History

Not political/dynastic history (that lives elsewhere) — this is what's happened _to the land itself_. Geological events, magical incidents, battles or disasters that left a physical mark, why a river changed course, why a forest is scarred. Keep it tied to terrain and landscape, not court politics.

---

## 7. Peoples & Culture _(brief, cross-linked)_

Since culture pages exist separately, this section stays short: who lives here, link to their culture page(s), and note only what's _regionally distinct_ — e.g. a subgroup's customs shifted by living in this specific climate/terrain. Don't re-describe the culture itself.

---

## 8. Economy & Industry

Given the 1750s-cusp setting and the self-sufficient norm at this scale, this section is less about a single defining industry and more about texture:

- Natural resources and what's harvested/mined/farmed, and how self-sufficiency plays out locally
- Trade goods that do move in and out, and who they trade with (even self-sufficient regions usually trade _something_)
- Level of industry — proto-industrial, artisanal, still preindustrial, early mechanization — and where within the region that varies
- Any regional specialty worth naming (a famous export, a guild, a craft) — this is where exceptions to "General development" in the infobox belong

---

## 9. Notable Locations & Landmarks

Key settlements, ruins, natural wonders, or sites worth a reader's attention. List format, link out where a location has its own page.

---

## 10. Flora & Fauna _(optional)_

Only if there's something distinctive — a fantastical creature, a plant tied to the region's identity or economy. Skip if it's not adding anything new.

---

## 11. Supernatural / Magical Features _(optional)_

For regions where magic is present at a level worth describing on its own — ley lines, hauntings, altered physics, magical hazards. Given the low/high fantasy mix, some regions will need this section and others won't; that's fine.

---

## 12. See Also

Cross-links: adjacent regions, relevant culture pages, key figures or events tied to this land, sub-region pages if split out.

---

### Notes on use

- Sections 1–2 exist to serve the website/map — keep them tight and structured, since they're what a Leaflet popup or nav card will likely pull from.
- Sections 3–4 are the descriptive core.
- Sections 6–9 are where regions will differ most in length — a quiet agricultural region might have three sentences of history and a page of economy; a contested borderland might flip that.
- Anything that's really about _culture_ or _politics_ in depth belongs on those dedicated pages — this file should stay geo-cultural, not duplicate them.