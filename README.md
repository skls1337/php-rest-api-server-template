# php-rest-api-server-template

## Overview

PHP REST API template

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
    └── README.md


## Install
Run ```composer install```

## Start server
Run ```php -S 127.0.0.1:8000 -t public``` to run server on localhost
