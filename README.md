# school_district_analysis
## Overview (background and purpose)
The purpose of this module was to introduce us to coding via jupyter notebooks and pandas. To accomplish this, we were given the following scenario: A school board tasks an analyst with performing a school analysis on the district. Furthermore, when it is suspected that academic dishonesty may be occurring at one of the grade levels of one of the schools (ninth graders at Thomas High School) we are tasked with removing their scores and analysing its affect on the school analysis.
## Results
Original school analysis:

![thomas_before](https://user-images.githubusercontent.com/94420548/151603595-8ce4eeed-7a99-4690-9642-d8524263a47a.png)

Updated school analysis:

![thomas_after](https://user-images.githubusercontent.com/94420548/151603674-88abc3ea-4ae8-42cc-9e69-e17f0c979ac8.png)

 - The district summary is virtually unaffected by the replacement of the ninth graders' scores.
 - Similarly, the school summary is unaffected except for the row containing the data for Thomas High School, which is affected only very slightly.
 - Replacing the scores of Thomas High School's ninth graders did not affect its performance relative to to other schools. Before and after score
   replacement, Thomas High school was still the second best performing school in the district.
 - Replacing the scores of Thomas High School's ninth graders did not affect math or reading scores by grade except
    for Thomas High School insofar as Thomas High now had no scores to report for their ninth graders; and even then, it did not affect their 10-12 graders.
 -  Replacing the ninth grader's scores had virtually no effect on scores by spending ranges per student; the $630-644 bin decreased by roughly
    0.08. In other words, the bin did not decrease by even one full percent.
 -  Replacing the ninth graders' scores had no affect on grouping the scores by school size.
 -  Replacing the ninth graders' scores had no affect on grouping the scores by school type.
## Summary
The four primary changes that occurred in the updated analysis were as follows:
1. Thomas High School's "Average Math Score" decreased from 83.42 to 83.35.
2. Thomas High School's "Average Reading Score increased from 83.85 to 83.90.
3. Thomas High School's "% Passing Math" decreased from 93.27% to 93.19%.
4. Thomas High School's "% Passing Reading decreased from 97.31% to 97.02%.
These changes are so minute that they have an insignificant effect on the results of the school analysis. I would inform the school board that if these scores of the Thomas High School freshmen need to be taken out, not to worry because it will leave the analysis virtually unaffected.
