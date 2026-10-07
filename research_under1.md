# RESEARCH — 15 Foods That Still Cost Under $1 a Serving in Canada (Oct 8, 2026)

Compiled from five research dossiers captured on 2026-10-07 UTC. Raw captures are in the session scratchpad (not committed).


======================================================================

# U1 PRICES DOSSIER: 15 Foods That Still Cost Under $1 a Serving in Canada (October 2026 Prices)

Prepared 7 October 2026 for Canadian Counter (upload 8 October 2026, 20:00 UTC).
Scope: prices, label servings, cost per serving, ranking. No health, nutrition, taste or food-safety content is included or implied. Serving sizes are quoted only as the label or retailer unit used for price division.

## 0. Capture facts (read first)

- **Primary store:** Bo's NO FRILLS Toronto Richmond, store #7952, 261 Richmond St W, Toronto ON M5V 3M6 (store list in the PC Express pickup-locations data).
- **Method:** PC Express API (`api.pcexpress.ca/pcx-bff/api/v1/products/search` and `/products/{code}`), the same data that drives nofrills.ca, banner `nofrills`, pickup type STORE.
- **Capture time:** 01:55 to 02:01 UTC, 7 October 2026. That is 9:55 to 10:01 pm EDT on 6 October in Toronto. The API was queried with the store date `07102026`, so the prices are the ones listed for **7 October 2026**. In the script, say "listed on nofrills.ca for the Richmond Street West No Frills in Toronto on the seventh of October 2026."
- **Flyer timing problem:** most SALE and SPECIAL prices captured **expire 2026-10-07**. That is the last day of the flyer week; the new No Frills week starts Thursday 8 October, which is upload day. **Do not quote any sale price as current in the video.** Every ranking below uses REGULAR prices.
- **How regular prices were established:** (a) for REGULAR items, the price captured; (b) for SALE items, the "was" price; (c) for items tagged SPECIAL with no "was" price, the API was queried again with the store date set to 8 October 2026 (`date=08102026`). It returned type REGULAR with no expiry. For the two items still on special on 8 October (Becel, canned corn), the date was set to 15 October 2026. These forward-dated reads are the API's scheduled regular price. **They are not a shelf observation.** The 8 October flyer specials may not have been loaded yet. **Re-capture on the morning of 8 October** before locking the script (see section 7).
- **Hand maths:** every cost per serving and per 100 g below was computed by hand from price and pack size. The API `comparisonPrices` field was **not** used. As a check, the API values were compared with the hand maths for every search result. All 15 picks matched to within rounding, but eight other SKUs were wrong (section 6).
- **Raw JSON:** `/tmp/claude-0/-home-user-Food/63b91656-26a4-59d5-baf9-bd65edc4c0dd/scratchpad/u1/` (`nofrills_7952/`, `nofrills_3403/`, `nofrills_3155/`, `loblaw_1000/`; `search/`, `p/`, `p_date08102026/`, `p_date15102026/`). There are 299 JSON files plus `capture_log.tsv`, which records the UTC timestamp, date parameter, banner, store and file for each request. The capture tool is `scratchpad/u1tools/cap.py` and the table generator is `u1tools/calc.py`.

## 1. RECOMMENDED FINAL 15 (countdown: #15 is the most expensive per serving, #1 the cheapest)

All prices are at No Frills #7952, 261 Richmond St W, Toronto, captured 7 Oct 2026 (01:55 to 02:01 UTC). "Reg" means regular price. Cost per serving = regular price divided by (pack size / label serving).

| # | Item (brand, product, size, code) | Category | Reg price | Label serving | Servings/pack | **Reg $/serving** | Reg $/100 g (ml) | Notes |
|---|---|---|---|---|---|---|---|---|
| 15 | No Name Large Size Eggs, 12 pack, 20812144001_EA | Dairy & eggs | $3.93 | 105 g (NFt) = 2 large eggs* | 6 | **$0.655** | n/a (sold by count); $0.3275/egg | *105 g read as 2 eggs is an inference (section 8). The 30-pack (21435777001_EA, $10.04) costs **more per egg**: $0.3347 against $0.3275. |
| 14 | No Name Flaked Light Tuna Packed in Water, 170 g, 20521648_EA | Canned | $1.29 (sale $1.00 ended 7 Oct) | 55 g | 3.09 | **$0.417** | $0.759 | Clover Leaf Flaked Light 170 g is $1.99 reg (20573583_EA), which works out to $0.644/serving if its label serving is also 55 g (not checked). |
| 13 | Neilson 2% Milk, 4 L bags, 20188873_EA | Dairy & eggs | $6.44 | 250 ml (1 cup) | 16 | **$0.403** | $0.161/100 ml | No store-brand 4 L milk was listed at this store. |
| 12 | No Name Assorted Sizes Green Peas (frozen), 750 g, 20312260_EA | Frozen | $3.00 (sale $2.77 ended 7 Oct) | 85 g | 8.82 | **$0.340** | $0.400 | Frozen mixed vegetables and frozen corn (No Name 750 g) are identical: $3.00 and $0.340. |
| 11 | No Name Diced Tomatoes, 796 ml, 20600787_EA | Canned | $2.00 | 129 ml | 6.17 | **$0.324** | $0.251/100 ml | |
| 10 | No Name Original Bread (white), 675 g, 21509822_EA | Grains | $2.48 | 75 g | 9.00 | **$0.276** | $0.367 | In Vancouver and Calgary the same name is a **520 g** loaf, 21509610_EA, at $2.50 (section 3). |
| 9 | Farmer's Market Carrots, 3 lb bag (1.362 kg), 20600927001_EA | Produce | $3.49 | 100 g (retailer-listed; produce has no NFt) | 13.62 | **$0.256** | $0.256 | |
| 8 | No Name Chickpeas (canned), 540 ml, 20325921001_EA | Legumes/canned | $1.50 | 86 ml | 6.28 | **$0.239** | $0.278/100 ml | No Name kidney beans ($0.253) or canned lentils ($0.264) can be swapped in at the same price. |
| 7 | Bananas, bunch, sold by weight, 20175355001_KG | Produce | $1.52/kg (API estimate $1.75 for a 1.15 kg bunch) | 140 g (retailer-listed) | per kg: 7.14 | **$0.213** | $0.152 | Priced by weight, so a single bunch costs a different amount. |
| 6 | No Name Spaghetti, 900 g, 20315613002_EA | Grains | $2.00 | 85 g (dry) | 10.59 | **$0.189** | $0.222 | Barilla Spaghetti 410 g is $2.50 reg, or $0.61/100 g. |
| 5 | PC Blue Menu Red Split Lentils (dry), 900 g, 20629496_EA | Legumes | $3.79 | 35 g (dry) | 25.71 | **$0.147** | $0.421 | No No Name dry lentils were listed at #7952. |
| 4 | Farmer's Market White Potatoes, 10 lb bag (4.54 kg), 20600997001_EA | Produce | **$5.99 (Oct 8 API regular)**; on 7 Oct it was $1.99 SPECIAL, ending 7 Oct | 100 g (retailer-listed) | 45.4 | **$0.132** | $0.132 | **Re-check the shelf price on 8 Oct.** At the $1.99 sale price it would be $0.044/serving. The Yellow 10 lb bag (20601017001_EA) is $6.99 reg = $0.154. |
| 3 | No Name Popping Corn, 1 kg, 21291313_EA | Pantry | $2.50 | 50 g (unpopped) | 20 | **$0.125** | $0.250 | Orville kernels 850 g are $5.99 reg, or $0.70/100 g. |
| 2 | No Name Large Flake 100% Whole Grain Oats, 1 kg, 20923994_EA | Grains | $3.00 (tagged SPECIAL to 7 Oct at $3.00; Oct 8 regular $3.00) | 40 g | 25 | **$0.120** | $0.300 | Quaker Large Flake 1 kg is $4.00 reg, or $0.40/100 g. |
| 1 | No Name Long Grain White Rice, 2 kg, 20069589_EA | Grains | $5.00 | 45 g (dry) | 44.44 | **$0.1125** | $0.250 | The 8 kg Club Size (20156226_EA, $15.49) is $0.087/serving, $0.194/100 g. |

Categories covered: grains (5), produce (3), legumes (2), canned (3, including chickpeas), dairy & eggs (2), frozen (1), pantry (1). No item in the 15 uses a padding serving.

**Spread for the script:** the most expensive pick is 65.5 cents per serving (eggs) and the cheapest is 11.25 cents (rice). The cheapest four (rice, oats, popcorn, potatoes) are all between 11 and 14 cents, so they are separated by fractions of a cent. Say the exact figure for each, never "the same."

### Three alternates (in the same ranking logic)

| Alt | Item | Reg price | Serving | Servings | Reg $/serving | $/100 g | Why it is an alternate |
|---|---|---|---|---|---|---|---|
| A1 | No Name Smooth Peanut Butter, 1 kg, 20296985001_EA | $4.50 (tagged SPECIAL to 7 Oct; Oct 8 regular $4.50) | 15 g (NFt; Kraft lists 1 tbsp) | 66.67 | **$0.0675** | $0.450 | It would rank #1, but the label serving is a 15 g tablespoon, which is close to padding. If used, say "one tablespoon." **Brand pair:** Kraft Smooth Peanut Butter 1 kg (20039581001_EA) is $6.50 reg = $0.0975/serving, $0.65/100 g. No Name is $2.00 less per kilo at this store. No Name 500 g (20316212001_EA) is $2.99 = $0.598/100 g, so the 1 kg is cheaper per gram. |
| A2 | Green cabbage, sold by weight, 20793034001_KG | $2.76/kg (API estimate $4.64 for a 1.68 kg head) | 100 g (retailer-listed) | per kg: 10 | **$0.276** | $0.276 | Could replace carrots or bread at #9 or #10. |
| A3 | No Name Naturally Imperfect Apples, 6 lb bag (2.72 kg), 20868985001_EA | $7.50 (Oct 8 API regular; $7.00 SPECIAL on 7 Oct, no "was") | 100 g (retailer-listed) | 27.2 | **$0.276** | $0.276 | Adds a second fruit. The Farmer's Market McIntosh or Gala 4 lb bag is $7.99 reg = $0.441. |

Other swaps that hold the order: PC Blue Menu Yellow Split Peas 2 kg (21307041_EA) $5.50 = $0.096; Suraj Yellow Split Peas 1.8 kg (20558865_EA) $4.29 reg = $0.083; Farmer's Market Yellow Onions 3 lb (20811994001_EA) $3.49 = $0.257; No Name Tomato Sauce 680 ml (20120683_EA) $2.00 = $0.185 per 63 ml.

## 2. FULL CANDIDATE TABLE: No Frills #7952 Toronto, 7 Oct 2026, sorted by regular cost per serving (high to low)

NFt = serving size read from the product's own `nutritionFacts` (servingSizeEN) in the PC Express product record. For fresh produce, no Nutrition Facts table is required on the pack, so the serving shown is the one the retailer lists in the same field, and per 100 g is the safer unit to say aloud.

| Item | Brand | Code | Pack | Price Oct 7 (type) | Was / sale ends | Regular used (source) | Label serving | Servings/pack | REG $/serving | REG $/100 g or ml | Sale $/serving | Category | Flag |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Roasted Garlic Pasta Sauce | President's Choice | 21734387_EA | 600 ml | $3.49 (REG) | — | $3.49 (today REG) | 131 ml (NFt) | 4.58 | **$0.762** | $0.582 | $0.762 | Pantry |  |
| Large Size Eggs 30 | No Name | 21435777001_EA | 30 eggs | $10.04 (REG) | — | $10.04 (today REG) | 105 g (NFt); 2 large eggs assumed | 15.00 | **$0.669** | n/a (sold by count) | $0.669 | Dairy & eggs |  |
| Large Size Eggs 12 Pack | No Name | 20812144001_EA | 12 eggs | $3.93 (REG) | — | $3.93 (today REG) | 105 g (NFt); 2 large eggs assumed | 6.00 | **$0.655** | n/a (sold by count) | $0.655 | Dairy & eggs |  |
| 10 Original Tortillas | No Name | 21064398_EA | 320 g (10) | $2.69 (REG) | — | $2.69 (today REG) | 64 g (NFt) = 2 tortillas by weight | 5.00 | **$0.538** | $0.841 | $0.538 | Grains |  |
| Loads of Raisins Raisin Bran Cereal | President's Choice | 20775732_EA | 625 g | $5.50 (REG) | — | $5.50 (today REG) | 55 g (NFt) | 11.36 | **$0.484** | $0.880 | $0.484 | Grains | store-brand cereal |
| McIntosh Apples, 4 lb Bag | Farmer's Market | 20713211001_EA | 1.81 kg | $4.99 (SPECIAL) | no was shown; ends 2026-10-07 | $7.99 (Oct 8 API REG) | 100 g (retailer-listed; produce) | 18.10 | **$0.441** | $0.441 | $0.276 | Produce |  |
| Gala Apples, 4 lb Bag | Farmer's Market | 20767998001_EA | 1.81 kg | $4.99 (SALE) | was $5.99; ends 2026-10-07 | $7.99 (Oct 8 API REG (was shown $5.99: CONFLICT)) | 100 g (retailer-listed; produce) | 18.10 | **$0.441** | $0.441 | $0.276 | Produce |  |
| Flaked Light Tuna Packed in Water | No Name | 20521648_EA | 170 g | $1.00 (SALE) | was $1.29; ends 2026-10-07 | $1.29 (was + Oct 8 API REG) | 55 g (NFt) | 3.09 | **$0.417** | $0.759 | $0.324 | Canned |  |
| 2% Milk (bags) | Neilson | 20188873_EA | 4 L | $6.44 (REG) | — | $6.44 (today REG) | 250 ml / 1 cup (NFt) | 16.00 | **$0.403** | $0.161 | $0.403 | Dairy & eggs |  |
| Assorted Sizes Green Peas (frozen) | No Name | 20312260_EA | 750 g | $2.77 (SALE) | was $3.00; ends 2026-10-07 | $3.00 (was + Oct 8 API REG) | 85 g (NFt) | 8.82 | **$0.340** | $0.400 | $0.314 | Frozen |  |
| Mixed Vegetables (frozen) | No Name | 20301012_EA | 750 g | $2.77 (SALE) | was $3.00; ends 2026-10-07 | $3.00 (was + Oct 8 API REG) | 85 g (NFt) | 8.82 | **$0.340** | $0.400 | $0.314 | Frozen |  |
| Whole Kernel Corn (frozen) | No Name | 20306375_EA | 750 g | $2.77 (SALE) | was $3.00; ends 2026-10-07 | $3.00 (was + Oct 8 API REG) | 85 g (NFt) | 8.82 | **$0.340** | $0.400 | $0.314 | Frozen |  |
| Mixed Vegetables (canned) | No Name | 20312587_EA | 398 ml | $1.49 (REG) | — | $1.49 (today REG) | 90 ml (NFt) | 4.42 | **$0.337** | $0.374 | $0.337 | Canned |  |
| Diced Tomatoes | No Name | 20600787_EA | 796 ml | $2.00 (REG) | — | $2.00 (today REG) | 129 ml (NFt) | 6.17 | **$0.324** | $0.251 | $0.324 | Canned |  |
| Whole Kernel Corn (canned) | No Name | 21504776_EA | 341 ml | $1.25 (SPECIAL) | no was shown; ends 2026-10-14 | $1.25 (Oct 15 API REG) | 85 ml (NFt) | 4.01 | **$0.312** | $0.367 | $0.312 | Canned | SPECIAL tag but same as regular |
| Cabbage, Green (sold by weight) | (no brand) | 20793034001_KG | per kg; est. 1.68 kg head $4.64 | $2.76/kg (REG) | — | $2.76/kg (today REG, $/kg) | 100 g (retailer-listed; produce) | 10.00 | **$0.276** | $0.276 | $0.276 | Produce |  |
| Naturally Imperfect Apples, 6 lb Bag | No Name | 20868985001_EA | 2.72 kg | $7.00 (SPECIAL) | no was shown; ends 2026-10-07 | $7.50 (Oct 8 API REG) | 100 g (retailer-listed; produce) | 27.20 | **$0.276** | $0.276 | $0.257 | Produce |  |
| Original Bread (white) | No Name | 21509822_EA | 675 g | $2.48 (REG) | — | $2.48 (today REG) | 75 g (NFt) | 9.00 | **$0.276** | $0.367 | $0.276 | Grains |  |
| Lentils (canned) | No Name | 20325921004_EA | 540 ml | $1.50 (REG) | — | $1.50 (today REG) | 95 ml (NFt) | 5.68 | **$0.264** | $0.278 | $0.264 | Legumes/Canned |  |
| Yellow Onions, 3 lb Bag | Farmer's Market | 20811994001_EA | 1.36 kg | $3.49 (REG) | — | $3.49 (today REG) | 100 g (retailer-listed; produce) | 13.60 | **$0.257** | $0.257 | $0.257 | Produce |  |
| Carrots, 3 lb Bag | Farmer's Market | 20600927001_EA | 1.362 kg | $3.49 (REG) | — | $3.49 (today REG) | 100 g (retailer-listed; produce) | 13.62 | **$0.256** | $0.256 | $0.256 | Produce |  |
| Dark Red Kidney Beans (canned) | No Name | 20554593_EA | 540 ml | $1.50 (REG) | — | $1.50 (today REG) | 91 ml (NFt) | 5.93 | **$0.253** | $0.278 | $0.253 | Legumes/Canned |  |
| Chickpeas (canned) | No Name | 20325921001_EA | 540 ml | $1.50 (REG) | — | $1.50 (today REG) | 86 ml (NFt) | 6.28 | **$0.239** | $0.278 | $0.239 | Legumes/Canned |  |
| Naturally Imperfect Carrots | No Name | 20945332001_EA | 2.27 kg | $5.00 (SPECIAL) | no was shown; ends 2026-10-07 | $5.00 (Oct 8 API REG) | 100 g (retailer-listed; produce) | 22.70 | **$0.220** | $0.220 | $0.220 | Produce |  |
| Bananas, Bunch (sold by weight) | (no brand) | 20175355001_KG | per kg; est. 1.15 kg bunch $1.75 | $1.52/kg (REG) | — | $1.52/kg (today REG, $/kg) | 140 g (retailer-listed; no NFt on loose produce) | 7.14 | **$0.213** | $0.152 | $0.213 | Produce |  |
| Spaghetti | No Name | 20315613002_EA | 900 g | $2.00 (REG) | — | $2.00 (today REG) | 85 g (NFt) | 10.59 | **$0.189** | $0.222 | $0.189 | Grains |  |
| Elbow Macaroni | No Name | 20315613003_EA | 900 g | $2.00 (REG) | — | $2.00 (today REG) | 85 g (NFt) | 10.59 | **$0.189** | $0.222 | $0.189 | Grains |  |
| Tomato Sauce | No Name | 20120683_EA | 680 ml | $2.00 (REG) | — | $2.00 (today REG) | 63 ml (NFt) | 10.79 | **$0.185** | $0.294 | $0.185 | Canned | not a pasta sauce |
| Yellow Onions, 10 lb Bag | Farmer's Market | 20600991001_EA | 4.54 kg | $3.99 (SALE) | was $6.99; ends 2026-10-07 | $7.99 (Oct 8 API REG (was shown $6.99: CONFLICT)) | 100 g (retailer-listed; produce) | 45.40 | **$0.176** | $0.176 | $0.088 | Produce |  |
| Carrots, 10 lb Bag | Farmer's Market | 20600930001_EA | 4.54 kg | $3.99 (SPECIAL) | no was shown; ends 2026-10-07 | $6.99 (Oct 8 API REG) | 100 g (retailer-listed; produce) | 45.40 | **$0.154** | $0.154 | $0.088 | Produce |  |
| Yellow Potato, 10 lb Bag | Farmer's Market | 20601017001_EA | 4.54 kg | $1.99 (SPECIAL) | no was shown; ends 2026-10-07 | $6.99 (Oct 8 API REG) | 100 g (retailer-listed; produce) | 45.40 | **$0.154** | $0.154 | $0.044 | Produce |  |
| Red Split Lentils (dry) | PC Blue Menu | 20629496_EA | 900 g | $3.79 (REG) | — | $3.79 (today REG) | 35 g (NFt) | 25.71 | **$0.147** | $0.421 | $0.147 | Legumes |  |
| Green Lentils (dry) | PC Blue Menu | 20629679_EA | 900 g | $3.79 (REG) | — | $3.79 (today REG) | 35 g (NFt) | 25.71 | **$0.147** | $0.421 | $0.147 | Legumes |  |
| Black Turtle Beans (dry) | PC Blue Menu | 20629153_EA | 900 g | $3.79 (REG) | — | $3.79 (today REG) | 35 g (NFt) | 25.71 | **$0.147** | $0.421 | $0.147 | Legumes |  |
| White Potatoes, 10 lb Bag | Farmer's Market | 20600997001_EA | 4.54 kg | $1.99 (SPECIAL) | no was shown; ends 2026-10-07 | $5.99 (Oct 8 API REG) | 100 g (retailer-listed; produce) | 45.40 | **$0.132** | $0.132 | $0.044 | Produce |  |
| Popping Corn | No Name | 21291313_EA | 1 kg | $2.50 (REG) | — | $2.50 (today REG) | 50 g (NFt) | 20.00 | **$0.125** | $0.250 | $0.125 | Pantry |  |
| Large Flake 100% Whole Grain Oats | No Name | 20923994_EA | 1 kg | $3.00 (SPECIAL) | no was shown; ends 2026-10-07 | $3.00 (Oct 8 API REG) | 40 g (NFt) | 25.00 | **$0.120** | $0.300 | $0.120 | Grains | SPECIAL tag but same as regular |
| Long Grain White Rice | No Name | 20069589_EA | 2 kg | $5.00 (REG) | — | $5.00 (today REG) | 45 g (NFt) | 44.44 | **$0.113** | $0.250 | $0.113 | Grains |  |
| Margarine Original | Becel | 21747692_EA | 800 g | $6.99 (SPECIAL) | no was shown; ends 2026-10-14 | $8.99 (Oct 15 API REG) | 10 g / 2 tsp (NFt) | 80.00 | **$0.112** | $1.124 | $0.087 | Pantry | PADDING |
| Smooth Peanut Butter | Kraft | 20039581001_EA | 1 kg | $6.50 (REG) | — | $6.50 (today REG) | 15 g / 1 tbsp (NFt) | 66.67 | **$0.097** | $0.650 | $0.097 | Pantry | SMALL serving (1 tbsp) |
| Yellow Split Peas Club Size (dry) | PC Blue Menu | 21307041_EA | 2 kg | $5.50 (REG) | — | $5.50 (today REG) | 35 g (NFt) | 57.14 | **$0.096** | $0.275 | $0.096 | Legumes |  |
| Smooth Peanut Butter | No Name | 20316212001_EA | 500 g | $2.99 (REG) | — | $2.99 (today REG) | 15 g (NFt) | 33.33 | **$0.090** | $0.598 | $0.090 | Pantry | SMALL serving (1 tbsp) |
| Long Grain White Rice Club Size | No Name | 20156226_EA | 8 kg | $15.49 (REG) | — | $15.49 (today REG) | 45 g (NFt) | 177.78 | **$0.087** | $0.194 | $0.087 | Grains |  |
| Yellow Split Peas (dry) | Suraj | 20558865_EA | 1.8 kg | $3.49 (SALE) | was $4.29; ends 2026-10-07 | $4.29 (was + Oct 8 API REG) | 35 g (NFt) | 51.43 | **$0.083** | $0.238 | $0.068 | Legumes |  |
| Vegetable Oil Margarine Original | I Can't Believe It's Not Butter! | 21747538_EA | 400 g | $1.89 (SALE) | was $3.29; ends 2026-10-07 | $3.29 (was + Oct 8 API REG) | 10 g / 2 tsp (NFt) | 40.00 | **$0.082** | $0.823 | $0.047 | Pantry | PADDING |
| Smooth Peanut Butter | No Name | 20296985001_EA | 1 kg | $4.50 (SPECIAL) | no was shown; ends 2026-10-07 | $4.50 (Oct 8 API REG) | 15 g (NFt) | 66.67 | **$0.067** | $0.450 | $0.067 | Pantry | SMALL serving (1 tbsp) |
| All-Purpose Flour | No Name | 20013256_EA | 2.5 kg | $3.79 (REG) | — | $3.79 (today REG) | 30 g (NFt) | 83.33 | **$0.045** | $0.152 | $0.045 | Pantry | ingredient |
| Granulated Sugar | Lantic | 20145033_EA | 2 kg | $1.99 (SALE) | was $2.99; ends 2026-10-07 | $2.99 (was + Oct 8 API REG) | 4 g / 1 tsp (NFt) | 500.00 | **$0.006** | $0.149 | $0.004 | Pantry | PADDING |


### Flags

- **Over $1 per serving at regular price: none.** Every candidate captured is under $1 at regular price. The highest is PC Roasted Garlic Pasta Sauce (21734387_EA) at $0.762 per 131 ml serving. Eggs come next at $0.655 for 2 eggs (12-pack) and $0.669 (30-pack).
- **Padding (tiny label servings; do not use as list items):** Lantic Granulated Sugar, 4 g / 1 tsp ($0.006/serving); I Can't Believe It's Not Butter! margarine, 10 g / 2 tsp ($0.082); Becel Original, 10 g ($0.112); Imperial 55% margarine 800 g (21747711_EA), $8.29 reg, 10 g ($0.104).
- **Borderline small servings:** peanut butter at 15 g (all three SKUs) and all-purpose flour at 30 g. Flour is an ingredient, not something eaten on its own, so leave it out.
- **Candidates not stocked as store brand at #7952:** No Name 4 L milk (only Neilson listed); No Name dry lentils (PC Blue Menu used, which is also a Loblaw store brand); No Name granulated sugar (only Lantic listed); No Name margarine (none listed); No Name ready-to-eat cereal (none listed; PC Loads of Raisins Raisin Bran used); No Name pasta sauce (only No Name Tomato Sauce, which is not a seasoned pasta sauce). Catelli Garden Select Tomato & Basil 600 ml (21619105_EA) is $2.69, but the API gave no serving size.
- **"SPECIAL" tags with no discount:** the oats, canned corn and No Name peanut butter were tagged SPECIAL at the same price the API returns as REGULAR for the next week. In the script, do not call these "sale" prices.

## 3. SECOND-CITY AND SECOND-BANNER CHECK (regular prices; captured 7 Oct 2026, 01:58 to 02:01 UTC)

Stores (from PC Express pickup-location records):
- **Vancouver:** Joti's NOFRILLS Vancouver, store #3403, 310 W Broadway, Vancouver BC V5Y 1R2
- **Calgary:** Kevin's NOFRILLS Calgary, store #3155, 10233 Elbow Dr SW, Calgary AB T2W 1E8
- **Alternate banner:** Loblaws Queen Street, store #1000, 585 Queen St W, Toronto (about 1.5 km from the No Frills)

Regular prices only. Where the item was on sale, the regular price is the "was" price or the 8 October API regular price, as marked. Cost per serving uses the same label serving as Toronto unless noted.

| # | Item | NF Toronto #7952 | NF Vancouver #3403 | NF Calgary #3155 | Loblaws Queen St Toronto #1000 |
|---|---|---|---|---|---|
| 15 | No Name Large Eggs 12 | $3.93 → $0.655 | $4.26 → $0.710 | $4.23 → $0.705 | $3.93 → $0.655 |
| 14 | No Name Flaked Light Tuna 170 g | $1.29 → $0.417 | $1.29 (Oct 8 reg; $1.00 sale to 7 Oct) → $0.417 | $1.29 → $0.417 | **$2.00** → $0.647 |
| 13 | 2% milk 4 L (brand differs) | Neilson $6.44 → $0.403 | Dairyland (20962518_EA) $5.81 → $0.363 | Beatrice (20658152_EA) $6.35 → $0.397 | Neilson $6.44 → $0.403 |
| 12 | No Name Frozen Green Peas 750 g | $3.00 → $0.340 | $3.00 → $0.340 | $3.00 → $0.340 | $3.79 → $0.430 |
| 11 | No Name Diced Tomatoes 796 ml | $2.00 → $0.324 | $2.00 → $0.324 | $2.00 → $0.324 | $2.29 → $0.371 |
| 10 | No Name Original Bread | 675 g $2.48 → $0.276 ($0.367/100 g) | **520 g** $2.50 (21509610_EA, 58 g serving) → $0.279 ($0.481/100 g) | **520 g** $2.50 → $0.279 ($0.481/100 g) | 675 g $2.48 → $0.276 |
| 9 | Carrots bag | 3 lb $3.49 → $0.256/100 g | 3 lb bag not listed; 2 lb $3.99 ($0.440/100 g); 5 lb (20600928001_EA) $6.49 ($0.286/100 g) | same as Vancouver | 3 lb $3.50 (Oct 8 reg; $3.00 sale to 7 Oct) → $0.257 |
| 8 | No Name Chickpeas 540 ml | $1.50 → $0.239 | $1.50 → $0.239 | $1.50 → $0.239 | $1.79 → $0.285 |
| 7 | Bananas, per kg (140 g serving) | $1.52/kg → $0.213 | $1.72/kg → $0.241 | $1.92/kg → $0.269 | $1.96/kg → $0.274 |
| 6 | No Name Spaghetti 900 g | $2.00 → $0.189 | $2.00 → $0.189 | $2.00 → $0.189 | $2.29 → $0.216 |
| 5 | PC Blue Menu Red Split Lentils 900 g | $3.79 → $0.147 | $3.79 → $0.147 | $3.79 → $0.147 | $4.00 reg (was; $3.50 sale to 14 Oct) → $0.156 |
| 4 | White Potatoes 10 lb | $5.99 (Oct 8 reg) → $0.132 | $6.99 → $0.154 | $6.99 → $0.154 | not captured |
| 4b | Yellow Potato 10 lb | $6.99 (Oct 8 reg) → $0.154 | $7.99 → $0.176 | $7.99 → $0.176 | $6.00 → $0.132 |
| 3 | No Name Popping Corn 1 kg | $2.50 → $0.125 | **$3.00** → $0.150 | **$3.00** → $0.150 | $3.49 → $0.175 |
| 2 | No Name Large Flake Oats 1 kg | $3.00 → $0.120 | $3.00 (Oct 8 reg) → $0.120 | $3.00 (Oct 8 reg) → $0.120 | $3.49 (was; Oct 8 reg) → $0.140 |
| 1 | No Name Long Grain White Rice 2 kg | $5.00 → $0.1125 | $5.00 → $0.1125 | $5.00 → $0.1125 | **$6.49** → $0.146 |
| A1 | No Name Smooth PB 1 kg / Kraft Smooth PB 1 kg | $4.50 / $6.50 | $4.50 / $6.50 | $4.50 / $6.50 | $6.00 / $7.99 (Oct 8 reg; "was $7.00" shown 7 Oct) |
| A2 | Green cabbage per kg (100 g serving) | $2.76 → $0.276 | $2.76 Oct 8 reg → $0.276 ($2.18/kg sale to 7 Oct, shown 'was $4.40' per 1.68 kg head) | same as Vancouver | $2.84 Oct 8 reg → $0.284 ($1.52/kg sale to 7 Oct, 'was $4.77' per head) |

Takeaways the script can use (all checkable in the raw JSON):
- The **packaged No Name staples** (rice, spaghetti, oats, chickpeas, diced tomatoes, frozen peas, lentils, tuna) had the **same regular price at No Frills in Toronto, Vancouver and Calgary**. The prices that differ by city are fresh produce (potatoes, bananas, carrots), eggs, milk, popcorn, and the bread loaf size.
- **Same banner, same city, different store:** across the 15, the Loblaws on Queen St W was equal to or higher than the No Frills on Richmond St W on every item but yellow potatoes. Rice 2 kg was $6.49 against $5.00; tuna $2.00 against $1.29; No Name peanut butter 1 kg $6.00 against $4.50. Both stores are owned by Loblaw Companies Limited. Present this as a price difference, not as wrongdoing.
- **Same name, smaller loaf out West:** No Name Original Bread is 675 g at $2.48 in Toronto and 520 g at $2.50 at both western stores. The product codes are different, so these are separate SKUs, not a change to one product. Say exactly that and imply nothing more.
- Even in the most expensive city captured, every one of the 15 stayed under $1 per serving. The highest was eggs at $0.710 in Vancouver.

## 4. STATCAN CROSS-CHECK (national average retail prices, table 18-10-0245-01)

- **Is the August 2026 data out?** No, as of 02:01 UTC on 7 October 2026. The full-table zip (`https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip`, files dated 2026-09-02) ends at **REF_DATE 2026-07**. The table page shows "Release date: 2026-09-02". The `latestN=5` download link returned "Failed to open stream for the full cube download". The latest usable month is **July 2026**.
- Canada, July 2026 averages (all brands and stores, so this is not a like-for-like comparison with a single No Frills store; use only as "the national average price"):
  - White rice 2 kg $9.62 (No Frills Toronto No Name: $5.00)
  - Eggs, 1 dozen $4.95 ($3.93)
  - Milk 4 L $6.99 ($6.44)
  - Dry or fresh pasta 500 g $3.45 (No Name 900 g $2.00)
  - Canned tomatoes 796 ml $2.27 ($2.00)
  - Canned tuna 170 g $1.84 ($1.29 reg)
  - Canned beans and lentils 540 ml $1.72 ($1.50)
  - Canned corn 341 ml $1.61 ($1.25)
  - Dried lentils 900 g $3.63 ($3.79, PC Blue Menu)
  - Frozen peas 750 g $3.83 ($3.00)
  - Frozen corn 750 g $3.87 ($3.00)
  - Carrots 1.36 kg $4.75 ($3.49)
  - Onions 1.36 kg $5.02 ($3.49)
  - Potatoes 4.54 kg $5.32 ($5.99 to $6.99 reg)
  - Bananas $1.88/kg ($1.52)
  - Apples $6.45/kg
  - Cabbage $2.90/kg ($2.76)
  - White bread 675 g $3.60 ($2.48)
  - Cereal 400 g $4.19
  - Peanut butter 1 kg $5.62 (No Name $4.50, Kraft $6.50)
  - Wheat flour 2.5 kg $5.36 ($3.79)
  - White sugar 2 kg $2.64 ($2.99 reg)
  - Margarine 907 g $6.09
  - Pasta sauce 650 ml $3.58
- One thing to note: for **potatoes 10 lb**, the No Frills Toronto regular price ($5.99 white, $6.99 yellow) is **above** the July national average for 4.54 kg ($5.32). That is a reason to keep potatoes as a "check the flyer" item and not to call them cheap in general.

## 5. SALE PRICES SEEN 7 OCT (for context only; all ended 7 Oct unless noted)

At #7952 Toronto:
- Yellow and White Potatoes 10 lb: $1.99 (regular $6.99 and $5.99)
- Yellow Onions 10 lb: $3.99, shown "was $6.99" (the Oct 8 API regular is $7.99, a conflict)
- Carrots 10 lb: $3.99 (regular $6.99)
- No Name Flaked Light Tuna: $1.00 (was $1.29)
- No Name frozen vegetables 750 g: $2.77 (was $3.00)
- Lantic sugar 2 kg: $1.99 (was $2.99)
- I Can't Believe It's Not Butter! 400 g: $1.89 (was $3.29)
- Gala apples 4 lb: $4.99, shown "was $5.99" (the Oct 8 API regular is $7.99, a conflict)
- McIntosh apples 4 lb: $4.99
- Becel Original 800 g: $6.99, runs to 14 Oct (regular $8.99 per the Oct 15 API read)

## 6. API DATA-QUALITY NOTES (why the hand maths matters)

The API `comparisonPrices` (unit price) disagreed with price divided by pack size on these SKUs in the 7 Oct #7952 search captures:

| Code | Product | Pack | Price | API unit price | Hand maths |
|---|---|---|---|---|---|
| 21613960_EA | PC Organics Unsweetened Apple Sauce | 620 ml | $3.50 | $5.65/100 ml | $0.565/100 ml |
| 21593622_EA | Barilla Cellentani Pasta | 340 g | $2.50 | $7.35/100 g | $0.735/100 g |
| 21610446_EA | Farm Girl Cinnamon Crisps Cereal | 280 g | $8.99 | $32.11/100 g | $3.21/100 g |
| 21393426_EA | Kraft Macaroni & Cheese Shapes | 156 g | $1.00 | $1.28/100 g | $0.64/100 g |
| 21310368_EA | PC Organics Unsweetened Apple Treat | 90 g | $4.00 | $0.37/100 g | $4.44/100 g |
| 20944993_EA | Minute Rice Jasmine | 125 g | $3.29 | $1.32/100 g | $2.63/100 g (the listing may be a multipack; unresolved) |
| 21335159_EA, 21335140_EA | Taylor Farms salad kits | 341 g / 336 g | $5.99 | $1.80 and $1.83 | $1.76 and $1.78 (small) |

At Vancouver #3403, No Name Naturally Imperfect Russet Potatoes 20 lb (20101572001_EA) showed a unit price of "$0.0/1ea".

None of the 15 picks or 3 alternates had a mismatch. Two **"was" prices conflict with the next-day regular price**: Yellow Onions 10 lb (was $6.99, Oct 8 regular $7.99) and Gala Apples 4 lb (was $5.99, Oct 8 regular $7.99). At Loblaws, Kraft PB showed "was $7.00" with an Oct 8 regular of $7.99. Do not use any of these in the script.

## 7. WHAT TO RE-CHECK ON 8 OCTOBER (before 20:00 UTC)

1. Re-run the product reads for the 15 picks and 3 alternates at #7952 with that day's date, ideally after 12:00 UTC (8 am ET):
   `D=08102026 python3 -I u1tools/cap.py p 7952 nofrills 20812144001_EA 20521648_EA 20188873_EA 20312260_EA 20600787_EA 21509822_EA 20600927001_EA 20325921001_EA 20175355001_KG 20315613002_EA 20629496_EA 20600997001_EA 21291313_EA 20923994_EA 20069589_EA 20296985001_EA 20793034001_KG 20868985001_EA`
   If any pick is on a new SALE, keep the regular price for the ranking and mention the sale only as dated.
2. Potatoes (#4) carry the most risk: the regular price comes only from a forward-dated API read. If the 8 Oct shelf price is not $5.99, re-rank or replace with Yellow Onions 3 lb ($0.257) or Yellow Split Peas.
3. Script price lines need retailer, store, city, date, pack size and unit price, for example: "At the No Frills on Richmond Street West in Toronto, listed on the seventh of October, a two-kilogram bag of No Name long grain white rice was five dollars. That's twenty-five cents per hundred grams. The label serving is forty-five grams, so the bag holds forty-four servings, at about eleven cents each." Add the house line once near the top: prices vary by location; check the shelf.

## 8. UNVERIFIED / DO-NOT-USE

- **Eggs "105 g = 2 large eggs."** The API gives only "105 g". The "2 eggs" household measure was **not** in the record. The 6-servings-per-dozen figure depends on this inference. Before saying "two eggs", confirm it against the carton's Nutrition Facts table, or say "the label serving of 105 grams". (Per egg, $0.3275, needs no inference.)
- **Tortillas "64 g = 2 tortillas."** This is inferred from 320 g divided by 10 tortillas, not stated in the record.
- **All forward-dated regular prices** (oats, No Name PB 1 kg, potatoes, carrots 10 lb, onions 10 lb, apples, Becel, canned corn, and the western oats, PB, tuna and peas) are the API's scheduled price, not a shelf observation. Treat them as UNVERIFIED until the 8 Oct re-capture.
- **"Was" prices for Yellow Onions 10 lb ($6.99), Gala Apples 4 lb ($5.99) and Loblaws Kraft PB ($7.00)** conflict with the next-day regular prices. Do not use them.
- **Sale prices that ended 7 Oct** (potatoes $1.99, tuna $1.00 and the rest in section 5). Do not present them as current on upload day.
- **"Prepared in Canada" badges.** The API shows a retailer "Prepared in Canada" badge on No Name oats, No Name and Kraft PB, PC Blue Menu lentils, split peas and black beans, No Name kidney beans, bread, tomato sauce and flour, Neilson milk, Lantic sugar, Suraj split peas and Catelli sauce. **This is a website badge, not label wording.** House rules allow the phrase only as exact label text, with the CFIA definition attributed, so do not use it unless the package is photographed. A CFIA page fetched 7 Oct (inspection.canada.ca, origin claims, last modified 2023-12-06) was summarised by a tool, not read verbatim. Re-read it word for word before quoting any definition.
- **Supplier or manufacturer of any No Name, PC, PC Blue Menu or Farmer's Market product:** not researched and **must not be inferred**. The API `disclaimer` strings (for example "NN RICE WHITE L.G.") are internal item descriptions, not supplier names.
- **Clover Leaf tuna cost per serving ($0.644):** assumes a 55 g serving; its product record was not fetched.
- **StatCan comparisons:** national averages cover all brands and outlets. Never say a No Frills price is "X% below the average price of the same product."
- **Any per-serving comparison of nutrients, any statement that an item is a good meal base, or any claim about how long items keep:** out of scope and banned by house rules.
- **Minute Rice Jasmine unit-price discrepancy:** cause unresolved (possibly a multipack listing). Do not cite it as an API error without a screenshot.

## 9. SOURCE REGISTER

| # | Source | URL / location | Accessed (UTC) | Tier |
|---|---|---|---|---|
| S1 | PC Express product search API, No Frills #7952 Toronto (search captures) | `https://api.pcexpress.ca/pcx-bff/api/v1/products/search` (banner nofrills, storeId 7952, date 07102026); raw: `u1/nofrills_7952/search/*.json` | 2026-10-07 01:55:36 to 01:56:36 | a (retailer's own listing data) |
| S2 | PC Express product detail API, #7952 (price, offer type, expiry, was price, nutritionFacts servingSizeEN) | `https://api.pcexpress.ca/pcx-bff/api/v1/products/{code}?storeId=7952&banner=nofrills&date=07102026`; raw: `u1/nofrills_7952/p/` | 2026-10-07 01:56:53 to 01:57:43 | a |
| S3 | Same, forward-dated 8 Oct 2026 (regular price on upload day) | `...&date=08102026`; raw: `u1/nofrills_7952/p_date08102026/` | 2026-10-07 01:57:55 to 01:58:15 | a (scheduled price; UNVERIFIED until shelf re-check) |
| S4 | Same, forward-dated 15 Oct 2026 (Becel, canned corn) | `...&date=15102026`; raw: `u1/nofrills_7952/p_date15102026/` | 2026-10-07 01:58:26 | a (scheduled) |
| S5 | PC Express, No Frills #3403 Vancouver (310 W Broadway), detail and search, today and 8 Oct | raw: `u1/nofrills_3403/` | 2026-10-07 01:59:06 to 01:59:53 | a |
| S6 | PC Express, No Frills #3155 Calgary (10233 Elbow Dr SW), detail and search, today and 8 Oct | raw: `u1/nofrills_3155/` | 2026-10-07 01:59:17 to 02:00:03 | a |
| S7 | PC Express, Loblaws #1000 Queen St (585 Queen St W, Toronto), detail today and 8 Oct | raw: `u1/loblaw_1000/` | 2026-10-07 02:00:16 to 02:00:41 | a |
| S8 | PC Express pickup-locations (No Frills store list) | `scratchpad/loc.json` (existing capture); Loblaws list `https://api.pcexpress.ca/pcx-bff/api/v1/pickup-locations?bannerIds=loblaw` → `u1/locations/loblaw.json` | loc.json earlier on 7 Oct; loblaw.json 2026-10-07 02:00 | a |
| S9 | Statistics Canada, Table 18-10-0245-01, Monthly average retail prices for selected products | `https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip` → `u1/statcan_dl/`; table page `https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810024501` (Release date 2026-09-02) | 2026-10-07 02:00:59 to 02:01 | a |
| S10 | StatCan latestN download link | `https://www150.statcan.gc.ca/t1/tbl1/en/dtl!downloadDbLoadingData-nonTraduit.action?pid=1810024501&latestN=5...` | 2026-10-07 02:00:5x | a (returned an error, no data) |
| S11 | CFIA, origin claims ("Product of Canada", "Made in Canada from...", "Prepared in Canada") | `https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims` | 2026-10-07 ~02:02 | a (tool summary only; re-read verbatim before quoting) |
| S12 | Capture log (every request: UTC time, date param, banner, store, file) | `u1/capture_log.tsv` | n/a | n/a (provenance) |
| none | No tier b, c or d sources used. | | | |

---

## GAP FIXES (critic), 7 Oct 2026, 02:19–02:26 UTC (full report: `scratchpad/u1_gaps.md`)

- **Recomputed from raw JSON:** all 15 cost-per-serving figures match this dossier to the tenth of a cent, and the #15→#1 order is correct. Log: `scratchpad/u1critic/recalc.txt`.
- **Ranking sensitivities:**
  - Potatoes swap with lentils (#4 and #5) if the 8 Oct regular price is **$6.70 or more** (break-even $6.69).
  - Carrots move to #8 if an 85 g serving is used instead of the retailer-listed 100 g. Keep 100 g.
  - Eggs drop to about #11 if one egg is a serving.
- **Clover Leaf resolved:** Flaked Light Tuna Skip Jack in Water 170 g (20573583_EA), detail record 02:21 UTC: serving **55 g**, $1.99 REGULAR → **$0.644/serving**. Remove it from section 8.
- **Brand pairs, per serving (detail records 02:21 UTC, #7952):**

| Product | Code | Label serving | Regular price | Per serving | Per 100 g |
|---|---|---|---|---|---|
| Quaker Large Flake 1 kg | 20323113002_EA | 40 g | $4.00 | **$0.160** | |
| Barilla Spaghetti 410 g | 21404912_EA | 85 g | $2.50 | **$0.518** | |
| Orville Original Gourmet Popping Corn Kernels 850 g | 20308686_EA | **63 g** | $5.99 | $0.444 | **$0.705** |

  The No Name popping corn serving is 50 g. Because the two servings differ, compare popcorn per 100 g, not per serving.
- **Distance correction:** #7952 and Loblaws #1000 are **0.84 km apart** in a straight line (store coordinates in `loc.json` and `u1/locations/loblaw.json`), not "about 1.5 km".
- **Ownership wording correction (section 3):** replace "Both stores are owned by Loblaw Companies Limited" with "both are Loblaw banners". Loblaw's own 16 Sep 2010 CNW release calls them "nofrills(R) banner stores". The pickup records show separate owner names.
- **Same price in three cities, exact count:** five at same-day REGULAR (rice, spaghetti, chickpeas, diced tomatoes, red lentils). Seven if peas ($3.00) and tuna ($1.29) are counted on the 7 Oct was-price, which the 8 Oct reads in all three cities also confirm. Eight with oats, which rests on forward reads only.
- **Data-quality flag:** the No Name Popping Corn (21291313_EA) record's `ingredients` field lists an unrelated product. It was unchanged on the 02:21 UTC re-fetch. Do not quote it. The 50 g serving is consistent with the record's other values. The record does not say "unpopped", so say "label serving of 50 grams".


======================================================================

# u1 — STATCAN DOSSIER: national-average cross-check and history
Project: "15 Foods That Still Cost Under $1 a Serving in Canada (October 2026 Prices)", upload 2026-10-08 20:00 UTC.
Compiled 2026-10-07, 01:55–02:00 UTC. Every figure here is a **Statistics Canada national average** (Canada, all regions combined). None of them is a store price. Do not present any of them as a No Frills, Toronto or shelf price.

---

## 1. Is August 2026 released? NO (as of 2026-10-07 01:59 UTC)

- Table 18-10-0245-01, *Monthly average retail prices for selected products*. The full-table CSV zip was re-downloaded at 2026-10-07 01:55 UTC (https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip, sha256 prefix 43cf3e6b). Its metadata says "End Reference Period 2026-07-01". The CSV inside is dated 2026-09-02 and is byte-identical in size to the 00:47 UTC extract already in `statcan/x/`.
- WDS `getCubeMetadata` (pid 18100245) returns `cubeEndDate 2026-07-01` and `releaseTime 2026-09-02T08:30`.
- WDS `getChangedCubeList` shows no 18-10-0245 change on 2026-09-14, 09-15, 09-16, 10-01, 10-02, 10-05, 10-06 or 10-07 (as of 01:59 UTC on Oct 7). The only 2026 change after July's release is 2026-09-02.
- The `latestN=5` link given in the brief returned "Failed to open stream for the full cube download" (HTTP 200, 48 bytes). The full zip and WDS were used in its place.
- **Release cadence**, from the WDS vector release times: each month's data comes out about five weeks after the month ends. June 2026 data came out 2026-08-05, July 2026 on 2026-09-02, and August 2025 on **2025-10-01**. That makes **August 2026 data due any day now**, plausibly 7 or 8 October at 08:30 ET (12:30 UTC). The StatCan release calendar page (cal2-eng.htm) renders through JavaScript and returned no average-price entry, so no date is confirmed.
- **ACTION:** re-run `getCubeMetadata` (or re-download the zip) at 12:35 UTC on Oct 7 and again on Oct 8 before lock. If `cubeEndDate` reads 2026-08-01, re-pull and replace the July lines below. Until that happens, every line says "**Statistics Canada national average, July 2026**".
- Source note on the July release: The Daily, "Monthly average retail prices for selected products, July 2026", released 2026-09-02 (https://www150.statcan.gc.ca/n1/daily-quotidien/260902/dq260902a-eng.htm).

---

## 2. Item-by-item: Statistics Canada national average (table 18-10-0245-01, GEO = Canada)

Latest month is **July 2026** for every row. YoY compares with July 2025, the 5-year change with July 2021, and the earliest with July 2017 (the table starts January 2017; same month used to avoid seasonality). No row for Canada carries a status or quality flag. Per-serving figures appear in section 2b.

| Candidate item | StatCan product (unit) | Vector | Jul 2026 | Jul 2025 → YoY | Jul 2021 → 5-yr | Jul 2017 → since 2017 | 12-mo range (Aug 25–Jul 26) |
|---|---|---|---|---|---|---|---|
| Rice | White rice, 2 kg | v1458869937 | **$9.62** | $9.58 → **+0.4%** | $8.43 → +14.1% | $7.15 → +34.5% | $9.26–$10.06 |
| Dry red lentils | Dried lentils, 900 g | v1353834344 | **$3.63** | $3.49 → +4.0% | $3.18 → +14.2% | $3.13 → +16.0% | $3.51–$3.63 |
| Dry beans | Dry beans and legumes, 900 g | v1458869913 | **$3.59** | $3.43 → +4.7% | $2.93 → +22.5% | $2.91 → +23.4% | $3.44–$3.59 |
| Peanut butter | Peanut butter, 1 kg | v1353834338 | **$5.62** | $6.16 → **−8.8%** | $4.73 → +18.8% | $4.11 → +36.7% | $5.57–$6.15 |
| Pasta | Dry or fresh pasta, 500 g | v1353834327 | **$3.45** | $3.34 → +3.3% | $2.56 → **+34.8%** | $2.36 → +46.2% | $3.18–$3.46 |
| Canned tuna | Canned tuna, 170 g | v1353834282 | **$1.84** | $1.79 → +2.8% | $1.65 → +11.5% | $1.57 → +17.2% | $1.54–$1.84 |
| Eggs | Eggs, 1 dozen | v1353834290 | **$4.95** | $4.95 → **0.0%** | $3.82 → +29.6% | $3.12 → **+58.7%** | $4.70–$4.95 |
| Canned tomatoes | Canned tomatoes, 796 mL | v1353834341 | **$2.27** | $2.18 → +4.1% | $1.56 → **+45.5%** | $1.37 → **+65.7%** | $2.03–$2.33 |
| Canned lentils/chickpeas | Canned beans and lentils, 540 mL | v1353834343 | **$1.72** | $1.69 → +1.8% | $1.31 → +31.3% | $1.14 → +50.9% | $1.65–$1.74 |
| Frozen peas | Frozen peas, 750 g | v1353834325 | **$3.83** | $3.65 → +4.9% | $3.05 → +25.6% | $2.97 → +29.0% | $3.47–$3.85 |
| Frozen mixed veg | Frozen mixed vegetables, 750 g | v1353834324 | **$4.30** | $4.05 → +6.2% | $3.41 → +26.1% | $3.27 → +31.5% | $3.88–$4.30 |
| Bananas | Bananas, per kg | v1353834294 | **$1.88/kg** | $1.67 → **+12.6%** | $1.61 → +16.8% | $1.58 → +19.0% | $1.66–$1.88 |
| Carrots | Carrots, 1.36 kg | v1353834303 | **$4.75** | $4.34 → +9.4% | $3.56 → +33.4% | $3.28 → +44.8% | $3.02–$4.87 |
| Potatoes (bag) | Potatoes, 4.54 kg | v1353834300 | **$5.32** | $5.52 → **−3.6%** | $4.96 → **+7.3%** | $5.07 → **+4.9%** | $4.22–$5.54 |
| Potatoes (loose) | Potatoes, per kg | v1353834316 | $5.23/kg | $5.08 → +3.0% | $4.28 → +22.2% | $3.41 → +53.4% | — |
| Whole chicken | Whole chicken, per kg | v1353834277 | **$7.62/kg** | $6.67 → **+14.2%** | $6.43 → +18.5% | $5.94 → +28.3% | **$6.18–$8.57** (volatile) |
| Milk | Milk, 4 L | v1353834285 | **$6.99** | $6.72 → +4.0% | $5.50 → +27.1% | $5.11 → +36.8% | $6.77–$7.03 |
| Sugar | White sugar, 2 kg | v1353834330 | **$2.64** | $3.23 → **−18.3%** | $2.24 → +17.9% | $2.45 → +7.8% | **$2.49–$3.36** (volatile) |
| Margarine | Margarine, 907 g | v1458869921 | **$6.09** | $6.91 → **−11.9%** | $4.79 → +27.1% | $4.10 → +48.5% | $6.09–$7.52 |
| Oats (rolled/quick) | **Not tracked** by 18-10-0245-01 | — | — | — | — | — | — |

Other cheap staples StatCan tracks, for reference (July 2026, Canada): Wheat flour 2.5 kg $5.36 (+0.9% YoY, +8.5% 5-yr); White bread 675 g $3.60 (+4.3%, +20.8%); Cabbage per kg $2.90 (+2.5%, +21.8%); Onions 1.36 kg $5.02 (−0.6%, +25.5%); Canned baked beans 398 mL $1.87 (0.0%, +55.8%); Canned corn 341 mL $1.61 (+1.9%, +17.5%); Brown rice 900 g $5.91 (+1.5%, +17.7%); Frozen corn 750 g $3.87 (+5.2%, +18.0%).

Peaks worth knowing (Statistics Canada national average): sugar peaked at $3.36 in January 2026, so July is 21% below that peak. Margarine peaked at $7.61 in July 2023, so July 2026 is 20% below. Peanut butter peaked at $6.43 in June 2023, so July 2026 is 12.6% below. Eggs at $4.95 are level with their series high (July 2025, $4.95). Canned tomatoes peaked at $2.33 in June 2026. Bananas at $1.88/kg are at their series high, tied with May 2026.

### 2a. Same-month CPI check: does the average-price move match pure price change?
CPI sub-indexes come from table 18-10-0004-01, Canada, not seasonally adjusted, released 2026-09-14. The comparison uses July 2026 YoY so it lines up with the average-price month, with August 2026 YoY alongside. **This matters for the script.** Where the two disagree, the average-price "drop" is probably product mix, promotions or a one-month swing, and StatCan's own footnote says not to read it as a price cut (see section 4).

| Item | Avg price YoY (Jul 26) | CPI sub-index | CPI YoY Jul 26 | CPI YoY Aug 26 | Verdict for script |
|---|---|---|---|---|---|
| Rice | +0.4% | Rice and rice-based mixes (v41691006) | −0.2% | +0.6% | **Agree: flat.** Safe to say "barely moved". |
| Eggs | 0.0% | Eggs (v41690999) | −1.3% | −2.4% | **Agree: flat to down.** Safe to say "no higher than a year ago". |
| Pasta | +3.3% | Dry or fresh pasta (v122665869) | **−4.9%** | **−7.5%** | Disagree. The CPI says pure prices fell while the average rose (mix includes fresh pasta). Do not say pasta "rose" or "fell" without naming the measure. |
| Peanut butter | **−8.8%** | Nut butter (v122665882) | **+1.9%** | **+3.6%** | **Disagree.** The average dropped from $6.12 in June to $5.62 in July in a single month. **Do not say peanut butter got cheaper.** |
| Margarine | **−11.9%** | Margarine (v41691034) | **+5.9%** | **+3.9%** | **Disagree sharply.** **Do not say margarine got cheaper.** |
| Sugar | **−18.3%** | Sugar and syrup (v41691031) | −0.3% | −0.5% | Same direction, very different size. Say "the national average fell" and attribute it, never "sugar is 18% cheaper". |
| Canned tuna | +2.8% | Canned tuna (v122665858) | +2.6% | +3.1% | Agree. |
| Whole chicken | +14.2% | Fresh or frozen whole chicken (v1592274398) | +3.5% | +0.8% | The average-price jump is far larger than the CPI. The series is volatile ($6.18–$8.57 in 12 months). |
| Potatoes 4.54 kg | −3.6% | Potatoes (v41691022) | +1.6% | +0.4% | Both small. Say "barely moved". |
| Milk 4 L | +4.0% | Fresh milk (v41690994) | +3.1% | +2.6% | Agree, roughly. |
| Frozen peas / mixed veg | +4.9% / +6.2% | Frozen and dried vegetables (v41691027) | +1.3% | +4.5% | Roughly agree on direction. |
| Canned tomatoes / canned legumes | +4.1% / +1.8% | Canned vegetables and other vegetable preparations (v41691028) | +1.3% | +1.8% | Agree on direction. |
| Bananas | +12.6% | Fresh fruit (v41691011) is the parent index. Bananas have no separate index in the pull. | +6.1% | +4.7% | Direction agrees. Don't claim a banana CPI figure. |

### 2b. Per-serving arithmetic at the Statistics Canada national average (illustrative only)
Method: national average price ÷ package size × serving size. The serving size is the one the **No Frills website lists** for the named product (PC Express API, captured 2026-10-06/07 in `c3live/p/`). The script must say "the No Frills website lists a __ serving" or quote a photographed label. These are **not** No Frills prices; they apply a label serving to a national average.

| Item | Serving used (source product) | Jul 2026 | Jul 2025 | Jul 2021 | Jul 2017 | $/100 g or mL, Jul 2026 |
|---|---|---|---|---|---|---|
| Sugar 2 kg | 4 g (Lantic Granulated 2 kg, 20145033_EA) | **$0.005** | $0.006 | $0.004 | $0.005 | $0.13 |
| Margarine 907 g | 10 g (Becel Original 800 g, 21747692_EA) | $0.07 | $0.08 | $0.05 | $0.05 | $0.67 |
| Peanut butter 1 kg | 15 g (No Name Smooth 1 kg, 20296985001_EA) | $0.08 | $0.09 | $0.07 | $0.06 | $0.56 |
| Potatoes 4.54 kg | 100 g (retailer-listed, Yellow Potato 10 lb, 20601017001_EA) | $0.12 | $0.12 | $0.11 | $0.11 | $0.12 |
| Dried lentils 900 g | 35 g (PC Blue Menu Red Split Lentils, 20629496_EA) | $0.14 | $0.14 | $0.12 | $0.12 | $0.40 |
| White rice 2 kg | 45 g dry (No Name Long Grain 2 kg, 20069589_EA) | $0.22 | $0.22 | $0.19 | $0.16 | $0.48 |
| Bananas per kg | 140 g (retailer-listed, Bananas Bunch, 20175355001_KG) | $0.26 | $0.23 | $0.23 | $0.22 | $0.19 |
| Canned beans & lentils 540 mL | 95 mL (No Name Lentils, 20325921004_EA); chickpeas list 86 mL, which gives $0.27 | $0.30 | $0.30 | $0.23 | $0.20 | $0.32 |
| Carrots 1.36 kg | 100 g (retailer-listed, Carrots 3 lb, 20600927001_EA) | $0.35 | $0.32 | $0.26 | $0.24 | $0.35 |
| Canned tomatoes 796 mL | 129 mL (No Name Diced, 20600787_EA) | $0.37 | $0.35 | $0.25 | $0.22 | $0.29 |
| Frozen peas 750 g | 85 g (No Name Green Peas, 20312260_EA) | $0.43 | $0.41 | $0.35 | $0.34 | $0.51 |
| Milk 4 L | 250 mL (Neilson 2% 4 L, 20188873_EA) | $0.44 | $0.42 | $0.34 | $0.32 | $0.17 |
| Pasta 500 g | 85 g (No Name Spaghetti 900 g, 20315613002_EA); StatCan's category includes fresh pasta | $0.59 | $0.57 | $0.44 | $0.40 | $0.69 |
| Canned tuna 170 g | 55 g (No Name Flaked Light, 20521648_EA) | $0.60 | $0.58 | $0.53 | $0.51 | $1.08 |
| Eggs, dozen | **per egg** (no serving assumption) | **$0.41/egg** | $0.41 | $0.32 | $0.26 | — |
| Eggs, dozen | label 105 g serving; if that is 2 eggs, then $0.83 (count UNVERIFIED) | ($0.83) | ($0.83) | ($0.64) | ($0.52) | — |
| Whole chicken per kg | 113 g (retailer-listed, Whole Tray Pack, 20654705_KG) | **$0.86** | $0.75 | $0.73 | $0.67 | $0.76 |

Every candidate StatCan tracks is under $1 per listed serving at the July 2026 national average. Whole chicken is closest to the line at $0.86, and it fails at No Frills Toronto ($11.00/kg gives $1.24, per the Oct 7 comp file). Its national average swings between $6.18 and $8.57/kg; at $8.85/kg or more a 113 g serving would pass $1.00. It is a poor "still under $1" pick.

---

## 3. The "STILL" tension: what fell or held, and what rose a lot but is still under $1

All figures below are the Statistics Canada national average.

**A. Held flat or fell, with the CPI agreeing (the safest "still" lines):**
1. **Rice (white, 2 kg)**: $9.62 in July 2026 against $9.58 in July 2025 (+0.4%). The CPI rice index was −0.2% in July and +0.6% in August. Works out to about $0.22 per listed 45 g dry serving.
2. **Eggs (dozen)**: $4.95, exactly the same as July 2025. The CPI egg index was −1.3% (July) and −2.4% (August). Still about 41 cents an egg, though eggs are up 58.7% since July 2017 ($3.12). That gives the hook "flat this year, but up nearly 60% since 2017".
3. **Potatoes (4.54 kg bag)**: $5.32, −3.6% YoY. The CPI potatoes index was +1.6% (July). The bag is up only **4.9% since July 2017** ($5.07), the smallest 9-year move of any candidate. About 12 cents per 100 g. The bag works out to $1.17/kg against $5.23/kg for loose potatoes per kg. That is a unit-price fact only; the two categories are different products.
4. **Dried lentils and dry beans (900 g)**: +4.0% and +4.7% YoY, but only +14.2% and +22.5% over five years. Red split lentils come to about $0.14 per listed 35 g serving.

**B. Average fell, but the CPI says otherwise (use with the footnote, or don't use):**
- Sugar: −18.3% average (CPI −0.3%). Margarine: −11.9% average (CPI +5.9%). Peanut butter: −8.8% average (CPI +1.9%). The safe wording is "Statistics Canada's national average price was lower in July 2026 than a year earlier". It must not become "these got cheaper", and the footnote in section 4 applies.

**C. Rose a lot, and are still under $1 per listed serving at the national average:**
- **Canned tomatoes**: +45.5% in 5 years, +65.7% since July 2017 ($1.37 to $2.27). Still about $0.37 per 129 mL serving.
- **Eggs**: +29.6% in 5 years, +58.7% since 2017. Still about $0.41 an egg.
- **Canned beans and lentils**: +31.3% in 5 years, +50.9% since 2017. Still about $0.30 per serving.
- **Pasta**: +34.8% in 5 years, +46.2% since 2017. Still about $0.59 per 85 g.
- **Carrots (1.36 kg)**: +33.4% in 5 years, +9.4% YoY. Still about $0.35 per 100 g.
- **Milk 4 L**: +27.1% in 5 years, +36.8% since 2017. Still about $0.44 per 250 mL.
- **Bananas**: +12.6% YoY, a series high of $1.88/kg. Still about $0.26 per 140 g.
- **Whole chicken**: +14.2% YoY ($6.67 to $7.62/kg). Still $0.86 per 113 g at the national average, but over $1 at No Frills Toronto. Use only as a "nearly priced out" foil, if at all.

**Benchmark for "still":** the CPI for food purchased from stores (18-10-0004-01, v41690975) rose **29.9%** from July 2021 (154.4) to July 2026 (200.5) and **40.0%** from July 2017 (143.2). Canned tomatoes (+45.5% / +65.7%), eggs (+58.7% since 2017), canned legumes and pasta all rose faster than the grocery CPI over those windows. Rice (+14.1% / +34.5%), dried lentils (+14.2% / +16.0%), potatoes 4.54 kg (+7.3% / +4.9%), canned tuna (+11.5% / +17.2%), sugar (+17.9% / +7.8%) and bananas (+16.8% / +19.0%) rose more slowly. This is a comparison of an average-price change with a CPI change, and StatCan warns the two are not directly comparable. If used, it must be phrased as "for comparison", not as "beat inflation".

**Comparability caveat (mandatory if any 5-year or 2017 figure is used):** StatCan table note 5: "With the release of data for the January 2024 reference month, this table has been updated to incorporate data from additional grocery retailers, increasing the sample of price data used in the calculation of monthly average prices. ... Users should continue to exercise caution when comparing average prices over time..." Every 5-year and 2017 comparison crosses that change in coverage.

---

## 4. StatCan footnotes, verbatim

**Table 18-10-0245-01, note 1** (from the table metadata file, `18100245_MetaData.csv`, downloaded 2026-10-07 01:55 UTC):
> "Average price estimates for these products are derived using transaction data from Canadian grocery retailers. The composition of a given product category may change over time due to evolving consumer purchasing patterns and product availability. Therefore, users should exercise caution when comparing average prices over time as average prices may not be fully comparable from one month to another and should not be used as a representative measure of pure price change through time. Note: Data are subject to revision."

**The Daily, 2026-09-02, "Note to readers"** (https://www150.statcan.gc.ca/n1/daily-quotidien/260902/dq260902a-eng.htm):
> "Users should exercise caution when comparing average prices over time. Factors such as product rotation, quality and quantity changes, and shifting consumer preferences can contribute to price differences from one month to another. To measure pure price change, otherwise known as inflation, it is recommended to use the CPI and its sub-indexes (table 18-10-0004-01), which control for these factors by reflecting price change only for the same or comparable item in the same outlet."

Script-safe paraphrase: "Statistics Canada itself says its average prices should not be used as a measure of pure price change, so treat these as a guide, not a receipt."

---

## 5. Latest CPI, food purchased from stores (table 18-10-0004-01)

- **August 2026: +2.8% year over year.** Index 199.6 against 194.2 in August 2025 (v41690975). Released **2026-09-14**, 08:30 ET.
- July 2026: +3.1% (200.5 against 194.4). All-items CPI for August 2026: +3.0% (169.8 against 164.8).
- The Daily, 2026-09-14 (https://www150.statcan.gc.ca/n1/daily-quotidien/260914/dq260914a-eng.htm), verbatim: "Price growth for food purchased from stores continued to slow in August, rising 2.8% year over year after increasing 3.1% in July. For the first time since July 2024, grocery price growth increased at a slower pace than the all-items CPI in August 2026." and "Prices for dairy products led the deceleration in grocery prices; they rose 0.7% year over year in August compared with a 3.1% rise in July."
- Next CPI (September 2026) is expected around mid-to-late October 2026. It lands after the Oct 8 upload, so +2.8% (August) is the figure to quote.

---

## SOURCE REGISTER

| # | Source | URL | Accessed (UTC) | Tier |
|---|---|---|---|---|
| S1 | StatCan table 18-10-0245-01, full CSV zip (cube end 2026-07-01, CSV dated 2026-09-02) | https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip, saved to scratchpad/statcan/dl2/ | 2026-10-07 01:55 | a primary |
| S2 | StatCan WDS getCubeMetadata pid 18100245 (cubeEndDate 2026-07-01, releaseTime 2026-09-02T08:30) | https://www150.statcan.gc.ca/t1/wds/rest/getCubeMetadata | 2026-10-07 01:55 | a primary |
| S3 | StatCan WDS getChangedCubeList for 2026-09-02, 09-14, 09-15, 09-16, 10-01, 10-02, 10-05, 10-06, 10-07 | https://www150.statcan.gc.ca/t1/wds/rest/getChangedCubeList/{date} | 2026-10-07 01:56 | a primary |
| S4 | StatCan WDS vector release history (v1353834330, v1353834338, v1458869921) | https://www150.statcan.gc.ca/t1/wds/rest/getDataFromVectorsAndLatestNPeriods | 2026-10-07 01:58 | a primary |
| S5 | The Daily, Monthly average retail prices, July 2026 (released 2026-09-02) | https://www150.statcan.gc.ca/n1/daily-quotidien/260902/dq260902a-eng.htm | 2026-10-07 01:58 | a primary |
| S6 | StatCan table 18-10-0004-01 CPI, WDS coordinate pulls (food from stores, all-items, food, 18 sub-indexes; July and August 2017/2021/2025/2026) | https://www150.statcan.gc.ca/t1/wds/rest/getDataFromCubePidCoordAndLatestNPeriods ; getDataFromVectorByReferencePeriodRange | 2026-10-07 01:56–01:59 | a primary |
| S7 | The Daily, Consumer Price Index, August 2026 (released 2026-09-14) | https://www150.statcan.gc.ca/n1/daily-quotidien/260914/dq260914a-eng.htm | 2026-10-07 01:57 | a primary |
| S8 | Table 18-10-0245-01 metadata (notes 1–6) | inside S1 zip (18100245_MetaData.csv); table page https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810024501 | 2026-10-07 01:55 | a primary |
| S9 | PC Express API product records, No Frills #7952, 261 Richmond St W, Toronto (serving sizes only): 20188873_EA, 20145033_EA, 21747692_EA fetched 2026-10-07 01:57 UTC; the others from c3live/p/ (Oct 6–7 captures) | api.pcexpress.ca/pcx-bff/api/v1/products/{code} | 2026-10-07 01:57 | a primary (retailer's own listing; label transcription by retailer) |
| S10 | StatCan release calendar | https://www150.statcan.gc.ca/n1/dai-quo/cal2-eng.htm | 2026-10-07 01:58 | c do-not-use (rendered through JavaScript; no usable listing returned) |
| S11 | "latestN=5" CSV download link from the brief | https://www150.statcan.gc.ca/t1/tbl1/en/dtl!downloadDbLoadingData-nonTraduit.action?pid=1810024501&latestN=5... | 2026-10-07 01:55 | c do-not-use (returned an error string, not data) |

Local files: `scratchpad/statcan/dl2/` (full.zip, 18100245.csv, cpi_meta.json, cpi_data.json, cpi_sub14.json, vec.json, d0902.htm, daily.htm), `scratchpad/u1tools/canada.json` (computed national series), `scratchpad/u1tools/sc.py`.

---

## UNVERIFIED / DO-NOT-USE

1. **August 2026 average retail prices**: NOT RELEASED as of 2026-10-07 01:59 UTC. Do not cite any August 2026 average price. Re-check at 12:35 UTC Oct 7 and on Oct 8. The expected release date is inferred from cadence only; no published date was found.
2. **"Sugar / margarine / peanut butter got cheaper"**: DO NOT USE. The average-price falls (−18.3%, −11.9%, −8.8%) are contradicted or heavily shrunk by the CPI (−0.3%, +5.9%, +1.9% for July). Peanut butter's fall is mostly a single-month drop from June to July ($6.12 to $5.62).
3. **"Eggs: 2 eggs per serving"**: UNVERIFIED. The No Frills record lists 105 g with no household measure. Use "about 41 cents an egg" (national average ÷ 12) instead.
4. **Whole chicken as an "under $1" item**: DO NOT USE as a list item. It passes at the national average ($0.86 per 113 g) but fails at No Frills Toronto ($1.24), and the national series is volatile. Never set the No Frills price against the national average as evidence of overcharging.
5. **Rolled/quick oats and frozen mixed-vegetable servings**: StatCan has no oats series, so oats cannot be cross-checked. Frozen mixed vegetables are tracked, but no label serving was captured here.
6. **Any 5-year or 2017 comparison presented as pure price change or "inflation"**: DO NOT USE that framing. Note 1 and note 5 (the January 2024 expansion of retailer coverage) apply. Say "Statistics Canada's national average price went from $X in July 2017 to $Y in July 2026".
7. **"Beat inflation" / "outpaced inflation" comparisons** between average-price changes and the CPI: avoid. StatCan states the two "are not comparable with the pure price changes calculated in the CPI". Use "for comparison" phrasing only, if at all.
8. **Pasta direction**: the average rose 3.3% while the CPI for dry or fresh pasta fell 4.9% (July) and 7.5% (August). Don't state a direction without naming the measure. The average also includes fresh pasta, so the per-serving figure ($0.59/85 g) runs high for dry spaghetti.
9. **Banana CPI figure**: not pulled. Only the parent "Fresh fruit" index (+6.1% July) was. Don't attribute a CPI change to bananas.
10. **The calendar summary and any WebFetch AI summary lines** not quoted verbatim from the raw HTML (for example the "Notable items" paraphrase of the CPI Daily): do not use. Only the verbatim quotes in section 5 were checked against raw HTML.
11. **Nutrition wording**: the serving sizes above are label or retailer-listed quantities only. No nutrient values from the captured records may be used. Banned: protein, fibre, filling, nutritious, healthy, Canada's Food Guide.

---

## GAP FIXES (critic), 7 Oct 2026, 02:19–02:26 UTC (full report: `scratchpad/u1_gaps.md`)

- **August 2026 still NOT released** at 02:22 UTC on 7 Oct.
  - WDS getCubeMetadata returns cubeEndDate 2026-07-01 and releaseTime 2026-09-02T08:30.
  - The zip's Last-Modified is Wed, 02 Sep 2026 12:31:36 GMT.
  - The latestN link still returns "Failed to open stream for the full cube download".
  - getChangedCubeList/2026-10-07 returns "The input date is a future release date."
  - Re-check on 8 Oct before lock.
- **Re-verified against the CSV (Canada, 2026-07):** rice 9.62, eggs 4.95, milk 6.99, pasta 3.45, canned tomatoes 2.27, tuna 1.84, canned beans and lentils 1.72, dried lentils 3.63, frozen peas 3.83, carrots 4.75, potatoes 4.54 kg 5.32, bananas 1.88/kg. All match.
- **Added for #10 bread:** White bread 675 g, **$3.60** (v1353834326). At the 75 g label serving that is 9 servings, about **$0.40 per serving** at the national average (all brands and stores).
- **Bananas cheapest per-kg product:** re-verified, 1st of 25 per-kg products. Next are cabbage $2.90, oranges $4.48 and sweet potatoes $4.83.
- **Not tracked:** popping corn and oats have no series in 18-10-0245-01 (only canned corn 341 ml and frozen corn 750 g exist). #3 popping corn and #2 oats carry facts or price comparisons instead. No "since 2017" or "still" history claim is possible for either.


======================================================================

# u1: FACTS DOSSIER. Canadian facts per item (non-health, primary or named-outlet sourced)

Project: "15 Foods That Still Cost Under $1 a Serving in Canada (October 2026 Prices)". Thumbnail "STILL UNDER $1". Upload 2026-10-08 20:00 UTC.
Compiled 2026-10-07, 02:02 to 02:16 UTC. Every web source below was opened in this session unless it is marked **CARRIED** (taken from an earlier repo dossier and not re-opened today).

House-rule filter applied to every line: no health, nutrition or food-safety claims; no storage-safety claims; no taste or quality stated as fact; no implied wrongdoing; no supplier inferred for No Name or any store brand; no U.S. figures; none of the banned words. Where a primary source itself uses banned or health wording, that part is left out and flagged in section 6.

How to read the tiers: **(a)** primary (regulator, statute, StatCan, government, the company or body speaking about itself); **(b)** named outlet; **(c)** do-not-use; **(d)** survey.

---

## 0. Five things the script writer must know before using anything below

1. **The No Frills "Prepared in Canada" badge is a website badge, not label wording.** The PC Express API returns it in `offers[].badges.preparedInCanadaBadge` with text "Prepared in Canada". It is the retailer's badge on the listing. It is NOT a photo of the package. House rules allow "Product of Canada" / "Prepared in Canada" only as exact label wording. **On air, say "the No Frills website shows a 'Prepared in Canada' badge on this listing"**, never "the label says". To say "the label says", film the package.
2. **Across 4,484 badge instances in every capture on disk (c3live, live, pcx and u1 searches), the only Canada badge that ever appears is "Prepared in Canada". Zero "Product of Canada" badges. Zero "Made in Canada" badges.** The API has fields for both (`productOfCanadaBadge`, `madeInCanadaBadge`), and all were null.
3. **The badges are identical in Toronto, Calgary and Vancouver.** 26 product codes were captured at all three No Frills stores (#7952, 261 Richmond St W, Toronto; #3155, 10233 Elbow Dr SW, Calgary; #3403, 310 W Broadway, Vancouver), on 2026-10-07 between 01:55 and 02:00 UTC. Badge sets differed for 0 of 26.
4. **Fresh produce and raw whole chicken do not have a legal "label serving".** Under the Food and Drug Regulations B.01.401(2), a fresh fruit or vegetable with no added ingredients, and raw single-ingredient poultry, are exempt from the Nutrition Facts table. So the serving sizes the No Frills site shows for bananas (140 g), carrots (85 g or 100 g), potatoes (100 g), onions (100 g) and whole chicken (113 g) come from the retailer's listing, not from a mandatory label. If the video ranks by "label serving", those items need a different sentence (see 1.3).
5. **Rice, spaghetti, canned chickpeas, canned lentils, diced tomatoes, tuna, eggs, frozen peas and mixed vegetables carry no Canada badge at all** on the No Frills listings. Say nothing about where they come from.

---

## 1. Cross-cutting facts (usable in the yardstick or between items)

### 1.1 What "Product of Canada" and "Prepared in Canada" mean: CFIA, verbatim (a)
Source: CFIA, "Origin claims on food labels", https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims (page "Date modified: 2023-12-06"), opened 2026-10-07 02:02 UTC.

- "A food product may use the claim "Product of Canada" when all or virtually all major ingredients, processing, and labour used to make the food product are Canadian. This means that all the significant ingredients in a food product are Canadian in origin and that non-Canadian material is negligible."
- Minor ingredients: "Generally, the percentage referred to as very little or minor is considered to be less than a total of 2% of the product". (The page does not use the number "98%". Say "less than 2 per cent", not "98 per cent".)
- "Made in Canada": "A "Made in Canada" claim with a qualifying statement can be used on a food product when the last substantial transformation of the product occurred in Canada, even if some ingredients are from other countries." The qualifier must read "Made in Canada from domestic and imported ingredients" or "Made in Canada from imported ingredients". "Made in Canada from domestic and imported ingredients" "may be used on a product that contains a mixture of imported and domestic ingredients, regardless of the level of Canadian content in the product."
- **"Prepared in Canada" is listed only as an example of an "other domestic content claim"**: ""Prepared in Canada" to describe a food which has been entirely prepared in Canada". The CFIA says such claims "may be used without further qualification, provided they are truthful and not misleading for consumers." **The page gives no ingredient-content test for "Prepared in Canada".** That is the decode: "Product of Canada" has a content rule; "Prepared in Canada" describes where it was prepared.
- Sister examples on the same list (useful for sugar): ""Refined in Canada" to describe imported cane sugar which has been refined in Canada" and ""Packaged in Canada" to describe a food which is imported in bulk and packaged in Canada".
- "The claim "Canadian" is considered to be the same as a "Product of Canada" claim".
- "100% Canadian": "the food or ingredient to which the claim applies must be entirely Canadian rather than "all or virtually all" Canadian."
- Grade names sit outside these guidelines: the guidelines do not apply to "terms or references that have regulated requirements and are not subject to the guidelines (for example, grade names, references to Canada Organic or mandatory country of origin labelling)".
- Meat and poultry: "Meat from imported hatching eggs, including those hatched in transit, would meet the "Product of Canada" guidelines provided that the chick was raised, slaughtered and processed in Canada."
- Eggs and milk: "Eggs from imported hens and milk from imported cows would qualify for the "Product of Canada" claim provided that the hen laid its eggs in Canada, and the cow is milked in Canada."
- "The use of "Product of Canada" and "Made in Canada" claims is voluntary."

### 1.2 How label serving sizes are set: the regulation, verbatim (a)
This is a labelling rule. Quote it as a rule about labels, with no comment on nutrition.

Source: Food and Drug Regulations, C.R.C., c. 870, Justice Laws full text ("current to 2026-09-21 and last amended on 2026-06-17"), https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._870/FullText.html, downloaded 2026-10-07 02:03 UTC.

- B.01.001, definition: "reference amount means, in respect of a food set out in column 1 of the Table of Reference Amounts, the amount of that food set out in column 2".
- B.01.001, definition: "Table of Reference Amounts means the document entitled Nutrition Labelling – Table of Reference Amounts for Food published by the Government of Canada on its website, as amended from time to time".
- **B.01.002A(1)**: "For the purposes of this Part, a serving of stated size of a food shall be (a) based on the food as offered for sale; (b) in either of the following cases, the net quantity of the food in the package: (i) if the quantity of food in the package can reasonably be consumed by one person at a single eating occasion, or (ii) if the package contains less than 200% of the reference amount for the food; and (c) in all other cases, the amount indicated for the food according to the criteria set out in column 3A of the Table of Reference Amounts." (History note on the section: "SOR/88-559, s. 2 SOR/2003-11, s. 3 SOR/2016-305, s. 3".)
- Plain-English version for the script: **the brand does not pick the serving size freely. Health Canada's Table of Reference Amounts sets a reference amount for each kind of food, and the serving on a multi-serving package has to follow that table's rules.**

Health Canada, "Nutrition labelling – Table of reference amounts for food", https://www.canada.ca/en/health-canada/services/technical-documents-labelling-requirements/table-reference-amounts-food/nutrition-labelling.html, "Published on: October 18, 2024". canada.ca refused curl (HTTP/2 stream reset) so the page was read by **WebFetch (automated summary), two reads at about 02:04 UTC**. Re-verify these rows on screen before air:
- The page says: "Reference amounts represent the amount of food typically consumed in one eating occasion".
- Reference amounts read (column 2): rice and grains "45 g dry, 140 g cooked"; dry pasta "85 g dry, 215 g cooked"; hot cereals and oats "40 g dry"; "Beans, peas and lentils" "35 g dry, 125 mL cooked, frozen or canned"; peanut butter "15 g"; eggs "100 g"; milk "250 mL"; "Butter, margarine, shortening, lard…" "10 g"; vegetables fresh, frozen or canned "85 g" or "125 mL"; fresh fruit "140 g"; potatoes "110 g fresh or frozen"; canned fish "55 g"; flour "30 g"; bread "75 g"; "Granulated, brown, icing or cinnamon sugar…" "10 g".
- **Independent corroboration from the No Frills listings (product-detail API, store #7952, 2026-10-07):** the Nutrition Facts serving fields match the table for No Name rice 45 g, No Name spaghetti and macaroni 85 g, No Name oats 40 g, PC Blue Menu dry lentils, beans and split peas 35 g, No Name and Kraft peanut butter 15 g, No Name eggs 105 g (the table's "number [of eggs] closest in weight" to 100 g), Neilson milk 250 ml, margarines 10 g, No Name frozen peas, mixed vegetables and corn 85 g, No Name tuna 55 g, No Name flour 30 g, No Name bread 75 g.
- **Sugar mismatch, do not explain on air:** the automated read gave sugar a 10 g reference amount, but the Lantic 2 kg listing shows a 4.0 g serving. Unresolved (column 3A may allow a household measure such as 1 tsp). See UNVERIFIED U3.

### 1.3 The produce and raw-chicken exemption, verbatim (a)
Same FDR source. B.01.401(2): the Nutrition Facts table requirement "does not apply to a prepackaged product if … (b) the product is … (iii) a raw single ingredient meat, meat by-product, poultry meat or poultry meat by-product … or (c) the product is (i) a fresh vegetable or fruit or any combination of fresh vegetables or fruits without any added ingredients…".
- Script use: "Bananas, carrots, potatoes and raw chicken don't have to carry a Nutrition Facts table at all, so for those we used Health Canada's reference amount for that kind of food." (Bananas 140 g fresh fruit; potatoes 110 g; vegetables 85 g; raw poultry: see U3, row not re-read today.)

### 1.4 Canada's Food Price Report 2026, exact numbers (a, the report's own publisher)
Source: Dalhousie University news release, 4 Dec 2025, https://www.dal.ca/news/2025/12/04/canada-food-price-report-2026.html (opened 02:05 UTC) and the full report PDF https://cdn.dal.ca/content/dam/dalhousie/pdf/sites/agri-food/FINAL%20E%20low.res%20DAL_PRICE_REPORT_2026.pdf (downloaded 02:05 UTC, 39 pages).
- Partners, verbatim: "an annual collaboration between research partners Dalhousie University, Saint Mary's University, University of Prince Edward Island, Cape Breton University, University of Guelph, Université Laval, University of British Columbia, and University of Saskatchewan." The report calls itself "the 16th edition".
- Headline: "Canada's Food Price Report 2026 forecasts that overall food prices will increase by 4% to 6%. The average family of four is expected to spend $17,571.79 on food in 2026, an increase of up to $994.63 from last year. Food prices are 27% higher than they were five years ago."
- Method of the family number (report p. 5): it uses "the highest end of the predicted scale (for this year, 6%)". So $17,571.79 is a **ceiling ("up to")**, not an average forecast. Family = man 31-50, woman 31-50, boy 14-18, girl 9-13. The 2025 observed figure was $16,577.16.
- Table 1, 2026 forecasts: Bakery 2%-4%; Dairy & Eggs 2%-4%; Fruit 1%-3%; Meat 5%-7%; Other 4%-6%; Restaurants 4%-6%; Seafood 1%-2%; Vegetables 3%-5%; Total 4%-6%.
- How the 2025 forecast did (Table 3, the report's own scorecard): Vegetables forecast 3%-5%, actual -0.9%; Fruit forecast 1%-3%, actual -1.1%; Meat forecast 4%-6%, actual 7.2%; Total forecast 3%-5%, actual 3.4%.
- Provinces: "Residents in Alberta, New Brunswick, Nova Scotia, Ontario, and Quebec are expected to see food price increases above the national average next year."
- Lead author quote (release): "Our forecast for 2026 makes one thing clear: food affordability will remain a major pressure point in the year ahead." (Dr. Sylvain Charlebois, Project Lead, Dalhousie University.)
- Chicken (report p. 31): "chicken prices are set to increase substantially in 2026 due to underproduction." Attribute as the report's forecast.

### 1.5 What actually happened since: StatCan CPI, August 2026 (a)
Source: StatCan, The Daily, "Consumer Price Index, August 2026", released 2026-09-14, https://www150.statcan.gc.ca/n1/daily-quotidien/260914/dq260914a-eng.htm (opened 02:13 UTC).
- "Price growth for food purchased from stores continued to slow in August, rising 2.8% year over year after increasing 3.1% in July. For the first time since July 2024, grocery price growth increased at a slower pace than the all-items CPI in August 2026." All-items CPI: +3.0%.
- "Although prices for groceries decelerated this month, prices have increased 29.0% since August 2021."
- Next CPI (September 2026): "Monday, October 19". Not out before upload.
- Careful: the CFPR 4%-6% includes restaurants. The 2.8% is food from stores only. Do not set them side by side as like for like.

### 1.6 StatCan average-price table status (a)
- Table 18-10-0245-01 still ends at **July 2026**: WDS getCubeMetadata at 2026-10-07 02:11 UTC returned cubeEndDate 2026-07-01, releaseTime 2026-09-02T08:30. August 2026 is not out. (Detail and per-item figures are in the separate u1_statcan.md dossier.)
- New derived fact from that table (July 2026, Canada): **bananas at $1.88 per kilogram are the cheapest per-kilogram item of all 25 per-kilogram products StatCan tracks**, below cabbage ($2.90), oranges ($4.48) and potatoes ($5.23 per kg loose). StatCan said the same about fruit in April 2024: "In each month over the same period, bananas have had the lowest per-kilogram average price among fruits we track." (https://www.statcan.gc.ca/o1/en/plus/6085-bananas-peeling-away-inflation, published April 17, 2024, opened 02:11 UTC.)

---

## 2. No Frills badge audit (store #7952 Toronto, product-detail API, 2026-10-07 ~01:55-01:58 UTC; same result at #3155 Calgary and #3403 Vancouver)

Website badge text is exactly "Prepared in Canada" wherever shown. "none" = no Canada badge of any kind.

| Candidate item (code) | Brand / name / size | Website Canada badge | Other origin-type text in the listing |
|---|---|---|---|
| Rice (20069589_EA) | No Name Long Grain White Rice 2 kg | none | none |
| Rice club (20156226_EA) | No Name Long Grain White Rice 8 kg | none | none |
| Red split lentils (20629496_EA) | PC Blue Menu 900 g | Prepared in Canada | none |
| Green lentils (20629679_EA) | PC Blue Menu 900 g | Prepared in Canada | none |
| Yellow split peas (21307041_EA) | PC Blue Menu 2 kg | Prepared in Canada | none |
| Yellow split peas (20558865_EA) | Suraj 1.8 kg | Prepared in Canada | none |
| Black beans dry (20629153_EA) | PC Blue Menu 900 g | Prepared in Canada | none |
| Canned chickpeas (20325921001_EA) | No Name 540 ml | none | none |
| Canned lentils (20325921004_EA) | No Name 540 ml | none | none |
| Canned kidney beans (20554593_EA) | No Name 540 ml | Prepared in Canada | none |
| Oats (20923828_EA, 20923994_EA) | No Name Quick / Large Flake 1 kg | Prepared in Canada | none |
| Spaghetti, macaroni (20315613002_EA, 20315613003_EA) | No Name 900 g | none | none |
| Flour (20013256_EA) | No Name All-Purpose 2.5 kg | Prepared in Canada | none |
| Bread (21509822_EA) | No Name Original 675 g | Prepared in Canada | none |
| Peanut butter (20296985001_EA) | No Name Smooth 1 kg | Prepared in Canada | none |
| Peanut butter (20039581001_EA) | Kraft Smooth 1 kg | Prepared in Canada | Kraft's own copy: "proudly prepared in Canada" |
| Sugar (20145033_EA) | Lantic Granulated 2 kg | Prepared in Canada | none |
| Eggs (20812144001_EA, 21435777001_EA) | No Name Large 12 / 30 | none | none |
| Milk (20188873_EA) | Neilson 2% 4 L | Prepared in Canada | none |
| Whole chicken (20654705_KG) | Chicken Whole, Tray Pack (no brand) | Prepared in Canada | none |
| Whole chicken (21636475_EA) | President's Choice Air Chilled 1.7 kg | Prepared in Canada | none |
| Potatoes (20600997001_EA, 20601017001_EA) | Farmer's Market White / Yellow 10 lb | none | none |
| Carrots (20600927001_EA) | Farmer's Market 3 lb | none | none |
| Onions (20811994001_EA) | Farmer's Market Yellow 3 lb | none | none |
| Cabbage (20793034001_KG) | Green cabbage, loose | none | none |
| Bananas (20175355001_KG) | Bananas, bunch | none | none |
| Frozen peas (20312260_EA) | No Name 750 g | none | none |
| Frozen mixed veg (20301012_EA) | No Name 750 g | none | listing text reads "Canada A." (a grade name; see 3.14) |
| Frozen corn (20306375_EA) | No Name 750 g | none | "Canada A" (grade) |
| Diced tomatoes (20600787_EA) | No Name 796 ml | none | none |
| Tomato sauce (20120683_EA) | No Name 680 ml | Prepared in Canada | none |
| Tuna (20521648_EA) | No Name Flaked Light Tuna in Water 170 g | none | ingredients: "Skipjack Tuna, Water, Salt." |
| Popping corn (21291313_EA) | No Name 1 kg | none | none |
| Margarine (21747711_EA, 21747692_EA) | Imperial 800 g; Becel 800 g | none | none |
| Tortillas (21064398_EA) | No Name 10 Original 320 g | none | (No Name 10 Wheat Tortillas, 21064397_EA, does carry the badge) |

Exact "Product of Canada" text that does appear in No Frills listing descriptions (not badges), for contrast only: Robin Hood all-purpose flour 20039497001_EA ("Product of Canada"), Carnation 2% evaporated milk 20896812_EA, PC Organics free-range eggs 20813711001_EA ("product of Canada"). Those are brand descriptions on the retailer site; the same filming caveat applies.

**Rule reminder: none of this tells you who makes any No Name or PC product. Do not name, hint at, or guess a manufacturer.**

---

## 3. Per-item facts (1-2 each, usable on air with the attribution shown)

### 3.1 Dry lentils (red split / green)
- **Saskatchewan alone ships 37% of the world's lentil exports.** Government of Saskatchewan, Ministry of Agriculture, "2024 Marketing Materials" (PDF, file dated 10/23/2025), table "SK Exports (as % of World Exports)": Lentils 37%; also "SK Production (as % of Canadian production)" 87% and "SK Exports (as % of Canadian Exports)" 88%. https://publications.saskatchewan.ca/api/v1/products/127522/formats/150566/download (downloaded 02:07 UTC). (a) Note: the heading is "Saskatchewan Leads the World as the Largest Exporter (By Value) of these Agri-Food Products", so these are shares **by value**, 2024 data.
- **StatCan 2025 crop (final):** Canada produced 3,363,216 tonnes of lentils; Saskatchewan 2,894,579 t (86.1%), Alberta 462,879 t (13.8%). No other province is listed with lentil production. Table 32-10-0359-01 (released 2026-09-16), downloaded 02:06 UTC. (a)
- **2026 is a smaller crop:** StatCan's model-based estimate (August 2026, released 2026-09-16) puts 2026 lentils at 2,466,733 t, down 26.7% from 2025 (our arithmetic from the table). Final survey numbers come December 4, 2026 (The Daily: "Final survey-based production estimates for 2026 will be released on December 4, 2026"). (a)
- Pulse Canada, describing its own sector: "As the world's largest exporter of peas, lentils, chickpeas, dry beans and faba beans…" (pulsecanada.com home page, opened 02:09 UTC). Tier (b/industry). Usable for **lentils and peas only**; see U8 on chickpeas.

### 3.2 Split peas / dry peas
- Saskatchewan = 27% of world dry pea exports (by value, 2024). Same SK Government source. (a)
- **In 2025 Alberta grew slightly more dry peas than Saskatchewan:** Alberta 1,823,474 t (46.3%), Saskatchewan 1,800,305 t (45.8%), Canada 3,934,217 t. StatCan 32-10-0359-01. (a) In the 2026 model estimate Saskatchewan is back ahead (1,715,899 t vs Alberta 1,379,085 t; Canada 3,260,187 t, -17.1%).

### 3.3 Dry beans and canned kidney beans
- **Manitoba is Canada's biggest dry-bean province:** 2025, Manitoba 214,239 t (48.9%), Ontario 143,097 t (32.7%), Alberta 68,380 t, Saskatchewan 7,558 t, Quebec 4,660 t; Canada 437,935 t. StatCan 32-10-0359-01 ("Beans, all dry (white and coloured)"). (a)

### 3.4 Canned chickpeas and canned lentils
- Chickpeas: Canada's 2025 crop was 481,589 t, up 67.9% from 286,768 t in 2024; Saskatchewan grew 91.8% of it (442,269 t). StatCan 32-10-0359-01. (a)
- Do NOT link the No Name cans to Canadian crops: those listings carry no badge and no origin text.

### 3.5 Rolled oats
- Saskatchewan = 23% of world oat exports (by value, 2024); SK = 44% of Canadian oat production and 53% of Canadian oat exports. SK Government 2024 Marketing Materials. (a)
- StatCan 2025 oats: Canada 3,919,796 t; Saskatchewan 1,763,257 t (45.0%), Manitoba 953,866 t (24.3%), Alberta 875,942 t (22.3%). 2026 model estimate: 3,030,964 t. The Daily (2026-09-16): "Nationally, oat production is anticipated to fall by 22.7% to 3.0 million tonnes, a result of both lower yields ( -3.5% to 94.7 bushels per acre) and lower harvested area ( -19.9% to 2.1 million acres) in 2026." https://www150.statcan.gc.ca/n1/daily-quotidien/260916/dq260916b-eng.htm (opened 02:07 UTC). (a)
- Prairie Oat Growers Association (industry body, describing its own sector; tier b), https://poga.ca/about-poga/the-oat-industry/ (opened 02:09 UTC): Canada is the "Largest oat product exporter" and "Largest raw oat exporter"; "Canada is the largest exporter of oats in Japan with over 40% of the market share." Attribute to POGA by name. See U9 for the POGA line NOT to use.
- National brand context (not No Name): PepsiCo Canada: "PepsiCo Canada operates two Quaker plants: Trenton (Ontario) and Peterborough (Ontario)." https://contact.pepsico.com/quakerca/about-us (opened 02:15 UTC). (a) Never connect this to No Name oats.

### 3.6 Spaghetti / macaroni (durum)
- Saskatchewan = 36% of world durum exports (by value, 2024); 76% of Canadian durum production. SK Government. (a)
- StatCan 2025 durum: Canada 7,304,979 t; Saskatchewan 5,563,885 t (76.2%), Alberta 1,581,258 t (21.6%). The Daily 2026-09-16 on 2026: "an anticipated decrease in durum wheat production ( -12.2% to 6.4 million tonnes)". (a)
- No Name spaghetti ingredients on the listing: "Durum Wheat Semolina." No badge, no origin text. Say nothing about where the wheat or the pasta comes from.

### 3.7 Flour and bread
- StatCan 2025 all-wheat crop: 40,561,984 t; Saskatchewan 18,759,567 t, Alberta 12,283,980 t, Manitoba 5,933,572 t, Ontario 3,054,986 t. 2026 model estimate: "wheat production is projected to decrease 10.9% year over year to 36.1 million tonnes in 2026" (The Daily, 2026-09-16). (a)

### 3.8 Peanut butter
- **Kraft Peanut Butter (national brand, not No Name):** Kraft Heinz Canada's head of supply chain, Jessica Jones, told Canadian Grocer (Rebecca Harris, 3/27/2026): "We run all of our peanut butter for the entire country off one line—one peanut roaster, one process, one pack line." The plant is the company's Mont Royal facility in Montreal, which the article calls "The 70-year-old plant, home to iconic products such as Kraft Dinner, Kraft Peanut Butter, Heinz Ketchup and Philadelphia Cream Cheese", getting a $250-million upgrade. https://canadiangrocer.com/qa-jessica-jones-kraft-heinz-canadas-250-million-investment (opened 02:10 UTC). (b, quoting the company)
- Kraft's own No Frills listing copy says it "is proudly prepared in Canada". The badge on both Kraft and No Name 1 kg is "Prepared in Canada". **Do not suggest who makes the No Name jar.**
- StatCan (u1_statcan.md): peanut butter 1 kg national average July 2026 $5.62, -8.8% year over year. Cross-reference only.

### 3.9 White sugar
- **Canada has one sugar-beet factory, in Taber, Alberta.** Lantic Inc. on its own site: "Canada's only sugar beet factory in Taber, Alberta" (https://www.lanticrogers.com/en/about-us, WebFetch read at about 02:09 UTC, re-verify on screen). Its history page: "Today's remaining operation is in Taber, Alberta, built in 1950. An over $40 million expansion completed in 1999 increased this plant's capacity by 50%." (https://www.lanticrogers.com/en/about-us/history, curl 02:09 UTC). (a)
- Lantic's cane side: "St. Lawrence Sugar's original cane refinery was built on the shores of the St. Lawrence river in 1888." Rogers: "established in 1890 by the entrepreneurial B. T. Rogers"; "Rogers' refinery was Vancouver's first major industry not based on logging or fishing." "Lantic Inc. is born after the merger of Lantic Sugar Limited and Rogers Sugar Ltd. in June 2008." (Lantic history page.) (a)
- StatCan 2025 sugar beets: Alberta 730,798 t; Ontario's figure is suppressed (flag "F"). Table 32-10-0359-01. (a)
- Pair with CFIA (1.1): "Refined in Canada" is CFIA's own example for "imported cane sugar which has been refined in Canada". **The No Frills listing does not say whether the 2 kg Lantic bag is beet or cane. Do not say which.**

### 3.10 Eggs
- **Producer price, not shelf price, is what supply management sets.** Egg Farmers of Canada: "The cost to produce a dozen eggs is calculated by examining the expenses necessary for its production." EFC lists three pillars: production management, import control and producer price. https://www.eggfarmers.ca/2020/01/supply-management-101/ (dated January 20, 2020; EFC refused curl with 403, so read by WebFetch at about 02:06 UTC). (a)
- **"Canada Grade A" is a grade, not an origin.** BC Egg Marketing Board, "Egg Labels 101" (https://bcegg.com/eggs-101/egg-labels-101/, opened 02:06 UTC): "just because it says "Canada Grade A" doesn't necessarily mean the eggs were laid in Canada, on Canadian egg farms. The "Canada Grade A" designation is granted if the eggs are graded in a licensed, Canadian grading facility and meet the "Grade A" standards, but they don't have to be Canadian eggs. However, they DO have to be clearly labeled as "Product of" their country of origin." (a) The CFIA rule behind it: Canadian Grade Compendium Volume 9, s. 1(2), imported eggs "graded by a licence holder … must use the Canadian grade name" (https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference/canadian-grade-compendium-volume-9, modified 2026-02-06, opened 02:10 UTC). Do NOT suggest the No Name eggs are imported; the listing says nothing about origin either way.
- Farm count, CARRIED: "1,295 egg farms and farm families located across Canada" (EFC 2025 Annual Report, per research_eggs.md source S14, opened 3 Oct 2026). Not re-opened today.
- Canadian Dairy Commission's 31 Oct 2025 release says that over five years eggs rose 28% and meat 26%, against 21% for dairy and 24% for all food (CDC paraphrase; see 3.11 for source and the wording to avoid).

### 3.11 Milk (4 L)
- **Only the farmer's price is regulated.** CDC, "2026 increase to farmgate milk price aligned with inflation", Ottawa, October 31, 2025 (https://cdc-ccl.ca/en/2026-increase-farmgate-milk-price-aligned-inflation, opened 02:06 UTC), verbatim: "Regulating the price of milk is one of the elements of the supply management system for dairy. However, only the price of milk that farmers get is regulated. With the exception of fluid milk in some provinces, the retail price of dairy products is not regulated in Canada." (a)
- **The February 1, 2026 number:** "The result of the National Pricing Formula (NPF)… is an increase of 2.3255%." Combined with carrying charges, "an increase in the cost of milk… of 2.3750%, which translates to just over 2 cents per litre of milk sold to processors". And: "A change in price paid to farmers for their milk does not necessarily translate to a similar consumer price change." The formula "takes into account 50% of the variation in the indexed cost of production as well as 50% variation in the consumer price index." (a)
- **Timing hook:** the CDC FAQ says "The CDC announces the price adjustment, if any, by November 1st of the current year at the latest… These will be available in mid-December of the current year and will apply on February 1st of the following year." (https://cdc-ccl.ca/en/node/895, opened 02:06 UTC). As of 02:06 UTC on 7 Oct 2026 the CDC "Pricing Announcements" page lists nothing newer than the 31 Oct 2025 releases, so **the February 2027 farm price has not been announced yet; it is due by November 1, 2026.** Last year's sequence: survey results to stakeholders 6 Oct 2025, final announcement 31 Oct 2025 (https://cdc-ccl.ca/en/national-pricing-formula-and-february-1-2026-farmgate-price-milk-adjustments). (a)
- The Neilson listing carries the "Prepared in Canada" website badge. On Neilson ownership see U10.

### 3.12 Whole chicken
- Chicken Farmers of Canada on itself (https://www.chickenfarmers.ca/about-us/, opened 02:10 UTC): "our 2,800 farmers", and the national board "meet every eight weeks to decide, based on market demand, just how much chicken to raise". (a; leave out the rest of that sentence, see section 6)
- CFPR 2026 (1.4): chicken "set to increase substantially in 2026 due to underproduction". The report says "The industry did not meet its targets for the last nine consecutive periods". Quote it as the report's words about production levels, nothing more.
- CFIA (1.1): chicken from imported hatching eggs can still be "Product of Canada" if raised, slaughtered and processed here. The No Frills badge on both whole-chicken listings is "Prepared in Canada", not "Product of Canada".
- No Nutrition Facts table is required on raw single-ingredient poultry (1.3).

### 3.13 Potatoes
- **Prince Edward Island is not Canada's biggest potato producer by weight.** StatCan table 32-10-0358-01, 2025 production (thousands of hundredweight): Canada 125,892; **Alberta 34,045 (27.0%)**, Manitoba 26,879 (21.4%), PEI 21,346 (17.0%), New Brunswick 16,203 (12.9%), Quebec 14,276 (11.3%), Ontario 8,803 (7.0%). In tonnes (×45.359 kg per cwt, our arithmetic): Canada about 5.71 million t; Alberta about 1.54 million t; PEI about 0.97 million t. (a) PEI still planted the most acres in 2025: 87,300 of 397,122 acres (22.0%) vs Alberta 81,760.
- **2026: Alberta now plants the most too.** StatCan, The Daily, "Canadian potato production (seeded area), 2026", released 2026-07-17 (https://www150.statcan.gc.ca/n1/daily-quotidien/260717/dq260717b-eng.htm, opened 02:08 UTC): "Potato farmers planted 395,176 acres (159 922 hectares) of potatoes in 2026, down 0.5% compared with 2025." "In 2026, Alberta reported the largest seeded area at 86,000 acres, followed closely by Prince Edward Island (83,700 acres) and Manitoba (70,500 acres)." (a)
- Label decode: CFIA Canadian Grade Compendium Vol. 2, s. 177: "The grades and grade names for potatoes are Canada No. 1 and Canada No. 2." (https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference/canadian-grade-compendium-volume-2, modified 2026-04-15, opened 02:10 UTC). (a)

### 3.14 Frozen peas and frozen mixed vegetables
- **"Canada A" on the bag is a grade, and an import can carry it.** CFIA Canadian Grade Compendium Vol. 3 (Processed Fruit or Vegetable Products, modified 2022-08-09, opened 02:10 UTC): s. 78(1) "The grade and grade names for frozen mixed vegetables are Canada A and Canada B." s. 78(2) "Canada A is the name for the grade of frozen mixed vegetables if every vegetable included in the mixture is of the grade Canada A." s. 82(1) "The grade and grade names for frozen peas are Canada A and Canada B." Vol. 9, s. 1(2): imported "processed fruit or vegetable products (items 34 and 35), if they are graded by a licence holder… must use the Canadian grade name" (item 35 is "Frozen Processed Fruit or Vegetable Product": CANADA A / GRADE A). And CFIA's origin page puts grade names outside the origin guidelines (1.1). (a)
- Script use: "The words 'Canada A' tell you the grade. They are not a promise about where the peas grew." Do NOT say or imply the No Name bag is imported; the listing gives no origin.
- Green peas in the field (fresh and processing): 2025, Ontario 26,625 t of Canada's 44,943 t; Quebec 11,062 t. StatCan 32-10-0365-01. (a)

### 3.15 Carrots
- **Ontario and Quebec grow about four in five Canadian carrots.** StatCan 32-10-0365-01 (released 2026-02-16), 2025 total production: Canada 412,643 t; Ontario 169,384 t (41.0%), Quebec 156,882 t (38.0%), Nova Scotia 50,056 t (12.1%). Carrots were Canada's second-largest field vegetable by tonnage in 2025, after tomatoes (649,054 t). (a; table note: "These commodities include fresh and processed vegetables.")
- The Daily, "Fruit and vegetable production, 2025" (2026-02-16, https://www150.statcan.gc.ca/n1/daily-quotidien/260216/dq260216c-eng.htm, opened 02:08 UTC): national vegetable production rose 8.0% "driven by higher volumes of tomatoes (+18.4%) and carrots (+15.5%)"; "In Quebec, both production and sales increased, driven by higher volumes of carrots (+45.9%)". (a)

### 3.16 Canned tomatoes and tomato sauce
- **Ontario grows 98% of Canada's field tomatoes.** StatCan 32-10-0365-01, 2025 total production (fresh and processed): Canada 649,054 t; Ontario 637,389 t (98.2%); Quebec 9,140 t. (a)
- The No Name diced tomatoes listing has no badge and no origin text; the No Name tomato sauce listing has the "Prepared in Canada" badge. Don't connect either to Ontario fields.

### 3.17 Bananas
- StatCan (April 17, 2024 article, opened 02:11 UTC): "In 2023, Canada imported 587.1 million kg of bananas (other than plantains, fresh or dried)"; "Close to half of the bananas imported in 2023 came from Guatemala (46.5%), followed by Costa Rica (17.2%), Colombia (10.2%), Honduras (9.0%) and Ecuador (8.9%)." "In 2022, there were 14.68 kg of bananas available per Canadian—which works out to around 10 bunches each!" (a; 2023 data, say the year.)
- July 2026: $1.88/kg national average, cheapest of all 25 per-kg items in StatCan's table (1.6). Up 12.6% year over year (u1_statcan.md).

### 3.18 Canned light tuna
- **"Light" is about the colour of the meat.** CFIA, "Labelling requirements for fish and fish products" (https://inspection.canada.ca/en/food-labels/labelling/industry/fish, modified 2025-01-15, opened 02:11 UTC): "The labels on all packages of hermetically sealed tuna must indicate the colour of the fish flesh". Permitted: "White meat tuna" / "white tuna" "(only tuna of the species Thunnus alalunga)", "Light meat tuna" / "light tuna", "Dark meat tuna". (a) The No Name listing's ingredients: "Skipjack Tuna, Water, Salt."
- Imported fish: "For prepackaged fish imported into Canada, the name of the country of origin must be clearly identified on the label… The country of origin is the country where the last substantial transformation occurred." (same page) The No Frills listing shows no country; read the can on camera if the script names one.

### 3.19 Margarine
- Canadian Encyclopedia ("Margarine", Erwin Kreutzweiser, last edited December 16, 2013; WebFetch read about 02:15 UTC; tier b): "In Canada, the manufacture and sale of margarine was forbidden by an Act of Parliament in 1886." "The ban was enforced until 1917, when wartime shortages of butter brought legalization; it was banned again in 1923." "Margarine did not become permanently legal until 1948, when Parliament referred the issue to the Supreme Court." Re-verify on screen; see U11 on Quebec's colour rule.
- Imperial listing ingredients begin "Soybean And/or Canola And/or Vegetable Oils 43%". Do not claim Canadian canola is in it.

### 3.20 Cabbage and onions (if used)
- Cabbage 2025: Quebec 96,437 t of Canada's 193,629 t (49.8%), Ontario 73,585 t. Dry onions 2025: Quebec 127,080 t of 277,287 t (45.8%), Ontario 93,275 t, Alberta 41,061 t. StatCan 32-10-0365-01. (a)
- Cabbage is the second-cheapest per-kg item StatCan tracks, at $2.90 in July 2026 (1.6).

---

## 4. Ready lines (each carries its source in the sentence)

- "According to the Canadian Food Inspection Agency, 'Product of Canada' means all or virtually all of the major ingredients, processing and labour are Canadian. 'Prepared in Canada' just means it was prepared here."
- "Across every No Frills listing we pulled on October 7, the only Canada badge the website shows is 'Prepared in Canada'. Not one says 'Product of Canada'."
- "Health Canada's Table of Reference Amounts sets the serving: 45 grams of dry rice, 85 grams of dry pasta, 35 grams of dry lentils, 15 grams of peanut butter."
- "Statistics Canada's figures say Saskatchewan grew 86 per cent of Canada's lentils in 2025, and Saskatchewan's government says that province alone accounts for 37 per cent of the world's lentil exports by value."
- "Statistics Canada says Alberta, not P.E.I., grew the most potatoes by weight in 2025, and in 2026 Alberta planted more acres too."
- "The Canadian Dairy Commission says only the price farmers get is regulated. On February 1, 2026 it rose 2.3255 per cent, which it calls just over two cents a litre."
- "'Canada A' on a frozen bag is a CFIA grade, and the CFIA requires imports graded here to use that same grade name."
- "Canada's Food Price Report 2026 forecast food prices up four to six per cent, and up to $17,571.79 for a family of four. In August, StatCan had grocery prices up 2.8 per cent."

---

## 5. SOURCE REGISTER

| # | Source | URL | Accessed (UTC, 2026-10-07) | Tier | Method |
|---|---|---|---|---|---|
| S1 | CFIA, Origin claims on food labels (modified 2023-12-06) | https://inspection.canada.ca/en/food-labels/labelling/industry/origin-claims | 02:02 | a | curl, full text |
| S2 | Food and Drug Regulations C.R.C., c. 870, full text (current to 2026-09-21) | https://laws-lois.justice.gc.ca/eng/regulations/C.R.C.,_c._870/FullText.html | 02:03 | a | curl, full text |
| S3 | Health Canada, Table of reference amounts for food (published Oct 18, 2024) | https://www.canada.ca/en/health-canada/services/technical-documents-labelling-requirements/table-reference-amounts-food/nutrition-labelling.html | ~02:04 | a | WebFetch x2 (curl refused); re-verify |
| S4 | Dalhousie news release, CFPR 2026 (Dec 4, 2025) | https://www.dal.ca/news/2025/12/04/canada-food-price-report-2026.html | 02:05 | a | curl |
| S5 | Canada's Food Price Report 2026, full PDF | https://cdn.dal.ca/content/dam/dalhousie/pdf/sites/agri-food/FINAL%20E%20low.res%20DAL_PRICE_REPORT_2026.pdf | 02:05 | a | curl + text extraction |
| S6 | CDC, NPF and Feb 1, 2026 adjustments (Oct 14, 2025) | https://cdc-ccl.ca/en/national-pricing-formula-and-february-1-2026-farmgate-price-milk-adjustments | 02:05 | a | curl |
| S7 | CDC, 2026 increase to farmgate milk price (Oct 31, 2025) | https://cdc-ccl.ca/en/2026-increase-farmgate-milk-price-aligned-inflation | 02:06 | a | curl |
| S8 | CDC, Pricing Announcements; Latest News 2026; FAQ (node/895) | https://cdc-ccl.ca/en/pricing-announcements ; https://cdc-ccl.ca/en/latest-news-2026 ; https://cdc-ccl.ca/en/node/895 | 02:06 | a | curl |
| S9 | Egg Farmers of Canada, Supply management 101 (Jan 20, 2020) | https://www.eggfarmers.ca/2020/01/supply-management-101/ | ~02:06 | a | WebFetch (curl 403) |
| S10 | BC Egg Marketing Board, Egg Labels 101 | https://bcegg.com/eggs-101/egg-labels-101/ | 02:06 | a | curl |
| S11 | StatCan table 32-10-0359-01 (field crops; release 2026-09-16) | https://www150.statcan.gc.ca/n1/tbl/csv/32100359-eng.zip | 02:06 | a | CSV + WDS metadata |
| S12 | StatCan, The Daily, Model-based principal field crop estimates, August 2026 (2026-09-16) | https://www150.statcan.gc.ca/n1/daily-quotidien/260916/dq260916b-eng.htm | 02:07 | a | curl |
| S13 | Government of Saskatchewan, Ministry of Agriculture, 2024 Marketing Materials (file dated 10/23/2025) | https://publications.saskatchewan.ca/api/v1/products/127522/formats/150566/download | 02:07 | a | PDF text extraction |
| S14 | StatCan table 32-10-0358-01 (potatoes; release 2026-07-17) | https://www150.statcan.gc.ca/n1/tbl/csv/32100358-eng.zip | 02:07 | a | CSV + WDS |
| S15 | StatCan table 32-10-0365-01 (vegetables; release 2026-02-16) | https://www150.statcan.gc.ca/n1/tbl/csv/32100365-eng.zip | 02:07 | a | CSV + WDS |
| S16 | StatCan, The Daily, Canadian potato production (seeded area), 2026 (2026-07-17) | https://www150.statcan.gc.ca/n1/daily-quotidien/260717/dq260717b-eng.htm | 02:08 | a | curl |
| S17 | StatCan, The Daily, Fruit and vegetable production, 2025 (2026-02-16) | https://www150.statcan.gc.ca/n1/daily-quotidien/260216/dq260216c-eng.htm | 02:08 | a | curl |
| S18 | Lantic, History | https://www.lanticrogers.com/en/about-us/history | 02:09 | a | curl |
| S19 | Lantic, About us | https://www.lanticrogers.com/en/about-us | ~02:09 | a | WebFetch; re-verify |
| S20 | Prairie Oat Growers Association, The Oat Industry | https://poga.ca/about-poga/the-oat-industry/ | 02:09 | b (industry body on itself) | curl |
| S21 | Pulse Canada home page | https://www.pulsecanada.com/ | 02:09 | b (industry body on itself) | curl |
| S22 | CFIA Canadian Grade Compendium Vol. 2 (fresh; modified 2026-04-15) | https://inspection.canada.ca/en/about-cfia/acts-and-regulations/list-acts-and-regulations/documents-incorporated-reference/canadian-grade-compendium-volume-2 | 02:10 | a | curl |
| S23 | CFIA Canadian Grade Compendium Vol. 3 (processed; modified 2022-08-09) | …/canadian-grade-compendium-volume-3 | 02:10 | a | curl |
| S24 | CFIA Canadian Grade Compendium Vol. 9 (imports; modified 2026-02-06) | …/canadian-grade-compendium-volume-9 | 02:10 | a | curl |
| S25 | Chicken Farmers of Canada, About us | https://www.chickenfarmers.ca/about-us/ | 02:10 | a | curl |
| S26 | Canadian Grocer, Q&A: Jessica Jones on Kraft Heinz Canada's $250-million investment (Rebecca Harris, 3/27/2026) | https://canadiangrocer.com/qa-jessica-jones-kraft-heinz-canadas-250-million-investment | 02:10 | b | curl |
| S27 | StatCan, Bananas: Peeling away at inflation (Apr 17, 2024) | https://www.statcan.gc.ca/o1/en/plus/6085-bananas-peeling-away-inflation | 02:11 | a | curl |
| S28 | StatCan WDS getCubeMetadata, table 18-10-0245-01 | https://www150.statcan.gc.ca/t1/wds/rest/getCubeMetadata | 02:11 | a | API |
| S29 | StatCan table 18-10-0245-01 CSV (July 2026, already on disk: u1/statcan_dl/18100245.csv) | https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip | file from 01:55 | a | CSV |
| S30 | CFIA, Labelling requirements for fish (modified 2025-01-15) | https://inspection.canada.ca/en/food-labels/labelling/industry/fish | 02:11 | a | curl |
| S31 | StatCan, The Daily, Consumer Price Index, August 2026 (2026-09-14) | https://www150.statcan.gc.ca/n1/daily-quotidien/260914/dq260914a-eng.htm | 02:13 | a | curl |
| S32 | PepsiCo Canada, Quaker About Us | https://contact.pepsico.com/quakerca/about-us | 02:15 | a | curl |
| S33 | The Canadian Encyclopedia, Margarine (last edited Dec 16, 2013) | https://www.thecanadianencyclopedia.ca/en/article/margarine | ~02:15 | b | WebFetch (curl 403); re-verify |
| S34 | PC Express API, No Frills #7952 Toronto, #3155 Calgary, #3403 Vancouver: product-detail and search JSONs | scratchpad u1/nofrills_7952/, u1/nofrills_3155/, u1/nofrills_3403/, c3live/ (log: u1/capture_log.tsv) | captured 01:20-02:00 | a (retailer listing) | API; badge scan script f1/badges.py |
| S35 | CARRIED: EFC 2025 Annual Report via research_eggs.md S14 | see /home/user/Food/research_eggs.md | opened 2026-10-03 | a | not re-opened |
| S36 | Search-result snippets only (Saputo/Neilson; OEC; trendeconomy; foodlabelmaker; indexbox; agcanada) | various | 02:01-02:15 | c | not opened or refused; do not use |

---

## 6. UNVERIFIED / DO-NOT-USE

**Unverified (do not air until fixed):**
- **U1.** Any statement that a package *label* says "Prepared in Canada" or "Product of Canada". Everything in section 2 is a **website badge**. Film the package first.
- **U2.** "98% Canadian" as the CFIA test. The current CFIA page says "less than a total of 2%" for minor ingredients and does not print "98%".
- **U3.** Health Canada Table of Reference Amounts rows were read by an automated summary, not raw text: confirm on screen before quoting the numbers. In particular: sugar (summary gave 10 g; the Lantic listing shows 4.0 g), raw poultry (summary gave "125 g raw, 100 g cooked"; the No Frills whole-chicken listing shows 113 g), canned tomatoes (summary gave "167 mL canned" under a fruit heading, which looks wrong), and every item number (C.7, K.2 and so on).
- **U4.** Lantic "Canada's only sugar beet factory" was read by WebFetch only (the history page, read by curl, says "Today's remaining operation is in Taber"). Fine to say "Lantic says"; confirm wording on screen.
- **U5.** Canada-level share of world lentil exports. 37% is **Saskatchewan's** share. A Canada figure of about 42% is our derivation (37% ÷ 0.88) and is not published by any source opened here. Do not air a Canada percentage.
- **U6.** "Canada is the world's largest exporter of oats / lentils / peas" said as a flat fact. Only POGA (oats) and Pulse Canada (lentils, peas) say it, about their own sectors. Attribute by name or drop it.
- **U7.** Rice: no primary source opened for "Canada grows no commercial rice" or for Canada's rice import volumes or countries. The figures seen (OEC, trendeconomy, indexbox, Statista) are tier c. Do not use.
- **U8.** Pulse Canada's "world's largest exporter of … chickpeas, dry beans and faba beans". The Saskatchewan Government puts Saskatchewan at 6% of world chickpea exports, and nothing opened here supports Canada being first for chickpeas or dry beans. Use Pulse Canada's line for lentils and peas only.
- **U9.** POGA's "Saskatchewan typically produces more than 50% of Canadian oats each year making Saskatchewan the largest oat producing region in the world". Contradicted for 2024-2025: StatCan 2025 has Saskatchewan at 45.0%; the Saskatchewan Government says 44%. Do not use.
- **U10.** Neilson ownership (Saputo bought Neilson Dairy from Weston Foods, Oct 2008, $465 million). Search snippet only; Saputo's newsroom timed out and agcanada returned 403. Do not use until a primary page is opened.
- **U11.** Quebec's margarine-colour rule and the year it ended (often given as 2008). No source opened. The Canadian Encyclopedia says only that "some provinces forbade the colouring of margarine".
- **U12.** Kraft Heinz's U.S. headquarters or ownership line. Not opened today. Say "Kraft Heinz Canada", nothing more.
- **U13.** Ontario sugar beets going to a U.S. processor. Not verified; StatCan suppresses Ontario's 2025 figure. Do not use.
- **U14.** EFC farm count of 1,295 is CARRIED from 3 Oct 2026 and not re-opened.
- **U15.** Canada's 2025 potato crop in tonnes (about 5.71 million t) and Alberta's (about 1.54 million t) are our conversions from hundredweight. Say "our conversion" or use StatCan's hundredweight figures.
- **U16.** Feb 2027 farmgate milk price. Not announced as of 02:06 UTC Oct 7 (due by Nov 1). Do not forecast it.
- **U17.** August 2026 StatCan average retail prices. Not released as of 02:11 UTC Oct 7. Every average price is July 2026.

**Do-not-use (house rules):**
- **D1.** Every No Frills / PC Express **description text** for the candidate items. The rice, chickpeas, canned lentils, oats, PC Blue Menu lentils, bananas, tuna, milk and eggs descriptions contain nutrition, health-benefit or taste wording that the house rules ban. Quote only the product name, size, ingredients line and badge.
- **D2.** CFPR 2026 text on nutrition legislation, front-of-pack labelling, milk fortification, "nutrient dense" foods, food-bank and food-insecurity health framing, and the release's line about grocery chains ("reign in corporate grocery greed…"). The last implies wrongdoing; the rest are health framing.
- **D3.** CDC quick fact phrased "Comparable sources of [banned word] such as eggs…". Paraphrase the numbers only, as in 3.10.
- **D4.** Chicken Farmers of Canada's full sentence about producing chicken that is safe and high quality, and Quaker's "power-packed line of nourishing food products". Safety and nutrition framing.
- **D5.** CFIA frozen-pea grade criteria about "good flavour", "tender" and so on. Quoting regulator grade criteria about taste risks stating taste as fact. Use only the grade names and the mixed-vegetable "every vegetable" rule.
- **D6.** Any best-before, storage or shelf-life statement for any item, including the BC Egg page's best-before paragraph.
- **D7.** Any link between a No Name or PC product and a named manufacturer, mill, plant, farm, packer or region (for example Quaker's Peterborough plant and No Name oats; Kraft's Montreal line and No Name peanut butter; Ontario tomato fields and No Name diced tomatoes; Lantic and No Name sugar).
- **D8.** U.S.-sourced figures (USDA, U.S. trade data) presented as Canadian. None are used here.
- **D9.** Pulse Canada's and Saskatchewan's environmental and carbon-footprint claims ("115 per cent lower" and similar). Off-topic and not independently verified.

---

## GAP FIXES (critic), 7 Oct 2026, 02:19–02:26 UTC (full report: `scratchpad/u1_gaps.md`)

### 3.21 Popping corn (#3), the gap: this item had no fact

**P1. Label servings differ by brand for the same food at the same store.** Source: PC Express product detail, No Frills #7952 Toronto, re-fetched 02:21 UTC on 7 Oct (tier a).
- No Name Popping Corn 1 kg (21291313_EA): 50 g serving, $2.50 REGULAR, 20 servings, $0.125 each, $0.25 per 100 g.
- Orville Original Gourmet Popping Corn Kernels 850 g (20308686_EA): 63 g serving, $5.99 REGULAR, 13.49 servings, $0.444 each, $0.705 per 100 g.
- Ready line: "Even the serving size isn't the same from brand to brand. No Name lists fifty grams, Orville lists sixty-three. So compare per hundred grams: twenty-five cents against just over seventy."

**P2. City spread.** No Name Popping Corn 1 kg was $2.50 at No Frills Toronto #7952 and $3.00 at both No Frills Vancouver #3403 and Calgary #3155 (all REGULAR, 7 Oct). It was $3.49 at Loblaws #1000 Toronto. This is the only packaged No Name pick that cost more out West.

Do not use:
- The Orville ownership line: the Conagra FY2026 10-K does not name Orville, and no primary brand page loaded.
- "Canada's most popular popcorn": a 2010 company marketing claim.
- The No Name listing's ingredients field: it lists an unrelated product.
- "Unpopped": not stated in the No Name record.

### Corrections to earlier sections
- **1.3 script line is wrong.** The ranking used the retailer-listed serving (carrots 100 g, potatoes 100 g, bananas 140 g), not Health Canada reference amounts. Replace it with: "Fresh produce doesn't have to carry a Nutrition Facts table, so for bananas, carrots and potatoes we used the serving the No Frills website lists."
- **1.2 overstates uniformity.** Change "the brand does not pick the serving size freely" to "the serving has to follow Health Canada's labelling rules, but it isn't identical from brand to brand" (see P1).
- **1.2 / U3.** A second WebFetch read of the Health Canada table (about 02:23 UTC; curl got an empty reply) gave vegetables 125 g, not 85 g. It also gave popcorn (S.1) 50 g and eggs "number of eggs closest in weight in grams to the RA". The two automated reads disagree, so U3 stands: no reference amount goes on air until it is read verbatim.
- **Section 4, ready line 2** ("only Canada badge… 'Prepared in Canada'… Not one says 'Product of Canada'") is **withdrawn**. It quotes the phrases from a website badge, and house rules allow them only as exact label wording.
- **Coverage confirmed:** every one of the 15 now has a StatCan line or a sourced, non-health fact. Rice (#1) has StatCan only (U7 stands), and oats (#2) and popping corn (#3) have facts only.


======================================================================

# U1 RETENTION DOSSIER: 15 Foods That Still Cost Under $1 a Serving in Canada (October 2026 Prices)

Prepared 7 October 2026, 02:05-02:20 UTC, for Canadian Counter. The upload is 8 October 2026 at 20:00 UTC.
Scope: retention and structure only. Prices and item order are taken from the sibling dossier `scratchpad/u1_prices.md` (No Frills #7952, Toronto, 7 Oct 2026). They must be re-captured on 8 Oct before lock, because every number in the hook depends on them.

---

## 0. Key findings (read first)

1. **The first item comes too late on CC's own compilations.** "15 CANADIAN Foods You'll Regret..." reaches item #15 (pasta) at about 2:17. A viewer's timestamp comment puts it at 2:21. "10 Fake Foods..." reaches item one at about 2:17. The three outside hits all reach item one by 0:46-1:10. This video must start #15 within the first 850 characters of narration.
2. **The outside hits are built around a loop.** Each plants a loop in the first minute ("Number one on my list is the best one... stay with me") or at the halfway point ("number 20 is the one that'll actually change your bill the most. It's the one thing on this list that isn't food at all"), then pays it off late, at 70-79% of the video. CC's 15-foods video ended on salt, introduced as "the least dramatic item in the store on purpose", which deflated the payoff. Our #1 is the cheapest food per serving: a specific number (11.25 cents), planted in the hook and paid off with the full division on screen.
3. **The ask in the CC videos sat at about 45%** (10:01 in Fake Foods, 11:53 in 15 Foods). This video's ask goes at 61-63%, at the hinge "six foods left, every one under nineteen cents a serving". The budget in section 4 puts it at 61.6%.
4. **The biggest opening in the comments: "I'm Canadian and even these basic staples cost A LOT MORE"** (53 likes, on Tried & True's 370K video). All three outside hits use U.S. figures. Money Culture America's description says it uses "U.S. retail pricing data". A Canadian, store-dated, per-serving version is the gap.
5. **Regional pushback is the recurring complaint on CC's own videos.** Examples: "each province has their own inflation", "that bag of sugar is 6$ in a part of Saskatchewan", "my pocket book says otherwise". The second-city check (Vancouver and Calgary No Frills) has to be spoken in the script, not just held in the dossier.
6. **The outside hits are full of things our house rules ban**: "protein" (11 uses across the three), "filling" or "fill you up", claims about how long food keeps, food-safety advice ("cut the sprouts off", "kidney beans will make you good and sick", the egg float test), and "scam". The top comment on Money Culture America (80 likes) is a correction of its potato-sprout advice. CC's own two hits also use now-banned words: "trick" (9) and "hidden", "quietly" and "caught" in Fake Foods, and "quietly" and "hidden" in 15 Foods. See section 6.
7. **Pace discrepancy.** The rules file says 21,000-23,000 characters is about 15-17 minutes. CC's measured pace is lower: Fake Foods ran 22,485 transcript characters in 22:20 (16.8 characters per second), and 15 Foods ran 23,803 in 26:14 (15.1 characters per second). At about 16 characters per second, 1:00 is about 950 characters, and a 22,300-character body runs about 23 minutes. The budget below shows timings at both paces.
8. **Real retention curves were not available.** NexLev `list_my_youtube_channels` returns only "Flip Choose" (UC_Wg7NQGrR73F8YnLw6VZ6g), not Canadian Counter (UCkuoOyuZyRqA49o5irJai9A). No audience-retention data was pulled for any video. Every "retention" point here is structural (where items, asks and loops fall), not a drop-off curve. Connect Canadian Counter at dashboard.nexlev.io/analytics to get real curves.

---

## 1. Videos studied (views pulled live, 2026-10-07 ~02:08 UTC)

| # | Channel | Title | Video ID | Published | Length | Views | Likes | Comments |
|---|---|---|---|---|---|---|---|---|
| O1 | Tried & True | You Only Need These 20 Groceries Every Week (Stop Buying the Rest) | 69p6tHh7qag | 2026-07-14 | 14:00 | **370,844** | 12,475 | 826 |
| O2 | Tried & True | Buy These 7 Groceries When Money's Tight | 9T6dDqRI2wQ | 2026-07-24 | 13:59 | **152,730** | 4,938 | 300 |
| O3 | Money Culture America | The 7 Cheapest Foods That Feed a Family (Real 2026 Prices) | 5UCblxPUtog | 2026-08-06 | 8:17 | **127,518** | 1,488 | 192 |
| C1 | Canadian Counter | 10 Fake Foods Canadians Are Buying Every Single Week (Check Your Kitchen) | 1NaLMzSsY8Q | 2026-08-09 | 22:20 | **48,679** | 1,158 | 48 |
| C2 | Canadian Counter | 15 CANADIAN Foods You'll Regret Not Stocking Up On Before 2026 Ends | Ri3vsAcrVoc | 2026-09-18 | 26:14 | **28,507** | 470 | 27 |

The IDs were found with NexLev `youtube_search` (Algrow `youtube_search` returned zero results for every query), and the CC IDs come from `scratchpad/cc_live_oct7.json`. For context, the flop "We Investigated 10 Tool Brands..." (Zh27O3oGTJk) had 131 views in cc_live_oct7.json.

All five transcripts were fetched with Algrow `fetch_transcript` and read in full. They are saved at `scratchpad/rt/<id>.txt`. They are auto-captions with no timestamps, so the times below are estimated in proportion to character position.

| Metric | O1 | O2 | O3 | C1 | C2 |
|---|---|---|---|---|---|
| Transcript characters | 13,476 | 13,770 | 7,707 | 22,485 | 23,803 |
| Words per minute | 177 | 188 | 172 | 176 | 159 |
| Characters per item (approx.) | ~490 | ~1,500 | ~690 | ~1,800 | ~1,270 |
| First item starts | 0:57 (6.8%) | 1:10 (8.4%) | 0:46 (9.4%) | **2:17 (10.2%)** | **2:17 (8.7%)** |
| Mid-video ask or plug | book plug 4:01 (28.7%) | book plug 2:31 (18.1%) | none | subscribe 10:01 (44.9%) | like and subscribe 11:53 (45.3%) |
| Loop planted | #20 at 6:37 (47%) | #1 at 1:04 | "#1 outperforms everything" bridge | "two phrases in your pocket" at ~1:20 | "the one I'd act on today" in the intro |
| Loop paid | 11:04 (79%) | 9:49 (70%) | 6:00 (73%) | apple juice ~16:00 (~70%) and the recap | salt 21:08 (81%), deflated |
| Sentences over 30 words | 6 | 11 | 3 | 20 | 18 |

---

## 2. Structure maps

### O1 Tried & True, "20 Groceries" (370.8K)
- **Hook, first 60 seconds:** a second-person checkout scene with a number: "You know that feeling at the checkout when the total comes up and you do a little flinch? $180..." Then a pantry paradox ("a full pantry saying there's nothing to eat"), then a stat pair ("The grocery store carries about 40,000 different items. A house runs on about 20."), then a thesis ("the same food taken apart, put in a smaller package, and sold back to you at three times the price"), then a persona ("feeding seven people on one income"), then a promise ("I'll tell you as we go which expensive thing each one replaces"). The tease for item one is paid immediately ("Number one... is the single best deal in the entire store... Let's go."). Item one starts at 0:57.
- **Countdown:** counts up from 1 to 20. That is unusual and works only because item one is billed as "the best deal".
- **Per item (~490 characters):** the number and plain item; "Not X, Y" (the plain form against the convenience form); a price or multiple ("10 times the price per serving"); what it replaces; a one-line punch ("You didn't buy salad, you rented it." "They sell a lot of minutes at that store.").
- **Re-hooks:** a book plug at 28.7% ("That's all I'll say about it."). At 47% comes the strongest re-hook in the set: "we're a little over halfway... stay with me because number 20 is the one that'll actually change your bill the most. It's the one thing on this list that isn't food at all."
- **Payoff:** #20 is salt and spices, reframed as "the biggest money saver" ("flavor costs about 8 cents"). Then a recap run of all 20, a total ("$70 to $90... not 180"), a "why your cart doesn't look like this" section on margins, a homework step ("swap three"), a two-question comment ask, and a tease for the next video.

### O2 Tried & True, "7 Groceries When Money's Tight" (152.7K)
- **Hook, first 60 seconds:** a receipt in the parking lot ("$140 and you're not even sure what you got"). Then "Here's what nobody tells you." Then the answer is not coupons; it is "seven of them by my count", which "the store just doesn't put... at eye level". Then an honesty promise ("what it won't do... I'm not going to stand here and tell you a bag of oats tastes like steak"). The loop is planted at 1:04: "Number one on my list is the best one, and it's the one most people walk right past. So stay with me." Item #7 starts at 1:10.
- **Countdown:** 7 down to 1.
- **Per item (~1,500 characters):** "Not the packets, the canister"; price per pound; per-serving maths ("a bowl of oatmeal costs you maybe 20 cents"); a second use (oats in meatloaf); "What oats won't do" (a fairness line); a storage or use tip.
- **Re-hooks:** a book plug at 18%; "hold that thought, we're getting there" (rice to beans); "And that brings us to number one, the one I promised you".
- **Payoff:** the whole chicken as "three dinners", a concrete three-step process (roast, pick, simmer). Then a recap with total ($25-30), "the quiet part" (a store-margin thesis), a one-step homework, a regional comment ask ("every region's got its own"), and a next-video tease.

### O3 Money Culture America, "7 Cheapest Foods" (127.5K)
- **Hook, first 60 seconds:** "Look at your last receipt. Not the total, the line items." Then "That's the store working exactly as designed." Then a credibility promise ("I went and pulled the actual current numbers... the government's own retail price data"), which is U.S. data according to the description. Item #7 starts at 0:46.
- **This is a near-clone of O2**: the same seven items and many of the same sentences (the meatloaf oats, "potatoes and onions spoil each other", "you paid them like a surgeon" becomes "you paid them for it", "toll for 30 minutes of work"). It shows the format can carry an 8-minute cut.
- **Per item (~690 characters):** the item, "skip the X", a price per pound, servings, one use, then **an explicit bridge tease ending every item**: "But oats are just the entry point. This next one is sitting... at one of its lowest prices in years". "Everything so far has been about what to buy. This next one is about what a single bag can turn into." "Rice is the floor. This next one is where the real savings live." This is the cleanest bridge pattern in the set.
- **Payoff:** "the one item that outperforms everything else on this list by a wide margin": the whole chicken, compared with ground beef per pound. There is no mid-video CTA. The end has a recap, a total, one swap, and a comment ask.

### C1 Canadian Counter, "10 Fake Foods" (48.7K)
- **Hook, first 60 seconds:** "Right now, somewhere in your kitchen, there is almost certainly a food that is lying to you." Then three unnamed teases (brown bread, maple-flavoured syrup, honey). Then "Most of it is completely legal." Then a front-against-back-of-package thesis. Then an "honest promise" block ("you have told us in the comments that you do not want scare tactics"). Then the yardstick planted as a loop: "Product of Canada and made in Canada... Keep those two phrases in your pocket. By the end of this video, they will unlock the whole game." **Item one starts at 2:17.**
- **Countdown:** ordered from "most universal" to "strangest", **with no spoken item numbers** (for example, "Begin with the loaf", "Stay in the dairy aisle"). That breaks Rule 3 of the house rules.
- **Per item (~1,800 characters):** a familiar anchor; the regulation or label; the ingredient list; a fairness line ("Let's be completely fair to Kraft"); an affordable Canadian fix.
- **Re-hooks:** the subscribe ask at 44.9% ("That is five items, and the pattern is already impossible to unsee... subscribe... Now, grab your pancakes because the second half opens with the most Canadian lie in the entire store."); the honey line "Hold on to that pattern... the next item is about to flip it inside out"; the pocket-phrases loop paid at apple juice.
- **Payoff:** "In nearly every case tonight, the honest version was Canadian." Then a "read three labels" homework and a sign-off.

### C2 Canadian Counter, "15 CANADIAN Foods" (28.5K)
- **Hook, first 60 seconds:** a Food Price Report forecast (4 to 6%, $17,571), then the actual CPI path, then a verbatim StatCan quote. There is no "you" plus a habit until later, and **no food is named or teased in the first minute**. Next come "Nothing is running out", the "best before / 90-day" filter yardstick (a durability claim, banned under the current rules), and the count ("15 foods, counting down from the least urgent to the one I'd act on today"). **Item #15 starts at 2:17.**
- **Per item (~1,270 characters):** StatCan index or price; supply story; a named filing or official; "Buy X, not Y". The data density is high, but there are no bridge teases between items.
- **Re-hooks:** "That's eight down and seven to go" plus like and subscribe at 45.3%, then "the second half is where the real pressure is."
- **Payoff:** #1 salt, "the least dramatic item in the store on purpose", followed by a three-group recap that is not in countdown order. The comments show **numbering confusion** ("Where are the last two?!", 6 likes, with a self-made list that goes wrong after #7) and a **visual mismatch** ("when you said 4.1% to 3.8%, to 2.8% while showing a graph rising?").

### Patterns to keep, and the ones to drop
- **Keep:** a second-person receipt or shelf scene with a number in the first sentence. The item count spoken exactly as in the title. A loop planted before 1:00 and paid at about 85-90%. Every item spoken as "Number X" first. A one-sentence bridge tease at the end of every item (O3 style). A "what it won't do" fairness line (O2 style). Homework in one step. A comment ask for a number the viewer already has.
- **Drop:** a yardstick or exposition intro over 1:00 (C1, C2); an unnumbered countdown (C1); a recap out of countdown order (C2); an anti-climactic #1 (C2); any keeping, safety or nutrition line (all five).

---

## 3. Comment mining (NexLev `youtube_video_comments`, sort = top, 20 per video, read 2026-10-07 ~02:08 UTC)

| Theme | Evidence (likes) | What the script does about it |
|---|---|---|
| U.S. prices don't fit Canada | O1: "I can tell you live in the US. I'm Canadian and even these basic staples cost A LOT MORE" (53, 6 replies) | Put the store, city, date and pack size on every price. Optional hook angle: "in kilos and Canadian dollars". |
| "Prices aren't the same where I live" | C2: "each province has their own inflation... Ontario 7.2%" (13); "that bag of sugar is 6$ in a part of Saskatchewan" (3); "my pocket book says otherwise" (3); "not in all of Canada" | Speak the Vancouver and Calgary check (the twist in section 5), say once that prices vary by location, and make the comment ask "your price, your city, your date". |
| Time is the real cost | O1: "The key is time... Spend less money, spend more time" (331 likes, 31 replies, the highest non-list comment); O3: dried beans "do not include the cost of... a stove running 2-3 hours" (14) | One honest line per relevant item: dry lentils (#5) need cooking, canned chickpeas (#8) don't, and that is why both are on the list. **Do not** give cooking times or safety steps. |
| "What about X?" additions | O1: ground beef, 5 lb sugar, baking powder (193); frozen berries, cottage cheese (209); garlic, whole milk (104); "legumes not just beans", maple syrup, sugar (20) | Add the "what we threw out" segment (sugar, peanut butter, margarine, each on its tiny label serving) just before the ask. It answers the question and works as a re-hook. |
| Cheaper protein cuts (meat) | O2: 10 lb chicken quarters under $9 (137); O3: chicken quarters $7.99 (107) | Expect "where's the chicken?" comments. **Not researched**: no chicken per-serving price is in the prices dossier. Either check a chicken item on 8 Oct or leave meat unmentioned. |
| Health talk floods the comments regardless | O1: "you'll be 10 thousand times healthier" (163), "essential for health" (104), "bill and health" (115); C2: "bad for our health" (6), "glyphosate... oats" (7); C1: microplastics in bottled water (13) | Do not engage, do not echo, and do not heart these. If a pinned comment is used, it should be about prices only. |
| Food-safety corrections hit the top | O3's **top comment**: "never eat potato sprouts... They are poison!!" (80), a correction of the video's "cut the sprouts" advice | This is proof that safety claims draw top-of-section corrections. Include none. |
| Numbering and visual mismatch | C2: "Where are the last two?!" (6); "showing a graph rising" (5); viewer-made timestamps (8) | Show an on-screen number card on every item, speak "Number X" as the first words, recap in strict countdown order, and match the b-roll to the number spoken. Add chapters. |
| Ownership interest | C2: "Kraft is American owned..." (5) | Viewers like ownership facts, but **never infer a supplier for No Name, PC or Farmer's Market items**. |
| Single households and fixed incomes | O1: "I live alone... fixed income" (46); O3: seniors at a food pantry (28) | Optional: the 8 kg rice beats the 2 kg on price per serving only if you use it all. Keep this about price only, with no keeping claims. |

Note: the pagination tokens returned the same 20 comments again on O1 and O2, so only the first page of top comments was read for each video.

---

## 4. Beat sheet: 15-item countdown under house constraints

### 4.1 Constraint checklist (the writer must verify each on the final draft)
- [ ] Body 21,000-23,000 characters (spoken narration only).
- [ ] **One** ask, containing "take a second to subscribe", starting at 61-63% of the body by character count. Window = 0.61 × total to 0.63 × total. At 22,315 characters that is 13,612-14,058. At 21,000 it is 12,810-13,230. At 23,000 it is 14,030-14,490. **Recompute after every edit.**
- [ ] "the truth is not always on the menu" appears **exactly twice**: in the mid-video twist and in the sign-off. Nowhere else, including the title card and the description text read aloud.
- [ ] **One** disclosure (draft in 5.4).
- [ ] A "How to protect yourself" section using First, Second, Third and Fourth.
- [ ] Every sentence 30 words or fewer. Every paragraph 6 sentences or fewer.
- [ ] #15 begins by about 1:00, which means **850 characters or fewer** of narration before "Number fifteen".
- [ ] 15 items of about 1,150-1,300 characters each.
- [ ] The hook contains "you" plus a number in the first sentence.
- [ ] A specific loop is planted in the hook (#1 = 11.25 cents a serving, item unnamed) and paid at #1 with the full division.
- [ ] Every price carries retailer, store, city, date, pack size and unit price.
- [ ] Zero banned words: protein, fibre, filling, nutritious, healthy, Canada's Food Guide, secret, hidden, quietly, caught (including the fishing sense), exposed, scam, trick. No keeping or safety claims, no taste or quality as fact, no implied wrongdoing, no supplier inference for store brands, no U.S. figures.
- [ ] **Rules conflict to resolve:** the rules file (Rule 14) asks for a mantra three times. This project asks for the tagline exactly twice. Recommendation: the tagline replaces the mantra; use no separate repeated mantra.

### 4.2 Character budget (target 22,315; the % column shows where each segment starts)

| Segment | Chars | Char range | Starts at | Time @ rules pace (1,375/min) | Time @ CC measured pace (16/s) |
|---|---|---|---|---|---|
| A Cold open (hook, teases, count, #1 loop, prices-vary) | 850 | 0-850 | 0.0% | 0:00 | 0:00 |
| B #15 Eggs (yardstick taught inside) | 1,300 | 850-2,150 | 3.8% | 0:37 | **0:53** |
| C Disclosure | 360 | 2,150-2,510 | 9.6% | 1:33 | 2:14 |
| #14 Flaked light tuna | 1,280 | 2,510-3,790 | 11.2% | 1:49 | 2:36 |
| #13 2% milk 4 L | 1,280 | 3,790-5,070 | 17.0% | 2:45 | 3:56 |
| #12 Frozen green peas | 1,280 | 5,070-6,350 | 22.7% | 3:41 | 5:16 |
| #11 Diced tomatoes | 1,280 | 6,350-7,630 | 28.5% | 4:37 | 6:36 |
| #10 White bread | 1,280 | 7,630-8,910 | 34.2% | 5:32 | 7:56 |
| #9 Carrots 3 lb | 1,280 | 8,910-10,190 | 39.9% | 6:28 | 9:16 |
| J Mid-video twist + tagline (1 of 2) | 550 | 10,190-10,740 | 45.7% | 7:24 | 10:36 |
| #8 Chickpeas (canned) | 1,280 | 10,740-12,020 | 48.1% | 7:48 | 11:11 |
| #7 Bananas | 1,280 | 12,020-13,300 | 53.9% | 8:44 | 12:31 |
| M "What we threw out" re-hook | 450 | 13,300-13,750 | 59.6% | 9:40 | 13:51 |
| **N THE ASK** ("take a second to subscribe") | 165 | 13,750-13,915 | **61.6%** | 10:00 | 14:19 |
| #6 Spaghetti | 1,180 | 13,915-15,095 | 62.4% | 10:07 | 14:29 |
| #5 Red split lentils (dry) | 1,180 | 15,095-16,275 | 67.6% | 10:58 | 15:43 |
| #4 White potatoes 10 lb | 1,180 | 16,275-17,455 | 72.9% | 11:50 | 16:57 |
| #3 Popping corn | 1,180 | 17,455-18,635 | 78.2% | 12:41 | 18:10 |
| #2 Large flake oats | 1,180 | 18,635-19,815 | 83.5% | 13:33 | 19:24 |
| **#1 Long grain white rice (loop paid)** | 1,250 | 19,815-21,065 | 88.8% | 14:24 | 20:38 |
| U How to protect yourself (First-Fourth) | 700 | 21,065-21,765 | 94.4% | 15:19 | 21:56 |
| V Close: synthesis, comment ask, next tease, tagline (2 of 2), sign-off | 550 | 21,765-22,315 | 97.5% | 15:49 | 22:40 |

The 15 items total 18,690 characters, an average of 1,246; the smallest is 1,180 and the largest 1,300. The ask hinge works because #6 through #1 (18.9, 14.7, 13.2, 12.5, 12.0 and 11.25 cents) are all under 19 cents. If the 8 Oct re-capture changes the order, keep the hinge sentence true or rewrite it.

### 4.3 Per-item template (about 1,250 characters; adapted from house Rule 5 for a positive list)
1. **"Number X." plus the item and a familiar anchor** (where it sits in a Canadian kitchen or routine; no taste claims). About 120 characters.
2. **The shelf line:** "At the No Frills on Richmond Street West in Toronto, listed on the seventh of October, a [pack] of [brand item] was [price]." About 200 characters.
3. **The division, spoken:** label serving (from the Nutrition Facts table, or "retailer-listed 100 g" for produce), servings per pack, cost per serving, per 100 g. About 260 characters.
4. **One comparison with a source in the sentence:** a name-brand pair at the same store, a second city, the Loblaws Queen St price, or the StatCan July national average ("across all brands and stores"; never "X% below the average for the same product"). About 280 characters.
5. **A fairness line or limit** (O2's "what it won't do", rebuilt on price): the sale ended, the label serving is dry weight, the product is priced by weight, there is no store brand at this store, and so on. About 180 characters.
6. **A verdict under 15 words, then a bridge tease** that names the next position, not the next item. About 200 characters.

### 4.4 Item-by-item beats (data from u1_prices.md; all regular prices at NF #7952, 7 Oct 2026)

| # | Item | Reg $/serving | Division to speak | Comparison beat | Fairness or limit beat | Bridge into next (draft) |
|---|---|---|---|---|---|---|
| 15 | No Name Large Eggs 12, $3.93 | $0.655 (per egg $0.3275) | **Teach the yardstick here:** price ÷ (pack ÷ label serving). Label serving 105 g; see UNVERIFIED for "2 eggs". | **Pack-size twist:** No Name 30-pack $10.04 = $0.3347/egg, **more** per egg than the dozen. Vancouver $4.26, Calgary $4.23. | Most expensive on the list and still under a dollar; the highest anywhere was $0.710 in Vancouver. | "Number fourteen comes in a can, and the store brand beats the name brand by seventy cents." |
| 14 | No Name Flaked Light Tuna 170 g, $1.29 | $0.417 | 55 g serving, 3.09 servings | Clover Leaf 170 g $1.99 reg (70 cents more; do not say its per-serving figure, since that serving size is unchecked). Loblaws Queen St $2.00. | The $1.00 sale ended on 7 Oct; the regular price is used. | "Number thirteen was a different brand in every city we checked." |
| 13 | Neilson 2% Milk 4 L, $6.44 | $0.403 | 250 ml, 16 servings | Dairyland $5.81 in Vancouver, Beatrice $6.35 in Calgary. | No store-brand 4 L was listed at #7952. | "Number twelve lives in the freezer, and it was three dollars in all three cities." |
| 12 | No Name Frozen Green Peas 750 g, $3.00 | $0.340 | 85 g, 8.82 servings | Same $3.00 in Toronto, Vancouver and Calgary; Loblaws $3.79. Mixed vegetables and corn are the same price. | The $2.77 sale ended on 7 Oct. | "Number eleven is a can, and it was two dollars from Toronto to Calgary." |
| 11 | No Name Diced Tomatoes 796 ml, $2.00 | $0.324 | 129 ml, 6.17 servings | StatCan July national average for 796 ml canned tomatoes: $2.27 (all brands). Loblaws $2.29. | None needed; regular price. | "Number ten has the same name in Toronto and Calgary, but not the same weight." |
| 10 | No Name Original Bread 675 g, $2.48 | $0.276 | 75 g, 9 servings | **The 520 g loaf at $2.50 in Vancouver and Calgary** ($0.481 vs $0.367 per 100 g). | **Required:** say these are separate products with different product codes, not a change to one product, and imply nothing more. | "Number nine comes out of the ground, and the bag sizes on offer depended on the city." |
| 9 | Carrots 3 lb (1.362 kg), $3.49 | $0.256 | Retailer-listed 100 g, 13.62 servings | The 3 lb bag was not listed in Vancouver or Calgary (2 lb at $3.99, 5 lb at $6.49). StatCan July average for 1.36 kg carrots: $4.75. | Produce has no Nutrition Facts table; say "100 grams, the serving the retailer lists". | **Into the twist.** |
| — | **Twist** (5.5) | | | | | |
| 8 | No Name Chickpeas 540 ml, $1.50 | $0.239 | 86 ml, 6.28 servings | $1.50 in all three cities; Loblaws $1.79. Kidney beans and canned lentils can be swapped in. | Optional time line: canned needs no soaking (a time point, not a safety one). | "Number seven is priced by the kilo, so no two bunches cost the same." |
| 7 | Bananas, $1.52/kg | $0.213 | 140 g retailer-listed, 7.14 per kg | Vancouver $1.72/kg, Calgary $1.92/kg, Loblaws $1.96/kg. StatCan July average $1.88/kg. | Priced by weight; your bunch will differ. | Into the "what we threw out" segment, then the ask. |
| — | **What we threw out (5.6), then THE ASK (5.7)** | | | | | |
| 6 | No Name Spaghetti 900 g, $2.00 | $0.189 | 85 g dry, 10.59 servings | Barilla 410 g $2.50 = $0.61/100 g against $0.222. Same $2.00 in three cities. | The label serving is dry weight. | "Number five costs more per bag than spaghetti, and less per serving." |
| 5 | PC Blue Menu Red Split Lentils 900 g, $3.79 | $0.147 | 35 g dry, 25.71 servings | StatCan July average for dried lentils 900 g: $3.63 (all brands). Same in three cities. | No No Name dry lentils at #7952; PC Blue Menu is also a Loblaw store brand. **Name no supplier.** | "Number four is the one item where the price depends on the week you shop." |
| 4 | White Potatoes 10 lb, $5.99 (Oct 8 API regular) | $0.132 | 100 g, 45.4 servings | It was $1.99 on special until 7 Oct. The regular $5.99 is **above** StatCan's July average of $5.32 for 4.54 kg. Vancouver and Calgary $6.99. | **HIGH RISK:** re-check on 8 Oct. Make this the honest "check the flyer" item. | "Number three is sold in the snack aisle, and it beats pasta, lentils and potatoes." |
| 3 | No Name Popping Corn 1 kg, $2.50 | $0.125 | 50 g unpopped, 20 servings | Orville 850 g $5.99 = $0.70/100 g against $0.25. Vancouver and Calgary $3.00. | Say "fifty grams of kernels, unpopped, the label serving". | "Number two is a breakfast, and the name brand costs a dollar more per bag." |
| 2 | No Name Large Flake Oats 1 kg, $3.00 | $0.120 | 40 g, 25 servings | Quaker Large Flake 1 kg $4.00. Loblaws $3.49. | Do not mention the SPECIAL tag; say "regular three dollars". | "One bag left. Five dollars. Forty-four servings." |
| 1 | No Name Long Grain White Rice 2 kg, $5.00 | **$0.1125** | 45 g dry, 44.44 servings | Loblaws Queen St $6.49 ($0.146); StatCan July average for 2 kg white rice: $9.62 (all brands); 8 kg Club Size $15.49 ($0.087). | "Different stores set different prices; nothing more is implied." Do not say "same owner" (see UNVERIFIED). | Into "How to protect yourself". |

Fairness lines needed: at least three mid-item concessions (Rule 10). The planned ones are #10, #4, #1, #5 and #9.

---

## 5. Draft lines (all checked: every sentence 30 words or fewer, zero banned words; character counts measured)

### 5.1 Hook drafts (all include "you" plus a number; no item, brand or store named in the teases except the city)

**H1 (recommended; 822 characters, so #15 starts by about 0:52 at CC's pace)**
> You can still buy a serving of food in Canada for eleven and a quarter cents. Not on sale. Not with a coupon. At the regular price, on a Toronto shelf, this week. But the price tag only gives you the package price. The serving size is on the back, in the Nutrition Facts table. We put the two together, fifteen times. One food on this list costs more per piece when you buy the bigger pack. Six cost exactly the same in Toronto, Vancouver and Calgary, to the cent. And one costs a dollar forty-nine more at a store about a kilometre and a half away. Same brand. Same size. Same bag. These are fifteen foods that still cost under a dollar a serving in Canada, at October 2026 prices. We count down from the most expensive to the cheapest. Number one is eleven and a quarter cents, and you'll see every step of the division.

The "prices vary by location" line sits in the disclosure (5.4), which keeps the hook under 850 characters.

**H2 (range-forward; 513 characters)**
> You have fifteen foods coming, and the most expensive one is sixty-five and a half cents a serving. The cheapest is eleven and a quarter. Every one of those numbers has a store, a city, a date and a pack size behind it. None of them is a sale price. One of them costs more per piece in the bigger pack. One costs a dollar forty-nine more a short walk away. Fifteen foods that still cost under a dollar a serving in Canada. Counted down from sixty-five cents to eleven. Number one is the plainest bag in the aisle.

**H3 (receipt habit, the O1/O2 style; 519 characters)**
> If you bought groceries this week, you looked at the total on the receipt. You didn't divide it by the servings. We did, for fifteen foods, at one Toronto store, on the seventh of October. The most expensive came to sixty-five and a half cents a serving. The cheapest came to eleven and a quarter. And we checked Vancouver and Calgary too, because a price without a city is half a fact. Fifteen foods that still cost under a dollar a serving in Canada. Number one costs five dollars a bag and holds forty-four label servings.

H2 and H3 leave room for a 300-character tease run (copy the three teases from H1) and still come in under 850.

### 5.2 The loop (planted, reinforced, paid)
- **Planted** at about 0:45: "Number one is eleven and a quarter cents" (H1), or "a dollar forty-nine more... same bag" (H1, H2).
- **Reinforced** in the twist (~45%): "The door you walk through can matter more, and number one proves it."
- **Reinforced** at the ask hinge (~61%): "Six foods left, and every one of them is under nineteen cents a serving."
- **Reinforced** before #1: "One bag left. Five dollars. Forty-four servings."
- **Paid** at #1 (~89%): the full division, plus the Loblaws Queen St figure that pays off "a dollar forty-nine more" (5.9).

### 5.3 Re-hook and bridge lines (one per item end; each is a single sentence)
- Into #15: "We start at the top of the range, with the one item where buying more costs you more per piece."
- The rest are in the table in 4.4. All 14 lines are checked in `scratchpad/u1_ret_lines.txt` (##REHOOKS). The longest is 20 words.

### 5.4 Disclosure (the only one; 357 characters; placed right after #15)
> One disclosure before number fourteen. Nobody paid for this video, and no store or brand saw it before you did. Every price is the regular price listed on nofrills.ca for the Richmond Street West No Frills in Toronto, on the seventh of October 2026. Sale prices that ended that day were left out. Prices vary by location, so check the tag on your own shelf.

If the 8 Oct re-capture becomes the price basis, change the date. The sponsorship statement must be confirmed true by the channel owner.

### 5.5 Mid-video twist (486 characters; tagline use 1 of 2)
> Here's what I didn't expect. We ran the same fifteen at No Frills stores on West Broadway in Vancouver and on Elbow Drive in Calgary. Six of the packaged staples were the same regular price in all three cities, to the cent. The fresh food was not. Bananas were a dollar fifty-two a kilo in Toronto and a dollar ninety-two in Calgary. So the province matters less than you'd think. The door you walk through can matter more, and number one proves it. The truth is not always on the menu.

The six, all regular prices on 7 Oct: rice, spaghetti, chickpeas, diced tomatoes, frozen peas and red lentils. Oats and tuna would make eight, but the western prices for those two are forward-dated (see UNVERIFIED). Raise the count to "eight" only after the 8 Oct re-capture confirms them.

Alternate twist, if the bread segment is cut: the eggs 30-pack costing more per egg than the dozen, moved from #15 to the midpoint.

### 5.6 "What we threw out" (396 characters; the re-hook just before the ask)
> Before the final six, here's what we threw out. A two-kilo bag of sugar works out to under one cent a serving. That's because the label serving is one teaspoon, four grams. A one-kilo jar of name-brand smooth peanut butter would have beaten every food on this list. Its label serving is one tablespoon, fifteen grams. Margarine's is ten grams. We ranked foods, not toppings, so all three are out.

Data: Lantic 2 kg at $2.99 regular = $0.006 per 4 g; Kraft Smooth PB 1 kg at $6.50 regular (today's REGULAR price, so verified) = $0.0975 per 15 g, which beats rice at $0.1125; margarine at 10 g. Brands may be named or left out. Do not use the No Name PB at $4.50, because it is forward-dated.

### 5.7 The ask (165 characters; the only one)
> Six foods left, and every one of them is under nineteen cents a serving. If you want this kind of maths before you shop, take a second to subscribe. Now, number six.

### 5.8 How to protect yourself (636 characters as drafted; budget 700)
> How to protect yourself, and your grocery budget, at the shelf. First, divide by the label serving. The package price is one number; the Nutrition Facts table gives you the other. Second, check every pack size. The thirty-pack of eggs cost more per egg than the dozen, and the eight-kilo rice cost less per serving than the two-kilo. Third, check the end date on any sale tag. Most of the sale prices we captured ended on Wednesday the seventh, so we ranked on regular prices. Fourth, check a second store, even under the same banner family. Rice was five dollars on Richmond Street and six forty-nine on Queen Street, in the same city.

The section is about prices only. It implies no wrongdoing: "protect" refers to the viewer's budget.

### 5.9 #1 payoff draft (1,202 characters)
> Number one. Long grain white rice. It's the plainest bag in the aisle, and it's the reason this video exists. At the No Frills on Richmond Street West in Toronto, on the seventh of October, a two-kilogram bag of No Name long grain white rice was five dollars. That's twenty-five cents per hundred grams. The label serving is forty-five grams, dry. Two thousand grams divided by forty-five is forty-four servings. Five dollars across forty-four servings is eleven and a quarter cents each. The same bag was five dollars at the No Frills in Vancouver and the one in Calgary. Now the promise from the top of this video. At the Loblaws on Queen Street West, about a kilometre and a half away, the same bag was listed at six forty-nine. That's fourteen point six cents a serving. Both stores carry Loblaw banners, and different stores set different prices. Nothing more than that is being said here. For context, Statistics Canada's national average for two kilos of white rice in July was nine sixty-two, across all brands and stores. And the eight-kilo bag on Richmond Street was fifteen forty-nine, or eight point seven cents a serving. Five dollars. Forty-four servings. Eleven and a quarter cents each.

Arithmetic: 2,000 ÷ 45 = 44.44; $5.00 ÷ 44.44 = $0.1125; $6.49 ÷ 44.44 = $0.146; $15.49 ÷ (8,000 ÷ 45 = 177.78) = $0.0871; $5.00 ÷ 20 = $0.25 per 100 g.

### 5.10 Close beats (550 characters)
1. Synthesis in one run, in countdown order (this fixes C2's "where are the last two"): eggs, tuna, milk, peas, tomatoes, bread, carrots, chickpeas, bananas, spaghetti, lentils, potatoes, popcorn, oats, rice, from sixty-five and a half cents down to eleven and a quarter.
2. Comment ask for data the viewer already has: "Tell me what a two-kilo bag of white rice costs at your store. Give me the store, the city and the date on the tag." This turns the regional pushback into participation.
3. Tease the next video in one sentence.
4. "The truth is not always on the menu." (Tagline use 2 of 2.) Then the sign-off.

---

## 6. Competitor claims that break our rules (do not reproduce or paraphrase)

| Claim (verbatim from transcript) | Source | Rule broken | Safe rebuild |
|---|---|---|---|
| "That's the cheapest protein in the building" / "cheapest complete proteins" / "Cheap protein, cheap fat" / "under 25 cents for real protein" | O1, O2, O3 (11 uses of "protein" in total) | Banned word; nutrition | Cost per label serving only. |
| "Cheapest filling food in the store" / "Oats stick with you. They fill you up slow" / "holds you until lunch" | O1, O2, O3 | Banned word "filling"; implied nutrition | Omit. Give servings per pack. |
| "keeps for weeks in a cool, dark spot" / "keeps in the refrigerator for a month or more" / "a whole carrot keeps a month" / "Butter... keeps for months in the freezer" / peanut butter "keeps forever" / white rice "lasts for years" / pasta "holds in the pantry for years" | O1, O2, O3 | Claims about keeping | Omit all storage durations. |
| "Eggs keep far longer... That date is a sell-by... Floats, it goes out" (float test) | O2 | Food safety; also wrong for Canada (best before, not sell-by) | Omit. |
| "red kidney beans... will make you good and sick if they only get half cooked... 10 minutes at a real boil" | O2 | Food safety | Omit. If kidney beans are swapped in at #8, use canned and say nothing about cooking. |
| "Cut the sprouts off and in the pot they go" / "Cut the sprouts and they go straight into the soup pot" | O2, O3 (the top comment on O3 corrects it) | Food safety | Omit. |
| "Potatoes and onions sitting together spoil each other faster" / the fridge "turns them strange and sweet" | O2, O3 | Keeping and quality | Omit. |
| "Brown rice is a bit better for you... goes rancid on the shelf inside a year" | O2 | Health and keeping | Omit. C2's "The bran layer on brown rice carries oil" is also out. |
| "Frozen vegetables... often fresher than the fresh ones" | O1 | Quality as fact | Omit. Give the price only. |
| "Make your own, it takes 20 minutes and it's better" / shredded cheese "doesn't melt as nice" / "tastes like somebody's grandmother made it" | O1, O2 | Taste and quality as fact | Omit. |
| "That's not a scam, exactly" | O3 | Banned word | Omit. |
| "The money is entirely in you not knowing and in you being tired on a Tuesday, which they are counting on" / "your tiredness on a shelf at eye level" / "the companies noticed that we stopped noticing" | O1, O2, C1 | Implies intent or wrongdoing | State prices; ascribe no motive. |
| "Recent pricing... whole bird close to $2 a pound... ground beef pushing close to $7 a pound" / "eggs to drop by roughly 30%" / "a dozen sitting around $2" / "$180", "$70 to $90", "$25-30" | O1, O2, O3 (O3's description says U.S. data) | U.S. figures presented as general | Use only the Canadian, store-dated prices from u1_prices.md. |
| "germ... the single most nutritious part... healthy oils, vitamin E" / yogurt sugar "your doctor vaguely told you to eat more of" | C1 | Nutrition and health | Out of scope. |
| "almost everything here is safe to eat" / "there is nothing unsafe in the bottle" / tap water "tested constantly" | C1 | Food-safety claims (even reassuring ones) | Omit. |
| "trick" ×9, "hidden", "quietly" ×3, "caught" ×3 (fish "caught in Canadian waters") | C1 | Banned words (the fishing sense counts too) | Use "landed" or "fished" if ever needed. |
| "quietly cheap" / "quietly picked up" / "sitting on something hidden" | C2 | Banned words | Omit. |
| "everything here is a food that, by Canada's own rules, doesn't need a date on it" (the 90-day best-before filter) / "Whole peppercorns hold their character for years" | C2 | Durability and keeping claims | Do not reuse as a yardstick; the yardstick is cost per label serving. |
| "per kilogram it is the cheapest protein staple" (peanut butter) | C2 | Banned word | "$0.45 to $0.65 per 100 g", with the store and date. |
| "Product of Canada means... roughly 98% are Canadian" (paraphrased, no attribution) | C1 | The phrase may only be quoted as exact label wording with the CFIA definition attributed | Do not use. The "Prepared in Canada" badges in the API data are website badges, not label text. |
| "I raised a family on these seven" / "feeding seven people on one income" | O1, O2 | Not a rule breach for them; a fabrication risk for us | CC must not invent persona biography. Rule 18's generic first-person scene only. |

---

## 7. Production notes for retention
- Show an on-screen number card the moment "Number X" is spoken, with the per-serving figure as a large lower-third (for example, "#15 · 65.5¢ / serving"). This prevents the C2 numbering confusion.
- Add YouTube chapters for all 15 items. The C2 audience built its own timestamps.
- B-roll must match the spoken number. Comments punished the "rising graph while saying falling" mismatch in C2. Avoid U.S. stock footage (pounds, dollar signs on U.S. tags, Walmart US). Show nofrills.ca listing screenshots dated 7 or 8 Oct for each item.
- At CC's measured pace the 22,315-character body runs about 22-23 minutes. If the editor wants about 17 minutes, the pace has to rise to about 22 characters per second, or the body moves to the 21,000-character floor. That gives about 21:50 at 16 characters per second, still well over 17 minutes.

---

## 8. SOURCE REGISTER

| # | Source | URL / location | Accessed (UTC) | Tier |
|---|---|---|---|---|
| R1 | Tried & True, "You Only Need These 20 Groceries Every Week (Stop Buying the Rest)": transcript (Algrow fetch_transcript), details (NexLev youtube_video_details), top comments (NexLev youtube_video_comments) | https://www.youtube.com/watch?v=69p6tHh7qag ; transcript saved `scratchpad/rt/69p6tHh7qag.txt` | transcript ~02:06; views and comments 2026-10-07 ~02:08 | a (what the video says and its view count); its factual claims are c (do not use) |
| R2 | Tried & True, "Buy These 7 Groceries When Money's Tight" | https://www.youtube.com/watch?v=9T6dDqRI2wQ ; `rt/9T6dDqRI2wQ.txt` | ~02:06 / ~02:08 | a for structure and views; c for claims |
| R3 | Money Culture America, "The 7 Cheapest Foods That Feed a Family (Real 2026 Prices)" | https://www.youtube.com/watch?v=5UCblxPUtog ; `rt/5UCblxPUtog.txt` | ~02:06 / ~02:08 | a for structure and views; c for claims (U.S. data) |
| R4 | Canadian Counter, "10 Fake Foods Canadians Are Buying Every Single Week (Check Your Kitchen)" | https://www.youtube.com/watch?v=1NaLMzSsY8Q ; `rt/1NaLMzSsY8Q.txt` | ~02:06 / ~02:08 | a |
| R5 | Canadian Counter, "15 CANADIAN Foods You'll Regret Not Stocking Up On Before 2026 Ends" | https://www.youtube.com/watch?v=Ri3vsAcrVoc ; `rt/Ri3vsAcrVoc.txt` | ~02:06 / ~02:08 | a |
| R6 | YouTube search results used to find the O1-O3 IDs (NexLev youtube_search) | queries: "You Only Need These 20 Groceries Tried & True", "Buy These 7 Groceries When Money's Tight", "\"The 7 Cheapest Foods That Feed a Family\"" | ~02:04-02:05 | a |
| R7 | Viewer comments (top sort, first page of 20 per video) | NexLev youtube_video_comments on the five IDs above | ~02:08 | d (anecdotal survey of viewer sentiment; not facts) |
| R8 | CC channel list with video IDs and views | `scratchpad/cc_live_oct7.json` (local capture, 7 Oct) | read ~02:03 | a |
| R9 | House rules and competitor rules | `/home/user/Food/script_rules_and_prompt.md` | read ~02:02 | n/a (internal) |
| R10 | Prices, servings, second-city check and StatCan July averages | `scratchpad/u1_prices.md` (sibling dossier; its own register lists PC Express API captures 01:55-02:01 UTC and StatCan 18-10-0245-01) | read ~02:15 | a (as recorded there; inherits its UNVERIFIED list) |
| R11 | StatCan 18-10-0245-01 latestN download | https://www150.statcan.gc.ca/t1/tbl1/en/dtl!downloadDbLoadingData-nonTraduit.action?pid=1810024501&latestN=5&startDate=&endDate=&csvLocale=en&selectedMembers= | 2026-10-07 02:11:59 | a; returned "Failed to open stream for the full cube download" (no data) |
| R12 | StatCan full-table zip (HEAD request) | https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip | 2026-10-07 ~02:12 | a; Last-Modified Wed, 02 Sep 2026 12:31:36 GMT, so **August 2026 is not out; July 2026 is the latest month** (agrees with the u1_prices check at 02:01) |
| R13 | NexLev connected channels | list_my_youtube_channels returned only "Flip Choose" (UC_Wg7NQGrR73F8YnLw6VZ6g) | ~02:14 | a; no CC retention data is available |
| — | Algrow youtube_search | returned 0 results for every query | ~02:04 | not used |

---

## 9. UNVERIFIED / DO-NOT-USE

- **Real audience-retention curves:** none pulled. NexLev is connected to "Flip Choose", not Canadian Counter. Every drop-off or retention inference here is structural, not measured. Do not tell anyone "viewers drop at X".
- **Timestamps in section 1 and 2:** estimated from character position. The auto-caption transcripts have no time codes. The 2:17 for C2's first item agrees with a viewer's timestamp comment (2:21), but the others are estimates.
- **Auto-caption errors:** the transcripts may misspell names (C2 renders Goderich as "Godrich" in a comment, for example). Do not quote competitor lines as exact speech without checking the video.
- **"Same owner" for No Frills #7952 and Loblaws #1000:** u1_prices.md says "Both stores are owned by Loblaw Companies Limited". No Frills stores are commonly run by franchisees (the store's own name is "Bo's NO FRILLS"). **Do not say "same owner" or "same company".** Say "both are Loblaw banners", and confirm even that wording against Loblaw's own site before use.
- **"About a kilometre and a half"** between 261 Richmond St W and 585 Queen St W is the sibling dossier's approximation and has not been measured. Measure it on a map before use, or say "a short walk away".
- **"Eight" packaged staples at the same price in three cities:** only six are same-day regular prices (rice, spaghetti, chickpeas, diced tomatoes, frozen peas, red lentils). Oats and tuna in Vancouver and Calgary are forward-dated 8 Oct API prices. Use "six" unless the 8 Oct re-capture confirms all eight.
- **Every number in the hook, loop, twist and #1 payoff** (11.25 cents, $1.49 gap, 65.5 cents, under 19 cents for the final six) depends on the 8 Oct re-capture. If rice is displaced from #1, or potatoes (#4) change, rewrite the hook, the hinge sentence and the payoff.
- **Eggs "105 g = 2 large eggs":** this is an inference (see u1_prices.md section 8). The 65.5 cents per serving depends on it. If it is unconfirmed, say "the label serving of 105 grams" and give the per-egg figure (32.75 cents), which needs no inference.
- **Potatoes at $5.99 regular:** forward-dated API price, not a shelf observation. It is the most volatile item.
- **No Name peanut butter at $4.50:** forward-dated. Use the Kraft $6.50 regular price in the "what we threw out" segment.
- **Clover Leaf per-serving figure:** its serving size was not fetched. Say only "$1.99 for the same 170 g size".
- **Supplier or manufacturer of any No Name, PC, PC Blue Menu or Farmer's Market product:** never infer.
- **"Prepared in Canada" / "Product of Canada":** the API shows website badges, not label text. Do not use either phrase.
- **The sponsorship statement in the disclosure:** the channel owner must confirm it is true.
- **Chicken or other meat per-serving prices:** not researched. Expect comments asking about them. Make no claim.
- **Every factual claim in the competitor videos** (U.S. prices, the "40,000 items" store count, margin claims, government outlook figures, all keeping, safety and nutrition statements): tier c. Do not use.
- **Viewer comments:** tier d. Use them only to anticipate questions, never as facts. Health and safety claims in comments (potato sprouts, glyphosate, microplastics) must not be repeated.

---

## GAP FIXES (critic), 7 Oct 2026, 02:19–02:26 UTC (full report: `scratchpad/u1_gaps.md`)

1. **H1 and the 5.9 payoff: distance is wrong.**
   - The store coordinates in the retailer's pickup records put #7952 (261 Richmond St W) and Loblaws #1000 (585 Queen St W) **0.84 km apart** in a straight line.
   - Replace "about a kilometre and a half away" with "**less than a kilometre away**". This also resolves the UNVERIFIED item.
2. **H1: "on a Toronto shelf" is wrong.** These are website listings. Use "listed for a Toronto store, this week".
3. **5.5 twist: the "six" list is inconsistent.** Peas were on sale on 7 Oct in all three cities, just as tuna was, so counting one and not the other doesn't hold.
   - Safe draft: "Five of the packaged staples had the same regular price in all three cities, to the cent."
   - The five are rice, spaghetti, chickpeas, diced tomatoes and red lentils.
   - "Seven" is acceptable only if the script says the frozen peas and tuna figures are the regular price shown alongside a sale that ended on the seventh.
4. **"Both are Loblaw banners" is now sourced:** Loblaw Companies Limited, CNW release, 16 Sep 2010, "nofrills(R) banner stores".
5. **#3 popping corn beat (4.4).**
   - Replace "Say 'fifty grams of kernels, unpopped'" with "**the label serving of fifty grams**". The record does not say "unpopped".
   - New comparison beat: Orville 850 g lists a **63 g** serving, so compare per 100 g ($0.705 against $0.25).
   - The bridge line "the name brand costs a dollar more per bag" (into #2) is true: Quaker Large Flake is $4.00 against $3.00. Quaker comes to $0.16 per 40 g serving.
6. **#14 tuna:** Clover Leaf's 55 g serving is now confirmed, so "$0.64 a serving against $0.42" may be said.
7. **Hinge sentence check:** "every one under nineteen cents" holds (spaghetti $0.1889). It breaks only if a re-capture lifts spaghetti above $2.01.
8. **Title:** keep it verbatim; it is literally true (see `u1_gaps.md` section 5). Never say "label serving" for bananas, carrots or potatoes.


======================================================================

# U1 GAPS: completeness critic for "15 Foods That Still Cost Under $1 a Serving in Canada (October 2026 Prices)"

Critic pass run 7 October 2026, 02:19 to 02:26 UTC. Upload is 8 October 2026 at 20:00 UTC.
Inputs read in full: `u1_prices.md`, `u1_statcan.md`, `u1_facts.md`, `u1_retention.md`, `/home/user/Food/script_rules_and_prompt.md`.
Every number below was recomputed from the raw PC Express JSON, not copied from the dossiers. The recalculation log is `scratchpad/u1critic/recalc.txt` and the extractor is `scratchpad/u1critic/ext.py`.

## VERDICT

**PASS WITH FIXES.**
- All 15 picks are under $1 per serving at the regular price, and the countdown order from #15 to #1 is correct.
- 14 of the 15 had a StatCan line or a fact. **#3 popping corn had neither.** That gap is now filled with a primary, non-health fact (section 3).
- Nine other defects were found and fixed or fenced off (section 4).
- **Recommended title: keep it word for word.** It is literally true on the evidence (section 5).

---

## 1. Under $1 at REGULAR price: recomputed from raw JSON

Source files:
- No Frills #7952, 261 Richmond St W, Toronto: `u1/nofrills_7952/p/*.json` (captured with date `07102026`, 01:56–01:57 UTC) and `u1/nofrills_7952/p_date08102026/*.json`.
- The regular price is the one returned as type `REGULAR`. Where the item was on sale on 7 October, it is the `wasPrice`, or the 8 October forward-dated regular price when there is no `wasPrice`.

| # | Item (code) | Raw price on 7 Oct (type) | Regular used | Pack ÷ serving (serving from `servingSizeEN`) | Servings | Critic $/serving | Dossier | Match |
|---|---|---|---|---|---|---|---|---|
| 15 | No Name Large Eggs 12 (20812144001_EA) | 3.93 REGULAR | 3.93 | 12 eggs ÷ 2 (105 g; the "2 eggs" is inferred) | 6 | **0.6550** | 0.655 | yes |
| 14 | No Name Flaked Light Tuna 170 g (20521648_EA) | 1.00 SPECIAL, was 1.29, ends 10-07 | 1.29 (was; Oct 8 REGULAR) | 170 ÷ 55 g | 3.091 | **0.4174** | 0.417 | yes |
| 13 | Neilson 2% Milk 4 L (20188873_EA) | 6.44 REGULAR | 6.44 | 4000 ÷ 250 ml | 16 | **0.4025** | 0.403 | yes |
| 12 | No Name Green Peas 750 g (20312260_EA) | 2.77 SPECIAL, was 3.00 | 3.00 (was; Oct 8 REGULAR) | 750 ÷ 85 g | 8.824 | **0.3400** | 0.340 | yes |
| 11 | No Name Diced Tomatoes 796 ml (20600787_EA) | 2.00 REGULAR | 2.00 | 796 ÷ 129 ml | 6.171 | **0.3241** | 0.324 | yes |
| 10 | No Name Original Bread 675 g (21509822_EA) | 2.48 REGULAR | 2.48 | 675 ÷ 75 g | 9 | **0.2756** | 0.276 | yes |
| 9 | Farmer's Market Carrots 3 lb, 1.362 kg (20600927001_EA) | 3.49 REGULAR | 3.49 | 1362 ÷ 100 g (retailer-listed) | 13.62 | **0.2562** | 0.256 | yes |
| 8 | No Name Chickpeas 540 ml (20325921001_EA) | 1.50 REGULAR | 1.50 | 540 ÷ 86 ml | 6.279 | **0.2389** | 0.239 | yes |
| 7 | Bananas (20175355001_KG) | $1.52/kg REGULAR (comparisonPrice; $1.75 for a 1.15 kg average bunch) | 1.52/kg | 1000 ÷ 140 g (retailer-listed) | 7.143 | **0.2128** | 0.213 | yes |
| 6 | No Name Spaghetti 900 g (20315613002_EA) | 2.00 REGULAR | 2.00 | 900 ÷ 85 g | 10.588 | **0.1889** | 0.189 | yes |
| 5 | PC Blue Menu Red Split Lentils 900 g (20629496_EA) | 3.79 REGULAR | 3.79 | 900 ÷ 35 g | 25.714 | **0.1474** | 0.147 | yes |
| 4 | Farmer's Market White Potatoes 10 lb, 4.54 kg (20600997001_EA) | 1.99 SPECIAL, no was, ends 10-07 | **5.99 (Oct 8 REGULAR, forward-dated)** | 4540 ÷ 100 g (retailer-listed) | 45.4 | **0.1319** | 0.132 | yes |
| 3 | No Name Popping Corn 1 kg (21291313_EA) | 2.50 REGULAR | 2.50 | 1000 ÷ 50 g | 20 | **0.1250** | 0.125 | yes |
| 2 | No Name Large Flake Oats 1 kg (20923994_EA) | 3.00 SPECIAL, no was | 3.00 (Oct 8 REGULAR) | 1000 ÷ 40 g | 25 | **0.1200** | 0.120 | yes |
| 1 | No Name Long Grain White Rice 2 kg (20069589_EA) | 5.00 REGULAR | 5.00 | 2000 ÷ 45 g | 44.444 | **0.1125** | 0.1125 | yes |

**Result: 15 of 15 are under $1 at the regular price.**
- The highest is eggs at $0.655.
- In the second-city files the highest is eggs at $0.710 (Vancouver #3403, $4.26) and $0.705 (Calgary #3155, $4.23).
- At Loblaws #1000 Queen St the highest is eggs at $0.655, then tuna at $0.647 ($2.00).
- The eggs pass even under the worst serving reading: at 3 eggs per serving the dozen works out to $0.9825.
- No item depends on a sale price to pass.

Second-city and Loblaws figures were spot-checked against `u1/nofrills_3403`, `u1/nofrills_3155` and `u1/loblaw_1000`. They all match `u1_prices.md` section 3, including the banana per-kg figures ($1.98 ÷ 1.15 = $1.72 and $2.21 ÷ 1.15 = $1.92) and the 520 g western loaf at $2.50 with a 58 g serving ($0.279).

## 2. Ranking order: correct, with three sensitivities

Sorted by recomputed regular cost per serving, the order is exactly #15 → #1. There are no ties inside the 15. Cabbage, an alternate at $0.276, ties bread to the tenth of a cent, but it is not in the list.

Sensitivities the script writer must respect:
1. **Potatoes (#4).** The $5.99 is a forward-dated API price, not a shelf observation.
   - Break-even against lentils is **$6.69**. If the 8 October regular price is $6.70 or more, potatoes and lentils swap places at #4 and #5.
   - At the yellow-bag price of $6.99, potatoes come to $0.154.
2. **Carrots (#9), serving basis.** The ranking uses the retailer-listed 100 g.
   - If anyone switches to a Health Canada reference amount (85 g in one automated read, 125 g in another; neither verified), carrots come to $0.2178 at 85 g and move to #8, between chickpeas and bananas.
   - **Use 100 g, retailer-listed, consistently.** Do not mix the two bases.
3. **Eggs (#15), the "2 eggs" inference.** At 1 egg per serving ($0.3275) eggs would drop to about #11, and the countdown changes.
   - The Health Canada table (automated read, unverified) says the egg serving is the "number of eggs closest in weight in grams" to 100 g, which supports 2 large eggs.
   - It is still not printed in the No Frills record. Say "the label serving of 105 grams, which works out to six servings a dozen".

## 3. Coverage: StatCan line or fact for each item

| # | Item | StatCan 18-10-0245-01 line (Canada, July 2026; re-verified against the CSV) | Fact (dossier section) | Status |
|---|---|---|---|---|
| 15 | Eggs | Eggs, 1 dozen $4.95 (v1353834290) | facts 3.10 (CFIA/BC Egg grade ≠ origin; EFC producer price) | OK |
| 14 | Tuna | Canned tuna 170 g $1.84 (v1353834282) | facts 3.18 (CFIA: "light" is flesh colour) | OK |
| 13 | Milk | Milk 4 L $6.99 (v1353834285) | facts 3.11 (CDC: only the farm price is regulated; +2.3255%) | OK |
| 12 | Frozen peas | Frozen peas 750 g $3.83 (v1353834325) | facts 3.14 ("Canada A" is a grade) | OK |
| 11 | Diced tomatoes | Canned tomatoes 796 ml $2.27 (v1353834341) | facts 3.16 (Ontario 98.2% of field tomatoes) | OK |
| 10 | Bread | White bread 675 g $3.60 (v1353834326; verified by the critic) | facts 3.7 (wheat crop) | OK |
| 9 | Carrots | Carrots 1.36 kg $4.75 (v1353834303) | facts 3.15 (Ontario and Quebec about 79%) | OK |
| 8 | Chickpeas | Canned beans and lentils 540 ml $1.72 (v1353834343) | facts 3.4 (2025 crop, +67.9%) | OK |
| 7 | Bananas | Bananas $1.88/kg (v1353834294); cheapest of 25 per-kg products (critic re-verified: cabbage $2.90, oranges $4.48, sweet potatoes $4.83 next) | facts 3.17 (imports by country, 2023) | OK |
| 6 | Spaghetti | Dry or fresh pasta 500 g $3.45 (v1353834327) | facts 3.6 (durum) | OK |
| 5 | Red lentils | Dried lentils 900 g $3.63 (v1353834344) | facts 3.1 (SK 86.1% of the 2025 crop) | OK |
| 4 | Potatoes | Potatoes 4.54 kg $5.32 (v1353834300) | facts 3.13 (Alberta largest by weight) | OK |
| **3** | **Popping corn** | **none (StatCan does not track popcorn or oats)** | **none** | **GAP → FIXED (below)** |
| 2 | Oats | none (not tracked) | facts 3.5 (StatCan oat crop; SK share) | OK (fact only) |
| 1 | Rice | White rice 2 kg $9.62 (v1458869937) | none (U7: no primary source on rice origin) | OK (StatCan only) |

**Gap fix for #3, popping corn (primary, non-health).**
- **Fact P1: different brands list different label servings for the same food at the same store.** The No Frills product records were re-fetched at 02:21 UTC on 7 Oct (PC Express API, store #7952, `c3live/p/`).
  - No Name Popping Corn 1 kg (21291313_EA): label serving **50 g**, $2.50 REGULAR, so 20 servings at **$0.125** each, or $0.25 per 100 g.
  - Orville Original Gourmet Popping Corn Kernels 850 g (20308686_EA): label serving **63 g**, $5.99 REGULAR, so 13.49 servings at **$0.444** each, or **$0.705 per 100 g**.
  - The script line: "Even the serving size isn't the same from brand to brand. No Name lists fifty grams, Orville lists sixty-three. So compare these two per hundred grams: twenty-five cents against just over seventy."
  - This is a price and label fact. It needs no StatCan line.
- **Fact P2: price across cities, from the same No Frills data.** No Name Popping Corn 1 kg was $2.50 in Toronto (#7952) and **$3.00** at both No Frills #3403 Vancouver and #3155 Calgary (both REGULAR on 7 Oct), which is $0.15 per serving. It was $3.49 at Loblaws #1000 Toronto.
  - This is the only packaged No Name pick that cost more out West.
- **Fact P3 (an internal flag, not for air):** the No Name Popping Corn record's `ingredients` field reads "Carrots*, Water, Potatoes*, Chicken*, Apples*, Celery*, Peas*, Barley Flour*. *organic." This is plainly another product's ingredient list. It was the same on the 02:21 UTC re-fetch.
  - Do not quote the listing's ingredients.
  - Treat the record's other fields with mild caution. The 50 g serving and 180-calorie figures are internally consistent with the Orville record's ratio.
  - Do not mention calories on air.
  - Do not present the mismatch as a retailer error on air; it is a listing data issue only.
- "Unpopped" is not stated in the No Name record. Say "the label serving of fifty grams", not "fifty grams of unpopped kernels".
- The Health Canada table read by WebFetch at about 02:23 UTC gives "S.1 – Chips, pretzels, popcorn" a 50 g reference amount. That is an automated summary, so it is UNVERIFIED and not for air.

Are the facts non-health and sourced? Every fact used for the 15 in `u1_facts.md` is tier a or tier b with a URL and access time, and none is a health, nutrition, keeping or safety claim. The grep for banned words across the three content dossiers found them only in the dossiers' own do-not-use lists. Two fact lines do need correcting (D3 and D4 below).

## 4. Defects found (beyond the popping corn gap), with fixes

| ID | Dossier | Defect | Fix |
|---|---|---|---|
| D1 | retention 5.1 (H1), 5.9; prices 3 | "**about a kilometre and a half**" between #7952 and Loblaws #1000 is wrong. The retailer's own store coordinates (`loc.json` 43.648854, -79.391514; `u1/locations/loblaw.json` 43.647355, -79.401696) give **0.84 km in a straight line**. | Say "**less than a kilometre away**" or "a short walk away". Never say "a kilometre and a half". |
| D2 | retention 5.5, UNVERIFIED | The "six packaged staples the same price in three cities" list is internally inconsistent. Frozen peas were on sale on 7 Oct in all three cities (SPECIAL $2.77, was $3.00), on exactly the same footing as tuna (SPECIAL $1.00, was $1.29), yet peas were counted and tuna excluded. | Same-day REGULAR-type prices identical in Toronto, Vancouver and Calgary: **five** (rice $5.00, spaghetti $2.00, chickpeas $1.50, diced tomatoes $2.00, red lentils $3.79). Add peas ($3.00) and tuna ($1.29) on the 7 Oct "was" price, also confirmed by the 8 Oct regular reads in all three cities, and the count is **seven**. Oats make **eight** only on forward-dated reads. **Say "five", or "seven" with the was-price basis stated.** |
| D3 | facts 1.3 script line | "For those we used Health Canada's reference amount" is **false**. The ranking uses the **retailer-listed** 100 g for carrots and potatoes, and 140 g for bananas. Two automated reads of the Health Canada table disagreed on vegetables (85 g, then 125 g). | Script line: "Fresh produce doesn't have to carry a Nutrition Facts table, so for bananas, carrots and potatoes we used the serving the No Frills website lists." Never call those three a "label serving". |
| D4 | facts 1.2 | "The brand does not pick the serving size freely" overstates uniformity. Orville popping corn lists 63 g and No Name lists 50 g for the same food. | Rewrite: "The serving has to follow Health Canada's labelling rules, but it isn't identical from brand to brand." For brand pairs, compare per 100 g. |
| D5 | facts 4 (ready lines) | "Across every No Frills listing… the only Canada badge… is 'Prepared in Canada'. Not one says 'Product of Canada'" quotes the phrases from a **website badge**. House rules allow them only as exact **label** wording with CFIA attributed, and the retention dossier bans both phrases. | **Drop this ready line** unless the packages are filmed. |
| D6 | prices 1 notes, 8 UNVERIFIED; retention 4.4 | Clover Leaf per-serving figure "not checked". | **Resolved**: the Clover Leaf Flaked Light Tuna Skip Jack in Water 170 g (20573583_EA) detail record, 02:21 UTC, shows a **55 g** serving at $1.99 REGULAR, so **$0.644 per serving**. This can be aired as "$0.64 a serving against $0.42 for No Name". |
| D7 | prices 1 | Brand-pair per-serving figures were not computed. | Detail records fetched at 02:21 UTC: Quaker Large Flake 1 kg (20323113002_EA) 40 g serving, $4.00, **$0.160**; Barilla Spaghetti 410 g (21404912_EA) 85 g serving, $2.50, **$0.518**; Orville 850 g 63 g serving, **$0.444** (see D4: compare per 100 g). |
| D8 | prices 3 | "Both stores are owned by Loblaw Companies Limited" (retention already flags this). The pickup records list store owner names (No Frills #7952 is "Bo's NO FRILLS"; Loblaws #1000 lists a named ownerName). | Use "both are Loblaw banners". Supported by Loblaw Companies Limited's own release (CNW, 16 Sep 2010): "five nofrills(R) banner stores". Never say "same owner". |
| D9 | retention 5.1 H1 | "At the regular price, **on a Toronto shelf**" is a capture-method error. These are website listings, not shelf observations. | "At the regular price, listed for a Toronto store, this week." |
| D10 | statcan 1 | Re-check requested. | Done at 02:22 UTC on 7 Oct: WDS `cubeEndDate` 2026-07-01, `releaseTime` 2026-09-02T08:30; zip Last-Modified 02 Sep 2026; the latestN link still returns "Failed to open stream…"; getChangedCubeList for 2026-10-07 returns "future release date". **August 2026 is NOT out.** Every average stays "July 2026". |

## 5. Title recommendation

**Keep: "15 Foods That Still Cost Under $1 a Serving in Canada (October 2026 Prices)".** Thumbnail "STILL UNDER $1" is also fine.

Literal-truth test:
- **"15"**: the script counts exactly 15.
- **"Under $1 a Serving"**: true for all 15 at regular prices. The maximum is $0.655 in Toronto and $0.710 in Vancouver, and it stays true even if eggs were 3 per serving ($0.98). The title says "a serving", not "a label serving". That matters, because three items (bananas, carrots, potatoes) carry no Nutrition Facts table, so the script must call their serving "the serving the retailer lists".
- **"Still"**: supported. At the StatCan national average, every one of the 13 tracked items comes in under $1 per listed serving in July 2017, July 2021, July 2025 and July 2026 (u1_statcan 2b). Popcorn and oats are not tracked, so do not make a "since 2017" claim for those two.
- **"in Canada"**: the prices come from No Frills stores in three provinces (ON, BC, AB) plus one Loblaws, and all 15 were under $1 in all of them. Keep the spoken disclaimer "prices vary by location; check your shelf."
- **"(October 2026 Prices)"**: captured 7 Oct 2026, with a scheduled re-capture on 8 Oct.

Condition: the title stays true even if potatoes come back at $6.99 on 8 October; only the order changes (section 2, sensitivity 1). The single risk to "under $1" would be eggs at 4 or more per serving, which no reading supports.

Do NOT change it to "Cheapest Foods in Canada" or "per label serving". The first is not shown, and the second is false for the produce items.

## 6. Actions before lock (8 Oct)

1. Re-run the 8 Oct capture (`u1_prices.md` section 7 command) after 12:00 UTC.
   - Re-rank if potatoes are $6.70 or more.
   - Confirm the oats are $3.00, the tuna $1.29 and the peas $3.00 as REGULAR.
2. Re-check StatCan `getCubeMetadata`. If `cubeEndDate` = 2026-08-01, replace the July lines.
3. Apply D1, D2, D3, D5 and D9 to the retention draft lines before the script is written.

---

## SOURCE REGISTER (critic pass)

| # | Source | URL / location | Accessed (UTC, 2026-10-07) | Tier |
|---|---|---|---|---|
| G1 | PC Express product detail, No Frills #7952 (raw, 7 Oct and forward 8 Oct), used for recalculation | `scratchpad/u1/nofrills_7952/p/`, `p_date08102026/` (api.pcexpress.ca/pcx-bff/api/v1/products/{code}) | files captured 01:56–01:58; read 02:19 | a |
| G2 | Same for #3403 Vancouver, #3155 Calgary, Loblaws #1000 | `scratchpad/u1/nofrills_3403/`, `nofrills_3155/`, `loblaw_1000/` | read 02:20 | a |
| G3 | PC Express product detail re-fetch: 21291313_EA, 20308686_EA, 20573583_EA, 20323113002_EA, 21404912_EA (store 7952, date 07102026) | https://api.pcexpress.ca/pcx-bff/api/v1/products/{code}?lang=en&date=07102026&pickupType=STORE&storeId=7952&banner=nofrills → `scratchpad/c3live/p/` | 02:21:26–02:21:28 | a |
| G4 | PC Express search, No Frills #7952: popcorn kernels (Orville 850 g $5.99 REGULAR), tuna, oats, spaghetti | `scratchpad/u1/nofrills_7952/search/*.json` | captured 01:55–01:56; read 02:21 | a |
| G5 | PC Express pickup-location records (store coordinates and names) | `scratchpad/loc.json`; `scratchpad/u1/locations/loblaw.json` | read 02:25 | a |
| G6 | StatCan table 18-10-0245-01 CSV (July 2026 values re-verified, including white bread v1353834326 and the per-kg ranking) | `scratchpad/u1/statcan_dl/18100245.csv` (from https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip) | read 02:21 | a |
| G7 | StatCan WDS getCubeMetadata pid 18100245; getChangedCubeList/2026-10-07; zip HEAD | https://www150.statcan.gc.ca/t1/wds/rest/getCubeMetadata ; …/getChangedCubeList/2026-10-07 ; https://www150.statcan.gc.ca/n1/tbl/csv/18100245-eng.zip | 02:22 | a |
| G8 | StatCan latestN download link from the brief | https://www150.statcan.gc.ca/t1/tbl1/en/dtl!downloadDbLoadingData-nonTraduit.action?pid=1810024501&latestN=5&startDate=&endDate=&csvLocale=en&selectedMembers= | 02:22 | c (returned an error string, no data) |
| G9 | Health Canada, Nutrition labelling – Table of reference amounts for food (published 18 Oct 2024) | https://www.canada.ca/en/health-canada/services/technical-documents-labelling-requirements/table-reference-amounts-food/nutrition-labelling.html | ~02:23 (curl: empty reply; WebFetch summary only) | c for air until read verbatim (two automated reads disagree) |
| G10 | Conagra Brands Inc., Form 10-K for fiscal year ended 31 May 2026 (filed 2026-07-15), SEC EDGAR | https://www.sec.gov/Archives/edgar/data/23217/000110465926083905/tmb-20260531x10k.htm | 02:22 | a (used only to establish that Orville is NOT named in it; see the do-not-use list) |
| G11 | Loblaw Companies Limited, "Multiple No Frills(R) opened in Atlantic Canada", CNW, 16 Sep 2010 | https://www.newswire.ca/news-releases/multiple-no-frillsr-opened-in-atlantic-canada-545491682.html | 02:24 | a (company's own release; dated 2010) |
| G12 | ConAgra Foods, "Orville Redenbacher's new line of popcorn…", CNW, 17 Jun 2010 | https://www.newswire.ca/news-releases/orville-redenbachers-new-line-of-popcorn-makes-snack-time-spicy-544225922.html | 02:22 | c (2010 marketing; contains house-banned health wording; do not use) |
| G13 | Web search snippets (Wikipedia on Orville, potatopro, strategyonline, blogto, delimarketnews and others) | various | 02:22–02:24 | c (not opened or not primary; do not use) |
| G14 | conagrabrands.com / conagrabrands.ca / orville.com / loblaw.ca pages | various | 02:22–02:24 | n/a (HTTP 403/404 or TLS failure; nothing read) |

## UNVERIFIED / DO-NOT-USE

1. **Orville Redenbacher's ownership.** Not confirmed by any primary source opened. Conagra's FY2026 10-K does not name Orville at all, and the brand pages returned 403 or 404. Wikipedia and the 2010 CNW release are not usable. **Do not air any ownership line for Orville.**
2. **"Canada's most popular popcorn brand."** A 2010 company marketing claim, tier c. Do not use.
3. **Health Canada reference amounts (popcorn 50 g, vegetables 85 g or 125 g, potatoes 110 g, eggs "closest in weight").** These come from automated summaries that disagree with each other. Do not quote them until read verbatim on screen.
4. **"Unpopped" for the No Name 50 g serving.** Not stated in the record. Say "the label serving of fifty grams".
5. **No Name Popping Corn listing ingredients.** The field shows an unrelated product's ingredient list. Do not quote it, and do not air the mismatch.
6. **Calories or any nutrient value from any record.** Banned by house rules. They were used here only to check internal consistency.
7. **"A kilometre and a half"** between the Toronto stores. Wrong: it is 0.84 km straight-line. Use "less than a kilometre".
8. **"Six the same in three cities."** Use "five" (same-day regular) or "seven" (with the was-price basis stated); see D2.
9. **"Both stores owned by Loblaw Companies Limited" / "same owner."** Do not use. "Loblaw banners" only.
10. **Potatoes $5.99, oats $3.00, and the western oats, tuna and peas regular prices** where they rest on forward-dated reads. These are scheduled prices; confirm them on 8 Oct.
11. **Eggs "2 eggs per serving."** Still an inference. Say "105 grams, six servings a dozen", or give the per-egg price.
12. **Any "since 2017" or "still" history claim for popcorn or oats.** StatCan does not track either.
13. **"Prepared in Canada" / "Product of Canada" ready line** (facts section 4). Website badge only; drop it.
