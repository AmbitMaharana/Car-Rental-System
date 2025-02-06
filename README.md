# Car Rental System

This is a Car Rental System built using **PHP** for the backend and **MySQL** for database management. The system allows users to rent cars, check availability, and manage rental bookings, while the admin can manage car listings, customer details, and bookings.

## Features

### User Features:
- Browse available cars for rent
- View car details and pricing
- Book a car for a specific duration
- View booking history and status

### Admin Features:
- Add, edit, and delete car listings
- Manage customer bookings
- View all rental transactions

## Technologies Used
- **PHP**: Backend logic
- **MySQL**: Database management
- **HTML/CSS/JavaScript**: Frontend for user interface
- **Bootstrap**: For responsive UI design

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/car-rental-system.git

2. **Set up the database**:

- Create a MySQL database.
- Import the database.
- sql file into your MySQL server to set up the tables.
- Edit the config.php file to configure your MySQL connection.
- Example of config.php:
  ```bash
  <?php
  $host = 'localhost';
  $user = 'root';
  $password = '';
  $dbname = 'car_rental';
  
  $conn = new mysqli($host, $user, $password, $dbname);
  
  if ($conn->connect_error) {
      die("Connection failed: " . $conn->connect_error);
  }
  ?>
  ```
3. **Running the project**:

- Upload the project to your PHP-enabled server (or run it locally using XAMPP/WAMP).
- Open the index.php in your browser to start using the system.

## Usage

1. **User Mode**:
- Register/login to rent cars.
- Choose a car, view details, and proceed to checkout.
  
2. **Admin Mode**:
- Admin can log in to manage cars and bookings.
- Add/edit/delete car listings and manage rental transactions.



