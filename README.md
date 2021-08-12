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

2) Which counties had the highest vaccination exemption rates in 2000? In 2015? 

I created a pivot table that summed the total number of PBE and PME exemptions, and the number of reported kindergarten students for every county in California in 2000 and 2015.

I copied the values to a new spreadsheet and summed the total number of PBE and PME exemptions to get the total number of exemptions per county. Then, I calculated the percentage of  kindergarteners with exemptions for each county based on the total number of kindergarteners per county. Finally, I sorted the vaccination exemption rates in descending fashion to determine the counties with the highest rates. 

> In 2000, the counties with the highest exemption rates were Nevada, Trinity, and Modoc.

> In 2015, the counties with the highest exemption rates were Nevada, Trinity, and Mariposa. 

3) Which counties exhibited the greatest increase in exemption rate in 2015 compared to 2000 data?

I used the same values from the old spreadsheet in question 2 and pasted it into a new spreadsheet. In this new spreadsheet, I deleted unnecessary columns and subtracted the exemption rates for 2000 from the 2015 counterpart for each county. Finally, I sorted the exemption rates based on descending values and reported the counties with the largest percentage increase in exemptions.

> The counties that exhibited the greatest increase in exemption rate in 2015 compared to 2000 were Nevada, Trinity, and Mariposa.

4) For public schools, what percentage of kindergarteners completed their MMR, DTP, and Polio vaccinations in 2000 and 2015? For private schools? How do they compare?

I created a pivot table that for each school type (public and private), reported the sum of total kindergarteners and the total number of children with completed MMR, DTP, and Polio vaccinations in 2000 and 2015. 

I copied the values to a new spreadsheet and determined the percentage of children who received each vaccination type from the total number of kindergarteners for each school type. 

> In 2000, private schools had vaccination rates of 92.252%, 93.331%, and 93.619% for the MMR, DTP, and Polio vaccines respectively. The same year, public schools had vaccination rates of 95.989%, 95.765%, and 96.451% for the MMR, DTP, and Polio vaccines respectively.

> In 2015, private schools had vaccination rates of 90.697%, 90.610%, and 90.903% for the MMR, DTP, and Polio vaccines respectively. The same year, public schools had vaccination rates of 94.896%, 94.538%, and 95.069% for the MMR, DTP, and Polio vaccines respectively.

> Private schools had lower vaccination rates than public schools in both 2000 and 2015. Private and public schools both decreased their vaccination rates overall in 2015 compared to 2000. 

5) Which counties had the lowest vaccination rates for MMR, DTP, and Polio in 2015?
	
I created a pivot table that reported the total number of kindergarteners and the total number of children who completed MMR, DTP, and Polio vaccinations in 2015 for each county. 

I copied the values from this table and pasted them into a new spreadsheet. I calculated the vaccination rates by determining the percentage of kindergarten children receiving each vaccination type from the total number of enrolled students in 2015. Finally, I sorted the vaccination rates for each vaccine type in ascending order to identify the counties with the lowest vaccination rates for MMR, DTP, and Polio independently.

>In 2015, Trinity, Nevada, and Tuolumne were the three counties with the lowest vaccination rates for MMR.

>In 2015, Trinity, Nevada, and Mariposa were the three counties with the lowest vaccination rates for DTP.

>In 2015, Trinity, Nevada, and Tuolumne were the three counties with the lowest vaccination rates for MMR.

6) Which counties had the highest standard deviation in vaccination rates for MMR, DTP, and Polio in 2015?

I created a pivot table that, for every county, displayed the standard deviation in percentage of kindergarteners receiving the MMR, DTP, and Polio vaccines in 2015. 

I copied the values of this table into a new spreadsheet and sorted the standard deviations in a descending fashion to determine the counties with the highest variation per vaccine type.

>In 2015, Lassen, Tuolumne, and Nevada counties had the greatest standard deviation in the percentage of reported kindergarteners who completed MMR vaccinations.

>In 2015, Lassen, Nevada, and Mariposa counties had the greatest standard deviation in the percentage of reported kindergarteners who completed DTP vaccinations.

>In 2015, Lassen, Nevada, and Mendocino counties had the greatest standard deviation in the percentage of reported kindergarteners who completed Polio vaccinations.

7) Which vaccine demonstrated the greatest standard deviation in vaccination rate across the state in 2015?

Using the spreadsheet in question 5 that detailed the vaccination rates for each vaccine type for each county in 2015, I calculated the standard deviation across every county for each vaccine type. 

> The DTP vaccine demonstrated the greatest standard deviation across all counties in 2015.







