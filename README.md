## Installation and Usage Guide
Follow these steps to set up the Laravel Inventory project on your local machine:

**Requirements:**
Composer, PHP version >5 and <8.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/naufalrandika/ERPLaravel.git

2. **Navigate to the Project Directory:**
   ```bash
   cd ERPLaravel

3. **Copy .env:**
   ```bash
   cp .env.example .env

4. **Install Dependencies:**
   ```bash
   composer install

5. **Make Database:**
   Open on browser ***https://localhost/phpmyadmin***
   , Create New Database dan Name it
   ```laravel
   laravel

6. **Run Migrations:**
   ```bash
   php artisan migrate:fresh

7. **Seed the Database:**
   ```bash
   php artisan db:seed

8. **Generate Application Key:**
   ```bash
   php artisan key:generate

9. **Start the Development Server:**
   ```bash
   php artisan serve
