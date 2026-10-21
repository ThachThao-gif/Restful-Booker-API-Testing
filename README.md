# Restful-Booker-API-Testing
Manual REST API Testing project using Postman
# Restful Booker – REST API Testing

## Project Overview

A personal API testing practice project using Postman to validate basic REST API functionalities of the Restful Booker hotel booking demo system.

## Tools & Technologies

- Postman
- REST API
- HTTP Methods: GET, POST
- JSON Request/Response

## Test Scope

| ID | Method | Endpoint | Status |
|---|---|---|---|
| API_01 | GET | /ping | PASS |
| API_02 | GET | /booking | PASS |
| API_03 | POST | /booking | PASS |
| API_04 | GET | /booking/{id} | PASS |
| API_05 | POST | /auth | PASS |

## Test Results

- Total Test Cases: 5
- Executed: 5
- Passed: 5
- Failed (Final): 0
- Pass Rate: 100%
- Confirmed Defects: 0

## Testing Activities

- Executed GET and POST requests using Postman.
- Verified HTTP status codes and JSON response data.
- Created a booking and retrieved its details using the generated Booking ID.
- Tested authentication and verified token generation.
- Investigated unsuccessful requests and corrected request configuration.

## Limitations

This is a basic API testing practice project. It does not include automated assertions, performance testing or comprehensive security testing.

## API Documentation

https://restful-booker.herokuapp.com/apidoc/index.html
