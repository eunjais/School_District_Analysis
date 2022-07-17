# School_District_Analysis
## Overview
This analysis project provides a comprehensive analysis and overview of the seven schools present in the district. Key metrics for school evaluation, such as grade, average scores, budget, student size and school type will be utilized to study the variable brackets and its relation to students' academic success.

## Results
To start with, we cleaned student names and got rid of prefixes as well as suffixes that are not relevant. These included: 
- Dr.
- Mr. / Mrs. / Miss
- MD / DDS / DVM / PhD

This did not impact the data. However, taking into account the potentially large impact of academic dishonesty due to the alteration of Thomas High School's math and reading scores for the 9th grade population, this analysis has nulled their records when calculating the remainder of the student-school statistics.

The impact of this is as follows:
- decrease in total population count for students
- shift in the average of math and reading scores for students (dependent on population)
- shift in the percentage of math, reading and overall passing rates for students
- spending per student calculation (dependent on population)

### District Summary Analysis

Before voiding Thomas High 9th Grade Scores:
![district_summary](https://user-images.githubusercontent.com/107447038/179427241-b0a1b4e9-5bbf-4321-ae89-974693afd69e.png)

After voiding Thomas High 9th Grade Scores:
![district_summary_ch](https://user-images.githubusercontent.com/107447038/179427236-a1458b88-d6fb-4b0c-acde-31c7869287f2.png)

Across 15 schools, 39,170 students and with a total budget of $24649428.00, this school district shows the average math score of ~79 and a reading score of ~ 82, with:

- 75 % total students passing math
- 86 % total students passing reading
- to a total of 65 % students passing both math and reading in their classes.

We see a subtle drop of the average math score as well as the % of overall math, reading and combined passing rate after voiding Thomas High 9th grade scores. 

### School Summary Analysis
![image](https://user-images.githubusercontent.com/107447038/179427388-f276f65a-5cec-4318-bf8a-8ce81e8af0a8.png)

School analysis by school size
![image](https://user-images.githubusercontent.com/107447038/179428023-4cbbde1c-d04a-4f76-bf99-b17935663e6e.png)

Small and medium schools have a tendency to harbor much more successful students than those of large schools.
- Small and medium schools all have 90+ % rate of passing in math, reading, and the two subjects combined.
- Compared to the large schools, which have 70 % rate of passing in math, 83 % in reading, and a 58 % overall passing rate. 

School analysis by school spending
![image](https://user-images.githubusercontent.com/107447038/179428069-262ca54f-b84c-4cce-b2de-b7434048a7db.png)

The quantity of spending range is inversely correlated to the success of students. The lower the spending range, the more students succeeded across math, reading and overall performance combined. 

School analysis by school type
![image](https://user-images.githubusercontent.com/107447038/179428121-862c40f5-11ce-4da2-ac7d-937526586596.png)

Charter schools had much higher rate of students passing subjects, as well as higher scores over all. The difference is rather striking when one compares the percentages;
- While Charter schools have 94 % passing math, 97 % passing reading, and 90 % of overall students passing in both subjects,
- District schools have 67 % passing math, 81% passing reading and 54 % of overall students passing in both subjects.

### Thomas High School Performance Analysis

Before Nulling 9th grade scores
![image](https://user-images.githubusercontent.com/107447038/179427718-3afa56e5-dcff-4a56-8108-db492ae968c9.png)

After Nulling 9th grade scores
![image](https://user-images.githubusercontent.com/107447038/179427464-ea8b093f-4cc2-4a8e-8277-cc374926984b.png)

For this school year, Thomas High SChool performed well, landing in the top five schools of the school district. 

Discounting the 9th grade population for academic dishonesty:
- The average math score: 83.3
- The average english score: 83.9
- 93.2% of students are passing math 
- 97.1% of students are passing reading
- 90.6% of students are passing overall.

## Summary
Of the fifteen schools, Thomas High School still performed well, landing in the top five echelon within the school district. However, this discounts the contribution of 9th grade math and reading scores. Compared to its performance prior to the omit:

1. The average math scores have fallen from 83.4 to 83.3. 
2. The average english score has risen from 83.8 to 83.9 
3. The passing percentage of math have dropped a tenth of a percent (93.3 % to 93.2%)
4. The passing percentage of reading have dropped more (97.3 % to 97.1 %)
5. The overall passing percentage of students have dropped from 90.9 % to 90.6 %.

Further analysis is required to study the relationship between charter schools and budget as well as size. These different matrices / factors leave a large impact on student success and could assist in better academic results for the future populations. Furthermore, a re-evaluation is in order after the extent of Thomas High's academic dishonesty is leveraged. 
