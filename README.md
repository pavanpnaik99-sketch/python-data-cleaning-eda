# Amazon Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on **cleaning and analyzing an Amazon-related dataset using Python**.  
The primary goal is to convert raw, messy data into a clean and analysis-ready format, followed by basic exploratory data analysis (EDA) to extract insights.

The notebook demonstrates a realistic data preprocessing workflow used in real-world data analysis tasks.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Description
- Input format: CSV file
- Contains Amazon-related data such as artist names, tour titles, gross values, peak rankings, and references
- Raw dataset includes:
  - Special characters
  - Text-based numeric values
  - Missing and inconsistent data
  - Unnecessary columns

---

## 🧹 Data Cleaning Performed
The following data cleaning steps were applied:

- Removed special characters from text fields using regular expressions
- Cleaned numeric columns by removing symbols and converting them to numeric types
- Handled missing values by filling them with statistical measures (mean)
- Dropped irrelevant columns not required for analysis
- Standardized text values for consistency
- Converted date fields into proper datetime format
- Created derived columns for further analysis
- Ensured correct data types across all columns

These steps transformed the raw dataset into a structured and reliable format suitable for analysis.

---

## 🔍 Exploratory Data Analysis (EDA)
- Aggregated gross revenue by artist
- Sorted and analyzed top-performing artists
- Examined distributions and rankings using visualizations
- Identified patterns and trends in cleaned data

---

## 📊 Visualizations
Visual analysis was performed using:
- Bar charts
- Distribution plots
- Count-based visualizations

These plots help in understanding trends and comparative performance within the dataset.

---


