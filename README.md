PLP Bookstore MongoDB Assignment
Overview
This project demonstrates the setup and usage of MongoDB to create a database and collection, perform CRUD operations, advanced queries, aggregation pipelines, and indexing as part of the PLP MERN Stack course Week 1 assignment.

Setup
MongoDB Setup

Installed MongoDB locally or used MongoDB Atlas.

Created a database called plp_bookstore.

Created a collection called books.

Insert Data

Inserted 10 example book documents with fields: title, author, genre, published_year, price, in_stock, pages, publisher.

Used MongoDB shell or provided insert_books.js script to populate data.

Queries Implemented
Basic CRUD
Find all books in a specific genre.

Find books published after a given year.

Find books by a specific author.

Update the price of a book by title.

Delete a book by title.

Advanced Queries
Find books in stock and published after 2010.

Project title, author, and price fields only.

Sort books by price ascending and descending.

Pagination with limit and skip for 5 books per page.

Aggregation Pipelines
Average price per genre.

Author with the most books.

Group books by publication decade with counts.

Indexing
Created an index on the title field.

Created a compound index on author and published_year.

Used explain() to verify improved query performance with indexes.

How to Use
Use mongosh or MongoDB Compass to connect to your database.

Run the queries.js file or execute queries manually in the shell.

To view query performance, use the .explain("executionStats") method on find queries.

Tech Stack
MongoDB Community Edition or MongoDB Atlas

MongoDB Shell (mongosh) or Compass GUI

Author
[Christopher Mwamburi]
