\## Dashboard



\# Employee Compensation \& Pay Adjustment Analysis



\## Project Overview



This project demonstrates an Excel-based compensation analysis using a synthetic workforce dataset of 500 employees.



The analysis evaluates employee salaries against external market benchmarks, identifies compensation gaps, examines market positioning across departments, and models the financial impact of alternative pay-adjustment scenarios.



The project was designed to demonstrate practical skills in compensation analysis, workforce data analysis, market benchmarking, pay-adjustment costing, and business reporting using Microsoft Excel.



> \\\*\\\*Note:\\\*\\\* All employee records and market benchmarks used in this project are synthetic and were created solely for portfolio demonstration purposes.



\---



\## Business Questions



The analysis addresses the following questions:



1\. How do current employee salaries compare with market median salaries?

2\. Which departments have the largest compensation gaps?

3\. How many employees are below established market-position thresholds?

4\. Which departments have the greatest concentration of below-market employees?

5\. What would a 3% across-the-board salary increase cost?

6\. What would it cost to bring employees below 90% of market up to the 90% threshold?

7\. What would it cost to bring employees below 95% of market up to the 95% threshold?

8\. Which pay-adjustment scenario provides the best balance between market alignment and cost?



\---



\## Tools \& Excel Skills



\- Microsoft Excel

\- XLOOKUP

\- IF / IFS

\- COUNTIF

\- SUM and AVERAGE

\- PivotTables

\- PivotCharts

\- Conditional Formatting

\- Excel Tables

\- Market Gap Analysis

\- Scenario Analysis

\- Compensation Costing

\- Dashboard Development



Python was used only to generate the synthetic raw employee and market-benchmark datasets. The compensation analysis, scenario modelling, PivotTables, charts, and dashboard were developed in Microsoft Excel.



\---



\## Dataset



The project uses a synthetic dataset containing \*\*500 fictional employees\*\* across six departments:



\- Administration

\- Finance

\- Human Resources

\- Information Technology

\- Operations

\- Policy \& Research



Employee data includes job title, job level, years of service, current salary, performance rating, and related workforce information.



A separate market-benchmark dataset provides market median salaries by job title.



\---



\## Compensation Analysis



Market position was calculated as:



\*\*Market Position = Current Salary / Market Median\*\*



For analytical purposes, employees were grouped into four categories:



| Market Position | Classification |

|---|---|

| Below 85% | Significantly Below Market |

| 85% to below 95% | Below Market |

| 95% to 105% | Around Market |

| Above 105% | Above Market |



These thresholds are assumptions created for this portfolio project and do not represent the compensation policies of any actual organization.



\---



\## Key Findings



\- The workforce consists of \*\*500 employees\*\* with a current annual payroll of approximately \*\*$32.49 million\*\*.

\- Average workforce market position is \*\*95.6%\*\*.

\- \*\*45.6% of employees\*\* are positioned below 95% of market.

\- \*\*15.8% of employees\*\* are significantly below market at less than 85%.

\- Administration has the lowest average market position at \*\*94.8%\*\* and the highest proportion of employees significantly below market at \*\*20.7%\*\*.

\- Information Technology has the largest average dollar market gap at approximately \*\*-$3,448\*\*.

\- Operations has the strongest average market position at \*\*97.7%\*\*.



\---



\## Pay Adjustment Scenario Analysis



Three compensation-adjustment scenarios were evaluated:



| Scenario | Employees Affected | Total Cost | Cost as % of Payroll |

|---|---:|---:|---:|

| 3% Across-the-Board Increase | 500 | $974,727 | 3.00% |

| Target Employees Below 90% of Market | 140 | $634,200 | 1.95% |

| Target Employees Below 95% of Market | 228 | $1,253,700 | 3.86% |



The targeted 90% market scenario has the lowest overall financial impact, requiring approximately \*\*$634,200\*\*, or \*\*1.95% of current payroll\*\*, while directing adjustments toward 140 employees currently positioned below 90% of the market median.



\---



\## Recommendation



Based on the simulated analysis, the \*\*90% market-target scenario\*\* provides the most cost-controlled immediate approach.



It prioritizes employees with larger relative market gaps while requiring a smaller payroll investment than either the 3% across-the-board increase or the 95% market-target scenario.



A broader move toward 95% of market could be evaluated as a longer-term option, subject to organizational priorities, compensation policy, internal equity considerations, and available budget.



\---



\## Dashboard



!\[Employee Compensation Dashboard](images/compensation\_dashboard.png)



The Excel dashboard summarizes:



\- Workforce size and current payroll

\- Average market position

\- Percentage of employees below 95% of market

\- Compensation-status distribution

\- Average market position by department

\- Pay-adjustment scenario costs

\- Adjustment costs by department

\- Key findings and recommendation



\---

## Excel Workbook

The Excel workbook contains the complete compensation analysis, including:

- Employee and market benchmark data
- Salary and market-position calculations
- Compensation status classification
- Department-level PivotTable analysis
- Pay-adjustment scenario modelling and costing
- Department-level adjustment analysis
- Executive dashboard
- Key findings and recommendations

The workbook is available in the `excel` folder:

`excel/Employee_Compensation_Analysis.xlsx`

\## Project Structure



```text

Employee-Compensation-Excel-Analysis/

│

├── data/

│   ├── employee\\\_data.csv

│   └── market\\\_benchmarks.csv

│

├── excel/

│   └── Employee\\\_Compensation\\\_Analysis.xlsx

│

├── images/

│   └── compensation\\\_dashboard.png

│

├── 01\\\_generate\\\_data.ipynb

├── README.md

└── .gitignore

```



\---



\## Methodology \& Assumptions



\- Employee records and market benchmarks are \*\*synthetic\*\* and were created solely for portfolio demonstration purposes.

\- Market-position thresholds are analytical assumptions developed specifically for this project.

\- Market Position = Current Salary ÷ Market Median.

\- Scenario 1 applies a 3% salary increase to all employees.

\- Scenario 2 brings employees below 90% of market to the 90% threshold.

\- Scenario 3 brings employees below 95% of market to the 95% threshold.

\- The analysis demonstrates Excel-based compensation analysis and costing techniques and does not represent compensation recommendations for an actual organization.



\---



\## Skills Demonstrated



This project demonstrates practical experience with:



\- Compensation and workforce data analysis

\- External market benchmarking

\- Salary gap and market-position analysis

\- Pay-adjustment costing

\- Scenario modelling

\- Data validation and quality checking

\- PivotTable analysis

\- Excel dashboard development

\- Translating analytical findings into business recommendations



!\[Employee Compensation Dashboard](images/compensation\_dashboard.png)

