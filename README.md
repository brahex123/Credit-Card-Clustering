# 💳 Credit Card Client Segmentation

This project focuses on unsupervised learning for segmenting credit card customers based on their spending behavior. The analysis is performed using clustering techniques such as K-Means and PCA for dimensionality reduction.

---

## 📌 Project Objectives

- Identify distinct customer segments based on transaction patterns
- Apply PCA to reduce feature dimensionality
- Perform K-Means clustering
- Visualize customer clusters and behavioral trends

---

## 📁 Project Files

```
CreditCardSegmentation/
├── CrediCardClass.ipynb     # Main notebook with preprocessing, PCA, clustering and visualizations
├── CC GENERAL.csv           # Dataset with anonymized credit card customer data
└── README.md                # Project documentation
```

---

## 🧪 Techniques Used

- Data Cleaning & Normalization
- Principal Component Analysis (PCA)
- K-Means Clustering
- Elbow Method and Silhouette Score
- Cluster Profiling & Visualization

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

2. Launch the notebook:

```bash
jupyter notebook CrediCardClass.ipynb
```

---

## 📊 Dataset Description

- **Source**: [Kaggle Dataset – CC GENERAL.csv]
- **Size**: 8,950 rows × 18 features
- Includes anonymized features such as:
  - Balance, Purchases, Credit Limit, Tenure, Payment Ratio, etc.

---

## 📈 Insights

- Customers are grouped into segments with similar financial behavior.
- PCA helped reduce noise and improve clustering accuracy.
- Useful for marketing strategies, risk assessment, and customer retention.

---

## 👨‍💻 Author

- **Brahim Mechaouat**  
  [Portfolio](https://brahex123.github.io/ibrahex123.github.io/)  
  [GitHub](https://github.com/brahex123)

---

## 📄 License

MIT License – open for educational and analytical use.
