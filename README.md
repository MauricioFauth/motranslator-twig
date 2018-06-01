# motranslator-twig

Twig integration for translation API for PHP using Gettext MO files.

[![Build Status](https://travis-ci.com/phpmyadmin/motranslator-twig.svg?branch=master)](https://travis-ci.com/phpmyadmin/motranslator-twig)
[![codecov.io](https://codecov.io/github/phpmyadmin/motranslator-twig/coverage.svg?branch=master)](https://codecov.io/github/phpmyadmin/motranslator-twig?branch=master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/phpmyadmin/motranslator-twig/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/phpmyadmin/motranslator-twig/?branch=master)
[![Packagist](https://img.shields.io/packagist/dt/phpmyadmin/motranslator-twig.svg)](https://packagist.org/packages/phpmyadmin/motranslator-twig)

## Features

* All strings are stored in memory for fast lookup
* Fast loading of MO files
* Low level API for reading MO files
* Emulation of Gettext API
* No use of `eval()` for plural equation

## Limitations

* Not suitable for huge MO files which you don't want to store in memory
* Input and output encoding has to match (preferably UTF-8)

## Installation

Please use [Composer][1] to install:

```
composer require phpmyadmin/motranslator-twig
```

## Documentation

The API documentation is available at 
<https://develdocs.phpmyadmin.net/motranslator-twig/>.


