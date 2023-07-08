# PHP Ninja Snippets - VSCode extension

PHP Ninja Snippets is an extension that provides a collection of snippets essential for PHP development. 

By using this extension, you will be freed from the hassle of repetitive coding tasks.

This plugin was created by forking **PHP Awesome Snippets** and adding custom snippets to it.

Thanks <a href="https://github.com/h4kst3r/php-awesome-snippets" target="_blank">h4kst3r/php-awesome-snippets</a> !!!

## Differences from PHP Awesome Snippets

We have added snippets for commonly used PHP functions that can be tedious to type. For example, we have added snippets for functions such as `array_shift`, `preg_match`, and `str_contains`.

On the other hand, we have removed unnecessary snippets that are no longer relevant. For instance, we have removed snippets related to PHP5.

## Snippets

### Array

| Snippets | Output |
| --- | --- |
| apu, push | array_push($array, $item) |
| as, shift | array_shift($array) |
| apo, pop | array_pop($array) |
| aus, unshift | array_unshift($array, $item) |
| ame, merge | array_merge($array, $array) |
| ama, map | array_map(function($val) { CODE } ,$array) |
| afi, filter | array_filter($array, function($val) { CODE }) |
| are, reduce | array_reduce($array, function($val) { CODE }) |
| auni, unique | array_unique($array) |



