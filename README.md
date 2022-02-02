# Mysql_JDBC_Connection
Driver class: The driver class for the mysql database is com.mysql.jdbc.Driver.
<br/>
Connection URL: The connection URL for the mysql database is jdbc:mysql://localhost:3306/sonoo where jdbc is the API, mysql is the database, localhost is the server name on which mysql is running, we may also use IP address, 3306 is the port number and sonoo is the database name. We may use any database, in such case, we need to replace the sonoo with our database name.
<br/>
Username: The default username for the mysql database is root.
Password: It is the password given by the user at the time of installing the mysql database. In this example, we are going to use root as the password.
<br/>
String url = "jdbc:mysql://localhost:3306/Emp";
    <br/>
    String driver = "com.mysql.jdbc.Driver";
        <br/>
        String userName = "";
        <br/>
        String password = "";
        <br/>
        Connection conn = DriverManager.getConnection(url,userName,password);
