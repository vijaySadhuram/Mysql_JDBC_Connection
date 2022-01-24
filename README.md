# Mysql_JDBC_Connection
Driver class: The driver class for the mysql database is com.mysql.jdbc.Driver.
Connection URL: The connection URL for the mysql database is jdbc:mysql://localhost:3306/sonoo where jdbc is the API, mysql is the database, localhost is the server name on which mysql is running, we may also use IP address, 3306 is the port number and sonoo is the database name. We may use any database, in such case, we need to replace the sonoo with our database name.
Username: The default username for the mysql database is root.
Password: It is the password given by the user at the time of installing the mysql database. In this example, we are going to use root as the password.
String url = "jdbc:mysql://localhost:3306/Emp";
        String driver = "com.mysql.jdbc.Driver";
        String userName = "root";
        String password = "root";
        Connection conn = DriverManager.getConnection(url,userName,password);
