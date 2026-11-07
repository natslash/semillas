# Chat 3 — Blanket coffee catch-up, Tango feedback and PIP decision, week-1 Friday update
*Original title: "Coffee catch-up notes with Blanket". 05/11/2026 22:41 → 06/11/2026 11:56 (Europe/Madrid). 16 turns. Real names replaced by role codes; tool calls summarised in [brackets]. Jandro's welcome mail was pasted as an attachment in turn 8; it is not reproduced, but its relevant content is in `people/tango/feedback-log.md`.*

---

**Shashi (05/11 22:41):**
Coffee catch up with Blanket
Blanket is my buddy during my onboarding, he is also an EM who reports to me. My notes from his meeting.

He explained about his team structure, how they work, key team members and what he needs me to support him with. Although I need to prod him to tell me more about how to improve his team and how I can support him, he told me few things that are important.

The principal engineer Tango is almost not present and the team feels that if he could do his job right, it would help the team in avoiding lot of back and forth. When the team seeks his help his vague answers and almost avoiding replies have made the team to not to involve him and bypass him, and only keep in the loop as FYI. He seems to be ok with this situation, has not reached out to be involved nor has reacted positively to the team members' structured, documented feedbacks several times.

This complaint has been received by two other teams and things have not changed. Team members feel that it's already may be too late to resolve this situation amicably where if Tango changes his way of working for the better. However they believe in second opportunities.

Among other things, Blanket feels his team might be helped with better quality user stories, for the moment developers themselves proactively work towards getting missing details and make the user stories complete.

As for Blanket himself, he thinks he has this imposter's syndrome and he is still learning as manager and needs support from me in this direction.

**Claude:**
I'll check how you've been recording 1:1s in this project, then file this one the same way.

[memory_read project preferences + em-1 note; project_read `(Gross ledger) 2026-11-03-coffee-catchup.md`; project_write — **mistakenly** appended Blanket's notes to Gross's record, with a confidential Tango section; corrected in turn 7]

I've added these to your 3 Nov coffee catch-up record. I treated Blanket as Gross, since he's the EM reporting to you that you had coffee with. If this was a different meeting or a different person, tell me and I'll move it to its own file. Names are coded. I put Tango in a section marked confidential at the bottom, so it doesn't end up in the copy you share with the EM.

Here's how I'd read it.

**Tango is the most urgent item, but it probably isn't yours to fix alone.** Three teams have complained, gave documented feedback, and nothing changed. That points to a management gap above the teams, not a dispute between a team and an engineer. Before you act, find out three things:
- **Who Tango reports to.** Principal engineers often don't report to the Senior EM.
- **Whether that manager and Jandro know about the complaints.**
- **How Tango's time is actually allocated.** "Almost not present" could be disengagement. It could also be someone who was pulled onto other work and never had his mandate with these teams redefined. Those need very different responses.

Two cheap ways to get evidence without it looking like an investigation:
- **Meet Tango as part of your normal onboarding round.** Ask how he sees his role and how teams use him. Hearing his side first protects the "second chance" the team itself said it believes in.
- **Ask Marlow and Saffron.** The two other complaining teams may well be theirs.

The real cost of waiting isn't Tango himself. It's that teams are already making architecture decisions without principal-level input, and every round of ignored feedback teaches them that raising issues doesn't work. You're new, which gives you a short window to ask naive questions. Use it in the next 2–3 weeks; don't let it become something you also inherited and tolerated.

There's also a link to Comet, who Gross described as "on his way to principal" and underpaid. Comet is probably already doing part of the missing principal work without the title or pay. That is a retention risk, and it's worth bringing up with Gross separately from anything about Tango.

**User stories are part of a problem you've already noted.** Developers filling in missing details, Lantern/Quill struggling to keep up with the Codex productivity gains, and tickets without business value are one problem seen from three sides: refinement upstream is the bottleneck. Right now developers are quietly absorbing the cost, so nobody sees it. Frame it with Lantern/Quill as a capacity mismatch, not a complaint about quality, or it will sound like blame. Ask the EM to track roughly how much time goes into clarifying stories for a sprint or two, so you have a number to work from. It could also become one of your Q1 OKRs.

**On Blanket's imposter syndrome:** reassurance won't help much; a concrete development structure will. Ask him to pick one or two areas he feels weakest in and set a small development slot in your regular 1:1s. Keep in mind that he's onboarding his own boss, which can make it harder for him to admit gaps. That may be part of why you had to prod him. Asking specific questions ("what did you do last time a story came in half-done?") will get more out of him than "how can I support you?"

---

**Shashi (05/11 22:44):**
All three teams are mine and the PE reports to me. I have three more feedbacks from others, hold on this, I'm just giving you notes. not looking for an answer at this time. I'll add notes and then lets work towards the solution

**Claude:**
[project_write — added "Tango reports to me; all three teams are mine; more feedback to come" to the confidential section]

I've updated the record to note that Tango reports to you and all three teams are yours. I'll just file your notes as they come in, and we'll work on a solution once you've added all of the feedback.

---

**Shashi (05/11 22:44):**
Should I add notes here itself or each in different conversations?

**Claude:**
Add the Tango feedback here. When we work on the solution, it helps to have all the accounts in one place so I can compare them: where they agree, where they differ, and what each person actually saw versus what they heard from others. In separate conversations I'd only have each note individually.

One change I'd suggest: I'll keep the Tango feedback in a single confidential file (e.g. `people/tango/feedback-log.md`), with each entry tagged by source and date, instead of spreading it across different people's 1:1 records. That way it's in the project whichever conversation you're in, and it's ready to use when you sit down with Tango.

For unrelated 1:1s (other EMs, peers), start new conversations. They'll still be filed in the same project.

---

**Shashi (05/11 22:57):**
ok then, I spoke to my peer california, who is in Berlin but takes care of complete engineering aspects for my domain, PMP. california mainly talked about PMP overview and then he spoke only about Tango.
He said that, from the get go, Tango didn't impress him, he lacked knowledge about the tech stack of the Berlin teams (he should have been aware of this as PE), he doesn't show ownership qualities, his excuses are unjustifiable and california gave him several tasks over the period of several months and not once has he received a quality deliverable from Tango. california has lost hope and he thinks the situation is at the point of no return.
I asked him if he gave constructive feedback to Tango and the answer was no, reason for this is though california is assigning tasks to Tango, he is not his manager and doesn't have authority. However such long duration without proper feedback might have given Tango the idea that he can somehow keep doing the same things without any repercussions or maybe not even aware that he is producing mediocre results (but this is my guess not california's).

I spoke to Harbour as well, interim manager for the third team (LUNA), she shared the same opinion about Tango, again, she hasn't given feedback to Tango either. She admitted that she should have. Although as PE, Tango should be aware of his responsibilities and should have been proactive.
Several team members of Gross and Blanket have had some conflictive discussions with Tango, they have also given proper documented feedback, Tango accepted it but no follow up discussions happened, nor any changes in his behavior related to work.
Now the situation: Tango is my ex-colleague, he referred me to this job. Jandro in his mail (we have it in one of our previous conversations that this is one of the priority tasks for me), california says this should have been dealt with 2 months ago and we are already late, Jandro couldn't do anything as he had other things on his plate and as he is head of Valencia branch this is understandable.
I am only a week in this company, now I have to decide whether to put Tango in PIP and also to convey him the message. What are my options? how to navigate this situation?

**Claude:**
I'll file these notes in the Tango feedback log, then look up Jandro's expectations before I answer.

[memory_read dkb-application + pe-1; conversation_search for Jandro's mail (not found); project_info]

I mixed two people up earlier. The 3 Nov coffee catch-up (Gross) was a different EM, not Blanket, so I wrongly added Blanket's notes to Gross's record. I'll separate them.

[project_write — restored `(Gross ledger) 2026-11-03-coffee-catchup.md` to its original content]
[project_write — created `(Blanket ledger) 2026-11-coffee-catchup.md`]
[project_write — created `people/tango/feedback-log.md` with Blanket/team, california, Harbour and team-member feedback, context, hypothesis, evidence to collect]

I've fixed the files.
- **Gross's record:** restored to what it was before.
- **Blanket's notes:** now in their own file, coded Blanket.
- **New file for the Tango feedback:** `people/tango/feedback-log.md`. It holds the feedback from Blanket's team, california and Harbour, plus your context: the referral, Jandro's priority and your hypothesis.

I couldn't find Jandro's mail in our past chats, so I've gone with your summary of it.

## What decides this

The feedback is consistent and comes from many sources: three teams, Berlin's engineering lead and an interim EM. That's strong evidence. The problem is that **nobody with authority has ever told Tango he is failing.** california and Harbour admit they never gave feedback. The teams' feedback was peer feedback with no consequences attached. Everyone treats it as a judgement already made, but Tango has never been put on notice. That gap decides which options are fair, and in Spain it also decides which are legally defensible.

## Your options

**1. Formal PIP now**
- **For:** Matches the urgency Jandro and california feel. Shows you act.
- **Against:**
  - It's week one, and you'd be acting entirely on what others told you, with no expectations ever set by his manager.
  - Tango can fairly say "no one ever told me," and he'd be right.
  - Because he referred you, a PIP from you this early looks either personal or like you're proving independence.
  - In Spain, a PIP has no legal force on its own. Dismissal for low performance needs a documented, continued decline against clear expectations. Starting here gives you the weakest paper trail.

**2. Formal expectations talk now, then a PIP only if nothing changes (recommended)**
- **How it works:** One meeting soon, with no ambiguity: "This is a serious performance problem. Here are the specific gaps. Here's what a PE in this role must deliver. You have 4–6 weeks with these deliverables and these dates. If they're not met, we go to a formal PIP, or we discuss whether this role is right for you."
- **For:**
  - It's fair, it's the second chance the teams said they believe in, and it builds the paper trail a later step would need.
  - A dated, written record gives you something concrete to show Jandro, california and the teams.
- **Against:** The formal process starts roughly 6 weeks later. california will think it's slow.
- **Countering that:** Tell Jandro and california the dates upfront, so they see a deadline, not a delay.

**3. Negotiated exit or role change**
- **For:** Often the cleanest result if Tango is checked out, and common in Spain.
- **Against:** Proposing it before he has had any formal feedback looks prejudged.
- **When to use it:** Keep it as the exit if option 2 goes nowhere, or bring it up if Tango signals in the first meeting that he wants out.

Waiting and watching isn't really an option. Jandro has made it your priority, and three teams are watching what the new manager does.

## The referral

Tell Jandro before you speak to Tango: "He's my ex-colleague and referred me. Here's my plan and timeline. I want you to sign off on it, and I'd like HR involved." That protects you from two opposite suspicions: that you'll go easy on him, or that you'll be harsh to prove you won't. It also makes the decision the company's, not a personal one between the two of you. Then watch yourself for both biases.

## Sequence
1. **This week or next:** Tell Jandro about the referral and get his agreement to option 2. Bring in HR, especially on Spanish labour-law requirements. I'm not a lawyer, so check this with them.
2. **In parallel:**
   - Collect california's task history (task, date, expected outcome, what was delivered).
   - Collect the teams' written feedback.
   - Write down what you expect from a PE here, in concrete terms. If no role description exists, part of this failure is the organisation's. Fix it, but don't let it excuse him.
   - Add the three remaining pieces of feedback. Don't let waiting for them delay the conversation with Jandro.
3. **Week 2–3:** The conversation with Tango, with HR's input and the expectations in writing. Name the relationship once at the start: "We know each other. That's why I'm being direct, and it won't change how I assess this." After that, stick to facts. Ask for his view and listen properly. There may be context nobody has mentioned, such as an unclear mandate between Valencia and Berlin, or something personal. That context changes how you support him, not the bar he has to meet.
4. **Weeks 3–8:** Short, documented check-ins. Then you make the decision: back on track, formal PIP, or exit.

When you have the other three pieces of feedback, I can draft the expectations document and an outline for the conversation with Tango.

---

**Shashi (05/11 23:01):**
Here is the mail, let's focus on Tango topic now, later I need your help in weekly status report as well:
*(Jandro's welcome mail pasted; key points: Tango "a potential PIP case in my view"; assess the situation and evidence before concluding; handle carefully, coordinate with relevant managers and HR/Jandro; wants autonomous decisions with reasoning in the Friday update and a clear statement of whether he needs to act; Harbour running a PIP since late Oct, another expected via a Berlin manager (Anchor); Walrus has questioned whether my role is needed.)*

**Claude:**
[project_read + project_write `people/tango/feedback-log.md` — added the mail's content to Context and "how semillas's PIP process works" to evidence]

I've added the relevant parts of Jandro's mail to the Tango log.

## What the mail changes

**Jandro asked for your assessment, not a PIP.** He calls Tango a potential PIP case, then asks you to assess the evidence and reach your own conclusion. That supports the recommended route (a formal expectations talk first, then a PIP if nothing changes). Starting a PIP in week 1 would go further than he asked. A dated, evidence-based plan is exactly what he asked for.

**The decision is yours. Jandro wants to be informed.** He wants you deciding on your own, with your reasoning in the Friday update and a clear line on whether he needs to act. So don't ask him what to do about Tango. Tell him what you've decided and what, if anything, you need from him.

**Harbour already knows the process.** She is running Drift's PIP right now. Ask her how PIPs work at semillas: the template, the usual length, and where HR comes in. You'll learn the process in one conversation, and your plan will line up with how the company already does it.

**Berlin will be watching.** Walrus doubts your role is needed, and california thinks you're already two months late. How you handle Tango will be read as a test of what you add. That's an argument for being decisive and quick on the timeline. It isn't an argument for skipping the step where Tango is formally told. If this later becomes a dismissal, a process with no prior feedback is the version that falls apart.

**Use california as the yardstick.** He's the main user of Tango's work. During the 4–6 week period, ask california to set two or three deliverables with clear acceptance criteria. If Tango delivers, california sees it himself. If he doesn't, the failure comes from the person who has complained most, and nobody can argue the bar was yours alone.

## For tomorrow's Friday update
Jandro wants a written update every Friday, and tomorrow is Friday. This is a draft Tango section. Raise the referral with him in person or on a call too; the written line is so it's on record.

> **Tango (Principal Engineer): decision and next steps (awareness, one ask)**
> - **What I've heard so far:** Blanket's team, california and Harbour all describe the same picture. Tango is rarely involved, california's tasks never came back to an acceptable standard, and the teams now work around him. Several people have given him written feedback with no change. Three more inputs are still to come.
> - **The gap:** Nobody with authority has given him clear expectations or told him what happens if he doesn't meet them. His feedback has all come from peers.
> - **Decision:** Within the next two weeks I'll hold a formal expectations conversation with him. He'll get written deliverables, agreed with california, and a review after 4–6 weeks. If he hasn't met them, it becomes a formal PIP. HR is involved from the start, and I'm aligning the process with Harbour, who is running a PIP now.
> - **Transparency:** Tango is a former colleague and referred me for this role. I'm flagging it so you can challenge my judgement on this case at any point.
> - **What I need from you:** Agreement with this approach, and the HR contact I should work with.

Once the three remaining pieces of feedback are in, I'll draft the written expectations for Tango and an outline for the conversation. Then we can do the full weekly update.

---

**Shashi (05/11 23:08):**
For the Friday update, I need to include everything I did these days:
first 2 days, onboarding, getting access, meeting people (met california, Harbour, Blanket, Gross), took two sessions each from Gross and Blanket in understanding their teams, work and established collaboration rules.
Worked with Harbour about getting to know the team LUNA; next week she'll introduce me to the team and also announce the joining of the manager Guy. I still haven't the access to Confluence, Miro, ChatGPT and other important tools, hindering me in getting better understanding of things I was shared by people I met this week.
Completing mandatory courses in parallel. You have from Jandro's mail I pasted, he expects the status report in a certain way, help summarize everything together

**Claude:**
Here's a draft in the format Jandro asked for: what's going well, issues and risks, blockers, and what needs his attention. Each item that needs him says whether it's an ask or just for awareness.

---

**Subject: Weekly update — Shashi — week 1 (6 Nov)**

Hi Jandro,

**What went well**
- **Onboarding:** Days 1–2 were onboarding and setting up access. I'm doing the mandatory trainings alongside.
- **First conversations:** I met california, Harbour, Blanket and Gross.
- **EMs:** I had two sessions each with Gross and Blanket covering their teams, ways of working and key people. We agreed how we'll work together, and I'll document our 1:1s and share them with each EM.
- **LUNA:** I worked with Harbour to understand the team. Next week she'll introduce me to them and announce that Guy is joining as EM on 1 Dec.
- **OKRs:** [confirm/edit] I reviewed the Engineering OKR draft with Saffron and Marlow and proposed items to own: the delivery metrics baseline and a connection item with HR/Ops.

**Issues and risks**
- **Upstream refinement is a bottleneck.** Codex has increased output, which puts pressure on the PO and BA. Stories reach developers incomplete, and developers fill the gaps themselves. That cost is invisible today. Next step: I'll quantify it with the EMs before proposing a fix with Product. *(For awareness.)*
- **Retention risk.** One of our strongest engineers is heading towards principal but is paid well below that level. I'll bring specifics to our 1:1. *(For awareness.)*
- **Tango (Principal Engineer).** The feedback is consistent: Blanket's team, california and Harbour all describe low engagement, no acceptable deliverables on california's tasks, and teams now working around him. Several people have given him written feedback with no change. However, nobody with authority has ever set clear expectations or consequences for him. Three more people still need to give feedback.
  - **Decision:** Within two weeks I'll hold a formal expectations conversation with him. He'll get written deliverables, agreed with california, and a review after 4–6 weeks. If he doesn't meet them, we move to a formal PIP. I'll involve HR from the start and align the process with Harbour's ongoing PIP.
  - **Transparency:** Tango is a former colleague and referred me for this role. I'm flagging this so you can challenge my judgement on this case at any point.
  - **Ask:** Your agreement on this approach, and the HR contact I should work with.

**Blocked**
- **Tool access.** I still don't have access to Confluence, Miro, ChatGPT and other key tools. Without it I can't go through the material people shared with me this week, which slows down my understanding of the domain.
  - **Ask:** Could you or Compass help speed this up?

**Next week**
- LUNA team introduction with Harbour.
- Coffees with the POs (Valencia and Berlin).
- Set up a regular round table with my EMs, alongside the 1:1s.
- Check in with Anchor on Drift's PIP.
- Finish collecting feedback on Tango and talk to HR.
- Continue the mandatory trainings.

Best,
Shashi

---

Some items here you didn't mention, so check them before you send:
- **The OKR line:** I took it from your OKR work earlier this week. Edit or delete it if you didn't post those proposals.
- **The retention line and "Check in with Anchor" (next week):** these are my additions. Anchor is in because Jandro's mail asked you to coordinate with him.
- **Next week:** a plan built on Jandro's 4-week expectations. Adjust it to what you've actually scheduled.

---

**Shashi (06/11 09:11):**
How should I talk to Tango? I haven't spoken to him since I have joined as I was busy onboarding

**Claude:**
[project_write `people/tango/conversation-plan.md` — first version: two separate conversations]

Since you haven't spoken to him at all yet, you'll need two separate conversations. The first time you sit down with him shouldn't be the one where he's told his work isn't good enough.

**The trade-off**
- **If you go straight to expectations:** you'd be telling someone you haven't spoken to that he's failing, based only on what others said. He's a former colleague who referred you, so that will feel like an ambush, and he'll be defensive from the first minute. You'd also lose the chance to hear his side before you've formed your view, which is what Jandro asked you to do.
- **If the first chat is purely friendly and the hard talk comes a week later:** that feels worse. He'll read the friendly chat as a set-up after the fact.
- **The answer:** a proper first 1:1 where you mostly listen, ending with a clear signal that a structured conversation is coming.

**Conversation 1 (early next week): listen, no verdict**
- **Set it up as a normal 1:1.** Book it at work, in a meeting room. No lunch or coffee out. He's been your direct report for a week without one, so book it Monday.
- **Name the change in your relationship, once:** "We know each other from before. Now I'm your manager, and that changes how we work together."
- **Then ask, and mostly listen:**
  - How does he see the PE role here?
  - What has he delivered in the last few months?
  - How do the teams and california involve him?
  - What feedback has he had, and what did he do with it?
  - What's blocking him?
  - How would he rate his own impact right now?

  His answers will tell you a lot. Notice whether he sees no problem, blames the setup, or admits gaps. There may also be context nobody has mentioned yet.
- **Before you close:** "I'm hearing concerns about how the PE role is working for the teams. I'll come back to you within two weeks with a structured conversation and clear expectations." This is the line that keeps conversation 2 from feeling like an ambush, without giving a verdict early.
- **Avoid:**
  - naming sources or saying "everyone says"
  - promising anything
  - agreeing with any complaints he makes about Berlin or california. If you sympathise even out of politeness, he'll quote it back later.

**Conversation 2 (within about two weeks, prepared with HR)**
1. State the purpose in the first minute.
2. Give the specific facts.
3. Explain the impact on the teams and delivery.
4. Ask for his view.
5. Hand over written deliverables, agreed with california.
6. Set the timeline: 4–6 weeks.
7. State the consequence: if he doesn't meet them, a formal PIP.
8. Say what support you'll offer.
9. Send a written follow-up the same day.

Only hold it once Jandro has agreed, HR is involved, and you have california's task history in hand.

**Until conversation 2,** don't discuss his situation with him informally, even if he brings it up at the coffee machine. As a former colleague, anything you say casually will feel to him like it carries weight.

I've saved both conversation plans in the project with the Tango log, as `people/tango/conversation-plan.md`.

---

**Shashi (06/11 11:56):**
Decision is made, he'll be in pre-PIP for the next 2 weeks and he'll enter PIP officially after that for the next 6 weeks, my conversation is to make him aware of the feedbacks, how he understood them and to tell him that there'll be specific expectations from him and I'm there to support him

**Claude:**
[project_write `people/tango/conversation-plan.md` — rewritten around the decision; this is the version in `project-docs/`]

That's a clear plan. I've updated `people/tango/conversation-plan.md` with it. One gap to close before you talk to him: say exactly what Tango has to do in the two pre-PIP weeks. Otherwise "pre-PIP" is just two weeks of waiting, and he'll reasonably take it as the PIP being already decided. The simplest version: ask him to come back with his own view of the gaps and what he'll deliver. That gives him ownership, and you get real input for the written PIP expectations.

**Before you meet**
- Check with HR or Harbour how semillas handles a pre-PIP. Is it in writing? Is HR copied?
- Prepare 3–4 concrete examples: california's tasks (what was asked, when, what came back), teams working around him, and written feedback that got no follow-up.
- Book a meeting room for 60 minutes, at work.

**Outline**
1. **State the purpose in the first minute.** "I want to talk about serious concerns about how the PE role is working. It's a difficult conversation, and I'd rather be direct."
2. **Mention your history once.** "We know each other from before. That's exactly why I'm being straight with you, and it doesn't change how I assess this."
3. **Give the feedback as themes with examples.** Stick to facts and their impact, not labels. Don't name who said what at team level.
4. **Ask how he sees it.** "How do you see this? Were you aware of it?" Then listen and take notes on what he accepts, what he disputes and what he explains.
5. **Be explicit about the process.** Two weeks pre-PIP, then a formal six-week PIP with written expectations and regular check-ins. Use the word "PIP." Being vague is how this got to this point.
6. **Give him his two-week task:** his own assessment of the gaps, plus the deliverables he commits to.
7. **Offer support.** Weekly check-ins with you, time with california and the teams to agree deliverables, and help with anything that blocks him.
8. **Close.** Summarise what was said and set the date of the next meeting. Send a written summary the same day.

**Likely reactions**
- **"Nobody told me."** "That's fair, and it's why we're talking now. From today, the expectations are clear."
- **He blames the role, Berlin or california.** Accept whatever is valid and fix it in the written expectations. The bar itself doesn't move.
- **He gets emotional.** Pause, and offer to continue another day. The message stays the same.
- **He brings up leaving.** Don't negotiate in the room. "We can talk about that. Let me come back to you after speaking with HR."
- **He appeals to your friendship.** "Because I respect you, I'm being clear instead of vague."
