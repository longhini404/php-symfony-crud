# PHP Symfony CRUD

## Setup

- PHP 7.4+
- Symfony CLI
- Composer

## Installation

### Clone the Repository

- git clone https://github.com/longhini404/php-symfony-crud
- cd your-project

### Composer Dependencies

- composer install

### Database Setup

- php bin/console doctrine:database:create
- php bin/console doctrine:migrations:migrate

## Running Symfony Server

- symfony server:start

---

http://localhost:8000

Routes Created:
- GET /albums - Lists all albums
- GET /albums/new - Form to create a new album
- POST /albums/new - Saves a new album
- GET /albums/{id} - Displays details of a specific album
- GET /albums/{id}/edit - Form to edit an album
- POST /albums/{id}/edit - Updates an existing album
- DELETE /albums/{id} - Deletes an album