# Retail Sales Dashboard — Power BI

**Objective:** Provide a single view of sales performance: Revenue, Orders, Average Order Value, Top Products, and City/Region trends.

## 🔍 Highlights
- Data model with Date table and relationships (Star schema)
- KPIs: `Total Revenue`, `Total Orders`, `AOV = Revenue / Orders`
- DAX examples:
  - `Total Revenue = SUM(FactSales[Revenue])`
  - `AOV = DIVIDE([Total Revenue], [Total Orders])`
- Time intelligence: MoM/YoY trend, last-12-month rolling line chart
- Interactions with slicers (Date, Product Line, City/Region)

## 📂 What’s in this repo
- `PowerBI/powerbi_project.pbix` — the full dashboard
- `assets/` — **add screenshots** here (e.g., `overview.png`, `by-city.png`)
- `README.md` — this file

## ▶️ How to open
1. Download the `.pbix` file.
2. Open in **Power BI Desktop** (free).
3. If data is embedded, you’re good. If not, update data source paths when prompted.

## 🌐 Publish (optional)
- Publish to Power BI Service → File → Publish.
- If you want a public (view-only) link for your CV, use **Publish to Web** (only if data is safe to share).

## 🧠 Skills Demonstrated
Power Query (transformations), data modeling (Star schema), DAX KPIs, report design & UX, business storytelling.

