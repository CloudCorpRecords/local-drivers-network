# Records Request Fees — What Small-City Requests Actually Cost

*Extracted from the Consolidated Brief, Appendix A (researched 2026-10-20). This answers the open question from the source thread: "find out what a typical records request fee is in cities under a 20k population." General information, not legal advice.*

## Appendix A — Research: Typical Records Request Fees in Small Cities (Under 20,000 Population)

*This appendix answers the open task in the thread: "Go ahead and find out what a typical records request fee is in cities under a 20k population." Researched October 20, 2026. This is general information, not legal advice.*

### A.1 The California rule (most small towns in the test area are in California)

Under the **California Public Records Act (CPRA)**:

- **Inspecting records in person is free.**
- An agency may charge only the **direct cost of duplication** for copies. Courts and agency schedules put this at typically **$0.10 to $0.25 per page**.
- An agency generally **may not charge for staff time spent searching for, retrieving, or reviewing records**.
- Records that **already exist in electronic form** (PDF, spreadsheet, database export) are commonly provided by email / portal at **no charge or minimal charge**.
- **The exception that can get expensive:** if a request requires the agency to **compile data, run custom queries, or do programming** to produce a record that does not already exist, the requester can be charged the full cost of that production, including staff/programmer time. This is the charge Rene likely ran into warnings about in testing, and it can run into **hundreds of dollars per agency** if the request is framed as "go calculate this for us."
- Agencies must respond with a determination within **10 calendar days** (with a limited extension possible).

**Practical answer to the question asked:** for a normal, narrow request in a California city under 20,000 people, expect **$0 to about $25 per agency** — most often $0 if the record is delivered electronically, or a small flat record-request fee plus a per-page charge if paper copies are produced.

### A.2 What the two test towns actually charge

**Grass Valley, CA (~12,000) — City fee schedule:**
- Police **Record Request Fee: $5.00 for the first 10 pages, plus $0.25 per additional page**
- General document copies: **$0.10 per page**
- Note: Grass Valley also lists a separate **DUI Investigation and Reports charge of $2.00 per minute** of police response time. That is a cost-recovery charge billed in connection with a DUI incident itself, not a records-request fee — but it is directly relevant to the project's DUI cost model, because it shows the city already prices DUI response by the minute.

**Nevada County Sheriff (covers Nevada City, ~6,000):**
- **$5.00 for the first page and $0.50 for each page thereafter** for report copies.

Both are consistent with the pattern in the thread: the Grass Valley / Nevada City tests cost **$0**, because a short electronic or in-person request in a small agency often comes in under, or outside, the copy-fee schedule.

### A.3 Fee categories — why no special status is needed in California

- Under the **federal FOIA** (federal agencies only), requesters are put into fee categories. **News media requesters pay no search or review fees and get the first 100 pages of duplication free.** That category does not apply to city police, sheriffs, or the Highway Patrol.
- City and county records in California are governed by the **CPRA**, which has **no special-status category and no purpose test** — anyone may request public records, and the fee limit (duplication cost only) is the same for everyone.
- So in California, the same low fee is available without claiming any status. In other states, fee and waiver rules vary by state public-records law — some states do have media or public-interest fee waivers, and some allow search fees. This needs a state-by-state check before Version 2.0 scales beyond California.

### A.4 What this means for a 20,000-town rollout — budget scenarios

The per-request fee is small. The risk is volume multiplied by requests that trigger the data-compilation exception.

| Scenario per town (assume 1–3 agencies per town) | Cost per town | Cost at 1,000 towns | Cost at 20,000 towns |
|---|---|---|---|
| Electronic delivery of an existing record | $0 | $0 | $0 |
| Typical small paper/electronic request | ~$5–$25 | ~$5,000–$25,000 | ~$100,000–$500,000 |
| Request requires data compilation / custom query | ~$100–$500+ | ~$100,000–$500,000+ | Not viable — must be avoided |

**Working rules for Version 2.0 that keep the rollout near $0:**

1. **Ask only for records that already exist** (e.g., DUI arrest counts / logs, calls-for-service data, existing reports and fee schedules) — never ask an agency to calculate a new statistic. The CPRA does not require an agency to create a record or answer a question; it requires it to produce existing records. Questions 4 and 5 in Section 5 therefore have to be converted into requests for existing source records, and the calculation done inside Rene's app.
2. **Request electronic format** and delivery by email wherever possible.
3. **Put a fee cap in every request** — e.g., "Please notify me and do not proceed if fees will exceed $25" — so no agency can generate a surprise bill.
4. **Pilot pricing first:** run the full request sequence in 10–20 towns, log every fee quoted, and only then project a national records budget.
5. **Track fees per agency type** (city police vs. sheriff vs. Highway Patrol) — the CHP and sheriffs run on different schedules than a small city PD.

---
