
# A/B Testing
## By Ayman El Taweel 



## Dataset

> Our dataset includes data about web traffic, such as: UserID, Time, Group and conversion state.
> The dataset source will be attached with the project.
> We cleaned our data as follows:

	1) Column Cleaning: 
		Unifying columns to be in small letters and separated by '-'		
	
	2) Dealing with duplicates: 
		dropping duplicates
	
	3) Assuring the consistency of our test group:
		 we created a new dataframe including , only, matched groups with their relevant landing page
	
	4) Dealing with duplicated **_ids
		 We dropped an instance of duplicated user_id in order to reduce any bias.
	

## Summary of Findings


* There is neither statistical nor paractical difference in the conversion rates for both old and new pages, as   a result of various statistical techniques including : Probability, Hypothesis testing and Z-test and finally    the regression models.

> So, the practical decision should be that the company maintains the old_page, becuse launching the new page   would cost more than it benefits in terms of conversions.


