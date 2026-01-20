# Week-6-Data-Visualization-with-Seaborn

## Interactive Sales Dashboard
### Project Overview

The Interactive Sales Dashboard is an end-to-end data analytics and visualization project designed to analyze sales performance using both statistical and interactive visualizations.

The dashboard helps stakeholders:

Track overall sales performance

Understand product, region, and customer behavior

Identify patterns, distributions, and correlations

Explore data interactively for deeper insights

The project combines Seaborn, Matplotlib, and Plotly to deliver a professional, cohesive analytics solution.

### 🎯 Objectives

Build 5+ visualization types using Seaborn and Plotly

Design a cohesive dashboard layout

Provide interactive exploration capabilities

Create executive-ready visuals for reporting

Follow industry-standard GitHub structure

Deliver complete documentation and validation

### 🛠️ Tech Stack

Category	Tools

Programming	Python

Data Analysis	Pandas, NumPy

Statistical Visualization	Seaborn, Matplotlib

Interactive Visualization	Plotly

Dashboard	Jupyter Notebook

Reporting	PNG, HTML, PDF

Version Control	GitHub

### 📁 Project Structure
interactive-sales-dashboard/
│
├── dashboard.ipynb               # Main interactive notebook
├── dashboard.py                  # Script version of dashboard
├── README.md                     # Project documentation
├── requirements.txt              # Python dependencies
│
├── data/
│   └── sales_data.csv             # Input dataset
│
├── visualizations/
│   ├── boxplot_price_category.png
│   ├── violinplot_sales_region.png
│   ├── correlation_heatmap.png
│   ├── dashboard_overview.png
│   └── sales_trend_plotly.html
│
├── reports/
│   └── Sales_Dashboard_Report.pdf
│
└── dashboard_demo.gif             # Demo of interactive dashboard

### ⚙️ Setup Instructions
1️⃣ Clone the Repository

2️⃣ Create Virtual Environment

3️⃣ Install Dependencies

4️⃣ Run the Dashboard

### 📊 Dashboard Components & Interpretation

1️⃣ KPI Summary

Total Sales: Overall revenue generated

Total Orders: Number of transactions

Average Order Value: Revenue per order

📌 Provides quick executive-level snapshot

2️⃣ Box Plot – Total Sales by Product

Purpose:

Identify sales spread and outliers

Compare product-level performance

3️⃣ Histogram – Distribution of Total Sales

Purpose:

Understand sales frequency and skewness

Identify high-value transactions

4️⃣ Bar Chart – Total Sales by Region

Purpose:

Compare regional performance

Support regional sales strategy decisions

5️⃣ Correlation Heatmap

Purpose:

Analyze relationships between:

Total Sales

Quantity

Price


6️⃣ Interactive Plotly Visualization

Features:

Hover tooltips

Zoom & pan

Time-based trend analysis

Enables deep exploratory analysis for stakeholders

### 🎨 Design & Visualization Principles

Consistent color palette

Clear titles and axis labels

Grid-based layout for readability

Separation of statistical vs interactive visuals

High-resolution exports for reporting

### 🧪 Testing & Validation

Data Validation

assert df.isnull().sum().sum() == 0

assert df['Total_Sales'].min() >= 0

Visualization Validation

Axis labels verified

Titles consistent

Outliers visually inspected

Correlations cross-checked numerically

### 📄 Reporting & Deliverables

✔ High-resolution dashboard images

✔ Interactive HTML visualization

✔ PDF report with insights

✔ Demo GIF showcasing interaction
