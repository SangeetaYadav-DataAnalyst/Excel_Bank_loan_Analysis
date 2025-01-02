# Bank Loan protfolio - Performance Overview

**Project overview**
The Bank Loan Analysis Project evaluates loan performance using two dynamic dashboards: Summary and Overview. The Summary Dashboard provides a high-level view of 38.6K loan applications, with a 6.9% MoM growth. It highlights the dominance of good loans (86.18%), with $370.2M funded and $435.8M repaid, versus bad loans (13.82%), with $65.5M funded and $37.3M repaid. Loan statuses like fully paid, charged off, and current are analyzed, alongside comparisons of interest rates and debt-to-income (DTI) metrics, showing lower risks for good loans.

**Tech Stacks:**
- Excel for data preparation, analysis & Chart generation

**Approach to Creating Loan Portfolio Summary Dashboard:**
*4-Step Methodology*

- *Data Preparation:* Collected, cleaned, and formatted loan data, organizing into separate sheets (loan data, state-wise, loan status).
- *Pivot Table Configurations:* Built pivot tables for loan summary, state-wise loans, loan status and characteristics, applying date filters and calculating key metrics.
- *Dashboard Creation:* Designed interactive dashboard with visualizations (bar, pie, line, heatmap charts), filters and slicers, highlighting KPIs.
- *Analysis & Visualization:* Utilized conditional formatting, dynamic charts and clear labels to illuminate trends, risks and actionable insights.

**Project Outcome:**
- Interactive dashboard
- Data-driven insights
- Enhanced lending decision-making
- Identifying trends and risks
- Data visualization
  
**Overall Report**
The Overview Dashboard focuses on trends, showing steady growth from 2.3K applications in January to 4.3K in December. It provides insights into state-wise application densities and loan purposes, revealing that 72.8% of loans are 36-month terms, primarily used for debt consolidation and credit card repayment. This project delivers actionable insights for better loan management and risk mitigation.
 
 The Summary Dashboard focuses on high-level insights into loan portfolio performance:
 ![Summary_dashboard](https://github.com/user-attachments/assets/86df8e5f-bb85-497a-a71d-4326ad512f4f)
 
- Key Performance Indicators (KPIs):
  - *Total Loan Applications:* Tracks overall applications, Month-to-Date (MTD) applications, and Month-over-Month (MoM) growth.
  - *Total Funded Amount:* Highlights total disbursed funds, MTD funding, and MoM trends.
  - *Total Amount Received:* Monitors borrower repayments and cash flow with MTD and MoM analysis.
  - *Average Interest Rate:* Assesses portfolio cost through MTD and MoM variations.
  - *Average Debt-to-Income (DTI):* Gauges borrowers' financial health, tracked for MTD and MoM changes.

- Good Loans vs. Bad Loans: Good loans are defined by statuses such as "Fully Paid" and "Current," while bad loans are categorized as "Charged Off."
  - *Good Loan Metrics:* Applications, funded amounts, and total repayments.
  - *Bad Loan Metrics:* Applications, disbursed funds, and repayments received.
  
- These KPIs help evaluate loan quality and identify areas requiring strategy adjustments.
  - *Loan Status Grid View:* A tabular representation summarizes total applications, funded amounts, repayments, interest rates, and DTI across different loan statuses.


The Overview Dashboard provides dynamic visualizations to identify trends and distribution patterns:
![Overview_dashboard](https://github.com/user-attachments/assets/1d360c47-8b21-4124-b146-511f922c75e4)

- *Monthly Trends by Issue Date (Line Chart):* Tracks total applications, funded amounts, and repayments month-over-month to uncover seasonality and long-term trends.
- *Regional Analysis by State (Filled Map):* Displays loan activity by state, revealing geographic lending hotspots and disparities.
- *Loan Term Analysis (Donut Chart):* Breaks down loan metrics by term lengths (e.g., 36 and 60 months), offering insights into term preferences.
- *Employment Length Analysis (Bar Chart):* Explores lending metrics by borrower employment duration, linking employment history with loan performance.
- *Loan Purpose Breakdown (Bar Chart):* Categorizes loans by purpose (e.g., debt consolidation, credit card repayment), highlighting key borrowing motivations.

