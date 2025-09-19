Executive Summary

Ravenstack, a growing SaaS company, has engaged the company as a case client to enable an understanding of the current customer base and to allow prediction of churn. Data points from Accounts, Subscriptions, Feature Usage, Support Tickets, and Churn Events have been analyzed. It has been concluded that the lack of product feature usage is the strongest signal for churn, representing 19% of all churned accounts. This indicates that customers are leaving either due to missing desired functionality or difficulty using existing features.

Support experience and budget concerns are also significant, each contributing 17.3% of churn, together accounting for over a third of customer losses. Beta feature adoption has been identified as a key driver of retention, which aligns with product feature usage being the highest churn factor. This suggests that rolling out new features that customers want and ensuring their adoption can reduce churn and increase engagement.

Event-driven referrals bring the highest-value customers, generating the largest average MRR and exhibiting the lowest churn, making this channel a critical growth lever. Further information, such as customer lifetime value, segmentation, and detailed engagement timelines, would be required to validate the analysis and provide guidance on marketing spend by identifying the most valuable customers.

By incorporating more granular time-to-churn and user-level data, these insights could be refined, enabling more precise retention strategies, optimized product engagement, and data-driven marketing investments, thereby supporting sustained growth.

Churn Prediction

The analysis shows that product features are the leading driver of churn, representing 19% of all churned accounts. Customers are leaving either because the product lacks desired functionality or because they struggle to use existing features effectively.

<img width="545" height="520" alt="Image" src="https://github.com/user-attachments/assets/cd607731-cf6c-4d91-87d0-0089249ae9f0" />


Support experience and budget concerns follow closely, each contributing 17.3% of churn. These factors collectively account for over a third of customer losses, emphasizing that service quality and cost management are critical to retention. Other factors, like losing users to competitors (15.3%) and pricing (15.2%), are notable but less frequent contributors.

Incorporating time-to-churn and user-level engagement data is recommended to enable a deeper analysis of which signals usage patterns, support interactions, or pricing sensitivity most accurately predict churn. This would allow Ravenstack to design more targeted and effective retention strategies.

Beta Feature Adoption

Engagement with beta features correlates strongly with retention. Accounts that actively use beta features exhibit lower churn rates, indicating a higher commitment to the platform.
This finding reinforces that product feature usage is the strongest predictor of churn, as rolling out features desired by customers and encouraging their adoption directly reduces churn risk. Leveraging beta features as part of the product strategy can enhance overall engagement and loyalty.

Targeted campaigns to promote beta participation and systematic incorporation of beta learnings into core product development are recommended to further strengthen retention.

Revenue Cohort Analysis

Evaluating revenue contribution by referral source highlights significant differences in customer value and retention. Event referrals generate the highest average MRR at $280.15 and exhibit the lowest churn, making them the most strategic channel for growth. Partner referrals contribute $190.25 on average, paid ads $175.50, organic search $150.00, and other channels $125.75.

Referral Source-->Average MRR

Event Referral-->$280.15

Partner Referral-->$190.25

Paid Ads-->$175.50

Organic Search-->$150.00

Others-->125.75


Marketing and partnership strategies should prioritize event-driven referrals to maximize revenue and retention, while other channels can be optimized for cost efficiency and reach.

Upgrade Funnel by Industry

Progression from trial to paid and upgraded plans varies across industries. Certain industries demonstrate strong movement to higher tiers, while others remain concentrated in trial or entry-level plans.

Understanding these patterns allows targeted marketing and sales efforts to focus on industries with the greatest potential for upsell and higher revenue contribution. It is recommended that industries exhibiting high upgrade propensity be prioritized for conversion campaigns and cross-sell opportunities.

Methodology

The data was first cleaned and standardized, ensuring consistent formats for boolean and date fields, handling missing values, and removing duplicates. A comprehensive feature table was engineered at the account level, incorporating metrics such as total product usage, beta feature engagement, days since last usage, support ticket activity and resolution times, satisfaction scores, account age, plan tier, and monthly recurring revenue (MRR).

A logistic regression model was then trained on these features to predict churn. Logistic regression was chosen for its interpretability, enabling identification of which behavioral, support, and subscription characteristics most strongly correlate with churn. Features were standardized, and categorical variables, such as plan tier, were one-hot encoded.

Model performance was evaluated using accuracy, precision, recall, and AUC metrics, confirming that churn can be reasonably predicted using these signals. This provides a foundation for proactive customer engagement.

Use of AI in this Project

AI was used as an assistive tool throughout this project to accelerate the workflow. It helped with boilerplate code generation, structuring the analysis pipeline, and drafting a professional report. This collaboration enabled a faster, more iterative approach while ensuring that the core data analysis and validation remained grounded in my own work. 

Example prompts used: 

1. "Write a Python script to load and clean five CSV files: accounts.csv, subscriptions.csv, feature_usage.csv, support_tickets.csv, and churn_events.csv. Ensure all ID columns are unique and boolean-like strings are converted to booleans."

2. "Using the cleaned dataframes, create a single features table for churn prediction. Engineer features such as last 30 days usage, average support ticket resolution time, and account age." 

3. "Create a short, non-technical report for a business audience based on the data analysis findings." 

4. "Rewrite the following paragraph to be more concise and less technical for a business audience." 

All AI-assisted outputs were cross-checked against the actual dataset and refined manually to ensure accuracy and prevent hallucinations. 
