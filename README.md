# E-Commerce Sales Analytics, Customer Segmentation & Revenue Prediction

## Project Overview

This project analyzes e-commerce transaction data to understand sales performance, identify customer segments, and predict daily revenue.

Python is used for data cleaning, exploratory data analysis, customer segmentation, and revenue prediction. Power BI is used to create visualizations and present the results in an interactive dashboard.

## Objectives

* Analyze sales and revenue trends.
* Identify top-performing products and countries.
* Segment customers based on purchasing behavior.
* Predict daily revenue using Linear Regression.
* Visualize insights using Power BI.

## Dataset

**Dataset:** UCI Online Retail Dataset

The dataset contains online retail transaction records, including invoice details, product information, quantities, prices, customer IDs, and countries.

Place the downloaded dataset in the `data` folder and name it:

`online_retail.csv`

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Power BI


## Project Workflow

### 1. Data Cleaning

* Remove duplicate records.
* Handle missing required values.
* Convert invoice dates into datetime format.
* Exclude cancelled transactions.
* Remove invalid quantities and unit prices.
* Calculate revenue using quantity multiplied by unit price.

### 2. Exploratory Data Analysis

Analyze and visualize:

* Monthly revenue trends.
* Top 10 products by revenue.
* Top 10 countries by revenue.

### 3. Customer Segmentation

Use Recency, Frequency, and Monetary (RFM) analysis to understand customer purchasing behavior.

Apply K-Means clustering to group customers based on their RFM features.

### 4. Revenue Prediction

* Aggregate sales by date.
* Split the data chronologically into training and testing sets.
* Train a Linear Regression baseline model.
* Compare actual and predicted daily revenue.

### 5. Power BI Dashboard

Create visualizations for:

* Customer segmentation.
* Top products by revenue.
* Top countries by revenue.
* Monthly revenue trends.
* Actual versus predicted daily revenue.

## Installation and Setup

### Step 1: Clone the Repository

```bash
git clone 
```

Replace the placeholders with your GitHub username and repository name.

### Step 2: Navigate to the Project Folder

```bash
cd Ecommerce_Sales
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` folder and run the cells in order.



## Results

The project generates visual outputs showing sales trends, product and country revenue contributions, customer segments, and actual versus predicted daily revenue.

The prediction model is a baseline. Its performance should be evaluated using metrics calculated from the executed notebook.

## Conclusion

This project demonstrates how Python and Power BI can be used together to analyze e-commerce data, understand customer purchasing behavior, and explore daily revenue prediction.

The analysis provides useful insights into sales patterns and customer groups while demonstrating a basic machine learning workflow.

## Author

**Name:** ANAGHA A

**Program:** IBM SkillsBuild Internship

**Project:** E-Commerce Sales Analytics, Customer Segmentation & Revenue Prediction
