<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About

A basic template which have been installed with:
- User Authentication
- User Role Access Permission (Spatie)
- Activity log (Spatie)

The system is built with:
- Laravel 12
- PHP 8.2.12
- Node 20.18.1
- Bootstrap 5.2.0
- Composer 2.8.9

## Using the template

For the owner, please go to your GitHub and navigate to this repository. Then click "Use as Template" and enter the repo name.

For other than owner, please use fork.

## Installation

1. After pull the code from git, open terminal and run "composer install" to install all the dependencies
2. Run "npm install" to install all packages
3. Then run "cp .env.example .env"
4. In .env file, edit DB_DATABASE= to your local database name
5. Run "php artisan key:generate" to generate laravel application key
6. Open mysql phpmyadmin, create database. Make sure the name is same with you have declare in .env.
7. Run "php artisan migrate" and "php artisan db:seed"
8. After done import, run "php artisan serve"
9. You can access the local system by using link http://localhost/app_name


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
