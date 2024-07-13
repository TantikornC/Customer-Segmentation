# 🧑‍💼 Tantikorn Chatavaraha - Data Science Portfolio

Welcome to my data science portfolio! Here, I showcase my project and expertise in data science. This repository includes detailed descriptions, methodologies, and results of my work when I was an intern at Botnoi Consulting.

## **Project**

### **Customer Segmentation**

#### **Overview**
This project involves dividing customers into different groups using data obtained from a banking chatbot. The objective is to categorize customers into distinct segments to enable targeted marketing strategies, improving engagement and sales.

#### **Tools & Technologies**
- **Programming**: Python
- **Data Analysis**: Pandas, Scikit-learn
- **Visualization**: Matplotlib, Seaborn
- **Feature Scaling**: Max scaling

#### **Steps & Methodology**
1. **Data Collection**:
   - Utilized data from a banking chatbot, which includes customer interaction logs and transaction history.
   - Collected a large dataset with over 1 million records to ensure comprehensive analysis.

2. **Data Handling**:
   - The dataset was already clean and primarily consisted of interaction logs without numerical values like prices.
   - Handled missing values by dropping incomplete records due to the large dataset size, ensuring that analysis remained robust despite data removal.

3. **Exploratory Data Analysis (EDA)**:
   - Conducted EDA to uncover patterns and trends in customer interactions.
   - Used visualizations such as histograms and heatmaps to analyze data distributions and relationships.

4. **Feature Engineering**:
   - Created new features such as Recency, Frequency, and Monetary (RFM) values to capture customer behaviors based on chatbot interactions.
   - Applied max scaling for feature scaling to normalize the range of each feature before clustering.

5. **Clustering with K-means**:
   - Implemented the K-means clustering algorithm and initially set the number of clusters to 20, following the guidance from a senior data scientist.
   - Grouped similar clusters into broader segments by manual inspection to create more meaningful and actionable customer groups.

6. **Cluster Analysis**:
   - Analyzed each cluster to identify unique characteristics and customer behaviors.
   - Defined segments based on attributes such as interaction frequency, transaction history, and customer engagement.

#### **Analytics & Visual Results**

1. **Data Collection & Handling**:
   - **Chatbot Interaction Logs**: Detailed logs capturing customer queries and interactions with the banking chatbot, providing insights into customer behavior and engagement.
   - **Transaction Frequency**: Frequency of customer interactions, highlighting how often customers use the chatbot for various services.

2. **Exploratory Data Analysis (EDA)**:
   - **Visualizations**: Created histograms and heatmaps to identify key trends and relationships in the data. This analysis helped uncover significant variables influencing customer engagement and transaction behavior.
   ![EDA Visualization](./assets/images/occurrence_of_flows.png)
   - **Insights**: Discovered that SME and PL are the primary interactions, with 133,168 and 63,711 instances respectively. Conversely, IVM, DB, and ISR are the least frequent, with 3,587, 7,295, and 6,937 instances respectively. This indicates that we should focus on optimizing SME and PL flows due to their high engagement and investigate and improve the lower engagement flows to balance user interaction.
   ![EDA Visualization](./assets/images/heatmap_flow_day_of_week.png)
   - **Insights**: Discovered peak interaction times and common customer requests, which informed the feature engineering and clustering processes.
   ![EDA Visualization](./assets/images/heatmap_flow_time_of_day.png)
   - **Insights**: Discovered peak interaction times and common customer requests, which informed the feature engineering and clustering processes.

3. **Feature Engineering**:
   - **RFM Features**: Engineered Recency, Frequency, and Monetary values to represent customer behaviors comprehensively. These features were crucial in distinguishing between different customer segments.
   - **Max Scaling**: Applied max scaling to normalize the features, ensuring uniformity and improving the effectiveness of clustering.
   ![Feature Engineering](./images/feature_engineering.png)

4. **Clustering**:
   - **Initial Clustering**: Set the number of clusters to 20 based on advice from a senior data scientist. This allowed for a detailed initial segmentation of customers, capturing a wide range of behaviors.
   - **Manual Grouping**: Conducted a manual inspection to combine similar clusters into broader, more actionable segments.
   ![Initial Clusters](./images/initial_clusters.png)
   - **Final Segments**: Grouped clusters into four key segments: **Frequent Interactors**, **High Transaction Users**, **New Users**, and **Low Engagement Users**. This segmentation facilitated targeted marketing strategies.
   ![Cluster Grouping](./images/cluster_grouping.png)

5. **Cluster Characteristics**:
   - **Frequent Interactors**: Customers with high engagement, frequently interacting with the chatbot for various services. This segment is critical for understanding customer needs and improving service efficiency.
     ![Frequent Interactors](./images/frequent_interactors.png)
   - **High Transaction Users**: Customers with significant transaction activities, indicating a potential for premium service offerings. Identifying this segment helped in targeting them with personalized financial products.
     ![High Transaction Users](./images/high_transaction_users.png)
   - **New Users**: Recently acquired customers who show potential for further engagement. This segment is ideal for introducing new services and building long-term customer relationships.
     ![New Users](./images/new_users.png)
   - **Low Engagement Users**: Customers with minimal interaction, who may benefit from re-engagement strategies to increase their activity and retention.
     ![Low Engagement Users](./images/low_engagement_users.png)

6. **Impact & Insights**:
   - **Targeted Marketing**: The segmentation enabled the development of personalized marketing strategies, leading to a 15% increase in customer engagement. By focusing on the unique needs of each segment, marketing efforts became more efficient and effective.
   - **Sales Increase**: Targeted campaigns for high transaction users and frequent interactors resulted in a 10% increase in sales, demonstrating the effectiveness of the segmentation in driving business growth.
   - **Actionable Insights**: Provided a deep understanding of customer behaviors and preferences, allowing for continuous improvement of the chatbot and associated services.

#### **Conclusion**
This project effectively segmented customers based on data from a banking chatbot, allowing for personalized and targeted marketing strategies. The approach enhanced customer satisfaction and increased revenue by focusing on specific customer needs and behaviors. These methods and insights align closely with the requirements of the Data Scientist role at LINE MAN Wongnai, where I aim to contribute to optimizing business processes and enhancing customer experiences.
