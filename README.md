# **PyCitySchools Challenge**

I am the Chief Data Scientist for my city's school district. In this capacity, I'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, I've been asked to analyze the district-wide standardized test results. I'll be given access to every student's math and reading scores, as well as various information on the schools they attend. My responsibility is to aggregate the data to showcase obvious trends in school performance.

My final report will include each of the following:

#### **District Summary**

##### **A high level snapshot (in table form) of the district's key metrics, including:**

- Total Schools
- Total Students
- Total Budget    
- Average Math Score    
- Average Reading Score    
- % Passing Math (The percentage of students that passed math.)    
- % Passing Reading (The percentage of students that passed reading.)    
- % Overall Passing (The percentage of students that passed math and reading.) 

#### **School Summary**

##### **An overview table that summarizes key metrics about each school, including:**

- School Name
- School Type
- Total Students
- Total School Budget
- Per Student Budget
- Average Math Score
- Average Reading Score
- % Passing Math
- % Passing Reading
- % Overall Passing (The percentage of students that passed math and reading.)

#### Top Performing Schools (By % Overall Passing)
Sort and display the top five performing schools by % overall passing, it will include :

- School Name
- School Type
- Total Students
- Total School Budget
- Per Student Budget
- Average Math Score
- Average Reading Score
- % Passing Math
- % Passing Reading
- % Overall Passing (The percentage of students that passed math and reading.)

#### Bottom Performing Schools (By % Overall Passing)
Sort and display the five worst-performing schools by % overall passing including all of the above metrics

#### Math Scores by Grade
- Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.
    * Create a pandas series for each grade. 
    * Group each series by school
    * Combine the series into a dataframe
    
Display the data cleaner by formatting

#### Reading Scores by Grade
- Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.
    * Create a pandas series for each grade. 
    * Group each series by school
    * Combine the series into a dataframe
    
Display the data cleaner by formatting

#### Scores by School Spending
* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Using 4 reasonable bins to group school spending. The table will include:
    - Average Math Score
    - Average Reading Score
    - % Passing Math
    - % Passing Reading
    - Overall Passing Rate (Average of the above two)
    
#### Scores by School Size
* Create a table that breaks down school performances based on average school size. Using 3 reasonable bins to group school spending. The table will include:
    - Average Math Score
    - Average Reading Score
    - % Passing Math
    - % Passing Reading
    - Overall Passing Rate (Average of the above two)
    
#### Scores by School Type
* Create a table that breaks down school performances based on School Type. Using the 2 bins to group school type. The table will include:
    - Average Math Score
    - Average Reading Score
    - % Passing Math
    - % Passing Reading
    - Overall Passing Rate (Average of the above two)
