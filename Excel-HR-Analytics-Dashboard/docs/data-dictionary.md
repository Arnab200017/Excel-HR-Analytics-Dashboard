# 📖 Data Dictionary

Source sheet: **Dataset** in `dashboard/HR_Analytics_Dashboard.xlsx` (also exported as `data/hr_dataset.csv`).
**1,470 rows × 28 columns** — one row per employee.

| Column | Meaning |
|---|---|
| `ID_employe` | Unique employee ID |
| `Age` | Employee age |
| `Attrition` | `Yes` = employee left the company, `No` = still working |
| `BusinessTravel` | How often the employee travels for work |
| `Department` | Sales, Research & Development, or Human Resources |
| `Education` | Below College, College, Bachelor, Master, Doctor |
| `EnvironmentSatisfaction` | Satisfaction with the work environment (Low → Very High) |
| `Gender` | Female / Male |
| `JobInvolvement` | How involved the employee is in the job |
| `Job Role` | Specific role (e.g., Sales Executive, Research Scientist) |
| `JobSatisfaction` | Satisfaction with the job (Low → Very High) |
| `PerformanceRating` | Performance rating |
| `WorkLifeBalance` | Bad, Good, Better, Best |
| `MaritalStatus` | Single / Married / Divorced |
| `StockOption` | Stock option level: None, Low, Mid, High |
| `OverTime` | Does the employee work overtime? Yes / No |
| `PercentSalaryHike` | Last salary increase (%) |
| `NumCompaniesWorked` | Number of previous companies |
| `TotalWorkingYears` | Total years of work experience |
| `YearsSinceLastPromotion` | Years since last promotion |
| `YearsWithCurrManager` | Years with the current manager |
| `DistanceFromHome` | Distance from home to office |
| `HourlyRate` / `DailyRate` / `MonthlyRate` | Pay rates |
| `Salary` | Monthly salary |
| `DateStart` | Joining date |
| `EmploymentType` | Full-time or Contractor |

## Helper columns added in the Excel workbook
The sheet **Dataset COPY** adds `YEAR OF JOINNING`, `Duration` (tenure), `Quarters` and `Years` (experience bands such as 0-7, 8-15 …) so the pivot tables can group the data.
