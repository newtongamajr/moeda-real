# Campo de Moeda Real para laravel Nova

Mask field for brazilian currency

### Install

Run this command into your nova project:

`composer require newtongamajr/moeda-real`

### Add it to your Nova Resource:

```php
use Galileo\MoedaReal\MoedaReal;

MoedaReal::make('Valor Total', 'valor_total'),
```
