# 📊 VentureInsight – Business Intelligence & Data Analytics Project

## 📎 Project Files & Documentation

📄 **SQL Project PDF (Full Report & Queries):**  
👉 [View SQL Project PDF](https://drive.google.com/file/d/1jytI13zvSSiT-1qfJRxqk-cXSExvjAxO/view?usp=drive_link)  
This PDF includes my complete SQL solutions, ER diagram explanations, analysis logic, and query outputs used in this project.

---

## Overview
This project simulates my first week as a **Data Analyst at VentureInsight**, a research firm providing data-driven insights to venture capital firms and startup investors.  
The goal of the project was to analyze a comprehensive venture capital database and produce insights that support **investment decisions, market analysis, and strategic planning**.

Using SQL and business analytics techniques, I explored startup performance, funding trends, acquisitions, investor behavior, and talent signals across the global startup ecosystem.

---

## 🧠 Business Objective
Venture capital clients rely on accurate, data-backed insights to make **multi-million-dollar investment decisions**.  
This project supports a quarterly investment report by answering critical questions such as:

- How successful are startups overall?
- Which sectors and countries attract the most funding?
- How do venture funds differ in activity and strategy?
- Do education levels correlate with startup failure or success?

---

## 🗄️ Database Structure
The analysis is based on a relational database with the following core tables:

- **company** – Startup details (status, funding total, category, country)
- **fund** – Venture capital fund information
- **funding_round** – Funding round data (amounts, dates)
- **investment** – Records of fund participation in funding rounds
- **acquisition** – Acquisition details and payment types
- **people** – Founders, employees, and investors
- **education** – Educational background of individuals

---

## 🔍 Key Analyses & Tasks

### 1. Startup Landscape Analysis
- Calculated how many startups **closed down** versus those still operating or acquired.
- Established a baseline startup success rate.

### 2. Sector Analysis for US Investors
- Identified **US-based news and media companies**.
- Ranked companies by **total funding raised** to benchmark investment sizes.

### 3. Cash Acquisition Analysis (2011–2013)
- Analyzed **cash-only acquisitions** during the post-recession period.
- Calculated total acquisition value in USD.

### 4. Identifying Industry Influencers
- Extracted individuals whose Twitter usernames start with **“Silver”**.
- Supported influencer outreach and marketing campaigns.

### 5. Finding Finance Influencers
- Identified finance-focused influencers with **“money”** in their Twitter handle.
- Filtered further by last names starting with **“K”**.

### 6. Geographic Investment Analysis
- Calculated total funding raised **by country**.
- Ranked countries by investment volume to highlight global VC hotspots.

### 7. Funding Round Volatility Analysis
- Compared **largest vs. smallest funding rounds per day**.
- Identified days with significant market volatility.
- Excluded zero-funding and equal-value anomalies.

### 8. Fund Activity Classification
Venture funds were classified based on investment activity:
- **High activity**: 100+ investments  
- **Middle activity**: 20–99 investments  
- **Low activity**: fewer than 20 investments  

### 9. Investment Strategy by Fund Activity
- Analyzed whether highly active funds participate in **more funding rounds per company**.
- Calculated and compared average funding rounds by activity category.

### 10. Employee Education & Startup Failure
- Identified startups that **closed after only one funding round**.
- Analyzed employee education data for those companies.
- Calculated the **average number of degrees per employee** at failed startups.

---

## 🛠️ Tools & Skills Used
- **SQL** (joins, subqueries, aggregation, filtering)
- **Business Intelligence & Analytics**
- **Data Cleaning & Validation**
- **Exploratory Data Analysis (EDA)**
- **Data-driven storytelling**
- **Investment & market analysis**

---

## 📈 Key Takeaways
- Funding concentration varies significantly by **sector and geography**.
- Highly active funds tend to follow different participation strategies than smaller funds.
- Market volatility can be detected through funding round dispersion.
- Education data provides measurable insight into **startup failure patterns**, but does not fully explain success on its own.

---

## 📁 Project Type
**Business Intelligence / Data Analytics Portfolio Project**  
Designed to simulate real-world VC analytics and stakeholder reporting.

---

## 👤 Author
**Orel Butbul**  
Aspiring Data Analyst | Business Intelligence & Analytics  
📍 United States

---

## 📌 Notes
This project was completed as part of a structured BI Analytics program and reflects real-world analytical workflows, stakeholder-driven questions, and SQL-based insights used in venture capital research.
