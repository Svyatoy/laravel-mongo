# laravel-mongo
Convenience library for working with MongoDB documents in Laravel.

## Installation

```php
'mongodb' => [
    'driver'        => 'mongodb',
    'hosts'         => env('DB_HOST', 'localhost:27017'),
    'database'      => env('DB_DATABASE', 'test'),
    'username'      => env('DB_USERNAME', ''),
    'password'      => env('DB_PASSWORD', ''),
    'uriOptions'    => [],
    'driverOptions' => [
        'typeMap' => [
            'root'     => 'array',
            'document' => 'array',
            'array'    => 'array'
        ]
    ]
],
```
