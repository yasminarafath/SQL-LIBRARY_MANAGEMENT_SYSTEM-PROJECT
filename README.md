Build a project based on Library Management System. It keeps track of all information about books in the library, their cost, status and total number of books available in the library.
created database named library
created tables with names
  1. Branch, with attributes
     Branch_no - Set as PRIMARY KEY
     Manager_Id
     Branch_address
     Contact_no
  2. Employee, with attributes
     Emp_Id – Set as PRIMARY KEY
     Emp_name
     Position
     Salary
     Branch_no - Set as FOREIGN KEY and it refered Branch_no in Branch table
  3. Books, with attribures
     ISBN - Set as PRIMARY KEY
     Book_title
     Category
     Rental_Price
     Status [Given yes if book available and no if book not available]
     Author
     Publisher 
  4. Customer, with attributes
     Customer_Id - Set as PRIMARY KEY
     Customer_name
     Customer_address
     Reg_date 
  5. IssueStatus, with attributes
     Issue_Id - Set as PRIMARY KEY
     Issued_cust – Set as FOREIGN KEY and it refered customer_id in CUSTOMER table
     Issued_book_name
     Issue_date
     Isbn_book – Set as FOREIGN KEY and it refered isbn in BOOKS table
  6. ReturnStatus, with attributes
     Return_Id - Set as PRIMARY KEY
     Return_cust
     Return_book_name
     Return_date
     Isbn_book2 - Set as FOREIGN KEY and it refered isbn in BOOKS table
Displayed all the tables and Wrote the queries for the following :
     1. Retrieve the book title, category, and rental price of all available books.
     2. List the employee names and their respective salaries in descending order of salary.
     3. Retrieve the book titles and the corresponding customers who have issued those books.
     4. Display the total count of books in each category.
     5. Retrieve the employee names and their positions for the employees whose salaries are above Rs.50,000.
     6. List the customer names who registered before 2022-01-01 and have not issued any books yet.
     7. Display the branch numbers and the total count of employees in each branch.
     8. Display the names of customers who have issued books in the month of June 2023.
     9. Retrieve book_title from book table containing history.
     10.Retrieve the branch numbers along with the count of employees for branches having more than 5 employees
     11. Retrieve the names of employees who manage branches and their respective branch addresses.
     12. Display the names of customers who have issued books with a rental price higher than Rs. 25.
Outputs of the queries:
1.![image](https://github.com/user-attachments/assets/c2c5c8c6-773a-4df6-b524-adfdedc15801)
2.![image](https://github.com/user-attachments/assets/6f8f4946-e4bc-404b-b298-2d3715ff11c3)
3.![image](https://github.com/user-attachments/assets/6883bbbb-661d-4272-9886-feb6899428eb)
4.![image](https://github.com/user-attachments/assets/d63a87f0-af23-45ac-bfe1-1c53f862ce81)
5.![image](https://github.com/user-attachments/assets/d2c82342-808b-42e6-831a-a7520f68004d)
6.![image](https://github.com/user-attachments/assets/fc2199dd-1f96-4cad-a44f-a3873fdc1341)
7.![image](https://github.com/user-attachments/assets/7280bef0-7b37-4731-a1e0-e3dfceec605e)
8.![image](https://github.com/user-attachments/assets/a6865717-2e35-4c65-9a1c-7719392e2848)
9.![image](https://github.com/user-attachments/assets/1b32b45b-d2a8-4176-9382-e45454e68296)
10.![image](https://github.com/user-attachments/assets/0d710873-7fa8-43a7-808b-8593a065b0ae)
11.![image](https://github.com/user-attachments/assets/2f7a8a3c-1903-4bfe-95df-5bd2a2612d9e)
12.![image](https://github.com/user-attachments/assets/473cfa95-a08c-4488-9181-8aedaea11e92)











