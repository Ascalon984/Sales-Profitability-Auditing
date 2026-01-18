<p align="center">
  <img src="https://github.com/user-attachments/assets/10b9f4ed-8295-4419-890c-dff4cdac3f78" width="700">
</p>

<h1 align="center">Global Sales Performance & Financial Integrity Pipeline</h1>

<p align="center">
  Transforming Global Transaction Records into Strategic Business Intelligence & Audit-Ready Insights.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Viz-4C78A8?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status">
</p>

**Overview**

This project is an automated data analysis pipeline for a global sales dataset of **100,000 records** sourced from **[Kaggle](https://www.kaggle.com/datasets/ishansurana1234/1000000-sales-records-excel-bi-analytics)**. Workflows include rigorous data cleansing (null and duplicate handling), feature transformation (profit & market segmentation), to financial integrity audits using **Benford's Law**. This analysis is designed to support data-based strategic decision making and early detection of transaction anomalies.

**Business Impact:**
- **Data Integrity:** Validate the authenticity of financial reports through statistical testing of the first digit.
- **Margin Optimization:** Identify products with high production costs versus market prices.
- **Strategic Segmentation:** Classifying products into *Star*, *Premium*, and *Mass Market* categories using profit and volume criteria.

---

## Module Navigation

Access complete technical documentation and source code through the following steps:

| 01. Data Cleaning & Optimization | 02. Feature Engineering | 03. Insight & Audit Visualization |
| :--- | :--- | :--- |
| Null handling, automatic data type conversion, & duplication cleanup. | Creating `Profit Class` & `Market Segment` labels using NumPy logic. | Financial correlation heatmap, regional bar chart, & Benford distribution test. |

---

📊 **Highlights of Analysis Results**

### 1. Financial Correlation & Operational Health
There is a very strong correlation (**0.88**) between *Total Revenue* and *Total Profit*. This shows a stable cost structure, where a linear increase in sales is followed by a proportional increase in profits.
<table border="0">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/929da93b-5ce2-471d-a6bf-4add069f6c8b" width="600" />
      <br><em>Financial Variable Correlation Matrix</em>
    </td>
  </tr>
</table>

### 2. Regional Demand & Market Leader
**Sub-Saharan Africa** leads the market demand with the highest volume (**26,019** order IDs), followed by Europe. Areas that are above the average line (14,286) are the main priority for stock allocation.
<table border="0">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/a8e90362-9dec-4b8c-870a-21d94afaf52c" width="500"/>
      <br><em>Product Demand Distribution per Region</em>
    </td>
  </tr>
</table>

### 3. Production Margin Analysis
Products such as **Household** and **Office Supplies** show significant unit margins. Comparative analysis between *Unit Price* and *Unit Cost* helps identify production efficiency in each product category.
<table border="0">
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/d7ce73de-4f37-4a0c-983d-87627d4e9ce5" width="500"/>
      <br><em>Unit Price vs Unit Cost by Item Type</em>
    </td>
  </tr>
</table>

### 4. Market Segmentation & Fraud Audit
The segmentation strategy groups products into *Star Products*, *Premium Niche*, and *Mass Market*. Additionally, the **Benford's Law** test confirms the natural distribution of the first digit (Digit 1 ≈ 28%), guaranteeing data integrity.
<table border="0">
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/68b24137-5e7a-473f-b9c0-d334fbadea67" width="500"/>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/d9e0fced-7290-4679-80ea-463a542bbbfc" width="600"/>
    </td>
  </tr>
  <tr>
    <td align="center"><em>Market Segment Distribution</em></td>
    <td align="center"><em>Fraud Audit: First Digit Distribution</em></td>
  </tr>
</table>

---

**Key Findings (Executive Insights)**

- **Profit Drivers:** Financial correlation shows that operational efficiency is well maintained along with revenue growth.
- **Market Integrity:** Statistical analysis through Benford's Law proves that transaction data is natural and free from manual manipulation.
- **Regional Strategy:** Focusing on expansion in the Sub-Saharan Africa and Europe regions is highly recommended considering the dominant volume of demand.
- **Product Portfolio:** Product identification through `Market Segment` allows companies to allocate resources more focused on *Star Products*.

---

**How to Run the Project**

1. **Clone this repository:**
   ```bash
   git clone [https://github.com/Ascalon984/Sales-Profitability-Auditing.git](https://github.com/Ascalon984/Sales-Profitability-Auditing.git)
   cd Sales-Profitability-Auditing
2. Make sure the dataset (Online-Store-Orders.xlsx) is available in the project folder.

3. Install dependencies:
pip install pandas numpy matplotlib seaborn tabulate

4. Run the Python script in order of numbering.
python "Data Sales Analysis.py"

---
Organized by **[Aditya Tri Prasetyo]** • 2026 | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/aditya-tri-prasetyo-7b3a0a396) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/aditya.trisetya)
