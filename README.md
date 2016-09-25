# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

Step 1: Install composer

Step 2: Install Slim-3 Framework
composer require slim/slim "^3.0"

Step 3: Install Slim-Twig-view (Render View of Slim Framework Template)
composer require slim/twig-view

Step 4: Install php-di/slim-bridge (Dependency Injection)
   Allow to Inject Object into Controller Method!!
   The latest Version of Slim-bridge 1.0.3 does not work!!
   Downgrade and Install version slim-bridge Version 1.0.2
   composer require php-di/slim-bridge 1.0.2

Step 5: Install illuminate/database
   Database component from Lareval
   composer require illuminate/database

Step 6:Generate psr-4 with composer autoload
 In composer.json, type below command  

"autoload" : {
      "psr-4" : {
          "Cart\\" : "app"
      }
}

Run below command in terminal/git
composer dump-autoload



### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
