# School_District_Analysis

## Project Overview

 Chief Data Scientist for a large school district has asked us to help complete analysis of the schools within their district. They are hoping to obtain data on how to allocate the budget to the different types of schools - District School and Charter Schools.

While analyzing the data, the school board suspects that some grades from Thomas High Schools may have been altered and there is high level proof of fraud. They would also like us to help them comb through the 9th grade math and reading schools to help determine if there is a reasonable amount of fraud detected.

## Objective
Our objective is to isolate and recalculate math and reading scores at Thomas High school and observe if there is any amount of change to indicate fraudulent scores.

### Resources

Data Sources:
    clean_students_complete.csv
    missing_grade.csv
    schools_complete.csv
    students_complete.csv

Software:
    Python 3.9
    Jupyter Notebooks 6.1.4
    Anaconda 3.8.5

Code Techniques Utilized:
Pandas
Numpy

## Results

### Initial DataFrame with Existing Data
    Shows the overall passing grade for Thomas High is 65%

![image](https://user-images.githubusercontent.com/59187034/118729150-07c5a600-b7fb-11eb-9263-f616306588a1.png)

### DataFrame after Removing 9th grade math and reading scores
    We removed 461 students from the initial data set.
    Now shows the overall passing grade for Thomas High is 90%

![image](https://user-images.githubusercontent.com/59187034/118729205-19a74900-b7fb-11eb-9143-3f673c5ed40c.png)




### Thomas High now a Top 5 School in district
    Before removing scores, Thomas High was a bottom 5 performing school, now they are comfortable in the top 5

![image](https://user-images.githubusercontent.com/59187034/118729244-262ba180-b7fb-11eb-8c4d-3db13d481851.png)

### Spend Per Student

    After the Thomas High School Math and Reading Scores were taken out, we were tasked with looking at spending per student. We had to make customized spending ranges to visualize the differences on how budgeting was allocated from school to school.

![image](https://user-images.githubusercontent.com/59187034/118729260-2c218280-b7fb-11eb-8e37-57008abbf307.png)

    As seen in this data frame, schools that had a higher spend per students, tend to have lower test scores those who spend higher than ~$630 per student

### School Performance by Size

    We also created a data frame to show how schools perform depending on their size. Schools on the smaller size (small to medium) tend to have better scores than schools considered large.

![image](https://user-images.githubusercontent.com/59187034/118729279-35125400-b7fb-11eb-9f1e-d679884e697d.png)

### School Performance by Type
    
    In this data set, we had two different types of schools, Charter and district schools. According to this data frame that we created arranged by "School Type" we can see that Charter schools tend to produce much better scores than district schools

![image](https://user-images.githubusercontent.com/59187034/118729291-3b083500-b7fb-11eb-843a-d278cfc8c6ad.png)

## Summary

    After analyzing the data set and removing the 9th grade math and reading test scores from Thomas High School overall district performing increased. We removed 461 student scores (a district total of roughly 40,000 students) from the initial data set. By removing the scores, the overall metrics of the school did not change, in fact by removing the suspicious scores, the averages actually increase.

  It seems more likely that schools that spend LESS on their students as well as being smaller in overall size, tend to have more success than larger schools that spend more per student.








