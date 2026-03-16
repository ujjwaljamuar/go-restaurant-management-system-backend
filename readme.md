# Restaurant Management System

A RESTful API built with Go for managing restaurant operations including food items, menus, orders, tables, users, and invoices.

## Features

- **User Management**: Handle user registration, authentication, and profiles.
- **Menu Management**: Create and manage food items and menus.
- **Order Management**: Process orders and order items.
- **Table Management**: Manage restaurant tables.
- **Invoice Management**: Generate and manage invoices.
- **Authentication**: JWT-based authentication middleware.

## Prerequisites

- Go 1.25.0 or later
- MongoDB database

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/restaurant-management-system.git
   cd restaurant-management-system
   ```

2. Install dependencies:
   ```
   go mod download
   ```

3. Set up your MongoDB connection in the database configuration.

## Usage

1. Run the application:
   ```
   go run main.go
   ```

2. The server will start on `http://localhost:8080` (or your configured port).

## API Endpoints

- `GET /users` - Get all users
- `POST /users` - Create a new user
- `GET /menu` - Get menu items
- `POST /orders` - Create an order
- And more... (Refer to routes for full list)

## Contributing

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push to the branch.
5. Open a Pull Request.

## License

This project is licensed under the MIT License.