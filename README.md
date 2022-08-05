# task:
### programming a web page This page does a "Get" of any integer number and then stores this number in database

# steps:
1. Download xampp
2. We use any text editor
3. Create a folder inside the htdocs folder
4. Include php files inside the folder we created 
5. Run phpMyadmin to create the database

# connection code

> <?php
$host="localhost";
$dbuser="root";
$dbpass="";
$dbname="";
$con=mysqli_connect($host,$dbuser,$dbpass,$dbname)
?>

