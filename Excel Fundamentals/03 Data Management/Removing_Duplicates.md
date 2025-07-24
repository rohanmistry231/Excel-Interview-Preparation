# Removing Duplicates in Excel

## Overview
Removing duplicates cleans datasets by eliminating redundant entries, a common interview task.

## Key Concepts
- **Remove Duplicates** (Data > Remove Duplicates):
  - Select columns to check for duplicates.
  - Keeps first occurrence, removes others.
- **Case Sensitivity**: “Apple” and “apple” are treated as the same.
- **Backup**: Copy data before removing duplicates.

## Step-by-Step Example
**Scenario**: Clean a customer list.
1. **Prepare Data**:
   - Columns: ID (A2:A100), Name (B2:B100).
2. **Remove Duplicates**:
   - Select A2:B100.
   - Data > Remove Duplicates > Check “ID” only.
   - Result: Duplicate IDs removed.
3. **Verify**:
   - Check row count before and after.

## Practical Scenario
You have a dataset with repeated customer emails. Remove duplicates based on email while keeping other columns.

## Practice Tasks
1. Remove duplicate customer IDs from a list.
2. Clean a dataset by checking two columns (e.g., Name and Email).
3. Verify data integrity after removing duplicates.
4. Test case sensitivity with text data.
5. Combine with sorting for a clean dataset.

## Interview Tip
Interviewers may ask for data cleaning. Practice removing duplicates and explaining the process.