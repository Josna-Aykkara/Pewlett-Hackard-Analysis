# Pewlett-Hackard-Analysis

## Overview of the analysis

This project is for the analysis is to help the HR Manager to prepare for the upcoming ‘Silver Tsunami”. The main goal of the project is to recognize the potential employees at Pewlett-Hackard who would be retiring soon based on the departments and to recognize the prospective employees who are eligible to part take in the mentorship program.


The report is extracted from the various data provided in csv format. I was able to get the results by creating a quick ERD diagram, creating customized tables, and importing and exporting data based on the queries created.


## Results

-	**The list of potential employees who would be retiring were identified from the analysis -** The retirement table created was able to identify the retiring employees along with their respective employee numbers, first_name, last_name,title, from-date and to-date. The below table displays the list of employees who are going to retire soon. The data is filters based on the birth date of employees born between 1952-1955, as a result we get 133,776 results.


![This is an image](https://github.com/Josna-Aykkara/Pewlett-Hackard-Analysis/blob/main/Data/Retirement%20Titles%20table.JPG)

- **The unique_titles table created displays the list of all the potential employees -** The table removes all duplicate rows or cell containing duplicate information. It helps to avoid duplication and get an clean data set for the running the report of employees


![This is an image](https://github.com/Josna-Aykkara/Pewlett-Hackard-Analysis/blob/main/Data/Unique_titles.JPG)

- **Potential retiring empolyees Grouped By title –** From the retiring_title table provides us information employees who would be retiring based on each department. The information would enable the company to plan their manpower effectively and avoid shortage of staffs in the various departments which in turn would affect functioning of the organization. As per the table there are 90,398 rows in total.


![This is an image](https://github.com/Josna-Aykkara/Pewlett-Hackard-Analysis/blob/main/Data/Retirement%20Titles%20count%20table.JPG)

- **Eligibility of employees for Mentorship program –** Based on the mentorship_eligibility table created after joining multiple tables, we can identify the potential employees who are eligible to mentor the new recruits or people who are promoted to the next level.  The information is readily available and easily understood. 


![This is an image](https://github.com/Josna-Aykkara/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.JPG)

## Summary

o	**How many roles will need to be filled as the "silver tsunami" begins to make an impact?**

The information regarding the employees who are potentially going to retire soon is available in the retirement_titles table. The numbers of openings in the various roles based on each department was extracted based on additional query. It would equip the departments to plan their manpower requirements effectively and avoid any problems due to manpower shortage. It also helps to plan the sound functioning of the department by planning smooth transition of the retiring roles.  

A major percentage of the workforce is in the potential retirement age, as a result there is an expectation of many positions to be covered over the next few years. Majority of the retiring employees constitute or hold higher management level title. Senior Engineer and Senior staff are the major titles that would be seeing a manpower turnover due to retirement in the next few years within the organization.

o	**Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?**

Yes, we can identify the qualifies retirement ready employees for each department who can mentor the next generation. We ran a query with filters to get the number of staffs and identify them based on their respective titles at various levels of the organization. The mentoring employees would be able to provide guidance o the future generation based on their rich experience in their respective field. The count of mentor eligible employees may not be sufficient to train the new hires due t the difficulty of the nature of work due to the technicality.



o	**Two additional queries or tables that may provide more insight into the upcoming "silver tsunami."**

- It would be beneficial to run a query to get information on the potential suitable employees who would be suitable for being a mentee.

- A query should be prepared to get the accurate information on the number of employees interested to continue in the workforce as a part-timer and mentor the junior staff. It would enable the organization to plan the manpower and plan the recruitment process accordingly, so that the new hires are not lost in the onboarding process to the new position without a mentor.
