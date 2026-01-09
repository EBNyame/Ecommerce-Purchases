# Ecommerce Purchases Project

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-brightgreen)
![Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

This repository contains a **Jupyter Notebook** that performs a detailed **data analysis on ecommerce purchase behaviour**. The goal is to explore real-world transaction data, uncover patterns in customer purchases, and extract insights using **Python data analysis libraries**.

---

## Project Overview

The **Ecommerce Purchases** notebook analyzes an ecommerce transaction dataset to:
- Understand purchasing behaviour and trends.
- Explore customer demographics and purchase patterns.
- Identify popular product categories and typical purchases prices.
- Demonstrate intermediate-level Python data analysis using **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.
  
This project is suitable for learners practicing **data cleaning**, **exploratory data analysis (EDA)**, and **insight generation with Python** in a Jupyter environmnet.

---

## Repository Contents

```text
Ecommerce-Purchases/
|
├── data/
|    └── Ecommerce Purchases.csv
|
├── Ecommerce_Purchases.ipynb
|
├── README.md
│
└── requirements.txt
```

## What’s Inside the Notebook

The notebook includes:
#### 1. Data Loading & Overview
- Read the ecommerce transactions dataset.
- Initial inspection with head(), info(), and describe().

#### 2. Data Cleaning
- Handle missing values and inconsistent formats.
- Convert relevant data types for analysis.

#### Exploratory Data Analysis (EDA)
- Summary statistics on purchase prices.
- Insights around purchase frequency, time of day, and customer segments.
- Visualization of spending trends and distribution of transaction values.

#### Visualizations
- Charts and plots using Matplotlib and Seaborn to reveal trends and relationships.

Each step is clearly annotated with Markdown explanations and code comments to make the workflow easy to follow and educational.

--- 

## Technologies & Tools Used
This project is built using the following technologies:

| Technology | Purpose
|----------|----------
| Python  | Main programming language for analytics 
| Pandas | Data manipulation & analysis
| NumPy | Numerical operations
| Matplotlib & Seaborn | Data visualization
| Jupyter Notebook  | Interactive environment for the analysis

## How to Run This Project Locally
To run this notebook on your local machine:
#### 1. Clone the repository:
```bash
git clone https://github.com/EBNyame/Ecommerce-Purchases.git
```

#### 2. Navigate into the project directory:
```bash
cd Ecommerce-Purchases
```

#### 3. Install required packages:
If you’re using pip:
```bash
cd Ecommerce-Purchases
```
Or if you prefer conda:
```bash
conda install pandas numpy matplotlib seaborn jupyter
```

#### 4. Open the notebook:
```bash
jupyter notebook Ecommerce_Purchases.ipynb
```

#### 5. Run all cells and explore the analysis interactively.

---

## Dataset
This project uses an ecommerce purchase dataset containing transaction records. It includes fields such as:
- Purchase price
- Customer job role
- Payment and credit card data
- Browser and IP information
- Purchase timestamp and more

**Download:** *https://www.kaggle.com/datasets/utkarsharya/ecommerce-purchases*

---

## Key Insights 
- 405 consumers have Mastercard as their credit card provider and made a purchase above $50
- 984 consumers are engineers
- The most common purchase price falls within the $0–$50 range.
- Evening purchases were more frequent than day purchases.
- Total of 988 credit cards expired in 2020
-Top 5 most popular email providers are;
  - hotmail.com
  - yahoo.com
  - gmail.com
  - smith.com
  - williams.com
 
---

## Future Enhancements
Here are ideas for improving this project:
- Add predictive modeling (e.g., spend prediction).
- Extend analysis to include customer segmentation (RFM analysis).
- Create an interactive dashboard (e.g., with Streamlit or Dash).
- Publish insights to a blog or portfolio site.

---  

## About You
Created by **Exodus Blessed Nyame**
GitHub: https://github.com/EBNyame

Portfolio / Contact: Add Your Website or Email

📜 License

This repository is open for personal and educational use. Please cite properly if reused in academic or professional settings.
