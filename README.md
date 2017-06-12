Easily tail your logs

You're free to use this package (it's MIT-licensed), but if it makes it to your production environment you are required to send us a postcard from your hometown, mentioning which of our package(s) you are using.

The best postcards will get published on the open source page on our website.
Install

You can install the package via composer:

composer require laraveltoast/laraveltail

You must install this service provider:

// config/app.php

'providers' => [
    ...
    laraveltoast\laraveltail\LaravelTailServiceProvider::class,
    ...
];
