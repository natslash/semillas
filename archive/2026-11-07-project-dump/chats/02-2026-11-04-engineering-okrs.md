# Chat 2 — Engineering OKRs planning
*04/11/2026 10:10 → 05/11/2026 12:16 (Europe/Madrid). 18 turns. Real names replaced by role codes; tool calls summarised in [brackets]. The uploaded spreadsheet `Q1_2027_Engineering_OKR_Decisions.xlsx` (13 rows) is not reproduced here; its content is reflected in Claude's analysis.*

---

**Shashi (04/11 10:10):**
Engg OKRs,

So, we need to work on OKRs for engg and my peers (2 SEMs) are already working on it. They have shared an excel, I'll share it here. I'll also provide you with some chats and a mail where I was made aware of this. LMK, what do you make of all this and my next move.

Mail (from Saffron):
> Hi everyone!
> Shashi, we'll share more context about the OKRs soon. Since this is your first week, we wanted to keep you in the loop as you get up to speed.
> Marlow and I discussed Jandro's proposed OKRs today. I've added our ideas and some proposals from Marlow's document to the spreadsheet. Please review the list and add your comments. I'll add the ideas to the main spreadsheet before Thursday.

chat and excel coming next

**Claude:** [memory_read `/areas/dkb-application.md`]

**Shashi (04/11 10:10):** *(uploaded the chat screenshots and `Q1_2027_Engineering_OKR_Decisions.xlsx`)*

**Claude:**
[Bash: dumped the spreadsheet with openpyxl]

Short version: the sheet is solid, but it's too long. It skips the one thing Jandro explicitly asked engineering for, and nothing in it is yours yet. You have about a day before Saffron merges it into the main tracker on Thursday, so the move is a few sharp comments plus claiming one or two items, not a rewrite.

**What I make of it**

- **It ignores Jandro's brief.** He asked for "a few" subgoals, especially where engineering connects to other functions. Your peers sent 13 rows. Too many items means none of them gets real attention, and that hurts engineering's credibility in the main tracker.
- **The connection he named is missing.** He asked engineering to help HR, Ops and Office with their AI ideas, maybe through a hackathon. The closest row, O6.KR4, is an AI trial for engineering's own Web features. Nothing covers the other departments. This is the clearest gap, and it's one you could fill.
- **Saffron and Marlow are aligned, and you came in late.** Saffron leads the mentorship and internal mobility rows, and the rest say "SEMs" or "EMs". If you just add comments, you end up with a share of rows that nobody actually leads.
- **Some rows are weaker than others:**
  - **O6.KR4** can only start after O6.KR1–KR3 are delivered (tool access, shared GPT library, Jira/Confluence integration). It also needs a January baseline and a 15% improvement by March on a small sample. Realistically you'll get a baseline and noise. Better to frame Q1 as "baseline plus a go/no-go decision".
  - **O5.KR2** asks for skills-matrix goals for every engineer by 31 January, across the holidays. That's heavy, and it overlaps with O3.KR2 (learning goals) and O8.KR1 (mobility plans built on the same matrix). Merge them or move the date.
  - **O1.KR1 and the new reliability KR** both set technical targets for the same services. Merge them.
  - **Three rows are proposals to change Jandro's KRs** (O3.KR2, O5.KR1, O10.KR1). Each one is reasonable, but three at once reads as pushback. Keep O10, because the 92% target can't be measured without a definition. Drop or soften one of the other two.
- **I can't see Jandro's actual objectives** (the text behind O1–O10 in the main tracker). So I can't check whether these rows actually connect to the Product, TA, HR and Ops goals. Ask for that link before you judge it.

**Your next move (today)**

1. **Claim one delivery item and one connection item.**
   - **O4.KR2 (cycle time and MR merge time baseline).** It speaks directly to Jandro's main doubt, whether you can turn settled teams into high-performing ones. california also said the real problem is delivery. A baseline is honest Q1 work for someone in his first 90 days.
   - **The missing AI-enablement item for HR, Ops and Office.** Something like: a hackathon in Q1 that produces one or two working use cases those teams actually adopt. It's cheap, it's what Jandro asked for, and it gets you working beyond your own teams early. The cost is that it takes engineers' time away from product work, so cap it at the hackathon plus a small follow-up.
2. **Leave three or four comments in the sheet**, not twenty: the count, the merges, and making O6.KR4 a decision rather than a target.
3. **Get 15 minutes with Saffron before Thursday.** Agreeing with her in a short call works better than overriding her work in comments during your first week.

Draft reply for the thread:

> Thanks Saffron and Marlow, great base to start from. A few thoughts before you consolidate: (1) Jandro asked for a few subgoals focused on connections, so could we trim to ~6 and merge the overlaps (O1.KR1 + reliability; O5.KR2 / O3.KR2 / O8.KR1 all use the skills matrix)? (2) Nothing covers enabling HR/Ops/Office AI cases yet. I'm happy to own that, e.g. via a Q1 hackathon. (3) I can also take O4.KR2, the delivery metrics baseline. Could we do 15 min today or tomorrow morning? And can you share the main tracker so I can see the cross-team objectives?

Want me to turn the AI-enablement item into a row in the sheet's format, ready to paste in?

---

**Shashi (04/11 10:13):**
There was a weekly update which I missed in all the onboarding stuff, here it is, this is from Jandro:

> **Weekly update — 30 October 2026**
> * New Joiner: Welcome Shashi (Monday) Senior EM for Sirius and working closely in GK with you Marlow!
> * Salary bands transparency — HR posted a message and no change there, we just need to monitor and support EMs if issues arise
> * EM Salary Bands — to be discussed among SEMs and Jandro. Idea: announce salary band change in manager channel mid-November and trigger manually Leapsome cycle for managers (takes 6 weeks); early January every EM is adjusted; lift the 6k salary increase (unsure); add some engineers who are doing exceptionally in the cycle as well (unsure)
> * Promotion committee Engineering: likely one Engineering committee for Valencia and Berlin, including SEMs from both locations. [HR lead] has adjusted the proposal to reflect my input and favors a shared committee for alignment. Watch for delays; invites and next steps expected mid- to late November. Positive will be more alignment, afraid of slowing down but can be mitigated
> * AI working groups: final alignment on goals planned for next Thursday, followed by launch. VLC-only pilot ideas would be welcome. Ledger, Marlow and one more are in the groups.
> * OKRs: rollout continues, I created all in Leapsome as well, stick to the channel, I present to HR/Ops next week as well, on Thursday we have a general alignment, I expect it to be short
> * Benefits-2027: presentation in AH and survey starts today or early next week; I calculated the cost of all existing benefits 2026 and already have some plans for 2027 but first we need to know the preferences
> * Hiring and growth: no priority changed; QA is more in focus now (watch out Marlow), Visa progresses really well (Saffron). Backend bulk hiring starts in a few weeks for Broker and others. We start Agile for Broker, Testmanager for GK Onboarding and Designers as well. Overall growth plan — VLC 220 by EOY 2027
> * Learning budget — company wide for 2027: Saffron €40k leadership/coaching/mentoring (to support the mentoring program if needed); Ledger €30k Product; Marlow and Shashi €25k each, specify on technical learning. Prioritize useful cross-company activities. Selected company-wide engineering/product events may be sponsored separately. Interview Mastery Programme is rolling out after the Berlin/Valencia trial; please sign up this week.
>
> **Operations and offices**
> * Corporate cards: contract in progress; November rollout remains the goal, though AirPlus is slow
> * GFT office: internet resolved, water as well
> * Temporary offices: CoworkUp Puerta de la Mar contract signed; lease starts in December; move-in planned by January. Plan is to leave GFT and Nomadom by end of December. I'll present this at AllHands.
> * Permanent office: fit-out terms agreed; waiting on one construction partner's legal team. Site work continues; hotel plans finished due by end of November. Fit-out planned from 1 December; allowing up to four months, with an April move target. Best case February. Worst case June. Estimate is 2 month construction (I double everything now in Spain regarding construction)
> * Hackathon: we will do cross locations but I want us to be strongly involved, suggest topics, personally I have some ideas regarding improving ops e.g. app for booking parking or doing social events or similar; office life; do a kickoff to migrate HR tool (maybe); build a "Setup employee in X minutes with all"
>
> **Staffing and upcoming dates**
> - Roster: latest roster pivot shows 126 active and 16 onboarding.
> - Executive visits: the parent bank IT, 10–12 November; [exec], 19 November; semillas Senior Leadership in early January
>
> **Harassment:** results are shared with me Monday, Saffron we discuss in our 1:1

**Claude:**
This changes a few things. Mostly it makes your angle sharper, and it corrects one thing I suggested earlier.

**What changes**

- **The AI angle overlaps with Marlow.** The AI working groups already exist, with Marlow and others in them, and their goals get aligned tomorrow. If you say "I'll own AI enablement for HR/Ops" in your first week, you step onto your closest peer's ground. Drop that framing. Feed the HR/Ops AI cases in as VLC pilot ideas, which Jandro has explicitly asked for, and run them through the hackathon instead.
- **The hackathon is your opening.** Jandro wants Valencia strongly involved and listed his own ideas. One of them, "set up a new employee in X minutes", matches O4.KR1 (new joiners can build, run and test on day 2). Growth makes this urgent: about 142 people now (126 active, 16 onboarding) and a 220 target by end of 2027, so roughly 80 more joiners. Linking onboarding speed to the hackathon to the growth plan connects three things he cares about. Nobody owns it yet, and it doesn't step on Saffron or Marlow.
- **O3.KR2 now involves you directly.** You hold €25k of technical learning budget for 2027. Saffron and Marlow propose measuring learning outcomes instead of budget use, and that proposal now covers your money. Back it and co-own it with Marlow. It costs you little and makes you accountable for something real.
- **QA is in focus, but it's Marlow's.** QA hiring is Marlow's area ("watch out Marlow"), and there's a test manager role for GK Onboarding. That's your background, and you work closely with Marlow in GK. Offer help rather than claiming it. Being useful to him early is worth more than one more OKR row with your name on it.
- **Timing:** the general alignment is tomorrow (Thursday), and Saffron consolidates before it. The exec visits on 10–12 and 19 November will eat the following weeks. Your input has to land today.

**Revised plan**

1. **Lead O4.KR2** (delivery metrics baseline for Sirius). It still answers Jandro's question about turning settled teams into high-performing ones.
2. **Propose one new connection item:** a Valencia hackathon track on "set up a new employee in X minutes", linked to O4.KR1. It can carry the HR/Ops AI cases.
3. **Co-own O3.KR2** with Marlow, tied to your €25k.
4. **Leave the comments on cutting the list and merging overlaps** as they were.

Updated thread reply:

> Thanks Saffron and Marlow, solid base. Before you consolidate: (1) Jandro asked for a few subgoals focused on connections, so could we trim to ~6 and merge the overlaps (O1.KR1 + reliability; O5.KR2 / O3.KR2 / O8.KR1 all use the skills matrix)? (2) I'll take O4.KR2 for Sirius. (3) Happy to co-own O3.KR2 with Marlow, since it covers our €25k technical learning budgets. (4) One connection proposal: tie O4.KR1 to a VLC hackathon track on "set up a new employee in X minutes" (one of Jandro's ideas). It also gives a home to the HR/Ops AI cases, and I can feed it into the AI groups as a VLC pilot idea. Got 15 min today?

The rest of the update (salary bands, promotion committee) is SEM business that's coming your way, but it's separate from the OKRs. Want the hackathon/onboarding item written up as a row in the sheet's format?

---

**Shashi (04/11 11:32):**
new response from Jandro on the chat:
> Ah apologies, Yes see it. Thank you very much!
> I still fail to distinguish between you and you meeting my expectations regarding ownership/pro-activity to some other topics/people at the moment, where I have to micro manage every day.

**Claude:**
It depends who Jandro was writing to, and I think it was most likely Saffron and Marlow, not you. "Ah apologies, yes see it" fits as an answer to Saffron's "let me know if you see our contributions". He opened the thread with a "quick reminder" to them. So the second sentence reads as: *I had to chase you on this, and I can't tell whether you'd have taken it on yourselves.* The grammar is garbled, but that's the most likely sense. If you'd already posted something in the thread and he was replying to you, tell me, because then it means something quite different.

Assuming it's aimed at them, here's what it tells you:

- **Jandro is frustrated with how much ownership he's getting**, enough to say so in a group channel during your first week. That fits the "political landscape" part of his 30-day expectations. Note it privately and don't react in the thread.
- **The bar is set by contrast.** He'll judge you on whether he ever has to chase you. That counts for more than how good your OKR comments are.
- **It changes how you should post.** Right after his jab, a public "let's trim to 6 and merge the overlaps" reads like you're piling on, or scoring points at your peers' expense. You'd gain a little with Jandro and lose a lot with Saffron and Marlow, and you need them more day to day.

So split the draft I gave you:

**In the thread (visible ownership, no critique):**
> I'll take O4.KR2 for Sirius and co-own O3.KR2 with Marlow (our €25k technical learning budgets). I'll also add a proposal linking O4.KR1 onboarding to a VLC hackathon track, "set up a new employee in X minutes". Will be in the sheet today.

**To Saffron directly (DM or a 15-minute call):** the point about trimming to "a few", the merges, and making O6.KR4 a go/no-go decision rather than a 15% target. Frame it as helping her land the list well in tomorrow's alignment, not as correcting it.

Then do what you said, and do it before you're asked. Put the rows in the sheet today, before Saffron consolidates. That's the behaviour Jandro is telling you he's short of.

---

**Shashi (04/11 11:33):**
to Saffron

**Claude:**
That makes it sharper. Jandro said it to Saffron, in a channel where you and Marlow can read it. That tells you a few things:

- **The gap is specifically with Saffron.** He chose to say it publicly, not in their 1:1. Either he's past the point of handling it privately, or he's signalling the standard to the rest of you. Either way, that's a manager–report issue between them. Don't get pulled in.
- **Expect to be used as a contrast.** If you deliver cleanly, he may hold you up against her, out loud or not. That helps you with Jandro and costs you with Saffron. Stay neutral: be visibly reliable without ever positioning yourself against her.
- **Saffron is probably stung right now.** That makes your DM more valuable, and riskier. Lead with something genuinely useful, like helping her land a tight list in tomorrow's alignment. Don't open with the critique. One good line on what's strong (the KR-change proposals and the mentorship row are well reasoned), then "a couple of thoughts to make it land tomorrow". Skip anything about Jandro's comment. Don't sympathise about it and don't refer to it.
- **Don't take over her items.** Mentorship and internal mobility are hers. Taking them now, even to help, would read as confirming Jandro's verdict.

The thread post stays as drafted. It's about your own ownership and touches nothing of hers.

---

**Shashi (04/11 11:34):**
that common chat for me to be informed about, I don't necessarily need to reply there on my third day, but I need to speak to Saffron and Marlow for sure

**Claude:**
Agreed. Staying quiet in the channel on day 3 is fine. Your ownership will show in the sheet, and Jandro is clearly watching it.

**Together or separately?** Meet them together for the OKRs, today or first thing tomorrow, before Saffron consolidates. They built the list as a pair. Meeting them one at a time to change it looks like lobbying, and it puts you in the middle right after Jandro's comment. Keep the 1:1s with each of them for relationship-building later this week or next, not tied to the OKRs. Marlow especially, since you share GK.

**Running the joint call (20–30 min).** Lead with questions, because on day 3 you'll learn more than you'll fix.

1. **Get the context first.** Where's Jandro's main tracker with the O1–O10 objectives? How do OKRs work here (Leapsome, check-ins, how strictly they're graded)? What happens at tomorrow's alignment?
2. **Then offer to take things on.** O4.KR2 for Sirius, co-owning O3.KR2 with Marlow, and the onboarding/hackathon idea. Concrete offers, with you doing the writing.
3. **Raise the trimming as a question**, not a verdict: "Jandro asked for a few. How many do you think will land well tomorrow?" Then suggest the merges if they don't get there themselves. It's their list. Let them do the cutting.
4. **Agree who adds what to the sheet, by when.** Today.

Then put your rows in the sheet before Saffron consolidates. That's the one thing that has to happen today whatever else does.

---

**Shashi (04/11 11:55):**
As OKRs themselves what does it tell you? Are they good enough? any insight I can gain about Saffron and Marlow?

**Claude:**
**Verdict:** the thinking is good, but it doesn't commit to much yet.

**What's strong**
- **Every row argues how it moves the KR.** That's rarer than it should be.
- **A consistent instinct for outcomes over activity.** Learning instead of budget spent (O3.KR2), pulse action instead of pulse completion (O5.KR1), mentorship deliverables instead of just NPS, skills measured with evidence rather than self-assessment.
- **Real care about measurement.** O10 asks what the 92% actually counts. The reliability row sets a baseline before any reduction target. O6.KR4 sets quality guardrails before claiming speed gains. These are people who won't be fooled by vanity metrics.

**What's weak**
- **Ownership is spread thin.** Only Saffron is named as a lead, on her two rows. Everything else says "EMs + SEM", "Engineering Leadership", or "Service owners". Several rows can only start once others agree: hub approval, Product agreement, HR data.
- **The language hedges.** "When feasible" (O2.KR1), "if agreed, set one target" (O4.KR2), plus three "Idea / Proposal" rows. That's analysis, not commitment.
- **Q1 is mostly baselining.** Defining, measuring, agreeing. That's defensible at the start of a year, but almost nothing actually improves in Q1, and the January deadlines fall over Christmas.
- **It's lopsided.** Most rows are people and process. Very little covers engineering itself: product delivery outcomes, tech debt, architecture, security, cost. For engineering OKRs, the engineering is thin.
- **There's no prioritisation and no check on capacity.** Thirteen initiatives on top of delivery, during a hiring push towards 220 people and an office move.

**What it suggests about Saffron and Marlow.** These are hypotheses from one jointly written document. Test them, don't conclude.

- **The pattern probably matches what Jandro is complaining about.** The proposals are articulate, but ownership gets pushed to groups, approvals, and dependencies on others. Good diagnosis, light commitment. If that's how they work in general, it's the gap Jandro means. Notice he aimed his comment at Saffron, and her name is the one that does appear.
- **Saffron looks people-oriented.** Mentorship, mobility and learning are where she put her name. That fits her €40k leadership and coaching budget.
- **Marlow looks technical and AI-oriented.** The O6.KR4 detail (Storybook, Xray, Codex, MCP) reads like someone hands-on with the tooling, and he sits in the AI working groups. Reliability and the Berlin metrics alignment through Ruler are probably his too.
- **Including you was handled well.** Saffron emailed to keep you in the loop in your first week. They aligned without you, which is normal, not a sign of anything.

**How to test this on the call:** ask each of them which row they'd personally put their name and a date on. How they answer will tell you more than the sheet does.

**And the lesson for your own rows:** your name, a firm date, no "if agreed". In this sheet, that alone will stand out.

---

**Shashi (04/11 11:57):**
What my row bruh?

**Claude:**
Here are three rows in the sheet's columns, ready to paste. Each has your name on it and a firm date, and none of them hedges.

**Row 1: O4.KR2 (edit the existing row or add one for Sirius)**
- **KR ID:** O4.KR2
- **Team:** Engineering – Sirius
- **What will we do?** Measure median cycle time and median MR merge time for every Sirius team, using the same method as semillas Berlin. Set one improvement target per team, based on the baseline, and review it at the end of Q1 with the team's EM.
- **Why will it move the KR?** Delivers the baseline the KR asks for, and turns it into a team-owned target instead of a report.
- **Need / dependency:** Ruler to confirm how Berlin measures these metrics. Access to Jira/GitLab data.
- **Lead:** Shashi (SEM Sirius), with the Sirius EMs
- **Decision:** Commit
- **By when:** Baseline 31 Jan; targets 15 Feb; review 31 Mar

**Row 2: O3.KR2 (co-own with Marlow)**
- **KR ID:** O3.KR2
- **Team:** Engineering
- **What will we do?** Use the 2027 technical learning budgets (€25k each, Shashi and Marlow) only against role-relevant learning goals agreed between each engineer and their EM. In Q1, at least 20% of engineers complete a goal and share what they applied, as a demo, a pull/merge request or a write-up.
- **Why will it move the KR?** Ties budget spend to learning that has actually been applied, which matches the proposed change to the KR. The budget becomes the means to the goal, not the measure.
- **Need / dependency:** Hub approval of the KR change. Leapsome or a simple tracker for the goals.
- **Lead:** Shashi + Marlow
- **Decision:** Commit (subject to the KR change)
- **By when:** Allocation rules 31 Dec; Q1 check 31 Mar

**Row 3: new, linking onboarding to the hackathon**
- **KR ID:** O4.KR1 (connection: Hackathon / HR / Ops)
- **Team:** Engineering + HR/Ops
- **What will we do?** Propose a Valencia hackathon track: "a new engineer is productive in X minutes". It automates dev environment setup, access requests and the first local build-and-test run. Measure the time from laptop handover to the first successful local test run for Q1 joiners, before and after.
- **Why will it move the KR?** With about 80 hires planned by end of 2027, onboarding friction grows with every joiner. Day-2 readiness becomes a repeatable result instead of depending on each buddy. The track can also take on HR/Ops AI cases.
- **Need / dependency:** Hackathon organisers accept the track. IT to support access automation. AI working groups for any AI parts.
- **Lead:** Shashi
- **Decision:** Commit (track proposal); Idea (target, set after the baseline)
- **By when:** Track proposed by 30 Nov; baseline from January joiners; result at the hackathon

**Before you paste:**
- Row 1 assumes Sirius has more than one team, each with its own EM. Adjust if not.
- In Row 3, X stays open until you have the baseline. Committing to a number now would be the same hedge-then-miss pattern, just in reverse.

---

**Shashi (05/11 12:16):**
row 3, this KR ID already exists on the excel

**Claude:**
Then don't add a second O4.KR1 row. Merge into the existing one. You've been arguing for fewer rows and merged overlaps, so adding a near-duplicate would undercut you. The existing row already tracks access blockers. Your part is the fix for those blockers, so it belongs in the same row.

The catch is that it's their row, so add to it rather than rewriting it. Append to each column:

- **What will we do?** *(add)*: "Fix the most common access and setup blockers through a VLC hackathon track, 'a new engineer is productive in X minutes': automate dev environment setup, access requests and the first local build-and-test run."
- **Why will it move the KR?** *(add)*: "Tracking blockers shows the problem; automating them removes it. With about 80 hires planned by end of 2027, this scales where buddies don't."
- **Need / dependency:** *(add)*: "Hackathon organisers accept the track; AI working groups for any AI parts."
- **Lead:** *(add)*: "Shashi (hackathon track)"
- **By when:** *(add)*: "Track proposed by 30 Nov; result at the hackathon"

If Saffron has already merged the sheet into the main tracker, leave a comment on that row with this text and tag her, rather than editing it after the fact.
