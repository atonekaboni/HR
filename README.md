# HR Employee Attrition Analysis
This project analyzes employee attrition data using **Power BI** with comprehensive dashboards and workforce insights for strategic human resources management.

## Project Overview
This project analyzes employee attrition patterns across 1,470 employees to identify retention risks and workforce trends. The analysis examines demographic factors, job satisfaction levels, salary distributions, and tenure patterns that influence employee turnover. Strategic insights support HR decision-making for talent retention, compensation planning, and department-level workforce optimization.

The dashboard provides actionable intelligence for HR managers balancing employee satisfaction with organizational stability. By analyzing historical patterns across departments, education levels, and career stages, this investigation reveals evidence-based findings that inform retention strategies and reduce costly turnover.

## Database Architecture
The HR database connects employee demographics to job roles, departments, and education levels through a normalized structure. This design enables multi-dimensional analysis across attrition patterns, compensation, and workforce characteristics.

<p align="center"><img width="700" height="auto" alt="ERD" src="https://github.com/user-attachments/assets/9a1e27b5-1aed-4c36-a24d-342a3a2d58c8" />

## Repository Structure
This repository contains the complete Human Resource Analytics Project with the following components:
- **[`HR Analytics Dashboard.pbix`](https://github.com/atonekaboni/HR/blob/main/HR%20Analytics%20Dashboard.pbix)** - Interactive Power BI dashboard with DAX measures and filtering capabilities
- **[`dataset.xlsx`](https://github.com/atonekaboni/HR/blob/main/HR_Data.xlsx)** - Complete employee dataset with demographics, job roles, and attrition records
- **[`README.md`](README.md)** - project documentation with findings and recommendations


##  Executive Summary
HR analytics reveals a 16% attrition rate (238 departures from 1,470 employees) with significant disparities across departments and demographics. Research & Development shows highest attrition (133 employees), while early-tenure employees (0-2 years) demonstrate peak turnover risk. Male attrition (151) significantly exceeds female (87), and Life Sciences graduates account for 37% of all departures. Analysis identifies actionable opportunities for targeted retention programs and compensation adjustments.
<br>

<p align="center"><img src="https://github.com/user-attachments/assets/84a9d90e-8a12-4e89-addb-1e512668d6a9" alt="HR Analytics Power BI Dashboard" width="700"></p>

## Key Findings
### Department Attrition Crisis

Research & Development shows 133 attritions representing 56% of total company departures despite being one of three main departments. Sales follows with significant attrition contributions, while HR maintains relatively stable retention patterns. This concentration in R&D suggests systemic issues in career advancement, project ownership, or compensation competitiveness requiring immediate intervention.

### Education and Career Alignment

Life Sciences graduates account for 37% of all attritions (89 employees), indicating potential misalignment between educational background and role expectations. Medical degree holders represent 27% of departures (63 employees), followed by Marketing graduates at 15% (35 employees). These patterns suggest field-specific retention challenges where specialized education may not translate to satisfying career paths within current organizational structure.

### Early Career Vulnerability

Employees with 0-2 years tenure demonstrate highest attrition rates, with peak departures occurring in year 1. This critical period represents the most vulnerable phase for retention as new hires evaluate cultural fit and career prospects. Analysis shows inverse relationship between tenure and turnover risk, with employees beyond 5 years exhibiting significantly lower departure probability, highlighting the importance of effective onboarding and early-career support.

### Compensation Structure Impact

Employees earning up to $5k monthly show disproportionately high attrition rates. Retention improves in the $5k-10k bracket, with best results at $10k+ salary range. The average monthly income of $6.5k ($65k annually) sits in high-risk zone, suggesting that targeted compensation adjustments for high performers in lower brackets could significantly impact overall retention metrics.

### Gender Attrition Disparity

Male employees account for 151 attritions (63.4%) compared to 87 female departures (36.6%), representing 73% higher male turnover rate. Laboratory Technicians, Sales Executives, and Research Scientists show highest absolute attrition numbers across roles, suggesting both gender-specific and role-specific factors influencing departure decisions.

## Recommendations

Target early-career employees with structured onboarding programs and 90-day check-ins during first two years. Deploy immediate retention strategy for R&D department focusing on career advancement and competitive benchmarking. Conduct salary market analysis for sub-$5k employees and implement targeted raises to bridge gap toward $10k retention threshold. Create specialized development programs for Life Sciences graduates addressing the 37% attrition rate. Investigate male attrition through exit interviews to identify root causes of 73% disparity.

## Technical Implementation

Power BI Desktop with DAX-based calculations for attrition rates, tenure analysis, and demographic segmentation. Interactive filtering by department and role with dynamic KPI cards and multi-dimensional visualizations. Excel source data processed through Power Query for cleansing and relationship modeling across 1,470 employees with 38 data attributes.

## Limitations

Dataset represents single snapshot without longitudinal tracking. No exit interview data limits causation analysis beyond correlations. External market factors and competitor actions not included. Satisfaction metrics use numeric scales without qualitative context.

## Contact

<p align="center">
  <a href="https://www.linkedin.com/in/tonekaboni/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  &nbsp;&nbsp;
  <a href="https://github.com/atonekaboni/" target="_blank"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  &nbsp;&nbsp;
  <a href="https://atonekaboni.github.io/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-D14836?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
</p>
