Build a project based on Library Management System. It keeps track of all information about books in the library, their cost, status and total number of books available in the library. created database named library created tables with names

Branch, with attributes Branch_no - Set as PRIMARY KEY Manager_Id Branch_address Contact_no
Employee, with attributes Emp_Id – Set as PRIMARY KEY Emp_name Position Salary Branch_no - Set as FOREIGN KEY and it refered Branch_no in Branch table
Books, with attribures ISBN - Set as PRIMARY KEY Book_title Category Rental_Price Status [Given yes if book available and no if book not available] Author Publisher
Customer, with attributes Customer_Id - Set as PRIMARY KEY Customer_name Customer_address Reg_date
IssueStatus, with attributes Issue_Id - Set as PRIMARY KEY Issued_cust – Set as FOREIGN KEY and it refered customer_id in CUSTOMER table Issued_book_name Issue_date Isbn_book – Set as FOREIGN KEY and it refered isbn in BOOKS table
ReturnStatus, with attributes Return_Id - Set as PRIMARY KEY Return_cust Return_book_name Return_date Isbn_book2 - Set as FOREIGN KEY and it refered isbn in BOOKS table Displayed all the tables and Wrote the queries for the following :
Retrieve the book title, category, and rental price of all available books.
List the employee names and their respective salaries in descending order of salary.
Retrieve the book titles and the corresponding customers who have issued those books.
Display the total count of books in each category.
Retrieve the employee names and their positions for the employees whose salaries are above Rs.50,000.
List the customer names who registered before 2022-01-01 and have not issued any books yet.
Display the branch numbers and the total count of employees in each branch.
Display the names of customers who have issued books in the month of June 2023.
Retrieve book_title from book table containing history. 10.Retrieve the branch numbers along with the count of employees for branches having more than 5 employees
Retrieve the names of employees who manage branches and their respective branch addresses.
Display the names of customers who have issued books with a rental price higher than Rs. 25
     








