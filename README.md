# PyCitySchools Challenge

## Overview of School District Analysis

### The purpose of this school district analysis is to better understand the school district data and thus what factors could potentially be affecting student performance. Specifically, to identify top and low performing schools and if school spending, school size, or school type could be affecting student performance. Additionally, the analysis accounts for data integrity issues by replacing grades for 9th graders at Thomas High School (THS) with null values. 

## Results

-How is the district summary affected? The average scores as well as percentages barely changed between the original district summary and the updated summary excluding the THS 9th grade values. (https://github.com/awolfe95/School_District_Analysis/blob/main/Resources/updated_school_district_summary.png) 
 
-How is the school summary affected? The school summary has updated values for average reading and math scores as well as percent passing for THS based on the removal of THS 9th grade score removal. (https://github.com/awolfe95/School_District_Analysis/blob/main/Resources/updated_per_school_summary.png) 

-How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? THS is the second best performing school based on overall passing percentage in both the original analysis as well as the analysis with updated THS values. (https://github.com/awolfe95/School_District_Analysis/blob/main/Resources/updated_THS_relative_performance.png) 

-How does replacing the ninth-grade scores affect the following:

	-Math and reading scores by grade: The math and reading scores for 9th grade at THS are null due to data integrity issues.( https://github.com/awolfe95/School_District_Analysis/blob/main/Resources/updated_math_reading_scores_bygrade.png) 
 
	-Scores by school spending: The spending range affected is the $630-$644 range and it is only slight affected. The average math score, percent passing math, percent passing reading, and overall percent passing values are all slightly lower in the updated version. The average reading score is slightly higher in the updated version. (https://github.com/awolfe95/School_District_Analysis/blob/main/Resources/updated_school_spending.png)

	-Scores by school size: The medium school size category was slightly affected by the update. The average math score, percent passing math, percent passing reading, and overall percent passing values are all slightly lower in the updated version. The average reading score is slightly higher in the updated version. (https://github.com/awolfe95/School_District_Analysis/blob/main/Resources/updated_school_size.png) 

	-Scores by school type: The charter school type category was slightly affected by the update. The average math score, percent passing math, percent passing reading, and overall percent passing values are all slightly lower in the updated version. The average reading score is slightly higher in the updated version. (https://github.com/awolfe95/School_District_Analysis/blob/main/Resources/updated_school_type.png)



## Summary

### Overall, the updated THS 9th grade reading and math scores had minimal effect on the analysis, with all the findings relating to school size, spending, and type staying the same. Four of the main changes include: (1) THS 9th grade scores were replaced with “NaN”, (2) THS’ school summary data slightly changed due to the update, (3) average reading scores for the school district metrics slightly increased in the categories that included THS, (4) the average math scores as well as passing percentages for the school district metrics slightly decreased in the categories that included THS.
![image](https://user-images.githubusercontent.com/82780266/119227622-cc69f680-badc-11eb-81ac-5d770451012f.png)
