# Nestflight

Family trips, planned the way a frequent flyer would do it: cross-reference the kids' school calendars, match destinations to the ideal time of year, and surface the deals and points redemptions that make the trip cheaper.

**Status:** Phase 0 — Validate. Interactive concept prototype built; not yet a live product. See `ROADMAP.md` and the open [Issues](../../issues) for what's next.

## What's in this repo

| Path | What it is |
|---|---|
| `prototype/index.html` | Interactive concept prototype — family travel profiles, school-calendar window matching, destination scoring, deals radar, miles/points tracker, membership tiers, and a per-trip budget/itinerary board. Single-file HTML, open it directly in a browser. |
| `ROADMAP.md` | CEO-level assessment: market sizing, competitive landscape, monetization model, phased roadmap, key metrics, and risks. |
| `docs/landing-page-copy.md` | Draft copy for a waitlist landing page (Phase 0). |
| `docs/parent-interview-script.md` | 20-minute discovery interview script for validating the concept with 30–50 parents (Phase 0). |
| `docs/affiliate-network-research.md` | Which flight/hotel/credit-card affiliate networks are realistic to get approved for pre-launch, and in what order to apply. |

## Why this exists

No single product today combines: (1) actual school-calendar-aware trip timing, (2) ideal-season destination matching, (3) mistake-fare/flash-deal hunting, and (4) miles & points optimization. The prototype demonstrates all four working together, plus a monetization model (free tier + Premium/Concierge subscriptions + affiliate booking commissions) built directly into the UI.

## Current phase: Validate (Weeks 0–8)

- [ ] Landing page + waitlist live
- [ ] 30–50 parent discovery interviews completed
- [ ] At least 2 realistic calendar-sync sources confirmed (ICS import, not school-district scraping)
- [ ] First affiliate network application submitted (see `docs/affiliate-network-research.md` — start with TravelPayouts)
- [ ] MVP scope and the one success metric (seasonal return rate) defined

Track detailed tasks in the [Issues](../../issues) tab, grouped by milestone (`Phase 0 — Validate`, `Phase 1 — MVP`, `Phase 2 — Monetize`, `Phase 3 — Scale`).

## Recommendation (from the CEO assessment)

Build it — the school-calendar wedge is genuinely underused — but don't build the concierge/booking layer or chase school-district partnerships until there's hard evidence families return to plan again ahead of the next school break. That's the one metric that decides whether this is a business or a nice demo. Full reasoning in `ROADMAP.md`.
