# School District Analysis
## Overview:
### Objective:
We were given student's grades and tasked with determining the grade averages by school, budget (per student), school size, and school type. I also calculated the average scores by grade class as well. The 9th grade class at THS may have had some faulty scores, so we were asked to calculate new totals while excluding the 9th grade class and analyze any variances in the results.

### Analysis:
After removing the THS 9th graders from the calculations, there was a very slight decrease in the overall district numbers. Although, the decrease was insignificant enough that it did not impact the calculations after rounding appropriately.
---
## Results
### Below are the results before and after removing the 9th graders scores from THS
- **District Summary (Average Math -0.1)**
- ![district_summary_df](resources/district_summary_df.png)
- - **Before:**
- - Average Math: 79.0, Average Reading: 81.9, % Passing Math: 75%, % Passing Reading: 86%, % Passing Overall 65%
- - **After:**
- - Average Math: 78.9, Average Reading: 81.9, % Passing Math: 75%, % Passing Reading: 86%, % Passing Overall 65%
- **School Summary**
- ![per_school_summary_df](resources/per_school_summary_df.png)
- - **Thomas High School Before:**
- - Average Math: 83.41, Average Reading: 83.84, % Passing Math: 93%, % Passing Reading: 97%, % Passing Overall 91%
- - **After:**
- - Average Math: 83.35, Average Reading: 83.89, % Passing Math: 93%, % Passing Reading: 97%, % Passing Overall 91%
- **How does replacing 9th grade THS students scores affect:
- Thomas High School remains #2 overall. Excluding the 9th grade class had a neglible inpact on the overall data.
- - **Math and Reading scores per grade:**
- - - After removing THS from the 9th grade averages, 9th Grade Math fell from 78.9 to 78.3 and 9th Grade Reading fell from 81.9 to 81.8
- - **Scores by school spending**
- - - There were insignificant decreases in the "$630-$644 (Per Student)" category of school, but the decrease would not have any changes to data when rounded appropriately.
- - **Scores by school size:**
- - - THS falls into the "Small" size category (<1750), which once again showed insignificant decreases that would not change the data when rounded appropriately.
- - **Scores by school type:**
- - - THS falls into the "Charter" type category, which once again showed insignificant decreases that would not change the data when rounded appropriately.
---
## Summary:
After excluding the 9th graders from THS and running the analyses again, there was a neglible decrease in the overall results. 9th Graders from THS make up 1.2% of the total students analyzed. THS remained #2 for "% Overall Passing", after a .3% decrease when we excluded the 9th grader's scores. Excluding the 9th graders from THS in our analysis gives us accurate numbers that seem to mimic our original data. When we calculated bugedget per student, scores by school spending, and scores by school size; we included the 9th graders so that the population counts would be accurate for THS.

### Notable:
If we had included the 9th graders in the counts with NaN for their score (essentially a 0 for these purposes):
- THS "% Overall Average" decreases from 91% to 65%.
- THS drops from #2 overall to #8.
- THS decreases the "$630-$644" Spending Range (Per Student) "% Overall Passing" from 63% to 54%.
- THS decreases the "Small" school size "% Overall Passing" from 90% to 84%.
- THS decreases the "Charter" school type from 90% to 87%.
