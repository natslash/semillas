# semillas

Private, code-named ledgers for my work as Senior Engineering Manager (Property Management Platform, Valencia hub). Plain markdown in git; no tool or LLM provider holds state. Any assistant working here reads `AGENTS.md` first.

**Rule zero: no real names, ever.** People appear only under the code names in the legend below. The key (code → real name) lives outside this repo and is never pasted into a chat that writes here. If a real name slips in, it is replaced, not reworded around.

## Layout

| Path | What it is | Rotates? |
|---|---|---|
| `AGENTS.md` | Operating instructions for any model/agent working in this repo | no |
| `CLAUDE.md` | One-line pointer to `AGENTS.md` | no |
| `prompts/` | Recurring procedures: weekly review, monthly insights, quarterly rotation, meeting prep, Friday update | no |
| `00-context.md` | Role, mandate, org, Jandro's expectations, cadences. Changes rarely | no |
| `05-self.md` | My own ledger: fears, ambitions, bets, decisions and the reasoning at the time | never |
| `10-stakeholders.md` | One block per person: role, what they care about, how they work, my current read | no (edited in place) |
| `20-em-*.md` | One ledger per EM reporting to me (and their team) | quarterly |
| `25-pe-tango.md` | Ledger for Tango (Principal Engineer, direct report) — the performance case | quarterly |
| `people/tango/` | Supporting docs for the case: feedback log, conversation plan | no |
| `30-tech-product.md` | california (Tech Lead) and brutus (Product Lead) | quarterly |
| `40-sem-peers.md` | Saffron and Marlow (peer Senior EMs) | quarterly |
| `50-jandro.md` | Jandro (my manager, Head of Branch Valencia) | quarterly |
| `60-hr-ops.md` | HR and Ops meetings I attend | quarterly |
| `70-threads.md` | Cross-cutting themes, each linking back to ledger entries by date. The connective tissue | never |
| `80-skip-levels.md` | One block per IC, dates seen, what I heard | no (edited in place) |
| `90-encounters.md` | One line per one-off encounter. Promote to `10-stakeholders.md` on second appearance | quarterly |
| `viz/` | Generated views, regenerated monthly by `prompts/monthly-viz.md`: timelines, tag×person matrix, commitment board, read-drift, stake map. Mermaid + one self-contained HTML | regenerated |
| `archive/` | Rotated entries and the original project dump | — |

## Entry template (ledger files)

Fixed field order, ISO dates, one entry per block, newest first. Machine-friendly on purpose so later automation only has to emit this shape.

```
### YYYY-MM-DD · <type> · <who>
- **facts:** what was said or happened. Attributable. No interpretation.
- **my read:** my interpretation, marked as such. Speculation is labelled "(speculation)".
- **commitments:** who → what → by when
- **open:** questions, things to verify, decisions pending
- **tags:** #tag #tag
```

Types: `1:1`, `skip`, `sync`, `coffee`, `mail`, `chat`, `meeting`, `self`.

Facts and my read are never mixed in one field. Observed behaviour, stated intent and inferred motive are three different things; the third is always speculation.

## Tag vocabulary

Fixed list. Add a tag only when a theme recurs three times without one.

| Tag | Covers |
|---|---|
| `#tango-case` | Everything on the Tango performance case |
| `#delivery` | Cycle time, throughput, delivery metrics, high-performing-teams question |
| `#refinement` | Upstream story quality, PO/BA capacity, Codex productivity side-effects |
| `#retention` | Flight risk of named ICs or EMs |
| `#compensation` | Salary, bands, promotions, pay review cycles |
| `#okrs` | Q1 2027 engineering OKRs and their follow-up |
| `#berlin` | Berlin teams, Berlin management, the eventual transfer of PMP Berlin teams |
| `#luna` | The LUNA team and its EM transition (Harbour → Guy) |
| `#hiring` | Headcount, roles open, growth plan to 220 |
| `#ai-wg` | AI working groups, AI pilots, hackathon |
| `#learning` | Learning budgets and learning goals |
| `#org-design` | Team arrangement, dev-lead vs EM structure, role definitions |
| `#politics` | Who is positioning for what; who is watched by whom |
| `#manager-dev` | Developing my EMs as managers |
| `#roadmap` | Product roadmap clarity, what teams know about what's coming |
| `#me` | My own onboarding, standing, fears, ambitions |

## Code legend (role only — no names here)

| Code | Role |
|---|---|
| Jandro | My manager, Head of Branch Valencia |
| Saffron | Peer Senior EM; most experienced of us (joined ~Sep 2026); cards and some teams; Valencia teams only for now |
| Marlow | Peer Senior EM; joined late Oct 2026; business banking with me; already has Valencia + Berlin teams |
| california | Berlin Tech Lead who owns PMP engineering; my technical partner; assigns tasks to Tango |
| brutus | Product Lead for PMP |
| Walrus | california's manager in Berlin |
| Gross | EM reporting to me (Valencia) |
| Blanket | EM reporting to me (Valencia); my onboarding buddy |
| Harbour | Interim EM for LUNA (Germany); may report to me in future |
| Guy | Incoming EM for LUNA, joins 2026-12-01 |
| Tango | Principal Engineer reporting to me; my ex-colleague; referred me |
| Comet | Senior engineer in Gross's team; star performer heading for principal |
| Flint | Engineer with a history of heated arguments with Tango |
| Drift | Engineer on Harbour's PIP |
| Hazel | HR partner |
| Compass | Operations; onboarded me; tool access |
| Anchor | Berlin manager running the other expected PIP |
| Ruler | Berlin contact for delivery metrics methodology |
| Ledger | Product peer holding the €30k product learning budget |
| Lantern | PO working with Gross's team |
| Quill | BA working with Gross's team |
| ENG-2…ENG-5 | Engineers in Gross's team, in the order of my notes; named when they recur |

Teams, locations and tools (LUNA, Sirius, GK, PMP, Valencia, Berlin, Leapsome, Codex) are kept as-is.

## Navigating

Open the repo folder as an Obsidian vault for search, tag browsing, backlinks and graph view. Entries link people and threads as `[[Gross]]`, `[[tango-case]]`; the graph is built from those. `.obsidian/` is gitignored. For patterns rather than navigation, use `viz/`.

## Workflow

- **Weekly (Friday):** paste raw notes → `prompts/weekly-review.md` → entries added, `70-threads.md` updated, Friday update drafted → commit.
- **Monthly:** `prompts/monthly-insights.md` over the whole corpus, then `prompts/monthly-viz.md`.
- **Any session:** decisions, changed reads, commitments and open questions that emerge from discussion are filed as `chat` entries before the session ends (AGENTS.md §4).
- **Quarterly:** `prompts/quarterly-rotation.md` — entries older than ~3 months compressed into a dated summary paragraph per file; raw entries moved to `archive/`.
- **Before a hard conversation:** `prompts/prep-meeting.md`.

## Privacy

Pseudonymised is not anonymous: a careful reader could re-identify people from context. Private repo, 2FA, personal account only. If anything here would be damaging if leaked even under code names, it goes in `05-self.md` and that file is a candidate for `git-crypt`.
