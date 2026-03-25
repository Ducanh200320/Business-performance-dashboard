**BUSINESS PERFORMANCE | POWER BI**

<img width="499" height="232" alt="Aspose Words 342cd697-a231-4f0c-980a-f422dcefcda1 001" src="https://github.com/user-attachments/assets/bfe5f03a-7e66-40d7-aafb-3405c8465bc9" />

**Author**: Dang Duc Anh

**Date:** January 2026

**Tools Used:** BI

**# Table of Contents:**
- **Dataset Description & Data Structure**
- **Outcome Dashboard:**

**1. Dataset Description & Data Structure**
   
   **📌 Data Source**
   
    - Source: Kaggle
    - Format:Pbix
      
    📊 Data Structure & Relationships

    The dataset consists of 5 main tables:
  - **customer.csv (Customer Information):**
    - Contains profiles for over 12,000 customers.
    - Key fields: customer id, age, and gender. This is the primary data for     demographic analysis.
  - **product.csv (Product Catalog):**
    - Lists 13 different office furniture products (e.g., Desk Lamps, Office Chairs, Bookshelves).
    - Key fields: product id, sku, product type, and unit price.
  - **orders.csv (Transaction Data - The Central File):**
    - Records nearly 10,000 sales transactions.
    - Role: This file connects everything. It links a customer id to a product id, a payment id, and a shipping id.
    - Key fields: Order status (Completed/Cancelled), date, feedback score, quantity, and total cost.
  - **payment.csv (Payment Methods):**
    - A lookup table for the 5 available payment options (Bank Transfer, Cash, Credit Card, Debit Card, Paypal).
    - Key fields: payment\_id, method name, and type (Online vs. Offline).
- **shipping.csv (Shipping Options):**
    - A lookup table for delivery methods (Standard, Expedited, Express, Overnight, Same Day).
    - Key fields: shipping id, shipping category, and the associated cost level (Low to Very High).
 
**📦Data relationships:**
         
<img width="795" height="428" alt="image" src="https://github.com/user-attachments/assets/e48bf888-e425-4999-9cae-fe31e8319237" />





**2. Outcome Dashboard:**

   **🔗Visual Link:** https://app.powerbi.com/view?r=eyJrIjoiYzFiM2ZlNjUtZWQ0Yi00MTgzLWFkMWMtYzExZmU5ODM0NWFjIiwidCI6IjY5MDRhYjJkLTlhZjQtNDNlOS05ODlmLTY1Mzg1NWEyODcyYSIsImMiOjEwfQ%3D%3D

      <img width="705" height="401" alt="image" src="https://github.com/user-attachments/assets/420e5364-8c5b-4c7c-8035-8e60e8e371ae" />








