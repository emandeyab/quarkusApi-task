# Quarkus CRUD Product Management Application

## Overview
This is a simple RESTful API application built with Quarkus to manage a list of products (Create, Read, Update, Delete operations). The application uses JAX-RS for endpoints and stores products in an in-memory `ArrayList` for simplicity.

## Features
- Add a new product.
- Retrieve all products or a specific product by ID.
- Update an existing product's details.
- Delete a product by ID.

## Prerequisites
- Java 11 or higher.
- Maven (for building the project).
- Postman (for testing the API).

## Setup Instructions
1. **Clone the Repository** (if applicable):
   ```
   git clone <repository-url>
   cd quarkus-crud
   ```
2. **Build the Project**:
   ```
   ./mvnw clean install
   ```
3. **Run the Application**:
   ```
   ./mvnw quarkus:dev
   ```
   The application will start on `http://localhost:8080`.

