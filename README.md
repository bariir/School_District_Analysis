# School_District_Analysis

## Overview of School District Analysis
The school board has notified Maria and her supervisor that the students_complete.csv dataset show evidence of academic dishonesty, especially reading and math grades for Thomas High School's ninth graders.
In order to understand the full extent of this behavior the board wants to uphold state-testing standards and asked Maria and her team to help. They specifically, have asked certain metrics that will help them in their decision-making process. 



# Results
Maria turned to the data analyst to produce certain metrics and provided him some requirement that include the following. 
- Read two files students_complete.csv file and schools_complete.csv which are in the resource folder.
	- students_complete.csv file has 39,170 rows
	- schools_complete.csv file has 15 rows
- The analyst will need to replace both math and reading grades for Thomas High School ninth graders while keeping the rest of the dataset as is.  
- The analyst have used several python libraries including Pandas and Numpy to import, clean, sort and create dataframes.
- The analyst have used several methods to prepare the reports including count, isnull, replace, sort, etc.


## Tools and Software: 
- Jupyter Notebook,  Anaconda 4.13.0, Visual Studio Code 1.68.1, Git Bash to commit changes into GitHub Repository


# Finding and Metrics

The analysis of the School District dataset shows the following:
- The student dataset contains lots of prefixes such as Miss, Mrs., Mr., Dr 
- The student dataset cotains lots of suffixes such as MD, PhD, DVM
- These are incorrect dataset that have been entered into student_complete.csv file. 
- In order to produce the correct metrics for the school district the input files will need to be cleaned and sorted.
- Following key metrics are to be delivered.

 - A high-level snapshot of the district's key metrics, presented in a table format
 - An overview of the key metrics for each school, presented in a table format
 - Tables presenting each of the following metrics:
	- Top 5 and bottom 5 performing schools, based on the overall passing rate
	- The average math score received by students in each grade level at each school
	- The average reading score received by students in each grade level at each school
	- School performance based on the budget per student
	- School performance based on the school size 
	- School performance based on the type of school



# Results

- How is the district summary affected? <br>


- How is the school summary affected? <br>


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? <br>

  - Top and bottom 5 performing schools <br>

	![Top 5 performing schools](/Resources/top_5_performing_schools.png)<br>
	
	![Bottom 5 performing schools](/Resources/bottom_5_performing_schools.png)<br>
	

  - Math and reading scores by grade <br>
  
	Thomas High School 9th graders math and reading scores has been excluded which will not be counted towards overall grades. <br>
	
	 ![Math scores by grades](/Resources/math_scores_by_grades.png)<br>
	 
	 ![Reading scores by grades](/Resources/reading_scores_by_grades.png)<br>
  
  - Scores by school spending<br>
  
	![Scores by school spending](/Resources/scores_by_school_spending.png)<br>
  
  - Scores by school size <br>
  
	![Scores by school size](/Resources/scores_by_school_size.png)<br>
  
  - Scores by school type <br>
  
	![Scores by school type](/Resources/scores_by_school_type.png)<br>



# Summary

 - Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are.
 1. 
 2. 
 3. 
 4. 



## Links to images:

Top 5 performatinc schools:![top_5_performing_schools.png](https://github.com/bariir/School_District_Analysis/tree/main/Resources/top_5_performing_schools.png?raw=true)

Bottom 5 performatinc schools:![bottom_5_performing_schools.png](https://github.com/bariir/School_District_Analysis/tree/main/Resources/bottom_5_performing_schools.png?raw=true)

Math scores by grades:![math_scores_by_grades.png](https://github.com/bariir/School_District_Analysis/tree/main/Resources/math_scores_by_grades.png?raw=true)

Reading scores by grades:![reading_scores_by_grades.png](https://github.com/bariir/School_District_Analysis/tree/main/Resources/reading_scores_by_grades.png?raw=true)

Scores by school spending:![scores_by_school_spending.png](https://github.com/bariir/School_District_Analysis/tree/main/Resources/scores_by_school_spending.png?raw=true)

Scores by school size:![scores_by_school_size.png](https://github.com/bariir/School_District_Analysis/tree/main/Resources/scores_by_school_size.png?raw=true)

Scores by school type:![scores_by_school_type.png](https://github.com/bariir/School_District_Analysis/tree/main/Resources/scores_by_school_type.png?raw=true)
