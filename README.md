# School_District_Analysis
Module 4

## Overview 

### Purpose
The PyCitySchools Analysis is performed to determine how the 9th grade scores for Thomas High School affect the results of the district summary reportings. The scores are removed from the data and to repeat the analysis for comparison to the original analysis. Results will remove any possiblity of academic honesty and uphold state-testing standards. 

## School_District Analysis Results
- District Summary 
  - Average Math Score decreased from 79.0 to 78.9
  - Average Reading Score remained at 81.9
  - % Passing Math decreased from 75% to 74.8%
  - % Passing Reading decreased from 86 to 85.7%
  - % Overall Passing decreased from 65% to 64.9%
 
- School Summary
  - Only Thomas High School results were affected
    - Average Math Score decreased from 83.418349 to 83.350937
    - Average Reading Score increased from 83.848930 to 83.896082
    - % Passing Math decreased from  93.272171 to 93.185690
    - % Passing Reading decreased from 97.308869 to 97.018739
    - % Overall Passing decreased from 90.948012	to 90.630324

- Replacing the ninth graders scores does not affert Thomas High School's performance relative to other schools. After removing ninth grade scores, the top five performing schools remains the same. 
  - Cabrera High School	
  - Thomas High School	
  - Griffin High School	
  - Wilson High School	
  - Pena High School	

- Replacing the ninth-grade scores also affected the following:
  - Math and reading scores by grade for Thomas High School were replaced by NaN
  - Scores by school spending in the $630-644 range were decreased
  - Scores by school size in the Medium (1000-2000) category were decreased
  - Scores by school type of Charter were decreased 

## School_District Analysis Summary

This PyCity Schools Analysis was minimally affected by removing the 9th grade scores for Thomas High School. The lowered score results may not confirm any alteration of the data, but removal of the scores provides assurance of the data accuracy. The overall Thomas High School passing percentages were lowered below 70% when calculated on the total student population after removing the ninth grade scores. This measure would not be accurate as not all ninth grade scores should be assumed as failing. A more accurate result is returned by also removing the count of the ninth grade students from the total school population.
