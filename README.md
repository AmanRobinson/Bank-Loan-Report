# 🏦 Bank Loan Report | Power BI & SQL Dashboard
 
A 3-page interactive Power BI dashboard built to analyze a bank's loan portfolio performance — covering loan applications, funding, repayment trends, risk segmentation, and borrower profiles.
 
---
 
## 📸 Dashboard Screenshots
 
### Page 1 — Summary
![Summary Dashboard](screenshots/summary.png)
 
### Page 2 — Overview
![Overview Dashboard](screenshots/overview.png)
 
### Page 3 — Details
![Details Dashboard](screenshots/details.png)
 
> 📂 **To add screenshots:** Create a `screenshots/` folder in your repo root, upload your 3 images as `summary.png`, `overview.png`, and `details.png`, and the images above will auto-render on GitHub.
 
---
 
## 📊 Project Overview
 
| Metric | Value |
|---|---|
| Total Loan Applications | 38,576 |
| Total Funded Amount | $435.8M |
| Total Amount Received | $473.1M |
| Average Interest Rate | 12.05% |
| Average DTI | 13.33% |
 
---
 
## 📁 Dashboard Pages
 
### 1. Summary
- KPI cards with **MTD** (Month-to-Date) and **MoM** (Month-over-Month) comparisons
- **Good Loans vs Bad Loans** segmentation using donut charts
  - Good Loans: **86.2%** → 33.2K applications, $370.2M funded, $435.8M received
  - Bad Loans: **13.8%** → 5.3K applications, $65.5M funded, $37.3M received
- Loan Status breakdown table (Fully Paid / Current / Charged Off)
### 2. Overview
- Monthly trend of loan applications (Jan–Dec, growing from 2.3K → 4.3K)
- Loan term distribution: **73.2% on 36-month** vs 26.8% on 60-month terms
- Applications by employee length (10+ years = highest at 8.9K)
- Home ownership split: Rent, Mortgage, Own
- Top loan purposes: Debt Consolidation (18.2K), Credit Card (5K), Other (3.8K)
- Geographic distribution via Azure Maps visual
### 3. Details
- Row-level drill-through table with loan ID, purpose, home ownership, grade, sub-grade, issue date, funded amount, amount received, and interest rate
- Supports filtering by Purpose, Grade, and State
---
 
## 🔍 Key Findings
 
1. **Strong portfolio health** — 86.2% of loans are classified as "Good" (Fully Paid or Current)
2. **Debt consolidation dominates** — nearly half of all loan applications (18.2K of 38.6K) are for debt consolidation
3. **Experienced borrowers lead** — applicants with 10+ years of employment have the highest application volume (8.9K)
4. **36-month term is preferred** — 73.2% of borrowers opt for shorter 36-month loans over 60-month
5. **Consistent growth** — monthly applications grew steadily from 2.3K in January to 4.3K in December
6. **MoM acceleration** — Total Funded Amount grew 13% MoM; Total Amount Received grew 15.8% MoM
7. **Charged Off loans** (bad debt) account for 5,333 records with $6.55M funded and only $3.72M recovered
---
 
## 🛠️ Tools & Tech Stack
 
- **Power BI Desktop** — dashboard design, DAX measures, page navigation
- **SQL** — data extraction, transformation, and aggregation
- **Excel** — initial data cleaning and validation
- **Azure Maps** — geographic loan distribution visual
---
 
## 📐 DAX Measures Used
 
- MTD Funded Amount, MTD Amount Received
- MoM % change for all KPIs
- Good Loan % and Bad Loan % calculated columns
- Average Interest Rate and Average DTI by loan status
---
 
## 🗂️ Loan Status Definitions
 
| Status | Description |
|---|---|
| Fully Paid | Loan has been completely repaid |
| Current | Loan is active and repayments are on track |
| Charged Off | Loan declared as loss; borrower unlikely to repay |
 
---
 
## 📌 Filters Available
 
- **Purpose** — filter by loan purpose (debt consolidation, credit card, etc.)
- **Grade** — filter by credit grade (A through G)
- **State** — filter by borrower's US state
---
 
## 👤 Author
 
**Aman Robinson**  
Data Analyst | Ex-EY SAP Intern | MCA — Amity University  
📍 Noida, Delhi NCR  
🔗 [LinkedIn](https://www.linkedin.com/in/) <!-- add your LinkedIn URL -->
 
---
 
> *This project demonstrates end-to-end loan portfolio analysis using SQL for data preparation and Power BI for interactive visualization — relevant to BFSI/NBFC domain analytics.*
 
