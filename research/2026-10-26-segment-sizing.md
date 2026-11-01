# R4 — Segment sizing: how many people, how many payers

Date: 2026-10-26 · Track: R4 (backlog: "rough segment sizing: collectors vs breeders vs sellers; orchid vs aroid overlap") · All figures fetched 2026-10-26; sources inline. Third-party Reddit stats (reddapi/hiveindex) are unaudited approximations — labeled.

## 1. Community bases (attention, not payers)

| Segment | Base | Source / quality |
|---|---|---|
| r/houseplants | ~3.0M members | thehiveindex.com (unaudited) |
| r/orchids | ~239k members, ~3.4k indexed posts | reddapi.dev (unaudited) |
| r/aroids | ~43k members | reddapi.dev (unaudited) |
| AOS (American Orchid Society) | "almost 20,000 members when Milton Carpenter was President" (~1990s), widely described as declining since | forum quote (sentiment), not current audited figure |

Overlap assumption **(Assumption)**: orchid⊂houseplants overlap high; orchid∩aroids small but the two record-cultures differ (orchids have grex registry + society judging = deeper provenance habit; aroids trade faster/shallower — matches aroid-adjacency file).

## 2. The funnel that matters: attention → payer (calibrated by the ONE incumbent we can see)

OrchidWiz is the only breeder-tool with a countable history (WTP-mining §1): community base ~239k r/orchids ⇒ demonstrated paying base **~1,000** at $99.99/yr after reprice. Implied attention→payer conversion for a paid records/breeder tool ≈ **0.4%** (Assumption: r/orchids ≈ breeder-adjacent population proxy; OrchidWiz buyers skew breeder/judge, a small core of the sub).

Sanity cross-check: RHS registers 3,000+ new hybrids/yr (web.archive of RHS page; current RHS page confirms role, volume figure from D§a 2026-10-10). Active registrant hybridizers globally plausibly **2,000–5,000** (many register multiple grexes/yr) — OrchidWiz's ~1k payers ≈ 20–50% of that population: the incumbent already holds a large share of the breeders who pay at all.

## 3. Seller side

- Etsy plant-shop count: **not retrievable** this pass (market pages render generic; no shop-count stat exposed) — gap.
- Proxy: Aroid Atlas recorded **6,957 UK aroid sales across 628 plants** in its (short) operating window — implies hundreds-to-low-thousands of semi-active UK aroid sellers alone; orchid equivalent plausibly similar order across EU+US small sellers **(Assumption, weak)**.
- The €100+ ladder where provenance sells (R7 F7.1) is a tail of that population, not its bulk (aroid medians £9–18; orchid mass market is grocery Phalaenopsis).

## 4. What the sizes mean against strategy-review exit thresholds

Decision row revisit condition was: "downgrade to micro-business if total reachable market < ~$250k/yr". Arithmetic on the two payer pools, at WTP-mining anchors:

- **Breeders:** 2k–5k population × OrchidWiz-realistic capture (10–25%) × $99/yr ⇒ **$20k–$124k/yr** at steady state, against an entrenched nonprofit incumbent. Below threshold even at the optimistic edge.
- **Sellers (S4 thesis):** N sellers × capture% × price. Threshold-busting needs e.g. 1,000 paying sellers at €20/mo — possible ONLY if the record-card rides listings and demonstrably helps sales (R7's untested causal claim), priced per-seller not per-plant.
- **Hobbyist inheritors:** non-payers by evidence (WTP-mining §2); free surface only.

**Verdict:** the *current* market for paid plant records is already a micro-market (~$100k/yr, incumbent-held). S4 only exceeds micro-business scale if it monetizes the *transaction-trust* function for sellers at listing volume — i.e., a different, larger market (seller tools for rare-plant e-commerce) that no incumbent currently serves and for which we still have zero revealed-preference evidence. Both branches are honest: "niche micro-business" (breeder/seller tools, lifestyle scale) vs "unproven larger seller-tools market". **This is exactly the fork smoke-test + interviews must decide — R4 does not resolve it, and pre-registers that no further agent sizing will.**

## Coverage gaps

- No audited member counts (Reddit stats unaudited; AOS figure historical quote).
- Etsy/eBay seller counts unreachable (R7 block persists).
- Hybridizer population is an inference from registration volume, not a census.
- Germany-specific seller counts: R8 noted fees unpublished; no counts either — one phone call to state Pflanzenschutzdienst would still settle the EU-seller denominator.
