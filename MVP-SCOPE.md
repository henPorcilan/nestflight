# Nestflight — MVP Scope (Phase 1)

Time-to-market is the constraint. This document exists to say no to things, not to list features. If it's not on the "In" list, it does not ship in the MVP — no exceptions without cutting something else first.

## The one thing the MVP has to prove

**Seasonal return rate:** do households come back to plan again ahead of the next school break? Nothing else matters until we can measure this. Every feature below is justified only by whether it helps us reach a first measurement of that number faster.

## In (ships in Phase 1)

- **Family travel profiles** — name, role (parent/kid), travel style, interest tags. Already built in the prototype; port as-is.
- **ICS calendar import** — parent pastes a school's public ICS/iCal export link per kid. No school portal integration, no scraping.
- **Window matching** — overlap kids' calendars into travel windows. Already built; port as-is.
- **Destination matching** — the scoring engine from the prototype (season + vibe + interest tags), against a hand-curated list of 15-20 destinations. Not a live pricing API yet.
- **Manually curated deals feed** — a short list of real flight/hotel deals, updated by hand 1-2x/week. Not a scraped or automated feed.
- **One working affiliate link** — via TravelPayouts (see docs/affiliate-network-research.md), so "Book now" is a real, trackable revenue event.
- **Free tier only** — no billing integration, no subscriptions yet.
- **Basic analytics** — track: profile completions, return visits, deal clicks, affiliate clicks. This is the instrumentation the whole MVP exists to produce.

## Out (explicitly deferred, do not build)

- Miles & points tracker / redemption calculator — nice, not load-bearing for the core hypothesis. Defer to Phase 2.
- Membership tiers / Premium subscription billing — no paying customers to bill yet. Defer to Phase 2.
- Real-time deal scraping or a fare-alert API integration — expensive, and manual curation is enough to test demand. Defer to Phase 2.
- Concierge / human-agent booking — Phase 3, and only once Premium users are asking for it.
- School-district direct calendar integrations — slow, legally heavier, and ICS import covers the same need faster.
- Native mobile app — web is enough to test the hypothesis.
- Multi-language / international school calendars — US only for now.

## Definition of "MVP shipped"

A parent can, unassisted: build a family profile, see their real school-break windows, get a matched destination list, click into one real affiliate booking link, and (separately) come back a second time in a later session. That loop, end to end, is the whole bar.

## Cut list if we're still behind schedule

If Phase 1 is still not shippable by the deadline in ROADMAP.md, cut in this order before touching the core loop above: (1) reduce curated destination list from 20 to 8, (2) reduce curated deals feed to weekly instead of twice-weekly, (3) narrow ICS import to a single supported school-portal export format instead of generic ICS parsing edge cases.
