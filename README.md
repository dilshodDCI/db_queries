# Assignment.
1.	Open mongo shell
2.	Create a new database called “meal”
3.	Create a collection called ‘saloon’ for database ‘meal’.
4.	Import `saloon.json` file to “saloon” collection.

```mongoimport --db <DATABASE_NAME> --collection <COLLECTION_NAME> --file <FILE_NAME>```

### Queries:
1. Print all the documents in the collection saloon.  
2. Print the fields restaurant_id, name, borough and cuisine for all the documents in the collection saloon.  
3. Print the fields restaurant_id, name, borough and cuisine, but exclude the field _id for all the documents in the collection saloon.  
4. Print the fields restaurant_id, name, borough and zip code, but exclude the field _id for all the documents in the collection saloon.  
5. Print all the restaurant which is in the borough Bronx.  
6. Print the first 5 restaurant which is in the borough Bronx.  
7. Print the next 5 restaurants after skipping first 5 which are in the borough Bronx.  
8. Find the restaurants who achieved a score more than 90.  
9. Find the restaurants that achieved a score, more than 80 but less than 100.  
10. Find the restaurants which locate in latitude value less than -95.754168. 
11. Find the restaurants that do not prepare any cuisine of 'American' and their grade score more than 70 and latitude less than -65.754168.  
12. Find the restaurants which do not prepare any cuisine of 'American' and achieved a score more than 70 and located in the longitude less than -65.754168.
Note : Do this query without using $and operator.  
13. Find the restaurants which do not prepare any cuisine of 'American ' and achieved a grade point 'A' not belongs to the borough Brooklyn. The document must be displayed according to the cuisine in descending order.  
14. Find the restaurant Id, name, borough and cuisine for those restaurants which contain 'Wil' as first three letters for its name.  
15. Find the restaurant Id, name, borough and cuisine for those restaurants which contain 'ces' as last three letters for its name.  
16. Find the restaurant Id, name, borough and cuisine for those restaurants which contain 'Reg' as three letters somewhere in its name.
