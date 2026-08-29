# UPIVOT PRO PHASE B

## Idea Alignment Document

Anushree Khubele

**Product Name:** Cue | Leads that go quiet

**Date:** 22/08/26 | V1

**Cohort:** Upivot Pro Phase B - August' 26

**Presented to:** Upivot Pro cohort + Abhik

---

## SECTION 1 · THE OPPORTUNITY

### Problem / Opportunity Identified:

**A company has a good sales conversation, sends a price, and then the customer goes quiet. Not a no — just silence. Months later, nobody remembers what was discussed. So follow-up is either neglected or delayed, and the deal dies of silence rather than rejection.**

- This is not about finding new customers. It is about leads a company has already found, already spoken to, and then lost track of.

- The segment: B2B services firms of roughly 5–50 people — agencies, consultancies, development studios — with deal sizes between ₹2L and ₹20L, where the person running sales calls is also delivering the work.

- A firm like this might have forty of these sitting in a spreadsheet. Each one is a real conversation with a real, interested person. Nobody has looked at that list in months.

### Why This Could Be Valuable:

A lead who already knows the company — who took the meeting, saw the price, and said they were interested — is the cheapest pipeline a firm will ever have.

The research supports it: across 2.5 million recorded sales conversations, [40 to 60 per cent of qualified deals end in "no decision"](https://www.jolteffect.com/blog/what-is-the-jolt-effect) rather than a loss to a competitor. These are not defeats; they are deals that lost their moment. At ₹2L–₹20L per deal, recovering a single one pays for the tool many times over — which makes the ROI conversation short.

### Why Explore Now

Two things have shifted at once. Cold outreach keeps decaying — average cold email reply rates are now around 3.4 per cent, down from 5.1 per cent in 2024, with one agency reporting its own campaigns falling from 6.8 to 5.8 per cent in a single year ([Instantly 2026 benchmark report](https://instantly.ai/cold-email-benchmark-report-2026)) — which makes already-warm dormant leads relatively more valuable every quarter. At the same time, LLMs became good enough to read a months-old email thread and reconstruct what the customer actually wanted and worried about — the context step that previously made this work manual and therefore undone.

---

## SECTION 2 · THE 5 WHYs — ROOT CAUSE ANALYSIS

| Level | Question | Answer / Insight |
| --- | --- | --- |
| **Why 1** | Why do these companies lose deals? | Because the customer stops replying after the proposal goes out. Not a no — just silence. |
| **Why 2** | Why does the customer stop replying? | Their priorities changed, the budget moved, or the person who liked the idea left. Nobody said no. It just went cold. |
| **Why 3** | Why do priorities change without the company noticing? | There is no proper warm up, followup process. Because once the proposal goes out, attention moves to the next deal. Nobody is assigned to the quiet ones, so nothing is watching them. |
| **Why 4** | Why is there no proper follow-up process? | Lack of tracking is the primary cause. Most CRMs merely log manually entered data or retain basic meeting transcripts. Either way, it just sits there. So the work falls back on people — and in a small team, the person doing sales calls is also delivering the work. They cannot hold forty old deals in their head. |
| **Why 5** | Why doesn't the CRM handle it? | Some CRMs do store the conversation, and a summary can tell you what the customer wanted and what they were worried about. But a CRM is passive. It waits to be opened. It never tells you a quiet deal has become worth reopening. |
| **Why 6 ★** | Why doesn't anyone check it themselves, then? | **★ ROOT CAUSE** — Because checking means continuously watching forty companies for a change on the outside: a budget cycle resetting, hiring restarting, new funding, the champion resurfacing somewhere new. That is continuous outside-world monitoring, which is capacity nobody in a small team has. So re-engagement fires on memory rather than on evidence — and memory almost never lands on the moment something actually changed. |

### Root Cause Statement:

In a firm where the person who sells is also the person who delivers, knowing when a dormant deal is worth reopening requires continuously monitoring the outside world for change — capacity no one has, and something no spreadsheet or CRM is built to provide. So follow-up is triggered by whoever happens to remember, almost never by what actually changed.

### Where this root cause comes from:

At Omdena our deals sat on Monday.com, but the board only ever told us what stage a deal had reached — never what had actually been said in it. So we connected Claude to read the emails and meeting notes and give us one line on each discussion. That fixed the memory problem and made the gap underneath it obvious: even with perfect recall of what was said, nothing told us when a quiet deal had become worth reopening. The context was recoverable. The timing was not.

---

## SECTION 3 · SUPPORTING EVIDENCE

### User Interviews Conducted:

3 interviews with B2B sellers across three deliberately different setups — a solo seller of marketing services, a business development lead at an India market-entry consultancy, and a sales head at a large logistics company. Chosen to test whether the problem holds across company sizes.

| Interviewee | Company / role | Setup | What they do with quiet deals |
| --- | --- | --- | --- |
| **Ashish** | CEO | Leads in a spreadsheet. No CRM. | Followed up twice, then stopped. None have ever come back. |
| **Ketan Arora** | Business Development Manager, Technova | Microsoft Dynamics. Dedicated BD team. | Deliberately does not chase. 1,200 companies a year, 2–3% convert. Only chases existing clients for upsell. |
| **Shrey Shukla** | Manager - International Business ( Key Account Acquisition & Retention ), Delhivery. International logistics. 50–70 direct reports. | Salesforce. Marketing team runs campaigns. | Has a process: CRM tasks scheduled for future dates, plus automated email and WhatsApp reactivation campaigns. |

### Common Themes (patterns across interviews):

- **Deals go quiet at the same point — right after the proposal or quote goes out.** Mentioned by 3/3. Ashish: inbound leads with active interest, quiet the moment the proposal landed. Ketan: lost on price or on "no budget this financial year". Shrey: buyers deferring to the next festive season.

- **Follow-up stops after one or two attempts, or is abandoned on purpose.** Mentioned by 2/3. Ashish tried twice and gave up. Ketan's firm made a deliberate policy of not chasing at all.

- **Nobody has ever paid to fix this.** 3/3. No tool, no agency, no assistant — in any of the three companies.

- **What AI and CRMs have not solved is judgement, not admin.** 2/3. Ashish: "not knowing what deals actually will close" and "understanding behaviours and making deal decisions". Ketan: no AI tool is used for this at all.

- **The CRM stores, it does not prompt.** 2/3. Shrey wants Gmail and calendar integration and finds Salesforce too complex to be useful day to day. Ashish has no CRM — just a spreadsheet.

- **Signals are already how people decide when to follow up — manually.** Ashish: "follow ups using any signals I get from buyer's accounts or a recent activity on social media". Nobody has a system for it. This is the root cause showing up in practice.

### Anchor Quotes (verbatim):

> "Lot of leads went quiet after proposal was sent. They came in inbound with active interest and post proposal went quiet. Last thing was they are going to discuss and get back."
> — Ashish, sold event marketing services

> "I followed up twice and then left it."
> — Ashish, asked what he did about a deal that went quiet

> "Not knowing what deals actually will close."
> — Ashish, on the most annoying part of running the pipeline

> "We don't touch them, to be honest, because it's a very repetitive job."
> — Ketan Arora, Tecnova, on cold leads

> "We only chase the clients that we are already selling to. We chase them for upselling. That's it."
> — Ketan Arora, Tecnova

> "Complicated, too much information, is not making my work easy. Plus it should be integrated with my Gmail, with my calendar, everywhere."
> — Shrey Shukla, Delhivery, on Salesforce

### What the interviews did NOT confirm:

Two of the three do not have this problem in the form the document assumes, and that is worth stating plainly.

- **Delhivery already has a process.** Tasks are scheduled in Salesforce for future dates, and dormant leads are re-engaged through automated email and WhatsApp campaigns — internally called reactivation. At that size, with a marketing team, the problem is already solved.

- **Tecnova has decided the problem is not worth solving.** With 1,200 conversations a year and a 2–3% conversion rate, chasing the other 97% is not economic for them. This is a real objection, not an oversight.

- **Only Ashish matches the problem as written** — the solo seller with no CRM and no team. He also gave the clearest evidence: proposals sent, went quiet, followed up twice, gave up, and none ever came back.

### What this narrows the segment to:

The problem sits in the middle. Large firms automate it. Firms with very low conversion rates opt out of it. It bites hardest where deal values are high enough that each one matters, the seller is one or two people, and there is no marketing team to run campaigns on their behalf — which is the 5–50 person B2B services firm named in Section 1. The next round of interviews needs to concentrate there rather than spread across company sizes.

### Market Signals:

- 40–60% of qualified B2B deals end in "no decision" rather than a loss to a competitor — [The JOLT Effect](https://www.jolteffect.com/blog/what-is-the-jolt-effect), Dixon & McKenna, from 2.5 million recorded sales calls.

- Average cold email reply rate is now around 3.4%, down from 5.1% in 2024 — [Instantly 2026 benchmark report](https://instantly.ai/cold-email-benchmark-report-2026). Leads a firm already has are worth more than they were.

- Competitive gap: sequencers and AI SDRs optimise sending. CRMs store deals but do not watch them. Reactivation at scale is sold as a marketing campaign, not as judgement about individual deals.

### JTBD Statement:

> "When a proposal I sent goes quiet, I want to know whether it is still worth reopening and what to say, so that I stop guessing which deals will close and stop losing revenue I already earned the right to — evidenced by 3 interviews."
