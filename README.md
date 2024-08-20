# Employee Management System

A basic Employee Management System built with Node.js, Express, and MongoDB.

## Features

- **Employee Management**: HR can add, update, delete, and list employees.
- **Role-Based Access Control (RBAC)**: Different access levels for HR and employees.
- **Performance Reviews**: HR can add performance reviews; employees can view their own reviews.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/employee-management-system.git
    cd employee-management-system
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    npm start
    ```

4. Access the app at `http://localhost:4000`.

## API Endpoints

- `POST /employees/create-employee` - Create a new employee.
- `GET /employees` - Get a list of all employees.
- `PUT /employees/update-employee/:id` - Update an employee by ID.
- `DELETE /employees/delete-employee/:id` - Delete an employee by ID.

## Database Schema

### Employee

```json
{
  "id": "Number",
  "name": "String",
  "email": "String",
  "rollno": "Number",
  "department": "String",
  "role": "String"
}
Department
json
Copy code
{
  "id": "Number",
  "name": "String"
}
Role
json
Copy code
{
  "id": "Number",
  "name": "String"
}
License
This project is licensed under the MIT License.

css
Copy code

This snippet provides a structured overview of the project, its features, installation instructions, API endpoints, and database schema.
