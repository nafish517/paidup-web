# Punnk Pay — Marketing Landing Page

> **Just professional invoices. No bloat. No surprise price hikes.**

This repository contains the **marketing / landing site** for the [Punnk Pay](https://play.google.com/TODO) Android app — an offline-first invoicing app for freelancers and solo businesses, by **PunkZero Labs**.

---

## What this site is (and isn't)

✅ A static marketing landing page — hero, features, pricing, trust, CTA  
❌ Not a working web invoice app  
❌ Not a cloud companion that syncs phone data  

---

## Stack

- Plain HTML + CSS + vanilla JS (zero dependencies)
- Fonts: Space Grotesk (headings) + DM Sans (body) via Google Fonts
- Images: `/assets/` (generated from brand spec)
- Fully static — no build step required

---

## Open locally

Just open `index.html` in any browser:

```bash
# Option 1 — open directly
start index.html

# Option 2 — simple local server
npx serve .
# or
python -m http.server 8080
```

---

## Deploy to GitHub Pages

1. Push to `main` branch (already done)
2. Go to **Settings → Pages → Source: main / (root)**
3. Site will be live at: `https://nafish517.github.io/paidup-web/`

---

## TODO before publishing

- [ ] **Replace all `#TODO_PLAY_STORE_URL` with the real Google Play Store URL**  
  Search for `TODO_PLAY_STORE_URL` in `index.html` — there are 5 occurrences (nav, hero, pricing ×3, CTA banner).
- [ ] Add real Privacy Policy and Disclaimer pages (currently placeholder links)
- [ ] Optionally add real emulator screenshots to `/assets/` to replace generated mockups

---

## Brand

| Token | Value |
|-------|-------|
| Background | `#1E232C` |
| Surface | `#2A2F3A` |
| Neon Lime (primary) | `#B0F152` |
| Brand Lime (launcher) | `#A4D62B` |
| Teal | `#00E5BC` / `#00B59C` |
| On-lime text | `#1A1F28` |

Launcher icon: split lime `#A4D62B` | teal `#00B59C` background + white invoice mark with dollar sign.

---

## Product facts

- **Public name:** Punnk Pay
- **Package:** `com.paidup.app`
- **Studio:** PunkZero Labs
- **Free tier:** 5 invoices/month, 1 template, footer branding
- **Pro:** Unlimited, all templates, custom logo, no footer — $4.99/mo · $29.99/yr · $59.99 lifetime
- **Trust principles:** historical invoices never locked, no ads in workflow, data export always available, restore purchases works

---

*A PunkZero Labs product.*
