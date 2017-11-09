## PHP 7

### Simple poll

OOP style coding with two classes using JSON file database.

[SimplePoll](https://github.com/bformela/SimplePoll)

### MySQLi OOP CRUD

Simple OOP class with methods being able to access MySQL database and perform create, read, update, delete actions using MySQLi.

[MySQLiOOP](https://github.com/bformela/MySQLiOOP)

### School punishment solution nowadays
```php
function punishment(string $sentence, int $amount): void {
    for ($i = 1; $i<=$amount; $i++) {
        echo nl2br($i . '. ' . $sentence . PHP_EOL);
    }
}

punishment('I will not throw paper airplanes in class.', 100);

```
