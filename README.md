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
Category 1: Customer Demographics (e.g., senior citizens, gender distribution)

Main Insight 1
  * Observation: The segment with the highest churn rate is Senior Citizen, Female, without Dependents or Partner, at 49.48%, followed closely by the same segment for Male, at 48.36%.
  * Interpretation: Older customers who are single and have no dependents are the most likely to leave the service.
  * Supporting Analysis: Across the Small Multiples chart (4 panels: Senior/Non-Senior × Male/Female), this segment consistently shows the tallest bars, indicating persistent churn risk.

Main Insight 2
  * Observation: Customers without a Partner or Dependents have the highest churn rates, while those with either or both have the lowest churn.
  * Quantitative Values:
    * “Neither” segment: ~30–49% churn
    * “Partner Only”, “Dependents Only”, or “Partner + Dependents” segments: 12–37% churn
  * Interpretation: Household connections (partner or dependents) appear correlated with higher retention

Main insight 3
  * Observation: Gender differences exist but are minor compared to household status.
  * Quantitative Comparison: Female Senior Citizens without Partner/Dependents: 49.48%; Male Senior Citizens without Partner/Dependents: 48.36%.
  * Interpretation: While females in this demographic have slightly higher churn, the primary driver remains the absence of dependents or partner.

![Customer Demographics Small Multiples](images/Category1_Demographics.png)

Main Insight 1 – Customer Base Profile
  * The primary services are Phone, Internet, and Value-Added Services (VAS), covering ~7,000 customers in total.

Main Insight 2 – Overall vs. Key Service Churn
  * Overall churn rate: 26.54%
  * Customers with Fiber Internet show a much higher churn rate of 41.89%, suggesting stronger competition or service dissatisfaction.
  * Those with Multiple Lines also have an elevated churn rate of 28.61%, slightly above the overall average.

Main Insight 3 – Internet Service Effect
  * Customers without Internet service have the lowest churn at only 7%, highlighting internet-related services as a primary churn driver.

Main Insight 4 – Service-Specific Risk
  * Customers with Multiple Lines churn at a rate similar to those with no Phone service, signaling that extreme ends of service adoption (none vs. many) both present risk.
  * Among value-added services, Streaming TV exhibits the highest churn rate at 30%, making it the most vulnerable VAS segment.

![ServicesSubscribed](images/Category2_ServicesSubscribed/png)

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
