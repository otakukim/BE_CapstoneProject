# University Venue Booking API

This is my backend capstone project for the ALX Software Engineering Program.

## Tech Stack
- Django
- Django REST Framework
- Python


A REST API for managing venue bookings at NUST University.  
Students and staff can view available venues, make bookings, and track their bookings.  
Admins can manage venues and approve or reject bookings.

## Project Structure
- Core project folder: `venue_booking_api`
- App folder: `venue_booking`




## Features

- User registration and authentication (JWT)
- Venue management (CRUD for admins)
- Venue booking system with conflict prevention
- Admin booking approval and rejection
- View user-specific bookings



## Authentication

- Uses **JWT tokens** for authentication
- Obtain token: `POST /api/token/` with `username` and `password`
- Include token in request headers:



