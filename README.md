# Zomato Data Analysis Using Python

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Zomato’s restaurant dataset to understand **customer preferences, restaurant trends, pricing behavior, and ordering patterns**. The analysis helps uncover actionable insights that can support **business decisions in the food & hospitality industry**.

The project uses **Python data analysis and visualization libraries** to answer real-world business questions.

---

## Objectives

The analysis aims to answer:

* Do more restaurants offer **online ordering** compared to offline services?
* Which **restaurant types** are most preferred by customers?
* What **price range** do couples prefer for dining?
* How do **ratings differ** between online and offline order modes?
* How does **order preference vary by restaurant type**?

---

## Dataset

* **Source:** Zomato restaurant dataset
* **Key Columns Used:**

  * `name` – Restaurant name
  * `rate` – Restaurant rating
  * `votes` – Number of customer votes
  * `online_order` – Online order availability
  * `listed_in(type)` – Restaurant category
  * `approx_cost(for two people)` – Approximate cost for two

---

## Tools & Technologies

* **Python**
* **Pandas** – Data manipulation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical plots

---

## Project Workflow

### 1. Data Loading

* Loaded dataset using `pandas.read_csv()`

### 2. Data Cleaning

* Converted `rate` column from string format (`4.1/5`) to numeric
* Checked for missing values (no nulls found)

### 3. Exploratory Data Analysis (EDA)

* Distribution of restaurant types
* Votes by restaurant category
* Online vs offline ordering trends
* Rating distribution analysis
* Cost preference for couples
* Rating comparison for online vs offline orders

### 4. Visualization

* Count plots
* Histograms
* Box plots
* Line plots
* Heatmaps

---

## Key Insights

* **Dining restaurants** dominate the dataset and receive the highest number of votes
* Majority of restaurants **do not support online ordering**
* Restaurants with **online ordering receive higher ratings**
* Most restaurants fall in the **3.5 – 4.0 rating range**
* **₹300 for two people** is the most preferred price point for couples
* **Dining restaurants** rely more on offline orders, while **cafes** receive more online orders

---

## Business Takeaways

* Online ordering is associated with **better customer satisfaction**
* Budget-friendly restaurants attract a larger audience
* Customer ordering behavior varies significantly by restaurant type
* Restaurants can optimize services based on order mode preferences

---

