# alx_travel_app

## Overview

**alx_travel_app** is a Django RESTful API for managing travel listings and bookings. It provides endpoints for creating, reading, updating, and deleting listings and bookings, and includes interactive API documentation with Swagger.

## Features

- CRUD operations for Listings and Bookings
- RESTful API endpoints
- Swagger (OpenAPI) documentation
- Django REST Framework powered

## Setup

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd alx_travel_app_0x01
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

4. **Run the development server**
   ```bash
   python manage.py runserver
   ```

## API Endpoints

| Endpoint           | Methods        | Description                |
|--------------------|---------------|----------------------------|
| `/listings/`       | GET, POST      | List or create listings    |
| `/listings/{id}/`  | GET, PUT, DELETE | Retrieve, update, delete a listing |
| `/bookings/`       | GET, POST      | List or create bookings    |
| `/bookings/{id}/`  | GET, PUT, DELETE | Retrieve, update, delete a booking |

## API Documentation

Visit [http://localhost:8000/swagger/](http://localhost:8000/swagger/) for interactive Swagger docs.

## Testing

You can test the API endpoints using [Postman](https://www.postman.com/) or `curl`.

## License

This project is for educational purposes.