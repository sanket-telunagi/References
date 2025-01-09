# References
# this is a repository for reference code snippets
# java read json file using gson
# updating the json file using gson 
# connecting kafka using java
# connecting mssql using java 
```java
import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.ResultSet;
import java.sql.SQLException;
import java.sql.Statement;

// create mssql url
String connURL = "jdbc:sqlserver://<server address>;username=<username>@<server>;password=<password>;";
try(Connection connection = DriverManager.getConnection(connURL)) {
    System.out.println("Connected to the database successfully!");
    return true;
} catch (SQLException e) {
    e.printStackTrace();
    return false ;
}
```
