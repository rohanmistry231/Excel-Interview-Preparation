# Automating Repetitive Tasks with VBA

## Overview
VBA automates repetitive tasks, saving time and impressing interviewers with efficiency.

## Key Concepts
- **Common Tasks**: Formatting, data cleaning, report generation.
- **Loops**: Automate across ranges.
- **Events**: Trigger macros on actions (e.g., worksheet change).

## Step-by-Step Example
**Scenario**: Automate monthly report formatting.
1. **Write Script**:
   ```vba
   Sub FormatReport()
       With Range("A1:D1")
           .Font.Bold = True
           .Interior.Color = vbBlue
       End With
       Range("B2:B100").NumberFormat = "$#,##0.00"
       Range("A1:D100").Borders.Weight = xlMedium
   End Sub
   ```
2. **Run Script**:
   - Developer > Macros > FormatReport > Run.

## Practical Scenario
Automate a script to clean a dataset: remove duplicates, format numbers, and add headers.

## Practice Tasks
1. Automate formatting for a table (bold headers, currency format).
2. Write a script to remove blank rows.
3. Automate a data copy to a new sheet.
4. Create a macro to apply filters.
5. Link a macro to a button for easy access.

## Interview Tip
Interviewers may ask for automation examples. Practice scripting repetitive tasks and explaining benefits.