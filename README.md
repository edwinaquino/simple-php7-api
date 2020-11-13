# Simple PHP API

This is a very simple API script to render JSON data from a MySQL database.

## Screenshot
![simple-php-api](https://user-images.githubusercontent.com/30946443/99025384-8cb6c680-251d-11eb-9ee0-7d5c2bc52e67.jpg)

## Getting Started
To get started, clone or download a copy of the repository into your local environment.

### Prerequisites
* PHP Version: 7
* MySQL

## Configuration
Open config.php and provide the following MySQL settings for your environment:
```
"mysql:host=<DB_HOST>:<PORT>;dbname=<DB_NAME>",
'<USER>',
'<DB_PASSWORD>',
```

## Database Migration
Import users.sql into your MySQL database.

## Running the application
Start PHP inside the script directory with the following command:
```
php -S 127.0.0.1:8007
```

## License
This project is licensed under the MIT License.