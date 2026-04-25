# Assignment4 — Spring MVC Member Registration & CRUD App

## Overview

A full-stack Java web application demonstrating **Create, Read, Update, and Delete (CRUD)** operations for member registration and login management. Built with the Spring Framework, secured with Spring Security, and backed by ObjectDB — an object-oriented JPA database.

## Tech Stack

- **Language:** Java (JDK 6+)
- **Framework:** Spring Framework 3.2.3, Spring Security 3.1.4
- **Database:** ObjectDB 2.6.3 (JPA/Hibernate)
- **Frontend:** JSP/JSTL, Bootstrap, HTML5, CSS3, JavaScript/jQuery
- **Build:** Apache Maven (WAR packaging)
- **CI/CD:** GitHub Actions + SonarCloud (code quality), JaCoCo + Coveralls (test coverage)

## Features

- User registration with form validation
- Login and authentication via Spring Security
- Member management (create, view, update, delete)
- Protection against POST_BACK bugs

## Requirements

- Java JDK 6.0 or above
- Maven 3+
- GlassFish Web Server (or compatible servlet container)
- Chrome or Firefox browser (IE not supported)

## Getting Started

1. Clone the repository.
2. Build the project:
   ```bash
   mvn clean install
   ```
3. Deploy the generated `.war` file to GlassFish or your preferred servlet container.
4. Access the app in your browser at `http://localhost:8080/Assignment4`.

## Project Structure

```
src/
├── main/
│   ├── java/          # Controllers, DAOs, Models, Validators
│   └── webapp/        # JSP views, Spring/Security config
└── test/
    └── java/          # JUnit tests
```

## Author

Arpitha M J
