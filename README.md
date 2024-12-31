# Spring JDBC Template with Spring MVC - Contact List Application

This project demonstrates how to integrate the Spring `JdbcTemplate` with a Spring MVC application. The application manages a contact list, allowing users to perform CRUD (Create, Read, Update, Delete) operations.

## Features

- Manage a contact list with basic CRUD functionality.
- Integration of Spring JDBC Template for database operations.
- Use of JSTL for dynamic views in JSP.
- Maven-based build and dependency management.

## Technologies Used

- **Java**: Version 7
- **Spring Framework**: Version 4.0
- **JSTL**: Version 1.2
- **MySQL Database**: Version 5.5
- **Maven**: Version 3
- **Eclipse IDE**: Kepler version

## Prerequisites

Before running the application, ensure you have the following installed:

1. Java Development Kit (JDK) 7 or newer.
2. MySQL Server 5.5 or newer.
3. Maven 3 or newer.
4. Eclipse IDE (Kepler or newer).
5. Apache Tomcat Server (or any compatible servlet container).

### Key Highlights

- **Spring Framework Integration**: Showcases the use of Spring MVC for handling web requests and `JdbcTemplate` for simplifying database interactions.
- **Dynamic UI with JSP and JSTL**: Employs JSP pages with JSTL tags for clean and dynamic front-end rendering.
- **Modular Codebase**: Organized into distinct layers for controllers, services, DAOs, and models, promoting maintainability and scalability.
- **Database Management**: Utilizes MySQL for data persistence, with easily configurable scripts for setup.
- **Build Automation**: Uses Maven for dependency management and project build.

### Features

1. **CRUD Operations**:
   - Add new contacts to the database.
   - View a list of all contacts.
   - Update details of existing contacts.
   - Delete contacts from the list.

2. **User-Friendly Interface**:
   - Clean, minimalistic design with responsive behavior.
   - Dynamic content generation using JSP.

3. **Flexible Database Configuration**:
   - Easily adapt the application to work with different databases by updating configuration files.

4. **Scalable Design**:
   - Supports future enhancements like pagination, search filters, or API integrations.



## Running the Application

1. Import the project into Eclipse as a Maven project.
2. Configure the Tomcat server in Eclipse.
3. Deploy the project to the Tomcat server.
4. Access the application at `http://localhost:8080/SpringJdbcMvc`.

## License

This project is licensed under the MIT License - see the LICENSE file for details
