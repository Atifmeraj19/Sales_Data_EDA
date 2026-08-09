# Sales Data — Exploratory Data Analysis

Exploratory Data Analysis of an e-commerce sales dataset with ~11,250 customer transactions, exploring who buys the most and which products and categories drive sales across gender, age, region, profession, and product category.

## Objective
Identify the customer segments and product categories that drive the most orders and revenue, to support data-driven marketing and inventory decisions.

## Dataset
- ~11,257 rows × 13 columns
- Fields include: User ID, Customer Name, Product ID, Age, Age Group, Gender, State, Zone, Profession, Product Category, Orders, and Amount

## Tools & Libraries
- Python
- pandas, NumPy — data loading, cleaning, and aggregation
- Matplotlib, Seaborn — data visualization
- Jupyter Notebook

## Process

**1. Data loading & inspection**
- Loaded the CSV with `unicode_escape` encoding to handle special characters
- Inspected structure with `.shape`, `.head()`, and `.info()`

**2. Data cleaning**
- Dropped the empty `Zipcode` column
- Checked for null values and removed fully-empty rows
- Standardized the `Gender` column (`M` → `Male`)

**3. Exploratory analysis & visualization**
- Summary statistics with `.describe()`
- Gender distribution (count plot, pie chart) and gender-wise total sales
- Age-group analysis, including age group split by gender
- State-wise analysis — top 5 states by orders and by revenue
- Product category analysis — by count, revenue, and gender
- Profession-wise analysis of buyers
- Top 10 products by number of orders

## Key Findings
Female shoppers aged 26–35, primarily from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the most active buyers — with Beauty, Sports, and Electronics being the top-performing product categories. Female customers accounted for higher total sales than male customers.

## Author
Sheikh Atif Meraj — MSc Data Science student
[LinkedIn](https://www.linkedin.com/in/atifmeraj007/) · [GitHub](https://github.com/Atifmeraj19)
