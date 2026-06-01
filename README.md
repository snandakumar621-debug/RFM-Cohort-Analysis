# Customer Segmentation Using RFM and Cohort Analysis

## Overview

This project implements RFM (Recency, Frequency, Monetary) Analysis and Cohort Analysis to segment customers and analyze customer retention patterns.

The solution helps businesses identify high-value customers, monitor purchasing behavior, detect churn risks, and improve retention strategies.

---

## Features

### RFM Analysis

* Calculate Recency, Frequency, and Monetary metrics.
* Generate RFM scores.
* Segment customers into:

  * Champions
  * Loyal Customers
  * Potential Loyalists
  * At Risk Customers
  * Others

### Cohort Analysis

* Group customers by acquisition month.
* Calculate retention rates.
* Generate cohort retention matrices.
* Visualize customer retention trends.

### Exploratory Data Analysis

* Revenue trend analysis
* Purchase behavior analysis
* Customer distribution analysis
* Top customer identification

---


## Installation

Clone the repository:

```bash
git clone <repository-url>
cd RFM_Cohort_Analysis
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Dataset Requirements

The dataset should contain:

| Column      | Description         |
| ----------- | ------------------- |
| CustomerID  | Customer identifier |
| InvoiceNo   | Transaction ID      |
| InvoiceDate | Transaction date    |
| Quantity    | Units purchased     |
| UnitPrice   | Unit price          |

Sales value is calculated as:

```python
Sales = Quantity * UnitPrice
```

---

## Running the Project

Execute the notebook:

```bash
jupyter notebook
```

Run:

```text
RFM_Cohort_Analysis.ipynb
```

---

## Output Files

The project generates:

* rfm_segments.csv
* cohort_retention.csv
* monthly_sales_trend.png
* customer_segments.png
* cohort_retention_heatmap.png

---

## Business Value

This project enables organizations to:

* Identify high-value customers.
* Improve customer retention.
* Reduce churn.
* Personalize marketing campaigns.
* Increase customer lifetime value (CLV).
* Optimize customer acquisition and engagement strategies.

---

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook


