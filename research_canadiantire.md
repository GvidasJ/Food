# Research — Canadian Tire (October 6, 2026)

Four research files from the October 4, 2026 research run, joined in full. Tiers: (a) primary, (b) named outlet, (c) do-not-use, (d) named survey.

---

# DOSSIER (retention): blueprint for "Why Some Canadians Are Refusing to Shop At Canadian Tire Anymore"

For: Canadian Counter (38.5K subs). The video airs **Oct 6, 2026**. It is a faceless narration of about 22 minutes, built as 9→1, then three positives, then a four-step protect section.
Compiled: **Oct 4, 2026**. Every source below was opened on Oct 4, 2026.
Raw captures (all in `scratchpad/`):
- Transcripts: `ct_tr_*.txt` (10 files). The raw JSON is `ct/raw_transcripts_batch1.json`.
- Metadata: `ct/ret_video_meta_20261004.json`, `ct/ret_bc_channel_videos_20261004.json` and `ct/ret_cc_channel_videos_20261004.json`.
- Measurements: `ct/measure.py`, `ct/numdens.py` and `ct/metrics.json`.
- Draft lines: `ct/ret_examples.txt`.
- **Pre-flight checker for the finished script: `ct/ret_check.py`** (see §6).

**How to read this file**
- **What this dossier is.** It is about *structure*. It is not a source of facts. The YouTube transcripts and view counts in it are **structural data only**. For any factual claim they are **tier (c), do not use** (house rule 8). Nothing a competitor's narrator says may be repeated on air.
- **Where the facts in the example lines come from.** Every Canadian Tire fact in the example lines is taken from the sibling dossier `scratchpad/ct_record.md` (its source IDs are given as [S#]). I did **not** re-open those sources. The writer must check each line against ct_record before use (see U7).
- **OUR NOTE** marks our own arithmetic or judgement.
- **No retention data exists for any of these videos** (see U1). "Hit" and "flop" mean views. Every link to retention is an inference from structure.

---

## 0. VERDICT FOR THE WRITER (the 12 things that matter most)

1. **Get to "Number nine" by about 1:00–1:15 (about 950–1,100 characters).** Canadian Counter's own hit (Costco, 236K) got there in about 73 s. The No Frills script gets there at about **3:20** (char 3,156). The extra time is a 298-word honesty bridge carrying 8 spoken figures.
2. **Sentence 1 should be about the viewer, with a concrete number. Sentence 2 opens a specific loop. Sentence 3 is the hardest labelled fact.** Every hit puts a number, a named thing or a "you" scene in its first 2 sentences. The No Frills script's sentence 1 has Loblaw as its subject and "posted an update to a notice" as its action.
3. **Name the loop exactly, and pay it at #1.** Costco's "the one we're saving for the end… could pay for your entire membership" (2.8%) was paid at 83%. Neither flop planted a specific loop. For Canadian Tire, the loop is: **"three of those five percentage points depend on one thing in your wallet."** It is planted in the first 15 s, re-teased at the ask and paid at #1.
4. **Order the list.** Second-strongest item at #9: the **Quebec guilty plea over regular prices** (label: guilty plea). Strongest at #1: **the Canadian Tire Money / Triangle card rule**. High-interest **auto service** goes at #2, right after the ask, to carry viewers across it.
5. **Never open the list with an item the viewer can't act on.** Our May Canadian Tire flop (5.4K) opened issue #1 with a human-rights complaint settlement and stayed on it for about 2 minutes. That is the clearest single difference from the hits.
6. **Don't open with a methods disclaimer.** The Giant Tiger flop (1.6K) told viewers at 0:35: "We haven't conducted a nationwide price survey… The examples will [be] illustrations, not receipts." Labels and caveats go **inside** items, attached to each fact.
7. **Keep the honesty bridge to 70 words or fewer, after #9.** One line of the "some" justification also goes in the hook (CTR comparable sales down in both 2026 quarters, per CTC). That keeps the title honest inside 90 s.
8. **Hold spoken figures to about 3 per 100 words or fewer.** The No Frills script is at **4.79**. Every comparison video is between 0.63 and 2.32. Put secondary figures in lower-thirds, not in the narration.
9. **Raise "you" to 2.5 or more per 100 words.** The No Frills script is at **1.55**. The hits are at 2.0–3.4 (Costco 3.38, Tesco 3.32). Give each item a one-line "you" scene.
10. **Keep sentences short and varied.** Aim for a mean of 12–16 words, 20% or more under 8 words, and 12% or fewer over 25. The May Canadian Tire flop averaged **25.1** words per sentence, with 42% over 25 words.
11. **Keep items even, at about 1,600–1,800 characters (≤ ~300 words).** #1 may run to about 2,200. Tesco's nine items ran 1,998–3,035 characters with no outlier. No Frills' #1 is 458 words (2,804 characters).
12. **Expect a lower ceiling for the topic.** Canadian Tire is a weaker topic than Tim Hortons or Costco, both for us and for Broken Canada:
    - Broken Canada: Canadian Tire 38K and 75K, against Princess Auto 529K and Tim Hortons 181K and 179K.
    - Us: Canadian Tire 5.4K, against Costco 236K.
    Retention work can lift average view duration and % viewed. It cannot fix packaging.

---

## 1. SOURCE REGISTER

All rows were opened on Oct 4, 2026. Views are a snapshot from the YouTube Data API v3 (via Algrow). **Tier** applies to factual use: these are all (c) for facts, and are used here **only** as structural samples.

| ID | Video | Channel | Published (UTC) | Views at Oct 4 | Length | URL | Tier | Transcript file |
|---|---|---|---|---|---|---|---|---|
| V1 | "Why Brits Are Refusing to Shop At Tesco Anymore" | Protect Our Plates | 2026-10-02 05:52 | 105,398 | 29:49 | https://www.youtube.com/watch?v=IftsR3XILB8 | c (structure only) | ct_tr_tesco.txt |
| V2 | "Millions of Canadians Are Now Boycotting Tim Hortons" | Broken Canada | 2026-09-30 | 181,408 | 26:31 | https://www.youtube.com/watch?v=jtkLilco7Kk | c | ct_tr_bc_tims_boycott.txt |
| V3 | "Canadians Are Turning Away From TIM HORTONS—and Retailers Are Taking Notice." | Broken Canada | 2026-09-28 | 116,318 | 27:38 | https://www.youtube.com/watch?v=yTqWxHLto00 | c | ct_tr_bc_tims_turning.txt |
| V4 | "Princess Auto Just Did What No Hardware Store Would" | Broken Canada | 2026-08-28 | 528,576 | 27:35 | https://www.youtube.com/watch?v=pSKibWHQxNU | c | ct_tr_bc_princessauto.txt |
| V5 | "Canadian Tire and 9 Other Auto Repair Chains Just Got Caught — Something Felt Wrong" | Broken Canada | 2026-09-27 | 75,037 | 27:16 | https://www.youtube.com/watch?v=r5DkjCpiSWo | c | ct_tr_bc_ct_autorepair.txt |
| V6 | "Canadian Tire Just Did What No Other Store Would" (extra comparison) | Broken Canada | 2026-08-17 | 38,236 | 27:37 | https://www.youtube.com/watch?v=-CUyGbsymag | c | ct_tr_bc_ct_didwhat.txt |
| V7 | "Don't Buy These 11 CANADIAN Yogurt Brands (Here's Why)" | Canadian Counter | 2026-06-02 18:00 | 286,512 | 27:50 | https://www.youtube.com/watch?v=eXWMTpIUHOY | c (our own; structure only) | ct_tr_cc_yogurt.txt |
| V8 | "Don't Renew Your Costco CANADIAN Membership Until You Watch This" | Canadian Counter | 2026-05-13 18:00 | 236,232 | 22:51 | https://www.youtube.com/watch?v=hlJg9VFW5hQ | c | ct_tr_cc_costco.txt |
| V9 | "Do Not Shop At Canadian Tire Again Until You Watch This!" (**flop**) | Canadian Counter | 2026-05-29 18:08 | 5,393 | 24:31 | https://www.youtube.com/watch?v=JCrqoERPVDk | c | ct_tr_cc_ct_may_flop.txt |
| V10 | "DON'T SHOP AT GIANT TIGER UNTIL YOU WATCH THIS (SENIOR BEWARE)" (**flop**) | Canadian Counter | 2026-09-25 | 1,561 | 22:31 | https://www.youtube.com/watch?v=pc7CE6DH1Zg | c | ct_tr_cc_gianttiger_flop.txt |
| V11 | `/home/user/Food/script_nofrills.md` (airs Oct 5; not yet published) | ours | n/a | n/a | n/a | local file | n/a | ct/nofrills_spoken.txt (lines 29–67) |
| R1 | Sibling dossier `scratchpad/ct_record.md` (the facts behind every Canadian Tire example line) | ours | compiled Oct 4, 2026 | n/a | n/a | local file | inherits each [S#] tier | n/a |

Notes on the brief's figures:
- **Tesco, "102K in a day".** The page showed 105,398 on Oct 4 for a video published Oct 2, 05:52 UTC, so the figure covers about two days, not one.
- **Broken Canada Tim Hortons, "181K in 4 days".** Matches: 181,408 for a Sep 30 upload.
- **Giant Tiger flop ID.** Found via the channel listing: **pc7CE6DH1Zg** (Sep 25, 2026).
- **May Canadian Tire flop date.** The local `canadian_counter_catalog.json` gives its date as 2026-06-07, which looks like the date of the catalog snapshot. The API says **2026-05-29**, and that is the date used here.

---

## 2. METHOD (and its limits)

- **Transcripts.** These are YouTube caption tracks fetched via Algrow. Punctuation in auto-captions is machine-inserted, so **sentence statistics for V1–V10 are approximate**. V11 is authored text, so its statistics are exact. The markers ">>" and "[music]" were removed before measuring.
- **"First 60 seconds" = the first 160 words.** At these videos' measured paces (145–174 wpm; see §3.2), that is 55–66 s.
- **Character positions** are measured on the whitespace-normalised transcript. "%" means percent of characters.
- **Spoken figures per 100 words.** A run of digits and/or number-words ("three hundred and thirty-six", "$7.99", "2.3%") counts as one figure. A bare "one" or "point" is not counted. The method is regex-based and approximate (`ct/numdens.py`).
- **"You" rate.** Counts you / your / you're / you'll / you've per 100 words.
- **Pace.** Words ÷ the duration from the API. The duration includes music and outro, so the pace is slightly understated.

---

## 3. MEASUREMENTS

### 3.1 Whole-video metrics

| Video | Views | Words | Pace (wpm) | Mean sentence (words) | % sentences <8 words | % >25 words | % >40 words | "you" per 100 words | Spoken figures per 100 words |
|---|---|---|---|---|---|---|---|---|---|
| V1 Tesco (template) | 105K | 5,089 | 171 | 17.5 | 15% | 22% | 3.8% | 3.32 | 0.92 |
| V2 BC Tims boycott | 181K | 4,573 | 173 | 13.9 | 34% | 14% | 2.4% | 2.08 | 1.68 |
| V3 BC Tims turning | 116K | 4,605 | 167 | 14.3 | 34% | 17% | 1.9% | 1.80 | 1.47 |
| V4 BC Princess Auto | 529K | 4,761 | 174 | 13.0 | 38% | 11% | 1.9% | 2.04 | 0.96 |
| V5 BC CT auto repair | 75K | 4,577 | 168 | 13.0 | 34% | 11% | 1.7% | 3.02 | 1.51 |
| V6 BC CT "did what" | 38K | 4,639 | 169 | 13.1 | 39% | 12% | 2.3% | 2.82 | 0.97 |
| V7 CC yogurt (hit) | 287K | 4,667 | 170 | 21.3 | 8% | 31% | 5.9% | 2.04 | 0.63 |
| V8 CC Costco (hit) | 236K | 3,671 | 165 | 15.9 | 21% | 17% | 1.3% | 3.38 | 2.18 |
| **V9 CC Canadian Tire (flop)** | **5.4K** | 3,493 | **145** | **25.1** | **0.7%** | **42%** | **10.1%** | **0.40** | 1.55 |
| **V10 CC Giant Tiger (flop)** | **1.6K** | 3,831 | 170 | 12.6 | 21% | 3% | 0% | 3.84 | 2.32 |
| V11 No Frills script | n/a | 3,882 | n/a | 14.5 | 20% | 9% | 0% | 1.55 | **4.79** |

### 3.2 The first 60 seconds (about 160 words)

Quotes are verbatim from the caption tracks (opened Oct 4, 2026; auto-captions, so spelling is as captioned).

| Video | Sentence 1 does… | Sentence 2 does… | Sentence 3 does… | First concrete payoff | First item/chapter starts | Loops planted in the intro (→ where closed) | Asks |
|---|---|---|---|---|---|---|---|
| **V1 Tesco** | Frame plus hype: "Today we uncover the shocking truth about Tesco UK." | **News peg with a number**: "Over 114 food additives have just been banned or restricted across Tesco's own brand range." | Scale: "the biggest supermarket in the country, holding around a quarter of the entire grocery market." | S2, about char 45 | char 2,813 (9.6%), about **2:52** | (a) "the one setting on Tesco's own website that most shoppers have no idea exists" (2.9%): **no payoff found in the transcript** (see U3). (b) "plus the three things they're genuinely getting right" (8.0%) → paid at 88–97%. | Like + hype at 8.5%; comment at 51.7%; subscribe at 68.6%; comment again at 99.2% |
| **V2 BC Tims boycott** | Identity plus a plea to stay (51 words): "If you are a Canadian who still makes a Tim Horton's run every single morning, I need you to stay with me for the next few minutes…" | Claim with a date ("around 2014") | Motive attribution (not allowed for us) | S2 (2014) | chapter at char 597, about 0:38 ("The brand Canadians built.") | Vague ("That changes today."). The countdown 3→1 of "what to buy instead" comes at 82–88% | Comment question at 48.6% |
| **V3 BC Tims turning** | Rule-of-two setup: "There are two things Canadians were never supposed to question." | "The first is hockey." | "The second is Tim Horton's." | none in the first 160 words except "1964" | chapter at about 0:35 | Implicit ("what was done to cause it") | Comment question at 42.3% |
| **V4 BC Princess Auto** | **Unnamed-subject curiosity gap**: "There is a store in Canada that the big box chains have been hoping you forget about." | Reverses an expectation: "Not because it is struggling…" | Names a rival: "Canadian Tire did the math and walked away." (unsourced; do not use) | **0 figures** in the first 160 words. Payoff is the name reveal (about word 110) | chapter at about 0:38 | Next-video tease at the end | Subscribe at 98.6% only |
| **V5 BC CT auto repair** | Universal scene: "There is a moment that happens to almost every Canadian driver." | "You bring your car in for an oil change." | "$63." (a 1-word number sentence) | S3 | chapter at about 0:31 | "today we are going to show you exactly how" | None found |
| **V7 CC yogurt** | Named stores (a fragment): "The tubs you are tossing into your cart at Loblaws, Sobeys, Metro, No Frills, Walmart…" | "…not always what the front of the package wants you to believe." | Health and sensory claims (**barred now**: rules 1 and 2) | No figure in the first 160 words; named brands at about word 140 | Activia at char 3,035, about **3:08** | "Then I will tell you the ones that are genuinely worth your money" → end | Like at 9.4%, 40.5% and 99.1% |
| **V8 CC Costco** | **Identity plus a number, in 8 words**: "Over 10 million Canadians have a Costco membership." | Personal stake: "The annual fee gets pulled from your credit card every renewal cycle without much thought." | **Prices**: "$65 for Gold Star, $130 for Executive." | S1 and S3 | first item at char 1,182, about **1:13** | **"the one we're saving for the end of this video, could pay for your entire membership"** (2.8%) → re-teased at 82.0% ("Before we get to the biggest secret on this list, quick favor") → paid at 83.7% (gas) | Like + subscribe at 82.4%, **sandwiched by the loop re-tease** |
| **V9 CC Canadian Tire (flop)** | A good "you" scene: "You walk through those red doors every season." | "You browse the seasonal aisles." | "You grab a couple of items you did not plan on buying." | Heritage, not a payoff: "since 1922… combined savings of $1,800" | "The first issue on our list" at 5.1%, about 1:23 | Vague: "the way you look at that red triangle logo will never be the same" | Subscribe + comment + "every subscriber tells YouTube…" **stacked** at 50.4–50.9% |
| **V10 CC Giant Tiger (flop)** | Instruction: "Before you shop at Giant Tiger again, keep this in mind." | A decent loop (31 words): "the receipt you're about to throw away could still be worth money next week." | Policy summary: "Giant Tiger publishes an ad match policy…" | **0 figures** in the first 160 words. A methods disclaimer at 4.4% (about 0:35): "We haven't conducted a nationwide price survey… illustrations, not receipts" | first policy at about 1:43; **no numbered list** | Abstract: "why a store can win on more items and still lose on the total bill" | **None** in the whole video |
| **V11 No Frills script** | Corporate admin act: "On October 2nd, Loblaw posted an update to a notice about customer accounts." | 38-word list of data types | Expansion figure (about seventy-five stores) | S2 (data list) | **"Number nine" at char 3,156, about 3:20** | (a) "one sign worth looking for at the front of the store" (5.6%) → paid in Protect (about 83%). (b) "three things No Frills genuinely gets right" → paid at 87%. **#1's basket result is not teased.** | Subscribe at 61.7% |

Time to first item, at each video's own pace: V5 0:31 · V3 0:35 · V2 0:38 · V4 0:38 · V6 0:43 · V8 **1:13** · V9 1:23 · V10 1:43 · V1 2:52 · V7 3:08 · V11 about 3:20.
OUR NOTE: **time to first item does not separate hits from flops** in this sample. Two big hits (V1, V7) took about 3 minutes, and a flop (V9) took 1:23. What V1 and V7 did in those 3 minutes was dense, emotional, viewer-centred claim-making ("Frankenstein food", "engineered dairy"). House rules bar that register. Our judgement: a cautious channel can't buy a long intro with outrage, so it should buy it with **speed to the first concrete item**, as V8 did.

### 3.3 Item length, re-hooks and asks

- **Tesco item lengths in characters, #9→#1:** 2,326 / 1,998 / 3,035 / 2,496 / 2,563 / 2,533 / 2,404 / 2,136 / 2,473. The mean is about 2,460 and no item exceeds 1.25× the mean.
- **No Frills items in words, #9→#1:** 258 / 258 / 220 / 255 / 201 / **350** / 317 / 267 / **458**.
- **Tesco's re-hook pattern.** Every item ends on a short kicker line, then the next number opens with a curiosity headline.
  - Kicker: "Your frying pan will tell you the truth." Next headline: "Number eight, the little letter on your packaging that…"
  - Kicker: "The picture of the barn is there to make you feel something, not to inform you." Next headline: "Number five, the price match that…"
  - Linking line, #4→#3: "This follows on naturally because it's the front end of that same data machine."
- **Costco's re-hook pattern.** "Now, the last secret on the list could be the reason you keep your membership for life." (The word "secret" is banned for us; the structure is fine.)
- **Broken Canada's re-hooks.** Chapter titles are read aloud as headlines ("The hardware store racket nobody talks about.", "The paper trail. What the investigations actually found."). These work the way "Number N. [headline]." works for us. (Their wording is not usable.)
- **Where asks sit.**
  - The best-placed ask in the set is V8's: a loop re-tease, then the ask, then the payoff.
  - V9 stacked three asks (subscribe, comment, "every subscriber tells YouTube") in one 60-word block at 50%.
  - V10 had no ask at all.
  - The No Frills ask (61.7%) is correctly placed, but it does not re-tease #1.

### 3.4 Hits against flops, plainly

1. **What the opening is about.** The hits open on the viewer's money or body: membership fee, prices, the cart, the morning coffee run. V9 opened on heritage (1922) and corporate abstractions ("financial services division… consumer data collection programs"). V10 opened on policy summaries and a methods disclaimer.
2. **What the first item is.** The hits' first item is something the viewer can act on: the Costco warranty concierge, Tesco's meat with added water. V9's first item was a human-rights complaint settlement: important, but not about the viewer's own trip, and it ran about 2 minutes.
3. **The loop.** The hits name a specific prize ("could pay for your entire membership"). The flops promise a feeling ("will never be the same") or an abstraction ("win on more items and still lose").
4. **Real data, said early.** V10 said in the first 35 s that its examples were hypothetical. Our caution belongs **next to each fact**, not as a preface that tells the viewer there are no facts.
5. **Rhythm.** V9 averaged 25 words per sentence with 0.7% short sentences, and its pace was 145 wpm against about 170 for everything else. V10 had fine rhythm and still flopped. Rhythm is necessary but not sufficient.
6. **"You".** V9 used "you" 0.40 times per 100 words, against 2.0–3.4 for the hits. Its "you" scene lasted three sentences and then disappeared.
7. **List shape.** Every hit has a countdown or ranked list with a visible end. V10 had none, and V9 had 12 issues with no countdown numbers.
8. **Topic ceiling.** Canadian Tire as a topic drew 5.4K for us and 38K/75K for Broken Canada. Those are lower ceilings than Princess Auto (529K) or Tim Hortons (181K) on the same channel in the same weeks. OUR NOTE: Broken Canada's best Canadian Tire–adjacent result (V5) framed it around the **viewer's car and money**, not the corporation.

---

## 4. CRITIQUE OF `script_nofrills.md`: the first 90 seconds and pacing (airs Oct 5)

Measured with `ct/ret_check.py`. All house-rule checks pass: 22,824 characters, ask at 61.7%, tagline ×2, disclosure ×1, four protect steps, longest sentence 38 words, no banned words.

### 4.1 What to fix, by priority

**P1: the cold open's first three sentences.** This is a 5-minute edit with no length change. Sentence 1 has Loblaw as its subject and an administrative act ("posted an update to a notice") as its verb. Sentence 2 is 38 words long, the longest sentence in the first 160 words. "You" appears **once** in the first 160 words, against 7–12 in V2, V5, V8 and V9. The cold open also leads with item #5's material (the account incident) instead of teasing #1. #1 is the money payoff, and it is the one that fits the title.

**P2: the honesty bridge is too long and too numeric before #9.** It runs 298 words (about 1:55), with 8 spoken figures (62,000 members; 0.2%; 6.1%; 1.7%; 9.1%…) before the viewer has received a single list item. "Number nine" lands at about **3:20**, which is slower than every comparison except V7.

**P3: figure density.** The script carries 4.79 spoken figures per 100 words, against 0.63–2.32 in the comparison set. Move secondary figures (store IDs, second and third unit prices, percentages that only support a point) into lower-thirds.

**P4: two long items.** #4 is 350 words and #1 is 458. Trim #1 by about 500 characters, for example by shortening the Competition Bureau ownership passage and the bread passage to one sentence each. Keep the labels.

**P5: the ask doesn't re-tease #1.** "If you want the next Canadian grocery name checked…" is fine. Add the loop before it: "Before the last two, including the store that beat No Frills in our basket, one quick thing."

### 4.2 Rewrites that keep the factual caution

Every fact below is already in the script. Nothing new is added. Drafts are in `ct/ret_examples.txt`, checked: longest sentence 27 words, no banned words.

**Cold open (replaces paragraph 1; 122 words, 701 characters):**
> On October 3rd, we looked up the same fifteen products, same product codes, at seven stores under Loblaw banners, on Loblaw's own website. The No Frills was not the cheapest. At number one, we'll show you a store that beat it, and the one item that made the difference. Meanwhile, Loblaw says it expects to open about seventy-five new grocery stores and pharmacies this year, with its grocery expansion focused predominantly on No Frills and Maxi. Yet under No Frills videos, you'll find people saying they're done with it. Both can't be the whole story. So we went through Loblaw's own filings, its own website data, the federal rules and the news record. Because the truth is not always on the menu.

- **Condition.** This depends on the Oct 5 re-capture (Appendix C, item 2). If the re-captured basket no longer has a store under Loblaw banners beating the No Frills, sentence 2 must change.
- **"Looked up".** This keeps the house wording. It is not "we bought" or "we visited".
- **The account incident.** It stays at #5 and loses nothing.

**Promise plus one "some" line (replaces paragraph 2; 80 words). This keeps the title note's "first 90 seconds" commitment:**
> Here's the plan. Nine things to know before you shop at No Frills again, counted down from nine to one. Then three things No Frills genuinely gets right. And one sign at the front of the store that matters if something scans higher than the shelf. One honest note first. Loblaw's own reports don't show Canadians leaving No Frills. They say its discount banners once again outperformed. So this is about why some shoppers are frustrated, checked against the record.

**Then "Number nine" straight away. It now starts at about 1,170 characters, about 1:15.**

**Bridge moved to after #9 (62 words):**
> Before number eight, how this works. Every key claim gets a label: a finding, an allegation, a settlement, an admission, or a company statement. Canadian Counter has no commercial relationship with No Frills, Loblaw or any retailer in this video, and none of them reviewed it. And one correction from us. Our December video said Loblaw owns FreshCo. It doesn't. Sobeys does.

**Cut:** the May 2024 boycott passage and the Q2 2024 figures (about 900 characters). If the writer wants to keep one line, use: "In 2024, CBC reported a Reddit group organised a month-long boycott of Loblaw-owned stores; CEO Per Bank told analysts the overall financial impact was minor." Its natural home is the close.

### 4.3 The constraint arithmetic for the No Frills ask (OUR NOTE)

The ask phrase now sits at character 14,080 of 22,824 (61.7%).
- **Cut alone fails.** Cutting about 1,612 characters before #9 and nothing else moves the ask to 12,468 / 21,212 = **58.8% (FAIL)**.
- **The working combination.** It passes the 61–63% rule and the 21,000 minimum:
  - cut 1,612 characters in the intro and bridge;
  - add about 900 characters as a one-sentence "you" scene in each of #9–#3 (about 130 characters each);
  - trim about 500 characters from #1.
  - Result: (14,080 − 712) / (22,824 − 712 − 500) = 13,368 / 21,612 = **61.9%**, with a total of 21,612.
- **The fallback.** If there is no time to write those scene lines, do **P1 only** (sentences 1–3) and P5. Both leave the length unchanged.
- **Re-run the checker** after any edit: `python3 scratchpad/ct/ret_check.py /home/user/Food/script_nofrills.md`.

---

## 5. RETENTION BLUEPRINT: Canadian Tire (Oct 6)

### 5.1 House constraints, built into the beat sheet
- 21,000–23,000 characters.
- Exactly one mid-list ask containing **"take a second to subscribe"**, with that phrase at 61–63% of characters.
- **"the truth is not always on the menu"** exactly twice: at the end of the hook and the last spoken line of the close.
- One no-commercial-relationship disclosure.
- A four-step "How to protect yourself" section.
- No sentence over 40 words.
- None of: secret / hidden / caught / exposed / scam / trick / quietly.
- No "we tested / bought / visited / tasted".
- Labels on every legal item.
- No comment ask mid-video; the comment prompt goes in the close only.

### 5.2 Beat sheet with character budgets (target total about 21,800; times at 160 wpm and about 5.88 characters per word)

| # | Beat | Characters (start–end) | Budget | % at start | Time at start | Job |
|---|---|---|---|---|---|---|
| B0 | Cold open (hook formula, §5.3) | 0–650 | 650 | 0% | 0:00 | "You" plus a number; plant L1; hardest labelled fact; tagline #1 |
| B1 | Promise and roadmap | 650–950 | 300 | 3.0% | 0:41 | 9→1, three positives, plant L2 (the Ontario sign) and L4 (a Triangle perk) |
| B2 | **#9** | 950–2,650 | 1,700 | 4.4% | **1:00** | Second-strongest item |
| B3 | Honesty bridge (≤70 words) | 2,650–3,050 | 400 | 12.2% | 2:49 | The "some" data with the company's reason; labels; pays L3 |
| B4 | #8 | 3,050–4,700 | 1,650 | 14.0% | 3:14 | Fast and surprising |
| B5 | #7 | 4,700–6,350 | 1,650 | 21.6% | 5:00 | Relevant to many viewers |
| B6 | #6 | 6,350–8,000 | 1,650 | 29.1% | 6:45 | Scene-led and lighter |
| B7 | #5 | 8,000–9,650 | 1,650 | 36.7% | 8:30 | Hard label (a finding), placed against the mid-video sag |
| B8 | "Halfway" re-hook (not an ask) | inside the end of #5 | about 120 | about 44% | about 10:15 | Re-tease L1 ("the five percent comes back at number one") |
| B9 | #4 | 9,650–11,450 | 1,800 | 44.3% | 10:16 | |
| B10 | #3 | 11,450–13,300 | 1,850 | 52.5% | 12:10 | Strong interest (Canadian-origin questions) to climb into the ask |
| B11 | **Ask** | 13,300–13,560 | 260 | 61.0% | 14:08 | Re-tease L1, then the ask (phrase at about 13,450 = **61.7%**), then "Now, the service bay." |
| B12 | **#2** | 13,560–15,500 | 1,940 | 62.2% | 14:25 | High-interest item to carry viewers past the ask |
| B13 | **#1** | 15,500–17,700 | 2,200 | 71.1% | 16:28 | Strongest item; pays L1 |
| B14 | How to protect yourself (four steps) | 17,700–18,950 | 1,250 | 81.2% | 18:49 | Pays L2 at step 2 |
| B15 | Pivot line | 18,950–19,070 | 120 | 86.9% | 20:08 | "None of this is about boycotting…" |
| B16 | Three positives | 19,070–20,870 | 3 × 600 | 87.5% | 20:16 | Pays L4 first |
| B17 | Close: recap in 1 sentence, comment prompt, tagline #2 | 20,870–21,370 | 500 | 95.7% | 22:11 | Keep it short. The tail drops fast |
| B18 | Sources, no-relationship disclosure, not-advice line | 21,370–21,800 | 430 | 98.0% | 22:43 | |

- **Pace.** At 160 wpm the runtime is about 23:10; at 168 wpm, about 22:05. Use the voice speed of the Costco hit (165 wpm), **not** the May Canadian Tire video's 145.
- **Rhythm targets** for every beat: mean sentence 12–16 words; 20% or more under 8 words; 12% or fewer over 25; spoken figures ≤ 3 per 100 words; "you" ≥ 2.5 per 100 words.

### 5.3 Hook formula (the first 3 sentences, then 2–4 more)

- **S1 (≤ 30 words): you + an icon + a number.** Put the viewer and a Canadian Tire object (Canadian Tire Money, the Triangle card, the red-triangle store) in the sentence with a number attributed to the company.
- **S2 (≤ 20 words): the loop.** Name a specific, checkable gap and promise the answer at a named number.
- **S3 (≤ 25 words): the hardest labelled record fact.** State it with its exact label and date.
- **S4: fairness.** The company's own words, in one sentence.
- **S5: the method line** (where we looked), then **tagline #1**.
- **Don't:** open with heritage (1922), "today we expose", a methods disclaimer, or any motive.

**Draft B (recommended; 114 words; longest sentence 29 words):**
> If you've linked your Tims app to Triangle Rewards since September, Canadian Tire says you can earn up to five percent in Canadian Tire Money on eligible Tims purchases. Read the terms, and three of those five percentage points depend on one thing in your wallet. We'll get to it at number one. In February, Canadian Tire pleaded guilty in a Quebec court to seventy-four counts over regular prices it advertised on five products in 2021. Canadian Tire says no customers were overcharged and the matter is now concluded. So we went through Canadian Tire's own filings, its own terms, provincial rules and the news record. Because the truth is not always on the menu.

Fact basis, all in ct_record (the writer re-checks each):
- **"up to 5%… eligible Tims purchases".** S9, verbatim release, Sep 2, 2026.
- **"Three of the five points depend on one thing in your wallet".** This is OUR NOTE from the S9 verbatim terms: 2% pre-tax for scanning, plus 2% post-tax **when paying with a Triangle credit card**, plus 1% **using a Triangle credit card** in Scan & Pay. So 3 of the 5 percentage points need the Triangle credit card.
- **The plea.** S20/S21, Feb 6–7, 2026; label: **guilty plea**.
- **"no customers were overcharged and the matter is now concluded".** Company statement, verbatim, via CBC/Global.

Draft A (record-first, 117 words) is in `ct/ret_examples.txt`. Use it if the Tims angle feels stale by Oct 6.

**Promise (50 words):**
> Here's the plan. Nine things to know before your next trip to Canadian Tire, counted down from nine to one. Then three things it genuinely gets right, including a perk for Triangle members. And if you're in Ontario, one sign worth looking for before you hand over your car keys.

The perk is free ship-to-home for Triangle members (S3, Q2 2026). **Re-check that it is still offered on Oct 5–6** (U15). The sign is Ontario's posted-sign requirement on parts commissions (S40).

### 5.4 Order principle for items 9→1

**Principle.**
- **#9: the second-strongest item.** It must be concrete, labelled, money-relevant, and deliverable in about 90 s. It stops the 1–4 minute drop-off.
- **#8–#6: fast, varied, "you"-scene items**, alternating weight (record → service → scene).
- **#5: a hard-label item** to break the mid-video sag (about 37–44%).
- **#3: rising interest** into the ask.
- **#2: the second-highest viewer interest**, right after the ask, so the ask costs nothing.
- **#1: the strongest item, which pays the hook's loop.**
- **Never put a non-actionable or heavy human-rights item first.** That was the V9 lesson.

**Proposed order.** Facts are from ct_record; labels follow house rule 4.

| Slot | Working headline (≤ 12 words) | Record basis (ct_record) | Label | Fix line (draft) | Why this slot |
|---|---|---|---|---|---|
| **#9** | "The regular price on the tag." | §7.2 Quebec OPC plea: 74 counts, five products, Apr–Oct 2021, fines just under $1.3M; pricing page: "Regular prices shown reflect the prices at which the products have been sold…" (S30) | **guilty plea**; company statement | "Judge a sale by the price you pay today. Compare the same model number at another retailer." | Second-strongest; the record backs it; teased in the hook, so the payoff lands by about 1:30 |
| **#8** | "The name on the door." | §2 AIF: 502 stores, 483 Dealers, "independent third parties"; prices "not exceeding those set by the Company"; "may sell for less"; "no obligation… to match online prices until the sale begins in their region" | company filing / company page | "Treat each store as its own. Check that store's page before you go." | Surprising, quick, useful |
| **#7** | "The account you made to shop online." | §7.4: breach Oct 2025 (CTC statement); HIBP 38.3M addresses (HIBP's figure); KND/Hammerco **proposed class action, not certified** | company statement; proposed class action | "Change a reused password and go to the site yourself, not through an emailed link." | Applies to many viewers; "you" is built in |
| **#6** | "The receipt check, and who decides it." | §9: CBC 2023 (receipt checks at "the discretion of individual store owners"); CBC 2024 (at least six Ontario stores scrapped self-checkout) | named outlet (b); company statement via CBC | "If a store's practice bothers you, it's that store's call, so raise it with that store." | Lighter scene item; ties back to #8 |
| **#5** | "What a privacy commissioner found in BC." | §7.3 OIPC BC, Apr 20, 2023: four stores contravened PIPA; all 12 removed facial recognition; "mutually agreed to prohibit" | **finding**; company statement | "You can ask any business what it collects and why, and make a request to see the personal information it holds about you." (**Verify the exact rights wording before use**; U16) | Hard label against the mid-video sag; fair ending built in. Must say "2023" |
| **#4** | "The price tool with a name: DaiVID." | §8: Hicks, "drop prices on more than 5,000 products"; CTC: "We do not use DaiVID for algorithmic pricing or real-time dynamic pricing." | company statement | "Photograph the shelf tag on anything big, and check it against your receipt." | Topical; never imply personalised pricing (U23 in ct_record) |
| **#3** | "Where the box on the shelf comes from." | §11: Hicks, about 15% of goods from the U.S.; AIF: about 50% of CTR inventory purchases sourced directly from outside Canada, primarily Asia (**different bases; do not combine**) | company statement / company filing | "Read the origin line on the box, not the flag on the sign." | High interest for this audience (our "ACTUALLY Canadian" titles: ketchup 90K, bread 42K) |
| *ASK* | | | | | |
| **#2** | "The service bay." | §10: AIF, "over 5,600 automotive service bays"; Automotive Service "record annual sales of $1 billion"; Ontario CPA: written estimate, **10% cap**, commission sign; **no Marketplace investigation of Canadian Tire auto service found** | company filing; statute/government page | "In Ontario, ask for a written estimate. The final bill can't be more than ten percent above it." | Second-highest interest (V5 drew 75K); carries viewers past the ask |
| **#1** | "The Canadian Tire Money rule." | §5.2 Tims terms (verbatim); "Canadian Tire Money can only be redeemed at…" (the list excludes Tim Hortons); §6: "CTFS distributes approximately 75% of all eCTM through its relationship with 2.3 million members who carry Triangle credit cards"; OUR NOTE worked example ($10 pre-tax → about 53¢ maximum; 20¢ without the card) | company statement; OUR NOTE | "Before you link anything, decide whether the card is worth it to you, and check what you actually earn on your own receipts." | Strongest; pays L1; the most Canadian-Tire-specific item |

Spare items if a slot fails verification:
- True North restructuring (§4). Avoid "closing stores" (ct_record says nothing supports it).
- Party City Canada (2019).
- Triangle Mastercard rate. **Do not quote 21.99% unless screenshotted** (ct_record U8).

### 5.5 Open-loop plan

| Loop | Planted (position) | Wording (draft) | Re-teased | Closed |
|---|---|---|---|---|
| **L1 (main)** | Hook S2, about 0:08 (char about 200) | "three of those five percentage points depend on one thing in your wallet. We'll get to it at number one." | about 44% ("Halfway. The five percent from the start comes back at number one.") and at the ask (61%) | **#1** (about 71–75%) |
| **L2** | Promise, about 0:50 | "if you're in Ontario, one sign worth looking for before you hand over your car keys" | #2 ("remember that sign") | **Protect step 2** (about 83%). This pulls viewers through #1 into Protect, as in No Frills/Tesco |
| **L3 (quick)** | Hook, optional S3b | "while two of its other chains grew" (only if Draft B is extended) | none | **Bridge** (about 2:50): "SportChek and Mark's grew." An early, small payoff that teaches the viewer we pay our loops |
| **L4** | Promise, about 0:45 | "including a perk for Triangle members" | Protect step 3 | **Positive 1** (about 88%); props up the tail |
| Micro-loops | Each item's headline | e.g., "The price tool with a name." (the answer within 20 s: DaiVID) | none | Inside the item |

Rule: **every loop gets paid on air.** Tesco's unpaid "one setting" loop (U3) is the thing not to copy.

### 5.6 Per-item micro-structure (≤ about 300 words, about 1,650–1,800 characters)

1. **Headline line (≤ 12 words).** "Number nine. The regular price on the tag." It must name a concrete thing, and it must not make a claim.
2. **Scene (1–2 sentences, ≤ 40 words, uses "you").** Where the viewer meets this: the flyer, the app, the service desk, the door.
3. **Fact (3–6 sentences).** Dated, attributed and labelled, with at most 3 spoken figures. Every other figure goes in the lower-third: "#9 · Quebec OPC · Feb 6, 2026 · guilty plea".
4. **Fairness (1–2 sentences).** The company's statement, verbatim and attributed, or the limit of the record ("That was five products, in 2021, in Quebec.").
5. **Fix (1 sentence).** Always starts "The fix:" and is an action the viewer can take this week.
6. **Re-hook (≤ 20 words).** A kicker or bridge into the next number (§5.7).

Budget per item: headline 60 · scene 220 · fact 900 · fairness 250 · fix 150 · re-hook 120 = **about 1,700 characters**.

**Skeleton for #9, structure only.** The writer fills it from ct_record §7.2 and must check every line:
> Number nine. The regular price on the tag. [scene: you see a tool marked down from its regular price in a flyer, ≤ 25 words, no implication about today's prices] [fact: OPC checked seven products in flyers, online and at three Montreal-area stores, April to October 2021; Canadian Tire pleaded guilty on five; 74 counts; just under $1.3 million] [what "regular price" means on Canadian Tire's own pricing page, verbatim] [fairness: company statement, verbatim; "That's one province, five products, in 2021."] The fix: judge a sale by the price you pay, and compare the same model number elsewhere. [re-hook]

### 5.7 Re-hook lines (channel voice; no wrongdoing claims; none of the banned words)

Each was checked: longest 18 words, no banned words.
1. "That one was about the price tag. The next one is about who owns the store."
2. "Keep that in mind, because number seven is about the account you may have made to shop online."
3. "That's the company's statement. Here's the part you can check yourself."
4. "Number five comes from a privacy commissioner's report, and it has a clear ending."
5. "Four to go, and the next one is about where the box on the shelf comes from."
6. "If you only keep one fix so far, keep that one. Now, the service bay."
7. "Hold on to that number, because it comes back at number one."
8. "Here's where the five percent from the start of this video comes back."
9. "Easy to miss, easy to fix. Here's the fix."
10. "That's the record. Now, what you can actually do about it."
11. "So far that's the shelf and the till. The next one isn't on the shelf at all."
12. "Two left, and they're the two that touch your wallet most directly."

### 5.8 The honesty bridge (after #9; ≤ 70 words) and where the disclosure goes

**Bridge, with figures (65 words):**
> Quick honesty check, because the title needs it. Canadian Tire's own figures show comparable sales in its Canadian Tire Retail business down two point three percent in the first quarter and zero point eight in the second. The company points to weather and seasonal sales. SportChek and Mark's grew. That's not a boycott, and we won't call it one. Every key claim gets a label.

The basis is ct_record §3.1 and §3.2 (S3, S4); these are CTC's non-GAAP figures. A version without figures (56 words) is in `ct/ret_examples.txt`.

**Disclosure (once; 23 words).** Put it in B18 with the sources line. If the producer wants it earlier, put it as the last line of the bridge and cut "Every key claim gets a label" so the bridge stays ≤ 70 words.
> Canadian Counter has no commercial relationship with Canadian Tire or any company in this video, and none of them reviewed it before release.

### 5.9 The mid-list ask (B11; 46 words; phrase at about 61.7%)
> Before the last two, which touch your wallet most directly, one quick thing. If you want the next Canadian name checked against the record like this, take a second to subscribe. Canadian Counter reads the fine print so you don't have to. Now, the service bay.

This follows the V8 pattern: a loop re-tease, then the ask, then an immediate payoff. There is no comment ask here. Only one ask, as the house rules require.

### 5.10 The tail (protect, positives, close)
- **Protect (1,250 characters).** Four steps, each one sentence of rule plus one of action. Pay L2 at step 2 (the Ontario sign and the 10% cap). Step 3 is Canadian Tire Money and the card decision. Step 4 is account safety.
- **Positives (3 × about 600 characters).** Lead with the most usable: free ship-to-home for Triangle members (S3; re-check), then the Dealer price ceiling and "may sell for less" (S1, S30), then the price cuts on more than 5,000 products (company statement, S11). The facial-recognition prohibition could be a fourth, but it is already at #5.
- **Close (≤ 500 characters).** One-line recap ("nine things worth knowing, three worth using"), the comment prompt ("which of the nine surprised you, and is your Canadian Tire better or worse than most?"), tagline #2 as the **last spoken line before the sources paragraph**.
- **Chapters (OUR judgement, untested).** Hold description chapters for the first 48 hours. Chapters let viewers jump straight to #1, which can lower % viewed.

---

## 6. PRE-FLIGHT CHECK (run on the finished Canadian Tire script)

`python3 /tmp/claude-0/-home-user-Food/63b91656-26a4-59d5-baf9-bd65edc4c0dd/scratchpad/ct/ret_check.py <script.md>`

**What it checks** (spoken body = the text between the first two `---` lines):
- length 21,000–23,000;
- "take a second to subscribe" once, at 61–63%;
- the tagline exactly twice;
- the disclosure once;
- a protect section with First/Second/Third/Fourth;
- no sentence over 40 words;
- banned words;
- "we tested/bought/visited/tasted";
- "Number nine." through "Number one." in order.

**What it reports:** each item's start time and word count (flagging items over 330 words); time to the first item (flagging anything after 1:15); "you" per 100 words; spoken figures per 100 words; and "you" and figures in the first 160 words.

**Result on the No Frills script:** every rule passes. It **fails** "first item by 1:15" (3.31 min), and it flags #4 (350 words), #1 (458 words), "you" at 1.55 and figures at 4.79.

---

## 7. UNVERIFIED / DO-NOT-USE (mandatory)

| # | Item | Status | Action |
|---|---|---|---|
| U1 | Any audience-retention, average-view-duration or %-viewed data for V1–V10 | **None available.** The NexLev account is connected to a different channel ("Flip Choose", UC_Wg7NQGrR73F8YnLw6VZ6g), not Canadian Counter (UCkuoOyuZyRqA49o5irJai9A). Every "retention" conclusion here is inferred from views plus structure | Pull YouTube Studio retention for V7, V8 and V9 before treating any rule here as proven. Compare the curves at 0:30, 1:00 and 3:00 |
| U2 | Sentence statistics and word counts for V1–V10 | Auto-caption punctuation is machine-inserted | Treat them as approximate; only V11's are exact |
| U3 | Tesco's "one setting on Tesco's own website" loop | No payoff found in the caption track. It may have been on screen only | Don't cite it as an example of a broken promise in public; use it internally only |
| U4 | "102K in a day" for the Tesco template | 105,398 views about 2 days after upload (Oct 4 snapshot) | Say "about 105K in two days" if it's needed internally |
| U5 | Pace and runtime estimates (160–168 wpm) | Taken from our past videos' word counts and API durations, which include music and outros | Time the Oct 6 TTS voice on a 1,000-character sample |
| U6 | Causal claims ("the flop flopped because…") | Correlational; one or two examples each. Titles, thumbnails, topic and upload timing are confounders | Use as heuristics, not findings |
| U7 | Every Canadian Tire fact in the example lines (§5.3–5.9) | Taken from `ct_record.md`; **I did not re-open S1, S3, S9, S11, S20, S21, S30 or S40** | The writer checks each line against ct_record and its raw captures before recording |
| U8 | "Three of those five percentage points depend on the Triangle credit card" | OUR NOTE from the S9 verbatim terms. Tims T&Cs (ct_record U9) not opened; there may be caps or exclusions | Keep "up to" and "eligible"; read timhortons.ca/terms-conditions-rewards before Oct 6 |
| U9 | Triangle base earn (0.4%), Triangle Mastercard 21.99%, Triangle Select price | ct_record U8, U10, U11: WebFetch or third-party only | **Not in the hook, not in #1** unless screenshotted |
| U10 | The OUR NOTE worked example ($10 pre-tax, about 53¢ maximum, 20¢ without the card) | Arithmetic on a hypothetical, assuming 13% HST | On air, say "a ten-dollar order before tax, in a province with thirteen percent HST" and show it on screen |
| U11 | The "2.3 million cardholders" and "more than 12 million members" ratio | Different definitions (ct_record U13) | Never compute a share on air |
| U12 | Competitor lines quoted in §3 (e.g., "Canadian Tire did the math and walked away", "$63 becomes $840", "quietly stopped", "Millions… boycotting") | Unsourced; some imply wrongdoing or motive | **Do not use on air.** Quoted here only to describe structure |
| U13 | V7 yogurt structure | Relied on health and quality claims that rules 1 and 2 now bar | Copy the pacing, not the content |
| U14 | The No Frills cold-open rewrite's sentence 2 ("The No Frills was not the cheapest.") | Depends on the Oct 5 basket re-capture (script Appendix C, item 2) | Re-check before recording; change the line if the order changes |
| U15 | Free ship-to-home for Triangle members (L4, Positive 1) | From the Q2 2026 release (S3); current status on Oct 6 not checked | Screenshot canadiantire.ca on Oct 5 |
| U16 | #5 fix wording on privacy rights (BC PIPA, or PIPEDA elsewhere) | Not researched here | Verify the exact rights wording, or use a generic fix ("ask the store what it collects and why") |
| U17 | Ontario sign and 10% cap outside Ontario | Ontario only (ct_record U21) | Always say "in Ontario" |
| U18 | Advice on chapters and "about 1,700 characters per item" | Our judgement from V1/V8 patterns; untested on this channel | Run as an experiment, and log the result in YouTube Studio after 7 days |
| U19 | Broken Canada channel names (V2–V6) | API-returned author "Broken Canada"; handle @BrokenCanadaYT resolved to UC5t8AOTkuBoniaaif-mTHfQ | Internal use only; not named on air |
| U20 | Recalls / product safety | None researched or used in this dossier | n/a |

Count of unverified / do-not-use items: **20**.

---

# DOSSIER (record) — Canadian Tire Corporation: the dated public record, 2024 to Oct 2026

For: Canadian Counter, "Why Some Canadians Are Refusing to Shop At Canadian Tire Anymore" (airs Oct 6, 2026)
Compiled: Oct 4, 2026. Every source below was opened on **Oct 4, 2026** unless a different date is given.
Raw captures: `scratchpad/ct/` (newswire releases in `ct/nw/*.html|.txt`; AIF in `ct/aif2025.pdf|.txt`; transcripts in `ct/r5DkjCpiSWo.txt`, `ct/GGMQoWEGjbU.txt`).

**How to read this file**
- **Tier**: (a) primary (statute, regulator, court, company filing, page or release, StatCan); (b) named outlet with byline and date; (c) do-not-use (Reddit, forums, deal blogs, newsletters, unsourced YouTube); (d) named survey.
- **Label** (house rule 4) on every legal or regulatory item: *finding*, *allegation*, *settlement*, *admission*, *consent agreement*, *guilty plea*, *proposed class action*, *certified*, or *company statement*.
- **Capture method**: "curl" means the raw page is saved and the quote was copied from it word for word. "WebFetch" means a summarising tool read the page. Its quote marks are **not guaranteed verbatim**, so check those lines in a browser before any on-screen quote.
- **OUR NOTE** marks our own arithmetic or inference. It is never the company's or the outlet's statement.
- **No prices** are in this dossier. Prices are another dossier's job (house rule 5).
- **No recalls or product-safety material** is used. See Appendix R, which is DO NOT USE ON AIR.

---

## 0. HEADLINE FINDINGS FOR THE WRITER (the 12 that matter most)

1. **Dealers can sell for less, but not for more.** CTC's 2025 AIF (Feb 18, 2026) says its Dealers agree to offer "merchandise for sale to consumers at prices not exceeding those set by the Company". The pricing page adds: "Canadian Tire Associate Dealers may sell for less." [S1, S30]
2. **The Canadian Tire banner's comparable sales fell in both 2026 quarters**: Q1 down 2.3% and Q2 down 0.8%. SportChek and Mark's grew in both. CTC blames weather (Q2: "weather-impacted categories"; Q1: "seasonal weakness impacting Ontario and Quebec"). On a two-year stack, CTR is up 5.5% (Q2). This is the strongest *data* hook for "some", and it must not be presented as a boycott. [S3, S4]
3. **Guilty plea in Quebec (Feb 6, 2026).** La Société Canadian Tire ltée pleaded guilty to 74 counts under s. 225 b) of Quebec's Consumer Protection Act (falsely stating a regular or reference price). Fines and costs total $1,287,550. Five products were involved: Henckels and Cuisinart knife sets, Lagostina and Heritage cookware, and a Dewalt cordless drill, checked April–October 2021. Label: **guilty plea**. [S20, S21, S22]
4. **The 2012-era Competition Bureau tire pricing case named in the brief could not be found against CTC.** The well-known regular-price tire case is ***Sears Canada*** (Competition Tribunal, 2005). Do **not** attribute it to Canadian Tire. We found no Competition Bureau enforcement action against CTC in 2024–2026 (see U1). [S23]
5. **Privacy finding (BC, Apr 20, 2023).** The BC OIPC found that four BC Canadian Tire stores contravened PIPA by using facial recognition technology (2018–2021). Twelve BC stores were using it, and all 12 removed it. Label: **finding** (a regulator's investigation report). [S24, S25]
6. **E-commerce data breach (identified Oct 2, 2025; disclosed Oct 14, 2025).** CTC said the breach involved name, address, email, year of birth, encrypted passwords and some truncated card numbers, plus full date of birth for "fewer than 150,000 accounts". Have I Been Pwned lists 38,306,562 email addresses. A **proposed class action** (KND and Hammerco) was announced Jul 24, 2026 and is **not certified**. [S26, S27, S28, S29]
7. **Tims link, exact terms (launched Sep 2, 2026).** Members earn up to 5% in Canadian Tire Money: 2% pre-tax for scanning Tims Rewards, plus 2% *post-tax* when paying with a Triangle credit card, plus 1% pre-tax using a Triangle card in Tims app Scan & Pay. CT Money **cannot** be redeemed at Tims. "Not all Tim Hortons locations participate." [S9, S10]
8. **AI pricing tool "DaiVID".** On the Q2 call (Aug 13, 2026), Hicks said CTC used DaiVID "to drop prices on more than 5,000 products". A CTC spokesperson told Global News: "We do not use DaiVID for algorithmic pricing or real-time dynamic pricing." [S11]
9. **True North (Mar 6, 2025).** More than $2 billion over four years, about $85M in one-time charges "including severance", 17 standalone Atmosphere stores closed, and an undisclosed number of corporate roles cut (CTV, Jul 29, 2025). Helly Hansen was sold to Kontoor for $1,276M (announced Feb 19, 2025; closed Jun 2, 2025). [S5, S6, S7, S8, S12]
10. **Party City Canada was acquired in 2019, not 2023.** The deal was announced Aug 8, 2019 at $174.4M. The brief's "2023" is wrong. [S31, S32]
11. **Auto service.** The AIF says Canadian Tire stores house "over 5,600 automotive service bays". CTC says Automotive Service reached "record annual sales of $1 billion" (Q4 2025). Ontario law caps the final bill at 10% over a written estimate and requires a posted sign disclosing commissions on parts. No CBC Marketplace investigation of Canadian Tire auto service was found. [S1, S2, S40]
12. **Tariff statements.** In Feb 2025 Hicks said about 15% of goods come from the U.S., 25–30% of those could be re-sourced in Canada, and tariff threats had "substantially erased" a consumer-confidence uptick. In May 2025 he said customers were "more resilient than we anticipated". In Aug 2026 he said "consumer sentiment remained soft". [S13, S14, S15, S11]

---

## 1. SOURCE REGISTER

| ID | Source | Date of source | URL | Tier | Capture |
|---|---|---|---|---|---|
| S1 | CTC 2025 Annual Information Form | Feb 18, 2026 | https://s201.q4cdn.com/326551073/files/doc_financials/2025/ar/AIF-EN.pdf | a | curl → ct/aif2025.pdf, .txt |
| S2 | CTC release: Q4 & FY2025 results | dateline Feb 18, 2026 (newswire timestamp Feb 19, 2026 06:02 ET) | https://www.newswire.ca/news-releases/canadian-tire-corporation-reports-strong-fourth-quarter-and-full-year-2025-results-and-significant-progress-in-first-year-of-true-north-transformation-strategy-800572198.html | a | curl |
| S3 | CTC release: Q2 2026 results | Aug 13, 2026 | https://www.newswire.ca/news-releases/canadian-tire-corporation-reports-second-quarter-2026-results-866796557.html | a | curl |
| S4 | CTC release: Q1 2026 results | May 14, 2026 | https://www.newswire.ca/news-releases/canadian-tire-corporation-reports-first-quarter-2026-results-826611042.html | a | curl |
| S4b | CTC releases: Q1 2024, Q2 2024, Q3 2024, FY2024, Q1 2025, Q2 2025, Q3 2025 | May 9 2024; Aug 8 2024; Nov 7 2024; Feb 13 2025; May 8 2025; Aug 7 2025; Nov 6 2025 | newswire.ca (files in ct/nw/) | a | curl |
| S5 | CTC release: True North launch | Mar 6, 2025 | https://www.newswire.ca/news-releases/canadian-tire-corporation-launches-true-north-transformative-growth-strategy-newly-designed-leadership-team-and-operating-model-will-accelerate-customer-focus-agility-and-scale-877713282.html | a | curl |
| S6 | CTC release: sale of Helly Hansen to Kontoor | Feb 19, 2025 | https://www.newswire.ca/news-releases/canadian-tire-corporation-announces-sale-of-helly-hansen-to-kontoor-brands-simplifying-ctc-portfolio-to-focus-on-canadian-retail-growth-825248061.html | a | curl |
| S7 | CTC release: Helly Hansen sale completed | Jun 2, 2025 | https://www.newswire.ca/news-releases/canadian-tire-corporation-announces-completion-of-helly-hansen-sale-823570749.html | a | curl |
| S8 | CP24/CTV News, Lynn Chaya, "Canadian Tire says it has eliminated some corporate roles" | Jul 29, 2025 | https://www.cp24.com/news/canada/2025/07/29/canadian-tire-says-it-has-eliminated-some-corporate-roles/ | b | curl |
| S9 | CTC/Tims release: Tims partnership launch | Sep 2, 2026 | https://www.newswire.ca/news-releases/triangle-rewards-and-tims-rewards-launch-loyalty-partnership-832879003.html | a | curl |
| S9b | CTC/Tims release: partnership announced | Sep 15, 2025 | https://www.newswire.ca/news-releases/canadian-tire-corporation-and-tim-hortons-two-of-canada-s-most-beloved-brands-team-up-in-strategic-loyalty-partnership-816536197.html | a | curl |
| S10 | CP24 / The Canadian Press (Tara Deschamps), "Canadian Tire and Tim Hortons launch partnership to boost loyalty programs" | Sep 2, 2026 | https://www.cp24.com/news/canada/2026/09/02/canadian-tire-and-tim-hortons-launch-partnership-to-boost-loyalty-programs/ | b | curl |
| S11 | Global News, Ariel Rabinovitch, "Canadian Tire says consumer sentiment 'soft' amid trade war, tariffs" | Aug 13, 2026 | https://globalnews.ca/news/12019942/canadian-tire-earnings/ | b | curl |
| S12 | CTC release: HBC brand assets | May 15, 2025 | https://www.newswire.ca/news-releases/canadian-tire-plans-to-steward-the-hbc-coat-of-arms-and-stripes-with-purchase-of-iconic-hudson-s-bay-company-brand-assets-821329224.html | a | curl |
| S13 | Global News / CP, Tara Deschamps, "Tariff threats 'substantially erased' economic rebound: Canadian Tire CEO" | Feb 13, 2025 | https://globalnews.ca/news/11017812/tariff-threats-impact-consumer-confidence-canadian-tire-ceo/ | b | curl |
| S14 | Yahoo Finance Canada, Alicja Siekierska, "'So unfortunate on so many levels'…" | Feb 13, 2025 | https://ca.finance.yahoo.com/news/so-unfortunate-on-so-many-levels-canadian-tire-reviewing-product-sourcing-due-to-trump-tariffs-165638425.html | b | curl |
| S15 | BNN Bloomberg / CP (Tara Deschamps), "Shoppers 'more resilient' in face of tariffs than Canadian Tire CEO expected" | May 8, 2025 | https://www.bnnbloomberg.ca/business/company-news/2025/05/08/canadian-tire-q1-profit-down-from-year-ago-due-to-restructuring-costs/ | b | curl |
| S16 | RBC/CTC release: RBC link launch | Jan 13, 2026 | https://www.newswire.ca/news-releases/rbc-and-canadian-tire-corporation-launch-loyalty-partnership-unlocking-more-rewards-and-value-for-millions-of-canadians-810907949.html | a | curl |
| S17 | CTC/WestJet release: WestJet link launch | Mar 25, 2026 | https://www.newswire.ca/news-releases/canadians-can-now-spend-once-and-earn-twice-with-innovative-canadian-tire-corporation-and-westjet-loyalty-partnership-865830134.html | a | curl |
| S18 | CTC/Petro-Canada release | Mar 26, 2024 | https://www.newswire.ca/news-releases/canadian-tire-corporation-and-petro-canada-tm-fuel-new-adventures-with-loyalty-partnership-launch-869534318.html | a | curl |
| S19 | CTC release: strategic review of Financial Services completed | Dec 6, 2024 | https://www.newswire.ca/news-releases/canadian-tire-corporation-completes-strategic-review-of-its-financial-services-business-823785247.html | a | curl |
| S20 | Office de la protection du consommateur (OPC), "La Société Canadian Tire ltée plaide coupable" (French) | Feb 6, 2026 | https://www.opc.gouv.qc.ca/actualite/communiques/article/canadian-tire-plaide-coupable ; newswire copy https://www.newswire.ca/fr/news-releases/faux-prix-de-reference-pour-des-produits-en-solde-la-societe-canadian-tire-ltee-plaide-coupable-818177860.html | a | curl |
| S21 | CBC News / The Canadian Press, Pierre Saint-Arnaud, "Canadian Tire slammed with near $1.3M fine for false advertising" | Feb 7, 2026 | https://www.cbc.ca/news/canada/montreal/canadian-tire-fine-false-advertising-9.7079005 | b | curl |
| S22 | Global News (Staff/CP), "Canadian Tire ordered to pay nearly $1.3 million for false advertising" | Feb 7, 2026 | https://globalnews.ca/news/11657561/que-canadian-tire-fines/ | b | curl |
| S23 | Competition Tribunal, Sears Canada decision summary CT-2002-004 (for contrast only) | 2005 | https://www.ct-tc.gc.ca/en/cases/decision-summaries/CT-2002-004.html | a | search result only, not opened |
| S24 | OIPC BC news release, "Investigation finds Canadian Tire Associate Dealers not authorized to use facial recognition technology" | Apr 20, 2023 | https://www.oipc.bc.ca/documents/news-releases/2619 | a | curl (PDF) → ct/oipcbc_2619.txt |
| S25 | CBC News / CP, Dirk Meissner, "Canadian Tire stores in B.C. broke privacy laws on facial ID technology…" | Apr 20, 2023 | https://www.cbc.ca/news/canada/british-columbia/canadian-tire-bc-facial-id-technology-privacy-commissioner-1.6817039 | b | curl |
| S26 | CTC advisory: e-commerce data incident | Oct 14, 2025 | https://www.newswire.ca/news-releases/advisory-canadian-tire-corporation-e-commerce-data-incident-887782556.html | a | curl |
| S27 | Global News / CP, Tara Deschamps, "Canadian Tire says recent data breach may have hit online shoppers' info" | Oct 14, 2025 | https://globalnews.ca/news/11477315/canadian-tire-data-breach-customers/ | b | curl |
| S28 | Have I Been Pwned breach entry "CanadianTire" (API) | added Feb 25, 2026 | https://haveibeenpwned.com/api/v3/breach/CanadianTire | b (named security service, not a regulator) | curl → ct/hibp.json |
| S29 | KND Complex Litigation & Hammerco Lawyers release, proposed class action | Jul 24, 2026 | https://www.newswire.ca/news-releases/knd-complex-litigation-and-hammerco-lawyers-llp-announce-proposed-consumer-data-privacy-class-action-against-canadian-tire-898489593.html | a (plaintiff counsel's own release; contains **allegations only**) | curl |
| S30 | canadiantire.ca Pricing Policy | undated page | https://www.canadiantire.ca/en/customer-service/policies/pricing-policy.html | a | WebFetch, plus a raw text capture by a sibling task: ct/customer-service_policies.txt (14:17 Oct 4) |
| S31 | CTV News, Jeremiah Rodriguez, "Canadian Tire buys up Party City Canada for $174.4 million" | Aug 8, 2019 | https://www.ctvnews.ca/canada/article/canadian-tire-buys-up-party-city-canada-for-1744-million/ | b | curl |
| S32 | Party City Holdco Q2 2019 results, SEC 8-K Ex. 99.1 | Aug 2019 | https://www.sec.gov/Archives/edgar/data/1592058/000119312519215993/d672303dex991.htm | a | curl |
| S33 | CBC News, Sophia Harris, self-checkout theft and receipt checks | Jul 10, 2023 | https://www.cbc.ca/news/business/self-checkout-theft-receipt-retailers-1.6899677 | b | curl |
| S34 | CBC News, Sophia Harris, stores ditching self-checkout | Apr 30, 2024 | https://www.cbc.ca/news/business/self-checkout-walmart-giant-tiger-1.7188556 | b | curl |
| S35 | CBC News (RCI English copy), Sophia Harris, "Customers are fed up with anti-theft measures at stores…" | page shows May 16, 2024 (verify) | https://ici.radio-canada.ca/rci/en/news/2073236/customers-are-fed-up-with-anti-theft-measures-at-stores-retailers-say-organized-crime-is-to-blame | b | curl |
| S36 | CBC Go Public, Rosa Marchitelli, "Routine oil change turns into highway hazard after Canadian Tire uses plastic zip ties…" | Oct 20, 2025 | https://www.cbc.ca/news/gopublic/canadian-tire-zip-tie-repair-9.6931461 | b, **safety: DO NOT USE ON AIR** | curl |
| S37 | CBC News, Kathy Tomlinson, "Canadian Tire store sells questionable repairs" | Nov 30, 2010 | https://www.cbc.ca/news/canadian-tire-store-sells-questionable-repairs-1.879107 | b (old) | curl |
| S38 | Canadian Tire Bank Triangle Mastercard page (rates, earn) | undated | https://www.canadiantire.ca/mastercard | a | **WebFetch only** |
| S39 | Triangle Rewards legal information page | "effective as of March 26, 2025" per WebFetch | https://triangle.canadiantire.ca/en/legal-information.html | a | **WebFetch only** (curl 403) |
| S40 | Ontario.ca, "A guide for auto repair businesses" | updated Aug 19, 2025 | https://www.ontario.ca/page/guide-auto-repair-businesses | a | curl |
| S41 | SP Avocats, class action page: Canadian Tire Bank cash advance fees (Option consommateurs) | notice Feb 14, 2017 | https://spavocats.ca/en/class-actions/canadian-tire-credit-cards-cash-advance-charges/ | a/b (plaintiff counsel page) | curl |
| S42 | CTC cyber incident page | undated | https://corp.canadiantire.ca/English/Cyber-Incident/default.aspx | a | **WebFetch only** (curl 403) |
| S43 | Broken Canada video r5DkjCpiSWo, "Canadian Tire and 9 Other Auto Repair Chains Just Got Caught — Something Felt Wrong" | published Sep 27, 2026; 75,005 views on Oct 4 | https://www.youtube.com/watch?v=r5DkjCpiSWo | c | transcript → ct/r5DkjCpiSWo.txt |
| S44 | Canadian Rant video GGMQoWEGjbU, "Canadians Have Had Enough of Canadian Tire" | published Jun 19, 2026; 21,636 views on Oct 4 | https://www.youtube.com/watch?v=GGMQoWEGjbU | c | transcript → ct/GGMQoWEGjbU.txt |
| S45 | Do Not Pass Go (Substack), Peter Nowak, "Caught, Fined… Still On Sale?" | Feb 11, 2026 | https://www.donotpassgo.ca/p/caught-fined-and-still-on-sale-canadian | c (newsletter; lead only) | WebFetch |

Channel names for S43 and S44 come from the brief. The video-data API returned titles, dates and views, but not channel names (see U25).

---

## 2. CORPORATE STRUCTURE AND THE ASSOCIATE DEALER MODEL (CTC's own words)

**S1, the 2025 AIF dated Feb 18, 2026 (tier a). Label: company filing.**

- Scale: "Today, the Company has one of the largest retail store networks in Canada, with more than 1,400 stores, one of the country's largest loyalty programs, Triangle Rewards, with 12.2 million active members, and a credit card portfolio with 2.3 million active credit cardholders." (p. 4)
- Canadian Tire store count: "Through a network of 502 stores across the country operated by Dealers and its online digital channels…" (p. 5). Also: "more than 186,000 products in 212 product categories across five divisions: Automotive, Fixing, Living, Playing, and Seasonal & Gardening." (p. 6)
- **What a Dealer is:** "Canadian Tire's 502 stores are operated by Dealers, who are independent third parties that own the fixtures, equipment and inventory of the stores they operate, employ the store staff, and are responsible for store operating expenses." (p. 6)
- **Prices and stock, verbatim:** "Each Dealer agrees to comply with prescribed policies, marketing plans and operating standards, which among other things, include purchasing merchandise primarily from CTC, while maintaining the decision-making behind customizing their assortments to meet the demands of the communities in which they operate, and offering merchandise for sale to consumers at prices not exceeding those set by the Company." (p. 6)
- Contract term: "Individual Dealer contracts are in a standard form, each of which generally expires on December 31, 2039." (p. 6)
- Dealer count: "CTC has entered into a standard form contract with each of its 483 Dealers…" (s. 2.5, p. 15)
- What CTC does for Dealers: "category business management, marketing, purchasing, product curation and distribution… administrative, financial, and IT services, as well as operational support…" (p. 6)
- 2025 contract change: "CTC negotiated amendments to its contracts with Dealers, strengthening joint alignment on the True North strategic priorities." (s. 3.1). The same wording appears in S2 as "During the third quarter of 2025".
- Party City: "a leading, one-stop shopping destination for party supplies with 69 stores operated by Dealers." (p. 7)
- Other banners, end of 2025: PartSource 82 stores in the text but **81 in the table** (internal discrepancy; see U14). PHL 21. SportChek 190 corporate stores; Sports Experts 91, Atmosphere 44 and Le Trio Hockey 29 franchise stores. Mark's 357 corporate and 29 franchise stores. Petroleum 277 gas bars.
- Provincial split of the 502 Canadian Tire stores: BC 53, AB 58, SK 16, MB 15, ON 202, QC 100, NB 19, NS 22, PEI 2, NL 13, YT 1, NT 1. (p. 7)
- Property: "Of the 502 stores, 34 are located on properties owned by the Company, 337 are located on properties leased to the Company by CT REIT, and the remaining 131 are located on properties leased to either the Company or individual Dealers by third parties." (p. 7)
- Electronic shelf labels: refreshed stores feature "new technology including deployment of electronic shelf labels." (p. 7). OUR NOTE: this is a fact about refreshed stores only. It is not evidence of any dynamic pricing (see §8).
- Employees: "As at January 3, 2026, CTC employed 11,877 full-time and 17,050 part-time permanent employees. The figures do not include employees at Canadian Tire and Party City stores…" (s. 2.7)
- Sourcing: "In 2025, approximately 50 percent of Canadian Tire Retail, 33 percent of Mark's, and 21 percent of SportChek inventory purchases were sourced directly from vendors outside Canada, primarily from Asia, and denominated in U.S. dollars." (p. 11)
- Legal proceedings, the whole section: "In the ordinary course of business, CTC is a party to a number of legal and regulatory proceedings which may involve monetary damages and other relief. CTC cannot determine the ultimate outcome of all outstanding proceedings, but believes that their ultimate disposition will not have a material adverse effect…" (s. 10)

**Pricing page (S30, tier a), verbatim lines confirmed in the raw capture:**
- "Canadian Tire Associate Dealers may sell for less."
- "Dealers are under no obligation to make promotional products available, or to match online prices until the sale begins in their region."
- "Regular prices shown reflect the prices at which the products have been sold by Canadian Tire as of the date of issuance indicated."
- From WebFetch only: "online prices…may differ from those in store and may vary by geographic region."

**How CTC describes Dealers to the media (company statements):**
- To CBC in 2023: "While Canadian Tire stores are independently owned and operated by associate dealers, the corporation and the dealers have mutually agreed to prohibit the use of facial recognition technology in Canadian Tire stores." [S25]
- To CBC Go Public in 2025, head office said "its locations are independently owned and operated, and its response is based only on information provided by that local dealer" (CBC's paraphrase in a caption). [S36]
- To CBC in 2023 on receipt checks: "receipt and bag checks, which are left up to the discretion of individual store owners, are commonly used in the industry for 'inventory control.'" (CBC paraphrase with an inner quote) [S33]

OUR NOTES
- 502 stores against 483 Dealers: there are 19 more stores than Dealer contracts. **Do not infer** how many Dealers run multiple stores. The AIF doesn't say, and Party City stores are also Dealer-run.
- Ontario has 202 of 502 stores (40.2%) and Quebec 100 (19.9%).
- CTC's permanent workforce: 11,877 + 17,050 = 28,927. This **excludes** staff in Dealer-run Canadian Tire stores.

---

## 3. FINANCIALS 2024 → Q2 2026 (CTC releases, tier a, label: company statement)

### 3.1 Comparable sales by banner (as stated in each release)

| Period | Release date | Consolidated | CTR | SportChek | Mark's | CEO line or context (verbatim) |
|---|---|---|---|---|---|---|
| Q1 2024 | May 9, 2024 | −1.6% | −0.6% | not captured | −1.2% | "…consumer spending remained down in a challenging consumer demand environment." |
| Q2 2024 | Aug 8, 2024 | −4.6% | −5.6% | −0.9% | −0.8% | "…as consumers continued to prioritize essential spending in Canadian Tire Retail (CTR)'s most discretionary quarter." |
| Q3 2024 | Nov 7, 2024 | −1.5% | −2.2% | +2.9% | −2.3% | "With customer spending still constrained, Canadians are seeking value…" |
| Q4 2024 | Feb 13, 2025 | +1.1% (retail) | +1.1% | +0.4% | +1.8% | "…observing economic green shoots like improved consumer sentiment and spending" |
| FY2024 | Feb 13, 2025 | −1.7% (excl. Petroleum) | — | — | — | "…reflecting a weaker consumer demand environment." |
| Q1 2025 | May 8, 2025 | +4.7% | +4.7% | +6.3% | +2.2% | "It's clear Canadians are choosing CTC," said Greg Hicks |
| Q2 2025 | Aug 7, 2025 | +5.6% | +6.4% | +3.9% | +1.0% | "In a dynamic consumer environment, customers continued to turn to us…" |
| Q3 2025 | Nov 6, 2025 | +1.8% | +1.2% | +4.2% | +2.5% | "Discretionary sales growth outpaced essential sales for the first time since 2021." |
| Q4 2025 | Feb 18/19, 2026 | +4.2% | +2.7% | +9.5% | +7.2% | "…one of the best holiday seasons in recent memory" |
| FY2025 | Feb 18/19, 2026 | +4.1% | +3.7% | +6.2% | +3.9% | "…a year of strong sales growth and market share gains" |
| **Q1 2026** | May 14, 2026 | **−1.0%** | **−2.3%** | +3.3% | +1.2% | "Canadian consumers remain resilient but selective, clearly prioritizing value, but not at the expense of quality products and shopping experiences." |
| **Q2 2026** | Aug 13, 2026 | **+0.7%** | **−0.8%** | +8.0% | +4.2% | "In Q2, we demonstrated our operational agility by lowering prices for value-seeking customers, adapting to challenging weather conditions, and ultimately delivering strong financial results." |

### 3.2 Q2 2026 detail (S3, verbatim)
- "CTR Comparable sales were down 0.8% and up 5.5% on a two-year stack basis. Automotive sales grew for the 24th consecutive quarter, partly offsetting weather-impacted categories across other divisions. eCommerce sales grew 14%, outpacing growth in Retail sales."
- "Retail sales were $5,391.6 million, up 4.5%, compared to the second quarter of 2025. Retail sales, excluding Petroleum were up 2.5%."
- "Loyalty sales were up 3.1%, continuing to outpace non-loyalty sales, as members active in the program grew. CTC extended its Triangle Rewards member benefits to include free ship-to-home on CTR eCommerce orders."
- Normalized diluted EPS was $3.94 (+10.4%). Dividend: $1.80 a share, payable Dec 1, 2026.
- On the call, CFO Darren Myers said: "World Cup sales accounted for roughly half of the growth, with Montreal Canadiens fan wear sales also contributing." (Global, S11)
- Consumer demand on the call: Hicks said "consumer sentiment remained soft" and "For a long while now, consumers have been living with the threat of trade wars and tariffs and managing the day-to-day pressure of higher food and gas prices." (Global, S11)

### 3.3 FY2025 (S2, verbatim)
- "Retail sales were $18,986.9 million, up $809.2 million, or 4.5% over the prior year."
- "Consolidated comparable sales were up 4.1%, with strong performance across all major banners; CTR was up 3.7%, SportChek was up 6.2% and Mark's was up 3.9% on a comparable 52-week basis."
- "Automotive was up for the 22nd consecutive quarter, with Automotive Service reaching record annual sales of $1 billion in Q4."
- "Triangle Rewards came to life for more Canadians. 9.8 million are now active registered members of the program, representing a 6% increase on 2024." (Compare the AIF's "12.2 million active members"; see U13.)
- "…a new AI tool (DaiVID) that optimizes pricing and margin, provided customer value and contributed to growth."
- FY2024 (Feb 13, 2025): "Canadians redeemed $360 million of eCTM in 2024, up 7%." "Loyalty sales penetration represented 54.4% of full-year retail sales on a direct scan basis."

OUR NOTES
- CTR comparable sales were negative in **both** reported 2026 quarters (Q1 −2.3%, Q2 −0.8%). The last time before that was **Q3 2024** (−2.2%). CTC attributes 2026 to weather and seasonal categories, not to customer defection. **Say "down", not "Canadians leaving".**
- SportChek Q2 2026 comparable sales were +8.0%. The CFO's "roughly half" means about 4 points came from World Cup sales (approximate).
- Every comparable figure is CTC's own non-GAAP measure. Cite it as "Canadian Tire's own figures".

---

## 4. TRUE NORTH, RESTRUCTURING, JOB CUTS, CLOSURES, DIVESTITURES

| Date | Event | Source and label |
|---|---|---|
| Mar 6, 2025 | True North launched: "a new four-year transformative growth strategy… CTC will reorganize from a complex holding company model into a more agile operating company". "CTC expects to invest more than $2 billion over four years starting in 2025; expense savings begin in 2025 with $100 million run rate expected to start in 2026" | S5, company statement |
| Mar 6, 2025 | "The Company will close 17 uncompetitive standalone Atmosphere stores, with 14 sites to be co-located within SportChek stores." AIF: "all 17 Atmosphere corporate stores which were closed in connection with the Company's True North strategy." | S5, S1, company statement |
| Mar 6, 2025 | "One-time charges of approximately $85 million in transformation and restructuring costs, including severance, as well as closure costs for Atmosphere stores." | S5, company statement |
| Jul 29, 2025 | CTC statement to CTV: "Changes are underway and we are altering various processes and teams to transform and modernize… As a result, some corporate roles are expanding and others are being eliminated." CTV: "The company would not say how many people or positions had been cut." | S8, company statement reported by a named outlet |
| Nov 6, 2025 | "CTC began operating under its newly implemented operating structure at the end of Q3 2025, following the completion of its anticipated restructuring" | S4b, company statement |
| Feb 2026 | "With the True North restructuring completed in the third quarter of 2025, the Company is now benefiting from the associated run-rate savings, with approximately $30 million of savings reflected in operating expense in the fourth quarter of 2025." | S2, company statement |
| Feb 19, 2025 | Helly Hansen sale to Kontoor Brands agreed, "total gross proceeds of $1,276 million". Hicks: "As our strategy becomes more singularly focused on great Canadian retail, it is time to pass this iconic brand into global hands." CTC "expects to continue to sell Helly Hansen products in its banners under a multi-year supply agreement" | S6, company statement |
| Jun 2, 2025 | "…successfully closed the previously-announced sale of the Helly Hansen business to Kontoor Brands, Inc." | S7, company statement |
| 2025 | HBC IP bought "for approximately $30 million" (AIF), including HBC Stripes, Hudson's Bay Company and The Bay marks | S1, S12, company filing |
| Nov 2023 (context) | "In November 2023, the Company implemented targeted headcount reductions, reducing 3% of its full-time equivalent employees and eliminating the majority of its vacancies resulting in a further 3% reduction…" | S1, company filing |
| 2024 | Brampton industrial property sold for $258M. Financial Services review ended with CTC keeping 100% of the Bank | S1, S19 |
| **2019, not 2023** | Party City Canada: CTV (Aug 8, 2019), "Canadian Tire buys up Party City Canada for $174.4 million". Party City Holdco (SEC 8-K, Q2 2019) refers to "their acquisition of our retail stores in Canada" | S31, S32. Completion date Oct 1, 2019 per a law-firm deal note (search result only; see U16) |
| 2025 | Petroleum: "42 gas bars were rebranded from Canadian Tire Gas+ to Petro-Canada in 2025, bringing the total number of rebranded gas bars to 61." Two gas bars closed (ON, NB) | S1 |

OUR NOTE: 17 Atmosphere closures with 14 co-located leaves 3 sites not co-located. That is our arithmetic, and CTC did not state it.

No closure of Canadian Tire, SportChek or Mark's stores was announced under True North in the sources we read. The AIF records SportChek-family franchise closures in 2025: "two Sports Experts stores… and one Atmosphere franchise store in Quebec". Nothing in the record supports a statement like "Canadian Tire is closing stores".

---

## 5. TRIANGLE REWARDS 2024–2026 AND THE TIM HORTONS LINK

### 5.1 Timeline (all tier a releases unless marked; label: company statement)
- **Mar 26, 2024, Petro-Canada linked.** Linked members "earn both CT Money and 20% more Petro-Points with each fuel transaction, convert Petro-Points into CT Money…" [S18]
- **Mar 27, 2025, RBC announced. Jan 13, 2026, RBC launched.** "Eligible RBC cardholders earn 3x Canadian Tire Money on purchases at Canadian Tire, SportChek, Mark's and other participating CTC retailers." Also: "starting later this year, will have the ability to convert Avion points to Canadian Tire Money." [S16]
- **May 8, 2025, WestJet announced. Mar 25, 2026, launched.** "Linked members earn WestJet points on top of Canadian Tire Money on qualifying purchases at participating stores including Canadian Tire, SportChek and Mark's." "Linked members can also convert their WestJet points into Canadian Tire Money." [S17]
- **Sep 15, 2025, Tims announced** ("Launching later in 2026"). **Sep 2, 2026, Tims launched.** [S9b, S9]
- **Q2 2026, free shipping:** "CTC extended its Triangle Rewards member benefits to include free ship-to-home on CTR eCommerce orders." [S3]
- Partner reach, Q2 2026 call (Global's paraphrase): "more than 12 million members of the loyalty program, and two million of them are considered active with at least one loyalty partnership". [S11]
- Earlier counts: "almost 100,000 RBC Avion members and 600,000 Petro-Canada Petro Points members had linked to Triangle" "by early 2026" [S2].

### 5.2 Tims terms, exact (S9, Sep 2, 2026, verbatim)
- "Members of both programs can now link their Tims Rewards and Triangle Rewards accounts to earn up to 5% in Canadian Tire Money on their eligible Tims purchases* in addition to the Tims Rewards points they already earn at participating Tim Hortons restaurants**."
- "Scan for Tims Rewards: Earn 2% on eligible Tim Hortons purchases* (pre-tax)."
- "Scan for Tims Rewards and then pay with a Triangle® credit card: Earn an additional 2% on total Tim Hortons purchases (post-tax)."
- "Use a Triangle credit card as the payment method for Scan & Pay in the Tims app: Earn an additional 1% on eligible Tim Hortons purchases* (pre-tax)."
- "Canadian Tire Money can only be redeemed at Canadian Tire, Party City, SportChek, Mark's, L'Équipeur, Pro Hockey Life, Sports Rousseau, Hockey Experts, Atmosphere, L'Entrepôt du Hockey and participating Sports Experts locations across Canada."
- "Tims Rewards points can only be redeemed at participating Tim Hortons restaurants**."
- "** Not all Tim Hortons locations participate."
- "*Terms and conditions apply. Visit https://www.timhortons.ca/terms-conditions-rewards" (terms page not opened; see U9)
- Link at triangle.com/timsrewards.
- Scale: "more than 12 million Triangle Rewards members, almost 8 million Tims Rewards members"
- Quote: Darryl Jenkins, EVP & Chief Development Officer: "…will give millions of Canadians an easy way to earn Canadian Tire Money on their Tims purchases…"

CP/CP24 (S10, Tara Deschamps, Sep 2, 2026; tier b):
- "customers who link their Triangle and Tims Rewards accounts will earn between two and five per cent in Canadian Tire money in addition to Tims points on select Tims purchases."
- "Right now, 53 per cent of Triangle Rewards customers are enrolled in both loyalty programs."
- Critic, named (Liza Amlani, Retail Strategy Group): "this is less about customer delight and more about two legacy brands scrambling for incremental share in an oversaturated loyalty market." This was given by email when the partnership was teased in Sep 2025.
- Jenkins on timing: "We certainly didn't plan it this way."

OUR NOTE (illustrative arithmetic only, not a price; house rule 5 does not apply because no product price is stated): take a hypothetical $10.00 pre-tax Tims order in a 13% HST province, $11.30 with tax. Scanning earns 2% × $10.00 = $0.20. Paying with a Triangle card adds 2% × $11.30 = $0.226. Using Scan & Pay with a Triangle card adds 1% × $10.00 = $0.10. The maximum is about $0.53 in CT Money, roughly 5.3% of the pre-tax amount, because one 2% leg is on the post-tax total. **Without a Triangle credit card the maximum is 2%.** The "up to 5%" headline therefore depends on holding the Canadian Tire Bank card.

### 5.3 Program terms (WebFetch only; verify before use)
- Base earn: "0.4%" on the pre-tax amount for members (S39, WebFetch; also widely reported by third-party sites; see U10).
- Triangle Select (paid tier, launched 2023, AIF): "We can make changes to the program or cancel Triangle Select at any time on 30 days notice." (S39, WebFetch). The AIF describes it as "an annual fee-based subscription program" (S1). The $89 price is from CBC 2023 and third parties, not re-verified (see U11).
- Paper Canadian Tire Money: no dated primary or named-outlet source for its 2024–2026 status was opened (see U12).

### 5.4 The member-count discrepancy (flag on air if numbers are used)
- AIF (Feb 18, 2026): "12.2 million active members".
- FY2025 release (same week): "9.8 million are now active registered members".
- Partner releases: "nearly 12 million" (Sep 2025, Jan 2026); "more than 12 million" (Sep 2026).
- OUR NOTE: these are different definitions ("active" and "active registered"). If a number is needed, say "more than 12 million members, according to Canadian Tire" and avoid the word "active".

---

## 6. CANADIAN TIRE BANK AND THE TRIANGLE MASTERCARD

- AIF (S1): CTB is "a Canadian federally regulated Schedule I bank". "CTB was the seventh largest issuer of credit cards in Canada in 2025 based on outstanding receivables." It has 2.3 million active cardholders.
- Strategic review (S19, Dec 6, 2024): "CTC will retain 100% ownership of the Bank." Also: "CTFS distributes approximately 75% of all eCTM through its relationship with 2.3 million members who carry Triangle credit cards." "Engaged Triangle Rewards members spend more than twice as much as non-members on average."
- True North (S5): "a new retail-focused bank strategy to acquire and engage more Triangle Mastercard holders."
- Q2 2026 (S3): "Financial Services receivables (GAAR) increased 4.2% on continued cardholder engagement." "The use of loyalty offers and promotional events has also increased eCTM issuance at Canadian Tire Bank, supporting Retail sales."
- Funding (S1): CTB entered into a funding commitment with RBC ($300M secured line, $1.2B note purchase facility, to Apr 30, 2028), replacing Scotiabank facilities.
- **Rates and fees (S38, WebFetch only; see U8):** "There is no annual fee with the Triangle Mastercard or Triangle World Elite Mastercard." Purchase rate "21.99%". Earn: "4% CT Money" at CTC stores; gas "5¢ per litre"; groceries 1.5% (Triangle MC) or 3% (World Elite) on the first $12,000 a year. **No rate change or fee change between 2024 and 2026 was found.**
- Historical class action (S41; label: **settlement**, subject to court approval; dates outside the window): Option consommateurs v. Canadian Tire Bank, Quebec, over cash advance fees. The class covered cardholders who paid cash-advance fees "since October 1st, 2001". The approval hearing was set for Sep 7, 2016. A $1.5M figure appears only in a secondary index (canadacommons) and was **not verified** (see U17).
- FCAC: no Commissioner's decision naming Canadian Tire Bank was found. The FCAC decisions index failed to load (empty reply), so this was **not exhaustively checked** (see U18).

---

## 7. REGULATORY, LEGAL AND PRIVACY RECORD

### 7.1 Competition Bureau
- **No Competition Bureau enforcement action against CTC was found.** That includes a consent agreement, a Tribunal application or a court case, in any year searched (canada.ca and competition-bureau.canada.ca searches; Tribunal search). Status: **not found** (see U1). A Bureau search hit lists Canadian Tire only as a *competitor* in the Lowe's/RONA merger review.
- The "2012-era tire pricing / regular price" premise in the brief appears to be a **mix-up with Sears Canada**. The Commissioner's ordinary-selling-price case over **tires** ended in a Tribunal finding against **Sears** (CT-2002-004, decided 2005). **Never attribute this to Canadian Tire.**
- The actual regular-price outcome against Canadian Tire is the **Quebec OPC guilty plea** (§7.2), which is provincial and not a Bureau matter.

### 7.2 Quebec OPC: GUILTY PLEA (Feb 6, 2026)
OPC release (S20, tier a, French, verbatim):
> « L'Office de la protection du consommateur (OPC) annonce que la Société Canadian Tire ltée a plaidé coupable, aujourd'hui à Montréal, à des accusations portées en vertu de la Loi sur la protection du consommateur (LPC). Pour 74 des chefs d'accusation déposés par le Directeur des poursuites criminelles et pénales, la Société devra payer des amendes totalisant 1 287 550 $ avec les frais. »
> « L'Office reprochait à Canadian Tire d'avoir contrevenu à l'article 225 b) de la LPC, qui interdit au commerçant d'indiquer faussement un prix courant ou un autre prix de référence pour la vente d'un bien. Sur une période de 6 mois, soit d'avril à octobre 2021, l'Office a vérifié les prix de 7 produits ciblés dans les circulaires de Canadian Tire, sur son site web ainsi que dans 3 succursales de la grande région de Montréal. »
> « …l'analyse des données de vente a démontré que les produits n'étaient vendus au prix courant que dans une très faible proportion des cas. L'enquête a aussi établi qu'en magasin, les produits n'ont pratiquement jamais été affichés au prix courant pendant la période de vérification. »
> « Canadian Tire a reconnu sa culpabilité pour 5 des produits faisant l'objet de l'enquête, soit des ensembles de couteaux Henckels et Cuisinart, des batteries de cuisine Lagostina et Heritage et une perceuse sans fil Dewalt. »

Our working English (not an official translation): Canadian Tire pleaded guilty in Montreal to charges under Quebec's Consumer Protection Act. For 74 counts it must pay fines totalling $1,287,550 including costs. The OPC alleged breaches of s. 225 b), which prohibits a merchant from falsely stating a regular or other reference price. Over April–October 2021 the OPC checked 7 products in flyers, online and at 3 Montreal-area stores. Sales data showed the products sold at the regular price in only a very small proportion of cases. Canadian Tire acknowledged guilt for 5 of the products.

CBC/CP (S21, Pierre Saint-Arnaud, Feb 7, 2026, tier b):
- "Canadian Tire has been ordered to pay just under $1.3 million after pleading guilty to 74 counts of violating sections of Quebec's Consumer Protection Act, related to false advertising."
- "Crown prosecutor Jérôme Dussault says the Canadian retail giant agreed to the settlement after initially pleading not guilty."
- "Quebec court Judge Simon Lavoie approved the agreement, which includes fines and fees ranging from $15,625 to $18,150 per count."
- **Company statement, verbatim (CBC and Global):** "The OPC charges relate to five products over a six-month period five years ago. Importantly, no customers were overcharged and the matter is now concluded."

LABEL: **guilty plea** (the court approved a plea agreement). The CBC photo caption says "admitted to violating… 74 times", so "admission" also fits. **Do not call it a "settlement"** on air without saying it was a guilty plea, even though the prosecutor used that word.
OUR NOTE: $1,287,550 ÷ 74 counts = about $17,399 per count, which falls inside CP's reported $15,625–$18,150 range.
Do not say: "fake sales are still happening", "still on sale". S45 (Peter Nowak's newsletter) claims similar high-low pricing in a Feb 2026 Repentigny flyer. That is a tier-c lead with an implied ongoing breach, so **do not use**.

### 7.3 BC Privacy Commissioner: FINDING (Apr 20, 2023; outside 2024–26, but the only privacy regulator finding located)
OIPC BC release (S24, tier a, verbatim):
- Headline: "Investigation finds Canadian Tire Associate Dealers not authorized to use facial recognition technology"
- "Four BC Canadian Tire stores using facial recognition technology (FRT) to collect customer's biometric information between 2018 and 2021 contravened the Personal Information Protection Act (PIPA)."
- "…the stores did not properly notify people entering the store that FRT was in use, failed to demonstrate a reasonable purpose for using FRT, and did not obtain consent…"
- "…learned that 12 locations were using the technology… All 12 stores confirmed that they removed their FRT systems after the investigation began."
- Commissioner Michael McEvoy: "Retailers, like the ones in this case, would have to present a highly compelling case to demonstrate such collection would be reasonable… The stores failed to do so in this case."
- CBC/CP (S25): "The stores will not face sanctions because there are no penalty provisions under the act". Company statement: "…the corporation and the dealers have mutually agreed to prohibit the use of facial recognition technology in Canadian Tire stores."

LABEL: **finding** against four Dealer-operated stores, not against CTC corporate.

### 7.4 E-commerce data breach (Oct 2025): COMPANY STATEMENT, plus a PROPOSED CLASS ACTION
CTC advisory (S26, Oct 14, 2025, verbatim):
- "On October 2, 2025, Canadian Tire Corporation… identified a data breach involving customer information in an e-commerce database. The unauthorized activity was limited to that database, which did not include Canadian Tire Bank information or Triangle Rewards loyalty data."
- "The database contained basic personal information for customers who have an e-commerce account with one or more of Canadian Tire, SportChek, Mark's/L'Équipeur and Party City. This included name, address, email, and year of birth. It also included encrypted passwords and, in some cases, truncated (i.e. incomplete) credit card numbers, none of which can be used for account access, transactions or purchases."
- "In the case of fewer than 150,000 accounts, the data included date of birth… CTC has reported this matter to applicable privacy regulators."
- Global/CP (S27): credit monitoring is offered "from TransUnion Canada".

Have I Been Pwned (S28, added Feb 25, 2026): "PwnCount": 38,306,562. It describes "almost 42M records… 38M unique email addresses along with names, phone numbers and physical addresses", with data classes including "Genders" and "Phone numbers". **This is HIBP's description, not CTC's.** CTC's advisory lists neither phone numbers nor gender.

Proposed class action (S29, Jul 24, 2026; label: **proposed class action, allegations only, not certified**):
- "…have commenced a proposed class action on behalf of all persons whose personal information was affected…"
- "The proposed class action alleges that despite its history of being involved in customer data breaches, Canadian Tire failed to implement proper safeguards…"
- The release says Canadian Tire was "reporting that the breach had affected over 40 million customer records". **We found no CTC statement giving that number** (see U5).
- The court is not named in the release. A secondary search summary said the Supreme Court of British Columbia (unverified; see U6).

Federal Privacy Commissioner: no announced investigation or finding on this breach was located (see U7).

### 7.5 Other matters searched with no result in 2024–2026
- Competition Bureau (see 7.1); FCAC (see §6). No certified class action against CTC was found in 2024–2026.

---

## 8. PRICING STATEMENTS AND CONTROVERSIES (named outlets and company)

- **DaiVID and AI pricing (S11, Global, Aug 13, 2026):**
  - Hicks: "We kept our value proposition sharp using our DaiVID AI analysis to drop prices on more than 5,000 products, and we saw strong customer response to lower prices on essentials like cleaning and storage."
  - COO TJ Flood: "Most of our price changes are deliberate to try to provide value where we think Canadians want value, and our elasticity curves point us in those directions… There are at times, we do have to watch competitive activity and react based on what the competition does."
  - Company statement to Global: "We do not use DaiVID for algorithmic pricing or real-time dynamic pricing. It is a longer-term pricing tool. Price changes are reviewed, planned, and scheduled through our established pricing processes."
  - Global's own line: "the company did not specify if the same AI tools could be used to strategize when to raise prices."
  - LABEL: company statement. **Never** imply surveillance or personalised pricing.
- Price ceiling and Dealer discretion: §2 (AIF; pricing page).
- Regular-price guilty plea: §7.2.
- OUR NOTE: CTC does publish the "Regular prices shown…" definition on its pricing page (S30). That is the company's own standard, and it is what the OPC case tested in Quebec for 2021.

---

## 9. STORE-FLOOR ISSUES: THEFT MEASURES, RECEIPT CHECKS, SELF-CHECKOUT

- **CBC, Sophia Harris, Jul 10, 2023 (S33; outside the window, context):** a Toronto shopper, Brian Simpson, "says after paying for his items at a self-checkout, a security guard blocked him from exiting and demanded to see his receipt." A Burnaby shopper "says she's now boycotting the store." Company statement (CBC paraphrase): checks "are left up to the discretion of individual store owners" and are used "for 'inventory control.'" Also: "Despite the backlash, Canadian Tire, Loblaw and Walmart gave no indication that they're reconsidering the practice."
- **CBC, Sophia Harris, Apr 30, 2024 (S34):** "At least six Canadian Tire locations in Ontario have also scrapped self-checkout. Two of the stores' franchise owners, one in North Bay and one in Toronto, told CBC News they made the move because they felt it improved customer service."
- **CBC, Sophia Harris, date on page May 16, 2024; verify (S35):** "Major retailers like Canadian Tire and Walmart have implemented some of the measures; Loblaw has incorporated all of them." The measures named are wheel-locking carts, metal gates, random receipt checks and plexiglass barriers. **The article does not say which measures Canadian Tire uses** (see U19).
- No 2025–2026 named-outlet story on locked cases at Canadian Tire was located.

---

## 10. AUTO SERVICE

- Scale (S1): "Canadian Tire stores house over 5,600 automotive service bays, and substantially all Canadian Tire stores also provide a variety of automotive services." Roadside assistance covers "over 207,000 members".
- Revenue (S2): "Automotive Service reaching record annual sales of $1 billion in Q4" (2025). Automotive retail sales have grown for 24 consecutive quarters (Q2 2026, S3).
- **CBC Marketplace:** **no Marketplace investigation of Canadian Tire auto service was found.** The 2018 Marketplace oil-change story (David Common, Mar 9, 2018) covered **dealerships**. The older "oil-change shop caught" story was about **Economy Lube**. Do not attribute either to Canadian Tire (see U20).
- **CBC News, Kathy Tomlinson, Nov 30, 2010 (S37; outside the window):** a North Vancouver customer alleged an attempt to sell a "$400 repair — on an inexplicable loose wheel bearing". Company spokesman Duncan Fulton called the story's allegations "untrue, incorrect and extremely damaging to our brand", then said "we believe our customer did not receive the level of customer service excellence we aim to provide". LABEL: **allegation** by the customer, denied in part by the company. Too old and too thin for on-air use.
- **CBC Go Public, Rosa Marchitelli, Oct 20, 2025 (S36): DO NOT USE ON AIR (vehicle-safety claim, house rule 1).** It covers a Clarenville, N.L. customer's account of zip ties on an engine splash shield. It is recorded only so the producer knows it exists and is the most-cited recent Canadian Tire auto story.
- **The useful rule for "How to protect yourself" (S40, Ontario.ca, updated Aug 19, 2025, tier a; Ontario only):**
  - Required invoice and estimate wording: "The Consumer Protection Act, 2002, provides you with rights in relation to having a motor vehicle repaired. Among other things, you have a right to a written estimate. A repairer may not charge an amount that is more than ten (10) per cent above that estimate. If you waived your right to an estimate, the repairer must have your authorization of the maximum amount that you will pay for the repairs… In either case, the repairer may not charge for any work you did not authorize."
  - The required shop sign must tell customers about "any commissions repairers receive for selling parts and how the commission is calculated".
  - OUR NOTE: this is **Ontario law only**. Other provinces differ and were not checked (see U21). The "$100 threshold" in the Broken Canada video **does not appear** on this page.

---

## 11. TARIFFS AND "BUY CANADIAN" STATEMENTS (company statements via named outlets)

- **Feb 13, 2025 (S13 Global/CP; S14 Yahoo):**
  - Hicks: "I suspect the consumer confidence uptick that I mentioned earlier has now been substantially erased with tariff talk."
  - Hicks: "We have already begun to try to insulate our customers from the risk of higher trade costs hitting our shelves… We are reviewing products and U.S. suppliers and assessing alternatives to the inevitable inflationary pressure these tariffs would deliver."
  - CP: "Canadian Tire purchases about 15 per cent of its goods from the U.S." and "could find Canadian suppliers for between 25 and 30 per cent of the items it gets from the U.S."
  - Hicks: "If you think about anything that kind of goes into a bag or a bottle, it's likely that is a Canadian supplier."
- **May 8, 2025 (S15 BNN/CP):**
  - Hicks: "Despite low confidence levels, customers have been and remain more resilient than we anticipated."
  - CP: "About 15 per cent of the money Canadian Tire spends on acquiring or manufacturing products is tied to the U.S. and only a 'manageable fraction of that is currently affected.'"
  - CP on mitigation: a "tariff task force" that "has been seeking alternatives to U.S. goods, negotiating with vendors and managing margins to blunt the risk of price inflation for customers."
- **Aug 13, 2026 (S11):** "consumer sentiment remained soft" (Hicks, quoted in §3.2).
- **AIF risk factors (S1):** "adverse geopolitical conditions, including trade restrictions, quotas, tariffs and other import-related taxes…"
- No CTC "Made in Canada" or maple-leaf shelf-labelling program was found in a CTC release or named outlet (see U22). **Do not claim one, or its absence.**
- OUR NOTE: "15% of goods from the U.S." (Hicks) and "about 50% of CTR inventory purchases sourced directly from vendors outside Canada" (AIF) use **different bases**. Do not add or subtract them.

---

## 12. COMPETITOR VIDEOS: CLAIMS AND THEIR STATUS
Tags: **V** = verifiable and checked; **V?** = verifiable in principle but not checked or not supported; **O** = outlet-reported; **U** = unsourced.

### 12.1 Broken Canada, r5DkjCpiSWo, "Canadian Tire and 9 Other Auto Repair Chains Just Got Caught — Something Felt Wrong" (Sep 27, 2026; 75,005 views)
The structure is an auto-repair industry piece. Canadian Tire takes about a 3-minute chapter, the rest covers "the other nine", a nine-item "bait repairs" list and "five rules".

| # | Claim (paraphrase, with the transcript quote where useful) | Tag | Our check |
|---|---|---|---|
| B1 | "Canadian Tire operates over 500 auto service locations across Canada." | V (approx.) | AIF: 502 stores, "substantially all" offer auto services. Sayable as "around 500 stores, nearly all with service bays" |
| B2 | "It is the single largest automotive service chain in the country." | U | Not stated by CTC. Avoid |
| B3 | Training, inspection sheets, adviser pay and "upsell targets are all corporate" | U | No source. The AIF says CTC gives "operational support". Do not use |
| B4 | BBB files hold "thousands of complaints" on CT auto service | U | Not checked. BBB complaints are not findings |
| B5 | Corporate response "almost always… Individual franchise responsibility" | O (one instance) | Go Public 2025 shows head office citing independently owned locations in one case. A pattern is unsourced |
| B6 | "continuing to collect franchise fees" | U | The AIF does not describe Dealer fees in those terms. Avoid |
| B7 | Jiffy Lube BC/ON investigations with "findings… services billed… never performed" | U | Not CT. Unchecked |
| B8 | Midas quotes varying "400%" | U | Not CT |
| B9 | Mr. Transmission complaint rate "among the highest… according to provincial consumer protection data" | U | Not CT |
| B10 | Pep Boys "entered the Canadian market" | U (likely wrong) | Not checked. Not CT |
| B11 | "1998 CBC Marketplace investigation into transmission shops" | V? | Not located. Not CT |
| B12 | Ontario ministry "published consumer guidance explicitly warning about the multi-point inspection upsell pattern" | V? | Not found on the Ontario guide page we read |
| B13 | "In Ontario, [a written estimate] is actually the law for repairs over $100." | V? (partly wrong) | Ontario gives a right to a written estimate and a 10% cap (S40). No $100 threshold on that page |
| B14 | US studies show women are quoted more | U | No study named |
| B15 | Modern fuel detergents make fuel-system cleaning unnecessary; most post-2012 cars have electric power steering | U, **product/technical** | House rule 2. Do not use |
| B16 | Cabin filter "$8 to 12" vs "$65 to $90 installed" | U | Prices without retailer, date or store (house rule 5). Do not use |
| B17 | Oil change "$63" becoming "$840" or "$312" | U | Hypothetical. Do not use |

### 12.2 Canadian Rant, GGMQoWEGjbU, "Canadians Have Had Enough of Canadian Tire" (Jun 19, 2026; 21,636 views)
The structure is a compilation of short-form social clips with a narrator bridge. Every customer claim is **U** (anonymous social video, tier c).

| # | Claim | Tag | Note |
|---|---|---|---|
| R1 | "more and more customers are speaking out about poor customer service…" | U | No data |
| R2 | Bathroom garbage cans "$50… cheapest… $24" | U | No store or date. House rule 5 |
| R3 | Calgary stores won't sell a rim and tire for take-away mounting "as of this year… They just said that's the policy" | U | Could be checked with CTC. Not checked |
| R4 | Store-brand tent "water resistant at 600" vs Walmart "1,200"; tent falling apart | U, **product quality** | House rule 2. Do not use |
| R5 | "Canadian Tire is selling refurbished vacuums" | U, **implies wrongdoing** | House rule 4. Do not use |
| R6 | Battery replaced for "$450" when the key fob battery was the fault; "$10 to take your battery back" | U | Single anecdote |
| R7 | Wheel-bearing job followed by a "$2600" list of recommended repairs, which another mechanic said were not needed | U | Single anecdote. **Allegation** at most |
| R8 | Receipt check at the exit after a return | U | Echoes CBC 2023 (S33), which is the usable source |
| R9 | Propane tank leaking in the car | U, **safety** | House rule 1. DO NOT USE |
| R10 | Mark's cashier service complaint | U | Anecdote |
| R11 | Online tire appointment, no stock authorization | U | Anecdote |
| R12 | Positive clip (US visitor: "very cool store") and a "shout out" to an associate | U | Could be used as a balance note, but it is unsourced |

OUR NOTE: neither video cites the OPC guilty plea, the BC facial recognition finding, the 2025 data breach or CTR's negative 2026 comparable sales. Those four are the record-backed differentiators for our video.

---

## 13. WHAT THE RECORD SUPPORTS AS "THINGS CANADIAN TIRE GETS RIGHT" (company statements and record facts only)
- Prices were lowered on more than 5,000 products, per Hicks on the Q2 2026 call. Label: company statement; it is not our test. [S11]
- Free ship-to-home on CTR online orders for Triangle members (Q2 2026). [S3]
- Facial recognition was removed at all 12 BC stores, and CTC and its Dealers "mutually agreed to prohibit" it. [S24, S25]
- The Dealer price ceiling: Dealers can't charge above CTC's set price, and "may sell for less". [S1, S30]
- The data-breach notice was public within 12 days, with credit monitoring for the date-of-birth subset. These are company statements. [S26, S27]

---

## 14. UNVERIFIED / DO-NOT-USE (mandatory)

| # | Item | Why unverified or barred | Action |
|---|---|---|---|
| U1 | Any Competition Bureau action against CTC (the brief's "2012-era tire pricing / regular price" case) | Not found in Bureau, canada.ca or Tribunal searches. The known tire OSP case is **Sears Canada (2005)** | Do not say the Bureau ever acted against CTC. Do not attribute the Sears case |
| U2 | 2024–2026 Competition Bureau matter involving CTC | None found. The canada.ca news search failed with an HTTP/2 error | Do not mention |
| U3 | Federal or other privacy findings on Triangle Rewards or Canadian Tire Bank | None found | Do not mention |
| U4 | Alberta OIPC P2005-IR-007 (a Calgary store recording driver's licence numbers on returns) | Search snippet only, not opened. Dated 2005 | Do not use |
| U5 | "Over 40 million customer records" attributed to Canadian Tire | Appears only in the plaintiff counsel's release. CTC's statements give no total | Do not attribute to CTC. If used, say "Have I Been Pwned lists about 38.3 million email addresses" and label it HIBP |
| U6 | Court where the breach class action was filed (BC Supreme Court?) | Secondary summary only | Say "a proposed class action, not certified" with no court |
| U7 | Any federal Privacy Commissioner investigation of the 2025 breach | Not found. CTC says only that it "reported this matter to applicable privacy regulators" | Do not claim an investigation |
| U8 | Triangle Mastercard 21.99%, no annual fee, earn rates | WebFetch only; the ctfs.com product page returned 404 to curl | Screenshot canadiantire.ca/mastercard before any on-screen use |
| U9 | Tims Rewards terms (timhortons.ca/terms-conditions-rewards) | Not opened | Read before quoting exclusions or caps |
| U10 | Triangle base earn of 0.4% | WebFetch of the legal page (403 to curl) plus third-party sites | Screenshot first |
| U11 | Triangle Select price ($89) and benefits | 2023 CBC and third parties. Current price not checked | Do not quote a price |
| U12 | Paper Canadian Tire Money status (issuance ended 2020; still redeemable) | Wikipedia and secondary only. No dated CTC or named-outlet source opened | Do not state |
| U13 | Triangle "active" member count | AIF says 12.2M "active"; the FY2025 release says 9.8M "active registered" | Say "more than 12 million members, according to Canadian Tire" |
| U14 | PartSource store count (82 in text vs 81 in table) | Internal AIF discrepancy | Avoid the number |
| U15 | Q1 2024 SportChek comparable sales | Not captured | Not needed |
| U16 | Party City Canada completion date of Oct 1, 2019 | Law-firm and search summary only | Say "2019" |
| U17 | $1.5M Canadian Tire Bank cash-advance settlement (Option consommateurs) | Secondary index only. Approval not confirmed | Do not use the amount. Too old |
| U18 | FCAC decisions naming Canadian Tire Bank | Index page failed to load | Do not claim "no violations" |
| U19 | Which anti-theft measures (locked carts, gates, plexiglass) Canadian Tire stores use, and the CBC article date | CBC says "some of the measures", unspecified. Date ambiguous on page | Don't name a measure for CT |
| U20 | Any CBC Marketplace or W5 investigation of Canadian Tire auto service | Not found. The W5 Calgary spark-plug story was in a search snippet only (undated, not opened) | Do not mention |
| U21 | Written-estimate rules outside Ontario | Not checked | Say "in Ontario" only |
| U22 | A CTC "Made in Canada" / maple-leaf shelf-label program | Not found | Don't claim it exists or doesn't |
| U23 | CTC-specific dynamic or surveillance pricing | No evidence. CTC denies algorithmic or real-time pricing (S11) | Never imply |
| U24 | Peter Nowak / Do Not Pass Go claim that "high-low" pricing continued after the plea (Repentigny flyer) | Tier c newsletter; implies ongoing wrongdoing | Do not use |
| U25 | Channel names "Broken Canada" and "Canadian Rant" for S43 and S44 | Taken from the brief; the API didn't return the channel | Confirm on YouTube before naming on screen |
| U26 | All Broken Canada and Canadian Rant claims tagged U or V? in §12 | Unsourced or unchecked | Do not repeat |
| U27 | CBC Go Public zip-tie story (S36) and the Canadian Rant propane clip (R9) | Vehicle and product safety (house rule 1) | DO NOT USE ON AIR |
| U28 | Global News's paraphrase "two million of them are considered active with at least one loyalty partnership" | Outlet paraphrase of a call remark; transcript not opened | Attribute to Global if used |
| U29 | Quotes captured only by WebFetch (S30 online-price line, S38, S39, S42) | Summariser; not guaranteed verbatim | Screenshot in a browser first |
| U30 | CBC 2023 "$89 a year" Triangle Select story | Search snippet only | Not used |

Count of unverified / do-not-use items: **30**.

---

## APPENDIX R — RECALLS / PRODUCT SAFETY — DO NOT USE ON AIR
No recall material was researched, by design. The only safety-adjacent items met in passing are U27 (the Go Public zip-tie service story and the Canadian Rant propane clip). Both are barred on air.

---

# Canadian Tire: policies and prices dossier

**Prepared:** 4 Oct 2026 (UTC, roughly 14:15–14:45) for Canadian Counter. The video airs 6 Oct 2026: "Why Some Canadians Are Refusing to Shop At Canadian Tire Anymore".
**Scope:** the rules, policies and prices a Canadian Tire shopper meets, from primary sources where possible.
**Opened:** every source was opened on **4 Oct 2026** unless its row says otherwise.
**Raw captures:** everything is saved under `scratchpad/ct/` (paths below are relative to it).
**Tiers:** (a) primary; (b) named outlet with byline and date; (c) do not use; (d) named survey.

House rules applied throughout. There are no health, safety or recall claims (recalls appear only in Appendix R, marked DO NOT USE ON AIR). There are no product-quality claims. Corporate claims are quoted verbatim and attributed. Nothing here states or implies wrongdoing or motive. No U.S. figures are presented as Canadian. No supplier or manufacturer is inferred. We never say we tested, bought or visited anything.

---

## 0. HOW THE PRICES WERE CAPTURED (read first)

- **canadiantire.ca pages.** A bare `curl` gets **HTTP 403** from Akamai ("Access Denied", ref. 18.8dbd7768…). With a full browser header set (sec-ch-ua, sec-fetch-*, Accept-Language), the pages return 200. Script: `ctget.sh`.
- **The site's own API (`apim.canadiantire.ca`)** returned 200 when sent the same headers the site's JavaScript sends. Those are the public `Ocp-Apim-Subscription-Key` embedded in every product page, `baseSiteId: CTR`, `service-client: ctr/web`, and Origin/Referer canadiantire.ca. Script: `apim.sh`. Endpoints used:
  - `/v1/product/api/v2/product/sku/PriceAvailability?storeId=…&sku=…` (GET) returns the per-store current price, "originalPrice", `isOnSale`, `displayWasLabel`, **`priceValidUntil`** (the sale end), eco fee and stock. The POST form of this endpoint returned **403**; the GET form works.
  - `/v1/product/api/v1/product-families/{code}` returns name, specs, model number and warranty message.
  - `/v1/product/api/v1/product-families/{code}/pricing` returns the price, eco-fee text and the Triangle benefit rates.
  - `/v1/store/v2/stores?latitude=&longitude=&maxCount=` (store search) and `/v1/store/store/{id}` (store detail).
- **triangle.canadiantire.ca** returned **403** to curl even with browser headers. Its pages were read through WebFetch, which returns a model-extracted summary, not raw HTML. **Quotes from triangle.canadiantire.ca are therefore marked "WebFetch extract".** Screenshot them before air. Where the same text exists in a raw primary file (the Triangle T&C PDF on media.ctfs.com, or canadiantire.ca pages), that file is quoted instead.
- **Competitors:**
  - **Home Depot Canada** worked through its own JSON API (`/api/search/v1/search`, `/api/productsvc/v1/products/{id}/store/{store}`).
  - **Amazon.ca** product pages fetched with browser headers.
  - **Princess Auto** through its site-search provider endpoint (`ac.cnstrc.com`, the index key embedded in princessauto.com). That gives one national online list/sale price, not a store price.
  - **Walmart.ca is BLOCKED.** It redirected to `/blocked?...` with the page "Verify Your Identity" / "We like real shoppers, not robots!" (curl at 14:2x UTC and WebFetch), so **no Walmart prices were captured**.
- **Capture timestamps (UTC, 4 Oct 2026):**
  - CT basket 14:24:26–14:24:31; the extra DeWalt SKUs about 14:29.
  - HD 14:30:40 and 14:31:21.
  - Amazon about 14:27–14:31.
  - Princess Auto about 14:29.

---

## VERDICT (one paragraph)

The record supports a strong, safe "rules you should know" video, built almost entirely on Canadian Tire's own words and data.

**Strongest primary items:**
1. **No price-match policy appears** anywhere in CT's current policy set. Its Pricing Policy says "Canadian Tire Associate Dealers may sell for less" and Dealers have "no obligation… to match online prices until the sale begins in their region".
2. CTC's **AIF says Dealers sell "at prices not exceeding those set by the Company"**.
3. **Refund Cards expire one year after issue** (except in Saskatchewan). Gift cards do not expire.
4. **e-CT Money can expire after 18 months of inactivity.** Base earn is **0.4%**, which is $4 per $1,000 pre-tax, confirmed in CT's own API field `tsRewardsBaseLoyalty: 0.004`.
5. **Triangle Select costs $89 a year, is non-refundable outside Quebec and auto-renews** (except in Quebec, and in Alberta unless chosen).
6. **Paper CT Money issuance ceased on 21 March 2020.** It is still redeemable at Canadian Tire stores only.
7. **Online tires and wheels can't be paid for with CT Money.**
8. **Quebec's OPC: CT pleaded guilty on 6 Feb 2026 to 74 counts** of falsely indicating a regular/reference price, with fines totalling $1,287,550. The OPC checked 7 products in April–October 2021, and CT admitted 5 of them. That is a **guilty plea** under Quebec's Consumer Protection Act, *not* a Competition Act case. No Competition Bureau ordinary-price case against CTC was found.
9. **Same SKU, same day, different "regular" prices by region.** WD-40 325 g is $12.99 regular in Toronto and Calgary, $11.99 in Halifax and Vancouver. Rubbermaid 68 L is $17.99 vs $19.99. Sale end dates also differ by region (Oct 7 vs Oct 8).
10. **DeWalt kits.** CT's sale prices on two DeWalt kits were within $2 of Home Depot's and Amazon.ca's everyday price for the same model numbers. Example: DCK277D2 at CT was $199.99 "Save 33%" from $299.99; at HD and Amazon.ca it was $198.00.
11. **Quebec's new legal good-working-order warranty takes effect 5 Oct 2026**, the day before air.

**Weak spots:**
- Walmart is blocked.
- CT publishes no auto-service labour rates or menu prices online.
- No general "Product Protection Plan" for merchandise was found on canadiantire.ca. Only the priced **Tire Care Guarantee with Replacement Advantage** ($9.99–$24.99 per tire) and per-product exchange warranties appear.
- The Triangle pages are WebFetch extracts.

---

## SOURCE REGISTER

| ID | Source | Date on source | Tier | URL | Opened / method / raw file |
|---|---|---|---|---|---|
| P1 | Canadian Tire, Policies page (Returns, Pricing, Resale, Auto Service T&C, Paper CT Money, Gift Card and Refund Card T&C) | none shown; © 2026 | a | https://www.canadiantire.ca/en/customer-service/policies.html | 4 Oct, curl+browser headers; `customer-service_policies.html/.txt` |
| P2 | Canadian Tire, Returns page | none shown | a | https://www.canadiantire.ca/en/customer-service/returns.html | 4 Oct; `customer-service_returns.html/.txt` |
| P3 | Canadian Tire, Online Ordering / Ship to Home FAQ (ship-to-home.html redirects here) | none shown | a | https://www.canadiantire.ca/en/customer-service/online-ordering.html | 4 Oct; `customer-service_online-ordering.*` |
| P4 | Canadian Tire, Customer Support FAQ | none shown | a | https://www.canadiantire.ca/en/customer-service.html | 4 Oct; `customer-service.*` |
| P5 | Canadian Tire, Triangle Support FAQ (on canadiantire.ca) | none shown | a | https://www.canadiantire.ca/en/customer-service/my-canadian-tire.html | 4 Oct; `myct.*` |
| P6 | Canadian Tire, Tires Warranty (Tire Care Guarantee) | none shown | a | https://www.canadiantire.ca/en/customer-service/tires-warranty.html | 4 Oct; `tirewarranty.*` |
| P7 | Canadian Tire, Quebec Right to Repair and Warranty | none shown | a | https://www.canadiantire.ca/en/customer-service/quebec-right-to-repair.html | 4 Oct; `customer-service_quebec-right-to-repair.*` |
| P8 | Canadian Tire, Auto Service pages (main, tires, oil change, brakes) | none shown | a | https://www.canadiantire.ca/en/auto-service.html (+ /auto-service/tires.html, /oil-change.html, /brakes.html) | 4 Oct; `auto*.html/.txt` |
| P9 | Canadian Tire, site-wide legal footer (on every page) | © 2026 | a | e.g. policies.html footer | 4 Oct; same files |
| P10 | Canadian Tire, price-match URL test | n/a | a (absence) | https://www.canadiantire.ca/en/customer-service/price-match.html | 4 Oct; **HTTP 404**; `pm.html` |
| T1 | Triangle Rewards Program T&C (PDF on Canadian Tire Financial Services media server) | PDF metadata: created 12 Jun 2019, modified 30 Nov 2023 | a (may not be the latest version) | https://media.ctfs.com/documents/Triangle_Rewards_Terms_Conditions_EN_V2.pdf | 4 Oct, curl; `tri_tc.pdf/.txt` |
| T2 | Triangle Rewards program rules page | "Information effective as of March 26, 2025" (credit card section) | a, **WebFetch extract** | https://triangle.canadiantire.ca/en/support/legal-and-privacy/program-rules.html | 4 Oct, WebFetch (curl 403) |
| T3 | Triangle Select landing page | none | a, **WebFetch extract** | https://triangle.canadiantire.ca/en/triangle-select.html | 4 Oct, WebFetch |
| T4 | Triangle Select T&C | none found | a, **WebFetch extract** | https://triangle.canadiantire.ca/en/support/legal-and-privacy/triangle-select-terms-and-conditions.html | 4 Oct, WebFetch |
| T5 | Triangle "Collecting and Redeeming" FAQ | none | a, **WebFetch extract** | https://triangle.canadiantire.ca/en/support/collecting-and-redeeming.html | 4 Oct, WebFetch |
| T6 | Canadian Tire 'Money' Rewards Program rules (paper coupons) PDF | effective-date banner: 21 Mar 2020 | a | https://media-triangle.canadiantire.ca/banners/promo-content/2023/01/-final-ctm-paper-coupons-rules-en.pdf | 4 Oct, curl; `ctm_paper_rules.pdf`, `ctm_paper.txt` |
| M1 | CTC/RBC release, "RBC and Canadian Tire Corporation launch loyalty partnership…" (CNW) | 13 Jan 2026 | a | https://canadiantire.mediaroom.com/2026-01-13-RBC-and-Canadian-Tire-Corporation-launch-loyalty-partnership,-unlocking-more-rewards-and-value-for-millions-of-Canadians | 4 Oct, curl; `mr_rbc.*` |
| M2 | CTC release, "Triangle Rewards and Tims Rewards Launch Loyalty Partnership" (CNW) | 2 Sep 2026 | a | https://canadiantire.mediaroom.com/2026-09-02-Triangle-Rewards-and-Tims-Rewards-Launch-Loyalty-Partnership | 4 Oct, curl; `mr_tims.*` |
| F1 | CTC, 2025 Annual Information Form | 18 Feb 2026 | a | https://s201.q4cdn.com/326551073/files/doc_financials/2025/ar/AIF-EN.pdf | 4 Oct, curl; `aif2025.pdf/.txt` |
| L1 | Competition Act, R.S.C. 1985, c. C-34, s. 74.01 ("current to 2026-09-21, last amended 2026-03-26") | 2026 | a | https://laws-lois.justice.gc.ca/eng/acts/c-34/page-11.html | 4 Oct, curl; `compact11.*` |
| L2 | Competition Bureau, "Ordinary Price Claims" (Enforcement Guidelines) | Date modified 2022-06-23 | a | https://competition-bureau.canada.ca/en/how-we-foster-competition/education-and-outreach/ordinary-price-claims | 4 Oct, curl; `cb_opc.*` |
| L3 | Competition Bureau, "Guide to the June 2024 amendments to the Competition Act" | Date modified 2025-08-18 | a | https://competition-bureau.canada.ca/en/how-we-foster-competition/education-and-outreach/guide-june-2024-amendments-competition-act | 4 Oct, curl; `cb_2024guide.*` |
| Q1 | OPC (Quebec), "La Société Canadian Tire ltée plaide coupable" | 6 Feb 2026 | a | https://www.opc.gouv.qc.ca/actualite/communiques/article/canadian-tire-plaide-coupable | 4 Oct, curl; `opc_ct.*` |
| Q2 | OPC, "Nouvelle garantie de bon fonctionnement en vigueur bientôt" | 15 Sep 2026 | a | https://www.opc.gouv.qc.ca/actualite/communiques/article/nouvelle-garantie-de-bon-fonctionnement-en-vigueur-bientot | 4 Oct, curl; `opc_gbf.*` |
| Q3 | OPC, "Consumer Tips: Before Purchasing an Additional Warranty" | none shown | a | https://www.opc.gouv.qc.ca/en/consumer/topic/warranties/tip-warranty | 4 Oct, curl; `opc_tip-warranty.*` |
| Q4 | OPC, "Electronic Devices – Being Aware of Legal Warranties" | "Last update: 29 September 2026" | a | https://www.opc.gouv.qc.ca/en/consumer/good-service/goods/electronic/advice/before-buying/aware-legal-warranties | 4 Oct, curl; `opc_aware-legal-warranties.*` |
| N1 | CBC News / The Canadian Press, Pierre Saint-Arnaud, "Canadian Tire slammed with near $1.3M fine for false advertising" | 7 Feb 2026, 11:10 AM EST | b | https://www.cbc.ca/news/canada/montreal/canadian-tire-fine-false-advertising-9.7079005 | 4 Oct, curl; `cbc_fine.*` |
| N2 | The Canadian Press, Tara Deschamps, "Purchase scanned at the wrong price? This policy may help you get it for free" | first published 19 Feb 2026 | b | https://www.thecanadianpressnews.ca/business/purchase-scanned-at-the-wrong-price-this-policy-may-help-you-get-it-for-free/article_6de6cc27-5370-5078-ad65-98af9e843384.html | 4 Oct, curl; `cp_scop.*` |
| N3 | The Globe and Mail / The Canadian Press, "Canadian Tire launches fee-based Triangle Rewards subscription program for $89 a year" | 13 Mar 2023 | b (WebFetch extract) | https://www.theglobeandmail.com/business/article-canadian-tire-launches-fee-based-triangle-rewards-subscription-program/ | 4 Oct, WebFetch |
| D1 | **CT API captures**: per-store price, sale end, eco fee, stock, Triangle rates (4 stores × 18 SKUs) | 4 Oct 2026 14:24–14:29 UTC | a (retailer's own data) | apim.canadiantire.ca (endpoints in §0) | `pa/*.json`, `pf/*.json`, `st*.json`, summary `ct_basket_2026-10-04.csv` |
| D2 | **Home Depot Canada API captures** (3 stores) | 4 Oct 2026 14:30–14:31 UTC | a (retailer's own data) | homedepot.ca/api/... | `comp/hdp/*.json`, `comp/hds_*.json` |
| D3 | **Amazon.ca product pages** | 4 Oct 2026 ~14:27–14:31 UTC | a (retailer's own page) | amazon.ca/dp/B00IJ0ALYS, /dp/B0C3PQHGR7, /dp/B0828CHKG3, /dp/B0CKKK1RGV | `comp/amz_*.html` |
| D4 | **Princess Auto site search** (Constructor.io index) | 4 Oct 2026 ~14:29 UTC | a (retailer's own site-search data) | ac.cnstrc.com/search/…?key=key_wIXKbLnT5aNrKxN9 | `comp/pa_*.json` |
| X1 | Flipp blog, "Does Canadian Tire Price Match?" and RedFlagDeals threads saying the price match ended around Aug 2022 | various | **c** | blog.flipp.com…, forums.redflagdeals.com… | search snippets only; **do not use** |

---

## 1. PRICE MATCH: current status

**What the primary record shows (4 Oct 2026):**
- CT's Policies page (P1) lists exactly these policy types: "Returns Policy Pricing Policy Resale Policy Privacy Policy Accessibility Policy Terms & Conditions Canadian Tire Text Messaging Terms & Conditions Multi-Year Accessibility Plan Canadian Tire Auto Service Terms and Conditions Paper Canadian Tire Money Canadian Tire Gift Card Terms & Conditions Refund Card Terms & Conditions". **There is no price-match policy among them.**
- `https://www.canadiantire.ca/en/customer-service/price-match.html` returns **HTTP 404** (P10).
- The **Pricing Policy** (P1), verbatim:
  - "**Price consistency** Canadian Tire attempts to match online prices to those in store. However, online prices, product and service selection and availability, as well as sale effective dates, may differ from those in store and may vary by geographic region."
  - "**Regional differences** Due to differences in sale effective dates across the country, items may be available online at the sale price before they are available in store. Dealers are under no obligation to make promotional products available, or to match online prices until the sale begins in their region."
  - "**Flyer differences** The prices found in the online version of the Canadian Tire flyer may be different to the ones appearing on the website. Market conditions and competitive pressures may cause prices and availability to change without further notice. Canadian Tire Associate Dealers may sell for less."
  - "Although great care is taken in the production of the canadiantire.ca website, typographical, illustrative or pricing errors may occur. We reserve the right to correct errors at any time."
- **The one price adjustment CT does state** (P3, online-order FAQ): "**Before I received my Ready for Pick Up email, a product in my order went on sale. Will the price be adjusted?** Yes, when you receive the email and visit the store to pick up your order, you should find that the price has been adjusted to reflect the sale price."
- **Clearance footnote** (P9): "Pricing, selection, and availability of clearance items are determined by each store… Rainchecks unavailable."

**OUR NOTE:**
- We can say: "Canadian Tire's current policy pages list no price-match policy, and its pricing policy says Associate Dealers may sell for less."
- We cannot say *when* the price match ended. The "August 2022" date comes only from tier-c sources (X1). See the UNVERIFIED section.
- Individual stores may still match at a Dealer's discretion. That is not documented, so don't claim either way.

---

## 2. RETURNS: policy and exceptions (P2, P1)

**Core rule (P2), verbatim:**
- "Unopened items in original packaging returned with a receipt within 90 days of purchase will receive a refund to the original method of payment or will receive an exchange. Items that are opened, damaged and/or not in resalable condition may not be eligible for a refund or exchange. Valid photo ID may be required to confirm this information."
- "We will attempt to give you a refund or exchange on every item purchased at any Canadian Tire store when you bring in your original receipt and issued Canadian Tire 'Money'®. When you don't have your receipt, we will offer a receipt look-up. Receipt look-up enables Canadian Tire stores to verify credit or debit card purchases within 90 days of the date of purchase."

**Shorter windows (P2), verbatim bullets (selection):**
- "E-scooters and electronics (home audio & video, personal audio & video, cameras & accessories, communications) may only be returned within 30 days."
- "Auto electronics (backup cameras, Bluetooth, car audio, GPS, inverters, portable DVD, remote starters, satellite radio) may only be returned within 14 days."
- "Dehumidifiers and Portable Air Conditioners may only be returned within 30 days."
- "Ink cartridges, media, and memory cards, books, DVDs, CDs, mattresses and portable beds may only be returned if unopened."
- "Bikes cannot be returned. Free tune up within 30 days with proof of purchase."
- "Gas powered outdoor equipment such as lawn mowers, snowblowers, tractors and generators may only be returned within 30 days and the item must be new, unused, and in its original packaging."
- "Tire Chains: … cannot be returned, refunded, exchanged or credited, except to exchange unused chains for a different size within 3 days of their original purchase."
- "Apple AirPods, Apple AirTags and Beats Audio Products: 30-day refund or replacement if product is returned in its unopened original packaging."
- "Returns, exchanges or warranties on an item without a receipt may not be accepted."
- "A defective item is subject to the manufacturer's warranty and will be repaired or replaced."
- Holiday: "Christmas and Halloween décor may be subject to return restrictions. Please contact your local store for details or refer to the returns policy printed on the bottom half of your store receipt."

**Non-refundable / non-exchangeable (P2), verbatim list:** "Gift Cards; Tinted paint and stain products; Products cut to length or modified; Magazines; Firearms; Ammunition; Fireworks; Clearance, final sale or AS-IS merchandise; Reusable Value Bags; All infant & child Car Seats, Booster Seats, and Travel systems; … Helium tanks… ; Balloons that have been inflated; Automotive trailers (utility, boat, and dump); Breast Pumps; Blind Bag Mini Hockey Sticks…; Trading & Collector Cards; Bear Repellants are final sale; Pokémon Trading Cards". (Some items in this list relate to safety categories. The rule-1 caution applies: don't comment on why.)

**Shipping on returns (P1, Pricing Policy):** "For items that have been delivered and are being returned, the portion of the shipping cost applicable to the item(s) being returned will not be refunded."

**Pick-up fees on returns (P3):** "In the event of a return, it is at the discretion of the store you placed your order with as to whether you are eligible for a refund of your pick up fee."

**CT Money on returns:**
- e-CTM (T1): "If you return an item for a refund and had received eCTM when you purchased such item, such amount of eCTM will be deducted from your Triangle Rewards Account. Merchandise that was purchased either in whole or in part by redeeming eCTM may not be returned for cash, rather, the connected Triangle Rewards Account will be credited with the same amount of eCTM used to make the original purchase."
- Paper (T6): "Upon return of merchandise you are required to return the same amount of Canadian Tire 'Money' coupons received with the purchase, failing which the value will be deducted from your refund."

**Refund Cards: they expire (P1, P2), verbatim:**
- "**Refund Cards will expire one year after the date of issue (except for those issued in the province of Saskatchewan). After expiry any remaining balance will not be returned to you.**"
- "Return of merchandise purchased with a Refund Card will only be credited to another Refund Card. Cards are not redeemable for cash or gift cards…"
- "Any portion of a purchase paid for using a Refund Card balance will not be eligible to earn Canadian Tire Money. Refund Cards cannot be used for on-line purchases."

**Gift cards, for contrast (P1):** "Gift cards have no expiry date and are non-refundable… Gift cards cannot be used for online purchases or the purchase of other gift cards… In Quebec only, cards with a value of $5 or under may be exchanged for cash."

**Receipt-free returns perk (P5):** registering for Triangle lets members "Return products at Canadian Tire, Mark's/L'Equipeur, Sport Chek, and Atmosphere without a paper receipt."

**OUR NOTE:**
- 90 days is the headline window, but the electronics category is 30 days and auto electronics 14 days.
- **Refund Card expiry (1 year) vs gift card no-expiry** is a clean, viewer-useful contrast. Fix: spend a refund card within a year, or ask for a refund to the original payment method where the policy allows.
- Whether provincial gift-card laws apply to "Refund Cards" was **not verified**. Do not say the expiry is legal or illegal.

---

## 3. TRIANGLE REWARDS / CT MONEY

### 3a. Earn rates (CT's own words)
- **Base rate 0.4%.** P9 footer and the auto-service page footnote (P8), verbatim: "Any bonus multiplier is based on the base rate of collecting CT Money (0.4%), and will be added to whatever the Member would otherwise collect, without the bonus. Example: On a $100 (pre-tax) purchase with a 20x bonus multiplier a Member would earn a bonus $8 in CT Money (20 X 0.4% X $100)."
- **CT's API confirms it per product.** Every price capture in D1 returns `"triangleBenefits":{"tsRewardsBaseLoyalty":0.004,…,"tsTriangleMastercardBenefits":0.04}`. For example, WD-40 325 g at $10.99 shows `tsRewardsBaseLoyaltyValue: 0.04`, which is **4 cents**.
- **Triangle Mastercard (P8 footnote):** "The 50x for Triangle Mastercard, World Mastercard and World Elite Mastercard customers consists of the 10x everyday plus a 40x bonus." The API field `tsTriangleMastercardBenefits: 0.04` matches that: 10 × 0.4% = 4%.
- **"Not all items" (P9):** "Not all items sold at Canadian Tire earn CT Money. The offered rate is exclusive of any bonus or promotional offers or redemption transactions. CT Money is collected on the pre-tax."
- **Excluded "Eligible Merchandise" (T1), verbatim excerpt:** "gift cards, lottery tickets, hunting and fishing licences, tire disposal fees, tire taxes, … environmental fees, repair charges, delivery or assembly charges, other store services (other than automobile service), … other store labour (other than labour for automobile repairs), … tobacco products or alcohol, … premiums for credit card balance insurance or for insurance or extended warranties on items purchased with a Canadian Tire branded credit card…"
- **Store-level exclusions (T1):** "**In addition, individual Canadian Tire stores may exclude additional items sold in that store from being Eligible Merchandise.** We reserve the right, at any time without notice, to change what constitutes Eligible Merchandise."
- **Rate changes (T1):** "The rate at which eCTM can be collected may vary from time to time and by location and is subject to change by Canadian Tire without notice."
- **Fuel (P5):** "Triangle Rewards card: You can collect 3 cents back per litre in CT Money when using cash or debit (0.5 cents per litre when using 3rd party or fleet credit cards). Triangle Mastercard: 5 cents back per litre in CT Money on all fuel types." And: "You can collect CT Money on fuel purchases at Gas+/Essence+ and Petro-Canada locations. Unfortunately, you are not able to redeem."
- **No earn on redeemed portion (T1):** "You will not be able to collect eCTM on that portion of a transaction in respect of which you redeemed eCTM." P5: "CT Money is earned on the balance of your transaction after redemption is made."

**OUR NOTE (arithmetic):**
- 0.4% = **$4 of CT Money per $1,000** of eligible pre-tax spend.
- With a Triangle Mastercard at CT's 4% everyday rate, that becomes **$40 per $1,000**.
- Tims partnership (M2): 2% for scanning is **5×** the base CT store rate.

### 3b. Redemption
- **T1:** "eCTM can only be redeemed for merchandise (including applicable taxes) at participating Canadian Tire stores or at other locations designated by Canadian Tire. eCTM cannot be redeemed for alcohol, tobacco, gift cards, pre-paid cards…, or used to make a payment on any Canadian Tire Bank issued credit cards…"
- **P5:** "You can not redeem CT Money on shipping and handling. CT Money can only be redeemed for eligible merchandise (including applicable taxes). **Currently tires and wheel purchases are excluded.**" This is the answer to "Can I redeem for my full purchase online at canadiantire.ca?"
- **P5, online:** "Redeem your CT Money in-store at … as well as online at **select stores** at canadiantire.ca. You will be advised if online redemption is possible for your selected store during checkout." And: "In order to redeem your CT Money for online purchases at canadiantire.ca, you are required to be signed in with a Triangle ID."
- **Where it can be spent (M2, 2 Sep 2026):** "Canadian Tire Money can only be redeemed at Canadian Tire, Party City, SportChek, Mark's, L'Équipeur, Pro Hockey Life, Sports Rousseau, Hockey Experts, Atmosphere, L'Entrepôt du Hockey and participating Sports Experts locations across Canada."
- **PartSource (P5):** CT's answer to "Can I redeem Canadian Tire Money® at Partsource?" lists only the banners above. PartSource is not among them.
- **No minimum redemption** is stated in T1 or T2.

### 3c. Expiry and inactivity
- **T1 (raw PDF):** "**We may expire the eCTM in your Triangle Rewards Account in the event that there has been a period of inactivity of 18 months or more.** For the purposes of this section, 'inactivity' means that there has been neither a transaction in which you have collected eCTM, nor a transaction in which you have redeemed eCTM during the period in question."
- **T2 (WebFetch extract)** carries the same 18-month sentence.
- **Termination (T1):** "Termination or cancellation of membership in the Program will result in the immediate closing of the Member's Triangle Rewards Account and the cancellation of all eCTM in such Triangle Rewards Account without any compensation or other liability to the Member."
- **Program-wide expiry power (T1):** "Canadian Tire may, in its sole discretion and at any time without prior notice either (i) cancel the Program or (ii) except if you are a Member residing in Quebec, Ontario or such other province where prohibited by law, establish a date upon which eCTM will expire and may no longer be used."
- **Amendments (T1):** "For Members resident outside of Quebec only: Canadian Tire may amend these terms and conditions at any time without notice." Quebec members get "written notice of any amendment … at least 60 days, but not more than 90" days before it takes effect.

### 3d. 2025–2026 changes (primary)
- **RBC × Triangle, launched 13 Jan 2026 (M1):** "By linking their eligible RBC credit and debit cards with their Triangle Rewards accounts, millions of RBC cardholders can earn 3x Canadian Tire Money when they use their linked RBC credit or debit card to make a qualifying purchase at Canadian Tire, SportChek, Mark's and other participating CTC retail banners… starting later this year, will have the ability to convert Avion points to Canadian Tire Money." Quote from Darryl Jenkins, EVP and Chief Development Officer, CTC: "This partnership supports our ongoing transformation of Triangle Rewards from a loyalty program into a powerful Canadian ecosystem that offers everyday value to our nearly 12 million members."
- **Tims × Triangle, launched 2 Sep 2026 (M2):**
  - Earn: "**Scan for Tims Rewards:** Earn 2% on eligible Tim Hortons purchases* (pre-tax)." / "**Scan for Tims Rewards and then pay with a Triangle credit card:** Earn an additional 2% on total Tim Hortons purchases (post-tax)." / "**Use a Triangle credit card as the payment method for Scan & Pay in the Tims app:** Earn an additional 1% on eligible Tim Hortons purchases* (pre-tax)."
  - Footnote: "Not all Tim Hortons locations participate."
  - Membership: "more than 12 million Triangle Rewards members, almost 8 million Tims Rewards members".
- **WestJet linked loyalty (P8 footnote, verbatim excerpt):** "Linked Members can convert WestJet points into CT Money at a rate of one hundred twenty (120) WestJet points to one dollar ($1.00) in CT Money. A minimum of two thousand four hundred (2400) WestJet points must be transferred." The same footnote describes Canadian Tire and Party City stores as "(both of which are independently owned and operated)".
- **Petro-Canada (F1, AIF 18 Feb 2026):** "Through the partnership, a total of over 200 of the Company's Canadian Tire Gas+ gas bars are planned for rebranding into Petro-Canada stations while maintaining CTC ownership… [some] were rebranded from Canadian Tire Gas+ to Petro-Canada in 2025, bringing the total number of rebranded gas bars to 61."
- **Membership size (F1):** "Triangle Rewards, with 12.2 million active members, and a credit card portfolio with 2.3 million active credit cardholders."

### 3e. Triangle Select (subscription)
- **Price.** T3 (WebFetch extract): "Only $89 per year (plus applicable taxes)". T4 (WebFetch extract): "The annual subscription fee is $89, plus applicable tax". Quebec monthly equivalent: "$7.42 + applicable taxes".
- **Benefits.** T3 (WebFetch extract):
  - "10x Everyday In-Store Bonus on in store purchases at participating stores"
  - "20x In-Store Brand Boost on eligible purchases of 20 select brands"
  - "20x In-Store Top Up Bonus on your largest purchase each year"
  - "Welcome Gift (Valued at $50)"
  - "Free Shipping over $50 at Mark's & Sport Chek Unlimited (up to the first $20 in shipping fees per order)"
  - "Ship to Home Fees Reimbursed from Canadian Tire On 5 transactions"
  - T4 adds: "Reimbursement will be…up to a maximum of $12, for the first five online purchases".
- **Participating stores (T4):** "Canadian Tire, Mark's/L'Equiper, Sport Chek and Party City". On the 20x largest purchase: "We will apply the 20X bonus multiplier after the end of the Subscription Term."
- **Cancellation and refunds (T4):**
  - Outside Quebec: "cancellation is only effective as at the end of the Subscription Term and the Subscription Fee is non-refundable".
  - Quebec: "you may be entitled to a partial refund of the Subscription Fee based on the time left in the Subscription Term, less the value of any goods, services or vouchers you have received".
- **Auto-renewal (T3):** "Your subscription will automatically be renewed at the end of your subscription term and your payment method on file will be charged (excluding Alberta and Quebec)." T4 lists the exceptions: Quebec residents, Alberta residents who did not select auto-renewal at enrolment, members who switched it off, and failed payment.
- **Launch.** N3 (Globe/CP, 13 Mar 2023): $89 a year. Quote from Jason Blanchette, then SVP loyalty: beta members earned "more than three times the subscription fee". **That is a company claim, attribute it.** F1 (AIF) lists the launch in its 2023 history: "The Company launched Triangle Select, an annual fee-based subscription program…".
- **API (D1):** the CT pricing API returns `triangleSelectBenefits: {"tsEverydayDiscount":0.04, "tsBrandDiscount":0.08}` on each product. Example: WD-40 at $10.99 gives tsEverydayDiscountValue $0.44.

**OUR NOTE (break-even arithmetic, pre-tax, ignoring brand and top-up bonuses):**
- The 10x everyday bonus = 10 × 0.4% = **4%** extra CT Money.
- To earn back $89 in bonus alone: $89 ÷ 0.04 = **$2,225** of eligible in-store spend per year.
- If you count the $50 welcome gift at CT's stated value: ($89 − $50) ÷ 0.04 = **$975**.
- With 13% HST on the fee (Ontario): $100.57, so break-even is about **$2,514** without the gift.
- The fee is non-refundable outside Quebec and auto-renews in most provinces.
- Caveat: the T4 extract found no cap on the 10x bonus, and WebFetch may miss small print. **Verify on screen before stating "no cap".**

### 3f. Paper Canadian Tire 'Money'
- **T6, rules PDF, verbatim banner:** "**EFFECTIVE MARCH 21, 2020, ISSUANCE OF ALL CANADIAN TIRE 'MONEY' PAPER COUPONS CEASED.** CANADIAN TIRE 'MONEY' PAPER COUPONS CAN NO LONGER BE EARNED, HOWEVER, YOU CAN CONTINUE TO REDEEM YOUR CANADIAN TIRE 'MONEY' PAPER COUPONS IN ACCORDANCE WITH THESE TERMS AND CONDITIONS."
- **T6:** "Rewards can be redeemed only at Canadian Tire stores. Please note this means that rewards are not redeemable at Canadian Tire gas bars." And: "There are no time limits, no thresholds, no minimum redemption values…" And: "The program is subject to modifications or termination at any time by Canadian Tire Corporation, Limited without notice."
- **P1:** "We no longer issue paper CT Money, but you can earn electronic CT Money by scanning a Triangle Rewards card or paying with a Triangle credit card… **Can I redeem paper Canadian Tire 'Money'®?** Yes, you can redeem paper CT Money at all Canadian Tire stores."
- **P5:** "No, Canadian Tire paper money can only be redeemed or converted to electronic CT Money at Canadian Tire retail stores." T5 (WebFetch): "Triangle Rewards™ Members can convert paper CT Money to electronic CT Money at a Canadian Tire retail store."
- **OUR NOTE:**
  - Paper CTM has **no time limit** under its own rules (T6).
  - e-CTM **can expire after 18 months of inactivity** (T1).
  - Converting paper to electronic swaps the first rule set for the second. That is a factual contrast, not advice to never convert.
  - Rule-4 care: CT's rules allow this. Present it as "read the rules", not as a trap.

---

## 4. WARRANTIES, PROTECTION PLANS and the QUEBEC CONTEXT

**CT's own exchange warranties.** These are product-page `warrantyMessage` fields (D1), verbatim:
- "This product carries a 1 year exchange warranty redeemable at any Canadian Tire store." This appears on WD-40, Duracell, Energizer, Mobil 1, Castrol, Rain-X, Coleman cylinder, Lysol, the Ninja AF100C, and the Toshiba, Panasonic and MASTER Chef microwaves.
- "This product carries a lifetime exchange warranty redeemable at any Canadian Tire store." (Rubbermaid Roughneck 68 L; Mastercraft 270-pc socket set)
- "This product carries a 3 year exchange warranty redeemable at any Canadian Tire store." (Mastercraft 20V drills; MotoMaster chargers)
- "This product carries a special warranty. Please see your local Canadian Tire store for details." (DEWALT DCK240C2, DCK477D2) and "3 yr repair" (DEWALT DCK277D2)
- "4-year free replacement warranty & 4-year Power Assist roadside boost assistance" (MotoMaster OEPLUS Group 48 battery)
- **P2:** "We stand behind the products we sell. Details on warranties can be found on all product detail pages. If you need to make a claim on the manufacturer's warranty, please contact the manufacturer or your local Canadian Tire store. If a product is defective, the manufacturer's warranty applies."

**The paid protection product we found: Tire Care Guarantee with Replacement Advantage (P6), verbatim:**
- "Tires that have been purchased and installed at Canadian Tire are backed by our complementary Tire Care Guarantee. Tire Care Guarantee with Replacement Advantage applies only if purchased along with your tires."
- Table: Warranty Cost: Tire Care Guarantee "Free" / with Replacement Advantage "From $9.99". Non-repairable road hazard damage: "Pro-Rated" / "Free*". Manufacturer defects: "Pro-Rated" / "Yes". Duration: "6 Years" / "6 Years". "Free spare tire change service – 1st year after purchase": "No" / "Yes". Satisfaction guarantee: "30 Days" / "30 Days".
- **Price schedule:** "Replacement Advantage cost is based on the regular retail price of a tire: $9.99 for tires priced up to $149.99 each, $14.99 for tires priced up to $199.99 each, $16.99 for tires priced up to $249.99 each, $19.99 for tires priced up to $299.99 each, and $24.99 for tires priced over $300.00 each."
- "One Tire Care Guarantee with Replacement Advantage must be purchased for each tire."
- **Pro-rating:** "A pro-rated replacement price will be charged based on regular retail price… if one third of the useable tread is used, you pay one third of the regular retail price of a new tire purchased from us." And: "Balancing, disposal fees and taxes (for replacement tires) are the responsibility of the tire owner."
- **Provider:** "Tire Care Guarantee and Tire Care Guarantee with Replacement Advantage are provided by Canadian Tire Corporation, Limited."
- **OUR NOTE:** for a set of four tires at $150–$199.99 each, Replacement Advantage = 4 × $14.99 = **$59.96** plus tax. Price examples only; no claim on value.

**General merchandise "Product Protection Plans":**
- We **found none** on canadiantire.ca on 4 Oct 2026. Checks made: the customer-service and policy pages, the product warranty messages for 18+ SKUs, the site JavaScript (no "protectionPlan" or "extendedWarranty" strings), and web search.
- The T1 exclusion list does mention "premiums … for insurance or extended warranties on items purchased with a Canadian Tire branded credit card". That is a credit-card product, not a store plan.
- **Do not say CT sells, or does not sell, extended warranties on merchandise.** Say "we didn't find one on its website".

**Quebec context: extended warranties (OPC, primary).** Q3 (OPC English page), verbatim:
- "Before selling you an additional warranty (also known as an "extended warranty"), merchants are required to inform you about the existing free warranties."
- In store, the merchant must "inform you of the existence and contents of certain legal warranties by reading the following text to you: 'The Act provides a warranty on the goods you purchase or lease: they must be usable for normal use for a reasonable length of time.' Merchants must also give you a written notice that only contains certain mandatory information".
- The merchant must also "verbally inform you of the existence and length of the warranty offered free of charge by the manufacturer, if applicable."
- Q4 (last updated 29 Sep 2026): "Before buying an extended warranty, be aware that any electronic device bought from a merchant is covered by warranties provided by law."

**Quebec's new legal "garantie de bon fonctionnement", in force 5 Oct 2026 (Q2, OPC, 15 Sep 2026), verbatim (French):**
- "Dans moins d'un mois, plusieurs électroménagers et appareils électroniques seront couverts par une nouvelle garantie légale de bon fonctionnement. Elle s'appliquera à 14 catégories de biens dès le 5 octobre 2026."
- "Cuisinière, réfrigérateur, congélateur, climatiseur et thermopompe : 6 ans / Laveuse, sécheuse et lave-vaisselle : 5 ans / Téléviseur : 4 ans / Ordinateur portable ou de bureau, console de jeu vidéo, téléphone cellulaire et tablette électronique : 3 ans"
- "Protection automatique et gratuite"; "Durée de la garantie calculée à compter de la date de livraison"; applies to goods "achetés ou loués à l'état neuf auprès d'un commerçant à compter du 5 octobre 2026".
- Our translation, for the producer: "In less than a month, several appliances and electronic devices will be covered by a new legal good-working-order warranty. It will apply to 14 categories of goods from October 5, 2026."

**CT's Quebec notice (P7), verbatim:** "NOTICE TO QUÉBEC CONSUMERS re: Availability of Replacement Parts, Repair Services, and Maintenance and Repair Information. Please note that Canadian Tire Corporation, Limited, and its retailers do not guarantee the availability of replacement parts, repair services, or maintenance and repair information for products within the meaning of the Quebec Consumer Protection Act." (P7 then lists third-party brand-owner links. **Do not use that list to name who makes any CT product (rule 7).**)

**OUR NOTE:**
- The angle is "before you pay for an extended warranty in Quebec, the law already gives you one", and from Oct 5 a fixed-length one for 14 categories. That applies to any Quebec retailer, not CT specifically.
- Don't imply CT fails to give the s.228.1 notice. We have no evidence either way.

---

## 5. "REGULAR PRICE", "WAS" and "SAVE X%": CT's statements, the law, and CT's case history

### 5a. CT's own words
- **P1 Pricing Policy:** "The e-FLYER and canadiantire.ca each offer limited-time sales values, special buys and items at Canadian Tire's everyday low prices. **Regular prices shown reflect the prices at which the products have been sold by Canadian Tire as of the date of issuance indicated.**"
- **P9 footer:** "**±Was price reflects the last national regular price this product was sold for.**"
- **P9 footer:** "**Online prices and sale effective dates may differ from those in-store and may vary by region. Dealers may sell for less.**"
- **P9 clearance:** "◊Off our original prices. Pricing, selection, and availability of clearance items are determined by each store."
- **What the API shows (D1).** The site carries two separate flags: `isOnSale` (which drives the "Save X%" badge against `originalPrice`) and `displayWasLabel` (the "Was" label). **In all 74 store × SKU captures (`pa/*.json`), `displayWasLabel` was `false`.** Every sale item was shown as "Save X%" against an `originalPrice`, not as "Was $X". There is no price-history endpoint, so **we captured no "was" price history**.

### 5b. The law (L1, Competition Act, current to 2026-09-21), verbatim
- **s. 74.01(2), "Ordinary price: suppliers generally":** "Subject to subsection (3), a person engages in reviewable conduct who, for the purpose of promoting… makes a representation to the public concerning the price at which a product or like products have been, are or will be ordinarily supplied where suppliers generally in the relevant geographic market, having regard to the nature of the product, (a) have not sold a substantial volume of the product at that price or a higher price within a reasonable period of time before or after the making of the representation, as the case may be; and (b) have not offered the product at that price or a higher price in good faith for a substantial period of time recently before or immediately after the making of the representation, as the case may be."
- **s. 74.01(3), "Ordinary price: supplier's own":** "A person engages in reviewable conduct who… makes a representation to the public as to the price at which a product or like products have been, are or will be ordinarily supplied by the person making the representation **unless that person, having regard to the nature of the product and the relevant geographic market, establishes that** (a) they have sold a substantial volume of the product at that price or a higher price within a reasonable period of time before or after the making of the representation, as the case may be; or (b) they have offered the product at that price or a higher price in good faith for a substantial period of time recently before or immediately after the making of the representation, as the case may be."
- **s. 74.01(5), "Saving":** "Subsections (2) and (3) do not apply to a person who establishes that, in the circumstances, a representation as to price is not false or misleading in a material respect."
- **s. 74.01(1.1), "Drip pricing":** "…the making of a representation of a price that is not attainable due to fixed obligatory charges or fees constitutes a false or misleading representation, unless the obligatory charges or fees represent only an amount imposed on a purchaser of the product… by or under an Act of Parliament or the legislature of a province."
- History line under the section: "1999, c. 2, s. 22; 2009, c. 2, s. 422; 2022, c. 10, s. 259; 2024, c. 15, s. 236; 2026, c. 3, s. 597".

### 5c. Bureau guidance
**L2, Enforcement Guidelines, date modified 2022-06-23.** These predate the 2024 amendment, and the statute text quoted inside them is the older wording.
- Volume test: "The substantial volume of product requirement will be met if more than 50% of sales are at or above the reference price." And: "The time period to be considered will be the twelve months prior to (or following) the making of the representation. However, this period may be shorter having regard to the nature of the product."
- Time test: "The substantial period of time requirement will be met if the product is offered at or above the reference price for more than 50% of the time period considered." And: "The time period to be considered will be the six months prior to (or following) the making of the representation."
- Good faith factors include whether "the reference price was a price at which genuine sales had occurred, or it was a price comparable to that offered by competitors."
- Geographic market: "In the case of larger suppliers, the relevant geographic market may be the combined geographic areas of individual outlets. The relevant geographic market is usually captured by the area covered by the medium of communication that is employed."

**L3, Guide to the June 2024 amendments, modified 2025-08-18:** "The changes strengthen the Competition Bureau's ability to act against bogus discount claims and drip pricing by: Requiring that businesses be able to establish that their discount claims are genuine. Clarifying that it is misleading to omit mandatory fees from advertised prices, unless those fees are imposed by government on purchasers, such as sales tax."

### 5d. CTC case history on reference prices
**Q1, OPC, 6 Feb 2026. Label: GUILTY PLEA (Quebec Consumer Protection Act, penal).** Verbatim (French):
- "L'Office de la protection du consommateur (OPC) annonce que la Société Canadian Tire ltée a plaidé coupable, aujourd'hui à Montréal, à des accusations portées en vertu de la Loi sur la protection du consommateur (LPC). Pour 74 des chefs d'accusation déposés par le Directeur des poursuites criminelles et pénales, la Société devra payer des amendes totalisant 1 287 550 $ avec les frais."
- "L'Office reprochait à Canadian Tire d'avoir contrevenu à l'article 225 b) de la LPC, qui interdit au commerçant d'indiquer faussement un prix courant ou un autre prix de référence pour la vente d'un bien. Sur une période de 6 mois, soit d'avril à octobre 2021, l'Office a vérifié les prix de 7 produits ciblés dans les circulaires de Canadian Tire, sur son site web ainsi que dans 3 succursales de la grande région de Montréal."
- "Canadian Tire a reconnu sa culpabilité pour 5 des produits faisant l'objet de l'enquête, soit des ensembles de couteaux Henckels et Cuisinart, des batteries de cuisine Lagostina et Heritage et une perceuse sans fil Dewalt."
- Our translation: the OPC said that when the targeted products were advertised on sale, the discount was stated against a regular price, but sales data showed the products were sold at that regular price "only in a very small proportion of cases", and in store they were "practically never" displayed at the regular price during the review period.

**N1, CBC/The Canadian Press, Pierre Saint-Arnaud, 7 Feb 2026:**
- "Canadian Tire has been ordered to pay just under $1.3 million after pleading guilty to 74 counts of violating sections of Quebec's Consumer Protection Act, related to false advertising."
- "Crown prosecutor Jérôme Dussault says the Canadian retail giant agreed to the settlement after initially pleading not guilty." "…fines and fees ranging from $15,625 to $18,150 per count."
- **CT's statement, as reported:** "The OPC charges relate to five products over a six-month period five years ago. Importantly, no customers were overcharged and the matter is now concluded."

**Competition Bureau (federal):** our searches found **no** Competition Bureau consent agreement, Tribunal or court case against CTC on ordinary-price claims. That is a "not found", not a "none exists".

**OUR NOTE (on-air framing):**
- Label it "a guilty plea under Quebec's consumer protection law, over 5 products, from April to October 2021", and **carry CT's statement in full**.
- **Do not** link it to any current price we captured, and do not say or imply that current "Save X%" claims are false. The 2026 captures are a separate observation, *not* evidence about the 2021 case.
- Using DeWalt's present prices right next to the OPC's "perceuse sans fil Dewalt" would imply continuation. **Keep those beats apart, or drop one** (see DO-NOT-USE).

---

## 6. SCANNER PRICE ACCURACY CODE (N2, Tara Deschamps, The Canadian Press, 19 Feb 2026)

- "It's only applied at retailers that sign the code, which include Best Buy, **Canadian Tire**, Costco, Giant Tiger, Loblaw Cos. Ltd., Metro, Rona, Shoppers Drug Mart, Sobeys, Home Depot Canada and Walmart Canada."
- "If an item is advertised as less than $10 and rings up incorrectly, the code dictates the purchaser should receive the item for free. If you're buying multiples of the same item, the code says the shopper gets the first one free and all subsequent items at the price they should have been charged. If the incorrectly priced item costs more than $10, customers receive $10 off the displayed price."
- "The code does not apply to items with prices physically attached to them — merchandise with sale or clearance stickers… The code applies across most of Canada but not in certain provinces or territories like Quebec, where legislation already offers recourse when customers are mischarged."
- "To find out whether the place you're shopping has signed the code, look for signage at the front of the store or ask a cashier, said Santo Ligotti, the council's vice-president of marketing and member services."
- The Retail Council of Canada page (retailcouncil.org) returned **403** to both curl and WebFetch, so the signatory list is from CP only (tier b).
- **OUR NOTE:**
  - Each CT store is Dealer-operated (F1). Say: "The Canadian Press lists Canadian Tire among signatories; look for the sign at your store's front."
  - Do not assert every store applies it. A tier-c forum thread title suggests some stores didn't in the past (DO-NOT-USE).

---

## 7. ONLINE vs IN-STORE PRICES, and DEALER-SET PRICING (CTC's own words)

- **F1 (AIF, 18 Feb 2026):** "Canadian Tire's 502 stores are operated by Dealers, who are independent third parties that own the fixtures, equipment and inventory of the stores they operate, employ the store staff, and are responsible for store operating expenses."
- **F1:** "Each Dealer agrees to comply with prescribed policies, marketing plans and operating standards, which among other things, include purchasing merchandise primarily from CTC, while maintaining the decision-making behind customizing their assortments to meet the demands of the communities in which they operate, and **offering merchandise for sale to consumers at prices not exceeding those set by the Company**."
- **F1, pricing tools:** "Existing AI deployments have included customer-facing and internal use cases, such as an AI-enabled shopping assistant and tools to optimize pricing and margin." This is a company statement. **No claim of personalised pricing is made or implied.**
- **P1:** "Canadian Tire Associate Dealers may sell for less." / "Dealers are under no obligation to make promotional products available, or to match online prices until the sale begins in their region."
- **P4:** "We have attempted to match our prices on canadiantire.ca with those that you will see in your local store. However, while we strive for pricing accuracy, market conditions and competitive pressures can cause prices to change. Online pricing and product selection may also differ from your local store."
- **P8 footnote:** "Canadian Tire and Party City retail store locations (both of which are independently owned and operated)".
- **Observed in D1** (online, per-store prices, 4 Oct 2026; see §10):
  - Same SKU, different regular price by region. WD-40 Smart Straw 325 g: **$12.99** regular in Toronto (150) and Calgary (302) vs **$11.99** in Halifax (465) and Vancouver (389). Rubbermaid Roughneck 68 L: **$17.99** in Toronto and Halifax vs **$19.99** in Calgary and Vancouver.
  - The same sale ends on different dates by region. Duracell AA 24 at $19.99 runs until 2026-10-08 (Toronto, Vancouver) vs 2026-10-07 (Calgary, Halifax). DCK277D2 runs until 2026-10-22 (Toronto, Vancouver) vs 2026-10-14 (Calgary, Halifax).
  - The badge "STORESPECIAL" appeared on Coleman 2-in-1 grill 0762614 (Toronto and Halifax). Its meaning was not verified.
- **OUR NOTE:** these are website prices for the selected store. CT itself says in-store can differ. Never say "the shelf price was". Always say "on Canadian Tire's website, with [store] selected".

---

## 8. SHIP-TO-HOME, PICK-UP, SAME-DAY: fees and thresholds (P3)

- **Pick Up:** "Pick Up is free at the majority of stores. Some stores may require a minimum order value (before taxes). Orders that do not meet this value will be subject to a small fee."
- **Same-Day Delivery:** "$9.99 flat fee + tax." and "distance from store must be less than 15km." **Discrepancy:** the site footer (P9) says "distance from store must be less than **10km**". Both seen 4 Oct 2026.
- **Ship to Home:** "Registered Triangle Rewards Members can enjoy Free Local Shipping† on eligible orders above a certain pre-tax order spend at select stores. Shipping rates depend on the size and weight of your eligible product(s), the distance of the delivery address from your selected store, and whether the delivery area is remote…" and "†Free Local Shipping is only available up to a certain distance from participating delivery stores. Maximum distance is approximately 50 km and is subject to change."
- **Free Local Shipping conditions:** "Your order must hit the minimum pre-tax order spend, which may vary by store…" and "Only eligible Ship to Home products count towards the minimum pre-tax order spend… Certain shipping-related fees (e.g. In-Home Delivery, In-Home Delivery and Unpack) are not covered by Free Local Shipping."
- **Exclusions:** "Due to tax requirements, we are unable to ship across provincial borders." "Heavy and/or oversized (66-350lbs and/or 120"-350" in any direction) products are only available for delivery to addresses within 100km of your selected Canadian Tire store."
- **Holds and pre-authorizations:**
  - "Your order will be held at your selected store location for a minimum of 3 days, up to a maximum of 15 days. Hold times vary by store."
  - "For Pick Up at Store/Curbside Pick Up: When you place an order, we retain a preauthorization for the full amount on your credit card until the items are located and ready for pick up."
- **Store API (D1, `/v1/store/store/{id}`):** all four stores return `"subsidizedSTH":[{"isLoyalty":true,"threshold":99}]` and `"onlineOrdering":true`. **OUR NOTE / interpretation:** this looks like a **$99** pre-tax Free Local Shipping threshold for Triangle members at those four stores. It is an API field, not on-page text. **Verify on the site header before stating $99.**
- **Triangle Select (T3, T4):** reimburses CT ship-to-home fees "On 5 transactions", "up to a maximum of $12".
- **CT Money and shipping (P5):** "You can not redeem CT Money on shipping and handling."

---

## 9. AUTO SERVICE: rates, fees, estimates and authorization

- **Posted labour rates or menu prices: none found.** P8 (auto-service.html, /tires.html, /oil-change.html, /brakes.html) lists services and what's included but **no prices**. The CT product search returned no priced installation, storage or oil-change service SKUs (4 Oct 2026). The only auto-service price on P8: "Roadside Assistance® Plans starting from $74.99 +tax."
- **Repair authorization (P1, "Canadian Tire Auto Service Terms and Conditions"), verbatim:**
  - "I hereby authorize you and your employees to carry out the repair work described in the Repair Order and to purchase on my account any parts and materials necessary to carry out repair work subject to the estimate attached (if applicable) **or an estimate which I later approve (whether in writing, orally or by electronic communication)**…"
  - "I acknowledge that, upon the completion of the repair work authorized hereby, you will have a lien pursuant to applicable repair and storage lien legislation and that you may register that lien and seize, at your discretion and at my sole cost and expense, the vehicle for non-payment… By replying 'Approved' (or an equivalent statement of approval) I acknowledge and agree to the terms and conditions above and to those below."
  - "I HEREBY RELEASE AND FOREVER DISCHARGE YOU AND EACH OF YOUR EMPLOYEES FROM ANY LOSSES I MAY SUFFER RELATING TO DAMAGE TO OR LOSS OF MY VEHICLE AND/OR ANY ITEMS CONTAINED THEREIN THAT ARE CAUSED BY CIRCUMSTANCES BEYOND YOUR CONTROL."
- **Ontario stores (P1), CT quoting the Ontario CPA:** "you have a right to a written estimate. A repairer may not charge an amount that is more than ten (10) per cent above that estimate. If you have waived your right to an estimate, the repairer must have your authorization of the maximum amount that you will pay for the repairs… In either case, the repairer may not charge for any work you did not authorize."
- **Manitoba stores (P1):**
  - "A written estimate for repairs that cost more than $100 must have been given to you unless you declined to receive a written estimate…"
  - "You cannot be charged a fee for an estimate unless you were told about the fee and agreed to pay it."
  - "You cannot be charged more than the total of the estimate plus 10% of that estimate up to a maximum of $100."
- **Shop supplies fee (P1):** "**Shop Supplies are calculated at a rate of 10% of labour sales.**"
- **Labour warranty (P1):** "Warranty not available for commercial use, a minimum labour warranty of 100 days / 5500 km applies to parts installed unless otherwise stated."
- **Tire storage (P1), verbatim:** "Tires will be stored up to a maximum of 8 months from Invoice date OR until customer requests to have Tires removed from the storage location for any reason, at which point the storage term will end. Canadian Tire is not responsible for unclaimed tires at expiration of storage term. **Tires left beyond 30 days of term expiration date will be disposed of without any liability or obligation to customer.** Payment is deemed to be acceptance of these terms by customer." The tire storage price is not published.
- **Cash rounding (P1):** "Auto Work orders are also subject to rounding, which is done at the register. Therefore, the total on the work order may not match the total being paid at the register."
- **Extra charges (P8, tires):** "There may be an additional charge if vehicle has a Tire Pressure Monitoring System." / "Additional charge may apply if vehicle is equipped with a Tire Pressure Monitoring System."
- **Tire recycling fee (P9):** "The tire producer / manufacturer of the tires you are buying, and Canadian Tire is responsible for the recycling fee that is included in your invoice." (Verbatim, including the garbled grammar.)
- **CT Money and auto (T1):** auto service labour is *not* excluded from earning: "other store labour (other than labour for automobile repairs)". **But** "tire disposal fees, tire taxes … environmental fees" are excluded. Online, "tires and wheel purchases are excluded" from **redemption** (P5).
- **OUR NOTE, on-air "fix":**
  - Ask for a written estimate and the shop-supplies line (10% of labour) before you say "Approved".
  - Approving by text or phone counts under CT's own form.
  - Collect stored tires within 8 months. CT's terms let it dispose of tires left 30 days past the term.

---

## 10. PRICES: the fixed basket (D1), canadiantire.ca API, 4 Oct 2026 14:24 UTC

**Stores** (selected via CT's own store API; nearest full-line store to each city centre):
- **150** Toronto, Yonge & Church: 839 Yonge St, M4W 2H2
- **302** Calgary Westhills: 5200 Richmond Rd SW, T3E 6M9
- **465** Halifax, Bayers Lake: 194 Chain Lake Dr, B3S 1C5
- **389** Vancouver, Cambie & 7th: 2290 Cambie St, V5Z 2T7

**Notes on the table:**
- Prices are **canadiantire.ca online prices with that store selected**. CT says in-store may differ (§7).
- "Sale to" is the API field `priceValidUntil`, exactly as returned in UTC ISO format. Treat it as the sale's last day. The on-site wording ("Sale ends …") was not captured.
- Eco fee = `feeValue` (type ECO_FEE), shown on site as "Plus $x Env. Fee" and **added on top of** the shelf price. Blank = none returned.
- **displayWasLabel = false on every row.**
- Unit prices are OUR NOTE arithmetic (price ÷ size), before eco fee and tax.

| # | Item (CT code) | Size | Toronto 150 | Calgary 302 | Halifax 465 | Vancouver 389 | Unit price (OUR NOTE) |
|---|---|---|---|---|---|---|---|
| 1 | Duracell Coppertop AA alkaline (0650024P) | 24-pk | **$19.99 SALE**, reg $25.99, to 2026-10-08; eco fee $2.88 | $19.99 SALE, reg $25.99, to 2026-10-07 | $19.99 SALE, reg $25.99, to 2026-10-07 | $19.99 SALE, reg $25.99, to 2026-10-08; eco $1.44 | $0.833/battery sale ($1.083 at reg) |
| 2 | Energizer Max AA alkaline (0651015P) | 20-pk | $19.99 reg; eco $2.40 | $19.99 reg | $19.99 reg | $19.99 reg; eco $1.20 | $1.00/battery |
| 3 | WD-40 Smart Straw Multi-Purpose (0381571P) | 325 g | **$10.99 SALE, reg $12.99**, to 2026-10-15 | $10.99 SALE, reg $12.99, to 2026-10-14 | **$9.99 SALE, reg $11.99**, to 2026-10-14 | $9.99 SALE, reg $11.99, to 2026-10-15; eco $0.20 | $3.38/100 g (Tor/Cal); $3.07/100 g (Hfx/Van) |
| 4 | Mobil 1 5W30 Synthetic, MPN 124483 (0289450P) | 4.73 L | $49.99 reg | $49.99 reg | $49.99 reg | $49.99 reg; eco $1.18 | $10.57/L |
| 5 | Castrol EDGE 5W30 Adv. Synthetic, MPN 2011-3A (0289212P) | 5 L | $54.99 reg | $54.99 reg | $54.99 reg | $54.99 reg; eco $1.25 | $11.00/L |
| 6 | Rain-X ClearView Winter Shield washer fluid −45 °C (0294130P) | 3.78 L | $7.49 SALE, reg $8.49, to 2026-10-08 | $7.49 SALE, reg $8.49, to 2026-10-07 | $7.49 SALE, reg $8.49, to 2026-10-07 | $7.49 SALE, reg $8.49, to 2026-10-08 | $1.98/L sale ($2.25 reg) |
| 7 | Coleman Propane Cylinder (0762021P) | 16-oz | $10.99 reg; eco $0.90 | $10.99 reg | $10.99 reg | $10.99 reg | $0.69/oz |
| 8 | Rubbermaid Roughneck Storage Box w/ Lid, blue (0422963P) | 68 L | **$17.99** reg | **$19.99** reg | $17.99 reg | $19.99 reg | $0.26/L vs $0.29/L |
| 9 | Lysol Disinfecting Wipes, Lavender & Cotton Blossom (1533442P) | 75 ct | $7.99 reg | $7.99 reg | $7.99 reg | $7.99 reg | $0.107/wipe |
| 10 | DEWALT DCK240C2 20V MAX drill/impact combo (0542320P) | kit | $229.99 reg | $229.99 reg | $229.99 reg | $229.99 reg; eco $0.80 | n/a |
| 11 | Ninja single-basket air fryer, model AF100C (0430348P) | 4-qt | $129.99 reg | $129.99 reg | $129.99 reg | $129.99 reg; eco $1.35 | n/a |
| 12 | PEAK Blue DEF Platinum diesel exhaust fluid (0290018P) | 9.46 L | $29.99 reg | $29.99 reg | $29.99 reg | $29.99 reg | $3.17/L |
| **Basket total (shelf prices, 12 items)** | | | **$590.38** | **$592.38** | **$589.38** | **$591.38** | |
| **+ eco fees returned** | | | +$6.18 = $596.56 | +$0 = $592.38 | +$0 = $589.38 | +$7.42 = $598.80 | |
| **Basket at "regular" prices** | | | $599.38 | $601.38 | $598.38 | $600.38 | |

**Extra SKUs captured (same method):**

| Item (CT code) | Size | Toronto 150 | Calgary 302 | Halifax 465 | Vancouver 389 | Unit |
|---|---|---|---|---|---|---|
| Certified All-Season washer fluid −35 °C (0294199P), CT house brand | 3.78 L | $5.99 reg | $5.99 | $5.99 | $5.99 | $1.58/L |
| Reflex All Season washer fluid −45 °C (0290005P) | 3.78 L | $6.69 SALE, reg $7.49, to 10-08 | $6.69 to 10-07 | $6.69 to 10-07 | $6.69 to 10-08 | $1.77/L |
| DEWALT DCK277D2 brushless drill/impact combo (0547273P) | kit | **$199.99 SALE, reg $299.99, "Save 33% ($100.00)", to 2026-10-22** | $199.99, to 10-14 | $199.99, to 10-14 | $199.99, to 10-22; eco $0.80 | n/a |
| DEWALT DCK477D2 4-tool combo (0546716P) | kit | **$399.99 SALE, reg $649.99, "Save 38% ($250.00)", to 2026-10-08** | $399.99, to 10-07 | $399.99, to 10-07 | $399.99, to 10-08; eco $3.20 | n/a |
| Mastercraft 20V drill/driver + 76-pc kit (0548737P), CT house brand | kit | $69.99 SALE, reg $129.99, "Save 46% ($60.00)", to 10-15 | n/c | $69.99, to 10-14 | n/c | n/a |

(n/c = not captured.)

**Eco-fee text (D1, pricing API), verbatim:** "What is an environmental Fee? Sometimes called an Eco Fee, is a fee collected by manufacturers and retails to help fund recycling programs that divert potentially hazardous items, such as fire exinguishers, household cleaners, and paint, from landfills." (Spelling as on CT.) Label: "Plus $x Env. Fee".

**OUR NOTE (price observations, all from CT's own data):**
1. The 12-item basket varied by only **$3.00** across the four cities on shelf price ($589.38–$592.38). The differences come from WD-40 (−$1 in Halifax and Vancouver) and Rubbermaid (+$2 in Calgary and Vancouver).
2. **Eco fees** changed the comparison: +$6.18 in Toronto and +$7.42 in Vancouver, with none returned in Calgary or Halifax. Example: Duracell 24-pk = $19.99 + $2.88 in Toronto, which is 14.4% on top of the sale price. Eco fees are set under provincial stewardship programs. **We have not verified the provincial basis, so don't comment on legality** (see DO-NOT-USE).
3. **Sale windows differ by region.** The Toronto and Vancouver flyer week ends a day later (Oct 8) than Calgary and Halifax (Oct 7). DCK277D2's sale runs to Oct 22 in Toronto and Vancouver vs Oct 14 in Calgary and Halifax.
4. **The "regular" price for the same SKU differs by region** (WD-40, Rubbermaid). Each region's "Save X%" is computed against that region's own regular price: WD-40 is "Save 15%" in Toronto vs "Save 17%" in Halifax.

---

## 11. COMPETITOR COMPARISON (same model number only, unless marked "near-identical")

**Home Depot stores** (HD API, 4 Oct 2026 14:30–14:31 UTC): **7080** Gerrard Square, 1000 Gerrard St E, Toronto; **7037** Calgary North Hill, 1818 16th Ave NW; **7126** Halifax, 368 Lacewood Dr. HD returned **no promotion messages and no "was" price** on any of these items. Its price was identical in all three cities.

### A. Same model number (on-air usable with dates and stores)

| Model | Canadian Tire (website, 4 Oct) | Home Depot (7080 / 7037 / 7126) | Amazon.ca | Princess Auto |
|---|---|---|---|---|
| **DEWALT DCK240C2** 20V MAX 2-tool combo (2 × 1.3 Ah per HD title) | $229.99 regular, all 4 stores | **$229.00** all three (online stock 21; store stock 0 at all three) | **$229.00**, ASIN B00IJ0ALYS; page shows "Item model number DCK240C2"; ships from / sold by "Amazon.ca" | not found |
| **DEWALT DCK277D2** 20V MAX brushless 2-tool combo (2 × 2 Ah) | **$199.99 SALE**, "Save 33% ($100.00)" vs reg **$299.99**, all 4 stores; sale to 10-22 (Tor/Van) or 10-14 (Cal/Hfx) | **$198.00** all three | **$198.00**, ASIN B0C3PQHGR7 (title ends "(DCK277D2)"; ships from / sold by Amazon.ca) | not found |
| **DEWALT DCK477D2** 20V MAX 4-tool combo | **$399.99 SALE**, "Save 38% ($250.00)" vs reg **$649.99**, all 4; to 10-08 (Tor/Van) or 10-07 (Cal/Hfx) | **$398.00** all three | not found (the $398 result B0CKKK1RGV is **DCK427D2**, a different model; excluded) | not found |
| **Castrol EDGE 5W30, 5 L**: CT MPN "2011-3A"; HD model "02011-3A", named "EDGE SPT 5w30 5L SYNTHETIC OIL" | $54.99 regular, all 4 | **$89.98** all three (store stock 0 at all three) | not captured | not found |
| **Ninja AF100C** 4-qt air fryer | $129.99 regular, all 4 | HD sells **AF101C** (different model, $149.99); no AF100C | $129.99 on ASIN B0828CHKG3, but the page's merchant block says "**Sold by Warehouse Deals**", a used/open-box seller, so **not comparable** | not found |

**OUR NOTE:**
- **DCK240C2:** CT is **$0.99 higher** than HD and Amazon.ca.
- **DCK277D2:** CT's sale price is **$1.99 above** HD's and Amazon's everyday price. CT's stated regular price ($299.99) is **$101.99 (51.5%) above** HD's everyday $198.00.
- **DCK477D2:** CT's sale is **$1.99 above** HD. CT's regular ($649.99) is **$251.99 (63.3%) above** HD's $398.00.
- **Castrol EDGE 5 L:** HD's listed price is $35 (64%) higher than CT's. The names differ ("EDGE" vs "EDGE SPT") and HD's part number has a leading zero, so verify it is the same jug before using.
- **Framing (rule 4).** State these as observed prices on a date: "On October 4th, the same DeWalt kit was $199.99 on sale at Canadian Tire and $198 at Home Depot and Amazon." **Do not** say or imply that CT's regular price is false or not genuine. We don't have CT's sales volumes or price history, and the law's tests turn on those (L1, L2).

### B. Near-identical (same brand, product line and size; CT shows no model number), NOT for on-air head-to-head

| Item | CT Toronto 150 | HD 7080 (same at 7037, 7126) | Princess Auto (national online) | Amazon.ca |
|---|---|---|---|---|
| Duracell Coppertop AA 24-pk | $19.99 SALE (reg $25.99) + $2.88 eco | $27.98 (HD model "5001530") | not Duracell (Powerfist 24-pk $12.99), so no match | search returned no parsable results |
| Energizer Max AA 20-pk | $19.99 + $2.40 eco | $20.98 (model E91LP-20) | n/a | not captured |
| WD-40 Smart Straw 325 g | $10.99 SALE (reg $12.99) | $10.98 (model 02272, "Original Formula… Smart Straw, 325g") | **$11.99** list (PA0009042763, brand WD-40) | 325 g listings had no clean single-unit price |
| Rain-X ClearView Winter Shield −45 °C 3.78 L | $7.49 SALE (reg $8.49) | $8.48 (model 35-444RX) | n/a | n/a |

### C. Not matched
- Mobil 1 5W30 4.73 L (CT MPN 124483): Amazon.ca lists U.S. part numbers (120764, 5 qt), so no match.
- Coleman 16-oz cylinder: HD sells Bernzomatic. PEAK DEF: HD and PA sell other brands. Rubbermaid Roughneck 68 L: no HD or Amazon match captured. Lysol 75-ct: HD count not shown.

### D. Blocked or failed
- **Walmart.ca:** bot wall, as described in §0. No prices.
- **Princess Auto** carries none of the DeWalt or Castrol models.

---

## 12. SUGGESTED SCRIPT BEATS from this dossier (all label-safe)

1. **"There's no price match on the books."** CT's policy list contains none, and its pricing policy says Dealers "may sell for less" (P1, P10). *Fix:* ask your store, and bring the competitor ad.
2. **"Your refund card has a clock."** Refund Cards expire after one year, except in Saskatchewan; gift cards don't (P1, P2).
3. **"CT Money is 0.4%."** That is $4 per $1,000 (T1, API), and it can expire after 18 months of no activity (T1). Paper CTM hasn't been issued since March 21, 2020, and its own rules say "no time limits" (T6).
4. **"Do the Triangle Select maths."** $89 a year, non-refundable outside Quebec, auto-renews. Break-even is $2,225 in-store spend on the 10x bonus alone, or $975 if you value the $50 gift (OUR NOTE).
5. **"Regular price depends on where you live."** WD-40 is $12.99 regular in Toronto vs $11.99 in Halifax on the same day. Sale end dates differ by a day (D1). CTC's AIF: Dealers sell "at prices not exceeding those set by the Company" (F1).
6. **"The sale price vs the competitor's everyday price."** DeWalt DCK277D2: CT $199.99 "Save 33%"; HD and Amazon.ca $198.00, Oct 4 (D1–D3). Observation only, no inference.
7. **"Quebec's guilty plea."** 74 counts, $1,287,550, 5 products, April–October 2021. Carry CT's statement: "no customers were overcharged and the matter is now concluded" (Q1, N1). Keep it apart from beat 6.
8. **"Eco fees go on top."** Duracell 24-pk: $19.99 + $2.88 in Toronto (D1).
9. **"Before you say 'Approved' at the garage."** Estimate rules, 10% shop supplies, the lien, and the 8-month tire storage plus 30-day disposal (P1).
10. **"Quebec: the law gives you a warranty first."** s.228.1 notice duty (Q3), and the new 3–6-year good-working-order warranty from Oct 5, 2026 (Q2).
11. **The Scanner Price Accuracy Code:** look for the sign (N2).

---

## APPENDIX R: RECALLS (DO NOT USE ON AIR)

- CT links to a recall list at https://corp.canadiantire.ca/English/media/product-recalls/default.aspx (P2). It was not opened or analysed for this dossier.
- Per house rule 1, no recall content is in scope.

---

## UNVERIFIED / DO-NOT-USE

1. **Price match ended "August 5, 2022".** Tier c only (RedFlagDeals threads, Flipp blog, LoansCanada). DO NOT USE the date. Say only that no price-match policy appears in CT's current policies.
2. **"Canadian Tire no longer participating in the scanner price accuracy code"** (RedFlagDeals thread title). Tier c, undated. DO NOT USE.
3. **Triangle pages (T2–T5) are WebFetch model extracts, not raw text.** Quotes may differ in punctuation or wording. **Screenshot the live pages before quoting on air.** This covers the $89 price, the benefit wording, the $12 reimbursement cap, the auto-renew exceptions and the "no cap" on 10x.
4. **"No cap on the 10x Triangle Select bonus."** Unverified: the extract may have missed small print.
5. **T1 Triangle T&C PDF** was last modified 30 Nov 2023 per metadata, and **may not be the current version**. The 18-month rule is corroborated by T2 (extract) only.
6. **e-CTM expiry notice "30–60 days before expiry"** appears in third-party summaries only. Not found in T1. DO NOT USE.
7. **$99 Free Local Shipping threshold** is from the store API field `subsidizedSTH.threshold: 99`, not on-page text. Verify in the site header first.
8. **`isFreeStorePickup: false`** on all four stores. Meaning unclear (fee `null`, threshold 0). DO NOT interpret as "pickup costs money".
9. **Same-day delivery radius:** 15 km (online-ordering page) vs 10 km (site footer), a CT inconsistency. If used, quote both with source; don't call it misleading.
10. **`priceValidUntil` timestamps** are UTC ("…T23:59:59.000Z" or "…T00:00:00.000Z"). How these map to local "sale ends" dates on-screen was not verified. Use dates, not times.
11. **"STORESPECIAL" badge** meaning unverified.
12. **Store API `address.firstName` field** contains a person's name for each store (e.g., store 150). It is presumably the Associate Dealer, but the field's meaning is unconfirmed, and these are private individuals. **DO NOT USE names.**
13. **CT `vendorName` field** in product data (e.g., the vendor of record on the CT house-brand "Certified" washer fluid). **DO NOT USE. Rule 7: never infer a manufacturer or supplier from vendor-of-record data.** The same applies to the P7 Quebec brand-to-company list.
14. **Castrol EDGE HD $89.98 vs CT $54.99.** The part numbers differ by a leading zero ("2011-3A" vs "02011-3A") and HD calls it "EDGE SPT". Store stock was 0 at all three HD stores. Verify it is the same product before using.
15. **Ninja AF100C on Amazon.ca at $129.99** was sold by "Warehouse Deals" (used/open-box) per page block. Not comparable. DO NOT USE.
16. **Near-identical comparisons (§11B)**: Duracell, Energizer, WD-40, Rain-X. CT shows no model number or UPC. Not for on-air head-to-head unless verified on pack or UPC.
17. **Eco fees.** The legal basis per province (and whether CT's display meets s.74.01(1.1)) is **not analysed**. DO NOT imply any non-compliance. Calgary and Halifax returned no fee value; don't state "no eco fee in Alberta/Nova Scotia" without checking checkout.
18. **The DeWalt regular-price comparisons (§11A)** are observations only. **DO NOT** say or imply CT's "regular" or "Save" prices are false, inflated or "fake", or link them to the OPC 2021 case (which also involved "une perceuse sans fil Dewalt"). Rules 4 and 6.
19. **Competition Bureau case history.** "No CTC ordinary-price case found" is a search result, not proof. Say "we found no Competition Bureau case" only with that wording.
20. **Refund-card expiry legality** (e.g., Ontario or other gift-card statutes) is not analysed. DO NOT comment on legality.
21. **Gas+ redemption.** P5 says you cannot redeem CT Money at Gas+/Petro-Canada. The brief's assumption that CTC "owns Gas+" holds per F1, but **over 200 Gas+ sites are planned to become Petro-Canada-branded** (F1). Don't present Gas+ as a stable banner.
22. **Walmart.ca prices: none captured** (blocked). Do not claim any Walmart comparison.
23. **Global News, Globe and Mail and other coverage of Triangle changes** beyond N3 was not opened. N3 is a WebFetch extract; the "more than three times the subscription fee" quote needs a screenshot of the article.
24. **Auto-service labour rates, tire installation and storage prices** are not published online. Any figure from forums or YouTube is tier c. DO NOT USE.

**unverified_count = 24**

---

# DOSSIER: Canadian Tire: what it genuinely gets right (positives + survey record)

For: "Why Some Canadians Are Refusing to Shop At Canadian Tire Anymore" (airs Oct 6, 2026), segment "3 things Canadian Tire genuinely gets right" plus scene-setting.
Compiled: Oct 4, 2026. Every source below was opened Oct 4, 2026 unless another date is given. Raw captures are in `scratchpad/ct/`, with file names given per source.
House rules applied: no health, safety, recall or product-quality claims. Corporate claims are quoted verbatim and attributed. Outcome labels are exact. No U.S. figure is presented as Canadian. We never say "we tested", "bought" or "visited".

---

## 0. VERDICT AND RECOMMENDED "3 THINGS THEY GET RIGHT"

**Verdict:** Usable, with catches. Three positives hold up on primary sources, and each one has a catch that is also documented. Two of the suggested positives do **not** hold up and should be dropped:
- **Price match.** Canadian Tire's policy pages, read Oct 4, 2026, describe no competitor price-match policy. The claim that it "ended Aug 2022" exists only on deal blogs and forums, which are tier c.
- **"Returns or warranties that beat competitors".** Not supported. Canadian Tire's 90 days matches Home Depot's 90 days. Home Depot gives 365 days on online purchases made with its own cards. Princess Auto's written guarantee is broader.

| # | Positive (recommended order on air) | The good part (sourced) | The catch (sourced) |
|---|---|---|---|
| 3 | **The loyalty money is real money** (Triangle Rewards / CT Money) | CT Money redeems "$1 for $1", "Redeem Anytime, Any Amount". No-fee Triangle Mastercard earns "4% CT Money" at CTC banners. Canadian Tire calls paper CT Money (1958) "Canada's oldest loyalty program". | Base rate without the card is **0.4%**, which is 40¢ per $100 (OUR NOTE). The card's purchase rate is 21.99%. eCTM can expire after **18 months** of inactivity. Paper CT Money issuance stopped in 2020 (see U9). |
| 2 | **Jumpstart: the charity money is large and audited** | Jumpstart site: "$329 MILLION+" invested, "4.5 MILLION+ KIDS" helped "since 2005". Audited 2025 statements (Deloitte, signed Feb 23, 2026): $31.17M revenue, $30.43M program disbursements. FAQ: CTC "funds all of our general administrative expenses, allowing 100% of customer donations to go directly toward supporting kids in need." | In 2024, **customers gave more than the corporation**: $9.83M (34.8%) against CTC's $6.35M (22.5%), per Jumpstart's 2024 Annual Report. Jumpstart's FAQ says individual child grants are "no longer available in some communities", with a maximum of $300 per child per year (2026). |
| 1 | **Canadian-controlled and locally run** (Billes family and Associate Dealers) | AIF 2025: founded "in 1922 by brothers A.J. and J.W. Billes". Martha Billes and Owen Billes control 61.4% of the voting Common Shares. All 502 Canadian Tire stores are run by Dealers, who "own the fixtures, equipment and inventory", "employ the store staff". CEO in 2025: "Some things are just meant to stay Canadian" (HBC Stripes purchase). | Canadian-owned does not mean Canadian-made. AIF 2025: "approximately 50 percent of Canadian Tire Retail … inventory purchases were sourced directly from vendors outside Canada, primarily from Asia". Dealers buy "primarily from CTC" and sell "at prices not exceeding those set by the Company". |

**Alternates, if one of the three fails producer review:**
- **Tire Care Guarantee:** free repair of road-hazard damage on tires bought and installed at Canadian Tire. Catch: pro-rated replacement, a long exclusions list, and a 6-year limit.
- **Loan-A-Tool:** a deposit you get back in full. Catch: "select stores".
- **The facial-recognition ban:** CTC and its Dealers have "mutually agreed to prohibit" the technology. Catch: it followed a BC privacy commissioner finding (2023).
- **Bikes:** "Free tune up within 30 days with proof of purchase". Catch: "Bikes cannot be returned."

**Scene-setting and survey hook:** Leger's ranking of Canada's most reputable companies put Canadian Tire **3rd in 2024, 5th in 2025 and 7th in 2026**. It is still top-10, but it has dropped two places each year. (Tier d. Leger's own pages and named coverage are in §4.)

---

## 1. POSITIVE A: TRIANGLE REWARDS / CANADIAN TIRE MONEY

### 1.1 What CTC says (tier a, company pages)
- **Triangle Rewards home** (https://triangle.canadiantire.ca/en.html; capture `ct_triangle.md`):
  - "Every dollar earned in CT Money is $1 that you can redeem at any of your favourite stores."
  - "Redeem Anytime, Any Amount†"
  - Base-rate footnote: "Any bonus multiplier is based on the base rate of collecting CT Money (0.4%) … Example: On a $100 (pre-tax) purchase with a 20X bonus multiplier a Member would earn a bonus $8 in CT Money (20 X .4% X $100)."
  - Membership benefit: "Return products at Canadian Tire, Sport Chek, Mark's, L'Équipeur and Atmosphere stores without a paper receipt."
  - RBC link: "you'll earn 3x the CT Money® on qualifying purchases" when an eligible RBC debit or credit card is linked.
- **Loyalty / compare-cards page** (https://triangle.canadiantire.ca/en/loyalty.html and /en/credit-cards.html; captures `tr_loyalty.md`, `tr_cards.md`). Table, verbatim cells:
  - Triangle Rewards card: "Earn 0.4% CT Money† on qualifying purchases at Canadian Tire, Sport Chek, Mark's, L'Équipeur, Atmosphere, Party City, Pro Hockey Life…"; fuel "3ȼ (per litre) when you pay with cash/debit".
  - Triangle Mastercard: "$0 No Annual Fee"; "Purchase Rateƒ: 21.99%"; "Earn 4% CT Money†" at those banners; "5ȼ (per litre)"; "Earn 1.5% CT Money at Grocery Stores (on the first $12,000 per year; excludes Costco and Walmart)"; "Earn 0.5% CT Money Everywhere Else†".
  - Triangle World Elite Mastercard: "$80,000 annual income or $150,000 household income"; "Earn 4% CT Money†"; "Collect 7¢ per litre in CT Money on premium fuel, and 5¢ per litre on all other fuel types"; "Earn 3% CT Money at Grocery Stores"; "Earn 1% CT Money Everywhere Else†".
  - "There is no annual fee with the Triangle Mastercard or Triangle World Elite Mastercard."
- **Program rules** (https://triangle.canadiantire.ca/en/support/legal-and-privacy/program-rules.html; capture `tr_rules.md`). No "last updated" date is shown on the page.
  - "We may expire the eCTM in your Triangle Rewards Account in the event that there has been a period of inactivity of 18 months or more."
  - "The rate at which eCTM can be collected may vary from time to time and by location and is subject to change by Canadian Tire without notice."
  - "eCTM is not exchangeable and cannot be redeemed for cash".
  - "individual Canadian Tire stores may exclude additional items sold in that store from being Eligible Merchandise."
  - "Termination or cancellation of membership in the Program will result in the immediate closing of the Member's Triangle Rewards Account and the cancellation of all eCTM in such Triangle Rewards Account without any compensation".
- **Triangle Select** (https://triangle.canadiantire.ca/en/triangle-select.html; capture `tr_select.md`): "Only $89 per year"; "Earn 10x bonus CT Money on almost all in-store purchases at Canadian Tire, Sport Chek, Mark's…"; "Welcome Gift (valued at $50, new members only)". The fee was shown on the national Triangle site on Oct 4, 2026. No store-level price applies.
- **CTC corporate Triangle page** (https://corp.canadiantire.ca/English/about-us/triangle/default.aspx; capture `corp_triangle.md`). Undated.
  - "Paper Canadian Tire Money began circulating in 1958, making it Canada's oldest loyalty program. Since then, over 1 billion Canadian Tire Money notes have been produced."
  - "Conceived by Muriel Billes, wife of Canadian Tire co-founder A.J. Billes, the coupons featured a happy tire and dollar sign running hand-in-hand".
  - "Canadian Tire Money is so deeply rooted in Canadian heritage that it is even included in the Oxford English Dictionary." (CTC claim. Not independently checked; see U10.)
- **AIF 2025** (CTC, dated Feb 18, 2026; https://s201.q4cdn.com/326551073/files/doc_financials/2025/ar/AIF-EN.pdf; capture `ctc_aif2025.txt`):
  - "Triangle Rewards, with 12.2 million active members, and a credit card portfolio with 2.3 million active credit cardholders."
  - "Since the launch of the Triangle Rewards program in 2018…"
- **Q2 2026 results release** (CTC, quarter ended Jul 4, 2026; capture `corp_q2_2026.md`):
  - "Loyalty sales were up 3.1%, continuing to outpace non-loyalty sales, as members active in the program grew. CTC extended its Triangle Rewards member benefits to include free ship-to-home on CTR eCommerce orders."
  - Hicks: "we demonstrated our operational agility by lowering prices for value-seeking customers".
  - Catch on the shipping perk, from CT's online-ordering page (`ct_online.md`): "Registered Triangle Rewards Members can enjoy Free Local Shipping on eligible orders above a certain pre-tax order spend at select stores." and "Your order must hit the minimum pre-tax order spend, which may vary by store."

### 1.2 Named outlet (tier b)
- Global News, Ariel Rabinovitch, Feb 19, 2026, "Canadian Tire says Triangle Rewards are its 'linchpin' for growth" (https://globalnews.ca/news/11674468/canadian-tire-earnings-loyalty-program/). It quotes CTC: "Triangle Rewards tied everything together … with membership up and active registered members growing six per cent to 9.8 million."
  - **Conflict:** this "active registered members" figure (9.8M) differs from the AIF's "12.2 million active members". See U8. On air, say "about 12 million members", which is the CTC boilerplate, or name the definition you use.

### 1.3 OUR NOTE (our arithmetic, using CTC's own rates)
- Card-free member: $100 pre-tax at Canadian Tire × 0.4% = **$0.40** in CT Money.
- Triangle Mastercard at a CTC banner: $100 × 4% = **$4.00**.
- Fuel, 50 L fill: cash or debit with Triangle at 3¢/L = **$1.50**; Triangle credit card at 5¢/L = **$2.50**; World Elite on premium at 7¢/L = **$3.50**. Rates "could vary by location".
- Triangle Select at $89/yr: the 10x bonus is 10 × 0.4% = 4% extra. Break-even on the bonus alone is $89 ÷ 4% = **$2,225** of pre-tax in-store spending a year. In the first year, counting the $50 welcome gift at face value, it is ($89 − $50) ÷ 4% = **$975**.
- Carrying a balance: CTC's own disclosure example (Quebec residents' table on canadiantire.ca) gives **$9.04 a month** in interest on a $500 average balance at 21.99%. That is $108.48 a year, which equals the 4% CT Money on **$2,712** of spending at its stores.

### 1.4 Draft on-air line (compliant)
> "Canadian Tire Money is the real thing. Canadian Tire calls it Canada's oldest loyalty program, and every dollar of it spends like a dollar in its stores. But read the rate. Without the store's credit card, the base is zero point four percent. That's forty cents on a hundred-dollar shop. The card gets you four percent. But at a twenty-one ninety-nine percent purchase rate, one carried balance can eat that. And if you don't earn or spend for eighteen months, Canadian Tire's rules say it may expire your balance."

---

## 2. POSITIVE B: JUMPSTART (charity; no health framing)

### 2.1 Jumpstart's own pages (tier a)
- https://jumpstart.canadiantire.ca/pages/about (capture `js_about.html`):
  - "Since 2005, our commitment has translated into measurable impact"
  - "Invested $329 MILLION+ in community sport and play initiatives"
  - "Helped 4.5 MILLION+ KIDS access sport and play through Jumpstart since 2005"
  - "Certified over 1,800 COMMUNITY PARTNERS"
  - "Developed 56 INCLUSIVE PLAY SPACES spanning 618,000+ square feet nationwide"
  - "Charitable Business Number: 13792 9451 RR0002"
- FAQ, https://jumpstart.canadiantire.ca/pages/faq (capture `js_faq.html`):
  - "Canadian Tire Corporation is our biggest supporter, as it funds all of our general administrative expenses, allowing 100% of customer donations to go directly toward supporting kids in need."
  - "Vendors from Canadian Tire Corporation are also key supporters and funders of Jumpstart. The Government of Canada and several provincial governments also provide grants…"
  - "As of 2026, the maximum amount per child per year is $300, subject to chapter discretion and/or local demands."
  - "In some regions, this means Individual Child Grants are no longer available."
  - "All funds raised within a community will continue to support impactful initiatives in that same community."
  - **Do not quote** the FAQ phrase "healthy and active living". House rule 1.

### 2.2 Audited financial statements, year ended Dec 31, 2025 (tier a; Deloitte LLP, report dated Feb 23, 2026; capture `js_fs2025.pdf/.txt`)
URL: https://cdn.shopify.com/s/files/1/0122/8124/9892/files/2025_Audited_Financial_Statements_EN.pdf
- Revenue line: "Canadian Tire Corporation, Limited and related donors including employees, vendors, dealers, and customers": **$25,379,676** (2024: $24,438,942). Federal grants $2,667,502; provincial grants $1,528,745. Total revenue **$31,170,862**.
- Disbursements:
  - "Canadian Tire Jumpstart Program for kids in financial need": $24,669,508;
  - "Inclusive Play Program": $3,859,544;
  - "program delivery": $1,898,045;
  - total charitable disbursements **$30,427,097**.
- "General and administrative expenses": **$2,250,131**. "(Deficiency) excess of revenue over disbursements": **($1,569,863)**.
- Note 8: "During the year, CTC incurred costs of $10.08 million ($1.97 million in 2024) for advertising that may also have benefited Jumpstart Charities for which no amounts have been recorded in these financial statements." The same note covers CTC's $0.55M for "benefits, travel and office space" and a $10.0M CTC loan facility, with a $0 balance.
- Auditor's opinion is **qualified** for the standard charity reason: "In common with many not-for-profit organizations, the Organization derives revenue from the public in the form of donations, the completeness of which is not susceptible to satisfactory audit verification." This is not a finding of wrongdoing. Do not use it on air.
- Note 1: incorporated "November 20, 1992"; "registered charity".

### 2.3 Jumpstart 2024 Annual Report (tier a; capture `js_ar2024.txt`), "2024 Revenue Sources", in thousands of $, total 28,240

| Source | Amount | Share |
|---|---|---|
| Canadian Tire family of companies customers | 9,831 | 35% |
| Canadian Tire Corporation | 6,354 | 22% |
| CT family vendors | 3,966 | 14% |
| CT Associate Dealers | 2,309 | 8% |
| CTC employees | 863 | 3% |
| Federal and provincial government | 2,134 | 8% |
| Other | 2,783 | 10% |

- Also: "G&A Ratio 7.73%" (2024) and "nearly 4 million kids we've supported since 2005". The report's "social value of $143 million" is a modelled figure. Do not use it (U15).

### 2.4 OUR NOTE
- Shares were recomputed from the table: customers 34.8%, CTC 22.5%. Customers plus vendors plus Dealers plus employees = $16.97M, or **60.1%** of 2024 revenue. On that basis, customers gave about **$1.55 for every $1** the corporation gave in 2024 (9,831 ÷ 6,354).
- 2025: program disbursements were 93.1% of total spending ($30.43M ÷ $32.68M), and G&A was 6.9%.
- The 2025 statements put CTC and its donor groups on one line, so the 2025 split by source is not shown there. Use the 2024 annual report table for the split.

### 2.5 Draft on-air line
> "Jumpstart, Canadian Tire's charity, says it has put more than three hundred and twenty-nine million dollars into kids' sport and play since 2005. Its audited statements for last year show about thirty million dollars going out the door to programs. Jumpstart says the corporation pays its administrative costs, so customer donations go to kids. Here's the part most people don't know. In 2024, Jumpstart's own report shows customers gave nine point eight million dollars. The corporation gave six point four. A lot of that generosity is yours, collected at the till."

---

## 3. POSITIVE C: CANADIAN-CONTROLLED, LOCALLY RUN (identity and the dealer model)

### 3.1 CTC filings and pages (tier a)
- AIF 2025 (Feb 18, 2026), §2:
  - "Starting from a single garage established in 1922 by brothers A.J. and J.W. Billes, CTC has grown to one of the country's most recognized brands".
  - §1: "incorporated under the laws of Ontario by letters patent dated December 1, 1927".
- AIF §8.3: "Through two privately held companies, Tire 'N' Me Pty. Ltd. and Albikin Management Inc, Martha Billes and Owen Billes beneficially own, control or direct, in aggregate, 2,101,150 Common Shares of CTC". The same section gives the group's holding of Common Shares as "representing 61.4% of the issued and outstanding Common Shares". Class A shares are "Non-Voting".
- AIF §2.1, Dealers:
  - "Canadian Tire's 502 stores are operated by Dealers, who are independent third parties that own the fixtures, equipment and inventory of the stores they operate, employ the store staff, and are responsible for store operating expenses."
  - Catch, same paragraph: "Each Dealer agrees to comply with prescribed policies … include purchasing merchandise primarily from CTC, while maintaining the decision-making behind customizing their assortments to meet the demands of the communities in which they operate, and offering merchandise for sale to consumers at prices not exceeding those set by the Company."
  - The AIF counts "502 stores" but a contract with each of "483 Dealers" (§2.5).
- AIF §2.1, Retail Sourcing (**the catch**): "In 2025, approximately 50 percent of Canadian Tire Retail, 33 percent of Mark's, and 21 percent of SportChek inventory purchases were sourced directly from vendors outside Canada, primarily from Asia, and denominated in U.S. dollars. CTC operates retail sourcing offices abroad, including in Bangladesh, Hong Kong, Vietnam and China."
- AIF §3.1 (2025 developments): "completed the sale of the Helly Hansen business to Kontoor Brands, Inc. for approximately $1.3 billion, reflecting the Company's increasing focus on its Canadian retail portfolio."
- canadiantire.ca pricing policy (capture `ct_pricing.md`):
  - "Canadian Tire Associate Dealers may sell for less."
  - The site footer adds: "Online prices and sale effective dates may differ from those in-store and may vary by region. Dealers may sell for less."
- CTC release, May 15, 2025 (HBC brand assets; capture `corp_hbc.md`). Hicks: "Some things are just meant to stay Canadian and we are honoured to welcome many of HBC's leading brands – including the iconic HBC coat of arms and the Stripes – into our Canadian Tire family." Also: "This choice feels as strategic as it feels patriotic." Price "$30 million".
- CTC boilerplate, same release: "has been a proudly Canadian business since 1922."

### 3.2 Named outlets (tier b)
- Tara Deschamps, The Canadian Press, via Global News, Feb 13, 2025, "Tariff threats 'substantially erased' economic rebound: Canadian Tire CEO" (https://globalnews.ca/news/11017812/...; capture `gn_tariff_2025.md`):
  - "Canadian Tire purchases about 15 per cent of its goods from the U.S."
  - "The company figures it could find Canadian suppliers for between 25 and 30 per cent of the items it gets from the U.S."
  - Hicks: "If you think about anything that kind of goes into a bag or a bottle, it's likely that is a Canadian supplier."
  - Hicks: "We have already begun to try to insulate our customers from the risk of higher trade costs hitting our shelves."
  - Note: the 15% is a CP paraphrase. Attribute it to CP, not to a filing.
- Sophia Harris, CBC News, Jun 3, 2025: court approved the HBC IP sale to Canadian Tire "for $30 million". This is a court approval, not a finding about any party.

### 3.3 OUR NOTE
- 502 stores and 483 Dealers means at least 19 more stores than Dealers. Some Dealers run more than one store.
- The "Canadian" claim is about **control**: the Billes family holds a majority of the voting shares, and the stores are locally operated. On the **goods**, CTC's own AIF says about half of Canadian Tire Retail's inventory purchases come directly from outside Canada, mainly Asia. Do not imply the products are Canadian-made (house rule 7: never infer a manufacturer).

### 3.4 Draft on-air line
> "Canadian Tire is still Canadian-controlled. Its filing says the Billes family, whose founders started with one garage in 1922, controls sixty-one percent of the voting shares. And every one of its five hundred and two stores is run by a local Dealer who owns the inventory and employs the staff. But Canadian-owned isn't the same as Canadian-made. The same filing says about half of what Canadian Tire Retail bought last year came directly from suppliers outside Canada, mostly in Asia. The fix is the same as it is everywhere: read the country of origin on the box."

---

## 4. NAMED SURVEYS ON CANADIAN TIRE'S REPUTATION AND TRUST (tier d)

| Survey (publisher) | Year / edition | Canadian Tire result | Method / sample / dates | Source and tier |
|---|---|---|---|---|
| Leger, Reputation study | 2026 (29th) | **#7** in "Reputation 2026 Canada Ranking" (1 Dollarama, 2 Samsung, 3 Costco, 4 Sony, 5 The Weather Network, 6 Toyota, **7 Canadian Tire**, 8 Lindt, 9 Google, 10 YouTube). Score not captured. | "roughly 38,600 Canadians surveyed between November and January"; 334 companies, 29 sectors; six pillars (Strategy). Strategy says "most reputable company in English Canada", so the scope may exclude Quebec (U7). | Leger page image alt text, https://leger360.com/reputation-study/ (`leger_rep.html`), tier a for the ranking. Strategy, Christopher Lombardo, Apr 20, 2026 (`strat_leger2026.md`), tier b. |
| Leger, Reputation | 2025 (28th) | **#5**, score 71; "Canadian Tire (+4): A steady performer, its alignment with national values continues to reinforce consumer trust." | "38,616 Canadians were surveyed … 326 companies in 30 different industries" | Retail Insider, Mario Toneguzzi, Apr 10, 2025 (`ri_leger2025.md`), tier b. CTC's own post (`ctc_leger2025.md`): "We are honoured to have earned the top spot among Canadian companies and 5th overall." |
| Leger, Reputation | 2024 | **#3**, score 71 | "more than 38,000 Canadians … close to 300 companies across 30 different sectors" | Retail Insider, Mario Toneguzzi, Apr 3, 2024 (`ri_leger2024.md`), tier b. CTC post: "Canadian Tire was ranked third overall … highest-ranked Canadian company on the list." |
| Leger, Reputation | 2023 (26th) | **#5**, score 70 | as Leger page | Leger, Apr 5, 2023 (`leger2023.md`), tier a |
| Morning Consult, Most Trusted Brands 2023 | 2023 | **No. 1 in Canada**, "Net Trust: 55.04"; "Canadian Tire in Canada … ousted … Tim Horton's" | "gathered March 3-April 3, 2023"; net trust = trust "a lot"/"some" minus "not much"/"not at all"; "Representative samples of 408 to 8,553 adults were gathered from each country"; online | Morning Consult report PDF (`mc2023.txt`), tier a/d. No Canada No. 1 found for 2024 or 2025 (U17). |
| Harris Poll Canada, "100 Most Canadian Brands" | Feb 2025 | **#1 "most Canadian" brand**, named by 39% (Tim Hortons 25%) | "1,483 Canadians were surveyed on February 6-7, 2025"; unaided, "up to FIVE brands", open-ended | Harris Poll page (method, `harris100.md`), tier d. 39% figure from Strategy, Feb 12, 2025 (`strat_harris.md`), byline not captured (U5). |
| Angus Reid Group (commercial, not the Institute), Canada-U.S. Relations 360 | Mar 2025 | "From the 10+ brands we tested, Starbucks emerges as the biggest loser so far in the 'Buy Canadian' movement. Canadian Tire is the biggest winner." | "n=3,300 Canadians selected from the Angus Reid Forum"; "completed the interviews between March 5-8, 2025"; online | https://www.angusreid.com/canada-us-relations-360/ (`arg_360.md`), tier d. No numbers published for CT (U6). |
| BrandSpark Most Trusted Awards | 2026 (13th; released Nov 20, 2025) | **Winner, "Tire Sales & Service (National)"**. Note the other way: "Retailer for Home Improvement: The Home Depot"; "Gas Loyalty Program: Petro-Points" | "45,394 Canadian shoppers … 240,033 brand evaluations across 363 categories"; unaided "single brand they trust most"; win = "statistically significant lead or … trust share exceeds 10%" | BrandSpark release PDF (`bs2026.txt`), tier d. BrandSpark says "Permission … required to reference a … win" (U20). |
| Ipsos, Most Influential Brands | 2025 (published Feb 11, 2026) | **Not in top 10** (Google, Amazon, YouTube, Apple, Facebook, Costco, Walmart, Visa, Netflix, Tim Hortons) | "6,700 Canadians", over 100 brands, eight dimensions | Ipsos release (WebFetch), tier d |
| Gustavson Brand Trust Index (UVic) | latest found: 2023 (9th) | **CT rank not verified** (U4). 2023: MEC and Costco tied #1. | "13,188 Canadian consumers … between January 10 and April 25, 2023"; 407 brands, 33 categories (Toyota Canada release) | Retail Insider, Toneguzzi, Jul 13, 2023; Toyota release. The UVic brand-trust URL now redirects to the Gustavson home page, so the index appears to have been discontinued (U4). |

**OUR NOTE (trend):** Leger rank by year: 2023 #5 → 2024 #3 → 2025 #5 → 2026 #7. Scores: 70 → 71 → 71 → not captured. The honest framing is "still top ten, but slipping since 2024". It is not a collapse.

**Draft on-air line:**
> "Here's a twist. Canadians still rate Canadian Tire. In Leger's 2026 reputation ranking it's seventh in the country. But it was third in 2024 and fifth in 2025. Still trusted, just less of a lock. And when Harris Poll asked fourteen hundred Canadians in February 2025 to name the most Canadian brand, Canadian Tire came first, ahead of Tim Hortons."

---

## 5. ALTERNATE POSITIVES (with catches)

### 5.1 Tire Care Guarantee (canadiantire.ca/en/customer-service/tires-warranty.html; tier a; `ct_tirewarranty.md`)
- "Tires that have been purchased and installed at Canadian Tire are backed by our complementary Tire Care Guarantee." [sic: "complementary"]
- Table: "Road Hazard Damage (ie. Nail punctures, pot hole damage) Yes"; "Repairable road hazard damage repaired for free Yes"; "Manufacturer defects repaired or replaced Pro-Rated" (standard plan).
- 30-day satisfaction return: "This program enables customers who have purchased tires to return their tires if they are not 100% satisfied with them. Customer must return within 30 days with their work order."
- Paid upgrade, "Replacement Advantage": "$9.99 for tires priced up to $149.99 each … $24.99 for tires priced over $300.00 each". These are national list fees on CT's site, Oct 4, 2026.
- **Catches:**
  - "Balancing, disposal fees and taxes are the responsibility of the tire owner."
  - Exclusions include "Tires returned more than six years after the purchase date", "Tires installed on a vehicle other than the original vehicle", and "Ride disturbance after one year or the first 2/32" of tread wear".
  - "Repair or replacement of the tires is the sole and exclusive remedy".
- This is a policy description. Say nothing about tire quality.

### 5.2 Loan-A-Tool (canadiantire.ca/en/automotive/loan-a-tool.html; tier a, read via WebFetch)
- "Put down a deposit on the loaner tool." "Return the tool in its original condition." "Receive a full refund" or "Just keep it: the deposit is your purchase price." "over 60 specialized tools."
- **Catch:** "Available in select stores". Deposit amounts and loan periods are not stated (U22).

### 5.3 Bikes and returns (canadiantire.ca/en/customer-service/returns.html; tier a; `ct_returns_jina.md`)
- "Bikes cannot be returned. Free tune up within 30 days with proof of purchase."
- General policy: "Unopened items in original packaging returned with a receipt within 90 days of purchase will receive a refund to the original method of payment or will receive an exchange. Items that are opened, damaged and/or not in resalable condition may not be eligible for a refund or exchange."
- "Receipt look-up enables Canadian Tire stores to verify credit or debit card purchases within 90 days".
- Shorter windows: "E-scooters and electronics … within 30 days"; "Auto electronics … within 14 days"; "Gas powered outdoor equipment … within 30 days … new, unused, and in its original packaging".
- Non-returnable includes "Clearance, final sale or AS-IS merchandise", "Tinted paint", "All infant & child Car Seats, Booster Seats, and Travel systems", "Tire Chains" (with a 3-day size exchange).
- Refund Cards: "Refund Cards will expire one year after the date of issue (except for those issued in the province of Saskatchewan)."

### 5.4 Returns compared with competitors (verbatim; tier a)

| Retailer | Standard window | Verbatim | Capture |
|---|---|---|---|
| Canadian Tire | 90 days, unopened, receipt | "Unopened items in original packaging returned with a receipt within 90 days of purchase will receive a refund…" | `ct_returns_jina.md` |
| Home Depot Canada | 90 days; 365 days for online purchases on HD cards | "Returns with a valid sales receipt within 90 days of purchase will be exchanged or refunded in the same tender as the original purchase." "If your online purchase was made with a The Home Depot Consumer Credit Card … you have 365 days from date of purchase". "Major appliances are non-returnable." | https://www.homedepot.ca/en/home/customer-support/return-policy.html (`hd_returns.md`) |
| Princess Auto | No day limit stated | "No sale is final until you're satisfied. We guarantee to make it right. We will repair, replace or refund any product to your satisfaction." "All ammunition sales are final." | https://www.princessauto.com/en/frequently-asked-questions (`pa_faq.md`) |
| Walmart Canada | 90 days (search snippet only) | Page blocked by a bot check, so the text was not read (U2) | none |

- **OUR NOTE:** Canadian Tire's terms are standard, not better. Its "unopened" condition is stricter than Princess Auto's satisfaction guarantee. Do **not** say Canadian Tire's returns "beat" competitors. A fair line: "Canadian Tire's ninety-day window is the industry standard, and if you're a Triangle member it can look up your purchase without the paper receipt."

### 5.5 Facial-recognition ban (positive with a regulator finding attached)
- CT privacy charter (`ct_pricing.md`, page title "Policies"; undated): "The video surveillance technology in use is not equipped with facial recognition technology. While Canadian Tire stores are independently owned and operated by Associate Dealers, the Corporation and the Dealers have mutually agreed to prohibit the use of facial recognition technology in Canadian Tire stores."
- **Context (finding), from the Office of the Information and Privacy Commissioner for BC, news release, Apr 20, 2023** (https://www.oipc.bc.ca/documents/news-releases/2619; `oipc_nr.md`):
  - "Four BC Canadian Tire stores using facial recognition technology (FRT) to collect customer's biometric information between 2018 and 2021 contravened the Personal Information Protection Act (PIPA)."
  - "12 locations were using the technology."
  - "All 12 stores confirmed that they removed their FRT systems after the investigation began."
- Label it a **finding** (Investigation Report 23-02) about four Dealer-run stores. This probably belongs in the "9 things" list rather than in the positives. Coordinate with that dossier.

---

## 6. GAS+ AND CENTS-OFF WITH TRIANGLE (current terms)
- Triangle home (tier a):
  - "Collect 3¢ per litre back in CT Money at Gas+ & Essence+ locations every time you fill up with Triangle Rewards."
  - "Collect 5¢ - 7¢ per litre back in CT Money every time you fill up with a Triangle® Mastercard®, Triangle® World Mastercard® or Triangle® World Elite Mastercard®."
  - "Get up to 3c per litre in CT Money on fuel with Triangle Rewards when you pay with cash or debit" (Petro-Canada and Gas+).
- Footnotes:
  - "CT Money is collected on the number of whole litres of fuel purchased … Rate subject to change and could vary by location, see local gas bar for details. Not all Gas+ locations have premium fuel. Must go inside kiosk to collect rewards with App or key fob."
  - The cash/debit offer "Excludes the following Gas+ locations: 843 Tower St. South, Fergus, ON, 1002 Broad St. East, Dunnville, ON, 1445 Innisfil Beach Rd., Innisfil, ON, 183 Boul.Norbert-Morin, Ste-Agathe-des-Monts, QC and 2, rue Gauthier Nord., Notre-Dame-des-Prairies, QC."
- AIF 2025:
  - "more than 275 gas bars".
  - "a total of over 200 of the Company's Canadian Tire Gas+ gas bars are planned for rebranding into Petro-Canada stations while maintaining CTC ownership. Suncor will become the Company's primary fuel provider over time."
  - Petro-Canada is "a business owned by Suncor Energy Inc."
- **Catch:** Gas+ is turning into Petro-Canada. The rate is "up to" 3¢, and the CT Money is store credit, not cash off the pump price. OUR NOTE: a 50 L fill at 3¢ is $1.50 in CT Money.
- The gasplus.canadiantire.ca page carries an outdated credit-card footnote: "19.99%" against "21.99%" on the Triangle site. Use the Triangle site (U12).

---

## 7. CANADIAN-IDENTITY SCENE-SETTING (CTC's own words preferred)
- **1922:** "Starting from a single garage established in 1922 by brothers A.J. and J.W. Billes" (AIF 2025, tier a).
- **1927:** incorporated "by letters patent dated December 1, 1927" (AIF).
- **1958:** "Paper Canadian Tire Money began circulating in 1958, making it Canada's oldest loyalty program." (CTC corp page; attribute the "oldest" claim to CTC.) "Canadian Tire Money is introduced at Canadian Tire gas bars, pioneering the loyalty program concept. Conceived by Muriel Billes…" (same page).
- **Logo:** CTC logo history page (`corp_logo.md`):
  - "In 1940, the original version of our current logo is unveiled, featuring a bold orange triangle and green CTC-inscribed maple leaf".
  - "With the help of designer Bernie Freedman in the 1960s, our logo is revamped with a widened triangle (now red instead of orange)".
  - Spelling conflict: the corp Triangle page says "Bernie Freeman" (Sandy McTire), while the logo page says "Bernie Freedman". Avoid the name.
  - First logo "was drawn by an anonymous customer who presented it to Canadian Tire co-founder A.J. Billes."
- **2018:** Triangle Rewards launched (AIF).
- **2020:** paper CT Money issuance ceased "EFFECTIVE MARCH 21, 2020". Primary text is in sibling capture `ctm_paper.txt`; source URL to confirm (U9).
- **2025:** HBC Stripes bought for $30M. Helly Hansen sold for ~$1.3B "reflecting the Company's increasing focus on its Canadian retail portfolio" (AIF).
- **Purpose line:** "We Are Here to Make Life in Canada Better" (AIF).
- Tier b only, not for air without a second source: "the two brothers purchased the Hamilton Tire and Garage Ltd., located in Toronto's Riverdale neighbourhood. The pair bought the business for $1,800." (The Canadian Encyclopedia; byline and date not captured; U10.)

---

## 8. RETENTION CRAFT NOTES FOR THE "3 THINGS" SEGMENT (producer)
- Use the same three beats for each positive: (1) a surprising, concrete number, (2) "here's the catch" with a primary source, (3) a one-line fix the viewer can use today. This mirrors the No Frills segment's "Check the tag, not the brand."
- Open the segment on the Leger slide (3rd → 5th → 7th) as a pattern interrupt. "Still trusted, just less of a lock" carries viewers from the nine negatives into the positives without whiplash.
- Strongest "I didn't know that" beats, in our judgment:
  - customers out-gave the corporation to Jumpstart in 2024 ($9.8M vs $6.4M);
  - 0.4% is forty cents per $100;
  - about half of Canadian Tire Retail's inventory purchases come directly from outside Canada (CTC's own filing).
- End the segment on the identity beat (1922 garage, 1958 money) and go straight into the close. That gives an emotional landing before the comment prompt.
- Keep every price or fee tied to its source on screen: "triangle.canadiantire.ca, Oct 4, 2026".

---

## 9. SOURCE REGISTER (all opened Oct 4, 2026)

| ID | Source | Tier | URL | Capture |
|---|---|---|---|---|
| S1 | CTC 2025 Annual Information Form (Feb 18, 2026) | a | https://s201.q4cdn.com/326551073/files/doc_financials/2025/ar/AIF-EN.pdf | ctc_aif2025.pdf/.txt |
| S2 | canadiantire.ca Returns | a | https://www.canadiantire.ca/en/customer-service/returns.html | ct_returns_jina.md |
| S3 | canadiantire.ca Policies (pricing policy, privacy charter) | a | https://www.canadiantire.ca/en/customer-service/policies/pricing.html | ct_pricing.md |
| S4 | canadiantire.ca Tire warranty | a | https://www.canadiantire.ca/en/customer-service/tires-warranty.html | ct_tirewarranty.md |
| S5 | canadiantire.ca Loan-A-Tool | a | https://www.canadiantire.ca/en/automotive/loan-a-tool.html | WebFetch only (ct_loanatool.md lacks the body) |
| S6 | canadiantire.ca Online ordering | a | https://www.canadiantire.ca/en/customer-service/online-ordering.html | ct_online.md |
| S7 | Triangle home / loyalty / cards / rules / Select / Tims / Petro | a | triangle.canadiantire.ca (paths in §1, §6) | ct_triangle.md, tr_loyalty.md, tr_cards.md, tr_rules.md, tr_select.md, tr_tims.md, tr_petro.md |
| S8 | Gas+ site | a (stale footnotes) | https://gasplus.canadiantire.ca/en.html | gasplus.md |
| S9 | CTC corp: Triangle history, logo history, about | a | corp.canadiantire.ca/English/about-us/triangle/…; /CT-100-Logo-History | corp_triangle.md, corp_logo.md, corp_about.md |
| S10 | CTC release, HBC brand assets (May 15, 2025) | a | corp.canadiantire.ca/…/2025/Canadian-Tire-plans-to-steward-the-HBC-coat-of-arms… | corp_hbc.md |
| S11 | CTC Q2 2026 results release | a | corp.canadiantire.ca/…/2026/Canadian-Tire-Corporation-Reports-Second-Quarter-2026-Results/ | corp_q2_2026.md |
| S12 | CTC ESG posts on Leger 2024 and 2025 | a (company claim) | corp.canadiantire.ca/English/ESG/ESG-news/… | ctc_leger2024.md, ctc_leger2025.md |
| S13 | Jumpstart About, FAQ, Annual Reports page | a | https://jumpstart.canadiantire.ca/pages/about, /pages/faq, /pages/annual-reports | js_about.html, js_faq.html, js_annual.html, jumpstart_raw.html |
| S14 | Jumpstart audited FS 2025 (Deloitte, Feb 23, 2026) | a | https://cdn.shopify.com/s/files/1/0122/8124/9892/files/2025_Audited_Financial_Statements_EN.pdf | js_fs2025.pdf/.txt |
| S15 | Jumpstart 2024 Annual Report | a | https://cdn.shopify.com/s/files/1/0807/6152/0344/files/Canadian_Tire_Jumpstart_Charities_Annual_Report_2024_eb5e7784-37c3-45e8-9c8d-f95a44ebe6ff.pdf | js_ar2024.pdf/.txt |
| S16 | OIPC BC news release (Apr 20, 2023) | a | https://www.oipc.bc.ca/documents/news-releases/2619 | oipc_nr.md |
| S17 | Home Depot Canada return policy | a | https://www.homedepot.ca/en/home/customer-support/return-policy.html | hd_returns.md |
| S18 | Princess Auto FAQ; Shipping and returns | a | https://www.princessauto.com/en/frequently-asked-questions; /en/shipping-and-returns | pa_faq.md, pa_returns.md |
| S19 | Global News / CP, Tara Deschamps, Feb 13, 2025 | b | https://globalnews.ca/news/11017812/tariff-threats-impact-consumer-confidence-canadian-tire-ceo | gn_tariff_2025.md |
| S20 | Global News, Ariel Rabinovitch, Feb 19, 2026 | b | https://globalnews.ca/news/11674468/canadian-tire-earnings-loyalty-program/ | WebFetch only |
| S21 | CBC, Sophia Harris, May 15, 2025 and Jun 3, 2025 | b | https://www.cbc.ca/news/business/hudson-s-bay-stripes-candian-tire-1.7536366; https://www.cbc.ca/news/business/hudon-s-bay-canadian-tire-1.7551035 | cbc_hbc1.md, cbc_hbc.md |
| S22 | Leger Reputation page (2026 ranking) | d (publisher primary) | https://leger360.com/reputation-study/ | leger_rep.html, leger_rep.md |
| S23 | Leger 2023 Reputation page (Apr 5, 2023) | d | https://leger360.com/2023-reputation-study-discover-the-most-reputable-companies-in-canada/ | leger2023.md |
| S24 | Strategy, Christopher Lombardo, Apr 20, 2026 (Leger 2026) | b | https://strategyonline.ca/2026/04/20/dollarama-brand-reputation-2026/ | strat_leger2026.md |
| S25 | Strategy, Apr 10, 2025 (Leger 2025) | b (byline not captured) | https://strategyonline.ca/2025/04/10/leger-reputation-2025/ | strat_leger2025.md |
| S26 | Retail Insider, Mario Toneguzzi, Apr 3, 2024 and Apr 10, 2025 | b | retail-insider.com/retail-insider/2024/04/…, /2025/04/… | ri_leger2024.md, ri_leger2025.md |
| S27 | Morning Consult, Most Trusted Brands 2023 | d | https://pro-assets.morningconsult.com/wp-uploads/2023/05/Most-Trusted-Brands-2023.pdf | mc2023.pdf/.txt |
| S28 | Harris Poll, "The 100 Most Canadian Brands" | d | https://theharrispoll.com/articles/the-100-most-canadian-brands/ | harris100.md |
| S29 | Strategy, Feb 12, 2025 (Harris) | b (byline not captured) | https://strategyonline.ca/2025/02/12/canadian-tire-harris-poll/ | strat_harris.md |
| S30 | Angus Reid Group, Canada-U.S. Relations 360 | d | https://www.angusreid.com/canada-us-relations-360/ | arg_360.md |
| S31 | BrandSpark 2026 Most Trusted Awards release (Nov 20, 2025) | d | https://brandspark-most-trusted.squarespace.com/s/2026-BMTA-Canada-Press-Release.pdf | bs2026.pdf/.txt |
| S32 | Ipsos, Canada's Most Influential Brands 2025 (Feb 11, 2026) | d | https://www.ipsos.com/en-ca/ipsos-reveals-canadas-most-influential-brands-2025 | WebFetch only |
| S33 | Retail Insider, Toneguzzi, Jul 13, 2023 (GBTI 2023); Toyota Canada release (GBTI method) | b / a (Toyota's own release) | retail-insider.com/…/2023/07/…; media.toyota.ca/… | gbti_ri2023.md, toyota_gbti.md |
| S34 | The Canadian Encyclopedia, "Canadian Tire" | b (byline and date not captured) | https://www.thecanadianencyclopedia.ca/en/article/canadian-tire-corporation-limited | tce_ct.md |
| X1 | Deal blogs and forums on price match (Flipp, RedFlagDeals, priceadjust.ca, canadianfreestuff, etc.) | **c, do not use** | various | not saved |
| X2 | Narcity reader "poll" on most trusted retailers (Feb 11, 2025) | **c, do not use** (unscientific) | narcity.com/… | narcity_gbti.md |
| X3 | Curiocity (Morning Consult rewrite) | c | curiocity.com/most-trusted-brand-2023/ | curio_mc.md |

---

## 10. UNVERIFIED / DO-NOT-USE (mandatory)

| # | Item | Status | Action |
|---|---|---|---|
| U1 | **Price match.** Deal blogs and forums say CT ended competitor price matching on Aug 5, 2022. | Only tier c sources. CT's policies page (Oct 4, 2026) contains no competitor price-match policy, only "Canadian Tire attempts to match online prices to those in store" and "Dealers may sell for less". Wayback lookup was blocked. | **Do not use as a positive.** Do not state the 2022 end date. At most: "Canadian Tire's policy pages, read October 4th, describe no competitor price-match policy. Ask your store." |
| U2 | Walmart Canada return policy text | Page blocked by bot check; snippet only | Do not quote Walmart on screen |
| U3 | Tire storage service | Not found on CT national pages; likely dealer-specific | Do not use |
| U4 | Gustavson Brand Trust Index: CT rank (a search summary claimed #37 in 2023, unverified) and whether the index continues after 2023 | UVic PDF and page now redirect | Do not cite GBTI for CT |
| U5 | Harris "39%" and the Strategy byline | 39% figure only in Strategy (no byline captured); the Harris page gives method and dates only | Say "Harris Poll found Canadian Tire was named most often". If quoting 39%, screen-grab the Strategy article |
| U6 | Angus Reid Group "biggest winner" | Commercial teaser page; no numbers; Angus Reid Group, not the Angus Reid Institute | Quote the sentence verbatim with the method; no percentages |
| U7 | Leger 2026: CT score not captured; scope may be "English Canada" (Strategy wording) | Ranking from Leger's own image alt text | Say "Leger's 2026 ranking" and avoid "nationally including Quebec" |
| U8 | Triangle member counts conflict: 12.2M "active members" (AIF) vs 9.8M "active registered members" (Global, Feb 2026) vs "nearly 12 million members" (CTC boilerplate) | Different definitions | Use "about 12 million members (CTC)" or name the definition |
| U9 | Paper CT Money: issuance "ceased" Mar 21, 2020 | Text from sibling capture `ct/ctm_paper.txt` (CT 'Money' program T&C); source URL not confirmed by this dossier. CT returns page still mentions "issued Canadian Tire 'Money'" | Confirm URL before air. Do not say paper money is still being handed out |
| U10 | "Oxford English Dictionary" claim; "over 1 billion notes"; Hamilton Tire and Garage for $1,800 in Riverdale | CTC claims, and TCE without byline | Attribute to CTC ("Canadian Tire says…") or cut |
| U11 | Store counts: 1,400+ (AIF), 1,600+ (CTC About page), "nearly 1,700 retail and gasoline outlets" (CTC boilerplate), "more than 1,700" (CBC) | Inconsistent | Use AIF: "502 Canadian Tire stores" |
| U12 | Gas+ per-litre rates "could vary by location"; 5 excluded sites; Gas+ site footnote APR 19.99% vs Triangle 21.99% | Stale page | Re-check triangle.canadiantire.ca on Oct 5–6 before air |
| U13 | Tims "up to 5%" CT Money | Conditions in T&C PDF not read | Do not quote "5%" |
| U14 | Jumpstart "100% of customer donations" go to kids | Jumpstart's claim; FS show G&A paid from pooled revenue and do not itemise CTC's G&A funding | Attribute: "Jumpstart says…" |
| U15 | Jumpstart "social value of $143 million", "$547 per child" | Modelled figure | Do not use |
| U16 | Leger 2024 #3 | From Retail Insider and CTC's post; Leger's own 2024 page not captured | OK with attribution to Leger via Retail Insider |
| U17 | Morning Consult Canada No. 1 is 2023 only; per-country n is a range (408–8,553), Canada's n not isolated | 2024–2026 Canada results not found | Always say "in 2023" |
| U18 | Home Depot 365-day window | Text covers online purchases on HD cards only | Quote exactly; do not generalise |
| U19 | CT facial-recognition prohibition | Privacy charter undated | Say "Canadian Tire's privacy policy says…"; pair with the OIPC finding |
| U20 | BrandSpark "Permission … required to reference a … win" | Probably aimed at brands' marketing use | Producer to confirm editorial use; otherwise say "BrandSpark's 2026 survey" |
| U21 | Strategy 2025 bylines (Leger 2025, Harris) | Not captured | Screen-grab before on-screen attribution |
| U22 | Loan-A-Tool deposit amounts and loan period | Not stated online | No amounts on air |
| U23 | Free Local Shipping minimum | "may vary by store" | No dollar threshold on air |
| U24 | "Tested For Life in Canada" (CT marketing) | Product-performance claim | **Do not use** (house rule 2) |
| U25 | Hicks: "lowering prices for value-seeking customers" (Q2 2026) | Company statement; no price data in this dossier | Attribute only; never as our finding |
| U26 | CP figure "about 15 per cent of its goods from the U.S." | CP paraphrase, Feb 2025; not in AIF | Attribute to CP; do not mix with AIF's ~50% outside Canada (a different measure: direct imports, CTR only) |

**APPENDIX: Recalls. DO NOT USE ON AIR.** None were researched or collected for this dossier. CT's returns page links its recall list (corp.canadiantire.ca/English/media/product-recalls/default.aspx) and says nothing else about recalls. Nothing about recalls goes on air.
