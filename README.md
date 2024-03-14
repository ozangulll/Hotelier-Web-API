# Hotelier Web API

Hotelier Web API is a RESTful API designed to provide functionalities for managing hotel-related data such as rooms, bookings, and users. It serves as a backend system for hotel management applications, providing endpoints for various CRUD (Create, Read, Update, Delete) operations.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Hotelier Web API simplifies the process of building hotel management applications by providing a standardized interface for interacting with hotel data. It offers endpoints for managing hotel rooms, bookings, and user authentication, allowing developers to focus on building frontend applications without worrying about backend implementation details.

## Features

- **User Authentication:** Secure endpoints requiring user authentication for performing sensitive operations.
- **Room Management:** CRUD operations for managing hotel rooms, including listing, adding, updating, and deleting rooms.
- **Booking Management:** Endpoints for creating, retrieving, updating, and canceling hotel bookings.
- **Search Functionality:** Search functionality to find available rooms based on various criteria such as date, room type, and occupancy.
- **Role-based Access Control:** Different levels of access for users based on their roles, ensuring security and data integrity.
- **Swagger Documentation:** Interactive Swagger documentation for easy exploration of API endpoints.

## Technologies Used

- **ASP.NET Web Forms:** Web application framework for building dynamic web pages using .NET.
- **C#:** Programming language used in conjunction with ASP.NET for server-side logic.
- **Entity Framework:** Object-relational mapping (ORM) framework for .NET, used for database operations.
- **ASP.NET Identity:** Framework for managing users, roles, and authentication in ASP.NET applications.
- **JSON Web Tokens (JWT):** Secure mechanism for user authentication and authorization.
- **Swagger UI:** Framework for generating interactive API documentation.

## Installation

To run Hotelier Web API locally, follow these steps:

```bash
git clone https://github.com/ozangulll/Hotelier-Web-API.git

Open the solution file (Hotelier-Web-API.sln) in Visual Studio.

Build the solution to restore NuGet packages and compile the project.

Set up the database connection string in the Web.config file.

Run the application using the local development server provided by Visual Studio.

Access the API at http://localhost:<port>/api.
