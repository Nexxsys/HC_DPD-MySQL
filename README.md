# HC_DPD-MySQL
MySQL database creation and population of the HC DPD

HC_DPD-MySQL
This is a compilation of files for the creation of tables in MySQL as well as the import process for creation of a Health Canada Drug Product Database using MySQL
Process

## If you are doing this from a NON-XAMPP install, say from a Ubuntu Server SSH connection.
Pre-REQ: Have downloaded and unzipped the allfiles.zip from Health Canada.
wget http://www.hc-sc.gc.ca/dhp-mps/alt_formats/zip/prodpharma/databasdon/allfiles.zip

1. Login to phpmyadmin (need to have it installed on the server)
2. Import the hc_dpd_tables_mysql.sql script
3. unzip allfiles.zip and you must then copy those files over to the /var/lib/mysql/hc_dpd/
4. in your SSH connection execute this: mysql -h localhost -u <MySQL Username> -p<password>
*** yes, the -p and password must be together with no space between them
5. Then execute the MySQL Import Strings (MySQL Import Strings.txt)
