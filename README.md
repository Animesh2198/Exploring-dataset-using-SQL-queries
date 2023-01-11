# Exploring-dataset-using-SQL-queries
In this exercise we are going to use basic SQL queries to explore the data sets which will allow us perform different operations on our data. 
We are going to use 

1) COUNT 
   We are using count function to count no of rows from a data set. 
   **select Count(*) from carsalestable** - This will give ouput as a number of rows present in the datafield. 

2) DISTINCT 
   This function is used to return different values. In data set it is very common to get duplicates so in order to return distinct values we use this function. 
   **SELECT  distinct (model) from carsalestable** - This query will give output values from the data as distinct. They might have duplicates of it but using distinct
   function we will get them as individual. 

Also, we can count distinct values by merging both of the functions. **SELECT  count (distinct (model)) from carsalestable**  

3) SUM
   In this function we are going to sum values present in the data. The values must be in integer values and it will not sum values of string. 
   **SELECT  sum(mileage) from carsalestable** 
   
4) AVERAGE - SELECT avg(mileage) as avg_mileage from carsalestable
5) STDDEV - SELECT stddev(mileage) as stddev_of_mileage from carsalestable 
6) MAX - SELECT max(mileage) as max_of_mileage from carsalestable 
7) MIN - SELECT min(mileage) as min_of_mileage from carsalestable 
8) ORDER BY - SELECT * from PRICE order by price ASC; 
9) LIKE - select * from carsalestable where MODEL like "Dis%";
10) GROUP BY - 
We are also going to see how to SLICE, Sort the data in ascending or descending order, Using Filtering patterns and grouping the data in a single field.   
