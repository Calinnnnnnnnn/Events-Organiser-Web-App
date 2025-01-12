
# Events Organiser Web App

Events Organiser is a Java-based application for managing and organizing events such as parties, meetings, and business gatherings. 
The application uses Spring Boot for backend development and Thymeleaf for the frontend.

## Features

- User registration and authentication.
- Create, edit, and manage events.
- Event categorization by type (e.g., parties, meetings, etc.).
- Payment integration for event-related services (e.g., drones, speakers).
- User dashboard to view organized events.
- Responsive and user-friendly interface.

## Project Structure

```
Events_Organiser/
├── src/                # Source code for the application
├── pom.xml             # Maven configuration file
├── .gitignore          # Git ignore rules
├── HELP.md             # Additional help documentation
├── mvnw, mvnw.cmd      # Maven wrapper scripts
├── .mvn/               # Maven wrapper configuration files
├── target/             # Compiled files and build artifacts
└── .idea/              # IntelliJ IDEA configuration files
```

## Technologies Used

- **Java 17**: Main programming language.
- **Spring Boot**: Backend framework.
- **Thymeleaf**: Template engine for the frontend.
- **MySQL**: Relational database for storing user and event information.
- **Maven**: Build and dependency management tool.

## Installation

### Prerequisites

- Java 17 or later installed.
- Maven installed.
- MySQL server running.

### Steps

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd Events_Organiser
   ```

2. Set up the database:
   - Create a database named `Events_Organiser` in MySQL.
   - Update the database connection details in `src/main/resources/application.properties`.

3. Build the project:
   ```bash
   ./mvnw clean install
   ```

4. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

5. Access the application in your browser at `http://localhost:8080`.

## Usage

- Register an account or log in using an existing account.
- Create events by providing details such as name, type, and description.
- Add optional services for events and complete payment to confirm.
- View and manage your events from the dashboard.
