Bookmark Manager
-----------------
To start psql, type psql <database name> into a Terminal, where <database name> is the name of the database you want to interact with. So, typing psql postgres will give us direct access to that first database:

Creating your Database
postgres=# CREATE DATABASE "your_user_name_here";

Listing all database tables
postgres=# \l

Quitting SQL
postgres=# \q


Instructions to access Bookmark_Manager DB
--------------------------------------------
1. Connect to psql
2. Create the database using the psql command CREATE DATABASE bookmark_manager;
3. Connect to the database using the pqsl command \c bookmark_manager;
4. Run the query we have saved in the file 01_create_bookmarks_table.sql
