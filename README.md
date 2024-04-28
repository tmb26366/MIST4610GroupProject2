# Group 1 Mist 4610 Group Project 2

## Team Name: 
21484 Group 1

## Team Members:

1. Tim Bondon [@tmb26366](https://www.github.com/tmb26366)
2. Zain Merchant [@zm2231](https://www.github.com/zm2231)
3. Daxton Nell [@daxton-develops](https://www.github.com/daxton-develops)
4. Naseem Shash [@nshash02](https://www.github.com/nshash02)
5. Ethan Varghese [@ethanv12345](https://www.github.com/ethanv12345)
6. Marc Wetherington [@marcwetherington](https://www.github.com/marcwetherington)

## Description of dataset:

Our data set captures the listing date, town, address, assessed value, sales value, sales ratio, property type, residential type, non-use code, assessor remarks, OPM remarks, and exact location for properties sold from 2001-2021 in the state of Connecticut. The data was found in the data catalog for this project and consists of 14 columns and 747 rows. Our data set also includes data types such as whole numbers, date, string data, and decimal numbers. 

## Question 1:

Question: What is the average difference in sales price vs assessed value from 2001 to 2021 for residential and one, two, three, and four-family homes in Connecticut?

Importance: 

This question is particularly interesting and important because it helps us understand market trends and valuation accuracy among these homes. Looking at the difference between assessed values and actual market prices can help us highlight how the economy and market trends, regarding how the housing market affects how much of a premium buyers are paying. For investors and homeowners, understanding the gap between sale prices and assessed values can highlight opportunities to make investments and purchases. Properties that have a lower difference in sales price and assessed price can show which home types and areas could be undervalued, presenting a buying opportunity. On the other hand, homes that have a higher difference show desirable areas, where people are willing to pay more than the assessed value for their home. The relationship between the assessed values and market values can be used as an indicator of economic conditions, which is supported by the huge spike around the 2008 housing crisis.  

![visualization one](https://i.ibb.co/f1fc5ML/graph1.png)

This visualization shows the average/moving average of sale price vs assessed value, or the Premium paid, of  single, two, three, and four family residential properties in Connecticut across 2001-2021. This is indicative of the state of the housing market, as you are able to see the premium on home prices depending on the year and state of the housing market. The premium paid was calculated using the difference between the price paid and the assessed home value. The visualization shows that before the 2008 housing crisis the premium was high, showing how the home market was strong and people were willing to pay more than the home was worth. After the housing crisis, the premium decreased, showing that people were not purchasing homes and the price paid for homes being bought were not sold at a large premium. As of recent years, the premium has been rising significantly, showing many people have been in search of family homes in Connecticut and are willing to pay higher prices for these residential homes

![visualization two](https://i.ibb.co/nDCH5G3/graph2.png)

This visualization shows the average/moving average of sale price vs assessed value, or the Premium paid, of the initially excluded properties, including condos, apartments, industrial and commercial, and private sales of properties in Connecticut across 2001-2021. This is indicative of the state of the housing market, as you are able to see the premium on these varying property types’ prices depending on the year and state of the real estate market. This is indicative of the premiums on the entire real estate market, and shows that they had similar trends and lower premiums than residential homes over certain periods.

## Manipulations applied to the data set for analysis:

The calculations we made on our raw data to produce meaningful visualizations include a calculated field for Premiums paid on homes, which was calculated with (sale value - assessed value). We also filtered out assessor remarks, which is when a sale is not between a willing buyer and seller, is run down, unlivable, destroyed, flooded, with widows, includes wills, warranties, and foreclosures. We placed an additional filter on property type so we could distinguish trends regarding residential homes and other property types. There was another filter on OPM remarks to filter out incorrect sales prices due to private sales and duplicate entries, along with sales made well below market which were suspicious. This left us with valuable data we could analyze. 
For the second visualization, we filtered the foreclosure data to filter out Non Use Codes 18 & 19, a filter on the bankruptcy non use code 13, and Filtered out all instances of private/partial sales to include on public sales. We also filtered the years to include 2006-2010 to focus on the time following the financial crisis. For the visualization comparing the foreclosures of the housing crisis vs the COVID-19 pandemic, we included all years in the dataset (2001-2021) and focused on the periods from 2006-1010 and 2019-2021.

## Question 2:

Question: How did the 2008 financial crisis affect the housing market in Connecticut in terms of Foreclosures, Bankruptcy Sales, and overall Public Sales? 

Importance: 

This question is important because it offers insights into the resilience and adaptability of the housing market during major economic shocks. By evaluating the housing market dynamics during the 2008 financial crisis, we can investigate how the crises influenced foreclosure rates, transaction volumes, and overall market behavior. Through also comparing it with the 2019 pandemic, we can see how the two differing economic approaches had different outcomes, in terms of their effect on the housing market as well as the overall economy. This analysis could be very useful for economists and policymakers as it highlights how external economic influence impacts the housing market. Understanding these relationships aids in predicting future market reactions to economic stress, allowing governments to be more prepared. 

![visualization one](https://i.ibb.co/NWbWwZ4/q2graph1.png)

The financial and housing market crisis had a significant impact on the number of sales, foreclosures, and files for bankruptcy in Connecticut over the years of 2005-2012.  Over the years of 2006-2009, there is a significant increase in home foreclosures, which came due to people being unable to pay their mortgages. The number of public home sales sharply increased before the housing market crash, then rapidly fell at the beginning of the crash in 2006. This rise in home sales was what caused the crash, as banks were handing out loans to people with unqualified credit, which then caused the massive sale on all these homes when they were unable to pay their mortgages, starting around 2005. From the year 2007 until 2009, there is an extreme increase in bankruptcy related real estate transactions in the state of Connecticut among homeowners. These trends are representative of the state of the housing market and economy at this time to show their relevance in teaching the state of the markets in Connecticut. 

![visualization two](https://i.ibb.co/xq06LSz/q2graph2.png)

This bar graph shows the number of home foreclosures in Connecticut from 2001-2021, specifically highlighting the housing market crisis (2006-2011) and the COVID-19 pandemic (2019-2021). This bar graph demonstrates the economic effect that the relief efforts the government put in place had during a time of similar economic crisis. Both periods had many people lose their jobs and find themselves in a position unable to pay rent or mortgage. However, the government provided stimulus checks and a freeze on rent and mortgage payments for up to 18 months during the pandemic to prevent a similar case of mass foreclosure like they had in the housing market crisis. You can see how this dramatically reduced foreclosures in 2020 and 2021, to less than half the amount the previous year in 2019.

## Manipulations applied to the data set for analysis:

For the second visualization, we manipulated the data to get number of foreclosures by filtering Non Use Code where = 18 & 19, a filter on the bankruptcy non use code where it = 13, and filtered out all instances of private/partial sales to include on public sales.

## Tableau packaged workbook

The packaged workbook containing the visualizations shown above is attached to this repository.
