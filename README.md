# ContactManager

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.1.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

This is a Contact Manager Application built with Angular 19 using the legacy (NgModule) approach. It allows users to manage contacts with features such as adding, editing, viewing, and deleting contacts. The project also uses Bootstrap for styling and includes a mock backend using JSON Server.

Setup and Installation

Prerequisites

Ensure you have the following installed:

Node.js (Recommended version 18 or later)

Angular CLI (Version 19.2.1)

Installation Steps

Clone the Repository
git clone <repository-url>
cd contact-manager
npm install

Start the JSON Server (Mock Backend) Navigate to the servers folder and run:
cd servers
npm start

Start the Angular Project Open a new terminal in the root folder and run:
npm start
Access the Application
Visit http://localhost:4200 in your browser.

|-- src
|   |-- app
|       |-- components
|           |-- ContactManagerComponent
|           |-- AddContactComponent
|           |-- EditContactComponent
|           |-- ViewContactComponent
|           |-- NavbarComponent
|           |-- SpinnerComponent
|       |-- models
|           |-- IContact.ts
|           |-- IGroup.ts
|       |-- services
|           |-- contact.service.ts
|-- servers
|   |-- db.json
|   |-- server.js
|-- angular.json
|-- package.json
|-- README.md


✅ Manage contacts (Add, Edit, View, Delete).
✅ Utilizes Bootstrap for responsive styling.
✅ Uses JSON Server for mock API endpoints.
✅ Modularized with Angular components, services, and models for scalability.


The ContactService handles HTTP requests for fetching and managing contact data.

The SpinnerComponent provides a loading indicator during data fetch operations.

The project follows Angular's recommended best practices for modular structure and code organization.
