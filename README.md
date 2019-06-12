# pycityschools


## Academy of Py

In this capacity, you'll be helping the  school board and mayor make strategic decisions regarding future school budgets and priorities.

You've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your responsibility is to aggregate the data to and showcase obvious trends in school performance.

Your final report should include each of the following:

### District Summary

* Create a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)
![district_sum](https://user-images.githubusercontent.com/49836101/59325550-1dde9980-8ca9-11e9-92cc-edbd307ddfe7.png)

### School Summary

* Create an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)
![school_sum](https://user-images.githubusercontent.com/49836101/59325526-0acbc980-8ca9-11e9-8295-f0a18d88b081.png)
### Top Performing Schools (By Passing Rate)

* Create a table that highlights the top 5 performing schools based on Overall Passing Rate. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)
![top_performers](https://user-images.githubusercontent.com/49836101/59325540-16b78b80-8ca9-11e9-9d27-25ec4093ad68.png)

### Bottom Performing Schools (By Passing Rate)

* Create a table that highlights the bottom 5 performing schools based on Overall Passing Rate. Include all of the same metrics as above.
![bottom_performers](https://user-images.githubusercontent.com/49836101/59325553-1fa85d00-8ca9-11e9-96c9-cd9e5e1c22b1.PNG)

### Math Scores by Grade\*\*

* Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.
![mathscores](https://user-images.githubusercontent.com/49836101/59325547-1ae3a900-8ca9-11e9-9d24-5a0d2611a3bb.png)

### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.
![readingscores](https://user-images.githubusercontent.com/49836101/59325522-07d0d900-8ca9-11e9-8189-400d2363be23.png)


### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math
  * % Passing Reading
  * Overall Passing Rate (Average of the above two)
![spending](https://user-images.githubusercontent.com/49836101/59325537-14edc800-8ca9-11e9-9b3e-bdcf67c3de68.png)

### Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).
![schoolsize](https://user-images.githubusercontent.com/49836101/59325532-0f907d80-8ca9-11e9-96c7-b4198a556182.png)

### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).

![schooltype](https://user-images.githubusercontent.com/49836101/59325534-128b6e00-8ca9-11e9-9335-f1198904ed91.png)

# PyCity Schools Analysis

###### Based on the data we can draw the following conclusions about the school district test results:

* Schools with larger budgets do not necessarily result to higher test scores. In fact, we see that students who attended schools that spent less on students on average, scored higher on both their math and reading exams. Details depicting how the budget is used at each school, would be helpful to further verify this finding. 

* There is a correlation between the size of the school and student test scores. Students who attended smaller to medium sized schools (2000 students or less) scored significantly higher overall, compared to those with a student body size between 2,000 - 5,000. Smaller schools typically indicate smaller class sizes, smaller teacher to students ratios and hence these students are likely to be receiving more direct classroom support which may result in better performance. 
       
* Additionally, the data shows us that compared to any district school, students at charter schools consistently scored better overall. This may be in part to the smaller school/class size mentioned above, however, the variation in teaching methods at charter schools should also be considered


