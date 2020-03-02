# **Analysis of India's GDP**
## *Data*

The data is sourced from https://data.gov.in/, an Open Government Data (OGD) platform of India.The data for GDP analysis of the Indian states is divided into two parts:

**Data I-A**: This dataset consists of the GSDP (Gross State Domestic Product) data for the states and union territories.

**Data I-B**: This dataset contains the distribution of GSDP among three sectors: the primary sector (agriculture), the secondary sector (industry) and the tertiary sector (services) along with taxes and subsidies. There is separate dataset for each of the states. I read the dataset for the available states and joined these using PYTHON

 

**There are two parts to this project**. In the first part, I analysed and compared the GDPs of various Indian states (both total and per capita). The GDP of a state is referred to as the GSDP (Gross State Domestic Product).The states were then divided into four categories based on the GDP per capita, and for each of these four categories the sectors that contribute the most to the GDP (such as agriculture, real estate, manufacturing, etc.) were analyzed.


**The second part** analyzes the GDP per capita versus the dropout rates in schools and colleges.


**Part-I: GDP Analysis of the Indian States**
**The following questions have been answered as a part of the analysis**

How do the growth rates of any two states compare?
Which states have been growing consistently fast, and which ones have been struggling?
What is the Nation's growth rate?
What has been the growth rate of my home state, and how does it compare to the national growth rate?
Identify the top 5 and the bottom 5 states based on total GDP.
What states are performing poorly? 

**Part I-B:**

The states were categorized into four groups based on the GDP per capita (C1, C2, C3, C4, where C1 is the highest per capita GDP and C4, the lowest). The quantile values are (0.20,0.5, 0.85, 1), i.e., the states lying between the 85th and the 100th percentile are in C1; those between the 50th and the 85th percentiles are in C2, and so on.
For each category (C1, C2, C3, C4):
The top 3/4/5 sub-sectors (such as agriculture, forestry and fishing, crops, manufacturing etc., that contribute to approximately 80% of the GSDP of each category were analyzed

The nomenclature for this project is as follows: primary, secondary and tertiary are named 'sectors', while agriculture, manufacturing etc. are named 'sub-sectors'.

Plot the contribution of the sub-sectors as a percentage of the GSDP of each category.  

You will find answers to the following questions:

How does the GDP distribution of the top states (C1) differ from the others?
Which sub-sectors are correlated with high GDP?
Which sub-sectors do the various categories need to focus on? 
 
## **Part-II: GDP and Education Dropout Rates**
This part analyzes to find it there is relationship between per capita GDP and school dropout rates

## **Data II:** 
Part-II: GDP and Education

**The goal is to analyse if there is any correlation of GDP per capita with dropout rates in education (primary, upper primary and secondary) for the year 2014-2015 for each state.

**The following questions were answered after the analysis**

Is there any correlation between dropout rate and %contribution of each sector (Primary, Secondary and Tertiary) to the total GDP?
Is there any correlation between dropout rates and population? 
What is the expected trend and what is the observation?
