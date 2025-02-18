# 🛒 Market Basket Analysis

This project implements **Market Basket Analysis** using three different approaches:

- **Apriori Algorithm** 🧩  
- **User-to-User Collaborative Filtering** 👥  
- **Item-to-Item Collaborative Filtering** 🏷️  

## 📌 Project Overview

Market Basket Analysis helps businesses understand customer purchasing behavior by finding associations between products. This project aims to identify product relationships and provide meaningful recommendations.

### 🔍 Approaches Used:
1. **Apriori Algorithm** – Identifies frequent itemsets and association rules.
2. **User-to-User Collaborative Filtering** – Recommends items based on similar users' purchase behavior.
3. **Item-to-Item Collaborative Filtering** – Suggests items similar to those a customer has already purchased.

---

## 📂 Dataset: Online Retail

- **Dataset Name**: `Online Retail.csv`
- **Source**: UCI Machine Learning Repository  
- **Description**: Contains transactional data from a UK-based online retail store.
- **Format**:
InvoiceNo | StockCode | Description | Quantity | InvoiceDate | UnitPrice | CustomerID | Country

## 🚀 Implementation Details

### **1️⃣ Apriori Algorithm**
- Uses **support**, **confidence**, and **lift** to extract frequent itemsets.
- Helps identify product combinations frequently bought together.
- Implemented using the `mlxtend` library.

### **2️⃣ User-to-User Collaborative Filtering**
- Identifies similar users based on purchase history.
- Uses **cosine similarity** to determine user similarity.
- Suggests products based on users with similar shopping patterns.

### **3️⃣ Item-to-Item Collaborative Filtering**
- Computes product similarity based on co-occurrence.
- Uses **cosine similarity** to find related items.
- Recommends items similar to those previously purchased.

---

## 📊 Results & Insights

- **Apriori rules** reveal strong associations like **{Milk, Bread} → Butter**.
- **User-based filtering** personalizes recommendations based on shopping patterns.
- **Item-based filtering** improves product recommendations with high precision.

---
