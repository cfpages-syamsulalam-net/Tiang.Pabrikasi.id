# Topical Authority — tiang.pabrikasi.id

## Role and boundary

`tiang.pabrikasi.id` should become an Indonesian buyer-and-project knowledge hub for engineered pole systems: translating a site need into a design brief, fabrication package, protected steelwork, foundation/interface plan, safe erection, inspection, and maintainable asset. The domain may explain antenna, CCTV, lighting, high-mast, utility/telecom, traffic-signal, and lightning-protection applications because those systems already have commercial routes here.

The editorial hub must not impersonate a structural engineer, electrical designer, lightning-protection specialist, geotechnical engineer, welding inspector, or lifting supervisor. Dimensions, loads, welds, foundations, anchorages, electrical protection, lightning-protection design, lifting plans, and work-at-height controls require project-specific calculations, current applicable standards, competent review, and documented acceptance. Product/service quotations stay on the existing commercial routes; neutral learning articles answer one informational job each.

Geographic landing pages are not article ideas. A city, province, or district substitution does not create a distinct editorial intent. Other owned domains may independently discuss the same entity from their own viewpoint; cannibalization control applies only within this domain.

## Evidence audited

- Canonical Git origin `cfpages-syamsulalam-net/Tiang.Pabrikasi.id`, branch `main`, commit `e5997fc`.
- The tracked export contains 5,300 files; `README.md` records 4,016 URLs.
- Rank Math sitemap index plus 20 post sitemaps and one page sitemap were inspected. The selected files expose 3,930 sitemap URL entries; export inventories and tracked files also include archives and other generated routes.
- Eight large geographic filename families dominate the root: antenna (488), CCTV (489), high-mast (491), garden-light (490), electrical (489), lightning-protection (491), PJU (490), and traffic-light (489).
- Core commercial routes audited: `/antena/`, `/cctv/`, `/high-mast/`, `/lampu-jalan-pju/`, `/lampu-solar-energy/`, `/lampu-sorot/`, `/lampu-taman/`, `/led-lighting/`, `/listrik-telkom/`, `/pemasangan-pju/`, `/penangkal-petir/`, and `/traffic-light/`.
- Material routes audited: `/bahan/aluminium/`, `/bahan/bambu/`, `/bahan/besi/`, `/bahan/beton/`, `/bahan/fiber-optik/`, `/bahan/hollow/`, `/bahan/komposit/`, and `/bahan/stainless/`.
- Archive evidence: `/berita/`, category archives, pagination, and an author archive.
- Runtime evidence: `.head` loads an unversioned external script from `cekkode.github.io`; this needs owner and integrity review before it is treated as a dependable site component.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/` | Commercial manufacturer landing page; broad “tiang lampu jalan” positioning | keep | Commercial home | Verify claims, company identity, service area, and conversion tracking |
| Core product routes listed above | Clear quote/service intent but possible overlap with future neutral guides | expand | Each existing commercial route owns transactional intent | Separate sales copy from informational guides; verify canonical, H1, schema, and contact path |
| `/bahan/*/` | Material-led commercial pages; several names can imply suitability without engineering context | manual review | Material commercial routes; TPG-04 owns neutral selection | Verify actual supplied materials, terminology, certificates, structural suitability, and unsupported comparisons |
| `jual-pasang-tiang-<type>-<location>.html` | Roughly 3,917 location-swapped files across eight families; high doorway, duplication, crawl, and maintenance risk | manual review | One strong type route plus genuinely evidenced service-area information | Export GSC data, index status, leads, backlinks, canonical tags, content similarity, and business presence before merge/noindex/removal |
| `/berita/` and category archives | Discovery surfaces with thin/paginated archive risk | keep | Editorial archive | Verify unique indexable value, pagination canonicals, crawl depth, and orphan pages |
| Author archive | Likely little independent search value | noindex | Article bylines and author profile if substantive | Confirm author archive traffic/backlinks before changing |
| Sitemap set | Multiple static sitemap artifacts and count mismatch with README inventory | manual review | One generated canonical sitemap index | Crawl all sitemap URLs; verify 200 status, canonical, indexability, lastmod accuracy, and duplication |
| `.head` external JavaScript | Unversioned third-party runtime dependency | manual review | Site owner/deployment pipeline | Identify purpose, pin/re-host or remove, review source and privacy/security impact |

## Coverage matrix

| Lifecycle stage | Knowledge need | Topic owner | Existing commercial support |
|---|---|---|---|
| Discover | Pole-system taxonomy and application choice | TPG-01 | Product routes |
| Define | Site survey, requirements, and design brief | TPG-02 | Contact/quotation flow |
| Engineer | Loads, stability, fatigue, and serviceability | TPG-03 | None; requires engineering evidence |
| Select | Material, section, connection, and access details | TPG-04 | `/bahan/*/` |
| Make | Fabrication sequence and tolerances | TPG-05 | Home/manufacturer positioning |
| Join | Welding qualification, inspection, and repair | TPG-06 | None |
| Protect | Galvanizing, paint, duplex, and corrosion detailing | TPG-07 | Material/product routes |
| Support | Base plate, anchors, embedded systems, and foundations | TPG-08 | Installation routes |
| Apply | Antenna, CCTV, and telecom poles | TPG-09 | `/antena/`, `/cctv/`, `/listrik-telkom/` |
| Illuminate | PJU, solar, garden, and floodlighting | TPG-10 | Lighting routes |
| Operate high mast | High-mast structure and lowering system | TPG-11 | `/high-mast/` |
| Control/protect | Utility, traffic-signal, and lightning mast distinctions | TPG-12 | Utility, traffic, lightning routes |
| Integrate | Cable routing, earthing, bonding, and lightning interfaces | TPG-13 | Electrical/lightning routes |
| Deliver | Transport, lifting, erection, and K3 | TPG-14 | Installation routes |
| Sustain | Inspection, diagnosis, repair, and replacement | TPG-15 | Service routes |
| Procure/accept | BOQ, submittals, QA records, handover, and lifecycle cost | TPG-16 | Contact/quotation flow |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| TPG-01 | Pole-system fundamentals | Identify the correct pole family and vocabulary before requesting a quote | Pole versus mast; self-supporting versus stayed; fixed versus lowering; tapered versus prismatic; segment and joint types; application constraints; false equivalences; decision sequence | Taxonomy diagram, comparison matrix, glossary, expert review | Does not specify member size, foundation, electrical system, or a vendor; those belong to TPG-02/03/08/13 and commercial routes | 6 |
| TPG-02 | Requirements and site investigation | Produce a usable, risk-aware design brief | Asset purpose; mounted equipment; height/reference points; coordinates and exposure; access; soil/geotechnical inputs; utilities; maintenance method; environmental class; permits; missing-input register | Survey checklist, annotated brief, site-photo protocol, responsibility matrix | Does not turn observations into a certified structural/geotechnical design | 6 |
| TPG-03 | Structural behavior and design evidence | Understand what engineers must calculate and what evidence to request | Dead, wind, seismic, ice/rain where relevant, cable, maintenance and accidental actions; load combinations; drag area; deflection, vibration, fatigue, buckling, second-order behavior; design life; uncertainty | Load-path diagrams, worked method with non-project sample inputs, current primary standards, licensed-engineer review | No universal safe height/thickness/load and no project design values | 6 |
| TPG-04 | Materials, sections, and connections | Compare structural options without choosing by price or label alone | Carbon steel, stainless, aluminium, concrete, composite, timber/bamboo limits; round/polygonal/hollow sections; taper; flange/slip/spigot/bolted details; access doors; material traceability; galvanic compatibility | Decision tables, section drawings, certificate checklist, engineer review | Does not declare every material route structurally suitable or replace calculations | 6 |
| TPG-05 | Fabrication and dimensional control | Audit how a design becomes repeatable fabricated parts | Drawing release; cutting; forming/rolling; seams; drilling; flange and stiffener fit-up; straightness; segment trial assembly; tolerances; identification; hold points; nonconformance | Process map, traveler template, dimensional checklist, original shop photos when available | Does not claim shop capability, tolerances, or results without records | 6 |
| TPG-06 | Welding quality | Request and interpret welding controls and inspection records | WPS/PQR/WPQ concepts; consumables; joint preparation; fit-up; preheat/interpass where specified; distortion; visual/NDT selection; acceptance criteria; repair cycle; inspector competence | Weld-detail diagrams, document matrix, inspection checklist, current applicable standards, qualified review | Does not prescribe parameters, NDT extent, or acceptance clauses for an unnamed project | 6 |
| TPG-07 | Corrosion protection | Choose a protection strategy and diagnose avoidable coating failures | Exposure and design life; drainage and crevices; hot-dip galvanizing; paint systems; duplex systems; internal surfaces; vent/drain holes; field repair; stainless/aluminium interactions; inspection and maintenance | Environment decision tree, coating-system comparison, defect atlas, thickness/adhesion records, specialist review | Does not promise coating life or prescribe a system without environment and specification | 6 |
| TPG-08 | Base, anchors, and foundations | Understand the full load-transfer chain and required coordination | Base-plated versus embedded; anchor cage; templates; grout; shear transfer; edge distance; pedestal; soil investigation; overturning/uplift; settlement; drainage; tolerances; survey; remediation | Load-path diagram, interface checklist, survey sheet, geotechnical and structural review | No generic footing or anchor dimensions; project engineering owns them | 6 |
| TPG-09 | Antenna, CCTV, and telecom applications | Define mounted-equipment and performance requirements for communication/security poles | Antenna area and cable loads; line of sight; camera field of view; vibration; access; equipment cabinet; cable segregation; future additions; fall protection; privacy and permissions | Application matrices, field-of-view/line-of-sight diagrams, equipment schedule, specialist review | Sales/installation intent belongs to `/antena/`, `/cctv/`, and `/listrik-telkom/`; radio/network design is excluded | 6 |
| TPG-10 | Lighting poles | Coordinate pole, luminaire, power source, optics, and maintenance | PJU, garden, flood, LED, and solar distinctions; mounting height versus photometry; outreach arms; wind area; cable door; battery/panel loads; glare; access; spacing studies; maintenance | System diagrams, photometric input checklist, comparison matrix, lighting/electrical review | Does not publish universal spacing/wattage or replace photometric/electrical design; sales intent stays on lighting routes | 6 |
| TPG-11 | High-mast systems | Understand why a high mast is a system, not a taller PJU pole | Headframe/crown; lowering/raising mechanism; winch, rope, latches; luminaire ring; wind and fatigue; foundation; lightning/electrical interfaces; commissioning; rescue and maintenance | Component diagram, FMEA-style checklist, commissioning records, manufacturer and engineer evidence | Does not authorize operation, rescue, or mechanical settings without the system manual and competent team | 6 |
| TPG-12 | Utility, traffic, and lightning-support applications | Distinguish three regulated/specialist systems and prepare the right interfaces | Utility ownership requirements; conductor/cable loads; traffic-signal mast arms and visibility; lightning air-terminal support versus LPS design; clearances; permits; third-party assets; handover ownership | Boundary diagrams, authority checklist, current owner/authority requirements, discipline review | Does not replace utility approval, traffic engineering, electrical clearance design, or IEC/SNI lightning-risk assessment | 6 |
| TPG-13 | Electrical, earthing, bonding, and cable interfaces | Coordinate safe electrical pathways without confusing structural steel with a complete protection system | Cable entry and segregation; access doors; IP protection; protective devices; earthing versus bonding; continuity; corrosion at connections; lightning current paths; testing; labeling; as-built records | Single-line/interface diagrams, test-record checklist, current electrical/LPS standards, competent review | No wiring, electrode, conductor, or protection-device design values for a specific installation | 6 |
| TPG-14 | Logistics, lifting, erection, and K3 | Plan delivery and installation controls before the truck arrives | Segment transport; route/access survey; storage; lifting points and center of gravity; crane/rigging plan; exclusion zones; wind limits from approved plan; work at height; temporary stability; bolting; alignment; rescue; weather stop rules | Lift-plan input sheet, sequence diagram, K3 checklist, competent lifting/work-at-height review | Does not provide a generic lifting plan, rigging capacity, wind limit, or safe-work authorization | 6 |
| TPG-15 | Inspection, maintenance, and intervention | Build a condition-based program and recognize escalation triggers | Baseline data; inspection intervals by risk; corrosion, cracks, looseness, deformation, settlement, vibration, water ingress; NDT escalation; repair engineering; coating repair; strengthening limits; decommissioning | Inspection forms, defect atlas, severity/escalation matrix, trend log, specialist review | Photos and checklists do not determine structural safety; repair/reuse decisions require competent assessment | 6 |
| TPG-16 | Procurement, QA, and handover | Compare offers on equivalent scope and receive auditable assets | Employer requirements; drawings/calculations; material certificates; WPS/qualifications; ITP/hold points; coating records; dimensional/NDT reports; delivery/installation scope; exclusions; warranties; O&M; as-builts; lifecycle cost | BOQ scope matrix, submittal register, ITP template, handover dossier index | Does not endorse a supplier, fabricate credentials, or convert missing evidence into assumed compliance | 6 |

## Related-domain opportunities

| Domain | Independent viewpoint | Legitimate collaboration |
|---|---|---|
| `pabrikasi.id` | General fabrication process and supplier capability | Link to deep fabrication methods while this domain applies them to poles |
| `tiang.lampu.co.id` and `lampu.co.id` | Lighting products and lighting-specific selection | Exchange photometry and luminaire evidence; keep this domain focused on pole/system interfaces |
| `besi.co.id` | Steel materials and supply | Reference material grades, traceability, and availability evidence |
| `bengkel-las.co.id` | Welding services and craft/process detail | Reference welding qualifications and inspection explainers |
| `cutting.co.id` | Cutting processes | Reference process capability and edge-quality topics |
| `safety.co.id` | General K3 equipment and practice | Reference PPE/work-at-height fundamentals; retain pole-specific lifting sequence here |

Cross-domain similarity is not same-domain cannibalization. Each domain may publish its own useful perspective, with transparent attribution and no near-duplicate copy.

## Consolidation plan

1. Export GSC URL/query data, analytics, backlinks, conversions, and index status before changing any geographic page.
2. Cluster the geographic pages by type, canonical, content similarity, impressions, leads, links, and genuine local proof. Preserve pages with distinct, substantiated service information; do not infer value from a city name alone.
3. Select one canonical commercial owner for each product/service intent. Merge useful unique evidence into that owner and use redirects, canonicalization, or noindex only after URL-level review.
4. Separate neutral guides from transactional routes by title, CTA, schema, and internal-link role.
5. Consolidate sitemap artifacts into one generated source of truth; include only canonical, indexable 200-status URLs and maintain truthful `lastmod`.
6. Review archives and author pages for crawl value, then prevent thin pagination from becoming an accidental competing result.
7. Inventory unsupported claims, stock imagery, copied specifications, and external-script dependencies before the first editorial wave.

## Internal-link architecture

- `/` links to the principal commercial product routes and a future neutral “panduan sistem tiang” hub (TPG-01-01).
- The hub links by task: define (TPG-02), engineer (TPG-03/08/13), make/protect (TPG-04–07), apply (TPG-09–12), deliver (TPG-14), maintain (TPG-15), and procure (TPG-16).
- Each article links to one parent hub, two to four contextually necessary sibling/adjacent articles, and at most one relevant commercial route after the reader has enough information to qualify the need.
- Application articles link backward to the required structural, foundation, electrical, and K3 evidence rather than repeating those explanations.
- Diagnostic pages link to escalation and maintenance owners, not directly to a sales claim that implies a remote safety verdict.
- Breadcrumbs, HTML hubs, and sitemap inclusion must agree. Important guides should be reachable within three meaningful clicks.
- Anchor text describes the destination task; repeated exact-match keyword blocks and sitewide commercial footers are not an editorial link strategy.

## Evidence and editorial standards

- Use current primary Indonesian sources first: applicable SNI/BSN publications, ministries/JDIH, utility or road authority requirements, and project specifications. Use IEC/ISO/AWS or manufacturer documents only where relevant and clearly scoped.
- Cite the exact edition/date and verify current applicability at publication. Never invent clause numbers, loads, dimensions, coating life, wind limits, prices, warranties, or test outcomes.
- High-stakes structural, fabrication, welding, coating, foundation, lifting, electrical, lightning, and K3 content must carry named competent review and a “project-specific design required” boundary.
- Calculations use labeled illustrative inputs and units, show assumptions and method, and cannot be copied as a project answer.
- Original photos identify project, date, permission, component, and what the photo can or cannot prove. Case studies require real records; otherwise publish a checklist or hypothetical method, not a fabricated success story.
- Commercial claims need traceable certificates, drawings, test records, invoices, or project acceptance evidence. “Complies with standard” is not acceptable without scope and document proof.
- Every brief has one primary intent, a distinct promise, and an explicit exclusion. Update or consolidate when Search Console shows two pages answering the same query job.

## First bounded publication cluster

Wave 1 contains 12 assets: TPG-01-01, TPG-01-02, TPG-02-01, TPG-02-02, TPG-03-01, TPG-03-03, TPG-04-01, TPG-05-01, TPG-07-01, TPG-08-01, TPG-14-01, and TPG-16-01. Together they form one coherent “from need to accepted pole asset” path: choose the system, capture site inputs, understand design evidence, select material/section, inspect fabrication and corrosion controls, coordinate the foundation, plan safe erection, and compare bids.

The TPG-01 hub owns navigation. Each selection article links forward to survey and engineering inputs; delivery and procurement checklists link back to the evidence they require. Monitor canonical indexation, sitemap discovery, impressions grouped by intent, scroll/checklist use, relevant route clicks, qualified quotation inputs, and same-domain query overlap. Ranking alone is not a success criterion.

## Definition of done

- All 16 topics have six distinct, evidence-ready briefs and no geographic substitutions.
- Each published guide satisfies its catalog promise, exclusion, reviewer gate, citations, and related-link plan.
- Transactional product/service routes and neutral informational articles have distinct ownership.
- The sitemap contains only canonical, indexable, 200-status URLs with truthful metadata.
- Geographic pages have a documented URL-level decision backed by GSC, conversion, link, and local-evidence data.
- Route-collision and title/slug uniqueness checks pass before publication.
- Structural, welding, coating, foundation, lifting, electrical, lightning, and K3 claims have current primary evidence and competent review.
- Performance is reviewed by task completion, qualified leads, indexation, impressions by intent, and cannibalization—not article count alone.
