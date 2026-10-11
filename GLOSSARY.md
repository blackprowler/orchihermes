# Glossary & Working Terms

Living document. Every domain, business, and research term used in this workspace gets one line here: **term — meaning — how *we* use it specifically**. Add a term the first time it appears in any note; when two notes use a term differently, that's a bug — resolve it here.

## Business / product-market-fit

| Term | Meaning | In this project |
|---|---|---|
| **WTP** (willingness to pay) | How much a target customer would actually spend on a solution — established via interviews/pre-orders, never assumed | The main unvalidated variable for H1/H2 (see landscape note §3) |
| **PMF** | Product-market fit — a specific market's demand pulling a specific product | Our research goal; evidence bar = repeated unprompted pain + payment behavior |
| **H1 / H2** | Hypothesis 1: hobbyist collection tracker with sharing + plant-history adoption. Hypothesis 2: store/nursery tool for selling + crossing/lineage + plant passports | Illia's two original product ideas (2026-10-10) |
| **MVP** | Minimum viable product — smallest thing that tests the core claim | Belongs to `planning/`, not yet scoped |
| **ICP** | Ideal customer profile | We currently have 3 candidate segments (see below) |
| **TAM/SAM/SOM** | Total / serviceable / obtainable market size | Not yet estimated |
| **Cold-start problem** | A marketplace/network product needs both sides before either side values it | Why the orchid-auction niche scored high-risk (niche-scan §e) |
| **Wedge** | The narrow first use-case that gets a product adopted, from which it expands | Candidate wedge: transferable plant record; possibly breeder tooling |

## Research method

| Term | Meaning | In this project |
|---|---|---|
| **NEEDS VALIDATION** | (from AGENTS.md) Claim that would change product direction if wrong; must be checked before relying on it | Used inline in all notes |
| **Assumption** | (from AGENTS.md) Explicitly-labeled opinion/inference, not sourced fact | Headings in research notes |
| **Primary source** | Direct evidence: interview, forum post, app-store page, registry data | Preferred per AGENTS.md; market reports are secondary |
| **Sentiment** | Community posts prove users *report* something, not that it's true | Labeled as such in evidence files |
| **Coverage gap** | What a research pass could NOT reach, stated honestly | Listed in every evidence file |
| **Pain point** | A recurring, unprompted complaint/workaround in the target's own words | Our strongest: DIY record-keeping (6+ threads) |

## Orchid domain

| Term | Meaning | In this project |
|---|---|---|
| **Grex** | A registered orchid hybrid (the cross itself, not a clone); registration = naming the cross in the RHS International Orchid Register | The unit RHS registers: 4,000+/yr at £12 |
| **Cross / pollination** | Breeding: pollen parent × pod (seed) parent | Core data model of breeder tooling |
| **Pod** | Seed capsule resulting from a successful pollination | Breeder record: pod → flask → seedlings |
| **Flask / tissue culture (TC)** | Sterile gel-culture of orchid seed/meristem in a flask; how clones and bulk seedlings are produced | Nursery/lab workflow; TC-lab software niche = niche-scan §g |
| **Division / keiki** | Vegetative propagation: splitting a plant, or a baby (keiki) growing on one — the "mother-child" lineage case | Clone lineage ≠ seed lineage; both must model in any record schema |
| **True-to-name** | Guarantee that a sold plant matches its named cultivar/hybrid | Buyer-trust mechanism; certification tooling = niche-scan §b (empty) |
| **Virus-free certification** | Lab-tested (e.g. ELISA) claim a plant is virus-free; standard in quality orchid trade | Candidate trust layer for online sales |
| **CITES** | International treaty regulating trade in wild flora/fauna. **All orchid species (all ~30,000) are CITES-listed** — mostly Appendix II, some Appendix I — so even hybrid/flask trade paperwork is regulated | Verified via Kew checklist (community-pain-points §5) |
| **Phytosanitary certificate (phyto)** | Government export document certifying plants pest/disease-free; required alongside CITES for cross-border sales | Hobbyist import pain (pain-points §5) |
| **EU plant passport** | Mandatory label for plant moves within the EU (botanical name, quantity, origin, traceability; since 2019, online sellers included) | H2's "passport" feature; existing label tools lack compliance fields |
| **RHS** | Royal Horticultural Society (UK) — maintains the International Orchid Register, the global grex registry | Registration incumbent: manual PDF forms |
| **AOS** | American Orchid Society — its Commercial Council membership is the trust badge buyers are told to look for when vetting orchid sellers | Informal, non-software incumbent of the certification niche |
| **NAOCC** | North American Orchid Conservation Center — appears alongside AOS in the same buyer-vetting advice; exact role not yet confirmed from a primary source | NEEDS VALIDATION: which cert/badge bodies actually exist for orchid sellers |
| **Reblooming** | Inducing/records of a second bloom cycle (light/temp triggers) | Core hobbyist tracking field |
| **Media / mount** | Potting substrate (bark, lava, sphagnum) or mounting surface; repotting media history matters to orchid keepers | Candidate record field |
| **Incumbent** | Existing tool occupying a niche | e.g. Orchid Album (hobbyist default), OrchidWiz (breeder legacy) |

## Aroid / adjacent-collector domain (added by aroid-adjacency pass 2026-10-11)

| Term | Meaning | In this project |
|---|---|---|
| **Variegation / chimera (CM)** | Sectoral color mutation; usually random and revertible; "CM" = stable chimera | The named-mutation class retaining value post-crash; stability history = record field |
| **Reversion** | A variegated plant reverting to all-green | Disclosure problem at resale; candidate record field |
| **Cutter / cutting culture** | Trade in unrooted stems; provenance = photo of the mother plant | Current de-facto aroid provenance artifact |
| **Plant drop** | Scheduled limited-quantity seller release (IG/Shopify) | Aroid sales channel with no record layer |
| **ICRA** | International Cultivar Registration Authority (per-genus, ISHS-appointed) | Exists for Hoya (hoyacultivars.org) and carnivorous plants (ICPS); nomenclature only, no lineage-transfer tool; none for Philodendron/Anthurium |
| **Leafolio / InPlantory** | Aroid-relevant record apps: Leafolio = iOS collection journal w/ source history; InPlantory (beta) = aroid "botanical record system" w/ mother-plant genealogy | Occupants of the hobbyist-record niche; neither claims seller→buyer transfer. InPlantory teardown 2026-10-11: sign-in shell only, zero external footprint (see evidence/2026-10-11-incumbent-teardown.md) |
| **Velvet30** | All-plant breeding/pedigree web app (aroids-first, orchids in scope); free early beta since ~Apr 2026, Nursery Pro storefront tier planned | Closest conceptual competitor to H2's lineage half; zero visible traction (see evidence/2026-10-11-incumbent-teardown.md)

## Segments (candidate ICPs)

| Segment | Definition | Evidence so far |
|---|---|---|
| **Collector-hobbyist** | Keeps >~20 orchids, feels record pain, DIY-tracks today | Strong (pain-points §1) |
| **Hobby breeder/hybridizer** | Makes crosses, may register grexes at RHS | Volume proven (4,000+/yr registrations), individual WTP unproven |
| **Small nursery / online seller** | Micro to mid nursery or backyard seller selling web/offline | Improving — first-person seller voice sourced round 2 (Etsy forum, r/EtsySellers, GrowerTalks/Hausermann); loudest pain = compliance/takedowns, not records. See evidence/2026-10-11-seller-side-mining.md |
