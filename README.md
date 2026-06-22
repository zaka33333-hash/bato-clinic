# Bato Clinic — عيادة باتو

A cinematic, bilingual (Arabic-first / English) website for **Bato Clinic**, a medical-aesthetics & dermatology practice in Kuwait & Dubai. *“Where beauty and health meet.”*

**▶ Live:** https://zaka33333-hash.github.io/bato-clinic/

A single, self-contained `index.html` — no build step, no framework (Three.js + Lenis load from CDN).

## Concept — “The Threshold”
The visitor is walked, on scroll, through an **arcade of arches** — a real-time 3D corridor receding into fog toward a warm light at the end. The literal *“building you walk through”* mechanic (in the aircenter.space lineage), fused with Bato’s threshold-to-care metaphor: you move out of the dark, chamber by chamber, and arrive in the light at the booking step.

## Features
- **WebGL (Three.js) arcade** the camera dollies through as you scroll — fog depth, a warm light at the end, subtle cursor parallax. Graceful fallback if WebGL is unavailable.
- **8-scene journey:** Overture → Philosophy → Skin · Hair · Refinement · Facial → Practitioners → Booking, each fading in over the moving corridor.
- **Arabic-first, fully bilingual** with a one-click EN toggle and correct **RTL ⇄ LTR** mirroring.
- **Architectural / minimal register:** near-monochrome warm stone, monumental type, brutal negative space, a minimal counter-HUD + progress bar, custom cursor.
- **WhatsApp-first booking** form (composes a `wa.me` message — no backend) + sticky WhatsApp button.
- **Type:** Reem Kufi (Arabic display) · Fraunces (Latin display) · IBM Plex Sans Arabic · JetBrains Mono.
- **Lenis** smooth scroll drives the camera. Honors `prefers-reduced-motion`.

## Compliance (Kuwait MOH)
Designed to satisfy Kuwait medical-advertising rules: **no patient photos, no before/after, no prices/discounts, no superlatives**; doctor titles factual; a licence-disclosure block in the footer.

## Run locally
```bash
npx serve .          # or: node .claude/serve.js  → http://localhost:8137
```
(Or just open `index.html` in a browser.)

## ⚠️ Before going live — client to complete
1. **Legal:** replace the footer placeholders with the real **MOH advertising-permit + facility licence numbers** (the site is legally a medical “advertisement” and needs MOH Drug Inspection Dept approval — confirm with local counsel).
2. **Doctors:** confirm each name/title/credential is factual and licence-backed.
3. **Confirm** the WhatsApp number and the **Dubai branch** status before promoting it.

---
© 2026 Bato Medical Clinic.
