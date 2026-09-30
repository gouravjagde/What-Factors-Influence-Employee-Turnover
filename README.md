# What Factors Influence Employee Turnover?

A Power BI dashboard analyzing **2M employee records** to find where turnover is concentrated and which factors are associated with it: department, job level, performance rating, and salary.

## Business Question

**Which employee groups are leaving most, and what patterns could help an organization focus its retention efforts?**

## Dashboard at a Glance

| Metric | Value |
|---|---|
| Total employees | 2.0M |
| Active employees | 1.8M |
| Turnover count | 206.0K |
| Turnover rate | 10.3% |
| Average employee age | 31.5 |
| Average experience | 6.3 years |

Turnover rate is turnover count divided by total employees (206.0K / 2.0M ≈ 10.3%).

## Key Findings

1. **Turnover is highest in HR and Operations.** HR (11.9%) and Operations (11.4%) lead, while IT is lowest at 9.1%. The spread is under 3 percentage points, so no department is a dramatic outlier.
2. **Junior employees make up most departures.** Of the 206.0K departures, 125.7K (about 61%) were Junior, followed by Mid (59.3K), Senior (15.3K) and Director (5.7K).
3. **Leavers earned less on average.** Resigned ($70.4K) and terminated ($73.9K) employees had lower average salaries than active employees ($92.3K), roughly 20–24% lower.
4. **Turnover is not limited to weak performers.** Employees rated Excellent account for 14% of departures (28.7K), and those rated Good account for the largest share at 47% (96.0K). Only 13% of leavers were rated Needs Improvement.
5. **Retired employees have the highest average salary** ($236.7K), which makes them a distinct group from voluntary and involuntary leavers.

## Limitations

- **Job level is shown as counts, not rates.** Junior staff likely make up the largest share of the workforce, so their high count does not by itself prove they leave at a higher rate. A turnover rate by job level is a natural next step.
- **These are associations, not causes.** The dashboard shows where turnover is concentrated, not why people leave.
- **Public dataset.** The data comes from Kaggle, so findings illustrate the analysis approach rather than any real organization.

## Suggested Next Steps

- Add turnover **rate** by job level, tenure band and age group.
- Break turnover into voluntary (resigned) vs. involuntary (terminated) by department.
- Analyze how tenure and salary relative to peers relate to attrition.

## Tools

- **Power BI Desktop** for data modeling, measures and visuals
- **Dataset:** [Kaggle](LINK_TO_DATASET) <!-- add the dataset link -->

## Repository Contents

```
├── README.md
└── images/
    └── dashboard.png
```

## Author

**Gourav Jagde**, Business Administration (Finance & Management Information Systems), Simon Fraser University
[LinkedIn](https://www.linkedin.com/in/gouravjagde)
