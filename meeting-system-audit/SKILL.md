---
name: meeting-system-audit
description: "Audit a team's meeting system: an inventory of every recurring meeting with purpose, people-hours, decisions, ratings and overlaps, attendee surveys, keep, merge, shorten, async or end decisions, a lean core meeting set with written updates and meeting-free time, rules for new meetings and a measured pilot. Use whenever a team or company has too many meetings, slow decisions, managers stuck in calls, overlapping syncs, after a reorganisation or wants a meeting reset."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/meetings-calendar/meeting-system-audit/
  category: productivity
  subcategory: meetings-calendar
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-13"
---

# Meeting System Audit

In many organisations, meetings grow by accident. Each team adds a stand-up, a weekly sync, a monthly review and a few cross-team check-ins, and nobody looks at the whole. The result is overlapping meetings that discuss the same topics, managers who spend most of the week in calls, and decisions that still wait for "the right meeting". Some companies have reset this deliberately: Shopify, for example, cleared recurring meetings with more than two people from calendars in 2023 and asked teams to add back only what they needed. [Reported, Shopify 2023]

This skill audits the meeting system of a team or small organisation: every recurring meeting, its purpose, attendees, cost in people-hours, overlap with other meetings, decisions produced and satisfaction; then designs a leaner set of meetings with clear roles, written alternatives, meeting-free time and rules for adding new meetings. Individual calendars are covered by `calendar-audit`; this skill looks at the system.

## Operating principles
1. **Look at the whole system.** Overlaps and gaps only show when all meetings are listed together.
2. **Count the cost.** Length times attendees times frequency gives the real price of a meeting.
3. **Every meeting has one job.** Decide, solve, align, build relationships or learn; status belongs in writing.
4. **Ask the people in the room.** Short surveys reveal which meetings help and which do not.
5. **Reset, then add back.** It is easier to justify a meeting from zero than to defend each existing one.

## Meeting inventory
```
| Meeting | Owner | Purpose | Frequency | Length | Attendees | People-hours/month | Decisions last month | Rating (1-5) | Overlaps with |
| Weekly team sync | Head of ops | Status | Weekly | 60 | 12 | 52 | 1 | 2.4 | Monday stand-up |
```

## When to use, and when not to
Use it when a team says it has too many meetings, managers have no time for their teams, decisions are slow, after a reorganisation or growth spurt, or at the start of a year.

Don't use it for one person's calendar (`calendar-audit`) or a single meeting's agenda (`meeting-agenda`).

## Inputs
- List of recurring meetings (or calendar access for the team).
- Team structure and roles.
- Goals for the quarter.
- Optional: a short survey of attendees.

## Workflow

### Step 1. Build the inventory
List every recurring meeting with owner, purpose, frequency, length and attendees.

### Step 2. Calculate the cost
People-hours per month for each meeting and the total; express it as a share of working time.

### Step 3. Survey attendees
Three questions per meeting: Is it useful (1 to 5)? Could it be shorter or written? What would you change?

### Step 4. Map purpose and overlap
Tag each meeting by job (decide, solve, align, relationships, learning, status) and mark meetings covering the same topics or people.

### Step 5. Decide
Keep, merge, shorten, reduce frequency, replace with a written update, or end.

### Step 6. Design the new system
A small set of core meetings, each with an owner, purpose, agenda template and attendees; written updates for status; meeting-free blocks.

### Step 7. Set rules
What a new recurring meeting needs before it is created: purpose, owner, agenda, end date or review date.

### Step 8. Pilot and review
Run the new system for four to six weeks; measure hours, decision speed and satisfaction; adjust.

## Typical core meeting system for a team
| Meeting | Job | Frequency | Length |
|---|---|---|---|
| Weekly priorities | Align and decide | Weekly | 30 min |
| One-to-ones | Relationships, coaching | Weekly or fortnightly | 25 to 30 min |
| Decision meeting (as needed) | Decide | Ad hoc | 25 to 50 min |
| Monthly review | Learn and adjust | Monthly | 50 min |
| Written weekly update | Status | Weekly | Async |

## Meeting-free time
Agree team-wide focus blocks, such as two mornings a week or one meeting-free day, with exceptions only for customers and incidents. Put them in shared calendars and review monthly.

## Output format
```
1. Inventory with cost and ratings
2. Total meeting load (people-hours, share of time)
3. Overlaps and gaps
4. Decision for each meeting
5. New meeting system (core meetings, written updates, focus time)
6. Rules for new meetings
7. Pilot plan and measures
8. Messages announcing the changes
```

## Survey questions
For each recurring meeting, ask attendees:
1. How useful is this meeting for your work? (1 to 5)
2. Could it be shorter, less frequent or replaced by a written update?
3. What one change would make it better?
For the system overall, ask: How many hours a week do you spend in meetings? Which meeting would you miss most? Which would you not miss at all? Keep the survey to five minutes.

## Cost calculation
People-hours per month = length in hours x attendees x meetings per month. A weekly 60-minute meeting with 12 people costs about 52 people-hours a month. Showing the cost in hours, not money, is usually enough to change behaviour, but teams can multiply by an average hourly cost if leadership asks.

## Rules for new recurring meetings
- A named owner and a single purpose.
- An agenda template and a list of required attendees.
- A written alternative considered first.
- A review date within three months, after which the meeting ends unless renewed.
- 25 or 50-minute default lengths.

## Using an AI agent
The agent can build the inventory from shared calendars, calculate costs, draft and analyse the survey, tag purposes and overlaps, propose decisions and write the announcement, while the leadership team makes the final calls.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Leaders protect their own meetings | Include leadership meetings in the audit; lead by example |
| Distributed team across time zones | Fewer, rotating live meetings; strong written updates |
| Customer-facing or support teams | Keep short daily coordination; cut internal status meetings |
| Highly regulated work | Keep required governance meetings; tighten agendas |
| Low survey response | Use attendance and decision data; ask owners directly |

## Handoffs to related skills
- Individual calendars: `calendar-audit`
- Agendas for the core meetings: `meeting-agenda`
- Decision meetings: `decision-meetings`
- Notes and actions: `meeting-notes-actions`
- Written updates: the Communication and Presentations skills

## Worked example
A 40-person company listed 31 recurring meetings costing about 1,100 people-hours a month, roughly a sixth of working time. Surveys rated nine meetings below 2.5, and four pairs overlapped. The new system merged two leadership meetings, replaced three status meetings with a written Friday update, shortened six meetings to 25 minutes, ended five and introduced meeting-free Tuesday and Thursday mornings. After six weeks, meeting time fell by about 40%, survey ratings rose and the leadership team reported faster decisions because decision meetings now had pre-reads.

## Announcing the changes
Explain why (time back for focused work and faster decisions), what changes and when, how to raise a concern, and when the pilot will be reviewed. Invite people to suggest meetings to add back if something is missing after two weeks.

## Measures
| Measure | Baseline | After pilot |
|---|---|---|
| Meeting people-hours a month | | |
| Share of working time in meetings | | |
| Average meeting rating | | |
| Days from issue raised to decision | | |
| Team focus hours a week | | |

## Common mistakes
- Auditing only one person's calendar.
- Cutting meetings without a written alternative.
- Ignoring leadership meetings.
- No rules, so meetings grow back.
- No measurement, so the benefit is invisible.

## Self-check before you answer
- Is every recurring meeting listed with cost and purpose?
- Were attendees asked?
- Does the new system replace status meetings with written updates?
- Are there rules for new meetings and a pilot review?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/meetings-calendar/meeting-system-audit/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
