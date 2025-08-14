# E-commerce Sales Data Analysis

## Project: E-commerce MoM Amazon Sales Analysis (April vs May 2024)

### Overview
This project analyzes Amazon sales, traffic, and advertising data to perform a month-over-month (MoM) comparison between April 2024 and May 2024. The analysis covers key performance indicators, applies the "Magic Equation" decomposition, investigates root causes using the five whys, forms MECE hypotheses, and identifies the main product-level drivers of performance.

---

## Key Objectives

- Clean the original dataset and derive new performance metrics
- Calculate MoM KPIs with both absolute and percent delta
- Decompose sales movement using the Magic Equation (`Sales = Traffic × Conv Rate × ASP`)
- Identify and analyze outliers, drops, and root causes impacting business metrics
- Formulate MECE (Mutually Exclusive, Collectively Exhaustive) hypotheses for traffic/conversion drops
- List strategic recommendations for business teams

---

## Data

**Input:** Raw Amazon sales export

- **Columns:** Product Code, Date, Sales, Organic/Ad Split, Traffic, Impressions, Units, Ad Spend, etc.
- ~8,600 daily records across April and May 2024.

**Output:** Cleaned datasets, derived KPI tables, outlier reports.

---

## Main Steps

### Data Preparation & Cleaning
- Parse data, remove commas, handle negative/outlier values, fill nulls, and standardize column names.

### Feature Engineering
- Compute ROAS, ACoS, CTR, Conversion Rate, ASP, and derive movement/variance fields.

### Month-on-Month KPI Calculation
- Aggregate and compare sales, units, traffic, ad spend, conversion, and more for each month.

### Magic Equation Decomposition
- Break down sales delta into traffic, conversion, and ASP effects.

### Root Cause & Hypothesis Analysis
- Identify MECE hypotheses (stockout, listing, price, review, competition, seasonality, ad support).
- Flag outlier SKUs, quantify impact.

### Recommendation & Action Plan
- Actionable next steps on inventory, listings, ad strategy, pricing, and focus SKUs.

---

## Key Insights (April → May 2024)

- Overall revenue was up 1%, despite units falling 2% and traffic dropping 15%. Lift in conversion (+15%) and ASP (+3%) offset the traffic drop.
- Ads became more efficient: spend dropped 13%, but ROAS improved 20% and ACoS fell 16%.
- The bulk of the organic sales drop came from a small set of ASINs with large declines in both traffic and conversion—many showed evidence of stockouts or suppressed listings.
- No broad price-related conversion issues were detected.

---

## Recommendations

- Immediately resolve inventory & listing issues for key products with missing sales but active traffic.
- Increase ad support for high-value products with slipping organic rankings.
- Regularly monitor conversion rates by product to detect early risks of traffic/commercial performance drift.
- No urgent pricing actions required; pricing was not a primary issue.
