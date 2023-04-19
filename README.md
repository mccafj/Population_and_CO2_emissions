# Population_and_CO2_emissions
R | Excel | Etc

This project started out with the purpose of translating basic skills from Python over to R after completing a __[Google course on R](https://www.coursera.org/account/accomplishments/verify/5VHN7T9WNPZH)__.  And though I enjoyed becoming more familiar with R Studio, I think I ended up spending more time in Excel cleaning & re-formatting spreadsheets than spending time in R...  Oh well.

Data was obtained from __[ourworldindata.org](ourworldindata.org)__  And thanks to two Excel sources for help in reformatting the spreadsheets __[1](https://www.mrexcel.com/board/threads/how-can-i-reverse-abbreviated-numbers.1143161/)__ and __[2]()__ __[here](https://www.mrexcel.com/board/threads/no-matter-what-i-do-excel-formula-returns-a-date-as-1905.1037386/)__

I also abandoned ggplot2 for visualizations in favor of using Tableau, which was more user friendly for plotting by country vs. year, and filtering to specific countries.  Visuals included below.  I'll aim to start with fewer / better defined variables & simpler graphs in the future and build from there.  

There's no great insights to glean from this project, though I did focus on CO2 emissions and population growth (total and by percentage of change) for the G20 countries and additional OPEC countries.  I included each European Union member separately.  Of note, Qatar, UAE, Kuwait, & Luxembourg are historically very high CO2 emitters PER PERSON. 

![Sheet1](https://github.com/mccafj/Population_and_CO2_emissions/blob/main/images/select_CO2_highlights.png)

Total population estimates 2017:
- Qatar: 2.8M
- UAE: 9.6M
- Kuwait: 4.1M
- Luxembourg: 604K

Otherwise, the more industrialized and populous the country, the more CO2 emissions it was likely to have, which I think we would all surmise.  

Population Growth by Country (1960-2017)

![Sheet2](https://github.com/mccafj/Population_and_CO2_emissions/blob/main/images/pop_growth_country.png)

CO2 Emissions (in tonnes) PER PERSON, select countries from G20 and OPEC

![Sheet3](https://github.com/mccafj/Population_and_CO2_emissions/blob/main/images/select_CO2.png)

Population Change by Percentage, select countries from G20 and OPEC

![Sheet4](https://github.com/mccafj/Population_and_CO2_emissions/blob/main/images/select_pop_growth_percentage.png)


There's some more specific info on the data in the R markdown if you're interested.  

Best,
Jon

jonmccaffrey524@gmail.com
