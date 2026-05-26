# Product CRUD REST API

A Spring Boot REST API for managing products using MySQL and Spring Data JPA.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Postman
- Git & GitHub

## Features

- Create Product
- Get All Products
- Get Product By ID
- Update Product
- Delete Product

## API Endpoints

### Get All Products
GET /products

### Get Product By ID
GET /products/{id}

### Create Product
POST /products

Request Body:
{
  "name": "Laptop",
  "price": 50000
}

### Update Product
PUT /products/{id}

Request Body:
{
  "name": "Updated Laptop",
  "price": 55000
}

### Delete Product
DELETE /products/{id}

## Author

Rithika P
