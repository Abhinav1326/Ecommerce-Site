# Ecommerce Site

This is an Ecommerce site built using PHP for the backend and Apache MySQL server for the database.

## Features

- User registration and authentication
- Product listing and search
- Shopping cart functionality
- Order management
- Payment integration

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Abhinav1326/Ecommerce-Site.git
    ```

2. Install dependencies:

    ```bash
    composer install
    ```

3. Configure the database connection in the `.env` file:

    ```dotenv
    DB_HOST=localhost
    DB_PORT=3306
    DB_DATABASE=ecommerceadvlara
    DB_USERNAME=root
    DB_PASSWORD=
    ```

4. Run database migrations:

    ```bash
    php artisan migrate
    ```

5. Start the development server:

    ```bash
    php artisan serve
    ```

6. Open the site in your browser:

    ```plaintext
    http://localhost:8000
    ```

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please open an issue or submit a pull request.
