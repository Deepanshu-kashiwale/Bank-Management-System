# Bank Management System

A banking management project repository containing the existing banking application and the StateBank Banking Portal demo.

## StateBank Banking Portal

A full-stack educational banking management application built with:

- **Frontend:** React, Vite, JavaScript, CSS
- **Backend:** Java, Spring Boot, Spring Data JPA
- **Database:** MySQL
- **Build tool:** Maven

### Features

- Dashboard overview
- Customer management
- Bank account management
- Transaction records
- Cards and loans
- Branch and employee management
- Reports
- Add, view, edit, and delete operations for supported modules

### Prerequisites

- Node.js and npm
- JDK 21
- Maven
- MySQL Server

### Run the project

1. Create the database:

   `CREATE DATABASE statebank_demo;`

2. Configure the MySQL username and password using environment variables `DB_USERNAME` and `DB_PASSWORD`, or your local configuration.

3. Start the backend from the `backend` directory:

   `mvn spring-boot:run`

4. Start the frontend from the `frontend` directory:

   `npm install`

   `npm run dev`

5. Open the local URL displayed by Vite, usually `http://localhost:5173`.

The backend normally runs at `http://localhost:8080`.

**Note:** This is an educational demo, not a production banking system. It does not provide production-grade authentication or real banking transaction processing.

## Existing Team Project

The repository also contains the existing `banking-app` project.

### Team Members

1. Piyush Pathak — Frontend MVC, routing, HTTP services
2. Deepanshu Kashiwale — Backend banking modules, including transactions and loans
3. Bhavesh Baviskar — Database service, DFDs, schemas, reverse engineering
4. Aditya Yeole — Backend module integration

## License

See the repository's `LICENSE` file.
