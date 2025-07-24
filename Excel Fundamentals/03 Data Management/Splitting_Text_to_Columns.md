# Splitting Text to Columns in Excel

## Overview
Text to Columns separates combined data into multiple columns, useful for data cleaning.

## Key Concepts
- **Text to Columns** (Data > Text to Columns):
  - **Delimited**: Split by commas, spaces, tabs, etc.
  - **Fixed Width**: Split at specific positions.
- **Common Delimiters**: Comma, space, tab, semicolon.
- **Preview**: See split results before applying.

## Step-by-Step Example
**Scenario**: Split full names into first and last names.
1. **Prepare Data**:
   - Column A: Names (e.g., “John Doe” in A2:A10).
2. **Split by Delimiter**:
   - Select A2:A10.
   - Data > Text to Columns > Delimited > Space > Finish.
   - Result: First names in A, last names in B.
3. **Fixed Width**:
   - For fixed-format codes (e.g., “123-ABC”).
   - Data > Text to Columns > Fixed Width > Set break at position 3.

## Practical Scenario
You have addresses in one column (e.g., “123 Main St, NY”). Split into street and city using a comma delimiter.

## Practice Tasks
1. Split “City,State” into two columns.
2. Split product codes (e.g., “A123-B”) using a hyphen.
3. Use fixed width to split “MMDDYYYY” dates.
4. Split email addresses at “@”.
5. Clean a dataset with inconsistent delimiters.

## Interview Tip
Interviewers may test data cleaning. Practice splitting text and verifying results.