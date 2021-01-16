# Python Pandas-challenge: PyCitySchools
**Two Observable Trends Based on the Data**
1.) Students who attend charter schools perform better on Math and Reading tests then students who attend district schools (see summary table Part 9). For district schools, their students math performance drew down the overall passing rate in which 1 out of 3 did not pass the math tests (see summary table Part 4). 
2.) While district schools spend more money on their students (compared summary tables from Part 3 and 4), these schools are larger than charter schools. In this sample of schools, there were 7 district schools and 8 charter schools.

The goal of this challenge was to analyze a combined dataframe that had school-type data and students-who-attended-the-school data. Python, Pandas, and Jupyter Notebook made it easy to extract data that had multiple units of analysis (e.g., students vs. school). 

**NOTE:**
The Jupyter Notebook may seem like there are two tables for each part. Actually, the first table is the example table that I needed to match my output. The sample table also helped me think about what I needed for the table, how I wanted to contructed, and what information the table is trying to convey.

  ## PART 1: DISTRICT SUMMARY
    Create a high level snapshot (in table form) of the district’s key metrics, including:
    Total Schools
    Total Students
    Total Budget
    Average Math Score
    Average Reading Score
    % Passing Math (The percentage of students that passed math.)
    % Passing Reading (The percentage of students that passed reading.)
    % Overall Passing (The percentage of students that passed math and reading.)

  ## PART 2: SCHOOL SUMMARY
    Create a high level snapshot (in table form) of the district’s key metrics, including:
    Total Schools
    Total Students
    Total Budget
    Average Math Score
    Average Reading Score
    % Passing Math (The percentage of students that passed math.)
    % Passing Reading (The percentage of students that passed reading.)
    % Overall Passing (The percentage of students that passed math and reading.)

  ## PART 3: TOP PERFORMING SCHOOLS (BY % OVERALL PASSING)
    Create a table that highlights the top 5 performing schools based on % Overall Passing. Include:
    School Name
    School Type
    Total Students
    Total School Budget
    Per Student Budget
    Average Math Score
    Average Reading Score
    % Passing Math (The percentage of students that passed math.)
    % Passing Reading (The percentage of students that passed reading.)
    % Overall Passing (The percentage of students that passed math and reading.)  
  
  ## PART 4: BOTTOM PERFORMING SCHOOLS (BY % OVERALL PASSING)
    Create a table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.

  ## PART 5: MATH SCORES BY GRADE
    Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.
    
  ## PART 6: READING SCORES BY GRADE
    Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

  ## PART 7: SCORES BY SCHOOL SPENDING
    Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
    Average Math Score
    Average Reading Score
    % Passing Math (The percentage of students that passed math.)
    % Passing Reading (The percentage of students that passed reading.)
    % Overall Passing (The percentage of students that passed math and reading.)
    
  ## PART 8: SCORES BY SCHOOL SIZE
    Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).
    
  ## PART 9: SCORES BY SCHOOL TYPE
    Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).
    
# Tips/Reflections
I chose the education data of "PyCitySchools" over the gaming data "Heroes of Pymoli" because I'm clueless about gaming. But also, I have a formal training as an educator. So it was nice to work with data that I have domain knowledge.

I first needed to retrieve the two datasets and merge them into one dataframe. This was another reason I chose this project because we had to merge two completely different datasets. The Gaming Dataset did not need to merge (only had one csv file). After doing some quick checks for missing data (NaN), datatypes, and column names, I got a sense of the data that I was working with and started to completed all nine parts of the challenge.

It took awhile to get a handle on dataframe, groupby, and functions. I was curious to see if I could use some lambda functions, but I was not able to create some that made sense. Once I saw that the analysis was moving from large to drilling down, it was important to set up a working dataframe. I did not want to mess with the original combined dataframe during the analysis out of fear that I would alter it permanently. So I made a few copies and renamed dataframes. Eventually, I got more comfortable that I was not messing anything up and could go back to the combined dataframe ("summary_school_df").

While there was a day when I was pounding my head against the wall, I decided to step away for a day and come back at it. With a fresh eyes and mind, I was better in my approach and thinking. I may need to apply this break strategy more with coding and data analysis.
