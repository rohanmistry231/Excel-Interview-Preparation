# Arithmetic Operators in Excel

## Overview
Arithmetic operators perform basic calculations, a foundational skill for Excel interviews. This guide covers addition, subtraction, multiplication, and division.

## Key Concepts
- **Operators**:
  - `+`: Addition (e.g., `=A1+B1`).
  - `-`: Subtraction (e.g., `=A1-B1`).
  - `*`: Multiplication (e.g., `=A1*B1`).
  - `/`: Division (e.g., `=A1/B1`).
- **Order of Operations**: PEMDAS (Parentheses first, then Exponents, Multiplication/Division, Addition/Subtraction).
- **Cell References**: Use relative (A1) or absolute ($A$1) references for dynamic calculations.

## Step-by-Step Example
**Scenario**: Calculate order totals for a store.
1. **Setup Data**:
   - Column A: Quantity (A2:A5).
   - Column B: Price per unit (B2:B5).
2. **Total Cost**:
   - In C2, enter `=A2*B2` to multiply quantity by price.
   - Drag down to C5.
3. **Discounted Total**:
   - In D2, enter `=C2-C2*0.1` for 10% discount.
4. **Total Revenue**:
   - In D6, enter `=SUM(D2:D5)`.

## Practical Scenario
You have a dataset with units sold and unit price. Calculate total revenue, apply a 5% tax, and subtract shipping costs ($10 per order).

## Practice Tasks
1. Multiply quantity and price for 10 orders.
2. Calculate profit (revenue - cost) for a dataset.
3. Divide a budget of $5000 across 12 months.
4. Use parentheses to prioritize calculations (e.g., `=(A1+B1)*C1`).
5. Combine operators to calculate net income after tax and expenses.

## Interview Tip
Interviewers may test formula accuracy. Practice using cell references and explaining calculations clearly.