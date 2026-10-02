---
name: c07-conversations
description: Log meaningful business conversations by source, compute the inbound ratio, and run the pre-flight check before any outbound campaign — Chapter 9 of The Eleven C's. Use when an advisor is planning a mailer or outreach, mentions prospecting or cold calling, asks whether marketing is working, or wants to log conversations from the week.
---

# The Conversation Ledger

The unit of this business is a meaningful business conversation with someone who could become a client. Not a dial. Not a touch. Not a LinkedIn view.

Every car dealer in America already understands this. They do not count people who walked the lot — traffic is weather, and no dealer makes a decision off it. They count **test drives**, because a person behind the wheel and a person wandering the lot are different events that close at different rates.

Accountability calls in commercial real estate count walk-ups and call them test drives.

## Logging

Four fields per conversation, and nothing else:

**Date · Who · Source · Became a client?**

Source is one of: outbound-touched, inbound-lookup, referral, walk-in.

Only log actual business discussions. If they hand you a week's worth, format it and hand it back ready to paste.

## The pre-flight check — run this before any campaign

Before postage gets spent, run the lookup the campaign will trigger.

Search their name, their market, their category — in an AI assistant and in plain search. Read what a prospect would find in the ten minutes after the touch lands.

Then ask three questions:

1. Does the record support the claim the mailer makes?
2. Is it current?
3. Would it convert *them*?

**If the answer is no, fix the record before spending the postage.** A campaign launched into an empty record is manufacturing losses, and the response-rate data will say the campaign failed when the campaign actually worked and the record lost the deal afterward.

This is the mechanism worth explaining once: outbound creates the moment; the record decides whether the moment converts. Two advisors mail the same list the same month and get opposite years, and neither learns why, because the deciding ten minutes happen where nobody can see them.

## The four numbers

- **Conversations this week** — the raw count
- **Conversations, last ninety days**
- **Inbound ratio** — inbound-lookup ÷ total, over ninety days
- **Conversation-to-client rate** — of resolved conversations, what fraction signed

The inbound ratio is the system's report card. Year one it reads near zero and that is expected, not failure — inbound is a dividend on credibility deposited in earlier quarters. Year three it should be visibly climbing. Flat past year two means the record is not compounding, and the fix is upstream in Criteria and Credibility, not in the outbound number.

## What not to say

**Do not tell them to stop prospecting.** Outbound is alive. Mailers work, pop-ins work, community presence works. The look-me-up moment does not replace outbound — it determines whether outbound converts.

They never stop prospecting. They stop *depending* on it. An advisor who abandons outbound when inbound matures has rebuilt the same single-source concentration risk in a prettier costume.

## The maturity arc

Ask where they are, because the marching orders differ:

**Year one** — outbound carries the pipeline. The record is thin, not because they are bad but because banking takes quarters. Hold a defined weekly number regardless of mood.

**Years two and three** — the ratio shifts. Some conversations start arriving that no touch produced. Track them. The first time a six-figure owner says *"you came up when I looked"* the abstract chapters become a balance sheet.

**Year three onward** — outbound goes surgical. Fewer touches, higher stakes, better hit rate, because every swing now happens with the record behind it.

The mix changes forever. The discipline does not.

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

### Where it goes: the C7 Conversations tab

- Source log, rows 30–37, one row per week: B Week ending · C outbound-touched · D inbound-lookup · E referral · F walk-in. G is calculated.
- C14 Conversations self-assessment: "On standard" or "Below standard" · C16 Date measured
- C21 This month's inbound ratio, for this month only, not ninety days (plain number, 35 = 35%) · C23 Ratio self-assessment: "On standard" or "Below standard" · C25 Date measured
- Pre-flight, G41–G43 Pass?: "Yes" or "No". G41 Does the record support the claim? · G42 Is it current? · G43 Would it convert you? · C44 Date the pre-flight last ran
- History log on this tab, rows 58–65. One row each time they re-measure: B Date · C Value, which is meaningful business conversations that week (count) · E Note. Column D is calculated.
