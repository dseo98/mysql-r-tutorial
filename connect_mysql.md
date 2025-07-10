# Load the DBI file
library("DBI")

# Connect to the MySQL database : con
con <- dbConnect(RMySQL::MySQL(), 
+                  dbname = "your_db", 
+                  host = "localroot", 
+                  port = ____,
+                  user = "root",
+                  password = "your_password")

# See what tables the database contains
dbListTables(con)

# Import the specific table from dbname
dbReadTables(con,"specific_table)
