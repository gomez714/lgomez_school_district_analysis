# lgomez_school_district_analysis
- Analysis of school performance in district utilizing Jupyter Notebook with Pandas and Numpy python libraries.
## Challenge
### Summary of Challenge 
Maria and her supervisor have discovered that the score averages for ninth graders from one high school are incorrect. Maria has asked you to replace the math and reading scores for that high school, but without removing those ninth-grade students from the analysis.

You need to replace incorrect data in columns using logical operations with conditionals; retrieve data from DataFrames; merge, filter, slice, and sort DataFrames; and apply the groupby() function to a DataFrame. Using these methods, you will create a new analysis with the incorrect data removed.

### Conclusions after the 9th grade test scores were replaced with absent values
- How is the district summary affected?
  - The district summary remains about the same. There is a .1% decrease in average scores for math, and a 1% decrease in percentage of students passing in both math and reading, as well as the overall percentage of passing students.
  - This should be expected since there is only 461 students in the district out of 39,120 that now have absent test scores.
- How is the school summary affected?
  - Although there is a minimal change in average test scores (.06 decrease in math and .13 in reading), we see a much more drastic change in percentages of students passing math, reading, and overall. The percentage of students that obtain passing grades for math decrease from 93.3% to 66.9%. The percentage of students that obtain passing grades for reading decreases from 97.3% to 69.7%. Lastly, there is a 25.8% decrease in percentage of students that passed overall going from 90.95% to 65.07%.
  - This can also be expected since the 9th grade class at Thomas High School makes up about a 1/4th of the school population. 461 students out of 1635.
- How does removing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
  - Before the change in grades, Thomas High School was the second highest performing school in the district. With the change in 9th grade scores, Thomas High School was moved to the 8th highest performing school in the district.
- How does removing the ninth grade scores affect the following
  - Math and Reading Scores by Grade
    - Every other grade score remained the same for Thomas High School, therefore the rest of the summary remained unchanged.
  - Scores by School Spending
    - Since Thomas High School was a school that fit within the $630 to $644 bin, there was a decrease in percentage of students that passed math, reading, and overall. The percentage of students that passed math decreased by 16% going from 73% to 67%. The percentage of students that passed reading decreased by 7% going from 84% to 77%. Lastly the percentage of students that passed overall decreased from 63% to 56%.
  - Scores by School Size
    - Since Thomas High School had 1,635 students, it was categorized as a medium sized school. In the medium size group of schools there was a decrease in percentage of students that passed math, reading, and overall. The percentage of students that passed math decreased from 94% to 86%. The percentage of students that passed reading decreased by 6% going from 97% to 91%. Lastly the percentage of students that passed overall decreased from 91% to 85%. All other sizes of schools were left unaffected.
  - Scores by School Type
    - Thomas High School was a charter school in the district, therefore charter school results were affected. Average scores in math and reading remained unchange, while the percentage of students that passed math, reading, and overall percentage of students that passed decreased. The percentage of students that passed math decreased by 4% going from 94% to 90%. The percentage of students that passed reading decreased by 4% going from 97% to 93%. Lastly the percentage of students that passed overall decreased from 90% to 87%.
