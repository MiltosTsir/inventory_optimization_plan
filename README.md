# Inventory Optimization Plan

## Purpose
This project demonstrates how to optimize inventory using simple Excel tools and formulas.  
It is designed as a **portfolio project** to showcase skills in supply chain analysis, data handling, and visualization.

---

## Features
- **Simulated Dataset** with 100 products.  
- **Key Formulas** implemented:
  - EOQ (Economic Order Quantity)
  - Safety Stock
  - Reorder Point (ROP)  
- **Excel Dashboard** to visualize:
  - Optimal order quantities
  - Reorder points
  - Inventory cost breakdown
  - Stockout risk analysis  
- **Insights & Recommendations** for balancing costs and product availability.

---

## Repository Structure
inventory_optimization_plan/
├── data/
│   └── inventory_dataset_100_products.xlsx
├── dashboard/
├── images/
├── docs/
│   └── data_dictionary.md
└── README.md

---

## Key Formulas
- **EOQ** = √(2DS / H)  
- **Safety Stock** = Z × σd × √L  
- **ROP** = (Average Demand × Lead Time) + Safety Stock  

---

## Dashboard
The Excel dashboard (`dashboard/inventory_dashboard.xlsx`) visualizes KPIs and recommendations.  

![Dashboard Screenshot](images/dashboard_screenshot.png)

---

## Insights
- Products with higher demand variability require more **Safety Stock**.  
- For slow-moving products, smaller EOQ reduces holding costs.  
- Balancing **service level vs. costs** helps optimize availability.  

---

## Notes
- The dataset is fully **simulated** and anonymized.  
- Excel files and images are small enough to be uploaded directly.  
- For larger binary files, consider using **Git LFS**.  
