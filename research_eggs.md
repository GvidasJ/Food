# Research — Eggs (October 5, 2026 redo)

Five research files from the October 3, 2026 research run, joined in full. Tiers: (a) primary, (b) named outlet, (c) do-not-use, (d) named survey.

---

# Structure note: the egg redo (replaces "7 Egg Brands Sold in Canada You MUST AVOID (And 2 That Are Actually Worth It)", 17 Apr 2026, 121K)

Prepared 3 Oct 2026. This note covers structure only:
- measured skeletons,
- why the April video hit and the August video flopped,
- a line-by-line audit of both egg videos against the house rules,
- the recommended skeleton.

Section 0b lists the primary pages opened today. The audit and the skeleton needed them, and the price snapshot in 0c shows that a price-per-egg order is documentable. Everything else is left to the dossier researchers.

Format follows note_costco_structure.md.

**Two facts change the redo before anything else:**
1. **The April President's Choice entry no longer holds.** Loblaw's own responsible-sourcing page, opened today, says: "Today, 100% of PC® shell eggs are now entirely free-run and/or free-range hen housing systems." The PC Free Run product page says: "all PC® eggs are consciously sourced from farms using 100% cage-free spaces". The April video's #5 (s57–60) said standard PC eggs "come from conventional or enriched cage production". The redo must not repeat it.
2. **The 2036 deadline does not end cages.** The NFACC Code says: "All hens must be housed in enriched cage or non-cage housing systems that meet this Code's requirements by July 1, 2036." Enriched cages remain permitted after 2036. April s28 and s30 said enriched housing is being phased out by 2036. That is wrong.

**Repo conflict to resolve before production.** /home/user/Food/covered_topics.md line 12 reads "Eggs brands — HIT (119K May 2026) — DO NOT REDO". This task is a redo with an identical title, so the user should confirm the override. The view count and month in that file also differ from the API (120,992, published 17 Apr 2026).

---

## 0. Sources

### 0a. Transcripts saved and measured (scratchpad)

All six were fetched on 3 Oct 2026 with Algrow `fetch_transcript` and saved as `tr_*.txt`. Each also has a `_clean.txt` (line breaks collapsed, `[...]` tags and `>>` removed) and a sentence-numbered working copy `eggs_num_*.txt`. Every "s#" reference below points into the numbered copy.

Words and characters are measured on auto-caption text. Captions under-punctuate, so c/w here runs low or high against a typed script.

| File | Channel / title | Published | Views (3 Oct) | Length | Words | Chars | c/w | wpm |
|---|---|---|---|---|---|---|---|---|
| tr_CC_eggs_apr2026_121K.txt | Canadian Counter, "7 Egg Brands Sold in Canada You MUST AVOID (And 2 That Are Actually Worth It)" (yO6Fd3I0CyQ) | 17 Apr 2026 (Fri) | 120,992; 2,279 likes; 190 comments | 20:18 | 3,172 | 19,951 | 6.29 | 156 |
| tr_CC_eggs_aug2026_4K.txt | Canadian Counter, "Canadians Must AVOID These 7 Egg Brands (Only 3 Are ACTUALLY Real Eggs)" (M25ZMji51hA) | 17 Aug 2026 (Mon) | 4,355; 146 likes; 7 comments | 23:53 | 3,752 | 21,831 | 5.82 | 157 |
| tr_CC_oliveoil_sep2026_16K.txt | Canadian Counter, "7 Olive Oil Brands Sold in Canada You MUST AVOID (And 2 That Are Actually Worth It)" (33VfZP0eE3s) | 27 Sep 2026 (Sun) | 16,657 in 6 days; 188 likes | 22:02 | 3,864 | 21,099 | 5.46 | 175 |
| tr_CC_jam_sep2026_8K.txt | Canadian Counter, "7 Jam Brands Sold in Canada You MUST AVOID (And 2 That Are Actually Worth It)" (nOWmPuzMppM) | 28 Sep 2026 (Mon) | 8,416 in 5 days; 112 likes | 22:10 | 3,770 | 21,068 | 5.59 | 170 |
| tr_HM_eggs_US_349K.txt | The Hidden Menu, "8 US Egg Brands You Must Avoid" (ZgEI9utS_GQ). U.S., structure only | 16 Mar 2026 | 348,749; 10,865 likes; 1,109 comments | 18:30 | 2,885 | 17,767 | 6.16 | 156 |
| tr_SBG_pjg7houH6fs_345K.txt | Steak and Butter Gal, "Avoid These 5 EGG Brands At ALL Costs (And 3 That Are Actually Safe to Eat)" (pjg7houH6fs). U.S., structure only | 16 Jun 2026 | 344,635; 14,656 likes; 1,643 comments | 25:24 | 4,791 | 27,984 | 5.84 | 189 |

**Channel baseline.** From `get_channel_videos` on 3 Oct 2026 (full list saved as `cc_videos_20261003.json`), the 53 uploads from 8 Aug to 30 Sep 2026 have:
- a median of 6,738 views;
- quartiles of 3,215 and 21,351.

**The title construction "N X Brands Sold in Canada You MUST AVOID (And …)":**
- 13 uploads, median 4,775.
- The exact suffix "(And 2 That Are Actually Worth It)" returned:
  - Peanut butter 24,615 (14 Apr)
  - Eggs 120,992 (17 Apr)
  - Jam 82,163 (16 Apr)
  - Frozen chicken breast 2,331 (19 Apr)
  - Olive oil 16,657 (27 Sep, 6 days)
  - Jam 8,416 (28 Sep, 5 days)
- The other April uploads in the same daily run returned 803 to 6,591, except butter at 21,595.
- So the construction alone does not explain 121K: on the run's days, the staples (eggs, jam) carried it.

**The title construction "Canadians Must AVOID These N …":** 12 uploads, median 3,887. It reached 100,970 once (cheese) and 31,378 once (ice cream).

### 0b. Primary and named pages opened on 3 Oct 2026, with tier

Working copies are in `scratchpad/eggs_src/`. "curl" means the page was fetched raw and read in full. "WebFetch" means the page was read through a summarising fetcher, so its quotes must be screen-captured verbatim before air.

| # | Source | URL | Method / result | Tier |
|---|---|---|---|---|
| P1 | Justice Laws, *Egg Regulations*, C.R.C., c. 284 | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._284/ | curl 200. Page reads: "Egg Regulations [Repealed, SOR/2018-108, s. 411]"; "Regulations are current to 2026-09-21 and last amended on 2019-01-15." **The Egg Regulations no longer exist. Cite the SFCR.** | (a) |
| P2 | Justice Laws, *Safe Food for Canadians Regulations*, SOR/2018-108, full text | https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/FullText.html | curl 200 (sfcr.txt) | (a) |
| P3 | CFIA, "Labelling requirements for shell eggs" (date modified 2024-03-18) | https://inspection.canada.ca/en/food-labels/labelling/industry/shelled-eggs-products | curl 200 (cfia_shell.txt) | (a) |
| P4 | CFIA, "Method of production claims on food labels" | https://inspection.canada.ca/en/food-labels/labelling/industry/method-production-claims | curl 200 (cfia_mop.txt). The page contains no egg-housing term ("free run", "free range", "cage") anywhere; a grep of P3 and P4 returned zero hits. | (a) |
| P5 | CFIA, *Canadian Grade Compendium: Volume 5 – Eggs* (date modified 2021-04-28) | https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference/canadian-grade-compendium-volume-5 | curl 200 (comp5.txt) | (a) |
| P6 | Statistics Canada, Table 18-10-0245-01, "Monthly average retail prices for selected products" (CSV zip) | https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip | curl 200. WDS `getCubeMetadata` (https://www150.statcan.gc.ca/t1/wds/rest/getCubeMetadata) gives "releaseTime":"2026-09-02T08:30" and "cubeEndDate":"2026-07-01", so July 2026 is the latest month. | (a) |
| P7 | Egg Farmers of Canada, *2025 Annual Report* (dated 2026-03-18) | https://www.eggfarmers.ca/wp-content/uploads/2026/03/2026-03-18_Egg-Farmers-of-Canada_Annual-Report-2025.pdf | curl 200, 5,673,023 bytes, byte-identical to the parallel dossier's copy (scratchpad/eggs/efc_ar2025.txt is the text). Other eggfarmers.ca HTML pages returned 403 (Cloudflare) to curl today. | (a) |
| P8 | NFACC, *Code of Practice for the Care and Handling of Pullets and Laying Hens* (HTML) and code landing page | https://www.nfacc.ca/poultry-layers-code-of-practice ; https://www.nfacc.ca/codes-of-practice/pullets-and-laying-hens | curl 200 (nfacc_full.txt). The landing page says the Code was "originally released in 2017" and that "Amendments … were initiated in 2023 and completed in 2025". | (a) |
| P9 | Eggs.ca (EFC), FAQ "Are there different types of hen housing?" | https://www.eggs.ca/faq/are-there-different-types-of-hen-housing/ | curl 200 | (a) |
| P10 | Eggs.ca FAQ "What is an egg grading station?" / "What is a Grade A egg?" / "Do egg farms ever get inspected?" | https://www.eggs.ca/faq/what-is-an-egg-grading-station/ ; https://www.eggs.ca/faq/what-is-a-grade-a-egg/ ; https://www.eggs.ca/faq/do-egg-farms-ever-get-inspected/ | curl 200 | (a) |
| P11 | Loblaw Companies, "Responsible sourcing" (cage-free chicken eggs section) | https://www.loblaw.ca/en/responsible-sourcing/ | curl 200 (loblaw_rs.txt) | (a) |
| P12 | Loblaw PC Express product API, search "eggs", date 03102026: Loblaws Toronto store 1032, No Frills Toronto store 7952 (Bo's), Real Canadian Superstore Vancouver 1517 (Marine Dr), RCSS Calgary 1539 (Heritage Meadows) | POST https://api.pcexpress.ca/pcx-bff/api/v1/products/search (the backend of loblaws.ca / nofrills.ca / realcanadiansuperstore.ca; same route as research_jam.md §0) | 200 at all four stores, captured 03:50–03:51 UTC. Raw JSON is in eggs_src/lb/*.json; filtered rows are in eggs_src/lb/egg_rows.json. Product detail GET …/products/{code}?…storeId=1032&banner=loblaw returned descriptions and label images (detail_*.json). | (a) |
| P13 | Loblaw product images (CDN) for No Name Large 12, Naturegg Nestlaid Omega 3, Burnbrae "Grade A Large Eggs" 18 | https://digital.loblaws.ca/PCX/20812144001_EA/en/1/20812144001_en_front_v1_800.png ; https://digital.loblaws.ca/PCX/21069384001_EA/en/1/6565100830_enfr_front_centre_marketing_GS1_Ecommerce_800.png ; https://digital.loblaws.ca/PCX/20814294001_EA/en/1/6565100001_enfr_front_centre_marketing_GS1_Ecommerce_800.png | curl 200, viewed | (a) |
| P14 | Gray Ridge Egg Farms (P&H Foods), home / "Our History" / "Hen Care" | https://grayridge.com/ ; https://grayridge.com/about-gray-ridge/our-history/ ; https://grayridge.com/hen-care/ | curl 200 | (a) |
| P15 | GoldEgg home | https://goldegg.ca/ | curl 200 | (a) |
| P16 | P&H Foods home (first request 200); "Our Brands – Retail" | https://phfoods.ca/ ; https://phfoods.ca/our-brands/retail/ | home: curl 200. Retail page: curl 403 (Cloudflare), WebFetch summary lists "Gray Ridge (Local Ontario eggs)", "Sparks Eggs (Local Alberta eggs)", "Golden Valley Eggs (Local BC eggs)". The home page lists affiliates gray-ridge-egg-farms, golden-valley, sparks-eggs, national-egg, global-egg, egg-solutions, perth-county-ingredients. | (a) |
| P17 | Yorkshire Valley Farms FAQ | https://yorkshirevalley.com/pages/frequently-asked-questions | curl 200. yorkshirevalleyfarms.com reset the connection / 503. | (a) |
| P18 | Susan Noakes, CBC News, "Retail Council says major grocers want cage-free eggs within the decade", posted 18 Mar 2016 | https://www.cbc.ca/news/business/retail-council-cage-free-eggs-1.3497958 | curl 200 | (b) |
| P19 | Tania Kohut, Global News, "Canadian grocers' move to cage-free eggs an 'important commitment'", posted 18 Mar 2016 | https://globalnews.ca/news/2586899/canadian-grocers-move-to-cage-free-eggs-an-important-commitment/ | curl 200 | (b) |
| P20 | CAN/CGSB-32.310-2026, *Organic production systems: General principles and management standards* | https://publications.gc.ca/collections/collection_2026/ongc-cgsb/P29-32-310-2026-eng.pdf | My curl returned a 19 KB non-PDF page. The clauses below were read from the parallel dossier's copy fetched today (scratchpad/eggs/cgsb2026pdf.txt). Re-open before any on-screen quote (U-list). | (a) |

Blocked today, with no content used:
- burnbraefarms.com, naturegg.com and islandeggs.com (all 403);
- retailcouncil.org (Cloudflare challenge / 403);
- sobeyssbreport.com (403);
- retail-insider.com (403);
- the P&H sub-pages (403);
- eggfarmers.ca HTML pages (403);
- yorkshirevalleyfarms.com (reset / 503).

**Key verbatim lines used throughout:**

- **P2, SFCR s. 218(1)(b).** The label must bear "the name and principal place of business of the person by or for whom the food was manufactured, prepared, produced, stored, packaged or labelled".
  - P3 applies this to shell eggs.
  - The No Name carton (P13) shows "LOBLAWS INC., TORONTO M4T 2S8, CANADA". The carton names the store, not the grader.
- **P2, s. 314(1)(a).** The grade name on an egg carton must be shown "on the top of the tray or egg carton". s. 316: size designation "in close proximity to the grade name". s. 256(1): imported prepackaged eggs must bear "Product of" followed by the country.
- **P3 grade names.** "There are 4 Canadian grade names for shell eggs … Canada A, Canada B, Canada C, Canada Nest Run". Canada A and B are shown "inside the outline of a maple leaf".
- **P3 claims.** These are CFIA's own stated positions:
  - "The Canadian Food Inspection Agency's (CFIA) position is that all eggs are fresh."
  - "The claim 'farm fresh' implies that the eggs were distributed directly from the farm to the store. This claim should only be used if the licence holder grades their own eggs on-farm and ships them directly to the store."
  - "CFIA's position is that all eggs are natural."
  - "Claims such as 'specially selected from young hens' are permitted."
  - "'no preservatives' or similar claims are not acceptable for shell eggs".
  - A "no hormones" claim alone "would be considered misleading … as the use of hormones is not permitted in poultry in Canada".
- **P4.** "all method of production claims provided on food labels or in advertising must be accurate, truthful, and must not mislead or deceive the consumer." Substantiation may be by "third party audit", "valid documentation", etc. The page does not define "free run" or "free range".
- **P5 Canada A requirements.**
  - On candling: "a reasonably firm albumen", "an indistinct yolk outline", "a round yolk that is reasonably well centered", "an air cell that is not in excess of 5 mm in depth".
  - A shell that is "uncracked".
  - Size bands: Large "56 g" to under "63 g"; Extra Large 63–70 g; Medium 49–56 g.
- **P6.** Canada, "Eggs, 1 dozen":
  - July 2026: $4.95.
  - July 2025: $4.95, which is the series maximum; the two are tied.
  - January 2017, the series start: $3.01.
  - Jan 2024 – Jun 2026 range: $4.26 (Mar 2024) to $4.95 (Jul 2025).
  - July 2026 by province ranges from Quebec $4.43 to British Columbia $5.75 (Ontario $5.00, Alberta $5.20).
- **P7 housing (p. ~9).** "As of mid-2025, the share of hens housed in conventional systems decreased to 39.45%, down from 42.02% in 2024 and 52.88% in 2021. Enriched colony remains the largest alternative housing system in Canada, representing 39.33% of hens in 2025. … In 2025, free run, free range and organic systems represented 21% of hens in Canada, compared to 10% in 2016. … Current trends suggest conventional housing is projected to be eliminated by the target date of 2036, if the transition maintains the pace observed over the past three years."
  - The table, July 2025 values: Aviary/free run 14.77%; Organic 4.99%; Free range 1.46%.
- **P7 other figures.**
  - "937 million dozen eggs produced in Canada in 2025."
  - "1,295 egg farms and farm families located across Canada"; average 22,069 layers per farmer.
  - "egg production up by approximately 7.6% in 2025".
  - Free range standard: "a national Free Range Standards Certification Program. This mandatory program details a consistent set of standards that egg farms must meet to be considered free range, including range access and space, vegetation, pophole and perimeter fence requirements. The Free Range Standards Certification Program was approved by the EFC Board of Directors in August for implementation in early 2026."
- **P8 (NFACC Code, s. 2.5).**
  - "If any hens have not been transitioned from conventional cages by July 1, 2031, each of those hens still kept in conventional cages must be provided with a minimum space allowance in those systems of 580.6 cm2 (90.0 sq in) … All hens must be housed in enriched cage or non-cage housing systems that meet this Code's requirements by July 1, 2036."
  - s. 2.5.1: "For Enriched Cages, each hen must be provided with a minimum of 750.0 cm2 (116.25 sq in) of total space, including nests, of which 600.0 cm2 (93.0 sq in) does not include nest boxes." This applies to new construction or re-tooling "initiated after April 1, 2017".
  - Single-tier all-litter non-cage: "1,900.0 cm2". Single- or multi-tier combination systems: "929.0 cm2".
- **P9.** "In conventional systems, hens are housed in small group settings with plenty of access to food and water. Enriched systems are equipped with perches and a curtained off area where the hens lay their eggs. In free run systems, hens roam the entire barn floor. Some of these barns are also equipped with multi-tiered aviaries. Similar to free run systems, in free range systems hens also roam the barn floor, and when weather permits they go outside."
- **P10.** "Once eggs have left the farm, they go through the grading station where they are washed, candled, weighed and packed. All grading stations are registered and inspected by the Canadian Food Inspection Agency."
  - Washing is a process fact only; no food-safety commentary.
- **P11 (Loblaw).** "we have accelerated our transition plan, ensuring that all control brand shelled chicken eggs will come from hens housed in alternatives to the standard 'battery' cage by 2030, including from free-run² or free-range³. Today, 100% of PC® shell eggs are now entirely free-run and/or free-range hen housing systems. In 2025, free-run and free-range eggs represented approximately 18% of total category sales." Footnote: "Subject to available supply."
- **P12 detail pages.**
  - PC Free Run Brown Eggs Large: "exclusively from hens who live in an open-concept barn environment where they are free to roam, feed and nest … all PC® eggs are consciously sourced from farms using 100% cage-free spaces."
  - Naturegg Solar Free Range: "Free Range: Laying hens housed in an open concept barn with outdoor access."
  - Burnbrae "Grade A Large Eggs" (18, a Prestige Club Pack in the image): "Since 1893. From Our Family to Yours!"
  - Rowe Farms Green Valley: shells "are either white or brown, depending on the breed of the hen."
- **P13 images.**
  - The No Name Large 12 top shows only: "no name", "12 eggs", "large size", the Canada A maple leaf, "BEST BEFORE", "KEEP REFRIGERATED", "LOBLAWS INC., TORONTO M4T 2S8", "NUTRITION FACTS INSIDE LID". No housing word.
  - The Nestlaid Omega 3 top carries small print at upper right that reads approximately "FROM HENS RAISED IN ENRICHED COLONY HOUSING EQUIPPED WITH PERCHES AND NESTING AREAS". That reading is not certain at 800 px and needs a physical capture.
  - The Burnbrae 18 "Grade A Large Eggs" image is a Prestige Club Pack ("First choice for chefs") with no housing word on the top.
- **P14 (Gray Ridge).**
  - "In 1934, Lyle and Ina Gray established an egg grading station … By 1969, they had become the only egg grading station in Ridgetown … In 1970, Ina Gray created the Gray Ridge Egg Farms brand".
  - "supplying eggs … under the Gray Ridge Egg Farms, GoldEgg, and Conestoga Farms brands. Over a decade ago, Bill Gray partnered with Parrish & Heimbecker, Limited (P&H) … This partnership laid the foundation for what is now P&H Foods Inc., bringing Gray Ridge Egg Farms and its affiliated brands together under one organization".
  - "Each carton of Ontario eggs – whether it be Gray Ridge, GoldEgg or Conestoga Farms branded – proudly sports the famous Foodland Ontario logo."
  - The home page describes Conestoga Farms as "Ultra-wholesome, hyper-local Ontario eggs".
  - Hen Care: "Enriched colony is a newer housing type that features larger enclosures, allowing hens to exhibit their natural behaviours with access to quiet nesting boxes, perches and scratching areas. All egg farmers in Canada are phasing out conventional (cage) housing by 2036."
- **P15 (GoldEgg).** "Under the national GoldEgg brand, local farmers deliver Canadians quality specialty eggs, like free run and organic, eggs enriched with nutrients like Vitamin D and Omega-3, or convenient liquid eggs."
  - The nutrient part is off limits on air.
- **P17 (YVF).** "founded in 2010 by two eastern Ontario farming families and today, is one of Canada's leading organic poultry providers. We are supported by over 30 dedicated Ontario organic poultry farms, who also farm over 2,300 acres of organic crops". Also: "certified organic by Pro-Cert Organic Systems Ltd".
- **P18 (CBC).**
  - "A group representing Canada's major grocers has committed to buying cage-free eggs by the end of 2025. The Retail Council of Canada issued a release Friday saying the voluntary commitment would be contingent on 'availability of supply within the domestic market.' The Retail Council includes Loblaw Co. Ltd., Metro Inc. Sobeys Inc. and Wal-Mart Canada Corp., which together represent 90 per cent of grocery retail in Canada."
  - "Currently about 90 per cent of Canadian egg production is in what the industry calls 'conventional housing' meaning cages. In February, industry association Egg Farmers of Canada committed to a 'systematic, market-oriented transition from conventional egg production toward other methods of production for supplying eggs.'"
- **P20 (CGSB 32.310-2026).**
  - 6.13.1 a): "The keeping of poultry in row, battery, enriched or colony cages, is prohibited".
  - 6.13.1 b): "Poultry shall be reared in open-range conditions and have free access to pasture, open-air runs, and other exercise areas, subject to weather and ground conditions."
  - 6.13.2 a): "The laying flock shall have outdoor access for at least one third of its laying life."
  - 6.13.2 c): "Layer flocks shall be limited to 10,000 birds."
  - 6.13.7: "Poultry barns shall have sufficient exits (popholes) to ensure that all birds have ready access to the outdoors."

### 0c. Shelf snapshot, 3 Oct 2026 (P12): shell eggs only, price per egg computed

Banner, store, pack, price and price type are as the retailer's own site returned them at 03:50–03:51 UTC. Price per egg = price ÷ count. "OUT" or "LOW" is the stock status returned. Re-capture on air day (rule 5).

**Loblaws, Toronto, store 1032** (product URLs are https://www.loblaws.ca + link in egg_rows.json):

| ¢/egg | Brand | Product (retailer's name) | Pack | Price | Note |
|---|---|---|---|---|---|
| 30.6 | No Name | Eggs, Medium | 30 | $9.18 | |
| 30.6 | Burnbrae Farms | Farm Eggs Medium | 30 | $9.19 | OUT |
| 32.8 | No Name | Large Size Eggs 12 Pack | 12 | $3.93 | |
| 38.8 | Burnbrae Farms | Grade A Large Eggs (image = Prestige Club Pack) | 18 | $6.98 | |
| 39.1 | No Name | Extra Large Size Eggs 12 Pack | 12 | $4.69 | |
| 50.0 | Burnbrae Farms | Naturegg Nestlaid Omega 3 Large | 12 | $6.00 SPECIAL (was $6.69 = 55.8¢) | |
| 52.4 | No Name | Large Size Brown Eggs 12 Pack | 12 | $6.29 | |
| 54.1 | Rowe Farms | Green Valley Omega 3 Eggs, Large | 12 | $6.49 | |
| 57.5 | PC Organics | Free-Range Large Brown Eggs, Club Pack | 30 | $17.25 | |
| 58.3 | Conestoga Eggs | Brown Eggs Free Run Omega-3 Large | 18 | $10.49 | |
| 59.6 | President's Choice | Free Run Brown Eggs Large | 12 | $7.15 | |
| 60.8 | Burnbrae Farms | Naturegg Omega 3 Brown Eggs, Large | 12 | $7.29 | |
| 62.5 | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | 12 | $7.50 SPECIAL (was $8.19 = 68.3¢) | |
| 63.8 | Burnbrae Farms | Organic Free Range Eggs | 18 | $11.49 | |
| 66.6 | PC Organics | Organics Large Size Free-Range Brown Eggs | 12 | $7.99 | LOW |
| 66.6 | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | 12 | $7.99 | |
| 69.1 | Green Valley | Brown Eggs Free Range Farm Large | 12 | $8.29 | |
| 74.9 | Conestoga Eggs | Brown Eggs Free Range Omega-3 Large | 12 | $8.99 | |

**No Frills, Toronto, store 7952:**
- No Name Large 12 at $3.93 (32.8¢).
- No Name Large Brown 12 at $5.99 (49.9¢).
- Burnbrae Grade A Large 18 at $7.06 (39.2¢).
- Nestlaid Omega 3 12 at $6.49 (54.1¢).
- PC Free Run Large 12 at $7.18 (59.8¢).
- Conestoga Free Run Omega-3 18 at $10.49 (58.3¢).
- PC Organics Free-Range Club 30 at $17.50 (58.3¢).
- Naturegg Solar Free Range 12 at $8.19 (68.2¢).

**Real Canadian Superstore Calgary 1539 / Vancouver 1517:**
- No Name Large 12: $4.18 / $4.21 (34.8 / 35.1¢).
- PC Organics Free-Range Club 30: $16.99 at both (56.6¢).
- Burnbrae Organic Free Range 18: $11.49 at both (63.8¢).

**What the snapshot settles:**
- **A price-per-egg order is documentable** from the retailer's own site, store by store, on a named date.
- **No conventional PC carton** was returned at any of the four stores. Every President's Choice / PC Blue Menu shell-egg SKU was "Free Run" or "Organic Free-Range". This agrees with P11.
- **The brown premium:** at Loblaws 1032 the same brand (No Name, Large, 12) costs 32.8¢ white and 52.4¢ brown, +19.6¢ per egg (+60%).
- **Organic undercuts some free-range and free-run cartons:** the PC Organics 30-pack (57.5¢ Toronto, 56.6¢ West) is cheaper per egg than Conestoga Free Range Omega-3 (74.9¢), PC Blue Menu Free-Run (66.6¢) and PC Free Run 12 (59.6¢).
- **Not covered:**
  - Great Value (Walmart) and Compliments (Sobeys), both in the April video, were not captured. walmart.ca blocks bots; Sobeys and voila were not tried. research_jam.md §0 documents the Flipp feed and voila routes.
  - Gray Ridge white cartons were not returned at Loblaws 1032.

---

## 1. Measured skeletons

### 1a. Canadian Counter, 17 Apr 2026 (121K): the video being redone. 3,172 w, 19,951 chars

**Cold open, 225 w (7.1%). Five moves:**
1. An object hook, the carton "in your refrigerator right now" (s1), plus four "without" clauses (s2): 66 w.
2. The count: "Seven brands on the avoid list today, two that earned worth it placements" (s3): 13 w.
3. Teaser 1: "Canada's largest egg producer", with an advocacy group's 2024 finding (s4): 42 w.
4. Teaser 2: the same parent company sells an avoid and a worth-it (s5): 45 w.
5. Teaser 3: "the healthiest recommendation … more than double the vitamin D and three and a half times the vitamin E" (s6): 59 w.

There is no dated fact, no source list and no ask. The first brand is named at 6.7% of characters.

**Count and order.** Seven numbered avoids ("The second brand…", "The fourth brand…"), then two worth-its. The order basis is not stated aloud. The structure implies "largest first" (Burnbrae), then store brands, then the Gray Ridge/P&H family.

| Beat | Sent. | Words | Share | Starts (w%) | Starts (c%) |
|---|---|---|---|---|---|
| Cold open | 1–6 | 225 | 7.1% | 0.0% | 0.0% |
| #1 Burnbrae | 7–24 | 485 | 15.3% | 7.1% | 6.7% |
| #2 No Name | 25–34 | 291 | 9.2% | 22.4% | 22.3% |
| #3 Great Value | 35–41 | 195 | 6.1% | 31.6% | 31.4% |
| #4 Gray Ridge (+ L.H. Gray history) | 42–53 | 313 | 9.9% | 37.7% | 37.6% |
| #5 President's Choice | 54–60 | 214 | 6.7% | 47.6% | 47.3% |
| #6 Compliments | 61–70 | 222 | 7.0% | 54.3% | 54.0% |
| Channel note + subscribe ask | 71–73 | 71 | 2.2% | 61.3% | 61.3% |
| #7 Conestoga Farms | 74–87 | 290 | 9.1% | 63.6% | 63.6% |
| Turn + W1 GoldEgg | 88–103 | 321 | 10.1% | 72.7% | 72.2% |
| W2 Yorkshire Valley Farms | 104–118 | 407 | 12.8% | 82.8% | 82.3% |
| Close (moral) | 119–126 | 138 | 4.4% | 95.6% | 95.8% |

**Ask.** One ask, the subscribe ask, at 62.9% of characters (s72): "If this investigation is providing value, subscribe now and turn on notifications so you don't miss the next one."
- It is preceded by a 30-word channel-method line (s71) and followed by a stay-hook (s73: "The Worth It brands at the end of this list are worth staying for.").
- There is no like ask, no comment ask, no share ask, no tagline and no disclaimer.
- The hit's ask already sat inside the 61–63% window the redo targets.

**Per-beat anatomy (words).**

| Beat | Jobs and word counts |
|---|---|
| #1 Burnbrae (485) | frame 56; founding history 88; company today 76; "not about identity" 35; MFA 2013 / W5 53; MFA 2024 reporting critique 130; close 47 |
| #2 No Name (291) | frame 43; brand identity (1978) 35; housing claim + 2036 phase-out 149; concession + steer 64 |
| #3 Great Value (195) | frame 40; identity 16; housing claim + "purely price" 139 |
| #4 Gray Ridge (313) | frame 50; Gray family history 148; housing claim 77; "estimated to control" concentration 38 |
| #5 PC (214) | frame 44; identity (1984) 37; housing claim 133 |
| #6 Compliments (222) | frame 40; identity / banners 36; housing claim 53; "duopoly" 93 |
| #7 Conestoga (290) | lesson ("who owns a brand does not determine…") 62; identity 71; free-range / organic carve-out 67; housing + close 90 |
| W1 GoldEgg (321) | frame 32; same-parent 66; **nutrition 223** |
| W2 YVF (407) | frame 36; history 78; certification 41; housing / feed 67; **nutrition 102**; award + verdict 83 |

**Mechanism.**
- Every avoid rests on one sentence, "sourced from conventional or enriched cage production", stated without a source for six of the seven brands. Burnbrae's rests on advocacy-group material.
- Every worth-it rests on nutrition. About 400 words (about 13%) are nutrition: s6, s94–103, s114–116, s118 and s122.
- The comments asked for brevity:
  - "Spit out your story, we do not need the history" (16 likes);
  - "Video is too long. Name the brands" (14);
  - "History lesson not needed" (7);
  - "way too long. Please stop padding" (5).
- The comments also flagged availability:
  - "Never seen Yorkshire Valley" (BC, 30 likes);
  - "never heard of the last 3" (GTA, 11);
  - "Have not seen these in Montreal" (7);
  - "Never heard of the last 2. Yorkshire and Goldegg" (9).
- The top comment is "We gonna end up eating nothing" (172 likes). The second (89) is a viewer listing the eight brands.

### 1b. Canadian Counter, 17 Aug 2026 (4.4K): the August flop. 3,752 w, 21,831 chars

**Cold open, 340 w (9.1%), plus 235 w of thesis and definitions. The first brand starts at 15.2% of characters.**
1. A dated U.S. event: "In March of last year, the United States lost its mind over eggs" (s1).
2. U.S. bird flu, U.S. prices, Waffle House, rationing (s2–5).
3. U.S. border egg seizures against fentanyl (s6–8).
4. Windsor and Michigan Walmart prices (s9).
5. StatCan band $4.26–$4.95 (s10).
6. USDA letters to Europe, Turkey, The Logic at a Niagara No Frills (s11–14).
7. The Canadian system: 1,300 farms, Cal-Maine 44M (s15–20).
8. "not going to tell you Canadian eggs are fake, or dangerous" (s21–22).
9. Thesis: the carton words (s23–25).
10. Definition of "real" (s26–34).

The U.S. material takes 260 words (6.9%) before Canada is mentioned.

| Beat | Sent. | Words | Share | Starts (c%) |
|---|---|---|---|---|
| Cold open: U.S. crisis + system | 1–20 | 340 | 9.1% | 0.0% |
| Thesis + "real" definition | 21–34 | 235 | 6.3% | 9.4% |
| #1 Classic white dozen (Grade A, washing, best-before, cages, Marketplace) | 35–65 | 443 | 11.8% | 15.2% |
| #2 Naturegg Nestlaid | 66–96 | 403 | 10.7% | 27.0% |
| #3 Prestige | 97–106 | 133 | 3.5% | 38.1% |
| #4 P&H four brands + Island Gold | 107–121 | 244 | 6.5% | 41.5% |
| Like ask | 122–123 | 22 | 0.6% | 48.4% |
| #5 Omega-3 | 124–147 | 352 | 9.4% | 49.0% |
| #6 Free run vs free range | 148–172 | 301 | 8.0% | 57.8% |
| Subscribe ask | 173–175 | 43 | 1.1% | 66.0% |
| #7 Retailer cage-free pledge | 176–192 | 286 | 7.6% | 67.1% |
| Fridge decoder (4 rules) | 193–212 | 180 | 4.8% | 75.0% |
| Three worth-its (free range, organic, certification / small flock) | 213–234 | 435 | 11.6% | 79.8% |
| Recap + 2036 close | 235–245 | 257 | 6.8% | 91.6% |
| Comment + share ask + sign-off | 246–248 | 78 | 2.1% | 98.0% |

**Asks.**
- Like at 48.4% of characters (s122: "If this label decoding is saving your grocery money, hit like.").
- Subscribe at 66.0% (s173: "If this is the kind of fine print you want read every single week, subscribe to Canadian Counter.").
- Comment at 98.4% (s246).
- Share at 99.3% (s247: "send them this").
- There is no tagline and no disclaimer.

**Per-beat anatomy (words).**
- #1: brands + grade 110; washing / best-before 165; housing 92; fairness / Marketplace nutrition 76.
- #2: identity 47; product name + company copy 112; concession + surveys 111; Animal Justice 85; close 48.
- #5: price 42; nutrition 110; yolk colour 67; "enhanced" + concession 133.
- #6: definitions 101; law 110; concession + BC 90.
- #7: pledge 101; "fair version" + close 185.
- Worth-its: free range 98; organic 187; certification / small flock 150.

**The title promises seven brands; the script delivers four brands and three concepts.**
- #1 is three store brands treated as one ("the classic white dozen").
- #4 is four brands treated as one.
- #5 is a category, #6 a word, #7 a retailer promise.
- The three worth-its are categories (free range, organic, certified or farm-gate), not brands.
- The script explicitly disowns the title's "real eggs" claim (s26–27): "every egg in this video is a real egg. Nobody is counterfeiting breakfast."

### 1c. Canadian Counter olive oil, 27 Sep 2026 (16.7K in 6 days): the best current execution of this title construction. 3,864 w

| Beat | Words | Share | Starts (c%) |
|---|---|---|---|
| Cold open (CFIA number, "worse than honey", no brand named, count, hook "Number one is the bottle in the fridge door of a million Canadian kitchens with a $7 million settlement", "Don't skip ahead", sources) | 182 | 4.7% | 0.0% |
| Yardstick: grade word, origin line, date, price per 100 mL, French line | 462 | 12.0% | 4.8% |
| #7 No Name | 210 | 5.4% | 16.5% |
| #6 Great Value | 190 | 4.9% | 21.8% |
| #5 President's Choice | 232 | 6.0% | 26.7% |
| #4 Carapelli | 262 | 6.8% | 32.8% |
| #3 Colavita | 329 | 8.5% | 39.8% |
| Like ask ("Quick favor before the last two") | 44 | 1.1% | 48.4% |
| #2 Filippo Berio | 437 | 11.3% | 49.4% |
| #1 Bertolli | 552 | 14.3% | 60.8% |
| Turn + W2 Terra Delyssa | 193 | 5.0% | 75.1% |
| W1 Kirkland (+ Arini mention) | 279 | 7.2% | 80.1% |
| Counter test | 125 | 3.2% | 87.3% |
| Run-back + quality/value split + 3 questions | 272 | 7.0% | 90.5% |
| Comment ask + mantra + disclaimer | 95 | 2.5% | 97.5% |

**Per-brand template (every brand):**
1. Number + name + recognition line.
2. Shelf price with banner and "this week", and the per-100 mL figure.
3. "Here is what is genuinely good about it" / "Full credit", the concession.
4. The label or ownership fact.
5. The legal record, labelled ("American case, American court", "No court found the label false. Nothing was admitted.").
6. "The habit from number N" (one checkable instruction).

The order is a countdown, worst last. The single like ask at 48.4% sits before the last two. The disclaimer ends "Nothing here is health or dietary advice."

### 1d. Canadian Counter jam, 28 Sep 2026 (8.4K in 5 days). 3,770 w

| Beat | Words | Share | Starts (c%) |
|---|---|---|---|
| Cold open (law number in s3, count, "Every price was checked at a named store on the 26th of September 2026", order basis "from the brand with the least shelf space … to the brand with the most", hook, "Don't skip ahead") | 191 | 5.1% | 0.0% |
| Yardstick (4 checks) | 272 | 7.2% | 5.0% |
| #7 Dora | 274 | 7.3% | 12.1% |
| #6 St. Dalfour | 272 | 7.2% | 19.4% |
| #5 No Name | 234 | 6.2% | 26.3% |
| Interlude: four legal names + CFIA on "pure" | 276 | 7.3% | 32.6% |
| #4 PC Blue Menu | 314 | 8.3% | 40.1% |
| #3 PC Pure | 275 | 7.3% | 48.1% |
| Like ask | 27 | 0.7% | 55.4% |
| #2 Bonne Maman | 316 | 8.4% | 56.1% |
| #1 Smucker's | 364 | 9.7% | 64.2% |
| Turn + W1 Crofter's | 312 | 8.3% | 74.1% |
| W2 Last Mountain + viewer mentions | 260 | 6.9% | 82.7% |
| Counter test | 128 | 3.4% | 90.0% |
| Run-back + 3 questions + comment ask + disclaimer | 255 | 6.8% | 93.4% |

**Per-brand template:**
1. Recognition.
2. Price per 100 at named stores.
3. The legal common name read off the label.
4. "Flip the jar", the first three ingredient words.
5. "The concession".
6. "The reality gap".
7. A one-line closer.

**Two devices the egg redo can reuse:**
- The order basis is stated in the open and is documentable (shelf presence).
- The nutrition refusal is said on air: "a calorie comparison we will not discuss because this channel does not do nutrition" (s141).

### 1e. The Hidden Menu, "8 US Egg Brands You Must Avoid" (349K). U.S.; structure only

| Beat | Words | Share | Starts (c%) |
|---|---|---|---|
| Cold open: price ($6.23), profits (+340%), DOJ probe, label words, "Every claim comes from court documents, class action settlements, regulatory actions, or verified reporting" | 224 | 7.8% | 0.0% |
| #8 Great Value / Marketside (Cal-Maine supplier, 2018 class action) | 321 | 11.1% | 7.5% |
| #7 Eggland's Best (class action, "puffery") | 327 | 11.3% | 18.6% |
| #6 Handsome Brook (recall) | 308 | 10.7% | 30.2% |
| #5 Nellie's (class action, undercover) | 263 | 9.1% | 41.7% |
| Like + subscribe ask | 64 | 2.2% | 51.1% |
| #4 Vital Farms | 307 | 10.6% | 53.0% |
| #3 August Egg (recall) | 242 | 8.4% | 63.7% |
| #2 Cal-Maine (DOJ, price-fixing suit) | 459 | 15.9% | 72.2% |
| #1 "The egg aisle itself" + close | 370 | 12.8% | 87.8% |

**Structure points:**
- A countdown with "Eight." … "One." as one-word bridges.
- No worth-it list at all.
- One ask at 51–52% of characters: "Take a second to subscribe and hit the like button. It costs nothing and it sends a message that consumers want the truth."
- The final line is "And remember the truth is not always on the menu." The house tagline is identical to The Hidden Menu's sign-off (fact, no inference).
- Each brand beat uses the same five jobs:
  1. who they are (scale, revenue);
  2. the label words quoted;
  3. the legal record, mostly labelled "alleges";
  4. a money comparison;
  5. a rhetorical closer.

Everything in it is U.S. (rule 7). Its recall and salmonella beats (#6, #3) and its "price-fixing" framing (#2) are barred under rules 1 and 6 in any Canadian adaptation.

### 1f. Steak and Butter Gal, "Avoid These 5 EGG Brands At ALL Costs (And 3 That Are Actually Safe to Eat)" (345K). U.S.; structure only

| Beat | Words | Share | Starts (c%) |
|---|---|---|---|
| Cold open ("I'm going to do two things") | 104 | 2.2% | 0.0% |
| Myth 1: brown vs white | 246 | 5.1% | 2.0% |
| Myth 2: washing / cuticle + comment ask | 214 | 4.5% | 7.0% |
| Sponsor 1 | 222 | 4.6% | 11.5% |
| Myth 3: yolk colour (DSM yolk fan) | 384 | 8.0% | 16.0% |
| Myth 4: dates (USDA Julian date) | 358 | 7.5% | 24.2% |
| Myth 5: badges / certifiers | 418 | 8.7% | 31.0% |
| Inside the egg (nutrition) | 271 | 5.7% | 39.8% |
| Sponsor 2 | 451 | 9.4% | 45.5% |
| Brands 1–5 (Eggland's, Vital Farms, Quality Egg / DeCoster, August Egg, Cal-Maine) | 1,693 | 35.3% | 55.0% |
| Global + "3 things to look for" + close | 430 | 9.0% | 91.0% |

**Structural lesson:** the "five things about the industry" myth-buster block (36% of the video) comes before the brands. Its one transferable device is myth 5: who certifies a label and who pays the certifier. In Canada, P4 (claims must be substantiated, for example by third-party audit) and P20 (organic certification) are the lawful equivalents.

Almost everything else is barred for CC: nutrition, "inflammation", salmonella, recalls, prosecutions, "safe to eat", U.S. rules, and the sponsor reads.

### 1g. Cross-format table

| Video | Views | Words | First brand at (c%) | Order basis stated? | Asks (c%) | Worth-its rest on | Dated fact in first sentence? |
|---|---|---|---|---|---|---|---|
| CC eggs Apr | 121K | 3,172 | 6.7 | No (implied "largest first") | Sub 62.9 | Nutrition | No |
| CC eggs Aug | 4.4K | 3,752 | 15.2 | No | Like 48.4, Sub 66.0, Comment 98.4, Share 99.3 | Categories (free range, organic, certification) | Yes, but U.S. ("March of last year") |
| CC olive Sep | 16.7K / 6 d | 3,864 | 16.5 (after 462-w yardstick) | Countdown, worst last | Like 48.4, Comment 98.0 | Checkable label facts + price | Yes (CFIA, "last year") |
| CC jam Sep | 8.4K / 5 d | 3,770 | 12.1 | Yes, shelf presence | Like 55.4, Comment 96.5 | Label facts + price | Law number in s3; price date in s8 |
| Hidden Menu | 349K | 2,885 | 7.5 | Countdown | Like + Sub 51.1 | n/a | Yes ("early 2025", U.S.) |
| SBG | 345K | 4,791 | 55.0 (brands); 2.0 (myths) | No | Comment 11.4; sponsors | Nutrition | No |

---

## 2. Why the April video hit and the August video flopped (facts only; no retention or CTR data was available)

### 2a. Title construction

| Video | Title | Construction | Views |
|---|---|---|---|
| CC Apr | 7 Egg Brands Sold in Canada You MUST AVOID (And 2 That Are Actually Worth It) | Number + staple + "Sold in Canada" + CAPS imperative + a positive payoff in the parenthesis | 120,992 |
| CC Aug | Canadians Must AVOID These 7 Egg Brands (Only 3 Are ACTUALLY Real Eggs) | Nationality-first imperative + a parenthesis claiming most eggs are not "real". The script disowns this at s26–27. verification_log_eggs.md says the title mirrored Protect Our Plates' "DON'T Buy These 7 Egg Brands (Only 3 Are ACTUALLY Real Eggs)". | 4,355 |
| Hidden Menu | 8 US Egg Brands You Must Avoid | Number + nationality + imperative; no payoff | 348,749 |
| SBG | Avoid These 5 EGG Brands At ALL Costs (And 3 That Are Actually Safe to Eat) | Imperative + count + safety payoff (barred for CC) | 344,635 |

**What the titles show:**
- **The flop's title promised what its script refused.** The August title claims a fake-egg finding that the script itself says does not exist. The April title promises seven brands and two to buy, and the script delivers exactly that.
- **The April title is the channel's proven egg title,** and it is the one this redo keeps.
- **August came four months after the April video on the same topic,** and the April video was still live and still ranking at 121K. The note records this fact only; there are no impression or traffic-source data to say whether the two competed.
- **August was published on a Monday** (17 Aug), nine days after the channel resumed uploading on 8 Aug following a gap from 22 Jun. April was published on a Friday.

### 2b. Thumbnails (viewed 3 Oct 2026 via Algrow `get_video_thumbnail`)

| Video | Thumbnail |
|---|---|
| CC Apr | Factory conveyor of broken eggs, two workers in lab coats with clipboards, a liquid-egg nozzle, a misspelled "BERNBRAE" Solar Free Range carton, and a red "EXCLUSIVE:" tag over "CHEMICALS IN EGGS!" |
| Hidden Menu | The same template, published a month earlier (16 Mar): conveyor, lab coats, nozzle, an Eggland's Best carton, "EXCLUSIVE:" over "CHEMICALS IN EGGS" |
| CC Aug | A hand holding a cracked brown egg, a correctly spelled Burnbrae Naturegg "Solar Free Range" carton on a kitchen counter, and yellow "NOT REAL EGGS?" |
| SBG | Presenter, a Vital Farms Pasture Raised carton, a microscope inset, "THEY THINK YOU'RE DUMB!" |
| CC olive Sep | Split "PURE" (Kirkland) / "DILUTED" (Bertolli) with tick and cross |
| CC jam Sep | Split "FAKE" (Smucker's Pure) / "REAL" (Crofter's) |

**What the thumbnails show:**
- **The hit borrowed a 349K competitor's template.** The April hit used The Hidden Menu's thumbnail template, which was then a month old. The thumbnail asserted "CHEMICALS IN EGGS!" The word "chemical" appears zero times in the April script.
- **The flop put a product it recommends under "NOT REAL EGGS?"** The August thumbnail shows Burnbrae's Naturegg Solar Free Range carton, a product the August script recommends (s215, "Naturegg free range … the clearest"), under "NOT REAL EGGS?".
- **The olive and jam thumbnails also carry a factual risk.** Both label a named product DILUTED or FAKE that their scripts do not say.

**Rule note for the redo.** None of the four egg thumbnail approaches is usable:
- "CHEMICALS IN EGGS" is an implied food-safety or health claim (rule 1).
- "NOT REAL EGGS?" is the fake-egg framing (rule 1).
- "DUMB" and "AT ALL COSTS / Safe to Eat" are safety and character framing (rules 1 and 6).
- See 5a for a factual alternative.

The April thumbnail's contribution to 121K cannot be separated from the title's. That is a known risk of changing it.

### 2c. Framing and what each avoid case rested on

| Video | Framing | What each avoid rested on | Payoff |
|---|---|---|---|
| CC Apr | Third-person "investigation"; company histories; ownership ("the same processor can sell you a product worth avoiding and a product worth buying") | Six of seven rested on the single unsourced sentence that the brand's standard eggs come from "conventional or enriched cage production". Burnbrae rested on Mercy For Animals material (2013 W5 footage; a 2024 reporting critique). | Both worth-its rested on nutrition (GoldEgg DHA and lutein; YVF vitamins D and E via CBC Marketplace). Two of the nine brands drew "never seen it" comments from BC, the GTA and Montreal. |
| CC Aug | U.S. crisis, then "the carton words"; defined "real" as "the carton's promise matches the hen's actual life" | Label words against company copy (Nestlaid "furnished cage"); a freshness claim (Prestige); consolidation (P&H); nutrition (omega-3); a definition gap (free run vs free range); a missed retailer pledge. Three of the seven are not brands. | Categories, not brands. Food-safety content (washing, "dangerous", "unsafe", bacteria) and nutrition throughout. 7 comments in seven weeks. |

### 2d. Measurable facts on placement and length

- **Length.** April ran 20:18 at 3,172 words; August ran 23:53 at 3,752 words. The hit was the shorter, and its comments still called it long.
- **Time to first brand.** April reached its first brand at 6.7% of characters; August at 15.2%, after 575 words of U.S. context and definitions. Olive reached its first brand at 16.5% (after its yardstick), and that video is still performing, so time to first brand alone does not decide.
- **Asks.** April had one ask (subscribe, 62.9%). August had four (like, subscribe, comment, share).
- **Health and food-safety vocabulary**, counted in the clean text:
  - April: "nutri" 19, "vitamin" 8, "omega" 6, "health" 3, "protein" 1.
  - August: "real" 12, "omega" 9, "vitamin" 5, "bird" 4 (bird flu), "protein" 3, "nutri" 3, "fake" 1, "cholesterol" 1, "safe" 1.

---

## 3. Every line in the April and August egg videos that the redo must not repeat

Codes:
- **R1**: health, nutrition, omega-3-as-benefit, salmonella, avian-flu-as-risk, food-safety or "fake egg".
- **R6**: states or implies wrongdoing or motive.
- **R7**: U.S. or U.K. data, or U.S. framing.
- **U**: unsourced or not verified today.
- **X**: contradicted by a source opened today.
- **W**: an animal-welfare characterisation that is not literal code or company wording.

### 3a. April 17 video (tr_CC_eggs_apr2026_121K, eggs_num_ file)

| s# | Line (abridged) | Code | Note |
|---|---|---|---|
| 2 | "whether the cheerful farm imagery has anything to do with how the hens … actually live" | R6 (implied) | Rephrase as a label-reading instruction |
| 4 | "an animal protection organization found in 2024 that it was grouping caged hens … in a way that blurred…" | R6, W, U | Advocacy material presented as a finding |
| 6 | "the healthiest recommendation … double the vitamin D and three and a half times the vitamin E" | R1 | |
| 9 | "founded in 1891 … Joseph Hudson … Stranraer … Lyn … 100 acre farm" | U, X? | Burnbrae's site was blocked today. The Loblaws listing of Burnbrae eggs (P12) says "Since 1893". Do not state a year until captured from burnbraefarms.com. |
| 11 | 1940s, 50 hens, high-school project | U | |
| 12 | "sixth generation … majority female owned … Margaret Hudson as president … certified women's business enterprise" | U | Company claim; capture and attribute or drop |
| 13 | "largest integrated family owned egg company in Canada with eight grading stations, three processing plants, and seven wholly owned farms across five provinces" | U | Company claim; capture and attribute. "Largest" by market share is not published. |
| 17–18 | Mercy For Animals 2013, W5, named supplier farms, "hens in conventional battery cages", Burnbrae suspended purchases | W, R6, U | Advocacy plus investigation footage |
| 19–22 | MFA 2024 critique ("~49% … by 2022", "grouping enriched cages"); enriched cages "do not allow hens to … engage in normal foraging or dust bathing" | W, R6, U, X | NFACC s. 2.5 (P8) says all housing systems hens are transitioned to "must support nesting, perching, and foraging (pecking and scratching) behaviour" |
| 24 | "the transparency consumers would need … is not provided" | R6 | |
| 26 | No Name "introduced in 1978" | U | Probably correct; source it from Loblaw or drop it |
| 28 | No Name eggs "sourced from conventional or enriched cage production, the standard housing that Egg Farmers of Canada is working to phase out by 2036" | U, X | No source for No Name housing. Enriched housing is not being phased out: NFACC (P8) allows "enriched cage or non-cage" after July 1, 2036. |
| 29 | phase-out "because … the industry recognized that this no longer aligned with animal welfare science or consumer expectations" | R6 (motive), U | The ~90% figure is supported by CBC 2016 (P18) |
| 30 | "precisely the category that the industry itself has identified as requiring replacement" | X | Same error as s28 for enriched |
| 31 | No No Name cage-free or free-range option | Partly verified | No such SKU was found at four Loblaw-banner stores on 3 Oct (P12). Say "we didn't find one at these stores on this date", not "doesn't offer". |
| 32 | "the housing most associated with the welfare concerns" | W | |
| 35 | Walmart "more than 400 locations" | U | |
| 37–41 | Great Value "sourced from conventional or enriched cage production"; "nutritionally differentiated" | U, R1 | |
| 45 | Lyle Gray "in the basement of his parents' house" | U | Not on P14 |
| 47 | Listowel, Strathroy, Calgary, Abbotsford grading facilities | U | P14 says "multiple … facilities in Southwestern Ontario" only |
| 48 | Gray Ridge "acquired by P and H Foods Inc." | X (wording) | P14: "partnered with Parrish & Heimbecker … what is now P&H Foods Inc." Use the company's words. |
| 49 | Gray Ridge eggs "are conventional and enriched cage eggs … the bottom of the welfare tier" | U, W | |
| 52–53 | Gray Ridge and Burnbrae "estimated to control a substantial portion" | U | No source |
| 55 | PC "launched in 1984" | U | |
| 57–60 | Standard PC eggs from "conventional or enriched cage production", "does not translate to … nutritional differentiation" | X, R1 | Loblaw (P11): "100% of PC® shell eggs are now entirely free-run and/or free-range". The product page agrees. |
| 62 | (caption garble) | n/a | |
| 64–65 | Sobeys banners; "approximately 1,600 stores" | U | |
| 66–67 | Compliments standard eggs "conventional or enriched"; "nutritional profile" | U, R1 | |
| 68–70 | "The grocery duopoly that controls much of Canadian food retail" | R6 (characterisation), U | |
| 71 | "researched from … independent nutritional testing" | R1 | |
| 79 | Conestoga "references Conestoga wagon country in … Waterloo region" | U | |
| 80 | Conestoga sells free run, free range and organic | Partly verified | Free run and free range Omega-3 SKUs are at Loblaws 1032 (P12); organic was not seen |
| 82 | The standard Conestoga caged egg "is the most widely purchased item under the brand" | U | No sales data |
| 90 | GoldEgg is a P&H-family brand | Verified | P14 lists GoldEgg among Gray Ridge's brands |
| 94–103 | GoldEgg diets, DHA "125 mg", "lutein for eye health", "nutrients that matter" | R1 | All of it |
| 104 | "The healthiest recommendation" | R1 | |
| 106–108 | YVF founded 2010 by two eastern Ontario farming families; 30+ farms; 2,300 acres | Verified (P17) | The "Arens family farm near Peterborough … organically for more than 30 years" detail is U |
| 109–110 | Pro-Cert certification | Verified (P17) | |
| 111–113 | Open-concept barns, seasonal pasture; feed "never treated with herbicides or pesticides"; pasture program "minimum of 6 hours" | U | Capture from YVF or drop |
| 114–116 | CBC Marketplace 2021 lab nutrition; "lowest in saturated fat" | R1 | |
| 117 | Canadian Organic Trade Association "organic supplier of the year in 2018" | U | |
| 118 | "nutritional profile" | R1 | |
| 119 | "the egg industry has structured itself to keep it that way" | R6 (motive) | |
| 122 | "adds nutritional formulation that justifies the carton" | R1 | |

### 3b. August 17 video (tr_CC_eggs_aug2026_4K, eggs_num_ file)

| s# | Line (abridged) | Code | Note |
|---|---|---|---|
| 1–5 | U.S. "lost its mind", "Bird flu had torn through American mega-farms", $6.23 U.S., "nearly $9 Canadian", California $9, Waffle House, rationing | R7, R1 (avian flu), U (conversion) | |
| 6–8 | 3,254 U.S. egg seizures vs fentanyl 134; "much of it coming through Detroit from Canada" | R7 | U.S. CBP data via CBC. It also frames Canadian eggs as smuggled. |
| 9 | Windsor Walmart $3.93 vs Michigan "about $8.50 Canadian" | Rule 5 | Prices not from the retailer's own site / app / flyer |
| 10 | StatCan band $4.26–$4.95 over 30 months | Verified (P6) | Jan 2024–Jun 2026: min $4.26 (Mar 2024), max $4.95 (Jul 2025) |
| 12–13 | USDA letters to European associations; Turkey ~420 million eggs | R7 | |
| 14 | The Logic: Niagara Falls No Frills shoppers "recognizable … by their accents"; "$300 US fine" | U (paywalled), R7 | |
| 17 | ~1,300 farms, ~22,000 hens each | Verified (P7) | 1,295 farms; average 22,069 layers |
| 18 | Cal-Maine 44 million hens "more than every laying hen in Canada combined" | R7 | U.S. company figure; derived comparison |
| 19–20 | "When disease hits a Canadian farm, we lose a barn…" | R1 (avian flu as risk) | |
| 21 | "not going to tell you Canadian eggs are fake, or dangerous" | R1 | Raising "fake" and "dangerous" at all is barred |
| 22 | "the best run egg supply in North America, and we can prove it with a chart" | U (superlative) | |
| 24 | "worth up to $5.50 a dozen every single week for the rest of your life" | U | No calculation shown |
| 26–34 | "every egg in this video is a real egg … Nobody is counterfeiting breakfast"; the "real" definition | R1 (fake-egg framing) | The title's "Real Eggs" is the problem |
| 35 | "$3.93 tray" | Verified today | No Name Large 12 is $3.93 at Loblaws 1032 and No Frills 7952 (P12) |
| 39 | Air cell ≤5 mm; "checked by rolling every single egg over a bright candling light on a conveyor" | Partly verified | The 5 mm limit and the candling definition are in P5. "every single egg … on a conveyor" is U. |
| 43–51 | Washing "in temperature and acidity-controlled water", cuticle, Europe, "the same bacteria", "genuinely dangerous", best-before "not when it becomes unsafe" | R1 (food safety) | All of it |
| 57, 59 | "The classic carton is where those eggs go"; "the answer is the housing nobody prints" | U | Inference |
| 61–63 | "cheapest honest protein", Marketplace "protein, cholesterol, and most vitamins" | R1 | |
| 65 | "the silence on the box is not an accident" | R6 (motive) | |
| 68 | "Canada's biggest egg company" | U | Market share is not published |
| 75 | Burnbrae: "free to perch, scratch, and lay their eggs in a curtained nesting area in a furnished cage environment" | U today | Search snippet only (burnbraefarms.com 403). Capture before use. |
| 78–79 | "each hen is guaranteed 750 square centimeters … including the nest"; "smaller than a sheet of legal paper per bird for life" | Partly verified; W | The 750.0 cm² figure is in P8. The paper comparison and "for life" are editorial. |
| 80 | EFC "the business class of hen housing" | U | Not found on the pages opened |
| 83 | "advocacy survey … only 11%" | U, not tier (d) | Advocacy, no methodology |
| 88 | "Polling has found 80% … three quarters" | U | Needs publisher, date and methodology (tier d) |
| 89–92 | Animal Justice 2024 "largest egg industry investigation" linking cartons "including this one" | R6, W | |
| 96 | "accurate to regulators and pastoral to you at the same time, on purpose" | R6 (motive) | |
| 103 | "the same trap the UK's fanciest supermarket eggs run" | R7 | |
| 113 | P&H "as of May 2025 … quietly completed its purchase of the entire Grey family egg empire" | U (date), R6 ("quietly") | P14 gives no date |
| 115 | "two companies, Burnbrae and P&H, grade and pack the overwhelming majority of everything on the shelf, including most store brands" | U | |
| 117–118 | Island Gold, Jensen family 1951, Burnbrae-owned since 2007 | U today | islandeggs.com 403 |
| 120 | "Look past the logo to the fine print, where the grader's identity lives" | X (as a rule) | SFCR 218(1)(b) requires the name of the person "by or for whom". The No Name carton names "LOBLAWS INC." (P13), not a grader. |
| 124–147 | Omega-3: ALA, DHA "the form your brain actually wants", salmon, flax, McGill and dietitians, "very small amount of flax, beautifully marketed", "fish counter" | R1, R6 | All of it |
| 126 | PC Blue Menu omega-3 free run $7.49 vs No Name $3.93 | Stale | Today PC Blue Menu Free-Run Brown is $7.99 at Loblaws 1032 (P12) |
| 138–140 | Lutein / marigold, "golden orange yolk can be dialed up" | R1 (adjacent), rule 8 | Yolk colour is opinion territory |
| 142–143 | CFIA's word "enhanced", "vitamin D cartons" | R1 | P3 defines "enhanced" as a nutrient term. Do not explain it on air. |
| 144 | Burnbrae Omega Plus "solar-powered barns with free-range hens" | Partly verified | P12 lists "Naturegg Omega Plus Solar Free Range Eggs". Capture the Burnbrae page for "solar-powered barns". |
| 151–152 | EFC: free range "when weather permits, go outside to pasture"; free run "roam the entire barn floor" | Verified (P9, close wording) | P9 says free range hens "roam the barn floor, and when weather permits they go outside". It does not say "pasture". Quote P9 exactly. |
| 157 | "the phrase was chosen, brilliantly, to sound identical" | R6 (motive) | |
| 159–164 | "Neither term is defined in Canadian law … honor system … No pre-market review" | Partly verified | P3 and P4 contain neither term, and P4 requires claims be "accurate, truthful" with substantiation. "honor system" and "No pre-market review" are characterisations. Say "the CFIA's labelling pages we read do not define either term". |
| 165 | "The industry itself has effectively admitted the gap" | R6 (characterisation) | State P7's program wording instead |
| 166–167 | EFC national Free Range Standards Certification Program | Verified (P7) | Add "approved … in August for implementation in early 2026" |
| 171 | BC: 120 days a year, 6 hours a day | U today | |
| 172 | "that blur was the business model" | R6 | |
| 177–188 | Pledge "quietly missed", "nearly silent", "No press conferences for the target that got quietly redefined", "billion-dollar transition", "Costco Canada was around 21%, Sobeys 17, Loblaws 16", "4/5 caged" | R6, U | Rule 6 allows only the companies' own words against the dated record. The scorecard numbers are advocacy (Mercy For Animals) via Retail Insider (403 today). Loblaw's own page now says "approximately 18% of total category sales" (2025) and a 2030 control-brand target. |
| 195–198 | "these words mean nothing. Farm-fresh, natural, nest-laid, grain-fed, vegetarian-fed … Hens are natural omnivores who are all fed grain anyway" | X, U | CFIA (P3) gives "farm fresh" a specific meaning ("distributed directly from the farm to the store") and says "all eggs are natural". The feed line is U. |
| 200 | "Silence on the carton means cages" | U | Inference; no source ties silence to housing |
| 204 | "Organic means free-range with legal teeth" | Partly verified | P20 6.13.1 a)–b), 6.13.2 a). Quote the clauses instead. |
| 207–209 | "Brown and white are nutritionally identical"; yolk colour "from the feed bag" | R1, rule 8 | Say only that shell colour depends on the hen's breed (P12, Rowe Farms listing) |
| 223–224 | Organic standard "open range … pop holes"; "a third-party certifier audits it annually, by law" | Partly verified | Clause text is in P20. "annually, by law" needs the SFCR Part 13 / COR citation (U). |
| 225 | PC Organics $9.50; Kirkland "roughly $9 something" | Stale, U | Today PC Organics Large 12 is $7.99 and the 30-pack $17.25 at Loblaws 1032. Kirkland not captured. |
| 226–227, 232 | Marketplace "more vitamin E, more vitamin D, even a gram more protein"; "may literally measure better" | R1 | |
| 229 | YVF "Canada's largest organic poultry producer, drawing from over 35 family farms" | X | YVF's own FAQ (P17): "one of Canada's leading organic poultry providers … over 30 … farms" |
| 230–231 | BC SPCA Certified / Certified Humane, "an auditor whose salary does not depend on selling you eggs" | U, R6 (implied) | |
| 233 | Farm-gate price "undercuts the fanciest carton … beating it on every test" | U, rule 5 | |
| 234 | "The best egg in Canada has no brand at all" | Opinion | |
| 236 | Seizure, fentanyl and "nine Canadian dollars" recap | R7 | |
| 237 | "Canadians eat 259 eggs a year each and rising" | U today | Not located in P7's text |
| 240 | "a premium that means young hens rather than happy ones", "30 cent flax", "a cage-free promise that expired without a eulogy" | R1, R6, W | |
| 245 | "companies that read the sales data like scripture" | R6 (characterisation) | |
| 247 | "If someone in your family proudly pays double for brown eggs or farm fresh, send them this" | Fine in substance | Do not reuse the share ask; one ask only |

### 3c. Competitor lines that must not migrate into the redo (U.S.; rules 1, 6, 7)

- **Hidden Menu:**
  - price $6.23 / "past 10";
  - Cal-Maine profits, DOJ probe, "price-fixing", "priced by agreement";
  - Walmart overcharging settlements;
  - Eggland's "puffery";
  - Alder egg settlement;
  - Handsome Brook and August Egg recalls and salmonella;
  - Nellie's beak trimming and male chicks;
  - Vital Farms linoleic acid and sanctions;
  - U.S. "67 square inches";
  - HM s116, "Similar research conducted in Canada in 2024 … only 14%" (no source given).
- **SBG:**
  - brown-egg breed "costs more feed" folklore and Phil Lempert's 10–20%;
  - the U.S. washing / cuticle explanation;
  - the DSM yolk fan and canthaxanthin mg;
  - USDA Julian dates and 30/45-day rules;
  - U.S. certifier space figures;
  - Penn State and pastured-egg nutrition, choline;
  - "linoleic … inflammation";
  - Quality Egg / DeCoster prosecution;
  - August Egg pasteurisation;
  - Cal-Maine EPA settlement and jury verdict;
  - "corn and soy-free", "hard firm shell means healthier hen";
  - both sponsor reads.

---

## 4. What a viewer who saw April needs to be NEW in October (questions for the fact researchers)

Today's partial answers are in brackets.

1. **President's Choice.** Capture Loblaw's responsible-sourcing paragraph (P11) and the PC Free Run product page as screenshots with the date.
   - [P11 and P12: all PC shell eggs free-run and/or free-range.]
   - When did this become true? Find the dated Loblaw ESG disclosure for the year the PC line converted, so the April error can be corrected with a date.
2. **No Name.** Capture the side and back panels of a physical No Name Large 12. Do they print any housing word, a grading-station name or a registration or licence number?
   - [Top panel: none (P13). Name shown: "LOBLAWS INC., TORONTO".]
   - Loblaw's control-brand target is "by 2030" (P11). Does Loblaw publish the current share for No Name?
3. **Burnbrae.** burnbraefarms.com was 403 to curl and WebFetch today; it needs a browser capture. Capture:
   - the founding year: 1891 (April s9) vs "Since 1893" (Loblaws listing);
   - the Nestlaid page ("furnished cage environment" per search snippet) and the Nestlaid carton's printed housing line;
   - the Prestige page ("young hens", "packed to order");
   - the Solar Free Range page;
   - the company-size claims.
4. **Gray Ridge / P&H.**
   - The date and nature of the P&H transaction. P14 says only "Over a decade ago, Bill Gray partnered with … P&H". The August video's "May 2025" is unsourced.
   - Which grading stations pack Conestoga and GoldEgg cartons, and is that printed on the cartons?
   - Is there a conventional (unlabelled) Gray Ridge or Conestoga carton at retail?
5. **Great Value and Compliments** (both in April). Retailer's-own-site prices and carton captures. Use the Walmart route via the Flipp ecom feed or Walmart app, and voila.ca for Sobeys (research_jam.md §0). What does each carton print about housing?
6. **Retailer pledges,** in each company's own current words:
   - Sobeys / Empire Sustainable Business Report 2025 egg line (403 today);
   - Metro;
   - Walmart Canada;
   - Costco Canada.
   - Against the 18 Mar 2016 record (P18, P19); the RCC release itself was 403 today.
7. **EFC free-range certification.** Is the "Free Range Standards Certification Program" (P7: "implementation in early 2026") live? Is there a carton mark a viewer can look for?
8. **Organic.**
   - The SFCR Part 13 provisions and the Canada Organic logo rules (certification by a CFIA-accredited body).
   - Re-open P20 directly; my curl got a non-PDF page.
   - Is CAN/CGSB-32.310-2026 in force for eggs sold now, or only from a later date? The note at 6.13.3 d) mentions "as of December 2026".
9. **YVF ownership.** A search result (PE Hub headline, paywalled) says "Premium Brands acquires majority stake in Yorkshire Valley Farms" (2018).
   - Confirm from Premium Brands Holdings' own release or annual report before any "family" framing.
   - Find where YVF eggs are sold. April's comments said BC, the GTA and Montreal shoppers had never seen them.
10. **StatCan.** Does Table 18-10-0245-01 add August 2026 before air? [Release 2 Sep 2026 covered July.]
11. **Import / TRQ.** EFC (P7) says production rose ~7.6% in 2025 and "reduced the need for imports beyond existing trade agreements". The CBSA / Global Affairs TRQ notice for shell eggs is optional. A copy of Customs Tariff chapter 4 is in scratchpad/eggs/ch04.txt from the parallel dossier; not opened by me.

---

## 5. Recommended skeleton for the redo

### 5a. Targets, title, thumbnail

- **Length.** 21,000–23,000 characters of plain spoken prose. At 6.0–6.15 c/w, that is about 3,550–3,800 words. The skeleton below totals 3,625 words: about 21,750 characters at 6.0 c/w, or 22,290 at 6.15.
- **Run time.** About 22–23 minutes at 156–160 wpm.
- **Title** (identical to the April hit): **7 Egg Brands Sold in Canada You MUST AVOID (And 2 That Are Actually Worth It)**
  - The April video with the same title is live at 121K. The user should decide whether to unlist or retitle it. No data says which is better; the fact is noted.
- **Thumbnail.** Two real cartons photographed side by side on a shelf: the No Name Large 12 and the most expensive avoid in the final roster. Each gets a per-egg price tag from the retailer's own site ("32.8¢" / "74.9¢", banner and date in small type). Over them: "SAME GRADE A. WHAT'S THE 42¢?"
  - The claim is checkable: both are Canada A (P3: Canada A eggs carry the maple-leaf grade name on the carton top).
  - Do not use: "EXCLUSIVE", "CHEMICALS", "NOT REAL", "FAKE", "DILUTED", "DUMB", factory or lab imagery, broken eggs, or any product the script recommends.

### 5b. Order basis, stated in the open and as a lower-third on every item

"Seven cartons, cheapest egg first, at one Loblaws in Toronto on [date], then the two we'd actually buy."

- **Why this basis.** It is documentable from the retailer's own site (P12), store and date stated. It needs no market-share data, which is not published, so "biggest egg company first" cannot be documented. It also makes the price-per-egg habit the spine of the video.
- **Lower-third on each item:** "#N · [brand, product] · [price] for [count] = [¢]/egg · Loblaws [store], Toronto · checked [date]".
- **Cross-check.** Read the No Frills 7952 and one Superstore price aloud where they differ by more than 2¢ per egg.

### 5c. Eligibility for a slot (avoid or worth it)

A slot needs all three of:
1. a retailer's-own-site price with pack count;
2. a photographed carton (top and side) whose printed words are read on air;
3. at least one tier (a) document that gives those words a legal or company meaning: SFCR or CFIA (P2, P3, P5), NFACC (P8), EFC (P7, P9), CGSB (P20), or the company's or retailer's own page.

Nothing from advocacy groups, scorecards, Reddit or deal blogs can carry a slot.

An "avoid" is a carton where the price-per-egg step-up buys words that the law or the company's own page defines more narrowly than the carton implies, or where the carton says nothing a buyer can check. It is never "bad eggs", never health, never motive.

### 5d. Jobs in every avoid item (fixed order)

| # | Job | Words |
|---|---|---|
| 1 | Bridge + lower-third: number, product, ¢/egg, store, date | 15–20 |
| 2 | Read the carton's top panel aloud (grade, size, the claim words) | 30–50 |
| 3 | What those words mean, in the regulator's, code's or company's own words (on screen) | 50–90 |
| 4 | The price-per-egg comparison against the nearest checkable alternative on the same shelf | 30–50 |
| 5 | Concession, in the company's or retailer's words ("full credit", olive and jam style) | 20–40 |
| 6 | "The habit from number N": one check the viewer can do at the shelf | 15–25 |
| 7 | Closer: one line, with no "quietly", "secretly", "trick", "on purpose" or "business model" | 10–15 |

### 5e. Word budgets and positions

| # | Beat | Words | Starts at word | Start % |
|---|---|---|---|---|
| 1 | Cold open (dated fact) + tagline (1st use) | 150 | 0 | 0.0% |
| 2 | Method, order basis, April acknowledgement, disclosure | 140 | 150 | 4.1% |
| 3 | Yardstick: four things on every carton (grade/size on top; housing words; the name the law requires; price ÷ count) | 180 | 290 | 8.0% |
| 4 | Avoid #1 (cheapest ¢/egg) | 260 | 470 | 13.0% |
| 5 | Avoid #2 | 230 | 730 | 20.1% |
| 6 | Avoid #3 | 230 | 960 | 26.5% |
| 7 | Avoid #4 | 330 | 1,190 | 32.8% |
| 8 | Avoid #5 | 300 | 1,520 | 41.9% |
| 9 | Avoid #6 | 250 | 1,820 | 50.2% |
| 10 | Interlude: "free run, free range, organic: three words, three rulebooks" | 200 | 2,070 | 57.1% |
| 11 | **Mid-list ask (only ask before the end)** | 50 | 2,270 | **62.6%** |
| 12 | Avoid #7 (highest ¢/egg) | 260 | 2,320 | 64.0% |
| 13 | Turn | 60 | 2,580 | 71.2% |
| 14 | Worth it #1 | 260 | 2,640 | 72.8% |
| 15 | Worth it #2 | 230 | 2,900 | 80.0% |
| 16 | Run-back (one line per carton, ¢/egg) | 100 | 3,130 | 86.3% |
| 17 | How to protect yourself (four steps) | 260 | 3,230 | 89.1% |
| 18 | Moral + comment ask + tagline (2nd use) | 90 | 3,490 | 96.3% |
| 19 | Disclaimer | 45 | 3,580 | 98.8% |
| | **Total** | **3,625** | | |

- **Ask position.** The ask starts at word 2,270 of 3,625 (62.6%). At an even c/w that is about 13,620 of 21,750 characters.
- **Measuring the draft.** Measure the finished draft in characters. If the ask falls outside 61–63%, move words between beats 3 and 10. Never move them into the ask.

### 5f. Cold open (about 150 w), method beat (140 w), yardstick (180 w)

**Cold open, six moves:**
1. Dated fact, first sentence (P6): "In July 2026, Statistics Canada's average price for a dozen eggs was $4.95. That ties the highest month in a table that starts in January 2017, when it was $3.01." That is about 41¢ an egg.
2. Second dated fact (P7, 18 Mar 2026 report): "As of mid-2025, 39.45% of Canada's laying hens were in conventional cages and 39.33% in enriched colony housing." These are EFC's words; say "conventional cages" exactly as printed.
3. The carton problem: the top of the cheapest carton in Toronto prints a grade, a size, a count and a store's address, and nothing about where the hen lived (P13). This is a description, not an accusation.
4. Method: one Loblaws, one date, price ÷ count, then the carton, then the rulebook.
5. Count and order basis.
6. Tagline, first of two uses.

Draft (about 150 w):

> "In July, Statistics Canada's average price for a dozen eggs hit four ninety-five. That ties the highest month in a table that goes back to 2017, when the same dozen was three dollars and a penny. That's about forty-one cents an egg. Egg Farmers of Canada's own report says that as of last summer, thirty-nine percent of Canada's laying hens were in conventional cages, and another thirty-nine in what it calls enriched colony housing. Now pick up the cheapest carton at a Toronto Loblaws. On top: a grade, a size, a count, and the store's address. So we did what the carton doesn't. Seven cartons, cheapest egg first, priced off the store's own site on one day, every word on the lid checked against the rulebook it comes from. Then the two we'd actually buy. Because the truth is not always on the menu."

- Recheck the StatCan figure on air day. If August 2026 is out, use it and re-date.
- No ask, no "secret", no health word, no U.S. content.

**Method beat (140 w):**
- State the order basis (5b).
- April acknowledgement, said plainly. Draft: "In April we made a video with this exact title. Two things in it we can't stand behind today. We said President's Choice's standard eggs came from cages; Loblaw's own page now says every PC shell egg is free-run or free-range. And we said enriched housing is being phased out by 2036; the national code says enriched cages are still allowed after that date. This video replaces it."
- Disclosure, spoken once, here only: "We have no commercial relationship with any egg farm, grader, brand or grocer named in this video, and none of them knew it was being made."

**Yardstick (180 w), four things on every carton:**
1. **Grade and size on the lid** (P2 s. 314, P3, P5). Canada A means an uncracked shell, a reasonably centred yolk and an air cell no deeper than 5 mm on candling, plus a weight band. Every carton in this video says Canada A. Grade is not a ranking between cartons; it is the price of entry.
2. **The housing words, or their absence.** EFC's own definitions (P9) for conventional, enriched, free run and free range. The CFIA's labelling pages we read define neither free run nor free range (P3, P4). Organic is the only one with a federal standard behind it (P20).
3. **The name the law requires** (SFCR 218(1)(b)): the person "by or for whom" the eggs were packaged or labelled. On a store brand that may be the store.
4. **Price ÷ count.** Write the cents per egg on your hand. "We'll use it nine times."

### 5g. The seven avoids: a provisional roster in price-per-egg order (Loblaws 1032, 3 Oct 2026)

Researchers must confirm each carton physically. Any slot whose carton capture fails rule 5c is replaced by the next carton in ¢/egg order from 0c. Great Value and Compliments should be priced and captured, and they take a slot if their cartons fit 5c.

| # | Carton | ¢/egg (3 Oct) | What the case rests on (tier a only) | Concession | Habit |
|---|---|---|---|---|---|
| 1 | No Name Large 12 | 32.8 ($3.93) | Lid prints no housing word; the name shown is "LOBLAWS INC., TORONTO" (P13; SFCR 218(1)(b) explains why). Loblaw's own target for control-brand eggs is "alternatives to the standard 'battery' cage by 2030" (P11). Say only that the carton doesn't tell you. | Cheapest Canada A egg on the shelf; Loblaw publishes its target | Read the address: it tells you who sells it, not who graded it |
| 2 | Burnbrae "Grade A Large Eggs" 18 (Prestige Club Pack) | 38.8 ($6.98) | Lid: "Prestige", "First choice for chefs", "Since 1893" (Loblaws listing). CFIA permits "specially selected from young hens" claims (P3). Read Burnbrae's own Prestige wording once captured. No housing word on the lid (P13). | A named family company, 6¢ per egg more than No Name, and says what it is selling | A quality word is not a housing word |
| 3 | No Name Large **Brown** 12 | 52.4 ($6.29) vs 32.8 white | Same brand, same grade, same size: +19.6¢ per egg (+60%). Shell colour "depending on the breed of the hen" (Rowe Farms listing on loblaws.ca, P12). No nutrition comparison at all. | None needed | Compare the same brand in white and brown before you pay for colour |
| 4 | Naturegg Nestlaid Omega 3 12 | 54.1 regular ($6.49 NF); 50.0 on special at Loblaws | Printed line (to capture) "hens raised in enriched colony housing equipped with perches and nesting areas"; Burnbrae's own "furnished cage environment" (capture). NFACC: 750.0 cm² per hen including nests, and enriched cages remain permitted after July 1, 2036 (P8). EFC: 39.33% of hens in enriched colony (P7). "Omega 3" is read as the printed product name only. | Burnbrae prints the housing line on the lid; enriched is the code's permitted system | If the lid says "colony", "enriched" or "furnished", that is a cage under the national code's own vocabulary ("Enriched Cage", P8) |
| 5 | Conestoga Brown Free Run Omega-3 18 | 58.3 ($10.49) | Gray Ridge's own words: Conestoga is "Ultra-wholesome, hyper-local Ontario eggs", and Gray Ridge sells it alongside Gray Ridge and GoldEgg under what is now P&H Foods (P14). "Free run" means "hens roam the entire barn floor" (P9), with no outdoor access in the definition. | Free run is out of cages; Foodland Ontario certifies origin (P14) | Three brands, one grader family: read the side panel for the grader's name |
| 6 | PC Blue Menu Free-Run Brown Large 12 vs PC Free Run Brown Large 12 | 66.6 ($7.99) vs 59.6 ($7.15) | Same retailer, same housing word, same size, both brown: +7¢ per egg for the Blue Menu line. Its listing's difference is a nutrient claim, which this channel will not discuss (say so, jam s141 style). Loblaw: all PC eggs free-run or free-range (P11). | Both are cage-free per Loblaw's own page | When two cartons share the housing word, the price gap is buying something else; ask what |
| 7 | Conestoga Brown Free Range Omega-3 Large 12 | 74.9 ($8.99), the highest non-organic ¢/egg at Loblaws 1032 | "Free range" per EFC = barn floor "and when weather permits they go outside" (P9). EFC's own national Free Range Standards Certification Program was "approved … in August [2025] for implementation in early 2026" (P7): does the carton show it? On the same shelf, PC Organics Free-Range 30-pack is 57.5¢, and organic under CGSB prohibits "row, battery, enriched or colony cages" and requires outdoor access "for at least one third of its laying life" (P20). | The door exists per EFC's definition | Compare free range to organic per egg before you pay for the word |

**Interlude (200 w), "three words, three rulebooks", placed after #6 and before the ask:**
- Free run: P9.
- Free range: P9, plus EFC's 2026 certification program (P7).
- Organic: P20 clauses, quoted; the certification requirement to be cited from SFCR Part 13 once captured.
- CFIA's own positions on "fresh", "farm fresh" and "natural" (P3), read verbatim. This replaces the August line "these words mean nothing", which P3 contradicts.

### 5h. Mid-list ask (50 w), at 61–63% of characters

Draft:

> "One left before the two we'd buy, and it's the most expensive non-organic carton on that shelf. If you want the next grocery aisle read like this before you pay, take a second to subscribe. Canadian Counter reads the label so you don't have to. Number seven."

- Must contain "take a second to subscribe".
- No like ask, no share ask.

### 5i. The turn (60 w) and the two "actually worth it" (260 + 230 w)

**The turn.** "Two cartons we'd actually put in the cart. Neither is the cheapest. Both print what they are, and both have a rulebook behind the word."

**Worth it #1: PC Organics Free-Range Large Brown, 30-pack.**
- Price: 57.5¢ at Loblaws 1032 ($17.25); 58.3¢ at No Frills 7952; 56.6¢ at both Superstores ($16.99).
- The case:
  - "organic" is the one carton word with a national standard behind it: P20 6.13.1 a) and b), 6.13.2 a) and c);
  - the 30-pack is cheaper per egg than several free-run and free-range cartons on the same shelf (0c);
  - Loblaw's own listing says the eggs "come from free-range hens" (P12).
- Concession: a 30-pack is a lot of eggs. Do the per-egg math on the 12 too (66.6¢).
- No nutrition, taste or yolk comparison.

**Worth it #2: research pick between two candidates, by the same test.**
- **(a) Burnbrae Organic Free Range 18:** 63.8¢, the same $11.49 at three stores (P12).
- **(b) Burnbrae Naturegg Solar Free Range 12:** 62.5¢ on special, 68.3¢ regular. The listing says "Laying hens housed in an open concept barn with outdoor access" (P12).

Pick whichever carton's capture shows its housing words and any certification mark. Option (b) also corrects the August thumbnail, which put this exact carton under "NOT REAL EGGS?".

Concession line: Burnbrae prints both the most specific housing line in the avoid list (#4) and this one. Same company, different carton (the April "product, not parent" lesson, kept).

Do not use Yorkshire Valley or GoldEgg as worth-its:
- both April picks rested on nutrition;
- April viewers said they could not find them;
- YVF ownership is U.

### 5j. Run-back (100 w)

One line per carton: product, ¢/egg, and the one word that decides it. Use the olive run-back cadence ("No name tells you nothing, which is honest.").

### 5k. How to protect yourself (260 w). Four steps: "First," "Second," "Third," "Fourth"

1. **First, read the grade and the housing words.**
   - The grade is on the lid by law (SFCR 314(1)(a)), inside a maple leaf for Canada A (P3). It sets a floor, not a ranking.
   - Then look for a housing word: conventional / no word, enriched / colony / furnished, free run, free range, organic.
   - No word means the lid has not told you (P13). Do not say "means cages" (U).
2. **Second, find who the carton names.**
   - The law requires the name and principal place of business of the person "by or for whom" the eggs were packaged or labelled (SFCR 218(1)(b)).
   - On a store brand that is often the store (P13).
   - Some cartons also name a grading station or farm on the side. If yours does, that's who graded it.
   - Grading stations are "registered and inspected by the Canadian Food Inspection Agency" (P10).
   - Do not promise a licence number until a capture shows one (U).
3. **Third, know what the label words legally mean.**
   - Free run and free range: EFC's definitions (P9). The CFIA's labelling pages we read do not define either (P3, P4). EFC's free-range certification (P7).
   - Organic: CGSB clauses (P20) plus certification.
   - "Farm fresh", "fresh", "natural", "young hens": CFIA's own positions (P3).
   - Never explain "Omega-3" or "enhanced". Read them as printed names only.
4. **Fourth, compare price per egg.**
   - Shelf price ÷ count, in cents. $3.93 ÷ 12 = 32.75¢; $17.25 ÷ 30 = 57.5¢.
   - Compare within the same housing word first, then across words.

### 5l. Moral, comment ask, tagline (90 w)

- **Moral:** "The grade on the lid is the floor (confirm on the captures that all nine cartons read Canada A before saying 'every'). What you pay above it should buy a word you can check: on the lid, in a rulebook, in cents per egg."
- **Comment ask, framed as the viewer's own data:** "Pick up your carton and tell us in the comments: the brand, the housing word on the lid (or none), the price, the count and your province. We'll do the per-egg math for a few of you."
- **Tagline, second and last use:** "Because the truth is not always on the menu."

### 5m. Disclaimer (about 45 w), spoken last and shown on screen

> "Prices in this video were taken from the retailers' own websites on [date] at the named stores and change often. Label wording is read from cartons and company pages checked on [date]. Nothing here is health, nutrition or food-safety advice. Read your own carton before you buy."

That is 46 words. Do not add "Not sponsored"; the disclosure in 5f is the single use.

### 5n. Vocabulary rules for the body

- **Never use:** fake, real egg(s), chemical(s), dangerous, safe, unsafe, safety, bacteria, salmonella, bird flu, avian, disease, healthy, health, nutrition, nutrient, vitamin, protein, cholesterol, omega-3 as a benefit, DHA, lutein, "for your brain", cruel, cruelty, humane, inhumane, suffering, battery (except quoting Loblaw's "standard 'battery' cage" or CGSB's "battery … cages"), secret, hidden, quietly, trick, business model, on purpose, duopoly, cartel, monopoly, scam, caught, exposed.
- **Every company statement is attributed:**
  - "Loblaw's page says";
  - "Burnbrae's page says";
  - "Gray Ridge says";
  - "EFC's annual report says";
  - "the national code says".
- **Every legal or regulatory statement names the instrument:** SFCR section, CFIA page, Compendium Vol. 5, NFACC section, CGSB clause.
- **No U.S. or U.K. content.**
- **Recalls:** none in the script. Any recall raised in research goes to an appendix marked "DO NOT USE ON AIR".
- **Animal welfare** is stated only as the code's, EFC's, CGSB's or the company's literal words and numbers (750.0 cm², 1,900.0 cm², July 1, 2031, July 1, 2036, "one third of its laying life", "10,000 birds").

---

## Appendix R. Recalls: DO NOT USE ON AIR

- None researched for this note. Canadian egg recalls, if any are raised by the dossier, go here only.
- Hidden Menu (Handsome Brook, August Egg) and SBG (August Egg, Quality Egg) recall and outbreak items are U.S. and barred (rules 1 and 7).

---

## 6. UNVERIFIED / DO-NOT-USE

### 6a. Could not be opened, or not fully verified, on 3 Oct 2026

| # | Item | What happened | Action |
|---|---|---|---|
| U1 | Burnbrae's own pages: Nestlaid "furnished cage environment"; Prestige "young hens … packed to order"; Solar Free Range; founding year; size claims; Omega Plus "solar-powered barns" | burnbraefarms.com, naturegg.com, dev.burnbraefarms.com: 403 to curl and WebFetch. The Nestlaid wording is seen only in a search snippet. | Browser capture with date before any quote |
| U2 | Burnbrae founding year | April said 1891; the Loblaws listing (P12) says "Since 1893" | State no year until Burnbrae's own page is captured |
| U3 | Nestlaid carton small print "…enriched colony housing equipped with perches and nesting areas" | Read approximately from an 800 px retailer image (P13) | Photograph the physical carton |
| U4 | Island Gold ownership (Burnbrae since 2007; Jensen family 1951) | islandeggs.com 403 | Capture or drop |
| U5 | P&H transaction date ("May 2025" in August s113) | P14 says only "Over a decade ago … partnered"; P&H sub-pages 403 | Do not give a date |
| U6 | P&H retail brands page | WebFetch summary only (Gray Ridge, Sparks, Golden Valley) | Capture |
| U7 | Retail Council of Canada release, 18 Mar 2016 | retailcouncil.org 403 / Cloudflare | Use CBC (P18) and Global (P19), attributed, or capture RCC |
| U8 | Retailers' current pledge statements: Sobeys / Empire SBR 2025, Metro, Walmart Canada, Costco | sobeyssbreport.com 403; others not opened | Capture each company's own words |
| U9 | Mercy For Animals / Retail Insider scorecard figures (Costco ~21%, Sobeys 17–18%, Loblaws 16%, "no major retailer met") | retail-insider.com 403; advocacy-sourced | Do not use; Loblaw's own "approximately 18% of total category sales" (P11) is the citable Loblaw figure |
| U10 | Great Value and Compliments carton prices and lid wording | Not captured (walmart.ca blocks bots; Sobeys/voila not tried) | Capture via Walmart app / Flipp ecom feed and voila.ca |
| U11 | Whether any carton prints a grading-station name, registration or licence number | Not seen on any lid image | Physical capture of side and back panels |
| U12 | CAN/CGSB-32.310-2026 clauses | My curl of the publications.gc.ca PDF returned a 19 KB non-PDF page; clauses read from the parallel dossier's copy | Re-open and screenshot the PDF page; confirm the effective date |
| U13 | SFCR Part 13 / Canada Organic Regime citation for "certified … annually" | Not opened | Open the SFCR Part 13 sections and the CFIA organic page |
| U14 | Yorkshire Valley Farms ownership (Premium Brands majority stake, 2018) | PE Hub paywalled; IFT 404; yorkshirevalleyfarms.com reset / 503 | Premium Brands release or annual report |
| U15 | YVF pasture program "6 hours", feed claims, COTA 2018 award | Not on P17 | Drop |
| U16 | BC Egg free-range "120 days, 6 hours" | Not opened | Capture or drop |
| U17 | "259 eggs a year each" per capita | Not found in P7 text | Find EFC's own figure or drop |
| U18 | EFC FAQ on brown vs white shells | eggs.ca URL guessed: 404 | Use the Rowe Farms listing on loblaws.ca (P12), or capture EFC's page |
| U19 | Whether EFC's Free Range Standards Certification Program is live and has a carton mark | P7 says "implementation in early 2026" only | Ask EFC or capture a page |
| U20 | StatCan August 2026 egg price | The table (released 2 Sep 2026) ends at July 2026 | Recheck on air day |
| U21 | April facts not checkable today: No Name 1978; PC 1984; Walmart 400+ stores; Sobeys ~1,600 stores; Gray Ridge plant locations; Conestoga name origin; "Margaret Hudson president" | Not opened | Not needed in the redo; drop |
| U22 | The thumbnails' effect on views | No impressions or CTR data available | Decision risk, noted in 2b |

### 6b. DO-NOT-USE (any channel, including our April and August videos)

- **Nutrition of any kind:**
  - GoldEgg DHA "125 mg", lutein "for eye health", vitamins E, B12 and D, selenium;
  - Yorkshire Valley vitamins D and E and saturated fat;
  - CBC Marketplace 2021 lab results;
  - ALA vs DHA, "brain", salmon, flax "on your oatmeal";
  - "cheapest honest protein";
  - "nutritionally identical" brown and white;
  - PC Blue Menu "source of omega-3 polyunsaturates" and "13 grams of protein";
  - EFC FAQ nutrition lines;
  - CFIA "enhanced", explained.
- **Food safety:**
  - washing and sanitising "in temperature and acidity-controlled water", cuticle, Europe unwashed, "same bacteria", "genuinely dangerous", best-before "not unsafe";
  - salmonella, recalls, outbreaks, pasteurisation;
  - avian or bird flu, "when disease hits a Canadian farm".
- **Fake-egg framing:** "Only 3 Are ACTUALLY Real Eggs", "NOT REAL EGGS?", "Nobody is counterfeiting breakfast", "CHEMICALS IN EGGS!".
- **Advocacy-sourced welfare material:**
  - Mercy For Animals (2013 W5 farms; 2024 reporting critique; scorecards);
  - Animal Justice (2024 investigation; 11% survey; "Burnbrae Harms");
  - Research Co. polling;
  - "battery cage" characterisations not in a code or company quote;
  - "smaller than a sheet of legal paper … for life";
  - "business class" (unsourced);
  - "cruel / inhumane / prison".
- **Wrongdoing or motive language:**
  - "on purpose";
  - "the silence on the box is not an accident";
  - "the phrase was chosen, brilliantly";
  - "that blur was the business model";
  - "quietly missed / quietly redefined / quietly completed";
  - "the egg industry has structured itself to keep it that way";
  - "grocery duopoly";
  - "admitted the gap";
  - "an auditor whose salary does not depend on selling you eggs".
- **Factually wrong today:**
  - April's PC "conventional or enriched" claim (X: P11, P12);
  - "enriched … phased out by 2036" (X: P8);
  - "these words mean nothing: farm-fresh, natural" (X: P3);
  - "the grader's identity lives in the fine print" as a rule (X: SFCR 218(1)(b), P13);
  - YVF "Canada's largest organic poultry producer, over 35 farms" (X: P17);
  - "Gray Ridge acquired by P&H" (wording; use P14).
- **U.S. or U.K. content:**
  - U.S. prices, Waffle House, rationing;
  - U.S. border seizures vs fentanyl;
  - Windsor vs Michigan prices;
  - USDA letters, Turkey exports;
  - The Logic Niagara anecdote;
  - Cal-Maine and all Hidden Menu / SBG brand material;
  - UK supermarket eggs.
- **Unsourced figures:**
  - "$5.50 a dozen every week";
  - "two companies grade and pack the overwhelming majority";
  - "estimated to control a substantial portion";
  - "Canada's biggest / largest egg company" (market share unpublished);
  - "259 eggs";
  - "Kirkland $9-something";
  - August-snapshot prices ($7.49, $9.50), which are stale.
- **Thumbnail templates:** "EXCLUSIVE:", factory / lab-coat / broken-egg imagery, "NOT REAL", "FAKE / REAL" or "PURE / DILUTED" split labels on named products, and any recommended product under a negative caption.
- **Tagline overlap (fact, for the user's decision):** "the truth is not always on the menu" is The Hidden Menu's closing line (HM s183). The house uses it exactly twice; no other HM wording may be reused.

---

# Eggs video: rules, definitions and label meanings (tier (a) primary sources)

Compiled 3 Oct 2026. Every source below was opened on **3 Oct 2026** unless a row says otherwise. Quotes are verbatim from the page as fetched. "OUR NOTE" marks our own reading or arithmetic. It is not a source quote.

**House-rule compliance for this file**
- This file contains no health, nutrition, food-safety, salmonella, avian-influenza-as-risk or cholesterol content. Where a primary page mixes such material in with rules (CFIA rationales, EFC program descriptions, the eggs.ca FAQ), we quote only the rule or definition and leave the rest out.
- "Omega-3" appears only as a word that may be printed on a carton or shell. We do not explain it.
- Animal-welfare items appear only as what a code, standard, board or company literally says. We add no characterisation.
- No prices appear in this file. It covers rules only.
- No U.S. or U.K. data is presented as Canadian.

---

## 0. Source register

| ID | Source (publisher) | URL opened | Tier | Page's own date / currency | Opened |
|---|---|---|---|---|---|
| S1 | Safe Food for Canadians Regulations, SOR/2018-108 (Justice Laws) | https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/FullText.html | a | "current to 2026-09-21 and last amended on 2025-09-19" | 3 Oct 2026 |
| S1a | SFCR s.255, previous version (repealed by SOR/2022-144) | https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/section-255-20190115.html | a | PIT version | 3 Oct 2026 |
| S1b | SFCR s.257, previous version (repealed by SOR/2022-144) | https://laws-lois.justice.gc.ca/eng/regulations/SOR-2018-108/section-257-20190115.html | a | PIT version | 3 Oct 2026 |
| S2 | Egg Regulations, C.R.C., c. 284: index page showing them repealed | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._284/index.html | a | "[Repealed, SOR/2018-108, s. 411]" | 3 Oct 2026 |
| S2a | Egg Regulations, point-in-time text (2013-04-26 to 2019-01-14, the final version) | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._284/20130426/P1TT3xt3.html | a | historical | 3 Oct 2026 |
| S3 | Food and Drug Regulations, C.R.C., c. 870 (Justice Laws) | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._870/FullText.html | a | "current to 2026-09-21 and last amended on 2026-06-17" | 3 Oct 2026 |
| S4 | CFIA, Canadian Grade Compendium: Volume 5 – Eggs | https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference/canadian-grade-compendium-volume-5 | a | Date modified 2021-04-28 | 3 Oct 2026 |
| S5 | CFIA, Canadian Grade Compendium: Volume 9 – Import Grade Requirements | https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference/canadian-grade-compendium-volume-9 | a | Date modified 2026-02-06 | 3 Oct 2026 |
| S6 | CFIA, Labelling requirements for shell eggs (Industry Labelling Tool) | https://inspection.canada.ca/en/food-labels/labelling/industry/shelled-eggs-products | a | Date modified 2024-03-18 | 3 Oct 2026 |
| S7 | CFIA, Method of production claims | https://inspection.canada.ca/en/food-labels/labelling/industry/method-production-claims | a | Date modified 2024-01-24 | 3 Oct 2026 |
| S8 | CFIA, Origin claims | https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims | a | Date modified 2023-12-06 | 3 Oct 2026 |
| S9 | CFIA, Organic claims | https://inspection.canada.ca/en/food-labels/labelling/industry/organic-claims | a | Date modified 2026-04-27 | 3 Oct 2026 |
| S10 | CFIA, Egg and processed egg products: regulatory requirements (SFCR Part 6 Div 3) | https://inspection.canada.ca/en/food-guidance-commodity/egg-and-processed-egg-products/regulatory-requirements | a | (date line not captured) | 3 Oct 2026 |
| S11 | CGSB, CAN/CGSB-32.310-2026 Organic production systems: General principles and management standards (PDF via Publications Canada) | https://publications.gc.ca/collections/collection_2026/ongc-cgsb/P29-32-310-2026-eng.pdf (catalogue page https://publications.gc.ca/site/eng/9.960491/publication.html) | a | "published in March 2026"; "Supersedes CAN/CGSB-32.310-2020, Corrigendum No. 1" | 3 Oct 2026 |
| S12 | NFACC, Pullets and Laying Hens Code page | https://www.nfacc.ca/codes-of-practice/pullets-and-laying-hens | a | (amended 2025) | 3 Oct 2026 |
| S13 | NFACC, Code of Practice for the Care and Handling of Pullets and Laying Hens (HTML) | https://www.nfacc.ca/poultry-layers-code-of-practice | a | © EFC & NFACC (2017); includes 2025 amendment | 3 Oct 2026 |
| S14 | Egg Farmers of Canada, 2025 Annual Report (PDF) | https://www.eggfarmers.ca/wp-content/uploads/2026/03/2026-03-18_Egg-Farmers-of-Canada_Annual-Report-2025.pdf | a | file dated 2026-03-18 | 3 Oct 2026 |
| S15 | EFC, About us | https://www.eggfarmers.ca/about-us/ | a | undated | 3 Oct 2026 |
| S16 | EFC, "The choice is yours! A guide to buying eggs" | https://www.eggfarmers.ca/2020/07/guide-to-buying-eggs/ | a | published 2020-07-30, modified 2024-10-15 | 3 Oct 2026 |
| S17 | EFC, "From enriched colony to free run and free range…" | https://www.eggfarmers.ca/2023/08/from-enriched-colony-to-free-run-and-free-range-learn-about-the-different-types-of-hen-housing-in-canada/ | a | modified 2024-10-15 | 3 Oct 2026 |
| S18 | EFC, "Here's how to identify Canadian eggs" | https://www.eggfarmers.ca/2020/07/how-to-identify-canadian-eggs/ | a | published 2020-07-28, modified 2026-07-06 | 3 Oct 2026 |
| S19 | EFC, "Canada's Egg Quality Assurance (EQA) program: 8 things to know" | https://www.eggfarmers.ca/2022/06/canadas-egg-quality-assurance-eqa-program-8-things-to-know/ | a | published 2022-06-30, modified 2026-03-30 | 3 Oct 2026 |
| S20 | EQA program FAQ (EFC program site) | https://eggquality.ca/frequently-asked-questions/ | a | undated | 3 Oct 2026 |
| S21 | EFC, "Supply management 101" | https://www.eggfarmers.ca/2020/01/supply-management-101/ | a | modified 2026-07-13 | 3 Oct 2026 |
| S22 | EFC backgrounder, "Canada's innovative system of supply management" (PDF) | https://www.eggfarmers.ca/wp-content/uploads/2023/10/2023-09-21_SM5-Backgrounder-on-Supply-Management.pdf | a | file dated 2023-09-21 | 3 Oct 2026 |
| S23 | eggs.ca (EFC consumer site) FAQs: free run vs free range; hen housing; organic; Grade A; best before; grading station; egg code; sizes; farms in every province | https://eggs.ca/faq/… (exact URLs in each section) | a | undated | 3 Oct 2026 |
| S24 | Egg Farmers of Ontario (Get Cracking), Hen Housing | https://www.getcracking.ca/our-farmers/hen-housing | a | published 2024-09-11, modified 2025-04-10 | 3 Oct 2026 |
| S25 | BC Egg Marketing Board, "Egg Labels 101" | https://bcegg.com/eggs-101/egg-labels-101/ | a | undated | 3 Oct 2026 |
| S26 | BC Egg, "BC Egg Introduces Standards for Free-Range Eggs" | https://bcegg.com/news-posts/bc-egg-introduces-standards-for-free-range-eggs/ | a | published 2017-10-02 | 3 Oct 2026 |
| S27 | Canadian Egg Marketing Agency Proclamation, C.R.C., c. 646 (Justice Laws) | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._646/FullText.html | a | current consolidation | 3 Oct 2026 |
| S28 | Canadian Egg Marketing Agency Quota Regulations, 1986, SOR/86-8 (Justice Laws) | https://laws-lois.justice.gc.ca/eng/regulations/SOR-86-8/FullText.html | a | current consolidation | 3 Oct 2026 (title confirmed only) |
| S29 | Farm Products Council of Canada home page | https://www.canada.ca/en/farm-products-council.html | a | (opened via WebFetch; curl was refused) | 3 Oct 2026 |
| S30 | FPCC, Supply management | https://www.canada.ca/en/farm-products-council/services/supply-management.html | a | Date modified 2025-10-14 (WebFetch) | 3 Oct 2026 |
| S31 | FPCC, Marketing agencies | https://www.canada.ca/en/farm-products-council/services/national-agencies.html | a | Date modified 2025-10-14 (WebFetch) | 3 Oct 2026 |
| S32 | CBSA, Customs Tariff 2026, Chapter 4 | https://www.cbsa-asfc.gc.ca/trade-commerce/tariff-tarif/2026/html/00/ch04-eng.html | a | 2026 schedule | 3 Oct 2026 |
| S33 | Global Affairs Canada, CUSMA: Eggs and Egg Products TRQ, Serial No. 1030 | https://www.international.gc.ca/trade-commerce/controls-controles/notices-avis/1030.aspx?lang=eng | a | Notice dated June 15, 2020; modified 2021-09-29 | 3 Oct 2026 |
| S34 | Global Affairs Canada, Key dates and access quantities 2026-2027: TRQs for supply-managed products | https://www.international.gc.ca/trade-commerce/controls-controles/trq-dates-ct.aspx?lang=eng | a | Date modified 2026-10-01 | 3 Oct 2026 |
| S35 | Global Affairs Canada, WTO: Eggs and Egg Products TRQ, Serial No. 990 | https://www.international.gc.ca/trade-commerce/controls-controles/notices-avis/990_2.aspx?lang=eng | a | Notice dated October 1, 2020; modified 2021-09-29 (WebFetch summary; curl reset) | 3 Oct 2026 |

---

## 1. The law that applies today: SFCR, not the old Egg Regulations

- **S2:** The federal Egg Regulations page on Justice Laws now reads: "Egg Regulations [Repealed, SOR/2018-108, s. 411]".
- **S1, s.411:** "The following Regulations are repealed: (a) the Egg Regulations".
- **OUR NOTE:** On air, refer to the **Safe Food for Canadians Regulations (SFCR)** and the **Canadian Grade Compendium, Volume 5 – Eggs**. Volume 5 is "incorporated by reference into the Safe Food for Canadians Regulations (SFCR)" (S4). Do not describe the old Egg Regulations as current law.

**Scope (which eggs the federal grading rules cover). S6, verbatim:**
> "This section summarizes the labelling requirements that apply to imported shell eggs, as well as those that are produced, treated, graded, packaged or labelled in Canada for interprovincial trade and for export. In some cases, the labelling requirements would also apply when these are intraprovincially traded."
> "When sold intraprovincially, shell eggs are subject to the labelling requirements under the FDA and FDR, as well as specific requirements of the SFCA and SFCR that apply to prepackaged foods sold in Canada, regardless of the level of trade. Provincial regulations may also have labelling requirements that apply when these are sold within that province."

**S1, s.306(1) (mandatory grading), verbatim:**
> "Any eggs, fish, fresh fruits or vegetables, processed fruit or vegetable products, honey, maple syrup or beef carcass in respect of which grades are prescribed by these Regulations that are sent or conveyed from one province to another or that are imported or exported must (a) be graded; (b) meet the requirements that are set out in the Compendium … in respect of the applicable grade of that food; and (c) be labelled … with the applicable grade name …"

**Definitions, S1 s.1, verbatim:**
- "**egg** means an egg of a domestic chicken of the species Gallus domesticus or, in respect of a processed egg product, means that egg or an egg of a domestic turkey of the species Meleagris gallopavo. It does not include a balut."
- "**egg carton** means a package that is capable of being closed and of containing not more than 30 eggs in separate compartments."
- "**tray**, in respect of eggs, means a package, other than an egg carton, that is capable of containing not more than 30 eggs in separate compartments."

---

## 2. Grades: Canada A, Canada B, Canada C, Canada Nest Run

**S4, s.2, verbatim:**
> "There are four grades of eggs with the grade names Canada A, Canada B, Canada C and Canada Nest Run (see Volume 9 Import Grade Requirements for grade names used for imported eggs)."

### 2.1 What a grade measures (S4, verbatim extracts)

| Grade | Requirement (verbatim, S4) |
|---|---|
| **Canada A** (s.4(1)) | "(a) show, on candling (i) a reasonably firm albumen, (ii) an indistinct yolk outline, (iii) a round yolk that is reasonably well centered, and (iv) an air cell that is not in excess of 5 mm in depth; (b) have a shell that (i) has not more than three stain spots, the aggregate area of which does not exceed an area equivalent to 25 mm² and is otherwise free of dirt and stain, (ii) is normal or nearly normal in shape but may have rough areas and ridges other than heavy ridges, and (iii) is uncracked; and (c) be also graded for size, as set out in section 5." |
| Canada A, lot sample (s.4(2)) | "(a) the quality factor of albumen firmness of the eggs in the sample averages 67 Haugh units or higher; (b) the sample does not contain more than (i) 10% of eggs with cracked shells; … (vi) 5% of eggs with an air cell in excess of 5 mm in depth; and (vii) 2.5% of eggs that are leakers; and (c) the sample does not contain more than a total of 15% of eggs described in subparagraphs (b)(i) to (vii)." |
| Canada A at retail (s.4(4)) | "If eggs graded Canada A or having the grade name Grade A are inspected on the premises of a retailer, the depth of the air cell must not be taken into account in determining under-grades." |
| Canada A tolerance away from grading site (s.4(3)) | "…not more than 10% of the total number of eggs examined may be under-grade and not more than 7% of the total number of eggs examined may be under-grade by reason of causes other than cracked shells." |
| **Canada B** (s.6(1)) | "(a) weigh at least 49 g; (b) be uncracked; and (c) show (i) on candling, a distinct yolk outline, (ii) on candling, a yolk that is moderately oblong in shape and that floats freely within the egg when twirled, (iii) on candling, a very slight degree of germ development, (iv) on candling, an air cell not in excess of 9 mm in depth; (v) stain spots on the shell, where the aggregate area of the stain does not exceed 320 mm², … or (vi) a shell that is slightly abnormal in shape and has rough areas and definite ridges." |
| **Canada C** (s.7(1)) | "(a) be free from dirt; and (b) show (i) on candling, a prominent yolk outline, (ii) on candling, a yolk that is definitely oblong in shape but does not adhere to the shell membrane, (iii) on candling, meat spots or blood spots not in excess of 3 mm in diameter, (iv) stain spots on the shell, the aggregate area of which does not exceed 1/3 of the shell surface of the egg, or (v) a shell that is cracked, when the internal contents are not leaking." |
| **Canada Nest Run** (s.8) | "Eggs in a lot must not be graded as Canada Nest Run unless (a) the lot does not contain more than (i) 10% of eggs with cracked shells, (ii) 5% of eggs with dirt on the shells where the dirt is more than 160 mm² in size, and (iii) 3% of eggs that are leakers or rejects; and (b) the lot does not contain more than a total of 15% of eggs described in paragraph (a)." |

**S4, definition of candling, verbatim:**
> "'candling' means examining the interior condition of an egg by rotating or causing the egg to rotate in front of or over a light source that illuminates the contents of the egg."

**S1 s.332(1) (conditions for grading at all), verbatim:**
> "A licence holder may grade an egg only if the egg (a) is edible; (b) does not emit an abnormal odour; (c) is not mouldy; (d) has not been in an incubator; (e) does not have any internal defect; and (f) is of a usual colour."
> s.332(2): "…a licence holder may grade and apply the grade name Canada C to an egg that has a particle of the oviduct or a blood spot neither of which exceeds 3 mm in diameter."

**S1 s.333:**
> "(1) Ungraded eggs that are received at an establishment where eggs are graded by a licence holder must be graded and labelled with the applicable grade name … or, if they do not meet the requirements in respect of any grade …, they must be rejected. (2) Eggs that are rejected must be destroyed or be placed in a container that is labelled with the words 'Rejects' and 'rejetés'."

**Where B, C and Nest Run eggs go (S1 s.99), verbatim:**
> "(1) Any person who sends or conveys any of the following from one province to another must deliver them to an establishment where eggs are processed and treated by a licence holder: (a) eggs that are graded Canada A or Canada B that bear an ink mark that consists of the word 'dyed' or 'teint' or a deposit of ink …; (b) eggs that are graded Canada C; (c) eggs that are graded Grade C or Grade Nest Run that are imported; and (d) ungraded eggs that are imported …"
> "(2) Any person who sends or conveys eggs that are graded Canada Nest Run from one province to another must deliver them to an establishment where either eggs are graded or eggs are processed and treated by a licence holder."

**What the egg boards say a grade means (attributed, plain-language):**
- eggs.ca, "What is a Grade A egg?" (https://eggs.ca/faq/what-is-a-grade-a-egg/): "There are three main things that determine Grade A quality of an egg: the condition of the shell, the position of the yolk, and the size of the air cell inside the shell. If the shell has no cracks, the yolk is centered and the air cell is very small – it meets Canada Grade A standards. These are the eggs you buy at the store."
- EFC (S18): "The Canada Grade A symbol on the carton means eggs meet the Canada Grade A standard required by the Canadian Food Inspection Agency. This means the eggs were graded at a Canadian Food Inspection Agency certified Canadian grading facility and have a clean and uncracked shell, a centered yolk, a firm white and a small air cell."
- **OUR NOTE:** "These are the eggs you buy at the store" and "All Canadian eggs sold in stores will feature the Canada Grade A symbol" (S18) are EFC statements. No SFCR provision we opened says that only Canada A may be sold at retail. Attribute this to EFC.

---

## 3. Grade mark and size designation on the carton

**Grade name location (S1 s.314(1)), verbatim:**
> "The grade name on prepackaged eggs must be shown (a) in the case of a tray with an overwrap or an egg carton, on the top of the tray or egg carton; and (b) in the case of a container, other than a tray with an overwrap or an egg carton, in a central location on the container, except the top or the bottom."

**Type size (S1 s.315), verbatim:**
> "(a) in the case of a tray with an overwrap or an egg carton of eggs graded Canada A or Canada B, 1.5 mm for the word 'Canada' and 3 mm for 'A' or 'B'; (b) in the case of a tray with an overwrap or an egg carton of eggs graded Canada C or Canada Nest Run, 1.5 mm; …"

**Maple-leaf outline (S6, citing Compendium Vol 5 s.3(1)), verbatim:**
> "When eggs are graded Canada A or Canada B, this grade name must be shown inside the outline of a maple leaf…"
> "When applied to prepackaged Canada C or Canada Nest Run eggs, the grade name is simply shown in upper case letters with no maple leaf outline."

**Size designation required for Canada A (S1 s.316), verbatim:**
> "Eggs that are graded Canada A must be labelled with any applicable size designation that is set out in the Compendium. The size designation must be shown on the container in close proximity to the grade name."

**Size type height (S4 s.3(2)):** "(a) in the case of a tray with an overwrap or a carton, in characters of not less than 3 mm in height".

### 3.1 Sizes, Peewee to Jumbo (S4 s.5 table; bilingual names from S6)

| Size designation (EN / FR) | "Egg Weighs Not Less Than" | "Egg Weighs Less Than" |
|---|---|---|
| Jumbo Size / Calibre Jumbo | 70 g | — |
| Extra Large Size / Calibre Extra gros | 63 g | — |
| Large Size / Calibre Gros | 56 g | — |
| Medium Size / Calibre Moyen | 49 g | — |
| Small Size / Calibre Petit | 42 g | — |
| Peewee Size / Calibre Très petit | — | 42 g |

- **OUR NOTE:** The regulation sets **per-egg minimum weights**. Peewee is the only size with a ceiling (under 42 g). Each band's upper edge is implied by the next size up (for example Large is 56 g up to under 63 g), but the table states only minimums.
- **Flag:** BC Egg (S25) says "extra large eggs are 63 to 69 grams". The Compendium does not state that ceiling. Do not quote BC Egg's figure as the legal band.
- eggs.ca (https://eggs.ca/faq/why-are-eggs-different-sizes/): "Eggs are sorted at the grading station based on weight, not circumference, and packaged accordingly into the following sizes: pee wee, small, medium, large, extra large or jumbo." The same page also attributes size to the hen's age. If used, treat that line as EFC's description.
- **Multiple sizes (S4 s.5(3)):** "more than one size designation may be shown on the container, other than a tray with an overwrap or a carton, if the size designation of the eggs in the container is clearly shown on the container." **OUR NOTE:** On a carton, only one size designation applies.

---

## 4. Other mandatory carton items (CFIA shell-egg labelling page, S6)

| Item | Verbatim rule (S6 unless noted) | Legal cite given |
|---|---|---|
| Common name | "The common name 'Eggs' / 'Oeufs' is required to be stated on the label of prepackaged shell eggs. The common name must be shown on the principal display panel of the egg container" | B.01.006(1) FDR; 218(1)(a) SFCR |
| Net quantity | "Every container of prepackaged shell eggs must be labelled with the net quantity." "The declaration of net quantity on prepackaged shell eggs is by numerical count … The quantity can be either displayed numerically or the words can be written out, for example, '12' or 'one dozen'." | 221, 244.1(b), 231, 244 SFCR |
| Name and principal place of business | "The label of prepackaged shell eggs must include the name and principal place of business of the person by or for whom the food was manufactured, prepared, produced, stored, packaged or labelled on any part of the label other than the bottom of the container" | 218(1)(b) SFCR |
| Best before (durable life date) | "The durable life date is required on the label of prepackaged shell eggs. This requirement is considered to be met when the information is marked on the shell of every egg, if it is clearly visible to the consumer without having to open the container (for example, clear plastic cartons)." | B.01.007 FDR |
| Storage instruction | "Storage information, for example, 'Keep Refrigerated', is also required on the label of prepackaged shell eggs." | B.01.007 FDR |
| Loose eggs | "Eggs sold loose in trays are not considered to be prepackaged, unless they are overwrapped. The requirements for durable life dates and storage information in section B.01.007 of the FDR apply only to prepackaged foods." | |
| Country of origin (imports) | "The country of origin is required on all labels of imported prepackaged shell eggs and must be declared as 'Product of' and 'produit de', followed by the name of the country of origin" | 256(1) SFCR |
| Grade name | see §3 | 306, 314, 315 SFCR |
| Size designation | see §3.1 | 316 SFCR |
| Lot code | "For information on the requirement for a lot code or other unique identifier for traceability purposes, consult Traceability-specific labelling requirements." | SFCR Part 5 |
| Pasteurized in shell | "The words 'Pasteurized' and 'pasteurisé', as well as the expression 'Graded Canada A Before Pasteurization' … must appear in both official languages…" | 205(2), 254 SFCR |
| Ungraded | "The words 'Ungraded Eggs' / 'oeufs non classifiés' must appear on the label of the container" (import or interprovincial movement) | 98(1)(b), 99 SFCR |

**SFCR s.256 (imported eggs), verbatim (S1):**
> "(1) The label of imported prepackaged eggs must bear the expressions 'Product of' and 'produit de', followed by the name of the foreign state of origin. (2) That information must be shown in characters that are (a) in the case of a tray with an overwrap or an egg carton, on the top or side of the tray or egg carton, at least 1.5 mm in height…"

**Lot code (S1 s.92(2)), verbatim:**
> "In the case of consumer prepackaged food that is not packaged at retail, the unique identifier referred to in paragraph 90(1)(a) must be a lot code."

### 4.1 "Best before": the legal basis

**FDR B.01.007(1.1)(b) (S3), verbatim:**
> "where a prepackaged product having a durable life of 90 days or less is packaged at a place other than the retail premises from which it is to be sold, (i) the durable life date, and (ii) instructions for the proper storage of the prepackaged product if it requires storage conditions that differ from normal room temperature"

**FDR B.01.007(4)(a):**
> "the words 'best before' and 'meilleur avant' shall be shown grouped together with the durable life date unless a clear explanation of the significance of the durable life date appears elsewhere on the label"

**FDR B.01.001, verbatim:** "durable life date means the date on which the durable life of a prepackaged product ends".
- **OUR NOTE (on-air caution):** The FDR definition of "durable life" includes nutrition and wholesomeness wording, so do not read it out. Use only "durable life date" or "best before".

**What the egg board says the date means (attributed, not law).** eggs.ca (https://eggs.ca/faq/what-does-the-best-before-date-mean/): "The best before date indicates the time the eggs will maintain Grade A quality, if stored properly. It is normally 28 to 35 days from the date of packing."
- **OUR NOTE:** "28 to 35 days" is EFC's description. No regulation we opened fixes a number of days for eggs. Never say "the law says 28 days".

### 4.2 The "station number" on cartons: what the law did and does say

- **The old rule, now repealed (S2a, Egg Regulations s.17).** Verbatim:
  > "(1) Every container, **other than a tray with an overwrap or a carton**, of eggs graded pursuant to these Regulations shall be marked (a) with the registration number of the registered egg station (i) in which the eggs were graded and packed, or (ii) for which the eggs were graded and packed…"
  > "(2) Every tray with an overwrap and every carton containing eggs graded pursuant to these Regulations shall be marked with the information required under the Consumer Packaging and Labelling Act and the name and address of (a) the registered egg station … or (b) the wholesaler or retailer of the eggs."
- Old-regulation definition (S2a): "registration number means the number assigned to a registered egg station pursuant to section 7".
- **Today (S1, S6).** Neither the current SFCR nor CFIA's shell-egg labelling page lists a grading-station number among the required carton items. What they require is the **name and principal place of business** (218(1)(b)) and a **lot code** (92(2)).
- **OUR NOTE:** Even under the old regulations, a registration number was required on the outer **cases** ("other than a tray with an overwrap or a carton"), not on consumer cartons. If a carton shows a number such as "Reg." or "Station", we found no current rule that requires it or defines what it means. Describe it only as "a code the packer prints" unless the packer confirms otherwise.
- **Shell codes (attributed).** eggs.ca (https://eggs.ca/faq/why-do-i-see-some-eggs-with-a-code/): "In some parts of Canada, a code is stamped onto the eggshell. This code is part of a traceability system which identifies information like the farm where the eggs comes from, the place it was graded, and the best before date."
- **Ink on shells (S1 s.100):** "If a licence holder applies ink to an egg's shell, the ink must be fast-drying and indelible and it must not present a risk of injury to human health." CFIA (S10) says ink is used "to apply markings that can be used to identify and track eggs and to provide other types of information about the egg". **OUR NOTE:** The CFIA rationale also contains nutrient wording, which we do not use.

### 4.3 Words CFIA restricts on egg cartons (S6 "Other claims", verbatim)

| Word on carton | CFIA position (verbatim) |
|---|---|
| "Fresh" | "The Canadian Food Inspection Agency's (CFIA) position is that all eggs are fresh. Therefore, the claim 'fresh' is permitted only if it appears as part of a statement such as 'all eggs are fresh' or 'like all eggs, these eggs are fresh'." |
| "Farm fresh" | "The claim 'farm fresh' implies that the eggs were distributed directly from the farm to the store. This claim should only be used if the licence holder grades their own eggs on-farm and ships them directly to the store." |
| "Natural" | "CFIA's position is that all eggs are natural. Therefore, the term 'natural' is permitted only if it appears as part of a statement such as 'all eggs are natural' or 'like all eggs, these eggs are natural'." |
| "No hormones" | "A 'no hormones' claim by itself on an egg carton would be considered misleading under section 5(1) of the FDA, as the use of hormones is not permitted in poultry in Canada. … A 'no hormones' claim can be made on an egg carton provided it is accompanied by a statement explaining that 'the use of hormones is not permitted in poultry in Canada' and must be placed in close proximity to the claim." |
| "No preservatives" | "CFIA's position is that 'no preservatives' or similar claims are not acceptable for shell eggs as it is not possible to insert preservatives inside of an egg." |
| "Young hens" | "Claims such as 'specially selected from young hens' are permitted. Indication of what is considered young (for example, less than X months of lay) is recommended. Claims that the eggs are young (rather than the hens) are not permitted." |
| "Enhanced" (term only) | "'Enhanced' is the term to be used when a nutrient in an egg has been increased via the feed. The terms 'fortified' and 'enriched' are not to be used to describe a shell egg nutrient profile because these terms are used for foods where nutrients have been added directly to the food." |

- **OUR NOTE:** "Omega-3" on a carton may be read on air **only as a printed product name**. We give no explanation of what it means for the eater. The fact that CFIA uses "enhanced" as a **labelling term** may be stated as a terminology rule.
- **OUR NOTE:** "Enriched" has two unrelated uses. In CFIA's nutrient-labelling sense it is barred for shell eggs. In the housing sense, "enriched colony" or "enriched cage", it is used by EFC and NFACC. Keep the two apart on air.

---

## 5. Origin: "Product of Canada", "Canadian", the maple leaf, imports

| Rule / statement | Verbatim | Source |
|---|---|---|
| Imported eggs must say origin | "The label of imported prepackaged eggs must bear the expressions 'Product of' and 'produit de', followed by the name of the foreign state of origin." | S1 s.256(1) |
| Imported eggs graded in Canada carry the Canadian grade name | "(2) Subsection (1) does not apply to imported eggs (item 2) … if they are graded by a licence holder. These foods must use the Canadian grade name as shown in Column 2 … rather than the import grade name referred to in Column 3." | S5 s.1(2) |
| Import grade names (imported, not regraded) | Canada A ↔ "Grade A"; Canada B ↔ "Grade B"; Canada C ↔ "Grade C"; Canada Nest Run ↔ "Grade Nest Run" | S5 table, item 2; S6 |
| "Product of Canada" is voluntary | "The use of 'Product of Canada' and 'Made in Canada' claims is voluntary. However, once a company chooses to make one of these claims, the product to which it is applied should meet these guidelines." | S8 |
| Test for "Product of Canada" | "A food product may use the claim 'Product of Canada' when all or virtually all major ingredients, processing, and labour used to make the food product are Canadian." | S8 |
| "Canadian" = "Product of Canada" | "The claim 'Canadian' is considered to be the same as a 'Product of Canada' claim and any product carrying this claim must meet the criteria for a 'Product of Canada' claim described above." | S8 |
| "100% Canadian" | "When the claim '100% Canadian' is used on a label, the food or ingredient to which the claim applies must be entirely Canadian rather than 'all or virtually all' Canadian." | S8 |
| "Local" | "A policy has been adopted which recognizes 'local' food as: food produced in the province or territory in which it is sold, or food sold across provincial borders within 50 km of the originating province or territory" | S8 |
| Maple leaf symbol | "The maple leaf, other than the stylized 11-point maple leaf, or other similar symbol may be used on food products without further permission. The use of these vignettes on their own does not always imply that the product is wholly or partially Canadian…" | S8 |
| Old rule (repealed) on export labels | SFCR s.257 (repealed by SOR/2022-144) previously read: "The label of prepackaged eggs that are graded in accordance with these Regulations and that are exported must bear the expressions 'Product of Canada' and 'produit du Canada'." | S1b |

**What EFC and BC Egg say about the Grade A maple leaf on imported eggs (attributed):**
- EFC (S18): "In some rare cases, the Canada Grade A symbol might be present on a carton of eggs that is labeled as USDA or a product of the United States. This means imported eggs were graded in Canada and packaged by a Canadian grader."
- EFC (S18): "All Canadian eggs sold in stores will feature the Canada Grade A symbol on the carton, and many also feature a 'Product of Canada' label." And: "Because of obligations under international trade agreements, Canada imports some eggs. Imported eggs are labeled with the country of origin on the egg carton."
- BC Egg (S25): "just because it says 'Canada Grade A' doesn't necessarily mean the eggs were laid in Canada, on Canadian egg farms. The 'Canada Grade A' designation is granted if the eggs are graded in a licensed, Canadian grading facility and meet the 'Grade A' standards, but they don't have to be Canadian eggs. However, they DO have to be clearly labeled as 'Product of' their country of origin."

**OUR NOTE:** The maple-leaf "CANADA A" mark is a **grade** mark. By itself it is not an origin mark. Origin on imported eggs comes from the "Product of [country]" line (s.256). Origin on domestic eggs comes from voluntary claims ("Product of Canada", "Canadian") or the EQA mark (§12).

---

## 6. Housing words: who defines them, and is any of them legally defined?

### 6.1 Plain answer on legal status
- **Of the housing words, only "organic" has a federal legal definition.** It is regulated under SFCR Part 13 (the Canada Organic Regime) and the standard CAN/CGSB-32.310 (see §7).
- **"Conventional", "enriched/furnished/enriched colony", "free run", "free range", "cage-free" and "pasture/pasture-raised"** are **not defined** in the SFCR text or on the CFIA shell-egg labelling page (S6), the CFIA method-of-production claims page (S7) or the CFIA origin page (S8). We opened and searched all of these on 3 Oct 2026.
- What CFIA does say applies to all such claims (S7, verbatim):
  > "Claims related to the method of production are also subject to subsection 5(1) of the Food and Drugs Act (FDA) and subsection 6(1) of the Safe Food for Canadians Act (SFCA), which prohibit statements and claims that are false, misleading, deceptive or that create an erroneous impression regarding the product."
  > "While most method of production claims are not mandatory, in some cases, criteria exist for their use. For example, if a company chooses to apply a voluntary organic, kosher or halal claim, then specific regulatory requirements are triggered and must be met."
  > "Acceptable manners to substantiate a method of production claim include: third party audit, valid documentation, or non-government certification programs. All documents used to substantiate a method of production claim must be made available to a CFIA inspector upon request."
- **Industry and provincial definitions do exist.** EFC and boards publish them, the NFACC Code glossary has them, and BC Egg sets provincial free-range standards. EFC also reports a national free-range certification program (§6.3). These are industry or provincial-board standards. None of them is a CFIA legal definition.

### 6.2 Definitions table (verbatim, by publisher)

| Term | EFC (S16 guide / S17 housing page) | eggs.ca (EFC consumer site) | Egg Farmers of Ontario (S24) | BC Egg (S25) | NFACC Code glossary (S13) |
|---|---|---|---|---|---|
| **Conventional** | S16: "Regular white or brown eggs come from hens that are housed in small group settings. These are the most common eggs found in Canada." S17: "In conventional housing, hens live in small groups in elevated housing … Canadian egg farmers are actively phasing out conventional hen housing and moving to other systems like enriched colony, free run and free range housing." | hen-housing FAQ: "In conventional systems, hens are housed in small group settings with plenty of access to food and water." | "Conventional Housing: Older style small group housing system being phased out by Canadian egg farmers." | "This type of housing is being phased out and is being replaced with enriched housing." | "Conventional Cage: A wire mesh enclosure for housing laying hens with equipment for provision of water, automated feeding, and egg collection. Also referred to as unfurnished cage." |
| **Enriched / furnished / enriched colony** | S16: "Enriched colony and furnished eggs come from hens that are housed in small group settings with amenities such as perches and a curtained off area where hens lay their eggs." S17: "Enriched colony housing includes features such as nest boxes, scratch pads and perches." S17 also: "Enriched colony housing is sometimes referred to as the 'business class' of hen housing." (EFC's own phrase) | "Enriched systems are equipped with perches and a curtained off area where the hens lay their eggs." | "Enriched Colony: Naturally-sized social groups with perches, scratch areas and private nest boxes benefit hen health and welfare." | "Enriched housing is the new standard for your least expensive grocery store eggs. It offers significantly more space per bird and is equipped with amenities like nest boxes, perches and scratch pads…" | "Enriched Cage: A wire mesh enclosure outfitted with perches, nest area, scratch area, and more head room compared to a conventional cage; group sizes in furnished cages can range from 10 to over 100 hens, depending on the model. Also referred to as furnished cage or colony cage." |
| **Free run** | S16: "Free run eggs come from hens that roam the entire barn floor. Some of these barns are equipped with multi-tiered aviaries." | free-run-vs-free-range FAQ: "Free run eggs come from hens that roam the entire barn floor. Some of these barns may be equipped with multi-tiered aviaries." | "Free Run: Hens have access to the entire barn floor. They can also perch, scratch and use private nest boxes to lay their eggs." | "Free-run eggs are produced in an environment where the hens have the run of the barn. … The number of hens in these barns is regulated to ensure they are not over crowded." | "Free-Run: A system where birds roam freely inside a barn but do not have access to the outdoors. Also referred to as barn systems." |
| **Free range** | S16: "Free range eggs come from hens that roam the barn floor and access the outdoors when weather permits. Outdoor access is only seasonally available in Canada." | "Free range eggs come from hens that roam the barn floor and when weather permits, go outside to pasture. Outdoor access is only seasonally available in Canada." | "Free Range: Hens have access to the entire barn floor. They can also perch, scratch and use private nest boxes to lay their eggs. Weather permitting, hens also have access to an outdoor space." | "Free-range eggs come from barns that are similar to free run barns but also give hens access to the outdoors. There are standards in place to ensure the hens have access to the outdoors at least 120 days a year (minimum of six hours per day)." | "Free-Range: A system where laying hens are allowed access to an outdoor pasture or range area." |
| **Organic** | S16: "Organic eggs come from hens raised in a free range system with access to the outdoors. These hens are fed certified organic feed, and farmers follow the Canadian Organic Standards regulated by the Canadian Food Inspection Agency." | organic FAQ: "Eggs that are sold as organic are produced under specific standards laid out by the Canadian General Standards Board and certified by a reputable organic certification board. All certified organic eggs in Canada are produced in free range operations and the hens are fed certified organic feed." | (not on page) | "Organic eggs are produced in barns that are similar to free-range barns. … Organic producers are also given an extra layer of oversight, as their organic certification is administered by a third-party auditor." | (not defined; see CGSB, §7) |
| **Cage-free** | (not defined on S16/S17) | — | — | "Cage-Free is a term that can be applied to the remaining three production types: free run, free range and organic." | "Non-Cage Systems: Systems that include single-tier (free-run, floor, or barn), multi-tier (aviary), and free-range, and do not use cages to house birds." Body text: "Non-cage systems, also referred to as free-run or cage-free systems…" |
| **Pasture / pasture-raised** | **No EFC definition found.** | Appears only inside the free-range answer ("go outside to pasture"). | — | — | No "pasture-raised" definition. "Free-Range" glossary says "outdoor pasture or range area". |
| **Aviary / multi-tier** | — | — | "Aviary: In aviary housing, hens have access to the whole barn floor as well as different levels of the barn where they can perch, feed, drink and lay their eggs." | — | "Multi-Tier: A non-cage system where nest, perching, and food and water resources are located on multiple elevated tiers. Also referred to as aviary systems or aviaries." |

URLs for the eggs.ca column: https://eggs.ca/faq/are-there-different-types-of-hen-housing/ ; https://eggs.ca/faq/whats-the-difference-between-free-run-and-free-range-eggs/ ; https://eggs.ca/faq/how-are-eggs-certified-organic/

- **Excluded content:** The eggs.ca free-run vs free-range page also carries a sentence comparing nutrient content. It is excluded under the house rules. The BC Egg page carries nutrition and medication lines. They are excluded.

### 6.3 Provincial and national free-range standards (attributed)
- **BC Egg (S26, published 2017-10-02), verbatim:** "The new standards state that hens must have access to the range at least 120 days a year – and a day is a minimum of six hours. Farmers must document the number of days and hours a day hens have access to the outdoors." Also: "hens must be given outdoor access when the temperature is between 15 and 30 degrees Celsius. If a farmer restricts outside access, he/she must have a letter from a vet stating why the access is restricted." Also: "the range must have grass, be free from debris, and not have anything that can attract wildlife (like food dishes)." Quote from Katie Lowe, then Executive Director of BC Egg: "We are very proud to be the first in Canada to set these standards and make them mandatory for all free-range farmers in BC".
- **EFC national program (S14, 2025 Annual Report), verbatim:** "Another key initiative was the development of a national Free Range Standards Certification Program. This mandatory program details a consistent set of standards that egg farms must meet to be considered free range, including range access and space, vegetation, pophole and perimeter fence requirements. The Free Range Standards Certification Program was approved by the EFC Board of Directors in August for implementation in early 2026."
- **OUR NOTE:** This is an industry program, "mandatory" in EFC's words for egg farms within the regulated system. It is not a CFIA definition. The program's text, the numbers in it and whether implementation actually began were **not found** on a public page (see UNVERIFIED).

---

## 7. Organic: the one legally defined housing word (Canada Organic Regime)

**SFCR s.353(1), verbatim (S1):**
> "The expressions 'organic' or 'biologique' or 'organique', 'organically grown' …, 'organically raised' … and 'organically produced' … and any similar expressions, including abbreviations of, symbols for and phonetic renderings of those expressions, may be shown on the label or used in the advertisement of a food commodity that is sent or conveyed from one province to another if (a) the food commodity is an organic product; and (b) in the case of a multi-ingredient food commodity, at least 95% of its contents are organic products."

**SFCR s.1 definition, verbatim:** "organic product means a food commodity that has been certified as organic under subsection 345(1) or certified as organic by an entity accredited by a foreign state that is referred to in subparagraph 357(1)(a)(ii)."

**SFCR s.354(a):** the label "must also bear (a) in the case of a food commodity that is sent or conveyed from one province to another, the name of the certification body that certified the food commodity as organic".

**SFCR s.359(1) (Canada Organic logo / product legend):** "A person is authorized to apply the product legend that is set out in Schedule 9 to and use it in connection with a food commodity if (a) the food commodity is an organic product; and (b) in the case of a multi-ingredient food commodity, at least 95% of its contents are organic products."

**CFIA (S9), verbatim:**
> "Imported or interprovincially traded products making an organic claim must be certified under the Canada Organic Regime."
> "The use of the organic logo is only permitted on products that have an organic content that is greater than or equal to 95% and have been certified according to the requirements of the Canada Organic Regime. The use of the organic logo is voluntary but when used it is subject to the requirements of the SFCR [359 (1), SFCR]."
> "'Certified organic' and other similar claims are not acceptable and are considered misleading if they are used without being in connection to the name of the certification body…"
> Imported products bearing the logo must include "the statement 'Product of', immediately preceding the name of the country of origin, or the word 'Imported', in close proximity to the logo".

**SFCR s.345(1):** "A certification body must conduct an on-site verification and certify a food commodity as organic if it determines that…" the methods "meet the requirements and comply with the general principles respecting organic production that are set out … in CAN/CGSB-32.310". **s.346(2)** requires a further on-site verification within each 12-month period.

### 7.1 What the organic standard says about laying hens: CAN/CGSB-32.310-2026 (S11), verbatim
- **6.13.1 a):** "The keeping of poultry in row, battery, enriched or colony cages, is prohibited;"
- **6.13.1 b):** "Poultry shall be reared in open-range conditions and have free access to pasture, open-air runs, and other exercise areas, subject to weather and ground conditions. Outdoor areas shall: … 2) be covered with vegetation, seeded if necessary, and periodically left empty to allow vegetation to regrow … 3) have effective overhead cover … Overhead cover shall represent at least 10% of the minimum required range area … 4) show signs of use as appropriate for the season;"
- **6.13.1 c):** "In an emergency, when outdoor access results in an imminent threat to the health and welfare of poultry, access may be restricted. Outdoor access shall resume when the imminent threat ends. Producers shall document periods of confinement;"
- **6.13.2 a):** "Layers may be confined during the onset of lay, that is, until peak production is reached. The laying flock shall have outdoor access for at least one third of its laying life."
- **6.13.2 c):** "Layer flocks shall be limited to 10,000 birds. More than one flock may be in the same building if the flocks are separated and have separate runs."
- **6.13.3 (enriched verandahs):** "Enriched verandahs shall be used when barn-raised layers do not have access to outdoor runs because of weather or disease constraints…" A verandah must "represent at least one third of the footprint of the indoor barn area" and must "not count towards indoor or outdoor space allowance". Also: "Enriched verandahs shall be provided in new construction for barn-raised layers. They shall be added to existing infrastructure when the operator cannot demonstrate that at least 25% of layers utilize the outdoor range when there are no weather or disease constraints."
- **6.13.4:** "Layers shall have access to the nest space area listed in the requirements of the Code of Practice for the Care and Handling of Pullets and Laying Hens for non-cage systems".
- **6.13.5 c):** "Laying hens shall have a minimum of 15 cm (5.9 in.) perch space per hen, accessible at all times and at varying heights."
- **Table 5, maximum densities:** Layers (19 weeks and older): **Indoors 6 birds/m²; Outdoor runs 4 birds/m²**. Footnote b: "Nest space shall not be included when calculating usable space allowance."
- **6.13.14:** "Multi-level aviary systems for layers shall have no more than three levels or tiers above ground level."
- **6.13.15:** "For pasture-based operations with mobile units, stocking density shall be no more than 2000 layers/ha (800 layers/ac.)…"
- **Edition and timing (S11), verbatim:** "This National Standard of Canada, CAN/CGSB-32.310-2026, supersedes the 2020 edition and 2021 Corrigendum." "Certification bodies must allow a period of up to 12 months after the publication date of an amendment to this standard … for an applicant to come into compliance with any changes to the requirements." SFCR s.340 defines CAN/CGSB-32.310 "as amended from time to time".
- **OUR NOTE:** Because the 2026 edition was published in March 2026, operators may be inside a compliance window of up to 12 months. On air, "organic standard requires…" is safe for clauses that the 2020 edition also contained. Before an on-screen quote graphic, confirm whether a clause is new in 2026 (see UNVERIFIED).

---

## 8. NFACC Code of Practice for the Care and Handling of Pullets and Laying Hens (2017; amended 2025)

**Status and authorship (S12, S13), verbatim:**
- S12: "The Code of Practice for the Care and Handling of Pullets and Laying Hens was originally released in 2017. The 5-year review of this Code was completed in 2022 with a recommendation to initiate an amendment … Amendments to the pullets and laying hens Code were initiated in 2023 and completed in 2025."
- S13: "© Copyright is jointly held by Egg Farmers of Canada and the National Farm Animal Care Council (2017)".
- **What a "Requirement" is (S13), verbatim:** "Requirements - These refer to either a regulatory requirement or an industry imposed expectation outlining acceptable and unacceptable practices and are fundamental obligations relating to the care of animals. … When included as part of an assessment program, those who fail to implement Requirements may be compelled by industry associations to undertake corrective measures or risk a loss of market options. Requirements also may be enforceable under federal and provincial regulation."
- **OUR NOTE:** Describe the Code as an industry code that is enforced through industry programs and in some places referenced in law. Do not call it a federal regulation.

### 8.1 Transition away from conventional cages (verbatim, S13)
- Preface: "this Code mandates the phase out of conventional cages, so that hens may have more freedom of movement and the ability to perform a variety of natural behaviours."
- Preface: "It is expected that 50% of hens in Canada will be transitioned to alternative housing systems (i.e. enriched cages; non-cage housing) within 8 years."
- §2.5: "The industry commits to a minimum of 85% of hens to be transitioned from existing conventional cage systems to alternative housing systems that meet the requirements of this Code within 15 years, and will aim to transition 100% of hens within the same time frame. It is expected that 50% of birds will be transitioned within 8 years. The transition will be overseen by the industry and its stakeholders, and reviewed within 10 years to assess and evaluate the status of the transition."
- §2.5 Requirements:
  - "If any hens have not been transitioned from conventional cages by July 1, 2031, each of those hens still kept in conventional cages must be provided with a minimum space allowance in those systems of 580.6 cm² (90.0 sq in), effective July 1, 2031."
  - "**All hens must be housed in enriched cage or non-cage housing systems that meet this Code's requirements by July 1, 2036.**"
  - "Enriched cages installed after January 1, 2032, must be designed to include amenities that provide hens with improved opportunities to forage and dust bathe."
  - "All housing systems to which hens are transitioned must support nesting, perching, and foraging (pecking and scratching) behaviour."

### 8.2 Space allowances (verbatim, S13 §2.5.1)

| System / condition | Minimum per hen | Effective |
|---|---|---|
| Enriched cages, new build/re-tool | "750.0 cm² (116.25 sq in) of total space, including nests, of which 600.0 cm² (93.0 sq in) does not include nest boxes" | construction/re-tooling initiated after April 1, 2017; all enriched cages for flocks placed after January 1, 2022 ("(F)") |
| Cages with Furnishings installed before Apr 1 2017 | "580.6 cm² (90.0 sq in)" | flocks placed after April 1, 2017 (transitional) |
| Conventional cages installed before Jul 1 2016 | "432.0 cm² (67.0 sq in) for white birds and 484.0 cm² (75.0 sq in) for brown birds" | flocks placed after January 1, 2020 (transitional) |
| Conventional cages still in use | "580.6 cm² (90.0 sq in)" | July 1, 2031 |
| Non-cage, single-tier, all litter | "1,900.0 cm² (294.5 sq in/2.05 sq ft)" useable space (excluding nests) | new build after April 1, 2017 |
| Non-cage, single-tier, wire/slats/litter | "929.0 cm² (144.0 sq in/1.0 sq ft)" | same |
| Non-cage, multi-tier | "929.0 cm² (144.0 sq in/1.0 sq ft)" | same |
| Enriched and non-cage height | "a minimum height of 45.0 cm (17.7 in) must be provided between the floor and ceiling of each level" | |
| Nest space, enriched cages | "a minimum of 65.0 cm² (10.0 sq in)" | |
| Nest space, non-cage | "83.2 cm² (12.9 sq in) [1.0 m² (10.8 sq ft) for each 120 hens]" | |

- **OUR NOTE (arithmetic only):** 750 cm² equals 0.075 m². A US-letter sheet (21.6 × 27.9 cm) is about 603 cm². A legal sheet (21.6 × 35.6 cm) is about 768 cm². If a comparison is used, it must be labelled as our arithmetic, not NFACC's words.
- 2025 amendment (S13, verbatim): space for pullets in multi-tier rearing applies to "Multi-Tier Rearing Systems for which new construction or re-tooling … was initiated after August 1, 2025". The S12 page lists the amended sections: "Round feeder space for pullets and laying hens (sections 1.1.3 & 2.3), Minimum space allowance for pullets in multi-tier systems (section 1.1.4), and Maximum number of tiers allowed in laying and rearing facilities (sections 1.1.5 & 2.6)."

---

## 9. EFC's own figures (2025 Annual Report, S14, published 2026-03-18)

### 9.1 Share of hens by housing type: "Hen issuance by production method"

| Production method | 2025 | 2024 | 2023 | 2022 | 2021 |
|---|---|---|---|---|---|
| Conventional housing | 39.45% | 42.02% | 45.28% | 49.64% | 52.88% |
| Enriched colony | 39.33% | 38.02% | 35.33% | 32.47% | 29.30% |
| Aviary/free run | 14.77% | 13.49% | 13.02% | 11.14% | 11.43% |
| Organic | 4.99% | 5.01% | 5.02% | 5.43% | 5.07% |
| Free range | 1.46% | 1.46% | 1.35% | 1.32% | 1.32% |

Table notes, verbatim: "Source: Egg boards". "Note: 2021-2024 data represents December, end of year value. 2025 data represents July, mid-year value."

Narrative, verbatim (S14):
> "As of mid-2025, the share of hens housed in conventional systems decreased to 39.45%, down from 42.02% in 2024 and 52.88% in 2021. Enriched colony remains the largest alternative housing system in Canada, representing 39.33% of hens in 2025. … In 2025, free run, free range and organic systems represented 21% of hens in Canada, compared to 10% in 2016."
> "Current trends suggest conventional housing is projected to be eliminated by the target date of 2036, if the transition maintains the pace observed over the past three years."

- **OUR NOTE:** 14.77 + 4.99 + 1.46 = 21.22%, which matches EFC's "21%". Conventional plus enriched colony = 78.78% (our arithmetic). The 2025 figure is a July value and the other years are December values, so 2024→2025 is not a full-year change.

### 9.2 Farms, flock size and production

| Item | Figure (verbatim) | Source |
|---|---|---|
| Number of farmers, 2025 | Total "1,295"; average layers per farmer "22,069" ("Note: Reported data for 2025.") | S14 table "Farmers and average flock size per province and territory" |
| By province (farmers / avg layers) | BC 160 / 24,587; AB 168 / 21,852; NT 1 / 124,348; SK 71 / 22,603; MB 154 / 18,010; ON 450 / 26,020; QC 239 / 27,628; NB 15 / 36,468; NS 24 / 40,067; PE 7 / 20,335; NL 6 / 66,125 | S14 |
| Production 2025 | "937 million dozen eggs produced in Canada in 2025" | S14 |
| Production growth | "With egg production up by approximately 7.6% in 2025…" | S14 |
| Layers added | "a total of 2,922,258 layers were added to the national system in 2025. This 8.62% increase in quota…" | S14 |
| Quota allocations "prior approved" by FPCC | "Federal quota increase of 1,353,964 layers – Week 17 of 2025"; "Federal quota increase of 1,568,294 layers – Week 41 of 2025"; "STMRQ quota allocation of 1,154,500 layers – Week 1 of 2026" | S14 |
| EFC self-description | "We are a national organization that represents Canada's more than 1,290 regulated egg farmers in all 10 provinces and the Northwest Territories. Created in 1972 under the federal Farm Products Agencies Act, Egg Farmers of Canada manages the supply of eggs, promotes eggs and develops standards for egg farming in Canada." "Our farmers produce over 937 million dozen eggs annually…" | S15 |

- **OUR NOTE:** 1,295 × 22,069 ≈ 28.6 million layers (our arithmetic). EFC does not state that total. The farm count wording varies by source: 1,295 (S14), "more than 1,290" (S15, S18), "more than 1,200" (FPCC, S31), "more than 1,000 farm families" (eggs.ca, https://eggs.ca/faq/are-there-egg-farms-in-every-province/). On air, use **1,295 (EFC 2025 Annual Report)**.

---

## 10. Supply management: who does what

| Body / mechanism | Verbatim | Source |
|---|---|---|
| Farm Products Council of Canada | "FPCC is a federal public interest oversight body that oversees the national supply management system for poultry and eggs, including the operations of the four marketing agencies." | S29 (WebFetch) |
| FPCC's definition of supply management | "Supply management is a system that balances supply and demand of a commodity through production setting (quota), price setting and import control" | S30 (WebFetch) |
| EFC as a federal agency | "Created in 1972." "Manages the supply of eggs, promotes the consumption of eggs, and develops standards for egg farming in Canada." | S31 (WebFetch) |
| Legal creation | "…do by this Our Proclamation establish an agency to be known as the Canadian Egg Marketing Agency…" and "the farm product in relation to which the Canadian Egg Marketing Agency may exercise its powers is eggs from domestic hens" | S27 |
| Federal–provincial quota link | Plan s.2(1): "The Agency shall, by order or regulation, establish a quota system by which quotas are assigned to all members of classes of egg producers in each province to whom quotas are assigned by the appropriate Board or Commodity Board." s.7: "The Agency may, with the concurrence of a Commodity Board, appoint that Commodity Board to administer on its behalf any orders or regulations made by it…" | S27 |
| Quota regulations exist | Title confirmed: "Canadian Egg Marketing Agency Quota Regulations, 1986 (SOR/86-8)" | S28 |
| Objects of a federal agency (as quoted by EFC) | "To promote a strong, efficient and competitive production and marketing industry for the regulated product…" / "To have due regard to the interests of producers and consumers of the regulated product or products." | S14 (quoting the Farm Products Agencies Act) |
| EFC's "three pillars" | "To work efficiently and effectively, supply management is built on three important pillars: production management, import control, and producer pricing." | S22 |
| Cost-of-production pricing (EFC's words) | "The cost to produce a dozen eggs is calculated by examining the expenses necessary for its production. The results are used to set the producer price, which ensures farmers earn a fair return that covers their labour and investment…" | S21 |
| Same, from the backgrounder | "producer prices are based on the expenses necessary for its production, such as input costs (e.g. animal feed, fuel, equipment and labour)." | S22 |
| COP in 2025 | "we implemented the latest Cost of Production (COP) Study results with the rollout of the National Free Run Producer Pricing Policy and an updated pricing method for conventional and enriched eggs." And: "Memorandums of Understanding (MOU) were signed with egg boards … These concerted efforts delivered coordinated pricing structures for conventional, enriched colony and free run production that uphold jurisdictional responsibilities…" | S14 |
| EFC on TRQs (its own analogy) | "TRQs act like a dam because we are required to import a certain amount of eggs into the Canadian market—think of that as when the dam is open. Once that amount comes in at a low tariff, the dam closes and a tariff is applied to imported eggs beyond the predetermined amount." | S21 |
| Trade position (EFC's words) | "EFC will continue to advocate for no new market access or changes to the over-quota tariff throughout other trade negotiations and as the scheduled review of the Canada-United States-Mexico Agreement (CUSMA) gets underway." It also says supply management protection is "backed by federal legislation thanks to the successful passage of Bill C-202." | S14 |

- **OUR NOTE:** The producer price is the price paid to the farmer. It is not the shelf price. None of these sources sets the retail price. Attribute "fair return" wording to EFC. We did not open the text of Bill C-202 (see UNVERIFIED).

---

## 11. Imports: tariff items, over-quota tariff, TRQs

### 11.1 Customs Tariff 2026, heading 04.07 (S32), verbatim rows

| Tariff item | Description | MFN tariff | Preferential (listed) |
|---|---|---|---|
| 0407.21.10 | "Other fresh eggs: – Of fowls of the species Gallus domesticus – Within access commitment" | **1.51¢/dozen** | "CCCT, LDCT, UST, CT, CRT, PT, COLT, JT, PAT, CEUT, UAT, CPTPT, UKT: Free" |
| 0407.21.10.10 | "…Within access commitment – White, regular, excluding organic and other specialty, for retail or table" | 1.51¢/dozen | same |
| 0407.21.10.20 | "…Within access commitment – Organic and other specialty, including free run or range, omega, brown and Columbus, for retail or table" | 1.51¢/dozen | same |
| 0407.21.10.30 | "…Within access commitment – For breaking purposes only" | 1.51¢/dozen | same |
| **0407.21.20** | "Other fresh eggs: – Of fowls of the species Gallus domesticus – **Over access commitment**" | **"163.5% but not less than 79.9¢/dozen"** | (none listed) |
| 0407.90.12 | "Other – Of the fowls of the species Gallus domesticus: – Over access commitment" | "163.5% but not less than 79.9¢/dozen" | (none listed) |

- **On-air wording (verbatim):** the over-access-commitment tariff on fresh hen eggs in shell is "163.5% but not less than 79.9¢/dozen" (Customs Tariff 2026, tariff item 0407.21.20).

### 11.2 TRQ access quantities (Global Affairs, S34, modified 2026-10-01), verbatim rows

| Agreement / TRQ | Allocation year | Access quantity |
|---|---|---|
| CPTPP Eggs | January 1 to December 31 | 17,378,087 dozen eggs equivalent |
| CUSMA Eggs and Egg Products | January 1 to December 31 | 10,201,000 dozen eggs equivalent |
| WTO Eggs and Egg Products | January 1 to December 31 | 21,370,000 dozen eggs equivalent |

- Page header, verbatim: "Key dates and access quantities 2026-2027: TRQs for supply-managed products". "The following includes TRQs already allocated and calendar year 2027 TRQs."
- **OUR NOTE:** These are "dozen eggs equivalent" and cover **eggs and egg products** (CUSMA, WTO), not shell eggs alone. The page mixes 2026 allocations and 2027 calendar-year TRQs, so confirm which year a figure belongs to before quoting it as "this year".

### 11.3 TRQ administration (S33, CUSMA Serial No. 1030, verbatim)
> "This Notice to Importers sets out the policies and practices pertaining to the administration of Canada's tariff rate quota (TRQ) for eggs and egg products under the Canada-United States-Mexico Agreement (CUSMA)."
> Eligibility: "A federally-registered processed egg station (breaking eggs); A federally-registered egg grading station (table/shell eggs)".
> "The allocation to federally-registered processed egg stations (breaking eggs) is calculated first … Once the requirements of the eligible breaking egg applicants have been met, any remaining quota is allocated to federally-registered egg stations (table/shell eggs) in proportion to each station's market share…"

**WTO Serial No. 990 (S35, WebFetch summary; the quotes are as returned by the tool):** dated "October 1, 2020". It defines the product as items "falling under tariff items 04.07, 04.08, 21.06 or 35.02". Shell-egg allocations go to "Traditional allocation holders and federally-registered egg stations". The page was not opened in full by curl (connection reset), so its full text is unverified.

---

## 12. The carton logo: Egg Quality Assurance (EQA) mark, in EFC's own words

| Point | Verbatim | Source |
|---|---|---|
| What it is | "The Egg Quality Assurance™ (EQA®) program is an industry-wide initiative certifying that eggs from regulated Canadian farms meet strict food safety and animal welfare standards." | S20 |
| Origin | "The distinctive mark makes it easy to identify made-in-Canada eggs…" | S19 |
| Imports excluded | "Imported eggs are not covered by the EQA® program's standards and cannot receive EQA® certification." | S20 |
| Basis | "In order to receive and maintain their EQA® certification, Canadian egg farmers must meet the requirements of both the national Animal Care Program and Start Clean-Stay Clean® on-farm food safety program." | S19 |
| Audits (EFC's words) | "Quality is achieved through five key principles: critical requirements, verification, third-party auditing, continuous improvement and farmer commitment." | S19 |
| Animal Care Program (EFC's words) | "The Animal Care Program enforces over 100 requirements…" | S20 |
| Voluntary display | "However, using the mark is voluntary. Even if some egg cartons and egg products do not feature the certification mark, they could still meet the standards of the EQA® program." | S20 |
| Not a grade | "The EQA® program and its certification mark are focused on Canadian origin, egg farming practices, food safety and animal welfare. In contrast, the grading ratings relate to the eggs' weight, shell quality and the condition of the yolk and white." | S20 |
| Who oversees | "Egg Farmers of Canada oversees the EQA® program…" | S20 |
| Launch year | "The EQA® program was launched in 2019…" | S20 |
| Cost / licence | "There are no costs for egg farmers, graders, processors, retailers or foodservice providers to obtain licensing and use the EQA® certification mark." | S20 |

- **On-air caution:** EFC's description of EQA includes "food safety" wording. Under the house rules, on air we say only that **EFC says the EQA mark identifies made-in-Canada eggs from regulated farms that meet EFC's national programs, and that imported eggs cannot carry it**. We do not paraphrase any safety meaning.
- **OUR NOTE:** EQA is an industry certification mark run by EFC. It is not a government mark. We did not find a "Canada Egg" logo by that name. The EFC logo that appears on cartons is the EQA mark.

---

## 13. CFIA licensing of egg grading

- **SFCR s.7(2)(a)(i) (S1):** for any food "that is to be exported or sent or conveyed from one province to another", these are prescribed activities that need a licence: "manufacturing, processing, treating, preserving, **grading**, packaging and labelling…".
- **SFCR s.308(1)(d):** a licence holder may apply a grade name to an egg only if, among other conditions, "the food has been graded by a licence holder".
- **SFCR s.332(1):** "A licence holder may grade an egg only if…" (see §2).
- **CFIA (S6) scope:** "shell eggs include only eggs of domestic chickens (of the species Gallus domesticus) that are graded in a grading station operated by a license holder (unless otherwise noted)."
- **EFC (eggs.ca, https://eggs.ca/faq/what-is-an-egg-grading-station/), attributed:** "Once eggs have left the farm, they go through the grading station where they are washed, candled, weighed and packed. All grading stations are registered and inspected by the Canadian Food Inspection Agency."
- **OUR NOTE:** "Registered" is the old Egg Regulations term. Under the SFCR the term is "licence holder". Grading stations that sell only within one province may fall under provincial rules (S6). EFC's "all grading stations" wording is attributed to EFC, and we did not confirm it against a CFIA list (see UNVERIFIED). Global Affairs still uses "federally-registered egg grading station" in its 2020 notice (S33).

---

## 14. In-store checklist: what each carton feature lawfully tells a shopper

| Carton feature | What it DOES tell you (per rule or source) | What it does NOT tell you | Basis |
|---|---|---|---|
| **"CANADA A" inside a maple-leaf outline** | The eggs were graded to Canada A (shell, air cell ≤ 5 mm at grading, yolk centring and outline, albumen firmness, size) by a licence holder. | It does **not** say the eggs were laid in Canada. Imported eggs graded by a Canadian licence holder use the Canadian grade name. It says nothing about hen housing, feed or brand. At retail, air-cell depth is not counted for under-grades. | S4 s.4; S5 s.1(2); S6; S18 (EFC); S25 (BC Egg) |
| **Size word (Large, XL, …)** | Each egg meets the minimum weight for that size (for example Large ≥ 56 g). Required on Canada A. | It does not set the carton's total weight. "Large" is a per-egg minimum. It says nothing about quality beyond the grade. | S4 s.5; S1 s.316 |
| **"12" / "one dozen"** | Net quantity by count (mandatory). | — | S6; S1 s.244.1(b) |
| **Best before date** | Mandatory durable life date. Per EFC, the time "the eggs will maintain Grade A quality, if stored properly". | It is not a lay date or a packing date. No legal fixed number of days (EFC says "normally 28 to 35 days from the date of packing"). | S3 B.01.007; S6; eggs.ca (attributed) |
| **Name and address on carton** | Who the eggs were packed or labelled by or for (mandatory). | It is not necessarily the farm. It can be the packer, wholesaler or retailer. | S1 s.218(1)(b) |
| **Lot code / station-type number** | The lot code is required for traceability. | We found no current rule that defines a "station number" on cartons. The old repealed rule required a registration number only on non-carton containers. Do not decode it on air. | S1 s.92(2); S2a s.17 |
| **"Product of [country]"** | Mandatory on imported eggs, on the top or side of the carton, ≥ 1.5 mm. | — | S1 s.256 |
| **"Product of Canada" / "Canadian"** | A voluntary claim. If used, "all or virtually all" Canadian. "Canadian" counts as "Product of Canada". | Its absence does not mean imported. Domestic eggs are not required to say it. | S8; S18 |
| **The word "local"** | CFIA policy: produced in the province or territory of sale, or within 50 km across a border. | — | S8 |
| **A maple leaf (outside the grade mark)** | Nothing by itself. CFIA: vignettes "on their own" do not always imply Canadian origin. | Not an origin claim on its own. | S8 |
| **EQA® mark** | EFC says it identifies made-in-Canada eggs from regulated farms that meet EFC's national programs. Imported eggs cannot carry it. | It is voluntary to display, so absence does not mean non-Canadian. It is an industry mark, not a government mark, and not a grade. | S19; S20 |
| **"Free run"** | Industry meaning (EFC): hens "roam the entire barn floor". NFACC: no outdoor access. | No CFIA legal definition. It is subject only to the general false or misleading prohibition and CFIA's substantiation expectation. It says nothing about outdoor access. | S16; S13; S7 |
| **"Free range"** | Industry meaning (EFC): outdoor access "when weather permits" and "only seasonally available in Canada". BC: ≥ 120 days a year, 6 h per day (provincial standard). EFC reports a national certification program approved for "early 2026". | No CFIA legal definition. It does not mean year-round outdoor access. National program details are not public (unverified). | S16; S26; S14; S7 |
| **"Enriched" / "furnished" / "nestlaid"-type words** | Industry meaning: small-group housing with perches, nest area and scratch area. NFACC calls it an "Enriched Cage". | No CFIA legal definition. In CFIA's nutrient sense, "enriched" is not to be used for shell eggs. | S16; S13; S6 |
| **"Cage-free"** | BC Egg: covers free run, free range and organic. NFACC: "non-cage". | No CFIA legal definition. | S25; S13 |
| **"Pasture-raised" / "pastured"** | — | No CFIA, EFC or NFACC definition found. Only the general false or misleading prohibition applies. | S6; S7; S16; S13 |
| **"Organic" / Canada Organic logo** | Legally defined. Certified under the Canada Organic Regime to CAN/CGSB-32.310. The certifier's name must appear. The standard bars cages ("row, battery, enriched or colony cages") and requires outdoor access "subject to weather and ground conditions" and for "at least one third of its laying life". | It does not mean year-round outdoor access. Imported organic eggs bearing the logo must say "Product of" or "Imported". | S1 ss.353–359; S9; S11 |
| **"Omega-3" (printed name)** | It is a word in the product name or shell print. Read it on air **only as a name**. CFIA's labelling term for nutrients raised via feed is "enhanced". | We give **no explanation** of benefit (house rule). | S6 (terminology only) |
| **"Fresh" / "Natural"** | CFIA: "all eggs are fresh" and "all eggs are natural". The words are allowed only as "all eggs are…" or "like all eggs…" statements. | Not a differentiator between brands. | S6 |
| **"Farm fresh"** | Implies the farm graded its own eggs on-farm and shipped them directly to the store (CFIA position). | — | S6 |
| **"No hormones"** | Must be accompanied by "the use of hormones is not permitted in poultry in Canada". | Not a differentiator. Hormones are not permitted for any Canadian hen (CFIA). | S6 |
| **"From young hens"** | Allowed. CFIA recommends stating what "young" means. "Young eggs" is not allowed. | — | S6 |
| **"No preservatives"** | CFIA: not acceptable on shell eggs. | — | S6 |
| **Brown vs white (shell colour)** | Not addressed by any grade rule we opened, other than eggs having to be "of a usual colour" to be graded. | Do not imply any quality difference (house rule 8). | S1 s.332(1)(f) |

---

## Appendix R: Recalls (DO NOT USE ON AIR)
No recall research was done for this file. This appendix is deliberately empty. Any future recall item goes here, marked "do not use on air".

---

## UNVERIFIED / DO-NOT-USE

1. **EFC national Free Range Standards Certification Program, details.** Only the annual-report description (S14) was found. No public standard text was found, so any numbers (range space, days, popholes) and whether implementation actually began in "early 2026" are unverified. Do not quote any numbers.
2. **WTO TRQ Serial No. 990 full text.** curl failed ("Connection reset by peer"). Only a WebFetch tool summary exists (S35). Use only the tariff-heading list and the date, and mark them as a summary.
3. **FPCC pages (S29–S31).** canada.ca refused curl ("Empty reply from server" / HTTP/2 error). The pages were read via WebFetch, which returns tool-extracted quotes. Re-open in a browser before an on-screen quote graphic.
4. **Which year the TRQ access quantities belong to.** The S34 page mixes 2026 allocations and 2027 calendar-year TRQs. Confirm the year before saying "this year".
5. **CAN/CGSB-32.310-2026 clauses new versus 2020.** We did not diff against the 2020 edition. The compliance window of up to 12 months may apply to new clauses. Verify before a graphic that says "required now".
6. **Grading-station number printed on cartons.** We found no current SFCR or CFIA requirement. The meaning of any number on a specific brand's carton is unverified. Do not decode it.
7. **"All grading stations are registered and inspected by the CFIA"** (eggs.ca). This is an EFC statement only. It was not checked against a CFIA licence registry, and intraprovincial-only operations may be provincially regulated.
8. **"All Canadian eggs sold in stores will feature the Canada Grade A symbol"** (EFC, S18). This is EFC's statement. No SFCR provision we opened bars Canada B at retail. Attribute it to EFC and do not present it as law.
9. **BC Egg "extra large … 63 to 69 grams"** (S25). It differs from the Compendium, which gives XL as not less than 63 g with Jumbo starting at 70 g. Do not use BC Egg's ceiling.
10. **Bill C-202 text and status.** EFC (S14) says it passed. We did not open it on LEGISinfo or Justice Laws. Attribute it to EFC only.
11. **Provincial boards other than ON and BC** (Quebec FPOQ, Alberta, Manitoba, Atlantic boards). Their housing definitions were not opened.
12. **Statistics Canada egg production and layer counts.** Not opened for this file. The EFC figures stand alone.
13. **NFACC 2025 amendment PDF** ("Layer Amendment 25_FINAL.pdf", at https://www.nfacc.ca/pdfs/codes/Layer%20Amendment%2025_FINAL.pdf). Not opened. We used the integrated HTML Code (S13) only. The tier-limit wording in §§1.1.5 and 2.6 was not extracted.
14. **CFIA S10 page "Date modified".** Not captured.
15. **The "legal paper" comparison** for 750 cm² is our arithmetic. Label it as ours if used.
16. **Excluded under the house rules (do not use):** the nutrient sentence on the eggs.ca free-run/free-range page; the EFC/EQA "food safety" descriptions beyond naming the program; CFIA health rationales on S10; any material in S14 on vaccination, HPAI or the Salmonella program; BC Egg's nutrition and antibiotic lines; the EFC "nutritious" and "fresh" marketing lines.
17. **Anything from earlier project files** (e.g. /home/user/Food/verification_log_eggs.md) that was not re-opened today. That includes the retailer pledge (RCC 2016), the MFA/Retail Insider scorecard, CBC and Reuters items, and all prices. These are outside tier (a) for this file and were not re-verified on 3 Oct 2026.

---

# Eggs video: brand dossiers. Who makes the eggs on the Canadian shelf (2026)

Compiled **3 Oct 2026**. Every URL in this file was opened on **3 Oct 2026** (UTC times are given where they matter). Quotes are verbatim from the page as fetched. "OUR NOTE" marks our own reading or arithmetic. It is not a source quote. Companion files: `eggs_rules_labels.md` (rules, label definitions, EFC housing figures) and `eggs_prices.md` (price study). This file covers brands, owners, labels and pledges.

**House-rule compliance for this file**
- No health, nutrition, food-safety, salmonella or avian-influenza content. Where a company or retailer page mixes such copy into a product or company description, that copy is cut and the cut is marked "[…]". "Omega-3" / "Omega 3" / "Omega Plus" / "Born 3" / "Golden D" appear only as printed product names. They are not explained.
- Animal-welfare items are given only as what the company, retailer, code or regulator literally says. We add no characterisation.
- Prices appear only from a retailer's own site/API, with banner, store or region, pack, price and our computed price per egg.
- Private-label packers: **no packer is named for any private label in this file.** No label image, retailer page, CFIA/court record or tier (b) report opened today named one. See UNVERIFIED #1.
- No U.S. or U.K. figure is presented as Canadian. Foreign figures are labelled.
- Taste, yolk colour and freshness appear only inside a company's own attributed words, or are cut.
- Recalls: none are discussed. The recall appendix (§9) is empty by design.

---

## 0. Method and source register

### 0.1 How the shelf was enumerated (retailers' own sites only)

| Channel (tier a: retailer's own site/API) | Store / region the site applied | What was run | Capture window (UTC, 3 Oct 2026) | Result |
|---|---|---|---|---|
| Loblaw banners via PC Express API `POST https://api.pcexpress.ca/pcx-bff/api/v1/products/search`, details via `GET https://api.pcexpress.ca/pcx-bff/api/v1/products/{code}` | 13 stores: Loblaws Bullock Dr, Markham ON (1032); Loblaws City Market Vancouver Post, Vancouver BC (7155); RCSS Heritage Meadows Way, Calgary AB (1539); RCSS Marine Dr, Vancouver BC (1517); RCSS Portage Ave, Winnipeg MB (1508); RCSS Albert St, Regina SK (1533); RCSS Argentia Rd, Mississauga ON (1080); Bo's No Frills Richmond St W, Toronto ON (7952); Kevin's No Frills Elbow Dr SW, Calgary AB (3155); Dean's No Frills Fraser St, Vancouver BC (3410); Atlantic Superstore Young St, Halifax NS (0354); Provigo av. des Canadiens-de-Montréal, Montréal QC (7297); Maxi Ste-Catherine Est, Montréal QC (9528) | 10 generic terms ("eggs", "large eggs", "free run eggs", "free range eggs", "organic eggs", "omega 3 eggs", "brown eggs", "liquid egg", "egg whites", "oeufs") at all 13 stores, up to 96 results each; 24 brand-name terms at 6 stores; 114 product-detail calls | 03:56–04:03 | 165/165 searches + 144 brand searches returned 200. 113 egg listings kept after removing chocolate, pet food, cookware etc. |
| Voilà by Sobeys, `https://voila.ca` (category pages + search, then the site's own product API `PUT https://voila.ca/api/webproductpagews/v6/products`) | **No address set.** Page state: `"regionName":"Default Region 1"`. The catalogue mixes brands from several provinces, so **region is not established** for Voilà prices | Category "Dairy & Eggs > Eggs" (`/categories/dairy-eggs/eggs/WEB2493021`, 221 items) and "Whole Eggs" (`/categories/dairy-eggs/eggs/whole-eggs/WEB39215426`, 184 items) + 17 searches | 03:58–03:59 | 219 items in the Eggs category tree |
| Save-On-Foods storefront gateway `https://storefrontgateway.saveonfoods.com/api/stores/{store}/preview?q=…` and `/products/{sku}` | Store 1982 = Save-On-Foods, 19855 92a Ave, Langley Twp BC; store 6634 = "Heritage", #100-8855 MacLeod Trail SW, Calgary AB (store identities from Save-On's own store list captured 30 Sep 2026 in this project) | Preview returns only 3 items per query, so **105 queries per store** were run (generic + brand-name terms) | 04:02–04:03; details 04:19 | 105/105 per store returned 200 |
| Walmart Canada, `https://www.walmart.ca/en/search?q=…` with a **mobile** user agent | Page data: postal code **L5V 2N6** (Mississauga ON), store **1061** | 15 search attempts | 04:03–04:05 (retries to 04:28) | 11 searches parsed (04:03–04:05); "18 eggs" at 04:05 and all later calls, including every product page, were redirected to `walmart.ca/blocked`. See UNVERIFIED #6 |
| Metro, via Metro's own host `https://api2.metro.ca` (www.metro.ca returns 403) | Store shown in page header: **"Metro Devonshire"** (default; no address shown) | Aisle `…/aisles/dairy-eggs/eggs` + sub-aisles whole-eggs, organic-eggs, liquid-eggs-egg-whites; 7 product pages | 04:06–04:26 | 40 unique tiles. Search URLs on api2 returned 403. Pages 2+ of the aisle load by script and returned no tiles, so **the Metro list may be incomplete** |
| Giant Tiger, Shopify collection feed `https://www.gianttiger.com/collections/eggs/products.json?limit=250` + `/search/suggest.json` | Online listings tagged by province; **every egg listing carries `in_store_only:true`** | 1 collection + 7 suggest queries | 04:07–04:08 | 83 products in the "eggs" collection |
| Costco: costco.ca search API (`https://search.costco.ca/api/apps/www_costco_ca/query/www_costco_ca_search`) and Costco Same-Day (`https://sameday.costco.ca`, operated by Instacart) | costco.ca: online locations 894_0-edi / 801-bd; Same-Day: postal **L5V2N6** | 9 search terms; 3 Same-Day product pages | 04:07–04:09 | **costco.ca online: no shell eggs listed.** Same-Day: 1 egg item priced at L5V2N6 |
| Farm Boy, `https://www.farmboy.ca` (product catalogue; no online prices) | n/a | site search "eggs" | 04:23 | 1 own-label shell-egg product |

Raw captures: `/tmp/claude-0/-home-user-Food/63b91656-26a4-59d5-baf9-bd65edc4c0dd/scratchpad/eb/` (`lb/`, `lbd/`, `vo/`, `sof/`, `wm/`, `metro/`, `gt/`, `cs/`, `sd/`, `img/`, `src/`). Brand index: `eb/brands_found.json`. Full Loblaw price rows: `eb/prices_lb.md`.

### 0.2 Company, retailer and news sources opened today

| ID | Source | URL opened | Tier | Page's own date | Status |
|---|---|---|---|---|---|
| C1 | Burnbrae Farms website (live) | https://www.burnbraefarms.com/en/ (and /en/about-us/, naturegg.com, sitemap) | a | — | **403 "Your request was blocked." on every URL, curl and WebFetch.** Company pages below were read from Internet Archive captures of burnbraefarms.com |
| C1a | Burnbrae "Our Farms" (Wayback capture 19 Jun 2026) | https://web.archive.org/web/20260619032819/https://www.burnbraefarms.com/en/our-farms/ | a (company page, archived copy) | capture 2026-06-19 | 200 |
| C1b | Burnbrae "Animal welfare" (Wayback 16 Jul 2026) | https://web.archive.org/web/20260716053147/https://www.burnbraefarms.com/en/our-values/animal-welfare | a (archived) | capture 2026-07-16 | 200 |
| C1c | Burnbrae blog "Consumer choice" (Wayback 10 Mar 2026) | https://web.archive.org/web/20260310193642/https://www.burnbraefarms.com/en/blog/consumer-choice | a (archived) | no on-page date; capture 2026-03-10 | 200 |
| C1d | Burnbrae "Statement: It's the right thing to do" (Wayback 15 Jan 2026) | https://web.archive.org/web/20260115211038/https://www.burnbraefarms.com/en/blog/statement-its-the-right-thing-to-do | a (archived) | page date **April 12, 2024** | 200 |
| C1e | Burnbrae "Burnbrae Farms statement" (Wayback 13 Jun 2026) | https://web.archive.org/web/20260613215912/https://www.burnbraefarms.com/en/blog/burnbrae-farms-statement | a (archived) | no on-page date | 200 |
| C1f | Burnbrae blog post "…we champion choice" (title abridged; it contains nutrition wording) (Wayback 20 Jan 2026) | https://web.archive.org/web/20260120163352/https://www.burnbraefarms.com/en/blog/local-nutritious-affordable-eggs-we-champion-choice | a (archived) | no on-page date | 200 |
| C1g | Burnbrae release, Strathroy plan (Feb 2024) (Wayback 9 Aug 2025) | https://web.archive.org/web/20250809051906/https://www.burnbraefarms.com/en/blog/burnbrae-farms-announces-plan-to-build-a-new-state-of-the-art-egg-grading-facility-in-strathroy-ontario | a (archived) | "February 2, 2024" | 200 |
| C1h | Burnbrae release via GlobeNewswire, reprinted on thecanadianpressnews.ca | https://www.thecanadianpressnews.ca/globenewswire_press_releases/burnbrae-farms-announces-plans-to-break-ground-on-local-state-of-the-art-egg-grading/article_ab902a55-4ff6-528b-9b53-4355019f983f.html | a (company release) | "Aug. 08, 2025" | 200 |
| C1i | Burnbrae "The Vision of Two Local Eastern Ontario Farm Kids" (Wayback 16 May 2026) | https://web.archive.org/web/20260516143603/https://www.burnbraefarms.com/en/blog/burnbrae-farms-the-vision-of-two-local-eastern-ontario-farm-kids | a (archived) | "May 16, 2026" on page | 200 |
| C1j | Burnbrae "Raising the bar for animal welfare at Burnbrae Farms" (Wayback 15 Oct 2025) | https://web.archive.org/web/20251015044151/https://www.burnbraefarms.com/en/blog/raising-the-bar-for-animal-welfare-at-burnbrae-farms | a (archived) | no on-page date | 200 |
| C1k | Burnbrae "Canada Soccer / Eggs Get Goals" GlobeNewswire release | https://www.globenewswire.com/news-release/2026/06/11/3310525/0/en/burnbrae-farms-teams-up-with-canada-soccer-to-launch-eggs-get-goals-national-activation.html | a | 11 Jun 2026 (URL) | **curl failed (000)**; headline seen only in Burnbrae's archived "Our Farms" page. Not used for facts |
| C2 | Country Grocer supplier page "Island Eggs" (retailer's own site) | https://www.countrygrocer.com/supplier/island-eggs/ | a (retailer page) | undated | 200 |
| C2x | islandeggs.com | https://islandeggs.com/ and /company-overview.html | a | — | **403** |
| P1 | P&H Foods, "New beginnings: We're now P&H Foods Inc." | https://phfoods.ca/new-beginnings/ | a | page metadata `datePublished` 2025-10-10 | 200 |
| P2 | P&H Foods, "Gray Ridge Eggs Unveils Canada's Largest Egg Grading Station…" | https://phfoods.ca/gray-ridge-eggs-unveils-canadas-largest-egg-grading-station-at-expanded-facility-in-listowel-ontario/ | a | `datePublished` 2026-03-02 | 200 |
| P3 | P&H Foods, Atlantic Canada joint venture | https://phfoods.ca/atlantic-poultry/ | a | `datePublished` 2026-06-01 | 200 |
| P4 | Parrish & Heimbecker release, same JV | https://parrishandheimbecker.com/news/parrish-heimbecker-expands-ph-foods-business-with-atlantic-canada-joint-venture/ | a | "June 1, 2026" | 200 |
| P5 | Parrish & Heimbecker, "P&H Foods Inc." division page | https://parrishandheimbecker.com/ph-foods-inc/ | a | undated | 200 |
| P6 | Parrish & Heimbecker home page | https://parrishandheimbecker.com/ | a | © 2026 | 200 |
| P7 | P&H Foods "Our History" | https://phfoods.ca/our-history/ | a | undated | 200 |
| P8 | P&H Foods affiliate page "Golden Valley" | https://phfoods.ca/our-affiliates/golden-valley/ | a | undated | 200 |
| P9 | P&H Foods affiliate page "Gray Ridge Egg Farms" | https://phfoods.ca/our-affiliates/gray-ridge-egg-farms/ | a | undated | 200 |
| P10 | P&H Foods "Our Affiliates" and "Our Brands – Retail" | https://phfoods.ca/our-affiliates/ ; https://phfoods.ca/our-brands/retail/ | a | undated | 200 |
| P11 | Gray Ridge "Our History", "Hen Care", home | https://grayridge.com/about-gray-ridge/our-history/ ; https://grayridge.com/hen-care/ ; https://grayridge.com/ | a | undated | 200 |
| P12 | GoldEgg home | https://goldegg.ca/ | a | undated | 200 |
| P13 | Sparks Eggs home | https://sparkseggs.com/ | a | undated | 200 |
| P14 | Rabbit River Farms home | https://rabbitriverfarms.com/ | a | "Copyright 2015" | 200 |
| P15 | goldenvalleyeggs.com / goldenvalleyeggs.ca | https://www.goldenvalleyeggs.com/ | — | — | 200 but the page only redirects to "/lander" (no company content) |
| P16 | conestogafarms.ca | https://www.conestogafarms.ca/ | — | — | redirected to https://grayridge.com/conestogafarms/ which returned **404** |
| P17 | Farmer's Finest Eggs home | https://farmersfinesteggs.ca/ | a | undated | 200 |
| L1 | Lovo (formerly Nutri Group), "Who We Are" | https://lovo.co/en/who-we-are/ | a | `datePublished` 2026-09-08 | 200 |
| L2 | Lovo release on newswire.ca, "Lovo: Nutri Group's new name hits grocery store shelves" | https://www.newswire.ca/news-releases/lovo-nutri-group-s-new-name-hits-grocery-store-shelves-839212087.html | a (company release) | "Sept. 22, 2026" | 200 |
| L3 | Lovo press release "New Identity, New Approach: Groupe Nutri Becomes Lovo" (old nutrigroupe.ca URL redirects here) | https://lovo.co/en/press-releases/new-identity-new-approach-groupe-nutri-becomes-lovo/ | a | "May 7, 2026" | 200 |
| L4 | Lovo press release "Star Egg Company joins Nutri Group network" | https://lovo.co/en/press-releases/star-egg-company-joins-nutrigroupe-network/ | a | `datePublished` 2017-10-10 | 200 |
| L5 | Lovo press release "Groupe Nutri acquires new industrial space" | https://lovo.co/en/press-releases/groupe-nutri-acquires-new-industrial-space/ | a | (see §3.5) | 200 |
| L6 | Saskatchewan Egg Producers, "About" | https://www.saskegg.ca/about | a (provincial egg board) | undated | 200 |
| L7 | nutrigroupe.ca Maritime Pride business-unit URLs | https://nutrigroupe.ca/en/business-units/maritime-pride-eggs/ | a | — | **redirected to https://lovo.co/en/who-we-are/** (no Maritime Pride page). Maritime Pride facts below come from the carton image only |
| O1 | Organic Meadow home and FAQ | https://organicmeadow.com/ ; https://organicmeadow.com/ENGLISH-FAQ.htm | a | © 2026 | 200 |
| O2 | yorkshirevalleyfarms.com | https://yorkshirevalleyfarms.com/ | a | — | **connection closed by egress (000)**; see UNVERIFIED #9 |
| O3 | Maple Lodge Farms home | https://maplelodgefarms.com/ | a | — | 200 |
| V1 | Vital Farms, Inc., Form 10-K for fiscal 2025 (SEC EDGAR) | https://www.sec.gov/Archives/edgar/data/1579733/000119312526073423/vitl-20251228.htm | a | FY ended 28 Dec 2025 | 200 |
| R1 | Retail Council of Canada release, 18 Mar 2016 (newswire.ca) | https://www.newswire.ca/news-releases/retail-council-of-canada-grocery-members-voluntarily-commit-to-source-cage-free-eggs-by-the-end-of-2025-572574901.html | a | "March 18, 2016" | 200 |
| R2 | Loblaw Companies Ltd, "Responsible sourcing" | https://www.loblaw.ca/en/responsible-sourcing/ | a | page links the "2025 Priority ESG Disclosure Report" | 200 |
| R2a | Loblaw "Animal Welfare Principles" PDF | https://dis-prod.assetful.loblaw.ca/content/dam/loblaw-companies-limited/creative-assets/loblaw-ca/responsibility-/Animal%20Welfare%20Statement_EN.pdf | a | PDF created 2025-06-23 | 200 |
| R2b | Loblaw 2025 Priority ESG Disclosure Report PDF | https://dis-prod.assetful.loblaw.ca/content/dam/loblaw-companies-limited/creative-assets/loblaw-ca/responsibility-/Loblaw%202025%20Priority%20ESG%20Disclosure%20Report_EN.pdf | a | PDF created 2026-02-25 | 200; **contains no egg or cage wording** (text search) |
| R3 | Empire/Sobeys Fiscal 2025 Sustainable Business Report PDF (Wayback copy of company PDF, captured 2 Aug 2025) | https://web.archive.org/web/20250802221048id_/http://sobeyssbreport.com/wp-content/uploads/2025/07/Fiscal-2025-Sustainable-Business-Report_EN.pdf | a (archived) | July 2025 | 200 (live sobeyssbreport.com and corporate.sobeys.com returned **403**) |
| R3a | Sobeys SBR 2024 "Ethical & Sustainable Sourcing" (Wayback 7 Feb 2026) | https://web.archive.org/web/20260207160526/https://www.sobeyssbreport.com/sustainable-business-report-2024/ethical-sustainable-sourcing/ | a (archived) | 2024 report | 200 |
| R4 | Metro Inc., "Animal Welfare & Responsible Procurement" | https://corpo.metro.ca/en/corporate-social-responsibility/delighted-customers/animal-welfare.html | a | update block dated "June 2021" | 200 |
| R5 | Walmart Inc., ESG "Animal Welfare" | https://corporate.walmart.com/purpose/esgreport/animal-welfare | a | FY2026 data | 200 (U.S. figures only) |
| R6 | Costco, "Animal Welfare" | https://www.costco.com/f/-/animal-welfare | a | FY2025 data | 200 (global) |
| R7 | Metro "Our products and private brands" | https://api2.metro.ca/en/our-products-private-brands | a | undated | 200 |
| R8 | Pattison Food Group home | https://pattisonfoodgroup.com/ | a | undated | 200 |
| R9 | Costco "Kirkland Signature" page | https://www.costco.ca/f/-/kirkland-signature | a | undated | 200 |
| R10 | Giant Tiger "Giant Value" page | https://www.gianttiger.com/pages/giant-value | a | undated | 200 |
| R11 | Walmart Inc. release, Great Value redesign (U.S.) | https://corporate.walmart.com/news/2026/04/15/walmart-unveils-modern-redesign-of-great-value-its-flagship-private-brand | a | "April 15, 2026" | 200 |
| R12 | Empire, Farm Boy purchase completed (on farmboy.ca) | https://www.farmboy.ca/company-news/empire-company-completes-purchase-of-farm-boy-ontarios-best-in-class-food-retailer/ | a | `datePublished` 2018-12-10 | 200 |
| R13 | Empire release, Longo's 51% completed (newswire.ca) | https://www.newswire.ca/news-releases/empire-completes-purchase-of-51-per-cent-of-longo-s-and-grocery-gateway-accelerates-growing-presence-in-ontario-847409095.html | a | "May 10, 2021" | 200 |
| N1 | CBC News, Susan Noakes, "Cage-free eggs only a goal for major Canadian grocers by 2025" | https://www.cbc.ca/news/business/retail-council-cage-free-eggs-1.3497958 | b | Mar 18, 2016 | 200 |
| N2 | La Presse, Stéphanie Bérubé, "Production d'œufs: Nutri fait coquille neuve" | https://www.lapresse.ca/affaires/entreprises/2026-03-28/production-d-oeufs/nutri-fait-coquille-neuve.php | b | 2026-03-28 | 200 |
| N3 | CTV News London, Scott Miller (video report), "'450,000 dozen per day': Listowel now home to largest egg grading facility in Canada" | https://www.ctvnews.ca/london/article/450000-dozen-per-day-listowel-now-home-to-largest-egg-grading-facility-in-canada/ | b | Jan 16, 2026 | 200 (page carries the video and headline; no article text) |
| N4 | Midwestern Newspapers (Listowel Banner), Nicole Beswitherick, "Listowel home to largest, most advanced egg grading facility in Canada" | https://midwesternnewspapers.com/listowel-home-to-largest-most-advanced-egg-grading-facility-in-canada/ | b | Jan 22, 2026 | 200 (paywalled after first paragraph) |
| N5 | Daily Commercial News (ConstructConnect), "Egg-cellent: Burnbrae Farms expands its footprint in Strathroy" | https://canada.constructconnect.com/dcn/news/projects/2026/01/egg-cellent-burnbrae-farms-expands-its-footprint-in-strathroy | b (byline is the outlet, "Daily Commercial News", not a named reporter) | 2026-01-27 | 200 |

---

## 1. The shelf: every egg brand found on retailers' own sites, 3 Oct 2026

"Brand as shown" is normalised only for spelling variants of the same retailer brand field (e.g. "Goldegg", "Gold Egg", "GoldEgg" → GoldEgg; "Nutri-Egg", "Nutri Group", "Nutri" → Nutri). Numbers in brackets = distinct listings. Voilà's region is unset (see §0.1), so a Voilà listing proves the brand is in Voilà's catalogue, not that a given store carries it.

| # | Brand as shown (normalised) | Retailer channel(s) where found on 3 Oct 2026 | Example listing (exact retailer name) | Example URL |
|---|---|---|---|---|
| 1 | Alderwood Farms | Loblaw (2) | Pasture-Raised Eggs (12 ea) | https://www.loblaws.ca/pasture-raised-eggs/p/21434214001_EA |
| 2 | Avalon | SaveOn-1982 (3), Voila (2) | AVALON - Large Brown Eggs, Organic | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00066939060010 |
| 3 | Born 3 | SaveOn-1982 (1) | Born 3 - Omega-3 Large Eggs | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00666933900420 |
| 4 | Britestone | Voila (3) | Britestone Brown Eggs Super Large 12 Count | https://voila.ca/products/911424EA/details |
| 5 | Burnbrae Farms | GiantTiger (53), Loblaw (24), Metro (5), SaveOn-1982 (1), SaveOn-6634 (5), Voila (29), Walmart (3) | Burnbrae Farms Eggs2go! Peeled Hard Boiled Eggs, 2-Pack, 88 g | https://www.gianttiger.com/products/burnbrae-farms-eggs2go-peeled-hard-boiled-eggs-2-pack-88-g-3 |
| 6 | Burnbrae Farms (EGGS2go!) | Voila (2) | Eggs2go Eggs Hard Boiled Peeled Dill 2 x 42 g  | https://voila.ca/products/694137EA/details |
| 7 | Burnbrae Farms (Naturegg) | Metro (1), SaveOn-1982 (1), SaveOn-6634 (1), Voila (2), Walmart (1) | Simply Egg Whites™ Free Run Liquid Egg Whites (500 g) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/liquid-eggs-egg-whites/simply-egg-whites-free-run-liquid-egg-whites/p/065651005262 |
| 8 | Burnbrae Farms (Prestige) | GiantTiger (6), Voila (1) | Prestige Club Pack Large Eggs, 18-Pack | https://www.gianttiger.com/products/prestige-club-pack-large-eggs-18-pack-6 |
| 9 | Burnbrae Farms (Super Bon-ee) | GiantTiger (1) | Super Bon-EE Extra Large Eggs, 12-Pack | https://www.gianttiger.com/products/super-bon-ee-extra-large-eggs-12-pack |
| 10 | Canadian Harvest | Voila (1) | Canadian Harvest Brown Eggs Large 12 Count | https://voila.ca/products/843779EA/details |
| 11 | Coldspring Farm | Loblaw (1), Voila (1) | Eggs, Maritime Pride Free Range Size Large 12  (12 ea) | https://www.atlanticsuperstore.ca/eggs-maritime-pride-free-range-size-large-12/p/21340326001_EA |
| 12 | Coligny Creek | Loblaw (2) | Free Range Eggs, Brown, 18 Count (18 ea) | https://www.realcanadiansuperstore.ca/free-range-eggs-brown-18-count/p/21751043001_EA |
| 13 | Compliments | Voila (19) | Compliments White Eggs Medium Value Size 30 Count | https://voila.ca/products/627001EA/details |
| 14 | Compliments Balance | Voila (1) | Compliments Balance Omega 3 Brown Eggs Large 12 Count | https://voila.ca/products/337988EA/details |
| 15 | Compliments Organic | Voila (3) | Compliments Organic Brown Eggs Free Range Grade A Large 12 Count | https://voila.ca/products/732323EA/details |
| 16 | Conestoga Farms | Loblaw (5), Metro (7), Voila (10), Walmart (4) | Brown Eggs Free Run Omega-3 Size: Large (18 ea) | https://www.loblaws.ca/brown-eggs-free-run-omega-3-size-large/p/21542380001_EA |
| 17 | Country Golden Yolks | Loblaw (1), Voila (2) | Country Golden Yolk Large Free Range Eggs (12 ea) | https://www.loblaws.ca/country-golden-yolk-large-free-range-eggs/p/20905536001_EA |
| 18 | Countryside | Loblaw (1), Voila (1) | XL 18 White Eggs    (18 ea) | https://www.realcanadiansuperstore.ca/xl-18-white-eggs/p/20819781001_EA |
| 19 | Daybreak Farms | Voila (3) | Daybreak Farms Brown Eggs Free Run Large 12 Count | https://voila.ca/products/861907EA/details |
| 20 | Delong Farms | GiantTiger (2), Voila (1) | Large Brown Eggs, 12-Pack | https://www.gianttiger.com/products/large-brown-eggs-12-pack |
| 21 | Eyking Farm | Voila (2) | Eyking Farm Eggs Jumbo Value Size 12 Count | https://voila.ca/products/870469EA/details |
| 22 | Farm Boy | FarmBoy (1) | Farm Boy™ Large White Eggs (dozen) | https://www.farmboy.ca/products/farm-boy-large-white-eggs-dozen/ |
| 23 | Farmer John | GiantTiger (1) | Farmer John Eggs, Large, 12-Pack | https://www.gianttiger.com/products/farmer-john-eggs-large-12-pack-1 |
| 24 | Farmer's Finest | Loblaw (2), SaveOn-6634 (4), Voila (1) | Free Range, Large Eggs (12 ea) | https://www.nofrills.ca/free-range-large-eggs/p/20881824001_EA |
| 25 | Foremost | Loblaw (1) | Large Size Eggs 18 Pack (18 ea) | https://www.loblaws.ca/large-size-eggs-18-pack/p/20976887001_EA |
| 26 | Gamble Farm | Voila (3) | Gamble Farm White Eggs Free Run 12 Count | https://voila.ca/products/605820EA/details |
| 27 | Gerber's Farm | Voila (2) | Gerber's Farm White Eggs Grade A Large 12 Count | https://voila.ca/products/861905EA/details |
| 28 | Giant Tiger ("Best Value") | GiantTiger (3) | Burnbrae Farms Extra Large Eggs, 12-Pack | https://www.gianttiger.com/products/burnbrae-farms-extra-large-eggs-12-pack |
| 29 | GoldEgg | Loblaw (6), Metro (4), SaveOn-1982 (5), SaveOn-6634 (7), Voila (13), Walmart (3) | Omega 3 Brown Eggs, Large (12 ea) | https://www.realcanadiansuperstore.ca/omega-3-brown-eggs-large/p/20822561001_EA |
| 30 | Golden Valley | Loblaw (2), SaveOn-1982 (4), Voila (4) | White Eggs, Extra Large (18 ea) | https://www.loblaws.ca/white-eggs-extra-large/p/20819851001_EA |
| 31 | Gray Ridge | GiantTiger (2), Loblaw (10), Metro (8), Voila (12), Walmart (4) | Large Brown Eggs | https://www.gianttiger.com/products/large-brown-eggs |
| 32 | Great Value | Walmart (5) | Great Value Large 12 Eggs | https://www.walmart.ca/en/ip/Great-Value-Large-12-Eggs/10052944 |
| 33 | Green Valley | Loblaw (1), Voila (2) | Brown Eggs Free Range Farm Large (12 ea) | https://www.loblaws.ca/brown-eggs-free-range-farm-large/p/21185920_EA |
| 34 | Harman | Loblaw (1) | Eggs 18ct      (18 ea) | https://www.realcanadiansuperstore.ca/eggs-18ct/p/20823665001_EA |
| 35 | Hartmann | Voila (1) | Hartmann White Eggs Jumbo 12 Count | https://voila.ca/products/597856EA/details |
| 36 | Keenan Farms | Voila (1) | Keenan Farms Eggs Medium 12 Count | https://voila.ca/products/339659EA/details |
| 37 | Kirkland Signature | CostcoSameDay (1) | Kirkland Signature Free Run Large Eggs (24 ct) | https://sameday.costco.ca/store/costco-canada/products/63993483-ks-gros-oeufs-en-libert-paquet-de-24 |
| 38 | Life Smart | Metro (8) | Large Organic Brown Eggs (12 un) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-organic-brown-eggs/p/059749976817 |
| 39 | Longo's | Voila (5) | Longo's White Eggs Enriched Coop Extra Large 18 Count | https://voila.ca/products/13840EA/details |
| 40 | Lovo | Voila (25) | Lovo Pickled Eggs Wine Vinegar & Sea Salt 500 ml | https://voila.ca/products/1462897EA/details |
| 41 | Maple Hill | SaveOn-1982 (3), Voila (2) | Maple Hill - Free Range Eggs, Large Size | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00830312000036 |
| 42 | Maritime Pride | GiantTiger (5), Loblaw (5), Voila (13) | Maritime Pride Large White Eggs, 18-Pack | https://www.gianttiger.com/products/maritime-pride-large-white-eggs-18-pack-1 |
| 43 | Nature's Farm | Voila (5) | Natures Farm Organic Omega 3 Eggs Large 12 Count | https://voila.ca/products/513910EA/details |
| 44 | Newfoundland Eggs | Voila (5) | Newfoundland White Eggs Grade A Medium Value Size 30 Count | https://voila.ca/products/596090EA/details |
| 45 | No Name | Loblaw (10) | Large Size Brown Eggs 12 Pack (12 ea) | https://www.loblaws.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 46 | Nova Eggs | GiantTiger (3) | Nova Brown Eggs, Large, 12-Pack | https://www.gianttiger.com/products/nova-brown-eggs-large-12-pack-1 |
| 47 | Nutri | GiantTiger (2), Loblaw (4), Voila (8) | Nutri Maritime Pride Ultra Extra Large Size Brown Eggs, 12-Pack | https://www.gianttiger.com/products/12pk-maritime-pride-lg-brown |
| 48 | ONLY GOODNESS | SaveOn-1982 (1), SaveOn-6634 (1) | ONLY GOODNESS - Organic Large Brown Eggs | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639368401 |
| 49 | PC Blue Menu | Loblaw (6) | Blue Menu Large Size Free-Run Brown Eggs (12 ea) | https://www.loblaws.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 50 | PC Organics | Loblaw (5) | Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ea) | https://www.loblaws.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 51 | Poultry Farm Laviolette | GiantTiger (4) | Poultry Farm Laviolette Extra Large Eggs, 12-Pack | https://www.gianttiger.com/products/poultry-farm-laviolette-extra-large-eggs-12-pack |
| 52 | President's Choice | Loblaw (7) | Free Run Brown Eggs Large (12 ea) | https://www.loblaws.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 53 | Rabbit River | Loblaw (6), SaveOn-1982 (4), SaveOn-6634 (3) | Free Run Omega 3 Brown Eggs (12 ea) | https://www.loblaws.ca/free-run-omega-3-brown-eggs/p/20821369001_EA |
| 54 | Rochfort Bridge | Voila (3) | Rochfort Bridge Fresh Eggs Large Value Size 18 Count | https://voila.ca/products/848650EA/details |
| 55 | Rowe Farms | Loblaw (2), Voila (1) | Green Valley Eggs Size Large Free Run Brown (12 ea) | https://www.loblaws.ca/green-valley-eggs-size-large-free-run-brown/p/20821562001_EA |
| 56 | Selection | Metro (5) | Large Eggs (12 un) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/059749896054 |
| 57 | Sparks | Loblaw (1), SaveOn-6634 (1), Voila (1) | White Eggs, Extra Large (18 ea) | https://www.nofrills.ca/white-eggs-extra-large/p/20821162001_EA |
| 58 | Star | Loblaw (2), Voila (1) | Free Run Eggs, Large (18 ea) | https://www.realcanadiansuperstore.ca/free-run-eggs-large/p/21028407001_EA |
| 59 | Sunshine Valley | Voila (5) | Sunshine Valley Brown Eggs Free Range Extra Large 12 Count | https://voila.ca/products/584732EA/details |
| 60 | Vanderwees | Voila (2) | Vanderwees White Eggs Large 12 Count | https://voila.ca/products/843761EA/details |
| 61 | Vita | Voila (6) | Vita Original White Eggs Free Run Canada A Large Value Size 18 Count | https://voila.ca/products/507582EA/details |
| 62 | Vitala | Voila (1) | Vitala Omega 3 Brown Eggs Free Run Large 12 Count | https://voila.ca/products/282092EA/details |
| 63 | Western Family | SaveOn-1982 (11), SaveOn-6634 (10) | Western Family - Free Run Eggs | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639332921 |

**Non-hen-shell items also in the egg aisles** (listed for completeness, no dossier): pickled eggs, quail and duck eggs, plant-based "egg" liquids, scramble kits.

---

## 2. Ownership map (summary)

| Brand(s) on shelf | Owner as stated by the company itself | Chain (dated) | Family / farmer / co-op? (company's own words) | Primary source |
|---|---|---|---|---|
| Burnbrae Farms; Naturegg (Omega 3, Free Run, Solar Free Range, Omega Plus, Nestlaid, Nature's Best, Organic, Simply Egg Whites); Egg Creations; EGGS2go!; Prestige; Super Bon-ee | Burnbrae Farms (the Hudson family) | Farm bought 1891 by Joseph Hudson in Lyn ON; eggs from the 1940s; "privately owned and operated by the Hudson family since it was founded in 1891" (release, 8 Aug 2025) | "sixth generation Canadian family–owned and operated company" | C1a, C1h |
| Island Eggs (brands "Island Gold" and "Naturegg" in B.C.) | Burnbrae Farms Ltd. | "In 2007, Island Eggs was purchased by Burnbrae Farms Ltd." (retailer's supplier page) | Jensen family founders; Burnbrae "also a family-owned and operated business" | C2 |
| Gray Ridge; GoldEgg; Conestoga Farms | P&H Foods Inc., a subsidiary of Parrish & Heimbecker, Limited | L. H. Gray & Son (from 1934) → P&H relationship from **2010** → "we're now P&H Foods Inc." (post dated 10 Oct 2025 in page metadata) | P&H: "a Canadian, family owned agri-business" | P1, P5, P9 |
| Golden Valley; Born 3; Country Golden Yolks; Canadian Harvest; Rabbit River Farms | P&H Foods Inc. (Golden Valley Foods, Abbotsford BC) | as above | as above | P8, P14 |
| Sparks | P&H Foods Inc. | as above | as above | P5, P10 |
| Lovo; Nutri / Nutri-Egg; Maritime Pride (carton: "Farmer owned Maritime Pride Eggs" with the NUTRI seal) | Lovo, formerly Nutri Group (Groupe Nutri), Saint-Hyacinthe QC | "Farmer-owned since 1987"; name change announced 7 May 2026 (L3) and on shelves from 22 Sep 2026 (L2) | "Lovo is the only Canadian company owned by local farmers" (company claim); La Presse: owned by 47 Québec producers | L1–L3, N2 |
| Star (Star Egg Company, Saskatoon) | Joint venture | SaskEgg: "co-own Star Egg Company, in a joint-venture partnership with the Harman family and NutriGroupe" | provincial board + family + Nutri | L6, L4 |
| No Name; President's Choice (PC Free Run); PC Organics; PC Blue Menu | Loblaws Inc. / Loblaw Companies Ltd (carton: "LOBLAWS INC., TORONTO M4T 2S8") | retailer brand | — | label images; R2 |
| Compliments; Compliments Organic; Compliments Balance; Longo's; Farm Boy | Sobeys Inc. / Empire Company Limited (Farm Boy purchase completed Dec 2018; 51% of Longo's completed 10 May 2021) | retailer brands | — | R3, R12, R13 |
| Selection; Life Smart (Irresistibles not seen in eggs) | Metro Inc. | retailer brands | — | R7 |
| Great Value | Walmart ("its flagship private brand", Walmart Inc. U.S. release) | retailer brand | — | R11 |
| Western Family; Only Goodness | Pattison Food Group (Western Family listed as a "Corporate Brand"); Only Goodness: Save-On listing brand only | retailer brands | Pattison: "a Jim Pattison business" | R8 |
| Kirkland Signature | Costco | retailer brand | — | R9 |
| Giant Value | Giant Tiger | **no Giant Value egg listing found**; Giant Tiger lists "Best Value Eggs, Large, 12-pack" (vendor field "Giant Tiger") | — | R10, GT feed |
| Farmer's Finest | **Owner not confirmed today.** Its website's contact link points to `https://sparkseggs.com/contact-us` (a fact about the page, not an ownership statement) | — | — | P17; UNVERIFIED #10 |
| Rowe Farms / Green Valley; Vita; Sunshine Valley; Maple Hill; Coligny Creek; Alderwood Farms; Foremost; Harman; Rochfort Bridge; Britestone; Avalon; Countryside; Daybreak Farms; Gerber's Farm; Vanderwees; Eyking Farm; Gamble Farm; Delong Farms; Keenan Farms; Newfoundland Eggs; Nature's Farm; Coldspring Farm; Farmer John; Nova Eggs; Poultry Farm Laviolette; Hartmann | **Not researched to primary-source standard today** | — | — | UNVERIFIED #11 |

---

## 3. Brand dossiers

### 3.1 Burnbrae Farms (and Naturegg, Egg Creations, EGGS2go!, Prestige, Super Bon-ee, Nestlaid, Nature's Best)

**Owner and chain.** Burnbrae's own pages (live site blocked; read via Internet Archive copies C1a, C1i) and its 8 Aug 2025 release (C1h):
- "We're a sixth generation Canadian family–owned and operated company that continues to be one of Canada's leading egg farmers, with farms, grading stations and processing operations across the country." (C1a)
- "In 1891, shortly after arriving to Canada from Scotland, Joseph Hudson purchased a farm in the village of Lyn near Brockville, Ontario. He named it Burnbrae … 130 years later Burnbrae Farms remains in the Hudson family with businesses far and wide across Canada." (C1a)
- "In 1956, Burnbrae began grading eggs to ship to Steinberg's in Montreal, the company's first large grocery chain store account." (C1i, page dated May 16, 2026)
- "Burnbrae Farms is a sixth-generation family-owned Canadian company that has been producing eggs and egg products for more than 80 years. With egg grading, breaking, and farming operations in five provinces across Canada, shipping coast to coast to coast, it has been privately owned and operated by the Hudson family since it was founded in 1891." (C1h, Aug. 08, 2025)
- "Burnbrae Farms is the largest family-owned and operated egg business in Canada […]" (C1h; remainder is product-quality copy, cut)
- Trademarks (footer, C1a): "Naturegg, Naturegg Simply Egg Whites, Naturegg Nestlaid, Naturegg Nature's Best, Naturegg Omega Plus, Egg Creations, EGGS2 go! , EGG Bakes and EGG Bites are Registered Trademarks of Burnbrae Farms."
- President & CEO: Margaret Hudson (named as "president and CEO, Burnbrae Farms" in N5, tier b).
- Subsidiary: Island Eggs (Vancouver Island), bought 2007 (§3.4).

**Where graded/packed (company's words).** "egg grading, breaking, and farming operations in five provinces" (C1h). Strathroy ON: "a place we've called home for more than 45 years" (C1h). A Burnbrae blog title names a "Mississauga grading station" (CDX listing of `burnbraefarms.com/en/blog/a-bright-idea-reducing-energy-consumption-at-mississauga-grading-station`; page not opened, so treat as a lead only). **Carton station line: not legible in any retailer image opened today.**

**Front-of-pack (retailer images opened today).**

| Product (retailer listing) | What the front panel shows (verbatim where legible) | Housing words on front | Maple leaf / "Canada" wording | Image URL |
|---|---|---|---|---|
| Naturegg Omega 3 White Eggs, Large, 12 | "BURNBRAE FARMS·FERMES", "Naturegg Naturœuf", "OMEGA 3", "Eggs for Life!® · Des œufs pour la vie !MD", "12 EGGS SIZE: LARGE" | none on front | Canada Grade A mark (contains a maple leaf) | https://digital.loblaws.ca/PCX/20815563001_EA/en/1/20815563001_en_front_800.png |
| Naturegg Nest Laid White Eggs, Large, 12 | "Naturegg Naturœuf", "NESTLAID™ COCO'NIDMC", top-right panel: "FROM HENS RAISED IN ENRICHED COLONY HOUSING EQUIPPED WITH PERCHES AND NESTING AREAS"; "bullfrogpower" logo | **enriched colony** (printed) | Canada A mark | https://digital.loblaws.ca/PCX/20816075001_EA/en/1/20816075001_en_front_800.png |
| Nature's Best White Eggs, Large, 12 | "NATURE'S BEST™ OEUF NATUREL™", "VEGETARIAN FEED · NOURRITURE VÉGÉTARIENNE" (yolk-colour and other feed/production statements not transcribed) | none | Canada A mark | https://digital.loblaws.ca/PCX/20814983001_EA/en/1/6565100022_enfr_front_centre_ecomm_A_1_GS1_Ecommerce_800.png |
| Organic Free Range Eggs, 18 (listing) | "Naturegg Naturœuf", "ORGANIC BIOLOGIQUES", "FREE RANGE·PARCOURS LIBRE", Canada Organic logo. **The image shows "18 EGGS SIZE: MEDIUM"** while the listing name gives no size | **free range** + organic | Canada Organic logo (contains a maple leaf) | https://digital.loblaws.ca/PCX/21572055001_EA/en/1/6565102257_enfr_front_centre_marketing_GS1_Ecommerce_800.png |

Other Burnbrae listings seen today (names only): "Grade A Large Eggs" 18; "Grade A White Eggs, Large/Small"; "Super Bon-Ee Grade A White Eggs, Super Extra Large"; "Naturegg Free Run Eggs, Large"; "Naturegg Free Run Omega 3 Eggs"; "Naturegg Solar Free Range Eggs, Large" (Loblaw description: "Free Range: Laying hens housed in an open concept barn with outdoor access."); "Naturegg Omega Plus Solar Free Range Eggs, Large"; "Naturegg Organic White Eggs, Large"; "Farm Eggs Medium" 30; Prestige Club/Family Pack 18; "Burnbrae Farms Brown Eggs Large"; "White Eggs Overwrap Wire Basket Medium 30" (Voilà); liquid: "Egg Creations", "Naturegg Simply Egg Whites", "Naturegg Free Run Egg Whites", "Naturegg Organic Simply Egg Whites Free Range"; EGGS2go! hard-boiled. Retail URLs: §1 and `eb/brands_found.json`.

**Company's own housing/welfare commitment (verbatim, dated).**
- April 12, 2024 (C1d): "At Burnbrae Farms, hen care is a top priority. All hens, regardless of the type of housing, receive the highest standard of care based on poultry science, veterinarian recommendations and research-based best practices. It's the right thing to do." … "This is why Burnbrae continues to supply eggs from housing types like [enriched], which balances exceptional hen care and […] affordable egg production. We stand behind – and have been fully transparent about – our commitment to provide eggs from hens in all housing types endorsed by the [Code of Practice]". (Bracketed words are link text missing from the text extract; the link targets are Burnbrae's "enriched" page and the Code.)
- "Consumer choice" page (no on-page date; archive capture 10 Mar 2026) (C1c): "Along with all Canadian egg farmers, Burnbrae is committed to moving hens out of conventional cage housing before 2036 and into enriched and cage-free (free run or free range) housing. Burnbrae Farms and the hundreds of farmers we work with are on pace to achieve this timeline."
- "Burnbrae Farms statement" (no on-page date; capture 13 Jun 2026) (C1e): "Hens are raised in four housing types: 1) conventional (being phased out in 2036); 2) enriched colony (larger cages with smaller social groups) […]; 3) free run […]; 4) free range […]". Also: "We have a National Animal Care Specialist on staff, with a Ph.D. in poultry behaviour and wellbeing".
- Animal-welfare page (capture 16 Jul 2026) (C1b): "We strive to maintain high standards of animal care regardless of housing type, and support poultry science research that explores opportunities for continuous improvement. We are also committed to providing consumers with choice in the types of eggs they purchase."

**What the current line shows (OUR NOTE, from retailer listings and images opened today).** The line spans enriched colony (Nestlaid carton wording), free run, free range, organic free range, and cartons with no housing word at all (Burnbrae Farms Grade A, Prestige, Super Bon-ee, Nature's Best, Naturegg Omega 3 white). For cartons with no housing word, the housing system is **not stated** on the panels we could read; we do not infer it.

**2023–2026 news (dated).**

| Date | Item | Source (tier) |
|---|---|---|
| 2 Feb 2024 | Burnbrae "has announced its plans to construct a new state of the art egg grading facility in Strathroy, Ontario … The 100,000 plus square foot facility will be operational within the next two years" | C1g (a) |
| 7–8 Aug 2025 | Plans "to break ground" in Strathroy's Molnar Industrial Park; "Spanning more than 150,000 square feet, the new facility is scheduled to be operational late in 2026" | C1h (a) |
| 27 Jan 2026 | DCN: "Construction began in August 2025 and Hudson said construction is on track to begin egg grading operations at the new site in the fourth quarter of 2026." Also: Burnbrae "did receive a $1.2 million grant from the Municipality of Strathroy-Caradoc's Community Improvement Plan program"; Sue Hudson: "We are more than doubling our current footprint in Strathroy and it is adding close to 14 per cent to overall operations." | N5 (b; outlet byline) |
| 11 Jun 2026 | Release headline "Burnbrae Farms® Teams Up with Canada Soccer to Launch 'Eggs Get Goals™' National Activation" (headline only, as listed on Burnbrae's archived page) | C1a (a) |

**One-line reading.** Canada's largest family-owned egg company by its own description, Hudson family since 1891; its own pages commit to leaving conventional cages before 2036 and say it will keep selling enriched-colony eggs alongside free run, free range and organic.

---

### 3.2 P&H Foods Inc.: Gray Ridge, GoldEgg, Conestoga Farms, Golden Valley, Sparks

**Owner and chain (company's own words).**
- P&H division page (P5): "P&H Foods Inc., a Parrish & Heimbecker, Limited (P&H) company, serves customers across Ontario, Alberta, and British Columbia with trusted retail egg brands … Brands under the P&H Foods Inc. umbrella include Gray Ridge Egg Farms in Ontario, Golden Valley Foods in British Columbia, Sparks Eggs in Alberta, and GoldEgg serving major Canadian markets, along with value-added and industrial partners EggSolutions , Global Egg , EggSolutions Vanderpol's , EggSolutions EPIC and Perth County Ingredients – businesses previously operated by L. H. Gray & Son ."
- "New beginnings" (P1; page metadata 10 Oct 2025): "Today, we're excited to announce the next step in our journey: we're now P&H Foods Inc., a Parrish & Heimbecker, Limited (P&H) company." … "This acquisition represents the natural next step in a long-standing relationship between P&H and L.H. Gray & Son. This partnership began in 2010, when P&H first entered into business with the L.H. Gray group of companies."
- Parent (P6): "Parrish & Heimbecker, Limited (P&H) is a Canadian, family-owned agribusiness, with roots in the agriculture industry dating back to 1909." Head office in the footer: "201 Portage Avenue, Suite 1400 Winnipeg, Manitoba".
- Gray Ridge history (P11): "In 1934, Lyle and Ina Gray established an egg grading station in Southwestern Ontario. … In 1970, Ina Gray created the Gray Ridge Egg Farms brand".
- **Golden Valley owner (answering the brief's "owner?")**: P&H Foods. P&H's Golden Valley page (P8): "Since 1950, Golden Valley Eggs has been providing B.C. families with fresh eggs and egg products. Based in Abbotsford, British Columbia". The same page lists **Country Golden Yolks, Born 3, GoldEgg (B.C.), Canadian Harvest and Rabbit River Farms**. The completion date of the P&H purchase is not stated on any P&H page opened today (UNVERIFIED #12).

**Where graded/packed (company's words).** Gray Ridge: "It operates two shell egg grading stations in Strathroy and Listowel." (P9). Golden Valley: Abbotsford BC (P8; Rabbit River contact block: "Golden Valley Foods Ltd. 3841 Vanderpol Court Abbotsford, BC V2T 5W5", P14). Sparks: "Since 1976, Sparks Eggs has been a trusted egg grading partner to Alberta farmers…" (P10). Carton station line: not legible in images opened.

**"Canadian" / local wording.** Gray Ridge (P9): "with the Foodland Ontario symbol on-pack, you can rest assured that you're buying local"; "In Ontario, GoldEgg brand eggs are certified Foodland Ontario local." "All Conestoga Farms eggs are certified local by Foodland Ontario." Sparks home (P13): "Locally Produced Alberta Eggs."

**Front-of-pack (images opened).**

| Product | Front panel (verbatim where legible) | Housing words | Maple leaf / origin | Image URL |
|---|---|---|---|---|
| Gray Ridge Grade A Brown Eggs, Large, 12 | "Gray Ridge® EGG FARMS", "12 Brown Eggs Size: Large / 12 Oeufs bruns Calibre : Gros", "Pick Ontario Freshness" with Foodland Ontario mark, "Delivering Lifestyle Choices™" | none | Canada A mark (red maple leaf) | https://digital.loblaws.ca/PCX/20822900001_EA/en/1/6476734301_enfr_front_centre_marketing_GS1_Ecommerce_800.png |
| GoldEgg Golden D White Eggs, Large, 18 | "GoldEgg JauneDoré", "Golden D", "White Eggs \| Œufs blancs", "18 LARGE SIZE \| CALIBRE GROS", EQA \| AQO logo (nutrient copy not transcribed) | none | Canada A mark | https://digital.loblaws.ca/PCX/20819807001_EA/en/1/67495900022_enfr_front_centre_marketing_GS1_Ecommerce_800.png |
| Golden Valley "Born 3 White Eggs, Large", 12 | "BORN 3 EGGS", "OMEGA-3", "12 LARGE" (feed/production statements not transcribed). **No "Golden Valley" name visible on the front panel**; the retailer's brand field says Golden Valley | none | red maple-leaf grade mark | https://digital.loblaws.ca/PCX/20819626001_EA/en/1/66693390042_enfr_front_centre_marketing_GS1_Ecommerce_800.png |

Retailer listing names with housing words (P&H brands): Voilà "Gold Egg White Eggs Enriched Coop Large 12 Count" (627148EA); Walmart "GoldEgg Free Run Large 12 Eggs"; Metro "Gold Egg Large Free-Run Brown Eggs", "Gold Egg Large Organic Brown Eggs"; Conestoga "Large Free-Range Eggs", "Large Free-Run Omega-3 Brown Eggs", "Extra Large Organic Brown Eggs" (Metro); Loblaw "Country Golden Yolk Large Free Range Eggs"; Save-On "Golden Valley - Country Golden Yolks Free Range Large Brown Eggs". Gray Ridge plain listings carry no housing word.

**Company's own housing statement (verbatim, undated page).** Gray Ridge "Hen Care" (P11): "That includes working with farmers who transition to alternative hen housing, including enriched colony, free run and free range. Enriched colony is a newer housing type that features larger enclosures, allowing hens to exhibit their natural behaviours with access to quiet nesting boxes, perches and scratching areas." … "All egg farmers in Canada are phasing out conventional (cage) housing by 2036." P&H/Golden Valley on Country Golden Yolks (P8): "From family farms in the Fraser Valley, Country Golden Yolks eggs come from free range hens. Our free-roaming hens have access to outside pasture […]". **No dated P&H-wide housing-transition commitment was found.**

**2023–2026 news (dated).**

| Date | Item | Source (tier) |
|---|---|---|
| (company page) | Gray Ridge "received the 'Canadian Grocer Impact Award 2024' for sustainability" | P10 (a) |
| 10 Oct 2025 (metadata) | L. H. Gray & Son businesses "now P&H Foods Inc." | P1 (a) |
| 16 Jan 2026 | CTV News London video report (Scott Miller): "'450,000 dozen per day': Listowel now home to largest egg grading facility in Canada"; page also carries the heading "$35 million expansion for Gray Ridge Listowel facility" | N3 (b) |
| 22 Jan 2026 | Listowel Banner (Nicole Beswitherick): "Gray Ridge Eggs Inc. in Listowel is now the largest and most advanced egg grading facility in the country. The facility's new Moba Omnia PX530 egg grading machine and 60,000 square foot expansion made this possible." | N4 (b) |
| 2 Mar 2026 (metadata) | P&H: "With this expansion, the Listowel facility is now the largest egg grading station in Canada" (company claim) | P2 (a) |
| 1 Jun 2026 | P&H Foods "has entered into a joint venture with Atlantic Poultry Incorporated (API) to create a new company, P&H Foods Atlantic. … P&H Foods will lead the management of the grading operation, while API contributes its existing infrastructure". "The transaction is expected to be completed this summer, subject to customary closing conditions." API is described as "100% owned and operated by Atlantic Canadian poultry farmers". | P3, P4 (a). Completion: **not confirmed** (UNVERIFIED #13) |

**One-line readings.**
- **Gray Ridge**: Ontario's Gray family brand since 1970, now owned by grain-and-milling company Parrish & Heimbecker; the company says its Listowel plant is Canada's largest grading station.
- **GoldEgg**: P&H's national specialty-egg brand ("Local premium eggs. National brand power.", P10); listed today at Loblaw-banner stores in ON, MB, SK and AB, at Save-On (BC, AB), Walmart Mississauga, Metro's default store and Voilà.
- **Conestoga Farms**: P&H's Ontario free run / free range / organic line; its own website now returns 404.
- **Golden Valley (B.C.)**: owned by P&H Foods; also markets Born 3, Country Golden Yolks, Canadian Harvest and Rabbit River.
- **Sparks (Alberta)**: P&H's Alberta grader since 1976.

---

### 3.3 Rabbit River Farms (B.C.)

- **Company's own description (P14):** "We are committed to the values of socially responsible, sustainable and humane farming practices. Our family farms produce certified organic, free range and free run eggs. All our chicken flocks live in a cage free environment […]. As the pioneer and leader in Canadian organic and cage free chicken egg production we were the very first SPCA (Humane) certified farm in Canada. We authored the original Canadian certified organic egg production standards (COABC) and today maintain our certified organic status through a third party certifier – Pro-Cert Organic Systems" (company claims, attributed).
- **Owner:** listed by P&H Foods among Golden Valley's brands (P8). Rabbit River's site gives "Rabbit River Farms 17740 River Road Richmond, BC" and routes sales enquiries "via Golden Valley Foods" (P14).
- **Front of pack** (Loblaw "Organic Eggs, Medium", 12): "Rabbit River Farms", "Free Range Organic Eggs / Œufs biologiques", "MEDIUM 12 MOYEN", Canada Organic logo, "Certified by PRO-CERT", a "BC" logo, banner "ALL ORGANIC VEGETARIAN FEED"; a slogan on the panel contains health wording and is not transcribed. Housing: **free range** + organic printed. Image: https://digital.loblaws.ca/PCX/20995948001_EA/en/1/20995948001_en_front_800.png
- Retailer listings: Loblaw (BC/MB/SK/AB stores) incl. "Free Run Omega 3 Brown Eggs", "Large Size White Eggs Free Run Dark Yolk"; Save-On 1982/6634 "Rabbit River Farms - Organic Free Range Large Brown Eggs" (Save-On page text: "One Dozen Eggs - Free Range on Certified Organic Land. Canadian Grown").
- **One-line reading:** B.C. organic/free-range brand whose own site claims Canada's first SPCA-certified farm; it now sits in P&H's Golden Valley portfolio.

### 3.4 Island Eggs (Vancouver Island)

- **Owner:** Burnbrae Farms. Country Grocer's supplier page (C2): "Island Eggs is a family-owned and operated business that has been handling eggs on Vancouver Island for more than 60 years. Started by the Jensen family, Island Eggs is responsible for grading and packaging the eggs that are produced only by farmers on the Island and across the province. Island Eggs sells its packaged eggs to local and major grocery store chains on the Island and throughout British Columbia under the Island Gold and Naturegg brand names. In 2007, Island Eggs was purchased by Burnbrae Farms Ltd. , also a family-owned and operated business. The Jensen family continues to be actively involved in Island Eggs, with Cheryl, the third generation Jensen, managing the business as the Director of Operations."
- islandeggs.com returned 403. **No Island Eggs / Island Gold listing was found** on Loblaw (incl. Vancouver stores), Voilà, or Save-On Langley/Calgary today.
- **One-line reading:** Vancouver Island grader owned by Burnbrae since 2007; its "Island Gold" brand was not found on any online shelf scanned today.

### 3.5 Lovo (formerly Nutri Group / Groupe Nutri), incl. Nutri, Maritime Pride, Star Egg JV

**Owner and chain.**
- "Farmer-owned since 1987, Lovo has carried this legacy forward for two generations." "Lovo is the only Canadian company owned by local farmers, and one of the country's largest egg graders, processors and distributors." (L1; company claims)
- Release, Sept. 22, 2026 (L2): "Lovo, formerly Nutri Group, is officially making its way onto grocery store shelves with colourful packaging and a new brand identity. Owned by farming families, Lovo grades, processes, and distributes more than 2.4 billion eggs a year". Boilerplate: "Lovo, formerly Nutri Group, has been owned by Québec farming families since 1987 … through its subsidiary, Supreme Egg Products". CEO: Sébastien Léveillé.
- Release, May 7, 2026 (L3): "Behind Lovo are families of farmers from Québec, Manitoba, Ontario, and New Brunswick".
- La Presse, 28 Mar 2026 (N2, Stéphanie Bérubé): "L'entreprise par actions appartient à 47 producteurs québécois, mais elle s'approvisionne aussi dans d'autres poulaillers, pour un total de 300 fermes fournisseuses."
- **Maritime Pride:** the Loblaw carton image reads "FARMER OWNED MARITIME PRIDE EGGS" beside a "NUTRI" seal and "PRODUCT OF CANADA – PRODUIT DU CANADA" (https://digital.loblaws.ca/PCX/20830377001_EA/en/1/20830377001_en_front_800.png). Nutri's Maritime Pride business-unit URL now redirects to Lovo's "Who We Are" page (L7), so no company page on Maritime Pride was read.
- **Star Egg (Saskatoon):** Saskatchewan Egg Producers (L6): "SaskEgg is also proud to co-own Star Egg Company , in a joint-venture partnership with the Harman family and NutriGroupe ." Nutri release (L4, page dated 2017-10-10): "Nutri Group … welcomes Star Egg Company within its group of farm owners. With a proven track record since 1966 … Star Egg is proud to distribute these eggs in Saskatchewan, Alberta, and northern British Columbia." (Loblaw Regina lists "Star Free Bird Free Range Large Eggs" and "Star Free Run Eggs, Large"; "Harman Eggs 18ct".)

**Where graded/packed.** Saint-Hyacinthe QC (L2, L5). Release, July 9 (2026; page metadata 2026-07-09): "The new grading plant, located on Picard Street in Saint-Hyacinthe, will enable Lovo to increase its processing capacity". Carton station line: not legible.

**Front of pack.** Nutri-Egg "Free Run Hens Large White Eggs" 12 (Atlantic Superstore): "FREE RUN HENS / POULES EN LIBERTÉ", "FARMER OWNED NUTRI FERMIERS PROPRIÉTAIRES", "PRODUCT OF CANADA – PRODUIT DU CANADA", "LARGE WHITE EGGS – GROS ŒUFS BLANCS". Image: https://digital.loblaws.ca/PCX/21023768001_EA/en/1/21023768001_en_front_800.png. Lovo-branded cartons: not imaged today.

**Company's own welfare wording.** "The well-being of our hens and the health of our land are non-negotiable." (L1). **No dated housing-transition commitment found** on Lovo pages opened.

**What the current line shows (Voilà listing names).** "Lovo White Eggs Free Run Large 12", "Lovo White Eggs Dark Yolk Free Run Large 12", "Lovo Organic Brown Eggs …", "Lovo White Eggs Comfort Farm Large 12", plus plain "Lovo White Eggs Large 12"; "Nutri Comfort Farm White Eggs Large 12". "Comfort Farm" is not defined on any page opened (UNVERIFIED #14).

**2023–2026 news (dated).**

| Date | Item | Source (tier) |
|---|---|---|
| 11 Feb 2025 (metadata) | "We are pleased to announce the acquisition of an industrial building near our current facilities." | L5 (a) |
| 28 Mar 2026 | La Presse: "Grand changement au comptoir des œufs : le transformateur Nutri devient Lovo." | N2 (b) |
| 7 May 2026 | "Nutri Group recently announced the launch of Lovo, its new brand identity." | L3 (a) |
| 9 Jul 2026 | Egg Industrial Campus: "spanning more than 600,000 square feet"; "$1.6 million in financial support from Québec's Ministère de l'Agriculture, des Pêcheries et de l'Alimentation (MAPAQ) and is also eligible for a loan of up to $20 million from Investissement Québec." | https://lovo.co/en/press-releases/lovo-kicks-off-its-industrial-egg-campus-in-saint-hyacinthe/ (a) |
| 22 Sep 2026 | New Lovo packaging "gradually appearing on the shelves of major grocery chains across Québec and Manitoba" | L2 (a) |

**One-line reading.** Québec farmer-owned grader (47 Québec producer-shareholders per La Presse) that renamed itself Lovo in 2026; its Maritime Pride cartons say "Farmer owned".

### 3.6 Maple Lodge Farms

- Maple Lodge Farms' home page (O3) presents a chicken business: "We're Chicken Experts"; "In the 1830s, the May family began raising chickens on a farm outside what is now Brampton, Ontario."
- **No Maple Lodge egg product was found on any retailer site scanned today.**
- **One-line reading:** not an egg brand on the 2026 shelf; do not list it as one.

### 3.7 Organic Meadow eggs → Yorkshire Valley Farms

- Organic Meadow FAQ (O1): "Where can I purchase Organic Meadow eggs? Yorkshire Valley Farms now sells our eggs repackaged under their brand name. This agreement will help the egg producers grow the organic egg category together by focusing their collective efforts. The eggs will continue to be produced in the same fashion and by the same farmers." The home page reads "© Copyright 2026 Organic Meadow Limited Partnership" and lists dairy only.
- Voilà searches returned Organic Meadow dairy items only; **no Organic Meadow or Yorkshire Valley egg listing** was found on any retailer site today.
- Yorkshire Valley Farms: its site could not be opened (O2). A 2018 Premium Brands stake is reported only in tier (c)/(b) sources not opened to standard (UNVERIFIED #9).
- **One-line reading:** Organic Meadow no longer sells eggs under its own name, by its own FAQ; the Yorkshire Valley successor brand was not found online today.

### 3.8 Vital Farms and other U.S. brands

- Vital Farms 10-K, FY2025 (V1): "We market our products throughout the United States". The filing's only "Canada" mention is a carton-supplier location. No Canadian sales are described.
- **No Vital Farms or other U.S. shell-egg brand was found on any Canadian retailer site scanned today.** An instacart.ca listing appeared in a web search (tier c, not opened). UNVERIFIED #15.
- **One-line reading:** not on the Canadian grocery shelves we could scan; do not say it is sold here.

### 3.9 Kirkland Signature (Costco)

- **Owner's words (R9):** "Every product that carries the Kirkland Signature name is carefully researched, tested, hand-selected, or custom-created by a dedicated team of experts here at Costco."
- **Shelf:** costco.ca's online catalogue lists **no shell eggs** (9 searches, §0.1). Costco Same-Day at postal L5V2N6 (04:08 UTC): "Kirkland Signature Free Run Large Eggs", 24 ct, $10.20 (page also shows "$0.42 each"). https://sameday.costco.ca/store/costco-canada/products/63993483-ks-gros-oeufs-en-libert-paquet-de-24
- **Front of pack** (Same-Day image https://d2lnr5mha7bycj.cloudfront.net/product-image/file/large_5ca7b02c-4907-41f0-9ff5-c36e3e771573.jpg): "KIRKLAND Signature", "FREE RUN / POULES EN LIBERTÉ", "24 LARGE SIZE EGGS / CALIBRE GROS ŒUFS", Canada A mark. A small line under the size block is not legible. **Packer: not named** (UNVERIFIED #1).
- Two other Costco egg URLs carried over from this project's earlier Costco work ("burnbrae-costco-large-eggs-30-ct", "wcsl-28-ecsl-extra-large-eggs-30-ct") **fell back to a Montréal default store and returned no egg record today**. Their URL slugs are not evidence of a packer or a current product.
- **One-line reading:** Costco's own-label shell egg seen today is a 24-pack of free-run eggs; the packer is not printed legibly.

### 3.10 No Name (Loblaw)

- **Front of pack** (Loblaw "Large Size Eggs 12 Pack", images https://digital.loblaws.ca/PCX/20812144001_EA/en/1/20812144001_en_front_v1_800.png and …_en_angle_800.png): "no name® sans nom®", "12 eggs · œufs", "large size · calibre gros", Canada A mark, "LOBLAWS INC., TORONTO M4T 2S8, CANADA © 2025", "KEEP REFRIGERATED", "BEST BEFORE". **No housing word.** Brown 12 side image (…/20813936001_EA/en/3/20813936001_en_side_800.png): "large size·brown/calibre gros·bruns", Canada A mark, no housing word, no packer line legible.
- Listings: "Large Size Eggs 12 Pack", "Extra Large…", "Medium…", "Large Size Brown Eggs 12 Pack", "Large Size Eggs" 30, "Eggs, Medium" 30, and older "Eggs, Large/Extra Large/Medium/Large Brown" (BC/AB/MB/SK stores).
- **Loblaw's own pledge for No Name** (R2a, PDF dated 23 Jun 2025): "in 2024 we committed to collaborating with various stakeholders to define our long-term strategy for eggs within our no name® portfolio. As part of this commitment, we have accelerated our transition plan, ensuring that all control-brand shelled chicken eggs will come from hens housed in alternatives to the standard 'battery' cage by 2030 including from free-run, free-range or enriched housing." Footnote: "Enriched housing - enriched housing systems, while remaining in a wire mesh enclosure, hens are provided with perches, nest area, scratch area, and more head room compared to a conventional cage."
- **One-line reading:** Loblaw's cheapest egg; the carton states no housing type, and Loblaw's own 2030 plan for its control brands names enriched housing as an allowed alternative.

### 3.11 President's Choice (PC Free Run), PC Organics, PC Blue Menu

- **PC Free Run** (Loblaw "Free Run Brown Eggs Large", image https://digital.loblaws.ca/PCX/20813628001_EA/en/1/20813628001_en_front_800.png): "President's Choice® | le Choix du Président", "FREE-RUN BROWN EGGS / ŒUFS BRUNS PONDUS EN LIBERTÉ", "12 LARGE SIZE · 12 CALIBRE GROS", Canada A mark. Lid text: "These Canada Grade A eggs are exclusively from hens who live in an open-concept barn environment where they are free to roam, feed and nest." Loblaw listing text adds: "✓ Did you know…all PC® eggs are consciously sourced from farms using 100% cage-free spaces." (retailer page, attributed)
- **PC Organics** (image https://digital.loblaws.ca/PCX/20813711001_EA/en/1/20813711001_en_front_v1_800.png): "Organics Biologique", "FREE-RANGE BROWN EGGS / ŒUFS BRUNS PONDUS EN LIBERTÉ", "12 LARGE SIZE / CALIBRE GROS", Canada Organic logo, **"PRODUCT OF CANADA / PRODUIT DU CANADA"**, Canada A mark. Loblaw listing: "A product of Canada, they come from free-range hens".
- **PC Blue Menu** (image https://digital.loblaws.ca/PCX/20992723001_EA/en/1/20992723001_en_front_v2_800.png): "Blue Menu Bleu", "FREE-RUN · PONDUS EN LIBERTÉ", "WHITE EGGS / ŒUFS BLANCS", "12 LARGE SIZE / 12 CALIBRE GROS", Canada A mark; "OMÉGA-3" printed (name only); a small upside-down line on the top flap appears to read "PRODUCT OF CANADA/PRODUIT DU CANADA" (low-resolution, treat as unconfirmed). Nutrient claims on the panel are not transcribed.
- Also listed: "President's Choice Extra Large Free Run Brown Eggs"; "President's Choice Farm-Fresh Quail Eggs" 18.
- **Loblaw's own statements** (R2, live page): "Today, 100% of PC ® shell eggs are now entirely free-run and/or free-range hen housing systems." (R2a): "Our PC® shell eggs are now entirely cage-free".
- **Packer: not named** on any image or page opened (UNVERIFIED #1).
- **One-line reading:** every PC shell-egg carton seen today prints free run or free range, matching Loblaw's own statement.

### 3.12 Compliments (Sobeys / Empire)

- **Owner's words:** Empire/Sobeys FY2025 report (R3): "our Compliments brand is backed by a 100% Guarantee program." Banner list (R3): "Sobeys Inc. oversees familiar banner names of Sobeys, Safeway, IGA, Foodland, FreshCo, Thrifty Foods, Farm Boy, Kim Phat, Longo's, Lawtons Drugs, Ricardo and Voilà".
- **Front of pack (Voilà images opened):**
  - "Compliments White Eggs Large 12" (https://voila.ca/images-v3/2d92d19c-0354-49c0-8a91-5260ed0bf531/c58e2f98-363f-4515-b70b-160e73c03bd8/500x500.jpg): "compliments", "LARGE · GROS", "12", "Egg Quality Assurance" logo, small "PRODUCT OF CANADA" text on the lid. No housing word. A small distributor line is not legible.
  - "Compliments Cozy Coop Eggs Large 12" (…/cd6c9e4d-3279-4bc5-b65b-ce25494b8746/500x500.jpg): "COZY COOP / POULAILLER DOUILLET", "12 LARGE SIZE WHITE EGGS". A small lid statement begins "From hens raised in small groups in furnished housing…" (partly legible; not fully transcribed).
  - "Compliments White Eggs Free Run Large 12" (…/9c8a05db-5c1c-4a7a-8623-829e07660222/500x500.jpg): "FREE RUN / POULES EN LIBERTÉ", "12 LARGE SIZE WHITE EGGS".
- Other listings: "Compliments Organic Brown Eggs Free Range Large/Medium", "Compliments Omega 3 White Eggs Free Run Large", "Compliments Balance Omega 3 Brown Eggs Large", "Compliments Specialty Eggs Large", "Compliments Brown Eggs Large/Medium", white XL/L/M, 18 and 30 packs.
- **Packer: not named** (UNVERIFIED #1).
- **One-line reading:** Sobeys' own label spans plain cartons with no housing word, "Cozy Coop", free run and organic free range.

### 3.13 Great Value (Walmart)

- **Owner's words (R11, U.S. release, 15 Apr 2026):** "Walmart today announced a comprehensive redesign of its flagship private brand, Great Value". (U.S. context; the release gives no Canadian figure.)
- **Shelf (walmart.ca, store 1061, Mississauga, 04:03 UTC):** "Great Value Large 12 Eggs" $3.93; "Great Value XL White 12 Eggs" $4.63; "Great Value Medium White 30 Eggs" $9.18; "Great Value Omega-3 Large White 12 Eggs" $6.22 (was $6.93); "Great Value Organic Free Run Large Brown 12 Eggs" $7.88. URLs: e.g. https://www.walmart.ca/en/ip/Great-Value-Large-12-Eggs/10052944 ; https://www.walmart.ca/en/ip/Great-Value-Organic-Free-Run-Large-Brown-12-Eggs/6000196119460
- **Front of pack, housing, maple leaf, packer:** product pages were blocked (`/blocked`) after 04:05 UTC. **Not read** (UNVERIFIED #6).
- **One-line reading:** Walmart Canada's own-label eggs were listed today, including an "Organic Free Run" pack; the cartons themselves could not be read.

### 3.14 Selection and Life Smart (Metro)

- **Owner's words (R7):** Metro's private-brands page lists "IRRESISTIBLES", "SELECTION" and "LIFE SMART".
- **Shelf (api2.metro.ca, "Metro Devonshire", 04:06 UTC):** Selection "Large Eggs" 12 $3.99, 18 $4.99, 30 $9.99; "Extra Large Eggs" 12 $4.89; "Medium Eggs" 12 $3.89. Life Smart "Large Free-Run Eggs" 12 $7.59 / 18 $10.49; "Large Free-Run Omega-3 Eggs" 12 $7.99; "Large Organic Brown Eggs" 12 $7.79; "Extra Large Organic Free-Run Brown Eggs" 12 $8.29; "Organic Free-Run Medium Brown Eggs" 12 $7.99; liquid whites.
- **Retailer page text (verbatim, nutrient copy cut):** Selection Large Eggs 30 (https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/059749976879): "Product of Canada". Life Smart Large Free-Run Eggs (…/large-free-run-eggs/p/059749992206): page title "Life Smart Naturalia Large Free-Run Eggs"; "Free-run hens are raised in spacious indoor henhouses equipped with nests, perches, and dust-bathing areas, but they do not have access to the outdoors."; "Product of Canada". Life Smart Large Organic Brown Eggs (…/large-organic-brown-eggs/p/059749976817): page title "Free-Range Large Organic Brown Eggs", yet the description repeats the free-run sentence above. **The page carries both "Free-Range" (title) and the free-run housing text (description).** Reported literally; no inference.
- **Front of pack:** not imaged (Metro product images were 403 in this project's earlier sessions; not retried). **Packer: not named** (UNVERIFIED #1).
- **One-line reading:** Metro's Selection eggs carry no housing word in their listings; Life Smart is Metro's free-run/organic line.

### 3.15 Western Family and Only Goodness (Pattison Food Group / Save-On-Foods)

- **Owner's words (R8):** Pattison Food Group's site lists "Corporate Brands Western Family" and "Retail Banners Save-On-Foods", and says: "Pattison Food Group is a Jim Pattison business and Canada's largest Western-based provider of food and […] products. Headquartered in British Columbia, Canada, we have been in business since 1915."
- **Shelf and retailer text (Save-On API, store 1982 Langley BC and 6634 Calgary AB, item records modified 9 Aug–29 Sep 2026):**
  - "Western Family - Large White Eggs" (12): "Product of Canada. Canada A." (health sentence cut). $4.35.
  - "Western Family - Free Run Eggs" (12): "12 Large Eggs Exclusively from Hens who are Free to Roam Indoors and Express Some Natural Behaviours." $7.35.
  - "Western Family - Free Range Brown Eggs, Large" (12): "12 Large Size Brown Eggs Exclusively From the Hens that are Free to Express Natural Behaviours while Roaming Indoors and Outdoors". $7.85.
  - "Western Family - Large Brown Eggs": "Product of Canada. Canada A." $5.79.
  - Also "Omega 3 Large Eggs", "Extra Large White", "Medium White", "Large White Eggs 18", "Large White Eggs Cello" (30), "Liquid Egg Whites", "Quail Eggs, 18 Pack".
  - "ONLY GOODNESS - Organic Large Brown Eggs" (12): "12 large free range eggs. […] Organic eggs are produced in free range operations and the hens are fed certified organic feed." $8.85.
  - Save-On attaches "made in canada" and "product of canada" filter tags to these items (retailer tags, not label text).
- **Front of pack:** the Save-On API returned no image for these items. Not read. **Packer: not named** (UNVERIFIED #1).
- **One-line reading:** Pattison's own label in Western Canada, with plain, free-run and free-range cartons; Save-On's pages say "Product of Canada".

### 3.16 Giant Value / Giant Tiger

- Giant Tiger has a "Giant Value" brand page (R10). **No "Giant Value" egg was found** in the eggs collection (83 items) or in "giant value eggs" search (only chocolate eggs and egg rolls).
- The vendor field "Giant Tiger" appears on "Best Value Eggs, Large, 12-pack" ($4.89, tags AB/MB/SK, `in_store_only:true`, https://www.gianttiger.com/products/12s-best-value-eggs-large) and two Burnbrae/Naturegg listings.
- Giant Tiger's egg shelf online is dominated by Burnbrae Farms listings (53 of 83 by vendor field), plus Maritime Pride, Nova Eggs, Nutri, Delong Farms, Farmer John, Poultry Farm Laviolette, Gray Ridge.
- **One-line reading:** there is no Giant Value egg online; Giant Tiger's own-vendor egg is "Best Value", Prairies only.

### 3.17 Farm Boy (Sobeys / Empire)

- Product page (https://www.farmboy.ca/products/farm-boy-large-white-eggs-dozen/): "Farm Boy™ Large White Eggs (dozen)"; breadcrumb "Private Label Products > Dairy and Eggs > Eggs > Chicken"; "our large, Grade-A eggs from Ontario hens are a smart choice at any meal" (the rest of the sentence is nutrient copy, cut). Ingredients: "Eggs. Oeufs." No price online. No housing word.
- Ownership: "Empire Company Limited … announced today that it has completed its purchase of Farm Boy" (R12, page dated 10 Dec 2018).
- **One-line reading:** Farm Boy's own-label dozen says its eggs come "from Ontario hens"; it names no housing type.

### 3.18 Longo's (51% Empire)

- Voilà listings: "Longo's White Eggs Enriched Coop Large 12" ($5.49), "Longo's Brown Eggs Enriched Coop Large 12", "Longo's White Eggs Enriched Coop Extra Large 18", "Longo's Brown Eggs Free Run Large 12", "Longo's Omega-3 White Eggs Large 12".
- Ownership: "Empire … has completed the purchase of 51% of Longo's" (R13, May 10, 2021).
- **One-line reading:** Longo's own label names "Enriched Coop" on three of five listings.

### 3.19 Other brands found (short entries; owner not researched to standard)

| Brand | Where found | Housing words in listing names | Note |
|---|---|---|---|
| Farmer's Finest | Loblaw Calgary; Save-On Calgary; Voilà | "Comfort Coop", "Free Range", "Free Run", "Organic" | Carton (Loblaw image https://digital.loblaws.ca/PCX/20882339001_EA/en/1/20882339001_en_front_v1_800.png): "Comfort Coop / Poulailler aménagé", "Our Hens Live in Spacious Environments". Its site (P17): "Comfort Coop eggs come from hens that are housed in small group settings with amenities such as perches and a curtained off area where hens lay their eggs." Owner: UNVERIFIED #10 |
| Rowe Farms / Green Valley | Loblaw (ON, NS); Voilà | "Free Run", "Free Range"; Loblaw description of "Green Valley Omega 3 Eggs, Large": "Greenvalley Omega 3 eggs come from hens raised in small social groups that are free to nest and perch in an enriched colony house." | owner not researched |
| Vita | Voilà | "Free Run", "Organic" | the old nutrigroupe.ca "Vita Eggs" product URL now redirects to https://lovo.co/en/product/organic-large-brown-eggs-12x/ (a fact about the redirect, not an ownership statement) |
| Sunshine Valley | Voilà | "Free Range", "Organic" | owner not researched |
| Maple Hill (Farms) | Save-On Langley; Voilà | "Free Range", "Organic Free Range" | owner not researched |
| Coligny Creek | Loblaw Vancouver | "Free Range", "Organic Free Range" | owner not researched |
| Alderwood Farms | Loblaw Markham / Mississauga | "Pasture-Raised" | "pasture-raised" is not a CFIA-defined term in the sources opened (see eggs_rules_labels.md) |
| Foremost | Loblaw BC/AB/SK/MB | none | Loblaw: "A product of Canada" |
| Avalon | Save-On; Voilà | "Organic", "Free Range" | owner not researched |
| Star; Harman | Loblaw Regina | "Free Bird Free Range"; "Free Run" | Star Egg JV, §3.5 |
| Britestone; Rochfort Bridge; Countryside; Daybreak Farms; Gerber's Farm; Vanderwees; Eyking Farm; Gamble Farm; Delong Farms; Keenan Farms; Newfoundland Eggs; Nature's Farm; Coldspring Farm; Farmer John; Nova Eggs; Poultry Farm Laviolette; Hartmann; Canadian Harvest; Country Golden Yolks | Voilà / Giant Tiger / Loblaw | various (see §1) | Canadian Harvest and Country Golden Yolks are Golden Valley brands per P8 |


---

## 4. Retailers' own cage-free / housing pledges (verbatim, dated)

### 4.0 The 2016 joint commitment

- **Retail Council of Canada release, March 18, 2016 (R1):** "Today, the Retail Council of Canada (RCC) grocery members, including : Loblaw Companies Limited, Metro Inc., Sobeys Inc., and Wal-Mart Canada Corp. , announced a step towards improving animal welfare by voluntarily committing to the objective of purchasing cage-free eggs by the end of 2025." Also: "this voluntary commitment is made recognizing the restrictions created by Canada's supply management system and importantly this objective will have to be managed in the context of availability of supply within the domestic market." (quote attributed in the release to David Wilkes, RCC)
- **CBC News, Susan Noakes, Mar 18, 2016 (N1, tier b):** "The Retail Council includes Loblaw Co. Ltd., Metro Inc. Sobeys Inc. and Wal-Mart Canada Corp., which together represent 90 per cent of grocery retail in Canada."
- Costco is **not** named in the RCC release.

### 4.1 Loblaw

| Date | Loblaw's own words | Source |
|---|---|---|
| 2016 (as restated by Loblaw) | "In 2016, we announced that we would source all shell eggs from cage-free systems by 2025." | R2a (PDF created 23 Jun 2025) |
| 2021 (as restated) | "In 2021, however, it became evident that our farmer partners would not be able to meet the 2025 timeline. At that time, we communicated publicly that the initial timeline would not be met and reaffirmed our commitment to NFACC and their efforts to generate good standards." | R2a |
| 2024 (as restated) | "Additionally, in 2024 we committed to collaborating with various stakeholders to define our long-term strategy for eggs within our no name® portfolio. As part of this commitment, we have accelerated our transition plan, ensuring that all control-brand shelled chicken eggs will come from hens housed in alternatives to the standard 'battery' cage by 2030 including from free-run, free-range or enriched housing." | R2a |
| current page | "We are committed to transitioning to 100% cage free eggs as soon as practically possible." | R2a |
| current page | "As part of this commitment, we have accelerated our transition plan, ensuring that all control brand shelled chicken eggs will come from hens housed in alternatives to the standard 'battery' cage by 2030, including from free-run² or free-range³. Today, 100% of PC ® shell eggs are now entirely free-run and/or free-range hen housing systems. In 2025, free-run and free-range eggs represented approximately 18% of total category sales." (Footnote ³ also reads "Subject to available supply.") | R2 (live page, opened 04:15 UTC) |

OUR NOTE (literal comparison, no characterisation): the live web page lists "free-run or free-range" as the 2030 alternatives; the June 2025 PDF lists "free-run, free-range or enriched housing". The 2025 ESG Disclosure Report PDF (R2b) contains no egg wording. On the shelf today: PC cartons print free run / free range (§3.11); No Name cartons print no housing word (§3.10).

### 4.2 Sobeys / Empire

| Date | Company's own words | Source |
|---|---|---|
| 2016 | Joint RCC commitment (§4.0) | R1 |
| Fiscal 2024 report | Headline only: "Poultry & Eggs … Working to increase the availability of cage-free eggs … Collaborating with suppliers, industry associations and NGOs" | R3a |
| Fiscal 2025 report (July 2025) | "We remain committed to continuing to work with suppliers and industry partners, such as the NFACC, to increase the availability of cage-free (including free-run, free-range and organic) and enriched-housing eggs, setting internal purchasing milestones and educating customers on the options available in stores. In fiscal 2025, 20% of total shell eggs sales were cage-free, with the remainder coming from enriched housing systems or conventional cages. Currently, many egg suppliers use both enriched housing systems and conventional cages, and it is difficult to get accurate data as to the proportions from each type of housing within the supply provided. As the transition from conventional cages to enriched housing systems continues, we will work with suppliers to get accurate data to help demonstrate our progress towards our commitment." | R3 (archived copy of company PDF) |

A Sobeys statement that it "would not meet" the 2025 date in 2021 appears only in search snippets (tier c); its own 2021 page was not opened (UNVERIFIED #16).

### 4.3 Metro

| Date | Metro's own words | Source |
|---|---|---|
| 2016 | "Eggs In 2016: Voluntary commitment to the objective of purchasing cage-free eggs by the end of 2025." | R4 |
| 2021 (block dated "June 2021") | "In 2021: Through ongoing discussions with our suppliers, it became apparent that this commitment would not be achievable by the industry within the planned time frame of 2025. Canada's egg producers plan to completely eliminate the use of conventional cages, which restrict some of the hens' natural behaviours by 2036. METRO will continue to work with its suppliers to increase its supply of eggs from hens raised in cage-free system and enriched housing. Today, over 50% of the eggs under METRO's Life Smart brand are cage-free and organic, including 100% of Life Smart brown eggs. METRO will continue to research about the best alternative to conventional cages for the welfare of laying hens to guide our purchasing practices. We will report our progress annually in our corporate responsibility report." | R4 (opened 04:14 UTC) |
| same page | "Despite adjustments to the commitments made with the industry on pork and eggs, METRO remains firmly committed to achieving its animal welfare goals as part of its responsible procurement approach." | R4 |

No later dated Metro egg figure was opened today (UNVERIFIED #17).

### 4.4 Walmart Canada

- 2016: joint RCC commitment (§4.0, R1).
- Walmart Inc. ESG page (R5) gives **U.S. figures only** (labelled, not Canadian): "As of FYE2026, 30.4% of Walmart U.S. shell egg sales were cage-free." and "Although Walmart's 2025 aspiration to achieve 100% cage-free shell eggs was not achieved, Walmart continues to work with suppliers to address production costs, customer demand, and supply disruption while expanding access to cage-free options and reporting annual progress." The page states its animal-welfare asks for "Walmart U.S. and Sam's Club U.S." suppliers.
- **No Walmart Canada page with a Canadian egg figure or a dated update was found today.** A "9%" Walmart Canada figure circulates only via an advocacy scorecard and search snippets (UNVERIFIED #18).

### 4.5 Costco Canada

- Costco "Animal Welfare" page (R6, global): "Cage-Free Commitment — We work to procure cage-free eggs in all 14 regions where we operate and will continue to transition to cage-free eggs with added availability and capacity of cage-free production." No Canada-specific figure on the page.
- Costco is not a signatory of the 2016 RCC release (R1).
- On the online shelf today, the only Kirkland Signature egg seen is "Free Run" (§3.9).
- A "22.6%" Costco Canada figure appears only in an advocacy scorecard via search snippets (UNVERIFIED #18).

### 4.6 Producer-side reference points (for context; full detail in eggs_rules_labels.md)

- Burnbrae: "Along with all Canadian egg farmers, Burnbrae is committed to moving hens out of conventional cage housing before 2036" (C1c).
- Gray Ridge: "All egg farmers in Canada are phasing out conventional (cage) housing by 2036." (P11)
- Metro: "Canada's egg producers plan to completely eliminate the use of conventional cages … by 2036" (R4).

---

## 5. Price snapshot from retailers' own sites (3 Oct 2026)

Price per egg = shelf price ÷ count, computed by us. "REGULAR" / "SPECIAL" are Loblaw's own price types. Full Loblaw rows (131): `eb/prices_lb.md`. Voilà prices are from an unset region (§0.1).

| Retailer, store / region | Brand – exact listing | Count | Price | Type | Per egg | Time (UTC) | URL |
|---|---|---|---|---|---|---|---|
| Maxi Ste-Catherine, Montréal QC | No Name – Large Size Eggs 12 Pack | 12 | $2.99 | REGULAR | $0.249 | 03:58 | https://www.maxi.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Bo's No Frills, Toronto ON | No Name – Large Size Eggs 12 Pack | 12 | $3.93 | REGULAR | $0.328 | 03:57 | https://www.nofrills.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Atlantic Superstore Young St, Halifax NS | No Name – Large Size Eggs 12 Pack | 12 | $4.98 | REGULAR | $0.415 | 04:01 | https://www.atlanticsuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Bo's No Frills, Toronto ON | No Name – Large Size Eggs | 30 | $10.04 | REGULAR | $0.335 | 03:57 | https://www.nofrills.ca/large-size-eggs/p/21435777001_EA |
| Loblaws Bullock Dr, Markham ON | President's Choice – Free Run Brown Eggs Large | 12 | $7.15 | REGULAR | $0.596 | 03:59 | https://www.loblaws.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Loblaws Bullock Dr, Markham ON | PC Organics – Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 03:59 | https://www.loblaws.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Loblaws Bullock Dr, Markham ON | PC Blue Menu – Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.49 | REGULAR | $0.624 | 03:59 | https://www.loblaws.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Bo's No Frills, Toronto ON | Burnbrae Farms – Naturegg Omega 3 White Eggs, Large | 12 | $6.45 | REGULAR | $0.537 | 03:57 | https://www.nofrills.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Loblaws Bullock Dr, Markham ON | Burnbrae Farms – Grade A Large Eggs | 18 | $6.98 | REGULAR | $0.388 | 03:59 | https://www.loblaws.ca/grade-a-large-eggs/p/20814294001_EA |
| RCSS Argentia Rd, Mississauga ON | Gray Ridge – Grade A Brown Eggs, Large | 12 | $6.19 | REGULAR | $0.516 | 03:58 | https://www.realcanadiansuperstore.ca/grade-a-brown-eggs-large/p/20822900001_EA |
| Dean's No Frills, Vancouver BC | Golden Valley – Born 3 White Eggs, Large | 12 | $6.15 | REGULAR | $0.513 | 03:58 | https://www.nofrills.ca/born-3-white-eggs-large/p/20819626001_EA |
| RCSS Marine Dr, Vancouver BC | Rabbit River – Organic Eggs, Medium | 12 | $8.19 | REGULAR | $0.683 | 04:00 | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| Atlantic Superstore Young St, Halifax NS | Maritime – White Eggs, Large (Maritime Pride carton) | 18 | $8.17 | REGULAR | $0.454 | 04:01 | https://www.atlanticsuperstore.ca/white-eggs-large/p/20830377001_EA |
| Atlantic Superstore Young St, Halifax NS | Nutri-Egg – Free Run Hens Large White Eggs | 12 | $6.37 | REGULAR | $0.531 | 04:01 | https://www.atlanticsuperstore.ca/free-run-hens-large-white-eggs/p/21023768001_EA |
| RCSS Heritage Meadows Way, Calgary AB | Farmers Finest – Comfort Coop, Large Eggs | 12 | $5.57 | REGULAR | $0.464 | 04:00 | https://www.realcanadiansuperstore.ca/comfort-coop-large-eggs/p/20882339001_EA |
| Voilà (region unset) | Compliments – White Eggs Large 12 Count | 12 | $4.19 | shown | $0.349 | 03:58 | https://voila.ca/products/437783EA/details |
| Voilà (region unset) | Compliments – Cozy Coop Eggs Large 12 Count | 12 | $5.49 | shown | $0.458 | 03:58 | https://voila.ca/products/840388EA/details |
| Voilà (region unset) | Compliments – White Eggs Free Run Large 12 Count | 12 | $6.99 | shown | $0.583 | 03:58 | https://voila.ca/products/848792EA/details |
| Voilà (region unset) | Compliments Organic – Brown Eggs Free Range Large 12 Count | 12 | $9.29 | shown | $0.774 | 03:58 | https://voila.ca/products/552035EA/details |
| Voilà (region unset) | Lovo – White Eggs Large 12 Count | 12 | $4.19 | shown | $0.349 | 03:58 | https://voila.ca/products/1444809EA/details |
| Voilà (region unset) | Longo's – White Eggs Enriched Coop Large 12 Count | 12 | $5.49 | shown | $0.458 | 03:58 | https://voila.ca/products/13845EA/details |
| Save-On-Foods 1982, Langley Twp BC | Western Family – Large White Eggs | 12 | $4.35 | shown | $0.363 | 04:02–04:03 | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639410124 |
| Save-On-Foods 1982, Langley Twp BC | Western Family – Free Run Eggs | 12 | $7.35 | shown | $0.613 | 04:02–04:03 | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639332921 |
| Save-On-Foods 1982, Langley Twp BC | Western Family – Free Range Brown Eggs, Large | 12 | $7.85 | shown | $0.654 | 04:02–04:03 | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639332938 |
| Save-On-Foods 1982, Langley Twp BC | ONLY GOODNESS – Organic Large Brown Eggs | 12 | $8.85 | shown | $0.738 | 04:02–04:03 | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00062639368401 |
| Save-On-Foods 1982, Langley Twp BC | Golden Valley – Country Golden Yolks Free Range Large Brown Eggs | 12 | $8.45 | shown | $0.704 | 04:02–04:03 | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00774290091559 |
| Save-On-Foods 1982, Langley Twp BC | Rabbit River Farms – Organic Free Range Large Brown Eggs | 12 | $9.35 | shown | $0.779 | 04:02–04:03 | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00620580000025 |
| Metro Devonshire (default store) | Selection – Large Eggs | 12 | $3.99 | shown | $0.333 | 04:06 | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/059749896054 |
| Metro Devonshire (default store) | Selection – Large Eggs | 30 | $9.99 | shown | $0.333 | 04:06 | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/059749976879 |
| Metro Devonshire (default store) | Life Smart – Large Free-Run Eggs | 12 | $7.59 | shown | $0.633 | 04:06 | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-eggs/p/059749992206 |
| Walmart.ca store 1061, Mississauga ON | Great Value Large 12 Eggs | 12 | $3.93 | shown | $0.328 | 04:03 | https://www.walmart.ca/en/ip/Great-Value-Large-12-Eggs/10052944 |
| Walmart.ca store 1061, Mississauga ON | Great Value Organic Free Run Large Brown 12 Eggs | 12 | $7.88 | shown | $0.657 | 04:03 | https://www.walmart.ca/en/ip/Great-Value-Organic-Free-Run-Large-Brown-12-Eggs/6000196119460 |
| Walmart.ca store 1061, Mississauga ON | GoldEgg Free Run Large 12 Eggs | 12 | $7.08 | shown | $0.590 | 04:03 | https://www.walmart.ca/en/ip/GoldEgg-Free-Run-Large-12-Eggs/6000196823370 |
| Giant Tiger online (ON-tagged, in_store_only) | Burnbrae Farms Large Eggs, 12-Pack | 12 | $3.93 | shown | $0.328 | 04:07 | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack-8 |
| Giant Tiger online (AB/MB/SK-tagged) | Best Value Eggs, Large, 12-pack | 12 | $4.89 | shown | $0.408 | 04:07 | https://www.gianttiger.com/products/12s-best-value-eggs-large |
| Costco Same-Day, postal L5V2N6 (Instacart location) | Kirkland Signature Free Run Large Eggs | 24 | $10.20 | shown | $0.425 | 04:08 | https://sameday.costco.ca/store/costco-canada/products/63993483-ks-gros-oeufs-en-libert-paquet-de-24 |

Costco Same-Day help page (from this project's Costco file, opened 1 Oct 2026, not re-opened today): "Item prices are marked up higher than your local warehouse." Treat the Same-Day price as an online price, not a warehouse price.

---

## 6. Housing words found on own-label egg listings (OUR NOTE: literal tally from listing names / images opened today)

| Retailer brand | Housing words seen on listings or cartons | Listings with no housing word |
|---|---|---|
| No Name (Loblaw) | none | all 10 |
| President's Choice / PC Organics / PC Blue Menu | "Free Run" / "Free-Range" / "Free-Run" | none (quail eggs excepted) |
| Compliments (Sobeys) | "Cozy Coop", "Free Run", "Free Range" (organic) | white/brown L, M, XL, 18, 30; "Specialty" |
| Longo's | "Enriched Coop" (3), "Free Run" (1) | Omega-3 White |
| Farm Boy | none | 1 |
| Selection (Metro) | none | all 5 |
| Life Smart (Metro) | "Free-Run", "Organic" (title of one page says "Free-Range") | none among shell-egg listings (liquid whites excepted) |
| Great Value (Walmart) | "Organic Free Run" (1) | 4 |
| Western Family (Save-On) | "Free Run", "Free Range" | white/brown L, XL, M, 18, 30, Omega 3 |
| Only Goodness (Save-On) | "Organic", page text "free range" | — |
| Kirkland Signature (Costco Same-Day) | "Free Run" | — |
| Best Value (Giant Tiger) | none | 1 |

---

## 7. One-line readings (all brands with a dossier)

| Brand | Reading |
|---|---|
| Burnbrae Farms / Naturegg / Egg Creations / EGGS2go! | Hudson family since 1891, sixth generation; says it will keep enriched-colony eggs alongside free run/free range/organic and leave conventional cages before 2036. |
| Island Eggs | Vancouver Island grader owned by Burnbrae since 2007; not seen online today. |
| Gray Ridge | Gray family brand (1970), now P&H Foods (Parrish & Heimbecker); Listowel plant claimed as Canada's largest grading station. |
| GoldEgg | P&H's national specialty brand; listings include free run, organic and "Enriched Coop". |
| Conestoga Farms | P&H Ontario specialty line (free run / free range / organic); own website 404. |
| Golden Valley | B.C. grader owned by P&H Foods; also Born 3, Country Golden Yolks, Canadian Harvest, Rabbit River. |
| Sparks | P&H's Alberta grader since 1976. |
| Rabbit River Farms | B.C. organic/free-range brand in P&H's Golden Valley portfolio; claims Canada's first SPCA-certified farm. |
| Lovo / Nutri / Maritime Pride | Québec farmer-owned grader renamed Lovo in 2026; Maritime Pride cartons say "Farmer owned". |
| Star | Saskatchewan grader co-owned by SaskEgg, the Harman family and Nutri. |
| Maple Lodge | Chicken company; no eggs on the shelf. |
| Organic Meadow | Eggs now sold under Yorkshire Valley Farms' name (its own FAQ); neither found online today. |
| Vital Farms | U.S.-only by its own 10-K; not on Canadian retail sites scanned. |
| Kirkland Signature | Costco's 24-pack is free run; packer not legible. |
| No Name | No housing word on the carton; Loblaw's 2030 plan allows enriched for control brands (June 2025 PDF). |
| President's Choice (PC Free Run, PC Organics, PC Blue Menu) | All PC shell-egg cartons seen are free run or free range, as Loblaw states. |
| Compliments | Sobeys' label spans plain, "Cozy Coop", free run and organic free range. |
| Great Value | Listed at Walmart Mississauga incl. "Organic Free Run"; cartons unread (blocked). |
| Selection / Life Smart | Metro's plain line vs its free-run/organic line; one Life Smart page mixes "Free-Range" and free-run text. |
| Western Family / Only Goodness | Pattison's Western label; Save-On text says "Product of Canada". |
| Giant Value | No Giant Value egg online; Giant Tiger's own egg is "Best Value" (Prairies). |
| Farm Boy | Own-label dozen "from Ontario hens", no housing word. |
| Longo's | Own label prints "Enriched Coop" on most listings. |
| Farmer's Finest | Alberta brand with a "Comfort Coop" line; owner not confirmed. |

---

## 8. Front-of-pack maple leaf / "Canadian" wording seen today (literal)

| Carton | Wording / mark |
|---|---|
| Every carton imaged (No Name, PC, PC Organics, Blue Menu, Burnbrae/Naturegg, Gray Ridge, GoldEgg, Born 3, Rabbit River, Maritime Pride, Nutri-Egg, Kirkland, Compliments) | Canada Grade A mark (the grade mark itself contains a maple leaf). This is the grade mark, not a separate origin claim. |
| PC Organics; Maritime Pride; Nutri-Egg Free Run; Compliments White Large | "PRODUCT OF CANADA / PRODUIT DU CANADA" printed |
| PC Organics; Burnbrae Organic; Rabbit River | Canada Organic logo (contains a maple leaf) |
| Gray Ridge | Foodland Ontario mark ("Pick Ontario Freshness") |
| Rabbit River | "BC" logo with "LOCAL FOOD" |
| Retailer text (not label): Save-On Western Family | "Product of Canada" in the description |
| Retailer text: Metro Selection 30, Life Smart | "Product of Canada" |
| Retailer text: Farm Boy | "from Ontario hens" |

---

## 9. Appendix: recalls (DO NOT USE ON AIR)

No recall records were searched or used for this file. Nothing to list.

---

## 10. Appendix: other egg-aisle items (no dossier)

| Item | Retailer | Listing | URL |
|---|---|---|---|
| Bry-Conn Eggs | Loblaw | Quail Eggs (24 ea) | https://www.realcanadiansuperstore.ca/quail-eggs/p/20819628001_EA |
| CRAVE | Voila | Crave Scramble Kit Veggie 64 g | https://voila.ca/products/961441EA/details |
| Elman's | Loblaw | Eggs Pickled (225 g) | https://www.loblaws.ca/eggs-pickled/p/21561586_EA |
| Hatchimals | SaveOn-6634 | Hatchimals - Jumbo Candy Egg | https://storefrontgateway.saveonfoods.com/api/stores/6634/products/00038252650032 |
| Just | Voila | Just Egg Plant Based Egg Scramble 340 g | https://voila.ca/products/888002EA/details |
| Just Egg | Voila | Just Egg Plant Based Egg 500 g | https://voila.ca/products/336140EA/details |
| Just Egg | SaveOn-6634 | Just Egg - Plant Based Liquid | https://storefrontgateway.saveonfoods.com/api/stores/6634/products/00191011001299 |
| Just Egg | SaveOn-1982 | Just Egg - Plant Based Liquid | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00191011001299 |
| Just Egg | Metro | Plant Based Egg (500 g) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/liquid-eggs-egg-whites/plant-based-egg/p/191011001299 |
| Kosa | Loblaw | Quail Eggs In Water (425 g) | https://www.loblaws.ca/quail-eggs-in-water/p/21453362_EA |
| Kosa | Voila | Kosa Canned Quail Eggs In Water 425 g | https://voila.ca/products/569715EA/details |
| Kosa | SaveOn-6634 | Kosa - Quail Eggs in Water | https://storefrontgateway.saveonfoods.com/api/stores/6634/products/00894467000150 |
| Kosa | SaveOn-1982 | Kosa - Quail Eggs in Water | https://storefrontgateway.saveonfoods.com/api/stores/1982/products/00894467000150 |
| Kosa | Walmart | Kosa Can Quail Eggs in Water | https://www.walmart.ca/en/ip/Kosa-Can-Quail-Eggs-in-Water/6000200897638 |
| Len Xiang | Walmart | Len Xiang Cooked Salted Duck Eggs | https://www.walmart.ca/en/ip/Len-Xiang-Cooked-Salted-Duck-Eggs/6000197110645 |
| Six Fortune | Voila | Six Fortune Preserved Duck Egg Hard 6 Count | https://voila.ca/products/262841EA/details |
| Smith Snack | Voila | Smith Snack Warren's Pickled Eggs 1 EA | https://voila.ca/products/602275EA/details |
| Spring Creek Quail Farms | Voila | Spring Creek Quail Farms Farms Fresh Quail Eggs Value Size 18 Count | https://voila.ca/products/838249EA/details |
| Strubs | Loblaw | Kosher Pickled Eggs (500 ml) | https://www.atlanticsuperstore.ca/kosher-pickled-eggs/p/20175831_EA |
| YB | Voila | Y&B Cooked Quail Egg 425 g | https://voila.ca/products/10932EA/details |

## 11. Appendix: Loblaw-banner price rows for selected egg products (PC Express API, 3 Oct 2026)

Per egg computed by us. Store names and regions are as returned by the API's store records.

| Banner / store (region) | Brand | Exact listing name | Pack | Price | Price type | Per egg | Captured (UTC) | URL |
|---|---|---|---|---|---|---|---|---|
| Loblaws Bullock Drive (Markham, Ontario) | No Name | Large Size Eggs 12 Pack | 12 | $3.93 | REGULAR | $0.328 | 03:59 3 Oct | https://www.loblaws.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | No Name | Large Size Eggs 12 Pack | 12 | $4.21 | REGULAR | $0.351 | 04:01 3 Oct | https://www.loblaws.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Maxi Montreal Ste-Catherine (Montreal, Quebec) | No Name | Large Size Eggs 12 Pack | 12 | $2.99 | REGULAR | $0.249 | 03:58 3 Oct | https://www.maxi.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Kevin's NOFRILLS Calgary (Calgary, Alberta) | No Name | Large Size Eggs 12 Pack | 12 | $4.18 | REGULAR | $0.348 | 03:58 3 Oct | https://www.nofrills.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | No Name | Large Size Eggs 12 Pack | 12 | $4.21 | REGULAR | $0.351 | 03:58 3 Oct | https://www.nofrills.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | No Name | Large Size Eggs 12 Pack | 12 | $3.93 | REGULAR | $0.328 | 03:57 3 Oct | https://www.nofrills.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Provigo avenue des Canadiens de Montréal (Montréal, Quebec) | No Name | Large Size Eggs 12 Pack | 12 | $3.00 | SPECIAL to 2026-10-07, was $4.29 | $0.250 | 04:00 3 Oct | https://www.provigo.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Atlantic Superstore - Young Street (Halifax, Nova Scotia) | No Name | Large Size Eggs 12 Pack | 12 | $4.98 | REGULAR | $0.415 | 04:01 3 Oct | https://www.atlanticsuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | No Name | Large Size Eggs 12 Pack | 12 | $3.93 | REGULAR | $0.328 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | No Name | Large Size Eggs 12 Pack | 12 | $4.16 | REGULAR | $0.347 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | No Name | Large Size Eggs 12 Pack | 12 | $4.21 | REGULAR | $0.351 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | No Name | Large Size Eggs 12 Pack | 12 | $4.20 | REGULAR | $0.350 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | No Name | Large Size Eggs 12 Pack | 12 | $4.18 | REGULAR | $0.348 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | No Name | Large Size Eggs | 30 | $10.22 | REGULAR | $0.341 | 04:01 3 Oct | https://www.loblaws.ca/large-size-eggs/p/21435777001_EA |
| Maxi Montreal Ste-Catherine (Montreal, Quebec) | No Name | Large Size Eggs | 30 | $10.19 | REGULAR | $0.340 | 03:58 3 Oct | https://www.maxi.ca/large-size-eggs/p/21435777001_EA |
| Kevin's NOFRILLS Calgary (Calgary, Alberta) | No Name | Large Size Eggs | 30 | $10.28 | REGULAR | $0.343 | 03:58 3 Oct | https://www.nofrills.ca/large-size-eggs/p/21435777001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | No Name | Large Size Eggs | 30 | $10.22 | REGULAR | $0.341 | 03:58 3 Oct | https://www.nofrills.ca/large-size-eggs/p/21435777001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | No Name | Large Size Eggs | 30 | $10.04 | REGULAR | $0.335 | 03:57 3 Oct | https://www.nofrills.ca/large-size-eggs/p/21435777001_EA |
| Provigo avenue des Canadiens de Montréal (Montréal, Quebec) | No Name | Large Size Eggs | 30 | $10.33 | REGULAR | $0.344 | 04:00 3 Oct | https://www.provigo.ca/large-size-eggs/p/21435777001_EA |
| Atlantic Superstore - Young Street (Halifax, Nova Scotia) | No Name | Large Size Eggs | 30 | $10.78 | REGULAR | $0.359 | 04:01 3 Oct | https://www.atlanticsuperstore.ca/large-size-eggs/p/21435777001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | No Name | Large Size Eggs | 30 | $10.25 | REGULAR | $0.342 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs/p/21435777001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | No Name | Large Size Eggs | 30 | $10.22 | REGULAR | $0.341 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs/p/21435777001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | No Name | Large Size Eggs | 30 | $10.28 | REGULAR | $0.343 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs/p/21435777001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | No Name | Large Size Eggs | 30 | $10.28 | REGULAR | $0.343 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs/p/21435777001_EA |
| Kevin's NOFRILLS Calgary (Calgary, Alberta) | No Name | Eggs, Large | 12 | $4.18 | REGULAR | $0.348 | 03:58 3 Oct | https://www.nofrills.ca/eggs-large/p/20044005_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | No Name | Eggs, Large | 12 | $4.16 | REGULAR | $0.347 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/eggs-large/p/20044005_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | No Name | Eggs, Large | 12 | $4.21 | REGULAR | $0.351 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/eggs-large/p/20044005_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | No Name | Eggs, Large | 12 | $4.18 | REGULAR | $0.348 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/eggs-large/p/20044005_EA |
| Loblaws Bullock Drive (Markham, Ontario) | President's Choice | Free Run Brown Eggs Large | 12 | $7.15 | REGULAR | $0.596 | 03:59 3 Oct | https://www.loblaws.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | President's Choice | Free Run Brown Eggs Large | 12 | $6.99 | REGULAR | $0.583 | 04:01 3 Oct | https://www.loblaws.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Maxi Montreal Ste-Catherine (Montreal, Quebec) | President's Choice | Free Run Brown Eggs Large | 12 | $7.17 | REGULAR | $0.598 | 03:58 3 Oct | https://www.maxi.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Kevin's NOFRILLS Calgary (Calgary, Alberta) | President's Choice | Free Run Brown Eggs Large | 12 | $7.07 | REGULAR | $0.589 | 03:58 3 Oct | https://www.nofrills.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | President's Choice | Free Run Brown Eggs Large | 12 | $6.99 | REGULAR | $0.583 | 03:58 3 Oct | https://www.nofrills.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | President's Choice | Free Run Brown Eggs Large | 12 | $7.18 | REGULAR | $0.598 | 03:57 3 Oct | https://www.nofrills.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Provigo avenue des Canadiens de Montréal (Montréal, Quebec) | President's Choice | Free Run Brown Eggs Large | 12 | $7.17 | REGULAR | $0.598 | 04:00 3 Oct | https://www.provigo.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | President's Choice | Free Run Brown Eggs Large | 12 | $7.15 | REGULAR | $0.596 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | President's Choice | Free Run Brown Eggs Large | 12 | $7.05 | REGULAR | $0.588 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | President's Choice | Free Run Brown Eggs Large | 12 | $7.08 | REGULAR | $0.590 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | President's Choice | Free Run Brown Eggs Large | 12 | $7.74 | REGULAR | $0.645 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | President's Choice | Free Run Brown Eggs Large | 12 | $7.68 | REGULAR | $0.640 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 03:59 3 Oct | https://www.loblaws.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 04:01 3 Oct | https://www.loblaws.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Maxi Montreal Ste-Catherine (Montreal, Quebec) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 03:58 3 Oct | https://www.maxi.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $8.11 | REGULAR | $0.676 | 03:58 3 Oct | https://www.nofrills.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 03:57 3 Oct | https://www.nofrills.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Provigo avenue des Canadiens de Montréal (Montréal, Quebec) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 04:00 3 Oct | https://www.provigo.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Atlantic Superstore - Young Street (Halifax, Nova Scotia) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 04:01 3 Oct | https://www.atlanticsuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | 12 | $7.99 | REGULAR | $0.666 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.49 | REGULAR | $0.624 | 03:59 3 Oct | https://www.loblaws.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.81 | REGULAR | $0.651 | 04:01 3 Oct | https://www.loblaws.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Maxi Montreal Ste-Catherine (Montreal, Quebec) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.00 | SPECIAL to 2026-10-07, was $7.49 | $0.583 | 03:58 3 Oct | https://www.maxi.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Kevin's NOFRILLS Calgary (Calgary, Alberta) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.73 | REGULAR | $0.644 | 03:58 3 Oct | https://www.nofrills.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.81 | REGULAR | $0.651 | 03:58 3 Oct | https://www.nofrills.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.52 | REGULAR | $0.627 | 03:57 3 Oct | https://www.nofrills.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Provigo avenue des Canadiens de Montréal (Montréal, Quebec) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.49 | REGULAR | $0.624 | 04:00 3 Oct | https://www.provigo.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Atlantic Superstore - Young Street (Halifax, Nova Scotia) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.55 | REGULAR | $0.629 | 04:01 3 Oct | https://www.atlanticsuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.49 | REGULAR | $0.624 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.73 | REGULAR | $0.644 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.81 | REGULAR | $0.651 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.73 | REGULAR | $0.644 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | 12 | $7.73 | REGULAR | $0.644 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $5.75 | SPECIAL to 2026-10-07, was $6.75 | $0.479 | 03:59 3 Oct | https://www.loblaws.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $5.75 | SPECIAL to 2026-10-07, was $7.03 | $0.479 | 04:01 3 Oct | https://www.loblaws.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Maxi Montreal Ste-Catherine (Montreal, Quebec) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $6.49 | REGULAR | $0.541 | 03:58 3 Oct | https://www.maxi.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $6.45 | REGULAR | $0.537 | 03:57 3 Oct | https://www.nofrills.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Provigo avenue des Canadiens de Montréal (Montréal, Quebec) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $6.99 | REGULAR | $0.583 | 04:00 3 Oct | https://www.provigo.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $7.03 | REGULAR | $0.586 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $7.03 | REGULAR | $0.586 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $7.03 | REGULAR | $0.586 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | 12 | $7.03 | REGULAR | $0.586 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | Burnbrae Farms | Grade A Large Eggs | 18 | $6.98 | REGULAR | $0.388 | 03:59 3 Oct | https://www.loblaws.ca/grade-a-large-eggs/p/20814294001_EA |
| Maxi Montreal Ste-Catherine (Montreal, Quebec) | Burnbrae Farms | Grade A Large Eggs | 18 | $6.85 | REGULAR | $0.381 | 03:58 3 Oct | https://www.maxi.ca/grade-a-large-eggs/p/20814294001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | Burnbrae Farms | Grade A Large Eggs | 18 | $7.06 | REGULAR | $0.392 | 03:57 3 Oct | https://www.nofrills.ca/grade-a-large-eggs/p/20814294001_EA |
| Provigo avenue des Canadiens de Montréal (Montréal, Quebec) | Burnbrae Farms | Grade A Large Eggs | 18 | $6.98 | REGULAR | $0.388 | 04:00 3 Oct | https://www.provigo.ca/grade-a-large-eggs/p/20814294001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | 12 | $7.50 | SPECIAL to 2026-10-14, was $8.19 | $0.625 | 03:59 3 Oct | https://www.loblaws.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| Maxi Montreal Ste-Catherine (Montreal, Quebec) | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | 12 | $8.19 | REGULAR | $0.682 | 03:58 3 Oct | https://www.maxi.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | 12 | $8.19 | REGULAR | $0.682 | 03:57 3 Oct | https://www.nofrills.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| Provigo avenue des Canadiens de Montréal (Montréal, Quebec) | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | 12 | $7.50 | SPECIAL to 2026-10-14, was $8.19 | $0.625 | 04:00 3 Oct | https://www.provigo.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| Atlantic Superstore - Young Street (Halifax, Nova Scotia) | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | 12 | $7.25 | SPECIAL to 2026-10-14, was $7.97 | $0.604 | 04:01 3 Oct | https://www.atlanticsuperstore.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | 12 | $8.19 | REGULAR | $0.682 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | Gray Ridge | Grade A Brown Eggs, Large | 12 | $6.19 | REGULAR | $0.516 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/grade-a-brown-eggs-large/p/20822900001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | Golden Valley | Born 3 White Eggs, Large | 12 | $7.92 | REGULAR | $0.660 | 04:01 3 Oct | https://www.loblaws.ca/born-3-white-eggs-large/p/20819626001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | Golden Valley | Born 3 White Eggs, Large | 12 | $6.15 | REGULAR | $0.513 | 03:58 3 Oct | https://www.nofrills.ca/born-3-white-eggs-large/p/20819626001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | Golden Valley | Born 3 White Eggs, Large | 12 | $7.92 | REGULAR | $0.660 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/born-3-white-eggs-large/p/20819626001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | Country Golden Yolks | Country Golden Yolk Large Free Range Eggs | 12 | $8.03 | REGULAR | $0.669 | 04:01 3 Oct | https://www.loblaws.ca/country-golden-yolk-large-free-range-eggs/p/20905536001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | Country Golden Yolks | Country Golden Yolk Large Free Range Eggs | 12 | $8.03 | REGULAR | $0.669 | 03:58 3 Oct | https://www.nofrills.ca/country-golden-yolk-large-free-range-eggs/p/20905536001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | Country Golden Yolks | Country Golden Yolk Large Free Range Eggs | 12 | $8.03 | REGULAR | $0.669 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/country-golden-yolk-large-free-range-eggs/p/20905536001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | Rabbit River | Organic Eggs, Medium | 12 | $8.24 | REGULAR | $0.687 | 04:01 3 Oct | https://www.loblaws.ca/organic-eggs-medium/p/20995948001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | Rabbit River | Organic Eggs, Medium | 12 | $8.17 | REGULAR | $0.681 | 03:58 3 Oct | https://www.nofrills.ca/organic-eggs-medium/p/20995948001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | Rabbit River | Organic Eggs, Medium | 12 | $8.19 | REGULAR | $0.682 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | Rabbit River | Organic Eggs, Medium | 12 | $8.19 | REGULAR | $0.682 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | Rabbit River | Organic Eggs, Medium | 12 | $8.19 | REGULAR | $0.682 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | Rabbit River | Organic Eggs, Medium | 12 | $8.19 | REGULAR | $0.682 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| Atlantic Superstore - Young Street (Halifax, Nova Scotia) | Maritime | White Eggs, Large | 18 | $8.17 | REGULAR | $0.454 | 04:01 3 Oct | https://www.atlanticsuperstore.ca/white-eggs-large/p/20830377001_EA |
| Atlantic Superstore - Young Street (Halifax, Nova Scotia) | Nutri-Egg | Free Run Hens Large White Eggs | 12 | $6.37 | REGULAR | $0.531 | 04:01 3 Oct | https://www.atlanticsuperstore.ca/free-run-hens-large-white-eggs/p/21023768001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | Goldegg | Golden D White Eggs, Large | 18 | $8.99 | REGULAR | $0.499 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/golden-d-white-eggs-large/p/20819807001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | Goldegg | Golden D White Eggs, Large | 18 | $8.98 | REGULAR | $0.499 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/golden-d-white-eggs-large/p/20819807001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | Goldegg | Golden D White Eggs, Large | 18 | $8.98 | REGULAR | $0.499 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/golden-d-white-eggs-large/p/20819807001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | Goldegg | Golden D White Eggs, Large | 18 | $8.98 | REGULAR | $0.499 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/golden-d-white-eggs-large/p/20819807001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | Conestoga Eggs | Brown Eggs Free Run Omega-3 Size: Large | 18 | $10.49 | REGULAR | $0.583 | 03:59 3 Oct | https://www.loblaws.ca/brown-eggs-free-run-omega-3-size-large/p/21542380001_EA |
| Bo's NO FRILLS Toronto Richmond (Toronto, Ontario) | Conestoga Eggs | Brown Eggs Free Run Omega-3 Size: Large | 18 | $10.49 | REGULAR | $0.583 | 03:57 3 Oct | https://www.nofrills.ca/brown-eggs-free-run-omega-3-size-large/p/21542380001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | Conestoga Eggs | Brown Eggs Free Run Omega-3 Size: Large | 18 | $10.49 | REGULAR | $0.583 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/brown-eggs-free-run-omega-3-size-large/p/21542380001_EA |
| Kevin's NOFRILLS Calgary (Calgary, Alberta) | Farmers Finest | Comfort Coop, Large Eggs | 12 | $5.57 | REGULAR | $0.464 | 03:58 3 Oct | https://www.nofrills.ca/comfort-coop-large-eggs/p/20882339001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | Farmers Finest | Comfort Coop, Large Eggs | 12 | $5.57 | REGULAR | $0.464 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/comfort-coop-large-eggs/p/20882339001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | Star | Free Bird Free Range Large Eggs | 12 | $7.79 | REGULAR | $0.649 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/free-bird-free-range-large-eggs/p/21033226001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | Foremost | Large Size Eggs 18 Pack | 18 | $7.61 | REGULAR | $0.423 | 04:01 3 Oct | https://www.loblaws.ca/large-size-eggs-18-pack/p/20976887001_EA |
| Kevin's NOFRILLS Calgary (Calgary, Alberta) | Foremost | Large Size Eggs 18 Pack | 18 | $7.25 | REGULAR | $0.403 | 03:58 3 Oct | https://www.nofrills.ca/large-size-eggs-18-pack/p/20976887001_EA |
| Dean's NOFRILLS Vancouver (Vancouver, British Columbia) | Foremost | Large Size Eggs 18 Pack | 18 | $7.29 | REGULAR | $0.405 | 03:58 3 Oct | https://www.nofrills.ca/large-size-eggs-18-pack/p/20976887001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | Foremost | Large Size Eggs 18 Pack | 18 | $6.09 | REGULAR | $0.338 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-18-pack/p/20976887001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | Foremost | Large Size Eggs 18 Pack | 18 | $7.29 | REGULAR | $0.405 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-18-pack/p/20976887001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | Foremost | Large Size Eggs 18 Pack | 18 | $7.27 | REGULAR | $0.404 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-18-pack/p/20976887001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | Foremost | Large Size Eggs 18 Pack | 18 | $7.25 | REGULAR | $0.403 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/large-size-eggs-18-pack/p/20976887001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | Coligny Creek | Free Range Eggs, Brown, 18 Count | 18 | $12.00 | REGULAR | $0.667 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/free-range-eggs-brown-18-count/p/21751043001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | Alderwood Farms | Pasture-Raised Eggs | 12 | $7.99 | SPECIAL to 2026-10-07 | $0.666 | 03:59 3 Oct | https://www.loblaws.ca/pasture-raised-eggs/p/21434214001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | Alderwood Farms | Pasture-Raised Eggs | 12 | $8.99 | REGULAR | $0.749 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/pasture-raised-eggs/p/21434214001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | 18 | $11.49 | REGULAR | $0.638 | 03:59 3 Oct | https://www.loblaws.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| Loblaws City Market Vancouver Post (Vancouver, British Columbia) | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | 18 | $11.49 | REGULAR | $0.638 | 04:01 3 Oct | https://www.loblaws.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | 18 | $11.49 | REGULAR | $0.638 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| Real Canadian Superstore Portage Avenue (Winnipeg, Manitoba) | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | 18 | $11.49 | REGULAR | $0.638 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| Real Canadian Superstore Marine Drive (Vancouver, British Columbia) | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | 18 | $11.49 | REGULAR | $0.638 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| Real Canadian Superstore Albert Street (Regina, Saskatchewan) | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | 18 | $11.49 | REGULAR | $0.638 | 03:57 3 Oct | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| Real Canadian Superstore Heritage Meadows Way (Calgary, Alberta) | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | 18 | $11.49 | REGULAR | $0.638 | 04:00 3 Oct | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| Loblaws Bullock Drive (Markham, Ontario) | Rowe Farms | Green Valley Omega 3 Eggs, Large | 12 | $6.49 | REGULAR | $0.541 | 03:59 3 Oct | https://www.loblaws.ca/green-valley-omega-3-eggs-large/p/20974459001_EA |
| Atlantic Superstore - Young Street (Halifax, Nova Scotia) | Rowe Farms | Green Valley Omega 3 Eggs, Large | 12 | $6.49 | REGULAR | $0.541 | 04:01 3 Oct | https://www.atlanticsuperstore.ca/green-valley-omega-3-eggs-large/p/20974459001_EA |
| Real Canadian Superstore #1080 Argentia Rd (Mississauga, ON) | Rowe Farms | Green Valley Omega 3 Eggs, Large | 12 | $6.49 | REGULAR | $0.541 | 03:58 3 Oct | https://www.realcanadiansuperstore.ca/green-valley-omega-3-eggs-large/p/20974459001_EA |


---

## UNVERIFIED / DO-NOT-USE

Nothing in this section may be stated on air as fact.

| # | Item | Why it is here | What would verify it |
|---|---|---|---|
| 1 | **Packer of any private label** (No Name, PC, PC Organics, PC Blue Menu, Compliments, Longo's, Farm Boy, Selection, Life Smart, Great Value, Western Family, Only Goodness, Kirkland Signature, Best Value) | No label image, retailer page, CFIA/court record or tier (b) report opened today names one. **DO NOT USE (inference only):** two retailer listings carry GTINs that begin 0065651, the same prefix as Burnbrae-branded listings: Loblaw "No Name Large Size Brown Eggs 12 Pack" (GTIN 00065651000120) and Loblaw "Rowe Farms Green Valley Omega 3 Eggs, Large" (GTIN 00065651014073). A shared code prefix is not evidence of who packed the eggs. | A legible "Packed for/by" or grading-station line on a physical carton; a CFIA record; a named news report |
| 2 | All Burnbrae company quotes | Live burnbraefarms.com returned 403 to every request; quotes come from Internet Archive copies (capture dates given). | Re-open the live pages in a browser before broadcast |
| 3 | Burnbrae "Mississauga grading station" | Seen only as a blog URL title in the archive index; page not opened. | Open the page |
| 4 | Burnbrae "Eggs Get Goals" release (11 Jun 2026) | GlobeNewswire URL failed (000); only the headline was seen. | Open the release |
| 5 | Grading-station lines on any carton | Not legible in any retailer image at 500–800 px. | Physical cartons or higher-resolution images |
| 6 | Walmart Canada: Great Value front-of-pack, housing claims, maple leaf, packer; any Walmart egg listing after 04:05 UTC | walmart.ca redirected to `/blocked` for all product pages and later searches. Only search-result names and prices captured 04:03–04:05 UTC are used. | Retry walmart.ca in a browser; photograph cartons in store |
| 7 | Metro: completeness of the egg list; Selection/Life Smart carton text | Aisle pages 2+ are script-loaded and returned no tiles; api2 search URLs returned 403; product images not fetched. | Browser check of metro.ca; store photos |
| 8 | Voilà prices by region | Voilà region unset ("Default Region 1"). | Set a postal code in a browser |
| 9 | Yorkshire Valley Farms ownership (Premium Brands majority stake, reported as 62.6% completed 30 Jul 2018) and whether YVF eggs are on shelves | yorkshirevalleyfarms.com unreachable (egress closed connection); the stake figure comes only from search snippets (Meat+Poultry, PE Hub — paywalled, not opened to standard). No YVF egg listing found on any retailer site today. | Premium Brands annual report / SEDAR+; YVF site |
| 10 | Farmer's Finest owner | A web-search snippet says it is "a Sparks Eggs brand … a division of Golden Valley Foods Ltd., which is a P&H Foods Inc. Company". Its site's text opened today does not say this; only its contact link points to sparkseggs.com. | A Farmer's Finest or P&H page naming it |
| 11 | Owners of: Rowe Farms/Green Valley, Vita, Sunshine Valley, Maple Hill, Coligny Creek, Alderwood Farms, Foremost, Harman, Rochfort Bridge, Britestone, Avalon, Countryside, Daybreak Farms, Gerber's Farm, Vanderwees, Eyking Farm, Gamble Farm, Delong Farms, Keenan Farms, Newfoundland Eggs, Nature's Farm, Coldspring Farm, Farmer John, Nova Eggs, Poultry Farm Laviolette, Hartmann | Not researched to primary-source standard. Search snippets (not opened) say Vita is made by "Countryside Farms, a division of Nutrigroupe"; one Sunshine Valley search result is a farm in Creston BC — not confirmed to be the Voilà brand. | Company pages |
| 12 | Date P&H's purchase of the L. H. Gray businesses completed | P&H pages give no completion date; the "New beginnings" post carries page metadata 2025-10-10. A blog (Agri 007, tier c) says May 2025. | P&H release or a tier (b) report |
| 13 | Completion of the P&H Foods Atlantic joint venture | The 1 Jun 2026 release says "expected to be completed this summer". No completion notice opened. | P&H/API notice |
| 14 | Meaning of Lovo/Nutri "Comfort Farm", Compliments "Cozy Coop", Longo's/GoldEgg "Enriched Coop" | Not defined on any page opened (the Compliments lid text was only partly legible: "From hens raised in small groups in furnished housing…"). Do not equate these names with a housing system on air without the company's own definition. | Company definitions / carton text |
| 15 | Vital Farms on sale in Canada | Only an instacart.ca search result (tier c, not opened). Its 10-K says U.S. | Retailer listing |
| 16 | Sobeys' 2021 statement that the 2025 date would not be met | Search snippets only; the 2021 Sobeys report page was not opened. | Sobeys 2021 SBR page |
| 17 | Any Metro egg figure after June 2021 | Not found on the page opened. | Metro CSR report 2024/2025 |
| 18 | Cage-free percentages for Walmart Canada ("9%"), Costco Canada ("22.6%"), Loblaw ("16%") and Canada-wide comparisons with the U.S./U.K. | From an advocacy scorecard (Mercy For Animals, 2026) and advocacy blogs via search snippets, not opened. Advocacy sources are not tier (b). U.S./U.K. comparisons are foreign data. | Each company's own report |
| 19 | Retail Insider (Oct 2025) and WATTPoultry articles on cage-free pledges | 403 on every request. | Browser |
| 20 | Island Eggs / "Island Gold" on shelves in 2026 | Not found on Loblaw, Voilà or Save-On (Langley, Calgary). islandeggs.com 403. | Thrifty Foods / Country Grocer product pages |
| 21 | Golden Valley's own website | goldenvalleyeggs.com/.ca return only a redirect to "/lander". No inference is drawn. | — |
| 22 | PC Blue Menu "PRODUCT OF CANADA" | Low-resolution, upside-down flap text. | Higher-resolution image |
| 23 | Costco Same-Day "burnbrae-costco-large-eggs-30-ct" and "wcsl-28-ecsl-extra-large-eggs-30-ct" | URLs from earlier project work; today they fell back to a Montréal default store and returned no egg record. URL slugs are not evidence of brand, packer or availability. | Same-Day with a postal code where the item is stocked |
| 24 | Who grades GoldEgg cartons outside ON, AB and BC (e.g. GoldEgg listings at Loblaw-banner stores in Winnipeg and Regina) | P&H says P&H Foods "serves customers across Ontario, Alberta, and British Columbia"; GoldEgg's own page speaks of "local farmers" province by province. Not established for MB/SK cartons. | Carton / company statement |
| 25 | Star Egg joint-venture status today | SaskEgg page undated; Nutri release 2017. | Current SaskEgg annual report |
| 26 | Lovo Egg Industrial Campus year | Release text says "July 9" without a year; page metadata says 2026-07-09. | Release PDF |
| 27 | DCN (27 Jan 2026) figures: $1.2 million grant; "close to 14 per cent"; Q4 2026 start | Outlet byline only ("Daily Commercial News"), no named reporter. | Municipality of Strathroy-Caradoc council record |
| 28 | CTV (16 Jan 2026) "$35 million" | Appears as a page heading for a video; video content not transcribed. | Watch the video / P&H statement |
| 29 | Feed and production statements on cartons ("vegetarian feed", "no antibiotics or animal by-products", "dark yolk", vitamin/nutrient claims) and the Rabbit River slogan | Not transcribed or cut under the house rules (health/food-safety adjacency, taste/yolk-colour opinion). | — |
| 30 | Burnbrae "Organic Free Range Eggs, 18" size | Listing gives no size; image shows "MEDIUM". | Retailer confirmation |
| 31 | Loblaw "Animal Welfare Principles" PDF vs live page wording on 2030 alternatives (enriched listed in the PDF, not on the live page) | Both are Loblaw's own words, quoted literally in §4.1; which is current was not confirmed with Loblaw. | Loblaw statement |
| 32 | Wikipedia, Owler, PitchBook, ZoomInfo, Instacart, Agri 007 blog and similar results that appeared in searches | Tier (c): flagged only, nothing taken from them. | — |

---

# Canadian retail egg prices — retailer captures, 3 Oct 2026 (UTC), plus StatCan and farm-gate context

Prepared 3 Oct 2026. All retail prices below come only from retailers' own sites, apps or APIs, captured between 04:04 and 04:21 UTC on 3 Oct 2026 (00:04–00:21 EDT, 3 Oct; evening of 2 Oct in Pacific time). No flyer aggregators, price trackers, Reddit or blogs were used. Raw captures: `scratchpad/eg/` (subfolders `lb/` Loblaw API JSON, `sof/` Save-On gateway JSON, `vo/` Voilà HTML and JSON, `wm/` Walmart HTML and JSON, `metro/` Metro HTML, `gt/` Giant Tiger JSON, `co/` Costco HTML and JSON, `sc/` Statistics Canada CSV, `src/` egg-board PDFs and pages). The unified listing file is `scratchpad/eg/all_rows.csv` (818 rows; 717 shell-egg rows).

**House rules applied.** This file covers only prices, label wording as printed, and published statistics. Words such as "Omega 3", "Omega Plus", "Golden D", "Vitamin D Enriched", "Born 3" or "Dark Yolk" appear only because they are printed in a retailer's product name. They are not explained. Housing words (free run, free range, organic, nest laid, comfort coop, pasture-raised) are reported only as printed in the listing name. A listing with no such words is marked "None stated". We do not infer how those hens are housed.

## Key findings (all dated, sourced below)

1. **The house-brand dozen of Large eggs costs $2.99 to $4.98 across 13 Loblaw-owned stores on the same night.** No Name "Large Size Eggs 12 Pack" was $3.93 at RCSS #1080 Mississauga, Loblaws #1032 Markham and No Frills #7952 Toronto. It was $2.99 at Maxi #9528 Montréal (regular price). At Provigo #7297 Montréal it was $3.00 on sale (regular $4.29, sale ends 7 Oct 2026). In Winnipeg, Regina and Calgary it was $4.16–$4.20, in Vancouver $4.21, and at Atlantic Superstore #0354 Halifax $4.98. Source: PC Express API, 3 Oct 2026.
2. **Great Value Large 12 at Walmart (store 1061, Mississauga) was $3.93, the same as No Name Large 12 at RCSS #1080 Mississauga.** Metro's Selection Large Eggs 12 at Metro Devonshire, Windsor ON was $3.99.
3. **Large eggs with no housing claim in the name** ran from $0.249/egg (Maxi No Name 12, $2.99) to $0.625/egg (Gold Egg White Eggs Large 6-pack, Save-On, $3.75). That is $2.99 to $7.50 per dozen. A Giant Tiger listing at $0.188/egg (Nutri Large White Eggs, 18-Pack, $3.39) has no province tag and is flagged, not ranked.
4. **Large "free run"** ran from $0.425/egg (Kirkland Signature Free Run Large Eggs, 24 ct, $10.20, Costco Same-Day, Mississauga) to $0.732/egg (Naturegg Free Run Eggs, Large, 6-pack, $4.39, Loblaws Markham and Provigo Montréal).
5. **Large "free range" (not organic)**: the cheapest was Farmers Finest Free Range, Large Eggs 12 at $7.03 ($0.586/egg; No Frills #3155 and RCSS #1539, Calgary). The dearest was Maple Hill Free Range Eggs, Large Size 12 at $8.99 ($0.749; Save-On) and Conestoga Brown Eggs Free Range Omega-3 Large 12 at $8.99 (RCSS Mississauga / Loblaws Markham). See §2 for full rankings.
6. **Large "organic"** ran from $0.561/egg (PC Organics Free-Range Large Brown Eggs, Club Pack 30 ct, $16.84, RCSS #1080) to $0.916/egg (Maple Hill Farms Organic Eggs Free Range Large 12, $10.99, Voilà default region).
7. **Premium over the cheapest no-claim Large egg at the same store** (median across stores, cheapest vs cheapest, regular prices): free run +$0.244/egg (+$2.93/dozen); organic +$0.272/egg (+$3.26/dozen); free range +$0.308/egg (+$3.70/dozen); Nest Laid (as named) +$0.140/egg; Comfort/Cozy Coop (as named) +$0.122/egg. The widest gap was at Maxi #9528: free range was +$0.433/egg (+174%) over the $2.99 No Name dozen.
8. **Private label vs national brand, Large with no claim, same store** (cheapest of each per egg, regular prices, §3a): the cheapest national brand cost 13% to 77% more per egg than the cheapest private label at 18 of 21 stores or groupings. The exceptions: RCSS #1508 Winnipeg, where Foremost 18 was 1% cheaper per egg than No Name 30; Giant Tiger's AB/MB/SK-tagged listings, where Burnbrae Farms Large 12 at $4.16 was 15% cheaper per egg than Best Value Large 12 at $4.89; and Voilà, +3%. For Large free run the pattern often reversed. At RCSS #1533 Regina, Star Free Run Eggs, Large 18 was 31% cheaper per egg than PC Blue Menu Free-Run 12. At RCSS #1080, Loblaws #1032 and No Frills #7952, Conestoga's free-run 18-pack was 2–3% cheaper per egg than President's Choice Free Run 12.
9. **StatCan average retail price, Eggs, 1 dozen (18-10-0245-01)**: Canada $4.95 in July 2026 (latest), unchanged from July 2025, +4.4% over 2 years, +29.6% over 5 years (July 2021 $3.82). BC was highest at $5.75 and Quebec lowest at $4.43.
10. **CPI, Eggs (18-10-0004-01, 2002=100)**: Canada 223.7 in August 2026: −2.4% over 1 year, +1.2% over 2 years, +20.2% over 5 years. Over the same 5 years, all-items rose 19.1% and food purchased from stores 29.0%.
11. **Farm-gate (producer) minimum price, BC Egg Marketing Board orders, Grade A Large, per dozen (white, EXW farm)**: $3.16 from 25 Feb 2024; cut to $2.98 effective 2 Nov 2025; $3.02 effective 19 Apr 2026; $3.07 effective **4 Oct 2026** (Order 02/2026, approved 4 Sept 2026). Egg Farmers of Alberta lists Grade A Large at $2.920 per dozen, effective 2 Nov 2025. Its yearly averages were $3.080 (2024) and $3.055 (2025).

---

## 0. Retailer sources, stores and method

| Retailer / banner | Channel opened (date opened 3 Oct 2026) | Store / region | Result |
|---|---|---|---|
| Real Canadian Superstore, Loblaws, No Frills, Atlantic Superstore, Provigo, Maxi | `POST https://api.pcexpress.ca/pcx-bff/api/v1/products/search` (Loblaw's own PC Express API; 3 passes, 42 search terms, 13 stores; 04:04–04:21 UTC). Store addresses from `GET https://api.pcexpress.ca/pcx-bff/api/v1/pickup-locations?bannerIds=…` (04:04) | RCSS #1080 Mississauga ON, #1517 Vancouver BC, #1539 Calgary AB, #1508 Winnipeg MB, #1533 Regina SK; Loblaws #1032 Markham ON, #7155 (City Market) Vancouver BC; No Frills #7952 Toronto ON, #3155 Calgary AB, #3410 Vancouver BC; Atlantic Superstore #0354 Halifax NS; Provigo #7297 Montréal QC; Maxi #9528 Montréal QC | 200 on all calls; 365 egg-related store-listings; 352 shell-egg listings |
| Save-On-Foods | `GET https://storefrontgateway.saveonfoods.com/api/stores/{id}/categories/30919/search?take=100` (category "Eggs & Substitutes"), store list `…/api/stores` (04:06–04:07) | #1982 Langley Twp BC (the gateway lists it as type "Corporate", shopping mode "planning" only); also #2242 Langley-Downtown BC, #6634 Calgary AB, #4415 Winnipeg MB | 36 / 30 / 31 / 34 items; no promotions returned |
| Voilà by Sobeys | `https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426` (category says 184 products) + `PUT https://voila.ca/api/webproductpagews/v6/products` (04:07–04:08) | No postal code set. The page state reads `regionName "Default Region 1"`, `retailerRegionId "DEF_REG01"`. Region not resolved | 184 products; price shown, promo fields not returned |
| Walmart Canada | `https://www.walmart.ca/en/search?q=…` with a mobile-browser user agent (04:09–04:11) | Page data: store 1061, postal code L5V 2N6 (Mississauga ON) | 11 of 15 searches returned; 4 redirected to `walmart.ca/blocked` |
| Metro | `https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs` + 32 product pages (04:10–04:11). Store page `https://api2.metro.ca/en/find-a-grocery/378` | Metro Devonshire, store 378, 3100 Howard Ave., Windsor ON N8X 3Y8 (`provinceCode "ON"`) | 32 items (data-total-results="32"); sale end dates from product pages |
| Giant Tiger | `https://www.gianttiger.com/collections/eggs/products.json?limit=250` (04:11:36) | No store selected. Each listing carries `mms_province_code` tags and `in_store_only:true` | 83 listings, several duplicated per region |
| Costco.ca | `https://search.costco.ca/api/apps/www_costco_ca/query/www_costco_ca_search?q=eggs` (and 4 other terms) (04:13) | costco.ca online catalogue | **No shell eggs** in costco.ca's online catalogue (27 results for "eggs": egg bites, egg powder, chocolate eggs, etc.) |
| Costco Same-Day (Instacart) | `https://sameday.costco.ca/store/costco-canada/products/63993483-ks-gros-oeufs-en-libert-paquet-de-24?zipcode=L5V2N6&utm_source=nav` (curl 04:12:36 + WebFetch) | postal L5V 2N6, retailer location 40595 (Mississauga) | 1 shell-egg product read. Search and collection pages are JavaScript-only |

**How per-egg prices are computed.** Shelf price ÷ egg count printed in the pack size. Example: No Name Large Size Eggs 12 Pack, RCSS #1080, $3.93 ÷ 12 = $0.3275, shown as $0.328. Regular-price basis = the was/regular price when a sale was live. "Shelf" = the price displayed at capture. Loblaw sale end dates come from the API field `prices.price.expiryDate` / `dealBadge.expiryDate`. Metro sale end dates come from the product page text "On sale until …". Walmart shows "Rollback" with a was-price and no end date. Prices can vary by store, date and pickup or delivery. Metro's page says: "Prices subject to change, depending on your order pickup or delivery date, current promotions, and location." (quoted from the Metro page).

**Grade.** Most retailer listings do not print a grade in the product name. "Grade A" is recorded only where the name says it, and otherwise as "not stated in listing".

### 0b. Same product, different stores: No Name "Large Size Eggs 12 Pack" (Loblaw code 20812144001_EA) and the other house-brand large dozens

| Banner | Store | Product (verbatim) | Shelf price | Regular | Sale end | $/egg (shelf) | Captured (UTC) |
|---|---|---|---|---|---|---|---|
| Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name Large Size Eggs 12 Pack | $2.99 | $2.99 | — | $0.249 | 2026-10-03T04:13:55Z |
| Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name Large Size Eggs 12 Pack | $3.00 | $4.29 | 2026-10-07 | $0.250 | 2026-10-03T04:13:29Z |
| Loblaws | #1032, 200 Bullock Dr, Markham ON | No Name Large Size Eggs 12 Pack | $3.93 | $3.93 | — | $0.328 | 2026-10-03T04:10:57Z |
| No Frills | #7952, 261 Richmond St W, Toronto ON | No Name Large Size Eggs 12 Pack | $3.93 | $3.93 | — | $0.328 | 2026-10-03T04:11:47Z |
| Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | No Name Large Size Eggs 12 Pack | $3.93 | $3.93 | — | $0.328 | 2026-10-03T04:08:37Z |
| Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  Great Value Large 12 Eggs | $3.93 | $3.93 | — | $0.328 | 2026-10-03T04:09:29Z |
| Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection Large Eggs | $3.99 | $3.99 | — | $0.333 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) |
| Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | No Name Large Size Eggs 12 Pack | $4.16 | $4.16 | — | $0.347 | 2026-10-03T04:10:03Z |
| No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | No Name Large Size Eggs 12 Pack | $4.18 | $4.18 | — | $0.348 | 2026-10-03T04:12:10Z |
| Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name Large Size Eggs 12 Pack | $4.18 | $4.18 | — | $0.348 | 2026-10-03T04:09:34Z |
| Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | No Name Large Size Eggs 12 Pack | $4.20 | $4.20 | — | $0.350 | 2026-10-03T04:10:30Z |
| Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | No Name Large Size Eggs 12 Pack | $4.21 | $4.21 | — | $0.351 | 2026-10-03T04:11:24Z |
| No Frills | #3410, 4508 Fraser St, Vancouver BC | No Name Large Size Eggs 12 Pack | $4.21 | $4.21 | — | $0.351 | 2026-10-03T04:12:34Z |
| Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name Large Size Eggs 12 Pack | $4.21 | $4.21 | — | $0.351 | 2026-10-03T04:09:06Z |
| Atlantic Superstore | #0354, 6141 Young St, Halifax NS | No Name Large Size Eggs 12 Pack | $4.98 | $4.98 | — | $0.415 | 2026-10-03T04:13:02Z |

## 1. Price per egg by brand and housing claim, across banners

Shell eggs only, packs of 6 or more, all sizes. $/egg = shelf price ÷ count as captured (sale prices included where a sale was live; regular-price $/egg in the last column). Housing = the claim printed in the retailer's product name; "None stated" means the listing name carries no housing words (we do not infer the housing system). n = listings.

| Brand | Housing claim (name) | Banner | n | Min $/egg (shelf) | Max $/egg (shelf) | Min–max $/egg (regular basis) |
|---|---|---|---|---|---|---|
| Alderwood Farms | Pasture-raised | Loblaws | 2 | $0.666 | $0.708 | $0.666–$0.708 |
| Alderwood Farms | Pasture-raised | Real Canadian Superstore | 2 | $0.749 | $0.791 | $0.749–$0.791 |
| Avalon | Organic | Save-On-Foods | 4 | $0.812 | $0.838 | $0.812–$0.838 |
| Avalon | Organic | Voilà | 2 | $0.824 | $0.833 | $0.824–$0.833 |
| Best Value (Giant Tiger) | None stated | Giant Tiger | 1 | $0.407 | $0.407 | $0.407–$0.407 |
| Born 3 | None stated | Save-On-Foods | 2 | $0.566 | $0.566 | $0.566–$0.566 |
| Britestone | None stated | Voilà | 3 | $0.555 | $0.691 | $0.555–$0.691 |
| Burnbrae Farms | Free range | Atlantic Superstore | 2 | $0.604 | $0.604 | $0.664–$0.664 |
| Burnbrae Farms | Free range | Loblaws | 2 | $0.625 | $0.625 | $0.682–$0.682 |
| Burnbrae Farms | Free range | Maxi | 1 | $0.682 | $0.682 | $0.682–$0.682 |
| Burnbrae Farms | Free range | No Frills | 2 | $0.682 | $0.682 | $0.682–$0.682 |
| Burnbrae Farms | Free range | Provigo | 2 | $0.625 | $0.682 | $0.682–$0.682 |
| Burnbrae Farms | Free range | Real Canadian Superstore | 2 | $0.682 | $0.682 | $0.682–$0.682 |
| Burnbrae Farms | Free range | Voilà | 1 | $0.616 | $0.616 | $0.616–$0.616 |
| Burnbrae Farms | Free run | Giant Tiger | 3 | $0.583 | $0.619 | $0.583–$0.619 |
| Burnbrae Farms | Free run | Loblaws | 2 | $0.657 | $0.732 | $0.657–$0.732 |
| Burnbrae Farms | Free run | Provigo | 1 | $0.732 | $0.732 | $0.732–$0.732 |
| Burnbrae Farms | Free run | Voilà | 1 | $0.665 | $0.665 | $0.665–$0.665 |
| Burnbrae Farms | Nest Laid (as named) | Atlantic Superstore | 2 | $0.458 | $0.521 | $0.489–$0.562 |
| Burnbrae Farms | Nest Laid (as named) | Loblaws | 2 | $0.479 | $0.500 | $0.516–$0.557 |
| Burnbrae Farms | Nest Laid (as named) | Loblaws (City Market) | 1 | $0.479 | $0.479 | $0.479–$0.479 |
| Burnbrae Farms | Nest Laid (as named) | Maxi | 2 | $0.524 | $0.541 | $0.524–$0.541 |
| Burnbrae Farms | Nest Laid (as named) | No Frills | 4 | $0.458 | $0.541 | $0.479–$0.541 |
| Burnbrae Farms | Nest Laid (as named) | Provigo | 1 | $0.500 | $0.500 | $0.541–$0.541 |
| Burnbrae Farms | Nest Laid (as named) | Real Canadian Superstore | 6 | $0.479 | $0.557 | $0.479–$0.557 |
| Burnbrae Farms | Nest Laid (as named) | Voilà | 1 | $0.482 | $0.482 | $0.482–$0.482 |
| Burnbrae Farms | None stated | Atlantic Superstore | 2 | $0.458 | $0.500 | $0.489–$0.531 |
| Burnbrae Farms | None stated | Giant Tiger | 50 | $0.302 | $0.511 | $0.302–$0.511 |
| Burnbrae Farms | None stated | Loblaws | 9 | $0.306 | $0.682 | $0.306–$0.682 |
| Burnbrae Farms | None stated | Loblaws (City Market) | 1 | $0.479 | $0.479 | $0.586–$0.586 |
| Burnbrae Farms | None stated | Maxi | 10 | $0.274 | $0.682 | $0.274–$0.682 |
| Burnbrae Farms | None stated | No Frills | 6 | $0.392 | $0.583 | $0.392–$0.583 |
| Burnbrae Farms | None stated | Provigo | 6 | $0.388 | $0.682 | $0.388–$0.682 |
| Burnbrae Farms | None stated | Real Canadian Superstore | 15 | $0.452 | $0.641 | $0.452–$0.641 |
| Burnbrae Farms | None stated | Voilà | 14 | $0.343 | $0.615 | $0.343–$0.615 |
| Burnbrae Farms | Organic | Loblaws | 1 | $0.638 | $0.638 | $0.638–$0.638 |
| Burnbrae Farms | Organic | Loblaws (City Market) | 1 | $0.638 | $0.638 | $0.638–$0.638 |
| Burnbrae Farms | Organic | Provigo | 1 | $0.678 | $0.678 | $0.678–$0.678 |
| Burnbrae Farms | Organic | Real Canadian Superstore | 5 | $0.638 | $0.638 | $0.638–$0.638 |
| Canadian Harvest | None stated | Voilà | 1 | $0.312 | $0.312 | $0.312–$0.312 |
| Cokk's Dairy Farm | Free range | Voilà | 1 | $0.682 | $0.682 | $0.682–$0.682 |
| Coldspring Farm | Free range | Atlantic Superstore | 1 | $0.684 | $0.684 | $0.684–$0.684 |
| Coligny Creek | Free range | Real Canadian Superstore | 1 | $0.667 | $0.667 | $0.667–$0.667 |
| Coligny Creek | Organic | Real Canadian Superstore | 1 | $0.778 | $0.778 | $0.778–$0.778 |
| Compliments | Enriched/Comfort/Cozy coop (as named) | Voilà | 1 | $0.458 | $0.458 | $0.458–$0.458 |
| Compliments | Free run | Voilà | 4 | $0.583 | $0.624 | $0.583–$0.624 |
| Compliments | None stated | Voilà | 11 | $0.333 | $0.472 | $0.333–$0.472 |
| Compliments | Organic | Voilà | 3 | $0.666 | $0.774 | $0.666–$0.774 |
| Conestoga | Free range | Loblaws | 1 | $0.749 | $0.749 | $0.749–$0.749 |
| Conestoga | Free range | Metro | 1 | $0.641 | $0.641 | $0.641–$0.641 |
| Conestoga | Free range | Real Canadian Superstore | 1 | $0.749 | $0.749 | $0.749–$0.749 |
| Conestoga | Free range | Voilà | 2 | $0.632 | $0.649 | $0.632–$0.649 |
| Conestoga | Free range | Walmart | 1 | $0.582 | $0.582 | $0.582–$0.582 |
| Conestoga | Free run | Loblaws | 2 | $0.583 | $0.583 | $0.583–$0.583 |
| Conestoga | Free run | Metro | 5 | $0.544 | $0.691 | $0.555–$0.691 |
| Conestoga | Free run | No Frills | 2 | $0.583 | $0.583 | $0.583–$0.583 |
| Conestoga | Free run | Real Canadian Superstore | 2 | $0.583 | $0.583 | $0.583–$0.583 |
| Conestoga | Free run | Voilà | 3 | $0.577 | $0.624 | $0.577–$0.624 |
| Conestoga | Free run | Walmart | 3 | $0.554 | $0.619 | $0.554–$0.619 |
| Conestoga | None stated | Real Canadian Superstore | 2 | $0.666 | $0.713 | $0.666–$0.713 |
| Conestoga | Organic | Metro | 1 | $0.865 | $0.865 | $0.865–$0.865 |
| Conestoga | Organic | Voilà | 1 | $0.748 | $0.748 | $0.748–$0.748 |
| Country Golden Yolks | Free range | Loblaws (City Market) | 1 | $0.669 | $0.669 | $0.669–$0.669 |
| Country Golden Yolks | Free range | No Frills | 1 | $0.669 | $0.669 | $0.669–$0.669 |
| Country Golden Yolks | Free range | Real Canadian Superstore | 1 | $0.669 | $0.669 | $0.669–$0.669 |
| Country Golden Yolks | Free range | Voilà | 2 | $0.383 | $0.632 | $0.383–$0.632 |
| Countryside | None stated | Real Canadian Superstore | 1 | $0.404 | $0.404 | $0.404–$0.404 |
| Countryside Farms | Free range | Voilà | 1 | $0.616 | $0.616 | $0.616–$0.616 |
| Daybreak Farms | Free run | Voilà | 1 | $0.541 | $0.541 | $0.541–$0.541 |
| Daybreak Farms | None stated | Voilà | 2 | $0.407 | $0.449 | $0.407–$0.449 |
| Delong Farms | None stated | Giant Tiger | 2 | $0.414 | $0.468 | $0.414–$0.468 |
| Delong Farms | None stated | Voilà | 1 | $0.482 | $0.482 | $0.482–$0.482 |
| Eyking Farm | None stated | Voilà | 2 | $0.461 | $0.474 | $0.461–$0.474 |
| Farmer John | None stated | Giant Tiger | 1 | $0.414 | $0.414 | $0.414–$0.414 |
| Farmer's Finest | Enriched/Comfort/Cozy coop (as named) | Save-On-Foods | 1 | $0.474 | $0.474 | $0.474–$0.474 |
| Farmer's Finest | Free range | Save-On-Foods | 1 | $0.654 | $0.654 | $0.654–$0.654 |
| Farmer's Finest | Organic | Save-On-Foods | 1 | $0.757 | $0.757 | $0.757–$0.757 |
| Farmers Finest | Enriched/Comfort/Cozy coop (as named) | No Frills | 1 | $0.464 | $0.464 | $0.464–$0.464 |
| Farmers Finest | Enriched/Comfort/Cozy coop (as named) | Real Canadian Superstore | 1 | $0.464 | $0.464 | $0.464–$0.464 |
| Farmers Finest | Free range | No Frills | 1 | $0.586 | $0.586 | $0.586–$0.586 |
| Farmers Finest | Free range | Real Canadian Superstore | 1 | $0.586 | $0.586 | $0.586–$0.586 |
| Foremost | None stated | Loblaws (City Market) | 1 | $0.423 | $0.423 | $0.423–$0.423 |
| Foremost | None stated | No Frills | 2 | $0.403 | $0.405 | $0.403–$0.405 |
| Foremost | None stated | Real Canadian Superstore | 4 | $0.338 | $0.405 | $0.338–$0.405 |
| Gamble Farm | Free run | Voilà | 3 | $0.499 | $0.500 | $0.499–$0.500 |
| Gerber's Farm | None stated | Voilà | 2 | $0.391 | $0.407 | $0.391–$0.407 |
| Gold Egg | Enriched/Comfort/Cozy coop (as named) | Voilà | 1 | $0.516 | $0.516 | $0.516–$0.516 |
| Gold Egg | Free run | Metro | 1 | $0.599 | $0.599 | $0.599–$0.599 |
| Gold Egg | Free run | Save-On-Foods | 5 | $0.641 | $0.691 | $0.641–$0.691 |
| Gold Egg | Free run | Voilà | 1 | $0.632 | $0.632 | $0.632–$0.632 |
| Gold Egg | Free run | Walmart | 2 | $0.499 | $0.590 | $0.499–$0.590 |
| Gold Egg | None stated | Metro | 2 | $0.499 | $0.583 | $0.499–$0.632 |
| Gold Egg | None stated | Real Canadian Superstore | 9 | $0.499 | $0.682 | $0.499–$0.682 |
| Gold Egg | None stated | Save-On-Foods | 10 | $0.454 | $0.625 | $0.454–$0.625 |
| Gold Egg | None stated | Voilà | 7 | $0.455 | $0.615 | $0.455–$0.615 |
| Gold Egg | None stated | Walmart | 1 | $0.499 | $0.499 | $0.499–$0.499 |
| Gold Egg | Organic | Save-On-Foods | 1 | $0.841 | $0.841 | $0.841–$0.841 |
| Gold Egg | Organic | Voilà | 2 | $0.708 | $0.708 | $0.708–$0.708 |
| Golden Valley | Free range | Save-On-Foods | 4 | $0.608 | $0.704 | $0.608–$0.704 |
| Golden Valley | None stated | Loblaws (City Market) | 2 | $0.416 | $0.660 | $0.416–$0.660 |
| Golden Valley | None stated | No Frills | 2 | $0.416 | $0.513 | $0.416–$0.513 |
| Golden Valley | None stated | Real Canadian Superstore | 2 | $0.416 | $0.660 | $0.416–$0.660 |
| Golden Valley | None stated | Save-On-Foods | 4 | $0.386 | $0.524 | $0.386–$0.524 |
| Golden Valley | None stated | Voilà | 3 | $0.353 | $0.557 | $0.353–$0.557 |
| Gray Ridge | None stated | Giant Tiger | 1 | $0.443 | $0.443 | $0.443–$0.443 |
| Gray Ridge | None stated | Metro | 8 | $0.405 | $0.565 | $0.405–$0.565 |
| Gray Ridge | None stated | Real Canadian Superstore | 10 | $0.258 | $0.516 | $0.258–$0.516 |
| Gray Ridge | None stated | Voilà | 11 | $0.320 | $0.532 | $0.320–$0.532 |
| Gray Ridge | None stated | Walmart | 4 | $0.358 | $0.448 | $0.358–$0.448 |
| Great Value | None stated | Walmart | 4 | $0.306 | $0.518 | $0.306–$0.578 |
| Great Value | Organic | Walmart | 1 | $0.657 | $0.657 | $0.657–$0.657 |
| Green Valley | Free range | Atlantic Superstore | 1 | $0.691 | $0.691 | $0.691–$0.691 |
| Green Valley | Free range | Loblaws | 1 | $0.691 | $0.691 | $0.691–$0.691 |
| Green Valley Farms | Free range | Voilà | 1 | $0.708 | $0.708 | $0.708–$0.708 |
| Harman | None stated | Real Canadian Superstore | 1 | $0.415 | $0.415 | $0.415–$0.415 |
| Hartmann | None stated | Voilà | 1 | $0.458 | $0.458 | $0.458–$0.458 |
| Kirkland Signature | Free run | Costco Same-Day | 1 | $0.425 | $0.425 | $0.425–$0.425 |
| Laviolette | None stated | Giant Tiger | 3 | $0.328 | $0.386 | $0.328–$0.386 |
| Life Smart | Free run | Metro | 3 | $0.583 | $0.666 | $0.583–$0.666 |
| Life Smart | Organic | Metro | 2 | $0.649 | $0.691 | $0.649–$0.691 |
| Longo's | Enriched/Comfort/Cozy coop (as named) | Voilà | 3 | $0.444 | $0.499 | $0.444–$0.499 |
| Longo's | Free run | Voilà | 1 | $0.624 | $0.624 | $0.624–$0.624 |
| Longo's | None stated | Voilà | 1 | $0.583 | $0.583 | $0.583–$0.583 |
| Lovo | Enriched/Comfort/Cozy coop (as named) | Voilà | 1 | $0.566 | $0.566 | $0.566–$0.566 |
| Lovo | Free run | Save-On-Foods | 4 | $0.499 | $0.625 | $0.499–$0.625 |
| Lovo | Free run | Voilà | 7 | $0.429 | $0.632 | $0.429–$0.632 |
| Lovo | None stated | Save-On-Foods | 2 | $0.411 | $0.549 | $0.411–$0.549 |
| Lovo | None stated | Voilà | 11 | $0.343 | $0.566 | $0.343–$0.566 |
| Lovo | Organic | Save-On-Foods | 2 | $0.625 | $0.729 | $0.625–$0.729 |
| Lovo | Organic | Voilà | 3 | $0.694 | $0.915 | $0.694–$0.915 |
| Maple Hill | Free range | Save-On-Foods | 2 | $0.741 | $0.749 | $0.741–$0.749 |
| Maple Hill | Organic | Save-On-Foods | 2 | $0.749 | $0.774 | $0.749–$0.774 |
| Maple Hill | Organic | Voilà | 2 | $0.916 | $0.916 | $0.916–$0.916 |
| Maritime Pride | Free run | Voilà | 2 | $0.557 | $0.582 | $0.557–$0.582 |
| Maritime Pride | None stated | Atlantic Superstore | 5 | $0.454 | $0.588 | $0.454–$0.588 |
| Maritime Pride | None stated | Giant Tiger | 6 | $0.414 | $0.443 | $0.414–$0.443 |
| Maritime Pride | None stated | Voilà | 11 | $0.346 | $0.615 | $0.346–$0.615 |
| Nature's Farm | Free run | Voilà | 3 | $0.440 | $0.524 | $0.440–$0.524 |
| Nature's Farm | Organic | Voilà | 2 | $0.632 | $0.633 | $0.632–$0.633 |
| Newfoundland Eggs | None stated | Voilà | 4 | $0.466 | $0.532 | $0.466–$0.532 |
| No Name | None stated | Atlantic Superstore | 5 | $0.359 | $0.472 | $0.359–$0.472 |
| No Name | None stated | Loblaws | 5 | $0.306 | $0.524 | $0.306–$0.524 |
| No Name | None stated | Loblaws (City Market) | 5 | $0.340 | $0.448 | $0.340–$0.448 |
| No Name | None stated | Maxi | 5 | $0.249 | $0.469 | $0.249–$0.469 |
| No Name | None stated | No Frills | 17 | $0.316 | $0.499 | $0.316–$0.499 |
| No Name | None stated | Provigo | 5 | $0.250 | $0.482 | $0.344–$0.482 |
| No Name | None stated | Real Canadian Superstore | 34 | $0.306 | $0.456 | $0.306–$0.456 |
| Nova Eggs | None stated | Giant Tiger | 2 | $0.468 | $0.472 | $0.468–$0.472 |
| Nutri | Enriched/Comfort/Cozy coop (as named) | Voilà | 1 | $0.499 | $0.499 | $0.499–$0.499 |
| Nutri | Free range | Voilà | 1 | $0.649 | $0.649 | $0.649–$0.649 |
| Nutri | Free run | Atlantic Superstore | 2 | $0.531 | $0.550 | $0.531–$0.550 |
| Nutri | Free run | Voilà | 1 | $0.537 | $0.537 | $0.537–$0.537 |
| Nutri | None stated | Atlantic Superstore | 2 | $0.550 | $0.583 | $0.550–$0.583 |
| Nutri | None stated | Giant Tiger | 1 | $0.468 | $0.468 | $0.468–$0.468 |
| Nutri | None stated | Voilà | 1 | $0.343 | $0.343 | $0.343–$0.343 |
| Nutri | Organic | Voilà | 1 | $0.758 | $0.758 | $0.758–$0.758 |
| Only Goodness | Organic | Save-On-Foods | 3 | $0.737 | $0.737 | $0.737–$0.737 |
| PC Blue Menu | Free run | Atlantic Superstore | 1 | $0.629 | $0.629 | $0.629–$0.629 |
| PC Blue Menu | Free run | Loblaws | 2 | $0.624 | $0.666 | $0.624–$0.666 |
| PC Blue Menu | Free run | Loblaws (City Market) | 2 | $0.651 | $0.662 | $0.651–$0.662 |
| PC Blue Menu | Free run | Maxi | 1 | $0.583 | $0.583 | $0.624–$0.624 |
| PC Blue Menu | Free run | No Frills | 3 | $0.627 | $0.651 | $0.627–$0.651 |
| PC Blue Menu | Free run | Provigo | 2 | $0.624 | $0.666 | $0.624–$0.666 |
| PC Blue Menu | Free run | Real Canadian Superstore | 10 | $0.624 | $0.666 | $0.624–$0.666 |
| PC Organics | Organic | Atlantic Superstore | 1 | $0.666 | $0.666 | $0.666–$0.666 |
| PC Organics | Organic | Loblaws | 4 | $0.575 | $0.691 | $0.575–$0.691 |
| PC Organics | Organic | Loblaws (City Market) | 2 | $0.575 | $0.666 | $0.575–$0.666 |
| PC Organics | Organic | Maxi | 4 | $0.583 | $0.666 | $0.583–$0.666 |
| PC Organics | Organic | No Frills | 4 | $0.583 | $0.691 | $0.583–$0.691 |
| PC Organics | Organic | Provigo | 4 | $0.575 | $0.678 | $0.575–$0.678 |
| PC Organics | Organic | Real Canadian Superstore | 18 | $0.561 | $0.713 | $0.561–$0.713 |
| President's Choice | Free run | Loblaws | 2 | $0.596 | $0.632 | $0.596–$0.632 |
| President's Choice | Free run | Loblaws (City Market) | 1 | $0.583 | $0.583 | $0.583–$0.583 |
| President's Choice | Free run | Maxi | 1 | $0.598 | $0.598 | $0.598–$0.598 |
| President's Choice | Free run | No Frills | 4 | $0.583 | $0.624 | $0.583–$0.624 |
| President's Choice | Free run | Provigo | 1 | $0.598 | $0.598 | $0.598–$0.598 |
| President's Choice | Free run | Real Canadian Superstore | 6 | $0.588 | $0.645 | $0.588–$0.645 |
| Prestige (Burnbrae) | None stated | Giant Tiger | 3 | $0.382 | $0.443 | $0.382–$0.443 |
| Rabbit River | Free run | Loblaws (City Market) | 1 | $0.620 | $0.620 | $0.620–$0.620 |
| Rabbit River | Free run | No Frills | 2 | $0.549 | $0.555 | $0.549–$0.555 |
| Rabbit River | Free run | Real Canadian Superstore | 1 | $0.617 | $0.617 | $0.617–$0.617 |
| Rabbit River | Free run | Save-On-Foods | 6 | $0.588 | $0.666 | $0.588–$0.666 |
| Rabbit River | Organic | Loblaws (City Market) | 2 | $0.687 | $0.703 | $0.687–$0.703 |
| Rabbit River | Organic | No Frills | 1 | $0.681 | $0.681 | $0.681–$0.681 |
| Rabbit River | Organic | Real Canadian Superstore | 4 | $0.682 | $0.682 | $0.682–$0.682 |
| Rabbit River | Organic | Save-On-Foods | 8 | $0.779 | $0.787 | $0.779–$0.787 |
| Rochfort Bridge | None stated | Voilà | 3 | $0.444 | $0.482 | $0.444–$0.482 |
| Rowe Farms | Free run | Atlantic Superstore | 1 | $0.587 | $0.587 | $0.587–$0.587 |
| Rowe Farms | Free run | Loblaws | 1 | $0.603 | $0.603 | $0.603–$0.603 |
| Rowe Farms | Free run | Real Canadian Superstore | 1 | $0.586 | $0.586 | $0.586–$0.586 |
| Rowe Farms | None stated | Atlantic Superstore | 1 | $0.541 | $0.541 | $0.541–$0.541 |
| Rowe Farms | None stated | Loblaws | 1 | $0.541 | $0.541 | $0.541–$0.541 |
| Rowe Farms | None stated | Real Canadian Superstore | 1 | $0.541 | $0.541 | $0.541–$0.541 |
| Selection | None stated | Metro | 5 | $0.277 | $0.407 | $0.324–$0.407 |
| Sparks | None stated | No Frills | 1 | $0.411 | $0.411 | $0.411–$0.411 |
| Sparks | None stated | Real Canadian Superstore | 1 | $0.411 | $0.411 | $0.411–$0.411 |
| Sparks | None stated | Save-On-Foods | 1 | $0.414 | $0.414 | $0.414–$0.414 |
| Sparks | None stated | Voilà | 1 | $0.343 | $0.343 | $0.343–$0.343 |
| Star | Free range | Real Canadian Superstore | 1 | $0.649 | $0.649 | $0.649–$0.649 |
| Star | Free run | Real Canadian Superstore | 1 | $0.447 | $0.447 | $0.447–$0.447 |
| Star | Organic | Voilà | 1 | $0.633 | $0.633 | $0.633–$0.633 |
| Sunshine Valley | Organic | Voilà | 3 | $0.624 | $0.741 | $0.624–$0.741 |
| Vanderwees | None stated | Voilà | 2 | $0.399 | $0.433 | $0.399–$0.433 |
| Vita | Free run | Save-On-Foods | 2 | $0.499 | $0.621 | $0.499–$0.621 |
| Vita | Free run | Voilà | 3 | $0.450 | $0.583 | $0.450–$0.583 |
| Vita | None stated | Voilà | 1 | $0.524 | $0.524 | $0.524–$0.524 |
| Vita | Organic | Save-On-Foods | 2 | $0.625 | $0.729 | $0.625–$0.729 |
| Vita | Organic | Voilà | 2 | $0.644 | $0.708 | $0.644–$0.708 |
| Western Family | Free range | Save-On-Foods | 3 | $0.654 | $0.654 | $0.654–$0.654 |
| Western Family | Free run | Save-On-Foods | 4 | $0.608 | $0.612 | $0.608–$0.612 |
| Western Family | None stated | Save-On-Foods | 29 | $0.337 | $0.562 | $0.337–$0.562 |
| Western Family | Organic | Save-On-Foods | 1 | $0.704 | $0.704 | $0.704–$0.704 |

### 1b. Median $/egg by housing claim and banner (Large size only, regular-price basis)

| Housing claim | Atlantic Superstore | Costco Same-Day | Giant Tiger | Loblaws | Loblaws (City Market) | Maxi | Metro | No Frills | Provigo | Real Canadian Superstore | Save-On-Foods | Voilà | Walmart |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| None stated | $0.510 (n=10) | — | $0.414 (n=54) | $0.541 (n=9) | $0.436 (n=6) | $0.469 (n=9) | $0.455 (n=10) | $0.404 (n=18) | $0.482 (n=7) | $0.455 (n=51) | $0.482 (n=35) | $0.458 (n=55) | $0.402 (n=5) |
| Nest Laid (as named) | $0.526 (n=2) | — | — | $0.537 (n=2) | $0.479 (n=1) | $0.532 (n=2) | — | $0.498 (n=4) | $0.541 (n=1) | $0.479 (n=6) | — | $0.482 (n=1) | — |
| Enriched/Comfort/Cozy coop (as named) | — | — | — | — | — | — | — | $0.464 (n=1) | — | $0.464 (n=1) | $0.474 (n=1) | $0.499 (n=6) | — |
| Free run | $0.568 (n=4) | $0.425 (n=1) | $0.583 (n=3) | $0.603 (n=7) | $0.651 (n=3) | $0.611 (n=2) | $0.627 (n=8) | $0.586 (n=10) | $0.645 (n=4) | $0.644 (n=19) | $0.621 (n=17) | $0.583 (n=25) | $0.590 (n=5) |
| Free range | $0.674 (n=4) | — | — | $0.687 (n=4) | $0.669 (n=1) | $0.682 (n=1) | $0.641 (n=1) | $0.676 (n=4) | $0.682 (n=2) | $0.676 (n=6) | $0.654 (n=7) | $0.641 (n=6) | — |
| Organic | $0.666 (n=1) | — | — | $0.620 (n=2) | $0.666 (n=3) | $0.625 (n=2) | $0.649 (n=1) | $0.666 (n=3) | $0.666 (n=3) | $0.616 (n=10) | $0.747 (n=16) | $0.708 (n=13) | $0.657 (n=1) |

## 2. Cheapest and dearest listing per type (all banners captured)

Ranked on shelf $/egg as captured on 3 Oct 2026 (UTC). A second line ranks on regular price where a sale was live. Voilà rows are from a session with no postal code set ("Default Region 1"); Giant Tiger rows are online listings with a province tag but no store selected.

### Large, no housing claim in name, white or colour not stated, no Omega/Golden D/other label token ("large conventional white") — 150 listings

| Rank | $/egg (shelf) | $/egg (regular) | Banner | Store / region | Brand | Product name (verbatim) | Count | Shelf price | Regular | Sale end | Captured (UTC) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | $0.249 | $0.249 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name | Large Size Eggs 12 Pack | 12 | $2.99 | $2.99 | — | 2026-10-03T04:13:55Z |
| Cheapest 2 | $0.250 | $0.357 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name | Large Size Eggs 12 Pack | 12 | $3.00 | $4.29 | 2026-10-07 | 2026-10-03T04:13:29Z |
| Cheapest 3 | $0.277 | $0.333 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection | Large Eggs | 18 | $4.99 | $5.99 | October 7, 2026 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) |
| Dearest 1 | $0.625 | $0.625 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Gold Egg | Gold Egg - White Eggs Large | 6 | $3.75 | $3.75 | — | 2026-10-03T04:07:09Z |
| Dearest 2 | $0.625 | $0.625 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Gold Egg | Gold Egg - White Eggs Large | 6 | $3.75 | $3.75 | — | 2026-10-03T04:07:09Z |
| Dearest 3 | $0.625 | $0.625 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Gold Egg | Gold Egg - White Eggs Large | 6 | $3.75 | $3.75 | — | 2026-10-03T04:07:08Z |

Spread (shelf): $0.249 to $0.625 per egg = $2.99 per dozen to $7.50 per dozen.

### Large, "free run" in name (any colour, label tokens allowed) — 108 listings

| Rank | $/egg (shelf) | $/egg (regular) | Banner | Store / region | Brand | Product name (verbatim) | Count | Shelf price | Regular | Sale end | Captured (UTC) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | $0.425 | $0.425 | Costco Same-Day | postal L5V 2N6, retailer location 40595 (Mississauga ON) | Kirkland Signature | Kirkland Signature Free Run Large Eggs | 24 | $10.20 | $10.20 | — | 2026-10-03T04:12:36Z |
| Cheapest 2 | $0.440 | $0.440 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nature's Farm | Nature's Farm Eggs Omega-3 Free Run Large 30 Count | 30 | $13.19 | not shown | — | 2026-10-03T04:08:32Z |
| Cheapest 3 | $0.447 | $0.447 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Star | Free Run Eggs, Large | 18 | $8.04 | $8.04 | — | 2026-10-03T04:10:30Z |
| Dearest 1 | $0.732 | $0.732 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg Free Run Eggs, Large | 6 | $4.39 | $4.39 | — | 2026-10-03T04:06:48Z |
| Dearest 2 | $0.732 | $0.732 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Free Run Eggs, Large | 6 | $4.39 | $4.39 | — | 2026-10-03T04:05:52Z |
| Dearest 3 | $0.691 | $0.691 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Conestoga | Large Free-Run Omega-3 Brown Eggs | 12 | $8.29 | $8.29 | — | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) |

Spread (shelf): $0.425 to $0.732 per egg = $5.10 per dozen to $8.78 per dozen.

### Large, "free range" in name, not organic (any colour) — 36 listings

| Rank | $/egg (shelf) | $/egg (regular) | Banner | Store / region | Brand | Product name (verbatim) | Count | Shelf price | Regular | Sale end | Captured (UTC) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | $0.586 | $0.586 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | Farmers Finest | Free Range, Large Eggs | 12 | $7.03 | $7.03 | — | 2026-10-03T04:12:10Z |
| Cheapest 2 | $0.586 | $0.586 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Farmers Finest | Free Range, Large Eggs | 12 | $7.03 | $7.03 | — | 2026-10-03T04:09:34Z |
| Cheapest 3 | $0.604 | $0.664 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Burnbrae Farms | Naturegg Omega Plus Solar Free Range Eggs, Large | 12 | $7.25 | $7.97 | 2026-10-14 | 2026-10-03T04:13:02Z |
| Dearest 1 | $0.749 | $0.749 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Maple Hill | Maple Hill - Free Range Eggs, Large Size | 12 | $8.99 | $8.99 | — | 2026-10-03T04:06:39Z |
| Dearest 2 | $0.749 | $0.749 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Conestoga | Brown Eggs Free Range Omega-3 Large Size | 12 | $8.99 | $8.99 | — | 2026-10-03T04:04:51Z |
| Dearest 3 | $0.749 | $0.749 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Conestoga | Brown Eggs Free Range Omega-3 Large Size | 12 | $8.99 | $8.99 | — | 2026-10-03T04:05:48Z |

Spread (shelf): $0.586 to $0.749 per egg = $7.03 per dozen to $8.99 per dozen.

### Large, "organic" in name (any colour; many also say free range or free run) — 55 listings

| Rank | $/egg (shelf) | $/egg (regular) | Banner | Store / region | Brand | Product name (verbatim) | Count | Shelf price | Regular | Sale end | Captured (UTC) |
|---|---|---|---|---|---|---|---|---|---|---|---|
| Cheapest 1 | $0.561 | $0.561 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | 30 | $16.84 | $16.84 | — | 2026-10-03T04:08:37Z |
| Cheapest 2 | $0.566 | $0.566 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | 30 | $16.99 | $16.99 | — | 2026-10-03T04:10:03Z |
| Cheapest 3 | $0.566 | $0.566 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | 30 | $16.99 | $16.99 | — | 2026-10-03T04:09:06Z |
| Dearest 1 | $0.916 | $0.916 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maple Hill | Maple Hill Farms Organic Eggs Free Range Large 12 Count | 12 | $10.99 | not shown | — | 2026-10-03T04:08:32Z |
| Dearest 2 | $0.915 | $0.915 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo Organic Brown Eggs Large 6 Count | 6 | $5.49 | not shown | — | 2026-10-03T04:08:32Z |
| Dearest 3 | $0.824 | $0.824 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Avalon | Avalon Organics Brown Eggs Free Range Large 12 Count | 12 | $9.89 | not shown | — | 2026-10-03T04:08:32Z |

Spread (shelf): $0.561 to $0.916 per egg = $6.74 per dozen to $10.99 per dozen.

## 3. National brand vs private label at the same store

Same store, same type, Large only, regular-price basis ($/egg). "Private label" = a retailer-owned brand (No Name, President's Choice, PC Blue Menu, PC Organics, Compliments, Longo's, Western Family, Only Goodness, Great Value, Selection, Life Smart, Kirkland Signature, Best Value). Positive gap = the national brand costs more per egg. Table 3a compares the cheapest listing of each kind in any pack size; table 3b compares 12-egg cartons only (like-for-like pack).

### 3a. Cheapest per egg, any pack size

| Store | Type | Private label (cheapest) | PL $/egg | National brand (cheapest) | NB $/egg | Gap $/egg | Gap % |
|---|---|---|---|---|---|---|---|
| Atlantic Superstore — #0354, 6141 Young St, Halifax NS | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.78) | $0.359 | Maritime Pride — White Eggs, Large (18 ct, $8.17) | $0.454 | +$0.095 | +26% |
| Atlantic Superstore — #0354, 6141 Young St, Halifax NS | Large free run | PC Blue Menu — Blue Menu Free-Run Large Size White Eggs 12 Pack (12 ct, $7.55) | $0.629 | Nutri — Free Run Hens Large White Eggs (12 ct, $6.37) | $0.531 | −$0.098 | -16% |
| Giant Tiger — online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Large conventional (no claim, not brown) | Best Value (Giant Tiger) — Best Value Eggs, Large, 12-pack (12 ct, $4.89) | $0.407 | Burnbrae Farms — Burnbrae Farms Large Eggs, 12-Pack (12 ct, $4.16) | $0.347 | −$0.061 | -15% |
| Loblaws (City Market) — #7155, 658 Homer St, Vancouver BC | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.22) | $0.341 | Foremost — Large Size Eggs 18 Pack (18 ct, $7.61) | $0.423 | +$0.082 | +24% |
| Loblaws (City Market) — #7155, 658 Homer St, Vancouver BC | Large organic | PC Organics — Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $17.25) | $0.575 | Rabbit River — Large Organic Eggs (12 ct, $8.44) | $0.703 | +$0.128 | +22% |
| Loblaws — #1032, 200 Bullock Dr, Markham ON | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Burnbrae Farms — Grade A Large Eggs (18 ct, $6.98) | $0.388 | +$0.060 | +18% |
| Loblaws — #1032, 200 Bullock Dr, Markham ON | Large free run | President's Choice — Free Run Brown Eggs Large (12 ct, $7.15) | $0.596 | Conestoga — Brown Eggs Free Run Omega-3 Size: Large (18 ct, $10.49) | $0.583 | −$0.013 | -2% |
| Maxi — #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $2.99) | $0.249 | Burnbrae Farms — Grade A Large Eggs (18 ct, $6.85) | $0.381 | +$0.131 | +53% |
| Metro — Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Large conventional (no claim, not brown) | Selection — Large Eggs (12 ct, $3.99) | $0.333 | Gray Ridge — Large Eggs, Premium Brand (18 ct, $7.29) | $0.405 | +$0.073 | +22% |
| Metro — Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Large free run | Life Smart — Large Free-Run Eggs, Naturalia (18 ct, $10.49) | $0.583 | Conestoga — Large Free-Run Omega-3 Eggs (18 ct, $9.99) | $0.555 | −$0.028 | -5% |
| No Frills — #3155, 10233 Elbow Dr SW, Calgary AB | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.28) | $0.343 | Foremost — Large Size Eggs 18 Pack (18 ct, $7.25) | $0.403 | +$0.060 | +18% |
| No Frills — #3410, 4508 Fraser St, Vancouver BC | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.22) | $0.341 | Foremost — Large Size Eggs 18 Pack (18 ct, $7.29) | $0.405 | +$0.064 | +19% |
| No Frills — #3410, 4508 Fraser St, Vancouver BC | Large free run | President's Choice — Free Run Brown Eggs Large (12 ct, $6.99) | $0.583 | Rabbit River — Large Size Brown Eggs Free Run (18 ct, $9.88) | $0.549 | −$0.034 | -6% |
| No Frills — #7952, 261 Richmond St W, Toronto ON | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Burnbrae Farms — Grade A Large Eggs (18 ct, $7.06) | $0.392 | +$0.065 | +20% |
| No Frills — #7952, 261 Richmond St W, Toronto ON | Large free run | President's Choice — Free Run Brown Eggs Large (12 ct, $7.18) | $0.598 | Conestoga — Brown Eggs Free Run Omega-3 Size: Large (18 ct, $10.49) | $0.583 | −$0.016 | -3% |
| Provigo — #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.33) | $0.344 | Burnbrae Farms — Grade A Large Eggs (18 ct, $6.98) | $0.388 | +$0.043 | +13% |
| Provigo — #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Large free run | President's Choice — Free Run Brown Eggs Large (12 ct, $7.17) | $0.598 | Burnbrae Farms — Naturegg Free Run Eggs, Large (6 ct, $4.39) | $0.732 | +$0.134 | +22% |
| Provigo — #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Large organic | PC Organics — Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $17.25) | $0.575 | Burnbrae Farms — Naturegg Organic White Eggs, Large (12 ct, $8.13) | $0.678 | +$0.103 | +18% |
| Real Canadian Superstore — #1080, 3050 Argentia Rd, Mississauga ON | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Gray Ridge — Premium Large Eggs (18 ct, $6.98) | $0.388 | +$0.060 | +18% |
| Real Canadian Superstore — #1080, 3050 Argentia Rd, Mississauga ON | Large free run | President's Choice — Free Run Brown Eggs Large (12 ct, $7.15) | $0.596 | Conestoga — Brown Eggs Free Run Omega-3 Size: Large (18 ct, $10.49) | $0.583 | −$0.013 | -2% |
| Real Canadian Superstore — #1508, 3193 Portage Ave, Winnipeg MB | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.25) | $0.342 | Foremost — Large Size Eggs 18 Pack (18 ct, $6.09) | $0.338 | −$0.003 | -1% |
| Real Canadian Superstore — #1517, 350 SE Marine Dr, Vancouver BC | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.22) | $0.341 | Foremost — Large Size Eggs 18 Pack (18 ct, $7.29) | $0.405 | +$0.064 | +19% |
| Real Canadian Superstore — #1533, 3806 Albert St, Regina SK | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.28) | $0.343 | Foremost — Large Size Eggs 18 Pack (18 ct, $7.27) | $0.404 | +$0.061 | +18% |
| Real Canadian Superstore — #1533, 3806 Albert St, Regina SK | Large free run | PC Blue Menu — Blue Menu Free-Run Large Size White Eggs 12 Pack (12 ct, $7.73) | $0.644 | Star — Free Run Eggs, Large (18 ct, $8.04) | $0.447 | −$0.198 | -31% |
| Real Canadian Superstore — #1539, 20 Heritage Meadows Way SE, Calgary AB | Large conventional (no claim, not brown) | No Name — Large Size Eggs (30 ct, $10.28) | $0.343 | Foremost — Large Size Eggs 18 Pack (18 ct, $7.25) | $0.403 | +$0.060 | +18% |
| Save-On-Foods — #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Large conventional (no claim, not brown) | Western Family — Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Gold Egg — Gold Egg - White Eggs Large (6 ct, $3.75) | $0.625 | +$0.272 | +77% |
| Save-On-Foods — #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Large free range | Western Family — Western Family - Free Range Brown Eggs, Large (12 ct, $7.85) | $0.654 | Golden Valley — Golden Valley - Country Golden Yolks Free Range Large Brown Eggs (12 ct, $8.45) | $0.704 | +$0.050 | +8% |
| Save-On-Foods — #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Large organic | Only Goodness — ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | Maple Hill — Maple Hill - Large Organic Free Range Eggs (12 ct, $9.29) | $0.774 | +$0.037 | +5% |
| Save-On-Foods — #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Large conventional (no claim, not brown) | Western Family — Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Gold Egg — Gold Egg - White Eggs Large (6 ct, $3.75) | $0.625 | +$0.272 | +77% |
| Save-On-Foods — #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Large free range | Western Family — Western Family - Free Range Brown Eggs, Large (12 ct, $7.85) | $0.654 | Golden Valley — Golden Valley - Country Golden Yolks Free Range Large Brown Eggs (12 ct, $8.45) | $0.704 | +$0.050 | +8% |
| Save-On-Foods — #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Large organic | Only Goodness — ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | Rabbit River — Rabbit River Farms - Organic Free Range Large Brown Eggs (12 ct, $9.35) | $0.779 | +$0.042 | +6% |
| Save-On-Foods — #4415 St James, 850 St James St, Winnipeg MB | Large conventional (no claim, not brown) | Western Family — Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Gold Egg — Gold Egg - Grain Fed Large Eggs White (12 ct, $6.09) | $0.507 | +$0.154 | +44% |
| Save-On-Foods — #4415 St James, 850 St James St, Winnipeg MB | Large organic | Western Family — Western Family - Organic Free Range Large Eggs (12 ct, $8.45) | $0.704 | Vita — VITA - Vita Organic Large Eggs (18 ct, $11.25) | $0.625 | −$0.079 | -11% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Large conventional (no claim, not brown) | Western Family — Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Gold Egg — Gold Egg - Grain Fed Large Eggs White (12 ct, $6.09) | $0.507 | +$0.154 | +44% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Large free range | Western Family — Western Family - Free Range Brown Eggs, Large (12 ct, $7.85) | $0.654 | Farmer's Finest — Farmer's Finest - Free Range Large Eggs Brown (12 ct, $7.85) | $0.654 | +$0.000 | +0% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Large organic | Only Goodness — ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | Farmer's Finest — Farmer's Finest - Organic Large Eggs Brown (12 ct, $9.09) | $0.757 | +$0.020 | +3% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Large conventional (no claim, not brown) | Compliments — Compliments Specialty Eggs Large 12 Count (12 ct, $3.99) | $0.333 | Lovo — Lovo White Eggs Shrink Large 30 Count (30 ct, $10.29) | $0.343 | +$0.010 | +3% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Large free run | Compliments — Compliments White Eggs Free Run Large 12 Count (12 ct, $6.99) | $0.583 | Nature's Farm — Nature's Farm Eggs Omega-3 Free Run Large 30 Count (30 ct, $13.19) | $0.440 | −$0.143 | -25% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Large organic | Compliments — Compliments Organic Brown Eggs Free Range Grade A Large 12 Count (12 ct, $8.49) | $0.708 | Nature's Farm — Natures Farm Organic Omega 3 Eggs Large 12 Count (12 ct, $7.59) | $0.632 | −$0.075 | -11% |
| Walmart — store 1061 (page postal code L5V 2N6, Mississauga ON) | Large conventional (no claim, not brown) | Great Value — Great Value Large 12 Eggs (12 ct, $3.93) | $0.328 | Gray Ridge — Gray Ridge Premium Large White 18 Eggs (18 ct, $6.98) | $0.388 | +$0.060 | +18% |

### 3b. 12-egg cartons only

| Store | Type | Private label (cheapest) | PL $/egg | National brand (cheapest) | NB $/egg | Gap $/egg | Gap % |
|---|---|---|---|---|---|---|---|
| Atlantic Superstore — #0354, 6141 Young St, Halifax NS | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $4.98) | $0.415 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $5.87) | $0.489 | +$0.074 | +18% |
| Atlantic Superstore — #0354, 6141 Young St, Halifax NS | Large free run | PC Blue Menu — Blue Menu Free-Run Large Size White Eggs 12 Pack (12 ct, $7.55) | $0.629 | Nutri — Free Run Hens Large White Eggs (12 ct, $6.37) | $0.531 | −$0.098 | -16% |
| Giant Tiger — online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Large conventional (no claim, not brown) | Best Value (Giant Tiger) — Best Value Eggs, Large, 12-pack (12 ct, $4.89) | $0.407 | Burnbrae Farms — Burnbrae Farms Large Eggs, 12-Pack (12 ct, $4.16) | $0.347 | −$0.061 | -15% |
| Loblaws (City Market) — #7155, 658 Homer St, Vancouver BC | Large organic | PC Organics — Organics Large Size Free-Range Brown Eggs 12 Pack (12 ct, $7.99) | $0.666 | Rabbit River — Large Organic Eggs (12 ct, $8.44) | $0.703 | +$0.037 | +6% |
| Loblaws — #1032, 200 Bullock Dr, Markham ON | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $6.21) | $0.517 | +$0.190 | +58% |
| Loblaws — #1032, 200 Bullock Dr, Markham ON | Large free run | President's Choice — Free Run Brown Eggs Large (12 ct, $7.15) | $0.596 | Rowe Farms — Green Valley Eggs Size Large Free Run Brown (12 ct, $7.23) | $0.603 | +$0.007 | +1% |
| Maxi — #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $2.99) | $0.249 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $4.99) | $0.416 | +$0.167 | +67% |
| Metro — Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Large conventional (no claim, not brown) | Selection — Large Eggs (12 ct, $3.99) | $0.333 | Gray Ridge — Large Eggs, Premium Brand (12 ct, $5.59) | $0.466 | +$0.133 | +40% |
| Metro — Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Large free run | Life Smart — Large Free-Run Eggs, Naturalia (12 ct, $7.59) | $0.632 | Gold Egg — Large Free-Run Brown Eggs (12 ct, $7.19) | $0.599 | −$0.033 | -5% |
| No Frills — #3410, 4508 Fraser St, Vancouver BC | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $4.21) | $0.351 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $6.39) | $0.532 | +$0.182 | +52% |
| No Frills — #7952, 261 Richmond St W, Toronto ON | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $5.99) | $0.499 | +$0.172 | +52% |
| Provigo — #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Large organic | PC Organics — Organics Large Size Free-Range Brown Eggs 12 Pack (12 ct, $7.99) | $0.666 | Burnbrae Farms — Naturegg Organic White Eggs, Large (12 ct, $8.13) | $0.678 | +$0.012 | +2% |
| Real Canadian Superstore — #1080, 3050 Argentia Rd, Mississauga ON | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Gray Ridge — Grade A Premium White Eggs, Large (12 ct, $5.19) | $0.433 | +$0.105 | +32% |
| Real Canadian Superstore — #1080, 3050 Argentia Rd, Mississauga ON | Large free run | President's Choice — Free Run Brown Eggs Large (12 ct, $7.15) | $0.596 | Rowe Farms — Green Valley Eggs Size Large Free Run Brown (12 ct, $7.03) | $0.586 | −$0.010 | -2% |
| Real Canadian Superstore — #1508, 3193 Portage Ave, Winnipeg MB | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $4.16) | $0.347 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $6.38) | $0.532 | +$0.185 | +53% |
| Real Canadian Superstore — #1517, 350 SE Marine Dr, Vancouver BC | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $4.21) | $0.351 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $6.39) | $0.532 | +$0.182 | +52% |
| Real Canadian Superstore — #1533, 3806 Albert St, Regina SK | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $4.20) | $0.350 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $6.49) | $0.541 | +$0.191 | +55% |
| Real Canadian Superstore — #1539, 20 Heritage Meadows Way SE, Calgary AB | Large conventional (no claim, not brown) | No Name — Large Size Eggs 12 Pack (12 ct, $4.18) | $0.348 | Burnbrae Farms — Nature's Best White Eggs, Large (12 ct, $6.39) | $0.532 | +$0.184 | +53% |
| Save-On-Foods — #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Large free range | Western Family — Western Family - Free Range Brown Eggs, Large (12 ct, $7.85) | $0.654 | Golden Valley — Golden Valley - Country Golden Yolks Free Range Large Brown Eggs (12 ct, $8.45) | $0.704 | +$0.050 | +8% |
| Save-On-Foods — #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Large organic | Only Goodness — ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | Maple Hill — Maple Hill - Large Organic Free Range Eggs (12 ct, $9.29) | $0.774 | +$0.037 | +5% |
| Save-On-Foods — #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Large free range | Western Family — Western Family - Free Range Brown Eggs, Large (12 ct, $7.85) | $0.654 | Golden Valley — Golden Valley - Country Golden Yolks Free Range Large Brown Eggs (12 ct, $8.45) | $0.704 | +$0.050 | +8% |
| Save-On-Foods — #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Large organic | Only Goodness — ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | Rabbit River — Rabbit River Farms - Organic Free Range Large Brown Eggs (12 ct, $9.35) | $0.779 | +$0.042 | +6% |
| Save-On-Foods — #4415 St James, 850 St James St, Winnipeg MB | Large conventional (no claim, not brown) | Western Family — Western Family - Large White Eggs (12 ct, $4.35) | $0.362 | Gold Egg — Gold Egg - Grain Fed Large Eggs White (12 ct, $6.09) | $0.507 | +$0.145 | +40% |
| Save-On-Foods — #4415 St James, 850 St James St, Winnipeg MB | Large organic | Western Family — Western Family - Organic Free Range Large Eggs (12 ct, $8.45) | $0.704 | Vita — VITA - Organic Large Eggs (12 ct, $8.75) | $0.729 | +$0.025 | +4% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Large conventional (no claim, not brown) | Western Family — Western Family - Large White Eggs (12 ct, $4.35) | $0.362 | Gold Egg — Gold Egg - Grain Fed Large Eggs White (12 ct, $6.09) | $0.507 | +$0.145 | +40% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Large free range | Western Family — Western Family - Free Range Brown Eggs, Large (12 ct, $7.85) | $0.654 | Farmer's Finest — Farmer's Finest - Free Range Large Eggs Brown (12 ct, $7.85) | $0.654 | +$0.000 | +0% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Large organic | Only Goodness — ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | Farmer's Finest — Farmer's Finest - Organic Large Eggs Brown (12 ct, $9.09) | $0.757 | +$0.020 | +3% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Large conventional (no claim, not brown) | Compliments — Compliments Specialty Eggs Large 12 Count (12 ct, $3.99) | $0.333 | Lovo — Lovo White Eggs Large 12 Count (12 ct, $4.19) | $0.349 | +$0.017 | +5% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Large free run | Compliments — Compliments White Eggs Free Run Large 12 Count (12 ct, $6.99) | $0.583 | Nature's Farm — Nature's Farm Smart Eggs Omega 3 Eggs Free Run Large 12 Count (12 ct, $6.29) | $0.524 | −$0.058 | -10% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Large organic | Compliments — Compliments Organic Brown Eggs Free Range Grade A Large 12 Count (12 ct, $8.49) | $0.708 | Nature's Farm — Natures Farm Organic Omega 3 Eggs Large 12 Count (12 ct, $7.59) | $0.632 | −$0.075 | -11% |

## 4. Premium per egg for each housing claim vs "no housing claim" eggs at the same store

Baseline per store = cheapest Large listing with no housing words in its name (any colour, no label token), regular-price basis. For each claim, the cheapest Large listing with that claim at the same store. Premium = claim $/egg − baseline $/egg (and per dozen). This is a price comparison of listing names only; it does not state or imply anything about the housing of the baseline eggs.

| Store | Baseline listing | Base $/egg | Claim | Cheapest listing with claim | $/egg | Premium $/egg | Premium per dozen | Premium % |
|---|---|---|---|---|---|---|---|---|
| Atlantic Superstore — #0354, 6141 Young St, Halifax NS | No Name Large Size Eggs (30 ct, $10.78) | $0.359 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $5.87) | $0.489 | $0.130 | $1.56 | +36% |
| Atlantic Superstore — #0354, 6141 Young St, Halifax NS | No Name Large Size Eggs (30 ct, $10.78) | $0.359 | Free run | Nutri Free Run Hens Large White Eggs (12 ct, $6.37) | $0.531 | $0.172 | $2.06 | +48% |
| Atlantic Superstore — #0354, 6141 Young St, Halifax NS | No Name Large Size Eggs (30 ct, $10.78) | $0.359 | Free range | Burnbrae Farms Naturegg Omega Plus Solar Free Range Eggs, Large (12 ct, $7.97) | $0.664 | $0.305 | $3.66 | +85% |
| Atlantic Superstore — #0354, 6141 Young St, Halifax NS | No Name Large Size Eggs (30 ct, $10.78) | $0.359 | Organic | PC Organics Organics Large Size Free-Range Brown Eggs 12 Pack (12 ct, $7.99) | $0.666 | $0.307 | $3.68 | +85% |
| Giant Tiger — online listing, province tag(s): ON,QC; tag in_store_only:true; no store selected | Burnbrae Farms Burnbrae Farms Large Eggs, 12-Pack (12 ct, $3.93) | $0.328 | Free run | Burnbrae Farms Burnbrae Farms Naturegg Free Run Large Eggs, 12-Pack (12 ct, $6.99) | $0.583 | $0.255 | $3.06 | +78% |
| Giant Tiger — online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms Burnbrae Farms Large White Eggs, 30-Pack (30 ct, $9.52) | $0.317 | Free run | Burnbrae Farms Burnbrae Farms Naturegg Free Run Large Eggs, 12-Pack (12 ct, $6.99) | $0.583 | $0.265 | $3.18 | +84% |
| Loblaws (City Market) — #7155, 658 Homer St, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $5.75) | $0.479 | $0.139 | $1.66 | +41% |
| Loblaws (City Market) — #7155, 658 Homer St, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Free run | President's Choice Free Run Brown Eggs Large (12 ct, $6.99) | $0.583 | $0.242 | $2.90 | +71% |
| Loblaws (City Market) — #7155, 658 Homer St, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Free range | Country Golden Yolks Country Golden Yolk Large Free Range Eggs (12 ct, $8.03) | $0.669 | $0.328 | $3.94 | +96% |
| Loblaws (City Market) — #7155, 658 Homer St, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $17.25) | $0.575 | $0.234 | $2.81 | +69% |
| Loblaws — #1032, 200 Bullock Dr, Markham ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $6.19) | $0.516 | $0.188 | $2.26 | +58% |
| Loblaws — #1032, 200 Bullock Dr, Markham ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Free run | Conestoga Brown Eggs Free Run Omega-3 Size: Large (18 ct, $10.49) | $0.583 | $0.255 | $3.06 | +78% |
| Loblaws — #1032, 200 Bullock Dr, Markham ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Free range | Burnbrae Farms Naturegg Solar Free Range Eggs, Large (12 ct, $8.19) | $0.682 | $0.355 | $4.26 | +108% |
| Loblaws — #1032, 200 Bullock Dr, Markham ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $17.25) | $0.575 | $0.247 | $2.97 | +76% |
| Maxi — #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name Large Size Eggs 12 Pack (12 ct, $2.99) | $0.249 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $6.29) | $0.524 | $0.275 | $3.30 | +110% |
| Maxi — #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name Large Size Eggs 12 Pack (12 ct, $2.99) | $0.249 | Free run | President's Choice Free Run Brown Eggs Large (12 ct, $7.17) | $0.598 | $0.348 | $4.18 | +140% |
| Maxi — #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name Large Size Eggs 12 Pack (12 ct, $2.99) | $0.249 | Free range | Burnbrae Farms Naturegg Solar Free Range Eggs, Large (12 ct, $8.19) | $0.682 | $0.433 | $5.20 | +174% |
| Maxi — #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name Large Size Eggs 12 Pack (12 ct, $2.99) | $0.249 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $17.50) | $0.583 | $0.334 | $4.01 | +134% |
| Metro — Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection Large Eggs (12 ct, $3.99) | $0.333 | Free run | Conestoga Large Free-Run Omega-3 Eggs (18 ct, $9.99) | $0.555 | $0.223 | $2.67 | +67% |
| Metro — Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection Large Eggs (12 ct, $3.99) | $0.333 | Free range | Conestoga Large Free-Range Eggs (12 ct, $7.69) | $0.641 | $0.308 | $3.70 | +93% |
| Metro — Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection Large Eggs (12 ct, $3.99) | $0.333 | Organic | Life Smart Large Organic Brown Eggs, Free-Range (12 ct, $7.79) | $0.649 | $0.317 | $3.80 | +95% |
| No Frills — #3155, 10233 Elbow Dr SW, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $5.75) | $0.479 | $0.137 | $1.64 | +40% |
| No Frills — #3155, 10233 Elbow Dr SW, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Enriched/Comfort/Cozy coop (as named) | Farmers Finest Comfort Coop, Large Eggs (12 ct, $5.57) | $0.464 | $0.122 | $1.46 | +35% |
| No Frills — #3155, 10233 Elbow Dr SW, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Free run | President's Choice Free Run Brown Eggs Large (12 ct, $7.07) | $0.589 | $0.247 | $2.96 | +72% |
| No Frills — #3155, 10233 Elbow Dr SW, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Free range | Farmers Finest Free Range, Large Eggs (12 ct, $7.03) | $0.586 | $0.243 | $2.92 | +71% |
| No Frills — #3410, 4508 Fraser St, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $5.75) | $0.479 | $0.139 | $1.66 | +41% |
| No Frills — #3410, 4508 Fraser St, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Free run | Rabbit River Large Size Brown Eggs Free Run (18 ct, $9.88) | $0.549 | $0.208 | $2.50 | +61% |
| No Frills — #3410, 4508 Fraser St, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Free range | Country Golden Yolks Country Golden Yolk Large Free Range Eggs (12 ct, $8.03) | $0.669 | $0.328 | $3.94 | +96% |
| No Frills — #3410, 4508 Fraser St, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Organic | PC Organics Organics Large Size Free-Range Brown Eggs 12 Pack (12 ct, $8.11) | $0.676 | $0.335 | $4.02 | +98% |
| No Frills — #7952, 261 Richmond St W, Toronto ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $6.19) | $0.516 | $0.188 | $2.26 | +58% |
| No Frills — #7952, 261 Richmond St W, Toronto ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Free run | Conestoga Brown Eggs Free Run Omega-3 Size: Large (18 ct, $10.49) | $0.583 | $0.255 | $3.06 | +78% |
| No Frills — #7952, 261 Richmond St W, Toronto ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Free range | Burnbrae Farms Naturegg Solar Free Range Eggs, Large (12 ct, $8.19) | $0.682 | $0.355 | $4.26 | +108% |
| No Frills — #7952, 261 Richmond St W, Toronto ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $17.50) | $0.583 | $0.256 | $3.07 | +78% |
| Provigo — #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name Large Size Eggs (30 ct, $10.33) | $0.344 | Nest Laid (as named) | Burnbrae Farms Naturegg NestlaidOmega 3 Large Size 12 Eggs (12 ct, $6.49) | $0.541 | $0.197 | $2.36 | +57% |
| Provigo — #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name Large Size Eggs (30 ct, $10.33) | $0.344 | Free run | President's Choice Free Run Brown Eggs Large (12 ct, $7.17) | $0.598 | $0.253 | $3.04 | +74% |
| Provigo — #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name Large Size Eggs (30 ct, $10.33) | $0.344 | Free range | Burnbrae Farms Naturegg Solar Free Range Eggs, Large (12 ct, $8.19) | $0.682 | $0.338 | $4.06 | +98% |
| Provigo — #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name Large Size Eggs (30 ct, $10.33) | $0.344 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $17.25) | $0.575 | $0.231 | $2.77 | +67% |
| Real Canadian Superstore — #1080, 3050 Argentia Rd, Mississauga ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $6.19) | $0.516 | $0.188 | $2.26 | +58% |
| Real Canadian Superstore — #1080, 3050 Argentia Rd, Mississauga ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Free run | Conestoga Brown Eggs Free Run Omega-3 Size: Large (18 ct, $10.49) | $0.583 | $0.255 | $3.06 | +78% |
| Real Canadian Superstore — #1080, 3050 Argentia Rd, Mississauga ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Free range | Burnbrae Farms Naturegg Solar Free Range Eggs, Large (12 ct, $8.19) | $0.682 | $0.355 | $4.26 | +108% |
| Real Canadian Superstore — #1080, 3050 Argentia Rd, Mississauga ON | No Name Large Size Eggs 12 Pack (12 ct, $3.93) | $0.328 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $16.84) | $0.561 | $0.234 | $2.81 | +71% |
| Real Canadian Superstore — #1508, 3193 Portage Ave, Winnipeg MB | Foremost Large Size Eggs 18 Pack (18 ct, $6.09) | $0.338 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $5.75) | $0.479 | $0.141 | $1.69 | +42% |
| Real Canadian Superstore — #1508, 3193 Portage Ave, Winnipeg MB | Foremost Large Size Eggs 18 Pack (18 ct, $6.09) | $0.338 | Free run | President's Choice Free Run Brown Eggs Large (12 ct, $7.05) | $0.588 | $0.249 | $2.99 | +74% |
| Real Canadian Superstore — #1508, 3193 Portage Ave, Winnipeg MB | Foremost Large Size Eggs 18 Pack (18 ct, $6.09) | $0.338 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $16.99) | $0.566 | $0.228 | $2.74 | +67% |
| Real Canadian Superstore — #1517, 350 SE Marine Dr, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $5.75) | $0.479 | $0.139 | $1.66 | +41% |
| Real Canadian Superstore — #1517, 350 SE Marine Dr, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Free run | President's Choice Free Run Brown Eggs Large (12 ct, $7.08) | $0.590 | $0.249 | $2.99 | +73% |
| Real Canadian Superstore — #1517, 350 SE Marine Dr, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Free range | Country Golden Yolks Country Golden Yolk Large Free Range Eggs (12 ct, $8.03) | $0.669 | $0.328 | $3.94 | +96% |
| Real Canadian Superstore — #1517, 350 SE Marine Dr, Vancouver BC | No Name Large Size Eggs (30 ct, $10.22) | $0.341 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $16.99) | $0.566 | $0.226 | $2.71 | +66% |
| Real Canadian Superstore — #1533, 3806 Albert St, Regina SK | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $5.75) | $0.479 | $0.137 | $1.64 | +40% |
| Real Canadian Superstore — #1533, 3806 Albert St, Regina SK | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Free run | Star Free Run Eggs, Large (18 ct, $8.04) | $0.447 | $0.104 | $1.25 | +30% |
| Real Canadian Superstore — #1533, 3806 Albert St, Regina SK | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Free range | Star Free Bird Free Range Large Eggs (12 ct, $7.79) | $0.649 | $0.307 | $3.68 | +89% |
| Real Canadian Superstore — #1533, 3806 Albert St, Regina SK | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $16.99) | $0.566 | $0.224 | $2.68 | +65% |
| Real Canadian Superstore — #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Nest Laid (as named) | Burnbrae Farms Naturegg Nest Laid White Eggs, Large (12 ct, $5.75) | $0.479 | $0.137 | $1.64 | +40% |
| Real Canadian Superstore — #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Enriched/Comfort/Cozy coop (as named) | Farmers Finest Comfort Coop, Large Eggs (12 ct, $5.57) | $0.464 | $0.122 | $1.46 | +35% |
| Real Canadian Superstore — #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Free run | President's Choice Free Run Brown Eggs Large (12 ct, $7.68) | $0.640 | $0.297 | $3.57 | +87% |
| Real Canadian Superstore — #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Free range | Farmers Finest Free Range, Large Eggs (12 ct, $7.03) | $0.586 | $0.243 | $2.92 | +71% |
| Real Canadian Superstore — #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name Large Size Eggs (30 ct, $10.28) | $0.343 | Organic | PC Organics Free-Range Large Brown Eggs, Club Pack (30 Count) (30 ct, $16.99) | $0.566 | $0.224 | $2.68 | +65% |
| Save-On-Foods — #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Free run | Rabbit River Rabbit River Farms - Free Run Dark Yolk Large White Eggs (18 ct, $10.59) | $0.588 | $0.235 | $2.82 | +67% |
| Save-On-Foods — #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Free range | Western Family Western Family - Free Range Brown Eggs, Large (12 ct, $7.85) | $0.654 | $0.301 | $3.61 | +85% |
| Save-On-Foods — #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Organic | Only Goodness ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | $0.384 | $4.61 | +109% |
| Save-On-Foods — #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Free run | Rabbit River Rabbit River Farms - Free Run Dark Yolk Large White Eggs (18 ct, $10.59) | $0.588 | $0.235 | $2.82 | +67% |
| Save-On-Foods — #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Free range | Western Family Western Family - Free Range Brown Eggs, Large (12 ct, $7.85) | $0.654 | $0.301 | $3.61 | +85% |
| Save-On-Foods — #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Organic | Only Goodness ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | $0.384 | $4.61 | +109% |
| Save-On-Foods — #4415 St James, 850 St James St, Winnipeg MB | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Free run | Vita VITA - Free Run Eggs - Large (18 ct, $8.99) | $0.499 | $0.146 | $1.75 | +41% |
| Save-On-Foods — #4415 St James, 850 St James St, Winnipeg MB | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Organic | Vita VITA - Vita Organic Large Eggs (18 ct, $11.25) | $0.625 | $0.272 | $3.26 | +77% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Enriched/Comfort/Cozy coop (as named) | Farmer's Finest Farmer's Finest - Comfort Coop Large Eggs White (12 ct, $5.69) | $0.474 | $0.121 | $1.45 | +34% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Free run | Rabbit River Rabbit River Farms - Free Run Dark Yolk Large White Eggs (18 ct, $10.59) | $0.588 | $0.235 | $2.82 | +67% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Free range | Farmer's Finest Farmer's Finest - Free Range Large Eggs Brown (12 ct, $7.85) | $0.654 | $0.301 | $3.61 | +85% |
| Save-On-Foods — #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family Western Family - Large White Eggs Cello (30 ct, $10.60) | $0.353 | Organic | Only Goodness ONLY GOODNESS - Organic Large Brown Eggs (12 ct, $8.85) | $0.737 | $0.384 | $4.61 | +109% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Canadian Harvest Canadian Harvest Brown Eggs Large 12 Count (12 ct, $3.75) | $0.312 | Nest Laid (as named) | Burnbrae Farms Burnbrae Farms Nestlaid Eggs Large 12 Count (12 ct, $5.79) | $0.482 | $0.170 | $2.04 | +54% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Canadian Harvest Canadian Harvest Brown Eggs Large 12 Count (12 ct, $3.75) | $0.312 | Enriched/Comfort/Cozy coop (as named) | Compliments Compliments Cozy Coop Eggs Large 12 Count (12 ct, $5.49) | $0.458 | $0.145 | $1.74 | +46% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Canadian Harvest Canadian Harvest Brown Eggs Large 12 Count (12 ct, $3.75) | $0.312 | Free run | Nature's Farm Nature's Farm Eggs Omega-3 Free Run Large 30 Count (30 ct, $13.19) | $0.440 | $0.127 | $1.53 | +41% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Canadian Harvest Canadian Harvest Brown Eggs Large 12 Count (12 ct, $3.75) | $0.312 | Free range | Burnbrae Farms Burnbrae Farms Naturegg Eggs Free Range Large 12 Count (12 ct, $7.39) | $0.616 | $0.303 | $3.64 | +97% |
| Voilà — online; no postal code set ('Default Region 1', DEF_REG01) | Canadian Harvest Canadian Harvest Brown Eggs Large 12 Count (12 ct, $3.75) | $0.312 | Organic | Nature's Farm Natures Farm Organic Omega 3 Eggs Large 12 Count (12 ct, $7.59) | $0.632 | $0.320 | $3.84 | +102% |
| Walmart — store 1061 (page postal code L5V 2N6, Mississauga ON) | Great Value Great Value Large 12 Eggs (12 ct, $3.93) | $0.328 | Free run | Gold Egg GoldEgg Free Run Large White 30 Eggs (30 ct, $14.98) | $0.499 | $0.172 | $2.06 | +52% |
| Walmart — store 1061 (page postal code L5V 2N6, Mississauga ON) | Great Value Great Value Large 12 Eggs (12 ct, $3.93) | $0.328 | Organic | Great Value Great Value Organic Free Run Large Brown 12 Eggs (12 ct, $7.88) | $0.657 | $0.329 | $3.95 | +101% |

### 4b. Summary across stores (cheapest-vs-cheapest premium, regular-price basis)

| Claim | Stores compared | Min premium $/egg | Median premium $/egg | Max premium $/egg | Median per dozen |
|---|---|---|---|---|---|
| Nest Laid (as named) | 14 | $0.130 | $0.140 | $0.275 | $1.68 |
| Free run | 22 | $0.104 | $0.244 | $0.348 | $2.93 |
| Free range | 17 | $0.243 | $0.308 | $0.433 | $3.70 |
| Organic | 19 | $0.224 | $0.272 | $0.384 | $3.26 |
| Enriched/Comfort/Cozy coop (as named) | 4 | $0.121 | $0.122 | $0.145 | $1.46 |


## 5. Statistics Canada — average retail price, "Eggs, 1 dozen" (table 18-10-0245-01), monthly, January 2022 to latest

Source: Statistics Canada, Table 18-10-0245-01 "Monthly average retail prices for selected products". Full-table CSV `https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip`, opened 3 Oct 2026 04:05 UTC. Metadata via WDS `getCubeMetadata`: cube end date 2026-07-01, release time 2026-09-02T08:30. **July 2026 is the latest month published.** Table page: https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810024501 .

StatCan's table note 1 (verbatim): "Average price estimates for these products are derived using transaction data from Canadian grocery retailers. The composition of a given product category may change over time due to evolving consumer purchasing patterns and product availability. Therefore, users should exercise caution when comparing average prices over time as average prices may not be fully comparable from one month to another and should not be used as a representative measure of pure price change through time." Note 5 (verbatim, excerpt): "With the release of data for the January 2024 reference month, this table has been updated to incorporate data from additional grocery retailers … Users should continue to exercise caution when comparing average prices over time and when interpreting the 1-month change for January 2024 and the 12-month change for the next 12 months."

### 5a. Changes

| Geography | Vector | Jul 2021 | Jan 2022 | Jul 2024 | Jul 2025 | Jul 2026 (latest) | 1-yr | 2-yr | 5-yr | Peak Jan 2022–Jul 2026 (month) |
|---|---|---|---|---|---|---|---|---|---|---|
| Canada | v1353834290 | $3.82 | $3.91 | $4.74 | $4.95 | $4.95 | +0.0% | +4.4% | +29.6% | $4.95 (2026-07) |
| Newfoundland and Labrador | v1159446994 | $3.59 | $4.26 | $5.21 | $5.50 | $5.53 | +0.5% | +6.1% | +54.0% | $5.53 (2026-07) |
| Prince Edward Island | v1159447034 | $3.77 | $4.30 | $5.22 | $5.43 | $5.32 | -2.0% | +1.9% | +41.1% | $5.43 (2025-08) |
| Nova Scotia | v1159447074 | $3.66 | $4.27 | $5.23 | $5.46 | $5.42 | -0.7% | +3.6% | +48.1% | $5.46 (2025-08) |
| New Brunswick | v1159447114 | $3.74 | $4.07 | $4.95 | $5.35 | $5.30 | -0.9% | +7.1% | +41.7% | $5.35 (2025-07) |
| Quebec | v1159447154 | $3.71 | $3.10 | $4.32 | $4.66 | $4.43 | -4.9% | +2.5% | +19.4% | $4.67 (2025-05) |
| Ontario | v1159447194 | $3.91 | $4.11 | $4.73 | $4.85 | $5.00 | +3.1% | +5.7% | +27.9% | $5.00 (2026-07) |
| Manitoba | v1159447234 | $3.26 | $3.98 | $4.61 | $4.71 | $4.71 | +0.0% | +2.2% | +44.5% | $4.77 (2026-05) |
| Saskatchewan | v1159447274 | $3.39 | $4.00 | $4.60 | $4.73 | $4.77 | +0.8% | +3.7% | +40.7% | $4.77 (2026-07) |
| Alberta | v1159447314 | $3.60 | $4.18 | $4.95 | $5.10 | $5.20 | +2.0% | +5.1% | +44.4% | $5.20 (2026-07) |
| British Columbia | v1159447354 | $4.29 | $4.74 | $5.34 | $5.56 | $5.75 | +3.4% | +7.7% | +34.0% | $5.75 (2026-07) |

### 5b. Monthly values, January 2022 – July 2026 (dollars per dozen)

| Month | CAN | NL | PE | NS | NB | QC | ON | MB | SK | AB | BC |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 2022-01 | $3.91 | $4.26 | $4.30 | $4.27 | $4.07 | $3.10 | $4.11 | $3.98 | $4.00 | $4.18 | $4.74 |
| 2022-02 | $4.07 | $4.24 | $4.26 | $4.25 | $4.16 | $3.80 | $4.09 | $3.62 | $3.70 | $3.96 | $4.58 |
| 2022-03 | $4.19 | $4.28 | $4.32 | $4.29 | $4.20 | $3.92 | $4.24 | $3.81 | $3.86 | $4.10 | $4.70 |
| 2022-04 | $4.04 | $4.75 | $4.78 | $4.82 | $4.38 | $3.10 | $4.33 | $4.00 | $3.95 | $4.27 | $4.86 |
| 2022-05 | $4.24 | $4.85 | $4.84 | $4.87 | $4.36 | $3.51 | $4.35 | $4.12 | $4.11 | $4.42 | $4.92 |
| 2022-06 | $4.19 | $4.53 | $4.59 | $4.58 | $4.42 | $3.42 | $4.37 | $4.01 | $4.05 | $4.38 | $4.88 |
| 2022-07 | $4.29 | $5.02 | $4.51 | $4.42 | $4.23 | $3.77 | $4.46 | $3.88 | $3.97 | $4.28 | $4.82 |
| 2022-08 | $4.39 | $5.04 | $4.51 | $4.37 | $4.30 | $4.01 | $4.53 | $3.84 | $3.95 | $4.28 | $4.84 |
| 2022-09 | $4.68 | $5.09 | $5.07 | $5.16 | $5.00 | $4.45 | $4.58 | $4.21 | $4.29 | $4.65 | $5.17 |
| 2022-10 | $4.52 | $5.12 | $4.93 | $4.97 | $4.53 | $3.76 | $4.69 | $4.25 | $4.31 | $4.67 | $5.13 |
| 2022-11 | $4.59 | $4.56 | $4.62 | $4.65 | $4.59 | $4.24 | $4.57 | $4.30 | $4.40 | $4.79 | $5.21 |
| 2022-12 | $4.36 | $4.79 | $4.77 | $5.04 | $4.57 | $3.36 | $4.56 | $4.36 | $4.44 | $4.82 | $5.39 |
| 2023-01 | $4.38 | $4.43 | $4.52 | $4.57 | $4.30 | $3.52 | $4.62 | $4.37 | $4.45 | $4.81 | $5.22 |
| 2023-02 | $4.52 | $4.79 | $4.88 | $4.90 | $4.68 | $3.86 | $4.64 | $4.23 | $4.34 | $4.67 | $5.13 |
| 2023-03 | $4.45 | $4.20 | $3.97 | $3.86 | $3.87 | $3.94 | $4.66 | $4.19 | $4.29 | $4.74 | $5.21 |
| 2023-04 | $4.50 | $5.01 | $5.16 | $5.16 | $4.75 | $3.68 | $4.67 | $4.33 | $4.41 | $4.76 | $5.26 |
| 2023-05 | $4.38 | $5.06 | $5.20 | $5.21 | $4.70 | $3.50 | $4.55 | $4.32 | $4.40 | $4.81 | $5.30 |
| 2023-06 | $4.57 | $5.09 | $5.22 | $5.26 | $4.87 | $3.84 | $4.67 | $4.30 | $4.43 | $4.79 | $5.30 |
| 2023-07 | $4.71 | $5.16 | $4.79 | $4.81 | $4.58 | $4.26 | $4.75 | $4.44 | $4.49 | $4.87 | $5.37 |
| 2023-08 | $4.62 | $4.87 | $4.83 | $4.80 | $4.50 | $3.87 | $4.75 | $4.57 | $4.55 | $4.90 | $5.40 |
| 2023-09 | $4.48 | $5.19 | $4.42 | $4.41 | $4.15 | $3.77 | $4.52 | $4.57 | $4.58 | $4.94 | $5.40 |
| 2023-10 | $4.47 | $5.19 | $5.29 | $5.34 | $4.83 | $3.43 | $4.80 | $4.59 | $4.58 | $4.94 | $5.43 |
| 2023-11 | $4.65 | $5.12 | $5.07 | $5.15 | $4.69 | $3.89 | $4.74 | $4.57 | $4.57 | $4.96 | $5.46 |
| 2023-12 | $4.41 | $5.12 | $5.03 | $5.14 | $4.52 | $3.38 | $4.85 | $4.60 | $4.61 | $4.99 | $5.45 |
| 2024-01 | $4.46 | $5.14 | $4.91 | $5.03 | $4.79 | $3.70 | $4.66 | $4.55 | $4.55 | $4.89 | $5.24 |
| 2024-02 | $4.43 | $5.05 | $4.95 | $5.01 | $4.59 | $3.66 | $4.70 | $4.57 | $4.56 | $4.92 | $5.28 |
| 2024-03 | $4.26 | $4.61 | $4.51 | $4.54 | $4.27 | $3.66 | $4.53 | $3.99 | $4.05 | $4.47 | $4.89 |
| 2024-04 | $4.61 | $4.86 | $4.98 | $4.98 | $4.63 | $3.98 | $4.76 | $4.62 | $4.64 | $4.93 | $5.34 |
| 2024-05 | $4.45 | $5.09 | $5.08 | $5.10 | $4.56 | $3.59 | $4.79 | $4.62 | $4.62 | $4.96 | $5.37 |
| 2024-06 | $4.42 | $5.33 | $5.28 | $5.14 | $5.21 | $3.66 | $4.53 | $4.62 | $4.62 | $4.97 | $5.35 |
| 2024-07 | $4.74 | $5.21 | $5.22 | $5.23 | $4.95 | $4.32 | $4.73 | $4.61 | $4.60 | $4.95 | $5.34 |
| 2024-08 | $4.71 | $5.27 | $5.28 | $5.33 | $4.83 | $4.11 | $4.82 | $4.65 | $4.64 | $4.96 | $5.42 |
| 2024-09 | $4.87 | $5.22 | $5.15 | $5.24 | $5.13 | $4.52 | $4.85 | $4.64 | $4.63 | $4.99 | $5.44 |
| 2024-10 | $4.66 | $5.18 | $5.13 | $5.23 | $5.08 | $3.90 | $4.87 | $4.69 | $4.71 | $5.04 | $5.52 |
| 2024-11 | $4.85 | $5.39 | $5.36 | $5.38 | $5.20 | $4.45 | $4.81 | $4.72 | $4.72 | $5.08 | $5.54 |
| 2024-12 | $4.75 | $5.35 | $5.32 | $5.36 | $5.07 | $4.24 | $4.80 | $4.69 | $4.69 | $5.05 | $5.47 |
| 2025-01 | $4.89 | $5.41 | $5.34 | $5.42 | $5.26 | $4.51 | $4.87 | $4.75 | $4.72 | $5.11 | $5.52 |
| 2025-02 | $4.91 | $5.33 | $5.31 | $5.39 | $5.27 | $4.64 | $4.83 | $4.74 | $4.71 | $5.10 | $5.48 |
| 2025-03 | $4.92 | $5.42 | $5.37 | $5.41 | $5.32 | $4.64 | $4.83 | $4.72 | $4.74 | $5.10 | $5.51 |
| 2025-04 | $4.92 | $5.44 | $5.37 | $5.45 | $5.33 | $4.64 | $4.82 | $4.70 | $4.70 | $5.08 | $5.51 |
| 2025-05 | $4.94 | $5.43 | $5.37 | $5.41 | $5.31 | $4.67 | $4.83 | $4.72 | $4.73 | $5.12 | $5.58 |
| 2025-06 | $4.94 | $5.47 | $5.41 | $5.46 | $5.33 | $4.66 | $4.84 | $4.72 | $4.72 | $5.12 | $5.57 |
| 2025-07 | $4.95 | $5.50 | $5.43 | $5.46 | $5.35 | $4.66 | $4.85 | $4.71 | $4.73 | $5.10 | $5.56 |
| 2025-08 | $4.81 | $5.50 | $5.43 | $5.46 | $5.33 | $4.25 | $4.85 | $4.75 | $4.75 | $5.13 | $5.61 |
| 2025-09 | $4.89 | $5.36 | $5.35 | $5.42 | $5.22 | $4.41 | $4.89 | $4.74 | $4.76 | $5.13 | $5.60 |
| 2025-10 | $4.76 | $5.42 | $5.38 | $5.43 | $5.25 | $4.01 | $4.94 | $4.76 | $4.77 | $5.16 | $5.61 |
| 2025-11 | $4.74 | $5.33 | $5.26 | $5.31 | $5.18 | $4.07 | $4.93 | $4.62 | $4.62 | $5.04 | $5.50 |
| 2025-12 | $4.70 | $5.22 | $5.12 | $5.25 | $5.09 | $3.98 | $4.98 | $4.65 | $4.64 | $5.06 | $5.49 |
| 2026-01 | $4.74 | $5.38 | $5.25 | $5.33 | $5.17 | $4.07 | $4.93 | $4.66 | $4.66 | $5.08 | $5.53 |
| 2026-02 | $4.81 | $5.41 | $5.26 | $5.35 | $5.14 | $4.25 | $4.94 | $4.66 | $4.66 | $5.08 | $5.54 |
| 2026-03 | $4.77 | $5.34 | $5.20 | $5.30 | $5.15 | $4.20 | $4.94 | $4.66 | $4.67 | $5.07 | $5.49 |
| 2026-04 | $4.80 | $5.39 | $5.19 | $5.35 | $5.20 | $4.12 | $5.00 | $4.72 | $4.70 | $5.14 | $5.58 |
| 2026-05 | $4.85 | $5.45 | $5.29 | $5.39 | $5.26 | $4.19 | $5.00 | $4.77 | $4.76 | $5.18 | $5.69 |
| 2026-06 | $4.88 | $5.47 | $5.29 | $5.39 | $5.27 | $4.29 | $5.00 | $4.70 | $4.73 | $5.11 | $5.63 |
| 2026-07 | $4.95 | $5.53 | $5.32 | $5.42 | $5.30 | $4.43 | $5.00 | $4.71 | $4.77 | $5.20 | $5.75 |

## 6. Statistics Canada — Consumer Price Index, Eggs (table 18-10-0004-01), 2-year and 5-year changes

Source: Table 18-10-0004-01 "Consumer Price Index, monthly, not seasonally adjusted" (2002=100). Full-table CSV `https://www150.statcan.gc.ca/n1/tbl/csv/18100004-eng.zip`, opened 3 Oct 2026 04:05 UTC. Cube end date 2026-08-01, release 2026-09-14T08:30. Latest month: August 2026. Table page: https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000401 .

| Geography | Series | Vector | Aug 2021 | Aug 2024 | Aug 2025 | Aug 2026 (latest) | 1-yr | 2-yr | 5-yr |
|---|---|---|---|---|---|---|---|---|---|
| Canada | Eggs | v41690999 | 186.1 | 221.1 | 229.2 | 223.7 | -2.4% | +1.2% | +20.2% |
| Canada | Food purchased from stores | v41690975 | 154.7 | 187.7 | 194.2 | 199.6 | +2.8% | +6.3% | +29.0% |
| Canada | All-items | v41690973 | 142.6 | 161.8 | 164.8 | 169.8 | +3.0% | +4.9% | +19.1% |
| Newfoundland and Labrador | Eggs | v41691261 | 184.2 | 235.3 | 242.5 | 241.2 | -0.5% | +2.5% | +30.9% |
| Prince Edward Island | Eggs | v41691396 | 219.8 | 268.0 | 270.8 | 264.9 | -2.2% | -1.2% | +20.5% |
| Nova Scotia | Eggs | v41691530 | 198.5 | 238.6 | 242.7 | 238.3 | -1.8% | -0.1% | +20.1% |
| New Brunswick | Eggs | v41691665 | 207.3 | 243.4 | 248.2 | 244.6 | -1.5% | +0.5% | +18.0% |
| Quebec | Eggs | v41691800 | 182.7 | 207.5 | 221.4 | 207.3 | -6.4% | -0.1% | +13.5% |
| Ontario | Eggs | v41691936 | 194.6 | 232.3 | 241.8 | 238.4 | -1.4% | +2.6% | +22.5% |
| Manitoba | Eggs | v41692072 | 204.1 | 242.6 | 246.8 | 239.2 | -3.1% | -1.4% | +17.2% |
| Saskatchewan | Eggs | v41692208 | 200.5 | 234.8 | 238.9 | 231.7 | -3.0% | -1.3% | +15.6% |
| Alberta | Eggs | v41692344 | 193.9 | 237.8 | 242.4 | 238.5 | -1.6% | +0.3% | +23.0% |
| British Columbia | Eggs | v41692479 | 157.2 | 187.9 | 192.4 | 190.2 | -1.1% | +1.2% | +21.0% |

For a same-month comparison with table 18-10-0245 (latest July 2026), CPI Eggs, Canada, was: July 2021 179.6; July 2024 223.9; July 2025 229.3; July 2026 226.4. That is +1.1% over 2 years and +26.1% over 5 years to July 2026.

<details><summary>CPI Eggs, Canada, monthly Jan 2022 – Aug 2026</summary>

| Month | CPI Eggs, Canada (2002=100) |
|---|---|
| 2022-01 | 183.7 |
| 2022-02 | 185.1 |
| 2022-03 | 188.8 |
| 2022-04 | 194.0 |
| 2022-05 | 194.8 |
| 2022-06 | 194.0 |
| 2022-07 | 207.9 |
| 2022-08 | 206.3 |
| 2022-09 | 205.9 |
| 2022-10 | 210.7 |
| 2022-11 | 213.8 |
| 2022-12 | 209.0 |
| 2023-01 | 212.4 |
| 2023-02 | 210.3 |
| 2023-03 | 211.1 |
| 2023-04 | 210.6 |
| 2023-05 | 210.7 |
| 2023-06 | 211.2 |
| 2023-07 | 214.8 |
| 2023-08 | 213.8 |
| 2023-09 | 212.2 |
| 2023-10 | 214.8 |
| 2023-11 | 217.6 |
| 2023-12 | 215.4 |
| 2024-01 | 215.1 |
| 2024-02 | 215.7 |
| 2024-03 | 215.7 |
| 2024-04 | 220.2 |
| 2024-05 | 218.6 |
| 2024-06 | 221.2 |
| 2024-07 | 223.9 |
| 2024-08 | 221.1 |
| 2024-09 | 222.9 |
| 2024-10 | 219.7 |
| 2024-11 | 226.2 |
| 2024-12 | 226.2 |
| 2025-01 | 225.9 |
| 2025-02 | 225.4 |
| 2025-03 | 226.9 |
| 2025-04 | 228.8 |
| 2025-05 | 229.1 |
| 2025-06 | 229.4 |
| 2025-07 | 229.3 |
| 2025-08 | 229.2 |
| 2025-09 | 227.8 |
| 2025-10 | 226.7 |
| 2025-11 | 221.9 |
| 2025-12 | 223.8 |
| 2026-01 | 222.9 |
| 2026-02 | 222.9 |
| 2026-03 | 225.1 |
| 2026-04 | 223.4 |
| 2026-05 | 222.8 |
| 2026-06 | 224.3 |
| 2026-07 | 226.4 |
| 2026-08 | 223.7 |

</details>

## 7. Farm-gate (producer) prices, 2022–2026 — as published by egg boards

### 7a. British Columbia Egg Marketing Board — pricing orders (primary)

Index page: https://bcegg.com/pricing-announcements/ (opened 3 Oct 2026 04:14 UTC). It lists announcements dated October 2026, April 2026, November 2025, March 2025, February 2024, November 2023, July 2023, January 2023, June 2022 and March 2022. Each PDF below was opened 3 Oct 2026 04:14 UTC.

Wording common to each order (verbatim, Order 02/2026): "British Columbia Regulation 173/67 Sections 36 and 37 and British Columbia Egg Marketing Board Consolidated Order Part X.1., provide the pricing authority for eggs produced in British Columbia. By Board Order No. 02/2026 effective October 4, 2026 and until further notice, the minimum prices paid per dozen of eggs, by grade, EXW the farm, by an operator of an egg grading station shall be:" The table is headed "White", "$/dozen" and "Market" (2025–2026 orders) or "Classic" (2022–Mar 2025 orders).

| Order | Approved | Effective | Grade A Large old → new ($/dozen) | A Medium old → new | A Small old → new | Column label | PDF |
|---|---|---|---|---|---|---|---|
| 01/2022 | 14th DAY OF February, 2022 | March 6, 2022 | 2.67 → 2.85 | 2.38 → 2.56 | 2.06 → 2.24 | Classic | https://bcegg.com/wp-content/uploads/2022/02/Pricing-Announcement_Classic_Week-11-2022.pdf |
| 02/2022 | 26th DAY OF MAY, 2022 | June 12, 2022 | 2.85 → 3.03 | 2.56 → 2.73 | 2.24 → 2.37 | Classic | https://bcegg.com/wp-content/uploads/2022/05/Pricing-Announcement-Classic-Week-25-2022.pdf |
| 01/2023 | 23rd DAY OF December, 2022 | January 29, 2023 | 3.03 → 2.91 | 2.73 → 2.61 | 2.37 → 2.26 | Classic | https://bcegg.com/wp-content/uploads/2023/01/Pricing-Announcement_Classic_Week-5-2023.pdf |
| 02/2023 | 16th DAY OF June, 2023 | July 16, 2023 | 2.91 → 3.03 | 2.61 → 2.73 | 2.26 → 2.38 | Classic | https://bcegg.com/wp-content/uploads/2023/06/Pricing-Announcement_Classic_Week-29-2023.pdf |
| 03/2023 | 10th DAY OF October, 2023 | November 5, 2023 | 3.03 → 3.09 | 2.73 → 2.79 | 2.38 → 2.44 | Classic | https://bcegg.com/wp-content/uploads/2023/10/Pricing-Announcement_Classic_Week-45-2023.pdf |
| 01/2024 | 29th DAY OF January, 2024 | February 25, 2024 | 3.09 → 3.16 | 2.79 → 2.85 | 2.44 → 2.50 | Classic | https://bcegg.com/wp-content/uploads/2024/01/Pricing-Announcement_Classic_Week-09-2024.pdf |
| 01/2025 | 24th DAY OF February, 2025 | March 23, 2025 | 3.16 → 3.16 | 2.85 → 2.85 | 2.50 → 2.50 | Classic | https://bcegg.com/wp-content/uploads/2025/02/Pricing-Announcement_Classic_Week-13-2025.pdf |
| 02/2025 | 26th DAY OF SEPTEMBER, 2025 | November 2, 2025 | 3.16 → 2.98 | 2.85 → 2.67 | 2.50 → 2.30 | Market | https://bcegg.com/wp-content/uploads/2025/09/Pricing-Announcement_Market_Week-45-2025.pdf |
| 01/2026 | 19th DAY OF MARCH, 2026 | April 19, 2026 | 2.98 → 3.02 | 2.67 → 2.71 | 2.30 → 2.35 | Market | https://bcegg.com/wp-content/uploads/2026/03/Pricing-Announcement_Market_Week-17-2026.pdf |
| 02/2026 | 4th DAY OF SEPTEMBER, 2026 | October 4, 2026 | 3.02 → 3.07 | 2.71 → 2.76 | 2.35 → 2.40 | Market | https://bcegg.com/wp-content/uploads/2026/09/Pricing-Announcement_Market_Week-41-2026.pdf |

Reading the BC orders: Grade A Large (white, minimum paid by a grading station, EXW farm) was $2.67 before 6 Mar 2022. It then went to $2.85 (6 Mar 2022), $3.03 (12 Jun 2022), $2.91 (29 Jan 2023), $3.03 (16 Jul 2023), $3.09 (5 Nov 2023) and $3.16 (25 Feb 2024). It was unchanged at $3.16 (23 Mar 2025), then $2.98 (2 Nov 2025), $3.02 (19 Apr 2026) and $3.07 (4 Oct 2026). Change 2024 → 2026: from $3.16 (2024 level) to $3.07 effective 4 Oct 2026 = −$0.09 (−2.8%).

### 7b. Egg Farmers of Alberta — "Egg Prices" page (primary)

https://eggs.ab.ca/healthy-farms/supply-management/egg-prices/ (opened 3 Oct 2026 04:15 UTC). Verbatim: "Egg Prices Effective Date: November 2, 2025" — "A – Extra Large $2.920; A – Large $2.920; A – Medium $2.610; A – Small $2.250; A – Nest Run $2.747; A – Pee Wee $0.280; B $0.760; C $0.160". Also: "Note: From the minimum paying price, graders can only deduct charges as authorized by the EFA Board of Directors."

| Year | "Average Producer Prices", Alberta, Grade A Large ($/dozen) (verbatim from page) |
|---|---|
| 2025 | 3.055 |
| 2024 | 3.080 |
| 2023 | 2.918 |
| 2022 | 2.857 |
| 2021 | 2.538 |
| 2020 | 2.364 |

### 7c. Egg Farmers of Canada — market information (primary, partial)

https://www.eggfarmers.ca/market-information-tables/ (opened 3 Oct 2026 04:15 UTC) lists "Producer prices — Source: Egg boards — Note: Data are subject to revisions. Prices are effective on the Sunday of the price week." and "Cost of Production — Source: Egg Farmers of Canada". Both tables are embedded Tableau Public views. The CSV export returned 404 (Tableau's bot wall). Only the static preview images could be read (`https://public.tableau.com/static/images/ES/ESPMarketInformationDataExternalv2_17030895092330/EFCProducerPrices-POCPrixauxproducteurs/1.png` and `…/EFCCOP-POCCDP/1.png`, opened 04:15:36 UTC). Their units are "Boxes of 15 Dozens":

- Producer prices, BC column, Grade L: 44.7000 per box of 15 dozen for weeks 202601–202616, then 45.3000 for weeks 202617–202624. ÷ 15 = $2.98 and $3.02 per dozen, which matches the BC orders above.
- Cost of Production, BC column, L: 43.2000 (weeks 202601–04), 43.3500 (05–08), 43.5000 (09–12), 43.6500 (13–16), 44.4000 (17–20), 44.7000 (21–26) per box of 15 dozen = $2.88 to $2.98 per dozen.
- How old the preview images are is not stated. Treat these as a cross-check only.

Retail vs farm-gate, side by side (no margin is implied; grading, packing, transport, wholesale and retail costs sit between the two figures): BC producer minimum for Grade A Large, $3.02/dozen (in effect 19 Apr – 3 Oct 2026). StatCan BC average retail price, "Eggs, 1 dozen", July 2026: $5.75.

## 8. Master listing — every shell-egg listing captured (retailer's own channel, 3 Oct 2026 UTC)

Columns: banner; store/region; brand (retailer's brand field, or blank); product name verbatim; grade as stated; size as named; count; colour as named; housing claim as named; regular price; sale price and end date; shelf $/egg; capture time (UTC); source. Loblaw URLs are the retailer product-page paths returned by the API. The data was read from the API (opened), not the HTML page.

| # | Banner | Store / region | Brand | Product name (verbatim) | Grade | Size | Count | Colour | Housing claim (name) | Regular | Sale (ends) | $/egg shelf | Captured UTC | URL |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.78 | — | $0.359 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/large-size-eggs/p/21435777001_EA |
| 2 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.91 | — | $0.409 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 3 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.98 | — | $0.415 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 4 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Maritime | White Eggs, Large | not stated in listing | Large | 18 | white | None stated | $8.17 | — | $0.454 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/white-eggs-large/p/20830377001_EA |
| 5 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.49 | — | $0.458 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 6 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $5.87 | $5.50 (ends 2026-10-14) | $0.458 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 7 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $5.87 | $5.50 (ends 2026-10-14) | $0.458 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 8 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $5.67 | — | $0.472 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 9 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Maritime | Maritime Pride Jumbo Brown Eggs Jumbo Size | not stated in listing | Jumbo | 12 | brown | None stated | $5.69 | — | $0.474 | 2026-10-03T04:06:38Z | https://www.atlanticsuperstore.ca/maritime-pride-jumbo-brown-eggs-jumbo-size/p/20827698001_EA |
| 10 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Maritime | White Eggs Extra Large, 18 Count | not stated in listing | Extra Large | 18 | white | None stated | $8.68 | — | $0.482 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/white-eggs-extra-large-18-count/p/20827632001_EA |
| 11 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Maritime | White Eggs, Jumbo | not stated in listing | Jumbo | 12 | white | None stated | $5.87 | — | $0.489 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/white-eggs-jumbo/p/20828241001_EA |
| 12 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $6.37 | $6.00 (ends 2026-10-14) | $0.500 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 13 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Burnbrae Farms | Naturegg NestlaidOmega 3 Large Size 12 Eggs | not stated in listing | Large | 12 | not stated | Nest Laid (as named) + Omega-3 (name) | $6.75 | $6.25 (ends 2026-10-14) | $0.521 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/naturegg-nestlaidomega-3-large-size-12-eggs/p/21069384001_EA |
| 14 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Nutri-Egg | Free Run Hens Large White Eggs | not stated in listing | Large | 12 | white | Free run | $6.37 | — | $0.531 | 2026-10-03T04:19:13Z | https://www.atlanticsuperstore.ca/free-run-hens-large-white-eggs/p/21023768001_EA |
| 15 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Rowe Farms | Green Valley Omega 3 Eggs, Large | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.49 | — | $0.541 | 2026-10-03T04:06:38Z | https://www.atlanticsuperstore.ca/green-valley-omega-3-eggs-large/p/20974459001_EA |
| 16 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Nutri-Egg | Large Brown Eggs | not stated in listing | Large | 6 | brown | None stated | $3.30 | — | $0.550 | 2026-10-03T04:06:38Z | https://www.atlanticsuperstore.ca/large-brown-eggs/p/21341900001_EA |
| 17 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Nutri-Egg | Free Run Hens Large White Eggs | not stated in listing | Large | 6 | white | Free run | $3.30 | — | $0.550 | 2026-10-03T04:19:13Z | https://www.atlanticsuperstore.ca/free-run-hens-large-white-eggs/p/21341954001_EA |
| 18 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Nutri-Egg | Omega 3 Large White Eggs | not stated in listing | Large | 6 | white | None stated + Omega-3 (name) | $3.50 | — | $0.583 | 2026-10-03T04:19:13Z | https://www.atlanticsuperstore.ca/omega-3-large-white-eggs/p/21342062001_EA |
| 19 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Rowe Farms | Green Valley Eggs Size Large Free Run Brown | not stated in listing | Large | 12 | brown | Free run | $7.04 | — | $0.587 | 2026-10-03T04:06:38Z | https://www.atlanticsuperstore.ca/green-valley-eggs-size-large-free-run-brown/p/20821562001_EA |
| 20 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Maritime | Eggs, Large White Large Size Omega 3 | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.05 | — | $0.588 | 2026-10-03T04:19:13Z | https://www.atlanticsuperstore.ca/eggs-large-white-large-size-omega-3/p/20827214001_EA |
| 21 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Burnbrae Farms | Naturegg Omega Plus Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Omega-3 (name); Solar (name) | $7.97 | $7.25 (ends 2026-10-14) | $0.604 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/naturegg-omega-plus-solar-free-range-eggs-large/p/21565655001_EA |
| 22 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Solar (name) | $7.97 | $7.25 (ends 2026-10-14) | $0.604 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| 23 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.55 | — | $0.629 | 2026-10-03T04:06:38Z | https://www.atlanticsuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 24 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:13:02Z | https://www.atlanticsuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 25 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Coldspring Farm | Eggs, Maritime Pride Free Range Size Large 12 | not stated in listing | Large | 12 | not stated | Free range | $8.21 | — | $0.684 | 2026-10-03T04:06:38Z | https://www.atlanticsuperstore.ca/eggs-maritime-pride-free-range-size-large-12/p/21340326001_EA |
| 26 | Atlantic Superstore | #0354, 6141 Young St, Halifax NS | Green Valley | Brown Eggs Free Range Farm Large | not stated in listing | Large | 12 | brown | Free range | $8.29 | — | $0.691 | 2026-10-03T04:06:38Z | https://www.atlanticsuperstore.ca/brown-eggs-free-range-farm-large/p/21185920_EA |
| 27 | Costco Same-Day | postal L5V 2N6, retailer location 40595 (Mississauga ON) | Kirkland Signature | Kirkland Signature Free Run Large Eggs | not stated in listing | Large | 24 | not stated | Free run | $10.20 | — | $0.425 | 2026-10-03T04:12:36Z | https://sameday.costco.ca/store/costco-canada/products/63993483-ks-gros-oeufs-en-libert-paquet-de-24?zipcode=L5V2N6&utm_source=nav |
| 28 | Giant Tiger | online listing, province tag(s): ; tag in_store_only:true; no store selected | Nutri | Nutri Large White Eggs, 18-Pack | not stated in listing | Large | 18 | white | None stated | $3.39 | — | $0.188 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/oeufs-famiale-18 |
| 29 | Giant Tiger | online listing, province tag(s): ; tag in_store_only:true; no store selected | Super Bon-EE | Super Bon-EE Extra Large Eggs, 12-Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $3.97 | — | $0.331 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/super-bon-ee-extra-large-eggs-12-pack |
| 30 | Giant Tiger | online listing, province tag(s): AB,MB,NB,NS,ON,PE,QC,SK; tag in_store_only:true; no store selected | Poultry Farm Laviolette | Large Eggs - 18pk. | not stated in listing | Large | 18 | not stated | None stated | $6.68 | — | $0.371 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/large-eggs-18pk |
| 31 | Giant Tiger | online listing, province tag(s): AB,MB,NB,NS,ON,PE,QC,SK; tag in_store_only:true; no store selected | Gray Ridge Egg Farms | Large Brown Eggs | not stated in listing | Large | not stated | brown | None stated | $6.08 | — | n/a | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/large-brown-eggs |
| 32 | Giant Tiger | online listing, province tag(s): AB,MB,NB,NS,ON,PE,QC,SK; tag in_store_only:true; no store selected | Poultry Farm Laviolette | Jumbo Eggs | not stated in listing | Jumbo | not stated | not stated | None stated | $5.38 | — | n/a | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/jumbo-eggs |
| 33 | Giant Tiger | online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $4.16 | — | $0.347 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack-6 |
| 34 | Giant Tiger | online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Medium Eggs, 30-Pack | not stated in listing | Medium | 30 | white | None stated | $10.50 | — | $0.350 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/2-5doz-burnbrae-m-white-egg |
| 35 | Giant Tiger | online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large White Eggs, 30-Pack | not stated in listing | Large | 30 | white | None stated | $10.99 | — | $0.366 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-white-eggs-30-pack-1 |
| 36 | Giant Tiger | online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Giant Tiger | Best Value Eggs, Large, 12-pack | not stated in listing | Large | 12 | not stated | None stated | $4.89 | — | $0.407 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/12s-best-value-eggs-large |
| 37 | Giant Tiger | online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Gray Ridge Egg Farms | Gray Ridge Egg Farms Extra Large Size Family Pack, 18-Eggs | not stated in listing | Extra Large | 18 | not stated | None stated | $7.97 | — | $0.443 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/prestige-club-pack-large-eggs-18-pack-7 |
| 38 | Giant Tiger | online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Brown Large Eggs - 12pk. | not stated in listing | Large | 12 | brown | None stated | $5.36 | — | $0.447 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-brown-large-eggs-12pk-2 |
| 39 | Giant Tiger | online listing, province tag(s): AB,MB,SK; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Large Eggs - 12pk. | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.13 | — | $0.511 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-omega-3-large-eggs-12pk-5 |
| 40 | Giant Tiger | online listing, province tag(s): AB; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Size Large, 30-Pack | not stated in listing | Large | 30 | white | None stated | $10.18 | — | $0.339 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/2-5doz-burnbrae-lrg-eggs |
| 41 | Giant Tiger | online listing, province tag(s): AB; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $4.14 | — | $0.345 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack |
| 42 | Giant Tiger | online listing, province tag(s): AB; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $4.14 | — | $0.345 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack-7 |
| 43 | Giant Tiger | online listing, province tag(s): AB; tag in_store_only:true; no store selected | Prestige | Prestige Club Pack Large Eggs, 18-Pack | not stated in listing | Large | 18 | not stated | None stated | $7.97 | — | $0.443 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/prestige-club-pack-large-eggs-18-pack-6 |
| 44 | Giant Tiger | online listing, province tag(s): AB; tag in_store_only:true; no store selected | Prestige | Prestige Club Pack Large Eggs, 18-Pack | not stated in listing | Large | 18 | not stated | None stated | $7.97 | — | $0.443 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/prestige-club-pack-large-eggs-18-pack-4 |
| 45 | Giant Tiger | online listing, province tag(s): AB; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Brown Eggs, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.34 | — | $0.445 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-brown-eggs-12-pack-9 |
| 46 | Giant Tiger | online listing, province tag(s): AB; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Brown Eggs, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.34 | — | $0.445 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-brown-eggs-12-pack-8 |
| 47 | Giant Tiger | online listing, province tag(s): AB; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Large Eggs - 12pk. | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.13 | — | $0.511 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-omega-3-large-eggs-12pk-4 |
| 48 | Giant Tiger | online listing, province tag(s): NB,NS,ON,PE,QC; tag in_store_only:true; no store selected | Laviolette | Poultry Farm Laviolette Extra Large Eggs, 12-Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.63 | — | $0.386 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/poultry-farm-laviolette-extra-large-eggs-12-pack |
| 49 | Giant Tiger | online listing, province tag(s): NB; tag in_store_only:true; no store selected | Maritime Pride | Maritime Pride Large White Eggs, 12-Pack | not stated in listing | Large | 12 | white | None stated | $4.97 | — | $0.414 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/maritime-pride-large-white-eggs-12-pack-3 |
| 50 | Giant Tiger | online listing, province tag(s): NB; tag in_store_only:true; no store selected | Maritime Pride | Maritime Pride Large White Eggs, 18-Pack | not stated in listing | Large | 18 | white | None stated | $7.97 | — | $0.443 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/maritime-pride-large-white-eggs-18-pack-1 |
| 51 | Giant Tiger | online listing, province tag(s): NB; tag in_store_only:true; no store selected | Nova Eggs | Nova Brown Eggs, Large, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.67 | — | $0.472 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/nova-brown-eggs-large-12-pack-1 |
| 52 | Giant Tiger | online listing, province tag(s): NS,ON; tag in_store_only:true; no store selected | Nova Eggs | Maritime Pride Large Eggs, 12-pack | not stated in listing | Large | 12 | not stated | None stated | $4.97 | — | $0.414 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/maritime-pride-large-eggs-12-pack-1 |
| 53 | Giant Tiger | online listing, province tag(s): NS,ON; tag in_store_only:true; no store selected | Maritime Pride | Maritime Pride White Eggs, Large, 18-Pack | not stated in listing | Large | 18 | white | None stated | $7.97 | — | $0.443 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/maritime-pride-white-eggs-large-18-pack-2 |
| 54 | Giant Tiger | online listing, province tag(s): NS,ON; tag in_store_only:true; no store selected | Nova Eggs | Nova Eggs Ultra Brown Extra Large Size, 12-Pack | not stated in listing | Extra Large | 12 | brown | None stated | $5.62 | — | $0.468 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/nova-eggs-ultra-brown-extra-large-size-12-pack-1 |
| 55 | Giant Tiger | online listing, province tag(s): NS; tag in_store_only:true; no store selected | Farmer John | Farmer John Eggs, Large, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $4.97 | — | $0.414 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/farmer-john-eggs-large-12-pack-1 |
| 56 | Giant Tiger | online listing, province tag(s): NS; tag in_store_only:true; no store selected | Delong Farms | Delong Farms Large Size Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $4.97 | — | $0.414 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/large-white-eggs-12pk-1 |
| 57 | Giant Tiger | online listing, province tag(s): NS; tag in_store_only:true; no store selected | Delong Farms | Large Brown Eggs, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.62 | — | $0.468 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/large-brown-eggs-12-pack |
| 58 | Giant Tiger | online listing, province tag(s): ON,QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Medium Eggs, 30-Pack | not stated in listing | Medium | 30 | white | None stated | $9.07 | — | $0.302 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-medium-white-eggs-30-pack-2 |
| 59 | Giant Tiger | online listing, province tag(s): ON,QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $3.93 | — | $0.328 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12pk-1 |
| 60 | Giant Tiger | online listing, province tag(s): ON,QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Prestige Club Pack Large Eggs - 18pk. | not stated in listing | Large | 18 | not stated | None stated | $6.88 | — | $0.382 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-prestige-club-pack-large-eggs-18pk-1 |
| 61 | Giant Tiger | online listing, province tag(s): ON,QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Large Eggs, 6-Pack | not stated in listing | Large | 6 | white | None stated | $2.97 | — | $0.495 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-white-large-eggs-6-pack |
| 62 | Giant Tiger | online listing, province tag(s): ON,QC; tag in_store_only:true; no store selected | Giant Tiger | Naturegg Omega 3 Large Eggs - 12pk. | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $5.97 | — | $0.497 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/naturegg-omega-3-large-eggs-12pk-1 |
| 63 | Giant Tiger | online listing, province tag(s): ON,QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Brown Large Eggs - 12pk. | not stated in listing | Large | 12 | brown | None stated | $5.99 | — | $0.499 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-brown-large-eggs-12pk-3 |
| 64 | Giant Tiger | online listing, province tag(s): ON,QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Free Run Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | Free run | $6.99 | — | $0.583 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-free-run-large-eggs-12-pack-4 |
| 65 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Medium Eggs, 30-Pack | not stated in listing | Medium | 30 | white | None stated | $9.07 | — | $0.302 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/t2-30pk-medium-white-eggs-1 |
| 66 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Medium Eggs, 30-Pack | not stated in listing | Medium | 30 | white | None stated | $9.07 | — | $0.302 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/t2-30pk-medium-white-eggs |
| 67 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Medium Eggs, 30-Pack | not stated in listing | Medium | 30 | white | None stated | $9.18 | — | $0.306 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-medium-white-eggs-30-pack-3 |
| 68 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Medium Eggs, 12-Pack | not stated in listing | Medium | 12 | not stated | None stated | $3.73 | — | $0.311 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-medium-white-eggs-12pk-1 |
| 69 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large White Eggs, 30-Pack | not stated in listing | Large | 30 | white | None stated | $9.52 | — | $0.317 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-white-eggs-30-pack-2 |
| 70 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large White Eggs, 30-Pack | not stated in listing | Large | 30 | white | None stated | $9.52 | — | $0.317 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-white-eggs-30-pack |
| 71 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Laviolette Poultry Farm | Large White Eggs - 12pk. | not stated in listing | Large | 12 | white | None stated | $3.93 | — | $0.328 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/large-white-eggs-12pk |
| 72 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $3.93 | — | $0.328 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack-10 |
| 73 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $3.93 | — | $0.328 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-large-eggs-12-pack-1 |
| 74 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $3.93 | — | $0.328 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack-8 |
| 75 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Giant Tiger | Burnbrae Farms Extra Large Eggs, 12-Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.18 | — | $0.348 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-extra-large-eggs-12-pack |
| 76 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Prestige Size Large Family Pack, 18-pack | not stated in listing | Large | 18 | not stated | None stated | $6.88 | — | $0.382 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-prestige-size-large-family-pack-18-pack-1 |
| 77 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Prestige | Burnbrae Farms Prestige Family Pack Eggs, Large, 18-Pack | not stated in listing | Large | 18 | not stated | None stated | $6.88 | — | $0.382 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-prestige-family-pack-eggs-large-18-pack-3 |
| 78 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Prestige | Prestige Club Pack Large Eggs, 18-Pack | not stated in listing | Large | 18 | not stated | None stated | $6.88 | — | $0.382 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/prestige-club-pack-large-eggs-18-pack-5 |
| 79 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Large Eggs, 6-Pack | not stated in listing | Large | 6 | white | None stated | $2.97 | — | $0.495 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-white-large-eggs-6-pack-1 |
| 80 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $5.97 | — | $0.497 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-omega-3-large-eggs-12-pack-1 |
| 81 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $5.97 | — | $0.497 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-omega-3-large-eggs-12pk-7 |
| 82 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Large Eggs - 12pk. | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $5.97 | — | $0.497 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-omega-3-large-eggs-12pk-6 |
| 83 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Brown Eggs, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.99 | — | $0.499 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-brown-eggs-12-pack-6 |
| 84 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Brown Eggs, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.99 | — | $0.499 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-brown-eggs-12-pack-5 |
| 85 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Large Brown Eggs, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.99 | — | $0.499 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-large-brown-eggs-12-pack-1 |
| 86 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Free Run Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | Free run | $6.99 | — | $0.583 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-free-run-large-eggs-12-pack-1 |
| 87 | Giant Tiger | online listing, province tag(s): ON; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Free Run Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | Free run | $7.43 | — | $0.619 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-free-run-large-eggs-12-pack-3 |
| 88 | Giant Tiger | online listing, province tag(s): PE; tag in_store_only:true; no store selected | Maritime Pride | Maritime Pride Large White Eggs, 12-Pack | not stated in listing | Large | 12 | white | None stated | $4.97 | — | $0.414 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/maritime-pride-large-white-eggs-12-pack-2 |
| 89 | Giant Tiger | online listing, province tag(s): PE; tag in_store_only:true; no store selected | Maritime Pride | Maritime Pride White Eggs, Large, 18-Pack | not stated in listing | Large | 18 | white | None stated | $7.97 | — | $0.443 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/maritime-pride-white-eggs-large-18-pack-3 |
| 90 | Giant Tiger | online listing, province tag(s): PE; tag in_store_only:true; no store selected | Nutri | Nutri Maritime Pride Ultra Extra Large Size Brown Eggs, 12-Pack | not stated in listing | Super/Ultra XL (as named) | 12 | brown | None stated | $5.62 | — | $0.468 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/12pk-maritime-pride-lg-brown |
| 91 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Medium Eggs, 30-Pack | not stated in listing | Medium | 30 | white | None stated | $9.29 | — | $0.310 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-white-medium-eggs-30-pack-1 |
| 92 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms White Medium Eggs, 30-Pack | not stated in listing | Medium | 30 | white | None stated | $9.29 | — | $0.310 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-medium-white-eggs-30pk-1 |
| 93 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large White Eggs, 30-Pack | not stated in listing | Large | 30 | white | None stated | $9.78 | — | $0.326 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-white-eggs-30-pack-4 |
| 94 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Medium Eggs, 12-Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.03 | — | $0.336 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/t2-12pk-medium-white-eggs |
| 95 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Medium Eggs, 12-Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.03 | — | $0.336 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-medium-eggs-12-pack-1 |
| 96 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $4.08 | — | $0.340 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack-11 |
| 97 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated | $4.08 | — | $0.340 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack-9 |
| 98 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Prestige | Burnbrae Farms Prestige Large Eggs Family Pack, 18-Pack | not stated in listing | Large | 18 | not stated | None stated | $6.19 | — | $0.344 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-prestige-large-eggs-family-pack-18-pack-1 |
| 99 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Prestige | Burnbrae Farms Prestige Family Pack Eggs, Large, 18-Pack | not stated in listing | Large | 18 | not stated | None stated | $6.19 | — | $0.344 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-prestige-family-pack-eggs-large-18-pack-2 |
| 100 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Extra Large Eggs, 12-Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.63 | — | $0.386 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-extra-large-eggs-12-pack-1 |
| 101 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Large Brown Eggs, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.63 | — | $0.469 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-large-brown-eggs-12-pack-7 |
| 102 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Brown Large Eggs, 12-Pack | not stated in listing | Large | 12 | brown | None stated | $5.63 | — | $0.469 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-brown-large-eggs-12-pack-1 |
| 103 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3, Large, 12-Pack | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.13 | — | $0.511 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-omega-3-large-12-pack-1 |
| 104 | Giant Tiger | online listing, province tag(s): QC; tag in_store_only:true; no store selected | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Size Large Eggs, 12-Pack | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.13 | — | $0.511 | 2026-10-03T04:11:36Z | https://www.gianttiger.com/products/burnbrae-farms-naturegg-omega-3-size-large-eggs-12-pack-1 |
| 105 | Loblaws | #1032, 200 Bullock Dr, Markham ON | No Name | Eggs, Medium | not stated in listing | Medium | 30 | not stated | None stated | $9.18 | — | $0.306 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/eggs-medium/p/21685186001_EA |
| 106 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Farm Eggs Medium | not stated in listing | Medium | 30 | not stated | None stated | $9.19 | — | $0.306 | 2026-10-03T04:10:33Z | https://www.loblaws.ca/farm-eggs-medium/p/21303271001_EA |
| 107 | Loblaws | #1032, 200 Bullock Dr, Markham ON | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $3.85 | — | $0.321 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 108 | Loblaws | #1032, 200 Bullock Dr, Markham ON | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $3.93 | — | $0.328 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 109 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Grade A Large Eggs | A (in name) | Large | 18 | not stated | None stated | $6.98 | — | $0.388 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/grade-a-large-eggs/p/20814294001_EA |
| 110 | Loblaws | #1032, 200 Bullock Dr, Markham ON | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.69 | — | $0.391 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 111 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $6.21 | $5.75 (ends 2026-10-07) | $0.479 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 112 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $6.75 | $5.75 (ends 2026-10-07) | $0.479 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 113 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $6.19 | $5.75 (ends 2026-10-07) | $0.479 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 114 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg NestlaidOmega 3 Large Size 12 Eggs | not stated in listing | Large | 12 | not stated | Nest Laid (as named) + Omega-3 (name) | $6.69 | $6.00 (ends 2026-10-14) | $0.500 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/naturegg-nestlaidomega-3-large-size-12-eggs/p/21069384001_EA |
| 115 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Omega 3 White Eggs | not stated in listing | not stated | 18 | white | None stated + Omega-3 (name) | $9.09 | — | $0.505 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/naturegg-omega-3-white-eggs/p/20826563001_EA |
| 116 | Loblaws | #1032, 200 Bullock Dr, Markham ON | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $6.29 | — | $0.524 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 117 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Rowe Farms | Green Valley Omega 3 Eggs, Large | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.49 | — | $0.541 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/green-valley-omega-3-eggs-large/p/20974459001_EA |
| 118 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Grade A White Eggs, Large | A (in name) | Large | 6 | white | None stated | $3.30 | — | $0.550 | 2026-10-03T04:10:33Z | https://www.loblaws.ca/grade-a-white-eggs-large/p/20814818001_EA |
| 119 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.19 | $6.75 (ends 2026-10-14) | $0.562 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 120 | Loblaws | #1032, 200 Bullock Dr, Markham ON | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $17.25 | — | $0.575 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 121 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Conestoga Eggs | Brown Eggs Free Run Omega-3 Size: Large | not stated in listing | Large | 18 | brown | Free run + Omega-3 (name) | $10.49 | — | $0.583 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/brown-eggs-free-run-omega-3-size-large/p/21542380001_EA |
| 122 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Conestoga Eggs | White Eggs Free Run Omega-3 Large Size | not stated in listing | Large | 18 | white | Free run + Omega-3 (name) | $10.49 | — | $0.583 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/white-eggs-free-run-omega-3-large-size/p/21622556001_EA |
| 123 | Loblaws | #1032, 200 Bullock Dr, Markham ON | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.15 | — | $0.596 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 124 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Rowe Farms | Green Valley Eggs Size Large Free Run Brown | not stated in listing | Large | 12 | brown | Free run | $7.23 | — | $0.603 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/green-valley-eggs-size-large-free-run-brown/p/20821562001_EA |
| 125 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Omega 3 Brown Eggs, Large | not stated in listing | Large | 12 | brown | None stated + Omega-3 (name) | $7.29 | — | $0.608 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/naturegg-omega-3-brown-eggs-large/p/20815722001_EA |
| 126 | Loblaws | #1032, 200 Bullock Dr, Markham ON | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.49 | — | $0.624 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 127 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Solar (name) | $8.19 | $7.50 (ends 2026-10-14) | $0.625 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| 128 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Omega Plus Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Omega-3 (name); Solar (name) | $8.19 | $7.50 (ends 2026-10-14) | $0.625 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/naturegg-omega-plus-solar-free-range-eggs-large/p/21565655001_EA |
| 129 | Loblaws | #1032, 200 Bullock Dr, Markham ON | President's Choice | Extra Large Free Run Brown Eggs | not stated in listing | Extra Large | 12 | brown | Free run | $7.59 | — | $0.632 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/extra-large-free-run-brown-eggs/p/20813937001_EA |
| 130 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | not stated in listing | not stated | 18 | not stated | Organic | $11.49 | — | $0.638 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| 131 | Loblaws | #1032, 200 Bullock Dr, Markham ON | PC Organics | Organics Medium Size Free-Range Brown Eggs 12 Pack | not stated in listing | Medium | 12 | brown | Organic | $7.79 | — | $0.649 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/organics-medium-size-free-range-brown-eggs-12-pack/p/20818960001_EA |
| 132 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Free Run Omega 3 Eggs | not stated in listing | not stated | 12 | not stated | Free run + Omega-3 (name) | $7.89 | — | $0.657 | 2026-10-03T04:10:33Z | https://www.loblaws.ca/naturegg-free-run-omega-3-eggs/p/20816074001_EA |
| 133 | Loblaws | #1032, 200 Bullock Dr, Markham ON | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 134 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Alderwood Farms | Pasture-Raised Eggs | not stated in listing | not stated | 12 | not stated | Pasture-raised | not shown | $7.99 (SPECIAL, ends 2026-10-07; was-price not shown) | $0.666 | 2026-10-03T04:10:57Z | https://www.loblaws.ca/pasture-raised-eggs/p/21434214001_EA |
| 135 | Loblaws | #1032, 200 Bullock Dr, Markham ON | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.99 | — | $0.666 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 136 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Omega 3 White Eggs | not stated in listing | not stated | 6 | white | None stated + Omega-3 (name) | $4.09 | — | $0.682 | 2026-10-03T04:05:52Z | https://www.loblaws.ca/naturegg-omega-3-white-eggs/p/20815567001_EA |
| 137 | Loblaws | #1032, 200 Bullock Dr, Markham ON | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $8.29 | — | $0.691 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 138 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Green Valley | Brown Eggs Free Range Farm Large | not stated in listing | Large | 12 | brown | Free range | $8.29 | — | $0.691 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/brown-eggs-free-range-farm-large/p/21185920_EA |
| 139 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Alderwood Farms | Pasture-Raised Eggs, Extra Large | not stated in listing | Extra Large | 12 | not stated | Pasture-raised | not shown | $8.49 (SPECIAL, ends 2026-10-07; was-price not shown) | $0.708 | 2026-10-03T04:17:51Z | https://www.loblaws.ca/pasture-raised-eggs-extra-large/p/21434746001_EA |
| 140 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Burnbrae Farms | Naturegg Free Run Eggs, Large | not stated in listing | Large | 6 | not stated | Free run | $4.39 | — | $0.732 | 2026-10-03T04:05:52Z | https://www.loblaws.ca/naturegg-free-run-eggs-large/p/20815566001_EA |
| 141 | Loblaws | #1032, 200 Bullock Dr, Markham ON | Conestoga Eggs | Brown Eggs Free Range Omega-3 Large Size | not stated in listing | Large | 12 | brown | Free range + Omega-3 (name) | $8.99 | — | $0.749 | 2026-10-03T04:05:48Z | https://www.loblaws.ca/brown-eggs-free-range-omega-3-large-size/p/21624591001_EA |
| 142 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.08 | — | $0.340 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 143 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.22 | — | $0.341 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/large-size-eggs/p/21435777001_EA |
| 144 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.21 | — | $0.351 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 145 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.71 | — | $0.393 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 146 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Golden Valley | White Eggs, Extra Large | not stated in listing | Extra Large | 18 | white | None stated | $7.49 | — | $0.416 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/white-eggs-extra-large/p/20819851001_EA |
| 147 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Foremost | Large Size Eggs 18 Pack | not stated in listing | Large | 18 | not stated | None stated | $7.61 | — | $0.423 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/large-size-eggs-18-pack/p/20976887001_EA |
| 148 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.38 | — | $0.448 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 149 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | not shown | $5.75 (SPECIAL, ends 2026-10-07; was-price not shown) | $0.479 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 150 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.03 | $5.75 (ends 2026-10-07) | $0.479 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 151 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $17.25 | — | $0.575 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 152 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $6.99 | — | $0.583 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 153 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Rabbit River | Free Run Omega 3 Brown Eggs | not stated in listing | not stated | 12 | brown | Free run + Omega-3 (name) | $7.44 | — | $0.620 | 2026-10-03T04:05:59Z | https://www.loblaws.ca/free-run-omega-3-brown-eggs/p/20821369001_EA |
| 154 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | not stated in listing | not stated | 18 | not stated | Organic | $11.49 | — | $0.638 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| 155 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.81 | — | $0.651 | 2026-10-03T04:05:59Z | https://www.loblaws.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 156 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Golden Valley | Born 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Born 3 (name) | $7.92 | — | $0.660 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/born-3-white-eggs-large/p/20819626001_EA |
| 157 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.94 | — | $0.662 | 2026-10-03T04:05:59Z | https://www.loblaws.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 158 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 159 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Country Golden Yolks | Country Golden Yolk Large Free Range Eggs | not stated in listing | Large | 12 | not stated | Free range | $8.03 | — | $0.669 | 2026-10-03T04:11:24Z | https://www.loblaws.ca/country-golden-yolk-large-free-range-eggs/p/20905536001_EA |
| 160 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Rabbit River | Organic Eggs, Medium | not stated in listing | Medium | 12 | not stated | Organic | $8.24 | — | $0.687 | 2026-10-03T04:05:59Z | https://www.loblaws.ca/organic-eggs-medium/p/20995948001_EA |
| 161 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Rabbit River | Large Organic Eggs | not stated in listing | Large | 12 | not stated | Organic | $8.44 | — | $0.703 | 2026-10-03T04:18:09Z | https://www.loblaws.ca/large-organic-eggs/p/20821561001_EA |
| 162 | Loblaws (City Market) | #7155, 658 Homer St, Vancouver BC | Rabbit River | Free Range Organic Eggs Large Size | not stated in listing | Large | 2 | not stated | Organic | $5.99 | — | $2.995 | 2026-10-03T04:18:09Z | https://www.loblaws.ca/free-range-organic-eggs-large-size/p/21543545001_EA |
| 163 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $2.99 | — | $0.249 | 2026-10-03T04:13:55Z | https://www.maxi.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 164 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Grade A White Eggs, Small | A (in name) | Small | 12 | white | None stated | $3.29 | — | $0.274 | 2026-10-03T04:19:48Z | https://www.maxi.ca/grade-a-white-eggs-small/p/20814299001_EA |
| 165 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.19 | — | $0.340 | 2026-10-03T04:13:55Z | https://www.maxi.ca/large-size-eggs/p/21435777001_EA |
| 166 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.11 | — | $0.343 | 2026-10-03T04:13:55Z | https://www.maxi.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 167 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Grade A Large Eggs | A (in name) | Large | 18 | not stated | None stated | $6.85 | — | $0.381 | 2026-10-03T04:13:55Z | https://www.maxi.ca/grade-a-large-eggs/p/20814294001_EA |
| 168 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.71 | — | $0.393 | 2026-10-03T04:13:55Z | https://www.maxi.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 169 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $4.99 | — | $0.416 | 2026-10-03T04:13:55Z | https://www.maxi.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 170 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Super Bon-Ee Grade A White Eggs, Super Extra Large | A (in name) | Super/Ultra XL (as named) | 12 | white | None stated | $5.29 | — | $0.441 | 2026-10-03T04:13:55Z | https://www.maxi.ca/super-bon-ee-grade-a-white-eggs-super-extra-large/p/20814693001_EA |
| 171 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.63 | — | $0.469 | 2026-10-03T04:13:55Z | https://www.maxi.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 172 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Naturegg Omega 3 White Eggs | not stated in listing | not stated | 18 | white | None stated + Omega-3 (name) | $8.81 | — | $0.489 | 2026-10-03T04:13:55Z | https://www.maxi.ca/naturegg-omega-3-white-eggs/p/20826563001_EA |
| 173 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Grade A White Eggs, Large | A (in name) | Large | 6 | white | None stated | $3.00 | — | $0.500 | 2026-10-03T04:13:31Z | https://www.maxi.ca/grade-a-white-eggs-large/p/20814818001_EA |
| 174 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $6.29 | — | $0.524 | 2026-10-03T04:13:55Z | https://www.maxi.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 175 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Naturegg NestlaidOmega 3 Large Size 12 Eggs | not stated in listing | Large | 12 | not stated | Nest Laid (as named) + Omega-3 (name) | $6.49 | — | $0.541 | 2026-10-03T04:13:55Z | https://www.maxi.ca/naturegg-nestlaidomega-3-large-size-12-eggs/p/21069384001_EA |
| 176 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $6.49 | — | $0.541 | 2026-10-03T04:13:55Z | https://www.maxi.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 177 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $17.50 | — | $0.583 | 2026-10-03T04:13:55Z | https://www.maxi.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 178 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.49 | $7.00 (ends 2026-10-07) | $0.583 | 2026-10-03T04:06:59Z | https://www.maxi.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 179 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.17 | — | $0.598 | 2026-10-03T04:13:55Z | https://www.maxi.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 180 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.19 | — | $0.599 | 2026-10-03T04:13:55Z | https://www.maxi.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 181 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Naturegg Omega 3 Brown Eggs, Large | not stated in listing | Large | 12 | brown | None stated + Omega-3 (name) | $7.19 | — | $0.599 | 2026-10-03T04:06:59Z | https://www.maxi.ca/naturegg-omega-3-brown-eggs-large/p/20815722001_EA |
| 182 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $7.87 | — | $0.656 | 2026-10-03T04:06:59Z | https://www.maxi.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 183 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:13:55Z | https://www.maxi.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 184 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | PC Organics | Organics Medium Size Free-Range Brown Eggs 12 Pack | not stated in listing | Medium | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:06:59Z | https://www.maxi.ca/organics-medium-size-free-range-brown-eggs-12-pack/p/20818960001_EA |
| 185 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Naturegg Omega 3 White Eggs | not stated in listing | not stated | 6 | white | None stated + Omega-3 (name) | $4.09 | — | $0.682 | 2026-10-03T04:13:31Z | https://www.maxi.ca/naturegg-omega-3-white-eggs/p/20815567001_EA |
| 186 | Maxi | #9528, 1835 rue Sainte-Catherine Est, Montréal QC | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Solar (name) | $8.19 | — | $0.682 | 2026-10-03T04:13:55Z | https://www.maxi.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| 187 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection | Large Eggs | not stated in listing | Large | 18 | not stated | None stated | $5.99 | $4.99 (ends October 7, 2026) | $0.277 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/059749896078 |
| 188 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection | Medium Eggs | not stated in listing | Medium | 12 | not stated | None stated | $3.89 | — | $0.324 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/medium-eggs/p/059749896047 |
| 189 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection | Large Eggs | not stated in listing | Large | 12 | not stated | None stated | $3.99 | — | $0.333 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/059749896054 |
| 190 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection | Large Eggs, Value Pack | not stated in listing | Large | 30 | not stated | None stated | $9.99 | — | $0.333 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/059749976879 |
| 191 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gray Ridge Egg Farms | Large Eggs, Premium Brand | not stated in listing | Large | 18 | not stated | None stated | $7.29 | — | $0.405 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/064767343053 |
| 192 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Selection | Extra Large Eggs | not stated in listing | Extra Large | 12 | not stated | None stated | $4.89 | — | $0.407 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/extra-large-eggs/p/059749896061 |
| 193 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gray Ridge Egg Farms | Extra Large Eggs, Value Pack | not stated in listing | Extra Large | 18 | not stated | None stated | $7.59 | — | $0.422 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/extra-large-eggs/p/064767342056 |
| 194 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gray Ridge Egg Farms | Large Brown Eggs, Value Pack | not stated in listing | Large | 18 | brown | None stated | $7.99 | — | $0.444 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-brown-eggs/p/064767343114 |
| 195 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gray Ridge Egg Farms | Large Eggs, Premium Brand | not stated in listing | Large | 12 | not stated | None stated | $5.59 | — | $0.466 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/064767343046 |
| 196 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gray Ridge Egg Farms | Jumbo Eggs, Super 747s | not stated in listing | Jumbo | 12 | not stated | None stated | $5.79 | — | $0.482 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/jumbo-eggs/p/064767341004 |
| 197 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gold Egg | Large Eggs, Golden D | not stated in listing | Large | 18 | not stated | None stated + Golden D/Vitamin D (name) | $8.99 | — | $0.499 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/674959000222 |
| 198 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gray Ridge Egg Farms | Large Brown Eggs | not stated in listing | Large | 12 | brown | None stated | $6.39 | — | $0.532 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-brown-eggs/p/064767343015 |
| 199 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Conestoga Farms | Large Free-Run Omega-3 Eggs | not stated in listing | Large | 18 | not stated | Free run + Omega-3 (name) | $9.99 | $9.79 (ends October 7, 2026) | $0.544 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-omega-3-eggs/p/064767343947 |
| 200 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gray Ridge Egg Farms | Extra Large Brown Eggs | not stated in listing | Extra Large | 12 | brown | None stated | $6.59 | — | $0.549 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/extra-large-brown-eggs/p/064767342018 |
| 201 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Conestoga Farms | Large Free-Run Omega-3 Brown Eggs | not stated in listing | Large | 18 | brown | Free run + Omega-3 (name) | $11.19 | $9.99 (ends October 7, 2026) | $0.555 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-omega-3-brown-eggs/p/064767343954 |
| 202 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gray Ridge Egg Farms | Large Eggs | not stated in listing | Large | 6 | not stated | None stated | $3.39 | — | $0.565 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-eggs/p/064767343312 |
| 203 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gold Egg | Large Brown Eggs, Omega-3 | not stated in listing | Large | 12 | brown | None stated + Omega-3 (name) | $7.59 | $6.99 (ends October 7, 2026) | $0.583 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-brown-eggs/p/674959000031 |
| 204 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Life Smart | Large Free-Run Eggs, Naturalia | not stated in listing | Large | 18 | not stated | Free run | $10.49 | — | $0.583 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-eggs/p/059749992220 |
| 205 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Conestoga Farms | Medium Brown Free-Run Eggs | not stated in listing | Medium | 12 | brown | Free run | $7.19 | — | $0.599 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/medium-brown-free-run-eggs/p/064767366014 |
| 206 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Gold Egg | Large Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.19 | — | $0.599 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-brown-eggs/p/674959000086 |
| 207 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Life Smart | Large Free-Run Eggs, Naturalia | not stated in listing | Large | 12 | not stated | Free run | $7.59 | — | $0.632 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-eggs/p/059749992206 |
| 208 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Conestoga Farms | Large Free-Run Omega-3 Eggs | not stated in listing | Large | 12 | not stated | Free run + Omega-3 (name) | $7.69 | — | $0.641 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-omega-3-eggs/p/064767343855 |
| 209 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Conestoga Farms | Large Free-Range Eggs | not stated in listing | Large | 12 | not stated | Free range | $7.69 | — | $0.641 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-range-eggs/p/064767343978 |
| 210 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Life Smart | Large Organic Brown Eggs, Free-Range | not stated in listing | Large | 12 | brown | Organic | $7.79 | — | $0.649 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-organic-brown-eggs/p/059749976817 |
| 211 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Life Smart | Large Free-Run Omega-3 Eggs, Naturalia | not stated in listing | Large | 12 | not stated | Free run + Omega-3 (name) | $7.99 | — | $0.666 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-omega-3-eggs/p/059749992237 |
| 212 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Life Smart | Extra Large Organic Free-Run Brown Eggs | not stated in listing | Extra Large | 12 | brown | Organic | $8.29 | — | $0.691 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/extra-large-organic-free-run-brown-eggs/p/059749976824 |
| 213 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Conestoga Farms | Large Free-Run Omega-3 Brown Eggs | not stated in listing | Large | 12 | brown | Free run + Omega-3 (name) | $8.29 | — | $0.691 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/large-free-run-omega-3-brown-eggs/p/064767343909 |
| 214 | Metro | Metro Devonshire (store 378), 3100 Howard Ave., Windsor ON | Conestoga Farms | Extra Large Organic Brown Eggs | not stated in listing | Extra Large | 6 | brown | Organic | $5.19 | — | $0.865 | 2026-10-03T04:10:35Z (list) / 04:10:55-04:11:20Z (product pages) | https://api2.metro.ca/en/online-grocery/aisles/dairy-eggs/eggs/whole-eggs/extra-large-organic-brown-eggs/p/064767542166 |
| 215 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.09 | — | $0.341 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 216 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.28 | — | $0.343 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/large-size-eggs/p/21435777001_EA |
| 217 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.18 | — | $0.348 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 218 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | No Name | Eggs, Large | not stated in listing | Large | 12 | not stated | None stated | $4.18 | — | $0.348 | 2026-10-03T04:18:42Z | https://www.nofrills.ca/eggs-large/p/20044005_EA |
| 219 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.68 | — | $0.390 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 220 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | Foremost | Large Size Eggs 18 Pack | not stated in listing | Large | 18 | not stated | None stated | $7.25 | — | $0.403 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/large-size-eggs-18-pack/p/20976887001_EA |
| 221 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | Sparks | White Eggs, Extra Large | not stated in listing | Extra Large | 18 | white | None stated | $7.40 | — | $0.411 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/white-eggs-extra-large/p/20821162001_EA |
| 222 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.38 | — | $0.448 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 223 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $5.75 | $5.50 (ends 2026-10-07) | $0.458 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 224 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | Farmers Finest | Comfort Coop, Large Eggs | not stated in listing | Large | 12 | not stated | Enriched/Comfort/Cozy coop (as named) | $5.57 | — | $0.464 | 2026-10-03T04:06:18Z | https://www.nofrills.ca/comfort-coop-large-eggs/p/20882339001_EA |
| 225 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | Farmers Finest | Free Range, Large Eggs | not stated in listing | Large | 12 | not stated | Free range | $7.03 | — | $0.586 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/free-range-large-eggs/p/20881824001_EA |
| 226 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.07 | — | $0.589 | 2026-10-03T04:12:10Z | https://www.nofrills.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 227 | No Frills | #3155, 10233 Elbow Dr SW, Calgary AB | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.73 | — | $0.644 | 2026-10-03T04:06:18Z | https://www.nofrills.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 228 | No Frills | #3410, 4508 Fraser St, Vancouver BC | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.08 | — | $0.340 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 229 | No Frills | #3410, 4508 Fraser St, Vancouver BC | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.22 | — | $0.341 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/large-size-eggs/p/21435777001_EA |
| 230 | No Frills | #3410, 4508 Fraser St, Vancouver BC | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.21 | — | $0.351 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 231 | No Frills | #3410, 4508 Fraser St, Vancouver BC | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.71 | — | $0.393 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 232 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Foremost | Large Size Eggs 18 Pack | not stated in listing | Large | 18 | not stated | None stated | $7.29 | — | $0.405 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/large-size-eggs-18-pack/p/20976887001_EA |
| 233 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Golden Valley | White Eggs, Extra Large | not stated in listing | Extra Large | 18 | white | None stated | $7.49 | — | $0.416 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/white-eggs-extra-large/p/20819851001_EA |
| 234 | No Frills | #3410, 4508 Fraser St, Vancouver BC | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.38 | — | $0.448 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 235 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $5.75 | $5.50 (ends 2026-10-07) | $0.458 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 236 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Golden Valley | Born 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Born 3 (name) | $6.15 | — | $0.512 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/born-3-white-eggs-large/p/20819626001_EA |
| 237 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $6.39 | — | $0.532 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 238 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Rabbit River | Large Size Brown Eggs Free Run | not stated in listing | Large | 18 | brown | Free run | $9.88 | — | $0.549 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/large-size-brown-eggs-free-run/p/21724440001_EA |
| 239 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Rabbit River | Large Size White Eggs Free Run Dark Yolk | not stated in listing | Large | 18 | white | Free run + Dark yolk (name) | $9.99 | — | $0.555 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/large-size-white-eggs-free-run-dark-yolk/p/21724479001_EA |
| 240 | No Frills | #3410, 4508 Fraser St, Vancouver BC | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $6.99 | — | $0.583 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 241 | No Frills | #3410, 4508 Fraser St, Vancouver BC | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.81 | — | $0.651 | 2026-10-03T04:06:28Z | https://www.nofrills.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 242 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Country Golden Yolks | Country Golden Yolk Large Free Range Eggs | not stated in listing | Large | 12 | not stated | Free range | $8.03 | — | $0.669 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/country-golden-yolk-large-free-range-eggs/p/20905536001_EA |
| 243 | No Frills | #3410, 4508 Fraser St, Vancouver BC | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $8.11 | — | $0.676 | 2026-10-03T04:12:34Z | https://www.nofrills.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 244 | No Frills | #3410, 4508 Fraser St, Vancouver BC | Rabbit River | Organic Eggs, Medium | not stated in listing | Medium | 12 | not stated | Organic | $8.17 | — | $0.681 | 2026-10-03T04:06:28Z | https://www.nofrills.ca/organic-eggs-medium/p/20995948001_EA |
| 245 | No Frills | #7952, 261 Richmond St W, Toronto ON | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $3.79 | — | $0.316 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 246 | No Frills | #7952, 261 Richmond St W, Toronto ON | No Name | Eggs, Medium | not stated in listing | Medium | 30 | not stated | None stated | $9.54 | — | $0.318 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/eggs-medium/p/21685186001_EA |
| 247 | No Frills | #7952, 261 Richmond St W, Toronto ON | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $3.93 | — | $0.328 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 248 | No Frills | #7952, 261 Richmond St W, Toronto ON | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.04 | — | $0.335 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/large-size-eggs/p/21435777001_EA |
| 249 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Grade A Large Eggs | A (in name) | Large | 18 | not stated | None stated | $7.06 | — | $0.392 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/grade-a-large-eggs/p/20814294001_EA |
| 250 | No Frills | #7952, 261 Richmond St W, Toronto ON | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.71 | — | $0.393 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 251 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Super Bon-Ee Grade A White Eggs, Super Extra Large | A (in name) | Super/Ultra XL (as named) | 12 | white | None stated | $5.49 | — | $0.458 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/super-bon-ee-grade-a-white-eggs-super-extra-large/p/20814693001_EA |
| 252 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $5.99 | — | $0.499 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 253 | No Frills | #7952, 261 Richmond St W, Toronto ON | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.99 | — | $0.499 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 254 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $6.19 | — | $0.516 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 255 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $6.45 | — | $0.537 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 256 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Naturegg NestlaidOmega 3 Large Size 12 Eggs | not stated in listing | Large | 12 | not stated | Nest Laid (as named) + Omega-3 (name) | $6.49 | — | $0.541 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/naturegg-nestlaidomega-3-large-size-12-eggs/p/21069384001_EA |
| 257 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Naturegg Omega 3 Brown Eggs, Large | not stated in listing | Large | 12 | brown | None stated + Omega-3 (name) | $6.99 | — | $0.583 | 2026-10-03T04:06:09Z | https://www.nofrills.ca/naturegg-omega-3-brown-eggs-large/p/20815722001_EA |
| 258 | No Frills | #7952, 261 Richmond St W, Toronto ON | Conestoga Eggs | Brown Eggs Free Run Omega-3 Size: Large | not stated in listing | Large | 18 | brown | Free run + Omega-3 (name) | $10.49 | — | $0.583 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/brown-eggs-free-run-omega-3-size-large/p/21542380001_EA |
| 259 | No Frills | #7952, 261 Richmond St W, Toronto ON | Conestoga Eggs | White Eggs Free Run Omega-3 Large Size | not stated in listing | Large | 18 | white | Free run + Omega-3 (name) | $10.49 | — | $0.583 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/white-eggs-free-run-omega-3-large-size/p/21622556001_EA |
| 260 | No Frills | #7952, 261 Richmond St W, Toronto ON | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $17.50 | — | $0.583 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 261 | No Frills | #7952, 261 Richmond St W, Toronto ON | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.18 | — | $0.598 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 262 | No Frills | #7952, 261 Richmond St W, Toronto ON | President's Choice | Extra Large Free Run Brown Eggs | not stated in listing | Extra Large | 12 | brown | Free run | $7.49 | — | $0.624 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/extra-large-free-run-brown-eggs/p/20813937001_EA |
| 263 | No Frills | #7952, 261 Richmond St W, Toronto ON | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.52 | — | $0.627 | 2026-10-03T04:06:09Z | https://www.nofrills.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 264 | No Frills | #7952, 261 Richmond St W, Toronto ON | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 265 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Solar (name) | $8.19 | — | $0.682 | 2026-10-03T04:11:47Z | https://www.nofrills.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| 266 | No Frills | #7952, 261 Richmond St W, Toronto ON | Burnbrae Farms | Naturegg Omega Plus Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Omega-3 (name); Solar (name) | $8.19 | — | $0.682 | 2026-10-03T04:06:09Z | https://www.nofrills.ca/naturegg-omega-plus-solar-free-range-eggs-large/p/21565655001_EA |
| 267 | No Frills | #7952, 261 Richmond St W, Toronto ON | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $8.29 | — | $0.691 | 2026-10-03T04:06:09Z | https://www.nofrills.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 268 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.29 | $3.00 (ends 2026-10-07) | $0.250 | 2026-10-03T04:13:29Z | https://www.provigo.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 269 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.33 | — | $0.344 | 2026-10-03T04:13:29Z | https://www.provigo.ca/large-size-eggs/p/21435777001_EA |
| 270 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.19 | — | $0.349 | 2026-10-03T04:13:29Z | https://www.provigo.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 271 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Grade A Large Eggs | A (in name) | Large | 18 | not stated | None stated | $6.98 | — | $0.388 | 2026-10-03T04:13:29Z | https://www.provigo.ca/grade-a-large-eggs/p/20814294001_EA |
| 272 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.79 | — | $0.399 | 2026-10-03T04:13:29Z | https://www.provigo.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 273 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Super Bon-Ee Grade A White Eggs, Super Extra Large | A (in name) | Super/Ultra XL (as named) | 12 | white | None stated | $5.29 | — | $0.441 | 2026-10-03T04:13:29Z | https://www.provigo.ca/super-bon-ee-grade-a-white-eggs-super-extra-large/p/20814693001_EA |
| 274 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.79 | — | $0.482 | 2026-10-03T04:13:29Z | https://www.provigo.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 275 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg NestlaidOmega 3 Large Size 12 Eggs | not stated in listing | Large | 12 | not stated | Nest Laid (as named) + Omega-3 (name) | $6.49 | $6.00 (ends 2026-10-14) | $0.500 | 2026-10-03T04:13:29Z | https://www.provigo.ca/naturegg-nestlaidomega-3-large-size-12-eggs/p/21069384001_EA |
| 276 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Grade A White Eggs, Large | A (in name) | Large | 6 | white | None stated | $3.10 | — | $0.517 | 2026-10-03T04:13:04Z | https://www.provigo.ca/grade-a-white-eggs-large/p/20814818001_EA |
| 277 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.19 | $6.50 (ends 2026-10-14) | $0.542 | 2026-10-03T04:13:29Z | https://www.provigo.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 278 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $17.25 | — | $0.575 | 2026-10-03T04:13:29Z | https://www.provigo.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 279 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $6.99 | — | $0.583 | 2026-10-03T04:13:29Z | https://www.provigo.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 280 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.17 | — | $0.598 | 2026-10-03T04:13:29Z | https://www.provigo.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 281 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.49 | — | $0.624 | 2026-10-03T04:06:48Z | https://www.provigo.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 282 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Solar (name) | $8.19 | $7.50 (ends 2026-10-14) | $0.625 | 2026-10-03T04:13:29Z | https://www.provigo.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| 283 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | PC Organics | Organics Medium Size Free-Range Brown Eggs 12 Pack | not stated in listing | Medium | 12 | brown | Organic | $7.83 | — | $0.652 | 2026-10-03T04:06:48Z | https://www.provigo.ca/organics-medium-size-free-range-brown-eggs-12-pack/p/20818960001_EA |
| 284 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:13:29Z | https://www.provigo.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 285 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.99 | — | $0.666 | 2026-10-03T04:06:48Z | https://www.provigo.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 286 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg Organic White Eggs, Large | not stated in listing | Large | 12 | white | Organic | $8.13 | — | $0.677 | 2026-10-03T04:06:48Z | https://www.provigo.ca/naturegg-organic-white-eggs-large/p/20827074001_EA |
| 287 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $8.13 | — | $0.677 | 2026-10-03T04:06:48Z | https://www.provigo.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 288 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg Omega 3 White Eggs | not stated in listing | not stated | 6 | white | None stated + Omega-3 (name) | $4.09 | — | $0.682 | 2026-10-03T04:13:04Z | https://www.provigo.ca/naturegg-omega-3-white-eggs/p/20815567001_EA |
| 289 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg Omega Plus Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Omega-3 (name); Solar (name) | $8.19 | — | $0.682 | 2026-10-03T04:06:48Z | https://www.provigo.ca/naturegg-omega-plus-solar-free-range-eggs-large/p/21565655001_EA |
| 290 | Provigo | #7297, 1275 av. des Canadiens-de-Montréal, Montréal QC | Burnbrae Farms | Naturegg Free Run Eggs, Large | not stated in listing | Large | 6 | not stated | Free run | $4.39 | — | $0.732 | 2026-10-03T04:06:48Z | https://www.provigo.ca/naturegg-free-run-eggs-large/p/20815566001_EA |
| 291 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Grade A White Eggs, Small | A (in name) | Small | 12 | white | None stated | $3.09 | — | $0.258 | 2026-10-03T04:16:14Z | https://www.realcanadiansuperstore.ca/grade-a-white-eggs-small/p/20822678001_EA |
| 292 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | No Name | Eggs, Medium | not stated in listing | Medium | 30 | not stated | None stated | $9.18 | — | $0.306 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/eggs-medium/p/21685186001_EA |
| 293 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $3.79 | — | $0.316 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 294 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $3.93 | — | $0.328 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 295 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Premium Large Eggs | not stated in listing | Large | 18 | not stated | None stated | $6.98 | $6.50 (ends 2026-10-14) | $0.361 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/premium-large-eggs/p/20822787001_EA |
| 296 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.69 | — | $0.391 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 297 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Brown Eggs, Large | not stated in listing | Large | 18 | brown | None stated | $7.24 | — | $0.402 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/brown-eggs-large/p/20822788001_EA |
| 298 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Grade A Premium White Eggs, Large | A (in name) | Large | 12 | white | None stated | $5.19 | — | $0.432 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/grade-a-premium-white-eggs-large/p/20822673001_EA |
| 299 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Large Eggs | not stated in listing | Large | 30 | not stated | None stated | $13.11 | — | $0.437 | 2026-10-03T04:16:14Z | https://www.realcanadiansuperstore.ca/large-eggs/p/20987491001_EA |
| 300 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Grade A Eggs, Super Extra-Large | A (in name) | Super/Ultra XL (as named) | 12 | not stated | None stated | $5.69 | — | $0.474 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/grade-a-eggs-super-extra-large/p/20822680001_EA |
| 301 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Grade A Double Yolk White Eggs | A (in name) | not stated | 12 | white | None stated + Double yolk (name) | $5.99 | — | $0.499 | 2026-10-03T04:16:14Z | https://www.realcanadiansuperstore.ca/grade-a-double-yolk-white-eggs/p/20822896001_EA |
| 302 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Goldegg | Golden D White Eggs, Large | not stated in listing | Large | 18 | white | None stated + Golden D/Vitamin D (name) | $8.99 | — | $0.499 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/golden-d-white-eggs-large/p/20819807001_EA |
| 303 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | White Eggs, Large | not stated in listing | Large | 6 | white | None stated | $3.00 | — | $0.500 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/white-eggs-large/p/20823664001_EA |
| 304 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $6.19 | — | $0.516 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 305 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Grade A Brown Eggs, Large | A (in name) | Large | 12 | brown | None stated | $6.19 | — | $0.516 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/grade-a-brown-eggs-large/p/20822900001_EA |
| 306 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Gray Ridge | Grade A Brown Eggs, Extra Large | A (in name) | Extra Large | 12 | brown | None stated | $6.19 | — | $0.516 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/grade-a-brown-eggs-extra-large/p/20822640001_EA |
| 307 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $6.21 | — | $0.517 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 308 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Rowe Farms | Green Valley Omega 3 Eggs, Large | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.49 | — | $0.541 | 2026-10-03T04:04:44Z | https://www.realcanadiansuperstore.ca/green-valley-omega-3-eggs-large/p/20974459001_EA |
| 309 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Burnbrae Farms | Naturegg NestlaidOmega 3 Large Size 12 Eggs | not stated in listing | Large | 12 | not stated | Nest Laid (as named) + Omega-3 (name) | $6.69 | — | $0.557 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/naturegg-nestlaidomega-3-large-size-12-eggs/p/21069384001_EA |
| 310 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $16.84 | — | $0.561 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 311 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Goldegg | Omega 3 White Eggs | not stated in listing | not stated | 12 | white | None stated + Omega-3 (name) | $6.89 | — | $0.574 | 2026-10-03T04:16:14Z | https://www.realcanadiansuperstore.ca/omega-3-white-eggs/p/20822519001_EA |
| 312 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Goldegg | Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $6.99 | — | $0.583 | 2026-10-03T04:16:14Z | https://www.realcanadiansuperstore.ca/omega-3-white-eggs-large/p/20822637001_EA |
| 313 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Conestoga Eggs | Brown Eggs Free Run Omega-3 Size: Large | not stated in listing | Large | 18 | brown | Free run + Omega-3 (name) | $10.49 | — | $0.583 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/brown-eggs-free-run-omega-3-size-large/p/21542380001_EA |
| 314 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Conestoga Eggs | White Eggs Free Run Omega-3 Large Size | not stated in listing | Large | 18 | white | Free run + Omega-3 (name) | $10.49 | — | $0.583 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/white-eggs-free-run-omega-3-large-size/p/21622556001_EA |
| 315 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Rowe Farms | Green Valley Eggs Size Large Free Run Brown | not stated in listing | Large | 12 | brown | Free run | $7.03 | — | $0.586 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/green-valley-eggs-size-large-free-run-brown/p/20821562001_EA |
| 316 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.15 | — | $0.596 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 317 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.19 | — | $0.599 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 318 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | President's Choice | Extra Large Free Run Brown Eggs | not stated in listing | Extra Large | 12 | brown | Free run | $7.49 | — | $0.624 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/extra-large-free-run-brown-eggs/p/20813937001_EA |
| 319 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.49 | — | $0.624 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 320 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Goldegg | Omega 3 White Eggs, Extra Large | not stated in listing | Extra Large | 12 | white | None stated + Omega-3 (name) | $7.49 | — | $0.624 | 2026-10-03T04:16:14Z | https://www.realcanadiansuperstore.ca/omega-3-white-eggs-extra-large/p/20820642001_EA |
| 321 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | not stated in listing | not stated | 18 | not stated | Organic | $11.49 | — | $0.638 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| 322 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Goldegg | Omega 3 Brown Eggs, Large | not stated in listing | Large | 12 | brown | None stated + Omega-3 (name) | $7.69 | — | $0.641 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/omega-3-brown-eggs-large/p/20822561001_EA |
| 323 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | PC Organics | Organics Medium Size Free-Range Brown Eggs 12 Pack | not stated in listing | Medium | 12 | brown | Organic | $7.79 | — | $0.649 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/organics-medium-size-free-range-brown-eggs-12-pack/p/20818960001_EA |
| 324 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 325 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.99 | — | $0.666 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 326 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Conestoga Eggs | Omega 3 White Eggs | not stated in listing | not stated | 12 | white | None stated + Omega-3 (name) | $7.99 | — | $0.666 | 2026-10-03T04:16:18Z | https://www.realcanadiansuperstore.ca/omega-3-white-eggs/p/21305346001_EA |
| 327 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Goldegg | Omega 3 White Eggs, Medium | not stated in listing | Medium | 6 | white | None stated + Omega-3 (name) | $4.09 | — | $0.682 | 2026-10-03T04:16:14Z | https://www.realcanadiansuperstore.ca/omega-3-white-eggs-medium/p/20822563001_EA |
| 328 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Burnbrae Farms | Naturegg Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Solar (name) | $8.19 | — | $0.682 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/naturegg-solar-free-range-eggs-large/p/21565857001_EA |
| 329 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Burnbrae Farms | Naturegg Omega Plus Solar Free Range Eggs, Large | not stated in listing | Large | 12 | not stated | Free range + Omega-3 (name); Solar (name) | $8.19 | — | $0.682 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/naturegg-omega-plus-solar-free-range-eggs-large/p/21565655001_EA |
| 330 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $8.29 | — | $0.691 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 331 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Conestoga Eggs | Omega 3 Brown Eggs | not stated in listing | not stated | 12 | brown | None stated + Omega-3 (name) | $8.55 | — | $0.713 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/omega-3-brown-eggs/p/21293237001_EA |
| 332 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Alderwood Farms | Pasture-Raised Eggs | not stated in listing | not stated | 12 | not stated | Pasture-raised | $8.99 | — | $0.749 | 2026-10-03T04:08:37Z | https://www.realcanadiansuperstore.ca/pasture-raised-eggs/p/21434214001_EA |
| 333 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Conestoga Eggs | Brown Eggs Free Range Omega-3 Large Size | not stated in listing | Large | 12 | brown | Free range + Omega-3 (name) | $8.99 | — | $0.749 | 2026-10-03T04:04:51Z | https://www.realcanadiansuperstore.ca/brown-eggs-free-range-omega-3-large-size/p/21624591001_EA |
| 334 | Real Canadian Superstore | #1080, 3050 Argentia Rd, Mississauga ON | Alderwood Farms | Pasture-Raised Eggs, Extra Large | not stated in listing | Extra Large | 12 | not stated | Pasture-raised | $9.49 | — | $0.791 | 2026-10-03T04:16:14Z | https://www.realcanadiansuperstore.ca/pasture-raised-eggs-extra-large/p/21434746001_EA |
| 335 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $3.98 | — | $0.332 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 336 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Foremost | Large Size Eggs 18 Pack | not stated in listing | Large | 18 | not stated | None stated | $6.09 | — | $0.338 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/large-size-eggs-18-pack/p/20976887001_EA |
| 337 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.25 | — | $0.342 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/large-size-eggs/p/21435777001_EA |
| 338 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.16 | — | $0.347 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 339 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | No Name | Eggs, Large | not stated in listing | Large | 12 | not stated | None stated | $4.16 | — | $0.347 | 2026-10-03T04:17:14Z | https://www.realcanadiansuperstore.ca/eggs-large/p/20044005_EA |
| 340 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.68 | — | $0.390 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 341 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Countryside | XL 18 White Eggs | not stated in listing | Extra Large | 18 | white | None stated | $7.27 | — | $0.404 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/xl-18-white-eggs/p/20819781001_EA |
| 342 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.31 | — | $0.443 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 343 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Burnbrae Farms | Super Bon-Ee Grade A White Eggs, Super Extra Large | A (in name) | Super/Ultra XL (as named) | 12 | white | None stated | $5.42 | — | $0.452 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/super-bon-ee-grade-a-white-eggs-super-extra-large/p/20814693001_EA |
| 344 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $5.75 | — | $0.479 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 345 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Goldegg | Golden D White Eggs, Large | not stated in listing | Large | 18 | white | None stated + Golden D/Vitamin D (name) | $8.98 | — | $0.499 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/golden-d-white-eggs-large/p/20819807001_EA |
| 346 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $6.38 | — | $0.532 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 347 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $16.99 | — | $0.566 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 348 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.03 | — | $0.586 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 349 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.05 | — | $0.588 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 350 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | not stated in listing | not stated | 18 | not stated | Organic | $11.49 | — | $0.638 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| 351 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.69 | — | $0.641 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 352 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.73 | — | $0.644 | 2026-10-03T04:05:26Z | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 353 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.85 | — | $0.654 | 2026-10-03T04:05:26Z | https://www.realcanadiansuperstore.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 354 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:10:03Z | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 355 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $8.10 | — | $0.675 | 2026-10-03T04:05:26Z | https://www.realcanadiansuperstore.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 356 | Real Canadian Superstore | #1508, 3193 Portage Ave, Winnipeg MB | Rabbit River | Organic Eggs, Medium | not stated in listing | Medium | 12 | not stated | Organic | $8.19 | — | $0.682 | 2026-10-03T04:05:26Z | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| 357 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.08 | — | $0.340 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 358 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.22 | — | $0.341 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/large-size-eggs/p/21435777001_EA |
| 359 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Eggs, Medium | not stated in listing | Medium | 12 | not stated | None stated | $4.16 | — | $0.347 | 2026-10-03T04:16:35Z | https://www.realcanadiansuperstore.ca/eggs-medium/p/20007168_EA |
| 360 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.21 | — | $0.351 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 361 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Eggs, Large | not stated in listing | Large | 12 | not stated | None stated | $4.21 | — | $0.351 | 2026-10-03T04:16:35Z | https://www.realcanadiansuperstore.ca/eggs-large/p/20044005_EA |
| 362 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.71 | — | $0.393 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 363 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Eggs, Extra Large | not stated in listing | Extra Large | 12 | not stated | None stated | $4.74 | — | $0.395 | 2026-10-03T04:16:35Z | https://www.realcanadiansuperstore.ca/eggs-extra-large/p/20095570_EA |
| 364 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Foremost | Large Size Eggs 18 Pack | not stated in listing | Large | 18 | not stated | None stated | $7.29 | — | $0.405 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/large-size-eggs-18-pack/p/20976887001_EA |
| 365 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Golden Valley | White Eggs, Extra Large | not stated in listing | Extra Large | 18 | white | None stated | $7.49 | — | $0.416 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/white-eggs-extra-large/p/20819851001_EA |
| 366 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.38 | — | $0.448 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 367 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | No Name | Eggs, Large Brown | not stated in listing | Large | 12 | brown | None stated | $5.47 | — | $0.456 | 2026-10-03T04:05:03Z | https://www.realcanadiansuperstore.ca/eggs-large-brown/p/20067335_EA |
| 368 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $5.75 | — | $0.479 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 369 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $6.39 | — | $0.532 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 370 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $16.99 | — | $0.566 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 371 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.03 | — | $0.586 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 372 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.08 | — | $0.590 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 373 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Rabbit River | Free Run Omega 3 Brown Eggs | not stated in listing | not stated | 12 | brown | Free run + Omega-3 (name) | $7.40 | — | $0.617 | 2026-10-03T04:05:03Z | https://www.realcanadiansuperstore.ca/free-run-omega-3-brown-eggs/p/20821369001_EA |
| 374 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | not stated in listing | not stated | 18 | not stated | Organic | $11.49 | — | $0.638 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| 375 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.69 | — | $0.641 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 376 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.81 | — | $0.651 | 2026-10-03T04:05:03Z | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 377 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Golden Valley | Born 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Born 3 (name) | $7.92 | — | $0.660 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/born-3-white-eggs-large/p/20819626001_EA |
| 378 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.94 | — | $0.662 | 2026-10-03T04:05:03Z | https://www.realcanadiansuperstore.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 379 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 380 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Coligny Creek | Free Range Eggs, Brown, 18 Count | not stated in listing | not stated | 18 | brown | Free range | $12.00 | — | $0.667 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/free-range-eggs-brown-18-count/p/21751043001_EA |
| 381 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Country Golden Yolks | Country Golden Yolk Large Free Range Eggs | not stated in listing | Large | 12 | not stated | Free range | $8.03 | — | $0.669 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/country-golden-yolk-large-free-range-eggs/p/20905536001_EA |
| 382 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $8.10 | — | $0.675 | 2026-10-03T04:05:03Z | https://www.realcanadiansuperstore.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 383 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Rabbit River | Organic Eggs, Medium | not stated in listing | Medium | 12 | not stated | Organic | $8.19 | — | $0.682 | 2026-10-03T04:05:03Z | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| 384 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | PC Organics | Organics Medium Size Free-Range Brown Eggs 12 Pack | not stated in listing | Medium | 12 | brown | Organic | $8.55 | — | $0.713 | 2026-10-03T04:05:03Z | https://www.realcanadiansuperstore.ca/organics-medium-size-free-range-brown-eggs-12-pack/p/20818960001_EA |
| 385 | Real Canadian Superstore | #1517, 350 SE Marine Dr, Vancouver BC | Coligny Creek | Organic Free Range Eggs, Brown, 18 Count | not stated in listing | not stated | 18 | brown | Organic | $14.00 | — | $0.778 | 2026-10-03T04:09:06Z | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-brown-18-count/p/21751226001_EA |
| 386 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.09 | — | $0.341 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 387 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.28 | — | $0.343 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/large-size-eggs/p/21435777001_EA |
| 388 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.20 | — | $0.350 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 389 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.68 | — | $0.390 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 390 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Foremost | Large Size Eggs 18 Pack | not stated in listing | Large | 18 | not stated | None stated | $7.27 | — | $0.404 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/large-size-eggs-18-pack/p/20976887001_EA |
| 391 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Harman | Eggs 18ct | not stated in listing | not stated | 18 | not stated | None stated | $7.47 | — | $0.415 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/eggs-18ct/p/20823665001_EA |
| 392 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Star | Free Run Eggs, Large | not stated in listing | Large | 18 | not stated | Free run | $8.04 | — | $0.447 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/free-run-eggs-large/p/21028407001_EA |
| 393 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.38 | — | $0.448 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 394 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | No Name | Eggs, Large Brown | not stated in listing | Large | 12 | brown | None stated | $5.46 | — | $0.455 | 2026-10-03T04:05:36Z | https://www.realcanadiansuperstore.ca/eggs-large-brown/p/20067335_EA |
| 395 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $5.75 | — | $0.479 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 396 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Goldegg | Golden D White Eggs, Large | not stated in listing | Large | 18 | white | None stated + Golden D/Vitamin D (name) | $8.98 | — | $0.499 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/golden-d-white-eggs-large/p/20819807001_EA |
| 397 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $6.49 | — | $0.541 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 398 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $16.99 | — | $0.566 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 399 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.03 | — | $0.586 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 400 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | not stated in listing | not stated | 18 | not stated | Organic | $11.49 | — | $0.638 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| 401 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.69 | — | $0.641 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 402 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.73 | — | $0.644 | 2026-10-03T04:05:36Z | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 403 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.74 | — | $0.645 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 404 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Star | Free Bird Free Range Large Eggs | not stated in listing | Large | 12 | not stated | Free range | $7.79 | — | $0.649 | 2026-10-03T04:05:36Z | https://www.realcanadiansuperstore.ca/free-bird-free-range-large-eggs/p/21033226001_EA |
| 405 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.86 | — | $0.655 | 2026-10-03T04:05:36Z | https://www.realcanadiansuperstore.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 406 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:10:30Z | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 407 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $8.10 | — | $0.675 | 2026-10-03T04:05:36Z | https://www.realcanadiansuperstore.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 408 | Real Canadian Superstore | #1533, 3806 Albert St, Regina SK | Rabbit River | Organic Eggs, Medium | not stated in listing | Medium | 12 | not stated | Organic | $8.19 | — | $0.682 | 2026-10-03T04:05:36Z | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| 409 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Medium Size Eggs 12 Pack | not stated in listing | Medium | 12 | not stated | None stated | $4.09 | — | $0.341 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/medium-size-eggs-12-pack/p/20813386001_EA |
| 410 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Large Size Eggs | not stated in listing | Large | 30 | not stated | None stated | $10.28 | — | $0.343 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/large-size-eggs/p/21435777001_EA |
| 411 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Eggs, Medium | not stated in listing | Medium | 12 | not stated | None stated | $4.15 | — | $0.346 | 2026-10-03T04:16:54Z | https://www.realcanadiansuperstore.ca/eggs-medium/p/20007168_EA |
| 412 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Large Size Eggs 12 Pack | not stated in listing | Large | 12 | not stated | None stated | $4.18 | — | $0.348 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| 413 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Eggs, Large | not stated in listing | Large | 12 | not stated | None stated | $4.18 | — | $0.348 | 2026-10-03T04:16:54Z | https://www.realcanadiansuperstore.ca/eggs-large/p/20044005_EA |
| 414 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Extra Large Size Eggs 12 Pack | not stated in listing | Extra Large | 12 | not stated | None stated | $4.68 | — | $0.390 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/extra-large-size-eggs-12-pack/p/20812726001_EA |
| 415 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Eggs, Extra Large | not stated in listing | Extra Large | 12 | not stated | None stated | $4.75 | — | $0.396 | 2026-10-03T04:16:54Z | https://www.realcanadiansuperstore.ca/eggs-extra-large/p/20095570_EA |
| 416 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Foremost | Large Size Eggs 18 Pack | not stated in listing | Large | 18 | not stated | None stated | $7.25 | — | $0.403 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/large-size-eggs-18-pack/p/20976887001_EA |
| 417 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Sparks | White Eggs, Extra Large | not stated in listing | Extra Large | 18 | white | None stated | $7.40 | — | $0.411 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/white-eggs-extra-large/p/20821162001_EA |
| 418 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Large Size Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | None stated | $5.38 | — | $0.448 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/large-size-brown-eggs-12-pack/p/20813936001_EA |
| 419 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | No Name | Eggs, Large Brown | not stated in listing | Large | 12 | brown | None stated | $5.45 | — | $0.454 | 2026-10-03T04:05:14Z | https://www.realcanadiansuperstore.ca/eggs-large-brown/p/20067335_EA |
| 420 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Farmers Finest | Comfort Coop, Large Eggs | not stated in listing | Large | 12 | not stated | Enriched/Comfort/Cozy coop (as named) | $5.57 | — | $0.464 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/comfort-coop-large-eggs/p/20882339001_EA |
| 421 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Burnbrae Farms | Naturegg Nest Laid White Eggs, Large | not stated in listing | Large | 12 | white | Nest Laid (as named) | $5.75 | — | $0.479 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/naturegg-nest-laid-white-eggs-large/p/20816075001_EA |
| 422 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Goldegg | Golden D White Eggs, Large | not stated in listing | Large | 18 | white | None stated + Golden D/Vitamin D (name) | $8.98 | — | $0.499 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/golden-d-white-eggs-large/p/20819807001_EA |
| 423 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Burnbrae Farms | Nature's Best White Eggs, Large | not stated in listing | Large | 12 | white | None stated | $6.39 | — | $0.532 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/nature-s-best-white-eggs-large/p/20814983001_EA |
| 424 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | PC Organics | Free-Range Large Brown Eggs, Club Pack (30 Count) | not stated in listing | Large | 30 | brown | Organic | $16.99 | — | $0.566 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/free-range-large-brown-eggs-club-pack-30-count/p/21205224001_EA |
| 425 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Burnbrae Farms | Naturegg Omega 3 White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.03 | — | $0.586 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/naturegg-omega-3-white-eggs-large/p/20815563001_EA |
| 426 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Farmers Finest | Free Range, Large Eggs | not stated in listing | Large | 12 | not stated | Free range | $7.03 | — | $0.586 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/free-range-large-eggs/p/20881824001_EA |
| 427 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Burnbrae Farms | Organic Free Range Eggs, 18 Eggs | not stated in listing | not stated | 18 | not stated | Organic | $11.49 | — | $0.638 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/organic-free-range-eggs-18-eggs/p/21572055001_EA |
| 428 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | President's Choice | Free Run Brown Eggs Large | not stated in listing | Large | 12 | brown | Free run | $7.68 | — | $0.640 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| 429 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Burnbrae Farms | Naturegg Omega Plus White Eggs, Large | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $7.69 | — | $0.641 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/naturegg-omega-plus-white-eggs-large/p/20815787001_EA |
| 430 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | PC Blue Menu | Blue Menu Free-Run Large Size White Eggs 12 Pack | not stated in listing | Large | 12 | white | Free run | $7.73 | — | $0.644 | 2026-10-03T04:05:14Z | https://www.realcanadiansuperstore.ca/blue-menu-free-run-large-size-white-eggs-12-pack/p/20992723001_EA |
| 431 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | PC Blue Menu | Blue Menu Large Size Free-Run Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.87 | — | $0.656 | 2026-10-03T04:05:14Z | https://www.realcanadiansuperstore.ca/blue-menu-large-size-free-run-brown-eggs/p/20812736001_EA |
| 432 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | PC Organics | Organics Large Size Free-Range Brown Eggs 12 Pack | not stated in listing | Large | 12 | brown | Organic | $7.99 | — | $0.666 | 2026-10-03T04:09:34Z | https://www.realcanadiansuperstore.ca/organics-large-size-free-range-brown-eggs-12-pack/p/20813711001_EA |
| 433 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | PC Organics | Organic Free-Range Extra Large Size Brown Eggs 12 Pack | not stated in listing | Extra Large | 12 | brown | Organic | $8.10 | — | $0.675 | 2026-10-03T04:05:14Z | https://www.realcanadiansuperstore.ca/organic-free-range-extra-large-size-brown-eggs-12/p/20813389001_EA |
| 434 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | Rabbit River | Organic Eggs, Medium | not stated in listing | Medium | 12 | not stated | Organic | $8.19 | — | $0.682 | 2026-10-03T04:05:14Z | https://www.realcanadiansuperstore.ca/organic-eggs-medium/p/20995948001_EA |
| 435 | Real Canadian Superstore | #1539, 20 Heritage Meadows Way SE, Calgary AB | PC Organics | Organics Medium Size Free-Range Brown Eggs 12 Pack | not stated in listing | Medium | 12 | brown | Organic | $8.55 | — | $0.713 | 2026-10-03T04:05:14Z | https://www.realcanadiansuperstore.ca/organics-medium-size-free-range-brown-eggs-12-pack/p/20818960001_EA |
| 436 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Medium White Eggs | not stated in listing | Medium | 12 | white | None stated | $4.15 | — | $0.346 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639410131) |
| 437 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Large White Eggs Cello | not stated in listing | Large | 30 | white | None stated | $10.60 | — | $0.353 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639394981) |
| 438 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Large White Eggs | not stated in listing | Large | 12 | white | None stated | $4.35 | — | $0.362 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639410124) |
| 439 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Golden Valley | Golden Valley - Large Brown Eggs | not stated in listing | Large | 30 | brown | None stated | $11.59 | — | $0.386 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00055799103043) |
| 440 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Extra Large White Eggs | not stated in listing | Extra Large | 12 | white | None stated | $4.85 | — | $0.404 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639410117) |
| 441 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Large White Eggs 18 | not stated in listing | Large | 18 | white | None stated | $7.35 | — | $0.408 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639199784) |
| 442 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Large Brown Eggs | not stated in listing | Large | 12 | brown | None stated | $5.79 | — | $0.482 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639411572) |
| 443 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Golden Valley | Golden Valley - Jumbo Eggs White | not stated in listing | Jumbo | 12 | white | None stated | $6.29 | — | $0.524 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00055799101100) |
| 444 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Omega 3 Large Eggs | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.75 | — | $0.562 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639320966) |
| 445 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Born 3 | Born 3 - Omega-3 Large Eggs | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name); Born 3 (name) | $6.79 | — | $0.566 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00666933900420) |
| 446 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Rabbit River Farms | Rabbit River Farms - Free Run Dark Yolk Large White Eggs | not stated in listing | Large | 18 | white | Free run + Dark yolk (name) | $10.59 | — | $0.588 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00620580000483) |
| 447 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Golden Valley | Golden Valley - Country Golden Yolks Free Range Medium Brown Eggs | not stated in listing | Medium | 12 | brown | Free range | $7.29 | — | $0.608 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00774290445499) |
| 448 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Free Run Eggs | not stated in listing | not stated | 12 | not stated | Free run | $7.35 | — | $0.613 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639332921) |
| 449 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Gold Egg | Gold Egg - White Eggs Large | not stated in listing | Large | 6 | white | None stated | $3.75 | — | $0.625 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00674959000109) |
| 450 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Western Family | Western Family - Free Range Brown Eggs, Large | not stated in listing | Large | 12 | brown | Free range | $7.85 | — | $0.654 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639332938) |
| 451 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Gold Egg | Gold Egg - Free Run Large Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.89 | — | $0.657 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00674959000086) |
| 452 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Rabbit River Farms | Rabbit River Farms - Free Run Large Brown Eggs | not stated in listing | Large | 18 | brown | Free run | $11.99 | — | $0.666 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00620580000476) |
| 453 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Gold Egg | Gold Egg - Free Run Omega 3 Large Brown Eggs | not stated in listing | Large | 12 | brown | Free run + Omega-3 (name) | $8.29 | — | $0.691 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00674959000284) |
| 454 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Golden Valley | Golden Valley - Country Golden Yolks Free Range Large Brown Eggs | not stated in listing | Large | 12 | brown | Free range | $8.45 | — | $0.704 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00774290091559) |
| 455 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | ONLY GOODNESS | ONLY GOODNESS - Organic Large Brown Eggs | not stated in listing | Large | 12 | brown | Organic | $8.85 | — | $0.738 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00062639368401) |
| 456 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Maple Hill | Maple Hill - Free Range Brown Eggs, Extra Large | not stated in listing | Extra Large | 12 | brown | Free range | $8.89 | — | $0.741 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00830312000043) |
| 457 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Maple Hill | Maple Hill - Free Range Eggs, Large Size | not stated in listing | Large | 12 | not stated | Free range | $8.99 | — | $0.749 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00830312000036) |
| 458 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Maple Hill | Maple Hill - Free Range, Grade A Organic Brown Eggs, Medium Size | A (in name) | Medium | 12 | brown | Organic | $8.99 | — | $0.749 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00830312000067) |
| 459 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Maple Hill | Maple Hill - Large Organic Free Range Eggs | not stated in listing | Large | 12 | not stated | Organic | $9.29 | — | $0.774 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00830312000074) |
| 460 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Rabbit River Farms | Rabbit River Farms - Organic Free Range Large Brown Eggs | not stated in listing | Large | 12 | brown | Organic | $9.35 | — | $0.779 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00620580000025) |
| 461 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Rabbit River | Rabbit River - Organic Extra Large Eggs Free Range | not stated in listing | Extra Large | 12 | not stated | Organic | $9.45 | — | $0.787 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00620580000018) |
| 462 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | AVALON | AVALON - Large Brown Eggs, Organic | not stated in listing | Large | 12 | brown | Organic | $9.75 | — | $0.812 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00066939060010) |
| 463 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | AVALON | AVALON - Organic Medium Brown Eggs | not stated in listing | Medium | 12 | brown | Organic | $9.75 | — | $0.812 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00066939060003) |
| 464 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | AVALON | AVALON - Organic Extra Large Brown Eggs | not stated in listing | Extra Large | 12 | brown | Organic | $10.05 | — | $0.838 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00066939060027) |
| 465 | Save-On-Foods | #1982, 19855 92a Ave, Langley Twp BC (gateway store type 'Corporate', mode 'planning') | Gold Egg | Gold Egg - Jumbo Organic Eggs | not stated in listing | Jumbo | 12 | not stated | Organic | $10.09 | — | $0.841 | 2026-10-03T04:06:39Z | https://storefrontgateway.saveonfoods.com/api/stores/1982/categories/30919/search?take=100&skip=0 (sku 00674959000178) |
| 466 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Medium White Eggs | not stated in listing | Medium | 12 | white | None stated | $4.15 | — | $0.346 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639410131) |
| 467 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Large White Eggs Cello | not stated in listing | Large | 30 | white | None stated | $10.60 | — | $0.353 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639394981) |
| 468 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Large White Eggs | not stated in listing | Large | 12 | white | None stated | $4.35 | — | $0.362 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639410124) |
| 469 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Golden Valley | Golden Valley - Large Brown Eggs | not stated in listing | Large | 30 | brown | None stated | $11.59 | — | $0.386 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00055799103043) |
| 470 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Large Size Brown Eggs | not stated in listing | Large | 30 | brown | None stated | $11.59 | — | $0.386 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639385309) |
| 471 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Extra Large White Eggs | not stated in listing | Extra Large | 12 | white | None stated | $4.85 | — | $0.404 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639410117) |
| 472 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Large White Eggs 18 | not stated in listing | Large | 18 | white | None stated | $7.35 | — | $0.408 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639199784) |
| 473 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Large Brown Eggs | not stated in listing | Large | 12 | brown | None stated | $5.79 | — | $0.482 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639411572) |
| 474 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Golden Valley | Golden Valley - Jumbo Eggs White | not stated in listing | Jumbo | 12 | white | None stated | $6.29 | — | $0.524 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00055799101100) |
| 475 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Omega 3 Large Eggs | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.75 | — | $0.562 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639320966) |
| 476 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Born 3 | Born 3 - Omega-3 Large Eggs | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name); Born 3 (name) | $6.79 | — | $0.566 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00666933900420) |
| 477 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Rabbit River Farms | Rabbit River Farms - Free Run Dark Yolk Large White Eggs | not stated in listing | Large | 18 | white | Free run + Dark yolk (name) | $10.59 | — | $0.588 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00620580000483) |
| 478 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Golden Valley | Golden Valley - Country Golden Yolks Free Range Medium Brown Eggs | not stated in listing | Medium | 12 | brown | Free range | $7.29 | — | $0.608 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00774290445499) |
| 479 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Free Run Eggs | not stated in listing | not stated | 12 | not stated | Free run | $7.35 | — | $0.613 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639332921) |
| 480 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Gold Egg | Gold Egg - White Eggs Large | not stated in listing | Large | 6 | white | None stated | $3.75 | — | $0.625 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00674959000109) |
| 481 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Western Family | Western Family - Free Range Brown Eggs, Large | not stated in listing | Large | 12 | brown | Free range | $7.85 | — | $0.654 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639332938) |
| 482 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Rabbit River Farms | Rabbit River Farms - Free Run Large Brown Eggs | not stated in listing | Large | 18 | brown | Free run | $11.99 | — | $0.666 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00620580000476) |
| 483 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Gold Egg | Gold Egg - Free Run Omega 3 Large Brown Eggs | not stated in listing | Large | 12 | brown | Free run + Omega-3 (name) | $8.29 | — | $0.691 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00674959000284) |
| 484 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Golden Valley | Golden Valley - Country Golden Yolks Free Range Large Brown Eggs | not stated in listing | Large | 12 | brown | Free range | $8.45 | — | $0.704 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00774290091559) |
| 485 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | ONLY GOODNESS | ONLY GOODNESS - Organic Large Brown Eggs | not stated in listing | Large | 12 | brown | Organic | $8.85 | — | $0.738 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00062639368401) |
| 486 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Rabbit River Farms | Rabbit River Farms - Organic Free Range Large Brown Eggs | not stated in listing | Large | 12 | brown | Organic | $9.35 | — | $0.779 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00620580000025) |
| 487 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | Rabbit River | Rabbit River - Organic Extra Large Eggs Free Range | not stated in listing | Extra Large | 12 | not stated | Organic | $9.45 | — | $0.787 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00620580000018) |
| 488 | Save-On-Foods | #2242 Langley - Downtown, 20151 Fraser Hwy, Langley BC | AVALON | AVALON - Large Brown Eggs, Organic | not stated in listing | Large | 12 | brown | Organic | $9.75 | — | $0.812 | 2026-10-03T04:07:08Z | https://storefrontgateway.saveonfoods.com/api/stores/2242/categories/30919/search?take=100&skip=0 (sku 00066939060010) |
| 489 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Medium White Eggs | not stated in listing | Medium | 12 | white | None stated | $4.05 | — | $0.338 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639410131) |
| 490 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Large White Eggs Cello | not stated in listing | Large | 30 | white | None stated | $10.60 | — | $0.353 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639394981) |
| 491 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Large White Eggs | not stated in listing | Large | 12 | white | None stated | $4.35 | — | $0.362 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639410124) |
| 492 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Extra Large White Eggs | not stated in listing | Extra Large | 12 | white | None stated | $4.85 | — | $0.404 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639410117) |
| 493 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Large White Eggs 18 | not stated in listing | Large | 18 | white | None stated | $7.35 | — | $0.408 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639199784) |
| 494 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Lovo | Lovo - Extra Large White Eggs | not stated in listing | Extra Large | 18 | white | None stated | $7.39 | — | $0.411 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00061719062208) |
| 495 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Large Brown Eggs | not stated in listing | Large | 12 | brown | None stated | $5.79 | — | $0.482 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639411572) |
| 496 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | VITA | VITA - Free Run Eggs - Large | not stated in listing | Large | 18 | not stated | Free run | $8.99 | — | $0.499 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00056526538008) |
| 497 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Lovo | Lovo - Large Dark Yolk Eggs - Free Run | not stated in listing | Large | 18 | not stated | Free run + Dark yolk (name) | $8.99 | — | $0.499 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00061719065100) |
| 498 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Lovo | Lovo - Large Size Eggs - Free Run | not stated in listing | Large | 30 | not stated | Free run | $14.99 | — | $0.500 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00061719097101) |
| 499 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Gold Egg | Gold Egg - Grain Fed Large Eggs White | not stated in listing | Large | 12 | white | None stated | $6.09 | — | $0.507 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00674959000062) |
| 500 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Lovo | Lovo - Large Omega 3 Eggs | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.59 | — | $0.549 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00061719065407) |
| 501 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Omega 3 Large Eggs | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.75 | — | $0.562 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639320966) |
| 502 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Rabbit River Farms | Rabbit River Farms - Free Run Dark Yolk Large White Eggs | not stated in listing | Large | 18 | white | Free run + Dark yolk (name) | $10.59 | — | $0.588 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00620580000483) |
| 503 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Free Run Eggs | not stated in listing | not stated | 12 | not stated | Free run | $7.29 | — | $0.608 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639332921) |
| 504 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | VITA | VITA - Free Run Eggs - Large | not stated in listing | Large | 12 | not stated | Free run | $7.45 | — | $0.621 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00056526000079) |
| 505 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Lovo | Lovo - Large Dark Yolk Eggs - Free Run | not stated in listing | Large | 12 | not stated | Free run + Dark yolk (name) | $7.45 | — | $0.621 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00061719065216) |
| 506 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Gold Egg | Gold Egg - White Eggs Large | not stated in listing | Large | 6 | white | None stated | $3.75 | — | $0.625 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00674959000109) |
| 507 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | VITA | VITA - Vita Organic Large Eggs | not stated in listing | Large | 18 | not stated | Organic | $11.25 | — | $0.625 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00056526528009) |
| 508 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Lovo | Lovo - Large Brown Organic Eggs | not stated in listing | Large | 18 | brown | Organic | $11.25 | — | $0.625 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00061719064400) |
| 509 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Lovo | Lovo - Large Size Eggs - Free Run | not stated in listing | Large | 6 | not stated | Free run | $3.75 | — | $0.625 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00061719060006) |
| 510 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Gold Egg | Gold Egg - Free Run Large Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.69 | — | $0.641 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00674959000086) |
| 511 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Western Family | Western Family - Organic Free Range Large Eggs | not stated in listing | Large | 12 | not stated | Organic | $8.45 | — | $0.704 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00062639332945) |
| 512 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | VITA | VITA - Organic Large Eggs | not stated in listing | Large | 12 | not stated | Organic | $8.75 | — | $0.729 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00056526520027) |
| 513 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Lovo | Lovo - Large Brown Organic Eggs | not stated in listing | Large | 12 | brown | Organic | $8.75 | — | $0.729 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00061719061102) |
| 514 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Rabbit River Farms | Rabbit River Farms - Organic Free Range Large Brown Eggs | not stated in listing | Large | 12 | brown | Organic | $9.35 | — | $0.779 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00620580000025) |
| 515 | Save-On-Foods | #4415 St James, 850 St James St, Winnipeg MB | Rabbit River | Rabbit River - Organic Extra Large Eggs Free Range | not stated in listing | Extra Large | 12 | not stated | Organic | $9.39 | — | $0.782 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/4415/categories/30919/search?take=100&skip=0 (sku 00620580000018) |
| 516 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Medium White Eggs | not stated in listing | Medium | 12 | white | None stated | $4.15 | — | $0.346 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639410131) |
| 517 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Large White Eggs Cello | not stated in listing | Large | 30 | white | None stated | $10.60 | — | $0.353 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639394981) |
| 518 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Large White Eggs | not stated in listing | Large | 12 | white | None stated | $4.35 | — | $0.362 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639410124) |
| 519 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Extra Large White Eggs | not stated in listing | Extra Large | 12 | white | None stated | $4.85 | — | $0.404 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639410117) |
| 520 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Large White Eggs 18 | not stated in listing | Large | 18 | white | None stated | $7.35 | — | $0.408 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639199784) |
| 521 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Sparks | Sparks - Extra Large Eggs White | not stated in listing | Extra Large | 18 | white | None stated | $7.45 | — | $0.414 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00068258009503) |
| 522 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Gold Egg | Gold Egg - Jumbo White Eggs | not stated in listing | Jumbo | 12 | white | None stated | $5.45 | — | $0.454 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00674959000093) |
| 523 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Gold Egg | Gold Egg - Omega 3 Large Eggs White | not stated in listing | Large | 18 | white | None stated + Omega-3 (name) | $8.39 | — | $0.466 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00674959000123) |
| 524 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Farmer's Finest | Farmer's Finest - Comfort Coop Large Eggs White | not stated in listing | Large | 12 | white | Enriched/Comfort/Cozy coop (as named) | $5.69 | — | $0.474 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00068258618422) |
| 525 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Large Brown Eggs | not stated in listing | Large | 12 | brown | None stated | $5.79 | — | $0.482 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639411572) |
| 526 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Gold Egg | Gold Egg - Grain Fed Large Eggs White | not stated in listing | Large | 12 | white | None stated | $6.09 | — | $0.507 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00674959000062) |
| 527 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Omega 3 Large Eggs | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.75 | — | $0.562 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639320966) |
| 528 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Gold Egg | Gold Egg - Omega 3 Large Brown Eggs | not stated in listing | Large | 12 | brown | None stated + Omega-3 (name) | $6.79 | — | $0.566 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00674959000031) |
| 529 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Gold Egg | Gold Egg - Omega Choice Eggs Large | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | $6.79 | — | $0.566 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00674959000055) |
| 530 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Rabbit River Farms | Rabbit River Farms - Free Run Dark Yolk Large White Eggs | not stated in listing | Large | 18 | white | Free run + Dark yolk (name) | $10.59 | — | $0.588 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00620580000483) |
| 531 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Free Run Eggs | not stated in listing | not stated | 12 | not stated | Free run | $7.35 | — | $0.613 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639332921) |
| 532 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Gold Egg | Gold Egg - White Eggs Large | not stated in listing | Large | 6 | white | None stated | $3.75 | — | $0.625 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00674959000109) |
| 533 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Farmer's Finest | Farmer's Finest - Free Range Large Eggs Brown | not stated in listing | Large | 12 | brown | Free range | $7.85 | — | $0.654 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00068258618309) |
| 534 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Western Family | Western Family - Free Range Brown Eggs, Large | not stated in listing | Large | 12 | brown | Free range | $7.85 | — | $0.654 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639332938) |
| 535 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Gold Egg | Gold Egg - Free Run Large Brown Eggs | not stated in listing | Large | 12 | brown | Free run | $7.95 | — | $0.662 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00674959000086) |
| 536 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | ONLY GOODNESS | ONLY GOODNESS - Organic Large Brown Eggs | not stated in listing | Large | 12 | brown | Organic | $8.85 | — | $0.738 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00062639368401) |
| 537 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Farmer's Finest | Farmer's Finest - Organic Large Eggs Brown | not stated in listing | Large | 12 | brown | Organic | $9.09 | — | $0.757 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00068258618507) |
| 538 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Rabbit River Farms | Rabbit River Farms - Organic Free Range Large Brown Eggs | not stated in listing | Large | 12 | brown | Organic | $9.35 | — | $0.779 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00620580000025) |
| 539 | Save-On-Foods | #6634 Heritage, 8855 MacLeod Trail SW, Calgary AB | Rabbit River | Rabbit River - Organic Extra Large Eggs Free Range | not stated in listing | Extra Large | 12 | not stated | Organic | $9.45 | — | $0.787 | 2026-10-03T04:07:09Z | https://storefrontgateway.saveonfoods.com/api/stores/6634/categories/30919/search?take=100&skip=0 (sku 00620580000018) |
| 540 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Canadian Harvest | Canadian Harvest Brown Eggs Large 12 Count | not stated in listing | Large | 12 | brown | None stated | not shown | — | $0.312 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 843779EA) |
| 541 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge Egg Farms White Eggs Tray Grade A Medium 30 Count | A (in name) | Medium | 30 | white | None stated | not shown | — | $0.320 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 582623EA) |
| 542 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments Specialty Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | None stated | not shown | — | $0.333 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 481673EA) |
| 543 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Large 30 Count | not stated in listing | Large | 30 | white | None stated | not shown | — | $0.333 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 627073EA) |
| 544 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Medium 12 Count | not stated in listing | Medium | 12 | white | None stated | not shown | — | $0.341 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 552023EA) |
| 545 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Shrink Large 30 Count | not stated in listing | Large | 30 | white | None stated | not shown | — | $0.343 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428489EA) |
| 546 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nutri | Nutri White Eggs Medium 30 Count | not stated in listing | Medium | 30 | white | None stated | not shown | — | $0.343 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 583841EA) |
| 547 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms White Eggs Overwrap Wire Basket Medium Value Size 30 Count | not stated in listing | Medium | 30 | white | None stated | not shown | — | $0.343 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 583269EA) |
| 548 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Sparks | Sparks White Eggs Medium Wrapped Tray 30 Count | not stated in listing | Medium | 30 | white | None stated | not shown | — | $0.343 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 595969EA) |
| 549 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Medium 12 Count | not stated in listing | Medium | 12 | white | None stated | not shown | — | $0.346 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 437808EA) |
| 550 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride Eggs White Eggs Medium 30 Count | not stated in listing | Medium | 30 | white | None stated | not shown | — | $0.346 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 591754EA) |
| 551 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments Eggs Large Value Size 18 Count | not stated in listing | Large | 18 | not stated | None stated | not shown | — | $0.348 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 507041EA) |
| 552 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Large 12 Count | not stated in listing | Large | 12 | white | None stated | not shown | — | $0.349 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 552025EA) |
| 553 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Large 12 Count | not stated in listing | Large | 12 | white | None stated | not shown | — | $0.349 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 437783EA) |
| 554 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Large 12 Count | not stated in listing | Large | 12 | white | None stated | not shown | — | $0.349 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1444809EA) |
| 555 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Medium 12 Count | not stated in listing | Medium | 12 | white | None stated | not shown | — | $0.349 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428523EA) |
| 556 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Large 18 Count | not stated in listing | Large | 18 | white | None stated | not shown | — | $0.349 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428524EA) |
| 557 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms White Eggs Large 30 Count | not stated in listing | Large | 30 | white | None stated | not shown | — | $0.350 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 613306EA) |
| 558 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Golden Valley | Golden Valley White Eggs Medium 30 Count | not stated in listing | Medium | 30 | white | None stated | not shown | — | $0.353 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 585652EA) |
| 559 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge White Eggs Grade A Large 12 Count | A (in name) | Large | 12 | white | None stated | not shown | — | $0.357 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 531480EA) |
| 560 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride White Eggs Large 30 Count | not stated in listing | Large | 30 | white | None stated | not shown | — | $0.363 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 940001EA) |
| 561 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Prana | Country Golden Brown Eggs Free Range Medium 12 Count | not stated in listing | Medium | 12 | brown | Free range | not shown | — | $0.383 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 843732EA) |
| 562 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Eggs Grade A Large 12 Count | A (in name) | Large | 12 | not stated | None stated | not shown | — | $0.383 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 37125EA) |
| 563 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Brown Eggs Large Value Size 30 Count | not stated in listing | Large | 30 | brown | None stated | not shown | — | $0.383 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 508228EA) |
| 564 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge Egg Farms White Eggs Grade A Extra Large Value Size 18 Count | A (in name) | Extra Large | 18 | white | None stated | not shown | — | $0.388 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 531477EA) |
| 565 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Prestige Club Pack Eggs Large Value Size 18 Count | not stated in listing | Large | 18 | not stated | None stated | not shown | — | $0.388 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 532525EA) |
| 566 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gerber's Farm | Gerber's Farm White Eggs Grade A Large 12 Count | A (in name) | Large | 12 | white | None stated | not shown | — | $0.391 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 861905EA) |
| 567 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge White Eggs Grade A Extra Large 12 Count | A (in name) | Extra Large | 12 | white | None stated | not shown | — | $0.399 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 531475EA) |
| 568 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Vanderwees | Vanderwees White Eggs Large 12 Count | not stated in listing | Large | 12 | white | None stated | not shown | — | $0.399 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 843761EA) |
| 569 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge Premium White Eggs Grade A Large Value Size 18 Count | A (in name) | Large | 18 | white | None stated | not shown | — | $0.405 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 531484EA) |
| 570 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Golden Valley | Golden Valley White Eggs Large 18 Count | not stated in listing | Large | 18 | white | None stated | not shown | — | $0.405 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 211149EA) |
| 571 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Daybreak Farms | Daybreak Farms White Eggs Large 12 Count | not stated in listing | Large | 12 | white | None stated | not shown | — | $0.407 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 861904EA) |
| 572 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gerber's Farm | Gerber's Farm White Eggs Grade A Extra Large 12 Count | A (in name) | Extra Large | 12 | white | None stated | not shown | — | $0.407 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 843763EA) |
| 573 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge Premium White Eggs Grade A Large 12 Count | A (in name) | Large | 12 | white | None stated | not shown | — | $0.416 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 521236EA) |
| 574 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Free Run Medium 24 Count | not stated in listing | Medium | 24 | white | Free run | not shown | — | $0.429 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428495EA) |
| 575 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | white | None stated | not shown | — | $0.432 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 552027EA) |
| 576 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Vanderwees Farms | Vanderwees Farms Eggs Large Family Pack 18 Count | not stated in listing | Large | 18 | not stated | None stated | not shown | — | $0.433 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 587195EA) |
| 577 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Natures Farm | Nature's Farm Eggs Omega-3 Free Run Large 30 Count | not stated in listing | Large | 30 | not stated | Free run + Omega-3 (name) | not shown | — | $0.440 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 985302EA) |
| 578 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments Brown Eggs Medium 12 Count | not stated in listing | Medium | 12 | brown | None stated | not shown | — | $0.441 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 437765EA) |
| 579 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge Brown Eggs Grade A Large Value Size 18 Count | A (in name) | Large | 18 | brown | None stated | not shown | — | $0.444 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 531488EA) |
| 580 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Longo's | Longo's White Eggs Enriched Coop Extra Large 18 Count | not stated in listing | Extra Large | 18 | white | Enriched/Comfort/Cozy coop (as named) | not shown | — | $0.444 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 13840EA) |
| 581 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Rochfort Bridge | Rochfort Bridge Fresh Eggs Large Value Size 18 Count | not stated in listing | Large | 18 | not stated | None stated | not shown | — | $0.444 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 848650EA) |
| 582 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Daybreak Farms | Daybreak Farms Brown Eggs Large 12 Count | not stated in listing | Large | 12 | brown | None stated | not shown | — | $0.449 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 861906EA) |
| 583 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Vita | Vita White Eggs Free Run Large Value Size 30 Count | not stated in listing | Large | 30 | white | Free run | not shown | — | $0.450 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 590351EA) |
| 584 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride White Eggs Large Value Size 18 Count | not stated in listing | Large | 18 | white | None stated | not shown | — | $0.454 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 460271EA) |
| 585 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg Golden D White Eggs Large Value Size 18 Count | not stated in listing | Large | 18 | white | None stated + Golden D/Vitamin D (name) | not shown | — | $0.455 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 318487EA) |
| 586 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge Egg Farms 747 Brand Eggs Grade A Jumbo 12 Count | A (in name) | Jumbo | 12 | not stated | None stated | not shown | — | $0.458 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 531474EA) |
| 587 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments Cozy Coop Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | Enriched/Comfort/Cozy coop (as named) | not shown | — | $0.458 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 840388EA) |
| 588 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Longo's | Longo's White Eggs Enriched Coop Large 12 Count | not stated in listing | Large | 12 | white | Enriched/Comfort/Cozy coop (as named) | not shown | — | $0.458 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 13845EA) |
| 589 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments Brown Eggs Large Carton 12 Count | not stated in listing | Large | 12 | brown | None stated | not shown | — | $0.458 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 437781EA) |
| 590 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | white | None stated | not shown | — | $0.458 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428511EA) |
| 591 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Super Bon-ee White Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | white | None stated | not shown | — | $0.458 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 870412EA) |
| 592 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Hartmann | Hartmann White Eggs Jumbo 12 Count | not stated in listing | Jumbo | 12 | white | None stated | not shown | — | $0.458 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 597856EA) |
| 593 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride White Eggs Extra Large Value Size 18 Count | not stated in listing | Extra Large | 18 | white | None stated | not shown | — | $0.461 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 870434EA) |
| 594 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Eyking Farm | Eyking Farm Eggs Extra Large Value Size 18 Count | not stated in listing | Extra Large | 18 | not stated | None stated | not shown | — | $0.461 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 870470EA) |
| 595 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nature's Farm Smart Egg | Nature's Farm Smart Egg Grade A Large Free Run Omega3 Eggs 18 Count | A (in name) | Large | 18 | not stated | Free run + Omega-3 (name); Smart Eggs (name) | not shown | — | $0.461 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 985297EA) |
| 596 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge Brown Eggs Grade A Large 12 Count | A (in name) | Large | 12 | brown | None stated | not shown | — | $0.466 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 531481EA) |
| 597 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Brown Eggs Large 12 Count | not stated in listing | Large | 12 | brown | None stated | not shown | — | $0.466 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 863244EA) |
| 598 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Newfoundland Eggs | Newfoundland Eggs Large Value Pack 18 Count | not stated in listing | Large | 18 | not stated | None stated | not shown | — | $0.466 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 575076EA) |
| 599 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Vita | Vita Original White Eggs Free Run Canada A Large Value Size 18 Count | A (in name) | Large | 18 | white | Free run | not shown | — | $0.472 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 507582EA) |
| 600 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | white | None stated | not shown | — | $0.472 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 437795EA) |
| 601 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge Egg Farms Brown Eggs Grade A Extra Large 12 Count | A (in name) | Extra Large | 12 | brown | None stated | not shown | — | $0.474 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 531476EA) |
| 602 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | GoldEgg White Eggs Omega 3 Choice Large 12 Count | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | not shown | — | $0.474 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 169057EA) |
| 603 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Eyking Farm | Eyking Farm Eggs Jumbo Value Size 12 Count | not stated in listing | Jumbo | 12 | not stated | None stated | not shown | — | $0.474 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 870469EA) |
| 604 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride White Eggs Jumbo 12 Count | not stated in listing | Jumbo | 12 | white | None stated | not shown | — | $0.482 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 870429EA) |
| 605 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Delong Farms | Delong Farms Brown Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | brown | None stated | not shown | — | $0.482 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 870212EA) |
| 606 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Nestlaid Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | Nest Laid (as named) | not shown | — | $0.482 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 312452EA) |
| 607 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Rochfort Bridge | Rochfort Bridge Fresh Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | None stated | not shown | — | $0.482 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 848669EA) |
| 608 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Rochfort Bridge | Rochfort Bridge Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | not stated | None stated | not shown | — | $0.482 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 848648EA) |
| 609 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Super Bon-ee Eggs Double Yolk Extra Large 12 Count | not stated in listing | Extra Large | 12 | not stated | None stated + Double yolk (name) | not shown | — | $0.491 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 532531EA) |
| 610 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maple Ridge | Maritime Pride Brown Eggs Jumbo 12 Count | not stated in listing | Jumbo | 12 | brown | None stated | not shown | — | $0.491 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 454956EA) |
| 611 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Newfoundland Eggs | Newfoundland Eggs Brown Eggs Large 12 Count | not stated in listing | Large | 12 | brown | None stated | not shown | — | $0.491 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 405152EA) |
| 612 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo Brown Eggs Large 12 Count | not stated in listing | Large | 12 | brown | None stated | not shown | — | $0.499 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428510EA) |
| 613 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Ultra Extra Large 12 Count | not stated in listing | Super/Ultra XL (as named) | 12 | white | None stated | not shown | — | $0.499 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428496EA) |
| 614 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Longo's | Longo's Brown Eggs Enriched Coop Large 12 Count | not stated in listing | Large | 12 | brown | Enriched/Comfort/Cozy coop (as named) | not shown | — | $0.499 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 13844EA) |
| 615 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nutri | Nutri Comfort Farm White Eggs Large 12 Count | not stated in listing | Large | 12 | white | Enriched/Comfort/Cozy coop (as named) | not shown | — | $0.499 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 681777EA) |
| 616 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Nature's Best Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | None stated | not shown | — | $0.499 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 863607EA) |
| 617 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gamble Farm | Gamble Farm White Eggs Free Run 12 Count | not stated in listing | not stated | 12 | white | Free run | not shown | — | $0.499 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 605820EA) |
| 618 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Perfect Sunny Side Up Large 12 Count | not stated in listing | Large | 12 | white | None stated | not shown | — | $0.499 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428535EA) |
| 619 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gamble Farm | Gamble Farm White Eggs Free Run 12 Count | not stated in listing | not stated | 12 | white | Free run | not shown | — | $0.499 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 605706EA) |
| 620 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg Omega 3 White Eggs Large Value Pack 18 Count | not stated in listing | Large | 18 | white | None stated + Omega-3 (name) | not shown | — | $0.499 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 298433EA) |
| 621 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gamble Farm | Gamble Farm Brown Eggs Free Run Medium Value Size 30 Count | not stated in listing | Medium | 30 | brown | Free run | not shown | — | $0.500 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 605817EA) |
| 622 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | MARITIME PRIDE EGGS | Maritime Pride Solstice Eggs White Large 12 Count | not stated in listing | Large | 12 | white | None stated | not shown | — | $0.507 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 964791EA) |
| 623 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg White Eggs Enriched Coop Large 12 Count | not stated in listing | Large | 12 | white | Enriched/Comfort/Cozy coop (as named) | not shown | — | $0.516 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 627148EA) |
| 624 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Newfoundland Eggs | Newfoundland Brown Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | brown | None stated | not shown | — | $0.516 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 405153EA) |
| 625 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo Brown Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | brown | None stated | not shown | — | $0.524 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428533EA) |
| 626 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | not shown | — | $0.524 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 329064EA) |
| 627 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nature's Farm | Nature's Farm Smart Eggs Omega 3 Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | not stated | Free run + Omega-3 (name); Smart Eggs (name) | not shown | — | $0.524 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 949009EA) |
| 628 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Vita Eggs | Vita Eggs Omega 3 Eggs Grade A Large 12 Count | A (in name) | Large | 12 | not stated | None stated + Omega-3 (name) | not shown | — | $0.524 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 158686EA) |
| 629 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride Omega 3 White Eggs Large 6 Count | not stated in listing | Large | 6 | white | None stated + Omega-3 (name) | not shown | — | $0.525 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 79606EA) |
| 630 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Gray Ridge Egg Farms | Gray Ridge White Eggs Grade A Large 6 Count | A (in name) | Large | 6 | white | None stated | not shown | — | $0.532 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 191403EA) |
| 631 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Newfoundland Eggs | Newfoundland Eggs Jumbo 12 Count | not stated in listing | Jumbo | 12 | not stated | None stated | not shown | — | $0.532 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 404616EA) |
| 632 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nutri | Nutri White Eggs Free Run Hens Large 12 Count | not stated in listing | Large | 12 | white | Free run | not shown | — | $0.537 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 683193EA) |
| 633 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Daybreak Farms | Daybreak Farms Brown Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | brown | Free run | not shown | — | $0.541 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 861907EA) |
| 634 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride Brown Eggs Large 6 Count | not stated in listing | Large | 6 | brown | None stated | not shown | — | $0.548 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 569399EA) |
| 635 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg Omega 3 White Eggs Large 12 Count | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | not shown | — | $0.549 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 150352EA) |
| 636 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride Omega 3 White Eggs Grade A Large 12 Count | A (in name) | Large | 12 | white | None stated + Omega-3 (name) | not shown | — | $0.549 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 870433EA) |
| 637 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Brown Eggs Large 12 Count | not stated in listing | Large | 12 | brown | None stated + Omega-3 (name) | not shown | — | $0.549 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 549750EA) |
| 638 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Britestn | Britestone Eggs Grain Fed Large Value Size 18 Count | not stated in listing | Large | 18 | not stated | None stated | not shown | — | $0.555 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 911947EA) |
| 639 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride Brown Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | brown | Free run | not shown | — | $0.557 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 459654EA) |
| 640 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Golden Valley | Golden Valley Born 3 Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | None stated + Born 3 (name) | not shown | — | $0.557 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 506884EA) |
| 641 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg White Eggs Large 6 Count | not stated in listing | Large | 6 | white | None stated | not shown | — | $0.565 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 156252EA) |
| 642 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms White Eggs Large 6 Count | not stated in listing | Large | 6 | white | None stated | not shown | — | $0.565 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 532530EA) |
| 643 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg Omega 3 White Eggs Grade A Extra Large 12 Count | A (in name) | Extra Large | 12 | white | None stated + Omega-3 (name) | not shown | — | $0.566 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 169061EA) |
| 644 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Comfort Farm Large 12 Count | not stated in listing | Large | 12 | white | Enriched/Comfort/Cozy coop (as named) | not shown | — | $0.566 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428490EA) |
| 645 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Double Yolk Extra Large 12 Count | not stated in listing | Extra Large | 12 | white | None stated + Double yolk (name) | not shown | — | $0.566 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428512EA) |
| 646 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Naturegg | Burnbrae Farms Naturegg Omega Plus Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | None stated + Omega-3 (name) | not shown | — | $0.566 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 510704EA) |
| 647 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Select Large 12 Count | not stated in listing | Large | 12 | white | None stated | not shown | — | $0.566 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428527EA) |
| 648 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Conestoga Farms | Conestoga Farms Omega 3 Eggs Free Run Large Value Size 18 Count | not stated in listing | Large | 18 | not stated | Free run + Omega-3 (name) | not shown | — | $0.577 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 947433EA) |
| 649 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride White Eggs Free Run Hens Large 6 Count | not stated in listing | Large | 6 | white | Free run | not shown | — | $0.582 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 569411EA) |
| 650 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | white | Free run | not shown | — | $0.583 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 552028EA) |
| 651 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Conestoga Farms | Conestoga Farms Omega 3 White Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | white | Free run + Omega-3 (name) | not shown | — | $0.583 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 698647EA) |
| 652 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | white | Free run | not shown | — | $0.583 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428516EA) |
| 653 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments Omega 3 White Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | white | Free run + Omega-3 (name) | not shown | — | $0.583 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 552029EA) |
| 654 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Longo's | Longo's Omega-3 White Eggs Large 12 Count | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | not shown | — | $0.583 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 19186EA) |
| 655 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments White Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | white | Free run | not shown | — | $0.583 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 848792EA) |
| 656 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | LOVO INC | Lovo Brown Eggs Free Run Medium 12 Count | not stated in listing | Medium | 12 | brown | Free run | not shown | — | $0.583 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428517EA) |
| 657 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | LOVO INC | Lovo Omega 3 White Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | white | Free run + Omega-3 (name) | not shown | — | $0.583 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428526EA) |
| 658 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Vita | Vita Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | not stated | Free run | not shown | — | $0.583 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 505037EA) |
| 659 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo White Eggs Dark Yolk Free Run Large 12 Count | not stated in listing | Large | 12 | white | Free run + Dark yolk (name) | not shown | — | $0.608 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1429598EA) |
| 660 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Britestn | Britestone White Eggs Super Large 12 Count | not stated in listing | Super/Ultra XL (as named) | 12 | white | None stated | not shown | — | $0.608 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 911423EA) |
| 661 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg Omega 3 White Eggs Grade A Medium 6 Count | A (in name) | Medium | 6 | white | None stated + Omega-3 (name) | not shown | — | $0.615 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 191415EA) |
| 662 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maritime Pride | Maritime Pride Omega 3 White Eggs Large 6 Count | not stated in listing | Large | 6 | white | None stated + Omega-3 (name) | not shown | — | $0.615 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 569386EA) |
| 663 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Naturegg Omega 3 Eggs Grade A Medium 6 Count | A (in name) | Medium | 6 | not stated | None stated + Omega-3 (name) | not shown | — | $0.615 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 532541EA) |
| 664 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Naturegg Eggs Free Range Large 12 Count | not stated in listing | Large | 12 | not stated | Free range | not shown | — | $0.616 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 792844EA) |
| 665 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Countryside Farms | Countryside Farms Brown Eggs Free Range Hens Large 12 Count | not stated in listing | Large | 12 | brown | Free range | not shown | — | $0.616 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 431428EA) |
| 666 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Conestoga Farms | Conestoga Farms Omega 3 Brown Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | brown | Free run + Omega-3 (name) | not shown | — | $0.624 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 164099EA) |
| 667 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Longo's | Longo's Brown Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | brown | Free run | not shown | — | $0.624 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 19185EA) |
| 668 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments | Compliments Omega 3 White Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | white | Free run + Omega-3 (name) | not shown | — | $0.624 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 848791EA) |
| 669 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Sunshine Valley | Sunshine Valley Organic Eggs Free Range Medium 12 Count | not stated in listing | Medium | 12 | not stated | Organic | not shown | — | $0.624 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 468682EA) |
| 670 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo Brown Eggs Free Run Large 6 Count | not stated in listing | Large | 6 | brown | Free run | not shown | — | $0.632 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428534EA) |
| 671 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | LOVO | Lovo White Eggs Free Run Large 6 Count | not stated in listing | Large | 6 | white | Free run | not shown | — | $0.632 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428518EA) |
| 672 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Conestoga Farms | Conestoga Farms Brown Eggs Free Range Medium 12 Count | not stated in listing | Medium | 12 | brown | Free range | not shown | — | $0.632 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 698645EA) |
| 673 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg Brown Eggs Free Run Large 12 Count | not stated in listing | Large | 12 | brown | Free run | not shown | — | $0.632 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 150353EA) |
| 674 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Country Golden | Country Golden Yolks Brown Eggs Free Range Large 12 Count | not stated in listing | Large | 12 | brown | Free range | not shown | — | $0.632 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 843775EA) |
| 675 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Natures Farm | Natures Farm Organic Omega 3 Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | Organic + Omega-3 (name) | not shown | — | $0.632 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 513910EA) |
| 676 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Star | Star Organic Eggs Free Range Large 18 Count | not stated in listing | Large | 18 | not stated | Organic | not shown | — | $0.633 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 21127EA) |
| 677 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nature's Farm | Nature's Farm Organic Omega 3 Eggs Grade A Large Value Size 30 Count | A (in name) | Large | 30 | not stated | Organic + Omega-3 (name) | not shown | — | $0.633 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 985299EA) |
| 678 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Vita | Vita Organic Eggs Large 18 Count | not stated in listing | Large | 18 | not stated | Organic | not shown | — | $0.644 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 21506EA) |
| 679 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Conestoga Brand | Conestoga Brand Eggs Free Range Large 12 Count | not stated in listing | Large | 12 | not stated | Free range | not shown | — | $0.649 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 784540EA) |
| 680 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nutri | Nutri Brown Eggs Free Range Hens Large 12 Count | not stated in listing | Large | 12 | brown | Free range | not shown | — | $0.649 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 683194EA) |
| 681 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Burnbrae Farms | Burnbrae Farms Naturegg Eggs Free Run Grade A Large 6 Count | A (in name) | Large | 6 | not stated | Free run | not shown | — | $0.665 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 532540EA) |
| 682 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments Organic | Compliments Organic Brown Eggs Free Range Medium 12 Count | not stated in listing | Medium | 12 | brown | Organic | not shown | — | $0.666 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 485350EA) |
| 683 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Cokk's Dairy Farm | Coldspring Farm Brown Eggs Free Range Large 12 Count | not stated in listing | Large | 12 | brown | Free range | not shown | — | $0.682 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 870477EA) |
| 684 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Britestn | Britestone Brown Eggs Super Large 12 Count | not stated in listing | Super/Ultra XL (as named) | 12 | brown | None stated | not shown | — | $0.691 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 911424EA) |
| 685 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo Organic Brown Eggs Medium 18 Count | not stated in listing | Medium | 18 | brown | Organic | not shown | — | $0.694 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1444810EA) |
| 686 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg Organic Brown Eggs Large 12 Count | not stated in listing | Large | 12 | brown | Organic | not shown | — | $0.708 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 169060EA) |
| 687 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | GoldEgg | Gold Egg Organic Brown Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | brown | Organic | not shown | — | $0.708 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 169055EA) |
| 688 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments Organic | Compliments Organic Brown Eggs Free Range Grade A Large 12 Count | A (in name) | Large | 12 | brown | Organic | not shown | — | $0.708 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 732323EA) |
| 689 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Green Valley Farms | Green Valley Farms Brown Eggs Free Range Medium 12 Count | not stated in listing | Medium | 12 | brown | Free range | not shown | — | $0.708 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 947855EA) |
| 690 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Vita | Vita Organic Eggs Large 12 Count | not stated in listing | Large | 12 | not stated | Organic | not shown | — | $0.708 | 2026-10-03T04:08:33Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 173011EA) |
| 691 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Sunshine Valley | Sunshine Valley Organic Eggs Free Range Large 12 Count | not stated in listing | Large | 12 | not stated | Organic | not shown | — | $0.741 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 468683EA) |
| 692 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Sunshine Valley | Sunshine Valley Organic Eggs Free Range Extra Large 12 Count | not stated in listing | Extra Large | 12 | not stated | Organic | not shown | — | $0.741 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 468688EA) |
| 693 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Conestoga Farms | Conestoga Farms Organic Brown Eggs Extra Large 6 Count | not stated in listing | Extra Large | 6 | brown | Organic | not shown | — | $0.748 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 439936EA) |
| 694 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Nutri | Nutri Organic Brown Eggs Free Range Hens Large 6 Count | not stated in listing | Large | 6 | brown | Organic | not shown | — | $0.758 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 584126EA) |
| 695 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Compliments Organic | Compliments Organic Brown Eggs Free Range Large 12 Count | not stated in listing | Large | 12 | brown | Organic | not shown | — | $0.774 | 2026-10-03T04:08:31Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 552035EA) |
| 696 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Lovo | Lovo Organic Brown Eggs Medium 12 Count | not stated in listing | Medium | 12 | brown | Organic | not shown | — | $0.774 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1449222EA) |
| 697 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Avalon Organics | Avalon Organics Brown Eggs Free Range Large 12 Count | not stated in listing | Large | 12 | brown | Organic | not shown | — | $0.824 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 861908EA) |
| 698 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Avalon Organics | Avalon Organics Organic Brown Eggs Extra Large 12 Count | not stated in listing | Extra Large | 12 | brown | Organic | not shown | — | $0.833 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 843769EA) |
| 699 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | LOVO | Lovo Organic Brown Eggs Large 6 Count | not stated in listing | Large | 6 | brown | Organic | not shown | — | $0.915 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 1428509EA) |
| 700 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maple Hill Farms | Maple Hill Farms Organic Eggs Free Range Extra Large 12 Count | not stated in listing | Extra Large | 12 | not stated | Organic | not shown | — | $0.916 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 861903EA) |
| 701 | Voilà | online; no postal code set ('Default Region 1', DEF_REG01) | Maple Hill Farms | Maple Hill Farms Organic Eggs Free Range Large 12 Count | not stated in listing | Large | 12 | not stated | Organic | not shown | — | $0.916 | 2026-10-03T04:08:32Z | https://voila.ca/categories/dairy-eggs/eggs/whole-eggs/WEB39215426 (retailerProductId 843748EA) |
| 702 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Great Value Medium White 30 Eggs | not stated in listing | Medium | 30 | white | None stated | $9.18 | — | $0.306 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Great-Value-Medium-White-30-Eggs/29JQFZYPVSQ1 |
| 703 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Great Value Large 12 Eggs | not stated in listing | Large | 12 | not stated | None stated | $3.93 | — | $0.328 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Great-Value-Large-12-Eggs/10052944 |
| 704 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Gray Ridge Medium White 60 Eggs | not stated in listing | Medium | 60 | white | None stated | $21.46 | — | $0.358 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Gray-Ridge-Medium-White-60-Eggs/3IH8YI1WOI5C |
| 705 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Great Value XL White 12 Eggs | not stated in listing | Extra Large | 12 | white | None stated | $4.63 | — | $0.386 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Great-Value-XL-White-12-Eggs/6000191273494 |
| 706 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Gray Ridge Premium Large White 18 Eggs | not stated in listing | Large | 18 | white | None stated | $6.98 | — | $0.388 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Gray-Ridge-Premium-Large-White-18-Eggs/6000191268613 |
| 707 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Gray Ridge Large Brown 18 Eggs | not stated in listing | Large | 18 | brown | None stated | $7.24 | — | $0.402 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Gray-Ridge-Large-Brown-18-Eggs/6000191268641 |
| 708 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Gray Ridge Super 747 Jumbo 12 Eggs | not stated in listing | Jumbo | 12 | not stated | None stated | $5.38 | — | $0.448 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Gray-Ridge-Super-747-Jumbo-12-Eggs/6000191268591 |
| 709 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | GoldEgg Golden D Vitamin D Enriched Large 18 Eggs | not stated in listing | Large | 18 | not stated | None stated + Golden D/Vitamin D (name) | $8.98 | — | $0.499 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/GoldEgg-Golden-D-Vitamin-D-Enriched-Large-18-Eggs/6000196823375 |
| 710 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | GoldEgg Free Run Large White 30 Eggs | not stated in listing | Large | 30 | white | Free run | $14.98 | — | $0.499 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/GoldEgg-Free-Run-Large-White-30-Eggs/31FWPJLZ3WHE |
| 711 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Great Value Omega-3 Large White 12 Eggs | not stated in listing | Large | 12 | white | None stated + Omega-3 (name) | $6.93 | $6.22 (Rollback (was $6.93); no end date shown) | $0.518 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Great-Value-Omega-3-Large-White-12-Eggs/6000196968682 |
| 712 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Conestoga Farms Free Run Omega3 Large 18 Eggs | not stated in listing | Large | 18 | not stated | Free run + Omega-3 (name) | $9.98 | — | $0.554 | 2026-10-03T04:09:50Z | https://www.walmart.ca/en/ip/Conestoga-Farms-Free-Run-Omega3-Large-18-Eggs/15SGVF892XRR |
| 713 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Conestoga Farms Free Range Medium Brown 12 Eggs | not stated in listing | Medium | 12 | brown | Free range | $6.98 | — | $0.582 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Conestoga-Farms-Free-Range-Medium-Brown-12-Eggs/6000196403932 |
| 714 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | GoldEgg Free Run Large 12 Eggs | not stated in listing | Large | 12 | not stated | Free run | $7.08 | — | $0.590 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/GoldEgg-Free-Run-Large-12-Eggs/6000196823370 |
| 715 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Conestoga Farms Free Run Omega-3 Large Brown 12 Eggs | not stated in listing | Large | 12 | brown | Free run + Omega-3 (name) | $7.28 | — | $0.607 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Conestoga-Farms-Free-Run-Omega-3-Large-Brown-12-Eggs/6000197453383 |
| 716 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Conestoga Farms Free Run Omega-3 Large White 12 Eggs | not stated in listing | Large | 12 | white | Free run + Omega-3 (name) | $7.43 | — | $0.619 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Conestoga-Farms-Free-Run-Omega-3-Large-White-12-Eggs/6000197318280 |
| 717 | Walmart | store 1061 (page postal code L5V 2N6, Mississauga ON) |  | Great Value Organic Free Run Large Brown 12 Eggs | not stated in listing | Large | 12 | brown | Organic | $7.88 | — | $0.657 | 2026-10-03T04:09:29Z | https://www.walmart.ca/en/ip/Great-Value-Organic-Free-Run-Large-Brown-12-Eggs/6000196119460 |

Excluded from the analysis but kept in `all_rows.csv`: 101 non-shell or non-hen-egg items, such as liquid whites, hard-boiled, pickled, quail, duck, kits, a towel set named "Duck Egg" and an egg-ring display. Also excluded: shell-egg listings under 6 eggs or with no count printed, namely Rabbit River "Free Range Organic Eggs Large Size" listed as "2 ea" at $5.99 (Loblaws #7155), Giant Tiger "Large Brown Eggs" and "Jumbo Eggs" with no count in the title.

## Appendix — recalls (DO NOT USE ON AIR)

Recalls were not researched for this price file. None are cited.

## UNVERIFIED / DO-NOT-USE

- **Voilà region.** Voilà prices were captured with no postal code set. The page reports "Default Region 1" (DEF_REG01). The city/region these prices apply to is not resolved, and promotional fields were not returned. Do not attribute Voilà prices to a named city. Treat any Voilà sale status as unknown.
- **Giant Tiger store pricing.** gianttiger.com product JSON prices were read with no store selected, and listings are tagged `in_store_only:true`. Prices may differ in store. The listing "Nutri Large White Eggs, 18-Pack" at $3.39 (handle `oeufs-famiale-18`) has no province tag and is an outlier ($0.188/egg). It is excluded from rankings. Confirm it in a store before any use.
- **Save-On-Foods #1982.** The gateway lists store 1982 as type "Corporate", shopping mode "planning" only, at the head-office address. Its prices are identical to store #2242 (Langley-Downtown). Use #2242/#6634/#4415 when naming a shoppable store.
- **Costco.** Only one Same-Day product (Kirkland Signature Free Run Large Eggs 24 ct, $10.20, L5V 2N6) could be read. The Same-Day search and egg collection pages are JavaScript-only and showed no products. Warehouse shelf prices for Costco eggs were **not** captured. costco.ca's online catalogue lists no shell eggs. Same-Day prices may differ from warehouse prices. No statement about that was found on the page, so do not compare Same-Day with warehouse prices.
- **Walmart.** 4 searches ("extra large eggs", "gray ridge eggs", "goldegg eggs", "pasture raised eggs") were redirected to `walmart.ca/blocked` and are missing. No Walmart free-range listing was found among the searches that loaded. That is not evidence that none is sold.
- **Metro.** One store only (Metro Devonshire, Windsor ON). Metro Quebec, Super C and Food Basics were not captured.
- **Loblaw coverage.** Search-based. Each store's results depend on the search terms used, so items not returned by 42 terms may exist. Some names omit size or count. Rabbit River "Free Range Organic Eggs Large Size" shows "2 ea" at $5.99 (Loblaws #7155), which looks like a data entry and should not be used. The Rowe Farms Green Valley Omega 3 comparison price in the API ($6.49/ea) is inconsistent with its 12-count; we computed our own $/egg.
- **EFC producer-price and cost-of-production tables.** Only Tableau preview images could be read. The CSV export returned 404, and the preview's snapshot date is unknown. The second province column in the producer-price image (values 43.80 → 44.40 per 15-dozen box, i.e. $2.92 → $2.96 per dozen from week 17 of 2026) has no visible header and **is not attributed** to any province here. Egg Farmers of Alberta's own page still shows the 2 Nov 2025 price ($2.920).
- **Other provinces' farm-gate prices** (Ontario / Egg Farmers of Ontario, Quebec / FPOQ, Saskatchewan, Manitoba, Atlantic boards) were not found on the boards' own sites in this pass. `manitobaegg.ca` and `eggfarmersofns.ca` did not connect (curl status 000). `fpcc-cpac.gc.ca` did not connect. Unverified. Do not state them.
- **Search-engine pointers.** A WebSearch summary claiming "$2.69 per dozen in 2023" for Quebec came from a search snippet, not an opened page. Do not use it.
- **Retail–farm gap.** Do not present the difference between retail and farm-gate prices as a retailer, grader or farmer margin. No cost data were collected.
- **Brand ownership.** "Only Goodness" is treated as a Save-On (Pattison) private label because its UPC (00062639368401) uses the same 062639 company prefix as Western Family items. Ownership is not confirmed from a company page. "Longo's" is treated as private label of the Longo's banner. Unverified as to current corporate ownership in this file.
- **Sale end dates** for Loblaw items with type SPECIAL but no was-price (e.g. Alderwood Farms Pasture-Raised Eggs $7.99 at Loblaws #1032, expiry 2026-10-07) are API fields. No regular price is known.
---

# Canadian egg industry: the documented record, 2023–2026 (tier a/b only)

Prepared 3 Oct 2026. Every source in this file was opened on 3 Oct 2026 unless the source register says otherwise.

**Scope.** This file covers:
- Statistics Canada production, layers and per-capita availability
- Egg Farmers of Canada (EFC) annual reports for 2023–2025
- federal quota decisions (FPCC prior approvals, and the quota regulations as amended in the Canada Gazette)
- shell-egg trade (HS 0407) by country
- the over-quota tariff and TRQ use
- the 2025 U.S. shortage, labelled U.S.
- the 2025–2026 U.S.–Canada dispute and Bill C-202
- legal and competition items
- retailer and restaurant cage-free commitments, in the companies' own words, against the dated record
- named surveys

**House rules applied:**
- There are no health, nutrition or food-safety claims anywhere in the body of this file.
- Disease wording and recalls appear only in Appendix R, which is "DO NOT USE ON AIR".
- Animal-welfare items are stated only as what a code, company or regulator literally says.
- Legal items are labelled as allegation, settlement, order and so on.
- U.S. data is labelled **[U.S.]**.

**Tiers:**
- (a) primary
- (b) named outlet with byline and date
- (c) flag only, never a sole source
- (d) named survey with publisher, date and method

**How pages were opened.** curl through the agent proxy worked for:
- statcan.gc.ca (with retries)
- laws-lois.justice.gc.ca and gazette.gc.ca
- cbsa-asfc.gc.ca, international.gc.ca and eics-scei.gc.ca
- agriculture.canada.ca
- eggfarmers.ca, parl.ca, ustr.gov, whitehouse.gov, justice.gov and data.bls.gov
- cbc.ca, globalnews.ca and newswire.ca
- the company sites listed below

canada.ca (FPCC) refused curl ("Empty reply from server"). Its decisions page was read with **WebFetch (WF)**. The FPCC decision-letter PDFs were downloaded by WebFetch and their text was then extracted locally. Three company pages refused both curl and WF with HTTP 403: sobeyssbreport.com, mcdonalds.com/ca, and retail-insider.com (a bot check). For Sobeys and McDonald's, the **Internet Archive (Wayback) copy of the company's own page** was opened instead, and is labelled as such.

---

## 0. Key findings (each sourced below)

1. **Production and layers hit records in 2025 (StatCan).**
   - 2025 egg production was **997,203 thousand dozen**, up from 876,348 thousand dozen in 2023.
   - The average number of layers was **40,525 thousand** in 2025, up from 35,581 thousand in 2023.
   - Monthly, layers reached **43,347 thousand in April 2026**, the latest months being Apr–May 2026.
   - Source: A1, A2.
2. **Per-capita availability rose in 2025.**
   - StatCan "food available": **16.04 kg/person** in 2025, against 15.00 kg in 2023 (A3).
   - AAFC's table gives **22.53 dozen/person** in 2025, against 21.06 dozen in 2023 (A4).
   - EFC's 2025 report says "Canadians eat an average of 259 eggs per year", citing AAFC's 2024 figure (A10).
3. **The federal quota grew 26% in three years, but part of that is a reclassification.**
   - The sum of provincial limits to federal quotas was 791,744,781 dozen for 2023 and **997,622,922 dozen for 2026**.
   - The separate "egg for processing" quota (40,273,176 dozen in 2024) was **repealed** for 2025 by SOR/2024-287. Part of the 2025 jump is therefore a reclassification.
   - Every change was approved by the National Farm Products Council (FPCC) "after being satisfied that they are necessary for the implementation of the marketing plan".
   - Source: A12–A15, A17.
4. **No hen shell eggs went to the U.S. from Jan 2023 to Jul 2026.** Canada's exports of fresh hen eggs in shell (HS 0407.21) to the United States were **zero** in every month. The only recorded destinations were St. Pierre and Miquelon (PM) and "FR" (A7). The AAFC spokesperson quote below confirms this, via CBC (B1).
5. **Imports of hen shell eggs all came from the U.S.**
   - Effectively all imports came from the **United States**. The exception was 3 dozen from Mexico in 2024.
   - Volumes: 46.1 million dozen in 2023, 60.2 million in 2024, 43.6 million in 2025, and 13.0 million in Jan–Jul 2026 (A6).
   - The declared customs value of **breaking eggs** averaged **$7.42/dozen in 2025**, against $3.43 in 2024 and $2.44 in Jan–Jul 2026. These are our computations from customs values, not retail prices.
6. **Supplementary import permits for breaking eggs dropped to zero in 2026.**
   - These are import permits issued beyond the trade-agreement TRQs, from Global Affairs data.
   - 2023: 18,463,645 dozen. 2024: 29,213,408. 2025: 20,065,801.
   - **2026 to 2 Oct: 0** (A20).
7. **The over-quota tariff did not change, 2025 to 2026.** Fresh hen eggs over the access commitment pay **"163.5% but not less than 79.9¢/dozen"** under the Customs Tariff 2025 and 2026, item 0407.21.20 (A18, A19).
8. **Bill C-202 is law.**
   - It received royal assent on **26 June 2025** (S.C. 2025, c. 1).
   - It bars the Foreign Affairs minister from any trade commitment that would increase the TRQ, or reduce the over-quota tariff, on "dairy products, poultry or eggs" (A21, A22).
   - The U.S. 2026 trade actions under Section 338 name **dairy**, not eggs, in their text (A24–A26) [U.S.].
9. **[U.S.] The U.S. retail egg price peaked in March 2025.** The U.S. average for Grade A large eggs was **$6.227/dozen (USD) in March 2025**, and **$2.272 in Aug 2026** (BLS, A29). For the same months, StatCan's Canadian average retail price for "Eggs, 1 dozen" was $4.92 (Mar 2025) and $4.95 (Jul 2026), in CAD (A5). The two currencies differ, and this is not a like-for-like comparison.
10. **The 2016 "cage-free by end of 2025" pledges, against the companies' own latest numbers.** The 2016 pledge came from the RCC grocers (Loblaw, Metro, Sobeys, Walmart Canada). Other chains made similar pledges.

    | Company | Latest own figure | Source |
    |---|---|---|
    | Loblaw | free-run/free-range ≈ **18%** of 2025 category sales | A31 |
    | Sobeys | **20%** of fiscal-2025 shell-egg sales "were cage-free" | A36, Wayback copy |
    | Metro | cage-free **13.7%** of 2025 shell-egg sales | A38 |
    | Walmart Canada | ≈ **9%** in calendar 2024 | A39 |
    | Costco Canada | **22.6%** in FY25 | A40 |
    | RBI, all brands in Canada (incl. Tim Hortons) | **27%** at end-2025 | A41 |
    | McDonald's Canada | "100% Canadian free-run eggs" for McMuffin, McGriddles and Bagel sandwiches, announced 3 Jun 2024 | A42, Wayback copy |
11. **No Canadian enforcement action on eggs was found.** We found no Competition Bureau decision, court ruling or Canadian class action involving egg companies or egg pricing, 2023–2026. The only egg-pricing enforcement found is **[U.S.]**: the DOJ complaint and proposed settlements of 30 Jun 2026 against three U.S. producers, which are allegations with settlements pending court approval (A30).

---

## 1. Source register

| ID | Source | Tier | URL opened | Page's own date | Method / note |
|---|---|---|---|---|---|
| A1 | Statistics Canada, Table 32-10-0119-01 "Production and disposition of eggs, annual" | a | https://www150.statcan.gc.ca/n1/tbl/csv/32100119-eng.zip (table page https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210011901) | released 2026-05-27; data 1920–2025 | curl, 3 Oct 2026 |
| A2 | Statistics Canada, Table 32-10-0121-01 "Production and disposition of eggs, monthly" | a | https://www150.statcan.gc.ca/n1/tbl/csv/32100121-eng.zip | released 2026-07-31; data to 2026-05 | curl |
| A3 | Statistics Canada, Table 32-10-0054-01 "Food available in Canada" | a | https://www150.statcan.gc.ca/n1/tbl/csv/32100054-eng.zip | released 2026-05-28; data to 2025 | curl |
| A4 | AAFC, "Protein disappearance and demand by species" (table of food available per person; eggs in dozens) | a | https://agriculture.canada.ca/en/sector/animal-industry/protein-disappearance-and-demand-species | Date modified 2026-05-28 | curl (second try). The page title is AAFC's own; we use only the eggs-per-person column |
| A5 | Statistics Canada, Table 18-10-0245-01 "Monthly average retail prices for selected products" | a | https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip | released 2026-09-02; data to 2026-07 | curl |
| A6 | Statistics Canada, CIMT open-data bulk files, **imports** by HS10 × country × province (ODPFN014), 2023, 2024, 2025, 2026 | a | https://www150.statcan.gc.ca/n1/pub/71-607-x/2021004/zip/CIMT-CICM_Imp_2023.zip (and _2024, _2025, _2026) | file versions: 2023 dated 2026-02-02; 2026 file runs to **2026-07** (ODPFN014_202607N, dated 2026-08-17) | curl, 3 Oct 2026. The 2024 and 2025 zips were re-downloaded today and are byte-identical to copies from 29 Sep |
| A7 | Statistics Canada, CIMT **total exports** by HS8 × country (ODPFN017), 2023–2026 | a | https://www150.statcan.gc.ca/n1/pub/71-607-x/2021004/zip/CIMT-CICM_Tot_Exp_2023.zip (and _2024, _2025, _2026) | 2026 file to 2026-07 (dated 2026-08-21) | curl |
| A8 | Egg Farmers of Canada, 2023 Annual Report (PDF) | a | https://www.eggfarmers.ca/wp-content/uploads/2024/03/2023_Egg-Farmers-of-Canada_Annual-Report.pdf | uploaded 2024-03 | curl |
| A9 | EFC, 2024 Annual Report (PDF) | a | https://www.eggfarmers.ca/wp-content/uploads/2025/03/2025-03-19_Egg-Farmers-of-Canada_Annual-Report-2024.pdf | 2025-03-19 | curl |
| A10 | EFC, 2025 Annual Report (PDF) | a | https://www.eggfarmers.ca/wp-content/uploads/2026/03/2026-03-18_Egg-Farmers-of-Canada_Annual-Report-2025.pdf | 2026-03-18 | curl |
| A11 | NFACC, Code of Practice for the Care and Handling of Pullets and Laying Hens (HTML, incl. 2025 amendment) | a | https://www.nfacc.ca/poultry-layers-code-of-practice | Code 2017, amended 2025 | curl |
| A12 | Justice Laws, Canadian Egg Marketing Agency Quota Regulations, 1986 (SOR/86-8), current consolidation | a | https://laws-lois.justice.gc.ca/eng/regulations/SOR-86-8/FullText.html | "current to 2026-09-21 and last amended on 2025-12-28" | curl |
| A13 | Justice Laws, point-in-time versions of SOR/86-8 **Schedule 1** (federal quota) | a | …/SOR-86-8/section-sched898219-20251005.html, -20250420, -20241229, -20240908, -20231231, -20230101, -20211226 | each version dated in its URL | curl |
| A14 | Justice Laws, point-in-time versions of **Schedule 1.1** (STMRQ), section-sched898229-20250420 / -20241229 / -20231231 / -20230326, and **Schedule 1.2** (egg for processing) section-sched898239-20231231 | a | https://laws-lois.justice.gc.ca/eng/regulations/SOR-86-8/section-sched898229-20241229.html etc. | as dated | curl |
| A15 | Canada Gazette Part II: SOR/2023-284 and SOR/2023-285 (2024-01-03); SOR/2024-171 (2024-09-11); SOR/2024-287, -288, -290 (2025-01-15); SOR/2025-123, -124 (2025-05-07); SOR/2025-204 (2025-10-22); SOR/2025-284, -285 (2025-12-31) | a | e.g. https://gazette.gc.ca/rp-pr/p2/2025/2025-12-31/html/sor-dors284-eng.html ; https://gazette.gc.ca/rp-pr/p2/2025/2025-10-22/html/sor-dors204-eng.html ; https://gazette.gc.ca/rp-pr/p2/2025/2025-05-07/html/sor-dors123-eng.html ; https://gazette.gc.ca/rp-pr/p2/2025/2025-01-15/html/sor-dors287-eng.html ; https://gazette.gc.ca/rp-pr/p2/2024/2024-09-11/html/sor-dors171-eng.html ; https://gazette.gc.ca/rp-pr/p2/2024/2024-01-03/html/sor-dors285-eng.html | as dated | curl |
| A16 | FPCC, "Decisions" page (EFC entries) | a | https://www.canada.ca/en/farm-products-council/services/council-decisions.html | "Date Modified: 2026-09-23" (as returned by WF) | **WF only**; curl refused. The listing may be incomplete (see UNVERIFIED) |
| A17 | FPCC decision letters to EFC, with EFC's request letters attached. The five PDFs are listed after this table | a | — | letters dated 2023-12-14, 2024-08-14, 2024-12-12, 2025-04-11, 2026-07-17 | WF fetched the binaries; text extracted locally with PyMuPDF |
| A18 | CBSA, Customs Tariff 2026, Chapter 4 | a | https://www.cbsa-asfc.gc.ca/trade-commerce/tariff-tarif/2026/html/00/ch04-eng.html | 2026 schedule | curl |
| A19 | CBSA, Customs Tariff 2025, Chapter 4 | a | https://www.cbsa-asfc.gc.ca/trade-commerce/tariff-tarif/2025/html/00/ch04-eng.html | 2025 schedule | curl |
| A20 | Global Affairs Canada, TRQ "Utilization data" page and EICS reports "Utilization Data – Eggs and Egg Products" for 2023, 2024, 2025 and 2026 | a | https://www.international.gc.ca/trade-commerce/controls-controles/utilization-utilisation.aspx?lang=eng (Date modified 2026-08-11); https://www.eics-scei.gc.ca/report-rapport/Utilization_Data-Eggs_and_Egg_Products.htm ("As of: 2026/10/2"); …-25.htm (as of 2026/3/3); …-24.htm (as of 2025/1/1); …-23.htm (as of 2024/1/3) | as dated | curl |
| A21 | Parliament of Canada, LEGISinfo, Bill C-202 (45-1) | a | https://www.parl.ca/legisinfo/en/bill/45-1/c-202 | — | curl |
| A22 | Justice Laws, S.C. 2025, c. 1 (annual statute text of C-202) | a | https://laws-lois.justice.gc.ca/eng/AnnualStatutes/2025_1/FullText.html | "Assented to 2025-06-26"; page modified 2026-09-28 | curl |
| A23 | **[U.S.]** USTR, 2026 National Trade Estimate Report, Canada chapter (p. 61 of report) | a (U.S.) | https://ustr.gov/sites/default/files/files/Press/Releases/2026/National%20Trade%20Estimate%20Report%202026.pdf | 2026 | curl |
| A24 | **[U.S.]** White House, "Fact Sheet: President Donald J. Trump Imposes Additional Tariffs on Canada" | a (U.S.) | https://www.whitehouse.gov/fact-sheets/2026/07/fact-sheet-president-donald-j-trump-imposes-additional-tariffs-on-canada/ | July 20, 2026 | curl |
| A25 | **[U.S.]** White House, Proclamation "Imposing Additional Duties to Offset Canadian Discrimination… with Respect to Dairy" | a (U.S.) | https://www.whitehouse.gov/presidential-actions/2026/07/imposing-additional-duties-to-offset-canadian-discrimination-against-the-commerce-of-the-united-states-with-respect-to-dairy/ | July 20, 2026 | curl |
| A26 | **[U.S.]** White House, "Fact Sheet: President Donald J. Trump Responds to Canada's Retaliation" | a (U.S.) | https://www.whitehouse.gov/fact-sheets/2026/09/fact-sheet-president-donald-j-trump-responds-to-canadas-retaliation/ | September 8, 2026 | curl |
| A27 | **[U.S.]** White House, "President Trump Is Finally Ending Canada's Free Ride" | a (U.S.) | https://www.whitehouse.gov/releases/2026/08/president-trump-is-finally-ending-canadas-free-ride/ | 2026-08-25 | curl |
| A28 | **[U.S.]** USTR, "Ambassador Greer Issues Statement on President Trump Imposing Section 338 Tariffs on Canada" | a (U.S.) | https://ustr.gov/about/policy-offices/press-office/press-releases/2026/july/ambassador-greer-issues-statement-president-trump-imposing-section-338-tariffs-canada | July 2026 | curl |
| A29 | **[U.S.]** BLS, Average Price Data, series APU0000708111 "Eggs, grade A, large, per doz." (U.S. city average) | a (U.S.) | https://data.bls.gov/timeseries/APU0000708111?output_view=data&include_graphs=false&years_option=specific_years&from_year=2023&to_year=2026 | data to Aug 2026 | curl (the BLS API refused with a daily threshold; the web table was used) |
| A30 | **[U.S.]** U.S. DOJ, "Justice Department Requires Egg Producers to End Coordinated Benchmark Manipulation…" | a (U.S.) | https://www.justice.gov/opa/pr/justice-department-requires-egg-producers-end-coordinated-benchmark-manipulation | Tuesday, June 30, 2026 | curl |
| A31 | Loblaw, "Responsible Sourcing" page (Cage-free chicken eggs) | a | https://www.loblaw.ca/en/responsible-sourcing/ | undated; refers to "In 2025" | curl |
| A32 | Loblaw, "Animal Welfare Statement" (PDF; internal title "Animal Welfare Principles") | a | https://dis-prod.assetful.loblaw.ca/content/dam/loblaw-companies-limited/creative-assets/loblaw-ca/responsibility-/Animal%20Welfare%20Statement_EN.pdf | PDF created 2025-06-23 | curl |
| A33 | Loblaw, 2023 Environmental, Social and Governance Report (PDF) | a | https://dis-prod.assetful.loblaw.ca/content/dam/loblaw-companies-limited/creative-assets/loblaw-ca/responsibility-/ESG%20Report_ENGLISH_final%20AODA.pdf | PDF created 2024-04-24 | curl |
| A34 | Loblaw, 2024 Environmental, Social, and Governance Report (PDF) | a | https://dis-prod.assetful.loblaw.ca/content/dam/loblaw-companies-limited/creative-assets/loblaw-ca/responsibility-/2024%20ESG%20Report_EN.pdf | PDF created 2025-04-25 | curl |
| A35 | Loblaw, 2025 Priority ESG Disclosure Report (PDF) | a | https://dis-prod.assetful.loblaw.ca/content/dam/loblaw-companies-limited/creative-assets/loblaw-ca/responsibility-/Loblaw%202025%20Priority%20ESG%20Disclosure%20Report_EN.pdf | PDF created 2026-02-25 | curl. **It contains no egg text** |
| A36 | Sobeys/Empire, Sustainable Business Report, "Ethical & Sustainable Sourcing" (current report) | a, **via archive** | Live https://www.sobeyssbreport.com/sustainable-business-report/ethical-sustainable-sourcing/ returned **403**. Opened instead: https://web.archive.org/web/20260711091327id_/https://www.sobeyssbreport.com/sustainable-business-report/ethical-sustainable-sourcing/ (identical egg text in the 2026-01-01 snapshot) | Wayback snapshot 2026-07-11 | curl via Wayback |
| A36b | Sobeys SBR 2023, same section | a, via archive | https://web.archive.org/web/20241104085506id_/https://sobeyssbreport.com/sustainable-business-report-2023/ethical-sustainable-sourcing/ | snapshot 2024-11-04 | curl via Wayback |
| A36c | Sobeys SBR 2024, same section | a, via archive | https://web.archive.org/web/20260123181115id_/https://www.sobeyssbreport.com/sustainable-business-report-2024/ethical-sustainable-sourcing/ | snapshot 2026-01-23 | curl via Wayback |
| A37 | Metro Inc., "Animal Welfare & Responsible Procurement" | a | https://corpo.metro.ca/en/corporate-social-responsibility/delighted-customers/animal-welfare.html | undated | curl |
| A38 | Metro, Corporate Responsibility Reports FY2023, FY2024, FY2025 (PDFs) | a | https://corpo.metro.ca/userfiles/file/PDF/2025-cr-report.pdf ; …/2024-cr-report.pdf ; …/2023-cr-report.pdf | PDFs created 2025-12-15, 2025-01-15, 2023-12-15 | curl |
| A39 | Walmart Canada, "Policies" page, Animal Welfare section | a | https://www.walmartcanada.ca/policies | undated; refers to "calendar year 2024" | curl |
| A40 | Costco, 2025 Sustainability Report (PDF) and Costco "Animal Welfare" page | a | https://gdx-assets.costco.com/adobe/assets/urn:aaid:aem:6df027a5-f17a-463d-83d7-221313ee3a8d/original/as/costco-sustainability-report-2025.pdf ; https://www.costco.com/f/-/animal-welfare | PDF created 2026-09-21 | curl (page body JS-rendered; PDF used) |
| A41 | Restaurant Brands International (RBI), "Restaurant Brands for Good" reports 2023, 2024, 2025 (PDFs) | a | https://s26.q4cdn.com/317237604/files/doc_downloads/2026/07/2025-Restaurant-Brands-For-Good-Report.pdf ; …/2025/05/2024-Restaurant-Brands-For-Good-Report.pdf ; …/2024/08/2023-Restaurant-Brands-for-Good.pdf | PDFs created 2026-05-05, 2025-04-30, 2024-08-14 | curl |
| A42 | McDonald's Canada newsroom, "McDonald's Canada Achieves Goal of Sourcing 100% Canadian Free-Run Eggs" | a, **via archive** | Live page returned **403** to curl and WF. Opened instead: https://web.archive.org/web/20240607151538id_/https://www.mcdonalds.com/ca/en-ca/newsroom/article/McDonald-s-Canada-Achieves-Goal-of-Sourcing-100--Canadian-Free-Run-Eggs-.html | page dated "06-03-2024"; snapshot 2024-06-07 | curl via Wayback |
| A43 | A&W Food Services of Canada, CNW release "A&W Announces Leadership Investment to Advance Better Cage-Free Egg Production in Canada" | a | https://www.newswire.ca/news-releases/aw-announces-leadership-investment-to-advance-better-cage-free-egg-production-in-canada-571705841.html | March 10, 2016 | curl |
| A44 | Retail Council of Canada, CNW release "Retail Council of Canada Grocery Members Voluntarily Commit to Source Cage-Free Eggs by the End of 2025" | a | https://www.newswire.ca/news-releases/retail-council-of-canada-grocery-members-voluntarily-commit-to-source-cage-free-eggs-by-the-end-of-2025-572574901.html | March 18, 2016 | curl |
| B1 | CBC News, Natalie Stechyson, "Desperate for eggs, the U.S. looks to Europe. Why haven't they asked Canada to shell out?" | b | https://www.cbc.ca/news/world/eggs-us-canada-europe-1.7495959 | 2025-03-28 | curl |
| B2 | CBC News, Natalie Stechyson, "U.S. officials cracking down on people trying to bring valuable eggs across the border" | b | https://www.cbc.ca/news/world/us-border-fentanyl-eggs-1.7486369 | 2025-03-19 | curl |
| B3 | CBC News, Mike Crawley, "What July 1 means for CUSMA…" | b | https://www.cbc.ca/news/politics/cusma-usmca-july-1-canada-us-mexico-trade-trump-tariffs-9.7253789 | 2026-06-30 | curl |
| B4 | Global News / The Canadian Press, Émilie Bergeron, "LeBlanc says Canada seeking clarity after U.S. opts for annual CUSMA review" | b | https://globalnews.ca/news/11953602/canada-seeking-clarity-annual-cusma-review/ | 2026-07-05 | curl |
| B5 | CBC News, Emily Chung and Alexis Gacon, "Canada's major food companies say they care about animal welfare. Here's how they actually perform" | b | https://www.cbc.ca/news/science/mercy-for-animals-scorecard-1.7006954 | 2023-10-25 | curl |
| B6 | CBC News, Susan Noakes, "Cage-free eggs only a goal for major Canadian grocers by 2025" | b | https://www.cbc.ca/news/business/retail-council-cage-free-eggs-1.3497958 | 2016-03-18 | curl |
| B7 | Manitoba Co-operator, Geralyn Wichers, "Survey says Canadians want cage-free eggs but purchase choices don't agree" | b | https://www.manitobacooperator.ca/news-opinion/news/survey-says-canadians-want-cage-free-eggs-but-purchase-choices-dont-agree/ | 2023-07-25 | curl |
| B8 | Canadian Poultry Magazine, Brett Ruffell, "McDonald's Canada Achieves 100% Sourcing Of Free-run Eggs" | b (trade) | https://www.canadianpoultrymag.com/mcdonalds-canada-achieves-100-sourcing-of-free-run-eggs/ | 2024-06-27 | curl |
| B9 | Canadian Poultry Magazine, Monica Dick, "The Story Behind McDonald's Cage-free Milestone" | b (trade) | https://www.canadianpoultrymag.com/a-pledge-kept/ | 2024-10-24 | curl |
| D1 | Bryant Research, "Canadians support an end to cage confinement for egg-laying hens" (n=1,005), plus Mercy For Animals CNW release about the same poll | d | https://bryantresearch.co.uk/insight-items/end-cage-confinement/ ; https://www.newswire.ca/news-releases/new-poll-shows-majority-of-canadians-want-cage-free-eggs-866687398.html | page 2023-06-23; release 2023-06-26 | curl |
| D2 | Bryant Research for Animal Justice, "REPORT: Canadian Consumers Widely Misled by Egg Carton Welfare Labels" (n=1,006), plus Animal Justice release | d | https://animaljustice.ca/uncategorized/consumers-widely-misled-egg-labels ; https://animaljustice.ca/media-releases/most-canadian-shoppers-misled-by-egg-carton-welfare-labels-according-to-survey | 2024-03-26 | curl |

**A17 decision-letter PDFs:**
- https://www.canada.ca/content/dam/fpcc-cpac/documents/decision-letters/2023/12-efc-quota-and-levies-order_en.pdf
- https://www.canada.ca/content/dam/fpcc-cpac/documents/decision-letters/08-efc-quota-en.pdf
- https://www.canada.ca/content/dam/fpcc-cpac/documents/decision-letters/2024/12-efc-quota-and-levies-order_en.pdf
- https://www.canada.ca/content/dam/fpcc-cpac/documents/council-decisions--2025/04-efc-quota_en.pdf
- https://www.canada.ca/content/dam/fpcc-cpac/documents/council-decisions-2026/07-efc-quota_en.pdf

Tier (c) items seen and **not used** as sources are listed in UNVERIFIED: Wikipedia, Retail Insider (blocked), Mercy For Animals and Animal Justice blogs, The Deep Dive, farms.com, refdesk.ca, GHY, National Observer opinion, Axios, Fortune and Hot Air.

---

## 2. Statistics Canada: production, layers, per-capita availability

### 2a. Annual, Canada (A1, Table 32-10-0119-01; units as StatCan publishes them)

| Year | Average number of layers (thousands) | Eggs per 100 layers | Production of eggs in shell (thousand dozen) | Sold for consumption (thousand dozen) | For hatcheries (thousand dozen) | Value of production ($ thousands) |
|---|---|---|---|---|---|---|
| 2019 | 33,553 | 29,401 | 822,072 | 730,105 | 74,352 | 1,587,058 |
| 2020 | 34,126 | 29,512 | 839,284 | 748,601 | 72,842 | 1,651,906 |
| 2021 | 34,467 | 29,523 | 847,978 | 755,737 | 74,307 | 1,816,486 |
| 2022 | 35,193 | 29,561 | 866,950 | 772,134 | 76,503 | 2,063,920 |
| **2023** | **35,581** | 29,556 | **876,348** | 780,033 | 77,820 | 2,218,976 |
| **2024** | **37,063** | 29,574 | **913,406** | 813,950 | 80,253 | 2,318,235 |
| **2025** | **40,525** | 29,529 | **997,203** | 893,423 | 82,929 | 2,544,422 |

StatCan notes, verbatim (A1 metadata):
- "Production of eggs includes eggs in shell (116111) as well as eggs for home consumption and eggs for producers' use for hatching."
- "Average number of layers expressed in thousand numbers, eggs per 100 layers expressed in numbers only, production expressed in thousand dozens, and value expressed in thousand dollars."

**OUR NOTE:**
- StatCan's "production" and "layers" **include hatching-egg flocks and hatching eggs**. That explains why StatCan's 2025 production (997.2 million dozen) is higher than EFC's "937 million dozen eggs produced in Canada in 2025" (A10).
- The closest StatCan line to table and processing eggs is "sold for consumption": **893.4 million dozen in 2025**.
- Do not mix the two series on screen.
- Changes, 2023→2025 (our arithmetic): layers +13.9%; production +13.8%; sold for consumption +14.5%.

### 2b. Monthly, Canada, latest 17 months (A2, Table 32-10-0121-01)

| Month | Average layers (thousands) | Production in shell (thousand dozen) | Sold for consumption (thousand dozen) | Farm price, eggs sold for consumption (¢/dozen) |
|---|---|---|---|---|
| 2025-01 | 37,324 | 74,405 | 66,074 | 220.1 |
| 2025-02 | 37,645 | 75,238 | 67,610 | 220.4 |
| 2025-03 | 38,263 | 78,500 | 69,797 | 220.3 |
| 2025-04 | 39,258 | 81,236 | 72,586 | 219.3 |
| 2025-05 | 40,042 | 82,968 | 74,244 | 219.6 |
| 2025-06 | 40,752 | 83,587 | 74,816 | 221.0 |
| 2025-07 | 41,314 | 85,748 | 76,664 | 221.4 |
| 2025-08 | 41,554 | 86,154 | 77,557 | 222.2 |
| 2025-09 | 41,866 | 85,576 | 76,527 | 222.4 |
| 2025-10 | 42,881 | 87,569 | 78,316 | 222.1 |
| 2025-11 | 42,790 | 87,399 | 78,732 | 225.1 |
| 2025-12 | 42,607 | 88,823 | 80,499 | 227.5 |
| 2026-01 | 42,932 | 86,230 | 77,403 | 228.8 |
| 2026-02 | 42,636 | 85,727 | 77,453 | 229.3 |
| 2026-03 | 42,808 | 86,506 | 77,419 | 228.9 |
| 2026-04 | **43,347** | 88,843 | 79,917 | 231.3 |
| 2026-05 | 43,252 | **89,892** | **80,927** | 231.2 |

- StatCan note on the farm price, verbatim: "Price received by producer." This is the farm-gate price, not the shelf price.
- **OUR NOTE:** In May 2026 against May 2025: layers +8.0%, production +8.3%, farm price +5.3% (our arithmetic). The monthly sums for 2023, 2024 and 2025 equal the annual totals in 2a exactly (checked).

### 2c. Per-capita availability

| Year | StatCan "Food available", eggs (kg/person/year) (A3) | StatCan "Food available adjusted for losses", eggs (kg/person/year) (A3) | AAFC eggs (dozens/person/year) (A4) | AAFC dozens × 12 (our arithmetic) |
|---|---|---|---|---|
| 2022 | 15.28 | 9.42 | 21.46 | 257.5 |
| 2023 | 15.00 | 9.25 | 21.06 | 252.7 |
| 2024 | 15.31 | 9.44 | 21.50 | 258.0 |
| 2025 | **16.04** | **9.89** | **22.53** | **270.4** |

StatCan notes, verbatim (A3):
- on eggs: "In fresh equivalent weight."
- on the loss-adjusted series: "Experimental, use with caution. The data have been adjusted for retail, household, cooking and plate loss."

AAFC (A4) gives "Source: Statistic Canada" for the table, and footnote "[3] Edible weight" on the fish column. The eggs column is in dozens.

EFC (A10, 2025 Annual Report), verbatim: "Canadians eat an average of 259 eggs per year." Its footnote cites "Statistics Canada (2025). 2024 Protein disappearance and demand by species estimated by Agriculture and Agri-Food Canada". EFC's 259 is the 2024 figure. AAFC's 2025 figure, published 2026-05-28, is 22.53 dozen, which is about 270 eggs.

---

## 3. Egg Farmers of Canada annual reports (A8, A9, A10), verbatim figures

### 3a. Headline figures by report

| Item | 2023 Annual Report (A8) | 2024 Annual Report (A9, dated 2025-03-19) | 2025 Annual Report (A10, dated 2026-03-18) |
|---|---|---|---|
| Production (EFC's words) | "more than 837 million dozen eggs produced in Canada and retail sales up 2.6%" (Chair's message) | "856 million dozen eggs produced in Canada in 2024." | "937 million dozen eggs produced in Canada in 2025." Also: "With egg production up by approximately 7.6% in 2025…" |
| Farms (table "Farmers and average flock size per province and territory") | Total **1,243** farmers; average **22,117** layers per farmer ("Reported data for 2023") | Total **1,270**; average **22,503** ("Reported data for 2024. Excludes inventory for EFP.") | Total **1,295**; average **22,069** ("Reported data for 2025.") |
| Retail sales | "2.6% increase in the retail sales of eggs in 2023." | "annual retail egg sales increased by 6.4% and egg orders at foodservice were up by 4.8% when compared to 2023." | "an increase of 5.8% in annual egg sales and a 2.6% jump in annual egg orders at foodservice." |
| Layers added | — | — | "a total of 2,922,258 layers were added to the national system in 2025. This 8.62% increase in quota…" |

EFC cites its sources for the retail and foodservice figures: "Nielsen MarketTrack" and "Ipsos Foodservice Monitor". The two series are not the same measure.

### 3b. Housing transition: "Hen issuance by production method" (Source: Egg boards), as printed in each report

| Production method | 2023 AR: value printed for 2023 ("July, mid-year") | 2024 AR: 2023 (Dec) / **2024 (July)** | 2025 AR: 2024 (Dec) / **2025 (July)** |
|---|---|---|---|
| Conventional housing | 48.02% | 45.28% / **43.25%** | 42.02% / **39.45%** |
| Enriched colony | 33.86% | 35.33% / **36.94%** | 38.02% / **39.33%** |
| Aviary/free run | 11.34% | 13.02% / **13.51%** | 13.49% / **14.77%** |
| Organic | 5.40% | 5.02% / **4.88%** | 5.01% / **4.99%** |
| Free range | 1.38% | 1.35% / **1.42%** | 1.46% / **1.46%** |

Each report's own note:
- 2023 AR: "2019-2022 data represents December, end of year value. 2023 data represents July, mid-year value."
- 2024 AR: "2020-2023 data represents December, end of year values. 2024 data represents July, mid-year value."
- 2025 AR: "2021-2024 data represents December, end of year value. 2025 data represents July, mid-year value."

EFC's narrative and projection, verbatim, in date order:
- **2023 AR:** "Today, fewer than half of hens in Canada are in conventional housing. In the first half of 2023, the proportion of hens in enriched colony housing increased by 2 percentage points, now representing 34% of hens in Canada. … these production systems representing approximately 18% of hens." "The assessment of these latest trends suggest conventional production methods will be phased out by 2035, with the possibility of completing the transition sooner."
- **2024 AR:** "As of mid-2024, the share of hens housed in conventional systems has decreased to 43%, down from 45% in 2023 and 82% in 2016 when the transition process was initiated. Enriched colony housing remains the largest alternative production system, representing nearly 37% of hens in 2024. … Collectively, these alternative housing systems represent approximately 20% of hens in Canada." "Current trends suggest conventional housing is projected to be fully phased out by 2035, if the transition maintains the pace observed over the past three years."
- **2024 AR, on 2031:** "the requirement to increase the space per hen to 90 square inches will take effect in 2031, which is estimated to reduce the number of birds in conventional housing by up to 1.4 million across Canada."
- **2025 AR:** "As of mid-2025, the share of hens housed in conventional systems decreased to 39.45%, down from 42.02% in 2024 and 52.88% in 2021. Enriched colony remains the largest alternative housing system in Canada, representing 39.33% of hens in 2025. … In 2025, free run, free range and organic systems represented 21% of hens in Canada, compared to 10% in 2016." "Current trends suggest conventional housing is projected to be eliminated by the target date of 2036, if the transition maintains the pace observed over the past three years."
- **2025 AR, free-range program:** "Another key initiative was the development of a national Free Range Standards Certification Program. This mandatory program details a consistent set of standards that egg farms must meet to be considered free range, including range access and space, vegetation, pophole and perimeter fence requirements. The Free Range Standards Certification Program was approved by the EFC Board of Directors in August for implementation in early 2026."

**OUR NOTES:**
- (1) The **projected end-date moved** in EFC's own wording. The 2023 and 2024 reports say "phased out by 2035"; the 2025 report says "eliminated by the target date of 2036". State this only as the reports' words, dated.
- (2) The same year shows different values in different reports. For example, 2023 is 48.02% (July value, 2023 AR) but 45.28% (December value, 2024 and 2025 ARs). Always say which report and which month.
- (3) Our arithmetic: conventional plus enriched colony equals 78.78% of hens at mid-2025. Free run plus organic plus free range equals 21.22%.

### 3c. What the NFACC Code literally requires (A11, verbatim)

- "All hens must be housed in enriched cage or non-cage housing systems that meet this Code's requirements by July 1, 2036."
- "If any hens have not been transitioned from conventional cages by July 1, 2031, each of those hens still kept in conventional cages must be provided with a minimum space allowance in those systems of 580.6 cm2 (90.0 sq in), effective July 1, 2031."
- "For Conventional Cages installed prior to July 1, 2016, each bird must be provided with a minimum space allowance of 432.0 cm2 (67.0 sq in) for white birds and 484.0 cm2 (75.0 sq in) for brown birds."

**OUR NOTE:** The Code's 2036 requirement permits **enriched cages**. "Cage-free by 2036" is not what the Code says.

### 3d. EFC on trade and pricing (verbatim)

- **2025 AR:** "We have the government's assurance that supply management is not on the bargaining table in ongoing and future trade talks. This is backed by federal legislation thanks to the successful passage of Bill C-202. Looking ahead, EFC will continue to advocate for no new market access or changes to the over-quota tariff throughout other trade negotiations and as the scheduled review of the Canada-United States-Mexico Agreement (CUSMA) gets underway."
- **2025 AR:** "Bill C-202 received Royal Assent. The strong bipartisan Parliamentary support for supply management led to the successful passage in June of Bill C-202… This bill, put forward by the Bloc Québécois… became one of the rare Private Members' Bills to receive unanimous support in the House of Commons."
- **2025 AR:** "…the implementation of the 2021 COP results through the rollout of the National Free Run Producer Pricing Policy and an updated pricing method for conventional and enriched eggs." EFC says MOUs "delivered coordinated pricing structures for conventional, enriched colony and free run production". These are producer prices, not shelf prices.
- **2024 AR:** "A significant focus of our advocacy efforts in 2024 was on Bill C-282… Collectively more than 73,000 emails were sent to Senators." And "progress on the bill came to a halt with the announcement of the prorogation of Parliament in January 2025".
- **2024 AR:** EFC launched a "Supply and Demand Optimization Project" in July 2024, "tasked with assessing the necessary tools, program and approaches that will allow our sector to reduce its reliance on supplemental imports and meet market demand with eggs from Canadian farms."
- **2025 AR [U.S. price cited by EFC]:** "The Urner Barry price for breaking eggs more than doubled from $2.98 to $6.43 USD per dozen eggs in early February, making it extremely difficult for the Canadian processing market to obtain supply." This is EFC's citation of a U.S. private price report. Attribute it to EFC, labelled U.S. The sentences around it in the report concern disease; see Appendix R.

---

## 4. Federal quota: FPCC approvals and the regulations as amended, 2023–2026

### 4a. Sum of provincial "Limits to Federal Quotas" (dozens), SOR/86-8 Schedule 1, every version in force since 2023 (A12, A13, A15)

| Version in force (Justice Laws) | Allocation period | Amending instrument (Gazette) | Total, 11 provinces/NWT (our sum) | Ontario | Quebec |
|---|---|---|---|---|---|
| 2023-01-01 to 2023-12-30 | Jan 1 – Dec 30, 2023 | (SOR/2022-282) | 791,744,781 | 283,060,210 | — |
| 2023-12-31 to 2024-09-07 | Dec 31, 2023 – Dec 28, 2024 | SOR/2023-285, registered Dec 20, 2023; in force Dec 31, 2023 (Gazette 2024-01-03) | 828,842,791 | 296,826,349 | 169,088,067 |
| 2024-09-08 to 2024-12-28 | same | SOR/2024-171, registered Aug 29, 2024; in force Sept 8, 2024 (Gazette 2024-09-11) | 839,951,471 | 301,045,335 | 171,352,370 |
| 2024-12-29 to 2025-04-19 | Dec 29, 2024 – Dec 27, 2025 | SOR/2024-288, registered Dec 24, 2024; in force Dec 29, 2024 (Gazette 2025-01-15) | 931,137,001 | 335,886,939 | 189,763,232 |
| 2025-04-20 to 2025-10-04 | same | SOR/2025-123, registered Apr 24, 2025; in force Apr 20, 2025 (Gazette 2025-05-07) | 956,004,453 | 345,393,574 | 194,947,903 |
| 2025-10-05 to 2025-12-27 | same | SOR/2025-204, registered Oct 1, 2025; in force Oct 5, 2025 (Gazette 2025-10-22) | 965,608,715 | 349,054,977 | 196,977,010 |
| **2025-12-28 to present** | **Dec 28, 2025 – Dec 26, 2026** | SOR/2025-284, registered Dec 18, 2025; in force Dec 28, 2025 (Gazette 2025-12-31) | **997,622,922** | **361,259,654** | **203,740,700** |

2026 limits by province, verbatim from A12:

| Province | Limit (dozens) |
|---|---|
| Ontario | 361,259,654 |
| Quebec | 203,740,700 |
| Nova Scotia | 28,037,660 |
| New Brunswick | 19,112,824 |
| Manitoba | 81,959,627 |
| British Columbia | 126,833,737 |
| Prince Edward Island | 4,657,248 |
| Saskatchewan | 45,887,042 |
| Alberta | 109,425,604 |
| Newfoundland and Labrador | 12,599,755 |
| Northwest Territories | 4,109,071 |

A12's currency line, verbatim: "Regulations are current to 2026-09-21 and last amended on 2025-12-28." So there was **no in-year federal-quota amendment in 2026** up to that date.

**Reclassification caveat.** Before 2025 there was also a separate **Egg for Processing quota**, Schedule 1.2. For Dec 31, 2023 – Dec 28, 2024 it totalled **40,273,176 dozen** (our sum; A14). By province:

| Province | EFP limit 2024 (dozens) |
|---|---|
| Ontario | 20,368,176 |
| Quebec | 7,962,000 |
| Manitoba | 5,308,000 |
| British Columbia | 2,654,000 |
| Saskatchewan | 3,317,500 |
| Alberta | 663,500 |
| Others | 0 |

**SOR/2024-287** (registered Dec 24, 2024; Gazette 2025-01-15) repealed it. Verbatim: "The definition egg for processing quota in section 2 … is repealed."

Like-for-like (our arithmetic): 2024 federal plus EFP was 880,224,647 dozen. Against that, 2026 federal is **+13.3%** and 2025 (initial) is +5.8%. Against federal only, 2024 initial to 2026 is +20.4%.

### 4b. Special Temporary Market Requirement Quota (STMRQ), Schedule 1.1 totals (our sums; A14, A15)

| Period | Version / instrument | Total (dozens) |
|---|---|---|
| Mar 26 – Dec 30, 2023 | sched898229-20230326 (SOR/2023-55) | 39,912,077 |
| Dec 31, 2023 – Dec 28, 2024 | SOR/2023-283 | 55,866,729 |
| Dec 29, 2024 – Dec 27, 2025 (from Dec 29, 2024) | SOR/2024-290 | 35,052,120 |
| same (from Apr 20, 2025) | SOR/2025-124 | 47,598,997 |
| Dec 28, 2025 – Dec 26, 2026 | SOR/2025-285 | 30,582,705 |

EFC's own description, verbatim (from its request letters attached to A17, Nov 18, 2024 and Mar 19, 2025): "The STMRQ category was created as a fiscally prudent risk mitigation tool to increase domestic supply for the processing industry, lessening reliance on imports, specifically supplementary requests." And: "no eggs produced under STMRQ are destined to the table market."

### 4c. FPCC decision letters (A17; A16 lists them), verbatim

| FPCC letter date | What Council reviewed | FPCC's words |
|---|---|---|
| **December 14, 2023** | Levies Order; Federal Quota (Sch. 1), STMRQ (Sch. 1.1), Egg for Processing Quota (Sch. 1.2), Vaccine Quota (Sch. 2), as outlined in EFC letters of Nov 15 and Nov 24, 2023 | "The proposed amendments to the Federal Quota (Schedule 1), Special Temporary Market Requirement Quota (Schedule 1.1), Egg for Processing Quota (Schedule 1.2) and Vaccine Quota (Schedule 2) were also approved. The amendments to the four schedules come into effect on December 31, 2023, and expire on December 28, 2024." |
| **August 14, 2024** (meeting Aug 13, 2024) | Schedule 1 (Federal Quota), per EFC letter of July 11, 2024 | "Council members found that the amendments are necessary for the implementation of the marketing plan as contained in the Canadian Egg Marketing Agency Proclamation." |
| **December 12, 2024** (meetings Dec 11–12, 2024) | Levies Order and Quota Regulations, per EFC letters of Nov 18, 2024 | "Following a thorough review of the rationale provided by EFC and internal analysis, Council members found that the amendments are necessary for the implementation of EFC's marketing plan." |
| **April 11, 2025** | Schedule 1 and 1.1 for Dec 29, 2024 – Dec 27, 2025, per EFC letter of Mar 19, 2025 | "…Council members found that the amendments are necessary for the implementation of EFC's marketing plan. The amendments will come into force on April 20, 2025." |
| **July 17, 2026** | Schedule 2 (Vaccine Quota) for Dec 27, 2026 – Dec 25, 2027, per EFC letter of June 29, 2026 | "…Council members found that the amendments are necessary… The amendments will come into force on December 27, 2026." EFC's request letter asked for "Ontario for 6,716,666 dozens (the equivalent of 492,000 layers)". |

EFC's July 11, 2024 request letter (A17), verbatim: "Mr. Wilson's memo emphasized that the EFC Board has discretion regarding the allocation of quota, as determined in the 2006 Justice Shore ruling, and that the Quota Allocation Calculation (QAC) Policy can be used as a guideline in exercising that discretion…"

EFC's own list of FPCC prior approvals (annual reports, verbatim):
- **2023 AR, for 2024:**
  - "Federal regulated quota increase of 1,397,815 layers – Week 1 of 2024"
  - "STMRQ increase of 150,000 layers – Week 1 of 2024"
- **2024 AR, for 2025:**
  - "Federal regulated quota increase of 2,494,009 layers – Week 1 of 2025"
  - "STMRQ decrease of 784,273 layers"
  - "Eggs for processing quota repealed"
  - "Vaccine quota layers decrease of 211,680 layers"
- **2025 AR:**
  - "Federal quota increase of 1,353,964 layers – Week 17 of 2025"
  - "Federal quota increase of 1,568,294 layers – Week 41 of 2025"
  - "STMRQ quota allocation of 1,154,500 layers – Week 1 of 2026"

**Gap:** The FPCC decisions page (A16, read via WF) listed no letters for the Oct 2025 (SOR/2025-204) or Dec 2025 (SOR/2025-284/-285) amendments. Each of those Gazette instruments states that the Council "has approved the proposed Regulations". See UNVERIFIED.

---

## 5. Trade: tariff, TRQs, imports and exports of shell eggs (HS 0407)

### 5a. Over-quota tariff (A18 2026; A19 2025, identical rows), verbatim

| Tariff item | Description | MFN rate | Preferential rates listed |
|---|---|---|---|
| 0407.21.10 (and .10/.20/.30 statistical suffixes) | Fresh eggs of Gallus domesticus, **within** access commitment | 1.51¢/dozen | "CCCT, LDCT, UST, CT, CRT, PT, COLT, JT, PAT, CEUT, UAT, CPTPT, UKT: Free" |
| **0407.21.20 00** | "Birds' eggs, in shell, fresh, preserved or cooked. - Other fresh eggs: - Of fowls of the species Gallus domesticus - **Over access commitment**" | **"163.5% but not less than 79.9¢/dozen"** | none listed |
| 0407.90.12 00 | Preserved or cooked, Gallus, over access commitment | "163.5% but not less than 79.9¢/dozen" | none listed |

### 5b. TRQ access and permits issued, eggs and egg products (A20)

Units are dozens egg-equivalent, except WTO egg products and WTO egg powder, which are in kg.

| Year (report "as of") | Access: CPTPP / CUSMA / WTO | Shell eggs: WTO TRQ permits | Shell eggs: **Supplemental** permits | Shell eggs/Breaking: CUSMA TRQ | Shell eggs/Breaking: **Supplemental** | Shell eggs/Breaking: IREP |
|---|---|---|---|---|---|---|
| 2023 (2024/1/3) | 16,700,000 / 6,666,667 / 21,370,000 | 11,722,254 | **5,824,791** | 6,306,667 | **18,463,645** | 187,200 |
| 2024 (2025/1/1) | N/A / N/A / 21,370,000 (as printed) | 11,757,705 | **1,812,058** | 8,064,675 | **29,213,408** | 387,900 |
| 2025 (2026/3/3) | 17,035,670 / 10,000,000 / 21,370,000 | 7,766,957 | **0** | 9,252,401 | **20,065,801** | 390,600 |
| 2026 to date (2026/10/2) | 17,378,087 / 10,201,000 / 21,370,000 | 9,514,970 | **9,475** | 5,803,474 | **0** | 100,800 |

- Report footnote, verbatim: "* Data extracted from NEICS - Issued Import Permits ** All quantities are shown in dozens egg equivalent except WTO egg products and WTO egg powder, which are shown in kilograms".
- **OUR NOTE:** These are **permits issued**, not goods cleared. Section 5c gives the customs counts. "Supplemental" means permits beyond the TRQs. The 2024 access row printed "N/A" for CPTPP and CUSMA.

### 5c. Imports of HS 0407.21 (fresh hen eggs) by line, dozens and declared value (A6, CIMT)

| HS10 line | 2023 dozen | 2023 $ | 2024 dozen | 2024 $ | 2025 dozen | 2025 $ | Jan–Jul 2026 dozen | Jan–Jul 2026 $ |
|---|---|---|---|---|---|---|---|---|
| 0407.21.10.10 table, white regular, within access | 17,111,432 | 34,808,603 | 15,451,863 | 42,853,583 | 8,205,840 | 22,605,349 | 6,172,664 | 8,660,920 |
| 0407.21.10.20 table, organic/specialty (incl. free run/range), within access | 708,699 | 882,331 | 207,241 | 819,211 | 87,663 | 337,479 | 35,886 | 111,530 |
| 0407.21.10.30 for breaking only, within access | 28,290,791 | 90,131,743 | 44,435,179 | 152,282,634 | 35,286,091 | 261,880,679 | 5,921,933 | 14,436,219 |
| 0407.21.20.00 **over access** | 28,015 | 67,001 | 66,372 | 266,069 | 0 | 0 | 840,525 | 596,988 |
| **Total 0407.21** | **46,138,937** | 125,889,678 | **60,160,655** | 196,221,497 | **43,579,594** | 284,823,507 | **12,971,008** | 23,805,657 |

Jan–Jul comparison, total 0407.21: 2023 26,164,577 dozen; 2024 32,269,209; 2025 31,693,664; **2026 12,971,008**.

**By country of origin.** Every dozen in 0407.21 came from the **United States (US)** in 2023, 2025 and Jan–Jul 2026. In 2024 every dozen did too, except **3 dozen from Mexico** (over-access line, April 2024, into QC). By U.S. state of origin, the 2026 over-access entries were New York into Ontario, plus small amounts from Washington into BC.

**Declared customs value per dozen** (our computation; customs values, **not retail prices**):

| Line | 2023 | 2024 | 2025 | Jan–Jul 2026 |
|---|---|---|---|---|
| Breaking eggs | $3.19 | $3.43 | **$7.42** | $2.44 |
| Table white regular | $2.03 | $2.77 | $2.75 | $1.40 |
| Over-access (2026) | — | — | — | $0.71 |

All 0407.21 lines in **Feb 2025** together: $86,995,826 for 6,528,319 dozen = **$13.33/dozen**.

Monthly 0407.21 imports, 2025 (dozen):

| Month | Table white | Specialty | Breaking | Total value $ |
|---|---|---|---|---|
| Jan | 1,061,297 | 42,879 | 4,919,408 | 49,795,422 |
| Feb | 72,900 | 25,460 | 6,429,959 | 86,995,826 |
| Mar | 48,600 | 19,324 | 4,963,680 | 53,077,823 |
| Apr | 24,300 | 0 | 4,570,020 | 24,535,069 |
| May | 48,600 | 0 | 4,825,587 | 16,970,645 |
| Jun | 48,600 | 0 | 3,434,750 | 13,968,986 |
| Jul | 72,900 | 0 | 1,085,400 | 4,839,655 |
| Aug | 241,314 | 0 | 1,157,400 | 5,039,059 |
| Sep | 1,699,151 | 0 | 2,458,800 | 13,843,186 |
| Oct | 2,772,333 | 0 | 1,100,887 | 9,336,779 |
| Nov | 778,865 | 0 | 246,600 | 2,790,168 |
| Dec | 1,336,980 | 0 | 93,600 | 3,630,889 |

**Context (our arithmetic, labelled):** total 0407.21 imports compared with StatCan "sold for consumption" (A1) were 5.9% in 2023, 7.4% in 2024 and **4.9% in 2025**. These are two different statistical series; use them as an order of magnitude only.

Province of clearance, 2025 (dozen): ON 26,101,050; QC 8,787,568; MB 6,183,583; BC 2,094,712; SK 347,499; AB 65,182.

Other 0407 import lines, 2025, for completeness (A6):
- hatching eggs for broilers, within access (0407.11.11): 11,331,745 dozen
- other Gallus hatching eggs (0407.11.91): 1,997,984 dozen
- turkey hatching eggs (0407.19.00.10): 231,629 dozen
- other preserved birds' eggs (0407.90.90): 1,408,296 dozen

These are **not table eggs**.

### 5d. Exports of shell eggs (HS 0407), including to the United States (A7, CIMT total exports)

| HS8 line | 2023 | 2024 | 2025 | Jan–Jul 2026 |
|---|---|---|---|---|
| **0407.21 fresh hen eggs** (dozen / $) | 26,209 / 32,762, all to **PM** (St. Pierre and Miquelon) | 66,962 / 83,701, all to **PM** | 58,736 / 78,098: **FR** 32,466; **PM** 26,270 | 41,869 / 52,338: PM 39,472; FR 2,397 |
| **0407.21 to the United States** | **0** | **0** | **0** | **0** |
| 0407.29 fresh eggs of birds **other than** Gallus (dozen) | 2,307,367 (US 2,306,489) | 2,699,060 (all US) | 3,665,308 (all US) | 2,158,441 (US 2,158,365) |
| 0407.11 Gallus eggs fertilized for incubation (dozen) | 533,104 (US 230,813) | 577,605 (US 465,249) | 996,216 (US 865,062) | 332,135 (US 254,772) |
| 0407.19 other birds' eggs fertilized for incubation (dozen / $) | 2,782,889 / 75,316,472 (US $52.4M) | 2,335,673 / 69,168,058 (US $48.9M) | 2,061,791 / 64,102,131 (US $48.9M) | 1,296,223 / 37,637,740 (US $28.5M) |

**On-air-safe wording:** "Statistics Canada's trade data show no exports of fresh hen eggs in shell from Canada to the United States in 2025, or in any month from January 2023 to July 2026."
- **Do not** call the 0407.29 exports hen eggs. The HS description is "Birds' eggs, fresh, o/t of fowls of species Gallus domesticus".
- **Do not** call the 0407.11 and 0407.19 exports table eggs. They are eggs "fertilized for incubation".

AAFC, as quoted by CBC (B1, 2025-03-28), verbatim: "Canada has not received any request to export shelled eggs to the United States," a spokesperson for Agriculture and Agri-Food Canada told CBC News. Also: "The American egg production industry is more than ten times larger than Canada's industry, Agriculture and Agri-Food Canada explained."

---

## 6. [U.S.] The 2025 U.S. egg price spike: U.S. facts, labelled U.S.

### 6a. [U.S.] BLS, average price, eggs, Grade A large, per dozen, U.S. city average, in USD (A29)

| Year | Jan | Feb | Mar | Apr | May | Jun | Jul | Aug | Sep | Oct | Nov | Dec |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 2023 | 4.823 | 4.211 | 3.446 | 3.270 | 2.666 | 2.219 | 2.094 | 2.043 | 2.065 | 2.072 | 2.138 | 2.507 |
| 2024 | 2.522 | 2.996 | 2.992 | 2.864 | 2.699 | 2.715 | 3.080 | 3.204 | 3.821 | 3.370 | 3.649 | 4.146 |
| 2025 | 4.953 | 5.897 | **6.227** | 5.122 | 4.548 | 3.775 | 3.599 | 3.587 | 3.488 | –(X) | 2.860 | 2.712 |
| 2026 | 2.577 | 2.500 | 2.348 | 2.250 | 2.191 | 2.141 | 2.189 | 2.272 | | | | |

BLS note, verbatim: "X : Data unavailable due to the 2025 lapse in appropriations".

### 6b. Canada, for contrast: StatCan average retail price, "Eggs, 1 dozen", Canada, CAD (A5)

| Month | Price |
|---|---|
| 2024-12 | 4.75 |
| 2025-01 | 4.89 |
| 2025-02 | 4.91 |
| 2025-03 | 4.92 |
| 2025-04 | 4.92 |
| 2025-05 | 4.94 |
| 2025-06 | 4.94 |
| 2025-07 | 4.95 |
| 2025-08 | 4.81 |
| 2025-09 | 4.89 |
| 2025-10 | 4.76 |
| 2025-11 | 4.74 |
| 2025-12 | 4.70 |
| 2026-01 | 4.74 |
| 2026-02 | 4.81 |
| 2026-03 | 4.77 |
| 2026-04 | 4.80 |
| 2026-05 | 4.85 |
| 2026-06 | 4.88 |
| 2026-07 | 4.95 |

StatCan caution, verbatim (A5 metadata): "Users should continue to exercise caution when comparing average prices over time…"

**OUR NOTE:**
- The CAD and USD figures are different currencies, and the products are defined differently ("Grade A, large" versus "Eggs, 1 dozen").
- Show them side by side only with both labels. Never present them as a converted comparison unless the exchange rate and its date are given.

### 6c. [U.S.] Other U.S. facts reported by CBC (tier b), attributed

- B2 (2025-03-19), verbatim: "Officials made 3,254 egg-related seizures in January and February 2025, according to new data released by U.S. Customs and Border Protection (CBP). That's a 116 per cent increase…"
- B2, verbatim: "Egg interceptions at the Detroit border crossing (where most eggs are coming in from Canada) increased 36 per cent in the 2025 fiscal year compared to the same time period in 2024, according to data provided by CBP to CBC News."
- B2, verbatim: "These numbers do not capture what is actually smuggled into the country, although CBP says most of the egg seizures happen after travellers willingly declare the product."
- B1 (2025-03-28), verbatim: "Last week, the USDA announced it had secured 'new egg import commitments' from Turkey and South Korea."
- B1, verbatim: "Canada produced 856 million dozen eggs in 2024, according to the Egg Farmers of Canada's recently released Annual General Report. The U.S. produced about nine billion dozen eggs that same year, according to the USDA's annual Chickens and Eggs report."

---

## 7. The 2025–2026 U.S.–Canada trade dispute as it touched supply-managed eggs

### 7a. Canada: Bill C-202 (A21, A22)

**LEGISinfo (A21), verbatim:**
- Title: "An Act to amend the Department of Foreign Affairs, Trade and Development Act (supply management)"
- Bill type: "Private Member's Bill"
- Sponsor: "Yves-François Blanchet (Beloeil—Chambly)"
- Status: "This bill received royal assent on Thursday, June 26, 2025"; "Statutes of Canada 2025, c. 1".

| Stage | Date (A21) |
|---|---|
| House, first reading | Thursday, May 29, 2025 |
| House, second reading, committee report, report stage and third reading | all Thursday, June 5, 2025 ("Subject to special order respecting proceedings at all stages") |
| Senate, first reading | Tuesday, June 10, 2025 |
| Senate, second reading | Thursday, June 12, 2025 (sponsor's speech: Pierre Dalphond) |
| Senate, third reading | Tuesday, June 17, 2025 |
| Royal assent | Thursday, June 26, 2025 |
| Predecessor | "C-282" (44th Parliament, 1st session) |

**Statute text (A22), verbatim:**
> "(2.1) In exercising and performing the powers, duties and functions set out in subsection (2), the Minister must not make any commitment on behalf of the Government of Canada, by international trade treaty or agreement, that would have the effect of
> (a) increasing the tariff rate quota, within the meaning of subsection 2(1) of the Customs Tariff, applicable to dairy products, poultry or eggs; or
> (b) reducing the tariff applicable to those goods when they are imported in excess of the applicable tariff rate quota."

### 7b. [U.S.] U.S. claims, in U.S. words, labelled U.S.

- **USTR, 2026 National Trade Estimate (A23), Canada, "Agricultural Supply Management", verbatim:**
  - "Canada uses supply-management systems to regulate its dairy, chicken, turkey, and egg industries."
  - "Canada's supply-management system severely limits the ability of U.S. producers to increase exports to Canada above TRQ levels and increases the prices that Canadians pay for dairy and poultry products."
  - "Under the current system, U.S. imports above quota levels are subject to prohibitively high tariffs (e.g., 245 percent for cheese and 298 percent for butter)."
  - "Canada has also opened TRQs for U.S. chicken and U.S. eggs and egg products."
  - **[Our label]** These are U.S. claims. The Canadian over-quota rate for fresh hen eggs is 163.5% / 79.9¢ per dozen (A18).
- **White House, July 20, 2026 (A24), verbatim:** "President Donald J. Trump signed three Proclamations pursuant to Section 338 of the Tariff Act of 1930 to impose additional 50% tariffs on certain goods of Canada… leveling the playing field for crucial American exports—cars, alcohol, and dairy."
- **Proclamation (A25):** it is titled "…with Respect to Dairy". Its stated finding concerns Canada's USMCA versus CETA cheese TRQ eligibility. Verbatim: "While Canada's eligibility criteria for the USMCA dairy TRQs — and specifically, the cheeses of all types TRQ — do not allow retailers to obtain and use TRQ quantities, the eligibility criteria for the CETA do grant retailers access…" **The proclamation and fact sheet texts opened contain no reference to eggs.** The annexed product lists were not opened.
- **USTR (A28), verbatim:** "President Trump is imposing a 50 percent tariff on nearly $20 billion in imports from Canada, which will take effect in thirty days."
- **White House, Aug 25, 2026 (A27), verbatim (dairy):** "…dairy with tariff-rate quotas far more restrictive than those given to Europe, plus over-quota tariffs of nearly 300%…"
- **White House, Sept 8, 2026 (A26), verbatim:** "After breaking off trade talks with the United States last month, today Canada imposed new retaliatory tariffs on about $20 billion of U.S. exports, including steel, dairy, and agricultural equipment." And: "…imposed import bans on certain Canadian dairy and other products of Canada… The import bans will take effect on September 29, 2026…" **[Our label]** These are U.S. characterizations, and the Canadian measures were not opened (see UNVERIFIED). Eggs are not named.

### 7c. CUSMA review (tier b)

- **CBC, Mike Crawley, 2026-06-30 (B3), verbatim:** the U.S. "will be gunning for greater access to Canada's dairy market, a frequent complaint of the Trump administration."
- **The Canadian Press via Global News, Émilie Bergeron, 2026-07-05 (B4), verbatim:**
  - "Days after the Trump administration decided to require annual reviews of the Canada-United States-Mexico Agreement instead of renewing it in its current form until 2042, the Canadian government says significant uncertainty remains over the next steps in trade negotiations."
  - "The U.S. decision set in motion a renewable annual review process that could last up to 10 years."
  - LeBlanc: "There wasn't an answer at the meeting. … It was agreed that we would continue the conversation over the coming weeks."

---

## 8. Legal, competition and court items (labelled)

| Item | Jurisdiction | Label | Date | What the record says | Source |
|---|---|---|---|---|---|
| Competition Bureau decisions, court rulings or class actions in **Canada** involving egg companies or egg pricing, 2023–2026 | Canada | **None found** | — | Searches (web; CanLII via web search) found no such item in the 2023–2026 window | (search only; see UNVERIFIED 23) |
| Animal Justice's request that the Commissioner of Competition inquire into Burnbrae Farms' "Nestlaid" / "À l'ancienne" marketing | Canada | **Request / allegation by an advocacy group. No Bureau finding located** | 2012-09-11 (outside window) | AJ's release, verbatim: "Animal Justice Canada calls upon Melanie L. Aiken, Commissioner of Competition, to conduct an inquiry into Burnbrae Farms Limited's use of the term 'Nestlaid' / 'À l'ancienne' in the marketing of its eggs." The outcome is unknown. **Not for air** unless the Bureau's own record is found | https://animaljustice.ca/media-releases/animal-justice-calls-for-burnbrae-farms-false-advertising-inquiry (opened today; tier c for the substance) |
| **[U.S.]** DOJ and 17 State AGs v. Cal-Maine Foods, Hickman's Egg Ranch, Versova entities (N.D. Iowa) | **U.S. only** | **Complaint (allegations) plus proposed settlements, pending court approval (Tunney Act)** | June 30, 2026 | DOJ, verbatim: "the complaint alleges that Cal-Maine, Hickman's, and Versova coordinated to artificially inflate the daily quotations of Urner Barry Publications…" And: "the Department filed proposed settlements that will, if approved by the court, prevent these companies from engaging in such coordinated manipulation in the future." **No Canadian company is named.** Do not imply any link to Canada | A30 |

**OUR NOTE:**
- EFC's 2025 report cites an Urner Barry U.S. breaking-egg price (section 3d). Do **not** connect that citation to the DOJ allegations. They are separate facts, and nothing in the record links them.
- Never present the DOJ item as a finding. The settlement terms (dollar amounts, egg donations) are reported by media only (UNVERIFIED).

---

## 9. Cage-free commitments: the companies' own words against the dated record

### 9a. The 2016 grocer pledge (A44, verbatim; RCC release on CNW, March 18, 2016)

> "Today, the Retail Council of Canada (RCC) grocery members, including : Loblaw Companies Limited, Metro Inc., Sobeys Inc., and Wal-Mart Canada Corp., announced a step towards improving animal welfare by voluntarily committing to the objective of purchasing cage-free eggs by the end of 2025."
> "this voluntary commitment is made recognizing the restrictions created by Canada's supply management system and importantly this objective will have to be managed in the context of availability of supply within the domestic market."

CBC, Susan Noakes, 2016-03-18 (B6), verbatim: "The Retail Council includes Loblaw Co. Ltd., Metro Inc. Sobeys Inc. and Wal-Mart Canada Corp., which together represent 90 per cent of grocery retail in Canada."

### 9b. Company-by-company: their words, latest dated figures

| Company | Commitment (their words, date) | Later position (their words, date) | Latest progress figure (their words) | Source |
|---|---|---|---|---|
| **Loblaw** | "In 2016, we announced that we would source all shell eggs from cage-free systems by 2025." (2023 ESG Report; Animal Welfare Statement) | "In 2021, however, it became evident that our farmer partners would not be able to meet the 2025 timeline." (Animal Welfare Statement, PDF created 2025-06-23). Current page: "we have accelerated our transition plan, ensuring that all control brand shelled chicken eggs will come from hens housed in alternatives to the standard 'battery' cage by 2030, including from free-run² or free-range³." The 2024 ESG Report and the Animal Welfare Statement list "free-run, free-range **or enriched housing**" for the same 2030 control-brand goal | **2023:** "the sale of cage-free eggs accounted for approximately 19.5% of control brand category sales" (A33). **2024:** "the sale of free-run and free-range eggs (previously 'cage free') accounted for approximately 16% of all category sales (includes national brand and control brand eggs sold in corporate, franchise, associate-owned, and T&T® stores)" (A34). **2025:** "free-run and free-range eggs represented approximately 18% of total category sales." Also: "Today, 100% of PC® shell eggs are now entirely free-run and/or free-range hen housing systems." (A31) | A31–A34 |
| **Sobeys (Empire)** | (2016 RCC pledge, A44) | SBR 2023 (A36b): "As part of our commitment to continuous improvement, we are developing protein-specific sourcing guidelines, starting with egg-laying hens and pork." Current SBR (A36): "We remain committed to continuing to work with suppliers and industry partners, such as the NFACC, to increase the availability of cage-free (including free-run, free-range and organic) and enriched-housing eggs, setting internal purchasing milestones and educating customers on the options available in stores." | "In fiscal 2025, 20% of total shell eggs sales were cage-free, with the remainder coming from enriched housing systems or conventional cages." "Currently, many egg suppliers use both enriched housing systems and conventional cages, and it is difficult to get accurate data as to the proportions from each type of housing within the supply provided." (A36, **Wayback copy, snapshot 2026-07-11**; live page 403) | A36, A36b |
| **Metro** | "Eggs In 2016: Voluntary commitment to the objective of purchasing cage-free eggs by the end of 2025." | "In 2021: Through ongoing discussions with our suppliers, it became apparent that this commitment would not be achievable by the industry within the planned time frame of 2025." "METRO will continue to work with its suppliers to increase its supply of eggs from hens raised in cage-free system and enriched housing." (A37). FY2025 report: "There is currently no scientific consensus to suggest that cage-free housing provides superior overall welfare for hens compared to enriched cages." | FY2025 report: "In 2025, cage-free eggs accounted for 33% of our total whole-egg assortment and close to 14% of our sales in that category, while eggs from enriched cage systems represented 37% of our offering and approximately 2% of sales." "This year, the average transition rate among our suppliers was 65%, with 32% from enriched cages and 33% from cage-free systems." "…94% of our stores offer cage-free eggs, and all whole eggs sold under our private brand Life Smart are organic and cage-free." KPI table: cage-free shell-egg sales **13.7% (2025), 13.0% (2024)**; stores offering cage-free 94.5% (2025), 94.9% (2024), 93.1% (2023), 92.8% (2022). FY2024 report: "In 2024, cage-free eggs represented 34% of our total product offering in the whole-egg category and 13% of our sales in that same category." | A37, A38 |
| **Walmart Canada** | "In 2013 and 2016 respectively, Walmart committed to the pursuit of gestation crate free pork by 2022 and cage free eggs by 2025." | "Although progress has been made toward both of these goals it has become apparent that they will not be achieved in the original timelines. We remain committed to ongoing dialogue with the supply chain…" | "In calendar year 2024, cage-free shell eggs accounted for approximately 9% of Walmart Canada's total shell egg net sales, based on supplier reports." (no 2025 figure on the page) | A39 |
| **Costco (Canada)** | Costco page: "We work to procure cage-free eggs in all 14 regions where we operate and will continue to transition to cage-free eggs with added availability and capacity of cage-free production." | 2025 report: "In Canada, the percentage of cage-free (or free run eggs) in Kirkland Signature Liquid Eggs continues to increase." Footnote: Canada is among markets "selling cage-free eggs in select locations and will continue to expand based on availability." | KPI 20.2, "Cage-Free Chicken Shell Eggs (% of Total Number of Individual Eggs)", **Canada: FY23 22%, FY24 21.3%, FY25 22.6%** ([U.S.] for contrast: FY25 84.7%) | A40 |
| **Tim Hortons** (reported within RBI; RBI's "Canada" figure covers RBI brands in Canada) | 2023 report: "In Canada, Tim Hortons is continuing to make significant progress in converting to cage-free systems, now aiming for 100% completion by 2028, ahead of the original 2030 target." | 2024 report: "In Canada, for cage-free eggs our aim is 15% achievement by the end of 2024, 30% by 2025, 50% by 2026, 70% by 2027, and then full compliance by 2028." 2025 report: "In the U.S. and Canada, which collectively represent 90% of our total shell and liquid egg requirements, we expect to achieve 100% compliance across our brands by 2026 and 2028, respectively." | **2024:** "In 2024, our cage-free eggs compliance in Canada was 7%." (stated aim was 15%). **2025:** "By the end of 2025, we achieved 40% of our global cage-free egg commitment across all regions: North America 39% (Canada 27% and U.S. 50%)…" (stated aim was 30%) | A41 |
| **McDonald's Canada** | Original target: "reaching this goal by 2025, set in 2015 as part of McDonald's Canada's Food Quality and Sourcing journey." | — | Dated "06-03-2024": "McDonald's Canada is proud to announce it has reached its goal of sourcing 100% Canadian free-run eggs for its McMuffin®, McGriddles® and Bagel sandwiches." Hope Bentley: "Over 117 million Canada Grade A eggs are sourced per year for Canadian restaurants…" "Burnbrae Farms has supplied eggs to McDonald's restaurants in Canada since the early 1970's and has been the sole supplier since 2003." (A42, **Wayback copy**; also reported by B8, 2024-06-27) | A42, B8 |
| **A&W Canada** | CNW, March 10, 2016: "A&W Food Services of Canada Inc. announces today a major commitment to become the first national quick service restaurant in Canada to serve eggs from hens raised in better cage-free housing. It expects to achieve this goal within two years." | CBC, 2023-10-25 (B5), reporting the company's comment: "Griffiths says the company has transitioned to larger, enriched cages, which include things like nesting areas, perches and scratch mats, and are now in the process of transitioning to cage-free and free-run systems." | **No dated current figure found on A&W's own site** (JS-rendered; see UNVERIFIED) | A43, B5 |

### 9c. Named-outlet reporting on whether targets were met (tier b), with their words only

- **CBC, Emily Chung and Alexis Gacon, 2023-10-25 (B5):** "Meanwhile, Tim Hortons was criticized for pushing back its deadline to have only cage-free eggs — from 2025 to 2030 — 'without any transparency on its progress to date.'" (CBC quoting the Mercy For Animals report.) RBI's response as quoted by CBC: the new target "is the practical timing to match up the volume of eggs we use and the availability of cage free eggs supply in Canada."
  - Our note: RBI's later reports (A41) state 2028 for Canada.
- **Manitoba Co-operator, Geralyn Wichers, 2023-07-25 (B7):** "'We've learned that the supply chain needs more time to adapt and change,' Sobeys said in its 2022 animal welfare statement." And, quoting Loblaw's 2022 ESG report: "'However, in 2021 it became evident that our farmer partners would not be able to meet the 2025 timeline,' it said."
- **Canadian Poultry Magazine, Monica Dick, 2024-10-24 (B9):** "However, in 2021, RCC members announced they were abandoning their cage-free pledge." And RCC spokesperson Michelle Wasylyshen, quoted: "We believe real progress is made by working collaboratively with farmers, sorters, processors, animal health and welfare experts and retailers and by educating consumers about the availability of different kinds of eggs."
- **Gap:** We found **no CBC, Globe and Mail, CP or CTV news story from 2025–2026** that assesses, after the end-2025 deadline, whether the grocers met the RCC pledge. The Globe "hits" in search were reposted PR Newswire releases from Mercy For Animals, not Globe journalism. See UNVERIFIED.

**On-air framing (rule 6):** say only "In 2016 they said X by end-2025. Their own latest reports say Y." No adjectives, no motive. Use the dated figures in 9b with their bases. Loblaw's base changes between years (control brand in 2023, all category sales in 2024 and 2025). Metro reports both "offering" and "sales".

---

## 10. Named Canadian consumer surveys on egg housing and labels

| Survey | Publisher / commissioner | Date | Sample and method (as published) | Wording available | Results (as published) |
|---|---|---|---|---|---|
| D1 | **Bryant Research** (U.K. firm). Released in Canada by **Mercy For Animals** (advocacy group) | Fieldwork "in May" 2023 (MFA release); Bryant page 2023-06-23; MFA CNW release 2023-06-26 | "1,005 residents of Canada"; "recruited to be representative of Canada in terms of age, gender, and region"; respondents "were shown photographs of various laying hen conditions, and asked for their opinions about the obligations of food companies." Mode (online or other) and exact field dates are **not stated** on the pages opened | Exact question wording is **not published** on the pages opened. The paraphrase is "whether they think it is acceptable to confine egg-laying hens in battery cages, or in enriched cages" | "80% found battery cages unacceptable, while 75% found enriched cages unacceptable – just 7% and 12% found these systems acceptable respectively." "87% agree that stores and restaurants should be transparent about the types of eggs they use in their supply chains." "79% say that grocery stores and restaurants should commit to banning cage sourced eggs altogether." "63%, say they are willing to pay more for cage-free eggs, with just 11% ruling this out." Manitoba Co-operator (B7) adds: "25 per cent were unsure" |
| D2 | **Bryant Research "on behalf of Animal Justice"** (advocacy group). Report "written by Elise Hankins and Chris Bryant" | Published 2024-03-26 | "a recent survey of 1,006 Canadian residents"; "representative across age, gender, and province"; respondents shown images of packaging. Percentages are reported for "the subset of respondents who stated that they have purchased the corresponding type of eggs." Field dates and mode are **not stated** | Respondents "were shown images of common egg packaging and asked what type of housing they believed the corresponding egg-laying hens experience". The "correct" answers are **the publisher's own definitions** | "Nestlaid" packaging: "only 21% of consumers correctly answered that these hens are held in larger indoor metal cages with 10 to 100 hens per cage. Most respondents (57%) believed these hens were housed in better, cageless conditions." "Free run": "only 14% of consumers correctly answered that, while housed in a cageless system, these hens are held indoors 24/7." "Free range": "only 24% of consumers correctly answered…" "Across all egg labels tested, the majority of consumers (52 to 74%) reported that they have deliberately spent more on specific eggs…" |

**Caveats (must accompany any on-air use):**
- Both surveys were commissioned or released by **animal-advocacy organizations**.
- Neither published the full questionnaire or field dates on the pages opened.
- D2 scores answers as "correct" against the publisher's own housing descriptions. Attribute every figure, for example: "a 2024 survey of 1,006 Canadians by Bryant Research for the advocacy group Animal Justice found…".
- D2 names a brand (Burnbrae's Naturegg and Nestlaid). For brand descriptions, use only Burnbrae's own words, which are not in this file. Do not repeat the publisher's characterizations of the brand.

**Not tier (d): EFC-cited polling.**
- EFC 2025 AR: "86% of Canadians believe supply management keeps egg prices stable." Footnote: "Abacus Data (2025). National Omnibus Survey. [Unpublished raw data]. Prepared for EFC."
- EFC 2025 AR: "7 in 10 Canadians believe the federal government should prioritize food self-sufficiency" (same footnote source).
- No sample, dates or wording are published. Attribute these only as "EFC says". See UNVERIFIED.

---

## Appendix R: Recalls and disease items (DO NOT USE ON AIR)

**DO NOT USE ON AIR.** This list records material **excluded** from the body under house rule 1, so producers know it exists and keep it out:

- EFC 2023, 2024 and 2025 Annual Reports (A8–A10): every passage giving avian-influenza or "HPAI" as a reason for quota, STMRQ, imports or flock numbers. This includes "Domestic cases of HPAI on Canadian egg farms jumped quickly in late 2024 and early 2025, with 1.2 million hens impacted within a four-month period", and the U.S. "crisis" sentences around the Urner Barry price.
- EFC 2025 AR: the protocol to "vaccinate all hens against Salmonella Enteritidis (SE)", and all EQA "food safety" language.
- EFC 2024 AR: the National SE Protocol recommendations.
- FPCC/EFC request letters (A17): HPAI rationale paragraphs (Nov 15, 2023; Nov 18, 2024; Mar 19, 2025). The July 2026 letter's background on vaccine production and the pandemic.
- Costco 2025 report (A40): "In FY25, cage-free eggs were a smaller percentage of our eggs sold due to the impact of avian flu globally", and footnotes 1 and 3, which mention "food safety practices" and "High Pathogenic Avian Influenza".
- RBI reports (A41): footnotes on "higher exposure of cage-free birds to Avian Influenza" and "safety of our guests".
- Metro FY2025 report (A38): "enriched cages have their own advantages, such as more effective prevention of disease and injury."
- CBC B1 and B2: all sentences attributing U.S. prices to bird-flu outbreaks, and the hen-loss figures.
- **Recalls:** no egg-recall research was done for this file. Any recall item found later goes here only.

---

## UNVERIFIED / DO-NOT-USE

1. **Sobeys' current SBR page** (A36) returned **HTTP 403** to curl and WebFetch. The text is from Internet Archive snapshots of Sobeys' own page (2026-01-01 and 2026-07-11, identical egg text). Re-open live in a browser before an on-screen quote.
2. **McDonald's Canada's 2024 release** (A42): the live page returned 403. The text is from a Wayback snapshot of 2024-06-07. Canadian Poultry Magazine (B8) reports the same facts. The 2015 pledge page also returned 403 and was not opened.
3. **A&W Canada's current egg policy.** web.aw.ca is JS-rendered, and no egg text was retrievable. A&W's 2016 release (A43) and CBC's 2023 paraphrase (B5) are the latest dated record here. **Do not state A&W's current status.**
4. **FPCC decisions page (A16)** was read via WebFetch only, a tool-extracted listing. It showed no entries for the Oct 2025 (SOR/2025-204) or Dec 2025 (SOR/2025-284/-285) approvals, which the Gazette shows were approved. The listing may be incomplete.
5. **Retail Insider, Oct 2025, "Canadian Retailers Falling Short on Cage-Free Egg Pledges"** (and the Mercy For Animals 2025 scorecard it reports) was blocked by a bot check and **not opened**. Do not use the figures from search snippets: "Loblaws 16%", "Sobeys 17–18%", "Costco 21.3%".
6. **No 2025–2026 CBC, Globe, CP or CTV news assessment** of whether the RCC grocers met the end-2025 pledge was found. Globe search results were PR Newswire reposts of Mercy For Animals releases (tier c). The National Observer item of 2025-09-25 is an **opinion** column and was not used.
7. **[U.S.] Section 338 annexes** (July 20 and Sept 8, 2026 product lists) were not opened. Whether any egg HTS codes are on the lists is unknown. The opened texts name dairy, cars and alcohol.
8. **Canada's Sept 8, 2026 retaliatory surtax list** was not opened from a Government of Canada source. Whether eggs are on it is unknown, and so is the White House claim that Canada "broke off trade talks" [U.S. claim].
9. **[U.S.] DOJ settlement terms.** The figures "$3.3 million" and "53 million eggs donated" appear in media (Axios, Fortune; tier c). They are not in the DOJ release opened (A30). U.S. private class actions (for example, those filed Nov 2025 naming Urner Barry and producers) were **not opened**.
10. **USTR 2025 National Trade Estimate** was not opened. Only the 2026 NTE (A23) was used.
11. **D1 survey:** exact field dates, mode, full questionnaire and commissioning party were not found. MFA's release says "conducted by UK-based Bryant Research in May".
12. **D2 survey:** field dates and mode were not stated. Its housing percentages ("51.17%", "31.58%") are the publisher's figures, not EFC's current data.
13. **EFC-cited Abacus Data polling** ("86%", "7 in 10") is "[Unpublished raw data]" with no methodology. EFC's "Environics… National Egg Consumption Omnibus Survey" (Sept 2025) is the same: unpublished. Not tier d.
14. **AAFC "no request" quote** comes via CBC (B1) only. No AAFC primary statement was found.
15. **[U.S.] CBP seizure figures** come via CBC (B2) only. The CBP primary data was not opened.
16. **RBI "Canada 27%"** covers RBI brands in Canada (Tim Hortons, Burger King, Popeyes, Firehouse). A Tim Hortons-only figure is not published. Say "RBI, which owns Tim Hortons, reports 27% for Canada".
17. **Costco's fiscal year** ("FY25") end-date was not verified. Do not convert it to a calendar year.
18. **Walmart Canada calendar-2025 figure:** none is published on the page opened (A39). The latest is calendar 2024 (≈9%).
19. **Loblaw's bases differ.** 2023 is "control brand category sales". 2024 and 2025 are "all/total category sales". Do not present 19.5% → 16% → 18% as one trend.
20. **CIMT data end at July 2026.** The 2026 bulk file is version 202607 (dated 2026-08-17 and 2026-08-21). Figures after July 2026 are not covered.
21. **CIMT export destination "FR"** (32,466 dozen of 0407.21 in 2025) is as coded by StatCan. Whether it refers to metropolitan France or French overseas territories was not verified.
22. **2026 over-access imports (0407.21.20)** of 840,525 dozen were declared at about $0.71/dozen. Whether duty was paid, or the goods entered under a duty-relief or remission program, is not shown in CIMT. Do not characterize it.
23. **Canadian legal search.** The CanLII and Competition Bureau searches were web searches only; the CanLII database itself was not queried directly. The absence of items is "not found", not "none exist". The Ontario "Security from Trespass and Protecting Food Safety Act" litigation (2024 ONSC, 2025 ONCA) concerns farm access generally. It was not opened, and it is excluded.
24. **The Animal Justice 2012 Competition Bureau request** is an advocacy release (tier c for the substance). It is outside the window, and the outcome is unknown. Not for air.
25. **The EFC 2023 "more than 837 million dozen" figure.** EFC does not reconcile it with StatCan (876.3 million dozen including hatching eggs). Do not compare the two directly.
26. **EFC Free Range Standards Certification Program.** Whether it was implemented "in early 2026" was not verified, and no standard text was found.
27. **The Global Affairs "Key dates and access quantities 2026-2027" page** was not re-opened for this file. The access quantities used are from the EICS utilization reports (A20).
28. **The StatCan monthly egg table (A2)** was released 2026-07-31 with data to May 2026. Check for a newer release before broadcast.
29. **[U.S.] BLS October 2025** is missing ("Data unavailable due to the 2025 lapse in appropriations"). Do not interpolate it.
30. **The 0407.29 exports to the U.S.** (3.67 million dozen in 2025) are "Birds' eggs… o/t of fowls of species Gallus domesticus". The species is unknown. **Never** describe them as hen or table eggs sent to the U.S.
