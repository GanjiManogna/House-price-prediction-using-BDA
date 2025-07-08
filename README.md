# House Price Prediction using Big Data Analytics

This project is a simple academic exercise for Big Data Analytics, focusing on predicting house prices using machine learning techniques with PySpark and exploratory data analysis (EDA) in Python.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Key Steps](#key-steps)
- [Results & Visualizations](#results--visualizations)
- [References](#references)

---

## Project Overview

The goal of this project is to predict house prices based on various features using linear regression with PySpark. The project demonstrates:
- Loading and preprocessing data
- Feature engineering
- Building and evaluating a regression model
- Visualizing results and feature relationships

This project was completed as part of my Big Data Analytics coursework.

---

## Technologies Used

- Python (Pandas, Matplotlib, Seaborn)
- PySpark (Spark MLlib)
- Jupyter Notebook / Google Colab

---

## Dataset

- **File:** `HousePricePrediction.xlsx`
- **Source:** Kaggle or geeksforgeeks
- **Features Used:**  
  - LotArea
  - OverallCond
  - YearBuilt
  - TotalBsmtSF
  - SalePrice (target)

---

## Project Structure

```
.
├── bda.ipynb           # Jupyter Notebook with all code and analysis
├── HousePricePrediction.xlsx  # Dataset
└── README.md           # Project documentation
```

---

## How to Run

### **In Google Colab**
1. Upload `HousePricePrediction.xlsx` to your Google Drive.
2. Open `bda.ipynb` in Google Colab.
3. Run all cells in order.

### **In Jupyter Notebook (Local)**
1. Install dependencies:
   ```
   pip install pyspark pandas matplotlib seaborn
   ```
2. Place `HousePricePrediction.xlsx` in your working directory.
3. Open and run `bda.ipynb` in Jupyter Notebook.

---

## Key Steps

1. **Data Loading:**  
   Load the dataset using Pandas and convert it to a PySpark DataFrame.

2. **Data Cleaning:**  
   Select relevant columns and drop rows with missing values.

3. **Feature Engineering:**  
   Assemble features for machine learning.

4. **Model Training:**  
   Train a linear regression model using PySpark MLlib.

5. **Evaluation:**  
   Evaluate the model using RMSE and R² metrics.

6. **Visualization:**  
   - Actual vs Predicted Sale Price scatter plot
   - Residuals plot
   - Correlation heatmap
   - Bar plot of average sale price by overall condition

---

## Results & Visualizations

- The model provides a basic prediction of house prices based on selected features.
- Visualizations help understand feature relationships and model performance.

![Screenshot 2025-07-08 171658](https://github.com/user-attachments/assets/039ad088-5643-433a-8d4c-69318eb43462)
![Screenshot 2025-07-08 171719](https://github.com/user-attachments/assets/90a37b61-c2a4-4af4-8b54-8651fc2589ad)
![Screenshot 2025-07-08 171734](https://github.com/user-attachments/assets/75fe79c0-3724-4ef8-9ee7-f48b765d1b28)
![Screenshot 2025-07-08 171753](https://github.com/user-attachments/assets/0355d9ad-e2a0-447c-849d-f1df2d0bb6fe)

---

## References

- [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/)
- [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- [Project Notebook on GitHub](https://github.com/GanjiManogna/House-price-prediction-using-BDA/blob/main/bda.ipynb)

---

**This project was completed as part of my Big Data Analytics coursework.**
