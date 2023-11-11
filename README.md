# API-design
Different types of API documentation are provided in this repository

### 1. JSON-RPC design.json 
The file contains designed JSON-RPC API documentation according to the task:

You are working on developing API for a data storage that stores sensitive user data. The system must provide the ability to add, retrieve and delete data, considering different access levels.

**Requirements to the method:**
 + Method name: manageSecretData
 + The method should take the folowing parameters:
    * action: action type (add, get, delete)
    * dataID: data identifier
    * userData: data to be added (optional)
    * accessLevel: access level (user, admin, superAdmin)
+ Depending on action and accessLevel, the method should return relevant errors or results. For example, only superAdmin can delete data.

### 2. GraphQL.txt
The file contains designed GraphQL schema according to the task:

Develop a GraphQL sсhema to manage the DB of students and courses.

**Requirements:**
+ Entities:
   * Student: Name, Surname, Age, A list of courses.
   * Course: Name, Description, Cost.
+ Operations:
   * Add, Delete, Edit a student
   * Add, Delete, Edit a course
   * Enrol on a course
   * DropOut of a course
+ Requests:
   * Get a list of all students
   * Get a list of all courses
   * Get information about student
   * Get information about course
+ Additionally:
   * Implement filtering of courses by cost
   * Implement pagination of a student list
   * Add a field to course showing count of registered students   

### 3. gRPC.proto
The file contains designed gRPC schema according to the task:

Develop a gRPC sсhema to manage information of products in a online-store.

**Requirements:**
+ Entities:
   * Product
   * Category
+ Operations and requests:
   * Add a new product
   * Edit an existing product
   * Delete a product
   * Add a new category
   * Edit an exicting category
   * Delete a category
   * Attach a product to a category
   * Detach a product from a category
   * Get all products
   * Get all categories
   * Get a product by Id
   * Get a category by Id
+ Additionally:
   * Implement filtering of products by cost
   * Implement pagination of a product list


### 4. REST.yml
The file contains designed REST schema according to the task:

Develop RESTful API to manage the DB of books and authors in a library.

**Requirements:**
+ Entities:
   * Book: Id, name, genre, year, authorId.
   * Author: Id, name, lastName, BirthDate.
+ Operations and requests:
   * Add a new book
   * Edit an existing book
   * Delete a book
   * Add a new author
   * Edit an exicting author
   * Delete an author
   * Get all books
   * Get all authors
   * Get a book by Id
   * Get an author by Id
+ Additionally:
   * Implement filtering of book by genre
   * Implement pagination of a book list

