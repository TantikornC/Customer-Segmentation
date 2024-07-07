# 🧑‍💼 Tantikorn Chatavaraha - Data Science Portfolio

Welcome to my data science portfolio! Here, I showcase my project and expertise in data science. This repository includes detailed descriptions, methodologies, and results of my work when I was an intern at Botnoi Consulting.

## **Project**

### **Customer Segmentation**

#### **Overview**
This project involves dividing customers into different groups using data obtained from a banking chatbot. The objective is to categorize customers into distinct segments to enable targeted marketing strategies, improving engagement and sales.

#### **Tools & Technologies**
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

#### **Steps & Methodology**
1. **Data Collection**:
   - Utilized data from a banking chatbot, which includes customer interaction logs and transaction history.
   - Collected a large dataset with over 1 million records to ensure comprehensive analysis.

2. **Data Handling**:
   - The dataset was already clean and primarily consisted of interaction logs without numerical values like prices.
   - Handled missing values by dropping incomplete records due to the large dataset size, ensuring that analysis remained robust despite data removal.

3. **Exploratory Data Analysis (EDA)**:
   - Conducted EDA to uncover patterns and trends in customer interactions.
   - Used visualizations such as histograms and stacked bar charts to analyze data distributions and relationships.

4. **Feature Engineering**:
   - Created new features such as Recency, Frequency, and Monetary (RFM) values to capture customer behaviors based on chatbot interactions.
   - Created 

5. **Clustering with K-means**:
   - Implemented the K-means clustering algorithm to segment customers into distinct groups.
   - Determined the optimal number of clusters using the Elbow method to ensure meaningful segmentation.

6. **Cluster Analysis**:
   - Analyzed each cluster to identify unique characteristics and customer behaviors.
   - Defined segments based on attributes such as interaction frequency, transaction history, and customer engagement.

#### **Analytics & Results**

1. **Data Collection & Handling**:
   - Gathered data from a banking chatbot, including:
     - **Chatbot Interaction Logs**: Records of customer interactions, detailing inquiries and actions taken.
     - **Transaction Frequency**: How often customers use the chatbot for transactions or information requests.
     - **Types of Requests**: Nature of requests made through the chatbot, such as balance inquiries, transfers, or loan applications.
     - **Engagement Patterns**: Analysis of peak interaction times, duration of sessions, and common user paths.
   - The dataset, comprising over 1 million records, was large enough to maintain robustness even after dropping missing values.

2. **Exploratory Data Analysis (EDA)**:
   - Conducted EDA to understand the patterns and distributions of customer interactions.
   - Visualized key trends and relationships between customer behaviors using histograms and scatter plots.

3. **Feature Engineering**:
   - Engineered features like RFM values to represent customer behaviors comprehensively based on chatbot interactions.
   - Created additional features to capture detailed patterns in customer interactions and transaction history.

4. **Clustering**:
   - Applied K-means clustering to divide customers into 4 distinct segments: **Frequent Interactors**, **High Transaction Users**, **New Users**, and **Low Engagement Users**.
   - Used the Elbow method to identify the optimal number of clusters, ensuring meaningful segmentation.

5. **Cluster Characteristics**:
   - **Frequent Interactors**: Customers who frequently interact with the banking chatbot, indicating high engagement.
   - **High Transaction Users**: Customers with significant transaction activity via the chatbot, valuable for targeted premium services.
   - **New Users**: Recently acquired customers with potential for growth, ideal for introductory offers.
   - **Low Engagement Users**: Customers with minimal interaction, targeted for re-engagement campaigns.

6. **Visualization**:
   - Created visualizations like scatter plots to display the distribution of customer segments.
   - Utilized histograms to highlight the distribution of RFM values within each segment.

7. **Impact & Insights**:
   - Implemented targeted marketing strategies based on customer segments, resulting in a 15% increase in customer engagement.
   - Personalized campaigns for high transaction users and frequent interactors led to a 10% increase in sales.

8. **Key Findings**:
   - Identified peak interaction times, optimizing marketing efforts for high engagement periods.
   - Discovered that high transaction users respond positively to premium offers, driving significant revenue growth.

#### **Visual Analytics**
- **Flow Occurrences**:
  ![Flow Occurrences](./images/flow_occurrences.png)
  This chart illustrates the frequency of different customer journeys through the banking chatbot, showcasing key interaction flows and their outcomes.

- **Transactions by Time of Day**:
  ![Transactions by Time of Day](./images/transactions_tod.png)
  Histogram depicting the distribution of customer transactions across various times of day, providing insights into peak interaction periods.

- **Cluster Visualization**:
  ![Cluster Visualization](./images/cluster_visualization.png)
  Scatter plot showcasing customer segments. Each cluster represents a distinct group with unique characteristics, derived from banking chatbot interactions.

#### **Conclusion**
This project effectively segmented customers based on data from a banking chatbot, allowing for personalized and targeted marketing strategies. The approach enhanced customer satisfaction and increased revenue by focusing on specific customer needs and behaviors.
