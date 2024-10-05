# InMemoryAuthAPI
# CRM Module QA Assignment

## Project Overview

This project involves testing the **CRM Module** APIs, focusing on functionalities for managing contacts and invoices. As part of the QA assessment, the following tasks were performed:

1. **Test Plan Creation**: Comprehensive test cases for both functional and non-functional requirements.
2. **API Testing**: Testing various endpoints related to managing contacts and invoices.
3. **Bug Reporting**: Identifying bugs in the API and reporting them with detailed descriptions and steps to reproduce.

## Test Plan and Bug Report

You can access the **comprehensive test plan and bug report** through the following Google Sheet:

### [Test Plan & Bug Report - Google Sheet](https://docs.google.com/spreadsheets/d/14MUizWVbvJq7uIL6iI-QwvB6tUp0e0bbCCsKYj8SutY/edit?gid=18#gid=18)

This document contains detailed test cases, steps to reproduce bugs, and descriptions of the bugs found during testing.

Additionally, the **issue file** includes **9 issues**, each with corresponding **videos, screenshots**, and **logs** to demonstrate the bugs. 
## Project Structure

- **Test Plan**: A document containing test cases, methods, and expected outcomes for each API endpoint based on the user stories.
- **Bug Report**: A structured bug report with details of the identified issues.
- **API Documentation**: Swagger documentation link used for API testing.
- **API Endpoints Tested**:
    - **Auth**: User Registration and Login.
    - **Contacts**: Managing contact details (CRUD operations and balance adjustment).
    - **Invoices**: Creating, viewing, returning, and paying invoices.

## User Stories

1. **Manage Contacts**: 
    - Create, view, update, and delete contacts.
    - Adjust contact balances.
  
2. **Manage Invoices**: 
    - Create and pay invoices.
    - Mark invoices as returned.

## Prerequisites

To test the API, you need to follow these steps:

1. **API Documentation**: Visit the [Swagger API Documentation](https://qa-assignment.sortcrm.com/swagger/index.html) to view and interact with the API endpoints.
2. **Register an Account**: Use the `/api/Auth/register` endpoint to create a new user.
3. **Login**: After registering, use the `/api/Auth/login` endpoint to log in and obtain an authorization token.
4. **Authorize Swagger**: Before making any requests, use the login token to authorize Swagger by adding `Bearer <your_token>` as the authorization value.

## Contact

For any inquiries, feel free to contact me at:

- Email: [mohamedsamy13699@gmail.com ](mailto:your_email@example.com)
- GitHub: [mohamedsamy13699](https://github.com/yourusername)

