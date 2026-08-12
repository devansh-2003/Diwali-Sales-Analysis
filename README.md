# Diwali Sales Data Analysis

An exploratory data analysis project using Python to analyze Diwali sales data and identify customer purchasing patterns, high-performing states, occupations, product categories, and other sales trends.

## Project Overview

This project analyzes a Diwali sales dataset to understand customer behavior and sales performance.

The analysis focuses on questions such as:

* Which gender makes more purchases?
* Which age group contributes the most to sales?
* Which states generate the highest number of orders and sales?
* How does marital status relate to purchasing behavior?
* Which occupations have the highest purchasing power?
* Which product categories are most popular?
* Which products receive the highest number of orders?

## Repository Contents

```text
.
├── Diwali_Sales_Analysis.ipynb
├── Diwali Sales Data.csv
└── README.md
```

### Files

**`Diwali_Sales_Analysis.ipynb`**

Jupyter Notebook containing the data cleaning, exploratory data analysis, visualizations, and findings.

**`Diwali Sales Data.csv`**

The dataset used for the analysis.

**`README.md`**

Documentation for the project.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Data Preparation

The notebook performs the following preprocessing steps:

1. Loads the CSV dataset using Pandas.
2. Checks the shape and structure of the dataset.
3. Removes unrelated or blank columns.
4. Checks for missing values.
5. Removes rows containing null values.
6. Converts the `Amount` column to an integer data type.
7. Performs descriptive statistical analysis.

## Exploratory Data Analysis

The analysis explores sales across several dimensions.

### Gender

The analysis compares the number of buyers and total purchasing amount by gender.

### Age Group

The project analyzes customer distribution and sales across different age groups.

The 26–35 age group represents one of the major customer segments in the dataset.

### State

The analysis identifies the states with the highest number of orders and total sales.

Uttar Pradesh, Maharashtra, and Karnataka are among the leading states in terms of orders and total sales.

### Marital Status

The project compares purchasing behavior across marital status and gender.

### Occupation

Customer purchasing behavior is analyzed across different occupations.

IT, Healthcare, and Aviation are among the prominent occupation groups in the analysis.

### Product Category

The analysis examines the number of products sold and total sales across product categories.

Food, Clothing, and Electronics are among the leading product categories.

### Product ID

The notebook also identifies the top 10 products based on the total number of orders.

## Visualizations

The project uses Matplotlib and Seaborn to create visualizations including:

* Gender-wise buyer counts
* Gender-wise total sales
* Age-group distribution
* Age-group-wise sales
* Top states by orders
* Top states by sales
* Marital-status distribution
* Marital-status and gender-wise sales
* Occupation-wise buyer distribution
* Occupation-wise sales
* Product-category distribution
* Product-category-wise sales
* Top 10 products by number of orders

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <your-repository-name>
```

### 2. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the Notebook

Open:

```text
Diwali_Sales_Analysis.ipynb
```

Make sure `Diwali Sales Data.csv` is located in the same directory as the notebook.

### 5. Run the Notebook

Run the notebook cells from top to bottom to reproduce the data cleaning, analysis, visualizations, and findings.

## Key Insights

* Female customers represent a larger share of buyers in the analyzed dataset.
* The 26–35 age group is a major customer segment.
* Uttar Pradesh, Maharashtra, and Karnataka are among the top-performing states.
* Marital status and gender are analyzed to understand purchasing behavior.
* IT, Healthcare, and Aviation are among the prominent occupation groups.
* Food, Clothing, and Electronics are among the leading product categories.
* The analysis identifies the top 10 products based on order volume.

## Project Objective

The objective of this project is to use data analysis and visualization to understand customer purchasing behavior during Diwali sales.

The insights from the analysis can help with:

* Customer targeting
* Product promotion
* Inventory planning
* Marketing campaigns
* Regional sales strategies
