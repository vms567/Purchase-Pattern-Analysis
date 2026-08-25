#  Purchase Pattern Analysis

##  Project Overview

Purchase Pattern Analysis is a retail analytics project that analyzes customer purchasing behavior and identifies products frequently purchased together.

The project uses **Market Basket Analysis** and the **Apriori Algorithm** to discover product associations and generate actionable business insights.

---

##  Objectives

- Analyze retail transaction data.
- Perform data cleaning and Exploratory Data Analysis (EDA).
- Identify frequently purchased products.
- Apply the Apriori algorithm to find frequent itemsets.
- Generate association rules using Support, Confidence, and Lift.
- Visualize results using Power BI.
- Provide business recommendations for cross-selling and product bundling.

---

##  Dataset

- **Records:** 50,000
- **Columns:** 7
- **Unique Products:** 2,802
- **Countries:** 19
- **Cleaned Records:** 49,152
- **Primary Market:** United Kingdom

### Main Features

`BillNo` | `Itemname` | `Quantity` | `Present_Date` | `Price` | `CustomerID` | `Country`

---

##  Data Cleaning

The following steps were performed:

- Handled missing values
- Removed duplicate records
- Standardized text data
- Converted date fields
- Removed invalid quantities and prices
- Created transaction-level product baskets
- Converted the basket into binary format for Apriori analysis

---

##  Market Basket Analysis

The **Apriori algorithm** was used to identify frequent product combinations and generate association rules.

### Parameters

| Metric | Value |
|---|---:|
| Minimum Support | 0.02 |
| Minimum Lift | 1 |
| Confidence Threshold | 0.60 |

### Key Metrics

- **Support** – Frequency of an itemset in transactions
- **Confidence** – Likelihood of purchasing the consequent when the antecedent is purchased
- **Lift** – Strength of association between products

---

##  Key Findings

- **WHITE HANGING HEART T-LIGHT HOLDER** was the most frequently occurring product.
- Several strong product associations were identified.
- Some rules achieved confidence above **0.60**.
- The highest observed lift was approximately **21.90**.
- The analysis identified opportunities for cross-selling and product bundling.

---

##  Business Recommendations

- Use strong associations for **cross-selling**.
- Create **product bundles** based on high-lift rules.
- Implement **Frequently Bought Together** recommendations.
- Use purchase patterns for targeted promotions.
- Prioritize frequently purchased products for inventory planning.

---

##  Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Mlxtend**
- **Apriori Algorithm**
- **Market Basket Analysis**
- **Power BI**

---

##  Repository Contents

| File | Description |
|---|---|
| `Cleaned_dataset.xlsx` | Cleaned dataset |
| `EDA_and_Data_Cleaning_Report.pdf` | EDA and cleaning report |
| `MBA_analysis.pbix` | Power BI dashboard |
| `Notebook.ipynb` | Python analysis notebook |
| `Purchase_Pattern_Analysis .pdf` | Project report |
| `Report_Presentation.pptx` | Project presentation |
| `Rules_output.xlsx` | Association-rule results |

---

##  Author

**Vikas Gaikwad**

**Data Analyst | Python | SQL | Power BI | Excel**

---

 *This project demonstrates the use of data analytics and Market Basket Analysis to convert retail transaction data into actionable business insights.*
