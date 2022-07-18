# School_District_Analysis

## Overview of the school district analysis

The purpose of the project is to provide an analysis on the the budget spending of schools and testing scores with/without nineth grades. This analysis can help finding trends in school performance and can be used to make significant decisions. The results include:

* A high-level snapshot of the district's key metrics
* An overview of the key metrics for each school
* Tables presenting each of the following metrics:
	* Top 5 and bottom 5 performing schools, based on the overall passing rate
	* The average math score received by students in each grade level at each school
	* The average reading score received by students in each grade level at each school
	* School performance based on the budget per student
	* School performance based on the school size 
	* School performance based on the type of school
  
  Tools used: pandas library, jupyter notebook
  
  ## The Results
- District Summary: 64.9% (25421 students)of the total students(39,170 total students) pass both reading and math among all 15 schools. The results were the same with or without nineth graders at Thomas High School removed.

![district_summary](https://github.com/tiffanylin706/School_District_Analysis/blob/e0a3e5481dc7793bd5864b5515db6640de340bfc/Resources/district_summary.png)
 
- School Summary: Replacing ninth graders' math and reading score increased the overall passing rate from 65.1% to 90.6% once ninth grade scores data was removed
 
 **Original Results**
 ![Original](https://github.com/tiffanylin706/School_District_Analysis/blob/e0a3e5481dc7793bd5864b5515db6640de340bfc/Resources/school_summary_original.png)
 
 **Revised Results**
 ![Revised](https://github.com/tiffanylin706/School_District_Analysis/blob/e0a3e5481dc7793bd5864b5515db6640de340bfc/Resources/school_summary_revised.png)

- How does replacing the ninth-grade scores affect the following:
**Math and reading scores by grade:** For ninth grade, the results showed "Naan" whereas other grades showed value.

![math_result](https://github.com/tiffanylin706/School_District_Analysis/blob/e0a3e5481dc7793bd5864b5515db6640de340bfc/Resources/replace_math_scores.png)

![reading_result](https://github.com/tiffanylin706/School_District_Analysis/blob/e0a3e5481dc7793bd5864b5515db6640de340bfc/Resources/replace_reading_score.png)

**Scores by school spending:** locations that spent less than $584 per student had 90% overall passing grade vs. only 54% in the highest spending range of $645-$675.

![spending](https://github.com/tiffanylin706/School_District_Analysis/blob/e0a3e5481dc7793bd5864b5515db6640de340bfc/Resources/scores_by_spending.png)

**Scores by school size:** Meidium sized schools has the best results with 91% overall passing grades compared to small sized(90%) and large sized(58%).

![size](https://github.com/tiffanylin706/School_District_Analysis/blob/e0a3e5481dc7793bd5864b5515db6640de340bfc/Resources/scores_by_size.png)

**Scores by school type:** There was no sigificant changes compared to the original result. Charter schools have 90% overall passing rate while District schools only have 54%.

![type](https://github.com/tiffanylin706/School_District_Analysis/blob/e0a3e5481dc7793bd5864b5515db6640de340bfc/Resources/scores_by_type.png)

##Summary
After reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs, the overall results were better than they were and there are four changes in the updated school distrcit analysis:

* Total number of students reduced from 39,170 to 38,709.
* Passing math percentage increased from 66.9% to 93.2%
* Passing reading percentage increased from 69.7% to 97.0%
* Overall passing percentage increased from 65.1% to 90.6%
