# SKU-Management

# Project Background
Effective inventory and SKU management is a critical backbone of supply chain operations, ensuring seamless alignment between warehouse storage, working capital efficiency, and product availability. In complex operational environments, poor visibility over stock movement, high-risk inventory items, and multi-location warehouses often lead to capital lockup, unexpected stockouts, or excessive holding costs.
Driven by a desire to bring clarity and peace of mind to daily operations, this project was built not just as a tool for crunching numbers, but as a reliable analytical companion for supply chain practitioners. By transforming raw logistical data into clear, intuitive insights—monitoring stock health, identifying high-risk items, and tracking stock movements across every warehouse corner.

# Data Structure Overview
The project utilises a relational data model built within an Excel workbook (SKU MANAGEMENT.xlsx), mimicking a professional Warehouse Management System (WMS) or ERP database. The data architecture consists of the following interconnected sheets:

1. CURRENT STOCK: The master inventory table holding 500 SKUs, tracking core attributes such as SKU codes, item descriptions, categories, safety parameters (Minimum Stock, Reorder Point), unit costs, current stock levels, stock statuses, financial valuations, and physical count variances.
2. STOCK IN: A transactional log comprising 1,800 records of inbound stock movements, capturing transaction IDs, timestamps, quantities received, supplier details, and purchase order references.
3. STOCK OUT: A transactional log containing 2,200 records of outbound shipments and internal distributions, tracking issue dates, quantities, destinations, and document references.
4. Item Master: The foundational reference table defining item metadata, supplier mappings, and standard lead times.
5. DASHBOARD & PIVOT: Summarised aggregation layers feeding key performance indicators (KPIs) and dynamic pivot metrics.

# Executive Summary
<img width="1416" height="750" alt="SKU MANAGEMENT_DASHBOARD" src="https://github.com/user-attachments/assets/d7e89e39-a25e-4389-ae75-9a18457ee738" />
Ps: Due to image compression, some chart labels and figures in the preview image above may appear unclear. For the best viewing experience and full interactivity, please open the SKU MANAGEMENT.xlsx file directly in Microsoft Excel.


An analytical overview of the 500 SKU portfolio reveals the following key performance indicators:
1. Asset Scale & Valuation: Total inventory value stands at Rp28,425,028,000, distributed across various storage zones (Zones A to E).
2. Stock Health Breakdown:
A. In Stock: 387 SKUs (77%) maintain healthy stock levels.
B. Out of Stock: 58 SKUs (12%) require immediate intervention to prevent operational bottlenecks.
C. Reorder Required: 28 SKUs (6%) have reached their designated reorder thresholds.
D. Low Stock: 27 SKUs (5%) sit close to critical safety limits.
3. Financial Risk Concentration: High-value categories such as Computer Hardware (specifically graphics cards and processors) dominate capital allocation, with individual items valued between Rp1.4 billion and Rp2.0 billion.
4. Physical Audit Variance:
A. Conform: 201 SKUs (40.2%) show perfect alignment between system records and physical counts.
B. Minus: 158 SKUs display negative variances (potential shrinkage or misplacement).
C. Surplus: 141 SKUs exhibit positive inventory discrepancies.

# Recommendation 
Based on the empirical findings from the dataset, the following operational improvements are recommended:
1. Immediately execute purchase orders for the 58 out-of-stock items and 28 reorder-flagged SKUs to mitigate lost sales and fulfil pending demand.
2. Implement Value-Based ABC Analysis and heightened physical security to high-capital Computer Hardware items to safeguard against inventory shrinkage.
3. Conduct targeted audits on the 158 Minus variance items and 141 Surplus variance items to reconcile discrepancies between system logs and physical warehouse stock.
4. Calibrate lead times and safety stock calculations for items experiencing high inbound and outbound volatility to stabilise stock buffer levels.
Surplus: 141 SKUs exhibit positive inventory discrepancies.
# Recommendation
