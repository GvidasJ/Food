# VERIFICATION LOG — COSTCO CANADA BUY vs SKIP

Script: `script_costco_buyskip.md` — body 22,986 characters, inside the 21,000–23,000 band.
Research: `research_costco_buyskip.md` — Part 1 (live prices, 19 Sept 2026) and Part 2 (claims,
Canadian specifics, audience).

Tier key: (a) CONFIRMED PRIMARY · (b) STRONGLY SUPPORTED, reputable named outlet ·
(c) SPECULATION — not used · (d) DOCUMENTED CONSUMER/MEDIA RECORD — not used as fact.

---

## 1. THE STRUCTURAL DECISION, AND WHY

The reference video's spine is Costco versus other Canadian retailers. **That spine cannot be
built honestly from anything obtainable.** On 19 September 2026 every major Canadian grocer
blocked automated price retrieval: Loblaws, Real Canadian Superstore, No Frills, Metro, Sobeys,
Save-On-Foods and Voilà all returned HTTP 403 or redirect loops; Walmart.ca and Amazon.ca
returned bot walls; the Loblaws mobile API returned HTTP 401. Only Flipp/Wishabi responded, and
Flipp is an intermediary carrying promotional flyer prices — tier (b), not tier (a).

Four genuinely like-for-like Costco-vs-Walmart pairs exist in the dossier. **Costco loses three
of them.** That result is an artefact, not a finding: Costco was priced at its ONLINE price,
which sits above the warehouse shelf (proven — Hellmann's $13.99 online vs $9.49 in the
31 Aug – 28 Sep warehouse booklet), while the competitor was priced at its everyday online price.
The comparison is stacked against Costco at both ends simultaneously.

**Therefore the script is built on Costco's internal unit-price arithmetic.** Every headline
comparison is Kirkland Signature against Kirkland Signature, same aisle, same day, both numbers
printed on Costco's own product pages. That is tier (a) throughout, needs no competitor, cannot
be disputed on store-brand quality, and produces a sharper thesis than the reference had:
Costco versus Costco, not Costco versus Loblaws.

**One competitor comparison survives into the script** (dishwasher pacs, §3 below) and it is
spoken with its own caveat attached, in the script itself.

---

## 2. PRICE CLAIMS — ALL TIER (a), costco.ca, CAPTURED 19 SEPTEMBER 2026

Every price below is the embedded `deliveredPrice` (the live price), not the JSON-LD `price`
field, which is pre-discount. **All require re-verification on the warehouse shelf on camera.**

| # | Spoken claim | Item # | Verified figure |
|---|---|---|---|
| 1 | KS Ultra Clean Premium Liquid, 146 loads, $24.99 | 1845613 | $0.171/load |
| 2 | KS Free and Clear Liquid, 146 loads, $24.99 | 1845621 | $0.171/load |
| 3 | KS Ultra Clean Laundry Pacs, 152, $31.99 | 1054838 | $0.211/pac — 23% above liquid |
| 4 | KS Oxi Power Premium Pacs, 110, $29.99 | 2675962 | $0.273/pac — 60% above liquid |
| 5 | KS 100% Italian EVOO, 2 L, $31.99 | 71003 | $15.99/L |
| 6 | KS 100% Spanish EVOO, 3 L, $36.99 | 4249003 | $12.33/L — Italian is 46% higher |
| 7 | KS Organic EVOO, 2 L, $21.99 | 692731 | $10.99/L |
| 8 | KS Olive Oil (not EV), 3 L, $30.99 | 1554830 | $10.33/L — Italian is 55% higher |
| 9 | KS Maple Syrup, 1 L, $17.99 | 118263 | $17.99/L |
| 10 | KS Organic Maple Syrup, 1 L, $18.99 | 679131 | $18.99/L |
| 11 | KS 2-ply Bath Tissue 30-pack, $32.99, 380 sheets/roll | 6262016 | 11,400 sheets → $0.289/100 sheets |
| 12 | KS Ultra Soft Premium 36-pack, $37.99, 231 sheets/roll | 1725952 | 8,316 sheets → $0.457/100 sheets — **58% more per sheet** |
| 13 | KS Dark Colombian Ground, 1.36 kg, $33.99 | 15071 | $24.99/kg |
| 14 | Tim Hortons Original Blend, 1.36 kg, $39.99 | 1019209 | $29.40/kg — **17.6% more, $6.00 on the identical bag** |
| 15 | KS Organic K-Cups, 120, $49.99 | 4272377–80 | $0.417/pod |
| 16 | Tim Hortons K-Cups, 80, $57.99 | 2660661 / 1669669 | $0.725/pod — **74% more** |
| 17 | KS Premium Performance Dishwasher Pacs, 115, $18.99 | — | $0.165/pac |
| 18 | KS Marble Cheddar, 1.15 kg, $14.99 | 1154953 | $1.303/100 g |
| 19 | KS Coastal Cheddar, 810 g, $18.99 | 1918390 | $2.344/100 g — 80% more |
| 20 | KS Rolled Oats, 4.54 kg, $11.99 | — | $0.264/100 g |
| 21 | KS Organic Sugar, 4.54 kg, $16.99 | — | $0.374/100 g |
| 22 | KS Basmati Rice, 5 kg, $24.99 | — | $0.500/100 g |
| 23 | KS Precooked Bacon, 500 g, $24.99 | 1527958 | **$49.98/kg — highest per-kg food item in the dataset** |
| 24 | KS Crumbled Bacon, 567 g, $12.99 | 190316 | $22.91/kg |
| 25 | KS Snacking Nuts Variety Pack, 30 × 45 g, $31.99 | 720827 | $2.370/100 g |
| 26 | KS Salted Mixed Nuts, 1.13 kg, $25.99 | 1645578 | $2.300/100 g — **the tub is cheaper per gram than the snack packs** |
| 27 | KS Shelled Walnuts, 1.36 kg, $15.99 | 36285 | $1.176/100 g |
| 28 | KS Mini Chocolate Chip Cookies, 30 × 28 g, $18.99 | 5014935 | $2.261/100 g |
| 29 | KS Frozen Chocolate Chunk Cookies, 6 kg, $36.99 | 1455819 | $0.617/100 g — **3.7× cheaper** |
| 30 | KS Protein Bars, 20-count, $38.99 | 1014809 | $1.950/bar |
| 31 | KS Chewy Protein Bars, 42 × 40 g, $22.99 | 1377067 | $0.547/bar — **3.6×** |

**Arithmetic re-checked independently:**
- 30 × 380 = 11,400; 32.99 ÷ 114 = $0.2894 per 100 sheets. ✓
- 36 × 231 = 8,316; 37.99 ÷ 83.16 = $0.4568 per 100 sheets. ✓
- 0.4568 ÷ 0.2894 = 1.578 → **58% more per sheet**. ✓
- 11,400 − 8,316 = **3,084 fewer sheets** for $5.00 more. ✓
- 29.40 ÷ 24.99 = 1.176 → **17.6% more per kg**; 39.99 − 33.99 = **$6.00**. ✓
- 0.725 ÷ 0.417 = 1.739 → **74% more per pod**. ✓
- 1.950 ÷ 0.547 = 3.565 → **3.6× per bar**. ✓
- 2.261 ÷ 0.617 = 3.665 → **3.7× per 100 g**. ✓
- 15.99 ÷ 12.33 = 1.297 → **46% more per litre** (Italian vs Spanish). ✓
- 15.99 ÷ 10.33 = 1.548 → **55% more** (Italian vs pure). ✓
- 0.211 ÷ 0.171 = 1.234 → **23% more per load**. ✓
- 0.273 ÷ 0.171 = 1.596 → **60% more per load**. ✓
- 2.344 ÷ 1.303 = 1.799 → **80% more per 100 g**. ✓
- 4 loads/wk × 52 = 208 loads; 208 × ($0.273 − $0.171) = **$21.22/yr**. ✓ ("about twenty-one dollars")

---

## 3. THE ONE COMPETITOR COMPARISON SPOKEN — AND ITS CAVEAT

**Spoken:** KS dishwasher pacs, 115 for $18.99 ($0.1651/pac) vs Walmart Great Value, 90 for
$16.97 ($0.1886/pac). Costco wins by $0.0235/pac, which over 115 pacs is **$2.70**.

- Costco figure: **tier (a)**, costco.ca, 19 Sept 2026.
- Walmart figure: **tier (b)**, Flipp/Wishabi e-commerce index, 19 Sept 2026, postal code
  M5V 3L9. Walmart.ca direct returned a bot wall.

**The script speaks the caveat out loud** — that Costco was priced online (above shelf) and the
competitor online too, that this stacks the comparison against Costco at both ends, and that the
real answer is almost certainly better for Costco than $2.70.

**PRODUCER ACTION:** if this pair cannot be re-shot in both stores in the same week, cut the
$2.70 beat and keep the paragraph about retailers blocking price checks. That paragraph carries
the segment on its own and is the honest core of it.

---

## 4. NON-PRICE CLAIMS

| Claim as spoken | Tier | Source |
|---|---|---|
| Gold Star $65, Executive $130, plus tax | (a) | costco.ca/join-costco.html, 19 Sept 2026 |
| Fee increase effective 1 Sept 2024, filing names Canada | (a) | 8-K Ex-99.1, 10 July 2024, SEC |
| Prior increase 2017; one increase in nine years | (a)+(b) | 2024 8-K primary; 2017 via CBC |
| 2% reward, capped $1,250 | (a) | costco.ca membership terms |
| Break-even $3,250/yr, ~$270/month | (a) | $65 ÷ 0.02 = $3,250; ÷ 12 = $270.83 ✓ |
| "the reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid" | (a) | verbatim, costco.ca |
| "we will refund your membership fee in full at any time if you are dissatisfied" | (a) | verbatim, Costco Canada CCSS89 v2.0, pub. 09/10/2025 |
| 90-day electronics returns | (a) | Costco Canada CCSS87 v4.0, pub. 10/10/2025 |
| 2-year warranty extension on TVs, projectors, major appliances, computers where manufacturer's is shorter | (a) | customerservice.costco.ca a_id/1017381 |
| Free phone tech support, English and French | (a) | same |
| 30-day price adjustment at the membership counter | (a) | Costco Canada CCSS124 v3.0, pub. 09/10/2025 |
| Consumer Reports on derivative models, "shoppers can't directly compare…" | (b) | CR, James K. Willcox, 12 Nov 2009 — **names Costco explicitly** |
| Manufacturers, not Costco, drive derivative models | (b) | same — this is why the script refuses the "by design" intent claim |
| Sony K65S20M2 / Hisense 65U68SG model numbers | (a) | costco.ca `productAttributes` → Model |
| "our poultry complex" / "operating losses from our poultry complex" | (a) | Costco FY2020 Form 10-K, SEC |
| Galanti 2015 "eat, if you will, thirty to forty million dollars a year in gross margin" | (b) | Fortune, 29 May 2015, crediting Consumerist |
| Starbucks custom-roasts certain KS coffee | (a) | **Costco's own product page**, key features |
| Leclerc Foods makes KS Nut Bars | (b) | WSJ, Sarah Nassauer, 10 Sept 2017 — Costco executives on the record in the story |
| Sonova supplied KS hearing aids, ended 2022 | (b) | Sonova's own announcement; hearing trade press |
| "certain information may be proprietary or confidential and will not be disclosed" | (a) | verbatim, Costco KS enquiry page |
| Costco Canada KS page names zero manufacturers | (a) | costco.ca/f/-/kirkland-signature |
| 115 Canadian warehouses, up from 108 | (a) | 8-K Ex-99.1, 8 July 2026, SEC (115 as at 5 July 2026); 108 as at 10 July 2024 |
| Renewal rate 92.3% US and Canada | (a) | Costco FY2025 Form 10-K |
| Riel: "Over 61% of our Kirkland Signature items are now manufactured in Canada" | (a) | House of Commons AGRI, Evidence No. 91, 13 Feb 2024 |
| Narcity rotisserie chicken $9, May 2026 | (d) | named outlet, **spoken only as "the most recent named Canadian outlet says nine dollars as of May, which is four months stale"** — never as a current price |

---

## 5. MANDATORY PHRASINGS — SPEAK THESE AS WRITTEN

1. **"I like Costco… this isn't one of those videos where a Canadian with a microphone tells you
   the warehouse is a scam. It isn't."** — the register the whole video depends on.
2. **"Every price here is Costco's online price. The warehouse shelf price is sometimes
   different."** — cannot be cut. It is the load-bearing caveat of the entire dossier.
3. **"I priced Costco online, which runs above the warehouse shelf. And I priced the competitor
   online too… That stacks the comparison against Costco at both ends at once."**
4. **"I won't invent one and read it to you with confidence."**
5. **"Is Costco sitting in a room designing it to frustrate you? Nobody has shown me that, and I
   won't say it."** — kills the intent claim the reference made.
6. **"Note what that actually says, because it's constantly mis-quoted. That's margin Costco
   chose not to collect by holding a price. It is not a statement that the bird sells below
   cost, it's a US price point, and it's eleven years old."**
7. **"I'm not putting a number on your screen and calling it national."** (rotisserie chicken)
8. **"There is no source for that. Not a filing, not a supplier statement, not one named
   outlet."** (the protein-bar supplier claim)
9. **"That's Costco's own number, items rather than dollars."** (the 61% figure)
10. **"The Tim Hortons bag is on offer right now… So the gap I just gave you is the gap at its
    narrowest."** — fairness against our own strongest beat. Do not cut.

---

## 6. PRODUCER ACTIONS BEFORE SHOOTING

1. **Re-verify every one of the 31 prices in §2 on the warehouse shelf, on camera.** The
   online/warehouse gap is real and inconsistent and cannot be modelled with a flat adjustment.
2. **Film the sheet counts on both toilet paper packs.** That is the closing beat and it lives
   or dies on the packaging shot. 380 vs 231.
3. **Declare the shooting city on screen.** Costco.ca resolved to warehouse 894, unmapped.
   Flipp data used M5V 3L9. Prices vary by province.
4. **Film the shelf tag for the Tim Hortons coffee** — it is on promotion to 28 September 2026.
   If the video publishes after that date, the regular price is $54.99 and the gap widens
   sharply. **Re-shoot or re-voice that beat if publishing after 28 September.**
5. **Re-shoot the dishwasher pac pair in both stores, same week, or cut it** (see §3).
6. **B-ROLL: no right-hand-drive vehicles. Bilingual packaging must be visible.** Canadian
   commenters caught both failures on competing videos; "AI slop" was the top comment on a
   143,000-view competitor upload.
7. **Music bed low.** Two separate complaints on the competitor videos.
8. **Refresh §4's warehouse count and any corporate figures if publishing after early October
   2026** — Costco's FY2026 10-K was not filed as of 19 Sept 2026.
9. **Do not open a comment thread on ingredients.** It fills with health claims. Every comment
   prompt in the script asks for a number, a place or a receipt.
10. **Pin the closing prompt** — "one number, one town" — and follow through on the promise to
    name towns in the next video. The promise is the mechanism.

---

## 7. DO-NOT-USE — 22 ITEMS

Nothing below may appear in the script, the thumbnail, the title, the description or the
pinned comment.

1. **"Costco loses $30–40 million a year on rotisserie chicken."** False framing of a real 2015
   quote about forgone gross margin from holding a US price point. Corrected version only.
2. **Any Canadian rotisserie chicken price** — $7.99, $9.07, or any other. Costco publishes none.
3. **"Kirkland protein bars are made by the same manufacturer as Premier Protein."** No source.
   Three content farms name three different manufacturers; one concedes it cannot confirm.
4. **Any Kirkland supplier beyond Starbucks, Leclerc and Sonova.** Specifically do not name
   Duracell, Ocean Spray, Reynolds, Jelly Belly, Niagara Bottling, Kimberly-Clark, LeVecke,
   Standard Functional Foods, Come Ready Foods or Quest.
5. **"The Hawkins Cheezies multi-pack is unavailable at US Costco."** Unsupportable — Costco's
   US catalogue search could not be run at all, and Cheezies are sold in the US by importers.
6. **"Costco carries different model numbers by design."** Intent claim. Not sourced.
7. **Any claim that Costco TVs undercut Best Buy, Amazon or Walmart.** Untested — all blocked.
8. **"Kirkland chocolate almonds rose from ~$17 to ~$30."** No support. Current price $26.99.
9. **Any Costco Canada pizza, hot dog, gasoline, optical, hearing aid or base tire price.**
   None is published; all sources are SEO aggregators. The $1.50 hot dog combo exists in a CBC
   piece dated 30 July 2025 but is stale and is not spoken.
10. **Any alcohol segment.** Provincial liquor law varies; the reference video was hammered by
    five separate commenters over a whiskey claim.
11. **Canada-vs-US segment operating margin (5.10% vs 3.42%).** Verified and tier (a), but it
    reads as a gouging implication in a buy/skip video. It belongs in a membership video.
12. **Any health, nutrition, ingredient or additive claim of any kind**, including protein
    grams, "clean," "healthy," oils, packaging chemicals or preservatives.
13. **The 2025 US rotisserie chicken preservative lawsuit.** Unresolved allegation, off-thesis.
14. **Animal-welfare litigation or campaign material.** Not researched, not included.
15. **"Costco makes no effort to identify Canadian products in store."** Affiliate/SEO only.
16. **Whether the Nebraska plant supplies Canada** — in either direction. No Costco statement.
17. **The date or venue of the 2015 Galanti call.** Transcript not retrieved.
18. **"$450 million" as a settled figure for the poultry plant.** Reported as both $400M and $450M.
19. **Canada-only Kirkland product lists** (Bee Maid honey, Zinetti lasagna, Natura soy,
    Citadelle syrup). SEO-only. Photograph labels instead.
20. **Any Costco Business Centre price.** Business Centre publishes none without a business
    delivery address, and it is a different store format from the warehouse regardless.
21. **Every quarantined comment** — health claims, wrongdoing allegations, the named-role
    workplace allegation, the olive-oil litigation reference, the shareholding claim, and the
    religious-slaughter cluster.
22. **Charmin 30-pack as a settled price.** Three Costco-sourced feeds gave three different
    prices on the same day ($39.99 / $33.49 / $26.49). Not spoken in the script. Film the tag.

---

## 8. COMMENT MODERATION

The dossier's audience mining found that ingredient and additive threads open fast on Costco
content and fill with material that cannot be engaged with under house rules. Every comment
prompt in the script asks for a **number, a place or a receipt** instead:

- Maple syrup grade off the bottle, plus province.
- Kirkland toilet paper sheets per roll, rolls, price, province.
- TV model number at Costco vs the same string elsewhere.
- Rotisserie chicken price and town.
- Closing: one number, one town — item, Costco price, other store's price, location.

**Do not reply to ingredient, additive or health comments at all.** Do not rebut them, do not
correct them, do not engage. Reply only to comments carrying a price, a sheet count, a model
number or a location, and reply with the arithmetic.

**Expected attacks and the honest answers:**
- *"You didn't compare to Superstore/Walmart."* — Correct, and the script says so out loud and
  says why. Point to the paragraph.
- *"Those are online prices."* — Correct, and the script says so in the first ninety seconds.
- *"Protein bars are cheaper in my province."* — Likely true. Regional variation is real. Ask
  for box count, price and province and use it in the next video.
- *"This is AI slop."* — the defence is the sourcing: SEC filings, parliamentary testimony,
  verbatim policy text with document numbers, and item numbers on every price.
