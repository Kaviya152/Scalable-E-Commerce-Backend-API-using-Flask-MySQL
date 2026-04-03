# Flask Python API

## Overview
This project is a scalable, efficient Flask-based API designed to manage customers, products, and orders. The application utilizes a layered architecture, leveraging Flask blueprints for organized route management and structured service layers for business logic. The API supports full CRUD operations for customers, products, and orders, and includes a health check endpoint to ensure the service remains operational.

## Features
- **Customers**: Create, update, retrieve, and delete customer records.
- **Products**: Add, modify, fetch, and delete products.
- **Orders**: Place and fetch customer orders, with transaction management.
- **Health Check**: Ensure API uptime and service availability.
- **Layered Architecture**: Separation of concerns through services and route handlers.
- **Flask Blueprints**: Modular routing for scalable API design.

## Technologies Used
- **Flask**: Web framework for building the API.
- **MySQL**: Database for persisting customer, product, and order information.
- **SQLAlchemy**: ORM for database interaction (if applicable).
- **Postman**: API documentation and testing.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/gayanukabulegoda/Flask-Python-API.git

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

3. **Set Up the Database**
   - Create a MySQL database and configure the database URI in the `config.py` file.

4. **Run the Application**
   ```bash
   flask run

5. **Access the API** 
   - The API will be accessible at `http://127.0.0.1:5001/`.

## API Documentation
The full API documentation is available on Postman. It provides a detailed overview of all available endpoints, request formats, and response examples.

- **Postman Documentation**: [Flask Python API Documentation](https://documenter.getpostman.com/view/36681432/2sAXqqchr4)

