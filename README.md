
# EstateHub — Real Estate Management System

EstateHub is a full-stack real estate management platform developed using Java, Spring Boot, MySQL, and Spring Security. It provides role-based functionality for administrators, property owners, and customers to manage property listings, inquiries, and related transactions.

## Tech Stack

- **Backend:** Java, Spring Boot, Spring Security, Hibernate
- **Database:** MySQL
- **API:** REST APIs
- **Payment Integration:** Razorpay
- **Image Management:** Cloudinary
- **Deployment:** Render, Railway MySQL

## Key Features

### Role-Based Access
- Admin, Owner, and Customer modules
- Authentication and role-based authorization

### Property Management
- Property listing and management
- Property search and filtering
- Property image uploads using Cloudinary

### Customer Features
- Browse available properties
- Submit property inquiries
- Wallet recharge functionality

### Integrations
- Razorpay payment integration
- Cloudinary image management
- MySQL database persistence

## Project Architecture

The application follows a layered Spring Boot architecture:

- **Controller Layer:** Handles HTTP requests and REST APIs
- **Service Layer:** Implements business logic
- **Repository Layer:** Manages database operations
- **Database Layer:** Stores application data in MySQL

## Getting Started

### Prerequisites

- Java
- Maven
- MySQL
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/sinku1999/real-estate-system.git
```

Navigate to the project directory:

```bash
cd real-estate-system
```

Configure your MySQL database connection and required Razorpay and Cloudinary credentials using the configuration mechanism provided by the application.

Build and run the Spring Boot application using the project's Maven configuration.

## Project Highlights

- Full-stack application development
- Role-based authentication and authorization
- REST API development
- Relational database integration
- Payment gateway and image storage integration
- Cloud deployment

## Disclaimer

This project is developed for educational and portfolio purposes.


## Project Status

- **Development:** Completed
- **Source Code:** Available on GitHub
- **Deployment:** Previously deployed using Render and Railway
- **Live Demo:** Temporarily unavailable due to database hosting limitations

> The application can be configured and run locally with a MySQL database.


## Developer

**Sinku Singh**

- [GitHub](https://github.com/sinku1999)
- [LinkedIn](https://linkedin.com/in/sinkusingh1999)
