# Context brief — Senior EM, Property Management Platform (PMP), semillas
*State of play as of Saturday 07/11/2026 (end of week 1). All people coded; see README for the code legend.*

## Who I am in this role
- Shashi. Senior Engineering Manager, PMP, semillas ("semillas"), Valencia. Started Mon 02/11/2026. Hired for "Sirius" (Jandro's wording) and work closely with Marlow in GK.
- Background: 20+ years engineering; roots in test automation; previously Delivery Lead / People Unit Lead at Deutsche Telekom (8 teams, 4 countries, 12 team leads, 30+ people).
- Reports to Jandro (Head of Branch Valencia). Peers: Saffron and Marlow (Senior EMs, Valencia). Technical partner: california (Berlin Tech Lead, owns PMP engineering). Product partner: brutus.
- Direct reports: Gross, Blanket (both Valencia EMs), Harbour (interim, Berlin, LUNA team until Guy joins 1 Dec), and Tango (Principal Engineer). Three teams in my area: Gross's team, Blanket's team, LUNA.
- Recurring meetings: 1:1s and skip-levels with my teams; all-EMs sync; weekly SEM sync plus shared meeting with Jandro; weekly 1:1 with california; weekly trio with california and brutus; HR/Ops syncs (attend, not run).

## Jandro's expectations (his words, from the offer stage)
- **30 days:** product/domain knowledge, who's who, political landscape (incl. how teams perform and work in the current dynamic), issues with product and people, proposals, start acting under Jandro's consultancy.
- **90 days:** extend scope to the Valencia hub and company, drive initiatives, prepare end-to-end plans.
- **180 days (average):** impact and initiatives at domain level. **180 days (exceeding):** Jandro hears about me from others; trust with brutus and california; PMP strategic plan with them by summer 2027; influence on budget; more projects for the hub.
- **His core doubt I must answer:** can I turn settled teams into high-performing ones.
- Review agreed after six months.
- Long-term direction: Valencia is semillas's main location; the three Berlin PMP teams (now under california) would eventually come under me.
- **Weekly Friday update required**, in his format: what went well / issues & risks / blocked / what needs his attention, each item marked "ask" or "for awareness". He wants autonomous decisions with reasoning explained there, and a clear line on whether he needs to act.
- Jandro has publicly (in the SEM channel, aimed at Saffron) complained about having to micro-manage ownership/pro-activity. He will judge me on whether he ever has to chase me.

## Working rules I have set for this project
- Anonymise everyone with role codes. Name key stays in my own files, never in project docs or chats.
- 1:1 notes with EMs are shared with them (via Leapsome at semillas; Copilot later) for transparency; confidential parts kept in a separate section/file.
- Tango feedback is kept in one confidential file: `people/tango/feedback-log.md`, entries tagged by source and date.
- Longer term: private git repo of code-named markdown ledgers, LLM-provider neutral, manual input for now.

## Open thread 1 — Tango (highest priority)
**Situation:** Tango reports to me, is my ex-colleague and referred me for this job (conflict of interest, to be disclosed to Jandro). Jandro's welcome mail called him "a potential PIP case in my view" and asked me to assess the evidence, reach my own conclusion, coordinate with relevant managers and HR/Jandro. california says this should have been dealt with two months ago. Walrus has reportedly questioned whether my role is needed, so Berlin is watching this case.

**Feedback collected (consistent, multi-source):**
- Blanket and team: largely absent; vague/avoiding answers; team bypasses him (FYI only); he seems fine with it; structured written feedback given several times, no reaction; team thinks it may be too late but believes in second chances.
- california (05/11): not impressed from the start; lacked knowledge of Berlin tech stack; no ownership; unjustifiable excuses; several tasks over several months, not one quality deliverable; point of no return. **Never gave him direct feedback** (not his manager).
- Harbour (05/11): same opinion. **Never gave him direct feedback**; admits she should have.
- Team members of Gross and Blanket: conflictive discussions; documented feedback accepted, no follow-up, no change.
- Three more pieces of feedback still to come.
- My hypothesis: nobody with authority ever set expectations or consequences; Tango may not know his output is seen as mediocre.

**Decision (06/11/2026):** 2-week pre-PIP, then formal 6-week PIP. First conversation: make him aware of the feedback, hear his understanding, state that specific expectations are coming, offer support. Full outline and likely reactions in `people/tango/conversation-plan.md`.

**Still to do:**
- Disclose the referral to Jandro (in person + one line in Friday update) and get his agreement; get the HR contact.
- Learn semillas's PIP process from Harbour (running one since late Oct) and HR: template, duration, whether pre-PIP is written and HR copied.
- Collect evidence: california's task history (task, date, expected, delivered); teams' documented feedback; whether a written PE role description exists.
- Define what Tango must deliver in the 2 pre-PIP weeks (proposal: his own assessment of gaps + committed deliverables, agreed with california as the yardstick).
- Book the first conversation: 60 min, meeting room, at work. I have not yet spoken to Tango since joining.
- Written summary to Tango same day; log it in feedback-log.md.

## Open thread 2 — Engineering OKRs (Q1 2027)
- Saffron and Marlow drafted 13 rows against Jandro's O1–O10 before I joined; Saffron consolidates into the main tracker (Leapsome). My read: strong outcome-oriented thinking, but too many rows, hedged language ("if agreed", "when feasible"), ownership spread to groups, Q1 mostly baselining, thin on actual engineering (delivery, tech debt, architecture, security, cost), no capacity check.
- I chose to stay quiet in the channel on day 3 and to meet Saffron and Marlow together (not separately) — questions first, then offers, trimming raised as a question.
- **My rows (name + firm date, no hedging):**
  1. **O4.KR2** — delivery metrics baseline for Sirius: median cycle time and MR merge time per team, same method as semillas Berlin (confirm with Ruler); one target per team with its EM. Baseline 31 Jan; targets 15 Feb; review 31 Mar. Lead: me with the EMs.
  2. **O3.KR2** — co-own with Marlow: the €25k technical learning budgets (each) spent only against agreed role-relevant learning goals; ≥20% of engineers complete a goal and show what they applied in Q1. Rules 31 Dec; check 31 Mar.
  3. **O4.KR1** (existing row, append — do not add a duplicate): Valencia hackathon track "a new engineer is productive in X minutes" (one of Jandro's own ideas): automate dev env setup, access requests, first local build-and-test. Measure laptop-handover → first green local test run for Q1 joiners. Can carry HR/Ops AI cases as VLC pilot ideas for the AI working groups. Track proposed by 30 Nov; result at the hackathon. Lead: me. X set after baseline.
- Things to watch: don't step on Marlow's AI-working-group ground; don't take Saffron's mentorship/mobility rows; be useful to Marlow on QA/test manager hiring (my background) rather than claiming it.
- Still need: Jandro's main tracker with the O1–O10 objective texts.

## Open thread 3 — Team and delivery observations (from Gross / Blanket catch-ups)
- **Upstream refinement bottleneck:** Codex has raised developer output; Lantern and Quill are under pressure; stories arrive incomplete and developers fill the gaps invisibly. Next: quantify with the EMs for a sprint or two before proposing a fix with Product; frame as capacity mismatch, not quality blame. Candidate OKR material.
- **Tickets lack business value** — Gross's fix request; needed to measure delivery impact.
- **Retention risk — Comet** (Gross's team): star performer heading to principal, paid well below. Probably already doing part of the missing principal work. Raise with Jandro before the next pay review; discuss with Gross separately from Tango.
- **Gross:** salary could be a factor for him leaving; topics for Jandro: promos/salary, org-wide benefits; unsure about semillas goals; suggests re-arranging teams (Valencia has EMs and no dev leads; Berlin has dev leads and EMs are only people leads).
- **Blanket:** imposter syndrome, still learning as manager. Plan: concrete development structure in 1:1s (pick 1–2 weak areas, small development slot), ask specific questions rather than "how can I support you".
- **LUNA:** worked with Harbour to understand the team; she introduces me next week and announces Guy joining 1 Dec.

## Context from Jandro's weekly update (30/10/2026)
- Salary bands transparency posted by HR; EM salary bands to be discussed among SEMs and Jandro (idea: announce mid-Nov, manual Leapsome cycle for managers ~6 weeks, adjustments early Jan).
- Engineering promotion committee likely shared Valencia+Berlin, with SEMs from both; invites mid–late Nov.
- AI working groups: goals aligned, launching; VLC-only pilot ideas welcome; Marlow, Ledger and one more are in them.
- OKRs rolled out in Leapsome; general alignment on Thursday 05/11.
- Hiring: QA more in focus (Marlow); backend bulk hiring for Broker; Agile for Broker, Test manager for GK Onboarding, designers. Growth plan: VLC 220 by EOY 2027 (currently 126 active + 16 onboarding ≈ 142).
- Learning budget 2027: Saffron €40k leadership/coaching; Ledger €30k product; Marlow and me €25k each, technical. Interview Mastery Programme rolling out — sign up.
- Offices: temporary CoworkUp Puerta de la Mar from Dec, move-in Jan; permanent office fit-out from 1 Dec, target April (best Feb, worst June).
- Hackathon: cross-location; Jandro wants Valencia strongly involved; his ideas include parking/social-events app, office life, HR tool migration kickoff, "set up employee in X minutes".
- Exec visits: the parent bank IT 10–12 Nov; another exec 19 Nov; semillas senior leadership early Jan.
- Harassment survey results with Jandro; discussed with Saffron.

## Week-1 Friday update (06/11) — content
Went well: onboarding + access setup, mandatory trainings in parallel; met california, Harbour, Blanket, Gross; two sessions each with Gross and Blanket (teams, ways of working, key people; agreed collaboration rules; will document and share 1:1s); LUNA with Harbour (intro next week, Guy announcement); OKR proposals with Saffron/Marlow.
Issues/risks: upstream refinement bottleneck (awareness); Comet retention (awareness); Tango decision + referral transparency (ask: agreement + HR contact).
Blocked: no access yet to Confluence, Miro, ChatGPT and other tools (ask: Jandro or Compass to speed up).
Next week: LUNA intro; coffees with POs (Valencia and Berlin); set up EM round table alongside 1:1s; check in with Anchor on Drift's PIP; finish Tango feedback and talk to HR; continue trainings.

## Preferences for how Claude should work with me here
- Sharp trade-off analysis over option surveys; objectivity toward the goal, not flattery.
- File 1:1 notes under `1on1s/<code>/<date>-<type>.md`; Tango material under `people/tango/`.
- When I say "just notes, not looking for an answer", file and wait.
- Help with the weekly Friday update in Jandro's format.
