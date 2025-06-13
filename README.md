# US-Economy-Insights-With-Time-Series
In this project, we will be utilizing the Federal Reserve Economic Data API to scrape, analyze, and forecast data regarding key aspects of the American economy, ranging from Gross Domestic Product (GDP), inflation, and unemployment. This project consists of two parts, Exploratory Data Analysis, aswell as time series forecasting which uses Autoregressive Integrated Moving Average(ARIMA) models.


# Gross Domestic Product
Gross Domestic Product is one of the most important economic indicators for how a country's economy is doing. It shows a comprehensive measure of economic activities and is a monetary measure of the total market value of goods and services every quarter. From the late 1940s to the late 1970s, growth was consistent but relatively slow. In the 1980's however, GDP started growing at a pace faster than ever, which would continue. Often known as the "Reagan Boom," this growth started with massive tax cuts, deregulations, aswell as a growing tech industry. Also, globalization slowly grew, expanding the scales of many companies. After the large 2020 "Covid dip", the GDP recovered quickly at great rates due to the reopening of businesses and jobs, stimulus checks, and pent-up demand. The percent change in GDP in recent quarters has been going down due to slower productivity from the post-covid boom, and tariffs and trade tensions from the Trump Administration.


# Consumer Price Index and Inflation
![Image](https://github.com/user-attachments/assets/8b1f5d6e-ccff-4479-afa7-bb8b90e37738)

CPI and Inflation are two terms that are similar but different. CPI is an essential factor for determining inflation rates, but is more specifically defined as the level of prices of goods and services commonly bought by households. Countries with higher CPIs may have to pay more for key goods and services, whereas countries with lower CPIs pay less. Inflation, on the other hand, is defined as the rate at which goods and services increase. GDP and CPI tend to be very correlated with one another, so the CPI graphs are very similar to the GDP graphs. After the mid-1970s, CPI started growing very fast. This is due to oil embargos, higher wages and unions, and wars. Inflation rates were at nearly 6% in the mid-1970s due to OPEC's embargo and poor management of interest rates. The early 1980s recession then led to the highest inflation in American history at over 6% from the prior period due to the early 1980s recession. The most recent spike in inflation was post-COVID covid where the government spent trillions of dollars on stimulus, aswell as bottlenecks and delays in supply chains.

## Housing
The median price of a home has increased from $20,000 in the 1960s to over $400,000. The large increase in recent years is primarily due to supply issues, where demand for housing exceeds the available supply.
The rate at which housing prices changed has been relatively similar to the inflation rate aswell.


# Income and Spending
In this section, we looked at Personal Disposable Income(PDI), Personal Consumer Expenditures(PCE), aswell as income and wages between demographic groups.

## PCE vs PDI
Do people make more than they spend? From just these two metrics, yes. Generally, over time, PDI and PCE have both increased, with people currently having a disposable income of over $20000. However, PCE has increased at the same rate. The gap between the graphs indicates money left for savings and non-immediate purchases.
Note: Neither metric is adjusted for inflation, which means the data simply reflects the median raw dollar amount during these years. Also, there are many other metrics that need to be taken into account to show if people are truly making more than the median Personal Consumer Expenditure rate.

## Weekly Income for College Graduates and Non-College Graduates.
![Image](https://github.com/user-attachments/assets/efe82288-1b88-4b64-b99a-f1d906c7ba28)

Moving on, to answer the commonly asked question, do college grads make more money? The answer is yes, as seen from the graph displays weekly pre-tax and deduction incomes for both groups over time. This shows that higher education can equate to a higher chance of financial stability; however, prices of tuition have increased by over 60% since 2000, meaning many college grads come out of college with debt(average of $27000), which can take longer to pay off.

## Minimum Wage
The first map visualization of this project shows the minimum wage of every state in 2025. Now, some states(Alabama, South Carolina, Tennessee, Louisiana, Mississippi) don't have a state minimum wage and default to the federal minimum wage of $7.25. Many other states have low minimum wages, like Texas, Pennsylvania, North Carolina, etc. Bigger blue states like California, Washington, New York, and Illinois have the highest minimum wages at or above $15 an hour.


# Employment
In this next section, we look at employment data. Unemployment tends to be cyclical due to changes in the world, like technology, the economy, and more. Most recently, the COVID-19 pandemic closed down many businesses, causing millions to lose their jobs. However, there was steady recovery after the initial boom, which led to the lowest unemployment since the 1960s at 3.4%. Labor Force Participation Rates(LFPR) are also another very important indicator showing how many people of the civilian population are working. Currently, the average LFPR is at the lowest level since the 1970s. This is because of an aging population, and the youth not working as much, with changes in behavioral health and personal beliefs. 

### Unemployment by Education Level
As mentioned earlier, college-educated people generally earn more, but from the graph in the subplot, we see they are also less likely to be unemployed. College-educated individuals typically have higher-demand skills, and many employers specifically look for college degrees on a resume.

### Unemployment by Race
In the graph showing unemployment by race, we see that Blacks and Latinos experience much higher rates of unemployment than Whites and Asians. Some of this is due to systemic issues in society and the workforce, where predominantly Hispanic and Black areas have fewer resources. Also, these individuals can face higher rates of racism and discrimination.

### Unemployment by Age
Unemployment for adults over 24 is generally quite low, but for young people, especially those out of college, rates are much higher than the national average. Reasons for this include that many people in this range look for their first jobs, and generally don't have the same level of experience as older people do. 

## Unemployment by State
The next map of this project looks at unemployment by state. Generally, states with higher populations have higher unemployment rates, such as California, Illinois, Nevada, and Michigan. Unemployment is the highest in Nevada due to the lingering effects of the pandemic and the general structure of its economy being dependent on tourism. Kentucky also experienced extraordinary levels of unemployment, primarily due to the decline in the coal industry. Other states like the Dakotas experience low levels of unemployment due to their business-friendly environment, key sectors like agriculture, and a large number of people who want to work. 

## Labor Force Participation by State
States with low unemployment don't necessarily have high labor force participation. For example, West Virginia's unemployment rate is similar to the national average; however, they have the lowest LFPR in America. This is because of an old population, a young population that doesn't want to work, and a dying coal industry. Coal used to fuel the West Virginia economy, but now it has died down. The state also has a lot of drug issues and drug addiction. 
On the other hand, the Dakotas have high LFPR aswell and low unemployment. This has a lot to due with the Dakotas' strong work culture. 


# Jobs
![Image](https://github.com/user-attachments/assets/af80c512-59ae-4a72-ae8d-280789fbb173)


