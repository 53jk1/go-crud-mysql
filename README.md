# 🚀 Deployment <a name = "deployment"></a>

Set enviromental variables:
```
export DBUSER=user
export DBPASS=password
```

Initialize the database:
```
mysql> CREATE TABLE `Employee` (
    -> `id` int(6) unsigned NOT NULL AUTO_INCREMENT,
    -> `name` varchar(30) NOT NULL,
    -> `city` varchar(30) NOT NULL,
    -> PRIMARY KEY (`id`));
    ```

Run the following command:
```
go run main.go
```

Load the following URL: http://localhost:8080
