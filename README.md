# DHL BusinessCustomerShipping API SDK

This *unofficial* library is wrapping some functions of the DHL SOAP *(v1.1 compatible)* API in order to easy create/delete shipments and labels.

## Requirements

- You need a [DHL developer Account](https://entwickler.dhl.de) and - as long as you want to use the API in production systems - a DHL Intraship Account.
- PHP-Version 7.2 or higher _(It may work on older Versions, but we don't offer Support for these)_
- PHP-SOAP-Client installed + enabled on your Server. [More information on php.net](http://php.net/manual/en/soap.setup.php)

## Installation

### Composer

You can use [Composer](https://getcomposer.org) to install the package to your project:

```
composer require octlabs/dhl-php-sdk
```

The classes are then added to the autoloader automatically.

### Without Composer

If you can't use Composer (or don't want to), you can also use this SDK without it.

To initial this SDK, just require the [_nonComposerLoader.php](https://github.com/octlabs/dhl-php-sdk/blob/master/includes/_nonComposerLoader.php)-File from the `/includes/` directory.

```php
require_once(__DIR__ . '/includes/_nonComposerLoader.php');
```

## Compatibility

This Project is written for the DHL-SOAP-API **Version 2 or higher**.

## Usage / Getting started

- [Getting started (Just a quick guide how you have to use it)](https://github.com/octlabs/dhl-php-sdk/blob/master/examples/getting-started.md)
- _More examples some day?_

## Code Documentation

You find Code-Examples with explanations in the `examples` Directory. I also explain how it works.
There is also a lot of old stuff in the Documentation, so that you can not sure if it is right...

## Credits

All these Persons helped to create this SDK for the DHL-API:
- [Petschko](https://github.com/Petschko) - Initially created this Project and decided to share it for free
- [cedricziel](https://github.com/cedricziel) - For turning this Project into a [Composer](https://getcomposer.org)
- [tobias-redmann](https://github.com/tobias-redmann) - For the `setFullStreet` method and the PHP-DHL-Example-Project for Version 1
- [nastymadecode](https://github.com/nastymadecode)
- [aschempp](https://github.com/aschempp) - For the help with the Notification E-Mail
- [Dakror](https://github.com/Dakror) - For the `ProductInfo`-Class
- [dasistdaniel](https://github.com/dasistdaniel)
- [klimser](https://github.com/klimser)
- [octlabs](https://github.com/octlabs) - For adding some missing Documentation
- [derslo](https://github.com/derslo) - For adding a minimal PHPUnit Testsuite

And special thanks to the helpers within the background:
- [OliverTempel](https://github.com/OliverTempel) - For adding label-types in Version 3
- [Tune389](https://github.com/Tune389) - For fixing the `updateShipmentOrder` for Version 2

## Contact

- You can Report Bugs here in the "[Issue](https://github.com/octlabs/dhl-php-sdk/issues)"-Section of the Project.
	- Of course you can also ask any stuff there, feel free for that!
	- If you want to use German, you can do it. Please keep in mind that not everybody can speak German, so it's better to use english =)
