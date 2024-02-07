# University Book Fetch System

A program built to allow students to browse and purchase books for University classes

## Description

This command-line Python program allows the user to access the book fetch database as numerous different users. As the student, the user can browse books, including books the program recomends based on books rating, previous purchases, etc. The student can add books to a cart, view the cart, and purchase books in their cart. As a customer service employee, the user can deal with trouble tickets (tickets relating to anything whether that be purchase issues, cancellation of orders, etc.). As a administrator or super administrator, the user can add new universities, books, and classes to the system. These are all linked together and allow for back-end connections between universities and books and allow for seamless recomendations and browsing for the student. 

## Getting Started

### Dependencies

* This program should run on any Python compiler, it was ran on Visual Studio Code when being developed.
* This program will also require a IDE that supports SQL databases and can host a connection to a SQL database. For development, we used SQL workbench.
* All the libraries necessary to run this program are embeded in the code and do not need to be downloaded from elsewhere.

### Installing

* To download the program, pull the entire repository into your preferred Python compiler

### Executing program

* Run table_creation.sql followed by data_insertion.sql (run both in an IDE that supports SQL like SQL Workbench).
* Host both these sql files on a local server that can be accessed by your Python compiler
* Run the following command in your Python compiler terminal to allow for connection between your SQL database and Python compiler
```
pip install mysql-connector-python
```
* Add your password to the password.py file. Ex. The password.py file should look like the following if your password is: hello
```
password="hello"  #put your password here
```
* Finally, run Main.py in your Python compiler (the program will not work if you run any of the other Python files first). Please ensure the terminal that the Python code is executing on is FULL SCREEN (otherwise printed lists will look wrong)
  
## Authors

Contributors names

* Cameron Doffing
* Tyler Muchow
* Alena Wadzinske 
* Isaiah Giebel 
* Natalie Dubois


## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
