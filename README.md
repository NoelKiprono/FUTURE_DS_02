# FUTURE_DS_02
Facebook Ad Campaign Performance Dashboard
1. Project Overview
   
This project involves the creation of a comprehensive Power BI Dashboard to analyze the performance of a Facebook ad campaign. The goal was to visualize key performance indicators (KPIs), identify trends in audience demographics, and evaluate the cost-efficiency of different targeting strategies.

This dashboard provides a high-level view of ROI and conversion metrics while drilling down into specific age and gender segments to optimize future ad spend.

2. Key Performance Indicators (KPIs)
   
The dashboard tracks the following aggregate metrics to determine overall campaign health:

ROI: 49.1%

Total Spent: $19.62K

Total Approved Conversions: 585

Conversion Rate: 5.01%

Cost Per Acquisition (CPA): $33.54

Click-Through Rate (CTR): 0.01%

Cost Per Click (CPC): $1.68

Total Clicks: 12K

Total Impressions: 79M

3. Insights & Analysis 
Audience Demographics
Impressions by Age: The campaign reach was heavily skewed toward younger audiences. The 30-34 age group received the highest impressions (36M), while reach tapered off significantly for older groups (e.g., 7M for ages 45-49).

Conversions by Age: This reach strategy correlated with results; the 30-34 age group generated the highest volume of conversions (approx. 900), whereas the 45-49 group generated the least (<200).

Interest Segmentation
The audience was segmented into three interest categories, showing a nearly even distribution of engagement:

Interest 1: 19K (30.53%)

Interest 2: 22K (34.73%)

Interest 3: 22K (34.74%)

Targeting Efficiency (CPA Heatmap)
A custom matrix with conditional formatting was created to identify the most cost-effective demographics.

Most Efficient: Females aged 30-34 showed the best performance with a CPA of just $7.02. generally, the Female (F) demographic maintained a lower CPA across all age brackets compared to Males.

Least Efficient: Males aged 40-44 and 45-49 were the most expensive to convert, with CPAs rising as high as $57.40 and $57.92 for 45-49 Females respectively.

4. Technical Details
Tool Used: Microsoft Power BI

Data Modeling: Connected and transformed raw campaign data to create relationships between ad spend, clicks, and conversion tables.

DAX Measures: Created custom measures to calculate ratios such as:

CPA = SUM(Total Spent) / SUM(Total Approved Conversion)

CTR = SUM(Total Clicks) / SUM(Total Impressions)

ROI calculations based on revenue and spend.

Visualizations: Utilized Donut charts for interest distribution, Funnel charts for impressions hierarchy, and Heatmaps for cost-efficiency analysis.

5. Conclusion
The data suggests that the campaign is highly effective with the 30-34 Female demographic. To improve the overall ROI of 49.1%, future budget allocation should likely be shifted away from the high-CPA Male 40-49 segments and reinvested into the younger female segments where acquisition costs are significantly lower
 DASHOARD
<img width="634" height="335" alt="Intern Task 2" src="https://github.com/user-attachments/assets/0384c3af-d0ef-4a41-86d9-8fea4a61cc62" />
