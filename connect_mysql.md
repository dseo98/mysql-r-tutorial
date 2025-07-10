library("DBI")
con <- dbConnect(RMySQL::MySQL(), 
+                  dbname = "your_db", 
+                  host = "localroot", 
+                  port = ____,
+                  user = "root",
+                  password = "your_password")

