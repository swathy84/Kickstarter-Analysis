# An Analysis of Kickstarter Campaigns 
Getting to know the Louise's "Kickstarter" Campaign file by formating, filtering, identifying the different data fields and numbers of data present in the data file.

Added new columns Percentage funded, Average donations and retrieved values based on Goal, Pledged and Backers_count to "Kickstarter " file.

Created a new  column to split "Category and Sub catergory " field into Parent category and Sub category to make the data more detailed for analysing in the Kickstarter file.

Used Pivot table and Pivot Chart for Parent category based on outcomes to analyze the Theatre category was the  most successful campaign Louise has among all the other categories . 
-Worksheet added to the Kickstarter file is "Category Statistics"
Below is the Picture image of the analyzation.
![Parent Category Outcomes](https://user-images.githubusercontent.com/93801581/147291012-a82957e2-173a-4955-bbf8-e3b2e39acbf7.png)

Next, to analyze which sub category was most successful, we are using the Pivot table and Pivot chart based on Sub categories related to the outcomes. We analyzed "Plays" sub category was the most successful .
-Worksheet added to the Kickstarter file are "Pivot table-Sub category Statistics" and "Subcategory statistics"
Below are the pictures

![Subcategory Outcome US](https://user-images.githubusercontent.com/93801581/147291579-2e5cfb0c-d2c0-4d96-8705-00090f9f50e1.png)
![Subcategory Outcomes GB](https://user-images.githubusercontent.com/93801581/147291581-18d6b8bd-6fd8-4663-8cf4-e3ea5bdb4828.png)

Next,  to analyze the Theatre catergory campaign progressed by month to month based on Outcomes, we first converted the datestamp in the Kickstarter  data file for Launch date  and created a new filed with conversion date and used Pivot table and Pivot chart to analyze which month  the most successful campaign occur. 
-Worksheet added to the Kickstarter file is " Outcome based on Launch Date"
Below is picture of analyzation. 
![OutcomeBasedOnLaunchDate](https://user-images.githubusercontent.com/93801581/147292454-e8b01c19-7d98-4a62-89cb-b1668fadf8e9.png)

Since Louise was inspired by particular plays for Edinburgh , we used VLookup function to retrieved data  from the Kickstarted data file  and created a new worksheet for Edinburgh analysis. 
-Workeet  name added in Kickstarter file is " Edinburgh Research"  

Created an new work sheet to  Use Measure of central tendancy and Measure of spread to do a descriptive statistics analyzation on Theater/Play category in the US and compared the statistics for the campaigns that succeeded versus failed   
- Workseet names added in the Kickstarter file are "Successful US Kickstarters", "Failed US Kickstarters","Descriptive Statistics"

also created a new work sheet  Used Measure of central tendancy and Measure of spread to do a descriptive statistics analyzation on Technolgy/Wearables category in the US and compared the statistics for the campaigns that succeeded versus failed to see how the data is showing other than Theater/plays category in Louise's campaign.
- Workseet names added in the Kickstarter file are "SuccessfulUSKickstarterTech", "FailedUSKickstarterTech","Descriptive Statistics Tech"

Next ,created an Outlier using Box and whisker plots to compare the distribution of the campaign goals and the distribution of the total amounts pledged for Musical in Great Britain
-Worksheet added ot Kickstarter is "Chart 1 " 
- Below is the Picture for Bos and Whisker plot for Great Britain - Musical campaign analyzed based on Goal and Pledged amounts
![Box and Whisker plots GB Musical](https://user-images.githubusercontent.com/93801581/147299213-9a4a6a1e-00ae-4c01-812d-cbf3d023e2b1.png)

The conclusion is Louise campaign had a successful outcome for Theater/Play category 
