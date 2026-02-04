## 📊 Approval to Non-Performing Loan (NPL) Trend Analysis

## 📌 Project Overview
This project analyzes the **time taken for approved loans to transition into Non-Performing Loan (NPL) status**, with emphasis on **early default behavior, employer (RIM Class) risk exposure, and portfolio-level deterioration trends**.

The analysis supports **credit risk management, portfolio monitoring, and strategic decision-making** by moving beyond traditional NPL ratios to focus on **time-to-default dynamics**.

The solution was developed using **Excel for feature engineering** and **Power BI for data modeling, DAX calculations, and visualization**.

---

## 🎯 Business Problem
While NPL ratios indicate the proportion of bad loans, they do not explain **how quickly loans become non-performing after approval**. Rapid default increases:
- Credit losses
- Capital pressure
- Portfolio instability

This project addresses the following key questions:
- How long does it take for loans to become NPLs after approval?
- What proportion of loans default early?
- Which employer groups default faster?
- How has default behavior changed over time?

---

## 🧾 Dataset Description
The dataset consists exclusively of **non-performing loan accounts**, including both **active NPLs and non-accrual loans**.

### Key Fields
| Column | Description |
|------|------------|
| LN Account | Loan account identifier |
| DP Account | Linked deposit account |
| Contract Date | Loan approval / disbursement date |
| Disbursed AMT | Original loan amount |
| Balance | Outstanding balance |
| Payoff | Expected payoff amount |
| Rate | Interest rate |
| Status | Active or Non-accrual |
| RIM Class | Employer / customer classification |
| CRNCY | Currency |
| Days in Arrears | Number of overdue days |

---

## 🛠 Data Preparation & Feature Engineering

### Assumption
A loan is classified as **Non-Performing at 90 days in arrears**.


**Result:**  
**5%**

---

## 📊 Analytical Views

### Average Days to NPL by Year
- Tracks changes in default speed over time
- Highlights periods of rising credit stress

Recent years show a **declining time-to-NPL**, indicating faster deterioration.

---

### Average Days to NPL by RIM Class
- Identifies employer groups associated with faster defaults
- Supports risk-based pricing and exposure management

Several Employer Classes default **significantly faster than the portfolio average**.

---

### Payoff Concentration by Employer class
- Highlights concentration of NPL exposure
- Identifies high-risk employer segments contributing disproportionate balances

---

## 📈 Key Insights
- Early default levels remain relatively low (5 accounts), suggesting stable underwriting quality.
- Overall defaults are occurring **faster**, indicating growing borrower stress.
- Employer-based segmentation reveals **structural risk concentrations**.
- Time-based default analysis provides stronger risk signals than static NPL ratios.

---

## 🧰 Tools & Technologies
- **Powerbi** – Feature engineering and date calculations
- **Power BI** – Data modeling, DAX measures, dashboards
- **DAX** – KPI computation
- **GitHub** – Documentation and version control

## 🏁 Conclusion
This project demonstrates how **approval-to-default analytics** provide deeper and more actionable insight than traditional NPL metrics. By focusing on **time-to-NPL**, financial institutions can strengthen early warning systems, improve credit policy, and better manage portfolio risk.

See dashboard below:





