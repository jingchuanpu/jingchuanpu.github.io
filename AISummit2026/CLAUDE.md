# Monthly Performance Report — working folder

This folder holds monthly business data for MapleStream, a subscription app for
home cooks. When asked to build or update the monthly performance report, produce
a single self-contained `report.html` saved in this folder, using only the data
in the files here.

## Files in this folder
- `sample-monthly-metrics.csv` — one row per month, with columns:
  marketing_spend, new_customers, revenue, churn_rate_pct, customer_satisfaction.
- `sample-customer-reviews.csv` — individual customer reviews, with columns:
  review_id, month, rating (1–5), review_text.

## What the report should contain
1. Headline — the latest month's key numbers (revenue, new customers, churn rate,
   marketing spend), each with the change versus the previous month. Flag anything
   that got worse by more than 10%.
2. Trend — a short read on the last few months, with a revenue-over-time chart.
3. Relationships — which metrics move together: a correlation heatmap and the
   strongest pairs. Always note that correlation is not causation, and that metrics
   trending over time can look related when they are not.
4. Customer feedback — the sentiment split (positive / neutral / negative) and the
   top themes from the reviews, each with one short quote. Then the top complaints
   and the top praises.
5. Recommendation — one or two specific next steps a manager could take.

## Rules
- Use only the data in this folder. Never invent numbers, quotes, or reviews.
- Keep the writing plain and short. Round percentages to one decimal place.
- Keep quotes word-for-word and under 15 words; use at most one quote per theme.
- Save the finished report as `report.html` in this folder.
- Do not delete or overwrite the source data files.

## Optional
- If asked, also save a short `summary.md` with the headline and recommendation only.
