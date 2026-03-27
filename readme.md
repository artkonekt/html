# Laravel 11+ Compatible Fork of the LaravelCollective Forms Package

[![Tests](https://img.shields.io/github/actions/workflow/status/artkonekt/html/tests.yml?branch=master&label=tests&style=flat-square)](https://github.com/artkonekt/html/actions?query=workflow%3Atests)
[![Packagist Stable Version](https://img.shields.io/packagist/v/konekt/html.svg?style=flat-square&label=stable)](https://packagist.org/packages/konekt/html)
[![Packagist downloads](https://img.shields.io/packagist/dt/konekt/html.svg?style=flat-square)](https://packagist.org/packages/konekt/html)
[![MIT Software License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE.txt)

This is a fork of the original LaravelCollective HTML package.
It aims to serve as a drop-in replacement after the original package is no longer updated.

The only change this package brings is that it only supports PHP 8.1+ and Laravel 10, 11, 12 & 13.

The rest of the functionality is identical with the original one.

## Installation

Run:

```bash
composer require konekt/html:^6.5
``` 

This will replace your existing laravelcollective/html v6.4+ installation with this version:

![Replace the package](docs/replace650.png)

See the original [Documentation](https://laravelcollective.com/docs) for usage details.
