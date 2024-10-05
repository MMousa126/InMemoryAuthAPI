# InMemoryAuthAPI
# CRM Module QA Assignment

## Project Overview

This project involves testing the **CRM Module** APIs, focusing on functionalities for managing contacts and invoices. As part of the QA assessment, the following tasks were performed:

1. **Test Plan Creation**: Comprehensive test cases for both functional and non-functional requirements.
2. **API Testing**: Testing various endpoints related to managing contacts and invoices.
3. **Bug Reporting**: Identifying bugs in the API and reporting them with detailed descriptions and steps to reproduce.

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

## Running the Tests

1. **Test Plan**: Follow the steps in the test plan to perform the tests. Ensure to cover both functional and non-functional requirements.
2. **Report Bugs**: Use the provided bug report template to document any issues you find. Include steps to reproduce, expected vs. actual results, and severity.

## Bug Reporting

I have identified the following bugs while testing the API:

- Bug 1: [Description of bug 1]
- Bug 2: [Description of bug 2]
- Bug 3: [Description of bug 3]

For the full bug report, please refer to the `bug_report.md` file in the repository.

## Documentation

- [Swagger Documentation](https://qa-assignment.sortcrm.com/swagger/index.html)
- Detailed test plan and bug report can be found in the `docs/` folder.

## Contact

For any inquiries, feel free to contact me at:

- Email: [your_email@example.com](mailto:your_email@example.com)
- GitHub: [yourusername](https://github.com/yourusername)

