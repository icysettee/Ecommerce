# Ecommerce Store

**Ecommerce Store** is an online shopping web application built with **Java Spring Boot MVC** and **Thymeleaf**. The frontend is developed using **HTML, CSS, JavaScript**, and **jQuery**, including **jQuery DataTables** for enhanced data management.

The backend leverages **Spring Boot** for a clean, structured codebase with a **service layer**, **Spring Data JPA** for efficient database operations using **MySQL**, and **Spring Security** for user authentication and role-based authorization. The project uses **Lombok** to reduce boilerplate code and is packaged as a **WAR** file for easy deployment on any servlet container such as **Apache Tomcat**.

---

## Features

- **Spring Boot MVC Architecture** — Well-organized structure with Service, Repository, and Controller layers for clean, maintainable, and scalable code.

- **Frontend Technologies**
  - **Thymeleaf** — Server-side Java templating engine for rendering dynamic HTML pages.
  - **HTML5 / CSS3** — Responsive design for modern browsers and mobile devices.
  - **JavaScript & jQuery** — Dynamic and interactive UI elements.
  - **jQuery DataTables** — Pagination, sorting, and search functionality for data tables.

- **Backend Technologies**
  - **Java Spring Boot (3.3.2)** — Core framework handling business logic and database interaction.
  - **Spring Data JPA** — Simplified data access with custom JPA finder methods.
  - **MySQL** — Relational database for data persistence.
  - **Spring Security** — User authentication and role-based access control.
  - **Lombok** — Eliminates boilerplate code (getters, setters, constructors).
  - **Maven** — Build and dependency management.
  - **Java Mail Sender** — Email support for password reset functionality.

- **Security Features**
  - User authentication and authorization via Spring Security.
  - Protected routes with role-based access control.

- **Deployment** — Packaged as a **WAR** file, deployable on any servlet container like Apache Tomcat.

- **Modern Development Practices**
  - Spring Boot DevTools for hot reload during development.
  - Custom JPA queries for efficient data retrieval.

---

## Requirements

- Java 17 (adjustable for Java 8 environments)
- MySQL
- Maven
- Apache Tomcat (for WAR deployment)

---

## Installation

**1. Clone the repository:**
```bash
git clone https://github.com/icysettee/Ecommerce.git
```

**2. Navigate to the project directory:**
```bash
cd Ecommerce_Store
```

**3. Set up the MySQL database:**
```sql
CREATE DATABASE ecommerce_store;
```

**4. Configure database connection settings in `application.properties`:**
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_store
spring.datasource.username=your-username
spring.datasource.password=your-password
```

**5. Build and run the application:**

Access the app at `http://localhost:8080`.

---

## Modules

- **User Management** — Register, login, logout, disable user, and password reset via email.
- **Admin Dashboard** — Centralized admin control panel.
- **Category Module** — Add, edit, search, and list product categories.
- **Product Module** — Add, edit, view product details, manage stock, and apply discounts.
- **Product Filtering** — Filter products by category with real-time results.
- **Forgot Password** — Email-based password recovery flow.

---

> **Note:** The project is still under active development. Additional modules and features are being added regularly.
