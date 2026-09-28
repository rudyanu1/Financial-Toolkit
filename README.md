# Financial-Toolkit
Three financial planning tools in one file. No install, no server, no account.  Most calculators hand you a single number. This toolkit shows you the range of what could happen and answers the questions people actually lose sleep over: Will my money last? Can I afford this house? What am I really paying?

1. Portfolio Simulator

A Monte Carlo simulator that runs thousands of possible futures for your investment mix and shows the spread of outcomes as a probability fan.

Fat-tailed returns (Student's t distribution) so crashes appear at realistic frequency, with an adjustable "market turbulence" control
Correlated holdings, 12 quick-add asset presets, and a per-holding return and volatility
Contributions or withdrawals, optionally growing with inflation, plus annual fees
Months or years as the time horizon, with the axis adapting to fit
"Chance of reaching my goal" and "chance my money runs out" readouts
Withdrawal solver: pick a target success rate, and it searches for the largest sustainable withdrawal
Sample runs (rough, typical, strong) drawn over the probability bands
Today's-dollars toggle to see inflation-adjusted results
Sequence-of-returns callout showing how much when a bad stretch lands matters
Interactive chart: hover for exact values
2. Retirement Number

A fast, deterministic readiness check, computed entirely in today's purchasing power.

Your FI number is built from a year-by-year spending schedule, not a single rule of thumb
Handles Social Security or pension that starts after you retire, part-time or rental income with an end age, healthcare that inflates faster than everything else, and a one-time big expense
Separate pre- and post-retirement return assumptions
Projected savings, surplus or shortfall, the contribution needed to close a gap, and Coast FI status
Lifecycle chart (saving, then drawing down) that flags the age funds would run out, if ever
Interactive chart: hover any age
3. Mortgage

A mortgage calculator built a little differently.

The payment is found, not looked up. The loan is simulated month by month and the payment is bisected until the balance lands on exactly zero at the end of the term. The result matches the standard formula to the cent; the approach is just different
PMI that falls off using paydown and home appreciation (when your balance reaches 80% of the home's current value)
True all-in monthly cost: principal and interest, property tax, insurance, PMI, HOA, and upkeep
Extra-payment analysis: time saved and interest saved
The crossover point: when your payment starts going mostly to principal instead of interest
"If I sold after N years": cash in hand after selling costs, and your effective monthly cost of living there, which is the number to compare against rent
Interactive chart: hover over any month
