#  Sales Data Analysis Report

---

##  1. Objective
The objective of this project is to analyze sales data to:
- Use pandas to load and analyze data
- Handle missing values appropriately
- Calculate at least 3 different metrics
- Create a clean, formatted report
- Add comments explaining each step

---

##  2. Dataset Overview
The dataset contains sales transaction records with the following columns:
- Date: Date of the day when item was bought
- Product: Name of the product
- Quantity: Number of units sold
- Price: Price per unit
- Customer_ID: A unique identifier for customer who purchased the product
- Region: The region (North, South, East, West) where the product was purchased
- Total_Sales = Quantity × Price

Dataset Shape:
- Rows: 101
- Columns: 7

---

##  3. Data Exploration
- Checked dataset structure using `.shape`, `.columns`, and `.dtypes`
- Verified numerical and categorical columns
- Observed initial data distribution and potential issues

---

##  4. Data Cleaning
The following preprocessing steps were performed:
- No missing or duplicate values

---

##  5. Key Metrics

### Total Revenue
Total revenue was calculated as:
Total_Sales = Quantity × Price

Total Revenue

---

## 6. Best-Selling Product Analysis 

The best-selling product was evaluated using multiple metrics:

1. Quantity Sold (Demand Perspective)
  a.) The total quantity sold for each product was calculated using grouping.
  b.) This metric helps identify which product has the highest customer demand.

2. Total Sales (Revenue Perspective)
  a.) A new column Total_Sales was created:
    Total_Sales = Quantity × Price
  b.)The total revenue for each product was then aggregated.

3. Sorting for Ranking
  a.) The results were sorted in descending order to rank products from highest to lowest.
  b.) This makes it easy to:
    1.) Identify top performers
    2.) Compare products effectively

###  Final Conclusion


The best-selling product was identified by analyzing both total quantity sold and total revenue generated. The results were sorted in descending order, and the product that consistently ranked highest across these metrics was concluded to be the best-performing product.

---

##  7. Key Insights

- The product Laptop ranks highest in both total quantity sold and total revenue, making it the overall best-performing product.
-  Laptop is the Revenue Leader
    a.) Contribution: 31.45%
    b.) Significantly higher than others
- Laptop, Tablet, and Phone are highest contributors.
- Headphones, and monitors are low contributors.
- 

---

##  8. Limitations

- The dataset is relatively small, which may limit the generalizability of insights.

- No cost or profit data is available, so analysis is limited to revenue and does not reflect actual profitability.

- External factors such as discounts, customer segments, or marketing campaigns are not considered.



