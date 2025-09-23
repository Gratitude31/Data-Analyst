# **Project Background**

This project uses the Telco Customer Churn dataset from Kaggle, which includes customer account information, demographics, subscribed services, billing details, and churn status.

For this analysis, I frame it as a case study of a telecommunications company that provides internet, phone, and streaming services. The company operates primarily on a monthly subscription model, generating revenue from recurring service charges.

Recently, the company has observed an increase in customer cancellations (churn). Because churn directly affects revenue and customer lifecycle, management has requested an in-depth analysis to:

  1. Understand the key drivers of churn

  2. Identify high-risk customer segments

  3. Recommend actionable strategies to improve retention

As the data analyst, my role is to deliver data-driven insights that management can use to design effective retention campaigns and strengthen long-term customer loyalty.

# **Data Cleaning & Preparation**

* Data inspection, cleaning, and transformation were performed using Power Query in Power BI.
* Steps included:
  * Text cleaning (trimmed and standardized service categories).
  * Data type conversions (e.g., TotalCharges from text to numeric).
  * Feature creation:
    * AverageMonthlySpend = TotalCharges ÷ max(Tenure, 1)
    * TenureGroup bucketed as:
      * 0–12 months
      * 13–24 months
      * 25+ months
* Removed duplicate records (none found).
* Checked for negative or out-of-range values in key financial columns (none detected).

# **Interactive Dashboard**

The interactive Power BI dashboard enables stakeholders to:
* Explore churn trends across demographics, contract types, services, and billing methods.
* Drill down by customer segment for targeted retention planning.
👉 Power BI Dashboard Link (insert link if published online)

# **Key Analysis Categories**

Insights and recommendations are organized around these areas:
* Category 1: Customer Demographics (e.g., senior citizens, gender distribution)
* Category 2: Services Subscribed (phone, internet, multiple lines)
* Category 3: Contract & Billing (monthly vs. long-term contracts, payment methods)
* Category 4: Financial Metrics (MonthlyCharges, AverageMonthlySpend, TotalCharges)

The data inspection and cleaning steps were performed in Excel, including initial checks for missing values, outliers, and basic transformations.

The interactive Power BI dashboard, which allows stakeholders to explore churn trends and drill down by customer segment, can be accessed here: [Power BI Dashboard Link]

Data Structure & Initial Checks

The companies main database structure as seen below consists of four tables: table1, table2, table3, table4, with a total row count of X records. A description of each table is as follows:

Table 2:
Table 3:
Table 4:
Table 5:
[Entity Relationship Diagram here]

Executive Summary
Overview of Findings
Explain the overarching findings, trends, and themes in 2-3 sentences here. This section should address the question: "If a stakeholder were to take away 3 main insights from your project, what are the most important things they should know?" You can put yourself in the shoes of a specific stakeholder - for example, a marketing manager or finance director - to think creatively about this section.

[Visualization, including a graph of overall trends or snapshot of a dashboard]

Insights Deep Dive
Category 1:
Main insight 1. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 2. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 3. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 4. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 1]

Category 2:
Main insight 1. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 2. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 3. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 4. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]

Category 3:
Main insight 1. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 2. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 3. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 4. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]

Category 4:
Main insight 1. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 2. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 3. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

Main insight 4. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]

Recommendations:
Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following:

Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

Assumptions and Caveats:
Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)

Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)

Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
