# Vehicle Parking System

A web-based Vehicle Parking System built using JavaScript, PHP, MySQL, and XAMPP. This application provides an efficient solution for managing vehicle parking spaces, tracking vehicle entry and exit, and generating reports.

## Features

- User authentication (Admin and Staff roles)
- Vehicle check-in and check-out functionality
- Real-time availability of parking slots
- Parking fee calculation based on vehicle type and duration
- Dashboard for managing vehicles and parking slots
- Reports for parking usage and revenue

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Development Environment**: XAMPP

## Installation

Follow these steps to set up the application on your local machine:

### Prerequisites

- Install [XAMPP](https://www.apachefriends.org/) on your system.
- Ensure a web browser is installed.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/vehicle-parking-system.git
   ```
2. Move the project files to the `htdocs` directory in your XAMPP installation:
   ```bash
   mv vehicle-parking-system /path-to-xampp/htdocs/
   ```
3. Import the database:
   - Open [phpMyAdmin](http://localhost/phpmyadmin/).
   - Create a new database named `vehicle_parking`.
   - Import the `vehicle_parking.sql` file from the `database` folder of the project.

4. Configure the database connection:
   - Open `config.php` in the project directory.
   - Update the following variables with your database details:
     ```php
     $host = 'localhost';
     $user = 'root';
     $password = '';
     $database = 'vehicle_parking';
     ```

5. Start the XAMPP server:
   - Launch XAMPP Control Panel.
   - Start the Apache and MySQL modules.

6. Access the application:
   - Open a browser and go to [http://localhost/vehicle-parking-system](http://localhost/vehicle-parking-system).

## Screenshots

### Dashboard
![Dashboard Screenshot](screenshots/dashboard.png)

### Vehicle Check-in
![Vehicle Check-in Screenshot](screenshots/checkin.png)

## Folder Structure

```plaintext
vehicle-parking-system/
├── css/             # Stylesheets
├── js/              # JavaScript files
├── images/          # Images and icons
├── database/        # Database export (vehicle_parking.sql)
├── includes/        # Reusable PHP components
├── config.php       # Database connection file
├── index.php        # Main entry point
└── README.md        # Documentation
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any questions or feedback, please contact:

- **Name**: Ithayaraj Inpalagan
- **Email**: ithayarajim15@gmail.com
- **GitHub**: [[your-username](https://github.com/your-username)](https://github.com/Ithayaraj)

Login ID

- username : admin
- password : Group02fots
