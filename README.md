# Predict Product Sales with AI (Decision Tree Models)
## Overview
This project explores the use of Decision Tree classification to predict future product sales based on historical data. The goal is to identify patterns and features that influence sales outcomes, enabling smarter forecasting and business decisions.

## Dataset

The dataset includes various product-related features such as:
- Product category
- Sales volume
- Pricing
- Promotion status
- Store location
- Seasonal indicators
## 🧠 Modeling Approach
- **Model Used**: Decision Tree Classifier
- **Target Variable**: Sales category (e.g., low, medium, high)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score

## ✅ Results
- **Overall Accuracy**: 81%
- **Class 0 & 1**: High precision and recall (F1-score ~0.86)
- **Class 2**: Lower recall (0.55), indicating room for improvement

## 🔍 Key Highlights
- The model effectively identifies products likely to sell well.
- Feature importance analysis reveals key drivers of sales.
- Can be used to support inventory planning and promotional strategies.
- Offers a foundation for more advanced forecasting models (e.g., Random Forest, Gradient Boosting).

## 🚀 Future Enhancements
- Improve Class 2 prediction using data balancing techniques.
- Explore ensemble models for better generalization.
- Integrate time-series elements for dynamic forecasting.

## 🛠️ How to Run
1. Clone the repository.
2. Open `Predicting Sales.ipynb` in Jupyter Notebook.
3. Run all cells to preprocess data, train the model, and view results.

## 📄 License
MIT License

## 👤 Author
Andres Salcido
