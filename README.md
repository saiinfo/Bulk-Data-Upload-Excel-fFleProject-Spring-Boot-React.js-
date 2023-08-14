# Bulk Data Upload Project (Spring Boot + React.js)

This project demonstrates bulk data uploading from an Excel file to a database using Spring Boot for the backend and React.js for the frontend.

## Description

This project provides a user-friendly interface for bulk uploading of data stored in an Excel file to a database. The backend processes the uploaded data and stores it in the database. The frontend allows users to select an Excel file, initiate the upload, and monitor the progress.

## Features

- Upload Excel file containing bulk data for upload.
- Process the Excel file data and store it in the database.
- Display status and progress of the upload process.
- User-friendly interface with responsive design.

## Prerequisites

Before running the project, make sure you have the following installed:

- Java Development Kit (JDK) 11+
- Node.js and npm

## Installation

### Backend

1. Clone this repository
2. Navigate to the `backend` directory: `cd bulk-data-upload/backend`.
3. Build the Spring Boot project: `./mvnw clean install`.
4. Run the Spring Boot application: `./mvnw spring-boot:run`.

### Frontend

1. Navigate to the `frontend` directory: `cd bulk-data-upload/frontend`.
2. Install frontend dependencies: `npm install`.
3. Start the React development server: `npm start`.

## Usage

1. Open your browser and go to `http://localhost:3000`.
2. Navigate to the bulk upload page.
3. Upload an Excel file containing data for bulk upload.
4. Initiate the upload process.
5. Monitor the status and progress of the upload.
6. 
## Technologies Used

### Backend

- Java Spring Boot
- Spring Data JPA
- Apache POI (for Excel processing)

### Frontend

- React.js
- Axios (for API requests)

