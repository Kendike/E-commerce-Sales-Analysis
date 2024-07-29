# Ecommerce-Market-Analysis
# Overview
The e-commerce market is rapidly expanding, driven by increasing internet penetration, technological advancements, and changing consumer behaviors. To thrive in this competitive environment, businesses must understand product performance and customer preferences comprehensively. This project aims to analyze product performance and customer preferences within an e-commerce setting, leveraging data analysis techniques to derive actionable insights.
# Objectives
- Evaluate Product Performance: Assess the sales performance of various products over time, identifying top-selling products and categories.
- Understand Customer Preferences: Analyze customer reviews and ratings to gauge customer satisfaction and preferences.
- Identify Trends and Patterns: Detect seasonal trends and temporal patterns in product sales to forecast future performance.
- Predictive Modeling: Build models to predict future sales, aiding inventory management and marketing efforts.
  
# Data Source
  [kaggle](Kaggle.com)
# Tools
- Excel: For initial data cleaning, transformation, and basic analysis
- Tableau: For  data visualization, trend analysis, Predictive model
# Data Cleaning
- Data was first transformed from wide to long data using query feature on excel
- Fields were changed to the right format.
- Duplicates removed and missing values handled
  Data is now clean for analysis
# Exploratory Analysis
Generated summary statistics for numerical fields (Max, Min, mean, Standard Deviation) to have better understanding of the dataset.

|Metrics|Review Score|Price |Sales |Revenue |
|-------|----------|--------|------|--------|
Mean |3.0276|$247.7 |501.7| $124058.7|
Maximum| 5  |$499.86 | 1000 | $495300 |
Miniumum |1 | $7   |     0| 0     |
Standard Deviation | 1.17 |$144.5 | 288.2 | $110257

# Interpretation
   - The Highest recorded sale is 1000 units average sale is 501 and there was no salw for some months. A standard deviation of 288 shows significant variablity among products.
   - on the scale of 1 - 5. The average review score is 3. This shows customers have a moderate satisfasction level of the products and a standard deviation of 1.17 shows their is a moderate spread of how customers perceive diferent products. This is significant for strategic decsdion making.
  To further understand data spread of sales and review sacores I visualize the data with histogram.
![image](https://github.com/user-attachments/assets/11191280-eaec-4e4c-a07c-2dbff3bb9313)

![image](https://github.com/user-attachments/assets/ef7424b9-e41f-4a8d-bea0-b4931f3323d8)

From the above visuals is it clear that there is a good spread in the data among data points. This is in harmony with the insights from summary statistics.
Now that the data is understond we move to adavnce analysis. 

# Advance Analysis/Visualization

<img width="628" alt="E-commerce" src="https://github.com/user-attachments/assets/c7359a06-f8ce-4f4e-bbe8-55606aefdbf0">

# Insights
- Books leading the sales shows high demand and popularity
- Toys and sport trail in second and third position respctively shows a strong custmer base is interested in this category.
- The least performing product is home and kitchen.
- Books is also the highest revenue generator this makes books rthe best product for the company.
- Sports being second in revenue shows sports related products has significant financial impact
- The sales trend shows stability over the observed monthly period.
<img width="534" alt="E-Commerce 2" src="https://github.com/user-attachments/assets/ca203473-1b57-4871-9acc-4fd073e72f2d">

# Insights
- The scatter plot demonstrates a positive correlation between sales and review scores. As review scores increase, sales also tend to increase.
- The trend line provides a visual representation of this correlation, indicating that higher review scores are generally associated with higher sales.
- The predictive model for sales is represented by the broken line and the shaded area. The actual sales data is shown alongside the forecast.
- The actual sales trend appears relatively stable with slight fluctuations over the observed period.
- The forecasted values extend beyond the actual data points, indicating an estimated future trend. The forecast area shows an expected continuation of current sales levels, with a slight upward trend.

# Recommendation

Based on the analysis of product performance and customer preferences in the e-commerce market, the following recommendations are provided to enhance business strategies and drive growth.

-The mean revenue is $124,058.68, with a standard deviation of $110,257.11, suggesting significant variability. Focus on products and categories with high revenue potential and explore ways to maximize their profitability
- Focus on Review Scores: There is a clear positive correlation between review scores and sales. To leverage this, company should prioritize improving product quality and customer satisfaction. Implement feedback mechanisms to address customer concerns and continuously improve product offerings.
- Customer Feedback Integration: Regularly collect and analyze customer feedback to identify areas for improvement. Use this feedback to make informed decisions about product features and enhancements.
- Highlight Top-Performing Categories: Focus marketing efforts on the top-performing categories identified in the analysis (Books, Toys, Sports). Promote these categories through targeted campaigns to maximize sales and revenue.
- Utilize Predictive Models: The predictive model indicates stable or slightly increasing sales trends.  This information should be used for strategic planning in areas such as procurement, staffing, and marketing budgets.
- Revenue Analysis: Books, Sports, and Toys are the top revenue-generating categories. Invest in these categories by expanding product lines, improving quality, and offering exclusive deals.
- Upsell and Cross-Sell Opportunities: Identify opportunities to upsell and cross-sell within these high-revenue categories. Recommend related products to increase the average order value.
- Innovate Product Offerings: There should be regular review and innovate product offerings to stay ahead of market trends. Also Introduce new products and features that align with customer preferences and market demands.

# Limitation 
Cause of Average Performance: The current dataset does not provide detailed information on the factors influencing the average performance of products. It's unclear whether the performance is affected by pricing strategies, product quality, or customer service issues.
Customer Feedback: There is a lack of qualitative data, such as customer feedback and reviews, which could provide deeper insights into customer satisfaction and areas for improvement.








  
