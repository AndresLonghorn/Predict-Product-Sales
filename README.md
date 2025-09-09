# 🎮 Video Game Genre Sales Analysis by Platform

## 📌 Project Overview
This project aims to help video game companies understand which genres perform best across different gaming platforms. As physical copies of video games are phasing out and becoming downloadable, video game companies still need to manage cost of doing business. By analyzing historical sales data and applying machine learning models, we can identify key patterns and predictive factors that influence global sales performance and thus improve gross margins by producing more genres that buyers want.
Below summarizes, the data, machine learning models used, results and conclusions. 

## 📊 Dataset
The dataset includes video game sales information with features such as:
- Regional Sale Data: North American `NA_Sales`, European `EU_Sales`, Japanese `JP_Sales`, Other Countries, `Other_Sales`, Total Sales `Global_Sales`
- Metadata: Gaming console `Platform`, `Year`, Video game company `Publisher`
- Target variable: Game genre `Genre`,

<img width="320" height="236" alt="image" src="https://github.com/user-attachments/assets/3a743043-5c13-460a-9a28-187d2c56b9da" />

- North America is the largest regional purchaser of video games in the dataset
  
<img width="494" height="247" alt="image" src="https://github.com/user-attachments/assets/962c77bb-c56f-487b-ad35-79193dd9783a" />

- Sale trend per region

<img width="488" height="326" alt="image" src="https://github.com/user-attachments/assets/6ad9b8b8-1f80-47eb-ab59-a8cba451b15c" />

- Top 5 sellers by region

## 🧠 Modeling Approach
We used a **Decision Tree** & **Random Forest Classifier** to predict video game genres based on sales and metadata.
-  Train/Test split
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
