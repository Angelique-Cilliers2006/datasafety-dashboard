# DataSafety Statistical Dashboard

An interactive Excel dashboard analysing workplace safety incidents across nine manufacturing plants, built as a group assignment for **STA181 (Statistics)** at Belgium Campus iTversity.

## The data

The `SafetyData` sheet holds **514 incident records** from January 2020 to June 2022. Each record includes the date, plant, department, shift, incident type, injury location, report type (Near Miss, First Aid, Medical Claim, Lost Time), days lost, incident cost, and the employee's gender and age group.

## What the dashboard shows

The `Dashboard` sheet is organised into five sections:

1. **Overall safety overview**: headline KPIs for the whole dataset
2. **Demographics**: incidents by gender and age group
3. **Operational risks**: where incidents are concentrated, by plant, department and shift, including a Plant × Department risk matrix
4. **Time, severity and cost**: trends over time, average days lost per incident type, and cost
5. **Findings**: a written summary of the results

### Interactive filters
The yellow cells let you filter by **plant, department and shift**. The incident count and the top department, shift and plant update automatically. This is built with Excel formulas (`COUNTIFS` with dropdown data validation), so no macros are needed.

## Key findings

- **Shipping** recorded the most incidents (68).
- **Maintenance** had the highest incident cost of any department ($98,442).
- **Florida** was the highest-cost plant ($102,964).
- **Burns** were the most frequent incident type (65), but **equipment** incidents caused the most days lost (66.5).
- The **night shift** lost the most days (161.5), despite a similar number of incidents to the day shift. Night-shift incidents tend to be more severe.
- 2022 only covers January to June, so its totals should not be compared directly with 2020 or 2021.

## Tools and techniques

Microsoft Excel · descriptive statistics · `COUNTIFS` / `MAX` lookup formulas · data validation dropdowns · bar charts · KPI design

## Files

| File | Description |
|---|---|
| `STA Assignment.xlsx` | The workbook: raw data (`SafetyData`) and the dashboard (`Dashboard`) |

To use it, download the workbook, open it in Excel and go to the `Dashboard` sheet.

## Author

**Angelique Cilliers** · BComp student, Belgium Campus iTversity
[LinkedIn](https://www.linkedin.com/in/angelique-cilliers-678577345/) · cilliersangelique7@gmail.com
