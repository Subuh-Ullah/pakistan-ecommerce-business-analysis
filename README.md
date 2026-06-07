# 🇵🇰 Pakistan E-Commerce Business Analysis

**A beginner-friendly, business-focused analysis of Pakistan's largest e-commerce dataset using pandas.**

---

## 📌 Project Overview

This project analyzes real order data from a major Pakistani e-commerce platform. Unlike typical data science projects that focus on complex models, this analysis answers **real business questions**:

- Which categories, products, and payment methods drive the most sales?
- When do sales peak — which months and weekdays?
- Do discounts actually help, or do they increase cancellations?
- Who are the most valuable customers?
- What should the business do next?

The notebook is written with **clear explanations** after every code cell, making it accessible for beginners and useful for business stakeholders.

> ⚠️ **Important Note**: This dataset contains sales values but **no product cost, delivery cost, or marketing cost**. Therefore, this analysis focuses on **sales planning, cancellation rates, discounts, customer behavior, and operational flags** — not true profit. All limitations are clearly stated in the notebook.

---

## 🧠 What This Analysis Covers

### Data Cleaning & Preparation
- Removed empty rows and blank columns
- Converted dates, prices, and quantities to proper numeric types
- Created helper columns: `net_sales_for_planning`, `processing_days`, `discount_rate`, `is_cancelled`, `slow_order`
- Handled missing values transparently (filled with "missing" where appropriate)

### 55+ Business Analysis Tables

| Analysis Area | Questions Answered |
|---------------|---------------------|
| **Sales Trends** | Which months and weekdays bring highest sales? |
| **Categories** | Which category has high sales but also high cancellations? |
| **Products (SKUs)** | Top products by quantity vs. sales vs. cancellation risk |
| **Payment Methods** | Which methods have highest cancellations or slow processing? |
| **Discounts** | Do heavy discounts lead to more cancellations? |
| **Customers** | Repeat customer rate, top customers, joining trends |
| **Operational** | How many days to process orders? Which categories are slow? |
| **Price Analysis** | Sales by price bands — cheap vs. expensive items |
| **Commission Codes** | Sales performance by campaign or partner codes |

### Final Deliverables
- **8-step Business Action Plan**
- **12-point Decision Checklist**
- **Data Gap Analysis** (what should be added next)

---

## 📁 Dataset

| Attribute | Details |
|-----------|---------|
| **Source** | Pakistan Largest Ecommerce Dataset (Kaggle) |
| **File** | `Pakistan Largest Ecommerce Dataset.csv` |
| **Rows** | ~100,000+ order item records |
| **Time Period** | Multiple years (check notebook output) |

### What's NOT in the Dataset
- ❌ City / Province (no geography analysis)
- ❌ Product cost (no true profit)
- ❌ Delivery cost & time
- ❌ Marketing cost
- ❌ Return reasons

---

## 🛠 Requirements

This notebook uses **only pandas** — no machine learning, no complex libraries.

```bash
pip install pandas
