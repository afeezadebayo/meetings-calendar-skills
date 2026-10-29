---
name: meeting-notes-actions
description: "Turn meeting transcripts, recordings or rough notes into one-page notes: outcome, decisions with reasons, actions with agreed owners and dates, open questions, key points and risks, flags instead of guesses, a decision log, consent and privacy rules, routing to task lists and tracking to done. Use whenever someone needs meeting notes, minutes, a summary of a call or transcript, action items with owners, a decision log or wants actions from meetings tracked until done."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/meetings-calendar/meeting-notes-actions/
  category: productivity
  subcategory: meetings-calendar
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Meeting Notes and Actions

Most meetings fail after they end. People leave with different memories of what was decided, actions have no owner or date, and the same discussion happens again next week. Transcription tools now record everything, but a full transcript is not a set of notes: nobody reads 40 minutes of text to find the three decisions that matter. What helps is a short record of decisions, actions and open questions, shared quickly and tracked until done.

This skill turns meeting recordings, transcripts or rough notes into clear notes: the outcome, decisions with reasons, actions with owners and dates, open questions, key points and risks. It separates facts from opinions, never invents owners or dates, flags anything unclear for confirmation and sends actions into the task system.

## Operating principles
1. **Decisions and actions first.** The top of the notes answers: what did we decide, and who does what by when?
2. **Owners are people, dates are real.** Never assign an owner or date nobody agreed; mark them "to confirm".
3. **Short over complete.** A one-page summary with a link to the transcript beats pages of text.
4. **Neutral and accurate.** Record what was said and agreed, not interpretations.
5. **Share fast.** Within a few hours, while memories are fresh.

## Notes template
```
# <Meeting> | <date> | <attendees>
Outcome: <was the meeting goal reached? one line>

Decisions
- <decision> (why: <short reason>)

Actions
| Action | Owner | Due | Status |
| <verb-led action> | <name> | <date> | Open |

Open questions
- <question> (owner to find out: <name>)

Key points
- <2 to 5 short points worth remembering>

Risks or concerns raised
- <risk> (raised by <name>)

Next meeting: <date or none>
Transcript or recording: <link>
```

## When to use, and when not to
Use it after any meeting with decisions or actions: team meetings, client calls, project meetings, interviews (for the interviewer), workshops and one-to-ones (private notes).

Don't use it to record sensitive HR, legal or medical conversations without consent and the right process, or to share private one-to-one notes widely.

## Inputs
- Transcript, recording summary or rough notes.
- Attendee list and roles.
- The agenda and meeting goal, if any.
- Where actions should go (task list, project tool) and who receives the notes.

## Workflow

### Step 1. Read against the agenda
Match discussion to agenda items; note items not covered.

### Step 2. Find decisions
Look for agreement language ("let's go with", "agreed", "we'll do") and record each with a short reason.

### Step 3. Find actions
Commitments ("I'll", "can you", "by Friday"), with owner and due date only where stated or clearly agreed.

### Step 4. Flag uncertainty
Unassigned actions, vague dates and conflicting statements go to "to confirm" rather than guesses.

### Step 5. Capture key points and risks
Only what someone would need later; skip small talk and repetition.

### Step 6. Write the summary
Use the template; aim for a page or less.

### Step 7. Share and route
Send to attendees and stakeholders; add the user's actions to their task list and others' to Waiting for.

### Step 8. Track to done
Start the next meeting with open actions from these notes.

## Decision record
For important decisions, add a short entry to a decision log:
```
| Date | Decision | Options considered | Reason | Decided by | Review date |
```
This prevents the same debate returning months later.

## Consent and privacy
- Tell attendees when a meeting is recorded or transcribed; follow local law and company policy.
- Keep one-to-one, HR and client-confidential notes private.
- Remove sensitive personal details from notes shared widely.
- Store transcripts according to retention rules.

## Output format
```
1. Notes (template above), one page or less
2. Actions routed: to task list and Waiting for
3. Items to confirm (owners, dates, conflicts)
4. Suggested follow-up email draft (if external)
```

## Writing good actions
| Vague | Clear |
|---|---|
| Look into pricing | Maya: compare three pricing options and share by Thu 17 Oct |
| Follow up with client | Sam: send revised proposal to Acme by Mon 21 Oct |
| Sort the bug | Lee: fix checkout error and confirm in channel by Wed |
Each action starts with a verb, names one owner and has a date.

## Live note-taking
When no transcript exists, a note-taker can use the same template during the meeting: write decisions and actions as they happen, read them back in the last five minutes, and confirm owners and dates before people leave. Reading actions aloud catches most misunderstandings.

## Transcripts and AI tools
Transcription and AI meeting tools are useful as raw material. Treat their summaries as drafts: check that decisions match what people actually agreed, that names are spelled correctly and that nothing sensitive was captured that should not be shared. Keep the transcript linked for anyone who needs detail.

## Notes for people who missed the meeting
Add a three-line summary at the very top: what changed, what was decided and what they need to do. Most people who missed a meeting only need those three lines.

## One-to-one notes
Keep a running private document per person with dated entries: topics discussed, commitments on both sides and follow-ups. Review it before the next one-to-one so conversations build on each other rather than starting over.

## Action tracking across meetings
Keep one running action table for recurring meetings rather than a new list each time. Mark items done with the date, carry open items forward and raise anything open for three meetings in a row: it needs a new owner, a smaller next step or a decision to drop it.

## Distribution list
Send notes to attendees and to anyone named in an action who was not present. For stakeholders who only need the outcome, forward the three-line summary instead of the full notes, so the people who must act see the detail and everyone else stays informed without extra reading.

Keep the notes in one shared place per meeting series.

Check actions weekly.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| No clear decisions | Say so; list options discussed and who decides |
| Poor transcript quality | Flag gaps; ask the user to confirm key points |
| Several languages | Notes in the team's working language; quotes kept in original if important |
| Disagreement unresolved | Record the positions neutrally and the next step to resolve it |
| Very long meeting | Section by agenda item; summary at the top |
| Client meeting | Share an external version; keep internal notes separate |

## Handoffs to related skills
- Agendas: `meeting-agenda`
- External follow-up emails: `meeting-follow-up`
- Decision meetings: `decision-meetings`
- Tracking actions: the Planning and Task Management `task-capture-clarify` skill
- Chasing owed actions: the Email and Inbox `follow-up-tracking` skill

## Worked example
A 45-minute project meeting produced a 6,000-word transcript. The agent's notes: outcome partly reached (launch date agreed, pricing deferred); two decisions with reasons; six actions, four with owners and dates and two marked "owner to confirm"; one open question on pricing assigned to finance; a risk about integration testing raised by the engineering lead. The notes went out within an hour, the user's three actions went to their task list, and the next meeting opened with the action table. The deferred pricing decision was resolved in the next meeting instead of drifting.

## Common mistakes
- Sharing transcripts instead of notes.
- Actions without owners or dates.
- Inventing owners to make notes look complete.
- Sending notes days later.
- Never checking actions at the next meeting.

## Self-check before you answer
- Are decisions and actions at the top?
- Does every action have an agreed owner and date, or a "to confirm" flag?
- Is the summary a page or less?
- Were privacy and consent respected?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/meetings-calendar/meeting-notes-actions/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
