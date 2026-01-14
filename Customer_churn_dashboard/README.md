# Customer Churn Analysis - Power BI Dashboard

## Dashboard Pages

### Customer Churn Dashboard
![Overview](/Customer_churn_Dashboard/Churn_PNG/Overview.png?raw=1)


##  Overview
This project delivers an end-to-end customer churn analysis using Power BI. The dashboard is designed to help stakeholders quickly understand churn levels, identify key drivers, highlight high-risk customer segments, and surface geographic outliers that require intervention.

The project is suitable for executive decision-making, stakeholder handover, and portfolio demonstration.

## Business Objective
- Understand overall customer churn
- Identify primary drivers contributing to churn
- Detect high-risk customer segments
- Highlight geographic regions with abnormal churn
- Support data-driven retention strategies

##  Key Insights
### Overall Trends
- Customer churn stands at approximately 27%, indicating a significant retention opportunity.

### Primary Drivers
- Competitive pressure is the leading reason customers churn.
- Customers on monthly contracts churn at significantly higher rates than those on longer-term agreements.

### High-Risk Segments
- Early-tenure customers are more likely to churn.
- Customers paying for an international plan without international usage exhibit extremely high churn, suggesting low perceived value.
- Unlimited plan customers using less than 5GB of data churn more frequently than higher-usage customers.

### Geographic Insights
- California is a critical outlier, with churn exceeding 60%, warranting focused regional analysis.

## Business Impact
- Strengthen onboarding and early engagement for new customers.
- Reevaluate international plan pricing, positioning, and customer education.
- Introduce right-sized or lower-cost plans for low-usage unlimited customers.
- Investigate competitive dynamics and market conditions in California.

## Data
- Source: Public dataset
- Rows: 6,688
- Features include: Custtomer ID, Churn Label, Account Length, Local calls, Int Calls, Intl Active, Extra data charges, Age, State, Churn Reason etc.

## Tools & Techniques
- Power BI Desktop
- DAX (measures, time intelligence)
- Interactive slicers and drill-through

## Files
- `Customer_churn.pbix` – Main Power BI report
- `Churn_PNG/Screenshots` – Static export
- `Databel.csv` – Source dataset

## Assumptions & Limitations
- Analysis is based on historical customer data available at the time.
- Churn reasons rely on recorded customer feedback and may not capture all contributing factors.
- Usage thresholds and segments are defined based on observed behavioral patterns.


### Author

Vivian Orekunrin-Gold
Data Scientist | Analytics & BI

