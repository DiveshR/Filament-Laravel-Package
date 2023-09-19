# Laravel 10 with Livewire and Filament 

```php
composer require filament/filament:"^3.0-stable" -W
```

```php
php artisan filament:install --panels
```

# Filament artisan commands

```php

  php artisan filament:assets                       //Set up Filament assets.
  php artisan filament:check-translations           //Check for missing and removed translations
  php artisan filament:install                      //Install Filament.
  php artisan filament:upgrade                      //Upgrade Filament to the latest version

  php artisan make:filament-page                  // Create a new Filament page class and view
  php artisan make:filament-panel                 // Create a new Filament panel
  php artisan make:filament-relation-manager      // Create a new Filament relation manager class for a resource
  php artisan make:filament-resource              // Create a new Filament resource class and default page classes
  php artisan make:filament-theme                 // Create a new Filament panel theme
  php artisan make:filament-user                  // Create a new Filament user
  php artisan make:filament-widget                // Create a new Filament widget class
```

```php
php artisan vendor:publish //complete list of configurations
php artisan vendor:publish --tag=filament-config
```