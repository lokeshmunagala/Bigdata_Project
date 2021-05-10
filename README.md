# Effect of COVID-19 on Economy
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/Screen%20Shot%202021-05-06%20at%203.30.06%20PM.png)
#  DATA Used


 #### 1)Covid-19 Data
 #### 2)Share Market, Gold,Oil Data
 #### 3)GDP of USA
 #### 4)Current Population Data[micro CPS]
 
 # DATA CLEANING AND PREPROCESSING
Data gathered from public sources is often riddled with data quality issues such as missing values, missing metadata, duplicate data, inconsistent and invalid entries and so on. Detecting and repairing dirty data is one of the perennial challenges in data analysis, and failure to do so can result in inaccurate analytics and unreliable decisions. As data is gathered from different sources, when multi- ple data sources need to be integrated, the need for data cleaning increases.

After dimensionality reduction of the COVID-19 dataset, next we moved to cleaning of the share market data. Since we are con- sidering the data of the following five countries – USA, India, Italy, China and Spain we had obtained data for the NASDAQ, NIFTY, NSEBANK, FTSE MIB, Hang Seng, Spain IBEX 35 which are few of the major composite indexes for these countries and are represen- tative of the stock market. We performed dimensionality reduction for these datasets along with the datasets we obtained for crude oil and gold prices and trade data as well for these countries as we only wanted to observe and analyze this data side by side with the COVID-19 data along the year 2020.

Acquiring data for the gross domestic product (GDP) for various sectors of the US was a bit challenging as the data acquired was in the form of statistics more than straightforward data entries and required encoding and some manual extraction and its conversion to a csv file. Lastly, we moved to the cleaning of the CPS data that consisted of 12 csv files for 12 months of the year 2020 and had more than 388 columns and 100,000 records per file with column headers and row data for few of those columns encoded in the form of predefined codes that were stored separately in a data dictionary provided by the United States Census Bureau for our reference. We had to go through the entire dictionary to understand what each of those 388 columns represent. It was the most challenging part of the project.

For all the 12 files we performed dimensionality reduction and re-moved records with missing values and checked for invalid entries and inconsistent data after the number of columns were reduced to make sure the data for the analysis was accurate. The data dictionary also had predefined invalid entries that made the process less time consuming however navigating through the dictionary itself and understanding the particular encodings for each value took up most of the time due to the size of the data. The datasets we used for this project consisted of more than 25 csv files amounting to around 1.8 GB of data.


![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/Screen%20Shot%202021-05-06%20at%203.29.55%20PM.png)
#  The Total Cases of COVID-19
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/Screen%20Shot%202021-04-24%20at%2011.28.41%20PM.png)
# The Total Cases of COVID-19(China,Spain,Italy,India,USA)
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/5%20countries.png)
 We observed a sharp rise in the total cases in the US, followed by India with the US reaching the 30 million mark in total cases in March 2021. Hence the fact that US had the most number of COVID-19 cases until date was proven with our collected data. Initially Italy followed by Spain were the most affected countries and the outbreak hadn’t reached India until that time hence we can see, for the months of April, May and June the number of cases in India are less compared to Italy and Spain. After the first and second wave of the outbreak in Italy and Spain, the two countries managed to contain the outbreak up to some extent in comparison to the US.
Even if the actual figures reported for China are considered valid, the empirical integrity of China’s numbers has been repeatedly questioned. According to a few news outlets the estimates for con- firmed cases for China would be around 232,000 just until April 2020.There was growing concern that China is not being entirely honest about the extent of its infections and deaths and can be seen from the given data. According to our dataset the total cases for China had reached only the 101443 mark by the month of March 2021 which explains the straight line shown by the plot for China.
# Stock Market Data
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/Stocks.png)
we plotted the stock market data of all the indexes of all the five countries we chose. As we expected, initially with the rise in the number of COVID-19 cases and governments implementing lock-downs in all the countries there was a sharp decline in the indexes that can be seen in the plot.
It was reported that global stocks surged to record highs after the drug companies Pfizer and BioNTech announced that their coronavirus vaccine was 90% effective in trials, giving hope that economies around the world can soon return to normal. The Dow Jones industrial average and the tech-focused Nasdaq Composite index hit new records before dropping back. The tech heavy Nas- daq ended the day down 1.5% as investors sold Netflix, Peloton and Zoom and other companies that have benefitted from a pandemic boost. The Dow ended the day up 2.95%.Many of the most pro- nounced stock market gainers were the companies most affected by restrictions on movement brought in to fight the pandemic, while companies that have most benefited from lockdowns retreated from some of their spectacular gains.These patterns are also observed in our plot where we have shown the temporary rise in market when the first and second vaccines were released.
# Oil Prices Data
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/oil.png)

In the months from March to June when most countries were in a lock- down, travel and transportation industry reduced it’s operations upto a great extent and hence there was a less need for oil that made the oil prices go down. As countries started lifting lockdowns in phases we can see the graph slowly moving upwards with time and it came back to normal after year in the month of February 2021.
# Gold Prices Data
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/gold.png)


We can clearly see a decrease in the prices for the months of March and April and a steady graph from there onwards until a hike in August which was when lockdowns had been lifted by most countries. Lastly the plot ends with an increase in the gold prices in comparison to the prices in February 2020.

# Flights Data
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/flight.png)


On plotting we observed a sharp decline in the total number of flights that were operated during the initial months as expected, with the plot climb- ing upwards with time. An important observation here to note was that the number of flights plotted for the month of January 2020 is more compared to February 2021, that is even after a year of the declaration of the pandemic airports and flight services are still not operating at their full capacity and that may happen only when things start going back to normal until then the flight and air industry will be facing a substantial loss economically compared to the profits it would have brought in to the US Economy in normal times.
# Total Merchandise Imports Data for the US
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/imports.jpeg)

# Total Merchandise Exports Data for the US
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/Exports.jpeg)
# ANALYSIS

We started by examining how many people in the CPS dataset had work for pay or profit for both types of businesses; incorporated and unincorporated individually and together for every month of the year 2020. Then we realized that the count of these peo- ple was distributed over various occupational sectors within the dataset and we sorted these counts for each mentioned sector in the data dictionary for the CPS data. We compare the number of unemployed people for each month by computing the percentage of active business owners from the employment characteristics given in the dataset for each individual, sector-wise. Based on this computation we observed a dramatic drop in the number of active business owners in April 2020 and the partial rebound in May and a continuing rebound in June.
The number of working business owners dropped from 15.0 million in February 2020 to 11.7 million in April 2020 because of COVID-19. March 2020 only shows a small drop in business owners likely because of the limited effect from shelter-in-place restrictions. May 2020 shows a partial rebound from April 2020 adding back 1.1 million active business owners (7 percentage points relative to February levels). The losses due to COVID-19 from February remain high at 15%, but the rebound suggests that not all of the losses of active business owners in April 2020 were permanent closures. June experienced a further rebound with business activity being down 8% from February levels.
As mentioned in a study by Robert Fairlie published in the J Econ Manag Strategy a loss of 3.3 million businesses (or 22%) was observed from February to April 2020 and was the largest drop on record and hence explains the observed pattern in our analysis.
The CPS data also provides detailed information on gender, race, and immigrant status.
# GDP:
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/gdp.png)
Gross Domestic Product in Q1,Q2,Q3,Q4 for 2019 is 21115309, 21329877, 21540325, 21747394 Millions of Dollars. And for 2020 in Q1,Q2,Q3,Q4
is 21561139, 19520114, 21170252, 21494731 Millions of dollars. There has been a huge drop in Q2 of 2020 when compared to previous year quarter because of the pandemic. In the Figure 9 we can see the contribution towards GDP from various sector and we can see all the sectors which have huge impact of the pandemic have decreased in their contribution towards GDP even when Total GDP has decreased showing some sectors got much more effected than the others. For example from Figure 10 we can see in Q2 the contribution of Finance and Real Estate increased from 0.2121%
to 0.2338% where as Transportation decreased from 0.0324% to 0.0266%. Showing Transportation got much more worstly effected than the Finance and Real Estate. Just looking at the contributions we can not get the full picture of how all the sectors effected in terms of business owners and Unemployment so we use CPS data to dig deeper.
# Unemployment Rate
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/duration%20of%20unemp.png)

 Unemployment rate peaked at an unprecedented level touching all time high of 14.8% in April 2020 as we can see from Figure 11 but it does not paint the full picture as we don’t know whether the jobs lost are permanent or temporary and which sectors lost more number of jobs. So in the next section we see the duration of jobs lost to get better understanding of effect of pandemic on employmnet.
# Duration of Unemployment
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/unemployment.png)

When the public health crisis began, many workers were laid off on temporary furloughs, but since then many of those tempo- rary job losses have become permanent. Assuming jobs return eventually after the pandemic subsides, this increase in perma- nent layoffs would be considered an increase in cyclical unemploy- ment—unemployment that is a result of the business cycle. However, if the pandemic results in permanent changes to and job losses in some industries, the level of structural unemployment relatively long-lasting unemployment as a result of shifts in the economy could increase. Figure 12 explains this phenomenon. In April 2020, due to the sudden closure of many businesses, the percentage of individuals unemployed for less than five weeks increased to more than 50%. Since the shock, the duration of unemployment has been increasing, with those unemployed for more than 14 weeks account- ing for over half of all unemployed individuals in October 2020.By December, the percentage of unemployed individuals who had been unemployed for 27 or more weeks was a seasonally adjusted 35%, up from 22% in February, before the pandemic began showing that the some jobs lost in April are permanent losses not just temporary because of pandemic.
# Percentage of Active Small Scale Business
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/small%20scale.png)

I identify all individuals who own a business as their main job in the survey month (based on the class of worker question and monthly labor force re code). The main job is defined as the one with the most hours worked during the survey week. Thus, individuals who start side businesses will not be counted if they are working more hours on a wage and salary job. The CPS captures the current work activity of the business owner, and whether that business owner is currently operating the business. Thus, the number of active business owners can be captured in the data, but there is no way of telling whether these are temporary or permanent business closures. But, inactive business owners regardless of whether the business is temporary or permanently closed are suffering losses in business income during those months of non operation.The measure of business owner- ship in the CPS captures all business owners including those who own incorporated or unincorporated businesses, and those who are employers or non employers and the partial rebound in May and a continuing rebound in June. March 2020 only shows a small drop in business owners likely because of the limited effect from shelter-in-place restrictions.May 2020 shows a partial rebound from April 2020.
# Employment Percentage for the Agriculture Sector

![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/agriculture.png)
# Active businesses for the Personal Services Sector
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/personal%20servises.png)
# Percentage of Active Business owners by Etnicity
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/resident%20status.jpeg)
##### • Major black-owned firms are more likely to be located in COVID-19 hot spots, whereas white-owned firms are less likely to be in the most heavily affected areas
##### • Black-owned businesses also had fewer resources to fall back on when the pandemic struck.
##### • There might be a disparity in government aid through policies like Paycheck Protection Program(PPP).
# Percentage of Active Business owners by Immigration Status
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/ownership.jpeg)
# Employment Percentage by industry
![Image of Yaktocat](https://github.com/badri449/Bigdata_Project/blob/master/png%20files/png%20files/table.png)

# COMMENT ON GOVERNMENT STEPS:
Based on the analysis we have done we will comment on two of the steps taken by the government to revive the economy and decrease the unemployment.
## Employment Visa Ban:
On June 24, 2020 the then President Trump issued a proclamation that will suspend the entry of foreign nationals of various work visa’s like H-1B, L-1, H-2B, J-1 categories, and related categories for dependents, with some exceptions and the reason sated for this proclamation is that "since Unemployment is at all time high we need to put more emphasis on hiring Americans over foreign nationals". Though Unemployment is at all time high this alone does not paint the whole picture as we can see from Figure 17 the percentage drop in active business in Financial Activities and Professional and Business is a little over 10% in April from March. where as other sectors such as Personal Services and Entertainment sectors are much more worstly effected than the former sectors so the increase in Unemployment is mostly likely because of the other sectors rather than Financial Activities and Professional and Business and majority of the high skilled labour under these banned visa’s come under this sector so banning these visa is not going to help in increasing the job growth.

## Paycheck Protection Program:
The Paycheck Protection Program (PPP) is a $953-billion business loan program established by the United States federal government in April 3rd 2020 through the Coronavirus Aid, Relief, and Economic Security Act (CARES Act) to help certain businesses, self-employed workers, sole proprietors, certain nonprofit organizations, and tribal businesses continue paying their workers.
As we can see from Figure 17 Personal Services sector like laundry and Saloons are the worst effected as its employment percentage dropped from 94.318% in February to 23.55% in April. But it in- creased to 50% followed by 73% in May and June. There are two possible explanations for this change.
#### • The Pandemic took the world and US by surprise and peo- ple’s first reaction to pandemic is much more intense which decreased over the next few months.
#### • Paycheck Protection Program Started by the Government to help small scale business in pandemic was successful in its implementation.


# CONCLUSION
The Pandemic has resulted in an all time high unemployment rate in USA. Even though it got better over the next few months some of the jobs lost in April are permanent losses. Government needs to to take steps in restoring the economy. PPF was a success according to the data It was a good step to implement PPf for the second time as it gives boost to small scale business. But even though policies are not biased based on Colour we have seen black business owners are much more worstly effected than white owners. Government needs to try to find the reason for this and take necessary steps. Travel data is also one sector which got effected mostly as it can bee seen from flight data. Now as more and more people are getting vaccinated once the situation stabilizes government should be more encouraging towards travel. One such way is incentivize people towards travel.


# Team
  ## 1) Badrinath Reddy Gujjula
  ## 2) Lokesh Munagala
  ## 3) Susmita Karyakarte

# Support
#### If you found this useful, please consider starring(★) the repo so that it can reach a broader audience.

# Report Link
## "https://github.com/badri449/Bigdata_Project/blob/master/png%20files/report.pdf"
