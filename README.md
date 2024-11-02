**README.txt**

---

**Title**: Practice Exercise - 1% Daily Commitment for Setting Up a Book Review Application Using Laravel 11

**Objective**:
This exercise aims to enhance your practical skills by building a book review application using Laravel 11. The project follows the principle of dedicating at least 1% daily effort to self-improvement and skill development.

**Overview**:
The book review application will allow users to register, log in, add books, write reviews, and view reviews by other users. This practice is designed to deepen your understanding of Laravel's MVC architecture, routing, Eloquent ORM, and essential CRUD operations.

**Features**:
- **User Authentication**: Registration and login system.
- **Book Management**: Users can add books to the catalog.
- **Review System**: Users can write, edit, and delete reviews.
- **Rating**: Optional feature to rate books out of 5 stars.
- **Responsive UI**: Basic front-end for user interaction.

**Prerequisites**:
- PHP 8.2 or later
- Composer
- Laravel 11 installed
- MySQL or a similar database management system

**Installation Steps**:
1. Clone the repository or set up a new Laravel 11 project.
   ```bash
   git clone <repository-link>
   cd book-review-app
   ```

2. Install Laravel dependencies:
   ```bash
   composer install
   ```

3. Copy the `.env` file and configure your database connection:
   ```bash
   cp .env.example .env
   ```

4. Generate an application key:
   ```bash
   php artisan key:generate
   ```

5. Run migrations to set up the database structure:
   ```bash
   php artisan migrate
   ```

6. Start the development server:
   ```bash
   php artisan serve
   ```

**Daily Commitment**:
- Spend 30-60 minutes each day working on this project.
- Break down the tasks into manageable chunks, such as setting up authentication, creating models, and building views.
- Track your progress and reflect on what you've learned after each session.

**Directory Structure**:
- `app/` - Contains the core application files, including models and controllers.
- `resources/views/` - Contains the Blade templates for the UI.
- `routes/web.php` - Defines the routes for the application.
- `public/` - The folder that hosts publicly accessible files.
- `database/` - Includes migration and seed files for database setup.

**Tips for Success**:
- Ensure you understand each feature before moving on to the next.
- Refer to the Laravel 11 documentation for up-to-date information and features.
- Utilize Laravel Mix or Vite for asset compilation if needed for front-end improvements.

**Completion Goal**:
By the end of this exercise, you should have a functional book review application and an enriched understanding of building applications with Laravel 11.

**Happy Coding!**

--- 

Feel free to customize this template according to your needs!
