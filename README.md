# BT20CSE088_SL3_A1_Q12
Create Database 

Cmd : CREATE DATABASE Student_DB;

Craete User

Cmd : CREATE USER 'nikhil_reddy'@'%' IDENTIFIED WITH mysql_native_password BY 'scientist@123';

Give User Permisssion Over DataBase

Cmd : GRANT ALL ON Student_DB.* TO 'nikhil_reddy'@'%';

I have created table named "Student_Deatails" in a database names "Student_DB"
through the command in mysql 

"CREATE TABLE Student_DB.Student_Details(Name VARCHAR(255) NOT NULL,(20) primary key,Roll_no int(5) not null, Year_of_Study int(1) not null,Department VARCHAR(10));"

now I have created index.html with the command "nano /var/www/nikhil/index.html"
now I have created insert.php with the command "nano /var/www/nikhil/insert.php"
now I have created edit.php with the command "nano /var/www/nikhil/edit.php"
now I have created delete.php with the command "nano /var/www/nikhil/delete.php"
now I have created display.php with the command "nano /var/www/nikhil/display.php"

Now we can open the index.html file in the browser with the url "http//:ip_address/index.html"
and now you can do any insertion , deletion, editing,display database.
