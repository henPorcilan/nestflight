# Nestflight

Family trips, planned the way a frequent flyer would do it: cross-reference the kids' school calendars, match destinations to the ideal time of year, and surface the deals and points redemptions that make the trip cheaper.

**Status:** Phase 0 — Validate, on a compressed ~3-week timeline (time-to-market is the priority — see `ROADMAP.md`). Landing page is live with a working waitlist form. See the open [Issues](../../issues) for what's next — parent interviews and the first affiliate application are the two things left in this phase.

**Try it now:** [landing page](https://henporcilan.github.io/nestflight/) (live) · [interactive prototype](prototype/index.html)

## What's in this repo

| Path | What it is |
|---|---|
| `index.html` | Live landing page with waitlist signup (Google Form embed link). |
| `prototype/index.html` | Interactive concept prototype — family travel profiles, school-calendar window matching, destination scoring, deals radar, miles/points tracker, membership tiers, and a per-trip budget/itinerary board. Single-file HTML, open it directly in a browser. |
| `ROADMAP.md` | CEO-level assessment: market sizing, competitive landscape, monetization model, compressed phased roadmap, key metrics, and risks. |
| `MVP-SCOPE.md` | The ruthless cut line for what ships in Phase 1 — what's in, what's explicitly deferred. |
| `docs/landing-page-copy.md` | Source copy for the live landing page. |
| `docs/parent-interview-script.md` | 20-minute discovery interview script for validating the concept with 30–50 parents (Phase 0). |
| `docs/recruitment-outreach.md` | Ready-to-post copy for recruiting interview participants (personal network, FB groups, listservs). |
| `docs/affiliate-network-research.md` | Which flight/hotel/credit-card affiliate networks are realistic to get approved for pre-launch, and in what order to apply. |
| `docs/affiliate-application-answers.md` | Ready-to-paste answers for each affiliate network's application form. |
| `docs/domain-shortlist.md` | Candidate domain names to check once the wedge is validated. |
| `interview-tracker.xlsx` | Spreadsheet for logging the 30–50 discovery interviews, with a live summary/progress sheet. |

## Why this exists

No single product today combines: (1) actual school-calendar-aware trip timing, (2) ideal-season destination matching, (3) mistake-fare/flash-deal hunting, and (4) miles & points optimization. The prototype demonstrates all four working together, plus a monetization model (free tier + Premium/Concierge subscriptions + affiliate booking commissions) built directly into the UI.

## Current phase: Validate — compressed to ~3 weeks

- [x] Landing page + waitlist live
- [ ] 30–50 parent discovery interviews completed (tracker: `interview-tracker.xlsx`)
- [ ] At least 2 realistic calendar-sync sources confirmed (ICS import, not school-district scraping)
- [ ] First affiliate network application submitted (see `docs/affiliate-application-answers.md` — start with TravelPayouts)
- [x] MVP scope locked (`MVP-SCOPE.md`)

Track detailed tasks in the [Issues](../../issues) tab, grouped by milestone (`Phase 0 — Validate`, `Phase 1 — MVP`, `Phase 2 — Monetize`, `Phase 3 — Scale`). A weekly automated check-in reviews progress against this list every Monday.

## Recommendation (from the CEO assessment)

Build it — the school-calendar wedge is genuinely underused — but don't build the concierge/booking layer or chase school-district partnerships until there's hard evidence families return to plan again ahead of the next school break. That's the one metric that decides whether this is a business or a nice demo. Full reasoning in `ROADMAP.md`.
