# School_District_Analysis
Module 4-Anaconda

## Overview
Maria from the city school district requires an update on the school district data. This is due to the occurrence of an alteration in Thomas High School's ninth grade scores. An update of the math and reading scores will be carried out by relpacing all ninth grader values in Thomas High School with null (NaN). This will result in cleaned data which analysis will be carried out on to evaluate the schools' performance. These analysis will be used by the school district board to aid them in budgeting decisions


## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

### How is the district summary affected?
Based on the results below, the district summary was not impacted.
![image](/Results/1DS.png)
### How is the school summary affected?
The average score for math and reading does not get affected, but the percentages passing (math, reading, & overall) all drop arround 30% each.  
![image2](/Results/2DS.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School performance is not affected relatived to other schools and it remains in the top 5 performing schools (2nd place) both before and after the ninth graders’ math and reading scores were dropped. 

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
As per below no impact has occurred due to the replacement.
![image3](/Results/3.png)

#### Scores by school spending  
As per below no impact has occurred due to the replacement.
![image4](/Results/4.png)

#### Scores by school size  
As per below no impact has occurred due to the replacement.
![image5](/Results/5.png)

#### Scores by school type  
As per below no impact has occurred due to the replacement.
![image6](/Results/6.png)


# Summary
After the comparison, the most evident change is in the school's individual summary, wherein the percentage passing of math, reading, and overall dropped significantly as we are omitting an the ninth grade's scores but considering the all students when calculating the percentages. This is then rectified by ommitting the count of grade nine students and the percentage passing is higher and more accurate as per below:
![image7](/Results/7.png)
