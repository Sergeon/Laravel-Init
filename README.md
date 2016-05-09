# Laravel-Init
Blueprint for laravel with some basic folders, files and gulp task built-in

##use

jQuery and Bootstrap are built-in, with some scss files under `resources/assets/sass`. Use `resources/assets/sass/app.scss` to import scss files. 

###Initialization

In the / of the app:

``` npm install ```

To watch changes within .scss and .js files, just:
``` gulp watch ``` 

(use flag `--production` to minify assets)

This project, as Laravel 5.2 by default, uses [Elixir](https://github.com/laravel/elixir) around Gulp for the task runner. Just check the documentacion if you want to use perform more tasks. 


###structure:

Assets served are versioned and live under `public/build/assets`, (just see `resources/views/partials/head.blade.php` to see how to call versioned files with the Elixir Laravel package) while source files are under `resources/assets/scss` and `resources/assets/js`. 


A simple layout structure over [Blade PHP]https://laravel.com/docs/5.1/blade is provided, just check `resources/vies/pages`,`resources/vies/partials` and `resources/vies/layouts`.    
