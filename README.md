# Sinking funds calculator

Free, single-file calculator for sinking funds: money set aside from every paycheck for a cost you can see coming (car insurance, holiday gifts, tires, annual subscriptions). Enter your pay schedule (weekly, biweekly, 15th and last day, monthly), your next payday and each fund with its cost, due date, amount already saved and whether it comes back (every year, 6 months, 3 months or one time). It shows:

- the number of real paydays left before each due date,
- the amount per paycheck for each fund to be ready on time (catch-up),
- the steady amount per paycheck once a recurring fund is caught up, counted on the real calendar (26 or 27 biweekly paydays in a year),
- the total set aside each month for the next 12 months,
- the whole plan, payday by payday, as a CSV for Excel or Google Sheets.

Use it online: https://ricco020.github.io/sinking-funds-calculator/

Calculation checked against an independent Python implementation on 300 random plans (all four pay frequencies, 1 to 5 funds, all repeat options, due dates before the first payday included): 0 difference.

Printable version to fill in by hand: https://tidysheets.shop/p/sinking-funds-tracker-printable

Runs fully in the browser, no tracking, no network calls. MIT licence.
