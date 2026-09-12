# Day 20: HR Attrition Dashboard

## Objective
Transform raw HR data into actionable management insights by building an interactive Power BI dashboard that analyzes employee attrition across departments, roles, and tenure.

## Technical Implementation
* **Tool Stack:** Power BI & DAX.
* **Metric Calculation:** Shifted analytical focus from raw turnover counts to **Attrition Rates**. Engineered a custom DAX Measure (`DIVIDE(CALCULATE(COUNT), COUNT)`) to ensure accurate percentage-based comparative analysis across varying department sizes.
* **Data Governance:** Ensured strict HR compliance by visualizing aggregated business unit metrics rather than individual personal information.

## Top 5 Management Insights
1. **Critical Flight Risk (Tenure):** The highest attrition rates consistently occur within the earliest years of employment, pointing to a severe issue with onboarding or initial job expectations.
2. **Departmental Warning:** The Sales department experiences the highest overall attrition rate in the company.
3. **High-Risk Role:** Drilling down into departments, the **Sales Representative** role is bleeding talent at an unsustainable rate compared to all other positions.
4. **Stability Milestone:** Employees who cross the initial multi-year hurdle show a drop in attrition, proving that long-term retention is highly probable if early-stage turnover can be mitigated.
5. **Business Recommendation:** HR should heavily investigate the first 90 days of the Sales Representative onboarding pipeline, potentially implementing mentorship programs to plug the highest leak in the talent funnel.
