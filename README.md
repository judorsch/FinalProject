# Examining the Relationship Between Different Economic Indicators and their Effect on Economic Output

#### By: Julianna Dorsch

The purpose of this project is to explore the interactions between different economic factors and how they affect the economic health of the United States.

### Background:

Americans suffer hardships when the economic health of the country is poor but benefit when the economic health of the country is strong.  Therefore, it is important to better understand the various economic factors that affect the health of the economy and how they interact with each other.  This way, economists might be able to advise and warn of looming economic hardship and recommend ways the government or the Federal Reserve can intervene to prevent economic downturns.  The economic indicators this research will be examining are the unemployment rate, the inflation rate, the interest rate, median family income, U.S. government spending, the Dow Jones Industrial Average (DJIA), and the Gross Domestic Product (GDP). The unemployment rate is the percentage of the workforce that does not have a job, the inflation rate is the rate at which prices for goods and services are rising, the interest rate is the rate at which banks borrow from each other, the DJIA is a stock market index tracking the overall strength of the stock market, and GDP is the sum of consumption, investment, government spending, and net exports of a country for a given time period.  

There are generally accepted relationships between these different indicators.  The unemployment rate and inflation typically have an inverse relationship ([Unemployment and Inflation](https://www.investopedia.com/articles/markets/081515/how-inflation-and-unemployment-are-related.asp)). This can be explained by the fact that when unemployment is high, typically wages are low because employers can attract workers to work for a low wage.  Low wages correspond with low prices, meaning inflation is lower.  The opposite explanation applies for explaining the relationship between low unemployment and high inflation.  Unemployment and GDP also have an inverse relationship ([Unemployment and GDP](https://www.investopedia.com/articles/economics/12/okuns-law.asp)).  High unemployment means there is less output, resulting in lower GDP, and vice versa.  Inflation and GDP are directly related ([Inflation and GDP](https://www.investopedia.com/ask/answers/112814/why-does-inflation-increase-gdp-growth.asp)), and this can be caused by a variety of scenarios, one being that a higher demand causes higher prices, meaning inflation and GDP both are higher.  Interest rates and GDP also have a direct relationship ([Interest Rates and GDP](https://saylordotorg.github.io/text_international-economics-theory-and-policy/s21-11-effect-of-a-real-gdp-increase-.html)), as with a higher GDP, the demand for money increases, which results in a higher interest rate.  Income and GDP also have a direct relationship ([Income and GDP](https://www.investopedia.com/ask/answers/060115/how-does-gross-domestic-product-gdp-affect-standard-living.asp#:~:text=Gross%20domestic%20product%20(GDP)%20measures,economy%20in%20a%20given%20period.)) because part of GDP is determined by consumer spending and with higher income, there is more consumer consumption.  Government spending and GDP are also directly related as part of GDP is determined by government spending ([Government Spending and GDP](https://www.investopedia.com/ask/answers/060115/how-does-gross-domestic-product-gdp-affect-standard-living.asp#:~:text=Gross%20domestic%20product%20(GDP)%20measures,economy%20in%20a%20given%20period.)).  Lastly, the DJIA and GDP are also directly related because increases in the DJIA cause increase in confidence, which will cause increase in spending and therefore GDP ([DJIA and GDP](https://www.investopedia.com/ask/answers/033015/how-does-stock-market-affect-gross-domestic-product-gdp.asp)).  During this research, these indicators will be examined to determine if there are periods of time when the described relationships are true and if there are periods of time when the described relationships are false. The strength of the relationship will also be examined. Additionally, this research will examine if a regression line can be found that relates GDP to the other indicators.  By doing so, economists will be more effective in warning about economic recessions.

### Questions to be Answered:

* What is the strength of the correlation between the different economic indicators discussed above when the generally accepted relationships hold?
* What is the strength of the correlation between the different economic indicators discussed above when the generally accepted relationships do not hold?
* Is it possible to find a regression line with a small residual to describe the relationship between the economic indicators and GDP? 

The first question is important to address to confirm the strength of the relationships that were previously discussed.  If it is found that these correlations coefficients are relatively strong and occur a majority of the time, this will make it easier to determine how strong of an effect the different economic indicators have on GDP, which would be helpful when answering the third question.

The second question is important to examine because it will determine not only how often the relationships discussed above are violated, but it will also clarify if it was a severe violation of the relationship, which would be indicated by a coefficient that has the opposite sign with an aboslute value closer to 1, or a slight violation which would be indicated by a coefficient value near 0.  

The third question is important to address because if a regression line with a low residual value can be found, it could be helpful in determining future trends of the health of the U.S. economy.  It will also be helpful in determining what is the overall shape of economic growth.  These growth patterns could include but are not limited to linear, quadratic, exponential, logarithmic, or periodic.  

### Dataset Links:

* [Unemployment Rate Since 1948](https://beta.bls.gov/dataViewer/view/timeseries/LNS14000000)
* [Inflation Rate Since 1914](https://www.usinflationcalculator.com/inflation/historical-inflation-rates/)
* [Interest Rate Since 1950](https://fred.stlouisfed.org/series/INTDSRUSM193N)
* [Dow Jones Industrial Average Historical Prices](https://www.wsj.com/market-data/quotes/index/DJIA/historical-prices)
* [Real GDP](https://fred.stlouisfed.org/series/A191RL1Q225SBEA)
* [Median Family Income](https://fred.stlouisfed.org/series/MEFAINUSA646N)
* [Government Spending](https://www.whitehouse.gov/omb/historical-tables/) Tables 14-2 and 14-3

The above datasets, going from top to bottom, reflect the following:

* The total unemployment rate in the United States since 1948
* The inflation rate in the U.S. since 1914
* The interest rate in the U.S. since 1950.  The interest rate is set by the Federal Reserve and determines the interest rate that is used for banks.  
* The historical prices of the DJIA, which is an index that tracks the 30 largest publicly traded companies and the value of their stock.
* Percent change in real GDP per quarter.  It is important to use real values over nominal values because real values account for inflation.
* Median Family Income, which tracks what the median income in the U.S. for a family.  The median is the important center statistic to use when tracking income because the top earners who make large sums of money and the bottom earners who perhaps make no money will not affect the calculation of the middle substantially.
* Government spending per year in billions of dollars since 1948.

This analysis will be conducted for the indicators since 1950.

### Ethics:

This research is studying the U.S. economy, which directly impacts the standard of living of every American, so any research conducted should be done cautiously.  The overall purpose of this research is to determine if trends can be tracked in the overall economy so that future economic downturns can be predicted and therefore prevented through government or Federal Reserve intervention.  This research could be used by individuals who after predicting a financial downturn, are then able to change their financial situation so that they are not as severely negatively impacted by the downturn.  This could also be used by government officials to help ensure that the overall quality of life for Americans does not decrease by trying to either dampen or fully prevent the effects of the downturn when it is forecasted.  However, this research could also be potentially used by people or groups wishing to exploit individuals.  With the knowledge of a potential economic downturn, these people and groups could exploit unaware individuals, thereby strengthening their financial situation while harming individuals who then would be even more exposed to the effects of a recession.