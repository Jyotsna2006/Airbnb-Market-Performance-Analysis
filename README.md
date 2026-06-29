# Airbnb-Market-Performance-Analysis (Power BI)
An interactive Power BI dashboard analyzing global hospitality market trends, pricing structures, and customer insights. Built with advanced DAX modeling and clean data transformations to serve as an executive business intelligence tool.

# Airbnb Global Performance Analysis Dashboard

#📊 Dashboard & Project Access

- **🚀 Live Interactive Dashboard:** [View Live Report Here](https://app.powerbi.com/view?r=eyJrIjoiZmZlOGZkMGMtNWY2Zi00NGQ3LWEzNzQtMDZjNjU1MDM2ODU1IiwidCI6ImRkM2U0NjExLWJlMjktNDg2ZC05ODdkLTViYjE2NzEwZjBhZCJ9)
- **🎬 Presentation & Walkthrough Video:** [Watch Video Here](INSERT_YOUR_LINKEDIN_VIDEO_LINK_HERE)
- **💾 Open-Source Dataset:** [Access Maven Analytics Dataset Here](https://mavenanalytics.io/data-playground/airbnb-listings-reviews)
- **📂 Power BI Project File:** Uploaded directly to this repository as a `.pbix` file (download to view full technical configurations and modeling).

---

## 📸 Executive Dashboard Landing Page
![Home Page](Home_Page.png)

---
## 📌 Problem Statement
Raw hospitality marketplace data containing over 250,000 global short-term rental listings and 5 million historical reviews presents a critical barrier for stakeholders: without a unified business intelligence layer, core operational metrics remain trapped in data silos. Marketplace managers and real estate investors struggle to isolate localized supply anomalies, identify critical property price drivers, map seasonal consumer interest waves, or evaluate cross-city travel value accurately. 

This project bridges that business gap by directly answering the foundational challenge questions proposed by Maven Analytics and scaling the dashboard architecture into a custom, data-driven pricing optimization platform.

---
## 📋 Recommended Tasks & Applied Solutions

Here is how each standard operational requirement was successfully analyzed, mapped, and solved within the interactive dashboard:

### 1. Cross-City Market Variance Mapping
* **The Business Challenge:** *Can you spot any major differences in the Airbnb market between cities?*
* **The Applied Solution:** Architected a dual-layered market breakdown using a Pareto distribution to evaluate total supply alongside localized performance patterns. The dashboard highlights that Paris, New York, and Sydney generate nearly 50% of all platform listings and 48% of global customer feedback reviews. Concurrently, the operational analysis reveals that Mexico City and Rio de Janeiro lead the platform in absolute traveler satisfaction ratings, while subcategories like **Cleanliness** and **Value for Money** represent recurring operational weaknesses across most baseline cities.

### 2. Core Pricing Drivers Assessment
* **The Business Challenge:** *Which attributes have the biggest influence on price?*
* **The Applied Solution:** Designed an inventory pricing baseline that structures average listings against specific accommodation types. The analysis explicitly demonstrates that property type and accommodation capacity exert the highest statistical impact on price variance. Hotel rooms command the highest platform premium at an average price of $800, followed by entire homes at $673, whereas private room alternatives establish the competitive baseline floor at $462.

### 3. Seasonality & Review Trend Extraction
* **The Business Challenge:** *Are you able to identify any trends or seasonality in the review data?*
* **The Applied Solution:** Built a seasonal time-series matrix utilizing a 100% stacked area flow visualization to isolate macro travel waves across calendar months. The dataset successfully exposes distinct, localized seasonal booking spikes: Paris and Rome experience heavy travel review peaks from April through August, whereas New York experiences an isolated demand spike during November and December.

### 4. Travel Value Optimization Analysis
* **The Business Challenge:** *Which city offers a better value for travel?*
* **The Applied Solution:** Created a multidimensional cross-comparison matrix mapping average overall ratings directly against average property pricing structures. The data identifies **Paris** as a primary market leader in volume and user engagement, but proves that high customer demand in this region is tightly linked to cost savings—as traditional hotel options command rates nearly twice the cost of a comparable Airbnb listing.

---

## 🔸 Self-Driven Independent Objectives (My Custom Extensions)

Beyond the standard challenge questions, the dashboard introduces a brand-new, self-driven analytical module built to extract deep revenue insights:

### 5. Advanced Price & Room Analysis Architecture
* **The Core Insight:** Independently conceptualized and engineered a new analytical module tracking the cross-section of guest capacity limits against structural property pricing. The data proves that while standard property rates scale in a highly predictable, steady line for smaller groups of 1 to 6 guests, major pricing premiums suddenly manifest at even-numbered accommodation capacities of **10, 12, and 14 guests**. This reveals a highly lucrative, high-margin premium segment tailored for luxury group stays.

### 6. Inventory Mix & Market Share Modeling
* **The Core Insight:** Built an independent distribution model using custom-segmented room type parameters to determine platform dominance. The model exposes an **Entire Home Dominance** across the global ecosystem at 65%, highlighting a massive traveler preference for complete space privacy. Simultaneously, it isolates private room inventory at a solid 31% market share, demonstrating its role as a vital financial safety net for budget-conscious solo travelers.
