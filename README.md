# SQL Practice Challenge

## Setup
* Clone this repository
* Ensure you have the `sqlite3` gem (you can run `gem install sqlite3`)
* Open up the sqlite console by running `sqlite3 student-classes-data.db`
* Run `.schema` to ensure your tables exist
* Run `.explain ON` and `.mode tabs` to make the output more readable - want to know more about configuring this sqlite shell? Run `.help`!

## Practice 

### Basic Commands

* Return all of the students
* Return all of the classes
* Return just the teachers' names from the teachers table
* Find the student named "Penelope"
* Find the teacher with the highest room number (be sure your output has the room number and the teacher's name)

### Joins?!

There are different types of joins we can use to return related data. The most common type of join is the "inner join". We'll be exploring how to query our database and return data from multiple tables at once using an inner join.
