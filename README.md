# PHPUNIT COMPLETIONS

Provides decent PHPUnit completions for Sublime Text.

## Overview

* [Features](#features)
* [Key Bindings](#key-bindings)
* [Installation](#installation)
* [Contributing](#contributing)
* [Changelog](#changelog)
* [License](#license)

# Features

* [PSR](http://www.php-fig.org) compliant
* Scoped to minimise auto-complete noise
* Test case type hints e.g. begin typing at `class Name extends |` and any other context where a type hint is valid.
* [Assertions](https://phpunit.de/manual/current/en/appendixes.assertions.html) e.g. begin typing `assert|` or `$this->assert|`
* Test case helpers e.g. begin typing `getMockBuilder|` or `$this->getMockBuilder|`
* [Annotations](https://phpunit.de/manual/current/en/appendixes.annotations.html) e.g. begin typing _(any valid doc block scope)_ `/* @covers| */` or without the `@` symbol `/* covers| */`

## Key Bindings

| OS X | Windows | Linux | Description |
|------|---------|-------|-------------|
| <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Alt</kbd>+<kbd>/</kbd> | Activate completions |

To enable [tab-completions](http://docs.sublimetext.info/en/latest/extensibility/completions.html#tab-completed-completions) set `"tab_completion": true` in `Preferences > Settings - User`.

## Installation

### Package Control installation

The preferred method of installation is via Package Control.

1. Install [Package Control](https://packagecontrol.io).
2. From inside Sublime Text, open Package Control's Command Pallet: <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> (Windows, Linux) or <kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Mac.
3. Type `install package` and hit Return. A list of available packages will be displayed.
4. Type `phpunit-sublime-completions` and hit Return. The package will be downloaded to the appropriate directory.
5. Restart Sublime Text to complete ins,rtallation. The features listed above should now be available.

### Manual installation

1. Close Sublime Text.
2. Download or clone this repository to a directory named `php-completions` in the Sublime Text Packages directory for your platform:
    * Sublime Text 3
        - Linux: `git clone https://github.com/tkowalewski/phpunit-sublime-completions.git ~/.config/sublime-text-3/Packages/phpunit-sublime-completions`
        - OS X: `git clone https://github.com/tkowalewski/phpunit-sublime-completions.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/phpunit-sublime-completions`
        - Windows: `git clone https://github.com/tkowalewski/phpunit-sublime-completions.git %APPDATA%\Sublime/ Text/ 3/Packages/phpunit-sublime-completions`
    * Sublime Text 2
        - Linux: `git clone https://github.com/tkowalewski/phpunit-sublime-completions.git ~/.config/sublime-text-2/Packages/phpunit-sublime-completions`
        - OS X: `git clone https://github.com/tkowalewski/phpunit-sublime-completions.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/phpunit-sublime-completions`
        - Windows: `git clone https://github.com/tkowalewski/phpunit-sublime-completions.git %APPDATA%\Sublime/ Text/ 2/Packages/phpunit-sublime-completions`
3. Restart Sublime Text to complete installation. The features listed above should now be available.
4.
## Contributing

Your issue reports and pull requests are always welcome.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## License

Released under the [???][LICENSE].
