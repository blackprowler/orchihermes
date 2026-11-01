# R10 — Competitor graveyard: why plant-app products die

Date: 2026-10-26 · Track: R10 (backlog: "did past plant apps die from no-traction or no-monetisation?") · Sources inline; sentiment labeled; post-mortems by third parties (no founder-written one found for the plant apps specifically — gap).

## G1 — The dead, with causes of death

| Product | Fate | Cause of death (evidence) |
|---|---|---|
| **Vera** (Bloomscape's free plant app, iOS+Android) | Removed from Google Play 23 Feb 2024; gone from both stores; **no export — user data stranded** | Was "a marketing channel for Bloomscape's plant sales" (getgrowli.app analysis, fetched 2026-10-26); parent's retail business no longer needed it. User impact: "I had all sorts of data about purchase dates, photo progress over YEARS, repotting information" — r/houseplants warning thread https://www.reddit.com/r/houseplants/comments/1hadf84/ (sentiment); insightweeds.com/vera-plant-care-app-disappears-appstore/ |
| **Greg** (VC-backed plant care app, $5.4M seed, TechCrunch 2021; "over 1 million plants") | Shut down 2024; App Store 404; "Greg plant data appears to be permanently inaccessible" | Free end-to-end, funded as Bloomscape marketing channel (same analysis, sprigplantcare.com/blog/greg-plant-app-alternative/) — **the best-funded consumer plant app died without ever charging anyone.** Note: both Greg and Vera trace to the same parent — one corporate decision killed the category's two biggest free products |
| **OrchidWiz (original)** | "Closed OrchidWiz on December 31, 2022" (founder email quoted on Slippertalk https://www.slippertalk.com/threads/orchidwiz-being-retired.52965/ and orchids.org article) — then **revived** at $250, then nonprofit membership $99.99/yr | Cause of first death: unit economics — vendor's own words: "we charged too little for 4 versions per year… 10% of user base getting it free" (WTP-mining §1). **Not a demand death.** The community grief at the closure ("what will we do without you?", orchids.org) + revival proves demand outlived the business model |
| MiIvy, PlantSnap-pricing | Phantom/unverifiable (B-file) | — |
| 2026 orchid-app wave (Orchid Keeper, OrchidManager, Orchid Water & Rebloom, Orchid Journal) | Alive but ~zero traction (B) | Supply-side noise; free solo-dev products; no monetisation attempted yet |

## G2 — Pattern: traction deaths vs monetisation deaths

- **Consumer tier (free care/ID): died from NO-MONETISATION + strategic abandonment.** Greg and Vera never charged; they were CAC funnels for a plant retailer, and died when the parent pivoted. Their users' recorded data died with them — which is precisely the pain the transferable-record thesis targets (watch 2026-10-12 #2, Vera report, was a downstream corpse of this event).
- **Niche tier (records/breeder): died from unit economics, never from lack of demand.** OrchidWiz is the data point: closed voluntarily at $35-class pricing, revived, and now sustains ~1k members at ~$100. The demand persisted through the death — people wrote grief posts and then paid double on return.
- **No plant app found died because "nobody wanted it."** The graveyard's cause-of-death distribution is: parent-company pivot ×2 (huge, free), underpricing ×1 (small, paid), traction-pending ×4 (free, new). The naive optimism the backlog wanted killed is specifically: **"we'll build the free care/records app and monetise later"** — Greg is the counterexample with $5.4M on the tombstone.

## G3 — Design lesson embedded in the graveyard

Every death stranded records; no death stranded anything else people cared about (care tips are commodity — phone Google Lens replaces them free). Implications for any build:
1. **Never be the single copy.** Export/transfer isn't a feature feature, it's the survival promise — and the graveyard is the marketing proof ("your Vera data is gone; ours isn't").
2. **Charge from day one, author-side.** Every free product in the graveyard either died or has zero traction; the only product that ever charged survived its own suicide.
3. **Don't depend on a parent/parent-like subsidy** (platform platform-risk: same as compliance-rule dependence, R8).

## Verdict

R10 answers the backlog question: **this graveyard is not a "demand doesn't exist" graveyard — it's a "free doesn't monetise and underpriced doesn't sustain" graveyard, and the one incumbent that fixed its pricing has been paying-people-supported ever since.** That is cautiously constructive for S4 (paid, author-side, survival-promise product) and fatal for any free-first consumer variant. Consistent with R4's micro-vs-seller-tools fork; adds no new gate.

## Coverage gaps

- No founder-written post-mortems for Vera/Greg (third-party analyses only); Greg shutdown has no official post-mortem found.
- Dead niche forums (orchidboard status unchanged; Slippertalk bodies Cloudflare-blocked — closure quotes are search snippets).
- App-store 1-star "abandoned app" review mining not done systematically (search surfaced threads instead); would add color, not cause-of-death data.
