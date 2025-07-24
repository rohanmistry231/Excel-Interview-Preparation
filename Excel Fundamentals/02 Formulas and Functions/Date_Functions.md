# Date Functions in Excel

## Overview
Date functions handle temporal data for analysis. This guide covers TODAY, NOW, and DATEDIF.

## Key Functions
- **TODAY**: `=TODAY()` – Returns current date.
- **NOW**: `=NOW()` – Returns current date and time.
- **DATEDIF**: `=DATEDIF(start_date, end_date, unit)` – Calculates time difference (e.g., “d” for days).

## Step-by-Step Example
**Scenario**: Track project deadlines.
1. **Current Date**:
   - In A1, enter `=TODAY()` to show today’s date.
2. **Current Date and Time**:
   - In A2, enter `=NOW()` to show date and time.
3. **Days Until Deadline**:
   - Data: Start date in B2, Deadline in C2.
   - In D2, enter `=DATEDIF(B2, C2, "d")` to calculate days.

## Practical Scenario
You have employee hire dates and need to calculate years of service as of today, formatting dates as “MM/DD/YYYY”.

## Practice Tasks
1. Display today’s date in a cell.
2. Calculate days between two project dates using `DATEDIF`.
3. Format a date column as “DD-MMM-YYYY”.
4. Use `NOW` to track task submission times.
5. Calculate months of service for employees (use “m” in `DATEDIF`).

## Interview Tip
Interviewers may ask for date calculations. Practice formatting dates and using `DATEDIF` for precise results.