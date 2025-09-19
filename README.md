# 🛒 Shopping Behavior Analysis

This repository contains an end-to-end analysis of customer shopping behavior using a Kaggle dataset.  
The notebook explores *purchase patterns, customer demographics, discount strategies, payment preferences, and high-value transactions* to generate actionable business insights.

---

## 📂 Dataset
- *Source*: Kaggle Dataset (exported as HTML and CSV)  
- *File*: shopping_behavior_updated.csv  
- *Key Features*:
  - Customer ID
  - Age, Gender, Location
  - Item Purchased, Category
  - Purchase Amount (USD)
  - Promo Code Used, Discount Applied
  - Payment Method
  - Frequency of Purchases
  - Subscription Status

---

## 🎯 Objectives
1. Identify the *Top 5 most frequently purchased items*.  
2. Detect *customers who used promo codes more than twice*.  
3. Build *pivot tables* to analyze average purchase amount across *Category × Payment Method*.  
4. Classify purchases into *High Value (>500 USD)* or *Normal*.  
5. Parse *purchase year* from dates and analyze spending trends.  
6. Generate *business insights* that can help improve sales strategy.

---

## 📊 Key Analysis & Results

### 🔝 Top 5 Purchased Items
- *Pants, Jewelry, Socks, Hat* appear most frequently in purchases.  
- Indicates high demand for *affordable essentials*.

### 🎟 Promo Code Usage
- Very few customers use promo codes more than 2 times.  
- Suggests either:
  - Promo campaigns are *not repeated effectively*, or  
  - *Customer awareness is low*.  

### 💳 Payment Preferences
- *Credit Cards & Debit Cards* show the highest average purchase values.  
- *Outerwear* has the highest average spend when paid via *Cash*.  
- Indicates customers trust cards for *larger transactions*.

### 💰 High-Value Purchases
- Purchases above *$500* are rare but exist across multiple categories.  
- These transactions should be *targeted for premium loyalty programs*.

### 📅 Purchase Year Trends
- After parsing years, most purchases cluster *post-2020*, showing increased digital shopping adoption.  

---

## 🧠 Real-Time Business Insights
1. *Category Demand*  
   - Essentials like *clothing and accessories* are purchased most often.  
   - Opportunity: Bundle these items for upselling.

2. *Promo Code Effectiveness*  
   - Very few repeated uses → Marketing should *redesign promo campaigns* for retention.  
   - Personalized promo codes can encourage loyalty.

3. *Payment Strategy*  
   - Customers spend more via *cards* than *cash/PayPal*.  
   - Suggests partnerships with banks for *cashback offers*.

4. *High-Value Customers*  
   - Purchases > $500 indicate *premium customers*.  
   - Opportunity: Offer *exclusive memberships, free express shipping, or premium discounts*.

5. *Subscription Behavior*  
   - Subscribed users purchase *more frequently*.  
   - Subscription model should be *expanded and incentivized*.

---

## 🚀 How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shopping-behavior-analysis.git
