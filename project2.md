## Documentation for Project 2


### Screenshots of commands executed and corresponding results can be found here:


updating Ubuntu packages to the latest
![sudo apt update](./images/1.%20sudo%20apt%20update.PNG)

installation of NGINX web server
![install nginx](./images/2.%20sudo%20apt%20install%20nginx1.PNG)

checking status of the NGINX server for conformation
![nginx status](./images/3.%20sudo%20systemctl%20status%20nginx.PNG)

This is to to request our Nginx on port 80 
![using curl to get webpage on the terminal](./images/4.%20curl%20http%20localhost%2080.PNG)

This is to test how our Nginx server can respond to requests from the internet via a browser
![accessing via the internet](./images/5.%20using%20public%20ip%20on%20browser%20to%20confirm%20nginx%20is%20running.PNG)

This is to install MySql server
![sudo apt install mysql-server](./images/6.%20sudo%20apt%20install%20mysql-server.PNG)

Launching mysql with user root with sudo rights
![sudo mysql](./images/7.%20launch%20mysql%20with%20user%20root%20with%20sudo%20mysql.PNG)

Setting password for root user
![set password for root](./images/8.%20setting%20a%20password%20for%20the%20root%20user.PNG)

This is to run a preinstalled script to change mysql default settings to enhance security
![run script to change default security settings](./images/9.%20%20run%20a%20preinstalled%20security%20script%20to%20remove%20some%20insecure%20default%20settings.PNG)

This is to login into mysql with root user specifying pasword option
![signin with password](./images/10.%20login%20into%20mysql%20with%20root%20user%20specifying%20pasword%20option.PNG)

To verify successful php installation by checking its version
![php -v](./images/10b.%20php%20installation%20success%20and%20checking%20for%20version.PNG)

This was used to create directory, assign ownership to the logged on user, opening of new config files in the sites-available and the activation of the the new config file
![alt text](./images/10c.%20creation%20of%20root%20directory-assigning%20ownership%20to%20user-opening%20new%20config%20file%20in%20sites-available-activation%20of%20new%20config%20file-testing%20nginx%20new%20config%20for%20errors.PNG)

Testing and successful confirmation of the new config sites-available file
![alt text](./images/10d.%20message%20to%20confirm%20no%20syntax%20error%20in%20the%20new%20config%20file.PNG)

linking of the NGINX server to make use of the PHP processor
![nginx linkup with php processor](./images/11.%20configuring%20nginx%20server%20to%20use%20php%20processor.PNG)

Confirmation of the PHP test with nginx on the browser
![alt text](./images/12.%20testing%20php%20with%20nginx.PNG)

Creation of DB, user within the DB as well as granting the user permissions
![alt text](./images/12b.%20create%20database-create%20user%20with%20password-grant%20permission%20to%20user.PNG)

Signing into MySql server with the new user and displaying all databases in the server.
![sign-in and show databases](./images/12c.%20signin%20with%20new%20user-displaying%20databses%20in%20mysql.PNG)

Creation of tables and insertion of values in the table
![create table and insert into table](./images/12d.%20create%20table%20in%20database%20and%20insert%20values%20into%20table.PNG)

Display table content with SELECT statement
![using select statement](./images/12e.%20displaying%20table%20content%20with%20select%20statement.PNG)

Running PHP script to connect the database as well as querying a to-do list table
![alt text](./images/13.%20PHP%20script%20connects%20to%20the%20MySQL%20database%20and%20queries%20for%20the%20content%20of%20the%20todo_list%20table.PNG)