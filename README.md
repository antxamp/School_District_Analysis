# School_District_Analysis
Anaconda3, Python 3.7.9

## Project Overview
   -    The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Resources
   -  Data Source: schools_complete.csv
                   & students_complete.csv

   -  Software: Jupyter Notebook, Anaconda3, Python 3.7.6 


## Deliverable 1: Replace Ninth-Grade Reading and Math Scores
### Results:
### Ninth-grade scores changed to NaN:  
![image after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/with_nan.png)
     
      
## Deliverable 2: Repeat the School District Analysis
### Results:
#### New Math & Reading results: 
<img src="https://github.com/antxamp/School_District_Analysis/blob/main/Images/math_by_grade_new.png" width="360" height="400"><img src="https://github.com/antxamp/School_District_Analysis/blob/main/Images/Reading_bygrade_new.png" width="340" height="430">

#### High and Low performers:
<img src="https://github.com/antxamp/School_District_Analysis/blob/main/Images/highperforming.png" width="680" height="200"><img src="https://github.com/antxamp/School_District_Analysis/blob/main/Images/lowperforming.PNG" width="680" height="200">

### Scores by Type:
<img src="https://github.com/antxamp/School_District_Analysis/blob/main/Images/school_type_new.png" width="700" height="125">

### Scores by Spending:
<img src="https://github.com/antxamp/School_District_Analysis/blob/main/Images/spending_ranges.PNG" width="800" height="130">

### Scores by Size:
<img src="https://github.com/antxamp/School_District_Analysis/blob/main/Images/scoresbyschool.PNG" width="800" height="130">

 
  
## Summary
### What the results show:
   -  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
         -  Removing the ninth graders' math and reading scores ending up showing a high percentage for %Passing Math, Reading and Overall have increased substantially.  

![Image before](https://github.com/antxamp/School_District_Analysis/blob/main/Images/THS_summary_dataframe%20(1).png)
![Image after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/THS_updated_summary_dataframe.png)
   
   -  How is the district summary affected? 
        - The district summary obviously showed an increase in overall passing within the district due to the adjustments made from Deliverable 1.
![Image after](https://github.com/antxamp/School_District_Analysis/blob/main/Images/district_summary.PNG)
   
   -  To summarize, by removing the altered ninth graders' inaccurate grades to NaN from Thomas High School we were able to attain a more accurate number which in fact can help the school with budgeting in the future. Comparable to other schools the numbers looked similar than being an outlier which paints a better image of percentages and can help better budget for the schools that need funding.
