# Competitive Landscape & Opportunity Gap Analysis

Date: 2026-10-11 · Status: synthesis of four evidence tracks · Author: Hermes research pass 1

Evidence base (all in `evidence/`, each claim carries its own source URL + date):

| Track | File | Scope |
|---|---|---|
| A | `evidence/2026-10-10-community-pain-points.md` | Hobbyist + small-nursery pain points (r/orchids, forums, App Store reviews, CITES/Kew) |
| B | `evidence/2026-10-10-competitors-hobbyist-apps.md` | 21 consumer apps, 3 tiers, prices + sharing features |
| C | `evidence/2026-10-10-competitors-nursery-tools.md` | Nursery software, breeding registries, plant passports, plant e-commerce |
| D | `evidence/2026-10-10-niche-scan.md` | 8 candidate niches ranked crowded → empty |

Inline citations below use track letters (A/B/C/D) + the section they come from; the underlying URLs are in those files. Claims from my own reasoning are marked **(Assumption)**.

---

## 1. Both hypotheses are directionally supported, but neither as first scoped

**H1 (hobbyist collection tracker + social + plant-history adoption).** Demand is the best-evidenced thing in this research. Record-keeping is unsolved and DIY across 6+ independent r/orchids threads (2022-2025): plant tags, phone photo albums, notebooks, Excel, dot-stickers plus Google Calendar (A§1). A template economy already exists — free Orchideria Excel tracker, Etsy "Orchid Journal" templates, forum threads requesting spreadsheets (A§1). One user states the sharing wish explicitly: an Excel sheet that works "but I want to send it to people who want to see my collection" (A§1).

Supply is weak but **not empty**, and that matters for how H1 is scoped. General care/ID apps converged on $30-80/yr subscriptions — PictureThis $39.99/yr, Planta $35.99/yr, PlantIn $29.99-39.99/yr, Blossom $59.99-79.99/yr (B) — none carries collection provenance. Orchid-specific apps sit at $4.99-7.99 one-time and are solo-dev projects: Orchid Album ($7.99, 2014, no cloud, dormant, distrusted as a system of record — "do not use this app as your only record") is still the community default; four new orchid apps shipped Mar-Sep 2026 (Orchid Keeper with a tag scanner and hybrid lineage, OrchidManager, Orchid Water & Rebloom $4.99, Orchid Journal free) with near-zero traction (B).

The genuinely unclaimed feature inside H1 is **history handover**. Across 21 competitors plus QR label vendors, the only precedent is Orchid Journal's offline "gift an orchid" shareable file (B). Nobody ships QR-tag + journal + ongoing record transfer to a new owner; QR label vendors (qrlog, joyofplants) stop at the original owner (B). Provenance loss is a live pain: "tag graveyard", cryptic nursery tags, inherited plants arriving with zero history (A§2).

So H1's tracker-plus-social framing walks into a crowded $30-80/yr band with four free orchid apps already competing, while H1's adoption/history framing points at something nobody has built. **(Assumption)** the second half is the wedge; the first half is the distribution surface.

**H2 (store tool: sell + track history + crossing/mother-child + passports).** The gap is real but the incumbents are real too. Nursery management exists at the big end (GrowerIQ, AGRIVI, Farmbrite, Agworld, ET Grow, Argos/SBI/Mprise Agriware cluster, Small Grower Software) and none is orchid-tuned; small nurseries run Google Sheets plus bolted-on barcode hacks (A§6). Plant-pollination and pedigree logging exists conceptually in Velvet30 — pollinations with pod/pollen/date/method, auto-built multi-generation pedigree trees, private-by-default with public share pages — the closest competitor to H2's lineage half, but with no commerce, no nursery inventory, no passport fields (C§2). EU plant-passport generation is served by Feedentity-style tools and tag printers (Sunfire POS, Rapid Garden POS) whose labels show no evidence of passport-compliant fields (C§3, NEEDS VALIDATION).

What no incumbent connects is the two sides: nothing lets a vendor publish care/lineage history that a buyer then inherits (B). That is H2 and H1 meeting in the middle, and it is the single strongest structural gap found.

## 2. The niche that may beat both

**Hybridizer/breeder tooling** is the emptiest niche with proven, quantified volume (D§a). RHS registers 4,000+ new orchid hybrids/yr at £12 per name, submitted via manual PDF forms (C§2, D§a). The only incumbent, OrchidWiz, is legacy Windows-only at $35 (C§2). Reddit users note apps don't cover creating crosses (D§a). No maintained open-source orchid tracker exists — GitHub search returned zero orchid-plant apps above 2 stars; all top "orchid" repos are unrelated software that happens to share the name (D§h).

Ranking from D, crowded → empty: (f) AI disease diagnosis — crowded, generalists at ~98% accuracy; (g) tissue-culture LIMS — thin and already filling with three recent entrants; (d) orchid show management — thin duopoly but the market is tiny by design, thin supply because thin demand; (a) breeder tooling — thinnest with proven volume; (b) provenance/true-to-name certification — no tooling at all, willingness to pay unproven; (c) CITES compliance for small sellers — empty, real regulatory pain, small buyer base; (e) dedicated orchid auction — empty but two-sided cold-start against eBay/Etsy "good enough".

Breeder tooling scores highest on demand/supply ratio and, importantly, runs on the same lineage engine H2 needs. **(Assumption)** a breeder-first product could seed the collection data that makes H1's adoption feature valuable, rather than needing to bootstrap hobbyist records from zero.

## 3. Convergent read across all four tracks

One pattern repeats in every file: **the record, not the reminder, is the unmet need.** Every incumbent optimises care instructions or identification; the pain people describe is losing, being unable to trust, or being unable to transfer the plant's history (A§1-2, B gaps, C§2, D§a-b). Willingness to pay is where evidence stops being strong — that is the honest limit of this pass.

| Claim | Strength |
|---|---|
| Hobbyists keep records in broken DIY tools | Strong — 6+ independent threads, template economy, incumbent distrusted |
| Nobody ships owner-to-owner history transfer | Strong — checked across 21 apps + QR vendors; one offline gift-file precedent |
| Breeder workflow is under-tooled at real volume | Strong — 4,000+/yr RHS registrations, £12 each, one Windows incumbent |
| Small nurseries have no adopted vertical SaaS | Medium — Sheets + barcode hacks, but no first-person orchid seller threads captured |
| Willingness to pay for any of it | **Weak — unvalidated.** Collector-depth SaaS pricing unproven (B); breeder WTP unproven (D); certification WTP weak (D§b) |
| CITES/phyto as a product wedge | Medium pain, small market; users say cross-border is "expensive, complex and not worth doing" (A§5) — the viable form is seller-side compliance guidance, not a hobbyist import tool |

## 4. Open questions that should be answered before scoping

1. **Willingness to pay**, three ways: what a collector-depth orchid SaaS can charge between the $4.99 one-time floor and the $30-80/yr general ceiling; what hybridizers pay today (OrchidWiz/OrchidList prices were not fetchable — JS-rendered pages, D§supply-price); what a seller pays for a listing that carries verifiable history.
2. **OrchidWiz teardown** — features, price, install base, why it survived on Windows. It is the only proof someone will pay for orchid lineage tooling.
3. **First-person seller interviews.** The largest coverage gap: no orchid-seller thread was reached at all (A coverage gaps). H2 rests on inferred need.
4. **EU passport field-level check** on Sunfire/Rapid Garden labels (C§6).
5. **Velvet30 traction** — if it has real users, the lineage gap is already closing (C§6).

## 5. Recommended next step

Do not pick between H1 and H2 yet. The evidence supports testing one product shape that contains the unclaimed halves of both: **a transferable plant record (QR-tagged, orchid-specific, carrying lineage + care + health history) that a nursery or breeder creates and a hobbyist inherits.** Demand-side pain is proven; the pricing and seller-participation questions are what a validation round must answer. Recorded as a decision pending owner sign-off — see `planning/decisions.md`.

Flagged **NEEDS VALIDATION** because it would change product direction: treating breeder tooling as the wedge rather than a feature.

## Coverage gaps (carried from evidence files)

- Reddit thread bodies unreachable from this environment (reddit.com, .json, old.reddit, api.reddit, redlib mirrors all blocked); evidence rests on search-index snippets — comment-level dates unverified (A).
- orchidboard.com behind a Cloudflare challenge; only titles + search descriptions obtained (A).
- No first-person orchid-seller sources; selling pain is buyer-side and adjacent plant subs only (A).
- Breeding-records pain inferred from the registry gap, not directly quoted (A§7).
- "MiIvy" could not be found in any store and is treated as a phantom app; PlantSnap pricing unverifiable, JS-only page (B).
