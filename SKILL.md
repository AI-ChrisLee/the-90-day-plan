---
name: the-90-day-plan
description: Use this when the offer, the sales script and the deck are ready and the founder asks how to spread. They say "/90days", "build my 90 day plan", "which lane should I run", "pick my lane", "Run /the-90-day-plan", or "continue the 90 day plan" (picking a stopped run back up); at week 13 they say "/90days improve" or "improve my plan". It asks one question, hours a day, reads the lane off their own files, and writes squad/90-day-plan.md, one page: the floor, the lane's weekly count sized to the hours, the block hour, the 2 gates and 13 weeks, every week the same cycle (Build Monday and Tuesday, Sell Wednesday to Saturday, Decide Sunday). When Google Drive is connected it puts the same plan in a Google Doc and prints the link. Improve reads the 90 days that happened and appends the next 13. It never sends anything, and the lane is always the founder's word.
---

# The 90 Day Plan

The offer is confirmed, the script is written, the deck is built. What is left is how to spread,
and that question dies by arithmetic, not by a menu. Your work, in one line: **ask hours a day
once, read the lane off the founder's own files, and write `squad/90-day-plan.md`, one page of
13 weeks, each one the same cycle, sized to those hours.** The founder's part is one number, one
yes, and the hour of the block.

**The week is the unit.** Build on Monday and Tuesday, Sell from Wednesday to Saturday, Decide on
Sunday. Every row of the plan is that cycle; what changes from week to week is the Build cell and
the one line Sunday writes into Decide. Nothing in the plan runs on a day count, and nothing in
it is a lane stretched flat across 13 weeks.

This skill runs in ANY founder's repo. Read `.claude/squad-roots.md` first, the instance file
every member-run skill shares; its values win over the `squad/` paths below, which are worked
examples, and a row reading "(none yet)" is an unanswered field rather than an override. Legacy
repos carry `.claude/spine-roots.md`: read that as the fallback. Three rows are this skill's own:
`hours a day`, written at beat 1; `daily lane` (OUTREACH, CONTENT or ADS), written at the yes;
`plan doc`, the Google Doc's link, written when one is made. `founder name` is read for the Doc's
title. `ads gate` is a1's row and is only read here. **Never write into the `lane` row.** That row
is the Winning Scrape's and holds a content-research path.

## The run map (where you run, where you STOP)

| Beat | Mode |
|---|---|
| 1 THE HOURS | HUMAN INPUT: one number, and nothing prints before it |
| 2 THE LANE AND THE PLAN | AUTO: the files read, the arithmetic, the plan written and printed whole under the lane line |
| 3 THE YES | **STOP · GATE: the founder's yes and the block hour; a different lane word reprints.** Then AUTO: the stamp, the roots row, and the Google Doc when a Drive connector answers |
| 4 THE READ (`improve`) | AUTO off the pipeline, the track's log, the Decide column and the posts folder, then HUMAN INPUT: the hours again, the lane's channel number only when no log holds it, the lane word only when the 90 made no money |
| 5 THE SECOND 90 | AUTO: keep, kill, change, the next 13 rows appended and printed |
| 6 THE YES | **STOP · GATE: the founder's yes and the block hour.** Then AUTO: the stamp, the roots rows, the Google Doc |

The beat numbers are the section numbers below. Beats 1 to 3 are `build`, the default, and they
run once. Beats 4 to 6 are `improve`, at week 13 or any Sunday after it. One question, one print,
one gate, in each mode. Never pause an automated beat to ask a small question; never run through a
gate because the answer seems obvious. Between the yes and week 13 this skill does nothing: `/bip`
writes the day, `/bip sunday` writes the week, and the founder's hand fills the Decide cell.

**Resuming.** The rule keys on the OUTPUTS, never on what a session remembers: check them in this
order and continue at the first one missing or incomplete.

| Missing or incomplete | Resume at |
|---|---|
| `.claude/squad-roots.md` has no `hours a day` row | beat 1 |
| the row is there and `squad/90-day-plan.md` does not exist | beat 2 |
| the plan exists and its header line carries no `confirmed <date>` stamp | beat 3, the gate only, never a rewrite |
| the plan is confirmed, the roots file has no `plan doc` row, and a Drive connector answers | beat 3's Doc step only: the Doc, the link, the row |
| the plan is confirmed and it is not yet week 13 | nothing here: point at `/bip` for the day and `/bip sunday` for the Decide cell |
| `squad/90-day-plan.md` carries a `## SECOND 90` (or later) block whose header line has no `confirmed` stamp | beat 6, the gate only |
| the newest confirmed block (or the first plan, when there is only one) is at week 13 or past it | on a bare `/90days` or a "continue", say so in one line and offer `/90days improve`; on the word `improve`, beat 4, a new block. Never rewrite a confirmed block |

## The outputs

1. `squad/90-day-plan.md`: THE file, one page, written to the exact shape in
   `references/plan-template.md`. `improve` appends a block under it and never edits a line above.
2. The `hours a day`, `daily lane` and `plan doc` rows in `.claude/squad-roots.md`.
3. Off disk, only when a Drive connector answers: one Google Doc, "90-day plan · <founder name>",
   the plan rendered as HTML. Created at the yes, never before it. `improve` makes a second one,
   dated in its title, because a Doc's body cannot be rewritten.

Nothing else gets written.

## 1 · THE HOURS

**First, a self-check.** One file inside THIS skill's folder, next to `SKILL.md`, must open:
`references/plan-template.md`. If it is missing, stop and tell the founder to finish the install:
copy the whole skill folder, `references/` included.

**Then the one question, when the roots file holds no `hours a day` row.** The resume table
already keeps this beat from firing on a finished run. Nothing prints before the question, not
the lane, not a file read, not a table:

> Hours a day for the squad, including the 30 minutes a day you spend reaching 10 people by hand?

One number. Write it into `.claude/squad-roots.md` as `| hours a day | N |`. The week said back
("so about N hours a week, weekends included?") is the first line of the next message, never a
second question; a wrong number gets corrected at the gate. A row already there is never re-asked.
The question counts all 7 days, which is why the said-back multiplies by 7; the plan spends those
hours on the 6 block days and Sunday's read, and beat 2's arithmetic says so.

## 2 · THE LANE AND THE PLAN

**Read, in this order, asking nothing about any of it.**

| File | What it answers |
|---|---|
| `.claude/squad-roots.md` | `hours a day`; `founder name`; `ads gate` (a1's row: open or shut) |
| `squad/business.md` | who buys: a buyer you can list by name, or one you cannot. Missing: stop on one line, G4 or G5 builds it |
| `squad/mep/*/plan.md` | the deck, built for whom |
| `squad/clients/*/notes.md` | who asked for a named thing; THE NEXT STEP with a date |
| `squad/pipeline.md` | who almost paid; money received |
| a paste of the Warm tab's live rows, only when the founder dropped one in | the floor's first names, counted. Never asked for; this run never goes looking for the sheet, and the plan reads `files only` when nothing was pasted |

**The lane is read, never asked.** ADS reads first when both its halves are there; otherwise the
first 2 rows decide.

| The files say | The lane | Chris's level rule |
|---|---|---|
| the buyer in `business.md` can be listed by name (an owner, a realtor, a clinic, a job title in a city), and there is something to show: the deck in `squad/mep/`, or a client folder with a dated next step | OUTREACH | proof in hand, outreach |
| the buyer cannot be listed by name (a consumer, a creator, a broad audience), or there is nothing to show yet | CONTENT | nothing yet, content |
| money received in `pipeline.md` on the offer as it stands, and the `ads gate` row reads open | ADS | money and a need for speed, ads |

No hours threshold decides the lane: content at 1 hour a day is a lane sized in minutes. A founder
who dreads the lane the files picked says the other word at the gate, and their word is written
with the same care.

**The count is one line of arithmetic.** The floor is the first 30 minutes of every budget and
never shrinks; what is left is the lane's.

```
minutes a day for the lane = hours a day x 60 - 30
OUTREACH   by hand a day = minutes / 3, rounded down to a 5; capped at 50 above the floor, the cap said out loud
           a week = a day x 4 Sell days (Wed to Sat)
CONTENT    the minutes, and 1 recording a week: built Mon and Tue, published as 1 piece on Wed
ADS        $100 a day flat, all 7 days, $700 a week, behind a1's gate; the minutes go on the creative
the floor  10 by hand a day, Monday to Friday, 50 a week: never lowered
```

The split, so the arithmetic reconciles: the hours question counts all 7 days; the block runs 6
days, Monday to Saturday, at the same hour; the floor's 30 minutes open Monday to Friday, which
is where its 50 a week comes from, 10 a day across those 5; the lane's by-hand count runs on the
4 Sell days; ad spend is the one thing that runs every day, so $100 a day is $700 a week. The
plan carries this arithmetic as a small table under THE LANE, never as a code block: the founder
reads the plan in a Google Doc and a black box does not read there. Never print a weekly number
the Sell days do not produce.

Under 1 hour, the floor is the plan and the print says the lane opens the week the hours reach 1.
No sequence count is printed before O2 is live and warmed; its sent number is the founder's to
report, never the plan's to promise.

**What goes in each column.** The lane decides the Build and the Sell cell; the template holds
the exact words per lane.

| Column | What it holds |
|---|---|
| Build (Mon, Tue) | the lane's build for that week. OUTREACH: the week's list cut (o1), then the deck for the one name worth an hour (g7). CONTENT: 1 recording, packaged the way c1 and c2 say, copied off what already wins in the founder's topic. ADS: the creative, one concept. Milestone weeks add their one-line marker here, after the build |
| Sell (Wed to Sat) | the floor's 50 by hand for the week (10 a day, Mon to Fri), on every row, then the lane's weekly count off the arithmetic |
| Decide (Sun) | blank when the plan is written. Every Sunday the founder types the one change into the Decide cell of that week's row in `squad/90-day-plan.md`, the file on disk; the Google Doc is a copy to read, not the copy that is read back. The change comes from `/bip sunday` or the track's read (o3, c6 or a4). This skill never writes the cell before week 13 |

**Then write `squad/90-day-plan.md` whole**, to `references/plan-template.md`, in its order, and
print ONE message:

- line 1: the week said back
- the lane, one line; why, one line off the files; "say a different word for a different lane"
- the whole plan, as written

Every number in it is the founder's hours, the arithmetic, or a count a file holds. Never a
projected result.

## 3 · THE YES

**STOP.** Ask for 2 things and nothing more: the yes, and the hour of the block (the plan
proposes 9:00 for the hours a day, Monday to Saturday; the founder confirms or names another). A
different lane word reprints the lane line, the arithmetic table and the 13 rows for that lane,
written with the same care. A changed hour reprints THE BLOCK only. On the yes: stamp the header
line `confirmed <today's date>`, the only record this gate happened and what the resume check
reads, and write `| daily lane | <lane> |` into `.claude/squad-roots.md`.

**Then the Google Doc, AUTO.** Look for a Drive connector: a tool whose name ends in `create_file`
on a server whose name is a UUID prefix. Detect by that suffix and that shape, never by a server's
own name or description. When one answers:

1. Render the whole plan as HTML: `<h1>90-day plan · <founder name></h1>`, the header line in a
   `<p>`, `<h2>` for THE FLOOR, THE LANE, THE BLOCK and THE GATES, the arithmetic as a small
   `<table>`, the miss clause in a `<p>`, and the 13 weeks as one `<table>` with a header row of
   the 5 columns. No markdown in it, no code block.
2. Call `create_file` with `title` "90-day plan · <founder name>" (the roots file's `founder
   name` row; missing, the founder's first name from the chat, and nothing invented), `textContent`
   the HTML, `contentMimeType` `text/html`. The connector converts it to a Google Doc with the
   headings and the tables intact.
3. Print the link, one line. Write `| plan doc | <link> |` into `.claude/squad-roots.md`.

No connector: one line, "connect Google Drive (g2) and I put it in Docs next time", and carry on.
Never a second line about it, never a retry. Sharing stays as Google made it; the founder flips
it if they want it seen.

Then one line back: `/bip` writes the day; `/bip sunday` writes the week and its closing lines
carry the one change, and you type that line into that week's Decide cell in
`squad/90-day-plan.md`; week 13 is
`/90days improve`.

## 4 · THE READ (`improve`)

Week 13, or any Sunday after it. **Read first**, asking nothing, and only these:

- `squad/pipeline.md`: replies by bucket, the next touch, what went out last, money received.
  This is where money is counted, and nowhere else.
- the track's own log, whichever exists. `squad/outreach-read.md` (o3: the batches, sent and
  replied, both gates) and `squad/ads-log.md` (a4: one row per week) hold the lane's numbers, so
  read every row. `squad/content-log.md` holds only what shipped and when (date, title, link,
  video id) and holds no numbers at all; count its rows for pieces published and read the
  CONTENT numbers off the founder's answer below. A lane whose log does not exist prints
  `(no log on disk)` and runs on the pipeline and the plan alone.
- the newest block's 13 rows: the Decide column, one change per week. Thirteen lines that say
  what the founder changed and when; a blank cell is a week nobody decided, and it is said as
  that.
- `squad/posts/`: the dated `.md` files, one a day, counted once, for days posted of the 91. The
  `.png` beside each is that night's drawing and is never counted. Never opened for numbers. There
  is no Number line in a post and nothing in a post is summed.

**Then one message, the only ask in this mode:**

- the hours again: "Hours a day for the next 90, including the 30 minutes a day for reaching 10
  people by hand?"
- the lane's own channel number, when the lane's log holds no numbers, which CONTENT's never
  does: o3's batch read (OUTREACH), the numbers in YouTube Studio (CONTENT), a4's Sunday card
  (ADS); text or a screenshot. A founder who never opened the track has none either way: say the
  number is missing in one line and run on the pipeline and the Decide column alone. It never
  blocks.
- only when the 90 made no money: the lane, read again off the files as in beat 2, printed with
  its one line why, and the founder says the word. Money in the 90 keeps the lane and changes
  only how it is run; the founder is not asked.

## 5 · THE SECOND 90

Off the read and the answers, and no other source:

| Line | What goes in it |
|---|---|
| KEEP | what produced a reply, a call or money, by week, off the track's log and the pipeline |
| KILL | what produced nothing 3 weeks running. The 10 percent check, said once: if under 10 percent of what you killed comes back in the next 90, you did not kill enough; a kill list of 1 item is a plan that was not read |
| CHANGE | the one biggest drop-off in the founder's own funnel, and the one thing that changes there |

| The drop-off | What is broken |
|---|---|
| sent to replies | OUTREACH: the list, or the first line. CONTENT: the packaging, the title and the picture. ADS: the creative |
| replies to calls | the ask: there is not one, or answering it costs too much |
| calls to money | the close: the script, the price line, the follow-up |

Then append to `squad/90-day-plan.md`, under `## SECOND 90 · <today's date>` (THIRD, FOURTH on
later runs), the block the template names: the header line with the new hours and lane, the three
lines above, the arithmetic recomputed, the block, and 13 new rows dated on from the week after
the last row above. The new rows are numbered 1 to 13 again, under their own block heading; the
block heading is what tells them apart. Never edit a line above the new heading. Print the block
whole.

## 6 · THE YES

**STOP.** The same gate as beat 3: the yes and the block hour. On the yes, stamp the new header
line `confirmed <date>` and rewrite the `hours a day` and `daily lane` rows in the roots file
where they changed. Then the Google Doc as at beat 3, with the whole file (every block) rendered.
The connector cannot rewrite a Doc's body, so a new Doc is made instead, titled "90-day plan ·
<founder name> · <today's date>", and the `plan doc` row is rewritten to the new link. When the
connector carries a title update, rename the previous Doc to "90-day plan · <founder name>
(superseded)" before printing the new link, so an old bookmark says what it is; when it does not,
print one line naming the old Doc as superseded. No connector, the same one line, carry on.

## Rules

- Every message is scannable: a short header, then bullets or a table. The founder is deciding,
  not studying.
- Never send a message, publish a piece, post anywhere, load a sequence, book a slot or spend a
  budget on their behalf, and never wire anything that would. The Google Doc is the one thing
  made off disk, and it is a copy of the plan.
- Never price past `squad/business.md`. Nothing here touches a price.
- Never invent a number, a name or a need. Every number printed is one the founder logged, a file
  holds, or the arithmetic produced from the hours they said.
- Never sum a post. Money is read off `squad/pipeline.md`; the lane's numbers off its own log;
  the dated `.md` files in `squad/posts/` are counted for days posted and nothing else.
- Never paraphrase a quote. A buyer's line is verbatim, labeled and dated, as the client folder
  holds it.
- Never a menu. One lane, one print, and the founder's word.
- Never a fenced block in the plan file. The arithmetic is a table there; the plan is read in a
  Doc.
- The day is `/bip`'s and the Sunday is `/bip sunday`'s plus the track's read. This skill writes
  nothing on a Sunday before week 13, and never writes a Decide cell.
