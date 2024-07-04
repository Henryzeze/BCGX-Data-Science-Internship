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
