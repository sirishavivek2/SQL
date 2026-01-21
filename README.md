# SQL
Just Solving the SQL Queries

1) Query all the columns for all American cities in the CITY table with population larger than 100000. The CountryCode for America is USA

   SELECT * FROM CITY
   WHERE CountryCOde = 'USA' AND Population > 100000;

2) Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer.
   
   SELECT DISTINCT CITY
   FROM STATION
   WHERE ID % 2 = 0;

3) Find the difference between the total number of CITY entries in the table and the number of distinct CITY entries in the table.

   SELECT COUNT(CITY) - COUNT(DISTINCT CITY)
   FROM STATION;

4) 


