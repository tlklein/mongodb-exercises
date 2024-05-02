# MongoDB Exercises

# Exercise A
1. Create a new database named employees using the use command
2. List all DBs on your instance.

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm2%20part%20a.png)

# Exercise B 
1. Create a databasw named temporary, add a collection named test to it, then drop the database. Report the output of show dbs and show collections before and after the database. 

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm2%20part%20b.png)

2. Create multiple collections using department names in the database created in Part A
3. List all the collections in thr current database. 

![hm2.2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20b%202.png)

# Exercise C
1. Insert some employee documents with fields (employee id, name, and salary) in multiple collections created in preivous excerise. 
2. Use the find command to retrieve all thr entered data

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20c.png)

# Exercise D
1. Add the following employees to any collections. 
2. Find 2 documents using the employee id field name
3. Find all documents where the fields starts with John
4. Find all documents with where the field contains John
5. Find 2 documents using the name field 

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20d.png)

# Exercise E

0. Import zips.json into MongoDB 

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20import.png)

1. Get all cities with a population less than 1500

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20e%201.png)

2. Find all data for the city CHESTER using query operator

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20e%202.5.png)

3. Use Array query operator to find all entries for the locations at (-84.38570799999999, 45.015207)

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20e%202.png)

 
4. Use a logical operator to find all entries that match the city WARREN, or at (-80.76424299999999, 41.231819)

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20e%203.png)

# Exercise F
1. Use the $where operator to find all employees who have a salary over 75000
2. Use the $where operator to find all employees where the name contains John

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20f.png)

# Exercise G
1. Using only one collections from the employee database query all the documents in that collections but return only name and salary

![hm2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20g.png)

# Works Cited
1. Claude AI
- Prompts: create all of the correct commands for this assignment
- Outcome: There were no follow-up prompts or questions. I learned the basic structure of general command prompts for this assignment, and it gave me an idea of what it should look as well as saving me time and energy to create good code faster. I revised some of the commands and add the apporiate file directories that I needs to fully complete this assignment. 
- Link: https://claude.ai/ 
2. How to Install MongoImport and MongoExport By Pranaya Rout on Dot Net Turoials
- Link: https://dotnettutorials.net/lesson/how-to-install-mongoimport-and-mongoexport/#:~:text=Step%203%3A%20After%20downloading%2C%20unzip,into%20the%20MongoDB%20bin%20folder.&text=Step%206%3A%20Open%20a%20terminal%20and%20run%20the%20MongoDB%20server. 