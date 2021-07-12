# School_District_Analysis

## Overview 
The purpose of this analysis was to redo a previous analysis done for Maria on school performance in the wake of reports of academic dishonesty. It seems that the scores for 9th graders at Thomas High School were altered, and therefore the analysis had to be redone in order to get a more honest picture of school performance.

## Results
1. How is the district summary affected?
    - Here are the results of the original district summary analysis:
    
    ![old_ds_df](https://github.com/typicalchazz/School_District_Analysis/blob/main/Resources/Images/Original_District_Summary_df.png)
    
    And here are the results of the new district summary analysis after replacing the values of 9th grade Thomas High students:
    
    ![new_ds_df](https://github.com/typicalchazz/School_District_Analysis/blob/main/Resources/Images/New_District_Summary_df.png)
    
    While not much has changed, you can see that the average math score in the original district summary analysis is 79.0, while in the new district summary analysis it's 78.9. The percentages differ, but that's due to formatting/rounding and not a result of the data differing.

2. How is the school summary affected?
    - Here are the results of the original school summary analysis:

    ![old_ss_df](https://github.com/typicalchazz/School_District_Analysis/blob/main/Resources/Images/Original_School_Summary_df.png)

    And here are the results of the new school summary analysis after replacing the values of 9th grade Thomas High students:

    ![new_ss_df](https://github.com/typicalchazz/School_District_Analysis/blob/main/Resources/Images/New_School_Summary_df.png)

    While the differences are slight, you can see that in the original school summary analysis:
        - The average math score was 83.418349,
        - The average reading score was 83.848930,
        - The percentage of students passing math was 93.272171%,
        - The percentage of students passing reading was 97.308869%, and 
        - The overall percentage of passing students was 90.948012%.
    
    In the new school summary analysis:
        - The average math score was 83.350937,
        - The average reading score was 83.896082,
        - The percentage of students passing math was 93.185690%,
        - The percentage of students passing reading was 97.018739%, and 
        - The overall percentage of passing students was 90.630324%.
        
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - It didn't have a significant impact, but it did have some effect. Regardless of whether you include the 9th grade scores or not, Thomas High still has the 2nd highest overall passing percentage and 7th hightest passing math percentage, but in the original Thomas High was 1st for passing reading percentage, while the newest analysis shows them 3rd.

4. How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade:
        - The math score dropped by 0.1 while the reading score stayed the same.
    - Scores by school spending:
        - The scores by school spending differed only in the hundreths and beyond and had no significant impact. 
    - Scores by school size:
        - Like school spending, the scores differed only in the hundreths and beyond, having no significant impact.
    - Scores by school type:
        - The values differ insignificantly and have no impact on the results of the analysis.

## Summary
Overall, the exclusion of the 9th grade Thomas High School students didn't have a profound impact on the results of the analysis, yet there still was an impact. From the new analysis we can see that with the removal of that data: 
    
    1. The average district math score was 0.1 point lower,
    2. The percentage of students who passed math dropped by 0.2%,
    3. The percentage of students who passed reading dropped by 0.3%, and
    4. The percentage of overall passing students dropped by 0.1%

These changes are very small, almost exclusively to the right of the decimal point. However those slight changes do have impact in some areas, such as when comparing the reading passing percentage: Thomas High School went from 1st to 3rd, the difference between gold and bronze. 


