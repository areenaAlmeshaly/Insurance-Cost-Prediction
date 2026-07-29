# 💰 Insurance Cost Prediction

This project applies Linear Regression and Polynomial Regression to predict medical insurance charges using demographic and health-related features.

The notebook includes data preprocessing, exploratory data analysis (EDA), data visualization, model training, and model evaluation.

---

## 📂 Repository Structure

```text
Insurance-Cost-Prediction/
│
├── insurance.csv
├── Insurance_Cost_Prediction.ipynb
└── README.md
```

---

## 📊 Dataset

The dataset contains demographic and health-related information used to predict medical insurance charges.

### Features

- Age
- Sex
- BMI
- Number of Children
- Smoker Status
- Region

### Target

- Insurance Charges

**Source:** https://www.kaggle.com/datasets/mirichoi0218/insurance/data

---

## 🔍 Exploratory Data Analysis

The notebook includes the following visualizations:

- Distribution of numerical features
- Correlation heatmap
- Pairplot
- Charges by sex and smoking status
- BMI vs. Charges
- Age vs. Charges
- Smoking status for individuals aged 18–19
- Average charges by region
- Average charges by number of children

---

## 🤖 Models

### Linear Regression

| Metric | Value |
|--------|-------:|
| MAE | 4155.24 |
| RMSE | 5814.25 |
| R² Score | 0.7694 |

### Polynomial Regression (Degree = 2)

| Metric | Value |
|--------|-------:|
| MAE | 2677.90 |
| RMSE | 4469.53 |
| R² Score | 0.8638 |

---

## 🛠 Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/Insurance-Cost-Prediction.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Open the Jupyter Notebook and run all cells.

---

## 👩‍💻 Author

**Areena Almeshaly**
