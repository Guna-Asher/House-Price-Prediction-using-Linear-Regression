# 🏡 House Price Prediction using Linear Regression

This project applies **linear regression** to predict house prices based on multiple features from the **King County House Sales dataset**, sourced via Kaggle. It includes data preprocessing, model training, performance evaluation, and visualization—all built using Python, pandas, scikit-learn, and seaborn.

---

## 📁 Project Structure

- `House Price Prediction using Linear Regression.ipynb`: Main notebook with step-by-step implementation
- `kc_house_data.csv`: Dataset used, downloaded via `kagglehub`
- Optional derived features: `house_age`, `price_per_sqft`

---

## 🧰 Tech Stack & Libraries

| Tool            | Purpose                     |
|-----------------|-----------------------------|
| Python 3.12+     | Programming language        |
| pandas, numpy   | Data manipulation            |
| scikit-learn    | Machine learning             |
| matplotlib, seaborn | Visualization            |
| kagglehub       | Dataset retrieval from Kaggle |

---

## 📦 Dataset Overview

- **Source**: [Kaggle - House Sales Prediction](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)
- **Location**: King County, USA
- **Sample Size**: ~21,000 house listings
- **Features**: bedrooms, bathrooms, sqft_living, grade, view, waterfront, condition, location, and sale price

---

## 🚀 How to Run This Project

1. **Install dependencies**:
   ```bash
   pip install kagglehub pandas scikit-learn matplotlib seaborn
