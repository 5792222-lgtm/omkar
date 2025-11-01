# 🏪 EDA Project: Dirty Cafe Sales Dataset

## 📘 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a sample cafe sales dataset called **Dirty Cafe Sales**. The goal is to explore, clean, visualize, and extract meaningful insights from the data to understand sales trends, customer preferences, and payment behaviors.

---

## 📊 Dataset Description

**File Name:** `dirty_cafe_sales.csv`
**Records:** 10,000 rows
**Attributes (Columns):**

1. Transaction ID
2. Item
3. Quantity
4. Price Per Unit
5. Total Spent
6. Payment Method
7. Location
8. Transaction Date

**Source:** Open-source sample dataset (simulated for EDA practice)

---

## 🧭 EDA Objectives

* Understand the structure and summary of the dataset.
* Detect and handle missing, inconsistent, and erroneous values.
* Perform data cleaning and type conversions.
* Identify outliers and handle them appropriately.
* Conduct univariate, bivariate, and multivariate analysis.
* Visualize distributions, correlations, and trends.
* Derive actionable insights about customer and sales behavior.

---

## ⚙️ Steps Performed

### 1️⃣ Dataset Overview

* Displayed dataset shape, columns, and data types.
* Counted missing and duplicate values.
* Checked unique values per column.

### 2️⃣ Data Quality Checks

* Identified invalid placeholders like `ERROR` and `UNKNOWN`.
* Found formatting inconsistencies and null entries.

### 3️⃣ Data Cleaning

* Replaced invalid placeholders with `NaN`.
* Converted numeric columns to proper data types.
* Imputed missing values using median/mode.
* Removed duplicate entries.

### 4️⃣ Descriptive Statistics

* Calculated mean, median, mode, variance, and standard deviation.
* Summarized categorical variables using value counts.

### 5️⃣ Outlier Detection

* Applied **IQR method** and visualized using **boxplots**.
* Identified and analyzed extreme spending values.

### 6️⃣ Data Visualization

* **Univariate:** Histograms, boxplots, and bar charts.
* **Bivariate:** Scatter plots and heatmaps for correlations.
* **Multivariate:** Pairplots for item-wise trends (optional).

### 7️⃣ Insights & Interpretation

* Found most frequently sold items and high-revenue products.
* Observed sales patterns by payment method and location.
* Noted the effect of item pricing on total spending.

---

## 🧠 Key Insights

* **Top-Selling Items:** Coffee and Sandwiches dominate sales volume.
* **Preferred Payment Methods:** Digital Wallets and Cash are most common.
* **Location Trend:** In-store purchases slightly outnumber takeaways.
* **Sales Anomalies:** Some rows contained invalid totals (`ERROR`), cleaned during preprocessing.

---

## 🧰 Tools and Libraries Used

* **Python 3**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib** & **Seaborn** – Data visualization

---


## 📁 Repository Structure

```
EDA_DirtyCafeSales_<RollNo>/
│
├── dirty_cafe_sales.csv               # Dataset file
├── EDA_DirtyCafeSales_<RollNo>.ipynb  # Main notebook
├── README.md                          # Project documentation
└── visuals/                           # Optional plots & images

