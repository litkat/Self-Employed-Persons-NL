# Self-Employed-Persons-NL   

## Goal ##   
Analyze self-employment trends from 2011 to 2020 in the Netherlands to find out the situation with self-employment for women in top 3 of the most profitable industries.   

## The data sources ##   
The information for this project is based on open data made available by a [StatLine](https://opendata.cbs.nl/#/CBS/nl/) the database of Statistics in the Netherlands. This source contains statistics regarding income and capital of self-employed persons in the Netherlands for whom self-employment provides for the main source of income. The figures in this table are broken down by type of self-employed person, sector, gender, age, migration background, position in the household.   

## A summary of data processing for this project can be viewed here: ##   
**1.** Formulate question   
**2.** [Find data](https://opendata.cbs.nl/statline/portal.html?_la=en&_catalog=CBS&tableId=84466ENG&_theme=1070)   
**3.** [Gather and store clean data in both a .csv file and a MySQL Workbench DB](project_files/gather_data_self-employed_persons.ipynb)   
**4.** [Exploratory Analysis, reading clean data from MySQL Workbench DB](project_files/eda_self-empl.ipynb)   
**5.** [Create and test hypothesis](project_files/hypothesis_testing.ipynb)   
**6.** [Build a Machine Learning model](project_files/model.ipynb)   
**7.** [Create a presentation for an external audience using Tableau](https://public.tableau.com/app/profile/ekaterina.litvinova/viz/Self-Employed-Persons-NL/Self-Employed-Persons-NL?publish=yes)   

## Results ##
**Top 3 of the most profitable industries**   
  
![Top 3 of the most profitable industries](/project_files/images/profitable_industries.png)   

I sorted the industries by the average self-employment income and the top 3 are **_Health and Social work_**, **_Financial Institutions_** and **_Specialized Business Services_**. 

**How many women work in each of these 3 industries and if there are any specific trends?**   

![How many women work in each of these 3 industries](/project_files/images/gender_trends.png)  

Interesting enough, the graph shows that in **_Health and Social industry_** there is much more women than men and the difference increased in past 10 years. What is even more interesting is that there is a huge difference in **_Financial Institutions_**. The number of self-employed women in this industry stays the same for 10 past years and in 2019 was six times lower than the number of self-employed men. For **_Specialized services_** category the difference is also big, but the growth trend is almost the same for men and women. Also we can see a break in the trends in 2020.   
According to the data source, the numbers are finalized for 2020, so the drop in self-employment due to Covid looks very clear.   

**What is the average self-employment income for women in these industries?**   

![average self-employment income for women in these industries](/project_files/images/Income_trends_gender.png)  

We can see, that on average women earn twice as less than men in the same industries, even though there is much more women in **_Health and Social services_**. Income in **_Financial Institutions_** grows for women over past 10 years and is the highest in 2020.   

**Let’s now see where the women of my age group (25 to 34) work the most and what are the trends?**   

![women of my age group](/project_files/images/number_self_eml_women_by_age.png)   

Not surprising that it is the **_Health industry_** and it was growing fast before Covid. There is almost no women of my age in **_Financial Institutions_** and, as we saw before, the number didn’t change for 10 years. Looks like there’s no women between 25 and 34 left there in 2020. The number is growing for **_Specialized Business services_**.   

**Is there any difference in income among women depending on age?**   

![women depending on age](/project_files/images/women_income_by_age.png)   

The patterns are almost the same for these three industries, but it looks like the highest salary for a woman between 25 and 34 years is in the **_Financial Institutions_**.   

**Conclusion**   
Considering that **_Financial Institutions_** is also an industry with the lowest number of self-employed women, I think this will be my choice 😊
