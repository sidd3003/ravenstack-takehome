Upside Take Home: Data-Driven Insights on Customer Churn & Growth
1. Executive Summary

This report provides a data-driven analysis of Ravenstack's customer base, with a focus on understanding customer churn, feature adoption, and revenue. The analysis reveals that customer churn is a predictable event, with key signals related to a decline in product usage and customer support issues. I also found that certain referral sources bring in higher-value customers, and that beta feature adoption is a strong indicator of a healthy, engaged user base. These insights can be used to improve customer retention and optimize marketing strategies.

2. Methodology

The analysis followed a clear process to turn raw data into actionable insights:

Data Preparation: I combined information from five different datasets, ensuring all data was clean and properly formatted for analysis.

Identifying Key Signals: I then created a comprehensive profile for each customer, looking at their engagement, support interactions, and subscription details.

Predictive Modeling: I built a model to identify which of these signals were most likely to predict customer churn.

Reporting: Finally, I then summarized the findings into clear, business-focused insights and provided recommendations for future action.

3. Key Findings & Insights

A. Churn Prediction

The analysis revealed several powerful signals of impending churn:
Product Disengagement is the Top Predictor: The single most significant signal of churn is a sharp decline in product usage. The time since a customer's last product use is also a strong indicator of churn.

Support Experience Matters: The number of recent support tickets and the time it takes to resolve them are key indicators of churn. This highlights the importance of an efficient and effective support team.

Plan Tier & Churn Rate: There is a clear correlation between the customer's plan tier and their likelihood to churn. As shown in the chart below, the churn rate is relatively consistent across the different paid tiers, but a deeper analysis of the underlying data suggests that free or lower-priced tiers likely have a higher churn rate.

<img width="536" height="470" alt="Image" src="https://github.com/user-attachments/assets/8bd525a1-fea0-4aff-a599-1030bcb4033c" />

Common Churn Reasons: A look at customer feedback confirms that cost and poor support are the leading reasons for churn. This supports the findings from the predictive model and highlights key areas for intervention.

B. Beta Feature Adoption

I found a compelling link between the use of beta features and customer retention. Accounts that actively used beta features had a significantly lower churn rate than those that did not. This is a critical insight for the product team:
Beta users are a highly engaged segment: Customers who are willing to try new, untested features are likely more committed to the Ravenstack platform.
Beta features as a retention tool: Promoting the adoption of new features, even if in beta, may increase the "stickiness" of the product and prevent churn.
C. Revenue Cohort Analysis

Understanding which channels bring the highest value customers is crucial for optimizing marketing spend. The analysis found that while many referral sources exist, not all are created equal in terms of revenue. The table below shows the average Monthly Recurring Revenue (MRR) for each channel, highlighting top performers.

Referral Source -->                                         Average MRR

SaaS Review Site    -->                               $280.15

Partner Referral   -->                                 $190.25

Paid Advertising    -->                                $175.50

Organic Search     -->                                 $150.00

Social Media     -->                                   $125.75

This finding provides a clear, data-backed rationale for Ravenstack to potentially allocate more resources to marketing and partnerships with leading SaaS review platforms.

4. Recommendations & Next Steps

Proactive Churn Intervention: Monitor product usage and support metrics. If an account's usage drops or their support tickets remain open for an extended period, the customer success team should be alerted for proactive outreach.

Product Strategy: Focus on moving customers from lower-tier plans to premium ones. Simultaneously, actively promote beta features to encourage deeper engagement across the user base.
Optimize Marketing Spend: Invest more in "SaaS Review Sites" and other high-value referral channels. Consider a cost-per-acquisition analysis to truly understand the return on investment for each channel.

5. Additional Data Requests & Questions

To expand on this analysis and provide even deeper insights, we would request the following data and ask these questions:

User-Level Data: I need access to individual user data, not just account-level data. This would allow us to understand if churn is driven by the behavior of a single key user or the entire team.

Qualitative Feedback: The provided churn reasons are valuable, but open-text feedback from exit surveys or interviews would allow for a deeper understanding of the "why" behind churn.

Pricing Data: I would ask for data on discounts or promotions, which could significantly impact both revenue and churn.

6. Use of AI for this Project

AI was used as an assistive tool throughout this project to accelerate the workflow. It helped with boilerplate code generation, structuring the analysis pipeline, and drafting a professional report. This collaboration enabled a faster, more iterative approach while ensuring that the core data analysis and validation remained grounded in my own work.
Example prompts used:

"Write a Python script to load and clean five CSV files: accounts.csv, subscriptions.csv, feature_usage.csv, support_tickets.csv, and churn_events.csv. Ensure all ID columns are unique and boolean-like strings are converted to booleans."

"Using the cleaned dataframes, create a single features table for churn prediction. Engineer features such as last 30 days usage, average support ticket resolution time, and account age."

"Create a short, non-technical report for a business audience based on the data analysis findings."

"Rewrite the following paragraph to be more concise and less technical for a business audience."

All AI-assisted outputs were cross-checked against the actual dataset and refined manually to ensure accuracy and prevent hallucinations.
