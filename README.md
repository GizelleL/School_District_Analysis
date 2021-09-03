# School_District_Analysis
## Objective: 
The purpose of the project is to provide evidence of whether there was academic dishonesty. Using the data provided we can make further understand the students’ scores and the overall scores for those schools in the differing districts, and we can confirm whether the averages of Thomas High School ninth graders have been altered.
## Results: 
### District Summary
The district summary provides a starting point as the data frame of the 15 schools can be used in comparison to the Thomas High School data frame

##### District Summary for Schools
![image](https://user-images.githubusercontent.com/84821870/131926655-29a84b70-655f-4aeb-867b-e859e5ff7fc2.png)

Again, comparing the above results to the Thomas High School data will allow the ability to confirm whether the ninth grade scores appear to be altered. Given that there were only 461 ninth grade students from Thomas High School (0.01% of the total students in our data frame), there average math and reading scores will have less impact on the averages and percentages. 

### School Summary
The school summary below reflects the scores and passing percentages of Thomas High School which includes the 9th to 12th grade students: 

##### School Summary including Thomas High School 9th to 12th grade students:

![image](https://user-images.githubusercontent.com/84821870/131926940-27073608-6019-4b32-bd04-4e4b59ba8e30.png)

In comparison, the below data frame shows the scores and percentages for Thomas High School 10th to 12th grade students. The Thomas High School Average Math Score is 83.35% and Average Reading Score is 83.89% (see District Summary for Schools above)whereas the Average Math Score for all schools is 78.9% and a Average Reading Score of 81.9% (see School Summary including Thomas High School 9th to 12 grade students data frame above)

Although the Thomas School Average Reading Score is slightly above the mean for all schools in the district, attention must be given to the difference in the Average Math Score of Thomas High School in comparison to the Average Math Score of all schools. There is a difference of ~5% which may possibly indicate that the Average Math Score and Average Reading Scores are inflated. 

Also, when reviewing the Thomas High School 10 – 12 grade students data frame, it shows that the 9th grade students skewed the average percentage into the lower quartile range. For instance, when comparing the % Passing Math, % Passing Reading and % Overall Passing scores between the School Summary including 9th to 12th grade Thomas High School students data frame to the Thomas High School 10th - 12th grade students data frame there is a larger spread between these percentages. In the 9th to 12th grade summary, the percentage passing math is 66.91%, the percentage passing reading is 69.66% and the percentage of overall passing is 65.07%. This shows that the 9th grade scores are skewed as the passing percentages are lowered when factoring them into the data frame

##### Thomas High School Summary omitting 9th grade students
 ![image](https://user-images.githubusercontent.com/84821870/131927273-9ec063d4-1378-4a6d-8427-1ebb45a2c5cc.png)
 
 ### Further Replacing of 9th Grade Scores and the effect the Math and Reading Scores by grade, Scores by School Spending, Scores by School Size and Scores by School Type
 
#### How does replacing the 9th grade scores affect Scores the Math and Reading Scores by Grade
Using the Thomas High School Data Frame, when we account for the 9th grade scores, the average math score and average reading score is lower then the scores for the 10th – 12th grades only

##### Average Math and Average Reading Score per School
![image](https://user-images.githubusercontent.com/84821870/131929523-3516319d-52ae-443b-a769-db34a914c35e.png)

The above shows that the average math score for all schools is 80.42% and an average reading score for all schools is 82.53% and although the average math and reading scores for Thomas High School are close to these averages, it would still reflect academic dishonesty given that there is a variance in the % passing math, % passing reading and % overall passing. From inflating the 9th grade student scores, it balances the average of Thomas High School, hiding the inflated grades. 

#### How does replacing the 9th grade scores affect Scores by School Spending
The minimum average budget per student for all schools is $578.00 and the maximum average budget per student for all schools is $655.00.
There are 3,376 students throughout the list of schools in the higher half of the student budget as indicated in the student bins, of these students, Thomas High School has a budget of $638.00 per student budget, placing themselves in the upper half (upper quartile) of the per student budget. Yet, when the 9th grade scores are ommitted, the average math score drops to 77.86% and the average reading score drops to 81.38%. Further, the percentage of students overall lowers to 58.81%
Given the assumption that higher student spend would benefit and raise the student scores, in this case it was lowered. This is a potential indication of academic dishonesty of the 9th grade students at Thomas High School.

##### Min and Max per Student Budget

![image](https://user-images.githubusercontent.com/84821870/131931381-5841eebd-1a08-48c5-a467-630c445a6ec5.png)

##### Average Budget per Student:

![image](https://user-images.githubusercontent.com/84821870/131931424-9e0c4297-152e-4ffe-b7c7-f156953f4cae.png)

#### How does replacing the 9th grade scores affect Scores by School Size
After categorizing the schools into bins based on the average budget per student, it is evident that there were more students in the larger budget bins. Interestingly, the larger budget per student bin, reflecting a higher student count, has lower average math and average reading scores.  This is evident in the Student Size and School Budget Bins Data frames as the average math score for the larger budget per student bin is 77.75%, with an average reading score of 81.34%. In comparison, the extra small category, which has less students and a smaller per student budget reflects an average math score of 83.82% and average reading score of 83.93% 
It draws the question: why is the group with a larger budget per student and being the group with more students, have lower average scores compared to the extra small group with less budget per students and being the less students in their group? (Rhetorical Question)

##### Student Bins: 

![image](https://user-images.githubusercontent.com/84821870/131931958-49b5ad43-d3fd-46ec-aa36-5e646cda0d32.png)

##### Student Size and School Budget Bins: 

![image](https://user-images.githubusercontent.com/84821870/131931985-5c5aacff-e9a7-4e64-b0b2-d2c3fd5e6d87.png)

#### How does replacing the 9th grade scores affect Scores by School Type

When omitting the 9th grade scores from School Type did not provide enough sufficient information about the average math and reading scores. 

However, it is evident that the average reading score for Charter schools is 83.90% and the average math score for Charter schools is 83.46%. In comparison, the average reading score for District schools is 80.96% and the average math score for District schools is 83.46%

Thomas High School is a Charter School and based on the table below, their math and reading score are closer to the mean of the average math and reading scores for Charter Schools: 

![image](https://user-images.githubusercontent.com/84821870/131932434-3047a836-dae6-4883-86bb-6165182337dc.png)

## Summary:

Four changes of the school district analysis after reading and math scores have been replaced include: % Passing Math, % Passing Reading, % Overall Passing and the Total Number of Students used for analysis. 
