# Laravel Multirole Application

This is a simple Laravel application that demonstrates how to implement a multi-role system with ACL permissions. The application allows you to manage users, roles, and products. The admin user has full access to all features, while the other users have limited access based on their roles and permissions.

## Prerequisites

- PHP (>= 7.4)
- Composer
- Laravel Framework (>= 8.x)
- MySQL or any other supported database

## Installation

1. Clone the repository or download the source code.

2. Open a terminal or command prompt and navigate to the project directory.

3. Install the project dependencies by running the following command:

```bash
composer install
```

1. Create a new MySQL database for the application.

2. Rename the `.env.example` file to `.env` and update the database configuration values with your database credentials.

3. Generate a new application key by running the following command:
```
php artisan key:generate
```
1. Run the database migrations and seeders to set up the initial database structure and data:

```
php artisan migrate --seed
```

1. Start the development server by running the following command:

```
php artisan serve
```

1. Access the application in your web browser at `http://localhost:8000/`.

## Usage

- Use the following credentials to log in as the admin user:

Email: admin@gmail.com
Password: 123456

- The application allows you to manage users, roles, and products. The admin user has full access to all features.

- After logging in, you can perform the following actions:

- Users:
   - View a list of users.
   - Create a new user.
   - Edit an existing user.
   - Delete a user.

- Roles:
   - View a list of roles.
   - Create a new role.
   - Edit an existing role.
   - Delete a role.

- Products:
   - View a list of products.
   - Create a new product.
   - Edit an existing product.
   - Delete a product.

- The ACL permissions are pre-defined with the following actions:

- Role Permissions:
   - role-list
   - role-create
   - role-edit
   - role-delete

- Product Permissions:
     - product-list
     - product-create
     - product-edit
     - product-delete

- You can modify the permissions and add more as per your requirements by editing the seeders or using the application's interface.

## Contributing

Feel free to contribute to this project by creating issues or submitting pull requests. Any improvements or bug fixes are welcome.

## License and Author

**Author**: [Hugo 'Svartorm' FRANGIAMONE](http://svartorm.me).
</br>
This project is licensed under the [MIT License](LICENSE).
