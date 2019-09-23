# `vendor:publish` for Lumen framework

[![Latest Stable Version](https://poser.pugx.org/joelhy/lumen-vendor-publish/v/stable)](https://packagist.org/packages/joelhy/lumen-vendor-publish) [![Total Downloads](https://poser.pugx.org/joelhy/lumen-vendor-publish/downloads)](https://packagist.org/packages/joelhy/lumen-vendor-publish) [![Latest Unstable Version](https://poser.pugx.org/joelhy/lumen-vendor-publish/v/unstable)](https://packagist.org/packages/joelhy/lumen-vendor-publish) [![License](https://poser.pugx.org/joelhy/lumen-vendor-publish/license)](https://packagist.org/packages/joelhy/lumen-vendor-publish)

This is a fork of [laravelista/lumen-vendor-publish](https://github.com/laravelista/lumen-vendor-publish), which is mostly a copy from [`illuminate/foundation`](https://github.com/laravel/framework/blob/5.3/src/Illuminate/Foundation/Console/VendorPublishCommand.php).

This package contains a single command that enables you to publish a package config file to the config folder of your Lumen application.

## Installation

```
composer require joelhy/lumen-vendor-publish
```

## Usage

To be able to use it you have to add it to your `app/Console/Kernel.php` file:

```
protected $commands = [
    \Joelhy\LumenVendorPublish\VendorPublishCommand::class
];
```
