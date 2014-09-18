## A Virtual Machine for PHP/Apache

### Introduction
This project automates the setup of a development environment for working with PHP 5.5.

## Requirements
* [VirtualBox](https://www.virtualbox.org)
* [Vagrant 1.5+](http://vagrantup.com)

## How To Build The Virtual Machine
Building the virtual machine is this easy:

    $ git clone https://github.com/wfsneto/trusty64-php-apache.git
    $ cd trusty64-php-apache
    $ vagrant up

### What's In The Box

#### Server
* Ubuntu 14.04 (trusty64)
* Apache 2.4.7

#### Languages
* PHP 5.5.9

#### Databases
* MySQL 5.5.37
 * user: root
 * pass: raquel
* PostgreSQL 9.3.4
 * user: admin
 * pass: admin

#### Tools
* phpMyAdmin 4.0.10
* phpPgAdmin
* Git 1.9.1
* Composer

#### Libs
* cURL
* ImageMagick
* MCrypt

#### Providers
Virtualbox only
