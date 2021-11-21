# school_district_analysis

## Overview

### Purpose
The objective of this challenge was to perform an analysis on test scores from several different high schools in a school district.
This analysis would include a breakdown of performance based on money allocated to the schools, by grade, by school size, and by school type.
Suspicious scores were removed from the analysis.
This analysis can help inform the school district on future resource allocation.

## Results
Removing the incorrect math and reading scores from the 9th grade class of Thomas High School produced the following results:

![district summary before](Resources\district_summary_before.png)
![district summary after](Resources\district_summary_after.png)
- The total number students in consideration went from 39,170 to 38,709.
The average math score reduced from 79.0 to 78.9.
The average reading score remained the same at 81.9.
The percentage of students passing math dropped from 75% to 74.8%.
The percentage of students passing reading dropped from 86% to 85.7%.
The overall percentage of students passing both math and reading dropped from 65% to 64.9%.
This information can be gleaned from the images above, with the latter image being the district summary after the 9th grade students from Thomas High School were removed.

![Thomas high school before](Resources\thomas_high_school_summary_before.png)
![Thomas high school after](Resources\thomas_high_school_summary_after.png)
- The school summary was only changed for the Thomas High School row (naturally).
The average math score dropped from 83.42 to 83.35.
The average reading score actually rose from 83.85 to 83.90.
The percentage of students passing math dropped from 93.27% to 93.19%.
The percentage of students passing reading dropped from 97.31% to 97.02%.
The percentage of students passing both reading and math dropped from 90.95% to 90.63%.
This information can be observed from the images above with the former being the results before the academically dishonest results were removed.

![top 5 schools before](Resources\top_5_before.png)
![top 5 schools after](Resources\top_5_after.png)
- Thomas High School occupied the number 2 position in the top 5 schools (based on the overall passing percentage) with the academically dishonest students results included.
After the offending scores were removed Thomas High School still occupied the second position.

- Removing the ninth grade scores from Thomas High School also produced the following effects:
  - The math and reading scores for the Thomas High School 9th graders went from 83.6% and 83.7%, respectively to NaNs since it was the ninth graders scores that were removed.
  The remaining grade scores weren't affected.
  - Thomas High School falls into the $630-$644 spent per student category of schools.
  Removing the ninth grade students scores produced no appreciable change across any of the tracked metrics for the $630-$644 spent per student up to the rounding that was used.
  - Thomas High School falls into the Medium (1000-2000 students) category.
  The removal of the ninth grade students scores produced no appreciable change across any of the tracked metrics for the Medium sized schools up to the rounding that was used.
  - Thomas High School is a charter school.
  Again, the removal of the ninth grade students scores produced no appreciable change across any of the tracked metrics for charter schools up to the rounding that was used.
## Summary
From the analysis that was done the school district summary showed the largest change in percentage of students passing reading at 0.3%.
The most surprising result was that Thomas High School actually had a rise in the average reading score with the removal of the ninth grade students' academically dishonest scores.
Thomas High School did not drop in rank in that they are still ranked the second highest school in terms of the overall passing percentage for both math and reading.
In terms of the results of the schools organized by school spending per student, school size, and school type there was no change across any metric based on the rounding of the results that was used.