# **Google Play Store Apps Analysis**

This project analyzes the Google Play Store Apps dataset, focusing on app ratings, installs, and other key features to extract insights and build predictive models.

## **Dataset Overview**
- **Name**: Google Play Store Apps
- **Link**: [Google Play Store Apps](https://www.kaggle.com/datasets/lava18/google-play-store-apps/data)
- **Description**: Contains information about apps on the Google Play Store including ratings, reviews, size, installs, and more.

## **Setup**
To install the required libraries, run:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly


**Data Cleaning & Preprocessing**
**Missing Values:** Filled missing ratings with the median, and handled other categorical columns by filling with the mode.
**Outliers:** Removed outliers from the 'Rating' column using the IQR method.
**Feature Transformation:** Converted 'Installs' and 'Size' columns to numerical values for better analysis.

**Exploratory Data Analysis (EDA)**
**Statistical Analysis:** Calculated mean, median, and standard deviation of ratings.
**Grouping:** Aggregated data by category to examine ratings and reviews.
**Visualization:** Created histograms, box plots, scatter plots, and a correlation heatmap to visualize data trends and relationships.

**Hypothesis Testing**
**Hypothesis 1:** Higher priced apps tend to have higher ratings.
**Hypothesis 2:** Apps in the 'GAME' category generally have higher ratings than other categories.

****Machine Learning Models****
**Linear Regression:** Used to predict app ratings based on features like reviews and installs.
**Decision Tree Regressor:** Applied for comparison with the linear model.

****Conclusion****
This project provides a comprehensive analysis of Google Play Store apps, with a focus on data cleaning, exploratory analysis, hypothesis testing, and machine learning. It aims to offer actionable insights and predictions for app developers and analysts.

**Getting Started**
**Clone the repository:**

```bash
git clone https://github.com/your-username/repo-name.git
cd repo-name
