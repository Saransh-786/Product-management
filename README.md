Product Management Backend System

OVERVIEW

This is a Product Management System built using Golang with a RESTful API, integrated with PostgreSQL for data storage and Redis for caching. The system allows users to perform basic CRUD operations (Create, Read, Update, Delete) on products, providing endpoints to add products, retrieve product details, and list all products.

FEATURES

Create Products: Add a new product with details such as name, description, price, and images.

List Products: Retrieve a list of all products.

Get Product by ID: Fetch details of a specific product by its ID.

Structured Logging: Logs API requests and responses for better monitoring.

PostgreSQL Integration: Store product data in a relational database.

Redis Caching (Optional): Implement caching for faster access to frequently requested data.

TECH STACK

1- Language: Golang (Go)

2- Database: PostgreSQL (for data storage)

3- ORM: GORM (for database interaction)

4- Cache: Redis (optional, for caching data)

5- Logging: Logrus (structured logging)

6- API Framework: Gin (for building RESTful APIs)

PROJECT STRUCTURE

product-management-backend/

│

├── config/                # Database and environment configurations

│   └── database.go        # PostgreSQL connection and setup

│

├── controllers/           # API request handlers

│   └── product_handlers.go # Handlers for managing products (Create, Get, List)

│

├── models/                # Data models for the application

│   ├── product.go         # Product model

│   └── user.go            # User model

│

├── utils/                 # Utility functions (e.g., logging setup)

│   └── logger.go

│

├── main.go                # Entry point for the Go application

│

└── README.md              # Project documentation

SETUP

Prerequisites

        Go installed

        PostgreSQL installed

