# Jose Melo 11/17/2025
# jojo_boohbah_Final_Review
Repository for DBA 120 Final Exam Review

### Question 1
##### The "GROUP BY" in the sql query is incorrect.
##### The "GROUP BY" can not run in this sql query because name column isn't in the boohbah_stand_link table. By using the "USING" keyword, it merges the boohbah_id from both the boohbah_stand_link table and the Boohbah table into one column, allowing the query to then group by the boohbah_id.


### Question 2
##### The output shows correctly, the issue is with the logic in the code
##### The logic within the code is incorrect because the provided sql query joins two unrelated tables based on their ID instead of using the link table to join them. The output from the code provided is coincidentally correct, but it could mess up with different ID numbers or it might output rows that shouldn't be there.


### Question 3
##### The code grabs a non - existant column (boohbah_name) from the boohbah table
##### The code grabs a column name that doesn't exist in the boohbah table. The simple fix to the this issue would be to look at the boohbah table (select * from boohbah;) and change the query to (select name, color) instead of (select boohbah_name, color)


### Question 4
##### The issue is that there are multiple ambiguously defined columns
##### This occurs when a query involves multiple tables, and a column is being referenced without specifing which table it comes from. This problem happens especially when the same column name exists in more than one table, making an ambiguous reference to SQL.


### Question 5:
##### The output shows correctly, the issue is with the logic in the code
##### The logic within the code is incorrect because the "WHERE" statement in the sub-query is not filter anything, since it returns true for all outputs.


## Question 6:
