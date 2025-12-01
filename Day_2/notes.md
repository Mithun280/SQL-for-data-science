# Creating a Database
- To start working with MySQL, the first step is to create a database.

### Syntax
```mysql
CREATE DATABASE database_name;
```
### Example
```mysql
CREATE DATABASE student_db;
```
This command creates a new database named `student_db.`

### Tips
- Database names should be unique.
- Avoid using spaces or special characters.
- Use lowercase and underscores `(_) `for better readability (e.g., `employee_records`).
- 
### Viewing All Databases
- To see all available databases:

```mysql
SHOW DATABASES;
```
Switching to a Database
Before working with tables, you must select the database:
```mysql
USE student_db;
```
## Dropping a Database
- To delete an existing database (this action is irreversible):
```mysql
DROP DATABASE database_name;
```
### Example
```mysql
DROP DATABASE student_db;
```
## Be very careful! This will permanently delete all data and tables in the database.
