# Timefull Capital — LP Intelligence Map

A clean, private dashboard for tracking LP archetypes and contacts for Fund I.

## Deploy to Vercel (free, 2 minutes)

1. Go to [vercel.com](https://vercel.com) and sign up / log in
2. Click **Add New → Project**
3. Upload this folder, or push it to a GitHub repo and import it
4. Click **Deploy** — no build settings needed

That's it. Your LP map is live at a private Vercel URL.

## Features

- **11 LP Archetypes** from the fund thesis, each with full descriptions and priority tags (Anchor / Priority)
- **Contact management** — add LP names, organizations, emails/LinkedIn, and pipeline status per archetype
- **Live sidebar stats** — total LPs tracked, archetypes engaged, fund parameters
- **Export to JSON** — download all LP data at any time
- **Persistent storage** — all data saved in browser localStorage (private to your device)

## LP Archetypes included

1. Gender-Lens & Inclusive Capitalism LPs ★ Anchor
2. Latino / LatinX Diaspora Capital — Priority
3. Emerging Manager Programmatic Allocators — Priority
4. AI-Native Tech Family Offices — Priority
5. Women Decision-Maker Networks & CIOs ★ Anchor
6. Creator Economy & Sports-Connected Investors
7. Digital Health & Biotech-Adjacent LPs
8. Survivor-Turned-Investor Operator LPs
9. DPI-Liquidity Focused Family Offices
10. Draper Ecosystem & Singularity University Insiders ★ Anchor
11. LatAm Cross-Border High-Net-Worth Investors

## Pipeline Status Colors

- ⚫ Prospect — identified, not yet contacted
- 🔵 Outreach — initial message sent
- 🟡 Meeting — call or meeting scheduled
- 🟢 Committed — verbal or signed
- 🔴 Passed — declined

## Notes

Data is stored in your browser's localStorage. To share data across devices, use the **Export JSON** button and import it manually into another browser. For a shared/team version with cloud sync, a Supabase free-tier backend can be added.
