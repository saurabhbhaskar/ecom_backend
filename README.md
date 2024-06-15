# Artiset Internship Project: eCommerce Backend

## Project Overview

This project is part of the Artiset internship program. The goal is to develop a scalable and efficient backend for an eCommerce application using Node.js and a microservices architecture.

## Technologies Used

- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: NoSQL database for storing application data.
- **Mongoose**: Elegant MongoDB object modeling for Node.js.
- **JWT (jsonwebtoken)**: For secure authentication.
- **bcrypt**: For hashing user passwords.
- **Docker**: Containerization platform for running microservices.
- **Kubernetes**: Container orchestration platform.
- **Nginx**: Web server for reverse proxy and load balancing.
- **RabbitMQ**: Message broker for communication between microservices.
- **Cloudinary**: Cloud storage for managing images and videos.

## Microservices

1. **User Service**: Handles user authentication, registration, and profile management.
2. **Product Service**: Manages product listings, categories, and inventory.
3. **Order Service**: Processes customer orders and manages order history.
4. **Payment Service**: Handles payment processing and transactions.
5. **Notification Service**: Sends notifications to users via email and SMS.

## Getting Started

### Prerequisites

- **Node.js** and **npm** installed on your machine.
- **MongoDB** instance running locally or on a cloud service.
- **Docker** and **Kubernetes** for containerization and orchestration.
- **RabbitMQ** instance for messaging.
- **Cloudinary** account for image and video management.

### Installation

1. **Clone the Repository**:

   ```sh
   git clone https://github.com/saurabhbhaskar/ecom_backend.git
   cd ecom_backend
