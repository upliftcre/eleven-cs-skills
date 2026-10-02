---
name: c05-contacts
description: Run the Friday sort and maintain the relationship ledger for a commercial real estate advisor — velocity, touch cadence and source mix from Chapter 7 of The Eleven C's. Use when someone mentions their contacts, database or CRM, asks who to follow up with, says referrals have dried up, wonders where their pipeline went, or wants to log people they met this week.
---

# The Activity Ledger

Relationships are not a vibe. They are a pipeline with physics, and the physics are measurable.

Two jobs here. Adding what they tell you, and running the Friday sort. Both should be fast — this instrument dies the moment it costs more than thirty seconds a day.

## Adding contacts

When they mention people they met or talked to, capture four things per person and nothing else:

**Contact · Source category · Date added · Date of last meaningful touch**

Source is one of: past client, professional referral partner, center of influence, self-generated.

**Qualify before adding.** A contact qualifies if they can send or become business inside the market the advisor claims, and if a real conversation could happen within a month. Someone who took a card to be polite does not qualify. Ledgers die by filling with dead weight until sorting them feels pointless and the whole thing gets abandoned by February.

If they hand you a batch — *"here are the six people I talked to this week"* — format all six and hand it back ready to paste. That is the fastest possible version of this and it is the one they will actually keep doing.

## The Friday sort

Sort by last-touch date. Read down the stale end.

For every contact past thirty days, force a binary: **touched, or consciously demoted.** No third option.

Demotion is allowed. Networks have tiers and pretending otherwise turns the ledger into a guilt machine. The difference is that demotion is a decision and decay is an accident. The ledger's real product is that no relationship in their business ends by accident.

Where a touch is due, draft it. A useful send takes ninety seconds when you know the person's world — an article answering something they asked about in March, a note flagging a lease expiration near their building, a congratulations that references specifics rather than generic warmth.

An email blast is not a touch. It is a touch for the sender and noise for the recipient. If their cadence has been a monthly newsletter, say so: their top contacts may not have heard from them personally in a year.

## The three diagnostics

1. **Velocity** — new qualified contacts added in the last seven days. Met is not added.
2. **Cadence** — of their top twenty, how many had a meaningful touch in the last thirty days?
3. **Source mix** — the percentage split across the four categories. Name the dominant one.

If they cannot answer these, that is the finding. They are running a seven-figure practice without a dashboard.

**Do not invent industry benchmarks.** There is no sourced standard to hand them. Their own first month is the baseline; from then on they compete against their trailing quarter, which is the only comparison that ever mattered.

## What the sort is actually fixing

Say this once, because it is the insight that makes them keep the ledger:

Maintained by memory and mood, they call whoever they thought of — which means whoever contacted *them* recently, whoever is loudest, whoever is most pleasant. The quiet, powerful, busy contacts hear from them least, precisely because those people never call first.

**Feel-based maintenance systematically starves the top of a network and overfeeds the bottom.** The sort does not care who texted last. It cares who has not been touched.

The same pattern shows up wherever recurring relationships are the asset. In service contracting, expired agreements tend to carry *higher* average value than active ones — the accounts that lapse are disproportionately the good ones, because the big ones never make themselves urgent.

## The empty category

Whichever source is thinnest is next week's prospecting assignment. That is diversification made mechanical — they never have to remember to broaden the network, because the ledger nags them toward balance on its own.

## If they call it bureaucratic

They will, in the first month. Listen to what the objection is defending: maintenance-by-feel, the system that starved their best contacts while feeding whoever called last.

The discomfort is not evidence the ledger is wrong. It is evidence they are replacing instinct with instrumentation, and that feels like a demotion for about four weeks.

## The tracker rule

The advisor's workbook is **The Eleven C's Tracker**: `10-eleven-cs-tracker.xlsx`, from the book's System Folder download. It has fourteen tabs: Read Me, Dashboard, C1 to C11, and The Feeder.

When you can reach the file, update it for them. Do these steps every time:

1. **Write only to the cells in the map below.** Every other cell is a label or a calculation. Never put a value in one, even if they ask. A broken formula shows no error. It shows a wrong number that looks right.
2. **Make a backup first.** Copy the file next to itself with today's date in the name, for example `10-eleven-cs-tracker-backup-2026-10-01.xlsx`. If the file is open in Excel, ask them to close it first.
3. **Count the formulas before and after.** If the count changes, or you put a value in a cell that is not in the map, restore the backup and tell them. Saving can turn a few empty-text cells into blank cells. That is harmless, so ignore it.
4. **Use the exact words.** Where the map shows words in quotes, use one of them exactly. That cell has a dropdown. Percentages go in as plain numbers: 2 means 2%. Dates go in as real dates, not text.
5. **In a log, use the next empty row.** Leave no blank rows between entries.
6. **Tell them what changed.** List each cell you wrote and its new value.

Use a tool that keeps formulas, such as openpyxl in Python. Never save the file in a mode that keeps only values.

If they uploaded the file in a chat and you can create files, return the updated copy. Tell them to replace their old file with it.

If you can't reach the file, give them a paste-ready block instead. Write one line per value, in this shape: `Tab › Cell · Label: value`.

If they don't use the tracker, skip all of this. The instrument still runs.

### Where it goes: the C5 Contacts tab

- Ledger, rows 49–68 (twenty rows): B Contact · C Source category, one of "Past client", "Professional referral partner", "Center of influence", "Self-generated" · D Date added · E Last meaningful touch · F Note. If the ledger is full, tell them. Never paste below row 68.
- C12 Contact Velocity (new qualified contacts this week) · C14 "On standard" or "Below standard" · C16 Date measured
- C22 Touch Cadence · C24 "On standard" or "Below standard" · C26 Date measured
- Referral-Source Mix, % of pipeline as plain numbers: C41 Past clients · C42 Professional referral partners · C43 Centers of influence · C44 Self-generated · C34 Date measured. C45 is calculated.
- The Feeder tab, weekly log rows 23–48: B Week ending · C Letters sent · D Emails sent · E Calls made · F Replies entered in the ledger · J Note. G, H and I are calculated.
- History log on this tab, rows 77–84. One row each time they re-measure: B Date · C Value, which is new qualified contacts added that week (count) · E Note. Column D is calculated.
