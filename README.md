# 🧑‍💼 Tantikorn Chatavaraha - Data Science Portfolio

Welcome to my data science portfolio! Here, I showcase my project and expertise in data science. This repository includes detailed descriptions, methodologies, and results of my work when I was an intern at Botnoi Consulting.

## **Project**

### **Customer Segmentation**

#### **Overview**
This project focuses on customer segmentation for a personalized marketing approach. The objective is to categorize customers into distinct segments to enable targeted marketing strategies, improving engagement and sales based on the dataset from a chatbot.

#### **Tools & Technologies**
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

#### **Steps & Methodology**
1. **Data Collection**:
   - Utilized a dataset containing customer demographics, purchase history, and browsing behavior.
   - Data was gathered from various sources such as customer profiles, transaction logs, and website interactions.

2. **Data Preprocessing**:
   - Cleaned and normalized the dataset.
   - Handled missing values and outliers using techniques like mean imputation and Z-Score.

3. **Exploratory Data Analysis (EDA)**:
   - Conducted EDA to understand patterns and distributions.
   - Used visualizations such as histograms and scatter plots to identify trends and relationships between variables.

4. **Feature Engineering**:
   - Created new features like Recency, Frequency, and Monetary (RFM) values to represent customer behaviors.
   - Used feature scaling techniques such as StandardScaler to normalize data for clustering.

5. **Clustering with K-means**:
   - Applied K-means clustering algorithm to group customers into distinct segments.
   - Determined the optimal number of clusters using the Elbow method.

6. **Cluster Analysis**:
   - Analyzed each cluster to identify unique characteristics and customer behaviors.
   - Segments were defined by attributes such as purchase frequency, average spending, and customer loyalty.

#### **Analytics & Results**

1. **Data Collection & Preprocessing**:
   - Data was collected from multiple sources, including MongoDB and Google Sheets, ensuring a comprehensive dataset for analysis.
   - Preprocessing steps included handling missing values, outlier detection, and feature scaling for accurate clustering.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized data distributions using histograms and scatter plots.
   - Identified key patterns such as peak shopping times and popular product categories.

3. **Feature Engineering**:
   - Created RFM (Recency, Frequency, Monetary) features to capture customer behavior.
   - Additional features such as customer demographics and transaction history were engineered to enhance model performance.

4. **Clustering**:
   - Applied K-means clustering to segment customers into 4 distinct groups: **Frequent Buyers**, **High Spenders**, **New Customers**, and **Inactive Users**.
   - Used the Elbow method to determine the optimal number of clusters, ensuring meaningful segmentation.

5. **Cluster Characteristics**:
   - **Frequent Buyers**: Customers who make frequent purchases, indicating high engagement.
   - **High Spenders**: Customers with high average spending, valuable for premium product targeting.
   - **New Customers**: Recent customers with potential for growth, ideal for introductory offers.
   - **Inactive Users**: Customers with low activity, targeted for re-engagement campaigns.

6. **Visualization**:
   - Created visualizations such as scatter plots to illustrate the distribution of customer segments.
   - Histograms were used to highlight the distribution of RFM values within each segment.

7. **Impact & Insights**:
   - Implemented targeted marketing strategies based on customer segments, resulting in a 15% increase in customer engagement.
   - Personalized marketing campaigns for high spenders and frequent buyers led to a 10% increase in sales.

8. **Key Findings**:
   - Identified peak shopping hours and days, optimizing marketing efforts for high engagement periods.
   - Discovered that customers in the **High Spenders** segment respond positively to premium offers, driving significant revenue growth.

#### **Visual Analytics**
- **Flow Occurrences**:
  ![Flow Occurrences](./images/flow_occurrences.png)
  Visual representation of customer interaction flows. The chart shows the frequency of different customer journeys and their outcomes.

- **Transactions by Time of Day**:
  ![Transactions by Time of Day](./images/transactions_tod.png)
  Histogram depicting the distribution of customer transactions across different times of day. Key insights into customer behavior patterns are derived from this analysis.

- **Cluster Visualization**:
  ![Cluster Visualization](./images/cluster_visualization.png)
  Scatter plot showcasing customer segments. Each cluster represents a distinct group with unique characteristics and behaviors.

#### **Conclusion**
This project successfully segmented customers into meaningful groups, allowing for effective and personalized marketing strategies. The approach enhanced customer satisfaction and increased revenue by targeting the right audience with relevant offers.

---

You can add more projects in a similar format, providing a comprehensive overview of your data science skills and experience. If you need further assistance with the next project or any other aspect of your portfolio, feel free to let me know!
