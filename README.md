# Power BI Assignment — Groups & Bins Analysis Dashboard

## Overview
This project fulfills the **Power BI Groups & Bins** assignment (Beginner–Intermediate level). It uses a small sales dataset to demonstrate how to build **categorical groups** and **numeric bins** in Power BI, then visualize them on a single dashboard page.

## Files in this Project

| File | Description |
|---|---|
| `PowerBI_Groups_Bins_Assignment__1_.xlsx` | Source dataset (`Sales_Data` sheet) — imported into Power BI as the base table. |
| `__Power_BI_Groups_and_bins_Assignment.pdf` | Original assignment brief with the full list of tasks (Parts A–C). |
| `groups.pbix` | Working/draft file — data model with Region and Product groups created, report page not yet built. |
| `Group_Bin.pbix` | **Final deliverable** — completed report with all groups, bins, and visuals in place. |

## Source Data
The `Sales_Data` table contains:

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Order_Date | Date of the order |
| Customer_Name | Customer name |
| Region | North / South / East / West |
| Product | Laptop / Mobile / Tablet |
| Sales_Amount | Order value (₹) |
| Quantity | Units sold |
| Age | Customer age |

## What Was Built

### Part A — Groups (Categorical Data)
- **Region Group**
  - North & East → `Group A`
  - South & West → `Group B`
- **Product Group**
  - Laptop & Tablet → `Electronics`
  - Mobile → `Handheld Device`
- A table visual summarizing **Product Group** vs **Total Sales Amount**.

### Part B — Bins (Numerical Data)
- **Sales Amount Bins**: bin size of `10,000`, grouping orders into sales-value ranges.
- **Age Bins**: custom ranges —
  - 18–25
  - 26–35
  - 36–45
  - 46–60
  - 60+
- A column chart showing **Age Bins vs Total Sales Amount**.

### Part C — Visualization (Dashboard Page)
The final report page — titled **"Groups & Bins Analysis Dashboard"** — brings everything together:
- Bar chart: **Sales Amount by Product Group**
- Column chart: **Sales Amount by Age Bins**
- Column chart: **Sales Amount by Sales Amount Bins**
- Column chart: **Sales Amount by Region Group**
- Slicer: **Region Group**, to filter the whole page interactively

## How to Open
1. Open `Group_Bin.pbix` in Power BI Desktop to view the completed dashboard.
2. If you want to see/edit the grouping logic from scratch, open `groups.pbix`, or re-import `PowerBI_Groups_Bins_Assignment__1_.xlsx` and recreate the groups/bins per the steps above.
3. To modify a group or bin: right-click the field in the **Fields** pane → **Edit groups** (for groups) or the field's **New group** dialog (for bins).

## Notes
- `Group_Bin.pbix` is the file to submit — it contains the fully built dashboard satisfying all 10 assignment questions (Parts A, B, and C).
- `groups.pbix` is kept as an earlier checkpoint showing the grouped fields before the report page was designed.
