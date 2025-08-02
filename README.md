📊 Superstore Sales Analysis - README

Overview

This project focuses on analyzing Superstore sales data using Python (Pandas, Matplotlib, Seaborn). The goal is to derive meaningful business insights by performing data cleaning, feature engineering, and visualizations.

Dataset

File: train.csv

Contents: Orders information including Order ID, Customer ID, Sales, Category, Sub-Category, Order Date, Ship Date, State, etc.

Key Steps

Data Loading & Cleaning

Load CSV file into Pandas DataFrame.

Parse date columns (Order Date, Ship Date).

Handle any missing or inconsistent data.

Feature Engineering

Calculate Processing Time (days between Order Date and Ship Date).

Extract Order Month for time-series analysis.

Descriptive Statistics

Total Sales

Average & Median Sales per Order

Unique Customers, States, Categories

Processing Time Distribution

Aggregations

Sales by Customer

Sales by State

Sales by Category & Sub-Category

Visualizations

Top Customers (Bar Plot)

Sales Distribution by State (HistPlot)

Monthly Sales Trend (Line Plot)

Sub-Category Order Counts (Bar Plot)

Insights Summary

Sales are driven mostly by small, repetitive orders.

Few high-value orders significantly impact overall revenue.

Average processing time is ~4 days, with same-day shipping observed.

Sales are distributed across 49 states.

Product assortment covers 3 main categories and 17 sub-categories.
