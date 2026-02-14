# Ecommerce Funnel & Cohort Retention Analysis

Business Intelligence project analyzing e-commerce user behavior to evaluate funnel performance and customer retention trends using Google Sheets.

---

## Project Documentation

- [View Full Report (PDF)](https://drive.google.com/file/d/1f3t1ktjmwTAwiV987nf-9mlCnMVghYJX/view?usp=drive_link)
- [View Google Sheets Analysis Model](https://docs.google.com/spreadsheets/d/1oL0Jq8XwsfDSlAtn1sGfjRhpeaiaRLMNHsqmgSlyQTQ/edit?usp=sharing)

---

## Business Objective

This analysis evaluates conversion efficiency and post-purchase retention in an e-commerce environment.

Key questions addressed:

- How effectively do product views convert into purchases?
- Where does the largest funnel drop-off occur?
- How does retention change across customer cohorts?
- What operational actions can improve conversion and repeat purchasing?

---

## Dataset Overview

Event-level activity logs including:

- user_id (unique customer identifier)
- event_type (view, cart, purchase)
- category_code / brand
- price
- event_date

---

## Analytical Framework

### Funnel Analysis (View → Cart → Purchase)

- Built a three-stage funnel using Pivot Tables  
- Calculated unique users per stage using COUNTUNIQUE  
- Computed stage-to-stage and overall conversion rates  
- Identified primary drop-off point  

### Cohort Modeling

- Isolated purchase events  
- Identified each user’s first purchase month  
- Created cohort month field  
- Calculated cohort age (months since first purchase)  

### Cohort Retention Analysis

- Measured returning purchasers by cohort  
- Tracked retention across cohort age (Month 0, Month 1, Month 2, etc.)  
- Compared performance across acquisition periods  

---

## Tools and Techniques

- Google Sheets  
- Pivot Tables  
- COUNTUNIQUE  
- VLOOKUP  
- TEXT (date normalization)  
- DATEDIF (cohort age calculation)  
- Data cleaning and transformation  
- KPI modeling and business interpretation  

---

## Key Findings

- The largest funnel drop-off occurs between product view and cart, indicating early-stage conversion friction.
- Retention declines after initial purchase across cohorts.
- Cohort tracking reveals performance variation by acquisition month.

---

## Business Recommendations

1. Improve product-to-cart conversion (optimize product pages, clarify CTAs, enhance trust signals).
2. Reduce cart abandonment (streamlined checkout, reminder flows, targeted incentives).
3. Strengthen post-purchase retention strategies (email automation, loyalty programs, replenishment campaigns).
4. Segment retention by product category and brand to identify high-LTV segments.
