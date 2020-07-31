# Retrieve and parse SendPolicy Framework (SPF) config for email domains

Github CI: 
![Tests](https://github.com/toolstud-io/ts_senderpolicy/workflows/Run%20Tests/badge.svg)
![Psalm](https://github.com/toolstud-io/ts_senderpolicy/workflows/Detect%20Psalm%20warnings/badge.svg)
![Styling](https://github.com/toolstud-io/ts_senderpolicy/workflows/Check%20&%20fix%20styling/badge.svg)

Packagist: 
[![Packagist Version](https://img.shields.io/packagist/v/toolstud-io/ts_senderpolicy.svg?style=flat-square)](https://packagist.org/packages/toolstud-io/ts_senderpolicy)
[![Packagist Downloads](https://img.shields.io/packagist/dt/toolstud-io/ts_senderpolicy.svg?style=flat-square)](https://packagist.org/packages/toolstud-io/ts_senderpolicy)

Retrieve and parse SendPolicy Framework (SPF) config for email domains

	created on 2020-07-31 by peter@forret.com

## Installation

You can install the package via composer:

```bash
composer require toolstud-io/ts_senderpolicy
```

## Usage

``` php
$obj = new ToolstudIo\TsSenderpolicy();
echo $obj->echoPhrase('Hello, toolstud-io!');
```

## Testing

``` bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please email author_email instead of using the issue tracker.

## Credits

- [Peter Forret](https://github.com/toolstud-io)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
