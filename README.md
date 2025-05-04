# Live-Google-Sheets-to-SQL-Database-Python-Converter
Originally designed for use within a university club, this project eliminates the need for a dedicated paid SQL server for small-scale databases.

This project accepts the share link of any google sheet (NOT the website link in the search bar). Then, it goes through the following steps to create a queryable database: 

1. Share Attendance Google sheet with “anyone with link”
2. Grab the Google Sheet share link in Collab
3. Convert link to a csv file link
4. Read csv into a dataframe
5. Wrangle dataframe to make it SQL-ready
6. Create a dictionary for python and SQL data types
7. Create a SQL table using the dataframe and data types
8. Iterate through the dataframe to write INSERT statements for each row
9. Query database


For the sake of this project, I have wrangled a fuel use dataset as an example, but it can be replaced by any google sheet. Notably, the column names (but not data) require one-word titles.
