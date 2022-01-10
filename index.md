---

layout: yandex2

style: |
    /* собственные стили можно писать здесь!! */
---

# ![](pictures/symcode-logo.svg){:.logo}

## {{ site.presentation.title }}
{:.title}

## Условия

**Типичный проект**

* nginx
* php-fpm
* mysql/memcache/rabbitmq
* symfony

## План

**PHP and symfony legacy**

* категории
* подходы
* культура

## Категории legacy

* OS ~~debian 8/ubuntu 10~~ => docker-specific linux distro
* php version
* framework version
* vendor packages

## Подходы

**Подходы**

* Жесткий SemVer: не `composer require vendor/package:*`
* Сборка: composer, линтеры, PHP CS
* Модульные тесты: phpunit, codeception
* Статический анализ: psalm, phan
* Минимизация зависимостей: плагины к composer, например, vendor cleaner
* Мутационное тестирование (не пробовал)
* Автоматический рефакторинг: PHP-CS-Fixer/RectorPHP (не пробовал)

## Проверка

**Проверка**

* Только регресс

## Культура

* Дайжесты/Release notes/RFC
* парк сборок под разные версии (docker и оркестрация)
* минимизация зависимостей

## Контакты
{:.contacts}

<!-- разделитель контактов -->
-------

<!-- center -->

- {:.telegram} symcode - чат
- {:.telegram} symcode_live - канал

<!-- right -->
