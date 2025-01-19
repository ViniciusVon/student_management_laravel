# Student Management System  

A simple Student Management System built with **Laravel 10**, utilizing CRUD principles. This project allows users to manage student records efficiently and includes functionality to generate payment receipts.  

## Features  
- Add, edit, view, and delete student records (CRUD operations).  
- Generate payment receipts for students.  
- User-friendly interface for managing student data.  

## Prerequisites  
- PHP >= 8.1  
- Composer  
- Laravel 10  
- A web server (e.g., Apache or Nginx)  
- MySQL or any other supported database  

## Installation  

1. **Clone the repository**  
   ```bash  
   git clone https://github.com/yourusername/your-repository-name.git  

2. **Navigate to the project directory**
   ```bash
   cd student_management_laravel

3. **Install Dependencies**
   ```bash
   composer install

4. **Set up the environment file**
   ```bash
   cp .env.example .env  

5. **Generate application key**
   ```bash
   php artisan key:generate  

6. **Run database migrations**
   ```bash
   php artisan migrate

7. **Start the development server**
   ```bash
   php artisan serve  

8. **Access the application**
   Open your browser and go to http://127.0.0.1:8000.
