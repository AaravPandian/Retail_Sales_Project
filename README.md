# Retail Sales Analysis with Python

This project explores a fictional retailer’s sales data to understand product performance, regional sales patterns and monthly trends. It demonstrates a complete beginner data-analysis workflow, from cleaning raw records to explaining findings.

## Objectives

- Calculate total completed sales and average order value.
- Identify products generating the most sales.
- Compare units sold across categories.
- Analyse sales by region and month.
- Identify the highest-performing category in each region.

## Tools

Python, pandas, Matplotlib and Jupyter Notebook.

## Data Preparation

Removed exact duplicate records, standardised category labels, labelled missing region and payment information as `Unknown`, and converted order dates into datetime values.

Sales analysis includes only completed product lines. Repeated order IDs are retained because an order can contain multiple products.

## Analysis

The notebook answers ten questions using filtering, calculated columns, grouping, aggregation, pivot tables and visualisations. It also includes checks confirming that product, regional and monthly totals reconcile.

## Key Results

- Total completed sales: **₹61,88,688**
- Average completed value per order with at least one completed line: **₹4,068.83**

## How to Run

1. Download the notebook and CSV.
2. Keep both files in the same folder.
3. Open the notebook in Jupyter and run the cells from top to bottom.

For Google Colab, open the notebook and upload the CSV through the Files panel before running.

## Limitations

This dataset is synthetic and intended for learning. Its findings do not describe a real business. The dataset does not include costs, so sales values should not be interpreted as profit.
