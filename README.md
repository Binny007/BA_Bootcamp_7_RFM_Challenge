# BA_Bootcamp_7_RFM_Challenge

#Segmentation - RFM (Recency, Frequency, Monetary) Challenge


# 🧩 Customer Segmentation Challenge – RFM Analysis

This repository contains a solution to the **Customer Segmentation Challenge**, which focuses on identifying the most valuable customers using the **RFM (Recency, Frequency, Monetary)** model. This analysis helps businesses understand customer behavior and prioritize marketing strategies accordingly.

---

## 📁 Repository Contents

- `RFM Challenge.ipynb`: Jupyter notebook with the full implementation of the RFM segmentation.
- `RFM Challenge.pdf`: A PDF summary of the challenge.
- `customer_data.csv`: Dataset used for the RFM analysis.
- `README.md`: You are here!

---

## 🏆 Challenge Overview

Companies often receive 80% of their revenue from just 20% of their customers. Identifying those high-value customers is critical for strategic decision-making. The challenge consists of the following steps:

---

## ✅ Objectives

### 1. **Prepare the Monetary (Basket) Variable**
- Created by dividing total revenue by the number of orders for each customer.
  
### 2. **Rename Variables**
- Standardized column names to `recency`, `frequency`, and `monetary` for easier RFM mapping.

### 3. **Build the RFM Model**
- Customers are scored on a scale of 1 to 3 for each R, F, and M metric.
- Combined into a total **RFM score**.

### 4. **Define Segments**
- A custom function assigns customers into segments based on their RFM score.
- Segments include:
  - `SuperStar`
  - `High Potential`
  - `Low Relevance`

### 5. **Generate an Overview**
- Summary statistics generated for each customer segment to help present insights to stakeholders.

---

## 📊 Sample Output

| RFM Segment     | Recency (avg) | Frequency (avg) | Monetary (avg) | Customers |
|----------------|---------------|------------------|----------------|------------|
| SuperStar       |     xx days    |       x.x         |     xxx.xx      |     xx     |
| High Potential  |     xx days    |       x.x         |     xxx.xx      |     xx     |
| Low Relevance   |     xx days    |       x.x         |     xxx.xx      |     xx     |

---

## 🛠️ Tools Used

- **Python** (Pandas, Numpy)
- **Jupyter Notebook**
- **CSV Data Handling**

---

## 📌 Conclusion

The RFM model is a powerful framework for customer segmentation. This project illustrates how to preprocess customer data, apply scoring logic, and define actionable segments that businesses can leverage for targeted marketing and retention strategies.

---

> 💡 *Want to dive into the code and explore the logic? Check out `RFM Challenge.ipynb`.*

---
