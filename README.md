# MEME - MALL MANAGEMENT SYSTEM

The Mall Management System is a web-based application designed to streamline and enhance mall operations by centralizing management functions and improving the overall customer experience. The platform acts as a bridge between administrators, vendors, and customers, ensuring seamless interaction and efficient service delivery.

- Centralized Operations & Service Integration:
  Designed and implemented a comprehensive platform integrating ticketing, event management, parking, store administration, and customer engagement, enabling a one-stop solution for mall services.
- Role-Based Access Control (RBAC) with Spring Security:
  Developed secure authentication and authorization mechanisms, ensuring that administrators, vendors, and customers access only relevant features based on their permissions, enhancing security and functionality.
- Optimized Parking Management System:
  Implemented dynamic parking allocation algorithms to reduce peak-hour congestion by assigning spots based on real-time mall traffic data and availability, improving both customer convenience and traffic flow.
- Event & Ticketing System:
  Integrated an automated event management module, allowing users to browse, book, and manage tickets for events, promotions, and entertainment activities within the mall.
- Vendor & Store Management:
  Provided vendors with tools to manage inventory, promotions, and customer interactions, enabling better business insights and operational efficiency.

This scalable system transforms traditional mall management into a digitally connected, automated, and user-friendly experience, making shopping more convenient while ensuring efficient mall administration.

## GETTING STARTED

To run this project locally, follow these steps:

### GITHUB:

Clone the git repository of the project: git clone https://github.com/keerthireddytummalapelly/MEME

### PRE-REQUISITES:

1. Install Java 11
2. Install Maven
3. Eclipse IDE for Enterprise Java and Web Developers -2022 -12
4. MySQL Workbench 8.0 CE

### FRONTEND SETUP:

1. Import the zip file of the project into eclipse IDE.
2. Add the Lombok plugin to Eclipse by using the URL https://projectlombok.org/p2.
3. Edit the following properties in ~/mallmgt/src/main/resources/application.properties file.

```
        spring.datasource.url=jdbc:mysql://localhost:3306/mallmgt?createDatabaseIfNotExist=true

        spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

        spring.datasource.username=root

        spring.datasource.password=root

        spring.jpa.database-platform = org.hibernate.dialect.MySQL8Dialect

        spring.jpa.generate-ddl=true

        spring.jpa.hibernate.ddl-auto = update

        server.port = 8080

```

### BACKEND SETUP:

1. Create MYSQL server on port 8080.
2. Dump the Database.sql file into MySQL Workbench.

### STEPS TO RUN THE PROJECT:

1. Run ~/mallmgt/src/main/java/in/co/health/care/mgt/sys/MallManagementApplication.java file as Java Application.
2. The application will be hosted on http://localhost:8080/MallManagement/
