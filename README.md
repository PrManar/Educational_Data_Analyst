# 📊 Education Data Integration & Dashboard Project (Saudi Arabia)

## 📌 Overview

This project focuses on integrating and preparing educational data from multiple regions in Saudi Arabia. The data was sourced from the official open data platform and then combined into a single, analysis-ready dataset.

The final dataset was used to build an interactive dashboard in Power BI.

---

## 🔗 Data Source

The data was obtained from the official Saudi Open Data Platform:

* https://open.data.gov.sa

Each dataset was originally provided per region and already cleaned individually.

---

## 🎯 Objectives

* Combine multiple regional datasets into one unified dataset
* Standardize data across all regions
* Translate Arabic content into English
* Prepare the dataset for visualization
* Build an interactive Power BI dashboard

---

## 🧰 Tools & Technologies

* Python (Pandas)
* Google Colab
* Power BI (Power Query + Visualization)
* GitHub

---

## 🗂️ Dataset Description

The dataset includes:

* Number of students
* Number of teachers
* School-related information
* Regions (e.g., Eastern, Alahsa)
* Gender (Boys / Girls)
* Academic years

---

## ⚙️ Data Preparation Process

### 1. Data Collection

* Downloaded datasets from the Saudi Open Data Platform
* Each file represents a specific region

### 2. Data Integration (Python - Google Colab)

* Combined all regional datasets into one dataset
* Ensured consistent column structure across all files

### 3. Data Transformation

* Translated Arabic values into English
  (e.g., الشرقية → Eastern, الأحساء → Alahsa)
* Converted Arabic numbers to standard numeric format
* Standardized column names

### 4. Data Cleaning in Power BI

* Imported dataset into Power BI
* Used **Power Query** to:

  * Handle missing values
  * Remove empty rows
  * Fix data inconsistencies

### 5. Final Output

* Clean and unified dataset ready for analysis:
  `Final_cleaned_data.csv`

---

## 📊 Dashboard (Power BI)

The dashboard includes:

* **Total Students (KPI)**
* **Students by Gender (Pie Chart)**
* **Students by Region (Bar Chart)**
* **Teachers by Region & Gender (Stacked Chart)**
* Additional insights (e.g., teachers, schools)

---

## 📈 Key Insights

* Comparison of student distribution across regions
* Gender-based analysis (Boys vs Girls)
* Regional education trends

---

## How to Use

1. Open the notebook in Google Colab
2. Run all cells step by step
3. Generate the combined dataset
4. Open Power BI
5. Load the dataset and build visualizations

---

## 📁 Project Structure

```
├── Educational_Data_Preparation.ipynb
├── Final_cleaned_data.csv
└── README.md
```

---

## 👩‍💻 Author

* Manar D. Almutairi

---

## ⭐ Notes

* The original datasets were already cleaned per region
* This project focuses on **data integration, transformation, and visualization**
* Missing data issues were handled inside Power BI by using Power Query

---
