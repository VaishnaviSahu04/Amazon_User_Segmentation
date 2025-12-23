🛒 Amazon User Segmentation using Machine Learning

📌 Project Overview

This project implements an end-to-end Amazon user segmentation system using machine learning techniques. The goal is to group users into meaningful behavioral segments based on engagement, pricing preference, and rating behavior, and deploy the solution as an interactive Streamlit web application.

The project follows the complete data science lifecycle, from data preprocessing and exploratory data analysis to clustering and deployment.

🎯 Problem Statement

Amazon users exhibit diverse purchasing behaviors. Treating all users uniformly leads to ineffective marketing strategies. This project aims to:

Identify distinct customer segments

Understand behavioral differences

Enable targeted marketing and personalization strategies

🧠 Solution Approach

The solution uses K-Means clustering to segment users based on engineered behavioral features derived from product reviews and pricing data.

🔍 Workflow

Data Preprocessing

Handling missing values

Data type conversion

Cleaning numeric fields

Exploratory Data Analysis (EDA)

15+ visualizations to understand pricing, ratings, discounts, and engagement

Business-oriented insights derived from patterns

Feature Engineering

Aggregation at user level

Creation of behavioral features:

Total reviews

Average rating

Average discount preference

Average spending

Engagement score

Feature Scaling

StandardScaler used to normalize features

Zero-variance features removed

Clustering

Optimal clusters determined using Elbow Method & Silhouette Score

K-Means clustering applied

Cluster Interpretation

Users segmented into meaningful personas

Business recommendations provided for each segment

Deployment

Model deployed using Streamlit

Interactive web app for real-time user segmentation

📊 Customer Segments Identified
🟢 Casual Buyers

Low engagement

Occasional purchases

Moderate ratings

Strategy: Personalized recommendations and onboarding offers

🔵 Deal Seekers

High discount sensitivity

Promotion-driven behavior

Strategy: Flash sales, coupons, price-drop alerts

🟣 Premium Loyalists

High engagement

High spending

Quality-focused

Strategy: Loyalty programs, exclusive offers, premium recommendations

🚀 Streamlit Application

The Streamlit app allows users to:

Enter behavioral details

Predict customer segment in real time

Understand user category instantly

📌 Live App: (Add your Streamlit URL here after deployment)

🗂 Project Structure
Amazon_Customer_Segmentation/
│

├── Amazon.ipynb

├── README.md

├── amazon.csv

├── app.py

├── features.pkl

├── kmeans_model.pkl

├── scaler.pkl

├── requirements.txt


🛠 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Streamlit

Joblib

GitHub

📈 Business Impact

Enables data-driven customer segmentation

Improves targeting and personalization

Optimizes marketing spend

Delivers a deployable ML solution

🔮 Future Enhancements

Time-based behavioral analysis

Advanced clustering techniques (DBSCAN, Hierarchical)

Real-time data integration

Enhanced Streamlit dashboards

🏁 Conclusion

This project demonstrates a complete, real-world implementation of customer segmentation using machine learning, combined with deployment for practical usability. The insights generated can help businesses improve engagement, retention, and revenue through targeted strategies.

👤 Author

Vaishnavi Sahu
B.Tech – Computer Science & Business Systems
Data Science | Machine Learning | Analytics
