# Employee Directory REST API

This project is a simple RESTful API built with Spring Boot to manage employee information. It allows users to perform Create, Read, Update, and Delete (CRUD) operations on employee records.
<img width="600" alt="Screenshot 2025-05-01 at 3 25 40 AM" src="https://github.com/user-attachments/assets/ef629a1a-a5ca-42ce-8aaa-5a79d4291b36" />


## Technologies Used

- Spring Boot
- Java
- RESTful API
- Spring Data JPA
- HTML/CSS
- MySQL DB

## Features

* **Add Employee:** Creates a new employee record.
* **View Employees:** Retrieves a list of all employees.
* **Update Employee:** Modifies the details of an existing employee.
* **Delete Employee:** Removes an employee record.

## How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/viratvector/rest-crud-api-employee-directory.git](https://github.com/viratvector/rest-crud-api-employee-directory.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd rest-crud-api-employee-directory
    ```
3.  **Build the application:**
    * **Using Maven:**
        ```bash
        ./mvnw spring-boot:run
        ```
    * **Using Gradle:**
        ```bash
        ./gradlew bootRun
        ```
4.  **Access the API:** Once the application is running, you can interact with the API endpoints using tools like Postman, cURL, or a web browser.

    * **Base URL:** Typically `http://localhost:8080` (may vary based on configuration).
    * **Endpoints (Examples):**
        * `POST /api/employees`: Add a new employee (request body in JSON format).
        * `GET /api/employees`: Get all employees.
        * `GET /api/employees/{id}`: Get a specific employee by ID.
        * `PUT /api/employees/{id}`: Update an existing employee (request body in JSON format).
        * `DELETE /api/employees/{id}`: Delete an employee by ID.
