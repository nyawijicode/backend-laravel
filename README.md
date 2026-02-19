# backend-laravel

spatie/laravel-permission
spatie/laravel-medialibrary
spatie/laravel-query-builder
spatie/laravel-activitylog
laravel/sanctum
laravel/passport --dev
barryvdh/laravel-debugbar
laravel/telescope
intervention/image
maatwebsite/excel
barryvdh/laravel-dompdf
pusher/pusher-php-server

php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"
php artisan vendor:publish --provider="Spatie\MediaLibrary\MediaLibraryServiceProvider" --tag="medialibrary-migrations"
php artisan vendor:publish --provider="Spatie\MediaLibrary\MediaLibraryServiceProvider" --tag="medialibrary-config"
php artisan vendor:publish --provider="Spatie\MediaLibrary\MediaLibraryServiceProvider"
php artisan vendor:publish --provider="Spatie\Activitylog\ActivitylogServiceProvider" --tag="activitylog-config"
php artisan vendor:publish --provider="Spatie\Activitylog\ActivitylogServiceProvider" --tag="activitylog-migrations"
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
php artisan vendor:publish --provider="Laravel\Passport\PassportServiceProvider"
php artisan vendor:publish --provider="Barryvdh\Debugbar\ServiceProvider"
php artisan vendor:publish --provider="Intervention\Image\ImageServiceProviderLaravelRecent"
php artisan vendor:publish --provider="Maatwebsite\Excel\ExcelServiceProvider"
php artisan vendor:publish --provider="Barryvdh\DomPDF\ServiceProvider"
php artisan telescope:install
php artisan vendor:publish --tag=telescope-config
php artisan passport:install
php artisan migrate
