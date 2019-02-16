## Installation

Either run

```
php composer.phar require --prefer-dist crocone/namecase "*"
```

or add

```json
"crocone/namecase" : "*"
```

to the `require` section of your composer.json.

## Usage

```php
$nc = new NCLNameCaseRu();
print_r($nc->qFirstName("Николай"));
 ```
