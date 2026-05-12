# Three Tomorrows, website redesign prototype

A static HTML prototype of the repositioned threetomorrows.com. Built on 12 May 2026.

## What's here

- `index.html` - Homepage
- `about.html` - About Val and Three Tomorrows
- `approach.html` - The design partner approach (Discover, Co-Design, Pilot, Scale)
- `contact.html` - Calendar and contact details
- `services/index.html` - Services overview (four service cards)
- `services/fractional.html` - Fractional AI & Digital Lead
- `services/co-design.html` - AI Co-Design Sprints
- `services/training.html` - AI Leadership Training (Mindset, Skillset, Toolset)
- `services/workflows.html` - AI Workflows & Solutions
- `styles.css` - Shared stylesheet for all pages

## Positioning

**Headline:** Building AI-Native Businesses.
**Subhead:** Bringing AI Mindsets, Insights & Adoption.

Three Tomorrows is repositioned from "practical futurist consultancy" to a sharp, AI-focused practice for Australian mid-market leaders. ESG, sustainability, Web3 as a marquee service are dropped.

## Audience

Primary: Aware-but-Stuck CEOs of Australian $10M-$100M businesses.
Secondary: L&D and leadership development partners (served via the Training page).

## To view locally

Open `index.html` in any browser. All assets are inline or loaded from CDN (Google Fonts). No build step required.

## To push to GitHub (when ready)

The prototype is repo-ready. To turn it into a live site via GitHub Pages:

```
cd "/Users/val/Documents/Claude Cowork/Second Brain OS/Projects/three-tomorrows/website-redesign"
git init
git add .
git commit -m "Initial prototype: AI-native repositioning"
gh repo create <username-or-org>/threetomorrows-website-2026 --public --source=. --push
gh repo edit --enable-pages --pages-branch main
```

The live URL will be `<username>.github.io/threetomorrows-website-2026/` once Pages is enabled.

## Verification flags

Things to sanity-check before going live:

1. **Operator brand list** - "Disney, ESPN, AFL, Optus, Ten Digital, SBS, ABC, ninemsn, JamTV, Norg.ai" is pulled from the fractional one-pager. Confirm Optus and JamTV inclusion.
2. **Stats** - "20+ yrs, 3M+ monthly users, 6.5M CRM records, 1.3M Footytips" pulled from the same source. Confirm these are the canonical numbers.
3. **CEO AI OS beta** - Page says "currently in closed beta" without naming a number. Vault has 3-4 participants (Sarah Veo, Synth, approaching Cam McFarlane).
4. **Training stats** - Stanford 77%, MIT NANDA 95%, KPMG #1/31% v 26%, 35% v 42%. Pulled from Maximus deck. Re-verify against source documents before live.
5. **Norg.ai framing** - "The Australian GEO platform Three Tomorrows partners with" appears across multiple pages. Confirm this aligns with the MoU.
6. **Insights cards (homepage)** - Three placeholder cards with mocked headlines. Replace with real Substack posts pulled from RSS when production-ready.

## Style compliance check

- Zero em dashes (— or –). Scanned and clean.
- Australian English throughout (organise, prioritise, recognise).
- No "leverage", "synergise", "delve", "underscore", "pivotal", "value proposition", or other banned phrases. Scanned and clean.
- Active voice. Direct claims. Customer-pain quotes left in italics on the homepage tiles.

## Next steps for the production build

1. Replace placeholder portrait on About page with real photo.
2. Wire the Insights section to the Substack RSS feed.
3. Embed the real Cal.com (or similar) calendar widget on Contact.
4. Add the Disruption by Design Substack URL (currently `#` placeholder).
5. Restore the animated aurora hero (current prototype uses a static gradient treatment).
6. Add favicon, social cards (Open Graph image), and analytics.
7. Port content into Payload CMS if you're keeping the existing stack.
