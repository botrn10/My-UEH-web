# Introduction

This project is a group assignment developed for the university course Web Application Development. The application is built using Laravel 10 and follows a RESTful API architecture, focusing on user management and product management features.

The project aims to demonstrate fundamental backend web development skills, including API design, database interaction, and framework-based development using Laravel.

# Technologies Used

* Laravel Framework 10.x
* PHP >= 8.1
* MySQL
* Laravel Sanctum
* Spatie Laravel Permission
* Chatify
* Pusher
* Laravel Shopping Cart
* Toastr

# Installation

## Step 1: Clone the repository

```bash
git clone <repository_url>
cd <project_name>
```

## Step 2: Install dependencies

```bash
composer install
```

## Step 3: Environment configuration

Create a `.env` file from the example:

```bash
cp .env.example .env
```

Update database configuration in the `.env` file:

```env
APP_NAME=Laravel
APP_ENV=local
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database
DB_USERNAME=root
DB_PASSWORD=
```

## Step 4: Generate application key

```bash
php artisan key:generate
```

## Step 5: Run database migrations

```bash
php artisan migrate
```

## Step 6: Start the development server

```bash
php artisan serve
```

# Main Features

## User Management

* User registration and login
* View user list and user details
* Update user information

## Product Management

* Create new products
* Update existing products
* Delete products
* View product list

# Sample API Endpoints

```http
POST    /login
POST    /register
GET     /users
POST    /products
PUT     /products/{id}
DELETE  /products/{id}
```
