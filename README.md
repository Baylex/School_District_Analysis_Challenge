# School_District_Analysis_Challenge

## Overview of the school district analysis: Explain the purpose of this analysis.
A school district asked for a snapshot of several key metrics by each school campus and by the district level.  The main analysis focused on the performance of math and reading scores disaggregated several ways in preparation for a board meeting.  However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating.  The school board asked for the data to be removed and analyzed again for a comparison. 

## PythonData Environment
Anaconda version 1.7.2
Conda version 4.9.0
Jupyter-Notebook version 6.1.4
ipykernal version 5.3.4
Python version 3.7.7
Pandas version 1.1.3
Numpy version 1.19.1
GitBash version 2.28.0.windows.1

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

### How is the district summary affected?
Original Analysis:
![Pic 1](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/1_dist_sum_2_decimals.PNG)

The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percents of passing math, passing reading, and the overall passing.  The total count of students did not change as that was run on the count of the student ids, which was not turned into null data. 

Adjusted Analysis:
![Pic 2](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_dist_sum_2_decimals.PNG)

When comparing the two charts, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set.  The change was less than a 1% difference and the numbers would still round to the same whole number.  

### How is the school summary affected?


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

### How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade

### Scores by school spending

get pic of the decimals - not formated 

### Scores by school size
![Pic 4](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/1_school_size_perf.PNG)
![Pic 5](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_school_size_perf.PNG)

git pic of decimals - not formatted

### Scores by school type

![Pic 6](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/1_school_type_perf.PNG)
![Pic 7](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_school_type_perf.PNG)


## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
