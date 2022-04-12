# Pewlett Hackard Analysis

Employee DB
SQL
pgAdmin4

## Objectives

* Create an ERD to map out the relationship of the datasets.
* Start a new SQL DB in pgAdmin4.
* Import csv files to created tables.
* Join tables and crate new tables.
* Export newly made tables to csv files.
* Use SQL query statements.

The main goal was to plan and prepare for the "silver tsunami".  Using pgAdmin4 to compile employee data and key in on specific demographic workforce fitting criteria for retirement and mentorship.  To arrive at the data table needed to understand the number of employees retiring data was imported to a SQL database using pgAdmin4.  Once the data was imported into the data tables made.  The data was then joined into new tables from established primary and foreign keys.

## Results

To start, it is helpful to map out the relationships of the data using quickdatabasediagrams.com, establishing the primary and foreign keys :

![ERD](https://github.com/vhernandezjr/Pewlett-Hackard-Analysis/blob/380492200a5f4ce344e4217e5d9933c0b4dcd79f/Analysis%20Projects%20Folder/Pewlett-Hackard-Analysis%20Folder/PNGs/ERD.png)

Having the keys established we are now able to dial in on the employees that meet our criteria of retirement age.  Using 'distinct on' is important for this step so no duplicates are listed and we have a unique list of employees.

![U_T](https://github.com/vhernandezjr/Pewlett-Hackard-Analysis/blob/2db2f5a701f3dd3b283a67a7e808d527506dfff6/Analysis%20Projects%20Folder/Pewlett-Hackard-Analysis%20Folder/PNGs/U_T.png)

Taking this data further we can also key in on specific job titles.  Knowing what departments are going to be most impacted is critical for preparation  of the "silver tsunami".

![R_Titles](https://github.com/vhernandezjr/Pewlett-Hackard-Analysis/blob/2db2f5a701f3dd3b283a67a7e808d527506dfff6/Analysis%20Projects%20Folder/Pewlett-Hackard-Analysis%20Folder/PNGs/R_Titles.png)

A key element for preporation is having staff available to mentor the next wave of core staff.  For this a table of staff falling into a specific range was 

![M_E](https://github.com/vhernandezjr/Pewlett-Hackard-Analysis/blob/2db2f5a701f3dd3b283a67a7e808d527506dfff6/Analysis%20Projects%20Folder/Pewlett-Hackard-Analysis%20Folder/PNGs/M_E.png)

## Summary

The impact of the "silver tsunami" is highlighted by impending number of potential retirees.  The analysis puts the number at +90K and leaves the question of how can P-H maintain its wealth of experience after the impending retirements.  A simple solution is to keep a population of transitional employees to mentor the next generation of senior staff.  In this program employees with potential to fill the critical gaps can be fast tracked to significant roles so the company maintains status quo.  The analysis of potential mentee employees puts the number at 1549, this is significantly smaller than those retiring.  This is why identifying key employees on the cusp of retirement for transition is important.  The company will potentially need to shift to having more management levels to oversee the younger less experienced staff.  So fast tracking employees that show promise to key positions under transitional staff is important.  The group that will fit this criteria will most likely fall in the "goldilocks" range, near the age of 35 under 44.  Expanding the mentee program will be critical.
