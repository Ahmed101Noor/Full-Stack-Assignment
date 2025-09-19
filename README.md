# Full Stack Assignment Project

This repository contains a full-stack e-commerce application, divided into two main parts: a backend API (`ECommerceTask`) and a frontend application (`Front-Task`).

## Project Structure

### `ECommerceTask/` (Backend)
This directory contains the backend API for the e-commerce application, built using .NET. It follows a layered architecture, separating concerns into different projects:

- `ECommerceTask.sln`: The main solution file for the backend project.
- `eCommerce.API/`: The entry point of the API, containing controllers, program startup, and application settings.
- `eCommerce.Application/`: Contains application-specific logic, DTOs, interfaces, and services.
- `eCommerce.Domain/`: Defines the core business logic, entities, and models of the application.
- `eCommerce.Infrastructure/`: Handles data access, persistence, migrations, and repository implementations.
- `eCommerce.Tests/`: Contains unit and integration tests for the backend.

### `Front-Task/` (Frontend)
This directory houses the frontend application, likely built with Angular given the file structure. It includes all the necessary files for a modern web application:

- `.angular/`: Angular-specific configuration files.
- `.vscode/`: VS Code specific settings for the project.
- `src/`: Contains the source code for the Angular application, including components, assets, and environments.
- `angular.json`: Angular CLI configuration file.
- `package.json`: Defines project metadata and lists dependencies.
- `package-lock.json`: Records the exact versions of dependencies.
- `tsconfig.json`: TypeScript configuration files.

## Getting Started

Further instructions on how to set up and run each part of the application will be provided within their respective `README.md` files or documentation.

## Database

- `Full Stack Assignment.sql`: This file contains the SQL script for setting up the database schema and initial data.
- `Full Stack Assignment.bak`: This is a database backup file, likely for restoring the database to a previous state.