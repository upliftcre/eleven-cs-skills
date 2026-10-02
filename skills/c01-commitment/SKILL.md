---
name: c01-commitment
description: Run the Stability Baseline and the Fail-to-First goal math for a commercial real estate advisor — Chapter 3 of The Eleven C's. Use when someone is setting goals, planning a year, talking about a slow quarter, mentions cash flow or runway, says they are chasing deals they shouldn't, or asks where to start with the framework.
---

# Commitment — Stability Baseline and the Fail-to-First Goal

Two instruments. The first takes ten minutes and is the most important thing in the book. The second takes half an hour and tells them what a good year is actually worth.

Run the baseline first. Always. A goal built on a shaky foundation gets abandoned by March.

## Instrument 1 — The Stability Baseline

Ask exactly this, and make them answer out loud:

> **If your commission checks stopped for six months, which part of your personal life breaks first — cash reserves, health, relationships, or geography?**

Not "would things get tight." Everything gets tight. Force a rank order and a single word.

**Three ways they will dodge, and what to do:**

*"Nothing would break."* Then they would be financially independent and would not be reading a book about commission careers. Everyone has a first failure point. Ask again.

*"Panic."* Panic is not a pillar, it is a symptom. Trace it. Panic about money is cash. Panic about time is health or relationships. Panic about being stuck is geography.

*Answering for the life they intend to have.* If the reserve covers eleven weeks and six months is twenty-six, the answer is cash — regardless of how disciplined they plan to be next year.

**Then capture four things:** the word, today's date, one sentence of evidence, and one shoring action on Monday's calendar *before* deal work. One action, not four.

Why six months: it is the realistic worst case for a working advisor — a financing freeze, a market rotation, a personal disruption. Stress tests use real disasters, not average Tuesdays.

Tell them to re-run it quarterly. Fix cash and health surfaces. Shore health and they finally notice the relationship strain they were too tired to feel.

**If it surfaces something bigger than a calendar entry can hold** — serious debt, real health trouble, a marriage in genuine difficulty — the honest Monday action is making an appointment with someone qualified. Say that plainly. It counts more than anything else on the list.

## Instrument 2 — The Fail-to-First Goal

Commit to a number engineered so that missing it by half still produces the life they wanted.

**Step 1 — territory by property count.** The radius around them containing **1,000 commercial properties**. Dense metro, maybe three submarkets. Rural, maybe four counties. The count is the constant; the map adjusts.

**Step 2 — the four levers.** Get all four as real numbers:

> database size × close rate × average deal size × fee rate = GCI

Worked: `1,000 × 1% × $5M × 2% = 10 closings = $1,000,000`

**Step 3 — commit to 2%, floor at 1%.** Twenty deals is a historic year. Miss by half and they closed ten and made a million. The failure mode is the success — that is the whole trick.

## Where to push

**Deal size is the lever that lies.** If they are carrying $500K habits, run it honestly: ten closings at $500K pays $100K. Hitting a million at that size takes a hundred deals — ten percent of the entire database.

Say the true version, not the sloppy one: **a $5M deal is harder than a $500K deal. It is not ten times harder.** That gap is the whole argument for moving up, and it is why a practice built on small deals has to run at a volume no calendar can hold.

**Check the floor.** If the 1% fallback lands below survival-plus-margin, fix the levers before fixing the goal. The goal is not the problem; one of the four inputs is.

## Deliver

The stability word with its date, evidence, and Monday action. Then the four levers, the arithmetic, the 2% commitment, and the 1% floor with its GCI.

Tell them to write the commitment as one sentence with a three-year date on it, and to re-check the baseline every quarter.

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

### Where it goes: the C1 Commitment tab

- Stability Baseline: "Yes" in exactly one of F23 (Cash reserves), F24 (Health), F25 (Relationships), F26 (Geography). "No" in the other three. G23–G26 Date noted. C16 Date measured.
- C28 One sentence of evidence · C29 The shoring action
- C41 Current value: closings as a percentage of the database (plain number) · C44 Date measured
- Four-lever math: C52 The Thousand (count) · C53 Close rate (plain number, 1 = 1%) · C54 Average deal size (dollars) · C55 Fee rate (plain number, 2 = 2%). C56 and C57 are calculated.
- C59 The number · C61 The milestones · C63 The identity · C65 The decision filter
- G69–G73 Done?: "Yes" or "No" for the five implementation actions, in order
- History log on this tab, rows 82–89. One row each time they re-measure: B Date · C Value, which is closings as a percentage of the database (plain number, 2 = 2%) · E Note. Column D is calculated.
