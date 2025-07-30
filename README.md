# 🚗 Ford Car Price Prediction

This project aims to predict the **price of used Ford cars** using various features such as model, year, mileage, transmission type, fuel type, engine size, etc., by applying **linear regression** techniques.

---

## 📂 Dataset

The dataset is sourced from Kaggle:  
👉 [Ford Car Price Prediction Dataset](https://www.kaggle.com/datasets/hellbuoy/ford-car-price-prediction)

> **Note:** The dataset file (`ford.csv`) is not included in this repository. Please download it manually from the above link and place it in the root directory of the project.

---

## 📊 Features in the Dataset

| Column        | Description                            |
|---------------|----------------------------------------|
| model         | Car model (e.g., Fiesta, Focus, etc.)  |
| year          | Manufacturing year                     |
| price         | Price in GBP                           |
| transmission  | Type of transmission                   |
| mileage       | Distance covered                       |
| fuelType      | Type of fuel used                      |
| tax           | Annual road tax                        |
| mpg           | Miles per gallon (fuel efficiency)     |
| engineSize    | Size of engine in liters               |

---

## 🔍 Exploratory Data Analysis (EDA)

- Distribution of car prices
- Correlation heatmap between numerical features
- Boxplots by year, model, transmission, and fuelType
- Scatter plots for price vs mileage

---

## 🧪 Machine Learning Models Used

### ✅ Linear Regression (with One-Hot Encoding)
- Preprocessing:
  - One-hot encoded categorical variables
  - Standard scaled numerical features
- Achieved **R² Score:** `0.8396`  
- **Adjusted R² Score:** `0.8387`

### ✅ Linear Regression (with Label Encoding)
- Used Label Encoding for categorical features
- Standard scaled all features
- Achieved **R² Score:** `0.7310`

---

## 📈 Results

| Encoding Technique | R² Score | Adjusted R² Score |
|--------------------|----------|-------------------|
| One-Hot Encoding   | 0.8396   | 0.8387            |
| Label Encoding     | 0.7310   | N/A               |

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn & Matplotlib (for EDA)
