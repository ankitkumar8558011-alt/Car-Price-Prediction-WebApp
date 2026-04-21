# 🚗 Car Price Prediction (Machine Learning Project)

Car Price Prediction is a **machine learning project** that estimates the price of used cars based on factors such as year, mileage, fuel type, and company.

The project follows a complete **end-to-end ML lifecycle**, from data cleaning to model building and evaluation.

## 🎯 Problem Statement

The objective of this project is to analyze how the price of a used car is affected by various factors, including:

* Year of manufacturing
* Kilometers driven
* Fuel type
* Car company / model

Using these features, the system predicts the **estimated resale price of a car**.

## 🔄 Machine Learning Lifecycle

This project follows a structured ML workflow:

1. Understanding the problem
2. Data collection
3. Data cleaning & preprocessing
4. Exploratory Data Analysis (EDA)
5. Model training
6. Model evaluation
7. Model selection

## 📂 Data Collection

* **Source:** Kaggle dataset
* Dataset contains **892 car records** with features like:

  * Name
  * Company
  * Year
  * Price
  * Kilometers driven
  * Fuel type

## 🔍 Data Checks Performed

✔ Checked missing values
✔ Checked duplicate records (94 duplicates found)
✔ Verified data types
✔ Analyzed unique values in each column
✔ Generated statistical summaries
✔ Identified inconsistent and noisy data

## 🧹 Data Cleaning & Preprocessing

Key cleaning steps:

* Removed non-numeric values from **year** column
* Converted year from object → integer
* Removed rows with `"Ask For Price"`
* Converted price to numeric format
* Cleaned `kms_driven` (removed "kms" and commas)
* Handled missing values in `fuel_type`
* Reduced car name to first 3 meaningful words
* Removed outliers (price > 60 lakhs)

📌 Final cleaned dataset: **816 records**

## 📊 Exploratory Data Analysis (EDA)

Performed analysis to understand:

* Distribution of car prices
* Impact of year on price
* Relationship between mileage and price
* Price variation across fuel types and companies

## 🤖 Model Building

### Features (X):

* Name
* Company
* Year
* Kilometers driven
* Fuel type

### Target (y):

* Price

### ⚙️ Techniques Used

* Train-test split using Scikit-learn
* Categorical encoding using OneHotEncoder
* Pipeline creation using `make_pipeline`
* Column transformation using `make_column_transformer`

### 📈 Model

* Linear Regression model used
* Evaluated using **R² Score**

## 🛠️ Tech Stack

**Programming →** Python

**Libraries →**
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## ⚙️ How to Run
git clone https://github.com/ankitkumar8558011-alt/Car-Price-Prediction-WebApp.git
cd car-price-prediction

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt
python main.py


## 📊 Output

* Predicted car price based on input features
* Model performance using R² score
* Cleaned dataset exported as CSV

---

## ⭐ Key Highlights

🔥 End-to-end ML project (data → cleaning → model → evaluation)
🔥 Real-world dataset with noisy data handling
🔥 Proper preprocessing pipeline
🔥 Feature engineering and encoding
🔥 Practical problem (used car pricing)


## 👨‍💻 Author

👤 Name - Ankit Kumar

## ⭐ Support

If you like this project, give it a ⭐ on GitHub

