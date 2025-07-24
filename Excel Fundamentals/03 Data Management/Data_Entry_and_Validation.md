# Data Entry and Validation in Excel

## Overview
Data validation ensures accurate input, critical for clean datasets. This guide covers setting validation rules and error alerts.

## Key Concepts
- **Data Validation** (Data > Data Validation):
  - Restrict to lists, numbers, dates.
  - Example: Dropdown for “Yes/No”.
  - Set ranges (e.g., 1-100).
- **Input Messages**: Show instructions when cell is selected.
- **Error Alerts**: Display messages for invalid entries (Stop, Warning, Information).

## Step-by-Step Example
**Scenario**: Restrict a column to specific categories.
1. **Create Dropdown**:
   - Select B2:B10.
   - Data > Data Validation > List > Source: “High,Medium,Low”.
2. **Set Number Range**:
   - Select C2:C10.
   - Data > Data Validation > Whole Number > Minimum: 1, Maximum: 100.
3. **Add Error Alert**:
   - In Data Validation, set Error Alert to “Stop” with message: “Enter 1-100 only”.

## Practical Scenario
You’re managing a survey. Restrict a column to “Male/Female” and another to ages 18-65, with error messages for invalid entries.

## Practice Tasks
1. Create a dropdown for product categories.
2. Restrict a column to dates in 2025.
3. Set a number range (0-500) with an error alert.
4. Add an input message to guide users.
5. Test validation by entering invalid data.

## Interview Tip
Interviewers may ask for data integrity. Practice setting up validation and explaining rules.