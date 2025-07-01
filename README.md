# atliq-dashboard
# 📊 AtliQ Sales Dashboard – Power BI

📊 Financial Insights from AtliQ Sales Dashboard
🗓 Fiscal Year Definition
AtliQ follows a fiscal year from September to August.

All YTD, QTD, and YoY metrics are aligned to this fiscal calendar using a custom date table.

🔹 2020 Insights
Net Sales: ₹76.92M (↑177% YoY)

Net Profit: ₹-6.15M (↑533% improvement)

Top Performing Segments: Notebook, Accessories, Peripherals

Key Regions: APAC and EU led growth

“2020 was a rapid growth year, with high sales volume but operational inefficiencies. Benchmark targets were not yet defined at this stage.”

🔹 2021 Insights
Net Sales: ₹201.05M (↑161% YoY)

Gross Margin: 28.83% (↓2.94% YoY)

Top Regions: APAC & NA

Exploding Category: Desktop ↑3,825.63% YoY

“Strong improvement in revenue, but cost pressures caused margin compression. Desktop sales emerged unexpectedly as a high-growth area.”

🔹 2022 (EST) Insights
Net Sales: ₹704.25M (↓11.8% YoY)

Gross Margin: 31.35% (↓17.8% YoY)

Profit Improvement: ₹-147.56M → 547.66% better than LY

Top Regions: North America (↑536%), APAC (↑312%)

Top Segments: Desktop, Notebook, Peripherals

“Though revenue slightly declined, profit improved significantly due to better cost control. This is the first year with defined Benchmark (BM) targets, enabling performance vs. target analysis.”

🔸 BM Target Availability Note
BM (Benchmark) targets were only set for FY 2022. Prior years (2018–2021) show BM not available because AtliQ did not establish structured targets during those years. A DAX condition was added to inform users when BM values are blank due to filters or year selection.
📦 Supply Chain Dashboard Insights – 2019 (Q2)
✅ 1. Overall Metrics
Forecast Accuracy: 86.36% (↑10.1% from last year)

Net Error: 0.08M units (↓33.13%)

Net Profit %: 0.22M (↑69.19%)

Insight:
“Forecast accuracy improved significantly year-over-year, helping reduce overstock/understock issues and improving profit margins. The drop in net error shows better alignment between demand forecasts and actual sales.”

📊 2. Accuracy / Net Error Trend Chart
Blue bars: Forecast Accuracy trending between 85–87% weekly

Orange line: Forecast Accuracy LY (last year) stayed around 76%

Insight:
“There’s a consistent improvement in forecast performance across Q2, enabling tighter inventory control.”

📉 3. Key Metrics by Customer
Customer	Accuracy %	Net Error	Risk
Amazon	78.16%	16885	OUT OF STOCK
Croma	40.66%	-2141	OUT OF STOCK
Currys (Dixons)	55.17%	193	EXCESS INVENTORY
Chip 7	40.50%	-2749	OUT OF STOCK

Insight:
“Major retailers like Amazon and Chip 7 are experiencing stockouts due to poor forecast accuracy or underestimated demand. Inventory policies should be revised for these accounts.”

🛠 4. Key Metrics by Product Segment
Segment	Forecast Accuracy	Net Error	Risk
Accessories	89.62%	-13,196	OUT OF STOCK
Networking	84.44%	35,771	EXCESS INVENTORY
Notebook	81.49%	-4,609	OUT OF STOCK
Peripherals	84.64%	-5,264	OUT OF STOCK

Insight:

Accessories have the highest accuracy but still show stockouts, indicating demand surge or lead time issues.

Networking has a large net error on the positive side, causing overstock.

This reflects a classic bullwhip effect — where small errors in forecast lead to large fluctuations in stock levels.

# 💼 Sales Insights – AtliQ Hardware (2020)

This document summarizes the key takeaways from the **Sales View dashboard** in the AtliQ Hardware Power BI project, covering customer profitability, regional performance, product contribution, and unit economics.

---

## 📊 Overview

- **Total Net Sales (NSS):** $238M  
- **Total Gross Margin:** $70.68M  
- **Overall Gross Margin % (GM%):** 29.66%

---

## 🧍‍♂️ Customer Performance

| Customer         | NSS   | Gross Margin $ | GM%     |
|------------------|--------|----------------|---------|
| Amazon           | $44M   | $13.62M        | 30.73%  
| AtliQ eStore     | $28M   | $8.63M         | 30.41%  
| AtliQ Exclusive  | $18M   | $5.54M         | 30.81%  
| Flipkart         | $10M   | $2.34M         | 24.90%  
| Ebay, Sage, etc. | $5M–$7M| 21%–24%        |  

🔍 **Insight:**  
> Amazon is the largest customer by revenue and maintains strong margins. AtliQ’s own channels (eStore, Exclusive) are both profitable and high-volume, validating their D2C model. Flipkart, while valuable, has margin compression that needs attention.

---

## 🌍 Regional Performance (Bubble Chart)

- **USA** has the highest net sales, but comparatively **lower margins**.
- **France, Sweden, Netherlands** show strong margin % on moderate volume.
- **India and South Korea** deliver good sales but slightly below-average GM%.

🔍 **Insight:**  
> Margin-rich regions like EU markets are good candidates for premium product launches. High-volume but low-GM markets (like USA) may benefit from pricing reviews or bundled offers.

---

## 📦 Product Segment Performance

| Segment     | NSS    | Gross Margin $ | GM%     |
|-------------|--------|----------------|---------|
| Notebook    | $77M   | $20.26M        | 26.27%  
| Accessories | $59M   | $17.46M        | 29.63%  
| Peripherals | $54M   | $18.06M        | 30.04%  
| Storage     | $25M   | $7.00M         | 28.52%  
| Networking  | $23M   | $6.99M         | 30.02%  
| Desktop     | $1M    | $0.24M         | 28.75%  

🔍 **Insight:**  
> Notebooks dominate in revenue but have lower margins. Peripherals and Networking contribute excellent margin % and should be emphasized in marketing and upsell efforts.

---

## ⚙️ Unit Economics (Donut Visuals)

- **Total Net Sales:** $238M  
- **COGS:** 30%  
- **Gross Margin Contribution:** 70%  
- **Post-Invoice Deductions:** ~23%

🔍 **Insight:**  
> Only 70% of revenue becomes gross margin due to invoice discounts and COGS. Product-level discounting strategies must be reviewed to protect margins.

---

## 🧠 Strategic Summary

- Strengthen profitability in low-GM high-revenue accounts like **USA** and **Flipkart**.
- Leverage high-margin segments like **Peripherals** and **Networking** in promotions.
- Target **Europe** for premium positioning given favorable margin profiles.
- Monitor invoice-level discounts that eat into profit even when gross sales are high.
 

## 🎥 Demo Video
[Watch it here](https://screenrec.com/share/2DlaGMUOHV)

### 🔗 Live Dashboard (Power BI Service):
[👉 View on Power BI](https://app.powerbi.com/groups/me/reports/66f5e34a-43aa-4879-9abc-ecf2dae03ee5?experience=power-bi)

## 🛠 Tools Used
- Power BI Desktop
- DAX for measures
- GitHub for version control
