# Task Management API

This is a RESTful API for a Product Management application, built with Java and Spring Boot.

## Features

*   GET products.
*   Pagination support for products lists.
*   API documentation with Swagger UI.

## Prerequisites

*   Java 21
*   Maven 3.x

## How to Build and Run

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd product
    ```
3.  **Build the project:**
    ```bash
    ./mvnw clean package
    ```
4.  **Run the application:**
    ```bash
    java -jar target/Products-0.0.1-SNAPSHOT.jar
    ```

The application will start on port `8080`.

## API Endpoints

The following endpoints are available:

| Method | Endpoint    | Description                 |
|--------|-------------|-----------------------------|
| `GET`  | `/products` | Get a list of all products. |


**Example:**

```
GET /products
```

## API Documentation

This project uses Springdoc OpenAPI to generate API documentation. Once the application is running, you can access the Swagger UI at the following URL:

[http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

This interface provides detailed information about the API endpoints and allows you to interact with them directly.