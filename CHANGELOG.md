# phpunit-snippets changelog

## 1.3.0 (next-version)

### Changes

* Removed strict option in phpunit.xml snippet. The `strict` attribute of the XML configuration file has been deprecated in PHPUnit 4.5. See https://github.com/sebastianbergmann/phpunit/wiki/Release-Announcement-for-PHPUnit-4.5.0#deprecated-settings.

## 1.2.0

### New Features

* `phpunitxml` snippet
    - Add php ini configurations
    - Add `forceCoversAnnotations=true`

### Changes

* `phpunitxml` snippet
    - Remove `color=true`
    - Change bootstrap option from `test/bootstrap.php` to `vendor/autoload.php

## 1.1.0

### New Features

* Snippets now target more specific scopes to minimise auto-complete noise

## 1.0.0

### New Features

* Minimise auto-complete noise. Snippets like `teardown` and `setup` no longer activate in a meta scope e.g. begin typing at `c extends |`. 
* Added: `testbootstrap` snippet - PHPUnit test bootstrap template

### Changes

* Changed: The last field in snippet no longer ends with `// code ...`, it's now just blank. 

## 0.1.0

* Initial import of basic phpunit snippets
