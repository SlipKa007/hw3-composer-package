# Процессор строк

HW3 composer package

Библиотека даёт беспрецедентную возможность обратиться  к **Magic Ball'у** с любым вопросом.
Но учти, дружочек, **Magic Ball** ответит тебе только *"Да"* или *"Нет"*. Внемли гласу ___Макоши!___:smiling_imp:


## Трбования

- PHP  8.1

## Установка

`
composer require slipka007\hw3-composer-package
`

## Использование

```php
<?php

$answer = new MagicBall();
echo $answer->getAnswer();?>