# 🏠 California Housing Price Prediction

### 📊 End-to-End Machine Learning Pipeline with Multi-Model Benchmarking

---

## 📖 Overview

This project presents a complete machine learning workflow to predict housing prices using the California Housing dataset.
It includes data analysis, feature engineering, preprocessing pipelines, and benchmarking of multiple regression models.

The goal is to identify the most accurate model for real-world housing price prediction.

---

## 🔗 Kaggle Integration

This project is originally developed and executed on Kaggle.

* 👤 **Kaggle Profile:**
  [PrajwalKedari](https://www.kaggle.com/code/prajwalkedari)

* 📊 **Kaggle Notebook:**
  [![Open in Kaggle](https://img.shields.io/badge/Kaggle-View%20Notebook-blue?logo=kaggle)](https://www.kaggle.com/code/prajwalkedari/california-housing-benchmark-20-regressors-pipelin)

---

## ✨ Key Highlights

* 🔍 Evaluated 20+ regression models
* ⚙️ Built a complete preprocessing pipeline using Scikit-Learn
* 🛠️ Applied feature engineering for improved performance
* 🎯 Performed hyperparameter tuning on top models
* 🏆 Achieved best performance using XGBoost (~0.81 R² score)

---

## 🗂️ Dataset Description

The dataset contains housing information across different districts in California.

**Features include:**

* 📍 Geographic data (latitude, longitude)
* 👥 Demographic data (population, households)
* 💰 Economic indicators (median income)
* 🏘️ Housing attributes (rooms, bedrooms)

**🎯 Target Variable:**

* `median_house_value`

---

## 🔄 Machine Learning Workflow

1. 🔍 Exploratory Data Analysis (EDA)
2. 🛠️ Feature Engineering
3. ⚙️ Data Preprocessing Pipeline
4. 🤖 Model Training (20+ models)
5. 📈 Model Evaluation (R² score)
6. 🎯 Hyperparameter Tuning
7. 📊 Model Comparison and Visualization

---

## 📊 Model Performance

| Model             | R² Score |
| ----------------- | -------- |
| 🏆 XGBoost        | ~0.81    |
| Gradient Boosting | ~0.77    |
| Extra Trees       | ~0.77    |
| Random Forest     | ~0.77    |
| KNN               | ~0.70    |
| Linear Models     | Low      |

---

## 📁 Project Structure

```
california-housing-ml-project/
│
├── california-housing.ipynb
├── README.md
└── requirements.txt (optional)
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/your-username/california-housing-ml-pipeline.git
cd california-housing-ml-pipeline
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the notebook:

```
jupyter notebook california-housing.ipynb
```

---

## 📌 Results and Insights

* 💰 Median income is the most influential feature
* 📊 Feature engineering significantly improves performance
* 🌲 Ensemble models outperform linear models
* 🏆 XGBoost provides the best results

---

## 🚀 Future Improvements

* ⚡ Hyperparameter tuning with advanced methods (Optuna)
* 🌐 Deployment using Streamlit or Flask
* 🔄 Integration with real-time data sources

---

## 👤 Author

**Prajwal Kedari**

---

## 📜 License

This project is open-source and available for educational purposes.
