# MEME - MALL EXPERIENCE MADE EASY

A web-based application aimed at enhancing the efficiency and convenience of mall operations. The application serves as a centralized platform connecting users and administrators, facilitating seamless interaction and improving
customer experience.

## GETTING STARTED

To run this project locally, follow these steps:

# GITHUB:

Git repository URL of the project: https://github.com/keerthireddytummalapelly/MEME

# PRE-REQUISITES:

1. Install Java 11
2. Install Maven
3. Eclipse IDE for Enterprise Java and Web Developers -2022 -12
4. MySQL Workbench 8.0 CE

# FRONTEND SETUP:

1. Import the zip file of the project into eclipse IDE.
2. Add the Lombok plugin to Eclipse by using the URL https://projectlombok.org/p2.
3. Edit the following properties in ~/mallmgt/src/main/resources/application.properties file.
   spring.datasource.url=jdbc:mysql://localhost:3306/mallmgt?createDatabaseIfNotExist=true
   spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
   spring.datasource.username=root
   spring.datasource.password=root
   spring.jpa.database-platform = org.hibernate.dialect.MySQL8Dialect
   spring.jpa.generate-ddl=true
   spring.jpa.hibernate.ddl-auto = update
   server.port = 8080

# BACKEND SETUP:

1. Create MYSQL server on port 8080.
2. Dump the Database.sql file into MySQL Workbench.

# STEPS TO RUN THE PROJECT:

1. Run ~/mallmgt/src/main/java/in/co/health/care/mgt/sys/MallManagementApplication.java file as Java Application.
2. The application will be hosted on http://localhost:8080/MallManagement/

# CREDENTIALS TO USE FOR TESTING:

Admin:
Main Admin:
Username: Admin@gmail.com
Password: Demo@123

    Food Admin:
        Food stall Name: Taco Bell
            Username: Tacobelladmin@gmail.com
            Password: Demo@123
        Food stall Name: Popeyes
            Username: Popeyesadmin@gmail.com
            Password: Demo@123
        Food stall Name: Mc Donalds
            Username: Mcdadmin@gmail.com
            Password: Demo@123

Customer:
Username: Keerthi@gmail.com
Password: Demo@123
