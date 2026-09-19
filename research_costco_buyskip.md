# RESEARCH DOSSIER: COSTCO CANADA — BUY vs SKIP

Working title: "10 Costco Canada Items Actually Worth It (And 5 That Aren't)"
Reference: Canada Food Insider, "10 Costco Canada Items That Are Actually Worth It - BUY vs SKIP (MAY 2026)" — 104,007 views, 13:52. Full script supplied by the user and read 100%. Structure map: scratchpad/note_costco_buyskip_structure.md

**WHY THIS TOPIC.** Costco money-decision content is the only category that clears a two-independent-channel test above 100K in Canada. Canadian Counter's own "Don't Renew Your Costco CANADIAN Membership Until You Watch This" did 235,602 — the channel's number two video. North America Crisis Radar's version of the same title did 143,227, and that is a channel whose Canadian honey video did 291 views. The buy/skip variant is proven at 104,007 and Canadian Counter has never made one. US ceiling on the format: 1,070,563.

**THE USER'S INSTRUCTION.** Everything current as of September 2026. The reference video's prices are from May. Every price in this package is re-pulled live.

**FOUR OF THE REFERENCE VIDEO'S CLAIMS DO NOT SURVIVE** — see Part 2 sections A1, A3, C1, B2 and E2. The rotisserie chicken loss figure is a mis-statement of a real 2015 quote. The Premier Protein supplier claim has no source at all. The Cheezies exclusivity claim cannot be supported. And its electronics SKIP verdict is contradicted by Costco Canada's own published warranty and return terms — and by its own top comment.

**THE BIGGEST STRUCTURAL RISK IS AI-SLOP PERCEPTION.** The top comment on the 143,227-view competitor is "i feel sick..AI slop" with 61 likes. Canadian commenters caught right-hand-drive vehicles in B-roll and English-only packaging on products sold in Canada. Any footage used here must be right-hand-drive-free and must show bilingual packaging.

---

# PART 1 DOSSIER — COSTCO CANADA: LIVE PRICES AND COMPARISONS (19 SEPT 2026)

**All Costco prices below were captured directly from costco.ca on 19 September 2026** (server timestamps on the API responses read `2026-09-19T23:xx:xxZ`). Competitor prices were captured the same day where capture was possible at all.

---

## 0. READ THIS BEFORE USING ANY NUMBER — THE ONE CRITICAL METHOD FINDING

The method note was correct: **costco.ca is retrievable**. Its product pages carry `application/ld+json` with `priceCurrency: CAD`, and — better — a deeper embedded payload containing a `priceInfo` object. I extracted that deeper object because **the JSON-LD `price` field is the pre-discount price, not the price you pay today.**

Worked example, Charmin Ultra Soft 30 × 200 sheets (item 2633624), captured 19 Sep 2026:

```
"displayPrice":{"onlinePrice":39.99,"aggregatedDiscountAmt":6.5,"deliveredPrice":33.49,"currency":"CAD"}
```

JSON-LD alone would have reported **$39.99**. The live price is **$33.49**. Every price in this dossier is the `deliveredPrice` (the live price), with the regular price and the discount shown separately.

**Second, larger caveat — the label on these pages says "Online Price", not "Warehouse Price".** The costco.ca page template contains both labels and a tooltip reading *"This is the price of the item sold at your selected Costco Warehouse. Warehouse pricing may vary."* The pages I scraped render the **Online Price**, and the shipping block states *"Standard shipping via UPS is included in the quoted price."* So these are delivered-to-door prices, not shelf prices.

I found hard evidence the two differ, and evidence they sometimes don't:

| Item | costco.ca online (19 Sep) | Costco in-warehouse savings booklet (31 Aug – 28 Sep) | Gap |
|---|---|---|---|
| Hellmann's Real Mayonnaise | $13.99 | $9.49 (regular $11.99, SAVE $2.50) | Online is **$2.00 above the warehouse regular price** |
| Tim Hortons Original Blend coffee | $39.99 | $39.99 (regular $54.99, SAVE $15) | Identical |

**Consequence for the video:** the online/warehouse gap is real but inconsistent, so it cannot be modelled with a flat adjustment. **Every price in this dossier must be re-verified in warehouse on camera.** That instruction is attached to every single line below and is not boilerplate here — it is the load-bearing caveat of Part 1.

---

## 1. PRIMARY SOURCE MECHANICS (so Part 2 can reproduce this)

| Route | Result |
|---|---|
| `costco.ca/sitemap_lw_index.xml` → `sitemap_lw_p_001.xml` | **WORKS.** 7,897 product URLs, `lastmod` 2026-09-17. This is the full costco.ca *online* catalogue. |
| Product page `application/ld+json` | **WORKS.** Name, item number (`sku`), price, currency, availability. |
| Embedded `priceInfo` / `displayPrice` block | **WORKS.** `onlinePrice`, `aggregatedDiscountAmt`, `deliveredPrice`. This is the good one. |
| Product `productAttributes` → `"key":"Model"` | **WORKS.** Manufacturer model numbers for electronics. |
| `gdx-api.costco.com/catalog/search/api/v1/search` | **BLOCKED.** HTTP 400 / Apigee gateway fault. |
| `gdx-api.costco.com/catalog/product/product-api/v2/products` | **BLOCKED.** HTTP 403. |
| `search.costco.ca` Lucidworks keyword pipeline | **BLOCKED.** HTTP 403 "not authorized". |
| costco.ca search results page | Client-rendered; results are **not** in the HTML. Use the sitemap instead. |

**What is NOT in the online catalogue** (checked by exhaustive search of all 7,897 URLs): rotisserie chicken, Costco bakery muffins/croissants/cakes, fresh eggs, fresh butter, fresh milk, fresh raw meat, Hawkins Cheezies, French's mustard, food court items, gasoline. These are warehouse-only and **have no obtainable online price. They must be filmed in store.**

**Costco Business Centre (costcobusinesscentre.ca) — attempted and failed.** Its sitemap works (2,126 products, and it *does* stock French's mustard, loose eggs by the 15-dozen, butter, KS Premium Bacon 4×500 g, KS Real Mayonnaise 1.9 L). But every product page returns `"priceInfo":"$undefined"` and JSON-LD with `priceCurrency: CAD` and **no `price` field at all** — Business Centre publishes no price without a business delivery address. Its own page text states *"All prices listed are delivered prices from Costco Business Centre. Orders under $250 (before tax) will be charged a $25 delivery surcharge."* **No Business Centre price is usable, and Business Centre pricing is a different store format from the regular warehouse anyway — do not present it as a Costco warehouse price.**

---

## 2. THE "WORTH IT" CANDIDATES — COSTCO.CA PRICES, 19 SEPT 2026

All tier **(a) CONFIRMED primary — costco.ca product page, captured 19 Sept 2026**. All: **re-verify in warehouse on camera.**

### 2.1 Maple syrup

| Item | Size | Item # | Price 19 Sep 2026 | Per L | URL |
|---|---|---|---|---|---|
| Kirkland Signature Maple Syrup | 1 L | 118263 | **$17.99** | $17.99 | costco.ca/kirkland-signature-maple-syrup,-1-l.product.100546387.html |
| Kirkland Signature Organic Maple Syrup | 1 L | 679131 | **$18.99** | $18.99 | costco.ca/kirkland-signature-organic-maple-syrup,-1-l.product.100417609.html |

Declared label facts (from the page, no commentary): *"Canada Grade A - Amber, Rich Taste, 100% pure maple syrup, 1 L."*
**Re-verify in warehouse on camera.**

### 2.2 Frozen chicken breasts — THE SPECIFIC ITEM DOES NOT EXIST ONLINE

There is **no Kirkland Signature boneless-skinless individually-frozen chicken breast** in the costco.ca catalogue. What is there:

| Item | Size | Item # | Price 19 Sep 2026 | Per kg | URL |
|---|---|---|---|---|---|
| Yorkshire Valley Farms Organic Boneless Skinless Chicken Breasts | 5 × 2 kg (10 kg) | 1842261 | **$279.99** | $28.00 | .../yorkshire-valley-farms-organic-boneless-skinless-chicken-breasts,-5-×-2-kg.product.4000284912.html |
| Sunrise Farms Frozen Seasoned Chicken Breast | 4 kg | 258929 | **$46.99** | $11.75 | .../sunrise-farms-frozen-seasoned-chicken-breast,-4-kg.product.100549058.html |
| Kirkland Signature Lightly Breaded Chicken Breast Chunks | 1.8 kg | 1736931 | **$26.99** | $14.99 | .../kirkland-signature-lightly-breaded-chicken-breast-chunks,-1.8-kg.product.4000309695.html |
| Kirkland Signature Chicken Breast, Canned | 6 × 354 g | 51070 | **$24.99** | $11.77 | .../kirkland-signature-chicken-breast-canned,-6-×-354-g.product.100413547.html |

**The plain KS frozen chicken breast is a warehouse-only item. Film the price and the bag weight in store.** Tier (a) for the four above; the KS IQF breast itself is **UNVERIFIED**.

### 2.3 Olive oil — all Canadian formats

| Item | Size | Item # | Price | Per L | URL slug |
|---|---|---|---|---|---|
| KS 100% Italian Extra Virgin Olive Oil | 2 L | 71003 | **$31.99** | **$15.99** | ...100799154 |
| KS 100% Spanish Extra Virgin Olive Oil | 3 L | 4249003 | **$36.99** | **$12.33** | ...100799194 |
| KS Organic Extra Virgin Olive Oil | 2 L | 692731 | **$21.99** | **$10.99** | ...100416825 |
| KS Olive Oil (not EV) | 3 L | 1554830 | **$30.99** | **$10.33** | ...100416749 |

**On-screen point:** within Costco's own shelf, the Italian EVOO costs **46% more per litre than the Spanish** ($15.99 vs $12.33) and **45% more than the Organic EVOO**. That arithmetic is internal to Costco and does not depend on any competitor. **Re-verify in warehouse on camera.**

### 2.4 Hawkins Cheezies multi-pack — NOT OBTAINABLE FROM COSTCO

Zero matches across all 7,897 costco.ca product URLs and all 2,126 Business Centre URLs. **Pack count and price must be filmed in store.** See §4 for the only current competitor prices I could get.

### 2.5 Laundry detergent — pods and liquid

| Item | Size | Item # | Price | Per load | URL slug |
|---|---|---|---|---|---|
| KS Ultra Clean Laundry Detergent Pacs | 152-count | 1054838 | **$31.99** | **$0.211** | ...4000200504 |
| KS Oxi Power Premium Laundry Detergent Pacs | 110-count | 2675962 | **$29.99** | **$0.273** | ...4000325154 |
| KS Ultra Clean Premium Liquid Detergent | 146 wash loads | 1845613 | **$24.99** | **$0.171** | ...100388606 |
| KS Free and Clear Ultra Clean Liquid | 146 wash loads | 1845621 | **$24.99** | **$0.171** | ...100388598 |
| KS Oxi Powder Laundry Booster | 5 kg | 1707952 | **$21.99** | n/a | ...4000391701 |
| KS Ultrafresh Premium Fabric Softener | 276 loads | 1045021 | **$19.99** | **$0.072** | ...4000237810 |

Declared label facts: liquid is *"2× as concentrated"*, *"Up to 146 wash loads"*; pacs are *"HE compatible"*.
**On-screen point:** KS liquid is **$0.171/load** vs KS pacs at **$0.211/load** — the pods cost 23% more per load than the liquid, same brand, same shelf. **Re-verify in warehouse on camera.**

### 2.6 Rotisserie chicken — THE $7.99 IN THE SCRIPT IS NOT CONFIRMED

Not in the costco.ca catalogue. No primary price exists.

| Tier | Source | Claim | Date |
|---|---|---|---|
| **(d) DOCUMENTED media record — STALE, DO NOT STATE AS CURRENT** | Narcity, "I compared rotisserie chickens from Costco, Loblaws and Metro" — narcity.com/toronto/taste-tested-compared-rotisserie-chicken-costco-loblaws-metro | Costco **$9**, ~1.2 kg bird; Loblaws **$13**, ~900 g; Metro **$13.99**, ~1,000 g | Published **20 May 2026** |

**The reference script's $7.99 is contradicted by the most recent named-outlet record I can find, which says $9 as of May 2026 — and May 2026 is four months stale.** Do not put either number on screen. **Film the shelf tag.** The Narcity Loblaws/Metro figures are the only rotisserie comparison numbers in existence for this project and they are also stale — treat as a filming shopping list, not as a claim.

### 2.7 Protein bars

| Item | Pack | Item # | Price | Per bar | URL slug |
|---|---|---|---|---|---|
| KS Protein Bars | 20-count | 1014809 | **$38.99** | **$1.95** | ...100417020 |
| KS Chewy Protein Bars | 42 × 40 g | 1377067 | **$22.99** | **$0.547** | ...100713037 |
| KS Nut Bars | 960 g / 24 bars, 40 g each | 1181556 | **$20.99** | **$0.875** | ...100560191 |

Bar weight for the 20-count is **not declared on the page** — do not state a gram figure for it; read it off the box on camera. Declared label facts for the 20-count: *"New formulation, Made with real chocolate, No artificial flavours."*
**On-screen point:** the 20-count bar costs **3.6× per bar** what the 42-count Chewy bar costs, both Kirkland Signature. **Re-verify in warehouse on camera.**

### 2.8 Bath tissue / toilet paper — the unit arithmetic is decisive

| Item | Rolls | Sheets/roll | Total sheets | Item # | Price | Per roll | Per 100 sheets |
|---|---|---|---|---|---|---|---|
| **KS 2-ply Bath Tissue, 30-pack** | 30 (5 packs of 6) | **380** | 11,400 | 6262016 | **$32.99** | $1.100 | **$0.289** |
| **KS Ultra Soft 2-ply Premium, 36-pack** | 36 (4 packs of 9) | **231** | 8,316 | 1725952 | **$37.99** | $1.055 | **$0.457** |
| Charmin Ultra Soft Jumbo, 30-pack | 30 | 200 | 6,000 | 2633624 | **$33.49** (reg $39.99, disc $6.50) | $1.116 | **$0.558** |
| Cashmere Premium Soft & Thick, 40-pack | 40 | not declared | — | 1424970 | **$29.49** (reg $34.99, disc $5.50) | $0.737 | n/a |

Both KS products declare *"MADE IN CANADA, 2-ply, Septic safe."*

**This is the best single piece of arithmetic in the dossier.** The "Ultra Soft *Premium*" Kirkland product costs **58% more per sheet** than the plain Kirkland product ($0.457 vs $0.289 per 100 sheets), because it has 231 sheets per roll against 380. Per *roll* it looks cheaper. Per *sheet* it is much more expensive. Both numbers are printed on Costco's own page. **Re-verify in warehouse on camera — and film the sheet counts on the packaging, because that is the whole point.**

### 2.9 Coffee — every blend and format stocked

| Item | Size | Item # | Price | Per kg | Per pod |
|---|---|---|---|---|---|
| KS Dark Colombian Ground Coffee (dark roast, fine grind, Supremo beans) | 1.36 kg | 15071 | **$33.99** | **$24.99** | — |
| KS Decaffeinated Dark Roast Fine Grind | 1.36 kg | 17996 | **$36.99** | **$27.20** | — |
| KS French Roast Whole Bean (dark) | 1.13 kg | 1528787 | **$29.99** | **$26.54** | — |
| KS Whole Bean Espresso Blend (dark) | 1.13 kg | 1726068 | **$28.99** | **$25.65** | — |
| KS Whole Bean House Blend (medium-dark) | 1.13 kg | 1726089 | **$27.99** | **$24.77** | — |
| KS Organic Breakfast Blend K-Cup Pods (light) | 120-count | 4272377 | **$49.99** | — | **$0.417** |
| KS Organic Pacific Bold K-Cup Pods (dark) | 120-count | 4272378 | **$49.99** | — | **$0.417** |
| KS Organic Summit K-Cup Pods (medium) | 120-count | 4272379 | **$49.99** | — | **$0.417** |
| KS Organic Decaf K-Cups (light) | 120-count | 4272380 | **$49.99** | — | **$0.417** |
| **Tim Hortons Original Blend Fine Grind** | 1.36 kg | 1019209 | **$39.99** | **$29.40** | — |
| **Tim Hortons Dark Roast K-Cup Pods** | 80-count | 2660661 | **$57.99** | — | **$0.725** |
| **Tim Hortons K-Cup Pods (medium)** | 80-count | 1669669 | **$57.99** | — | **$0.725** |

**The Kirkland vs Tim Hortons comparison the brief asked for, both bought at Costco on the same day:**
- **Ground, like for like, identical 1.36 kg format:** KS Dark Colombian **$24.99/kg** vs Tim Hortons Original **$29.40/kg**. Tim Hortons is **17.6% more per kg**, i.e. **$6.00 more for the same 1.36 kg bag**.
- **Pods:** KS Organic **$0.417/pod** vs Tim Hortons **$0.725/pod**. Tim Hortons is **74% more per pod**.

Note the warehouse booklet has Tim Hortons at $39.99 from a regular $54.99 (SAVE $15, 31 Aug – 28 Sep) — so the Tim Hortons gap is currently at its *narrowest*. Say so on camera. **Re-verify in warehouse on camera.**

### 2.10 Mixed nuts and the wider nut shelf

| Item | Size | Item # | Price | Per 100 g |
|---|---|---|---|---|
| **KS Salted Mixed Nuts** (cashews, almonds, pecans, Brazil nuts, macadamia) | 1.13 kg | 1645578 | **$25.99** | **$2.300** |
| **KS Unsalted Mixed Nuts** (cashews, almonds, pistachios, pecans) | 1.13 kg | 1652577 | **$26.99** | **$2.388** |
| KS Whole Almonds | 1.36 kg | 284601 | $21.99 | $1.617 |
| KS Pistachios | 1.36 kg | 203435 | $27.99 | $2.058 |
| KS Pecan Halves | 907 g | 203444 | $25.99 | $2.865 |
| KS Shelled Walnuts | 1.36 kg | 36285 | $15.99 | **$1.176** |
| KS Roasted Whole Cashews with Salt | 1.13 kg | 1390413 | $23.99 | $2.123 |
| KS Extra-large Peanuts | 1.13 kg | 234994 | $13.99 | $1.238 |
| KS Trail Mix | 1.81 kg | 1474436 | $23.99 | $1.325 |
| **KS Snacking Nuts Variety Pack** | 30 × 45 g (1.35 kg) | 720827 | $31.99 | **$2.370** |

**On-screen point:** the 30-count snack-pack variety box is **$2.370/100 g** — *more* than the big tub of Salted Mixed Nuts at **$2.300/100 g**, for the same brand. You pay a premium for the small bags, not a bulk discount. **Re-verify in warehouse on camera.**

---

## 3. THE "SKIP" CANDIDATES

### 3.1 Kirkland milk chocolate almonds — the $17→$30 claim is NOT SUPPORTED

| Item | Size | Item # | Price 19 Sep 2026 | Per 100 g |
|---|---|---|---|---|
| Kirkland Signature Chocolate Covered Almonds | 1.5 kg | 919999 | **$26.99** | **$1.799** |

Declared label facts: *"Chocolate covered almonds, 1.5 kg (3.3 lb)."* Note the catalogue name is **"Chocolate Covered Almonds"**, not "Milk Chocolate Almonds" — check you are filming the same SKU.

**The reference script's "rose from ~$17 to ~$30" is tier (c) SPECULATION — DO NOT USE.** I found no primary or named-outlet record of the historical price. The current price is $26.99, which matches neither figure. Costco.ca publishes no price history, and I will not reconstruct one from memory or from aggregator sites. If the price-rise story is central to the segment, it needs a dated receipt, a dated photo of a shelf tag, or a named outlet — none of which I could obtain today.

### 3.2 Costco bakery — muffins, croissants, cakes, cookies

**Costco's own in-store bakery items (the 12-pack muffins, the bakery croissants, the sheet cakes, the bakery cookies) are NOT in the online catalogue and have no obtainable price. Film them.**

Packaged bakery-adjacent items that *are* online:

| Item | Size | Item # | Price | Unit price |
|---|---|---|---|---|
| Otis Spunkmeyer Assorted Muffins | 15 × 113 g | 1791422 | **$21.99** | **$1.466/muffin**; $1.297/100 g |
| Pre-Proofed Butter Croissants | 30 units | 402498 | **$17.49** | **$0.583/croissant** |
| Ace Bakery All Butter Mini Cheese Croissant | 560 g | 1891948 | **$11.99** | $2.141/100 g |
| KS Mini Chocolate Chip Cookies | 30 × 28 g (840 g) | 5014935 | **$18.99** | **$2.261/100 g** |
| KS Frozen Chocolate Chunk Cookies | 6 kg | 1455819 | **$36.99** | **$0.617/100 g** |

**On-screen point:** the KS Mini Chocolate Chip Cookies in individual 28 g packs cost **$2.261/100 g**. The KS Frozen Chocolate Chunk Cookies cost **$0.617/100 g** — **3.7× cheaper per 100 g**, same brand, same store. That is a clean skip-list item. **Re-verify in warehouse on camera.**

### 3.3 Name-brand condiments at Costco — this is the strongest skip case in the dossier

| Item | Size | Item # | Costco price 19 Sep | Costco per L |
|---|---|---|---|---|
| **Heinz Ketchup** | 2 × 1.5 L (3 L) | 1920641 | **$13.99** | **$4.66/L** |
| **Hellmann's Real Mayonnaise** | **1.8 L jug** | 170600 | **$13.99** | **$7.77/L** |
| French's Mustard | — | — | **NOT IN COSTCO.CA CATALOGUE — FILM IT** | — |

**Direct like-for-like competitor comparison, same brand, same day (tier (b), see §4 for the source caveat):**

| Comparison | Costco | Walmart Canada | Verdict |
|---|---|---|---|
| Heinz Tomato Ketchup | 2 × 1.5 L = **$13.99** → **$4.663/L** | 1.5 L squeeze bottle **$6.97** → **$4.647/L** | **Walmart is marginally cheaper per litre.** Buying two Walmart bottles = $13.94 vs Costco's $13.99. Costco's bulk ketchup saves **nothing** — it costs 5¢ more. |
| Hellmann's Real Mayonnaise | 1.8 L jug **$13.99** → **$7.772/L** | 890 mL jar **$6.47** → **$7.270/L** | **Walmart is 6.9% cheaper per litre.** The giant Costco jug is *more* expensive per millilitre than a normal supermarket jar. |

**This is the single most quotable finding in Part 1: on two flagship name-brand condiments, the enormous Costco format is not cheaper per unit than the ordinary supermarket bottle.** Note honestly on camera that Costco's *in-warehouse* mayonnaise is currently on a savings-booklet offer at **$9.49** (regular $11.99, 31 Aug – 28 Sep, SAVE $2.50), which at 1.8 L is **$5.27/L — and that version does beat Walmart decisively.** Both facts are true and both belong in the video. **Re-verify in warehouse on camera.**

### 3.4 Costco electronics — three representative TVs with exact model numbers

| Brand / Series | Model number | Screen | Item # | Price 19 Sep 2026 | Declared specs (page text) |
|---|---|---|---|---|---|
| **Sony BRAVIA 2 II — 4K HDR LED** | **K65S20M2** | 65" (64.5" diag.) | 9792065 | **$898.00** | 4K HDR processor X1, Apple HomeKit, Google Assistant, Apple AirPlay, Google Home, Motionflow XR 240 (refresh rate 60 Hz) |
| **Hisense U68SG — 4K QLED Mini LED** | **65U68SG** | 65" (64.5" diag.) | 8986865 | **$897.99** | Quantum Dot Wide Colour Gamut, Alexa, Google Assistant, Google Home, Motion Rate 480 (refresh rate 144 Hz) |
| **LG OLED C6 — 4K UHD OLED** | **OLED55C6PUA.ACC** | 55" (54.5" diag.) | 9502155 | **$2,297.99** | NVIDIA G-Sync compatible, OLED Evo panel, refresh rate 120 Hz, Magic remote |

URLs: `costco.ca/sony-65"-class---bravia-2-ii-series---4k-hdr-led-tv.product.4000379986.html` · `costco.ca/hisense-65"-class---u68sg-series---4k-qled-mini-led-tv.product.4201008451.html` · `costco.ca/lg-55"-class---oledc6-series---4k-uhd-oled-tv.product.4000449975.html`

**On-screen point that needs no competitor data:** at Costco today the 65" Sony is **$898.00** and the 65" Hisense is **$897.99** — one cent apart — while the Hisense declares 144 Hz against the Sony's 60 Hz and adds Mini-LED. And the 55" LG OLED costs **2.6× either 65" set**. Model numbers are given so a price-match can be filmed. **Re-verify in warehouse on camera.**

**I could not obtain competitor prices for these exact model numbers** — see §4. Any "Costco is cheaper on TVs" claim is **UNVERIFIED**.

### 3.5 Other obvious poor-value items I found on costco.ca (my own additions)

| Item | Size | Item # | Price | Unit price | Why it earns a skip slot |
|---|---|---|---|---|---|
| **KS Precooked Bacon** | 500 g | 1527958 | **$24.99** | **$49.98/kg** | The most expensive per-kg food item in this entire dataset. Compare KS Crumbled Bacon at $22.91/kg (item 190316, $12.99/567 g). |
| **Yorkshire Valley Farms Organic BS Chicken Breasts** | 5 × 2 kg | 1842261 | **$279.99** | **$28.00/kg** | A $280 single-line commitment at 2.4× the per-kg price of the Sunrise Farms breast on the same shelf ($11.75/kg). |
| **KS Snacking Nuts Variety Pack** | 30 × 45 g | 720827 | **$31.99** | **$2.370/100 g** | More per gram than the bulk tub of the same brand's mixed nuts. |
| **KS Protein Bars 20-count** | 20 | 1014809 | **$38.99** | **$1.95/bar** | 3.6× the per-bar price of KS Chewy Protein Bars on the same aisle. |
| **KS Ultra Soft 2-ply Premium Bath Tissue 36-pack** | 36 × 231 | 1725952 | **$37.99** | **$0.457/100 sheets** | 58% more per sheet than the plain KS 30-pack. |
| **KS Coastal Cheddar** | 810 g | 1918390 | **$18.99** | **$2.344/100 g** | 80% more per 100 g than KS Marble Cheddar 1.15 kg at $1.303/100 g (item 1154953, $14.99). |
| **KS Mini Chocolate Chip Cookies** | 30 × 28 g | 5014935 | **$18.99** | **$2.261/100 g** | 3.7× the frozen KS cookie dough per 100 g. |

All tier (a), captured 19 Sept 2026. **Re-verify in warehouse on camera.**

---

## 4. COMPETITOR COMPARISONS — WHAT WORKED, WHAT DID NOT, AND WHAT YOU MUST FILM

### 4.1 Retailer access results, tested 19 September 2026

| Retailer | Route attempted | Result |
|---|---|---|
| **Loblaws** | loblaws.ca direct | **HTTP 403 — BLOCKED** |
| **Real Canadian Superstore** | realcanadiansuperstore.ca direct | **HTTP 403 — BLOCKED** |
| **No Frills** | nofrills.ca direct | **HTTP 403 — BLOCKED** |
| **Loblaws group (all banners)** | `api.pcexpress.ca/pcx-bff/api/v1/products/...` mobile/BFF API | **HTTP 401 `invalid_client`** — requires a valid rotating client credential. **BLOCKED** |
| **Walmart Canada** | walmart.ca direct (curl + independent fetch) | **BLOCKED** — returns a "Verify Your Identity / press and hold the button" bot wall on both search and product pages |
| **Metro** | metro.ca online grocery search | **HTTP 403 — CAPTCHA page returned** |
| **Sobeys** | sobeys.com direct | **HTTP 403 — BLOCKED** |
| **Save-On-Foods** | saveonfoods.com direct | **HTTP 403 — BLOCKED** |
| **Voilà** | voila.ca | **Infinite redirect loop (50+ hops) — BLOCKED** |
| **Amazon.ca** | amazon.ca search + product pages (curl + independent fetch) | **HTTP 503 / empty robot-check page — BLOCKED. No Amazon.ca price in this dossier.** |
| **GasBuddy** | gasbuddy.com station pages | **HTTP 403 — BLOCKED** |
| **Flipp (Wishabi)** | `backflipp.wishabi.com/flipp/items/search` and `/flipp/flyers` | **WORKS — the only competitor route that functioned.** |

**Every one of the six named grocers blocks automated retrieval. The brief's prediction held exactly.**

### 4.2 The one route that worked — and its limits

Flipp is the flyer platform operated by Wishabi. Its public endpoints returned (a) **retailers' current scanned flyer items** with explicit validity windows, and (b) an **e-commerce index carrying Walmart Canada's everyday online shelf prices.**

**Why I consider this usable but tier (b), not tier (a):** Flipp is a distribution channel for the retailers' own flyers, not an SEO price-guess site. But it is still an intermediary — I am not reading walmart.ca or loblaws.ca directly. **Every competitor figure below is tier (b) STRONGLY SUPPORTED, not confirmed primary, and every one must be re-shot in store or on the retailer's own shelf.**

Two further limits, stated plainly:
1. **Flyer prices are promotional, not regular shelf prices.** Where the flyer shows a "was" price I have given it.
2. **The Walmart "ecom" figures are everyday online prices** — closer to a fair comparison, but still online rather than in-store.

### 4.3 Competitor prices captured 19 September 2026 — tier (b)

**Postal code used: M5V 3L9 (downtown Toronto). Prices will differ by region — state the region on screen.**

#### Condiments (the clean like-for-like wins)

| Item | Retailer | Price | Unit price | Window |
|---|---|---|---|---|
| Heinz Tomato Ketchup, 1.5 L squeeze bottle | **Walmart Canada** (ecom) | **$6.97** | $4.647/L | everyday, captured 19 Sep 2026 |
| Heinz Tomato Ketchup, 750 mL | Walmart Canada (ecom) | $5.77 | $7.693/L | everyday, 19 Sep 2026 |
| Hellmann's Real Mayonnaise, 890 mL jar | **Walmart Canada** (ecom) | **$6.47** | $7.270/L | everyday, 19 Sep 2026 |
| Hellmann's Real Mayonnaise, 750 mL squeeze | Walmart Canada (ecom) | $6.47 | $8.627/L | everyday, 19 Sep 2026 |
| Hellmann's Real Mayonnaise, 1.42 L jar | Walmart Canada (ecom) | $9.48 | $6.676/L | everyday, 19 Sep 2026 |
| Hellmann's Mayonnaise | **Food Basics** (flyer) | **$5.99** | size not stated on flyer — **unusable without the size. Film it.** | valid 17–24 Sep 2026 |

**Note the Walmart 1.42 L jar at $6.676/L undercuts Costco's 1.8 L jug at $7.772/L by 14%.** That is the sharpest condiment line available. **Re-verify in warehouse / in store on camera.**

#### Toilet paper

| Item | Retailer | Price | Per roll | Window |
|---|---|---|---|---|
| Cashmere Toilet Paper, 30 big rolls = 62 single | **Walmart** (ecom) | **$17.50** | $0.583 | everyday, 19 Sep 2026 |
| Purex, 30 big rolls = 62 single | Walmart (ecom) | $17.96 | $0.599 | everyday, 19 Sep 2026 |
| Great Value Septic Safe, 30 = 100 rolls | Walmart (ecom) | $19.94 | $0.665 | everyday, 19 Sep 2026 |
| Royale Velour 2-ply, 30 = 80 rolls | Walmart (ecom) | $19.96 | $0.665 | everyday, 19 Sep 2026 |
| Charmin Ultra Soft, 30 triple rolls (90 reg. equiv.) | Walmart (ecom) | $30.98 | $1.033 | everyday, 19 Sep 2026 |
| Cashmere Bathroom Tissue 30 = 50 rolls | **FreshCo** (flyer) | **$12.99** (was $19.99, SAVE 35%) | $0.433 | valid **17–24 Sep 2026** |
| PC Bathroom Tissue, 30 = 100 rolls | **Real Canadian Superstore** (flyer) | **$20.00** + 5,000 PC Optimum pts ($5 in points) | $0.667 | valid 17–24 Sep 2026 |
| Royale Bathroom Tissue 15 = 30 rolls | No Frills (flyer) | $5.99 | $0.400 (15 physical rolls) | valid 17–24 Sep 2026 |

**Sheet counts are not published for any of these competitor packs.** Costco's KS 30-pack at **$0.289 per 100 sheets** cannot be honestly compared to them until someone films the sheet counts on the competitor packaging. **Roll-count comparisons here are misleading and I am flagging them as such — the per-sheet comparison is the only valid one and it must be filmed.**

#### Paper towels

| Item | Retailer | Price | Window |
|---|---|---|---|
| SpongeTowels UltraPro, 6 = 12 double rolls | **Walmart** (ecom + flyer) | **$14.77** | everyday / flyer 10 Sep – 22 Oct 2026 |
| Great Value Ultra, 12 rolls × 98 sheets | Walmart (ecom) | $22.94 | everyday, 19 Sep 2026 |
| Black & White, 12 rolls × 183 sheets | Walmart (ecom) | $17.93 | everyday, 19 Sep 2026 |
| Royale Facial Tissue 12×100 **or** Paper Towels 6 = 12 | Real Canadian Superstore (flyer) | $13.00 (SAVE up to 35%) | valid 17–24 Sep 2026 |
| Cashmere 24=48 / SpongeTowels Ultra 6=12 / Scotties 12 | Food Basics (flyer) | $10.98 | valid 17–24 Sep 2026 |
| SpongeTowels Premium, 12 × 106 sheets | **Costco** (own online deal) | **$30.99** (was $36.99) | valid 14–21 Sep 2026 |

Costco's own KS 2-ply Paper Towels 12-pack is **$33.99 = $2.833/roll**, but **Costco does not declare a sheet count for it** — film the sheet count, or the comparison is worthless.

#### Batteries

| Item | Retailer | Price | Per cell |
|---|---|---|---|
| **KS Alkaline AA, 48-count** | **Costco** (primary) | **$15.99** | **$0.333** |
| **Great Value AA alkaline, 48-pack** | **Walmart** (ecom) | **$14.97** | **$0.312** |
| Duracell CopperTop AA, 40-count | Costco (primary) | $19.99 (reg $25.99, disc $6.00) | $0.500 |

**Walmart's 48-pack store brand is 6.4% cheaper per cell than Kirkland's 48-pack.** Tier (b) on the Walmart side. **Film both.**

#### Hawkins Cheezies — the only current prices obtainable anywhere

| Retailer | Item | Price | Window |
|---|---|---|---|
| **Giant Tiger** (flyer) | Hawkins Cheezies | **$4.97** (was $6.77, SAVE $1.80) | valid **16–23 Sep 2026** |
| **Shoppers Drug Mart** (flyer) | Hawkins Cheezies **420 g** or Terra chips 141 g | **$4.99** | valid **19–25 Sep 2026** |

The Giant Tiger listing gives no size. **The Costco multi-pack count and price are unknown and must be filmed. Without the Costco pack count these comparisons cannot be completed.**

#### Bacon, eggs, butter, cheese (Costco side is warehouse-only — competitors given as a filming checklist)

| Item | Retailer | Price | Window |
|---|---|---|---|
| No Name Bacon, 375 g | No Frills (flyer) | $2.50 (was $3.50) | 17–24 Sep 2026 |
| PC Bacon, 375 g | Real Canadian Superstore (flyer) | $5.00 (was $7.00) | 17–24 Sep 2026 |
| Great Value bacon | Walmart (flyer) | $3.97 (was $4.97, Rollback) | 17–24 Sep 2026 |
| Selection Bacon | Metro (flyer) | $2.99 | 17–24 Sep 2026 |
| Compliments Bacon | Sobeys (flyer) | $5.99 | 17–24 Sep 2026 |
| Maple Leaf Original Natural Bacon | Walmart (ecom) | $5.97 | everyday 19 Sep 2026 |
| Great Value Large 12 Eggs | Walmart (ecom) | $3.93 | everyday 19 Sep 2026 |
| Gray Ridge Premium Large White 18 Eggs | Walmart (ecom) | $6.98 | everyday 19 Sep 2026 |
| Goldegg Free Run Large White **30 Eggs** | Walmart (ecom) | $14.98 | everyday 19 Sep 2026 |
| Prestige/Gray Ridge Large White 18's | Your Independent Grocer (flyer) | $4.44 "HOT PRICE" | 17–24 Sep 2026 |
| Great Value Salted Butter 454 g | Walmart (ecom) | $5.96 | everyday 19 Sep 2026 |
| Gay Lea Salted Butter 454 g | Walmart (ecom) | $4.97 (was $6.98) | everyday 19 Sep 2026 |
| Lactantia Butter 454 g | No Frills (flyer) | $4.99 | 17–24 Sep 2026 |
| Armstrong Old Cheddar | Walmart (ecom) | $4.98 | size not stated — **film it** |
| Great Value Old Cheddar 320 g | Walmart (ecom) | $5.67 | $1.772/100 g |
| Balderson Old Cheddar | Walmart (ecom) | $10.47 | size not stated — **film it** |

**Costco's fresh bacon, eggs and butter have NO obtainable price. The Costco side of every row above is blank until you film it.** The only Costco cheese comparison available: KS Marble Cheddar 1.15 kg at **$1.303/100 g** vs Great Value Old Cheddar 320 g at **$1.772/100 g** — Costco 26% cheaper per 100 g, but these are different cheeses (marble vs old cheddar), so **this is not a fair like-for-like and should not be stated as one.**

#### Olive oil, detergent, coffee, dish soap (competitor side only — no clean like-for-like)

| Item | Retailer | Price | Per L / note |
|---|---|---|---|
| Great Value Extra Virgin Olive Oil 1 L | Walmart (ecom) | $10.97 | $10.97/L |
| Terra Delyssa Premium EVOO 1 L | Walmart (ecom) | $11.97 (was $16.77) | $11.97/L |
| Gallo EVOO 1 L | Walmart (ecom) | $12.94 | $12.94/L |
| Gallo EVOO 750 mL / 1 L | No Frills (flyer) | $7.99 | ambiguous size — **unusable** |
| Tide Pods 31-count | Walmart (ecom) | $12.97 | **$0.418/pac** |
| Gain Flings 31-count | Walmart (ecom) | $12.97 | $0.418/pac |
| Great Value Dark Roast Ground Coffee 907 g | Walmart (ecom) | $14.92 | **$16.45/kg** |
| Great Value Ultra Dishwasher Pacs 90-count | Walmart (ecom) | $16.97 | **$0.189/pac** |
| Cascade Complete ActionPacs 80-count | Walmart (ecom, on rollback) | $19.97 (was $24.97) | $0.250/pac |

**Two honest findings that cut against Costco:**
- **Costco's KS Spanish EVOO at $12.33/L is more expensive per litre than Walmart's Great Value EVOO at $10.97/L.** Different products, but both are the store's own extra virgin olive oil — a defensible comparison if you say so plainly.
- **Costco's KS Dark Colombian ground coffee at $24.99/kg is 52% more per kg than Walmart's Great Value dark roast ground at $16.45/kg.** Again store-brand vs store-brand.
- Costco's KS dishwasher pacs at **$0.165/pac** *do* beat Walmart's Great Value at **$0.189/pac** — a genuine Costco win, 13% cheaper per pac.
- Costco's KS laundry pacs at **$0.211/pac** beat Tide Pods at Walmart ($0.418/pac) by half — but that is store brand vs name brand, so say so.

### 4.4 Costco's own current flyers, retrieved 19 September 2026 — tier (a)/(b) hybrid

Three live Costco Canada flyers were retrievable through Flipp:

| Flyer ID | Type | Validity |
|---|---|---|
| 8119992 | **In-warehouse savings booklet** | 31 Aug – 27/28 Sep 2026 |
| 8136459 | Costco.ca online deals | 14 – 20 Sep 2026 |
| 8136070 | Costco Grocery online deals | 14 – 20 Sep 2026 |

**In-warehouse savings prices (31 Aug – 28 Sep 2026) — these are the closest thing to a warehouse shelf price I could obtain:**

| Item | Now | Regular | Saving |
|---|---|---|---|
| Kirkland Signature marble cheddar slices | $12.99 | $16.99 | $4.00 |
| Kirkland Signature shredded pizza mozzarella | $14.99 | $18.99 | $4.00 |
| Kirkland Signature daily dry facial towel | $19.99 | $24.99 | $5.00 |
| Tim Hortons original blend coffee | $39.99 | $54.99 | $15.00 |
| Tide original laundry detergent | $23.99 | $29.99 | $6.00 |
| Tide PODS Spring Meadow / Free and Gentle | $29.99 | $37.99 | $8.00 |
| Purex After The Rain / Coldwater liquid | $17.99 | $22.99 | $5.00 |
| Hellmann's real mayonnaise | $9.49 | $11.99 | $2.50 |
| Bounty Plus paper towel | $25.99 | $32.49 | $6.50 |
| Balderson double smoked cheddar | $9.89 | $13.89 | $4.00 |
| Janes whole wheat chicken strips | $12.99 | $16.49 | $3.50 |
| Duracell AA or AAA batteries | (price not carried) | — | $6.00 |
| Kirkland Signature Lakeridge queen mattress | $949.99 | $1,199.99 | $250.00 |

Sizes are not given in the flyer data for most of these — **film the packaging.** The warehouse booklet's own item images carry no machine-readable prices, so this list is partial. **Re-verify in warehouse on camera.**

---

## 5. MASTER UNIT-PRICE TABLE

**This is the spine of the video's arithmetic.** All Costco figures tier (a), costco.ca, 19 Sept 2026. **All: re-verify in warehouse on camera.**

### Per litre

| Item | Size | Price | **Per litre** |
|---|---|---|---|
| KS Olive Oil (not extra virgin) | 3 L | $30.99 | **$10.33** |
| KS Organic Extra Virgin Olive Oil | 2 L | $21.99 | **$10.99** |
| KS 100% Spanish EVOO | 3 L | $36.99 | **$12.33** |
| KS 100% Italian EVOO | 2 L | $31.99 | **$15.99** |
| KS Maple Syrup | 1 L | $17.99 | **$17.99** |
| KS Organic Maple Syrup | 1 L | $18.99 | **$18.99** |
| KS Organic Balsamic Vinegar of Modena | 1 L | $19.99 | **$19.99** |
| KS Ultra Shine Liquid Dish Soap | 2.66 L | $13.99 | **$5.26** |
| Heinz Ketchup | 2 × 1.5 L | $13.99 | **$4.66** |
| Hellmann's Real Mayonnaise | 1.8 L | $13.99 | **$7.77** |

### Per 100 g

| Item | Size | Price | **Per 100 g** | Per kg |
|---|---|---|---|---|
| KS Whole Grain Rolled Oats | 4.54 kg | $11.99 | **$0.264** | $2.64 |
| KS Organic Sugar | 4.54 kg | $16.99 | **$0.374** | $3.74 |
| KS Traditional Basmati Rice | 5 kg | $24.99 | **$0.500** | $5.00 |
| KS Frozen Chocolate Chunk Cookies | 6 kg | $36.99 | **$0.617** | $6.17 |
| Kraft Smooth Peanut Butter | 2 kg | $12.99 | **$0.649** | $6.50 |
| KS Organic Greek Yogurt | 1.36 kg | $8.99 | **$0.661** | $6.61 |
| KS Natural Creamy Peanut Butter | 2 × 1 kg | $14.99 | **$0.750** | $7.50 |
| KS Cream Cheese | 4 × 250 g | $8.99 | **$0.899** | $8.99 |
| KS 100% Pure Liquid Honey | 3 kg | $28.99 | **$0.966** | $9.66 |
| KS Corn Chip Dippers | 907 g | $8.99 | **$0.991** | $9.91 |
| KS Hazelnut Spread with Cocoa | 2 × 1 kg | $19.99 | **$0.999** | $9.99 |
| KS Soft & Chewy Granola Bars | 64 × 24 g | $15.99 | **$1.041** | $10.41 |
| KS Shelled Walnuts | 1.36 kg | $15.99 | **$1.176** | $11.76 |
| Sunrise Farms Frozen Seasoned Chicken Breast | 4 kg | $46.99 | **$1.175** | $11.75 |
| KS Chicken Breast, Canned | 6 × 354 g | $24.99 | **$1.177** | $11.77 |
| KS Dipped and Chewy Granola Bar | 1.49 kg | $17.99 | **$1.207** | $12.07 |
| KS Kettle Brand Pink Salt Potato Chips | 907 g | $10.99 | **$1.212** | $12.12 |
| KS Extra-large Peanuts | 1.13 kg | $13.99 | **$1.238** | $12.38 |
| Otis Spunkmeyer Assorted Muffins | 15 × 113 g | $21.99 | **$1.297** | $12.97 |
| KS Marble Cheddar Cheese | 1.15 kg | $14.99 | **$1.303** | $13.03 |
| KS Trail Mix | 1.81 kg | $23.99 | **$1.325** | $13.25 |
| KS Chewy Protein Bars | 42 × 40 g | $22.99 | **$1.368** | $13.68 |
| KS Grass-Fed Beef Patties | 2.27 kg | $32.99 | **$1.453** | $14.53 |
| KS Lightly Breaded Chicken Breast Chunks | 1.8 kg | $26.99 | **$1.499** | $14.99 |
| KS Funhouse Treats Assorted Candies | 2 kg | $29.99 | **$1.499** | $14.99 |
| KS Sliced Soft Fresh Mozzarella | 2 × 450 g | $13.99 | **$1.554** | $15.54 |
| KS Whole Almonds | 1.36 kg | $21.99 | **$1.617** | $16.17 |
| KS Treatsize Favourites | 2 kg | $34.99 | **$1.750** | $17.50 |
| **KS Chocolate Covered Almonds** | 1.5 kg | $26.99 | **$1.799** | $17.99 |
| KS Pistachios | 1.36 kg | $27.99 | **$2.058** | $20.58 |
| KS Roasted Whole Cashews with Salt | 1.13 kg | $23.99 | **$2.123** | $21.23 |
| Ace Bakery Mini Cheese Croissant | 560 g | $11.99 | **$2.141** | $21.41 |
| KS Nut Bars | 960 g | $20.99 | **$2.186** | $21.86 |
| KS Mini Chocolate Chip Cookies | 30 × 28 g | $18.99 | **$2.261** | $22.61 |
| KS Crumbled Bacon | 567 g | $12.99 | **$2.291** | $22.91 |
| **KS Salted Mixed Nuts** | 1.13 kg | $25.99 | **$2.300** | $23.00 |
| KS Coastal Cheddar | 810 g | $18.99 | **$2.344** | $23.44 |
| **KS Snacking Nuts Variety Pack** | 30 × 45 g | $31.99 | **$2.370** | $23.70 |
| KS Unsalted Mixed Nuts | 1.13 kg | $26.99 | **$2.388** | $23.88 |
| **KS Dark Colombian Ground Coffee** | 1.36 kg | $33.99 | **$2.499** | $24.99 |
| KS Whole Bean House Blend | 1.13 kg | $27.99 | **$2.477** | $24.77 |
| KS Whole Bean Espresso Blend | 1.13 kg | $28.99 | **$2.565** | $25.65 |
| KS French Roast Whole Bean | 1.13 kg | $29.99 | **$2.654** | $26.54 |
| KS Decaf Dark Roast Fine Grind | 1.36 kg | $36.99 | **$2.720** | $27.20 |
| Yorkshire Valley Organic BS Chicken Breasts | 5 × 2 kg | $279.99 | **$2.800** | $28.00 |
| KS Pecan Halves | 907 g | $25.99 | **$2.865** | $28.65 |
| **Tim Hortons Original Blend Fine Grind** | 1.36 kg | $39.99 | **$2.940** | $29.40 |
| **KS Precooked Bacon** | 500 g | $24.99 | **$4.998** | $49.98 |

### Per load / per pac

| Item | Count | Price | **Per load/pac** |
|---|---|---|---|
| KS Ultrafresh Premium Fabric Softener | 276 loads | $19.99 | **$0.072** |
| KS Premium Performance Dishwasher Detergent | 115 pacs | $18.99 | **$0.165** |
| KS Ultra Clean Premium Liquid Detergent | 146 loads | $24.99 | **$0.171** |
| KS Free and Clear Ultra Clean Liquid | 146 loads | $24.99 | **$0.171** |
| KS Ultra Clean Laundry Detergent Pacs | 152 pacs | $31.99 | **$0.211** |
| KS Oxi Power Premium Detergent Pacs | 110 pacs | $29.99 | **$0.273** |

### Per bar / pod / cell / bag / roll / unit

| Item | Count | Price | **Per unit** |
|---|---|---|---|
| KS 1-ply Napkins | 1,040 | $19.99 | **$0.019/napkin** |
| KS Baby Wipes, Fragrance Free | 900 (9 × 100) | $24.99 | **$0.028/wipe** |
| KS Flushable Wipes | 640 | $26.99 | **$0.042/wipe** |
| KS Large Freezer Bags | 192 | $27.99 | **$0.146/bag** |
| KS Scented Drawstring Kitchen Bags | 200 | $33.99 | **$0.170/bag** |
| KS Drawstring Kitchen Bags | 200 | $34.99 | **$0.175/bag** |
| KS Large Garbage Bags (quad-tie) | 100 | $19.99 | **$0.200/bag** |
| KS Soft & Chewy Granola Bars | 64 | $15.99 | **$0.250/bar** |
| KS Alkaline AA Batteries | 48 | $15.99 | **$0.333/cell** |
| KS Alkaline AAA Batteries | 48 | $15.99 | **$0.333/cell** |
| KS Drawstring Garbage Bags (113 L / 30 gal) | 90 | $31.99 | **$0.355/bag** |
| KS Organic Fair Trade K-Cup Pods (all 4 blends) | 120 | $49.99 | **$0.417/pod** |
| Duracell CopperTop AA (on promo) | 40 | $19.99 | **$0.500/cell** |
| KS Chewy Protein Bars | 42 | $22.99 | **$0.547/bar** |
| Pre-Proofed Butter Croissants | 30 | $17.49 | **$0.583/croissant** |
| Tim Hortons K-Cup Pods | 80 | $57.99 | **$0.725/pod** |
| KS Nut Bars | 24 | $20.99 | **$0.875/bar** |
| KS 2-ply Bath Tissue 30-pack | 30 rolls | $32.99 | **$1.100/roll**; **$0.289/100 sheets** |
| KS Ultra Soft 2-ply Premium 36-pack | 36 rolls | $37.99 | **$1.055/roll**; **$0.457/100 sheets** |
| Charmin Ultra Soft 30-pack (promo) | 30 rolls | $33.49 | **$1.116/roll**; **$0.558/100 sheets** |
| Cashmere Premium 40-pack (promo) | 40 rolls | $29.49 | **$0.737/roll**; sheets not declared |
| Otis Spunkmeyer Muffins | 15 | $21.99 | **$1.466/muffin** |
| KS Protein Bars | 20 | $38.99 | **$1.950/bar** |
| KS 2-ply Paper Towels 12-pack | 12 rolls | $33.99 | **$2.833/roll**; sheets not declared |

---

## 6. THE MEMBERSHIP ARITHMETIC

### 6.1 Fees and terms — tier (a) CONFIRMED PRIMARY, costco.ca/join-costco.html, captured 19 Sept 2026

| Membership | Annual fee | Cards | Notes (quoted from costco.ca) |
|---|---|---|---|
| **Gold Star (Personal)** | **$65** plus applicable sales tax | 2 (you + one household member) | "Everyday Value". *"Annual 2% Reward — This benefit is not included for Gold Star memberships."* |
| **Executive (Personal)** | **$130** plus applicable sales tax | 2 | "Best Value & Exclusive Benefits" |
| Business | $65 plus tax | 2, add affiliates at $65 each | Purchase for resale permitted |
| Business Executive | $130 plus tax | 2, add affiliates at $65 each | — |
| **Executive upgrade from Gold Star** | **+$65/year** | — | *"We will prorate the upgrade amount based on the months remaining in your current membership… At your next renewal, you will be billed $130."* |

**Executive reward — exact terms, quoted:**
> *"Annual 2% Reward* — Up to $1,250 on eligible Costco and Costco Travel purchases."*
> *"Reward is capped at and will not exceed $1,250 for any 12-month period. Only purchases made by the Primary and active Primary Household Cardholder on the account will apply toward the Reward. **The Reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid.** Limit one Executive Membership per household and business."*

**Reward percentage: 2%. Annual cap: $1,250.**

**Second Executive benefit, quoted:** *"$10 off one monthly order ($150 basket min.) in the Instacart App or Costco Same-Day… one (1) $10 CAD instant credit… each month you have a valid Costco Executive membership that is linked to your Instacart account."*

### 6.2 Executive break-even vs Gold Star — full working for on-screen

```
INPUTS (all from costco.ca, 19 Sept 2026)
  Gold Star annual fee ............................. $65.00  (+ tax)
  Executive annual fee ............................. $130.00 (+ tax)
  Executive reward rate ............................ 2.0%
  Executive reward annual cap ...................... $1,250.00

STEP 1 — the incremental cost of upgrading
  $130.00 − $65.00 = $65.00 per year

STEP 2 — the spend that generates $65 of reward at 2%
  $65.00 ÷ 0.02 = $3,250.00

STEP 3 — express monthly
  $3,250.00 ÷ 12 = $270.83 per month

ANSWER: A household must spend $3,250 a year ($270.83 a month) on
        QUALIFYING Costco purchases for Executive to break even
        against Gold Star. Below that, Gold Star is the better buy.

STEP 4 — where the cap bites
  $1,250.00 ÷ 0.02 = $62,500.00 of qualifying spend per 12 months.
  Past $62,500 the reward stops growing.

STEP 5 — the Instacart credit, treated separately and honestly
  $10 × 12 months = $120.00 per year MAXIMUM.
  It requires a $150+ basket on Costco Same-Day / Instacart every
  single month, and the account must be linked. A household that
  genuinely hits that every month covers the $65 upgrade from this
  benefit alone, with $55 to spare — BEFORE any 2% reward.
  A household that never orders delivery gets $0 from it.
```

**Two things that must be said on camera:** (1) the word **"qualifying"** — Costco excludes categories from the reward and links to a full exclusions list; do not present $3,250 as total till spend. (2) Costco itself states **"The Reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid."** Quote it.

### 6.3 How many "worth it" items cover the basic $65 membership — SHOW EVERY INPUT, AND THE PROBLEM

**I must be straight with you: this calculation cannot yet be done honestly, and here is exactly why.**

To compute it I need, for each item, a Costco price and a like-for-like competitor price, both current. I have **four** genuinely like-for-like same-brand-or-same-tier pairs. Three of them show Costco **losing**:

```
PAIR 1 — Heinz Tomato Ketchup (identical brand)
  Costco   2 × 1.5 L = $13.99  →  $4.663 per L
  Walmart  1.5 L     = $6.97   →  $4.647 per L
  SAVING PER LITRE AT COSTCO: −$0.016  (Costco is DEARER)

PAIR 2 — Hellmann's Real Mayonnaise (identical brand)
  Costco   1.8 L  = $13.99  →  $7.772 per L
  Walmart  1.42 L = $9.48   →  $6.676 per L
  SAVING PER LITRE AT COSTCO: −$1.096  (Costco is DEARER)
  [BUT: Costco in-warehouse savings booklet, 31 Aug–28 Sep, has this
   at $9.49 → $5.272/L, which BEATS Walmart by $1.404/L.
   So this pair flips depending on online vs warehouse. FILM IT.]

PAIR 3 — Store-brand AA batteries, 48-count (identical count)
  Costco  KS 48-count           = $15.99  →  $0.333 per cell
  Walmart Great Value 48-pack   = $14.97  →  $0.312 per cell
  SAVING PER PACK AT COSTCO: −$1.02  (Costco is DEARER)

PAIR 4 — Store-brand dishwasher pacs (per pac)
  Costco  KS 115 pacs            = $18.99  →  $0.1651 per pac
  Walmart Great Value 90 pacs    = $16.97  →  $0.1886 per pac
  SAVING PER PAC AT COSTCO: +$0.0235
  Over a 115-pac Costco box: 115 × $0.0235 = +$2.70 saved per box.
```

```
THE ARITHMETIC, RUN ON WHAT I ACTUALLY HAVE
  Only Pair 4 produces a positive saving: $2.70 per purchase.
  $65 ÷ $2.70 = 24.1
  → a household would need to buy roughly 25 boxes of Kirkland
    dishwasher pacs a year (2,875 pacs) to cover a $65 Gold Star fee
    on the strength of the only like-for-like Costco win I could verify.
  That is an absurd answer, and I am reporting it as absurd rather
  than dressing it up.
```

**Why the answer is absurd, stated plainly:** I priced Costco at its **online** price (higher than warehouse, proven in §0 by the $2.00 mayonnaise gap) and priced competitors at Walmart's **everyday online** price, because every other Canadian grocer blocked retrieval. That stacks the comparison against Costco on both sides simultaneously. **The real answer is almost certainly much more favourable to Costco — but I cannot produce it from data I could actually obtain today, and I am not going to invent it.**

**What Part 2 / the shoot must capture to make this calculation real** — the inputs are otherwise complete:

1. Costco **warehouse shelf prices** (photographed) for: maple syrup 1 L, KS Spanish EVOO 3 L, KS laundry liquid 146 loads, KS 2-ply bath tissue 30-pack, KS Dark Colombian coffee 1.36 kg, KS Salted Mixed Nuts 1.13 kg, KS dishwasher pacs 115, rotisserie chicken, Hawkins Cheezies multi-pack.
2. The matching **competitor shelf prices and pack sizes**, photographed at Loblaws/Superstore/No Frills, Walmart, Metro/Food Basics, Sobeys/FreshCo in the same week.
3. **Sheet counts** off competitor toilet paper and paper towel packaging — without these, §5's best arithmetic has no counterpart.
4. A stated **annual purchase frequency** per item for the household model (e.g. 4 × TP/yr, 6 × coffee/yr). I have deliberately not assumed these — they are an editorial choice, not a fact, and inventing them would poison the number.

Formula to drop in once those exist:
```
  Items needed to cover the fee =
      $65 ÷ (Σ [ (competitor unit price − Costco unit price) × pack size ] )
  where every term is a filmed, dated, same-week, same-size price.
```

---

## 7. COSTCO SERVICES — WHAT IS AND IS NOT PUBLISHED

| Service | Page | Published pricing? |
|---|---|---|
| **Gasoline** | costco.ca/gasoline.html | **NO PRICE OF ANY KIND.** The page carries marketing copy only ("Kirkland Signature Gasoline. With 5X the Required CGSB Deposit Control Additive"), a locations tool, and no per-litre figure. GasBuddy returned HTTP 403. **No Costco per-litre price is obtainable and no comparison to nearby stations is possible. Film the pump price and the price signs at two nearby stations on the same day.** |
| **Tire Centre** | costco.ca/tires.html | **No base tire prices** (requires a vehicle/tire-size lookup). Two current promotions ARE published, tier (a), 19 Sept 2026: *"Receive **$100** instantly when you buy a set of 4 eligible Bridgestone tires… August 31 – October 4, 2026"* and *"Receive **$60** instantly when you buy a set of 4 eligible Firestone tires… valid between August 31 to October 4, 2026."* Page states installation package is included and the offers are valid at Canadian warehouses and on costco.ca. |
| **Optical** | costco.ca/optical.html | **NO PRICES. Zero dollar figures in the page's visible text.** Eye exam fees and frame/lens prices must be filmed at the counter. |
| **Hearing Aids** | costco.ca/hearing-aids.html | **NO PRICES. Zero dollar figures in the page's visible text.** |
| **Food Court** | no page exists on costco.ca | **NO PRICES PUBLISHED ANYWHERE BY COSTCO.** See §8. |

---

## 8. FOOD COURT — WHY THERE IS NO USABLE NUMBER HERE

**Costco publishes no food court menu or pricing on costco.ca.** Search of all 7,897 product URLs and the site's own pages returned nothing.

**Tier (b) STRONGLY SUPPORTED, named outlet, but DATED 2025 — usable for the story, NOT as a current price:**

- **CBC News**, *"As a B.C. Costco cracks down on its food court, is there anywhere truly cheap left to eat?"*, **published 30 July 2025** (`datePublished: 2025-07-30T08:00:00.674Z`), cbc.ca/news/canada/costco-food-court-membership-1.7595356. Direct quote: *"The $1.50 Costco hotdog meal. Despite inflation, the price has held firm since the 1980s."* The same article states *"the $65 membership fee"* — independently corroborating §6.1.
- **blogTO / Daily Hive** (2024): the $1.50 Canadian combo is an all-beef or Polish sausage hot dog with a 20 oz. fountain drink, refill included.

**PIZZA SLICE AND WHOLE PIZZA: NO USABLE SOURCE EXISTS.** Every result for Canadian Costco pizza pricing came from the SEO/aggregator sites listed in §10. **Do not put a pizza price on screen. Film the menu board.**

**Recommendation:** film the food court menu board. It is a 15-second shot and it is the only honest source for any of these numbers.

---

## 9. UNVERIFIED / DO-NOT-USE

**Nothing in this section may appear on screen as a factual claim.**

### 9.1 Tier (c) SPECULATION — DO NOT USE

| Claim | Status |
|---|---|
| **"Kirkland milk chocolate almonds rose from ~$17 to ~$30"** | **NO SUPPORT FOUND.** Current price is $26.99 (1.5 kg), matching neither figure. No price history is published by Costco and I found no named-outlet record. **Cut, or replace with a dated shelf-tag photograph.** |
| **"Costco rotisserie chicken is $7.99 in Canada"** (reference script) | **CONTRADICTED.** The most recent named-outlet record (Narcity, 20 May 2026) says **$9**. Even that is four months stale. **Film the tag.** |
| Any Costco Canada pizza slice or whole-pizza price | **NO CREDIBLE SOURCE EXISTS.** Only SEO aggregators. **Film it.** |
| Any Costco per-litre gasoline price, and any comparison to nearby stations | **NOT OBTAINABLE.** Costco publishes none; GasBuddy blocked. **Film the pump.** |
| Any Costco Optical, hearing aid, or base tire price | **NOT PUBLISHED.** **Film the counter.** |
| Any claim that Costco TVs undercut Best Buy / Amazon / Walmart | **NOT TESTED.** All three blocked. No competitor TV price was obtained for any of the three model numbers. |

### 9.2 Items with NO obtainable Costco price — all must be filmed in warehouse

Rotisserie chicken · Food court hot dog combo, pizza slice, whole pizza · Hawkins Cheezies multi-pack (pack count unknown) · Costco bakery muffins (count unknown), bakery croissants, cakes, bakery cookies · Fresh eggs · Fresh butter · Fresh milk · Fresh/raw bacon and raw meat · French's mustard · Kirkland Signature boneless-skinless IQF frozen chicken breast · Gasoline · Optical · Hearing aids · Tire base prices.

### 9.3 Competitor comparisons that MUST BE FILMED IN STORE

**Loblaws, Real Canadian Superstore, No Frills, Metro, Food Basics, Sobeys, FreshCo, Save-On-Foods, Voilà and Amazon.ca all blocked automated retrieval on 19 September 2026.** Where a price from these banners appears in §4 it came from a **current scanned flyer via Flipp**, is **promotional not regular shelf price**, and is **tier (b) not tier (a)**.

**There is not one single tier-(a) competitor price in this dossier.** Every Costco-vs-competitor claim in the video must be shot on camera in both stores in the same week.

Specifically unusable without filming:
- All toilet paper and paper towel per-sheet comparisons (competitor sheet counts unpublished).
- "Hellmann's Mayonnaise $5.99 at Food Basics" — **no size given on the flyer. Unusable.**
- "Gallo EVOO $7.99 at No Frills" — flyer reads "750 mL/1 L", **ambiguous size. Unusable.**
- "Armstrong Old Cheddar $4.98" and "Balderson Old Cheddar $10.47" at Walmart — **no size given. Unusable.**
- All Hawkins Cheezies comparisons — **Costco pack count unknown.**
- Any olive-oil comparison — Costco's KS grades (Italian EVOO / Spanish EVOO / Organic EVOO / pure) have no exact grade-matched competitor product in the data.

### 9.4 Internal data discrepancy — disclose it, don't paper over it

**Charmin Ultra Soft 30 × 200 sheets (item 2633624) has three different current prices in three Costco-sourced feeds on the same day:**

| Source | Price |
|---|---|
| costco.ca product page, `onlinePrice` (regular) | $39.99 |
| costco.ca product page, `deliveredPrice` (live, after $6.50 discount) | **$33.49** |
| Costco Grocery flyer via Flipp, valid 14–20 Sep 2026 | **$26.49** (was $32.99) |

Note the flyer's "was" price ($32.99) does not match the page's regular price ($39.99) either. **I do not know which is the warehouse shelf price and I am not going to guess. Film the tag.** Cashmere 40-pack shows the same pattern ($34.99 reg → $29.49 live on-page, and $29.49 in the flyer — those two agree, so the Charmin case may be a regional or timing artefact).

### 9.5 Geographic scope

All Flipp competitor data used postal code **M5V 3L9 (downtown Toronto)**. Costco.ca prices resolved to default **warehouse number 894**, which I could not map to a named location. **Prices vary by province — declare the shooting city on screen.**

### 9.6 House-rule compliance note

Weights, volumes, counts, sheet counts, pack counts and roll counts appear throughout this dossier **solely as declared label or page facts**. No nutritional figure, no protein content, and no statement about any food's effect on a body appears anywhere in this document. Product descriptions were quoted only for identification (roast level, grind, ply, scent, certification, country of manufacture). No company is stated or implied to have done anything wrong: all price differences reported are ordinary commercial differences between retailers and formats, and Costco's own promotional and regular prices are reported side by side wherever both were available.

---

## 10. EXCLUDED DOMAINS — SEO / AGGREGATOR SITES ENCOUNTERED AND REJECTED

The following appeared in search results for Costco Canada pricing and were **excluded from this dossier without exception**. They are menu/price-guess sites with no stated capture date, no primary sourcing, and in several cases obviously wrong or US-derived figures. **Do not cite any of them, and do not let them back in via a second-pass search.**

- costcofoodcourtmenu.ca
- costcofoodcourtmenus.ca
- costcofoodcourt.vercel.app
- canadianmenuwithprices.com
- menupricesincanada.com
- clubfoodcourt.com
- utilitycommons.com
- optimalrecipes.com
- costcoguides.com
- mojosalesandbranding.com
- torontoscoop.ca
- thekrazycouponlady.com

**Sources actually used and permitted:**

*Primary (tier a):* costco.ca product pages (sitemap `sitemap_lw_p_001.xml`, JSON-LD and embedded `priceInfo`); costco.ca/join-costco.html; costco.ca/executive-rewards.html; costco.ca/gasoline.html; costco.ca/tires.html; costco.ca/optical.html; costco.ca/hearing-aids.html; costcobusinesscentre.ca (retrieved, no prices published).

*Named outlet / flyer (tier b and d):* Flipp / Wishabi public flyer and item endpoints (`backflipp.wishabi.com`) for current scanned retailer flyers and Walmart Canada e-commerce listings; CBC News (cbc.ca, 30 July 2025); Narcity (narcity.com, 20 May 2026); blogTO and Daily Hive (2024, background only).

---

**END OF PART 1 DOSSIER. Capture date for every Costco price above: 19 September 2026. Re-verify in warehouse on camera.**


---

# PART 2 DOSSIER — COSTCO CANADA: CLAIMS, CANADIAN SPECIFICS, AUDIENCE

**Compiled 19 September 2026.** Tier key: **(a)** CONFIRMED primary — company filing, company statement, regulator, court · **(b)** STRONGLY SUPPORTED — named outlet · **(c)** SPECULATION — do not use · **(d)** DOCUMENTED consumer/media record, quarantined.

House rules applied throughout: no health or nutrition commentary; no uncharged wrongdoing stated or implied; corporate claims attributed as corporate claims.

---

## A. THE ROTISSERIE CHICKEN LOSS LEADER

### A1. The Galanti "$30 to $40 million" quote

**VERDICT: PARTIALLY SUPPORTED — the quote is real but is almost universally mis-stated. Use only with the correction.**

The quote exists and is consistently reported. The verbatim wording, as carried by Fortune (29 May 2015), which credits *Consumerist* as the original source:

> "I can only tell you what history has shown us: When others were raising their chicken prices from $4.99 to $5.99, we were willing to eat, if you will, $30 to $40 million a year in gross margin by keeping it at $4.99. That's what we do for a living."
> — Richard Galanti, then CFO, Costco Wholesale

Source: https://fortune.com/2015/05/29/costco-chicken-prices — **tier (b)**. The same wording was carried by The Seattle Times ("Costco on chicken: Keep 'em cheap," https://www.seattletimes.com/business/retail/costco-on-chicken-keep-em-cheap/) — **tier (b)**, paywalled, wording confirmed via search index only.

**What the figure actually is — this is the correction that beats the competitor:**

1. It is **gross margin foregone by holding a price**, not a loss on the product. Galanti's construction is conditional: *had* Costco followed competitors from $4.99 to $5.99, it would have captured $30–40M more gross margin. That is a statement about a **forgone price increase**, not a statement that Costco sells the bird below cost.
2. It is **US-framed**. The $4.99 → $5.99 comparison is US retail pricing.
3. It is **from 2015**. It is eleven years old. It is not a current annual figure and Costco has not, on the record I can find, restated it.
4. **Venue caveat:** Fortune describes it as "a recent call with analysts." Costco's Q3 FY2015 earnings call was held 28 May 2015, which is consistent with a 29 May 2015 publication date — **but I could not retrieve the Q3 FY2015 transcript itself to confirm the date and venue independently.** Do not assert the specific call date on air.

**SAFE ON-AIR WORDING:**
> "Back in 2015, Costco's then-CFO Richard Galanti told analysts the company was willing to — his words — 'eat, if you will, thirty to forty million dollars a year in gross margin' by keeping the chicken at four ninety-nine while competitors moved to five ninety-nine. Note what that actually says. It's margin Costco chose not to collect by holding a price. It's not a statement that the bird sells below cost, it's a US price point, and it's eleven years old. Costco has not restated the number since."

**DO NOT SAY:** "Costco loses $30–40 million a year on rotisserie chicken." That is the competitor's error and it is not what the source says.

### A2. The 2023 Galanti statement — a cleaner, more recent quote

**VERDICT: VERIFIED (as reported). Prefer this one.**

> "[It] is an investment in low prices to drive membership — to drive the sales in a big way."
> — Richard Galanti, CFO, on the $4.99 rotisserie chicken

Reported by FOX Business, 3 March 2023, by Daniella Genovese, attributed to "Costco's earnings call this week" (Costco's Q2 FY2023 call was 2 March 2023). https://www.foxbusiness.com/lifestyle/costco-maintaining-rotisserie-chicken-prices — **tier (b)**.

This is the better citation: it is recent, it is Costco characterising its own strategy, and it does not require arithmetic gymnastics.

### A3. Canadian price history of the rotisserie chicken

**VERDICT: NOT SUPPORTED — DO NOT USE a specific Canadian price or price history as fact.**

This is the single weakest link in the competitor's video, and its own comment section caught it.

- Costco Canada **does not list the rotisserie chicken on costco.ca**. There is no retrievable first-party Canadian price.
- The only retrievable Costco-branded Canadian listing is the same-day delivery storefront: "Seasoned Rotisserie Chicken (Avg. 1.2kg)" at **CAD $9.07** — https://sameday.costco.ca/store/costco-canada/products/21114703-ls-seasoned-rotisserie-chicken-each — **tier (d)**. This is a third-party-fulfilled delivery price and is **not** the warehouse shelf price. It cannot be used as the warehouse price.
- The competitor used "$7.99." Two commenters on that video challenged it directly (see H). One asked outright where the figure came from.
- I found **no documented Canadian price-increase event** and **no Costco Canada statement** on rotisserie chicken pricing. The frequently repeated "$7.99–$9.00 in Canada" range traces to a CBC *Cost of Living* radio piece (2022) that I could not retrieve directly (403) — treat as unconfirmed.

**SAFE ON-AIR WORDING:**
> "In the US it's been four ninety-nine for years and Costco talks about it openly. In Canada — Costco doesn't publish the warehouse price anywhere I can check. It isn't on costco dot ca. So I'm not going to put a number on your screen and pretend it's national. Tell me what it rings up at in your warehouse and which town — that's the map I want to build."

That turns the weakness into the video's best engagement hook. See H10.

### A4. Costco's poultry operation

**VERDICT: VERIFIED for ownership and existence (primary). PARTIALLY SUPPORTED for location, cost, capacity and purpose (named outlets only).**

**Confirmed by Costco's own SEC filings — tier (a):**

FY2019 Form 10-K (filed 11 Oct 2019):
> "Subsequent to year end, operations commenced at our new poultry processing plant."
> "Interest expense decreased in 2019 largely due to an increase in capitalized interest associated with our new poultry processing plant."

FY2020 Form 10-K (filed 7 Oct 2020):
> "Fresh foods gross margin increased as a result of efficiencies from increased sales, partially offset by operating losses from our poultry complex."
> "In 2020, operations commenced at our new poultry processing plant…"

Sources: https://www.sec.gov/Archives/edgar/data/909832/000090983219000019/cost10k9119.htm and https://www.sec.gov/Archives/edgar/data/909832/000090983220000017/cost-20200830.htm

This is gold. Costco calls it **"our poultry complex"** and books **"operating losses"** from it in its own audited annual report. That is a company admission of a loss-making vertical integration, in a filing, with no journalist in between.

**Important limits — Costco's filings never say:** Nebraska, "Lincoln Premium Poultry," a dollar figure, a bird count, or that the purpose is rotisserie chicken. All of that comes from outside sources.

**Named-outlet layer — tier (b):**
- Facility is in **Fremont, Nebraska**, operating as **Lincoln Premium Poultry**; began processing in **September 2019**, grand opening **19 October 2019**. (WATTAgNet: https://www.wattagnet.com/broilers-turkeys/processing-slaughter/article/15529320/lincoln-premium-poultry-plant-to-open-september-3-wattagnet)
- Investment reported **variously as $400 million and $450 million** — the figure is not settled. WATTAgNet's own headline says $400M; other accounts say $450M. **Say "roughly four hundred million dollars" or give the range.**
- Capacity: **~2 million chickens per week**, described as enough to supply roughly **40% of Costco's fresh chicken**. (WATTAgNet; Greater Omaha Chamber, 12 Nov 2025: https://www.omahachamber.org/lincoln-premium-poultry-building-a-generational-success-story-in-nebraska/)
- Greater Omaha Chamber describes LPP as "Costco Wholesale's first fully integrated poultry operation," supplying rotisserie chicken and fresh poultry to Costco warehouses. Note this is an **economic-development booster publication** — tier (b) at best, and it is promotional. Use for colour, not for load-bearing numbers.

**SAFE ON-AIR WORDING:**
> "This part you don't have to take from a blog. In its own annual report to the SEC, Costco calls it — quote — 'our poultry complex,' and in fiscal 2020 the company booked 'operating losses from our poultry complex' against its fresh foods margin. Costco built a chicken plant and told its shareholders it was losing money. The outside reporting puts that plant in Fremont, Nebraska, roughly four hundred million dollars, around two million birds a week — Costco's filings don't name the state or the price tag, so that part is the trade press, not the company."

### A5. Does the Nebraska plant supply Canada?

**VERDICT: NOT SUPPORTED — DO NOT ASSERT either way.**

Costco has made no statement I can find. The *regulatory context* is solid and usable on its own:

Canada's chicken sector operates under **supply management** — three pillars: production planning (farmer quota), import control, and producer pricing. Import volume is capped by **Tariff Rate Quotas**; the WTO chicken TRQ is set at **39,900,000 kg or 7.5% of domestic production, whichever is greater**.
Sources: Chicken Farmers of Canada, https://www.chickenfarmers.ca/how-does-it-work/ (**tier (a)**, industry regulator body); Library of Parliament, "Canada's Supply Management System," https://lop.parl.ca/sites/PublicWebsite/default/en_CA/ResearchPublications/201842E (**tier (a)**); Global Affairs Canada TRQ notice, https://www.international.gc.ca/trade-commerce/controls-controles/notices-avis/986_2.aspx?lang=eng (**tier (a)**).

**SAFE ON-AIR WORDING:**
> "Does the Nebraska plant feed Canadian warehouses? Costco doesn't say, and I'm not going to guess. What I can tell you is the rule: Canadian chicken runs on supply management — farmer quota, negotiated farm-gate price, and imports capped by tariff-rate quota. Bringing American chicken into Canada at scale isn't a procurement decision, it's a trade-quota decision."

**⚠️ EXCLUDED PER BRIEF:** No animal-welfare litigation or campaign material has been gathered or included. Additionally, a 2025 US consumer lawsuit concerning rotisserie chicken preservatives surfaced repeatedly in search — it is an **unresolved allegation**, off-thesis for a price video, and is listed in the DO-NOT-USE section.

---

## B. THE HAWKINS CHEEZIES CANADA-EXCLUSIVE CLAIM

### B1. Who makes them, where, since when

**VERDICT: VERIFIED for the core facts; one commonly repeated date is contested.**

- Maker: **W.T. Hawkins Ltd.**, a Canadian-owned, family-run company, now in its third/fourth generation (founder Willard Trice Hawkins → son Willard Western "Web" → grandson Kent Hawkins). — **tier (b)**
- Plant: **Belleville, Ontario**, at 105 Pinnacle Street. Production moved to Belleville in **1956** after a fire destroyed the original plant in **Tweed, Ontario**. — **tier (b)**
- Product origin: invented post-WWII by **James Marker** (Dayton, Ohio) and **W.T. Hawkins**, who developed the extruded-cornmeal method in Chicago. Production established at Tweed, Ontario in **1949**. — **tier (b)**
- Company site: https://cheezies.com/ — states only "Proudly Canadian. It's all about people." It does **not** publish founding dates, plant location or distribution territory on its landing page. — **tier (a)** for the tagline, useless for the rest.

**Date caution:** one source gives "**incorporated 27 June 1949**," another gives 1949 as the year production began in Tweed. These are compatible but not identical claims. Say "**1949**" and "**Belleville since 1956**" and do not over-specify the incorporation date.

**⚠️ DOMAIN WARNING:** `hawkinscheezies.com` is **not** the manufacturer's site. It lists a Toronto address (2500 Don Mills Road), claims "9+ years of experience," and reads as a reseller. The manufacturer's site is **cheezies.com**. Do not cite or link hawkinscheezies.com.

**SAFE ON-AIR WORDING:**
> "Cheezies are made by W.T. Hawkins Limited — family-owned, Canadian, making them since 1949, out of Belleville, Ontario since 1956 after a fire took out the original plant in Tweed. Same family, four generations."

### B2. Is the Costco multi-pack exclusive to Costco Canada?

**VERDICT: NOT SUPPORTED AS AN EXCLUSIVITY CLAIM — DO NOT USE "you can't get these in the States."**

What I can support:

- **Costco Canada does list it.** "Hawkins, Cheezies Corn Snacks, 36 × 36 g (1.27 oz)," costco.ca item page, listed at time of check as **Unavailable** at warehouse with a minimum online order quantity of 2. https://www.costco.ca/hawkins,-cheezies-corn-snacks,-36-%C3%97-36-g-1.27-oz.product.100474744.html — **tier (a)** (Costco's own site). Also carried by **Costco Business Centre Canada**: https://www.costcobusinesscentre.ca/hawkins-cheezies-corn-snacks,-36-%C3%97-36-g-.product.100281032.html — **tier (a)**. No price was displayed on either page to an unauthenticated visitor.
- **I could not establish absence from US Costco.** Costco's US and Canadian on-site search APIs both return Access Denied to automated requests, and the catalogue search pages are JavaScript-rendered and returned no product data. **I cannot honestly say "not listed on costco.com" either** — I was unable to run the search at all. That is a weaker position than the brief anticipated, and I am flagging it rather than papering over it.
- **Counter-evidence that kills the naive claim outright:** Hawkins Cheezies are **sold in the United States by third-party importers**, including a Walmart.com listing explicitly marketed as "Imported from Canada" (https://www.walmart.com/ip/Hawkins-Real-Cheddar-Cheezies-2pk-285g-10-oz-Bags-Imported-from-Canada/2625705261). So "Americans can't get Cheezies" is false on its face.

**SAFE ON-AIR WORDING:**
> "The thirty-six-pack is on Costco dot ca — it's a real Canadian Costco item, and it's in the Business Centre too. What I'm not going to tell you is that Americans can't get it. I couldn't get Costco's US search to return anything I'd stake a claim on, and Cheezies are sold in the States anyway through importers — there's a Walmart listing that literally says 'imported from Canada.' So: Canadian item, Canadian company, Canadian plant. Not a smuggling story."

### B3. Other genuinely Canada-distinctive Kirkland / Costco Canada items

**VERDICT: PARTIALLY SUPPORTED — the *category* is strong, the *item list* is not.**

The strong, sourceable version of this segment is **not** a list of products. It is the Pierre Riel parliamentary testimony in Section D, which is a primary-source Canadian executive statement that over 61% of Kirkland Signature items sold here are manufactured in Canada. **That is the segment.** Build it on D1, not on a product list.

The circulating item lists (Kirkland maple syrup from Quebec producers; honey from Bee Maid; lasagna from Zinetti Foods BC; nut bars from Leclerc; soy beverage from Natura) appear **only on SEO and affiliate sites** — canadamadein.ca, money.ca, moneywise/newsdirect syndication, shopcanadianstuff.ca, truecanadianfinds.com. **Tier (c). Do not read these on air as sourced facts.**

The one exception with real sourcing is **Leclerc** — see C3.

**A note on the strongest possible version of this segment:** Kirkland products carry country-of-origin marking on the physical package. If a researcher or the host photographs "Product of Canada" on a Kirkland item in a warehouse, that photograph is **tier (a) primary evidence** — better than any article. If this segment matters, shoot the labels.

---

## C. KIRKLAND SUPPLIER CLAIMS — THE BIGGEST TRAP

### C1. "Kirkland protein bars are made by the same manufacturer as Premier Protein"

**VERDICT: NOT SUPPORTED — DO NOT USE. This is the competitor's worst claim.**

- No primary source, no supplier statement, no filing, and no named outlet connects Premier Protein or BellRing Brands to Kirkland Signature protein bars.
- Searching the consumer press turns up **three mutually contradictory** answers for who makes them — Standard Functional Foods Group, Come Ready Foods / Ready Nutrition, and a "Quest dupe" framing — each on a Static Media or SEO property, none with a supplier confirmation, and at least one of which explicitly concedes the connection "lacks direct confirmation."
- Premier Protein's own brand page (BellRing Brands, https://bellring.com/brands) makes no Kirkland claim.

**The contradiction is itself the story.** Three content farms, three different manufacturers, zero confirmations.

**SAFE ON-AIR WORDING:**
> "The video I'm responding to says Kirkland protein bars come from the same manufacturer as Premier Protein. There is no source for that. Not a filing, not a supplier statement, not one named outlet. I went looking and found three different websites naming three different manufacturers for that same bar, and one of them admits in its own text that it can't confirm it. Costco doesn't say who makes it. Nobody does. That claim should not have been in that video."

### C2. Costco's stated policy on disclosing Kirkland manufacturers

**VERDICT: VERIFIED — primary, from Costco.**

Costco's own Kirkland Signature product-inquiry page states:

> "Please note that while we will do our best to answer any questions, certain information may be proprietary or confidential and will not be disclosed."

https://customerservice.costco.com/app/ks?r=mainNav — **tier (a)**.

Costco Canada's Kirkland Signature brand page describes the programme without naming a single manufacturer. Costco says it controls "tous les aspects de la marque : fraîcheur, ingrédients, fabrication, emballage" and works "en partenariat avec des fabricants de qualité dans le monde entier" — in partnership with quality manufacturers worldwide — and names none of them. https://www.costco.ca/f/-/kirkland-signature — **tier (a)**.

**SAFE ON-AIR WORDING:**
> "Here's Costco's actual position, from Costco's own website: certain information 'may be proprietary or confidential and will not be disclosed.' On its Canadian Kirkland page it says it partners with quality manufacturers worldwide — and then names exactly zero of them. So when a video tells you confidently who makes a Kirkland product, ask where that came from. Because it didn't come from Costco."

### C3. Kirkland supplier relationships that ARE confirmed

**VERDICT: VERIFIED — but only these. Name no others.**

**1. Starbucks — Kirkland Signature coffee. Tier (a). The strongest one.**
Costco discloses this itself, on its own product pages. The Kirkland Signature Decaf House Blend listing carries, in the product's own key features and specifications:
> "Custom Roasted by Starbucks"
> "Roasted by Starbucks Coffee Co.®"

https://www.costco.com/kirkland-signature-decaf-house-blend-coffee,-medium-roast,-whole-bean,-2.5-lbs.product.100493988.html

This is a **Costco disclosure**, not journalism. **Caveat:** the labelling has reportedly been removed from some Kirkland coffee SKUs since late 2023/early 2024, so the relationship is SKU-specific and may be changing. Say "on this product, Costco says so itself" — do not generalise to all Kirkland coffee.

**2. Leclerc Foods — Kirkland Signature Nut Bars. Tier (b), strong.**
Wall Street Journal reporting by **Sarah Nassauer**, published 10 September 2017 (carried via Dow Jones / FOX Business):
> "Over about five months, Costco developed the Kirkland Signature Nut Bars, made by Leclerc Foods USA, which is owned by Leclerc Group, a Canadian manufacturer…"

https://www.foxbusiness.com/features/how-kirkland-signature-became-one-of-costcos-biggest-success-stories

Costco executives cooperated with that story on the record — general merchandise manager **Tess Wilkins** and CFO **Richard Galanti** are both quoted in it — which makes the supplier naming unusually well-founded. **And it is Canadian-relevant:** Leclerc Group is a Quebec company, 120 years old.

**3. Sonova — Kirkland Signature hearing aids. Tier (b), and it is now historical.**
Sonova supplied the Kirkland Signature KS9 and KS10 hearing aids. Sonova itself announced it would cease supplying certain large retail chains, ending the arrangement around **November 2022**; the KS10 was sold until roughly October 2022. Trade press: hearingreview.com, hearinghealthmatters.org, hearingtracker.com. Useful as a **demonstration** that these relationships end without notice — but it is over, so frame it in the past tense.

**That's the list.** Three. One disclosed by Costco, one from the WSJ with Costco's cooperation, one from a supplier's own announcement.

**⚠️ Explicitly NOT confirmed** (all tier (c), do not name on air): Duracell/Kirkland batteries, Ocean Spray/Kirkland cranberry juice, Reynolds, Jelly Belly, Niagara Bottling, Kimberly-Clark, LeVecke, and every other pairing in the listicle ecosystem. On Ocean Spray specifically: an Ocean Spray logo appearing on a co-branded Kirkland juice package would be a **label fact** and usable if photographed — but I found **no press release and no corporate confirmation**, and the claim as it circulates is unsourced.

**THE REPORTABLE FINDING — this is the spine of the segment:**

> "I went looking for every confirmed Kirkland supplier I could find. Confirmed means the supplier said it, or Costco said it, or it's in a filing. Not 'a website said it.' I found three. Starbucks on coffee — and Costco prints that on the product page itself. Leclerc, a Quebec company, on the nut bars — that one's from the Wall Street Journal, with Costco executives on the record in the story. And Sonova on hearing aids, which Sonova itself ended back in 2022. Three. Everything else you've heard is guesswork with a logo next to it. Costco doesn't say."

---

## D. KIRKLAND SIGNATURE AND CANADA

### D1. The Canadian manufacturing proportion

**VERDICT: VERIFIED — primary source, parliamentary evidence. This is the best fact in the entire dossier.**

**Speaker:** Pierre Riel
**Title (as recorded):** Executive Vice President and Chief Operating Officer, Costco Wholesale International and Canada, Costco Wholesale Canada Ltd.
**Venue:** House of Commons Standing Committee on Agriculture and Agri-Food (AGRI), 44th Parliament, 1st Session, **Meeting No. 91**, study on efforts to stabilize food prices
**Date:** Tuesday, **13 February 2024**
**Chair:** Kody Blois

From Riel's opening statement, verbatim:

> "We've also continued to invest in our Kirkland Signature private label brand. We've increased the number of food items for the label by over 12% since 2019. Kirkland Signature products are designed to match or exceed the quality of national branded items, resulting in savings of around 20%.
>
> We've invested in Canadian suppliers. **Over 61% of our Kirkland Signature items are now manufactured in Canada.** We've mitigated price increases and accelerated price decreases as input and commodity prices drop, despite the weakening of the Canadian dollar."

Sources: House of Commons AGRI Evidence No. 91, https://www.ourcommons.ca/documentviewer/en/44-1/AGRI/meeting-91/evidence · mirrored full text at https://openparliament.ca/committees/agriculture/44-1/91/ — **tier (a)**.

Other verbatim from the same statement, all usable:
> "Our membership renewal rate in Canada and the United States is over 92%."
> "We have 53,000 employees in Canada, up from 48,000 in 2021. Our starting hourly wage was increased to $18.50 in September 2023."
> "The average hourly wage is up from $27.63 in 2019 to $30.20 today."
> "A cashier who has worked full time at Costco for six years makes over $70,000 a year."
> "Since the start of 2023, we've decreased prices on hundreds of items."

Secondary coverage for corroboration: Rosa Saba, The Globe and Mail, 13 Feb 2024, https://www.theglobeandmail.com/business/article-costco-executive-says-company-always-looking-to-lower-prices-mitigate/ — **tier (b)**.

**Three critical framing caveats — get these right or the fact rots:**
1. It is **61% of Kirkland Signature ITEMS (SKUs)**, not 61% of Kirkland sales, revenue or volume. Do not convert it.
2. It is a **corporate claim made by a Costco executive**, under parliamentary testimony. It is not independently audited. Attribute it as Costco's own number.
3. It is from **February 2024** — two and a half years old as of broadcast.

**SAFE ON-AIR WORDING:**
> "In February 2024 Costco's number two internationally, Pierre Riel, sat in front of the House of Commons agriculture committee and said this on the record: 'We've invested in Canadian suppliers. Over sixty-one per cent of our Kirkland Signature items are now manufactured in Canada.' That's Costco's own number, said under parliamentary testimony, and it's items — SKUs — not dollars. But it's on the parliamentary record, which is a lot more than most retail claims can say."

### D2. Canadian sourcing, "Buy Canadian," and tariff response, 2025–2026

**VERDICT: VERIFIED for the corporate statements below. NOT SUPPORTED for any claim about Costco Canada's in-store Canadian-product labelling.**

**Ron Vachris, President and CEO**, Q3 FY2025 earnings call (late May 2025), as reported by Global News (Sean Previl, 2 June 2025, https://globalnews.ca/news/11208577/costco-canada-supply-chain-tariffs/) — **tier (b)**:
> "We rerouted many goods sourced from countries with large tariff exposure to our non-U.S. markets."
> "We continue to move more Kirkland Signature product sourcing into the countries or regions where items are sold and this is helping us to lower costs and mitigate some of the potential impacts of tariffs."

**Ron Vachris**, earnings call 6 March 2025, as reported by Ben Cousins for the Financial Post (via Yahoo Finance Canada, https://ca.finance.yahoo.com/news/costco-reduce-canadian-products-u-184408234.html) — **tier (b)**:
> "There's not many items that we can't find something to replace or something else to bring in that category."
> "The tariffs are very fluid right now, so it's hard to give any predictions on what we can do, but our people are very well-equipped to lower prices and defer any cost increases that come our way."
In the same call, CFO **Gary Millerchip** noted adjusted sales in Costco's then-109 Canadian locations rose 10.5%.

**Ron Vachris**, Q3 FY2026 earnings call, **28 May 2026** (transcript via The Motley Fool, https://www.fool.com/earnings/call-transcripts/2026/05/28/costco-cost-q3-2026-earnings-transcript/) — **tier (b)**:
> "In Canada, yes, we have a lot of upside potential. We have got some clubs. We have got the next 3 to 5 years charted out."
> "So we see consistent strong growth in Canada for at least the next 5 years, and then we will have to come back and evaluate."
> "On the topic of tariffs, we started submitting our refund claims for the Section 301 tariffs."
> "Our plan is to return to our members in some form the portion of tariffs that were passed on to them."

**Costco's own FY2025 10-K — tier (a)**, the company's standing supply-chain language:
> "For future product supply need, we pursue diversification in our supply-chain and seek to expand in-country production."

**⚠️ DO NOT USE:** The circulating claim that "Costco makes no effort to identify Canadian products in store or online, unlike every other major Canadian retailer" appears only on affiliate/SEO sites (shopcanadianstuff.ca, truecanadianfinds.com). I could not verify it and it is an absence claim about in-store signage across 115 warehouses. **Tier (c).** It may well be true; it is not sourced.

**SAFE ON-AIR WORDING:**
> "On tariffs, here's Costco's CEO Ron Vachris, on the record: 'We continue to move more Kirkland Signature product sourcing into the countries or regions where items are sold.' And in the annual report the company writes that it seeks to 'expand in-country production.' That's the corporate line. Whether you see that on a shelf in Mississauga is a different question — and I'm not going to tell you Costco does or doesn't flag Canadian products in store, because I couldn't verify it either way."

---

## E. THE ELECTRONICS CLAIM

### E1. "Slightly different model numbers… tricky by design"

**VERDICT: PARTIALLY SUPPORTED. The practice is real and documented. "By design" is an intent claim that must be attributed — never stated as Costco's motive.**

**The best-sourced version — Consumer Reports, "Buzzword: Are 'derivative' TV models a good buy?", James K. Willcox, 12 November 2009** (https://www.consumerreports.org/cro/news/2009/11/buzzword-are-derivative-tv-models-a-good-buy/index.htm) — **tier (b), and it names Costco explicitly.**

> "Since the model numbers, and usually, specifications, are different, shoppers can't directly compare the models sold in these different types of retail outlets."

CR names Walmart and Costco as channels that receive derivative models, and cites specific examples in Samsung's LN-B400/B500 and Sony's KDL-L504/S504 series. Crucially, CR frames the practice as **manufacturer-driven** — manufacturers distribute derivative models to warehouse and mass channels so as not to disrupt pricing at mainstream retail partners.

**Corroborating — NBC News, Herb Weisbaum, 17 November 2015** (https://www.nbcnews.com/business/consumer/black-friday-brief-derivative-tvs-smoking-deal-or-sham-n464296) — **tier (b)**:
- **Jim Willcox**, Senior Electronics Editor, Consumer Reports: *"It also helps retailers as they've stepped-up their price-matching guarantees."*
- **Benjamin Glaser**, Features Editor, DealNews: *"If you see an amazing deal on a set, it could be because it's been cranked out in a limited run just for Black Friday."*
- **Chris Heinonen**, Staff Writer, The Wirecutter: *"It might be a great value, but we have no way of really knowing that."*

**The "by design" problem.** The sourcing supports: (i) derivative and channel-exclusive model numbers exist; (ii) they make direct price comparison and price-matching harder; (iii) **manufacturers** create them, in conjunction with retailers, to hit price points without disrupting mainstream pricing. The sourcing does **not** support an assertion that **Costco** adopts them in order to frustrate your comparison shopping. Costco is one of several named channels; the origination is described as the manufacturer's.

**SAFE ON-AIR WORDING:**
> "The model-number thing is real, and it's not a Costco invention. Consumer Reports has been writing about 'derivative' models since 2009, and they name Costco — along with Walmart — as channels that get them. Their words: because the model numbers and usually the specs are different, 'shoppers can't directly compare the models sold in these different types of retail outlets.' But note who's driving it. Consumer Reports describes it as manufacturers building derivative models for these channels so they don't blow up pricing at their mainstream partners. So: does it make comparison harder? Yes, demonstrably. Is that Costco sitting in a room designing it that way? Nobody has shown me that, and I'm not going to say it."

### E2. The electronics positives — REQUIRED FOR FAIRNESS

**VERDICT: VERIFIED — primary, from costco.ca. These cut hard against a "skip" verdict and the script must carry them.**

**Costco Technical and Warranty Service** — Costco Canada customer service, https://customerservice.costco.ca/app/answers/answer_view/a_id/1017381/ — **tier (a)**:
- Costco extends the manufacturer's warranty to **two (2) years from the date of purchase** for **televisions, projectors, major appliances, and computers (excluding tablets)** purchased from Costco Canada — **where the manufacturer's warranty is less than two years**.
- Includes free technical support, setup help, troubleshooting and warranty assistance by phone; in-home service where in-home service is covered under the manufacturer's warranty. Support handled in Canada and the US, English and French, business hours. Canadian line: 1-866-231-9731.
- Service hub: https://www.costco.ca/f/-/concierge

**Electronics returns: 90 days.** Verbatim from Costco Canada's return policy (below).

**Price adjustment — 30 days.** Costco Canada, Document CCSS124 v3.0, published 09/10/2025, https://customerservice.costco.ca/app/answers/answer_view/a_id/1017287/ — **tier (a)**:
> "We will honour price adjustment requests for purchases made in-warehouse within 30 days from the date of purchase. The item must be in stock (excluding demonstration merchandise) and within the valid promotional dates when requesting a price adjustment. Simply visit the Membership Counter of your local warehouse and our clerks will be happy to help you."

**SAFE ON-AIR WORDING:**
> "Before anyone calls electronics a skip — here's what Costco Canada actually offers, from Costco's own site. Ninety days to return a TV or a computer, no receipt hunt. Costco extends the manufacturer's warranty to two years on televisions, projectors, major appliances and computers, if the manufacturer's warranty is shorter. Free phone tech support and setup help, in English and French. And thirty days of price adjustment at the membership counter. Compare that against the store that sells you a two-year extended warranty for extra. The model number makes comparison harder — the warranty makes the comparison worth losing."

**Audience corroboration (tier (d), but it's the single most-liked comment on the competitor's video, 80 likes):** *"Electronics at Costco is worth the warranty alone. Try taking back an open computer or TV to Best Buy."* A second comment at 47 likes: *"When you add the extra cost charged by Walmart, Best Buy and Amazon for a 2 year extended warranty, Costco comes out way ahead in value."* **The competitor called electronics a skip and its own top comment overturned it.** That is our opening.

---

## F. COSTCO CANADA RETURN POLICY AND MEMBERSHIP GUARANTEE

**VERDICT: VERIFIED — verbatim primary from costco.ca. Read it on screen; it is the most checkable advantage in the video.**

### F1. Costco's satisfaction guarantee (Document CCSS89 v2.0, published 09/10/2025)
https://customerservice.costco.ca/app/answers/answer_view/a_id/1017252/ — **tier (a)**

> **Costco's Risk Free 100% Satisfaction Guarantee**
>
> **On Membership:** We will refund your membership fee in full at any time if you are dissatisfied.
>
> **On Merchandise:** We guarantee your satisfaction on every product we sell and will refund your purchase price, with the following exceptions:
>
> **Electronics:** Costco will accept returns within 90 days from the date of purchase for televisions, projectors, computers, cameras, tablets, camcorders, MP3 players, cellular phones, major appliances and other products identified by Costco from time to time.
>
> **Diamonds:** When returning items containing a 1.00 ct diamond or larger, Costco will require additional time to verify the diamond, in which case a refund will be approved upon positive verification. This process may require two to five business days.
>
> **Gold bars and gold bullion:** Cannot be returned or refunded.
> **Silver bars and silver bullion:** Cannot be returned or refunded.
> **All Gift Cards and Live Event Tickets:** Cannot be returned or refunded.
>
> **Custom Installation Services:** Custom products ordered or installed according to our members' personal and unique specifications cannot be returned or refunded, except for warranty repair/replacement due to failure to meet specifications and otherwise to the extent required by law.
>
> Costco may in the future restrict its return policy regarding other products. Restriction will be shown at the point of purchase.

### F2. The return policy page (Document CCSS87 v4.0, published 10/10/2025)
https://customerservice.costco.ca/app/answers/answer_view/a_id/1017250/ — **tier (a)**

Note this page is **more current** and its exception list is **longer** than CCSS89. Verbatim:

> **On Membership:** We will refund your membership fee in full if you are dissatisfied.
>
> **On Merchandise:** We guarantee your satisfaction with every product we sell and will refund your purchase price, with the following exceptions:
>
> **Electronics:** Costco will accept returns within 90 days from the date of purchase for televisions, major appliances\*, projectors, computers, cameras, Aerial Cameras (drones), camcorders, digital music players, tablets, smart watches, Cellular Phones (return details will vary by carrier service contract) and other electronic products identified by Costco from time to time.
>
> **Diamonds:** When returning items containing a 1.00 ct diamond or larger, Costco warehouses will require additional time to verify the diamond… This process will require approximately 2 to 5 business days.
>
> **Cigarettes and alcohol:** Costco does not accept returns on cigarettes or alcohol where prohibited by law.
>
> Products with a limited useful life expectancy, such as **tires and batteries**, may be sold with a product-specific limited warranty.
>
> **Custom Installation Services:** Custom products ordered or installed according to our members' personal and unique specifications cannot be returned or refunded…
>
> **Airline and Live Performance Event items** are non-refundable.
> **Gold bullion, gold bars, silver coins and silver bars** are non-refundable.
> **Shop Cards** are non-refundable.
> **Gift Card and Ticket items** are non-refundable.
>
> Costco may in the future restrict its return policy regarding these and other products. Restrictions will be shown at the point of purchase
>
> \*Countertop microwaves excluded

**Editorial notes:**
- Costco Canada maintains **two live pages** with **differing exception lists** (CCSS87 adds drones, smart watches, cigarettes/alcohol, tires/batteries, Shop Cards; CCSS89 does not). Cite **CCSS87** as the operative one — it is the newer publication date and the more specific. That discrepancy is itself a small, honest, checkable observation nobody else has made.
- The membership guarantee wording differs subtly: CCSS89 says "**at any time**," CCSS87 omits it. Quote CCSS89 for the "at any time" phrasing and cite it as such.
- Note the standing reservation: "Costco may in the future restrict its return policy." Do not present the policy as a permanent guarantee.

**SAFE ON-AIR WORDING:**
> "This is the part nobody puts in a Costco video, so here it is word for word off Costco Canada's own site: 'On Membership: We will refund your membership fee in full at any time if you are dissatisfied.' In full. At any time. Which means the sixty-five dollars is refundable, which means the membership is the only item in this video you can test for free. On merchandise: satisfaction guaranteed, refund of purchase price — with exceptions, and the big one is electronics at ninety days. Also excluded: gold and silver bullion, gift cards, live event tickets, custom installs, and cigarettes and alcohol where the law prohibits returns. And Costco reserves the right to restrict the policy in future — that's their language, not mine."

---

## G. COSTCO CANADA SCALE AND CORPORATE FACTS

### G1. Warehouse count

**VERDICT: VERIFIED — primary, SEC-filed.**

| As at | Canada | Worldwide | Source |
|---|---|---|---|
| 10 July 2024 | 108 | 882 | 8-K Ex-99.1, 10 Jul 2024 |
| 31 Aug 2025 (FY2025 year-end) | **110** | 914 | FY2025 10-K, Item 2 |
| 10 May 2026 (Q3 FY2026) | **115** | 928 | Q3 FY2026 10-Q, Note 1 |
| **5 July 2026 (most recent filed)** | **115** | **933** | 8-K Ex-99.1, 8 Jul 2026 |

Most current citable figure: **115 Costco warehouses in Canada**, per Costco's June-sales press release filed with the SEC on 8 July 2026 — https://www.sec.gov/Archives/edgar/data/909832/000090983226000060/costex9918-k7726.htm — **tier (a)**.

FY2025 10-K also gives the Canadian property breakdown (Item 2, Properties): of 110 Canadian warehouses, **94 owned land and building, 16 leased land and/or building**; Canadian warehouses held approximately **15.9 million square feet** of the company's 134.7 million sq ft of operating floor space. https://www.sec.gov/Archives/edgar/data/909832/000090983225000101/cost-20250831.htm — **tier (a)**.

**⚠️ Caution:** Costco's FY2026 10-K (year ended ~30 Aug 2026) had **not been filed** as of 19 Sept 2026 — expect it in early October. If the video publishes after that, refresh this number.

**SAFE ON-AIR WORDING:** *"115 Costco warehouses in Canada, as of Costco's most recent filing with the SEC this July. It was 108 two years ago. They're building."*

### G2. Membership fee history

**VERDICT: VERIFIED — primary, SEC-filed, and it explicitly names Canada.**

Costco 8-K Exhibit 99.1, press release dated **10 July 2024**, https://www.sec.gov/Archives/edgar/data/909832/000090983224000036/costex9918-k71024.htm — **tier (a)**, verbatim:

> "The Company also announced that, effective September 1, 2024, it will increase annual membership fees by $5 for U.S. and Canada Gold Star (individual), Business, and Business add-on members. With this increase, all U.S. and Canada Gold Star, Business and Business add-on members will pay an annual fee of $65. Also effective September 1, annual fees for Executive Memberships in the U.S. and Canada will increase from $120 to $130 (Primary membership of $65, plus the Executive upgrade of $65), and the maximum annual 2% Reward associated with the Executive Membership will increase from $1,000 to $1,250. The fee increases will impact around 52 million memberships, a little over half of which are Executive."

**Summary:**
- **1 Sept 2024:** Gold Star / Business $60 → **$65**; Executive $120 → **$130**; Executive 2% Reward cap $1,000 → **$1,250**. Canada explicitly named. **Tier (a).**
- **Prior increase: 1 June 2017** — Gold Star $55 → $60, Executive $110 → $120, affecting ~35 million members, also applied in Canada (CBC, "Costco will hike membership fees in Canada and U.S. this June," https://www.cbc.ca/news/business/costco-membership-1.4008130) — **tier (b)**. I did not retrieve the 2017 8-K itself.
- So: **one increase in the last nine years**, a seven-year gap between 2017 and 2024, and **no change since 1 September 2024** — fees have now held for two years.

**Context from the FY2025 10-K — tier (a):**
- Worldwide paid members **81.0 million**; total cardholders **145.2 million**.
- Executive members: **38.7 million** of paid members; Executive penetration **~73.6% of worldwide net sales**.
- **Renewal rate 92.3% in the US and Canada**; 89.8% worldwide.

**SAFE ON-AIR WORDING:** *"Costco's fee went up once in the last nine years. Sixty to sixty-five for Gold Star, a hundred and twenty to a hundred and thirty for Executive, effective September first, 2024 — and the filing names Canada specifically, so that's Canadian dollars in Canada. Before that, 2017. It hasn't moved in two years. And the renewal rate in the US and Canada is 92.3 per cent."*

### G3. Canada segment financials

**VERDICT: VERIFIED — the prior dossier's figures are correct. Updated with newer data.**

**FY2025 (52 weeks ended 31 August 2025), Form 10-K Note 11, Segment Reporting** (US$ millions) — **tier (a)**:

| | Total revenue | Merchandise costs | SG&A | Operating income | **Operating margin** |
|---|---|---|---|---|---|
| United States | 200,046 | 174,021 | 19,147 | 6,878 | **3.44%** |
| **Canada** | **36,923** | 32,204 | 2,870 | **1,849** | **5.01%** |
| Other International | 38,266 | 33,661 | 2,949 | 1,656 | 4.33% |
| **Total** | **275,235** | 239,886 | 24,966 | **10,383** | 3.77% |

**Prior dossier confirmed exactly: Canada revenue US$36,923M, operating income US$1,849M, 5.01% vs US 3.44%.** Both figures reproduce from the filing.

**NEWER DATA — Q3 FY2026 Form 10-Q, Note 9, 36 weeks ended 10 May 2026** (US$ millions) — **tier (a)**, https://www.sec.gov/Archives/edgar/data/909832/000090983226000051/cost-20260510.htm:

| 36 weeks | Total revenue | Operating income | **Operating margin** |
|---|---|---|---|
| United States | 149,934 | 5,124 | **3.42%** |
| **Canada** | **27,774** | **1,416** | **5.10%** |
| Other International | 29,723 | 1,344 | 4.52% |

**The gap has widened.** Canada is running **5.10%** operating margin against the US at **3.42%** — a spread of 168 basis points, up from 157bp in FY2025. Three-year Canadian trend: FY2023 4.38% → FY2024 4.73% → FY2025 5.01% → FY2026 YTD 5.10%.

Also from the FY2025 10-K, Canada segment: depreciation & amortization $196M; additions to property and equipment **$580M** (up from $351M in FY2024 — a 65% jump in Canadian capex); property and equipment net $2,930M; total assets $7,304M.

**Framing discipline.** Higher segment operating margin is a **financial-reporting fact**. It is not evidence of overcharging Canadians — it reflects a mix of gasoline penetration, warehouse maturity, real-estate ownership (94 of 110 Canadian warehouses owned outright), labour costs, membership mix, FX translation, and segment cost allocation. **Do not imply it means Canadians are gouged.** State it and let it sit.

**SAFE ON-AIR WORDING:**
> "Here's something from Costco's own filings almost nobody reports. Costco breaks out Canada as its own segment. In fiscal 2025, Canada did thirty-six point nine billion US in revenue and one point eight five billion in operating income — that's a five point oh one per cent operating margin. The United States, same year: three point four four. And the most recent quarterly filing, through May of this year, has Canada at five point one zero and the US at three point four two. The gap is getting wider, not narrower. I'm not going to tell you that means you're being gouged — segment margin moves with gas sales, with how many warehouses you own outright, with currency. But it is Costco's number, in Costco's filing, and Canada is the most profitable place Costco operates per dollar of revenue."

---

## H. WHAT CANADIANS ACTUALLY SAY — AUDIENCE MINING

**⚠️ ALL OF SECTION H IS TIER (d). Quarantined.** These are anonymous YouTube comments. They are **not evidence of fact** and must never be presented as verification of a price, a policy or a supplier. They are useful for three things only: (i) what Canadians raise unprompted, (ii) what the competitor got wrong in the eyes of its own audience, (iii) comment-prompt design.

**Videos mined** (all pulled 19 Sept 2026):
1. **"Don't Renew Your Costco CANADIAN Membership Until You Watch This"** — Canadian Counter, 13 May 2026, **235,602 views**, 3,307 likes, 129 comments, 22:51. `hlJg9VFW5hQ`
2. **"Don't Renew Your Costco Canada Membership Until You Watch This"** — North America Crisis Radar, 2 May 2026, **143,227 views**, 2,678 likes, 127 comments, 19:37. `HsJQZPadmBw`
3. **"10 Costco Canada Items That Are Actually Worth It - BUY vs SKIP (MAY 2026)"** — Canada Food Insider, 13 May 2026, **104,007 views**, 3,355 likes, 344 comments, 13:52. `C31KT1khrCA` — **this is the reference video.**

### H1. Items Canadians name UNPROMPTED as best buys

Ranked by frequency across the three comment sets:

- **Cheese** — repeatedly, both Kirkland and imported. *"Cosco also has the best price for imported cheese."* *"Costco cheese is usually a good buy. I cut it into smaller pieces and freeze it."* Multiple independent mentions. **The single most-named item not in the reference video.**
- **Gasoline** — named constantly, with hard numbers: *"Usually 8 cents to as high as 14 cents per litre cheaper."* *"With a 100 litre tank you basically move the decimal point over 2. I save 30 to 50 dollars a month."*
- **Clothing / apparel** — a notable gap complaint: *"I am surprised clothing in general wasn't mentioned…cant be beat!"* (32 likes), echoed by others.
- **Kirkland facial tissues** — a genuine sleeper: *"A surprise must buy are Kirkland facial tissues… People just walk right [past]"*
- **Maple syrup** and **olive oil** — both endorsed, both already in the reference video.
- **Laundry pods / Tide pods / dishwasher tabs** — *"excellent cost per load compared to other grocery stores."*
- **Eggs (18-pack), free-run eggs, bananas, fruit** — mixed but frequent.
- **Optical / eyewear** — *"You do NOT need a membership to buy your glasses or use the Optician services."* (Worth verifying independently — potentially a strong under-reported segment.)
- **Hearing aids** — *"You should have included the great discount that Canadians get on hearing aids."*
- **Home and auto insurance via Costco** — two separate commenters claim four-figure savings. *"We saved almost $1000 off our home insurance thru Costco."* *"I saved 978 Cdn dollars a year by changing over my 2 car insurance policy."*
- **Pet supplies** — dog pee pads, dental sticks, wet/dry food.
- **Bird seed / sunflower seeds**, **spices**, **olives**, **Que Pasa taco chips**, **Stonemill sourdough**, **food-court pizza**.

### H2. What they say is a waste

- **Toilet paper — the most contested item in the entire dataset.** Sharply split. Pro: *"Kirkland Toilet Paper is BETTER than name brand stuff… rolls are smaller, sheets are smaller and there are fewer sheets per roll [elsewhere]. Costco wins!"* Against, on **value**: *"PC triple roll toilet paper in the 30 roll size is a lot better deal at $22.00."* *"Toilet paper is cheaper at Real Canadian Superstore for a 30 pack. and more sheets per roll."* *"the rolls have been reduced (sheets per roll) to something like 370. You can still get 400 per roll from other store brands like PC AND less expensive."* **This is a real, checkable, shrinkflation-flavoured price story and it is the best BUY-vs-SKIP fight available.** ⚠️ A separate cluster of toilet-paper comments makes plumbing/septic claims — those are unverified consumer anecdotes, see H4.
- **Bakery items** — not "bad," but **volume-mismatched**. And the audience answered its own objection, three times over: *"To solve the bakery item volume issue I freeze em in smaller containers. Esp the croissants."* (68 likes) *"Buy those croissants and muffins and freeze them!"* *"Wrap the baked goods individually and freeze them!"* **The freezer counter-argument is the most-liked practical tip in the dataset.**
- **Fruit** — *"Fruit is not often cheaper than other retailers, except maybe bananas."*
- **Meat** — recurring complaint that prices have risen: *"Their costs have gone up i find....especially the meat."* *"Its not such a deal now, meat has doubled."*
- **Protein bars — a direct regional price challenge to the reference video:** *"Not sure where the channel lives but in Ontario kirkland protein bars cost almost double what is shown here and more than other protein bars packs at costco. I still prefer them to many alternatives but not a bargain anymore."* And a separate arithmetic challenge: *"I think the math is off with the protein bars. You show a box with 20 count for $17.99. That is about 90 cents each, not $1.20-1.50."* **The reference video's protein-bar segment was attacked on both price and arithmetic.**
- **Membership itself, for small households / no car / rural** — *"we have a costco about 40 miles from home i'm not going out of my way to shop there."* *"I don't own a car so the gas part wouldn't work for me."*

### H3. Recurring complaints and unanswered questions

**Complaints:**
1. **"AI slop."** Overwhelming on video 2 — *"i feel sick..AI slop"* (61 likes) is the **top comment on a 143,000-view video**. Plus *"Nothing like AI slop in the morning,"* *"Another AI crap,"* *"don't waste 19.36 minutes of your life watching this AI generated CRAP,"* *"A robot teaches you how to live!!!"*, and a remark on AI vocal fry. Video 3 also drew *"AI slop. Kirkland Frozen Chicken Breasts but used imagery of fresh."* **This is the largest single failure mode in the category.** Stock-footage/product mismatch is being caught.
2. **Misleading title.** *"This title is beyond misleading"* (23 likes). *"I don't understand the title of this post"* (28 likes). *"Ok so why shouldn't I renew before watching this????"* *"Should've called this listen to the Costco salesman."* **The "Don't Renew" framing is actively resented** because both videos then praise Costco.
3. **Factual errors caught by Canadians, repeatedly.** These are the specific kills:
   - **Alcohol.** At least five separate commenters: *"Since when does Costco Canada sell whiskey?"* *"Alcohol isn't sold in Canadian Costco stores"* *"Costco doesn't sell alcohol here"* *"You can't buy whiskey or any booze at any Canada Costco so how much can you trust this review"*. Provincial liquor law varies; a blanket alcohol segment is a trap. **Do not include one.**
   - **The rotisserie chicken price.** *"Where did you get the cost for Rotisserie Chicken at $7.99. Here in California it's been $4.99 for years and years."* and *"Rotisserie chicken isn't $7.99 in Canada"*. See A3.
   - **Right-hand-drive stock footage.** *"9:36 sure ain't in Canada, we drive on the right side of the road and our steering wheel is on the left side"* (36 likes).
   - **French labelling.** *"If this was canadian, those labels would be in french as well"* (11 likes). **Canadian bilingual packaging law means US stock imagery is instantly detectable.**
   - **Gas stations aren't universal.** *"There is NO Costco gas bar anywhere where i live."* *"Where are there gas stations in Canada? Why not in greater Vancouver??"*
   - **Membership fee stated wrongly.** *"Gold Star is actually higher now."* Also several commenters citing $150 — apparently conflating Executive ($130) with something else. **Get $65/$130 right and cite the filing.**
4. **Background music too loud.** Two separate complaints. Trivially fixable.
5. **Padding.** *"Please get to the point… You are extending the video time by repeating the same statement with different words over and over again."*
6. **Everything is old news.** *"These are not secret at all known about this for years."* *"Good job captain obvious!!"* **This is the strategic opening: the SEC filings, the parliamentary testimony and the verbatim policy text in this dossier are all genuinely new to this audience.**

**Unanswered questions — direct segment fuel:**
- *"Can u do a segment on Cosco mattresses?"*
- *"How about clothing? Sometimes they have decent prices for good brands in the apparel section"*
- *"Has anyone compared the rewards programs offered by Costco, PC Optimum, and various credit card points?"*
- *"Would love to see glutten free option"*
- *"They never have Shreddies. I love them but I never see them at our Costco in Canada?"*
- *"BUT IS THE GRADE A - Light, Medium, Dark or Very Dark?"* (maple syrup grade — a real, checkable Canadian labelling question)
- *"Why not in greater Vancouver??"* (gas station distribution)
- *"when will wine be sold in Canada stores?"*
- Whether a **senior membership tier** exists: *"I really wish they had a Senior Membership."*

### H4. ⚠️ QUARANTINED COMMENTS — CANNOT BE USED

**Health / nutrition claims.** A substantial cluster of comments across all three videos makes assertions about ingredients, additives, packaging chemicals, oils, and effects on the body — regarding rotisserie chicken, bakery items, laundry detergent, chicken breasts, maple syrup packaging and water. **Per house rule 1, none of these may be repeated, evaluated, rebutted or alluded to.** They are excluded from this dossier's substance entirely and are not quoted above. Do not open a comment thread on ingredients; it will fill with this material.

**Allegations of wrongdoing — none may be stated or implied.** Flagged and excluded:
- A former-employee comment alleging serious workplace misconduct by named-role managers. **Unverified personal allegation concerning identifiable individuals. Absolutely unusable.**
- *"Trump owns shares in costco boycott"* — unverified assertion about an individual's holdings.
- *"Crooked as F"* / *"Boycott them immediately..MAKE THEM GO BROKE"* — unsupported.
- *"Apparently Kirkland olive oil has been in the courts for questionable false quality"* — an unverified reference to litigation. **Allegation is not finding.** Do not mention.
- *"Many of the return policies… are 'quietly' being put in place"* — unverified claim of undisclosed policy change. Note that Costco's published policy *does* reserve the right to restrict (F2), which is the sourced version.
- *"This is misinformation and illegal"* / *"We need content like this removed from YouTube"* — a viewer's legal characterisation of another creator. Unusable.
- The **2025 US consumer lawsuit regarding rotisserie chicken preservatives** (surfaced via CBC in search, not from comments) — **unresolved allegation, off-thesis, DO NOT USE.**

**Religious-slaughter / halal labelling comments.** Several appear across videos 1 and 3. These mix factual labelling questions with contested characterisations and shade into both health and identity territory. **Excluded. Do not build a segment on this.**

**Political / boycott comments.** A visible "Buy Canadian / boycott US retailers" cluster (*"Costco is an american company"*, *"all profits go to the big American company"*, *"Shop Canadian"*). This is **real and sizeable audience sentiment** and it is legitimate to acknowledge that Costco is a US-headquartered company operating 115 Canadian warehouses with 53,000 Canadian employees (all sourced above). **Do not adopt, endorse or attack the boycott position.** Note also two comments framing the video itself as foreign interference — evidence that this topic invites conspiracy framing. Stay on filings and prices.

### H5. The competitor's own list, as its audience recorded it

One commenter (76 likes) transcribed the reference video's verdicts. This is our best record of what we are responding to:

> "Kirkland Maple syrup, kirkland Chicken Breasts, Kirkland extra virgin olive oil, Hawkins cheesies, Kirkland laundry detergent. Rotisserie Chicken (loss leader) $7.99, Kirkland protein bar, Kirkland 30 pack toilet paper, Kirkland Dark Roast Coffee, Kirkland mixed nuts / Skip: Kirkland Chocolate Almon[ds]…"

Note the confirmed overlaps with this dossier's kills: **"$7.99" rotisserie chicken (A3 — unsourceable)**, **Kirkland protein bar (C1 — supplier claim false; and challenged on price and arithmetic by the audience)**, **Hawkins Cheezies (B2 — exclusivity unsupported)**, **electronics as SKIP (E2 — overturned by the video's own top comment)**.

### H6. TEN COMMENT PROMPTS — asking for DATA THEY HAVE

Each asks for a **number, a place, or a receipt**. No opinions.

1. **The one this video can't answer:** What does the rotisserie chicken ring up at in YOUR warehouse — and what town? I could not find a Canadian price published anywhere by Costco. Price and city. Let's build the actual map.
2. **Toilet paper, settle it:** Go look at your Kirkland pack. How many **sheets per roll** does it say, and how many rolls, and what did you pay? I want to know if the 400-to-370 story is real and whether it's national.
3. **Gas:** Costco price per litre versus the nearest non-Costco station, same day, your city. Two numbers and a postal-code prefix.
4. **Protein bars:** An Ontario viewer told the other channel these cost nearly double there. Box count, price, province. Is Kirkland protein bar pricing regional?
5. **Did you ever actually get the membership refunded?** Costco's site says "in full at any time if you are dissatisfied." Has anyone here tested that? What did they say at the counter, and which warehouse?
6. **Electronics warranty, real cases only:** Did you ever claim the Costco two-year extension on a TV, computer, projector or major appliance? What broke, what month, and did they pay? I want outcomes, not opinions.
7. **The model-number test:** Next time you're in, photograph the model number on a TV at Costco, then look up that exact string at Best Buy or Amazon. Post what you find — exact match, or one letter off?
8. **Kirkland made in Canada:** Costco's own executive said over 61% of Kirkland items sold here are made in Canada. Flip a Kirkland package over. What does the country-of-origin line actually say? Product name and the exact wording.
9. **Price adjustment:** Costco Canada says 30 days, at the membership counter. Has anyone here gotten one? What item, how many days after, how much back?
10. **The gap in this video:** Cheese and clothing were the two most-named items in the other channel's comments and neither made anyone's list. What's your best cheese or apparel price at Costco right now — item, size, price, province?

### H7. CLOSING QUESTION

> **"One number, one town. Tell me the single Costco Canada price you've actually verified against another store this month — what the item is, what Costco charged, what the other store charged, and where you live. I'll put the ones that check out in the next video and I'll name the town. Costco won't publish most of these prices. You're the only ones who can."**

Rationale: it requests a comparison the viewer already performed, is falsifiable, geographically taggable, promises reciprocity, and directly repairs the credibility hole the competitor opened by asserting a $7.99 chicken its own audience disputed.

---

## ⚠️ UNVERIFIED / DO-NOT-USE

**Claims checked that FAILED and must not appear in any form:**

1. **"Costco loses $30–40 million a year on rotisserie chicken."** FALSE framing of a real 2015 quote about **forgone gross margin** from holding a US price point. See A1. Use only the corrected version.
2. **"Kirkland protein bars are made by the same manufacturer as Premier Protein."** NO SOURCE. Three content farms name three different manufacturers; one admits it can't confirm. See C1.
3. **A specific Canadian rotisserie chicken price ($7.99 or any other).** Not published by Costco; not retrievable; disputed in the competitor's own comments. The only Costco-branded Canadian figure found is a same-day **delivery** price of CAD $9.07, which is not a warehouse price. See A3.
4. **"The Hawkins Cheezies multi-pack is unavailable at US Costco."** I could not run Costco's US catalogue search at all (Access Denied / JS-rendered), so I cannot even claim "not listed on costco.com." And Cheezies are demonstrably sold in the US via importers. See B2.
5. **Any Kirkland supplier beyond Starbucks (coffee, per Costco's own product page), Leclerc Foods USA (nut bars, per WSJ with Costco on the record), and Sonova (hearing aids, historical, per Sonova).** Specifically DO NOT name: Duracell, Ocean Spray, Reynolds, Jelly Belly, Niagara Bottling, Kimberly-Clark, LeVecke, Standard Functional Foods, Come Ready Foods, Quest. See C3.
6. **"Costco makes no effort to identify Canadian products in store or online, unlike other Canadian retailers."** Affiliate/SEO sourcing only. Unverified absence claim across 115 warehouses. See D2.
7. **The Nebraska plant supplies Canadian warehouses** — or that it doesn't. No Costco statement either way. Use the supply-management regulatory framing instead. See A5.
8. **The exact date/venue of the 2015 Galanti quote.** Reported as "a recent call with analysts"; Costco's Q3 FY2015 call was 28 May 2015 and that is consistent, but I could not retrieve the transcript. Do not state the call date.
9. **"$450 million" as a settled figure for the poultry plant.** Reported variously as $400M and $450M by the same trade-press ecosystem. Say "roughly four hundred million" or give the range.
10. **The specific Canada-only Kirkland product lists** (Bee Maid honey, Zinetti lasagna, Natura soy, Citadelle/Maple Treat syrup). SEO-only. Photograph labels instead. See B3.
11. **Any Costco Canada alcohol segment.** Provincial liquor law varies; the competitor was hammered by at least five commenters for a whiskey claim. See H3.
12. **Rotisserie chicken preservative litigation (US, 2025).** Unresolved allegation, off-thesis. Allegation is not finding.
13. **Animal-welfare litigation or campaign material re: Costco poultry.** Excluded by brief; not researched; not included.
14. **Every quarantined comment in H4** — all health/ingredient claims, all wrongdoing allegations, the named-role workplace allegation, the olive-oil litigation reference, the shareholding claim, and the religious-slaughter cluster.
15. **FY2026 full-year Canada segment figures.** Costco's FY2026 10-K was not filed as of 19 Sept 2026. Use FY2025 full-year plus Q3 FY2026 36-week data, labelled as such.

### EXCLUDED DOMAINS — SEO, content-farm, aggregator and affiliate

**Static Media property network** (these outlets recycle one another; none does primary reporting on this topic): chowhound.com · tastingtable.com · thetakeout.com · foodrepublic.com · mashed.com · foodie.com · thedailymeal.com · moneydigest.com · thelist.com · slashgear.com

**Kirkland-supplier speculation sites:** whoreallymakes.com · chefsresource.com · costco97.com · hip2save.com · moneytalksnews.com · barchart.com (listicle syndication) · costcuisine.com · costcoinsider.com · warehouserunner.com

**Return-policy / price content farms:** storepolicies.com · costrefund.com · thereturnguide.com · costlowapp.com · settlemate.io · accio.com · dealnews.com (feature pages) · thekrazycouponlady.com · moneygenius.ca

**"Canadian products" affiliate sites:** shopcanadianstuff.ca · truecanadianfinds.com · canadamadein.ca · madeinca.ca · norther.ca · money.ca · moneywise.com · newsdirect.com (moneywise syndication) · thenorthernstar.ca

**Rotisserie-chicken SEO:** mojosalesandbranding.com · thelaunchpadincubator.com · 247-foodrecipes.com · tatnuckmeatandsea.com · costcoguides.com · olavigroup.com · poultryproducer.com (aggregator) · launchpadgroupusa.com (WSJ reprint scraper)

**Other excluded:** quora.com · ontario-bakery.com · hometechnologyreview.com · solatatech.com · eatthis.com · take-note.ca · **hawkinscheezies.com** (reseller impersonating the manufacturer's site — the real one is cheezies.com) · any Yahoo/AOL/finance.yahoo republication of the above (syndication, not sourcing)

**Retrieved but blocked / unusable:** snopes.com (HTTP 402) · cnn.com (HTTP 451) · seattletimes.com (paywalled — Galanti quote confirmed only via search index) · cbc.ca (HTTP 403 on two articles) · wattagnet.com direct fetch (403; content confirmed via search index only) · bloomberg.com · search.costco.com and search.costco.ca APIs (Access Denied)

---

### Coverage notes for the caller

- **Strongest new material, in order:** (1) Costco's own 10-K saying "operating losses from our poultry complex" — a company admission in an audited filing that nobody in this niche has used; (2) Pierre Riel's parliamentary testimony on 61% Canadian Kirkland manufacturing; (3) the Canada-vs-US segment margin gap widening to 168bp; (4) the verbatim Costco Canada return policy and the two-page discrepancy between CCSS87 and CCSS89.
- **Four of the reference video's claims do not survive:** the chicken loss figure (mis-stated), the Premier Protein supplier claim (unsourced), the Cheezies exclusivity claim (unsupportable), and the electronics SKIP verdict (contradicted by verifiable Costco Canada warranty and return terms, and by its own top comment).
- **The single biggest structural risk** is AI-slop perception. Stock-footage mismatch, right-hand-drive vehicles, and English-only packaging were all caught and called out by Canadian commenters. Any B-roll must be right-hand-drive-free and show bilingual packaging.
- **Refresh before publication if after early October 2026:** the FY2026 10-K will supersede G1 and G3.
