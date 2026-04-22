Analysis of Douyin E-commerce User Consumption Characteristics & High-Value User Profiling

1. Problem & User 
This project analyzes demographic and behavioral data of Douyin e-commerce users to identify core consumption patterns and define high-value user traits, providing actionable insights for platform operators and merchants to implement targeted marketing and refined user operation strategies.

2. Data 
• Data source: Douyin e-commerce user behavior dataset
• Access date: 2026-04-22
• Sample size: 1000 records, 16 columns (no missing values)
• Key fields:
Demographics: User_ID, Age, Gender, Location, Income
Preferences: Interests, Product_Category_Preference
Behavior metrics: Last_Login_Days_Ago, Purchase_Frequency, Average_Order_Value, Total_Spending, Time_Spent_on_Site_Minutes, Pages_Viewed, Newsletter_Subscription

3. Methods 
1. Data loading & inspection: Load the dataset using Pandas, check data structure, missing values and basic statistics with df.info() and df.head().
2. Descriptive & exploratory analysis: Analyze the distribution of user gender, age and purchase frequency, and explore basic consumption patterns.
3. Data visualization: Use Matplotlib to plot user gender distribution pie chart, age distribution bar chart and purchase frequency histogram.
4. User segmentation: Compare spending level and purchase frequency across different age and gender groups to identify high-value user characteristics.

4. Key Findings 
Male users account for 52.6% and female users 47.4%, showing a relatively balanced gender structure.
Young and middle-aged adults are the main user group, with high concentration in platform activity and consumption.
Total spending is right-skewed: most users have moderate to low consumption, while a small number of high-value users contribute disproportionately to total revenue.
Users aged 25–40 show significantly higher purchase frequency and average order value, especially those interested in fashion and beauty categories.
Users with recent login, longer browsing time and higher page views tend to have stronger consumption willingness and spending power.

5. Product link / Demo
This is a local data analysis project based on Jupyter Notebook. The full analysis workflow, charts and user profiling results are included in the submitted notebook file.

6. Limitations & next steps
• Limitations:
The dataset lacks time-series trends and detailed regional information, limiting long-term trend analysis.
The relationship between user interests and actual purchase behavior has not been fully quantified.
Skewed spending data may affect the accuracy of user value classification without further outlier processing.
• Next steps:
Establish a formal RFM model to standardize high-value user identification.
Conduct deeper correlation analysis between user interests, product preferences and spending behavior.
Add more behavioral features to improve the precision of user segmentation and personalized marketing suggestions.
