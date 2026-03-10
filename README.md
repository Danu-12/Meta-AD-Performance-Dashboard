# Meta Ads Performance Dashboard

Running paid advertising campaigns on platforms like Facebook and Instagram has become increasingly competitive and expensive. Marketing teams must ensure that their ad spend reaches the right audience segments, drives meaningful engagement, and ultimately leads to conversions such as clicks, purchases, or sign-ups.

However, with multiple campaigns, ad formats, and audience segments running simultaneously, it becomes difficult for marketing teams to quickly identify which campaigns are actually driving performance and which are wasting budget.

---

## Project Overview

This project analyzes over 80,000 Meta advertising performance records to evaluate the effectiveness of paid campaigns across key marketing funnel stages—engagement, clicks, and conversions. The analysis focuses on three **North Star metrics: Engagement Rate, Click-Through Rate (CTR), and Conversion Rate**, supported by additional metrics such as impressions, clicks, likes, shares, comments, and purchases.

To uncover deeper insights, campaign performance is analyzed across multiple dimensions including:     
  * **User demographics (Age, Gender)**
  * **Ad formats**
  * **Time of day**

By combining these metrics and dimensions into a structured performance view, the dashboard enables marketing teams to:
  * Identify high-performing audience segments
  * Compare campaign performance
  * Detect underperforming ads
  * Make data-driven decisions to optimize ad spend and improve campaign effectiveness

**This dashboard helps marketing teams answer questions such as:**

  * Which campaigns generate the highest CTR and conversions?
  * Which audience demographics engage the most with ads?
  * Which ad formats drive better engagement and purchases?
  * What time of day delivers the best campaign performance?

---
##  Data Structure

![Data_Structure](https://i.postimg.cc/4NzW4DLk/datastr.png)

---
## Executive Summary

Campaign performance shows **strong top-of-funnel engagement**, with an **Engagement Rate of 13.56%** and a** CTR of 11.76%**, indicating ad creatives are highly effective at capturing user attention & driving clicks. The overall **Purchase Rate remains low at 0.61%** of impressions, revealing a drop-off in the lower stage of the conversion funnel. 

Audience behavior highlights **young adults (20–30 age group) as  most responsive segmen**t, with engagement declining noticeably among audiences aged 35 and above. **Female audiences consistently show higher engagement** than males, indicating stronger resonance with this demographic.

Regionally, **India and the United States demonstrate strong engagement and reach,** while Germany and the United Kingdom show relatively stronger conversion potential, likely driven by higher purchasing power.

Among creative formats, **Story ads generate the highest impressions and conversion**, while Images and Videos higher enegaement and CTR, suggesting that multi-visual ad formats may be more effective in encouraging purchase decisions.

---
## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Main data visualization platform used for report creation
* 📂 **Power Query** – Data transformation and cleaning layer for reshaping raw ad data
* 🧠 **DAX (Data Analysis Expressions)** – Used for calculated KPIs such as engagement rate, CTR, and performance comparisons
* 🧩 **Data Modeling** – Relationships built between campaign, audience, and performance tables for accurate filtering and aggregation
* 📁 **File Formats** – `.pbix` for development and `.png` for dashboard previews

---

## 📂 Data Source

**Source:** Meta Ads Manager (Exported / Simulated Campaign Data)

The dataset includes structured advertising performance data such as:

* Campaign and Ad IDs
* Impressions and Reach
* Engagement metrics (clicks, likes, interactions)
* Audience segmentation attributes
* Time-based performance indicators

All data was cleaned and optimized using Power Query before visualization.

---

## 🚀 Features & Highlights

### 🔍 Business Problem

Raw data exports from Meta Ads Manager are difficult to analyze quickly and do not provide clear insights for decision-making. Marketing teams often face challenges in:

* Identifying high- vs low-performing campaigns
* Understanding audience engagement behavior
* Tracking campaign trends over time
* Reducing repetitive manual reporting

---


### 📊 Walkthrough of Key Visuals

**Key KPI Section (Top Panel):**

* Total Impressions
* Total Engagements
* Engagement Rate
* Number of Active Campaigns
* Average Performance Metrics

Provides an instant snapshot of overall ad performance.

**Campaign Performance Comparison (Bar / Column Charts):**

* Visual comparison of impressions and engagement across campaigns
* Helps identify top-performing and underperforming ads

**Time-Based Trend Analysis (Line Charts):**

* Shows impressions and engagement trends over time
* Useful for spotting spikes, drops, and campaign effectiveness

**Audience & Segmentation Insights:**

* Engagement breakdown by audience segments
* Helps identify which audience groups respond best to ads

**Engagement Distribution Analysis:**

* Highlights campaigns or creatives driving maximum user interaction

---

### 📈 Business Impact & Insights

* **Campaign Optimization:** Faster identification of high-performing ads enables continuous optimization
* **Time Efficiency:** Automated reporting reduced manual analysis effort by approximately **40%**
* **Improved Targeting:** Audience insights support more precise marketing strategies
* **Data-Driven Decisions:** Stakeholders can make informed decisions on budget allocation and campaign scaling

---

## Dashboard Preview

![Dashboard Preview](https://github.com/Danu-12/Meta-AD-Performance-Dashboard/blob/main/Meta%20AD%20Performance%20Dashboard.gif)



---


