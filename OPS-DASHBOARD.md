# Sovereign Ops Dashboard
### Baz Porter LLC® | The Prestige Architect®
**Single pane of glass for the full Sovereign Leadership Architecture™ ecosystem.**

---

## What This Is

The Ops Dashboard is the operating layer of this repository. It does two things:

1. **Surfaces ecosystem state** across four zones — Offers & Funnel, IP & Trademark, Frameworks & Methodology, Channels & Credibility — pulled directly from the canonical markdown files.
2. **Runs agents on demand** — a Claude Code subagent roster with a top-level orchestrator that dispatches specialist agents in parallel. Agents running agents.

*The dashboard does not replace the canonical documents. It indexes and audits them.*

---

## Three Ways to Use It

| Surface | How to launch | Best for |
|---|---|---|
| **Slash commands** (fastest) | Type `/check-everything` (or any command below) in Claude chat | Daily ops — one command, agent runs, report appears |
| **Console UI** | Open [`dashboard/index.html`](dashboard/index.html) in a browser | Visual overview of the whole ecosystem, browsing offers/trademarks/etc. |
| **This file** | Read `OPS-DASHBOARD.md` | Canonical text record in repo style |

### The Slash Commands

Type any of these in Claude chat. The right agent runs automatically.

```
/check-everything       Full health check on all 4 parts of your business
/ops                    Short alias for /check-everything
/ops-help               Show this list anytime

/check-offers           Audit all 12 offers — prices, tier health, conversion path
/check-killzone         Check the $497 → $5,997 pricing bridge
/check-pricing          Look for discounts, fake bonuses, fake scarcity

/check-trademarks       Audit trademarks — what's registered, what's risky
/trademark-priority     Tell me what to file first

/check-methods          Audit all frameworks — docs, naming, deployment
/fix-rams               Fix the RAMS naming mix-up
/find-gaps              Find frameworks in IP-REGISTRY with no file

/check-reputation       Audit reputation, credentials, channels
/check-voice            Check writing voice consistency
/check-content-universe Check whether the 20-piece content system exists
```

You can also just describe what you want in plain English ("audit my offers", "what trademark should I file first?") and Claude will pick the right agent.

---

## The Four Zones

### Zone 1 · Offers & Funnel
**Source:** [`OFFERS.md`](OFFERS.md)
**Agent:** `offers-funnel-agent`
**State:** 🟢 Live

The Full Ascension Stack — 12 tiers, from Free Content Universe (Tier 0) to The Coming Home Project (Tier 11, $1M/year, invitation only).

**Critical mechanics monitored:**
- **The Kill Zone** — $497 → $5,997 bridge via Reclaim Her Power ($4,620) + $500 BPA Priority Gateway
- **Diamond capacity** — 8 seats annually, SCD™ qualification required
- **Pricing integrity** — no manufactured value stacks, no inflated bonus math, no artificial scarcity

**Known drift:** Business Profit Accelerator listed as **$5,997** in `OFFERS.md` but **$5,998** in `README.md`. Reconcile.

---

### Zone 2 · IP & Trademark
**Source:** [`IP-REGISTRY.md`](IP-REGISTRY.md)
**Agent:** *handled by `ops-orchestrator` directly*
**State:** 🟡 Watch

| Mark | Status | Priority |
|---|---|---|
| BAZ PORTER | Registered · Reg. 7125540 · Class 041 | — |
| THE PRESTIGE ARCHITECT | Filing priority | Tier 1 |
| RAMS / RAMS FRAMEWORK | **Deployed in 3 institutions under common-law ™ only** | Tier 1 |
| SOVEREIGN LEADERSHIP | Pending | Tier 2 |
| SILENT COLLAPSE | Pending | Tier 2 |
| THE GRAVITY CODE | Pending | Tier 3 |
| THE FIVE IMPOSTERS | Pending | Tier 3 |
| Six Drives of Human Intelligence™ | Registered — protection active | — |

> *Licensing without federal registration is a structural vulnerability.* — IP-REGISTRY.md

---

### Zone 3 · Frameworks & Methodology
**Source:** [`FRAMEWORKS.md`](FRAMEWORKS.md), [`METHODOLOGY.md`](METHODOLOGY.md), [`frameworks/`](frameworks/)
**Agent:** `frameworks-methodology-agent`
**State:** 🟡 Watch

Eleven active proprietary frameworks. Six-Layer Integration Model runs through every module: Neuroscience · Quantum Principles · Military Doctrine · Identity Architecture · NLP Pattern Installation · AI Governance Ethics.

**Known drift:** RAMS™ acronym is inconsistent across docs.
- `METHODOLOGY.md` / `README.md`: **Results · Attitude · Mastery · Systems**
- `FRAMEWORKS.md`: **Results, Attitude, Authenticity, Mastery, Systems**
- A Million Dreams™ Bronze: **Regulate, Activate, Modulate, Stabilize**

**Gaps:** Sovereign Nervous System Protocol™, The Oliver Standard, Sovereign AI Charter™ — registered in IP-REGISTRY.md but no standalone `frameworks/*.md` file.

---

### Zone 4 · Channels, Credibility & Content
**Source:** [`CREDIBILITY.md`](CREDIBILITY.md), [`PROFILE.md`](PROFILE.md), [`README.md`](README.md), [`STORY.md`](STORY.md), [`VOICE.md`](VOICE.md)
**Agent:** `channels-credibility-agent`
**State:** 🟢 Live

**Distribution:** bazporter.com · LinkedIn · Rise From The Ashes (C-Suite Network, 100+ eps) · Substack · YouTube · Silent Collapse Diagnostic landing · Apply page · Delphi AI Clone (24.7K minds trained).

**Proof anchors:** 2× international bestseller · Excel Arena London (35,000 attendees) · Princeton invited speaker · Tony Robbins Platinum Partnership · Best Transformational Leadership Coaching 2024 · British Army 6.5 years · Yahoo Finance / CEO Weekly / Thrive Global featured.

**Content Universe (Tier 0):** 20-piece deployment across the Four Worth Distortion Patterns — Boundaries · Courage · Deservability · Love.

---

## The Agent Roster

All agents live in [`.claude/agents/`](.claude/agents/). They are Claude Code subagents — defined as markdown files with YAML frontmatter — and are invoked automatically when their description matches the user's request, or explicitly via the `Agent` tool.

| Agent | Role |
|---|---|
| [`ops-orchestrator`](.claude/agents/ops-orchestrator.md) | Top-level dispatcher. Runs full ecosystem audits. Handles the IP zone directly. Calls the three specialists in parallel and synthesizes one executive report. |
| [`offers-funnel-agent`](.claude/agents/offers-funnel-agent.md) | Owns the Full Ascension Stack. Audits tier health, Kill Zone, pricing integrity, cross-doc drift. |
| [`frameworks-methodology-agent`](.claude/agents/frameworks-methodology-agent.md) | Owns the framework portfolio. Audits trademark/deployment/file consistency. Flags RAMS™ acronym drift. |
| [`channels-credibility-agent`](.claude/agents/channels-credibility-agent.md) | Owns channels, proof points, and voice. Audits the Content Universe and distribution surfaces. |

### How "agents running agents" works

When you click **▶ Full ecosystem audit** in the HTML dashboard (or paste the prompt into Claude Code):

```
ops-orchestrator
   ├─→ offers-funnel-agent         (parallel)
   ├─→ frameworks-methodology-agent (parallel)
   ├─→ channels-credibility-agent   (parallel)
   └─→ IP-REGISTRY.md audit (self)

   ↓

   One synthesized executive report:
     • TL;DR
     • Zone Status table (🟢🟡🔴)
     • Cross-Zone Signals
     • Top 3 Recommended Actions
```

---

## Operating Principles

- **The dashboard never invents numbers.** Revenue, conversion rates, seat utilisation, dates — these come from you (via the HTML KPI inputs, which persist to your browser's localStorage) or are marked `TODO — user to fill`.
- **Cross-doc drift is the most important signal.** A price mismatch between `OFFERS.md` and `README.md` is a real structural problem, not a typo.
- **Words matter exactly.** Every ™ and ® is enforced. The agents never rename frameworks or paraphrase doctrinal language.
- **The voice is architectural.** Declarative. No coach-speak. No exclamation points. Match `VOICE.md`.

---

## Quickstart

```
# 1. Open the dashboard
open dashboard/index.html

# 2. Click any ▶ button to generate an agent prompt
# 3. Copy and paste into Claude Code chat
# 4. The right subagent is invoked automatically
```

To run the full ecosystem audit from Claude Code without the HTML view, paste:

> Use the ops-orchestrator agent to run a full ecosystem audit of the Sovereign Leadership Architecture™ portfolio.

---

*© 2019–2026 Baz Porter LLC®. All Rights Reserved.*
*Baz Porter LLC® and The Prestige Architect® are registered trademarks.*
