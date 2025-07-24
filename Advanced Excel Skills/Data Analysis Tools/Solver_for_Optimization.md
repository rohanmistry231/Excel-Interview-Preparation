# Solver for Optimization in Excel

## Overview
Solver optimizes solutions by adjusting variables, ideal for complex interview problems.

## Key Concepts
- **Enable Solver**: Data > Solver (enable via File > Options > Add-ins).
- **Components**:
  - Objective: Cell to optimize (max/min).
  - Variables: Cells to adjust.
  - Constraints: Limits on variables.
- **Solve**: Find optimal solution.

## Step-by-Step Example
**Scenario**: Maximize profit by adjusting product mix.
1. **Setup Model**:
   - A1:A2: Units of Product A and B.
   - B1:B2: Profit per unit.
   - C1: Total Profit (`=A1*B1+A2*B2`).
   - D1:D2: Resource constraints.
2. **Run Solver**:
   - Data > Solver.
   - Set Objective: C1 (Max), Variables: A1:A2, Constraints: D1:D2<=100.
   - Solve.

## Practical Scenario
Optimize a budget allocation across three projects to maximize ROI under resource limits.

## Practice Tasks
1. Use Solver to maximize sales with budget constraints.
2. Minimize costs with fixed output.
3. Add multiple constraints (e.g., min/max units).
4. Test Solver with non-linear objectives.
5. Save and load Solver scenarios.

## Interview Tip
Interviewers may test optimization. Practice setting up Solver models and explaining constraints.