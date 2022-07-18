# School District Analysis

## Overview of the School District Analysis

This project is about the School District Analysis that analyze and run using Pandas. With the use of Pandas module, we were able to determine the top 5 and bottom 5 performing schools based on the overall passing rate. We were also able to analyze the Math and Reading Scores, and % Passing of each school.


## School District Results

**How is the district summary affected?** 
The district summary is an aggregated collection of the combined high schools within that district. Summarizing the data in a dataframe allows us to view the district's overall performance in a single row.

*Image 1A: District Summary*
![District Data](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/District_Summary.png)

**How is the school summary affected?**
The school summary adds more granularity to the district summary, by splitting the data out further by High School Name. For each high school name, each entry includes new information such as School Type, Total Students, Total School Budget, and Per Student Budget.

*Image 1B: Original School Summary Data*
![Original School Summary](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/Original_Per_School_Summary.png)

**How does replacing the ninth graders' math and reading score affect Thomas High School's performance relative to the other school?**

*Image 2A: Thomas High School Math and Reading Scores **including** 9th Graders*
![Including 9th Graders](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/incl%209th_grader_THS_Summary.png)

*Image 2B: Thomas High School Math and Reading Scores **excluding** 9th Graders*
![excluding 9th Graders](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/excl%209th_grader_THS_Summary.png)

As you can see in the images above, the Math and reading scores of Thomas High School was positively affected when we removed the 9th Graders' scores. The Percentage Passing for Math was increased from 66.91% to 93.19%. While the Percentage Passing for Reading was increased from 69.66% to 97.02%.

*Image 2C: Overall Passing Summary*
![Overall_Passing](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/Overall_Passing.png)
Thomas High School's overall passing rate was only 65.08% with the 9th graders' scores. It increased to 90.41% replacing the 9th-grade scores.


**How does replacing the ninth-grade scores affect the following:**

 - Math and reading scores by grade
	
	Both the math and reading Scores were positively affected by replacing the 9th-Grade scores. The scores for both classes increased significantly.

  *Image 3A: Math Scores By Grade*

![Math Scores](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/Math%20Scores%20By%20Grade.png)

  *Image 3B: Reading Scores By Grade*	

![Reading Scores](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/Reading%20Score%20By%20Grade.png)

	
 - Scores by school spending
 
  The schools with the lowest spending range per students had the highest percentage overall passing grade/rate. The spending range that is less than $586.00 had the highest overall passing rate of 90%.
	 
  *Image 4: Scores By Spending range*![Scores By Spending range](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/Spending_Range.png)


 - Scores by school size
 
  The schools with a medium-sized student body has the best % Overall Passing rate
	 
  *Image 5: Scores By School Size* ![Scores By School Size](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/Scores_School_Size.png)


 - Scores by school type

  Charter schools produce significantly higher scores than district scores (90% vs 54%)
![Scores_By_School_Type](https://raw.githubusercontent.com/Mishabatoon/School_District_Analysis/main/Screenshots/Scores_School_type.png)


## Summary

Four major changes after replaceing Thomas High School's 9th grade numbers to NaN is that the 

 1. Average scores for Thomas High School's Reading and Math increased
 2. Thomas High School's % Overall Passing, % Passing Reading, and % Passing Math inreased
 3. The % Overall Passing, % Passing Reading, and % Passing Math increased for Medium schools (since Thomas High School is considered a Medium-sized school)
 4. The % Overall Passing, % Passing Reading, and % Passing Math increased for Charter schools (since Thomas High School is a Charter school as well)


