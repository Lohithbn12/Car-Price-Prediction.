# Car Price Prediction

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Regression](https://img.shields.io/badge/Regression-00B4D8?style=for-the-badge)

A machine learning project that **predicts the price of a car** from its features, such as brand, age, mileage, engine and fuel type.

---

## 🎯 Problem Statement

Pricing a used car fairly is hard: price depends on many factors at once, and buyers and sellers often disagree on its value.

This project builds a **regression model** that estimates a car's price from its specifications, giving buyers, sellers and dealers a data-driven reference price.

---

## 📦 Files in this Repository

| File | Description |
|---|---|
| `car_price_pridection_project.ipynb` | Full analysis notebook (data exploration, preprocessing, modeling, evaluation) |
| `data.csv` | Car dataset used for training and testing |
| `README.md` | Project documentation |

---

## 🔄 Workflow

1. **Load and inspect** the dataset
2. **Clean the data:** handle missing values, duplicates and outliers
3. **Explore** which features influence price (correlations and visualizations)
4. **Preprocess:** encode categorical features and scale numeric features where needed
5. **Train** regression models and compare them
6. **Evaluate** on a held-out test set using R², MAE and RMSE

---

## 🛠️ Tools Used

- **Python**
- **pandas** and **NumPy** for data handling
- **scikit-learn** for modeling and evaluation
- **Matplotlib** / **Seaborn** for visualization
- **Jupyter Notebook**

---

## ▶️ How to Run

```bash
# 1) Clone the repository
git clone https://github.com/Lohithbn12/car-price-prediction.git
cd car-price-prediction

# 2) Create an environment and install the libraries
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# 3) Launch the notebook
jupyter notebook
```

Open the notebook and run the cells from top to bottom. Keep `data.csv` in the same folder as the notebook so the file path works.

---

<!--
## 📊 Results (uncomment and fill in from your notebook)

| Model | R² | MAE | RMSE |
|---|:---:|:---:|:---:|
| Linear Regression | | | |
| Random Forest | | | |
| Gradient Boosting | | | |

**Best model:** ...

**Most important features:** ...

![Actual vs predicted](images/actual_vs_predicted.png)
![Feature importance](images/feature_importance.png)
-->

## 💡 Key Insights

<!-- Add 2 or 3 findings, for example which features affect price most and how accurate the final model is. -->

---

## 🚀 Possible Next Steps

- Tune hyperparameters with cross-validated search
- Try gradient boosting models (XGBoost, LightGBM)
- Add feature engineering (for example car age from the year)
- Deploy as a simple web app where users enter car details and get a price estimate

---

## 👤 Author

**Lohith B N** · [Portfolio](https://portfolio-0lzq.onrender.com/) · [LinkedIn](https://www.linkedin.com/in/lohith-b-n/) · [GitHub](https://github.com/Lohithbn12)
