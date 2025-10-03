## Clover Sketch: Template Engine

Clover Sketch: Template Engine; fully inspire by Vue.js and Laravel Blade. Built-in XSS attack prevention and @CSRF token generation.

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
