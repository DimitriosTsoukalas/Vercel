# Vela Textile DPP Prototype

Static Digital Product Passport prototype for the TraceWeave practical case.

## Files

- `index.html` — complete static website with CSS and JavaScript included.
- `vercel.json` — Vercel static routing fallback.
- `README.md` — project note.

## Deployment

Upload these three files directly into the root of the GitHub repository, then deploy with Vercel.

Recommended Vercel settings:

- Framework Preset: Other
- Build Command: leave empty
- Output Directory: leave empty or `.`
- Root Directory: leave empty

## Latest update

This version includes two viewing modes at the top of the website:

1. **Holistic View** — shows the full one-page scroll website exactly as a complete DPP journey.
2. **DPP Blocks View** — lets the user select one DPP block at a time through a circular 9-segment selector, so clicking Identification, Origin, Composition, Compliance, etc. highlights the corresponding circle segment and shows only that block.

The site remains a single static HTML file, with no React, Tailwind, npm, external assets, or build command. The Compliance block now shows a KYC/CLM-style sequential evidence review where Line 1 closes first, QC is unlocked second, and Final Audit Checks close last with review dates recorded at each closure.

## Design notes

- Pure dark green / gold / grey gradient background.
- Nine DPP blocks only, represented in DPP Blocks View through a circular block selector.
- Compliance block includes certification identification, documentation checklist, Line 1 / QC / Final Audit role-based closure workflow, and a lightweight risk-based calculator.
- All values are fictional and used only for the case prototype.


## Circular selector fix

The DPP Blocks View circular selector now aligns the gold segment with the selected circular node/block.

## Contained Blocks View scroll

DPP Blocks View now uses contained scrolling: the page itself stays fixed, and only the selected DPP block panel scrolls when its content is taller than the available screen space. This avoids excessive empty page scrolling while still allowing long blocks such as Compliance to remain readable.

## Origin & production hover interaction

The five production-stage cards now subtly zoom and highlight on mouse hover to make the multi-tier chain feel more interactive.

## Traceability zoom interaction

The Traceability table now opens in a smooth in-page zoom overlay when clicked. The user can close it with the X button, by pressing Escape, or by clicking outside the enlarged panel.

## Traceability readable zoom update

The Traceability zoom overlay now enlarges the actual table typography, spacing and table width so the zoom view improves readability rather than only enlarging the container.
