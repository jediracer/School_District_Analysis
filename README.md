# School_District_Analysis

## Project Overview
Evidence of academic dishonesty was found in the data that was originally provided. 
1. The compromised data needs to be replaced with NaN values.
2. Re-run the original analysis without 9th grade scores from Thomas High School.
3. Alter the analysis for Thomas High School to exclude 9th grade scores.

## Resources
- Data Sources: 
	- schools_complete.csv
	- students_complete.csv
- Software: Python 3.8.8, Visual Studio Code 1.57.1

## Results
- Affects on the District Summary
	- The Average Math score dropped one tenth of a percent to 78.9%.
	- The Average Reading Score did not change.
	- The percentage of students that had a passing math score (% Passing Math) dropped two tenths of a percent to 74.8%.
	- The percentage of students that had a passing reading score (% Passing Reading) dropped one tenth of a percent to 85.7%.
	- The overall passing percentage (% Overall Passing) dropped three tenths of a percent to 64.9%
		- Original District Summary
		![Original District Summary](https://github.com/jediracer/School_District_Analysis/blob/main/resources/Original%20District%20Summary.png)
		- Updated District Summary
		![Updated District Summary](https://github.com/jediracer/School_District_Analysis/blob/main/resources/Updated%20District%20Summary.png)
- Affects on the School Summary
	- Only the metrics for Thomas High School were affected in the School Summary
		- Original School Summary
		![Original School Summary](https://github.com/jediracer/School_District_Analysis/blob/main/resources/Original%20School%20Summary.png)
		- Updated School Summary
		![Updated School Summary](https://github.com/jediracer/School_District_Analysis/blob/main/resources/Updated%20School%20Summary.png)
- Thomas High School’s Performance Relative to the Other Schools
	- Thomas High School remained second in the top schools list based on % Overall Passing.
		- Original Top School Summary
		![Original Top School Summary](https://github.com/jediracer/School_District_Analysis/blob/main/resources/Original%20Top%20School%20Summary.png)
		- Updated Top School Summary
		![Updated Top School Summary](https://github.com/jediracer/School_District_Analysis/blob/main/resources/Updated%20Top%20School%20Summary.png)	
- Affects on replacing the ninth grade scores for Thomas High School
	- Math & Reading Scores by Grade
		1. The average of all grades for Thomas High School
		2. The average of the 9th grade for all schools in the district
	- Scores by School Spending
		- No affect
	- Scores by School Size
		- No affect
	- Scores by School Type	
		- No affect
## Summary
- The affects on the District Summary were very small.  removing the 9th grade scores from the Thomas High School did not have a substantial impact over the district as a whole.
- The metrics for Thomas High School were the one affected on the School Summary as data was not removed from other schools.
- The performance rating of Thomas High school was minimally impacted even though the 9th grade scores were removed.
- The affects on the metrics for Thomas High School were also minimal even though the 9th grade scores were removed.

		

