# Utility Operations Dashboard

## Power BI & SQL Operations Analysis

A business-focused data analytics project analysing utility operational performance, workload, costs, SLA performance, customer satisfaction and engineer activity.

The project combines SQL analysis with an interactive Power BI dashboard to demonstrate how operational data can be transformed into useful business insights for decision-making.

---

## Project Overview

Utility organisations manage large volumes of operational jobs every day. Understanding workload, costs, completion performance, SLA performance and customer satisfaction is important for effective resource planning and service delivery.

This project was created to analyse utility operations data and answer practical business questions such as:

- How many jobs are being handled?
- What types of jobs generate the most workload?
- Which job types have the highest costs?
- How long do jobs take to complete?
- How is SLA performance?
- What is the customer satisfaction level?
- How is engineer workload distributed?
- What operational areas may require further attention?

---

## Project Objectives

The main objectives of this project were to:

1. Analyse operational job data using SQL.
2. Calculate key operational performance measures.
3. Identify patterns in workload, costs and job types.
4. Analyse SLA and customer performance.
5. Examine engineer workload and activity.
6. Build an interactive Power BI dashboard.
7. Present operational information in a clear format suitable for management decision-making.

---

## Tools & Technologies

- **SQL / MySQL**
- **Microsoft Power BI**
- **Microsoft Excel**
- **Data Cleaning**
- **Data Analysis**
- **Data Visualisation**
- **Business Intelligence**

---

## SQL Analysis

The SQL analysis was completed using a utility operations database containing the `UTILITY_JOBS` table.

The table includes fields such as:

- Job ID
- Date Raised
- Due Date
- Completion Date
- Region
- Area
- Engineer
- Job Type
- Priority
- Status
- SLA Target Hours
- Actual Hours
- SLA Met
- Customer Rating
- Cost
- Department
- Raised By
- Case Source

### SQL techniques demonstrated

The project includes practical examples of:

- `SELECT`
- `WHERE`
- `AND` / `OR`
- `IN`
- `BETWEEN`
- `LIKE`
- `IS NULL`
- `COUNT`
- `SUM`
- `AVG`
- `MIN`
- `MAX`
- `GROUP BY`
- `HAVING`
- `ORDER BY`
- `LIMIT`
- `CASE`

Examples include analysing job volumes, costs, average completion hours, customer ratings, priority levels, job types and engineer workload.

The complete SQL practice script is available in:

`Utility_SQL_Practice.sql`

---

## Power BI Dashboard

The Power BI report was developed to provide an interactive view of utility operational performance.

### Key KPIs

| KPI | Result |
|---|---:|
| Total Jobs | 5,000 |
| Total Cost | £3,199,387 |
| Average Actual Hours | 28.81 |

### Dashboard Analysis

The dashboard includes:

### Jobs by Job Type & Priority

Shows the volume of operational jobs across different job types and priority levels.

### Cost by Job Type

Shows how operational costs are distributed across different job types.

### Jobs by Status

Provides a view of completed, in-progress and open jobs.

### SLA Performance

Shows the proportion of jobs that met SLA, did not meet SLA, or are pending.

### Customer Rating

Displays average customer rating across job types.

### Engineer Performance

Provides a breakdown of engineer activity across completed, in-progress and open jobs.

### Engineer Filter

An interactive slicer allows users to select individual engineers and analyse their workload.

---

## Key Dashboard Findings

The dashboard provides an overview of:

- Overall operational workload.
- Total operational expenditure.
- Average job completion time.
- Job type and priority distribution.
- Completed, open and in-progress work.
- SLA performance.
- Customer satisfaction.
- Engineer workload.

The dashboard can therefore be used as a management reporting tool to identify workload patterns, monitor service performance and support operational planning.

---

## Business Recommendations

Based on the analysis, organisations could use this type of dashboard to:

- Monitor operational workload regularly.
- Identify areas with higher job volumes.
- Review job types associated with higher operational costs.
- Monitor SLA performance and investigate areas of lower compliance.
- Review engineer workload to support resource planning.
- Track customer satisfaction alongside operational performance.
- Use data-driven reporting to support operational decision-making.

---

## Project Structure

```text
Utility-Operations-Dashboard
│
├── README.md
│
├── Utility_Operations_Dashboard.pbix
│
└── Utility_SQL_Practice.sql
