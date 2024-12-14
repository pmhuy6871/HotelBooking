# Online Hotel Reservation System

A simple and easy-to-use **Online Hotel Reservation System** built with **PHP** and **MySQLi**. This system allows users to book hotel rooms, manage reservations, and make payments online.

## Features

- **User Side**:
  - Browse available hotel rooms.
  - Search rooms based on date and number of guests.
  - User registration and login.
  - Make hotel reservations online.
  - View reservation history.

- **Admin Side**:
  - Manage room availability.
  - View and manage bookings.
  - Manage room categories and pricing.

## Technologies Used

- **PHP**: Backend scripting language.
- **MySQLi**: Database management system.
- **HTML/CSS/JavaScript**: Frontend development.

## Installation

### Prerequisites

- A web server like **Apache** or **Nginx**.
- PHP installed (preferably version 7.0 or higher).
- MySQL server for the database.

### Steps to Install

1. **Download the source code**:
   - Download the code from this repository or clone it using Git.
   - If you prefer to clone it, run the following command:
     ```bash
     git clone https://github.com/yourusername/repositoryname.git
     ```

2. **Set up the database**:
   - Create a MySQL database for the hotel reservation system.
   - Import the SQL file located in the `database` folder (or included in the documentation) to create the necessary tables.

3. **Configure Database Connection**:
   - In the `config.php` file, update the database credentials:
     ```php
     define('DB_SERVER', 'localhost');
     define('DB_USERNAME', 'your_db_username');
     define('DB_PASSWORD', 'your_db_password');
     define('DB_DATABASE', 'your_db_name');
     ```

4. **Run the Application**:
   - Upload the project to your server, and navigate to the website in your browser (e.g., `http://localhost/your-project-folder`).
   - You should now see the online hotel reservation system.

## Usage

### For Users:
1. Create an account or log in to make reservations.
2. Browse available rooms and make your booking by entering the required details.
3. Review your booking history from your account.

### For Admin:
1. Log in to the admin panel.
2. Manage rooms, bookings, and users.
3. Adjust pricing and room availability as needed.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-xyz`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-xyz`).
5. Create a new Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- The system is built using PHP and MySQLi, with simple yet powerful design principles.
- Inspired by various hotel reservation platforms available online.

---

For any issues or questions, feel free to open an issue on the GitHub repository.
