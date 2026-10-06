# Manual Testing Project: AutomationExercise.com

A manual QA project on a practice e-commerce website (https://automationexercise.com),
covering test planning, test case design, execution, bug reporting and basic API testing.

## What's inside
- `docs/`: Test Plan and Test Summary Report
- `test-cases/`: Test case workbook (Signup, Login, Products/Search, Cart, Checkout, Contact Us)
- `postman/`: Postman collection (10 API requests)
- `screenshots/`: Jira bug tickets and Postman responses

## Tools
Excel, Jira (bug tracking), Postman (API testing)

## Approach
Black box, functional testing with smoke and negative checks.
Out of scope: load, stress and security testing, and automation.

## Results
- 35 test cases executed: 32 passed, 3 failed
- 3 bugs logged in Jira (login error messaging, Contact Us form validation)
- API observation: error responses return HTTP 200 with the real error code in the response body

## Notes
This is a practice project on a public demo site. All test data is dummy data.
