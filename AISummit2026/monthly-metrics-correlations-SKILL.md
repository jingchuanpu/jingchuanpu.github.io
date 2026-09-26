---
name: metric-correlations
description: Find and visualize which metrics move together in a monthly business file. Use when the user asks about correlations, relationships, "what moves together," or wants a heatmap or scatter plot of their metrics.
---

# Metric Correlations and Visualization

When the user gives you a spreadsheet or CSV of monthly metrics, do the following:

1. Correlations — compute the correlation between each pair of numeric columns.
2. Top relationships — list the five strongest relationships in plain English. For each,
   name both metrics, give the correlation value rounded to two decimals, and say whether
   it is positive or negative. Also call out the strongest negative relationship.
3. Visualize —
   - a correlation heatmap of all numeric metrics, with a clear title and a readable
     color scale;
   - a scatter plot of the single strongest pair, with a light trend line.
4. Caution (always include) — one short paragraph reminding the reader that correlation
   is not causation, and that because these are monthly numbers trending over time, many
   metrics rise together, so a high correlation can be misleading. Point out any pair that
   is likely driven by a shared upward trend rather than a real link.
5. One thing to investigate — suggest a single relationship worth testing properly,
   and say why.

Rules:
- Use only the data in the file. Never invent or estimate numbers.
- Round correlations to two decimals.
- Label every chart with a title and axis names; keep colors readable.
- If a column is not numeric or has missing values, skip it and say so.
- Keep the written part under one page; let the charts carry the detail.
