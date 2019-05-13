
# Project
Read the questions carefully and code your answers.

1.- Create a numeric vector that contains the months of a year. Then, a vector that contains the name for each month. Later, display the months related to the summer season (June, July, August)

2.- Construct a matrix with 5 rows containing the numbers 1 up to 15, filled row-wise.

3.-Create a factor with these observations "XXL", "XXL", "XXL", "XL", "L", "M", "M", "S", "S", "S"  and print a summary

4.- Create a data frame that should contain:
- 5 of your courses (e.g. Fundamentals of Programming, Object-Oriented Programming, Databases, etc ).
- 5 of your marks
- 5 of your professors' names    

5.- Load the dataset labeled as **ITU_WB.csv** that is located in the **data folder** and storage this dataset in a variable called "itu".   Then, you should describe the composition of the dataset. This description must contain the number of  observations, variables and the type of each variable

6.- Filter the itu dataset to retrieve only the observation from Mexico, grouped by year and  in descending order selecting the  "Internet value" column

7.- Create a new variable called "itu_by_year" grouping per "year"  and "Income group" variables. Then, remove  NAs observations. Later, using the function summarize() you should  estimate the median  of the `Internet value` variable and store it in a variable called "medianValue"

Visualizing median "Internet value" per "year" and "Income Group" and removing "NA" values

8.-Create a line plot to visualize trends over time. You should use the variables created in the "itu_by_year" dataset

9.- Create a new variable called "itu_latin" filtering per Region,  selecting Latin America & Caribbean and grouping per Income group. 

Then, using this dataset, create a plot visualizing the relationship between Internet value and GDP (US$)  colored per Income group and faceting per Economy

10.- Create a new variable called "itu_2017" filtering the year 2017 and removing observations that contain NAs. 

Then, using this dataset, create a plot visualizing the relationship between Internet value and GDP (US$)  colored per Income group. Furthermore,  you should use a log scale in both axes ("x" and "y"). Finally, you should use the facet function in order to wrap by Region.


