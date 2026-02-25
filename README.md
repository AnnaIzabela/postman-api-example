# Example Postman Collection

This is a **sample Postman collection** created to demonstrate API testing skills. It includes basic API requests and automated tests using Postman's **built-in Chai library**.

> The collection was developed using **Swagger documentation** as a reference.

## Overview

- **Login** – POST request to `/login`, saves Bearer token.  
- **Get Projects / Drivers / Clients / Cars** – GET requests using the saved token.  
- **Add Project** – POST request to `/projects` with example data and a test for response status `200`.

## Key Features

- Automated tests with Chai assertions.  
- Pre-request scripts for token handling.  
- Environment and collection variables used for dynamic requests.

## Notes

All data (username, password, URLs) are **placeholder values**. This collection is meant to **showcase testing skills**, not for direct API usage.
