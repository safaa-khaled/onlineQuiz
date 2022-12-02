<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>


## About Online Quiz

online quiz website is built using laravel framework, it is a test of 10 questions which are randomely chosed from questions bank.  the website contain two roles admin and student.
admin can add new student, show all student, and show the students' results, add question and question options.
student can login to do the quiz or show his result.


to run online quiz website on your machine:
- download repository zip file to your machine and extract it.
- create database.
- copy .env file and change database configuration with your database info.
- in terminal or cmd run this instructions:
    - composer update
    - php artisan key:generate
    - php artisan migrate
    - php artisan db:seed
    - php artisan serve
- login using admin@admin.com


