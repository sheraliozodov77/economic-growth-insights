# 📈 **Analyzing Economic Growth: Factors and Predictive Trends**

This project leverages **machine learning** to explore economic growth across various countries. By analyzing indicators such as GDP, health and education expenditure, and trade dynamics, it classifies countries by development stages and forecasts economic trends to guide policy-making and strategic planning.

---

## 📚 **Project Overview**
- **Objective**: Identify key factors influencing economic growth and classify countries into development groups.
- **Dataset**: Annual global economic indicators from 2000 to 2022, sourced from the World Bank.
- **Methods**:
  - **Regression Analysis** (Linear, Polynomial, Ridge)
  - **K-Means Clustering**
  - **Exploratory Data Analysis (EDA)**

---

## 🛠️ **Technologies and Tools**
- **Libraries**: pandas, numpy, scikit-learn, seaborn, matplotlib, geopandas
- **Models**: Linear Regression, Ridge Regression, K-Means Clustering

---

## 📝 **Key Steps**
1. **Exploratory Data Analysis (EDA)**:
   - Visualized trends and correlations among GDP, trade, and other economic indicators.
   - Examined sectoral composition of GDP (agriculture, industry, services) by continent.

2. **Feature Engineering**:
   - Selected core indicators such as R&D, trade balance, and health expenditure for model building.

3. **Model Training**:
   - Implemented polynomial regression to capture non-linear relationships.
   - Optimized ridge regression using cross-validation.
   - Conducted K-Means clustering to group countries based on economic profiles.

---

## 📊 **Results**
- **Regression Model**:
  - **R² Score**: 0.997
  - **Test RMSE**: $56.77 billion
  - **Key Factors**: R&D, trade balance, health and education expenditure

- **Clustering Analysis**:
  - **Cluster 0**: Emerging economies
  - **Cluster 1**: Dominant global economies
  - **Cluster 2**: Developed economies

---

## 🏆 **Key Insights**
- **Invest in R&D**: Innovation drives long-term economic growth.
- **Balance Trade**: Positive trade balance correlates with higher GDP.
- **Support Education and Health**: These sectors play crucial roles in sustained economic development.
