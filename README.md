# 🏠 Bengaluru House Price Prediction

This project focuses on building a machine learning model to predict house prices in **Bengaluru, India**, using a dataset containing various features of residential properties.

---

## 📌 Project Overview

The goal is to develop a predictive model that can estimate the **price of a house** based on its attributes such as:

- Location  
- Area (in square feet)  
- Number of bathrooms  
- Number of balconies  
- Number of bedrooms  

---

## 📂 Dataset

The dataset used in this project is:

- **`Bengaluru_House_Data.csv`**  
It contains information on property listings including location, size, total square feet, number of bathrooms, balconies, and price.

---

## 🚀 Project Workflow

1. **Data Loading and Exploration**  
   Load the dataset and explore its structure, shape, and key statistics.

2. **Data Cleaning**  
   Remove irrelevant columns (like `society` or `availability`), handle missing values, and clean `size` and `total_sqft` columns.

3. **Feature Engineering**  
   Add new features such as:  
   - `sqft_per_bed` (square feet per bedroom)  
   - `price_per_sqft` (price per square foot)

4. **Outlier Removal**  
   Remove entries with unrealistic or extreme values for `sqft_per_bed` and `price_per_sqft`.

5. **Data Preprocessing**  
   - Encode categorical variables (`location`)  
   - Scale numerical features

6. **Model Building**  
   Train a **Linear Regression** model using a pipeline with preprocessing steps.

7. **Model Evaluation**  
   Use **R² Score** to evaluate model performance on unseen test data.

8. **Prediction**  
   Use the trained model to predict house prices based on user input via console or form.

---

## 🧰 Technologies Used

- Python 🐍  
- pandas 🐼  
- numpy 🔢  
- scikit-learn ⚙️  
- matplotlib / seaborn 📊 (for optional visualization)
