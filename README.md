# Exploratory-Data-Analysis


# Part 0: Reading the data


# Part 1: Data cleaning

●	Write a function called data_cleaning() which, when called, would perform the following activity:

1.	Create a column at the end, named “inc/dec percentage”, which would give the growth/reduction percentage in numbers of level 1 vs level 4 columns.
Like, (“Level 1” – “Level 4”) / “Level 1” * 100

2.	Replaces the null values (if they exist) with the average of the respective column in the data.

3.	In column ‘B’ replace Jan with january, feb with february, march with march, apr with April and so on. Use the lambda function to do the same.

4.	In column ‘E’ Replace “Came_From_LinkedIn” with “From LinkedIn” and “Landed_Directly” with “Direct_traffic” .


# Part 2: Descriptive statistics

●	Write a function called descriptive_stats(‘Year’, ‘Month’ , ‘Laptop/Desktop’ , ‘Type_of_Customers?’ , ‘Coming from’) which, when called, would perform the following activity:

1.	Gives the minimum values present in all the level-columns. (Level 1, 2, 3, 4)

2.	Gives the maximum value of “Level 2” / “Level 1” among those who came directly to the via desktop website.

3.	Would filter the dataframe with the given parameters; if any parameter is missed, then consider a default value to that parameter (e.g., default: ‘year’ – 2020, ‘month’-Jan, & so on) . Let’s call this new dataframe ‘df’.

4.	Generates the summary statistics (Mean, Median, Quartile, standard deviation) of all the numerical columns of the new dataframe, df.

5.	Produce a list of all the unique values & data types present in the non-numeric columns in df.


# Part 3: Prescriptive statistics

●	The marketing manager has asked you the following questions, please provide the answers along with summarized data supporting your answer.

1.	What are the top 3 “Place_in_India”  on the basis of column “Level 4” for the year 2020 and 2022 separately ?

2.  Provide the data for all the cities & for all the years

3.	What are the bottom 3 “Place_in_India”  on the basis of column “Level 4”/ “Level 1” for the year 2021 and 2022 separately ?

4.	Which place in India is having “Level 4” value greater than 150000 most of the times?

5.	Which place in India is having least number of existing customers?


# Part 4: Simple Machine learning questions

●	Write a function called predict_future(‘Year’, ‘Month’ , ‘Laptop/Desktop’ , ‘Type_of_Customers?’ , ‘Coming from’ , ‘Place_in_India’) which, when called, would perform the following activity:

1.	Predict “Level 4” future values for the next 1 year, given the parameters of the function. (Please make sure the parameters have default values in place) Also, plot it.

2.	Generates the MAPE and RMSE of your prediction of the year 2022, 2021 & 2020 for the given parameters.

3.	Plot a line graph of the level 4 actual numbers from 2020-2022 & in the same graph, there should be the predicted numbers for 2023. The x-axis should be the timeline from 2020 Jan to 2023 Dec and the y-axis should be the value of the level 4 column

4.	Considering “Level 4”, which places in India would do better in 2023 w.r.t 2022 ? (e.g., if Pune has 5000 in level 4 in 2022 and 7500 in 2023. Now, on the other hand, say, Bengaluru has 8000 in 2022 and 4000 in 2023 in level 4, then the output would give only Pune, not Bengaluru.)


# Part 5: Visualization

●	Write a code to display the following 6 graphs:

1.	A line graph for “Level 2” for the different “Place_in_India?” over the months of the year 2020 & 2021.
 
2.	A line graph for “Level 1” for the different “Laptop/Desktop” over the months of the year 2020 & 2021.

3.	A line graph for “Level 2” for the different “Coming from” over the months of the year 2021 & 2022.

4.	A line graph for “Level 1”, “Level 4”  and “inc/dec percentage” columns over the months of the year 2020, 2021 & 2022.

5.	A line graph for “Level 3” and “Place_in_India” over the months of the year 2020 and 2021.

6.	A well visualized bar graph showing the “Level 1” from various places in India , also, representing the type of customers, for the year 2022.

7.	Please add any insights you could derive from all the graphs above. 


