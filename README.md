# Sales Data Analysis

## 1. Project Overview

This project focuses on analyzing retail sales data using Python to identify business trends, evaluate profitability, and generate actionable insights.

The analysis is based on the Sample Superstore dataset and aims to support data-driven business decisions through data cleaning, exploratory data analysis (EDA), and data visualization.

## 2. Project Objectives

- Analyze overall sales and profitability.
- Identify the best-performing product categories and sub-categories.
- Evaluate sales and profit performance across regions.
- Understand the impact of discounts on profitability.
- Identify business opportunities and areas for improvement.

## 3. Dataset Description

The project uses the `SampleSuperstore.csv` dataset.

The original dataset contains:
- 9,994 rows.
- 13 columns.

Main features include:

- Order information: Ship Mode, Segment.
- Geographic information: Country, City, State, Postal Code, Region.
- Product information: Category, Sub-Category.
- Sales information: Sales, Quantity, Discount, Profit.

## 4. Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## 5. Project Structure

```text
Sales-Data-Analysis/
│
├── data/
│   └── SampleSuperstore.csv
│
├── notebooks/
│   └── 01_Data_Exploration.ipynb
│
├── images/
│
├── reports/
│
├── README.md
└── requirements.txt
```

## 6. Data Cleaning & Preparation

The following operations were performed:

- Inspected the dataset structure and data types.
- Checked for missing values.
- Identified and removed 17 duplicate rows.
- Converted Postal Code from integer to string to preserve its categorical nature and leading zeros.
- Verified data consistency after cleaning.

Final dataset:
- 9,977 rows.
- 13 columns.
- No missing values.
- No duplicate records.

## 7. Exploratory Data Analysis

The exploratory analysis focused on:

- Overall sales and profit performance.
- Sales and profit by product category.
- Sub-category performance.
- Regional business performance.
- Discount and profitability analysis.

## 8. Key Business Insights

### Overall Performance

- Total Sales: $2,296,195.59
- Total Profit: $286,241.42
- Total Quantity Sold: 37,820
- Average Sales: $230.15
- Average Profit: $28.69
- Average Discount: 15.63%
- Overall Profit Margin: 12.47%

### Category Performance

| Category | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| Technology | $836,154.03 | $145,454.95 | 17.40% |
| Furniture | $741,306.31 | $18,421.81 | 2.49% |
| Office Supplies | $718,735.24 | $122,364.66 | 17.02% |

Technology generates the highest sales and profit.

Furniture has a significantly lower profit margin compared to the other categories, suggesting an opportunity to review pricing and discount strategies.

## 9. Visualizations

The project uses Matplotlib and Seaborn to explore business performance through visual representations.

Visualizations will be added to the `images/` directory.

## 10. How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project directory

```bash
cd Sales-Data-Analysis
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the environment

Windows:

```bash
.venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook located in the `notebooks/` directory.

## 11. Conclusion

This project demonstrates the use of Python for retail sales analysis, from data cleaning and preparation to exploratory analysis and business insights.

The findings highlight the importance of analyzing product profitability, understanding regional performance, and evaluating discount strategies to support better business decisions.

**Project Status:** In Progress – Documentation and GitHub publication.