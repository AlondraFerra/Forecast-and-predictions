# Predictive Analytics & Clustering for Customer Retention

# Context
Model Fitness, a subscription-based gym chain, is facing high customer churn, a common challenge in the fitness industry. Understanding why customers cancel their memberships is crucial for improving retention strategies and sustaining business growth. This project aims to analyze user behavior, identify key churn predictors, and develop data-driven recommendations to enhance customer engagement and loyalty.  

# Tools Used
- **Data Processing & Analysis:** Python, pandas, NumPy  
- **Visualization:** seaborn, matplotlib  
- **Machine Learning:** scikit-learn (classification models, clustering techniques)  
- **Business Insights:** Customer segmentation, retention strategies  

# Analysis Conducted
1. **Data Exploration & Preprocessing** – Cleaned and structured the dataset to ensure consistency and usability.  
2. **Exploratory Data Analysis (EDA)** – Examined user demographics, membership details, visit frequency, and spending behavior to detect patterns influencing retention.  
3. **Classification Models** – Developed predictive models to estimate churn probability based on user attributes and behavior.  
4. **User Clustering** – Segmented customers into five groups using clustering techniques to understand different retention risks and behavioral profiles.  

# Results & Findings
The analysis identified **five distinct customer clusters**, each with different levels of engagement and risk of churn:  
- **Cluster 0 (43.4% churn rate):** Customers with low engagement, short contracts, and minimal spending. Their weak connection with the gym makes them highly likely to cancel.  
- **Cluster 1 (53.1% churn rate - highest):** The least active group, characterized by infrequent visits and short-term memberships, making them the most vulnerable to churn.  
- **Cluster 2 (7.1% churn rate - low risk):** Active users who frequently attend classes and make additional purchases, indicating strong engagement despite preferring short-term contracts.  
- **Cluster 3 (2.9% churn rate - lowest):** The most loyal customers, with long-term contracts, high visit frequency, and strong social engagement.  
- **Cluster 4 (28.5% churn rate):** A moderately engaged group, with room for improvement in retention strategies.  

# Conclusions & Recommendations
To reduce churn and improve retention, the following strategies are suggested:  
- **Encourage Long-Term Memberships:** Offer discounts and exclusive perks for 6-12 month contracts to increase commitment.  
- **Promote Social & Group Activities:** Leverage referral programs and group classes to enhance user engagement.  
- **Incentivize Regular Attendance:** Implement rewards for consistent gym visits to maintain user motivation.  
- **Personalized Outreach for At-Risk Users:** Target low-engagement users with special offers, reminders, and personalized experiences to prevent cancellations.  
