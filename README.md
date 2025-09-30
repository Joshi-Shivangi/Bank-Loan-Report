# Bank Loan Report Dashboard

## Problem Statement
Financial institutions handle thousands of loan applications each month, making it crucial to track lending performance, repayments, and borrower risk. However, without a centralized reporting system, identifying trends, risk exposure, and portfolio health becomes difficult.

To solve this challenge, a **Bank Loan Report Dashboard** was developed using **SQL and Power BI** to provide a unified, data-driven overview of loan activities. This dashboard enables stakeholders to monitor **loan KPIs**, assess **Good vs Bad Loans**, and make **strategic lending decisions** based on real-time insights.


---

## Objective
The objective of this project is to design a **comprehensive and interactive Power BI dashboard** that:
- Monitors **loan portfolio performance**
- Evaluates **repayment trends**
- Compares **Good vs Bad Loans**
- Tracks **key financial KPIs (MTD & MoM)**
- Provides **detailed insights** across borrower profiles, regions, and loan purposes

The solution helps stakeholders visualize trends, analyze borrower behavior, and make data-backed strategic lending decisions.

---

## Project Description
This end-to-end solution integrates SQL for data extraction, cleaning, and aggregation, and Power BI for visualization and storytelling.
SQL queries were first used for performing key calculations, and later during Power BI reporting, all values were cross-verified with SQL results to ensure accuracy.

1. **Summary Dashboard** – High-level KPIs, Good vs Bad Loan analysis, and Loan Status Grid.  
2. **Overview Dashboard** – Trend analysis by month, region, purpose, and borrower characteristics.  
3. **Details Dashboard** – A comprehensive, tabular view providing all essential loan data for quick reference and analysis.

The dashboard empowers users to understand **portfolio performance**, **loan risk exposure**, and **financial health** through real-time visual analytics.

---

## Key Performance Indicators (KPIs)

### 1. **Total Loan Applications**
- Displays total applications received in a given period.  
- Includes **Month-to-Date (MTD)** and **Month-over-Month (MoM)** comparison.

### 2. **Total Funded Amount**
- Shows total disbursed loan amount.  
- Tracks **MTD Funded Amount** and **MoM % change**.

### 3. **Total Amount Received**
- Reflects total repayments collected from borrowers.  
- Includes **MTD Amount Received** and **MoM trend**.

### 4. **Average Interest Rate**
- Monitors the **average lending rate** across all loans.  
- Compares **MTD** and **MoM variations** to track changes in lending cost.

### 5. **Average Debt-to-Income (DTI) Ratio**
- Measures borrower’s repayment capacity.  
- Evaluates **MTD** and **MoM trends** to gauge borrower financial health.

---

## Good Loan KPIs
- **Good Loan Application Percentage**  
- **Good Loan Applications**  
- **Good Loan Funded Amount**  
- **Good Loan Total Received Amount**

+ Indicates loans performing well with regular repayments.

---

## Bad Loan KPIs
- **Bad Loan Application Percentage**  
- **Bad Loan Applications**  
- **Bad Loan Funded Amount**  
- **Bad Loan Total Received Amount**

+ Highlights high-risk loans and defaults for improved risk management.

---

## Loan Status Grid View
A tabular summary categorized by **Loan Status** (e.g., Fully Paid, Current, Charged Off) featuring:
- Total Loan Applications  
- Total Funded Amount  
- Total Amount Received  
- MTD Funded Amount  
- MTD Amount Received  
- Average Interest Rate  
- Average DTI  

+ Enables granular analysis of loan health and repayment progress.

---

## Charts & Visuals (Overview Dashboard)

| Chart Type | Purpose |
|-------------|----------|
| **Line Chart – Monthly Trends by Issue Date** | Identifies seasonality and growth trends in loan applications. |
| **Filled Map – Regional Analysis by State** | Visualizes loan activity across regions to assess state-wise performance. |
| **Donut Chart – Loan Term Analysis** | Compares distribution across different loan tenures (e.g., 36 vs 60 months). |
| **Bar Chart – Employee Length Analysis** | Shows how employment stability impacts loan applications. |
| **Bar Chart – Loan Purpose Breakdown** | Highlights top purposes for borrowing (debt consolidation, credit card, etc.). |
| **Tree Map – Home Ownership Analysis** | Displays how home ownership (rent/mortgage/own) influences loan distribution. |

Each visualization tracks **Total Loan Applications**, **Total Funded Amount**, and **Total Amount Received** for better decision-making.

---

## Details Dashboard
The **Details Dashboard** acts as a **comprehensive data explorer**, allowing users to:
- Access detailed loan-level metrics  
- View borrower profiles  
- Analyze loan performance  
- Filter by grade, purpose, and region  

### Objective of Details Dashboard:
To provide a **user-friendly, consolidated interface** that serves as a **one-stop solution** for accessing detailed loan information and portfolio insights.

---

## Key Insights 
- Steady Growth: Loan applications increased from 2.3K in January to 4.3K in December, reflecting consistent demand over the year.
- Positive Cash Flow: Total Amount Received ($473.1M) exceeds Total Funded Amount ($435.8M), indicating healthy repayment trends and strong portfolio performance.
- Good Loans: 86.2% of loans are performing well with regular repayments, showcasing strong borrower credibility.
- Bad Loans: 13.8% of loans show repayment risk, highlighting the need for targeted risk mitigation strategies.
- Home Ownership Mix: The portfolio is well balanced with 18.4K renters and 17.2K mortgage holders, suggesting a diverse customer base.
- Top Loan Purpose: Debt Consolidation (18K applications) dominates lending activity, followed by Credit Card payoff, indicating a focus on refinancing and debt management.
- Income Insights: Higher approval and performance rates are observed among customers earning above $50K annually, reflecting stable repayment capacity.
- Verification Factor: Applicants with verified income show lower default rates, emphasizing the importance of document validation in loan approvals.
- Credit Grade Influence: The majority of good loans belong to Grade B and C, while Grades E to G show higher risk and default tendencies.

---

## Conclusion
The **Bank Loan Report Dashboard** provides a powerful, interactive solution for tracking loan performance, assessing borrower risk, and improving credit decisions. By visualizing **KPIs, trends, and borrower segments**, stakeholders gain clarity into portfolio health and can take proactive measures for growth and risk mitigation.

---

## Tools & Technologies Used
- **Power BI** – Data visualization & dashboard design  
- **Power Query** – Data transformation & cleaning  
- **DAX** – Creation of calculated measures (MTD, MoM, KPIs)  
- **Excel / CSV** – Data source  
- **Visualization Techniques:** KPI cards, Donut charts, Line charts, Bar charts, Tree maps, and Tables  

---

## Key Learnings
- Built an **end-to-end financial analytics dashboard** in Power BI  
- Applied **MTD & MoM analysis using DAX**  
- Leveraged **interactive slicers** for filtering by Purpose, Grade, and State  
- Enhanced **business storytelling** through visual design and data-driven insights  

---

*Developed to demonstrate integration of SQL and Power BI for financial analytics, KPI tracking, and business intelligence.*





