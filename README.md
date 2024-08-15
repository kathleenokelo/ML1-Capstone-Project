# ML1-Capstone-Project
## PowerCo Customer Churn

This a project that focuses on PowerCo's customer retention challenge and proposes a structured approach to address it using the data science process. Below, I give a framework of the problem, key factors affecting customer's decisions, and how we can analyze these factors to better understand and mitigate customer churn.

### Problem Formulation Using the 5-Step Data Science Process:

#### 1.  Business Understanding and Problem Framing
PowerCo is experiencing customer churn, where customers are switching to other energy providers. The goal is to identify the factors contributing to this churn and develop strategies to improve customer retention.

To investigate the key reasons for customer churn, we need to gather relevant data, including:
  - Customer demographics (age, income, location)
  - Customer purchasing trends (energy usage, billing history over the last 5 years)
  - Customer service interactions (frequency and nature of complaints, reviews)
  - Competitor pricing and offers
  - Type of energy purchased (renewable vs. non-renewable)
  - Location of the business

#### 2. Exploratory Data Analysis and Data Cleaning.

This involves using statistical methods and visualization techniques to identify the trends and correlations within the data. Using heatmaps, bar charts, and time series plots to visualize the impact of various factors on churn. For example, we could use a heatmap to show the correlation between pricing changes and churn rates across different regions. It involves cleaning the collected data, handling missing values, and transforming categorical variables into numerical formats. We will also segment customers based on various attributes such as location, contract type, and energy usage patterns.

Examples of EDA we could perform include:
- Customer Purchasing Trends: Analyzing historical purchase data to detect patterns related to energy consumption and pricing.
- Location Data: Assessing whether geographic factors, such as proximity to energy sources or service centers, influence customer satisfaction.
- Customer Service Interactions:  Visualize the relationship between relationship between customer service interactions and retention to understand how bad service could affect customer churn

#### 3. Feature Engineering.

This involves interacting with the features in the dataset, understanding their impact on customer retention and creating new features that could provide further insight on the factors that influence customer churn. For example, we could create new features that might impact churn, such as customer loyalty scores or energy usage variability.

#### 4.Modeling and Evaluation

Develop predictive models (e.g., logistic regression, decision trees) to assess the impact of different factors on customer churn. These models can help identify high-risk customers and the key drivers behind their decisions to switch providers. Validate the models using appropriate metrics (e.g., accuracy, F1 score , R2 score) and interpret the results to understand which factors most significantly influence customer retention. For instance, if price sensitivity emerges as a key factor, we can explore targeted pricing strategies or discounts for at-risk customers.

#### 5.Insights and Recommendations.

After evaluating the model and gaining insight on which factors have a significant impact on customer churn, we could make recommendations on what could be a better approach to improving customer retention. Such insights could be:
- Price Sensitivity: Competitive pricing may be a primary driver for customers switching providers.
- Energy Source: The increasing demand for clean, renewable energy could influence customer decisions.
- Customer Service Quality: Poor service experiences might push customers to seek alternatives.
- Contract Flexibility: Rigid contract terms or lack of flexible options could lead to higher churn rates.



By systematically addressing these aspects, we can gain actionable insights into the root causes of customer churn and develop data-driven strategies to enhance customer retention.
