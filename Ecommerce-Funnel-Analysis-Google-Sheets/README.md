# 🛒 Ecommerce Funnel & Cohort Retention Analysis

Author: Orel Butbul  
Role: Business Intelligence Analyst  
Tool: Google Sheets  
Techniques: Pivot Tables | COUNTUNIQUE | VLOOKUP | TEXT | DATEDIF

---

## 📁 Project Files & Documentation

📄 **Full Report (PDF / Google Drive):**  
https://drive.google.com/file/d/1f3t1ktjmwTAwiV987nf-9mlCnMVghYJX/view?usp=drive_link

📊 **Google Sheets Analysis File (Model + Pivots):**  
https://docs.google.com/spreadsheets/d/1oL0Jq8XwsfDSlAtn1sGfjRhpeaiaRLMNHsqmgSlyQTQ/edit?usp=sharing

---

## 🧠 Business Objective

This project analyzes e-commerce user behavior to measure **conversion performance** and **customer retention over time**.

It answers key business questions:
- How effectively do product views convert into purchases?
- Where is the biggest drop-off in the funnel?
- How does retention change across cohorts after the first purchase?
- What actions could improve conversion and repeat purchasing?

---

## 🗂 Dataset Structure

Event-level activity data (raw logs), including fields such as:
- `user_id` (unique customer identifier)
- `event_type` (view, cart, purchase)
- `category_code` / `brand`
- `price`
- `event_date`

---

## 🔎 Key Analysis Areas

### 1) Conversion Funnel (View → Cart → Purchase)
Built a 3-stage funnel using Pivot Tables + COUNTUNIQUE to calculate:
- Unique users at each stage
- Stage-to-stage conversion rates
- Overall conversion rate

### 2) Cohort Preparation
Prepared purchase-only data and created a cohort model by:
- Identifying each user’s **first purchase month**
- Creating a cohort month field
- Calculating “cohort age” (months since first purchase)

### 3) Cohort Retention Analysis
Calculated retention by cohort by measuring returning purchasers over time:
- Cohorts grouped by first purchase month
- Retention tracked across cohort age (Month 0, Month 1, Month 2, etc.)
- Trends summarized into actionable insights

---

## 🛠 Tools & Skills Used

- Google Sheets
- Pivot Tables (funnel + cohort tables)
- COUNTUNIQUE (unique user calculations)
- VLOOKUP (joining cohort fields)
- TEXT (date formatting / month creation)
- DATEDIF (cohort age calculation)
- Data cleaning & transformation
- Business interpretation & recommendations

---

## ✅ Key Takeaways

- Funnel drop-off is strongest between **product view → cart**, indicating conversion friction early in the journey.
- Retention declines after the first purchase across cohorts, showing the need for stronger post-purchase engagement.
- Cohort tracking makes it easy to compare retention performance across acquisition months.

---

## 📌 Business Recommendations

1. Improve product-to-cart conversion (product pages, CTA clarity, trust signals, shipping visibility).
2. Reduce cart abandonment (reminder emails, incentives, streamlined checkout).
3. Launch post-purchase retention campaigns (email/SMS flows, loyalty offers, replenishment reminders).
4. Segment repeat behavior by category/brand to find high-LTV patterns.

---

## 🧩 Project Type

Business Intelligence | Funnel Analytics | Cohort Retention Modeling

