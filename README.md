# Vela Textile DPP Prototype — Animated one-page static site

This repository contains a polished one-page scroll prototype for the TraceWeave practical case. It is intentionally static: no React, no Tailwind build, no npm install and no build step required.

## Files

- `index.html` — complete one-page DPP prototype with embedded CSS and JavaScript animations.
- `vercel.json` — minimal Vercel config for clean static hosting.
- `README.md` — this file.

## Deploy on Vercel

Use these settings:

- Framework Preset: **Other**
- Build Command: leave empty
- Output Directory: leave empty or `.`
- Root Directory: leave empty if these files are in the repository root

## Prototype content

The page covers: DPP readiness, product identity, supply chain, composition, certification/evidence layer, environmental impact, durability, end of life, compliance and public QR metadata.

## Motion design

The site includes smooth anchor scrolling, scroll progress, section reveal animations, staggered cards, animated material bars, animated impact rings and subtle hero motion. It also respects `prefers-reduced-motion` for accessibility.
