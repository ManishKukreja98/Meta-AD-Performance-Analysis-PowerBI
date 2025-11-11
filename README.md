# Meta Ad Performance Analysis Report | Facebook & Instagram Campaign Analytics using Power BI  

![Meta](https://github.com/ManishKukreja98/Meta-AD-Performance-Analysis-PowerBI/blob/ca2eaa37b476877ea2a0c046bbd0a7f186e63f04/Assets/Meta.png)

## 🚀 Background & Overview
This **Meta Ad Performance Analysis Report** is designed to evaluate and visualize the effectiveness of ad campaigns across **Facebook and Instagram** using **Power BI**.  

The report tracks key **marketing KPIs** — such as **impressions, clicks, engagements, conversions, and budget utilization** — providing a complete funnel view from **awareness → engagement → purchase**.  

It enables marketing teams to:
- Measure **ad effectiveness** and audience behavior.  
- Identify **drop-offs** in the conversion funnel.  
- Optimize **ad creatives, targeting, and budget allocation** using data-driven insights.  

---
## Preview

![Dashboard](https://github.com/ManishKukreja98/Meta-AD-Performance-Analysis-PowerBI/blob/ca2eaa37b476877ea2a0c046bbd0a7f186e63f04/Assets/Meta%20Ad%20Analysis%20Dashboard.png)

![Data Modeling](https://github.com/ManishKukreja98/Meta-AD-Performance-Analysis-PowerBI/blob/ca2eaa37b476877ea2a0c046bbd0a7f186e63f04/Assets/Data%20modeling.png)

## 🧩 Overview of Data Structure
The dataset was extracted from **Meta Ads Manager** and contains campaign-level details.  

| Field | Description |
|-------|--------------|
| `Campaign_Name` | Name or ID of the ad campaign |
| `Platform` | Facebook / Instagram |
| `Impressions` | Total times the ad was displayed |
| `Clicks` | Number of users who clicked the ad |
| `Engagements` | Total interactions (likes, shares, comments) |
| `Purchases` | Completed purchases or conversions |
| `CTR` | Click-Through Rate (%) |
| `Engagement_Rate` | Engagements ÷ Impressions (%) |
| `Conversion_Rate` | Purchases ÷ Clicks (%) |
| `Budget` | Total spend on the campaign |
| `Date` | Campaign run date |
| `Gender`, `Age_Group`, `Country` | Audience demographic and location data |

---

## 💼 Executive Summary

### 🧩 Problem Statement  
The marketing team needed a **comprehensive ad performance tracker** to assess ROI, identify inefficiencies in the funnel, and guide future ad spending decisions across Facebook and Instagram.

### 💡 Solution  
A **Power BI Dashboard and Analysis Report** was developed to visualize the entire customer journey — from **impressions → clicks → purchases** — segmented by **audience demographics, geography, ad formats, and time trends**.  

The dashboard helps:
- Monitor **KPI trends and funnel efficiency**.  
- Compare **Facebook vs Instagram performance**.  
- Identify **audience behavior patterns** for better targeting.  

### 🎯 Impact  
- Brought clarity to **ad ROI and funnel efficiency**.  
- Identified key issues in the **conversion funnel** and **landing page experience**.  
- Helped marketing teams **refine audience targeting**, **ad formats**, and **budget distribution** for improved ROI.  

---

## ⚙️ Methodology

1. **Data Cleaning & Transformation**
   - Imported campaign data from Meta Ads Manager (CSV/Excel).  
   - Cleaned null values, standardized formats, and merged multiple campaign datasets.  
   - Created calculated KPIs such as **CTR**, **Engagement Rate**, and **Conversion Rate**.  

2. **Data Modeling**
   - Built relationships among campaign, demographic, and time tables.  
   - Created a **Calendar Table** using DAX:  
     ```DAX
     WEEKDAY('Calendar Table'[Date], 2)
     ```  
     to enable weekday and hourly trend analysis.  

3. **Visualization in Power BI**
   - Designed **interactive visuals**: funnel charts, donut charts, line graphs, and heat maps.  
   - Used **slicers** for demographics, regions, and time filters.  
   - Applied a **Meta-inspired theme** (blue, purple, and pink tones).  

4. **Insight Derivation**
   - Interpreted KPIs and visuals to highlight actionable business insights and optimization strategies.  

---

## 📊 Insights from the Project

### 🧮 Key KPI Metrics

| Metric | Value | Insight |
|--------|-------|---------|
| **Impressions** | 216K | Strong reach & visibility |
| **Clicks** | 25.4K | High top-funnel activity |
| **CTR** | 11.76% | Excellent ad performance |
| **Engagement Rate** | 13.56% | Strong audience resonance |
| **Purchases** | 1.3K | Moderate conversions |
| **Conversion Rate (Clicks → Purchase)** | 5.21% | Room for optimization |
| **Purchase Rate (Impressions → Purchase)** | 0.61% | Weak lower-funnel efficiency |
| **Total Budget** | ₹2.5M | Total ad expenditure |
| **Avg. Budget per Campaign** | ₹50.7K | Indicates multiple campaign tests |


### 📈 Funnel Analysis
- **Impressions:** 216K → **Clicks:** 25.4K → **Purchases:** 1.3K  
- **CTR:** 11.76% (well above 1–2% industry average)  
- **Engagement Rate:** 13.56% (high audience interest)  
- **Conversion Rate:** 5.21% (clicks → purchase)  
- **Purchase Rate:** 0.61% (impressions → purchase)  

➡ **Insight:** Ads successfully attract and engage users, but conversion efficiency is low — likely due to **landing page friction**, **audience mismatch**, or **offer weakness**.  

---

### 👥 Demographic Insights
- **Females (43%)** engage almost twice as much as **males (22%)**.  
- **Age group 18–30** drives the majority of interactions.  
➡ Focus campaigns on **young female audiences** for maximum ROI.  

---

### 🌍 Geographic Insights
- Top engagement markets: **India, Brazil, and the US**.  
- High-value markets: **Germany and the UK** (better purchasing power).  
➡ Strategy: **High-volume campaigns** in India/Brazil and **premium targeting** in Germany/UK.  

---

### ⏰ Time & Seasonality
- Engagement peaks during **afternoons (3–8 PM)**.  
- Spikes observed around **19–21st and 25–27th**, likely due to promotions or product launches.  
➡ Schedule ad delivery during **peak hours** and **event-driven periods** for better ROI.  

---

### 🎥 Ad Type Performance
- **Video Ads** outperform all formats in CTR, conversion, and engagement.  
- **Story Ads** perform strongly; **Carousel/Image Ads** lag behind in conversions.  
➡ Shift more budget to **video and story formats** for improved conversion value.  

---

## 🧭 Recommendations

1. **Improve Conversion Funnel** – Optimize landing pages, CTAs, and offers.  
2. **Retarget Engaged Users** – Capture users who clicked but didn’t purchase.  
3. **Audience Focus** – Prioritize females aged 18–30 in India and Brazil.  
4. **Ad Format Optimization** – Allocate more budget to video and stories.  
5. **Time Optimization** – Schedule campaigns during afternoon & evening hours.  
6. **Budget Reallocation** – Move spend from low-performing regions to high-engagement ones.  

---



