# CRUD Operations using Spring Boot and Java

This project demonstrates basic CRUD (Create, Read, Update, Delete) operations using Spring Boot and Java.

## Features

### 1. Create
- **Endpoint:** `/api/create`
- **Description:** Allows the creation of a new entity.
- **Method:** POST
- **Request Body:** JSON format describing the entity to be created.

### 2. Read
- **Endpoint:** `/api/{id}`
- **Description:** Retrieves a specific entity by ID.
- **Method:** GET
- **Path Variable:** `id` - ID of the entity to retrieve.

### 3. Update
- **Endpoint:** `/api/update/{id}`
- **Description:** Updates an existing entity by ID.
- **Method:** PUT
- **Path Variable:** `id` - ID of the entity to update.
- **Request Body:** JSON format containing updated information.

### 4. Delete
- **Endpoint:** `/api/delete/{id}`
- **Description:** Deletes an entity by ID.
- **Method:** DELETE
- **Path Variable:** `id` - ID of the entity to delete.

## Technologies Used
- Spring Boot
- Java
- RESTful API

## Getting Started
1. Clone the repository: `git clone https://github.com/anushka-srivastava22/rest-api-crud-operation.git`
2. Navigate to the project directory: `cd your_project`
3. Build the project: `mvn clean install`
4. Run the application: `java -jar target/your_project.jar`

## Usage
1. Make requests to the specified endpoints using a tool like Postman or cURL.
2. Ensure you have valid JSON payloads for create and update operations.
