# Basic POS System

A CodeIgniter 4 Point-of-Sale system with products, customers, staff, sales recording and sales history.

## Pages

- `/`
- `/login`
- `/sales`
- `/products`
- `/customers`
- `/users`

## Run with XAMPP

1. Place the `midterm_prac` folder in `C:\xampp\htdocs`.
2. Start Apache & MySQL in XAMPP.
3. Open `http://localhost/phpmyadmin` then import midterm_prac.sql from folder directory.
4. Then go to the config file (php.ini) under Apache and change this line from `;extension=gd` to `extension=gd`.
5. Open `http://localhost/midterm_prac/public/`.

Login creds: `admin` / `password123`

PHP 8.2 or newer is required.

10/10/26 - Login/Logon functionality added
10/21/26 - Products, sales, login with hashed passwords, and image uploads were added in this activity.