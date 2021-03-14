# School_District_Analysis

## Overview of the School District Analysis 
###### Purpose :
There were some evidence of academic dishonesty in the data given to us in our inital analysis. Specifically, the reading and math data for ninth grade Thomas High School students shows that grades may have been tampered with. In order to keep the intregrety of our analysis, we will exclude the math and reading data from those specific ninth graders and repeat the school district analysis. 


## Results 
###### District Summary Results 
Based on our analysis:
- Total Students and Total Budget has remained the same, as they were not affected by the omited ninth grade grades
- Average Math Score decreased .1 percent from 79.0% in our previous analysis to 78.9% in our current analysis 
- Average Reading score has remained the same, staying at 81.9%
- % Passing Math has decreased .2 percent from 75% in our previous analysis to 74.8% in our current analyis 
- % Passing Reading has decreased .3 percent from 86% in our previous analysis to 85.7% in our current anaylsis
- % Overall Passing decreased .1 percent from 65% in our previous analysis to 64.9 in our current analysis

![old_district_summary.png](https://github.com/Cmarescot/School_District_Analysis/blob/main/Resources/old_district_summary.png)
![new_district_summary.png](https://github.com/Cmarescot/School_District_Analysis/blob/main/Resources/new_district_summary.png)

###### School Summary Results
- The Thomas High School metrics in the school summary column have all changed with the exeption of the Total students, Total School Budget and Per Student Budget columns
- Average Math score changed from 83.418349 to 83.350937 
- Average Reading Score changed from 83.848930 to 83.896082
- % Passing Math changed from 93.272171 to 93.185690  
- % Passing Reading changed from 97.308869 to 97.018739  
- % Overall Passing chanfed from 90.948012 to 90.630324 

![old_school_summary.png](https://github.com/Cmarescot/School_District_Analysis/blob/main/Resources/old_school_summary.png)
![new_School_Summary.png](https://github.com/Cmarescot/School_District_Analysis/blob/main/Resources/new_School_Summary.png)

###### Thomas High School Performance 
- By replacing the ninth graders scores for Thomas High School our data has slightly changed but not enough to overturn the major key takeaways.
- Thomas High School still has the second % overall passing of 90.630324 
- Thomas High School over all passing percentage slightly decreased from 90.948012 to 90.630324

![old_thomas_performance.png](https://github.com/Cmarescot/School_District_Analysis/blob/main/Resources/old_thomas_performance.png)
![new_thomas_performance.png](https://github.com/Cmarescot/School_District_Analysis/blob/main/Resources/new_thomas_performance.png)

###### Ninth Grade Score Replacement Affects
Replacing the ninth grade scores has:
  - Only affected the scores for 9th graders (by having been dropped). 10th , 11th and 12th math and reading scores by grades have remained the same 
  - Scores by school Spending have remained the same 
  - Score by school size have also remained the same 
  - Scores by school types have also remained the same 

## Summary 
###### Major Changes 
The major changes from this analysis are:
- NaN replaced Thomas High Schools's ninth grade scores
- Total Student count was recounted (9th graders were excluded from the count)
- Calculations were reformulated in order to include only data regardering 10th-12th graders
- ONLY reading and math data were excluded from the analysis. Eveything else was left as is. 
