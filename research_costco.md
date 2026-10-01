# Research package — Costco membership redo (1 Oct 2026)

<!-- ===== note_costco_structure.md ===== -->

# Structure note: the Costco renewal redo (replaces "Don't Renew Your Costco CANADIAN Membership Until You Watch This", May 13 2026, 236K)

Prepared 1 Oct 2026 for an episode going live Sunday 4 Oct 2026. This note covers structure only: skeletons, claim audit, hit-versus-flop facts, the questions for the fact researchers, and the recommended skeleton. Section 0b lists the primary pages opened today, because the claim audit in section 2 needed them. All other facts are left to the dossier researchers.

Format follows note_oatmeal_structure.md section 4 and note_apples_structure.md sections 1d–1f.

---

## 0. Sources

### 0a. Transcripts saved and measured (scratchpad)

All seven were fetched on 1 Oct 2026 with Algrow `fetch_transcript`. Each has a raw `.txt` and a `_clean.txt`; the clean version has [music] tags and line breaks removed. Sentence-numbered working copies are in `costco_num_*.txt` and `costco_may_numbered.txt`. Word counts below are from the clean text with ">>" speaker marks stripped.

| File | Channel / title | Published | Views (1 Oct) | Length | Words | Chars | c/w | wpm |
|---|---|---|---|---|---|---|---|---|
| tr_CC_costco_renew_may2026_236K.txt | Canadian Counter, "Don't Renew Your Costco CANADIAN Membership Until You Watch This" (hlJg9VFW5hQ) | 13 May 2026 (Wed) | 236,047 | 22:51 | 3,671 | 22,583 | 6.15 | 161 |
| tr_NACR_costco_renew_143K.txt | North America Crisis Radar, "Don't Renew Your Costco Canada Membership Until You Watch This" (HsJQZPadmBw) | 2 May 2026 | 143,279 | 19:37 | 2,978 | 18,580 | 6.24 | 152 |
| tr_FRUGALPRO_costco_40K.txt | FRUGAL PRO, "Don't Renew Your Costco Membership Until You Watch This" (UBvpwz2njMY), U.S. content | 13 Apr 2026 | 39,911 | 19:06 | 2,750 | 16,210 | 5.89 | 144 |
| tr_BC_costco_22K.txt | Broken Canada, "Don't Renew Your Costco Canada Membership Before Watching This" (7NrXkx1N0Jk) | 24 May 2026 | 21,868 | 29:23 | 4,426 | 25,890 | 5.85 | 151 |
| tr_FF_costco_12rules_216K_US.txt | Frugal Flow, "12 New Costco Rules for 2026 (Don't Get Your Membership Revoked!)" (ZWmP3S1Qq60), U.S., structure only | 23 Apr 2026 | 216,166 | 20:38 | 3,331 | 20,251 | 6.08 | 161 |
| tr_CC_costco_caught_sep2026_25K.txt | Canadian Counter, "Costco Canada Just Got Caught... And Members Already Knew Something Was Wrong" (cOnUYXhkteM) | 17 Sep 2026 (Thu) | 25,451 | 28:41 | 4,494 | 26,803 | 5.96 | 157 |
| tr_CC_costco_worthit_sep2026_3.8K.txt | Canadian Counter, "10 Costco Canada Items Actually Worth It And 5 That Aren't (SETEMPBER 2026)" (dcJfOVqONt8) | 21 Sep 2026 (Mon) | 3,925 | 22:11 | 3,609 | 20,033 | 5.55 | 163 |

- **Channel baseline:** the median for the 51 Canadian Counter uploads from 8 Aug to 28 Sep 2026 is 7,546 views (quartiles 3,137 and 17,217), from `get_channel_videos` on 1 Oct 2026.
- **Against that median:** May is about 31x (it was published in a different period), Caught 3.4x, Worth-it 0.52x.
- **Delivery speed:** at the channel's 155–163 wpm, a 21,000–23,000-character script at about 6.0 c/w (3,500–3,800 words) runs about 22–24 minutes.

### 0b. Primary and named pages opened on 1 Oct 2026, with tier

Working copies of the curl fetches are in `scratchpad/cc_renew/`. "WebFetch" means the page was read through a summarising fetcher. Its quotes are close but must be screen-captured verbatim before air (see U-list).

| # | Source | URL | Method / result | Tier |
|---|---|---|---|---|
| S1 | Costco Wholesale Canada, *Membership Conditions & Regulations*, page dated "August 1, 2026" | https://www.costco.ca/f/-/membership-conditions-regulations | curl, HTTP 200, full text (terms.txt) | (a) |
| S2 | costco.ca Join page | https://www.costco.ca/join-costco.html | curl, 200 | (a) |
| S3 | costco.ca Executive 2% Reward page | https://www.costco.ca/executive-rewards.html | curl, 200 | (a) |
| S4 | costco.ca CIBC Executive offer page, including the full CIBC rewards fine print | https://www.costco.ca/cibc-executive-offer.html | curl, 200 | (a) |
| S5 | CIBC, CIBC Costco Mastercard page | https://www.cibc.com/en/personal-banking/credit-cards/all-credit-cards/costco-mastercard.html | curl, 200. The tooltip caps are not in the HTML; S4 carries them. | (a) |
| S6 | costco.ca Tires page | https://www.costco.ca/tires.html | curl, 200 | (a) |
| S7 | costco.ca Kirkland Signature Gasoline page | https://www.costco.ca/gasoline.html | curl, 200 | (a) |
| S8 | costco.ca Optical page | https://www.costco.ca/optical.html | curl, 200. Barred topic; used only to tag the claim. | (a) |
| S9 | Costco CS "Does Costco offer extended warranty on products?" (a_id 1017267) | https://customerservice.costco.ca/app/answers/answer_view/a_id/1017267/~/does-costco-offer-extended-warranty-on-products | curl 401; WebFetch OK | (a) |
| S10 | Costco CS "What is the Costco Technical and Warranty Service?" (a_id 1017381) | https://customerservice.costco.ca/app/answers/answer_view/a_id/1017381/~/what-is-the-costco-technical-and-warranty-service | WebFetch | (a) |
| S11 | Costco CS "What is the price adjustment policy for warehouse items?" (a_id 1017287) | https://customerservice.costco.ca/app/answers/answer_view/a_id/1017287 | WebFetch | (a) |
| S12 | Costco CS "Costco's Satisfaction Guarantee" (a_id 1017252) | https://customerservice.costco.ca/app/answers/answer_view/a_id/1017252 | WebFetch | (a) |
| S13 | Costco CS "Membership FAQ" (a_id 1017208) | https://customerservice.costco.ca/app/answers/answer_view/a_id/1017208 | WebFetch | (a) |
| S14 | Costco CS "Where can I purchase a Shop Card?" (a_id 1017560) | https://customerservice.costco.ca/app/answers/answer_view/a_id/1017560 | WebFetch | (a) |
| S15 | costco.ca "Costco credit card change, March 2022" | https://www.costco.ca/f/-/connection-costco-credit-card-change-march-2022 | WebFetch | (a) |
| S16 | The Canadian Press on CBC News, "Costco Canada to stop accepting American Express cards", 18 Sep 2014 | https://www.cbc.ca/news/business/costco-canada-to-stop-accepting-american-express-cards-1.2770732 | curl, 200 | (b) |
| S17 | David Paddon, The Canadian Press, on Global News, "Costco Canada dumping American Express for MasterCard", 18 Sep 2014 | https://globalnews.ca/news/1571433/costco-canada-dumping-american-express-for-mastercard/ | curl, 200 | (b) |
| S18 | Costco Wholesale Corp., Form 8-K Ex. 99.1, "reports fourth quarter and fiscal year 2026 operating results", 24 Sep 2026 | https://www.sec.gov/Archives/edgar/data/0000909832/000090983226000084/costex9918-k92426.htm | WebFetch | (a) |
| S19 | Costco CS search list for "price adjustment" (answer titles only) | https://customerservice.costco.ca/app/answers/list/kw/price%20adjustment/page/1 | WebFetch | (a), titles only |

Earlier dossiers in the repo are cited by section and were not re-opened today: /home/user/Food/research_costco_caught.md (3.1 fee increase, 3.5 reward exclusions, 3.6 Executive perks, 3.7 renewal rates, 2.1 El Bechara) and /home/user/Food/research_rotisserie.md (Canadian chicken price).

Key lines from S1–S4, verbatim, used throughout:

- S1: "Gold Star Membership fee is $65 (plus applicable taxes) per 12-month period…"; "Executive Membership is $130 (plus applicable taxes)…"
- S1: "On Membership: We will cancel and refund your membership fee at any time if you are dissatisfied."
- S12 (CS page): "We will refund your membership fee in full at any time if you are dissatisfied."
  - The two Costco pages word the promise differently. Quote whichever page is shown on screen.
- S1, on the reward: "Rewards will not be calculated: (i) on purchases of cigarettes or other tobacco-related products; (ii) on purchases that are not recorded through Costco Wholesale's front-end registers, such as services, purchases at Costco Wholesale's gas stations, food courts, optical centres (Quebec only), and pharmacies; (iii) on membership fees; … (vii) on certain other categories as determined from time to time at Costco Wholesale's sole discretion…"
- S1: "The period of calculation will run approximately from the date of the member's paid enrollment or upgrade to Executive Membership through the date approximately three months prior to the member's renewal date. Purchases from the last three months will be added to the following year's Reward calculation. Calculation of a Reward is capped at, and will not exceed, $1,250 for any 12-month period. Executive Members who downgrade to Gold Star or Business status or cancel their membership and receive a refund of their membership fees will not receive a Reward."
- S1: "If you have not signed up for auto renewal, your membership fee will be charged on your first shop of your renewal month. … Costco members may charge their membership fees automatically on any Mastercard® credit card or Visa credit or debit card; the card will be charged on the first day of your renewal month." Also: "Memberships renewed within 2 months after expiration of the current membership year will be extended for 12 months from the expiration date. Memberships renewed more than 2 months after such expiration will be extended for 12 months from the renewal date. All renewals will be at the membership fee in effect on the date the membership fee is paid."
- S2: "The Reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid." Also: "Purchases made prior to upgrade do not qualify for the 2% Reward."
- S4 (CIBC fine print, personal card): "earn 3% on purchases … at merchants classified in the credit card network as Costco gas stations within Canada and 2% on purchases … at … gas merchants and electric vehicle charging … on the first $5,000 net annual card purchases in this category… Earn 2% on … Costco.ca purchases on the first $8,000… Purchases at merchants classified in the credit card network as restaurants will earn 3% and all other qualifying purchases will earn 1%… Cash Back Gift Certificate … once per calendar year in January…"
  - The $8,000 restaurant cap appears only in the Business Mastercard paragraph.
- S18: membership fees FY2026 "$5,907" million, Q4 "$1,850" million (USD, company-wide); "115 in Canada"; "939 warehouses" total; Canada comparable sales 52 weeks "7.8%" reported and "6.7%" adjusted.
  - The 8-K defines the adjustment; quote it from the document.

---

## 1. Measured skeletons

### 1a. Canadian Counter, May 13 2026 (236K): the video being replaced. 3,671 w, 22,583 chars, 6.15 c/w

**Cold open, 176 w (4.8%). Eight moves:**
1. An unsourced national count: "Over 10 million Canadians have a Costco membership."
2. The fee as an unthinking auto-charge, with both prices ("$65 for Gold Star, $130 for Executive").
3. The assumed value list (bulk, "rotisserie chicken at $7.99", Kirkland, fuel).
4. The "But" pivot to "savings opportunities, refund policies, and access tricks".
5. An escalation ladder: "a few dollars", then "hundreds of dollars a year", then "could pay for your entire membership", with the best "saved for the end".
6. The count and frame: "10 Costco Canada secrets the warehouse doesn't advertise on a billboard."
7. The renewal promise: "whether you renew it at all, should look very different."
8. Sign-on: "Grab your membership card. Let's dig in."

There is no dated fact, no source and no ask in the open. "Renew" appears 6 times in the whole script; "secret" 7 times.

**Count and order.** Ten reasons, never numbered aloud, introduced by scene-setting bridges. No order basis is stated. The only device is "the biggest secret" held for last (gas). Each reason runs 250–390 w and the beats grow longer toward the end.

| Beat | Sent. | Words | Share | Starts (w%) | Starts (c%) |
|---|---|---|---|---|---|
| Cold open | 1-13 | 176 | 4.8% | 0.0% | 0.0% |
| R1 Concierge/warranty + Instacart credit | 14-29 | 274 | 7.5% | 4.8% | 4.6% |
| R2 Tire centre | 30-45 | 293 | 8.0% | 12.3% | 12.1% |
| R3 30-day price adjustment | 46-65 | 257 | 7.0% | 20.2% | 20.4% |
| R4 Price-tag codes | 66-86 | 305 | 8.3% | 27.2% | 27.2% |
| R5 Non-member back doors (pharmacy, optical, Shop Card) | 87-105 | 326 | 8.9% | 35.5% | 35.1% |
| R6 Kirkland makers | 106-125 | 363 | 9.9% | 44.4% | 44.2% |
| R7 Return policy | 126-146 | 280 | 7.6% | 54.3% | 54.8% |
| R8 Membership-fee refund + "joining window" | 147-167 | 322 | 8.8% | 61.9% | 63.1% |
| R9 Mastercard-only + CIBC card | 168-189 | 383 | 10.4% | 70.7% | 71.6% |
| Like + subscribe ask | 190-193 | 72 | 2.0% | 81.1% | 81.9% |
| R10 Gas bar | 194-214 | 380 | 10.4% | 83.1% | 83.6% |
| Recap (all ten, one line each) | 215-226 | 174 | 4.7% | 93.5% | 93.5% |
| Close | 227-231 | 66 | 1.8% | 98.2% | 98.2% |

**Ask.** There is one ask, at 81.9% of characters, placed before the last reason: "Before we get to the biggest secret on this list, quick favor. If anything here has been useful, take a second to hit the like button and subscribe to the channel." It contains the phrase "take a second to … subscribe". There is no comment ask and no share ask. The close is a moral ("The trick is knowing the policies, using the services, and stacking the returns.") with no tagline and no disclaimer.

**How each reason is built (measured on six).** Every reason uses the same template:
1. A second-person "most members" hook (14–41 w).
2. The rule or mechanism (20–116 w).
3. A competitor contrast with no price or source (Best Buy, Canadian Tire).
4. A second layer or perk.
5. An instruction ("check…", "use this…").
6. A one-line closer that turns the fact into a "hidden"/"quietly" frame ("Most members never realize they're sitting there.", "The desk doesn't proactively offer it.", "It is the membership.").

| Reason | Jobs and word counts |
|---|---|
| R1 (274) | hook 25; mechanics 67; competitor contrast 37; second perk (phone line) 59; Instacart credit 54; closer 32 |
| R2 (293) | hook 41; bundled-services list 104; Canadian Tire contrast 34; promo events 59; instruction 55 |
| R3 (257) | hook 35; rule 115; timing windows 52; "desk doesn't offer" 24; instruction 31 |
| R8 (322) | hook 15; rule 80; terms quote + 11-month scenario 86; "not a secret … invisible" 25; mental model 48; joining window 68 |
| R9 (383) | hook 14; rule 20; 2014 history 50; CIBC 2022 62; earn rates 116; stacking math 81; closer 40 |
| R10 (380) | hook 26; 5–15 c/L claim 31; "check an app" 22; arithmetic 62; fee comparison 69; fuel quality 37; member-only scan 36; thesis + upgrade call 97 |

There are no dated sources in any reason except "a 2016 interview with WSB Television" (R6) and "March 2022" (R9). The only quote from a Costco document is the refund line (R8). Reason by reason the source density is near zero, and the "hidden" frame does the persuading.

What the title promises versus what the script delivers: the title is a renewal decision, but the script is a perks list that answers the decision only in R10's last 97 words ("The smart move isn't deciding whether to renew…"). The comments say so: "I don't understand the title" (28 likes), "Ok so why shouldn't I renew before watching this????", "What the hell is this title trying to tell us ???".

### 1b. North America Crisis Radar (143K), same title, 2 May 2026. 2,978 w, 6.24 c/w

| Beat | Sent. | Words | Share | Starts (c%) |
|---|---|---|---|---|
| Cold open + promise | 1-24 | 381 | 12.8% | 0.0% |
| #7 price-tag codes | 25-51 | 341 | 11.5% | 11.9% |
| #6 Kirkland | 52-76 | 321 | 10.8% | 22.9% |
| #5 returns + price adjustment | 77-93 | 268 | 9.0% | 34.5% |
| Retention tease ("Still with us?") | 94-95 | 13 | 0.4% | 43.5% |
| #4 gas | 96-106 | 273 | 9.2% | 43.9% |
| #3 pharmacy / optical / tires | 107-131 | 319 | 10.7% | 53.4% |
| #2 "membership reset" / promo codes | 132-150 | 365 | 12.3% | 65.1% |
| #1 executive stack | 151-181 | 467 | 15.7% | 77.7% |
| Recap + moral | 182-197 | 172 | 5.8% | 92.9% |
| Comment + share ask | 198-203 | 58 | 1.9% | 98.3% |

**Cold open moves:**
1. A TikToker hook.
2. A second-person trip montage ("You grabbed your cart…").
3. "Here's what nobody tells you", attributed to unnamed "consumer savings advocates".
4. The stakes: "$65 … $130. The prices went up."
5. Speculation that future increases could come sooner, attributed to unnamed analysts.
6. The channel name, then seven "secrets" with three teasers.
7. "Stay with us all the way to secret number one."

**Structure.** A numbered countdown, 7 to 1, with the biggest item last. It has a mid-video retention tease at 43.5% but no subscribe ask anywhere; the only ask is comment + share at 98%.

**Reasons.** Nearly every reason is attributed to unnamed groups ("consumer insiders", "alleged Costco employees across forums", "consumer deal analysts"). That is a rule (2c)/(8) failure pattern, and the redo must not copy it.

**What it did that May did not:** it numbered the list aloud, put an explicit Executive break-even in the #1 slot ("$3,250 … roughly $270 per month"), and closed with a renewal action ("Before your next renewal date, look at what you've actually used.").

### 1c. FRUGAL PRO (40K), "Don't Renew Your Costco Membership Until You Watch This", 13 Apr 2026. 2,750 w. U.S. content

| Beat | Sent. | Words | Share | Starts (c%) |
|---|---|---|---|---|
| Cold open | 1-14 | 173 | 6.3% | 0.0% |
| #10 food court | 15-29 | 170 | 6.2% | 6.5% |
| #9 pharmacy | 30-44 | 181 | 6.6% | 12.4% |
| #8 Kirkland | 45-68 | 193 | 7.0% | 19.3% |
| #7 hearing aids | 69-88 | 233 | 8.5% | 26.7% |
| #6 optical | 89-106 | 213 | 7.7% | 35.7% |
| #5 rotisserie chicken (+ "war in the comments" bait at 50%) | 107-128 | 252 | 9.2% | 43.6% |
| #4 executive math | 129-148 | 262 | 9.5% | 52.2% |
| #3 travel | 149-166 | 265 | 9.6% | 61.5% |
| #2 returns | 167-193 | 266 | 9.7% | 71.5% |
| #1 "savings stack" | 194-240 | 497 | 18.1% | 81.0% |
| Comment / share / subscribe | 241-245 | 45 | 1.6% | 98.5% |

**Cold open:** "Walk into Costco this year and something feels different", three claimed changes (food-court scan, Executive early hour, "the federal government is actively investigating", which is unsourced), "separating insiders from everyone else", and "10 Costco secrets the warehouse does not want going public."

Everything in it is U.S. (Citi Visa, Sam's Club, J.D. Power, "16% of the entire US hearing aid market", Expedia). Its one structural lesson is the comment-bait line at 50% ("I know that's going to start a war in the comments").

Its claim that Costco "will refund the difference" if the 2% does not cover the upgrade is U.S. lore. Costco Canada's own join page (S2) says the opposite: "The Reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid."

### 1d. Broken Canada (22K), "…Before Watching This", 24 May 2026. 4,426 w, 5.85 c/w

| Beat | Sent. | Words | Share | Starts (c%) |
|---|---|---|---|---|
| Cold open + channel intro | 1-17 | 260 | 5.9% | 0.0% |
| Promise vs reality (fee history) | 18-62 | 464 | 10.5% | 5.9% |
| Kirkland "bait and switch" | 63-121 | 632 | 14.3% | 16.3% |
| Treasure hunt | 122-150 | 433 | 9.8% | 31.0% |
| Price illusion | 151-183 | 522 | 11.8% | 40.3% |
| Membership-fee "racket" + exec math | 184-209 | 363 | 8.2% | 52.0% |
| Who it works for / not | 210-235 | 406 | 9.2% | 60.4% |
| Alternatives 3-2-1 | 236-278 | 641 | 14.5% | 69.5% |
| One rule before you renew (receipt audit) | 279-311 | 414 | 9.4% | 84.3% |
| Bottom line | 312-323 | 185 | 4.2% | 93.5% |
| Subscribe ask + next-week tease | 324-329 | 106 | 2.4% | 97.6% |

**Factual problems.** Chapters, not a list. The cold open's money claim is wrong for Canada: "anywhere from 104 to 136 dollars", against $65/$130 per S1.

The fee history ("$60 in 2009 … $104 today … 73%") is wrong per S1 and research_costco_caught.md 3.1. These are unsourced: "14 million card holders", "caps its product margin at 14%", "membership fees represent over 70% of Costco's profit", "Kirkland's Canadian bacon … reduced protein content", "a 2019 study", and "Dalhousie 2023 price audit". The Kirkland chapter alleges supplier swaps and "specification drift" with no source (rule 6). The transcript also contains a stray, repeated "Number 17, meatloaf with tomato glaze and green beans" (sentences 174, 199, 293), which looks like script contamination.

**What transfers (structure only):**
- the "who it works for / who it doesn't" chapter at 60%;
- the receipt-audit rule at 84% ("Your purchase history is available through your online account. Pull the last year.");
- three-tier renewal verdicts ("If your savings exceed $300 over the membership fee, renew … between $100 and $300 … pause … under $100 … do not renew").

The dollar thresholds are the channel's own invention and must not be reused as if documented.

### 1e. Frugal Flow (216K), "12 New Costco Rules for 2026", 23 Apr 2026. U.S., structure only. 3,331 w

| Beat | Words | Share | Starts (c%) |
|---|---|---|---|
| Cold open (like ask at s5, 2.3%) | 83 | 2.5% | 0.0% |
| Rules 1–12, numbered aloud "One, …", 132–345 w each (mean 258) | 3,092 | 92.8% | 2.3%–90.8% |
| Close + comment ask ("Which recent change … surprised you the most?") | 156 | 4.7% | 95.3% |

**Rule anatomy:**
1. The rule stated as a change ("You can no longer…").
2. What happens to you at the door, pump or till.
3. "This change didn't happen by accident", with a company number.
4. The consequence ("could be turned away", "revoked").
5. A next-visit instruction.

**Lessons for the redo:**
- It is the clearest "rules you must know" construction. Each item is a rule that acts on the viewer, rather than a perk.
- Every item is numbered aloud.
- The open is 83 w.
- A like ask comes in the first 25 words.
- Almost every factual claim is U.S. or unsourced: face-match scanning, "147.2 million", "ADA standards", "gold bars one per transaction", "up to 5% on gas". Use none of it.

### 1f. Canadian Counter, "Costco Canada Just Got Caught…" (25K, 3.4x median), 17 Sep 2026. 4,494 w, 5.96 c/w

**Cold open, 256 w (5.7%):**
1. A dated archival event as the first sentence ("October 30th, 1985. The National.").
2. Named people quoted verbatim (Knowlton Nash, Karen Webb, London Drugs' Mark Nussbaum: "And let them have it.").
3. The place (Burnaby, Brighton Avenue).
4. Then-to-now numbers (1 → 59 → 115).
5. A roll of closed competitors.
6. The question ("41 years later, what did Canada actually hand over?").

**Honesty frame, 174 w.** Next comes a separate frame: "not been fined by the Competition Bureau … zero Canadian legal proceedings in its annual report", a documents-only method, the count (15 + 5 "gets right") and the direction ("Counting up").

| Beat | Words | Share | Starts (c%) |
|---|---|---|---|
| Cold open (1985 archive) | 256 | 5.7% | 0.0% |
| Honesty frame + method + promise | 174 | 3.9% | 5.3% |
| Items 1–9 (terms clauses, scanners, fee, 2% exclusions, food court, Kirkland prices) | 1,305 | 29.0% | 9.2% |
| Comment ("drop the number nine") + subscribe ask | 51 | 1.1% | 38.4% |
| Items 10–15 (shrink, proposed class action, 61% made in Canada, recall-notice names, committee document, segment margin) | 1,675 | 37.3% | 39.5% |
| Turn | 45 | 1.0% | 77.6% |
| Five "gets right" | 749 | 16.7% | 78.7% |
| Close | 176 | 3.9% | 95.0% |
| Like / subscribe + two comment questions ("Are you renewing anyway? Because 92.1% of you did last year.") | 63 | 1.4% | 98.7% |

**Item anatomy:**
1. A one-line headline that states the finding ("Seven, the 2% doesn't cover the gas.").
2. The document, named and quoted verbatim.
3. The arithmetic or consequence ("2% has to cover the extra $65 … $3,250 … 62,500 to hit the cap").
4. Where needed, a concession or allegation label ("This is an allegation. It has not been tested.").
5. A one-line closer.

Items run 80–393 w. The ask sits at 38% and doubles as a comment prompt.

**Overlap the redo must manage.** Items 4–7 (terms clauses, fee increase, 2% exclusions, break-even arithmetic) are exactly the material the redo needs. Anyone who watched the Caught video has heard "the 2% doesn't cover the gas" and "$3,250". The redo must add something those items did not:
- the CIBC split;
- the three-month cut-off and the forfeiture on refund;
- the renewal-timing clauses;
- "not guaranteed";
- tax on the fee;
- the four-step method.

It must also present the material as rules to act on before paying, not as "caught" items.

Sentence 335 ("92.1% of you did last year") presents a combined U.S.-and-Canada rate as "you" (Canadian viewers). This is a rule 7 slip; do not repeat it.

### 1g. Canadian Counter, "10 Costco Canada Items Actually Worth It And 5 That Aren't (SETEMPBER 2026)" (3.9K, 0.52x), 21 Sep 2026. 3,609 w, 5.55 c/w

**Cold open, 351 w (9.7%):**
1. First-person disclaimer ("Let me be straight with you… I like Costco… I have a membership").
2. "This isn't one of those videos where … the warehouse is a scam."
3. Dated method ("Off costco.ca on the 19th of September 2026, item number by item number").
4. The insight ("a story about Costco versus Costco").
5. Count and two promises.
6. A caveat (online vs warehouse price, with the Hellmann's example).

There is no outside dated event and no decision for the viewer to make.

| Beat | Words | Share | Starts (c%) |
|---|---|---|---|
| Cold open + method + promises | 351 | 9.7% | 0.0% |
| W10–W5 (laundry, olive oils, maple syrup, bath tissue, coffee, dishwasher packs) | 1,075 | 29.8% | 9.4% |
| Subscribe ask ("hit subscribe because this is becoming a series") | 32 | 0.9% | 38.7% |
| W4–W1 (cheddar, bulk pantry, electronics terms, membership + Executive math) | 807 | 22.4% | 39.6% |
| Rotisserie aside (declines to price it) | 271 | 7.5% | 62.7% |
| Skip intro + S5–S1 (bacon, snack nuts, mini cookies, protein bars + supplier myth, premium bath tissue) | 673 | 18.6% | 70.1% |
| Close + "gets right" | 272 | 7.5% | 88.9% |
| Comment asks (two, data requests) | 128 | 3.5% | 96.5% |

**Item anatomy:**
1. Product, pack, price.
2. Unit price.
3. The neighbouring Kirkland SKU.
4. The percentage gap.
5. "I'm not telling you X is bad."

Items run 56–304 w. The script contains 19 hedge phrases ("could not", "won't", "I'm not going to"), against 4 in May. First-person "I" appears 70 times, against 0 in May; "we" appears 2 times, against 5.

### 1h. Cross-format table

| Video | Views | Open (w) | Dated fact in open? | List numbered aloud? | Order basis stated? | Asks: position (c%) | Comment ask? | Delivers the title's decision? | Disclaimer? |
|---|---|---|---|---|---|---|---|---|---|
| CC May (236K) | 236,047 | 176 | no | no | no ("biggest" saved for last) | 81.9% like + sub | no | only in last 97 w of R10 | no |
| NACR (143K) | 143,279 | 381 | no | yes, 7→1 | no | 98.3% comment + share | yes | yes, closing action | no |
| Frugal Flow US (216K) | 216,166 | 83 | no | yes, 1→12 | no | 2.3% like; 99.7% comment | yes | n/a (rules) | no |
| FRUGAL PRO US (40K) | 39,911 | 173 | no | yes, 10→1 | no | 50% comment bait; 98.5% comment/share/sub | yes | partly (#4 exec math) | no |
| Broken Canada (22K) | 21,868 | 260 | no | chapters | no | 97.6% subscribe | no | yes (renew / pause / don't-renew tiers) | no |
| CC Caught (25K) | 25,451 | 256 + 174 frame | yes, 1985 | yes, 1→15 then 1→5 | "counting up, biggest last" | 38.4% comment + sub; 98.7% like/sub + 2 comment Qs | yes | n/a | no |
| CC Worth-it (3.9K) | 3,925 | 351 | method date only | yes, 10→1 then skip 5→1 | no | 38.7% subscribe; 96.5% comment | yes (data request) | n/a (shopping list) | no |

---

## 2. Every claim in the May 13 video, tagged

**Tags:**
- **S** = sourced today, at tier (a) or (b), from the source cited.
- **U** = unsourced or unverified this session.
- **US** = U.S. material presented as Canadian.
- **O** = outdated or imprecise.
- **W** = contradicted by a tier (a) page opened today.
- **B** = barred (health or pharmacy/optical/food safety; "secret" or insider; "former employees"; supplier lore; implied motive).

A claim can carry several tags. Sentence numbers are from costco_may_numbered.txt.

| # | Sent. | Claim (May's wording, condensed) | Tag | Basis / note for the redo |
|---|---|---|---|---|
| 1 | 1, 226 | "Over 10 million Canadians have a Costco membership"; "10 million Canadians keep their membership" | U | Costco does not publish a Canada-only member count. Its figures are worldwide or "U.S. and Canada" (research_costco_caught.md 3.7). Do not state any Canadian member count. |
| 2 | 2 | The fee "gets pulled from your credit card every renewal cycle" | O | Only if you are on auto-renew. Otherwise it is "charged on your first shop of your renewal month"; auto-renew charges "on the first day of your renewal month", on Mastercard or Visa credit/debit (S1). |
| 3 | 3, 150, 202–203 | $65 Gold Star, $130 Executive | S | S1. Add "plus applicable taxes" (S1). |
| 4 | 5 | "rotisserie chicken at $7.99" | O, U | No costco.ca price exists. Radio-Canada International, 10 Feb 2026, gave $7.99–$9.00 (research_rotisserie.md). Comments disputed it. Rule 5: no retailer-own price, so do not say it. |
| 5 | 6, 10, 216 | "access tricks", "10 Costco Canada secrets the warehouse doesn't advertise on a billboard" / "won't put on a billboard" | B | "Secret" frame. Every item in the redo is printed on Costco's or CIBC's own pages. Say so. |
| 6 | 9, 204, 205, 226 | One item "could pay for your entire membership before you've even walked into the warehouse"; gas pays the fee "within a couple of months" | U | Rests on the unsourced c/L gap (#38). |
| 7 | 15 | "Costco Concierge Service" | O | Costco's CS page now calls it "Costco Technical and Warranty Service" (S10). |
| 8 | 16–18 | 2-year extension on TVs, projectors, computers (excluding tablets), major appliances; automatic, no cost; "Costco quietly adds the second" | S (rule); B ("quietly") | S9, S10: "Costco extends the manufacturer's warranty to two (2) years from the date of purchase" when the maker's warranty is shorter. Drop "quietly". |
| 9 | 19 | Best Buy / manufacturers pitch extended warranties "often costing 1 or 200 dollars per item" | U | No competitor source. Rule 5. |
| 10 | 21–23 | "free lifetime access" to a phone line, "staffed 7 days a week" | U, O | S10 (WebFetch) says support runs "during opening hours", in English and French. "Lifetime" and "7 days" are not on the page opened. |
| 11 | 24–25 | Since June 2025, Executive members get a $10 monthly Instacart / Same-Day credit on $150+ orders, on top of the 2% | S | S3 footnote: "$10 off one monthly order ($150 basket min.)". Effective 30 Jun 2025 per research_costco_caught.md 3.6. |
| 12 | 26–29 | "don't appear prominently", "paid for whether you use them or not", "Most members never realize" | U, B | Motive / "hidden" frame. |
| 13 | 32–33, 35–36 | Tires: installation included; lifetime rotation, balancing, flat repair; 5-year road-hazard warranty | S | S6: "Tire purchase includes installation at No charge. Additional member values included 5 year road hazard warranty, Rotation and Balancing, Flat repairs, Nitrogen tire Inflation…". S6 also says "Additional component costs, including TPMS service pack fees, may apply". Say that too (a commenter raised a $25 fee). |
| 14 | 34 | Nitrogen "maintains tire pressure better and runs cooler" | U | Technical claim, unsourced. Drop. |
| 15 | 37 | Road hazard pays a "pro-rated credit based on the remaining usable tread" | U | Road-hazard terms page not opened. |
| 16 | 38–40, 45 | At Canadian Tire the services "appear as line items"; competitors add "20% in services"; Costco "all-in number is often lower" | U | No source. Comparative claim about a named retailer. Drop. |
| 17 | 41–42 | Promotions "several times each year, typically $25 to $40 per tire"; "appear quietly" | O, B | Current promotions on S6 are dated and larger. Bridgestone "$100 instantly" and Firestone "$60" run Aug 31–Oct 4, 2026. Michelin "$100 off" and BFGoodrich "$60 off" run 9/28/26–11/01/26. Drop "quietly". |
| 18 | 50–51 | 30-day price adjustment if the price drops | S | S11: "We will honour price adjustment requests for purchases made in-warehouse within 30 days from the date of purchase. The item must be in stock (excluding demonstration merchandise) and within the valid promotional dates…" May omitted these conditions. |
| 19 | 50, 60–62 | "the vast majority of members never claim"; "The desk doesn't proactively offer it" | U, B | No data. Implies motive. |
| 20 | 52–55 | No return needed; "You don't need the receipt"; credit "back to your original payment method on the spot" | U | Not on S11. |
| 21 | 56–57 | Own price changes only; no competitor matching; "consistently honored" | U | S19 lists a CS answer titled "Does Costco match other retailers?" (a_id 1017310). It was not opened. "Consistently honored" is unsourced. |
| 22 | 58–59 | Best windows after Christmas and in late summer; the patio-furniture clearance example, "you're owed the difference" | U | Untested against S11's "in stock" and "valid promotional dates" conditions. |
| 23 | 66–86 | Price-tag codes: asterisk = deleted; .97 = clearance/manager markdown; .49/.79/.89 = manufacturer promotion; .99 = regular; "corroborated by … former employees and reporting outlets" | B, U, US | The video concedes "aren't officially confirmed by Costco". "Former employees" breaks rule 8. It is U.S. deal-blog lore. Never on air. |
| 24 | 87–90 | "plenty of Canadians are shopping at Costco Canada without holding any membership" | U | Vague. S1: "No sales will be made to any person unless they have a valid membership card." The Shop Card is the documented exception (#28). |
| 25 | 91–92 | "By Canadian provincial pharmacy law, Costco Canada cannot require a membership to access the pharmacy" | B, U | Pharmacy is a health service (rule 1). The law is not cited, and costcopharmacy.ca returned an empty shell today. |
| 26 | 93–95 | Pharmacy "widely regarded as one of the lowest priced … generic prescriptions"; "50-plus Canadians managing multiple medications … hundreds of dollars" | B, U | Health. Barred. |
| 27 | 96–100 | Optometrists are independent; non-members can book an eye exam; buying eyewear requires membership; "the exam is the loophole" | B, U | Health service. S8 says only "You do not need to have an eye exam at Costco to purchase eyewear." A commenter disputed the membership requirement. Barred. |
| 28 | 101–103 | A member can buy a Shop Card for a non-member, who can shop with it | S | S14: "Members may buy Costco Shop Cards for non-members. In order to use the Costco Shop Card at a Canadian warehouse, Non-members must present the Shop Card at the front entrance." A one-day-pass requirement appears only in a search summary (U-list). |
| 29 | 104 | Non-members "can't make returns that result in cash back" | U | Not on S14. |
| 30 | 105 | "the legitimate workaround Costco doesn't advertise" | W, B | Costco publishes it on its own customer-service page (S14). |
| 31 | 106–107, 116, 122 | Kirkland products "in many cases, are produced in the exact same factories as the premium brands"; "same manufacturer"; "the pattern repeats" | B, U | Supplier lore. Costco's own Kirkland inquiry notice says information "may be proprietary or confidential and will not be disclosed" (research_costco_caught.md Part 2, section 2). |
| 32 | 108–111 | Kirkland batteries "manufactured by Duracell … confirmed by … Craig Jelinek, in a 2016 interview with WSB Television in Atlanta" | US, O, B | A U.S. local station, about U.S. product, 10 years old. Says nothing about a 2026 Canadian pack. |
| 33 | 112–113 | Kirkland Scotch supplied by Alexander Murray & Co. since 2007 | US, U | Costco Canada does not sell spirits in most provinces; a commenter flagged this. U.S. product lore. |
| 34 | 114–115 | Kirkland Food Service foil by Reynolds; Reynolds logo on the pack | US, U | No Canadian pack photographed. |
| 35 | 117–119 | Starbucks roasts certain Kirkland coffees; Kimberly-Clark makes Kirkland diapers; Bumble Bee makes the albacore | Starbucks: S if re-shown on costco.ca; others: US, U, B | The Worth-it video (s105) says costco.ca prints "custom roasted by Starbucks" on certain listings. That page was not re-opened today. The diapers and tuna are lore. |
| 36 | 120–121 | "Canadian regulations require manufacturers or distributors to be listed on product packaging" | S (rule exists) | CFIA: name and principal place of business of the manufacturer or "the person for whom the food has been manufactured" (note_oatmeal_structure.md S5; Caught video s204). The inference in s122 ("same product") is U. |
| 37 | 123–125 | The Kirkland vodka / Grey Goose link is a myth; Grey Goose has denied it | US, U | U.S. lore. Not needed. |
| 38 | 196 | Costco gas is "typically … 5 to 15 cents per liter below nearby competitors" | U | No dated, sourced comparison. A commenter quotes "2 cents cheaper than any gas stations in 2 km", which is also unsourced. |
| 39 | 197 | "GasBuddy or a similar fuel price app" | (c) | Flag only. |
| 40 | 199–201 | 5 c/L × 60 L weekly ≈ $150/yr; 10 c ≈ $300 | arithmetic OK, premise U | 0.05 × 60 × 52 = $156; 0.10 × 60 × 52 = $312. |
| 41 | 131–134 | "100% satisfaction guarantee"; return "almost any item … at any time … for any reason" | S | S12 ("100% satisfaction guarantee"; "will refund the purchase price", with exceptions); S1. |
| 42 | 135, 143 | "There's no standard time limit"; "even just changed your mind months later" | S (with exceptions) | S1, S12. |
| 43 | 137–139 | "You don't need your receipt"; "Every purchase is automatically logged against your membership card" | U | Not on S1 or S12. |
| 44 | 141 | 90-day window for TVs, projectors, computers, tablets, smartwatches, cameras, drones, camcorders, music players, phones, major appliances | S | S1, verbatim list. |
| 45 | 142 | Diamonds 1 ct+: 2–5 business days to verify; original certificates; "Costco's in-house gemologist" | S; "in-house gemologist" U | S1: "approximately 2 to 5 business days" and "IGI and/or GIA certificates". |
| 46 | 144–145 | "Costco actively monitors return patterns"; excessive returners "can have their memberships terminated without refund"; "the most generous return guarantee in Canadian retail" | U (monitoring, "without refund", superlative); S (termination power) | S1: terminated "at Costco's discretion without cause, as well as for … abuse of your membership privileges". The superlative is unsourced. |
| 47 | 136 | The list of returnable categories (bulk food, clothing, furniture…) | S (general) | S1 lists exceptions only. Also say gold and silver bullion, gift cards, e-certificates and custom installs are non-refundable, which May omitted. |
| 48 | 148–149, 152–153 | Membership fee refundable "fully", "at any time", "for any reason", "not pro-rated", "not minus an admin fee"; the quote "We will refund your membership fee in full at any time if you are dissatisfied." | S, with a wording note | The quote matches S12 (CS page). S1 (terms dated Aug 1 2026) reads "We will cancel and refund your membership fee at any time if you are dissatisfied." The S2 join page reads "We will cancel and refund your membership at any time if you are dissatisfied." "Not pro-rated / no admin fee" is not stated on any page opened (U). |
| 49 | 150–151 | Executive refund is "minus any 2% annual reward you've already received that year" | O | S1: "Executive Members who downgrade … or cancel their membership and receive a refund of their membership fees will not receive a Reward." That is a forfeiture rule, not a deduction rule. Say it exactly. |
| 50 | 153 | "shop for 11 months … pharmacy … gas bar … then in month 12 … cancel and get every dollar back" | S (rule); B (pharmacy) | The rule is S. The scenario coaches maximum use followed by a refund. S1 allows termination for "abuse of your membership privileges". Do not coach it. |
| 51 | 154 | "isn't a secret in the legal sense … effectively invisible because almost no member tests it" | B, U | Secret frame; no data. |
| 52 | 161–167 | "Sign up before Christmas … reassess in January … the refund is waiting" | B, U | Coaching a refund play. Do not repeat. |
| 53 | 169–172 | "Costco Canada doesn't accept Visa … American Express … cash, debit, and MasterCard. And that's it." | O, incomplete | True of warehouse credit cards per S16/S17, but: S1 also lists "Costco Shop Card, preprinted personal cheque"; S1 lets the membership fee auto-charge to "Visa credit or debit"; commenters note Visa works on costco.ca (not verified today, U). |
| 54 | 173–174 | "traces back to 2014 when MasterCard became the exclusive credit card network … replacing American Express" | O | S16: Costco Canada would "end its 15-year-old relationship with American Express on Dec. 31" (story of 18 Sep 2014). S17: Costco Canada would "accept any issuer's MasterCard". The switch took effect at the start of 2015. |
| 55 | 177 | "In March 2022, … CIBC took over from Capital One as the exclusive issuer" | S | S15: "All eligible Capital One® Costco Mastercard® accounts will change to the CIBC Costco Mastercard as of March 4, 2022." |
| 56 | 178, 188 | No annual fee; requires a valid Costco membership | S | S5 ("Annual fee $0"); S4 ("you must be a Costco member with a valid Costco membership"). |
| 57 | 180 | "3% cash back on restaurant purchases on the first $8,000 of annual spending" | W | S4: on the personal card, restaurants "will earn 3%" with no cap stated. The $8,000 restaurant cap is in the Business Mastercard paragraph. |
| 58 | 181 | 3% Costco gas in Canada, 2% other gas and EV, on the first $5,000 | S | S4. The $5,000 is one combined gas/EV cap; after it, 1%. |
| 59 | 182 | 2% on costco.ca up to $8,000; 1% on everything else including in-warehouse | S | S4, S5 ("1% cash back on all other purchases including at Costco"). |
| 60 | 183 | Paid as a Costco gift certificate each January, redeemable in Canadian warehouses | S | S4, S5. |
| 61 | 184–186 | Executive 2% + card 1% = "3%" on in-warehouse spend | S (arithmetic), with caveats | Two programs with different bases, caps and timing: the 2% is capped at $1,250 and calculated to about 3 months before renewal (S1); the CIBC year is January to December (S5). |
| 62 | 187 | At the gas bar: "pump price discount plus 3% on the card plus the executive 2% reward where the gas qualifies" | W | S1: rewards are not calculated on "purchases at Costco Wholesale's gas stations". Gas never qualifies. |
| 63 | 214 | "upgrade to executive, stack the cashback card, and capture three layers of returns on every tank" | W | Same as #62. The Executive layer is zero on gas. |
| 64 | 189 | "one of the highest value pieces of plastic you can carry in this country" | U | Opinion. |
| 65 | 206–207, 213 | "top-tier rated"; "meets the additional detergent standards required by major automotive manufacturers, which means cleaner engines, better fuel efficiency, and fewer maintenance issues"; "the cleaner fuel" | S (Costco's words) / U (effects) | S7 shows the "Top Tier Detergent Gasoline" logo and "With 5X the Required CGSB Deposit Control Additive" and "Protects fuel injectors & intake valves". Attribute these to Costco. Efficiency and maintenance effects are U. |
| 66 | 208–209 | Gas bars are member-only; scan your card at the pump | U today | Not on the pages opened. S1 says only "purchase at our Gas Stations can only be made by debit card, Costco Shop Card, and those credit cards accepted". Check a costco.ca gas FAQ before using. |
| 67 | 210 | Digital cards work at entrances; pump compatibility "rolling out unevenly" | U | S1: you must scan "either in its original physical form or as it appears on the Costco mobile application" at entry and checkout. Pumps are not addressed. |
| 68 | 211–212 | "the Costco Canada gas bar isn't just a perk of the membership. It is the membership." | U | Opinion built on #38. |
| 69 | 227–231 | Close: "The trick is knowing the policies, using the services, and stacking the returns." | — | Do not reuse. |

**Counts** (computed from the 69 rows above; a row can carry several tags):

| Tag | Count |
|---|---|
| S (fully or for the core rule) | 23 |
| U (whole claim or a load-bearing part) | 36 |
| B | 16 |
| O | 9 |
| US | 6 |
| W | 4 (#30, #57, #62, #63); #49 is tagged O but works as a misstatement |

Every May reason except R3 (price adjustment), R7 (returns) and R9's earn rates carries at least one W, B or US line. R4 (codes), R5 (pharmacy and optical) and R6 (Kirkland makers) are wholly unusable.

**Sentences and phrases the redo must not reuse (May's signature lines):**
- "Grab your membership card. Let's dig in."
- "10 Costco Canada secrets the warehouse doesn't advertise on a billboard"
- "Most members never realize they're sitting there."
- "The desk doesn't proactively offer it. The transaction sits there, owed to you, until you bring it up."
- "you stop shopping blind"
- "So, the exam is the loophole, not the eyewear."
- "Different label, significantly lower price, same manufacturer."
- "Don't believe everything you read on social media."
- "And that phrase isn't marketing language. It's an operational policy."
- "The policy isn't a secret in the legal sense"
- "The mental model most Canadians carry into a membership is that you pay the fee and that's that."
- "It's one of the highest value pieces of plastic you can carry in this country"
- "It's outside at the gas bar."
- "It is the membership."
- "The smart move isn't deciding whether to renew"
- "That decision should look different now."
- "The trick is knowing the policies, using the services, and stacking the returns."
- "you'll know exactly what you're paying"

Also do not reuse the competitor sentences from NACR ("pulling back the curtain", "Costco is not going to show you this table", "Stay sharp, Canada"), FRUGAL PRO ("loyalty tax", "risk-free trial", "cash back machine") or Broken Canada ("It is a system", "loyalty loop", "The households that save the most … are loyal to the unit price").

---

## 3. Why the 236K and 25K Costco videos hit and the 3.9K one flopped (facts only; no retention data was available)

### 3a. Title construction

| Video | Title | Construction | Views |
|---|---|---|---|
| CC May | Don't Renew Your Costco CANADIAN Membership Until You Watch This | Negative imperative + a money decision at a deadline ("Renew") + brand + CAPS nationality + "Until You Watch This" gap. No number, no date, no product. | 236,047 |
| NACR | Don't Renew Your Costco Canada Membership Until You Watch This | Identical, without caps; 11 days earlier | 143,279 |
| FRUGAL PRO | Don't Renew Your Costco Membership Until You Watch This | Identical; U.S.; a month earlier | 39,911 |
| Broken Canada | Don't Renew Your Costco Canada Membership Before Watching This | Variant; 11 days later | 21,868 |
| Frugal Flow (U.S.) | 12 New Costco Rules for 2026 (Don't Get Your Membership Revoked!) | Number + "rules" + year + membership-loss consequence | 216,166 |
| CC Caught | Costco Canada Just Got Caught... And Members Already Knew Something Was Wrong | The channel's recurring "Just Got Caught" formula (Tim Hortons 16,235; Loblaws 3,858) | 25,451 |
| CC Worth-it | 10 Costco Canada Items Actually Worth It And 5 That Aren't (SETEMPBER 2026) | Product list + count + misspelled month tag | 3,925 |

- **Same title, four channels.** Four channels used the same "Don't Renew … Until/Before You Watch This" title between 13 Apr and 24 May 2026, and all four reached at least 21.8K. Two Canadian versions passed 140K.
- **The framing is the payment.** The framing those four share is a decision made at the moment of paying. Both Costco hits over 200K (May 236K, Frugal Flow 216K) put the membership itself at stake in the title.
- **The flop has no stakes.** Its title has no decision, no deadline and no stakes: it is a shopping list. The month tag is misspelled "SETEMPBER".
- **The format can work elsewhere.** The format did 104K on Canada Food Insider in May (note_costco_buyskip_structure.md), so a product list is not unworkable in general. On this channel's audience, in September, it returned 0.52x median.

### 3b. Thumbnails (viewed 1 Oct 2026 via Algrow `get_video_thumbnail`)

| Video | Thumbnail |
|---|---|
| CC May | AI-generated warehouse crowd, a news camera operator, a phone filmer, a yellow caution tape across the aisle, the Costco Wholesale Canada logo, a red "EXCLUSIVE:" tag, and "COSTCO CANADA IS IN TROUBLE!" in a white bar |
| NACR | The same template: camera with "NEWS" bug, caution tape, "EXCLUSIVE: COSTCO CANADA IN TROUBLE" |
| FRUGAL PRO | The same template: "EXCLUSIVE: COSTCO IN TROUBLE" |
| Broken Canada | The same template: "EXCLUSIVE COSTO IN TROUBLE!" (misspelled) |
| Frugal Flow | The same "EXCLUSIVE:" bar with "THIS CHANGES EVERYTHING", a hand holding a Gold Star card, a blurred "NEW COSTCO RULES" sign |
| CC Caught | "COSTCO CANADA HAS BEEN CAUGHT", angry customers at a food-court counter, a receipt reading "$97.00", Kirkland pizza boxes |
| CC Worth-it | Costco Wholesale logo, red "BUY vs SKIP" box, a Kirkland Maple Syrup jug, a "Made in Canada" maple-leaf roundel, a rotisserie chicken. No people, no conflict, no money figure. The video explicitly declines to price the chicken it shows (s173–195). |

Five of the six hits used a conflict or news-event thumbnail. The flop used a catalogue thumbnail.

**Rule note.** The May, NACR, FRUGAL PRO and BC thumbnails assert "IN TROUBLE" with crime-scene imagery that nothing in the videos supports. Under rule 6 ("never state or imply wrongdoing"), the redo cannot use that template. See 5a for a factual alternative.

### 3c. Framing and payoff

| Video | Framing | Payoff |
|---|---|---|
| CC May | Second person ("you/your" 124 times, "I" 0). Every reason is a "hidden" perk. | The decision named in the title is never worked through. Comments say the title was not paid off. Two of the top comments correct facts (the $7.99 chicken, whisky in Canada). |
| CC Caught | Documents first, then a "gets right" turn. Opens on a dated archive event. | Its "2% doesn't cover the gas" and "$3,250" items are the strongest renewal material on the channel, buried at items 6–7 of 15. Top comment: "Nothing enlightening to see here. Mostly click bait." (12 likes). |
| CC Worth-it | First person ("I" 70 times). 19 hedges. Several items are rules of arithmetic rather than findings. Unit-price comparisons are mostly Kirkland against Kirkland, because "everyone blocked" competitor prices. | 61 likes, 3 comments (one spam). |

### 3d. Measurable facts on placement and length

- **Length.** The two hits ran 22:51 (May) and 28:41 (Caught). The flop ran 22:11. Length does not separate them.
- **Weekday.** Wednesday (May), Thursday (Caught), Monday (Worth-it). 4 Oct 2026 is a Sunday.
- **Competition.** May went up 11 days after NACR's identical title. NACR had 143K by 1 Oct, which shows search and browse demand for the phrase existed in May.

---

## 4. What a viewer who saw the May video needs to be NEW in October (questions for the fact researchers)

Facts are left to the dossier researchers; these are the questions. Today's partial answers are in brackets with their source; everything else is open.

1. **Terms.**
   - Which clauses changed between the version live on 13 May 2026 and the page now dated "August 1, 2026" (S1)?
   - In particular, did the membership guarantee change from "refund your membership fee in full" to "cancel and refund your membership fee"? [S1, S2 and S12 differ today.]
   - An archived pre-August copy is needed; Wayback was blocked today.
2. **Fee.**
   - Has Costco announced, or been asked about, a next fee increase? The last was effective 1 Sep 2024 (research_costco_caught.md 3.1).
   - What did management say on the Q4 FY2026 call (24 Sep 2026)? Open the call transcript.
3. **The company's own numbers since May.**
   - Q4 / FY2026 release [S18: FY2026 membership fees US$5,907M; 115 warehouses in Canada; Canada comparable sales 7.8% reported, 6.7% adjusted, 52 weeks].
   - What is the U.S.-and-Canada renewal rate at FY2026 year-end? [search summaries say 92.3%; not in the 8-K; U-list.]
   - Paid members, Executive members and Executive share of sales.
   - When will the FY2026 10-K be filed, and will it land before 4 Oct?
   - Canada segment revenue and operating income for FY2026: the FY2025 numbers were in the Caught video.
4. **Warehouses and gas.**
   - Which Canadian warehouses or gas stations opened since May?
   - Are any standalone gas stations in Canada?
5. **Executive perks.**
   - Is the $10 Same-Day/Instacart credit still in force? [S3 shows it on 1 Oct.]
   - Do Executive early hours still apply in Canadian warehouses, and at what times?
   - Has the exclusions list (the "Annual 2% Reward Exclusions List" linked on S3) changed? Capture the list itself; it was not opened.
6. **CIBC card.**
   - Have earn rates or caps changed since May? [S4 today: 3% Costco gas and restaurants; 2% other gas/EV on $5,000 combined; 2% costco.ca on $8,000; 1% other.]
   - Is the "$65 statement credit" new-Executive-plus-new-card offer [S4: since 13 Jan 2025, for new members or memberships expired more than 18 months] still running in October?
7. **Tires.** The current promotions with dates [S6: Bridgestone and Firestone to Oct 4; Michelin and BFGoodrich Sept 28–Nov 1, 2026]. Which are live on 4 Oct? Capture the road-hazard warranty terms page.
8. **Price adjustment and costco.ca vs warehouse.**
   - Any change since May? Open the costco.ca-orders answer (a_id 1017251) and "Why is there a difference between warehouse prices and Costco.ca prices?" (a_id 1017385).
   - Status of the proposed class action *El Bechara v. Costco Wholesale Canada* in Federal Court: certified, or still an allegation?
9. **Returns.** Has Costco Canada added restrictions since May? S1 says "Costco may in the future restrict its return policy… Restrictions will be shown at the point of purchase."
10. **Entry scanners and food court.**
    - National status of entry scanners in Canada in 2026 (CBC listed four markets in Aug 2024).
    - Food-court membership enforcement beyond downtown Vancouver.
    - The 2026 combo change (bottled-water option), which the Caught video asserted; source it.
11. **Tariffs.** Did Costco say anything on the Q4 call about tariff refunds or Canadian pricing? A Yahoo headline today reads "Costco Q4 2026 earnings beat expectations on tariff refund"; open the transcript.
12. **Sales tax on the fee by province.** GST/HST/QST/PST rates applied to a membership fee, from CRA and Revenu Québec, so the break-even can be shown with tax.
13. **Regulators since May.** Any Competition Bureau, OPC Québec or FCAC action naming Costco Canada or the CIBC Costco card? FCAC covers the card's disclosures.
14. **Statistics Canada.** Latest food-from-stores CPI. The August release came out in September; the September release (about 21 Oct) falls after posting, so state the month.
15. **Auto-renewal.** Any Canadian rule or case on Costco auto-renewal? The U.S. class action is U.S.-only (research_costco_caught.md 2.3.3); keep it out.
16. **Gas price gap.** Is any dated, sourced Canadian comparison of Costco pump prices available at tier (a)/(b)/(d)? If not, the redo must not state a c/L gap.
17. **Shop Card.** Does Costco Canada require non-members to take a one-day pass? Open the full Shop Card FAQ; the search summary says so, S14 does not.
18. **Visa on costco.ca.** Does costco.ca accept Visa for online orders? Commenters say yes; open the payment-methods page.

---

## 5. Recommended skeleton for the redo

### 5a. Targets, title, thumbnail

- **Length.** 21,000–23,000 characters of plain spoken prose. At the channel's 5.9–6.15 c/w, that is about 3,550–3,800 words. The skeleton below is 3,625 words: about 21,750 characters at 6.0 c/w, or 22,290 at 6.15.
- **If a draft runs at 6.3 c/w,** cut 30 words each from #5, #6 and the turn.
- **Run time.** About 22.5–23.5 minutes at 155–161 wpm.

**Title.** Use the construction of the 236K video, with the one change a returning viewer needs to see:

> Don't Renew Your Costco CANADIAN Membership Until You Watch This (October 2026)

- Alternative, identical to the hit: "Don't Renew Your Costco CANADIAN Membership Until You Watch This".
- If a month tag is used, spell it correctly ("SETEMPBER" is on the flop).
- Do not add "secrets", "caught", "exposed" or "in trouble".

**Thumbnail.** Do not use the "EXCLUSIVE / IN TROUBLE / caution tape / news camera" template; it implies an incident or wrongdoing (rule 6). Instead use a photographed renewal notice or membership card with three callouts quoted from Costco's own pages:
- "$65 / $130 (plus applicable taxes)" (S1);
- "2% … not … gas stations" (S1);
- "not guaranteed to be equal to or greater than the Executive upgrade fee" (S2).

A stamped "RENEW?" with a question mark is acceptable because it describes the viewer's decision, not Costco's conduct. Do not show a CIBC logo unless CIBC's trademark rules allow it. Show no product the video does not discuss.

### 5b. Order basis, stated in the open and as a lower-third on every item

"Ten things, in the order your membership year happens to you: the renewal charge, the upgrade, what counts, when it's counted, how you pay, what happens after you buy, and what happens if you want out."

- **Why this basis:** it is checkable against Costco's own terms (S1 runs in roughly this order). It needs no ranking data the channel does not have. It lands the refund item (#9) and the company's renewal number (#10) right before the turn to "who should renew".
- **Lower-third on each item:** "#N of 10 · [document name] · costco.ca / cibc.com / SEC · checked [date]".

### 5c. Eligibility for a slot

A slot needs a rule or number printed in a tier (a) document: Costco's terms or customer-service pages, CIBC's published terms, or Costco's SEC filings. It must be opened and captured on screen with the date.

A named outlet (b) may add a date or reaction but never carries the slot alone. Nothing from YouTube, forums, deal blogs or "insiders" may be used. No health or pharmacy or optical item, and no food-safety or recall item. No supplier claims.

### 5d. Jobs in every item (fixed order)

| # | Job | Words |
|---|---|---|
| 1 | Bridge + lower-third: number, the document, the date checked | 10–15 |
| 2 | The rule, read verbatim off the page (on screen) | 40–80 |
| 3 | What it means in dollars: arithmetic shown on screen, inputs labelled | 40–90 |
| 4 | What changed since May, or what the May video got wrong (only where true; see 5h) | 0–40 |
| 5 | Concession: what the rule does in the member's favour, in Costco's or CIBC's words | 15–35 |
| 6 | The one action before you pay | 15–30 |
| 7 | Closer: one line, no "hidden/quietly/secret" | 10–15 |

### 5e. Word budgets and positions

| # | Beat | Words | Starts at word | Start % |
|---|---|---|---|---|
| 1 | Cold open (dated fact) | 150 | 0 | 0.0% |
| 2 | Method + order basis + May acknowledgement + disclosure | 110 | 150 | 4.1% |
| 3 | #1 The renewal charge: how much, when, on what card | 270 | 260 | 7.2% |
| 4 | #2 The Executive upgrade: $65, prorated, "not guaranteed" | 260 | 530 | 14.6% |
| 5 | #3 What the 2% does not count | 300 | 790 | 21.8% |
| 6 | #4 The $1,250 cap, the three-month cut-off, the coupon | 260 | 1,090 | 30.1% |
| 7 | #5 The co-branded card is a separate deal (CIBC terms) | 340 | 1,350 | 37.2% |
| 8 | #6 Price drops: the 30-day adjustment; warehouse vs costco.ca | 280 | 1,690 | 46.6% |
| 9 | #7 Returns: the guarantee and its written exceptions | 270 | 1,970 | 54.3% |
| 10 | Mid-list ask (the only mid-list ask) | 50 | 2,240 | 61.8% |
| 11 | #8 What is bundled: 2-year electronics extension; the tire package | 250 | 2,290 | 63.2% |
| 12 | #9 The membership-fee refund itself | 250 | 2,540 | 70.1% |
| 13 | #10 Costco's own numbers on who renews | 190 | 2,790 | 77.0% |
| 14 | Turn: who should renew and who shouldn't (arithmetic) | 320 | 2,980 | 82.2% |
| 15 | How to protect yourself (four steps) | 200 | 3,300 | 91.0% |
| 16 | Moral + comment ask + tagline (second use) | 80 | 3,500 | 96.6% |
| 17 | Disclaimer | 45 | 3,580 | 98.8% |
| | Total | 3,625 | | |

The ask starts at word 2,240 of 3,625 (61.8%); at an even c/w that is about 13,440 of 21,750 characters, also 61.8%.

Measure the finished draft in characters. If the ask falls outside 61–63%, move words between #2 and #8. Never move them into the ask.

### 5f. Cold open (about 150 w) and method beat (110 w)

**Cold open, six moves (a draft of about 150 words is below):**
1. A dated fact, first sentence, from S18: on 24 Sep 2026 Costco reported US$5.907 billion in membership fees for fiscal 2026. Label it "company-wide, all countries" (rule 7).
2. The Canadian line from the same document: 115 warehouses in Canada. Costco does not say how much of the fee came from Canada.
3. The viewer's moment: the renewal month.
4. The method: the terms page dated August 1st, 2026, and the bank's card terms, read line by line.
5. Count and order basis.
6. Tagline, first of two uses.

Draft (about 150 w):

"On September 24th, 2026, Costco told its shareholders it collected five point nine billion U.S. dollars in membership fees in the year that had just ended. That's every country combined; Costco doesn't break out how much of it came from Canada. The same filing counts 115 warehouses here. If your card renews this fall, your sixty-five or hundred and thirty dollars is about to be part of next year's number. So before it charges again, we read the rules you agree to when you pay: Costco Canada's membership terms, the version dated August 1st, 2026, line by line, plus the bank's terms for the card that doubles as your membership card. Ten things in them every member should know before renewing, in the order your membership year happens. Then the arithmetic on who should renew, and who shouldn't. Because the truth is not always on the menu."

- Confirm the US$5.907B and 115 figures against the 8-K PDF itself before recording; they were read through a fetch summary today.
- No ask in the open, no "secret", no health word.

**Method beat (110 w):**
- State the order basis (5b).
- The May acknowledgement, said plainly. Draft: "In May we made a video with this same title. Since then Costco re-dated its terms, and parts of what we said then we can't stand behind: the price-tag codes, the lists of who makes Kirkland, and the idea that the Executive reward counts at the gas pump. It doesn't. This video replaces it."
- The disclosure, spoken once, here only: "We have no commercial relationship with Costco, CIBC or any company named in this video, and none of them knew it was being made."

### 5g. The ten items, with the documented material each turns on

**#1 The renewal charge (270 w).** Source: S1.
- Fees: "$65 (plus applicable taxes)" and "$130 (plus applicable taxes)" per 12-month period from enrollment.
- If not on auto-renew, the fee "will be charged on your first shop of your renewal month". Auto-renew charges "on the first day of your renewal month", on "any Mastercard® credit card or Visa credit or debit card".
- Renewing "within 2 months after expiration" extends from the expiration date. Renewing later extends from the renewal date.
- "All renewals will be at the membership fee in effect on the date the membership fee is paid."
- Last change: effective 1 Sep 2024, $60 → $65 and $120 → $130 (research_costco_caught.md 3.1, Costco press release 10 Jul 2024; re-open before quoting).
- Concession: one change in about nine years. Action: find your renewal month on your account.
- Closer: the month matters more than the day.
- What changed since May: May said the fee is pulled from "your credit card"; that applies only on auto-renew.

**#2 The Executive upgrade (260 w).** Sources: S2, S3, S13.
- "an additional $65", prorated on the months remaining.
- "Purchases made prior to upgrade do not qualify for the 2% Reward."
- The sentence to read slowly (S2): "The Reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid."
- Arithmetic: $65 ÷ 2% = $3,250 a year of qualifying spending, $270.83 a month, before tax on the fee.
- "Limit of one Executive Membership per business or household" (S1).
- Concession: the reward runs on most merchandise in warehouses in Canada and the U.S. and on costco.ca, plus Costco Travel (S1).
- Closer: Costco's own page says the 2% may not cover the $65.
- Do not repeat the U.S. "refund the difference" line (FRUGAL PRO).

**#3 What the 2% does not count (300 w).** Source: S1, read as the verbatim list.
- Tobacco.
- Anything not through the front-end registers: "services, purchases at Costco Wholesale's gas stations, food courts, optical centres (Quebec only), and pharmacies".
- Membership fees; fees, deposits and taxes; services "including auto"; and "certain other categories as determined from time to time at Costco Wholesale's sole discretion".
- What changed since May, verbatim: "In May we told you the Executive 2% stacks at the gas bar. Costco's terms say rewards are not calculated on purchases at its gas stations."
- Concession: the list is published, and Costco links an exclusions list (S3); show it once it is captured (U-list).
- Action: take your gas, pharmacy and food-court spending off before you do the math.
- Note: the pharmacy is named only because the term names it. Say nothing about prescriptions.
- Closer: the biggest line on most members' Costco statements may not count.

**#4 The cap, the cut-off, the coupon (260 w).** Source: S1.
- "capped at, and will not exceed, $1,250"; that is $62,500 of qualifying spending (arithmetic).
- The calculation period ends "approximately three months prior to the member's renewal date"; "Purchases from the last three months will be added to the following year's Reward calculation."
- The coupon is "mailed with membership renewal notices", is redeemable only by the Primary, and only "at Costco Wholesale warehouses throughout Canada". It is not valid "at … gas stations, food courts, optical centres (Quebec only), pharmacies and online at Costco.ca"; "Reward coupons will not be replaced if lost or stolen".
- Forfeiture: Executives who downgrade or "cancel their membership and receive a refund … will not receive a Reward."
- Concession: purchases are not lost in the lag; they roll to next year.
- Action: decide on the upgrade or downgrade before the cut-off, not at the till.
- Closer: the coupon arrives with the bill.

**#5 The co-branded card (340 w).** Sources: S4, S5, S15, S16/S17.
- Issuer: CIBC since March 4, 2022 (S15). Before that Capital One; American Express ended on Dec. 31, 2014 (S16).
- Earn rates (S4 fine print):
  - 3% at Costco gas in Canada and 2% at other gas and EV charging, on the first $5,000 combined, then 1%;
  - 2% on costco.ca on the first $8,000, then 1%;
  - 3% at restaurants;
  - 1% on everything else, "including at Costco" (S5).
- The certificate comes "once per calendar year in January", redeemable at Canadian warehouses. The card "is also your Costco membership card" (S5). "Annual fee $0" (S5).
- The two programs differ: the card year runs January to December; the Executive year runs to about three months before your renewal.
- What changed since May: May put an $8,000 cap on restaurants. On the personal card that cap does not appear; it is on the Business card.
- Current offer (S4), if still live on air day: a $65 statement credit for new Executive members, or memberships "expired for more than 18 months", who are approved for a new card the same day and spend $65 in 120 days. Upgrades do not qualify.
- Concession: no annual fee.
- Action: the card is a credit product; read its interest rate before using it to "stack". Do not state a rate; it did not render on S5.
- Closer: two rewards, two calendars, two sets of exclusions.

**#6 Price drops (280 w).** Sources: S11, S19 titles.
- Verbatim S11: "We will honour price adjustment requests for purchases made in-warehouse within 30 days from the date of purchase. The item must be in stock (excluding demonstration merchandise) and within the valid promotional dates when requesting a price adjustment."
- costco.ca orders have their own policy (a_id 1017251; capture it, U-list).
- Costco also has an answer titled "Why is there a difference between warehouse prices and Costco.ca prices?" (a_id 1017385; capture it).
- Optional, only if status is re-checked: the proposed class action over online vs warehouse prices, labelled "an allegation; not certified" (research_costco_caught.md 2.1).
- What changed since May: May left out the "in stock" and "valid promotional dates" conditions.
- Concession: you don't return the item.
- Action: keep the receipt or the account entry, and check within 30 days.
- Closer: thirty days, in stock, in the promo window.

**#7 Returns (270 w).** Sources: S1, S12.
- "We guarantee your satisfaction on every product we sell, and will refund your purchase price*, with the following exceptions":
  - electronics 90 days (read the list);
  - diamonds of 1.00 ct+ need the original IGI/GIA paperwork and "approximately 2 to 5 business days";
  - cigarettes and alcohol "where prohibited by law";
  - tires and batteries "may be sold with a product-specific limited warranty";
  - custom installs;
  - gold and silver bullion; e-certificates; gift cards and tickets.
- And: "Costco may in the future restrict its return policy… Restrictions will be shown at the point of purchase."
- Termination power: "without cause, as well as for … abuse of your membership privileges" (S1).
- Concession: no general time limit.
- Action: read the restriction at the point of purchase.
- Closer: the guarantee is wide, and it is written down, exceptions included.
- No "no receipt needed" line (U).

**Mid-list ask (50 w), at 61–63% of characters.** Draft:

"Three left, and the last one is the number Costco itself reports. If you'd rather have the fine print read for you before the next bill lands, take a second to subscribe. Canadian Counter reads the documents, so you don't have to. Number eight."

- It must contain "take a second to subscribe".
- No like ask; no share ask.

**#8 What is bundled (250 w).** Sources: S9, S10, S6.
- Electronics: "Costco extends the manufacturer's warranty to two (2) years from the date of purchase" for "televisions, projectors, major appliances, and computers (excluding tablets)", with free phone support "during opening hours", English and French, 1-866-231-9731. The service is now called "Costco Technical and Warranty Service"; May called it Concierge.
- Tires (S6): "Tire purchase includes installation at No charge", "5 year road hazard warranty, Rotation and Balancing, Flat repairs, Nitrogen tire Inflation", and "Additional component costs, including TPMS service pack fees, may apply."
- The dated promotions live on air day, with brand, amount and dates read off the page. Do not show competitor installation prices.
- Concession and action: check your tire size against the page before you book anywhere.
- Closer: bundled is not the same as free; read the line that says what's extra.

**#9 The membership-fee refund (250 w).** Sources: S1, S2, S12.
- Read all three wordings and say which page each is from:
  - terms (S1): "We will cancel and refund your membership fee at any time if you are dissatisfied."
  - join page (S2): "We will cancel and refund your membership at any time if you are dissatisfied."
  - customer-service page (S12): "We will refund your membership fee in full at any time if you are dissatisfied."
- The Executive consequence: no Reward if you cancel and take the refund (S1).
- Do not coach "shop 11 months, then cancel"; S1 lets Costco terminate for "abuse".
- Concession: it is a real, written guarantee.
- Action: if your receipts say no, this is the exit.
- Closer: the guarantee is how you test the fee, not how you game it.

**#10 Costco's own numbers on who renews (190 w).**
- Sources: S18 (115 warehouses in Canada; fee income) plus the FY2025 10-K / Q4 FY2026 release or call for the renewal rate. FY2025: "92.3% in the U.S. and Canada"; research_costco_caught.md 3.7. Re-open the current figure before use.
- Rule 7 line, verbatim: "That's the U.S. and Canada together; Costco doesn't publish a Canada-only rate."
- Executive share of worldwide sales (FY2025 10-K: "approximately 73.6% of worldwide net sales").
- Concession: very few subscriptions keep nine in ten.
- Closer: almost everyone renews; this video is about whether you should.

### 5h. The turn: who should renew and who shouldn't (320 w)

Open: "Here's the arithmetic, with Costco's numbers and yours."

- **Gold Star ($65 plus tax).** Renew if your own receipts show savings on what you actually buy that beat the fee. Costco's guarantee (#9) lets you test that. Do not use Broken Canada's $100/$300 thresholds; they are invented.
- **Executive upgrade (+$65 plus tax).** Pays only above $3,250 a year ($270.83 a month) of qualifying, pre-tax purchases. Worked on screen:
  - $400 a month = $4,800 a year → $96 reward → $31 ahead of the fee before tax.
  - $200 a month = $2,400 → $48 → $17 behind.
  - With tax on the upgrade fee, the break-even rises: for example, at a 13% rate, $65 × 1.13 = $73.45 → $3,672.50 a year. Use the CRA/Revenu Québec rate by province, sourced (U-list); show one province on screen and say "check your province".
- **Who should not upgrade:** members whose Costco spending is mostly gas, pharmacy or food court, since those count zero (#3), or who spend under about $270 a month at the registers.
- **The card is separate:**
  - 1% on in-warehouse spending: $48 on $4,800.
  - 3% at Costco gas up to the $5,000 combined gas cap: at most $150 a year.
  - No annual fee.
  - It does not change the Executive arithmetic.
- **The cap:** $1,250 needs $62,500 of qualifying spending.

Close the turn: "If the numbers say no, the refund in number nine is in writing."

### 5i. How to protect yourself (200 w). Four steps: "First," "Second," "Third," "Fourth"

- **First, check your actual annual spend on your Costco receipts or your costco.ca account.** Take out gas, pharmacy, food court, tobacco, taxes and fees, because the 2% doesn't count them (S1).
- **Second, do the 2% Executive math.** Qualifying spend × 2%, minus $65 plus your province's tax. Below $3,250 a year, Gold Star wins. Mind the three-month cut-off before renewal and the $1,250 cap (S1, S2).
- **Third, compare unit prices with your usual grocer.**
  - Use the shelf tag's unit price on the same day for the items you actually buy, and write down the store and the date.
  - Do it outside the warehouse: S1 says "recording of prices in any manner is not permitted" on Costco premises. Use costco.ca and your own receipts instead.
  - Rule 5: say this as a method, and show no competitor price unless it is captured from the retailer's own site with banner, store, date, pack and unit price.
- **Fourth, know the refund policy.** The fee guarantee (S1/S12) and the merchandise exceptions (S1), including that an Executive who cancels with a refund forfeits the Reward.

### 5j. Moral, comment ask, tagline (80 w)

- **Moral:** "Costco's terms are long, and they're printed. The renewal is the one purchase you make there where the price is the same for everyone and the value isn't."
- **Comment ask, framed as the viewer's own data:** "Check your last reward coupon or your account and tell us in the comments: Gold Star or Executive, roughly what you spent at the registers last year, and which province. We'll do the arithmetic for a few of you."
- **Tagline, second and last use:** "Because the truth is not always on the menu."

### 5k. Disclaimer (about 45 w), spoken last and shown on screen

"Everything in this video comes from Costco Canada's membership terms and customer-service pages, CIBC's published card terms and Costco's filings with the U.S. Securities and Exchange Commission, checked on [date]. Fees, rewards and offers change and vary by province. Read your own renewal notice."

That is 45 words. Do not add "Not sponsored"; the disclosure in 5f is the single use.

### 5l. Vocabulary rules for the body

- **Never use:** secret, hidden, quietly, loophole, trick, hack, insider, "former employees", "employees say", exposed, caught, trouble, scam, racket, rigged, healthy, health, medication, prescription (except where the terms list "pharmacies"), safe, safety, cleaner engine, recall.
- **Every Costco rule is "Costco's terms say" / "Costco's page says".** Every card figure is "CIBC's terms say".
- **Every combined figure is labelled** "U.S. and Canada together" or "all countries"; U.S. dollars are said as U.S. dollars.
- **No supplier claims about Kirkland.**
- **No gas-price gap.**
- **No rotisserie chicken price.**
- **No competitor price** unless captured per rule 5.
- **Legal items:** label as allegation, finding, settlement or order. The proposed class action, if used, is "an allegation; not certified".

---

## 6. UNVERIFIED / DO-NOT-USE

### 6a. Could not be opened or not fully verified this session

| # | Item | What happened | Action |
|---|---|---|---|
| U1 | Any archived pre-August 2026 copy of the membership terms (to show what changed since May 13) | archive.org returned 429 and the CDX endpoint was "Blocked by egress policy" (1 Oct 2026) | Researchers to obtain; until then say only "the page is dated August 1, 2026" |
| U2 | Customer-service pages S9–S14, S19 | curl returned HTTP 401; read through WebFetch summaries only | Screen-capture each page verbatim before quoting |
| U3 | U.S.-and-Canada renewal rate at FY2026 year-end (92.3%), paid members (84.1M), Executive members (42.3M) | Search-result summaries only; the 8-K (S18) did not show a renewal rate; the Fool transcript (2026/09/29) was not opened | Open the transcript or 10-K before use |
| U4 | Canada comparable-sales adjustment definition (S18) | Read via fetch summary | Quote from the 8-K text |
| U5 | CIBC personal-card interest rates | S5 shows unresolved template placeholders | Do not state a rate |
| U6 | The "Annual 2% Reward Exclusions List" linked from S3 | Not opened | Capture before #3 |
| U7 | Shop Card one-day pass for non-members | Search summary only; S14 does not say it | Do not say it |
| U8 | Price adjustment for costco.ca orders (a_id 1017251) and the warehouse vs costco.ca price answer (a_id 1017385) | Search snippet only | Capture |
| U9 | Visa on costco.ca for online orders | Comments only | Capture the payment-methods page |
| U10 | Gas stations members-only and card scan at the pump | Not on pages opened | Capture or drop |
| U11 | Tire road-hazard pro-rating terms | Not opened | Capture or drop |
| U12 | Provincial sales-tax rates on the fee | Not opened (CRA / Revenu Québec) | Source before showing |
| U13 | El Bechara proposed class action, current status | Not re-checked since the Caught dossier | Re-check, or leave out |
| U14 | Starbucks custom-roast statement on costco.ca coffee listings | Not re-opened today | Not needed in this script |
| U15 | Executive early-hours in Canadian warehouses in Oct 2026 | Dossier cites Axios and Nasdaq (U.S. / tier c) and Daily Hive | Do not state hours without a costco.ca page |
| U16 | The fee-change history before 2024 (2017: $55 → $60) | CBC 2017 per research_costco_buyskip.md; not re-opened | Re-open if used |
| U17 | costcopharmacy.ca and costco.ca/pharmacy.html | Returned 31-character shells | Barred topic anyway |

### 6b. DO-NOT-USE (any channel, including our May video)

- **Price-tag codes** (asterisk, .97, .88/.00, .49/.79/.89, "death star", date codes): unconfirmed lore, "former employees" / "insiders", U.S. deal blogs. (May R4; NACR #7.)
- **All Kirkland supplier claims:** Duracell batteries (Jelinek / WSB-TV 2016, U.S.), Alexander Murray Scotch, Reynolds foil, Kimberly-Clark/Huggies diapers, Bumble Bee tuna, Grey Goose vodka, Jelly Belly, "specification drift", reformulated "Canadian bacon", mixed-nut ratios, detergent supply changes. (May R6; NACR #6; FRUGAL PRO #8; Broken Canada.)
- **Pharmacy, optical and hearing-aid items of any kind:** non-member access, "provincial pharmacy law", generic pricing, "up to 80%", eye exams, glasses, hearing-aid prices, the "16% of the US hearing aid market". Rule 1 (health), and largely U.S.
- **Gas-price gap claims:** "5 to 15 cents", Narcity's "$244", "2 cents within 2 km", GasBuddy.
- **Fuel-effect claims beyond Costco's own words:** "better fuel efficiency", "fewer maintenance issues", "cleaner engines".
- **"The Executive 2% counts at the gas bar"** (May s187, s214): contradicted by S1.
- **"3% restaurants on the first $8,000"** for the personal card (May s180): the $8,000 restaurant cap is the Business card's (S4).
- **"Costco refunds the difference if the 2% doesn't cover the upgrade":** U.S. lore; Canada's page says "not guaranteed" (S2).
- **Coaching a refund play** ("shop 11 months, cancel in month 12", "join before Christmas, refund in January"): S1 allows termination for abuse; not house style.
- **Promo-code "membership reset" and letting a membership lapse 18 months** (NACR #2; RedFlagDeals; "Costco65"): tier (c). The only documented new-member offer is CIBC's on S4; use that or nothing.
- **Broken Canada's figures:** $104/$136 fees; "$60 in 2009 … 73%"; "14 million card holders"; "14% margin cap"; "Walmart 24%"; "70% of profit"; "Dalhousie 2023 price audit"; "2019 study … $40 to $60 unplanned"; "Costco USA $8 vs Canada $11 margin"; "prices up 18–31% 2019–2024"; "fee up 12%"; Amazon Subscribe & Save 5–15%; No Frills/FreshCo olive oil prices. All unsourced or wrong.
- **FRUGAL PRO and Frugal Flow U.S. content:** Citi Visa 4%/5% gas; "$1.50 hot dog since 1985" with the "I will kill you" quote (U.S. anecdote; unverified here); "$30 billion Kirkland"; Nebraska poultry plant; J.D. Power; Costco Travel shop cards; face-match scanning; ADA service dogs; gold-bar limits; "147.2 million"; "350,000 pizzas". U.S. or unsourced.
- **Rotisserie chicken price** ($7.99, $4.99, $9): no costco.ca price exists (rule 5); keep it out of the script and the thumbnail.
- **Any Canadian member count** ("10 million", "14 million"): not published by Costco.
- **The 92.1% / 92.3% renewal rate as "Canadian" or "you":** it is U.S. and Canada combined.
- **Thumbnail claims:** "EXCLUSIVE", "IN TROUBLE", caution tape, news cameras, "HAS BEEN CAUGHT" (rule 6).
- **Recalls:** none are needed for this script. If any recall notice is raised in research, it is a food-safety item: appendix only, do not use on air.
- **Competitor service prices** (Best Buy warranties "$100–200", Canadian Tire "line items", "20% in services"): no retailer-own source.

<!-- ===== costco_membership_terms.md ===== -->

# Costco Canada membership: documented facts as of 1 October 2026

**Compiled:** 1 Oct 2026. Every source below was opened on 1 Oct 2026 unless the source log says otherwise.
**Scope:** Costco Wholesale Canada Ltd. membership terms (costco.ca), plus Costco Wholesale Corporation (Nasdaq: COST) SEC disclosures that cover Canada.
**Order:** tier (a) primary sources first (sections A1 to A14), then tier (b) named outlets (B), then tier (c) items that are flagged only (C), legal items (D), the recalls appendix (E), the source log (F), and the mandatory UNVERIFIED / DO-NOT-USE section.

**How the pages were read**
- **curl:** costco.ca, sec.gov, cibc.com, sameday.costco.ca, globalnews.ca, cbc.ca, ctvnews.ca and newswire.ca were downloaded raw with curl and their text was extracted.
- **WF (WebFetch):** `customerservice.costco.ca` returned **HTTP 401** to curl. Those pages were read through WebFetch, which passes the page through a summarising model. Quotes taken this way are marked **[WF]**. Check them character-for-character against the live page before broadcast.
- **Currency:** Costco's SEC filings report in **US dollars (millions)**. costco.ca prices are in **Canadian dollars**. Costco's own 2017 and 2024 fee announcements give one figure ("$65", "$130") for "U.S. and Canada", meaning each country's local currency.
- **House rules applied:**
  - No health, nutrition or food-safety claims appear in the body of this file.
  - Recalls appear only in the appendix (section E).
  - Corporate claims are attributed.
  - U.S., Canadian and combined figures are labelled.

---

## A. TIER (a): PRIMARY SOURCES

### A1. Current Canadian membership tiers and prices (costco.ca, 1 Oct 2026)

| Tier (costco.ca naming) | Annual fee (CAD) | Per month (computed: fee ÷ 12) | Cards included | Source |
|---|---|---|---|---|
| Gold Star (personal) | **$65** "Plus applicable sales tax" | $5.42 | Primary + 1 Household card | join-costco.html; membership-conditions-regulations.html |
| Business ("Business Value" on the join page) | **$65** "Plus applicable sales tax" | $5.42 | Primary + 1 Household card; Affiliates can be added | same |
| Business Affiliate (add-on) | **$65 each**, "up to 6 Affiliates" | $5.42 | Each Affiliate also gets a Household card "at no additional cost" | membership-conditions-regulations.html |
| Executive (personal or business) | **$130** "Plus applicable sales tax" | $10.83 | Primary + Household card | same |
| Executive upgrade (from Gold Star/Business) | **+$65/yr**, prorated | — | — | join-costco.html; executive-rewards.html |

Notes: banner = Costco Wholesale Canada (costco.ca), region = Canada (national online price list), viewed 1 Oct 2026. The page footer reads "© 2005 — 2026 Costco Wholesale Canada Ltd." and "Built At: 10/1/2026".

**Verbatim, Membership Conditions & Regulations (page dated "August 1, 2026")**, https://www.costco.ca/membership-conditions-regulations.html:
> "Gold Star Membership fee is $65 (plus applicable taxes) per 12-month period from the date of enrollment of the Primary cardholder. This entitles the Primary cardholder to one personalized membership card and one Household card."

> "Business Membership fee is $65 (plus applicable taxes) per 12-month period from the date of enrollment of the Primary cardholder. This entitles the Primary cardholder to one personalized membership card and one Household card. Each Primary member may name up to 6 Affiliates for $65 each and corresponding Household cardholders at no additional cost."

> "Executive Membership is $130 (plus applicable taxes) per 12-month period from the date of enrollment of the Primary cardholder. This entitles the Primary cardholder to one personalized membership card and Household card. If upgrading from a Gold Star Membership or Business Membership, upgrade amount will be prorated based on the months remaining on your current membership. Affiliate cardholders on an existing Business Membership account that is being upgraded can choose to remain as Affiliates or purchase a Gold Star or Executive Membership on their own."

> "Limit of one Executive Membership per business or household."

> "Membership is available to qualifying individuals 16 years of age or older."

> "A Canadian federal or provincial government-issued ID must be presented at a warehouse Membership Counter when applying for a Costco membership. We do not record government ID numbers of Gold Star members."

**Verbatim, Join page**, https://www.costco.ca/join-costco.html:
> "The Executive Membership upgrade fee is an additional $65 a year for Business or Gold Star Members (plus sales tax where applicable). We will prorate the upgrade amount based on the months remaining in your current membership. Purchases made prior to upgrading are not eligible for the 2% Reward. At your next renewal, you will be billed $130 for your Executive Membership. To upgrade, visit the membership counter at any Costco warehouse."

**Executive-only extras listed on costco.ca (1 Oct 2026):**
- Annual 2% Reward.
- "$10 Monthly Credit on Same-Day or Costco via Instacart".
- "Costco Services Discounts".
- "NEW! Online Wills Exclusively for Executive Members".
- "Costco Connection magazine by mail".

The Instacart credit terms are verbatim on the join page:
> "As a valid Costco Executive member card holder, you can receive one (1) $10 CAD instant credit in your Instacart account to use at either Costco on Instacart's marketplace or SameDay.Costco.ca (collectively, the "Eligible Accounts") each month you have a valid Costco Executive membership that is linked to your Instacart account starting 6/30/2025. Each monthly credit is only eligible on one (1) purchase of $150 CAD or more of eligible products ... Alcohol, Rx, and gift card products are ineligible to count toward the minimum spend and credit will not apply to alcohol, Rx or gift card products. ... Instacart and/or Costco reserves the right to modify or cancel this offer at any time."

**New-member CIBC offer on costco.ca** (https://www.costco.ca/cibc-executive-offer.html):
> "Get $65 back when you apply and are approved for a CIBC Costco Mastercard or CIBC Costco Business Mastercard with your new Executive Membership."

The terms add:
> "This offer is only for new Costco members or Costco memberships that have been expired for more than 18 months. Beginning January 13, 2025 ... Membership upgrades, or the purchase of a new Costco Executive Memberships by an existing Costco member, do not qualify for this offer."

Computed, not Costco statements:
- At 2%, qualifying spend of **$3,250/yr** produces a Reward equal to the $65 upgrade fee.
- The $1,250 cap is reached at **$62,500** of qualifying spend.

Costco itself says (join-costco.html): "The Reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid."

---

### A2. Fee history in Canada (Costco SEC filings)

| Effective date | Change (U.S. and Canada unless stated) | Reward cap change | Verbatim source |
|---|---|---|---|
| Apr 1, 1998 (U.S.); **May 1, 1998 (Canada)** | "+$5" for Business and Gold Star | — | FY2000 10-K: "a five dollar increase in the annual membership fee for both Business and Gold Star members effective April 1, 1998 in the United States and May 1, 1998 in Canada." https://www.sec.gov/Archives/edgar/data/909832/000089102000002053/v67051e10-k405.txt |
| Sep 1, 2000 | "averaging approximately $5 per member" (company-wide; no Canada-specific amounts given) | — | FY2000 10-K: "Effective September 1, 2000 the Company has increased annual membership fees for its Gold Star (individual), Business, and Business Add-on Members." (same URL) |
| **May 1, 2006 (new) / Jul 1, 2006 (renewals)** | Gold Star, Business, Business Add-on +$5, to $50 (FY2006/07 10-Ks state $50). Executive $100. | Cap $500 | FY2006 10-K: "We increased annual membership fees by $5 for our U.S. and Canada Gold Star (individual), Business, and Business Add-on Members, effective May 1, 2006, for new members and July 1, 2006, for existing members". https://www.sec.gov/Archives/edgar/data/909832/000119312506238399/d10k.htm |
| **Nov 1, 2011 (new) / Jan 1, 2012 (renewals)** | **Canada Business** to $55 (Canada Gold Star *not listed*). U.S. and Canada Executive $100 → $110. | $500 → $750 | FY2012 10-K: "Effective November 1, 2011, for new members, and January 1, 2012, for renewing members, we increased our annual membership fee by $5 for U.S. Goldstar (individual), Business, Business Add-on and Canada Business members to $55. Our U.S. and Canada Executive Membership annual fee increased from $100 to $110 annually and the Executive Membership 2% reward annual limit increased from $500 to $750." https://www.sec.gov/Archives/edgar/data/909832/000119312512428890/d388097d10k.htm |
| (by FY2014 10-K) | Canada fee stated as $55 | — | FY2014 10-K: "Our annual fee for these memberships is $55 in our U.S. and Canadian operations". https://www.sec.gov/Archives/edgar/data/909832/000090983214000021/cost10k2014.htm. The date Canada Gold Star moved to $55 was not found (see UNVERIFIED). |
| **Jun 1, 2017** | Gold Star, Business, Business add-on +$5 to **$60**. Executive $110 → **$120** ($60 + $60 upgrade). | $750 → **$1,000** | FY2017 10-K: "Effective June 1, 2017, we increased our annual membership fees in the U.S. and Canada for Gold Star (individual), Business and Business add-on by $5 to $60 per year. The Executive membership fee increased from $110 to $120 (annual membership fee of $60, plus Executive upgrade of $60), and the maximum annual 2% reward, which is earned on qualified purchases and can be redeemed only at Costco warehouses, increased from $750 to $1,000." https://www.sec.gov/Archives/edgar/data/909832/000090983217000014/cost10k90317.htm |
| **Sep 1, 2024** (announced Jul 10, 2024) | Gold Star, Business, Business add-on +$5 to **$65**. Executive $120 → **$130** ($65 + $65). | $1,000 → **$1,250** | 8-K Ex. 99.1, Jul 10, 2024 (verbatim below) |

**Verbatim, 8-K Exhibit 99.1, July 10, 2024**, https://www.sec.gov/Archives/edgar/data/909832/000090983224000036/costex9918-k71024.htm:
> "The Company also announced that, effective September 1, 2024, it will increase annual membership fees by $5 for U.S. and Canada Gold Star (individual), Business, and Business add-on members. With this increase, all U.S. and Canada Gold Star, Business and Business add-on members will pay an annual fee of $65. Also effective September 1, annual fees for Executive Memberships in the U.S. and Canada will increase from $120 to $130 (Primary membership of $65, plus the Executive upgrade of $65), and the maximum annual 2% Reward associated with the Executive Membership will increase from $1,000 to $1,250. The fee increases will impact around 52 million memberships, a little over half of which are Executive." *(COMBINED U.S. and Canada figure)*

The same release gives the warehouse count then: "108 in Canada".

**Costco on the effect of the 2024 increase.** These are company-wide figures, USD millions.
- FY2025 10-K: "As previously reported, we increased our annual membership fees in the U.S. and Canada, effective September 1, 2024. ... The fee income increase accounted for approximately 40% of membership income growth during 2025." https://www.sec.gov/Archives/edgar/data/909832/000090983225000101/cost-20250831.htm
- Q3 FY2026 10-Q (12 weeks ended May 10, 2026): "The fee income increase accounted for approximately 25% and 35% of membership income growth during the third quarter and first thirty-six weeks of 2026." https://www.sec.gov/Archives/edgar/data/909832/000090983226000051/cost-20260510.htm
- FY2017 10-K, on the 2017 increase: "These fee increases had a positive impact on membership fee revenues during 2017 of approximately $23 and will positively impact the next several quarters. We expect these increases to positively impact membership fee revenue by approximately $175 in fiscal 2018." (USD millions, company-wide)

---

### A3. Executive 2% Reward (Canada)

| Item | Costco Canada wording (verbatim) | Source |
|---|---|---|
| Rate | "The Reward is approximately 2% of pre-tax purchases of most merchandise including Costco Travel" | membership-conditions-regulations.html; executive-rewards.html |
| Cap (current) | "Calculation of a Reward is capped at, and will not exceed, $1,250 for any 12-month period." | same |
| Cap history | $500 (to 2011) → $750 (Nov 2011/Jan 2012) → $1,000 (Jun 1, 2017) → $1,250 (Sep 1, 2024) | A2 sources |
| Who earns | "Only purchases made by the Primary and Household cardholders are used to calculate the Reward." / "The Household cardholder must be active at the time the Reward is earned and issued." | same |
| Where earned | "will be calculated on purchases by Canadian residents of merchandise through the front-end registers at Costco Wholesale warehouses in Canada and the United States and online at Costco.ca." | same |
| Period | "The period of calculation will run approximately from the date of the member's paid enrollment or upgrade to Executive Membership through the date approximately three months prior to the member's renewal date. Purchases from the last three months will be added to the following year's Reward calculation." | same |
| Issued | "The Executive 2% Reward coupon is mailed approximately 2 months before your membership expiry date along with the membership renewal notice." | executive-rewards.html FAQ |
| Redemption | "Reward coupons may be redeemed by the Primary member toward purchases of most merchandise through the front-end registers at Costco Wholesale warehouses throughout Canada only. Reward coupon may not be redeemed for cash." | membership-conditions-regulations.html |
| Online use | "No, the Executive 2% Reward can only be used for most in-warehouse purchases through the Front-End registers across Canada." | executive-rewards.html FAQ |
| Other limits | "Non-negotiable, not accepted as payment on Costco credit card accounts. Must be a current member to redeem. Not replaceable if lost or stolen. Redeemable only at Costco locations in Canada." | executive-rewards.html; join-costco.html |
| Expiry | Not stated on costco.ca. The parent 10-K (company-wide, "most countries") says the reward "does not expire". FY2025 10-K: "In most countries, the Company's Executive members qualify for a 2% reward on qualified purchases, subject to an annual maximum value, which does not expire and is redeemable at Costco warehouses." | FY2025 10-K |
| Downgrade/refund forfeits | "Executive Members who downgrade to Gold Star or Business status or cancel their membership and receive a refund of their membership fees will not receive a Reward." | membership-conditions-regulations.html |
| Program changes | "Costco Wholesale reserves the right at its discretion to discontinue or change the Reward Program at any time or to disqualify or cancel members' participation." | same |
| vs CIBC rebate | "The 2% Reward is issued by Costco to Executive members only, whereas the CIBC reward is issued by CIBC to any member who has an active CIBC Costco Mastercard." | executive-rewards.html |

**Earning exclusions, verbatim** (https://www.costco.ca/executive-rewards.html, "Annual 2% Reward Exclusions List"):
> "Items that fall into the following categories are not eligible for the 2% Reward. In all provinces: - prescription drugs - all tobacco products (including: cigarette paper, lighters, matches and tubes) - all food court items - all bottle deposits and refunds - all taxes and levies - all Costco Services - eye examinations - tire disposal fees (where applicable) - tire mounting and balancing, and stud installation fees - gift certificates and Costco Shop Cards - membership fees - oil disposal fees (where applicable) - home delivery charges - administration fees - gasoline - charitable donations - third party insurance payments - postage stamps - environmental fees, deposits or levies - other items, products and services specified as exclusions from time to time - all liquid milk and cream items (e.g., 1%, 2%, homogenized and skim milk, chocolate milk, light cream, cream blends, coffee cream, whipping cream, eggnog, buttermilk, concentrated milk, etc. in the provinces of Quebec and Nova Scotia only)"

> "Additional exclusions in the province of Quebec: - all pharmacy items (including analgesics, cough and cold medication, allergy medication, eye care products, antacids, condoms, nicotine replacement therapies, vitamins, minerals, supplements, insulin, etc.) - all optical centre items and services (e.g., eyeglasses, contact lenses, etc.)"

**Calculation exclusions, verbatim** (membership-conditions-regulations.html):
> "Rewards will not be calculated: (i) on purchases of cigarettes or other tobacco-related products; (ii) on purchases that are not recorded through Costco Wholesale's front-end registers, such as services, purchases at Costco Wholesale's gas stations, food courts, optical centres (Quebec only), and pharmacies; (iii) on membership fees; (iv) on miscellaneous fees, deposits and taxes, including applicable sales tax and goods and services tax; (v) on purchases of services, including auto and other services; (vi) on purchases where prohibited by legal or regulatory restrictions; (vii) on certain other categories as determined from time to time at Costco Wholesale's sole discretion; or (viii) on purchases made by anyone other than the Executive Membership account's Primary and Household cardholders."

**Redemption exclusions, verbatim** (same page):
> "Reward coupons may not be used: (i) toward purchases of certain merchandise such as alcoholic beverages, cigarettes or other tobacco-related products; (ii) toward purchases that are not recorded through Costco Wholesale's front-end registers, such as purchases at Costco Wholesale's gas stations, food courts, optical centres (Quebec only), pharmacies and online at Costco.ca and Costcobusinesscentre.ca; (iii) toward purchases of services, including travel, auto and other services; (iv) toward purchases where prohibited by legal or regulatory restrictions; or (v) toward certain other purchases as determined from time to time at Costco Wholesale's discretion."

Note on alcohol: on costco.ca, alcohol appears on the **redemption** exclusions list. It is **not** on the "In all provinces" **earning** exclusions list. Gasoline and tobacco are excluded from earning.

**Costco Travel**, verbatim:
> "For Executive Member purchases made directly from Costco Travel, a 2% Reward (up to $1,250) will be earned on qualified purchases and applied after travel is completed. Must be an Executive Member when travel starts."

---

### A4. Refund/cancellation policy; Executive upgrade and downgrade

Costco publishes three slightly different wordings. Quote the one that matches the page you show.

| Wording (verbatim) | Page | Page date |
|---|---|---|
| "On Membership: We will cancel and refund your membership fee at any time if you are dissatisfied." | membership-conditions-regulations.html | "August 1, 2026" |
| "100% Satisfaction Guarantee — We will cancel and refund your membership at any time if you are dissatisfied" | join-costco.html | viewed 1 Oct 2026 |
| "On Membership: We will refund your membership fee in full if you are dissatisfied." [WF] | customerservice.costco.ca a_id 1017250 | "Published Date: 10/10/2025" |

- **How to cancel** [WF], https://customerservice.costco.ca/app/answers/answer_view/a_id/1017248: "To cancel a membership, the primary member can speak with a team member at any Costco Membership Counter and receive a refund." (Published 09/10/2025)
- **Downgrade** [WF], https://customerservice.costco.ca/app/answers/answer_view/a_id/1017314: "The simplest way to return to a Business or Gold Star Membership is to visit any Costco Membership Counter." (Published 09/17/2026)
- **Upgrade online.** executive-rewards.html: "Sign in to your Costco.ca account ... Go to "Account" and click on "Renew Membership", and then click on "Upgrade Membership." You will see your prorated upgrade fee under "Order Summary."" The executive-rewards FAQ also says: "stop by the the Membership Counter, visit Costco.ca or call 1-800-463-3783." (The doubled "the" is on Costco's page.)
- **Who may upgrade** (FY2025 10-K, company-wide): "Paid members (except affiliates) are eligible to upgrade to an Executive membership".
- **Reward forfeiture on downgrade or refund:** see A3.
- **Termination by Costco**, verbatim (membership-conditions-regulations.html): "Costco reserves the right to refuse membership to any applicant and membership may be terminated at Costco's discretion without cause, as well as for such things as failure to comply with these conditions and regulations or abuse of your membership privileges."
- **Amendments**, verbatim: "Except for BC residents, these conditions and regulations may be amended by Costco without prior written notice to or consent of the member, but in such cases, the changes made will apply upon the renewal of your Costco membership." / "For British Columbia residents only : Any provision of these conditions and regulations may be amended at any time by Costco with prior notice to you. Any amendment to terms relating to cancellations, returns, exchanges or refunds may be made only if the amendment does not increase your obligations or reduce Costco's obligations."

**Renewal rules**, verbatim (membership-conditions-regulations.html):
> "If you have not signed up for auto renewal, your membership fee will be charged on your first shop of your renewal month. Renewal fees are due no later than the last day of the month your membership expires. ... Costco members may charge their membership fees automatically on any Mastercard® credit card or Visa credit or debit card; the card will be charged on the first day of your renewal month."

> "Memberships renewed within 2 months after expiration of the current membership year will be extended for 12 months from the expiration date. Memberships renewed more than 2 months after such expiration will be extended for 12 months from the renewal date. All renewals will be at the membership fee in effect on the date the membership fee is paid."

---

### A5. Household cards, card sharing, entry scanners (Canada)

**Membership conditions**, verbatim (https://www.costco.ca/membership-conditions-regulations.html, dated August 1, 2026):
> "Your membership card is valid at any Costco warehouse worldwide and is not transferable."

> "Primary and Affiliate members receive one free Household card for anyone over the age of 16 and living at the same address ("Household"). Household cardholders will be asked to present proof that they live at the same address as either the Primary or Affiliate member."

> "Your membership card must have a card number and recognizable, unobstructed full-face photo to be valid. If your photo is not on your card, you must present valid provincial or federal government-issued photo ID at the membership counter to have your photo added to your card."

> "Each cardholder may bring their children and up to two guests into the warehouse; however members are responsible for their children and guests. Children should not be left unattended. Guests do NOT have purchasing privileges."

> "No sales will be made to any person unless they have a valid membership card."

> "Costco can refuse entry to anyone at any time at its discretion. This includes members who do not display their Costco membership cards when requested."

> "**You will be required to scan your membership card (either in its original physical form or as it appears on the Costco mobile application) when entering any Costco warehouse and when checking out at a payment register. Bar codes, photos or other copies are not acceptable.**"

**Join page**, verbatim: "The designated household member must provide proof that they live at the same address as the Primary Member."

**Entry-scanner announcement** [WF], https://customerservice.costco.ca/app/answers/answer_view/a_id/1017225 ("Published Date: 09/10/2025"):
> "Over the coming months, membership scanning devices will be used at the entrance door of your local warehouse. Once deployed, prior to entering, all members must scan their physical or digital membership card by placing the barcode or QR Code against the scanner. Guests must also be accompanied by a valid member for entry. ... If your membership is inactive, expired, or you would like to sign up for a new membership, the attendant will ask that you stop by the membership counter prior to entering the warehouse to shop. Additionally, if your membership card does not have a photo, please be prepared to show your valid photo ID."

News dating of the Canadian rollout (August 2024 pilot markets) is in section B.

### A6. Self-checkout and register membership-card rules

- **Scan at every register.** The A5 condition applies: the card must be scanned "when checking out at a payment register. Bar codes, photos or other copies are not acceptable." It names no self-checkout exception.
- **Digital Shop Cards** [WF], Shop Card FAQ, https://customerservice.costco.ca/app/answers/answer_view/a_id/1017204/ (Published 09/21/2026): "At this time, Digital Shop Cards cannot be redeemed at Self-Checkout, Food Court Kiosks or the Gas Stations."
- **No Canada-specific self-checkout statement found.** No standalone Costco Canada page on self-checkout ID checks was found. The Digital Membership Card FAQ (a_id 8940) returned "This answer is no longer available" (see UNVERIFIED). CBC's description of self-checkout-related ID checks is in section B.

### A7. Executive early-shopping hours: Canada versus U.S.

**Finding: no Executive-only early hours appear on Costco's Canadian pages.**
- **Parent company says U.S. only.** FY2025 10-K (filed Oct 8, 2025): "**In the U.S.**, we recently added exclusive shopping hours for our Executive members and our gasoline operations generally have extended hours." https://www.sec.gov/Archives/edgar/data/909832/000090983225000101/cost-20250831.htm
- **Canadian warehouse pages show one schedule for all members.** Each page below shows a single "Hours" block. None has an "Executive Member Hours" block. Viewed 1 Oct 2026, verbatim:
  - Etobicoke (https://www.costco.ca/w/-/on/etobicoke/524): "Hours Mon-Fri: 9:00 a.m. - 8:30 p.m. Sat-Sun: 9:00 a.m. - 7:00 p.m. Thanksgiving: Closed". The holiday data gives the Thanksgiving closure date as 2026-10-12.
  - Richmond BC (https://www.costco.ca/w/-/bc/vancouver/54): same schedule, "Thanksgiving: Closed".
  - Terrebonne QC (served at https://www.costco.ca/w/-/on/east-york/525): "Mon-Fri: 9:00 a.m. - 8:30 p.m. Sat-Sun: 9:00 a.m. - 7:00 p.m."
- **U.S. comparison (labelled U.S.).** The Roseville, CA page, viewed 1 Oct 2026 (https://www.costco.com/w/-/ca/roseville/1702), shows split hours: "Executive Member Hours Mon-Fri: 9:00 AM - 8:30 PM Sat: 9:00 AM - 7:00 PM Sun: 9:00 AM - 6:00 PM Gold Star & Business Member Hours Mon-Fri: 10:00 AM - 8:30 PM Sat: 9:30 AM - 7:00 PM Sun: 10:00 AM - 6:00 PM". **U.S. only. Do not present as Canadian.**
- **What did start in Canada on the same date** (join-costco.html): the Executive $10 Instacart/Same-Day monthly credit, "starting 6/30/2025".

### A8. Co-branded credit card and accepted payment methods

**Issuer: CIBC.**
- CIBC release (Sept 2, 2021, via CNW/newswire.ca), https://www.newswire.ca/news-releases/cibc-to-become-exclusive-credit-card-issuer-for-costco-mastercards-in-canada-and-acquire-existing-costco-canadian-credit-card-portfolio-839660736.html: "CIBC ... announced today that it has signed a long-term agreement to become the exclusive issuer of Costco Mastercards in Canada, expected to start in early calendar year 2022." / "CIBC will also acquire the existing Canadian Costco credit card portfolio ... has over $3 billion in outstanding balances. Mastercard will remain the exclusive payment network for the Costco cobranded credit card in Canada and acceptance in Costco warehouses in Canada."
- In the same release, Mastercard Canada president Sasha Krstic is quoted: "Mastercard has proudly served as the network of choice for Costco in Canada since 2014".
- Switch date (costco.ca Connection page, https://www.costco.ca/f/-/connection-costco-credit-card-change-march-2022), verbatim: "rewards earned on both the Capital One Costco Mastercard program (earned from January 1 to March 3, 2022) and the CIBC Costco Mastercard (earned March 4 to December 31, 2022)". Costco's FY2025 10-K says: "The Company also maintains varying co-branded credit card arrangements in Canada".

**Issuer's page** (https://www.cibc.com/en/personal-banking/credit-cards/all-credit-cards/costco-mastercard.html, viewed 1 Oct 2026), verbatim:
- "Annual fee $0" · "Additional cardholders $0 up to 3"
- "3% cash back at restaurants and at Costco gas." · "2% cash back at other gas stations, electric vehicle charging stations and at Costco.ca." · "1% cash back on all other purchases including at Costco."
- "Minimum annual income of $15,000 is required to qualify for the CIBC Costco Mastercard." / "Minimum $50,000 individual annual income or $80,000 household annual income is required to qualify for the CIBC Costco World Mastercard."
- "Your credit card is also your Costco membership card with all membership details on the back."
- Interest rates did not render: they are loaded by script (see UNVERIFIED).

**Caps, verbatim footnote on costco.ca** (https://www.costco.ca/cibc-executive-offer.html):
> "For the CIBC Costco Mastercard, earn 3% on purchases (less returns) at merchants classified in the credit card network as Costco gas stations within Canada and 2% on purchases (less returns) at merchants classified in the credit card network as gas merchants and electric vehicle charging with a merchant category code of MCC 5552 on the first $5,000 net annual card purchases in this category on your account. After that, net card purchases at all gas merchants, including Costco, and electric vehicle charging ... will earn 1% in Cash Back Rewards. Earn 2% on purchases (less returns) classified in the credit card network as Costco.ca purchases on the first $8,000 net annual card purchases in this category on your account. After that, net card purchases at Costco.ca will earn 1% in Cash Back Rewards. Purchases at merchants classified in the credit card network as restaurants will earn 3% and all other qualifying purchases will earn 1% in Cash Back Rewards. The $5,000 and $8,000 limit will reset to zero annually on January 1. Cash Back Rewards will be provided in the form of a Cash Back Gift Certificate issued in Canadian dollars to an eligible Primary Cardholder once per calendar year in January for the cash back earned in the prior calendar year."

**Accepted payment methods** [WF], https://customerservice.costco.ca/app/answers/answer_view/a_id/1017193 ("Published Date: 09/10/2025"), verbatim:
> "Costco Canada warehouses accept the following methods of payment: Mastercard · Debit Card · Cash · Costco Shop Card* · Personal Cheque** · Apple Pay"

> "Costco Canada gas stations accept the following methods of payment: Mastercard credit & debit · Debit Card · Costco Shop Card* (Physical card only) — Cash and Digital Shop Cards are not accepted at Costco gas stations"

> "Costco.ca accepts the following methods of payment: Mastercard · Visa · Most PIN-based Debit/ATM Cards · Costco Shop Card*"

**Same-Day (Instacart)**, from costco.ca sameday-grocery-help, verbatim:
> "Debit, Credit, PayPal and Apple Pay on mobile are accepted methods of payment on Same-Day." / "Costco Shop Cards, international credit cards, and prepaid debit cards are not currently accepted."

**Membership conditions**, verbatim: "All purchases must be made by cash, debit card, Costco Shop Card, preprinted personal cheque or by those credit cards accepted by Costco from time to time."

### A9. Online (Costco.ca) and Same-Day (Instacart) pricing

- **Costco.ca versus warehouse** [WF], https://customerservice.costco.ca/app/answers/answer_view/a_id/1017385 ("Published Date: 09/10/2025"), verbatim:
  > "As you may already know, not all products sold on Costco.ca are available at local Costco warehouses. Also, products sold online may have different pricing than the same products sold at your local Costco warehouse. That's due to the shipping and handling fees charged for delivery to your home or business. Please note that Costco.ca does not price match warehouse or vice versa."
- **Same-Day versus warehouse** (costco.ca, https://www.costco.ca/f/-/sameday-grocery-help), verbatim:
  > "Why are prices different when shopping in-warehouse vs Delivery on the Sameday.costco.ca? Item prices are marked up higher than your local warehouse. Instacart uses the markup to pay for their delivery service."
- **Same-Day pricing policy** (Instacart-operated Costco Same-Day site, https://sameday.costco.ca/store/costco-canada/pages/pricing-policy), verbatim:
  > "Item prices are marked up higher than your local Costco warehouse. Instacart+ members receive additional savings through lower item pricing as compared to non-Instacart+ members. Instacart uses the markup to pay for their delivery services. The order minimum is $35."
- **Join page banner**, verbatim: "Same-Day Delivery Prices and availability will vary".
- **Same-Day exclusions**, verbatim (sameday-grocery-help): "Pharmacy prescription - OTC drugs / products where ID is required - Catering - Food court items - Special order products (e.g. custom cakes) - Costco Shop Cards - Gifts of membership - Postage Stamps" and "Alcohol can only be delivered in Ontario".

### A10. Gas stations: membership requirement

From https://www.costco.ca/f/-/gasoline-q-and-a, verbatim:
> "The gas station is open to Costco members only, with one exception: Costco Shop Card holders do not need to be members."

> "When a customer inserts a membership card or a co-branded MasterCard the system reads the membership number on the card and confirms the membership is active. Costco Shop Cards can only be purchased or recharged by members. Anyone can use a Costco Shop Card at the gas station, as it also serves as membership authorization for the pump."

> "The gas station is entirely self-serve, with pay-at-the-pump technology. We accept MasterCard, Canadian debit cards and Costco Shop Cards."

> "Cash and cheques are not accepted for payment."

> Pre-authorization: "The amount "pre-authorized" is the lower of the dollar limit issued by the card issuer or $200."

From https://www.costco.ca/f/-/gasoline-rebate: "Your CIBC Costco® Mastercard® doubles as your Costco membership card at the pump. Plus, earn 3% cash back* when you fill up at Costco Gas Stations." Membership conditions: "purchase at our Gas Stations can only be made by debit card, Costco Shop Card, and those credit cards accepted by Costco from time to time." Gasoline does not earn the 2% Reward (A3).

### A11. Costco Shop Card

From the Shop Card FAQs [WF], https://customerservice.costco.ca/app/answers/answer_view/a_id/1017204/ ("Published Date: 09/21/2026"), verbatim:
> "they never expire, you can recharge your card, and they come in full range of denominations."

> "To purchase a Costco Shop Card, you must be a Costco member at any Costco warehouse or online at Costco.ca."

> "Non-members* as well as members may use Costco Shop Cards to shop at any Costco location in Canada, the U.S.**, or Puerto Rico." with the footnote "*If you are a non-member, you must register for a day pass. This can be done a maximum of 2 times per year." (Footnote is WF-only: verify, see UNVERIFIED.)

> "Costco Shop Cards may be used toward a membership and merchandise."

> "Costco Shop Cards (physical and digital) are not redeemable for cash, excepts as required by law."

> "The Costco Shop Card cannot be used as a form of payment for Same-day Delivery powered by Instacart orders."

> "all Costco Shop Card transactions are final."

Amounts, from the payment answer [WF] a_id 1017193: "The Costco Shop Card can be purchased in any amount from $50-$2,000."

Other limits:
- Shop Cards are on the 2% Reward earning exclusions list (A3).
- The return policy says "Shop Cards are non-refundable." [WF]

### A12. Satisfaction guarantee and return policy (verbatim, with exceptions)

**From the Membership Conditions page** (dated August 1, 2026), https://www.costco.ca/membership-conditions-regulations.html:
> "On Merchandise: We guarantee your satisfaction on every product we sell, and will refund your purchase price*, with the following exceptions:"

> "Electronics: Costco will accept returns within 90 days from the date of purchase for televisions, major appliances, projectors, computers, cameras, aerial cameras (drones), camcorders, digital music players, tablets, smart watches, cellular phones (return details will vary by carrier service contract), and other electronic products identified by Costco from time to time."

> "Diamonds: Members returning items containing a 1.00ct diamond or larger must also present all original paperwork (IGI and/or GIA certificates). Costco warehouses will require additional time to verify the diamond, in which case a refund will be approved upon positive verification. This process will require approximately 2 to 5 business days."

> "Cigarettes and alcohol: Costco does not accept returns on cigarettes or alcohol where prohibited by law."

> "Products with a limited useful life expectancy, such as tires and batteries, may be sold with a product-specific limited warranty."

> "Custom Installation Services: Custom product(s) manufactured to our members' personal and unique specifications cannot be returned or refunded, except for warranty repair/replacement due to failure to meet specifications or as otherwise to the extent required by law."

> "Gold bars and gold bullion cannot be returned or refunded." / "Silver bars and silver bullion cannot be returned or refunded." / "All e-certificates are non refundable." / "Gift cards and ticket items are non-refundable."

> "Costco may in the future restrict its return policy regarding these and other products. Restrictions will be shown at the point of purchase."

> "QUEBEC ONLY - Exclusion of the right to repair† Costco does not guarantee the availability of any replacement parts, repair services or information necessary to maintain or repair any goods. ... †Notice pursuant to section 39.2 of the Consumer Protection Act (CQLR, c. P-40.1)."

**Customer-service version** [WF], https://customerservice.costco.ca/app/answers/answer_view/a_id/1017250 ("Published Date: 10/10/2025"). Differences from the Conditions page:
- It adds "Airline and Live Performance Event items are non-refundable."
- It reads "Gold bullion, gold bars, silver coins and silver bars are non-refundable."
- It adds "Shop Cards are non-refundable."
- It footnotes "*Countertop microwaves excluded", attached to "major appliances*" in the electronics line.

Join page: "Enjoy free technical support on TVs, computers and other devices along with our 90-day guarantee." with the footnote "1 Product-specific limitations apply."

### A13. Other membership conditions relevant on air

- "Only Costco Canada and Costco US members with a valid membership card can shop on Costco.ca."
- "Use of still or digital cameras or other recording devices, or recording of prices in any manner is not permitted. Offenders will be asked to leave the premises and their membership may be revoked."
- "You will be required to show your receipt for the items you purchased at the warehouse exit."
- "Termination of the Primary cardholder account for any reason will result in the termination of all other associated cardholder accounts."
- "Costco may realize a profit or receive rebates, discounts or other allowances in respect of contracts with suppliers of member services which Costco shall be entitled to retain for its own use/credit without accounting to members."

All five are quoted from membership-conditions-regulations.html (Aug 1, 2026).

---

### A14. Costco Wholesale Corp.: FY2025 10-K and FY2026 Q4 / Q3 disclosures

Fiscal 2026 = 52 weeks ended **August 30, 2026**. Costco's SEC figures are in USD.

**Q4 FY2026 earnings release.** 8-K dated **September 24, 2026** (Item 2.02), filed with EDGAR on 2026-09-24:
- 8-K: https://www.sec.gov/Archives/edgar/data/909832/000090983226000084/cost-20260924.htm
- Ex. 99.1 (press release): https://www.sec.gov/Archives/edgar/data/909832/000090983226000084/costex9918-k92426.htm
- Ex. 99.2 (supplement): https://www.sec.gov/Archives/edgar/data/909832/000090983226000084/costex9928-k92426.htm

| Metric | Value | Label | Source |
|---|---|---|---|
| Membership fees, Q4 FY26 (16 wks) | $1,850M (vs $1,724M) | Company-wide, USD | Ex. 99.1 income statement |
| Membership fees, FY26 (52 wks) | $5,907M (vs $5,323M FY25) | Company-wide, USD | Ex. 99.1 |
| Membership income growth, Q4 | "+7.3% Membership Income Growth"; "+7.7% Membership Income Growth ex-FX" | Company-wide | Ex. 99.2 |
| Paid memberships | "84.1MM Paid Memberships +3.8% Growth" | Worldwide | Ex. 99.2 |
| Total cardholders | "150.4MM Total Cardholders +3.6% Growth" | Worldwide | Ex. 99.2 |
| Executive memberships | "42.3MM Executive Memberships" | Worldwide | Ex. 99.2 |
| Executive sales penetration | "75.6% Penetration of Sales to Executive Members" | Worldwide | Ex. 99.2 |
| Renewal rate | "**92.3% US/CN Renewal Rate**" | **COMBINED U.S. and Canada** | Ex. 99.2 |
| Renewal rate | "89.8% Worldwide Membership Renewal Rate" | Worldwide | Ex. 99.2 |
| Deferred membership fees (Aug 30, 2026) | $3,006M (vs $2,854M) | Company-wide | Ex. 99.1 balance sheet |
| Accrued member rewards | $3,037M (vs $2,677M) | Company-wide | Ex. 99.1 |
| **Canada comparable sales**, Q4 (16 wks) | **5.0%**; adjusted* **4.6%** | **CANADA** | Ex. 99.1 |
| **Canada comparable sales**, FY26 (52 wks) | **7.8%**; adjusted* **6.7%** | **CANADA** | Ex. 99.1 |
| **Canada** Q4 comp ticket / traffic | Ticket +2.5%, Traffic +2.5%; adjusted ticket +2.1% | **CANADA** | Ex. 99.2 |
| U.S. comparable sales, Q4 / FY | 10.7% / 8.2% (adj 7.2% / 6.6%) | U.S. | Ex. 99.1 |
| **Canadian warehouses** | "**115 in Canada**" (of 939 total) | **CANADA** | Ex. 99.1 |
| Canada warehouse bridge | Q4 FY'25 end 110; +5 in Q1–Q3 FY'26; 0 in Q4; end FY'26 115; **end FY'27 (estimated) 120** | **CANADA** | Ex. 99.2 |

*"Excluding the impacts from changes in gasoline prices and foreign exchange."

The release does not report Canadian membership counts or Canada-only renewal rates. The Q4 earnings-call transcript was **not** available from Costco's investor site: investor.costco.com returned HTTP 403 to curl, and the WebFetch view showed no transcript. See UNVERIFIED.

**FY2025 10-K** (fiscal year ended Aug 31, 2025; filed Oct 8, 2025), https://www.sec.gov/Archives/edgar/data/909832/000090983225000101/cost-20250831.htm:

| Metric | Value | Label |
|---|---|---|
| Membership fees | $5,323M (FY24 $4,828M; FY23 $4,580M) | Company-wide |
| Paid members (thousands) | 81,000 (Gold Star 68,300; Business incl. affiliates 12,700) | Worldwide |
| Executive members (thousands) | 38,700 (FY24 35,400; FY23 32,300) | Worldwide |
| Household cards / total cardholders (thousands) | 64,200 / 145,200 | Worldwide |
| Renewal rate | "Our member renewal rate was **92.3% in the U.S. and Canada** and 89.8% worldwide at the end of 2025." | **COMBINED U.S. and Canada** / worldwide |
| Executive sales penetration | "approximately 73.6% of worldwide net sales in 2025" | Worldwide |
| 2% reward reduction in sales | "$3,007" (FY24 $2,804; FY23 $2,576) | Company-wide, USD M |
| **Canadian warehouses (Aug 31, 2025)** | **110** (94 own land and building; 16 lease) | **CANADA** |
| **Canada total revenue** (incl. membership fees, merchandise, gasoline) | **$36,923M** (FY24 $34,874M; FY23 $33,056M) | **CANADA**, USD |
| **Canada operating income** | **$1,849M** (FY24 $1,648M) | **CANADA**, USD |
| **Canada net sales change** | 6% (FY24 6%; FY23 4%) | **CANADA** |
| **Canada comparable sales** | 5% (adj. 8%) | **CANADA** |
| **Canada employees** | 55,000 | **CANADA** |
| **Canada floor space** | 15.9 million sq ft | **CANADA** |

Verbatim renewal-rate method (FY2025 10-K):
> "That rate, which excludes affiliates of Business members, is a trailing calculation that captures renewals during the period seven to eighteen months prior to the reporting date."

> "Renewal rates were negatively impacted by a higher number of memberships sold online, including through digital promotions, entering the renewal rate calculation. These members renew at a slightly lower rate on average."

**Q3 FY2026 10-Q** (12 weeks ended May 10, 2026; filed Jun 3, 2026), https://www.sec.gov/Archives/edgar/data/909832/000090983226000051/cost-20260510.htm:
- "At the end of the third quarter of 2026, our renewal rates were 92.2% in the U.S. and Canada and 89.7% worldwide." (combined / worldwide)
- Total paid members 82,900 thousand (worldwide).
- **Canada:** net sales +13% (Q3) and +11% (36 weeks). Comparable sales 11% and 9% (adjusted 6% and 8%). Segment total revenue $9,410M Q3 (vs $8,321M) and $27,774M for 36 weeks (vs $25,021M). Operating income $506M Q3. All CANADA, USD.

**Historical U.S. and Canada (combined) renewal rates in 10-Ks:**

| Fiscal year | U.S. and Canada | Worldwide |
|---|---|---|
| FY2012 | 89.7% | 86.4% |
| FY2014 | ~91% | ~87% |
| FY2015 | ~91% | ~88% |
| FY2016 | 90% | 88% |
| FY2017 | 90% | 87% |
| FY2025 | 92.3% | 89.8% |
| Q3 FY2026 | 92.2% | 89.7% |
| Q4 FY2026 (Ex. 99.2) | 92.3% | 89.8% |

---

## B. TIER (b): NAMED OUTLETS (bylined, dated)

| Outlet / byline / date | Fact, attributed | URL |
|---|---|---|
| **Global News**, Sarah Do Couto, published 2024-08-08 (updated 2024-08-09) | "In an effort to implement stricter store policies, Costco Wholesale announced it will be placing membership scanners at the entrance door to each of its locations." / "The wholesaler said the scanners are expected to be implemented "in the coming months."" / The fee rise to $65 "applies to Canadians holding an individual, business or business add-on membership." / "The annual fee was last raised in June 2017." | https://globalnews.ca/news/10687641/costco-membership-scanners-warehouse-canada-entrance/ |
| **CBC News**, Jenna Benchetrit, posted Aug 13, 2024 (updated Aug 14, 2024) | "The scanners, which were announced last week, are set up at Costco warehouse entrances in Ottawa, Edmonton, Regina and B.C.'s Lower Mainland, a company representative confirmed to CBC News." / "The representative couldn't confirm whether it would be expanded to all Costco locations in Canada." / "Regular "gold star" and business members will now have to pay $65 annually, rather than $60, while an executive membership will cost $130 annually, up from $120. The maximum annual two per cent reward for executive memberships will increase to $1,250 from $1,000." / CBC also reports Costco "began asking customers to show photo ID alongside their membership passes last year" in connection with self-checkout (CBC's characterization; attribute to CBC). | https://www.cbc.ca/news/business/costco-memberships-photo-id-1.7293020 |
| **Global News**, Saba Aziz, 2025-01-14 | Proposed class action. **ALLEGATION ONLY**; see section D. Global quotes Costco's website: "products sold online may have different pricing than the same products sold at your local Costco warehouse." | https://globalnews.ca/news/10957804/costco-canada-class-action-lawsuit/ |
| **CTV News** (Toronto video), published 2025-06-13 (URL dated 2025/06/12) | Headline: "Costco members in U.S. will soon have access to extended store hours". Description: "Costco members holding an executive membership in the U.S. can expect some added benefits to start later this month." Supports A7: the early hours were described as **U.S.** | https://www.ctvnews.ca/toronto/video/2025/06/12/costco-members-in-us-will-soon-have-access-to-extended-store-hours/ |

---

## C. TIER (c): FLAGGED ONLY (never a source)

These surfaced in searches. They are not used as sources.
- Motley Fool Q4 FY2026 transcript, fool.com (2026-09-29). Opened via WebFetch summary only.
- GuruFocus, 24/7 Wall St., TradingKey, panabee and mojosalesandbranding Q4 FY2026 summaries.
- Daily Hive, blogTO, Toronto Scoop and Grocery Business articles on scanners.
- Yahoo News Canada "executive member shopping hours".
- wiki.nsacct.org, savvynewcanadians.com, princeoftravel.com, frugalflyer.ca, milesopedia.com, rewardscanada.ca, canadianbudgetbinder.com, insurdinary.ca and soscip.org.
- slickdeals.net, thetakeout.com and mashed.com.

None of these is relied on for any fact above.

---

## D. LEGAL ITEMS (labelled)

| Item | Status label | What is documented | Source |
|---|---|---|---|
| Proposed class action against Costco Wholesale Canada Ltd., Federal Court (Perrier Avocats; plaintiff named by Global News as Ibrahim El Bechara), re: online vs. in-warehouse prices | **ALLEGATION.** Proposed class action, filed December 2024. Global News says it "still has to be approved by the court". **No finding, no settlement, no admission.** | Global News reports that the claim alleges "double ticketing" and "false or misleading indications". The proposed class is anyone in Canada who since Dec 23, 2022 bought on the app or website "and paid more than the price displayed for that same item in Costco warehouses". Global "reached out to Costco for comment ... but did not receive a response before publication". | https://globalnews.ca/news/10957804/costco-canada-class-action-lawsuit/ (Global News, Saba Aziz, 2025-01-14). Court file not opened; see UNVERIFIED. |

Costco's own published position on online pricing is in A9: "products sold online may have different pricing ... Costco.ca does not price match warehouse or vice versa".

Regulators and courts:
- No Competition Bureau, Quebec Office de la protection du consommateur, FCAC or CRA decision about Costco Canada membership terms was found or used.
- No CanLII decision was found or used.
- These searches were limited (see UNVERIFIED).

---

## E. APPENDIX: RECALLS (food-safety item, **DO NOT USE ON AIR**)

costco.ca's site footer links to "Recalls and Product Notices". The page was not opened and no recall content was collected. Per house rules, recall content is excluded from the body of this file.

---

## F. SOURCE LOG (all opened 1 Oct 2026)

| # | URL | Method | Result |
|---|---|---|---|
| 1 | https://www.costco.ca/join-costco.html | curl | 200, prices and FAQ extracted |
| 2 | https://www.costco.ca/membership-conditions-regulations.html | curl | 200, dated "August 1, 2026" |
| 3 | https://www.costco.ca/executive-rewards.html | curl | 200 |
| 4 | https://www.costco.ca/cibc-executive-offer.html | curl | 200 |
| 5 | https://www.costco.ca/gasoline.html ; /f/-/gasoline-q-and-a ; /f/-/gasoline-rebate | curl | 200 |
| 6 | https://www.costco.ca/f/-/sameday-grocery-help | curl | 200 |
| 7 | https://sameday.costco.ca/store/costco-canada/pages/pricing-policy | curl | 200 |
| 8 | https://www.costco.ca/w/-/on/etobicoke/524 ; /w/-/bc/vancouver/54 ; /w/-/on/east-york/525 (served Terrebonne 525) | curl | 200 |
| 9 | https://www.costco.com/w/-/ca/roseville/1702 (U.S. comparison) | curl | 200 |
| 10 | https://www.costco.ca/f/-/connection-costco-credit-card-change-march-2022 | curl | 200 |
| 11 | customerservice.costco.ca a_id 1017250, 1017193, 1017385, 1017314, 1017248, 1017400, 1017225, 1017204 | WebFetch [WF] | curl = HTTP 401. WF rendered with published dates. |
| 12 | customerservice.costco.ca a_id 11019 (Membership FAQ), 8940 (Digital Membership Card FAQs) | WebFetch | "This answer is no longer available" |
| 13 | https://www.cibc.com/en/personal-banking/credit-cards/all-credit-cards/costco-mastercard.html | curl | 200. Interest rates not rendered. |
| 14 | newswire.ca CIBC release, 2021-09-02 | curl | 200 |
| 15 | SEC EDGAR: 8-K 2026-09-24 + Ex. 99.1/99.2; 10-Q 2026-06-03; 10-K FY2025, FY2017, FY2016, FY2015, FY2014, FY2013, FY2012, FY2011, FY2007, FY2006, FY2001, FY2000; 8-K 2024-07-10 Ex. 99.1; 8-K 2017-05-26 Ex. 99.1 | curl | 200 |
| 16 | https://investor.costco.com/ (and events pages) | curl / WebFetch | curl 403. WF showed no transcript. |
| 17 | globalnews.ca (x2), cbc.ca, ctvnews.ca | curl | 200 |
| 18 | costco.ca return-policy.html, membership-terms-and-conditions.html, shop-card pages tried | curl | 404 (these URLs do not exist) |

---

## UNVERIFIED / DO-NOT-USE

1. **Q4 FY2026 earnings-call remarks.** Costco's investor site (investor.costco.com) returned 403. The only transcript opened was Motley Fool's (tier c), via WebFetch summary. Its quotes are unverified, including CFO Gary Millerchip's "$1.849 billion" fee income and a claim that the Sept 2024 increase "contributed less than 1% of growth" in Q4. Do not use. Use the 8-K exhibits in A14 instead.
2. **Date Canada Gold Star rose from $50 to $55.** The FY2012 10-K lists only "Canada Business members" in the Nov 2011 increase. The FY2014 10-K states $55 for Canada. The exact Canadian Gold Star effective date was not found.
3. **Sept 1, 2000 increase: Canada-specific amounts.** The 10-K gives only "averaging approximately $5 per member", company-wide.
4. **Executive Membership launch date in Canada** (circa 2000/2001). Not verified.
5. **Whether entry scanners are now at all 115 Canadian warehouses.** Costco's answer (09/10/2025) says "over the coming months". No completion statement was found.
6. **Global News citing "social media pages dedicated to Canadian Costco fans"** on early scanner sightings. Unsourced. Do not use.
7. **Search-engine summary claims about Executive hours in Canada.** One said Canada has executive early hours; another said it does not. These are WebSearch model summaries, not sources. Use only A7 (10-K wording plus warehouse pages).
8. **Status of the Federal Court proposed class action after Jan 14, 2025.** Court file number and docket not opened. Authorization/certification status unknown. ALLEGATION only.
9. **Product price examples in the class action** (e.g., storage-container set, pitcher), as reported by Global News from a court document. Not from a retailer's own site or app with date, store and unit price. **Do not use as prices.**
10. **CIBC Costco Mastercard interest rates.** Loaded by script and not rendered ("RDS%rate..." placeholders). Installment-plan rates (5.99%/6.99%/7.99%) appeared without their context. Do not use.
11. **Digital membership card at self-checkout.** The Costco answer (a_id 8940) is "no longer available". A search snippet said digital cards work at self-checkout. Unverified.
12. **Shop Card non-member "day pass ... maximum of 2 times per year".** Seen only through WebFetch rendering of a_id 1017204. Verify on the live page before use.
13. **All [WF] quotes** (customerservice.costco.ca). Retrieved through a summarising fetch because curl got HTTP 401. Re-check verbatim on screen before broadcast.
14. **Canada FY2026 full-year segment revenue, operating income and employees.** The FY2026 10-K was not yet filed as of 1 Oct 2026. Only Q3 YTD (10-Q) and Q4 comps (8-K) are available.
15. **Canadian membership counts and Canada-only renewal rate.** Costco does not report them separately in the documents opened. Only the combined "U.S. and Canada" renewal rate exists.
16. **Exact year Costco Canada switched to Mastercard-only acceptance.** The only statement found is Mastercard's "network of choice for Costco in Canada since 2014", quoted in CIBC's 2021 release. Costco's own statement of the switch date was not opened.
17. **Regulator and court searches.** Competition Bureau, Quebec OPC, FCAC, CRA, CanLII and the Quebec class-action registry were not searched exhaustively. No items are reported. Absence of results is not evidence of absence.
18. **Instacart Help Center pages** (memejour.costco.ca) and the second CTV video ("Costco members paying $130 fee ...") were not opened.
19. **Yahoo News Canada "executive member shopping hours" article.** Not opened. Tier unclear. Do not use.
20. **Tier (c) items in section C.** Flag only. Never a source.

<!-- ===== costco_record_news.md ===== -->

# Costco Canada: documented record, 13 May – 1 Oct 2026 (plus the essential record for 2023–2026)

**Research date:** every URL below was opened on **1 October 2026** unless the line says otherwise.
**Purpose:** research for a script that posts on **4 October 2026**. This file covers what is **new since the channel's 13 May 2026 video**, the background record that still matters, and a claim-by-claim check of the channel's 17 September 2026 video, "Costco Canada Just Got Caught".
**Companion file:** `costco_membership_terms.md` in the same folder covers membership terms, fees, the Executive reward, returns and scanners from costco.ca. This file does not repeat that material except where a news item depends on it.

**Tier key**
- **(a)** Primary sources: SEC filings, Costco's investor-site PDFs, costco.ca, regulators, court records, Statistics Canada, Parliament.
- **(b)** A named outlet, with byline and date.
- **(c)** Flag only. Never a source.
- **(d)** A named survey, with its methodology.

**Other markers**
- **[WF]** means the page was read through a summarising fetch tool because curl was blocked. Re-check the exact wording on screen before air.
- **Money:** Costco reports in **USD** unless a line says otherwise.
- **Geography:** every figure is labelled **CANADA**, **U.S.**, **COMBINED U.S.+Canada**, or **COMPANY-WIDE / WORLDWIDE**.

---

## 0. Summary: what is actually new since 13 May 2026 (all tier a/b)

| # | What is new | Date | Tier | One-line status |
|---|---|---|---|---|
| 1 | **Canada's sales growth slowed through the summer.** Canada had the weakest adjusted comparable sales of Costco's three regions in Q4. | 3 Jun – 24 Sep 2026 | (a) | August 2026 Canada adjusted comp sales were +2.8%, against U.S. +5.6% and Other International +6.8%. Q4 Canada adjusted was +4.6%, against U.S. +7.2%. |
| 2 | **Four Canadian warehouses listed for November 2026:** NE Edmonton AB, Lloydminster AB, E Windsor ON, Wasaga Beach ON. | Page live 1 Oct 2026 | (a) | Listed on costco.ca "New Locations". No day-specific dates are given. |
| 3 | **Costco plans 5 Canadian openings in FY2027.** Its estimate is 120 Canadian warehouses at the end of FY2027, up from 115. | 24 Sep 2026 | (a) (8-K Ex. 99.2). The call wording comes from a third-party transcript (see §3). | Plan only. |
| 4 | **No new Canadian warehouse opened between 31 May and 30 Aug 2026.** | Releases of 3 Jun, 8 Jul, 5 Aug, 2 Sep and 24 Sep 2026 | (a) | Every release gives "115 in Canada". |
| 5 | **Federal Court proposed class action T-3644-24** (El Bechara v. Costco Wholesale Canada Ltd., about online vs. warehouse prices). It held a case conference on 11 May 2026, and the court issued a direction on 12 May 2026. Amendment-motion filings followed on 25 May, 4 June and 10 June 2026. | May–June 2026 | (a) court docket | **ALLEGATION.** The class action is **not certified**. Costco has a motion to strike pending. The court indicated a certification hearing window of Dec 2026 – Feb 2027. |
| 6 | **Competition Bureau grocery work names Costco as one of the "five grocery giants"** (2 June 2026 testimony). The Bureau opened a food-supply-chain examination (notice dated 16 June 2026). It also opened an investigation into minimum-advertised-pricing policies (28 Sep 2026). | Jun–Sep 2026 | (a) | **No Costco-specific allegation.** The Bureau's notice says "We are not examining any specific allegations of wrongdoing." The 28 Sep release does not name Costco. |
| 7 | **Membership Conditions & Regulations now dated "August 1, 2026".** | 1 Aug 2026 | (a) | **What changed is NOT established.** No earlier version could be retrieved (see UNVERIFIED). |
| 8 | **Q4 FY2026 results.** Membership fees were US$1,850M for the quarter and US$5,907M for the year (company-wide). The U.S.+Canada combined renewal rate was 92.3%. | 24 Sep 2026 | (a) | No fee change announced. Global News (25 Sep 2026): fees "have not changed since an increase in 2024." |
| 9 | **New stores reported locally:** Belleville ON (Global News, 29 Jul 2026), Thunder Bay ON building-permit application (CBC, 30 Jul 2026), and Costco confirming November for E Windsor (CBC, 28 Aug 2026). | Jul–Aug 2026 | (b) | Belleville and Thunder Bay have no opening date. |
| 10 | **Survey:** 75% of Canadians see Costco as American (Abacus Data, fielded 4–9 Sep 2026, published 1 Oct 2026). | 1 Oct 2026 | (d) | Usable with the method stated (see §9). |
| 11 | **Statistics Canada, released 14 Sep 2026:** prices for food purchased from stores rose 2.8% year over year in August 2026 and are up 29.0% since August 2021. | 14 Sep 2026 | (a) | All grocers. **Not** Costco-specific. |

**Searched for, with no change found since 13 May 2026 (absence of evidence only):**
- Fee changes in Canada.
- Executive-only shopping hours in Canada. Warehouse pages show one schedule; see the companion file §A7.
- New card-sharing enforcement in Canada.
- Changes to pharmacy, optical, hearing-aid, tire, travel or gas policy in Canada.
- Uber Eats or DoorDash expansion to Canada. Costco's Q4 call described these expansions as U.S.-only.
- Any "Buy Canadian" shelf-labelling programme at Costco Canada.
- Any CBC Marketplace investigation of Costco Canada in 2026.

---

## 1. Timeline since 13 May 2026

| Date | Event | Label | Tier | Source (opened 1 Oct 2026) |
|---|---|---|---|---|
| 11 May 2026 | Federal Court case-management conference in T-3644-24 (Justice Joyal, Justice Ngo, Associate Judge Alexandra Steele). Recorded outcome: "Affaire entendue – une ordonnance/directive suivra". | Procedural. ALLEGATION stage. | (a) | Federal Court recorded entries, T-3644-24 (API endpoint `https://www.fct-cf.gc.ca/CourtFilesAndDecisions/proceedingQueriesRE?division=t&courtnumber=T-3644-24`; public search page https://www.fct-cf.gc.ca/en/court-files-and-decisions/court-files) |
| 12 May 2026 | Direction from Justice Ngo, verbatim (French): "la Cour observe que le dossier souffre de certaines lacunes. En particulier, l'acte introductif d'instance est présentement une cible mouvante." The court set deadlines of 25 May, 4 June and 10 June 2026 for the plaintiff's motion to amend. It said the motion to strike and the certification motion "seront entendues en même temps" afterwards. | Procedural direction. **Not a ruling on the merits.** | (a) | Same docket, RE #71 |
| 25 May – 10 Jun 2026 | Plaintiff filed a complete motion record to amend (25 May). Costco filed an amended response record (4 Jun). Plaintiff filed a reply (10 Jun). This is the last docket entry seen. | Procedural | (a) | Same docket, RE #73–86 |
| 28 May 2026 | Q3 FY2026 call (Costco). | — | Transcript is (c); see §3 | — |
| 2 Jun 2026 | Competition Bureau Interim Commissioner Jeanne Pratt told a Commons committee: "Canada's grocery industry is concentrated, with most Canadians buying their groceries in stores owned by five grocery giants: Loblaws, Sobeys, Metro, Costco and Walmart." | Regulator statement. **Not an allegation against Costco.** | (a) [WF] | https://www.canada.ca/en/competition-bureau/news/2026/06/competitive-markets-are-essential-in-supporting-food-security-and-affordability.html |
| 3 Jun 2026 | May sales release. Canada comp +9.2% (adjusted +5.3%). "115 in Canada". | Company report | (a) | https://s201.q4cdn.com/287523651/files/doc_news/Costco-Wholesale-Corporation-Reports-May-Sales-Results-2026.pdf |
| 3 Jun 2026 | Q3 FY2026 10-Q filed. Canada segment: Q3 revenue $9,410M, operating income $506M. Canada comp sales Q3 +11% (excl. FX and gas +6%). 36-week comp +9% (excl. +8%). U.S.+Canada renewal rate 92.2% (COMBINED). | Company filing | (a) | https://www.sec.gov/Archives/edgar/data/909832/000090983226000051/cost-20260510.htm |
| 16 Jun 2026 (page date) | Competition Bureau notice, "Behind the price tag: Examining the food supply chain". Submissions ended 4 Sep 2026. Verbatim: "This is not a law enforcement investigation. We are not examining any specific allegations of wrongdoing." | Regulator, sector-wide | (a) | https://competition-bureau.canada.ca/en/how-we-foster-competition/notice-behind-price-tag-examining-food-supply-chain |
| 17 Jun 2026 | CBC (John Mazerolle) reports Costco's lawyers called a **U.S.** rotisserie-chicken "no preservatives" class action "fatally flawed". The case is in the U.S. District Court, S.D. California. | **U.S. case. ALLEGATION.** Food-labelling subject. | (b) | https://www.cbc.ca/news/world/costco-chicken-9.7237331. **Do not use. See UNVERIFIED / DO-NOT-USE.** |
| 8 Jul 2026 | June sales release. Canada comp +3.7% (adjusted +4.9%). "115 in Canada". | Company report | (a) | https://www.sec.gov/Archives/edgar/data/909832/000090983226000060/costex9918-k7726.htm |
| 29 Jul 2026 | Global News video, reported by Kaytlyn Poberznick: "After years of speculation, it's finally official. Costco is coming to Belleville. City officials say the wholesale retail giant will build a new warehouse on Bell Boulevard". | Announcement attributed to city officials. No date. | (b) | https://globalnews.ca/video/11998308/new-state-of-the-art-costco-coming-to-belleville/ (uploadDate 2026-07-29) |
| 30 Jul 2026 | CBC Thunder Bay (Kris Ketonen): the city "has received a building permit application for the new Costco retail warehouse and gas bar" at Golf Links Road and Central Avenue. City director Joel DePeuter is quoted: the permit fee is "over $200,000 for a $33 million construction project." | Permit **application**, not approval | (b) | https://www.cbc.ca/news/canada/thunder-bay/costco-building-permit-thunder-bay-9.7291388 |
| 1 Aug 2026 | Membership Conditions & Regulations page carries the date "August 1, 2026". | Costco document | (a) | https://www.costco.ca/membership-conditions-regulations.html |
| 5 Aug 2026 | July sales release. Canada comp +4.2% (adjusted +4.9%). "115 in Canada". | Company report | (a) | https://s201.q4cdn.com/287523651/files/doc_news/Costco-Wholesale-Corporation-Reports-July-Sales-Results-2026.pdf |
| 28 Aug 2026 | CBC Windsor (Desmond Brown): "A Costco representative confirmed to CBC Windsor that the new store is expected to open in November, although an exact opening date has not yet been set." | Costco statement, via CBC | (b) | https://www.cbc.ca/news/canada/windsor/windsor-second-costco-9.7323209 |
| 2 Sep 2026 | August sales release. Canada comp +4.0% (adjusted **+2.8%**). Costco says: "Labor Day in the U.S. and Canada will occur one week later this year. The shift negatively impacted August total and comparable sales by a little less than 75 bps." | Company report. The Labor Day effect is COMBINED U.S.+Canada. | (a) | https://s201.q4cdn.com/287523651/files/doc_news/Costco-Wholesale-Corporation-Reports-August-Sales-Results-2026.pdf |
| 14 Sep 2026 | Statistics Canada: "Price growth for food purchased from stores continued to slow in August, rising 2.8% year over year…" and "prices have increased 29.0% since August 2021." | All grocers. Not Costco. | (a) | https://www150.statcan.gc.ca/n1/daily-quotidien/260914/dq260914a-eng.htm |
| 24 Sep 2026 | Q4/FY2026 8-K (details in §2). | Company filing | (a) | https://www.sec.gov/Archives/edgar/data/909832/000090983226000084/costex9918-k92426.htm ; Ex. 99.2: https://www.sec.gov/Archives/edgar/data/909832/000090983226000084/costex9928-k92426.htm |
| 25 Sep 2026 | Global News (Ariel Rabinovitch) on the Q4 results. Verbatim: "Costco's membership fees have not changed since an increase in 2024." It quotes CFO Gary Millerchip: "We see members being very thoughtful about where they're spending their dollars." | Outlet report | (b) | https://globalnews.ca/news/12073257/costco-earnings-consumer-spending/ |
| 25 Sep 2026 | BNN Bloomberg (Archie Niari): the Bureau "is expected to publish a call for information on the morning of Sept. 28, asking for input on pricing policies used in retail grocery." | Sector-wide | (b) | https://www.bnnbloomberg.ca/business/economics/2026/09/25/competition-bureau-to-publish-a-call-for-information-on-grocery-pricing-policies/ |
| 27 Sep 2026 | CBC Marketplace Cheat Sheet (Bobby Hristova). The headline items are Sobeys property controls and deepfake doctors. Costco is not in the headline. | — | (b) | https://cbc.ca/news/marketplace/marketplace-cheat-sheet-september-27-2026-9.7358938 |
| 28 Sep 2026 | Competition Bureau: "The Competition Bureau has launched an investigation into the use of minimum advertised pricing policies in the grocery sector." **Costco is not named** (WebFetch check). | Investigation of a sector **practice**. **No retailer is named.** | (a) [WF] | https://www.canada.ca/en/competition-bureau/news/2026/09/competition-bureau-concerned-that-grocery-deals-are-being-kept-from-canadians.html |
| 1 Oct 2026 | costco.ca "New Locations" lists "**NE Edmonton, AB** - November 2026", "**Lloydminster, AB** - November 2026", "**E Windsor, ON** - November 2026", "**Wasaga Beach, ON** - November 2026". | Costco announcement | (a) | https://www.costco.ca/new-locations.html (redirects to https://www.costco.ca/f/-/new-locations) |
| 1 Oct 2026 | Abacus Data: "Costco is seen as American by 71% then and 75% now." | Survey | (d) | https://abacusdata.ca/nineteen-months-on-the-buy-canadian-shopper-has-not-gone-home/ |
| 12 Oct 2026 (upcoming) | Canadian warehouse pages show "Thanksgiving: Closed" for both the warehouse and the gas station. The page data gives the date 2026-10-12. | Costco notice | (a) | https://www.costco.ca/w/-/on/etobicoke/524 (Etobicoke). The companion file also checked Richmond BC and Terrebonne QC. |

---

## 2. Costco's own Canadian numbers (tier a)

### 2.1 Canada comparable sales, May–August 2026 (from Costco releases)

All comparable-sales figures are percentages. "Adj." means excluding gas-price and foreign-exchange effects. Costco reports these in USD terms, so FX moves the unadjusted figures.

| Period | Canada comp | Canada adj. | U.S. comp | U.S. adj. | Other Intl adj. | Source |
|---|---|---|---|---|---|---|
| Q3 FY26 (12 wks to 10 May) | 11% | 6% | 9% | 7% | 6% | 10-Q (above) |
| May (4 wks to 31 May) | 9.2% | 5.3% | 13.7% | 8.7% | 6.9% | May release PDF |
| June (5 wks to 5 Jul) | 3.7% | 4.9% | 10.6% | 7.6% | 5.6% | 8-K Ex. 99.1, 8 Jul |
| July (4 wks to 2 Aug) | 4.2% | 4.9% | 10.3% | 6.9% | 6.6% | July release PDF |
| August (4 wks to 30 Aug) | 4.0% | **2.8%** | 9.0% | 5.6% | 6.8% | August release PDF |
| **Q4 FY26 (16 wks)** | **5.0%** | **4.6%** | 10.7% | 7.2% | 6.2% | 8-K Ex. 99.1, 24 Sep |
| **FY26 (52 wks)** | **7.8%** | **6.7%** | 8.2% | 6.6% | 6.5% | 8-K Ex. 99.1 |

- **Q4 Canada traffic and ticket (Ex. 99.2):** traffic +2.5%, ticket +2.5%, adjusted ticket +2.1%. The U.S. figures were traffic +3.2% and ticket +7.3%. **CANADA vs U.S., labelled.**
- **Analysis (our arithmetic, not Costco's words):** Canada had the lowest adjusted comp of the three reporting regions in Q4 and in August. Costco gives **no explanation specific to Canada** in the releases. Do not supply one; any reason given would be speculation.

### 2.2 Canada segment (USD)

| Item | Value | Label | Source |
|---|---|---|---|
| FY2025 total revenue (incl. membership fees and gas) | $36,923M (FY24 $34,874M; FY23 $33,056M) | CANADA | FY2025 10-K segment note: https://www.sec.gov/Archives/edgar/data/909832/000090983225000101/cost-20250831.htm |
| FY2025 operating income | $1,849M (FY24 $1,648M; FY23 $1,448M) | CANADA | same |
| FY2025 U.S. total revenue / operating income | $200,046M / $6,878M | U.S. | same |
| Q3 FY26 (12 wks) Canada revenue / operating income | $9,410M / $506M (prior year $8,321M / $450M) | CANADA | Q3 10-Q |
| 36 wks FY26 Canada revenue / operating income | $27,774M / $1,416M (prior year $25,021M / $1,215M) | CANADA | Q3 10-Q |
| Canadian warehouses | 110 at the end of Q4 FY25 → +5 in Q1–Q3 FY26 → 0 in Q4 → **115** at the end of FY26 → **120 estimated** at the end of FY27 | CANADA | Ex. 99.2, 24 Sep 2026 |
| FY2026 full-year Canada segment figures | **Not yet published.** The FY2026 10-K had not been filed as of 1 Oct 2026. | — | — |

**Operating-margin arithmetic (ours, from the filed figures):**

| Region, FY2025 | Calculation | Operating margin |
|---|---|---|
| Canada | 1,849 / 36,923 | 5.01% |
| U.S. | 6,878 / 200,046 | 3.44% |
| Other International | 1,656 / 38,266 | 4.33% |

On the 36-week FY26 figures: Canada 1,416 / 27,774 = 5.10%; U.S. 5,124 / 149,934 = 3.42%.

**Caveat on the margin comparison:**
- Costco's **FY2017** 10-K segment note said: "Certain operating expenses, predominantly stock-based compensation, incurred on behalf of the Company's Canadian and Other International operations, but are included in the U.S. operations because those costs are not allocated internally and generally come under the responsibility of U.S. management." (https://www.sec.gov/Archives/edgar/data/909832/000090983217000014/cost10k90317.htm)
- The FY2024 and FY2025 10-Ks do not contain that sentence. The FY2025 note says only that "Inter-segment net sales and expenses, including royalties, have been eliminated in computing total revenue and operating income."
- Whether shared costs are still carried in the U.S. segment is **not stated**.
- So a line such as "Canada is ~45% more profitable per dollar than the U.S." is **arithmetic on segment figures that depend on internal cost allocation**. If used, attribute it as our calculation and include this caveat.

### 2.3 Membership (company-wide or combined unless labelled)

| Item | Value | Label | Source |
|---|---|---|---|
| Membership fees, Q4 FY26 / FY26 | $1,850M / $5,907M (FY25 $5,323M) | COMPANY-WIDE | Ex. 99.1, 24 Sep 2026 |
| Operating income, FY26 / FY25 | $11,685M / $10,383M | COMPANY-WIDE | Ex. 99.1 |
| Fee share of operating income | FY26: 5,907 / 11,685 = 50.6%. FY25: 5,323 / 10,383 = 51.3%. | COMPANY-WIDE, our arithmetic | — |
| Renewal rate | "92.3% US/CN Renewal Rate"; "89.8% Worldwide" | **COMBINED U.S.+Canada** / worldwide | Ex. 99.2 |
| Paid members / Executive members | 84.1M / 42.3M | WORLDWIDE | Ex. 99.2 |
| Canada-only member count or renewal rate | **Costco does not publish these.** | — | Not in the 10-K, 10-Q or 8-K |
| Fee increase, effective 1 Sep 2024 | "increase annual membership fees by $5 for U.S. and Canada Gold Star (individual), Business, and Business add-on members. With this increase, all U.S. and Canada Gold Star, Business and Business add-on members will pay an annual fee of $65" | COMBINED announcement | 8-K Ex. 99.1, 10 Jul 2024: https://www.sec.gov/Archives/edgar/data/909832/000090983224000036/costex9918-k71024.htm |
| Current Canadian fees | Gold Star/Business $65; Executive $130 (upgrade "an additional $65 a year"); reward cap $1,250 | CANADA | https://www.costco.ca/join-costco.html |
| Executive Same-Day credit (Canada) | "one (1) $10 CAD instant credit … starting 6/30/2025 … on one (1) purchase of $150 CAD or more" | CANADA. Started June 2025, **not new since May 2026**. | join-costco.html |

### 2.4 Things in the Q4 release that are NOT Canadian (do not present as Canadian)
- **Price cuts in Ex. 99.2:** "KS Walnuts $13.79 to $9.99; KS Colombian (Whole Bean) From $21.99 to $19.99; KS Dry Facial Towel $19.99 to $18.99; KS Course Black Pepper From $6.99 to $5.99". No country or currency is given; these are **probably U.S. dollar prices**. **Do not use as Canadian prices.** Rule 5 also applies: these are not shelf prices with a store and pack size.
- **IEEPA tariff refunds** ("non-recurring benefit of $0.15 per diluted share from IEEPA tariff refunds"). These are **U.S.** tariffs paid by the U.S. business.
- **Q3 10-Q:** "In March 2026, four class actions were filed against the Company seeking a refund of tariffs paid … under the International Emergency Economic Powers Act". **U.S. courts, U.S. ALLEGATIONS.**

---

## 3. Earnings-call statements about Canada

**Sourcing problem:**
- investor.costco.com returned HTTP 403 to curl, and no transcript was found on Costco's own site or on SEC.
- Costco's releases point to a **webcast** only.
- The quotes below come from **Motley Fool transcripts** (fool.com; the Q4 transcript is also syndicated on theglobeandmail.com). These are **tier (c) transcriptions of tier (a) speech**.
- **Check every quote against the Costco webcast before air.** If that is not possible, paraphrase and attribute: "Costco told analysts, according to a published transcript…"

| Call (date) | Speaker (per transcript) | Verbatim (per transcript) | Label | Transcript URL |
|---|---|---|---|---|
| Q4 FY26 (24 Sep 2026) | Not attributed in the extract; prepared remarks | "For fiscal year '27, we are planning to open 4 buildings in Europe, 5 in Canada, and 1 in Mexico" | CANADA plan. Matches Ex. 99.2 (115 → 120). | https://www.fool.com/earnings/call-transcripts/2026/09/29/costco-cost-q4-2026-earnings-call-transcript/ |
| Q4 FY26 | prepared remarks | "These partnerships will complement the successful long-term partnership that we've had with Instacart in the U.S. and Canada." | This came right after the announcement that Uber Eats and DoorDash are expanding to **the U.S.**. No Canadian expansion is stated. | same |
| Q4 FY26 | CFO Gary Millerchip | "The September 2024 U.S. and Canada membership fee increase accounted for less than 1% of fee growth. And as a reminder, Q4 marks the last quarter in which we will see a year-over-year benefit from the membership fee increase." | COMBINED U.S.+Canada | same |
| Q4 FY26 | CFO | "our U.S. and Canada renewal rate was 92.3%, up 10 basis points from last quarter" | COMBINED | same (matches Ex. 99.2) |
| Q3 FY26 (28 May 2026) | CEO Ron Vachris (answering an analyst) | "In Canada, yes, we have a lot of upside potential. We have got some clubs. We have got the next 3 to 5 years charted out. So we see consistent strong growth in Canada for at least the next 5 years" | CANADA | https://www.fool.com/earnings/call-transcripts/2026/05/28/costco-cost-q3-2026-earnings-transcript/ |
| Q3 FY26 | CFO | "In the quarter, we opened 4 net new warehouses, including 3 in the U.S., and 1 additional Canadian business center." | CANADA | same |
| Q3 FY26 | CFO | "The September 2024 US and Canada membership fee increase accounted for a little more than 1/4 of membership income growth." | COMBINED | same |
| Q2 FY26 (5 Mar 2026; before 13 May, for context) | CEO Ron Vachris | "As far as Canada goes, we have 114 buildings now… We recently expanded operating hours in all of our Canadian buildings to help offset some of the traffic increases." | CANADA. Consistent with warehouse pages showing Sat–Sun closing at 7:00 p.m. | https://www.fool.com/earnings/call-transcripts/2026/03/05/costco-cost-q2-2026-earnings-call-transcript/ |
| Q2 FY26 | CFO | "The September 2024 US and Canada membership fee increase accounted for about one-third of our membership income growth." | COMBINED | same |
| Q2 FY26 | CFO | "Canada was up 12.8%, or 9.3% adjusted for gas deflation and FX." (February comps) | CANADA | same |
| Q2 FY26 | CEO | "We will be transparent in how we plan to do this if and when we receive any refunds." | Refers to **U.S.** IEEPA tariff refunds | same |

**Not Canadian, do not use as Canadian:**
- The Q4 claim that Costco "saved our members over $3.2 billion versus the average price at the pump" (markets where it operates; **company-wide**).
- "penetration of U.S. member households that purchased gas" (**U.S.**).
- Pharmacy remarks. GLP-1 and Medicare remarks are **health/U.S.** and are excluded by house rule 1.

---

## 4. Warehouses: opened or announced in Canada

| Location | Status | Date info | Tier | Source |
|---|---|---|---|---|
| NE Edmonton, AB | Listed by Costco | "November 2026" | (a) | costco.ca/f/-/new-locations |
| Lloydminster, AB | Listed by Costco | "November 2026" | (a) | same |
| E Windsor, ON | Listed by Costco. A representative confirmed November to CBC. | "November 2026"; "exact opening date has not yet been set" | (a)+(b) | same; CBC 28 Aug 2026 (above) |
| Wasaga Beach, ON | Listed by Costco | "November 2026" | (a) | same |
| FY2027: 5 Canadian openings | Plan | 115 → 120 estimated by the end of FY27 | (a) Ex. 99.2 | — |
| Thunder Bay, ON | Building-permit application received by the city | No date | (b) CBC 30 Jul 2026 | above |
| Belleville, ON | City officials say Costco will build on Bell Boulevard | No date | (b) Global 29 Jul 2026 | above |
| South Surrey, BC | Council approved the application. CBC photo caption: "A new location is coming to South Surrey in 2027." | 2027 (CBC caption) | (b) CBC, Akshay Kulkarni, 19 Nov 2025 | https://www.cbc.ca/news/canada/british-columbia/south-surrey-costco-164-street-9.6985581 |
| Halifax area (third store, Middle Sackville) | Mayor Andy Fillmore: "Costco is exploring the possibility" | "very early stage" | (b) CBC, 16 Sep 2025 | https://www.cbc.ca/news/canada/nova-scotia/costco-third-location-middle-sackville-1.7595851 |
| Ottawa, Cyrville Rd Business Centre gas station (up to 24 pumps) | Proposal | CTV Ottawa, Josh Pringle, 4 May 2026 (before the window) | (b) | https://www.ctvnews.ca/ottawa/article/costco-wants-to-build-24-pump-gas-station-in-ottawas-east-end/ |
| Canadian business centres | Q2 FY26 call: "two additional Canadian business centers". Q3 FY26: "1 additional Canadian business center". | Before 10 May 2026 | Transcript (c), see §3 | — |
| Rocky View County AB; second Regina SK | Mentioned only in search-engine summaries | — | **UNVERIFIED** | — |

---

## 5. Membership and service areas: status check

The question in each row is whether anything **changed since 13 May 2026**, with evidence.

| Area | What is documented | Changed since 13 May? | Source |
|---|---|---|---|
| Fees | $65 / $130 (Canada). Last increase effective 1 Sep 2024. | **No.** Global (25 Sep 2026): "have not changed since an increase in 2024." | join-costco.html; Global 25 Sep 2026 |
| Membership conditions | Now dated "August 1, 2026". | **Re-dated, but the content changes are unknown.** | membership-conditions-regulations.html |
| Executive-only hours | Canadian warehouse pages show a single schedule: Mon–Fri 9:00 a.m.–8:30 p.m.; Sat–Sun 9:00 a.m.–7:00 p.m. FY2025 10-K: "**In the U.S.**, we recently added exclusive shopping hours for our Executive members". | **No Canadian Executive hours found.** | Etobicoke page; 10-K FY2025 |
| Weekend hours | Sat–Sun closing at 7:00 p.m. A Costco spokesperson, quoted by INsauga (Ryan Rocca, 22 Dec 2025): "Instead of 6 p.m., your local Costco warehouse will close at 7 p.m. on Saturdays and Sundays going forward." | Took effect in early 2026, **before** the window. | https://www.insauga.com/new-permanent-change-for-costco-in-canada/ (local outlet, bylined). Confirmed by the warehouse page. |
| Entry scanners / card sharing | Conditions: "You will be required to scan your membership card … when entering any Costco warehouse and when checking out at a payment register." CBC (Jenna Benchetrit, 13 Aug 2024): scanners at "Ottawa, Edmonton, Regina and B.C.'s Lower Mainland". CBC sub-headline: "New scanning system being implemented ahead of September membership rate hike". | **No new enforcement news found** after 13 May 2026. | Conditions page; https://www.cbc.ca/news/business/costco-memberships-photo-id-1.7293020 |
| Gas | Etobicoke gas hours: Mon–Fri 6:00 a.m.–9:30 p.m.; Sat–Sun 6:00 a.m.–8:30 p.m.; Thanksgiving closed. | No policy change found. Gas **prices** load by script and were not captured. | Etobicoke page |
| Executive 2% reward exclusions | "Rewards will not be calculated: … on purchases … at Costco Wholesale's gas stations, food courts, optical centres (Quebec only), and pharmacies" | No change found. | Conditions page |
| Pharmacy / optical / hearing aids | No Canadian policy change found. Health-related content is excluded by house rule 1. | — | — |
| Tires / travel | No Canadian change found. | — | — |
| Same-Day / Instacart | Executive $10 credit since 30 Jun 2025. CTV (Christl Dabu, 13 Jun 2025) reported the perk. | No change found. Uber Eats and DoorDash expansions are **U.S.** | join-costco.html; https://www.ctvnews.ca/business/article/costco-reveals-new-perk-for-executive-members/ |
| Online vs. warehouse pricing | Costco's position, as quoted by Global News: "products sold online may have different pricing than the same products sold at your local Costco warehouse." | This is the subject of the proposed class action (§7). | Global 14 Jan 2025 |

---

## 6. Tariffs, sourcing and "Buy Canadian" at Costco Canada

| Date | Item | Label | Tier | Source |
|---|---|---|---|---|
| 7 Mar 2025 | Financial Post (Ben Cousins), syndicated on Yahoo Finance Canada. Headline: "Costco to reduce Canadian products in U.S. stores in wake of tariffs". Quotes CEO Ron Vachris: "There's not many items that we can't find something to replace or something else to bring in that category". FP adds: Costco "sources less than 20 per cent of its products from Canada, China and Mexico for its U.S. locations." | Concerns **U.S. stores**. FP's text calls it a "fourth-quarter earnings call"; it was the **Q2 FY2025** call (6 Mar 2025). Do not repeat FP's quarter label. | (b) | https://ca.finance.yahoo.com/news/costco-reduce-canadian-products-u-184408234.html |
| 2 Jun 2025 | Global News (Sean Previl). Quotes Vachris on the Q3 FY25 call: "We rerouted many goods sourced from countries with large tariff exposure to our non-U.S. markets" and "We continue to move more Kirkland Signature product sourcing into the countries or regions where items are sold". Global reports that Sobeys described its "Shop Canada" labelling and Metro and Loblaw described local sourcing. **The article does not say Costco was asked about shelf labelling.** | Costco says. | (b) | https://globalnews.ca/news/11208577/costco-canada-supply-chain-tariffs/ |
| 13 Feb 2024 | Pierre Riel (EVP & COO, Costco Wholesale International and Canada) to the Commons Agriculture Committee: "Over 61% of our Kirkland Signature items are now manufactured in Canada." | Costco says, under testimony | (a) | https://www.ourcommons.ca/documentviewer/en/44-1/AGRI/meeting-91/evidence |
| 11 Feb 2026 | Ipsos: "With more than 10 million card-carrying members in Canada, the wholesale retailer's nimble supply-chain maneuvering helped it dodge tariffs and pass savings to consumers." | **Ipsos's characterisation, not Costco's.** The member count is not in any Costco filing. | (d) | §9 |
| Any date | A Costco Canada "Buy Canadian" or maple-leaf shelf-label programme | **Not found** in tier (a)/(b). This is an absence, not a finding. | — | — |

---

## 7. Legal and regulatory record, Costco Wholesale Canada Ltd. (2023–2026, plus context)

| Matter | Forum / file | Status label | What the record says | Source |
|---|---|---|---|---|
| **El Bechara v. Costco Wholesale Canada Ltd.**: proposed class action on online vs. in-warehouse prices ("double ticketing", s. 54 Competition Act; "false or misleading indications") | **Federal Court, T-3644-24**, Montréal. Filed **23 Dec 2024** ("Déclaration déposée le 23-DEC-2024"). Plaintiff's counsel: Perrier Avocats (Eric Perrier, Réjean Paul Forget). Defendant's counsel per the docket: Eric Lefebvre, Virginie Blanchette-Séguin, Henri Barbeau. | **ALLEGATION. NOT CERTIFIED.** No finding, no settlement, no admission. | The court made the case a special management proceeding on 30 Dec 2024. Costco filed a motion to strike the statement of claim (Rule 221(1)(a)) on 25 Apr 2025. The plaintiff filed a certification motion on 7 May 2025 and a motion to amend on 13 Jun 2025. Justice Gascon recused himself on 4 Mar 2025, citing prior work with defence counsel. The case was reassigned to Justice Ngo on 30 Mar 2026. Direction of 30 Mar 2026: a hearing of up to 3 days "au cours de la période de décembre 2026 à février 2027", including certification. Direction of 12 May 2026 (quoted in §1). Last entry seen: 10 Jun 2026. | Federal Court recorded entries (API above). Global News (Saba Aziz, 14 Jan 2025): https://globalnews.ca/news/10957804/costco-canada-class-action-lawsuit/ |
| The same case, as covered by Protégez-Vous (Jean-Luc Lavallée, 10 Apr 2026) | — | ALLEGATION (outlet's report of a pleading) | PV reports that the certification motion "devrait être débattue entre décembre 2026 et février 2027… Aucune date n'a encore été déterminée." It also quotes the plaintiff's pleading. | https://www.protegez-vous.ca/nouvelles/argent/costco-en-ligne-quand-la-livraison-fait-exploser-la-facture |
| **BC Privacy Commissioner Order P25-07** (Costco Wholesale Canada Ltd.) | OIPC BC, **2025 BCIPC 92**, 9 Oct 2025. Adjudicator: Elizabeth Vranjkovic. | **ORDER (finding, in part).** | An individual asked Costco for his personal information under PIPA. The adjudicator "found that the applicant had no right to access some of the information because it was not his personal information," "found that s. 23(4)(c) applied to some … but ss. 23(3)(c) and 23(4)(d) did not apply," and "ordered Costco to disclose the information it was not authorized or required to withhold". The request related to an interaction on 5 Oct 2023 at the Vancouver warehouse. | https://www.oipc.bc.ca/documents/orders/3034 (PDF) |
| Ontario Ministry of Health penalty, CWC Pharmacies Ontario Ltd. (**2019**, outside window; context only) | Ontario Ministry of Health (per CBC) | **REGULATORY FINDING / PENALTY (2019).** Appeal status unknown. | CBC (Timothy Sawa, 1 Feb 2019) quotes the ministry: "[Costco pharmacies] had received $7,250,748.00 for advertising services which the Ministry concluded violated the prohibition on rebates." | https://www.cbc.ca/news/health/costco-kickbacks-1.5003341. **On air: use the ministry's wording only. Pharmacy-related. Recommend not using in a consumer video (see DO-NOT-USE).** |
| CITT customs appeal **AP-2024-004**, appellant Costco Wholesale Canada Ltd. | Canadian International Trade Tribunal | Decision exists (listed as "Decision and reasons"). **Content not opened.** | Tariff-classification type appeal; outcome unknown. | Listed at https://www.citt-tcce.gc.ca/en/about-tribunal/list-tribunal-decisions-not-yet-published. The decision page (https://decisions.citt-tcce.gc.ca/citt-tcce/c/en/item/521491/index.do) loads by script, so the text was not read. **UNVERIFIED.** |
| **Competition Bureau** | — | **No Costco-specific case found.** | Costco is named only as one of the "five grocery giants" (2 Jun 2026). The 2023 market study said: "The success of Costco and Walmart across Canada has brought more choice to the grocery industry. But with only about 500 stores between them, they are not an option in every community." | https://competition-bureau.canada.ca/en/how-we-foster-competition/education-and-outreach/canada-needs-more-grocery-competition |
| **Grocery Sector Code of Conduct** | Federal / provincial / territorial agriculture ministers | **Voluntary industry code.** Not an enforcement action. | AAFC statement of July 2024: all major retailers incl. Walmart and Costco agreed to join. That page failed to load by curl (connection error). Global News (Uday Rana, 15 Dec 2025): the code's office "had completed its governance framework, setting the ground for the implementation starting on Jan. 1, 2026." | https://globalnews.ca/news/11578652/canada-grocery-code-of-conduct-2026/ ; AAFC URL in UNVERIFIED |
| Quebec OPC; FCAC; CRA; federal privacy commissioner; labour boards | — | **No items found** in searches. Absence of results is not evidence of absence. | — | — |
| CanLII | — | **Not searchable from here.** canlii.org returned 403 (bot protection). | — | — |
| Quebec class-action registry | — | **Not searchable from here.** registredesactionscollectives.quebec returned 403 (Cloudflare). | — | — |
| Costco's own disclosure | FY2025 10-K (Note 10) and Q3 FY26 10-Q legal notes | — | **No Canadian matter is listed** in either. This reflects Costco's own materiality judgment. **Do not imply concealment.** | 10-K / 10-Q URLs above |

**U.S. matters (labelled U.S., not Canadian):**
- The rotisserie-chicken "no preservatives" proposed class action (S.D. Cal.). **ALLEGATION.**
- The IEEPA tariff-refund class actions (N.D. Ill., King County, and others). **ALLEGATIONS.**
- Costco's own tariff-refund complaint against the U.S. government at the U.S. Court of International Trade (CBC, 2 Dec 2025: https://www.cbc.ca/news/world/costco-suing-trump-tariffs-9.7000556).

---

## 8. Consumer investigations (bylined)

| Outlet / byline / date | Subject | What it says | Use |
|---|---|---|---|
| **Protégez-Vous**, Jean-Luc Lavallée, 10 Apr 2026 | Online vs. warehouse prices at Costco.ca | Verbatim: "les prix des produits en ligne sont généralement supérieurs à ceux affichés en magasin, à quelques exceptions près". PV says it checked prices "entre le 3 et le 5 avril 2026" (same product codes). It reports that a Greenworks mower cost $679.99 in a warehouse and $879.99 online at the end of March. PV also notes: "la livraison d'un électroménager comprend aussi une installation minimale… ce qui peut justifier en partie l'écart". | Usable as **PV's finding, attributed**. The **prices are outlet-reported, not retailer-site prices**, so they cannot be used as prices under rule 5 (see DO-NOT-USE). |
| **CBC News**, Sophia Harris, 12 Nov 2019 | Receipt and bag checks (Walmart, with a Costco section) | CCLA's Michael Bryant: "Their right is to say, 'Thanks, but no thanks,' and walk away." CBC: Costco customers "may have provided consent — depending on how clearly the rules are laid out, said CCLA's Bryant." "Costco didn't reply to requests for comment". | Usable, **dated 2019**. https://www.cbc.ca/news/business/walmart-receipt-check-costco-1.5355527 |
| **CBC News**, Natalie Stechyson, 30 Jul 2025 | Downtown Vancouver food court made members-only | "CBC News has contacted Costco Canada for a comment and not yet heard back." McMaster's William Huggins: "Inadvertently, what happens is we've got corporations making up for deficits in our social programs." | Usable. One store only. https://www.cbc.ca/news/canada/costco-food-court-membership-1.7595356 |
| CBC Marketplace (2021, Instacart pricing incl. Costco) | Delivery mark-ups | Search snippet only; **not opened**. | UNVERIFIED |
| CBC Marketplace, 2026 | — | **No Costco Canada investigation found** for 2026. The 27 Sep 2026 Cheat Sheet headlines Sobeys. | — |

---

## 9. Named surveys and studies (tier d)

| Publisher | Date | Sample / method | Wording / result (verbatim) | Source |
|---|---|---|---|---|
| **Abacus Data** (David Coletto) | Published 1 Oct 2026. Fielded 4–9 Sep 2026; comparison wave 5–11 Feb 2025. | "1,479 Canadian adults" (Sep 2026) and "3,000 Canadian adults" (Feb 2025). "conducted online with panelists from a blend of partner panels and weighted to census data". "paid for by Abacus Data Inc." | "Costco is seen as American by 71% then and 75% now." Also: "nine in ten want stores to clearly indicate which products are made in Canada (91% then, 89% now)." | https://abacusdata.ca/nineteen-months-on-the-buy-canadian-shopper-has-not-gone-home/ |
| **Ipsos**, Most Influential Brands 2025 | Release dated 11 Feb 2026 | "a representative survey of 6,700 Canadians". Over 100 brands; eight dimensions. Fieldwork dates are not given in the release. | "6. Costco (Back on the list, +5)". "half of Canadians agree Costco understands their needs, compared to an average of 21%." | https://www.ipsos.com/sites/default/files/ct/news/documents/2026-02/mib-2025-press-release_02-11-26_2.pdf |
| **Leger**, Reputation 2025 | Spring 2025 | Leger's six pillars. Sample size not on the page read. | "For the first time, Costco overtook the #1 spot in Leger's annual Reputation Study". The page also states wage figures sourced to *Canadian Grocer*. **Do not use those wage figures.** | https://leger360.com/reputation-2025-top-brands-in-canada/ |
| **Leger**, Reputation 2026 | Toyota Canada release dated 16 Apr 2026 | "Leger surveyed more than 38,000 Canadians to gather their perspectives on 334 companies across 29 different sectors." | **Costco's 2026 rank was not seen on a Leger page.** A Pelmorex release on GlobeNewswire (27 Apr 2026, [WF]) lists "Dollarama, Samsung, Costco, Sony, The Weather Network…", which implies #3. **Verify on leger360 before use.** | https://media.toyota.ca/en/releases/2026/toyota-again-ranks-among-10-most-respected-companies-in-canada--.html |
| **Leger**, Reputation 2024 (via Daily Hive, 3 Apr 2024) | 2024 | "more than 38,000 Canadians" | Costco 10th, score 68. | Daily Hive is (c). **Flag only.** |
| **Competition Bureau** consumer survey in the 2023 grocery study | 2023 | Per the Bureau page | "What stores do you typically go to when buying groceries? … Costco: 18%" | Competition Bureau study page (§7) |
| Dalhousie Agri-Food Analytics Lab; Angus Reid Institute | — | — | **No Costco-specific survey found.** | — |
| dunnhumby Retailer Preference Index (Costco #1, 2024 and 2025) | Dec 2025 | Industry study | Business Wire page returned 403; **not opened**. | UNVERIFIED |

---

## 10. Check of "Costco Canada Just Got Caught" (channel video, 17 Sep 2026)

### What it was based on
- The video was **not based on a single news event.** It is a 15-item countdown compiled from documents: the costco.ca conditions, Costco's 10-K, CBC and Global stories from 2019–2025, Commons committee testimony, recall notices, and a StatCan release.
- The only items dated close to 17 Sep 2026 are:
  - the **Membership Conditions dated 1 Aug 2026**;
  - the **StatCan CPI release of 14 Sep 2026**;
  - a claimed **August 2026 amendment to a Quebec maple-syrup class action**. This is unverified, and Costco is not a party.
- The transcript examined is `tr_CC_costco_caught_sep2026_25K_clean.txt` in this folder. The publish date comes from the task brief and was not independently checked.

### Claim-by-claim

| # | Claim in the video | Verdict | Evidence |
|---|---|---|---|
| Intro | CBC *The National*, 30 Oct 1985: Knowlton Nash quotes; London Drugs' Mark Nussbaum: "If they're going to sell below cost, more power to them… And let them have it." | **HOLDS** (b) | CBC Archives, posted 30 Oct 2019: https://www.cbc.ca/archives/the-dawn-of-the-costco-era-in-canada-1.5328668 |
| Intro | "Costco Wholesale Canada has not been fined by the Competition Bureau… not been prosecuted by any provincial consumer regulator" | **RISKY.** Absences cannot be proven, and in **2019 Ontario's Ministry of Health penalised Costco's Ontario pharmacy entity $7.25M** (per CBC). That was a health regulator, not a "consumer regulator", but a viewer will hear "never fined". | §7 |
| Intro | "discloses zero Canadian legal proceedings in its annual report" | **HOLDS** for the FY2025 10-K and the Q3 FY26 10-Q. Add that this is Costco's materiality judgment. | §7 |
| 1 | Conditions dated 1 Aug 2026: "Use of still or digital cameras or other recording devices, or recording of prices in any manner is not permitted. Offenders will be asked to leave the premises and their membership may be revoked." | **HOLDS, verbatim** (a). The line "Every price comparison video… was made in violation" is the channel's inference. Drop it. | membership-conditions-regulations.html |
| 2 | "You will be required to show your receipt…" plus the CBC/CCLA material | **HOLDS.** **Add the date:** the CBC story is from **Nov 2019**, which the video does not say. | §8 |
| 3 | Bag-inspection consent clause | **HOLDS, verbatim:** "Costco reserves the right to inspect any container, backpack, briefcase, bag or other package when our members and their guests enter or leave our warehouses. Our members and their guests consent to such inspections when they enter our warehouses." | Conditions page |
| 4 | "Costco can cancel you for nothing and change the rules without telling you" | **HOLDS WITH A MATERIAL OMISSION.** The clause continues: "…may be amended by Costco without prior written notice to or consent of the member, **but in such cases, the changes made will apply upon the renewal of your Costco membership.**" The BC paragraph: "may be amended at any time by Costco with prior notice to you." The Quebec paragraph is a "QUEBEC ONLY - Exclusion of the right to repair" notice under s. 39.2 CPA. "Without cause" is verbatim. | Conditions page |
| 5 | Scanners before the fee increase. CBC Aug 2024. Vachris quote to Fox Business. | **Scanners: HOLDS.** CBC Benchetrit, 13 Aug 2024; the sub-headline is verbatim. **Fox Business quote: UNVERIFIED** (Fox Business is not opened and not in the approved outlet list). | §5 |
| 6 | Fee rose 1 Sep 2024: $60→$65 and $120→$130. CFO in March 2026: "about 1/3". FY25 fees $5.323B vs operating income $10.383B. | **HOLDS** (a) for the fee and the financials. The CFO quote is from a **third-party transcript**. "More than half of everything Costco earned" = 51.3% of **operating income**, company-wide. Say "operating income", not "everything Costco earned". | 8-K 10 Jul 2024; 10-K FY25; §3 |
| 7 | Executive 2% exclusions, quoted with "optical centers" | **MISQUOTED.** The text reads "optical centres **(Quebec only)**". **Also an omission:** the video says the last three months "don't count", but the terms say "Purchases from the last three months will be added to the following year's Reward calculation." Breakeven $3,250 and cap at $62,500: arithmetic OK. | Conditions page |
| 8 | Vancouver food court (CBC, Jul 2025); Huggins quote | **HOLDS** (b). One location, downtown Vancouver; CBC Stechyson, 30 Jul 2025. | §8 |
| 9 | Narcity (Lisa Belmonte, Feb 2026) Kirkland price rises; StatCan +29.0% since Aug 2021 | **StatCan: HOLDS** (a), released 14 Sep 2026. **The Narcity prices fail rule 5** (not from the retailer's site with date, store and unit price) → DO-NOT-USE. Comparing them to the CPI basket is also apples-to-oranges. | §1; DO-NOT-USE |
| 10 | Detergent pods shrinking (blogger Nathaniel Christopher); Daily Hive bath tissue | **TIER (c). DO NOT USE.** | — |
| 11 | Federal Court proposed class action (El Bechara, Perrier) | **HOLDS. Update it:** court file **T-3644-24**, still **not certified**. Costco's motion to strike is pending. A certification hearing window of Dec 2026 – Feb 2027 is indicated. Costco's quoted position ("may have different pricing… due to the shipping and handling fees") is consistent with Global's quote. **The "odd" line about the 10-K implies concealment. Drop it.** | §7 |
| 12 | Riel, 13 Feb 2024: "Over 61% of our Kirkland Signature items are now manufactured in Canada"; detergent and maple syrup examples | **HOLDS, verbatim** (a), AGRI meeting 91. | https://www.ourcommons.ca/documentviewer/en/44-1/AGRI/meeting-91/evidence |
| 12 | Kirkland inquiry-form notice ("certain information may be proprietary or confidential") | **UNVERIFIED.** The costco.ca URLs tried returned 404. | — |
| 13 | Recall notices naming Vita Health and Factors Group; IVC ownership; NHP vs. food labelling law | **DO NOT USE.** These are recall and health-product items (house rule 1). The whole segment is appendix-only. | Appendix |
| 14 | "confidential presentation submitted to the committee on November 2, 2023" | **HOLDS, verbatim** (13 Feb 2024 evidence). | AGRI 91 |
| 14 | "As you know, we're a private company. We report our numbers globally with the U.S. company, so I cannot disclose that." presented as a Feb 2024 answer about Canadian numbers | **MISDATED / MISCONTEXTUALISED.** The quote is from **17 April 2023** (AGRI evidence, meeting 56). It answered a question about **grocery profit margins**. Riel added: "our profit from selling merchandise, before tax is paid, has been at 1.43% for the last two years". In Feb 2024 he said the opposite on ownership: "You must understand that our company is public." | https://www.ourcommons.ca/documentviewer/en/44-1/AGRI/meeting-56/evidence ; AGRI 91 |
| 14 | Perron–Riel exchange on figures given to the Competition Bureau | **HOLDS, verbatim** (13 Feb 2024). The video's gloss ("a sentence that began by declining…") is editorial. Drop it. | AGRI 91 |
| 14 | Grocery code: "Costco just didn't sign until the federal government said the word mandatory out loud" | **EDITORIAL; implies motive.** Fails rule 6. State only that the July 2024 ministers' statement listed Walmart and Costco as joining. | §7 |
| 15 | Canada segment: revenue $36,923M, operating income $1,849M; margins 5.01% vs 3.44%; 13.4% of revenue and 17.8% of operating income | **Numbers HOLD** (a). Add the **allocation caveat** (§2.2). The transcript has the U.S. revenue garbled ("200 million and 46 million"); correct it to **$200,046M**. | 10-K FY25 |
| 15 | FP, 7 Mar 2025, "Costco to reduce Canadian products in US stores"; Vachris quote | **HOLDS** (b). Note that it concerns **U.S. stores**. | §6 |
| 15 | No comparable Costco "Buy Canadian" labelling found | **Absence, framed correctly in the video.** Global's June 2025 piece did not say it asked Costco. | §6 |
| + | $1.50 hot dog. Millerchip 2024 "price is safe". 2026 combo change (bottled water). | **Price: commonly reported, but no retailer-site check was done here.** The Millerchip quote is from a third-party transcript. The **bottled-water change is UNVERIFIED and may be U.S.-only.** The CAD→USD conversion must be recomputed with a Bank of Canada rate on the air date. | UNVERIFIED |
| + | Wages: "In March 2025, we increased the starting wage by $0.50 an hour to at least $20.00 for all entry-level positions in the U.S. and Canada." Retention ~94% (U.S.+Canada). | **HOLDS** (a), FY25 10-K. The retention figure is **COMBINED**. The video's statement that the March 2026 and March 2027 increases were "locked in" is **not verified** in the text read. | 10-K FY25 |
| + | Riel: 53,000 employees in Canada; average wage $27.63 (2019) → $30.20; part-timers guaranteed 25 hours; health benefits "paid in full by Costco" | **HOLDS, verbatim** (13 Feb 2024). The benefits wording is a Costco claim; attribute it. | AGRI 91 |
| + | "A regular grocery store in Canada sells between 25,000 and 60,000 products. Costco sells just 3,500… Our pack of toilet paper has 40 rolls." "if on day 365, they aren't satisfied, we will refund their membership fee" | **HOLDS, verbatim. But the date is 17 Apr 2023 (AGRI 56), not Feb 2024.** | AGRI 56 |
| + | Competition Bureau 2023 quote ("brought more choice… about 500 stores") | **HOLDS, verbatim** (a). | §7 |
| + | "Costco is Canada's number two grocery retailer at about 15% of the market" | **UNVERIFIED.** No source found. The Bureau's survey says only that 18% of Canadians "typically go to" Costco for groceries, which is a different measure. | — |
| + | CFIA $47,000 product-of-Canada penalties; CBC Marketplace maple-washing; Quebec maple class action (Aug 2026) | **UNVERIFIED** here. These are food-labelling enforcement items about other companies. Do not use. | — |
| + | Q2 FY26 price cuts (eggs, cheese, coffee, paper); "We will be transparent…" | The refund quote is from a **third-party transcript** and is about **U.S.** IEEPA refunds. The specific price-cut list is not verified as Canadian. | §3 |
| Close | "Because 92.1% of you did last year" | **WRONG AS FRAMED.** 92.1% is the **combined U.S.+Canada** rate at **Q2 FY26** (Feb 2026). The current figure is **92.3%** (FY26). There is **no Canada-only rate**. | Ex. 99.2; §3 |

**Overall:** the video's document spine holds at tier (a)/(b). However, it has:
- **two misattributions:** the Riel "private company" quote is misdated to 2024, and "optical centres (Quebec only)" is misquoted;
- **two omissions that change meaning:** "changes apply upon renewal", and the last three months rolling into the next year's reward;
- **one combined-vs-Canada error:** the 92.1% renewal figure;
- **several tier (c), recall or health segments that fail house rules:** items 10 and 13, and the Narcity prices.

**Do not reuse "Caught" as a source for the 4 October script.** Re-source each fact from the rows marked HOLDS.

---

## 11. Tier (c): flagged only, never a source
- Motley Fool / Globe and Mail-syndicated, Seeking Alpha, Benzinga, GuruFocus, Investing.com and Yahoo transcript pages. These were used only to locate call wording (§3).
- Grocery Business (403), Canadian Grocer, Retail Insider (403), Western Grocer, Narcity, Daily Hive, blogTO, INsauga (bylined local outlet; used once with a confirming tier (a) page), Culture Alberta, Barrie360, Vancouver Is Awesome, MTL Blog, Time Out, Access Winnipeg, Hungry416, TO Times, Food Blog Canada.
- Droit-inc (Marie-Ève Buisson, 10 Jan 2025). Its sentence "Costco admet ainsi contrevenir à l'article 54" is the **outlet's own inference, not an admission**. **Never repeat it.**
- Le Droit en Bref, lanature.ca, soscip.org, lawmonarch.com, savvynewcanadians, wealthnorth, cocowest, cocoeast, cocoquebec, flyer sites, costrefund.com, mojosalesandbranding, retailshout, thetakeout, mashed, sporked, whatnow, thehill (U.S. syndication), money.ca, ground.news, Wikipedia, YouTube, TikTok, Reddit-type forums.

---

## 12. Appendix: recalls and food-safety items. **DO NOT USE ON AIR.**
House rule 1 applies: recalls and health-product items are excluded from the script. These items are listed only so nobody sources them by accident. **None were opened for content.**
- Global News: "Costco Canada recalls croissants, toaster oven and other items" (https://globalnews.ca/news/12004604/costco-canada-recalls/); "Costco Canada chicken product is being recalled" (https://globalnews.ca/news/12052322/costco-canada-chicken-product-recall/); "Costco Canada recalls yogurt products that may contain mould" (https://globalnews.ca/news/12019869/costco-canada-yogurt-recall/).
- CTV: "'Do not consume': Milk recalled at Costco Canada"; "Costco Canada recalling select chicken products"; "Costco Canada recall includes food, appliances and toys".
- "Caught" item 13: Government of Canada recall notices naming Vita Health Products Inc. and Factors Group (Kirkland natural health products), the Kirkland basmati rice recall, and the Osler deal sheet on IVC's ownership of Vita Health.
- lanature.ca (Mar 2026): a U.S. rotisserie-chicken class action alleging an undisclosed salmonella issue. Tier (c), food-safety, U.S.
- CBC, 17 Jun 2026: U.S. "no preservatives" rotisserie-chicken class action. Food labelling, U.S., ALLEGATION.

---

## 13. Source log (opened 1 Oct 2026)

| # | URL | Method | Result |
|---|---|---|---|
| 1 | sec.gov 8-K Ex. 99.1 / 99.2, 24 Sep 2026 | curl | 200 |
| 2 | sec.gov 8-K Ex. 99.1, 8 Jul 2026 (June sales) | curl | 200 |
| 3 | s201.q4cdn.com May, July and August 2026 sales PDFs | curl + pypdf | 200 |
| 4 | sec.gov 10-Q Q3 FY26; 10-K FY2025; 10-K FY2024; 10-K FY2017; 8-K Ex. 99.1, 10 Jul 2024 | curl | 200 |
| 5 | sec.gov EDGAR 8-K filing index for Costco | curl | 200 |
| 6 | investor.costco.com quarterly results | curl | **403** |
| 7 | fool.com transcripts: Q2, Q3 and Q4 FY26; theglobeandmail.com Q4 syndication | curl | 200 (tier c) |
| 8 | costco.ca/f/-/new-locations; join-costco.html; membership-conditions-regulations.html; w/-/on/etobicoke/524 | curl | 200 |
| 9 | costco.ca Kirkland product-inquiry URLs (two guesses) | curl | 404 |
| 10 | Federal Court party search and recorded entries for T-3644-24 (fct-cf.gc.ca JSON endpoints) | curl | 200 |
| 11 | registredesactionscollectives.quebec | curl | **403** |
| 12 | canlii.org | curl | **403** |
| 13 | oipc.bc.ca Order P25-07 (PDF) | curl | 200 |
| 14 | citt-tcce.gc.ca decisions list (200); decision page 521491 (script-loaded, no text); 2024 annual report (200) | curl | partial |
| 15 | Competition Bureau: grocery study page (200); food-supply-chain notice (200); 2 Jun 2026 and 28 Sep 2026 releases (curl failed, read via [WF]) | curl / WF | see note |
| 16 | statcan.gc.ca Daily, 14 Sep 2026 | curl | 200 |
| 17 | ourcommons.ca AGRI meeting 91 (13 Feb 2024) and meeting 56 (17 Apr 2023) evidence. Meetings 55 and 57: 403. | curl | 200 |
| 18 | CBC: Windsor, Thunder Bay, chicken, receipts 2019, food court 2025, scanners 2024, Halifax, South Surrey, tariff suit, archives 1985, 2019 pharmacy penalty, Marketplace Cheat Sheet 27 Sep 2026 | curl | 200 |
| 19 | Global News: 2025 class action, Jun 2025 tariffs, Sep 2026 earnings, Dec 2025 grocery code, Belleville video | curl | 200 |
| 20 | CTV: Ottawa gas station (May 2026), Executive perk (Jun 2025); BNN Bloomberg (Sep 2026); Yahoo/FP (Mar 2025) | curl | 200 |
| 21 | protegez-vous.ca (Apr 2026); droit-inc; ledroit-enbref; insauga | curl | 200 |
| 22 | abacusdata.ca; ipsos.com PDF; leger360.com (2025 page, reputation-study page); media.toyota.ca; GlobeNewswire Pelmorex release ([WF], curl failed) | curl / WF | see note |
| 23 | grocerybusiness.ca; retail-insider.com; businesswire dunnhumby | curl / WF | **403** |
| 24 | web.archive.org (Wayback CDX and availability for the conditions page) | curl | connection reset / no snapshots |
| 25 | canada.ca AAFC grocery-code statement, July 2024 | curl | connection error |

---

## UNVERIFIED / DO-NOT-USE

**UNVERIFIED (could not open, or confirmed only below tier a/b):**
1. **What changed in the 1 Aug 2026 Membership Conditions.** No prior version was retrieved; the Wayback Machine returned no snapshot or a connection reset. Do not say "Costco changed X on Aug 1".
2. **Every earnings-call quote in §3.** They come from third-party transcripts, and investor.costco.com returned 403. Verify against the webcast, or attribute to "a published transcript".
3. **Exact opening days** for NE Edmonton, Lloydminster, E Windsor and Wasaga Beach. Costco lists only "November 2026".
4. **Rocky View County AB and a second Regina store** (search summaries only). **Belleville and Thunder Bay opening dates.**
5. **Leger 2026: Costco at #3.** Seen only through a third-party release via [WF]. Leger 2024 rank 10th: Daily Hive only.
6. **dunnhumby RPI** "Costco #1" (Business Wire returned 403).
7. **CITT AP-2024-004** decision content and outcome.
8. **AAFC July 2024 grocery-code statement** (the page did not load). It is cited through search results and Global/CBC.
9. **Quebec class-action registry and CanLII** searches. Both were blocked. Other Quebec, provincial or tribunal matters about Costco Wholesale Canada may exist.
10. **Whether the Federal Court has ruled** on the amendment motion after 10 Jun 2026. No later docket entry appeared as of 1 Oct 2026.
11. **The Fox Business quote** from Ron Vachris on scanners (Sept 2024).
12. **The "2026 combo change: bottled water option"**, and whether it applies in Canada. Also the Millerchip 2024 "hot dog price is safe" quote (transcript only).
13. **"Costco is Canada's #2 grocer at ~15% market share".** No source.
14. **CFIA $47,000 "Product of Canada" penalties; CBC Marketplace maple-washing; the Quebec maple-syrup class action amended Aug 2026.** Not opened.
15. **Kirkland Signature Product Inquiries notice** ("proprietary or confidential"). The page was not found.
16. **Canadian membership counts:**
    - Ipsos: "more than 10 million card-carrying members in Canada".
    - Riel, 17 Apr 2023: "15 million people in Canada have a membership card".
    - May 13 video: "Over 10 million Canadians".

    Costco's filings report no Canadian count, and these figures conflict. Attribute any one of them to its speaker, or skip.
17. **Uber Eats / DoorDash delivering from Costco in Canada.** Search summary only; Costco's Q4 remarks describe U.S. expansion.
18. **The FY2026 Canada segment** (full-year revenue, operating income, employees). The FY2026 10-K is not yet filed.
19. **Gas prices per litre** at any Canadian Costco. The page loads them by script, so none were captured.
20. **Whether the 2019 Ontario Ministry of Health penalty** (CWC Pharmacies Ontario Ltd.) was appealed or varied.
21. **The "Caught" video's publish date** (17 Sep 2026). Taken from the brief, not independently checked.
22. **The FY2025 10-K wage statement** that later increases (March 2026 / March 2027) were "locked in". Not seen in the text extracted.

**DO-NOT-USE (fails house rules):**
1. **All recall, food-safety and natural-health-product items** (Appendix §12), including "Caught" item 13.
2. **Health and pharmacy remarks**, including the Q4 call's GLP-1 and Medicare comments, and the 2019 Ontario pharmacy-rebate penalty in a consumer script. If the 2019 penalty is ever mentioned, use the ministry's wording only and label it a 2019 regulatory penalty.
3. **Prices not taken from a retailer's own site with date, store, pack size and unit price:**
   - Protégez-Vous's Greenworks $679.99 / $879.99 and the other items in its table;
   - Global's Glasslock $34.99 / $44.99 and pitcher $24.99 / $31.99 (these come from a pleading);
   - Narcity's Kirkland granola and other figures;
   - Daily Hive's bath tissue;
   - the blogger's detergent-pod weights;
   - Ex. 99.2 walnut, coffee and pepper prices (also likely USD/U.S.).
4. **Droit-inc's line "Costco admet ainsi contrevenir à l'article 54".** This is an outlet inference, **not an admission**. Saying it would imply wrongdoing.
5. **Any wording that the El Bechara case shows Costco "overcharged" or "broke the law".** It is a **proposed, uncertified class action, ALLEGATION only**. Costco has moved to strike it.
6. **"Canada is 45% more profitable than the U.S."** stated as fact without the cost-allocation caveat (§2.2), or **"more than half of everything Costco earns comes from fees"**. Say "membership fees equalled about half of company-wide operating income", and label it COMPANY-WIDE.
7. **"92.1% / 92.3% of Canadians renew".** These are **COMBINED U.S.+Canada** rates. No Canada-only rate is published.
8. **U.S.-only facts presented as Canadian:**
   - Executive early hours (U.S.);
   - Uber Eats / DoorDash expansion (U.S.);
   - IEEPA tariff refunds and the related class actions (U.S.);
   - the rotisserie "no preservatives" suit (U.S.);
   - U.S. gas-household penetration;
   - the $3.2B gas savings (company-wide);
   - U.S. average hourly wage (~$32, 10-K).
9. **"Caught" lines that imply motive:**
   - "didn't sign until the federal government said the word mandatory";
   - the "odd" absence of the Canadian case from the 10-K;
   - "Every price comparison video… was made in violation";
   - "We have nothing to hide, in a sentence that began by declining…".
10. **The Riel "private company / report our numbers globally" quote dated to February 2024.** If used at all, it must be dated **17 April 2023** and placed in its context: a question on grocery margins.
11. **The Executive-reward exclusion quoted as "optical centers"** without "(Quebec only)". Also the claim that the last three months "don't count" without the roll-forward sentence.
12. **The "secret" or "insider" framing from the 13 May video** (for example, price-tag codes "corroborated by former employees"). Rule 8 forbids it, since no named outlet quotes a named person.

<!-- ===== costco_value_math.md ===== -->

# Does a Costco Canada membership pay for itself? Documented arithmetic, 30 Sep - 1 Oct 2026

**Compiled:** 1 October 2026. Every price and fact below was opened on 1 Oct 2026; the capture times are in UTC. Most captures fall between 22:55 and 23:20 UTC (18:55 to 19:20 Eastern).
**Region chosen for the price basket:** Mississauga / western GTA, Ontario. The anchor postal code is L5V 2N6, which is the postal code walmart.ca assigned by default to store 1061.
**Currency:** CAD unless labelled. Costco Wholesale Corp. SEC figures are in USD and are not used for prices here.

**House rules applied:**
- No health, nutrition or food-safety claims. Product feature text such as protein or fibre wording is deliberately not quoted.
- Recalls are in the appendix only, marked "do not use on air". None were collected.
- Corporate claims are attributed.
- U.S., Canadian and combined figures are labelled.
- The legal item is labelled ALLEGATION.

---

## 0. HEADLINE FINDINGS (each one is sourced in the sections below)

1. **Fees, verbatim from costco.ca.** Gold Star costs $65 and Executive costs $130 ("plus applicable taxes"). The Executive upgrade is "an additional $65 a year". The 2% Reward "is capped at, and will not exceed, $1,250 for any 12-month period". (Re-opened 1 Oct 2026 23:16 UTC.)
2. **Break-even for the Executive upgrade.** $65 ÷ 0.02 = **$3,250 a year** of qualifying pre-tax purchases. That is $270.83 a month or $62.50 a week. The $1,250 cap is reached at $1,250 ÷ 0.02 = **$62,500 a year**. Costco itself says: "The Reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid."
3. **The break-even against an average grocery bill.** Statistics Canada's Survey of Household Spending (SHS) puts the average Canadian household's spending on **food purchased from stores in 2023 at $8,579** (Ontario: $7,974).
   - $3,250 is **37.9%** of that 2023 national figure (Ontario: 40.8%).
   - Scaling the 2023 figure to August 2026 prices with the food-from-stores CPI gives about $9,368. On that basis the break-even is about **34.7%** (Ontario: about 37.5%). This scaling is an illustrative computation, not a Statistics Canada figure.
4. **Food CPI.** Food purchased from stores, Canada, rose **6.3%** from August 2024 (187.7) to August 2026 (199.6). Food overall rose 6.4% (190.3 to 202.4). Source: Statistics Canada table 18-10-0004-01.
5. **Basket of 15 staples, captured from retailers' own sites.** Costco's online or Same-Day price was **lower per unit** for:
   - Terra Delyssa extra-virgin olive oil: 36% to 44% lower per 100 mL than the same brand's 1 L bottles elsewhere.
   - Quaker Quick Oats 5.16 kg: 27% lower than Real Canadian Superstore on Costco's current promotion, and 7% lower at Costco's regular price.
   - Bounty paper towels and Cashmere toilet paper, both on Costco promotions.
   - Tide Ultra Coldwater, per load as labelled: 6% to 13% lower.
   - Free-run eggs: 15% to 29% lower.
   - Kirkland 100% Colombian ground coffee against other 100% Colombian ground coffees: 12% to 31% lower.
   - Bananas: 7% lower than Loblaw banners.

   Costco was **not cheaper** for:
   - conventional large eggs (Costco's Same-Day site offered no conventional large-egg pack at this postal code);
   - store-brand butter;
   - 2% milk;
   - canned light tuna (15% to 86% higher);
   - 8 kg jasmine rice (33% to 108% higher);
   - chicken breast, compared with Walmart's price and with No Frills' current special;
   - big-canister mainstream ground coffee and store-brand coffee.
6. **Warehouse prices were NOT captured.** Costco does not publish in-warehouse shelf prices online. All Costco prices here come from costco.ca (online, delivery included) or Costco Same-Day (Instacart). Costco says online prices "may differ", and that Same-Day prices "are marked up higher than your local warehouse". No statement in this file describes warehouse prices.
7. **Gas.** costco.ca does publish per-warehouse gas prices through a service its warehouse pages call. On 1 Oct 2026 at 23:15 UTC, regular gasoline at six GTA-area warehouses was $1.599 to $1.669 per litre. Statistics Canada's Toronto average for regular self-serve in **August 2026** was 170.3 cents per litre. These are different months and cannot be compared like-for-like. September 2026 was not yet published. Costco says: "The gas station is open to Costco members only, with one exception: Costco Shop Card holders do not need to be members."
8. **Alternatives, at their own published prices:**
   - PC Optimum Insiders: $119 a year plus tax.
   - Amazon Prime Canada: $9.99 a month or $99 a year.
   - **Walmart+ is available in Canada**: $89 a year or $8.97 a month, plus taxes.
   - Instacart+ Canada: $99 a year or $9.99 a month.

---

## 1. METHOD

### 1.1 Retailers, channels, store and region

| Banner | Channel actually read | Store / region the site applied | How it was read |
|---|---|---|---|
| Costco (costco.ca) | Product pages `https://www.costco.ca/p/-/x/{id}` plus costco.ca's public search API `https://search.costco.ca/api/apps/www_costco_ca/query/www_costco_ca_search` | The page data shows `"warehouseNumber":"894"`, which is costco.ca's online price list. The search API returned location codes `801-bd` / `894_0-edi`. **No physical warehouse was selected.** | curl; price taken from the page's `displayPrice` (`onlinePrice`, `deliveredPrice`, discount) |
| Costco Same-Day (sameday.costco.ca, operated by Instacart) | Product pages with `?zipcode=L5V2N6&utm_source=nav` | Postal code L5V 2N6; Instacart "retailer location" **40595** (coordinates 43.607, -79.690, Mississauga). Two items, tuna and a 12-egg pack, were served from the default location 121687 (postal H3A 3J5, Montreal) and are flagged. | curl; server-rendered price |
| Real Canadian Superstore (RCSS) | Loblaw PC Express API `POST https://api.pcexpress.ca/pcx-bff/api/v1/products/search` (banner `superstore`) | Store **#1080**, 3050 Argentia Rd, Mississauga ON | curl; `price.type` gives REGULAR or SPECIAL and the expiry date |
| No Frills (NF) | Same API (banner `nofrills`) | Store **#3907**, 6085 Creditview Rd, Mississauga ON (L5V 2A8) | same |
| Walmart Canada | walmart.ca search pages, read with a mobile user-agent (the desktop user-agent is served a bot wall) | The page data shows postal code "L5V 2N6" and store **1061**. Some items list store **2000**, which is Walmart's online/ship-to-home store. | curl. Some calls returned walmart.ca's `/blocked` page and were retried later. |
| Voilà by Sobeys | voila.ca search pages (server state) | **No delivery address set.** The page state shows `"regionName":"Default Region 1"`. The catalogue returned includes dairies from several provinces, so **the region is not established**. Treat Voilà prices as lower-confidence. | curl |
| Giant Tiger | gianttiger.com Shopify suggest endpoint `/search/suggest.json` and product pages | Online price. Listings are tagged by province. Only listings tagged **ON** were used. Many grocery listings carry the tag `in_store_only:true`. | curl |

### 1.2 Rules used for the comparison

- **Unit price** = price ÷ quantity stated in the listing name or pack size, computed by me. Where a site showed its own unit price, it is noted.
- **Sale prices** are labelled. Costco promotions show the online regular price and the discount; Loblaw shows SPECIAL with an end date; Same-Day shows "reg." prices.
- **Like-for-like.** Same national brand across stores where possible. Otherwise Kirkland Signature is compared with the store brands (No Name, Great Value, Compliments, Giant Value) of the same product type.
- **Not like-for-like is flagged.** This covers organic versus conventional, free-run versus conventional, solid versus chunk tuna, and different sheet sizes in paper goods.
- **Costco's own statements on online pricing, verbatim:**
  - costco.ca product page (e.g. https://www.costco.ca/p/-/x/100416749, 1 Oct 2026): "Standard shipping via UPS is included in the quoted price." Also: "Item may be available in your local warehouse, prices may vary." Also: "Warehouse pricing may vary".
  - costco.ca Same-Day help, https://www.costco.ca/f/-/sameday-grocery-help (opened 23:19 UTC): "Item prices are marked up higher than your local warehouse. Instacart uses the markup to pay for their delivery service."
  - Global News (Saba Aziz, 14 Jan 2025) quotes Costco's website: "products sold online may have different pricing than the same products sold at your local Costco warehouse." See section 6.
- **Availability caveat.** Every costco.ca product page's schema data read "OutOfStock" when fetched without a delivery location. The costco.ca search API listed the same items as "in stock" at its online locations. Online availability on a given day is therefore unverified.
- **Never used:** Flipp, coupon blogs, Reddit, aggregators.

---

## 2. (A) THE BASKET: 15 STAPLES, PRICES AS CAPTURED

The tables are ordered by item. **Bold** = computed unit price.


#### Eggs, large (per egg)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Free Run Large Eggs | 24 ct | $10.20 | shown | **$0.425/egg** | 2026-10-01 22:59 | https://sameday.costco.ca/store/costco-canada/products/63993483-ks-gros-oeufs-en-libert-paquet-de-24 |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Large Size Eggs | 12 | $3.93 | REGULAR | **$0.328/egg** | 2026-10-01 23:02 | https://www.realcanadiansuperstore.ca/large-size-eggs-12-pack/p/20812144001_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | President's Choice Free Run Brown Eggs Large | 12 | $7.15 | REGULAR | **$0.596/egg** | 2026-10-01 23:02 | https://www.realcanadiansuperstore.ca/free-run-brown-eggs-large/p/20813628001_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | No Name Large Size Eggs | 12 | $3.93 | REGULAR | **$0.328/egg** | 2026-10-01 23:03 | https://www.nofrills.ca/large-size-eggs-12-pack/p/20812144001_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | President's Choice Free Run Brown Eggs Large | 12 | $7.18 | REGULAR | **$0.598/egg** | 2026-10-01 23:03 | https://www.nofrills.ca/free-run-brown-eggs-large/p/20813628001_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Great Value Large 12 Eggs | 12 | $3.93 | shown | **$0.328/egg** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Great-Value-Large-12-Eggs/10052944 |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | GoldEgg Free Run Large White 30 Eggs | 30 | $14.98 | shown | **$0.499/egg** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/GoldEgg-Free-Run-Large-White-30-Eggs/31FWPJLZ3WHE |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments White Eggs Large 30 Count | 30 | $9.99 | shown | **$0.333/egg** | 2026-10-01 23:06 | https://voila.ca/products/search?q=large+eggs (SKU 627073EA) |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments White Eggs Free Run Large 12 Count | 12 | $6.99 | shown | **$0.583/egg** | 2026-10-01 23:06 | https://voila.ca/products/search?q=large+eggs (SKU 552028EA) |
| gianttiger.com (ON-tagged listing; online price) | Burnbrae Farms Large Eggs, 12-Pack (tag in_store_only:true) | 12 | $3.93 | shown | **$0.328/egg** | 2026-10-01 23:08 | https://www.gianttiger.com/products/burnbrae-farms-large-eggs-12-pack-8 |

#### Butter, 454 g (per 100 g)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature Organic Salted Butter | 454 g | $8.99 | online price | **$1.980/100 g** | 2026-10-01 23:11 | https://www.costco.ca/p/-/x/100558748 |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Natrel Butter Salted 454g | 454 g | $6.57 | shown | **$1.447/100 g** | 2026-10-01 23:00 | https://sameday.costco.ca/store/costco-canada/products/18603775-natrel-salted-butter-454-g |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Salted Butter | 454 g | $5.99 | REGULAR | **$1.319/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/salted-butter/p/20325029_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Lactantia Salted Butter | 454 g | $4.97 | SPECIAL to 2026-10-07 (was 8.49) | **$1.095/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/salted-butter/p/20639926_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | No Name Salted Butter | 454 g | $6.00 | REGULAR | **$1.322/100 g** | 2026-10-01 23:03 | https://www.nofrills.ca/salted-butter/p/20325029_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Great Value Salted Butter | 454 g (site shows $1.31/100g) | $5.96 | shown | **$1.313/100 g** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Great-Value-Salted-Butter/6000200237828 |
| Voila by Sobeys (no address set; 'Default Region 1') | Natrel Salted Butter 454 g | 454 g | $8.99 | shown | **$1.980/100 g** | 2026-10-01 23:07 | https://voila.ca/products/search?q=salted+butter (SKU 497422EA) |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments Salted Butter 454 g | 454 g | $5.99 | shown | **$1.319/100 g** | 2026-10-01 23:07 | https://voila.ca/products/search?q=salted+butter (SKU 1454895EA) |
| gianttiger.com (ON-tagged listing; online price) | Giant Value Salted Butter, 454 g (in_store_only:true) | 454 g | $4.87 | shown | **$1.073/100 g** | 2026-10-01 23:08 | https://www.gianttiger.com/products/giant-value-salted-butter-454-g |

#### Milk 2%, 4 L (per L)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | 2% Milk (URL slug: beatrice-2-milk-4-l) | 4 L | $6.91 | shown | **$1.728/L** | 2026-10-01 23:00 | https://sameday.costco.ca/store/costco-canada/products/19461863-beatrice-2-milk-4-l |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Organic 2% Milk | 4 L | $11.68 | shown | **$2.920/L** | 2026-10-01 23:00 | https://sameday.costco.ca/store/costco-canada/products/24104424-kirkland-signature-organic-2-milk-4-l |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Neilson 2% Milk | 4 L | $6.44 | REGULAR | **$1.610/L** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/2-milk/p/20188873_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | PC Organics Organic Partly Skimmed Milk 2% M.F. | 4 L | $11.49 | REGULAR | **$2.873/L** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/organic-partly-skimmed-milk-2-m-f/p/20304385_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Neilson 2% Milk | 4 L | $6.44 | REGULAR | **$1.610/L** | 2026-10-01 23:03 | https://www.nofrills.ca/2-milk/p/20188873_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Sealtest Partly Skimmed 2% Milk (site shows 16 cents/100ml) | 4 L | $6.44 | shown | **$1.610/L** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Sealtest-Partly-Skimmed-2-Milk/6000199044832 |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Natrel Organic Fine-Filtered 2% Milk 4L | 4 L | $10.96 | shown | **$2.740/L** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Natrel-Organic-Fine-Filtered-2-Milk-4L/10220342 |
| Voila by Sobeys (no address set; 'Default Region 1') | Sealtest 2% Milk Partly Skimmed 4 L | 4 L | $6.49 | shown | **$1.623/L** | 2026-10-01 23:07 | https://voila.ca/products/search?q=2%25+milk+4+l (SKU 507464EA) |
| gianttiger.com (ON-tagged listing; online price) | Reid's Dairy Partly Skimmed Milk 2% M.F., 4-L (in_store_only:true) | 4 L | $6.44 | shown | **$1.610/L** | 2026-10-01 23:08 | https://www.gianttiger.com/products/reids-dairy-partly-skimmed-milk-2-m-f-4-l |

#### Ground coffee (per 100 g)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature Dark Colombian Ground Coffee | 1.36 kg | $34.99 | online price | **$2.573/100 g** | 2026-10-01 23:11 | https://www.costco.ca/p/-/x/100411882 |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Dark Colombian Ground Coffee | 1.36 kg | $32.90 | shown | **$2.419/100 g** | 2026-10-01 23:02 | https://sameday.costco.ca/store/costco-canada/products/20651416-kirkland-signature-100-colombian-filter-coffee |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | President's Choice Single Origin Colombian Medium Roast Fine Grind | 340 g | $11.99 | REGULAR | **$3.526/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/single-origin-colombian-medium-roast-fine-grind-co/p/21380579_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Medium Roast Ground Coffee | 907 g | $15.99 | REGULAR | **$1.763/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/medium-roast-ground-coffee/p/21707399_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Maxwell House Medium Original Roast Ground Coffee | 864 g | $16.00 | SPECIAL to 2026-10-07 (was 18.99) | **$1.852/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/medium-original-roast-ground-coffee/p/21606882_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | No Name Medium Roast Ground Coffee | 907 g | $15.00 | REGULAR | **$1.654/100 g** | 2026-10-01 23:03 | https://www.nofrills.ca/medium-roast-ground-coffee/p/21707399_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Maxwell House Medium Original Roast Ground Coffee | 864 g | $18.99 | REGULAR | **$2.198/100 g** | 2026-10-01 23:03 | https://www.nofrills.ca/medium-original-roast-ground-coffee/p/21606882_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Maxwell House Original Roast Ground Coffee, 864 g Canister | 864 g | $18.97 | shown | **$2.196/100 g** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Maxwell-House-Original-Roast-Ground-Coffee-864-g-Canister/37PCONNSAJI9 |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments Ground Coffee 100% Columbian 300 g | 300 g | $10.99 | shown | **$3.663/100 g** | 2026-10-01 23:07 | https://voila.ca/products/search?q=ground+coffee (SKU 589696EA) |
| Voila by Sobeys (no address set; 'Default Region 1') | Maxwell House Ground Coffee Original Roast 864 g | 864 g | $21.49 | shown | **$2.487/100 g** | 2026-10-01 23:07 | https://voila.ca/products/search?q=ground+coffee (SKU 1008964EA) |
| gianttiger.com (ON-tagged listing; online price) | Giant Tiger Marche Ground Columbian Coffee, 340 g | 340 g | $9.97 | shown | **$2.932/100 g** | 2026-10-01 23:08 | https://www.gianttiger.com/products/giant-tiger-marche-ground-columbian-coffee-340-g |
| gianttiger.com (ON-tagged listing; online price) | Maxwell House Ground Coffee Original Roast Medium, 864 g | 864 g | $17.97 | shown | **$2.080/100 g** | 2026-10-01 23:08 | https://www.gianttiger.com/products/maxwell-house-ground-coffee-original-roast-medium-864-g |

#### Olive oil (per 100 mL)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature 100% Spanish Extra Virgin Olive Oil | 3 L | $36.99 | online price | **$1.233/100 mL** | 2026-10-01 23:11 | https://www.costco.ca/p/-/x/100799194 |
| costco.ca (online, warehouse 894 price list; shipping included) | Terra Delyssa Extra Virgin Olive Oil | 3 L | $31.99 | online price | **$1.066/100 mL** | 2026-10-01 23:11 | https://www.costco.ca/p/-/x/100552507 |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Extra Virgin Olive Oil | 3 L | $34.04 | shown | **$1.135/100 mL** | 2026-10-01 23:01 | https://sameday.costco.ca/store/costco-canada/products/21132189-kirkland-signature-extra-virgin-olive-oil-3-l |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Extra Virgin Olive Oil Club Size | 3 L | $30.00 | SPECIAL to 2026-10-07 | **$1.000/100 mL** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/extra-virgin-olive-oil-club-size/p/20141395_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Terra Delyssa Premium Extra Virgin Olive Oil | 1 L | $19.00 | REGULAR | **$1.900/100 mL** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/premium-extra-virgin-olive-oil/p/20729461_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | No Name 100% Extra Virgin Olive Oil | 750 mL | $9.00 | REGULAR | **$1.200/100 mL** | 2026-10-01 23:03 | https://www.nofrills.ca/100-extra-virgin-olive-oil/p/20047715_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Terra Delyssa Premium Extra Virgin Olive Oil | 1 L | $16.79 | REGULAR | **$1.679/100 mL** | 2026-10-01 23:03 | https://www.nofrills.ca/premium-extra-virgin-olive-oil/p/20729461_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Great Value Extra Virgin Olive Oil 1L | 1 L | $10.97 | shown | **$1.097/100 mL** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Great-Value-Extra-Virgin-Olive-Oil-1L/6000203408497 |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Terra Delyssa Premium Smooth Extra Virgin Olive Oil 1L | 1 L | $16.77 | shown | **$1.677/100 mL** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Terra-Delyssa-Premium-Smooth-Extra-Virgin-Olive-Oil-Single-Origin-Contains-Polyphenols-1L/6000196167259 |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments Olive Oil Extras Virgin Pure Rich Taste 2 L | 2 L | $28.99 | shown | **$1.450/100 mL** | 2026-10-01 23:07 | https://voila.ca/products/search?q=extra+virgin+olive+oil (SKU 850785EA) |
| gianttiger.com (ON-tagged listing; online price) | Terra Delyssa Extra Virgin Olive Oil, 500-ml (handle: chefs-edition) | 500 mL | $8.96 | shown | **$1.792/100 mL** | 2026-10-01 23:08 | https://www.gianttiger.com/products/terra-delyssa-first-cold-pressed-extra-virgin-olive-oil-chefs-edition-500-ml |

#### Oats (per 100 g)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature Whole Grain Rolled Oats | 4.54 kg | $11.99 | online price | **$0.264/100 g** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/4000339745 |
| costco.ca (online, warehouse 894 price list; shipping included) | Quaker Quick Oats, 2 x 2.58 kg | 5.16 kg | $10.99 | online, $3.00 off $13.99 (promo 2026-09-28 to 2026-10-26) | **$0.213/100 g** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/100570610 |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Whole Grain Rolled Oats | 4.54 kg | $11.34 | shown | **$0.250/100 g** | 2026-10-01 23:01 | https://sameday.costco.ca/store/costco-canada/products/84469724-kirkland-signature-whole-grain-rolled-oats-4-54-kg |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Quaker Quick Oats | 5.16 kg | $14.99 | REGULAR | **$0.291/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/quaker-quick-oats/p/21294986_C01 |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Large Flake 100% Whole Grain Oats Club Size | 2.25 kg | $5.50 | SPECIAL to 2026-10-07 (was 6.00) | **$0.244/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/large-flake-100-whole-grain-oats-club-size/p/20923840_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Quaker Quick Oats | 2.25 kg | $7.29 | REGULAR | **$0.324/100 g** | 2026-10-01 23:03 | https://www.nofrills.ca/quick-oats/p/20053840_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Great Value Quick Oats 1 kg | 1 kg | $2.77 | shown | **$0.277/100 g** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Great-Value-Quick-Oats-1-kg/6000195340329 |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Quaker Large Flake Oats, 1kg | 1 kg | $3.97 | shown | **$0.397/100 g** | 2026-10-01 23:04 | https://www.walmart.ca/en/ip/Quaker-Large-Flake-Oats-1kg/10284789 |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments Quick Oats 2.25 kg | 2.25 kg | $6.79 | shown | **$0.302/100 g** | 2026-10-01 23:08 | https://voila.ca/products/search?q=quick+oats (SKU 487320EA) |
| Voila by Sobeys (no address set; 'Default Region 1') | Quaker Quick Oats 2.25 kg | 2.25 kg | $7.99 | shown | **$0.355/100 g** | 2026-10-01 23:08 | https://voila.ca/products/search?q=quick+oats (SKU 217690EA) |
| gianttiger.com (ON-tagged listing; online price) | Giant Value Large Flake Oats, 1 kg | 1 kg | $2.77 | shown | **$0.277/100 g** | 2026-10-01 23:08 | https://www.gianttiger.com/products/giant-value-large-flake-oats-1-kg |

#### Peanut butter (per 100 g)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kraft Smooth Peanut Butter | 2 kg | $10.99 | online, $2.00 off $12.99 (promo ends 2026-10-05) | **$0.549/100 g** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/100417656 |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kraft Smooth Peanut Butter | 2 kg | $9.07 | shown, 'reg. $11.07' | **$0.454/100 g** | 2026-10-01 23:02 | https://sameday.costco.ca/store/costco-canada/products/17881950-smooth-light-peanut-butter-2-kg |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Kraft Smooth Peanut Butter | 2 kg | $12.00 | REGULAR | **$0.600/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/smooth-peanut-butter/p/20064825001_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Smooth Peanut Butter, Club Size | 2 kg | $9.00 | REGULAR | **$0.450/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/smooth-peanut-butter-club-size/p/20323398002_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Kraft Smooth Peanut Butter | 2 kg | $11.00 | REGULAR | **$0.550/100 g** | 2026-10-01 23:03 | https://www.nofrills.ca/smooth-peanut-butter/p/20064825001_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | No Name Smooth Peanut Butter, Club Size | 2 kg | $9.00 | REGULAR | **$0.450/100 g** | 2026-10-01 23:03 | https://www.nofrills.ca/smooth-peanut-butter-club-size/p/20323398002_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Kraft Smooth Peanut Butter, 2 kg Jar | 2 kg | $10.97 | shown | **$0.548/100 g** | 2026-10-01 23:05 | https://www.walmart.ca/en/ip/Kraft-Smooth-Peanut-Butter-2-kg-Jar/10304164 |
| Voila by Sobeys (no address set; 'Default Region 1') | Kraft Peanut Butter Smooth 2 kg | 2 kg | $12.99 | shown | **$0.649/100 g** | 2026-10-01 23:07 | https://voila.ca/products/search?q=peanut+butter (SKU 552135EA) |
| gianttiger.com (ON-tagged listing; online price) | Kraft Smooth Peanut Butter, 1 kg | 1 kg | $6.97 | shown | **$0.697/100 g** | 2026-10-01 23:08 | https://www.gianttiger.com/products/kraft-smooth-peanut-butter-1kg-1 |

#### Canned light tuna in water (per 100 g)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature Solid Light Tuna in Water, 8 x 184 g | 1,472 g | $19.99 | online price | **$1.358/100 g** | 2026-10-01 23:11 | https://www.costco.ca/p/-/x/100417042 |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Clover Leaf Chunk Light Tuna, Skip Jack In Water | 170 g | $2.00 | REGULAR | **$1.176/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/chunk-light-tuna-skip-jack-in-water/p/20018117001_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Chunk Light Tuna Packed in Water | 170 g | $1.39 | REGULAR | **$0.818/100 g** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/chunk-light-tuna-packed-in-water/p/20521647_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Clover Leaf Chunk Light Tuna, Skip Jack In Water | 170 g | $1.99 | REGULAR | **$1.171/100 g** | 2026-10-01 23:03 | https://www.nofrills.ca/chunk-light-tuna-skip-jack-in-water/p/20018117001_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Clover LEAF Chunk Light Tuna in Water (site shows 73 cents/100g) | 170 g | $1.24 | shown, 'was $1.88' | **$0.729/100 g** | 2026-10-01 23:13 | https://www.walmart.ca/en/ip/Clover-LEAF-Chunk-Light-Tuna-in-Water/10182587 |
| gianttiger.com (ON-tagged listing; online price) | Clover Leaf Flaked Light Tuna Skipjack in Water - 170g | 170 g | $1.87 | shown | **$1.100/100 g** | 2026-10-01 23:08 | https://www.gianttiger.com/products/clover-leaf-flaked-light-tuna-skipjack-in-water-170g-1 |
| gianttiger.com (ON-tagged listing; online price) | Giant Value Flaked Light Tuna, 170 g | 170 g | $1.24 | shown | **$0.729/100 g** | 2026-10-01 23:08 | https://www.gianttiger.com/products/giant-value-flaked-light-tuna-170g-1 |

#### Toilet paper (per 100 sheets)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature 2-ply Bath Tissue, 30-pack, '380 sheets per roll' | 30 x 380 = 11,400 sheets | $32.99 | online price | **$0.289/100 sheets** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/4000111232 |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature 2-Ply Bath Tissue 30 ct (URL: '380-sheets') | 30 x 380 = 11,400 sheets | $27.23 | shown | **$0.239/100 sheets** | 2026-10-01 23:01 | https://sameday.costco.ca/store/costco-canada/products/20243446-kirkland-signature-2-ply-380-sheets-bath-tissue-rolls-30-ct |
| costco.ca (online, warehouse 894 price list; shipping included) | Cashmere Premium Soft & Thick Toilet Paper, 40-pack, '250 sheets per roll' | 40 x 250 = 10,000 sheets | $29.49 | online, $5.50 off $34.99 (promo 2026-09-28 to 2026-10-26) | **$0.295/100 sheets** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/100572733 |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Royale Everyday Comfort, 30 Equal 60 Rolls, 242 sheets per roll | 30 x 242 = 7,260 sheets | $16.97 | SPECIAL to 2026-10-07 (was 19.99) | **$0.234/100 sheets** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/everyday-comfort-toilet-paper-30-equal-60-rolls-24/p/21378233_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Royale Everyday Comfort, 30 Equal 60 Rolls, 242 sheets per roll | 30 x 242 = 7,260 sheets | $18.99 | REGULAR | **$0.262/100 sheets** | 2026-10-01 23:03 | https://www.nofrills.ca/everyday-comfort-toilet-paper-30-equal-60-rolls-24/p/21378233_EA |
| walmart.ca, online store 2000 (postal L5V 2N6 shown) | Great Value ECO Bathroom Tissue, 12 Double Rolls, 242 Sheets, 2-Ply | 12 x 242 = 2,904 sheets | $7.94 | shown | **$0.273/100 sheets** | 2026-10-01 23:12 | https://www.walmart.ca/en/ip/Great-Value-ECO-Bathroom-Tissue-12-Double-Rolls-242-Sheets-2-Ply/6000202479531 |
| Voila by Sobeys (no address set; 'Default Region 1') | Cashmere Toilet Paper 2-Ply 24 Double Rolls x 242 Sheets | 24 x 242 = 5,808 sheets | $21.49 | shown | **$0.370/100 sheets** | 2026-10-01 23:07 | https://voila.ca/products/search?q=bathroom+tissue (SKU 948158EA) |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments Toilet Paper Satiny Soft 2-Ply 24 Rolls x 242 Sheets | 24 x 242 = 5,808 sheets | $16.99 | shown | **$0.293/100 sheets** | 2026-10-01 23:07 | https://voila.ca/products/search?q=bathroom+tissue (SKU 5015EA) |

#### Paper towels (per 100 sheets)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature 2-ply Paper Towels, 12 x 160 sheets | 1,920 sheets | $34.99 | online price | **$1.822/100 sheets** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/100363149 |
| costco.ca (online, warehouse 894 price list; shipping included) | Bounty Plus Paper Towel, 12 x 91 Sheets | 1,092 sheets | $33.49 | online, $6.50 off $39.99 (promo 2026-09-28 to 2026-10-26) | **$3.067/100 sheets** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/4000339232 |
| costco.ca (online, warehouse 894 price list; shipping included) | SpongeTowels Premium Paper Towels, 12 x 106 sheets | 1,272 sheets | $36.99 | online price | **$2.908/100 sheets** | 2026-10-01 23:11 | https://www.costco.ca/p/-/x/4000041720 |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Royale Ultra Strength Paper Towel, 6 Equal 12 Rolls, 98 Sheets per Roll | 6 x 98 = 588 sheets | $15.00 | SPECIAL to 2026-10-07 (was 19.99) | **$2.551/100 sheets** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/ultra-strength-paper-towel-6-equal-12-rolls-98-she/p/21484732_EA |
| walmart.ca, online store 2000 (postal L5V 2N6 shown) | Bounty Paper Towels Select-A-Size White, 4 Triple Rolls, 123 Sheets Per Roll | 4 x 123 = 492 sheets | $18.48 | shown | **$3.756/100 sheets** | 2026-10-01 23:12 | https://www.walmart.ca/en/ip/Bounty-Paper-Towels-Select-A-Size-White-4-Triple-Rolls-123-Sheets-Per-Roll/1VDL66QI8PCC |
| Voila by Sobeys (no address set; 'Default Region 1') | Bounty Paper Towel 2-Ply 8 Triple Rolls x 123 Sheets | 8 x 123 = 984 sheets | $34.99 | shown | **$3.556/100 sheets** | 2026-10-01 23:07 | https://voila.ca/products/search?q=paper+towels (SKU 1317288EA) |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments Ultra Paper Towel 2-Ply 12 Rolls x 144 Sheets | 12 x 144 = 1,728 sheets | $23.99 | shown | **$1.388/100 sheets** | 2026-10-01 23:07 | https://voila.ca/products/search?q=paper+towels (SKU 1298979EA) |

#### Tide Ultra Coldwater liquid (per load, as labelled)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Tide Ultra Coldwater Clean Liquid Laundry Detergent, 124 Loads | 124 loads | $34.99 | online price | **$0.282/load** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/4000363006 |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Tide Ultra Coldwater Liquid, Original Scent, 83 Loads, 3.46 L | 83 loads | $26.99 | REGULAR | **$0.325/load** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/ultra-coldwater-liquid-laundry-detergent-original/p/21671018_EA |
| walmart.ca, online store 2000 (postal L5V 2N6 shown) | Tide Ultra Coldwater Liquid, Original Scent, 3.46 L, 83 Loads | 83 loads | $24.97 | shown | **$0.301/load** | 2026-10-01 23:12 | https://www.walmart.ca/en/ip/Tide-Ultra-Coldwater-Liquid-Laundry-Detergent-Original-Scent-3-46-L-83-Loads-Laundry-Detergent-Liquid-Formulated-for-Cold-Water/6000208860504 |

#### Kirkland detergent (per load, as labelled)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature Ultra Clean Premium Laundry Detergent, 146 wash loads | 146 loads | $24.99 | online price | **$0.171/load** | 2026-10-01 23:10 | https://www.costco.ca/p/-/x/100388606 |

#### Bananas (per kg)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Banana | 1.36 kg | $1.92 | shown | **$1.412/kg** | 2026-10-01 22:59 | https://sameday.costco.ca/store/costco-canada/products/17328915-banana-3-lbs |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Bananas, Bunch (sold by weight; site shows $1.52/kg) | per kg | $1.52 | REGULAR | **$1.520/kg** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/bananas-bunch/p/20175355001_KG |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Bananas, Bunch (sold by weight; site shows $1.52/kg) | per kg | $1.52 | REGULAR | **$1.520/kg** | 2026-10-01 23:03 | https://www.nofrills.ca/bananas-bunch/p/20175355001_KG |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Banana, Sold in singles, 0.15-0.23 KG ($0.35 each; site shows 15 cents/100g) | per kg (site unit price) | $1.50 | shown | **$1.500/kg** | 2026-10-01 23:13 | https://www.walmart.ca/en/ip/banana/875806 |
| Voila by Sobeys (no address set; 'Default Region 1') | Bananas 1 Bunch (5 - 6 bananas) (site shows $2.18/kg) | per kg | $2.18 | shown | **$2.180/kg** | 2026-10-01 23:07 | https://voila.ca/products/search?q=bananas (SKU 7630KG) |
| gianttiger.com (ON-tagged listing; online price) | Bananas, 3 lbs (in_store_only:true) | 3 lb = 1.361 kg | $2.04 | shown | **$1.499/kg** | 2026-10-01 23:08 | https://www.gianttiger.com/products/banana-3-lbs |

#### Chicken breast, boneless skinless, fresh (per kg)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Boneless Skinless Chicken Breasts ($17.58/kg; ~$39.38/pkg est.) | per kg | $17.58 | shown | **$17.580/kg** | 2026-10-01 23:00 | https://sameday.costco.ca/store/costco-canada/products/29561251-ks-halal-boneless-skinless-chicken-breasts-each |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Chicken Breast, Club Pack Boneless Skinless (site shows $18.28/kg) | per kg | $18.28 | REGULAR | **$18.280/kg** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/chicken-breast-club-pack-boneless-skinless/p/20593099_KG |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Club Pack Chicken Breasts, Boneless Skinless 2 kg | 2 kg | $42.99 | REGULAR | **$21.495/kg** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/club-pack-chicken-breasts-boneless-skinless/p/20702394_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Chicken Breast Boneless & Skinless, Club Pack (site shows $10.76/kg) | per kg | $10.76 | SPECIAL to 2026-10-07 | **$10.760/kg** | 2026-10-01 23:03 | https://www.nofrills.ca/chicken-breast-boneless-skinless-club-pack/p/20654124_KG |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Maple Leaf Boneless Skinless Chicken Breasts, 6-7 pc (site shows $1.27/100g) | per kg | $12.70 | shown | **$12.700/kg** | 2026-10-01 23:13 | https://www.walmart.ca/en/ip/maple-leaf-boneless-skinless-chicken-breasts/3Z4HSOD28G07 |
| Voila by Sobeys (no address set; 'Default Region 1') | Compliments Chicken Breasts Boneless Skinless Value Pack 4 Pack (site shows $17.13/kg) | per kg | $17.13 | shown | **$17.130/kg** | 2026-10-01 23:07 | https://voila.ca/products/search?q=boneless+skinless+chicken+breast (SKU 585104KG) |
| gianttiger.com (ON-tagged listing; online price) | Prime Boneless Skinless Chicken Breast, 474 g (in_store_only:true) | 474 g | $9.97 | shown | **$21.034/kg** | 2026-10-01 23:08 | https://www.gianttiger.com/products/prime-boneless-skinless-chicken-breast-474-g |

#### Jasmine rice, 8 kg (per kg)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature Thai Hom Mali Jasmine Rice | 8 kg | $30.99 | online price | **$3.874/kg** | 2026-10-01 23:11 | https://www.costco.ca/p/-/x/4000107096 |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Thai Hom Mali Jasmine Rice | 8 kg | $26.66 | shown | **$3.333/kg** | 2026-10-01 23:02 | https://sameday.costco.ca/store/costco-canada/products/21018892-kirkland-signature-p120-h48-thai-hom-mali-jasmine-rice-8-kg |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Jasmine Gold Thai Jasmine Rice | 8 kg | $19.99 | REGULAR | **$2.499/kg** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/thai-jasmine-rice/p/21496274_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | Royal Umbrella Thai Jasmine Rice | 8 kg | $19.99 | REGULAR | **$2.499/kg** | 2026-10-01 23:03 | https://www.nofrills.ca/thai-jasmine-rice/p/20710232_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Delicious Kitchen Premium Jasmine Scented White Rice 8kg | 8 kg | $14.88 | shown | **$1.860/kg** | 2026-10-01 23:13 | https://www.walmart.ca/en/ip/Delicious-Kitchen-Premium-Jasmine-Scented-White-Rice-8kg/6000197088557 |
| Voila by Sobeys (no address set; 'Default Region 1') | Rose White Rice Jasmine Scent Value Size 8 kg | 8 kg | $26.99 | shown | **$3.374/kg** | 2026-10-01 23:08 | https://voila.ca/search?q=jasmine+rice (SKU 912076EA) |
| gianttiger.com (ON-tagged listing; online price) | Pacific Star Jasmine Rice, 8-kg | 8 kg | $19.97 | shown | **$2.496/kg** | 2026-10-01 23:08 | https://www.gianttiger.com/products/pacific-star-jasmine-rice-8-kg |

#### Cheddar block (per kg)

| Retailer / store-region | Product (as listed) | Pack | Price (CAD) | Price status | Unit price (computed) | Captured (UTC) | URL opened |
|---|---|---|---|---|---|---|---|
| costco.ca (online, warehouse 894 price list; shipping included) | Kirkland Signature Marble Cheddar Cheese | 1.15 kg | $14.99 | online price | **$13.035/kg** | 2026-10-01 23:11 | https://www.costco.ca/p/-/x/100559615 |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Old Cheddar Cheese | 1.15 kg | $18.15 | shown | **$15.783/kg** | 2026-10-01 23:01 | https://sameday.costco.ca/store/costco-canada/products/21114419-kirkland-signature-t108h5p540-ec-wc-sl70-old-cheddar-cheese-1-15-kg |
| Costco Same-Day (Instacart), postal L5V 2N6, location 40595 | Kirkland Signature Marble Cheddar Cheese | 1.15 kg | $13.61 | shown, 'reg. $17.61' | **$11.835/kg** | 2026-10-01 23:01 | https://sameday.costco.ca/store/costco-canada/products/21115064-kirkland-signature-marble-cheddar-cheese-1-15-kg |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | No Name Old Cheddar Cheese | 700 g | $8.79 | REGULAR | **$12.557/kg** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/old-cheddar-cheese/p/20975873_EA |
| Real Canadian Superstore #1080, 3050 Argentia Rd, Mississauga ON | Black Diamond Marble Cheddar Cheese Bar | 400 g | $5.49 | SPECIAL to 2026-10-07 (was 7.49) | **$13.725/kg** | 2026-10-01 23:03 | https://www.realcanadiansuperstore.ca/marble-cheddar-cheese-bar/p/21279221_EA |
| No Frills #3907, 6085 Creditview Rd, Mississauga ON | No Name Old Cheddar Cheese | 700 g | $10.00 | REGULAR | **$14.286/kg** | 2026-10-01 23:03 | https://www.nofrills.ca/old-cheddar-cheese/p/20975873_EA |
| walmart.ca, store 1061 (postal L5V 2N6, Mississauga ON) | Great Value Old Cheddar Cheese (site shows $1.37/100g, i.e. 400 g) | 400 g | $5.48 | shown | **$13.700/kg** | 2026-10-01 23:13 | https://www.walmart.ca/en/ip/great-value-old-cheddar-cheese/6000208884796 |
| gianttiger.com (ON-tagged listing; online price) | Black Diamond Marble Cheddar Cheese 32% M.F. - 400g (in_store_only:true) | 400 g | $6.97 | shown | **$17.425/kg** | 2026-10-01 23:08 | https://www.gianttiger.com/products/black-diamond-marble-cheddar-cheese-32-m-f-400g-1 |

---

## 3. (A, continued) WHERE COSTCO IS CHEAPER, WHERE IT IS NOT, AND BY HOW MUCH

All percentages are computed from the tables above: (Costco unit price ÷ comparison unit price) − 1. A negative number means Costco is cheaper.

- "Costco online" means costco.ca, delivery included.
- "SD" means Costco Same-Day at L5V 2N6.
- These are **not warehouse prices**.

### 3.1 Same national brand at Costco and elsewhere

| Item | Costco unit price | Comparison | Difference | Note |
|---|---|---|---|---|
| Terra Delyssa EVOO | Costco online 3 L: $1.066/100 mL | Walmart 1 L $1.677 · No Frills 1 L $1.679 · RCSS 1 L $1.900 | **−36.4% · −36.5% · −43.9%** | Pack size differs (3 L vs 1 L). The line names also differ: "Extra Virgin" at Costco, "Premium" at Loblaw, "Premium Smooth" at Walmart. |
| Quaker Quick Oats 5.16 kg (same pack) | Costco online $10.99 on promotion ($13.99 regular) | RCSS $14.99 regular | **−26.7%** on promotion · **−6.7%** at Costco's regular price | Costco's $3.00 discount runs 2026-09-28 to 2026-10-26 (page data). |
| Kraft Smooth Peanut Butter 2 kg | Costco online $10.99 on promotion ($12.99 regular); SD $9.07 ("reg. $11.07") | Walmart $10.97 · NF $11.00 · RCSS $12.00 · Voilà $12.99 | Costco online promo **+0.2%** vs Walmart; Costco online regular **+18.4%** vs Walmart; **SD promo −17.3%** vs Walmart; SD regular **+0.9%** | The costco.ca promotion ends 2026-10-05. |
| Bounty paper towels (per 100 sheets as labelled) | Costco online 12 x 91: $3.067 on promotion ($3.662 regular) | Walmart 4 x 123: $3.756 · Voilà 8 x 123: $3.556 | Promo **−18.4% / −13.8%** · regular **−2.5% / +3.0%** | Bounty Plus versus Select-A-Size; sheet dimensions are not stated, so "per sheet" is approximate. |
| Cashmere toilet paper (per 100 sheets) | Costco online 40 x 250: $0.295 on promotion ($0.350 regular) | Voilà 24 double rolls x 242: $0.370 | Promo **−20.3%** · regular **−5.4%** | Promotion 2026-09-28 to 2026-10-26. |
| Tide Ultra Coldwater (per load as labelled) | Costco online 124 loads: $0.282 | RCSS 83 loads $0.325 · Walmart 83 loads $0.301 | **−13.2% · −6.2%** | No Frills had the 3.46 L jug at $22.00 SPECIAL (to Oct 7), but that listing gives no load count, so no per-load figure was computed. Load counts are P&G's labels. Costco's product is "Coldwater Clean"; the others are "Ultra Coldwater ... Original Scent". |
| Natrel salted butter 454 g | SD $6.57 | Voilà $8.99 | **−26.9%** | Same-Day is Costco's marked-up channel (Costco's own statement, section 1.2). |

### 3.2 Kirkland Signature against store brands and others of the same type

| Item | Costco unit price | Cheapest comparable captured elsewhere | Difference | Verdict |
|---|---|---|---|---|
| Free-run large eggs | SD Kirkland Free Run 24: $0.425/egg | Walmart GoldEgg Free Run 30: $0.499 · Voilà Compliments Free Run: $0.583 · RCSS PC Free Run: $0.596 | **−14.9% to −28.7%** | Costco cheaper among free-run eggs |
| Large eggs, any type | SD Kirkland Free Run: $0.425 | No Name / Great Value / Burnbrae (GT) large 12: $0.328 | **+29.8%** | Not cheaper. No conventional Costco pack was available on Same-Day at L5V 2N6. |
| Butter 454 g | Costco online Kirkland **Organic** salted: $1.980/100 g; SD Natrel (conventional): $1.447 | RCSS No Name: $1.319 · Walmart Great Value: $1.313 · Giant Tiger Giant Value: $1.073 | SD Natrel **+9.7%** vs No Name; Kirkland organic **+50.1%** vs No Name (organic vs conventional, not like-for-like) | Not cheaper |
| 2% milk, 4 L | SD "2% Milk": $1.728/L | Neilson (RCSS, NF), Sealtest (Walmart), Reid's (GT): $1.610/L | **+7.3%** | Not cheaper |
| Organic 2% milk, 4 L | SD Kirkland Organic: $2.920/L | Walmart Natrel Organic $2.740 · RCSS PC Organics $2.873 | **+6.6% · +1.7%** | Not cheaper |
| Ground coffee, 100% Colombian | Costco online Kirkland Dark Colombian: $2.573/100 g; SD $2.419 | GT Marché Colombian $2.932 · RCSS PC Colombian $3.526 · Voilà Compliments Colombian $3.663 | **−12.3% to −29.8%** online; SD −31.4% vs PC | Costco cheaper |
| Ground coffee, any large canister | Costco online Kirkland: $2.573 | NF No Name 907 g: $1.654 · GT Maxwell House 864 g: $2.080 · Walmart Maxwell House: $2.196 | **+55.6%** vs No Name; +17.2% vs Maxwell House (Walmart) | Not cheaper (different products) |
| Extra-virgin olive oil | Costco online Kirkland 100% Spanish 3 L: $1.233/100 mL; SD Kirkland EVOO 3 L: $1.135 | RCSS No Name 3 L SPECIAL: $1.000 · Walmart Great Value 1 L: $1.097 · Voilà Compliments 2 L: $1.450 | **+23.3%** vs No Name (special); +12.4% vs Great Value; **−14.9%** vs Compliments | Mixed |
| Oats | Costco online Kirkland rolled 4.54 kg: $0.264/100 g; SD $0.250 | Walmart Great Value Quick 1 kg: $0.277 · GT Giant Value Large Flake: $0.277 · RCSS No Name Large Flake 2.25 kg: $0.244 (special) / $0.267 (regular) | **−4.7%** vs Great Value; −1.0% vs No Name regular; +2.2% (SD) vs No Name special | Roughly level |
| Peanut butter, 2 kg | SD Kraft $9.07 promo: $0.454/100 g | No Name Smooth 2 kg (RCSS, NF): $0.450 | +0.8% | Level. Kirkland Natural PB 2 x 1 kg ($0.750) is a different product type. |
| Canned light tuna in water | Costco online Kirkland **Solid** Light 8 x 184 g: $1.358/100 g | RCSS No Name **Chunk** Light: $0.818 · Walmart Clover Leaf Chunk Light: $0.729 ("was $1.88") · RCSS Clover Leaf Chunk Light: $1.176 | **+15.4% to +86.2%** | Not cheaper. Solid vs chunk is not identical; no solid-light-in-water comparator was captured. |
| Toilet paper | Costco online Kirkland 30 x 380: $0.289/100 sheets; SD $0.239 | RCSS Royale Everyday Comfort 30 x 242: $0.234 (special) · NF same: $0.262 (regular) · Walmart Great Value ECO: $0.273 · Voilà Compliments: $0.293 | Online **+10.6%** vs Royale NF regular; **SD −8.7%** vs Royale NF regular; online −1.1% vs Compliments | Mixed. Sheet size and ply are not standardised. |
| Paper towels | Costco online Kirkland 12 x 160: $1.822/100 sheets | Voilà Compliments Ultra 12 x 144: $1.388 | **+31.3%** | Not cheaper per sheet as labelled. Sheet sizes are not stated. |
| Bananas | SD 1.36 kg $1.92: $1.412/kg | RCSS / NF $1.52 · Walmart $1.50 · GT 3 lb $1.50 · Voilà $2.18 | **−7.1%** vs RCSS/NF | Slightly cheaper |
| Chicken breast, boneless skinless | SD Kirkland: $17.58/kg (as shown) | NF club pack SPECIAL to Oct 7: $10.76 · Walmart Maple Leaf 6-7 pc: $12.70 · Voilà Compliments value pack: $17.13 · RCSS club pack: $18.28 · RCSS No Name 2 kg: $21.50 | **+63.4%** vs NF special; +38.4% vs Walmart; −3.8% vs RCSS club; −18.2% vs No Name 2 kg | Mixed; not the cheapest |
| Jasmine rice, 8 kg | Costco online Kirkland Thai Hom Mali: $3.874/kg; SD $3.333 | Walmart Delicious Kitchen: $1.860 · RCSS Jasmine Gold / NF Royal Umbrella / GT Pacific Star: about $2.50 · Voilà Rose: $3.374 | **+55%** online vs $2.50 brands; **+33%** SD; +108% vs Walmart | Not cheaper. Different brands; Kirkland is labelled "Thai Hom Mali". |
| Cheddar block | Costco online Kirkland Marble 1.15 kg: $13.03/kg; SD marble promo $11.83 (regular $15.31); SD Kirkland Old $15.78 | RCSS No Name Old 700 g: $12.56 · Walmart Great Value Old 400 g: $13.70 · NF No Name Old 700 g: $14.29 | Online +3.8% vs RCSS No Name; −4.9% vs Great Value; −8.8% vs NF | Roughly level |

### 3.3 Reading the basket honestly

- On **this** basket, from **these** channels, Costco's prices were lower mainly on:
  - bulk national brands bought in larger packs (olive oil, Quaker oats, Tide, Bounty, Cashmere);
  - premium-tier items (free-run eggs, single-origin Colombian coffee).
- They were higher or level against the discount grocers' store brands on everyday fresh and pantry basics: milk, conventional eggs, butter, tuna, rice and chicken.
- Several of Costco's wins depend on **time-limited Costco promotions** (oats, Kraft PB, Bounty, Cashmere). Several comparisons were against **competitor specials** (No Frills chicken, No Name EVOO, Royale TP).
- **No conclusion about warehouse shelf prices can be drawn.** Costco says online prices include shipping and that Same-Day prices are "marked up higher than your local warehouse". The direction of any warehouse difference is Costco's statement only; the size was not measured.

---

## 4. (B) MEMBERSHIP MATH (Canada)

### 4.1 Fees and cap, verbatim, costco.ca (re-opened 1 Oct 2026, 23:16-23:17 UTC)

Cross-checked against `costco_membership_terms.md` (same date); the two agree.

| Fact | Verbatim | URL |
|---|---|---|
| Gold Star fee | "Gold Star Membership fee is $65 (plus applicable taxes) per 12-month period from the date of enrollment of the Primary cardholder." | https://www.costco.ca/membership-conditions-regulations.html (page dated "August 1, 2026") |
| Executive fee | "Executive Membership is $130 (plus applicable taxes) per 12-month period from the date of enrollment of the Primary cardholder." | same |
| Upgrade | "The Executive Membership upgrade fee is an additional $65 a year for Business or Gold Star Members (plus sales tax where applicable)." | https://www.costco.ca/join-costco.html |
| Rate | "approximately 2% of pre-tax purchases of most merchandise including Costco Travel" | https://www.costco.ca/membership-conditions-regulations.html |
| Cap | "Calculation of a Reward is capped at, and will not exceed, $1,250 for any 12-month period." | same |
| No guarantee | "The Reward is not guaranteed to be equal to or greater than the Executive upgrade fee paid." | https://www.costco.ca/join-costco.html |
| Exclusions (partial) | "Rewards will not be calculated: (i) on purchases of cigarettes or other tobacco-related products; (ii) on purchases that are not recorded through Costco Wholesale's front-end registers, such as services, purchases at Costco Wholesale's gas stations, food courts, optical centres ..." | https://www.costco.ca/membership-conditions-regulations.html |
| Redemption | "Reward coupons may be redeemed by the Primary member toward purchases of most merchandise through the front-end registers at Costco Wholesale warehouses throughout Canada only." | same |
| Executive Instacart credit | "one (1) $10 CAD instant credit in your Instacart account to use at either Costco on Instacart's marketplace or SameDay.Costco.ca ... each month you have a valid Costco Executive membership that is linked to your Instacart account starting 6/30/2025. Each monthly credit is only eligible on one (1) purchase of $150 CAD or more of eligible products ..." | https://www.costco.ca/join-costco.html |

Earlier fee history (2017 to $60/$120, cap $1,000; September 2024 to $65/$130, cap $1,250) is documented with SEC sources in `costco_membership_terms.md`, section A2. Costco's 8-K language describes "U.S. and Canada" fees together; the Canadian page shows the same figures in CAD.

### 4.2 Computations (mine, not Costco's)

| Quantity | Formula | Result |
|---|---|---|
| Annual qualifying spend at which the 2% Reward equals the upgrade fee | $65 ÷ 0.02 | **$3,250 a year** |
| Per month / per week | $3,250 ÷ 12 ; ÷ 52 | **$270.83 / $62.50** |
| Same, if sales tax is paid on the fee (illustrative 13% rate) | ($65 × 1.13) ÷ 0.02 | $3,672.50 |
| Same, illustrative 5% rate | ($65 × 1.05) ÷ 0.02 | $3,412.50 |
| Annual qualifying spend at which the $1,250 cap binds | $1,250 ÷ 0.02 | **$62,500 a year** |
| Net gain at the cap | $1,250 − $65 | $1,185 (before any tax on the fee) |
| Executive's Instacart credit, if used every month | 12 × $10, each month requiring one Same-Day/Instacart order of $150+ | Up to $120 a year. This is conditional, and Same-Day prices are marked up (Costco's statement). |

**What does not count toward the $3,250.** The Reward is "approximately" 2%, of "pre-tax" purchases. Costco's list excludes:
- gas;
- tobacco;
- food court;
- services;
- in Quebec and Nova Scotia, liquid milk;
- other items listed in `costco_membership_terms.md`, section A3.

So the true spend needed is at least $3,250 of *qualifying* pre-tax merchandise.

**Gold Star fee recovery.** There is no published formula. The basket above suggests where per-unit savings exist. Two illustrations from section 2 (online prices, not warehouse):
- One 3 L Terra Delyssa at costco.ca ($31.99) versus three 1 L bottles at Walmart ($50.31) saves $18.32.
- One Quaker 5.16 kg at Costco's promotional price ($10.99) versus RCSS ($14.99) saves $4.00.

How many such purchases a household makes is not documented here.

---

## 5. (C) CONTEXT: STATISTICS CANADA

### 5.1 Household spending on food from stores (Survey of Household Spending)

Table **11-10-0125-01**, "Detailed food spending, Canada, regions and provinces". Average expenditure per household. Read through the StatCan WDS API (`getDataFromCubePidCoordAndLatestNPeriods`) on 1 Oct 2026. Cube end date 2023-01-01. The 2023 values carry release time 2026-09-18T08:30.

Source pages: https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1110012501 (WDS: https://www150.statcan.gc.ca/t1/wds/rest/getDataFromCubePidCoordAndLatestNPeriods)

| Geography | Category | 2021 | **2023 (latest)** | Vector |
|---|---|---|---|---|
| Canada | Food expenditures (stores + restaurants) | $10,305 | **$11,933** | v54531258 |
| Canada | **Food purchased from stores** | $8,065 | **$8,579** | v54531259 |
| Ontario | Food expenditures | $9,822 | $11,716 | v64484271 |
| Ontario | **Food purchased from stores** | $7,840 | **$7,974** | v64484272 |

### 5.2 Food CPI, August 2024 to August 2026

Table **18-10-0004-01**, CPI, monthly, not seasonally adjusted (2002 = 100). Read through the WDS on 1 Oct 2026. The August 2026 values were released 2026-09-14.

| Series | Aug 2024 | Aug 2025 | Aug 2026 | Change Aug 2024 → Aug 2026 | Change Aug 2025 → Aug 2026 |
|---|---|---|---|---|---|
| All-items, Canada (v41690973) | 161.8 | 164.8 | 169.8 | **+4.9%** | +3.0% |
| Food, Canada (v41690974) | 190.3 | 196.8 | 202.4 | **+6.4%** | +2.8% |
| **Food purchased from stores, Canada** (v41690975) | 187.7 | 194.2 | 199.6 | **+6.3%** | +2.8% |
| Food purchased from stores, Ontario (v41691921) | 190.8 | 196.9 | 202.3 | **+6.0%** | +2.7% |

### 5.3 The break-even as a share of an average grocery bill (computed)

| Basis | Food-from-stores spend | $3,250 as a share | 2% of that spend |
|---|---|---|---|
| Canada, 2023 SHS (published) | $8,579 | **37.9%** | $171.58 |
| Canada, 2023 scaled to Aug 2026 prices (× 199.6 ÷ 182.78, the 2023 average of v41690975) | about $9,368 (illustrative) | **about 34.7%** | about $187 |
| Ontario, 2023 SHS (published) | $7,974 | **40.8%** | $159.48 |
| Ontario, scaled (× 202.3 ÷ 186.33) | about $8,657 (illustrative) | **about 37.5%** | about $173 |

**Read-across, as arithmetic not advice.** A household needs about **a third of an average household's annual store-bought food spending** to pass through Costco registers as qualifying purchases before the Executive upgrade pays for itself.

- If an average household bought **all** its store food at Costco, the 2% would come to about $172 to $187. That exceeds the $65 upgrade fee.
- The SHS "food purchased from stores" category is food only. Costco's 2% also accrues on most non-food merchandise, so non-food spending also counts toward the $3,250.
- The scaling uses CPI as a price index only. It assumes quantities did not change; this is an assumption, not data.

---

## 6. (D) GAS

### 6.1 Does costco.ca publish warehouse gas prices? Yes, through its warehouse pages.

- The costco.ca warehouse page for Etobicoke (https://www.costco.ca/w/-/on/etobicoke/524, opened 23:14 UTC) carries the configuration `"enableGasPriceDisplay":true`. It also names a service, "Warehouse service to get gas prices for a list of warehouses", with endpoint `/AjaxGetGasPricesService`.
- Calling https://www.costco.ca/AjaxGetGasPricesService?warehouseid=524 at 2026-10-01 23:15 UTC returned: `{"524":{"premium":"1.899","regular":"1.669"}}`.
- Disclaimer on the page, verbatim: "Prices shown here are updated frequently, but may not reflect the price at the pump at the time of purchase. All sales will be made at the price posted on the pumps at each Costco location at the time of purchase."

### 6.2 Snapshot, 1 Oct 2026, 23:15 UTC

Source: https://www.costco.ca/AjaxWarehouseBrowseLookupView?numOfWarehouses=20&hasGas=true&populateWarehouseDetails=true&latitude=43.6071&longitude=-79.6904&countryCode=CA (costco.ca's warehouse-locator service). The values are dollars per litre.

| Warehouse (costco.ca ID, name) | Regular | Premium |
|---|---|---|
| 526 N Mississauga (5900 Rodeo Dr) | $1.629 | $1.879 |
| 1169 C Mississauga | $1.649 | $1.899 |
| 524 Etobicoke | $1.669 | $1.899 |
| 1655 NW Toronto (Etobicoke) | $1.669 | $1.899 |
| 537 Scarborough | $1.619 | $1.869 |
| 159 Ajax | $1.599 | $1.849 |

### 6.3 Statistics Canada average retail gasoline price, Toronto

Table **18-10-0001-01**, "Monthly average retail prices for gasoline and fuel oil, by geography". Cents per litre. Read through the WDS on 1 Oct 2026. The latest month is August 2026.

| Month 2026 | Toronto, regular, self-serve (v735098) | Toronto, premium, self-serve (v735116) | Canada, regular, self-serve (v1352087861) |
|---|---|---|---|
| March | 161.4 | 192.3 | 164.2 |
| April | 176.6 | 207.4 | 178.8 |
| May | 186.9 | 217.8 | 188.7 |
| June | 165.4 | 196.3 | 169.4 |
| July | 172.7 | 203.7 | 175.5 |
| **August** | **170.3** | **201.5** | **173.8** |

**Comparison status: NOT like-for-like.**
- Costco's figures are a single moment (1 Oct 2026), not an average.
- StatCan's latest figure is the August 2026 monthly average. September and October 2026 were not published as of 1 Oct 2026.
- **Do not present a Costco-versus-average saving from these numbers.** A valid comparison needs Costco prices captured across the same month as a published StatCan month. For example, capture daily through October 2026 and compare with StatCan's October figure when it is released, expected in mid-November 2026.

### 6.4 Membership and gas, verbatim

- https://www.costco.ca/f/-/gasoline-q-and-a (re-opened 23:16 UTC): "The gas station is open to Costco members only, with one exception: Costco Shop Card holders do not need to be members."
- The 2% Reward is not calculated on "purchases at Costco Wholesale's gas stations" (https://www.costco.ca/membership-conditions-regulations.html).
- The CIBC Costco Mastercard's "3% cash back ... at Costco gas" is documented in `costco_membership_terms.md`, A8. That figure comes from CIBC's and Costco's pages, opened 1 Oct 2026 by that file's compiler, and was not re-opened for this file.

---

## 7. (E) ALTERNATIVES, AT THEIR OWN PUBLISHED PRICES (opened 1 Oct 2026)

| Program | Fee, verbatim | Grocery-relevant perk, verbatim | URL / time (UTC) |
|---|---|---|---|
| **PC Optimum Insiders** (Loblaw) | "The 12-month subscription plan costs $119 (plus tax)" (terms; CMS record updated 2026-04-27) | "Earn 10% back in PC Optimum™ points on all PC® products!" · "You'll also pay no service fee for PC Express pickup orders made at Loblaw banner PC Express websites with a $30 minimum purchase (where applicable) before applicable taxes and fees are applied. Loblaw banner stores exclude Real Canadian Wholesale Club. T&T Supermarket is also excluded." | https://www.pcoptimum.ca/insiders (data at https://www.pcoptimum.ca/insiders/page-data/index/page-data.json and .../page-data/en/terms-and-conditions/page-data.json), 23:15-23:16 |
| PC Insiders refund, verbatim | "If you cancel your subscription and have paid an Annual Subscription Fee, you will receive a prorated refund based on the amount of time remaining in the 12-month period following the payment of your Annual Subscription Fee." | | same terms page |
| **Amazon Prime (Canada)** | "Prime Monthly $9.99 per month after trial Prime Annual $99 per year after trial" and "Only $9.99/month (plus tax) after trial." | (not grocery-specific) | https://www.amazon.ca/prime (redirected to https://www.amazon.ca/amazonprime), 23:15 |
| **Walmart+ (Canada)**: available | "Join Walmart+ now for only $89 annually or $8.97 monthly. (Plus applicable taxes)." FAQ: "Monthly: $8.97 plus applicable taxes, billed every 30 days · Annual: $89 plus applicable taxes, billed every 365 days" | "No fees on standard delivery over $35 & get the same low prices as in store. Exclusions apply." · "¹$35 order minimum. Restrictions apply." · "An order must be placed by 4 pm to receive same-day delivery." | https://www.walmart.ca/en/plus (mobile user-agent), 23:15 |
| **Instacart+ (Canada)** | "For a flat standard fee of $99/year or $9.99/month, members enjoy exclusive benefits ($0 delivery fee on orders of $10+ and Costco orders of $35+. Service fees apply)" · "Trial auto-renews to a $99/year paid subscription." | Instacart operates Costco Same-Day, whose prices Costco says are marked up (section 1.2). | https://www.instacart.ca/instacart-plus, 23:15 |
| Costco Gold Star / Executive (for reference) | $65 / $130, plus applicable taxes | Section 4 | costco.ca |

**Fee comparison, computed:**
- Walmart+ annual ($89) is $24 more than Gold Star ($65) and $41 less than Executive ($130).
- PC Optimum Insiders ($119) is $11 less than Executive.
- Prime ($99) and Instacart+ ($99) are $34 more than Gold Star.

These are fee comparisons only. The programs' benefits are not equivalent.

---

## 8. LEGAL ITEM (labelled)

| Item | Status | What is documented | Source (opened 1 Oct 2026, 23:19 UTC) |
|---|---|---|---|
| Proposed class action against Costco Wholesale Canada Ltd., Federal Court, filed by Perrier Attorneys (Montreal), concerning online versus in-warehouse prices | **ALLEGATION.** A proposed class action. Global News reports: "The proposed class action against Costco Canada still has to be approved by the court." **No finding, no settlement, no admission.** | Global News reports the claim alleges "double ticketing". The proposed class is "anyone in Canada who, since Dec. 23, 2022, has purchased an item from Costco's app or its website and paid more than the price displayed for that same item in Costco warehouses." Global News "reached out to Costco for comment on the allegations ... but did not receive a response before publication." It quotes Costco's website: "products sold online may have different pricing than the same products sold at your local Costco warehouse." | Global News, Saba Aziz, posted 14 Jan 2025: https://globalnews.ca/news/10957804/costco-canada-class-action-lawsuit/ |

The court file was not opened (see UNVERIFIED). No Competition Bureau, Quebec OPC, FCAC or CRA decision on these topics was found or used.

---

## APPENDIX: RECALLS (food-safety items), DO NOT USE ON AIR

No recall material was collected for this file. costco.ca's footer links to "Recalls and Product Notices"; that page was not opened. Under house rules, nothing from recalls appears in the body.

---

## SOURCE LOG (all opened 1 Oct 2026; UTC)

| # | Source | URL (as opened) | Method | Result |
|---|---|---|---|---|
| 1 | costco.ca search API (15 staples + brand searches) | https://search.costco.ca/api/apps/www_costco_ca/query/www_costco_ca_search?q={term}&locale=en-CA&rows=48&start=0 | curl, header `x-api-key` taken from costco.ca's own page config | 200, 22:55-22:56 and 23:09-23:10 |
| 2 | costco.ca product pages (22) | https://www.costco.ca/p/-/x/{4000111232, 100572733, 100363149, 4000339232, 4000363006, 4000254430, 100388606, 4000339745, 100570610, 100417656, 100550319, 100417042, 4000107096, 100411882, 100559615, 100558748, 100552507, 100417088, 100799194, 100416825, 100416749, 4000041720} | curl | 200, 23:10-23:11. 100416825 (Kirkland Organic EVOO 2 L) showed onlinePrice 0 and was not used. |
| 3 | Costco Same-Day product pages (31 attempts) | URLs in the tables, each with `?zipcode=L5V2N6&utm_source=nav` | curl | 22:59-23:02 and 23:17. Burnbrae 30-ct, ECSL XL 30-ct, a 60-ct pack and Fraser Valley butter did not return a priced item for L5V 2N6. Tuna and a 12-ct egg pack fell back to location 121687 and were not used for L5V 2N6. |
| 4 | Loblaw PC Express API: RCSS #1080 and NF #3907, 17 terms each | POST https://api.pcexpress.ca/pcx-bff/api/v1/products/search | curl | 200, 23:02-23:03 |
| 5 | walmart.ca search (mobile user-agent) | https://www.walmart.ca/en/search?q={term} | curl | 200 for 17 terms (23:04-23:05, 23:12-23:13). 7 terms returned `/blocked` at 23:05 and were retried at 23:12. |
| 6 | Voilà search | https://voila.ca/products/search?q={term} (redirects to /search?q=) | curl | 200 for 17 terms (23:06-23:08). One 202 (rate limit) retried. |
| 7 | Giant Tiger suggest | https://www.gianttiger.com/search/suggest.json?q={term}&resources[type]=product&resources[limit]=10 | curl | 200, 23:08-23:09 |
| 8 | costco.ca membership pages | https://www.costco.ca/join-costco.html ; https://www.costco.ca/membership-conditions-regulations.html ; https://www.costco.ca/f/-/gasoline-q-and-a ; https://www.costco.ca/f/-/sameday-grocery-help | curl | 200, 23:16-23:19 |
| 9 | costco.ca gas | https://www.costco.ca/w/-/on/etobicoke/524 ; https://www.costco.ca/AjaxGetGasPricesService?warehouseid=524 ; https://www.costco.ca/AjaxWarehouseBrowseLookupView?... | curl | 200, 23:14-23:15 |
| 10 | Statistics Canada WDS | getCubeMetadata and getDataFromCubePidCoordAndLatestNPeriods for 11100125, 18100004 and 18100001; getDataFromVectorByReferencePeriodRange for v41690975 and v41691921 | curl | SUCCESS |
| 11 | PC Optimum Insiders | https://www.pcoptimum.ca/insiders and its page-data JSON (index, en/terms-and-conditions, en/how-it-works) | curl | 200 |
| 12 | Amazon.ca Prime | https://www.amazon.ca/prime → /amazonprime | curl | 200 |
| 13 | Walmart+ Canada | https://www.walmart.ca/en/plus | curl, mobile user-agent | 200 |
| 14 | Instacart+ Canada | https://www.instacart.ca/instacart-plus | curl | 200 |
| 15 | Global News | https://globalnews.ca/news/10957804/costco-canada-class-action-lawsuit/ | curl | 200 |
| 16 | Cross-check file | `costco_membership_terms.md` (same scratchpad, compiled 1 Oct 2026) | read | Fees and cap agree |
| — | Search-engine results | WebSearch, restricted to sameday.costco.ca | Used **only to find Same-Day product URLs**. No price was taken from a search snippet. | |

Raw captures are saved under `scratchpad/cv/`:
- `cs_*.json`, `cp/`, `sd/`, `sd_results*.json`
- `lb/`, `lb_show.txt`
- `wm/`, `vo/`, `vo_all.txt`, `gt/`
- `alt/`, `wh524.html`, `whloc.json`
- `tables.md` and `build_tables.py` (the unit-price arithmetic)

---

## UNVERIFIED / DO-NOT-USE

1. **Costco warehouse shelf prices.** Not captured. Costco publishes no warehouse price list online. Every Costco price here is costco.ca online (shipping included) or Same-Day (marked up, per Costco). Do not say "Costco warehouse price is X", and do not quantify a warehouse-versus-online gap.
2. **Costco.ca online availability on 1 Oct 2026.** Page schema showed "OutOfStock" without a delivery location, while the search API said "in stock". Unresolved.
3. **Voilà region.** No address was set and the region shows as "Default Region 1". The catalogue appears to mix provinces, so prices may not be GTA prices. Treat Voilà rows as indicative only.
4. **Giant Tiger.** Online prices from Shopify listings tagged ON. Many carry `in_store_only:true`. Giant Tiger's product pages have stated "Online prices may vary from in-store prices" (seen in an earlier capture, not re-opened today). Store-level prices are not established.
5. **walmart.ca store 2000 rows** (Bounty, Tide, Great Value ECO TP). These are Walmart's online/ship-to-home listings, not store 1061 shelf prices.
6. **Same-Day "2% Milk 4 L".** The brand is inferred from the URL slug "beatrice"; the page name shows only "2% Milk".
7. **Same-Day Kirkland paper towels ($29.50, 12 ct) and Cashmere 40 ct ($24.39, "reg. $29.89").** Sheet counts were not shown on the Same-Day pages, so no per-sheet price was computed. The 380-sheet figure for Same-Day Kirkland TP comes from the Same-Day URL slug; costco.ca states "380 sheets per roll".
8. **Paper-goods per-sheet comparisons.** Sheet dimensions and ply differ, and "double/triple/equal" roll claims are manufacturers' labels. Per-sheet figures are approximate.
9. **Tide loads.** Load counts are P&G's labels on different jug sizes and formulations. Some Loblaw and Voilà listings did not state loads and were not used per load.
10. **Loblaw API prices.** These are PC Express online prices for the named store. Whether they equal the shelf price in store on 1 Oct 2026 was not verified. "memberOnlyPrice" values (PC Optimum member prices, e.g. PC Marble Cheddar 400 g $4.88) were not used.
11. **NF chicken "regular" per-kg price.** Only the special ($10.76/kg) and an estimated package "was" price ($18.89) were shown. Any regular per-kg figure (about $15.41) would be my inference and is not used.
12. **Same-Day Kirkland chicken.** "$39.38 /pkg (est.)" is Instacart's estimate for a variable-weight package. Only $17.58/kg is used.
13. **Same-Day page LD-JSON** marks `"priceCurrency":"USD"` although the storefront is Canadian and displays "$". The prices are assumed to be CAD, as displayed.
14. **Kirkland Organic EVOO 2 L ($21.99)** appeared in the search API only; the product page showed 0. Not used.
15. **Sales tax on membership fees.** The 13% and 5% rates in 4.2 are illustrative rates, not sourced statements of any province's rate. Check CRA / provincial sources before stating a province's tax.
16. **CPI scaling of the 2023 SHS figure.** This is my computation, not Statistics Canada's. It assumes constant quantities.
17. **Gas comparison.** The Costco snapshot (1 Oct) and the StatCan monthly average (August) are not the same period. Do not use them as a saving.
18. **CIBC 3% at Costco gas, and the full 2% Reward exclusions list.** Taken from `costco_membership_terms.md`; not re-opened for this file.
19. **The class action's current status, court file number and docket.** Not opened. ALLEGATION only. The price examples in that claim were not used.
20. **Same-Day pricing-policy page** (https://sameday.costco.ca/store/costco-canada/pages/pricing-policy). Re-opened at 23:19 UTC, but its text did not render server-side. The quote "Item prices are marked up higher than your local Costco warehouse ..." comes from `costco_membership_terms.md`. The costco.ca help page quote in 1.2 was verified today.
21. **Walmart's "Save with W+" badge on search items** was observed in page data. What it implies for individual item prices was not checked.
22. **PC Optimum Insiders' other perks** (free shipping on joefresh.com and shoppersdrugmart.ca, PC Express Pass offers) were seen in page data but not verified line by line. Only the fee, refund and the quoted lines in section 7 are used.
23. **Search-engine snippets** (WebSearch on sameday.costco.ca) showed some prices that differed from the pages, e.g. bananas $2.26 and 2% milk $8.58. Those snippets are **not** sources and were not used.
24. **Tier (c) items.** None were used. No Flipp, coupon blogs, Reddit, YouTube or aggregators.
