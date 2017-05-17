# BlueHornet

A PHP package for working w/ the BlueHornet API.

## Install

Normal install via Composer.

## Usage

```php
use Travis\BlueHornet;

$key = 'yourapikey';
$secret = 'yourapisecret';
$response = BlueHornet::run($key, $secret, 'legacy.retrieve_active', [
	'return_count' => 1,
]);
```

Call the ``run()`` method and pass the api key, the api secret, the method name, and an array of arguments.