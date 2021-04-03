# Chi-Crime-Study

Data Analysis and Clean Up:

General Demographics:
- Analysis/Clean Up of Sex: The initial values were male, female, and NA. I replaced NA with Not Reported. I did not want to remove them from the sample because there is value in knowing the percentage of a demographic that does not get reported, so we know where we can improve data collection. After replacing the values, I used Matplotlib to create a pie chart depicting this information.
- Analysis/Clean Up of Age: There were many missing values for age, so I decided to remove them using "dropna" because I was going to bin my ages. After dropping the NA values, I created a histogram for frequency of age groups. This exercise was a bit difficult, and I did have TA and tutor assistance for this.
- Analysis/Clean Up of Race/Ethnicity: Again, there were many NA values for this variable. This time, I replaced NA with Not Reported, as knowing how many officers don't report race/ethnicity is critical to understanding the limitations of this dataset. After replacing the NA values, I used Matplotlib to create a bar chart of race/ethnicity.

Location Data


Most common time points for a stop to occur:


Demographic Relationships