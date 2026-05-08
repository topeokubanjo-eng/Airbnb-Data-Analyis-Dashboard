# 🏡 U.S. Airbnb Market Analysis — Power BI Dashboard & Presentation

> A data-driven market guide for prospective Airbnb hosts, built from 458K+ U.S. listings across 2020 and 2023.

---

## 📊 Dashboard Preview

![U.S. Airbnb Market Analysis Power BI Dashboard](AirbnbPowerBI%20Picture.JPG)

---

## 📁 Project Overview

This project analyzes the U.S. short-term rental market to help new hosts make informed investment decisions. Using two Kaggle datasets (`AB_US_2020` and `AB_US_2023`), it combines a **Power BI dashboard** and a **structured presentation** to surface pricing trends, demand signals, city-level comparisons, and a bottom-line profitability breakdown.

**Stakeholders:** Market analysts, real estate investors, prospective Airbnb hosts

---

## 🗂️ Files

| File | Description |
|------|-------------|
| `U_S_Airbnb_Market_Analysis_Presentation.pptx` | Slide deck with full narrative, P&L breakdown, and city recommendations |
| `POWERBI_AIRNBN.JPG` | Dashboard screenshot |
| *(Power BI .pbix file)* | Interactive dashboard with city-level filter |

---

## 🔑 Key Findings

### Market at a Glance
| Metric | Value |
|--------|-------|
| Average Price / Night | $239.86 |
| Total Active Listings | 458,177 |
| Total Hosts | 188,040 |
| Est. Monthly Revenue (70% occupancy) | $5,037 |

### What Type of Listing Earns Most?
- **Entire home/apt** captures **81% of total market revenue** (~$89M) — nearly 5x more than private rooms
- Hotel rooms show a higher average ($9.5K/mo) but this is skewed by a tiny number of luxury boutique properties; they are not a realistic entry point for new hosts

### Monthly P&L — Entire Home (U.S. Avg)
*Based on $239.86 avg price · 70% occupancy · 21 nights/month*

| Item | Amount |
|------|--------|
| Gross Revenue | +$5,037 |
| Airbnb Host Fee (3%) | −$151 |
| Cleaning (~$15/turnover × 21) | −$315 |
| Utilities & Supplies | −$150 |
| Damage Reserve (2% of gross) | −$101 |
| Short-Term Rental Insurance | −$100 |
| **Est. Net Monthly Profit** | **~$4,220** |

---

## 📍 City Recommendation

High price ≠ high returns. The analysis ranked cities on **both** nightly rate and demand (avg reviews/listing):

| City | Avg Price/Night | Avg Reviews/Listing | Verdict |
|------|----------------|---------------------|---------|
| New York City | $174 | 20 | ❌ Low demand |
| Los Angeles | $257 | 33 | ❌ Low demand |
| Portland | $137 | 75 | ⚠️ Low price |
| **Nashville** | **$254** | **58** | ✅ Sweet spot |
| **New Orleans** | **$222** | **45** | ✅ Sweet spot |

### 🥇 Nashville, TN — Top Pick
- $5.34K/mo gross · ~$4,080 net · **~$48,960 est. net annual income**
- 58 avg reviews/listing — strong, consistent demand
- Only 4,928 hosts across 14.69K listings — favorable competition ratio
- Premium coastal-city pricing with a growing tourism and tech sector

### 🥈 New Orleans, LA — Strong Runner-Up
- $4.67K/mo gross · ~$3,570 net · **~$42,840 est. net annual income**
- 45 avg reviews/listing — solid occupancy driven by year-round festivals and tourism
- 4,792 hosts across 13.46K listings — manageable competition

---

## 🛠️ Tools Used

- **Power BI** — interactive dashboard with city-level slicer, KPI cards, donut chart, bar charts
- **Kaggle Datasets** — `AB_US_2020` and `AB_US_2023`
- **PowerPoint** — narrative presentation structured across 3 acts (Opportunity → Real Numbers → Where to Invest)
- **ChatGPT** — used to simulate net income estimates

---

## ⚠️ Assumptions & Limitations

- 70% occupancy rate assumed throughout
- Cleaning cost estimated at $15/turnover (market rates range $15–$30+)
- Net income estimates deduct host fee, cleaning, utilities, damage reserve, and insurance
- Airbnb remits occupancy tax, but net rental profit remains taxable income
- Always verify local short-term rental regulations and permit requirements before investing

---

## 📬 Contact

**Tope Okubanjo**
[Portfolio](https://topeokubanjo-eng.github.io) · [LinkedIn](https://linkedin.com/in/topeokubanjo)
