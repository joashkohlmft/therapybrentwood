# therapybrentwood.com — SEO Competitive Plan

*Built from live Semrush data (US database), August 6, 2026. Research-first plan. Every number below is pulled from Semrush.*

## ▶ START HERE — Execution kickoff & status (READ FIRST)

**Status (updated Aug 11, 2026): Milestones M1–M6 executed in the working files (awaiting Joash's GitHub deploy). M3 is in its Step-A measurement window. M7 and Phases 2–6 are pending.** This document is the single source of truth.

### Progress log
- **M1 — DONE (Aug 11, 2026).** Quick wins: trauma-brainspotting title + H1 keyword; couples-therapy opening keyword; three contextual inbound links to eft-vs-gottman.
- **M2 — DONE.** `couples-therapy-nashville` rebuilt with no verbatim overlap vs `couples-therapy`; Nashville-specific FAQ + schema; added to nav dropdown + mobile overlay sitewide (48 files); contextual links from home/what-is-eft/resources. **Enhanced further:** extractable "In brief" box; distinctive Music-City + Bible-Belt culture section (tied to Joash's pastoral background, cited to LifeWay Research); cost section; Nashville skyline visual + ImageObject schema. Fees centralized to `faq#fees` (no hardcoded prices; schema `offers` price removed). **Awaiting Joash: GSC "Request Indexing" + re-validate.**
- **M3 Step A — DONE.** Additive cannibalization fix: couples-therapy reinforced for "marriage counseling brentwood"; four inbound links (faq, premarital, discernment, contact) with anchor "marriage counseling in Brentwood." Guard-rail respected (premarital NOT optimized). **Step B = measure ~2–3 weeks (until early Sept 2026) before any Step-C de-optimization.**
- **M4 — DONE.** couples-therapy AEO: cost section (→ faq#fees), money/roles/life-transition terms, three new FAQs (works/worth it; one partner; online vs in-person) in visible + FAQPage schema (now 8 Qs).
- **M5 — DONE.** what-is-eft AEO: EFT disambiguation (not tapping / not Greenberg's Emotion-Focused Therapy), EFIT/EFFT note, plain "what happens in a session" beat, new visible 7-item FAQ block matched to FAQPage schema (em-dash-free).
- **M6 — DONE.** eft-vs-gottman AEO: "Can you combine EFT and Gottman?" section + visible 5-item FAQ block matched to FAQPage schema.

### Deferred — to revisit later (in order)
1. **M7 — Entity/schema + housekeeping** (next up): Person schema for Joash sitewide; build the "Joash Koh" bio page; interim 301 joashkoh.com → bio page; reconcile URL consistency + sitemap lastmod.
2. **Phase 2 — Franklin page** (uncontested; dedicated landing page).
3. **Phase 3 — Nashville authority push** (after the M2 page is indexed).
4. **Phase 4 — joashkoh.com standalone hub.**
5. **Phase 5 — Link-building** (102 → ~140 referring domains; Section 3A list).
6. **Phase 6 — Position + AI-Overview tracking.**

### Open items to decide
- Resource-article sitemap `lastmod` for `what-is-eft` and `eft-vs-gottman` was left on their cadence dates (not bumped) to preserve the date-sync invariant; decide whether to bump `dateModified` for a freshness signal given how much was added.
- `couples-therapy` still carries `price: 225` in its Service JSON-LD `offers`; left in place, can be stripped for consistency with the fees-centralization decision.

**To resume in a fresh chat:**
1. Read `CLAUDE.md` (house rules / "same MO") and this entire `SEO-PLAN.md`.
2. The site's HTML files are in the project folder with full read/write access — no upload needed.
3. Execute in the Section 12 milestone order. Get the user's OK before starting a milestone; verify twice, then report back after each.

**Milestone order (Section 12):** M1 Quick wins → **M2 Nashville page MAJOR rewrite (highest priority)** → M3 Cannibalization fix (additive-first) → M4–M6 AEO enrichment (couples-therapy, what-is-eft, eft-vs-gottman) → M7 Entity/schema + housekeeping.

**Working rules:** read the full file before editing; surgical edits only; verify twice (new present / old gone); batch multi-file edits with Python; update BOTH the nav dropdown AND the mobile overlay when structure changes; update `sitemap.xml` lastmod; output all touched files; never alter unrelated JSON-LD/meta, mobile CSS breakpoints, or biographical content.

**Critical gotchas — do not miss:**
- **Cannibalization = additive-first (Section 6).** Add internal links first, measure 2–3 weeks, de-optimize only if still needed. NO canonical tags / 301s / noindex on the distinct service pages.
- **Do NOT follow Semrush's suggestion** to add "marriage counseling brentwood" to `premarital-counseling` — it deepens the cannibalization.
- **Nashville page (M2) is a MAJOR rewrite, not minor edits.** `/couples-therapy-nashville` is "crawled — currently not indexed" because it overlaps `/couples-therapy`. Make it substantially unique (lean into the Nashville + online/telehealth angle), strengthen internal links + nav/overlay, then request indexing in GSC + re-validate. This unblocks the entire Nashville must-win — budget the most effort here.
- **joashkoh.com:** Phase 1 = interim 301-redirect only; the full standalone site is its own Phase 4 (after Nashville).
- **Semrush API units are exhausted** for Keyword Gap, broad-match, page-level export, and referring-domain reports. Use the free SERP-diff method (Section 11) for semantic gaps; standard reports (domain/organic/SERP/backlinks-comparison) still work.

---

**Geographic scope: Nashville, Brentwood, Franklin only.** Nashville is a must-win (goal: page 1 to 2 minimum). Murfreesboro, Knoxville, Memphis, etc. are out of active SEO scope for now (still covered by the sitewide geo footer, but not target-page priorities).

**Primary strategy: AEO (be the AI answer).** Classic search volume is small and authority-gated; AI answer engines are the asymmetric, uncontested opportunity and play to Joash's credentials. See Section 8. **Local pack is off the table** (telehealth, no verifiable physical address to establish a Google Business Profile), so we lean fully on organic pages, directories, and AEO.

**Domain strategy decision: one domain, dedicated city pages. Do NOT buy separate Nashville/Franklin domains.** Rationale: (1) exact-match domains lost their ranking power in Google's 2012 EMD update — a keyword in the domain gives negligible benefit now; (2) separate domains would split our authority three ways when the whole constraint is authority (AS 2, 102 referring domains) — every link should compound on one domain; (3) new domains have no trust history and rank poorly for months, while therapybrentwood.com already ranks page 3 for these terms; (4) multiple thin single-city sites owned by one solo practice reads as a doorway/microsite pattern Google penalizes. Instead build `/nashville-couples-therapy` and `/franklin-couples-therapy` pages on the existing domain, mirroring how the market leader runs `/nashville` and `/brentwood` pages on one domain. (Note: "brentwood" in the domain is mildly suboptimal for Nashville/Franklin brand perception but is not a ranking barrier; a geo-neutral rebrand is optional and out of scope for SEO.)

**This bans geo/exact-match microsites** (no separate Nashville or Franklin domain). The name-based personal-brand hub **joashkoh.com is a deliberate, different case** — distinct audience and intent (expert/author/supervisor, not local client acquisition), built in parallel with strict role separation and cross-linking. See Section 8D.

---

## 0. Research priority order (and status)

What to pull from Semrush, in priority order, and where each stands:

1. **Backlink / authority gap** — DONE. Explains the page-3 ceiling. See Section 3.
2. **Full Nashville keyword universe** — DONE (built from competitor pulls + broad match). See Section 4.
3. **Full Franklin keyword universe + SERP** — DONE. See Section 5.
4. **Nashville leader page-level teardown** (nashvilletherapygroup structure) — DONE. See Section 4A.

**Semrush unit note:** two report types are exhausted (`API UNITS BALANCE IS ZERO`): the paid **Keyword Gap** and **broad-match (fullsearch)** reports. Everything else (domain rank, organic keywords, SERP, backlinks) runs on a separate quota that still works. Top up units if we want automated gap/broad-match monitoring; the manual method used here is equally reliable.

---

## 1. Where we stand today

| Metric | therapybrentwood | brentwoodmarriagecounselor | redtherapygroup | nashvilletherapygroup |
|---|---|---|---|---|
| Semrush Rank | 15,450,533 | 3,975,892 | 4,312,644 | (leader) |
| Organic keywords | 26 | 67 | 149 | 200+ |
| Est. monthly organic traffic | ~0 | 88 | 72 | few hundred |
| **Authority Score** | **2** | **8** | **17** | **19** |
| Referring domains | 102 | 131 | 199 | 268 |

The core problem is position, not topic. We rank for the right keywords but sit on pages 3 to 9. Three causes: keyword cannibalization, thin geo coverage, and a real authority gap (Section 3). This is a small, low-volume, winnable market. Even the leader pulls only a few hundred visits a month.

---

## 2. Who our competitors actually are (three-city scope)

Directories excluded (Psychology Today, Yelp, Reddit, TherapyDen, Zencare, TherapyTribe, TheKnot, ICEEFT directory) — they hold slots but are not beatable the same way.

**Nashville (must-win, hardest).** Leader: **nashvilletherapygroup.com** — #1 for "therapy nashville," "couples counseling nashville," "marriage counseling nashville," "couples therapy nashville." Secondary: sagehill.co, midtownnashvillecounseling.com, thehappyhournash.com, jfsnashville.org, marriagefamilyinstitute.org, gettherapie.com. EFT niche led by redtherapygroup.com.

**Brentwood (home turf, most winnable).** Leader: **brentwoodmarriagecounselor.com** (Dr. Richard Sanders) — #1 "marriage counseling brentwood tn." Secondary: drjohnfite.com, fccwellbeing.com, ccgtherapy.org, brentwoodcounseling.com, susanhyattmft.com, concordfamilycounseling.com.

**Franklin (soft target).** **brentwoodmarriagecounselor.com** ranks #1 but only on its homepage. fccwellbeing.com has a dedicated Franklin page at #3. Others: concordfamilycounseling.com, refugecenter.org, ramonpressontherapy.com, truenorthtn.net, jeffgrossmancounseling.com. **No competitor has a strong Franklin-specific page — a purpose-built page can win.**

---

## 3. Authority gap (why KD-0 terms still sit on page 3)

| Domain | Authority Score | Total backlinks | Referring domains |
|---|---|---|---|
| **therapybrentwood.com** | **2** | 178 | 102 |
| brentwoodmarriagecounselor.com | 8 | 234 | 131 |
| redtherapygroup.com | 17 | 694 | 199 |
| nashvilletherapygroup.com | 19 | 4,008 | 268 |

**Read:**
- **Brentwood is winnable on authority now.** We have 102 referring domains vs BMC's 131 — close. The gap is small enough that fixing cannibalization + on-page should move us onto page 1 for Brentwood terms.
- **Nashville is a real authority climb but not insurmountable.** nashvilletherapygroup has 4,008 backlinks (a moat) but only 268 referring domains (2.6x ours). Referring-domain count, not raw backlinks, is the catchable metric. Realistic Nashville goal near-term: page 1 to 2, not #1.
- **EFT niche is relevance-driven, not authority-driven.** redtherapygroup holds "emotionally focused therapy nashville" (#1) on KD 0 despite modest authority. As triple-certified ICEEFT, we can compete on relevance here regardless of the AS gap.

**Action:** a light, ethical link-building push (local directories, professional associations, ICEEFT/AAMFT profiles, guest articles, local press) to close the referring-domain gap. Getting from 102 to ~140 domains likely unlocks the Brentwood page-1 terms.

**Key signal on competitor links:** brentwoodmarriagecounselor's single highest-authority backlink is **yellowpages.com (AS 56)** — a free directory listing. Their authority edge is directory-driven, not earned press. That means it is cheaply and directly replicable.

### 3A. Link-building target list (Phase 4 checklist)

Prioritized, mostly-free sources appropriate for a licensed TN therapist. Claim/verify each and ensure NAP (name, address, phone) is consistent everywhere.

**Therapist directories (highest relevance, do first):**
- Psychology Today (already have — keep optimized)
- TherapyDen, GoodTherapy, Zencare, TherapyTribe, Theravive
- Mental Health Match, OpenCounseling, Choosing Therapy directory
- Inclusive Therapists, Therapy for [population] directories where applicable

**Professional / credential authority (strong trust signals):**
- ICEEFT therapist directory (EFT certification — on-brand, high authority)
- AAMFT / TN-AAMFT member profile
- Tennessee state licensing board profile
- Certified Clinical Trauma Professional (IATP) directory

**General business directories (the yellowpages-style links competitors use):**
- Yellow Pages, Yelp, Bing Places, Apple Maps, Google Business Profile
- Nextdoor business, Better Business Bureau

**Local / geo (supports the three-city strategy):**
- Williamson County / Brentwood / Franklin chamber of commerce
- Nashville-area wellness and local business listings
- Local church / community counseling referral pages (fits Joash's pastoral background)

**Content-earned (slower, higher value):**
- Guest articles on local Nashville/Franklin lifestyle or parenting blogs
- HARO / expert-quote requests on relationships, EFT, attachment
- Local press or podcast features on couples therapy / intensives

**Confirmed named targets (from Semrush On-Page Checker link-gap, Aug 2026):** links our top-10 competitors have that we don't. Triaged for relevance:
- Pursue: **therapyden.com** (dir), **neustarlocaleze.biz** (citation aggregator; set up as telehealth/service-area), **therapyhelpers.com** + **rubymentalwellness.com** (niche content sites — guest post / editorial mention), **revdex.com** (review directory).
- Skip (irrelevant/low quality, do not chase despite domain score): hashnode.dev (dev platform), canadiandentalwebsites.com, classifiedsforfree.com, intently.co. Relevance beats domain score.

---

## 4. Nashville keyword universe (must-win)

Goal: page 1 to 2 on the core set. Volume and keyword difficulty (KD) from Semrush.

### Core Nashville targets (priority)
| Keyword | Volume | KD | We rank | Leader |
|---|---|---|---|---|
| couples counseling nashville | 390 | 14 | — | NTG #1 |
| marriage counseling nashville | 320 | 13 | — | NTG #1 |
| marital counseling nashville tn | 320 | 6 | — | NTG #1 |
| couples counseling nashville tn | 260 | 8 | — | NTG #1 |
| couples therapy nashville | 210 | 12 | — | NTG #1 |
| marriage counseling nashville tn | 210 | 12 | — | NTG #1 |
| relationship counseling nashville tn | 170 | 8 | — | NTG #1 |
| nashville relationship counseling | 110 | 5 | — | NTG #1 |
| premarital counseling nashville | 110 | 5 | #50 | NTG #1 / RTG #4 |
| relationship counseling nashville | 90 | 11 | — | NTG #1 |
| couples therapy nashville tn | 70 | 10 | — | NTG #1 |
| couple therapy nashville | 40 | 1 | — | RTG #6 |
| **emotionally focused therapy nashville** | 40 | **0** | **#25** | RTG #1 |
| nashville couples therapy | 30 | 4 | — | — |
| eft couples therapy nashville | 10 | 0 | — | — |
| gottman couples therapy nashville | 10 | 0 | — | — |

### Adjacent Nashville (we offer the service, low KD)
| Keyword | Volume | KD | We rank |
|---|---|---|---|
| family therapy nashville tn | 70 | 5 | — |
| trauma therapist nashville | 70 | 13 | — |
| sex therapy nashville | 40 | 11 | #44 |
| individual therapy nashville | 90 | 24 | — |

**Nashville plan:** we have a dedicated Nashville page (`/couples-therapy-nashville`) targeting the core set; win "emotionally focused therapy nashville" (KD 0, we're already #25) as the beachhead. **But see the indexing blocker below — the page must get indexed before any of this can rank.**

**⚠ Indexing blocker (GSC, Aug 2026): `/couples-therapy-nashville` is "Crawled — currently not indexed" (validation failed).** This is NOT the duplicate label, and the page is technically clean (self-canonical, index,follow, rich schema). But three factors combine to keep it out of the index: (1) **content overlap with `/couples-therapy`** — verbatim lines ("excellent partners in logistics and strangers in intimacy"), repeated 75%/gold-standard passages, near-identical FAQ answers; (2) **low site authority** (AS 2 — the enabling condition; Google is stingy about indexing); (3) **weak internal linking** — the page is not in the main nav/overlay, only some footers + one in-body link. **Until indexed it cannot rank, so this blocks the Nashville must-win.** Fix, in impact order: (a) rewrite the overlapping paragraphs + FAQ so the page is substantially unique, leaning into the Nashville + online/telehealth angle; (b) strengthen internal links from strong indexed pages (home, what-is-eft, resources) and consider adding to nav; (c) request indexing in GSC URL Inspection + re-run validation; (d) grow authority (Section 3A).

### 4A. Nashville leader page-level teardown (site-structure playbook)

Which pages actually carry nashvilletherapygroup's rankings (Semrush page-level export, by traffic share):

| Page | Keywords | Traffic | Share |
|---|---|---|---|
| /couples | 57 | 182 | 25.6% |
| / (home) | 214 | 168 | 23.6% |
| /emdr-and-trauma-therapy | 37 | 52 | 7.3% |
| /holistic-health | 208 | 50 | 7.0% |
| /hannah-barney (clinician bio) | 1 | 21 | 2.9% |
| /megan-marks (clinician bio) | 1 | 16 | 2.3% |
| /journal/premarital-counseling-nashville-questions | 6 | 12 | 1.7% |
| /sexual-health | 5 | 11 | 1.5% |
| plus | /brentwood, /nashville, /cost, 6+ more clinician bios, ~10 journal articles | | |

Five lessons to copy:

1. **One dedicated /couples page is their single biggest traffic driver (25.6%).** Validates our plan to make /couples-therapy the single couples authority page and to build one dedicated Nashville page rather than spreading terms across many.
2. **Clinician-name bio pages rank and drive real traffic** (hannah-barney 21, megan-marks 16) purely on branded/name search. We should own **"Joash Koh"** with a strong, name-optimized bio page. We're the only clinician, so this is a clean win with zero competition and reinforces E-E-A-T.
3. **Geo + topic journal articles target local long-tail** ("premarital-counseling-nashville-questions," "trauma-therapy-nashville-guide," "sex-therapy-nashville-where-to-begin"). Directly supports our AEO/GEO strategy: city + topic blog posts, which we already do well (ARS series, resource articles).
4. **Dedicated city pages exist** (/brentwood, /nashville) but carry thin traffic, because home + /couples capture the head terms. They still hold the geo net. Confirms that building Franklin + Nashville pages is standard, expected practice.
5. **A transparent /cost page ranks for pricing intent.** We publish pricing already; a clean fees/pricing page can capture "cost/price" searches.

Note: brentwoodmarriagecounselor's page-level export was blocked by Semrush units, but its keyword URLs show it is overwhelmingly homepage-concentrated with few service pages, which is exactly why a dedicated Franklin page can outrank its homepage.

---

## 5. Franklin keyword universe (soft target — biggest quick win)

No competitor has a strong Franklin-specific page. brentwoodmarriagecounselor is #1 on its homepage only. ~560/mo combined, very low difficulty.

| Keyword | Volume | KD | Leader |
|---|---|---|---|
| couples therapy franklin | 140 | 18 | BMC #1 (homepage) |
| marriage counseling franklin tn | 140 | 13 | BMC #1 (homepage) |
| couples counseling franklin tn | 90 | 2 | BMC #1 |
| marriage counseling franklin | 70 | 5 | BMC #1 |
| premarital counseling franklin | 50 | 0 | BMC #1 |
| franklin couples therapy | 40 | 1 | BMC #1 |
| couples therapy franklin tn | 30 | 2 | BMC #1 |

**Franklin competitors (real practices):** brentwoodmarriagecounselor (homepage), fccwellbeing (dedicated page #3), concordfamilycounseling, refugecenter.org, ramonpressontherapy, truenorthtn.net, jeffgrossmancounseling. Field is fragmented and thin.

**Franklin plan:** build a dedicated **Franklin couples-therapy landing page** mirroring the Brentwood page. Because the market leader ranks via homepage only, a purpose-built page targeting all seven terms can realistically take top positions. Add to nav + mobile overlay + sitemap.xml + resources per the working method.

---

## 6. Page-by-page cannibalization fix

Our worst self-inflicted problem. Multiple URLs compete for the same term, so Google can't pick an authority and none ranks well. Fix = one primary page per term; point the others at it via internal links; de-optimize the phrase on secondary pages.

### Term 1 — "marriage counseling brentwood tn" (40/mo, KD 0) — **7 URLs competing**
| Current URL | Position |
|---|---|
| /faq | **13** (accidental winner) |
| / (home) | 47 |
| /premarital-counseling | 67 |
| /discernment-counseling | 71 |
| /couples-therapy | 76 |
| /couples-therapy | 80 |
| /contact | 85 |

**Fix:** make **/couples-therapy** the single primary target. Strengthen "marriage counseling in Brentwood, TN" there; de-emphasize on FAQ, premarital, discernment, contact and internal-link them to /couples-therapy. KD 0 — page 1 is very reachable once consolidated.

### Term 2 — "marriage counseling brentwood" (40/mo, KD 6) — **3 URLs**
| Current URL | Position |
|---|---|
| / (home) | **27** |
| /discernment-counseling | 59 |
| /discernment-counseling | 68 |

**Fix:** consolidate onto **/couples-therapy** (see decision below); remove the competing optimization on /discernment-counseling.

### Term 3 — "couples counseling brentwood" (30/mo, KD 2) — **2 URLs**
| Current URL | Position |
|---|---|
| /couples-therapy | **56** |
| /contact | 76 |

**Fix:** **/couples-therapy** primary; de-optimize /contact and internal-link it over. KD 2 — winnable.

### Decision: make /couples-therapy the single Brentwood-couples authority page for all three terms. Let the home page rank naturally without competing anchor text. This concentrates internal-link equity on one URL.

**Method — additive-first, low-risk (steps in Milestone 2):** the competing pages rank at #47–#85 for the shared term (near-zero traffic) and each keeps its OWN primary keyword, so there is almost nothing to lose. Resolve by (1) adding internal links to /couples-therapy, (2) measuring for 2–3 weeks, (3) only then de-emphasizing the phrase surgically if still needed (contact page first, FAQ's #13 last). **No canonical tags, no 301 redirects, no noindex** — these are distinct, legitimate service pages that must keep ranking for their own terms. Prefer differentiation (sharpen each page on its own keyword) over deletion.

**Independent confirmation (Semrush On-Page Checker, Aug 2026):** the tool sees /premarital-counseling as a landing page for "marriage counseling brentwood" — the exact cannibalization above. **Guard-rail: do NOT follow the tool's on-page suggestions for /premarital-counseling** (it recommends adding "marriage counseling brentwood" to that page's H1/title/body and earning links for it). That would deepen the cannibalization. The On-Page Checker optimizes each page-keyword pair in isolation and cannot see our consolidation strategy. Correct action: strip that term OFF /premarital-counseling and internal-link it to /couples-therapy.

**Not cannibalization (leave alone):** "eft vs gottman" / "gottman vs eft" both → /eft-vs-gottman (same page). "premarital counseling in nashville tn" / "pre marital counseling nashville" both → /premarital-counseling.

---

## 7. Priority page-1 pushes (near-miss terms we already rank)

| Keyword | Current | KD | Target page | Action |
|---|---|---|---|---|
| emotionally focused therapy nashville | #25 | 0 | /couples-therapy (then new Nashville page) | **Own this.** ICEEFT authority vs RTG on KD 0. |
| marriage counseling brentwood tn | #13 (faq) | 0 | /couples-therapy | Consolidate (Term 1) |
| couples therapy brentwood | #26 | 8 | / then /couples-therapy | Consolidation + links |
| marriage counseling brentwood | #27 | 6 | /couples-therapy | Consolidation (Term 2) |
| couples counseling brentwood | #56 | 2 | /couples-therapy | Consolidation (Term 3) |

---

## 8. AEO / GEO playbook (PRIMARY STRATEGY)

**Why this leads.** Classic search volume here is tiny (30 to 390/mo) and capped by our authority gap. AI answer engines (ChatGPT, Perplexity, Google AI Overviews) are the asymmetric opportunity: no competitor optimizes for extraction, and this is the one dimension where Joash's credentials and content depth beat the authority gap outright. The local pack is unavailable to us (telehealth, no verifiable address), which makes AEO even more central rather than a nice-to-have.

**A. Schema layer (extractability) — money pages + articles**
- FAQPage schema on service pages and articles, built from the real questions people ask AI.
- Speakable schema on the key answer paragraph of each page.
- Person schema for Joash: hasCredential (LMFT TN #1970, ICEEFT EFCT/EFIT/EFFT, CCTP), memberOf (AAMFT, ICEEFT), knowsAbout (EFT, attachment, couples therapy). Reused sitewide as author.
- Service + online/telehealth business schema: areaServed = Nashville, Brentwood, Franklin; serviceType = couples therapy, EFT, discernment, premarital, etc. No physical LocalBusiness address; use areaServed + provider = Person/Organization.
- Article schema with author = the Joash Person entity on every resource page.

**B. Extractable answer format**
- Open each key page with a crisp, quotable 40 to 60 word direct answer to its core question ("What is EFT?", "How much does couples therapy cost in Nashville?", "Is EFT better than the Gottman Method?"). AI engines lift these near-verbatim.
- Use H2s phrased as the actual questions, with a concise answer immediately below; lists/tables where they aid extraction.

**C. Question-targeted + comparison content**
- Leverage existing assets: eft-vs-gottman (already ranks), does-insurance-cover-couples-therapy, the ARS series.
- Add decision/comparison guides: "How to choose a couples therapist in Nashville," "Couples therapy vs marriage counseling," "How long does couples therapy take." These win research-stage searchers and are AI-favored formats.

**D. Entity consistency (E-E-A-T)**
- Consistent name + credentials + telehealth service area across the site and every directory, so AI systems bind "Joash Koh" to "EFT couples therapy in Nashville/Brentwood/Franklin" as a single entity.
- **joashkoh.com — decision: interim 301-redirect now; full standalone build is its OWN phase after Nashville.** Positioning: a focused expertise spine (EFT / attachment / ARS) expressing Joash as clinician, supervisor, teacher, and author — deliberately NOT a generic thought-leader (generic dilutes the entity and ranks/cites poorly). Sequence:
  - **Interim (now, through the Nashville phase):** 301-redirect joashkoh.com → a dedicated "Joash Koh" bio page on therapybrentwood.com. Captures name-domain type-ins + branded search and strengthens the entity at near-zero cost. Fully reversible.
  - **Dedicated phase (after Nashville — see Section 9, Phase 4):** build joashkoh.com as a standalone authority hub (new site + hosting + content). A substantial multi-step project (design, build, hosting, content), which is why it is its own phase rather than a Phase 1 task. At launch, remove the redirect and make joashkoh.com the live hub.
  - **Two-property rules (once live):** *Different jobs, no overlap* — therapybrentwood.com = local client funnel; joashkoh.com = person/expert/author/supervisor hub (his name, the ARS framework, EFT training + supervision, thought leadership, speaking, future book/course); joashkoh.com must NOT target "couples therapy nashville" etc. *No duplicate content* — each article on one domain; keep the clinical ARS series on therapybrentwood.com, joashkoh.com hosts the framework's origin/creator story + professional/training layer + thought leadership, LINKING not copying. *Cross-linking + shared Person schema with sameAs* between domains. *Launch lean.*
  - Branded-search bonus: the Nashville leader's clinician-bio pages prove name pages pull real traffic; owning "Joash Koh" captures it.

**E. Measurement**
- Track AI Overview + featured-snippet capture via Semrush (domain_rank exposes serp_ai_overview_keywords and serp_featured_snippet_keywords columns).
- Spot-check ChatGPT / Perplexity / Google AI Overview manually for the core queries monthly.

---

## 9. Sequenced roadmap (AEO-led)

**Phase 1 — AEO foundation + quick wins (weeks 1 to 3).**
- Primary: schema layer (8A) + extractable-answer rewrite (8B) on the money pages (/couples-therapy, /what-is-eft, /eft-vs-gottman, /discernment-counseling) and a new "Joash Koh" bio page.
- Interim 301-redirect joashkoh.com → the new bio page (the full standalone joashkoh.com build is its own phase after Nashville — see Phase 4).
- Quick wins alongside (cheap, correct): cannibalization fix (Section 6) + EFT-Nashville push (Section 7). Modest traffic (~50 to 80 clicks) but free.
- Kick off directory link-building (Section 3A) — lifts all terms at once.

**Phase 2 — Claim Franklin (weeks 3 to 5).** Dedicated Franklin page (Section 5), AEO-formatted from day one. Uncontested by any dedicated competitor page. Nav + mobile overlay + sitemap + resources.

**Phase 3 — Nashville authority page (weeks 5 to 9).** The Nashville differentiation rewrite + indexing fix (Section 4 blocker) and targeting the Section 4 core set, AEO-formatted. Goal: page 1 to 2. Mirror the leader's structure (Section 4A).

**Phase 4 — joashkoh.com standalone authority hub (its own phase, AFTER Nashville).** Build joashkoh.com as a separate site: design, build, hosting setup, and initial content (bio/expertise hub, ARS creator/origin page, supervision + teaching pages). A substantial multi-step project, hence a standalone phase. At launch, remove the interim redirect so joashkoh.com becomes the live hub. Apply the two-property rules in Section 8D (no topic overlap, no duplicate content, cross-linking + shared Person schema).

**Phase 5 — Authority + entity building (ongoing from week 1).** Directory + association links (Section 3A) to move 102 → ~140 referring domains; consistent entity data everywhere.

**Phase 6 — Research + tracking (monthly).** Position + AI-Overview tracking on the three-city set. Watchlist: redtherapygroup (EFT), brentwoodmarriagecounselor (Franklin + Brentwood), nashvilletherapygroup (Nashville). Quarterly backlink re-pull.

---

## 10. Research still worth pulling from Semrush (next units allowing)

- **phrase_questions** on core terms → the real question list that feeds FAQ schema (blocked by units this session).
- **Keyword Gap + broad-match** once units reset, for automated missing-keyword monitoring.
- **brentwoodmarriagecounselor page-level export** + the three leaders' referring-domain lists (specific link sources to replicate).
- **Position-tracking project** with AI Overview flags for measured movement after Phase 1.

---

*Highest-leverage sequence: AEO foundation (schema + extractable answers + the Joash Koh bio page with joashkoh.com redirected in), run cannibalization fix and the EFT push as free quick wins alongside, then the Franklin page (uncontested), then the Nashville authority page, with directory link-building running underneath the whole time.*

---

## 11. Free semantic-gap method + page audits (no paid Semrush)

**Method (replaces the paid Semantic-ideas tab):** for each target page, (1) read our page + the top 2-3 ranking competitor pages for the keyword; (2) read Google's People Also Ask + the cost/how-long questions from a plain search; (3) list topics/terms the ranking pages and questions cover that our page under-emphasizes. That list IS the semantic enrichment.

**Audits completed (Aug 2026). Overall finding: our content quality already beats competitors; enrichment is surgical, not bulk. All three pages already use good extractable "In brief" summaries; none has a formal FAQ block with FAQPage schema — adding that is the top shared win.**

- **/couples-therapy:** Add a "How much does couples therapy cost?" section (every competitor ranks on cost; our page omits it). Weave in plain-language terms searchers use: money/finances, roles & division of labor, life transitions. Work a target term into the first H2 (H1 is emotive, keyword-free — minor). Add FAQs: "Does couples therapy work / is it worth it," "What if only one partner wants to go," "Online vs in-person."
- **/what-is-eft:** Add EFT disambiguation (not Emotional Freedom Technique / tapping, not Greenberg's Emotion-Focused Therapy) — highest-value line. Add a short "EFT for individuals (EFIT) and families (EFFT)" note (leverages triple certification). Add a plain "what happens in an EFT session" beat. FAQ block + schema.
- **/eft-vs-gottman:** Add a "Can you combine EFT and Gottman?" section (the main PAA gap). Otherwise near-complete. FAQ block + schema.

---

## 12. Phase 1 Execution Plan (ordered task list)

Working rules for every milestone: read the full file before editing; make surgical edits only; **verify twice** (pass 1 = new content correct/present, pass 2 = old/forbidden content gone); for multi-file changes use a Python pass for consistency; do not touch nav dropdown + mobile overlay, mobile CSS, unrelated JSON-LD/meta, or biographical content; update sitemap.xml `lastmod` for any edited page; output all touched files. **Double-check after each milestone, then report back before starting the next.**

### Milestone 1 — Quick wins (fast, low-risk, no new sections) — ✅ DONE (Aug 11, 2026)
1.1 `trauma-brainspotting.html` — add "trauma therapy brentwood" into `<title>` and `<h1>` (page ranks #34; Semrush-flagged). *Verify:* term present in both, nothing else changed.
1.2 `couples-therapy.html` — ensure a target term ("couples therapy in Brentwood & Nashville") sits in the first H2 or opening sentence, satisfying the H1-keyword flag without losing the emotive H1.
1.3 `eft-vs-gottman.html` — add 2–3 contextual internal links pointing TO this page from related pages (it's flagged under-linked; ranks #42). Use descriptive anchors.
→ Milestone check: diff review, confirm nav/footer/schema untouched. Report.

### Milestone 2 — Nashville page: MAJOR differentiation rewrite (HIGH PRIORITY, unblocks the Nashville must-win) [see Section 4 blocker] — ✅ DONE + enhanced (awaiting deploy + GSC re-index)
**Scope note — this is NOT minor edits.** `/couples-therapy-nashville` is "crawled — currently not indexed" largely because it overlaps heavily with `/couples-therapy`. It must be rebuilt into a substantially unique, **exceptionally strong, best-in-market** page that stands fully on its own. Treat this as a near-ground-up rewrite of the overlapping sections, not a light pass. **Budget the most time/effort of any Phase 1 task here.** Until this page is genuinely distinct AND indexed, the entire Nashville strategy is blocked.
2.1 Rewrite every passage that overlaps `/couples-therapy` so little to nothing is shared verbatim: replace the "excellent partners in logistics / strangers in intimacy" line, the repeated 75%/gold-standard passages, and the near-identical FAQ answers with fresh, Nashville-specific writing.
2.2 Lean hard into this page's true differentiator that `/couples-therapy` does NOT own: **Nashville + online/telehealth**. Deepen local specificity (neighborhoods, industries — Vanderbilt/HCA/healthcare, music industry, transplant-city isolation, commute/traffic reality) and the online-therapy case (why telehealth, effectiveness parity, discretion, access for shift/irregular work).
2.3 Add genuinely unique value the Brentwood page lacks: a distinct Nashville-specific FAQ, local context/resources, and an online-first intent framing so the two pages serve different searchers.
2.4 Strengthen internal links TO the page from strong indexed pages (home, what-is-eft, resources) with descriptive anchors; add it to the nav dropdown + mobile overlay (BOTH, per house rules).
2.5 Keep/adjust the strong existing schema (self-canonical, ProfessionalService, Service, FAQPage, speakable); update the FAQPage JSON-LD to match the new unique FAQ copy.
2.6 After deploy: request indexing in GSC URL Inspection + re-run validation; monitor index status.
→ Verify twice: unique-content check vs `/couples-therapy` (no verbatim overlap), internal links present, schema matches copy, nav + overlay both updated. Report. **This is the largest single-page effort in Phase 1 — allocate runtime accordingly.**

### Milestone 3 — Cannibalization fix (ADDITIVE-FIRST, low-risk) [see Section 6] — ✅ Step A DONE · ⏳ Step B measuring (~early Sept 2026)
Principle: the competing pages rank at #47–#85 (page 6–9) for "marriage counseling brentwood" — near-zero traffic — so there is almost nothing to lose. Each page keeps its OWN primary keyword untouched. We resolve by consolidation and differentiation, NOT deletion. **No canonical tags, no 301 redirects, no noindex** — these are distinct legitimate service pages that must keep ranking for their own terms.

**Step A (additive, zero-risk) — do first:**
3.1 `couples-therapy.html` — confirm/strengthen it as the single authority for "marriage counseling brentwood (tn)" and "couples counseling brentwood".
3.2 Add internal links from `faq.html`, `premarital-counseling.html`, `discernment-counseling.html`, `contact.html` → `/couples-therapy` with the anchor "marriage counseling in Brentwood." Adds signal, removes nothing.
3.3 **Guard-rail:** do NOT add "marriage counseling brentwood" to `premarital-counseling` (Semrush suggests it; it deepens cannibalization).

**Step B (measure):** wait 2–3 weeks; check whether couples-therapy rises and the duplicates fade on their own. Often Step A is enough.

**Step C (subtractive, only if still needed):** if the wrong pages still outrank couples-therapy, de-emphasize the exact phrase surgically — start with `contact.html` (a contact page shouldn't target a service term), then lightly on service pages via **differentiation** (sharpen each page on its own unique keyword), never by gutting content. Touch `faq.html`'s #13 ranking last.
→ Verify with a Python grep of the phrase across all files after each step. Report.

### Milestone 4 — AEO enrichment: `couples-therapy.html` — ✅ DONE (Aug 11, 2026)
4.1 Add a "How much does couples therapy cost?" section (range + link to fees).
4.2 Weave in searcher terms: money/finances, roles & division of labor, life transitions.
4.3 Add FAQ block (does it work / is it worth it; what if only one partner wants to go; online vs in-person) + FAQPage JSON-LD.
→ Verify. Report.

### Milestone 5 — AEO enrichment: `what-is-eft.html` — ✅ DONE (Aug 11, 2026)
5.1 Add EFT disambiguation line (not Emotional Freedom Technique/tapping; not Greenberg's Emotion-Focused Therapy).
5.2 Add short "EFT for individuals (EFIT) & families (EFFT)" note (leverages triple certification).
5.3 Add a plain "what happens in an EFT session" beat.
5.4 Add FAQ block + FAQPage JSON-LD.
→ Verify. Report.

### Milestone 6 — AEO enrichment: `eft-vs-gottman.html` — ✅ DONE (Aug 11, 2026)
6.1 Add "Can you combine EFT and Gottman?" section.
6.2 Add FAQ block + FAQPage JSON-LD.
→ Verify. Report.

### Milestone 7 — Entity/schema + housekeeping — ⬜ PENDING (next up)
7.1 Person schema for Joash (credentials: LMFT #1970, ICEEFT EFCT/EFIT/EFFT, CCTP; memberOf AAMFT/ICEEFT) on key pages, consistent.
7.2 Prep the "Joash Koh" bio page + interim 301-redirect joashkoh.com → it at DNS. (The full standalone joashkoh.com site is its own later phase — Section 9, Phase 4 — not part of Phase 1.)
7.3 Reconcile URL consistency (e.g. `eft-vs-gottman` footer `/#` vs `/index.html#` links) and sitemap `lastmod`.
→ Verify. Report.

*Order rationale: quick wins bank easy movement first; the Nashville differentiation rewrite comes next because it unblocks the must-win market and is the single biggest build; the cannibalization fix then removes self-competition; AEO enrichment compounds on clean, consolidated pages; entity/schema last as the connective layer.*
