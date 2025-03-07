java cCE4208 Distributed Systems Assignment #1: Data Centred Distributed Systems Assignment
Page 1 of 3
CE4208 Distributed Systems
Data Centred Distributed Systems Assignment
1.Overview
This is an individual assignment, where each student must submit their own solution – any 
duplicate solutions will receive 0 marks. Your task is to develop a desktop application that 
uses JDBC to connect a database.
If you have any queries, please post them on the “Assignment #1 Data Centred Distributed 
Systems” forum on the module’s Brightspace page.
2. Description
Your task is to develop your own relational database – this database can store anything you 
like. Then, you are asked to provide a desktop application that interacts with your DB via JDBC.
2.1 Database Requirements
Your database must be implemented in the Derby Database (Apache Java DB) and have the 
following properties:
• Use at least one One-to-One relationship.
• Use at least one One-to-Many relationship.
• Use at least one Many-to-Many relationship (you must use a junction table – the same 
relationship as for the One-to-Many cannot be used).
• Use at least one column of the following types: INTEGER, VARCHAR, 
DATE/TIME/TIESTAMP (one of these), fixed point number with exactly 2 digits for the 
fractional component (2 digits to the right of the decimal point – specify your own 
limit for the overall precision).
2.2 Desktop Application Requirements
Develop a desktop application (not a Web application) that interacts with your database. Use 
either dialog methods from the JOptionPane or develop a proper Swing GUI (only advisable if 
you have experience with Java Swing).
All database interactions must be implemented by using JDBC. Your application must provide 
the following features:
• At start up a method that establishes whether the tables of your database are 
available must execute.
• If they are not available, it should create your tables in Derby:
o Feel free to add your tables to the sample database or create your own logical 
database within Derby.
o If you use the sample database, please precede all table names with your 
student ID to ensure unique table names.
o If you create your own logical database within Derby, please include your 
student ID in the database name to ensure unique database names.
CE4208 Distributed Systems Assignment #1: Data Centred Distributed Systems Assignment
Page 2 of 3
• Either way, your application must ensure that sufficient data is available in your tables 
to allow meaningful execution of your application (as a rough guideline, I would expect 
most tables to hold at least 8-10 rows).
• Several methods (one method per bullet point) implementing the following (values 
should be passed as parameters to the methods):
o A method using a query that uses an explicit join over two tables (feel free to 
use either a natural join, a join condition, or any of the outer joins).
o A method using a query that involves tables with a Many-to-Many relationship
(all tables must contribute to the query result).
o A method adding an entry to the junction table of a Many-to-Many 
relationship.
o A method that implements a transaction over (at least) two SQL statements.
o A query/statement as a PreparedStatement that has at least one query
parameter and that executes multiple times within代 写CE4208、Java/SQL
代做程序编程语言 a loop. This method should 
receive values for the parameter(s) in form of an array or Collection (e.g. 
ArrayList, LinkedList, etc.).
3. Deadline and Deliverables
Deadline for submission of your solution is 11:00h on Monday, 10
th March 2025. Please note: 
Where I have concerns about the originality of the submitted work, I reserve the right to 
conduct interviews with students, where marks will be adjusted according to the outcome of 
the interview.
Please submit your solution as a single zip, 7-zip or rar archive (please do not use any other 
format and do not remove the extension from the archive) via the module’s SULIS page. A 
complete solution includes the following items:
• Complete NetBeans 24 project that contains sources (well documented and 
formatted) of your entire solution (submit the entire project folder, not only the 
individual source code files!). Comments must include at least the following:
o Description for each class (use Javadoc for this).
o Description for each public member, including details for parameters and 
return value (use Javadoc for this).
o For any non-trivial methods provide “in code” description in form of basic Java 
comments.
• Report (MS Word, RTF, PDF or plain text – include this in the top folder of your project) 
that contains the following:
o Description of your database design (all your tables, their column properties -
such as type and constraints - and their relationship to other tables).
o How (and where) you implemented the requested One-to-One, One-to-Many 
and Many-to-Many relationships.
o List of used queries/statements to fulfil the desktop application requirements. 
Include class and method name where these are executed, which requirement 
they implement.
Note: If your report omits any requested information, I assume that the 
corresponding feature has not been implemented, and you will receive 0 marks 
for that feature. I will not search for those features in your application! For 
CE4208 Distributed Systems Assignment #1: Data Centred Distributed Systems Assignment
Page 3 of 3
example, if you do not indicate which tables implement a Many-to-Many 
relationship you will receive 0 marks for that feature even if your database 
implements this feature. Similarly, if you do not detail where you implemented the 
transaction over at least two SQL queries/statements, I assume you did not 
implement this and you will receive 0 marks for the transaction feature. 
4. Marking
The project is worth 15% of the module. Marks are distributed as shown in the table below:
Database Design:
• One-to-One Relationship
• One-to-Many Relationship
• Many-to-Many Relationship
• Requested types used 
5
(1)
(1)
(2)
(1)
Desktop Application:
• Test for tables  create tables/content.
• Query with explicit Join.
• Query with Many-to-Many Relationship.
• Adding to Junction Table of Many-to-Many 
Relationship.
• Transaction over multiple SQL statements.
• Repeated execution of PreparedStatement with 
parameters.
10
(2)
(2)
(2)
(1)
(1)
(1)
Penalties:
• Insufficient commenting
• Poor code format
• No report submitted (I will not search for features!)
• No NetBeans project submitted
Up to -30%
Up to -30%
-100%
-75%
Total 15

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
