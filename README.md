# smf2000ledger
Personal Finance Dashboard



04-Aug-2026
Fixed in v17.1: it now sorts by and displays nextDate (statement), while Bills' "Next to pay" keeps using the due date.

fixed in v17.2. Maxis Bill's stored statement stays 24-Jul (so its unpaid bill still carries in Bills), but "Next expected" now rolls a past statement forward one cadence for display — it reads Maxis Bill · 24-08-2026, and the card picks the nearest upcoming statement across all schedules.

v17.3: "Next expected" now headlines the nearest statement, then lists any other active schedules whose upcoming statement lands in that same month (name · DD-MM · amount), closing with "N statements in Aug 2026 · RM total". It groups by the headline's month rather than the calendar month, so the card is never empty when nothing is due until next month. Confirmed list untouched.

v18.0 — the dashboard now carries a Fixed commitments band right under Safe to spend, in three panels:

Committed each month — RM 3,237.72/mo (RM 38.8k/yr), split bar for recurring vs subscriptions with counts, plus the share of your average monthly income (6% today; turns amber past 40%, red past 60%).
August tracker — settled vs to-go, a progress bar, and the next four occurrences with day badges and status chips (Settled / overdue / Due today / Not yet issued / Issued · due DD-MM).
Subscriptions — active subs ranked by monthly cost with mini bars and each one's next statement date.
The old "Coming up" card is gone (its content lives in the tracker, now with paid/unpaid state), so Recent activity spans the full row

v19.0 Planned Expense live — nav item 4

3-Aug-2026 v13-17
bill schedule pause/resume

02-Aug-2026 
v10.0	2 Aug 2026	Custom date range on Period filter (From/To, quick picks, live summary, saved in settings)

v11.0	2 Aug 2026	Account-to-account transfers (⚠️ CSV re-import loses pairing)

v11.1	2 Aug	Account row click → Transactions (filtered, This month)

v12.0	2 Aug	Default account for new entries (first / last used / specific)

29-Jul-2026 
Uploaded v6.4

v8 bill tracking section, v.8.1/8.2 bug fixed

v9.0/1 Finance Management features
v9.2 fix correct month bill display

28-Jul-2026 Uploaded v5 + v6 + v6.3

27-Jul-2026 Uploaded v3
