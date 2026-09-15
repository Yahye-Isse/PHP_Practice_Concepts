# PHP Programming Screenshots

This folder contains screenshots demonstrating PHP programming concepts covered in the course **Web Application Development - PHP & MySQL**.

# PHP Introduction Screenshots

This folder contains screenshots explaining the basic concepts of PHP in the course:

**Web Application Development - PHP & MySQL**

---

# 1. PHP Introduction

## Screenshot Name

`PHP_Introduction.png`

## Description

This screenshot introduces PHP as a server-side scripting language.

Main concepts covered:

- PHP syntax is influenced by languages such as C and Java.
- PHP is a hybrid language that combines features from different programming languages.
- PHP files use the `.php` extension.
- When a web server receives a PHP file, it sends the file to the PHP processor for execution.

## Screenshot

![PHP Introduction](PHP_Introduction.png)

# 2. PHP File Extension and Execution

## Screenshot Name

`PHP_File_Extension.png`

## Description

This screenshot explains how to create and run a PHP file.

Important points:

- PHP files must be saved using the `.php` extension.
- The PHP file should be placed inside the web server root directory.

Examples:

```
XAMPP:
C:\xampp\htdocs

WAMP:
C:\wamp\www
```

The PHP application can be accessed through a browser:

```
http://localhost/index.php
```

## Screenshot

![PHP File Extension](PHP_File_Extension.png)

---

# 3. PHP File Structure

## Screenshot Name

`PHP_File_Structure.png`

## Description

This screenshot explains the structure of a PHP file.

A PHP file can contain three main components:

1. Text content
2. HTML code
3. PHP script

PHP files are different from normal HTML files because they contain PHP instructions processed by the PHP engine.

Important:

- PHP files must have the `.php` suffix.
- PHP files must be stored inside the web server root directory.

Example:

```
C:\xampp\htdocs
```

## Screenshot

![PHP File Structure](PHP_File_Structure.png)

---

---

#  PHP Tags

## Screenshot Name:
`PHP_Tags.png`

## Description:
This screenshot demonstrates the basic PHP syntax structure.

PHP code is written inside PHP opening and closing tags:

```php
<?php

# PHP Generating Output

This section explains how PHP displays output using the `echo` and `print` statements.

---

# 4. Echo and Print Statements

## Screenshot Name

`PHP_Echo_Print_Code.png`

## Description

This screenshot demonstrates how to generate output in PHP using:

- `echo`
- `print`

Both commands are used to display text in the browser.

### Echo Example

```php
<?php

echo "Welcome to PHP";

echo ("Welcome to PHP");

?>
```

### Print Example

```php
<?php

print "Welcome to PHP";

print ("Welcome to PHP");

?>
```

### Multiple Arguments with Echo

`echo` can display multiple values without parentheses.

Example:

```php
<?php

echo "Yahye", "Ali";

?>
```

## Screenshot

![Echo Print Code](PHP_Echo_Print_Code.png)

---

# 5. Echo Statement and Print Statement

## Description

This  explains the differences between `echo` and `print`.

### Echo

- Used to output text from the server to the browser.
- Can display one or more parameters.
- Does not return a value.
- Usually faster than print.

Example:

```php
<?php

echo "Hello World";

?>
```

### Print

- Used to display text in the browser.
- Accepts only one parameter.
- Returns a value.

Example:

```php
<?php

print "Hello World";

?>
```

### Important Note

Parentheses are optional for both:

```php
echo "PHP";

print "PHP";
```

or

```php
echo ("PHP");

print ("PHP");
```
# 6. Difference Between Echo and Print

## Screenshot Name

`PHP_Echo_Print_Difference.png`

## Description

This screenshot demonstrates advanced differences between `echo` and `print`.

## Echo

Advantages:
- Accepts multiple parameters.
Example:

```php
<?php
echo "Hello World!", " Yahye Ali Isse";
?>
```
Output:
```
Hello World! Yahye Ali Isse
```
## Print

Limitations:
- Accepts only one parameter.
Example:
```php
<?php
print "Hello World!", " PHP";

?>
```
Result:
```
Error
```
## Ternary Expression
`print` can be used inside a ternary expression, while `echo` cannot.
Example:
```php
<?php
$x = 5;
$y = 10;
$x < $y ? print "x is less than y" : print "x is greater than y";
?>
```



