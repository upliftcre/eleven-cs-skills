---
name: c10-closings
description: Run the post-closing protocol for a commercial real estate advisor — the deposit and the adjacent-opportunity contact, both within seven days, from Chapter 12 of The Eleven C's. Use when someone says a deal funded or closed, mentions collecting a commission, or asks what to do after a transaction is finished.
---

# Closing Conversion

A closing is the most valuable event in an advisor's year, and for most of them it evaporates in about a week.

Two actions, both inside seven days. A closing that produces neither was just a transaction.

## What is actually sitting there at funding

Four assets, all at peak value the day the money moves, all decaying fast:

- **Proof** — they just solved a real problem at real stakes
- **A widened network** — the other side's broker, the lender, the attorney all updated their opinion
- **Market intelligence** — pricing, timing, what the lender required
- **Adjacent opportunities** — the seller's other buildings, the neighbor who watched, the tenant down the street

The testimonial requested a month later arrives after the glow cooled. The adjacent contact made a quarter later finds a competitor already in the room.

## Action one — the deposit

Convert the closing into proof: a written case record, dated, published where it can be found. Invoke the c06-credibility skill if it is available; otherwise draft it here against the five elements — named problem, a decision only expertise explains, verifiable outcome, date and market tag, a findable home.

Draft it within days while the numbers are still exact. Request the testimonial while gratitude is warm, and name the moment you want described: *"Would you mind mentioning the pricing conversation from our first meeting?"* A client asked seven days after funding says yes. The same client asked two quarters later says "sure, send me something," which means nothing arrives.

Ask for specifics. *"He was great"* is decoration. *"He told us our price expectation was wrong in the first meeting, showed us why, and we sold three months later at his number"* is evidence.

## Action two — the convert

Build the adjacent list — ten minutes, everyone the deal touched:

- **The seller's other holdings.** What else do they own, and what did this sale just teach them about value?
- **Neighboring owners and tenants.** Who watched this trade and now has a number in their head?
- **The lender.** Who just watched them perform and will finance the next one.
- **The opposing broker.** Good experience or bad, there is now a working relationship and a shared submarket.
- **The client's own network.** Ask directly: *"Who else do you know facing this same decision?"*

Rank by warmth and timing. Pick at least one. Contact within the week — not a blast, a specific human outreach referencing the specific event. *"We just closed the Miller Building at $X; given you're next door, worth fifteen minutes?"*

The closing did the prospecting. Warm context, current news, a natural reason to call. Declining that call leaves qualified self-generated pipeline in the parking lot.

**First contact is theirs.** Support can build the list. Relationships do not delegate, and neither does the judgment about which door to knock on first.

## Why this gets skipped, and what to say

It is not forgetting. It is depletion. A closing is the end of a marathon and every instinct says *done*.

Two things worth telling them:

**This is not more selling.** The case record is fifteen minutes of writing about something they just lived. The testimonial is one email at peak goodwill. The adjacent call references news the other party actively wants. These are the lightest-touch actions in their entire practice, scheduled at the exact moment they are cheapest.

**The week after funding is when their value is most visible** — which makes it prospecting season, not recovery season. The neighboring owner who watched them close will never be more reachable than he is right now.

Take a day. Then put the hour on the calendar before the month swallows it.

## When the well looks dry

Sometimes a deal funds and there is nothing obvious — a confidential client, an unpublicizable transaction type.

The diagnostic still stands, it just routes differently. A confidential closing still deposits anonymously — structure, obstacle, outcome, no names. It still converts internally: the lender relationship deepens, the opposing broker remembers them, the knowledge sharpens the next pitch.

And when a closing genuinely produces neither, write down why. A pattern of dry closings points upstream — to deals that passed the filter on charm rather than evidence, or engagements whose scope never touched anyone but the signer.

## The seven days

- **Day of funding:** block two hours later in the week. Move every date from the closing file into the calendar while it is open.
- **Days one to two:** draft the case record while numbers are exact. Send the testimonial request.
- **Days two to four:** build the adjacent list, make the call. *"We just closed"* has a shelf life measured in weeks.
- **Days five to seven:** place the deposit where it can be found. Confirm the testimonial landed. Log any conversation that came out of the adjacent call.

Three hours across a week, against a closing that took months. The most expensive work of their year deserves its cheapest follow-through.

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

### Where it goes: the C10 Closings tab

- C20 Closing (property, date funded) · C21 Deposit made within one week? "Yes" or "No" · C22 Adjacent opportunity contacted within one week? "Yes" or "No"
- C15 Date measured
- G30–G34 Contacted?: "Yes" or "No". G30 The seller's portfolio · G31 The neighboring owners and tenants · G32 The lender · G33 The opposing broker · G34 The client's own network
- The deposit itself goes in the C6 Credibility deposit log, rows 22–33: B Date · C Deposit description · E Lane tag · F Location published.
- History log on this tab, rows 55–62. One row each time they re-measure: B Date · C Value, which is "Both", "One of two" or "Neither" for the most recent closing · E Note. Column D is calculated.
