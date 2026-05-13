# Crime-Pattern-Analysis
This is my end to end Data Science Project

Background

1.Detailed crime dataset of India from 2020-2024(Kaggle)

2.Our objective is to understand crime patterns and also have a clear view of crime resolution rates.

3.Prominent features include
	Date of Reporting
	Date of occurrence
	Crime Domain
	Victim Gender
	Weapoms used(Knife,Blunt object etc)
	City
	Crime Description
	Police Deployed

Among others

4.Derived Features(Using feature engineering)
	Crime Hour- 0-23 as the values.They represent the hour at which the crime was committed
	Case Duration-Derived from the difference of Case closed date- Reporting Date
	Crime period:-
1.	Hours 5-12 were assigned Morning
2.	Hours 12-17 were assigned Afternoon
3.	Hours 18-21 were assigned Evening
4.	Hours 22-4 were assigned Night

	Report Delay-Derived from the difference of Date Reported and Date of occurrence.

5.	During feature engineering, the report delay variable was calculated using the difference between the date reported and the date of occurrence. Some records produced negative delays due to inconsistencies where the reported date preceded the occurrence date. Since such cases are logically impossible, those records were removed during data cleaning.

