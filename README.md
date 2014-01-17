# ezBBC
### A PHP class for ease of use bulletin board code.

##### Usage
```php
<?php
require 'class.ezBBC.php';
$bbc = new orpheus\ezBBC();
/**
 *
 * $bbc = new orpheus\ezBBC(
 *          array(
 *            '/\[s\](.*?)\[\/s\]/i' => function($match) {
 *              return '<span style="text-decoration: line-through;">' . $match[1] . '</span>';
 *            }
 *          )
 *        );
 *
 */
echo $bbc->bbcize('[b]hello world[/b]');
echo $bbc->bbcize('[url="http://google.ca"]search[/url]');
?>
```
