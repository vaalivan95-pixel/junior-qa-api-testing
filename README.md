# REST API Testing — DummyJSON

## Project Overview

This project demonstrates practical REST API testing skills using Postman and JavaScript.

The goal is to validate API responses, verify data integrity, and test positive and negative scenarios for the DummyJSON Products API.

**API:** https://dummyjson.com

## Tools & Technologies

- Postman
- JavaScript
- Chai Assertions
- REST API, HTTP, JSON
- Git & GitHub

## Test Coverage

| Test Scenario | Method | Endpoint |
|---|---|---|
| Create a product | POST | `/products/add` |
| Get a non-existent product | GET | `/products/999999` |
| Validate pagination | GET | `/products?limit=5&skip=5` |
| Search products | GET | `/products/search?q=phone` |
| Get product by ID | GET | `/products/1` |
| Get all products | GET | `/products` |

## Validation Techniques

- HTTP status code validation
- JSON structure and data type validation
- Required field checks
- Positive and negative API testing
- Pagination and search validation
- Unique ID verification
- JavaScript assertions using `every()`, `map()`, `Set` and Chai

## Test Execution Results

**Last verified run: October 15, 2026**

- Total requests: 6
- Automated assertions: 49
- Passed: 49
- Failed: 0
- Errors: 0
- Average response time: 215 ms

## How to Run

1. Clone this repository.
2. Open the collection folder in a compatible Postman Local workspace.
3. Select the collection in Postman.
4. Open Collection Runner.
5. Run all six requests and review the results.

## Author

Junior Manual QA Engineer — API Testing Portfolio Project
