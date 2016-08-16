# phpunit-snippets

[![Author](https://img.shields.io/badge/author-@gerardroche-blue.svg?style=flat)](https://twitter.com/gerardroche)
[![Source Code](https://img.shields.io/badge/source-GitHub-blue.svg?style=flat)](https://github.com/gerardroche/sublime-phpunit-snippets)
[![License](https://img.shields.io/badge/license-BSD--3-blue.svg?style=flat)](https://raw.githubusercontent.com/gerardroche/sublime-phpunit-snippets/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/gerardroche/sublime-phpunit-snippets.svg?style=flat)](https://github.com/gerardroche/sublime-phpunit-snippets/stargazers)
[![Sublime version](https://img.shields.io/badge/sublime-v3-lightgrey.svg?style=flat)](https://sublimetext.com)
[![Latest version](https://img.shields.io/github/tag/gerardroche/sublime-phpunit-snippets.svg?label=release&style=flat&maxAge=2592000)](https://github.com/gerardroche/sublime-phpunit-snippets/tags)

PHPUnit snippets for Sublime Text.

## THIS PROJECT IS NO LONGER MAINTAINED!

**I moved all my snippets to my custom [sublimefiles](https://github.com/gerardroche/sublimefiles).**

## Overview

* [Features](#features)
* [Key Bindings](#key-bindings)
* [Installation](#installation)
* [Contributing](#contributing)
* [Changelog](#changelog)
* [License](#license)

**Works best with [PHP Grammar], [PHP Completions], [PHP Snippets], [PHPUnit], and [PHPUnit Completions].**

## Features

* PHPUnit [~4.4](http://semver.org)
* DbUnit [~1.3](http://semver.org)
* [PSR](http://www.php-fig.org) compliant
* Scoped to minimise auto-complete noise

## Snippets

| Trigger | Description |
| ------- | ----------- |
| `phpunitxml` | PHPUnit: xml configuration declaration |
| `provide` | PHPUnit: data provider test |
| `setup` | PHPUnit: setup method declaration |
| `teardown` | PHPUnit: teardown method declaration |
| `test` | PHPUnit: test |
| `testbootstrap` | PHPUnit: bootstrap |
| `testcase` | PHPUnit: test case declaration |
| `testd` | PHPUnit: test with annotated @depends |

## Key Bindings

| OS X | Windows | Linux | Description |
|------|---------|-------|-------------|
| <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Alt</kbd>+<kbd>/</kbd> | Activate completions |

To enable [tab-completions](http://docs.sublimetext.info/en/latest/extensibility/completions.html#tab-completed-completions) set `"tab_completion": true` in `Preferences > Settings - User`.

## Installation

### Manual installation

1. Close Sublime Text.
2. Download or clone this repository to a directory named `phpunit-snippets` in the Sublime Text Packages directory for your platform:
    * Sublime Text 3
        - Linux: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git ~/.config/sublime-text-3/Packages/phpunit-snippets`
        - OS X: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/phpunit-snippets`
        - Windows: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git %APPDATA%\Sublime/ Text/ 3/Packages/phpunit-snippets`
    * Sublime Text 2
        - Linux: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git ~/.config/sublime-text-2/Packages/phpunit-snippets`
        - OS X: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/phpunit-snippets`
        - Windows: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git %APPDATA%\Sublime/ Text/ 2/Packages/phpunit-snippets`
3. Restart Sublime Text to complete installation. The features listed above should now be available.

## Contributing

Your issue reports and pull requests are always welcome.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## License

Released under the [BSD 3-Clause License](LICENSE).

[Package Control]: https://packagecontrol.io/browse/authors/gerardroche
[PHP Completions]: https://packagecontrol.io/browse/authors/gerardroche
[PHP Grammar]: https://packagecontrol.io/browse/authors/gerardroche
[PHP Snippets]: https://packagecontrol.io/browse/authors/gerardroche
[PHPUnit Completions]: https://packagecontrol.io/browse/authors/gerardroche
[PHPUnit Snippets]: https://packagecontrol.io/browse/authors/gerardroche
[PHPUnit]: https://packagecontrol.io/browse/authors/gerardroche
[Composer]: https://getcomposer.org
