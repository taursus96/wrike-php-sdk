Wrike PHP SDK
================================

Introduction
------------

**This is full pre-configured Wrike PHP SDK package for [Wrike PHP Library](https://github.com/zibios/wrike-php-library).**

Handle
[Wrike PHP Library](https://github.com/zibios/wrike-php-library),
[HTTP Client plugin](https://github.com/zibios/wrike-php-guzzle) and
[response transformer plugin](https://github.com/zibios/wrike-php-jmsserializer)
in one package.


For more info or none standard purposes please check [generic Wrike PHP Library](https://github.com/zibios/wrike-php-library).
For Symfony2 / Symfony3 please check full configured [Wrike bundle](https://github.com/zibios/wrike-bundle).

Project status
--------------

[![Packagist License](https://img.shields.io/packagist/l/zibios/wrike-php-sdk.svg)](https://packagist.org/packages/zibios/wrike-php-sdk)
[![Packagist Downloads](https://img.shields.io/packagist/dt/zibios/wrike-php-sdk.svg)](https://packagist.org/packages/zibios/wrike-php-sdk)
[![Packagist Version](https://img.shields.io/packagist/v/zibios/wrike-php-sdk.svg)](https://packagist.org/packages/zibios/wrike-php-sdk)

[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/zibios/wrike-php-sdk/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/zibios/wrike-php-sdk/?branch=master)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/3dea766e-c7cc-4180-b611-8a3b103f334f/mini.png)](https://insight.sensiolabs.com/projects/3dea766e-c7cc-4180-b611-8a3b103f334f)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/1fcef9280f3844b6bb1249fe0f21de0f)](https://www.codacy.com/app/zibios/wrike-php-sdk)
[![Test Coverage](https://codeclimate.com/github/zibios/wrike-php-sdk/badges/coverage.svg)](https://codeclimate.com/github/zibios/wrike-php-sdk/coverage)
[![Build Status](https://travis-ci.org/zibios/wrike-php-sdk.svg?branch=master)](https://travis-ci.org/zibios/wrike-php-sdk)
[![Libraries.io](https://img.shields.io/librariesio/github/zibios/wrike-php-sdk.svg)](https://libraries.io/packagist/zibios%2Fwrike-php-sdk)

[All badges](docs/Badges.md)

Installation
------------
To try it yourself clone the repository:

```bash
git clone git@github.com:zibios/wrike-php-sdk.git
cd wrike-php-sdk
```

and install dependencies with composer:

```bash
composer install
```

Run PHPUnit tests:

```bash
./vendor/bin/phpunit
``` 

Usage
-----
```php
/**
 * Basic usage
 */
$api = ApiFactory::create(<PermanentToken>);
$allContacts = $api->getContactResource()->getAll();
...
```
 
For more info please check full documentation on [Generic Wrike PHP Library](https://github.com/zibios/wrike-php-library)


Reference
---------

[Generic Wrike PHP Library](https://github.com/zibios/wrike-php-library)

[Response transformer plugin](https://github.com/zibios/wrike-php-jmsserializer) for Wrike PHP Library

[HTTP Client plugin](https://github.com/zibios/wrike-php-guzzle) for Wrike PHP Library

[Symfony bundle](https://github.com/zibios/wrike-bundle)

Official [Wrike API Documentation](https://developers.wrike.com/documentation/api/overview)

License
-------

This bundle is available under the [MIT license](LICENSE).
