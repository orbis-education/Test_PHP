# **Orbis Education Homework Assignment**

The goal of this assignment is to test your knowledge of PHP by completing the tasks below. It shouldn't take more than an hour. Send us back your code when you're done. Good luck!

## **Guidelines**

This program should set default information about a person. It should display their name, age and hair color by using a custom class. Then, you should change the person's name programmatically and display the updated information. Finally, it should save the data to a mock database.

## **Tasks**

### **Part 1**

You'll be working with storing data about a person. To begin, create a Person object with the following properties:

1. Name
2. Age
3. Hair color

In your Person class file, you should have functions to get and set the person's details. Set each to a default value.

In your main code file, you should call each of the functions and print out the results. It should display the person's name, age and hair color. Then, you should call the update functions to update the name and hair color and display the updated information below. The program should display information for two people.

### **Part 2**

Now we're going to extend this class. We're going to simulate a database connection to store this information into a database. NOTE: You will NOT need to establish a database connection, we're just looking to see your knowledge of SQL. _Simply creating a "sql-statements.sql" file containing your SQL statements will be fine._

You should create the necessary SQL commands to save a person to a MySQL database. These statements should include:

- Checking if a database and table exist. If not, create them.
- Insert a person into the database.

## **Bonus Tasks**

- Please provide documentation on how you built your program and explain your reasoning.
- Create a database class that initializes a MySQL connection and stores each person's details.
- Feel free to add any other functionality or extend this project.
