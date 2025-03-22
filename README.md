# GRE Champs Sport Competition Platform

A comprehensive platform for managing sports competitions and championships.

## Overview

GRE Champs is a web-based application designed to streamline the management of sports competitions. It provides tools for organizers to create and manage tournaments, track participants, schedule matches, and publish results.

## Features

- **Competition Management**: Create, edit, and manage multiple sports competitions
- **Participant Registration**: Easy registration process for teams and individual athletes
- **Tournament Scheduling**: Automated or manual scheduling of matches and events
- **Real-time Results**: Live updating of scores and standings
- **User Roles**: Different access levels for administrators, organizers, and participants
- **Reporting**: Generate comprehensive reports and statistics

## Technology Stack

- **Backend**: Laravel PHP Framework
- **Frontend**: Blade templates with JavaScript
- **Database**: MySQL
- **Authentication**: Laravel Sanctum

## Installation

### Prerequisites

- PHP >= 8.0
- Composer
- MySQL
- Node.js and NPM

### Setup Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/gre-champs-sport-competition-platform.git
    cd gre-champs-sport-competition-platform
    ```

2. Install PHP dependencies:

    ```bash
    composer install
    ```

3. Install JavaScript dependencies:

    ```bash
    npm install
    ```

4. Create a copy of the .env file:

    ```bash
    cp .env.example .env
    ```

5. Generate application key:

    ```bash
    php artisan key:generate
    ```

6. Configure your database in the .env file:

    ```
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=gre_champs
    DB_USERNAME=root
    DB_PASSWORD=
    ```

7. Run database migrations:

    ```bash
    php artisan migrate
    ```

8. Seed the database (optional):

    ```bash
    php artisan db:seed
    ```

9. Start the development server:
    ```bash
    composer run dev
    ```

## Usage

After installation, access the application at `http://localhost:8000`. Log in with the default administrator account:

- Email: admin@example.com
- Password: password

(Remember to change these credentials in a production environment)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For questions or support, please contact [admin@akordium.id](mailto:admin@akordium.id).
