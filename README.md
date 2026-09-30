# 🛒 Retail Transaction Analysis & Prediction

This repository contains an end-to-end analysis of a mock retail transaction dataset as part of an internship assessment. The goal was to understand customer behavior, perform sales analysis, engineer features, and develop predictive models to classify high-value customers.

---

## 📁 Dataset

The dataset used is `retail_data.csv` with the following fields:
- `InvoiceNo`: Unique transaction ID
- `StockCode`: Product code
- `Description`: Product name
- `Quantity`: Units sold
- `InvoiceDate`: Transaction timestamp
- `UnitPrice`: Price per unit
- `CustomerID`: Unique customer ID
- `Country`: Purchase country
- `TotalPrice`: Computed as Quantity × UnitPrice

---

## 🔍 Project Objectives

- Clean and preprocess retail transaction data
- Perform exploratory data analysis (EDA) with visualizations
- Engineer customer-level features (e.g., basket size, total spend)
- Train classification models to predict high-value customers
- Analyze feature importance and provide business insights

---

## 📊 Key Techniques Used

- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost
- **EDA**: Time series sales trends, top products, country-wise performance
- **Feature Engineering**:
  - TotalSpend per customer
  - PurchaseFrequency
  - Average basket size
  - Average spend per basket
- **Models**:
  - Random Forest Classifier
  - XGBoost Classifier
- **Evaluation**: Accuracy, Precision, Recall, F1-Score
- **Feature Importance**: Identified key drivers of high customer value

---

## 📌 Project Highlights

- Perfect model accuracy using Random Forest (due to small dataset)
- XGBoost achieved 92% accuracy with balanced metrics
- High-value customers typically spend more per transaction and buy in larger quantities
- Marketing recommendation: focus on customers with high basket size and per-order spend

---

## 📁 Files in the Repo

- `Retail_Analysis_Notebook.ipynb` – Complete Colab notebook with code, EDA, and modeling
- `retail_data.csv` – Sample dataset
- `README.md` – Project overview

---

## 🚀 Future Enhancements

- Use a larger, real-world dataset for better generalization
- Include seasonal trends, discount flags, and product categories
- Perform unsupervised clustering for customer segmentation
- Build time-series forecasting models for revenue or product demand

---

## 📬 Contact

For any questions or suggestions, feel free to connect via dhawan.nitya@gmail.com.

---

