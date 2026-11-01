# R7 — Marketplace Forensics: does provenance sell plants, and at what price points?

Date: 2026-10-26 · Track: R7 (backlog: "do €100+ listings carrying provenance sell at premium; how is provenance claimed today") · Method: live listing pages via browser + web search; eBay blocked ("SORRY / Something went wrong", fetched 2026-10-26), Etsy listing pages rendered empty via browser (search-snippet level only). Community quotes are sentiment; listing copy is vendor-authored marketing (not verified claims).

## F7.1 — Provenance is ALREADY listing copy, hand-typed (fact about the listings)

- Etsy, Rlc. Aka's Art seedlings: listing body literally reproduces the registry record — "Registered with the Royal Horticultural Society (RHS) in 2020 by A. Buckman, the hybrid is a cross between: Rlc. …" https://www.etsy.com/listing/4498086569/ (snippet, fetched 2026-10-26) — the seller is hand-copying grex/parentage data into prose. No tool; no structured field; nothing the buyer keeps.
- Etsy Epiphyllum cuttings ("Dragonheart", "Three Oranges"): "This is a registered variety called 'Dragonheart'… Whether you are a beginning collector or experienced one this is not to be missed." https://www.etsy.com/listing/50122241/ , https://www.etsy.com/listing/385453006/ (snippets) — registration name = trust token + sales hook, even for a $-level cutting.
- Exotic Plant Company (DE Shopify nursery), Paph. rothschildianum ('Black Panther' x 'Ho #2'): **€350**, copy sells the CROSS not the species — "Some of the finest Paph rothschildianum seedlings are emerging from this cross… This cross has received over 20 Gold medals so far and many SM and BM awards too." https://exoticplantcompany.com/products/paphiopedilum-rothschildianum-black-panther-x-ho-2 (fetched 2026-10-26; vendor marketing) — named clonal parents + award pedigree is the price justification at the top of the market. Same shop: named-cross Paph anitum (Bear #3 x Bear #8 Dark) €250, hangianum (Summer Wine x Huge) €250, plain henryanum €45 — **structured price ladder: unnamed/plain €45 → named cross of awarded parents €250–350** (same page).
- Giulio Celandroni Orchidee (IT Shopify): Paph. rothschildianum x self **€100** https://celandroni.myshopify.com/en/products/paphiopedilum-rothschildianum-x-self (fetched 2026-10-26) — same species spans €100–350 depending on cross/clone claims. Propagation-method claims ("seed grown" vs mericlone vs division) are themselves provenance claims with known price effect (myorchiddiary.wordpress.com 2017; YouTube sv0rclqepoY; bborchids.com blog — fetched 2026-10-26, weak secondary sources).

## F7.2 — Aroid market: verification layer emerging, price base collapsed

- **Aroid Atlas (UK, live, fetched 2026-10-26): 6,957 recorded UK sales, 628 plants, 141 with a "Verified" price badge** — a third party is already monetizing attention around *price/trust verification* for aroids: https://aroidatlas.co.uk/ (also has "Selling a plant" + "Is this a fair price?" flows). The badge mechanism is market evidence that verification is treated as valuable — but see price base below.
- Typical UK prices are LOW: median £9–£18 per genus (Philodendron £13, Monstera £17, Anthurium £18); most-traded named cultivars £16–£41; top October-2026 single sales £141–£519 (Alocasia 'Bambino' Pink £519). Named cultivars ('Thai Constellation', 'Bulbasaur') carry the naming + price, no lineage fields shown.
- Secondary claim (unverified): MonsteraX auction platform, Oct 2025, starting bid $15,000 on a cultivar — "auction record" (tropicalplantkit.com, fetched 2026-10-26) — **NEEDS VALIDATION**; treat as outlier signal that named-cultivar trading infrastructure exists for aroids.
- Read: post-2021-bubble aroid prices sit at cutting-level £10–40 — S4's "record card" cannot be priced into a £20 sale; it only works where F7.1's ladder exists (€100+ / named crosses / award lineage). Orchid beachhead confirmed as the right first market; aroid extension only at the named-cross/auction tail.

## F7.3 — What buyers distrust at point of sale (sentiment, prior + this pass)

- Prior evidence (aroid-adjacency file): variegation-from-seed scam endemic; "you cannot guarantee variegation via seed"; NoID epidemic from lost tags (watch 2026-10-26 #3).
- This pass could not reach buyer-side threads on purchase trust (Etsy bodies empty to this environment; targeted search drifted to car titles). Coverage gap stands.

## F7-verdict — effect on strategy S4

**S4 core claim DIRECTIONALLY CONFIRMED (Medium strength), causal claim NOT testable from public data:**
1. Provenance is already a paid-for feature — it is hand-typed registry prose inside €100–350 listings, and the same species trades 3–8x apart on cross/clone/award claims alone (F7.1, fact about listings). The seller's motive exists and is live; the tooling is copy-paste.
2. The trust-token vocabulary is already standardized enough to structure: grex + registration year/registrant + parent cultivar/cultivar names + propagation method + awards. That is a schema, waiting for a product.
3. But no public dataset shows provenance *causes* better sale outcomes (only correlation-shaped price ladders on vendor claims), and the aroid volume base is too poor to carry a record fee (F7.2). The kill-shot for S4 therefore remains what strategy-review §5 said: smoke test + seller interviews. R7 moves it from "mechanism hypothetical" to "mechanism visible, uninstrumented".
4. New sub-finding worth keeping: a third party (Aroid Atlas) already earns audience/trust as verifier in an adjacent genus — either future competitor for the buyer-trust half of S4, or partner/data source. Watch.

## Coverage gaps (honesty section)

- eBay search blocked entirely this pass; Etsy listing bodies rendered empty — both rest on search-index snippets, labeled above.
- Prices are asking prices (vendor claims), not sold prices, except Aroid Atlas's own recorded-sales figures (itself unaudited).
- MonsteraX $15k bid unverified secondary claim.
- No first-person buyer-trust threads reached this pass (F7.3).
- Causal sale-outcome effect of provenance not testable without platform data or interviews.
