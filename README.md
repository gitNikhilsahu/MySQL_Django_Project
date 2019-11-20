django and mysql setup.

download mysqlclient:- https://www.lfd.uci.edu/~gohlke/pythonlibs/ 

mysql path:- C:\Program Files\MySQL\MySQL Server 8.0\bin 

OperationalError: (2059, "Authentication plugin 'caching_sha2_password' cannot be loaded:   The specified module could not be found.\r\n")   

run cmd (press WINDOWS BUTTON + R) / write cmd / press enter   

mysql -u root -p   

ALTER USER 'username'@'ip_address' IDENTIFIED WITH mysql_native_password BY 'password';       
