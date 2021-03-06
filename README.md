# School_District_Analysis

## Overview
Helping the city's chief data scientists with analyzing the standardized test data of multiple different schools to uncover any performance trends and patterns. The analysis will be used **to help the School Board with creating informed decisions on where to allocate school budgets and priorities**. 

## Resources
- We will be looking at multiple of different databases aggragated into one: (**clean_students_complete.csv**)
  - This data includes important information on each individual's school, thier math scores, their reading scores, etc.
  - We will be using Python libraries such as **Pandas** and **Numpy** to help clean and to analyze the data

## Results
After cleaning our data so that it is fit for analysis, we organized our data to see the differences in standardized test performances based on a few different criteria:
- The first criteria we looked at was the difference in standardized testing performances between grades (9th-12th). However, we have found that the difference in grade does not affect the performance of the students. This is shown as the averages for both reading and math scores are only tenth of a percent off from each other.

### Math Scores 
![Math Score #1](Pictures/math_scores_by_school_one.png)
![Math Score #2](Pictures/math_scores_by_school_two.png)

<br>

### Reading Scores 

![Math Score #1](Pictures/reading_scores_by_school_one.png)
![Math Score #2](Pictures/reading_scores_by_school_two.png)

- Another critea we looked at was the difference between the different school types. Through our analysis, it is clearly evident that the different school types plays a major role in the performance of the students. It is shown that students who attend Charter schools do significantly better than District school students in all performance aspects.

### School Type

![School Type](Pictures/school_type.png)

- Another criteria we looked at was how school size can affect the indiviual student's performances. From the graph below, we can see that size does play a factor in school performance once the student capcity begins to exceed 2000. Once exceeding 2000 students, we can see that the performance metrics begin to greatly decline. 

### School Size

![School Size](Pictures/student_size.png)

- At last, we look at the different ranges a school has in their budget per student and how it affects the student's performance. Suprisingly enough, our findings were very counterintuitive and completely invalidated our hypothesis. It can be seen as a school's budget per student goes up, the greater decline of the performance metrics. 

### Budget per student

![Student Budget](Pictures/spending_per_student.png)

## Summary
After changing the scores for reading and math, there were some slight differences. Some of the biggest differences was the significant changes in performance metrics within THS. This has also raised THS to be on of the top 5 schools after these changes were pushed. Because the difference in performance metrics in THS, this also affects the metric averages for all the grades. After the changes, the metric averages goes up significantly! There were no significant changes in the criterias mentioned above (school type/ School Size/ budget per student)

