# KPI Definitions – Inventory Optimization

This document explains the main KPIs and formulas used in the **Inventory Optimization Plan** project.

---

## Economic Order Quantity (EOQ)
**Definition:**  
The ideal order quantity that minimizes the total cost of ordering and holding inventory.

**Formula:**  
\[EOQ = \sqrt{\frac{2DS}{H}}\]

- **D** = Annual demand (units)  
- **S** = Ordering cost per order  
- **H** = Holding cost per unit per year  

**Interpretation:**  
Higher demand → larger EOQ.  
Higher holding cost → smaller EOQ.

---

## 🛡️ Safety Stock (SS)
**Definition:**  
Extra stock kept as a buffer against demand or supply variability.

**Formula:**  
\[SS = Z \times \sigma_d \times \sqrt{L}\]

- **Z** = Service level factor (based on % target)  
- **σd** = Standard deviation of demand  
- **L** = Lead time (days)  

**Interpretation:**  
Higher variability or longer lead times → higher Safety Stock.

---

## Reorder Point (ROP)
**Definition:**  
The inventory level at which a new order should be placed to avoid stockouts.

**Formula:**  
\[ROP = (Average\ Demand \times Lead\ Time) + Safety\ Stock\]

- **Average Demand** = Daily demand  
- **Lead Time** = Supplier delivery time in days  
- **Safety Stock** = As calculated above  

**Interpretation:**  
ROP ensures that new orders arrive just before inventory runs out.

---

## Summary
- **EOQ** → How much to order.  
- **Safety Stock** → How much buffer stock to keep.  
- **ROP** → When to reorder.  
