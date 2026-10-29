---
name: meeting-follow-up
description: "Write follow-up emails after meetings: outcome in the first line, only actions actually agreed with owners and dates, promised materials attached and checked, a specific next step, templates for client, sales, interview, partner, internal and networking follow-ups, same-day timing and routing of actions to task lists. Use whenever someone needs to send a follow-up after a meeting, client call, sales call, interview or networking chat, confirm next steps by email or thank someone after a meeting."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/meetings-calendar/meeting-follow-up/
  category: productivity
  subcategory: meetings-calendar
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Meeting Follow-Up Emails

The follow-up email is where a meeting's value is kept or lost. Without it, a client remembers the call differently, a partner waits for a proposal nobody promised to send, and a prospect goes cold while the team debates who should write. A good follow-up is short, sent quickly and confirms three things: what was agreed, who does what by when, and what happens next.

This skill writes follow-up emails after client calls, sales meetings, interviews, partner meetings, internal decisions and networking conversations. It uses the meeting notes, leads with the outcome, lists agreed actions with owners and dates, attaches promised materials, proposes the next step and adapts tone to the relationship. It never adds commitments that were not made.

## Operating principles
1. **Send within one working day.** Same day for clients, prospects and interviews where possible.
2. **Outcome first.** The first line states what was agreed or decided.
3. **Only what was agreed.** No new promises, prices or dates slipped in.
4. **Make the next step easy.** A specific date, a booking link or a clear question.
5. **Short and scannable.** Bullets for actions; links for detail.

## Follow-up types
| Type | Focus |
|---|---|
| Client or project call | Decisions, actions with owners and dates, next meeting |
| Sales or discovery call | Their goals in their words, proposed next step, materials promised |
| Interview (as candidate) | Thanks, one specific point from the conversation, continued interest |
| Interview (as interviewer) | Next steps and timeline for the candidate |
| Partner or supplier | Agreed terms, open questions, who confirms what |
| Internal decision | Decision, reason, owners, what changes and when |
| Networking chat | Thanks, one thing learned, any promised introductions |

## When to use, and when not to
Use it after any meeting where something was agreed, promised or decided, or where a relationship matters.

Don't use it to send full notes to large internal groups (`meeting-notes-actions`) or to negotiate new terms that were not discussed (the Email and Inbox `difficult-emails` skill).

## Inputs
- Meeting notes or transcript (or the user's quick summary).
- Attendees and their roles.
- Materials promised (decks, proposals, links).
- The relationship and tone.
- The next step the user wants.

## Workflow

### Step 1. Pull the outcome
From the notes: what was agreed, decided or learned.

### Step 2. List actions
Only actions agreed in the meeting, each with owner and date; mark unclear ones for the user to confirm before sending.

### Step 3. Gather materials
Links or attachments promised; check they exist and access is set.

### Step 4. Choose the next step
A meeting date, a decision deadline, a document to review or a booking link.

### Step 5. Draft
Subject line with the topic and next step; outcome in the first line; actions in bullets; materials; next step; sign-off.

### Step 6. Check
Nothing promised that was not agreed; names, dates and figures correct; tone matches the relationship.

### Step 7. Track
Add the user's actions to their task list and others' to Waiting for.

## Template
```
Subject: <topic>: summary and next steps

Hi <name>,
Thanks for today. We agreed <outcome in one sentence>.

Next steps
- <owner>: <action> by <date>
- <owner>: <action> by <date>

As promised, here's <material and link>.

<Next step: meeting date, deadline or question>.

Best,
<sign-off>
```

## Examples
**After a sales discovery call**
```
Subject: Onboarding automation: next steps

Hi Lena, thanks for walking me through your onboarding process.
You mentioned new clients wait about five days for account setup,
and you'd like that under one day before the January intake.

As promised: a two-page outline of how teams like yours cut setup
time: [link]. I'll send a tailored proposal by Thursday.
Could we review it together on Monday at 2pm?
```

**After an interview (candidate)**
```
Subject: Thank you: Growth Lead interview

Hi Sam, thank you for your time today. I enjoyed our discussion
about reducing drop-off in the first week; it's the kind of problem
I've spent the last two years on. I'm very interested in the role
and happy to share anything else that would help.
```

## Output format
```
1. Draft follow-up email (subject and body)
2. Actions to confirm before sending
3. Materials to attach and access to check
4. Actions routed to task list and Waiting for
```

## Subject lines
| Weak | Clear |
|---|---|
| Follow up | Pilot agreed: next steps and dates |
| Our call | Onboarding proposal by Thu; review Mon 2pm? |
| Thanks | Thank you: Growth Lead interview |
A subject line that names the topic and the next step makes the email easy to find later.

## Using an AI agent
The agent can draft the follow-up from the transcript or notes as soon as the meeting ends, check that every action in the draft appears in the notes, find promised documents and confirm sharing settings, suggest a next meeting time from the calendar and hold the draft for the user's approval. It never sends on its own.

## Follow-up after no-shows or cancellations
If the other person missed the meeting, send a short, warm note offering two new times or a booking link, without blame. After a second no-show, ask whether the topic is still a priority for them and offer to reconnect later.

## Keeping momentum
If there is no reply within three to five working days, send one brief nudge in the same thread that adds something useful, such as an answer to an open question or a relevant example. Log the follow-up so the next contact builds on it.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Disagreement left open | State the open point neutrally and the next step to resolve it |
| Several stakeholders on the client side | Address the main contact; Cc others who attended |
| Sensitive pricing or legal terms | Confirm only what was agreed; flag for review before sending |
| Meeting went badly | Thank them, acknowledge concerns, propose a concrete next step |
| No clear next step agreed | Propose one with a date and ask if it works |
| Long meeting with many actions | Top three actions in the email; link to full notes |

## Handoffs to related skills
- Notes from the meeting: `meeting-notes-actions`
- Preparation for the next meeting: `meeting-prep-brief`
- Chasing actions others owe: the Email and Inbox `follow-up-tracking` skill
- Clear email structure: the Email and Inbox `email-writing-clarity` skill
- Interview follow-ups in context: the Jobs and Careers skills

## Worked example
After a partner call, an agency director's notes listed four agreed actions, a promised case study and a decision to pilot with one client. The agent drafted a seven-line email within the hour: the pilot agreed in the first line, four actions with owners and dates, the case study link with access checked and a proposed check-in date two weeks later. One action had no owner in the notes, so the agent flagged it; the director confirmed it and sent the email. The partner replied the same day confirming the pilot dates.

## Common mistakes
- Waiting days to send.
- Restating the whole meeting.
- Adding new commitments in writing.
- Forgetting promised materials.
- No clear next step.

## Timing and channel
Send client and prospect follow-ups the same day, ideally within two hours while the conversation is fresh. Internal follow-ups can go in the team channel or shared notes when that is where work happens, with email kept for external contacts and formal records. Interview thank-you notes are best sent the same day or the next morning.

## Self-check before you answer
- Is the outcome in the first line?
- Are all actions agreed, with owners and dates?
- Are promised materials attached and accessible?
- Is the next step specific?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/meetings-calendar/meeting-follow-up/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
