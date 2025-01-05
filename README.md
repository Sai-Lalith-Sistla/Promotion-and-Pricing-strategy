# Experimenting with ML, AI & DL Techniques for Promotion and Price Prediction

Alternate key words : Promotion Price Sensitivity

## What is the purpose of this repository?

The purpose of this repository is to explore and document the best Machine Learning (ML), Artificial Intelligence (AI), and Deep Learning (DL) techniques for predicting product promotions and prices. By focusing on selected models and evaluation metrics, we aim to identify the most effective approaches for different use cases.

---

## What are the key goals of the project?

1. Experiment with the most effective ML, AI, and DL techniques.
2. Evaluate the effectiveness of these techniques for promotion and price prediction.
3. Provide a structured comparison of models, use cases, and evaluation metrics.
4. Share insights and best practices for similar applications.

---

## What techniques are explored in this project?

### Selected Techniques:

#### Machine Learning:
1. **Gradient Boosting (e.g., XGBoost, LightGBM)** - Known for its high performance on structured data.
2. **Random Forests** - Reliable for interpretability and handling imbalanced datasets.

#### Deep Learning:
1. **Long Short-Term Memory Networks (LSTM)** - Effective for capturing temporal patterns in price trends.
2. **Artificial Neural Networks (ANN)** - Versatile for capturing nonlinear relationships in data.

#### AI Techniques:
1. **Reinforcement Learning** - Suitable for dynamic pricing strategies.
2. **Clustering for Market Segmentation** - Helps in understanding customer groups and targeting promotions.

---

## Q4: What datasets are used in this project?

This project uses publicly available datasets such as:
- Retail price and promotion datasets (e.g., Kaggle, UCI).
- Simulated datasets to demonstrate techniques.
- Custom datasets with synthetic noise for robustness testing.

---

## Q5: What is the table of use cases and evaluation metrics?

| **Use Case**                     | **Technique**                   | **Best Evaluation Metrics**        | **Why**                                                                                      |
|----------------------------------|---------------------------------|------------------------------------|---------------------------------------------------------------------------------------------|
| Promotion Effectiveness Analysis | Gradient Boosting, Random Forests | F1-Score, Precision-Recall AUC    | Handles class imbalance and provides interpretable feature importance.                     |
| Price Prediction                 | Gradient Boosting, LSTM         | RMSE, MAPE                         | RMSE captures absolute error, and MAPE evaluates relative error useful for pricing.         |
| Demand Forecasting               | LSTM                            | MAE, RMSE                          | Captures time series trends, where absolute error minimization is crucial.                  |
| Dynamic Pricing                  | Reinforcement Learning          | Reward Function (e.g., Revenue)    | Maximizes cumulative revenue or profit, aligning directly with business goals.              |
| Market Segmentation              | Clustering                     | Silhouette Score, Davies-Bouldin Index | Assesses cluster cohesion and separation for effective segmentation.                       |

---
