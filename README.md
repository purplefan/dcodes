# Requirements #
* composer
* php 5.6
* symfony 2.8



# Installation #

```bash
$ composer install
```

# Run #
```bash
$ php app/console server:run
```
Browser:
```
http://127.0.0.1:8000/dcode
```

# Console #
```bash

$ php app/console codes:generate <length> <count>
Arguments:
  length                   Length of discount code (4 - 1000)
  count                    Count of discount code (1 - 1000000)
```