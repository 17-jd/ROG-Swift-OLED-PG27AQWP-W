# ROG·SOURCE — Find an ASUS ROG Dealer in India

A simple, graphic website that helps an IT buyer in **Surat, Gujarat** find dealers
for two ASUS ROG products and **call them in one tap** — with full "dossier" pages
behind clickable links for everything we collected (specs, all prices, reviews, sources).

1. **ROG Swift OLED PG27AQWP-W** — 26.5" QHD 540 Hz Tandem WOLED gaming monitor (White)
2. **ROG Rapture GT-BE19000AI** — Tri-band Wi-Fi 7 "AI" gaming router (White)

## How to open

Open **`index.html`** in any browser. It opens with a **country picker** — choose
**India / UAE-Dubai / China** — and lands on that country's page with its local dealers,
official ASUS purchase links and pricing. Each product links to a full "dossier".

```
index.html    → country picker (India / UAE / China)
india.html    → India: dealers + tap-to-call + official ASUS India links + ₹ pricing
uae.html      → UAE / Dubai: dealers + official links + AED pricing
china.html    → China: official ASUS / ROG China stores (JD / e-store) + ¥ pricing
monitor.html  → full monitor dossier (specs, all regions' prices & dealers, reviews, sources)
router.html   → full router dossier (specs, all regions, reviews, sources)
styles.css    → shared design system (one source of truth for all pages)
```

## Design

Built with the `frontend-design` skill (`anthropics/skills`). The look is a deliberate
"ROG spec-terminal" identity rather than a generic template:

- **Type:** Chakra Petch (squared technical display) + Inter (body) + JetBrains Mono
  (phone numbers, prices, ranks — the data "callsign" treatment).
- **Palette:** graphite `#0C0E13`, ROG signal-red `#FF2452`, electric `#25E5FF`,
  in-stock green `#34E27D`, verify-amber `#FFC24A`.
- **Signature:** angular "contact tags" with monospace callsigns and clip-path CALL
  buttons echoing ROG's slash motif; rank numbers encode price order (1 = cheapest),
  and the #1 pick's call button is the lone red one.

Fonts load from Google Fonts; if offline, the page degrades to system fonts gracefully.
Responsive to mobile, keyboard-focusable, and respects `prefers-reduced-motion`.

## Key findings (snapshot — 28 Jun 2026)

**Monitor — PG27AQWP-W (available in India):** cheapest verified ₹1,27,999 at Computech
Store (+91 70 3939 6969, ships pan-India). Also National PC (Kolkata), PrimeABGB (Mumbai,
out of stock), and wholesale via Nexus Infosys / EliteHubs (Mumbai). Global MSRP $1,099;
no official ASUS India MRP. **UAE alternative:** Al Ershad (Bur Dubai, +971 52 902 3208,
~AED 4,459) and Adarc Computer (Abu Dhabi, +971 2 676 3999, AED 6,999 in stock).

**Router — GT-BE19000AI (NOT yet sold in India):** global MSRP $899.99; no India price.
Best India path is import / B2B special-order (strongest lead: Cirqube Systems, Pune).
**UAE alternative — it IS sold there:** Buy4Less (Dubai, +971 55 253 0853, AED 3,608 in
stock); also Sharaf DG (~AED 3,499) and Amazon.ae. Don't confuse it with the older
GT-BE19000 (Black, non-AI).

**China:** Monitor is sold officially (国行) — ASUS e-store ¥8,999, JD.com ¥8,499 (¥7,955
JD PLUS); CN name 华硕 ROG 超杀 27 Pro 二代. Router has no domestic SKU — only JD Worldwide
cross-border import (~¥11,576). Don't confuse it with the GT-BE96AI ("ROG 八爪鱼 7 AI"),
a different model that *is* sold in China.

## Honesty note

**No contact details were fabricated.** Public numbers are shown as-is; IndiaMART-gated
numbers are marked "hidden"; directory-only numbers (the Surat router dealers) are flagged
**"verify number on call"** — never guessed. Every dossier section links to its source, and
unverifiable items are listed explicitly. Prices and stock change weekly — always confirm
the price, exact model, and GST invoice with the seller before paying.

## Data sources

ASUS press / ROG official · TFTCentral · RTINGS · Dong Knows Tech · Tom's Hardware ·
Newegg · Best Buy · Computech Store · National PC · PrimeABGB · Nexus Infosys · EliteHubs ·
IndiaMART · TradeIndia · ASUS store locator.
