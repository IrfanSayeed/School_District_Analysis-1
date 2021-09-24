# **School_District_Analysis**

## **Background:**
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

### Data Source: clean_students_complete.csv, schools_complete.csv, students_complete.csv 
### Software: Python 3.7.10 , Jupyter Notebook


## **Overview of the school district analysis:**
The purpose of the school district anlaysis is to aggregate the data to provide insights on performance trends and patterns on all standardized test data for analysis, reporting and presentations. This will allow the school board to have informed discussions and make strategic decisios on student funding, budgets and school priorities.

## **Results:**
A re-assessment of both the school summaries and individual school performance, show that the altered grade 9 math and reading scores skewed the inital testing results.  The analysis was repeated using scrubbed data, where all grade nine math and reading scores for Thomas High School were replaced with "NaN" values.  This affected 461 students of a total of 3970 high school students in the district.   

Noted changes to the School District Analysis are as noted below: 

* **How is the district summary affected?**

 The overall district summary saw minimal impact, affecting only the overall average math score by minus 0.1%.
      
  ##### Original District Summary

  <img width="720" alt="District_Summary_Original" src="https://user-images.githubusercontent.com/89538802/134520149-342d4e16-c5ce-4484-a088-d3f532a17899.PNG">

  ##### Scrubbed District Summary

  <img width="705" alt="District_Summary_Scrubbed" src="https://user-images.githubusercontent.com/89538802/134528624-bc9d17c2-a820-42e5-b825-332fcb0b8603.PNG">

 * **How is the school summary affected?**
 
  ##### Original Per School Summary
  
  ![Per_School_Summary_Original](https://user-images.githubusercontent.com/89538802/134528076-2f2211f3-29de-455b-beba-3157935b0633.PNG)

 
  ##### Scrubbed Per School Summary
  ![Per_School_Summary_Scrubbed](https://user-images.githubusercontent.com/89538802/134528515-4218c2bb-3a38-4b99-824e-39dcf36b985b.PNG)



***How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**





* **How does replacing the ninth-grade scores affect the following:**
  * Math and reading scores by grade
  * 
  #### Reading
  
  <img width="231" alt="Reading_Grade_Scrubbed" src="https://user-images.githubusercontent.com/89538802/134545580-b61f8d5e-aec9-49ee-b999-699ebd4f8466.PNG">

  ##### Math
  
  <img width="234" alt="Math_Grade_Scrubbed" src="https://user-images.githubusercontent.com/89538802/134545621-b1fb2cd7-2cef-4ede-972e-2ca86fde31b7.PNG">


  * Scores by school spending
********************
When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores. However, this data change did impact the spending ranges for passing percentages. According to the summary above, there was a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 6% decrease in % overall passing in the $630-644 spending range.
**************************

  * Scores by school size
***********************
When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing).
***************************
  * Scores by school type
************************
In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.
*******************************

## **Summary:**

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. change 1
2. change 2
3. change 3
4. change 4
