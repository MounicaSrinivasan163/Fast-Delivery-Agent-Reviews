# Fast-Delivery-Agent-Reviews
# 🚚 Fast Delivery Agent Reviews – Dataset Analysis

This repository contains a dataset of **5,000 real-world delivery reviews** across top delivery agents in India. It enables data exploration, service quality benchmarking, customer satisfaction analysis, and sentiment classification using pandas.

---

## 📦 Dataset Overview

- **File:** `Fast Delivery Agent Reviews.csv`
- **Records:** 5,000
- **Columns:** 12
- **Purpose:** Evaluate delivery agent performance, customer experience, and sentiment across multiple variables.

---

## 📊 Feature Classification: Categorical vs Continuous

| Feature Name               | Type         | Description                              |
|---------------------------|--------------|------------------------------------------|
| `Agent Name`              | Categorical  | Delivery provider                        |
| `Rating`                  | **Continuous** | Customer rating (float)                  |
| `Review Text`             | Categorical  | Unstructured text (useful for NLP)       |
| `Delivery Time (min)`     | **Continuous** | Numeric delivery time in minutes         |
| `Location`                | Categorical  | Customer’s city                          |
| `Order Type`              | Categorical  | Type of product ordered                  |
| `Customer Feedback Type`  | Categorical  | Sentiment class                          |
| `Price Range`             | Categorical  | Price category                           |
| `Discount Applied`        | Categorical  | Yes or No                                |
| `Product Availability`    | Categorical  | In Stock or Out of Stock                 |
| `Customer Service Rating` | **Continuous** | Integer rating (0–5)                      |
| `Order Accuracy`          | Categorical  | Whether the order was accurate           |


**The colab analysis contains:

-*Data Reading*

-*Data Preprocessing/cleaning*

-*Pandas Analysis*

-*Encoding*

-*Correlation Analysis*

-*Statistical Analysis*
---

## 🔍 Medium-Level Analysis (Pandas)

1. **Average customer rating:** 
2. **Average delivery time:** 
3. **Review count per delivery agent** 
4. **Feedback type distribution** 
5. **Most common price range:**   
6. **Agent-wise average rating**  
7. **Average service rating by city** 
8. **Order Accuracy count:**  
9. **Fastest order type:** 
10. **Average rating: With vs Without discount** 

---

## 🧠 Complex-Level Analysis (Pandas)

1. **Correlation: Delivery time vs Rating**  
2. **Average delivery time by Order Accuracy**  
3. **Best agent in cities with lowest service ratings**  
4. **Do customers rate higher when product is in stock & discount applied?**  
5. **Top 3 Agent + Order Type combos by rating**  

> *(See `notebooks/` or `main_analysis.py` for full code & output)*

---

## 🛠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fast-delivery-reviews.git
   cd fast-delivery-reviews
