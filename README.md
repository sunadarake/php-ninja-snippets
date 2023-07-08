# PHP Ninja Snippets - VSCode extension

PHP Ninja Snippets is an extension that provides a collection of snippets essential for PHP development. 

By using this extension, you will be freed from the hassle of repetitive coding tasks.

This plugin was created by forking **PHP Awesome Snippets** and adding custom snippets to it.

Thanks <a href="https://github.com/h4kst3r/php-awesome-snippets" target="_blank">h4kst3r/php-awesome-snippets</a> !!!

## Differences from PHP Awesome Snippets

We have added snippets for commonly used PHP functions that can be tedious to type. For example, we have added snippets for functions such as `array_shift`, `preg_match`, and `str_contains`.

On the other hand, we have removed unnecessary snippets that are no longer relevant. For instance, we have removed snippets related to PHP5.

## Snippets

Some snippets have multiple triggers specified.

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

###　Class

| Snippets | Output |
| --- | --- |
| class, cls | class ClassName{# code...} |
| clsex, class_extends | class ClassName extends MotherClass{# code...} |
| clsim, class_implements | class ClassName implements Interfaces{# code...} |
| clxi | class ClassName extends MotherClass implements Interfaces{# code...} |
| acl | abstract class ClassName{# code...} |
| aclx | abstract class ClassName extends MotherClass{# code...} |
| acli | abstract class ClassName implements Interfaces{# code...} |
| aclxi | abstract class ClassName extends MotherClass implements Interfaces{# code...} |
| fcl | final class ClassName{# code...} |
| fclx | final class ClassName extends MotherClass{# code...} |
| fcli | final class ClassName implements Interfaces{# code...} |
| fclxi | final class ClassName extends MotherClass implements Interfaces{# code...} |
| in | interface InterfaceName{# code...} |
| inx | interface InterfaceName extends Interfaces{# code...} |
| trt | trait TraitName{# code...} |

### If Switch Ternary

| Snippets | Output |
| --- | --- |
| if | if (condition) {# code...} |
| ifel | if (condition) {# code...} else {# code...} |
| ifelif | if (condition) {# code...} elseif (condition) {# code...} else {# code...} |
| sw | switch ($variable) {case 'label':# code...break;case 'label':# code...break;$6default:# code...break;} |
| cs | case 'label':# code...break; |
| tern | condition ? if_true : if_false; |

### Error

| Snippets | Output |
| --- | --- |
| tryc | try {# code...} catch (\Throwable $e) {# code...} |
| tryf | try {# code...} catch (\Throwable $e) {# code...} finally {# code...} |
| cat | catch (\Throwable $e) {# code...} |
| fy | finally {# code...} |
| thr | throw new SomeException("Error statement"); |

### Function

| Snippets | Output |
| --- | --- |
| fn, func | function func_name($args): void {# code...} |
| fna | function (Type $args): void {# code...} |
| fnu | function (Type $args) use ($vars): void {# code...} |

### Global Variables

| Snippets | Output |
| --- | --- |
| gglob | $_GLOBALS["key"] |
| gser | $_SERVER["key"] |
| greq | $_REQUEST["key"] |
| gpost | $_POST["key"] |
| gget | $_GET["key"] |
| gfile | $_FILES['userfile']['key'] |
| genv | $_ENV["key"] |
| gcook | $_COOKIE["key"] |
| gss | $_SESSION["key"] |

### Loop

| Snippets | Output |
| --- | --- |
| fora | foreach ($items as $item) {# code...} |
| forh | foreach ($items as $key => $item) {# code...} |
| for | for ($i = 0; $i < $limit; $i++) {# code...} |
| wl | while ($var <= $limit) {# code...} |
| dowl | do {# code...} while ($var <= $limit); |

### Method

| Snippets | Output |
| --- | --- |
| pubc, construct | public function __construct($args){# code...} |
| prif | private function methodName(args): void{# code...} |
| prisf | private static function methodName(args): void{# code...} |
| fprif | final private function methodName(args): void{# code...} |
| fprisf | final private static function methodName(args): void{# code...} |
| prof | protected function methodName(args): void{# code...} |
| prosf | protected static function methodName(args): void{# code...} |
| fprof | final protected function methodName(args): void{# code...} |
| fprosf | final protected static function methodName(args): void{# code...} |
| aprof | abstract protected function methodName(args): void; |
| aprosf | abstract protected static function methodName(args): void; |
| pubf | public function methodName(args): void{# code...} |
| pubsf | public static function methodName(args): void{# code...} |
| fpubf | final public function methodName(args): void{# code...} |
| fpubsf | final public static function methodName(args): void{# code...} |
| apubf | abstract public function methodName(args): void; |
| apubsf | abstract public static function methodName(args): void; |

### Preg function

| Snippets | Output |
| --- | --- |
| pr | preg_replace($search, $replace, $subject) |
| pm | preg_match($pattern, $replace, $matches) |
| pma | preg_match_all($pattern, $replace, $matches) |

### Statement

| Snippets | Output |
| --- | --- |
| df | define("CONSTANT", "value"); |
| inc | include __DIR__.'path_to_filename'; |
| inco | include_once __DIR__.'path_to_filename'; |
| rqr | require __DIR__.'path_to_filename'; |
| rqro | require_once __DIR__.'path_to_filename'; |
| eco | echo "text"; |
| pr | print_r($variable); |
| vd | var_dump($variable); |
| vx | var_export($variable); |

### String

| Snippets | Output |
| --- | --- |
| sc | str_contains($haystack, $needle) |
| sr | str_replace($search, $replace, $subject) |

