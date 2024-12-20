# MongoDB Exercises

This repository contains a series of exercises designed to help users practice basic MongoDB operations such as creating databases, inserting documents, querying collections, and using advanced query operators. The exercises include screenshots and explanations to guide users through each task.

## Exercise A: Create and List Databases

1. Create a new database named `employees` using the `use` command.
2. List all databases on your MongoDB instance.

### Screenshot
![Exercise A](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm2%20part%20a.png)


## Exercise B: Create, Drop, and List Collections

1. Create a database named `temporary`, add a collection named `test` to it, and then drop the database. Report the output of `show dbs` and `show collections` before and after the database drop.

### Screenshot
![Exercise B1](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm2%20part%20b.png)

2. Create multiple collections using department names in the database created in Exercise A.
3. List all collections in the current database.

### Screenshot
![Exercise B2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20b%202.png)


## Exercise C: Inserting and Retrieving Documents

1. Insert some employee documents with fields (employee id, name, and salary) into multiple collections created in previous exercises.
2. Use the `find` command to retrieve all the entered data.

### Screenshot
![Exercise C](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20c.png)

## Exercise D: Querying Documents

1. Add the following employees to any collections.
2. Find 2 documents using the `employee id` field.
3. Find all documents where the `name` field starts with "John".
4. Find all documents where the `name` field contains "John".
5. Find 2 documents using the `name` field.

### Screenshot
![Exercise D](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20d.png)


## Exercise E: Working with `zips.json`

0. Import the `zips.json` file into MongoDB.

### Screenshot
![Exercise E0](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20import.png)

1. Get all cities with a population of less than 1500.

### Screenshot
![Exercise E1](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20e%201.png)

2. Find all data for the city "CHESTER" using a query operator.

### Screenshot
![Exercise E2](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20e%202.5.png)

3. Use the array query operator to find all entries for locations at `(-84.38570799999999, 45.015207)`.

### Screenshot
![Exercise E3](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20e%202.png)

4. Use a logical operator to find all entries that match the city "WARREN", or the location at `(-80.76424299999999, 41.231819)`.

### Screenshot
![Exercise E4](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20e%203.png)


## Exercise F: Using the `$where` Operator

1. Use the `$where` operator to find all employees with a salary over 75,000.
2. Use the `$where` operator to find all employees where the `name` contains "John".

### Screenshot
![Exercise F](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20f.png)


## Exercise G: Querying Specific Fields

1. Using only one collection from the `employees` database, query all documents in that collection but return only the `name` and `salary` fields.

### Screenshot
![Exercise G](https://github.com/tlklein/mongodb-exercises/blob/0b44631d43d3c72f1bd2c7fb781898765d47cfae/screenshots/hm%202%20part%20g.png)


## About the Author

This activity was completed as part of the **CIS 4338 Database Administration & Implementation** course at the University of Houston under the guidance of Professor Susan Miertschin.

---

Feel free to contribute, provide feedback, or discuss improvements!

