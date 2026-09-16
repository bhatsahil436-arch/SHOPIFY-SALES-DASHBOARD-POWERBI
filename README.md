# Shopify Analysis Dashboard

Interactive Power BI dashboard delivering a full analysis of Shopify store performance — sales, customers, and products.

## Overview

This Power BI dashboard analyzes Shopify order-level sales data across the US, covering revenue trends, customer retention, payment gateways, regional performance, and product-level breakdowns. It's built as a two-page report: a high-level **Analysis** overview and a **Details** tab with granular order-level data.

## Key Metrics (Analysis Page)

**Transaction Performance**
- Net Sales: **$41,80,874**
- Total Quantity Sold: **8K units**
- Net Avg Order Value: **$562.6**

**Customer Purchase Behaviour**
- Total Customers: **4,431**
- Single Order Customers: **2,392**
- Repeat Customers: **2,039**

**Retention & Value KPIs**
- Customer Lifetime Value: **$943.6**
- Repeat Rate: **46%**
- Purchase Frequency: **1.68**

## Features

- **Regional Overview** — US map and city-level breakdown of net sales by province/city (Washington, Houston, New York City, El Paso, Dallas, and more)
- **Net Sales Trend Over Time** — Line and bar combo chart tracking sales momentum across periods
- **Net Sales by Gateway Payment Method** — Donut chart breakdown: Shopify Payments (58%), PayPal (18%), Gift Card (16%), Amazon Payments (6%), Manual
- **Net Sales by Product Type** — Bar chart ranking products (Running Shoes leads at $1.5M, followed by Tennis Shoes, Walking Shoes, Cycling Shoes, and more)
- **Interactive Filter Panel** — Slice by Measures, Gateway, and Province
- **Details Tab** — Full order-level table with Order Number, Customer Name, Province, City, Zip Code, Product Type, Gateway, Net Sales, Total Tax, and Total Price (USD)

## Tech Stack

- **Power BI Desktop** — Dashboard design and data modeling
- **DAX** — Custom measures (Net Sales, LTV, Repeat Rate, Purchase Frequency, etc.)
- **Power Query** — Data cleaning and transformation

## Data Source

Shopify order-level sales dataset including customer, location, product, gateway, and tax details.

## Dashboard Preview

**Analysis Overview**
![Dashboard Overview](screenshots/dashboard-overview.png)

**Order Details**
![Dashboard Details](screenshots/dashboard-details.png)
