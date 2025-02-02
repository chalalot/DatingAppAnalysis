# **Dating App User Analysis - Data Exploration & Machine Learning**

## **Overview**
This notebook explores a dating app dataset to uncover trends in user behavior, relationship preferences, and app usage. The goal was to analyze key patterns and test the predictive power of machine learning models to classify user frequency and relationship goals.

---

## **1. Dataset Exploration**
The dataset consists of user demographics, interests, and app engagement statistics, including:

- **Personal Traits**: Age, Gender, Education Level, Interests, and Children.
- **Behavioral Data**: Swiping History, Frequency of Usage.
- **Preferences**: Relationship Goals (Casual Dating, Marriage, Friendship, etc.).

### **Key Findings**
- **Age Group Trends**:  
  - Most users fall in the **23-30 age group**.
  - Swiping count and frequency of usage are **positively correlated**—more active users tend to swipe more.

- **Relationship Preferences**:  
  - **Young users (23-30)** prefer **casual dating and marriage**, investing in love actively.
  - **Older users** are more likely to seek **long-term relationships** rather than casual ones.

- **Interests & Social Behavior**:  
  - Users who prefer **outdoor activities** often **look for friendships** rather than romantic relationships, suggesting they seek companions for their hobbies.
  - **Education Level & Children** impact app usage:
    - Higher education leads to **less frequent usage**, likely due to time constraints.
    - Having children also affects app behavior, with parents tending to use the app less.

---

## **2. Machine Learning Attempts**
Two machine learning models were tested to predict **Frequency of Usage** and **Relationship Type**:
1. **K-Nearest Neighbors (KNN)**
2. **Random Forest Classifier**

### **Results**
- **Neither model performed well**, with low accuracy (~49%).
- Feature correlations were weak, suggesting **the dataset lacks strong predictive power**.
- The dataset **may be too small**, leading to **poor generalization** for machine learning models.

### **Conclusion**
While the dataset reveals **expected behavioral trends**, it does not have enough predictive strength for machine learning models to reliably classify user behavior. More **data collection, richer features, or a larger dataset** would be needed to improve predictions.
