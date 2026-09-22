# 🛒 E-commerce Sales Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing a large **E-commerce Sales dataset containing around 1.1 million records** using Python.

The main objective of this project is to explore sales data, understand product and category performance, analyze quantities and prices, and identify sales trends across different cities and months.

The analysis was performed using **Jupyter Notebook** with Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🎯 Objectives

* Analyze the overall E-commerce sales data
* Understand product-wise performance
* Analyze category-wise sales and quantity
* Study product prices
* Analyze order quantities
* Identify city-wise sales performance
* Analyze monthly sales trends
* Create visualizations to understand the data easily

---

## 📂 Dataset

The project uses an E-commerce sales dataset containing approximately **1.1 million records**.

Important columns used in the analysis include:

* `Order_ID`
* `Product`
* `Category`
* `Quantity`
* `Price`
* `City`
* `Date`

A new `Sales` column was also created:

```python
Sales = Quantity × Price
```

A `Month` column was created from the `Date` column for monthly analysis.

---

## 🛠️ Technologies & Tools

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Data analysis           |
| Pandas           | Data manipulation       |
| NumPy            | Numerical operations    |
| Matplotlib       | Data visualization      |
| Seaborn          | Visualization           |
| Jupyter Notebook | Development environment |

---

## 🔍 Analysis Performed

### 1. Dataset Exploration

The dataset was explored using:

* First and last records
* Dataset shape
* Data types
* Column names
* Descriptive information
* Product and category counts

---

### 2. Product Analysis

Analyzed:

* Number of products
* Product frequency
* Average product price
* Total product price
* Product-wise sales

---

### 3. Category Analysis

Analyzed:

* Category distribution
* Category-wise sales
* Category-wise quantity sold

---

### 4. Price Analysis

Calculated:

* Maximum price
* Minimum price
* Average price
* Mode price

---

### 5. Quantity Analysis

Analyzed:

* Total quantity sold
* Average quantity
* Maximum quantity
* Minimum quantity

---

### 6. Date Analysis

Converted the date column into the appropriate datetime format and analyzed:

* Starting date
* Latest date
* Daily sales
* Monthly sales

A separate `Month` column was created for monthly analysis.

---

### 7. City-wise Sales Analysis

Sales were grouped by city to understand sales performance across different locations.

---

## 📊 Visualizations

The project contains several visualizations, including:

* 📊 Product-wise Sales
* 📊 Category-wise Sales
* 📊 City-wise Sales
* 📈 Monthly Sales Trend
* 📊 Category-wise Quantity Sold

These visualizations make it easier to identify patterns and compare sales performance.

---

## 📈 Sales Calculation

The project calculates total sales using:

```python
df['Sales'] = df['Quantity'] * df['Price']
```

Product, category, city, and monthly sales are then calculated using Pandas `groupby()` operations.

---

## 💡 Key Learning Outcomes

Through this project, I practiced:

* Working with a large dataset
* Data exploration using Pandas
* Data aggregation and grouping
* Date and time analysis
* Creating calculated columns
* Sales analysis
* Data visualization
* Extracting meaningful information from raw data

---

## 📁 Project Structure

```text
Ecommerce-Sales-Analysis/
│
├── E-commerce-Sales-Analysis.ipynb
├── ecommerce_sales_dataset.csv
└── README.md
```

---

## 🚀 How to Run the Project

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Open the project

Open the project folder in **Jupyter Notebook** or **VS Code**.

### Step 3: Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Open the notebook

```bash
jupyter notebook
```

Open:

```text
E-commerce-Sales-Analysis.ipynb
```

### Step 5: Update the dataset path

Change the CSV file path in the notebook according to your system:

```python
df = pd.read_csv("your_dataset_path.csv")
```

### Step 6: Run the notebook

Run the cells from top to bottom to reproduce the analysis.

---

## 👨‍💻 Author

**Abhishek Tyagi**

MCA Student | Aspiring Data Analyst

### Skills

`Python` `SQL` `Power BI` `Excel` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Data Analysis`

---

## ⭐ Project Purpose

This project was created as part of my **Data Analytics learning and portfolio development** to demonstrate practical skills in Python-based data analysis and visualization.
