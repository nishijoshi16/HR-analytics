# HR-analytics
1. Project Title:
HR Analytics Dashboard using Power BI

2. Short Description / Purpose:
This project aims to provide a comprehensive view of employee attendance trends, including presence, work-from-home (WFH), and sick leave (SL) statistics. It helps HR managers and team leaders monitor workforce participation, identify absenteeism patterns, and take informed decisions to improve employee engagement and operational efficiency.

3. Tech Stack:
Tool Used: Microsoft Power BI
Data Processing: Power Query & DAX
Visualization: Power BI Charts (line, bar, matrix, cards)
Data Model: Star schema structure with calendar mapping for time-series analysis

4. Data Source:
Source: HR attendance data (dummy or anonymized internal data)
Granularity: Daily-level employee attendance including Present (P), WFH, Sick Leave, Weekly Off (WO), and Half-day/Leave types
Period Covered: April 2022 to June 2022

5. Business Problems Addressed: Lack of visibility into employee attendance trends, Difficulty in tracking WFH adoption and sick leave usage, Need to identify employees with frequent absences, Understand day-of-week productivity variances

6. Dashboard Features & Visual Walkthrough:
KPI Cards: Present %: 91.55%, WFH %: 11.15%, Sick Leave %: 1.08%

Line Charts: Present % by Date: Reveals declining attendance trend over 3 months, SL % by Date: Shows rising sick leave pattern, WFH % by Date: Indicates fluctuations with a slight increase

Matrix Table (Day-wise): Shows WFH, SL, and Present % for each day of the week. E.g., Friday has the highest WFH (13.83%).

Employee-Wise Table: Displays individual-level Present %, WFH %, and SL %. E.g., Gregory Carr has the lowest presence (52.38%).

Daily Log (April 1st, 2022): Shows attendance status (P/WFH/WO) per employee on a specific date for micro-level drill down

7. Impacts and Analysis: Helped HR identify top absenteeism days (Fridays & Thursdays) to consider policy changes or flexible scheduling. Detected patterns of employees consistently on WFH or absent, enabling one-on-one HR interventions. Improved team productivity by focusing on the correlation between SL spikes and workload/stress periods. Informed decision-makers about overall workforce participation trends, essential for resource planning and business continuity.

8. Demo:
<img width="1445" height="801" alt="Screenshot 2025-07-21 185905" src="https://github.com/user-attachments/assets/2d764724-0b4e-4670-8df4-202ae817c6b9" />
