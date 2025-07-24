# Automating Data Refresh in Power Query

## Overview
Automating data refresh in Power Query saves time by updating datasets automatically, a valuable skill for interviews.

## Key Concepts
- **Refresh**: Data > Refresh All updates queries.
- **Connection Properties**: Set refresh intervals or manual refresh.
- **Data Sources**: Ensure source files/databases are accessible.
- **Load Settings**: Optimize for large datasets.

## Step-by-Step Example
**Scenario**: Automate refresh for a monthly sales report.
1. **Create Query**:
   - Import `sales.csv` via Power Query.
   - Transform: Filter for 2025, group by month.
2. **Set Refresh**:
   - Data > Queries & Connections > Right-click query > Properties.
   - Enable “Refresh every 60 minutes” or “Refresh on open”.
3. **Test Refresh**:
   - Update `sales.csv`, click Data > Refresh All.

## Practical Scenario
You have a query pulling data from a shared folder. Set it to refresh automatically when the workbook opens.

## Practice Tasks
1. Set a query to refresh every 30 minutes.
2. Configure a query to refresh on workbook open.
3. Test refresh with an updated CSV file.
4. Combine multiple queries with automatic refresh.
5. Optimize refresh for a large dataset.

## Interview Tip
Interviewers may ask about automation. Practice setting refresh options and explaining benefits.