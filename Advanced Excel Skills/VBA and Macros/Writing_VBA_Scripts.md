# Writing VBA Scripts in Excel

## Overview
Writing VBA scripts allows custom automation, a key skill for advanced Excel interviews.

## Key Concepts
- **VBA Editor**: Developer > Visual Basic.
- **Structure**: Subroutines (`Sub`), variables, and objects.
- **Common Objects**:
  - `Range`: Access cells (e.g., `Range("A1")`).
  - `Worksheet`: Access sheets (e.g., `Worksheets("Sheet1")`).

## Step-by-Step Example
**Scenario**: Highlight cells >1000.
1. **Open VBA Editor**:
   - Developer > Visual Basic.
2. **Insert Module**:
   - Insert > Module.
3. **Write Code**:
   ```vba
   Sub HighlightHighSales()
       Dim cell As Range
       For Each cell In Range("B2:B100")
           If cell.Value > 1000 Then
               cell.Interior.Color = vbYellow
           End If
       Next cell
   End Sub
   ```
4. **Run Script**:
   - Developer > Macros > HighlightHighSales > Run.

## Practical Scenario
Write a VBA script to format all negative values in a column with red font.

## Practice Tasks
1. Write a script to bold a range (A1:A10).
2. Create a script to copy data to another sheet.
3. Clear formatting in a range using VBA.
4. Write a script to insert a new row.
5. Test a script with error handling (`On Error Resume Next`).

## Interview Tip
Interviewers may ask for custom automation. Practice writing and debugging simple VBA scripts.