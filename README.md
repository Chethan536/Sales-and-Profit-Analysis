
# Sales and Profit Analysis

A comprehensive exploratory data analysis (EDA) project on a “Superstore” dataset to uncover insights into sales performance, profitability, and operational efficiency. This analysis covers data cleaning, time‑series trends, category performance, negative profit handling, and the impact of shipping modes on delivery times.

---

## 📂 Project Structure

```text
├── Sample - Superstore.csv       # Raw dataset
├── Sales & Profit Analysis.ipynb # EDA, visualizations, insights
├── images/                           # Static plots (for README)
├── requirements.txt                  # Python package dependencies
└── README.md                         # Project overview and instructions
````

---

This project focuses on analyzing sales and profit trends over time, identifying top-performing categories and sub-categories, and deriving actionable insights for business growth. Using Python and libraries like pandas, matplotlib, and seaborn, we explore data-driven solutions to improve decision-making.


1. What is the trend of sales and profit over time?
2. Which regions contribute the most to sales and profit?
3. Which cities and states are the most profitable?
4. Which products are the most popular (highest quantity sold)?
5. How do discounts affect profit margins across different categories and sub-categories?
6. What is the customer segmentation based on sales and profit contribution?
7. What is the shipping mode's impact on delivery time and customer satisfaction?

---

## 📝 Dataset

* **Source**: “Sample – Superstore.csv”
* **Contents**:

  * Order information (Order ID, Order Date, Ship Date, Ship Mode)
  * Customer details (Customer ID, Segment, Region, City, State)
  * Product details (Category, Sub‑Category, Product Name)
  * Performance metrics (Sales, Quantity, Discount, Profit)

---

## 🔍 Key Features & Questions

1. **Data Cleaning & Preparation**

   * Handled missing values
   * Converted date strings to datetime
   * Standardized categorical labels

2. **Sales & Profit Trends**

   * Time‑series analysis of monthly/yearly sales and profit
   * Identification of peak and slow periods

3. **Category & Sub‑Category Performance**

   * Top‑performing categories by total sales and profit
   * Sub‑category breakdown within each main category

4. **Negative Profit Handling**

   * Detection of negative‑profit transactions
   * Imputation of negative profit values with the overall mean

5. **Shipping Mode Analysis**

   * Impact of different shipping modes on delivery lead time
   * Correlation between quicker shipping and customer satisfaction indicators

6. **Interactive Visualizations**

   * Boxplots for profit distribution by segment
   * Bar charts for top cities, states, products
   * Pie charts and stacked bars for category composition
   * Line charts for trend analysis

---

## 🛠️ Tools & Libraries

* **Language**: Python 3.x
* **Data Manipulation**: pandas, numpy
* **Visualization**: matplotlib, seaborn

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/Chethan536/sales-profit-analysis.git
   cd sales-profit-analysis
   ```

2. **Create & activate a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate   # macOS/Linux
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the notebook**

   ```bash
   jupyter notebook notebooks/Sales\ &\ Profit\ Analysis.ipynb
   ```

---

## 📊 Key Insights & Recommendations

* **Top Regions & Segments**

  * The **West** and **East** regions lead in both sales and profit.
  * The **Corporate** segment shows the highest profit margins; **Consumer** lags behind.

* **Category Performance**

  * **Technology** and **Office Supplies** drive the bulk of sales, but **Furniture** shows higher average profit margin.

* **Operational Improvements**

  * Replacing slower shipping modes (e.g., Standard Class) with faster ones in high‐value orders can boost customer satisfaction without a proportional cost increase.

* **Actionable Recommendations**

  1. **Optimize marketing** for underperforming segments (Consumer).
  2. **Promote high‐margin categories** with targeted discounts on Furniture.
  3. **Audit shipping contracts** to balance delivery speed and cost for key customers.

---

## 🤝 Contributing

Feel free to submit issues or pull requests for enhancements—whether it’s deeper statistical modeling, dashboard integration, or new visualizations!

---

