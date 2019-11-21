# mssql-access-review
A project to easily perform an access review of multiple servers/databases in MSSQL

# Purpose
Looking for a repeatable way to query permissions from multiple database objects in a single server, and even multiple servers across an environment and return the specific database level access.   

I'm starting with a SQL query put together by https://stackoverflow.com/users/9266/jeremy
Which can be found at https://stackoverflow.com/questions/7048839/sql-server-query-to-find-all-permissions-access-for-all-users-in-a-database

The above query will return values from a single database, but has to be installed as a view on each database and run individually.   My ultimate goal is to query multiple databases so I can see where all a specific servers permission is applied across multiple databases.  

