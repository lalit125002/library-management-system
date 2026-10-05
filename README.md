# Online Library Management System

A PHP and MySQL web application for managing a library. It includes a student-facing portal and an admin panel for managing books, authors, categories, students, and issued books.

## Requirements
- PHP (with MySQLi enabled)
- MySQL or MariaDB
- Apache web server (XAMPP, WAMP, or similar)
- phpMyAdmin (optional, for importing the database)

## Setup
1. Install and start Apache and MySQL.
2. Copy this repository folder into your web server's document root (for example, `htdocs` in XAMPP).
3. Create a MySQL database named `library`.
4. Import `database/library.sql` into that database using phpMyAdmin or the MySQL command line.
5. Open `includes/config.php` and `admin/includes/config.php`. Update the database host, username, password, and database name to match your local setup.
6. Visit `http://localhost/library/` (adjust the URL if you renamed the folder).

## Application areas
- Student portal: `/`
- Admin panel: `/admin/`

## Demo credentials
The original project notes list these demo credentials:
- Student: `test@gmail.com` / `Test@123`
- Admin: `admin` / `Test@123`

These are provided for local evaluation only. Change/remove demo accounts and use secure credentials before deploying publicly.

## Repository structure
- `admin/` — administration pages and assets
- `assets/` — student portal styles, scripts, fonts, and images
- `includes/` — shared PHP configuration and layout files
- `database/library.sql` — database schema and seed data

## Notes
This repository is packaged from the supplied project archive. Review the PHP configuration and SQL seed data before deployment. Do not publish real credentials or sensitive production data.
