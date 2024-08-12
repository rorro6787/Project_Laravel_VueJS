# FullStack Project with Laravel & VueJS
<p align="center"><a href="https://vuejs.org" target="_blank" rel="noopener noreferrer"><img width="200" src="https://vuejs.org/images/logo.png" alt="Vue logo"></a></p>

This repository contains code and resources for a Full Stack web application built with Laravel on the backend and Vue.js on the frontend. The project includes user authentication, CRUD operations, and a RESTful API for seamless interaction between the frontend and backend.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction
The goal of this project is to create a Full Stack web application that demonstrates modern web development practices. It is designed to serve as a boilerplate for developers looking to create similar projects with Laravel and Vue.js. The application includes user authentication, API integration, and dynamic frontend rendering using Vue.js

## Features

- **User Authentication**: Register, login, and manage user sessions.
- **CRUD Operations**: Create, read, update, and delete records from the database.
- **RESTful API**: A well-structured API for seamless communication between the frontend and backend.
- **Vue.js Integration**: Dynamic and responsive frontend powered by Vue.js.
- **Modular Architecture**: Clean and maintainable code with a modular structure.

## Requirements
- PHP 8.x
- Composer
- Node.js & npm
- MySQL or any other supported database

## Installation

1. Clone the repository:
   
    ```sh
    git clone https://github.com/yourusername/repository_name.git
    ```
3. Navigate to the project directory:
   
    ```sh
    cd repository_name
    ```
6. Install backend dependencies using Composer:

   ```sh
    composer install
    ```
   
6. Install frontend dependencies using npm:

   ```sh
    npm install
    ```

6. Set up your .env file by copying .env.example:

   ```sh
    cp .env.example .env
    ```

6. Generate an application key:

   ```sh
    php artisan key:generate
    ```
6. Set up the database and run migrations:

   ```sh
    php artisan migrate
    ```
6. (Optional) Seed the database with sample data:

   ```sh
    php artisan db:seed
    ```
6. Build the frontend assets:

   ```sh
    npm run dev
    ```
6. Start the local development server:

   ```sh
    php artisan serve
    ```

## Usage
Once the application is installed, you can access it via http://localhost:8000. You can start using the application by registering a new account or logging in with existing credentials. The frontend is dynamically rendered using Vue.js, and all interactions with the backend are handled via the RESTful API.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## Acknowledgements
Inspired by various tutorials and Antonio Sarosi's Mastermind course.
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="700" alt="Laravel Logo"></a></p>





















