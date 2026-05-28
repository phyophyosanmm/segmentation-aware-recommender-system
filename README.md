# 🛍️ Segmentation-Aware Recommendation Framework for Sparse E-Commerce Transactional Data

## 📌 Overview

This project presents a **Segmentation-Aware Hybrid Recommendation System** designed to address the challenges of **extremely sparse e-commerce transactional data**. The framework integrates **RFM-based customer segmentation**, **HDBSCAN clustering**, and **Learning-to-Rank recommendation models** to improve recommendation performance for both active and low-engagement users.

The study uses the **Olist Brazilian E-Commerce Dataset** and focuses on solving common recommender system challenges such as:

* ⚠️ Data sparsity
* ❄️ Cold-start users
* 🛒 One-time buyers
* 📉 Low-repeat customer interactions

The proposed framework combines personalized ranking models for dense users with a category-aware popularity fallback strategy for sparse users, ensuring full recommendation coverage.

---

# 🎯 Research Objectives

This project aims to:

* 📊 Evaluate machine learning recommendation models under sparse transactional conditions
* 👥 Investigate the impact of RFM-based customer segmentation on recommendation performance
* ⚖️ Compare segmentation-aware approaches with traditional collaborative filtering
* 🚀 Develop a lightweight and interpretable recommendation framework suitable for SMEs and startups

---

# ✨ Key Features

## 👤 Customer Segmentation

* 📅 RFM (Recency, Frequency, Monetary) feature engineering
* 🧠 Behavioural feature construction
* 🔍 HDBSCAN clustering for sparse user segmentation

## 🤖 Recommendation Models

* 📦 Item-Based Collaborative Filtering
* 🔢 Singular Value Decomposition (SVD)
* 🌟 LightGBM Learning-to-Rank
* ⚡ XGBoost Ranker

## 🔄 Hybrid Recommendation Strategy

* 🎯 Personalized ranking for dense users
* 📈 Category-aware popularity fallback for sparse/noise users
* ❄️ Cold-start handling strategy
* ✅ Full user recommendation coverage

## 📏 Evaluation Metrics

* 🎯 Precision@10
* 🔍 Recall@10
* ⚖️ F1@10
* 📊 NDCG@10

---

# 📂 Dataset

This project uses the publicly available **Olist Brazilian E-Commerce Dataset** from Kaggle.

### Dataset Includes:

* 👥 Customer information
* 📦 Orders
* 🏷️ Products
* 🕒 Purchase timestamps
* 💳 Transaction history

### Dataset Characteristics:

* ⚠️ Highly sparse transactional interactions
* 🛒 More than 90% one-time buyers
* 🌎 Real-world e-commerce purchasing behaviour

---

# 🛠️ Methodology

## 1️⃣ Data Preprocessing

* 🧹 Data cleaning
* ❌ Missing value handling
* 📉 Outlier removal
* ⏳ Temporal train-validation-test split
* 🔄 Feature normalization and transformation

## 2️⃣ Feature Engineering

* 📅 RFM metrics
* 🧠 Behavioural indicators
* ❤️ User-category preference scores
* 🔥 Popularity features

## 3️⃣ Customer Segmentation

* 🔍 HDBSCAN clustering
* 👥 Dense user identification
* 🚨 Noise user detection

## 4️⃣ Recommendation Modelling

* 📦 Baseline collaborative filtering
* 🔢 Matrix factorization (SVD)
* 🌟 Learning-to-Rank models using LightGBM and XGBoost

## 5️⃣ Hybrid Recommendation Strategy

* 🎯 Personalized recommendations for clustered users
* 📈 Popularity-based fallback recommendations for sparse users

---

# 📈 Experimental Results

The proposed segmentation-aware recommendation framework outperformed traditional recommendation methods under sparse data conditions.

## 🏆 Best Performing Model

### 🌟 LightGBM Ranker

| Metric       | Score  |
| ------------ | ------ |
| Precision@10 | 0.0433 |
| Recall@10    | 0.3844 |

### 🔑 Key Findings

* ✅ Behavioural segmentation improves recommendation robustness
* 📈 Popularity features remain important under sparse conditions
* ❄️ Hybrid strategies help address cold-start and ultra-sparse users
* 🚀 Lightweight recommendation systems can still achieve effective personalization

---

# 💻 Technologies Used

## 🐍 Programming Language

* Python

## 📚 Libraries & Frameworks

* Pandas
* NumPy
* Scikit-learn
* LightGBM
* XGBoost
* HDBSCAN
* Matplotlib
* Seaborn

---

# 📁 Project Structure

```bash id="re89x1"
├── data/
├── notebooks/
├── src/
│   ├── preprocessing/
│   ├── feature_engineering/
│   ├── segmentation/
│   ├── recommendation_models/
│   └── evaluation/
├── results/
├── figures/
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## 📥 Clone the Repository

```bash id="s8n2ak"
git clone https://github.com/your-username/your-repository-name.git
```

## 📦 Install Dependencies

```bash id="md2xq3"
pip install -r requirements.txt
```

## ▶️ Run the Project

```bash id="a3d9lm"
python main.py
```

---

# 🔮 Future Improvements

Possible future enhancements include:

* 🌐 Real-time recommendation deployment
* 🧪 Online A/B testing
* 📱 Integration of clickstream and browsing data
* 🧠 Deep learning recommendation models
* ⏱️ Session-based recommendations
* 🔍 Explainable AI recommendation strategies

---

# 🎓 Academic Contribution

This research contributes empirical evidence on the effectiveness of combining:

* 👥 Customer segmentation
* 🧠 Behavioural analytics
* 🌟 Learning-to-Rank recommendation systems

under highly sparse real-world e-commerce conditions.

The framework is especially suitable for:

* 🏪 SMEs
* 🚀 Startups
* 💻 Resource-constrained e-commerce platforms

---

# 👩‍💻 Author

**Phyo Phyo San**
🎓 Master of Data Science and Business Analytics

---

# 📜 License

This project is intended for academic and research purposes.
