# 📊 Sales Discount & Profitability Analysis

## 📌 Business Analytics Project — Excel

This project analyzes the impact of commercial discounts on company profitability using transactional sales data.

The main objective is to identify how discount policies affect gross profit, determine which transactions and business segments generate losses, and simulate potential profitability improvements under different discount scenarios.

---

## 🎯 Business Problem

The company generates a significant volume of sales but presents negative overall gross profitability.

The analysis focuses on answering the following questions:

- How much profit is the company losing?
- What percentage of transactions generate negative gross profit?
- How are discounts affecting profitability?
- Which salespeople, regions, categories, and channels generate the largest losses?
- What discount level can each transaction support before becoming unprofitable?
- What would happen to profitability if the company implemented discount limits?

---

## 🛠️ Tools & Technologies

- **Microsoft Excel**
- Pivot Tables
- Excel formulas
- Data analysis
- KPI development
- Scenario analysis
- Business intelligence concepts
- Data visualization

---

## 📂 Dataset

The dataset contains transactional sales information, including variables such as:

- Transaction ID
- Salesperson
- Region
- Category
- Sales Channel
- Product
- Quantity
- Unit Price
- Cost
- Discount
- Net Sales
- Gross Profit
- Gross Margin

The dataset was analyzed at the transaction level to identify the relationship between discounts and profitability.

---

# 📈 Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Net Sales | ARS 59.7M |
| Gross Profit | ARS -4.16M |
| Gross Margin | -7.0% |
| Loss-Making Transactions | 60.4% |
| Gross Loss | ARS 5.95M |
| Average Discount | 15.2% |
| Average Discount — Loss-Making Transactions | 18.8% |
| Average Break-Even Discount | 7.4% |

---

# 🔎 Key Findings

### 1. Negative Overall Profitability

Despite generating approximately **ARS 59.7M in net sales**, the company generates an overall gross loss of approximately **ARS 4.16M**.

This indicates that sales volume alone is not translating into positive profitability.

---

### 2. High Percentage of Loss-Making Transactions

Approximately **60.4% of analyzed transactions generate negative gross profit**.

This suggests that profitability problems are not isolated to a small number of exceptional transactions.

---

### 3. Discount Levels and Profitability

Loss-making transactions have an average discount of approximately **18.8%**, while their average break-even discount is approximately **7.4%**.

This indicates that many transactions are receiving discounts above the level supported by their available gross margin.

---

### 4. Loss Concentration

The analysis identifies the salespeople, regions, categories, channels and individual transactions that contribute most significantly to the company's negative profitability.

This allows management to focus corrective actions on the areas with the greatest financial impact.

---

# 📊 Dashboard

The Excel dashboard provides an interactive overview of:

- Sales performance
- Gross profitability
- Loss-making transactions
- Discount levels
- Break-even discount
- Profitability by salesperson
- Profitability by region
- Profitability by category
- Profitability by sales channel
- Top loss-making transactions

---

# 💡 Discount Scenario Analysis

One of the main components of this project is a scenario simulator designed to estimate how profitability could change under different discount limits.

For example, a scenario limiting discounts to **5%** estimates:

- Potential recovered profit: approximately **ARS 7.43M**
- Projected gross profit: approximately **ARS 3.27M**

### Important assumption

The scenario assumes that sales volume and quantities remain constant after changing the discount policy.

Therefore, the simulation should be interpreted as a **financial sensitivity analysis**, not as a guaranteed forecast.

In a real-world implementation, changes in customer demand and sales volume should also be incorporated into the model.

---

# 🧮 Methodology

### Net Sales

```text
Net Sales = Quantity × Unit Price × (1 - Discount)
