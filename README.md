# User Engagement & Fitness Data Analysis

## Overview
This project analyzes user engagement and app performance in a fitness tracking app using statistical techniques, regression models, clustering, and machine learning methods.  
The goal is to predict user behavior, segment users into meaningful groups, and optimize app recommendations for better fitness engagement.

By performing data-driven analysis, this project identifies:
- User activity patterns (Sedentary, Moderate, Active)
- Regression-based predictions for calorie expenditure
- K-Means clustering for user segmentation
- Feature correlations that impact app usage

---

## Key Objectives
- Identify user engagement trends and understand how age, gender, and activity level impact app usage.  
- Predict user behavior by applying regression models to estimate calorie expenditure based on user data.  
- Segment users for optimization using K-Means Clustering based on activity patterns.  
- Evaluate model performance using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² Score.  
- Provide actionable insights to improve software engineering decisions for fitness app optimization.  

---

## Features & Analysis

### 1. Exploratory Data Analysis (EDA)
- User Activity Segmentation: Categorizing users as Sedentary, Moderate, or Active.
- Correlation Analysis: Examining relationships between App Sessions, Distance Travelled, and Calories Burned.
- Visualization Techniques: Histograms, Boxplots, Scatter Plots for trend identification.

### 2. Statistical Techniques Applied
- Regression Analysis: Predicts Calories Burned based on App Sessions, Distance Travelled, and Age.
- K-Means Clustering: Segments users into behavioral groups for improved fitness recommendations.
- Silhouette Score Analysis: Measures the effectiveness of clustering.
- Mann-Whitney U Test & Kruskal-Wallis Test: Compares engagement levels across user groups.

### 3. Performance Evaluation of Models
- Regression Metrics:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R² Score (Accuracy of Predictions)
- Clustering Metrics:
  - Silhouette Score for Optimal Cluster Selection
  - Elbow Method for K Selection

---

## Data Insights & Findings

### 1. Key Statistical Findings
- App Sessions have a direct impact on Calories Burned.  
  - More frequent users burn significantly more calories than occasional users.
- Distance Travelled is strongly correlated with overall fitness engagement.  
  - Users who travel more tend to have higher calorie burn rates.
- Regression Model is effective for predicting Calories Burned.  
  - The model shows an R² score above 0.75, indicating strong predictive power.

### 2. Clustering-Based User Segmentation
Users were grouped into three clusters based on fitness engagement:
1. Sedentary Users → Low sessions, low calories burned.
2. Moderate Users → Medium sessions, moderate calorie burn.
3. Active Users → High sessions, high calorie burn.

### 3. Recommendations for App Optimization
- Personalized Fitness Plans: Use clustering results to recommend workouts tailored to user engagement.  
- In-App Notifications: Target Sedentary users with motivational reminders based on their activity levels.  
- Gamification Features: Introduce streak-based incentives for users with high engagement patterns.  
- Real-Time Prediction Models: Use regression models to provide instant calorie burn estimations during workouts.  

---

## Technologies Used
- Programming Language: Python
- Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Statsmodels
- Machine Learning: Regression, Clustering (K-Means)
- Statistical Methods: Correlation Analysis, Mann-Whitney U Test, Kruskal-Wallis Test
- Performance Metrics: MSE, MAE, R² Score, Silhouette Score
- Data Visualization: Histograms, Boxplots, Scatter Plots, Heatmaps

---

## Conclusion
This project successfully analyzes user behavior and provides data-driven recommendations for fitness app optimization. The combination of exploratory analysis, machine learning models, and performance metrics allows for better decision-making in software engineering and fitness app development.

---

## Authors
- Gurtej Singh
- Student ID: 270412474
