<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# Laravel Starter Kit 

This project serves as a starter kit for Laravel applications, providing a skeleton structure with essential packages and configurations to kickstart your development process.

## Dependencies

The project relies on the following dependencies:

- **laravel/breeze**: A minimalistic authentication system for Laravel.
- **laravel/pulse**: A performance monitoring tool for Laravel applications (beta version).
- **spatie/laravel-backup**: A package to backup your Laravel app.
- **spatie/laravel-login-link**: Generate temporary signed URLs to login without a password.
- **spatie/laravel-sitemap**: Generate sitemaps dynamically.
- **fakerphp/faker**: A library for generating fake data.
- **laravel/pint**: A package to manage your database migrations efficiently.
- **laravel/sail**: Docker development environment for Laravel.
- **laravel/telescope**: An elegant debug assistant for Laravel.
- **mockery/mockery**: A simple yet flexible PHP mock object framework.
- **nunomaduro/collision**: Error handling for console/command-line PHP applications.
- **nunomaduro/larastan**: A PHPStan wrapper for Laravel applications.
- **pestphp/pest**: Elegant testing framework for PHP.
- **pestphp/pest-plugin-laravel**: Laravel plugin for Pest.
- **spatie/laravel-ignition**: A powerful error page for Laravel.

## Setup Instructions

Follow these steps to set up the Laravel Starter Kit on your local machine:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vcjpierre/laravel-starter-kit.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd laravel-starter-kit
   ```

3. **Install Composer dependencies**:
   ```bash
   composer install
   ```

4. **Install NPM dependencies**:
   ```bash
   npm install && npm run dev
   ```

5. **Configure Environment**:
   - Create a copy of the `.env.example` file and name it `.env`.
   - Generate an application key:
     ```bash
     php artisan key:generate
     ```

6. **Set up the Database**:
   - Ensure your database credentials are correctly set in the `.env` file.
   - Create and migrate the database:
     ```bash
     php artisan migrate
     ```

7. **Run the Development Server**:
   ```bash
   php artisan serve
   ```

8. **Access the Application**:
   Open your web browser and navigate to `http://localhost:8000` to access the Laravel Starter Kit.

## Additional Notes

- Explore the `routes`, `app`, and `resources` directories to understand the project structure.
- Refer to Laravel documentation for detailed information on using specific features and packages.

Happy coding with Laravel! 🚀
