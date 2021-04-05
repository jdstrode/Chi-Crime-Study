# Chi-Crime-Study

Data Analysis and Clean Up:

General Demographics:
- Analysis/Clean Up of Sex: The initial values were male, female, and NA. I replaced NA with Not Reported. I did not want to remove them from the sample because there is value in knowing the percentage of a demographic that does not get reported, so we know where we can improve data collection. After replacing the values, I used Matplotlib to create a pie chart depicting this information.
- Analysis/Clean Up of Age: There were many missing values for age, so I decided to remove them using "dropna" because I was going to bin my ages. After dropping the NA values, I created a histogram for frequency of age groups. This exercise was a bit difficult, and I did have TA and tutor assistance for this.
- Analysis/Clean Up of Race/Ethnicity: Again, there were many NA values for this variable. This time, I replaced NA with Not Reported, as knowing how many officers don't report race/ethnicity is critical to understanding the limitations of this dataset. After replacing the NA values, I used Matplotlib to create a bar chart of race/ethnicity.

Location Data
- Used pd.notnull to remove all datapoints that were missing coordinates. This was all that was necessary to create the primary data set, but also made subsets for drivers that were black and white.

Most common time points for a stop to occur:
- Isolated the date, time, violation, arrest_made, citation_issued, and outcome columns. 
- Dropped all of the NA values dropping the dataset from 846456 to 5737. Then, proceeded to combine date and time column and create a date time index. This allowed to explore if time of the day when stops occurred and a yearly analysis of the data.

Demographic Relationships
- Isolated the subject_race & officer_race columns, then dropped all NA values. This took the dataset from 846,121 total rows to 164,434 rows.
- Analysis of Incident Count by Race: Created a table of incidents by race of driver and officer and used this table to create bar graph to analyze relationships between race of driver and officer.
- Analysis of Reported Crimes per Subject Race: Did a groupby of driver race and officer race to create a bar graph.
