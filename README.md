# php-rest-api-server-template

## Overview

PHP REST API template with a MySQL database connection

### Project layout

    .
    ├── public                  # Public files
        ├── index.php           # File to serve the controller and process the requests
    ├── src                     # Source files
        ├── Controller          # Controllers folder
        ├── System              # Database connection
        ├── TableGateways       # Gateway folder to define classes for database tables
    ├── bootstrap.php           # Load environment variables
    ├── LICENSE
    ├── README.md
    └── dbseed.php              # Seed database with dummy data
    


## Install
Run ```composer install```

## Start server
Run ```php -S 127.0.0.1:8000 -t public``` to run server on localhost

## Seed database
Run ```php dbseed.php```

### Create .env file with the following database configuration
```
DB_HOST=db_host
DB_PORT=db_port
DB_DATABASE=db_name
DB_USERNAME=db_username
DB_PASSWORD=db_password
```
