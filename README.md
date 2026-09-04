# The 90 Day Plan: install in 60 seconds

The part of an Execution Squad that decides how the next 90 days spread. Your offer is
confirmed, your sales script is written, your shell is built. This one asks how many hours a
day you have, reads your lane off your own files, and writes `squad/90-day-plan.md`: one page,
your lane, your weekly count sized to your hours, the hour you run it, and 13 weeks.

## What to bring

Your own files, and the run opens them itself: `squad/business.md`, the shell in `squad/mep/`,
your client folders under `squad/clients/`, `squad/pipeline.md`, and your posts in
`squad/posts/`. Nothing else. If you want your sheet's live rows counted on the floor line,
paste them in with your answer; nobody asks for them, and the plan says `files only` when you
did not.

## Run it

Open Claude Code in your business folder and say: **"/90days"** (or **"Run
/the-90-day-plan."**). Downloaded this folder on its own? Drop the whole thing into
`.claude/skills/`, then quit and reopen Claude Code.

It asks one question: hours a day for the squad, counting the 30 minutes you already block for
people. One number. Then it prints your lane with one line on why, and the whole plan under
it. Say yes and name the hour of your block. Want the other lane? Say the word, and it rewrites
the plan to that lane with the same care.

Stopped halfway, or closed the laptop? Say **"continue the 90 day plan"** in a new window. It
reads what is on disk and picks up at the first thing missing.

## What you get

One page, `squad/90-day-plan.md`: the floor (10 by hand a day, and where the names come
from), your lane's weekly count as one line of arithmetic, the block hour, the 2 gates, and
one table of 13 weeks. Every number in it is your hours, the arithmetic, or a count your
files already hold. It never predicts a result.

## Then

Nothing here until week 13. `/bip` writes the day, `/bip sunday` writes the week, and your
lane's own read fills the Sunday column. At week 13 say **"/90days improve"**: it reads the 90
days that happened, prints what to keep, what to kill and the one thing to change, asks your
hours again, and appends the next 13 weeks under the first.

## Tools

None. No connector, no scrape, no calendar. The `mcp.json.example` in this folder is the
kit's shared config and this run does not use it. It never sends anything, never starts a
sequence, never spends a budget. Your hand does the contact.
