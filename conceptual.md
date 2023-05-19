### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
- PostgreSQL is the Open Source RDBMS

- What is the difference between SQL and PostgreSQL?
  SQL is an RDBMS and Postgre is an ORDBMS

- In `psql`, how do you connect to a database?
- \c "selected database"

- What is the difference between `HAVING` and `WHERE`?
- WHERE lets you filter through a specific row
- HAVING filters through a group of rows by aggregating columns

- What is the difference between an `INNER` and `OUTER` join?
  INNER keeps info related to both tables 
  OUTER will keep related and unrelated info from both tables

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
- Left keeps all info from left side and matched data drom the right side
- RIGHT keeps all info from right side and unmatched info from the left side

- What is an ORM? What do they do?
- Object relational mapping connects OOP code with a database

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  AJAX changes a portion of a website without reloading
  HTTP request refreshes page to show changes


- What is CSRF? What is the purpose of the CSRF token?
  A CSRF Token is a value that the server side app creates in order to protect CSRF vulnerable resources. 

- What is the purpose of `form.hidden_tag()`?
- This is used to protect the form against a CSRF attack
