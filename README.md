## Pg System

PG Management System 

How to Installation Custom App on Frappe Framework 

Step 1.bench get-app https://github.com/admin627863/pg_system.git

Step 2. bench --site <site-name> install-app pg_system

Note:  Once you have completed the installation of the custom application, please navigate to the 'database' folder and download the database for the system.

If you have downloaded the database file, kindly place it in the 'frappe-bench' folder directory.

and Try this command:

Step 3. bench --site <site-name> --force restore 20240118_164854-karkhana-database.sql.gz --with-private-files 20240118_164854-karkhana-private-files.tar --with-public-files 20240118_164854-karkhana-files.tar

Congratulations! Your system is now ready to use.

Please use the following credentials:

Username: Administrator
Password: frappe

#### License

MIT