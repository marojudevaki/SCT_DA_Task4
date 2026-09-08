# SCT_DA_Task4

## Task 4: Business Insights Report (EDA)

Performed Exploratory Data Analysis (EDA) on a marketing campaign dataset to identify the most effective marketing channels based on ROI, revenue, and conversions.

### Objective
Analyze marketing campaign performance, visualize the marketing funnel, compare channel performance, and recommend which channels should receive more budget.

### Data Preparation
- Loaded the marketing campaign dataset using Python and Pandas.
- Checked for missing values.
- Checked for duplicate records.
- Converted Start_Date and End_Date into datetime format.
- Validated the cleaned dataset.

### EDA Performed
- Dataset summary and descriptive statistics
- Marketing funnel analysis
- ROI comparison by marketing platform
- Marketing spend vs revenue comparison
- Leads and conversions by platform
- Conversion rate analysis

### Key Findings
- Email had the highest calculated ROI at approximately 634.43%.
- Instagram had the second-highest calculated ROI at approximately 485.22%.
- Email generated the highest revenue and conversions.
- Google Ads ranked third based on calculated ROI.

### Recommendations
- Increase budget priority for Email campaigns.
- Gradually increase investment in Instagram campaigns.
- Continue Google Ads as a supporting channel.
- Optimize lower-performing channels before increasing their budgets.

### Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

### Files
- `SCT_DA_Task4.ipynb` – EDA notebook
- `campaign_data.csv` – Original dataset
- `cleaned_campaign_data.csv` – Cleaned dataset
- `marketing_business_insights.csv` – Platform performance analysis
- `Business_Insights_Report.txt` – Business insights report
