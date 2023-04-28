# Bash-Script-CentOS-8
Install software (( PHP-FPM, PostgreSQL, Nginx)at the top of the script is the configuration of the web server settings (version PHP-fpm, PostgreSQL,) on Centos 8 for AWS https://aws.amazon.com with 1 CPU 1Gb RAM.
The bash script contains files for configuration settings. The script also contains all the files ( index.php and test config nginx file).
this is bash script creates a PostgreSQL user with a randomly generated password (login and password are written to the /home/centos/account_data.csv file) after creating the database configuration, changes are made to the authentication from trust to md5. User granted superuser permissions.
