# Bato Clinic — عيادة باتو

A cinematic, bilingual (Arabic-first / English) website for **Bato Clinic**, a medical-aesthetics & dermatology practice in Kuwait & Dubai. *“Where beauty and health meet.”*

**▶ Live:** https://zaka33333-hash.github.io/bato-clinic/

Built as a single, self-contained `index.html` — no build step, no framework, no dependencies to install.

## Concept — “The Threshold”
The clinic rendered as a sequence of arched niches (*mihrab*) you are walked through, light deepening toward care. A scroll-as-storytelling experience in the lineage of award sites like aircenter.space, in a warm Gulf register.

## Features
- **8-scene scroll journey:** Overture → Manifesto → Skin · Hair · Refinement · Facial → Practitioners → Booking, with calligraphic interludes.
- **Arabic-first, fully bilingual** with a one-click EN toggle and correct **RTL → LTR** mirroring.
- **Cinematic motion:** Lenis smooth scroll, mihrab arches that draw on scroll, per-section theme inversion, a counter HUD + progress bar, a custom action-label cursor, and a warm WebGL light wash in the hero (disabled under `prefers-reduced-motion`).
- **WhatsApp-first booking** form (composes a `wa.me` message — no backend) + a sticky WhatsApp button.
- **Type:** Reem Kufi · Amiri · IBM Plex Sans Arabic · Fraunces · Source Serif 4 · JetBrains Mono.
- **Palette:** warm plaster + a single brass light.

## Compliance (Kuwait MOH)
Designed to satisfy Kuwait medical-advertising rules: **no patient photos, no before/after, no prices/discounts, no superlatives**; doctor titles factual; a licence-disclosure block in the footer.

## Run locally
```bash
# any static server works, e.g.
npx serve .
# or
python3 -m http.server 8137
```
…then open the URL. (You can also just open `index.html` directly in a browser.)

## ⚠️ Before going live — client to complete
1. **Legal:** replace the footer placeholders with the real **MOH advertising-permit + facility licence numbers** (the site is legally a medical “advertisement” and needs MOH Drug Inspection Dept approval — confirm with local counsel).
2. **Doctors:** confirm each name/title/credential is factual and licence-backed; swap monogram tiles for consented, MOH-cleared headshots.
3. **Photography:** optionally drop real photos of the clinic *space* (not patients) into the `[data-photo]` slots.
4. **Confirm** the WhatsApp number and the **Dubai branch** status before promoting it.

---
© 2026 Bato Medical Clinic.
