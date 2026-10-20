# First-Java-CRUD

**Student:** Damir Rymsha

**Student ID:** 73597

A simple Java application for managing customers, created for the First Java CRUD assignment.

## Features

- Add a customer.
- View the customer list.
- Edit customer details.
- Delete a customer.
- Search customers by last name.

## Technologies

- Java 21
- Spring Boot
- Vaadin
- Spring Data JPA
- H2 Database
- Maven

## Run locally

Open the project directory in a terminal.

On Windows:

```powershell
.\mvnw.cmd spring-boot:run
```

On macOS or Linux:

```bash
./mvnw spring-boot:run
```

After the application starts, open http://localhost:8080 in a browser.

## Project structure

- `Customer.java` — customer data.
- `CustomerRepository.java` — database operations.
- `MainView.java` — customer table and search.
- `CustomerEditor.java` — form for adding, editing and deleting customers.
- `CrudWithVaadinApplication.java` — application entry point and sample data.

## Source

Based on the [Spring CRUD with Vaadin tutorial](https://spring.io/guides/gs/crud-with-vaadin/) and its [example code](https://github.com/spring-guides/gs-crud-with-vaadin).
