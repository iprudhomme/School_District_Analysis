# School_District_Analysis
## Overview 
For our fourth project in the Data Analytics course, we've been giving testing results for a school district and asked to summarize analyze the data and return a summary the results over a variety of categories.  In the course of the analysis it was discovered that a section of students had to be removed due to academic dishonesty, so we have been asked to remove those scores and re-analyze the data without those scores.  We've used Jupyter Notebook and Python Pandas to assist us in our analysis.
## Resources
- Data Sources: clean_students_complete.csv
                schools_complete.csv
- Software: Python 3.9.7, Visual Studio Code, 1.63.2, Pandas 1.3.5, Jupyter Notebook 6.4.7

## School District Analysis Results

District Summary (adjusted)
461 ninth grade students from Thomas High School were removed from the analysis due to academic dishonesty.  Below is the adjusted scores for the district.
![School District Summary](/Resources/district_summary.png) 
* Avg Math score was reduced by 0.1%
* The Avg Reading score remained the same
* The % passing math was reduced by 0.2%
* The % passing reading was reduced by 0.3% 
* The overall % passing was reduced by 0.1% 

School Summary
Totals corrected for Thomas High School
![School Summary](/Resources/school_summary.png) 
The removal of the 9th grade students caused a slight reduction in all categories for Thomas High School.  Though the overall percentage went down, the reduction was not enough to cause the school to drop out of the 2nd place position based on overall score.  The reduction was from 90.95% down to 90.63%.

Top 5 schools:
![Top 5 Schools](/Resources/top_5_schools.png) 
Scores by Grade: 

You can see that both the 9th grade math and reading scores has been removed and replaced by NaN.  The other scores are not affected.

![Math Scores By Grade](/Resources/math_scores_by_grade.png) 
![Reading Scores By Grade](/Resources/reading_scores_by_grade.png) 

Scores by School Spending:
![Scores by Spending Ranges](/Resources/scores_by_spending_ranges.png) 

No noticible changes in the aggregate of student spending ranges.

Scores by School Size:
![Scores by School Size](/Resources/scores_by_school_size.png) 

No noticible changes in the aggregate of school size ranges.

Scores by School Type:
![Scores by School Size](/Resources/scores_by_school_type.png) 

No noticible changes in the aggregate of school type ranges.
## School District Summary

We have run the analysis for the school district and have adjusted the analysis to remove the 461 ninth grade students from Thomas High School.  Looking at the analysis, there was a slight adjustment to the results for the school.  However when doing district wide aggregates, the changes were not significant enough to make a difference in the overall percentages.  Thomas High School still remained the 2nd best school in the district, though it was almost replaced by Griffin High School.  Overall the schools with the highest level of funding per capita did the best in the district with 90% passing, while the lowest funding did the worst with 54% passing.  There was a direct correlation between funding and passing rates.  