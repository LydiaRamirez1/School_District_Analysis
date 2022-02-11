# School_District_Analysis
## Overview
The purpose of this analysis was to use the data from the test scores in the district in order to determine budgeting and other allocation of resources for the next school year.
## Results
District Summaries:
The original district summary is shown below:
![mod 4](https://user-images.githubusercontent.com/89167956/153621607-8d55d65f-3a84-4600-a4e0-c84f225a048a.PNG)
Next is the district summary without the scores from the Thomas High School 9th graders:
![mod 4 pt 2](https://user-images.githubusercontent.com/89167956/153621700-c24bc315-7a55-4493-9d41-7ba72b1e052e.PNG)
The scores did effect the data slightly, as almost every category shows very slight drops in their value.

School Summary for Thomas High School:
- The specific values of Thomas High School remained largely unchanged after the data points for the 9th grade were removed once everything was taken into account.
- Thomas High School's standing in the district kept its position as the second best school in the district.
- The 9th grade scores were no longer taken into account, but the other grades were unaffected.
- The scores by spending, size, and school type were all also unaffected.

## Summary
Several changes had to be made to the analysis in order to get the correct numbers with the removal of the scores for the Thomas High School 9th graders. The changes included the total amount of students overall had to be changed in order to not affect the averages by using too many students, the total amount of students for Thomas High School in 10th through 12th grade had to be calculated in order to get the correct scores, the 9th grade scores for Thomas High School had to be changed to NaN within the data frame itself, and the data had to be specifically filtered to find the 9th graders from Thomas High School.
