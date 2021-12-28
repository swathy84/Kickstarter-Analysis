
# Analysis of Kickstarter Campaign

## Overview of the Project 

Analyzing the Louise's Kickstarter campaign file to determine which category was the most successful. 

### Step 1. Profile the data

Reviewed the Louise's "Kickstarter" Campaign file by formating, filtering, identifying the different data fields and numbers of records present in the data file.

After modifying the Kickstarter data file by adding fields like Percentage funded,Average donations,Parent category,sub category,Date created conversion,Date ended conversion,Years within the file, analyzed that Theater/Play category was successful than others catergories.

![main](Resources/Kickstarter.png)

### Step 2. Trying to analyze the data of Theater/play category based on Launch dates and funding goals

### Analysis of Outcomes Based on Launch Date
  
To determine the campaign status for Theater catergory in relation to their Launch dates and Outcomes
Modified the file by adding "Year" field by calculating the year from "Date created conversion" column.
Worksheet added to the Kickstarter file  -  "Theater Outcomes by Launch Date"

Pivot table and Pivot chart to view the Theater category analysis based on Outcomes (Success,Failed,Canceled) by months of the year.
![main](Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

To determine the Campaign status for Play Subcategory in relation to their Goals and Outcomes
New sheet added by extracting data of Goals and Outcomes field from the Kickstarter file to analyze deeper into the Goals based on the outcomes.
Worksheet added to the Kickstarter file  - "Outcome Based on Goals"

Pivot table and Pivot line chart to view the Plays analysis based on Outcomes for the Goal ranges. 
![main](Resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

Sorting the Goal ranges in the Line chart for the  "Outcomes based on Goal" analysis. 

## Results

Conclusion for Outcomes based on Launch Date is  Lousie's Theater catergory was most successful in May month of all the years from the "Launch date" field.
Worksheet added to the Kickstarter file -  "Successful theater Kickstarter", "Failed theater Kickstarter","Descriptive Statistics theater". 

Box and whiskers plot graph explains Louise campaign needs to be  Less than $1000 to be successful.
![BoxPlot Theater](https://user-images.githubusercontent.com/93801581/147512509-2cf4412c-df88-4623-85c8-d9bc7402e153.png)


Conclusion for Outcomes based on Goals is Louise's Plays Subcategory made the most success when the goals was less than $1000 range.
Worksheet added to the Kickstarter file -  "Successful Plays Kickstarter", Failed Plays Kickstarter,Descriptive Statistics Plays". 

Box and whiskers plot graph for the Play subcategory based on Goal and Pledged amounts
![Boxplot Play](https://user-images.githubusercontent.com/93801581/147512527-bad42651-8460-402e-b5a9-9061bba71a88.png)


- What are some limitations of this dataset?
Box and Whishker plot graphs for Theater/Plays Category above helped us analyze there are many outliers above $30000 goal amount. To be successful, Louies's campaign needs to be less than $1000 to be successful. 

- What are some other possible tables and/or graphs that we could create? 
The data for the Outcomes based on goals can also be interpreted using Bar chart where we can analyze the Percentage of success and failure in a better way for the Plays Subcategory. 
![main](Resources/OutcomesBasedOnGoals.png)
 
Box and Whiskers plots graph for Theater/Plays category taking Goals and Pledged amounts determines the outliers for the Theater/Plays catergory campaign.
 
Based on the above observations, Louise's campaign will be more successful if the Gaols are less than $1000. 
