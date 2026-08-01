# CHANGELOG, Sovereign Leadership Architecture

**Repository:** github.com/baz-stack/sovereign-leadership-architecture
**Owner:** Baz Porter LLC® · The Prestige Architect®

---

## v2026.08.01.1, Close Loops + Rename + Research Pull

**Date:** August 1, 2026
**Scope:** Reconcile-only follow-up before the next build. Nothing deleted.

1. **Rename** — "RAMS Business Accelerator" / "RAMS Accelerator" → **RAMS Business Profit Accelerator™** across public + private files (the old strings existed only in the private draft; the public live-stack "Business Profit Accelerator" is aligned to the same canonical name, carrying ™). Tagline set where the container is described: *"Your Clients On Your Terms. Fast!"* Added the mark to `canon/IP-REGISTRY.md`, `canon/OFFERS.md`, `glossary/`, and the `baz-porter.txt` trademark list. Private draft file renamed `rams-accelerator.md → rams-business-profit-accelerator.md` (git mv). `_holding/` archive left frozen.
2. **Source mapping** — private index (`institution/README.md`) now names each curriculum draft; the course source resolves under its new name "Course Thesis — RAMS Business Profit Accelerator™" (original Drive title preserved for traceability).
3. **CODEOWNERS** — verified `@baz-stack` is a valid GitHub user (id 270181308) with admin access; a valid CODEOWNERS target. Comment updated to confirm.
4. **Sealed-canon "transformation"** — the two non-tagline descriptor uses aligned to "return": `METHODOLOGY.md` heading "The Transformation Arc" → "The Return Arc"; `FRAMEWORKS.md` "internal transformation evidence" → "internal return evidence". The registered tagline "Not transformation. Return.™" left untouched everywhere.
5. **Live link spot-check** — could not run: the environment's outbound egress policy returns 403 CONNECT for all external hosts (verified in the proxy failure log, incl. the known-live umn.edu). Reported as inconclusive/blocked, not dead. No external links edited.
6. **Research pull (private tier)** — pulled verbatim into `/institution/`: `research/physics-anchor-library.md`, `curriculum-private/paradynamic-healing.md`, `curriculum-private/RAMS-framework.md`. Physics/quantum claims lacking a real citation tagged `[RESEARCH PENDING]`; no sources invented. All three under `/institution/` only — not in sitemap, covered by robots Disallow.

---

## v2026.07.31.2, Canon Restructure + Private Institution

**Date:** July 31, 2026
**Scope:** Restructure the repo into a clean, citable tree; build the missing discovery + trust files; stand up the private institution container. Reconcile-only — nothing deleted.

### Moved (nothing removed)

1. **Canon source files → `/canon/`.** `OFFERS, VOICE, ICA, IP-REGISTRY, MANIFESTO, STORY, PROFILE, CREDIBILITY, BOOKS, METHODOLOGY, CATEGORY, AFFILIATE, DISCOVERY-LAYER, FRAMEWORKS, RETIRED, TRADEMARKS` moved from root into `/canon/` via `git mv` (history preserved). Intra-canon links preserved.
2. **`schema-jsonld.md` → `/identity/`.**
3. **Framework files renamed to canonical names** (via `git mv`, all cross-links fixed): `RAMS-framework.md → rams.md`, `oliver-standard.md → the-oliver-standard.md`, `gravity-code.md → the-gravity-code.md`.

### Built (public tree — gaps only)

4. **`/frameworks/` new definitions:** `silent-collapse-diagnostic.md`, `sovereign-leadership.md`, `sovereign-leadership-architecture.md`.
5. **`/identity/`:** `entity-and-founder.md`, `authority-sources.md` (built from the "Media links" sheet + canon identifiers), plus the moved+enhanced `schema-jsonld.md` (now carries both books/ISBNs, ORCID, USPTO).
6. **`/glossary/glossary-and-terms.md`**, **`/citations/chronological-citation.md`** and **`chronological-index.md`**, **`/faq/faq.md`**.
7. **Root governance + machine:** `robots.txt` (AI crawlers welcomed; `/institution/` disallowed), `sitemap.xml` (public pages only), `CODEOWNERS`, `GOVERNANCE.md`, `LICENSE.md`, `FOOTER.md`. `README.md` rewritten for the new tree.

### Machine layer reconciled

8. **ISBNs + USPTO propagated.** Both ISBNs added to `baz-porter.txt` and `llms.txt`; USPTO Reg. No. 7,125,540 added to `llms.txt`; `schema-jsonld.md` gained two `Book` nodes + ORCID/USPTO identifiers. Fixed a `Code™™` double-mark typo in `baz-porter.txt`.
9. **`CITATION.cff`** expanded with both books (ISBNs) and the USPTO identifier.

### Private tier stood up (walled off)

10. **`/institution/`** created — `README.md`, `VISION.md` (trainer-of-trainers standard; no physics claim asserted as fact), `curriculum-private/` (the 6 RAMS drafts pulled verbatim from the Drive "IP & Frameworks" folder), `research/RESEARCH-PLAN.md` (scoped, not run; every claim `[RESEARCH PENDING]`). Never in sitemap, disallowed in robots, zero public links.

---

## v2026.07.31.1, Canon Finish + Go-Live

**Date:** July 31, 2026
**Scope:** Public-safe cleanup, machine-layer consolidation, and go-live of the AI-discoverability layer

### Removed

1. **Private/future-state tier purged.** The unnamed seven-figure "endgame" tier that had leaked into public `FRAMEWORKS.md` is removed. Public canon now shows the eleven-tier live stack only.

### Machine layer

2. **Consolidated to one source of truth.** Canonical machine anchor is `llms.txt` (publishes at bazporter.com/llms.txt); canonical AI reference is `baz-porter.txt` (publishes at bazporter.com/baz-porter-txt). Every self-canonical pointer resolves to bazporter.com/llms.txt. Superseded duplicates (`public/llms-txt-v3.1.md`, `public/baz-porter-txt-v1.1.md`, and the interim `baz-porter-txt.md`) archived to `_holding/`.
3. **Manifesto wired as the human anchor.** `llms.txt`, `baz-porter.txt`, and `schema-jsonld.md` name bazporter.com/manifesto as the human/category anchor and bazporter.com/llms.txt as the machine anchor. AI is pointed at the live site, not the repo.
4. **ORCID + schema live.** `schema-jsonld.md` and `CITATION.cff` carry ORCID 0009-0006-1670-9956.

### Marks + citations

5. **Marks completed.** The ™ applied to The Reclamation Code™ and Revenue Architecture System (RAS™) across the repo.
6. **Third-party authority.** University of Minnesota CCAPS citation added to `CREDIBILITY.md` and the machine layer; media and podcast citations recorded in `CREDIBILITY.md`.
7. **Books tied to ORCID.** `BOOKS.md` links both titles (with ISBNs) to ORCID 0009-0006-1670-9956.

### Housekeeping

8. **README repaired.** Architecture-overview list corrected; machine-layer files indexed.

---

## v2026.06.06.2, Full Repository Canon Alignment

**Date:** June 6, 2026
**Scope:** Comprehensive canon reset across all root files and framework files

### Major Decisions Locked

1. **RAMS™ pillar order, manifesto canon wins**, Results · Attitude · Authenticity · Mastery · Systems (Attitude in position 2, Authenticity in position 3). Matches bazporter.com/manifesto.
2. **Silent Collapse Diagnostic™ live duration**, 60 minutes, conducted personally by Baz. Replaces all prior durations.
3. **Coming Home™ locked as the canonical methodology name**, canonical methodology name across all external and internal output. Tier names: Find Yourself · Repair · Your Relationship.
5. **Service length**, 6.5 years British Army (1997 to 2004), locked canon-wide.
6. **The Becoming™** confirmed at Gold ($4,620). The Becoming™ formally retired and logged.
8. **Using Trauma to Thrive**, old title logged as retired. Remains on Amazon listings; never promoted.

### Framework Updates

1. The Five Pillars of RAMS™ formalized with weighting (Results 30 / Attitude 15 / Authenticity 20 / Mastery 20 / Systems 15)
2. The Six Integration Layers reclassified, not a pillar, separate framework layer
3. The Sovereign Return Architecture™ formalized as proprietary 6-stage pathway
4. The Sovereign Nervous System Protocol™ formalized
5. The Sovereign AI Charter™ formalized
6. The Oliver Standard™ trademark applied consistently
7. The Becoming™ documented as standalone framework
8. Coming Home™ methodology documented with three tiers

### IP-REGISTRY Expansion

17+ proprietary assets added to the registry:

1. The Sovereign Return Architecture™
2. The Sovereign Nervous System Protocol™
3. The Sovereign Operating System™
4. The Sovereign AI Charter™
5. The Oliver Standard™
6. The Four Worth Distortion Patterns
7. The Dual Audit Architecture
8. The Four-Question Diagnostic Protocol
9. The Three-Stage Pre-Engagement Architecture
10. The Victoria-to-Oliver Bridge
11. The Twelve Core Patterns Architecture
12. The Six Integration Layers
13. The 74 Cosmic Laws
15. Money Mirrors / Old Money New Money
16. Horizon Leaders
17. The Congruence Gate / Congruence Certification Standard

Plus two brand taglines:
18. Power Without Performance. Peace Without Retreat.™
19. Not transformation. Return.™

### Files Touched

**Root files (rewrites):**
1. FRAMEWORKS.md, full rewrite
2. METHODOLOGY.md, full rewrite
3. PROFILE.md, full rewrite
4. CATEGORY.md, patched + cleaned
5. CREDIBILITY.md, patched + cleaned
6. CONTRIBUTING.md, patched
7. OFFERS.md, updated
8. IP-REGISTRY.md, expanded
9. RETIRED.md, expanded
10. README.md, updated
11. CHANGELOG.md, this entry

**Framework files (frameworks/):**
12. RAMS-framework.md, full rewrite (was truncated)
13. coming-home.md, created (renamed from coming-home-to-love.md, rewritten)
14. silent-collapse.md, patched
15. gravity-code.md, patched (Diamond/Quarterly hybrid naming)
16. five-imposters.md, patched
17. the-reclamation-code.md, patched (Tier 3 to $45K, naming, Gold tier added)
18. brand-narrative.md, created (renamed from "The Six Drives of Human Intelligence.md")
19. six-drives.md, patched (Class B mark added, links fixed)
21. the-becoming.md, NEW
22. sovereign-return-architecture.md, NEW
23. sovereign-nervous-system-protocol.md, NEW
24. sovereign-ai-charter.md, NEW
25. oliver-standard.md, NEW

### Directory Cleanup

1. `frameworks/frameworks/` nested folder, DELETED (contents moved to `frameworks/`)
2. `github.com/baz-stack/frameworks/` malformed folder, DELETED (contents moved to `frameworks/`)

### Source-of-Truth Alignment

The full repository now aligns with bazporter.com/manifesto and bazporter.com/baz-porter-txt (llms.txt v4.0). Every downstream skill, page builder, workflow, and content surface resolves against this canon.

---

## v2026.06.06.1, RAMS Pillar Patch (SUPERSEDED)

**Files patched:** IP-REGISTRY.md · CHANGELOG.md · README.md · RETIRED.md

The v2026.06.06.1 patch placed Authenticity in position 2. This has been **superseded** by v2026.06.06.2, which corrects the order to manifesto canon (Attitude in position 2, Authenticity in position 3).

The v2026.06.06.1 brief 5-pillar order is now logged as retired in RETIRED.md.

---

## v2026.06.06, Full Canon Reset

**Files updated:** README.md · OFFERS.md · IP-REGISTRY.md
**Files created:** DISCOVERY-LAYER.md · AFFILIATE.md · RETIRED.md · CHANGELOG.md

### Retirements

1. **A prior identity offer**, formally retired. Replaced by The Becoming™ at the Gold tier ($4,620). Logged in `RETIRED.md`. Permanent exclusion from all output.

### Locks

2. **The Becoming™ confirmed at Gold** ($4,620 or 3×$1,620 payment plan)
4. **Revenue Architecture System (RAS™) → Gold bridge:** Payment plan functions as the bridge. No separate offer.
5. **Platinum → Find Yourself gap:** Intentional structural mechanism. No bridge.

### New Architecture

1. **Discovery Layer** formally separated from priced stack
2. **Affiliate program** documented as parallel revenue line
3. **Speaking** documented as parked future productization

---

## VERSION POLICY

1. Version format: `vYYYY.MM.DD[.N]` where N is the patch number for the same date
2. Every file carries the current version at top
3. Every change logged here with date, files touched, and summary
4. Retirements are permanent, once logged in `RETIRED.md`, the asset does not return under that name
