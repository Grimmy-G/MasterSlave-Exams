# MasterSlave-Exams


The project contains the automation and provisioning of two Ubuntu-based servers, named “Master” and “Slave”,

using Vagrant, with a bash script to automate the deployment of a LAMP (Linux, Apache, MySQL, PHP) stack,

and cloned a PHP application from GitHub, with all necessary packages, and configured Apache web server and MySQL

while using ansible to execute the bash script on the Slave node and cronjob to create check the server's uptime
 
every 12:00am. the bash script is reusable and readable and can be accessible through the following repository:

git@github.com:Grimmy-G/MasterSlave-Exams.git
