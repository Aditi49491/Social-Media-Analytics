# upGrad Social Media Analytics — Campaign Plan

A data-driven social & performance marketing plan for **upGrad's M.Sc. in Data Science**, built as an application project for a **Social Media Analytics** role (Google Trends / Meta Ads / funnel analytics).

Instead of a generic content calendar, this project simulates the actual workflow of a performance-marketing analyst: pull real demand and competitor data → design a channel & budget strategy → build a measurement and attribution framework → show the statistical rigor behind test decisions.

📁 **Deck:** [`upGrad_Social_Media_Analytics_Project.pptx`](./upGrad_Social_Media_Analytics_Project.pptx) · 12 slides

---

## Why this project

Most "social media marketing" application projects are a content calendar and a vibe. This one is built the way the job actually works: every recommendation is traced back to a data source (a live Google Trends export, a live Meta Ads Library pull, a public brand stat) or flagged explicitly as a stated, testable assumption — never presented as real data it isn't.

## What's inside

| # | Slide | What it shows |
|---|-------|----------------|
| 01 | Objective | The problem framing: seasonal demand, dense competition, CPL as the fundability metric |
| 02 | Category context | upGrad's Data Science portfolio (IIIT-B / LJMU), scale, and 6 competitors to benchmark |
| 03 | Demand timing | **Live Google Trends export** (India, 12 months) — when search demand actually peaks vs. when the "obvious" New Year spike assumption breaks down |
| 04 | Competitive intelligence | **Live Meta Ads Library teardown** of 7 Simplilearn + 8 Great Learning ads, scored on hook / proof / CTA / format / offer |
| 05 | Audience | Two personas ("The Pivoter," "The Upskiller") with distinct targeting logic per platform |
| 06 | Platform strategy | Why LinkedIn, Meta, and Google each play a different funnel role rather than competing for the same budget |
| 07 | Budget plan | A funnel-shaped ₹5L budget split, not an even one |
| 08 | Measurement | Weekly KPI targets (CTR, CPL, MQL rate, CAC) and the reporting stack behind them |
| 09 | Attribution model | Position-based attribution vs. last-click — shows why last-click would (wrongly) tell you to cut LinkedIn |
| 10 | Test design | The actual sample-size math behind "95% confidence," including why MQL-rate tests aren't practical at this budget |
| 11 | Summary | Why the approach is timed, benchmarked, and accountable |

## Methodology & data sources

- **Google Trends** — live export, India, past 12 months, for "data science course" and "online MBA"
- **Meta Ads Library** — live pull of currently-running Simplilearn and Great Learning ads (India), manually scored against a 5-point creative rubric
- **Public brand/category stats** — upGrad's own learner and program data, competitor-published outcome claims, cited where used
- **Attribution model** — position-based weighting (40% first touch / 40% last touch / 20% middle), illustrated on the slide 7 budget scenario since it needs UTM-tagged, CRM-joined journey data that only exists inside a live campaign
- **Sample-size / MDE math** — standard two-proportion z-test formula (95% confidence, 80% power), applied to this campaign's assumed CPM/CTR/CPL baselines

**What's real vs. illustrative is labeled on every slide.** Anything that requires a live ad account, CRM, or campaign history (attribution journeys, weekly performance numbers, budget pacing) is explicitly marked as an illustrative model built on stated assumptions — not dressed up as live results.

## Tools used

Google Trends · Meta Ads Library · Google Sheets (mock reporting logic) · two-proportion z-test for sample sizing

## Caveats

This was built outside a live ad account, so campaign performance numbers (CTR, CPL, MQL rate, CAC) are **pre-launch targets benchmarked against public edtech CTR/CPL ranges**, not results from a real campaign. The attribution and budget-pacing slides use a stated, disclosed weighting model rather than actual UTM/CRM data. Swap-in points for live data are called out directly on the relevant slides.

## Author

Aditi Sachdeva
