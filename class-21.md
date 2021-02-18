# Read 09: SQL Relations and Joins

* Complete SQLBolt 

1. They really cranked up the heat on these exercises real quick lol. I thought it was a 
   little confusing as well becasue it doesnt go over the "." anchoring method. It was still really fun but I couldnt get a single on right 
   on the international box office sales exercise.



* Database Normalization Explained in Simple English

1. a process used to organize a database into tables and columns.
2. By limiting a table to one purpose you reduce the number of duplicate data contained within your database.
3. As tables satisfy each successive database normalization form, they become less prone to 
   database modification anomalies and more focused toward a sole purpose or topic.
4. Reasons to normalize a database:
    - minimize duplicate data
    - minimize or avoid data modification issues
    - simplify queries
5. Duplicated information presents 2 problems:
    - increases storage and decreases performance
    - becomes more difficult to maintain data changes
6. 3 modificaiton anomalies that occur:
    - insert anomaly: certain attributes cannot be inserted into the database without the presence of other attributes
    - update anomaly: If we don’t update all rows, then inconsistencies appear.
    - deletion anomaly: Deletion of a row causes removal of more than one set of facts.
7. 3 common forms of database normalization:
    - 1NF: The information is stored in a relational table with each column containing atomic values. 
      There are no repeating groups of columns.
    - 2NF: The table is in first normal form and all the columns depend on the table’s primary key.
    - 3NF: The table is in second normal form and all of its columns are not transitively dependent on the primary key



* Visual Representation of SQL Join's

1. I am still very confused by these lol. Going to practice a ton though this weekend. 