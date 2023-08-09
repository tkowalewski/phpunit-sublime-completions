# PHPUNIT COMPLETIONS

Provides decent PHPUnit completions for Sublime Text.

## Overview

* [Features](#features)
* [Key Bindings](#key-bindings)
* [Installation](#installation)
* [Contributing](#contributing)
* [Changelog](#changelog)

# Features

- Fully [PSR](http://www.php-fig.org) compliant
- Scoped to minimize auto-complete noise
- Enhanced support for test case type hints, such as starting at `class Name extends |`, and any other context where a type hint is applicable.
- Extensive [assertions](https://phpunit.de/manual/current/en/appendixes.assertions.html) support, including starting with `assert|` or `$this->assert|`
- Time-saving test case helpers like starting with `getMockBuilder|` or `$this->getMockBuilder|`
- Streamlined use of [annotations](https://phpunit.de/manual/current/en/appendixes.annotations.html) through doc block scope, such as `/* @covers| */` or without the `@` symbol `/* covers| */`

## Key Bindings

| OS X | Windows | Linux | Description |
|------|---------|-------|-------------|
| <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Ctrl</kbd>+<kbd>Space</kbd> | <kbd>Alt</kbd>+<kbd>/</kbd> | Activate completions |

To enable [tab-completions](http://docs.sublimetext.info/en/latest/extensibility/completions.html#tab-completed-completions) set `"tab_completion": true` in `Preferences > Settings - User`.

## Installation

**Package Control Installation**

1. Open Sublime Text.
2. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS) to open the Command Palette.
3. Type "Package Control: Install Package" and press `Enter`.
4. In the input field, type "PHPUnit Completions" and select it from the list of available packages.

**Git Repository Installation**

1. Open a terminal or command prompt.
2. Navigate to the Sublime Text Packages directory:
    - On Windows: `%APPDATA%\Sublime Text\Packages`
    - On macOS: `~/Library/Application Support/Sublime Text/Packages`
    - On Linux: `~/.config/sublime-text/Packages`
3. Clone the plugin repository directly into the Packages directory using Git:
   ```
   git clone https://github.com/tkowalewski/phpunit-sublime-completions.git
   ```

## Contributing

Your issue reports and pull requests are always welcome.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
