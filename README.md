# **School_District_Analysis**

## **Background:**
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

### Data Source: clean_students_complete.csv, schools_complete.csv, students_complete.csv 
### Software: Python 3.7.10 , Jupyter Notebook


## **Overview of the school district analysis:**
The purpose of the school district anlaysis is to aggregate the data to provide insights on performance trends and patterns on all standardized test data for analysis, reporting and presentations. This will allow the school board to have informed discussions and make strategic decisios on student funding, budgets and school priorities.

### **Challenge:**

## **Results:**
The removal of the grade 9 Thomas High School scores affected the results of the School District Analysis as follows:

* **How is the district summary affected?**
The grade nine math and reading scores for Thomas High School were to be replaced with "NaN" values.  This affected 461 students of a total of xx students.   The impact was minimal and affected the overall average math score changed by -.1% when the analysis was rerun.
      
  ##### Original District Summary

  <img width="720" alt="District_Summary_Original" src="https://user-images.githubusercontent.com/89538802/134520149-342d4e16-c5ce-4484-a088-d3f532a17899.PNG">

  ##### Scrubbed District Summary

  <img width="705" alt="District_Summary_Scrubbed" src="https://user-images.githubusercontent.com/89538802/134528624-bc9d17c2-a820-42e5-b825-332fcb0b8603.PNG">

 * **How is the school summary affected?**
 
  ##### Original Per School Summary
  
  ![Per_School_Summary_Original](https://user-images.githubusercontent.com/89538802/134528076-2f2211f3-29de-455b-beba-3157935b0633.PNG)

 
  ##### Scrubbed Per School Summary
  ![Per_School_Summary_Scrubbed](https://user-images.githubusercontent.com/89538802/134528515-4218c2bb-3a38-4b99-824e-39dcf36b985b.PNG)

********************************
When assessing school summaries and performing schools, the score replacements did affect the ranking of the top five performing schools. Thomas High School ranked second place in the top five performing schools with a 91% overall passing. After replacing both math and reading scores, Thomas High School was taken out of the top five category since they now display a 65% overall passing. On the plus side, these changes did not place Thomas High School among the bottom five performing schools. Those ranks remained the same. Per the revised School Summary, Thomas High School now ranks 8th place among 15 high schools in the district
***********************************

***How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**





* **How does replacing the ninth-grade scores affect the following:**
  * Math and reading scores by grade
  * 
  ####Reading
  
  <img width="231" alt="Reading_Grade_Scrubbed" src="https://user-images.githubusercontent.com/89538802/134545580-b61f8d5e-aec9-49ee-b999-699ebd4f8466.PNG">

  #####Math
  
  <img width="234" alt="Math_Grade_Scrubbed" src="https://user-images.githubusercontent.com/89538802/134545621-b1fb2cd7-2cef-4ede-972e-2ca86fde31b7.PNG">


  * Scores by school spending
  * Scores by school size
  * Scores by school type


## **Summary:**

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. change 1
2. change 2
3. change 3
4. change 4
