# 🛒 Swiggy Instamart Sales Dashboard | Power BI

An interactive Power BI dashboard that analyzes Swiggy Instamart sales by city type, shop size, shop type and quarter, with KPIs and a Top 5 shops leaderboard.



![Dashboard Preview](YOUR-SCREENSHOT-FILE-NAME.png)



## 📌 Business Problem
A quick-commerce business needs to know where revenue comes from so it can decide which shop formats to expand, which cities to prioritize and when to plan stock. This dashboard answers those questions in one interactive view.

## 🎯 Objectives
- Track headline KPIs: sales, orders, order value and customer rating
- Compare sales across city tiers, shop sizes and shop types
- Spot quarterly trends
- Rank the Top 5 shops by sales
- Let users filter the whole report by year

## 📊 Key KPIs
| KPI | Value |
|---|---|
| Total Sales | 439K |
| Total Orders | 2K+ |
| Average Order Value | 183.80 |
| Average Rating | 3.92 / 5 |

## 🔍 Key Insights
1. **Supermarket Type1 drives about 74% of sales** (326,898 of 439,282), while Grocery Stores contribute about 26% (112,384).
2. **Tier 3 cities generate the highest sales**, followed by Tier 1, with Tier 2 lowest.
3. **Sales are spread almost evenly across shop sizes** (roughly 32% to 35% each), so no single size dominates.
4. **The Top 5 shops contribute 47,722 in sales (about 11% of the total)**. SHOP052 leads with 10,100.
5. **SHOP059 has the best rating (4.07) among the Top 5**, while SHOP017 has the lowest (3.79), so high sales don't always mean high satisfaction.
6. **Quarterly sales stay in a narrow band (about 106K to 114K)**, showing a stable demand pattern with mild seasonality.

## 💡 Business Recommendations
- Prioritize Supermarket-format shops when expanding, since they bring the most revenue.
- Invest in Tier 3 cities, which are the top-performing market.
- Study what SHOP059 does well (rating 4.07) and replicate it in lower-rated shops.
- Plan inventory ahead of the strongest quarters.

## 🛠️ Tools & Skills Used
| Tool | Usage |
|---|---|
| Power BI | Data modeling, visuals, slicers |
| DAX | Custom measures, e.g. `Average Order Value = DIVIDE([Total Sales], [Total Orders])` |
| Top N Filter | Top 5 shops leaderboard |
| Excel | [Source data / cleaning] |

## 📈 Dashboard Features
- KPI cards (Sales, Orders, AOV, Rating)
- Sales by City Type (bar chart)
- Sales by Shop Size (pie chart)
- Orders and Sales by Shop Type (bar chart and table)
- Quarterly sales trend (area chart)
- Top 5 shops table
- Year slicer (2021 to 2024) that filters the whole report
