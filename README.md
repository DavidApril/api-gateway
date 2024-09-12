# API Gateway - Scalable Ecommerce Platform

## Description

This project is an **API Gateway** microservice for a scalable ecommerce platform, developed with **FastAPI** and *
*Python**. The API Gateway centralizes the management of all client requests to the various microservices that make up
the system's backend. It also implements authentication, load balancing, and security handling.

## Key Features

- **Unified routes**: Centralized access to all platform microservices.
- **Authentication and Authorization**: Integrated with JWT and OAuth2 to secure endpoints.
- **Traffic Management**: Load balancing between microservices and traffic control.
- **Security**: Token validation and CORS handling.
- **Scalability**: Microservice-based architecture that facilitates horizontal scalability.

## Technologies Used

- **Python 3.9+**
- **FastAPI**
- **Uvicorn**
- **Docker** (for containerization)
- **Redis** (for authentication caching and rate limiting)
- **JWT** (for authentication)
- **OAuth2** (for authorization)
- **Nginx** (optional, as a reverse proxy)

## Project Structure

    api-gateway/
    ├── app/
    │   ├── api/               # Route definitions
    │   ├── core/              # App core configuration (security, authentication)
    │   ├── models/            # Data models
    │   ├── services/          # Logic to interact with other microservices
    │   └── main.py            # Application entry point
    ├── tests/                 # Unit tests
    ├── Dockerfile             # Docker image for the microservice
    ├── requirements.txt       # Project dependencies
    └── README.md              # Project documentation

## Installation and Setup

### Prerequisites

- **Python 3.9+**
- **Docker** (optional, for running in containers)
- **Redis** (for caching)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/DavidApril/E-commerce_platform.git
   cd api-gateway
   ```
   
