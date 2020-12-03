# Assignment 07
*JMMoore, 12.2.2020*
 
## Introduction 
This assignment will over the different types of user-defined functions within SQL and when a user would utilize those functions.

### SQL User-defined Functions
SQL user-defined functions (UDFs) are functions created within SQL by the user to solve complex queries for specific multi-use function rather than using the SQL generated functions.
UDFs will either yield a single value (Scalar functions) or a table value (Multi-statement functions). 
Users would use UDFs when they want to simplify code by using a stored, query specific function. 

### Scalar, Inline, Multi-Statement Functions
User-defined Scalar functions allow you to take one to two parameters and return a single value.
User-defined Inline functions are similar to view functions in that it produces a table, but you are only able to use "select" functions with this UDF.
Multi-statement function is similar to an inline function as it produces a table, but it is far more flexible with the functions used in executing this UDF. 

## Conclusion
There are numerous benefits to using UDF in code: simplifying the queries within your source code and allowing for quicker function utilization across multiple DBs. 
