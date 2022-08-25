Whitney Secor 
Due: 24 August 2022 
Foundations of Databases and SQL Programming 
Assignment 7
Link:  https://github.com/wns213/DBFoundations-Module07

**Assignment 07: Functions** 

**Introduction**

Functions are a helpful tool in SQL. There are numerous functions a SQL user can utilize, and a user can even create their own functions (UDFs). Most SQL functions return one value (such as GetDate), but you can use them in a SELECT, and apply the function to many rows, saving the SQL user time. In this assignment, I will explore how a user can create their own functions, and the differences between a Scalar, Incline, and Multi-Statement Functions. 

**Explain when you would use a SQL UDF.**

User Defined Functions or UDFs are custom functions. UDFs allow faster execution for a SQL user. If a SQL user had a set of complex string of values that the user needed to reuse, the SQL user could create a UDF to save the set of code to the database. The user would then be able to utilize the UDF whenever they needed to bring up the specific code again. 

**Explain are the differences between Scalar, Inline, and Multi-Statement Functions.**

There are two basic functions, and these two functions allow a user to retrieve a table of values or a single value. Custom Scalar functions are sometimes used for Check constraints because you cannot otherwise reference a column in another table. You can create a UDF to return a single (scalar) value as an expression. Unlike a Scalar function, an Inline function returns a table instead of a single value. A multi-statement table-valued function (MSTVF) is similar to an Inline function in that it also returns a table. However, a MSTVF uses multiple SELECT statements – this function is useful, because a SQL user can execute multiple queries within the function and aggregate results into the returned table.

**Summary**

There are numerous Function provided in SQL, and a SQL user also can create their own Functions (UDF’s). Preset and UDF Functions are helpful for a SQL user if they want to save time or keep their code uniform. A Function can return one single value, which is the most common, but it can also return tables data through the use of Inline and Multi-Statement functions. 
