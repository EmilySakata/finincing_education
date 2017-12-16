## Financing Education 

## Background

Many of us consider enducation as an important investment for our future well being and particularly an integral part of what government spends for thier citizens to realizing the vision of the coiuntry where all people have a chance to make the most of thier talents. 

But how important is education compared to the other social services that our government provides? 
Are government effictive in providing equal opportunity for all citizens to get educated?

With the ammount of money our government spend, are citizens receiving the level of quality services?
As a result of the education, are we able to achieve the level of income to sustain our living?

In order to answer to those high level questions, we grouped our data analysis into below 3 categories: 

1) Education spending trend  
Key questions:
 
   - How important is the education in relations to public policy?
   - What is the source of education funding?
 
 2) Education equality and effectiveness  
 Key questions:
  		  
   - Are all US citizens receiving education equally?
   - What type of education are they receiving? Teacher effectiveness?
 		  
 3) Education funding effectiveness  
 Key questions:
  		  
   - How much student loans are students taking out?
   - What percentage of household income is spent on education?
   - What is the outcome of education? How much does education impact the future income?
  		  
  		  
  Here are the high level steps we took to analyze the data: 		





* placeholder for a good data visualization image 
![ScatterPlot.png](https://github.com/EmilySakata/d3_census/blob/master/ScatterPlot.png)



In order to understand how education is financed, and what type of impact it has to the targeted demographics, we broke our analysis down into three category of areas to answer the above questions.




Here are the high level steps we took to analyze the data: 

1) Data gathering

Look for demographic information using the 2014 one-year estimates from the U.S. Census Bureau's American Community Survey. You can specify your information using the American FactFinder tool. When searching through the data, be sure to select these options in the left sidebar(http://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml):
Topics -> Dataset -> 2014 ACS 1-year estimates
Geographies -> Select a geographic type -> State - 040 -> All States within United States and Puerto Rico

Next, you'll search for data on health risks using 2014 survey data from the Behavioral Risk Factor Surveillance System. 
(https://chronicdata.cdc.gov/Behavioral-Risk-Factors/BRFSS-2014-Overall/5ra3-ixqq)

2) Data formatting

For the two data types chosen, grab the value columns from each and paste them into a new Excel document. Create header names that you can easily call with JavaScript (concise, lowercased, camelCased). Make sure that your rows and columns line up—You may need to delete Guam from your datasheet so that your Census and BRFSS data matches.

3) Visualization

Create a scatter plot that represents each state with circle elements. 
Scatter plot has:
  The x-values of the circles should match the demographic census data, while the y-values should represent the risk data.
  Include state abbreviations in the circles.

4) iframe-html

Embed it in index.html with an iframe to plot your d3 scatter plot. 

In order to execute the html, run the server localy by using the following command in your terminal
-m http.server <local host address>


## Contributors


Daniel Saw      | https://github.com/dsdata1

Emily Sakata    | https://github.com/EmilySakata

Prateek Gupto 	| https://github.com/pgupto

Denis Sorokin 	| https://github.com/xprntl

-------------------------------------------------------------


## Technology Used

- Postgres SQL
- Python
- Excel, csv
- Jupyter Notebook
- Machine Learning ( Linear regression)
- Google Data Studio
- Tableau
- HTML,CSS


Tableau Link: https://public.tableau.com/profile/daniel.saw#!/

## Data Source:


<b>Educational attainment of the population 18 years and over, by age, sex, race, and hispanic origin</b>

Data Source: US census   
Description of available measures: Information on educational attainment, for over 18 years of age on all races.  
Time span: 2016  
Geographical coverage: U.S.  
Link: https://www.census.gov/data/tables/2016/demo/education-attainment/cps-detailed-tables.html  


<b>A Half - Centry of Learning: Historical Statustics on Educational Attainment in the United States, 1940 to 2000: tables  </b>
Data Source: US census:   
escription of available measures: Percent population 25 years and older with high school diploma or highter and bachelar degree and higher in US between 1940 to 2000. Table 1 and 2. In repo titled as "Historical_edu_attainmentinUS_Bachelors.xls" and "Historical_edu_attainmentinUS_Highschool.xls". For ease of data use of the project, both tables are manually combined and titled as "historical_edu_attainment_percent.csv"  
Time span: 1940 to 2000  
Geographical coverage: U.S.  
Link:https://www.census.gov/data/tables/time-series/demo/educational-attainment/educational-attainment-1940-2000.html  


<b>College enrollment in the United States from 1965 to 2015 and projections up to 2026 for public and private colleges (in millions)  </b>
Data Source: NCES  
escription of available measures: College enrollment data for public and private schools in US.
Time span: 1965-2015  
Geographical coverage: U.S.    
Link: https://www.statista.com/statistics/183995/us-college-enrollment-and-projections-in-public-and-private-institutions/

<b> Public and private expenditure on educational institutions as a percentage of GDP</b>
 Data Source: OECD
 Description of available measures: Public and Private spending on education as percentage of GDP for various countries
 Time span: 2013
 Link: http://www.oecd-ilibrary.org/education/education-at-a-glance-2016_eag-2016-en
 
 <b> Unemployment rate by Educational Attainment </b>
 Data Source: BLS
 Description of available measures: Unemployment rates vs various level of educational in the US over time
 Time span: 2005-2015
 Link: https://www.bls.gov/opub/ted/2015/unemployment-rates-by-educational-attainment-in-april-2015.htm
 
 <b>Graduation Rate</b>
 Date Source: NCHEMS
 Description of available measures: Graduation rate by state over the year
 Time span: 2010-2015
Link: http://www.higheredinfo.org/dbrowser/index.php?measure=19


<b>Education Inequality Report</b>
Data Source: NIH
Description: Inequality in Teaching and Schooling: How opportunity is Rationed to Students of Color in America
Time span: 2001
Link: https://www.ncbi.nlm.nih.gov/books/NBK223640/

<b> Civil Rights Data Collection</b>
 Data Source: CRDC
 Description: The CRDC collects a variety of information including student enrollment and educational programs and services, most of which is disaggregated by race/ethnicity, sex, limited English proficiency, and disability.  
 Time span: 2013-2014
 Link: https://www2.ed.gov/about/offices/list/ocr/docs/crdc-2013-14.html
              
 <b>US college Enrollment Statistics for Public and Private Colleges</b>
 Data Source: Statista
 Description: College enrollement for Public and private and public colleges over the year with forecast to 2026
 Time span: 1965 to 2014
 Link: https://www.statista.com/statistics/183995/us-college-enrollment-and-projections-in-public-and-private-institutions/
              
<b> Primary & Secondary Education </b>
Data Source: Our World in Data
Description: This data is concerned with Primary and Secondary Education
Time span: 1970 to 2016
Link: https://ourworldindata.org/primary-and-secondary-education

<b> Primary Completion rate </b>
Data Source: UNESCO
Description: Primary completion rate by relevant age group
Time span: 1970 to 2016
Link: https://data.worldbank.org/indicator/SE.PRM.CMPT.ZS



<b>Inequality at School</b>
Data Source: American Psychological Association
Description: What's behind the racial disparity in our Education System?
Time span: 2016
Link: http://www.apa.org/monitor/2016/11/cover-inequality-school.aspx

<b> US Educational Finances </b>
Data Source: Kaggle
Description: Revenues and expenditures for U.S. grade school, by year and state
Time span: 1993 to 2015
Link: https://www.kaggle.com/noriuk/us-educational-finances

<b>County-Level Data Sets</b>
Data Source: USDA
Description: Unempolyment and medium household income as well as population estamates and educational attainment data
Time Span: 1970-2015
Link: https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/


<b> Local Education Agency Finance Survey </b>
Data Source: IES>NCES
Description: Revenue Expenditure data for all school districts in the US
Time Span: 1989-2014
Link: https://nces.ed.gov/ccd/f33agency.asp


<b>CIVIL RIGHTS DATA COLLECTION</b>
 Data Source: CRDA
 Descriptions: Key data highlights on Equity and opportunity gaps in our nation's public schools
 Time Span: 2013-14
Link: https://www2.ed.gov/about/offices/list/ocr/docs/2013-14-first-look.pdf

<b> Census Data </b>
Data Source: US Census
Description: Census data
Time Span:
Link: https://www.census.gov/data.html

<b>Student Loans by State</b>
Data Source: college-insight
Description: data on studentloans, graduation level, average debt by state
Time Span: 2010-15
 Link: http://college-insight.org/#explore/go&h=20b58c75248e62c2bfd642dd2cc35c0e
 Link: http://college-insight.org/#explore/go&h=390205a77fbe809c34e44b4c9de3ee9d
 
 <b> Income level vs educational attainment </b>
 Data source: nces
 Time Span: 2000-15
 Description: data on income level and education attainment
 Link: https://nces.ed.gov/programs/coe/indicator_cba.asp
