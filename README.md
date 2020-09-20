# Kickstarter-Excel



## Overview of Project
This consultative project evaluated grassroots fundraising efforts known as crowdfunding campaigns to provide recommendations for a playwright who sought funding for her new play. 


### Purpose
Analysis work included identifying theater play campaigns from a comprehensive crowdfunding campaigns dataset to understand the impact of factors like campaign launch month and campaign goal on a successful theater crowdfunding projects. 


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis began with the complete crowdfunding dataset. After some exploratory analysis to evaluate the dataset, data manipulation converted one date format to another to enable analsys by month; filtered the data set to evalute only the category of theater campaigns; and then focused on the outcome of successful, failed or canceled campaigns to generate a line graph. The graph below compares the status of theater campaigns by the month of a their launch date.

![Theater Outcomes Based on Launch Date](
https://github.com/kdmatar/Kickstarter-Excel/blob/master/Resources/Theater%20Outcomes%20by%20Launch%20Date.png?raw=true)

### Analysis of Outcomes Based on Goals
The data manipulation for this analysis began with filtering the dataset to evaluate only plays and aggregating each campaign by campaign goal into 12 goal categories, summarizing the outcome of each campaign by those goal ranges and then calcuating the percentage of each type of campaign outcome--*successful, failed, or canceled*--by goal range.  

![Outcomes Based on Goal](https://github.com/kdmatar/Kickstarter-Excel/blob/master/Resources/Outcomes%20Based%20on%20Goal.png?raw=true)

### Challenges and Difficulties Encountered
While analysis with this dataset was rather straight-forward, there could have been challenges with the analysis if the dataset had missing values in the date or goals or category fields particularly. Mismatched data types within a particular field would also present a challenge in working with this dataset.



## Results
The **majority of successful theater campaigns launched in May** while December showed the fewest number of successful campaign launches. Interestingly, May also revealed the greatest number of failed campaigns but successful campaigns outnumbered fail campaigns by two to one. In other words, **two-thirds of the campaigns launched in May were successful**.

Notably, the **greatest percentage of successful campaigns have a goal below  a threshold of 5.000** which bodes well for this playwright who wishes to raise 4,000 to stage her play.


#### Limitations of Datasset
One limitation of this dataset is that the goal and pledged amounts are not in a standardized monetary unit. Each project has the goal/pledged amounts in the country of origin currency. A focus on theater and play projects within the US might yield a better understanding of the trends that are most relevant for playwright client. Additionally, the dataset includes nearly 10 years of data which may not take into account any time-sensitive factors that affect crowdfunding campaign success. Perhpas this analysis might have considered only projects within the last two or three years to minimize the impact of any adverse issues on a fundraising campaign from more distant years.

#### Recommendation for Further Analysis
Further analysis might include generating additional charts with country filtered for US and years filtered for the last two years to compare outcomes. Another trend that might have been interesting to evaluate is if the duration of the crowdfunding campaign correlated with the outcome. For instance, do shorter campaigns correlate with successful campaigns; or do shorter campaigns correlate with a higher pledge amount per contributor? 

However, findings from this analysis did reveal actionable insight that enabled the playwright to move forward with her fundraising campaign.
