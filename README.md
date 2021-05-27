Monica Cornejo

May 26, 2021

Foundations of Databases & SQL Programming

Assignment07

https://github.com/MonicaCornejo/DBFoundations-Module07 


# Module 7: Questions
## Introduction
In this document, I will answer the questions from Assignment07 regarding SQL User defined functions, scalar functions, inline functions and multi-statement functions.
## Content
### Explain when you would use a SQL UDF
Use a User Defined Function when you need to create your own custom function, adequate to a specific need. There are functions that return a table of values and functions that return a single value (scalar functions).
### Explain are the differences between Scalar, Inline, and Multi-Statement Functions
#### Scalar Function
This function returns a single value as a result. It can return int, char, varchar data types, but the Text, ntext, image and timestamp data types are not supported.

Result example: 6
#### Inline (Table-Valued) Function
The Inline Function returns a table variable as a result of the function, derived from a single SELECT statement. There is no BEGIN/END block needed in the CREATE FUNCTION statement.
#### Multi-Statement (Table-Valued) Functions
A Multi-Statement Function returns a table variable as a result of actions performed by the function, but it can have more than one SQL statement.
## Reference
(https://excelkingdom.blogspot.com/2018/01/how-to-create-scalar-inline-and-multi.html), 2021 (External Link). 
## Summary
In this Module, I answered all the questions related to the User Defined Functions (UDF), which allows you to perform customized tasks within it, scalar, and table-valued functions. Within the table valued functions, there is the inline and the multi-statement functions. 
