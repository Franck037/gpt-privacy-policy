---
name: awesome-design-md
description: Library of 74 ready-made DESIGN.md design-system analyses inspired by well-known websites (Stripe, Linear, Apple, Vercel, Notion, Airbnb, Tesla, Spotify, Figma, Supabase...). Use when the user asks for a page, UI or redesign "in the style of" / "like" / "inspired by" one of these brands, wants a ready-made design system or DESIGN.md to start from, or asks which brand styles are available.
---

# Awesome DESIGN.md

Vendored from [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md) (MIT, see `LICENSE`).
Each file in `designs/` is a DESIGN.md (Google Stitch format): YAML front matter with design tokens
(colors, typography, spacing, radii, components) followed by prose guidance on layout, depth,
components, responsive behaviour and do's / don'ts.

## How to use

1. Pick the file matching the brand the user names: `designs/<brand>.md`. If they describe a vibe
   instead of a brand, propose 2-3 fitting candidates from the list below and let them choose.
2. Read the whole file before writing UI code. Use its tokens (hex values, font stacks, sizes,
   radii, spacing) as the source of truth; do not invent new ones.
3. To give a project a persistent design system, copy the file to `DESIGN.md` at the project root.
4. These are *inspired-by* analyses, not official brand kits. Do not reuse the brand's logo,
   name or proprietary assets on the user's page; proprietary fonts (e.g. Sohne, SF Pro) need a
   licensed or open-source fallback, which the font stacks usually already list.

## Available designs

**AI & dev tools:** claude, cohere, composio, cursor, elevenlabs, expo, hashicorp, lovable, minimax,
mintlify, mistral.ai, ollama, opencode.ai, posthog, raycast, replicate, resend, runwayml, sanity,
sentry, supabase, together.ai, vercel, voltagent, warp, x.ai, clickhouse, mongodb

**Productivity & SaaS:** airtable, cal, clay, figma, framer, intercom, linear.app, miro, notion,
slack, superhuman, webflow, zapier

**Fintech & crypto:** binance, coinbase, kraken, mastercard, revolut, stripe, wise

**Consumer & media:** airbnb, apple, meta, nike, pinterest, spotify, starbucks, theverge, uber, wired

**Automotive:** bmw, bmw-m, bugatti, ferrari, lamborghini, renault, spacex, tesla

**Hardware, gaming & retro:** dell-1996, hp, ibm, nintendo-2001, nvidia, playstation, shopify, vodafone
