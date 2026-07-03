Wells Fargo Software Engineering Virtual Experience – Task 2

A Java-based implementation developed as part of the **Wells Fargo Software Engineering Virtual Experience Program (Forage)**. This project demonstrates object-oriented programming principles by modeling the relationship between financial advisors, clients, investment portfolios, and securities.

Project Overview

The objective of this task is to build a simple financial domain model that represents how advisors manage clients and their investment portfolios. The implementation focuses on clean object-oriented design, readable code, and maintainable project structure.

Features

* Object-oriented domain model
* Advisor, Client, Portfolio, and Security entities
* Clear separation of responsibilities between classes
* Maven project structure
* Easy to understand and extend

Project Structure

```text
src
└── main
    └── java
        └── com.wellsfargo.counselor
            ├── Entrypoint.java
            └── entity
                ├── Advisor.java
                ├── Client.java
                ├── Portfolio.java
                └── Security.java
```

Technologies Used

* Java
* Maven
* Object-Oriented Programming (OOP)

Architecture

```text
                Advisor
                   │
          manages Clients
                   │
                   ▼
                Client
                   │
          owns Portfolios
                   │
                   ▼
              Portfolio
                   │
         contains Securities
                   │
                   ▼
               Security
```

Getting Started

### Prerequisites

* Java 17 or later
* Maven 3.8+

Clone the repository

```bash
git clone https://github.com/Aaditya022/wells-fargo-task-2.git
```

Navigate to the project

```bash
cd wells-fargo-task-2
```

### Build the project

```bash
mvn clean install
```

### Run

```bash
mvn spring-boot:run
```

or execute the `Entrypoint` class from your IDE.

Learning Outcomes

This project helped reinforce:

* Object-Oriented Programming
* Class design
* Entity relationships
* Code organization
* Maven project management

Future Improvements

* Add unit tests using JUnit 5
* Add input validation
* Introduce service and repository layers
* Add REST APIs using Spring Boot
* Persist data using a relational database

License

This project is created for educational purposes as part of the Wells Fargo Software Engineering Virtual Experience Program hosted on Forage.

Author

Aditya Agrawal

GitHub: https://github.com/Aaditya022
