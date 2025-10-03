## Clover Sketch: Template Engine

Clover Sketch: Template Engine; fully inspire by Vue.js and Laravel Blade. Built-in XSS attack prevention and @CSRF token generation.

[![Code Coverage](https://github.com/cloverphp/clover/actions/workflows/code-coverage.yml/badge.svg?branch=main)](https://github.com/cloverphp/clover/actions/workflows/code-coverage.yml)
[![CodeQL](https://github.com/cloverphp/clover/actions/workflows/github-code-scanning/codeql/badge.svg?branch=main)](https://github.com/cloverphp/clover/actions/workflows/github-code-scanning/codeql)
[![Tests](https://github.com/cloverphp/clover/actions/workflows/tests.yml/badge.svg)](https://github.com/cloverphp/clover/actions/workflows/tests.yml)
![Packagist Version](https://img.shields.io/packagist/v/cloverphp/sketch?style=flat&logo=composer&logoColor=%23fff)
![Packagist Dependency Version](https://img.shields.io/packagist/dependency-v/cloverphp/sketch/php?style=flat&logo=php&logoColor=blue&label=PHP&color=blue)
![Packagist License](https://img.shields.io/packagist/l/cloverphp/sketch?style=flat&label=License&color=blue)
![Packagist Downloads](https://img.shields.io/packagist/dt/cloverphp/sketch?style=flat&logo=packagist&label=Downloads&color=blue)
![Packagist Stars](https://img.shields.io/packagist/stars/cloverphp/sketch?style=flat&logo=github&logoColor=%23ffffff&label=%F0%9F%8C%9F%20Stars)

## Example
```vue
<h2> {{ $name }} </h2>
```
Output:
```php
<?php echo htmlspecialchar($name); ?>
```
## Example 2

```vue
<clover:@css>
    h2
    {
        color: red;
    }
</clover:@css>
```
output:
```html
<style>
h2{
  color: red;
}
</style>
```
