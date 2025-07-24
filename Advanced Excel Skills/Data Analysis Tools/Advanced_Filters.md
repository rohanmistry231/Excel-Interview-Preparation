# Advanced Filters in Excel

## Overview
Advanced Filters handle complex filtering criteria, a key skill for advanced data analysis and interviews.

## Key Concepts
- **Advanced Filter**: Data > Advanced.
- **Criteria Range**: Define conditions in a separate range.
- **Options**: Filter in place or copy to another location.
- **Conditions**: Use formulas or multiple criteria.

## Step-by-Step Example
**Scenario**: Filter sales >1000 in “North” region.
1. **Setup Data**:
   - Columns: Region (A), Sales (B).
2. **Create Criteria Range**:
   - D1:D2: Region, Sales.
   - D2: “North”, E2: “>1000”.
3. **Apply Filter**:
   - Data > Advanced.
   - List Range: A1:B100, Criteria Range: D1:E2.
   - Copy to: F1.

## Practical Scenario
Filter a dataset for employees with salary >$50,000 and years of service >5.

## Practice Tasks
1. Filter data for sales >500 in specific categories.
2. Use a formula in the criteria range (e.g., `=B2>AVERAGE(B:B)`).
3. Copy filtered results to a new sheet.
4. Combine multiple criteria (e.g., date and value).
5. Test Advanced Filter with text conditions.

## Interview Tip
Interviewers may test complex filtering. Practice setting up criteria ranges and explaining logic.