# Simplest Router

To applications in PHPOO with MVC

## Based in

This simplest, friendly and efficient has was created from the softwares:

- https://github.com/nikic/FastRoute
- https://github.com/panique/mini3

This little routing system works well with PHPOO applications with MVC

Capture the URL and split it into parts: controller, action and parameter

http://localhost/application/controller/action/param

Example

http://localhost/crud-mvc/product/edit/5

## Try with/Support

- Windows 10
    - Laragon - PHP 8.1
- Linux Mint 21
    - PHP 8.1
- Ubuntu
    - 22.04 - PHP 8.1
    - 20.04 - PHP 7.4
    - 14.04 - PHP 5.5
- Namespace
- Require
- Fixo
- MySQL/MariaDb
- PostgreSQL

## PHP 5 does not support:

declare(strict_types = 1);

Nor is the syntax:

$this->controller->{$this->action}( ...$this->params);

## Requirements

- Module mod_rewrite from Apache

## Extra Tips

## Native PHP functions and constants for classes and objects

if ( ! class_exists('App\\Controllers\\ProductController')) die('Class not found!');

die(__CLASS__);

get_class($this);

die(__NAMESPACE__);


## Licence

MIT

This means that you can freely use and modify it for personal and commercial projects, only with the credit of the authors.

