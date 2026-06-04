# A-B-testing-template-
A/B Test Analysis Dashboard | Tableau + BigQuery
· Stack: BigQuery · SQL · Tableau

Data was extracted from Google BigQuery using a structured SQL query built with CTEs and window functions. Tableau is connected via a live connection, so the dashboard updates automatically — no manual refresh needed.

The dashboard tracks 10 user events across both test groups with filters by device, channel, country, and date. The most notable result: +12.12% uplift in add_payment_info (a direct conversion step) and +4.25% growth in user_engagement in the test group. Minor declines in new_account (−3.71%) and add_to_cart (−2.08%) were noted as points for follow-up.

Group split was verified as 50/50 across all segments — confirming correct randomization. Mobile accounts for ~58% of traffic in both groups, making it the dominant segment worth targeting in future tests.

Recommendation: roll out the tested changes based on the payment funnel signal, and investigate the new_account drop separately before full deployment.
