# 📊 E-Commerce Sales Insights Dashboard

An interactive, end-to-end **Excel Sales Dashboard** built using a cleaned and standardized transactional dataset of 300 orders. This project demonstrates database consistency, advanced formula implementation, data validation, dynamic pivot tables, and professional data visualization techniques.

---

## 🖥️ Dashboard Preview
<img width="809" height="278" alt="excel-dashboard" src="https://github.com/user-attachments/assets/9d745e59-43b8-4cd2-854d-f3ee0b74f274" />

---

## 🛠️ Key Features Implemented
*   **Dynamic Total Calculations:** Replaced hardcoded total values with clean formulas: `=(Price * Quantity) * (1 - Discount_Percent)` to ensure mathematical integrity.
*   **Data Validation Dropdowns:** Implemented drop-down menus on the main data entry tab to ensure clean categorization and prevent user typos.
*   **Logical Demographics Preservation:** Maintained a dedicated "Women" category for faith-based and women-specific clothing (like Hijabs), preserving valuable demographic insights that would otherwise be lost in general categories.
*   **Interactive Slicers:** Connected slicers for **City**, **Category**, **Product**, and **Payment Method** to update all pivot tables and charts simultaneously in real-time.
*   **Professional Documentation Tab:** Included a clean, custom `readme` sheet inside the workbook for end-user documentation.

---

## 📈 Key Business Insights From the Data

Based on the final 300 processed transactions, the store generated **$2,347,955 in Total Revenue** with **904 total units sold**.

### 1. Product Category Performance
*   **Clothing** is the dominant category, driving **$1,253,740** in sales (505 units).
*   **Footwear** brought in **$558,900** (136 units).
*   **Accessories** generated **$433,300** (137 units).
*   **Women's Specific Wear** (Hijabs & Dresses) successfully isolated **$102,015** in targeted niche revenue (126 units).

### 2. Regional Sales Distribution
Our sales span across 5 major cities, with Multan leading the pack:
1.  **Multan:** $628,595 (Top performing region)
2.  **Faisalabad:** $533,135
3.  **Karachi:** $403,195
4.  **Islamabad:** $395,525
5.  **Lahore:** $387,505

### 3. Payment Method Preferences
Payment methods are highly balanced, showing strong trust across all options:
*   **Cash on Delivery (COD):** Leads slightly with **$862,320** (105 orders).
*   **Card Payments:** Follows closely with **$785,550** (106 orders).
*   **Digital Wallets:** Generated **$700,085** (89 orders).

---

## 📁 File Directory Structure
*   `sheet1`: Raw sales data with active formulas and dropdown validations.
*   `readme`: Visual project summary and documentation.
*   `pivot`: Back-end pivot structures.
*   `dashboard`: The main visual presentation layer.
