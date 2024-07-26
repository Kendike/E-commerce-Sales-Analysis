# E-commerce-Market-Sales-Analysis
# Overview
The e-commerce market is rapidly expanding, driven by increasing internet penetration, technological advancements, and changing consumer behaviors. To thrive in this competitive environment, businesses must understand product performance and customer preferences comprehensively. This project aims to analyze product performance and customer preferences within an e-commerce setting, leveraging data analysis techniques to derive actionable insights.
# Objectives
- Evaluate Product Performance: Assess the sales performance of various products over time, identifying top-selling products and categories.
- Understand Customer Preferences: Analyze customer reviews and ratings to gauge customer satisfaction and preferences.
- Identify Trends and Patterns: Detect seasonal trends and temporal patterns in product sales to forecast future performance.
- Predictive Modeling: Build models to predict future sales and customer preferences, aiding inventory management and marketing efforts.
  # Data Source
  
# Tools
- Excel: For initial data cleaning, transformation, and basic analysis
- Tableau: For advanced data visualization, trend analysis, Predictive model
# Data Cleaning
- Data was first transformed from wide to long data using query feature on excel
- Fields was changed to the right format
- Duplicates removed and missing values handled
# Exploratory Analysis
Generated summary statistics for numerical fields (Max, Min, mean, Standard Deviation)
SUMMARY STATISTICS 				
Metrics	Review Score	Price	Sales	Revenue
Mean	3.0276	247.67713	501.6593333	124058.6819
Maximum	5	499.86	1000	495300
Minimun	1	7.29	0	0
Standard Deviation	1.170657183	144.5356611	288.1655744	110257.1121
![image](https://github.com/user-attachments/assets/ceb4dd60-ddc1-4a9a-b006-7e3f109824aa)

- Interpretation
   - The highgest recorded sale is 1000 units aveage sale is 501 and there was no salwe in some months. A standard deviation of 288 shows significant variablity among products.
   - on the scale of 1 - 5. The average review score is 3. This shows customers have a moderate satisfasction level of the products and a standard deviation of 1.17 shows their is a mnoderate spread of how customers perceive diferent products. This is significant for strategic decsdion making.
  To further understand data spread of sales and review sacores I visualize the data with histogram.
![image](https://github.com/user-attachments/assets/11191280-eaec-4e4c-a07c-2dbff3bb9313)

![image](https://github.com/user-attachments/assets/ef7424b9-e41f-4a8d-bea0-b4931f3323d8)

From the above visuals is it clear that there is a good spread in the data among data points. This is in harmony with the insights from summary statistics.
Now that the data is understond we move to adavnce analysis. 

# Advance Analysis/Visualization

<img width="597" alt="E-commerce" src="https://github.com/user-attachments/assets/eb99b30a-6b57-4051-9c76-c1202969cfe8">

# Insights
- Books leading leading the sales showes high demand and popularity
- Toys and sport trail in second and third position respctively shows a strong custmer base is interested in this category.
- The least performing product is home and kitchen.
- Books is also the highest revenue generator this makes books rthe best product for the company.
- Sports being second in reveuen shows sports related products has significanr financial impact
- The sales trend shows stability over the observed monthly period.

<img width="463" alt="E-Commerce 2" src="https://github.com/user-attachments/assets/15d5df80-e5cc-434f-be6a-ce0c85ba8258">

# Insights
- The scatter plot demonstrates a positive correlation between sales and review scores. As review scores increase, sales also tend to increase.
- The trend line provides a visual representation of this correlation, indicating that higher review scores are generally associated with higher sales.
- The predictive model for sales is represented by the broken line and the shaded area. The actual sales data is shown alongside the forecast.
- The actual sales trend appears relatively stable with slight fluctuations over the observed period.
- The forecasted values extend beyond the actual data points, indicating an estimated future trend. The forecast area shows an expected continuation of current sales levels, with a slight upward trend.

# Recommendation

Based on the analysis of product performance and customer preferences in the e-commerce market, the following recommendations are provided to enhance business strategies and drive growth.

- Focus on Review Scores: There is a clear positive correlation between review scores and sales. To leverage this, prioritize improving product quality and customer satisfaction. Implement feedback mechanisms to address customer concerns and continuously improve product offerings.
- Customer Feedback Integration: Regularly collect and analyze customer feedback to identify areas for improvement. Use this feedback to make informed decisions about product features and enhancements.
- Highlight Top-Performing Categories: Focus marketing efforts on the top-performing categories identified in the analysis (Books, Toys, Sports). Promote these categories through targeted campaigns to maximize sales and revenue.
- Utilize Predictive Models: The predictive model indicates stable or slightly increasing sales trends. Use this information for strategic planning in areas such as procurement, staffing, and marketing budgets.
- Revenue Analysis: Books, Sports, and Toys are the top revenue-generating categories. Invest in these categories by expanding product lines, improving quality, and offering exclusive deals.
- Upsell and Cross-Sell Opportunities: Identify opportunities to upsell and cross-sell within these high-revenue categories. Recommend related products to increase the average order value.
- Innovate Product Offerings: Regularly review and innovate product offerings to stay ahead of market trends. Introduce new products and features that align with customer preferences and market demands.


# Limitation 
There is need for further research on the cause for average performance of products. If it is due to price, quality of product or customer service. The data for this is not available hence the need for further research to boost sales and review score.








  
