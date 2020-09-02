# Miscellaneous

## Description

In this repository you will find multiple files that I consider easier not to have categorized by programming language since they have different objectives and are in different languages. They are mostly configuration scripts.

## File Index
|File name              |Description              |Instructions                |
|-----------------------|-------------------------|----------------------------|
|[mysql_5.7_setup](mysql_5.7_setup)|Script that delete any current version of mysql and its data and install MySQL 5.7.28|WARNING: THIS SCRIPT DELETES ANY FILE OR CONFIGURATION OF YOUR CURRENT MYSQL VERSION.<br>1. Go to console, paste the next command and press enter: wget -O - https://raw.githubusercontent.com/akegiraldo/Miscellaneous/master/mysql_5.7_setup | sudo bash<br>2. Done, it's already installed.|
|[100-dump_only_utf8](100-dump_only_utf8.sql)|To test the AirBnb Clone project, especially in its final stage, we need a large amount of data stored in the database. For this, Holberton provided us with a script with approximately 3500 records between its tables. The problem is that the original file has some characters that are not encoded in UTF8. This script has the same data as that one, but I fixed the error with those characters. Use only in case the original doesn't work.|1. Open a new console session.<br>2. Clone this repository and enter the resulting folder.<br>3.Copy the following command and press enter: `echo 100-dump_only_utf8.sql | mysql -u root -p` insert the password you created for the root user and press enter again. WARNING: This script deletes the current database with that name and all its records.<br>4. If everything went well, you already have the database, the user and all the information created.<br>|
