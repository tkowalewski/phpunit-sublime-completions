# PHPUNIT COMPLETIONS

## 1.2.0

* Update to PHPUnit 8.5

## 1.1.0

* Update to PHPUnit 7.5

## 1.0.0

* Update to PHPUnit 7.2

## 0.13.0

* Update to PHPUnit 6.5

## 0.12.0

* Update to PHPUnit 5.7.9

## 0.11.1

* Fixed: several issues with scopes in new builds of ST

## 0.11.0

* Added: cursor placeholder for methods with only one optional param
* Updated: PHPUnit 5

## 0.10.0

Fixed: Work around ST issues when triggers contain certain characters

Completions are broken in a various ways when completion
triggers contain characters not in range [a-zA-Z0-9_-].

See https://github.com/SublimeTextIssues/Core/issues/1061
See https://github.com/SublimeTextIssues/Core/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+completions

## 0.9.0

* Added: Package Settings Menu with README, CHANGELOG, and LICENSE links
* Added: PHPUnit_Framework_Error* class instantiable and type hint completion

## 0.8.0

* Added: a semicolon is now appened to all completions
* Changed: completions now only include the required parameter fields

## 0.7.0

* Renamed repository from sublime-phpck to sublime-php-completions. To change Git remote url see https://help.github.com/articles/changing-a-remote-s-url/
* Update to DbUnit 1.3.2; Adds `createArrayDataSet()` method

## 0.6.0

* Descriptions for DbUnit completions now says DbUnit
* Added some missing completions: `getMock`, `setExpectedExceptionFromAnnotation`, `setExpectedExceptionRegExp`, `atLeast`, `atMost`, `setUseErrorHandlerFromAnnotation`

## 0.5.0

* Scopes blacklists are now pretty printed
* Scopes are now sorted
* Type hints are now available in multi line comments, not just phpdocs's e.g. begin typing at `/* @var |`
* Annotations are now available in multi line comments, not just phpdoc's e.g. `/* @annotation `
* Minimise auto-complete noise: Functions and language constructs no longer activate in a "meta" scope e.g. typing at `class a extends |`

## 0.4.1

* (alister-patch-1) Spelling fix Thanks @alister #1

## 0.4.0

* Fixed: 8b1369f Completions shouldn't trigger in a class constant context e.g. self::|
* Fixed: 9e641cf Completions shouldn't trigger in a declaration context e.g. class a|

## 0.3.0

* Updated: b429b9a PHPUnit 4.4.0
* Added `assertArraySubset` method

## 0.2.2

* Fixed: 5282d19 Annotations can now be triggered without having to type the @ symbol

## 0.2.1

* Fixed: 9552886 Functions are no longer triggered in a comment context

## 0.2.0

* Updated: e2b7390 PHPUnit 4.3.5
* Added `expectedExceptionMessageRegExp` annotation
* Added `isInIsolation` method

## 0.1.1

* Fixed: Functions no longer trigger in a string context gerardroche/sublime-phpck#6

## 0.1.0

* Added DBUnit assertions, matchers, and other helper methods
* Added DBUnit testcase type hints
* Added Annotations
* Added Assertions, matchers, and other helper methods
* Added Test-case type hints

