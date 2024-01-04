# <p align="center" style="margin-top: 0px;"> SQL_function-procedures
This project goes to demonstrate how functions and procedures are created in SQL.

# <p align="center" style="margin-top: 0px;"> Overview
The data used for this project was that of a salary data, which is fictional.  it has only one table with 6 columns.

# <p align="center" style="margin-top: 0px;"> Stored Procedures
Stored procedures is a hardcoded action that is stored to gain actionable and quick insight. It also can be called multiple times within the query. The procedure created was meant to debit and credit based off on job title.
The procedure is called by the CALL function alongside the procedure name, it has three parameters which it holds; the transaction amount, the sender and the receiver.

![](procedure.png)
---

# <p align="center" style="margin-top: 0px;"> Functions
Functions are hardcoded to carry out calculation, manipulations of data and ultimately return data.
## Function 1
The function was created to return the total amount earned by a specific gender in a field/job title. The function is called using the SELECT statement alongsides the function name,it received two parameters; the jobtitle and the sex.

![](function_1_query.png)
--
![](function_1_output.png)
---

## Function 2
The function returns the count of people within the years of experience range.The function is called using the SELECT statement alongsides the function name,it received two parameters; the minimum and maximum years of experience. It filters through the data to return the number of persons within the specified years of experience

![](function_2_query.png)
--
![](function_2_output.png)
---

![](sql_thanks.jpg)
--
