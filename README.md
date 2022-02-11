# OXID Academy Product Counter Service
**This Package is part of the OXID Academy Development Basic Training.**

## Installation
```
composer require oxid-academy/product-counter-service
```

## Description
This OXID eShop Component counts all available products in the currently active shop.

## Example
```php
/** @var Counter $counter */
$container = ContainerFactory::getInstance()->getContainer();
$counter = $container->get(OxidAcademy\ProductCounterService\Counter::class);

var_dump($counter->count());
```
