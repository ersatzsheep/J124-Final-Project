# Story Summary and Sourcing

In this project, I analyzed [“California Kindergarten Immunization Rates”](https://www.kaggle.com/broach/california-kindergarten-immunization-rates?select=InfantData.csv) sourced from the California Department of Public Health. My analysis focuses on [kindergarten immunization statistics](https://www.kaggle.com/broach/california-kindergarten-immunization-rates?select=StudentData.csv) from 2000 to 2015. 

# Data Visualizations


# Data Analysis Process
The first step of my analysis was to clean the data. After inspection, the data did not require much refining as it was mostly normalized. Because my scope of analysis did not require school names and this column of data exhibited significant inconsistencies, I created a new spreadsheet without it for my analysis. I also introduced five new variables: 1) pMMR, 2) pDTP, 3) pPolio, 4) pPBE, and 5) pPME. Details on column headers can be found here.

The scope of my analysis sought to answer the following questions:
1)	What was the total exemption rate in 2000? In 2015? How did the two years compare?
2)	Which counties had the highest vaccination exemption rates in 2000? In 2015? 
3)	For public schools, what percentage of kindergarteners completed their MMR, DTP, and Polio vaccinations in 2000 and 2015? For private schools? How do they compare?
4)	Which counties exhibited the greatest increase in exemption rate in 2015 compared to 2000 data?
5)	Which counties had the lowest vaccination rates for MMR, DTP, and Polio in 2015?
6)	Which counties had the highest standard deviation in vaccination rates for MMR, DTP, and Polio in 2015?
7)	Which vaccine demonstrated the greatest standard deviation in vaccination rate across the state in 2015?

Key assumptions for analysis:
* All questions were answered solely using the data set mentioned above.
* Vaccination rate is defined as the percentage of students vaccinated for each respective vaccine type from the total number of students in the school type, county, or year specified in the question.
* Exemption rate is defined as the percentage of students with an exemption (PBE or PME) from the total number of students in the school type, county, or year specified in the question.

Answers to my data analysis:
1)	What was the total exemption rate in 2000? In 2015? How did the two years compare?

First, I created a pivot table that summed up the total number of PBE and PME exemptions, and the number of reported kindergarten students in 2000 and 2015.


Then I copied the pivot table’s values into another spreadsheet and found the total number of exemptions in 2000 by summing the total number of PBE and PME exemptions. I determined the exemption rate by dividing the total number of exemptions by the total number of students and multiplying the resulting value by 100. 

> The total exemption rates in 2000 and 2015 were 0.842% and 2.498% respectively. The total exemption rate increased by 1.656% from 2000 to 2015 with a notable increase in personal belief exemptions from inspection. 






