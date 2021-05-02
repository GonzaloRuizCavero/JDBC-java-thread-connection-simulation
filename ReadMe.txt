

In order to make it work, make sure of the following:

- You have an APACHE server active (or any other listening server)

- The port of the sockets in all files is the same (default is 5064)

- The string containing the location of the virtual machine storing the database is correct and the same in all files 
(Default is String url = "jdbc:mysql://192.168.2.138:3306";)

- The string user and pass (containing the user and password of the mysql user) are changed 
to match your username (Default are String user = "GONZALO"; String pass = "Gonzalo1!";)

+ You can change the speed in which the cases are reported with the doublingTime variable (lower = more speed).
+ The database created in the MySQL database is called MINISTRY_OF_HEALTH
+ Each hospital creates its own table in that database, storing its number of reported cases.
+ The file TransactionData.txt shows the results of the algorithm when using transactions in different cases.
