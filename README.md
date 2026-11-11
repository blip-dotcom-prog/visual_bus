# visual_bus — 2100 St. Claude Ave site planner

An interactive site plan for **2100 St. Claude Avenue, New Orleans** (corner of Frenchmen St., Marigny). It works on iPhone and desktop.

**Open it:** https://blip-dotcom-prog.github.io/visual_bus/ (after GitHub Pages is turned on)

## What it does
- An 84′ × 56′ lot on a 1-ft grid, with St. Claude Ave, Frenchmen St. and the neighboring lots
- The existing tire shop and its canopy, from the city's building footprints, checked against Feb 2025 street-level photos
- Buses you can drag, rotate and resize. They start at 32′, and you can add as many as you want.
- Driveway, car stalls, canopies, green space, containers and custom shapes
- Every piece has length and width sliders
- An editable driveway: a U on St. Claude, a U on Frenchmen, or angled (in on Frenchmen, out on St. Claude)
- Tap a neighboring lot for its owner-of-record info
- Warnings when something crosses a property line, overlaps the building, sits on the driveway, or breaks a clearance you set
- Site numbers, including whether you meet the 15% permeable open space HMC-2 requires
- Each person's layout saves in their own browser, so everyone can play around separately

## Zoning summary (HMC-2, New Orleans CZO Article 10)
- Setbacks: 0′ on all sides
- Max height: 50′
- Max FAR: 2.2
- Min permeable open space: 15%
- Historic review: Faubourg Marigny local historic district, full control (HDLC)

This is not a survey. Lot dimensions come from the assessor's record, and the building outline is the city's GIS footprint.

## Hosting
It's a single static `index.html`. To publish it on GitHub Pages: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / root**.
