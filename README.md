
## About

CRUD API, base template with the following endpoints:

GET /api/students will return all students and will be accepting GET requests.

GET /api/students/{id} will return a student record by referencing its id and will be accepting GET requests.

POST /api/students will create a new student record and will be accepting POST requests.

PUT /api/students/{id} will update an existing student record by referencing its id and will be accepting PUT requests.

DELETE /api/students/{id} will delete a student record by referencing its id and will be accepting DELETE requests.


$ cd api-project
Next, start up the Laravel server if it’s not already running:

$ php artisan serve
You will be able to visit your application on https://localhost:8000.



## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.


## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
