# Family-Cash-Card-App

Welcome to the **Family Cash Card App**! This project is a fully functional REST API built using **Spring Boot** and the **Spring Framework**. It follows a **Test Driven Development (TDD) approach** to ensure reliability and robustness. The primary goal of this application is to allow families to manage allowances through digital debit cards, providing a seamless and secure way to distribute funds among family members.

## Project Overview

With this application, users can create, manage, and delete cash cards securely. **Spring Security** ensures that only authorized users have access to their respective cash card data. **Spring Data JDBC** simplifies the process of interacting with the database by automatically converting Java objects to database entities and vice versa.

Additionally, to enhance the development experience, an in-memory **H2 database** is utilized, making it easier to test and deploy the application without requiring a full-fledged database setup.

Disclosure: I completed a course in [Spring](https://spring.io/) to help solidify my knowledge and skills in developing this project.

## Getting Started

To get started with **Spring boot**, you can use the **[Spring Initializr](https://start.spring.io/)**. Spring Initializr is web-based tool that allows for you to easily set up Spring boot projects in an easy and efficient manner.

For additional documentation and in-depth tutorials on using Spring Boot, visit the official [Spring Guide](https://spring.io/guides/gs/spring-boot)

## Key Features and Learnings

#### 📌 REST APIs

The project implements a RESTful API using Spring's `@RestController` annotation. The API enables users to perform **CRUD operations (Create, Read, Update, Delete)** on cash cards. Each endpoint is designed to ensure smooth and intuitive interactions, allowing users to manage their cards efficiently.

For more insights on building REST APIs with Spring Boot, visit this [guide](https://www.geeksforgeeks.org/spring-boot-crud-operations/).

#### 📌 Data Persistence

For ease of development and testing, this project uses **H2 Database**, an in-memory relational database that simplifies data storage and retrieval during runtime. This means the database resets with each application restart, making it an excellent choice for rapid development and testing.

Learn more about H2 Database [here](https://www.baeldung.com/spring-boot-h2-database).

#### 🔐 Spring Security

Security is a top priority in this application. **Spring Security** is integrated to provide **Basic Authentication**, ensuring that only authorized users can access and manage their cash cards. Each user has specific permissions, making sure that financial data remains secure and private.

To explore how Spring Security works, check out this [Spring Security guide](https://spring.io/guides/gs/securing-web).

#### ✅ Test Driven Development & Unit Testing

Throughout the development lifecycle, **unit tests** were written and executed to verify that the Cash Card Service functions as expected.
This **TDD approach** helps in identifying potential bugs early and ensures that any modifications made to the system do not break existing functionality.

Unit testing in Spring Boot is a critical aspect of developing robust applications, and by following this approach, the project is **well-tested maintainable and reliable**.

## How to Run the Project

1. Clone this Repository

   `git clone https://github.com/your-username/family-cash-card-app.git`

2. Navigate to the Project Directory

   `cd family-cash-card-app`

3. Build and run the application using Maven

   `mvn spring-boot:run`

4. Access the API at `http://localhost:8080`. - Or whatever port you decided to use.

## Conclusion

The Family Cash Card App is a comprehensive project that demonstrates the power and flexibility of Spring Boot and Spring Security in building secure, scalable, and RESTful applications. By leveraging TDD, robust authentication mechanisms, and efficient data handling techniques, this project serves as an excellent example of a well-structured Spring Boot application.

For further learning, you can check out the **[Spring Academy©](https://spring.academy/courses/building-a-rest-api-with-spring-boot)** course, which played a crucial role in shaping this project.

Happy coding! 🚀
