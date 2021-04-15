# School_District_Analysis
Anaconda3, Python 3.7.9

## Project Overview
   -    The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Resources
   -  Data Source: schools_complete.csv
                   & students_complete.csv

   -  Software: Jupyter Notebook, Anaconda3, Python 3.7.6 

## Results
What the results show:
   -  How is the district summary affected? 
        - The district summary wasn't affected by much due to the small amount that was NaN from 9th graders of Thomas High School. There were slight changes in % Overall passing. From 64.9% up to 65%.
 
   -  How is the school summary affected?
        - The school summary did change due to removing the data. (via the image below)
  ![image before](https://github.com/antxamp/School_District_Analysis/blob/main/Images/old_schoolsummary.png) 
  
  ![image after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/new_schoolsummary.png)
     
   -  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
        - Removing the ninth graders' math and reading scores ending up showing a high percentage overall but that could be misleading due to the removal.  

![Image before](https://github.com/antxamp/School_District_Analysis/blob/main/Images/THS_summary_dataframe%20(1).png)
![Image after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/THS_updated_summary_dataframe.png)
       
   -  How does replacing the ninth-grade scores affect the following:

###### Math and reading scores by grade

###### Old Math results
![before](https://github.com/antxamp/School_District_Analysis/blob/main/Images/math_by_grade_old.png)

###### New Math results
![after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/math_by_grade_new.png)


###### Old Reading results
![before](https://github.com/antxamp/School_District_Analysis/blob/main/Images/Reading_bygrade_old.png)

###### New Reading results
![after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/Reading_bygrade_new.png)


###### Scores by school spending...
Scores of Thomas High School are reduced see images...

###### Old spending results
![before](https://github.com/antxamp/School_District_Analysis/blob/main/Images/schoolsummaryold.png)

###### New spending results
![after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/spending_new.png)


###### Scores by school type...

###### Old results by school type
![before](https://github.com/antxamp/School_District_Analysis/blob/main/Images/schooltypeold.png)

###### New results by school type
![after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/school_type_new.png)


###### Scores by school size...

###### Old results by school type
![before](https://github.com/antxamp/School_District_Analysis/blob/main/Images/size_old.png)

###### New results by school type
![after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/size_new.png)
 

  
## Summary
   -  To summarize by removing the altered ninth graders' inaccurate numbers from Thomas High School we were able to attain a more accurate number which did in fact help the school with budgeting in the future. 
