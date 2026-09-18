# VERIFICATION LOG — TIM HORTONS

Script: `script_timhortons.md` (22,775 chars) · Research: `research_timhortons.md` (219KB, three parts)
Reference structure: Protect Our Plates, "Domino's Just Got Caught" (5FZEGj7Sa6A). Transcript read 100%.
Research date: 18 September 2026. Compiled 18 September 2026.

Tiers: **(a)** CONFIRMED primary · **(b)** STRONGLY SUPPORTED reputable named outlet · **(c)** SPECULATION, not used · **(d)** DOCUMENTED consumer/media record.

**Standing note on prices.** Every price in the script was captured on 18 September 2026 at 23:16 UTC from Restaurant Brands International's own production ordering API — the back end serving timhortons.ca and the app — per store, in cents, pre-tax. That makes them tier (a) as *the company's own first-party channel prices*. It does **not** make them verified menu-board prices. **Film the board.**

---

## PART A — CLAIM BY CLAIM

### Number nine — The Franchise Price Lottery

| # | Claim as spoken | Tier | Source |
|---|---|---|---|
| 1 | Large Original Blend, 18 Sept 2026, 6 cities same minute: Toronto $2.14 · Mississauga $1.97 · Halifax $2.15 · Calgary $2.14 · Winnipeg $2.14 · Vancouver $2.21 | a | RBI production menu API, `use1-prod-th-gateway.rbictg.com/graphql`, `storeMenu`, channel `whitelabel`. Store IDs 102601 / 107273 / 100476 / 104829 / 103950 / 103719 |
| 2 | Vancouver highest on every line checked | a | Same capture |
| 3 | Dozen donuts $14.49 Toronto vs $11.99 Mississauga | a | Same capture |
| 4 | Boston cream $1.79 vs $1.49 | a | Same capture |
| 5 | The two Ontario stores are ~25 km apart | b | Geography, 65 Queen St W Toronto to 1801 Courtney Park Dr Mississauga |
| 6 | **99.3% of TH restaurants are franchised; RBI operates 31** | a | RBI 2025 Form 10-K, Item 2 Properties table: 4,555 franchised + 31 company = 4,586. Arithmetic ours, exact |
| 7 | Franchisees set their own prices | a | Implied and confirmed by the six-city variance plus 10-K franchise structure |

⚠️ **Claim 6 is US+Canada combined.** RBI does not break out Canada. The script says "in Canada and the United States." Keep that wording.

### Number eight — The Delivery Price Book

| # | Claim | Tier | Source |
|---|---|---|---|
| 8 | Medium coffee $1.83 pickup → $2.29 delivery, +25.1% | a | Same API, same store 102601, same timestamp, `serviceMode` changed only |
| 9 | Large $2.14 → $2.59 | a | Same |
| 10 | Single donut $1.79 → $2.09 | a | Same |
| 11 | Dozen $14.49 → $17.39, +20% | a | Same |
| 12 | Mississauga is a flat +10% across the whole menu | a | Store 107273, same capture |
| 13 | Delivery fee is $3.99, separate and on top | a | Extracted verbatim from the live timhortons.ca JS bundle: `caDeliveryFeeAndTermsDisclosure: "$3.99 delivery fee. $9 minimum order..."` |
| 14 | The uplift is not Uber Eats / DoorDash / Skip | a | It is RBI's own first-party `whitelabel` channel. Aggregators were never queried (all returned HTTP 403) |
| 15 | App code contains "Menu prices higher on delivery. Terms and fees apply." | a | Verbatim from the shipped bundle, key `usDeliveryPriceDisclaimer` |
| 16 | That string is keyed to the US; the two `ca` strings disclose fee and minimum | a | Verbatim, both keys extracted |
| 17 | **The script refuses to assert Canada lacks the disclosure** | — | **CORRECT HANDLING. See Part C.1.** A disclosure may render elsewhere in the UI. The script says so out loud and commits to filming it. |

**This is the most original finding in the package and the most legally sensitive. The script's construction — state what was found, state what was not established, then film it — is not optional.**

### Number seven — The Cup That Changed Its Name

| # | Claim | Tier | Source |
|---|---|---|---|
| 18 | Jan 2012: new 24 oz XL added, every size renamed down one | b | CBC, Globe and Mail, Chatelaine, CSP Daily News, corroborated across four outlets |
| 19 | Old XL 20 oz → Large; old Large 14 oz → Medium; old Medium → Small; old Small → Extra Small | b | Same |
| 20 | **Volumes did not change** | b | Same. Script states this explicitly twice |
| 21 | Someone habitually ordering "large" went from 14 oz to 20 oz | b | Derived from the rename table |
| 22 | **CBC tested the cups and confirmed the stated sizes** | d | CBC BC, 2014. ⚠️ Article not retrievable (403). **Script uses it only to exonerate. If it cannot be re-sourced, cut the sentence — do NOT invert it.** |

⚠️ **The 2012 company statement on the rename ("guests receive the same amount of coffee for the same price, only the name of the size has changed") is tier (b) reconstructed from search summaries — CSP, CBC and Chatelaine all returned 403.** The script does **not** quote it verbatim for that reason. Keep it paraphrased unless re-sourced.

### Number six — The Seven-To-Twenty Switch

| # | Claim | Tier | Source |
|---|---|---|---|
| 23 | Tims Rewards launched 20 March 2019, visit-based, free item on the 7th visit | a | Tim Hortons corporate press release, newswire.ca |
| 24 | Launch was announced by full corporate press release | a | Same |
| 25 | 21 Feb 2023, 12:00:01 a.m. ET: moved to 10 points per dollar | b | CBC |
| 26 | Free coffee went 70 points → 400 points | b | CBC |
| 27 | ~$12 of spend → ~$40; ~7 visits → ~20 | b | CBC's own arithmetic, reproduced |
| 28 | **The 2023 change was posted as a notice at the bottom of the app and website; no press release** | b | CBC |

⚠️ The June 2022 and December 2022 interim changes are sourced only to loyalty-industry blogs. **They are NOT in the script.** Keep them out.

### Number five — The Always Fresh Question

| # | Claim | Tier | Source |
|---|---|---|---|
| 29 | **Late 2003, Maidstone Bakeries, Brantford, Ontario** | b | Globe and Mail, Marina Strauss, 14 May 2010 |
| 30 | 50/50 JV formed 2001 with Cuisine de France (IAWS Group, Ireland) | b | Globe and Mail, Tim Kiladze, 12 Aug 2010 |
| 31 | Donuts arrive par-baked and flash frozen, finished in store each morning | b | CBC's own description, 28 Feb 2012, quoted verbatim in the dossier |
| 32 | **Tim Hortons sold its 50% to Aryzta in Aug 2010 for $475M cash on ~$75M invested** | b | Globe and Mail, 12 Aug 2010 |
| 33 | "They have not owned the place that makes the donuts for sixteen years" | b | Derived from #32. **Script says "does not own that bakery" — correct. Do NOT name the current operator.** See Part C.2 |
| 34 | Franchisee class action reported at $2 billion | b | CBC, 28 Feb 2012. Use CBC's figure, not the $1.95B variant |
| 35 | **Dismissed on summary judgment 2012; upheld by ONCA; SCC refused leave 2013** | a | *Fairview Donut Inc. v. The TDL Group Corp.*, 2012 ONSC 1252; 2012 ONCA 867; [2013] S.C.C.A. No. 47 |
| 36 | Justice Strathy: a franchisor "must be permitted to introduce new products, new methods of production or sale, and new techniques" | a | 2012 ONSC 1252, quoted in CBC |
| 37 | Par-baking is legal and standard across the industry | — | Statement of general fact; the court ruling at #36 is the support |
| 38 | Nobody in ~5,350 competitor comments dated it correctly | d | Four competing videos mined; dates given ranged from "late 90s" to 2014 |

⚠️ **#35 is the single most important sentence in this segment.** The franchisees LOST at every level. Any cost-per-donut figure from that case is a failed allegation. The script states the dismissal in the same breath. **Never cut it.**

### Number four — The Landlord You Didn't Know You Had

| # | Claim | Tier | Source |
|---|---|---|---|
| 39 | 765 sites owned by RBI and leased to franchisees; 2,769 leased by RBI and subleased; 1,021 held directly by franchisees | a | RBI 2025 Form 10-K, Item 2 Properties, TH column, verbatim table |
| 40 | **3,534 of 4,555 = 77.6%** | a | Arithmetic ours, exact |
| 41 | Royalties "typically range from 3.0% to 6.0% of gross sales, based in part on whether we own or sublease the property" | a | 10-K, verbatim |
| 42 | Advertising fund contributions "range from 2.0% to 5.0% of gross sales" and are required | a | 10-K, verbatim |
| 43 | Rent "usually 8.5% to 10.0% of monthly gross sales" | a | 10-K, verbatim |
| 44 | Stacked range 13.5%–21% of gross sales | a (inputs) / **ours** (arithmetic) | Script presents it as a range, never a single figure. **Keep it that way** — RBI discloses ranges, not per-store terms |
| 45 | Supply chain sales $2,909M of TH total revenue $4,247M = 69% | a | RBI FY2025 results |
| 46 | Franchise and property revenues $995M = 23.4% | a | Same |

### Number three — The Quiet Quarter

| # | Claim | Tier | Source |
|---|---|---|---|
| 47 | TH Canada comparable sales Q2 2025 +3.6%; Q2 2026 +0.1% | a | RBI Q2 2026 press release filed with SEC, TH segment table |
| 48 | **The CEO's quote in that release names Burger King and International and does not mention Tim Hortons** | a | Verbatim quote reproduced in full in the dossier. **Show the release on screen** |
| 49 | Kobza: "our calendar didn't drive the growth we've come to expect from Tims" | b | Q2 2026 earnings call transcript, 13 Aug 2026. ⚠️ Third-party transcript. **Re-verify against RBI's own webcast** |
| 50 | TH Canada grew 2.8% across FY2025 | a | RBI FY2025 results |
| 51 | ~80 new Canadian restaurants in 2026 vs "over 50 last year"; ~400 renovations | b | Globe and Mail, 22 May 2026, plus earnings call |
| 52 | COO: "restaurant count has been fairly static since 2019, and the Canadian population has grown about 10 per cent since then" | b | Globe and Mail, 22 May 2026 |

### Number two — The Sixty-Four Cent Cup

| # | Claim | Tier | Source |
|---|---|---|---|
| 53 | Starbucks has been closing stores | b | Referenced in CBC, Oct 2025 |
| 54 | Second Cup's international division filed for CCAA creditor protection in May 2025 | b | Reported. ⚠️ **Do not state a Second Cup store count** — the company's own locator is reported inaccurate |
| 55 | 71% of Canadians drank a coffee yesterday; 80% noticed rising prices; >50% cutting back | b | Coffee Association of Canada, *Canadian Coffee Drinking Trends*, published 17 Feb 2026 |
| 56 | StatCan average price, 340g roasted/ground coffee, July 2026: **$9.54** | a | StatCan Table 18-10-0245-01, retrieved via Web Data Service 18 Sept 2026 |
| 57 | TH medium = 14 US fl oz = 414 mL | b | Post-2012 size table |
| 58 | ~23 g grounds at standard strength → **64 cents**; ~15 mediums per bag | a (inputs) / **ours** (arithmetic) | 0.414 L × 55 g/L = 22.8 g; × $0.0281/g = $0.64. **On-screen card required** |
| 59 | Oct 2025: first coffee increase in three years, ~3 cents, ~1.5% | b | Tim Hortons statement to CBC, 6 Oct 2025; Global News, same date |
| 60 | ~7% cumulative inflation over the same three years | b | Company's own figure — **attribute as the company's claim** |
| 61 | Green coffee US$1.58 → US$3.90/lb | b | Global News, 6 Oct 2025 |
| 62 | Two Canadian university economists called the increase defensible | b | CBC, 6 Oct 2025 — William Huggins (McMaster), Michael von Massow (Guelph) |

⚠️ **The script deliberately does not quote a national Tim Hortons coffee price** and instead sends the viewer to their own receipt. That is correct: there is no national price (see #6, #7) and no credible published source for one. **Do not insert a number here.**

### Number one — The App That Followed You Home

| # | Claim | Tier | Source |
|---|---|---|---|
| 63 | 1 June 2022: OPC + Quebec CAI + Alberta OIPC + BC OIPC published joint findings | a | **PIPEDA Findings #2022-001** |
| 64 | From May 2019 the app used a third-party service to track device location | a | Report, verbatim |
| 65 | "collect and process the Users' device location, as often as every few minutes… infer the location of a User's home and place of work, and when they were travelling… identify when the User was visiting a Tim Hortons competitor" | a | Report, **verbatim** |
| 66 | Mostly collected while the app was closed | a | Report, verbatim ("the vast majority of which was collected when the App was not in use") |
| 67 | Journalist's device logged >2,700 times in under 5 months, incl. Netherlands and North Africa where TH does not operate | a | Report, verbatim |
| 68 | Contraventions of PIPEDA and all three provincial statutes | a | Report, formal findings on both purpose and consent |
| 69 | Regulators described the company's permission-screen and FAQ statements as "misleading statements, not consistent with the actual operation of the App" | a | Report, verbatim |
| 70 | Therrien: "Following people's movements every few minutes of every day was clearly an inappropriate form of surveillance." | a | OPC news release, 1 June 2022 |
| 71 | **No fine, no penalty, no order** | a | Report contains recommendations only; disposition is "well-founded and conditionally resolved" |
| 72 | Collection permanently ceased Aug 2020; SDK removed Sept 2020 | a | Report, verbatim |
| 73 | Four class actions settled nationally, approved 22 Sept 2022 — free hot beverage + baked good, ~1.9M credits, court valued at $16,179,000 | a | Quebec Superior Court, Sheehan J., No. 500-06-001081-203, paras. 44–47 |
| 74 | **The court recorded that the defendants contested the consent finding** | a | Same judgment, para. 34, verbatim |
| 75 | June 2023: OPC "satisfied that the company has met its commitments" | a | OPC blog, Michael Maguire, 29 June 2023 |
| 76 | 8.6 million Canadian downloads | a | Report, verbatim |

⚠️ **ACCESS CAVEAT.** priv.gc.ca returned connection resets / HTTP 503 during research. All OPC verbatim text was extracted from Internet Archive captures of the official pages. **The text is the OPC's own, but re-open the live URLs and confirm every quoted passage before broadcast.**

### The good list and the close

| # | Claim | Tier | Source |
|---|---|---|---|
| 77 | Foundation Camps founded 1974 in Tim Horton's memory | b | CBC obituary of Ron Joyce, 1 Feb 2019 |
| 78 | "nearly 350,000 youth at no cost to them or their families" | a | RBI *Restaurant Brands for Good* 2025 report, verbatim — **attribute as a company claim** |
| 79 | Camp Day 2025 raised over C$13M; C$275M since inception; owners donate 100% of hot and iced coffee proceeds | a | Same report, verbatim |
| 80 | Smile Cookie: C$35.6M in 2025; over C$150M since 1996; 1,200+ organisations | a | Same report, verbatim |
| 81 | **Recipients are chosen by the local restaurant owner** | a | Same report, verbatim |
| 82 | ~4,000 restaurants in Canada; over 100,000 employees; ~45% aged 15–24 | a | Tim Hortons corporate newsroom — **company claim** |
| 83 | 370,000+ kids in Timbits Sports in 2025 | a | RBI 2025 report |
| 84 | Reusable cup saves 10 cents at every size | a | Live API capture, 18 Sept 2026, store 102601 |

⚠️ **#82: say "roughly 4,000 in Canada" and cite the company.** Sources give 3,558 / 3,570 / 3,903 / 4,000+ / 4,586. **4,586 is Canada + US.** Do not use it for Canada.

---

## PART B — MANDATORY ON-AIR PHRASINGS

1. **The three fairness beats are not optional.** (i) The coffee-price defence at number two — 3 cents, 1.5% vs 7%, green coffee $1.58→$3.90, two named economists. (ii) The 2.8% FY2025 growth and 80 new stores at number three. (iii) The resolution of the privacy matter at number one — no fine, stopped in 2020, OPC satisfied June 2023. Cutting any of these makes the video both less accurate and more attackable.
2. **"Well-founded and conditionally resolved" is the regulators' own term of art.** Use it. It is the whole legal basis for the segment.
3. **State the dismissal in the same breath as every allegation.** Fairview Donut, Latifi, GWNFA, the US case. The script does this; keep it.
4. **"Our calculation" on screen** for the 64-cent arithmetic and the 13.5–21% stack.
5. **Every price table carries "captured 18 Sept 2026 from Tim Hortons' own ordering system. Prices vary by restaurant."**
6. **Foreign ownership is not wrongdoing** and the script must not imply it is. 3G's stake has *fallen* from ~51% to 21.3%.
7. **Attribute every company figure as a company claim** — the Foundation numbers, the employee count, the inflation comparison.
8. **The delivery-disclosure gap is stated as unresolved, on air.** "I cannot prove a negative from a code file." Keep that sentence verbatim.
9. **The register is loss, not contempt.** No sneering in the VO. The cold open is about a smell.
10. **Never state or imply that any franchisee committed an offence.** No charge, conviction or prosecution of any franchisee was located.

---

## PART C — PRODUCER ACTIONS BEFORE RECORDING

1. **FILM THE CANADIAN DELIVERY CHECKOUT.** Open the app, add a medium coffee, switch pickup→delivery, film the entire flow including any disclosure text and the fee breakdown. This is the highest-value shot in the video and it resolves the one open question in the script.
2. **Do not name the current operator of the Brantford plant.** The dossier could not confirm to tier (a) that Aspire Bakeries runs that specific facility today. Say "now in third-party hands," which is what the script says.
3. **Re-open priv.gc.ca live** and confirm every quoted OPC passage. All of it came via Internet Archive.
4. **Re-verify the Q2 2026 earnings-call quote** against RBI's own webcast, not the third-party transcript.
5. **Film two menu boards in one city** plus both receipts, date and location visible.
6. **Film the reusable-cup discount** ringing through.
7. **Measuring jug and a large cup on camera** for the 2012 rename segment.
8. **Buy a 340g bag of coffee on camera** with the price tag visible.
9. **Pronunciation pass:** Aryzta (a-RIZ-ta), Maidstone, Brantford, Kobza (KOB-za), Therrien (TERR-ee-en), Commission d'accès à l'information du Québec.
10. **Verify every map frame.** Three separate commenters on one competing video caught it showing US states under Canadian narration. Get Newfoundland and Labrador into any coast-to-coast line.
11. **No AI thumbnail and no AI B-roll.** A commenter on a competing video was upvoted 26 times for mocking exactly that.

---

## PART D — DO NOT USE

1. **"Tim Hortons was fined / ordered."** No fine, no penalty, no order. A Report of Findings with accepted recommendations.
2. **"A court found Tim Hortons broke privacy law."** A regulator found it. No court ruled on the merits.
3. **"Tim Hortons admitted it."** The company contested the consent finding in court, para. 34.
4. **That the third-party location provider sold or misused data.** The regulators expressly accepted it did not.
5. **That Tim Hortons shrank the cups in 2012.** Volumes were unchanged.
6. **That the 2014 Temporary Foreign Worker moratorium penalised Tim Hortons.** It was sector-wide across all food services. Presenting it otherwise is a factual error and a legal exposure.
7. **Any franchisee cost figure from the Fairview Donut case.** Failed allegations.
8. **That the Latifi wage case went to the Supreme Court.** The SCC *refused to hear it*, with costs, 18 Sept 2025. It never ruled on the merits.
9. **That Ottawa found problems with the 2014 takeover.** The Investment Canada Act review found "no compliance issues." Exculpatory.
10. **Any claim about 3G Capital's nationality.** The jurisdiction field was not confirmed from the filing.
11. **The Ron Joyce "certainly not the same" quote about frozen donuts.** Traces only to a Maclean's feature that was Cloudflare-blocked. Tier (c). **If it verifies from a library database it becomes the best cold open available — but not until then.**
12. **Any menu price from an aggregator site.** ~40 of them are listed and excluded in the dossier. Several present themselves as "official 2026 menu prices" and are scraped, stale or invented.
13. **A fabricated 2026 Tim Hortons recall** currently circulating from a satire site. It is a joke. It is not a recall.
14. **The "$243,889 per franchisee per year" cost figure.** The franchisee association's own estimate, never audited.
15. **The GWNFA's "almost half of Canadian franchisees" membership claim.** Never independently verified.
16. **Any Second Cup store count.** The company's own locator is reported inaccurate.
17. **The "70% of Canada's hot brewed coffee" market-share figure.** No primary source exists.
18. **"Mother Parkers sold Tim Hortons' old beans to McDonald's."** Widely repeated, no primary source, and Tim Hortons publicly denied selling its recipe or beans in 2019.
19. **Any rural-vs-urban store split.** No source exists. Show a map instead.
20. **Cleanliness and washroom complaints from competitor comment sections.** Subjective impressions of individual franchises, unverifiable at scale, off-thesis, and they pull the comments straight into the material quarantined in Part E.
21. **BCHRT temporary foreign worker complaint outcomes.** Allowed to proceed in 2015; the final outcome could not be established. Do not state one.

---

## PART E — COMMENT MODERATION: READ BEFORE PUBLISHING

Four competing Canadian Tim Hortons videos totalling ~461,000 views and ~5,350 comments were mined for this dossier. **The highest-liked comments in that genre are overwhelmingly about the ethnicity of staff.** In one video, five of the top ten. In another, three of the top five. A second large block makes unproven allegations about hygiene, fraud and immigration abuse.

The dossier lists those handles with the text withheld, for editorial awareness only. **None may be read, shown, paraphrased or screenshotted.**

Practical consequences:
1. **You cannot build a "what Canadians are angry about" montage from top-liked comments.** It would be a montage of racial abuse.
2. **Your own comment section will go the same way within an hour.** Budget moderation from minute one. Consider holding comments for review on this upload specifically.
3. **The closing CTA is a moderation tool.** Asking for a dated receipt — a number, a town, a province — gives the audience a concrete, non-inflammatory task. That is deliberate. Do not swap it for an opinion prompt.

---

## PART F — WHAT THE AUDIENCE ALREADY KNOWS, AND GETS WRONG

Content gaps confirmed across ~5,350 competitor comments. Each is answered in this script, and each is a reason the video exists:

- **"Who actually owns Tim Hortons?"** Answered variously as Brazilian, American, Burger King, private equity. Nobody says: Restaurant Brands International, incorporated under the Canada Business Corporations Act, listed on the TSX and NYSE, executive offices in Miami, Tim Hortons segment headquartered in Toronto. All tier (a).
- **"When did in-store baking stop?"** Answers range from the late 90s to 2014. **Nobody got it right. It is late 2003.**
- **"Does Tim Hortons still own the Brantford bakery?"** Never asked correctly. They sold it in 2010.
- **"Why is the price different at every store?"** Nobody explains franchisee pricing autonomy.
- **"If everyone's quitting, why are the lineups long?"** Asked three times across the corpus. Answered never. **Answered at number three in this script.**
- **"Did McDonald's get Tim Hortons' old coffee?"** Asserted with 215 likes on one video. Unsourced. Left out of this script deliberately.

The accuracy bar is high: three separate commenters on one competing video caught a US map shown under Canadian narration. This audience checks frames, dates and arithmetic.
