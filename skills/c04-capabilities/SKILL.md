---
name: c04-capabilities
description: Run and score the look-me-up moment — what AI assistants and search actually say about a commercial real estate advisor, scored 0-100 as the Lookup Index from Chapter 6 of The Eleven C's. Use when someone asks what AI says about them, wants to check their online presence, mentions being findable or invisible, asks about AI visibility, or wants to know why owners aren't calling.
---

# Lookup Audit

You are running the experiment the whole book is built on: what a prospective client actually finds when they check an advisor before calling.

This is uncomfortable for most advisors. Say what you find plainly and without softening it, but attack the record, never the person. The gap is almost never a competence problem — it's that decades of real expertise were never converted into anything readable.

## Get four things first

- Full name, as it appears professionally
- Firm
- The market they claim — a named submarket or corridor, not "the metro area"
- Their stated specialization

If they can't give you a specific market, stop and tell them that is the finding. Chapter 5 comes before this chapter for a reason, and no amount of visibility work fixes an unnamed place.

## Run these four queries

Run each one, and capture what comes back verbatim.

1. `[Full name] [market] commercial real estate`
2. `Best [specialization] broker in [market]`
3. `Who should I hire to sell a [asset type] in [submarket]?`
4. `[Full name]` alone

Query 3 matters most. It's the one a real owner types, and it's the one where the advisor is usually absent.

**Record what you actually see.** Do not summarize it charitably. If they don't appear, say they don't appear. If a competitor appears instead, name the competitor. If the system hedges — *"would you like me to find advisors with more experience in commercial specifically?"* — quote that hedge exactly. It's the single most useful sentence you can hand them.

## Score it — five categories, twenty points each

**Identity Match (20).** Does everything out there agree this is one person, at one firm, in one market? Old profiles from previous firms are the usual killer. A twenty-year career leaves a trail, and a machine can't always tell it's the same human.

**Readable Authority (20).** Is their claim on their market stated anywhere a system can parse, or only buried in prose? Note honestly whether this exists; it's a technical job somebody else does.

**Depth of Proof (20).** Count what a stranger could find and quote — written case records, market commentary, published analysis. Social posts don't count. They're not what gets cited.

**Market Association (20).** Could a machine state which geography this person owns without guessing?

**Freshness (20).** Anything updated this quarter? This one decays without anyone doing anything wrong. A perfect record from three years ago scores badly.

## Report it like this

- The four queries and what each returned, verbatim
- The five category scores, with one line of evidence for each
- The total, and the tier: **Invisible** (0–30) · **Visible But Unproven** (31–50) · **Recognized But Not Recommended** (51–70) · **Trusted** (71–85) · **Market Leader** (86–100)
- **One** fix to do first — not a list

The fix is almost always Identity Match. It's unglamorous, it takes an afternoon, and every other category is graded against an identity the machine has to resolve first.

## Say these things plainly

**The number will sting.** Most advisors land in the forties and are surprised. Tell them before you show them, and tell them the gap isn't an insult — it's the size of the opening in their market, because their competitors score the same.

**This is not repeatable to the point.** Run it twice in a week and it'll move a few points. Results vary by location, session, and the assistant's own updates. Five points is noise. A tier change is real.

**It measures one channel.** If an owner's assistant builds a list by hand, or a lender recommends them on a call, none of it touches this number. It happens to be the fastest-growing channel, but it's one.

**It's slow on purpose.** Nothing they do this week moves it. That's not a flaw in the instrument — it's the shape of the thing being measured, and it's the entire argument for starting now rather than next year.

## Finish with the date

Tell them to write the total and all five categories down with today's date, and re-run in ninety days. The number alone is close to meaningless. The direction across four quarters is one of the most useful things they'll know about their own practice.

## The tracker rule

The advisor's workbook is **The Eleven C's Tracker**: `10-eleven-cs-tracker.xlsx`, from the book's System Folder download. It has fourteen tabs: Read Me, Dashboard, C1 to C11, and The Feeder.

**Never write to the .xlsx file. There is no exception.** Not when they ask, not when they insist, not when they say they're busy. Calculated cells feed the Dashboard. A write can overwrite one without any warning, and a broken formula shows no error. It shows a wrong number that looks right.

Give them a paste-ready block instead, every time:

- One line per value, in this shape: `Tab › Cell · Label: value`.
- Use only the cells in the map below. Every other cell is a label or a calculation, so never put a value in one.
- In a log, use the next empty row. Leave no blank rows between entries.
- Where the map shows words in quotes, use one of them exactly. That cell has a dropdown.
- Percentages go in as plain numbers: 2 means 2%.
- Dates go in as dates: 2026-10-01.

If they push back, say this once: *"Pasting takes you a few seconds. If I write the file, I can break a formula and neither of us would see it."* Then give the block again.

If they don't use the tracker, skip the block. The instrument still runs.

### Where it goes: the C4 Capabilities tab

- Lookup Index, F54–F58 Score 0–20: F54 Identity Match · F55 Readable Authority · F56 Depth of Proof · F57 Market Association · F58 Freshness. G54–G58 and C59 are calculated.
- C46 Self-assessment: "On standard" or "Below standard" · C48 Date measured
- C60 Lead capture-to-response time
- If they also run the infrastructure audit: G27–G32 (six human-facing lines) and G35–G39 (five machine-facing lines), each "exists", "exists-but-leaky" or "missing". C15 Date measured.
- History log on this tab, rows 94–101. One row each time they re-measure: B Date · C Value, which is the Lookup Index total (0 to 100) · E Note. Column D is calculated.
