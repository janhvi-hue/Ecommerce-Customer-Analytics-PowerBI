# E-Commerce Customer Analytics Dashboard (Power BI)

## Overview
An end-to-end Power BI dashboard analyzing customer behavior and sales performance using the Olist e-commerce dataset. Built a complete star-schema data model from raw transactional data and segmented customers using RFM (Recency, Frequency, Monetary) analysis.

## Key Features
- **Star Schema Data Model** — Designed with 7 active relationships connecting fact and dimension tables for efficient querying
- **8 Custom DAX Measures** — Built in a dedicated `_Measures` table covering revenue, order metrics, and customer KPIs
- **RFM Segmentation** — Classified customers into 6 segments (Champions, Loyal Customers, At Risk, etc.) based on purchase recency, frequency, and monetary value
- **4-Page Interactive Dashboard** — Dark-themed report covering sales overview, customer segmentation, geographic analysis, and product performance

## Tools Used
- Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX (measures and calculated columns)

## Process
1. **Data Cleaning** — Used Power Query to clean and transform raw Olist transactional data
2. **Data Modeling** — Built a star schema with fact tables (orders, order items) and dimension tables (customers, products, sellers, dates) to optimize performance and enable clean cross-filtering
3. **DAX Measures** — Created 8 measures for revenue, average order value, customer counts, and RFM scoring
4. **RFM Segmentation** — Scored customers on Recency, Frequency, and Monetary value, then bucketed them into actionable segments to guide retention strategy
5. **Dashboard Design** — Built a 4-page report with a consistent dark theme, slicers for interactivity, and visuals tailored to each business question

## Dashboard Pages
1. Sales Overview
2. Customer Segmentation (RFM)
3. Geographic Analysis
4. Product Performance

## Screenshots
*(Add exported PNG screenshots of each dashboard page here)*

## Dataset
[Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
# Ecommerce-Customer-Analytics-PowerBI
Power BI dashboard analyzing e-commerce customer behavior using star-schema modeling, DAX measures, and RFM segmentation on the Olist dataset.
