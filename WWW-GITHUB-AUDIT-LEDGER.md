# Spiral Civilization — WWW ↔ GitHub Audit Ledger

**Audit date:** 2026-09-10  
**Repository:** `kassjas/spiral-civilization`  
**Website:** Spiral Civilization WordPress  
**Status:** Audit discovery pass completed; corrections are now being executed through this ledger.

## Purpose

This ledger records the relationship between public website material and GitHub documentation. Balance does **not** mean identical files or identical counts. An asymmetry is acceptable when its purpose is known and documented: source history, genealogy, language version, incorporation into another public document, laboratory material, operational website implementation, or an explicit publication decision.

The audit question is therefore:

> Where does this knowledge appear on the website, what is its GitHub form, and why are the two representations the same or different?

## Status vocabulary

- **PUBLIC / SYNCED** — public material has corresponding GitHub documentation.
- **GITHUB — SOURCE** — source material from which another public form was developed.
- **GITHUB — GENEALOGY** — developmental version intentionally preserved as project history.
- **GITHUB — INCORPORATED INTO [X]** — standalone source whose knowledge was incorporated into another public document.
- **GITHUB — LAB / DEVELOPMENT** — experimental or development material.
- **GITHUB — PUBLIC CANDIDATE** — substantive material whose publication status still requires a decision.
- **WWW — OPERATIONAL** — website implementation element that does not require a copy of generated markup in GitHub.
- **WWW → GITHUB MISSING** — substantive public material lacks corresponding GitHub documentation.
- **LOCATION / ARCHITECTURE GAP** — content exists on both sides but is not stored in the intended GitHub structure.
- **RECONCILE** — two related versions contain meaningful differences that need review.
- **TECHNICAL CLEANUP** — duplicate, empty placeholder, stock content, malformed text, date/permalink or similar implementation issue.
- **TO RESOLVE / DECIDE** — relationship or publication decision is not yet settled.

## Audit Ledger

| Area / Material | GitHub state | WWW state | Audit status | Reason / relationship | Next action |
|---|---|---|---|---|---|
| Welcome | `www/01-Welcome` | Home / Welcome | **PUBLIC / SYNCED** | Folder models the content units of the public Welcome area. | NONE |
| `Witam pl.md` | Root PL source | English Welcome public | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish counterpart/source of public English Welcome. | DOCUMENT relationship |
| `O Projekcie pl.md` | Root PL source | About the Project in Welcome | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish source/counterpart of English public text. | DOCUMENT relationship |
| Stage 21 Manifesto EN | `www/01-Welcome` | Public Welcome content | **PUBLIC / SYNCED** | Public English manifesto represented in GitHub. | NONE |
| Stage 21 Manifesto PL | Root | EN public | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish source/counterpart. Two root filenames currently have identical SHA/content. | DOCUMENT + later remove/resolve exact duplicate |
| Expedition Zero EN | `www/01-Welcome` | Welcome | **PUBLIC / SYNCED** | Threshold/genealogical text intentionally located in Welcome. | NONE |
| `Ekspedycja Zero pl 2026.08.03.md` | Root | Expedition Zero EN public | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish source/counterpart. | DOCUMENT relationship |
| Expedition One | `www/03-Expeditions` | Expeditions | **PUBLIC / SYNCED** | Main public Expedition One matches GitHub content. | NONE |
| `Ekspedycja Pierwsza pl 2026.08.03.md` | Root, short | Full EN Expedition One public | **GITHUB — SOURCE / INTRODUCTORY VERSION** | Short Polish introductory text, not a full translation of current EN Expedition One. | DOCUMENT relationship |
| Questions / Explore Questions | `www/07-Questions` | Explore Questions | **PUBLIC / SYNCED** | Public open question catalogue represented in GitHub. | NONE |
| `Aneks.md` — 21 Fundamental Questions | Root | No equivalent full public document identified | **GITHUB — SOURCE / RESEARCH ARCHITECTURE — TO DECIDE PLACEMENT** | Separate architecture: 21 fundamental questions arranged as seven levels of three; not the same document as Explore Questions. | DECIDE future placement; do not copy automatically |
| Foundations — Emerging Spiral | `www/02-Foundations` | Foundations | **PUBLIC / SYNCED** | Main foundation text represented on both sides. | NONE |
| `Nullynity-Foundation.md` | `www/02-Foundations` | Foundations contains intended `[Nullynity]` insertion/link point but not full text | **PUBLIC SOURCE / WWW REPRESENTATION INCOMPLETE** | Public-facing Nullynity foundation is intended to be linked/published from Foundations. | LINK / publish public representation after audit |
| `Nullynity-Protocol-v0.1.md` (content identifies itself as v0.2) | `www/02-Foundations`, already historically public | No full WWW publication required | **PUBLIC RESEARCH PROTOCOL / HISTORICAL DEVELOPMENT DOCUMENT** | Kass decided 2026-09-10 on the split model: Foundation = public conceptual layer; current already-disclosed Protocol remains a public research/development record; future implementation-sensitive material must be separated into a private Development Specification from inception. Ordinary deletion would not erase Git history. Filename/version mismatch remains to resolve. | KEEP; later reconcile filename v0.1 vs content v0.2; create future private Development Specification outside public repo |
| Project Cooperation | `www/04-Project Cooperation` | Project Cooperation | **PUBLIC / SYNCED — DEVELOPED VERSION** | Public developed architecture represented in `www/04`. | NONE |
| `Project-Cooperation.md` | Root | Later developed Project Cooperation public | **GITHUB — SOURCE / EARLIER VERSION** | Earlier/source form of the later public architecture. | DOCUMENT genealogy |
| Cooperation Network | `www/05-Cooperation Network` | Cooperation Network | **PUBLIC VERSION — RECONCILE** | Public/GitHub `www/05` version exists but contains malformed/truncated ending. | RECONCILE + FIX WWW/GitHub |
| `Cooperation-Network.md` | Root, richer | Public Network lacks some later/alternative material | **GITHUB — SOURCE / DEVELOPED OR ALTERNATIVE VERSION — RECONCILE** | Contains meaningful additional material, including participation without agreement and criticism/alternative hypotheses as research. | Compare and decide canonical additions |
| Nobility Prize | `www/06-Nobility Prize` | Nobility Prize | **PUBLIC / SYNCED — EARLY STUB** | Same intentionally minimal public statement. | NONE |
| Encyclopedia — 19 current entries | `www/08-Encyclopedia` | Encyclopedia + 19 child pages | **PUBLIC / SYNCED** | Current public entries have standalone GitHub representation. | NONE |
| `Project Cockpit.md` | `www/08-Encyclopedia` | Project Cockpit post exists | **PUBLIC CONCEPT / GENEALOGICAL ARCHITECTURE** | Substantial existing Cockpit architecture; future Cockpit environment must build from it rather than overwrite its genealogy. | Preserve; later map into Cockpit architecture |
| SoulSmugglers Stories 01–04 | `www/09-SoulSmugglers-Stories` | Public SSS posts | **PUBLIC / SYNCED** | Current series represented on both sides. | NONE |
| SSS 04 vs Conversation 04 | Separate transformed SSS and source conversation | Both public | **INTENTIONAL DERIVATION** | SSS 04 is an editorial transformation, not the literal original monologue; Conversation 04 preserves the source/genealogy. | Preserve distinction |
| Conversations 01–03 | `www/10-Conversations-with-Evo-AI` | Public Conversations 01–03 | **PUBLIC / SYNCED WITH SOURCE VARIANTS** | Public final forms exist; additional GitHub variants document development/language/source history. | Add relationship notes where useful |
| Conversation 04 FINAL | `2025-12-12-conversation-04-FINAL-complete-version.md` | Public Conversation 04 | **CANONICAL / PUBLIC SOURCE** | Final merged complete version is the canonical GitHub source for public Conversation 04. | NONE |
| Conversation 04 earlier versions | Multiple earlier files | Final version public | **GITHUB — GENEALOGY / DEVELOPMENT** | Earlier stages deliberately preserve evolution of the conversation. | DOCUMENT genealogy; do not delete as duplicates |
| Conversation 04 empty PL file | 0-byte `...-PL.md` | No content | **TECHNICAL CLEANUP / EMPTY PLACEHOLDER** | Empty file is not a substantive language version. | CLEANUP after ledger review |
| Conversation 04 substantial PL file | GitHub | EN final public | **GITHUB — SOURCE / LANGUAGE VERSION** | Substantive Polish version/source exists separately. | DOCUMENT relationship |
| 2026-09-07 Knowledge and Intelligence Laboratory | Standalone GitHub source | Incorporated into final Conversation 04 | **GITHUB — SOURCE / INCORPORATED INTO CONVERSATION 04** | Architectural Correction and Experimental Dialogue became Parts of final Conversation 04. | Add explicit relation note |
| 2026-09-08 Spoken Wish continuation | Standalone GitHub source | Incorporated into Conversation 02 | **GITHUB — SOURCE / INCORPORATED INTO CONVERSATION 02** | Later source document is intentionally preserved separately while its knowledge appears publicly inside Conversation 02. | Add explicit relation note |
| Spoken Wish Encyclopedia entry | Standalone concept entry | Public Encyclopedia | **PUBLIC / SYNCED — DISTILLED CONCEPT** | Canonical/distilled concept is a different epistemic layer from Conversation 02 genealogy. | Preserve distinction |
| `2026-08-20-the-evolutionary-gate.md` | GitHub only | No separate public post found; preceding Stage 21 Threshold is public | **GITHUB ONLY — SUBSTANTIVE SOURCE / PUBLICATION TO DECIDE** | Important source for birth of Project Cockpit; not equivalent to the earlier public FFID. | DECIDE: genealogy only vs public Conversation |
| `The Geometry of Evolution 2026.08.01.md` | Root GitHub only | No full equivalent identified | **GITHUB ONLY — SUBSTANTIVE SOURCE / PUBLICATION TO DECIDE** | Independent text on complementary evolutionary trajectories. | DECIDE public role/placement |
| Multisymbiotic Systems Tool | Root GitHub source | Public standalone page | **PUBLIC BOTH SIDES / LOCATION-ARCHITECTURE GAP** | Knowledge exists on both sides but GitHub source remains in repository root rather than structured `www`. | ORGANIZE non-destructively after audit |
| Personality Expansion & Identity Games | Root GitHub source | Public standalone page | **PUBLIC BOTH SIDES / LOCATION-ARCHITECTURE GAP** | Knowledge exists on both sides but GitHub source remains in root. | ORGANIZE non-destructively after audit |
| 16 Aug Amusement Park / Identity Games / Toolbar conversation | Root source family | Public page ID227 plus distilled Tool page ID208 | **GITHUB SOURCE → WWW CONVERSATION / GENEALOGY → WWW TOOL** | Public conversation records development; Tool page is a distilled cooperation/instrument layer. | DOCUMENT derivation; avoid treating as duplicate |
| Identity Fields Tool | No corresponding GitHub document found | Substantive public page | **WWW → GITHUB MISSING** | Genuine documentation gap; conceptual/prototype content is not merely operational markup. | CREATE canonical GitHub documentation from public source |
| Privacy Information — Participant Window | No corresponding GitHub document found | Substantive public policy page | **WWW → GITHUB MISSING** | Genuine public documentation gap. | CREATE canonical GitHub documentation from public source |
| Contact / Participant Window form | No generated-form mirror required | Public operational form | **WWW — OPERATIONAL** | Generated Formidable Forms HTML is implementation, not knowledge content to duplicate in GitHub. | Document architecture/version/rules only |
| Library / Resources | `www/11-Resources/Library` | Library | **PUBLIC / SYNCED — EARLY STUB** | Same intentionally minimal public text. | NONE |
| Why I Started Spiral Civilization EN | `www/12-Why I Started...` | Public page | **PUBLIC / SYNCED** | English public text represented in GitHub. | NONE |
| `Dlaczego rozpoczęłam projekt Cywilizacja Spirali.md` | Root PL | EN public | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish counterpart/source with minor translation differences. | DOCUMENT relationship |
| Root `0.0–0.3` outreach files | Root | Public descendants in Expedition/outreach architecture | **GITHUB — SOURCE / OUTREACH GENEALOGY** | Working communication architecture, invitation versions and question development. | Preserve; add genealogy note if reorganized |
| `Timeline.md` | Root | No public copy required | **GITHUB — PROJECT LEDGER / GENEALOGY** | Repository-level historical record, explicitly not full history of ideas. | NONE |
| `README.md` | Root | No public copy required | **GITHUB — REPOSITORY DOCUMENTATION** | Defines repository as public archive and explains preservation of development history. | NONE |
| WP post ID140 `2026.10.08 Spiral Civilization Concepts` | No separate canonical GitHub need identified | Public, published 2026-08-31 | **PROBABLE WWW DUPLICATE / MISDATED DEVELOPMENT COPY** | Content begins identically to ID141; title date conflicts with publication chronology and ID141 states conversation began 10 Aug 2026. | VERIFY full equivalence, then CLEANUP |
| WP post ID141 `2026-08-10 — Spiral Civilization Concepts` | Source relationship to project materials | Public Conversation | **PUBLIC / LIKELY CANONICAL OF ID140 PAIR** | Has explicit genealogy note dating conversation to 10 Aug 2026. | Keep; verify against ID140 |
| WP Sample Page ID2 | None required | Public WordPress stock page | **WWW — STOCK / TECHNICAL CLEANUP** | Default WordPress content, not Spiral Civilization knowledge. | Remove/unpublish after approval |

## Confirmed technical issues

1. **Cooperation Network truncated text** — public/GitHub version ends with `The network itself can therefore become a research instrume` and requires repair on both sides.
2. **Duplicate Polish Stage 21 files** — two root filenames have the same blob SHA and content; true technical duplicate, not genealogy.
3. **Conversation 04 empty PL placeholder** — 0-byte file; not a substantive version.
4. **WP ID140** — probable duplicate/misdated copy of ID141; full equivalence must be verified before cleanup.
5. **WP Sample Page ID2** — stock WordPress page.
6. **Nullynity Protocol filename/version mismatch** — filename says v0.1 while document content identifies itself as v0.2. Public/private architecture has been resolved: current already-public Protocol remains public research history; future implementation-sensitive Development Specification starts private and stays outside the public repository.

## Confirmed substantive gaps

### WWW → GitHub

1. **Identity Fields Tool** — canonical GitHub documentation missing.
2. **Privacy Information — Participant Window** — canonical GitHub documentation missing.

### GitHub → WWW incomplete / undecided

1. **Nullynity Foundation** — public source exists; intended website link/insertion point exists but full public representation is incomplete.
2. **The Evolutionary Gate** — substantive source; publication/genealogy decision required.
3. **The Geometry of Evolution** — substantive source; public role/placement decision required.
4. **Aneks — 21 Fundamental Questions** — research architecture exists; future placement must be decided rather than copied automatically.

## Structural issues to resolve after content balance

- Multisymbiotic Systems Tool and Personality Expansion & Identity Games should eventually be represented in an intentional `www`/Cockpit structure rather than only at repository root.
- Identity Fields Tool should join that instrument architecture once its canonical GitHub document is created.
- Project Cockpit already has an important conceptual/genealogical document in Encyclopedia. A future `www/13-Cockpit` must therefore be an operational/navigation environment, not a replacement for that document.
- Questions may later become structurally subordinate to Expeditions on the website, while remaining a full page. This is a navigation decision, not an audit correction.

## Nullynity public/private architecture — decision 2026-09-10

Three layers are now distinguished:

1. **Nullynity Foundation — PUBLIC FOUNDATION**  
   Public conceptual layer: what Nullynity is, why it exists, its role in Spiral Civilization and Project Cockpit.

2. **Nullynity Protocol — PUBLIC RESEARCH PROTOCOL**  
   The present Protocol has already existed in the public repository and remains part of the transparent research/development history. It may describe the research process and experimental architecture sufficiently for the project to remain inspectable and challengeable.

3. **Nullynity Development Specification — PRIVATE DEVELOPMENT LAYER**  
   Future implementation-sensitive material — detailed implementation procedures, internal prompts/configurations, evaluation parameters/algorithms, experimental operational details, or other material Kass deliberately chooses not to publish — must be created and maintained outside the public repository from inception. It must not be treated as private merely by adding an `internal` label to a public file.

**Boundary rule:** Public Foundation explains the concept. Public Protocol exposes the research method. Private Development Specification contains implementation-sensitive construction details.

## Action codes

- **NONE** — relationship is healthy and documented.
- **DOCUMENT** — add provenance/genealogy/status note only.
- **CREATE** — create missing canonical documentation.
- **LINK** — connect existing public source to intended website location.
- **RECONCILE** — compare meaningful variants and decide canonical public content.
- **ORGANIZE** — improve repository placement without destroying genealogy.
- **DECIDE** — Kass decides public/architectural role before implementation.
- **PROTECT** — keep future implementation-sensitive material outside the public repository from inception.
- **CLEANUP** — remove/repair technical residue only after verification/approval.

## Execution order — current

1. **DONE — architecture decision:** Nullynity public/private split established; current Protocol remains public research history; future Development Specification is private from inception.
2. Create GitHub documentation for Identity Fields Tool and Privacy Information.
3. Complete the public Nullynity Foundation representation/link.
4. Reconcile and repair Cooperation Network.
5. Verify ID140 vs ID141; resolve stock/empty/exact-duplicate technical residue.
6. Add provenance/status notes to intentional GitHub-only source and genealogy documents.
7. Decide publication/placement for The Evolutionary Gate, The Geometry of Evolution and Aneks — 21 Fundamental Questions.
8. Organize the tool family without destructive moves.
9. Only then change website navigation and construct the operational Cockpit / future `www/13-Cockpit`.

---

**Audit principle:** Preserve genealogy. Repair accidental asymmetry. Document intentional asymmetry. Do not confuse a public derivative with its source, and do not confuse a development record with a missing publication.
