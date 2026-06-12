Social App

A lightweight social app built with React Native and PHP.

Stack


Backend: PHP 8.3
Frontend: React Native
Database: MySQL
Authentication: JWT (Bearer Token)


Project Structure

/
  bootstrap.php
  composer.json
  /config
    .env
  /Api
    /auth
      register.php
      login.php
    /middleware
      TokenManager.php
    /posts
      index.php
      create.php
      update.php
      delete.php
  /Infrastructure
    /Persistence
      DbConnector.php
    /Repository
      UserRepository.php
      PostRepository.php

Installation


Clone the repository
Run composer install
Create /config/.env with your credentials
Import the database schema
Start your local server


Author

Elio Casciola
