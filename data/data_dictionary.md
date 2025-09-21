# Data Dictionary – Inventory Dataset

This dataset (`inventory_dataset_100_products.xlsx`) contains **simulated data** for 100 products.  
It is designed to demonstrate inventory optimization formulas (EOQ, Safety Stock, Reorder Point).

---

## Columns

| Column Name            | Description                                                                 | Example |
|-------------------------|-----------------------------------------------------------------------------|---------|
| **Product ID**          | Unique identifier for each product.                                        | P001 |
| **Average Demand**      | Average daily demand (units per day).                                      | 120 |
| **Std. Dev. of Demand** | Standard deviation of daily demand, used for Safety Stock calculation.     | 15 |
| **Lead Time (days)**    | Average supplier lead time in days.                                        | 7 |
| **Holding Cost**        | Cost of holding one unit of inventory per year.                            | 2.50 |
| **Ordering Cost**       | Cost per order placed (fixed cost).                                        | 50 |
| **Service Level**       | Desired service level (probability of not stocking out), expressed in %.   | 95% |

---

## Notes
- All values are **simulated** for demonstration purposes only.  
- Units of measurement are consistent across products.  
- These fields are enough to calculate:  
  - **Economic Order Quantity (EOQ)**  
  - **Safety Stock**  
  - **Reorder Point (ROP)**  
