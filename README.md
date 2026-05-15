# 🍔 Swiggy Web Traffic Analysis Dashboard

> Analysing Swiggy's web traffic across traffic sources, devices, geographies, campaigns, and browsers to understand conversion performance and user behaviour - built in Tableau.

---

## 📊 Project Overview

| Attribute | Detail |
|-----------|--------|
| **Tool** | Tableau (.twbx) |
| **Time Period** | 1 July 2024 - 21 October 2024 |
| **Total Sessions** | 30,110 |
| **Traffic Sources** | Direct, Organic, Paid, Referral |
| **States Covered** | 14 Indian states |
| **Campaigns** | Holiday Discounts, Newsletter, Product Launch, Spring Sale |

---

## 🔢 Key Metrics by Traffic Source

| Traffic Source | Sessions | Avg Session (min) | Avg Page Views | Bounce Rate | Conversion Rate |
|---------------|----------|-------------------|----------------|-------------|-----------------|
| Organic | 15,007 | 5.5 | 3 | 21.7% | 45.6% |
| Direct | 8,957 | 5.5 | 3 | 22.9% | 46.1% |
| Paid | 3,104 | 5.5 | 3 | 25.1% | 44.7% |
| Referral | 3,042 | 5.5 | 3 | 24.2% | 45.3% |
| **Grand Total** | **30,110** | **5.5** | **3** | **22.7%** | **45.6%** |

---

## 📁 Files in This Repository

```
📁 Swiggy-Web-Traffic-Analysis/
│
├── 📊 Swiggy_Traffic_Analysis.twbx                       # Tableau workbook
├── 🖼️ Swiggy_Web_Traffic_Analysis_Dashboard.png          # Dashboard screenshot
└── 📄 README.md                                          # This file
```

---

## Dashboard Overview
[Swiggy_Web_Traffic_Analysis_Dashboard]<img width="1366" height="755" alt="Swiggy_Web_Traffic_Analysis_Dashboard" src="https://github.com/user-attachments/assets/2224efd4-e58d-4f29-a4be-88eeac25a00d" />


## 📐 Dashboard Components

The Tableau dashboard includes:

- **KPI Table** - Sessions, Avg Session Duration, Avg Page Views, Bounce Rate, Conversion Rate by traffic source
- **Weekly Sessions Trend** - Line chart showing weekly session count with conversion rate overlay (Jul-Oct 2024)
- **States (% of Sessions)** - Bar chart showing Maharashtra (17%), UP, Karnataka as top states
- **Top 10 States by Conversion Rate (%)** - Heatmap across traffic sources × states
- **Sessions by Device Split** - Pie chart (Mobile 60%, Desktop 35%, Tablet 5%)
- **New vs Returning Visitors** - Donut chart (New 45.1%, Returning 46.7% — wait, Returning leads!)
- **OS Distribution by Bounce Rate** - Horizontal bar chart (Windows, Android, iOS, Linux, macOS)
- **Campaign Performance — Conversion Rate by State** - 4 India maps for each campaign
- **Sessions & Conversion Rate by Browser** - Bar chart (Chrome leads by far, followed by Safari, Firefox)
- **Filters** - Date range, State, Traffic Source, Conversion Rate range

---

## 🔍 Key Findings

**Device Split**

Mobile dominates at 60% of sessions - Swiggy's audience is mobile-first. Desktop accounts for 35%, Tablet 5%.

**New vs Returning**

Returning visitors (46.7%) slightly outnumber new visitors (45.1%) - indicating healthy user retention on the platform.

**Top Converting States**

West Bengal leads in referral conversion (52%), Maharashtra performs consistently across all sources. Rajasthan shows strong paid conversion.

**Campaign Performance**

- Holiday Discounts shows highest conversion in Maharashtra (54%) and MP (56.3%)
- Product Launch shows strong performance in Delhi NCR (55.5%) but low in Bihar (18.2%)
- Spring Sale is most consistent nationally across states

**Browser Breakdown**

Chrome is the dominant browser with ~15,000 sessions. Safari, Firefox, Internet Explorer, and Edge trail significantly.

**OS Bounce Rate**

Windows users have the highest bounce rate (~20%). Android and iOS perform better, consistent with mobile-first usage.

---

## 📐 Metric Tree

```
🎯 BUSINESS GOAL: Improve Web Conversion Rate
│
└── ⭐ PRIMARY METRIC: Conversion Rate (45.6% avg)
        │
        ├── 📱 Device Type
        │       └── · Mobile / Desktop / Tablet
        │
        ├── 🌍 Geography
        │       └── · State-wise performance
        │
        ├── 🔗 Traffic Source
        │       └── · Direct / Organic / Paid / Referral
        │
        └── 📢 Campaign
                └── · Holiday Discounts / Newsletter /
                    Product Launch / Spring Sale
```

---

## 🛠️ Tools Used

- **Tableau** - Full interactive dashboard with geographic maps, heatmaps, trend lines, pie/donut charts, and bar charts

---

## 👩‍💻 Author

**Vaishali Parmar**  
Data Analyst | Next Leap Program

---

*This project is part of the Next Leap Data Analytics Program*
