# Retail Sales Dataset Analysis
## Overview

This project demonstrates a series of Excel techniques applied to organise, analyse, and extract insights from a dataset. The focus is on efficient data manipulation using tables, formulas, and conditional functions.

## Key Features & Tasks

1. Convert Data Range into a Table
All data from columns A to H was converted into an Excel Table to enable easier sorting, filtering, and formula application.
(Insert screenshot of table here)

2. Filter and Sort Data by Age
Applied Excel’s Filter function on the Age column and sorted values from largest to smallest to identify trends and patterns by age.

<img width="493" height="194" alt="Screenshot 2025-12-08 at 16 16 51" src="https://github.com/user-attachments/assets/21aaece3-aa91-4913-9142-0dab970e9a51" />

3. Calculate Total Commission
Used the SUM function to calculate the total commission across all entries.

Cell: P10
Formula:
=SUM(H2:H100)

<img width="490" height="127" alt="Screenshot 2025-12-08 at 16 18 00" src="https://github.com/user-attachments/assets/26b933f2-80db-4f93-92fc-bb60c36b3c06" />

4. Calculate Average Commission
Used the AVERAGE function to determine the mean commission value.

Cell: P11
Formula:
=AVERAGE(H2:H100)

<img width="493" height="188" alt="Screenshot 2025-12-08 at 16 19 23" src="https://github.com/user-attachments/assets/63205db3-33b2-4520-a3a6-1a46d25a11ee" />

5. Retrieve Specific Data with VLOOKUP
Used VLOOKUP to find the commission for a specific customer ID.

Formula:
=VLOOKUP(J2, A:H, 8, FALSE)

<img width="986" height="391" alt="Screenshot 2025-12-09 at 14 42 31" src="https://github.com/user-attachments/assets/590f8a6a-c58b-40b2-8a83-5eac997743fa" />

6. Extract Unique Values
Used the UNIQUE function to list distinct entries from a column (e.g., customer names or regions).

Formula:
=UNIQUE(Table1[Product Category])

<img width="1100" height="284" alt="Screenshot 2025-12-09 at 15 04 20" src="https://github.com/user-attachments/assets/98f8f7cd-c4bb-4239-8aa1-7649e2639d26" />

7. Conditional Summing
Used SUMIFS to sum values based on specific criteria, e.g., total commission by region or age group.

Formula Example:
=SUMIFS(H2:H100, B2:B100, "Region1")

<img width="1064" height="147" alt="Screenshot 2025-12-09 at 15 07 53" src="https://github.com/user-attachments/assets/c748e2d6-6817-42ab-9bcd-0c1a039145d7" />

8. Conditional Averaging
Used AVERAGEIFS to calculate averages for subsets of data.

Formula Example:
=AVERAGEIFS(H2:H100, B2:B100, "Region1")

<img width="1013" height="147" alt="Screenshot 2025-12-09 at 15 06 56" src="https://github.com/user-attachments/assets/02ed9f63-7202-4392-bb71-d3c1aeb931ee" />

9. Transpose Unique Values
Combined TRANSPOSE and UNIQUE to display unique values horizontally rather than vertically.

Formula:
=TRANSPOSE(UNIQUE(Table1[Gender]))

<img width="1069" height="221" alt="Screenshot 2025-12-09 at 15 12 04" src="https://github.com/user-attachments/assets/1e3f63d0-9b06-413d-be73-1a7da3e35ba7" />

10. Count Total Orders
Used the COUNTIF function to count the number of orders by evaluating all Transaction IDs greater than zero.

Formula:
=COUNTIF(Table1[Transaction ID], ">0")

<img width="864" height="195" alt="Screenshot 2025-12-09 at 15 24 39" src="https://github.com/user-attachments/assets/f33790d5-550b-4f0f-a70a-1a5c118e4d95" />

11. Create a Pivot Table
Created a Pivot Table to summarise student performance and applied filtering and sorting to display the best-performing students in each subject.

<img width="497" height="250" alt="Screenshot 2025-12-09 at 16 11 06" src="https://github.com/user-attachments/assets/6acd98a0-a4de-4415-9fbe-3e553a236f97" />


13. Calculate Average Scores
Calculated the average score for each student and filled the results into column E using an appropriate average formula.

Formula example:
=AVERAGE(B2:D2)

<img width="570" height="290" alt="Screenshot 2025-12-09 at 16 12 38" src="https://github.com/user-attachments/assets/ed6df142-dd58-4788-8b5b-b92116dd647c" />

14. Identify the Highest Scores
Used the MAX function to determine which students achieved the highest scores.

Formula example:
=MAX(B2:D2)

<img width="500" height="250" alt="Screenshot 2025-12-09 at 16 12 02" src="https://github.com/user-attachments/assets/d6db3c3c-bfd6-4260-ac0d-ecea6f761c75" />


15. Filter and Sort to Identify Top Students
Applied filters and sorting to highlight the best student in the class based on average score, and then again based on the highest individual subject score.

<img width="720" height="584" alt="Screenshot 2025-12-09 at 16 13 33" src="https://github.com/user-attachments/assets/242f4424-f4b8-4bf8-83c4-566e87f10ba2" />

16. Conditional Formatting for Performance Insight
Used conditional formatting to clearly identify the highest and lowest average scores, making performance differences easier to spot visually.

<img width="735" height="235" alt="unknown" src="https://github.com/user-attachments/assets/ab9a6299-f705-4ca7-a78f-bcda0ee5b5ff" />

By applying these Excel techniques, I am able to organise and analyse data more efficiently, identify patterns and trends, and extract meaningful insights quickly. Skills such as creating tables, using formulas like SUM, AVERAGE, VLOOKUP, SUMIFS, AVERAGEIFS, COUNTIF, UNIQUE, TRANSPOSE, and MAX, as well as building PivotTables and applying filtering, sorting, and conditional formatting, enable me to explore datasets in greater depth. These methods allow me to highlight top performers, compare groups, identify the highest and lowest values, and present information clearly and accurately. Mastering these functions enhances my ability to work confidently in Excel and supports faster, more informed, data-driven decision-making across different types of analysis.
