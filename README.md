# Assignment-7

**All codes needed for this assignment** 

- composer create-project laravel/laravel Assignment - 7
- php artisan make:controller UserController
- In UserController.php I have made the following function :
    > public function index() 
    > {
    >   return 'Hello, Laravel!';
    > }
- I have made a route in web.php
    > Route::get('/hello', [UserController::class, 'index'])->name('hello');
- php artisan serve

