📊 FUTURE_DS_02 — Social Media Ad Campaign Performance Dashboard (Power BI)

🔍 Project Overview

This project is part of Future Interns – Data Science & Analytics Task 2, where I analyzed social media ad campaign data and built multiple interactive dashboards using Power BI.
The goal was to evaluate campaign performance, engagement, cost efficiency and ROI, with a focus on improving ad decision-making and optimization strategies.

🎯 Business Objective

Identify which audiences, channels and campaign goals perform best, and derive insights that can:

Reduce ad spending wastage

Improve click-through and conversion rates

Increase overall return on investment

Support data-driven marketing decisions

📁 Dataset Description

The dataset contains Instagram/Facebook advertising campaign data with the following fields:

Column	Description
Campaign_ID	Unique campaign reference
Target_Audience	Audience segment targeted
Campaign_Goal	Marketing objective
Channel_Used	Social platform (e.g., Instagram)
Impressions	Total ad views
Clicks	Total ad clicks
Conversion_Rate	Rate of conversions from clicks
Acquisition_Cost	Cost of acquiring a converted user
ROI	Return on investment ratio
Engagement_Score	Interaction level
Location	Region targeted
Language	Preferred audience language
Date	Campaign run date
🧮 Data Enhancements (Calculated Columns)

To improve campaign analytics, the following new calculated columns were added:

Column	Formula	Purpose
Conversions	Clicks × Conversion_Rate	Actual conversion count
Spend	Conversions × Acquisition_Cost	Total money spent
Revenue	Spend × (1 + ROI)	Earnings estimation
CTR	Clicks ÷ Impressions	Click-through rate
EngagementRate	Engagement_Score ÷ Impressions	Engagement efficiency
CPC	Spend ÷ Clicks	Cost per click
CPM	(Spend ÷ Impressions) × 1000	Cost per 1000 impressions
ROI_Percent	(Revenue − Spend) ÷ Spend	Profitability score
🛠 Tools Used
Tool	Purpose
Power BI Desktop	Data modeling & dashboards
Power Query	Data cleaning
DAX	Calculated columns & measures
GitHub	Version & project presentation
📊 Dashboard Breakdown
1️⃣ Executive Performance Dashboard

Purpose: Business-level KPIs
Includes: Spend, Revenue, CTR, ROI, Trend Analysis, Channel Comparison

2️⃣ Audience & Targeting Insights Dashboard

Purpose: Identify best-responding segments
Includes: Audience breakdown, engagement vs conversions, scatter plot, heat tables

3️⃣ Campaign Optimization Dashboard

Purpose: Investment decision support
Includes: Spend vs Revenue, ROI performance, waterfall, efficiency table

🔍 Key Insights (Sample Findings)

(Replace with your real findings after reviewing visuals)

Certain audience groups show high engagement but low conversion, indicating a targeting mismatch

Instagram-focused campaigns delivered better CTR than other channels

Some campaigns generated positive ROI at lower spend, suggesting scalable opportunities

A few campaigns require budget re-allocation or creative redesign

📌 Conclusion

This project demonstrates how social media ad campaign performance can be analyzed using Power BI by combining marketing metrics + data modeling + visual storytelling, resulting in clear, actionable insights for digital marketers.

🚀 Future Improvements

Add UTM tracking data

Integrate real-time API for live dashboards

Predictive conversion modelling using ML

Segmentation clustering

🤝 Acknowledgement

This project was completed as part of Future Interns Data Science & Analytics Challenge – Task 2, focusing on data interpretation, dashboard design, and performance storytelling.
