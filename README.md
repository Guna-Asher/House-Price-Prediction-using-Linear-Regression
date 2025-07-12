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


## 📊 Model Results

- **R² Score**: `0.884`  
  The model explains **88.4% of the variance** in house prices, indicating a strong linear relationship between features and target.

- **Mean Squared Error (MSE)**: `17.5 billion`  
  While this number seems large, it's expected due to the scale of housing prices and variability in the dataset.

---

## 🔧 Scope for Improvement

| Strategy                    | Benefit                                           |
|-----------------------------|---------------------------------------------------|
| Remove Outliers             | Helps stabilize predictions and reduce MSE        |
| Apply Feature Scaling       | Improves performance of linear regression         |
| Use Regularized Models      | Ridge or Lasso regression to minimize overfitting |
| Log-transform Price Feature | Normalizes skewed data for better prediction      |
| Feature Selection           | Reduce noise by dropping low-impact features      |
| Build Streamlit or Flask UI | Enables user-friendly, interactive predictions    |

---

## 👤 Author

**Guna**  
🎓 MCA Student @ DSCE Bengaluru  
💻 Focused on data science, automation, and practical tech applications  
🐄 Exploring IoT for smart dairy farming  
📈 Passionate about building efficient systems that merge traditional industries with modern innovation

---

## 📜 License

MIT License  
This project is open-source and free to use, adapt, and extend for learning or development.

