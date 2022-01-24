# School_District_Analysis

## Project Overview
A data scientist with a city school district has assigned the following tasks to reveal performance trends and patterns.

1. Replace ninth-grade reading and math scores for Thomas High School due to academic dishonesty
2. Complete a school district analysis to show the following metrics:
    - District summary
    - School summary
    - The top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score for each grade level from each school
    - The average reading score for each grade level from each school
    - The scores by school spending per student, by school size, and by school type

## Analysis Results
- How is the district affected?
  - Before replacing scores for Thomas High School
    - Average Math Score = 79.0
    - Average Reading Score = 81.9
    - % Passing Math = 75.0
    - % Passing Reading = 85.8
    - % Overall Passing = 65.2
  - After replacing scores for Thomas High School   
    - Average Math Score = 78.9
    - Average Reading Score = 81.9
    - % Passing Math = 74.8
    - % Passing Reading = 85.7
    - % Overall Passing = 64.9  
    
![District Before](https://user-images.githubusercontent.com/96347933/150705835-f7e8eb48-1eae-495a-be98-b65b1d4219fa.PNG)

![District After](https://user-images.githubusercontent.com/96347933/150705862-a5d97126-6613-419c-ac66-0ad681bcfba6.PNG)

- How is the school summary affected?
  - Before replacing scores for Thomas High School
    - Average Math Score = 83.4
    - Average Reading Score = 83.8
    - % Passing Math = 93.3
    - % Passing Reading = 97.3
    - % Overall Passing = 90.9
  - After replacing scores for Thomas High School   
    - Average Math Score = 83.4
    - Average Reading Score = 83.9
    - % Passing Math = 66.9
    - % Passing Reading = 69.7
    - % Overall Passing = 65.1  

![Thomas Before](https://user-images.githubusercontent.com/96347933/150663366-5504326d-0fd5-4a7d-9afb-39cda1204615.PNG)

![Thomas After](https://user-images.githubusercontent.com/96347933/150663377-12d0880b-d9f3-4bbb-a2b8-7c77047defc4.PNG)

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
  - Replacing the scores has a significant impact on the % of overall passing, dropping from 90.9% to 65.1%.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - Replacing math a reading scores only impacts Thomas High School 9th graders, all others remain the same
  - Scores by school spending 
    - Slight change in the $630-644 scores by school spending group.  Less than 0.1 percent change in each category.
  - Scores by school size
    - Slight change in the 1000-2000 medium school size group.  Again less than 0.1 percent change.
  - Scores by school type
    - Sligh change in the charter school type category.  Again less than 0.1 percent change.

## Summary
- District Analysis- Slight decrease in math and reading percentages due to change to ninth grade scores at Thomas High School.  This decreased the overall passing rate slightly
- School Analysis- By changing ninth grade math and reading scores for Thomas High School, their performace saw a significant drop to overall passing percentage from 90.0% to 65.1%
- Math and reading scores by grade- Only 9th graders at Thomas High School were affected
- Scores by school spending/school size/school type- Limited impact by changing ninth grade math and reading scores for Thomas High School


