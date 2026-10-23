# webgriffe/phpunit-dist

PHPUnit phar distribution for Webgriffe projects.

Provides the `phpunit` binary via Composer without pulling in PHPUnit's full dependency tree.

## Installation

```bash
composer require --dev webgriffe/phpunit-dist
```

## Usage

```bash
vendor/bin/phpunit
```

## Versioning

Versions mirror [PHPUnit upstream releases](https://github.com/sebastianbergmann/phpunit/releases).
The latest and the previous major are published. Each tag declares the PHP version required by that PHPUnit release.

## How it works

This package is automatically updated by [webgriffe/php-tools-dist](https://github.com/webgriffe/php-tools-dist).
When a new PHPUnit release is published, the phar is downloaded from phar.phpunit.de and a new tagged version is pushed here within 24 hours.
