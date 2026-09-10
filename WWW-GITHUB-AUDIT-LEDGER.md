# Spiral Civilization — WWW ↔ GitHub Audit Ledger

**Audit date:** 2026-09-10  
**Repository:** `kassjas/spiral-civilization`  
**Website:** Spiral Civilization WordPress  
**Status:** Major synchronization and cleanup pass completed; remaining unresolved items are explicitly identified below.

## Purpose

This ledger records the relationship between public website material and GitHub documentation. Balance does **not** mean identical files or identical counts. An asymmetry is acceptable when its purpose is known and documented: source history, genealogy, language version, incorporation into another public document, laboratory material, operational website implementation, or an explicit publication decision.

The audit question is:

> Where does this knowledge appear on the website, what is its GitHub form, and why are the two representations the same or different?

## Status vocabulary

- **PUBLIC / SYNCED** — public material has corresponding GitHub documentation.
- **GITHUB — SOURCE** — source material from which another public form was developed.
- **GITHUB — GENEALOGY** — developmental version intentionally preserved as project history.
- **GITHUB — INCORPORATED INTO [X]** — standalone source whose knowledge was incorporated into another public document.
- **GITHUB — LAB / DEVELOPMENT** — experimental or development material.
- **GITHUB — PUBLIC CANDIDATE** — substantive material whose publication status still requires a decision.
- **WWW — OPERATIONAL** — website implementation element that does not require a copy of generated markup in GitHub.
- **TO RESOLVE — SOURCE CHAT REQUIRED** — status cannot responsibly be reconstructed from current repository material alone.
- **TECHNICAL CLEANUP** — duplicate, empty placeholder, stock content, malformed text, date/permalink or similar implementation issue.

## Audit Ledger

| Area / Material | GitHub state | WWW state | Audit status | Reason / relationship | Next action |
|---|---|---|---|---|---|
| Welcome | `www/01-Welcome` | Home / Welcome | **PUBLIC / SYNCED** | Folder models the content units of the public Welcome area. | NONE |
| `Witam pl.md` | Root PL source | English Welcome public | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish counterpart/source of public English Welcome. | NONE |
| `O Projekcie pl.md` | Root PL source | About the Project in Welcome | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish source/counterpart of English public text. | NONE |
| Stage 21 Manifesto EN | `www/01-Welcome` | Public Welcome content | **PUBLIC / SYNCED** | Public English manifesto represented in GitHub. | NONE |
| Stage 21 Manifesto PL | `2026.01.11 Cywilizacja Spirali — Etap 21 pl.md` | EN public | **GITHUB — SOURCE / LANGUAGE VERSION** | Canonical Polish source retained; exact duplicate root file deleted after verification. | NONE |
| Expedition Zero EN | `www/01-Welcome` | Welcome | **PUBLIC / SYNCED** | Threshold/genealogical text intentionally located in Welcome. | NONE |
| `Ekspedycja Zero pl 2026.08.03.md` | Root | Expedition Zero EN public | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish source/counterpart. | NONE |
| Expedition One | `www/03-Expeditions` | Expeditions | **PUBLIC / SYNCED** | Main public Expedition One matches GitHub content. | NONE |
| `Ekspedycja Pierwsza pl 2026.08.03.md` | Root, short | Full EN Expedition One public | **GITHUB — SOURCE / INTRODUCTORY VERSION** | Short Polish introductory text, not a full translation of current EN Expedition One. | NONE |
| Questions / Explore Questions | `www/07-Questions` | Explore Questions | **PUBLIC / SYNCED** | Open question laboratory represented in GitHub and on WWW. | NONE |
| `Aneks.md` — 21 Fundamental Questions | Root PL source + `www/07-Questions/21 Fundamental Questions.md` | Public child page of Explore Questions; linked also from Conversations with Evo AI | **PUBLIC / SYNCED — QUESTIONS + CONVERSATIONS LINKED / ROOT SOURCE PRESERVED** | Origin is Kass asking Evo AI for fundamental questions in the broad context of philosophy/science; one canonical public document avoids duplication while preserving dialogic provenance. | NONE |
| Foundations — Emerging Spiral | `www/02-Foundations` | Foundations | **PUBLIC / SYNCED** | Main foundation text represented on both sides. | NONE |
| `Nullynity-Foundation.md` | `www/02-Foundations` | Public Nullynity page ID393 linked from Foundations | **PUBLIC / SYNCED** | Full public conceptual Foundation representation is now live and linked. | NONE |
| `Nullynity-Protocol-v0.1.md` (content identifies itself as v0.2) | `www/02-Foundations` | Publication/version intention cannot be safely reconstructed from current material | **TO RESOLVE — SOURCE CHAT REQUIRED** | Filename/content version mismatch and original intended status require the source conversation. No source chat was recovered in current search. | DEFER until source chat/data export; do not rename/delete/reclassify |
| Project Cooperation | `www/04-Project Cooperation` | Project Cooperation | **PUBLIC / SYNCED — DEVELOPED VERSION** | Public developed architecture represented in `www/04`. | NONE |
| `Project-Cooperation.md` | Root | Later developed Project Cooperation public | **GITHUB — SOURCE / EARLIER VERSION** | Earlier/source form of later public architecture. | NONE |
| Cooperation Network | `www/05-Cooperation Network` | Cooperation Network | **PUBLIC / SYNCED** | Developed canonical content reconciled on WWW and in `www/05`; malformed/truncated version repaired. | NONE |
| `Cooperation-Network.md` | Root | Developed content represented publicly | **GITHUB — SOURCE / GENEALOGY** | Root developed/source version preserved after reconciliation. | NONE |
| Nobility Prize | `www/06-Nobility Prize` | Nobility Prize | **PUBLIC / SYNCED — EARLY STUB** | Same intentionally minimal public statement. | NONE |
| Encyclopedia — 20 entries | `www/08-Encyclopedia` | Encyclopedia + child pages | **PUBLIC / SYNCED** | Includes the added Three Spirals entry. | VERIFY alphabetical index contains newest entry |
| `Project Cockpit.md` | `www/08-Encyclopedia` | Project Cockpit post | **PUBLIC CONCEPT / GENEALOGICAL ARCHITECTURE** | Existing conceptual Cockpit architecture must remain distinct from future operational Cockpit environment. | Preserve; later map into Cockpit architecture |
| Three Spirals — The Geometry of Evolution | `www/08-Encyclopedia/Three Spirals — The Geometry of Evolution.md` + root source | Public Encyclopedia page ID398 | **PUBLIC / SYNCED — ENCYCLOPEDIA ENTRY** | Root `The Geometry of Evolution 2026.08.01.md` remains SOURCE / GENEALOGY; third internal trajectory intentionally remains `The Trajectory of Conscious Participation`. | NONE |
| SoulSmugglers Stories 01–04 | `www/09-SoulSmugglers-Stories` | Public SSS posts | **PUBLIC / SYNCED** | Current series represented on both sides. | NONE |
| SSS 04 vs Conversation 04 | Separate transformed SSS and source conversation | Both public | **INTENTIONAL DERIVATION** | SSS 04 is an editorial transformation; Conversation 04 preserves source/genealogy. | NONE |
| Conversations 01–03 | `www/10-Conversations-with-Evo-AI` | Public Conversations 01–03 | **PUBLIC / SYNCED WITH SOURCE VARIANTS** | Public final forms exist; additional GitHub variants preserve development/language/source history. | Later repair legacy backlinks/verification notes |
| Conversation 04 FINAL | `2025-12-12-conversation-04-FINAL-complete-version.md` | Public Conversation 04 | **CANONICAL / PUBLIC SOURCE** | Final merged complete version is canonical GitHub source. | NONE |
| Conversation 04 earlier versions | Multiple earlier files | Final version public | **GITHUB — GENEALOGY / DEVELOPMENT** | Earlier stages deliberately preserve evolution. | NONE |
| Conversation 04 empty PL placeholder | Deleted | None | **RESOLVED — TECHNICAL CLEANUP** | Verified 0-byte placeholder; deleted while substantive PL version remains. | NONE |
| Conversation 04 substantial PL file | GitHub | EN final public | **GITHUB — SOURCE / LANGUAGE VERSION** | Substantive Polish version/source remains separately. | NONE |
| 2026-09-07 Knowledge and Intelligence Laboratory | Standalone GitHub source | Incorporated into final Conversation 04 | **GITHUB — SOURCE / INCORPORATED INTO CONVERSATION 04** | Architectural Correction and Experimental Dialogue became parts of final Conversation 04. | NONE |
| 2026-09-08 Spoken Wish continuation | Standalone GitHub source | Incorporated into Conversation 02 | **GITHUB — SOURCE / INCORPORATED INTO CONVERSATION 02** | Later source intentionally preserved while its knowledge appears publicly inside Conversation 02. | NONE |
| Spoken Wish Encyclopedia entry | Standalone concept entry | Public Encyclopedia | **PUBLIC / SYNCED — DISTILLED CONCEPT** | Distilled concept is a different epistemic layer from Conversation 02 genealogy. | NONE |
| The Evolutionary Gate | `www/10-Conversations-with-Evo-AI/2026-08-20-the-evolutionary-gate.md` | Public Conversation post ID399 | **PUBLIC / SYNCED — CONVERSATION + BIDIRECTIONAL GENEALOGY LINKS** | Public genealogy now connects Stage 21 — Threshold → The Evolutionary Gate ↔ Project Cockpit. | Verify Conversations catalogue/excerpt |
| Multisymbiotic Systems Tool | Root Prototype v0.1 + `www/04-Project Cooperation/Multisymbiotic Systems Tool.md` | Public developed standalone page | **PUBLIC / SYNCED — DEVELOPED PUBLIC VERSION / ROOT SOURCE PRESERVED** | WWW is more developed than root Prototype v0.1; `www/04` records current canonical placement and relationship without overwriting genealogy. | Later export clean developed public prose to Markdown if useful |
| Personality Expansion & Identity Games | Root source + `www/04-Project Cooperation/Personality Expansion & Identity Games.md` | Public standalone page | **PUBLIC / SYNCED / ROOT SOURCE PRESERVED** | Canonical `www/04` placement recorded; generated form markup intentionally excluded. | NONE |
| 16 Aug Amusement Park / Identity Games / Toolbar conversation | Root source family | Public page ID227 + distilled Tool page ID208 | **GITHUB SOURCE → WWW CONVERSATION / GENEALOGY → WWW TOOL** | Conversation records development; Tool page is distilled cooperation/instrument layer. | NONE |
| Identity Fields Tool | `www/04-Project Cooperation/Identity Fields Tool.md` | Public page ID221 | **PUBLIC / SYNCED** | Missing canonical GitHub documentation created from public conceptual layer; generated form markup excluded. | NONE |
| Privacy Information — Participant Window | `www/04-Project Cooperation/Privacy Information — Participant Window.md` | Public page ID169 | **PUBLIC / SYNCED** | Public policy now has canonical GitHub documentation. | NONE |
| Contact / Participant Window form | No generated-form mirror required | Public operational form | **WWW — OPERATIONAL** | Formidable-generated markup is implementation, not knowledge content to duplicate. | Document architecture/version/rules only as needed |
| Library / Resources | `www/11-Resources/Library` | Library | **PUBLIC / SYNCED — EARLY STUB** | Same intentionally minimal public text. | NONE |
| Why I Started Spiral Civilization EN | `www/12-Why I Started...` | Public page | **PUBLIC / SYNCED** | English public text represented in GitHub. | NONE |
| `Dlaczego rozpoczęłam projekt Cywilizacja Spirali.md` | Root PL | EN public | **GITHUB — SOURCE / LANGUAGE VERSION** | Polish counterpart/source with minor translation differences. | NONE |
| Root `0.0–0.3` outreach files | Root | Public descendants in Expedition/outreach architecture | **GITHUB — SOURCE / OUTREACH GENEALOGY** | Working communication architecture, invitation versions and question development. | Preserve |
| `Timeline.md` | Root | No public copy required | **GITHUB — PROJECT LEDGER / GENEALOGY** | Repository-level historical record. | NONE |
| `README.md` | Root | No public copy required | **GITHUB — REPOSITORY DOCUMENTATION** | Defines repository as public archive and preservation context. | NONE |
| WP post ID140 `2026.10.08 Spiral Civilization Concepts` | No separate canonical GitHub need | Trashed | **RESOLVED — WWW DUPLICATE / DEVELOPMENT COPY** | ID141 retained as canonical developed Conversation. | NONE |
| WP post ID141 `2026-08-10 — Spiral Civilization Concepts` | Source relationship to project materials | Public Conversation | **PUBLIC / CANONICAL OF ID140 PAIR** | Explicit genealogy dates conversation to 10 Aug 2026. | NONE |
| WP Sample Page ID2 | None required | Trashed | **RESOLVED — STOCK WORDPRESS CONTENT** | Default WordPress content removed from public site. | NONE |

## Resolved technical issues

1. **Cooperation Network truncation** — repaired and canonical developed version synchronized.
2. **Duplicate Polish Stage 21 file** — exact duplicate deleted; canonical PL source preserved.
3. **Conversation 04 empty PL placeholder** — verified empty and deleted; substantive PL source preserved.
4. **WP ID140** — duplicate/development copy resolved by trashing ID140; ID141 retained.
5. **WP Sample Page ID2** — stock WordPress page trashed.
6. **Identity Fields Tool documentation gap** — closed.
7. **Privacy Information documentation gap** — closed.
8. **Nullynity Foundation WWW gap** — closed.
9. **The Geometry of Evolution publication decision** — closed as `Three Spirals — The Geometry of Evolution` Encyclopedia entry.
10. **The Evolutionary Gate publication decision** — closed as a Conversation with bidirectional genealogy links.
11. **21 Fundamental Questions placement** — closed as canonical Questions subpage linked also from Conversations with Evo AI; root PL source preserved.
12. **Multisymbiotic Systems Tool and Personality Expansion location gaps** — canonical `www/04-Project Cooperation` representations created without destructive root moves.

## Explicitly deferred / unresolved

### Nullynity Protocol

The only substantive status/version issue deliberately deferred in this pass is `Nullynity-Protocol-v0.1.md`, whose content identifies itself as v0.2. The original source conversation is required to determine intended version/status and publication boundary. Until that source is recovered:

- do not rename the file;
- do not delete it;
- do not declare the current text definitively public, private, canonical or superseded;
- preserve it as-is in GitHub;
- resume the decision after source-chat/data-export recovery.

## Remaining audit/technical checks

These are not known major content-balance gaps; they are verification and maintenance tasks:

1. Verify the Encyclopedia index page includes **Three Spirals — The Geometry of Evolution** alphabetically.
2. Verify the Conversations catalogue includes **The Evolutionary Gate** and add/adjust a curated excerpt if needed.
3. Repair legacy Conversation 01–04 backlinks that still target removed manual catalogue anchors.
4. Repair SSS backlinks that still target removed manual anchors.
5. Normalize Conversation 01–03 verification/source-context notes toward the shared Source Context where appropriate.
6. Audit the large embedded Genesis section on the SSS catalogue against standalone Genesis post ID128 before any removal decision.
7. Run a functional website search-results test.
8. If useful, export the current developed Multisymbiotic Systems Tool public prose into a clean full Markdown canonical document; do not replace the root Prototype v0.1.
9. Continue adding explicit provenance/status notes to significant intentional root/source/genealogy documents when encountered.

## Structural work intentionally postponed until audit completion

- Do **not** change the main website menu yet.
- Do **not** create `www/13-Cockpit` yet.
- Do **not** construct the operational Cockpit yet.
- Preserve `Project Cockpit.md` as conceptual/genealogical architecture.

Only after the remaining verification checks are complete should navigation and the operational Cockpit architecture begin.

## Action codes

- **NONE** — relationship is healthy and documented.
- **DOCUMENT** — add provenance/genealogy/status note only.
- **CREATE** — create missing canonical documentation.
- **LINK** — connect existing public source to intended website location.
- **RECONCILE** — compare meaningful variants and decide canonical public content.
- **ORGANIZE** — improve repository placement without destroying genealogy.
- **DECIDE** — Kass decides public/architectural role before implementation.
- **PROTECT** — keep deliberately private implementation-sensitive material outside a public repository.
- **CLEANUP** — remove/repair technical residue only after verification/approval.
- **DEFER** — preserve unresolved material unchanged until required source evidence is available.

---

**Audit principle:** Preserve genealogy. Repair accidental asymmetry. Document intentional asymmetry. Do not confuse a public derivative with its source, and do not confuse a development record with a missing publication.