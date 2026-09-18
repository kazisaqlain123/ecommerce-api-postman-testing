# E-Commerce API Testing with Postman

This project demonstrates basic API testing using Postman and Newman.

## API Used

DummyJSON Products API

## Test Coverage

- GET all products
- GET product by ID
- Negative GET with invalid product ID
- POST add product
- PATCH update product
- DELETE product

## Assertions Covered

- Status code validation
- Response field validation
- Product ID validation
- Product data validation
- Error message validation
- Array length validation
- Required field validation

## Tools

- Postman
- Newman
- JavaScript
- Git
- GitHub

## Run with Newman

Command: newman run E-Commerce_API_Testing.postman_collection.json

## Current Result

- 6 requests executed
- 17 assertions passed
- 0 failures