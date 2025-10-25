# 🏍️ SQL Analysis: Motorcycle Part Wholesale Revenue

## 🎯 Overview

This repository contains a SQL query designed to analyze sales data for a motorcycle parts company. The goal is to understand net revenue generated from **Wholesale** clients, broken down by product line, month, and warehouse.

---

## 📊 Business Goal

The board of directors requested an analysis to better understand wholesale revenue patterns. Specifically, this query calculates the **net revenue** for each **product line**, aggregated monthly across the company's **three warehouses** (`North`, `Central`, `West`).

---

## 💾 Data Source

The analysis uses a single table named `sales` with the following key columns:

| Column         | Data Type | Description                                        |
| :------------- | :-------- | :------------------------------------------------- |
| `date`         | DATE      | Order date (June-August 2021)                      |
| `warehouse`    | VARCHAR   | Originating warehouse (North, Central, West)       |
| `client_type`  | VARCHAR   | Customer type (Retail or **Wholesale**)          |
| `product_line` | VARCHAR   | Type of product                                    |
| `total`        | FLOAT     | Total order price ($)                              |
| `payment_fee`  | FLOAT     | Fee incurred based on payment method ($)           |
