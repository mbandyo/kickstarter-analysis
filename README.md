# Kickstarting with Excel

##  Project Description:
The project aims to analyze fundraising data for the purpose of designing a fundraising campaign. The dataset is rich, diverse and provides data in detailed granularity. The data points include information about fundraising campaigns in dimension of country, outcome, parent category and subcategory, goals, pledged, launch time of the campaigns and a short description of campaign purpose. 

### Purpose 
The purpose of the analysis is to provide client some idea of common factors of both successful and failed campaigns. 

Since the client is interested in launching fundraising campaign for production of a theater act, the analysis is focused on the successful theater campaigns specifically fundraising goals and launch time.  

### Analysis
* Launch date analysis highlights the following trend for US theater fundraising campaigns:
Most successful campaigns were launched in Q2 (month of May), followed by February and October. However, the October peak is ambiguous as high number of failed campaigns were also launched in the month of October.
![Theater Outcomes vs. Launch Date](https://raw.githubusercontent.com/mbandyo/kickstarter-analysis/8b69d9dd69fffa5ae25a073c6bdd3c219b5a2fe2/Resources/Theater_Outcomes_vs_Launch.png)

* Analysis of Outcomes Based on Goals:
Most successful US theater campaign goals were in the range of $1000 - $5000 with an average of $2350 and median $3000. Median is higher than the mean implying data Is skewed to the left.
![Theater Outcomes Based on Goals](https://github.com/mbandyo/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered
It is not possible to ascertain if this is a comprehensive dataset i.e., we cannot know if there are datasets that are not included which might change the analysis and conclusions.
The data does not inform whether any incentive was included with pledges for successful campaigns i.e., free tickets to opening show. 


## Results
The analysis of successful campaigns based on launch date can be summarized in the following chart:


* Most successful campaigns were launched in the month of May, followed by June and July. 
* The same pattern is repeated for failed campaigns also.
A reasonable conclusion would be the launch date is not the sole factor for successful campaigns.
The analysis of successful campaigns based on goals can be summarized in the following chart:

* Most successful theater campaigns had low bar of less than $1000 goals.

* Next successful category was between $1000 and $5000 with a mean of $2350 and median of $3000. This implies the data is skewed to the left.
A reasonable conclusion from goal-based analysis would be that the probability of a successful campaign increases with lower goals. 


### Limitations
The dataset is limited in terms of time horizon. It does not reflect other competing entertainment options available. It also does not provide details of locations, community and demographic information making it challenging to target and/or customize the campaign. Also, the data does not include any common theme in the successful campaigns.

### Scope
The data can inform about other category and subcategory campaign related information. For example, we can create a chart that shows the category that had most successful campaigns and so on. 
