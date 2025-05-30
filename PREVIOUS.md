### Laravel version <= 9

```bash
$ composer require circuitix/laravel-invoices:^3.3
```

### Laravel version <= 8

```bash
$ composer require circuitix/laravel-invoices:^2.0
```

### Laravel version <= 7

```bash
$ composer require circuitix/laravel-invoices:^1.3
```

### If you're using Laravel version < 5.5

If you don't use auto-discovery, add the ServiceProvider to the providers array in `config/app.php`

```php
Circuitix\Invoices\InvoiceServiceProvider::class,
```

If you want to use the facade to generate invoices, add this to your facades in `config/app.php`

```php
'Invoice' => Circuitix\Invoices\Facades\Invoice::class
```
