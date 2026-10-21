# V2.0 Screening Questions — The Two Question Sets

From the source thread (Consolidated Brief §§5, 8). Every town in the 5,000–40,000 band, 1+ hour from a major city, gets Set 1 from public data. Towns that pass get Set 2 via public records requests.

## Set 1 — Screening (public data, automated)
1. Have they lost their taxi company?
2. Have the Uber drivers left to go to a major city within an hour's distance? (Pattern case: Grass Valley lost its Uber drivers to Sacramento.)
3. Are they seeing a rise in alcohol-related accidents?

## Set 2 — Cost case (records requests to local police, sheriff's department, Highway Patrol)
4. How much time are officers spending per DUI? (Reference point: Chief Dan Foss, Nevada City — 2 to 6 hours.)
5. What is the taxpayer cost for that DUI? (Labor, lawyers' fees, etc.)

**Implementation rule (from Brief §11 / Appendix A):** records law compels agencies to produce *existing records*, not to answer questions or create statistics. Set 2 must therefore be filed as requests for existing source records (DUI arrest logs/counts, calls-for-service data, existing cost or fee schedules), and the time/cost figures computed inside the V2.0 app. See `cpra-request-template.md`.

## Output per town
One row in the format of `data/screening-template.csv`: screen answers, DUI volume, officer hours, taxpayer cost per DUI, records fees quoted/paid, and a qualified yes/no — the input to direct marketing and to the revenue forecast for Marry O.
