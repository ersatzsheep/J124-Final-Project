# Nevada County's Barriers to Vaccination

## Story Summary

In summary, my data analysis identified Nevada, Trinity, and Mariposa as the counties with the highest vaccination exemption rates in 2015. Additionally, Trinity, and Nevada had the lowest vaccination rates for MMR, DTP, and Polio in 2015. Finally, Nevada was among the counties with the highest standard deviation in vaccination rates for MMR, DTP, and Polio in 2015. From these results, the recurrence of Nevada County emerges as a newsworthy lead.

Nevada County is a point of interest due to its relatively lower vaccination rates, higher vaccination exemption rates, and higher standard deviation in vaccination rates based on immunization records for California kindergarteners in 2015. These identified trends lead me to believe that this county experiences significant barriers to vaccination. My investigation will involve identifying these barriers and outlining why they exist. 

Are people hesitant to receive vaccinations? If so, why? Is there a deep-rooted historical rationale? Is it due to religious beliefs? Are there medical conditions that disproportionately affect this community that lead to increased medical exemptions? Or, are these trends due to deficits in physical access to vaccines? Are there limited nearby medical facilities? Are there monetary barriers that discourage vaccinations? These questions will be investigated by visiting Nevada County and interviewing locals. Recording anecdotes from those who have not completely vaccinated their kindergarteners is essential to contextualize the trends found in the data. After understanding the root of the problem, I want to compare Nevada county’s Covid vaccination rates to the rest of the state and nation to see if the same barriers have carried over to the pandemic in a time where being vaccinated could easily be the determining factor in a life or death situation.

## Sourcing

In this project, I analyzed [“California Kindergarten Immunization Rates”](https://www.kaggle.com/broach/california-kindergarten-immunization-rates?select=InfantData.csv) sourced from the California Department of Public Health. My analysis focuses on [kindergarten immunization statistics](https://www.kaggle.com/broach/california-kindergarten-immunization-rates?select=StudentData.csv) from 2000 to 2015. 

### Potential Interview Contacts
1) Jill Blake, the Public Health Director of Nevada County
	* Email: public.health@co.nevada.ca.us
	* Phone Number: 530-265-1450 
	* As the Public Health Director of Nevada County, I am assuming Blake has a lot of knowledge about the current and historical shortcomings in local vaccination efforts. Additionally, Blake can contextualize these trends in the overarching vaccination hesitancy problem that has received national attention due to the Covid-19 pandemic.
2) Sharyn Turner, the Nevada County Superintendent of Schools Health Coordinator
	* Email: sturner@nevco.org
	* Phone Number: (530) 478-6400 ext. 2045
	* Turner is the official contact for the Nevada County Public Health’s annual Back-to-School Immunization Clinic. I want to ask Turner about the school’s stance on current vaccination rates for kindergarteners and what outreach efforts are in progress to improve statistics. Turner is key in learning about the strengths and weaknesses in ongoing solutions.

### Additional Sources
1) [Nevada County’s 2019 Health Needs Assessment](https://www.mynevadacounty.com/DocumentCenter/View/27995/Nevada-County-CHA-2019-PDF?bidId=)
	* This source provides statistics on the county’s self-assessed health needs.
	* This information can be used to identify additional trends that contextualize the barriers residents are facing when it comes to early childhood immunizations for MMR, DTP, and Polio.
Any trends found can be used to develop strategies to improve health outcomes in Nevada County in a solutions-based journalism piece. 
2) [Covid-19 Case Rates and Vaccination Data](https://nevcounty.maps.arcgis.com/apps/dashboards/index.html#/14d4460858214b358dfa3fae4cf33458)
	* This source provides the latest statistics posted by the county on Covid-19 transmission amidst increased vaccination efforts and the rising delta variant.
	* This information can be compared to national vaccination and case rate data to outline and address the deficits in Nevada County amidst recent surges.

## Data Visualizations

### 1) [Vaccination Exemption Rates in 2015](https://www.datawrapper.de/_/krQtn/)
![choropleth](https://user-images.githubusercontent.com/87747630/129159216-054c26a0-f851-4929-a83d-3b520c71c07f.png)

### 2) [Vaccination Exemption Rates from 2000-2015 in Mariposa, Nevada, and Trinity Counties](https://infogram.com/kindergarten-vaccination-exemption-rates-in-california-from-2000-2015-1h7g6k09wxmro2o?live)

<img width="639" alt="Screen Shot 2021-08-12 at 01 10 06" src="https://user-images.githubusercontent.com/87747630/129161834-c0aac4e4-3832-4172-806e-1e41907e8e7a.png">

<img width="625" alt="Screen Shot 2021-08-12 at 01 07 48" src="https://user-images.githubusercontent.com/87747630/129161521-5b17ddd1-79ab-43b5-9bbd-ac0ee441f9fb.png">

## Data Analysis Process
The first step of my analysis was to clean the data. After inspection, the data did not require much refining as it was mostly normalized. Because my scope of analysis did not require school names and this column of data exhibited significant inconsistencies, I created a [new spreadsheet](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=131514056) without it for my analysis. I also introduced five new variables: 1) pMMR, 2) pDTP, 3) pPolio, 4) pPBE, and 5) pPME. Details on column headers can be found [here](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=2141576536).

The scope of my analysis sought to answer the following questions:
1) What was the total exemption rate in 2000? In 2015? How did the two years compare?
2) Which counties had the highest vaccination exemption rates in 2000? In 2015? 
3) For public schools, what percentage of kindergarteners completed their MMR, DTP, and Polio vaccinations in 2000 and 2015? For private schools? How do they compare?
4) Which counties exhibited the greatest increase in exemption rate in 2015 compared to 2000 data?
5) Which counties had the lowest vaccination rates for MMR, DTP, and Polio in 2015?
6) Which counties had the highest standard deviation in vaccination rates for MMR, DTP, and Polio in 2015?
7) Which vaccine demonstrated the greatest standard deviation in vaccination rate across the state in 2015?

Key assumptions for analysis:
* All questions were answered solely using the data set mentioned above.
* Vaccination rate is defined as the percentage of students vaccinated for each respective vaccine type from the total number of students in the school type, county, or year specified in the question.
* Exemption rate is defined as the percentage of students with an exemption (PBE or PME) from the total number of students in the school type, county, or year specified in the question.

Answers to my data analysis:
1) What was the total exemption rate in 2000? In 2015? How did the two years compare?

First, I created a [pivot table](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=813051499) that summed up the total number of PBE and PME exemptions, and the number of reported kindergarten students in 2000 and 2015.

<img width="468" alt="1_1" src="https://user-images.githubusercontent.com/87747630/129158206-7075e6a5-2b29-4b09-9d83-03329cc87b29.png">

Then I copied the pivot table’s values into [another spreadsheet](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=280452227) and found the total number of exemptions in 2000 by summing the total number of PBE and PME exemptions. I determined the exemption rate by dividing the total number of exemptions by the total number of students and multiplying the resulting value by 100. 

<img width="468" alt="1_2" src="https://user-images.githubusercontent.com/87747630/129158207-3f6c3e9b-c6f1-4ad1-ac3a-93944a322669.png">

> The total exemption rates in 2000 and 2015 were 0.842% and 2.498% respectively. The total exemption rate increased by 1.656% from 2000 to 2015 with a notable increase in personal belief exemptions from inspection. 

2) Which counties had the highest vaccination exemption rates in 2000? In 2015? 

I created a [pivot table](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=1539983966) that summed the total number of PBE and PME exemptions, and the number of reported kindergarten students for every county in California in 2000 and 2015.

<img width="468" alt="2_1" src="https://user-images.githubusercontent.com/87747630/129158209-300daad4-734b-4a68-8162-11c3ed644589.png">

I copied the values to a [new spreadsheet](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=322148175) and summed the total number of PBE and PME exemptions to get the total number of exemptions per county. Then, I calculated the percentage of  kindergarteners with exemptions for each county based on the total number of kindergarteners per county. Finally, I sorted the vaccination exemption rates in descending fashion to determine the counties with the highest rates. 

<img width="468" alt="2_2" src="https://user-images.githubusercontent.com/87747630/129158211-bfd450dc-f3fd-4c5b-a4de-4c4c396f14d6.png">

> In 2000, the counties with the highest exemption rates were Nevada, Trinity, and Modoc.

<img width="468" alt="2_3" src="https://user-images.githubusercontent.com/87747630/129158212-66a4d07a-bf53-43b5-b23b-c872ede739a1.png">

> In 2015, the counties with the highest exemption rates were Nevada, Trinity, and Mariposa. 

3) Which counties exhibited the greatest increase in exemption rate in 2015 compared to 2000 data?

I used the same values from the [old spreadsheet](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=322148175) in question 2 and pasted it into a new spreadsheet. In this [new spreadsheet](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=639338057), I deleted unnecessary columns and subtracted the exemption rates for 2000 from the 2015 counterpart for each county. Finally, I sorted the exemption rates based on descending values and reported the counties with the largest percentage increase in exemptions.

<img width="468" alt="3_1" src="https://user-images.githubusercontent.com/87747630/129158213-b9736999-25d6-46d7-90a0-225e93b9b6fb.png">

> The counties that exhibited the greatest increase in exemption rate in 2015 compared to 2000 were Nevada, Trinity, and Mariposa.

4) For public schools, what percentage of kindergarteners completed their MMR, DTP, and Polio vaccinations in 2000 and 2015? For private schools? How do they compare?

I created a [pivot table](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=1373690576) that for each school type (public and private), reported the sum of total kindergarteners and the total number of children with completed MMR, DTP, and Polio vaccinations in 2000 and 2015. 

<img width="468" alt="4_1" src="https://user-images.githubusercontent.com/87747630/129158216-2b19d9ca-ad8e-45fe-b634-230e3ba96518.png">

I copied the values to a [new spreadsheet](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=30241331) and determined the percentage of children who received each vaccination type from the total number of kindergarteners for each school type. 

<img width="468" alt="4_2" src="https://user-images.githubusercontent.com/87747630/129158217-12c8eb3b-36d7-44fe-ba2b-dcc97621eb3b.png">

> In 2000, private schools had vaccination rates of 92.252%, 93.331%, and 93.619% for the MMR, DTP, and Polio vaccines respectively. The same year, public schools had vaccination rates of 95.989%, 95.765%, and 96.451% for the MMR, DTP, and Polio vaccines respectively.

> In 2015, private schools had vaccination rates of 90.697%, 90.610%, and 90.903% for the MMR, DTP, and Polio vaccines respectively. The same year, public schools had vaccination rates of 94.896%, 94.538%, and 95.069% for the MMR, DTP, and Polio vaccines respectively.

> Private schools had lower vaccination rates than public schools in both 2000 and 2015. Private and public schools both decreased their vaccination rates overall in 2015 compared to 2000. 

5) Which counties had the lowest vaccination rates for MMR, DTP, and Polio in 2015?
	
I created a [pivot table](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=407531506) that reported the total number of kindergarteners and the total number of children who completed MMR, DTP, and Polio vaccinations in 2015 for each county. 

<img width="468" alt="5_1" src="https://user-images.githubusercontent.com/87747630/129158219-17b91220-5fe7-4885-a3b6-194294631e38.png">

I copied the values from this table and pasted them into a [new spreadsheet](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=944171930). I calculated the vaccination rates by determining the percentage of kindergarten children receiving each vaccination type from the total number of enrolled students in 2015. Finally, I sorted the vaccination rates for each vaccine type in ascending order to identify the counties with the lowest vaccination rates for MMR, DTP, and Polio independently.

<img width="468" alt="5_2" src="https://user-images.githubusercontent.com/87747630/129158221-aa216275-4980-4281-b6ab-c98f6c95b820.png">

>In 2015, Trinity, Nevada, and Tuolumne were the three counties with the lowest vaccination rates for MMR.

<img width="468" alt="5_3" src="https://user-images.githubusercontent.com/87747630/129158224-89034c71-76a9-4a5e-b174-8182ea906394.png">

>In 2015, Trinity, Nevada, and Mariposa were the three counties with the lowest vaccination rates for DTP.

<img width="468" alt="5_4" src="https://user-images.githubusercontent.com/87747630/129158227-b02ccc95-d099-44e5-b7ce-ba6e927da2b8.png">

>In 2015, Trinity, Nevada, and Tuolumne were the three counties with the lowest vaccination rates for MMR.

6) Which counties had the highest standard deviation in vaccination rates for MMR, DTP, and Polio in 2015?

I created a [pivot table](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=228190039) that, for every county, displayed the standard deviation in percentage of kindergarteners receiving the MMR, DTP, and Polio vaccines in 2015. 

<img width="468" alt="6_1" src="https://user-images.githubusercontent.com/87747630/129158229-3ef11d68-08b7-4dfa-9652-1fbae0b62d3c.png">

I copied the values of this table into a [new spreadsheet](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=1069321620) and sorted the standard deviations in a descending fashion to determine the counties with the highest variation per vaccine type.

<img width="314" alt="6_2" src="https://user-images.githubusercontent.com/87747630/129158234-d79fcb5d-8b83-446b-b72f-a6b67ea1d722.png">

>In 2015, Lassen, Tuolumne, and Nevada counties had the greatest standard deviation in the percentage of reported kindergarteners who completed MMR vaccinations.

<img width="329" alt="6_3" src="https://user-images.githubusercontent.com/87747630/129158235-2f898c47-b7f0-465f-8d80-0a6471ed84db.png">

>In 2015, Lassen, Nevada, and Mariposa counties had the greatest standard deviation in the percentage of reported kindergarteners who completed DTP vaccinations.

<img width="377" alt="6_4" src="https://user-images.githubusercontent.com/87747630/129158236-17e5d647-5fa3-49a6-873b-4c2746332840.png">

>In 2015, Lassen, Nevada, and Mendocino counties had the greatest standard deviation in the percentage of reported kindergarteners who completed Polio vaccinations.

7) Which vaccine demonstrated the greatest standard deviation in vaccination rate across the state in 2015?

Using the spreadsheet in question 5 that detailed the vaccination rates for each vaccine type for each county in 2015, I calculated the [standard deviation](https://docs.google.com/spreadsheets/d/11xsReMhUc88-CZwxbBA9uzRk7Lcp6k9Zb3dHJlJGuZs/edit#gid=1591613893)across every county for each vaccine type. 

<img width="468" alt="7_1" src="https://user-images.githubusercontent.com/87747630/129158237-b7af4d89-f617-4f5a-b689-9b6361166b2f.png">

> The DTP vaccine demonstrated the greatest standard deviation across all counties in 2015.







