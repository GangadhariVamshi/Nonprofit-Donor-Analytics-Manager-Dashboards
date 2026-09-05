# Nonprofit Donor Analytics — Manager Dashboards

## Overview
This project builds on the Week 1 nonprofit data cleaning work, combining member, donation, and regional data into a single connected model, then delivers three role-specific Power BI dashboards — for a Product Manager, a Customer Relationship Manager, and a Regional Manager — each highlighting the metrics most relevant to that role.

## Data Preparation
- Corrected and finalized the data cleaning from the prior week (deduplication, column splitting, formatting)
- Established relationships across the three source tables (Members, Donations, Regions) into a single combined data model (`Combined_Data`)

## Dashboards

### Product Manager Dashboard
Layout: **Asymmetrical** — mixed visual sizes and irregular placement (summary cards along the top, a stacked bar chart, pie chart, line chart, and table arranged in varying proportions rather than a uniform grid).

- Summary cards: Total Revenue, Average Donation, Minimum Gift Size, Product Mix Score
- 100% stacked bar chart: Donation size breakdown by total donations and average donation
- Pie chart: Donation size vs. total donations, segmented by a gender/donation interaction term
- Line chart: Average donation trend by month
- Data table: Donation size, total donations, total amount, average donation, and total members

**Highlighted callouts on the dashboard:**
- 28.9% of gifts are premium ($400+)
- Average gift declined from $326 (Feb) to $276 (Dec) — a 15% drop from Q1 to Q4

### Customer Relationship Manager (CRM) Dashboard
Layout: **Symmetrical** — visuals arranged in an even grid across the page.

- Gauge: Count of recent donors
- Donut chart: Donations by gender
- 100% stacked column chart: Donations by age group and gender
- Clustered bar chart: Top engaged donors by name
- Line chart: Total donation amount by donor (last name)
- Combo chart (line + stacked column): Donations over time by year, month, and day

### Regional Manager Dashboard
Layout: **Radial** — donut, ribbon, and pie charts arranged around a central table, echoing a circular/radial composition rather than a strict grid.

- Donut chart: Total donations by region
- Ribbon chart: Total donations by region over time/rank
- Clustered column chart: Average donation by region
- Combo chart: Total revenue by region
- Clustered bar chart: Total revenue by state
- Pie chart: Donor penetration by region
- Data table: Region, total revenue, average donation, total donations, penetration, and active donors by region

## Analytical Report

**Product Manager — Insights & Recommendations**
The Product Manager dashboard shows that premium gifts ($400+) make up a meaningful minority of all donations (28.9%), while the average gift size has been on a steady decline over the year — dropping from $326 in February to $276 in December, a 15% fall from Q1 to Q4. This suggests that while there is a valuable premium-donor segment, overall gift size is trending downward. **Recommendation:** investigate what's driving the decline (e.g., donor fatigue, campaign timing, or a shift toward smaller/more frequent gifts) and consider targeted campaigns to re-engage the premium donor segment specifically, since they represent outsized value relative to their share of donors.

**CRM — Insights & Recommendations**
The CRM dashboard's gender and age-group breakdowns, combined with the top engaged donors chart, let the CRM team quickly identify which donor segments are most active and where engagement may be lagging. The time-based combo chart (year/month/day) reveals whether donation activity is seasonal or driven by specific campaign dates. **Recommendation:** use the top engaged donors view to build a stewardship program for high-value repeat donors, and use the demographic breakdowns to tailor outreach messaging by age group and gender.

**Regional Manager — Insights & Recommendations**
The regional dashboard highlights how total donations, average donation size, revenue, and donor penetration vary by region and state, with the penetration pie chart and active-donor metrics pointing to regions that are under-penetrated relative to their potential. **Recommendation:** prioritize outreach and campaign investment in low-penetration, high-potential regions, while using top-performing regions as a model for replicable donor engagement strategies elsewhere.

## Skills Demonstrated
- Data modeling: combining multiple related tables into a single connected data model
- Designing role-specific dashboards tailored to distinct stakeholder needs
- Applying varied dashboard layout principles (symmetrical, asymmetrical, radial)
- Using a range of visualization types (cards, gauges, donut/pie/ribbon charts, combo charts, stacked charts, tables) to convey different kinds of insights
- Translating dashboard metrics into actionable business recommendations

## Files in this Repo
- `nonprofit_donor_manager_dashboards.pbix` — Power BI file containing all three manager dashboards
- `README.md` — This file
