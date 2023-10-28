# Data-Analysis
This repository includes two projects in data science and data analysis.

- [China Housing Data Analysis Project](#china-housing-data-analysis-project)
- ["sib" company Data Analysis Project](#sib-company-data-analysis-project)


# China Housing Data Analysis Project

This GitHub repository contains a comprehensive data analysis project focused on real estate data for homes in the city of Beijing. The project involves data preprocessing, exploratory data analysis (EDA), and visualization of the results through various charts and graphs. The primary goal is to extract meaningful insights and patterns from the dataset.

## Introduction<a name="introduction"></a>

The project is structured into four main sections:

### 1. Data Preprocessing

In this section, we read the raw data and clean it by removing unnecessary columns and handling missing values. Data is prepared for further analysis.

### 2. Feature Engineering

Data columns are transformed into appropriate formats, and outliers are identified and removed. New features are created using existing ones, which will be crucial for subsequent analysis.

### 3. Geospatial Visualization

Geographical information such as longitude and latitude is leveraged to plot the houses on a map. This visual representation provides a comprehensive overview of the distribution of properties in the city.

### 4. Time Series Analysis

The project concludes with a time series analysis of transaction data. Trends and patterns in transaction times are explored, providing valuable insights into the dynamics of the real estate market in Beijing.

## Data Sources

The dataset used for this project contains real estate information for homes in Beijing. It includes details about property characteristics, transaction data, and geographical information.

# sib company Data Analysis Project

## Introduction

"sib" is a leading non-oil product exporter to various countries worldwide. In this project we are tasked with analyzing the company's recent years' sales data and providing insights to address their questions.

The sales data is provided in an Excel file named `sales.xlsx` with the following columns:

- **InvoiceNumber**: A unique 6-digit number assigned to each invoice. If it starts with the letter 'C', it means the invoice is canceled.
- **ProductCode**: A unique 5-digit number assigned to each product type.
- **ProductName**: The name of the product.
- **Quantity**: The quantity of a specific product in an invoice.
- **InvoiceDate**: The date the invoice was created.
- **UnitPrice**: The price of a single unit of a product.
- **CustomerID**: A unique 5-digit number assigned to each customer.
- **Country**: The name of the customer's residence country.

This project is structured into five main stages:

1. **Data Preprocessing**: In this phase, you will familiarize yourself with the project's data and perform various data preparation and preprocessing steps.

2. **Exploratory Data Analysis (EDA)**: You will answer high-level questions and gain a visual understanding of the company's financial data.

3. **Market Study**: In the third step, you will analyze sales and distribution by country to determine in which countries sales are lower despite having a significant customer base.

4. **Customer Valuation**: Using the RFM (Recency, Frequency, Monetary) model, you will categorize customers into 7 segments based on their behavior and significance for marketing purposes.

5. **Customer Retention Analysis**: In the final step, you will determine what percentage of customers continue making purchases in the following months after their initial purchase.

## Data Sources

The dataset used for this project contains financial information from "sib" company's sales, including product details, invoices, customer information, and country data.
