---
name: the-90-day-plan
description: Use this when the offer, the sales script and the shell are ready and the founder asks how to spread. They say "/90days", "build my 90 day plan", "which lane should I run", "pick my lane", "Run /the-90-day-plan", or "continue the 90 day plan" (picking a stopped run back up); at week 13 they say "/90days improve" or "improve my plan". It asks one question, hours a day, reads the lane off their own files, and writes squad/90-day-plan.md, one page: the floor, the lane's weekly count sized to the hours, the block hour, the two gates and thirteen weeks. Improve reads the 90 days that happened and appends the next thirteen. It never sends anything, and the lane is always the founder's word.
---

# The 90 Day Plan

The offer is confirmed, the script is written, the shell is built. What is left is how to spread,
and that question dies by arithmetic, not by a menu. Your work, in one line: **ask hours a day
once, read the lane off the founder's own files, and write `squad/90-day-plan.md`, one page of
weekly counts sized to those hours.** The founder's part is one number, one yes, and the hour of
the block.

This skill runs in ANY founder's repo. Read `.claude/squad-roots.md` first, the instance file
every member-run skill shares; its values win over the `squad/` paths below, which are worked
examples, and a row reading "(none yet)" is an unanswered field rather than an override. Legacy
repos carry `.claude/spine-roots.md`: read that as the fallback. Two rows are this skill's own:
`hours a day`, written at beat 1, and `daily lane` (OUTREACH, CONTENT or ADS), written at the yes.
`ads gate` is a1's row and is only read here. **Never write into the `lane` row.** That row is the
Winning Scrape's and holds a content-research path.

## The run map (where you run, where you STOP)

| Beat | Mode |
|---|---|
| 1 THE HOURS | HUMAN INPUT: one number, and nothing prints before it |
| 2 THE LANE AND THE PLAN | AUTO: the files read, the arithmetic, the plan written and printed whole under the lane line |
| 3 THE YES | **STOP · GATE: the founder's yes and the block hour; a different lane word reprints** |
| 4 THE READ (`improve`) | AUTO off the log and the plan, then HUMAN INPUT: the hours again, the lane's channel number if they have one, the lane word only when the 90 made no money |
| 5 THE SECOND 90 | AUTO: keep, kill, change, the next thirteen rows appended and printed |
| 6 THE YES | **STOP · GATE: the founder's yes and the block hour** |

The beat numbers are the section numbers below. Beats 1 to 3 are `build`, the default, and they
run once. Beats 4 to 6 are `improve`, at week 13 or any Sunday after it. One question, one print,
one gate, in each mode. Never pause an automated beat to ask a small question; never run through a
gate because the answer seems obvious. Between the yes and week 13 this skill does nothing: `/bip`
writes the day, `/bip sunday` writes the week, and the track's read fills the Sunday cell.

**Resuming.** The rule keys on the OUTPUTS, never on what a session remembers: check them in this
order and continue at the first one missing or incomplete.

| Missing or incomplete | Resume at |
|---|---|
| `.claude/squad-roots.md` has no `hours a day` row | beat 1 |
| the row is there and `squad/90-day-plan.md` does not exist | beat 2 |
| the plan exists and its header line carries no `confirmed <date>` stamp | beat 3, the gate only, never a rewrite |
| the plan is confirmed and it is not yet week 13 | nothing here: point at `/bip` for the day and the track's read for Sunday |
| `improve` was asked and the newest `## SECOND 90` block (or THIRD, and so on) has no `confirmed` stamp | beat 6, the gate only |
| `improve` was asked and every block is confirmed | beat 4, a new block |

## The outputs (two files, every run)

1. `squad/90-day-plan.md`: THE file, one page, written to the exact shape in
   `references/plan-template.md`. `improve` appends a block under it and never edits a line above.
2. The `hours a day` and `daily lane` rows in `.claude/squad-roots.md`.

Nothing else gets written.

## 1 · THE HOURS

**First, a self-check.** One file inside THIS skill's folder, next to `SKILL.md`, must open:
`references/plan-template.md`. If it is missing, stop and tell the founder to finish the install:
copy the whole skill folder, `references/` included.

**Then the one question, when `squad/90-day-plan.md` does not exist and the roots file holds no
`hours a day` row.** Nothing prints before it, not the lane, not a file read, not a table:

> Hours a day for the squad, counting the 30 minutes you already block for people?

One number. Write it into `.claude/squad-roots.md` as `| hours a day | N |`. The week said back
("so about N hours a week, weekends included?") is the first line of the next message, never a
second question; a wrong number gets corrected at the gate. A row already there is never re-asked.
The question counts all 7 days, which is why the said-back multiplies by 7; the plan spends those
hours on the 5 block days, and beat 2's arithmetic says so.

## 2 · THE LANE AND THE PLAN

**Read, in this order, asking nothing about any of it.**

| File | What it answers |
|---|---|
| `.claude/squad-roots.md` | `hours a day`; `ads gate` (a1's row: open or shut) |
| `squad/business.md` | who buys: a buyer you can list by name, or one you cannot. Missing: stop on one line, G5 forges it |
| `squad/mep/*/plan.md` | the shell, built for whom |
| `squad/clients/*/notes.md` | who asked for a named thing; THE NEXT STEP with a date |
| `squad/pipeline.md` | who almost paid; money received |
| `squad/posts/` | what the log already shows |
| a paste of the Warm tab's live rows, only when the founder dropped one in | the floor's first names, counted. Never asked for; there is no connector |

**The lane is read, never asked.** ADS reads first when both its halves are there; otherwise the
first two rows decide.

| The files say | The lane | Chris's level rule |
|---|---|---|
| the buyer in `business.md` can be listed by name (an owner, a realtor, a clinic, a job title in a city), and there is something to show: the shell in `squad/mep/`, or a client folder with a dated next step | OUTREACH | proof in hand, outreach |
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
CONTENT    the minutes, and 1 long-form recording a week, published as 1 piece
ADS        $100 a day flat, behind a1's gate; the minutes go on the creative
a week = a day x 5 block days; ad spend is the one that runs all 7
```

The split, so the arithmetic reconciles: the hours question counts all 7 days, the by-hand count
and the minutes run on the 5 block days (a day x 5, and the floor's 50 a week is the same 5), and
ad spend is the one thing that runs every day, so $100 a day is $700 a week. THE BLOCK's five days
and the ADS line carry it in the file; never print a weekly number the block's days do not produce.

Under 1 hour, the floor is the plan and the print says the lane opens the week the hours reach 1.
No sequence count is printed before O2 is live and warmed; its sent number is the founder's to
report, never the plan's to promise.

**Then write `squad/90-day-plan.md` whole**, to `references/plan-template.md`, in its order, and
print ONE message:

- line 1: the week said back
- the lane, one line; why, one line off the files; "say a different word for a different lane"
- the whole plan, as written

Every number in it is the founder's hours, the arithmetic, or a count a file holds. Never a
projected result.

## 3 · THE YES

**STOP.** Ask for two things and nothing more: the yes, and the hour of the block (the plan
proposes 9:00 for the hours a day, 5 days; the founder confirms or names another). A different
lane word reprints the lane line, the count line and the table for that lane, written with the
same care. A changed hour reprints THE BLOCK only. On the yes: stamp the header line
`confirmed <today's date>`, the only record this gate happened and what the resume check reads,
and write `| daily lane | <lane> |` into `.claude/squad-roots.md`.

Then one line back: `/bip` writes the day, `/bip sunday` writes the week, the track's read (o3,
c8 or a4) fills the Sunday cell, and week 13 is `/90days improve`.

## 4 · THE READ (`improve`)

Week 13, or any Sunday after it. **Read first**, asking nothing:

- `squad/posts/`: the Sunday files, the ones whose last line begins `Week`. Their counts are the
  weekly totals: sent by hand, replies, calls, money. Sum only those files. A `Day` file is never
  added on top (that counts the week twice); the `Day` files are counted once, for days posted
  of the 91, never summed. A week with no Sunday file prints `(no Sunday post)`.
- the plan's thirteen rows: each week's Different cell, and the one change the Sunday cell holds.

**Second:** `squad/pipeline.md` (replies by bucket, calls, prices said, money) and
`squad/mep/*/plan.md` (which shell went to whom).

**Then one message, the only ask in this mode:**

- the hours again: "Hours a day for the next 90, counting the 30 minutes for people?"
- the lane's own channel number, if they have it, the one the track's read taught them to pull:
  O3's batch read (OUTREACH), c3's Studio Reach tab (CONTENT), a4's Sunday card (ADS); text or a
  screenshot. A founder who never opened the track has none: say the number is missing in one
  line and run on the log and the pipeline alone. It never blocks.
- only when the 90 made no money: the lane, read again off the files as in beat 2, printed with
  its one line why, and the founder says the word. Money in the 90 keeps the lane and changes
  only how it is run; the founder is not asked.

## 5 · THE SECOND 90

Off the read and the answers, and no other source:

| Line | What goes in it |
|---|---|
| KEEP | what produced a reply, a call or money, by week, off the Sunday totals and the pipeline |
| KILL | what produced nothing 3 weeks running. The ten-percent check, said once: the list is long enough when under 10 percent of it comes back in the next 90; a kill list of 1 item is a plan that was not read |
| CHANGE | the one biggest drop-off in the founder's own funnel, and the one thing that changes there |

| The drop-off | What is broken |
|---|---|
| sent to replies | OUTREACH: the list, or the first line. CONTENT: the packaging, the title and the picture. ADS: the creative |
| replies to calls | the ask: there is not one, or answering it costs too much |
| calls to money | the close: the script, the price line, the follow-up |

Then append to `squad/90-day-plan.md`, under `## SECOND 90 · <today's date>` (THIRD, FOURTH on
later runs), the block the template names: the header line with the new hours and lane, the three
lines above, the count recomputed, the block, and thirteen new rows dated on from the week after
the last row above. Never edit a line above the new heading. Print the block whole.

## 6 · THE YES

**STOP.** The same gate as beat 3: the yes and the block hour. On the yes, stamp the new header
line `confirmed <date>` and rewrite the `hours a day` and `daily lane` rows in the roots file
where they changed.

## Rules

- Every message is scannable: a short header, then bullets or a table. The founder is deciding,
  not studying.
- Never send a message, publish a piece, load a sequence, book a slot or spend a budget on their
  behalf, and never wire anything that would.
- Never price past `squad/business.md`. Nothing here touches a price.
- Never invent a number, a name or a need. Every number printed is one the founder logged, a file
  holds, or the arithmetic produced from the hours they said.
- Never paraphrase a quote. A buyer's line is verbatim, labeled and dated, as the client folder
  holds it.
- Never a menu. One lane, one print, and the founder's word.
- The day is `/bip`'s and the Sunday is `/bip sunday`'s plus the track's read. This skill writes
  nothing on a Sunday before week 13.
