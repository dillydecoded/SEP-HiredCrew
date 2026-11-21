# Hired Crew — HiredCrew

> HiredCrew is an AI interview assistant for NTU and other Singapore university students: it finds interviews in their Gmail, schedules them against their calendar, prepares them for each round, runs a spoken mock interview and drafts every email the process needs, and it sends nothing without the student's approval.

## 1. Snapshot

| Field | Answer |
|---|---|
| Status | Active — last updated 21 Nov 2026 |
| Idea conceived · team formed · joined SEP | Jun 2026 · Jun 2026 · Sep 2026 |
| Stage | Prototype |
| Company incorporated? | No |
| Mentor / supervisor | None yet |
| Our 3 metrics | 1. Students using HiredCrew (signed in at least once, cumulative) 2. Mock interviews completed (cumulative) 3. Conversations with students about their job search (cumulative) |
| Latest numbers | 1. 0 (first testers still being finalised) 2. Not counted yet 3. About 10 (as of Nov 2026) |
| Latest video | [Update 1 – Nov 2026](https://youtu.be/lgN6WD32cTI) |
| Website / demo | https://hiredcrewsg.vercel.app |

## 2. Team

| Name | Role | Programme & expected graduation | Hours per week on venture | Joined | GitHub |
|---|---|---|---|---|---|
| Dilon | Team Lead (product, design and engineering) | Computer Engineering, May 2027 | About 25 | Jun 2026 | @dillydecoded |

**Team changes:** None

## 3. Problem, solution and SEP milestones

**Problem and customer:** University students in Singapore applying for internships and graduate roles run several hiring processes at once, each with two to six rounds (online assessments, recruiter calls, technical and behavioural interviews). The work around each round is scattered across Gmail, calendars and notes: spotting the invitation, offering times, researching the company and the round, practising, replying on time and following up. A missed reply or an unprepared round can cost the offer. In our interviews with students, they told us they would like one place that tracks every round from their inbox and tells them what to do next. First segment: NTU students, then other Singapore universities.

**Solution:** HiredCrew reads the student's inbox (with their permission) and turns each interview email into one tracked process: what stage it is at, what the recruiter is waiting for, and the next step. For each round it writes a prep document researched for that company and stage, suggests people to network with, runs a voice mock interview with an AI interviewer and gives a feedback scorecard, and drafts every email (replies to recruiters, follow-ups, reschedules, offer replies, withdrawals). It also keeps a story bank for behavioural questions, can record an interview's notes and pull out the next steps, and works on a phone as an installable app. Compared with the alternatives: a general chatbot does not know the student's inbox, rounds or deadlines; career services cannot follow every round of every student; and doing nothing means missed replies and generic preparation.

**SEP milestones** (set at the start; update the Status column, don't rewrite the targets — add a new row if a pivot changes them):

| # | Milestone | Target date | Status | Evidence |
|---|---|---|---|---|
| 1 | Working product live for NTU testers, with real Gmail, Google Calendar and daily reminders | Oct 2026 | Done | Live since 14 Oct 2026: https://hiredcrewsg.vercel.app |
| 2 | Improvements from the first round of feedback built and independently checked (115 requirements) | Nov 2026 | On track (113 of 115 checked in the running app) | This video |
| 3 | Improvements released to the live site and checked on real phones and a real Gmail account | Dec 2026 | Not started | None |
| 4 | Google verification path decided and started (Gmail reading needs Google's restricted-scope review and a yearly security assessment; the alternative is paste-only detection) | Jan 2027 | Not started | None |
| 5 | 50 NTU students using HiredCrew through an application season | Mar 2027 | Not started | None |

## 4. Updates (newest first)

### Update 1 — Nov 2026
**Video:** [Hired Crew – SEP Update 1](https://youtu.be/lgN6WD32cTI) (2:55)

| Metric | Last update | Now |
|---|---|---|
| Students using HiredCrew (cumulative) | — | 0 (first testers still being finalised) |
| Mock interviews completed (cumulative) | — | Not counted yet |
| Conversations with students (cumulative) | — | About 10 |
| Customer / user conversations this period | — | About 10 |

- **Goals we set last time → result:** First update; no goals were set before.
- **Highlights:**
  1. Won 1st place at the LinkedIn Trailblazer Hackathon (Jul 2026).
  2. Launched on 14 Oct 2026 with real Gmail and Google Calendar: interviews are found in the inbox, tracked by stage, and reminders go out daily.
  3. Rebuilt around the first round of feedback: a profile filled in from the student's resume before anything else, a 3-month inbox look-back for interviews already under way, a Needs you list that only shows what is waiting on the student, an archive for processes older than 6 months, interview recording with next steps pulled out, and an admin dashboard. Every change is checked by automated tests (about 7,000 unit tests and 2,100 browser tests on phone and desktop) and by independent reviews before it ships.
- **What went wrong or didn't work:**
  1. Reading Gmail counts as a restricted scope for Google, so a public launch needs Google's review plus a yearly security assessment. Until then only up to 100 listed testers can sign in, and Google ends their access every 7 days.
  2. OpenAI is retiring both audio models the mock interview uses (January and February 2027), so the spoken answers had to move to a newer model.
  3. Our quality bar slowed the release: each independent review found more small issues, so the live site is still on the October version while the improvements are finished.
- **Changes or pivots:** None
- **Who did what:** Dilon: product, design, engineering and testing.
- **What we need from SEP:** None
- **Goals for the next 2 months:** 1. Release the improvements to the live site and pass the checks on real phones and a real Gmail account. 2. Decide the Google verification path and start it. 3. Get the first 20 NTU students using HiredCrew and hold 10 feedback conversations.

## 5. Funding, awards and materials

| Date | Type (grant / competition / investment / revenue / award / press / IP / deck / report) | Description | Amount (SGD) or link |
|---|---|---|---|
| Jul 2026 | competition | 1st place, LinkedIn Trailblazer Hackathon | None |
