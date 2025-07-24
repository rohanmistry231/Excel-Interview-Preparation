# Transforming Data in Power Query

## Overview
Power Query’s transformation tools clean and reshape data, essential for preparing datasets for analysis and interviews.

## Key Concepts
- **Transformations**:
  - Filter Rows: Remove unwanted data.
  - Remove Columns: Keep only relevant fields.
  - Merge Queries: Combine datasets.
  - Group By: Aggregate data (e.g., sum, average).
- **Query Editor**: Apply transformations visually.
- **Applied Steps**: Track and modify transformation steps.

## Step-by-Step Example
**Scenario**: Clean and merge sales data.
1. **Import Data**:
   - Load two CSV files: `sales.csv` (Date, Product, Sales) and `products.csv` (Product, Category).
2. **Filter Rows**:
   - In Query Editor, filter `sales.csv` to exclude Sales <100.
3. **Merge Queries**:
   - Home > Merge Queries > Join `sales` with `products` on Product column.
4. **Group By**:
   - Group `sales` by Category, calculate total Sales.

## Practical Scenario
You have a dataset with duplicate rows and missing values. Use Power Query to remove duplicates, fill missing data, and merge with a category table.

## Practice Tasks
1. Filter a dataset to show only 2025 sales.
2. Remove unnecessary columns from a query.
3. Merge two datasets on a common key (e.g., Product ID).
4. Group sales data by region and calculate averages.
5. Replace null values with a default (e.g., 0).

## Interview Tip
Interviewers may test data cleaning. Practice transformations and explain each step clearly.