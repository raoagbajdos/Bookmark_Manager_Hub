To start psql, type psql <database name> into a Terminal, where <database name> is the name of the database you want to interact with. So, typing psql postgres will give us direct access to that first database:

Creating your Database
postgres=# CREATE DATABASE "your_user_name_here";

Listing all database tables
postgres=# \l

Quitting SQL
postgres=# \q
