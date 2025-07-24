# Text Functions in Excel

## Overview
Text functions manipulate strings for data cleaning. This guide covers LEFT, RIGHT, and CONCATENATE.

## Key Functions
- **LEFT**: `=LEFT(text, num_chars)` – Extracts characters from the start.
- **RIGHT**: `=RIGHT(text, num_chars)` – Extracts characters from the end.
- **CONCATENATE**: `=CONCATENATE(text1, text2, ...)` – Joins text strings.

## Step-by-Step Example
**Scenario**: Clean and combine customer names.
1. **Extract First Name**:
   - Data: Full names in A2:A10 (e.g., “John Doe”).
   - In B2, enter `=LEFT(A2, FIND(" ", A2)-1)` to get “John”.
2. **Extract Last Name**:
   - In C2, enter `=RIGHT(A2, LEN(A2)-FIND(" ", A2))` to get “Doe”.
3. **Combine Names**:
   - In D2, enter `=CONCATENATE(B2, " ", C2)` to get “John Doe”.

## Practical Scenario
You have a column of email addresses (e.g., john.doe@company.com). Extract usernames and domains, then combine with a custom suffix.

## Practice Tasks
1. Extract the first 3 characters of product codes.
2. Get the last 4 digits of phone numbers using `RIGHT`.
3. Combine city and state with a comma using `CONCATENATE`.
4. Use `LEFT` and `FIND` to extract area codes.
5. Clean inconsistent text data (e.g., trim extra spaces).

## Interview Tip
Interviewers may test text manipulation. Practice combining functions like `FIND` with `LEFT` for complex tasks.