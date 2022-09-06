# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later
- Docker & docker compose

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
- Docker containers
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql

# Application
- Edit /src/main/resources/application.properties conf file for desired values
- PS: Use the same values in the docker compose file for corresponding docker images variables

# Docker images
- To build docker images go to the directory containing dockerfile and run
- > docker build -t projectname/containername:TAG .
