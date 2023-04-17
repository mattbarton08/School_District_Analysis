# School District Analysis

## Overview:
In this analysis, I looked at the math and reading scores of all students in the district and looked at which factors might have contributed to high or low passing rates. The ninth grade scores for both math and reading had to be dropped due to academic dishonesty which changed the story the data tells.

## Results:

### How is the district summary affected?
Changing these grades did not greatly affect the district math or reading scores or passing percentages. When rounded to the nearest percent, the percent of students who passed math, reading, and overall was the same.

### How is the school summary affected?
In the school summary data frame, we can see that Thomas High School's passing percentages dropped slightly after dropping the ninth graders' scores. <br>
Before: ![Alt text](https://i.imgur.com/Xiawnfq.png "Screenshot_2")
After: ![Alt text](https://i.imgur.com/bowI0uw.png"Screenshot_1")

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Thomas High School is still the second highest performing school even though their scores dropped.<br>
Before: ![Alt text](https://i.imgur.com/ZcP26Rb.png "Screenshot_3")
After: ![Alt text](https://i.imgur.com/UXLPYVq.png "Screenshot_4")

## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
All data looks the same in the grade-level data drame other than Thomas High School's ninth grade numbers, which are replaced by "NaN".

### Scores by school spending
The school spending data did not visibly change after dropping the scores.
![Alt text](https://i.imgur.com/IzMnRHw.png "Screenshot_5")

### Scores by school size
The scores by school size did not change after rounding the scores. This is what the data looked like before and after:
![Alt text](https://i.imgur.com/7hborps.png "Screenshot_6")

### Scores by school type
The scores by school type were slightly less for charter schools after dropping the ninth graders' scores but again it does not show up after rounding the data. Here is the final rounded data:
![Alt text](https://i.imgur.com/yRuEau1.png "Screenshot_7")

## Summary: 
The biggest change after dropping the scores was that the passing percentages for Thomas High School dropped slightly. The overall scores for ninth graders in the district also dropped slightly but not enough to show up after rounding the scores. The same happened in charter school and medium size schools, where the passing percentages dropped but not enough to show up after formatting the data. In the grade level data, the only difference was that ninth graders at Thomas High School did not have scores anymore.
