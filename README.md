# 🎮 Video Game Genre Sales Analysis by Platform

## 📌 Project Overview
This project aims to help video game companies understand which genres perform best across different gaming platforms. By analyzing historical sales data and applying machine learning models, we can identify key patterns and predictive factors that influence global sales performance and thus profits.
Below summarizes, the data, machine learning models used, results and conclusions. 

## 📊 Dataset
The dataset includes video game sales information with features such as:
- Regional sales: `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`
- Metadata: `Platform`, `Year`, `Genre`, `Publisher`
- Target variable: `Global_Sales`

## 🧠 Modeling Approach
We used a **Random Forest Classifier** to predict video game genres based on sales and metadata. The model was trained and evaluated using:
- Train/Test split
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- Feature Importance Analysis

### 🔍 Key Modeling Steps
- Label encoding for categorical variables
- Hyperparameter tuning for optimal tree depth and split criteria
- Visualization of classification performance and confusion matrix

## ✅ Results
- **Model Accuracy**: ~89.2%
- **Cross-Validation Score**: ~96%
- **ROC AUC Score**: ~99.5%
- Balanced performance across most genre classes
- Strong generalization with minimal overfitting

## 📈 Key Insights for Game Companies
- **Regional sales** (especially NA and EU) are strong predictors of global success.
- Certain genres consistently outperform others on specific platforms.
- Feature importance analysis reveals which attributes drive genre classification.
- Confusion matrix and classification report help identify areas for improvement in genre targeting.

## 📦 Deliverables
- Decision Tree and Random Forest models
- Performance visualizations (bar charts, confusion matrix)
- Feature importance graphs
- Classification report summaries

## 🚀 Future Work
- Expand dataset with more recent titles and platforms
- Explore ensemble models like Gradient Boosting
- Integrate time-series analysis for sales trends

---

## 👤 Author
Andres Salcido
