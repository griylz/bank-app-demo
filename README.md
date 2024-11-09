
# Demo Bank Application

This project is a demo banking application built with a modern tech stack, including a Spring Boot back-end and an Angular.js front-end. It demonstrates secure and efficient interaction between the client-side and server-side, using best practices in both development and security.

## Table of Contents
- [Technologies](#technologies)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Security Measures](#security-measures)
- [Contributing](#contributing)
- [License](#license)

## Technologies

**Front-end:**  
- **Angular.js**: For building a dynamic and user-friendly client-side application
- **TypeScript**: Used to take advantage of type safety and modern JavaScript features

**Back-end:**  
- **Spring Boot**: Provides a robust, scalable, and secure REST API
- **Java**: Language for writing the server-side logic

**Security Technologies:**  
- **JWT (JSON Web Token)**: Used for secure authentication and authorization
- **CORS (Cross-Origin Resource Sharing)**: Configured to ensure secure communication between client and server

## Features

- **Modern UI/UX**: Intuitive and user-friendly design to provide a seamless banking experience
- **Secure Authentication & Authorization**: Protects against common security threats
- **Responsive Design**: Ensures compatibility across devices
- **Robust API Integration**: Smooth data communication between front-end and back-end
- **Error Handling & Logging**: Comprehensive mechanisms for enhanced stability and debugging

## Installation

### Prerequisites
- **Node.js** (for running Angular.js)
- **Java 21** (for running Spring Boot)
- **Maven** (for building the back-end application)

### Steps to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/demo-bank-app.git
   cd demo-bank-app
   ```

2. **Set Up the Back-End**
   - Navigate to the `back-end` directory.
   - Build the application using Maven:
     ```bash
     mvn clean install
     ```
   - Run the Spring Boot application:
     ```bash
     java -jar target/demo-bank-app.jar
     ```

3. **Set Up the Front-End**
   - Navigate to the `front-end` directory.
   - Install the dependencies:
     ```bash
     npm install
     ```
   - Start the Angular.js development server:
     ```bash
     ng serve
     ```
   - The front-end will be available at `http://localhost:4200`.

## Usage

1. Access the front-end at `http://localhost:4200`.
2. Register or log in using your credentials.
3. Explore features such as account balance, transaction history, and money transfers.


## Security Measures

- **JWT Authentication**: Ensures secure token-based login and session management.
- **Password Hashing**: Uses strong hashing algorithms to secure user passwords.
- **CORS**: Configured to allow cross-origin requests securely.
- **Input Validation & Sanitization**: Protects against SQL Injection and XSS attacks.


## License

This project is licensed under the [MIT License](LICENSE).
