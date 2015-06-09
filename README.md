# sublime-phpunit-snippets

sublime-phpunit-snippets plugin for Sublime Text. Provides decent PHPUnit snippets.

## Overview

* [Features](#features)
* [Key Bindings](#key-bindings)
* [Installation](#installation)
* [Contributing](#contributing)
* [Changelog](#changelog)
* [Complementary Plugins](#complementary-plugins)
* [License](#license)

# Features

* PHPUnit [~4.4][semver]
* DbUnit [~1.3][semver]
* [PSR][php-fig] compliant
* Scoped to minimise auto-complete noise

See the [documentation] for a list of the snippets.

## Key Bindings

| OS X | Windows | Linux | Description |
|------|---------|-------|-------------|
| <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Alt</kbd>+<kbd>/</kbd> | Activate completions |

To enable [tab-completions][tab-completed-completions] set `"tab_completion": true` in `Preferences > Settings - User`.

## Installation

### Manual installation

1. Download or clone this repository to a directory named `phpunit-snippets` in the Sublime Text Packages directory for your platform:
    * Sublime Text 3
        - Linux: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git ~/.config/sublime-text-3/Packages/phpunit-snippets`
        - OS X: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/phpunit-snippets`
        - Windows: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git %APPDATA%\Sublime/ Text/ 3/Packages/phpunit-snippets`
    * Sublime Text 2
        - Linux: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git ~/.config/sublime-text-2/Packages/phpunit-snippets`
        - OS X: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/phpunit-snippets`
        - Windows: `git clone https://github.com/gerardroche/sublime-phpunit-snippets.git %APPDATA%\Sublime/ Text/ 2/Packages/phpunit-snippets`
2. Restart Sublime Text to complete installation. The features listed above should now be available.

## Contributing

Issue reports and pull requests are always welcome.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## Complementary Plugins

* [php-completions]
* [php-grammar]
* [php-snippets]
* [phpunit-completions]
* [phpunit-snippets]
* [phpunit]

## License

sublime-phpunit-snippets is released under the [BSD 3-Clause License][license].

[documentation]: DOCUMENTATION.md
[license]: LICENSE
[Package Control]: https://packagecontrol.io
[php-completions]: https://github.com/gerardroche/sublime-phpck
[php-fig]: http://www.php-fig.org
[php-grammar]: https://github.com/gerardroche/sublime-php-grammar
[php-snippets]: https://github.com/gerardroche/sublime-php-snippets
[phpunit-completions]: https://github.com/gerardroche/sublime-phpunitck
[phpunit-snippets]: https://github.com/gerardroche/sublime-phpunit-snippets
[phpunit]: https://github.com/gerardroche/sublime-phpunit
[semver]: http://semver.org
[tab-completed-completions]: http://docs.sublimetext.info/en/latest/extensibility/completions.html#tab-completed-completions
