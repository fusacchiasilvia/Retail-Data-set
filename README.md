# Retail Sales Dataset Analysis
## Overview

This document outlines the tasks completed on the retail_sales_dataset.xlsx Excel file. The dataset contains information on retail sales, including customer age, sales figures, commissions, and other relevant metrics. The steps below describe how the data was analysed and summarised using various Excel functions.

## Tasks Completed
Task	Description	Screenshot
1. Convert Data Range into a Table, selected all available data from columns A to H and converted it into an Excel table to enable easier sorting, filtering, and applying functions.	(Insert screenshot of table here)
2. Filter Data by Age.	Applied the Filter function on the Age column and sorted values from Largest to Smallest to identify trends by age.
<img width="493" height="194" alt="Screenshot 2025-12-08 at 16 16 51" src="https://github.com/user-attachments/assets/21aaece3-aa91-4913-9142-0dab970e9a51" />

3. I calculated the Total Commission and used the SUM function to calculate the total commission.
Cell: P10
Formula: =SUM(H2:H100)

<img width="490" height="127" alt="Screenshot 2025-12-08 at 16 18 00" src="https://github.com/user-attachments/assets/26b933f2-80db-4f93-92fc-bb60c36b3c06" />

4. I calculated the average commission	and used the AVERAGE function to calculate the average commission.
Cell: P11
Formula: =AVERAGE(H2:H100
<img width="493" height="188" alt="Screenshot 2025-12-08 at 16 19 23" src="https://github.com/user-attachments/assets/63205db3-33b2-4520-a3a6-1a46d25a11ee" />

5. I used VLOOKUP to retrieve the commission for a specific customer ID.
Formula: =VLOOKUP(J2, A:H, 8, FALSE)	

(Insert screenshot of VLOOKUP formula and result here)


6. To extract Unique Values, I used the UNIQUE function to list distinct entries from a column (e.g., customer names or regions).	(Insert screenshot of UNIQUE function here)


7. Conditional Summing	Used SUMIFS to sum values based on specific criteria, e.g., total commission by region or age group.	(Insert screenshot of SUMIFS function here)


8. Conditional Averaging	Used AVERAGEIFS to calculate averages for subsets of data.	(Insert screenshot of AVERAGEIFS function here)


9. Transpose Unique Values	Combined: TRANSPOSE and UNIQUE to display unique values horizontally rather than vertically.	(Insert screenshot of TRANSPOSE UNIQUE function here)
Notes


Using tables, filters, and dynamic functions such as UNIQUE, SUMIFS, VLOOKUP, and AVERAGEIFS improves efficiency and insight when analysing Excel data.

Screenshots provide visual confirmation of applied functions and results, making it easier to verify the work that has been completed.
