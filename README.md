# 📊 Telco Customer Segmentation & Churn Prediction Pipeline

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-yellowgreen)

> An end-to-end data science workflow on the Telco subscriber dataset. The objective is twofold: first, to group customers based on behavioral attributes using unsupervised learning, and second, to predict potential churn using a tuned machine learning model.

## 📑 Table of Contents
- [Key Insights & Objectives](#-key-insights--objectives)
- [Tech Stack Used](#-tech-stack-used)
- [Project Structure](#-project-structure)
- [Model Performance](#-model-performance)

## 🎯 Key Insights & Objectives
1. **Exploratory Data Analysis**: Visualized continuous features like tenure months and monthly charges to spot outlier behaviors and class imbalances across subscriber metrics.
2. **Customer Segmentation**: Applied K-Means Clustering to partition the scaled feature space into 4 distinct customer personas, allowing targeted retention strategies.
3. **Supervised Modeling**: Implemented a Random Forest Classifier optimized via `RandomizedSearchCV` to accurately handle non-linear decision boundaries and identify primary churn drivers.

## 💻 Tech Stack Used

| Category | Tools |
|---|---|
| **Environment** | Google Colab / Jupyter Notebooks |
| **Data Core** | Python, Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-Learn (`StandardScaler`, `KMeans`, `RandomForestClassifier`) |

## 📂 Project Structure
```text
├── CBSOT_SIP_PROJECT-1.ipynb   # Main Jupyter Notebook with complete ML pipeline
├── architecture.md             # System architecture and data flow diagram
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
