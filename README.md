# BCGX-Data-Science-Internship

![](cover,jpg)

## Introduction

- The client is PowerCo - a major gas and electricity utility that supplies to small and medium-sized enterprises.
- The energy market has had a lot of change in recent years and there are more options than ever for customers to choose from.
- PowerCo is concerned about its customers leaving for better offers from other energy providers. When a customer leaves to use another service provider, this is called churn.
- This is becoming a big issue for PowerCo and they have engaged BCG to help diagnose the reason why their customers are churning.

### 1. Business Understanding & Problem Framing:

PowerCo is concerned about customers leaving for better offers from other energy providers. I aim to diagnose the reasons behind this churn and provide actionable insights to reduce it.

### Key Reasons for Customer Churn:

- **Price:** Competitiveness of PowerCo’s pricing compared to other providers.
- **Energy Source:** Preference for clean/renewable energy sources.
- **Customer Service:** Quality and responsiveness of customer support.
- **Contract Terms:** Flexibility and length of contracts.
- **Location:** Regional factors influencing energy provider choice.
- **Service Reliability:** Frequency and duration of service outages.
- **Incentives and Offers:** Availability of promotional offers and loyalty programs.
- **Billing and Payment Options:** Ease and variety of billing and payment methods.

### 2. Data Requirements: 

To investigate these reasons, the following data was initially requested from Powerco:

- **Customer Demographics:** Age, gender, business type, and location.
- **Customer Transaction Data:** Historical purchase data, energy consumption, billing amounts, and payment history.
- **Contract Information:** Contract start and end dates, terms, and any changes over time.
- **Customer Service Interactions:** Records of customer inquiries, complaints, and resolution times.
- **Churn Data:** List of customers who have churned and those who have stayed, with timestamps.
- **Competitor Pricing and Offers:** Information on competitors’ pricing, offers, and incentives.
- **Service Reliability Metrics:** Data on service outages, durations, and maintenance schedules.
- **Marketing Campaigns:** Details of any marketing efforts targeted at customer retention.

### 3. Exploratory Data Analysis & Data Cleaning: 

I will perform an initial analysis to understand the data structure, identify missing values, and detect any anomalies. Techniques such as summary statistics, data visualizations (e.g., histograms, box plots), and correlation analysis will be employed.

### 4. Feature Engineering: 

Based on our understanding of the data, I will create new features that could be predictive of churn. For instance, calculating customer lifetime value, monthly energy consumption trends, and customer service interaction frequency.

### 5. Modeling and Evaluation: 

I will apply various predictive modeling techniques such as logistic regression, decision trees, and machine learning algorithms (e.g., random forests, gradient boosting) to identify factors contributing to churn. I will evaluate model performance using metrics such as accuracy, precision, recall, and ROC-AUC.

### 6. Insights & Recommendations: 

The final step will involve interpreting the model results to identify key drivers of churn. I will provide PowerCo with actionable insights and recommendations, such as targeted retention campaigns, pricing adjustments, or improvements in customer service.

### Data Visualization Techniques:

- **Churn Rate Trends:** Line charts showing churn rates over time.
- **Customer Segmentation:** Cluster analysis to identify segments with high churn risk.
- **Correlation Heatmaps:** To visualize relationships between different variables.
- **Bar Charts and Pie Charts:** To show the distribution of reasons for churn.
- **Geospatial Analysis:** Maps showing churn rates by location.

By leveraging these steps, I aim to provide a comprehensive analysis that helps PowerCo understand the reasons behind customer churn and implement effective strategies to mitigate it.

## Task 1

The client Powerco sent over 3 data sets (shown below):

- Historical customer data: Customer data such as usage, sign up date, forecasted usage etc
- Historical pricing data: variable and fixed pricing data etc
- Churn indicator: whether each customer has churned or not

Am tasked to run an analysis on the datasets using Python:

- The data types of each column
- Descriptive statistics of the dataset
- Distributions of columns
- Visualizations

[Task One Analysis Report on Jupyter Notebook](https://github.com/Henryzeze/BCGX-Data-Science-Internship/blob/main/Task_2_eda_completed.ipynb)

## Task 2

As part of my task, I focused on creating new features for my analysis and prepared a comprehensive Python script to achieve this. Here is a summary of the tasks I completed:

First, I examined the datasets to identify columns that could be removed.

Upon looking at the dataset, I could not identify any columns that were not relevant to the analysis or had only one unique value, making them redundant.

Second, I expanded the datasets by creating new features from existing columns.

For instance, I had "date" columns in the raw data that were not useful in their original form. I extracted valuable components from these date columns, such as the month, day of the month, day of the year, and the year, and created individual columns for each. These new features provided more granular insights and improved the dataset's usability.

Third, I combined some columns to create "better" columns.

To define a "better" column, I focused on columns that could improve the accuracy of the predictive churn model. I experimented with various combinations of columns, looking for pairs that shared similar information or complemented each other. For example, I combined columns related to customer activity and transaction history to create new features that better represented customer engagement and purchasing patterns.

Finally, I combined the datasets using common columns for joining.

I identified columns that featured in both datasets and shared the same values, which allowed me to join them effectively. This merging process resulted in a more comprehensive dataset, incorporating all relevant information into a single, unified dataset.

Throughout these steps, I maintained a clear framework for feature engineering, ensuring each new feature added value to the analysis. I documented the process thoroughly and uploaded the completed Python file for review.

[Task Two Feature Engineering on Jupyter Notebook](https://github.com/Henryzeze/BCGX-Data-Science-Internship/blob/main/Task_3_feature_engineering_done.ipynb)

## Task 3

I was tasked to:

- Train a random forest classifier to predict churn
- Evaluate the predictions using evaluation metrics to demonstrate how accurately the model has performed

[Task Three prediction using classification and random forest on Jupyter Notebook](https://github.com/Henryzeze/BCGX-Data-Science-Internship/blob/main/Task_4_modeling_Completed.ipynb)
