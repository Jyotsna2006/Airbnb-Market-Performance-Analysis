# Airbnb-Market-Performance-Analysis (Power BI)
An interactive Power BI dashboard analyzing global hospitality market trends, pricing structures, and customer insights. Built with advanced DAX modeling and clean data transformations to serve as an executive business intelligence tool.

# Airbnb Global Performance Analysis Dashboard

#📊 Dashboard & Project Access

- **🚀 Live Interactive Dashboard:** [View Live Report Here](https://app.powerbi.com/view?r=eyJrIjoiZmZlOGZkMGMtNWY2Zi00NGQ3LWEzNzQtMDZjNjU1MDM2ODU1IiwidCI6ImRkM2U0NjExLWJlMjktNDg2ZC05ODdkLTViYjE2NzEwZjBhZCJ9)
- **🎬 Presentation & Walkthrough Video:** [Watch Video Here](INSERT_YOUR_LINKEDIN_VIDEO_LINK_HERE)
- **💾 Open-Source Dataset:** [Access Maven Analytics Dataset Here](https://mavenanalytics.io/data-playground/airbnb-listings-reviews)
- **📂 Power BI Project File:** Uploaded directly to this repository as a `.pbix` file (download to view full technical configurations and modeling).

---
## 📌 Problem Statement
Raw marketplace data containing over 250,000 global short-term rental listings and 5 million historical reviews presents a critical business barrier for stakeholders: without a unified business intelligence environment, core operational metrics remain trapped in silos. Marketplace managers and real estate investors struggle to isolate localized market anomalies, identify critical property price factors, map seasonal consumer interest, or rank cross-city travel value accurately. 

This project bridges that gap by directly answering the foundational challenge questions from Maven Analytics and scaling the dashboard into a custom, data-driven pricing optimization platform.

---

## 📋 Recommended Tasks & Applied Solutions

Here is how each standard operational requirement was successfully analyzed, mapped, and solved within the interactive dashboard:

### 1. Cross-City Market Variance Mapping
* **The Business Challenge:** *Can you spot any major differences in the Airbnb market between cities?*
* **The Applied Solution:** Architected a dual-layered market breakdown using a Pareto distribution to evaluate total supply alongside localized performance patterns. The dashboard highlights that Paris, New York, and Sydney generate nearly 50% of all platform listings and 48% of global customer feedback reviews. Concurrently, the operational analysis reveals that Mexico City and Rio de Janeiro lead the platform in absolute traveler satisfaction ratings, while subcategories like **Cleanliness** and **Value for Money** represent recurring operational weaknesses across most baseline cities.

#### 📸 Market Overview Reference:
![Market Overview](Market_Overview_2.png)

---

### 2. Core Pricing Drivers Assessment & 4. Travel Value Optimization Analysis
* **The Business Challenge:** *Which attributes have the biggest influence on price?* & *Which city offers a better value for travel?*
* **The Applied Solution:** Designed an inventory pricing baseline that structures average listings against specific accommodation types. The analysis explicitly demonstrates that property type and accommodation capacity exert the highest statistical impact on price variance. Hotel rooms command the highest platform premium at an average price of $800, followed by entire homes at $673, whereas private room alternatives establish the competitive baseline floor at $462. The data identifies **Paris** as a primary market leader in volume and user engagement, but proves that high customer demand in this region is tightly linked to cost savings—as traditional hotel options command rates nearly twice the cost of a comparable Airbnb listing.

#### 📸 Ratings & Value Reference:
![Ratings Analysis 1](Ratings1_2.png)
![Ratings Analysis 2](Ratings2_2.png)

---

### 3. Seasonality & Review Trend Extraction
* **The Business Challenge:** *Are you able to identify any trends or seasonality in the review data?*
* **The Applied Solution:** Built a seasonal time-series matrix utilizing a 100% stacked area flow visualization to isolate macro travel waves across calendar months. The dataset successfully exposes distinct, localized seasonal booking spikes: Paris and Rome experience heavy travel review peaks from April through August, whereas New York experiences an isolated demand spike during November and December.

#### 📸 Reviews & Seasonality Reference:
![Reviews and Seasonality](Reviews_2.png)

---

## 🔸 Self-Driven Independent Objectives (My Custom Extensions)

Beyond the standard challenge questions, the dashboard introduces a brand-new, self-driven analytical module built to extract deep revenue insights:

### 5. Advanced Price & Room Analysis Architecture
* **The Core Insight:** Independently conceptualized and engineered a new analytical module tracking the cross-section of guest capacity limits against structural property pricing. The data proves that while standard property rates scale in a highly predictable, steady line for smaller groups of 1 to 6 guests, major pricing premiums suddenly manifest at even-numbered accommodation capacities of **10, 12, and 14 guests**. This reveals a highly lucrative, high-margin premium segment tailored for luxury group stays.

#### 📸 Custom Price & Room Analysis Reference:
![Price and Room Analysis](Price_Room_Analysis_2.png)

### 6. Inventory Mix & Market Share Modeling
* **The Core Insight:** Built an independent distribution model using custom-segmented room type parameters to determine platform dominance. The model exposes an **Entire Home Dominance** across the global ecosystem at 65%, highlighting a massive traveler preference for complete space privacy. Simultaneously, it isolates private room inventory at a solid 31% market share, demonstrating its role as a vital financial safety net for budget-conscious solo travelers.
