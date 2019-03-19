# 5709Project

## Setup
**Note** Make sure you have NPM, node, mysql server installed in your local machine
### Node Server setup
1. Once you have node and npm installed, run `npm install` to install required dependencies in the command line / terminal
2. Same in the command line / terminal, run `npm run start` to start the application

### MySQL Server setup
1. Once you have MySQL server installed, change the password of `root` role for your Mysql server. This can be done by running `ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'root';` in the command line / terminal after you login the Mysql server.
2. Create a database name called `5709Project`
3. It would be more straightforward if your have mysql workbench application in your machine, then you can import the database by following the procedures described in this [link](https://dev.mysql.com/doc/workbench/en/wb-admin-export-import-management.html). The path to sql file is `src/api/connection/database.sql`


