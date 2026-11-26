# Task 3 — fixed-window reliability review (replace four lines)
SLI: (10000-120)/10000* 100=98.8%, below the agreed 99.0% SLO for window 2026-10-01T00:00:00Z/2026-10-30T00:00:00Z.
Allowed errors: 10000 *(1-99/100) = 100 requests.
Remaining error budget: 100-120=-20 requests.
Decision: Prioritize reliability improvements before routine feature releases because the error budget has been exceeded by 20 requests.
