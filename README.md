# Falcon Airlines Booking System

A terminal-based airline booking system built with Python and MySQL. This project allows users to book flights, view their reservations, and cancel bookings. It includes basic data setup with sample airports and flight schedules.

## Features

- Book a flight by entering passenger information
- View existing bookings using email
- Cancel a reservation by booking ID
- Automatically creates tables and populates sample data on first run
- Simple terminal interface for demonstration and learning purposes

## Technologies Used

- Python 3.x
- MySQL
- PyMySQL library

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/falcon-airlines-booking.git
cd falcon-airlines-booking
```

### 2. Install Dependencies
```bash
pip install pymysql
```
### 3. Create a MySQL Database
```bash
create database falcon_airlines;
```

### 4. Configure Database Credentials
```bash
def createConnection():
    return pymysql.connect(
        host="localhost",
        port=3306,
        user="your_mysql_username",
        password="your_mysql_password",
        database="falcon_airlines"
    )
```

### 5. Run the Application
