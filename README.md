# 📊 Education Data Integration & Dashboard Project (Saudi Arabia)

## 📌 Overview

This project focuses on integrating educational datasets from multiple regions in Saudi Arabia into a single unified dataset, followed by building an interactive Power BI dashboard.

The data was sourced from the official Saudi Open Data Platform and transformed for analysis and visualization.

---

## 🔗 Data Source

The data was obtained from the official Saudi Open Data Platform:

* https://open.data.gov.sa

Each dataset was originally provided per region and already cleaned individually.

---

## 🎯 Objectives

* Combine multiple regional datasets into one dataset
* Standardize structure across all files
* Translate Arabic data into English
* Prepare data for visualization
* Build an interactive dashboard using Power BI

---

## 🧰 Tools & Technologies

* Python (Pandas)
* Google Colab
* Power BI (Power Query + Visualization)
* GitHub

---

## ⚙️ Data Preparation Process

### 1. Data Collection

* Downloaded datasets for different regions from the Open Data Platform

### 2. Data Integration (Python)

* Combined all regional datasets into one dataset
* Ensured consistent column structure

### 3. Data Transformation

* Translated Arabic values to English
  (e.g., الشرقية → Eastern, الأحساء → Alahsa)
* Converted Arabic numbers to standard numeric format
* Standardized column names

### 4. Data Cleaning (Power BI)

* Used **Power Query** to:

  * Handle missing values
  * Remove empty rows
  * Fix inconsistencies

### 5. Final Output

* Clean dataset ready for analysis:
  `Final_cleaned_data.csv`

---

## 📊 Dashboard

The Power BI dashboard includes:

* Total Students (KPI)
* Students by Gender
* Students by Region
* Teachers by Region & Gender
* Additional insights (teachers, schools)

📸 *See screenshot in the Dashboard folder*

---

## 📁 Project Structure

```
├── 📁 dashboard/
│   ├── dashboard_screenshot.png
│   
│
├── 📁 code/
│   └── Educational_Data_Preparation.ipynb
│
├── 📁 data/
│   └── Final_cleaned_data.csv
│
└── README.md
```

---

## 📈 Key Insights

* Student distribution across regions
* Gender comparison (Boys vs Girls)
* Regional trends in education data

---

## 🚀 How to Use

1. Open the notebook from the `code/` folder in Google Colab
2. Run all cells to generate the dataset
3. Open Power BI
4. Load the dataset from the `data/` folder
5. Explore or rebuild the dashboard

---

## 👩‍💻 Author

* Manar D. Almutairi

---

## ⭐ Notes

* Original datasets were already cleaned per region
* This project focuses on **data integration and visualization**
* Missing data issues were resolved using Power Query in Power BI

---


---
