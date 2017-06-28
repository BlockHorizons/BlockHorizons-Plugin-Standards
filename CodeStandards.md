# BlockHorizons' Code Standards

* When using PHPStorm, [this coding style](https://github.com/BlockHorizons/BlockHorizons-Plugin-Standards/blob/master/BlockHorizonsCodeStyle.xml) should really be considered.
* Tabs must be used instead of spaces
* Tabs must have an indentation size of 4
* PHPDoc comments should have a space between every tag type, e.g.
```php
/**
 * Some method.
 * 
 * @param string $parameter
 *
 * @return bool
 */
```
* Functions should use type hints wherever possible, both in return types and function parameters.
* Functions that are usable by other plugins should really be documented clearly.
* There really should be a whitespace between every function in a class.

* The plugin.yml file should really not contain plugin APIs that the plugin has not been tested with.
* Plugins really should contain ways to modify the behaviour of the plugin through API such as plugin events.

* YAML files should have hyphens and could use capital letters for each first letter of a word.
* YAML files should start with `---` and end with `...`, and a space between the text and comment hashtag, e.g.

```yaml
---
# A comment
Some-Key: something
...
```