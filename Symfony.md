# Symfony-Reference
## by Shubhrendu Tripathi

<br><br>

# All

New project without Git

    $ symfony new project1 --no-git

Help

    $ symfony new --help 

# Project Structure

Composer creates a Symfony application structure.

    $ ls -1ap --group-directories-first
    ./
    ../
    bin/
    config/
    public/
    src/
    var/
    vendor/
    .env
    .gitignore
    composer.json
    composer.lock
    symfony.lock

Directory | Description |
--- | --- |
`bin`       |   contains the `console` tool - a command-line utility to execute various types of commands
`public`    |   contains the web files. In a Symfony skeleton application, it contains one file: index.ph
`config`    |   contains the configuration files
`public`    |   contains the 
`src`       |   contains the source code
`var`       |   contains temporary files
`vendor`    |   contains third party dependencies
&nbsp;      |   &nbsp;
.env        |   &nbsp;
.gitignore  |   &nbsp;

# proc_open(): fork failed errors

If composer shows proc_open() fork failed on some commands:

PHP Fatal error: Uncaught exception 'ErrorException' with message 'proc_open(): fork failed - Cannot allocate memory' in phar

This could be happening because the VPS runs out of memory and has no Swap space enabled.

    free -m

    total used free shared buffers cached
    Mem: 2048 357 1690 0 0 237
    -/+ buffers/cache: 119 1928
    Swap: 0 0 0

To enable the swap you can use for example:

    /bin/dd if=/dev/zero of=/var/swap.1 bs=1M count=1024
    /sbin/mkswap /var/swap.1
    /bin/chmod 0600 /var/swap.1
    /sbin/swapon /var/swap.1

You can make a permanent swap file following this tutorial.

# Components

## Installation

    $ composer require symfony/asset

    $ composer require symfony/string 

## Component List

Component | Description | Resources
--- | --- | --- |
Asset | Manages URL generation and versioning of web assets such as CSS stylesheets, JavaScript files and image files | &nbsp;
BrowserKit | Simulates the behavior of a web browser | &nbsp;



# Fast Track Book Review

## Step 1: Checking Work Environment

<b>Work Environment<b>

<ol>
<li>A Computer</li>
<li>Choose database (MySQL), queue manager etc</li>
<li>IDE - Visual Studio Code</li>
<li>Terminal</li>
<li>Git</li>
<li>PHP</li>
<li>Composer</li>
<li>Docker and Docker Compose</li>
<li>Symfony CLI<li>
</ol>

<b>Symfony CLI<b>

    $ symfony server:ca:install

    $ symfony book:check-requirements

Almost always prefix a command in terminal with `symfony` like in `symfony composer` instead of just `composer`, or `symfony console` instead of `./bin/console`.

## Step 2: Introducing the Project


### windows setup symfony

install git (needed for symfony)
install xampp
install composer binary from getcomposer.org 
install symfony binary from symfony.org - install using defaults

### (1) check if computer meets all requirements

    $ symfony check:requirements

### (2) run this for a traditional web application

    $ symfony new my_project_name --full

### (3) run this for a traditional web application - using composer

    $ composer create-project symfony/website-skeleton my_project_name

### (4) run this for a building a microservice, console application or API

    $ symfony new my_project_name

### (5) run this for a building a microservice, console application or API - using composer

    $ composer create-project symfony/skeleton my_project_name

### show info about a project

    $ cd prj1
    $ php bin/console about

### clear cache

    $ php bin/console cache:clear

### php ini info

    $ php --ini

### annotations for routing

$ composer require annotations

$ php bin/console cache:clear
$ php bin/console cache:warmup
$ php bin/console router


$ php bin/console debug:route
$ php bin/console debug:router

### web debug toolbar for symfony

$ composer require symfony/profiler-pack

$ composer require twig

### All

$ composer require symfony/web-profiler-bundle

$ composer require symfony/maker-bundle

$ symfony console list make

$ php bin/console debug:container

$ php bin/console debug:container --types

to search for a specific service - 'Hello' service
$ php bin/console debug:container Hello


to show all controllers
$ php bin/console debug:container Controller


list of all php versions on the machine
$ symfony local:php:list

tradition web application
$ symfony new prj1 --full --no-git

$ php bin/console about

$ composer install

# the best way to create a functioning project - with the debug toolbars and everything working

$ symfony new prj1 --demo --no-git

then browse to 

http://localhost/prj2/public

after adding controller Hello, browse to 

http://localhost:8080/europa/public/en/hello

# symfony recommendations

<ul>

</ul>

# full working set of commands to get a running application

$ symfony new prj1 --demo --no-git
$ chmod -R 777 prj1
$ cd prj1/
$ php bin/console about
$ php bin/console debug:container
$ php bin/console debug:container Controller
$ php bin/console debug:router 
$ composer require annotations
$ composer require twig
$ composer require doctrine/annotations
$ php bin/console debug:router

# composer show all installed packages
browse to the project directory - that has composer.json
then

$ composer show -i

# routing

App receives request -> calls a `Controller action` to generate response

Routing configuration 
- which action to run for each incoming URL
- other useful features - like generating SEO-friendly URLs

## create routes

Routes can be configured in:
- YAML
- XML
- PHP 
- attributes
- annotations

All formats provide the same features and performance.

<ins>Symfony Recommendation</ins>: attributes
because it's convenient to put the route and controller in the same place.


## misc

below show run on cli - grep with known text on the page

    $ curl localhost/prj2/public/en/hello

$ php bin/console make:controller MyappController

# References

* https://getcomposer.org/doc/




