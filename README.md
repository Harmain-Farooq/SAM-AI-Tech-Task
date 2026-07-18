# SAM AI Tech Task Submission

This repository contains my submissions for the SAM AI technical assessment tasks, showcasing data analysis, visualization, and dashboard development workflows.

---

## 📁 Repository Structure

* **[Task 1: Customer Churn Dashboard](./Task-1-Customer-Churn-Dashboard)** - Power BI dashboard focused on tracking and predicting customer retention and risk factors.
* **[Task 2: HR Analytics Dashboard](./Task-2-HR-Analytics-Dashboard)** - Power BI dashboard designed to monitor employee attrition, salary distributions, performance, and hiring trends.
* **[Task 3: Financial Health Dashboard](./Task-3-Financial-Health-Dashboard)** - Power BI dashboard built to evaluate organizational corporate performance, profitability margins, liquidity, and revenue forecasting.

---

## 📊 Task 1: Customer Churn Dashboard

A multi-page Power BI dashboard designed to monitor high-level retention metrics and analyze predictive customer risk profiles. The dashboard provides actionable insights into service preferences, billing styles, and demographic behaviors driving customer attrition.

### 📈 Executive KPIs
* **Total Customers:** 1K
* **Churned Customers:** 883
* **Overall Churn Rate:** 88.30%
* **Average Tenure:** 18.97 months
* **Lost Monthly Revenue:** $67.07K

### 🔍 Key Insights & Features
* **Executive Churn Overview (Page 1):** 
    * Tracks churn variance by Internet Service types: Fiber Optic (30.92%), DSL (31.62%), and None (37.46%).
    * Visualizes volume breakdowns by gender (470 Female vs. 413 Male churned customers) alongside lifespan trends up to 122+ months.
* **Customer Risk Profile & Insights (Page 2):**
    * Highlights **Month-to-Month** contracts as the highest risk segment (511 customers, $38,789.60 in monthly charges, and a **55.00% Predicted Churn Probability**).
    * Pinpoints actual contract attrition where Month-to-Month hits 100%, Two-Year sits at 77%, and One-Year at 75.43%.

### 🛠️ Tech Stack
* Power BI Desktop | Power Query | DAX

---

## 👥 Task 2: Human Resource Analytics Dashboard

A comprehensive, 4-page HR Analytics dashboard designed to evaluate talent acquisition metrics, operational expenditures, employee performance, and organizational attrition trends.

### 📈 Dashboard Page Breakdown & Performance Insights

#### 1. Employee Attrition Analysis
*   **Core Metrics:** Total Employees (**3K**), Attrition Count (**1K**), and an Attrition Rate of **40.71%**.
*   **Departmental Breakdown:** Marketing has the highest attrition count (**494**), followed closely by HR (**478**), Engineering (**469**), Operations (**464**), Finance (**461**), and Sales (**434**).
*   **Job Satisfaction:** Tracks attrition volume against employee sentiment, indicating that even among "Highly Satisfied" employees, **307** individuals exited the organization, compared to **355** for "Satisfied".

#### 2. Salary and Department Insights
*   **Financial Metrics:** Total Monthly Salary (**209M**) with an Average Monthly Salary of **74.49K**.
*   **Salary Drivers:** Features a breakdown of monthly compensation by Role Level (Senior: **33.8%**, Mid: **33.56%**, Junior: **32.64%**).
*   **Performance vs. Pay:** A performance line graph maps monthly salary allocations against performance tiers (1 through 5), peaking prominently at rating **3**.

#### 3. Attendance / Performance Dashboard
*   **Operational Health:** Displays a **54.57%** Overall Attendance Rate alongside an Average Performance Rating of **2.96**.
*   **Absenteeism Analysis:** Identifies HR as the leading department for total absenteeism volume (**5.0K**), closely followed by Marketing (**4.9K**) and Engineering (**4.7K**).

#### 4. Hiring Trend Visualization
*   **Talent Acquisition:** Visualizes **3K** Total Hires, **2K** Net Headcount Growth, and an average workload metric of **49.84** Average Weekly Hours.
*   **Staffing Distribution:** Breaks down total employees by role seniority (Senior: **953**, Mid: **932**, Junior: **915**).
*   **Time-Series Tracking:** Employs a dual-axis area chart mapping historical spikes and drops for concurrent "Total Hires" and "Attrition Count" across month-by-month cycles.

### 🛠️ Tech Stack
*   **Business Intelligence:** Power BI Desktop
*   **Data Transformation:** Power Query
*   **Advanced Visualizations:** Sankey Charts, Tree Maps, Waterfall Charts, and Dual-Axis Trend Lines.
*   **Formulas & Metrics:** DAX for structured rolling averages, headcount tracking, and attendance percentage allocations.

---

## 💰 Task 3: Financial Health Dashboard

A comprehensive corporate finance dashboard designed to evaluate core liquidity positions, structural income statements, operational efficiency ratios, and variance between projected and actual revenue streams.

### 📈 Corporate Financial KPIs
* **Total Credit Sales:** $2.44M
* **Working Capital:** $7.00M
* **Net Burn Rate:** $890K
* **AR Days (Accounts Receivable Turnover):** 50.69 Days
* **Average Net Margin:** 28.68%

### 🔍 Key Insights & Features
* **Income Statement Matrix:** 
    * Consolidates performance tracking for the first half of 2026, summarizing **$3,045,000** in Total Revenue against **$1,228,400** in COGS, yielding a strong Gross Profit of **$1,816,600**. 
    * Factors in **$940,000** in Operating Expenses (OpEx) to close out H1 with a Net Income of **$876,600**.
* **Liquidity & Solvency Analysis:** Features a target gauge monitoring the **Quick Ratio**. The current standing sits at **1.99**, nearly perfectly aligned with the standard corporate health benchmark target of **2.00**.
* **Revenue vs. Forecast Variance:** Integrates a scatter plot quadrant mapping actual vs. forecasted revenue by fiscal quarters (e.g., Q1-2026 vs Q2-2026) to flag target variance.
* **Cash Flow Dynamics:** Utilizes a combined bar and trend visualization mapping Net Income against Net Cash Flow month-by-month (January to June), highlighting month-end cash flow peaks such as February ($0.14M) and May ($0.16M).

### 🛠️ Tech Stack
*   **Business Intelligence:** Power BI Desktop
*   **Data Modeling:** Power Query, Star Schema relationships, Date Tables
*   **Analysis Metrics:** DAX formulas evaluating financial margins, inventory liquidity ratios, and time-intelligence forecasting models.

---

## 📁 Files & Navigation
Each folder (`/Task-1-...`, `/Task-2-...`, and `/Task-3-...`) contains the corresponding `.pbix` dashboard file. Download and open them in Power BI Desktop to interact with the visual filters, date matrices, and custom dynamic slicers.

