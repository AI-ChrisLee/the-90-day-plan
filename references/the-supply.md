# What the lane runs on (the 90 Day Plan: THE SUPPLY, and every Sunday's restock)

A lane with nothing to run on stops on day two. The warm list is spent by now and never reopens,
so the lane gets its own supply before the first morning, restocked weekly after by the same
rules and to the same stop. Only approved supply reaches a morning.

## OUTREACH

Build `squad/cold-list.md`. One row per company, these labels in this order, and a blank stays
blank rather than being guessed.

| Label | What goes in it |
|---|---|
| `WHO` | The named human. No row without one |
| `COMPANY` | The business |
| `WHERE` | The working email or the profile they can be reached at |
| `SOURCE` | The named source below |
| `SEGMENT` | The one line every row in this pull shares |
| `RESEARCH` | The personal line, on the hand-touched ten only |
| `STATUS` | LISTED · TOUCHED · REPLIED · DEAD, one way only |
| `TOUCHED` | The date, written by the founder after the morning |
| `NEXT TOUCH` | The date the next touch is due, written by you when the row is touched |

The warm list's WARMTH, KNOWS, RECENT and NEED do not transfer, because nothing about a stranger
off a map search can be graded against a working line. **`STATUS` and `TOUCHED` here are where a
cold row gets marked.** The Outreach Sheet's Warm tab is warm work only, and `squad/pipeline.md`
gets a row the day a reply lands, not before.

**A cold row that never answers still owes two more touches, and `NEXT TOUCH` is what carries
them.** Same spacing Warm Extract used, day 4 after the first touch and day 9 after that, since
a founder should not have to hold two different rhythms in their head. A row that has had all
three and said nothing goes DEAD, and `NEXT TOUCH` goes blank. Without that date the morning has
nothing to print under follow-ups, and a list works itself once and then rots.

1. **The source, named.** The founder says where their buyer is already listed: a directory, a map
   search, a job board, a conference roster, the followers of one account. One source at a time,
   written into the file by name, so a dead week can be traced back to it.
2. **Pull it, and read the `research mode` row in `.claude/squad-roots.md` before you decide
   how.** That row is the Winning Offer's own record of whether this laptop is wired, and it is
   the only thing that answers the question. Wired means Apify is callable, and Apify is what
   reaches a directory, a map search or the followers of one account: check the actor's input
   schema before the run, then pull. Unwired means the founder does the pull by hand off the named
   source, or takes the export the source offers, and hands you the file; same cap, same cleaning,
   and nothing here installs a tool to get around it. Either way, where the source hands over its
   own export (a job board CSV, a conference roster), that file is the pull and nothing gets
   scraped. **Cap the first pull at 200 rows.** Two hundred rows is about a week of the ninety,
   because the sequence touches each row roughly three times, and about four weeks of the
   hand-sent ten. A small pull that comes back wrong costs an hour instead of a day. Then clean
   it: drop duplicates, anything with no human name, no company or no working address, and every
   name already in `squad/pipeline.md`.
3. **Research the ten.** Only the ten the founder touches by hand, one line each: what they do now,
   and the one thing you could fix. The rest carry the segment's line, not a personal one.
4. **Draft.** One message per hand-touched row, in their voice off the offer document. The sequence
   copy for the ninety is drafted here and handed to the outreach track's cold-email skill, which
   owns the sending. Nothing is sent here and nothing is loaded into any tool.

## CONTENT

The week's supply is one topic and one recording slot, and nothing more.

1. **The topic, one line.** Taken off `squad/warm-notes.md`: the question their buyers actually
   asked, in the words they used. One topic, not a calendar.
2. **The slot.** The hour this week the founder records it, named in their calendar.
3. **The week's pieces.** What that one recording gets cut into across the seven days, listed.
4. **The ten, by name, because the floor still asks for them.** This lane's hundred is minutes, so
   the ten hand-sent reach-outs are not inside it and they need their own supply, named and
   approved here exactly like a cold list. One source at a time, and it is people rather than a
   strategy: whoever replied to a published piece, whoever commented or asked a real question, and
   the warm rows marked NOT NOW, each carrying the date its re-touch is due. **Until a piece has
   actually shipped there is nobody on the first two, so the ten come off the NOT NOW pile,**
   worked oldest date first, and say that plainly rather than asking a founder with no published
   work to find ten strangers at eight in the morning.

The day the winning scrape is installed the topic stops being yours: it picks the week off what is
winning with their buyers right now, and you print what it decided. The ten stay here.

## ADS

Nothing gets built here. The supply is the creative pipeline the ads track builds and approves
(a3), and the money card the ads track wrote at `squad/ads-money-card.md` (a2). The week's block
carries the pointer to both, and the founder reads only the week's ten names.

## The stop, and where the approved supply is written

**One stop, and it has a different shape in each lane.** In OUTREACH the founder reads the ten
names and the message that goes with each, cuts the wrong ones, and says the list is theirs. In
CONTENT they say the topic back in one sentence, name the recording hour, and read the week's ten
names the same way the outreach founder reads theirs. In ADS they read the week's ten names and
the pointer.

Write the approved supply into `squad/90-day-plan.md` under that week's `## WEEK N` block, in the
shape `references/plan-template.md` names.
