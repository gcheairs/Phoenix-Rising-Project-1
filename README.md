# Phoenix-Rising-Project-1


# Notes and citations - Gi'Anna

# Presentation Notes

My portion of the analysis focused on the most and least costly insulin by manufacturer. In order to have a more accurate comparison, we used the average cost, by summing the insulin spend and dividing by the number of doses.
Slide 1
•	Avg cost per dosage ranged from $2.81 to $33.83
•	2 most expensive insulin producers were Eli Lilley ($31 - $33 from 2019-2021) and Novo Nordisk ($34 remained consistent)
•	Cheapest was Novo Nordisk-Wa ($2.81 - $3.56 from 2019 - 2021). 
•	Novo Nordisk is a global healthcare company HQ in Denmark. They have many global subsidiaries. Novo Nordisk-Wa is a subsidiary with HQ in Seattle, WA. https://www.biospace.com/employer/531392/novo-nordisk-wa-/	

Slide 2
•	As stated before, the 2 most expensive insulin producers were Eli Lilley and Novo Nordisk. They produced 2 insulin types 
•	Insulin lispro - fast-acting type of insulin; begins to exert its effects within 15 minutes of subcutaneous administration, peaks within 30-90 minutes and lasts approximately 5 hours (https://www.aafp.org/pubs/afp/issues/1998/0115/p279.html#:~:text=Insulin%20lispro%20begins%20to%20exert,is%20less%20than%20five%20hours.)	
•	insulin aspart - is a fast-acting, type of insulin; begins to exert its effects within 5 - 10 minutes of subcutaneous administration, peaks within 1 - 3 hours and lasts approximately 5 hours. (https://www.aafp.org/pubs/afp/issues/2004/1201/p2081.html)
•	Insulin lispro and insulin aspart - Both are fast acting types of insulin that start to exert affects within 5 – 15 minutes of administration, peak within 30 minutes – 3 hours and last 4-6 hours
•	The cheapest insulin producer was Novo Nordisk-Wa. They produced 
•	‘insulin Regular, Human’ - is a short-acting insulin that takes 30 minutes to 1 hour to start working, peaks within 2-5 hours and lasts up to 6 hours (https://www.drugs.com/insulin-regular.html)	
•	Insulin aspart and insulin lispro come in at around the same price point of $58, while regular human insulin is about half the price at $29 (per 10 ml) (https://www.aafp.org/pubs/afp/issues/2004/1201/p2081.html)
•	Hypothesis -  insulin aspart and lispro are so much costlier because their onset is about 6 X faster and it takes about half the time to reach its peak effectiveness. Which can be life changing in a diabetic emergency. This is what is driving the huge cost difference.

# Notes and citations - Timothy

https://www.cbo.gov/publication/57126

https://data.cms.gov/summary-statistics-on-use-and-payments/medicare-medicaid-spending-by-drug/medicare-part-d-spending-by-drug/data

Inflation reduction act - https://phrma.org/inflation-reduction-act?utm_campaign=2023-q3-pri-v6&utm_medium=pai_srh_cpc-ggl-adf&utm_source=ggl&utm_content=clk-pat-v6-v6-v6-all-pai_srh_cpc-ggl-adf-IRAEvergreenSearchWCNational1-evg-v6-v6-lrm-soc_txt-v6-vra-adf&gclid=Cj0KCQiA1rSsBhDHARIsANB4EJZX00BkYpjbpbdC5yHMgeZrEZCXQGN2fdHzqMRBpJW21JzI17iCOdAaAshHEALw_wcB


# Notes and citations - Cristian

https://fred.stlouisfed.org/series/FPCPITOTLZGUSA

# Notes and citations - Betsy

**Objective and Scope**
​ Our objective was to understand how Medicare manufacturing costs impacted benefits through Medicare spending for Insulin medication from 2019-2021. We looked at dosage distribution, spending, and how beneficiaries and costs are correlated with the cost of living. 
​ The scope was working with a data set that looked at Medicare Part D spending by Drug from 2019-2021. We specifically looked at Insulin data for the top four insulin medications which are 'Insulin Glulisine','Insulin Lispro', 'Insulin Aspart','Insulin Regular, Human'
​ The Questions we were looking to address are. Who were the top Insulin distributors through medicare, Which manufacturers spent the most on insulin production? Who’s insulin cost the least? How much did Medicare spend on insulin for beneficiaries? Overall trends in beneficiaries for insulin distribution? If there was a correlation between the spending on insulin variation with the rising cost of living?

**Approach and Cleaning the data**
​ Created dataframes, explored the columns, cut down the years from 2017-2021 to only look at 2019-2021 [Due to missing data for the years in 2017 & 2018 for manufacturers]
Cleaned up NA’s, obtained the dtypes, transformed the data to more user friendly numbers, renamed columns. 

**Why is this important**
​ Each year the Pharmaceutical Industry develops a variety of new drugs that provide valuable medical benefits. Many of these drugs are considered expensive and contribute to rising health care costs for the private sector and the federal government. Policymakers have considered policies that would lower drug prices and reduce federal drug expenditures. Such policies have the grave potential to reduce the industry’s incentive to develop new drugs.
Machine Learning has the ability to address various challenges in the HealthCare Industry and one being Manufacturing and Distribution Cost. Drug discovery has long been one of the most major challenges for Pharmaceutical and Biotech Companies. The expected cost to develop a new drug has been estimated to range from more than $1 to $2 billion.

**Total Data Values and Top Insulin Manufacturer**
​ We started by looking at the overall data, here we are looking at the Mean and median spending values in dollars by year. You can see a more significant decrease from 2019 to 2020 on the mean chart with a difference of 50 million dollars from 2019 to 2020, and a  5 million dollar decrease from 2020 to 2021. The Median is slightly less dramatic across the three years with the biggest difference in median spending values from 2020 to 2021 with about a 10 million difference. 
​ Dosages follow a very similar pattern with the highest year of dosage units in 2019 with 8 million dosage units to 2020 and 2021 where there was only about a 1 million dosage difference. Showing that dosage distribution is linked to manufacturing spending. 
​ Plotting the standard deviation for spending and dosages. On the left blue line is the standard deviation for spending from 2019-2021, with a slight negative curve from 2019 to 2020 indicating the standard deviation is fairly large in relation to the mean for spending data.  
​ The orange line plots the standard deviation for the dosage data, with almost a flat line indicating the standard deviation is higher than average and a more spread out data set in relation to the mean for dosage data. 
​ Now that we were oriented in the overall data we started drilling into the more detailed questions. The first question is who were the top insulin producers. To get that we took the average insulin production across 2019-2021 and plotted out where they fell. Far and away Novo Nordisk and Eli Lilly & Co with an average production of over 70 million dosage units from 2019-2021 outpaced the next 3 manufacturers that didn’t break 10 million in average production. The conclusion we drew was that the top producers aren’t necessarily benefiting from economies of scale when it comes to their average dosage price. 