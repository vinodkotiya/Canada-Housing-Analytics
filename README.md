# Canada-Housing-Analytics
Data Visualisation and Predictive Analysis for Canada Housing Sector for  Immigrants

**Data:** The Statistics Canada Open License governs the use of free and priced information, regardless of medium, format or reference year, that is published on Statistics Canada's website. Under the Statistics Canada Open License, you are permitted to sell the Statistics Canada data "as is". You may also sell a value-added product you have created using Statistics Canada data under conditions granted in the Statistics Canada Open License.

Total family income and characteristics of residential property owners by family type

**Datasource Link:** https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=4610005101 (1.5 GB)

Household spending, Canada, regions and provinces

**Datasource Link:** https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1110022201 (700KB)

**Primary Audience:** Times are wild. Canadian home prices are so out of control that anyone moving to  Canada would like to see the housing related data before making any life changing decision. 

**Objectives:** Canada’s openness to immigration is pitched as civic-minded global leadership. 
The National Housing Strategy Act (2019) declared that “the right to adequate housing is a fundamental human right affirmed in international law.” Adequate housing is understood as housing that provides secure tenure; is affordable; is habitable; provides access to basic infrastructure; is located close to employment, services and amenities; is accessible for people of all abilities; and is culturally appropriate.

This project focuses on the experience of recent immigrants living in Canada using the following indicators collected and produced by Statistics Canada. These are:  housing affordability, housing suitability, household expenditures, and show the extent of inequalities in housing.

**Plan (Visual and Predictive Analytics):** We have a tentative plan to do Analytics on Multiple-property owners status, Earning comparisons of owners, First time home buyers comparisons, Household expenditure trends province wise, Household expenditure comparison on products etc.

**In continuation to Project report and Data Visualisation Dashboard for showing analytics for Housing and Household expenditure (Demo link). Here we have tried to predict the household expenditure under various head like Food, Shelter, Rent etc for the year 2020 based on the historical data from 2009 to 2019. We have followed these steps:

--Cleaned up data in Tableauprep and uploaded CSV on GITHub (Project link)

--Imported the CSV in Python

--Identified the features for predictions which are year, type of expenditure and amount.

--We tried to increase the datapoint from 10 to 117 by sequencing the expenditure across all provinces.

--Truth or Bluff: Next step was to identify linear regression or polynomial regression to best fit the data.

--Based on R squared value we opted for linear and polynomial regression and developed the prediction model consisting both.

--We have developed both model in a function.

--Read Me File link

Visual Analytics We have made 2 dashboards for clearly explaining the housing scenario for a new immigrant in Canada. For Housing Dashboard Part 1 we have mostly used bar chart and crosstab for giving a comparative analysis of housing cast in different provinces according to family type. We opted for couple, and single family as major immigrants fall into this category, so we discarded the other features from stats Canada data source. For Household Expenditure Dashboard Part 2 we have used bubble chart to show first impression of major annual expenditure to the immigrant. We have used a bar chart to give comparative analysis and a time series chart to show the increase in expenditure under different categories over the year. We again opted for features required for use of immigrants and discarded the irrelevant ones from stats Canada data source.

Housing Dashboard 1  https://public.tableau.com/app/profile/vinod.kotiya/viz/HousingVisualAnalyticsPart1/Dashboard2?publish=yes

Household Expenditure Dashboard 2   https://public.tableau.com/app/profile/vinod.kotiya/viz/HouseholdExpenditurePart2/Dashboard1?publish=yes

Google Colab Predictive Analysis  https://colab.research.google.com/drive/1DoezPxcapqiA0JZB69BuWXn5qAjMefDY#scrollTo=8jgYtLCrpGGQ
