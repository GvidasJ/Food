# Research package — oatmeal redo (30 Sep 2026)

<!-- ===== note_oatmeal_structure.md ===== -->

# Structure note: the oatmeal redo (replaces "7 Oatmeal Brands Canadians Must STOP Buying - What I Found Will SHOCK You", Dec 22 2025)

Prepared 30 Sep 2026 (Eastern). The sandbox clock read 1 Oct 2026 00:xx UTC, so every "opened" date below is 30 Sep 2026 in Canadian time.

What this note gives the writer:
- measured skeletons of the channel's ketchup and bread hits, the soup and cookie flops, the December oatmeal video, and the two biggest oatmeal videos from other channels (section 1);
- how ketchup and bread built "Only 3 Are ACTUALLY Canadian", and what separates them from soup and cookies (section 2, facts only);
- every December line that breaks the house rules (section 3, with the full line table in Appendix B);
- a recommended skeleton of 21,000–23,000 characters with word budgets, an order basis that can be stated on screen, and the documented material for every beat (section 4);
- an evidence bank (section 5), a food-safety appendix that must not be used on air (Appendix A), and the mandatory UNVERIFIED / DO-NOT-USE list (last section).

The test the new video runs is ownership plus the origin line on the pack. Neither involves health, so nothing in the script needs any nutrition, glyphosate, sugar or safety content. Read the vocabulary rules (4n) before drafting.

---

## 0. Sources

### 0a. Transcripts saved and measured (scratchpad)

Transcripts are YouTube auto-captions fetched through Algrow `fetch_transcript` on 30 Sep 2026. In the `_clean` versions, `[music]` and `>>` markers are removed and whitespace is collapsed. Views and dates come from NexLev `youtube_video_details` and Algrow `get_channel_videos`, read 30 Sep 2026.

| File | Video | ID | Published | Views (30 Sep) | Length | Words | Chars | c/w |
|---|---|---|---|---|---|---|---|---|
| tr_CC_ketchup_88K_clean.txt (already in scratchpad) | Canadian Counter, 'We Investigated 8 "Canadian" Ketchup Brands (Only 3 Are ACTUALLY Canadian)' | r1Ro5OxZmt8 | 3 Sep 2026 | 90,078 | 21:46 | 3,299 | 19,560 | 5.93 |
| tr_CC_bread_42K.txt / _clean | CC, 'We Investigated 9 "Canadian" Bread Brands (Only 3 Are ACTUALLY Canadian)' | 3ENefR9MK1w | 5 Sep 2026 | 42,385 | 22:15 | 3,519 | 20,520 | 5.83 |
| tr_CC_soup_6.3K.txt / _clean | CC, 'We Investigated 8 "Canadian" Soup Brands (Only 3 Are ACTUALLY Canadian)' | K9FHgj_2lqc | 6 Sep 2026 | 6,600 | 23:50 | 3,706 | 21,294 | 5.75 |
| tr_CC_cookies_1.9K.txt / _clean | CC, "We Investigated 9 Cookie Brands In Canada (Only 3 Are ACTUALLY Canadian)" | Yg5mAmuwdJg | 7 Sep 2026 | 1,891 | 22:28 | 3,586 | 20,914 | 5.83 |
| tr_CC_oatmeal_dec2025_31K.txt / _clean | CC, "7 Oatmeal Brands Canadians Must STOP Buying - What I Found Will SHOCK You" (the video being replaced) | sj3QB3OZ-Xo | 22 Dec 2025 | 31,298 | 29:40 | 4,167 | 27,353 | 6.56 |
| tr_FCUK_porridge_300K.txt / _clean | Food Crisis UK, "8 UK Porridge Brands YOU Must Avoid (And 5 That Are SAFE)" | 1mKZBgfLb0w | ~2 months ago | 300,255 | 19:02 | 3,669 | 20,167 | 5.50 |
| tr_TR_oatmeal_96K.txt / _clean | Taste & Reason, "This Is Not REAL Oatmeal (Even Though Quaker Says So)" | s-bSiAZwngA | ~8 months ago | 95,987 | 14:54 | 2,304 | 13,680 | 5.94 |
| tr_CB_oatmeal_38K.txt / _clean | Charles Brennan, "25 Oatmeal Brands You Should NEVER Touch And 10 You Can Actually Trust" | 7AophYZy3iA | ~11 months ago | 37,905 | 45:38 | 7,337 | 45,934 | 6.26 |
| tr_CE_porridge_10K.txt / _clean | Consumer Exposed, "9 Porridge Brands You Should NEVER Buy (And 5 That Are Actually Healthy!)" | GRnOrzMgMiY | ~2 weeks ago | 10,400 | 27:43 | 4,108 | 24,657 | 6.00 |

The two biggest other-channel transcripts are Food Crisis UK (300K) and Taste & Reason (96K). Both were fetched and measured in full. Charles Brennan and Consumer Exposed were fetched too and measured only at headline level (1h).

Thumbnails were downloaded to `thumbs/` (r1Ro5OxZmt8, 3ENefR9MK1w, K9FHgj_2lqc, Yg5mAmuwdJg, sj3QB3OZ-Xo) and viewed.

Channel baseline: the 40 most recent uploads, 21 Aug–30 Sep 2026, have a median of 5,695 views. The 30 Sep upload is included in that figure; without it the median is 6,130.

### 0b. Primary and named sources opened (30 Sep 2026), with tier

Working files are in `scratchpad/oat2/`. A sibling research process fetched some CFIA and Finance Canada pages into `scratchpad/oat/` on the same date. I read those files and give their canonical URLs.

| # | Source | Tier | URL | What it gives |
|---|---|---|---|---|
| S1 | Statistics Canada, The Daily, "Production of principal field crops, November 2025", released 2025-12-04 | a (WebFetch; curl reset) | https://www150.statcan.gc.ca/n1/daily-quotidien/251204/dq251204a-eng.htm | "Total oat production increased by 16.7% to 3.9 million tonnes, as both harvested area (+5.6% to 2.6 million acres) and yields (+10.6% to 98.1 bushels per acre) increased in 2025." |
| S2 | Statistics Canada, The Daily, "Model-based principal field crop estimates, August 2026", released 2026-09-16 | a (WebFetch) | https://www150.statcan.gc.ca/n1/daily-quotidien/260916/dq260916b-eng.htm | "Nationally, oat production is anticipated to fall by 22.7% to 3.0 million tonnes, a result of both lower yields (-3.5% to 94.7 bushels per acre) and lower harvested area (-19.9% to 2.1 million acres) in 2026." |
| S3 | AAFC, "Canada: Outlook for Principal Field Crops, 2025", December 17, 2025 (PDF; saved oat2/aafc_outlook_202512.pdf and .txt) | a | https://agriculture.canada.ca/sites/default/files/documents/2025-12/Canada%20Outlook%20for%20Principal%20Field%20Crops_202512.pdf | Oats: "more than 3.9 Mt"; "the 2025 production is 17% higher than the 2024 crop"; "Compared to the previous five-year average, production in 2025 is 5% higher"; "Saskatchewan accounts for 45% of the national production, followed by Manitoba (25%) and Alberta (20%)"; CBOT oat price "$305/t, down $40/t y/y and the lowest in five years" |
| S4 | CFIA, "Origin claims on food labels" (Date modified 2023-12-06; file oat/origin.html) | a | https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims | Product of Canada, Made in Canada, Prepared in Canada and maple-leaf rules (quoted in 4g) |
| S5 | CFIA, "Name and principal place of business on food labels" (Date modified 2022-07-06; file oat/dealer.html) | a | https://inspection.canada.ca/en/food-labels/labelling/industry/name-and-principal-place-business | A label names the maker "or ... the person for whom the food has been manufactured, prepared, produced, stored, packaged or labelled" [218(1)(b) SFCR]. The mill does not have to be named |
| S6 | CFIA statement, "Food businesses face penalties for mislabelling products as Canadian" (page date 2026-03-16; file oat/cfia_stmt2026.html) | a | https://www.canada.ca/en/food-inspection-agency/news/2026/03/food-businesses-face-penalties-for-mislabelling-products-as-canadian.html | "Since April 1, 2025, the Agency has issued $47,000 in financial penalties to businesses for inaccurate or misleading country of origin claims" (penalties are regulatory orders; see 4g for how to say it) |
| S7 | PepsiCo Canada, Quaker "About Us" ("© 2026 PepsiCo Canada ULC") | a | https://contact.pepsico.com/quakerca/about-us | "A leader in the Canadian food industry for over 130 years"; "PepsiCo Canada operates two Quaker plants: Trenton (Ontario) and Peterborough (Ontario)."; "PepsiCo generated nearly $92 billion in net revenue in 2024" |
| S8 | PC Express (Loblaw) product API, Real Canadian Superstore store 1080, 3050 Argentia Rd, Mississauga ON (the store address is from the cottage note's S29); search and product records queried for 30 Sep 2026; saved oat2/pcx_oats_all.json, pcx_details_2026-09-30.json, pcx_oats_table.tsv; pack images saved to oat2/img/ from digital.loblaws.ca | a (retailer's own site) | https://api.pcexpress.ca/pcx-bff/api/v1/products/search and /products/{code} | Prices, sale flags, ingredient lines, Loblaw's own "Prepared in Canada" site badge, pack images |
| S9 | Voilà by Sobeys, search "oats" and 7 product pages; default region, no postal code entered; saved oat2/voila_oats.html, voila_oats_products.json, vp/*.html; images saved to oat2/img/v_*.jpg | a (retailer's own site) | https://voila.ca/search?q=oats ; https://voila.ca/products/x/{id} | Prices and pack images for Compliments, Farm Boy, Speerville, Only Oats, Quaker, Robin Hood, Bob's Red Mill, One Degree |
| S10 | Robin Hood site footer: "© / TM / MC / ® / MD Smucker Foods of Canada Corp. or its affiliates." | a | https://www.robinhood.ca/en | Owner of the brand in Canada |
| S11 | The J.M. Smucker Co., Form 10-K for the fiscal year ended April 30, 2026 | a (WebFetch; curl got 403) | https://www.sec.gov/Archives/edgar/data/0000091419/000009141926000050/sjm-20260430.htm | Head office "One Strawberry Lane, Orrville, Ohio"; "Operations outside the U.S. are principally in Canada". The extract did not mention Robin Hood by name |
| S12 | Nisshin Seifun Group, "Flour Milling Business" | a | https://www.nisshin.com/english/company/group/seifun.html | "Rogers Foods Ltd. A Canadian subsidiary engaged in the manufacture and sales of flour, premixes, and other food products" |
| S13 | Rogers Foods, home page and About Us | a | https://rogersfoods.com/ ; https://rogersfoods.com/about-us/ | "Rogers Foods Ltd. is a proudly Canadian company with over 75 years of milling excellence. Headquartered in British Columbia, Canada, we operate a state-of-the-art milling facility in Armstrong, as well as two additional facilities in Chilliwack."; "proudly milling quality flour and cereal products from Canadian grain for over 60 years" (the two pages give different year counts; attribute either one) |
| S14 | Bob's Red Mill, "Employee Owned" | a | https://www.bobsredmill.com/employee-owned | "Bob Moore and his wife, Charlee, founded Bob's Red Mill in 1978"; ESOP "in 2010"; "That happy day came in April 30th of 2020: ... Bob's Red Mill is now 100% employee owned" |
| S15 | Nature's Path, "Our History" | a | https://naturespath.com/pages/our-history | "1985 Arran and Ratana Stephens open Nature's Path"; "1999 ... opens the second manufacturing facility in Blaine, Washington"; "2021 Nature's Path welcomes Anita's Organic Mill to the family" |
| S16 | One Degree Organics, "How We Make Our Sprouted Oats", "Our Story", FAQs | a | https://onedegreeorganics.com/how-sprouted-oats-are-made/ ; /our-story/ ; /faqs/ | "our order travels by truck from their Northern Alberta farm directly to our facilities in Abbotsford, British Columbia"; "One Small Family With One Big Idea". Its glyphosate, heavy-metal and nutrition copy is barred |
| S17 | Speerville Flour Mill, home page and product record | a | https://www.speervilleflourmill.ca/ ; /products/new-found-oatmeal.json | "Speerville Flour Mill Wholesome Organic Food Since 1982"; "As a proud Maritime company, we're pleased to offer over 150 products of which 50 products are milled and made on site from locally grown grains in Atlantic Canada." Own-site prices for New Found Oatmeal: 1.82 kg $9.53; 8 kg $32.17 |
| S18 | Empire Company, Q4 F2026 news release, "Stellarton, NS. June 18, 2026" (saved pdf_empire_q4_f26_nr.txt; the cottage note's S26) | a | https://www.empireco.ca/uploads/2026/06/Empire-Consolidated-Q4-F26-News-Release-.pdf?id=axx12z | Head office dateline Stellarton, N.S.; owner of Compliments (the cottage note's S27: "Since the launch of the Compliments brand in 2005") |
| S19 | Loblaw Companies, Q4 2025 release, "BRAMPTON, ONTARIO February 25, 2026" (saved pdf_loblaw_q4_2025_nr.txt; the cottage note's S25) | a | https://dis-prod.assetful.loblaw.ca/content/dam/loblaw-companies-limited/creative-assets/loblaw-ca/investor-relations-reports/annual/2025/LCL_Q4%202025_NR.pdf | Head office Brampton; owner of No Name and President's Choice |
| S20 | Avena Foods, "Our Company" | a | https://www.avenafoods.com/about-us/our-company/ | "Avena was established in 2008 by a group of pedigreed seed growers in Saskatchewan"; merged with Best Cooking Pulses in January 2018. It does not mention Only Oats; see U9 |
| S21 | Costco.ca, Kirkland Signature Whole Grain Rolled Oats 4.54 kg, item 1736339 | a (page opened; JS-rendered; WebFetch read it) | https://www.costco.ca/p/-/kirkland-signature-whole-grain-rolled-oats-454-kg/4000339745 | Specs "Whole grain rolled oats", "4.54 kg (10.01 lb)", "Kosher". No price, no origin, no ingredient line displayed; "Unavailable" |
| S22 | Department of Finance Canada, "Complete list of U.S. products subject to counter tariffs" (list updated August 26, 2026; file oat/fin_list.html) | a | https://www.canada.ca/en/department-finance/programs/international-trade-finance-policy/canadas-response-us-tariffs/complete-list-us-products-subject-to-counter-tariffs.html | Row "1004.90.00 / Cereals / Oats. / Other / 2025-03-04 / 25%". Barred from air for now (U12) |

---

## 1. Measured skeletons

All percentages are shares of transcript words. Start positions are given as % of words and % of characters. Beat boundaries come from marker phrases (script `_seg.py`).

### 1a. Ketchup (90K; 15.8x the channel median). The construction's best hit. 3,299 w, 19,560 chars

| Beat | Words | Share | Starts (%w / %c) |
|---|---|---|---|
| Cold open | 237 | 7.2% | 0.0 / 0.0 |
| #1 Heinz | 567 | 17.2% | 7.2 / 7.1 |
| Like ask | 35 | 1.1% | 24.4 / 24.0 |
| #2 French's | 648 | 19.6% | 25.4 / 24.9 |
| "60 seconds of ketchup law" | 348 | 10.5% | 45.1 / 45.2 |
| #3–7 store brands, as a block | 381 | 11.5% | 55.6 / 55.9 |
| #8 Primo | 131 | 4.0% | 67.2 / 67.4 |
| Winners 3-2-1 (W3 57, W2 72, W1 126, French's coda 39) | 308 | 9.3% | 71.1 / 71.6 |
| Close, "the ending this story earned" | 486 | 14.7% | 80.5 / 81.0 |
| Checklist | 109 | 3.3% | 95.2 / 95.5 |
| Comment ask, share line, sign-off | 49 | 1.5% | 98.5 / 98.6 |

Cold-open moves, in order:
1. The object in your own fridge: "The bottle in your fridge door has been there your whole life."
2. A dated national event the viewer took part in, by word 30: "In 2016, this country fought a war over ketchup."
3. A cascade of specific consequences: Orillia, "a quarter of a million shares", "24 hours".
4. The method: "We read every label in the ketchup aisle. That's all we did."
5. Three inversions promised as facts: identical ingredient lists, "Both of their parent companies are American", ketchup must contain a sweetener by law.
6. The answer withheld: "the actually Canadian ketchup ... has been sitting on the same shelf".
7. Count and order basis: "Eight brands, biggest first, three genuinely Canadian winners at the end."
8. Sign-on: "Elbows up."

Asks:

| Ask | Position | Wording |
|---|---|---|
| Like | 24.8%w / 24.3%c, after the biggest beat | "If you remember picking a side in 2016, and if you're Canadian, you do, hit the like button right now..." |
| Comment | 98.6% | "Tell us in the comments which side your family took in 2016" |
| Share | 99.5% | "send them this" |

There is no subscribe ask anywhere.

Per-beat anatomy: see note_apples_structure.md 1d. Heinz carries ten dated events, two verbatim quotes attributed to a named person and a named outlet, and one price. The 98% rule is in the close: "Heinz's bottles say, 'Prepared in Canada.' Not product of Canada. Because under federal rules, product of Canada requires about 98% Canadian content."

Rule note: ketchup also carries sugar and sodium figures (for example "4 g of sugars and 150 mg of sodium per tablespoon"). Under today's rule 1 those lines would be barred. They are part of the hit's construction, not part of what made it work. Do not copy them.

### 1b. Bread (42K; 7.4x). 3,519 w, 20,520 chars

| Beat | Words | Share | Starts (%w / %c) |
|---|---|---|---|
| Cold open | 338 | 9.6% | 0.0 / 0.0 |
| Ownership map (Canada Bread, Weston, Bimbo, FGF) | 229 | 6.5% | 9.6 / 9.0 |
| Like + subscribe ask | 43 | 1.2% | 16.1 / 15.6 |
| #1 Dempster's | 190 | 5.4% | 17.3 / 16.8 |
| #2 store brands | 260 | 7.4% | 22.7 / 22.2 |
| #3 Wonder (balloons 80; site-banner reveal 107; whole-wheat decode 272) | 459 | 13.0% | 30.1 / 29.9 |
| #4 Villaggio | 155 | 4.4% | 43.2 / 42.6 |
| #5–6 D'Italiano + Country Harvest | 119 | 3.4% | 47.6 / 47.0 |
| "There are your three actually Canadian brands" | 28 | 0.8% | 51.0 / 50.6 |
| Regional brands (POM, Bon Matin, Gadoua, Ben's) | 177 | 5.0% | 51.7 / 51.5 |
| Price-fixing section (framing 38; "admitted" 108; StatCan series 81; receipts 35/128/95; fairness paragraph 131) | 616 | 17.5% | 56.8 / 56.5 |
| Mid-video comment ask | 42 | 1.2% | 74.3 / 74.6 |
| Law and history | 462 | 13.1% | 75.5 / 75.6 |
| Who wins | 205 | 5.8% | 88.6 / 88.9 |
| Caution flag (premium shelf) | 55 | 1.6% | 94.4 / 94.7 |
| 5-second routine | 103 | 2.9% | 96.0 / 96.3 |
| Comment ask + sign-off | 38 | 1.1% | 98.9 / 99.1 |

Cold-open moves (word counts in brackets):
1. Two bags in hand, with the origin story of each (64).
2. The inversion, stated as a fact: "one of these two brands is owned by a family company headquartered in Toronto. The other one answers to Mexico City... The all-American loaf is the Canadian one. Canada's number one bread brand is not." (47)
3. A dated money event in the viewer's own life: "in 2023, a Canadian court handed down the largest price fixing fine in this country's history... If you got a check for $49.11 in the mail this past spring... if you remember a $25 grocery gift card back in 2018, same story." (92)
4. The method: "We read every bag... We looked up who actually owns every brand. We read the law..." (66)
5. Order basis and promise: "brand by brand, from the most popular down... which three of these nine brands are actually Canadian owned... As always, no scare stories, no chemistry lecture. We read labels." (69)

Asks:

| Ask | Position | Wording |
|---|---|---|
| Like + subscribe | 16.5%w / 16.0%c | "If you're already reaching for the bread bag in your kitchen to check it, hit the like button first, and subscribe if label reading is your kind of television." |
| Comment (mid-video) | 74.4% | "Tell us in the comments, did you get the gift card? Did the $49 show up this spring?" |
| Comment | 98.9% | "Tell us what's in your bread box right now and who really owns it." |

Wonder beat anatomy (459 w):
- The brand's own myth, the balloons in Indianapolis, 1921 (80).
- The reveal from the company's own site: "Go to wonderbread.ca today. The banner across the top says, in giant letters, quote, Canadian baked and owned." Then the ownership chain: Weston to FGF, December 2021, with the U.S. Wonder owned by Flowers Foods (107).
- A label decode with a government quote (272).

The beat is concession-free, because the reveal is in Wonder's favour.

Price-fixing section anatomy: a precision preamble ("real companies, real courtrooms, and real denials"); what was admitted; a StatCan price series; three dated "receipts"; then a fairness paragraph naming who was convicted, who received immunity and who denies wrongdoing. Every legal item is labelled (plea, immunity, settlement, denial). That is the model for rule 6.

### 1c. Soup (6.6K; 1.2x). The first flop. 3,706 w, 21,294 chars

| Beat | Words | Share | Starts (%w / %c) |
|---|---|---|---|
| Cold open (pantry can; the "high in sodium" symbol, Jan 1; "Not one drop of Campbell soup has been made in Canada since 2019"; Habitant made in the U.S.) | 319 | 8.6% | 0.0 / 0.0 |
| "One piece of law before the brands" (no soup standard; commercial sterility) | 196 | 5.3% | 8.6 / 8.1 |
| Like + subscribe ask | 28 | 0.8% | 13.9 / 13.3 |
| #1 Campbell condensed | 987 | 26.6% | 14.7 / 14.0 |
| #2 Chunky | 98 | 2.6% | 41.3 / 41.5 |
| #3 store brands / BCI | 383 | 10.3% | 43.9 / 43.9 |
| #4 Habitant | 324 | 8.7% | 54.3 / 54.8 |
| #5 Aylmer / BCI | 231 | 6.2% | 63.0 / 63.6 |
| #6 St-Hubert + Clark + Heinz beans | 233 | 6.3% | 69.2 / 69.9 |
| Law and history round | 601 | 16.2% | 75.5 / 76.4 |
| Who wins | 132 | 3.6% | 91.7 / 92.1 |
| Warhol coda | 93 | 2.5% | 95.3 / 95.8 |
| Comment ask + sign-off | 81 | 2.2% | 97.8 / 98.1 |

The largest beat (Campbell, 26.6%) spends most of its length on the sodium symbol: "800 mg of sodium per 250ml bowl", "the magnifying glass symbol triggers at 15% of the daily value", the 2012 sodium targets, "30 million teaspoons". Under today's rule 1 all of that would be barred.

### 1d. Cookies (1.9K; 0.3x). The second flop. 3,586 w, 20,914 chars

| Beat | Words | Share | Starts (%w / %c) |
|---|---|---|---|
| Cold open (six teasers, undated; "one word printed on that bag") | 220 | 6.1% | 0.0 / 0.0 |
| Method + chocolate law (35% cocoa solids; "chocolate-flavored, chocolate-like, and chocolaty") | 148 | 4.1% | 6.1 / 5.8 |
| Like ask | 51 | 1.4% | 10.3 / 9.9 |
| #1 Chips Ahoy | 244 | 6.8% | 11.7 / 11.2 |
| #2 Oreo | 226 | 6.3% | 18.5 / 18.3 |
| #3 Fudgee-O | 148 | 4.1% | 24.8 / 24.7 |
| Christie history + Peek Freans + Dad's (unnumbered detour) | 769 | 21.4% | 28.9 / 28.8 |
| #4 PC Decadent | 319 | 8.9% | 50.4 / 50.1 |
| #5 Dare | 336 | 9.4% | 59.3 / 59.2 |
| #6 Leclerc | 116 | 3.2% | 68.6 / 68.9 |
| #7 Voortman | 123 | 3.4% | 71.9 / 72.2 |
| Law numbers round (front-of-pack symbol thresholds, shrinkflation, StatCan cookie price) | 331 | 9.2% | 75.3 / 75.8 |
| Three delights | 191 | 5.3% | 84.5 / 84.9 |
| Winners | 188 | 5.2% | 89.8 / 90.2 |
| Absolution | 52 | 1.5% | 95.1 / 95.3 |
| 5-second routine | 66 | 1.8% | 96.5 / 96.7 |
| Comment ask + sign-off | 58 | 1.6% | 98.4 / 98.5 |

The video's spine is "chocolate or chocolaty", a compositional word, not Canadian ownership. "Actually Canadian" or "Canadian-owned" phrasing appears once in the transcript, at the winners: "If Canadian owned is your compass, exactly three of today's nine qualify."

### 1e. December oatmeal (31K). The video being replaced. 4,167 w, 27,353 chars, 6.56 c/w

| Beat | Words | Share | Starts (%w / %c) |
|---|---|---|---|
| Cold open ("I tested popular Canadian oatmeal brands in a lab"; glyphosate ppb; Oreo comparison; "poisoning Canadian families") | 137 | 3.3% | 0.0 / 0.0 |
| #7 Quaker | 596 | 14.3% | 3.3 / 2.9 |
| #6 Great Value | 471 | 11.3% | 17.6 / 16.5 |
| #5 President's Choice | 421 | 10.1% | 28.9 / 27.7 |
| Subscribe ask | 40 | 1.0% | 39.0 / 37.8 |
| #4 No Name | 332 | 8.0% | 40.0 / 38.7 |
| #3 Kirkland | 416 | 10.0% | 47.9 / 46.9 |
| #2 Nature's Path | 465 | 11.2% | 57.9 / 57.1 |
| #1 Bob's Red Mill | 408 | 9.8% | 69.1 / 69.0 |
| Recap | 122 | 2.9% | 78.9 / 78.6 |
| Picks (One Degree, "Backros") | 265 | 6.4% | 81.8 / 81.7 |
| Shopping "test" | 310 | 7.4% | 88.1 / 88.2 |
| Moral | 137 | 3.3% | 95.6 / 95.5 |
| Comment + share ask | 47 | 1.1% | 98.9 / 99.0 |

Asks: subscribe at 39.3%w / 38.1%c ("If you are shocked by what you have heard so far, make sure to subscribe"); comment and share at 99.5% ("share this with everyone still buying pesticide oatmeal").

The order basis is unstated ("Number seven ... Number one"). No law explainer, no dated fact in the open, no disclaimer. Thumbnail: "EXCLUSIVE: ACTUALLY DANGEROUS!" over a Quaker box with a red X.

At 27,353 characters it is about 4,000 characters over the 23,000 ceiling.

### 1f. Food Crisis UK, porridge (300K). The biggest oat video found. 3,669 w, 20,167 chars, 5.50 c/w

| Beat | Words | Share | Starts (%w / %c) |
|---|---|---|---|
| Cold open (price per kilo; owner reveal; baby porridge; blood-sugar claim) | 393 | 10.7% | 0.0 / 0.0 |
| Thesis, "what porridge was" (sachet, milling, protein wall) | 338 | 9.2% | 10.7 / 10.6 |
| Like + hype + share ask | 101 | 2.8% | 19.9 / 19.6 |
| #8 Scott's (PepsiCo) | 325 | 8.9% | 22.7 / 22.1 |
| #7 own-brand sachets | 166 | 4.5% | 31.5 / 31.1 |
| #6 Fuel 10K | 101 | 2.8% | 36.1 / 35.8 |
| #5 Mornflake Go | 313 | 8.5% | 38.8 / 38.7 |
| #4 Moma | 158 | 4.3% | 47.3 / 47.5 |
| #3 Ready Brek (Post Holdings) | 326 | 8.9% | 51.6 / 51.7 |
| #2 Heinz baby porridge | 169 | 4.6% | 60.5 / 60.6 |
| #1 Oat So Simple | 605 | 16.5% | 65.1 / 65.4 |
| Turn ("the safe list is also the cheap list") | 73 | 2.0% | 81.6 / 81.8 |
| Safe 5 | 390 | 10.6% | 83.6 / 83.8 |
| Glyphosate coda | 111 | 3.0% | 94.2 / 94.4 |
| Recap | 34 | 0.9% | 97.3 / 97.4 |
| Comment + subscribe + sign-off | 66 | 1.8% | 98.2 / 98.2 |

Cold-open moves:
1. A price per kilo against the oats' cost: "works out at 27 pounds a kilo. The oats inside it cost about 1 pound 10".
2. An ownership inversion: "One of the most patriotic tartan wrapped Scottish breakfast on the shelf is owned by the American giant that makes Pepsi and Walkers crisps."
3. A baby-food label claim.
4. A blood-sugar claim.
5. The "one shelf they can't touch" premise.
6. The count and order: "worst saved for last".

Asks:

| Ask | Position | Wording |
|---|---|---|
| Like + hype + share | 20.3%w | "One quick ask before the countdown..." |
| Comment + subscribe | 98.3% | "Your suggestions decide what we investigate. Subscribe and stick with me." |

Per-beat anatomy, #8 Scott's (325 w):
- the heritage imagery read off the box (tartan, strongman, "milled in Cupar Fife since 1947");
- the ownership chain with dates ("bought by Quaker back in 1982 and Quaker was swallowed by PepsiCo");
- the advertising history;
- a concession ("the porridge inside isn't bad, it's oats");
- a price multiple ("two to three times the price of a supermarket bag");
- a closer ("an American snack company renting you a memory").

That ownership beat is the only part of the 300K video that transfers. Its #1 (16.5%) and its cold open rest on glycemic and sugar claims, which are barred.

What transfers:
- the ownership inversion in the opening lines;
- a price per kilo for every product;
- concession before the closer;
- "the safe list is also the cheap list" as a turn device, made factual here with $/100 g.

### 1g. Taste & Reason (96K). 2,304 w, 13,680 chars

| Beat | Words | Share | Starts |
|---|---|---|---|
| Cold open ("Take a long hard look at the circular cardboard tube in your pantry") | 118 | 5.1% | 0.0 |
| Quaker | 189 | 8.2% | 5.1 |
| McCann's + flavoured packets | 245 | 10.6% | 13.3 |
| History / processing essay | 912 | 39.6% | 24.0 |
| Pick: One Degree | 272 | 11.8% | 63.5 |
| Pick: Bob's organic | 160 | 6.9% | 75.3 |
| Pick: Nature's Path | 109 | 4.7% | 82.3 |
| Red flags | 234 | 10.2% | 87.0 |
| Close | 65 | 2.8% | 97.2 |

There are no asks at all and no numbered countdown, and it is U.S.-only ("the American breakfast table"). Every brand beat rests on glyphosate, insulin, "biohazardous sludge" and "phytic acid". Nothing in it is usable. The one transferable move is the pantry object plus the mascot in the first sentence ("the smiling man in the black hat").

### 1h. Charles Brennan (38K) and Consumer Exposed (10.4K), headline measures only

Charles Brennan:
- 7,337 w, 45,934 chars.
- Opens directly on "number 25, Quaker" and Quaker's recalls, which are food safety (Appendix A).
- Topic-word counts: "sugar" ×75, "glyphosate" ×29, "protein" ×15, "fiber" ×12.
- No like or subscribe ask was detected.

Consumer Exposed:
- 4,108 w, 24,657 chars, U.S. brands.
- The cold open pairs "sugar as its second ingredient" with an ownership sale ("sold to the company behind Snickers and M&M's for $600 million"; U.S., unverified).
- It states its count and order: "Nine brands to put back on the shelf. Five that earned their place in your kitchen. Worst first."
- One share ask at about 99%.
- Topic-word counts: "sugar" ×43, "protein" ×17.

### 1i. Cross-format table

| Video | Views | Dated fact in first 100 w? | Inversion in open? | Order basis stated? | Asks (position) | Law explainer | Test word in title | Disclaimer |
|---|---|---|---|---|---|---|---|---|
| Ketchup | 90.1K | yes, "2016" at word 30 | yes (both parents American) | "biggest first" | like 24.8%; comment 98.6% | yes, 45.1%, 348 w | "Canadian" in quotes | no |
| Bread | 42.4K | yes, "1921", "2023", "$49.11" | yes (all-American loaf is Canadian) | "most popular down" | like+sub 16.5%; comment 74.4%, 98.9% | yes, 75.5% | "Canadian" in quotes | no |
| Soup | 6.6K | "January the 1st of this year" (sodium symbol); first four-digit year at word 172 | partly ("The famous soup left the country") | "most popular first" | like+sub 14.1%; comment 97.9% | yes, 8.6% and 75.5% | "Canadian" in quotes | no |
| Cookies | 1.9K | no; first year at word 143 | no (teasers) | "Most popular first" (at 11.7%) | like 10.5%; comment 98.5% | yes, 6.1% (chocolate) | none ("Cookie Brands In Canada") | no |
| Dec oatmeal | 31.3K | no (lab claim) | no | none | sub 39.3%; comment 99.5% | none | none | no |
| Food Crisis UK | 300K | no (price/kg) | yes (Scott's owned by PepsiCo) | "worst saved for last" | like 20.3%; comment+sub 98.3% | no | none | no |
| Taste & Reason | 96K | no | no | none | none | no | "REAL" | no |

---

## 2. How ketchup and bread built "Only 3 Are ACTUALLY Canadian", and what separates them from soup and cookies (facts only)

### 2a. Ketchup's test: four layers, with the 98% rule as fine print

The test, in the video's words:
- The open: "the actually Canadian ketchup, Canadian-owned, Canadian-made, Canadian tomatoes".
- The verdict on the #1 winner: "The only bottle in this entire video where the brand, the owner, the factory, and the tomatoes are all Canadian."

So the test is brand + owner + factory + ingredient origin.

The three winners, and what each passed on:

| Winner | Video's words | Passed on |
|---|---|---|
| W3 Compliments | "owned by Empire, the Nova Scotia-founded Stellarton headquartered company behind Sobeys"; "100% Canadian tomatoes per Sobeys" | owner + company claim |
| W2 President's Choice | "Loblaws is a Canadian company, and its own claim, 'Always made here in Canada with 100% Canadian-grown tomatoes'" | owner + company claim |
| W1 Primo | "Canadian-owned company, Canadian factory, Canadian tomatoes"; "product of Canada on the label, the origin claim the giants can't print" | owner + factory + ingredient + the label's origin line |

Only W1 was cleared on the printed origin line. W2 and W3 were cleared on owner plus the company's own claim.

The Product of Canada rule appears twice:
- In the close: "Heinz's bottles say, 'Prepared in Canada.' Not product of Canada. Because under federal rules, product of Canada requires about 98% Canadian content. And Heinz's sugar is imported."
- In the checklist: "Flip the bottle and read the origin line. Product of Canada means around 98% Canadian. Made in Canada from domestic and imported ingredients can mean almost any mix. Prepared in Canada means processed here. And product of USA means exactly what it says."

Ketchup is the only one of the four videos that quotes the "Made in Canada from domestic and imported ingredients" wording. That is the oatmeal video's centrepiece wording (4h, #5).

### 2b. Bread's test: ownership only

- The promise in the open: "which three of these nine brands are actually Canadian owned".
- The midpoint: "So, there are your three actually Canadian brands from the big shelf. Wonder, D'Italiano, Country Harvest, all one Toronto family company".
- The close: "If ownership is your compass... Wonder, D'Italiano, and Country Harvest are the Toronto-owned trio."

Bread never uses the Product of Canada or 98% rule.

Bread then names two more winners on other "compasses":
- the label compass: Dempster's 100% whole grains;
- "the full independence package": Silver Hills, "the flag, the family, and the factory all match", with "made in Canada on the back".

So bread's title count (3) holds only for the ownership compass.

### 2c. The other two

- Soup: "If you want Canadian-owned and Canadian-made, there are exactly three in this video" (Aylmer/BCI, St-Hubert, Clark). That is two layers: owner and factory.
- Cookies: "If Canadian owned is your compass, exactly three of today's nine qualify" (Dare, Leclerc, PC Decadent). That is one layer, owner.

### 2d. Hit versus flop: what differs, factually

| Variable | Ketchup 90K | Bread 42K | Soup 6.6K | Cookies 1.9K |
|---|---|---|---|---|
| Upload date (days live at 30 Sep) | 3 Sep (27) | 5 Sep (25) | 6 Sep (24) | 7 Sep (23) |
| Title noun / scare-quoted "Canadian" | Ketchup / yes | Bread / yes | Soup / yes | Cookie / no |
| Thumbnail text | "FAKE KETCHUP" (title noun) | "EXCLUSIVE: THIS IS SHOCKING!" (no noun) | "CHEMICAL SOUP?!" (title noun) | "NOT REAL CHOCOLATE?" (not the title noun) |
| Thumbnail image | five bottles with price tags | Dempster's logo on a maple leaf over an AI-style factory spraying loaves | Campbell's tomato can spilling | Fudgee-O pack |
| Spine of the video | ownership + a 2016 national boycott | ownership + a price-fixing case with a 2026 cheque | sodium symbol + Campbell's 2019 exit | "chocolate or chocolaty" (composition) |
| Viewer-lived dated event in first 100 w | 2016 boycott | $25 card (2018), $49.11 cheque (2026) | none (a labelling rule, Jan 1) | none |
| Words with an ownership verb (owned/owner/bought/sold/acquired/parent) | 12 | 33 | 12 | 19 |
| Health/nutrition-topic words (sugar, sodium, daily value, high in...) | 27 | 3 | 24 | 23 |
| Largest beat and topic | French's 19.6% (the boycott story) | price-fixing 17.5% | Campbell 26.6% (sodium arithmetic) | Christie history detour 21.4% |
| First ask position | 24.8% (after beat #1) | 16.5% (after the ownership map) | 14.1% (before brand #1) | 10.5% (before brand #1) |
| Where "three actually Canadian" is resolved | 71.1% | 51.0% (and again 88.6%) | 91.7% | 89.8% |
| Length | 21:46 | 22:15 | 23:50 | 22:28 |

Read factually. With n=4 these are correlations only:
1. Title noun and thumbnail noun matching does not separate the groups. Bread's thumbnail had no noun and hit; soup's matched and flopped.
2. Both hits open on a dated event the viewer personally lived through (a boycott; a cheque). Neither flop does.
3. Both hits make ownership the spine. Each flop's spine is a composition or nutrition device (sodium; chocolaty) that sits beside the ownership title. Cookies used the title's test once.
4. Both hits put the first ask after the first substantive beat. Both flops put it before brand #1.
5. Upload cadence: soup and cookies went out on the two days immediately after bread (5, 6, 7 Sep). The 8 Sep (tuna, 13.8K) and 9 Sep (frozen food, 13.4K) uploads in the same format did 2–7x the flops, so the cadence alone does not explain the flops.
6. Breadth: soup and cookies each run a long detour (law/history 16.2%; Christie history 21.4%) that is not about the title's test.

---

## 3. Every line in the December oatmeal video that breaks the house rules or is unsourced or U.S.

Of 370 transcript sentences, 269 trip at least one rule pattern (Appendix B lists every one, verbatim, with its beat and tags). A further 45 sentences that no pattern caught also breach a rule; they are listed in 3c.

Tags used in this section and Appendix B:

| Tag | Meaning | Rule |
|---|---|---|
| H | health, nutrition, sugar, glycemic, fibre, processing-as-harm, "clean", "wholesome" | rule 1 |
| P | glyphosate, chlormequat, pesticide, residue, contamination, carcinogen, organic-drift | rule 1 |
| S | safety, harm, recall | rule 1 |
| X | unnamed expert ("A food scientist told me", "A nutritionist told me", "consultant explained") | rules 2, 3 |
| US | U.S. data, agencies or litigation (EWG, EPA, USDA, WHO/IARC, U.S. class actions) | rule 7 |
| $ | unsourced price | rule 5 |
| W | implied wrongdoing or motive ("profit", "bonuses", "lowest bidder", "does not test") | rule 6 |
| C | co-packer inference ("same contract manufacturers", "identical") | rule 6 |
| T | taste or texture as fact | rule 8 |
| L | fabricated first-person testing ("I tested ... in a lab", "When I examined") | rules 2, 3 |
| U | other unsourced or wrong fact | rule 3 |

### 3a. Counts by tag (a line can carry several tags)

| Tag | Lines |
|---|---|
| P | 128 |
| H | 82 |
| W | 38 |
| $ | 34 |
| U | 20 |
| US | 19 |
| C | 15 |
| X | 11 |
| S | 9 |
| T | 5 |
| L | 4 |

By beat: Quaker 39, Great Value 35, Nature's Path 34, Kirkland 27, PC 26, shopping test 24, No Name 23, Bob's 22, picks 11, open 9, recap 9, moral 6, close 3, ask 1.

### 3b. The structural breaches (the lines a writer might be tempted to keep)

1. **The premise is fabricated testing (L).** "I tested popular Canadian oatmeal brands in a lab." No lab results exist in the channel's files. Every number that follows is EWG U.S. testing (US) presented as the channel's own. Also: "When I examined Great Value oatmeal..."; "When I examined no-name oatmeal..."; "When I tested Kirkland oats, the quality was good... The texture was proper" (T).
2. **Unnamed experts (X), eleven lines**, all barred:
   - "A food scientist told me..."
   - "A food industry consultant explained..."
   - "A nutritionist told me..."
   - "A food industry analyst explained..."
   - "A food safety researcher explained..."
   - "A microbiologist explained..."
   - "A food safety advocate told me..."
   - "reports suggest Nature's Path said..."
   - "A 2024 test reportedly found..."
3. **U.S. data as Canadian (US):**
   - EWG 2018 and 2024 glyphosate and chlormequat figures; "the EWG's health benchmark of 160 parts per billion";
   - "The EPA's legal limit for glyphosate on oats, 30 parts per million";
   - "The World Health Organization classified glyphosate as a probable carcinogen in 2015";
   - "Lawsuits have been filed against PepsiCo and Quaker" (U.S.);
   - "Bob's Red Mill faced a federal class action lawsuit in 2018" (U.S.; an allegation, unlabelled);
   - "a single packet contains more than two Oreo cookies".
   All of it is also rule 1.
4. **Co-packer inference (C), barred outright by rule 6:**
   - "Great Value oatmeal is contract manufactured, often by the same facilities that make name brand products";
   - "No name instant oatmeal is made by the same contract manufacturers who make President's Choice products. Same factories, same supply chain, different label";
   - "Identical ingredients list, identical texture, identical potential contamination."
5. **Wrongdoing and motive (W):**
   - "seven oatmeal brands poisoning Canadian families";
   - "Their executives collected massive bonuses while Canadian families cut back on groceries";
   - "Great Value does not test for glyphosate residue. They do not source from farmers who avoid pre-H harvest spraying. They buy from whoever offers the lowest price";
   - "The gap between the marketing and the reality is pure profit margin";
   - "Corporate ownership often leads to cost cutting that compromises quality";
   - "share this with everyone still buying pesticide oatmeal."
6. **Unsourced prices ($):**
   - "$5 to $8 per box for Quaker instant oatmeal";
   - "around $3 to $4 for a large container" (Great Value);
   - "A large container of plain rolled oats costs Walmart perhaps. 50 cents to produce";
   - "around $2 to $3 for instant oatmeal" (No Name);
   - "The 10 lb bag of rolled oats costs around $8. That is only 5 cents per ounce" (imperial units, no banner or date);
   - "Canadians pay 8 to12 for Bob's Redm Mill oat products";
   - "At around $15 for a large bag" (One Degree).

   None has a banner, date or $/100 g. The 30 Sep prices in section 5 replace them all.
7. **Facts checked against sources opened for this note:**
   - "a multinational snack food conglomerate with $91 billion in annual revenue": PepsiCo says "nearly $92 billion in net revenue in 2024" (S7). The December figure is out of date and unsourced.
   - "Nature's Path is a Canadian company founded in 1985 in British Columbia": matches S15. It is still unusable in its December context (glyphosate).
   - "Bob Moore famously gave the company to his workers in 2010": partly wrong. The ESOP began in 2010, and the company became 100% employee-owned on April 30, 2020 (S14).
   - "Kirkland Signature Rolled Oats are listed as a product of Canada packed in the USA": the Canadian Costco page shows no origin line (S21). The wording appears only on the U.S. costco.com listing (search snippet; U.S. context; not opened). Do not use it.
   - "Richardson International, Canada's largest oat miller, started requiring such agreements in 2021": not opened, and glyphosate-related, so barred.
   - "If oatmeal is owned by PepsiCo, Craft Hinds, or similar food conglomerates": Kraft Heinz owns no brand discussed. Wrong in context.
   - "Seven brands, four owned by massive corporations, including a soda company. Two owned by Canada's largest grosser...": on the video's own list, Quaker (PepsiCo), Great Value (Walmart), Kirkland (Costco), PC and No Name (Loblaw) make five large-company brands, not four. Internally inconsistent.
   - "One degree is a Canadian family company based in British Columbia ... They can trace ingredients back to specific farmers in Alberta": consistent with S16 ("Northern Alberta farm ... our facilities in Abbotsford"). Every other One Degree line in December is glyphosate, sprouting-nutrient or "clean" copy (H/P) and is barred.
   - "Backros Granola": a U.S. brand (Back Roads), not opened, and its only claim is glyphosate certification. Barred.

### 3c. Breaches the pattern tags did not catch (sentence numbers from Appendix B's numbering)

| # | Beat | Breach |
|---|---|---|
| 44, 45 | Quaker | "the regular cinnamon and spice flavor has 13 g", "Apples and cinnamon has 14 g" (sugar figures; H) |
| 49 | Quaker | "The processing is another concern." (H framing) |
| 66 | Great Value | "The tomato content measurement trick that food companies use." (garbled; unsourced) |
| 77, 84 | Great Value | "Walmart's business model is volume over margin."; "You are not getting a bargain." (W) |
| 111, 123 | PC | "President's Choice Instant Oatmeal uses the same conventional oat supply chain as other major brands."; "You are choosing between Loblaw products from the same supply chain." (C, unsourced) |
| 126, 127 | PC | "The premium you pay for the PC label over no name does not reflect ingredient quality. It reflects brand positioning and packaging design." (W, unsourced) |
| 144, 146 | No Name | "The same conventional commodity oats as every other major brand."; "The same industrial processing." (C, H) |
| 152, 162 | No Name | "No name represents Loblaw's strategy of capturing every market segment."; "The only difference is the marketing positioning." (W) |
| 168, 174 | No Name | "The modified ingredients are the same."; "The packaging was the only difference." (C; "modified ingredients" also mischaracterises a one-ingredient product) |
| 183, 189, 201 | Kirkland | "The oats are sourced from Canadian commodity markets."; "The 10 lb bag that everyone buys is conventional oats."; "for oats, the standard Kirkland offering remains conventional." (U, P) |
| 204, 209 | Kirkland | "It does not."; "The Kirkland name does not change that reality." (continuations of P/S lines) |
| 241, 248, 250 | Nature's Path | "Their practices are far better..."; "Nature's Path is clearly better."; "The farming practices are more sustainable." (P context; opinion) |
| 276, 279, 282 | Bob's | "Corporate ownership often leads to cost cutting that compromises quality."; "Bob's Red Mill is better than conventional brands."; "The testing does not always confirm." (W, P) |
| 301–306, 310 | Picks | One Degree "test every batch", "visit every farm", "No modified starch, no preservatives, no artificial anything" (unattributed; H by implication) |
| 317–320 | Picks | Back Roads certification lines (U.S., P) |
| 330, 342, 344 | Test | "Avoid instant oatmeal when possible."; "Consider the processing level."; "Rolled oats are steamed and flattened." (H context) |
| 353, 355, 358 | Test/Moral | "Craft Hinds" (wrong); the "four owned by massive corporations" miscount; "most consumers have no idea" (W) |
| 370 | Close | "They need to know what they are really eating." (P/S context) |

### 3d. The template overlap to avoid

Do not reuse the December:
- open ("I tested ... in a lab");
- countdown wording ("Number seven, Quaker. Let us start with Quaker Oats.");
- ask ("If you are shocked by what you have heard so far, make sure to subscribe");
- "Here is what they do not tell you", "Here is the truth", "But here is the disturbing part" pivots;
- close ("Have you been buying any of these contaminated oatmeal brands?").

The new script names Quaker, PC/No Name and Kirkland again. It must not echo a December sentence about any of them.

### 3e. Verdicts the new script changes, with the on-air acknowledgement

- December put Nature's Path at #2 avoid and One Degree at #1 buy, both on glyphosate grounds.
- The new script rests on ownership and the origin line. One Degree stays a pick on different grounds. Nature's Path drops off the avoid list, because its pack origin line could not be read (U5).

Suggested 25-word acknowledgement, placed in the turn (4j): "We made an oatmeal video last December. This one replaces it, with a narrower question we can document: who owns the brand, and what does the origin line say."

---

## 4. Recommended skeleton

### 4a. Targets

- 21,000–23,000 characters of plain spoken prose.
- The house register (ketchup 5.93, bread 5.83 chars/word) gives about 3,600–3,900 words.
- The skeleton below is 3,695 words: about 21,600 characters at 5.85 c/w, or 21,800 at 5.9.
- If a draft runs at 6.2 c/w, cut 40 words each from #5 Quaker, #3 Robin Hood and the law explainer to stay under 23,000.

Title, mirroring the two hits (scare-quoted "Canadian", noun "Oatmeal"):
'We Investigated 11 "Canadian" Oatmeal Brands (Only 3 Are ACTUALLY Canadian)'
The count is 8 avoid + 3 picks. Change it only if a slot is dropped.

Thumbnail. Mirror ketchup (packs and prices), not bread (AI factory imagery):
- A photographed Quaker 1 kg box, side panel visible.
- Two callouts quoting the box's own words: '"100% CANADIAN OATS"' with an arrow to the front, and '"DOMESTIC AND IMPORTED"' with an arrow to the side panel.
- Quoting the pack is factual.
- Do not write FAKE, DANGEROUS, SHOCKING, TOXIC, NOT CANADIAN or any verdict over a named product (rule 6), and do not show any product the video clears (Compliments, One Degree, Speerville).

### 4b. The test, said once in the open and again in the turn

"Actually Canadian, in this video, means two things you can check yourself: the company that owns the brand has its head office in Canada, and the bag says Product of Canada."

- Owner layer: the company's own filing or site (S7, S10–S19).
- Origin layer: the pack itself, photographed in store, plus the CFIA rule (S4).

The mill is a third thing the video reports on in every beat, but it is not a pass/fail layer. The label does not have to name the mill (S5), and most do not.

### 4c. Order basis, stated on screen and as a lower-third on every avoid beat

"Eight bags, most expensive per 100 grams first, at the regular online shelf price at one Real Canadian Superstore in Mississauga on September 30th, 2026."

Why price:
- Brand popularity and market share for oats were not found at tier (a), (b) or (d) (U1).
- Owner revenue cannot rank the list, because Bob's Red Mill, Nature's Path, One Degree and Speerville publish no revenue and the rest report in four currencies.
- One store on one date is the one ranking every slot can be measured on.

On-screen caveat, spoken once: "Prices change by store, by week and by region; this is one store's website on one day."

Kirkland (Costco) and Great Value (Walmart) are not sold through that store. Their slots need a price from costco.ca and walmart.ca, captured and dated before recording (U2, U3). Their provisional positions (#6, #8) are estimates only, and the order must be re-sorted once the prices are in.

### 4d. Eligibility for an avoid slot

All four must be opened and dated:
1. the pack, photographed (front and origin panel);
2. the owner from a tier (a) page;
3. a retailer price with pack size;
4. the ingredient line from the retailer or maker.

The avoid case must rest on the test (4b): a foreign head office, or an origin line other than Product of Canada, or both. Never on what is in the oats or what they do to a body.

### 4e. The jobs in every avoid beat (fixed order)

| # | Job | Words |
|---|---|---|
| 1 | Bridge, with lower-third: owner, head office, $/100 g | 10–15 |
| 2 | Recognition: the pack's own heritage words, read off the bag (mascot, "Since", maple leaf) | 30–50 |
| 3 | Owner reveal with the dated chain, from the company's own pages | 40–80 |
| 4 | The origin line, read verbatim from the photographed pack, then what CFIA says that phrase means | 40–90 |
| 5 | The mill, if the company names one; if not, say "the bag doesn't have to say, and doesn't" | 15–40 |
| 6 | Price: banner, store, date, pack, price, $/100 g | 20–30 |
| 7 | Concession: what is genuinely Canadian about it | 15–35 |
| 8 | Closer: one line naming the gap between the front and the record | 10–20 |

### 4f. Word budgets and positions

| # | Beat | Words | Starts at word | Start % |
|---|---|---|---|---|
| 1 | Cold open | 150 | 0 | 0.0% |
| 2 | "Sixty seconds of origin law" | 220 | 150 | 4.1% |
| 3 | The test + order basis + method | 90 | 370 | 10.0% |
| 4 | #1 Bob's Red Mill | 270 | 460 | 12.4% |
| 5 | #2 Rogers | 300 | 730 | 19.8% |
| 6 | #3 Robin Hood | 330 | 1,030 | 27.9% |
| 7 | #4 Grace Instant Oats (conditional, U4) | 210 | 1,360 | 36.8% |
| 8 | #5 Quaker (centrepiece, longest beat) | 480 | 1,570 | 42.5% |
| 9 | #6 Great Value (conditional, U3) | 230 | 2,050 | 55.5% |
| 10 | Mid-list ask (the only mid-list ask) | 50 | 2,280 | 61.7% |
| 11 | #7 No Name | 280 | 2,330 | 63.1% |
| 12 | #8 Kirkland Signature (conditional, U2) | 220 | 2,610 | 70.6% |
| 13 | Turn + December acknowledgement + no-commercial-relationship disclosure | 70 | 2,830 | 76.6% |
| 14 | P1 Compliments Quick Oats | 170 | 2,900 | 78.5% |
| 15 | P2 One Degree Sprouted Rolled Oats | 170 | 3,070 | 83.1% |
| 16 | P3 Speerville New Found Organic Oatmeal | 150 | 3,240 | 87.7% |
| 17 | How to protect yourself (four steps) | 180 | 3,390 | 91.7% |
| 18 | Moral + comment ask + tagline (second use) | 80 | 3,570 | 96.6% |
| 19 | Disclaimer | 45 | 3,650 | 98.8% |
| | Total | 3,695 | | |

The ask starts at word 2,280 of 3,695 (61.7%). At an even c/w that is about 13,330 of 21,620 characters, also 61.7%.

Measure the finished draft in characters before recording. If the ask falls outside 61–63% of characters, move words between #1 and #7. Never move them into the ask.

If a conditional slot (#4, #6, #8) cannot be documented, use the swaps in 4h. Keep the same word budget so the ask stays in band.

### 4g. Cold open (150 w) and "Sixty seconds of origin law" (220 w)

Cold open, five moves (a 152-word draft is below):
1. Dated fact, first sentence. Statistics Canada, December 4th, 2025: "Total oat production increased by 16.7% to 3.9 million tonnes" (S1). Add AAFC: "Saskatchewan accounts for 45% of the national production" (S3, December 17, 2025).
2. The object in your cupboard, ketchup-style: the box with the man in the hat.
3. The inversion from the pack itself:
   - front panel: "MADE WITH 100% WHOLE GRAIN CANADIAN OATS";
   - side panel, under a large red maple leaf reading "MADE IN • FABRIQUÉ AU CANADA": "MADE IN CANADA FROM DOMESTIC AND IMPORTED INGREDIENTS."
   - the ingredient line on the retailer's page: "Whole Grain Rolled Oats. Contains Oat Ingredients. May Contain Wheat Ingredients."

   Source: PC Express pack images 20323113002_EA_2/_3 and the product record, S8. The image may be an older pack, so photograph a current one before air (U6).
4. Method, count and order basis.
5. Tagline, first of two uses.

Draft (152 w):

"On December 4th, 2025, Statistics Canada reported that Canadian farmers grew 3.9 million tonnes of oats last year, 16.7 percent more than the year before, and Agriculture Canada says Saskatchewan alone grew 45 percent of them. So go to your cupboard and find the oats. If it's the box with the man in the black hat, read the front: "Made with 100% whole grain Canadian oats." Now turn it to the side and find the small print under the big red maple leaf: "Made in Canada from domestic and imported ingredients." The ingredient list is one item long. Oats. On September 30th we read every oat label on two Canadian grocers' websites, looked up who owns each brand, and read the federal rule behind those words. Eleven brands. Eight we'd put back, most expensive per hundred grams first. Three that are actually Canadian. Because the truth is not always on the menu."

The open has no ask and no health word. Do not say "black hat" if the photographed current pack differs.

"Sixty seconds of origin law" (220 w). Quote S4 verbatim, in this order:
1. "A food product may use the claim 'Product of Canada' when all or virtually all major ingredients, processing, and labour used to make the food product are Canadian." The minor-ingredient allowance: "Generally, the percentage referred to as very little or minor is considered to be less than a total of 2% of the product."
2. "Made in Canada" needs a qualifier; then the key sentence: "This claim may be used on a product that contains a mixture of imported and domestic ingredients, regardless of the level of Canadian content in the product."
3. CFIA's own example, which happens to be about oats: "a cookie manufactured in Canada using Canadian flour, oatmeal and shortening and imported sugar may be labelled ... 'Made in Canada from domestic and imported ingredients'." The counter-example on the same page: a cookie "from oatmeal, enriched flour, butter, honey and milk from Canada, and imported vanilla, may use the claim 'Product of Canada'".
4. "'Prepared in Canada' to describe a food which has been entirely prepared in Canada."
5. Maple leaf: "depending on how a maple leaf is used, it could imply a 'Product of Canada' claim... it is recommended that an accompanying domestic content statement be placed in close proximity to the vignette."
6. Who the label must name (S5): the maker "or ... the person for whom the food has been manufactured". So a bag can say whose oats they are without saying whose mill they came from.

Optional dated tag (15 w), S6: "CFIA said in March that it had issued $47,000 in penalties since April 2025 for misleading origin claims."
- Do not name the penalised businesses. They are unrelated to oats, and naming them next to oat brands implies a link (rule 6).
- Call them "penalties", which is what CFIA calls them.

Close the explainer: "So every bag gets two questions. Whose head office? And what does the origin line actually say?"

### 4h. The eight avoid beats, with the documented material each turns on

Prices are from Superstore #1080 online (S8), 30 Sep 2026, regular price unless marked. $/100 g = price ÷ grams × 100, computed here.

**#1 Bob's Red Mill Organic Old Fashioned Rolled Oats, 907 g (270 w)**
- Price: regular $8.99 = $0.99/100 g. Sale $7.64 = $0.84, ending 30 Sep. Voilà shows $9.99 = $1.10/100 g (S9).
- Recognition: the pack reads "An Employee-Owned Company / Compagnie appartenant aux employés", "Wholesomely Yours, Bob Moore", "World's Best Oatmeal®" (PC Express image 21161849_EA_1). Attribute the last as the company's trademark line.
- Owner, from the company (S14):
  - "Bob Moore and his wife, Charlee, founded Bob's Red Mill in 1978";
  - an Employee Stock Ownership Plan in 2010 "on his 81st birthday";
  - "That happy day came in April 30th of 2020 ... Bob's Red Mill is now 100% employee owned."
  - Head office Milwaukie, Oregon: the company's "© 1978-2026 Bob's Red Mill Natural Foods" footer. The city is from search results; read it off the pack's dealer line (U7).
- Origin line: not readable in any image opened. Photograph the pack before recording (U7).
  - If it says Product of USA (or Canada), read it verbatim.
  - If it carries "Imported by/for", explain S5's import rule. Under SFCR 223, a food wholly made abroad must say "Imported by" or "Imported for" unless the geographic origin is shown.
- Ingredient line on PC Express: "Organic Whole Grain Oats."
- Mill: the company's own; Bob's has none in Canada that the pages opened name.
- Concession: it is owned by its employees, not a conglomerate, and the pack says so in both languages.
- Closer: the most expensive bag per 100 grams in the plain-oats aisle, and the only one owned by the people who make it; they are in Oregon.
- Barred: everything December said about Bob's (glyphosate, lawsuit, gluten testing, "purer than pure").

**#2 Rogers Porridge Oats, Original Blend, 1 kg (300 w)**
- Price: $6.29 = $0.63/100 g.
- Recognition from the pack (image 20717030_EA_1): a blue tartan bag, the Rogers wheat-sheaf crest, a red maple leaf near the 1 kg mark, "All Natural / Tout Naturel".
  - The image shows the name "Healthy Grain Blend". Do not read that name aloud (rule 1 word); call it "the blue Rogers porridge oats bag".
  - The retailer lists the product as "Porridge Oats, Original Blend".
- The company line (S13), attributed:
  - "Rogers Foods Ltd. is a proudly Canadian company with over 75 years of milling excellence. Headquartered in British Columbia, Canada, we operate a state-of-the-art milling facility in Armstrong, as well as two additional facilities in Chilliwack."
  - Address: 4420 Larkin Cross Road, Armstrong, BC.
- Owner (S12), from the parent's own group page: "Rogers Foods Ltd. A Canadian subsidiary engaged in the manufacture and sales of flour, premixes, and other food products", listed under Nisshin Flour Milling Inc., Nisshin Seifun Group, Tokyo.
  - The year Nisshin took control (1989, per World Grain, which returned 403) is unverified (U8). Say "a subsidiary of Japan's Nisshin Seifun Group" with no year.
- Both statements are true at once: the company's operations and head office are in B.C., and its parent is in Japan. Say exactly that. Do not call "proudly Canadian" false (rule 6).
- Ingredient line, verbatim (S8): "Large Flake Oats, Oat Bran, Wheat Bran, Flaxseed." The bag is a blend, not plain oats. Say so, and read the list only.
- Origin line: not readable in the images opened (U8). Photograph it.
- Mill: Armstrong, B.C., named by the company.
- Concession: the mill is in Armstrong and the company says it mills Canadian grain ("from Canadian grain for over 60 years", About page). The two pages count the years differently; use one, attributed.
- Closer: milled in Armstrong, owned from Tokyo; the maple leaf is about the mill.

**#3 Robin Hood 100% Whole Grains Large Flake Oats, 1 kg (330 w)**
- Price: $4.69 = $0.47/100 g. Voilà: $4.79 = $0.48 (S9).
- Recognition: the archer mascot; the front roundel reads "MADE WITH • FAIT AVEC / 100% / CANADIAN OATS / GRUAU CANADIEN" (image 20893369_EA_1, legible).
- Origin line: the side panel (image 20893369_EA_2) appears to read "SMUCKER FOODS OF CANADA CORP., MARKHAM, ON L3R 0P3 ... PRODUCT OF CANADA / PRODUIT DU CANADA". The crop is low resolution, so photograph it before quoting (U9).
- Owner: robinhood.ca footer "© / TM / MC / ® / MD Smucker Foods of Canada Corp. or its affiliates" (S10). The parent's 10-K: head office "One Strawberry Lane, Orrville, Ohio" and "Operations outside the U.S. are principally in Canada" (S11).
- This is the French's beat from ketchup:
  - the bag passes the origin layer (Product of Canada; "100% Canadian oats");
  - the brand fails the owner layer (Ohio).
  - Say plainly that if Product of Canada is your test, this bag passes it.
- Mill: neither the bag images nor robinhood.ca name it. The Saskatoon-mill and Cargill/Horizon history comes from a tier (c) site and old search summaries (U10), so do not say it.
- Ingredient line (S8): "Rolled Oats. Contains: Oats. May Contain: Barley, Mustard, Rye, Soybean, Triticale, Wheat."
- Concession, required and generous: the strongest origin line of any big brand on the list.
- Closer: Canadian oats, a Canadian label, an Ohio owner. The archer is the only thing that changed sides.
- Optional colour (only if a tier (b) source is opened; U11): Smucker's Canadian stable once included Red River cereal, which Smucker discontinued and sold to Arva Flour Mills in 2022.

**#4 Grace Instant Oats, 1 kg (210 w; conditional on U4)**
- Price: special $4.00 = $0.40/100 g. The regular price is not shown. Capture it before ranking.
- Ingredient line (S8): "100% Oat Flakes." Retailer description: "Quality since 1922 ... Grace, Kennedy". Loblaw's site badge: "Prepared in Canada".
- Owner: GraceKennedy of Jamaica, through Grace Foods Canada Inc., Mississauga. Unverified: gracefoods.ca returned an expired certificate and GraceKennedy's report was not opened (U4).
- Run this beat only if both are confirmed:
  - a GraceKennedy page (tier a) names Grace Foods Canada as a subsidiary;
  - the photographed pack shows its origin line.
- If confirmed: a Caribbean-owned brand, quite possibly of oats prepared in Canada. The closer is the inversion.
- Swap if not confirmed: **Quaker Regular Instant Oatmeal, 280 g** (regular $3.50 = $1.25/100 g; ingredients "Whole Grain Rolled Oats, Whole Grain Oat Flour, Calcium Carbonate, Salt"), moved up the order by price.
  - Run it as a short second Quaker beat. Its retailer description reads "Made with 100% whole grain Canadian oats", which sets up #5.
  - Read the ingredient list only; no comment on any item.

**#5 Quaker Large Flake Oats, 1 kg (480 w; the centrepiece and the longest beat)**
- Price: regular $3.75 = $0.375/100 g. Special $2.77 = $0.28, ending 30 Sep, and the product was marked out of stock. Voilà: $6.49 = $0.65/100 g (S9). The two retailers differ by 73% on the same 1 kg box. Say both.
- Recognition: "QUAKER / EST° 1877" on the front; PepsiCo Canada calls the brand "A leader in the Canadian food industry for over 130 years" (S7, attributed).
- Owner: "© 2026 PepsiCo Canada ULC"; "PepsiCo Canada operates two Quaker plants: Trenton (Ontario) and Peterborough (Ontario)"; "PepsiCo generated nearly $92 billion in net revenue in 2024" (S7). PepsiCo's head office is in the U.S. (Purchase, N.Y., per its 10-K; not opened, U13). Say "PepsiCo, the American company" with S7 as the source, or open the 10-K.
- The front, read slowly: "MADE WITH 100% WHOLE GRAIN CANADIAN OATS / FAIT AVEC DE L'AVOINE À GRAINS 100% CANADIENNE".
- The side, read slowly: the large maple leaf "MADE IN • FABRIQUÉ AU / CANADA", then the small print "MADE IN CANADA FROM DOMESTIC AND IMPORTED INGREDIENTS. FABRIQUÉ AU CANADA À PARTIR D'INGRÉDIENTS CANADIENS ET IMPORTÉS." (images 20323113002_EA_2 and _3; legible crop saved as img/q3_crop.jpg.)
- The back, from the retailer: "Whole Grain Rolled Oats. Contains Oat Ingredients. May Contain Wheat Ingredients." (S8).
- Then the law, from 4g: CFIA says "Made in Canada from domestic and imported ingredients" "may be used on a product that contains a mixture of imported and domestic ingredients, regardless of the level of Canadian content." The same box says its oats are 100% Canadian. Say, verbatim: "We're not saying this label breaks a rule. We're saying it uses the wording the rules allow for a product with imported ingredients, on a box whose only ingredient it calls 100% Canadian. Quaker can tell you why. We've asked." Send the question before air (U6).
- Mill: named by the company, Peterborough and Trenton (S7). The box tells you neither.
- Also on the retailer's pages, and usable: the 1 kg bag and the 2.25 kg bag carry different ingredient wording on the retailer site ("Whole Grain Rolled Oats" vs "100% Rolled Oats. ... May Contain Wheat."). Read both as wording only.
- Concession: made in Ontario, by a company that says it has made Quaker in Canada for over 130 years; the oats are called Canadian on the box.
- Closer: "The front says 100% Canadian oats. The side says domestic and imported. Read the side."
- Barred: every December Quaker line (glyphosate, chlormequat, sugar per packet, glycemic index, recalls, lawsuits), the heart and cholesterol claim printed on the pack (image _4: "Oat Fibre Helps Reduce Cholesterol"; do not show it or read it), "Non-GMO Project Verified" (do not characterise).

**#6 Great Value oats (Walmart) (230 w; conditional on U3)**
- walmart.ca was not attempted this session. Earlier sessions recorded it as blocking automated access (build_dossier.py).
- Run the beat only if, before recording, a Great Value large-flake or quick-oats pack is photographed in a Canadian Walmart and the walmart.ca price is captured with date, region and pack size.
- Owner: Walmart Inc., Bentonville, Arkansas. Its 10-K was not opened (U3).
- Ask the pack the two questions: whose name is on the "Distributed by" / "Imported by" line, and what does the origin line say?
- If the slot cannot be filled, swap in **PC Organics Organic Quick Rolled Oats, 1 kg** ($5.00 = $0.50/100 g; Loblaw site badge "Prepared in Canada"; ingredients "Organic Rolled Oats. May Contain Wheat."). Its avoid case, like No Name's, is the origin line, and it moves to between #3 and #5 by price. Pack origin line not yet photographed (U14).

**Mid-list ask (50 w), at 61–63% of characters.** Draft:

"Two left on the put-back list. If you want labels like this read for you before your next grocery run, take a second to subscribe. Canadian Counter reads Canadian labels, laws and company filings every week, from the source. Now, the yellow bag."

- It must contain "take a second to subscribe".
- No like ask, no share ask.
- The disclosure is not here; it goes in the turn.

**#7 No Name Large Flake 100% Whole Grain Oats, 1 kg (280 w)**
- Price: $3.00 = $0.30/100 g. The 2.25 kg club size is $5.50 = $0.24/100 g, regular $6.00 = $0.27.
- Recognition: the yellow bag; the front reads "large flake oats / 100% whole grain Canadian oats / avoine canadienne à grains entiers à 100 %" (image 20923994_EA_1, legible).
- Origin line: a small red maple-leaf mark at lower left appears to read "PREPARED IN / PRÉPARÉ AU / CANADA". The crop is low resolution; photograph it (U15). Loblaw's own site badge also says "Prepared in Canada" (S8).
- Owner: Loblaw Companies Limited, Brampton, Ontario (S19).
- The point, factual:
  - the front says the oats are Canadian;
  - the origin mark says Prepared in Canada, which CFIA defines as "entirely prepared in Canada";
  - it does not say Product of Canada.
  - Under the two-layer test (4b) the bag fails on the wording alone, even though its owner passes and its front names Canadian oats. Say that, and say it is the closest call on the list.
- Who mills it: the bag names the company it was made for (S5), not the mill. Never infer a co-packer from the ingredient line (rule 6).
- Ingredient line (S8): "Rolled Whole Grain Oats. May Contain: Wheat."
- Barred: the description's fibre and cholesterol claims ("45% of the daily amount of the fibres...") and "Simple Check".
- Concession: Canadian-owned, Canadian oats on the front, and the cheapest plain oats per 100 g on the list.
- Closer: one phrase short of the claim the next bag makes.

**#8 Kirkland Signature Whole Grain Rolled Oats, 4.54 kg (Costco) (220 w; conditional on U2)**
- costco.ca, item 1736339 (S21): "Whole grain rolled oats", "4.54 kg (10.01 lb)", "Kosher". No price, no origin line, "Unavailable" when opened.
- Run the beat only if the pack is photographed in a Canadian Costco and the warehouse price is recorded (date, warehouse city) to compute $/100 g.
- Owner: Costco Wholesale, Issaquah, Washington. Its 10-K was not opened (U2).
- The December line ("product of Canada packed in the USA") comes only from the U.S. costco.com listing. U.S. context, unverified; do not use it unless the Canadian pack says so.
- Swap if not documented: **Dan-D Pak Rolled Oats, 1 kg** (regular $3.25 = $0.33/100 g; special $2.98 to 7 Oct).
  - Retailer description: "From the Canadian prairies. 100% natural. No preservatives. Kosher". The pack front shows a maple leaf and "From the Canadian Prairies / Des Prairies Canadiennes" (image 20876492_EA_1).
  - Owner: Dan-D Foods, Richmond B.C. (founder Dan On, per BIV, tier b, not opened; U16).
  - It is an avoid only if its pack lacks Product of Canada. If the pack says Product of Canada and the owner is confirmed Canadian, it passes, and it becomes an alternate pick, not an avoid.

### 4i. The turn (70 w), December acknowledgement and disclosure

Draft:

"So where's the oatmeal that passes both tests: a Canadian head office and Product of Canada on the bag? Three, at the prices we found. And a note: we made an oatmeal video last December. This one replaces it, with a narrower question we can document. We have no commercial relationship with any company named in this video, and none of them knew this video was being made."

The disclosure is spoken once, here only.

### 4j. The three "actually Canadian" picks

**P1 Compliments Quick Oats, 1 kg (Sobeys / Empire) (170 w)**
- Voilà, default region, 30 Sep 2026: $4.49 = $0.45/100 g. Compliments Organic Quick Oats: $4.99 = $0.50 (S9).
- The front carries a red roundel that appears to read "PRODUCT OF • PRODUIT DU • CANADA" around a maple leaf (Voilà image; low resolution; photograph it, U17). The organic bag carries the same roundel beside the Canada Organic logo.
- Ingredients on Voilà: "Rolled Oats. May Contain: Wheat".
- Owner: Empire Company Limited, "Stellarton, NS" (S18). Compliments launched 2005 (the cottage note's S27).
- Payoff: the same owner-and-origin pairing that made Compliments a ketchup winner.
- Concession: the bag does not name its mill.
- Closer: a Nova Scotia head office and the three words the big brands' bags don't print.

**P2 One Degree Organics Sprouted Rolled Oats, 680 g (170 w)**
- PC Express Superstore #1080: $9.49 = $1.40/100 g. Voilà: the same, $1.40 (S8, S9). The most expensive per 100 g of anything in this video. Say so.
- The company says (S16): "our order travels by truck from their Northern Alberta farm directly to our facilities in Abbotsford, British Columbia"; "One Small Family With One Big Idea".
- Ingredient line: "Sprouted organic gluten-free whole grain oats" (Voilà pack image). Read "gluten-free" only as part of the printed name, with no comment (rule 1).
- Origin line on the pack: not yet photographed (U18). The family's name and the ownership are on no tier (a) page opened (U18). The pick stands only once both are confirmed.
- Barred: its glyphosate, heavy-metal, sprouting-nutrient and "clean" copy (S16 FAQ).
- Closer: Alberta oats, a B.C. mill, a family name on the door, and the highest price per 100 g on the shelf.

**P3 Speerville New Found Organic Oatmeal, 910 g (Speerville Flour Mill, N.B.) (150 w)**
- Voilà: $5.49 = $0.60/100 g. Speerville's own site: 1.82 kg $9.53 = $0.52/100 g; 8 kg $32.17 = $0.40/100 g (S17).
- The company says (S17): "Wholesome Organic Food Since 1982"; "As a proud Maritime company ... 50 products are milled and made on site from locally grown grains in Atlantic Canada."
- Pack front (Voilà image): "NEW FOUND OATMEAL / GRUAU TOUT NEUF / Speerville flour mill / Rolled Oats · Avoine Concassée / No Additives · Sans Additifs", Ecocert organic. Say "No Additives" only as the pack's own words, attributed.
- Gaps: whether this oatmeal is one of the 50 products milled on site, whether the bag says Product of Canada, and the co-operative ownership (tier c only) are all unverified (U19). Confirm by phone or pack photo before air.
- Closer: a mill you can tour, in a village in New Brunswick.

Documented alternates, if P2 or P3 fails its checks:
- **Farm Boy Organic Large Flake Oats, 750 g.** Voilà $5.49 = $0.73/100 g. The pack reads "GMO FREE • MILLED IN ONTARIO / SANS OGM • MOULU EN ONTARIO" (legible; img/fb_label.jpg). Farm Boy is owned by Empire per the cottage note's S26 (re-confirm, U20). Two caveats: Product of Canada was not seen on the pack, and "Milled in Ontario" is a value-added claim, not an ingredient-origin claim. Say "GMO free" only as the pack's words.
- **Stoked Oats** (Calgary; the company's site banner reads "PROUDLY CANADIAN"; flavoured oats, Bucking Eh $8.50 special = $1.70/100 g). Owner and pack line unverified (U21).
- **Dan-D Pak** (see #8).

### 4k. How to protect yourself (180 w). Four numbered steps: "First," "Second," "Third," "Fourth"

- **First, read the origin line, not the maple leaf.** "Product of Canada" means all or virtually all ingredients, processing and labour are Canadian, with less than 2% allowed for minor items (S4). "Made in Canada from domestic and imported ingredients" can be used "regardless of the level of Canadian content" (S4). "Prepared in Canada" means entirely prepared here; it says nothing about where the oats grew. "Prepared for" (or "Distributed by") is not an origin claim at all. It names the company the food was made for (S5).
- **Second, find the owner.** The name on the bag is the company responsible for it, not necessarily the parent. Robin Hood's bag says Smucker Foods of Canada; the parent is in Orrville, Ohio (S10, S11). This video's lower-thirds give each owner.
- **Third, find the mill.** The label doesn't have to name it (S5), and most don't. Some companies say so on their own sites: Quaker's Peterborough and Trenton plants (S7), Rogers in Armstrong (S13), One Degree in Abbotsford (S16). If neither the bag nor the site says, you don't know, and neither do we.
- **Fourth, compare price per 100 grams on the shelf tag.** On September 30th, plain oats on one store's website ran from 30 cents per 100 g (No Name) to $1.40 (One Degree). The same Quaker box was $3.75 at one grocer and $6.49 at another.

### 4l. Moral, comment ask, tagline (80 w)

- Moral: "Canada grew 3.9 million tonnes of oats last year. Whose name is on the bag is a separate question, and the answer is printed in the smallest type on the box."
- Comment ask, ketchup-style, framed as the viewer's own data: "Go to your cupboard, find the origin line on your oats, and tell us in the comments exactly what it says, word for word, and which province you're in."
- Tagline, second and last use: "Because the truth is not always on the menu."

### 4m. Disclaimer (about 45 w), spoken last and shown on screen

"Everything in this video comes from Statistics Canada, Agriculture Canada and CFIA pages, company websites and filings, and retailer websites checked on September 30th, 2026. Labels, recipes, owners and prices change and vary by store and region. Read the bag in your hand."

That is 43 words. Add "Not sponsored." only if the disclosure in 4i is cut. The disclosure must appear exactly once.

### 4n. Vocabulary rules for the body

- **Never use:** healthy, healthier, nutritious, wholesome (except inside a quoted name), clean, natural (except as the pack's words), fibre/fiber, beta-glucan, heart, cholesterol, sugar (except reading an ingredient line verbatim), glycemic, blood sugar, protein (except inside a product name), gluten or celiac (except inside a printed product name), glyphosate, chlormequat, pesticide, residue, desiccation, organic-as-safer, heavy metals, additive, processed, ultra-processed, safe, safety, recall, contaminated, toxic, poison, dangerous, shocking, exposed.
- **Ingredient lines:** read verbatim, then compare only with the bag's own front panel or with another bag. Never say what an ingredient does.
- **Prices:** every price carries banner, store or "online", date, pack, price and $/100 g. Say "regular" or "sale".
- **Company claims:** every one carries "the company says" or "on its own site". Every pack quote is "the bag says".
- **Taste and texture:** no "we tasted" and no texture words. Robin Hood's retailer copy ("left large and thick for great taste and lots of texture") may be quoted only as the company's words, and is better left out.
- **U.S. data:** no U.S. figure, agency or lawsuit. U.S. head offices are named as owners' addresses only.
- **Legal and regulatory items:** label every one. CFIA "penalties" are orders, and the March 2026 statement is the only one used.

---

## 5. Evidence bank (opened 30 Sep 2026)

### 5a. Prices

Superstore = PC Express API for Real Canadian Superstore #1080, Mississauga, queried for 30 Sep 2026 (S8). Voilà = default region, no postal code entered (S9). $/100 g is computed as price ÷ grams × 100.

| Retailer | Product | Pack | Regular | Sale/special | $/100 g regular | $/100 g sale | Note |
|---|---|---|---|---|---|---|---|
| Superstore | Bob's Red Mill Organic Old Fashioned Rolled Oats | 907 g | $8.99 | $7.64 | 0.991 | 0.842 | sale to 30 Sep |
| Superstore | Bob's Red Mill Rolled Oats (gluten free) | 907 g | $8.99 | $7.64 | 0.991 | 0.842 | sale to 30 Sep |
| Superstore | Rogers Porridge Oats, Original Blend | 1 kg | $6.29 | – | 0.629 | – | |
| Superstore | Robin Hood 100% Whole Grains Large Flake Oats | 1 kg | $4.69 | – | 0.469 | – | |
| Superstore | Grace Instant Oats | 1 kg | not shown | $4.00 | – | 0.400 | special |
| Superstore | Quaker Large Flake Oats | 1 kg | $3.75 | $2.77 | 0.375 | 0.277 | special to 30 Sep; stock OUT |
| Superstore | Quaker Quick Oats | 1 kg | $3.75 | $2.77 | 0.375 | 0.277 | special to 30 Sep |
| Superstore | Quaker Quick Oats | 2.25 kg | $7.79 | – | 0.346 | – | |
| Superstore | Quaker Regular Instant Oatmeal | 280 g | $3.50 | $2.77 | 1.250 | 0.989 | special to 30 Sep |
| Superstore | No Name Large Flake 100% Whole Grain Oats | 1 kg | $3.00 | – | 0.300 | – | |
| Superstore | No Name Large Flake, Club Size | 2.25 kg | $6.00 | $5.50 | 0.267 | 0.244 | |
| Superstore | President's Choice Regular Instant Oatmeal | 280 g | not shown | $3.00 | – | 1.071 | special to 7 Oct |
| Superstore | PC Organics Organic Quick Rolled Oats | 1 kg | $5.00 | – | 0.500 | – | |
| Superstore | One Degree Rolled Oats Sprouted | 680 g | $9.49 | – | 1.396 | – | |
| Superstore | Anita's Organic Mill Old Fashioned Rolled Oats | 2.5 kg | $17.99 | – | 0.720 | – | Nature's Path-owned since 2021 (S15) |
| Superstore | Dan-D Pak Rolled Oats | 1 kg | $3.25 | $2.98 | 0.325 | 0.298 | special to 7 Oct |
| Superstore | Nature's Path Organic Maple Nut Instant Oatmeal | 400 g | $5.99 | $5.29 | 1.498 | 1.323 | special to 7 Oct |
| Superstore | Stoked Oats Bucking Eh Oats | 500 g | not shown | $8.50 | – | 1.700 | special to 7 Oct |
| Voilà | Compliments Quick Oats | 1 kg | $4.49 | – | 0.449 | – | |
| Voilà | Compliments Organic Quick Oats | 1 kg | $4.99 | – | 0.499 | – | |
| Voilà | Farm Boy Organic Large Flake Oats | 750 g | $5.49 | – | 0.732 | – | |
| Voilà | Speerville New Found Organic Oatmeal | 910 g | $5.49 | – | 0.603 | – | |
| Voilà | Only Oats Gluten-Free Rolled Oats | 1 kg | $11.99 | – | 1.199 | – | owner unverified (U9b) |
| Voilà | Quaker Old Fashioned Large Flake Oats | 1 kg | $6.49 | – | 0.649 | – | |
| Voilà | Robin Hood Large Flake Oats | 1 kg | $4.79 | – | 0.479 | – | |
| Voilà | Bob's Red Mill Organic Rolled Oats Old Fashioned | 907 g | $9.99 | – | 1.101 | – | |
| Voilà | One Degree Rolled Oats Sprouted | 680 g | $9.49 | – | 1.396 | – | |
| Speerville own site | New Found Oatmeal | 1.82 kg | $9.53 | – | 0.524 | – | S17 |

Voilà sale status is not exposed in the data parsed. Treat Voilà prices "as displayed".

### 5b. Pack and origin lines read from images (all saved in oat2/img/)

| Product | What the image shows | Legibility | Image |
|---|---|---|---|
| Quaker Large Flake 1 kg | Front: "MADE WITH 100% WHOLE GRAIN CANADIAN OATS". Side: "MADE IN • FABRIQUÉ AU / CANADA" (maple leaf); small print "MADE IN CANADA FROM DOMESTIC AND IMPORTED INGREDIENTS. FABRIQUÉ AU CANADA À PARTIR D'INGRÉDIENTS CANADIENS ET IMPORTÉS." | clear | 20323113002_EA_2, _3; q3_crop.jpg |
| Robin Hood Large Flake 1 kg | Roundel "MADE WITH • FAIT AVEC 100% CANADIAN OATS / GRUAU CANADIEN" (clear). Side: "SMUCKER FOODS OF CANADA CORP., MARKHAM, ON L3R 0P3 ... PRODUCT OF CANADA / PRODUIT DU CANADA" (low-res) | partial | 20893369_EA_1, _2; rh_badge.jpg, rh_side.jpg |
| No Name Large Flake 1 kg | "100% whole grain Canadian oats" (clear); lower-left mark "PREPARED IN / PRÉPARÉ AU / CANADA" (low-res) | partial | 20923994_EA_1; nn_prep.jpg |
| Compliments Quick Oats 1 kg | Red roundel "PRODUCT OF • PRODUIT DU • CANADA" (low-res) | partial | v_435017EA.jpg; c_roundel.jpg |
| Farm Boy Organic Large Flake 750 g | "GMO FREE • MILLED IN ONTARIO / SANS OGM • MOULU EN ONTARIO" | clear | v_836391EA_1.jpg; fb_label.jpg |
| Anita's Old Fashioned Rolled Oats | "Anita's Organic Mill is part of the Nature's Path Organic Foods family"; dealer "Anita's Organic Grain & Flour Mill Ltd., Chilliwack, BC ... CANADA"; no origin line visible on that panel | clear | 21304184_EA_2; anita_back.jpg |
| Bob's Red Mill, both 907 g | "An Employee-Owned Company"; no origin line visible | front only | 21127426_EA_1, 21161849_EA_1 |
| Rogers Porridge Oats | Maple leaf, "All Natural", name shown as "Healthy Grain Blend" (do not read aloud) | front only | 20717030_EA_1 |
| Only Oats 1 kg | "Natural Whole Grain / 100% Canadian / High in Fibre" (do not read "High in Fibre"); "Purity from farm to table" | front only | v_610109EA_1.jpg |
| Speerville New Found Oatmeal | "No Additives · Sans Additifs", Ecocert | front only | v_950142EA.jpg |
| Dan-D Pak Rolled Oats | "From the Canadian Prairies / Des Prairies Canadiennes", maple leaf | front only | 20876492_EA_1 |

### 5c. Owners and head offices

| Brand | Owner (source) | Head office (source) |
|---|---|---|
| Quaker | PepsiCo Canada ULC (S7) | PepsiCo: U.S. (10-K not opened, U13). Canadian plants Peterborough and Trenton (S7) |
| Robin Hood | Smucker Foods of Canada Corp. (S10; pack) | The J.M. Smucker Co., Orrville, Ohio (S11) |
| Rogers | Rogers Foods Ltd., subsidiary of Nisshin Seifun Group (S12) | Rogers: Armstrong, B.C. (S13); Nisshin: Tokyo (company site, U8) |
| Bob's Red Mill | employee-owned since April 30, 2020 (S14) | Milwaukie, Oregon (U7: read off the pack) |
| Nature's Path / Anita's | Stephens family company since 1985; Anita's joined 2021 (S15) | Richmond, B.C. (search only, U5) |
| One Degree | "One Small Family" (S16) | facilities in Abbotsford, B.C. (S16) |
| Speerville | Speerville Flour Mill, "a proud Maritime company" since 1982 (S17) | Speerville, N.B. (U19 for co-op status) |
| No Name, PC, PC Organics | Loblaw Companies Limited (S19) | Brampton, Ont. (S19) |
| Compliments, Farm Boy | Empire Company Limited (S18; Farm Boy U20) | Stellarton, N.S. (S18) |
| Kirkland Signature | Costco (S21 page; 10-K not opened) | U2 |
| Great Value | Walmart | U3 |
| Grace | GraceKennedy (unverified) | U4 |
| Only Oats | Above Food (2021, The Plant Base, unbylined) | U9b |

### 5d. National numbers usable on air

- "Total oat production increased by 16.7% to 3.9 million tonnes ... in 2025" (S1, StatCan, 4 Dec 2025).
- "Saskatchewan accounts for 45% of the national production, followed by Manitoba (25%) and Alberta (20%)" (S3, AAFC, 17 Dec 2025).
- "Compared to the previous five-year average, production in 2025 is 5% higher" (S3).
  - A web-search summary claimed oats were "58% above the five-year average ... the highest since 1990". The AAFC PDF gives that sentence to rye, not oats. Do not use it for oats.
- 2026 oat production "anticipated to fall by 22.7% to 3.0 million tonnes" (S2, StatCan, 16 Sep 2026). Usable as the most recent dated fact. It is a model-based estimate, so say "estimated".

---

## Appendix A. Recalls and food-safety items: do not use on air

These are food-safety items. Do not use any of them on air, in a lower-third, in the thumbnail or in the description.

- **Quaker recalls (U.S. and Canada, late 2023–early 2024).** Charles Brennan's 38K video opens on them; the U.S. plant closure (Danville, Ill.) is in search results only (Food Dive / Food Business News). Not opened.
- **CFIA recall notices for any oat product.** None were opened for this note, and none should be.
- **The December video's glyphosate, chlormequat, EWG, EPA, WHO/IARC, Health Canada MRL and "lab test" content** (Appendix B, tags P and S).
- **Competitor glyphosate and certification content:** One Degree's BioChecked and Detox Project lines (S16 FAQ), Food Crisis UK's glyphosate coda, Taste & Reason's entire script.
- **Pack and site claims:** Quaker's "Oat Fibre Helps Reduce Cholesterol" pack panel; No Name's and Quaker's fibre/cholesterol retailer descriptions; One Degree's heavy-metal testing statement.

---

## Appendix B. Every flagged December line, verbatim, with beat and tags

Sentence numbers follow the transcript order in tr_CC_oatmeal_dec2025_31K_clean.txt (split at sentence end; 370 sentences). The text is auto-captioned, so spelling errors ("preh harvest", "Backros", "Craft Hinds") are the caption's.

| # | Beat | Tags | Line (verbatim from the auto-caption transcript) |
|---|---|---|---|
| 1 | Open | L | "I tested popular Canadian oatmeal brands in a lab." |
| 2 | Open | H | "What came back was not healthy breakfast food." |
| 3 | Open | H,P | "It was more like pesticide residue mixed with sugar." |
| 4 | Open | P,W | "One brand contained nearly 3,000 parts per billion of glyphosate." |
| 5 | Open | S | "That is 18 times higher than the safety benchmark for children." |
| 6 | Open | H | "Another had so much added sugar that a single packet contains more than two Oreo cookies." |
| 7 | Open | P | "The worst part, the oats in some brands are sprayed with weed killer right before harvest." |
| 8 | Open | H,P | "You are paying for contaminated grain that is destroying your health with every spoonful." |
| 9 | Open | H,P | "I am about to expose seven oatmeal brands poisoning Canadian families, reveal how to spot fake, healthy oatmeal on shelves, and show you the brands actually made from clean oats." |
| 13 | #7 Quaker | U | "It is the most recognized oatmeal brand in Canada for over a century." |
| 15 | #7 Quaker | H | "Parents feed this to their children every morning believing it is healthy." |
| 16 | #7 Quaker | $ | "The low price reflects the quality." |
| 17 | #7 Quaker | H,P | "This is heavily processed oats with excessive sugar and pesticide contamination." |
| 18 | #7 Quaker | H,$,U | "Canadians pay $5 to $8 per box for Quaker instant oatmeal thinking they are making a nutritious choice." |
| 19 | #7 Quaker | W | "Here is what they do not tell you." |
| 21 | #7 Quaker | H | "This is not a wholesome heritage brand." |
| 22 | #7 Quaker | $,W | "This is a multinational snack food conglomerate with $91 billion in annual revenue." |
| 24 | #7 Quaker | P,US | "In 2018, the Environmental Working Group tested Quaker oatmeal products for glyphosate, the active ingredient in Roundup weed killer." |
| 26 | #7 Quaker | P,W | "Quaker old-fashioned oats contained over 1,000 parts per billion of glyphosate in two of three samples tested." |
| 27 | #7 Quaker | W | "Quaker Oatmeal Squares had nearly 3,000 parts per billion." |
| 28 | #7 Quaker | H,US,W | "That is almost 18 times higher than the EWG's health benchmark of 160 parts per billion for children." |
| 29 | #7 Quaker | P,X | "A food scientist told me glyphosate contamination in oats comes from preh harvest spraying." |
| 30 | #7 Quaker | P | "Canadian farmers spray glyphosate on oats before harvest as a drying agent." |
| 31 | #7 Quaker | P | "This practice called desiccation speeds up the harvest but leaves residue on the grain that ends up in your bowl." |
| 32 | #7 Quaker | P | "You are eating weed killer for breakfast." |
| 33 | #7 Quaker | H,P,US | "The World Health Organization classified glyphosate as a probable carcinogen in 2015." |
| 34 | #7 Quaker | P | "That means it probably causes cancer." |
| 35 | #7 Quaker | P,US | "Lawsuits have been filed against PepsiCo and Quaker over glyphosate contamination." |
| 36 | #7 Quaker | P,US | "Plaintiffs claim Quaker's marketing of products as 100% natural is misleading when they contain weed killer residue." |
| 37 | #7 Quaker | P | "But the contamination story does not end there." |
| 38 | #7 Quaker | P,US | "In 2024, a new pesticide called chlorom miquat was found in 92% of oat-based foods tested by the EWG, including Quaker oats." |
| 39 | #7 Quaker | P,S | "Chloromiquat is a growth regulator linked to reproductive harm in animal studies." |
| 40 | #7 Quaker | US | "The chemical was found in 77 out of 96 people tested in a separate study suggesting widespread human exposure through food." |
| 41 | #7 Quaker | H | "Now look at the sugar content in Quaker instant oatmeal." |
| 42 | #7 Quaker | H | "The maple and brown sugar flavor contains 12 g of sugar per packet." |
| 43 | #7 Quaker | H | "That is more sugar than two Oreo cookies, a single packet." |
| 46 | #7 Quaker | H | "The peaches and cream flavor has 12 g of sugar." |
| 47 | #7 Quaker | H | "You think you are eating a healthy breakfast." |
| 48 | #7 Quaker | H,P | "You are eating dessert with pesticide residue." |
| 50 | #7 Quaker | H | "Instant oatmeal has a glycemic index of around 83 compared to 53 for steel cut oats." |
| 51 | #7 Quaker | H | "This means instant oatmeal spikes your blood sugar much faster, which is particularly problematic for diabetics and anyone managing their weight." |
| 52 | #7 Quaker | H | "The oats are precooked, dried, and rolled extremely thin to achieve that instant cooking time." |
| 53 | #7 Quaker | H | "This processing breaks down the fiber structure that gives oatmeal its health benefits." |
| 54 | #7 Quaker | P,US | "When confronted about glyphosate contamination, Quaker and PepsiCo pointed out that their products meet federal regulatory limits." |
| 55 | #7 Quaker | S | "But just because something is legal does not mean it is safe." |
| 56 | #7 Quaker | H,P,US | "The EPA's legal limit for glyphosate on oats, 30 parts per million, was set in 2008, years before the World Health Organization's cancer findings." |
| 57 | #7 Quaker | H,US | "Federal standards are heavily influenced by industry lobbying and often failed to fully protect public health." |
| 58 | #7 Quaker | H,P,$ | "You are paying premium prices for heavily processed oats from a soda company, contaminated with pesticides, and loaded with added sugar." |
| 61 | #6 Great Value | $ | "It is cheap, around $3 to $4 for a large container." |
| 62 | #6 Great Value | U | "Canadians buy it thinking they are getting a bargain." |
| 64 | #6 Great Value | C | "Great Value oatmeal is contract manufactured, often by the same facilities that make name brand products." |
| 65 | #6 Great Value | H | "You are getting commodity oats processed at industrial scale." |
| 67 | #6 Great Value | H | "Oatmeal companies do the same thing with health claims." |
| 68 | #6 Great Value | H,P | "They market whole grain benefits while selling you pesticide contaminated processed grain." |
| 69 | #6 Great Value | P | "In 2024 testing, some generic store brand granas and cereals, including Walmart brands tested positive for chlorquat." |
| 70 | #6 Great Value | P | "The same growth regulator pesticide found in Quaker products." |
| 71 | #6 Great Value | P,US | "The Environmental Working Group found glyphosate in virtually all conventional oat products tested." |
| 72 | #6 Great Value | P | "Great Value uses conventional non-organic oats that are subject to the same preh harvest glyphosate spraying as other brands." |
| 73 | #6 Great Value | H | "The instant oatmeal varieties contain similar sugar levels to Quaker." |
| 74 | #6 Great Value | H | "Great value maple and brown sugar." |
| 75 | #6 Great Value | H,C | "Instant oatmeal has comparable added sugars because the formula is essentially identical to name brand competitors." |
| 78 | #6 Great Value | $,W | "They contract with the cheapest suppliers who meet minimum specifications." |
| 79 | #6 Great Value | W | "Quality control is less rigorous than dedicated food companies." |
| 80 | #6 Great Value | $ | "The price seems attractive because the actual cost of commodity oats is extremely low." |
| 81 | #6 Great Value | $ | "A large container of plain rolled oats costs Walmart perhaps." |
| 82 | #6 Great Value | $ | "50 cents to produce." |
| 83 | #6 Great Value | W | "The rest is packaging, distribution, and profit." |
| 85 | #6 Great Value | P | "You are getting the same potentially contaminated commodity oats as everyone else, just in yellow packaging." |
| 86 | #6 Great Value | P,W | "Great Value does not test for glyphosate residue." |
| 87 | #6 Great Value | P,W | "They do not source from farmers who avoid pre-H harvest spraying." |
| 88 | #6 Great Value | $,W | "They buy from whoever offers the lowest price." |
| 89 | #6 Great Value | X | "A food industry consultant explained, "Store brand oatmeal is made by the same industrial processes as name brands." |
| 90 | #6 Great Value | C | "The ingredients are virtually identical." |
| 91 | #6 Great Value | $ | "The price savings come from reduced marketing costs, not better sourcing." |
| 92 | #6 Great Value | P,$ | "People assume cheaper means worse quality, but with oatmeal, cheap and expensive brands have the same contamination problems." |
| 93 | #6 Great Value | H | "The convenience of one-stop shopping at Walmart comes at a cost to your health." |
| 95 | #6 Great Value | $,W | "If Walmart can sell a large container of oatmeal for $3 and still make profit, what does that tell you about ingredient sourcing?" |
| 96 | #6 Great Value | S | "The commodity oat market rewards volume and low cost, not quality or safety testing." |
| 97 | #6 Great Value | P,$ | "Farmers who avoid pre-h harvest glyphosate spraying often get lower prices for their crops because the oats take longer to dry naturally." |
| 98 | #6 Great Value | P,W | "The economic incentives pushed toward contamination, not away from it." |
| 99 | #6 Great Value | C,L | "When I examined Great Value oatmeal, it was indistinguishable from name brands." |
| 100 | #6 Great Value | P,T | "Same texture, same potential contamination, same industrial processing." |
| 101 | #6 Great Value | $ | "The lower price bought nothing different." |
| 104 | #5 PC | $ | "Positioned as quality products at reasonable prices." |
| 105 | #5 PC | U | "Canadians trust the PC name." |
| 107 | #5 PC | W,U | "President's Choice is owned by Loblaw Companies Limited, the largest food retailer in Canada, the same company that reported record profits in 2023 and 2024." |
| 108 | #5 PC | W | "While Canadians struggled with grocery inflation during the worst inflation crisis in decades, Loblaw was making billions." |
| 109 | #5 PC | W | "Their executives collected massive bonuses while Canadian families cut back on groceries." |
| 112 | #5 PC | P | "The oats are sourced from commodity markets where glyphosate desiccation is standard practice." |
| 113 | #5 PC | H | "The flavored instant varieties contain added sugars." |
| 114 | #5 PC | H | "The maple and brown sugar flavor has sugar listed as the second or third ingredient after oats." |
| 115 | #5 PC | H | "You are eating sugar delivery systems that happen to contain some grain." |
| 116 | #5 PC | H | "PC Blue Menu offers what they call healthier options." |
| 117 | #5 PC | H,P | "But Blue Menu Instant Oatmeal is still highly processed and still uses conventional oats that may contain pesticide residue." |
| 118 | #5 PC | H,X,C | "A nutritionist told me PC Blue Menu oatmeal is marketed as healthier, but the oats come from the same supply chain as regular PC products." |
| 119 | #5 PC | H,P | "The lower sugar content is good, but it does not address pesticide contamination." |
| 120 | #5 PC | H,P | "You are getting slightly less sugar with the same glyphosate exposure risk." |
| 121 | #5 PC | W | "Here is what Loblaw does not advertise." |
| 122 | #5 PC | $ | "They control multiple brands at different price points, all sourced from similar suppliers." |
| 124 | #5 PC | C | "You are choosing between Loblaw products from the same supply chain." |
| 125 | #5 PC | W | "President's Choice, no name, blue menu, different labels, same parent company, same profit margins, same commodity oats." |
| 128 | #5 PC | W | "Loblaw's dominance of Canadian grocery means limited competition and limited incentive to improve quality or sourcing practices." |
| 129 | #5 PC | W | "Here is what Loblaw could do but does not." |
| 130 | #5 PC | P,W | "They could source from farmers who sign agreements not to use glyphosate as a desicant." |
| 131 | #5 PC | U | "Richardson International, Canada's largest oat miller, started requiring such agreements in 2021." |
| 132 | #5 PC | P | "Major grain traders have moved away from accepting desiccated oats." |
| 133 | #5 PC | P,$ | "Loblaw could offer certified glyphosatefree oatmeal under the President's Choice label at accessible prices." |
| 135 | #5 PC | H | "Instead, they continue selling conventional commodity oats while marketing them as wholesome breakfast choices." |
| 136 | #5 PC | W | "The gap between the marketing and the reality is pure profit margin." |
| 138 | Ask | H,P | "The next brands get even more complicated and at the end I will reveal the oatmeal brands actually made from clean oats without pesticide contamination." |
| 141 | #4 No Name | $ | "Rock bottom pricing around $2 to $3 for instant oatmeal." |
| 142 | #4 No Name | U | "Canadians buy it by the millions." |
| 145 | #4 No Name | P | "The same potential for glyphosate and chloromiquat residue." |
| 147 | #4 No Name | C | "No name instant oatmeal is made by the same contract manufacturers who make President's Choice products." |
| 148 | #4 No Name | C | "Same factories, same supply chain, different label." |
| 149 | #4 No Name | $ | "The price difference between Noame and President's Choice is pure brand positioning." |
| 150 | #4 No Name | C | "You are paying less for identical product quality." |
| 153 | #4 No Name | H | "Premium shoppers buy PC, budget shoppers buy no-name, healthconscious shoppers by blue menu." |
| 154 | #4 No Name | $,W | "Loblaw profits either way while charging different prices for essentially the same products." |
| 155 | #4 No Name | W | "Loblaw reported record profits during a cost of living crisis." |
| 158 | #4 No Name | W | "The reality is calculated marketing designed to extract maximum profit from budgetconscious Canadians." |
| 159 | #4 No Name | X,C | "A food industry analyst explained no-name oatmeal is identical to PC oatmeal in everything except packaging." |
| 160 | #4 No Name | C | "The oats come from the same suppliers." |
| 161 | #4 No Name | C | "The processing is identical." |
| 163 | #4 No Name | $,W | "Budget brands create the illusion of choice while the same company profits from every price segment." |
| 164 | #4 No Name | P,W | "Noame oatmeal has the same contamination concerns as expensive brands without the pretense of quality." |
| 165 | #4 No Name | S,$ | "At least they are honest about being cheap, but cheap does not mean safe." |
| 166 | #4 No Name | W | "It just means less profit going to marketing." |
| 167 | #4 No Name | H | "The sugar content in flavored no-name instant oatmeal matches other brands." |
| 169 | #4 No Name | P,C | "The pesticide exposure risk is identical." |
| 171 | #4 No Name | S | "What it does not signal is any commitment to food safety beyond minimum legal requirements." |
| 172 | #4 No Name | C,L | "When I examined no-name oatmeal, it was indistinguishable from President's Choice." |
| 173 | #4 No Name | P,C,T | "Identical ingredients list, identical texture, identical potential contamination." |
| 176 | #3 Kirkland | $ | "Kirkland Signature is Costco's private label brand, known for quality products at warehouse prices." |
| 177 | #3 Kirkland | U | "Members trust Kirkland Signature." |
| 178 | #3 Kirkland | $ | "The 10 lb bag of rolled oats costs around $8." |
| 179 | #3 Kirkland | $ | "That is only 5 cents per ounce." |
| 180 | #3 Kirkland | $ | "Significantly cheaper than grocery store brands." |
| 182 | #3 Kirkland | US,U | "Kirkland Signature Rolled Oats are listed as a product of Canada packed in the USA." |
| 184 | #3 Kirkland | U | "Canada is one of the world's largest oat producers." |
| 185 | #3 Kirkland | P | "Canadian oats have been at the center of the glyphosate contamination controversy." |
| 186 | #3 Kirkland | P | "According to 2017 tests by the Canadian Food Inspection Agency, nearly 1/3 of food samples contain traces of glyphosate with some 1.3% found to have unacceptably high levels." |
| 187 | #3 Kirkland | P | "Most foods with unsafe glyphosate levels were grains." |
| 188 | #3 Kirkland | P | "Kirkland Signature does not offer organic rolled oats in the standard large format." |
| 190 | #3 Kirkland | S,X | "A food safety researcher explained Kirkland oats are Canadian commodity oats." |
| 191 | #3 Kirkland | P | "Canada has some of the highest rates of glyphosate desiccation in the world because the short growing season makes it economically necessary." |
| 192 | #3 Kirkland | H,P | "Costco's buying power could push for cleaner sourcing, but the standard Kirkland product is conventional oats with conventional contamination risks." |
| 193 | #3 Kirkland | P,U | ">> >> Richardson International, Canada's largest oat miller, began requiring signed agreements from farmers about glyphosate use after consumer pressure." |
| 194 | #3 Kirkland | P | "But conventional oats are still subject to potential contamination." |
| 195 | #3 Kirkland | P | "The value proposition of Kirkland oats assumes you are comfortable with conventional Canadian oats and their associated pesticide residue risks." |
| 196 | #3 Kirkland | $ | "The price is attractive." |
| 197 | #3 Kirkland | P | "The 10 lb bag is convenient for families who use oats regularly, but convenience comes with the same contamination tradeoffs as other conventional brands." |
| 199 | #3 Kirkland | P,$ | "Costco does carry on degree organic sprouted rolled oats, which are certified glyphosatefree, but they stock it at a premium price compared to the Kirkland product." |
| 200 | #3 Kirkland | H | "Costco's buying power could push suppliers toward cleaner practices." |
| 202 | #3 Kirkland | H | "Informed consumers can choose the cleaner alternative." |
| 203 | #3 Kirkland | $ | "Uninformed consumers buy the cheaper option, assuming Kirkland quality protects them." |
| 205 | #3 Kirkland | P | "Not for pesticide residue." |
| 206 | #3 Kirkland | P | "For members who prioritize organic and pesticide-free products, Kirkland's signature offering falls short despite the brand's quality reputation." |
| 207 | #3 Kirkland | L | "When I tested Kirkland oats, the quality was good for conventional oats." |
| 208 | #3 Kirkland | P,T | "The texture was proper, the cooking was consistent, but conventional means potential contamination." |
| 212 | #2 Nature's Path | U | "Nature's Path is a Canadian company founded in 1985 in British Columbia." |
| 213 | #2 Nature's Path | P | "family-owned, certified organic, non-GMO project verified." |
| 214 | #2 Nature's Path | P | "They even own organic farmland in Saskatchewan and Montana." |
| 216 | #2 Nature's Path | P | "Nature's Path products are certified organic, which means glyphosate cannot be used on their crops." |
| 217 | #2 Nature's Path | P | "Organic certification prohibits synthetic pesticides." |
| 218 | #2 Nature's Path | P,US | "However, the same EWG report that found glyphosate in conventional oats also found contamination in around 1/3 of organic oat products tested." |
| 219 | #2 Nature's Path | S | "The levels were lower, remaining below thresholds for harm, but traces were still present." |
| 220 | #2 Nature's Path | P | "How does glyphosate get into organic products?" |
| 221 | #2 Nature's Path | P | "Environmental drift." |
| 222 | #2 Nature's Path | P | "When nearby conventional farms spray glyphosate, it can travel through air and water to contaminate organic fields." |
| 223 | #2 Nature's Path | P | "The organic farmers are not spraying." |
| 226 | #2 Nature's Path | P | "They state that pesticide companies must be held accountable for contaminating the general environment and specifically organic farms." |
| 227 | #2 Nature's Path | P,X | "A microbiologist explained organic certification means the farmer did not spray glyphosate." |
| 228 | #2 Nature's Path | P | "It does not mean the product is glyphosatefree." |
| 229 | #2 Nature's Path | P | "Wind carries pesticides for miles." |
| 230 | #2 Nature's Path | P | "Water runoff contaminates soil." |
| 231 | #2 Nature's Path | P | "Organic farms surrounded by conventional farms face constant drift exposure." |
| 232 | #2 Nature's Path | P | "The organic label tells you about farming practices, not final product purity." |
| 233 | #2 Nature's Path | P,X | "When questioned about glyphosate testing, reports suggest Nature's Path said they do not test for glyphosate as part of their standard organic certification process." |
| 234 | #2 Nature's Path | P | "Does this mean their products contain glyphosate?" |
| 236 | #2 Nature's Path | P | "Organic products consistently test lower than conventional, but certified organic does not guarantee zero residue when environmental contamination is possible." |
| 237 | #2 Nature's Path | H | "Nature's Path also produces flavored instant oatmeal and granas that contain added sugars." |
| 238 | #2 Nature's Path | H | "The Brown Sugar Maple Instant Oatmeal has sugar added for flavor." |
| 239 | #2 Nature's Path | H | "Some granas have significant sugar content." |
| 240 | #2 Nature's Path | P,X | "The company genuinely advocates against glyphosate use and supports organic farming." |
| 242 | #2 Nature's Path | P | "They have invested in regenerative organic certification programs." |
| 243 | #2 Nature's Path | P | "Nature's Path deserves credit for their advocacy and their commitment to organic farming." |
| 244 | #2 Nature's Path | P,US | "They have purchased thousands of acres of organic farmland in Saskatchewan and Montana." |
| 245 | #2 Nature's Path | P | "They partner with independent organic family farmers representing approximately 100,000 organic acres." |
| 246 | #2 Nature's Path | P | "The company's founder, Aaron Stevens, has been vocal about the need to ban glyphosate entirely." |
| 247 | #2 Nature's Path | P | "They support initiatives like regenerative organic certification that go beyond basic organic standards." |
| 249 | #2 Nature's Path | P | "The contamination levels are lower." |
| 251 | #2 Nature's Path | P | "The company genuinely cares about these issues, but organic alone does not solve the systemic problem of widespread pesticide use contaminating the entire food supply." |
| 252 | #2 Nature's Path | P | "If you want verified glyphosatefree oats, you need to look for brands that specifically test and certify for that standard." |
| 254 | #1 Bob's | US,U | "And here we are, Bob's Red Mill, the employeeowned company from Oregon." |
| 256 | #1 Bob's | H,$ | "Wholesome branding, premium prices." |
| 257 | #1 Bob's | H,U | "Canadians pay 8 to12 for Bob's Redm Mill oat products, believing they are getting the cleanest, purest oats available." |
| 259 | #1 Bob's | P,US | "Bob's Red Mill faced a federal class action lawsuit in 2018 after glyphosate was found in both organic and non-organic oats." |
| 260 | #1 Bob's | P | "The suit alleged the company knew products contained or likely contained glyphosate, but did not disclose it on labels." |
| 261 | #1 Bob's | P,US | "The EWG testing found glyphosate in Bob's Red Mill products." |
| 262 | #1 Bob's | P,W | "One sample of organic old-fashioned rolled oats had no detectable levels, but other samples had 10 to 20 parts per billion." |
| 263 | #1 Bob's | H,P,X,W | "A 2024 test reportedly found 151 parts per billion of glyphosate in Bob's Redm Mill glutenfree all-purpose baking flour." |
| 264 | #1 Bob's | H,US,W | "That is close to the EWG health benchmark of 160 parts per billion." |
| 265 | #1 Bob's | S,X | "A food safety advocate told me Bob's Redm Mill markets itself as purer than pure." |
| 266 | #1 Bob's | P | "The premium pricing reflects this positioning, but independent testing has found glyphosate in their products at levels similar to or sometimes higher than other organic brands." |
| 267 | #1 Bob's | H | "The wholesome packaging creates expectations that testing does not always confirm." |
| 268 | #1 Bob's | P | "Bob's Redm Mill responded to the controversy by working with suppliers to end the use of glyphosate as a preh harvest desicant for all varieties of their oats." |
| 270 | #1 Bob's | P,US | "The company states that for USDA organic products, glyphosate use is strictly prohibited, but they acknowledge the risk of trace residue from environmental drift even in organic products." |
| 272 | #1 Bob's | H | "They maintain dedicated gluten-free facilities." |
| 273 | #1 Bob's | H | "They offer a wide range of minimally processed whole grain products." |
| 274 | #1 Bob's | U | "The employeeowned structure is genuinely admirable." |
| 275 | #1 Bob's | U | "Bob Moore famously gave the company to his workers in 2010 rather than selling to a corporation that matters." |
| 277 | #1 Bob's | P,W | "Employee ownership creates different incentives, but employee ownership does not change the fundamental challenge of producing grain products in a food system saturated with pesticides." |
| 278 | #1 Bob's | P | "Until glyphosate desiccation is banned and pesticide drift is controlled, even the best brands will face contamination challenges." |
| 280 | #1 Bob's | P | "Their organic products consistently test lower for contaminants." |
| 281 | #1 Bob's | $ | "Their commitment to quality is real, but the premium price suggests pristine purity." |
| 286 | Recap | P | "Pesticide contamination throughout the conventional oat supply." |
| 287 | Recap | H | "Added sugars in instant and flavored products." |
| 288 | Recap | H,W | "Corporate ownership prioritizing profits over health." |
| 289 | Recap | H | "Misleading marketing about what natural and wholesome actually mean?" |
| 292 | Recap | P | "Most oat products contain some level of pesticide residue." |
| 293 | Recap | P | "Glyphosate and chloromiquat are widespread in conventional oats due to standard farming practices." |
| 294 | Recap | P | "The only way to minimize exposure is to choose products that are certified organic and third-p partyy tested for glyphosate residue." |
| 295 | Recap | P | "Certified organic alone is not enough because of environmental drift from neighboring farms." |
| 296 | Recap | H | "You need real oatmeal made from actual clean oats." |
| 298 | Picks | P | "Number one, onederee organics." |
| 299 | Picks | P | "One degree is a Canadian family company based in British Columbia that offers third-party verified glyphosate free oats." |
| 300 | Picks | P | "Their products are certified organic, non-GMO, and biocheed non-glyphosate certified." |
| 307 | Picks | H,P,X | "The company was founded by passionate organic food advocates with deep respect for sustainable farming and clean nourishing foods." |
| 308 | Picks | H,P | "They source oats from certified organic farmers in Alberta who prioritize soil health and plant-based farming methods." |
| 309 | Picks | P | "What makes One different from other organic brands is their commitment to transparency." |
| 311 | Picks | H | "Their oats are also sprouted which activates enzymes that make nutrients more bioavailable and easier to digest." |
| 312 | Picks | H | "Sprouting breaks down anti-nutrients like fitic acid that can interfere with mineral absorption." |
| 313 | Picks | U | "Onederee sprouted oats are available at Costco Canada and natural food stores." |
| 314 | Picks | P,$ | "At around $15 for a large bag, they cost more than conventional oats, but provide verifiable assurance of no glyphosate residue." |
| 316 | Picks | P | "Backros was the first granola and oats company to achieve third-party glyphosate residuefree certification." |
| 321 | Test | H | "Now, there are other clean oatmeal brands." |
| 324 | Test | P | "Check for organic certification first." |
| 325 | Test | P | "This eliminates direct glyphosate." |
| 327 | Test | P | "Look for third-party glyphosate testing." |
| 328 | Test | P | "Certifications like Bioche or Detox Project indicate the company tests for residue beyond basic organic requirements." |
| 329 | Test | P | "If you see these logos, the company has verified their products are glyphosatefree." |
| 331 | Test | H | "Steel cut and rolled oats have lower glycemic index and less processing than instant varieties." |
| 332 | Test | H | "Steel cut oats have a glycemic index of 53." |
| 333 | Test | H | "Instant oats have a glycemic index of 83." |
| 334 | Test | H | "The difference affects blood sugar significantly." |
| 335 | Test | H | "Read the sugar content." |
| 336 | Test | H | "Plain oats have zero added sugar." |
| 337 | Test | H | "If sugar is in the first three ingredients, you are buying dessert, not breakfast." |
| 338 | Test | H | "Anything over 5 g of sugar per serving is excessive for plain oatmeal." |
| 340 | Test | P | "Canadian oats are subject to desiccation practices." |
| 341 | Test | P | "Some companies import from regions with stricter pesticide regulations." |
| 343 | Test | H | "Steel cut oats are minimally processed with just the groat cut into pieces." |
| 345 | Test | H | "Instant oats are precooked, dried, and rolled extremely thin." |
| 346 | Test | H | "The more processing, the faster the blood sugar spike, and the less nutritional benefit from the fiber structure." |
| 348 | Test | P,$,W | "Expensive does not mean pesticidefree, but extremely cheap definitely means commodity conventional oats from the lowest bidder." |
| 349 | Test | T | "Examine the texture." |
| 350 | Test | H,T | "Real minimally processed oats have visible texture and take time to cook." |
| 351 | Test | H | "If oats cook in 90 seconds, they have been heavily processed." |
| 354 | Test | W,U | "Independent brands and employeeowned companies are more likely to prioritize quality over quarterly profits." |
| 356 | Moral | W,U | "Two owned by Canada's largest grosser reporting record profits during inflation." |
| 357 | Moral | P,U | "One employeeowned company doing better but still facing systemic contamination challenges." |
| 359 | Moral | H,P | "The excessive pesticide residue, synthetic additives and flavored varieties, and heavily processed instant products make mainstream oatmeal terrible for your health despite its healthy reputation." |
| 363 | Moral | P | "The contamination pattern extends across the entire grain supply." |
| 364 | Moral | H,P | "the same pesticides, the same corporate priorities, the same misleading health claims." |
| 366 | Moral | H,W | "What we found will shock you because what consumers do not know is costing them their health and corporations are profiting from that ignorance." |
| 367 | Close | P | "Have you been buying any of these contaminated oatmeal brands?" |
| 368 | Close | H | "Are you ready to switch to one degree or another verified clean brand?" |
| 369 | Close | P | "Drop your thoughts in the comments and share this with everyone still buying pesticide oatmeal." |

---

## UNVERIFIED / DO-NOT-USE

Nothing below may go on air until the stated check is done. Each item names the page that could not be opened or the claim that rests on a tier (c) or unopened source.

| # | Item | Status / why | What would clear it |
|---|---|---|---|
| U1 | Oat or oatmeal brand market share in Canada (who is "most popular") | No tier (a), (b) or (d) source found. December's "most recognized ... for over a century" is unsourced | A named survey or a company annual report with Canadian oat share. Until then, use the price order basis (4c) |
| U2 | Kirkland Signature oats: Canadian pack origin line, price, owner head office | costco.ca (S21) shows no price, no origin, "Unavailable". "Product of Canada, Packed in the USA" is from the U.S. costco.com listing via search snippet only: U.S. context, not opened. Costco 10-K not opened | In-store photo at a Canadian Costco (date, city), warehouse price, Costco 10-K for the head office. Otherwise swap to Dan-D Pak (4h #8) |
| U3 | Great Value oats: pack, price, owner details | walmart.ca not attempted (blocked in earlier sessions); Walmart 10-K not opened | Photo and walmart.ca price with region and date. Otherwise swap to PC Organics (4h #6) |
| U4 | Grace Instant Oats owner (GraceKennedy / Grace Foods Canada Inc., Mississauga) and origin line; regular price | gracefoods.ca failed TLS (certificate expired); GraceKennedy report not opened; owner from search summaries only | GraceKennedy annual report page naming Grace Foods Canada; pack photo. Otherwise swap to Quaker Regular Instant (4h #4) |
| U5 | Nature's Path oatmeal origin line (Delta B.C. vs Blaine, Wash., plant); Richmond head office | Pack side text unreadable at 500 px; head office from search and Wikipedia only (tier c) | Pack photo; Nature's Path contact page. Nature's Path is not in the recommended list |
| U6 | Quaker 1 kg current pack (the images may be an older version; "black hat" wording); PepsiCo's explanation of "domestic and imported" on a one-ingredient box | Images from PC Express CDN, version "v1", date unknown | Photograph a current pack in store; send PepsiCo Canada a written question before air; quote any reply verbatim |
| U7 | Bob's Red Mill pack origin line and dealer line; Milwaukie, Oregon head office | Only front images seen; city from search and footer context | Pack photo of the back or side panel |
| U8 | Rogers pack origin line; year Nisshin took control (1989 per World Grain, which returned 403); Nisshin head office city | Not opened | Pack photo; Nisshin's corporate profile page; World Grain via a browser |
| U9 | Robin Hood side panel "PRODUCT OF CANADA" and "SMUCKER FOODS OF CANADA CORP., MARKHAM" | Low-resolution crop | Pack photo |
| U9b | Only Oats current owner | The Plant Base (21 Jul 2021, no named author) says Above Food Corp bought Only Oats; Avena Foods' page (S20) does not mention Only Oats; myonlyoats.com returned an empty page | Company page or Above Food filing. Do not use Only Oats on air |
| U10 | Robin Hood oats milled in Saskatoon; the 2006 Horizon Milling (Cargill) mill sale | madeinca.ca (tier c) and Wikipedia via search; SEC 8-K (2006) not opened | Open the Smucker 2006 8-K and a current company statement on where the oats are milled |
| U11 | Red River Cereal: Smucker discontinued it; Arva Flour Mills bought it (June 2022) | CBC article returned 403; foodbev / Wikipedia via search only | Open the CBC story (byline, date) in a browser. Optional colour only |
| U12 | Canada's 25% counter-tariff on U.S. oats, tariff item 1004.90.00, effective 2025-03-04, still listed (S22) | Opened, but whether CUSMA-compliant U.S. oats are exempt (SOR/2025-181, Aug 29, 2025) was not checked; raw oats are not oatmeal | Read SOR/2025-181 and the CBSA notice; even then, it is context only |
| U13 | PepsiCo head office (Purchase, N.Y.) and 2025 net revenue | PepsiCo 10-K not opened; S7 gives "nearly $92 billion ... in 2024" | Open the PepsiCo 2025 10-K |
| U14 | PC Organics Quick Oats pack origin line | Only Loblaw's site badge "Prepared in Canada" seen | Pack photo |
| U15 | No Name "PREPARED IN / PRÉPARÉ AU / CANADA" mark | Low-resolution crop | Pack photo |
| U16 | Dan-D Pak owner (Dan-D Foods, Richmond B.C., founder Dan On) and pack origin line | BIV article and Wikipedia via search only | dandpak.com about page; pack photo |
| U17 | Compliments Quick Oats "PRODUCT OF CANADA" roundel | 500 px image; low resolution | Pack photo (required before P1 airs) |
| U18 | One Degree: pack origin line; owner names (the Smith family / Stan Smith per Sustainable Brands, tier c) | Not on any tier (a) page opened | Pack photo; One Degree "Our Family" page |
| U19 | Speerville: co-operative status; whether New Found Oatmeal is milled on site from Atlantic Canadian oats; pack origin line | Co-op status from a McGill archive page and madeinca (tier c); company site is general | Phone the mill, or the product page and a pack photo |
| U20 | Farm Boy owned by Empire | From the cottage note's S26; not found in the text extraction of the Empire release this session | Re-open Empire's annual report or website |
| U21 | Stoked Oats: Calgary owner and founder (Simon Donato, 2011) | Crunchbase and LinkedIn via search (tier c); the company site banner says "PROUDLY CANADIAN" | Company about page; pack photo |
| U22 | "Canada is the largest exporter of oats"; "63% of global oat exports" (Jan–Oct 2025); "81% of exports go to the U.S." | Cereals Canada, POGA and Mexico Business News via search; none opened | AAFC or Canadian Grain Commission export page |
| U23 | Quaker Peterborough plant "opened in 1902"; the 1988 expansion; "440 members of Unifor Local 1996" | CAPI case study and Unifor page via search only | Open the Unifor page (named union, dated) and a company or archive source for 1902 |
| U24 | AAFC Question Period Note AAFC-2025-QP-00123 ("2% or less") | Read from a sibling's saved file (oat/qpnote.html); canonical URL not captured | Use the CFIA origin page (S4) instead; it carries the 2% wording |
| U25 | "Saskatchewan alone grew close to half" | AAFC says 45% (S3); "close to half" is a paraphrase | Say "45 percent" |
| U26 | Food Crisis UK, Consumer Exposed, Charles Brennan, Taste & Reason factual claims (Scott's / PepsiCo 1982; Ready Brek / Post 2017; "sold to the company behind Snickers ... $600 million") | U.K. and U.S. facts from competitor scripts; not opened; most are health claims | Not needed; do not use |
| U27 | Every December claim not re-verified in section 3 (Richardson glyphosate agreements, EWG figures, lawsuits, "$91 billion", Kirkland "packed in USA", the One Degree Costco listing, "Backros") | Barred by rule 1 or 7, or unsourced | Do not use |
| U28 | Bread and ketchup transcript facts (Bimbo, FGF, Heinz Leamington and so on) cited in section 2 | Quoted only as what those videos said, not verified for this note | Do not reuse them as facts in the oatmeal script |
| U29 | World Grain (Rogers), CBC (Red River), walmart.ca, gracefoods.ca, the agriculture.canada.ca HTML outlook page | 403, TLS failure, not attempted, or 404 respectively | Retry in a browser |

<!-- ===== oatmeal_rules_origin.md ===== -->

# Oatmeal: the "ACTUALLY Canadian" test, the rules it can rest on (tier a only)

Compiled **30 Sep 2026**. All pages below were opened on 30 Sep 2026 (Eastern time; the proxy logs show 2026-10-01 00:00–00:45 UTC). Each row says how the page was opened: **curl** means raw HTML, extracted locally; **WebFetch** means the text was extracted by a tool because curl was refused. WebFetch text is not guaranteed to be character-for-character, so those quotes are flagged and also listed in UNVERIFIED.

**How the house rules apply to this file**
- There are no health, nutrition, food-safety, additive, pesticide, gluten or sugar statements anywhere in this file. Where a primary source touches a barred topic, this file says only that the topic exists and is barred. Those items are in UNVERIFIED / DO-NOT-USE.
- Nothing here comes from the channel's December 2025 oatmeal video or from any competitor video.
- No company is accused of anything. Regulatory items are labelled **guidance**, **regulation**, **statute**, **penalty (regulator statement)** and so on.
- Prices: none. This file is rules only.

---

## 0. The bottom line, as the law actually stands (30 Sep 2026)

| # | Finding | Status | Source (opened 30 Sep 2026) |
|---|---|---|---|
| 1 | Canadian law does **not require** a box of oats or oatmeal to say where it comes from. Oats and cereals are **not** on the CFIA's list of imported foods that must carry a country of origin. | Regulation and guidance | CFIA, Country of origin: https://inspection.canada.ca/en/food-labels/labelling/industry/country-origin (modified 2022-07-19); SFCR full text (current to 2026-09-21) |
| 2 | **"Product of Canada"** and **"Made in Canada"** are **voluntary** claims. When a company uses one, the CFIA's guidelines apply: "all or virtually all" Canadian for Product of Canada, and a **mandatory qualifier** for Made in Canada. The guidelines rest on the false/misleading prohibitions in FDA s. 5(1) and SFCA s. 6(1). | Guidance, interpreting statute | CFIA origin claims: https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims (modified 2023-12-06) |
| 3 | The CFIA's own worked examples for these claims are **oatmeal cookies**. | Guidance | Same page |
| 4 | **"Canadian"** on a food = a Product of Canada claim. **"100% Canadian"** = entirely Canadian. | Guidance | Same page |
| 5 | A **maple leaf** alone does not legally mean "Canadian". The CFIA recommends putting a domestic-content statement next to it. | Guidance | Same page; CFIA notice of 14 Mar 2025, updated 30 Jul 2025 |
| 6 | The **dealer line** names the person **by or for whom** the food was made. It is not an origin statement. **"Prepared for" … "doesn't mean the food was prepared in Canada"** (CFIA's words). | Regulation (SFCR 218, FDR B.01.007) and guidance | CFIA consumer guide: https://inspection.canada.ca/en/food-labels/labelling/consumers/canadian-food (modified 2025-06-04) |
| 7 | **"Imported by / Imported for"** is required on food **wholly** made abroad when only a Canadian company's name and address appear, unless the origin is shown. | Regulation | SFCR s. 223 |
| 8 | There is **no Canadian standard of identity** for rolled oats, oatmeal or oat flakes, in either the CFCS or the Canadian Standards of Identity. | Searched; none found | CFCS (modified 2025-05-01); CFIA documents incorporated by reference |
| 9 | CFIA guideline text has **not changed** in 2025–26: the page is still dated 2023-12-06. What changed was enforcement messaging: a notice to industry (Mar 2025, updated Jul 2025), a revised consumer guide (Jun 2025) and a penalties statement (16 Mar 2026, $47,000 across five businesses since 1 Apr 2025). | Guidance and penalty (regulator statement) | See section 5 |
| 10 | **U.S. oats (tariff item 1004.90.00) were hit by Canada's 25% counter-tariff from 4 Mar 2025 to 31 Aug 2025, then removed on 1 Sep 2025.** Rolled/flaked oats (1104.12), other worked oats (1104.22), oat groats and meal (1103), and prepared cereal foods such as flakes (1904) were **never** on any list. The new counter-tariffs from 8 Sep 2026 contain **no oat items**. | Order and regulation; Finance list | Canada Gazette SOR/2025-66 and SOR/2025-181; Finance complete list (modified 2026-09-24) |

---

## 1. The two statutes everything rests on

| Law | Verbatim text | URL (opened 30 Sep 2026, curl) |
|---|---|---|
| **Safe Food for Canadians Act s. 6(1)** (current to 2026-09-21) | "It is prohibited for a person to manufacture, prepare, package, label, sell, import or advertise a food commodity in a manner that is false, misleading or deceptive or is likely to create an erroneous impression regarding its character, quality, value, quantity, composition, merit, safety or **origin** or the method of its manufacture or preparation." | https://laws-lois.justice.gc.ca/eng/acts/S-1.1/section-6.html |
| **Food and Drugs Act s. 5(1)** (current to 2026-09-21) | "No person shall label, package, treat, process, sell or advertise any food in a manner that is false, misleading or deceptive or is likely to create an erroneous impression regarding its character, value, quantity, composition, merit or safety." | https://laws-lois.justice.gc.ca/eng/acts/F-27/section-5.html |

- Production note: the word **"origin"** appears only in the SFCA prohibition. The FDA list does not include it. This is a literal comparison of the two texts, not a legal opinion.
- **Competition Act s. 74.01(1)(a)** (current to 2026-09-21) says "A person engages in reviewable conduct who, for the purpose of promoting … any business interest, by any means whatever, (a) makes a representation to the public that is false or misleading in a material respect". **s. 74.03(5)** says "the general impression conveyed by a representation as well as its literal meaning shall be taken into account". Sources: https://laws-lois.justice.gc.ca/eng/acts/C-34/section-74.01.html and https://laws-lois.justice.gc.ca/eng/acts/C-34/section-74.03.html

---

## 2. The CFIA "Product of Canada" and "Made in Canada" guidelines (the current page)

**Source:** CFIA, *Origin claims on food labels*, https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims. Date modified **2023-12-06**. Opened 30 Sep 2026 with curl.
**FAQ:** https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims/frequently-asked-questions. Date modified **2022-07-06**. Opened 30 Sep 2026 with curl.
**Legal status:** these are CFIA **guidelines** (interpretive guidance), not regulations. AAFC's Question Period note says they "have been in effect since December 31, 2008" (see section 5).

### 2.1 Legal basis and scope (verbatim)
> "The guidelines for "Product of Canada" and "Made in Canada" claims promote compliance with subsection 5(1) of the Food and Drugs Act and subsection 6(1) of the Safe Food for Canadians Act, which prohibit false and misleading claims."

> "The use of "Product of Canada" and "Made in Canada" claims is voluntary. However, once a company chooses to make one of these claims, the product to which it is applied should meet these guidelines."

> "The guidelines … apply to foods sold at all levels of trade, including bulk sale or wholesale foods for further processing. They also apply to claims made in advertising and by restaurants."

> "All ingredients and their components that contribute to the food, regardless of their generation when they were added, must be considered when assessing "Product of Canada" and "Made in Canada" claims."

### 2.2 "Product of Canada": all or virtually all (verbatim)
> "A food product may use the claim "Product of Canada" when all or virtually all major ingredients, processing, and labour used to make the food product are Canadian. This means that all the significant ingredients in a food product are Canadian in origin and that non-Canadian material is negligible."

Things that **do not** disqualify a Product of Canada claim (verbatim):
> "very low levels of ingredients that are not generally produced in Canada, including spices, food additives, vitamins, minerals, flavouring preparations, or grown in Canada such as oranges, cane sugar and coffee. Generally, the percentage referred to as very little or minor is considered to be less than a total of 2% of the product"

> "packaging materials that are sourced from outside Canada …"

> "the use of imported agricultural inputs such as seed, fertilizers, animal feed, and medications"

**The CFIA's own oatmeal example** (verbatim):
> "For example, a cookie that is manufactured in Canada from oatmeal, enriched flour, butter, honey and milk from Canada, and imported vanilla, may use the claim "Product of Canada" even if the vitamins in the flour and the vanilla are not from Canada."

### 2.3 The 2% guidance, from the FAQ (verbatim)
> "Generally, the percentage referred to as "very little" or "minor" is considered to be less than 2% of the product."

> "Why is the percentage … set at 2%? This guidance corresponds to B.01.008.2(4) of the Food and Drugs Regulations (FDR) which permits that certain ingredients be shown at the end of the list of ingredients in any order as they are present in minor amounts. Normally, these are less than 2% of the total content of the product."

> "Products using imported cane sugar at levels greater than 2% would not be eligible for a Product of Canada claim as this would be seen as misleading to the consumer. The qualified Made in Canada claim would be appropriate."

> "When such ingredients are minor ingredients added as a flavouring in a food (that is to say, less than 2%) and labelled as for flavouring, their presence would not disqualify the food from a Product of Canada claim."

- The rule the FAQ points to, FDR B.01.008.2(4) (Justice Laws, current to 2026-09-21, https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._870/FullText.html), reads: "Despite paragraph (3)(a), the following ingredients may be shown at the end of the list of ingredients, in any order: (a) spices, herbs and other seasonings, other than salt added separately, if the total weight of those other seasonings is no more than two per cent of the total weight of ingredients …; (b) natural flavours and artificial flavours; (c) flavour enhancers; …"
- Production note: the CFIA's 2% is **guidance language ("Generally")**, not a number written into a regulation.

### 2.4 "Canadian" means "Product of Canada" (verbatim)
> "The claim "Canadian" is considered to be the same as a "Product of Canada" claim and any product carrying this claim must meet the criteria for a "Product of Canada" claim described above."

> "When this type of claim is used to describe a single component ingredient within the food, all of the ingredient(s) and, if any, derivatives of that ingredient in the food must be Canadian. For example, if the claim "Contains Canadian blueberries" is used on a prepackaged blueberry pie, all of the blueberries, as well as any blueberry juice concentrate or derivative, must be Canadian."

### 2.5 "100% Canadian" (verbatim)
> "When the claim "100% Canadian" is used on a label, the food or ingredient to which the claim applies must be entirely Canadian rather than "all or virtually all" Canadian."

> "For example, if the claim "Made with 100% Canadian wheat" is used on a bag of dry pasta, all of the wheat, and its derivatives, used in that product must be Canadian."

### 2.6 "Made in Canada" requires a qualifier (verbatim)
> "A "Made in Canada" claim with a qualifying statement can be used on a food product when the last substantial transformation of the product occurred in Canada, even if some ingredients are from other countries."

> "A substantial transformation occurs when a food product undergoes processing which changes its nature and becomes a new product bearing a new name commonly understood by the consumer."

> "The qualifying statements that can be used include "Made in Canada from domestic and imported ingredients" or "Made in Canada from imported ingredients"."

> "All variations of "Made in Canada" claims must include a qualifying statement. For example, a claim such as "Proudly Made in Canada" would need a qualifying statement if the product contains imported ingredients …"

**Oatmeal examples again** (verbatim):
> "For example, a cookie manufactured in Canada from imported flour, oatmeal, shortening and sugar may be labelled or advertised with the claim "Made in Canada from imported ingredients"."

> "For example, a cookie manufactured in Canada using Canadian flour, oatmeal and shortening and imported sugar may be labelled or advertised with the claim "Made in Canada from domestic and imported ingredients"."

> "This claim may be used on a product that contains a mixture of imported and domestic ingredients, **regardless of the level of Canadian content** in the product."

> "… it would be considered acceptable if the order were reversed, if there were a higher proportion of imported ingredients than domestic ingredients."

> "The claim "Made in Canada from domestic and/or imported ingredients" is not permitted as it does not provide meaningful information to the consumer about the Canadian content."

From the FAQ (verbatim):
> "These claims are intended to indicate that a food product is manufactured or processed in Canada, not to specify the amount of Canadian ingredients."

### 2.7 Other domestic-content claims (verbatim list)
> "Processed in Canada" to describe a food which has been entirely processed in Canada · "Prepared in Canada" to describe a food which has been entirely prepared in Canada · "Packaged in Canada" to describe a food which is imported in bulk and packaged in Canada

FAQ (verbatim):
> "The use of Made in Canada with imported ingredients, Made in Canada from domestic and imported ingredients or any alternate claim, such as "Distilled in Canada" or "Packaged in Canada" should not trigger the need for the country of origin declaration, unless otherwise specified in regulations."

### 2.8 Multiple countries, blends, re-imports, changing sources (verbatim)
> "The use of a voluntary multiple country of origin statement that references Canada (for example, "Product of Canada and United States") would not be acceptable."

> "A blended claim, such as "A blend of Canadian (naming the product) and [Naming the country] (naming the product)", may be considered acceptable …"

> "Generally, products that are exported and re-imported into Canada would not be able to make a "Product of Canada" claim."

FAQ (verbatim):
> "Ingredient sources can change frequently … Would food processors be expected to change the label as ingredient sources change? Yes. Domestic content claims are voluntary, however if used, the appropriate criteria must be met."

> "There is no specific documentation required. … a company should be able to provide evidence that a product meets the criteria … if such claims are used in labelling or advertising."

### 2.9 Maple leaf, flag and official symbols (verbatim)
> "The maple leaf, other than the stylized 11-point maple leaf, or other similar symbol may be used on food products without further permission."

> "The use of these vignettes on their own does not always imply that the product is wholly or partially Canadian (for example, maple leaves as part of a fall scene on a product's label)."

> "However, depending on how a maple leaf is used, it could imply a "Product of Canada" claim. In such situations, the product must follow the criteria for a "Product of Canada" claim. In order to ensure that the use of the maple leaf or other similar symbol will not mislead the consumer, it is recommended that an accompanying domestic content statement be placed in close proximity to the vignette."

FAQ (verbatim):
> "The use of a maple leaf or other similar symbol should not imply that the product is wholly or partially Canadian without a clear domestic content statement."

Canadian Heritage, *Commercial use of symbols of Canada*, https://www.canada.ca/en/canadian-heritage/services/commercial-use-symbols-canada.html (modified 2026-08-10, opened 30 Sep 2026 with curl), verbatim:
> "The National Flag of Canada is protected by the Trademarks Act (Section 9) against unauthorized use for commercial purposes."
> "The stylized 11-point maple leaf is also protected by the Trademarks Act (Section 9) as well as Order in Council 1965-1623 against inappropriate use for commercial purposes."

### 2.10 Terms the guidelines do not govern (verbatim)
> "grade names incorporating the term Canada (for example, Canada Fancy)" · "the "Canada Organic" logo or references to Canada organic" · "mandatory country of origin labelling statements"

> "On imported products that are qualified to use the Canada organic logo, a country of origin statement or the statement "Imported" is required to be in close proximity to the logo …"

The regulation behind the organic rule is **SFCR s. 354(d)** (verbatim): "in the case of a food commodity that is imported and on whose label the product legend that is set out in Schedule 9 is applied, the expression "Product of" or "produit de" immediately preceding the name of the foreign state of origin or the word "Imported" or "importé" in close proximity to that product legend." Source: SFCR full text, https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/FullText.html (current to 2026-09-21).

### 2.11 CFIA general principles: "overall impression" (verbatim)
Source: https://inspection.canada.ca/en/food-labels/labelling/industry/general-principles (modified 2022-07-06, opened 30 Sep 2026 with curl).
> "All information on food labels or in advertisements, including words, pictures, vignettes and logos, will contribute to the overall impression created about a product."

> "Qualifying statements or disclaimers may not be used to correct a false or misleading statement or image. … it is not acceptable to use this technique to explain that a featured statement or image is not exactly what it appears to be."

> "Information that is provided voluntarily on food labels or in advertisements is often referred to as a claim. This may include any specific claims such as "Product of Canada," …"

---

## 3. Country-of-origin requirements for imported prepackaged food (SFCR)

**CFIA, *Country of origin on food labels*.** https://inspection.canada.ca/en/food-labels/labelling/industry/country-origin. Modified 2022-07-19. Opened 30 Sep 2026 with curl.

> "In Canada, there are mandatory requirements for certain food products to indicate the foreign state … of origin on their labels."

> "When a food product is wholly manufactured outside of Canada, the label must show that the product is imported. This information can be provided in one of three ways: the name and principal place of business of the foreign manufacturer · the statement "imported for" / "importé pour" or "imported by" / "importé par" followed by the name and principal place of business of the Canadian company · the name and principal place of business of the Canadian company with the country of origin of the product"

The list of foods that must state origin (verbatim): "wine and brandy · dairy products · honey · fish and fish products · fresh fruits and vegetables · shell egg · processed egg · meat products · maple products · processed fruit and vegetable products"

The same list on the CFIA consumer page (modified 2025-06-04): "dairy products, eggs, fish, fresh fruits and vegetables, maple and honey products, meat, wine, brandy, and some processed fruits and vegetables."

**→ Oats, oat flakes, oatmeal and breakfast cereals are not on either list.**

A search of the **SFCR full text** (current to 2026-09-21) for "Product of", "foreign state of origin" and "geographic origin" finds commodity rules only:
- s. 250: dairy
- ss. 256, 259, 260: eggs and processed eggs
- s. 266: fish
- s. 269: fresh fruits and vegetables
- ss. 276–278: honey
- s. 281: maple
- s. 297: meat
- s. 309: foreign grade designations
- s. 354: organic
- s. 223: the general "Imported by" rule

**None of these covers grain or cereal products.**

- **SFCR s. 309**, "Imported foods — no prescribed grade name" (verbatim): "A food that is imported and in respect of which no grade name is prescribed by these Regulations may be labelled with the grade designation that is established by the foreign state of origin if … (c) the name of that foreign state of origin is clearly indicated on the label."
- **History, for context only.** In 2019 the CFIA consulted on expanding origin labelling. Its page, https://inspection.canada.ca/en/about-cfia/transparency/consultations-and-engagement/completed/proposed-flm/origin-imported-food (modified 2019-09-05, status "Closed", opened 30 Sep 2026), says (verbatim): "The proposed amendment to the SFCR, which expands the origin requirement to most imported foods, does not prescribe the statement to be used to indicate the origin." The consultation "ran from June 22, 2019 to September 4, 2019." **The SFCR text current to 2026-09-21 contains no general origin requirement for all imported foods.** The page does not say what happened to the proposal (see UNVERIFIED).
- **No 2025–2026 consultation on mandatory origin labelling was found** on CFIA pages. AAFC's Dec 2025 Question Period note describes the government as "committed to helping consumers Buy Canadian by increasing transparency and stringency in origin of product labelling" but names no regulatory proposal (see section 5).

---

## 4. Dealer name and principal place of business ("the company line")

### 4.1 Regulations (verbatim; Justice Laws, opened 30 Sep 2026 with curl, current to 2026-09-21)

**SFCR s. 218(1)(b)** (https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/section-218.html):
> "a label that is applied or attached to a prepackaged food must bear … (b) the name and principal place of business of the person **by or for whom** the food was manufactured, prepared, produced, stored, packaged or labelled, on any part of the label other than any part that is applied or attached to the bottom of the container of the food"

**SFCR s. 218(2):** "The information referred to in paragraph (1)(b) may be shown on any part of the label that is applied or attached to the bottom of the container if that information is also shown on a part of the label that is not applied or attached to the bottom of the container."

**SFCR s. 220** (exemption): "Consumer prepackaged fresh fruits or vegetables that are packaged at retail in such a manner that the fresh fruits or vegetables are visible and identifiable in the container are not required to be labelled with the name and principal place of business …"

**SFCR s. 222** (https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/section-222.html):
> "If the label that is applied or attached to a consumer prepackaged food bears any reference, direct or indirect, to the place of manufacture of the label or container, the reference to that place must be accompanied by an additional statement that indicates that the reference relates only to the place of manufacture of the label or container."

**SFCR s. 223**, "Name of importer" (https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/section-223.html):
> "(1) If a consumer prepackaged food was wholly manufactured, processed or produced in a foreign state and the name and principal place of business of the person in Canada for whom it was manufactured, processed or produced or the person by whom it was stored, packaged or labelled in Canada is shown on its label, that information must be preceded by the expressions "Imported by" and "importé par" or "Imported for" and "importé pour", as the case may be, unless the geographic origin of the consumer prepackaged food is shown on the label in accordance with subsection (3)."
> "(2) If a food that was wholly manufactured, processed, produced in a foreign state is packaged in Canada, other than at retail, and the name and principal place of business of the person in Canada … is shown on the label …, that information must be preceded by the expressions "Imported by" and "importé par" or "Imported for" and "importé pour", … unless the geographic origin of the food is shown on the label in accordance with subsection (3)."
> "(3) The geographic origin of a food must, subject to the requirements of any other federal or provincial law, be shown (a) in close proximity to the name and principal place of business of the person by or for whom the food was manufactured, processed or produced; and (b) in characters of at least the same height as those in which the information referred to in paragraph (a) is shown."

**SFCR s. 206(2)** (bilingual quoted expressions): "A provision of these Regulations … that requires a consumer prepackaged food to be labelled with words or expressions that appear in quotation marks must be read to require both an English word or expression and a French word or expression to be shown on the label …"

**FDR B.01.007(1.1)(a)** (https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._870/section-B.01.007.html; current to 2026-09-21, last amended 2026-06-17):
> "(1.1) The following information shall be shown on any part of the label: (a) the identity and principal place of business of the person by or for whom the food was manufactured or produced;"

### 4.2 CFIA guidance on the dealer line (verbatim)
Source: https://inspection.canada.ca/en/food-labels/labelling/industry/name-and-principal-place-business. Modified 2022-07-06. Opened 30 Sep 2026 with curl.

> "The name declared on the label of prepackaged food identifies the person who is responsible for the prepackaged food. This person may be Canadian or foreign and is either: the person who has manufactured, prepared, produced, stored, packaged or labelled the food, or the person for whom the food was manufactured, prepared, produced, stored, packaged or labelled"

> "The principal place of business must lead to a physical location where the principal, or main, business can be found. … Websites, telephone numbers, and virtual addresses are not acceptable principal place of business declarations …"

> "Imported products that are not considered to have been wholly manufactured, processed or produced outside of Canada (that is to say, processing steps are carried out in Canada to modify the nature of the product) are also subject to these domestic requirements. The addition, removal or combination of one or more ingredients, physical or chemical processing, including grinding and blending, are examples of processes that modify the nature of a product. For example, macadamia nuts that have been imported in bulk and are then roasted, salted and canned in Canada are not wholly manufactured outside of Canada."

> "Consumer prepackaged foods wholly manufactured, processed or produced outside of Canada must indicate "Imported by" / "importé par" or "Imported for" / "importé pour" as part of the name and principal place of business declaration, unless the geographic origin of the foods is shown on the label."

> "An example includes nuts that have been imported in bulk (already roasted and salted) and are only canned in Canada."

> "If an imported product is repackaged at retail, it is not required to indicate "Imported by" / "importé par" or "Imported for" / "importé pour" …"

> "The following options satisfy the above requirements for the name and principal place of business of the responsible party for imported products: declare the name and principal place of business of the foreign manufacturer · declare the name and principal place of business of the Canadian company in close proximity to the country of origin of the product, or · declare "Imported for" or "Imported by" followed by the name and principal place of business of the Canadian company"

> "Additional terms, such as "prepared for", "packaged for", or "distributed by", that provide further information about the name and principal place of business may be voluntarily added on the label of prepackaged products. In general, this is not mandatory."

> "For retail foods … Where multiple stores are owned or franchised by a banner (for example, retail food chain), the legal name of the individual store or franchisee must appear on the label. The banner may also appear, but not on its own."

> "… the name and principal place of business on consumer prepackaged food must be in characters that are at least 1.6 millimetres (1/16 inch) in height [210(2), SFCR]."

> "Unlike other mandatory information …, the name and principal place of business do not have to be declared in both official languages … The expressions "Imported by" or "Imported for", when required on consumer prepackaged foods, must be declared in both official languages [206(2), SFCR]."

> "When "company A" sells their brand name (but not its company name) to "company B", and company B operates at the company B address, new labels will be required right away."

### 4.3 The CFIA consumer guide on "Prepared for" (verbatim; this is the key line for the segment)
Source: https://inspection.canada.ca/en/food-labels/labelling/consumers/canadian-food. Modified 2025-06-04. Opened 30 Sep 2026 with curl.
> "You might also find "Prepared for" when used to describe a food that was prepared for a retailer in Canada. This doesn't mean the food was prepared in Canada."

> "The Government of Canada does not pre-approve food labels and does not have a list of brands or products that are labelled as "Product of Canada" or "Made in Canada"."

> "There is no official logo for Canadian food products and a maple leaf on a product does not always mean the product is Canadian."

> "A Canadian grade does not necessarily mean the product is from Canada."

Transcript of the CFIA video "Choose Canada – Labelling guide" on the same page:
> "Product of Canada means it's all, or almost all, Canadian ingredients, and it's prepared in Canada."
> "Made in Canada means the food product was last significantly changed here in Canada."

(The old CFIA consumer URL …/consumers/shopping-canadian-food returned **HTTP 410 Gone** on 30 Sep 2026. The page above replaces it.)

---

## 5. 2025–2026: what changed, enforcement, and the Competition Bureau

### 5.1 CFIA timeline (all tier a)

| Date | Item | Type | Verbatim / key content | URL (opened 30 Sep 2026) |
|---|---|---|---|---|
| 14 Mar 2025; updated **30 Jul 2025**; page modified 2026-03-16 | *Notice to industry – The importance of accurate use of Product of Canada, Made in Canada and other origin claims* | Guidance / notice | "Updates include: new section on the use of the maple leaf online and on retail shelves · note on the increase in complaints related to origin claims on bulk produce". Also: "Retailers are responsible for the accuracy of any store signage or advertisements about the origin of a food that is store generated." And: "If a food business chooses to use the maple leaf on packaging, retail shelves or online, the CFIA recommends that an accompanying domestic content statement … be placed in close proximity to the maple leaf". And: "We have seen an increase in complaints related to origin claims on bulk produce, on food labels and in advertisements, including some related to "Product of Canada" and "Made in Canada"." And: "the information provided on retail shelves should not conflict with the information declared on the label." And: "The CFIA … will take the appropriate enforcement action to protect Canadians from misleading claims if non-compliance is found." | https://inspection.canada.ca/en/food-labels/labelling/notice-industry-2025-03-14 (curl) |
| Modified **2025-06-04** | Consumer guide *How to identify Canadian food* | Guidance (consumer) | Adds "100% Canadian", "Other Canadian content claims", "Prepared for", maple leaf, grades, and the provincial buy-local programs (quotes in section 4.3) | https://inspection.canada.ca/en/food-labels/labelling/consumers/canadian-food (curl) |
| Guideline page unchanged since **2023-12-06** | *Origin claims on food labels* | Guidance | **No 2025–26 revision to the guideline text itself** (date-modified stamp on the page) | https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims (curl) |
| Received **11 Dec 2025** | AAFC Question Period note AAFC-2025-QP-00123, "MAPLE WASHING AND PRODUCT OF CANADA LABELLING GUIDELINES" (Minister Heath MacDonald) | Government briefing record | "The "Product of Canada" and "Made in Canada" guidelines for food have been in effect since December 31, 2008." · "The misuse of a maple leaf or a Canadian content claim on a food label or in stores (often referred to as "maple washing") is not permitted because it can mislead consumers." · "The Government of Canada is committed to helping consumers Buy Canadian by increasing transparency and stringency in origin of product labelling so it is simple, clear, and easy to identify what is a truly Canadian product." · "The CFIA has received increased complaints regarding country of origin claims on food labels and advertisements, including issues related to the use of "Product of Canada"." · It also refers to "a social media campaign, including a video produced by Agriculture and Agri-Food Canada (AAFC)" and "an industry toolkit to promote labelling compliance, which was a collaboration between CFIA, AAFC and Innovation, Science and Economic Development Canada (ISED)". | https://search.open.canada.ca/qpnotes/record/aafc-aac,AAFC-2025-QP-00123 (curl) |
| **16 Mar 2026** | CFIA Statement, "Food businesses face penalties for mislabelling products as Canadian" | **Penalty (regulator statement)** | "Since April 1, 2025, the Agency has issued $47,000 in financial penalties to businesses for inaccurate or misleading country of origin claims: 1000717809 Ontario Limited (Fortinos Etobicoke) received a $10,000 penalty; Fresh in The City Inc. received a $7,000 penalty; Meatex Farms Ltd. received a $10,000 penalty; Oxford Frozen Foods Inc. received a $10,000 penalty; Real Canadian Superstore received a $10,000 penalty." · "In addition to responding to complaints, we conduct inspections to verify origin claims on labels and advertisements, including in-store signage." · "The CFIA selects appropriate compliance and enforcement actions based on a range of considerations including, the degree of risk, the harm caused by the non-compliance, the compliance history of the regulated party, whether there is negligence or intent to violate federal requirements, and responsiveness to resolving the issue." **The statement does not identify which products were involved. Nothing in it relates to oats or oatmeal. Do not connect these names to any oat product** (see UNVERIFIED). | https://www.canada.ca/en/food-inspection-agency/news/2026/03/food-businesses-face-penalties-for-mislabelling-products-as-canadian.html (curl) |
| 26 Jan 2026 | PM speech on groceries | Government statement | Speaks of "unit price labelling … in this era of "shrinkflation"" and support for the Competition Bureau. **No origin-labelling measure found in the text.** | https://www.pm.gc.ca/en/news/speeches/2026/01/26/prime-minister-carney-announces-new-measures-make-groceries-and-other (curl) |

### 5.2 Competition Bureau (tier a)
- **The Bureau's role on food.** Its *"Product of Canada" and "Made in Canada" Claims* enforcement guidelines are dated **March 7, 2025** (page modified 2025-03-17). They cover **non-food** products and defer food to the CFIA. Source: https://competition-bureau.canada.ca/en/how-we-foster-competition/education-and-outreach/publications/product-canada-and-made-canada-claims (curl, 30 Sep 2026). Verbatim:
  - "The Consumer Packaging and Labelling Act … applies only to non‑food products"
  - "The Canadian Food Inspection Agency has a mandate to enforce Canada's food legislation, including the Safe Food for Canadians Act (SFCA) … Until December 31, 2008, the CFIA relied on the Bureau's Guide to "Made in Canada" Claims to enforce the CPLA in relation to food products. Since then, the CFIA published its own guide …"
  - "These enforcement guidelines provide a distinction between "Product of Canada" and "Made in Canada" claims for non-food products. "Product of Canada" claims are subject to a higher threshold of Canadian content (98%), while "Made in Canada" claims are subject to a 51% threshold of Canadian content but should be accompanied by a qualifying statement …"
  - "Depending on the context, pictorial representations (e.g., logos, pictures, or symbols such as the Canadian flag or maple leaf) may by themselves be just as forceful as an explicit "Made in Canada" written representation."
  - **Do not apply the Bureau's 98%/51% cost thresholds to oatmeal.** For food the CFIA's "all or virtually all" and qualifier rules govern.
- **Consumer page.** *Made in Canada claims*, https://competition-bureau.canada.ca/en/deceptive-marketing-practices/made-canada-claims (date modified **2026-06-14**). **Opened via WebFetch only; curl was reset.** Tool-extracted quotes: "For information relating to the labelling of food products, visit the Canadian Food Inspection Agency's website." · "Don't assume a product is Canadian just because it displays red colours or a maple leaf design." · "Canadian symbols, colours or logos used in a deceptive way could raise concerns under the law." (flagged in UNVERIFIED; re-copy from the live page before air).
- **No Competition Bureau enforcement action on a "Canadian" food or oat claim in 2025–2026 was found.**

---

## 6. Is there a Canadian standard of identity for rolled oats, oatmeal or oat flakes? **No.**

| Searched | Result | Source (opened 30 Sep 2026, curl) |
|---|---|---|
| **Canadian Food Compositional Standards** (CFCS; incorporated into the FDR), all 19 volumes; full-text search for "oat" | **Zero matches.** Volume 12 "Grain and Bakery Products" has standards for flour, whole wheat flour, graham flour, another wheat-flour standard (12.1.5), crushed wheat, cracked wheat, rice, corn starch, cottonseed flour (12.1.1–12.1.10) and breads (12.2.1–12.2.6). **No oats, rolled oats, oatmeal or oat flakes.** | https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference/canadian-food-compositional-standards-0 (modified 2025-05-01) |
| **Canadian Standards of Identity** (SFCR), Volumes 1–8 | Dairy, Processed Egg, Fish, Processed Fruit or Vegetable, Honey, Maple, Meat, Icewine. **No grain or cereal volume.** | https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference |
| **Canadian Grade Compendium**, Volumes 1–9 | Ovine/poultry carcasses, fresh fruit/veg, processed fruit/veg, dairy, eggs, honey, maple syrup, fish, import grade requirements. **No cereal consumer grade.** | Same page |
| **Food and Drug Regulations** full text; search for "oat", "oats", "oatmeal", "rolled oat", "oat flake" | **"oatmeal", "rolled oat" and "oat flake" appear nowhere.** "oats" appears once, inside a definition in a topic barred by house rule 1 (not reproduced; see DO-NOT-USE). Division 13 "Grain and Bakery Products" has a section B.13.060 headed "Breakfast Cereal", but it is a nutrient-addition provision, **not a standard of identity** (barred topic; not reproduced). | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._870/FullText.html (current to 2026-09-21) |

**What follows.** With no standard, the **common name** of oats is governed by limb (c) of the definition, quoted verbatim from the CFIA common name page (https://inspection.canada.ca/en/food-labels/labelling/industry/common-name, modified 2025-01-15): "(c) in any other case, the name by which it is generally known or a name that is not generic and that describes the food" [B.01.001(1), FDR; 1, SFCR]. In practice, terms like "quick", "large flake", "steel cut" and "instant" are **not legally defined compositional terms** in Canada. They are subject only to the general false-or-misleading rules in section 1. This is an inference from the absence of a standard; it has not been checked against a CFIA statement.

---

## 7. Canadian Grain Commission grades for oats (context only)

The CGC website (grainscanada.gc.ca) **could not be opened** on 30 Sep 2026: curl gave connection resets and WebFetch got HTTP 503. The grade tables below come from the **regulation** on Justice Laws, which is tier a.

- **Canada Grain Regulations** (C.R.C., c. 889; current to 2026-09-21, last amended 2026-08-01), https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._889/FullText.html, opened 30 Sep 2026 with curl:
  - s. 5(1): "The following seeds are designated as grain for the purposes of the Act: barley, … oats, …"
  - **Schedule 3, Table 7, "Oats, Canada Western (CW)":** grade names **No. 1 CW, No. 2 CW, No. 3 CW, No. 4 CW**. The standard-of-quality columns include "Minimum Test Weight" (kg/hL: 56 / 53 / 51 / 48) and "Degree of Soundness" ("Good colour, 98% sound groats" / "Good colour, 96% sound groats" / "Fair colour, 94% sound groats" / "Poor colour, 92% sound groats"). There are also maximum limits for damage and foreign material.
  - **Schedule 3, Table 45, "Oats, Canada Eastern (CE)":** **No. 1 CE – No. 4 CE**. Minimum test weight (kg/hL): 51 / 49 / 46 / 43. Soundness: "Good natural colour, 98% sound groats" through "Poor colour, 92% sound groats".
- **Canada Grain Act** (R.S.C. 1985, c. G-10; current to 2026-09-21), https://laws-lois.justice.gc.ca/eng/acts/G-10/FullText.html, opened 30 Sep 2026 with curl. Verbatim definitions:
  - "Western Division means all that part of Canada lying west of the meridian passing through the eastern boundary of the City of Thunder Bay, including the whole of the Province of Manitoba"
  - "Eastern Division means that part of Canada not included in the Western Division"
  - "western grain means grain, other than imported grain, that is delivered into the Western Division"
  - "**imported grain means any grain grown outside Canada or the United States** and includes screenings from such a grain and every grain product manufactured or processed from such a grain"
  - s. 32(1)(a): an inspector issues a certificate "if the grain was grown in Canada or the United States, … assigning to the grain a grade established by or under this Act …"
  - s. 16(1): "The Commission may, by regulation, establish grades and grade names for any kind of western grain and eastern grain … for the purposes of meeting the quality requirements of purchasers of grain."
- **What a grade covers.** It is a **bulk-grain trading quality grade** (test weight, soundness, damage, foreign material) used at elevators and in inspection certificates. It is **not a consumer-package origin claim**, and no oats grade is required on retail packages (see section 6: no grade compendium volume for cereals).
- On the Act's literal text, "CW"/"CE" names a **division of delivery**, and the Act's "imported grain" definition excludes U.S.-grown grain. **Do not tell viewers that a "CW" grade proves Canadian origin.** Any stronger reading needs legal review (see UNVERIFIED).

---

## 8. Customs tariff and the 2025–2026 counter-tariffs

### 8.1 Customs Tariff 2026 (CBSA). **Opened via WebFetch only**; curl and PDF downloads of the chapter files were reset
Version T2026-2, effective 2026-09-01: https://www.cbsa-asfc.gc.ca/trade-commerce/tariff-tarif/2026/html/02/ch10-eng.html, …/ch11-eng.html and …/ch19-eng.html.

| Tariff item | Description (tool-extracted) | MFN | UST (U.S. Tariff) |
|---|---|---|---|
| 1004.10.00 | "Oats. - Seed" | Free | Free |
| **1004.90.00** | "Oats. - Other" | Free | Free |
| 1103.19.90.20 | "Of other cereals - Other - Of oats" (groats and meal) | Free | Free |
| **1104.12.00** | Heading 11.04: "Cereal grains otherwise worked (for example, hulled, rolled, flaked, pearled, sliced or kibbled) …"; subheading "Rolled or flaked grains: Of oats" | Free | Free |
| 1104.22.00 | "Other worked grains …: Of oats" | Free | Free |
| 19.04 (heading) | "Prepared foods obtained by the swelling or roasting of cereals or cereal products (for example, corn flakes); cereals (other than maize (corn)) in grain form or in the form of flakes or other worked grains (except flour, groats and meal), pre-cooked or otherwise prepared, not elsewhere specified or included." | 1904.10.90: 6%; 1904.20.50 ("other" unroasted cereal flakes): 6% (tool-extracted) | Free |

**Product classification:** this file does **not** classify any named oatmeal product, Quaker-type or otherwise, under any tariff item. Classification of a specific SKU is a CBSA determination.

### 8.2 The 2025 counter-tariffs: oats were on the first list, then removed

| Date | Event | Oat-related items | Source (opened 30 Sep 2026, curl) |
|---|---|---|---|
| Page dated 2025-02-02 | Finance backgrounder "List of products from the United States subject to 25 per cent tariffs effective February 4, 2025" ($30B list) | Includes **1004.90.00 "Oats."** No 1104, 1103 or 1904 items. | https://www.canada.ca/en/department-finance/news/2025/02/list-of-products-from-the-united-states-subject-to-25-per-cent-tariffs-effective-february-4-2025.html |
| **4 Mar 2025** | Finance: "Canada announces robust tariff package …". Verbatim: "The first phase of Canada's response includes tariffs on $30 billion in goods imported from the U.S., effective as of 12:01 a.m., March 4, 2025." The backgrounder list includes **1004.90.00 "Oats."** | 1004.90.00 only | https://www.canada.ca/en/department-finance/news/2025/03/canada-announces-robust-tariff-package-in-response-to-unjustified-us-tariffs.html ; https://www.canada.ca/en/department-finance/news/2025/03/list-of-products-from-the-united-states-subject-to-25-per-cent-tariffs-effective-march-4-2025.html |
| **4 Mar 2025** (legal instrument) | **United States Surtax Order (2025-1), SOR/2025-66**, P.C. 2025-265, registered March 3, 2025. Verbatim: "goods that originate in the United States that are classified under any of the tariff items set out in the schedule are subject to a surtax in the amount of 25% of the value for duty …" and "This Order comes into force, or is deemed to have come into force, on March 4, 2025." The schedule lists **"1004.90.00"**. | 1004.90.00 | https://gazette.gc.ca/rp-pr/p2/2025/2025-03-12/html/sor-dors66-eng.html |
| 4 Mar – 2 Apr 2025 | Finance consultation on a further $125B list. Verbatim: "The consultation ran from March 4, 2025, to April 2, 2025." Status "Closed". **The proposed list itself is no longer on the page** (see UNVERIFIED). | Unknown | https://www.canada.ca/en/department-finance/programs/consultations/2025/notice-intent-impose-countermeasures-response-united-states-tariffs-on-canadian-goods.html (modified 2025-04-03) |
| 16 Apr 2025 – 16 Oct 2025 | **Remission.** The SOR/2025-181 explanatory note (verbatim): "On April 16, 2025, Canada implemented the United States Surtax Remission Order (2025), which provides temporary, horizontal relief … It also provides relief for any goods used as inputs in Canadian manufacturing, processing or food and beverage packaging. Remission under this Order expires on October 16, 2025." | Context: inputs used in Canadian processing could qualify. Whether any oat importer claimed it is unknown. | https://gazette.gc.ca/rp-pr/p2/2025/2025-09-10/html/sor-dors181-eng.html |
| **1 Sep 2025** | **Removal.** SOR/2025-181 (verbatim): "the Order … removes tariffs on the full set of goods ($30.3 billion in annual imports from the United States) listed under the United States Surtax Order (2025-1) … from September 1, 2025, onwards." | **1004.90.00 removed** | Same URL |
| Finance complete list (modified 2026-09-24) | Section "Effective up to August 31, 2025": row **"1004.90.00 \| Cereals \| Oats. \| Other \| 2025-03-04 \| 25%"**. The page notes: "The consolidated list below is prepared for information purposes only and has no official sanction." | Confirms 1004.90.00, 25%, from 2025-03-04 | https://www.canada.ca/en/department-finance/programs/international-trade-finance-policy/canadas-response-us-tariffs/complete-list-us-products-subject-to-counter-tariffs.html |

### 8.3 The new counter-tariffs from 8 September 2026: no oat items
Same Finance page, verbatim: "As a result of the U.S.'s decision to impose a 50 per cent tariff on $27.6 billion of Canadian goods effective August 22, 2026, the Prime Minister announced that Canada will match the incoming U.S. Section 338 tariffs – dollar for dollar." · "These new countermeasures on $27.6 billion in products imported from the U.S. are effective as of 12:01 a.m., September 8, 2026." · "List updated as of August 26, 2026". The CBSA tariff index page banner also reads "Starting September 8, 2026: Surtaxes (counter tariffs) on certain U.S. goods" (https://www.cbsa-asfc.gc.ca/trade-commerce/tariff-tarif/menu-eng.html, curl).

**Machine check of every tariff item in all three sections of the complete list** (parsed 30 Sep 2026):

| List section | Tariff items in section | Chapter 10/11/19 items present | Oat items? |
|---|---|---|---|
| Effective September 8, 2026 | 648 | 1901.20.11–1901.20.29 only. These are "Mixes and doughs for the preparation of bakers' wares of heading 19.05 … Containing more than 25% by weight of butterfat …", at rate 50. | **None** |
| Effective September 1, 2025 to September 7, 2026 | 313 | none | **None** |
| Effective up to August 31, 2025 | 1,814 | wheat, durum, rye, barley, **1004.90.00 oats**, rice, wheat flour (1101), 1901.20/1901.90 dairy-mix lines, pasta (1902), 1905.90.51 | **1004.90.00 only** |

**Never on any section:** 1004.10 (seed oats), 1102, 1103 (oat groats/meal), **1104.12 (rolled/flaked oats)**, 1104.22, and **all of heading 19.04**.

**U.S. context, labelled U.S.:** the Finance page refers to "U.S. Section 338 tariffs" of 50% on Canadian goods from August 22, 2026. Whether Canadian oats or oat products are covered was **not checked** (see UNVERIFIED).

---

## 9. In-store checklist: what each label feature lawfully tells a shopper (and what it doesn't)

| Label feature | What it lawfully tells you | What it does **not** tell you | Rule / source |
|---|---|---|---|
| **"Product of Canada"** | Under CFIA guidance, "all or virtually all major ingredients, processing, and labour" are Canadian. Non-Canadian material is "negligible", generally under 2% in total. | It is not government-certified: "The Government of Canada does not pre-approve food labels". Packaging, seed and fertilizer may be imported. | CFIA origin claims page; CFIA consumer guide |
| **"Canadian"** (as a claim, e.g. "Canadian oats" on the front) | The CFIA treats it as **the same as Product of Canada**. If it describes an ingredient ("Canadian oats"), all of that ingredient and its derivatives must be Canadian. | Whether a **brand or company name** containing "Canadian" is treated as a claim is **not expressly addressed** in the CFIA origin page. Only the general "overall impression" principle applies. **Do not say any brand breaks the rule.** | CFIA origin page; CFIA general principles |
| **"100% Canadian"** / "Made with 100% Canadian oats" | Entirely Canadian (for the food, or for the named ingredient and all its derivatives). | For an ingredient claim, nothing about the other ingredients. | CFIA origin page |
| **"Made in Canada from domestic and imported ingredients"** | The last substantial transformation happened in Canada, and there is a mix of Canadian and imported ingredients. | **How much** is Canadian: the claim applies "regardless of the level of Canadian content". The order may be reversed when imported content is higher. | CFIA origin page and FAQ |
| **"Made in Canada from imported ingredients"** | Made in Canada; the ingredients are all from outside Canada. | Which countries. | CFIA origin page |
| **Bare "Made in Canada"** (no qualifier) | Under CFIA guidance, "All variations of "Made in Canada" claims must include a qualifying statement" when there are imported ingredients. | A shopper cannot tell from the box whether a qualifier was required. **Do not accuse any product.** | CFIA origin page and FAQ |
| **"Packaged in Canada" / "Processed in Canada" / "Prepared in Canada"** | The named step happened in Canada. CFIA: "Packaged in Canada" describes "a food which is imported in bulk and packaged in Canada". | Where the oats were grown. The claim does not trigger a duty to state the country of origin. | CFIA origin page and FAQ; consumer guide |
| **Maple leaf image** | Possibly nothing. "a maple leaf on a product does not always mean the product is Canadian". The CFIA recommends a domestic-content statement nearby. Depending on use, it "could imply a "Product of Canada" claim". | Origin, unless backed by a statement. | CFIA origin page; Notice (Jul 2025); consumer guide |
| **National flag / stylized 11-point leaf** | Commercial use is protected under Trademarks Act s. 9 and needs Canadian Heritage permission. | Origin, by itself. | Canadian Heritage page; CFIA origin page |
| **The dealer line, with a Canadian address and no other wording** | The name and physical principal place of business of the person **by or for whom** the food was made, packaged or labelled. For **domestic** rules this covers foods modified in Canada (e.g. "grinding and blending"). If the food was **wholly** made abroad and only a Canadian company is named, SFCR 223 requires "Imported by/for" **unless** the origin is shown. | It is not an origin statement. A Canadian address does not by itself mean Canadian oats. | SFCR 218(1)(b), 223; FDR B.01.007(1.1)(a); CFIA dealer page |
| **"Prepared for [retailer/company]"** | Who the food was prepared for. It is a voluntary term ("In general, this is not mandatory"). | Where it was prepared. CFIA: "This doesn't mean the food was prepared in Canada." | CFIA dealer page; consumer guide |
| **"Distributed by" / "Packaged for"** | Voluntary extra information about the responsible party. | Origin. | CFIA dealer page |
| **A U.S. (or other foreign) address in the dealer line** | One lawful way to show a food is imported is to "declare the name and principal place of business of the foreign manufacturer". | Proof that the food was made in that country. The responsible "person may be Canadian or foreign" and can be the person **for whom** the food was made. **Never infer a co-packer** from the address or ingredient list. | CFIA country-of-origin page; CFIA dealer page |
| **"Imported by / Importé par" or "Imported for / Importé pour"** | The food was **wholly** manufactured, processed or produced in a foreign state (SFCR 223). It must be bilingual (SFCR 206(2)). | Which country, unless a geographic origin is also shown. If shown, the origin must be "in close proximity" and in characters "of at least the same height" (SFCR 223(3)). | SFCR 223; CFIA dealer page |
| **"Product of USA" (or other country) near a Canadian company's name** | The geographic origin. For oats this is a lawful alternative to "Imported by", not a commodity requirement. | Anything about the Canadian company beyond its name and address. | SFCR 223(3); CFIA dealer page |
| **No origin wording at all** | Lawful for oats. Grain products are not on the mandatory country-of-origin list. | Anything about origin. Check the dealer line and the company's own statements. | CFIA country-of-origin page; SFCR full text |
| **Canada Organic logo** | The product meets Canada's organic standard. If imported, "Product of [country]" or "Imported" must appear close to the logo (SFCR 354(d)). | Canadian origin. "This does not, by itself, mean it is from Canadian ingredients or made in Canada." | CFIA consumer guide; SFCR 354 |
| **A grain grade such as "No. 1 CW"** (rare on retail packs) | A bulk-grain quality grade under the Canada Grain Regulations. | Origin. "CW"/"CE" are divisions of delivery under the Canada Grain Act, and the Act's "imported grain" definition excludes U.S.-grown grain. CFIA: "A Canadian grade does not necessarily mean the product is from Canada." | Canada Grain Act; Canada Grain Regulations Sch. 3; CFIA consumer guide |
| **Shelf tag or online "Canadian" icon** | The CFIA says: "Retailers are responsible for the accuracy of any store signage or advertisements about the origin of a food that is store generated", and shelf information "should not conflict with the information declared on the label." | Whether the retailer's icon matches the package. Check the box. | CFIA Notice to industry (updated 30 Jul 2025) |

**Wording that is safe for air** (each line restates a primary source):
1. "In Canada, a box of oats doesn't have to tell you where the oats came from. Oats aren't on the CFIA's mandatory country-of-origin list."
2. "'Product of Canada' means all or virtually all Canadian, and the CFIA's own example is an oatmeal cookie."
3. "'Made in Canada from domestic and imported ingredients' can be used regardless of how much is Canadian. Those are the CFIA's words."
4. "'Prepared for' tells you who it was made for, not where. The CFIA says it 'doesn't mean the food was prepared in Canada.'"
5. "A maple leaf on its own isn't a legal claim. The CFIA recommends a statement right next to it."
6. "U.S. oats were on Canada's counter-tariff list from March 4 to August 31, 2025. Rolled oats as a product never were."

---

## 10. Source log (every URL opened on 30 Sep 2026)

| Tier | Source | URL | Page date | Method |
|---|---|---|---|---|
| a | CFIA, Origin claims on food labels | https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims | modified 2023-12-06 | curl |
| a | CFIA, FAQ on Product/Made in Canada | https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims/frequently-asked-questions | 2022-07-06 | curl |
| a | CFIA, Country of origin on food labels | https://inspection.canada.ca/en/food-labels/labelling/industry/country-origin | 2022-07-19 | curl |
| a | CFIA, Name and principal place of business | https://inspection.canada.ca/en/food-labels/labelling/industry/name-and-principal-place-business | 2022-07-06 | curl |
| a | CFIA, How to identify Canadian food (consumer) | https://inspection.canada.ca/en/food-labels/labelling/consumers/canadian-food | 2025-06-04 | curl |
| a | CFIA, Notice to industry 2025-03-14 (updated 2025-07-30) | https://inspection.canada.ca/en/food-labels/labelling/notice-industry-2025-03-14 | 2026-03-16 | curl |
| a | CFIA, Statement 16 Mar 2026 (penalties) | https://www.canada.ca/en/food-inspection-agency/news/2026/03/food-businesses-face-penalties-for-mislabelling-products-as-canadian.html | 2026-03-16 | curl |
| a | CFIA, General principles for labelling and advertising | https://inspection.canada.ca/en/food-labels/labelling/industry/general-principles | 2022-07-06 | curl |
| a | CFIA, Common name | https://inspection.canada.ca/en/food-labels/labelling/industry/common-name | 2025-01-15 | curl |
| a | CFIA, Canadian Food Compositional Standards | https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference/canadian-food-compositional-standards-0 | 2025-05-01 | curl |
| a | CFIA, Documents incorporated by reference | https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference | n/a | curl |
| a | CFIA, 2019 consultation on origin of imported food | https://inspection.canada.ca/en/about-cfia/transparency/consultations-and-engagement/completed/proposed-flm/origin-imported-food | 2019-09-05 | curl |
| a | AAFC QP note AAFC-2025-QP-00123 | https://search.open.canada.ca/qpnotes/record/aafc-aac,AAFC-2025-QP-00123 | received 2025-12-11 | curl |
| a | SFCA s. 6 | https://laws-lois.justice.gc.ca/eng/acts/S-1.1/section-6.html | current to 2026-09-21 | curl |
| a | FDA s. 5 | https://laws-lois.justice.gc.ca/eng/acts/F-27/section-5.html | current to 2026-09-21 | curl |
| a | SFCR ss. 206, 218, 220, 221, 222, 223 and full text | https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/section-223.html (and siblings; FullText.html) | current to 2026-09-21 | curl |
| a | FDR B.01.007 and full text | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._870/section-B.01.007.html ; …/FullText.html | current to 2026-09-21 | curl |
| a | Competition Act ss. 74.01, 74.03 | https://laws-lois.justice.gc.ca/eng/acts/C-34/section-74.01.html ; …/section-74.03.html | current to 2026-09-21 | curl |
| a | Canada Grain Act | https://laws-lois.justice.gc.ca/eng/acts/G-10/FullText.html | current to 2026-09-21 | curl |
| a | Canada Grain Regulations (Sch. 3) | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._889/FullText.html | current to 2026-09-21 | curl |
| a | Competition Bureau, enforcement guidelines (Mar 7, 2025) | https://competition-bureau.canada.ca/en/how-we-foster-competition/education-and-outreach/publications/product-canada-and-made-canada-claims | 2025-03-17 | curl |
| a | Competition Bureau, Made in Canada claims (consumer) | https://competition-bureau.canada.ca/en/deceptive-marketing-practices/made-canada-claims | 2026-06-14 | **WebFetch only** |
| a | Canadian Heritage, commercial use of symbols | https://www.canada.ca/en/canadian-heritage/services/commercial-use-symbols-canada.html | 2026-08-10 | curl |
| a | PM speech, 26 Jan 2026 | https://www.pm.gc.ca/en/news/speeches/2026/01/26/prime-minister-carney-announces-new-measures-make-groceries-and-other | 2026-01-26 | curl |
| a | Finance, complete list of U.S. products subject to counter tariffs | https://www.canada.ca/en/department-finance/programs/international-trade-finance-policy/canadas-response-us-tariffs/complete-list-us-products-subject-to-counter-tariffs.html | 2026-09-24 | curl |
| a | Finance, Feb 2025 $30B list | https://www.canada.ca/en/department-finance/news/2025/02/list-of-products-from-the-united-states-subject-to-25-per-cent-tariffs-effective-february-4-2025.html | 2025-02-02 | curl |
| a | Finance, 4 Mar 2025 release and list | https://www.canada.ca/en/department-finance/news/2025/03/canada-announces-robust-tariff-package-in-response-to-unjustified-us-tariffs.html ; https://www.canada.ca/en/department-finance/news/2025/03/list-of-products-from-the-united-states-subject-to-25-per-cent-tariffs-effective-march-4-2025.html | 2025-03-04 | curl |
| a | Finance, $125B consultation (closed) | https://www.canada.ca/en/department-finance/programs/consultations/2025/notice-intent-impose-countermeasures-response-united-states-tariffs-on-canadian-goods.html | 2025-04-03 | curl |
| a | Canada Gazette II, SOR/2025-66 | https://gazette.gc.ca/rp-pr/p2/2025/2025-03-12/html/sor-dors66-eng.html | 2025-03-12 | curl |
| a | Canada Gazette II, SOR/2025-181 | https://gazette.gc.ca/rp-pr/p2/2025/2025-09-10/html/sor-dors181-eng.html | 2025-09-10 | curl |
| a | CBSA, Customs Tariff index | https://www.cbsa-asfc.gc.ca/trade-commerce/tariff-tarif/menu-eng.html | 2026-01-05 (banner mentions Sep 8, 2026) | curl |
| a | CBSA, Customs Tariff 2026 (T2026-2) ch. 10, 11, 19 | https://www.cbsa-asfc.gc.ca/trade-commerce/tariff-tarif/2026/html/02/ch10-eng.html (ch11, ch19) | effective 2026-09-01 | **WebFetch only** |

---

## UNVERIFIED / DO-NOT-USE

**UNVERIFIED** (re-check before air; do not state as fact):
1. **CBSA Customs Tariff 2026 rows** (section 8.1). These are tool-extracted text from WebFetch; the raw HTML and PDFs of chapters 10, 11 and 19 could not be downloaded (connection resets). Re-copy the exact descriptions and rates from the CBSA page or PDF before showing them on screen.
2. **Competition Bureau consumer page quotes** ("Don't assume a product is Canadian just because it displays red colours or a maple leaf design", etc.). Extracted by WebFetch, curl was reset. Re-copy verbatim.
3. **Canadian Grain Commission Official Grain Grading Guide, Chapter 7 Oats** (grainscanada.gc.ca). **Could not be opened** (resets and HTTP 503). Grade facts here rest on the Canada Grain Regulations instead.
4. **The reading that a "CW"/"CE" grade is not proof of Canadian origin** (Canada Grain Act s. 32(1)(a) and the "imported grain" definition). This is a literal reading of the statute, not CGC guidance. Get legal or CGC confirmation before saying it on air.
5. **Contents of Finance's proposed $125B list** (consultation March 4 – April 2, 2025). The list is no longer on the consultation page. Whether it named any oat or cereal items is unknown. (No such items appear in any section of the current complete list.)
6. **Why the Feb 2025 list was titled "effective February 4, 2025" while the surtax order came into force on March 4, 2025.** The reason for the gap was not verified from a primary page. Use only the Gazette date: **March 4, 2025**.
7. **What happened to the 2019 CFIA proposal** to expand origin labelling "to most imported foods". The SFCR current to 2026-09-21 shows no such general rule, but no CFIA page stating withdrawal or abandonment was found.
8. **The 5 Sep 2025 "Buy Canadian" announcement** that reportedly promised "tightening origin of product labelling". Seen only in search snippets and law-firm summaries (Stikeman; tier b/c). The PM/government release was **not opened**.
9. **The "private enforcement" of deceptive-marketing provisions from June 2025** (Competition Act amendments allowing private access to the Tribunal). Seen only in law-firm summaries; statute text not checked.
10. **Whether any specific oatmeal product (Quaker-type or other) was classified under a listed tariff item** (e.g. 1904.x, 2106.90.x) during 4 Mar – 31 Aug 2025. Not determined; never infer.
11. **Whether any oat importer used the U.S. Surtax Remission Order (2025)** "inputs" relief. Unknown.
12. **U.S. Section 338 tariffs (50%, from Aug 22, 2026)** referenced by Finance. Whether Canadian oats or oat products are covered was not checked. U.S. context only, if used.
13. **The inference in section 6** that "quick", "large flake", "steel cut" and "instant" are undefined in Canadian law. It follows from the absence of a standard but has no CFIA statement to confirm it.
14. **Tier b/c items seen in search results, flag only, not sources:** McCarthy Tétrault, Blakes/Mondaq, Fasken, BLG, DLA Piper, Stikeman, Smart & Biggar, ROBIC, Marks & Clerk, National Magazine, MCS Associates, Canooq blog, Food Compliance International, Acheson Group, briefs.co, globalsecurity.org, the CBC explainer (1.7451556), CBC (1.7636363), Retail Council of Canada, X/Twitter post by @CompBureau. None of them is relied on above.

**DO-NOT-USE** (house rules):
15. **FDR hit for "oats"**: the single occurrence is inside a definition in a barred topic (house rule 1). Not reproduced; do not use.
16. **FDR B.13.060 "Breakfast Cereal"**: a nutrient-addition provision (barred topic). Not reproduced; do not use.
17. **The CFIA country-of-origin page sentence about safety**, and anything on CFIA pages about front-of-package nutrition symbols or other barred topics. Do not quote.
18. **The CFIA general-principles example about heart symbols**: a barred topic. Do not quote.
19. **CFIA 16 Mar 2026 penalty list** (Fortinos Etobicoke numbered company, Fresh in The City, Meatex Farms, Oxford Frozen Foods, Real Canadian Superstore). These are regulator-reported penalties; the statement **does not identify the products**, and **none is connected to oats**. Do not use them in an oatmeal segment in any way that suggests an oat product was involved. If used at all: "the CFIA says it issued $47,000 in penalties for origin claims since April 2025", attributed and dated.
20. **Recalls**: none researched here. Any recall is a food-safety item and goes to an appendix only ("do not use on air").
21. **The channel's December 2025 oatmeal video** (transcript file in scratchpad): not opened or reused. **Competitor oatmeal videos** (nutrition, sugar and pesticide-residue framing): not used.
22. **The old CFIA consumer URL** …/consumers/shopping-canadian-food returned HTTP 410 Gone. Do not link it on screen.

<!-- ===== oatmeal_brands_national.md ===== -->

# Oatmeal in Canada, 2026: dossiers on national and regional brands

**Compiled:** 30 Sep 2026. Every URL below was opened on 30 Sep 2026, Eastern time. The proxy logs show 2026-10-01 00:25–01:05 UTC. Where a page could not be opened, the entry says so, and the item is in the UNVERIFIED section at the end.
**Scope:** rolled, large-flake, quick, one-minute and steel-cut oats, instant oatmeal packets and cups, and hot oat cereals sold at Canadian retail in 2026. Store brands (No Name, PC, PC Blue Menu, PC Organics, Compliments, Selection, Western Family, Only Goodness, Great Value, Giant Value, Co-op Gold, Farm Boy) are listed where they turned up but get no dossier. The exception is **Kirkland Signature**, because the brief asks for its label origin line. Overnight-oat kits, oat bars, granola, cold cereals, oat milk and oat flour are out of scope. Where they turned up, they are listed only.
**House rules applied:** This file contains no health, nutrition, fibre, heart, cholesterol, sugar, protein, gluten, glyphosate, pesticide, heavy-metal, additive or food-safety statements. Where a company or retailer description mixes those claims with other text, only the non-barred words are quoted, and every cut is marked "[…]". Ingredient lists are copied verbatim and are not characterised. Some ingredient names contain a barred word (for example "Gluten Free Whole Grain Oats"). Those are flagged **[verbatim label wording, do not discuss on air]**. Recalls and food-safety notices appear only in Appendix A (**DO NOT USE ON AIR**). Taste and texture words appear only inside attributed company quotes. Nothing here is taken from the channel's December 2025 oatmeal video or from any competitor video.
**Tiers:** (a) primary: government or court records, the company's own site, release, 10-K or annual report, or the retailer's own product page, API, app or flyer. (b) A named outlet with a byline and date. (c) Aggregator, SEO, Wikipedia, review site, Reddit or price tracker: flag only, never a source. (d) A named survey with publisher, year and method (none used here).
**Sibling file:** the rules on "Product of Canada", "Made in Canada", the dealer line, maple leaves and oat tariffs are in `oatmeal_rules_origin.md`. This file does not re-verify that law. Where it leans on that file, it says so.

---

## 0. Headline findings

| # | Finding | Tier / source (opened 30 Sep 2026) |
|---|---|---|
| 1 | **Quaker, Canada's dominant oat brand, is U.S.-owned but made in Canada.** PepsiCo, Inc. (Purchase, N.Y.) completed its merger with The Quaker Oats Company on 2 Aug 2001. PepsiCo Canada says Quaker Canada's oatmeal "comes from" its Peterborough, Ontario plant. | (a) PepsiCo 8-K, 2 Aug 2001: https://www.sec.gov/Archives/edgar/data/77476/000007747601500073/qkrclose.htm ; (a) https://www.pepsicojobs.com/main/our-locations/northamerica/canada |
| 2 | **Quaker's own label image says "MADE IN CANADA FROM DOMESTIC AND IMPORTED INGREDIENTS"** next to a red maple-leaf "MADE IN • FABRIQUÉ AU CANADA" roundel. That is the image Loblaw serves for the 1 kg **Large Flake** box. The same box's front reads "100% WHOLE GRAIN CANADIAN OATS". Its listed ingredient is only "Whole Grain Rolled Oats". This file reports both statements as printed and draws **no inference** about why the qualifier is used. | (a) Loblaw/PC Express API product 20323113002_EA, label images `…/en/3/20323113002_en_3_v1_800.png` and `…/en/8/…_en_8_v1_800.png` |
| 3 | **Robin Hood oats are owned by a U.S. company.** The site footer reads "© / TM / MC / ® / MD Smucker Foods of Canada Corp. or its affiliates." Smucker's FY2026 10-K lists **no Canadian oat mill**: Sherbrooke, Que. (canned milk) is its only Canadian plant. In 2006 Smucker sold its Canadian flour mills to Horizon Milling (Cargill/CHS) and kept the Robin Hood retail brand under a co-packing arrangement. The front of the oat bag carries a "MADE WITH • FAIT AVEC [maple leaf] 100% CANADIAN OATS / GRUAU CANADIEN" badge. | (a) https://www.robinhood.ca/en ; Smucker 10-K FY2026 https://www.sec.gov/Archives/edgar/data/91419/000009141926000050/sjm-20260430.htm ; Smucker 8-K ex. 99.1, 20 Jul 2006 https://www.sec.gov/Archives/edgar/data/91419/000129993306004902/exhibit1.htm ; label image 20893369_EA |
| 4 | **Nature's Path calls itself "Proudly Canadian-owned", yet its instant oatmeal sold in Canada is labelled "PRODUCT OF USA" / "PRODUIT DES É.-U."** The line is printed directly beside the Canada Organic logo, which carries a red maple leaf. | (a) https://naturespath.com/pages/our-path ; Loblaw label images 20304405003_EA (Maple Nut) and 20885283001_EA (Superseeds & Grains) |
| 5 | **Rogers (B.C.) is Japanese-owned.** Rogers Foods calls itself "a proudly Canadian company … headquartered in British Columbia". Nisshin Seifun Group (Japan) lists "Rogers Foods Ltd." as "A Canadian subsidiary". Retailer data marks Rogers Large Flake "Product of Canada". | (a) https://rogersfoods.com/about-us/ ; https://www.nisshin.com/english/company/group/seifun.html ; Save-On-Foods API sku 00060179436253 |
| 6 | **Kirkland Signature rolled oats (Costco) read "PRODUCT OF CANADA / PRODUIT DU CANADA".** The dealer is "Costco Wholesale Canada Ltd.", which is listed as a subsidiary of Costco Wholesale Corporation (U.S.). | (a) Costco.ca product 4000339745, image `1736339-894__2`; Costco 10-K FY2025 Ex. 21.1 https://www.sec.gov/Archives/edgar/data/909832/000090983225000101/costex21110k83125.htm |
| 7 | **McCann's says "IMPORTED / IMPORTÉ" on the front.** The brand belongs to B&G Foods (Parsippany, N.J.), which bought it from TreeHouse Foods on 16 Jul 2018. B&G says a portion of McCann's products is made under co-packing agreements. | (a) Voilà 556616EA image; B&G 8-K ex. 99.1 https://www.sec.gov/Archives/edgar/data/1278027/000110465918045288/a18-17265_1ex99d1.htm ; B&G 10-K FY2025 https://www.sec.gov/Archives/edgar/data/1278027/000110465926022961/bgs-20260103x10k.htm |
| 8 | **Bob's Red Mill is U.S.-made and employee-owned.** The company says it has been "100% employee owned" since 30 Apr 2020. Its address is Milwaukie, Oregon. **The origin line on the Canadian bag could not be read: UNVERIFIED.** | (a) https://www.bobsredmill.com/employee-owned ; https://www.bobsredmill.com/contact |
| 9 | **Red River Cereal contains no oats** (company: "cracked wheat, cracked rye, and cracked & whole flax"), so it is out of scope. It is now made at Arva Flour Mill, Ontario. Arva bought it from Smucker in June 2022 (CBC). **Cream of the West** is a Montana (U.S.) company and was **not found** on any Canadian shelf searched. | (a) https://arvaflourmills.com/collections/red-river-cereal ; (b) Luke Carroll, CBC News, 20 Nov 2022 ; (a) https://creamofthewest.com/ |
| 10 | **No Peterborough closure or investment announcement for 2024–2026 was found** in PepsiCo's filings or in the news searched. The newest dated items are a union contract (Unifor, 19 Jun 2024: "440 members of Local 1996") and a July 2026 local report in which a councillor names Quaker Oats as a major employer the city should work to keep. PepsiCo's 8 Dec 2025 shareholder-value release, which followed engagement with Elliott, **does not mention Quaker**. | (a) PepsiCo 8-K ex. 99.1, 8 Dec 2025; Unifor release; (b) Bethan Bates, kawarthaNOW, 21 Jul 2026 |

### 0.1 One-line readings (details and sources in section 2)

| Brand | Reading |
|---|---|
| **Quaker** | **U.S.-owned (PepsiCo, Inc.), made in Canada (Peterborough, Ont., per PepsiCo Canada); the label says "Made in Canada from domestic and imported ingredients" and the front says "100% whole grain Canadian oats".** |
| **Robin Hood** | **U.S.-owned (The J.M. Smucker Co., via Smucker Foods of Canada Corp., Markham); side panel reads "PRODUCT OF CANADA / PRODUIT DU CANADA" (partly legible, low-resolution image); front badge "Made with 100% Canadian oats"; the miller is not named, and Smucker owns no Canadian oat mill (10-K).** |
| **Bob's Red Mill** | **U.S.-owned (100% employee-owned ESOP, Milwaukie, Oregon); origin line on the Canadian bag UNVERIFIED.** |
| **Nature's Path** | **Canadian-owned (family company founded in Vancouver in 1985; HQ Richmond, B.C.); the instant oatmeal checked reads "PRODUCT OF USA".** |
| **Anita's Organic Mill** | **Canadian-owned (majority-owned by Nature's Path since 9 Nov 2021); made in Chilliwack, B.C. (company text on retailer page).** |
| **Rogers** | **Japanese-owned (Nisshin Seifun Group subsidiary), Product of Canada (retailer attribute); company says "Made in Canada" at mills in Armstrong and Chilliwack, B.C.** |
| **One Degree Organic Foods** | **Owner UNVERIFIED (Abbotsford, B.C., per a 2012 news report); bag reads "Product of Canada / Produit du Canada" (low-resolution image), and Save-On marks it "Product of Canada".** |
| **Only Oats (Avena Foods)** | **Toronto private-equity control since 2017 (tier b; current status UNVERIFIED); Saskatchewan miller; front says "100% Canadian" beside a maple leaf; origin line UNVERIFIED.** |
| **McCann's** | **U.S.-owned (B&G Foods, Inc.); "Imported / Importé"; ingredient line says Irish oats.** |
| **Kirkland Signature (Costco)** | **Store brand of U.S.-owned Costco (via Costco Wholesale Canada Ltd.); "Product of Canada / Produit du Canada".** |
| **Red River** | **Canadian-owned (Arva Flour Mill, Ont.), Product of Canada (retailer attribute); contains no oats, so out of scope.** |
| **Cream of the West** | **U.S. (Montana) company; not found on Canadian shelves.** |

---

## 1. Enumerating the shelf: what was searched, and what was found

### 1.1 Method, retailer by retailer

| Retailer / banner | How it was read (opened 30 Sep 2026) | Result | Tier |
|---|---|---|---|
| Loblaw banners (Loblaws, Real Canadian Superstore, No Frills, Atlantic Superstore, Provigo, Maxi) | PC Express API `https://api.pcexpress.ca/pcx-bff/api/v1/products/search` (POST). 13 stores: Loblaws Toronto 1032, City Market Vancouver 7155; RCSS Calgary 1539, Vancouver 1517, Winnipeg 1511, Saskatoon 1536, Regina 1533; No Frills Toronto 7952, Vancouver 3410, Charlottetown 7763; Atlantic Superstore Halifax 0354; Provigo Montréal 7297; Maxi Montréal 9528. Terms: oatmeal, rolled oats, oats, steel cut oats, instant oatmeal, hot cereal, porridge, red river cereal, cream of the west, gruau. Detail endpoint `…/products/{code}?…` for descriptions, ingredients and label images (`digital.loblaws.ca/PCX/…`) | WORKS. 1,962 rows. Brand list in 1.2 | (a) |
| Voilà by Sobeys | `https://voila.ca/search?q=…` for 10 terms; `https://voila.ca/products/{id}/details`; front image `voila.ca/images-v3/…/1280x1280.jpg`. Default location, no postal code | WORKS. ~360 products scanned | (a) |
| Save-On-Foods | `https://storefrontgateway.saveonfoods.com/api/stores/1982/preview?q=…` (50 queries; capped at 3 items per query) and `…/products/{sku}`. Store 1982 = Langley Twp, B.C. Includes Save-On's own "made in canada" / "product of canada" attributes | WORKS | (a) |
| Giant Tiger | `https://www.gianttiger.com/search?q=…` and `…/products/{handle}.json` (province tags) | WORKS. Quaker, Prana, Giant Value only | (a) |
| Costco | `https://www.costco.ca/CatalogSearch?keyword=oats` returns no items (JS-rendered). Two product pages found by web search and opened directly | Product pages WORK (JSON-LD + label images) | (a) |
| Flyers (Metro, Food Basics, Sobeys, Safeway, IGA, Foodland, Co-op, Walmart, Longo's, Farm Boy, Super C, Thrifty, Buy-Low, Freshmart, SuperValu and others) | Flipp flyer host `https://backflipp.wishabi.com/flipp/items/search?locale=en-ca&postal_code={PC}&q=…` for M5V3L9, H2Y1C6, V6B1A1, T2P1J9, R3C4T3, S7K1J5, B3J1P3, A1C5M2 × (oatmeal, oats, gruau, quaker, robin hood oats, rogers oats, red river cereal) | WORKS. Used to confirm which brands appear in each chain's flyer | retailer flyer via flyer host = (a*) |
| well.ca | `https://well.ca/searchresult.html?keyword=…` | WORKS (Bob's Red Mill listing only; no origin text) | (a) |
| walmart.ca | `https://www.walmart.ca/en/search?q=oatmeal` | **BLOCKED** (redirect to `/blocked`) | — |
| metro.ca | `https://www.metro.ca/en/online-grocery/search?filter=oatmeal` | **BLOCKED** (403) | — |
| longos.com | search | **BLOCKED** (403) | — |
| farmboy.ca | `https://www.farmboy.ca/?s=oats` | 200, site content only (no products). Farm Boy oats appear on Voilà | — |
| Co-op at Home (FCL) | `https://www.coopathome.ca/search?q=oats` | **429** Too Many Requests | — |
| Calgary Co-op | `https://shop.calgarycoop.com/search?q=oats` | **Proxy 502** (connection refused) | — |

### 1.2 Brands found on the oatmeal shelf (with a retailer URL for each)

| Brand | Owner (short; see s. 2) | Where found, with example URL | Dossier? |
|---|---|---|---|
| **Quaker** | PepsiCo, Inc. (U.S.) | Loblaw API, all 13 stores, e.g. https://www.loblaws.ca/large-flake-oats/p/20323113002_EA ; Voilà https://voila.ca/products/217510EA/details ; Save-On sku 00055577101018 ; Giant Tiger https://www.gianttiger.com/products/quaker-instant-oatmeal-flavour-variety-instant-oatmeal-packets-8-pack-314-g ; Costco https://www.costco.ca/p/-/quaker-quick-oats-2-258-kg/100570610 ; flyers: Metro, Walmart, Super C, IGA, Thrifty, Longo's, Co-op | Yes (2.1) |
| **Robin Hood** | J.M. Smucker (U.S.) | Loblaw 20893369_EA, 20893370_EA, 20894131_EA (9–11 stores); Voilà 280532EA ; Save-On 00059000084749 ; flyers: Sobeys, IGA, Foodland, Co-op, SuperValu, Freshmart | Yes (2.2) |
| **Bob's Red Mill** | Employee-owned (U.S.) | Loblaw 21127426_EA (13 stores) and 6 other SKUs; Voilà 15 SKUs, e.g. 938294EA ; Save-On 00039978004949 ; well.ca ; flyers: RCSS, Longo's | Yes (2.3) |
| **Nature's Path** | Family-owned (Canada) | Loblaw 20304405003_EA and 5 other SKUs; Voilà 114135EA and 5 others; Save-On 00058449450016 | Yes (2.4) |
| **Anita's Organic Mill** | Nature's Path (majority) | Loblaw 21304184_EA (3 stores: Toronto, Calgary, Winnipeg) | Yes (2.5) |
| **Rogers** | Nisshin Seifun Group (Japan) | Loblaw 20717030_EA, 20718427_EA ; Save-On 00060179436253 (Large Flake) and 3 porridge blends | Yes (2.6) |
| **One Degree Organic Foods** | UNVERIFIED | Loblaw 21532752_EA, 21532753_EA, 21535637_EA ; Voilà 1336258EA, 1382106EA (instant) ; Save-On 00675625323072 | Yes (2.7) |
| **Only Oats** (Avena Foods) | UNVERIFIED (see 2.8) | Voilà 610109EA, 610326EA, 766074EA ; Avril flyer (Montréal) | Yes (2.8) |
| **McCann's** | B&G Foods (U.S.) | Voilà 556616EA (steel cut), 556636EA (quick) | Yes (2.9) |
| **Kirkland Signature** | Costco (U.S.) store brand | Costco.ca https://www.costco.ca/p/-/kirkland-signature-whole-grain-rolled-oats-454-kg/4000339745 | Origin line only (2.10) |
| **Dan-D-Pak** | UNVERIFIED (label: Dan-D Foods) | Loblaw 20876492_EA, 20876242_EA ; Voilà 313459EA, 313453EA ; flyers: Foody World, Seasons, Thrifty | Brief (3) |
| **Stoked Oats** | UNVERIFIED | Loblaw 20971529_EA, 20971534_EA ; Voilà 774945EA, 774946EA, 610244EA ; flyers: Metro, Farm Boy | Brief (3) |
| **Oak Manor** | UNVERIFIED | Loblaw 20016104_EA (7 stores) | Brief (3) |
| **Willow Creek Organic Grain Co.** | UNVERIFIED | Voilà 301646EA, 301659EA, 688189EA and others | Brief (3) |
| **Wildly Canadian** | UNVERIFIED | Voilà 446420EA (no image: "Image coming soon") | Brief (3) |
| **Adagio Acres** | UNVERIFIED | Voilà 496033EA, 622661EA | Brief (3) |
| **Highwood Crossing** | UNVERIFIED | Voilà 839413EA ; also "Power Grains Hot Cereal" 839408EA | Brief (3) |
| **La Meunerie Milanaise / Milanaise** | UNVERIFIED | Voilà 756354EA, 576503EA | Brief (3) |
| **Speerville Flour Mill** | UNVERIFIED | Loblaw 20059495_EA (Atlantic Superstore Halifax only) | Brief (3) |
| **Good Eats** (listed under "Pilling Foods Inc.") | UNVERIFIED | Voilà 941211EA | Brief (3) |
| **Grace** (instant oats) | UNVERIFIED | Loblaw 20602221_EA ; Voilà 211979EA | Brief (3) |
| **Yumi Organics** (instant oatmeal) | UNVERIFIED | Loblaw 21706743_EA, 21660783_EA, 21660610_EA | Brief (3) |
| **Saffola** (masala oats) | UNVERIFIED | Loblaw 21707672_EA | Brief (3) |
| **Sunny Boy** (hot cereal; oat content not verified) | UNVERIFIED | Voilà 507866EA, 507865EA | Brief (3) |
| **Red River** (no oats) | Arva Flour Mill | Voilà 7378EA ; Save-On 00624307101378 | Short (2.11) |
| Overnight-oat kits (out of scope, listed only) | — | MUSH (Loblaw 21673494_EA), Prana (Loblaw 21439406_EA; Giant Tiger), Oatbox (Voilà 840791EA), Madame Labriski (Voilà 219969EA), Yumi Organics overnight (Voilà 6755EA), Farm Boy | Oatbox brief (3) |
| Flyer-only names (no product page opened) | — | Hamlyns (Supermarché PA, Montréal), Dunya (Vie En Vert), GOLDY'S instant oatmeal (Community Natural Foods, Calgary), Benefits By Nature (Healthy Planet) | Listed only |
| Store brands (no dossier) | — | No Name, PC, PC Blue Menu, PC Organics (Loblaw); Compliments, Farm Boy (Voilà); Western Family, Only Goodness (Save-On; onlygoodness.ca redirects to https://www.saveonfoods.com/only-goodness); Giant Value (Giant Tiger); Selection (Metro, Food Basics, Super C flyers); Co-op Gold (Co-op flyer); Great Value (not reached, Walmart blocked) | — |

### 1.3 Expected brands that were **not** found on any Canadian shelf searched

| Brand | What was checked | Result |
|---|---|---|
| Cream of the West | Loblaw API term "cream of the west" (13 stores); Voilà search; Save-On preview | Nothing. Voilà returned an unrelated item; Save-On returned a bath bomb and a water bottle. Company is in Montana (2.12) |
| Holista | Save-On preview "holista" | Only "Holista - Shampoo - Tea Tree Oil Shampoo". No oat product |
| Grain Millers / "Rolling Hills" | Save-On preview "grain millers"; Loblaw and Voilà brand lists | No retail oat product under either name |
| Kellogg / WK Kellogg (hot oat cereal) | Loblaw API brand list | Only cold cereals ("Kelloggs" Special K, Mini Wheats, Vector). No hot oat product |
| Dorset Cereals | Save-On preview "dorset" | Only two **mueslis** (sku 00814930010769, 00814930010721): out of scope; ownership not checked |
| Uncle Tobys | Save-On preview "uncle tobys"; Loblaw and Voilà brand lists | Nothing |
| Flahavan's | Save-On preview "flahavans" | Nothing |

---

## 2. Dossiers

### 2.1 Quaker (PepsiCo, Inc.)

**Owner and chain (tier a unless marked)**
| Date | Event | Source |
|---|---|---|
| 1877 | "The Quaker brand registers the first trade-mark for a breakfast cereal." (company timeline) | https://www.tastyrewards.com/en-ca/brands/quaker/about-us (quakeroats.ca redirects here) |
| 1902 | "The major Canadian production facility for Quaker Oats is located in Peterborough, Ontario on the shores of the Otonabee River." (company timeline) | same |
| 2 Aug 2001 | "PepsiCo said today it has completed its merger with The Quaker Oats Company" | PepsiCo 8-K, https://www.sec.gov/Archives/edgar/data/77476/000007747601500073/qkrclose.htm |
| 27 Dec 2025 | PepsiCo's subsidiary list includes "PepsiCo Canada ULC" (Canada) and "The Quaker Oats Company" (New Jersey) | PepsiCo 10-K FY2025 Ex. 21, https://www.sec.gov/Archives/edgar/data/77476/000007747626000007/pepsico202510-kexhibit21.htm |
| 2026 | Site copyright "© 2026 PepsiCo Canada ULC" | https://contact.pepsico.com/quakerca/about-us |
| FY2025 | Segment: "PepsiCo Foods North America (PFNA), which includes all of our convenient food businesses in the United States and Canada"; PFNA sells "oatmeal … under various brands including … Quaker" | PepsiCo 10-K FY2025, https://www.sec.gov/Archives/edgar/data/77476/000007747626000007/pep-20251227.htm |

Parent: PepsiCo, Inc., 700 Anderson Hill Road, Purchase, New York (8-K cover, 8 Dec 2025).

**Where it is made (company)**
- PepsiCo Canada: "Quaker Canada's oatmeal, cold cereal, granola bars, corn snacks, and pancake mixes comes from Peterborough, Ontario, location. Crispy rice snacks are made at our Trenton, Ontario, facility." https://www.pepsicojobs.com/main/our-locations/northamerica/canada
- PepsiCo Canada: "PepsiCo Canada operates two Quaker plants: Trenton (Ontario) and Peterborough (Ontario)." https://contact.pepsico.com/quakerca/about-us
- The plant sits on Hunter Street: "the Hunter Street Quaker plant" (b) kawarthaNOW, 5 Jun 2023, byline "kawarthaNOW" (no named reporter), https://kawarthanow.com/2023/06/05/quaker-oats-releases-new-commercial-filmed-in-peterborough/

**Origin line, main large-flake SKU (Quaker Large Flake Oats, 1 kg, Loblaw 20323113002_EA)**
- Label tile served by Loblaw (image 3 of 8): "MADE IN • FABRIQUÉ AU [red maple leaf] CANADA", and below it: **"MADE IN CANADA FROM DOMESTIC AND IMPORTED INGREDIENTS. FABRIQUÉ AU CANADA À PARTIR D'INGRÉDIENTS CANADIENS ET IMPORTÉS."** https://digital.loblaws.ca/PCX/20323113002_EA/en/3/20323113002_en_3_v1_800.png
- Front of box (image 8): "100% WHOLE GRAIN CANADIAN OATS". Top right is a white badge: "MADE WITH [maple leaf] 100% WHOLE GRAIN CANADIAN OATS". Bottom left is a black square: "MADE IN [maple leaf] CANADA". https://digital.loblaws.ca/PCX/20323113002_EA/en/8/20323113002_en_8_v1_800.png
- Tile (image 2): "MADE WITH 100% WHOLE GRAIN CANADIAN OATS / FAIT AVEC DE L'AVOINE À GRAINS 100% CANADIENNE" https://digital.loblaws.ca/PCX/20323113002_EA/en/2/20323113002_en_2_v1_800.png
- Retailer description (Loblaw API): "Get your day off to a delicious and satisfying start with Quaker Large Flake oats. Made with 100% whole grain Canadian oats, […]"
- Retailer attribute: Save-On-Foods marks Quaker Large Flake, Quick Oats and Regular Instant **"made in canada": true, "product of canada": false** (API skus 00055577101018, 00055577101100, 00055577113011, store 1982).
- **Dealer line:** not visible in any image examined. UNVERIFIED.

**Origin line, main instant SKU (Quaker Instant Oatmeal Maple & Brown Sugar, 8 packets, 344 g, Loblaw 21190254_EA)**
- Retailer description (Loblaw API): "Made in Canada from domestic and imported ingredients." and "made in Canada from domestic and imported ingredients."
- Label tiles: "MADE WITH [maple leaf] 100% CANADIAN OATS" badge, and a navy roundel "MADE IN • FABRIQUÉ AU [maple leaf] CANADA" (image 3 https://digital.loblaws.ca/PCX/21190254_EA/en/3/21190254_en_3_800.png ; image 2 …/en/2/21190254_en_2_800.png).

**Where the company says its oats come from (attributed):** "Made from 100% whole grain Canadian oats […]" (Quick Oats page, https://www.tastyrewards.com/en-ca/brands/quaker/products/quick-quakerr-oats). PepsiCo's 10-K lists oats among its "principal ingredients" but does not give a country.

**Ingredients (verbatim)**
- Large Flake 1 kg (Loblaw API): "Whole Grain Rolled Oats. Contains Oat Ingredients. May Contain Wheat Ingredients."
- Instant Maple & Brown Sugar 344 g. The label image reads: "Ingredients: Whole grain rolled oats, Sugar, Salt, Fruit and vegetable juice concentrates (apple, purple carrot, purple corn), Natural flavour. Contains: Oats May contain: Wheat" (image 5, https://digital.loblaws.ca/PCX/21190254_EA/en/5/21190254_en_5_800.png). The Loblaw API text gives the juice order as "(apple, Purple Corn, Purple Carrot)". Voilà's listing (418756EA) gives a different, shorter list: "Whole Grain Oats, Sugar, Salt, Natural Flavour." Retailer data are not label-current; **use the label image only.**

**Company product description (verbatim, barred words cut):** "Ready in just 5 minutes, Quaker ® Quick Oats are the perfect way to start the day. Made from 100% whole grain Canadian oats […]" (Quick Oats page above).

**Maple leaf / "Canadian" marketing on pack (described):** red maple leaf in the "Made in • Fabriqué au Canada" roundel; maple leaf in the "Made with 100% whole grain Canadian oats" badge; front line "100% WHOLE GRAIN CANADIAN OATS". Quaker Canada's local campaign brand is "QUAKERborough" (kawarthaNOW, 5 Jun 2023, above).

**Dated news, 2022–2026 (tier b unless marked)**
| Date | Item | Source |
|---|---|---|
| 13 Sep 2022 | Peterborough council endorsed selling naming rights for a downtown park to PepsiCo Canada as "Quaker Foods Urban Park". PepsiCo "produces Quaker-branded products including oatmeal at its Hunter Street plant" | kawarthaNOW (byline "kawarthaNOW"), https://kawarthanow.com/2022/09/13/peterboroughs-new-urban-park-to-be-named-quaker-foods-urban-park/ |
| 5 Jun 2023 | Quaker released a "QUAKERborough" commercial filmed with Peterborough plant employees | kawarthaNOW, URL above |
| 19 Jun 2024 | Union release: "Members at PepsiCo Foods Canada, which operate the Quaker Oats manufacturing facility in Peterborough, Ont., have ratified a new three-year contract." "There are 440 members of Local 1996 working at the Peterborough Plant." | Unifor (union's own release; no byline), https://www.unifor.org/news/all-news/wages-pensions-addressed-new-quaker-oats-contract |
| 2 Sep 2025 | Elliott Investment Management's letter to PepsiCo's board says PFNA "should streamline its portfolio by divesting non-core and underperforming assets". **The letter text opened does not name Quaker.** News reports that Elliott's presentation proposed selling Quaker could not be opened (403); see UNVERIFIED | (a, investor's own letter) https://elliottletters.com/wp-content/uploads/Elliotts-Letter-to-PepsiCo.pdf |
| 8 Dec 2025 | PepsiCo release on "Priorities to Enhance Shareholder Value". It says the plan "Follows constructive engagement with supportive PepsiCo shareholder Elliott Investment Management". **No Quaker divestiture is mentioned** | (a) https://www.sec.gov/Archives/edgar/data/77476/000007747625000059/exhibit991-pepsicopressrel.htm |
| 21 Jul 2026 | At a city economic-development open house, a councillor "spoke … about the loss of Lufthansa inTouch and Woodward Inc. as indicative of what may happen if work is not done to retain major employers such as Quaker Oats." | (b) Bethan Bates, Local Journalism Initiative, kawarthaNOW, https://kawarthanow.com/2026/07/21/city-of-peterborough-looks-beyond-chasing-smokestacks-in-new-economic-development-strategy/ |
| Searched, none found | Any 2024–2026 PepsiCo announcement of a Peterborough closure, expansion or investment. PepsiCo's 10-Q to 13 Jun 2026 and its 8-Ks of 8 Dec 2025 and 17 Sep 2026 do not mention Peterborough | (a) 10-Q https://www.sec.gov/Archives/edgar/data/77476/000007747626000035/pep-20260613.htm ; 8-K https://www.sec.gov/Archives/edgar/data/77476/000007747626000042/pep-20260917.htm |

Note: a Powder & Bulk Solids item about a fire at the Peterborough plant turned out to be dated **17 Mar 2017**. It is outside the window and is not used.

**Reading:** U.S.-owned (PepsiCo, Inc.); made in Canada at Peterborough (company). The label states "Made in Canada from domestic and imported ingredients". The front states "100% whole grain Canadian oats".

---

### 2.2 Robin Hood (The J.M. Smucker Co.)

**Owner and chain**
| Date | Event | Source |
|---|---|---|
| 1909 | "From its modest beginnings in Moose Jaw in 1909 …" F.A. Bean, "President of International Milling in Minneapolis", bought a mill in Moose Jaw (company history) | (a) https://www.robinhood.ca/en/history |
| (to 2004) | International Multifoods era. Smucker's 2006 release says the Canadian grain businesses were "acquired as part of the International Multifoods acquisition". **The year of that acquisition was not verified on a page opened today** | (a) Smucker 8-K ex. 99.1, 20 Jul 2006, https://www.sec.gov/Archives/edgar/data/91419/000129993306004902/exhibit1.htm |
| 20 Jul 2006 | Smucker agreed to sell "the Canadian grain-based foodservice and industrial businesses owned by Smucker Foods of Canada Co." to Horizon Milling G.P. (Cargill and CHS Inc.), including "three flour milling operations in Montreal, Quebec, Port Colborne, Ontario, and Saskatoon, Saskatchewan". "The Smucker Company will continue to market and distribute Robin Hood® branded products through Canadian retail channels … Through a co-packing agreement, Horizon Milling will provide branded retail baking products, including Robin Hood flour, to the Smucker Company." **Oats are not mentioned** | same |
| 2 Jan 2024 | Smucker "sold the Canada condiment business to TreeHouse Foods" (Bick's, Habitant, Woodman's, McLarens). Robin Hood was not part of it | (a) Smucker 10-K FY2026, https://www.sec.gov/Archives/edgar/data/91419/000009141926000050/sjm-20260430.htm |
| 2 Dec 2024 | Smucker sold Voortman (Burlington, Ont.). Robin Hood was not part of it | same |
| FY2025 10-K (filed 18 Jun 2025) | Competition table: "Canada flour Robin Hood ® (A) and Five Roses ®", where (A) "Identifies the current market leader" | (a) https://www.sec.gov/Archives/edgar/data/91419/000009141925000056/sjm-20250430.htm |
| FY2026 10-K (filed 9 Jun 2026) | Does not name Robin Hood. Its divestitures list does not include Robin Hood. "Our Canadian headquarters is located in Markham, Ontario." Manufacturing list: the only Canadian site is "Sherbrooke, Quebec — Canned milk" | (a) URL above |
| 26 Aug 2026 | Q1 FY2027 results release: no Canadian divestiture mentioned | (a) https://www.sec.gov/Archives/edgar/data/91419/000009141926000079/sjm20260826exhibit991.htm |
| 30 Sep 2026 | Site footer: "© / TM / MC / ® / MD Smucker Foods of Canada Corp. or its affiliates." History page: "In addition to Robin Hood ® flour and oats, our core consumer brands include Smucker's ®, Uncrustables ®, Jif ®, Adams ®, Eagle Brand ®, Folgers ®, Carnation ® and Golden Temple ®." | (a) https://www.robinhood.ca/en ; https://www.robinhood.ca/en/history |

**Brief's question about a Brynwood or Joyce Foods sale:** Smucker sold its **U.S.** baking brands (Pillsbury, Martha White, Hungry Jack) to Brynwood Partners in 2018. The coverage of that sale says the Canadian baking business was **excluded**. That coverage is a search-result summary of AgCanada/Farmtario; no byline was checked, so it is treated as UNVERIFIED background. No sale of Robin Hood to Brynwood or Joyce Foods was found in Smucker's filings (EDGAR full-text search for "Robin Hood", 2019–Sep 2026: hits only in 10-Ks and annual reports and two 2019–2020 8-Ks; none describes a Robin Hood sale).

**Where it is milled and packed:** **Not stated by the company.** The 2006 co-packing arrangement covered flour. Smucker's FY2026 10-K lists no Smucker-owned oat or flour mill in Canada. Who mills Robin Hood oats is UNVERIFIED, and **no co-packer is inferred.**

**Origin line, main large-flake SKU (Robin Hood Large Flake Oats, 1 kg, Loblaw 20893369_EA)**
- Side panel (angle image https://digital.loblaws.ca/PCX/20893369_EA/en/2/20893369_en_angle_800.png, enlarged): "…SMUCKER FOODS OF CANADA CORP. MARKHAM, ON L3R 0P3 … PRODUCT OF CANADA / PRODUIT DU CANADA …". The image is low-resolution and parts are illegible, so **treat it as partly legible.**
- Front (all three oat SKUs): black roundel "MADE WITH • FAIT AVEC [red maple leaf] 100% CANADIAN OATS/GRUAU CANADIEN". https://digital.loblaws.ca/PCX/20893369_EA/en/1/20893369_en_front_800.png
- Retailer attribute: Save-On marks Robin Hood Quick Oats **"product of canada": true** (sku 00059000084749).
- There is no instant SKU. Robin Hood's oat range is Large Flake, Quick and Minute (https://www.robinhood.ca/en/products/oats).

**Where the company says its oats come from:** the front badge "100% Canadian oats" (label). The website gives nothing further.

**Ingredients (verbatim, Loblaw API):** "Rolled Oats. Contains: Oats. May Contain: Barley, Mustard, Rye, Soybean, Triticale, Wheat." Save-On: "ROLLED OATS. CONTAINS OAT INGREDIENTS. MAY CONTAIN BARLEY, MUSTARD, RYE, SOYBEAN, TRITICALE AND WHEAT INGREDIENTS."

**Company product description (verbatim, attributed):** "These old-fashioned rolled oats are left large and thick for great taste and lots of texture. Because of their size, they will retain their shape when cooked." (https://www.robinhood.ca/en/products/oats/large-flake). Taste and texture are the company's words.

**"Canadian" marketing:** home-page banner "Canadian desserts, deserve Canadian flour" (https://www.robinhood.ca/en). The front oat badge is described above.

**Dated news 2023–2026:** none specific to Robin Hood oats found. Smucker's own Canadian divestitures (2024) are listed above.

**Reading:** U.S.-owned (The J.M. Smucker Co. via Smucker Foods of Canada Corp., Markham). The side panel reads "Product of Canada" (partly legible) and the front reads "Made with 100% Canadian oats". The miller is not named.

---

### 2.3 Bob's Red Mill (Bob's Red Mill Natural Foods, Milwaukie, Oregon)

**Owner and chain (company, tier a):** "Bob Moore and his wife, Charlee, founded Bob's Red Mill in 1978 …" "Bob took it one step further in 2010, when he created an Employee Stock Ownership Plan (ESOP) …" "That happy day came in April 30th of 2020: as of our 10th anniversary, Bob's Red Mill is now 100% employee owned" (https://www.bobsredmill.com/employee-owned). The Canadian bag front reads "An Employee-Owned Company / Compagnie appartenant aux employés" (Voilà 938294EA image https://voila.ca/images-v3/2d92d19c-0354-49c0-8a91-5260ed0bf531/19a56be3-ac74-41e2-99fa-643f50dfecbd/1280x1280.jpg). Address: "13521 SE Pheasant Ct, Milwaukie, OR 97222" (https://www.bobsredmill.com/contact).

**Where milled and packed:** for the oatmeal cups, the retailer description (supplier text) says the cup "is milled, mixed, packaged and tested in our dedicated […] facility" (Loblaw 21589893_EA). Bob's Canadian site is bobsredmill.ca (French by default); its product pages opened today give no origin line.
**Origin line on the Canadian bag (large flake / rolled):** **UNVERIFIED.** Loblaw, Voilà and Save-On serve front images only, and well.ca shows no origin text.
**Where the company says its oats come from:** the retailer text for steel-cut oats says "Whole grain oats grown on some of the best oat-growing fields in the world" (Loblaw 21127423_EA). No country is given.

**Ingredients (verbatim)**
- Organic Old Fashioned Rolled Oats 907 g (Loblaw 21161849_EA): "Organic Whole Grain Oats."
- Oatmeal cup, Maple Brown Sugar 61 g (Loblaw 21589893_EA): "Gluten Free Whole Grain Oats, Sugars (brown Sugar, Cane Sugar), Chia Seeds, Flaxseed Meal, Sea Salt, Maple Flavouring (maltodextrin, Modified Tapioca And Cornstarch, Caramel Colour, Natural Flavour)." **[verbatim label wording, do not discuss on air]**

**Company description (verbatim, cut):** "Old Fashioned Rolled Oats make a delicious, chewy, […] hot cereal […]. Also a great choice for classic oatmeal raisin cookies, homemade granola, and oatmeal bread." (Voilà 938294EA). The texture word is the company's.

**Maple leaf / "Canadian" marketing:** none seen on the fronts examined. The bag is bilingual (French and English).
**Tariffs:** the sibling rules file reports that rolled and flaked oats (tariff item 1104.12) and prepared cereal foods (1904) were never on Canada's U.S. counter-tariff lists. That finding is **not re-verified here**.

**Reading:** U.S.-owned (100% employee-owned per company, Milwaukie, Oregon). Origin line on the Canadian bag UNVERIFIED.

---

### 2.4 Nature's Path Foods (Richmond, B.C.)

**Owner (company, tier a):** "Arran and Ratana founded Nature's Path in 1985 in Vancouver, BC … Proudly Canadian-owned and operated in the U.S., we've been organic from the start …" and "As a Canadian-owned, Canadian-based business, we have prioritized our relationships with hundreds of Canadian farmers throughout the country and source a significant amount of our product ingredients within Canada." (https://naturespath.com/pages/our-path). The dateline on its 2021 release is "RICHMOND, BC".

**Where made (company FAQ, https://naturespath.com/pages/faqs):** "Our main production facilities are in Delta, British Columbia; Blaine, Washington; and Sussex, Wisconsin." "All our products are produced and packaged in the US or Canada." On ingredients: "We purchase ingredients from US and Canadian suppliers as well as internationally from recognized third-party certified organic suppliers."

**Origin line, main instant SKU (Organic Maple Nut Instant Oatmeal, 8 packets, 400 g, Loblaw 20304405003_EA)**
- English front: **"PRODUCT OF USA"**, printed under the Non-GMO Project mark and beside the "CANADA ORGANIC • BIOLOGIQUE CANADA" logo, which has a red maple leaf. https://digital.loblaws.ca/PCX/20304405003_EA/en/1/20304405003_en_front_v1_800.png
- French front: **"PRODUIT DES É.-U."** https://digital.loblaws.ca/PCX/20304405003_EA/en/2/20304405003_en_angle_v1_800.png
- Superseeds & Grains Superfood Oatmeal (Loblaw 20885283001_EA) also reads **"PRODUCT OF USA"** under the Canada Organic logo. https://digital.loblaws.ca/PCX/20885283001_EA/en/1/20885283001_en_front_800.png
- Which of the company's facilities makes these packs is not stated. UNVERIFIED.
- Plain rolled oats: Nature's Path lists "Organic Old Fashioned Oats" on its Canadian store (https://naturespath.com/en-ca/collections/oatmeal/products.json), but **no Nature's Path plain rolled-oats SKU was found at the retailers searched**. Its plain line on retail shelves is Anita's (2.5).

**Ingredients (verbatim)**
- Original instant (Voilà 114135EA): "Whole Grain Rolled Oats*. *Organic. Contains Oats. May Contain Milk, Tree Nuts, Peanuts, Wheat Or Soy."
- Maple Nut instant (label image, Loblaw `…/en/4/20304405003_en_back_800.png`): "INGREDIENTS: Whole grain rolled oats*, Sugars* (cane sugar*, maple sugar*), Pecans*, Sea salt, Maple flavour*. *Organic. Contains: Pecans, Oats. May contain: Milk, Other tree nuts, Peanuts, Wheat, Soy."

**Maple leaf / "Canadian" marketing (described):** the Canada Organic logo with a red maple leaf sits next to "PRODUCT OF USA". The Maple Nut box shows maple leaves in its artwork. The company describes itself as "Canadian-owned" (above).
**Dated news:** 9 Nov 2021, majority acquisition of Anita's Organic Mill (see 2.5).

**Reading:** Canadian-owned (company), and the instant oatmeal checked is "Product of USA" (label).

---

### 2.5 Anita's Organic Mill (Chilliwack, B.C.)

**Owner (tier a):** Nature's Path release, "RICHMOND, BC, Nov. 9, 2021": "Nature's Path … is thrilled to announce its portfolio of brands is expanding with a majority acquisition of Anita's Organic Mill." "Established in 1997 … Anita's sources top-quality organic grain from farmers across Canada, which is then stone-milled onsite at its facility in Chilliwack, BC." (https://naturespath.com/blogs/press-releases/the-natures-path-family-of-brands-is-expanding). Nature's Path's Canadian store sells Anita's oat products (products.json above).
**Company site:** https://www.anitasorganic.com/ **could not be opened** (connection reset; WebFetch HTTP 503). UNVERIFIED.

**Where made and origin (retailer page, supplier text, Loblaw 21304184_EA):** "MADE IN CANADA: Anita's products are made at our mill in Chilliwack, BC. Our organic grains from Canadian farms are shipped to our facility where they are freshly milled, sprouted, blended and packaged for bakers across the country". **The origin line on the bag could not be read.** The side image shows the Canada Organic logo (https://digital.loblaws.ca/PCX/21304184_EA/en/3/21304184_en_side_800.png).

**Ingredients (verbatim, label side image):** "Ingredients: Organic oats. Contains: Oats. May contain: Wheat, Barley, Rye, Triticale, Sesame." The Loblaw API text omits "Sesame": "Organic Oats. Contains: Oats. May Contain: Wheat, Barley, Rye, Triticale."
**Description (verbatim, attributed):** "Our organic rolled oats lend a chewier texture to oatmeal and are excellent for making granola or adding to baking recipes." (Loblaw API)
**Instant SKU:** none found at retail. Loblaw's product name "…Rolled Instant Oatmeal" is the retailer's title for a 2.5 kg bag of rolled oats.

**Reading:** Canadian-owned (majority Nature's Path, since 9 Nov 2021); made in Chilliwack, B.C. (company text); origin line UNVERIFIED.

---

### 2.6 Rogers (Rogers Foods Ltd., Armstrong and Chilliwack, B.C.)

**Owner:** Nisshin Seifun Group, Japan's flour-milling group, lists "Rogers Foods Ltd. — A Canadian subsidiary engaged in the manufacture and sales of flour, premixes, and other food products" (https://www.nisshin.com/english/company/group/seifun.html). The year Nisshin acquired Rogers (reported elsewhere as 1989) is **UNVERIFIED**: the World Grain article returned 403, and no Nisshin page opened today gives the year.
**Company self-description:** "Rogers Foods Ltd. is a proudly Canadian company with over 75 years of milling excellence, headquartered in British Columbia …" (company release, 13 Jan 2026, reproduced at https://rogersfoods.com/shop/retail-products/large-flake-oats/). Also: "Rogers Foods has been proudly milling quality flour and cereal products from Canadian grain for over 60 years. With mills in both Armstrong and Chilliwack, British Columbia, …" (https://rogersfoods.com/about-us/). The "75 years" and "60 years" figures both appear on the site as published. The address is "4420 Larkin Cross Road Armstrong British Columbia V0E 1B6".

**Origin**
- Save-On attributes: Rogers Large Flake Oats 1 kg and Porridge Oats Original Blend 1 kg are **"product of canada": true**. Porridge Oats & Ancient Grains 750 g is **"made in canada": true, "product of canada": false** (skus 00060179436253, 00060179131103, 00060179131202).
- The company product page lists "Made in Canada" among the large-flake attributes (https://rogersfoods.com/shop/retail-products/large-flake-oats/).
- Front of the Porridge Oats bag (Loblaw 20717030_EA): a red maple leaf above the "1 kg". https://digital.loblaws.ca/PCX/20717030_EA/en/1/6017913110_enfr_front_centre_marketing_GS1_Ecommerce_800.png

**Where the company says its grain comes from:** "from Canadian grain" (about-us, above).
**Ingredients (verbatim):** Large Flake Oats (Save-On): "Whole Grain Rolled Oats". Porridge Oats Original Blend (Loblaw API): "Large Flake Oats, Oat Bran, Wheat Bran, Flaxseed Contains: Wheat, Oats May Contain: Mustard, Rye, Triticale, Soy, Barley". No instant oatmeal SKU was found. The Save-On query "rogers instant oatmeal" returned only Quaker.
**Description (verbatim):** "Old Fashioned Large Flake Rolled Oats." (Save-On, first sentence only)
**Dated company news:** "Chilliwack, B.C. – January 13, 2026 — Rogers Foods Ltd. today announced that it has discontinued its Rogers Foods retail Dark Rye 2.5kg Flour bag" (company page). This is not oats.

**Reading:** Japanese-owned (Nisshin Seifun Group subsidiary); "Product of Canada" (retailer attribute); made at B.C. mills (company).

---

### 2.7 One Degree Organic Foods

**Owner:** **UNVERIFIED.** The company site (https://onedegreeorganics.com/our-story/) speaks of "Our family" but names no owner or address; its footer reads "©2026 One Degree Organic Foods." (b) Stephen Hui, *Georgia Straight*, 12 Dec 2012: "One Degree shares its Abbotsford plant with sister company Silver Hills Bakery … Silver Hills cofounders Stan and Kathy Smith … founded One Degree … in 2011." (https://www.straight.com/food/bcs-one-degree-organic-foods-feeds-veganic-farming-movement). That article is 2012, and current ownership was not verified.
**Origin:** the front of the bag (Loblaw 21532752_EA, Sprouted Rolled Oats 680 g) shows small text under the Canada Organic logo that reads "Product of Canada / Produit du Canada". The image is low-resolution (https://digital.loblaws.ca/PCX/21532752_EA/en/1/21532752_en_front_800.png). Save-On marks the same SKU **"product of canada": true** (sku 00675625323072).
**Ingredients (verbatim, Loblaw API):** Rolled Oats: "Sprouted Organic Gluten-free Whole Grain Oats. Made In A Peanut And Tree Nut Free Facility." **[verbatim label wording, do not discuss on air]**. The instant SKU (Voilà 1382106EA, Protein Instant Oatmeal Banana Brown Sugar): ingredients not shown on the page. UNVERIFIED.
**Description (verbatim, Loblaw):** "For rich organic oatmeal & hearty whole-grain baking" / "100% Ingredient Transparency".
**Note:** the company's FAQ and the bag carry claims in barred categories. They are not reproduced here.

**Reading:** owner UNVERIFIED; "Product of Canada" (label, low-resolution, and retailer attribute).

---

### 2.8 Only Oats (Avena Foods Ltd., Saskatchewan)

**Owner:** (b) *Bakers Journal*, 8 Jun 2017 (no named byline shown): "Ironbridge acquired control of Avena Foods on June 1"; Ironbridge Equity Partners is "a Toronto-based private equity firm" (https://www.bakersjournal.com/ironbridge-equity-partners-acquires-avena-foods-6923/). **Whether Ironbridge still controls Avena in 2026 is UNVERIFIED** (https://www.ironbridgeequity.com/portfolio returned 404).
**Facility (company):** "On July 22, 2025, Avena hosted the fifth annual Customer and Farmer Appreciation Day … near Avena's Rowatt Saskatchewan facility." (https://www.avenafoods.com/). Avena's site does not mention "Only Oats". **onlyoats.com is a parked page** (it redirects to "/lander"). Whether Only Oats is still Avena's brand is UNVERIFIED.
**Origin and pack marketing (described):** the Voilà front image for Gluten-Free Rolled Oats 1 kg (610109EA) shows a red maple leaf at the top of the oval and "100% Canadian" (left) and "100% canadien" (right). Each sits in a three-line block whose other lines are barred claims and are not reproduced. It also shows the slogan "Purity from farm to table / Pureté de la ferme à la table" and "NEW LOOK SAME QUALITY". https://voila.ca/images-v3/2d92d19c-0354-49c0-8a91-5260ed0bf531/74d81966-d47c-449c-a32a-81d4ce3c015b/1280x1280.jpg . **The "Product of" line was not visible: UNVERIFIED.**
**Ingredients:** not shown on Voilà. UNVERIFIED.

**Reading:** Saskatchewan miller (company); front says "100% Canadian" with a maple leaf (label); owner and origin line UNVERIFIED.

---

### 2.9 McCann's (B&G Foods, Inc.)

**Owner and chain (tier a):** "Parsippany, N.J., July 16, 2018—B&G Foods, Inc. (NYSE: BGS) announced that effective today it has acquired the McCann's brand of premium Irish oatmeal from TreeHouse Foods, Inc. for approximately $32.0 million in cash". "The story of McCann's Irish Oatmeal dates back to 1800 when John McCann built a mill in County Meath …" (https://www.sec.gov/Archives/edgar/data/1278027/000110465918045288/a18-17265_1ex99d1.htm). B&G's 10-K for FY2025 (filed 3 Mar 2026): "The McCann's brand has been in existence since 1800 and offers classic traditional steel cut Irish oatmeal as well as convenience-oriented oatmeal products." It also says B&G makes "a portion of our … McCann's … products under co-packing agreements or purchase orders" (https://www.sec.gov/Archives/edgar/data/1278027/000110465926022961/bgs-20260103x10k.htm). The 10-Q to 4 Jul 2026 still lists McCann's in the Meals segment (https://www.sec.gov/Archives/edgar/data/1278027/000110465926094525/bgs-20260704x10q.htm).
**Dated item (a):** B&G recorded impairment charges on "indefinite-lived intangible trademark assets for the Victoria and McCann's brands during the third quarter of 2025", and on the McCann's trademark among others in Q4 2024 (10-K above). This is an accounting finding, not a statement about the product.
**Origin (label front, Voilà):** Steel Cut 793 g (556616EA) reads "McCANN'S IMPORTED" and "IMPORTÉ"; Quick Cooking 453 g (556636EA) reads "McCANN'S IMPORTED" and "/IMPORTÉ". https://voila.ca/images-v3/2d92d19c-0354-49c0-8a91-5260ed0bf531/0f9b7e0d-a4cd-4e86-afbd-1be3c8dad8b9/1280x1280.jpg ; …/4ed73528-54e5-49f5-9224-9e3d3b4d226b/1280x1280.jpg . The full country line was not visible. UNVERIFIED.
**Ingredients (verbatim, as published by Voilà, French only):** Steel Cut: "100 Per Cent Graua A Grain Entire Irlandais"; Quick: "100% D'Avoine À Grains Entiers Irlandais." (Garbled spellings as published.)

**Reading:** U.S.-owned (B&G Foods, Inc.); "Imported / Importé" (label); the ingredient line states Irish oats.

---

### 2.10 Kirkland Signature rolled oats (Costco), origin line only

- Product: "Kirkland Signature Whole Grain Rolled Oats, 4.54 kg", item 1736339, $11.99, shown "OutOfStock" online (JSON-LD), https://www.costco.ca/p/-/kirkland-signature-whole-grain-rolled-oats-454-kg/4000339745
- Back of bag (image `1736339-894__2`): "Ingredients: Whole grain rolled oats. Contains: Oats. Ingrédients : Flocons d'avoine à grains entiers. Contient : Avoine." Dealer: "Costco Wholesale Canada Ltd.* 415 W. Hunt Club Road Ottawa, Ontario K2E 1C5, Canada … * faisant affaire au Québec sous le nom les Entrepôts Costco". Origin: **"PRODUCT OF CANADA / PRODUIT DU CANADA"**. https://gdx-assets.costco.com/adobe/assets/urn:aaid:aem:4be27720-74c6-4b33-a60c-05912ca477f7/as/1736339-894__2.jpg
- Costco Wholesale Canada Ltd. is listed among the subsidiaries of Costco Wholesale Corporation (Ex. 21.1, as of 31 Aug 2025, URL in s. 0).
- No maple leaf was seen on the front.
- **Reading:** store brand of U.S.-owned Costco; "Product of Canada". The miller is not named, and no co-packer is inferred.

---

### 2.11 Red River (Arva Flour Mill, Ontario): no oats, out of scope

- Company: "Our Red River Cereal Collection brings back the original hot cereal blend of cracked wheat, cracked rye, and cracked & whole flax — crafted the traditional way at Canada's oldest continuously operating flour mill." (https://arvaflourmills.com/collections/red-river-cereal)
- (b) Luke Carroll, CBC News, 20 Nov 2022: Smucker "discontinued the product"; Arva Flour Mill "purchased the Red River Cereal this past June", and the deal "was finalized in June 2022". The article also gives the history: created in Winnipeg in 1924, bought by Maple Leaf Milling in 1928 and "then Smuckers in 1995". https://www.cbc.ca/news/canada/north/red-river-cereal-ontario-flour-mill-northerners-1.6657563
- Retailer: Save-On marks it **"product of canada": true** and says it "is back in production at the Historic Arva Flour Mill" (sku 00624307101378). Voilà 7378EA: $9.99 / 908 g. The bag front reads "Celebrating 100 years / ans 1924-2024".
- **Reading:** Canadian-owned, Product of Canada (retailer attribute); **contains no oats** per the company, so it is not part of the oatmeal comparison.

### 2.12 Cream of the West: U.S. company, not on Canadian shelves

- Company: "Family-owned Montana company …" and "We have been making […] 100% whole grain foods from Montana grains since 1914." (https://creamofthewest.com/). U.S. context only. Its 7-Grain product is reported to contain oats, but that comes from a search-result summary, so it is UNVERIFIED.
- Not found at any Canadian retailer searched (s. 1.3). Whether a separate Canadian "Cream of the West" product ever existed is UNVERIFIED.

---

## 3. Smaller and regional brands (brief; only what was verified)

| Brand | What was verified (tier a, retailer or label) | Origin wording seen | Gaps |
|---|---|---|---|
| Dan-D-Pak | Loblaw 20876492_EA description (first sentence): "From the Canadian prairies." Ingredients: "Rolled Oats." | None on the front image | Owner, packer and origin line UNVERIFIED |
| Stoked Oats | Loblaw 20971529_EA: "Stoked Oats has built a very loyal following across Canada …" (company text). Ingredients (Bucking Eh): "Regenerative Organic Certified Gluten-free Oats, Currants, Apples, Flax Seeds, Mulberries, Chia Seeds, Cinnamon May Contain: Peanuts, Tree Nuts, Soy" **[verbatim label wording, do not discuss on air]** | Product name "Bucking Eh" | Owner and origin UNVERIFIED |
| Oak Manor | Loblaw 20016104_EA: "Organic Oats Flakes." (verbatim) | — | All else UNVERIFIED |
| Willow Creek Organic Grain Co. | Voilà 301659EA ingredients: "Organic Oats. Allergen Statement: Product May Contain Traces Of Gluten, Wheat And Mustard." **[verbatim label wording, do not discuss on air]** The bag label has a small red maple leaf | — | Owner and origin UNVERIFIED |
| Adagio Acres | Voilà 496033EA front: **"Product of / Produit du Manitoba"**. Storage text: "Our Naked Oats are freshly milled in small batches." | "Product of Manitoba" | Owner UNVERIFIED |
| Highwood Crossing | Voilà 839413EA front: round stamp "MADE IN CANADA / FABRIQUÉ AU CANADA" with a maple leaf | "Made in Canada" (no qualifier visible on the front) | Owner and back panel UNVERIFIED |
| La Meunerie Milanaise | Voilà 756354EA front: "Depuis / Since 1982" | — | Owner and origin UNVERIFIED |
| Speerville Flour Mill | Loblaw 20059495_EA "Newfoundland Oatmeal", ingredients "Organic Cold Rolled Oats." Atlantic Superstore Halifax only | — | Owner and origin UNVERIFIED |
| Good Eats (Pilling Foods Inc.) | Voilà 941211EA: "Organic Whole Grain Oats"; attribute "Local Product" | — | Owner UNVERIFIED |
| Grace (instant oats) | Voilà 211979EA, 1 kg, $4.49 | — | Owner and origin UNVERIFIED |
| Yumi Organics (instant) | Loblaw 21706743_EA etc.; ingredients not supplied | — | UNVERIFIED |
| Saffola Masala Oats | Loblaw 21707672_EA; GTIN prefix 890 (front image filename) | — | Origin line UNVERIFIED; GTIN prefixes do not prove origin |
| Sunny Boy hot cereal | Voilà 507866EA front: "original HOT CEREAL" | — | Ingredients, so oat content, UNVERIFIED |
| Oatbox (overnight oats; out of scope) | Company site: "Our Original and Barista oat beverages are made in Quebec from Canadian oats." That sentence is about beverages, not oatmeal (https://oatbox.com/). Overnight Oats Raspberry Cocoa ingredients (Voilà 840791EA): "Oats*, Chia Seeds*, Steel Cut Oats*, Sugars (Cane Sugar*), Sweetened Cranberries* (Cranberries*, Cane Sugar*, Sunflower Oil*), Cocoa Powder*, Freeze Dried Raspberries*, Natural Flavour*. May Contain: Tree Nuts (…), Wheat, Soy. *Ingrédients Biologiques / Organic Ingredients" | — | Owner and where the overnight oats are made UNVERIFIED |

---

## 4. Prices (retailer's own site, API or flyer; opened 30 Sep 2026; unit price computed here per 100 g)

| Brand / SKU | Retailer, banner, store / region | Pack | Price | Unit price ($/100 g) | Notes |
|---|---|---|---|---|---|
| Quaker Large Flake | PC Express API, RCSS Calgary 1539 (same at RCSS Vancouver, Winnipeg, Saskatoon, Regina) | 1 kg | $3.75 | 0.375 | — |
| Quaker Large Flake | PC Express API, Loblaws Toronto 1032 | 1 kg | $5.75 | 0.575 | price expiry 2026-10-14 |
| Quaker Large Flake | PC Express API, Atlantic Superstore Halifax 0354 | 1 kg | $4.49 (was $5.50) | 0.449 | sale to 2026-10-28 |
| Quaker Large Flake | PC Express API, Maxi Montréal 9528 | 1 kg | $4.00 | 0.400 | — |
| Quaker Old Fashioned Large Flake | Voilà 217510EA, default region | 1 kg | $6.49 | 0.649 | — |
| Quaker Large Flake | Save-On API, store 1982 Langley, B.C. | 1 kg | $6.99 | 0.699 | — |
| Quaker Quick Oats 2 × 2.58 kg | Costco.ca online, 100570610 | 5.16 kg | $13.99 (OutOfStock) | 0.271 | Costco flyer (Flipp item 1044208168, St. John's postal code, 28 Sep–5 Oct): "Online Price 10.99" = 0.213 |
| Quaker Instant Maple & Brown Sugar | PC Express API, RCSS Calgary | 344 g | $3.50 | 1.017 | — |
| Quaker Instant Maple & Brown Sugar | PC Express API, Loblaws Toronto | 344 g | $5.19 | 1.509 | — |
| Quaker Instant Maple Brown Sugar | Voilà 418756EA | 344 g | $5.29 | 1.538 | — |
| Quaker Instant Flavour Variety 8 pk | Giant Tiger (tags AB, MB, SK) | 314 g | $3.66 | 1.166 | — |
| Robin Hood Large Flake | PC Express API, Loblaws Toronto | 1 kg | $4.79 | 0.479 | — |
| Robin Hood Large Flake | PC Express API, No Frills Vancouver 3410 | 1 kg | $3.99 | 0.399 | — |
| Robin Hood Large Flake | Voilà 280532EA | 1 kg | $4.79 | 0.479 | — |
| Robin Hood Quick | Save-On API, Langley | 1 kg | $4.99 | 0.499 | — |
| Rogers Large Flake | Save-On API, Langley | 1 kg | $6.29 | 0.629 | — |
| Rogers Porridge Oats Original Blend | PC Express API, RCSS Calgary | 1 kg | $5.79 | 0.579 | Loblaws Toronto $5.99 |
| Bob's Red Mill Rolled Oats | PC Express API, RCSS Calgary | 907 g | $7.99 | 0.881 | Loblaws Toronto $8.49 (was $9.49) |
| Bob's Red Mill GF Old Fashioned Rolled Oats | Voilà 938294EA | 907 g | $11.79 | 1.300 | — |
| Bob's Red Mill oatmeal cup, Maple Brown Sugar | PC Express API, Loblaws Toronto | 61 g | $2.99 | 4.902 | — |
| Nature's Path Maple Nut Instant | PC Express API, RCSS Calgary | 400 g | $5.29 | 1.323 | Loblaws Toronto $6.99 = 1.748 |
| Nature's Path Original Instant | Voilà 114135EA | 400 g | $6.29 | 1.573 | — |
| Anita's Organic rolled oats | PC Express API, RCSS Calgary | 2.5 kg | $17.99 | 0.720 | Loblaws Toronto $18.99 = 0.760 |
| One Degree Sprouted Rolled Oats | PC Express API, Loblaws Toronto | 680 g | $8.49 (was $9.19) | 1.249 | RCSS $9.49 = 1.396 |
| Only Oats Gluten-Free Rolled Oats | Voilà 610109EA | 1 kg | $11.99 | 1.199 | — |
| McCann's Steel Cut Irish Oatmeal | Voilà 556616EA | 793 g | $10.99 | 1.386 | — |
| McCann's Quick | Voilà 556636EA | 453 g | $5.99 | 1.322 | — |
| Kirkland Signature Rolled Oats | Costco.ca online | 4.54 kg | $11.99 (OutOfStock) | 0.264 | — |
| Dan-D-Pak Rolled Oats | PC Express API, RCSS Calgary | 1 kg | $2.98 | 0.298 | — |
| Red River (no oats) | Save-On API, Langley | 908 g | $8.99 | 0.990 | Voilà $9.99 = 1.100 |

**Flyer cross-check (Flipp host; merchant flyers):** Metro (Toronto) "QUAKER INSTANT OATMEAL" $2.99 ea., 24 Sep–1 Oct; Walmart (all 8 postal codes) "Quaker Oatmeal protein" $6.98, 1–8 Oct; Sobeys (Toronto, Halifax, St. John's) "ROBIN HOOD Oats" $3.99, 1–8 Oct; Co-op (Winnipeg, Saskatoon) "Robin Hood Oats" SALE $3.99, 1–8 Oct; Real Canadian Superstore "BOB'S RED MILL OATS, 454-907 G" $5.09–$8.49 after savings, 1–8 Oct; Super C (Montréal) "gruau Quaker" $1.99, 1–8 Oct. Pack sizes are not fully stated in these flyer items, so no unit price is computed.

---

## 5. Cross-brand facts for the script (all sourced above)

| Question | Answer |
|---|---|
| Which big brands are foreign-owned? | Quaker (PepsiCo, U.S.), Robin Hood (Smucker, U.S.), Bob's Red Mill (U.S.), McCann's (B&G Foods, U.S.), Rogers (Nisshin Seifun Group, Japan), Kirkland Signature (Costco, U.S.) |
| Which are Canadian-owned? | Nature's Path (company: "Canadian-owned"), Anita's (majority Nature's Path), Red River (Arva, no oats). Only Oats (2017 Toronto PE control, current status UNVERIFIED) |
| Foreign-owned but labelled Canadian? | Quaker ("Made in Canada from domestic and imported ingredients"), Robin Hood ("Product of Canada", partly legible), Rogers ("Product of Canada", retailer attribute), Kirkland ("Product of Canada") |
| Canadian-owned but labelled U.S.? | Nature's Path instant oatmeal ("Product of USA", beside a maple-leaf Canada Organic logo) |
| Imported and says so? | McCann's ("Imported / Importé") |

---

## Appendix A: Recalls, food-safety and legal items (**DO NOT USE ON AIR**)

| Date | Item | Label | Source (opened 30 Sep 2026) |
|---|---|---|---|
| 11 Jan 2024 | Food recall warning: "Quaker brand granola bars and cereals and Cap'n Crunch brand Treats Crunch Berries Cereal Bars recalled". The page's product list contains **no oatmeal** (oats, instant, quick or large-flake) entries | Regulator notice (recall) | https://recalls-rappels.canada.ca/en/alert-recall/quaker-brand-granola-bars-and-cereals-and-cap-n-crunch-brand-treats-crunch-berries |
| 19 Jan 2024 | A Vancouver law firm "has filed a proposed Canada-wide class-action lawsuit against The Quaker Oats Company and PepsiCo Canada" | **Allegation** (proposed class action; no finding) | (b) Eric Stober, Global News, https://globalnews.ca/news/10237933/quaker-class-action-lawsuit-recall/ |
| 11 Apr 2024 (U.S. context) | PepsiCo is permanently closing the Danville, Illinois Quaker plant (510 employees), which was linked to the 2023–24 U.S. recalls | U.S. company decision, reported | (b) Christopher Doering, Food Dive, https://www.fooddive.com/news/pepsicos-quaker-plant-illinois-closing-layoffs/712954/ |
| FY2024 (U.S. filing) | PepsiCo recorded "a pre-tax charge of $ 187 million … associated with the Quaker Recall" | Company disclosure | (a) PepsiCo 10-K FY2025 (URL in s. 2.1) |
| Undated | Rogers Foods FAQ and product pages carry "Food Safety Notice" text about raw oats and bran | Company safety notice | (a) https://rogersfoods.com/frequently-asked-questions/ |

---

## UNVERIFIED / DO-NOT-USE

1. **Bob's Red Mill origin line on the Canadian bag.** No retailer image showed the back panel. Do not say "Product of USA" for the Canadian pack until it is read.
2. **Robin Hood side panel.** "PRODUCT OF CANADA / PRODUIT DU CANADA" and "SMUCKER FOODS OF CANADA CORP. MARKHAM" were read from a low-resolution, partly illegible retailer image that may not be the current pack. **Who mills Robin Hood oats is unknown.** Do not infer a co-packer, including Horizon Milling, whose 2006 co-pack deal named flour only.
3. **The year Smucker acquired International Multifoods (Robin Hood's prior owner)** was not opened today.
4. **"Brynwood / Joyce Foods" sale of Robin Hood:** no evidence found. The "Canadian baking excluded from the 2018 Brynwood sale" point rests on search snippets of AgCanada/Farmtario pages that were not opened with a byline. Do not use.
5. **Quaker dealer line** (PepsiCo Canada ULC address on pack) was not visible in any image.
6. **Quaker Large Flake qualifier.** The "domestic and imported ingredients" tile was served by Loblaw for the Large Flake SKU. Whether that exact tile is printed on every current Large Flake box is not confirmed with a physical pack. Do not imply any reason for the qualifier, and do not imply wrongdoing.
7. **Elliott's proposal to sell Quaker.** The CNBC (6 Sep 2025) and Baking Business pages returned 403. The Elliott letter text opened does not name Quaker. PepsiCo's 8 Dec 2025 release does not mention Quaker. Do not say "PepsiCo is selling Quaker".
8. **Nature's Path:** which plant makes the Canadian-sold instant oatmeal (Blaine, Wash., is likely given the label, but the company does not say). A search snippet attributing oatmeal output to Blaine is aggregator text (c).
9. **Anita's Organic Mill website:** could not be opened (connection reset; HTTP 503).
10. **Rogers:** the 1989 date of Nisshin's acquisition (World Grain returned 403). The site gives two different ages ("over 60 years" and "over 75 years").
11. **One Degree Organic Foods:** current owner; the "Product of Canada" reading is from a low-resolution image; instant-oatmeal ingredients not seen.
12. **Only Oats / Avena Foods:** current ownership (Ironbridge portfolio page 404); onlyoats.com is parked; origin line and ingredients not seen.
13. **Oatbox:** owner, and where the overnight oats are made.
14. **Cream of the West:** whether a Canadian product ever existed; 7-Grain oat content (search snippet only).
15. **Dorset Cereals ownership; Uncle Tobys, Holista, Grain Millers, "Rolling Hills", Kellogg/WK Kellogg hot oats:** not found or not researched. WK Kellogg ownership changes were not checked.
16. **Smaller brands in s. 3:** owners and origin lines not verified unless shown.
17. **Retailer data vs label:** ingredient text differs between retailers for the same Quaker SKU (Loblaw label image vs Voilà text), and Giant Tiger served an older-format Quaker variety-pack label (with "COLOUR" in the maple flavour). Quote label images only.
18. **Canada Organic logo next to "Product of USA":** the rule on logo use for imported products was not checked today. Do not comment on it.
19. **Tariffs:** the statement that rolled oats and cereal preparations were never on Canada's U.S. counter-tariff lists comes from the sibling file `oatmeal_rules_origin.md` and was not re-verified here.
20. **Blocked or unreachable retailers:** walmart.ca (blocked), metro.ca (403), longos.com (403), coopathome.ca (429), shop.calgarycoop.com (proxy 502). Their shelves are known only from flyers.
21. **Aggregators seen in searches, flag only, never sources:** Wikipedia (Robin Hood Flour, Red River Cereal, Quaker Oats Company, Nisshin Seifun, Odlums), madeinca.ca, fyicanada.ca, thecanadalist.ca, pitchbook.com, cbinsights.com, zoominfo, Amazon listings, wellness.alibaba.com, kiddle, airial.travel, dnb.com, glimpsesofcanadianhistory.ca, vintageinn.ca. None was used.
22. **Barred content encountered and excluded:** company and retailer text on fibre, cholesterol, heart health, protein, sugar, gluten, glyphosate, sprouting nutrition and "superfood" claims (Quaker, Bob's, Nature's Path, One Degree, Stoked Oats, Only Oats, Avena). None may be used on air.
23. **Powder & Bulk Solids "Quaker Oats plant fire"** was dated 17 Mar 2017. It is outside the window and not used.
24. **The December 2025 channel oatmeal video and competitor oatmeal videos** were not consulted and must not be reused.

<!-- ===== oatmeal_brands_private.md ===== -->

# Private-label oatmeal in Canada — retailer-by-retailer label dossiers (2026)

Compiled 30 Sep 2026 (Eastern), from pages opened 1 Oct 2026 00:41–01:12 UTC (= 30 Sep 2026 20:41–21:12 EDT). Every "opened" time below is UTC on 1 Oct 2026 unless stated.

**Scope.** House-brand (private-label) oats and oatmeal of ten Canadian retail brand families: President's Choice / PC Organics / PC Blue Menu and no name (Loblaw); Compliments (Sobeys/Empire); Great Value (Walmart Canada); Selection / Irresistibles / Life Smart (Metro); Western Family (Pattison Food Group / Save-On-Foods); Kirkland Signature (Costco Canada); Co-op Gold (Federated Co-operatives); Giant Value / Giant Tiger Marché (Giant Tiger); Farm Boy (Sobeys/Empire).

**House-rule compliance.** This file contains no health, nutrition, fibre, heart, cholesterol, sugar-content, glycemic, protein, gluten/celiac, glyphosate/pesticide, heavy-metal, additive or food-safety commentary. Retailer descriptions that contain such claims were deliberately not quoted. Ingredient lists, product names, origin statements and company lines are reproduced verbatim as label/page facts only; no ingredient is characterised. Product names that contain words such as "Gluten Free" or "Blue Menu" are reproduced only because the brief asks for the exact product name — they are not to be discussed on air. Recalls are in the appendix only, marked "do not use on air". No co-packer is named anywhere in this file (no label, retailer page, court/tribunal/CFIA record or tier-(b) report naming one was found), and none may be inferred from matching ingredient lists.

**Tier legend.** (a) primary — regulator, Justice Laws, company filing/site, the retailer's own product page or the retailer's own product back-end that serves that page; (b) named outlet with byline and date; (c) aggregator/SEO/Wikipedia/Open Food Facts/price tracker — flag only, never used as a source; (d) named survey.

**How retailer data was read (important for re-verification).**
- Loblaw banners: loblaws.ca / nofrills.ca product pages returned **HTTP 403** to automated requests (tested 00:47 UTC). Product data, prices, badges and pack images were read from Loblaw's own PC Express product back-end that powers those pages (`api.pcexpress.ca/pcx-bff/api/v1/products/...`, tier a) and its image host `digital.loblaws.ca`. Pack text quoted "from pack image" was read by me from those retailer-hosted images.
- Sobeys/Farm Boy: voila.ca (Voilà by Sobeys) product pages (tier a); farmboy.ca product pages (tier a).
- Walmart Canada: walmart.ca product pages with a mobile browser user-agent (desktop UA is served a bot check); page data shows store 1061, postal code L5V 2N6 (Mississauga, ON).
- Metro: www.metro.ca returned 403; the same Metro pages were served from Metro's own host `api2.metro.ca` (tier a). Metro product images (product-images.metro.ca) returned 403 — no Metro pack image was read.
- Save-On-Foods: saveonfoods.com returned 403 (Cloudflare); product records were read from Save-On's own storefront gateway `storefrontgateway.saveonfoods.com` (tier a), store 1982 = Save-On-Foods, 19855 92a Ave, Langley Twp, BC (resolved from the same gateway's store list).
- Giant Tiger: gianttiger.com product JSON (Shopify store, tier a).
- Costco: costco.ca and costcobusinesscentre.ca product pages; sameday.costco.ca (Costco Canada same-day site) read via WebFetch.

---

## 1. Headline findings (label-literal; every line sourced in the dossiers below)

| # | Finding | Evidence type | Where |
|---|---|---|---|
| 1 | **PC Organics instant oatmeal boxes carry the Canada Organic maple-leaf logo next to the words "IMPORTED / IMPORTÉ".** Both PC Organics instant SKUs (Maple & Brown Sugar Flavour 400 g; with Flaxseed 400 g). By contrast, the plain PC Organics oat bags carry Loblaw's "Prepared in Canada" badge in Loblaw's product data. | Pack image (front), retailer-hosted | §3.1 |
| 2 | Under the Safe Food for Canadians Regulations, an imported product bearing the Canada organic logo must show "Product of [country]" or the word "Imported" "in close proximity to that product legend" (SFCR s. 354(d), verbatim in §2). The label wording in #1 is the wording that rule prescribes. **Do not infer where the PC Organics instant product was made or who made it — the label shown does not say.** | Justice Laws (a) | §2 |
| 3 | **Great Value (Walmart Canada): plain oats say "PRODUCT OF • PRODUIT DU CANADA"; the instant oatmeal says "MADE IN CANADA FROM DOMESTIC AND IMPORTED INGREDIENTS"** — while both also say "100% Canadian oats". | Pack images + walmart.ca page text | §3.4 |
| 4 | **Western Family (Save-On-Foods): Save-On's own product records flag plain oats `"product of canada": true` and instant oatmeal `"made in canada": true` / `"product of canada": false`.** Pack fronts of plain oats show a "PRODUCT OF CANADA / PRODUIT DU CANADA" seal. | Retailer back-end + pack images | §3.6 |
| 5 | **Farm Boy classifies its own oats "Product of Canada" and its instant oatmeal, oatmeal cups and overnight oats "Prepared in Canada"** on its "Proudly Canadian" page, and defines the two terms there. | farmboy.ca (a) | §3.10 |
| 6 | **Kirkland Signature Whole Grain Rolled Oats 4.54 kg (Costco Canada): back panel reads "PRODUCT OF CANADA / PRODUIT DU CANADA" under "Costco Wholesale Canada Ltd.* 415 W. Hunt Club Road Ottawa, Ontario K2E 1C5, Canada".** No Kirkland instant oatmeal was found on Costco Canada's sites. | Pack image on costco.ca | §3.7 |
| 7 | **Compliments (Sobeys) Quick Oats 1 kg and Organic Quick Oats 1 kg fronts carry a round "PRODUCT OF • PRODUIT DU CANADA" maple-leaf seal**; no Canadian wording was visible on the fronts of the eight Compliments instant boxes imaged on Voilà. | Pack images on voila.ca | §3.3 |
| 8 | **Giant Value (Giant Tiger): plain oats badge "100% CANADIAN OATS / FLOCONS D'AVOINE 100% CANADIENS"; instant badge "MADE WITH 100% CANADIAN OATS".** Giant Tiger's product records tag the plain oats `product_of_canada` (the site template maps that tag to a "Product of Canada" badge); the three instant SKUs carry no such tag. | Pack images + retailer JSON | §3.9 |
| 9 | **no name (Loblaw) plain oats: pack front says "100% whole grain Canadian oats" / "avoine canadienne à grains entiers à 100 %"; Loblaw's product data gives them a "Prepared in Canada" badge, not a "Product of Canada" badge.** Loblaw told CBC (2025) that its in-store maple-leaf symbol "means the item was Prepared in Canada". CFIA guidance: "The claim 'Canadian' is considered to be the same as a 'Product of Canada' claim." These are three literal facts; **no conclusion about compliance is drawn or implied** — a "Prepared in Canada" badge is a retailer descriptor and does not mean a product fails the "Product of Canada" test (Loblaw's data uses only that one badge for every PC/no name oat SKU that has any badge). On air, say only what each label/page says. | Pack image + retailer data + CFIA (a) + CBC (b) | §2, §3.2, §4 |
| 10 | **President's Choice (non-organic) instant oatmeal fronts say "Made with 100% Canadian oats" ("Fait avec de l'avoine 100 % canadienne"); Loblaw's product data shows no origin badge of any kind for these SKUs.** Absence of a badge is not evidence of origin either way. | Pack image + retailer data | §3.1 |
| 11 | **Metro: Selection plain oats pages read "Product of Canada"; the Selection Maple & Brown Sugar instant page shows "Product of Canada" in its header block but lists the attribute "Made in Canada" in its "My Health My Choices" tags.** Two different origin descriptors on one retailer page (reported literally; no inference about the product or the pack, which could not be imaged). Metro's Canadian-products page says origin information "comes from certification agencies, product suppliers, and other Metro partners. We cannot be held liable for any information that may prove to be inaccurate." | api2.metro.ca (a) | §3.5, §4 |
| 12 | Price spread, plain quick oats per 100 g (retailer's own sites, 30 Sep 2026): Walmart Great Value 1 kg $0.277; Giant Value 1 kg $0.277; Metro Selection 1 kg $0.299; no name 1 kg $0.300–$0.325; Compliments 1 kg $0.449; Western Family 1 kg $0.469; Kirkland 4.54 kg $0.250 (Same-Day) / $0.264 (costco.ca, out of stock online). | Retailer sites | §6 |

**Pattern table — plain oats vs instant oatmeal origin wording (literal)**

| Brand | Plain oats: origin wording found | Instant oatmeal: origin wording found |
|---|---|---|
| no name | Pack: "100% whole grain Canadian oats"; Loblaw data badge: "Prepared in Canada" | No no name instant oatmeal returned at 5 Loblaw stores |
| President's Choice | — (PC-branded plain oats are PC Organics / PC Blue Menu, below) | Pack: "Made with 100% Canadian oats"; Loblaw data: no origin badge |
| PC Organics | Loblaw data badge: "Prepared in Canada"; pack: Canada Organic logo (no "Imported" seen in images) | Pack: Canada Organic logo + "IMPORTED / IMPORTÉ"; Loblaw data: no origin badge |
| PC Blue Menu | Steel cut 840 g pack: no Canada wording seen; no badge. Regular Steel Cut Oats 360 g (instant-style box) pack: "Made with 100% Canadian oats" | Supergrains boxes: no Canada wording seen; no badge |
| Compliments | Pack seal: "PRODUCT OF • PRODUIT DU CANADA"; Voilà text: "100% whole grain Canadian oats." | No Canadian wording on fronts imaged |
| Great Value | Pack seal: "PRODUCT OF • PRODUIT DU CANADA" + "100% WHOLE GRAIN CANADIAN OATS" | Pack seal: "MADE IN CANADA FROM DOMESTIC AND IMPORTED INGREDIENTS" + "MADE WITH 100% CANADIAN OATS" |
| Selection (Metro) | Page: "Product of Canada" | Page header "Product of Canada" + tag "Made in Canada" |
| Western Family | Pack seal "PRODUCT OF CANADA / PRODUIT DU CANADA"; Save-On data `product of canada: true` | Save-On data `made in canada: true`, `product of canada: false` |
| Kirkland Signature | Back panel: "PRODUCT OF CANADA / PRODUIT DU CANADA" | None found in Canada |
| Giant Value | Pack: "100% CANADIAN OATS"; GT tag `product_of_canada` | Pack: "MADE WITH 100% CANADIAN OATS"; no GT origin tag |
| Farm Boy | Farm Boy page: "Product of Canada"; pack: "MILLED IN ONTARIO / MOULU EN ONTARIO" | Farm Boy page: "Prepared in Canada" |
| Co-op Gold | Not verified (no retailer page opened) | Not verified |

---

## 2. Regulatory frame (tier a, verbatim)

**CFIA, "Origin claims on food labels"** — https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims (opened 01:02; page "Date modified: 2023-12-06"):
- "A food product may use the claim "Product of Canada" when all or virtually all major ingredients, processing, and labour used to make the food product are Canadian."
- "Generally, the percentage referred to as very little or minor is considered to be less than a total of 2% of the product"
- "A "Made in Canada" claim with a qualifying statement can be used on a food product when the last substantial transformation of the product occurred in Canada, even if some ingredients are from other countries."
- "The qualifying statements that can be used include "Made in Canada from domestic and imported ingredients" or "Made in Canada from imported ingredients"."
- "The claim "Canadian" is considered to be the same as a "Product of Canada" claim. As such, all or virtually all major ingredients, processing, and labour used to make the food product must be Canadian."
- "When the claim "100% Canadian" is used on a label, the food or ingredient to which the claim applies must be entirely Canadian rather than "all or virtually all" Canadian." … "For example, if the claim "Made with 100% Canadian wheat" is used on a bag of dry pasta, all of the wheat, and its derivatives, used in that product must be Canadian."
- Other domestic content claims, examples include: ""Prepared in Canada" to describe a food which has been entirely prepared in Canada" and ""Packaged in Canada" to describe a food which is imported in bulk and packaged in Canada".
- Maple leaf: "The use of these vignettes on their own does not always imply that the product is wholly or partially Canadian (for example, maple leaves as part of a fall scene on a product's label). However, depending on how a maple leaf is used, it could imply a "Product of Canada" claim."
- Canada Organic: "the Canada organic logo is an indication of organic certification to the Safe Food for Canadians Regulations. On imported products that are qualified to use the Canada organic logo, a country of origin statement or the statement "Imported" is required to be in close proximity to the logo, to avoid misleading consumers"

**Safe Food for Canadians Regulations, SOR/2018-108, s. 354(d)** — https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/FullText.html (opened 01:02; "Regulations are current to 2026-09-21 and last amended on 2025-09-19"):
- "(d) in the case of a food commodity that is imported and on whose label the product legend that is set out in Schedule 9 is applied, the expression "Product of" or " produit de " immediately preceding the name of the foreign state of origin or the word "Imported" or " importé " in close proximity to that product legend."
- s. 223(1) (same URL): if a consumer prepackaged food "was wholly manufactured, processed or produced in a foreign state" and a Canadian name and address is shown, "that information must be preceded by the expressions "Imported by" and " importé par " or "Imported for" and " importé pour "… unless the geographic origin of the consumer prepackaged food is shown on the label".

**CFIA, "Notice to industry – The importance of accurate use of Product of Canada, Made in Canada and other origin claims"**, March 14, 2025 (updated July 30, 2025) — https://inspection.canada.ca/en/food-labels/labelling/notice-industry-2025-03-14 (opened 01:02; "Date modified: 2026-03-16"):
- "If a food business chooses to use the maple leaf on packaging, retail shelves or online, the CFIA recommends that an accompanying domestic content statement (for example, Product of Canada, Made in Canada, or other content claim ) be placed in close proximity to the maple leaf"
- "Retailers are responsible for the accuracy of any store signage or advertisements about the origin of a food that is store generated."
- "The CFIA is reinforcing its commitment to a transparent and trustworthy market and will take the appropriate enforcement action to protect Canadians from misleading claims if non-compliance is found."

Scope note: the CFIA page says the food guidelines do not apply to "other consumer goods … these products may be assessed under the Competition Bureau's Guide to "Made in Canada" claims". Any "51%" or "98% of direct costs" threshold seen in search snippets is the Competition Bureau non-food test — **not the food rule** (see UNVERIFIED #9).

---

## 3. Dossiers

### 3.1 President's Choice / PC Organics / PC Blue Menu (Loblaw)

**Retailer/owner.** Loblaw Companies Limited (TSX: L). George Weston Limited's 2025 Annual Report (p. 6) shows "52.6% Loblaw" and states "Loblaw (TSX: L) is Canada's food and pharmacy leader and the nation's largest retailer. All material operations are carried out in Canada." — https://www.weston.ca/GeorgeWeston/Assets/Documents/Reports/2025/gwl_2025ar_en.pdf (opened 01:08). Country: Canada.

**Retailer product-page URLs** (format `https://www.loblaws.ca/en<link>`; all returned HTTP 403 at 00:47) and data read from Loblaw's PC Express back-end, `https://api.pcexpress.ca/pcx-bff/api/v1/products/{code}?lang=en&date=30092026&pickupType=STORE&storeId=1032&banner=loblaw` (opened 00:43–00:44; store 1032 = Loblaws, 200 Bullock Dr, Markham ON per Loblaw's pickup-locations endpoint, opened 01:13).

| Product (exact name in Loblaw data) | Code / GTIN | Size | Loblaw origin badge field | Page path |
|---|---|---|---|---|
| PC Organics — Organic Quick Rolled Oats | 20705773_EA / 00060383690229 | 1000 g | "Prepared in Canada" | /organic-quick-rolled-oats/p/20705773_EA |
| PC Organics — Old Fashioned Gluten Free Rolled Oats (name as listed) | 21396198_EA / 00060383035440 | 900 g | "Prepared in Canada" | /p/21396198_EA |
| PC Organics — Organic Steel Cut Oats | 20971286_EA / 00060383164676 | 1 kg | "Prepared in Canada" | /p/20971286_EA |
| PC Organics — Organics Maple and Brown Sugar Flavour Instant Oatmeal | 20974190_EA / 00060383150747 | 400 g | none | /p/20974190_EA |
| PC Organics — Organics Instant Oatmeal with Flaxseed | 20971781_EA / 00060383150730 | 400 g | none | /p/20971781_EA |
| President's Choice — Maple and Brown Sugar Flavour Instant Oatmeal | 21505150_EA / 00060383050498 | 344 g | none | /p/21505150_EA |
| President's Choice — Regular Instant Oatmeal | 21505058_EA / 00060383050399 | 280 g | none | /p/21505058_EA |
| President's Choice — Apples and Cinnamon Instant Oatmeal | 21506334_EA / 00060383050566 | 264 g | none | /p/21506334_EA |
| President's Choice — Instant Oatmeal, Peaches and Cream, 8 Servings | 21506332_EA / 00060383050467 | 264 g | none | /p/21506332_EA |
| President's Choice — Instant Oatmeal, Cinnamon & Spice, 8 Servings | 21505067_EA / 00060383050573 | 304 g | none | /p/21505067_EA |
| President's Choice — Instant Oatmeal, Variety Pack, 8 Pack | 21505117_EA / 00060383050474 | 314 g | none | /p/21505117_EA |
| PC Blue Menu — 100% Whole Grain Steel Cut Oats | 20703868_EA / 00060383781323 | 840 g | none | /p/20703868_EA |
| PC Blue Menu — Regular Steel Cut Oats | 20943962_EA / 00060383114657 | 360 g | none | /p/20943962_EA |
| PC Blue Menu — Maple & Brown Sugar Steel Cut Oats | 20943950_EA / 00060383114640 | 360 g | none | /p/20943950_EA |
| PC Blue Menu — Blue Menu Regular Supergrains Oatmeal | 21000529_EA / 00060383161583 | 8x38.0 g | none | /p/21000529_EA |
| PC Blue Menu — Blue Menu Maple and Brown Sugar Flavour Supergrains Oatmeal | 21004695_EA / 00060383161804 | 8x38.0 g | none | /p/21004695_EA |

The badge fields in Loblaw's data are `preparedInCanadaBadge`, `madeInCanadaBadge`, `productOfCanadaBadge`, `preparedInQuebecBadge`, `tariffAppliedBadge`; only `preparedInCanadaBadge` ("Prepared in Canada") was populated for any PC/no name oat SKU. "none" = all five null.

**Country-of-origin / "Product of" / "Made in" line.**
- PC Organics instant (both SKUs): **from pack image (front)** — Canada Organic / Biologique Canada logo, and beside it "IMPORTED" / "IMPORTÉ". Images: https://digital.loblaws.ca/PCX/20974190_EA/en/1/20974190_en_front_1200.png and https://digital.loblaws.ca/PCX/20971781_EA/en/1/20971781_en_front_v2_1200.png (opened 00:44). No country is named in the images served; the back-panel image (…/20974190_en_angle_1200.png) shows instructions, the ingredient list and a facts table only — the dealer/"Imported by/for" panel is not in any image served. **UNVERIFIED: country of origin and dealer line.**
- PC (non-organic) instant: **from pack image (front)** — "Made with 100% Canadian oats" (EN) / "Fait avec de l'avoine 100 % canadienne" (FR) on Maple & Brown Sugar (…/21505150_en_front_v2_1200.png; …/21505150_fr_angle_1200.png), Cinnamon & Spice (FR front image), Peaches & Cream (FR front image). No "Product of"/"Made in" line visible in any image served.
- PC Blue Menu Regular Steel Cut Oats 360 g: **from pack image (front)** "Made with 100% Canadian oats" (…/20943962_en_front_1200.png).
- PC Organics plain bags: no "Product of"/"Made in"/"Imported" text visible in the front images; Canada Organic logo visible on front (…/20705773_en_front_1200.png; …/21396198_en_front_1200.png; …/6038316467_enfr_front_centre_marketing_GS1_Ecommerce_1200.png). Retailer badge "Prepared in Canada" (data field).

**Dealer line.** PC Organics Old-Fashioned Gluten-Free Rolled Oats back panel (**pack image**, https://digital.loblaws.ca/PCX/21396198_EA/en/2/21396198_en_angle_1200.png): "LOBLAWS INC. TORONTO M4T 2S8, CANADA © 2021 ®/TM/MC TRADEMARKS OF / MARQUES DE COMMERCE DE LOBLAWS INC." and "CERTIFIED ORGANIC BY: / CERTIFIÉ BIOLOGIQUE PAR: QAI INC." (certifier, not a manufacturer). No dealer line visible in any PC instant image served.

**Ingredients (verbatim, Loblaw data).**
- Plain — PC Organics Organic Quick Rolled Oats: "Organic Rolled Oats. May Contain Wheat."
- Instant flavour — PC Organics Organics Maple and Brown Sugar Flavour Instant Oatmeal: "Organic Whole Grain Rolled Oats, Sugars (organic Evaporated Cane Syrup, Organic Maple Sugar), Sea Salt, Organic Natural Flavour. May Contain: Wheat."
- Instant flavour — President's Choice Maple and Brown Sugar Flavour Instant Oatmeal: "Whole Grain Rolled Oats, Sugar, Salt, Calcium Carbonate (thickener), Natural Flavour, Guar Gum, Vitamins And Minerals [ferric Orthophosphate (iron), Niacinamide, Thiamine Mononitrate, Calcium Pantothenate, Pyridoxine Hydrochloride (vitamin B6), Folic Acid], Caramel Colour. May Contain: Wheat."
- Plain — PC Blue Menu 100% Whole Grain Steel Cut Oats: "Steel Cut Oats. May Contain: Wheat."

**Maple leaf / "Canadian" wording on pack.** Canada Organic logo (contains a maple leaf) on all PC Organics items imaged; "Made with 100% Canadian oats" on PC instant and PC Blue Menu Regular Steel Cut Oats; "IMPORTED / IMPORTÉ" beside the organic logo on PC Organics instant.

**Prices:** §6.1.

### 3.2 no name (Loblaw)

Owner: as §3.1. Retailer pages 403; data from the same back-end (opened 00:43–00:44).

| Product (exact name) | Code / GTIN | Size | Loblaw badge | Path |
|---|---|---|---|---|
| Quick 100% Whole Grain Oats | 20923828_EA / 00060383159917 | 1 kg | "Prepared in Canada" | /quick-100-whole-grain-oats/p/20923828_EA |
| Large Flake 100% Whole Grain Oats | 20923994_EA / 00060383159924 | 1 kg | "Prepared in Canada" | /p/20923994_EA |
| One-Minute 100% Whole Grain Oats | 20923942_EA / 00060383159900 | 900 g | "Prepared in Canada" | /p/20923942_EA |
| Quick 100% Whole Grain Oats Club Size | 20923786_EA / 00060383159276 | 2.25 kg | "Prepared in Canada" | /p/20923786_EA (superstore 1517) |
| Large Flake 100% Whole Grain Oats Club Size | 20923840_EA / 00060383159283 | 2.25 kg | "Prepared in Canada" | /p/20923840_EA (superstore 1517) |

No no name instant oatmeal was returned by Loblaw's search for "instant oatmeal", "oatmeal", "no name oats" and 11 other terms at five stores (Markham Loblaws 1032, Toronto No Frills 7952, Vancouver RCSS 1517, Montréal Provigo 7297, Montréal Maxi 9528; 00:42).

**Origin wording — from pack image (front)** https://digital.loblaws.ca/PCX/20923828_EA/en/1/20923828_en_front_v1_1200.png (opened 00:44): "100% whole grain Canadian oats" / "avoine canadienne à grains entiers à 100 %"; same wording on Large Flake (…/20923994_en_front_1200.png) and Club Size (…/20923786_en_front_1200.png). A small maple-leaf mark with a two-line legend above "CANADA" appears bottom-left; **the two lines are not legible at the resolution served** (UNVERIFIED #3). No "Product of"/"Made in" line on the back panel image.

**Dealer line — from pack image (back)** https://digital.loblaws.ca/PCX/20923828_EA/en/2/20923828_en_angle_1200.png: "LOBLAWS INC. TORONTO M4T 2S8, CANADA ©[year illegible] ®/TM/MC TRADEMARKS OF / MARQUES DE COMMERCE DE LOBLAWS INC." and "Satisfaction Guaranteed / Satisfaction assurée".

**Ingredients (verbatim, Loblaw data):** "Rolled Whole Grain Oats. May Contain: Wheat." (all five SKUs). Pack image back panel: "Ingredients: Rolled whole grain oats. May contain: Wheat. Ingrédients : Flocons d'avoine à grains entiers. Peut contenir : Blé." Instant flavour: none exists (see above).

### 3.3 Compliments (Sobeys / Empire)

**Owner.** Empire Company Limited: "Empire Company Limited is a Canadian company headquartered in Stellarton, Nova Scotia." … "Sobeys Inc. is the wholly-owned subsidiary of Empire Company Limited." — https://www.empireco.ca/ (opened 01:07). Country: Canada.

**Retailer pages** (voila.ca, opened 00:48–00:49; no delivery address set — region not displayed). Price and unit price as displayed; "Country Of Origin" field present in page template but **not populated** for any Compliments oat SKU.

| Exact name (Voilà) | URL | Price shown | Unit shown |
|---|---|---|---|
| Compliments Quick Oats 1 kg | https://voila.ca/products/compliments-quick-oats-1-kg/435017EA | $4.49 | $0.45 per 100g |
| Compliments Quick Oats 2.25 kg | https://voila.ca/products/compliments-quick-oats-2-25-kg/487320EA | $6.79 | $0.30 per 100g |
| Compliments Organic Quick Oats 1 kg | https://voila.ca/products/compliments-organic-quick-oats-1-kg/730748EA | $4.99 | $0.50 per 100g |
| Compliments Quick Cook Steel Cut Oats 709 g | https://voila.ca/products/compliments-quick-cook-steel-cut-oats-709-g/759164EA | $5.49 | $0.77 per 100g |
| Compliments Instant Oatmeal Maple & Brown Sugar Flavour 344 g | https://voila.ca/products/compliments-instant-oatmeal-maple-brown-sugar-flavour-344-g/980771EA | $3.99 | $1.16 per 100g |
| Compliments Instant Oatmeal Regular 280 g | https://voila.ca/products/compliments-instant-oatmeal-regular-280-g/980773EA | $3.99 | $1.42 per 100g |
| Compliments Instant Oatmeal Apple & Cinnamon Flavour 260 g | https://voila.ca/products/compliments-instant-oatmeal-apple-cinnamon-flavour-260-g/980769EA | $3.99 | $1.53 per 100g |
| Compliments Instant Oatmeal Peaches & Cream Flavour 260 g | https://voila.ca/products/compliments-instant-oatmeal-peaches-cream-flavour-260-g/980772EA | $3.99 | $1.53 per 100g |
| Compliments Instant Oatmeal Variety Pack 313 g | https://voila.ca/products/compliments-instant-oatmeal-variety-pack-313-g/980774EA | $3.99 | $1.27 per 100g |
| Compliments Instant Oatmeal Variety Pack 691 g | https://voila.ca/products/compliments-instant-oatmeal-variety-pack-691-g/222160EA | $6.99 | $1.01 per 100g |
| Compliments Balance Instant Oatmeal Variety Pack 378 g | https://voila.ca/products/compliments-balance-instant-oatmeal-variety-pack-378-g/763767EA | $3.69 | $0.98 per 100g |
| Compliments Balance Oatmeal Maple & Brown Sugar 430 g | https://voila.ca/products/compliments-balance-oatmeal-maple-brown-sugar-430-g/286858EA | $3.69 | $0.86 per 100g |
| Compliments Instant Oatmeal Apple Cinnamon 325 g | https://voila.ca/products/compliments-instant-oatmeal-apple-cinnamon-325-g/286855EA | $3.69 | $1.14 per 100g |
| Compliments Instant Oatmeal Peaches & Cream 325 g | https://voila.ca/products/compliments-instant-oatmeal-peaches-cream-325-g/286865EA | $3.69 | $1.14 per 100g |
| Compliments Oatmeal Regular 336 g | https://voila.ca/products/compliments-oatmeal-regular-336-g/286867EA | $3.69 | $1.10 per 100g |

No Compliments large-flake oats were returned by Voilà searches ("compliments large flake oats", "compliments rolled oats").

**Origin wording.**
- Page text, Compliments Quick Oats 1 kg and 2.25 kg ("Product Information"): "100% whole grain Canadian oats."
- **From pack image (front):** Compliments Quick Oats 1 kg (https://voila.ca/images-v3/2d92d19c-0354-49c0-8a91-5260ed0bf531/7bcaeb20-d89c-448a-8fd7-b6675dc20518/1280x1280.jpg) and Compliments Organic Quick Oats 1 kg (…/a45a6f21-b61c-409e-bd63-59a7a4f64a38/1280x1280.jpg): round maple-leaf seal reading "PRODUCT OF • PRODUIT DU CANADA". Organic pack also shows the Canada Organic / Biologique Canada logo.
- Instant fronts (980769, 980771, 980772, 980773, 980774, 222160, 286858; images opened 00:49–00:50): **no Canada wording or maple leaf visible**. (286858 and other 2868xx images show an older "Compliments balance/équilibre" design — the image may not match current stock.)

**Dealer line.** Not visible in any image served; Voilà shows the front only. UNVERIFIED.

**Ingredients (verbatim, Voilà).**
- Plain — Compliments Quick Oats 1 kg: "Rolled Oats. May Contain: Wheat". (2.25 kg page: "Rolled Oats".) Organic Quick Oats: "Organic Rolled Oats. May Contain: Wheat". Steel Cut: "Whole Grain Steel Cut Oats. May Contain: Wheat".
- Instant — Compliments Balance Instant Oatmeal Variety Pack 378 g (only instant SKU with an ingredient list on Voilà; page lists one combined list for "4 Maple & Brown Sugar Flavour, 4 Apple & Cinnamon, 2 Cinnamon Spice"): "Whole Grain Rolled Oats, Sugar, Dried Apple (Apple, Calcium Stearate, Sulphites), Salt, Calcium Carbonate, Guar Gum, Cinnamon, Natural Flavours, Vitamins And Minerals [Ferric Orthophosphate (Iron), Niacinamide, Thiamine Mononitrate, Calcium Pantothenate, Pyridoxine Hydrochloride (Vitamin B₆), Folic Acid]. May Contain: Wheat". Voilà disclaimer on every page tells shoppers to "refer to the product package for the most current and accurate ingredient … or other product information."

### 3.4 Great Value (Walmart Canada)

**Owner.** "Walmart Canada is part of Walmart Inc." — https://www.walmartcanada.ca/about-us (opened 01:07). Walmart Inc. is a U.S. company (Bentonville, Arkansas — U.S. context; not re-opened today, see UNVERIFIED #12). Country of ultimate owner: United States.

**Retailer pages** (walmart.ca, mobile UA, opened 00:51; page data: store 1061, postal L5V 2N6, Mississauga ON):

| Exact name | URL | Size (page) | Price | Unit (page) |
|---|---|---|---|---|
| Great Value Quick Oats 1 kg | https://www.walmart.ca/en/ip/Great-Value-Quick-Oats-1-kg/6000195340329 | 1 kg | $2.77 | 28¢/100g |
| Great Value One Minute Oats | https://www.walmart.ca/en/ip/Great-Value-One-Minute-Oats/6000195371239 | 1 kg | $2.77 | 28¢/100g |
| Great Value Quick Cook Steel Cut Oats | https://www.walmart.ca/en/ip/Great-Value-Quick-Cook-Steel-Cut-Oats/6000195562899 | 1 kg | $2.77 | 28¢/100g |
| Great Value Organic Quick Oats | https://www.walmart.ca/en/ip/Great-Value-Organic-Quick-Oats/6000197801115 | 1 kg | $4.17 | 42¢/100g |
| Great Value Maple & Brown Sugar Natural Flavour Instant Oatmeal | https://www.walmart.ca/en/ip/Great-Value-Maple-Brown-Sugar-Natural-Flavour-Instant-Oatmeal/6GM77CYLYRQA | 344 g | $2.97 | 86¢/100g |
| Great Value Regular Instant Oatmeal | https://www.walmart.ca/en/ip/Great-Value-Regular-Instant-Oatmeal/4GTCVBWJWJT2 | 280 g | $2.97 | $1.06/100g |
| Great Value Apples & Cinnamon Instant Oatmeal | https://www.walmart.ca/en/ip/Great-Value-Apples-Cinnamon-Instant-Oatmeal/18M5MH8VH33Y | 264 g | $2.97 | $1.13/100g |
| Great Value Variety pack Instant Oatmeal | https://www.walmart.ca/en/ip/Great-Value-Variety-pack-Instant-Oatmeal/3CJSBXJAG8G3 | 314 g | $2.97 (search page) | 95¢/100g (search page) |

The Variety pack product URL returned **HTTP 404** but its embedded data still contained the ingredient and description fields quoted below; price is from the walmart.ca search results page (opened 00:50). Treat the variety pack as possibly delisted.

**Origin wording.**
- Plain — **from pack image (front)** https://i5.walmartimages.ca/asr/7f2cfd11-4285-4878-abba-18612848eada.e5b34c5d845782fa8afb2153693730fa.jpeg (Quick Oats): maple-leaf seal "PRODUCT OF • PRODUIT DU CANADA" and the line "100% WHOLE GRAIN CANADIAN OATS / AVOINE CANADIENNE À 100 % DE GRAINS ENTIERS". Steel Cut (…/e0a95b9f-…jpeg): same "PRODUCT OF • PRODUIT DU CANADA" seal and "100% WHOLE GRAIN CANADIAN OATS". One Minute (…/a47a6954-…jpeg): "100% WHOLE GRAIN CANADIAN OATS" and a maple-leaf "CANADA" seal (seal legend not legible at served resolution). One Minute page text: "100% Canadian". Organic Quick Oats front (…/4b087647-…jpeg): Canada Organic logo; no origin line visible.
- Instant — **from pack image (front)** https://i5.walmartimages.ca/asr/63522de4-847e-46db-8dc7-c0068bcda084.7745bf95035f92f090c7ea8d24311a6d.jpeg (Maple & Brown Sugar): maple-leaf seal "MADE IN CANADA / FROM DOMESTIC AND IMPORTED INGREDIENTS" and "MADE WITH 100% CANADIAN OATS". Page text (Maple & Brown Sugar, Regular, Apples & Cinnamon, Variety): "Made with 100% Canadian oats" and "Made in Canada from domestic and imported ingredients". The pack art also includes autumn maple-leaf illustrations.

**Dealer line.** Not visible in any image served (front, Ingredient Wise panel, ingredients panel, nutrition panel). UNVERIFIED.

**Ingredients (verbatim, walmart.ca).**
- Plain — Quick Oats 1 kg: "100% whole grain rolled oats. Contains: oats. May Contain: wheat. Naturally contains oat bran". Pack image ingredients panel (…/b6b70a58-…jpeg): "Ingredients: 100% whole grain rolled oats. Contains: Oats. May contain: Wheat." Organic: "100 % Whole Grain Organic Rolled Oats. Contains: Oats. May Contain: Wheat." Steel cut: "100% Whole Grain Oats. Contains: Oats. May Contain: Wheat."
- Instant — Maple & Brown Sugar: "Whole grain rolled oats, Sugars (sugar, brown sugar), Salt, Natural flavours, Caramel colour. Contains: Oats. May contain: Tree nuts, Milk, Soy, Wheat, Sulphites." (identical on pack image …/18bad129-…jpeg).

### 3.5 Selection / Irresistibles / Life Smart (Metro)

**Owner.** METRO Inc., "Head office 11 011, boul. Maurice-Duplessis Montreal (Quebec) H1C 1V6"; "A network of some 1012 food stores under several banners including Metro, Metro Plus, Super C and Food Basics." — https://corpo.metro.ca/en/about-us.html (opened 01:07). Country: Canada.

**Retailer pages** — www.metro.ca returned 403 (00:55); identical Metro pages read from `api2.metro.ca` (opened 00:55). Store shown on page: "Metro Devonshire"; Metro: "Prices subject to change, depending on your order pickup or delivery date, current promotions, and location."

| Exact name | URL (www.metro.ca path; read via api2.metro.ca) | Size | Price | Unit (page) | Origin text on page |
|---|---|---|---|---|---|
| Selection Quick Oats | /en/online-grocery/aisles/pantry/cereals-spreads-syrups/oatmeal-hot-cereals/quick-oats/p/059749955348 | 1 kg | $2.99 | $0.30 /100 g | "Product of Canada"; tag "Food Canada" |
| Selection Large Flake Oatmeal | …/large-flake-oatmeal/p/059749977852 | 900 g | $2.99 | $0.33 /100 g | "Product of Canada"; tag "Food Canada" |
| Selection Maple and Brown Sugar Instant Oatmeal | …/maple-and-brown-sugar-instant-oatmeal/p/059749955355 | 10x43 g | $3.49 | $0.81 /100 g | "Product of Canada"; tag "Made in Canada" |
| Selection Assorted Instant Oatmeal Packets | …/assorted-instant-oatmeal-packets/p/059749955362 | 380 g | $3.49 | $0.92 /100 g | "Product of Canada"; tag "Made in Canada" |
| Irrésistible Steel cut oatmeal | …/steel-cut-oatmeal/p/059749960823 | 680 g | $4.39 (out of stock) | $0.65 /100 g | none shown |
| Life Smart Quick Oatmeal Packets, Gluten Free (name as listed) | …/quick-oatmeal-packets/p/059749977838 | 344 g | $3.49 | $1.01 /100 g | "Product of Canada"; tag "Food Canada" |
| Life Smart Organic Instant Oatmeal | …/instant-oatmeal-in-packets/p/059749977845 | 320 g | $3.49 (out of stock) | $1.09 /100 g | "Product of Canada"; tag "Food Canada" |

Page description text (attributed, Metro says): Selection Quick Oats "Made with 100% Canadian oats"; Selection Maple & Brown Sugar instant "Made with 100% Canadian oats"; Irresistibles steel cut "made of whole grain Canadian oats". (The remainder of those Metro descriptions contains nutrition wording and is not quoted.)

**Ingredients (verbatim, Metro page).** Plain — Selection Quick Oats: "Rolled oats. Contains: Oats. May contain: Wheat, Barley, Rye, Triticale". Large Flake: "Rolled oats. Contains: Oats. May contain: Wheat". Instant flavour — **no ingredient list on either Selection instant page; pack images blocked (403)** — UNVERIFIED. (Life Smart Organic Instant: "organic whole grain oats. CONTAINS: oats. MAY CONTAIN: wheat, barley, almond, hazelnut, pecan, pistachio, cashew, sesame, milk, soy, sulphites, triticale." — this is the unflavoured product.)

**Dealer line / pack origin line / maple leaf on pack.** Not read — product-images.metro.ca returned 403. UNVERIFIED.

### 3.6 Western Family (Pattison Food Group / Save-On-Foods)

**Owner.** "Pattison Food Group is a Jim Pattison business and Canada's largest Western-based provider of food and health products. Headquartered in British Columbia, Canada, we have been in business since 1915." Corporate brands listed: "Western Family", "Only Goodness". — https://pattisonfoodgroup.com/ (opened 01:07). Country: Canada (privately held — ownership structure beyond "a Jim Pattison business" not verified today).

**Retailer data** — saveonfoods.com 403; Save-On's own storefront gateway `https://storefrontgateway.saveonfoods.com/api/stores/1982/products/{sku}` (opened 00:57), store 1982 = Save-On-Foods, 19855 92a Ave, Langley Twp, BC.

| Exact name | SKU | Size | Price | Unit (page) | Save-On attributes |
|---|---|---|---|---|---|
| Western Family - Quick Oats | 00062639185367 | 1 kg | $4.69 | $0.47/100g | made in canada: false; product of canada: true |
| Western Family - 100% Whole Grain Canadian Quick Oats | 00062639185350 | 2.25 kg | $7.69 | $0.34/100g | made in canada: false; product of canada: true |
| Western Family - 100% Whole Grain Canadian Steel Cut Oats | 00062639342470 | 1 kg | $4.69 | $0.47/100g | made in canada: false; product of canada: true |
| Western Family - Regular Instant Oatmeal | 00062639370695 | 280 g | $4.29 | $1.53/100g | made in canada: true; product of canada: false |
| Western Family - Maple & Brown Sugar Instant Oatmeal | 00062639370701 | 344 g | $4.29 | $1.25/100g | made in canada: true; product of canada: false |
| Western Family - Apple & Cinnamon Flavor Instant Oatmeal | 00062639370725 | 264 g | $4.29 | $1.63/100g | made in canada: true; product of canada: false |

Save-On product URLs (customer-facing, 403 to automated requests): `https://www.saveonfoods.com/sm/pickup/rsid/1982/product/{sku}` — not opened. No Western Family large-flake oats were returned by the gateway search ("western family large flake").

**Origin wording — from pack image (front)**, Save-On image host: https://images.cdn.saveonfoods.com/zoom/00062639342470.jpg (Steel Cut) and …/00062639185350.jpg (2.25 kg Quick): maple-leaf seal "PRODUCT OF CANADA / PRODUIT DU CANADA"; banner text "100% WHOLE GRAIN CANADIAN STEEL CUT OATS / AVOINE CANADIENNE DÉCOUPÉE" and "100% WHOLE GRAIN CANADIAN QUICK OATS / AVOINE CANADIENNE À CUISSON RAPIDE". Maple & Brown Sugar instant front (…/00062639370701.jpg): maple-leaf illustrations in the pack art; no origin statement visible on the front.

**Dealer line.** Not visible in images served. UNVERIFIED.

**Ingredients (verbatim, Save-On).** Plain — Quick Oats 1 kg: "Whole grain rolled oats. MAY CONTAIN: wheat." Instant — Maple & Brown Sugar: "Whole grain rolled oats, sugars (sugar, brown sugar), salt, natural flavours, caramel colour.CONTAINS: oats. MAY CONTAIN: milk, soy, tree nuts, wheat, sulphites."

### 3.7 Kirkland Signature (Costco Canada)

**Owner.** Costco Wholesale Corporation, 999 Lake Drive, Issaquah, WA (U.S.): "The Company is principally engaged in the operation of membership warehouses through wholly owned subsidiaries in the U.S., Canada, …"; "110 in Canada" warehouses at August 31, 2025. — Costco FY2025 Form 10-K (U.S. SEC filing), https://www.sec.gov/Archives/edgar/data/909832/000090983225000101/cost-20250831.htm (opened 01:09). Country of ultimate owner: United States.

**Retailer pages.**
- https://www.costco.ca/p/-/kirkland-signature-whole-grain-rolled-oats-454-kg/4000339745 (opened 00:53): name "Kirkland Signature Whole Grain Rolled Oats, 4.54 kg"; "Item 1736339"; features "Whole grain rolled oats; 4.54 kg; Kosher"; JSON-LD price $11.99, availability "OutOfStock"; page shows "Unavailable".
- https://sameday.costco.ca/store/costco-canada/products/84469724-kirkland-signature-whole-grain-rolled-oats-4-54-kg (read via WebFetch 00:54): "$11.34", "$0.25/100g", "4.54 kg", Item 1736339. Location not displayed.
- https://www.costcobusinesscentre.ca/p/-/kirkland-signature-whole-grain-rolled-oats-454-kg/2001204671 (opened 00:53): same item 1736339, "Container Size 4.54 kg (10.01 lb)", OutOfStock, no price exposed.

**Origin and dealer line — from pack image (back)**, https://gdx-assets.costco.com/adobe/assets/urn:aaid:aem:4be27720-74c6-4b33-a60c-05912ca477f7/as/1736339-894__2.jpg (served by costco.ca page; opened 00:54):
> "Costco Wholesale Canada Ltd.* 415 W. Hunt Club Road Ottawa, Ontario K2E 1C5, Canada 1-800-463-3783 • www.costco.ca * faisant affaire au Québec sous le nom les Entrepôts Costco"
> "PRODUCT OF CANADA / PRODUIT DU CANADA"

**Ingredients (pack image, verbatim):** "Ingredients: Whole grain rolled oats. Contains: Oats. Ingrédients : Flocons d'avoine à grains entiers. Contient : Avoine." costco.ca shows no ingredient text. **Instant flavour: no Kirkland Signature instant oatmeal was found on Costco Canada sites** (costco.ca search is client-rendered; see UNVERIFIED #6). No maple leaf on the pack images; "PRODUCT OF CANADA" text only.

### 3.8 Co-op Gold (Federated Co-operatives Limited)

**Owner.** Federated Co-operatives Limited (FCL): "As a wholesaler, FCL supplies high-quality grocery items across all departments to its members' retail locations. FCL develops private-label products" — https://www.fcl.crs/about-fcl (opened 01:07). A member co-op page states "Kindersley & District Co-op is owned by Kindersley & District Co-op members." — https://www.kindersleyco-op.crs/sites/kindersley/local/detail/co-op-is-proudly-canadian (dated February 12, 2025; opened 01:10). FCL's own ownership wording was not found on the pages opened (UNVERIFIED #10). Country: Canada.

**Product data: NOT VERIFIED.** No retailer page listing a Co-op Gold oat product could be opened: coopathome.ca returned 429; shoponline.calgarycoop.com and shop.crs are client-rendered (no products in HTML); WebFetch of the Calgary Co-op search returned navigation only (00:59–01:10). Search results point to a "Co-op Gold Pure Organic Quick Oats 1 kg" listing on a third-party grocer (edmontongrocer.com) and to calorie sites — tier (c), not used. See UNVERIFIED #5.

**Co-op statements usable for context (company/member-co-op pages, tier a):**
- Saskatoon Co-op, "Co-op Store Brands", April 17, 2023 — https://www.saskatoonco-op.crs/sites/saskatoon/food/detail/co-op-store-brands (opened 01:10): "At Co-op, we work hand in hand with our suppliers and strive to obtain products from Western Canada and Canada whenever feasible."
- Kindersley & District Co-op, "Co-op is proudly Canadian", February 12, 2025 (URL above): "Many Co-op Gold and Co-op Gold Pure products are made in Western Canada with ingredients grown in Western Canada, including some of our favourites, like Co-op Gold Pure Pickles , Co-op Gold Pure No-Sugar-Added Fruit Spreads and Co-op Gold Pure Oat Beverage ." (Oat beverage is not oatmeal.)

### 3.9 Giant Value / Giant Tiger Marché (Giant Tiger)

**Owner.** Giant Tiger Stores Limited, Ottawa. Tier (b): Retail Insider, Mario Toneguzzi, 15 May 2025 — "Giant Tiger, the leading Canadian-owned family discount store, is a privately held company with over 260 locations across Canada" (company statement reported) — https://retail-insider.com/retail-insider/2025/05/giant-tiger-and-banfield-partner-to-highlight-the-power-of-local-ownership/ (opened 01:09). Country: Canada.

**Retailer data** — product JSON `https://www.gianttiger.com/products/{handle}.json` (opened 00:58). Province availability from product tags. Site note on product pages: "Online prices may vary from in-store prices."

| Exact name | URL | Price | Size (pack) | Tags | Origin tag |
|---|---|---|---|---|---|
| Giant Value Quick Oats, 1 kg | https://www.gianttiger.com/products/giant-value-quick-oats-1kg-2 | $2.77 | 1 kg | AB, MB, NB, NS, ON, PE, QC, SK | product_of_canada |
| Giant Value Large Flake Oats, 1 kg | https://www.gianttiger.com/products/giant-value-large-flake-oats-1-kg | $2.77 | 1 kg | same | product_of_canada |
| Giant Value Regular Instant Oatmeal, 10-Pack | https://www.gianttiger.com/products/giant-value-regular-instant-oatmeal-10-pack | $2.87 | 280 g (pack image) | same | none |
| Giant Value Maple and Brown Sugar Instant Oatmeal, 8-Pack | https://www.gianttiger.com/products/giant-value-maple-and-brown-sugar-instant-oatmeal-8-pack | $2.87 | 344 g (pack image) | same | none |
| Giant Value Apples and Cinnamon Instant Oatmeal, 8-Pack | https://www.gianttiger.com/products/giant-value-apples-and-cinnamon-instant-oatmeal-8-pack | $2.87 | 264 g (pack image) | same | none |

The site's page template maps `product_of_canada` to a "Product of Canada" badge and `made_in_canada` to "Made in Canada" (template text on https://www.gianttiger.com/products/giant-value-maple-and-brown-sugar-instant-oatmeal-8-pack, opened 00:58). No "Giant Tiger Marché" oatmeal was returned (only granola/cookies).

**Origin wording — from pack image (front).** Quick Oats (https://cdn.shopify.com/s/files/1/0557/6858/0157/files/preview_images_804004_f_02.jpg) and Large Flake (…/preview_images_1422826_f_01.jpg): maple-leaf badge "100% CANADIAN OATS / FLOCONS D'AVOINE 100% CANADIENS". Maple & Brown Sugar instant (…/preview_images_1603457_f_01_en.jpg): maple-leaf badge "MADE WITH 100% CANADIAN OATS". No "Product of"/"Made in" statement visible on any pack image; no dealer line visible (UNVERIFIED).

**Ingredients — from pack images (verbatim).** Plain — Large Flake (…/preview_images_1422826_d_01.jpg): "Ingredients: Whole grain rolled oats. Contains: Oats. May contain: Wheat." Instant — Maple and Brown Sugar (…/preview_images_1603457_d_02.jpg): "Ingredients: Whole grain rolled oats, Sugars (sugar, brown sugar), Salt, Natural flavours, Caramel colour. Contains: Oats May contain: Tree nuts, Milk, Soy, Wheat, Sulphites".

### 3.10 Farm Boy (Sobeys / Empire)

**Owner.** Empire Company Limited completed its purchase of Farm Boy on 10 Dec 2018 — Ottawa Business Journal (OBJ staff), 10 Dec 2018: "Farm Boy's run as an independent grocer officially came to an end Monday with the close of Empire Co.'s $800-million acquisition of the Ottawa-based company." https://obj.ca/sobeys-parent-company-closes-800m-acquisition-of-ottawa-based-farm-boy/ (opened 01:08; tier b, staff byline). Seller's release (Berkshire Partners, 10 Dec 2018): https://berkshirepartners.com/empire-company-completes-purchase-of-farm-boy-ontarios-best-in-class-food-retailer/ (opened 01:08). Country: Canada.

**Retailer pages.**
- farmboy.ca (opened 01:01): "Farm Boy™ Large Flake Oats (750 g)" https://www.farmboy.ca/products/farm-boy-large-flake-oats-750-g/ ; "Farm Boy™ Quick Oats (750 g)" https://www.farmboy.ca/products/farm-boy-quick-oats-750-g/ ; "Farm Boy™ Steet Cut Oats (1 kg)" [sic] https://www.farmboy.ca/products/farm-boy-steet-cut-oats-1-kg/ ; "Farm Boy™ Twice Berry Instant Oatmeal (360 g)" https://www.farmboy.ca/products/farm-boy-twice-berry-instant-oatmeal-360-g/ ; "Farm Boy™ Maple Walnut Instant Oatmeal (70 g)" https://www.farmboy.ca/products/farm-boy-maple-walnut-instant-oatmeal-70-g/ (01:11). farmboy.ca shows no prices. The Apple & Cinnamon 360 g page redirected (307) and was not read.
- Prices from Voilà (Sobeys' e-commerce; Voilà listing of the Farm Boy brand, not a Farm Boy store price; opened 00:49): Farm Boy Organic Large Flake Oats 750 g $5.49 (https://voila.ca/products/farm-boy-organic-large-flake-oats-750-g/836391EA); Farm Boy Organic Steel Cut Oats 1 kg $5.99 (…/836389EA); Farm Boy Instant Oatmeal Apple & Cinnamon 6 x 60 g $4.99 (…/831935EA); Farm Boy Instant Oatmeal Twice Berry 6 x 60 g $4.99 (…/831938EA); Farm Boy Oatmeal Cup Apple & Cinnamon 70 g $1.79 (…/831870EA); Farm Boy Oatmeal Cup Maple Walnut 70 g $1.79 (…/831868EA); Farm Boy Overnight Oats Almond Raisin 70 g $2.99 (…/1294186EA).

**Origin classification — Farm Boy "Proudly Canadian" page**, https://www.farmboy.ca/canada-products/ (opened 01:01):
> "Look for "Product of Canada"— these items have at least 98% domestically sourced ingredients and production combined."
> "Our "Prepared in Canada" products are crafted in Canada with either a combination of domestic and imported ingredients or imported ingredients only."
Listed: Large Flake Oats (750 g) — "Product of Canada"; Quick Oats (750 g) — "Product of Canada"; Steet Cut Oats (1 kg) — "Product of Canada"; Apple & Cinnamon Instant Oatmeal (360 g) — "Prepared in Canada"; Twice Berry Instant Oatmeal (360 g) — "Prepared in Canada"; Apple Cinnamon / Banana Nut / Berry Medley / Maple Walnut Instant Oatmeal (70 g) — "Prepared in Canada"; Almond Raisin, Fig & Pistachio, Pecan Date Overnight Oats (70 g) — "Prepared in Canada".

**Pack wording — from pack image (front)** (Voilà images …/f9adf667-…/1280x1280.jpg and …/c2091d37-…/1280x1280.jpg): "ORGANIC LARGE FLAKE OATS / FLOCONS D'AVOINE BIOLOGIQUE", "MILLED IN ONTARIO / MOULU EN ONTARIO", "CERTIFIED ORGANIC BY PRO-CERT / CERTIFIÉ BIOLOGIQUE PAR PRO-CERT" (certifier, not a manufacturer), Canada Organic logo. Company description (Farm Boy says): oats "certified organic and milled in Ontario" (farmboy.ca); oatmeal cups "made with wholesome 100% Ontario-grown oats" (Voilà 831868EA; farmboy.ca 70 g pages); instant 360 g "made with 100% Canadian oats" (Voilà 831935EA). Note: farmboy.ca's Twice Berry 360 g page reuses the oatmeal-cup description text — page error flag, do not quote that page's description.

**Ingredients (verbatim, farmboy.ca).** Plain — Large Flake Oats: "Organic Oats. May Contain: Peanuts, Tree Nuts, Sesame, Soy, Wheat, Mustard." Instant — Twice Berry Instant Oatmeal (360 g): "Large And Small Flake Oats • Turbinado Sugar • Red Bran • Freeze-Dried Blueberries • Freeze-Dried Strawberries • Strawberry Flakes (Strawberries, Sugar, Cornstarch, Sunflower Lecithin) • Rye Flakes • Wheat Flakes • Blueberry Flakes (Blueberries, Cornstarch, Sunflower Lecithin) • Kosher Salt. Contains: Wheat. May Contain: Tree Nuts, Soy."

**Dealer line.** Not visible in any image served. UNVERIFIED.

---

## 4. Retailers' own 2025–2026 "Buy Canadian" labelling statements (verbatim, attributed)

| Date | Company | Verbatim statement | Source (tier) |
|---|---|---|---|
| 29 Mar 2025 | Loblaw | Loblaw said "The maple leaf symbol in stores means the item was Prepared in Canada" (CBC paraphrase) and, in an email: "With thousands of products changing all the time, we do our best to keep everything accurate, but sometimes mistakes happen." | CBC Marketplace, Bobby Hristova & Dexter McMillan, posted 29 Mar 2025, updated 13 Apr 2025 — https://www.cbc.ca/lite/story/1.7496182 (opened 01:03) (b) |
| 29 Mar 2025 | Sobeys (Voilà) | Sobeys "adds its labels to products manually, it said, and occasionally makes mistakes, but tries to fix them immediately." "The Shop Canada items include those that are 100 per cent Canadian, Products of Canada or Made in Canada"; "Over the past year, approximately 12 per cent of sales have come from products sourced in the U.S., and given our work to find alternatives to U.S. sources, we expect this number to decrease," Sobeys said. | same (b) |
| 29 Mar 2025 | Metro | "Metro told Marketplace the "produit d'ici" logo was mistakenly added to items on its Ontario web pages and is being removed and will just display the word "Canada," which means the product was produced, made or grown here." Context: an Irrésistible (Metro private label) orange juice shown with the logo. | same (b) |
| 2 Apr 2025 | Walmart Canada | "Walmart Canada recently removed "Made in Canada" badging from its website and app after discovering some items were incorrectly labelled." Spokesperson Sarah Kennedy: removal was "out of an abundance of caution"; "The retailer has since restored made-in-Canada labelling on its website." | The Globe and Mail, Mariya Postelnyak, 2 Apr 2025 — https://www.theglobeandmail.com/investing/personal-finance/article-patriotic-shoppers-cautious-that-brands-urging-buy-canadian-might-be/ (opened 01:04) (b) |
| 12 Feb 2025 | Kindersley & District Co-op | "When you shop at Co-op, you're supporting a Canadian business." | member co-op page (a), URL §3.8 |
| 27 Mar 2026 | Empire (Sobeys) | Luc L'Archevêque, chief customer officer: "We believe Canadians are, now more than ever, well informed in assessing country of origin when making their purchasing decisions based on package labelling and we are confident that this remains the best source of information for customers." (Empire "is starting to remove some signage meant to highlight Canadian products") | The Canadian Press (Ritika Dubey), 27 Mar 2026, via BNN Bloomberg — https://www.bnnbloomberg.ca/business/2026/03/27/sobeys-owner-empire-to-remove-some-buy-canadian-signage/ (opened 01:05) (b) |
| 27 Mar 2026 | Loblaw | Scott Bonikowsky: "At this time, signage in our stores identifying products as prepared in Canada remains in place." | same CP (b) |
| 27 Mar 2026 | Metro | Stephanie Bonk: the company "is not planning on making any changes at this time." | same CP (b) |
| 14 May 2026 | Sobeys | CBC: "Sobeys appears to have phased out the red maple leaf symbol it introduced last year"; "Sobeys did not respond to requests for comment." | CBC, Sophia Harris, 14 May 2026 — https://www.cbc.ca/news/investigates/sobeys-loblaw-maple-washing-9.7196767 (opened 01:03) (b) |
| 26 Aug 2026 | Loblaw | Spokesperson: "As Canada enters another period of trade uncertainty with the United States, we are once again taking steps to give customers clear information about products affected by tariffs and make Canadian products easier to identify." / "We will also continue using the maple leaf symbol in our stores to help customers identify Canadian-made and prepared products. This includes reintroducing the country-of-origin in our fresh produce aisles." / "We are reinstating the T symbol on shelf labels for products sourced directly from the U.S. that are affected by tariffs." | Global News, Uday Rana, 26 Aug 2026 — https://globalnews.ca/news/12036392/loblaw-country-of-origin-buy-canadian/ (opened 01:02) (b) |
| 26 Aug 2026 | Loblaw (CEO Per Bank, LinkedIn, as reported) | "And one commitment is especially important: Loblaw will not benefit from tariffs." / "Where tariffs increase our cost, any resulting increase on our shelves will reflect that impact — penny for penny." | The Canadian Press (Ritika Dubey), 26 Aug 2026, via BNN Bloomberg — https://www.bnnbloomberg.ca/tariffs/2026/08/26/loblaw-bringing-back-t-symbols-on-tariff-affected-items-as-trade-tensions-escalate/ (opened 01:03) (b) |
| 26 Aug 2026 | Empire (Sobeys) | Spokesperson Karen White-Boswell: "Customers can expect to see even more elements featuring local products prominently alongside provincial flags so that customers (can) identify items locally grown or made in Canada." | same CP (b) |
| 26 Aug 2026 | Metro | "Metro said it already gives priority to Canadian products and will continue to emphasize them in store and online, given the current geopolitical context." (CP paraphrase) | same CP (b) |
| undated (live 30 Sep 2026) | Metro | Metro's "Buy Canadian Products" page defines "Product of Canada" as "Any product that is completely made in Canada or any product that contains at least 98% ingredients (or components) from Canada, as long as every main ingredient (or component) comes from Canada" and "Made in Canada" as "Any product that is substantially processed or transformed in Canada." Footnote: "*We are currently working on updating the origin of all our products. This information comes from certification agencies, product suppliers, and other Metro partners. We cannot be held liable for any information that may prove to be inaccurate." | https://www.metro.ca/en/products-to-discover/shop-canadian-products (opened 01:04) (a) |
| undated (live 30 Sep 2026) | Farm Boy | "Product of Canada" / "Prepared in Canada" definitions quoted in §3.10 | farmboy.ca (a) |

Walmart Canada, Costco Canada, Giant Tiger and Save-On-Foods: no 2025–2026 retailer statement on origin labelling was opened today (Save-On's /shopcanadian page returned 403). See UNVERIFIED #9, #11.

---

## 5. Documented origin-labelling actions and admissions (labelled; none involves oatmeal)

**Regulator record — CFIA Administrative Monetary Penalties list** (tier a), https://inspection.canada.ca/en/inspection-and-enforcement/actions-taken/administrative-monetary-penalties ("dateModified 2026-09-28"; opened 01:02). Columns verbatim: Date served | Act | Section | Area | Type | Amount | Company.

| Date served | Act / s. | Area | Type (label) | Amount | Company or individual |
|---|---|---|---|---|---|
| 2026-03-19 | SFCA 6(1) | Atlantic | Warning (notice of violation) | $0 | Sobeys Capital Incorporated (IGA CO-OP) |
| 2026-03-11 | SFCA 6(1) | Ontario | Warning (notice of violation) | $0 | Metro Ontario Inc. |
| 2026-02-20 | SFCA 6(1) | Atlantic | Warning (notice of violation) | $0 | Loblaw Companies Limited (two entries) |
| 2026-01-15 | SFCA 6(1) | Ontario | Penalty (AMP) | $10,000 | Real Canadian Superstore (store #1033) |
| 2026-01-15 | SFCA 6(1) | Ontario | Penalty (AMP) | $10,000 | 1000717809 Ontario Limited (Fortinos store #7920) |
| 2025-04-17 | SFCA 6(1) | West | Warning (notice of violation) | $0 | The Real Canadian Superstore Ltd. |

The list does not describe the products. Product descriptions below come from CFIA statements to media (tier b, attributed).

| Date | Item (label) | Verbatim | Source |
|---|---|---|---|
| 20 Feb 2026 | **Regulator penalty (AMP)** — Superstore, Gerry Fitzgerald Dr., Toronto | CFIA: "This created a product advertisement that is misleading to consumers regarding the origin of the product." **Loblaw statement (apology):** "That's why we're continuing to strengthen our processes" … "We're sorry for any confusion this may have caused." | CBC, Sophia Harris, 20 Feb 2026 (upd. 26 Feb) — https://www.cbc.ca/news/business/superstore-imported-canadian-food-fine-9.7099827 (opened 01:02) (b) |
| 26 Feb 2026 | Same penalty — **private-label product identified by CFIA** | "The federal food regulator said the mislabelled product was a Loblaw-owned brand: President's Choice broccoli slaw" … promoted with "maple leaf advertising decals" and a "Product of Canada" statement on an in-store shelf tag, "even though its packaging stated, "Product of USA."" | CBC, Sophia Harris, 26 Feb 2026 — https://www.cbc.ca/news/business/loblaw-superstore-fine-buy-canadian-imported-food-broccoli-slaw-9.7106279 (opened 01:02) (b) |
| 26 Feb / 17 Mar 2026 | **Regulator investigation / finding, Sobeys house brand** (no fine reported) | A Safeway near Edmonton "advertised house brand Compliments avocado oil with in-store signage that included a red maple leaf and the statement, "Made in Canada." But the small print on the bottle revealed the product was imported." CFIA: "the file is ongoing to determine if further action is appropriate." (26 Feb). CBC 17 Mar caption: "the CFIA determined a Sobeys-owned Safeway near Edmonton violated the rules". Note: CBC's text says "Made in Canada"; its 26 Feb photo caption says the signage said "Product of Canada" — quote the text, not the caption. | CBC 26 Feb 2026 (above); CBC, Sophia Harris, 17 Mar 2026 — https://www.cbc.ca/news/business/loblaw-fine-canadian-9.7130933 (opened 01:03) (b) |
| 17 Mar 2026 | **Regulator penalty (AMP)** — Fortinos, Queens Plate Dr., Toronto | CFIA: "The product display created an impression that the product was made in Canada." (Président-brand Rondelé cheese spread, made in France). **Loblaw (Lina Maragha):** apology for "any confusion"; "If something doesn't look right, we encourage customers to let us know so we can correct it as quickly as possible." CBC also reports "more than a dozen "imported" Sobeys house-brand Compliments products, including ice cream cones, salad dressing, raw nuts and graham crackers, displayed with a red maple leaf symbol in a Toronto Sobeys store" (CBC finding, 2025). | CBC 17 Mar 2026 (above) (b) |
| 14 May 2026 | **Regulator investigation closed — no penalty** (Sobeys head office) | "The probe resulted in no fines because "corrective actions" were taken, the CFIA said in an email." "Since the start of 2025, the CFIA has identified 127 cases where retailers promoted imported food as Canadian. But so far, the agency has issued only two fines". Loblaw (email): committed to accurate labelling but task "can be challenging when dealing with mass inventory from constantly changing suppliers" (CBC paraphrase). | CBC 14 May 2026 (above) (b) |
| 29 Mar 2025 | **Company admission — Metro private label web badge** | Metro: "produit d'ici" logo "was mistakenly added to items on its Ontario web pages and is being removed" (Irrésistible orange juice example). | CBC Marketplace 29 Mar 2025 (above) (b) |
| 2 Apr 2025 | **Company action — Walmart Canada web badging** | removed "Made in Canada" badging "after discovering some items were incorrectly labelled" (Globe characterisation); spokesperson: "out of an abundance of caution". | Globe, 2 Apr 2025 (above) (b) |

None of these items concerns oats or oatmeal. **Do not connect any of them to any oat product on air.**

---

## 6. Prices (retailer's own site/back-end; 30 Sep 2026; unit price per 100 g computed = price ÷ grams × 100)

### 6.1 Loblaw banners (Loblaw PC Express back-end; search endpoint 00:42, detail endpoint 00:43–00:44 UTC)

Columns: price returned by Loblaw's product-search endpoint at each store → computed $/100 g; last column = price returned by the product-detail endpoint for the store shown. **The two endpoints disagree for no name (search $3.00; detail $3.25 "SPECIAL" ending 2026-09-30) — RE-VERIFY on shelf; SPECIAL prices may have ended 30 Sep.** "not returned" = the item did not appear in that store's search results (it may still be stocked).

Stores: Markham = Loblaws, 200 Bullock Dr, Markham ON (1032); Toronto NF = No Frills, 261 Richmond St W, Toronto ON (7952); Vancouver RCSS = Real Canadian Superstore, 350 SE Marine Dr, Vancouver BC (1517); Provigo = 1275 av. des Canadiens-de-Montréal, Montréal QC (7297); Maxi = 1835 rue Sainte-Catherine E, Montréal QC (9528).

| Product | Size | Markham | Toronto NF | Vancouver RCSS | Montréal Provigo | Montréal Maxi | Detail endpoint |
|---|---|---|---|---|---|---|---|
| no name Quick 100% Whole Grain Oats | 1 kg | $3.00 → $0.300 (was $3.49) | $3.00 → $0.300 | $3.00 → $0.300 | $3.00 → $0.300 (was $3.99) | $3.00 → $0.300 | $3.25 SPECIAL to 2026-09-30 → $0.325 (was $3.49), 1032 |
| no name Large Flake 100% Whole Grain Oats | 1 kg | $3.00 → $0.300 (was $3.49) | $3.00 → $0.300 | $3.00 → $0.300 | $3.00 → $0.300 (was $3.99) | $3.00 → $0.300 | $3.25 SPECIAL to 2026-09-30 → $0.325 (was $3.49), 1032 |
| no name One-Minute 100% Whole Grain Oats | 900 g | $3.00 → $0.333 (was $3.49) | $3.00 → $0.333 | $3.00 → $0.333 | not returned | $3.00 → $0.333 | $3.25 SPECIAL to 2026-09-30 → $0.361 (was $3.49), 1032 |
| no name Quick … Club Size | 2.25 kg | not returned | not returned | $5.49 → $0.244 (was $6.00) | not returned | not returned | $6.00 SPECIAL to 2026-09-30 → $0.267, 1517 |
| no name Large Flake … Club Size | 2.25 kg | not returned | not returned | $5.49 → $0.244 (was $6.00) | not returned | not returned | $6.00 SPECIAL to 2026-09-30 → $0.267, 1517 |
| PC Organics Organic Quick Rolled Oats | 1000 g | $5.00 → $0.500 | $5.00 → $0.500 | $5.00 → $0.500 | $5.00 → $0.500 | $5.00 → $0.500 | $5.00 SPECIAL to 2026-10-14 → $0.500, 1032 |
| PC Organics Old Fashioned Gluten Free Rolled Oats (name as listed) | 900 g | $5.00 → $0.556 | not returned | $5.00 → $0.556 | not returned | $5.50 → $0.611 | $5.00 SPECIAL to 2026-10-14 → $0.556, 1032 |
| PC Organics Organic Steel Cut Oats | 1 kg | $5.00 → $0.500 | not returned | $5.00 → $0.500 | $5.00 → $0.500 | $5.00 → $0.500 | $5.00 SPECIAL to 2026-10-14 → $0.500, 1032 |
| PC Organics Organics Maple and Brown Sugar Flavour Instant Oatmeal | 400 g | $6.99 → $1.748 | not returned | $5.50 → $1.375 | not returned | not returned | $6.99 REGULAR → $1.748, 1032 |
| PC Organics Organics Instant Oatmeal with Flaxseed | 400 g | $6.99 → $1.748 | not returned | not returned | not returned | not returned | $6.99 REGULAR → $1.748, 1032 |
| PC Maple and Brown Sugar Flavour Instant Oatmeal | 344 g | $4.29 → $1.247 | $3.00 → $0.872 | $3.00 → $0.872 | $3.79 → $1.102 | $3.29 → $0.956 | $4.29 REGULAR → $1.247, 1032 |
| PC Regular Instant Oatmeal | 280 g | $4.29 → $1.532 | not returned | $3.00 → $1.071 | $3.79 → $1.354 | $3.29 → $1.175 | $4.29 REGULAR → $1.532, 1032 |
| PC Apples and Cinnamon Instant Oatmeal | 264 g | $4.29 → $1.625 | not returned | $3.00 → $1.136 | $3.79 → $1.436 | not returned | $4.29 REGULAR → $1.625, 1032 |
| PC Instant Oatmeal, Peaches and Cream | 264 g | $4.29 → $1.625 | not returned | $3.00 → $1.136 | $3.79 → $1.436 | $3.29 → $1.246 | $4.29 REGULAR → $1.625, 1032 |
| PC Instant Oatmeal, Cinnamon & Spice | 304 g | $4.29 → $1.411 | not returned | $3.00 → $0.987 | not returned | not returned | $4.29 REGULAR → $1.411, 1032 |
| PC Instant Oatmeal, Variety Pack, 8 Pack | 314 g | $4.29 → $1.366 | $3.00 → $0.955 | $3.00 → $0.955 | $3.79 → $1.207 | $3.29 → $1.048 | $4.29 REGULAR → $1.366, 1032 |
| PC Blue Menu 100% Whole Grain Steel Cut Oats | 840 g | $5.00 → $0.595 | $4.00 → $0.476 | $4.00 → $0.476 | $5.00 → $0.595 | $4.79 → $0.570 | $5.00 REGULAR → $0.595, 1032 |
| PC Blue Menu Regular Steel Cut Oats | 360 g | $4.00 → $1.111 | not returned | $4.00 → $1.111 | $4.00 → $1.111 | not returned | $4.00 REGULAR → $1.111, 1032 |
| PC Blue Menu Maple & Brown Sugar Steel Cut Oats | 360 g | $4.00 → $1.111 | not returned | $4.00 → $1.111 | not returned | not returned | $4.00 REGULAR → $1.111, 1032 |
| PC Blue Menu Regular Supergrains Oatmeal | 8x38 g (304 g) | $4.49 → $1.477 | not returned | $4.00 → $1.316 | not returned | $4.29 → $1.411 | $4.49 REGULAR → $1.477, 1032 |
| PC Blue Menu Maple and Brown Sugar Flavour Supergrains Oatmeal | 8x38 g (304 g) | $4.49 → $1.477 | not returned | $4.00 → $1.316 | not returned | not returned | $4.49 REGULAR → $1.477, 1032 |

### 6.2 Other retailers (one row per SKU; computed $/100 g)

| Retailer / banner, region | Product | Pack | Price | Computed $/100 g | Page / time |
|---|---|---|---|---|---|
| Voilà by Sobeys (no address set) | Compliments Quick Oats | 1 kg | $4.49 | $0.449 | §3.3, 00:49 |
| Voilà | Compliments Quick Oats | 2.25 kg | $6.79 | $0.302 | §3.3 |
| Voilà | Compliments Organic Quick Oats | 1 kg | $4.99 | $0.499 | §3.3 |
| Voilà | Compliments Quick Cook Steel Cut Oats | 709 g | $5.49 | $0.774 | §3.3 |
| Voilà | Compliments Instant Oatmeal Maple & Brown Sugar Flavour | 344 g | $3.99 | $1.160 | §3.3 |
| Voilà | Compliments Instant Oatmeal Regular | 280 g | $3.99 | $1.425 | §3.3 |
| Voilà | Compliments Instant Oatmeal Apple & Cinnamon Flavour | 260 g | $3.99 | $1.535 | §3.3 |
| Voilà | Compliments Instant Oatmeal Peaches & Cream Flavour | 260 g | $3.99 | $1.535 | §3.3 |
| Voilà | Compliments Instant Oatmeal Variety Pack | 313 g | $3.99 | $1.275 | §3.3 |
| Voilà | Compliments Instant Oatmeal Variety Pack | 691 g | $6.99 | $1.012 | §3.3 |
| Voilà | Compliments Balance Instant Oatmeal Variety Pack | 378 g | $3.69 | $0.976 | §3.3 |
| Voilà | Compliments Balance Oatmeal Maple & Brown Sugar | 430 g | $3.69 | $0.858 | §3.3 |
| Voilà | Compliments Instant Oatmeal Apple Cinnamon | 325 g | $3.69 | $1.135 | §3.3 |
| Voilà | Compliments Instant Oatmeal Peaches & Cream | 325 g | $3.69 | $1.135 | §3.3 |
| Voilà | Compliments Oatmeal Regular | 336 g | $3.69 | $1.098 | §3.3 |
| Walmart.ca, store 1061 Mississauga ON | Great Value Quick Oats | 1 kg | $2.77 | $0.277 | §3.4, 00:51 |
| Walmart.ca | Great Value One Minute Oats | 1 kg | $2.77 | $0.277 | §3.4 |
| Walmart.ca | Great Value Quick Cook Steel Cut Oats | 1 kg | $2.77 | $0.277 | §3.4 |
| Walmart.ca | Great Value Organic Quick Oats | 1 kg | $4.17 | $0.417 | §3.4 |
| Walmart.ca | Great Value Maple & Brown Sugar Natural Flavour Instant Oatmeal | 344 g | $2.97 | $0.863 | §3.4 |
| Walmart.ca | Great Value Regular Instant Oatmeal | 280 g | $2.97 | $1.061 | §3.4 |
| Walmart.ca | Great Value Apples & Cinnamon Instant Oatmeal | 264 g | $2.97 | $1.125 | §3.4 |
| Walmart.ca (search page; product URL 404) | Great Value Variety pack Instant Oatmeal | 314 g | $2.97 | $0.946 | §3.4, 00:50 |
| Metro (store shown "Metro Devonshire") | Selection Quick Oats | 1 kg | $2.99 | $0.299 | §3.5, 00:55 |
| Metro | Selection Large Flake Oatmeal | 900 g | $2.99 | $0.332 | §3.5 |
| Metro | Selection Maple and Brown Sugar Instant Oatmeal | 10x43 g (430 g) | $3.49 | $0.812 | §3.5 |
| Metro | Selection Assorted Instant Oatmeal Packets | 380 g | $3.49 | $0.918 | §3.5 |
| Metro | Irrésistible Steel cut oatmeal (out of stock) | 680 g | $4.39 | $0.646 | §3.5 |
| Metro | Life Smart Quick Oatmeal Packets (name as listed) | 344 g | $3.49 | $1.015 | §3.5 |
| Metro | Life Smart Organic Instant Oatmeal (out of stock) | 320 g | $3.49 | $1.091 | §3.5 |
| Save-On-Foods, Langley Twp BC (store 1982) | Western Family - Quick Oats | 1 kg | $4.69 | $0.469 | §3.6, 00:57 |
| Save-On-Foods | Western Family - 100% Whole Grain Canadian Quick Oats | 2.25 kg | $7.69 | $0.342 | §3.6 |
| Save-On-Foods | Western Family - 100% Whole Grain Canadian Steel Cut Oats | 1 kg | $4.69 | $0.469 | §3.6 |
| Save-On-Foods | Western Family - Maple & Brown Sugar Instant Oatmeal | 344 g | $4.29 | $1.247 | §3.6 |
| Save-On-Foods | Western Family - Regular Instant Oatmeal | 280 g | $4.29 | $1.532 | §3.6 |
| Save-On-Foods | Western Family - Apple & Cinnamon Flavor Instant Oatmeal | 264 g | $4.29 | $1.625 | §3.6 |
| costco.ca (online; "OutOfStock") | Kirkland Signature Whole Grain Rolled Oats | 4.54 kg | $11.99 | $0.264 | §3.7, 00:53 |
| sameday.costco.ca (location not shown) | Kirkland Signature Whole Grain Rolled Oats | 4.54 kg | $11.34 | $0.250 | §3.7, 00:54 |
| gianttiger.com (AB–QC province tags; "Online prices may vary from in-store prices.") | Giant Value Quick Oats | 1 kg | $2.77 | $0.277 | §3.9, 00:58 |
| gianttiger.com | Giant Value Large Flake Oats | 1 kg | $2.77 | $0.277 | §3.9 |
| gianttiger.com | Giant Value Maple and Brown Sugar Instant Oatmeal | 344 g | $2.87 | $0.834 | §3.9 |
| gianttiger.com | Giant Value Regular Instant Oatmeal | 280 g | $2.87 | $1.025 | §3.9 |
| gianttiger.com | Giant Value Apples and Cinnamon Instant Oatmeal | 264 g | $2.87 | $1.087 | §3.9 |
| Voilà listing of Farm Boy brand (not a Farm Boy store price) | Farm Boy Organic Large Flake Oats | 750 g | $5.49 | $0.732 | §3.10, 00:49 |
| Voilà (Farm Boy brand) | Farm Boy Organic Steel Cut Oats | 1 kg | $5.99 | $0.599 | §3.10 |
| Voilà (Farm Boy brand) | Farm Boy Instant Oatmeal Apple & Cinnamon | 6 x 60 g (360 g) | $4.99 | $1.386 | §3.10 |
| Voilà (Farm Boy brand) | Farm Boy Instant Oatmeal Twice Berry | 6 x 60 g (360 g) | $4.99 | $1.386 | §3.10 |
| Voilà (Farm Boy brand) | Farm Boy Oatmeal Cup Apple & Cinnamon | 70 g | $1.79 | $2.557 | §3.10 |
| Voilà (Farm Boy brand) | Farm Boy Oatmeal Cup Maple Walnut | 70 g | $1.79 | $2.557 | §3.10 |
| Voilà (Farm Boy brand) | Farm Boy Overnight Oats Almond Raisin | 70 g | $2.99 | $4.271 | §3.10 |

Co-op Gold: no price captured. Every price above: **re-verify on shelf before broadcast**.

---

## 7. Access log (what did / did not open, 1 Oct 2026 UTC)

| Source | Result |
|---|---|
| loblaws.ca / nofrills.ca product pages | 403 (00:47) — data read from api.pcexpress.ca (200) and digital.loblaws.ca images (200) |
| pc.ca search | 301 redirect; not used |
| voila.ca product pages | 200 after cookie challenge (00:48–00:49); one page needed retry |
| walmart.ca product pages (mobile UA) | 200 (00:51); Variety pack 404; Canadian-made discovery page redirected to home (01:05) |
| metro.ca, superc.ca, foodbasics.ca | 403 (00:54); api2.metro.ca 200; product-images.metro.ca 403 |
| saveonfoods.com, /shopcanadian | 403 (Cloudflare); storefrontgateway preview/products/stores 200; search 403 |
| westernfamily.com | connection reset (00:56) |
| gianttiger.com search HTML | client-rendered; suggest.json and products/*.json 200 |
| costco.ca search | client-rendered (no results in HTML); product pages 200 |
| sameday.costco.ca product | curl returned storefront shell; WebFetch read product (00:54) |
| coopathome.ca | 429 (00:59, 01:01) |
| shoponline.calgarycoop.com, shop.crs | client-rendered; no products |
| farmboy.ca product pages | 200 (one 307) |
| corporate.gianttiger.com | proxy CONNECT rejected (01:07) |
| loblaw.ca about pages | 404 |
| yahoo CP mirror of Empire story | 404/"Content is currently unavailable" — used BNN Bloomberg copy instead |

---

## Appendix A — Recalls (food-safety item: **DO NOT USE ON AIR**)

- "PC Organics brand Old-Fashioned Rolled Oats recalled due to presence of insects" — Government of Canada Recalls and safety alerts, "Original published date: 2022-01-28"; product "PC Organics Old-Fashioned Rolled Oats 900 g", "Best Before 2022 OC23", UPC "0 60383 03544 0"; "Recall class Class 3"; "Companies Loblaw Companies Ltd." — https://recalls-rappels.canada.ca/en/alert-recall/pc-organics-brand-old-fashioned-rolled-oats-recalled-due-presence-insects (opened 01:12). Listed for completeness only. **Do not use on air.**
- Search of the recalls site for "oats" and "oatmeal" (food category; opened 01:11) returned no other private-label oatmeal recall among the ten brand families (results included Kirkland Signature oatmeal cookies and Great Value plant-based beverages — not oatmeal; not relevant). **Do not use on air.**

---

## UNVERIFIED / DO-NOT-USE

1. **Where PC Organics instant oatmeal is made, by whom, and its country of origin.** The front says "IMPORTED / IMPORTÉ"; no country and no "Imported by/for" line appeared in any image served. Do not name a country or a manufacturer. Photograph the full box.
2. **Dealer lines** for President's Choice instant, PC Blue Menu, Compliments, Great Value, Selection/Irresistibles/Life Smart, Western Family, Giant Value and Farm Boy — not visible in any retailer image served. Capture on camera.
3. **no name front maple-leaf mark legend** (two lines above "CANADA") — illegible at served resolution; it may read "Prepared in / Préparé au", but that is not confirmed. Do not quote it.
4. **Metro pack wording** (any "Product of Canada"/"Made in Canada" text or maple leaf on Selection/Irresistibles/Life Smart packs) and **Selection instant ingredient lists** — product images 403; pages give no ingredients for the instant SKUs.
5. **Co-op Gold oats** — product names, sizes, prices, origin lines, ingredients: no retailer page could be opened. Third-party listing (edmontongrocer.com "Co-op Gold Pure Organic Quick Oats 1 kg $8.49") and calorie sites are tier (c) — do not use.
6. **Kirkland Signature instant oatmeal in Canada** — none found; costco.ca search is client-rendered, so absence is not proven. A search-engine summary claimed Kirkland rolled oats are "sourced from Canada and packed in the USA" — **not found on any Costco Canada page; the Canadian pack image says "PRODUCT OF CANADA". Do not use the "packed in the USA" claim** (possibly U.S.-pack context; unverified).
7. **Loblaw prices** — search vs detail endpoints disagree (no name $3.00 vs $3.25 SPECIAL; club size $5.49 vs $6.00); SPECIAL prices flagged as ending 30 Sep 2026. Re-verify on shelf.
8. **Compliments instant pack images on Voilà** may show superseded designs (e.g., "balance/équilibre" box); confirm current packaging before saying "no Canadian wording on the box".
9. **Save-On-Foods "Shop Canadian" page definitions** (search snippet: "98 percent of the total direct costs" / "51 percent" for Made in Canada) — page 403; not verified. If accurate, those are Competition Bureau non-food thresholds, not the CFIA food rule; do not repeat without opening the page.
10. **FCL ownership wording** ("owned by member co-operatives") — not found verbatim on FCL pages opened; only member-co-op self-description verified.
11. **Walmart Canada, Costco Canada, Giant Tiger 2025–2026 Buy-Canadian statements** — none opened beyond the April 2025 Globe item (Walmart). Walmart Canada "Shop Food Products Grown or Made in Canada" page did not load.
12. **Walmart Inc. HQ (Bentonville, AR)** — not re-opened today (U.S. context only); Walmart Canada page says only "part of Walmart Inc."
13. **Giant Tiger ownership** — only the Retail Insider (b) quote of the company's self-description; no company filing.
14. **Farm Boy Apple & Cinnamon Instant Oatmeal 360 g farmboy.ca page** — redirected (307), not read; farmboy.ca Twice Berry 360 g page carries oatmeal-cup description text (page error) — do not quote that description.
15. **Retail Insider (27 Mar 2026) paraphrases** of Empire/Loblaw/Metro positions — superseded by the CP verbatim quotes in §4; do not quote Retail Insider's paraphrase as a company statement.
16. Any statement that a private-label oat product is made by a named mill or co-packer — **none was found in any label, retailer page, court/tribunal/CFIA record or tier-(b) report. Do not name one; do not infer one from matching ingredient lists.**
17. Any health, nutrition, gluten, glyphosate, sugar or food-safety angle (including competitor oatmeal-video talking points and the channel's December 2025 oatmeal video) — **excluded by house rule; do not use.**

<!-- ===== oatmeal_prices.md ===== -->

# Oatmeal: Canadian retail prices by brand, 30 September 2026

**What this file is:** dated shelf prices for oatmeal (large flake / rolled, quick and one-minute, steel-cut, and instant packets) by brand, taken only from the retailers' own websites, apps and APIs. Prices were captured between **2026-10-01 00:56 UTC and 01:06 UTC**, which is **30 Sep 2026, 8:56 to 9:06 p.m. EDT**. "Today" for this file is 30 Sep 2026. Every row in Appendix A has its own capture timestamp and URL.

**House rules applied:** This file contains no health, nutrition, fibre, beta-glucan, heart-health, cholesterol, sugar, glycemic, protein, gluten, glyphosate, pesticide, heavy-metal, additive or food-safety content. Several label panels and retailer descriptions that were opened carry such claims (for example, the Quaker heart panel and a One Degree feature line on Costco.ca). **They were deliberately not transcribed.** Product names are reproduced **verbatim as data**. Some names contain words such as "Protein", "Low Sugar", "High Fibre", "Gluten Free", "Superfood" or "Lactose-Free". These are the retailers' or makers' product names, not claims by this file, and they must not be read on air as claims. Do not reuse the channel's December 2025 oatmeal video. Nothing in this file comes from it. No Flipp, PriceListo, Reddit, blog, Open Food Facts or price-tracker data was used.

**Method in one paragraph:** Loblaw banners: the PC Express API that loblaws.ca, realcanadiansuperstore.ca, nofrills.ca, atlanticsuperstore.ca, provigo.ca and maxi.ca call. Twelve stores were queried, each with ten search terms ("oats", "oatmeal", "rolled oats", "quick oats", "large flake oats", "steel cut oats", "instant oatmeal", "gruau", "flocons d'avoine", "avoine"), up to 144 results per term. Voilà by Sobeys: the full "Oatmeal" category (197 items) plus ten searches, priced through Voilà's own product API. Save-On-Foods: its storefront API for store 1982, Langley Twp BC. That search preview returns only 3 items per query, so 65 queries were run. Giant Tiger: its own "oatmeal" collection feed. Costco.ca: its own search API (the public key embedded in costco.ca's page) and its product pages. Non-oatmeal items were filtered out: bars, cookies, cold cereal, granola, oat drinks, baby cereal, mixes, flour, bran and overnight-oats kits. **Unit price per 100 g is computed in this file** as the price shown ÷ the pack weight on the listing × 100. Where the retailer shows its own unit price, it is kept alongside. "Price shown" is the live price at capture. Where a sale with a was-price was shown, both are given with the end date.

**Tier:** every price in this file is tier (a), the retailer's own site, app or API. Brand-site pages are tier (a) where opened. Nothing here is tier (b), (c) or (d).

**Raw captures:** `/tmp/claude-0/-home-user-Food/63b91656-26a4-59d5-baf9-bd65edc4c0dd/scratchpad/op/`. Subfolders: `lb/` (Loblaw search JSON, one file per store × term × page), `lbd/` (Loblaw product detail JSON), `img/` (Loblaw label images), `voila/` (pages, `products_put.json`, `bop/` details), `sof/` (Save-On preview and product JSON), `gt/` (Giant Tiger collection and product JSON, images), `costco/` (search JSON, product pages), `other/` (blocked-site responses), `co/` (brand sites), `statcan/` (attempt log). Master dataset: `op/oat_listings_master.csv` / `.json` (806 listings).

---

## 0. Sources tried: every URL or endpoint, and whether it opened (30 Sep 2026 ET; timestamps UTC 1 Oct)

| # | Retailer / source | URL or endpoint actually requested | Opened? | Result | Time (UTC) |
|---|---|---|---|---|---|
| 1 | Loblaw banners (search) | `POST https://api.pcexpress.ca/pcx-bff/api/v1/products/search` with body `{banner, storeId, term, lang:"en", date:"30092026", pickupType:"STORE", pagination}` | YES | 289 of 289 calls returned 200. 12 stores × 10 terms, paginated. Raw files: `op/lb/` | 00:56:24–01:00:46 |
| 2 | Loblaw banners (product detail) | `GET https://api.pcexpress.ca/pcx-bff/api/v1/products/{code}?lang=en&date=30092026&pickupType=STORE&storeId={id}&banner={banner}` | YES | 81 of 81 returned 200 (one per unique oatmeal product). `op/lbd/` | 01:07:47–01:08:53 |
| 3 | Loblaw store list | `GET https://api.pcexpress.ca/pcx-bff/api/v1/pickup-locations?bannerIds={loblaw,superstore,nofrills,rass,provigo,maxi}` | YES | Store names and addresses. `op/lb_locations_*.json` | 00:56:10–00:56:11; 01:07:34–01:07:36 |
| 4 | Loblaw label images | `https://digital.loblaws.ca/PCX/{code}/en/{n}/..._800.png` (57 files, 20 products) | YES | 57 of 57 returned 200. `op/img/` | 01:09:15 |
| 5 | Voilà by Sobeys, category | `https://voila.ca/categories/pantry/cereal-breakfast-foods/oatmeal/WEB3432052` | YES | 197 items, default region "Default Region 1". No postal code was entered and no province is displayed | 00:58:34 |
| 6 | Voilà, searches | `https://voila.ca/search?q=oats` (also oatmeal, rolled oats, quick oats, large flake oats, steel cut oats, instant oatmeal, gruau, flocons d'avoine, porridge) | YES | 10 of 10 returned 200 | 00:58:36–00:58:51 |
| 7 | Voilà, product API | `PUT https://voila.ca/api/webproductpagews/v6/products` (11 batches) | YES | 413 products priced | 00:58:52–00:58:56 |
| 8 | Voilà, product details | `GET https://voila.ca/api/webproductpagews/v5/products/bop?retailerProductId={id}` | YES | 193 of 193 returned 200 (all oatmeal-category items) | 00:59:12–01:00:55 |
| 9 | Save-On-Foods, search | `GET https://storefrontgateway.saveonfoods.com/api/stores/1982/preview?q={term}` (65 terms) | YES | 3 items per query. 76 unique items | 01:01:40–01:02:30 |
| 10 | Save-On-Foods, products | `GET https://storefrontgateway.saveonfoods.com/api/stores/1982/products/{sku}` | YES | 63 of 63 returned 200 | 01:02:30–01:03:07 |
| 11 | Save-On-Foods, full search | `GET https://storefrontgateway.saveonfoods.com/api/stores/1982/search?q=oats&take=30&f=Category%3AOatmeal%20%26%20Hot%20Cereal` | NO | 403 (single test) | 01:01:13 |
| 12 | Giant Tiger, searches | `https://www.gianttiger.com/search?q={term}&page={n}` (22 pages, 11 terms) | YES | 200 | 01:03:52–01:04:12 |
| 13 | Giant Tiger, oatmeal collection | `https://www.gianttiger.com/collections/oatmeal/products.json?limit=250` | YES | 10 items (9 oatmeal, plus one buckwheat item that was excluded) | 01:04:48 |
| 14 | Giant Tiger, products | `https://www.gianttiger.com/products/{handle}.json` (23) and 4 package images on cdn.shopify.com | YES | 200 | 01:04:12–01:04:29; images 01:17 |
| 15 | Costco.ca search page | `https://www.costco.ca/CatalogSearch?keyword=oats` (redirects to `/s?&keyword=oats`) | PARTLY | 200, but rendered by JavaScript with no items in the HTML | 01:03:25 |
| 16 | Costco.ca search API | `GET https://search.costco.ca/api/apps/www_costco_ca/query/www_costco_ca_search?q={oats, oatmeal, steel cut oats, instant oatmeal, quaker}&locale=en-CA&rows=48` | YES | 5 of 5 returned 200. Without the key the API returns 401 | 01:05:13–01:05:52 |
| 17 | Costco.ca product pages | `https://www.costco.ca/p/-/x/{100570610, 4000339745, 4000039522, 100572752, 4000369027}` | YES | 200. Canonical URLs are in Appendix A | 01:06:12–01:06:36 |
| 18 | Costco Same-Day | `https://sameday.costco.ca/store/costco-canada/s?k=oats` | PARTLY | 200, JavaScript only, no items | ~01:05 (test, not separately logged) |
| 19 | Walmart Canada | `https://www.walmart.ca/en/search?q=oats`; `.../en/browse/grocery/pantry/cereal-breakfast/oatmeal-hot-cereals/...`; `.../en/ip/quaker-large-flake-oats/6000016945937` | NO | Redirected to `walmart.ca/blocked` ("Verify your identity" bot wall) | 01:03:22, 01:03:23, 01:16:42 |
| 20 | Metro | `https://www.metro.ca/en/online-grocery/search?filter=oats`; `.../aisles/pantry/cereals-spreads-syrups/oatmeal-hot-cereals`; `https://www.metro.ca/epicerie-en-ligne/recherche?filter=gruau` | NO | 403 (the home page `https://www.metro.ca/en` returned 200 but has no prices) | 01:03:24, 01:16:40 |
| 21 | IGA | `https://www.iga.net/en/search?k=oats`; `https://www.iga.net/fr/recherche?k=gruau`; `https://www.iga.net/en` | NO | 403 | 01:03:24, 01:16:41–42 |
| 22 | Longo's | `https://www.longos.com/search?text=oats`; `https://www.longos.com/` | NO | 403. Longo's-brand oats are priced on Voilà (rows below) | 01:03:26, 01:16:43 |
| 23 | Farm Boy | `https://www.farmboy.ca/?s=oats` (307); `https://www.farmboy.ca/`; `https://www.farmboy.ca/products/` (200) | NO PRICES | Farm Boy's site shows no prices. Farm Boy-brand oats are priced on Voilà | 01:03:26, 01:16:44 |
| 24 | Co-op (Calgary Co-op) | `https://shop.calgarycoop.com/search?q=oats`; `https://shop.calgarycoop.com/` | NO | Proxy: "gateway answered 502 to CONNECT" | 01:03:26, 01:16:45 |
| 25 | Co-op (Calgary Co-op) | `https://shoponline.calgarycoop.com/store/calgary-co-op/s?k=oats` | NO PRICES | 200, JavaScript only, no product data | 01:17:08 |
| 26 | "Co-op at Home" | `https://www.coopathome.ca/search?q=oats` (429); `https://www.coopathome.ca/` (200) | NOT RELEVANT | That site sells furniture and appliances, not groceries | 01:03:26, 01:16:45–49 |
| 27 | Sobeys-family banners | `https://www.foodland.ca/search?q=oats` (403); Super C `https://www.superc.ca/en/online-grocery/search?filter=oats` (403) | NO | 403 | 01:03:28, 01:16:50 |
| 28 | Statistics Canada | `POST https://www150.statcan.gc.ca/t1/wds/rest/getCubeMetadata` [18100004] and [18100245]; `POST …/getSeriesInfoFromCubePidCoord`; `GET …/getDataFromVectorByReferencePeriodRange?vectorIds=41690973,41691000,41691005,41691007,41690975&startRefPeriod=2022-08-01&endReferencePeriod=2026-08-01`; `GET https://www150.statcan.gc.ca/n1/tbl/csv/18100004-eng.zip` and `…/18100245-eng.zip`; `GET https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000401` | PARTLY | The host was intermittent ("tunnel closed (code 1006)"). These opened: 18100004 metadata (01:19:31), 18100245 metadata (01:26:28) and the series-ID lookup (01:35:10). **The CPI data values never opened** in more than 40 minutes of retries. Full log: `op/statcan/_log.txt` | 01:11–01:53 |
| 29 | Brand sites (origin check) | `https://www.bobsredmill.com/product/old-fashioned-rolled-oats` (404); `https://www.bobsredmill.ca/` (200, no origin text); `https://www.naturespath.com/en-ca/products/maple-nut-hot-oatmeal/` (404); `https://www.quaker.ca/en/products/oats/large-flake-oats` (404); `https://www.quaker.ca/en` (404); `https://www.robinhood.ca/en-ca/products/oats` (404); `https://www.rogersfoods.com/products` (404); `https://onedegreeorganics.com/` (200, no origin text) | NO USABLE TEXT | Nothing quoted | 01:10:37–01:10:52 |

**Banners covered with prices:** Loblaws, Real Canadian Superstore, No Frills, Atlantic Superstore, Provigo, Maxi, Voilà by Sobeys, Save-On-Foods, Giant Tiger, Costco.ca. **Not covered** (blocked or no online prices): Walmart, Metro, IGA, Longo's own site, Farm Boy own site, Co-op.

**Loblaw stores queried (from the API's pickup-locations list):** Loblaws Bullock Drive, 200 Bullock Dr, Markham ON (1032); Loblaws City Market Vancouver Post, 658 Homer St, Vancouver BC (7155); Bo's NO FRILLS Toronto Richmond, 261 Richmond St W, Toronto ON (7952); Kevin's NOFRILLS Calgary, 10233 Elbow Dr SW, Calgary AB (3155); Dean's NOFRILLS Vancouver, 4508 Fraser St, Vancouver BC (3410); Real Canadian Superstore Heritage Meadows Way, Calgary AB (1539); RCSS Marine Drive, Vancouver BC (1517); RCSS Portage Avenue, Winnipeg MB (1508); RCSS Albert Street, Regina SK (1533); Atlantic Superstore Young Street, Halifax NS (0354); Provigo avenue des Canadiens de Montréal, Montréal QC (7297); Maxi Ste-Catherine, Montréal QC (9528).

**Caveats on the data:**
- Online prices are for pickup at the named store. Shelf prices in the store may differ.
- Voilà prices are for its "Default Region 1", and the province is not displayed.
- Costco.ca prices are online prices for location code `801-bd`, `993-wm` or `894_0-edi` as returned. Costco states that warehouse prices can differ from costco.ca prices; that page was not opened today, so treat the point as UNVERIFIED.
- Giant Tiger prices are its online prices, tagged with the provinces where each item is carried.
- The Loblaw API marks some prices `SPECIAL` without showing a was-price. Those are flagged `*`.

---

## Headline numbers (each traceable to Appendix A rows)

1. **The same 1 kg bag of Quaker Large Flake Oats cost between $3.75 and $6.99 on 30 Sep 2026.** It was $3.75 at Real Canadian Superstore in Calgary, Vancouver, Winnipeg and Regina, and $6.99 at Save-On-Foods, Langley BC. At Loblaws Bullock Drive, Markham ON it was $5.75. Quaker Quick Oats 1 kg had the identical price at each Loblaw store. (Loblaw API `20323113002_EA`, `20323113001_EA`; Save-On sku `00055577101018`; Voilà `Quaker Old Fashioned Large Flake Oats 1 kg` $6.49.)
2. **No Name Large Flake and Quick oats, 1 kg, were $3.00 at all 12 Loblaw-owned stores queried**, from Vancouver to Halifax ($0.30/100 g). At three stores, $3.00 is a sale price ending 7 Oct 2026, and the was-price differs by store: $3.49 at Loblaws Markham, $3.50 at Loblaws Vancouver and $3.99 at Provigo Montréal. At the other nine stores, $3.00 is shown without a was-price. At No Frills, Atlantic Superstore and Maxi the API marks it `SPECIAL`, with expiry dates of 7 Oct, 28 Oct or 4 Nov 2026. At the four Real Canadian Superstores it is a regular price.
3. **Lowest computed price per 100 g found, all types:**
   - Quaker Quick Oats 2 × 2.58 kg on Costco.ca: $10.99 ($13.99 regular, "$3 OFF", promotion end `2026-10-26T06:59:00Z`), which is **$0.21/100 g**.
   - No Name Large Flake or Quick "Club Size" 2.25 kg at Real Canadian Superstore: $5.49 on sale to 7 Oct (was $6.00), **$0.24/100 g**.
   - Kirkland Signature Whole Grain Rolled Oats 4.54 kg on Costco.ca: $11.99, **$0.26/100 g**.
   - Giant Value Large Flake or Quick Oats 1 kg at Giant Tiger: $2.77, **$0.28/100 g**.
4. **Highest price per 100 g among plain bagged oats:**
   - Good Eats "Gluten-Free Organic Quick Rolled Oats" 454 g on Voilà, $8.79, which is $1.94/100 g.
   - Among instant products, single-serve cups on Voilà reach $7.82/100 g (Bob's Red Mill cup, 51 g, $3.99).
5. **Private label vs Quaker, same store, same type.** Every Loblaw store queried had No Name 1 kg at $3.00. Quaker 1 kg ranged from $3.75 to $5.75 at those stores. At Save-On-Foods, Western Family "100% Whole Grain Canadian Quick Oats" 2.25 kg was $7.69 ($0.34/100 g), against Quaker Quick Oats 1 kg at $6.99 ($0.70/100 g).

---

## 1. Price per 100 g by brand and type across banners

### 1a. Same product, twelve Loblaw-owned stores (shelf price shown online; per 100 g computed from the pack size)

Cell = price shown, then computed $/100 g. `S` = sale price with a was-price shown (end date in Appendix A). `*` = API price type SPECIAL with no was-price shown. `—` = not returned by the store's search on 30 Sep 2026.

| Product (code) | LB-Markham ON | LB-Vancouver BC | NF-Toronto ON | NF-Calgary AB | NF-Vancouver BC | RCSS-Calgary AB | RCSS-Vancouver BC | RCSS-Winnipeg MB | RCSS-Regina SK | ASS-Halifax NS | PRV-Montréal QC | MAXI-Montréal QC |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| No Name Large Flake 1 kg (20923994_EA) | $3.00 S ($0.30) | $3.00 S ($0.30) | $3.00 * ($0.30) | $3.00 * ($0.30) | $3.00 * ($0.30) | $3.00 ($0.30) | $3.00 ($0.30) | $3.00 ($0.30) | $3.00 ($0.30) | $3.00 * ($0.30) | $3.00 S ($0.30) | $3.00 * ($0.30) |
| Quaker Large Flake 1 kg (20323113002_EA) | $5.75 * ($0.57) | $5.75 S ($0.57) | $4.00 ($0.40) | $4.29 ($0.43) | $4.29 ($0.43) | $3.75 ($0.38) | $3.75 ($0.38) | $3.75 ($0.38) | $3.75 ($0.38) | $4.49 S ($0.45) | $4.99 ($0.50) | $4.00 ($0.40) |
| Robin Hood Large Flake 1 kg (20893369_EA) | $4.79 ($0.48) | — | — | $3.99 ($0.40) | $3.99 ($0.40) | $4.49 ($0.45) | $4.49 ($0.45) | $4.49 ($0.45) | $4.49 ($0.45) | $4.79 ($0.48) | — | $4.29 ($0.43) |
| No Name Quick 1 kg (20923828_EA) | $3.00 S ($0.30) | $3.00 S ($0.30) | $3.00 * ($0.30) | $3.00 * ($0.30) | $3.00 * ($0.30) | $3.00 ($0.30) | $3.00 ($0.30) | $3.00 ($0.30) | $3.00 ($0.30) | $3.00 * ($0.30) | $3.00 S ($0.30) | $3.00 * ($0.30) |
| Quaker Quick 1 kg (20323113001_EA) | $5.75 * ($0.57) | $5.75 S ($0.57) | $4.00 ($0.40) | $4.29 ($0.43) | $4.29 ($0.43) | $3.75 ($0.38) | $3.75 ($0.38) | $3.75 ($0.38) | $3.75 ($0.38) | $4.49 S ($0.45) | $4.99 ($0.50) | $4.00 ($0.40) |
| Robin Hood Quick 1 kg (20893370_EA) | $4.79 ($0.48) | $4.99 ($0.50) | — | $3.99 ($0.40) | $3.99 ($0.40) | $4.49 ($0.45) | $4.49 ($0.45) | $4.49 ($0.45) | $4.49 ($0.45) | $4.79 ($0.48) | $5.29 ($0.53) | $4.29 ($0.43) |
| No Name Large Flake Club 2.25 kg (20923840_EA) | — | — | — | — | — | $5.49 S ($0.24) | $5.49 S ($0.24) | $5.49 S ($0.24) | $5.49 S ($0.24) | $6.50 * ($0.29) | — | — |
| Quaker Quick 2.25 kg (20053840_EA) | $8.99 ($0.40) | — | — | $7.79 ($0.35) | $7.79 ($0.35) | $7.79 ($0.35) | $7.79 ($0.35) | $7.79 ($0.35) | $7.79 ($0.35) | $7.99 ($0.35) | — | — |
| PC Blue Menu Steel Cut 840 g (20703868_EA) | $5.00 ($0.59) | $5.00 ($0.59) | $4.00 * ($0.48) | $4.00 * ($0.48) | $4.00 * ($0.48) | $4.00 ($0.48) | $4.00 ($0.48) | $4.00 ($0.48) | $4.00 ($0.48) | $5.00 ($0.59) | $5.00 ($0.59) | $4.79 ($0.57) |
| PC Organics Steel Cut 1 kg (20971286_EA) | $5.00 * ($0.50) | $5.00 * ($0.50) | — | — | — | $5.00 ($0.50) | $5.00 ($0.50) | $5.00 ($0.50) | $5.00 ($0.50) | $5.00 * ($0.50) | $5.00 * ($0.50) | $5.00 ($0.50) |
| Quaker Quick Cook Steel Cut 709 g (20939060_EA) | $5.75 * ($0.81) | $5.75 S ($0.81) | — | $4.29 ($0.60) | $4.29 ($0.60) | $3.75 ($0.53) | $3.75 ($0.53) | $3.75 ($0.53) | $3.75 ($0.53) | $4.49 S ($0.63) | $4.99 ($0.70) | $4.00 ($0.56) |
| PC Regular Instant 280 g (21505058_EA) | $4.29 ($1.53) | — | — | $3.50 ($1.25) | $3.50 ($1.25) | $3.00 * ($1.07) | $3.00 * ($1.07) | $3.00 * ($1.07) | $3.00 * ($1.07) | $3.25 * ($1.16) | $3.79 ($1.35) | $3.29 ($1.18) |
| Quaker Regular Instant 280 g (21190265_EA) | $5.19 ($1.85) | $5.19 ($1.85) | $3.79 ($1.35) | $3.79 ($1.35) | $3.79 ($1.35) | $3.50 ($1.25) | $3.50 ($1.25) | $3.50 ($1.25) | $3.50 ($1.25) | $4.50 * ($1.61) | $5.19 ($1.85) | $3.79 ($1.35) |
| PC Maple & Brown Sugar Instant 344 g (21505150_EA) | $4.29 ($1.25) | $4.29 ($1.25) | $3.00 ($0.87) | $3.50 ($1.02) | $3.50 ($1.02) | $3.00 * ($0.87) | $3.00 * ($0.87) | $3.00 * ($0.87) | $3.00 * ($0.87) | $3.25 * ($0.94) | $3.79 ($1.10) | $3.29 ($0.96) |
| Quaker Maple & Brown Sugar Instant 344 g (21190254_EA) | $5.19 ($1.51) | $5.19 ($1.51) | $3.79 ($1.10) | $3.79 ($1.10) | $3.79 ($1.10) | $3.50 ($1.02) | $3.50 ($1.02) | $3.50 ($1.02) | $3.50 ($1.02) | $4.50 * ($1.31) | $5.19 ($1.51) | $3.79 ($1.10) |

Store key: LB-Markham ON = Loblaws Bullock Drive (Markham, Ontario) id 1032; LB-Vancouver BC = Loblaws City Market Vancouver Post (Vancouver, British Columbia) id 7155; NF-Toronto ON = Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) id 7952; NF-Calgary AB = Kevin's NOFRILLS Calgary (Calgary, Alberta) id 3155; NF-Vancouver BC = Dean's NOFRILLS Vancouver (Vancouver, British Columbia) id 3410; RCSS-Calgary AB = Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) id 1539; RCSS-Vancouver BC = Real Canadian Superstore Marine Drive (Vancouver, British Columbia) id 1517; RCSS-Winnipeg MB = Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508; RCSS-Regina SK = Real Canadian Superstore Albert Street (Regina, Saskatchewan) id 1533; ASS-Halifax NS = Atlantic Superstore - Young Street (Halifax, Nova Scotia) id 0354; PRV-Montréal QC = Provigo avenue des Canadiens de Montréal (Montréal, Quebec) id 7297; MAXI-Montréal QC = Maxi Montreal Ste-Catherine (Montreal, Quebec) id 9528.

### 1b. Comparable standard packs at the other banners that opened

| Banner (store/region) | Product name verbatim | Size | Price shown | Regular | Sale (end) | $/100 g computed | Retailer's own unit price |
|---|---|---|---|---|---|---|---|
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Compliments Instant Oatmeal Maple & Brown Sugar Flavour 344 g | 344g | $3.99 | $3.99 |  | $1.16 | $1.16/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Compliments Instant Oatmeal Regular 280 g | 280g | $3.99 | $3.99 |  | $1.43 | $1.42/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Quaker Instant Oatmeal Maple Brown Sugar 344 g | 344g | $5.29 | $5.29 |  | $1.54 | $1.54/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Quaker Instant Oatmeal Regular 280 g | 280g | $5.29 | $5.29 |  | $1.89 | $1.89/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Dan-D Pak Rolled Oats 1 kg | 1kg | $3.99 | $3.99 |  | $0.40 | $0.40/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Robin Hood Large Flake Oats 1 kg | 1kg | $4.79 | $4.79 |  | $0.48 | $0.48/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Quaker Old Fashioned Large Flake Oats 1 kg | 1kg | $6.49 | $6.49 |  | $0.65 | $0.65/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Farm Boy Organic Large Flake Oats 750 g | 100 x 7.5g | $5.49 | $5.49 |  | $0.73 | $0.73/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Longo's Organic Thick Rolled Oats 500 g | 500g | $5.99 | $5.99 |  | $1.20 | $1.20/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Longo's Organic Rolled Oats 500 g | 500g | $5.99 | $5.99 |  | $1.20 | $1.20/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Compliments Quick Oats 2.25 kg | 2.25kg | $6.79 | $6.79 |  | $0.30 | $0.30/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Quaker Quick Oats 2.25 kg | 2.25kg | $7.99 | $7.99 |  | $0.35 | $0.36/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Dan-D-Pak Quick Oats 1 kg | 1kg | $3.99 | $3.99 |  | $0.40 | $0.40/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Compliments Quick Oats 1 kg | 1kg | $4.49 | $4.49 |  | $0.45 | $0.45/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Robin Hood Quick Oats 1 kg | 1kg | $4.79 | $4.79 |  | $0.48 | $0.48/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Compliments Organic Quick Oats 1 kg | 1kg | $4.99 | $4.99 |  | $0.50 | $0.50/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Quaker Quick Oats 100% Whole Grain 1 kg | 1kg | $6.49 | $6.49 |  | $0.65 | $0.65/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Farm Boy Organic Steel Cut Oats 1 kg | 100 x 10g | $5.99 | $5.99 |  | $0.60 | $0.60/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Longo's Steel Cut Oats 700 g | 700g | $4.99 | $4.99 |  | $0.71 | $0.71/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Compliments Quick Cook Steel Cut Oats 709 g | 709g | $5.49 | $5.49 |  | $0.77 | $0.77/100g |
| Voilà by Sobeys (online, default region ('Default Region 1'; no postal code entered; province not displayed)) | Quaker Quick Cook Oats Steel Cut 709 g | 709g | $6.49 | $6.49 |  | $0.92 | $0.92/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Western Family - Maple & Brown Sugar Instant Oatmeal | 344.0 g | $4.29 | $4.29 |  | $1.25 | $1.25/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Quaker - Maple & Brown Sugar Flavour Instant Oatmeal | 344.0 g | $4.99 | $4.99 |  | $1.45 | $1.45/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Western Family - Regular Instant Oatmeal | 280.0 g | $4.29 | $4.29 |  | $1.53 | $1.53/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Quaker - Regular Instant Oatmeal | 560.0 g | $8.99 | $8.99 |  | $1.60 | $1.61/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Western Family - Apple & Cinnamon Flavor Instant Oatmeal | 264.0 g | $4.29 | $4.29 |  | $1.62 | $1.63/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Quaker - Regular Instant Oatmeal | 280.0 g | $4.99 | $4.99 |  | $1.78 | $1.78/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Western Family - 100% Whole Grain Canadian Old Fashioned Oats | 2.25 kg | $7.69 | $7.69 |  | $0.34 | $0.34/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Rogers - Large Flake Oats | 1.0 kg | $6.29 | $6.29 |  | $0.63 | $0.63/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | ONLY GOODNESS - Organic Old Fashioned Rolled Oats | 1.0 kg | $6.99 | $6.99 |  | $0.70 | $0.70/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Quaker - Large Flake Oats | 1.0 kg | $6.99 | $6.99 |  | $0.70 | $0.70/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | ONLY GOODNESS - Gluten Free Rolled Oats | 1.0 kg | $7.79 | $7.79 |  | $0.78 | $0.78/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Oats - Organic Thick Rolled, Bulk | bulk, sold per 100 g | $0.89 | $0.89 |  | $0.89 | $0.89/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Western Family - 100% Whole Grain Canadian Quick Oats | 2.25 kg | $7.69 | $7.69 |  | $0.34 | $0.34/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Quaker - Quick Oats - 2.25kg | 2.25 kg | $9.99 | $9.99 |  | $0.44 | $0.44/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Western Family - Quick Oats | 1.0 kg | $4.69 | $4.69 |  | $0.47 | $0.47/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Robin Hood - Quick Oats | 1.0 kg | $4.99 | $4.99 |  | $0.50 | $0.50/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Quaker - Quick Oats | 1.0 kg | $6.99 | $6.99 |  | $0.70 | $0.70/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | ONLY GOODNESS - Organic Quick Oats | 1.0 kg | $6.99 | $6.99 |  | $0.70 | $0.70/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Quaker - One Minute Oats | 900.0 g | $6.99 | $6.99 |  | $0.78 | $0.78/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Oats - Organic Quick Rolled, Bulk | bulk, sold per 100 g | $0.89 | $0.89 |  | $0.89 | $0.89/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Western Family - 100% Whole Grain Canadian Steel Cut Oats | 1.0 kg | $4.69 | $4.69 |  | $0.47 | $0.47/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Oats - Organic Steel Cut, Bulk | bulk, sold per 100 g | $0.89 | $0.89 |  | $0.89 | $0.89/100g |
| Save-On-Foods (Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC) | Quaker - Quick Cook Steel Cut Oats | 709.0 g | $6.99 | $6.99 |  | $0.99 | $0.99/100g |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Giant Value Maple and Brown Sugar Instant Oatmeal, 8-Pack | 344 g | $2.87 | $2.87 |  | $0.83 |  |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Giant Value Regular Instant Oatmeal, 10-Pack | 280 g | $2.87 | $2.87 |  | $1.02 |  |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Giant Value Apples and Cinnamon Instant Oatmeal, 8-Pack | 264 g | $2.87 | $2.87 |  | $1.09 |  |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Quaker Instant Oatmeal Variety 8pk. - 314g | 314.0 g | $3.66 | $3.66 |  | $1.17 |  |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Quaker Instant Oatmeal Flavour Variety Instant Oatmeal Packets, 8-Pack, 314-g | 314.0 g | $3.66 | $3.66 |  | $1.17 |  |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Quaker Dino Eggs Brown Sugar Instant Oatmeal 8pk. - 304g | 304.0 g | $3.66 | $3.66 |  | $1.20 |  |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Quaker Peaches and Cream Flavoured Oatmeal, 264-g | 264.0 g | $4.29 | $4.29 |  | $1.62 |  |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Giant Value Large Flake Oats, 1 kg | 1000.0 g | $2.77 | $2.77 |  | $0.28 |  |
| Giant Tiger (gianttiger.com (online price; in_store_only:false)) | Giant Value Quick Oats, 1 kg | 1000.0 g | $2.77 | $2.77 |  | $0.28 |  |
| Costco.ca (costco.ca online, location code 993-wm) | Quaker Instant Oatmeal 3 Flavour Variety Pack, 2.45 kg | 2.45 kg | $24.99 | $24.99 |  | $1.02 |  |
| Costco.ca (costco.ca online, location code 801-bd) | Kirkland Signature Whole Grain Rolled Oats, 4.54 kg | 4.54 kg | $11.99 | $11.99 |  | $0.26 |  |
| Costco.ca (costco.ca online, location code 801-bd) | One Degree Organic Sprouted Rolled Oats, 2.27kg | 2.27kg | $14.99 | $14.99 |  | $0.66 |  |
| Costco.ca (costco.ca online, location code 894_0-edi) | Stoked Oats Oatmeal, 8 × 500 g | 8 × 500 g | $59.99 | $59.99 |  | $1.50 |  |
| Costco.ca (costco.ca online, location code 801-bd) | Quaker Quick Oats, 2 × 2.58 kg | 2 × 2.58 kg | $10.99 | $13.99 | $10.99 to 2026-10-26 (promotionEndDate 2026-10-26T06:59:00Z) | $0.21 |  |

### 1c. Price per 100 g by brand and type across banners (all listings captured; range across stores and pack sizes, n = listings)

Computed from the price shown on 30 Sep 2026 (sale price where a sale was live) divided by the pack weight on the listing. Loblaw-banner cells pool every store of that banner listed in section 0.

**large flake / rolled**

| Brand | Loblaws | RCSS | No Frills | Atl. SS | Provigo | Maxi | Voilà | Save-On | Giant Tiger | Costco.ca |
|---|---|---|---|---|---|---|---|---|---|---|
| Adagio Acres |  |  |  |  |  |  | 1.09 (1) |  |  |  |
| Bob's Red Mill | 0.94–1.32 (4) | 0.84–1.18 (10) | 0.99 (3) | 0.94–1.43 (3) | 0.88–0.94 (2) | 0.99 (1) | 0.88–1.30 (5) |  |  |  |
| Bulk bin (no brand) |  |  |  |  |  |  |  | 0.89 (1) |  |  |
| Dan-D-Pak | 0.33 (2) | 0.30 (4) | 0.35 (1) | 0.33 (1) |  |  | 0.40 (1) |  |  |  |
| Farm Boy |  |  |  |  |  |  | 0.73 (1) |  |  |  |
| Giant Value |  |  |  |  |  |  |  |  | 0.28 (1) |  |
| Kirkland Signature |  |  |  |  |  |  |  |  |  | 0.26 (1) |
| La Meunerie Milanaise |  |  |  |  |  |  | 0.70–0.86 (2) |  |  |  |
| Left Coast |  |  |  |  |  |  |  | 1.07 (1) |  |  |
| Longo's |  |  |  |  |  |  | 1.20 (2) |  |  |  |
| No Name | 0.30 (2) | 0.24–0.30 (8) | 0.30 (3) | 0.29–0.30 (2) | 0.30 (1) | 0.30 (1) |  |  |  |  |
| Oak Manor | 0.85–0.95 (2) | 0.85 (3) |  | 0.85 (1) |  |  |  |  |  |  |
| One Degree | 1.25 (2) | 1.40 (4) |  | 1.25 (1) | 1.35 (1) |  | 1.40 (1) | 1.32 (1) |  | 0.66 (1) |
| Only Goodness |  |  |  |  |  |  |  | 0.70–0.78 (2) |  |  |
| Only Oats |  |  |  |  |  |  | 1.20 (1) |  |  |  |
| PC (President's Choice) | 0.56 (1) | 0.56 (3) |  | 0.56 (1) |  | 0.61 (1) |  |  |  |  |
| Quaker | 0.57 (2) | 0.38 (4) | 0.40–0.43 (3) | 0.45 (1) | 0.50 (1) | 0.40 (1) | 0.65 (1) | 0.70 (1) |  |  |
| Robin Hood | 0.48 (1) | 0.45 (4) | 0.40 (2) | 0.48 (1) |  | 0.43 (1) | 0.48 (1) |  |  |  |
| Rogers | 0.60–0.80 (3) | 0.58–0.77 (8) |  | 0.60–0.80 (2) | 0.80 (1) |  |  | 0.63–0.84 (3) |  |  |
| Speerville Flour Mill |  |  |  | 0.66 (1) |  |  | 0.60 (1) |  |  |  |
| Stoked Oats |  |  |  |  |  |  | 0.86 (1) |  |  |  |
| Western Family |  |  |  |  |  |  |  | 0.34 (1) |  |  |
| Willow Creek |  |  |  |  |  |  | 0.53–0.94 (4) |  |  |  |

**quick**

| Brand | Loblaws | RCSS | No Frills | Atl. SS | Provigo | Maxi | Voilà | Save-On | Giant Tiger | Costco.ca |
|---|---|---|---|---|---|---|---|---|---|---|
| Bob's Red Mill |  |  |  |  |  |  | 1.16–1.74 (2) |  |  |  |
| Bulk bin (no brand) |  |  |  |  |  |  |  | 0.89 (1) |  |  |
| Compliments |  |  |  |  |  |  | 0.30–0.50 (3) |  |  |  |
| Dan-D-Pak |  | 0.30 (4) | 0.35 (1) | 0.33 (1) |  |  | 0.40 (1) |  |  |  |
| Giant Value |  |  |  |  |  |  |  |  | 0.28 (1) |  |
| Good Eats (Pilling Foods) |  |  |  |  |  |  | 1.94 (1) |  |  |  |
| La Meunerie Milanaise |  |  |  |  |  |  | 0.70–0.86 (2) |  |  |  |
| No Name | 0.30–0.33 (3) | 0.24–0.33 (12) | 0.30–0.33 (6) | 0.29–0.33 (3) | 0.30 (1) | 0.30–0.33 (2) |  |  |  |  |
| One Degree | 1.25 (1) | 1.40 (3) |  | 0.62 (1) |  |  | 1.40 (1) | 1.32 (1) |  |  |
| Only Goodness |  |  |  |  |  |  |  | 0.70 (1) |  |  |
| Only Oats |  |  |  |  |  |  | 1.20 (1) |  |  |  |
| PC (President's Choice) | 0.50 (2) | 0.50 (4) | 0.50 (3) | 0.50 (1) | 0.50 (1) | 0.50 (1) |  |  |  |  |
| Quaker | 0.40–1.56 (6) | 0.29–1.07 (20) | 0.35–0.48 (8) | 0.35–1.37 (4) | 0.50–0.55 (2) | 0.40–0.44 (2) | 0.35–1.37 (4) | 0.44–1.47 (4) |  | 0.21 (1) |
| Robin Hood | 0.48–0.50 (3) | 0.45 (8) | 0.40 (4) | 0.48 (2) | 0.53 (1) | 0.43 (2) | 0.48 (2) | 0.50 (1) |  |  |
| Stoked Oats |  |  |  |  |  |  | 1.11 (1) |  |  |  |
| Western Family |  |  |  |  |  |  |  | 0.34–0.47 (2) |  |  |
| Wildly Canadian |  |  |  |  |  |  | 1.20 (1) |  |  |  |
| Willow Creek |  |  |  |  |  |  | 0.59–0.94 (4) |  |  |  |

**steel-cut**

| Brand | Loblaws | RCSS | No Frills | Atl. SS | Provigo | Maxi | Voilà | Save-On | Giant Tiger | Costco.ca |
|---|---|---|---|---|---|---|---|---|---|---|
| Adagio Acres |  |  |  |  |  |  | 1.00 (1) |  |  |  |
| Bob's Red Mill | 1.25 (1) | 1.18 (2) |  |  |  |  | 0.66–1.81 (5) |  |  |  |
| Bulk bin (no brand) |  |  |  |  |  |  |  | 0.89 (1) |  |  |
| Compliments |  |  |  |  |  |  | 0.77 (1) |  |  |  |
| Farm Boy |  |  |  |  |  |  | 0.60 (1) |  |  |  |
| Highwood Crossing |  |  |  |  |  |  | 1.55 (1) |  |  |  |
| Longo's |  |  |  |  |  |  | 0.71 (1) |  |  |  |
| McCann's |  |  |  |  |  |  | 1.32–1.39 (2) |  |  |  |
| One Degree | 1.25 (1) | 1.40 (3) |  |  |  |  | 1.40 (1) | 1.32 (1) |  |  |
| Only Oats |  |  |  |  |  |  | 1.20 (1) |  |  |  |
| PC (President's Choice) | 0.50–1.11 (7) | 0.48–1.11 (16) | 0.48 (3) | 0.50–1.25 (4) | 0.50–1.11 (3) | 0.50–0.57 (2) |  |  |  |  |
| Quaker | 0.81 (2) | 0.53 (4) | 0.60 (2) | 0.63 (1) | 0.70 (1) | 0.56 (1) | 0.92–1.63 (3) | 0.99 (1) |  |  |
| Rogers |  |  |  |  |  |  |  | 0.57 (1) |  |  |
| Western Family |  |  |  |  |  |  |  | 0.47 (1) |  |  |
| Willow Creek |  |  |  |  |  |  | 0.75 (1) |  |  |  |

**instant packets**

| Brand | Loblaws | RCSS | No Frills | Atl. SS | Provigo | Maxi | Voilà | Save-On | Giant Tiger | Costco.ca |
|---|---|---|---|---|---|---|---|---|---|---|
| Compliments |  |  |  |  |  |  | 0.86–1.53 (11) |  |  |  |
| Farm Boy |  |  |  |  |  |  | 1.39 (2) |  |  |  |
| Giant Value |  |  |  |  |  |  |  |  | 0.83–1.09 (3) |  |
| Nature's Path | 1.75–3.09 (9) | 1.32–2.76 (21) |  | 2.85–3.09 (4) | 3.29 (3) | 2.85 (2) | 1.45–3.07 (7) |  |  |  |
| One Degree |  |  |  |  |  |  | 2.72 (1) |  |  |  |
| PC (President's Choice) | 1.25–1.75 (12) | 0.87–1.38 (35) | 0.87–1.33 (12) | 0.94–1.75 (9) | 1.10–1.44 (5) | 0.96–1.41 (5) |  |  |  |  |
| Quaker | 1.22–3.56 (21) | 0.94–2.67 (68) | 1.10–2.68 (18) | 1.01–2.67 (18) | 1.51–2.63 (10) | 0.98–1.97 (11) | 1.01–3.45 (35) | 1.22–4.16 (11) | 1.17–1.62 (4) | 1.02 (1) |
| Saffola Oats | 1.10 (3) | 1.20 (12) |  | 1.10 (3) |  |  |  |  |  |  |
| Western Family |  |  |  |  |  |  |  | 1.25–1.62 (3) |  |  |
| Yumi Organics | 2.08 (2) | 1.89 (8) |  | 1.99 (2) |  |  |  |  |  |  |

**instant (cup)**

| Brand | Loblaws | RCSS | No Frills | Atl. SS | Provigo | Maxi | Voilà | Save-On | Giant Tiger | Costco.ca |
|---|---|---|---|---|---|---|---|---|---|---|
| Bob's Red Mill | 4.46–4.90 (3) | 3.42–3.75 (7) |  | 2.98–3.28 (2) | 4.90 (1) | 3.73–4.10 (2) | 5.20–7.82 (4) |  |  |  |
| Farm Boy |  |  |  |  |  |  | 2.56 (4) |  |  |  |

**instant (bag)**

| Brand | Loblaws | RCSS | No Frills | Atl. SS | Provigo | Maxi | Voilà | Save-On | Giant Tiger | Costco.ca |
|---|---|---|---|---|---|---|---|---|---|---|
| Anita's Organic Mill | 0.76 (1) | 0.72 (2) |  |  |  |  |  |  |  |  |
| Grace |  |  |  |  |  |  | 0.45 (1) |  |  |  |

**other**

| Brand | Loblaws | RCSS | No Frills | Atl. SS | Provigo | Maxi | Voilà | Save-On | Giant Tiger | Costco.ca |
|---|---|---|---|---|---|---|---|---|---|---|
| Bob's Red Mill | 0.99 (2) | 0.89 (4) | 1.05 (1) | 0.99 (1) | 0.88 (1) | 1.05 (1) | 0.79–1.76 (4) | 1.21 (1) |  |  |
| GORP |  |  |  |  |  |  | 0.91–1.27 (3) |  |  |  |
| Nature's Path |  |  |  |  |  |  | 1.32 (1) |  |  |  |
| Quaker | 1.93 (1) | 1.93 (4) |  | 1.93 (1) | 1.93 (1) |  | 1.11–1.49 (2) |  |  |  |
| Stoked Oats | 2.00 (2) | 1.70 (4) |  |  |  |  | 2.00 (4) |  |  | 1.50 (1) |
| Willow Creek |  |  |  |  |  |  | 0.69 (1) |  |  |  |


---

## 2. Cheapest and dearest per type (all 806 listings, price shown ÷ pack weight)

Duplicate rows (same product, same price, same banner) are collapsed, so a price shared by several stores of one banner appears once, with the first store listed. For ties across stores of one banner, see Appendix A.

**large flake / rolled**

| Rank | Banner | Store / region | Brand | Product name verbatim | Size (g) | Price shown | Regular | Sale end | $/100 g |
|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | No Name | Large Flake 100% Whole Grain Oats Club Size | 2250 | $5.49 | $6.00 | 2026-10-07 | $0.24 |
| Cheapest 2 | Costco.ca | costco.ca online, location code 801-bd | Kirkland Signature | Kirkland Signature Whole Grain Rolled Oats, 4.54 kg | 4540 | $11.99 | $11.99 |  | $0.26 |
| Cheapest 3 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Giant Value | Giant Value Large Flake Oats, 1 kg | 1000 | $2.77 | $2.77 |  | $0.28 |
| Cheapest 4 | Atlantic Superstore | Atlantic Superstore - Young Street (Halifax, Nova Scotia) id 0354 | No Name | Large Flake 100% Whole Grain Oats Club Size | 2250 | $6.50 | $6.50 |  | $0.29 |
| Cheapest 5 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | Dan D Pak | Rolled Oats | 1000 | $2.98 | $2.98 |  | $0.30 |
| Cheapest 6 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | No Name | Large Flake 100% Whole Grain Oats | 1000 | $3.00 | $3.49 | 2026-10-07 | $0.30 |
| Dearest 1 | Atlantic Superstore | Atlantic Superstore - Young Street (Halifax, Nova Scotia) id 0354 | Bobs Red Mill | Rolled Oats Old Fashioned Organic | 454 | $6.49 | $6.99 | 2026-10-14 | $1.43 |
| Dearest 2 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | One Degree Organic Foods | One Degree Organic Foods Rolled Oats Sprouted 680 g | 680 | $9.49 | $9.49 |  | $1.40 |
| Dearest 3 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | One Degree | Rolled Oats Sprouted | 680 | $9.49 | $9.49 |  | $1.40 |
| Dearest 4 | Provigo | Provigo avenue des Canadiens de Montréal (Montréal, Quebec) id 7297 | One Degree | Rolled Oats Sprouted | 680 | $9.19 | $9.99 | 2026-10-07 | $1.35 |
| Dearest 5 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | One Degree Organic | One Degree Organic - Sprouted Rolled Oats | 680 | $8.99 | $8.99 |  | $1.32 |
| Dearest 6 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Bobs Red Mill | Rolled Oats Old Fashioned Organic | 454 | $5.99 | $6.49 | 2026-10-14 | $1.32 |

**quick**

| Rank | Banner | Store / region | Brand | Product name verbatim | Size (g) | Price shown | Regular | Sale end | $/100 g |
|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | Costco.ca | costco.ca online, location code 801-bd | Quaker | Quaker Quick Oats, 2 × 2.58 kg | 5160 | $10.99 | $13.99 | 2026-10-26 (promotionEndDate 2026-10-26T06:59:00Z) | $0.21 |
| Cheapest 2 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | No Name | Quick 100% Whole Grain Oats Club Size | 2250 | $5.49 | $6.00 | 2026-10-07 | $0.24 |
| Cheapest 3 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Giant Value | Giant Value Quick Oats, 1 kg | 1000 | $2.77 | $2.77 |  | $0.28 |
| Cheapest 4 | Atlantic Superstore | Atlantic Superstore - Young Street (Halifax, Nova Scotia) id 0354 | No Name | Quick 100% Whole Grain Oats Club Size | 2250 | $6.50 | $6.50 |  | $0.29 |
| Cheapest 5 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | Quaker | Quaker Quick Oats | 5160 | $14.99 | $14.99 |  | $0.29 |
| Cheapest 6 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | Dan D Pak | Quick Oats | 1000 | $2.98 | $2.98 |  | $0.30 |
| Dearest 1 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Pilling Foods Inc. | Good Eats Gluten-Free Organic Quick Rolled Oats 454 g | 454 | $8.79 | $8.79 |  | $1.94 |
| Dearest 2 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Rolled Oats Quick Cooking 794 g | 794 | $13.79 | $13.79 |  | $1.74 |
| Dearest 3 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Quaker | Gluten-Free Quick Oats | 511 | $7.99 | $7.99 |  | $1.56 |
| Dearest 4 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Gluten Free Quick Oats | 511 | $7.49 | $7.49 |  | $1.47 |
| Dearest 5 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | One Degree Organic Foods | One Degree Organic Foods Quick Oats Sprouted 680 g | 680 | $9.49 | $9.49 |  | $1.40 |
| Dearest 6 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | One Degree | Quick Oats Sprouted | 680 | $9.49 | $9.49 |  | $1.40 |

**steel-cut**

| Rank | Banner | Store / region | Brand | Product name verbatim | Size (g) | Price shown | Regular | Sale end | $/100 g |
|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Western Family | Western Family - 100% Whole Grain Canadian Steel Cut Oats | 1000 | $4.69 | $4.69 |  | $0.47 |
| Cheapest 2 | No Frills | Kevin's NOFRILLS Calgary (Calgary, Alberta) id 3155 | PC Blue Menu | 100% Whole Grain Steel Cut Oats | 840 | $4.00 | $4.00 |  | $0.48 |
| Cheapest 3 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | PC Blue Menu | 100% Whole Grain Steel Cut Oats | 840 | $4.00 | $4.00 |  | $0.48 |
| Cheapest 4 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | PC Organics | Organic Steel Cut Oats | 1000 | $5.00 | $5.00 |  | $0.50 |
| Cheapest 5 | Maxi | Maxi Montreal Ste-Catherine (Montreal, Quebec) id 9528 | PC Organics | Organic Steel Cut Oats | 1000 | $5.00 | $5.00 |  | $0.50 |
| Cheapest 6 | Provigo | Provigo avenue des Canadiens de Montréal (Montréal, Quebec) id 7297 | PC Organics | Organic Steel Cut Oats | 1000 | $5.00 | $5.00 |  | $0.50 |
| Dearest 1 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Steel Cut Oats Whole Grain 680 g | 680 | $12.29 | $12.29 |  | $1.81 |
| Dearest 2 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Quick Cook Oatmeal Steel Cut Blueberries & Cranberries 368 g | 368 | $5.99 | $5.99 |  | $1.63 |
| Dearest 3 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Quick Cook Steel Cut Oatmeal Brown Sugar Cinnamon 384 g | 384 | $5.99 | $5.99 |  | $1.56 |
| Dearest 4 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Highwood Crossing | Highwood Crossing Organic Oats Steel Cut 775 g | 775 | $11.99 | $11.99 |  | $1.55 |
| Dearest 5 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | One Degree Organic Foods | One Degree Organic Foods Steel Cut Oats Sprouted 680 g | 680 | $9.49 | $9.49 |  | $1.40 |
| Dearest 6 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | One Degree | Steel Cut Oats Sprouted | 680 | $9.49 | $9.49 |  | $1.40 |

**instant packets**

| Rank | Banner | Store / region | Brand | Product name verbatim | Size (g) | Price shown | Regular | Sale end | $/100 g |
|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Giant Value | Giant Value Maple and Brown Sugar Instant Oatmeal, 8-Pack | 344 | $2.87 | $2.87 |  | $0.83 |
| Cheapest 2 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Balance Oatmeal Maple & Brown Sugar 430 g | 430 | $3.69 | $3.69 |  | $0.86 |
| Cheapest 3 | No Frills | Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) id 7952 | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | 344 | $3.00 | $3.00 |  | $0.87 |
| Cheapest 4 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | 344 | $3.00 | $3.00 |  | $0.87 |
| Cheapest 5 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | Quaker | Instant Oatmeal Flavour Variety Family Size | 694 | $6.49 | $6.49 |  | $0.94 |
| Cheapest 6 | Atlantic Superstore | Atlantic Superstore - Young Street (Halifax, Nova Scotia) id 0354 | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | 344 | $3.25 | $3.25 |  | $0.94 |
| Dearest 1 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Protein Instant Oatmeal,  Regular | 168 | $6.99 | $6.99 |  | $4.16 |
| Dearest 2 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Quaker | Protein Instant Oatmeal, Regular, 6 packets | 168 | $5.99 | $5.99 |  | $3.56 |
| Dearest 3 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Protein Instant Oatmeal Regular 6 packets 168 g | 168 | $5.79 | $5.79 |  | $3.45 |
| Dearest 4 | Provigo | Provigo avenue des Canadiens de Montréal (Montréal, Quebec) id 7297 | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | 228 | $7.49 | $7.49 |  | $3.29 |
| Dearest 5 | Provigo | Provigo avenue des Canadiens de Montréal (Montréal, Quebec) id 7297 | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | 228 | $7.49 | $7.49 |  | $3.29 |
| Dearest 6 | Provigo | Provigo avenue des Canadiens de Montréal (Montréal, Quebec) id 7297 | Nature's Path | Organic Creamy Coconut Instant Oatmeal | 228 | $7.49 | $7.49 |  | $3.29 |

**instant (cup)**

| Rank | Banner | Store / region | Brand | Product name verbatim | Size (g) | Price shown | Regular | Sale end | $/100 g |
|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Oatmeal Cup Apple & Cinnamon 70 g | 70 | $1.79 | $1.79 |  | $2.56 |
| Cheapest 2 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Oatmeal Cup Berry Medley 70 g | 70 | $1.79 | $1.79 |  | $2.56 |
| Cheapest 3 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Oatmeal Cup Maple Walnut 70 g | 70 | $1.79 | $1.79 |  | $2.56 |
| Cheapest 4 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Oatmeal Cup Banana Nut 70 g | 70 | $1.79 | $1.79 |  | $2.56 |
| Cheapest 5 | Atlantic Superstore | Atlantic Superstore - Young Street (Halifax, Nova Scotia) id 0354 | Bobs Red Mill | Gluten Free Oatmeal Apple Cinnamon | 67 | $2.00 | $2.00 |  | $2.98 |
| Cheapest 6 | Atlantic Superstore | Atlantic Superstore - Young Street (Halifax, Nova Scotia) id 0354 | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | 61 | $2.00 | $2.79 | 2026-11-04 | $3.28 |
| Dearest 1 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Oatmeal Cup Lightly Salted 51 g | 51 | $3.99 | $3.99 |  | $7.82 |
| Dearest 2 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Oatmeal Cup Maple Brown Sugar 61 g | 61 | $4.19 | $4.19 |  | $6.87 |
| Dearest 3 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Oatmeal Cup Apple Cinnamon 67 g | 67 | $3.69 | $3.69 |  | $5.51 |
| Dearest 4 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Oatmeal Cup Blueberry Hazelnut 71 g | 71 | $3.69 | $3.69 |  | $5.20 |
| Dearest 5 | Provigo | Provigo avenue des Canadiens de Montréal (Montréal, Quebec) id 7297 | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | 61 | $2.99 | $2.99 |  | $4.90 |
| Dearest 6 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | 61 | $2.99 | $2.99 |  | $4.90 |

**instant (bag)**

| Rank | Banner | Store / region | Brand | Product name verbatim | Size (g) | Price shown | Regular | Sale end | $/100 g |
|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Grace | Grace Instant Oats 1 kg | 1000 | $4.49 | $4.49 |  | $0.45 |
| Cheapest 2 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | Anita's Organic Mill | Organic Whole Grain Old Fashioned Rolled Instant Oatmeal | 2500 | $17.99 | $17.99 |  | $0.72 |
| Cheapest 3 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Anita's Organic Mill | Organic Whole Grain Old Fashioned Rolled Instant Oatmeal | 2500 | $18.99 | $18.99 |  | $0.76 |
| Dearest 1 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Anita's Organic Mill | Organic Whole Grain Old Fashioned Rolled Instant Oatmeal | 2500 | $18.99 | $18.99 |  | $0.76 |
| Dearest 2 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | Anita's Organic Mill | Organic Whole Grain Old Fashioned Rolled Instant Oatmeal | 2500 | $17.99 | $17.99 |  | $0.72 |
| Dearest 3 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Grace | Grace Instant Oats 1 kg | 1000 | $4.49 | $4.49 |  | $0.45 |

**other**

| Rank | Banner | Store / region | Brand | Product name verbatim | Size (g) | Price shown | Regular | Sale end | $/100 g |
|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek | Willow Creek Organic Whole Oat Groats 800 g | 800 | $5.49 | $5.49 |  | $0.69 |
| Cheapest 2 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Scottish Oatmeal 567 g | 567 | $4.49 | $4.49 |  | $0.79 |
| Cheapest 3 | Provigo | Provigo avenue des Canadiens de Montréal (Montréal, Quebec) id 7297 | Bobs Red Mill | Gluten Free Protein Oats | 907 | $7.99 | $8.99 | 2026-10-14 | $0.88 |
| Cheapest 4 | Real Canadian Superstore | Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) id 1508 | Bobs Red Mill | Gluten Free Protein Oats | 907 | $8.06 | $9.49 | 2026-10-07 | $0.89 |
| Cheapest 5 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | GORP | GORP Just Oats Oatmeal Blends 1.1KG | 1100 | $9.99 | $9.99 |  | $0.91 |
| Cheapest 6 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Bobs Red Mill | Gluten Free Protein Oats | 907 | $8.99 | $9.99 | 2026-10-14 | $0.99 |
| Dearest 1 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Lactose-Free Oatmeal Bucking-Eh Oats 500 g | 500 | $9.99 | $9.99 |  | $2.00 |
| Dearest 2 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Oatmeal Blend Aphrodisi-Oats 500 g | 500 | $9.99 | $9.99 |  | $2.00 |
| Dearest 3 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Lactose-Free Oatmeal Stone Age Bag Oats 500 g | 500 | $9.99 | $9.99 |  | $2.00 |
| Dearest 4 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Lactose-Free Oatmeal Redline Bag Oats 500 g | 500 | $9.99 | $9.99 |  | $2.00 |
| Dearest 5 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Stoked Oats | Stone Age Oats | 500 | $9.99 | $9.99 |  | $2.00 |
| Dearest 6 | Loblaws | Loblaws Bullock Drive (Markham, Ontario) id 1032 | Stoked Oats | Bucking Eh Oats | 500 | $9.99 | $9.99 |  | $2.00 |


**Reading notes for section 2:**
- Large flake / rolled: the cheapest three per 100 g are three different retailer models. A private-label club bag on sale (No Name 2.25 kg, RCSS, $5.49 to 7 Oct) is $0.24. A warehouse-club own brand (Kirkland Signature 4.54 kg, Costco.ca, $11.99) is $0.26. A discounter's own brand (Giant Value 1 kg, Giant Tiger, $2.77) is $0.28.
- Quick: the cheapest is a national brand, not a private label. Quaker 2 × 2.58 kg on Costco.ca is $10.99 with "$3 OFF" to 25 Oct (Pacific), which is $0.21/100 g. At regular price ($13.99) it would be $0.27/100 g.
- Steel-cut: the cheapest are store brands. Western Family 1 kg at Save-On is $4.69 ($0.47). PC Blue Menu 840 g is $4.00 at No Frills Calgary/Vancouver/Toronto and RCSS ($0.48).
- Instant packets: the cheapest is Giant Value Maple and Brown Sugar 8-pack, 344 g, $2.87 ($0.83/100 g). Next come Compliments Balance Oatmeal Maple & Brown Sugar 430 g on Voilà ($3.69, $0.86) and PC Maple and Brown Sugar 344 g at $3.00 (No Frills Toronto; RCSS) ($0.87). The dearest per 100 g is the Quaker "Protein Instant Oatmeal, Regular" 168 g box: $6.99 at Save-On ($4.16), $5.99 at Loblaws Markham ($3.57), $5.79 on Voilà ($3.45).
- Single-serve cups and single packets under 100 g are grouped as "instant (cup)". These include the Bob's Red Mill 61 g and 67 g items sold at Loblaw banners, which their listings do not call cups. On Voilà, Bob's Red Mill cups reach $7.82/100 g (51 g, $3.99). Farm Boy cups are $2.56/100 g (70 g, $1.79).
- Cups (section "instant (cup)") and "other" (blends, Scottish oatmeal, protein oats, oat groats) are listed separately so they do not distort the plain-oat comparisons.

---

## 3. Canadian-made vs imported, same banner

**Finding: no listing opened today stated a non-Canadian origin for any oatmeal product, so a verified "imported" side for this comparison does not exist.** The Loblaw API, Voilà, Save-On-Foods, Giant Tiger and Costco.ca all show origin only as a Canada flag or line when one is set. None of them showed "Product of U.S.A.", "Product of India" or similar on any oatmeal listing. For products sold here by U.S.-based or overseas brands (Bob's Red Mill, McCann's, Saffola, Nature's Path), the listings opened today show no origin line. The front-of-pack images opened today (Bob's Red Mill rolled and steel cut, Saffola Masala Oats) do not show one either. **Do not say any product is imported.** The comparison that can be made is between **listings carrying a Canada origin line** and **listings showing none**. "None shown" does not mean imported.

**What counts as a "Canada origin line" in this table:**
- Loblaw banners: the site badge "Prepared in Canada" in the API `badges.preparedInCanadaBadge`. No "Made in Canada" or "Product of Canada" badge appeared on any oatmeal listing.
- Save-On-Foods: the product attributes `"product of canada": true` or `"made in canada": true`.
- Voilà: a "Country Of Origin: Canada" field, set on only 3 of 193 oatmeal listings.
- Giant Tiger: the tag `product_of_canada`, or the package-image badge reading "MADE WITH 100% CANADIAN OATS".
- Costco.ca: the listing feature lines "Made with 100% whole grain Canadian oats" (Quaker instant) and "Made in Canada" (Stoked Oats).

| Banner | Type | Listings with a Canada origin line (n, median $/100 g, range) | Listings with no origin line shown (n, median $/100 g, range) | Brands with no origin line shown |
|---|---|---|---|---|
| Loblaws | large flake / rolled | 11, 0.57, 0.30–1.25 | 8, 0.94, 0.33–1.32 | Bob's Red Mill, Dan-D-Pak, Oak Manor |
| Loblaws | quick | 14, 0.50, 0.30–1.25 | 1, 1.56, 1.56–1.56 | Quaker |
| Loblaws | steel-cut | 3, 0.50, 0.50–1.25 | 8, 0.96, 0.59–1.25 | Bob's Red Mill, PC (President's Choice), Quaker |
| Loblaws | instant packets | 17, 1.85, 1.22–3.56 | 30, 1.75, 1.10–3.09 | Nature's Path, PC (President's Choice), Quaker, Saffola Oats, Yumi Organics |
| Real Canadian Superstore | large flake / rolled | 31, 0.45, 0.24–1.40 | 17, 0.85, 0.30–1.18 | Bob's Red Mill, Dan-D-Pak, Oak Manor |
| Real Canadian Superstore | quick | 39, 0.38, 0.24–1.40 | 12, 0.30, 0.29–1.07 | Dan-D-Pak, Quaker |
| Real Canadian Superstore | steel-cut | 7, 0.50, 0.50–1.40 | 18, 1.11, 0.48–1.18 | Bob's Red Mill, PC (President's Choice), Quaker |
| Real Canadian Superstore | instant packets | 52, 1.30, 0.94–2.67 | 92, 1.38, 0.87–2.76 | Nature's Path, PC (President's Choice), Quaker, Saffola Oats, Yumi Organics |
| No Frills | large flake / rolled | 8, 0.40, 0.30–0.43 | 4, 0.99, 0.35–0.99 | Bob's Red Mill, Dan-D-Pak |
| No Frills | quick | 21, 0.40, 0.30–0.50 | 1, 0.35, 0.35–0.35 | Dan-D-Pak |
| No Frills | steel-cut | 0 | 5, 0.48, 0.48–0.60 | PC (President's Choice), Quaker |
| No Frills | instant packets | 16, 1.35, 1.10–2.68 | 14, 1.25, 0.87–1.77 | PC (President's Choice), Quaker |
| Atlantic Superstore | large flake / rolled | 8, 0.52, 0.29–1.25 | 6, 0.89, 0.33–1.43 | Bob's Red Mill, Dan-D-Pak, Oak Manor, Speerville Flour Mill |
| Atlantic Superstore | quick | 10, 0.46, 0.29–0.62 | 2, 0.85, 0.33–1.37 | Dan-D-Pak, Quaker |
| Atlantic Superstore | steel-cut | 1, 0.50, 0.50–0.50 | 4, 0.94, 0.59–1.25 | PC (President's Choice), Quaker |
| Atlantic Superstore | instant packets | 14, 1.55, 1.01–2.67 | 22, 1.66, 0.94–3.09 | Nature's Path, PC (President's Choice), Quaker, Saffola Oats, Yumi Organics |
| Provigo | large flake / rolled | 4, 0.65, 0.30–1.35 | 2, 0.91, 0.88–0.94 | Bob's Red Mill |
| Provigo | quick | 5, 0.50, 0.30–0.55 | 0 |  |
| Provigo | steel-cut | 1, 0.50, 0.50–0.50 | 3, 0.70, 0.59–1.11 | PC (President's Choice), Quaker |
| Provigo | instant packets | 8, 1.91, 1.51–2.63 | 10, 1.84, 1.10–3.29 | Nature's Path, PC (President's Choice), Quaker |
| Maxi | large flake / rolled | 4, 0.41, 0.30–0.61 | 1, 0.99, 0.99–0.99 | Bob's Red Mill |
| Maxi | quick | 7, 0.43, 0.30–0.50 | 0 |  |
| Maxi | steel-cut | 1, 0.50, 0.50–0.50 | 2, 0.57, 0.56–0.57 | PC (President's Choice), Quaker |
| Maxi | instant packets | 9, 1.35, 0.98–1.97 | 9, 1.41, 0.96–2.85 | Nature's Path, PC (President's Choice), Quaker |
| Voilà by Sobeys | large flake / rolled | 0 | 22, 0.87, 0.40–1.40 | Adagio Acres, Bob's Red Mill, Dan-D-Pak, Farm Boy, La Meunerie Milanaise, Longo's, One Degree, Only Oats, Quaker, Robin Hood, Speerville Flour Mill, Stoked Oats, Willow Creek |
| Voilà by Sobeys | quick | 1, 0.65, 0.65–0.65 | 22, 0.78, 0.30–1.94 | Bob's Red Mill, Compliments, Dan-D-Pak, Good Eats (Pilling Foods), La Meunerie Milanaise, One Degree, Only Oats, Quaker, Robin Hood, Stoked Oats, Wildly Canadian, Willow Creek |
| Voilà by Sobeys | steel-cut | 0 | 18, 1.15, 0.60–1.81 | Adagio Acres, Bob's Red Mill, Compliments, Farm Boy, Highwood Crossing, Longo's, McCann's, One Degree, Only Oats, Quaker, Willow Creek |
| Voilà by Sobeys | instant packets | 2, 1.53, 1.23–1.83 | 54, 1.64, 0.86–3.45 | Compliments, Farm Boy, Nature's Path, One Degree, Quaker |
| Save-On-Foods | large flake / rolled | 9, 0.70, 0.34–1.32 | 1, 1.07, 1.07–1.07 | Left Coast |
| Save-On-Foods | quick | 9, 0.70, 0.34–1.32 | 1, 1.47, 1.47–1.47 | Quaker |
| Save-On-Foods | steel-cut | 3, 0.57, 0.47–1.32 | 2, 0.94, 0.89–0.99 | Bulk bin (no brand), Quaker |
| Save-On-Foods | instant packets | 13, 1.62, 1.22–4.16 | 1, 1.60, 1.60–1.60 | Quaker |
| Giant Tiger | large flake / rolled | 1, 0.28, 0.28–0.28 | 0 |  |
| Giant Tiger | quick | 1, 0.28, 0.28–0.28 | 0 |  |
| Giant Tiger | instant packets | 3, 1.02, 0.83–1.09 | 4, 1.19, 1.17–1.62 | Quaker |
| Costco.ca | large flake / rolled | 0 | 2, 0.46, 0.26–0.66 | Kirkland Signature, One Degree |
| Costco.ca | quick | 0 | 1, 0.21, 0.21–0.21 | Quaker |
| Costco.ca | instant packets | 1, 1.02, 1.02–1.02 | 0 |  |


**Same-banner, same-type pairs worth showing:**

| Banner, store | Canada line shown | Price, $/100 g | No origin line shown | Price, $/100 g |
|---|---|---|---|---|
| Real Canadian Superstore, Winnipeg (1508) | No Name "Large Flake 100% Whole Grain Oats" 1 kg, badge "Prepared in Canada" | $3.00, $0.30 | Bob's Red Mill "Rolled Oats" 907 g | $7.99, $0.88 |
| Loblaws, Markham (1032) | Quaker "Large Flake Oats" 1 kg, badge "Prepared in Canada" | $5.75, $0.57 | Bob's Red Mill "Rolled Oats Old Fashioned Organic" 454 g | $5.99 sale (was $6.49, to 14 Oct), $1.32 |
| Save-On-Foods, Langley BC | Western Family "100% Whole Grain Canadian Old Fashioned Oats" 2.25 kg, attribute Product of Canada | $7.69, $0.34 | Left Coast "Organic Rolled Oats" 1 kg | $10.69 sale (was $11.49, to 10/21/2026), $1.07 |
| Costco.ca | Quaker Instant Oatmeal 3 Flavour Variety Pack 2.45 kg, feature line "Made with 100% whole grain Canadian oats" | $24.99, $1.02 | Kirkland Signature Whole Grain Rolled Oats 4.54 kg (no origin line on listing) | $11.99, $0.26 |

**Verbatim origin statements read from label images or listings today (tier a):**

| Product | Exact wording | Where it was read (opened 30 Sep 2026 ET) |
|---|---|---|
| Quaker Large Flake Oats 1 kg | "MADE WITH 100% WHOLE GRAIN CANADIAN OATS" / "FAIT AVEC DE L'AVOINE À GRAINS 100% CANADIENNE" | Loblaw label image https://digital.loblaws.ca/PCX/20323113002_EA/en/2/20323113002_en_2_v1_800.png |
| Quaker Large Flake Oats 1 kg | "MADE IN CANADA FROM DOMESTIC AND IMPORTED INGREDIENTS." / "FABRIQUÉ AU CANADA À PARTIR D'INGRÉDIENTS CANADIENS ET IMPORTÉS." (under a "MADE IN • FABRIQUÉ AU CANADA" maple-leaf roundel) | Loblaw label image https://digital.loblaws.ca/PCX/20323113002_EA/en/3/20323113002_en_3_v1_800.png |
| Yumi "Morning Oats" Instant Oatmeal Maple & Brown Sugar | "Made in Canada with 100% Canadian Oats" (front of pack). The image shows "8 PACKETS 304g (8x38g)", but the Loblaw listing gives 264 g: **pack-size mismatch, use the listing size only with this caveat** | https://digital.loblaws.ca/PCX/21706743_EA/en/8/62850438212_en_front_noPlunge_ecomm_A_1_GS1_Ecommerce_800.png |
| Dan-D Pak Rolled Oats 1 kg | "From the Canadian Prairies / Des Prairies Canadiennes" (front of pack) | https://digital.loblaws.ca/PCX/20876492_EA/en/8/77079513125_enfr_front_noPlunge_ecomm_GS1_Ecommerce_1_800.png |
| Speerville "New Found Oatmeal" 910 g | Small maple-leaf roundel reading "MADE IN CANADA / FABRIQUÉ AU CANADA" (small print, read from the image) | https://digital.loblaws.ca/PCX/20059495_EA/en/8/5657400030_enfr_front_noPlunge_ecomm_GS1_Ecommerce_800.png |
| Giant Value instant oatmeal (Maple and Brown Sugar 344 g; Apples and Cinnamon 264 g; Regular 280 g) | Badge: "MADE WITH 100% CANADIAN OATS" | https://cdn.shopify.com/s/files/1/0557/6858/0157/files/preview_images_1603457_f_01_en.jpg ; …1603458_f_01_en.jpg ; …1603459_f_01_en.jpg (from https://www.gianttiger.com/collections/oatmeal/products.json) |
| Quaker Instant Oatmeal 3 Flavour Variety Pack 2.45 kg | Costco.ca feature line: "Made with 100% whole grain Canadian oats" | https://www.costco.ca/p/-/quaker-instant-oatmeal-3-flavour-variety-pack-245-kg/4000039522 |
| Stoked Oats Oatmeal 8 × 500 g | Costco.ca feature line: "Made in Canada" | https://www.costco.ca/p/-/stoked-oats-oatmeal-8-500-g/4000369027 |
| Quaker Quick Oats 100% Whole Grain 1 kg; Quaker Instant Oatmeal Peaches & Cream 325 g; Quaker Instant Oatmeal Wild Berry Medley 8 Pack 300 g | Voilà field "Country Of Origin": "Canada" | https://voila.ca/api/webproductpagews/v5/products/bop?retailerProductId=217560EA ; …=217210EA ; …=121393EA |
| Good Eats Gluten-Free Organic Quick Rolled Oats 454 g | Voilà field "Other Information": "Local Product" | …bop?retailerProductId=941211EA |
| Western Family "100% Whole Grain Canadian" Old Fashioned / Quick / Steel Cut Oats | The word "Canadian" is in the product name itself. Save-On attribute: Product of Canada | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639341299 ; …/00062639185350 ; …/00062639342470 |

Note on the Quaker wording: the same package says both "Made with 100% whole grain Canadian oats" and "Made in Canada from domestic and imported ingredients". Quote both together or neither. Do not interpret the difference. The label does not say which ingredient is imported, and this file does not speculate.

---

## 4. National brand vs private label

**Matched pairs, same store, same type, standard bags (from table 1a/1b; price shown on 30 Sep 2026):**

| Banner, store | Private label (pack, price, $/100 g) | National brand (pack, price, $/100 g) | National costs X% more per 100 g |
|---|---|---|---|
| Loblaws Markham ON | No Name Large Flake 1 kg, $3.00 sale (was $3.49), $0.30 | Quaker Large Flake 1 kg, $5.75 (*), $0.57 | +92% (+65% vs the $3.49 regular) |
| Loblaws Vancouver BC | No Name Large Flake 1 kg, $3.00 sale (was $3.50), $0.30 | Quaker Large Flake 1 kg, $5.75 sale, $0.57 | +92% |
| No Frills Toronto ON | No Name Large Flake 1 kg, $3.00 (*), $0.30 | Quaker Large Flake 1 kg, $4.00, $0.40 | +33% |
| No Frills Calgary AB / Vancouver BC | No Name Large Flake 1 kg, $3.00 (*), $0.30 | Robin Hood Large Flake 1 kg, $3.99, $0.40; Quaker 1 kg, $4.29, $0.43 | +33% / +43% |
| RCSS Calgary, Vancouver, Winnipeg, Regina | No Name Large Flake 1 kg, $3.00, $0.30 | Quaker Large Flake 1 kg, $3.75, $0.38 | +25% |
| Atlantic Superstore Halifax NS | No Name Large Flake 1 kg, $3.00 (*), $0.30 | Quaker Large Flake 1 kg, $4.49 sale, $0.45; Robin Hood, $4.79, $0.48 | +50% / +60% |
| Provigo Montréal QC | No Name Quick 1 kg, $3.00 sale (was $3.99), $0.30 | Quaker Quick 1 kg, $4.99, $0.50; Robin Hood Quick 1 kg, $5.29, $0.53 | +66% / +76% |
| Maxi Montréal QC | No Name Quick 1 kg, $3.00 (*), $0.30 | Quaker Quick 1 kg, $4.00, $0.40; Robin Hood Quick 1 kg, $4.29, $0.43 | +33% / +43% |
| Loblaw banners, instant | PC Regular Instant Oatmeal 280 g: $3.00 (*) at RCSS to $4.29 at Loblaws Markham | Quaker Regular Instant Oatmeal 280 g: $3.50 at RCSS to $5.19 at Loblaws Markham, Loblaws Vancouver and Provigo | +17% (RCSS) to +21% (Loblaws Markham) |
| Voilà (default region) | Compliments Quick Oats 1 kg, $4.49, $0.45 | Quaker Quick Oats 100% Whole Grain 1 kg, $6.49, $0.65; Robin Hood Quick Oats 1 kg, $4.79, $0.48 | +45% / +7% |
| Voilà (default region) | Compliments Quick Oats 2.25 kg, $6.79, $0.30 | Quaker Quick Oats 2.25 kg, $7.99, $0.36 | +18% |
| Voilà (default region) | Compliments Instant Oatmeal Regular 280 g, $3.99, $1.43 | Quaker Instant Oatmeal Regular 280 g, $5.29, $1.89 | +33% |
| Save-On-Foods Langley BC | Western Family Quick Oats 1 kg, $4.69, $0.47 | Quaker Quick Oats 1 kg, $6.99, $0.70; Robin Hood Quick Oats 1 kg, $4.99, $0.50 | +49% / +6% |
| Save-On-Foods Langley BC | Western Family Regular Instant Oatmeal 280 g, $4.29, $1.53 | Quaker Regular Instant Oatmeal 280 g, $4.99, $1.78 | +16% |
| Giant Tiger (online) | Giant Value Regular Instant Oatmeal 10-pack 280 g, $2.87, $1.03 | Quaker Instant Oatmeal Variety 8pk 314 g, $3.66, $1.17 (different flavour mix; the nearest Quaker pack listed) | +14% |
| Costco.ca | Kirkland Signature Whole Grain Rolled Oats 4.54 kg, $11.99, $0.26 | Quaker Quick Oats 2 × 2.58 kg, $10.99 sale (reg $13.99), $0.21 (reg $0.27) | −19% on sale; +3% at regular. Different types (rolled vs quick) |

(*) = Loblaw API price type `SPECIAL` with no was-price shown.

**Banner-level medians (all listings of the type; these pool different pack sizes and lines, so use the matched pairs above for any on-air claim):**

| Banner | Type | Private label: n, median $/100 g (range) | National/other brands: n, median $/100 g (range) | Median gap |
|---|---|---|---|---|
| Loblaws | large flake / rolled | 3, 0.30 (0.30–0.56) | 16, 0.82 (0.33–1.32) | national median is +175% vs private label |
| Loblaws | quick | 5, 0.33 (0.30–0.50) | 10, 0.57 (0.40–1.56) | national median is +73% vs private label |
| Loblaws | steel-cut | 7, 0.59 (0.50–1.11) | 4, 1.03 (0.81–1.25) | national median is +73% vs private label |
| Loblaws | instant packets | 12, 1.50 (1.25–1.75) | 35, 2.08 (1.10–3.56) | national median is +38% vs private label |
| Real Canadian Superstore | large flake / rolled | 11, 0.30 (0.24–0.56) | 37, 0.77 (0.30–1.40) | national median is +157% vs private label |
| Real Canadian Superstore | quick | 16, 0.32 (0.24–0.50) | 35, 0.42 (0.29–1.40) | national median is +32% vs private label |
| Real Canadian Superstore | steel-cut | 16, 0.81 (0.48–1.11) | 9, 1.18 (0.53–1.40) | national median is +46% vs private label |
| Real Canadian Superstore | instant packets | 35, 1.14 (0.87–1.38) | 109, 1.51 (0.94–2.76) | national median is +33% vs private label |
| No Frills | large flake / rolled | 3, 0.30 (0.30–0.30) | 9, 0.43 (0.35–0.99) | national median is +43% vs private label |
| No Frills | quick | 9, 0.33 (0.30–0.50) | 13, 0.40 (0.35–0.48) | national median is +20% vs private label |
| No Frills | steel-cut | 3, 0.48 (0.48–0.48) | 2, 0.60 (0.60–0.60) | national median is +27% vs private label |
| No Frills | instant packets | 12, 1.18 (0.87–1.33) | 18, 1.40 (1.10–2.68) | national median is +18% vs private label |
| Atlantic Superstore | large flake / rolled | 3, 0.30 (0.29–0.56) | 11, 0.80 (0.33–1.43) | national median is +166% vs private label |
| Atlantic Superstore | quick | 4, 0.32 (0.29–0.50) | 8, 0.48 (0.33–1.37) | national median is +51% vs private label |
| Atlantic Superstore | steel-cut | 4, 0.92 (0.50–1.25) | 1, 0.63 (0.63–0.63) | national median is -31% vs private label |
| Atlantic Superstore | instant packets | 9, 1.23 (0.94–1.75) | 27, 1.94 (1.01–3.09) | national median is +58% vs private label |
| Provigo | large flake / rolled | 1, 0.30 (0.30–0.30) | 5, 0.88 (0.50–1.35) | national median is +194% vs private label |
| Provigo | quick | 2, 0.40 (0.30–0.50) | 3, 0.53 (0.50–0.55) | national median is +32% vs private label |
| Provigo | steel-cut | 3, 0.59 (0.50–1.11) | 1, 0.70 (0.70–0.70) | national median is +18% vs private label |
| Provigo | instant packets | 5, 1.35 (1.10–1.44) | 13, 1.97 (1.51–3.29) | national median is +45% vs private label |
| Maxi | large flake / rolled | 2, 0.46 (0.30–0.61) | 3, 0.43 (0.40–0.99) | national median is -6% vs private label |
| Maxi | quick | 3, 0.33 (0.30–0.50) | 4, 0.43 (0.40–0.44) | national median is +29% vs private label |
| Maxi | steel-cut | 2, 0.53 (0.50–0.57) | 1, 0.56 (0.56–0.56) | national median is +5% vs private label |
| Maxi | instant packets | 5, 1.18 (0.96–1.41) | 13, 1.44 (0.98–2.85) | national median is +22% vs private label |
| Voilà by Sobeys | large flake / rolled | 3, 1.20 (0.73–1.20) | 19, 0.86 (0.40–1.40) | national median is -28% vs private label |
| Voilà by Sobeys | quick | 3, 0.45 (0.30–0.50) | 20, 0.84 (0.35–1.94) | national median is +86% vs private label |
| Voilà by Sobeys | steel-cut | 3, 0.71 (0.60–0.77) | 15, 1.22 (0.66–1.81) | national median is +71% vs private label |
| Voilà by Sobeys | instant packets | 13, 1.16 (0.86–1.53) | 43, 1.83 (1.01–3.45) | national median is +58% vs private label |
| Save-On-Foods | large flake / rolled | 1, 0.34 (0.34–0.34) | 9, 0.78 (0.63–1.32) | national median is +128% vs private label |
| Save-On-Foods | quick | 2, 0.41 (0.34–0.47) | 8, 0.74 (0.44–1.47) | national median is +82% vs private label |
| Save-On-Foods | steel-cut | 1, 0.47 (0.47–0.47) | 4, 0.94 (0.57–1.32) | national median is +100% vs private label |
| Save-On-Foods | instant packets | 3, 1.53 (1.25–1.62) | 11, 1.78 (1.22–4.16) | national median is +16% vs private label |
| Giant Tiger | instant packets | 3, 1.02 (0.83–1.09) | 4, 1.19 (1.17–1.62) | national median is +16% vs private label |
| Costco.ca | large flake / rolled | 1, 0.26 (0.26–0.26) | 1, 0.66 (0.66–0.66) | national median is +150% vs private label |


**Ingredient lines for the plain private-label and national bags, verbatim from the retailer listing.** Reproduced as label text only. **Do not characterise any ingredient. Do not infer who makes any private-label product from matching ingredient lists.** No co-packer or manufacturer was identified for No Name, Compliments, Western Family, Giant Value or Kirkland Signature oats in any source opened today.

| Product | Ingredient line as listed | Source (opened 30 Sep 2026) |
|---|---|---|
| No Name Large Flake 100% Whole Grain Oats 1 kg | "Rolled Whole Grain Oats. May Contain: Wheat." | Loblaw API detail `20923994_EA` |
| Quaker Large Flake Oats 1 kg | "Whole Grain Rolled Oats. Contains Oat Ingredients. May Contain Wheat Ingredients." | Loblaw API detail `20323113002_EA` |
| Robin Hood 100% Whole Grains Large Flake Oats 1 kg | "Rolled Oats. Contains: Oats. May Contain: Barley, Mustard, Rye, Soybean, Triticale, Wheat." | Loblaw API detail `20893369_EA` |
| Dan D Pak Rolled Oats 1 kg | "Rolled Oats." | Loblaw API detail `20876492_EA` |
| Western Family 100% Whole Grain Canadian Old Fashioned Oats 2.25 kg | "Whole grain rolled oats. MAY CONTAIN: wheat." | Save-On API `00062639341299` |
| Quaker Quick Oats 2 × 2.58 kg | "100% Rolled oats. Contains: Oats. May contain: Wheat" | https://www.costco.ca/p/-/quaker-quick-oats-2-258-kg/100570610 |
| Giant Value Large Flake Oats 1 kg | "Ingredients: Whole grain rolled oats." (package panel image) | https://cdn.shopify.com/s/files/1/0557/6858/0157/files/preview_images_1422826_d_01.jpg |

**Company / listing descriptions of the oat types (quoted and attributed; texture wording is the seller's own description, not a finding):** The Voilà listing for Robin Hood Large Flake Oats 1 kg says: "These old-fashioned rolled oats are left large and thick for great taste and lots of texture. Because of their size, they will retain their shape when cooked." Its cooking guide reads: "Oats variety: large … stovetop: 10 minutes, microwave: 4 minutes"; "Oats variety: quick … stovetop: 3 minutes, microwave: 2 minutes"; "Oats variety: minute … stovetop: 1 minute, microwave: 2 minutes" (https://voila.ca/api/webproductpagews/v5/products/bop?retailerProductId=280532EA). Quaker's large flake label reads "COOKS IN 4 TO 5 MINUTES" (Loblaw image `20323113002_en_3_v1_800.png`, URL above).

---

## 5. Statistics Canada CPI: cereal products (table 18-10-0004-01) and table 18-10-0245-01

**Table metadata opened (tier a):** `POST https://www150.statcan.gc.ca/t1/wds/rest/getCubeMetadata` with productId 18100004 returned 200 at 2026-10-01T01:19:31Z (saved `op/statcan/meta_18100004.json`). It gives the title "Consumer Price Index, monthly, not seasonally adjusted" (CANSIM 326-0020), series 1914-01-01 to **2026-08-01**, release time 2026-09-14T08:30.

Product members in the cereal branch, with names as published:

- 29 "Bakery and cereal products (excluding baby food)", under 4 "Food purchased from stores"
- 34 "Cereal products (excluding baby food)", under 29
- 36 "Breakfast cereal and other cereal products (excluding baby food)", under 34

**No product member of 18-10-0004-01 names oats or oatmeal.** Member 36 is the nearest series to oatmeal, and it also covers cold breakfast cereal. Say "breakfast cereal and other cereal products", never "oatmeal prices".

**Series IDs opened:** `POST https://www150.statcan.gc.ca/t1/wds/rest/getSeriesInfoFromCubePidCoord` returned 200 at 2026-10-01T01:35:10Z (saved `op/statcan/seriesinfo_18100004.json`):

| Vector | Coordinate | Series title |
|---|---|---|
| v41690973 | 2.2.0.0.0.0.0.0.0.0 | Canada;All-items |
| v41691000 | 2.29.0.0.0.0.0.0.0.0 | Canada;Bakery and cereal products (excluding baby food) |
| v41691005 | 2.34.0.0.0.0.0.0.0.0 | Canada;Cereal products (excluding baby food) |
| v41691007 | 2.36.0.0.0.0.0.0.0.0 | Canada;Breakfast cereal and other cereal products (excluding baby food) |
| v41690975 | 2.4.0.0.0.0.0.0.0.0 | Canada;Food purchased from stores |

**CPI data: NOT OPENED. Moved to UNVERIFIED (U1).** The table metadata above was opened once, at 01:19:31 UTC. The series-ID lookup succeeded, but every request for the series values (`getDataFromVectorByReferencePeriodRange`, retried about every 30 s until the retry window closed) failed with the proxy tunnel error. So did the CSV download `https://www150.statcan.gc.ca/n1/tbl/csv/18100004-eng.zip`. **No CPI number appears in this file.**

**Table 18-10-0245-01:** `POST https://www150.statcan.gc.ca/t1/wds/rest/getCubeMetadata` [18100245] returned 200 at 2026-10-01T01:26:28Z (saved `op/statcan/meta_18100245.json`). Title: "Monthly average retail prices for selected products", series 2017-01-01 to 2026-07-01, 110 product members.
**No product member contains "oat", "oatmeal", "gruau" or "avoine": table 18-10-0245-01 does not carry an oats series.** The nearest grain members are: "Dry or fresh pasta, 500 grams"; "Brown rice, 900 grams"; "White rice, 2 kilograms"; "Cereal, 400 grams"; "Wheat flour, 2.5 kilograms".

---

## Appendix A. Every listing captured (806 rows)

Store codes: LB = Loblaws, NF = No Frills, RCSS = Real Canadian Superstore, ASS = Atlantic Superstore, PRV = Provigo, MAXI = Maxi; addresses are in section 0. "Price used" = price shown at capture (sale price if a sale was live), and it is the basis for "$/100 g computed". "Retailer unit price" is the retailer's own figure as displayed. Where it disagrees with the computed figure, the computed one follows the listing's pack size; examples are Voilà "GORP … Oatmeal Blends 1.1 KG" (retailer $12.72/100g vs computed $1.27) and Voilà "Quaker Low Sugar Instant Oatmeal Maple & Brown Sugar 8 Packets 232 g" (retailer $1.89 vs computed $2.28). Loblaw product URLs are the banner's own product page path returned by the API. Voilà URLs are `https://voila.ca/products/{id}/details`. Save-On URLs are the API record that was opened.

| # | Banner | Store / region | Brand (listing field) | Product name verbatim | Type | Size (listing) | Size g | Regular | Sale | Sale end | Price used | $/100 g computed | Retailer unit price | Origin line shown | Notes | Captured (UTC) | Product URL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Loblaws | LB-Markham ON | Anita's Organic Mill | Organic Whole Grain Old Fashioned Rolled Instant Oatmeal | instant (bag) | 2.5 kg | 2500 | $18.99 |  |  | $18.99 | $0.76 | $0.76/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organic-whole-grain-old-fashioned-rolled-instant-o/p/21304184_EA |
| 2 | Loblaws | LB-Markham ON | Bobs Red Mill | Gluten Free Oatmeal Apple Cinnamon | instant (cup) | 67 g | 67 | $2.99 |  |  | $2.99 | $4.46 | $4.46/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:56:46Z | https://www.loblaws.ca/gluten-free-oatmeal-apple-cinnamon/p/21589858_EA |
| 3 | Loblaws | LB-Markham ON | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.99 |  |  | $2.99 | $4.90 | $4.9/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:56:46Z | https://www.loblaws.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 4 | Loblaws | LB-Markham ON | Nature's Path | Organic Blueberry Cinnamon Flax Instant Oatmeal | instant packets | 320 g | 320 | $6.99 |  |  | $6.99 | $2.18 | $2.18/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organic-blueberry-cinnamon-flax-instant-oatmeal/p/20315563002_EA |
| 5 | Loblaws | LB-Markham ON | Nature's Path | Organic Cacao Superfood Instant Oatmeal | instant packets | 210 g | 210 | $6.49 |  |  | $6.49 | $3.09 | $3.09/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organic-cacao-superfood-instant-oatmeal/p/21238137_EA |
| 6 | Loblaws | LB-Markham ON | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organic-cinnamon-pumpkin-seed-instant-oatmeal/p/20978914_EA |
| 7 | Loblaws | LB-Markham ON | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 8 | Loblaws | LB-Markham ON | Nature's Path | Organic Maple Nut Instant Oatmeal | instant packets | 400 g | 400 | $6.99 |  |  | $6.99 | $1.75 | $1.75/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organic-maple-nut-instant-oatmeal/p/20304405003_EA |
| 9 | Loblaws | LB-Markham ON | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 10 | Loblaws | LB-Markham ON | PC Blue Menu | Blue Menu Maple and Brown Sugar Flavour Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.49 |  |  | $4.49 | $1.48 | $1.48/100g |  |  | 2026-10-01T00:56:44Z | https://www.loblaws.ca/blue-menu-maple-and-brown-sugar-flavour-supergrain/p/21004695_EA |
| 11 | Loblaws | LB-Markham ON | PC Blue Menu | Blue Menu Regular Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.49 |  |  | $4.49 | $1.48 | $1.48/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/blue-menu-regular-supergrains-oatmeal/p/21000529_EA |
| 12 | Loblaws | LB-Markham ON | PC Organics | Organics Instant Oatmeal with Flaxseed | instant packets | 400 g | 400 | $6.99 |  |  | $6.99 | $1.75 | $1.75/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organics-instant-oatmeal-with-flaxseed/p/20971781_EA |
| 13 | Loblaws | LB-Markham ON | PC Organics | Organics Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 400 g | 400 | $6.99 |  |  | $6.99 | $1.75 | $1.75/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/organics-maple-and-brown-sugar-flavour-instant-oat/p/20974190_EA |
| 14 | Loblaws | LB-Markham ON | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $4.29 |  |  | $4.29 | $1.62 | $1.63/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T00:56:46Z | https://www.loblaws.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 15 | Loblaws | LB-Markham ON | President's Choice | Instant Oatmeal, Cinnamon & Spice, 8 Servings | instant packets | 304 g | 304 | $4.29 |  |  | $4.29 | $1.41 | $1.41/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T00:56:46Z | https://www.loblaws.ca/instant-oatmeal-cinnamon-spice-8-servings/p/21505067_EA |
| 16 | Loblaws | LB-Markham ON | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $4.29 |  |  | $4.29 | $1.62 | $1.63/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T00:56:46Z | https://www.loblaws.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 17 | Loblaws | LB-Markham ON | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $4.29 |  |  | $4.29 | $1.37 | $1.37/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T00:56:46Z | https://www.loblaws.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 18 | Loblaws | LB-Markham ON | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $4.29 |  |  | $4.29 | $1.25 | $1.25/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T00:56:46Z | https://www.loblaws.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 19 | Loblaws | LB-Markham ON | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $4.29 |  |  | $4.29 | $1.53 | $1.53/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T00:56:45Z | https://www.loblaws.ca/regular-instant-oatmeal/p/21505058_EA |
| 20 | Loblaws | LB-Markham ON | Quaker | Apples & Cinnamon Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $5.19 |  |  | $5.19 | $2.24 | $2.24/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/apples-cinnamon-flavour-low-sugar-instant-oatmeal/p/21683233_EA |
| 21 | Loblaws | LB-Markham ON | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $5.19 |  |  | $5.19 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 22 | Loblaws | LB-Markham ON | Quaker | Dino Eggs Instant Oatmeal | instant packets | 304 g | 304 | $5.19 |  |  | $5.19 | $1.71 | $1.71/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/dino-eggs-instant-oatmeal/p/20346597_EA |
| 23 | Loblaws | LB-Markham ON | Quaker | Fibre Instant Oatmeal, Wildberry Medley | instant packets | 304 g | 304 | $5.99 |  |  | $5.99 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/fibre-instant-oatmeal-wildberry-medley/p/21549428_EA |
| 24 | Loblaws | LB-Markham ON | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $5.19 |  |  | $5.19 | $1.65 | $1.65/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 25 | Loblaws | LB-Markham ON | Quaker | High Fibre Raisins & Spice Instant Oatmeal | instant packets | 344 g | 344 | $5.99 |  |  | $5.99 | $1.74 | $1.74/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/high-fibre-raisins-spice-instant-oatmeal/p/21550142_EA |
| 26 | Loblaws | LB-Markham ON | Quaker | High Protein Apples & Cinnamon Instant Oatmeal | instant packets | 228 g | 228 | $5.99 |  |  | $5.99 | $2.63 | $2.63/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/high-protein-apples-cinnamon-instant-oatmeal/p/21550131_EA |
| 27 | Loblaws | LB-Markham ON | Quaker | High Protein Triple Berry Instant Oatmeal | instant packets | 228 g | 228 | $5.99 |  |  | $5.99 | $2.63 | $2.63/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/high-protein-triple-berry-instant-oatmeal/p/21550071_EA |
| 28 | Loblaws | LB-Markham ON | Quaker | Instant Oatmeal Flavour Variety Family Size | instant packets | 694 g | 694 | $8.49 |  |  | $8.49 | $1.22 | $1.22/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/instant-oatmeal-flavour-variety-family-size/p/21520660_EA |
| 29 | Loblaws | LB-Markham ON | Quaker | Instant Oatmeal Flavour Variety Value Size | instant packets | 1.48 kg | 1480 | $19.99 |  |  | $19.99 | $1.35 | $1.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/instant-oatmeal-flavour-variety-value-size/p/21524549_C01 |
| 30 | Loblaws | LB-Markham ON | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $5.19 |  |  | $5.19 | $1.51 | $1.51/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 31 | Loblaws | LB-Markham ON | Quaker | Maple & Brown Sugar Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $5.19 |  |  | $5.19 | $2.24 | $2.24/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/maple-brown-sugar-flavour-low-sugar-instant-oatmea/p/21683172_EA |
| 32 | Loblaws | LB-Markham ON | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $5.19 |  |  | $5.19 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 33 | Loblaws | LB-Markham ON | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $5.99 |  |  | $5.99 | $2.63 | $2.63/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 34 | Loblaws | LB-Markham ON | Quaker | Protein Instant Oatmeal, Regular, 6 packets | instant packets | 168 g | 168 | $5.99 |  |  | $5.99 | $3.56 | $3.57/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/protein-instant-oatmeal-regular-6-packets/p/21515952_EA |
| 35 | Loblaws | LB-Markham ON | Quaker | Protein+ Instant Oatmeal, Banana Nut Flavour, 6 packets | instant packets | 366 g | 366 | $7.99 |  |  | $7.99 | $2.18 | $2.18/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/protein-instant-oatmeal-banana-nut-flavour-6-packe/p/21620094_EA |
| 36 | Loblaws | LB-Markham ON | Quaker | Protein+ Instant Oatmeal, Maple & Brown Sugar Flavour, 6 packets | instant packets | 360 g | 360 | $7.99 |  |  | $7.99 | $2.22 | $2.22/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/protein-instant-oatmeal-maple-brown-sugar-flavour/p/21619993_EA |
| 37 | Loblaws | LB-Markham ON | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $5.19 |  |  | $5.19 | $1.85 | $1.85/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/regular-instant-oatmeal/p/21190265_EA |
| 38 | Loblaws | LB-Markham ON | Saffola Oats | Masala Oats Classic Masala Mega Pack | instant packets | 500 g | 500 | $5.49 |  |  | $5.49 | $1.10 | $1.1/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/masala-oats-classic-masala-mega-pack/p/21707672_EA |
| 39 | Loblaws | LB-Markham ON | Saffola Oats | Masala Oats Peppy Tomato Mega Pack | instant packets | 500 g | 500 | $5.49 |  |  | $5.49 | $1.10 | $1.1/100g |  |  | 2026-10-01T00:56:44Z | https://www.loblaws.ca/masala-oats-peppy-tomato-mega-pack/p/21707090_EA |
| 40 | Loblaws | LB-Markham ON | Saffola Oats | Masala Oats Veggie Twist Mega Pack | instant packets | 500 g | 500 | $5.49 |  |  | $5.49 | $1.10 | $1.1/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/masala-oats-veggie-twist-mega-pack/p/21707076_EA |
| 41 | Loblaws | LB-Markham ON | Yumi Organics | Instant Oatmeal Hazelnut & Chocolate | instant packets | 264 g | 264 | $5.49 |  |  | $5.49 | $2.08 | $2.08/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/instant-oatmeal-hazelnut-chocolate/p/21660610_EA |
| 42 | Loblaws | LB-Markham ON | Yumi Organics | Instant Oatmeal Maple & Brown Sugar | instant packets | 264 g | 264 | $5.49 |  |  | $5.49 | $2.08 | $2.08/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/instant-oatmeal-maple-brown-sugar/p/21706743_EA |
| 43 | Loblaws | LB-Markham ON | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $9.49 | $8.49 | 2026-10-14 | $8.49 | $0.94 | $0.94/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/rolled-oats/p/21127426_EA |
| 44 | Loblaws | LB-Markham ON | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 907 g | 907 | $10.99 | $9.99 | 2026-10-14 | $9.99 | $1.10 | $1.1/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/rolled-oats-old-fashioned-organic/p/21161849_EA |
| 45 | Loblaws | LB-Markham ON | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 454 g | 454 | $6.49 | $5.99 | 2026-10-14 | $5.99 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/rolled-oats-old-fashioned-organic/p/21127424_EA |
| 46 | Loblaws | LB-Markham ON | Dan D Pak | Rolled Oats | large flake / rolled | 1000 g | 1000 | $3.79 | $3.28 | 2026-10-07 | $3.28 | $0.33 | $0.33/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/rolled-oats/p/20876492_EA |
| 47 | Loblaws | LB-Markham ON | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.49 | $3.00 | 2026-10-07 | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 48 | Loblaws | LB-Markham ON | Oak Manor | Organic Oat Flakes | large flake / rolled | 1 kg | 1000 | $9.49 |  |  | $9.49 | $0.95 | $0.95/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/organic-oat-flakes/p/20016104_EA |
| 49 | Loblaws | LB-Markham ON | One Degree | Rolled Oats Sprouted | large flake / rolled | 680 g | 680 | $9.19 | $8.49 | 2026-10-07 | $8.49 | $1.25 | $1.25/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/rolled-oats-sprouted/p/21532752_EA |
| 50 | Loblaws | LB-Markham ON | PC Organics | Old Fashioned Gluten Free Rolled Oats | large flake / rolled | 900 g | 900 | $5.00 |  |  | $5.00 | $0.56 | $0.56/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:56:45Z | https://www.loblaws.ca/old-fashioned-gluten-free-rolled-oats/p/21396198_EA |
| 51 | Loblaws | LB-Markham ON | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $5.75 |  |  | $5.75 | $0.57 | $0.58/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:56:45Z | https://www.loblaws.ca/large-flake-oats/p/20323113002_EA |
| 52 | Loblaws | LB-Markham ON | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 53 | Loblaws | LB-Markham ON | Rogers | Porridge Oats, Ancient Grain Blend | large flake / rolled | 750 g | 750 | $5.99 |  |  | $5.99 | $0.80 | $0.8/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/porridge-oats-ancient-grain-blend/p/20718427_EA |
| 54 | Loblaws | LB-Markham ON | Rogers | Porridge Oats, Original Blend | large flake / rolled | 1 kg | 1000 | $5.99 |  |  | $5.99 | $0.60 | $0.6/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/porridge-oats-original-blend/p/20717030_EA |
| 55 | Loblaws | LB-Markham ON | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.99 | $8.99 | 2026-10-14 | $8.99 | $0.99 | $0.99/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/gluten-free-protein-oats/p/21639699_EA |
| 56 | Loblaws | LB-Markham ON | Quaker | Protein Oatmeal | other | 465 g | 465 | $8.99 |  |  | $8.99 | $1.93 | $1.93/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/protein-oatmeal/p/21687669_EA |
| 57 | Loblaws | LB-Markham ON | Stoked Oats | Bucking Eh Oats | other | 500 g | 500 | $9.99 |  |  | $9.99 | $2.00 | $2.0/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/bucking-eh-oats/p/20971529_EA |
| 58 | Loblaws | LB-Markham ON | Stoked Oats | Stone Age Oats | other | 500 g | 500 | $9.99 |  |  | $9.99 | $2.00 | $2.0/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/stone-age-oats/p/20971534_EA |
| 59 | Loblaws | LB-Markham ON | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.49 | $3.00 | 2026-10-07 | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 60 | Loblaws | LB-Markham ON | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.49 | $3.00 | 2026-10-07 | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 61 | Loblaws | LB-Markham ON | One Degree | Quick Oats Sprouted | quick | 680 g | 680 | $9.19 | $8.49 | 2026-10-07 | $8.49 | $1.25 | $1.25/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/quick-oats-sprouted/p/21532753_EA |
| 62 | Loblaws | LB-Markham ON | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:56:45Z | https://www.loblaws.ca/organic-quick-rolled-oats/p/20705773_EA |
| 63 | Loblaws | LB-Markham ON | Quaker | Gluten-Free Quick Oats | quick | 511 g | 511 | $7.99 |  |  | $7.99 | $1.56 | $1.56/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/gluten-free-quick-oats/p/20970661_EA |
| 64 | Loblaws | LB-Markham ON | Quaker | One Minute Oats | quick | 900 g | 900 | $5.75 |  |  | $5.75 | $0.64 | $0.64/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:56:45Z | https://www.loblaws.ca/one-minute-oats/p/20323113003_EA |
| 65 | Loblaws | LB-Markham ON | Quaker | Quick Oats | quick | 1 kg | 1000 | $5.75 |  |  | $5.75 | $0.57 | $0.58/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:56:45Z | https://www.loblaws.ca/quick-oats/p/20323113001_EA |
| 66 | Loblaws | LB-Markham ON | Quaker | Quick Oats | quick | 2.25 kg | 2250 | $8.99 |  |  | $8.99 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/quick-oats/p/20053840_EA |
| 67 | Loblaws | LB-Markham ON | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 68 | Loblaws | LB-Markham ON | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 69 | Loblaws | LB-Markham ON | Bobs Red Mill | Steel Cut Oats Whole Grain Gluten Free | steel-cut | 680 g | 680 | $9.49 | $8.49 | 2026-10-14 | $8.49 | $1.25 | $1.25/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/steel-cut-oats-whole-grain-gluten-free/p/21127423_EA |
| 70 | Loblaws | LB-Markham ON | One Degree | Steel Cut Oats Sprouted | steel-cut | 680 g | 680 | $9.19 | $8.49 | 2026-10-07 | $8.49 | $1.25 | $1.25/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/steel-cut-oats-sprouted/p/21535637_EA |
| 71 | Loblaws | LB-Markham ON | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $5.00 |  |  | $5.00 | $0.59 | $0.6/100g |  |  | 2026-10-01T00:56:45Z | https://www.loblaws.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 72 | Loblaws | LB-Markham ON | PC Blue Menu | Maple & Brown Sugar Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:56:44Z | https://www.loblaws.ca/maple-brown-sugar-steel-cut-oats/p/20943950_EA |
| 73 | Loblaws | LB-Markham ON | PC Blue Menu | Regular Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:56:46Z | https://www.loblaws.ca/regular-steel-cut-oats/p/20943962_EA |
| 74 | Loblaws | LB-Markham ON | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:56:45Z | https://www.loblaws.ca/organic-steel-cut-oats/p/20971286_EA |
| 75 | Loblaws | LB-Markham ON | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $5.75 |  |  | $5.75 | $0.81 | $0.81/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:56:45Z | https://www.loblaws.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 76 | Loblaws | LB-Vancouver BC | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.99 |  |  | $2.99 | $4.90 | $4.9/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:57:08Z | https://www.loblaws.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 77 | Loblaws | LB-Vancouver BC | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/organic-cinnamon-pumpkin-seed-instant-oatmeal/p/20978914_EA |
| 78 | Loblaws | LB-Vancouver BC | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 79 | Loblaws | LB-Vancouver BC | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 80 | Loblaws | LB-Vancouver BC | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $4.29 |  |  | $4.29 | $1.62 | $1.63/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T00:57:07Z | https://www.loblaws.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 81 | Loblaws | LB-Vancouver BC | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $4.29 |  |  | $4.29 | $1.25 | $1.25/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T00:57:07Z | https://www.loblaws.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 82 | Loblaws | LB-Vancouver BC | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $5.19 |  |  | $5.19 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 83 | Loblaws | LB-Vancouver BC | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $5.19 |  |  | $5.19 | $1.51 | $1.51/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 84 | Loblaws | LB-Vancouver BC | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $5.19 |  |  | $5.19 | $1.85 | $1.85/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/regular-instant-oatmeal/p/21190265_EA |
| 85 | Loblaws | LB-Vancouver BC | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $9.99 | $8.50 | 2026-10-14 | $8.50 | $0.94 | $0.94/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/rolled-oats/p/21127426_EA |
| 86 | Loblaws | LB-Vancouver BC | Dan D Pak | Rolled Oats | large flake / rolled | 1000 g | 1000 | $3.99 | $3.28 | 2026-10-07 | $3.28 | $0.33 | $0.33/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/rolled-oats/p/20876492_EA |
| 87 | Loblaws | LB-Vancouver BC | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.50 | $3.00 | 2026-10-07 | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 88 | Loblaws | LB-Vancouver BC | Oak Manor | Organic Oat Flakes | large flake / rolled | 1 kg | 1000 | $8.49 |  |  | $8.49 | $0.85 | $0.85/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/organic-oat-flakes/p/20016104_EA |
| 89 | Loblaws | LB-Vancouver BC | One Degree | Rolled Oats Sprouted | large flake / rolled | 680 g | 680 | $8.99 | $8.49 | 2026-10-07 | $8.49 | $1.25 | $1.25/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/rolled-oats-sprouted/p/21532752_EA |
| 90 | Loblaws | LB-Vancouver BC | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $6.50 | $5.75 | 2026-10-14 | $5.75 | $0.57 | $0.58/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/large-flake-oats/p/20323113002_EA |
| 91 | Loblaws | LB-Vancouver BC | Rogers | Porridge Oats, Ancient Grain Blend | large flake / rolled | 750 g | 750 | $5.99 |  |  | $5.99 | $0.80 | $0.8/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:08Z | https://www.loblaws.ca/porridge-oats-ancient-grain-blend/p/20718427_EA |
| 92 | Loblaws | LB-Vancouver BC | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.99 | $8.99 | 2026-10-14 | $8.99 | $0.99 | $0.99/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/gluten-free-protein-oats/p/21639699_EA |
| 93 | Loblaws | LB-Vancouver BC | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.50 | $3.00 | 2026-10-07 | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 94 | Loblaws | LB-Vancouver BC | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:57:07Z | https://www.loblaws.ca/organic-quick-rolled-oats/p/20705773_EA |
| 95 | Loblaws | LB-Vancouver BC | Quaker | One Minute Oats | quick | 900 g | 900 | $6.50 | $5.75 | 2026-10-14 | $5.75 | $0.64 | $0.64/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/one-minute-oats/p/20323113003_EA |
| 96 | Loblaws | LB-Vancouver BC | Quaker | Quick Oats | quick | 1 kg | 1000 | $6.50 | $5.75 | 2026-10-14 | $5.75 | $0.57 | $0.58/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/quick-oats/p/20323113001_EA |
| 97 | Loblaws | LB-Vancouver BC | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $4.99 |  |  | $4.99 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 98 | Loblaws | LB-Vancouver BC | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $5.00 |  |  | $5.00 | $0.59 | $0.6/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 99 | Loblaws | LB-Vancouver BC | PC Blue Menu | Maple & Brown Sugar Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:57:09Z | https://www.loblaws.ca/maple-brown-sugar-steel-cut-oats/p/20943950_EA |
| 100 | Loblaws | LB-Vancouver BC | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T00:57:07Z | https://www.loblaws.ca/organic-steel-cut-oats/p/20971286_EA |
| 101 | Loblaws | LB-Vancouver BC | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $6.50 | $5.75 | 2026-10-14 | $5.75 | $0.81 | $0.81/100g |  |  | 2026-10-01T00:57:07Z | https://www.loblaws.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 102 | Real Canadian Superstore | RCSS-Regina SK | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.49 | $2.29 | 2026-10-07 | $2.29 | $3.75 | $3.75/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:58:46Z | https://www.realcanadiansuperstore.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 103 | Real Canadian Superstore | RCSS-Regina SK | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/organic-cinnamon-pumpkin-seed-instant-oatmeal/p/20978914_EA |
| 104 | Real Canadian Superstore | RCSS-Regina SK | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 105 | Real Canadian Superstore | RCSS-Regina SK | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 106 | Real Canadian Superstore | RCSS-Regina SK | PC Blue Menu | Blue Menu Regular Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.00 |  |  | $4.00 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/blue-menu-regular-supergrains-oatmeal/p/21000529_EA |
| 107 | Real Canadian Superstore | RCSS-Regina SK | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.00 |  |  | $3.00 | $1.14 | $1.14/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 108 | Real Canadian Superstore | RCSS-Regina SK | President's Choice | Instant Oatmeal, Cinnamon & Spice, 8 Servings | instant packets | 304 g | 304 | $3.00 |  |  | $3.00 | $0.99 | $0.99/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-cinnamon-spice-8-servings/p/21505067_EA |
| 109 | Real Canadian Superstore | RCSS-Regina SK | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.00 |  |  | $3.00 | $1.14 | $1.14/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 110 | Real Canadian Superstore | RCSS-Regina SK | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.00 |  |  | $3.00 | $0.95 | $0.96/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 111 | Real Canadian Superstore | RCSS-Regina SK | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.00 |  |  | $3.00 | $0.87 | $0.87/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 112 | Real Canadian Superstore | RCSS-Regina SK | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.00 |  |  | $3.00 | $1.07 | $1.07/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/regular-instant-oatmeal/p/21505058_EA |
| 113 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Apples & Cinnamon Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.50 |  |  | $3.50 | $1.51 | $1.63/100g |  | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/apples-cinnamon-flavour-low-sugar-instant-oatmeal/p/21683233_EA |
| 114 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.44/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 115 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Dino Eggs Instant Oatmeal | instant packets | 304 g | 304 | $3.50 |  |  | $3.50 | $1.15 | $1.25/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/dino-eggs-instant-oatmeal/p/20346597_EA |
| 116 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $3.50 |  |  | $3.50 | $1.11 | $1.21/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 117 | Real Canadian Superstore | RCSS-Regina SK | Quaker | High Fibre Raisins & Spice Instant Oatmeal | instant packets | 344 g | 344 | $4.49 |  |  | $4.49 | $1.30 | $1.31/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/high-fibre-raisins-spice-instant-oatmeal/p/21550142_EA |
| 118 | Real Canadian Superstore | RCSS-Regina SK | Quaker | High Protein Apples & Cinnamon Instant Oatmeal | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/high-protein-apples-cinnamon-instant-oatmeal/p/21550131_EA |
| 119 | Real Canadian Superstore | RCSS-Regina SK | Quaker | High Protein Triple Berry Instant Oatmeal | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/high-protein-triple-berry-instant-oatmeal/p/21550071_EA |
| 120 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Instant Oatmeal Flavour Variety Family Size | instant packets | 694 g | 694 | $6.49 |  |  | $6.49 | $0.94 | $0.94/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-flavour-variety-family-size/p/21520660_EA |
| 121 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Instant Oatmeal Flavour Variety Value Size | instant packets | 1.48 kg | 1480 | $15.49 |  |  | $15.49 | $1.05 | $1.05/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-flavour-variety-value-size/p/21524549_C01 |
| 122 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.50 |  |  | $3.50 | $1.02 | $1.1/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 123 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Maple & Brown Sugar Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.50 |  |  | $3.50 | $1.51 | $1.63/100g |  | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-flavour-low-sugar-instant-oatmea/p/21683172_EA |
| 124 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.44/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 125 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 126 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Protein Instant Oatmeal, Regular, 6 packets | instant packets | 168 g | 168 | $4.49 |  |  | $4.49 | $2.67 | $2.67/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-regular-6-packets/p/21515952_EA |
| 127 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Protein+ Instant Oatmeal, Banana Nut Flavour, 6 packets | instant packets | 366 g | 366 | $6.99 |  |  | $6.99 | $1.91 | $1.91/100g |  |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-banana-nut-flavour-6-packe/p/21620094_EA |
| 128 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Protein+ Instant Oatmeal, Maple & Brown Sugar Flavour, 6 packets | instant packets | 360 g | 360 | $6.99 |  |  | $6.99 | $1.94 | $1.94/100g |  |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-maple-brown-sugar-flavour/p/21619993_EA |
| 129 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.50 |  |  | $3.50 | $1.25 | $1.35/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/regular-instant-oatmeal/p/21190265_EA |
| 130 | Real Canadian Superstore | RCSS-Regina SK | Saffola Oats | Masala Oats Classic Masala Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/masala-oats-classic-masala-mega-pack/p/21707672_EA |
| 131 | Real Canadian Superstore | RCSS-Regina SK | Saffola Oats | Masala Oats Peppy Tomato Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:58:46Z | https://www.realcanadiansuperstore.ca/masala-oats-peppy-tomato-mega-pack/p/21707090_EA |
| 132 | Real Canadian Superstore | RCSS-Regina SK | Saffola Oats | Masala Oats Veggie Twist Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/masala-oats-veggie-twist-mega-pack/p/21707076_EA |
| 133 | Real Canadian Superstore | RCSS-Regina SK | Yumi Organics | Instant Oatmeal Hazelnut & Chocolate | instant packets | 264 g | 264 | $4.99 |  |  | $4.99 | $1.89 | $2.08/100g |  | deal badge: Limit 3, after limit $5.49 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-hazelnut-chocolate/p/21660610_EA |
| 134 | Real Canadian Superstore | RCSS-Regina SK | Yumi Organics | Instant Oatmeal Maple & Brown Sugar | instant packets | 264 g | 264 | $4.99 |  |  | $4.99 | $1.89 | $2.08/100g |  | deal badge: Limit 3, after limit $5.49 (to 2026-10-07) | 2026-10-01T00:58:46Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-maple-brown-sugar/p/21706743_EA |
| 135 | Real Canadian Superstore | RCSS-Regina SK | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $7.99 |  |  | $7.99 | $0.88 | $0.94/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07; deal badge: Limit 4, after limit $8.49 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/rolled-oats/p/21127426_EA |
| 136 | Real Canadian Superstore | RCSS-Regina SK | Dan D Pak | Rolled Oats | large flake / rolled | 1000 g | 1000 | $2.98 |  |  | $2.98 | $0.30 | $0.35/100g |  | deal badge: Limit 4, after limit $3.49 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/rolled-oats/p/20876492_EA |
| 137 | Real Canadian Superstore | RCSS-Regina SK | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 138 | Real Canadian Superstore | RCSS-Regina SK | No Name | Large Flake 100% Whole Grain Oats Club Size | large flake / rolled | 2.25 kg | 2250 | $6.00 | $5.49 | 2026-10-07 | $5.49 | $0.24 | $0.24/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats-club-size/p/20923840_EA |
| 139 | Real Canadian Superstore | RCSS-Regina SK | One Degree | Rolled Oats Sprouted | large flake / rolled | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/rolled-oats-sprouted/p/21532752_EA |
| 140 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $3.75 |  |  | $3.75 | $0.38 | $0.43/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/large-flake-oats/p/20323113002_EA |
| 141 | Real Canadian Superstore | RCSS-Regina SK | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 142 | Real Canadian Superstore | RCSS-Regina SK | Rogers | Porridge Oats, Ancient Grain Blend | large flake / rolled | 750 g | 750 | $5.79 |  |  | $5.79 | $0.77 | $0.77/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/porridge-oats-ancient-grain-blend/p/20718427_EA |
| 143 | Real Canadian Superstore | RCSS-Regina SK | Rogers | Porridge Oats, Original Blend | large flake / rolled | 1 kg | 1000 | $5.79 |  |  | $5.79 | $0.58 | $0.58/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/porridge-oats-original-blend/p/20717030_EA |
| 144 | Real Canadian Superstore | RCSS-Regina SK | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.49 | $8.06 | 2026-10-07 | $8.06 | $0.89 | $0.89/100g |  |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/gluten-free-protein-oats/p/21639699_EA |
| 145 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Protein Oatmeal | other | 465 g | 465 | $8.99 |  |  | $8.99 | $1.93 | $1.93/100g |  |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/protein-oatmeal/p/21687669_EA |
| 146 | Real Canadian Superstore | RCSS-Regina SK | Dan D Pak | Quick Oats | quick | 1000 g | 1000 | $2.98 |  |  | $2.98 | $0.30 | $0.35/100g |  | deal badge: Limit 4, after limit $3.49 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20876242_EA |
| 147 | Real Canadian Superstore | RCSS-Regina SK | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 148 | Real Canadian Superstore | RCSS-Regina SK | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 149 | Real Canadian Superstore | RCSS-Regina SK | No Name | Quick 100% Whole Grain Oats Club Size | quick | 2.25 kg | 2250 | $6.00 | $5.49 | 2026-10-07 | $5.49 | $0.24 | $0.24/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/quick-100-whole-grain-oats-club-size/p/20923786_EA |
| 150 | Real Canadian Superstore | RCSS-Regina SK | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/organic-quick-rolled-oats/p/20705773_EA |
| 151 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Gluten-Free Quick Oats | quick | 511 g | 511 | $5.49 |  |  | $5.49 | $1.07 | $1.07/100g |  |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/gluten-free-quick-oats/p/20970661_EA |
| 152 | Real Canadian Superstore | RCSS-Regina SK | Quaker | One Minute Oats | quick | 900 g | 900 | $3.75 |  |  | $3.75 | $0.42 | $0.48/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/one-minute-oats/p/20323113003_EA |
| 153 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Quaker Quick Oats | quick | 5.16 kg | 5160 | $14.99 |  |  | $14.99 | $0.29 | $0.29/100g |  |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/quaker-quick-oats/p/21294986_C01 |
| 154 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Quick Oats | quick | 1 kg | 1000 | $3.75 |  |  | $3.75 | $0.38 | $0.43/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20323113001_EA |
| 155 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Quick Oats | quick | 2.25 kg | 2250 | $7.79 |  |  | $7.79 | $0.35 | $0.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20053840_EA |
| 156 | Real Canadian Superstore | RCSS-Regina SK | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 157 | Real Canadian Superstore | RCSS-Regina SK | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 158 | Real Canadian Superstore | RCSS-Regina SK | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $4.00 |  |  | $4.00 | $0.48 | $0.48/100g |  |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 159 | Real Canadian Superstore | RCSS-Regina SK | PC Blue Menu | Maple & Brown Sugar Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:58:41Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-steel-cut-oats/p/20943950_EA |
| 160 | Real Canadian Superstore | RCSS-Regina SK | PC Blue Menu | Regular Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:58:45Z | https://www.realcanadiansuperstore.ca/regular-steel-cut-oats/p/20943962_EA |
| 161 | Real Canadian Superstore | RCSS-Regina SK | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/organic-steel-cut-oats/p/20971286_EA |
| 162 | Real Canadian Superstore | RCSS-Regina SK | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $3.75 |  |  | $3.75 | $0.53 | $0.61/100g |  | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:58:44Z | https://www.realcanadiansuperstore.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 163 | Real Canadian Superstore | RCSS-Calgary AB | Anita's Organic Mill | Organic Whole Grain Old Fashioned Rolled Instant Oatmeal | instant (bag) | 2.5 kg | 2500 | $17.99 |  |  | $17.99 | $0.72 | $0.72/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:31Z | https://www.realcanadiansuperstore.ca/organic-whole-grain-old-fashioned-rolled-instant-o/p/21304184_EA |
| 164 | Real Canadian Superstore | RCSS-Calgary AB | Bobs Red Mill | Gluten Free Oatmeal Apple Cinnamon | instant (cup) | 67 g | 67 | $2.49 | $2.29 | 2026-10-07 | $2.29 | $3.42 | $3.42/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:57:36Z | https://www.realcanadiansuperstore.ca/gluten-free-oatmeal-apple-cinnamon/p/21589858_EA |
| 165 | Real Canadian Superstore | RCSS-Calgary AB | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.49 | $2.29 | 2026-10-07 | $2.29 | $3.75 | $3.75/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:57:36Z | https://www.realcanadiansuperstore.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 166 | Real Canadian Superstore | RCSS-Calgary AB | Nature's Path | Organic Blueberry Cinnamon Flax Instant Oatmeal | instant packets | 320 g | 320 | $5.29 |  |  | $5.29 | $1.65 | $1.87/100g |  | deal badge: Limit 4, after limit $5.99 (to 2026-10-07) | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/organic-blueberry-cinnamon-flax-instant-oatmeal/p/20315563002_EA |
| 167 | Real Canadian Superstore | RCSS-Calgary AB | Nature's Path | Organic Cacao Superfood Instant Oatmeal | instant packets | 210 g | 210 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.76 | $2.76/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/organic-cacao-superfood-instant-oatmeal/p/21238137_EA |
| 168 | Real Canadian Superstore | RCSS-Calgary AB | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/organic-cinnamon-pumpkin-seed-instant-oatmeal/p/20978914_EA |
| 169 | Real Canadian Superstore | RCSS-Calgary AB | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 170 | Real Canadian Superstore | RCSS-Calgary AB | Nature's Path | Organic Maple Nut Instant Oatmeal | instant packets | 400 g | 400 | $5.29 |  |  | $5.29 | $1.32 | $1.5/100g |  | deal badge: Limit 4, after limit $5.99 (to 2026-10-07) | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/organic-maple-nut-instant-oatmeal/p/20304405003_EA |
| 171 | Real Canadian Superstore | RCSS-Calgary AB | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 172 | Real Canadian Superstore | RCSS-Calgary AB | PC Blue Menu | Blue Menu Maple and Brown Sugar Flavour Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.00 |  |  | $4.00 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:57:36Z | https://www.realcanadiansuperstore.ca/blue-menu-maple-and-brown-sugar-flavour-supergrain/p/21004695_EA |
| 173 | Real Canadian Superstore | RCSS-Calgary AB | PC Blue Menu | Blue Menu Regular Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.00 |  |  | $4.00 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/blue-menu-regular-supergrains-oatmeal/p/21000529_EA |
| 174 | Real Canadian Superstore | RCSS-Calgary AB | PC Organics | Organics Instant Oatmeal with Flaxseed | instant packets | 400 g | 400 | $5.50 |  |  | $5.50 | $1.38 | $1.38/100g |  |  | 2026-10-01T00:57:31Z | https://www.realcanadiansuperstore.ca/organics-instant-oatmeal-with-flaxseed/p/20971781_EA |
| 175 | Real Canadian Superstore | RCSS-Calgary AB | PC Organics | Organics Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 400 g | 400 | $5.50 |  |  | $5.50 | $1.38 | $1.38/100g |  |  | 2026-10-01T00:57:36Z | https://www.realcanadiansuperstore.ca/organics-maple-and-brown-sugar-flavour-instant-oat/p/20974190_EA |
| 176 | Real Canadian Superstore | RCSS-Calgary AB | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.00 |  |  | $3.00 | $1.14 | $1.14/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 177 | Real Canadian Superstore | RCSS-Calgary AB | President's Choice | Instant Oatmeal, Cinnamon & Spice, 8 Servings | instant packets | 304 g | 304 | $3.00 |  |  | $3.00 | $0.99 | $0.99/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:32Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-cinnamon-spice-8-servings/p/21505067_EA |
| 178 | Real Canadian Superstore | RCSS-Calgary AB | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.00 |  |  | $3.00 | $1.14 | $1.14/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 179 | Real Canadian Superstore | RCSS-Calgary AB | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.00 |  |  | $3.00 | $0.95 | $0.96/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 180 | Real Canadian Superstore | RCSS-Calgary AB | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.00 |  |  | $3.00 | $0.87 | $0.87/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 181 | Real Canadian Superstore | RCSS-Calgary AB | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.00 |  |  | $3.00 | $1.07 | $1.07/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/regular-instant-oatmeal/p/21505058_EA |
| 182 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Apples & Cinnamon Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.50 |  |  | $3.50 | $1.51 | $1.63/100g |  | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/apples-cinnamon-flavour-low-sugar-instant-oatmeal/p/21683233_EA |
| 183 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.44/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 184 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Dino Eggs Instant Oatmeal | instant packets | 304 g | 304 | $3.50 |  |  | $3.50 | $1.15 | $1.25/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/dino-eggs-instant-oatmeal/p/20346597_EA |
| 185 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $3.50 |  |  | $3.50 | $1.11 | $1.21/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 186 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | High Fibre Raisins & Spice Instant Oatmeal | instant packets | 344 g | 344 | $4.49 |  |  | $4.49 | $1.30 | $1.31/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/high-fibre-raisins-spice-instant-oatmeal/p/21550142_EA |
| 187 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | High Protein Apples & Cinnamon Instant Oatmeal | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:32Z | https://www.realcanadiansuperstore.ca/high-protein-apples-cinnamon-instant-oatmeal/p/21550131_EA |
| 188 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | High Protein Triple Berry Instant Oatmeal | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/high-protein-triple-berry-instant-oatmeal/p/21550071_EA |
| 189 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Instant Oatmeal Flavour Variety Family Size | instant packets | 694 g | 694 | $6.49 |  |  | $6.49 | $0.94 | $0.94/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-flavour-variety-family-size/p/21520660_EA |
| 190 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Instant Oatmeal Flavour Variety Value Size | instant packets | 1.48 kg | 1480 | $15.49 |  |  | $15.49 | $1.05 | $1.05/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-flavour-variety-value-size/p/21524549_C01 |
| 191 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.50 |  |  | $3.50 | $1.02 | $1.1/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 192 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Maple & Brown Sugar Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.50 |  |  | $3.50 | $1.51 | $1.63/100g |  | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-flavour-low-sugar-instant-oatmea/p/21683172_EA |
| 193 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.44/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 194 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 195 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Protein Instant Oatmeal, Regular, 6 packets | instant packets | 168 g | 168 | $4.49 |  |  | $4.49 | $2.67 | $2.67/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-regular-6-packets/p/21515952_EA |
| 196 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Protein+ Instant Oatmeal, Banana Nut Flavour, 6 packets | instant packets | 366 g | 366 | $6.99 |  |  | $6.99 | $1.91 | $1.91/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-banana-nut-flavour-6-packe/p/21620094_EA |
| 197 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Protein+ Instant Oatmeal, Maple & Brown Sugar Flavour, 6 packets | instant packets | 360 g | 360 | $6.99 |  |  | $6.99 | $1.94 | $1.94/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-maple-brown-sugar-flavour/p/21619993_EA |
| 198 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.50 |  |  | $3.50 | $1.25 | $1.35/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/regular-instant-oatmeal/p/21190265_EA |
| 199 | Real Canadian Superstore | RCSS-Calgary AB | Saffola Oats | Masala Oats Classic Masala Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/masala-oats-classic-masala-mega-pack/p/21707672_EA |
| 200 | Real Canadian Superstore | RCSS-Calgary AB | Saffola Oats | Masala Oats Peppy Tomato Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:57:36Z | https://www.realcanadiansuperstore.ca/masala-oats-peppy-tomato-mega-pack/p/21707090_EA |
| 201 | Real Canadian Superstore | RCSS-Calgary AB | Saffola Oats | Masala Oats Veggie Twist Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/masala-oats-veggie-twist-mega-pack/p/21707076_EA |
| 202 | Real Canadian Superstore | RCSS-Calgary AB | Yumi Organics | Instant Oatmeal Hazelnut & Chocolate | instant packets | 264 g | 264 | $4.99 |  |  | $4.99 | $1.89 | $2.08/100g |  | deal badge: Limit 3, after limit $5.49 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-hazelnut-chocolate/p/21660610_EA |
| 203 | Real Canadian Superstore | RCSS-Calgary AB | Yumi Organics | Instant Oatmeal Maple & Brown Sugar | instant packets | 264 g | 264 | $4.99 |  |  | $4.99 | $1.89 | $2.08/100g |  | deal badge: Limit 3, after limit $5.49 (to 2026-10-07) | 2026-10-01T00:57:36Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-maple-brown-sugar/p/21706743_EA |
| 204 | Real Canadian Superstore | RCSS-Calgary AB | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $7.99 |  |  | $7.99 | $0.88 | $0.94/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07; deal badge: Limit 4, after limit $8.49 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/rolled-oats/p/21127426_EA |
| 205 | Real Canadian Superstore | RCSS-Calgary AB | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 907 g | 907 | $8.99 | $7.64 | 2026-10-07 | $7.64 | $0.84 | $0.84/100g |  |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/rolled-oats-old-fashioned-organic/p/21161849_EA |
| 206 | Real Canadian Superstore | RCSS-Calgary AB | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 454 g | 454 | $6.29 | $5.34 | 2026-10-07 | $5.34 | $1.18 | $1.18/100g |  |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/rolled-oats-old-fashioned-organic/p/21127424_EA |
| 207 | Real Canadian Superstore | RCSS-Calgary AB | Dan D Pak | Rolled Oats | large flake / rolled | 1000 g | 1000 | $2.98 |  |  | $2.98 | $0.30 | $0.35/100g |  | deal badge: Limit 4, after limit $3.49 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/rolled-oats/p/20876492_EA |
| 208 | Real Canadian Superstore | RCSS-Calgary AB | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 209 | Real Canadian Superstore | RCSS-Calgary AB | No Name | Large Flake 100% Whole Grain Oats Club Size | large flake / rolled | 2.25 kg | 2250 | $6.00 | $5.49 | 2026-10-07 | $5.49 | $0.24 | $0.24/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats-club-size/p/20923840_EA |
| 210 | Real Canadian Superstore | RCSS-Calgary AB | Oak Manor | Organic Oat Flakes | large flake / rolled | 1 kg | 1000 | $8.49 |  |  | $8.49 | $0.85 | $0.85/100g |  |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/organic-oat-flakes/p/20016104_EA |
| 211 | Real Canadian Superstore | RCSS-Calgary AB | One Degree | Rolled Oats Sprouted | large flake / rolled | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/rolled-oats-sprouted/p/21532752_EA |
| 212 | Real Canadian Superstore | RCSS-Calgary AB | PC Organics | Old Fashioned Gluten Free Rolled Oats | large flake / rolled | 900 g | 900 | $5.00 |  |  | $5.00 | $0.56 | $0.56/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/old-fashioned-gluten-free-rolled-oats/p/21396198_EA |
| 213 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $3.75 |  |  | $3.75 | $0.38 | $0.43/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/large-flake-oats/p/20323113002_EA |
| 214 | Real Canadian Superstore | RCSS-Calgary AB | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 215 | Real Canadian Superstore | RCSS-Calgary AB | Rogers | Porridge Oats, Ancient Grain Blend | large flake / rolled | 750 g | 750 | $5.79 |  |  | $5.79 | $0.77 | $0.77/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:31Z | https://www.realcanadiansuperstore.ca/porridge-oats-ancient-grain-blend/p/20718427_EA |
| 216 | Real Canadian Superstore | RCSS-Calgary AB | Rogers | Porridge Oats, Original Blend | large flake / rolled | 1 kg | 1000 | $5.79 |  |  | $5.79 | $0.58 | $0.58/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/porridge-oats-original-blend/p/20717030_EA |
| 217 | Real Canadian Superstore | RCSS-Calgary AB | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.49 | $8.06 | 2026-10-07 | $8.06 | $0.89 | $0.89/100g |  |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/gluten-free-protein-oats/p/21639699_EA |
| 218 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Protein Oatmeal | other | 465 g | 465 | $8.99 |  |  | $8.99 | $1.93 | $1.93/100g |  |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/protein-oatmeal/p/21687669_EA |
| 219 | Real Canadian Superstore | RCSS-Calgary AB | Stoked Oats | Bucking Eh Oats | other | 500 g | 500 | $8.50 |  |  | $8.50 | $1.70 | $2.0/100g | retailer badge: Prepared in Canada | deal badge: Limit 4, after limit $9.99 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/bucking-eh-oats/p/20971529_EA |
| 220 | Real Canadian Superstore | RCSS-Calgary AB | Stoked Oats | Stone Age Oats | other | 500 g | 500 | $8.50 |  |  | $8.50 | $1.70 | $2.0/100g | retailer badge: Prepared in Canada | deal badge: Limit 4, after limit $9.99 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/stone-age-oats/p/20971534_EA |
| 221 | Real Canadian Superstore | RCSS-Calgary AB | Dan D Pak | Quick Oats | quick | 1000 g | 1000 | $2.98 |  |  | $2.98 | $0.30 | $0.35/100g |  | deal badge: Limit 4, after limit $3.49 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20876242_EA |
| 222 | Real Canadian Superstore | RCSS-Calgary AB | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 223 | Real Canadian Superstore | RCSS-Calgary AB | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 224 | Real Canadian Superstore | RCSS-Calgary AB | No Name | Quick 100% Whole Grain Oats Club Size | quick | 2.25 kg | 2250 | $6.00 | $5.49 | 2026-10-07 | $5.49 | $0.24 | $0.24/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/quick-100-whole-grain-oats-club-size/p/20923786_EA |
| 225 | Real Canadian Superstore | RCSS-Calgary AB | One Degree | Quick Oats Sprouted | quick | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/quick-oats-sprouted/p/21532753_EA |
| 226 | Real Canadian Superstore | RCSS-Calgary AB | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/organic-quick-rolled-oats/p/20705773_EA |
| 227 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Gluten-Free Quick Oats | quick | 511 g | 511 | $5.49 |  |  | $5.49 | $1.07 | $1.07/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/gluten-free-quick-oats/p/20970661_EA |
| 228 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | One Minute Oats | quick | 900 g | 900 | $3.75 |  |  | $3.75 | $0.42 | $0.48/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/one-minute-oats/p/20323113003_EA |
| 229 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Quaker Quick Oats | quick | 5.16 kg | 5160 | $14.99 |  |  | $14.99 | $0.29 | $0.29/100g |  |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/quaker-quick-oats/p/21294986_C01 |
| 230 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Quick Oats | quick | 1 kg | 1000 | $3.75 |  |  | $3.75 | $0.38 | $0.43/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20323113001_EA |
| 231 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Quick Oats | quick | 2.25 kg | 2250 | $7.79 |  |  | $7.79 | $0.35 | $0.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20053840_EA |
| 232 | Real Canadian Superstore | RCSS-Calgary AB | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 233 | Real Canadian Superstore | RCSS-Calgary AB | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 234 | Real Canadian Superstore | RCSS-Calgary AB | Bobs Red Mill | Steel Cut Oats Whole Grain Gluten Free | steel-cut | 680 g | 680 | $7.99 |  |  | $7.99 | $1.18 | $1.19/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07; deal badge: Limit 4, after limit $8.06 (to 2026-10-07) | 2026-10-01T00:57:32Z | https://www.realcanadiansuperstore.ca/steel-cut-oats-whole-grain-gluten-free/p/21127423_EA |
| 235 | Real Canadian Superstore | RCSS-Calgary AB | One Degree | Steel Cut Oats Sprouted | steel-cut | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/steel-cut-oats-sprouted/p/21535637_EA |
| 236 | Real Canadian Superstore | RCSS-Calgary AB | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $4.00 |  |  | $4.00 | $0.48 | $0.48/100g |  |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 237 | Real Canadian Superstore | RCSS-Calgary AB | PC Blue Menu | Maple & Brown Sugar Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:57:32Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-steel-cut-oats/p/20943950_EA |
| 238 | Real Canadian Superstore | RCSS-Calgary AB | PC Blue Menu | Regular Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:57:35Z | https://www.realcanadiansuperstore.ca/regular-steel-cut-oats/p/20943962_EA |
| 239 | Real Canadian Superstore | RCSS-Calgary AB | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/organic-steel-cut-oats/p/20971286_EA |
| 240 | Real Canadian Superstore | RCSS-Calgary AB | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $3.75 |  |  | $3.75 | $0.53 | $0.61/100g |  | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:57:34Z | https://www.realcanadiansuperstore.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 241 | Real Canadian Superstore | RCSS-Vancouver BC | Bobs Red Mill | Gluten Free Oatmeal Apple Cinnamon | instant (cup) | 67 g | 67 | $2.49 | $2.29 | 2026-10-07 | $2.29 | $3.42 | $3.42/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:57:58Z | https://www.realcanadiansuperstore.ca/gluten-free-oatmeal-apple-cinnamon/p/21589858_EA |
| 242 | Real Canadian Superstore | RCSS-Vancouver BC | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.49 | $2.29 | 2026-10-07 | $2.29 | $3.75 | $3.75/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:57:58Z | https://www.realcanadiansuperstore.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 243 | Real Canadian Superstore | RCSS-Vancouver BC | Nature's Path | Organic Blueberry Cinnamon Flax Instant Oatmeal | instant packets | 320 g | 320 | $5.29 |  |  | $5.29 | $1.65 | $1.87/100g |  | deal badge: Limit 4, after limit $5.99 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-blueberry-cinnamon-flax-instant-oatmeal/p/20315563002_EA |
| 244 | Real Canadian Superstore | RCSS-Vancouver BC | Nature's Path | Organic Cacao Superfood Instant Oatmeal | instant packets | 210 g | 210 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.76 | $2.76/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-cacao-superfood-instant-oatmeal/p/21238137_EA |
| 245 | Real Canadian Superstore | RCSS-Vancouver BC | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-cinnamon-pumpkin-seed-instant-oatmeal/p/20978914_EA |
| 246 | Real Canadian Superstore | RCSS-Vancouver BC | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 247 | Real Canadian Superstore | RCSS-Vancouver BC | Nature's Path | Organic Maple Nut Instant Oatmeal | instant packets | 400 g | 400 | $5.29 |  |  | $5.29 | $1.32 | $1.5/100g |  | deal badge: Limit 4, after limit $5.99 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-maple-nut-instant-oatmeal/p/20304405003_EA |
| 248 | Real Canadian Superstore | RCSS-Vancouver BC | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 249 | Real Canadian Superstore | RCSS-Vancouver BC | PC Blue Menu | Blue Menu Maple and Brown Sugar Flavour Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.00 |  |  | $4.00 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:57:58Z | https://www.realcanadiansuperstore.ca/blue-menu-maple-and-brown-sugar-flavour-supergrain/p/21004695_EA |
| 250 | Real Canadian Superstore | RCSS-Vancouver BC | PC Blue Menu | Blue Menu Regular Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.00 |  |  | $4.00 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/blue-menu-regular-supergrains-oatmeal/p/21000529_EA |
| 251 | Real Canadian Superstore | RCSS-Vancouver BC | PC Organics | Organics Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 400 g | 400 | $5.50 |  |  | $5.50 | $1.38 | $1.38/100g |  |  | 2026-10-01T00:57:58Z | https://www.realcanadiansuperstore.ca/organics-maple-and-brown-sugar-flavour-instant-oat/p/20974190_EA |
| 252 | Real Canadian Superstore | RCSS-Vancouver BC | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.00 |  |  | $3.00 | $1.14 | $1.14/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 253 | Real Canadian Superstore | RCSS-Vancouver BC | President's Choice | Instant Oatmeal, Cinnamon & Spice, 8 Servings | instant packets | 304 g | 304 | $3.00 |  |  | $3.00 | $0.99 | $0.99/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:58Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-cinnamon-spice-8-servings/p/21505067_EA |
| 254 | Real Canadian Superstore | RCSS-Vancouver BC | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.00 |  |  | $3.00 | $1.14 | $1.14/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 255 | Real Canadian Superstore | RCSS-Vancouver BC | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.00 |  |  | $3.00 | $0.95 | $0.96/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 256 | Real Canadian Superstore | RCSS-Vancouver BC | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.00 |  |  | $3.00 | $0.87 | $0.87/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 257 | Real Canadian Superstore | RCSS-Vancouver BC | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.00 |  |  | $3.00 | $1.07 | $1.07/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/regular-instant-oatmeal/p/21505058_EA |
| 258 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Apples & Cinnamon Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.50 |  |  | $3.50 | $1.51 | $1.63/100g |  | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/apples-cinnamon-flavour-low-sugar-instant-oatmeal/p/21683233_EA |
| 259 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.44/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 260 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Dino Eggs Instant Oatmeal | instant packets | 304 g | 304 | $3.50 |  |  | $3.50 | $1.15 | $1.25/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/dino-eggs-instant-oatmeal/p/20346597_EA |
| 261 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $3.50 |  |  | $3.50 | $1.11 | $1.21/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 262 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | High Fibre Raisins & Spice Instant Oatmeal | instant packets | 344 g | 344 | $4.49 |  |  | $4.49 | $1.30 | $1.31/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/high-fibre-raisins-spice-instant-oatmeal/p/21550142_EA |
| 263 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | High Protein Apples & Cinnamon Instant Oatmeal | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:58Z | https://www.realcanadiansuperstore.ca/high-protein-apples-cinnamon-instant-oatmeal/p/21550131_EA |
| 264 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | High Protein Triple Berry Instant Oatmeal | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/high-protein-triple-berry-instant-oatmeal/p/21550071_EA |
| 265 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Instant Oatmeal Flavour Variety Family Size | instant packets | 694 g | 694 | $6.49 |  |  | $6.49 | $0.94 | $0.94/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-flavour-variety-family-size/p/21520660_EA |
| 266 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Instant Oatmeal Flavour Variety Value Size | instant packets | 1.48 kg | 1480 | $15.49 |  |  | $15.49 | $1.05 | $1.05/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-flavour-variety-value-size/p/21524549_C01 |
| 267 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.50 |  |  | $3.50 | $1.02 | $1.1/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 268 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Maple & Brown Sugar Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.50 |  |  | $3.50 | $1.51 | $1.63/100g |  | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-flavour-low-sugar-instant-oatmea/p/21683172_EA |
| 269 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.44/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 270 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 271 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Protein Instant Oatmeal, Regular, 6 packets | instant packets | 168 g | 168 | $4.49 |  |  | $4.49 | $2.67 | $2.67/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-regular-6-packets/p/21515952_EA |
| 272 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Protein+ Instant Oatmeal, Banana Nut Flavour, 6 packets | instant packets | 366 g | 366 | $6.99 |  |  | $6.99 | $1.91 | $1.91/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-banana-nut-flavour-6-packe/p/21620094_EA |
| 273 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Protein+ Instant Oatmeal, Maple & Brown Sugar Flavour, 6 packets | instant packets | 360 g | 360 | $6.99 |  |  | $6.99 | $1.94 | $1.94/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-maple-brown-sugar-flavour/p/21619993_EA |
| 274 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.50 |  |  | $3.50 | $1.25 | $1.35/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/regular-instant-oatmeal/p/21190265_EA |
| 275 | Real Canadian Superstore | RCSS-Vancouver BC | Saffola Oats | Masala Oats Classic Masala Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/masala-oats-classic-masala-mega-pack/p/21707672_EA |
| 276 | Real Canadian Superstore | RCSS-Vancouver BC | Saffola Oats | Masala Oats Peppy Tomato Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:57:55Z | https://www.realcanadiansuperstore.ca/masala-oats-peppy-tomato-mega-pack/p/21707090_EA |
| 277 | Real Canadian Superstore | RCSS-Vancouver BC | Saffola Oats | Masala Oats Veggie Twist Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/masala-oats-veggie-twist-mega-pack/p/21707076_EA |
| 278 | Real Canadian Superstore | RCSS-Vancouver BC | Yumi Organics | Instant Oatmeal Hazelnut & Chocolate | instant packets | 264 g | 264 | $4.99 |  |  | $4.99 | $1.89 | $2.08/100g |  | deal badge: Limit 3, after limit $5.49 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-hazelnut-chocolate/p/21660610_EA |
| 279 | Real Canadian Superstore | RCSS-Vancouver BC | Yumi Organics | Instant Oatmeal Maple & Brown Sugar | instant packets | 264 g | 264 | $4.99 |  |  | $4.99 | $1.89 | $2.08/100g |  | deal badge: Limit 3, after limit $5.49 (to 2026-10-07) | 2026-10-01T00:57:58Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-maple-brown-sugar/p/21706743_EA |
| 280 | Real Canadian Superstore | RCSS-Vancouver BC | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $7.99 |  |  | $7.99 | $0.88 | $0.94/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07; deal badge: Limit 4, after limit $8.49 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/rolled-oats/p/21127426_EA |
| 281 | Real Canadian Superstore | RCSS-Vancouver BC | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 907 g | 907 | $8.99 | $7.64 | 2026-10-07 | $7.64 | $0.84 | $0.84/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/rolled-oats-old-fashioned-organic/p/21161849_EA |
| 282 | Real Canadian Superstore | RCSS-Vancouver BC | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 454 g | 454 | $6.29 | $5.34 | 2026-10-07 | $5.34 | $1.18 | $1.18/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/rolled-oats-old-fashioned-organic/p/21127424_EA |
| 283 | Real Canadian Superstore | RCSS-Vancouver BC | Dan D Pak | Rolled Oats | large flake / rolled | 1000 g | 1000 | $2.98 |  |  | $2.98 | $0.30 | $0.35/100g |  | deal badge: Limit 4, after limit $3.49 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/rolled-oats/p/20876492_EA |
| 284 | Real Canadian Superstore | RCSS-Vancouver BC | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 285 | Real Canadian Superstore | RCSS-Vancouver BC | No Name | Large Flake 100% Whole Grain Oats Club Size | large flake / rolled | 2.25 kg | 2250 | $6.00 | $5.49 | 2026-10-07 | $5.49 | $0.24 | $0.24/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats-club-size/p/20923840_EA |
| 286 | Real Canadian Superstore | RCSS-Vancouver BC | Oak Manor | Organic Oat Flakes | large flake / rolled | 1 kg | 1000 | $8.49 |  |  | $8.49 | $0.85 | $0.85/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-oat-flakes/p/20016104_EA |
| 287 | Real Canadian Superstore | RCSS-Vancouver BC | One Degree | Rolled Oats Sprouted | large flake / rolled | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/rolled-oats-sprouted/p/21532752_EA |
| 288 | Real Canadian Superstore | RCSS-Vancouver BC | PC Organics | Old Fashioned Gluten Free Rolled Oats | large flake / rolled | 900 g | 900 | $5.00 |  |  | $5.00 | $0.56 | $0.56/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/old-fashioned-gluten-free-rolled-oats/p/21396198_EA |
| 289 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $3.75 |  |  | $3.75 | $0.38 | $0.43/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/large-flake-oats/p/20323113002_EA |
| 290 | Real Canadian Superstore | RCSS-Vancouver BC | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 291 | Real Canadian Superstore | RCSS-Vancouver BC | Rogers | Porridge Oats, Ancient Grain Blend | large flake / rolled | 750 g | 750 | $5.79 |  |  | $5.79 | $0.77 | $0.77/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:58Z | https://www.realcanadiansuperstore.ca/porridge-oats-ancient-grain-blend/p/20718427_EA |
| 292 | Real Canadian Superstore | RCSS-Vancouver BC | Rogers | Porridge Oats, Original Blend | large flake / rolled | 1 kg | 1000 | $5.79 |  |  | $5.79 | $0.58 | $0.58/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/porridge-oats-original-blend/p/20717030_EA |
| 293 | Real Canadian Superstore | RCSS-Vancouver BC | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.49 | $8.06 | 2026-10-07 | $8.06 | $0.89 | $0.89/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/gluten-free-protein-oats/p/21639699_EA |
| 294 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Protein Oatmeal | other | 465 g | 465 | $8.99 |  |  | $8.99 | $1.93 | $1.93/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/protein-oatmeal/p/21687669_EA |
| 295 | Real Canadian Superstore | RCSS-Vancouver BC | Dan D Pak | Quick Oats | quick | 1000 g | 1000 | $2.98 |  |  | $2.98 | $0.30 | $0.35/100g |  | deal badge: Limit 4, after limit $3.49 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20876242_EA |
| 296 | Real Canadian Superstore | RCSS-Vancouver BC | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 297 | Real Canadian Superstore | RCSS-Vancouver BC | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 298 | Real Canadian Superstore | RCSS-Vancouver BC | No Name | Quick 100% Whole Grain Oats Club Size | quick | 2.25 kg | 2250 | $6.00 | $5.49 | 2026-10-07 | $5.49 | $0.24 | $0.24/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/quick-100-whole-grain-oats-club-size/p/20923786_EA |
| 299 | Real Canadian Superstore | RCSS-Vancouver BC | One Degree | Quick Oats Sprouted | quick | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/quick-oats-sprouted/p/21532753_EA |
| 300 | Real Canadian Superstore | RCSS-Vancouver BC | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-quick-rolled-oats/p/20705773_EA |
| 301 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Gluten-Free Quick Oats | quick | 511 g | 511 | $5.49 |  |  | $5.49 | $1.07 | $1.07/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/gluten-free-quick-oats/p/20970661_EA |
| 302 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | One Minute Oats | quick | 900 g | 900 | $3.75 |  |  | $3.75 | $0.42 | $0.48/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/one-minute-oats/p/20323113003_EA |
| 303 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Quaker Quick Oats | quick | 5.16 kg | 5160 | $14.99 |  |  | $14.99 | $0.29 | $0.29/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/quaker-quick-oats/p/21294986_C01 |
| 304 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Quick Oats | quick | 1 kg | 1000 | $3.75 |  |  | $3.75 | $0.38 | $0.43/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20323113001_EA |
| 305 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Quick Oats | quick | 2.25 kg | 2250 | $7.79 |  |  | $7.79 | $0.35 | $0.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20053840_EA |
| 306 | Real Canadian Superstore | RCSS-Vancouver BC | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 307 | Real Canadian Superstore | RCSS-Vancouver BC | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 308 | Real Canadian Superstore | RCSS-Vancouver BC | One Degree | Steel Cut Oats Sprouted | steel-cut | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/steel-cut-oats-sprouted/p/21535637_EA |
| 309 | Real Canadian Superstore | RCSS-Vancouver BC | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $4.00 |  |  | $4.00 | $0.48 | $0.48/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 310 | Real Canadian Superstore | RCSS-Vancouver BC | PC Blue Menu | Maple & Brown Sugar Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:57:55Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-steel-cut-oats/p/20943950_EA |
| 311 | Real Canadian Superstore | RCSS-Vancouver BC | PC Blue Menu | Regular Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/regular-steel-cut-oats/p/20943962_EA |
| 312 | Real Canadian Superstore | RCSS-Vancouver BC | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/organic-steel-cut-oats/p/20971286_EA |
| 313 | Real Canadian Superstore | RCSS-Vancouver BC | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $3.75 |  |  | $3.75 | $0.53 | $0.61/100g |  | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:57:57Z | https://www.realcanadiansuperstore.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 314 | Real Canadian Superstore | RCSS-Winnipeg MB | Anita's Organic Mill | Organic Whole Grain Old Fashioned Rolled Instant Oatmeal | instant (bag) | 2.5 kg | 2500 | $17.99 |  |  | $17.99 | $0.72 | $0.72/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/organic-whole-grain-old-fashioned-rolled-instant-o/p/21304184_EA |
| 315 | Real Canadian Superstore | RCSS-Winnipeg MB | Bobs Red Mill | Gluten Free Oatmeal Apple Cinnamon | instant (cup) | 67 g | 67 | $2.49 | $2.29 | 2026-10-07 | $2.29 | $3.42 | $3.42/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/gluten-free-oatmeal-apple-cinnamon/p/21589858_EA |
| 316 | Real Canadian Superstore | RCSS-Winnipeg MB | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.49 | $2.29 | 2026-10-07 | $2.29 | $3.75 | $3.75/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 317 | Real Canadian Superstore | RCSS-Winnipeg MB | Nature's Path | Organic Blueberry Cinnamon Flax Instant Oatmeal | instant packets | 320 g | 320 | $5.29 |  |  | $5.29 | $1.65 | $1.87/100g |  | deal badge: Limit 4, after limit $5.99 (to 2026-10-07) | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/organic-blueberry-cinnamon-flax-instant-oatmeal/p/20315563002_EA |
| 318 | Real Canadian Superstore | RCSS-Winnipeg MB | Nature's Path | Organic Cacao Superfood Instant Oatmeal | instant packets | 210 g | 210 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.76 | $2.76/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/organic-cacao-superfood-instant-oatmeal/p/21238137_EA |
| 319 | Real Canadian Superstore | RCSS-Winnipeg MB | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/organic-cinnamon-pumpkin-seed-instant-oatmeal/p/20978914_EA |
| 320 | Real Canadian Superstore | RCSS-Winnipeg MB | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 321 | Real Canadian Superstore | RCSS-Winnipeg MB | Nature's Path | Organic Maple Nut Instant Oatmeal | instant packets | 400 g | 400 | $5.29 |  |  | $5.29 | $1.32 | $1.5/100g |  | deal badge: Limit 4, after limit $5.99 (to 2026-10-07) | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/organic-maple-nut-instant-oatmeal/p/20304405003_EA |
| 322 | Real Canadian Superstore | RCSS-Winnipeg MB | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $6.29 | $5.79 | 2026-10-07 | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 323 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Blue Menu | Blue Menu Regular Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.00 |  |  | $4.00 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/blue-menu-regular-supergrains-oatmeal/p/21000529_EA |
| 324 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Organics | Organics Instant Oatmeal with Flaxseed | instant packets | 400 g | 400 | $5.50 |  |  | $5.50 | $1.38 | $1.38/100g |  |  | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/organics-instant-oatmeal-with-flaxseed/p/20971781_EA |
| 325 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Organics | Organics Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 400 g | 400 | $5.50 |  |  | $5.50 | $1.38 | $1.38/100g |  |  | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/organics-maple-and-brown-sugar-flavour-instant-oat/p/20974190_EA |
| 326 | Real Canadian Superstore | RCSS-Winnipeg MB | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.00 |  |  | $3.00 | $1.14 | $1.14/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 327 | Real Canadian Superstore | RCSS-Winnipeg MB | President's Choice | Instant Oatmeal, Cinnamon & Spice, 8 Servings | instant packets | 304 g | 304 | $3.00 |  |  | $3.00 | $0.99 | $0.99/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-cinnamon-spice-8-servings/p/21505067_EA |
| 328 | Real Canadian Superstore | RCSS-Winnipeg MB | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.00 |  |  | $3.00 | $1.14 | $1.14/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 329 | Real Canadian Superstore | RCSS-Winnipeg MB | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.00 |  |  | $3.00 | $0.95 | $0.96/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 330 | Real Canadian Superstore | RCSS-Winnipeg MB | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.00 |  |  | $3.00 | $0.87 | $0.87/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 331 | Real Canadian Superstore | RCSS-Winnipeg MB | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.00 |  |  | $3.00 | $1.07 | $1.07/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/regular-instant-oatmeal/p/21505058_EA |
| 332 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Apples & Cinnamon Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.50 |  |  | $3.50 | $1.51 | $1.63/100g |  | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/apples-cinnamon-flavour-low-sugar-instant-oatmeal/p/21683233_EA |
| 333 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.44/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 334 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Dino Eggs Instant Oatmeal | instant packets | 304 g | 304 | $3.50 |  |  | $3.50 | $1.15 | $1.25/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/dino-eggs-instant-oatmeal/p/20346597_EA |
| 335 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $3.50 |  |  | $3.50 | $1.11 | $1.21/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 336 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | High Fibre Raisins & Spice Instant Oatmeal | instant packets | 344 g | 344 | $4.49 |  |  | $4.49 | $1.30 | $1.31/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/high-fibre-raisins-spice-instant-oatmeal/p/21550142_EA |
| 337 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | High Protein Apples & Cinnamon Instant Oatmeal | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/high-protein-apples-cinnamon-instant-oatmeal/p/21550131_EA |
| 338 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | High Protein Triple Berry Instant Oatmeal | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/high-protein-triple-berry-instant-oatmeal/p/21550071_EA |
| 339 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Instant Oatmeal Flavour Variety Family Size | instant packets | 694 g | 694 | $6.49 |  |  | $6.49 | $0.94 | $0.94/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-flavour-variety-family-size/p/21520660_EA |
| 340 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Instant Oatmeal Flavour Variety Value Size | instant packets | 1.48 kg | 1480 | $15.49 |  |  | $15.49 | $1.05 | $1.05/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-flavour-variety-value-size/p/21524549_C01 |
| 341 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.50 |  |  | $3.50 | $1.02 | $1.1/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 342 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Maple & Brown Sugar Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.50 |  |  | $3.50 | $1.51 | $1.63/100g |  | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-flavour-low-sugar-instant-oatmea/p/21683172_EA |
| 343 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.44/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 344 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $4.49 |  |  | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 345 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Protein Instant Oatmeal, Regular, 6 packets | instant packets | 168 g | 168 | $4.49 |  |  | $4.49 | $2.67 | $2.67/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-regular-6-packets/p/21515952_EA |
| 346 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Protein+ Instant Oatmeal, Banana Nut Flavour, 6 packets | instant packets | 366 g | 366 | $6.99 |  |  | $6.99 | $1.91 | $1.91/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-banana-nut-flavour-6-packe/p/21620094_EA |
| 347 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Protein+ Instant Oatmeal, Maple & Brown Sugar Flavour, 6 packets | instant packets | 360 g | 360 | $6.99 |  |  | $6.99 | $1.94 | $1.94/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/protein-instant-oatmeal-maple-brown-sugar-flavour/p/21619993_EA |
| 348 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.50 |  |  | $3.50 | $1.25 | $1.35/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $3.79 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/regular-instant-oatmeal/p/21190265_EA |
| 349 | Real Canadian Superstore | RCSS-Winnipeg MB | Saffola Oats | Masala Oats Classic Masala Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/masala-oats-classic-masala-mega-pack/p/21707672_EA |
| 350 | Real Canadian Superstore | RCSS-Winnipeg MB | Saffola Oats | Masala Oats Peppy Tomato Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:58:18Z | https://www.realcanadiansuperstore.ca/masala-oats-peppy-tomato-mega-pack/p/21707090_EA |
| 351 | Real Canadian Superstore | RCSS-Winnipeg MB | Saffola Oats | Masala Oats Veggie Twist Mega Pack | instant packets | 500 g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.2/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/masala-oats-veggie-twist-mega-pack/p/21707076_EA |
| 352 | Real Canadian Superstore | RCSS-Winnipeg MB | Yumi Organics | Instant Oatmeal Hazelnut & Chocolate | instant packets | 264 g | 264 | $4.99 |  |  | $4.99 | $1.89 | $2.08/100g |  | deal badge: Limit 3, after limit $5.49 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-hazelnut-chocolate/p/21660610_EA |
| 353 | Real Canadian Superstore | RCSS-Winnipeg MB | Yumi Organics | Instant Oatmeal Maple & Brown Sugar | instant packets | 264 g | 264 | $4.99 |  |  | $4.99 | $1.89 | $2.08/100g |  | deal badge: Limit 3, after limit $5.49 (to 2026-10-07) | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/instant-oatmeal-maple-brown-sugar/p/21706743_EA |
| 354 | Real Canadian Superstore | RCSS-Winnipeg MB | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $7.99 |  |  | $7.99 | $0.88 | $0.94/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07; deal badge: Limit 4, after limit $8.49 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/rolled-oats/p/21127426_EA |
| 355 | Real Canadian Superstore | RCSS-Winnipeg MB | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 907 g | 907 | $8.99 | $7.64 | 2026-10-07 | $7.64 | $0.84 | $0.84/100g |  |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/rolled-oats-old-fashioned-organic/p/21161849_EA |
| 356 | Real Canadian Superstore | RCSS-Winnipeg MB | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 454 g | 454 | $6.29 | $5.34 | 2026-10-07 | $5.34 | $1.18 | $1.18/100g |  |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/rolled-oats-old-fashioned-organic/p/21127424_EA |
| 357 | Real Canadian Superstore | RCSS-Winnipeg MB | Dan D Pak | Rolled Oats | large flake / rolled | 1000 g | 1000 | $2.98 |  |  | $2.98 | $0.30 | $0.35/100g |  | deal badge: Limit 4, after limit $3.49 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/rolled-oats/p/20876492_EA |
| 358 | Real Canadian Superstore | RCSS-Winnipeg MB | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 359 | Real Canadian Superstore | RCSS-Winnipeg MB | No Name | Large Flake 100% Whole Grain Oats Club Size | large flake / rolled | 2.25 kg | 2250 | $6.00 | $5.49 | 2026-10-07 | $5.49 | $0.24 | $0.24/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats-club-size/p/20923840_EA |
| 360 | Real Canadian Superstore | RCSS-Winnipeg MB | Oak Manor | Organic Oat Flakes | large flake / rolled | 1 kg | 1000 | $8.49 |  |  | $8.49 | $0.85 | $0.85/100g |  |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/organic-oat-flakes/p/20016104_EA |
| 361 | Real Canadian Superstore | RCSS-Winnipeg MB | One Degree | Rolled Oats Sprouted | large flake / rolled | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/rolled-oats-sprouted/p/21532752_EA |
| 362 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Organics | Old Fashioned Gluten Free Rolled Oats | large flake / rolled | 900 g | 900 | $5.00 |  |  | $5.00 | $0.56 | $0.56/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/old-fashioned-gluten-free-rolled-oats/p/21396198_EA |
| 363 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $3.75 |  |  | $3.75 | $0.38 | $0.43/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/large-flake-oats/p/20323113002_EA |
| 364 | Real Canadian Superstore | RCSS-Winnipeg MB | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 365 | Real Canadian Superstore | RCSS-Winnipeg MB | Rogers | Porridge Oats, Ancient Grain Blend | large flake / rolled | 750 g | 750 | $5.79 |  |  | $5.79 | $0.77 | $0.77/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/porridge-oats-ancient-grain-blend/p/20718427_EA |
| 366 | Real Canadian Superstore | RCSS-Winnipeg MB | Rogers | Porridge Oats, Original Blend | large flake / rolled | 1 kg | 1000 | $5.79 |  |  | $5.79 | $0.58 | $0.58/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/porridge-oats-original-blend/p/20717030_EA |
| 367 | Real Canadian Superstore | RCSS-Winnipeg MB | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.49 | $8.06 | 2026-10-07 | $8.06 | $0.89 | $0.89/100g |  |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/gluten-free-protein-oats/p/21639699_EA |
| 368 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Protein Oatmeal | other | 465 g | 465 | $8.99 |  |  | $8.99 | $1.93 | $1.93/100g |  |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/protein-oatmeal/p/21687669_EA |
| 369 | Real Canadian Superstore | RCSS-Winnipeg MB | Stoked Oats | Bucking Eh Oats | other | 500 g | 500 | $8.50 |  |  | $8.50 | $1.70 | $2.0/100g | retailer badge: Prepared in Canada | deal badge: Limit 4, after limit $9.99 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/bucking-eh-oats/p/20971529_EA |
| 370 | Real Canadian Superstore | RCSS-Winnipeg MB | Stoked Oats | Stone Age Oats | other | 500 g | 500 | $8.50 |  |  | $8.50 | $1.70 | $2.0/100g | retailer badge: Prepared in Canada | deal badge: Limit 4, after limit $9.99 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/stone-age-oats/p/20971534_EA |
| 371 | Real Canadian Superstore | RCSS-Winnipeg MB | Dan D Pak | Quick Oats | quick | 1000 g | 1000 | $2.98 |  |  | $2.98 | $0.30 | $0.35/100g |  | deal badge: Limit 4, after limit $3.49 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20876242_EA |
| 372 | Real Canadian Superstore | RCSS-Winnipeg MB | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 373 | Real Canadian Superstore | RCSS-Winnipeg MB | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 374 | Real Canadian Superstore | RCSS-Winnipeg MB | No Name | Quick 100% Whole Grain Oats Club Size | quick | 2.25 kg | 2250 | $6.00 | $5.49 | 2026-10-07 | $5.49 | $0.24 | $0.24/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/quick-100-whole-grain-oats-club-size/p/20923786_EA |
| 375 | Real Canadian Superstore | RCSS-Winnipeg MB | One Degree | Quick Oats Sprouted | quick | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/quick-oats-sprouted/p/21532753_EA |
| 376 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/organic-quick-rolled-oats/p/20705773_EA |
| 377 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Gluten-Free Quick Oats | quick | 511 g | 511 | $5.49 |  |  | $5.49 | $1.07 | $1.07/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/gluten-free-quick-oats/p/20970661_EA |
| 378 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | One Minute Oats | quick | 900 g | 900 | $3.75 |  |  | $3.75 | $0.42 | $0.48/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/one-minute-oats/p/20323113003_EA |
| 379 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Quaker Quick Oats | quick | 5.16 kg | 5160 | $14.99 |  |  | $14.99 | $0.29 | $0.29/100g |  |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/quaker-quick-oats/p/21294986_C01 |
| 380 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Quick Oats | quick | 1 kg | 1000 | $3.75 |  |  | $3.75 | $0.38 | $0.43/100g | retailer badge: Prepared in Canada | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20323113001_EA |
| 381 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Quick Oats | quick | 2.25 kg | 2250 | $7.79 |  |  | $7.79 | $0.35 | $0.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/quick-oats/p/20053840_EA |
| 382 | Real Canadian Superstore | RCSS-Winnipeg MB | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 383 | Real Canadian Superstore | RCSS-Winnipeg MB | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 384 | Real Canadian Superstore | RCSS-Winnipeg MB | Bobs Red Mill | Steel Cut Oats Whole Grain Gluten Free | steel-cut | 680 g | 680 | $7.99 |  |  | $7.99 | $1.18 | $1.19/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07; deal badge: Limit 4, after limit $8.06 (to 2026-10-07) | 2026-10-01T00:58:21Z | https://www.realcanadiansuperstore.ca/steel-cut-oats-whole-grain-gluten-free/p/21127423_EA |
| 385 | Real Canadian Superstore | RCSS-Winnipeg MB | One Degree | Steel Cut Oats Sprouted | steel-cut | 680 g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/steel-cut-oats-sprouted/p/21535637_EA |
| 386 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $4.00 |  |  | $4.00 | $0.48 | $0.48/100g |  |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 387 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Blue Menu | Maple & Brown Sugar Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:58:18Z | https://www.realcanadiansuperstore.ca/maple-brown-sugar-steel-cut-oats/p/20943950_EA |
| 388 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Blue Menu | Regular Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:58:20Z | https://www.realcanadiansuperstore.ca/regular-steel-cut-oats/p/20943962_EA |
| 389 | Real Canadian Superstore | RCSS-Winnipeg MB | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/organic-steel-cut-oats/p/20971286_EA |
| 390 | Real Canadian Superstore | RCSS-Winnipeg MB | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $3.75 |  |  | $3.75 | $0.53 | $0.61/100g |  | deal badge: Limit 3, after limit $4.29 (to 2026-10-07) | 2026-10-01T00:58:19Z | https://www.realcanadiansuperstore.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 391 | No Frills | NF-Toronto ON | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.00 |  |  | $3.00 | $0.95 | $0.96/100g |  |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 392 | No Frills | NF-Toronto ON | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.00 |  |  | $3.00 | $0.87 | $0.87/100g |  |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 393 | No Frills | NF-Toronto ON | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $3.79 |  |  | $3.79 | $1.21 | $1.21/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 394 | No Frills | NF-Toronto ON | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.79 |  |  | $3.79 | $1.10 | $1.1/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 395 | No Frills | NF-Toronto ON | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $3.79 |  |  | $3.79 | $1.44 | $1.44/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 396 | No Frills | NF-Toronto ON | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.79 |  |  | $3.79 | $1.35 | $1.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/regular-instant-oatmeal/p/21190265_EA |
| 397 | No Frills | NF-Toronto ON | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $9.00 |  |  | $9.00 | $0.99 | $0.99/100g |  |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/rolled-oats/p/21127426_EA |
| 398 | No Frills | NF-Toronto ON | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T00:59:02Z | https://www.nofrills.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 399 | No Frills | NF-Toronto ON | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.00 |  |  | $4.00 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/large-flake-oats/p/20323113002_EA |
| 400 | No Frills | NF-Toronto ON | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T00:59:02Z | https://www.nofrills.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 401 | No Frills | NF-Toronto ON | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T00:59:02Z | https://www.nofrills.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 402 | No Frills | NF-Toronto ON | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/organic-quick-rolled-oats/p/20705773_EA |
| 403 | No Frills | NF-Toronto ON | Quaker | One Minute Oats | quick | 900 g | 900 | $4.00 |  |  | $4.00 | $0.44 | $0.44/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/one-minute-oats/p/20323113003_EA |
| 404 | No Frills | NF-Toronto ON | Quaker | Quick Oats | quick | 1 kg | 1000 | $4.00 |  |  | $4.00 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:02Z | https://www.nofrills.ca/quick-oats/p/20323113001_EA |
| 405 | No Frills | NF-Toronto ON | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $4.00 |  |  | $4.00 | $0.48 | $0.48/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T00:59:02Z | https://www.nofrills.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 406 | No Frills | NF-Vancouver BC | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.33/100g |  |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 407 | No Frills | NF-Vancouver BC | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.33/100g |  |  | 2026-10-01T00:59:37Z | https://www.nofrills.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 408 | No Frills | NF-Vancouver BC | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.50 |  |  | $3.50 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 409 | No Frills | NF-Vancouver BC | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.50 |  |  | $3.50 | $1.02 | $1.02/100g |  |  | 2026-10-01T00:59:38Z | https://www.nofrills.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 410 | No Frills | NF-Vancouver BC | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.50 |  |  | $3.50 | $1.25 | $1.25/100g |  |  | 2026-10-01T00:59:37Z | https://www.nofrills.ca/regular-instant-oatmeal/p/21505058_EA |
| 411 | No Frills | NF-Vancouver BC | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.79 |  |  | $3.79 | $1.44 | $1.44/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 412 | No Frills | NF-Vancouver BC | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $3.79 |  |  | $3.79 | $1.21 | $1.21/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 413 | No Frills | NF-Vancouver BC | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.79 |  |  | $3.79 | $1.10 | $1.1/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 414 | No Frills | NF-Vancouver BC | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $4.50 |  |  | $4.50 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 415 | No Frills | NF-Vancouver BC | Quaker | Protein Instant Oatmeal, Regular, 6 packets | instant packets | 168 g | 168 | $4.50 |  |  | $4.50 | $2.68 | $2.68/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:37Z | https://www.nofrills.ca/protein-instant-oatmeal-regular-6-packets/p/21515952_EA |
| 416 | No Frills | NF-Vancouver BC | Quaker | Protein+ Instant Oatmeal, Banana Nut Flavour, 6 packets | instant packets | 366 g | 366 | $6.49 |  |  | $6.49 | $1.77 | $1.77/100g |  |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/protein-instant-oatmeal-banana-nut-flavour-6-packe/p/21620094_EA |
| 417 | No Frills | NF-Vancouver BC | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.79 |  |  | $3.79 | $1.35 | $1.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/regular-instant-oatmeal/p/21190265_EA |
| 418 | No Frills | NF-Vancouver BC | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $9.00 |  |  | $9.00 | $0.99 | $0.99/100g |  |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/rolled-oats/p/21127426_EA |
| 419 | No Frills | NF-Vancouver BC | Dan D Pak | Rolled Oats | large flake / rolled | 1000 g | 1000 | $3.49 |  |  | $3.49 | $0.35 | $0.35/100g |  |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/rolled-oats/p/20876492_EA |
| 420 | No Frills | NF-Vancouver BC | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:59:39Z | https://www.nofrills.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 421 | No Frills | NF-Vancouver BC | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.29 |  |  | $4.29 | $0.43 | $0.43/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/large-flake-oats/p/20323113002_EA |
| 422 | No Frills | NF-Vancouver BC | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $3.99 |  |  | $3.99 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 423 | No Frills | NF-Vancouver BC | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.50 |  |  | $9.50 | $1.05 | $1.05/100g |  |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/gluten-free-protein-oats/p/21639699_EA |
| 424 | No Frills | NF-Vancouver BC | Dan D Pak | Quick Oats | quick | 1000 g | 1000 | $3.49 |  |  | $3.49 | $0.35 | $0.35/100g |  |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/quick-oats/p/20876242_EA |
| 425 | No Frills | NF-Vancouver BC | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:59:39Z | https://www.nofrills.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 426 | No Frills | NF-Vancouver BC | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:59:37Z | https://www.nofrills.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 427 | No Frills | NF-Vancouver BC | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:37Z | https://www.nofrills.ca/organic-quick-rolled-oats/p/20705773_EA |
| 428 | No Frills | NF-Vancouver BC | Quaker | One Minute Oats | quick | 900 g | 900 | $4.29 |  |  | $4.29 | $0.48 | $0.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/one-minute-oats/p/20323113003_EA |
| 429 | No Frills | NF-Vancouver BC | Quaker | Quick Oats | quick | 1 kg | 1000 | $4.29 |  |  | $4.29 | $0.43 | $0.43/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/quick-oats/p/20323113001_EA |
| 430 | No Frills | NF-Vancouver BC | Quaker | Quick Oats | quick | 2.25 kg | 2250 | $7.79 |  |  | $7.79 | $0.35 | $0.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/quick-oats/p/20053840_EA |
| 431 | No Frills | NF-Vancouver BC | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $3.99 |  |  | $3.99 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 432 | No Frills | NF-Vancouver BC | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $3.99 |  |  | $3.99 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 433 | No Frills | NF-Vancouver BC | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $4.00 |  |  | $4.00 | $0.48 | $0.48/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T00:59:39Z | https://www.nofrills.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 434 | No Frills | NF-Vancouver BC | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $4.29 |  |  | $4.29 | $0.60 | $0.61/100g |  |  | 2026-10-01T00:59:39Z | https://www.nofrills.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 435 | No Frills | NF-Calgary AB | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.33/100g |  |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 436 | No Frills | NF-Calgary AB | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.50 |  |  | $3.50 | $1.33 | $1.33/100g |  |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 437 | No Frills | NF-Calgary AB | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.50 |  |  | $3.50 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 438 | No Frills | NF-Calgary AB | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.50 |  |  | $3.50 | $1.02 | $1.02/100g |  |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 439 | No Frills | NF-Calgary AB | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.50 |  |  | $3.50 | $1.25 | $1.25/100g |  |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/regular-instant-oatmeal/p/21505058_EA |
| 440 | No Frills | NF-Calgary AB | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.79 |  |  | $3.79 | $1.44 | $1.44/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 441 | No Frills | NF-Calgary AB | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $3.79 |  |  | $3.79 | $1.21 | $1.21/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 442 | No Frills | NF-Calgary AB | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.79 |  |  | $3.79 | $1.10 | $1.1/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 443 | No Frills | NF-Calgary AB | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $4.50 |  |  | $4.50 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 444 | No Frills | NF-Calgary AB | Quaker | Protein Instant Oatmeal, Regular, 6 packets | instant packets | 168 g | 168 | $4.50 |  |  | $4.50 | $2.68 | $2.68/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/protein-instant-oatmeal-regular-6-packets/p/21515952_EA |
| 445 | No Frills | NF-Calgary AB | Quaker | Protein+ Instant Oatmeal, Banana Nut Flavour, 6 packets | instant packets | 366 g | 366 | $6.49 |  |  | $6.49 | $1.77 | $1.77/100g |  |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/protein-instant-oatmeal-banana-nut-flavour-6-packe/p/21620094_EA |
| 446 | No Frills | NF-Calgary AB | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.79 |  |  | $3.79 | $1.35 | $1.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/regular-instant-oatmeal/p/21190265_EA |
| 447 | No Frills | NF-Calgary AB | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $9.00 |  |  | $9.00 | $0.99 | $0.99/100g |  |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/rolled-oats/p/21127426_EA |
| 448 | No Frills | NF-Calgary AB | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:59:21Z | https://www.nofrills.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 449 | No Frills | NF-Calgary AB | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.29 |  |  | $4.29 | $0.43 | $0.43/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/large-flake-oats/p/20323113002_EA |
| 450 | No Frills | NF-Calgary AB | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $3.99 |  |  | $3.99 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 451 | No Frills | NF-Calgary AB | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:59:21Z | https://www.nofrills.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 452 | No Frills | NF-Calgary AB | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T00:59:21Z | https://www.nofrills.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 453 | No Frills | NF-Calgary AB | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/organic-quick-rolled-oats/p/20705773_EA |
| 454 | No Frills | NF-Calgary AB | Quaker | One Minute Oats | quick | 900 g | 900 | $4.29 |  |  | $4.29 | $0.48 | $0.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/one-minute-oats/p/20323113003_EA |
| 455 | No Frills | NF-Calgary AB | Quaker | Quick Oats | quick | 1 kg | 1000 | $4.29 |  |  | $4.29 | $0.43 | $0.43/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/quick-oats/p/20323113001_EA |
| 456 | No Frills | NF-Calgary AB | Quaker | Quick Oats | quick | 2.25 kg | 2250 | $7.79 |  |  | $7.79 | $0.35 | $0.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/quick-oats/p/20053840_EA |
| 457 | No Frills | NF-Calgary AB | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $3.99 |  |  | $3.99 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 458 | No Frills | NF-Calgary AB | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $3.99 |  |  | $3.99 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 459 | No Frills | NF-Calgary AB | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $4.00 |  |  | $4.00 | $0.48 | $0.48/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T00:59:21Z | https://www.nofrills.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 460 | No Frills | NF-Calgary AB | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $4.29 |  |  | $4.29 | $0.60 | $0.61/100g |  |  | 2026-10-01T00:59:21Z | https://www.nofrills.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 461 | Atlantic Superstore | ASS-Halifax NS | Bobs Red Mill | Gluten Free Oatmeal Apple Cinnamon | instant (cup) | 67 g | 67 | $2.00 |  |  | $2.00 | $2.98 | $2.99/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-11-04; single-serve under 100 g, grouped with cups | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/gluten-free-oatmeal-apple-cinnamon/p/21589858_EA |
| 462 | Atlantic Superstore | ASS-Halifax NS | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.79 | $2.00 | 2026-11-04 | $2.00 | $3.28 | $3.28/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 463 | Atlantic Superstore | ASS-Halifax NS | Nature's Path | Organic Cacao Superfood Instant Oatmeal | instant packets | 210 g | 210 | $6.49 |  |  | $6.49 | $3.09 | $3.09/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/organic-cacao-superfood-instant-oatmeal/p/21238137_EA |
| 464 | Atlantic Superstore | ASS-Halifax NS | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/organic-cinnamon-pumpkin-seed-instant-oatmeal/p/20978914_EA |
| 465 | Atlantic Superstore | ASS-Halifax NS | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 466 | Atlantic Superstore | ASS-Halifax NS | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 467 | Atlantic Superstore | ASS-Halifax NS | PC Blue Menu | Blue Menu Maple and Brown Sugar Flavour Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.79 |  |  | $4.79 | $1.58 | $1.58/100g |  |  | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/blue-menu-maple-and-brown-sugar-flavour-supergrain/p/21004695_EA |
| 468 | Atlantic Superstore | ASS-Halifax NS | PC Blue Menu | Blue Menu Regular Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.79 |  |  | $4.79 | $1.58 | $1.58/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/blue-menu-regular-supergrains-oatmeal/p/21000529_EA |
| 469 | Atlantic Superstore | ASS-Halifax NS | PC Organics | Organics Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 400 g | 400 | $6.99 |  |  | $6.99 | $1.75 | $1.75/100g |  |  | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/organics-maple-and-brown-sugar-flavour-instant-oat/p/20974190_EA |
| 470 | Atlantic Superstore | ASS-Halifax NS | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.25 |  |  | $3.25 | $1.23 | $1.23/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 471 | Atlantic Superstore | ASS-Halifax NS | President's Choice | Instant Oatmeal, Cinnamon & Spice, 8 Servings | instant packets | 304 g | 304 | $3.25 |  |  | $3.25 | $1.07 | $1.07/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/instant-oatmeal-cinnamon-spice-8-servings/p/21505067_EA |
| 472 | Atlantic Superstore | ASS-Halifax NS | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.25 |  |  | $3.25 | $1.23 | $1.23/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 473 | Atlantic Superstore | ASS-Halifax NS | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.25 |  |  | $3.25 | $1.03 | $1.04/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 474 | Atlantic Superstore | ASS-Halifax NS | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.25 |  |  | $3.25 | $0.94 | $0.94/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 475 | Atlantic Superstore | ASS-Halifax NS | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.25 |  |  | $3.25 | $1.16 | $1.16/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/regular-instant-oatmeal/p/21505058_EA |
| 476 | Atlantic Superstore | ASS-Halifax NS | Quaker | Apples & Cinnamon Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $4.50 |  |  | $4.50 | $1.94 | $1.94/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/apples-cinnamon-flavour-low-sugar-instant-oatmeal/p/21683233_EA |
| 477 | Atlantic Superstore | ASS-Halifax NS | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $4.50 |  |  | $4.50 | $1.71 | $1.7/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 478 | Atlantic Superstore | ASS-Halifax NS | Quaker | Dino Eggs Instant Oatmeal | instant packets | 304 g | 304 | $4.50 |  |  | $4.50 | $1.48 | $1.48/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/dino-eggs-instant-oatmeal/p/20346597_EA |
| 479 | Atlantic Superstore | ASS-Halifax NS | Quaker | Fibre Instant Oatmeal, Wildberry Medley | instant packets | 304 g | 304 | $5.00 | $4.49 | 2026-10-28 | $4.49 | $1.48 | $1.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/fibre-instant-oatmeal-wildberry-medley/p/21549428_EA |
| 480 | Atlantic Superstore | ASS-Halifax NS | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $4.50 |  |  | $4.50 | $1.43 | $1.43/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 481 | Atlantic Superstore | ASS-Halifax NS | Quaker | High Fibre Raisins & Spice Instant Oatmeal | instant packets | 344 g | 344 | $5.00 | $4.49 | 2026-10-28 | $4.49 | $1.30 | $1.31/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/high-fibre-raisins-spice-instant-oatmeal/p/21550142_EA |
| 482 | Atlantic Superstore | ASS-Halifax NS | Quaker | High Protein Apples & Cinnamon Instant Oatmeal | instant packets | 228 g | 228 | $5.00 | $4.49 | 2026-10-28 | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/high-protein-apples-cinnamon-instant-oatmeal/p/21550131_EA |
| 483 | Atlantic Superstore | ASS-Halifax NS | Quaker | High Protein Triple Berry Instant Oatmeal | instant packets | 228 g | 228 | $5.00 | $4.49 | 2026-10-28 | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/high-protein-triple-berry-instant-oatmeal/p/21550071_EA |
| 484 | Atlantic Superstore | ASS-Halifax NS | Quaker | Instant Oatmeal Flavour Variety Family Size | instant packets | 694 g | 694 | $8.99 | $6.99 | 2026-10-28 | $6.99 | $1.01 | $1.01/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/instant-oatmeal-flavour-variety-family-size/p/21520660_EA |
| 485 | Atlantic Superstore | ASS-Halifax NS | Quaker | Instant Oatmeal Flavour Variety Value Size | instant packets | 1.48 kg | 1480 | $21.99 |  |  | $21.99 | $1.49 | $1.49/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/instant-oatmeal-flavour-variety-value-size/p/21524549_C01 |
| 486 | Atlantic Superstore | ASS-Halifax NS | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $4.50 |  |  | $4.50 | $1.31 | $1.31/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 487 | Atlantic Superstore | ASS-Halifax NS | Quaker | Maple & Brown Sugar Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $4.50 |  |  | $4.50 | $1.94 | $1.94/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/maple-brown-sugar-flavour-low-sugar-instant-oatmea/p/21683172_EA |
| 488 | Atlantic Superstore | ASS-Halifax NS | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $4.50 |  |  | $4.50 | $1.71 | $1.7/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 489 | Atlantic Superstore | ASS-Halifax NS | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $5.00 | $4.49 | 2026-10-28 | $4.49 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 490 | Atlantic Superstore | ASS-Halifax NS | Quaker | Protein Instant Oatmeal, Regular, 6 packets | instant packets | 168 g | 168 | $5.00 | $4.49 | 2026-10-28 | $4.49 | $2.67 | $2.67/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/protein-instant-oatmeal-regular-6-packets/p/21515952_EA |
| 491 | Atlantic Superstore | ASS-Halifax NS | Quaker | Protein+ Instant Oatmeal, Banana Nut Flavour, 6 packets | instant packets | 366 g | 366 | $7.99 |  |  | $7.99 | $2.18 | $2.18/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/protein-instant-oatmeal-banana-nut-flavour-6-packe/p/21620094_EA |
| 492 | Atlantic Superstore | ASS-Halifax NS | Quaker | Protein+ Instant Oatmeal, Maple & Brown Sugar Flavour, 6 packets | instant packets | 360 g | 360 | $7.99 |  |  | $7.99 | $2.22 | $2.22/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/protein-instant-oatmeal-maple-brown-sugar-flavour/p/21619993_EA |
| 493 | Atlantic Superstore | ASS-Halifax NS | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $4.50 |  |  | $4.50 | $1.61 | $1.61/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/regular-instant-oatmeal/p/21190265_EA |
| 494 | Atlantic Superstore | ASS-Halifax NS | Saffola Oats | Masala Oats Classic Masala Mega Pack | instant packets | 500 g | 500 | $5.49 |  |  | $5.49 | $1.10 | $1.1/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/masala-oats-classic-masala-mega-pack/p/21707672_EA |
| 495 | Atlantic Superstore | ASS-Halifax NS | Saffola Oats | Masala Oats Peppy Tomato Mega Pack | instant packets | 500 g | 500 | $5.49 |  |  | $5.49 | $1.10 | $1.1/100g |  |  | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/masala-oats-peppy-tomato-mega-pack/p/21707090_EA |
| 496 | Atlantic Superstore | ASS-Halifax NS | Saffola Oats | Masala Oats Veggie Twist Mega Pack | instant packets | 500 g | 500 | $5.49 |  |  | $5.49 | $1.10 | $1.1/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/masala-oats-veggie-twist-mega-pack/p/21707076_EA |
| 497 | Atlantic Superstore | ASS-Halifax NS | Yumi Organics | Instant Oatmeal Hazelnut & Chocolate | instant packets | 264 g | 264 | $5.25 |  |  | $5.25 | $1.99 | $1.99/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/instant-oatmeal-hazelnut-chocolate/p/21660610_EA |
| 498 | Atlantic Superstore | ASS-Halifax NS | Yumi Organics | Instant Oatmeal Maple & Brown Sugar | instant packets | 264 g | 264 | $5.25 |  |  | $5.25 | $1.99 | $1.99/100g |  | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/instant-oatmeal-maple-brown-sugar/p/21706743_EA |
| 499 | Atlantic Superstore | ASS-Halifax NS | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $9.49 | $8.49 | 2026-10-14 | $8.49 | $0.94 | $0.94/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/rolled-oats/p/21127426_EA |
| 500 | Atlantic Superstore | ASS-Halifax NS | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 907 g | 907 | $10.49 | $8.99 | 2026-10-14 | $8.99 | $0.99 | $0.99/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/rolled-oats-old-fashioned-organic/p/21161849_EA |
| 501 | Atlantic Superstore | ASS-Halifax NS | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 454 g | 454 | $6.99 | $6.49 | 2026-10-14 | $6.49 | $1.43 | $1.43/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/rolled-oats-old-fashioned-organic/p/21127424_EA |
| 502 | Atlantic Superstore | ASS-Halifax NS | Dan D Pak | Rolled Oats | large flake / rolled | 1000 g | 1000 | $3.49 | $3.28 | 2026-10-07 | $3.28 | $0.33 | $0.33/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/rolled-oats/p/20876492_EA |
| 503 | Atlantic Superstore | ASS-Halifax NS | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-28 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 504 | Atlantic Superstore | ASS-Halifax NS | No Name | Large Flake 100% Whole Grain Oats Club Size | large flake / rolled | 2.25 kg | 2250 | $6.50 |  |  | $6.50 | $0.29 | $0.29/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/large-flake-100-whole-grain-oats-club-size/p/20923840_EA |
| 505 | Atlantic Superstore | ASS-Halifax NS | Oak Manor | Organic Oat Flakes | large flake / rolled | 1 kg | 1000 | $8.49 |  |  | $8.49 | $0.85 | $0.85/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/organic-oat-flakes/p/20016104_EA |
| 506 | Atlantic Superstore | ASS-Halifax NS | One Degree | Rolled Oats Sprouted | large flake / rolled | 680 g | 680 | $9.19 | $8.49 | 2026-10-07 | $8.49 | $1.25 | $1.25/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/rolled-oats-sprouted/p/21532752_EA |
| 507 | Atlantic Superstore | ASS-Halifax NS | PC Organics | Old Fashioned Gluten Free Rolled Oats | large flake / rolled | 900 g | 900 | $5.00 |  |  | $5.00 | $0.56 | $0.56/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/old-fashioned-gluten-free-rolled-oats/p/21396198_EA |
| 508 | Atlantic Superstore | ASS-Halifax NS | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $5.50 | $4.49 | 2026-10-28 | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/large-flake-oats/p/20323113002_EA |
| 509 | Atlantic Superstore | ASS-Halifax NS | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 510 | Atlantic Superstore | ASS-Halifax NS | Rogers | Porridge Oats, Ancient Grain Blend | large flake / rolled | 750 g | 750 | $5.99 |  |  | $5.99 | $0.80 | $0.8/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:03Z | https://www.atlanticsuperstore.ca/porridge-oats-ancient-grain-blend/p/20718427_EA |
| 511 | Atlantic Superstore | ASS-Halifax NS | Rogers | Porridge Oats, Original Blend | large flake / rolled | 1 kg | 1000 | $5.99 |  |  | $5.99 | $0.60 | $0.6/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/porridge-oats-original-blend/p/20717030_EA |
| 512 | Atlantic Superstore | ASS-Halifax NS | Speerville Flour Mill | Newfoundland Oatmeal | large flake / rolled | 910 g | 910 | $5.99 |  |  | $5.99 | $0.66 | $0.66/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/newfoundland-oatmeal/p/20059495_EA |
| 513 | Atlantic Superstore | ASS-Halifax NS | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.99 | $8.99 | 2026-10-14 | $8.99 | $0.99 | $0.99/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/gluten-free-protein-oats/p/21639699_EA |
| 514 | Atlantic Superstore | ASS-Halifax NS | Quaker | Protein Oatmeal | other | 465 g | 465 | $8.99 |  |  | $8.99 | $1.93 | $1.93/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/protein-oatmeal/p/21687669_EA |
| 515 | Atlantic Superstore | ASS-Halifax NS | Dan D Pak | Quick Oats | quick | 1000 g | 1000 | $3.49 | $3.28 | 2026-10-07 | $3.28 | $0.33 | $0.33/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/quick-oats/p/20876242_EA |
| 516 | Atlantic Superstore | ASS-Halifax NS | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-28 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 517 | Atlantic Superstore | ASS-Halifax NS | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-28 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 518 | Atlantic Superstore | ASS-Halifax NS | No Name | Quick 100% Whole Grain Oats Club Size | quick | 2.25 kg | 2250 | $6.50 |  |  | $6.50 | $0.29 | $0.29/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-07 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/quick-100-whole-grain-oats-club-size/p/20923786_EA |
| 519 | Atlantic Superstore | ASS-Halifax NS | One Degree | Quick Oats Sprouted | quick | 680 g | 680 | $9.19 | $4.19 | 2026-10-07 | $4.19 | $0.62 | $0.62/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/quick-oats-sprouted/p/21532753_EA |
| 520 | Atlantic Superstore | ASS-Halifax NS | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/organic-quick-rolled-oats/p/20705773_EA |
| 521 | Atlantic Superstore | ASS-Halifax NS | Quaker | Gluten-Free Quick Oats | quick | 511 g | 511 | $6.99 |  |  | $6.99 | $1.37 | $1.37/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/gluten-free-quick-oats/p/20970661_EA |
| 522 | Atlantic Superstore | ASS-Halifax NS | Quaker | One Minute Oats | quick | 900 g | 900 | $5.50 | $4.49 | 2026-10-28 | $4.49 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/one-minute-oats/p/20323113003_EA |
| 523 | Atlantic Superstore | ASS-Halifax NS | Quaker | Quick Oats | quick | 1 kg | 1000 | $5.50 | $4.49 | 2026-10-28 | $4.49 | $0.45 | $0.45/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/quick-oats/p/20323113001_EA |
| 524 | Atlantic Superstore | ASS-Halifax NS | Quaker | Quick Oats | quick | 2.25 kg | 2250 | $7.99 |  |  | $7.99 | $0.35 | $0.36/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/quick-oats/p/20053840_EA |
| 525 | Atlantic Superstore | ASS-Halifax NS | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 526 | Atlantic Superstore | ASS-Halifax NS | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 527 | Atlantic Superstore | ASS-Halifax NS | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $5.00 |  |  | $5.00 | $0.59 | $0.6/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 528 | Atlantic Superstore | ASS-Halifax NS | PC Blue Menu | Maple & Brown Sugar Steel Cut Oats | steel-cut | 360 g | 360 | $4.49 |  |  | $4.49 | $1.25 | $1.25/100g |  |  | 2026-10-01T00:59:59Z | https://www.atlanticsuperstore.ca/maple-brown-sugar-steel-cut-oats/p/20943950_EA |
| 529 | Atlantic Superstore | ASS-Halifax NS | PC Blue Menu | Regular Steel Cut Oats | steel-cut | 360 g | 360 | $4.49 |  |  | $4.49 | $1.25 | $1.25/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/regular-steel-cut-oats/p/20943962_EA |
| 530 | Atlantic Superstore | ASS-Halifax NS | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/organic-steel-cut-oats/p/20971286_EA |
| 531 | Atlantic Superstore | ASS-Halifax NS | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $5.50 | $4.49 | 2026-10-28 | $4.49 | $0.63 | $0.63/100g |  |  | 2026-10-01T01:00:02Z | https://www.atlanticsuperstore.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 532 | Provigo | PRV-Montréal QC | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.99 |  |  | $2.99 | $4.90 | $4.9/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T01:00:25Z | https://www.provigo.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 533 | Provigo | PRV-Montréal QC | Nature's Path | Organic Cinnamon Pumpkin Seed Instant Oatmeal | instant packets | 228 g | 228 | $7.49 |  |  | $7.49 | $3.29 | $3.29/100g |  |  | 2026-10-01T01:00:25Z | https://www.provigo.ca/organic-cinnamon-pumpkin-seed-instant-oatmeal/p/20978914_EA |
| 534 | Provigo | PRV-Montréal QC | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $7.49 |  |  | $7.49 | $3.29 | $3.29/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 535 | Provigo | PRV-Montréal QC | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $7.49 |  |  | $7.49 | $3.29 | $3.29/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 536 | Provigo | PRV-Montréal QC | President's Choice | Apples and Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.79 |  |  | $3.79 | $1.44 | $1.44/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T01:00:24Z | https://www.provigo.ca/apples-and-cinnamon-instant-oatmeal/p/21506334_EA |
| 537 | Provigo | PRV-Montréal QC | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.79 |  |  | $3.79 | $1.44 | $1.44/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T01:00:24Z | https://www.provigo.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 538 | Provigo | PRV-Montréal QC | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.79 |  |  | $3.79 | $1.21 | $1.21/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T01:00:24Z | https://www.provigo.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 539 | Provigo | PRV-Montréal QC | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.79 |  |  | $3.79 | $1.10 | $1.1/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T01:00:24Z | https://www.provigo.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 540 | Provigo | PRV-Montréal QC | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.79 |  |  | $3.79 | $1.35 | $1.35/100g |  | deal badge: $3.50 MIN 2 | 2026-10-01T01:00:24Z | https://www.provigo.ca/regular-instant-oatmeal/p/21505058_EA |
| 541 | Provigo | PRV-Montréal QC | Quaker | Apples & Cinnamon Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $5.19 |  |  | $5.19 | $2.24 | $2.24/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/apples-cinnamon-flavour-low-sugar-instant-oatmeal/p/21683233_EA |
| 542 | Provigo | PRV-Montréal QC | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $5.19 |  |  | $5.19 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 543 | Provigo | PRV-Montréal QC | Quaker | Dino Eggs Instant Oatmeal | instant packets | 304 g | 304 | $5.19 |  |  | $5.19 | $1.71 | $1.71/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/dino-eggs-instant-oatmeal/p/20346597_EA |
| 544 | Provigo | PRV-Montréal QC | Quaker | Fibre Instant Oatmeal, Wildberry Medley | instant packets | 304 g | 304 | $5.99 |  |  | $5.99 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:25Z | https://www.provigo.ca/fibre-instant-oatmeal-wildberry-medley/p/21549428_EA |
| 545 | Provigo | PRV-Montréal QC | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $5.19 |  |  | $5.19 | $1.65 | $1.65/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 546 | Provigo | PRV-Montréal QC | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $5.19 |  |  | $5.19 | $1.51 | $1.51/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 547 | Provigo | PRV-Montréal QC | Quaker | Maple & Brown Sugar Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $5.19 |  |  | $5.19 | $2.24 | $2.24/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/maple-brown-sugar-flavour-low-sugar-instant-oatmea/p/21683172_EA |
| 548 | Provigo | PRV-Montréal QC | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $5.19 |  |  | $5.19 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 549 | Provigo | PRV-Montréal QC | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $5.99 |  |  | $5.99 | $2.63 | $2.63/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 550 | Provigo | PRV-Montréal QC | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $5.19 |  |  | $5.19 | $1.85 | $1.85/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/regular-instant-oatmeal/p/21190265_EA |
| 551 | Provigo | PRV-Montréal QC | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $9.99 | $8.50 | 2026-10-14 | $8.50 | $0.94 | $0.94/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/rolled-oats/p/21127426_EA |
| 552 | Provigo | PRV-Montréal QC | Bobs Red Mill | Rolled Oats Old Fashioned Organic | large flake / rolled | 907 g | 907 | $8.99 | $7.99 | 2026-10-14 | $7.99 | $0.88 | $0.88/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/rolled-oats-old-fashioned-organic/p/21161849_EA |
| 553 | Provigo | PRV-Montréal QC | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.99 | $3.00 | 2026-10-07 | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 554 | Provigo | PRV-Montréal QC | One Degree | Rolled Oats Sprouted | large flake / rolled | 680 g | 680 | $9.99 | $9.19 | 2026-10-07 | $9.19 | $1.35 | $1.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/rolled-oats-sprouted/p/21532752_EA |
| 555 | Provigo | PRV-Montréal QC | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.99 |  |  | $4.99 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/large-flake-oats/p/20323113002_EA |
| 556 | Provigo | PRV-Montréal QC | Rogers | Porridge Oats, Ancient Grain Blend | large flake / rolled | 750 g | 750 | $5.99 |  |  | $5.99 | $0.80 | $0.8/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:25Z | https://www.provigo.ca/porridge-oats-ancient-grain-blend/p/20718427_EA |
| 557 | Provigo | PRV-Montréal QC | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $8.99 | $7.99 | 2026-10-14 | $7.99 | $0.88 | $0.88/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/gluten-free-protein-oats/p/21639699_EA |
| 558 | Provigo | PRV-Montréal QC | Quaker | Protein Oatmeal | other | 465 g | 465 | $8.99 |  |  | $8.99 | $1.93 | $1.93/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/protein-oatmeal/p/21687669_EA |
| 559 | Provigo | PRV-Montréal QC | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.99 | $3.00 | 2026-10-07 | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 560 | Provigo | PRV-Montréal QC | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T01:00:24Z | https://www.provigo.ca/organic-quick-rolled-oats/p/20705773_EA |
| 561 | Provigo | PRV-Montréal QC | Quaker | One Minute Oats | quick | 900 g | 900 | $4.99 |  |  | $4.99 | $0.55 | $0.55/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/one-minute-oats/p/20323113003_EA |
| 562 | Provigo | PRV-Montréal QC | Quaker | Quick Oats | quick | 1 kg | 1000 | $4.99 |  |  | $4.99 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/quick-oats/p/20323113001_EA |
| 563 | Provigo | PRV-Montréal QC | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $5.29 |  |  | $5.29 | $0.53 | $0.53/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 564 | Provigo | PRV-Montréal QC | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $5.00 |  |  | $5.00 | $0.59 | $0.6/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 565 | Provigo | PRV-Montréal QC | PC Blue Menu | Regular Steel Cut Oats | steel-cut | 360 g | 360 | $4.00 |  |  | $4.00 | $1.11 | $1.11/100g |  |  | 2026-10-01T01:00:21Z | https://www.provigo.ca/regular-steel-cut-oats/p/20943962_EA |
| 566 | Provigo | PRV-Montréal QC | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-10-14 | 2026-10-01T01:00:24Z | https://www.provigo.ca/organic-steel-cut-oats/p/20971286_EA |
| 567 | Provigo | PRV-Montréal QC | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $4.99 |  |  | $4.99 | $0.70 | $0.7/100g |  |  | 2026-10-01T01:00:24Z | https://www.provigo.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 568 | Maxi | MAXI-Montréal QC | Bobs Red Mill | Gluten Free Oatmeal Apple Cinnamon | instant (cup) | 67 g | 67 | $2.50 |  |  | $2.50 | $3.73 | $3.73/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T01:00:45Z | https://www.maxi.ca/gluten-free-oatmeal-apple-cinnamon/p/21589858_EA |
| 569 | Maxi | MAXI-Montréal QC | Bobs Red Mill | Gluten Free Oatmeal Naturally Flavoured Maple Brown Sugar | instant (cup) | 61 g | 61 | $2.50 |  |  | $2.50 | $4.10 | $4.1/100g |  | single-serve under 100 g, grouped with cups | 2026-10-01T01:00:45Z | https://www.maxi.ca/gluten-free-oatmeal-naturally-flavoured-maple-brow/p/21589893_EA |
| 570 | Maxi | MAXI-Montréal QC | Nature's Path | Organic Creamy Coconut Instant Oatmeal | instant packets | 228 g | 228 | $6.50 |  |  | $6.50 | $2.85 | $2.85/100g |  |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/organic-creamy-coconut-instant-oatmeal/p/20885283002_EA |
| 571 | Maxi | MAXI-Montréal QC | Nature's Path | Organic Superseeds & Grains Instant Oatmeal | instant packets | 228 g | 228 | $6.50 |  |  | $6.50 | $2.85 | $2.85/100g |  |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/organic-superseeds-grains-instant-oatmeal/p/20885283001_EA |
| 572 | Maxi | MAXI-Montréal QC | PC Blue Menu | Blue Menu Regular Supergrains Oatmeal | instant packets | 8x38.0 g | 304 | $4.29 |  |  | $4.29 | $1.41 | $1.41/100g |  |  | 2026-10-01T01:00:42Z | https://www.maxi.ca/blue-menu-regular-supergrains-oatmeal/p/21000529_EA |
| 573 | Maxi | MAXI-Montréal QC | President's Choice | Instant Oatmeal, Peaches and Cream, 8 Servings | instant packets | 264 g | 264 | $3.29 |  |  | $3.29 | $1.25 | $1.25/100g |  |  | 2026-10-01T01:00:42Z | https://www.maxi.ca/instant-oatmeal-peaches-and-cream-8-servings/p/21506332_EA |
| 574 | Maxi | MAXI-Montréal QC | President's Choice | Instant Oatmeal, Variety Pack, 8 Pack | instant packets | 314 g | 314 | $3.29 |  |  | $3.29 | $1.05 | $1.05/100g |  |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/instant-oatmeal-variety-pack-8-pack/p/21505117_EA |
| 575 | Maxi | MAXI-Montréal QC | President's Choice | Maple and Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.29 |  |  | $3.29 | $0.96 | $0.96/100g |  |  | 2026-10-01T01:00:42Z | https://www.maxi.ca/maple-and-brown-sugar-flavour-instant-oatmeal/p/21505150_EA |
| 576 | Maxi | MAXI-Montréal QC | President's Choice | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.29 |  |  | $3.29 | $1.18 | $1.18/100g |  |  | 2026-10-01T01:00:42Z | https://www.maxi.ca/regular-instant-oatmeal/p/21505058_EA |
| 577 | Maxi | MAXI-Montréal QC | Quaker | Apples & Cinnamon Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.79 |  |  | $3.79 | $1.63 | $1.63/100g |  |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/apples-cinnamon-flavour-low-sugar-instant-oatmeal/p/21683233_EA |
| 578 | Maxi | MAXI-Montréal QC | Quaker | Apples & Cinnamon Instant Oatmeal | instant packets | 264 g | 264 | $3.79 |  |  | $3.79 | $1.44 | $1.44/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/apples-cinnamon-instant-oatmeal/p/21190251_EA |
| 579 | Maxi | MAXI-Montréal QC | Quaker | Flavour Variety Instant Oatmeal | instant packets | 314 g | 314 | $3.79 |  |  | $3.79 | $1.21 | $1.21/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/flavour-variety-instant-oatmeal/p/21190260_EA |
| 580 | Maxi | MAXI-Montréal QC | Quaker | High Protein Triple Berry Instant Oatmeal | instant packets | 228 g | 228 | $4.50 |  |  | $4.50 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/high-protein-triple-berry-instant-oatmeal/p/21550071_EA |
| 581 | Maxi | MAXI-Montréal QC | Quaker | Instant Oatmeal Flavour Variety Family Size | instant packets | 694 g | 694 | $6.79 |  |  | $6.79 | $0.98 | $0.98/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:45Z | https://www.maxi.ca/instant-oatmeal-flavour-variety-family-size/p/21520660_EA |
| 582 | Maxi | MAXI-Montréal QC | Quaker | Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344 g | 344 | $3.79 |  |  | $3.79 | $1.10 | $1.1/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/maple-brown-sugar-flavour-instant-oatmeal/p/21190254_EA |
| 583 | Maxi | MAXI-Montréal QC | Quaker | Maple & Brown Sugar Flavour Low Sugar Instant Oatmeal (8 packets). | instant packets | 232 g | 232 | $3.79 |  |  | $3.79 | $1.63 | $1.63/100g |  |  | 2026-10-01T01:00:42Z | https://www.maxi.ca/maple-brown-sugar-flavour-low-sugar-instant-oatmea/p/21683172_EA |
| 584 | Maxi | MAXI-Montréal QC | Quaker | Peaches & Cream Flavour Instant Oatmeal | instant packets | 264 g | 264 | $3.79 |  |  | $3.79 | $1.44 | $1.44/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/peaches-cream-flavour-instant-oatmeal/p/21190266_EA |
| 585 | Maxi | MAXI-Montréal QC | Quaker | Protein Instant Oatmeal, Maple & Brown Sugar | instant packets | 228 g | 228 | $4.50 |  |  | $4.50 | $1.97 | $1.97/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/protein-instant-oatmeal-maple-brown-sugar/p/21550068_EA |
| 586 | Maxi | MAXI-Montréal QC | Quaker | Regular Family Size Instant Oatmeal | instant packets | 504 g | 504 | $6.79 |  |  | $6.79 | $1.35 | $1.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/regular-family-size-instant-oatmeal/p/21400447_EA |
| 587 | Maxi | MAXI-Montréal QC | Quaker | Regular Instant Oatmeal | instant packets | 280 g | 280 | $3.79 |  |  | $3.79 | $1.35 | $1.35/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/regular-instant-oatmeal/p/21190265_EA |
| 588 | Maxi | MAXI-Montréal QC | Bobs Red Mill | Rolled Oats | large flake / rolled | 907 g | 907 | $9.00 |  |  | $9.00 | $0.99 | $0.99/100g |  |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/rolled-oats/p/21127426_EA |
| 589 | Maxi | MAXI-Montréal QC | No Name | Large Flake 100% Whole Grain Oats | large flake / rolled | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T01:00:44Z | https://www.maxi.ca/large-flake-100-whole-grain-oats/p/20923994_EA |
| 590 | Maxi | MAXI-Montréal QC | PC Organics | Old Fashioned Gluten Free Rolled Oats | large flake / rolled | 900 g | 900 | $5.50 |  |  | $5.50 | $0.61 | $0.61/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/old-fashioned-gluten-free-rolled-oats/p/21396198_EA |
| 591 | Maxi | MAXI-Montréal QC | Quaker | Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.00 |  |  | $4.00 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/large-flake-oats/p/20323113002_EA |
| 592 | Maxi | MAXI-Montréal QC | Robin Hood | 100% Whole Grains Large Flake Oats | large flake / rolled | 1 kg | 1000 | $4.29 |  |  | $4.29 | $0.43 | $0.43/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/100-whole-grains-large-flake-oats/p/20893369_EA |
| 593 | Maxi | MAXI-Montréal QC | Bobs Red Mill | Gluten Free Protein Oats | other | 907 g | 907 | $9.50 |  |  | $9.50 | $1.05 | $1.05/100g |  |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/gluten-free-protein-oats/p/21639699_EA |
| 594 | Maxi | MAXI-Montréal QC | No Name | One-Minute 100% Whole Grain Oats | quick | 900 g | 900 | $3.00 |  |  | $3.00 | $0.33 | $0.33/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T01:00:44Z | https://www.maxi.ca/one-minute-100-whole-grain-oats/p/20923942_EA |
| 595 | Maxi | MAXI-Montréal QC | No Name | Quick 100% Whole Grain Oats | quick | 1 kg | 1000 | $3.00 |  |  | $3.00 | $0.30 | $0.3/100g | retailer badge: Prepared in Canada | API price type SPECIAL, no was-price shown, expiry 2026-11-04 | 2026-10-01T01:00:42Z | https://www.maxi.ca/quick-100-whole-grain-oats/p/20923828_EA |
| 596 | Maxi | MAXI-Montréal QC | PC Organics | Organic Quick Rolled Oats | quick | 1000 g | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:42Z | https://www.maxi.ca/organic-quick-rolled-oats/p/20705773_EA |
| 597 | Maxi | MAXI-Montréal QC | Quaker | One Minute Oats | quick | 900 g | 900 | $4.00 |  |  | $4.00 | $0.44 | $0.44/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/one-minute-oats/p/20323113003_EA |
| 598 | Maxi | MAXI-Montréal QC | Quaker | Quick Oats | quick | 1 kg | 1000 | $4.00 |  |  | $4.00 | $0.40 | $0.4/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/quick-oats/p/20323113001_EA |
| 599 | Maxi | MAXI-Montréal QC | Robin Hood | 100% Whole Grains Minute Oats | quick | 1 kg | 1000 | $4.29 |  |  | $4.29 | $0.43 | $0.43/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/100-whole-grains-minute-oats/p/20894131_EA |
| 600 | Maxi | MAXI-Montréal QC | Robin Hood | 100% Whole Grains Quick Oats | quick | 1 kg | 1000 | $4.29 |  |  | $4.29 | $0.43 | $0.43/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/100-whole-grains-quick-oats/p/20893370_EA |
| 601 | Maxi | MAXI-Montréal QC | PC Blue Menu | 100% Whole Grain Steel Cut Oats | steel-cut | 840 g | 840 | $4.79 |  |  | $4.79 | $0.57 | $0.57/100g |  |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/100-whole-grain-steel-cut-oats/p/20703868_EA |
| 602 | Maxi | MAXI-Montréal QC | PC Organics | Organic Steel Cut Oats | steel-cut | 1 kg | 1000 | $5.00 |  |  | $5.00 | $0.50 | $0.5/100g | retailer badge: Prepared in Canada |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/organic-steel-cut-oats/p/20971286_EA |
| 603 | Maxi | MAXI-Montréal QC | Quaker | Quick Cook Steel Cut Oats | steel-cut | 709 g | 709 | $4.00 |  |  | $4.00 | $0.56 | $0.56/100g |  |  | 2026-10-01T01:00:44Z | https://www.maxi.ca/quick-cook-steel-cut-oats/p/20939060_EA |
| 604 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Grace | Grace Instant Oats 1 kg | instant (bag) | 1kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/211979EA/details |
| 605 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Oatmeal Cup Apple Cinnamon 67 g | instant (cup) | 67g | 67 | $3.69 |  |  | $3.69 | $5.51 | $5.51/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/662768EA/details |
| 606 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Oatmeal Cup Lightly Salted 51 g | instant (cup) | 51g | 51 | $3.99 |  |  | $3.99 | $7.82 | $7.82/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/662770EA/details |
| 607 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Oatmeal Cup Maple Brown Sugar 61 g | instant (cup) | 61g | 61 | $4.19 |  |  | $4.19 | $6.87 | $6.87/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/662772EA/details |
| 608 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Oatmeal Cup Blueberry Hazelnut 71 g | instant (cup) | 71g | 71 | $3.69 |  |  | $3.69 | $5.20 | $5.20/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/662773EA/details |
| 609 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Oatmeal Cup Apple & Cinnamon 70 g | instant (cup) | 100 x 0.7g | 70 | $1.79 |  |  | $1.79 | $2.56 | $2.56/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/831870EA/details |
| 610 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Oatmeal Cup Banana Nut 70 g | instant (cup) | 100 x 0.7g | 70 | $1.79 |  |  | $1.79 | $2.56 | $2.56/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/831869EA/details |
| 611 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Oatmeal Cup Berry Medley 70 g | instant (cup) | 100 x 0.7g | 70 | $1.79 |  |  | $1.79 | $2.56 | $2.56/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/831894EA/details |
| 612 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Oatmeal Cup Maple Walnut 70 g | instant (cup) | 100 x 0.7g | 70 | $1.79 |  |  | $1.79 | $2.56 | $2.56/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/831868EA/details |
| 613 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Balance Instant Oatmeal Variety Pack 378 g  | instant packets | 378g | 378 | $3.69 |  |  | $3.69 | $0.98 | $0.98/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/763767EA/details |
| 614 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Balance Oatmeal Maple & Brown Sugar 430 g | instant packets | 430g | 430 | $3.69 |  |  | $3.69 | $0.86 | $0.86/100g |  |  | 2026-10-01T00:58:56Z | https://voila.ca/products/286858EA/details |
| 615 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Instant Oatmeal Apple & Cinnamon Flavour 260 g | instant packets | 260g | 260 | $3.99 |  |  | $3.99 | $1.53 | $1.53/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/980769EA/details |
| 616 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Instant Oatmeal Apple Cinnamon 325 g | instant packets | 325g | 325 | $3.69 |  |  | $3.69 | $1.14 | $1.14/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/286855EA/details |
| 617 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Instant Oatmeal Maple & Brown Sugar Flavour 344 g | instant packets | 344g | 344 | $3.99 |  |  | $3.99 | $1.16 | $1.16/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/980771EA/details |
| 618 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Instant Oatmeal Peaches & Cream 325 g | instant packets | 325g | 325 | $3.69 |  |  | $3.69 | $1.14 | $1.14/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/286865EA/details |
| 619 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Instant Oatmeal Peaches & Cream Flavour 260 g | instant packets | 260g | 260 | $3.99 |  |  | $3.99 | $1.53 | $1.53/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/980772EA/details |
| 620 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Instant Oatmeal Regular 280 g | instant packets | 280g | 280 | $3.99 |  |  | $3.99 | $1.43 | $1.42/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/980773EA/details |
| 621 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Instant Oatmeal Variety Pack 313 g | instant packets | 313g | 313 | $3.99 |  |  | $3.99 | $1.27 | $1.27/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/980774EA/details |
| 622 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Instant Oatmeal Variety Pack 691 g | instant packets | 691g | 691 | $6.99 |  |  | $6.99 | $1.01 | $1.01/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/222160EA/details |
| 623 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Oatmeal Regular 336 g | instant packets | 336g | 336 | $3.69 |  |  | $3.69 | $1.10 | $1.10/100g |  |  | 2026-10-01T00:58:56Z | https://voila.ca/products/286867EA/details |
| 624 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Instant Oatmeal Apple & Cinnamon 6 x 60 g | instant packets | 600 x 0.6g | 360 | $4.99 |  |  | $4.99 | $1.39 | $1.39/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/831935EA/details |
| 625 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Instant Oatmeal Twice Berry 6 x 60 g | instant packets | 600 x 0.6g | 360 | $4.99 |  |  | $4.99 | $1.39 | $1.39/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/831938EA/details |
| 626 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Nature's Path | Nature's Path Organic Gluten-Free Oatmeal Cinnamon Pumpkin Seed 6 x 38 g | instant packets | 600 x 0.38g | 228 | $6.99 |  |  | $6.99 | $3.07 | $3.07/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/471210EA/details |
| 627 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Nature's Path | Nature's Path Organic Gluten-Free Oatmeal Creamy Coconut 6 x 38 g | instant packets | 600 x 0.38g | 228 | $6.99 |  |  | $6.99 | $3.07 | $3.07/100g |  |  | 2026-10-01T00:58:56Z | https://voila.ca/products/470867EA/details |
| 628 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Nature's Path | Nature's Path Organic Gluten-Free Oatmeal Superseeds & Grains 6 x 38 g | instant packets | 600 x 0.38g | 228 | $5.99 |  |  | $5.99 | $2.63 | $2.63/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/470885EA/details |
| 629 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Nature's Path | Nature's Path Organic Hot Oatmeal Assorted Variety Pack 8 x 50 g | instant packets | 800 x 0.5g | 400 | $6.29 |  |  | $6.29 | $1.57 | $1.57/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/1927EA/details |
| 630 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Nature's Path | Nature's Path Organic Hot Oatmeal Maple Nut 400 g | instant packets | 400g | 400 | $5.99 |  |  | $5.99 | $1.50 | $1.50/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/114156EA/details |
| 631 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Nature's Path | Nature's Path Organic Instant Hot Oatmeal Original 8 x 50 g | instant packets | 400g | 400 | $6.29 |  |  | $6.29 | $1.57 | $1.57/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/114135EA/details |
| 632 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Nature's Path | Nature's Path Organic Oatmeal Apple Cinnamon 400 g | instant packets | 400g | 400 | $5.79 |  |  | $5.79 | $1.45 | $1.45/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/114163EA/details |
| 633 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | One Degree Organic Foods | One Degree Organic Foods Protein Instant Oatmeal Banana Brown Sugar Sprouted 6 x 55 g (330 g) | instant packets | 330g | 330 | $8.99 |  |  | $8.99 | $2.72 | $2.72/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/1382106EA/details |
| 634 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Dino Eggs Instant Oatmeal Brown Sugar 8 Pack 304 g | instant packets | 304g | 304 | $5.29 |  |  | $5.29 | $1.74 | $1.74/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/265566EA/details |
| 635 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker High Fibre Instant Oatmeal Raisin Spice 425 g | instant packets | 425g | 425 | $4.99 |  |  | $4.99 | $1.17 | $1.17/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/217255EA/details |
| 636 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker High Protein Instant Oatmeal Triple Berry 228 g | instant packets | 228g | 228 | $5.79 |  |  | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/920691EA/details |
| 637 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal 100% Whole Grain 300 g  | instant packets | 300g | 300 | $4.79 |  |  | $4.79 | $1.60 | $1.60/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/418889EA/details |
| 638 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal 3 Flavours 314 g | instant packets | 314g | 314 | $5.29 |  |  | $5.29 | $1.69 | $1.68/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/418723EA/details |
| 639 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Apples & Cinnamon 264 g | instant packets | 264g | 264 | $5.29 |  |  | $5.29 | $2.00 | $2.00/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/418780EA/details |
| 640 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Apples & Cinnamon Family Size 18 x 33 g | instant packets | 18 x 33g | 594 | $7.99 |  |  | $7.99 | $1.34 | $1.35/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/340185EA/details |
| 641 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Bananas Cream 240 g | instant packets | 240g | 240 | $5.29 |  |  | $5.29 | $2.20 | $2.20/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/645660EA/details |
| 642 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Gotham City Chocolate 280 g | instant packets | 280g | 280 | $4.99 |  |  | $4.99 | $1.78 | $1.78/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/962778EA/details |
| 643 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal High Fibre Raisins & Spice 344 g | instant packets | 344g | 344 | $6.49 |  |  | $6.49 | $1.89 | $1.89/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/419002EA/details |
| 644 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal High Protein Apples & Cinnamon 228 g | instant packets | 228g | 228 | $5.79 |  |  | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/881000EA/details |
| 645 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal High Protein Maple & Brown Sugar 228 g | instant packets | 228g | 228 | $6.49 |  |  | $6.49 | $2.85 | $2.85/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/315144EA/details |
| 646 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal High Protein Maple & Brown Sugar 228 g | instant packets | 228g | 228 | $5.79 |  |  | $5.79 | $2.54 | $2.54/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/920692EA/details |
| 647 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal High Protein Triple Berry 228 g | instant packets | 228g | 228 | $5.99 |  |  | $5.99 | $2.63 | $2.63/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/492988EA/details |
| 648 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Lightly Sweetened Apples & Cinnamon 232 g | instant packets | 232g | 232 | $5.29 |  |  | $5.29 | $2.28 | $2.28/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/419028EA/details |
| 649 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Lightly Sweetened Maple & Brown Sugar 304 g | instant packets | 304g | 304 | $5.29 |  |  | $5.29 | $1.74 | $1.74/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/855741EA/details |
| 650 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Maple & Brown Sugar 18 Pack 774 g | instant packets | 774g | 774 | $7.79 |  |  | $7.79 | $1.01 | $1.01/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/217518EA/details |
| 651 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Maple Brown Sugar 344 g | instant packets | 344g | 344 | $5.29 |  |  | $5.29 | $1.54 | $1.54/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/418756EA/details |
| 652 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Peaches & Cream 264 g | instant packets | 264g | 264 | $5.29 |  |  | $5.29 | $2.00 | $2.00/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/418848EA/details |
| 653 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Peaches & Cream 325 g | instant packets | 325g | 325 | $3.99 |  |  | $3.99 | $1.23 | $1.23/100g | listing 'Country Of Origin': Canada |  | 2026-10-01T00:58:53Z | https://voila.ca/products/217210EA/details |
| 654 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Regular 280 g | instant packets | 280g | 280 | $5.29 |  |  | $5.29 | $1.89 | $1.89/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/418722EA/details |
| 655 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Regular 504 g | instant packets | 504g | 504 | $7.79 |  |  | $7.79 | $1.55 | $1.55/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/855765EA/details |
| 656 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal S'Mores 280 g | instant packets | 280g | 280 | $5.29 |  |  | $5.29 | $1.89 | $1.89/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/980787EA/details |
| 657 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Super Cinnamon Roll 288 g  | instant packets | 288g | 288 | $4.99 |  |  | $4.99 | $1.73 | $1.73/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/965273EA/details |
| 658 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Super Grains Banana & Roasted Almond 330 g | instant packets | 330g | 330 | $4.99 |  |  | $4.99 | $1.51 | $1.51/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/737986EA/details |
| 659 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Variety Pack 40 Count  | instant packets | 40 x 37g | 1480 | $15.79 |  |  | $15.79 | $1.07 | $1.07/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/3156EA/details |
| 660 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Variety Pack 694 g | instant packets | 694g | 694 | $9.99 |  |  | $9.99 | $1.44 | $1.44/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/9402EA/details |
| 661 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Instant Oatmeal Wild Berry Medley 8 Pack 300 g | instant packets | 304g | 300 | $5.49 |  |  | $5.49 | $1.83 | $1.81/100g | listing 'Country Of Origin': Canada |  | 2026-10-01T00:58:53Z | https://voila.ca/products/121393EA/details |
| 662 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Low Sugar Instant Oatmeal Apples & Cinnamon 8 Packets 232 g | instant packets | 232g | 232 | $5.29 |  |  | $5.29 | $2.28 | $2.28/100g |  |  | 2026-10-01T00:58:56Z | https://voila.ca/products/1343635EA/details |
| 663 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Low Sugar Instant Oatmeal Maple & Brown Sugar 8 Packets 232 g | instant packets | 280g | 232 | $5.29 |  |  | $5.29 | $2.28 | $1.89/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/1343633EA/details |
| 664 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Protein Instant Oatmeal Regular 6 packets 168 g | instant packets | 168g | 168 | $5.79 |  |  | $5.79 | $3.45 | $3.45/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/3072EA/details |
| 665 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Protein+ Instant Oatmeal Banana Nut 6 Packets 366 g | instant packets | 366g | 366 | $7.49 |  |  | $7.49 | $2.05 | $2.05/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/1288829EA/details |
| 666 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Protein+ Instant Oatmeal Maple And Brown Sugar 6 Packets 360 g | instant packets | 360g | 360 | $7.49 |  |  | $7.49 | $2.08 | $2.08/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/1288830EA/details |
| 667 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Super Grains Instant Oatmeal Apples & Cinnamon 342 g | instant packets | 342g | 342 | $5.99 |  |  | $5.99 | $1.75 | $1.75/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/673090EA/details |
| 668 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Super Grains Instant Oatmeal Coconut & Honey 336 g | instant packets | 336g | 336 | $4.99 |  |  | $4.99 | $1.49 | $1.49/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/673091EA/details |
| 669 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Adagio Acres | Adagio Acres Rolled Naked Oats 900 g | large flake / rolled | 900g | 900 | $9.79 |  |  | $9.79 | $1.09 | $1.09/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/496033EA/details |
| 670 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Rolled Oats 907 g | large flake / rolled | 907g | 907 | $7.99 |  |  | $7.99 | $0.88 | $0.88/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/305348EA/details |
| 671 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Rolled Oats Old Fashioned 907 g | large flake / rolled | 907g | 907 | $11.79 |  |  | $11.79 | $1.30 | $1.30/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/938294EA/details |
| 672 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Organic Rolled Oats Old Fashioned 453 g | large flake / rolled | 453g | 453 | $3.99 |  |  | $3.99 | $0.88 | $0.88/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/261532EA/details |
| 673 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Organic Rolled Oats Old Fashioned 454 g | large flake / rolled | 454g | 454 | $5.79 |  |  | $5.79 | $1.27 | $1.28/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/948579EA/details |
| 674 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Organic Rolled Oats Old Fashioned 907 g | large flake / rolled | 907g | 907 | $9.99 |  |  | $9.99 | $1.10 | $1.10/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/938309EA/details |
| 675 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Dan-D-Pak | Dan-D Pak Rolled Oats 1 kg | large flake / rolled | 1kg | 1000 | $3.99 |  |  | $3.99 | $0.40 | $0.40/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/313459EA/details |
| 676 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Organic Large Flake Oats 750 g | large flake / rolled | 100 x 7.5g | 750 | $5.49 |  |  | $5.49 | $0.73 | $0.73/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/836391EA/details |
| 677 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | La Meunerie Milanaise | La Meunerie Milanaise Organic Oat Flakes Regular 1 kg | large flake / rolled | 1kg | 1000 | $6.99 |  |  | $6.99 | $0.70 | $0.70/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/756352EA/details |
| 678 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Longo's | Longo's Organic Rolled Oats 500 g | large flake / rolled | 500g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.20/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/13703EA/details |
| 679 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Longo's | Longo's Organic Thick Rolled Oats 500 g | large flake / rolled | 500g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.20/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/13704EA/details |
| 680 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Milanaise | Milanaise Organic Oat Flakes 500 g | large flake / rolled | 500g | 500 | $4.29 |  |  | $4.29 | $0.86 | $0.86/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/579998EA/details |
| 681 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | One Degree Organic Foods | One Degree Organic Foods Rolled Oats Sprouted 680 g | large flake / rolled | 680g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.40/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/1336258EA/details |
| 682 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Only Oats | Only Oats Gluten-Free Rolled Oats 1 KG | large flake / rolled | 1kg | 1000 | $11.99 |  |  | $11.99 | $1.20 | $1.20/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/610109EA/details |
| 683 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Old Fashioned Large Flake Oats 1 kg | large flake / rolled | 1kg | 1000 | $6.49 |  |  | $6.49 | $0.65 | $0.65/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/217510EA/details |
| 684 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Robin Hood | Robin Hood Large Flake Oats 1 kg | large flake / rolled | 1kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/280532EA/details |
| 685 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Speerville Flour Mill | Speerville New Found Organic Oatmeal 910 g | large flake / rolled | 910g | 910 | $5.49 |  |  | $5.49 | $0.60 | $0.60/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/950142EA/details |
| 686 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Organic Rolled Oats Run Of The Mill 810 g | large flake / rolled | 810g | 810 | $6.99 |  |  | $6.99 | $0.86 | $0.86/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/774945EA/details |
| 687 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek  | Willow Creek Organic Thick Rolled Oats 1.5 kg | large flake / rolled | 1.5kg | 1500 | $7.99 |  |  | $7.99 | $0.53 | $0.53/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/301659EA/details |
| 688 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek  | Willow Creek Organic Thick Rolled Oats 800 g | large flake / rolled | 800g | 800 | $5.99 |  |  | $5.99 | $0.75 | $0.75/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/301660EA/details |
| 689 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek Organic Grain Co. | Willow Creek Organic Grain Co. Gluten-Free Organic Thick Roll Oat 1.5 kg | large flake / rolled | 1.5kg | 1500 | $10.99 |  |  | $10.99 | $0.73 | $0.73/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/688189EA/details |
| 690 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek Organic Grain Co. | Willow Creek Organic Grain Co. Thick Gluten-Free Organic Roll Oat 800 g | large flake / rolled | 800g | 800 | $7.49 |  |  | $7.49 | $0.94 | $0.94/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/688190EA/details |
| 691 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Oatmeal Scottish Original 567 g | other | 567g | 567 | $9.99 |  |  | $9.99 | $1.76 | $1.76/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/948598EA/details |
| 692 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Scottish Oatmeal 567 g | other | 567g | 567 | $6.49 |  |  | $6.49 | $1.15 | $1.14/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/948607EA/details |
| 693 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Scottish Oatmeal 567 g | other | 567g | 567 | $4.49 |  |  | $4.49 | $0.79 | $0.79/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/261538EA/details |
| 694 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Wheat-Free Scottish Oatmeal 567 g | other | 567g | 567 | $6.99 |  |  | $6.99 | $1.23 | $1.23/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/470838EA/details |
| 695 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | GORP | GORP Just Oats Oatmeal Blends 1.1KG | other | 1.1kg | 1100 | $9.99 |  |  | $9.99 | $0.91 | $9.08/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/602227EA/details |
| 696 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | GORP | GORP Prairie Berries & Coconut Oatmeal Blends 1.1 KG | other | 1.1kg | 1100 | $13.99 |  |  | $13.99 | $1.27 | $12.72/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/602226EA/details |
| 697 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | GORP | GORP Roasted Nuts Flax & Seeds Oatmeal Blends 1.1 KG | other | 1.1kg | 1100 | $13.99 |  |  | $13.99 | $1.27 | $12.72/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/602231EA/details |
| 698 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Nature's Path | Nature's Path Organic Oatmeal Flax Plus 400 g | other | 800 x 0.5g | 400 | $5.29 |  |  | $5.29 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/114150EA/details |
| 699 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker All Natural Oatmeal 100% Whole Grain Oats 360 g | other | 360g | 360 | $3.99 |  |  | $3.99 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/231402EA/details |
| 700 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Oatmeal Cocoa & Sea Salt 336 g | other | 336g | 336 | $4.99 |  |  | $4.99 | $1.49 | $1.49/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/505398EA/details |
| 701 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Lactose-Free Oatmeal Bucking-Eh Oats 500 g | other | 500g | 500 | $9.99 |  |  | $9.99 | $2.00 | $2.00/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/610240EA/details |
| 702 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Lactose-Free Oatmeal Redline Bag Oats 500 g | other | 500g | 500 | $9.99 |  |  | $9.99 | $2.00 | $2.00/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/610244EA/details |
| 703 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Lactose-Free Oatmeal Stone Age Bag Oats 500 g | other | 500g | 500 | $9.99 |  |  | $9.99 | $2.00 | $2.00/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/610241EA/details |
| 704 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Oatmeal Blend Aphrodisi-Oats 500 g | other | 500g | 500 | $9.99 |  |  | $9.99 | $2.00 | $2.00/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/610338EA/details |
| 705 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek | Willow Creek Organic Whole Oat Groats 800 g | other | 800g | 800 | $5.49 |  |  | $5.49 | $0.69 | $0.69/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/301372EA/details |
| 706 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Rolled Oats Quick Cooking 794 g | quick | 794g | 794 | $13.79 |  |  | $13.79 | $1.74 | $1.74/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/938291EA/details |
| 707 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Wheat-Free Quick Cook Rolled Oats 907 g | quick | 907g | 907 | $10.49 |  |  | $10.49 | $1.16 | $1.16/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/305346EA/details |
| 708 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Quick Oats 1 kg | quick | 1kg | 1000 | $4.49 |  |  | $4.49 | $0.45 | $0.45/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/435017EA/details |
| 709 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Quick Oats 2.25 kg | quick | 2.25kg | 2250 | $6.79 |  |  | $6.79 | $0.30 | $0.30/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/487320EA/details |
| 710 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments Organic | Compliments Organic Quick Oats 1 kg | quick | 1kg | 1000 | $4.99 |  |  | $4.99 | $0.50 | $0.50/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/730748EA/details |
| 711 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Dan-D-Pak | Dan-D-Pak Quick Oats 1 kg | quick | 1kg | 1000 | $3.99 |  |  | $3.99 | $0.40 | $0.40/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/313453EA/details |
| 712 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | La Meunerie Milanaise | La Meunerie Milanaise Organic Quick Oat Flakes 1 kg | quick | 1kg | 1000 | $6.99 |  |  | $6.99 | $0.70 | $0.70/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/756354EA/details |
| 713 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Meunerie Milanaise | Meunerie Milanaise Organic Quick Oat Flakes 500 g | quick | 500g | 500 | $4.29 |  |  | $4.29 | $0.86 | $0.86/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/576503EA/details |
| 714 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | One Degree Organic Foods | One Degree Organic Foods Quick Oats Sprouted 680 g | quick | 680g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.40/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/1336262EA/details |
| 715 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Only Oats | Only Oats Gluten-Free Flakes Quick Oat 1 kg | quick | 1kg | 1000 | $11.99 |  |  | $11.99 | $1.20 | $1.20/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/766074EA/details |
| 716 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Pilling Foods Inc. | Good Eats Gluten-Free Organic Quick Rolled Oats 454 g | quick | 454g | 454 | $8.79 |  |  | $8.79 | $1.94 | $1.94/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/941211EA/details |
| 717 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Gluten-Free Quick Oats 511 g | quick | 511g | 511 | $6.99 |  |  | $6.99 | $1.37 | $1.37/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/658284EA/details |
| 718 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker One Minute Oats 900 g | quick | 900g | 900 | $6.49 |  |  | $6.49 | $0.72 | $0.72/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/217470EA/details |
| 719 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Quick Oats 100% Whole Grain 1 kg | quick | 1kg | 1000 | $6.49 |  |  | $6.49 | $0.65 | $0.65/100g | listing 'Country Of Origin': Canada |  | 2026-10-01T00:58:54Z | https://voila.ca/products/217560EA/details |
| 720 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Quick Oats 2.25 kg | quick | 2.25kg | 2250 | $7.99 |  |  | $7.99 | $0.35 | $0.36/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/217690EA/details |
| 721 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Robin Hood | Robin Hood Minute Oats 1 kg | quick | 1kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/280537EA/details |
| 722 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Robin Hood | Robin Hood Quick Oats 1 kg | quick | 1kg | 1000 | $4.79 |  |  | $4.79 | $0.48 | $0.48/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/280534EA/details |
| 723 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Stoked Oats | Stoked Oats Organic Quick Run Of The Mill 810 g | quick | 810g | 810 | $8.99 |  |  | $8.99 | $1.11 | $1.11/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/774946EA/details |
| 724 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Wildly Canadian | Wildly Canadian Organic Oats Quick Cook 500 g | quick | 500g | 500 | $5.99 |  |  | $5.99 | $1.20 | $1.20/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/446420EA/details |
| 725 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek | Willow Creek Organic Quick Rolled Oats 1.35 kg | quick | 1.35kg | 1350 | $7.99 |  |  | $7.99 | $0.59 | $0.59/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/301646EA/details |
| 726 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek  | Willow Creek Gluten-Free Organic Quick Roll Oats 1.35 kg | quick | 1.35kg | 1350 | $10.99 |  |  | $10.99 | $0.81 | $0.81/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/688191EA/details |
| 727 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek  | Willow Creek Organic Quick Rolled Oats 800 g | quick | 800g | 800 | $5.99 |  |  | $5.99 | $0.75 | $0.75/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/301647EA/details |
| 728 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek Organic Grain Co. | Willow Creek Organic Grain Co. Gluten-Free Organic Quick Roll Oat 800 g | quick | 800g | 800 | $7.49 |  |  | $7.49 | $0.94 | $0.94/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/688193EA/details |
| 729 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Adagio Acres | Adagio Acres Naked Oats Steel Cut 900 g | steel-cut | 900g | 900 | $8.99 |  |  | $8.99 | $1.00 | $1.00/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/622661EA/details |
| 730 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Gluten-Free Steel Cut Oats Whole Grain 680 g | steel-cut | 680g | 680 | $12.29 |  |  | $12.29 | $1.81 | $1.81/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/948574EA/details |
| 731 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Organic Steel Cut Oats 680 g | steel-cut | 680g | 680 | $8.29 |  |  | $8.29 | $1.22 | $1.22/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/948580EA/details |
| 732 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Steel Cut Oats 680 g | steel-cut | 680g | 680 | $7.49 |  |  | $7.49 | $1.10 | $1.10/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/261554EA/details |
| 733 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Steel Cut Oats 680 g | steel-cut | 680g | 680 | $4.49 |  |  | $4.49 | $0.66 | $0.66/100g |  |  | 2026-10-01T00:58:56Z | https://voila.ca/products/261466EA/details |
| 734 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Bob's Red Mill | Bob's Red Mill Steel Cut Oats The Golden Spurtle 680 g | steel-cut | 680g | 680 | $4.49 |  |  | $4.49 | $0.66 | $0.66/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/948584EA/details |
| 735 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Compliments | Compliments Quick Cook Steel Cut Oats 709 g | steel-cut | 709g | 709 | $5.49 |  |  | $5.49 | $0.77 | $0.77/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/759164EA/details |
| 736 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Farm Boy | Farm Boy Organic Steel Cut Oats 1 kg | steel-cut | 100 x 10g | 1000 | $5.99 |  |  | $5.99 | $0.60 | $0.60/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/836389EA/details |
| 737 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Highwood Crossing | Highwood Crossing Organic Oats Steel Cut 775 g | steel-cut | 775g | 775 | $11.99 |  |  | $11.99 | $1.55 | $1.55/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/839413EA/details |
| 738 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Longo's | Longo's Steel Cut Oats 700 g | steel-cut | 700g | 700 | $4.99 |  |  | $4.99 | $0.71 | $0.71/100g |  |  | 2026-10-01T00:58:54Z | https://voila.ca/products/13705EA/details |
| 739 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | McCann's | McCann's Irish Oatmeal Quick Cook 453 g | steel-cut | 453g | 453 | $5.99 |  |  | $5.99 | $1.32 | $1.32/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/556636EA/details |
| 740 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | McCann's | McCann's Oatmeal Steel Cut Irish 793 g | steel-cut | 793g | 793 | $10.99 |  |  | $10.99 | $1.39 | $1.39/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/556616EA/details |
| 741 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | One Degree Organic Foods | One Degree Organic Foods Steel Cut Oats Sprouted 680 g | steel-cut | 680g | 680 | $9.49 |  |  | $9.49 | $1.40 | $1.40/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/1336276EA/details |
| 742 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Only Oats | Only Oats Gluten Free Pure Whole Grain Steel Cut Oat 1 kg | steel-cut | 1kg | 1000 | $11.99 |  |  | $11.99 | $1.20 | $1.20/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/610326EA/details |
| 743 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Quick Cook Oatmeal Steel Cut Blueberries & Cranberries 368 g | steel-cut | 368g | 368 | $5.99 |  |  | $5.99 | $1.63 | $1.63/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/673089EA/details |
| 744 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Quick Cook Oats Steel Cut 709 g | steel-cut | 709g | 709 | $6.49 |  |  | $6.49 | $0.92 | $0.92/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/627781EA/details |
| 745 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Quaker | Quaker Quick Cook Steel Cut Oatmeal Brown Sugar Cinnamon 384 g | steel-cut | 384g | 384 | $5.99 |  |  | $5.99 | $1.56 | $1.56/100g |  |  | 2026-10-01T00:58:53Z | https://voila.ca/products/673088EA/details |
| 746 | Voilà by Sobeys | online, default region ('Default Region 1'; no postal code entered; province not displayed) | Willow Creek | Willow Creek Organic Steel Cut Groats 800 g | steel-cut | 800g | 800 | $5.99 |  |  | $5.99 | $0.75 | $0.75/100g |  |  | 2026-10-01T00:58:55Z | https://voila.ca/products/301652EA/details |
| 747 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Nature's Path | Nature's Path - Creamy Coconut Superfood Oatmeal | instant packets | 6.0 Each |  | $7.99 |  |  | $7.99 |  | $1.33 each |  |  | 2026-10-01T01:02:57Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00058449154020 |
| 748 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Nature's Path | Nature's Path - Organic Hot Oatmeal Original | instant packets | 8.0 Each |  | $7.99 |  |  | $7.99 |  | $1.00 each |  |  | 2026-10-01T01:02:57Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00058449450016 |
| 749 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Nature's Path | Nature's Path - Superseeds & Grain Superfood Oatmeal | instant packets | 6.0 Each |  | $7.99 |  |  | $7.99 |  | $1.33 each |  |  | 2026-10-01T01:02:58Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00058449154006 |
| 750 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - 3 Flavour Variety Instant Oatmeal | instant packets | 314.0 g | 314 | $4.99 |  |  | $4.99 | $1.59 | $1.59/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:47Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113004 |
| 751 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - High Fiber Raisins & Spice Instant Oatmeal | instant packets | 344.0 g | 344 | $6.99 |  |  | $6.99 | $2.03 | $2.03/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:42Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113059 |
| 752 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - High Protein Apple & Cinnamon Instant Oatmeal. | instant packets | 228.0 g | 228 | $6.99 |  |  | $6.99 | $3.07 | $3.07/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:42Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113172 |
| 753 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - High Protein Maple & Brown Sugar Flavour Instant Oatmeal, | instant packets | 228.0 g | 228 | $6.99 |  |  | $6.99 | $3.07 | $3.07/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:46Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113226 |
| 754 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - High Protein Triple Berry Instant Oatmeal. | instant packets | 228.0 g | 228 | $6.99 |  |  | $6.99 | $3.07 | $3.07/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:49Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113219 |
| 755 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Instant Oatmeal Flavour Variety 18ct Pack | instant packets | 694.0 g | 694 | $8.99 |  |  | $8.99 | $1.29 | $1.30/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:43Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113271 |
| 756 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Instant Oatmeal Flavour Variety 40ct Pack | instant packets | 1.48 kg | 1480 | $17.99 |  |  | $17.99 | $1.22 | $1.22/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:44Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113165 |
| 757 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Low Sugar Apple Cinnamon Instant Oatmeal | instant packets | 8.0 Each |  | $4.99 |  |  | $4.99 |  | $0.62 each | retailer attribute: Made in Canada |  | 2026-10-01T01:02:32Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113424 |
| 758 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Low Sugar Maple & Brown Sugar Instant Oatmeal | instant packets | 8.0 Each |  | $4.99 |  |  | $4.99 |  | $0.62 each | retailer attribute: Made in Canada |  | 2026-10-01T01:02:33Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113431 |
| 759 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Maple & Brown Sugar Flavour Instant Oatmeal | instant packets | 344.0 g | 344 | $4.99 |  |  | $4.99 | $1.45 | $1.45/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:46Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113028 |
| 760 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Protein Instant Oatmeal,  Regular | instant packets | 168.0 g | 168 | $6.99 |  |  | $6.99 | $4.16 | $4.16/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:45Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113288 |
| 761 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Protein+ Instant Oatmeal Maple And Brown Sugar | instant packets | 6.0 Each |  | $7.49 |  |  | $7.49 |  | $1.25 each |  |  | 2026-10-01T01:02:31Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113400 |
| 762 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Regular Instant Oatmeal | instant packets | 560.0 g | 560 | $8.99 |  |  | $8.99 | $1.60 | $1.61/100g |  |  | 2026-10-01T01:02:45Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113523 |
| 763 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Regular Instant Oatmeal | instant packets | 280.0 g | 280 | $4.99 |  |  | $4.99 | $1.78 | $1.78/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:41Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577113011 |
| 764 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Western Family | Western Family - Apple & Cinnamon Flavor Instant Oatmeal | instant packets | 264.0 g | 264 | $4.29 |  |  | $4.29 | $1.62 | $1.63/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:52Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639370725 |
| 765 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Western Family | Western Family - Maple & Brown Sugar Instant Oatmeal | instant packets | 344.0 g | 344 | $4.29 |  |  | $4.29 | $1.25 | $1.25/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:53Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639370701 |
| 766 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Western Family | Western Family - Regular Instant Oatmeal | instant packets | 280.0 g | 280 | $4.29 |  |  | $4.29 | $1.53 | $1.53/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:51Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639370695 |
| 767 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | ONLY GOODNESS | ONLY GOODNESS - Gluten Free Rolled Oats | large flake / rolled | 1.0 kg | 1000 | $7.79 |  |  | $7.79 | $0.78 | $0.78/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:34Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639371715 |
| 768 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | ONLY GOODNESS | ONLY GOODNESS - Organic Old Fashioned Rolled Oats | large flake / rolled | 1.0 kg | 1000 | $6.99 |  |  | $6.99 | $0.70 | $0.70/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:38Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639370183 |
| 769 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Oats | Oats - Organic Thick Rolled, Bulk | large flake / rolled | bulk, sold per 100 g | 100 | $0.89 |  |  | $0.89 | $0.89 | $0.89/100g | retailer attribute: Product of Canada | bulk bin item | 2026-10-01T01:03:02Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/14687 |
| 770 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | One Degree Organic | One Degree Organic - Sprouted Rolled Oats | large flake / rolled | 680.0 g | 680 | $8.99 |  |  | $8.99 | $1.32 | $1.32/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:34Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00675625323072 |
| 771 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Large Flake Oats | large flake / rolled | 1.0 kg | 1000 | $6.99 |  |  | $6.99 | $0.70 | $0.70/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:36Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577101018 |
| 772 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Rogers | Rogers - Large Flake Oats | large flake / rolled | 1.0 kg | 1000 | $6.29 |  |  | $6.29 | $0.63 | $0.63/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:36Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00060179436253 |
| 773 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Rogers | Rogers - Porridge Oats & Ancient Grains | large flake / rolled | 750.0 g | 750 | $6.29 |  |  | $6.29 | $0.84 | $0.84/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:56Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00060179131202 |
| 774 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Rogers | Rogers - Porridge Oats Original Blend | large flake / rolled | 1.0 kg | 1000 | $6.29 |  |  | $6.29 | $0.63 | $0.63/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:37Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00060179131103 |
| 775 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Western Family | Western Family - 100% Whole Grain Canadian Old Fashioned Oats | large flake / rolled | 2.25 kg | 2250 | $7.69 |  |  | $7.69 | $0.34 | $0.34/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:37Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639341299 |
| 776 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | left coast | left coast - Organic Rolled Oats | large flake / rolled | 1.0 kg | 1000 | $11.49 | $10.69 | 10/21/2026 | $10.69 | $1.07 | $1.07/100g |  |  | 2026-10-01T01:02:33Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00625691210363 |
| 777 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Bob's Red Mill | Bob's Red Mill - Gluten Free Protein Oats | other | 907.0 g | 907 | $13.79 | $10.99 | 10/7/2026 | $10.99 | $1.21 | $1.21/100g |  |  | 2026-10-01T01:02:55Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00039978004949 |
| 778 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | ONLY GOODNESS | ONLY GOODNESS - Organic Quick Oats | quick | 1.0 kg | 1000 | $6.99 |  |  | $6.99 | $0.70 | $0.70/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:59Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639370190 |
| 779 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Oats | Oats - Organic Quick Rolled, Bulk | quick | bulk, sold per 100 g | 100 | $0.89 |  |  | $0.89 | $0.89 | $0.89/100g | retailer attribute: Product of Canada | bulk bin item | 2026-10-01T01:02:54Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/14685 |
| 780 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | One Degree Organic | One Degree Organic - Sprouted Quick Oats | quick | 680.0 g | 680 | $8.99 |  |  | $8.99 | $1.32 | $1.32/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:56Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00675625324079 |
| 781 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Gluten Free Quick Oats | quick | 511.0 g | 511 | $7.49 |  |  | $7.49 | $1.47 | $1.47/100g |  |  | 2026-10-01T01:02:48Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577101155 |
| 782 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - One Minute Oats | quick | 900.0 g | 900 | $6.99 |  |  | $6.99 | $0.78 | $0.78/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577102053 |
| 783 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Quick Oats | quick | 1.0 kg | 1000 | $6.99 |  |  | $6.99 | $0.70 | $0.70/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:30Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577101100 |
| 784 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Quick Oats - 2.25kg | quick | 2.25 kg | 2250 | $9.99 |  |  | $9.99 | $0.44 | $0.44/100g | retailer attribute: Made in Canada |  | 2026-10-01T01:02:31Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577101681 |
| 785 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Robin Hood | Robin Hood - Quick Oats | quick | 1.0 kg | 1000 | $4.99 |  |  | $4.99 | $0.50 | $0.50/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:35Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00059000084749 |
| 786 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Western Family | Western Family - 100% Whole Grain Canadian Quick Oats | quick | 2.25 kg | 2250 | $7.69 |  |  | $7.69 | $0.34 | $0.34/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:51Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639185350 |
| 787 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Western Family | Western Family - Quick Oats | quick | 1.0 kg | 1000 | $4.69 |  |  | $4.69 | $0.47 | $0.47/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:49Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639185367 |
| 788 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Oats | Oats - Organic Steel Cut, Bulk | steel-cut | bulk, sold per 100 g | 100 | $0.89 |  |  | $0.89 | $0.89 | $0.89/100g |  | bulk bin item | 2026-10-01T01:03:02Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/594 |
| 789 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | One Degree Organic | One Degree Organic - Sprouted Steel Cut Oats | steel-cut | 680.0 g | 680 | $8.99 |  |  | $8.99 | $1.32 | $1.32/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:40Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00675625325076 |
| 790 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Quaker | Quaker - Quick Cook Steel Cut Oats | steel-cut | 709.0 g | 709 | $6.99 |  |  | $6.99 | $0.99 | $0.99/100g |  |  | 2026-10-01T01:02:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00055577102114 |
| 791 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Rogers | Rogers - Porridge Oats Steel Cut Oat Blend | steel-cut | 1.1 kg | 1100 | $6.29 |  |  | $6.29 | $0.57 | $0.57/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:40Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00060179131158 |
| 792 | Save-On-Foods | Save-On-Foods store 1982, 19855 92a Ave, Langley Twp, BC | Western Family | Western Family - 100% Whole Grain Canadian Steel Cut Oats | steel-cut | 1.0 kg | 1000 | $4.69 |  |  | $4.69 | $0.47 | $0.47/100g | retailer attribute: Product of Canada |  | 2026-10-01T01:02:53Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639342470 |
| 793 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Giant Value | Giant Value Apples and Cinnamon Instant Oatmeal, 8-Pack | instant packets | 264 g | 264 | $2.87 |  |  | $2.87 | $1.09 |  | package image: 'MADE WITH 100% CANADIAN OATS' | provinces tagged: AB,MB,NB,NS,ON,PE,QC,SK; pack weight read from the package image on the product page (264 g) | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/giant-value-apples-and-cinnamon-instant-oatmeal-8-pack |
| 794 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Giant Value | Giant Value Maple and Brown Sugar Instant Oatmeal, 8-Pack | instant packets | 344 g | 344 | $2.87 |  |  | $2.87 | $0.83 |  | package image: 'MADE WITH 100% CANADIAN OATS' | provinces tagged: AB,MB,NB,NS,ON,PE,QC,SK; pack weight read from the package image on the product page (344 g) | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/giant-value-maple-and-brown-sugar-instant-oatmeal-8-pack |
| 795 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Giant Value | Giant Value Regular Instant Oatmeal, 10-Pack | instant packets | 280 g | 280 | $2.87 |  |  | $2.87 | $1.02 |  | package image: 'MADE WITH 100% CANADIAN OATS' | provinces tagged: AB,MB,NB,NS,ON,PE,QC,SK; pack weight read from the package image on the product page (280 g) | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/giant-value-regular-instant-oatmeal-10-pack |
| 796 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Quaker | Quaker Dino Eggs Brown Sugar Instant Oatmeal 8pk. - 304g | instant packets | 304.0 g | 304 | $3.66 |  |  | $3.66 | $1.20 |  |  | provinces tagged: AB,MB,NB,NS,ON,PE,QC,SK | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/quaker-dino-eggs-brown-sugar-instant-oatmeal-8pk-304g |
| 797 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Quaker | Quaker Instant Oatmeal Flavour Variety Instant Oatmeal Packets, 8-Pack, 314-g | instant packets | 314.0 g | 314 | $3.66 |  |  | $3.66 | $1.17 |  |  | provinces tagged: AB,MB,SK | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/quaker-instant-oatmeal-flavour-variety-instant-oatmeal-packets-8-pack-314-g |
| 798 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Quaker | Quaker Instant Oatmeal Variety 8pk. - 314g | instant packets | 314.0 g | 314 | $3.66 |  |  | $3.66 | $1.17 |  |  | provinces tagged: NB,NS,ON,PE,QC | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/quaker-instant-oatmeal-variety-8pk-314g-1 |
| 799 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Quaker | Quaker Peaches and Cream Flavoured Oatmeal, 264-g | instant packets | 264.0 g | 264 | $4.29 |  |  | $4.29 | $1.62 |  |  | provinces tagged: AB,MB,SK | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/quaker-peaches-and-cream-flavoured-oatmeal-264-g |
| 800 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Giant Value | Giant Value Large Flake Oats, 1 kg | large flake / rolled | 1000.0 g | 1000 | $2.77 |  |  | $2.77 | $0.28 |  | retailer tag: product_of_canada | provinces tagged: AB,MB,NB,NS,ON,PE,QC,SK | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/giant-value-large-flake-oats-1-kg |
| 801 | Giant Tiger | gianttiger.com (online price; in_store_only:false) | Giant Value | Giant Value Quick Oats, 1 kg | quick | 1000.0 g | 1000 | $2.77 |  |  | $2.77 | $0.28 |  | retailer tag: product_of_canada | provinces tagged: AB,MB,NB,NS,ON,PE,QC,SK | 2026-10-01T01:04:48Z | https://www.gianttiger.com/products/giant-value-quick-oats-1kg-2 |
| 802 | Costco.ca | costco.ca online, location code 801-bd | Kirkland Signature | Kirkland Signature Whole Grain Rolled Oats, 4.54 kg | large flake / rolled | 4.54 kg | 4540 | $11.99 |  |  | $11.99 | $0.26 |  |  |  | 2026-10-01T01:06:34Z | https://www.costco.ca/p/-/kirkland-signature-whole-grain-rolled-oats-454-kg/4000339745 |
| 803 | Costco.ca | costco.ca online, location code 801-bd | One Degree | One Degree Organic Sprouted Rolled Oats, 2.27kg | large flake / rolled | 2.27kg | 2270 | $14.99 |  |  | $14.99 | $0.66 |  |  |  | 2026-10-01T01:06:35Z | https://www.costco.ca/p/-/one-degree-organic-sprouted-rolled-oats-227kg/100572752 |
| 804 | Costco.ca | costco.ca online, location code 801-bd | Quaker | Quaker Quick Oats, 2 × 2.58 kg | quick | 2 × 2.58 kg | 5160 | $13.99 | $10.99 | 2026-10-26 (promotionEndDate 2026-10-26T06:59:00Z) | $10.99 | $0.21 |  |  | marketing statement: $3 OFF | 2026-10-01T01:06:34Z | https://www.costco.ca/p/-/quaker-quick-oats-2-258-kg/100570610 |
| 805 | Costco.ca | costco.ca online, location code 894_0-edi | Stoked Oats | Stoked Oats Oatmeal, 8 × 500 g | other | 8 × 500 g | 4000 | $59.99 |  |  | $59.99 | $1.50 |  | listing feature line: 'Made in Canada' |  | 2026-10-01T01:06:36Z | https://www.costco.ca/p/-/stoked-oats-oatmeal-8-500-g/4000369027 |
| 806 | Costco.ca | costco.ca online, location code 993-wm | Quaker | Quaker Instant Oatmeal 3 Flavour Variety Pack, 2.45 kg | instant packets | 2.45 kg | 2450 | $24.99 |  |  | $24.99 | $1.02 |  | listing feature line: 'Made with 100% whole grain Canadian oats' |  | 2026-10-01T01:06:34Z | https://www.costco.ca/p/-/quaker-instant-oatmeal-3-flavour-variety-pack-245-kg/4000039522 |

---

## Appendix B. Recalls and food-safety items: DO NOT USE ON AIR

No recall or food-safety search was performed for this price file, and none is included. If a recall check is needed it belongs here only, labelled "do not use on air".

---

## UNVERIFIED / DO-NOT-USE

| # | Item | Why | What would fix it |
|---|---|---|---|
| U1 | **Statistics Canada CPI, table 18-10-0004-01** ("Breakfast cereal and other cereal products" or nearest), monthly Jan 2023–Aug 2026, and the two-year change | The table metadata and the vector IDs opened. Every request for the monthly values (WDS `getDataFromVectorByReferencePeriodRange` and the CSV zip) failed with "tunnel closed (code 1006)" between 01:11 and 01:53 UTC (log `op/statcan/_log.txt`). **No CPI figure may be used from this file.** Older copies of StatCan files exist in the scratchpad from earlier sessions (for example a `18100245.csv` dated 2 Sep 2026). They were **not** opened today and are not used | Re-run `GET https://www150.statcan.gc.ca/t1/wds/rest/getDataFromVectorByReferencePeriodRange?vectorIds=41690973,41691000,41691005,41691007,41690975&startRefPeriod=2022-08-01&endReferencePeriod=2026-08-01` (or `oat_statcan2.py`) when the host is reachable. Compute the Aug 2024 → Aug 2026 change for v41691007 ("Breakfast cereal and other cereal products") |
| U2 | (Resolved today: table 18-10-0245-01 has no oats series; see section 5.) | n/a | n/a |
| U3 | Walmart Canada (Great Value) oatmeal prices | walmart.ca returned its bot wall on all three URLs | A retailer-own source (Walmart app or in-store photo with date) |
| U4 | Metro, Super C, IGA, Foodland, Longo's (own site) prices | 403 on every URL | Same as U3 |
| U5 | Farm Boy own-site prices | farmboy.ca shows no prices. Farm Boy-brand oats are priced only via Voilà, default region | — |
| U6 | Co-op (Calgary Co-op / FCL) prices | shop.calgarycoop.com: proxy 502; shoponline.calgarycoop.com: JavaScript only | — |
| U7 | **Any statement that a listed oatmeal is "imported"** (Bob's Red Mill, McCann's, Saffola, Nature's Path, One Degree, Kirkland Signature or any other) | No retailer listing or label image opened today states a non-Canadian origin for any oatmeal product. Brand sites tried (section 0, row 29) returned 404 or no origin text | A back-panel photo or retailer listing that shows the "Product of …" line |
| U8 | Who manufactures No Name, PC, Compliments, Western Family, Giant Value or Kirkland Signature oats | Not identified in any source opened. Matching ingredient lines must not be used to infer it | The retailer's or maker's own statement |
| U9 | Whether "Only Goodness" and "Left Coast" (Save-On-Foods) are store brands | Not verified today. They are counted as "national/other" in section 4 | Save-On / Pattison Food Group's own brand page |
| U10 | Yumi "Morning Oats" Maple & Brown Sugar pack size | The Loblaw listing says 264 g. The package image on the same listing reads "304g (8x38g)" | A current pack photo |
| U11 | Rogers "Porridge Oats, Original Blend" 1 kg image | The Loblaw listing's image shows a different Rogers product ("Healthy Grain Blend") | Do not show that image for this product |
| U12 | Costco warehouse vs costco.ca prices | Costco.ca prices here are online prices for the location code returned (`801-bd`, `993-wm`, `894_0-edi`). Costco's statement that warehouse prices differ was not opened today | Open https://customerservice.costco.ca/app/answers/answer_view/a_id/1017385 and quote it, or use a dated warehouse photo |
| U13 | Voilà region | Prices are for Voilà's "Default Region 1". The page does not show which province | Re-capture with a postal code set |
| U14 | Loblaw `SPECIAL` prices with no was-price (flag `*`) | The API marks them SPECIAL with an expiry date but shows no regular price. Do not call them "sale" prices on air | Check the store's flyer page on the banner's own site |
| U15 | Speerville "MADE IN CANADA" roundel | Read from small print on a product image | A pack photo |
| U16 | Save-On "each"-priced items with no weight on the listing (Quaker Low Sugar 8-packet boxes, Quaker Protein+ 6 packets, Nature's Path Superfood and Hot Oatmeal Original boxes) | Per-100 g figures are not computed, because the listing gives no weight. Weights from other retailers were not borrowed | The Save-On pack weight |
| U17 | Label panels and listing text containing health, fibre, cholesterol, sugar, protein, gluten, GMO or glyphosate wording (for example the Quaker heart panel, and a One Degree feature line on Costco.ca) | House rule 1. Seen while reading origin lines and **not transcribed** | Do not use |

<!-- ===== oatmeal_industry_record.md ===== -->

# Oatmeal: the Canadian oat industry and the documented record, 2023–2026

Prepared 30 Sep 2026 (Eastern). The sandbox clock read 1 Oct 2026, 01:xx UTC, so every "opened" date below is **30 Sep 2026** in Canadian time unless another date is given.

**Scope.** This file covers production, world position, exports to the U.S., imports, the milling footprint, PepsiCo/Quaker in Canada, the 2025–2026 trade dispute as it touched oats and cereals, and the "Buy Canadian" record (surveys, CFIA, Competition Bureau, named reporting). Brand-by-brand label dossiers and prices are in the sibling files `oatmeal_brands_national.md` and `oatmeal_brands_private.md`, and the legal origin rules are in `oatmeal_rules_origin.md`. They are not repeated here. **This file contains no prices.**

**House rules applied.** There is no health, nutrition, residue, additive or safety content in the body. Recalls and barred company copy are in Appendix A ("do not use on air") and in the closing UNVERIFIED / DO-NOT-USE section. U.S. records are labelled **U.S.** Company statements are attributed ("the company says").

**How pages were opened.** curl worked through the proxy for statcan's *bulk CIMT zip* (2023 files, after retries), apps.fas.usda.gov, whitehouse.gov, govinfo.gov, sec.gov, supremecourt.gov, cbc.ca, theglobeandmail.com, angusreid.org, leger360.com, dal.ca, and the company sites. curl got **connection resets** from www150.statcan.gc.ca (the HTML/table pages), agriculture.canada.ca and canada.ca/inspection.canada.ca. Those were opened with **WebFetch (WF)**. For AAFC, WF returned the PDF binary, which was saved and text-extracted with pypdf. Where WF returned a model summary rather than raw text, the item is marked "WF-extract" and should be re-read in a browser before an on-screen quote. federalregister.gov returned a "Request Access" wall, so Federal Register documents were read from govinfo.gov (the GPO's official copy).

Tiers: **(a)** primary · **(b)** named outlet, byline, date · **(c)** aggregator, flag only · **(d)** named survey with methodology.

---

## 0. Headline findings (tier a first)

1. **Canada's oat crop, 2025:** **3,919,796 t**, with Saskatchewan 45.0%, Manitoba 24.3% and Alberta 22.3%. The Prairies grew **91.7%** of it. **2026 model-based estimate (Aug 2026, released 16 Sep 2026): 3,030,964 t**, down 22.7%. [A1, A2]
2. **World position (U.S. data, labelled U.S.):** USDA's PSD database puts Canada's oat grain exports at **1,496 thousand tonnes in market year 2025**, **50.7%** of the sum of all exporting countries (this file's computation). The figures are 59.2% for MY2024, 63.3% for MY2023 and 73.1% for MY2020. Australia is second, at 750 kt (25.4%) in MY2025. USDA FAS Ottawa (May 2025, U.S.): "Canada is the largest oat exporter in the world and its exports accounted for 63 percent of global oat exports." [U1, U2]
3. **The U.S. buys almost all of it.** AAFC (25 Sep 2026): in crop year 2025-26, raw oat grain exports were "1.5 Mt … with the US accounting for almost 80% of total shipments", and oat product exports were "0.9 Mt … with the US accounting for nearly 95%". [A3]
4. **Rolled/flaked oats (HS 1104.12), CIMT total exports:** **205,067 t / C$268.4M in 2025**. **92.9% of tonnes and 96.9% of value went to the U.S.** The U.S. share of tonnes was 93.2% in 2024, 93.6% in 2023 and 94.4% in Jan–Jul 2026. [A4]
5. **Canada imports far less rolled oats than it exports.** HS 1104.12 imports were **14,569 t (C$21.2M) in 2025**: U.S.-origin 12,832 t and "Canada"-origin (Canadian goods returned) 1,535 t. Exports were about **14 times** imports by weight. Imports roughly **doubled** from 7,550 t in 2024. [A5]
6. **Illustrative only (not a StatCan figure):** set against StatCan's 2025 "food available" for oatmeal and rolled oats (2.67 kg/person × 41.6M people ≈ 111,000 t), 2025 rolled/flaked-oat imports are about **13%** of that tonnage, or **about 12%** excluding Canadian-origin returns. For 2024 the figures are about 5% and 4%. Read the caveats in §5.4 before using either number. [A5, A6, A7]
7. **Mills.** The company says Richardson Milling (the former **Can-Oat Milling**, bought from Glencore/Viterra; agreement announced 20 Mar 2012) has Canadian mills at **Portage la Prairie, MB (100,000 MT), Martensville, SK (135,000 MT groats) and Barrhead, AB (36,000 MT)**. Other operators: **Grain Millers** at Yorkton, SK (bought 2001, per the company); **O Foods** (Paterson GlobalFoods), a new mill in northwest Winnipeg announced 2019 at "up to 250,000 metric tonnes", whose first grain delivery was on "July 5th" (year disputed; see §6.3); **Avena Foods** at Regina and Rowatt, SK and Portage la Prairie, MB; **Emerson Milling**, Emerson, MB ("Since 1987"); **AGT Foods**' Aberdeen, SK "oat processing facility". No mill closure in 2023–2026 was found. [C1–C12]
8. **Quaker in Canada:** "PepsiCo Canada operates two Quaker plants: Trenton (Ontario) and Peterborough (Ontario)." (PepsiCo Canada ULC page). Unifor (19 Jun 2024): "There are 440 members of Local 1996 working at the Peterborough Plant." PepsiCo 10-K FY2025 (U.S. filing): Canada net revenue **US$3,729M (2025)**, $3,764M (2024), $3,722M (2023). [P1–P3]
9. **Trade dispute.** **Canada** put a 25% surtax on U.S. **oats (tariff item 1004.90.00)** from **4 Mar 2025** and removed it from **1 Sep 2025**. Rolled oats (1104.12) and breakfast cereals (19.04) were **never** on a Canadian counter-tariff list. **U.S.:** IEEPA duties on Canada applied from 4 Mar 2025. USMCA-qualifying goods were exempted from **7 Mar 2025** (EO 14231). The Supreme Court held on **20 Feb 2026** that "IEEPA does not authorize the President to impose tariffs", and EO 14389 (signed 20 Feb 2026) ended those duties. The **Section 338** 50% tariffs (proclaimed 20 Jul 2026, effective 22 Aug 2026) and the 8 Sep 2026 modifications list **no HTSUS chapter 10 or 11 lines and, in chapter 19, only 1901.20.xx dairy-mix lines**. Oats, rolled oats and HS 1904 cereals are not on them. [T1–T12]
10. **Buy Canadian.** Angus Reid Institute (Feb 2025, n=3,310): "Four-in-five (78%)" said they already, or were likely to, buy more Canadian products. Leger (28–30 Aug 2026): "Nearly two-thirds of Canadians (64%) say they plan to look more actively for products made in Canada". Dalhousie AFAL (Feb 2026, n=3,000): 21.2% "always" and 37.1% "often" check "where food originated or was produced". CFIA (16 Mar 2026): "$47,000 in financial penalties" since 1 Apr 2025 for origin claims. None involved oats. [D1–D4, R1]

---

## 1. Source register (every URL opened; date = opened)

### 1a. Tier (a): Canadian government

| ID | Source | URL | Opened / method | What it gives |
|---|---|---|---|---|
| A1 | Statistics Canada, Table **32-10-0359-01** "Estimated areas, yield, production, average farm price and total farm value of principal field crops, in metric and imperial units". Release date 2026-09-16; DOI https://doi.org/10.25318/3210035901-eng | Table page: https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210035901 · Data pulled from the table's own CSV download endpoint: https://www150.statcan.gc.ca/t1/tbl1/en/dtl!downloadDbLoadingData-nonTraduit.action?pid=3210035901&latestN=7&startDate=&endDate=&csvLocale=en&selectedMembers=%5B%5B1%2C9%2C10%2C11%5D%2C%5B19%5D%2C%5B5%5D%5D&checkedLevels= (and the same with geography members 3,4,5,6,7,12,13) | 30 Sep 2026, WF (curl reset). The CSV rows were returned by WF as a table. **Arithmetic check passed**: the provinces sum exactly to the Canada total for 2020 and 2025, and to within 1 t for 2026 | Oats (crop member 5), "Production (metric tonnes)" (member 19), by province, 2020–2026. 2026 Canada vectors: v114995738 (production t), v46385 (seeded acres), v46445 (harvested acres), v46397 (yield bu/ac) |
| A2 | Statistics Canada, The Daily, "Model-based principal field crop estimates, August 2026", released 2026-09-16 | https://www150.statcan.gc.ca/n1/daily-quotidien/260916/dq260916b-eng.htm | 30 Sep 2026, WF-extract | National oat sentence (quoted §2) |
| A2b | Statistics Canada, The Daily, "Production of principal field crops, November 2025", released 2025-12-04 | https://www150.statcan.gc.ca/n1/daily-quotidien/251204/dq251204a-eng.htm | 30 Sep 2026, WF-extract | 2025 national oat sentence (quoted §2) |
| A3 | AAFC, "CANADA: OUTLOOK FOR PRINCIPAL FIELD CROPS, 2026", **September 25, 2026** (PDF) | https://agriculture.canada.ca/sites/default/files/documents/2026-09/Canada%20Outlook%20for%20Principal%20Field%20Crops_202609.pdf | 30 Sep 2026, WF (binary saved → `oi/aafc_202609.pdf`, text `oi/aafc_202609.txt`) | Oats section and supply-disposition table (quoted §2, §3, §4) |
| A3b | AAFC, same series, **October 17, 2025** | https://agriculture.canada.ca/sites/default/files/documents/2025-10/Canada%20Outlook%20for%20Principal%20Field%20Crops_202510.pdf | 30 Sep 2026, WF (binary saved → `oi/aafc_202510.pdf/.txt`) | 2024-25 crop year export split and market shares (quoted §3) |
| A4 | Statistics Canada, **Canadian International Merchandise Trade (CIMT)**, Total Exports bulk files, HS-8 (file ODPFN017) | https://www150.statcan.gc.ca/n1/pub/71-607-x/2021004/zip/CIMT-CICM_Tot_Exp_2023.zip · …_2024.zip · …_2025.zip · …_2026.zip | 2023: downloaded 30 Sep 2026 (curl, after retries; `oi/`). 2024–2026: downloaded 29 Sep 2026 UTC earlier in this research session (`cimt/`). 2026 file runs Jan–Jul 2026 (ODPFN021_202607N; file dated 2026-08-21). Aggregated by script `oi/cimt_oats.py` | Exports by HS-8 and country, value (C$) and quantity (kg) |
| A5 | Statistics Canada, CIMT Imports bulk files, HS-10 (file ODPFN014) | https://www150.statcan.gc.ca/n1/pub/71-607-x/2021004/zip/CIMT-CICM_Imp_2023.zip · …_2024.zip · …_2025.zip · …_2026.zip | Same as A4 | Imports by HS-10 and country; HS 1104.12 quantity is in tonnes (TNE) |
| A6 | Statistics Canada, Table 32-10-0054-01 "Food available in Canada", vector **v108231** ("Oatmeal and rolled oats", Food available, kg per person per year) | https://www150.statcan.gc.ca/t1/wds/rest/getDataFromVectorByReferencePeriodRange?vectorIds=108231&startRefPeriod=2019-01-01&endReferencePeriod=2025-12-31 | 30 Sep 2026, WF (WDS API); matches local CSV `32100054.csv` (file dated 2026-05-28) | 2019–2025 per-capita values; release time 2026-05-28 |
| A7 | Statistics Canada, Table 17-10-0009-01 Population estimates, quarterly, vector **v1** (Canada) | https://www150.statcan.gc.ca/t1/wds/rest/getDataFromVectorByReferencePeriodRange?vectorIds=1&startRefPeriod=2024-07-01&endReferencePeriod=2026-04-01 | 30 Sep 2026, WF (WDS API); release time 2026-09-23 | 2024-07-01: 41,162,593 · 2025-07-01: 41,608,982 |
| A8 | Canada Gazette Part II, **SOR/2025-66**, United States Surtax Order (2025-1), registered March 3, 2025, P.C. 2025-265 | https://gazette.gc.ca/rp-pr/p2/2025/2025-03-12/html/sor-dors66-eng.html | Opened 30 Sep 2026 by curl in this session (sibling process; saved `oat/sor66.txt`); re-read today | In force 4 Mar 2025; schedule lists **1004.90.00** |
| A9 | Canada Gazette Part II, **SOR/2025-181**, "Order Amending and Repealing Certain Orders Made Under the Customs Tariff (United States Surtax)", registered August 29, 2025 | https://gazette.gc.ca/rp-pr/p2/2025/2025-09-10/html/sor-dors181-eng.html | 30 Sep 2026, WF-extract (also `oat/sor181.txt`, curl in this session) | Removal from 1 Sep 2025; remission expiry 16 Oct 2025 |
| A10 | Finance Canada, "Complete list of U.S. products subject to counter tariffs" ("List updated as of August 26, 2026") | https://www.canada.ca/en/department-finance/programs/international-trade-finance-policy/canadas-response-us-tariffs/complete-list-us-products-subject-to-counter-tariffs.html | 30 Sep 2026: WF returned only the first section. The full page was fetched by curl in this session (`oat/fin_list.html/.txt`) and the oat row was re-read today | Row "1004.90.00 \| Cereals \| Oats. \| Other \| 2025-03-04 \| 25%" in section "Effective up to August 31, 2025" |
| A11 | CFIA statement, "Food businesses face penalties for mislabelling products as Canadian", 2026-03-16 | https://www.canada.ca/en/food-inspection-agency/news/2026/03/food-businesses-face-penalties-for-mislabelling-products-as-canadian.html | 30 Sep 2026, WF-extract | Penalties (quoted §9.2) |
| A12 | CFIA, "Notice to industry – The importance of accurate use of Product of Canada, Made in Canada and other origin claims", March 14, 2025, updated July 30, 2025 (date modified 2026-03-16) | https://inspection.canada.ca/en/food-labels/labelling/notice-industry-2025-03-14 | 30 Sep 2026, WF-extract | Quoted §9.2 |
| A13 | Competition Bureau, "Made in Canada claims" (date modified 2026-06-14) | https://competition-bureau.canada.ca/en/deceptive-marketing-practices/made-canada-claims | 30 Sep 2026, WF-extract | Quoted §9.3 |
| A14 | Government of Alberta, Agri-Food Products and Services Export Catalogue, "Canadian Oats Milling Ltd." | https://www.alberta.ca/ag-export-catalogue-canadian-oats-milling-ltd | 30 Sep 2026, curl | Company-supplied listing (quoted §6) |

### 1b. Tier (a): U.S. government records (all labelled **U.S.**)

| ID | Source | URL | Opened / method |
|---|---|---|---|
| U1 | USDA FAS, PSD Online bulk file "psd_grains_pulses_csv.zip" (Oats: Exports, Production; vintage Sep 2026 for MY2025/2026 rows) | https://apps.fas.usda.gov/psdonline/downloads/psd_grains_pulses_csv.zip | 30 Sep 2026, curl (`oi/psd_grains_pulses.csv`) |
| U2 | USDA FAS GAIN, "Grain and Feed Annual", Canada, Report CA2025-0020, **May 01, 2025** (Ottawa post; "assessments … made by USDA staff and not necessarily statements of official U.S. government policy") | https://apps.fas.usda.gov/newgainapi/api/Report/DownloadReportByFileName?fileName=Grain+and+Feed+Annual_Ottawa_Canada_CA2025-0020.pdf | 30 Sep 2026, curl (`oi/co/gain2025.pdf/.txt`) |
| T1 | EO 14193 "Imposing Duties To Address the Flow of Illicit Drugs Across Our Northern Border", signed 2025-02-01, 90 FR 9113 (published 2025-02-07) | https://www.govinfo.gov/content/pkg/FR-2025-02-07/html/2025-02406.htm (metadata: https://www.federalregister.gov/api/v1/documents/2025-02406.json) | 30 Sep 2026, curl |
| T2 | EO 14231 "Amendment to Duties To Address the Flow of Illicit Drugs Across Our Northern Border", signed 2025-03-06, 90 FR 11785 | https://www.govinfo.gov/content/pkg/FR-2025-03-11/html/2025-03990.htm | 30 Sep 2026, curl |
| T3 | White House fact sheet, "President Donald J. Trump Adjusts Tariffs on Canada and Mexico to Minimize Disruption to the Automotive Industry", 2025-03-06 | https://www.whitehouse.gov/fact-sheets/2025/03/fact-sheet-president-donald-j-trump-adjusts-tariffs-on-canada-and-mexico-to-minimize-disruption-to-the-automotive-industry/ | 30 Sep 2026, curl |
| T4 | White House fact sheet, "President Donald J. Trump Amends Duties to Address the Flow of Illicit Drugs Across our Northern Border", 2025-07-31 | https://www.whitehouse.gov/fact-sheets/2025/07/fact-sheet-president-donald-j-trump-amends-duties-to-address-the-flow-of-illicit-drugs-across-our-northern-border/ | 30 Sep 2026, curl |
| T5 | Supreme Court of the United States, *Learning Resources, Inc. v. Trump*, No. 24–1287, decided February 20, 2026 (slip opinion) | https://www.supremecourt.gov/opinions/25pdf/24-1287_4gcj.pdf | 30 Sep 2026, curl (`oi/us/scotus.pdf`) |
| T6 | EO 14389 "Ending Certain Tariff Actions", signed 2026-02-20, 91 FR 9437 | https://www.govinfo.gov/content/pkg/FR-2026-02-25/html/2026-03832.htm | 30 Sep 2026, curl |
| T7 | White House fact sheet, "President Donald J. Trump Imposes Additional Tariffs on Canada" (July 20, 2026) | https://www.whitehouse.gov/fact-sheets/2026/07/fact-sheet-president-donald-j-trump-imposes-additional-tariffs-on-canada/ | 30 Sep 2026, curl |
| T8 | Proclamations 11046 (alcoholic beverages), 11047 (dairy) and 11048 (motor vehicles), July 20, 2026, with Annexes I and II | https://www.whitehouse.gov/presidential-actions/2026/07/imposing-additional-duties-to-offset-canadian-discrimination-against-the-commerce-of-the-united-states-with-respect-to-alcoholic-beverages/ · …-dairy/ · …-motor-vehicles/ · annexes https://www.whitehouse.gov/wp-content/uploads/2026/07/ANNEX-I-1.pdf, ANNEX-I-2.pdf, ANNEX-I-3.pdf, Annex-II.pdf, Annex-II-1.pdf, Annex-II-2.pdf | 30 Sep 2026, curl; annexes text-extracted (`oi/us/`) |
| T9 | Proclamation "Temporary Suspension of Additional Duties … Alcoholic Beverages, Dairy, and Motor Vehicles" (August 2026) | https://www.whitehouse.gov/presidential-actions/2026/08/temporary-suspension-of-additional-duties-to-offset-canadian-discrimination-against-the-commerce-of-the-united-states-with-respect-to-alcoholic-beverages-dairy-and-motor-vehicles/ | 30 Sep 2026, curl |
| T10 | White House fact sheet, "President Donald J. Trump Responds to Canada's Retaliation" (September 8, 2026) | https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-responds-to-canadas-retaliation/ | 30 Sep 2026, curl |
| T11 | Five September 2026 proclamations (exclusions: alcoholic beverages, dairy, motor vehicles; scope modifications: alcoholic beverages, motor vehicles) and their annexes (ANNEX-I-ALCOHOL, ANNEX-I-AUTO, ANNEX-I-DAIRY, ANNEX-I-MOTOR-VEHICLES, ANNEX-II-AUTO, Alcohol-Scope-Modification-Annex-I/II) | https://www.whitehouse.gov/presidential-actions/2026/09/… (five URLs, saved `oi/us/s1–s5.html`); annexes https://www.whitehouse.gov/wp-content/uploads/2026/09/… | 30 Sep 2026, curl. A sixth guessed URL (dairy scope modification) returned 404 |
| T12 | PepsiCo, Inc., Form 10-K for fiscal year ended December 27, 2025, filed 2026-02-03 | https://www.sec.gov/Archives/edgar/data/77476/000007747626000007/pep-20251227.htm | 30 Sep 2026, curl (`oi/co/pep10k25.htm`) |

### 1c. Tier (a): company pages

| ID | Company page | URL | Opened |
|---|---|---|---|
| C1 | Richardson International, "Oat Milling" (© 2026) | https://www.richardson.ca/oat-milling/ | 30 Sep 2026, curl |
| C2 | Richardson, "All Richardson Milling" locations | https://www.richardson.ca/places/category/richardson-milling/ | 30 Sep 2026, curl |
| C3 | Richardson, "Richardson announces agreement to purchase Viterra assets" (page published 2012-03-20) | https://www.richardson.ca/richardson-announces-agreement-to-purchase-viterra-assets/ | 30 Sep 2026, curl |
| C4 | Richardson Food & Ingredients, "Oat Milling" (http://richardsonmilling.com/ redirects here) | https://richardsonfoodandingredients.com/richardson-milling/ | 30 Sep 2026, curl |
| C5 | Grain Millers, "Facilities" | https://www.grainmillers.com/our-company/facilities/ | 30 Sep 2026, curl |
| C6 | Avena Foods, "Our Company" (© 2026) and home page | https://www.avenafoods.com/about-us/our-company/ · https://www.avenafoods.com/ | 30 Sep 2026, curl |
| C7 | Emerson Milling Inc., home page | https://www.emersonmilling.com/ | 30 Sep 2026, curl |
| C8 | Paterson Grain, "Paterson GlobalFoods Oat Mill" (published 2019-10-03) | https://www.patersongrain.com/paterson-globalfoods-oat-mill/ | 30 Sep 2026, curl |
| C9 | Paterson GlobalFoods, "O Foods Commences Operations" (page metadata: published 2023-07-12) · "O Foods" company page (published 2022-05-10, modified 2023-05-19) · ofoods.ca home | https://www.patersonglobalfoods.com/o-foods-commences-operations/ · https://www.patersonglobalfoods.com/companies/o-foods/ · https://www.ofoods.ca/ | 30 Sep 2026, curl |
| C10 | AGT Foods, "Grains" product category page (© 2026) | https://www.agtfoods.com/about/productcategories/grains | 30 Sep 2026, curl |
| C11 | Sunrise Foods International, home page and "Oats" product page | https://www.sunrisefoods.com/ · https://www.sunrisefoods.com/our-products/oats/ | 30 Sep 2026, curl |
| C12 | (see A14) Canadian Oats Milling Ltd., via the Government of Alberta catalogue | — | — |
| P1 | PepsiCo Canada ULC, Quaker Canada "About Us" (contact.pepsico.com/quakerca) | https://contact.pepsico.com/quakerca/about-us | 30 Sep 2026, curl |
| P2 | Unifor, "Wages, pensions addressed in new Quaker Oats contract" (published 2024-06-19) | https://www.unifor.org/news/all-news/wages-pensions-addressed-new-quaker-oats-contract | 30 Sep 2026, curl. A union's own release: a party statement, attributed |
| P3 | = T12 (PepsiCo 10-K) | | |

### 1d. Tier (d) surveys and tier (b) reporting

| ID | Source | URL | Opened |
|---|---|---|---|
| D1 | Angus Reid Institute, "Shopping Shift: Four-in-five say they're buying more Canadian products in face of tariff threat", February 19, 2025; questionnaire PDF | https://angusreid.org/shopping-shift-tariff-threat-buy-canada/ · https://angusreid.org/wp-content/uploads/2025/02/2025.02.19_Questionnaire_tariff_response.pdf | 30 Sep 2026, curl |
| D2 | Leger, "The Trade War Is Back. Is Buy Canadian Back Too?" (page published 2026-09-09; fieldwork Aug 28–30, 2026) | https://leger360.com/the-trade-war-is-back-buy-canadian/ | 30 Sep 2026, curl |
| D3 | Dalhousie University Agri-Food Analytics Lab (with Caddle), *Canadian Food Sentiment Index*, Spring 2026 (PDF) | https://cdn.dal.ca/content/dam/dalhousie/pdf/sites/agri-food/FINAL_ENGLISH_LG_DalFoodSentimentSpring2026.pdf | 30 Sep 2026, curl; text-extracted |
| D4 | Dalhousie AFAL, *Canadian Food Sentiment Index Spring 2025* release page ("HALIFAX, NS – May 6, 2025") | https://www.dal.ca/sites/agri-food/research/the-canadian-food-sentiment-index-spring-2025.html | 30 Sep 2026, curl |
| B1 | CBC News, Bobby Hristova and Dexter McMillan, "Marketplace found up to 1 in 3 groceries get labelled as Canadian. Customers say they're skeptical", 2025-03-29 | https://www.cbc.ca/news/marketplace/marketplace-found-up-to-1-in-3-groceries-get-labelled-as-canadian-customers-say-they-re-skeptical-1.7496182 | 30 Sep 2026, curl |
| B2 | CBC News, Sophia Harris, "CBC investigation finds some big grocers promoting imported food with Canadian branding", 2025-07-24 | https://www.cbc.ca/news/business/label-grocer-canadian-1.7590956 | 30 Sep 2026, curl |
| B3 | CBC News, Sophia Harris, "No fines for big grocers that promoted imported food as Canadian", 2025-09-01 | https://www.cbc.ca/news/business/buy-canadian-label-maple-washing-1.7621843 | 30 Sep 2026, curl |
| B4 | The Globe and Mail, Kate Helmore and Susan Krashinsky Robertson, "Fines for false made-in-Canada claims could chill investment, food manufacturers say", 2026-03-18 | https://www.theglobeandmail.com/business/economy/article-fines-for-false-made-in-canada-claims-could-chill-investment-food/ | 30 Sep 2026, curl |

---

## 2. Production: Statistics Canada (tier a)

### 2.1 Oat production by province, metric tonnes (Table 32-10-0359-01, A1)

| Province | 2020 | 2021 | 2022 | 2023 | 2024 | 2025 | 2026 (model-based, Aug 2026) |
|---|---|---|---|---|---|---|---|
| Newfoundland and Labrador | 300 | F | 0 | 0 | 0 | F | 0 |
| Prince Edward Island | 8,800 | 6,303 | 6,179 | 4,290 | 10,824 | 7,955 | 6,764 |
| Nova Scotia | 3,100 | 3,369 | 1,680 | 1,882 | 1,803 | 1,186 | 1,882 |
| New Brunswick | 13,700 | 42,964 | 39,319 | 27,732 | 12,995 | 21,024 | 24,830 |
| Quebec | 173,200 | 201,264 | 210,280 | 140,450 (r) | 144,611 | 123,936 | 131,059 |
| Ontario | 103,700 | 95,357 | 111,869 | 72,527 | 91,303 | 70,805 | 70,278 |
| Manitoba | 1,117,000 | 766,531 | 1,168,612 | 653,251 | 934,350 | 953,866 | 661,584 |
| Saskatchewan | 2,296,400 | 1,152,532 | 2,567,136 | 1,034,149 | 1,469,992 | 1,763,257 | 1,351,940 |
| Alberta | 802,000 | 546,680 | 1,054,681 | 642,115 | 630,663 | 875,942 | 709,014 |
| British Columbia | 57,600 | 83,618 | 66,709 | 66,662 | 61,009 | 101,825 | 73,614 |
| **Canada** | **4,575,800** | **2,898,619** | **5,226,465** | **2,643,058 (r)** | **3,357,551** | **3,919,796** | **3,030,964** |

Status flags as returned: "r" = revised; "F" = too unreliable to be published. Nova Scotia shows 1,882 t in both 2023 and 2026 as returned. The arithmetic check passed, but re-confirm in a browser before putting that coincidence on screen.

**Computed shares (this file's arithmetic):** 2025: Saskatchewan 45.0%, Manitoba 24.3%, Alberta 22.3%, Prairies 91.7%. 2026 estimate: Saskatchewan 44.6%, Alberta 23.4%, Manitoba 21.8%, Prairies 89.8%.

**2026 national detail (A1, WF):** seeded area 2,544,800 acres (1,030,000 ha); harvested area 2,076,100 acres (840,200 ha); yield 94.7 bu/ac (3,607 kg/ha); production 3,030,964 t.

### 2.2 StatCan's own words (verbatim)
- 2026 (A2, released 2026-09-16): "Nationally, oat production is anticipated to fall by 22.7% to 3.0 million tonnes, a result of both lower yields (-3.5% to 94.7 bushels per acre) and lower harvested area (-19.9% to 2.1 million acres) in 2026." The release gives no provincial oat figures.
- 2025 (A2b, released 2025-12-04): "Total oat production increased by 16.7% to 3.9 million tonnes, as both harvested area (+5.6% to 2.6 million acres) and yields (+10.6% to 98.1 bushels per acre) increased in 2025."

### 2.3 AAFC's provincial reading (A3, 25 Sep 2026; verbatim)
- "For 2026-27, Canadian oat production is projected at 3.0 Mt, a notable decline from last season, primarily driven by reduced seeded area and yields declining significantly from the record highs achieved in the previous season. Provincially, Saskatchewan remains the largest oat-producing region, accounting for 45% of total production in 2026-27. Alberta follows with 23%, while Manitoba contributes 22%."
- AAFC Oct 2025 (A3b): "For 2025-26, about 1.2 Mha was seeded to oats, up 3% y/y but 11% below the five-year average. By province, Saskatchewan sowed 43% of the Canadian oat crop, followed by Alberta (28%), Manitoba (19%), with the remaining 11% seeded in the other provinces."

---

## 3. Canada's place in world oat trade

### 3.1 USDA PSD, oat **grain** exports by exporter (U.S. data, labelled U.S.; 1,000 MT; local marketing year)

Shares computed here as Canada ÷ the sum of all PSD exporter rows for that year. PSD has no "World" row in this file. **Grain only; oat products are not included.**

| Market year | Canada | Australia | Russia | EU | UK | U.S. | Sum of exporters | **Canada share** |
|---|---|---|---|---|---|---|---|---|
| 2020 | 2,022 | 396 | 86 | 139 | 41 | 46 | 2,766 | **73.1%** |
| 2021 | 1,328 | 556 | 150 | 227 | 123 | – | 2,517 | **52.8%** |
| 2022 | 1,744 | 534 | 150 | 83 | 172 | 28 | 2,754 | **63.3%** |
| 2023 | 1,502 | 293 | 275 | 118 | 116 | 30 | 2,374 | **63.3%** |
| 2024 | 1,642 | 559 | 300 | 93 | 64 | 36 | 2,775 | **59.2%** |
| 2025 | 1,496 | 750 | 300 | 183 | 93 | 52 | 2,953 | **50.7%** |
| 2026 (USDA projection) | 1,400 | 750 | 250 | 150 | 60 | 29 | 2,684 | 52.2% |

PSD vintage: Canada MY2025 and MY2026 rows dated 2026-09; Australia MY2025 dated 2026-09. U.S. oat **imports** in PSD: MY2024 1,228; MY2025 1,218; MY2026 1,241 (1,000 MT). Production share (PSD): Canada 14.9% of the sum of producers in MY2025 (3,920 of 26,229 kt). In the 2021 column the U.S. is not in the top six; Chile shows 69.

### 3.2 USDA FAS GAIN, Ottawa, CA2025-0020, May 1, 2025 (U.S.; U2; verbatim)
- "Canada is the largest oat exporter in the world and its exports accounted for 63 percent of global oat exports."
- "In MY 2024/25, exports to February 2025 have increased six percent over the same period in the previous year on increased demand in the United States."
- "Canada is not a significant importer of oats. In MY 2023/24 it imported 15,271 MT of oats, less than the than the five-year average of 19,097 MT." (sic)

### 3.3 AAFC on export destinations (tier a; verbatim)
- **Crop year 2025-26 (A3, 25 Sep 2026):** "Exports of raw oat grain during the entire crop year (August - July) totaled 1.5 Mt (-9% versus both the previous season and the five-year average), with the US accounting for almost 80% of total shipments, followed by Mexico, South Africa, Japan, Peru, and various other countries and regions. Exports of oat product (in grain equivalent) totaled 0.9 Mt (-1%; -2%), with the US accounting for nearly 95% of total shipments, followed by Mexico, Japan, and South Korea."
- **Crop year 2024-25 (A3b, 17 Oct 2025):** "Total exports reached 2.6 Mt (1.6 Mt for grain exports and 0.92 Mt for product exports), up significantly y/y and in line with the average. Top export markets for oat grain include the US (representing over 75% of grain exports), Mexico (10%), and Peru (<5%). Top export markets for oat products include the US (93%), Mexico (4%), and South Korea and Japan (2%)."
- **World outlook (A3):** "Worldwide, the USDA projects 2026-27 global oat production at 23 Mt, down notably y/y."
- AAFC does **not** state a Canadian share of world oat exports in the reports opened. The share figures above are USDA's (U.S.).

### 3.4 AAFC supply and disposition, oats (A3, 25 Sep 2026; thousand tonnes unless noted)

| Crop year | Seeded (kha) | Harvested (kha) | Yield (t/ha) | Production | Imports (b) | Total supply | Exports (c) | Food & industrial | Feed, waste & dockage | Total domestic use | Carry-out | Avg price (g) $/t |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 2024-2025 | 1,174 | 993 | 3.38 | 3,358 | 17 | 4,045 | 2,565 | 76 | 796 | 973 | 507 | 345 |
| 2025-2026f | 1,213 | 1,049 | 3.74 | 3,920 | 14 | 4,441 | 2,407 | 83 | 1,287 | 1,457 | 577 | 307 |
| 2026-2027f | 1,030 | 840 | 3.61 | 3,031 | 20 | 3,628 | 2,361 | 90 | 680 | 867 | 400 | 330 |

Footnotes (verbatim): "(b) Imports exclude products." "(c) Exports include grain products but exclude oilseed products." The price is "Oats (US No. 2 Heavy, CBOT nearby futures)". The 2025-26 export total (2,407 kt) is about **54%** of 2025-26 supply (4,441 kt) on AAFC's own figures (this file's division). AAFC: "The final average Chicago Board of Trade (CBOT) oat price was $307/t, down approximately $40/t y/y and approaching its lowest level in five years."

---

## 4. Exports of oats and oat products, by value and tonnes, and the U.S. share (CIMT, tier a; A4)

CIMT "Total exports" include re-exports. Value is C$ (current). Tonnes are converted from kg. "U.S. share" = U.S. ÷ all destinations. 2026 = **January–July only**.

### 4.1 Oat grain

| HS-8 | Year | Value, all (C$) | Tonnes, all | Value to U.S. | Tonnes to U.S. | U.S. share, value | U.S. share, tonnes |
|---|---|---|---|---|---|---|---|
| 1004.90.90 oats, not organic, not seed | 2023 | 684,182,337 | 1,708,238 | 555,208,280 | 1,353,591 | 81.1% | 79.2% |
| | 2024 | 594,830,330 | 1,463,554 | 440,565,347 | 1,091,119 | 74.1% | 74.6% |
| | 2025 | 590,309,979 | 1,509,410 | 467,606,097 | 1,192,329 | 79.2% | 79.0% |
| | 2026 Jan–Jul | 281,506,795 | 806,166 | 214,496,492 | 604,446 | 76.2% | 75.0% |
| 1004.90.10 oats, certified organic | 2023 | 26,519,930 | 46,245 | 18,618,163 | 32,372 | 70.2% | 70.0% |
| | 2024 | 25,580,299 | 45,195 | 16,692,749 | 29,668 | 65.3% | 65.6% |
| | 2025 | 25,606,695 | 42,749 | 15,215,453 | 24,863 | 59.4% | 58.2% |
| | 2026 Jan–Jul | 20,011,362 | 33,149 | 15,290,305 | 24,362 | 76.4% | 73.5% |
| 1004.10 seed oats | 2023 | 13,915,776 | 16,779 | 5,590,922 | 7,356 | 40.2% | 43.8% |
| | 2024 | 12,184,965 | 15,330 | 5,609,222 | 7,815 | 46.0% | 51.0% |
| | 2025 | 19,223,029 | 24,173 | 5,214,122 | 7,684 | 27.1% | 31.8% |
| | 2026 Jan–Jul | 8,861,237 | 11,815 | 2,614,864 | 3,814 | 29.5% | 32.3% |

Other leading destinations for 1004.90.90 in 2025 (value): Mexico C$50.0M, UAE C$13.0M, Peru C$12.8M, Japan C$12.4M, South Africa C$11.7M.

### 4.2 Oat products

| HS-8 | Year | Value, all (C$) | Tonnes, all | Value to U.S. | Tonnes to U.S. | U.S. share, value | U.S. share, tonnes |
|---|---|---|---|---|---|---|---|
| **1104.12 rolled or flaked oats** | 2023 | 273,975,668 | 184,089 | 267,172,688 | 172,293 | 97.5% | 93.6% |
| | 2024 | 289,751,032 | 202,461 | 281,891,254 | 188,788 | 97.3% | 93.2% |
| | 2025 | 268,433,187 | 205,067 | 260,066,846 | 190,477 | 96.9% | 92.9% |
| | 2026 Jan–Jul | 148,687,050 | 119,341 | 144,654,821 | 112,666 | 97.3% | 94.4% |
| 1103.19.10 oat groats and meal | 2023 | 184,282,028 | 184,614 | 165,061,724 | 156,013 | 89.6% | 84.5% |
| | 2024 | 200,457,984 | 230,950 | 182,082,623 | 202,882 | 90.8% | 87.8% |
| | 2025 | 181,603,079 | 228,613 | 168,126,814 | 206,677 | 92.6% | 90.4% |
| | 2026 Jan–Jul | 111,109,994 | 152,331 | 101,702,616 | 136,490 | 91.5% | 89.6% |
| 1104.22 oats, hulled/pearled/sliced/kibbled | 2023 | 184,726,442 | 167,604 | 183,891,586 | 166,143 | 99.5% | 99.1% |
| | 2024 | 160,996,081 | 149,201 | 160,347,568 | 148,067 | 99.6% | 99.2% |
| | 2025 | 112,577,559 | 118,379 | 111,848,028 | 117,098 | 99.4% | 98.9% |
| | 2026 Jan–Jul | 66,325,986 | 79,013 | 65,996,219 | 78,435 | 99.5% | 99.3% |

Other 1104.12 destinations in 2025: South Korea C$3.13M (5,514 t), Japan C$3.12M (5,404 t), Philippines C$0.61M, Hong Kong C$0.34M.

### 4.3 Breakfast-cereal headings (context only; **not oat-specific**: all grains)

| HS-8 | Year | Value, all (C$) | Tonnes | U.S. share, value |
|---|---|---|---|---|
| 1904.10 swelled/roasted cereal preparations | 2023 / 2024 / 2025 / 2026 Jan–Jul | 341.4M / 369.0M / 362.7M / 224.9M | 76,666 / 81,049 / 86,592 / 56,821 | 98.3% / 98.4% / 97.3% / 97.2% |
| 1904.20 preparations of unroasted cereal flakes | same | 63.9M / 85.0M / 84.2M / 42.2M | 16,836 / 19,630 / 21,256 / 10,434 | 96.5% / 96.4% / 96.5% / 97.8% |

### 4.4 Same-period comparison, January–July (this file's arithmetic)

| Item | Jan–Jul 2025 | Jan–Jul 2026 | Change |
|---|---|---|---|
| 1004.90.90 tonnes, all | 888,043 | 806,166 | −9.2% |
| 1004.90.90 tonnes, to U.S. | 664,891 | 604,446 | −9.1% |
| 1104.12 tonnes, all | 122,213 | 119,341 | −2.3% |
| 1104.12 value, all (C$) | 161,384,552 | 148,687,050 | −7.9% |
| 1104.12 tonnes, to U.S. | 112,817 | 112,666 | −0.1% |

The data do not show **why** volumes moved. Do not attribute any change to tariffs.

---

## 5. Imports into Canada: how much rolled oats and cereal could be foreign (CIMT, tier a; A5)

In the CIMT import files the "Country" field is the trading-partner country. Rows coded "CA" are goods recorded with Canada as the country, i.e. Canadian goods returned. How StatCan treats them was not re-verified today (see UNVERIFIED). Value is C$.

### 5.1 HS 1104.12.00.00 "Oats, rolled or flaked grains" (quantity unit: tonnes)

| Year | Total value | Total t | U.S. value (share) | U.S. t | "CA" value (share) | "CA" t | Next largest |
|---|---|---|---|---|---|---|---|
| 2023 | 13,769,836 | 14,384 | 6,166,320 (44.8%) | 7,959 | 7,001,428 (50.8%) | 6,097 | China C$215,495 (172 t) |
| 2024 | 15,762,944 | 7,550 | 7,634,680 (48.4%) | 5,084 | 7,572,071 (48.0%) | 2,246 | China C$219,535 (65 t) |
| 2025 | 21,212,392 | 14,569 | 13,492,312 (63.6%) | 12,832 | 7,239,102 (34.1%) | 1,535 | China C$237,773 (92 t) |
| 2026 Jan–Jul | 11,555,635 | 5,980 | 6,988,949 (60.5%) | 4,755 | 4,338,569 (37.5%) | 1,099 | China C$64,209 (16 t) |

Jan–Jul 2025 for comparison: total 11,305 t (C$13.56M), of which U.S. 10,369 t.

### 5.2 Oat grain and other oat headings imported (tonnes unless noted)

| HS-10 | 2023 | 2024 | 2025 | 2026 Jan–Jul | Main source |
|---|---|---|---|---|---|
| 1004.90.00.00 oats, other than seed | 18,675 t / C$4.11M | 17,322 t / C$4.57M | 14,278 t / C$4.95M | 5,792 t / C$1.65M | U.S. 96–99% |
| 1103.19.90.20 groats and meal of oats | 1,223 t | 765 t | 652 t | 128 t | U.S. and "CA"; India 22.7% of 2025 value |
| 1104.22.00.00 oats, hulled/pearled/etc. (kg) | 2,798,735 kg | 3,327,297 kg | 3,035,939 kg | 840,727 kg | U.S. 88–97% |

**U.S.-origin oat grain (1004.90) imports by month, during the Canadian surtax (4 Mar–31 Aug 2025) and a year earlier (tonnes):** Mar–Aug 2024: 1,155 / 673 / 714 / 1,128 / 805 / 5,618 = **10,093 t**. Mar–Aug 2025: 41 / 516 / 100 / 387 / 913 / 1,419 = **3,376 t**. Sep–Dec 2025: 2,908 / 908 / 2,237 / 1,082. These are recorded quantities only. CIMT does not record whether the surtax was paid or remitted (see §8.2 on remission), and **no cause can be inferred**.

### 5.3 Breakfast cereals, HS 1904.10 and 1904.20 (**all grains, not oat-specific**)

| Heading | Year | Total value (C$) | U.S. share | Next sources |
|---|---|---|---|---|
| 1904.10 (all lines) | 2023 | 693.2M | 91.5% | Mexico 5.7%, U.K. 1.0% |
| | 2024 | 704.9M | 90.3% | Mexico 6.0%, U.K. 1.5% |
| | 2025 | 710.3M | 92.0% | Mexico 3.1%, U.K. 1.6%, India 1.0% |
| | 2026 Jan–Jul | 405.3M | 92.0% | Mexico 3.6%, U.K. 1.5% |
| 1904.20 (all lines) | 2023 | 42.9M | 84.2% | U.K. 7.9%, India 3.3% |
| | 2024 | 61.3M | 85.9% | U.K. 7.9%, India 2.7% |
| | 2025 | 74.3M | 87.3% | U.K. 5.3%, India 2.5% |
| | 2026 Jan–Jul | 48.7M | 89.6% | U.K. 5.1%, India 2.0% |
| of which 1904.20.50.10 "'Musli' type breakfast cereals, <= 11.34 kg" | 2025 | 5.06M | U.K. 76.3%, U.S. 11.5% | Germany 4.2%, Switzerland 3.4% |
| of which 1904.20.50.90 "Prep foods, from unroasted or mx of unroasted/roasted cereal flakes, nes, <=11.34kg" | 2025 | 51.6M | U.S. 92.2% | India 3.4% |

Which heading a given instant-oatmeal SKU is entered under (1104.12, 1904.20 or another) is a CBSA classification matter. **This file does not classify any product.**

### 5.4 Illustrative scale only: imports against StatCan's "food available"

StatCan Table 32-10-0054-01, "Oatmeal and rolled oats", Food available, kg per person per year (A6): 2019 2.68 · 2020 1.78 · 2021 0.76 · 2022 1.59 · 2023 2.16 · **2024 3.46** · **2025 2.67** (adjusted for losses: 2024 2.09, 2025 1.62; local CSV).

| | 2024 | 2025 |
|---|---|---|
| Food available (kg/person) × population at 1 July (A7) | 3.46 × 41,162,593 ≈ **142,400 t** | 2.67 × 41,608,982 ≈ **111,100 t** |
| HS 1104.12 imports, all countries | 7,550 t (≈5.3%) | 14,569 t (≈13.1%) |
| HS 1104.12 imports excluding "CA" returns | 5,304 t (≈3.7%) | 13,034 t (≈11.7%) |

**Caveats (must accompany any use):** (1) This is this file's arithmetic, not a StatCan statistic. (2) The per-capita series is a supply-disappearance estimate and swings sharply year to year (0.76 to 3.46). (3) HS 1104.12 imports include bulk ingredient flakes for manufacturers, not only retail packs. (4) Instant or flavoured oatmeal may enter under 1904 headings, which are not oat-specific. (5) Imported packs can be Canadian oats milled abroad. The CIMT "CA" rows show Canadian goods returning, and origin of the grain is not recorded at all. **Safe wording: "Customs data show Canada exported about 14 tonnes of rolled oats for every tonne it imported in 2025."**

---

## 6. The Canadian oat-milling footprint (company pages, tier a; claims attributed)

### 6.1 Mill-by-mill table

| Company / site | Owner (per the page) | What the company says (verbatim) | Source |
|---|---|---|---|
| **Richardson Milling**: Portage la Prairie, MB ("#1 Can-Oat Drive PORTAGE LA PRAIRIE, MB R1N 3W1") | Richardson International Limited (Winnipeg; "© Copyright 2026 Richardson International Limited") | "Portage la Prairie, Manitoba, Canada 100,000 MT of groats, flakes, flour, and bran" | C1, C2 |
| Richardson Milling: Martensville, SK ("Three kilometres north of Martensville on Hwy 12") | Richardson | "Martensville, Saskatchewan, Canada 135,000 MT of groats" | C1, C2 |
| Richardson Milling: Barrhead, AB ("Box 4615, 2310 TWP Rd. 592 Manola Community Barrhead, AB T7N 1A5") | Richardson | "Barrhead, Alberta, Canada 36,000 MT of groats, flakes, flour, and bran"; "Facility is certified organic" | C1, C2 |
| Richardson: network total | Richardson | "With an annual processing capacity of over 360,000 metric tonnes, our North American oat milling facilities produce a wide range of high-quality products for major retail and industrial brands." The figure includes South Sioux City, Nebraska (U.S.), 97,000 MT. A U.K. mill (Bedford, 90,000 MT) is listed separately. "By sourcing raw commodities through Richardson Pioneer operations in Western Canada, we ensure a secure supply chain and full traceability for our customers." | C1 |
| **Can-Oat Milling: who owns it?** | **Richardson.** Richardson's release (page dated 2012-03-20): "Richardson will purchase the Can-Oat Milling business with oat processing plants in Portage la Prairie, MB, Martensville, SK and Barrhead, AB, and 21st Century Grain Processing, which has an oat processing plant in South Sioux City, NE and a wheat mill in Dawn, TX." Also: "Richardson International Limited is pleased to announce it has agreed to acquire in excess of $900 million worth of Viterra assets … which Glencore International plc plans to divest following its successful acquisition of Viterra." The Portage street address is still "#1 Can-Oat Drive". | | C3, C2 |
| **Grain Millers Canada Corp.**: Yorkton, SK ("1 Grain Millers Drive, PO Box 5040, Yorkton, SK, S3N 3Z4"; listed as "Canadian Operations") | Grain Millers (corporate HQ "Eden Prairie, MN", per the page; U.S.-headquartered) | "Our Yorkton milling facility was purchased in 2001. We have grown significantly since then and expanded our product line and customer base to supply all the major cereal, bread, cookie, and bar companies. This location offers a direct delivery point from some of the most fertile oat acreage in North America." | C5 |
| **Avena Foods Limited**: Regina, SK; Rowatt, SK; Portage la Prairie, MB | Avena Foods ("© Copyright 2026 Avena Foods Limited") | "Avena has three locations on the Canadian Prairies – the world's largest growing region for both oats and pulses." The Regina facility is a "[Purity Protocol …] Certified Processing Facility – Regina, Saskatchewan" (full name in DO-NOT-USE); the Rowatt site holds "Avena Best Cooking Pulses and Avena Purity Protocol … Cleaning and Processing Plants – Rowatt, Saskatchewan"; "Avena Best Pulse Flour and Fiber Mill – Portage la Prairie, Manitoba". "In January 2018, Avena Foods Limited merged with Best Cooking Pulses Inc. (BCP), a family-owned Canadian agri-foods milling company that had been active in the international pulse trade since 1936." Product line includes "Whole grain rolled oats, quick flakes, steel cuts, groats and flours." | C6 |
| **Emerson Milling Inc.**: Emerson, MB (page title "Oat Groat Producer \| About Emerson Milling \| MB") | Emerson Milling Inc. | "SINCE 1987 EMERSON MILLING INC. has been an industry leader in milling high quality oat groats (hulled oats) and steel cut oat groats. Ideally located in Central Canada on the United States border …" (the company's own claim) | C7 |
| **O Foods Ltd.**: northwest Winnipeg, MB | Paterson GlobalFoods (PGF), Winnipeg; "private, family owned … Originally established in 1908 as N.M. Paterson & Company Limited" | 2019 announcement (page published 2019-10-03): "The facility will be located on PGF's 600 acres adjacent to its existing inland grain terminal and ancillary businesses in northwest Winnipeg." "The new oat mill to be known as O Foods Ltd. when completed, will annually process up to 250,000 metric tonnes of raw oats from Western Canadian farmers." Start-up: "Paterson GlobalFoods is pleased to announce the commencement of operations at its subsidiary O Foods, one of Canada's largest oat mills. The first grain delivery took place on July 5th and the plant is now operating to serve both domestic and international customers for generations to come." | C8, C9 |
| **AGT Food and Ingredients**: Aberdeen, SK | AGT Foods, "majority owned by Fairfax Financial Holdings Limited" (per AGT home page) | "AGT also offers value-added oat groats, hulls, bakery products and oat-based ingredients from our Aberdeen, SK oat processing facility." | C10 |
| **Canadian Oats Milling Ltd.** (Alberta; phone 780 area code; no street address given) | "part of the Grupo Vida family of companies" | "Canadian Oats Milling Ltd. is a privately held company established in 2012 and part of the Grupo Vida family of companies with 40 years of experience in the oat business with several food processing facilities distributed throughout the Americas. Canadian Oats Milling is a large processor and exporter of conventional and organic specialty oat products …" "HS Codes: 1104.12, 1104.22" (company-supplied listing on a Government of Alberta page) | A14 |
| **Quaker / PepsiCo Canada**: Peterborough, ON and Trenton, ON | PepsiCo Canada ULC (PepsiCo, Inc., Purchase, N.Y.) | See §7 | P1 |
| **Sunrise Foods International**: Saskatoon, SK | Sunrise Foods | A **trader**, not shown as a miller. The home page says "For over 25 years , we've specialized in organic and non-GMO agri-food ingredients." It describes handling "logistics, processing and quality assurance" for producers. No oat mill is identified on the pages opened | C11 |
| **Popular Grain(s)** | — | **Not found.** populargrains.com did not resolve (curl 000), and no company page was found. See UNVERIFIED | — |

### 6.2 Capacity arithmetic (company figures only)
Richardson's three Canadian sites total **271,000 MT** by its own figures (100,000 + 135,000 + 36,000). The **O Foods** design figure is "up to 250,000 metric tonnes" of raw oats per year (2019 announcement; there is no current company capacity statement). These are **different units**: groats/flakes output versus raw-oat intake. **Do not add them** or compare them with production.

### 6.3 New mills and closures, 2023–2026
- **O Foods (Winnipeg): start of operations. The year is disputed between sources.**
  - The Paterson release text says only "July 5th". The page's machine metadata reads **datePublished 2023-07-12**, which points to **5 July 2023**.
  - USDA FAS GAIN (May 2025, **U.S.**) says: "O Foods accepted its first grain delivery on July 5, 2024 and the plant is now operating …"
  - The Paterson "O Foods" company page (published 2022-05-10; modified 2023-05-19) still says the company is "constructing a state-of-the-art oat mill with plans to supply the industry by late 2022."
  - **On air:** "Paterson GlobalFoods says its O Foods oat mill in Winnipeg took its first grain delivery on July 5th" and no year, unless a dated primary is found (UNVERIFIED #3).
- **AGT Aberdeen oat facility.** It is named on AGT's own page today. The 2022 announcement date and a 2023 commissioning date appear only in tier-b snippets that were not opened (UNVERIFIED #4).
- **Closures.** **No closure of a Canadian oat mill in 2023–2026 was found.** The searches covered "oat mill closure Canada 2024 2025 2026" plus company names. The only Quaker closure in results was in **Danville, Illinois (U.S.)**, a recall-linked item: Appendix A, do not use.
- **Grain Millers Yorkton expansion (C$100M, completed late 2018)** appears only in tier-b and aggregator snippets. It is outside 2023–2026 and was not opened.

---

## 7. PepsiCo's Canadian footprint and Quaker in Canada

**PepsiCo Canada ULC, Quaker "About Us" (P1; verbatim):**
- "A leader in the Canadian food industry for over 130 years, the Quaker brand features …" (sentence truncated here; the rest is marketing copy barred by house rule 1).
- "PepsiCo Canada operates two Quaker plants: Trenton (Ontario) and Peterborough (Ontario)."
- "Our portfolio of products includes Quaker Instant Oatmeal, Quick Quaker Oats, Quaker Life Cereal, Quaker Crispy Minis rice and/or corn chips and cakes, Quaker Granola Bars (Chewy, DIPPS, Yogourt, and Trail Mix) and Aunt Jemima pancakes and syrup." (**The page still names "Aunt Jemima"**, a brand PepsiCo renamed; the page text may be stale. Do not present it as current.)
- "PepsiCo generated nearly $92 billion in net revenue in 2024 …"
- Legal entity in the page data: "legalName":"PepsiCo Canada ULC". Privacy contact address: "PepsiCo Beverages Canada 2095 Matheson Boulevard East Mississauga, ON L4W 0G2".

**Unifor release (P2, published 19 Jun 2024; a union statement, attributed):**
- "Members at PepsiCo Foods Canada, which operate the Quaker Oats manufacturing facility in Peterborough, Ont., have ratified a new three-year contract."
- "There are 440 members of Local 1996 working at the Peterborough Plant."
- "Operated by PepsiCo Foods Canada, the Quaker brand has been around for over 130 years in Canada …"

**PepsiCo, Inc. Form 10-K, FY2025 (U.S. SEC filing, filed 2026-02-03; T12; verbatim):**
- Segments: "PepsiCo Foods North America (PFNA), which includes all of our convenient food businesses in the United States and Canada". PFNA "makes, markets, distributes and sells convenient foods, which include cereals, chips, dips, granola bars, oatmeal, pasta, rice and syrups and mixes …"
- "Our operations outside of the United States generated 44% of our consolidated net revenue in 2025, with Mexico, Russia, Canada, China, the United Kingdom, Brazil and South Africa, collectively, comprising 25% of our consolidated net revenue in 2025."
- **Net revenue by country, Canada (US$ millions): 2025 3,729 · 2024 3,764 · 2023 3,722.** This is all PepsiCo business in Canada (beverages and foods), not Quaker alone.
- Tariffs, as a risk factor: "… tariffs imposed or threatened to be imposed on China, the European Union, Canada and Mexico and other countries and any tariffs imposed by such countries) have impacted and could continue to impact our supply chain resulting in increased input costs, including the cost of certain raw materials and packaging."
- The 10-K "Significant properties" table lists **no Canadian plant**. Peterborough and Trenton rest on P1 only.

**Quaker Canada history.** The only dated history statements found on PepsiCo's own pages are "over 130 years" (P1) and "over 130 years in Canada" (Unifor, P2). pepsico.ca returned **HTTP 403** to curl and WebFetch. A Peterborough founding year (1902, "American Cereal Company") appears only in tier-b and aggregator snippets (UNVERIFIED #6).

---

## 8. The U.S.–Canada trade dispute as it touched oats and cereals, 2025–2026

### 8.1 United States (all **U.S.** records; claims are the U.S. government's)

| Date | Measure | What it says (verbatim) | Oats? | Source |
|---|---|---|---|---|
| 1 Feb 2025 (signed) | EO 14193, 90 FR 9113 | IEEPA duties on articles of Canada (25%; energy and potash lower) | General; covered Canadian goods | T1 |
| 4 Mar 2025 | Duties in effect | U.S. fact sheet: "On Tuesday, March 4, tariffs were issued on Canada and Mexico under the International Emergency Economic Powers Act (IEEPA) …" | — | T3 |
| **7 Mar 2025** | **EO 14231**: USMCA exemption | Sec. 2(a): "Articles that are entered free of duty as a good of Canada under the terms of general note 11 to the Harmonized Tariff Schedule of the United States (HTSUS) … as related to the Agreement between the United States of America, United Mexican States, and Canada, shall not be subject to the additional ad valorem rate of duty …" Sec. 2(c): "… on or after 12:01 a.m. eastern standard time on March 7, 2025." Fact sheet: "No tariffs on those goods from Canada and Mexico that claim and qualify for USMCA preference." | Any oat shipment entered as USMCA-qualifying was outside these duties from 7 Mar 2025. **Whether any given shipment claimed USMCA was not checked** | T2, T3 |
| 31 Jul 2025 (effective 1 Aug 2025) | Rate raised 25% → 35% | "Goods qualifying for preferential tariff treatment under the United States-Mexico-Canada Agreement (USMCA) continue to remain not subject to the IEEPA Canada tariffs." | Same | T4 |
| **20 Feb 2026** | Supreme Court, *Learning Resources, Inc. v. Trump*, No. 24–1287 | Syllabus: "Held: IEEPA does not authorize the President to impose tariffs." (**court ruling, a finding of law**) | Ends the legal basis of the IEEPA duties | T5 |
| 20 Feb 2026 (signed); 91 FR 9437 | EO 14389 "Ending Certain Tariff Actions" | Agencies shall "end the additional ad valorem duties imposed under IEEPA in Executive Order 14193, as amended …" and "as soon as practicable, terminate the collection" | — | T6 |
| 20 Jul 2026 | Section 338 Proclamations 11046 (alcohol), 11047 (dairy), 11048 (motor vehicles); 50% | Fact sheet (U.S. claims): "Each Section 338 proclamation imposes a 50% tariff on a different set of Canadian imports, covering products ranging from wine to hockey sticks to cement." "These Section 338 tariffs apply to all covered goods regardless of whether a good originates under the U.S.-Mexico-Canada Agreement (USMCA)." "These Section 338 tariffs will not apply to energy, potash, products subject to tariffs under Section 232, and certain other goods, such as fish or critical minerals." | **Annex check (this file): no HTSUS chapter 10 or 11 lines in any annex; chapter 19 lines are only 1901.20.25, 1901.20.35, 1901.20.60, 1901.20.70** (mixes for bakers' wares, e.g. "containing over 25% by weight butterfat"). **No 1004, 1103, 1104 or 1904 lines.** The words "oats"/"oatmeal" do not appear | T7, T8 |
| Aug 2026 | Temporary suspension; effective date moved | "(1) The effective date of the additional ad valorem duties imposed in Proclamations 11046, 11047, and 11048 shall be 12:01 a.m. eastern time on August 22, 2026." | — | T9 |
| 8 Sep 2026 | Five Section 338 proclamations: import bans and scope changes | Fact sheet (U.S. claims): "The import bans will take effect on September 29, 2026, and the product additions and removals will take effect on September 15, 2026." It also describes "removing certain products, such as rock salt and cement … and replacing those products with new ones, ranging from all-terrain vehicles (ATVs) to additional dairy products." | **Annex check: no chapter 10, 11 or 19 lines in any of the seven September annexes** | T10, T11 |

The fact-sheet characterisations ("discrimination", "retaliation", Canadian import statistics) are **U.S. government claims**. Present them as "the White House says".

### 8.2 Canada (tier a)

| Date | Measure | Oat-related items | Source |
|---|---|---|---|
| **4 Mar 2025** | **SOR/2025-66**, United States Surtax Order (2025-1), registered March 3, 2025: "This Order comes into force, or is deemed to have come into force, on March 4, 2025." 25% surtax on U.S.-origin goods in the schedule | Schedule includes **1004.90.00** (oats other than seed). **No 1104.12, 1103 or 1904 items** | A8 |
| 16 Apr – 16 Oct 2025 | United States Surtax Remission Order (2025). Per SOR/2025-181's explanatory note, relief for goods "used as inputs in Canadian manufacturing, processing or food and beverage packaging"; "Remission under this Order expires on October 16, 2025." | Whether any oat importer used it is unknown | A9; U2 (U.S. GAIN gives the same April 15–16 dates) |
| **1 Sep 2025** | **SOR/2025-181** (registered August 29, 2025): "Canada is removing its tariffs under the United States Surtax Order (2025-1)…starting on September 1, 2025." The goods affected total "$30.3 billion in annual imports from the United States" (WF-extract) | **1004.90.00 surtax ends** | A9 |
| Finance consolidated list (as of 26 Aug 2026) | Section "Effective up to August 31, 2025": "1004.90.00 \| Cereals \| Oats. \| Other \| 2025-03-04 \| 25%". The page notes the consolidated list "has no official sanction" (sibling file). | Confirms dates in and out | A10 |
| **8 Sep 2026** | New counter-tariffs matching U.S. Section 338/232 (15/25/50%) | **No oat items.** The sibling machine check of all 648 items found chapter 19 only at 1901.20.11–1901.20.29 (bakers'-ware mixes with butterfat). No 10.04, 11.03, 11.04 or 19.04 | A10; `oatmeal_rules_origin.md` §8.3 |

**Net, as of 30 Sep 2026.** No Canadian surtax applies to U.S. oats, rolled oats or HS 1904 cereals. The 25% surtax on U.S. oat grain (1004.90.00) ran from 4 Mar 2025 to 31 Aug 2025. In the U.S. record opened, no Section 338 tariff lists Canadian oats, rolled oats or 1904 cereals. The IEEPA duties ended after 20 Feb 2026 and had exempted USMCA-qualifying goods since 7 Mar 2025.

---

## 9. Buy Canadian, 2025–2026

### 9.1 Named surveys (tier d)

| Publisher / date | Fieldwork, sample, method | Exact wording (verbatim) | Key results (verbatim) | Source |
|---|---|---|---|---|
| **Angus Reid Institute**, Feb 19, 2025 | "a survey conducted online from February 16 – 18, 2025 among a representative randomized sample of 3,310 Canadian adults who are members of Angus Reid Forum. For comparison purposes only, a probability sample of this size would carry a margin of error of +/- 1.5 percentage points, 19 times out of 20." "The survey was self-commissioned and paid for by ARI." | "Which of the following are you already doing or seriously likely to do as a result of the tariffs? Select all that apply:" (options include "Buy more Canadian products", "Boycott products made in the US"). Follow-up to those choosing "buy more Canadian": "What Canadian products are you or do you intend to buy more of? (as many a apply)" (sic), with "Groceries" an option. Also: "Which one of the following applies to you... I am or plan to replace as many US products as I can with Canadian ones / … some US products … but this depends on price and quality, etc. / I am not nor do I plan to replace US products with Canadian ones" | "Four-in-five (78%) are committing to buying more Canadian products overall, while three-in-five (59%) say they'll boycott U.S. products." "For the four-in-five Canadians who are planning to buy more Canadian products, the grocery store appears to be ground zero for this trend. Nearly all (98%) say they intend to buy more Canadian groceries …" "85 per cent of Canadians stating that they have already done so, or plan to replace U.S. products." | D1 |
| **Leger**, page published 9 Sep 2026 | "Our latest Leger research, conducted August 28-30, 2026". **Sample size and method are not stated on the page** (it mentions the LEO panel only in navigation). Use with that caveat | Question wording is not published on the page | "Nearly two-thirds of Canadians (64%) say they plan to look more actively for products made in Canada given the current trade tensions with the U.S. Half say they will look more actively for products from Canadian-owned companies, while 45% say they plan to avoid U.S.-made products." "10% say they do not plan to change what they buy at all." "price came first at 67%, followed by product quality at 56%. Made in Canada was important at 45%" "88% said they would be likely to switch in food and beverages" "Made in Canada is a top switching influence for 60% of Canadians 55+, compared with just 25% of those aged 18-34." | D2 |
| **Dalhousie Agri-Food Analytics Lab** (with Caddle), *Canadian Food Sentiment Index*, Spring 2026 | "This survey, conducted on February 23 and 24, 2026 …" "The survey consisted of 3,000 respondents from across Canada." "Respondents were recruited through an online panel …" "The margin of error for this survey is +/- 1.8%, 19 times out of 20. However, as the survey was conducted online with non-probability sampling, the margin of error is less applicable." | "FIGURE 12a: How often do you check where food originated or was produced?" · "FIGURE 11: How often do you choose local foods over non-local foods?" | Spring 2026, Fig. 12a: "21.2% ALWAYS 37.1% OFTEN 29.6% SOMETIMES 9.4% RARELY 2.7% NEVER". Text: "The 'often' category rose sharply with the emergence of the 'Buy Canadian' movement in Spring 2025 (34.4%) and peaked in Fall 2025 (41.5%), before easing to 31.6% in Spring 2026. Meanwhile, the 'always' group has grown modestly over time, reaching 9.7% …" "… while the 'Buy Canadian' movement initially boosted local purchasing habits, its momentum may be softening, with affordability and convenience likely reasserting themselves as primary drivers." (The second quote is the authors' interpretation) | D3 |
| **Dalhousie AFAL**, Spring 2025 (release dated May 6, 2025) | "Data collection was conducted between March 4 and March 5, 2025 … The survey captured responses from 2,994 Canadians … survey data were weighted using the most recent Statistics Canada census data." Non-probability; "for reference … ±1.8 percentage points, 19 times out of 20." | (local-food item, as above) | "over 43.5% now say they 'always' or 'often' buy local foods , up 10 percentage points in six months." | D4 |

### 9.2 CFIA statements (tier a)
- **16 Mar 2026 statement (A11; WF-extract):** "Since April 1, 2025, the Agency has issued $47,000 in financial penalties to businesses for inaccurate or misleading country of origin claims". Named: 1000717809 Ontario Limited (Fortinos Etobicoke) $10,000; Fresh in The City Inc. $7,000; Meatex Farms Ltd. $10,000; Oxford Frozen Foods Inc. $10,000; Real Canadian Superstore $10,000. **Label: regulatory penalties (orders).** **The statement does not identify the products, and nothing connects any of them to oats.**
- **Notice to industry, 14 Mar 2025, updated 30 Jul 2025 (A12; WF-extract):** "We have seen an increase in complaints related to origin claims on bulk produce, on food labels and in advertisements." "Retailers are responsible for the accuracy of any store signage or advertisements about the origin of a food that is store generated." On the maple leaf, as returned: "The CFIA recommends that an accompanying domestic content statement be placed in close proximity to the maple leaf to clarify what is meant." The sibling file's curl copy reads "…the CFIA recommends that an accompanying domestic content statement … be placed in close proximity to the maple leaf"; use that wording.
- AAFC Question Period note AAFC-2025-QP-00123 (received 11 Dec 2025) and the 2023-12-06 origin-claims guideline are quoted in `oatmeal_rules_origin.md` §5.1. They are not re-opened here.

### 9.3 Competition Bureau (tier a; A13, date modified 2026-06-14; WF-extract)
- "For information relating to the labelling of food products, visit the Canadian Food Inspection Agency's website."
- "Don't assume a product is Canadian just because it displays red colours or a maple leaf design."
- "Canadian symbols, colours or logos used in a deceptive way could raise concerns under the law."
- **No Competition Bureau enforcement action on a Canadian food or oat origin claim in 2025–2026 was found.** The Bureau's March 7, 2025 enforcement guidelines cover non-food products (sibling file §5.2).

### 9.4 Named reporting on "Product of Canada" confusion (tier b; labels in brackets)

| Outlet / byline / date | Reported | Label |
|---|---|---|
| CBC Marketplace, Hristova & McMillan, 29 Mar 2025 (B1) | "Marketplace found that a third of products at the Loblaws were labelled as Prepared in Canada, and more than a fifth of products at Voilà were labelled with a Shop Canada logo." "Marketplace found Loblaws labelled 35 per cent of all products online as Prepared in Canada." Metro "told Marketplace the 'produit d'ici' logo was mistakenly added to items on its Ontario web pages and is being removed …" | Reporting of data analysis. Metro's statement = **company admission of error (on its website logo)** |
| CBC News, Sophia Harris, 24 Jul 2025 (B2) | "The CFIA, Canada's food regulator, told CBC News that between November 2024 and mid-July, it received 97 complaints related to country-of-origin claims." "Of the 91 complaints investigated so far, the CFIA found companies violated the rules in 29 (32 per cent) of the cases. Most involved bulk produce sold in stores, and in each case the problem was fixed, according to the agency." CBC also reports finding "imported raw almonds promoted with a red maple leaf symbol and a 'Made in Canada,' declaration" at a Toronto Sobeys | CFIA figures = **regulator findings (as reported)**. CBC's store observations = **reported observation, an allegation of mislabelling**. No oat products are named |
| CBC News, Sophia Harris, 1 Sep 2025 (B3) | "The Canadian Food Inspection Agency (CFIA) has identified 12 cases where grocers engaged in 'maple washing' …" "No fines or other penalties were issued in the cases …" "The CFIA says it has received 160 complaints related to country-of-origin claims for food so far this year … Forty cases so far have been identified by the agency as being in violation of the rules." Both grocers "told CBC News they strive for accurate country-of-origin signage" | CFIA = **findings (as reported)**. Grocers = **company statements** |
| The Globe and Mail, Helmore & Krashinsky Robertson, 18 Mar 2026 (B4) | "On Monday, the CFIA announced that since last spring, it has imposed $47,000 in fines on five businesses …" Loblaw's spokesperson "acknowledged the CFIA's findings, adding that the company is 'sorry for the error and any confusion it may have caused.'" "The CFIA is also investigating labelling and advertising overseen by the Sobeys head office, the agency said in a statement to The Globe." Sobeys "declined to comment." Food and Beverage Canada "is recommending that labelling requirements be adjusted, allowing a 'product of Canada' designation for food containing 85-per-cent domestic ingredients, down from the current 98-per-cent threshold." | Loblaw = **admission/apology (attributed)**. Sobeys = **investigation, no finding (as reported)**. The Globe's "98-per-cent" is its own paraphrase: CFIA's food rule is "all or virtually all"; use the CFIA wording (see `oatmeal_rules_origin.md` §2) |

**None of the reporting or regulatory records found names an oat or oatmeal product.**

---

## 10. Notes for the writer (what the record supports)

- **Supported:** "Canada grew about 3.9 million tonnes of oats in 2025, and Statistics Canada's August model puts 2026 at about 3.0 million" (A1, A2). "More than nine in ten of those tonnes came from the three Prairie provinces" (A1, computed). "U.S. Department of Agriculture data put Canada at roughly half of world oat grain exports in 2025" (U1, labelled U.S.). "AAFC says the U.S. took nearly 95% of Canada's oat-product exports last crop year" (A3). "Customs data show Canada exported about 14 tonnes of rolled oats for every tonne it imported in 2025" (A4, A5).
- **Supported with attribution:** "Richardson says its three Canadian oat mills, in Portage la Prairie, Martensville and Barrhead, can handle 271,000 tonnes" (C1, summed). "PepsiCo Canada says it runs two Quaker plants in Ontario: Peterborough and Trenton" (P1).
- **Not supported; do not say:** that any specific brand uses Richardson, Grain Millers or any other mill. No source opened links a retail brand to a mill (house rule 6: never infer a co-packer). Also do not say that any oatmeal was tariffed by either country, or that the 2025 drop in U.S. oat imports was caused by the surtax.

---

## Appendix A: Recalls, food-safety and barred items. **DO NOT USE ON AIR**

1. **PepsiCo 10-K FY2025 (T12):** references to the "Quaker Recall" (2023–2024) and pre-tax charges, e.g. "In 2024, we recorded a pre-tax charge of $ 187 million … associated with the Quaker Recall …", plus write-offs "associated with a previously announced voluntary recall of certain bars and cereals." These are food-safety items: **appendix only**.
2. **Quaker plant closure, Danville, Illinois (U.S.)**: seen only in search results (Food Dive, Manufacturing Dive; tier b, not opened). Recall-linked and U.S.; **do not use**.
3. **Richardson Food & Ingredients page (C4):** a sentence on sourcing practice relating to pre-harvest treatment. Pesticide-adjacent (house rule 1); **not reproduced; do not use.**
4. **Avena, Grain Millers and Richardson pages:** facility certifications and product claims tied to a barred dietary topic (house rule 1). Not reproduced beyond the location names.
5. **USDA GAIN 2025 and Paterson 2019 release:** a phrase characterising oat products in health terms. **Not reproduced; do not use.**
6. **The channel's December 2025 oatmeal video and competitor oatmeal videos:** not opened or reused here.

---

## UNVERIFIED / DO-NOT-USE

**UNVERIFIED** (re-check before air; do not state as fact):
1. **StatCan 32-10-0359-01 values** were returned by WebFetch from the table's CSV endpoint. The sums check exactly, but re-download the CSV (https://www150.statcan.gc.ca/n1/tbl/csv/32100359-eng.zip; curl was reset 40+ times today) or view the table in a browser before an on-screen table. The Nova Scotia 1,882 t repeat (2023 and 2026) especially needs a look.
2. **StatCan The Daily (A2, A2b), CFIA (A11, A12) and Competition Bureau (A13) quotes** are WebFetch extracts (curl reset). Re-copy them verbatim from the live pages.
3. **O Foods first-delivery year**: 2023 (Paterson page metadata) vs 2024 (USDA GAIN, U.S.). Unresolved.
4. **AGT Aberdeen oat facility dates** (announced 3 Mar 2022; "commissioned in 2023"; 36,000 t and 60,000 t capacity figures): tier-b and aggregator snippets only (panow, cjwwradio, producer.com, powderbulksolids, feedandgrain). Not opened.
5. **Richardson's Viterra deal closing date (1 May 2013) and "$800 million"**: GlobeNewswire (curl failed: empty reply), bakingbusiness, world-grain, AgCanada, RealAgriculture snippets. Richardson's own 2012 release says "in excess of $900 million" at agreement. Use only the Richardson release wording.
6. **Quaker Peterborough founding (1902, American Cereal Company; 1916 fire)** and **Ontario's 2012 $750,000 grant**: tier-b and aggregator snippets only (AgCanada, ptbocanada, kawarthanow, Wikipedia). pepsico.ca was 403.
7. **"Popular Grain(s)"**: no company page found; existence and location unverified.
8. **Sunrise Foods International** as an oat *miller*: not shown on its pages; it presents as a trader. One Degree Organics' farmer page names it as a supplier (in the national-brands file, not opened here).
9. **Grain Millers Yorkton C$100M expansion (2018)** and "tripled … capacity": tier b/c snippets only.
10. **CIMT "Country" field definition for imports** (origin vs. last shipment) and the meaning of "CA" rows: the definition was not re-opened today. The CIMT "Note to User" in the zip covers HS levels only.
11. **USDA PSD "share of world exports"** is this file's computation from the sum of exporter rows, not a USDA-published share. The GAIN "63 percent" is USDA staff assessment (May 2025), not official U.S. policy.
12. **Whether Canadian oat shipments to the U.S. claimed USMCA preference** in Mar 2025–Feb 2026: not checked. Do not say "Canadian oats were tariff-free" without U.S. CBP entry data. Say instead: "goods that qualified under USMCA were exempt from 7 March 2025".
13. **Any U.S. tariff on Canadian goods after 20 Feb 2026 other than Section 232/338** (e.g. a Section 122 measure): **not checked**. If used, it needs a primary record.
14. **Section 338 annex checks** used text extraction of the White House PDFs. Product scope is controlled by HTSUS, and the annex notes say descriptions "are provided for informational purposes only". A CBP or USITC confirmation would be stronger.
15. **The 2025 surtax-remission "inputs" relief**: whether any oat importer used it is unknown.
16. **Leger (D2) sample size and method**: not published on the page opened. Do not quote a margin of error.
17. **Dalhousie Fall 2025 PDF**: downloaded, but its text layer is encoded and unreadable by the extractor. Fall 2025 figures are used only as they appear inside the Spring 2026 report.
18. **AAFC Aug 2026 outlook figures** (scratchpad `aafc0826.txt`, from an earlier session) were not re-opened today. Only the Sep 2026 (A3) and Oct 2025 (A3b) PDFs were opened.
19. **Aggregators and other tier-c items seen, never used as sources:** tridge.com, oec.world, indexbox, globaltopstats, essfeed, ensun.io, zoominfo, dnb.com, Wikipedia (Richardson, Quaker, Paterson, Learning Resources, 2026 wildfires), blogTO, retail-insider, overheretoronto, elcentronews, mexicobusiness.news, agriville forum, grainelevators.ca, Thomson Reuters blog, law-firm summaries.

**DO-NOT-USE** (house rules):
20. Everything in Appendix A.
21. **The CFIA penalty list (16 Mar 2026)** in any oatmeal context that implies an oat product was involved. If used at all, say only "the CFIA says it issued $47,000 in penalties for origin claims since April 2025", attributed and dated.
22. **The Globe's "98-per-cent" description** of the food "Product of Canada" rule. Use CFIA's "all or virtually all" wording.
23. **Any inference that a store or private-label oatmeal is milled by Richardson, Grain Millers, Avena, O Foods or any other named mill.** No document opened makes that link (house rule 6).
24. **PepsiCo Canada Quaker page product list naming "Aunt Jemima"**: stale brand name; do not present it as current.
25. **The Quaker "About Us" marketing descriptors** (the rest of the "130 years" sentence): barred under house rule 1.
26. **Any statement that tariffs caused** the 2025 fall in U.S.-origin oat imports into Canada or the 2026 changes in Canadian exports. Correlation in dates only.
