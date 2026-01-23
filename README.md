# Financial Dashboard – Case Study

## Objective
The objective of this project was to build an interactive, monthly-level financial dashboard in Power BI to help stakeholders monitor the company’s overall financial performance. The dashboard focuses on key financial KPIs, trends, budget tracking, cash flow, and working capital, enabling data-driven decision-making.

---

## Data Overview
The dataset contains monthly financial and operational data, including:
- Profit & Loss metrics such as Revenue, COGS, Gross Profit, Operating Expenses, and EBITDA  
- Cash flow information including Cash Inflows, Cash Outflows, and Net Cash  
- Budgeted versus actual revenue figures  
- Product-level revenue data  
- Receivables aging information  

A separate Date table was created to support accurate filtering by month, quarter, and year and to ensure consistency across all visuals.

---

## Key KPIs and Calculations
The dashboard highlights the following key performance indicators:
- **Total Revenue**: Sum of actual revenue for the selected period  
- **Net Cash**: Difference between total cash inflows and cash outflows  
- **Gross Margin %**: Gross Profit divided by Total Revenue  
- **EBITDA %**: EBITDA divided by Total Revenue  

All KPIs were created using DAX measures to ensure correct aggregation and responsiveness to filters.

---

## Key Insights from the Dashboard
- **Revenue, Gross Profit & EBITDA Trend** shows how revenue growth translates into profitability over time and helps identify fluctuations in margins.  
- **Budget vs Actual Revenue** compares planned revenue against actual performance on a monthly basis, making it easier to identify periods of over- or under-performance.  
- **Product Performance Analysis** highlights revenue contribution by product or service, clearly identifying top-performing and lower-performing offerings.  
- **Cash Flow Analysis** displays monthly cash inflows, cash outflows, and net cash, helping assess liquidity trends and cash sustainability.  
- **Receivables Aging Analysis** groups outstanding receivables into aging buckets to highlight potential collection risks and working capital concerns.

---

## Assumptions and Limitations
- Budget values are assumed to be planned at a monthly level.  
- Receivables aging uses revenue as a proxy due to the absence of invoice-level receivable amounts.  
- The dashboard is designed for high-level financial monitoring and does not replace detailed accounting or statutory reports.

---

## Conclusion
This financial dashboard provides a consolidated and interactive view of the company’s financial health. It enables stakeholders to track performance, compare actuals against budgets, monitor cash flow, and identify potential risks, supporting informed and timely business decisions.
