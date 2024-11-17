# Problem Statement

The project aims to design and implement a data engineering pipeline for analyzing customer purchasing behavior and optimizing sales operations. Business stakeholders require actionable insights to improve marketing strategies, enhance customer targeting, and ensure efficient inventory management. This involves building a system that processes, analyzes, and visualizes online retail sales data for real-time and batch operations.

# Dataset Explanation

Below is a detailed explanation of each column in the dataset:

Transaction ID:

Unique identifier for each customer transaction. Useful for tracing and de-duplicating records.
Customer ID:

Unique identifier for each customer. Helps link transactions to specific individuals for segmentation and analysis.
Product ID:

Unique identifier for each product. Enables tracking of product-level sales trends.
Product Category:

The category to which a product belongs (e.g., Electronics, Apparel). Useful for analyzing category-level sales.
Quantity:

Number of units purchased in a transaction. Helps calculate revenue and detect bulk purchases.
Unit Price:

Price of a single unit of a product. Used to calculate transaction revenue.
Discount:

Discount applied to the transaction. Helps analyze the impact of promotional strategies.
Total Price:

Total cost for the transaction after applying discounts (calculated as Quantity * Unit Price - Discount).
Payment Method:

Method used to complete the purchase (e.g., Credit Card, PayPal). Useful for analyzing payment trends.
Transaction Date:

Date and time of the transaction. Critical for time-based trend analysis.
Customer Age:

Age of the customer. Helps in demographic analysis and segmentation.
Customer Gender:

Gender of the customer. Useful for targeting specific customer groups.
Customer Location:

Geographical location of the customer. Useful for regional sales analysis.
Customer Loyalty Tier:

Loyalty tier assigned to the customer (e.g., Silver, Gold). Helps analyze purchasing behavior by loyalty levels.












