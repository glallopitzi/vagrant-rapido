vagrant-rapido
==============

A vagrant setup to develop for jobrapido

*vagrant-rapido* is a packaged development environment for developing for Jobrapido.  
I started this environment from VagrantPress and vagrant-yeoman-dev.

# What's Installed

+ Ubuntu Trusty (14.04)
+ Wordpress 4.0
+ Mysql
+ Php
+ Phpmyadmin
+ Subversion
+ PEAR
+ Xdebug
+ PHPUnit
+ phploc
+ phpcpd
+ phpdcd
+ phpcs
+ phpdepend
+ phpmd
+ PHP_CodeBrowser
+ WordPress sniffs for phpcs
+ WordPress Unit Tests

# Prerequisites

+ [Vagrant](http://www.vagrantup.com/downloads.html)
+ [Virtualbox](https://www.virtualbox.org/wiki/Downloads)

## Getting Started

This is a fairly simple project to get up and running.  
The procedure for starting up a working Jobrapido evironment is as follows:

1. Clone the project.  (There’s only master branch.)
2. Run the command `vagrant up`
3. Open your browser to http://localhost:8080

## Working with the environment

To log in to the local Wordpress installation:

`http://localhost:8080/wp-admin/` the username is `admin`, the password is `vagrant`.

You can access phpMyAdmin:

`http://localhost:8080/phpmyadmin/` with username `wordpress`, password `wordpress`.

## A Few Details

* If you're needing a password (for anything - including mysql, it should be `vagrant`)

## Getting Help

Ask to Franco Immaginario
