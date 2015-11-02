# gerardroche/sublime-phpunit-snippets changelog

## 1.5.0-dev

* Added: Package Settings Menu with README, CHANGELOG, and LICENSE links

## 1.4.0

* Add new snippet: `testd` - test with annotated @depends
* All snippets descriptions are now prefixed with "PHPUnit: "

## 1.3.0

* Snippets now use PHP 5.4 array syntax `[]`
* `phpunit.xml` snippet: Fixed coding standard
* `phpunit.xml` snippet: Added default memory limit
* `phpunit.xml` snippet: Removed strict option in phpunit.xml snippet. The `strict` attribute of the XML configuration file has been deprecated in PHPUnit 4.5. See https://github.com/sebastianbergmann/phpunit/wiki/Release-Announcement-for-PHPUnit-4.5.0#deprecated-settings.
* `phpunit.xml` snippet:  Removed the `vendor/autoload.php` bootstrap attribute because PHPUnit already includes it.

## 1.2.0

* `phpunitxml` snippet: Added php ini configurations
* `phpunitxml` snippet: Added `forceCoversAnnotations=true`
* `phpunitxml` snippet: Removed `color=true`
* `phpunitxml` snippet: Changed bootstrap option from `test/bootstrap.php` to `vendor/autoload.php

## 1.1.0

* Snippets now target more specific scopes to minimise auto-complete noise

## 1.0.0

* Minimise auto-complete noise. Snippets like `teardown` and `setup` no longer activate in a meta scope e.g. begin typing at `c extends |`.
* Added: `testbootstrap` snippet - PHPUnit test bootstrap template
* Changed: The last field in snippet no longer ends with `// code ...`, it's now just blank.

## 0.1.0

* Initial import
