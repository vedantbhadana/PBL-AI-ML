# PBL-AI-ML
This project builds a complete machine learning pipeline to predict employee salary using a synthetically generated dataset with 20 features. It involves performing EDA, preprocessing the data, applying feature selection, and comparing regression models like Linear, Ridge, and Lasso using R² score and RMSE for evaluation.

Question Statement
Develop a regression-based machine learning system to predict employee salary using a synthetically generated dataset consisting of 20 employee-related features. The dataset should simulate a real organizational environment and include a mix of numerical and categorical attributes such as age (integer), years of experience (integer), education level (categorical), job level (categorical), department (categorical), job role (categorical), performance rating (1–5 scale), number of projects completed (integer), certifications count (integer), weekly work hours (integer), overtime hours (integer), team size (integer), leadership score (continuous), skill match score (continuous), years in current role (integer), promotion count (integer), employment type (categorical), location type (categorical), company size (categorical), and job satisfaction score (1–5 scale), with salary as the continuous target variable. The project should begin with Exploratory Data Analysis (EDA) to analyze feature distributions, correlations, and relationships with salary. Comprehensive data preprocessing must be performed, including data cleaning, normalization, and appropriate transformations, followed by forward feature selection to identify the most influential predictors. The system should implement and compare Linear Regression, Ridge Regression, and Lasso Regression models, and evaluate their performance using the R² score and RMSE . The project should demonstrate a complete machine learning pipeline from synthetic data generation to model evaluation, emphasizing best practices in data preprocessing and regression modeling.

## 🔹 Phase 1: Data Preprocessing and Exploratory Data Analysis (EDA)

In this phase, the synthetic employee dataset was loaded and examined to understand its structure and characteristics. Basic operations such as checking data types, summary statistics, and missing values were performed to ensure data quality. Exploratory Data Analysis (EDA) was conducted using histograms and correlation heatmaps to study feature distributions and relationships with the target variable (salary). Numerical features were scaled using StandardScaler, while categorical features were encoded using OneHotEncoder. This phase ensured that the dataset was clean, well-structured, and ready for machine learning modeling.

---

## 🔹 Phase 2: Feature Selection and Model Development

In this phase, the dataset was split into training and testing sets to build and evaluate models effectively. Forward Feature Selection was applied to identify the most relevant features influencing salary prediction. Two machine learning models were developed: Random Forest Regressor and Support Vector Regressor (SVR). Random Forest was tuned using GridSearchCV to optimize its hyperparameters, improving its predictive performance. For SVR, feature selection and hyperparameter tuning were applied to enhance its ability to handle complex relationships in the data. This phase focused on building efficient and optimized regression models.

---

## 🔹 Phase 3: Model Evaluation and Comparison

In the final phase, the performance of the trained models was evaluated using R² score and Root Mean Squared Error (RMSE). These metrics helped assess how well each model predicted employee salaries. The Random Forest model achieved the best performance due to its ability to capture non-linear patterns and feature interactions, while SVR showed comparatively lower performance. A comparative analysis was conducted to highlight differences between models, and results were visualized using graphs. This phase concluded the project by identifying the most effective model for salary prediction.
