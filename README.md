# Customer Segmentation Blueprint: Unsupervised Discovery of Actionable Personas with PCA & K-Means

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)


## Project Overview

This project implements a complete **enterprise-grade unsupervised learning pipeline** to segment mall customers into actionable business personas.

We follow the exact 4-phase architecture:

1. **SCALE** → Standardization (StandardScaler)
2. **COMPRESS** → Principal Component Analysis (PCA)
3. **CLUSTER** → K-Means + Elbow Method + Silhouette Score
4. **TRANSLATE** → Reverse-engineering centroids into clear marketing personas

---

## Key Features

- Full end-to-end pipeline from raw data to business strategy
- Proper feature scaling to avoid distance distortion
- PCA for dimensionality reduction and visualization
- Optimal K selection using both **Elbow Method** and **Silhouette Score**
- Reverse transformation of cluster centroids back to original scale
- Strategic Persona Matrix with recommended marketing actions
- Clean, well-documented Jupyter Notebook ready for portfolio

---

## Dataset

**Mall Customers Dataset** (200 customers)

| Feature              | Description                                      |
|----------------------|--------------------------------------------------|
| CustomerID           | Unique ID                                        |
| Gender (Genre)       | Male / Female                                    |
| Age                  | Age in years                                     |
| Annual Income (k$)   | Annual income in thousands of dollars            |
| Spending Score (1-100)| Score based on customer behavior and spending   |

---

## Final Customer Personas (K=4)

| Cluster | Persona                          | Avg Age | Income (k$) | Spending Score | Strategy                              |
|---------|----------------------------------|---------|-------------|----------------|---------------------------------------|
| 0       | The Affluent Conservatives       | ~41     | ~88         | ~17            | High-touch support, loyalty programs  |
| 1       | The High-Value Trendsetters      | ~33     | ~86         | ~82            | Exclusive perks, early access, VIP    |
| 2       | The Budget-Conscious Explorers   | ~25     | ~26         | ~79            | Flash sales, influencer, BNPL         |
| 3       | The Conservative Minimizers      | ~45     | ~26         | ~21            | Value pricing, basic products         |

---

## Project Structure
Customer-Segmentation-PCA-KMeans/
│
├── Customer_Segmentation_Blueprint.ipynb   # Main notebook (complete pipeline)
├── Mall_Customers.csv                      # Original dataset
├── Mall_Customers_Segmented.csv            # Dataset with cluster labels
├── Customer_Personas_Summary.csv           # Persona summary table
├── README.md
└── requirements.txt


## Tech Stack

Python 3.8+
Pandas, NumPy
Scikit-learn (StandardScaler, PCA, KMeans, Silhouette)
Matplotlib & Seaborn
Jupyter Notebook


## Key Learnings

Why feature scaling is mandatory for distance-based algorithms
How PCA helps fight the Curse of Dimensionality
How to choose optimal K using Elbow + Silhouette
How to translate mathematical clusters into real business strategy


## Hope this will helpful for you Gyz!!!
