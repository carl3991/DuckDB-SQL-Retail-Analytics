# Retail Analytics

### Project Description
This project uses simulated retail data using **DuckDB** and **SQL**. Usually, real company data is often private and unavailable to the public, therefore, synthetic datasets were created and they will showcase strong SQL, data modeling, analytics, and visualization skills without
using confidential information. The goal here is to show the ability to design a small data warehouse, generate data, write SQL queries, and derive business insights such as:
* Revenue trends
* Customer segmentation (RFM, CLV)
* Product performance
* Category contribution
* Geographic insights
* Cumulative Revenue metric

### Data Model (Star Schema)

##### Fact Table

* sales
     * transaction_id
     * sale_date
     * product_id
     * customer_id
     * quantity
     * revenue
##### Dimension Tables
* customer
   * custumer_id
   * gender
   * state
   * customer_age
   * customer_segment
* product
    * product_id
    * unit_price
    * brand
    * category

### Key Insights
1. **Monthly Sales Summary View**
* Total revenue generated
* Total quantity sold
* Total orders
* Average order value
2. **Cumulative Revenue Over Time**
  
To visualize growth trajectory.
3. **Category Revenue Contribution**

Percentage share of each category relative to total revenue.
4. **Product Performance**
* Top products by revenue
* Product ranking within each category
5. **Customer Segmentation**
* Receny-Frequency-Monetary (RFM) Analysis
6. **Customer Behavior Insights**
* Customers who never purchased from Electronics
* Premium vs Budget customer revenue comparison
* State‑level revenue patterns
### Visualizations
* Revenue by product category
* Revenue by custument segment
* Monthly revenue trend
* Cumulative revenue over time
### Conclusion
*
*
*
*
*
