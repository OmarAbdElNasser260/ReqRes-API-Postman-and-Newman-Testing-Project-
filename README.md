# Manual And Automation API Testing Project 
This project involves testing the [Fake API](https://reqres.in/) using various tools and technologies including *Postman, **Newman. The purpose is to automate the testing of API endpoints to ensure their reliability and performance.

[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)
[![Newman](https://img.shields.io/badge/Newman-00BFFF?style=for-the-badge&logoColor=white)](https://github.com/postmanlabs/newman)


## Tools & Technologies
- *Postman*: Used for manual API testing, sending requests, and verifying responses.
- *Newman*: Command-line tool to run Postman collections for API testing automation.

## Test Scenarios

### 1. Postman Testing

Postman is used to manually test the Platzi Fake API. The test scenarios cover the following endpoints:
- *GET /products*: Fetch all products.
- *GET /products/{id}*: Fetch a specific product by ID.
- *POST /products*: Add a new product.
- *PATCH /products/{id}*: Update partial an existing product by ID.
- *PUT /products/{id}*: Update an existing product by ID.
- *DELETE /products/{id}*: Delete a product by ID.

Assertions in Postman check:
- *Status codes* (200, 201, 404, etc.).
- *Response body content* to verify valid product data.
- *Response time* to ensure optimal API performance.

### 2. Newman Automation

*Newman* is used to run Postman collections from the command line or as part of a CI/CD pipeline. This makes it easy to automate tests across different environments.

## Conclusion
This project automates API testing of the Platzi Fake API using Postman, Newman. With automated testing integrated into CI/CD, we can ensure that the API is consistently reliable and performs well over time.
