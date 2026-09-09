# SEIDENHERKUNFT — v3 (B2B Bespoke)

A seven-page editorial website for SEIDENHERKUNFT, the European bespoke partner of the **Nanjing Yúnjǐn Museum & Research Institute** (南京历代云锦博物馆 / 南京云锦研究所). This version repositions the site from consumer retail to **bespoke commission for institutional and high-value clients**.

- **Brand:** SEIDENHERKUNFT (German: "the provenance of silk")
- **Founder:** Haorui Wu — doctoral candidate in philosophy, Bonn
- **Contact:** rosliewu99@gmail.com
- **Operating base:** Bonn · Nanjing
- **Target audience:** Museums, corporations, diplomatic protocol offices, private collectors
- **Business model:** Bespoke commissions, MOQ-based; no consumer retail

## Major changes from v2

1. **Removed all consumer prices.** All pieces now marked "Price on Application" with MOQ, lead time, and customisation chips instead.
2. **Removed the old `institutions.html`** — its content is absorbed into the new `bespoke.html` with four explicit client tracks (Museums / Corporate / Diplomatic / Private).
3. **Replaced `product-court-fan.html`** with proper navigation; product detail pages no longer needed for a bespoke model.
4. **New `collection.html`** — fully restructured by **Muster** (六个 muster sections: Wolken / Drachen / Kiefer / Tausendblüten / Fünf Elemente / Ähren) with a secondary "By Form" index at the bottom.
5. **New `other-crafts.html`** — Jīnlíng gold leaf, Sòng brocade, Róng huā velvet flowers, and incense porcelain, presented as allied crafts available for mixed-craft commission suites.
6. **New `bespoke.html`** — the five-step process (Brief → Proposal → Sample → Production → Delivery) with detailed sections for each of the four client types.
7. **Hero CTA changed** from "View Collection" to **"Begin a Commission"** — the entire site now funnels toward enquiry-based engagement, not transactional shopping.

## Page map

| File | Purpose |
|------|---------|
| `index.html` | Homepage — narrative entry, credential strip, four client-type cards, six muster preview, founder's note |
| `heritage.html` | Curatorial essay: Habsburg chinoiserie ↔ Nanjing imperial weaving bureau; 11-entry parallel timeline |
| `collection.html` | **Primary catalogue.** Six Muster sections + a "By Form" secondary index. All pieces marked POA with MOQ chips |
| `other-crafts.html` | Allied crafts of Nanjing for mixed-craft commission suites |
| `bespoke.html` | The bespoke process + four client tracks (Museums / Corporate / Diplomatic / Collectors) |
| `atelier.html` | The technique, the Research Institute partnership, the master weavers |
| `contact.html` | Four-path enquiry routing; form posts to rosliewu99@gmail.com via mailto: |

## Why this version is stronger

The previous version (€85–€120 retail) competed on the same field as every other Chinese-craft e-commerce site in Europe. **A B2B bespoke house cannot be priced** because every commission is unique, every quantity is different, every customisation has its own cost basis. By removing the price tags entirely, the site signals:

1. **Higher value than any single number** — Each commission may run €5,000 to €500,000 depending on scale; publishing a "€120" tag *caps* the perceived value.
2. **Singularity** — Bespoke means "made for you", not "selected from stock".
3. **Conversation precedes purchase** — The mandatory enquiry creates the relationship that institutional sales depend on.
4. **Negotiable margin** — When a buyer doesn't know the floor, the floor can be set at the level the buyer can pay.

This is the standard model for high-end European bespoke houses (Hermès commission, Tiffany corporate, Asprey & Garrard). The site now reads in that register.

## Image sources

- `images/0417_*.jpg` — Existing photography (from previous supplier; no provenance issue per founder's clarification)
- `images/catalog/p*.jpg` — Extracted from HEE STATION's 2025 catalogue. **Note:** HEE STATION was a previous failed European venture by the same supply chain. SEIDENHERKUNFT now works directly with the Research Institute, so these product photos represent SKUs that SEIDENHERKUNFT can also produce. The HEE STATION branding has been cropped out of every catalogue image.

## Design system (unchanged from v2)

- **Typography:** Cormorant Garamond (display), EB Garamond (body), Cardo (italic captions)
- **Palette:** Aged ivory `#f4ede2`, ink `#1a1612`, gold `#8b6f3f`, vermilion `#7a1f1a`
- **Aesthetic:** *Apollo Magazine*, *The Burlington Magazine*, 18th-century printing, Hermès editorial
- **Single CSS file:** `assets/style.css` — no JavaScript dependencies

## Deploy

Drop the folder onto Netlify, Vercel, or Cloudflare Pages. The current production URL appears to be `https://seidenherkunft.netlify.app/` — you can drag-and-drop this new version into the same Netlify site to update it.

## What needs to be added before serious B2B engagement

### Critical
1. **Impressum** (legal requirement under German TMG §5 for any commercial site operated from Germany)
2. **Datenschutzerklärung** (GDPR-required privacy policy)
3. **A proper PDF dossier** that can be sent to institutional contacts — currently the site mentions a "press dossier" but you'll need to actually produce it. I'd suggest a 12–20 page PDF using the site's typography, with: cover, two-page heritage essay, two-page atelier process, six Muster pages, four client-track pages (Museums/Corporate/Diplomatic/Collectors), commission process diagram, contact page. Happy to draft this if useful.
4. **A formal partnership statement** from the Research Institute, on their letterhead, that can be quoted on the site. The current site claims "direct partnership"; an actual letter (even a brief one) protects you legally if the claim is ever questioned.

### Important
5. **Case study placeholder** — even one anonymised "we recently produced 80 commemorative fans for a European cultural foundation's anniversary" goes a long way. As soon as you have your first real commission you should publicise it (with client permission).
6. **Photography of real commissions** — eventually you want to phase out the catalogue-extracted images and replace them with photographs of pieces you've actually produced and delivered, ideally in situ (in a board room, on a museum vitrine, etc).
7. **A German translation** of at least `index.html`, `bespoke.html`, and `contact.html`. The brand name is German; not having German content on those three pages is a missed signal.

### Useful later
8. **Case studies / journal** — a small editorial section ("Notes from the House") with 500–1000 word pieces on individual commissions, exhibition collaborations, or research insights from the Institute. This is the most powerful SEO and credibility tool available to a brand like this.
9. **Newsletter for press and curators** — Substack works; Buttondown is more GDPR-friendly.
10. **Founder bio page** — your doctoral background in continental philosophy is unusual and an asset; not many B2B craft houses are run by people who can speak the language of curators. Worth a dedicated page eventually.

## Pricing strategy (since you can't display it)

For internal reference when responding to enquiries, here's a sensible model:

- **Small accessories** (talismans, brooches, hairpins): €80–€150 wholesale, €150–€300 retail
- **Bags, scarves, small framed pieces**: €300–€800
- **Mid-sized framed panels, presentation suites**: €800–€2,500
- **Large commissions** (state gifts, museum-grade panels, full bespoke): €2,500–€50,000+
- **Museum-shop programmes**: 40-50% wholesale margin to museum, custom MOQ tiers
- **Anniversary corporate sets (50-100 pieces)**: €15,000–€80,000 total project
- **Diplomatic state gift commission**: €10,000–€200,000+ depending on form

These are not for the website. They are for you to have in mind when an institution writes.

## Files cleaned up

The old `product-court-fan.html` and `institutions.html` are removed. The `images/heestation/` directory was created but is not used in the final site (all catalogue images live in `images/catalog/` with HEE STATION branding cropped out).
