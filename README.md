# The 90 Day Plan: install in 60 seconds

The part of an Execution Squad that decides how the next 90 days spread. Your offer is
confirmed, your sales script is written, your deck is built. This one asks how many hours a
day you have, reads your lane off your own files, and writes `squad/90-day-plan.md`: one page,
your lane, your weekly count sized to your hours, the hour you run it, and 13 weeks that all
run the same cycle. Build on Monday and Tuesday. Sell from Wednesday to Saturday. Decide on
Sunday. When your Google Drive is connected, the same plan lands in a Google Doc and you get
the link.

## What to bring

Your own files, and the run opens them itself: `squad/business.md`, the deck in `squad/mep/`,
your client folders under `squad/clients/`, `squad/pipeline.md`, and your posts in
`squad/posts/`. Nothing else. If you want your sheet's live rows counted on the floor line,
paste them in with your answer; nobody asks for them, and the plan says `files only` when you
did not.

## Run it

Open Claude Code in your business folder and say: **"/90days"** (or **"Run
/the-90-day-plan."**). Downloaded this folder on its own? Drop the whole thing into
`.claude/skills/`, then quit and reopen Claude Code.

It asks one question: hours a day for the squad, including the 30 minutes a day you spend
reaching 10 people by hand. One number. Then it prints your lane with one line on why, and the whole plan under
it. Say yes and name the hour of your block. Want the other lane? Say the word, and it rewrites
the plan to that lane with the same care.

Stopped halfway, or closed the laptop? Say **"continue the 90 day plan"** in a new window. It
reads what is on disk and picks up at the first thing missing.

## What you get

One page, `squad/90-day-plan.md`: the floor (10 by hand a day, and where the names come
from), your lane's weekly count as a small table of arithmetic, the block hour, the 2 gates, and
one table of 13 weeks with 3 working columns: Build (Mon, Tue), Sell (Wed to Sat), Decide (Sun).
Build holds what you make that week. Sell holds the floor and your lane's count. Decide is
blank until Sunday, when you type the one change `/bip sunday` gave you into that week's Decide
cell in `squad/90-day-plan.md`, the file on disk; the Google Doc is a copy to read, not the copy
that is read back. Every number in it
is your hours, the arithmetic, or a count your files already hold. It never predicts a result.

With Google Drive connected (g2), you also get "90-day plan · your name" as a Google Doc, the
tables intact, and its link is saved in your roots file.

## Then

Nothing here until week 13. `/bip` writes the day, `/bip sunday` writes the week and hands you
the one change for the Decide cell. At week 13 say **"/90days improve"**: it reads the 90 days
that happened (your pipeline, your lane's own log, your 13 Decide cells), prints what to keep,
what to kill and the one thing to change, asks your hours again, and appends the next 13 weeks
under the first.

## Tools

Google Drive, optional, for the Doc; without it the plan still lands on disk and the run says
so in one line. No scrape, no calendar. It never sends anything, never posts, never starts a
sequence, never spends a budget. Your hand does the contact.
