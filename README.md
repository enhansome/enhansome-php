# Awesome PHP with stars

A curated list of awesome PHP libraries, resources, and useful tools.

## Contributing and Collaborating

Please see [CONTRIBUTING](https://github.com/ziadoz/awesome-php/blob/master/CONTRIBUTING.md) ⭐ 32,673 | 🐛 85 | 📅 2026-07-13, [CODE-OF-CONDUCT](https://github.com/ziadoz/awesome-php/blob/master/CODE-OF-CONDUCT.md) ⭐ 32,673 | 🐛 85 | 📅 2026-07-13 and [COLLABORATING](https://github.com/ziadoz/awesome-php/blob/master/COLLABORATING.md) ⭐ 32,673 | 🐛 85 | 📅 2026-07-13 for details.

## Table of Contents

* [Awesome PHP](#awesome-php)
  * [Composer Repositories](#composer-repositories)
  * [Dependency Management](#dependency-management)
  * [Dependency Management Extras](#dependency-management-extras)
  * [Frameworks](#frameworks)
  * [Framework Extras](#framework-extras)
  * [Content Management Systems](#content-management-systems-cms)
  * [Components](#components)
  * [Micro Frameworks](#micro-frameworks)
  * [Micro Framework Extras](#micro-framework-extras)
  * [Routers](#routers)
  * [Templating](#templating)
  * [Static Site Generators](#static-site-generators)
  * [HTTP](#http)
  * [Scraping](#scraping)
  * [Middlewares](#middlewares)
  * [URL](#url)
  * [Email](#email)
  * [Files](#files)
  * [Streams](#streams)
  * [Dependency Injection](#dependency-injection)
  * [Imagery](#imagery)
  * [Testing](#testing)
  * [Continuous Integration](#continuous-integration)
  * [Documentation](#documentation)
  * [Security](#security)
  * [Passwords](#passwords)
  * [Code Analysis](#code-analysis)
  * [Code Quality](#code-quality)
  * [Static Analysis](#static-analysis)
  * [Architectural](#architectural)
  * [Debugging and Profiling](#debugging-and-profiling)
  * [Error Tracking and Monitoring Services](#error-tracking-and-monitoring-services)
  * [Build Tools](#build-tools)
  * [Task Runners](#task-runners)
  * [Navigation](#navigation)
  * [Asset Management](#asset-management)
  * [Geolocation](#geolocation)
  * [Date and Time](#date-and-time)
  * [Event](#event)
  * [Logging](#logging)
  * [E-commerce](#e-commerce)
  * [PDF](#pdf)
  * [Office](#office)
  * [Database](#database)
  * [Migrations](#migrations)
  * [NoSQL](#nosql)
  * [Queue](#queue)
  * [Search](#search)
  * [Command Line](#command-line)
  * [Authentication and Authorization](#authentication-and-authorization)
  * [Markup and CSS](#markup-and-css)
  * [JSON](#json)
  * [Strings](#strings)
  * [Numbers](#numbers)
  * [Filtering, Sanitizing and Validation](#filtering-sanitizing-and-validation)
  * [API](#api)
  * [Caching and Locking](#caching-and-locking)
  * [Data Structure and Storage](#data-structure-and-storage)
  * [Notifications](#notifications)
  * [Deployment](#deployment)
  * [Internationalisation and Localisation](#internationalisation-and-localisation)
  * [Serverless](#serverless)
  * [Configuration](#configuration)
  * [LLMs](#llms)
  * [Third Party APIs](#third-party-apis)
  * [Extensions](#extensions)
  * [Miscellaneous](#miscellaneous)
* [Software](#software)
  * [PHP Installation](#php-installation)
  * [Development Environment](#development-environment)
  * [Virtual Machines](#virtual-machines)
  * [Text Editors and IDEs](#text-editors-and-ides)
  * [Web Applications](#web-applications)
  * [Infrastructure](#infrastructure)
* [Resources](#resources)
  * [PHP Websites](#php-websites)
  * [PHP Books](#php-books)
  * [PHP Videos](#php-videos)
  * [PHP Conferences](#php-conferences)
  * [PHP Podcasts](#php-podcasts)
  * [PHP Newsletters](#php-newsletters)
  * [PHP Reading](#php-reading)
  * [PHP Internals Reading](#php-internals-reading)

### Composer Repositories

*Composer Repositories.*

* [Firegento](https://packages.firegento.com/) - Magento Module Composer Repository.
* [Packagist](https://packagist.org/) - The PHP Package Repository.
* [Packalyst](https://packalyst.com/) - The Laravel package repository.
* [Private Packagist](https://packagist.com/) - Composer package archive as a service for PHP.
* [WordPress Packagist](https://wpackagist.org/) - Manage your plugins with Composer.

### Dependency Management

*Libraries for dependency and package management.*

* [Pie](https://github.com/php/pie) ⭐ 2,002 | 🐛 13 | 🌐 PHP | 📅 2026-08-31 - The official PHP installer for extensions.
* [Pickle](https://github.com/FriendsOfPHP/pickle) ⭐ 1,652 | 🐛 39 | 🌐 PHP | 📅 2023-09-29 - A PHP extension installer.
* [Composer Installers](https://github.com/composer/installers) ⭐ 1,441 | 🐛 26 | 🌐 PHP | 📅 2026-07-01 - A multi-framework Composer library installer.
* [Composer](https://getcomposer.org/) - A package and dependency manager.
* [Phive](https://phar.io/) - A PHAR manager.

### Dependency Management Extras

*Extras related to dependency management.*

* [Satis](https://github.com/composer/satis) ⭐ 3,296 | 🐛 98 | 🌐 PHP | 📅 2026-08-28 - A static Composer repository generator.
* [Composer Patches](https://github.com/cweagans/composer-patches) ⭐ 1,724 | 🐛 56 | 🌐 PHP | 📅 2026-08-31 - A plugin for Composer to apply patches.
* [Composer Unused](https://github.com/composer-unused/composer-unused) ⭐ 1,688 | 🐛 14 | 🌐 PHP | 📅 2026-04-27 - A CLI Tool to scan for unused composer packages.
* [Composer Normalize](https://github.com/ergebnis/composer-normalize) ⭐ 1,121 | 🐛 27 | 🌐 PHP | 📅 2026-08-30 - A plugin for normalizing `composer.json` files.
* [Composer Merge Plugin](https://github.com/wikimedia/composer-merge-plugin) ⭐ 1,017 | 🐛 72 | 🌐 PHP | 📅 2026-02-17 - A composer plugin to merge several `composer.json` files.
* [Composer Require Checker](https://github.com/maglnet/ComposerRequireChecker) ⭐ 1,010 | 🐛 45 | 🌐 PHP | 📅 2026-09-01 - CLI tool to analyze composer dependencies and verify that no unknown symbols are used in the sources of a package.
* [Composer Prefer Lowest Validator](https://github.com/dereuromark/composer-prefer-lowest) ⭐ 23 | 🐛 1 | 🌐 PHP | 📅 2026-06-28 - A plugin to check if minimum dependencies can be installed and tested.
* [Repman](https://repman.io) - A private PHP package repository manager and Packagist proxy.

### Frameworks

*Web development frameworks.*

* [Yii2](https://github.com/yiisoft/yii2/) ⭐ 14,299 | 🐛 332 | 🌐 PHP | 📅 2026-08-31 - A fast, secure, and efficient web framework.
* [Tempest](https://github.com/tempestphp/tempest-framework) ⭐ 2,258 | 🐛 27 | 🌐 PHP | 📅 2026-08-31 - A framework that gets out of your way.
* [CakePHP](https://cakephp.org/) - A rapid application development framework.
* [CodeIgniter](https://codeigniter.com/) - A powerful PHP framework with a very small footprint.
* [Ecotone](https://docs.ecotone.tech/) - A Service Bus for PHP based on architectural principles of DDD CQRS and Event Sourcing.
* [Laminas](https://getlaminas.org/) - A framework comprised of individual components (previously Zend Framework).
* [Laravel](https://laravel.com/) - A web application framework with expressive, elegant syntax.
* [Nette](https://nette.org) - A web framework comprised of mature components.
* [Phalcon](https://phalcon.io/en-us) - A framework implemented as a C extension.
* [Spiral](https://spiral.dev/) - A high-performance PHP/Go framework.
* [Symfony](https://symfony.com/) - A set of reusable components and a web framework.

### Framework Extras

*Extras related to web development frameworks.*

* [LaravelS](https://github.com/hhxsv5/laravel-s) ⭐ 3,880 | 🐛 70 | 🌐 PHP | 📅 2026-07-20 - An out-of-the-box adapter between Laravel/Lumen and Swoole.
* [CakePHP CRUD](https://github.com/friendsofcake/crud) ⭐ 379 | 🐛 11 | 🌐 PHP | 📅 2026-01-13 - A Rapid Application Development (RAD) plugin for CakePHP.
* [Filament PHP](https://filamentphp.com/) - A powerful open source UI framework for Laravel.
* [Inertia.js](https://inertiajs.com/) - An adapter for building single-page applications using server-side routing and controllers, without a separate API.
* [Livewire](https://livewire.laravel.com/) - Powerful, dynamic, front-end UIs without leaving PHP.

### Content Management Systems (CMS)

*Tools for managing digital content.*

* [WordPress](https://github.com/WordPress/WordPress) ⭐ 21,377 | 🐛 3 | 🌐 PHP | 📅 2026-09-01 - A blogging platform and CMS.
* [Grav](https://github.com/getgrav/grav) ⭐ 15,657 | 🐛 444 | 🌐 PHP | 📅 2026-08-31 - A modern flat-file CMS.
* [Magento](https://github.com/magento/magento2) ⭐ 12,171 | 🐛 2,143 | 🌐 PHP | 📅 2026-08-31 - A widely used open-source e-commerce platform.
* [CraftCMS](https://github.com/craftcms/cms) ⭐ 3,607 | 🐛 537 | 🌐 PHP | 📅 2026-09-01 - A flexible, user-friendly CMS for creating custom digital experiences on the web and beyond.
* [OpenMage](https://github.com/OpenMage/magento-lts) ⭐ 931 | 🐛 287 | 🌐 PHP | 📅 2026-09-01 - Fork of EoL Magento 1 e-commerce platform.
* [Backdrop](https://backdropcms.org) - A CMS targeting small-to-medium-sized business and non-profits (a fork of Drupal).
* [Concrete5](https://www.concretecms.com/) - A CMS targeting users with a minimum of technical skills.
* [Drupal](https://new.drupal.org/home) - An enterprise level CMS.
* [Joomla](https://www.joomla.org/) - Another leading CMS.
* [Kirby](https://getkirby.com/) - A flat-file CMS that adapts to any project.
* [Moodle](https://moodle.org/) - An open-source learning platform.
* [OctoberCMS](https://octobercms.com/) - A CMS built on Laravel.
* [Pico CMS](https://picocms.org/) - A lightweight flat-file CMS.
* [Silverstripe](https://www.silverstripe.org/) - A simple, flexible, and secure CMS.
* [Statamic](https://statamic.com/) - A flat-file and Git-based CMS built on Laravel.
* [Sulu](https://sulu.io/) - A user- and developer-friendly CMS built on the Symfony Framework.
* [TYPO3](https://typo3.org) - An enterprise level CMS.
* [WinterCMS](https://wintercms.com) - A community-maintained fork of OctoberCMS built on Laravel.

### Components

*Standalone components from web development frameworks and development groups.*

* [Aura](https://auraphp.com/) - Independent components, fully decoupled from each other and from any framework.
* [CakePHP Plugins](https://plugins.cakephp.org/) - A directory of CakePHP plugins.
* [Laminas Components](https://docs.laminas.dev/components/) - The components that make the Laminas Framework.
* [Laravel Components](https://github.com/illuminate) - The Laravel Framework components.
* [League of Extraordinary Packages](https://thephpleague.com/) - A PHP package development group.
* [Spatie Open Source](https://spatie.be/open-source) - A collection of open-source PHP and Laravel packages.
* [Symfony Packages](https://symfony.com/packages) - Decoupled libraries for PHP applications.

### Micro Frameworks

*Micro frameworks and routers.*

* [Minicli](https://github.com/minicli/minicli) ⭐ 1,084 | 🐛 0 | 🌐 PHP | 📅 2026-02-13 - Minimalist, dependency-free framework for building CLI-centric PHP applications.
* [Silly](https://github.com/mnapoli/silly) ⭐ 934 | 🐛 4 | 🌐 PHP | 📅 2026-06-29 - A micro-framework for CLI applications.
* [Laravel Zero](https://laravel-zero.com) - A micro-framework for console applications.
* [Mezzio](https://getexpressive.org/) - A micro-framework by Laminas.
* [Slim](https://www.slimframework.com/) - Another simple micro framework.

### Micro Framework Extras

*Extras related to micro frameworks and routers.*

* [Slim Skeleton](https://github.com/slimphp/Slim-Skeleton) ⭐ 1,624 | 🐛 15 | 🌐 PHP | 📅 2025-04-01 - A skeleton for Slim.
* [Slim PHP View](https://github.com/slimphp/PHP-View) ⭐ 275 | 🐛 0 | 🌐 PHP | 📅 2025-11-04 - A simple PHP renderer for Slim.

### Routers

*Libraries for handling application routing.*

* [Fast Route](https://github.com/nikic/FastRoute) ⭐ 5,265 | 🐛 26 | 🌐 PHP | 📅 2026-07-09 - A fast routing library.
* [Klein](https://github.com/klein/klein.php) ⭐ 2,658 | 🐛 95 | 🌐 PHP | 📅 2024-01-30 - A flexible router.
* [Route](https://github.com/thephpleague/route) ⭐ 671 | 🐛 4 | 🌐 PHP | 📅 2026-07-14 - A routing library built on top of Fast Route.
* [Aura.Router](https://github.com/auraphp/Aura.Router) ⭐ 502 | 🐛 3 | 🌐 PHP | 📅 2025-05-02 - A full-featured routing library.

### Templating

*Libraries and tools for templating and lexing.*

* [Mustache](https://github.com/bobthecow/mustache.php) ⭐ 3,286 | 🐛 4 | 🌐 PHP | 📅 2026-07-28 - A PHP implementation of the Mustache template language.
* [MtHaml](https://github.com/arnaud-lb/MtHaml) ⭐ 359 | 🐛 28 | 🌐 PHP | 📅 2022-10-23 - A PHP implementation of the HAML template language.
* [Latte](https://latte.nette.org/) - The safest and truly intuitive templates for PHP.
* [PHPTAL](https://phptal.org/) - A PHP implementation of the [TAL](https://en.wikipedia.org/wiki/Template_Attribute_Language) templating language.
* [Plates](https://platesphp.com/) - A native PHP templating library.
* [Smarty](https://www.smarty.net/) - A template engine to complement PHP.
* [Twig](https://twig.symfony.com/) - A comprehensive templating language.

### Static Site Generators

*Tools for pre-processing content to generate web pages.*

* [Cecil](https://cecil.app/) - A simple and powerful content-driven static site generator.
* [Couscous](https://couscous.io) - A tool for converting Markdown documentation into websites.
* [Jigsaw](https://jigsaw.tighten.com/) - Simple static sites with Laravel's Blade.
* [Sculpin](https://sculpin.io) - A tool that converts Markdown and Twig into static HTML.

### HTTP

*Libraries for working with HTTP.*

* [Guzzle](https://github.com/guzzle/guzzle) ⭐ 23,458 | 🐛 2 | 🌐 PHP | 📅 2026-08-24 - A comprehensive HTTP client.
* [Requests](https://github.com/WordPress/Requests) ⭐ 3,574 | 🐛 123 | 🌐 PHP | 📅 2026-08-31 - A simple HTTP library.
* [Saloon](https://github.com/saloonphp/saloon) ⭐ 2,437 | 🐛 30 | 🌐 PHP | 📅 2026-03-25 - A framework for building beautiful API integrations and SDKs.
* [Symfony HTTP Client](https://github.com/symfony/http-client) ⭐ 2,030 | 🐛 0 | 🌐 PHP | 📅 2026-08-30 - A component to fetch HTTP resources synchronously or asynchronously.
* [Buzz](https://github.com/kriswallsmith/Buzz) ⭐ 1,917 | 🐛 9 | 🌐 PHP | 📅 2026-05-15 - Another HTTP client.
* [Nyholm PSR-7](https://github.com/Nyholm/psr7) ⭐ 1,277 | 🐛 5 | 🌐 PHP | 📅 2025-11-28 - A super lightweight PSR-7 implementation. Very strict and very fast.
* [Laminas Diactoros](https://github.com/laminas/laminas-diactoros) ⭐ 560 | 🐛 33 | 🌐 PHP | 📅 2026-08-31 - PSR-7 HTTP Message implementation.
* [Retrofit](https://github.com/tebru/retrofit-php) ⭐ 154 | 🐛 5 | 🌐 PHP | 📅 2024-07-12 - A library to ease creation of REST API clients.
* [HTTPlug](https://httplug.io) - An HTTP client abstraction without binding to a specific implementation.
* [PHP VCR](https://php-vcr.github.io/) - A library for recording and replaying HTTP requests.

### Scraping

*Libraries for scraping websites and detecting crawlers.*

* [Symfony Panther](https://github.com/symfony/panther) ⭐ 3,068 | 🐛 210 | 🌐 PHP | 📅 2026-06-04 - A browser testing and web crawling library for PHP and Symfony.
* [Chrome PHP](https://github.com/chrome-php/chrome) ⭐ 2,677 | 🐛 0 | 🌐 PHP | 📅 2026-07-06 - Instrument headless Chrome/Chromium instances from PHP.
* [CrawlerDetect](https://github.com/JayBizzle/Crawler-Detect) ⭐ 2,402 | 🐛 0 | 🌐 PHP | 📅 2026-07-30 - A PHP class for detecting bots/crawlers/spiders via the user agent.
* [DiDOM](https://github.com/Imangazaliev/DiDOM) ⭐ 2,198 | 🐛 27 | 🌐 PHP | 📅 2026-01-28 - A super-fast HTML scrapper and parser.
* [Embed](https://github.com/php-embed/Embed) ⭐ 2,140 | 🐛 73 | 🌐 PHP | 📅 2026-07-08 - An information extractor from any web service or page.
* [PHP Spider](https://github.com/mvdbos/php-spider) ⭐ 1,340 | 🐛 4 | 🌐 PHP | 📅 2026-08-04 - A configurable and extensible PHP web spider.

### Middlewares

*Libraries for building application using middlewares.*

* [PSR-15 Middlewares](https://github.com/middlewares/psr15-middlewares) ⭐ 409 | 🐛 0 | 📅 2025-04-05 - Inspiring collection of handy middlewares.
* [Laminas Stratigility](https://github.com/laminas/laminas-stratigility) ⭐ 58 | 🐛 3 | 🌐 PHP | 📅 2026-08-31 - Middleware for PHP built on top of PSR-7.
* [Stack](https://github.com/stackphp) - A library of stackable middleware for Symfony.

### URL

*Libraries for parsing URLs.*

* [PHP Domain Parser](https://github.com/jeremykendall/php-domain-parser) ⭐ 1,239 | 🐛 0 | 🌐 PHP | 📅 2026-01-30 - A domain suffix parser library.
* [Uri](https://github.com/thephpleague/uri) ⭐ 1,134 | 🐛 0 | 🌐 PHP | 📅 2026-03-15 - Another URL manipulation library.
* [sabre/uri](https://github.com/sabre-io/uri) ⭐ 296 | 🐛 6 | 🌐 PHP | 📅 2026-08-26 - A functional URI manipulation library.

### Email

*Libraries for sending and parsing email.*

* [PHPMailer](https://github.com/PHPMailer/PHPMailer) ⭐ 22,283 | 🐛 30 | 🌐 PHP | 📅 2026-09-01 - Another mailer solution.
* [Mautic](https://github.com/mautic/mautic) ⭐ 10,426 | 🐛 171 | 🌐 PHP | 📅 2026-09-01 - Email marketing automation.
* [CssToInlineStyles](https://github.com/tijsverkoyen/CssToInlineStyles) ⭐ 5,825 | 🐛 32 | 🌐 PHP | 📅 2026-01-06 - A library to inline CSS in email templates.
* [Symfony Mailer](https://github.com/symfony/mailer) ⭐ 1,594 | 🐛 0 | 🌐 PHP | 📅 2026-08-31 - A powerful library for creating and sending emails.
* [ddeboer/imap](https://github.com/ddeboer/imap) ⭐ 919 | 🐛 73 | 🌐 PHP | 📅 2026-06-22 - Object-oriented, fully tested PHP IMAP library.
* [Email Reply Parser](https://github.com/willdurand/EmailReplyParser) ⭐ 650 | 🐛 11 | 🌐 PHP | 📅 2022-09-20 - An email reply parser library.
* [Fetch](https://github.com/tedious/Fetch) ⭐ 507 | 🐛 76 | 🌐 PHP | 📅 2024-01-11 - An IMAP library.
* [Stampie](https://github.com/Stampie/Stampie) ⚠️ Archived - A library for email services such as [SendGrid](https://www.twilio.com/en-us/sendgrid), [PostMark](https://postmarkapp.com), [MailGun](https://www.mailgun.com/) and [MailChimp](https://mailchimp.com/features/transactional-email/).

### Files

*Libraries for file manipulation and MIME type detection.*

* [Flysystem](https://github.com/thephpleague/Flysystem) ⭐ 13,587 | 🐛 105 | 🌐 PHP | 📅 2026-08-22 - Abstraction for local and remote filesystems.
* [PHP FFmpeg](https://github.com/PHP-FFmpeg/PHP-FFmpeg/) ⭐ 5,017 | 🐛 327 | 🌐 PHP | 📅 2026-01-19 - A wrapper for the [FFmpeg](https://www.ffmpeg.org/) video library.
* [CSV](https://github.com/thephpleague/csv) ⭐ 3,479 | 🐛 2 | 🌐 PHP | 📅 2026-08-21 - A CSV data manipulation library.
* [Gaufrette](https://github.com/KnpLabs/Gaufrette) ⭐ 2,464 | 🐛 81 | 🌐 PHP | 📅 2026-07-22 - A filesystem abstraction layer.
* [UnifiedArchive](https://github.com/wapmorgan/UnifiedArchive) ⭐ 282 | 🐛 7 | 🌐 PHP | 📅 2026-08-19 - A unified reader and writer of compressed archives.
* [Parquet](https://github.com/flow-php/parquet) ⭐ 61 | 🐛 0 | 🌐 PHP | 📅 2026-08-12 - PHP implementation of Parquet file format.

### Streams

*Libraries for working with streams.*

* [ByteStream](https://amphp.org/byte-stream) - An asynchronous stream abstraction.

### Dependency Injection

*Libraries that implement the dependency injection design pattern.*

* [Symfony DI](https://github.com/symfony/dependency-injection) ⭐ 4,167 | 🐛 0 | 🌐 PHP | 📅 2026-08-22 - A dependency injection container component.
* [Pimple](https://github.com/silexphp/Pimple) ⭐ 2,664 | 🐛 0 | 🌐 PHP | 📅 2026-03-02 - A tiny dependency injection container.
* [Container](https://github.com/thephpleague/container) ⭐ 868 | 🐛 5 | 🌐 PHP | 📅 2026-07-24 - Another flexible dependency injection container.
* [Auryn](https://github.com/rdlowrey/Auryn) ⭐ 724 | 🐛 3 | 🌐 PHP | 📅 2025-03-02 - A recursive dependency injector.
* [Aura.Di](https://github.com/auraphp/Aura.Di) ⭐ 353 | 🐛 3 | 🌐 PHP | 📅 2026-06-16 - A serializable dependency injection container with constructor and setter injection, interface and trait awareness, configuration inheritance, and much more.
* [Acclimate](https://github.com/AcclimateContainer/acclimate-container) ⭐ 220 | 🐛 6 | 🌐 PHP | 📅 2023-08-18 - A common interface to dependency injection containers and service locators.
* [Disco](https://github.com/bitExpert/disco) ⭐ 140 | 🐛 11 | 🌐 PHP | 📅 2026-01-27 - A PSR-11 compatible, annotation-based dependency injection container.
* [PHP-DI](https://php-di.org/) - A dependency injection container that supports autowiring.

### Imagery

*Libraries for manipulating images.*

* [Intervention Image](https://github.com/Intervention/image) ⭐ 14,364 | 🐛 22 | 🌐 PHP | 📅 2026-08-29 - Another image manipulation library.
* [Glide](https://github.com/thephpleague/glide) ⭐ 2,633 | 🐛 37 | 🌐 PHP | 📅 2026-07-16 - An on-demand image manipulation library.
* [PHP QR Code](https://github.com/chillerlan/php-qrcode/) ⭐ 2,385 | 🐛 2 | 🌐 PHP | 📅 2026-08-31 - QR Code generator and reader.
* [Image Hash](https://github.com/jenssegers/imagehash) ⭐ 2,063 | 🐛 39 | 🌐 PHP | 📅 2025-09-17 - A library for generating perceptual image hashes.
* [Color Extractor](https://github.com/thephpleague/color-extractor) ⭐ 1,323 | 🐛 3 | 🌐 PHP | 📅 2026-08-31 - A library for extracting colours from images.
* [Image Optimizer](https://github.com/psliwa/image-optimizer) ⭐ 915 | 🐛 10 | 🌐 PHP | 📅 2023-11-20 - A library for optimizing images.
* [PHP Image Workshop](https://github.com/Sybio/ImageWorkshop) ⭐ 852 | 🐛 23 | 🌐 PHP | 📅 2023-06-13 - Another image manipulation library.
* [Imagine](https://imagine.readthedocs.io/en/latest/index.html) - An image manipulation library.

### Testing

*Libraries for testing codebases and generating test data.*

* [PHPUnit](https://github.com/sebastianbergmann/phpunit) ⭐ 20,044 | 🐛 21 | 🌐 PHP | 📅 2026-09-01 - A unit testing framework.
* [Mockery](https://github.com/mockery/mockery) ⭐ 10,723 | 🐛 91 | 🌐 PHP | 📅 2026-08-20 - A mock object library for testing.
* [Prophecy](https://github.com/phpspec/prophecy) ⭐ 8,469 | 🐛 103 | 🌐 PHP | 📅 2026-04-13 - A highly opinionated mocking framework.
* [Codeception](https://github.com/Codeception/Codeception) ⭐ 4,859 | 🐛 167 | 🌐 PHP | 📅 2026-08-07 - A full stack testing framework.
* [Faker](https://github.com/fakerphp/faker) ⭐ 3,990 | 🐛 36 | 🌐 PHP | 📅 2026-05-02 - A fake data generator library.
* [Alice](https://github.com/nelmio/alice) ⭐ 2,538 | 🐛 52 | 🌐 PHP | 📅 2026-06-15 - An expressive fixture generation library.
* [ParaTest](https://github.com/paratestphp/paratest) ⭐ 2,497 | 🐛 6 | 🌐 PHP | 📅 2026-09-01 - A parallel testing library for PHPUnit.
* [Infection](https://github.com/infection/infection) ⭐ 2,237 | 🐛 219 | 🌐 PHP | 📅 2026-09-01 - An AST-based PHP Mutation testing framework.
* [PHPSpec](https://github.com/phpspec/phpspec) ⭐ 1,907 | 🐛 136 | 🌐 PHP | 📅 2026-08-08 - A design by specification unit testing library.
* [VFS Stream](https://github.com/bovigo/vfsStream) ⭐ 1,440 | 🐛 40 | 🌐 PHP | 📅 2024-08-29 - A virtual filesystem stream wrapper for testing.
* [Kahlan](https://github.com/kahlan/kahlan) ⭐ 1,148 | 🐛 8 | 🌐 PHP | 📅 2026-07-21 - Full stack Unit/BDD testing framework with built-in stub, mock and code-coverage support.
* [Foundry](https://github.com/zenstruck/foundry) ⭐ 800 | 🐛 33 | 🌐 PHP | 📅 2026-08-26 - A fixture factory generation library for Doctrine.
* [PHP MySQL Engine](https://github.com/vimeo/php-mysql-engine) ⭐ 561 | 🐛 10 | 🌐 PHP | 📅 2026-07-17 - A MySQL engine written in pure PHP.
* [Nette Tester](https://github.com/nette/tester) ⭐ 488 | 🐛 20 | 🌐 PHP | 📅 2026-07-17 - A productive and enjoyable parallel unit testing framework.
* [Phake](https://github.com/phake/phake) ⭐ 477 | 🐛 19 | 🌐 PHP | 📅 2026-02-10 - Another mock object library for testing.
* [PHP-Mock](https://github.com/php-mock/php-mock) ⭐ 371 | 🐛 3 | 🌐 PHP | 📅 2026-02-06 - A mock library for built-in PHP functions (e.g. time()).
* [PHPUnit Polyfills](https://github.com/Yoast/PHPUnit-Polyfills/) ⭐ 186 | 🐛 5 | 🌐 PHP | 📅 2026-08-20 - Simplifies running PHPUnit tests on multiple PHPUnit versions.
* [Behat](https://docs.behat.org/en/latest/) - A behaviour driven development (BDD) testing framework.
* [Mink](https://mink.behat.org/en/latest/) - Web acceptance testing.
* [Pest](https://pestphp.com/) - A testing framework with a focus on simplicity.
* [PHPT](https://php.github.io/php-src/miscellaneous/writing-tests.html) - A test tool used by PHP itself.

### Continuous Integration

*Libraries and applications for continuous integration.*

* [Setup PHP](https://github.com/shivammathur/setup-php) ⭐ 3,256 | 🐛 6 | 🌐 TypeScript | 📅 2026-09-01 - A GitHub Action for PHP.
* [CircleCI](https://circleci.com) - A continuous integration platform.
* [GitLab CI](https://about.gitlab.com/solutions/continuous-integration/) - A continuous integration platform.
* [Jenkins](https://www.jenkins.io/) - A continuous integration platform with [PHP support](https://www.jenkins.io/solutions/php/).
* [SemaphoreCI](https://semaphore.io/) - A continuous integration platform for open-source and private projects.
* [Travis CI](https://www.travis-ci.com) - A continuous integration platform.

### Documentation

*Libraries for generating project documentation.*

* [zircote/swagger-php](https://github.com/zircote/swagger-php) ⭐ 5,305 | 🐛 16 | 🌐 PHP | 📅 2026-09-01 - Generate OpenAPI documentation for your RESTful API.
* [Scramble](https://github.com/dedoc/scramble) ⭐ 2,192 | 🐛 19 | 🌐 PHP | 📅 2026-08-31 - Automatically generates OpenAPI documentation from your code without annotations.
* [APIGen](https://github.com/apigen/apigen) ⭐ 2,169 | 🐛 24 | 🌐 PHP | 📅 2025-02-21 - Another API documentation generator.
* [daux.io](https://github.com/dauxio/daux.io) ⭐ 829 | 🐛 8 | 🌐 PHP | 📅 2026-08-31 - A documentation generator that uses Markdown files.
* [phpDocumentor](https://phpdoc.org/) - A documentation generator.

### Security

*Libraries for generating secure random numbers, encrypting data and scanning and testing for vulnerabilities.*

* [SQLMap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,334 | 🐛 32 | 🌐 Python | 📅 2026-09-01 - An automatic SQL injection and database takeover tool.
* [Zap](https://github.com/zaproxy/zaproxy) ⭐ 15,714 | 🐛 860 | 🌐 Java | 📅 2026-09-01 - An integrated penetration testing tool for web applications.
* [Halite](https://paragonie.com/project/halite) - A simple library for encryption using [libsodium](https://github.com/jedisct1/libsodium) ⭐ 13,927 | 🐛 1 | 🌐 C | 📅 2026-08-31.
* [PHPSecLib](https://github.com/phpseclib/phpseclib) ⭐ 5,586 | 🐛 209 | 🌐 PHP | 📅 2026-08-31 - A pure PHP secure communications library.
* [PHPGGC](https://github.com/ambionics/phpggc) ⭐ 3,879 | 🐛 21 | 🌐 PHP | 📅 2025-09-29 - A library of PHP unserializable payloads along with a tool to generate them.
* [PHP Encryption](https://github.com/defuse/php-encryption) ⭐ 3,875 | 🐛 11 | 🌐 PHP | 📅 2024-01-02 - Secure PHP Encryption Library.
* [Roave Security Advisories](https://github.com/Roave/SecurityAdvisories) ⭐ 2,914 | 🐛 1 | 📅 2026-08-31 - This package ensures that your application doesn't have installed dependencies with known security vulnerabilities.
* [Optimus](https://github.com/jenssegers/optimus) ⭐ 1,276 | 🐛 14 | 🌐 PHP | 📅 2024-03-27 - Id obfuscation based on Knuth's multiplicative hashing method.
* [AntiXSS](https://github.com/voku/anti-xss) ⭐ 712 | 🐛 3 | 🌐 PHP | 📅 2026-09-01 - A library that tries to preventing Cross-Site Scripting (XSS) attacks by blacklisting.
* [Secure Headers](https://github.com/BePsvPT/secure-headers) ⭐ 550 | 🐛 2 | 🌐 PHP | 📅 2026-07-21 - A package that adds security related headers to HTTP response.
* [OWASP](https://owasp.org/) - Explore the world of cyber security.

### Passwords

*Libraries and tools for working with and storing passwords.*

* [Zxcvbn PHP](https://github.com/bjeavons/zxcvbn-php) ⭐ 873 | 🐛 25 | 🌐 PHP | 📅 2025-02-24 - A realistic PHP password strength estimate library based on Zxcvbn JS.
* [Password-Generator](https://github.com/hackzilla/password-generator) ⭐ 307 | 🐛 5 | 🌐 PHP | 📅 2024-09-01 - PHP library to generate random passwords.
* [Password Validator](https://github.com/jeremykendall/password-validator) ⭐ 142 | 🐛 3 | 🌐 PHP | 📅 2018-04-07 - A library for validating and upgrading password hashes.
* [GenPhrase](https://github.com/timoh6/GenPhrase) ⭐ 115 | 🐛 2 | 🌐 PHP | 📅 2025-02-17 - A library for generating secure random passphrases.
* [phpass](https://www.openwall.com/phpass/) - A portable password hashing framework.

### Code Analysis

*Libraries and tools for analysing, parsing and manipulating codebases.*

* [PHP Parser](https://github.com/nikic/PHP-Parser) ⭐ 17,461 | 🐛 72 | 🌐 PHP | 📅 2026-08-23 - A PHP parser written in PHP.
* [Rector](https://github.com/rectorphp/rector) ⭐ 10,412 | 🐛 5 | 🌐 PHP | 📅 2026-08-31 - A tool to upgrade and refactor code.
* [GrumPHP](https://github.com/phpro/grumphp) ⭐ 4,313 | 🐛 6 | 🌐 PHP | 📅 2026-08-11 - A PHP code-quality tool.
* [Phpactor](https://github.com/phpactor/phpactor) ⭐ 1,922 | 🐛 292 | 🌐 PHP | 📅 2026-08-26 - PHP completion, refactoring and introspection tool.
* [Better Reflection](https://github.com/Roave/BetterReflection) ⭐ 1,247 | 🐛 17 | 🌐 PHP | 📅 2026-09-01 - An AST-based reflection library that allows analysis and manipulation of code.
* [PHP Magic Number Detector](https://github.com/povils/phpmnd) ⭐ 586 | 🐛 21 | 🌐 PHP | 📅 2026-02-25 - A library that detects magic numbers in code.
* [PHPQA](https://github.com/EdgedesignCZ/phpqa) ⭐ 565 | 🐛 4 | 🌐 XSLT | 📅 2025-11-22 - A tool for running QA tools (phploc, phpcpd, phpcs, pdepend, phpmd, phpmetrics).
* [UBench](https://github.com/devster/ubench) ⭐ 563 | 🐛 3 | 🌐 PHP | 📅 2023-09-14 - A simple micro-benchmark library.
* [Scrutinizer](https://scrutinizer-ci.com/) - A web tool to [scrutinise PHP code](https://github.com/scrutinizer-ci/php-analyzer) ⭐ 439 | 🐛 414 | 📅 2021-10-03.
* [PHP Semantic Versioning Checker](https://github.com/tomzx/php-semver-checker) ⭐ 437 | 🐛 39 | 🌐 PHP | 📅 2026-02-05 - A command line utility that compares two source sets and determines the appropriate semantic versioning to apply.
* [Bladestan](https://github.com/bladestan/bladestan) ⭐ 375 | 🐛 18 | 🌐 PHP | 📅 2026-08-28 - A PHPStan extension for static analysis of Blade templates.
* [Editorconfig-Checker](https://github.com/editorconfig-checker/editorconfig-checker.php) ⭐ 76 | 🐛 6 | 🌐 PHP | 📅 2026-08-10 - A command line utility which verifies that your files implement your `.editorconfig` rules.
* [Code Climate](https://codeclimate.com) - An automated code review.
* [PHP AST Viewer](https://php-ast-viewer.com/) - A tool for viewing the Abstract Syntax Tree of PHP code.

### Code Quality

*Libraries for managing code quality, formatting and linting.*

* [PHP CS Fixer](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer) ⭐ 13,548 | 🐛 82 | 🌐 PHP | 📅 2026-08-31 - A coding standards fixer library.
* [Laravel Pint](https://github.com/laravel/pint) ⭐ 3,158 | 🐛 13 | 🌐 PHP | 📅 2026-08-17 - A coding standards fixer library for Laravel.
* [PHP Mess Detector](https://github.com/phpmd/phpmd) ⭐ 2,451 | 🐛 63 | 🌐 PHP | 📅 2026-08-23 - A library that scans code for bugs, sub-optimal code, unused parameters and more.
* [PHP CodeSniffer](https://github.com/PHPCSStandards/PHP_CodeSniffer) ⭐ 1,554 | 🐛 199 | 🌐 PHP | 📅 2026-08-21 - A library that detects and can auto-fix PHP, CSS and JS coding standard violations.
* [CaptainHook](https://github.com/captainhook-git/captainhook) ⭐ 1,117 | 🐛 12 | 🌐 PHP | 📅 2026-03-25 - An easy-to-use and flexible Git hook library.
* [PHPCheckstyle](https://github.com/PHPCheckstyle/phpcheckstyle) ⭐ 166 | 🐛 18 | 🌐 PHP | 📅 2022-12-09 - A tool to help adhere to certain coding conventions.
* [PHP CS Fixer Configurator](https://mlocati.github.io/php-cs-fixer-configurator/) - A web application to help configure PHP CS Fixer rule sets.

### Static Analysis

*Libraries for performing static analysis of PHP code.*

* [PHPStan](https://github.com/phpstan/phpstan) ⭐ 14,093 | 🐛 1,139 | 🌐 PHP | 📅 2026-09-01 - A PHP Static Analysis Tool.
* [Larastan](https://github.com/larastan/larastan) ⭐ 6,502 | 🐛 115 | 🌐 PHP | 📅 2026-08-31 - A PHPStan wrapper for Laravel that adds static analysis to Laravel projects.
* [Psalm](https://github.com/vimeo/psalm) ⭐ 5,887 | 🐛 2,101 | 🌐 PHP | 📅 2026-07-13 - A static analysis tool for finding errors in PHP applications.
* [phan](https://github.com/phan/phan) ⭐ 5,624 | 🐛 794 | 🌐 PHP | 📅 2026-08-26 - A static analyzer based on PHP 7+ and the php-ast extension.
* [Mago](https://github.com/carthage-software/mago) ⭐ 3,420 | 🐛 106 | 🌐 Rust | 📅 2026-08-29 - A toolchain for PHP that aims to improve the developer experience.
* [Deptrac](https://github.com/deptrac/deptrac) ⭐ 2,999 | 🐛 37 | 🌐 PHP | 📅 2026-08-14 - A static analysis tool for enforcing dependency rules between architectural layers.
* [PHP Metrics](https://github.com/phpmetrics/PhpMetrics) ⭐ 2,613 | 🐛 3 | 🌐 PHP | 📅 2026-08-21 - A static metric library.
* [PHPCompatibility](https://github.com/PHPCompatibility/PHPCompatibility) ⭐ 2,301 | 🐛 103 | 🌐 PHP | 📅 2026-08-30 - A PHP compatibility checker for PHP CodeSniffer.
* [PHPDoc Parser](https://github.com/phpstan/phpdoc-parser) ⭐ 1,533 | 🐛 20 | 🌐 PHP | 📅 2026-09-01 - Next-gen phpDoc parser with support for intersection types and generics.
* [PHP Architecture Tester](https://github.com/carlosas/phpat) ⭐ 1,276 | 🐛 17 | 🌐 PHP | 📅 2026-08-10 - Easy-to-use architecture testing tool for PHP.
* [Dead Code Detector](https://github.com/shipmonk-rnd/dead-code-detector) ⭐ 509 | 🐛 10 | 🌐 PHP | 📅 2026-08-31 - A PHPStan extension for finding unused PHP code.
* [Exakat](https://github.com/exakat/exakat) ⭐ 380 | 🐛 47 | 🌐 PHP | 📅 2022-03-24 - A static analysis engine for PHP.

### Architectural

*Libraries related to design patterns, programming approaches and ways to organize code.*

* [Design Patterns PHP](https://github.com/DesignPatternsPHP/DesignPatternsPHP) ⭐ 22,187 | 🐛 1 | 🌐 PHP | 📅 2025-02-03 - A repository of software patterns implemented in PHP.
* [Functional PHP](https://github.com/lstrojny/functional-php) ⭐ 1,984 | 🐛 16 | 🌐 PHP | 📅 2026-03-21 - A functional programming library.
* [Finite](https://github.com/yohang/Finite) ⭐ 1,350 | 🐛 0 | 🌐 PHP | 📅 2025-12-01 - A simple PHP finite state machine.
* [Iter](https://github.com/nikic/iter) ⭐ 1,141 | 🐛 16 | 🌐 PHP | 📅 2025-08-10 - A library that provides iteration primitives using generators.
* [Pipeline](https://github.com/thephpleague/pipeline) ⭐ 998 | 🐛 4 | 🌐 PHP | 📅 2025-02-06 - A pipeline pattern implementation.
* [RulerZ](https://github.com/K-Phoen/rulerz) ⭐ 876 | 🐛 26 | 🌐 PHP | 📅 2022-09-02 - A powerful rule engine and implementation of the Specification pattern.
* [Porter](https://github.com/ScriptFUSION/Porter) ⭐ 611 | 🐛 11 | 🌐 PHP | 📅 2026-03-10 - Data import abstraction library for consuming Web APIs and other data sources.
* [IterTools PHP](https://github.com/markrogoyski/itertools-php) ⭐ 151 | 🐛 1 | 🌐 PHP | 📅 2026-07-26 - A library that provides functionality for working with iterable entities (similar to itertools library in Python).

### Debugging and Profiling

*Libraries and tools for debugging errors and profiling code.*

* [Whoops](https://github.com/filp/whoops) ⭐ 13,233 | 🐛 9 | 🌐 PHP | 📅 2026-08-16 - A pretty error-handling library.
* [Symfony VarDumper](https://github.com/symfony/var-dumper) ⭐ 7,427 | 🐛 0 | 🌐 PHP | 📅 2026-08-30 - A variable dumper component.
* [xDebug](https://github.com/xdebug/xdebug) ⭐ 3,415 | 🐛 9 | 🌐 PHP | 📅 2026-08-21 - A debug and profile tool for PHP.
* [Kint](https://github.com/kint-php/kint) ⭐ 2,819 | 🐛 4 | 🌐 PHP | 📅 2026-01-18 - A debugging and profiling tool.
* [XHProf](https://github.com/phacility/xhprof) ⭐ 2,595 | 🐛 34 | 🌐 PHP | 📅 2019-05-28 - A profiling tool originally developed by Facebook.
* [PHPBench](https://github.com/phpbench/phpbench) ⭐ 2,018 | 🐛 38 | 🌐 PHP | 📅 2026-06-14 - A benchmarking framework.
* [Tracy](https://github.com/nette/tracy) ⭐ 1,837 | 🐛 27 | 🌐 PHP | 📅 2026-08-18 - A simple error detection, logging and time measuring library.
* [PHPSpy](https://github.com/adsr/phpspy) ⭐ 1,500 | 🐛 23 | 🌐 C | 📅 2026-05-21 - A low-overhead sampling profiler.
* [Barbushin PHP Console](https://github.com/barbushin/php-console) ⭐ 1,332 | 🐛 56 | 🌐 PHP | 📅 2024-02-07 - Another web debugging console using Google Chrome.
* [LaraDumps](https://github.com/laradumps/laradumps) ⭐ 1,269 | 🐛 3 | 🌐 PHP | 📅 2026-08-16 - A debugging tool for Laravel with a dedicated desktop application.
* [PCOV](https://github.com/krakjoe/pcov) ⭐ 789 | 🐛 34 | 🌐 C | 📅 2026-07-21 - A self-contained code coverage compatible driver.
* [PHP Console](https://github.com/Seldaek/php-console) ⭐ 525 | 🐛 6 | 🌐 PHP | 📅 2021-03-14 - A web debugging console.
* [Metrics](https://github.com/beberlei/metrics) ⭐ 323 | 🐛 0 | 🌐 PHP | 📅 2026-08-28 - A simple metrics API library.
* [Trap](https://github.com/buggregator/trap) ⭐ 274 | 🐛 33 | 🌐 PHP | 📅 2026-06-16 - An extended variable dumper with a web interface and IDE plugin.
* [APM](https://pecl.php.net/package/APM) - Monitoring extension collecting errors and statistics into SQLite/MySQL/StatsD.
* [PHP Debug Bar](https://php-debugbar.com/) - A debugging toolbar.
* [Z-Ray](https://www.zend.com/products/z-ray) - A debug and profile tool for Zend Server.

### Error Tracking and Monitoring Services

*Self-hosted or cloud-based application performance monitoring & error tracking tools*

* [Blackfire](https://www.blackfire.io) - A low-overhead code profiler.
* [Buggregator](https://buggregator.dev) - A debug server that aggregates var-dumps, profiling data, emails, logs and Sentry events.
* [BugSnag](https://www.bugsnag.com/) - Error and Real User Monitoring.
* [Honeybadger](https://www.honeybadger.io/) - Error Tracking & Application Monitoring for Developers.
* [Rollbar](https://rollbar.com/) - Error Logging & Tracking Service for Software Teams.
* [Sentry](https://sentry.io/welcome/) - Application Performance Monitoring & Error Tracking Software.
* [Tideways](https://tideways.com/) - Monitoring and profiling tool.

### Build Tools

*Project build and automation tools.*

* [Box](https://github.com/box-project/box) ⭐ 1,321 | 🐛 101 | 🌐 PHP | 📅 2026-06-29 - A utility to build PHAR files.
* [RMT](https://github.com/liip/RMT) ⭐ 459 | 🐛 22 | 🌐 PHP | 📅 2025-12-03 - A library for versioning and releasing software.
* [PHPacker](https://github.com/phpacker/phpacker) ⭐ 422 | 🐛 5 | 🌐 PHP | 📅 2025-11-07 - A PHAR builder that compiles PHP apps to standalone executables.
* [Phing](https://www.phing.info/) - A PHP project build system inspired by Apache Ant.

### Task Runners

*Libraries for automating and running tasks.*

* [Robo](https://github.com/consolidation/Robo) ⭐ 2,708 | 🐛 186 | 🌐 PHP | 📅 2025-11-14 - A PHP task runner with object-oriented configurations.
* [Jobby](https://github.com/jobbyphp/jobby) ⭐ 1,048 | 🐛 36 | 🌐 PHP | 📅 2024-03-29 - A PHP cron job manager without modifying crontab.

### Navigation

*Tools for building navigation structures.*

* [KnpMenu](https://github.com/KnpLabs/KnpMenu) ⭐ 1,394 | 🐛 22 | 🌐 PHP | 📅 2026-08-21 - A menu library.
* [Menu](https://github.com/spatie/menu) ⭐ 754 | 🐛 0 | 🌐 PHP | 📅 2025-09-08 - A flexible menu library with a fluent interface.

### Asset Management

*Tools for managing, compressing and minifying website assets.*

* [Laravel Mix](https://github.com/laravel-mix/laravel-mix) ⭐ 5,220 | 🐛 271 | 🌐 JavaScript | 📅 2024-01-24 - An elegant wrapper around Webpack for the 80% use case.
* [Symfony Asset](https://github.com/symfony/asset) ⭐ 3,148 | 🐛 0 | 🌐 PHP | 📅 2026-08-14 - Manages URL generation and versioning of web assets.
* [Symfony Encore](https://github.com/symfony/webpack-encore) ⭐ 2,220 | 🐛 22 | 🌐 JavaScript | 📅 2026-08-14 - A simple but powerful API for processing and compiling assets built around Webpack.
* [JShrink](https://github.com/tedious/JShrink) ⭐ 763 | 🐛 14 | 🌐 PHP | 📅 2025-11-20 - A JavaScript minifier library.

### Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [Country List](https://github.com/umpirsky/country-list) ⭐ 5,252 | 🐛 12 | 🌐 HTML | 📅 2026-04-17 - A list of all countries with names and ISO 3166-1 codes.
* [PHPGeo](https://github.com/mjaschen/phpgeo) ⭐ 1,612 | 🐛 21 | 🌐 PHP | 📅 2026-08-06 - A simple geo library.
* [GeoTools](https://github.com/thephpleague/geotools) ⭐ 1,406 | 🐛 25 | 🌐 PHP | 📅 2026-03-22 - A library of geo-related tools.
* [GeoJSON](https://github.com/jmikola/geojson) ⭐ 307 | 🐛 10 | 🌐 PHP | 📅 2024-01-17 - A GeoJSON implementation.
* [GeoCoder](https://geocoder-php.org/) - A geocoding library.

### Date and Time

*Libraries for working with dates and times.*

* [Carbon](https://github.com/briannesbitt/Carbon) ⭐ 16,596 | 🐛 4 | 🌐 PHP | 📅 2026-08-30 - A simple DateTime API extension.
* [Chronos](https://github.com/cakephp/chronos) ⭐ 1,362 | 🐛 2 | 🌐 PHP | 📅 2026-08-31 - A DateTime API extension supporting both mutable and immutable date/time.
* [Yasumi](https://github.com/azuyalabs/yasumi) ⭐ 1,098 | 🐛 7 | 🌐 PHP | 📅 2026-08-30 - A library to help you calculate the dates and names of holidays.
* [Moment.php](https://github.com/fightbulc/moment.php) ⭐ 967 | 🐛 21 | 🌐 PHP | 📅 2025-07-27 - Moment.js inspired PHP DateTime handler with i18n support.
* [PHP RRule](https://github.com/rlanvin/php-rrule) ⭐ 710 | 🐛 10 | 🌐 PHP | 📅 2026-07-29 - A library for working with recurring dates and times based on the iCalendar RRule spec.
* [CalendR](https://github.com/yohang/CalendR) ⭐ 467 | 🐛 11 | 🌐 PHP | 📅 2025-12-02 - A calendar management library.
* [Business Time](https://github.com/kylekatarnls/business-time) ⭐ 318 | 🐛 0 | 🌐 PHP | 📅 2025-10-25 - A Carbon extension for handling business hours and working days.

### Event

*Libraries that are event-driven or implement non-blocking event loops.*

* [Swoole](https://github.com/swoole/swoole-src) ⭐ 18,914 | 🐛 41 | 🌐 C++ | 📅 2026-09-01 - An event-driven asynchronous and concurrent networking communication framework with high performance for PHP written in C.
* [Workerman](https://github.com/walkor/Workerman) ⭐ 11,546 | 🐛 107 | 🌐 PHP | 📅 2026-08-29 - An event-driven non-blocking I/O library.
* [ReactPHP](https://github.com/reactphp/reactphp) ⭐ 9,091 | 🐛 0 | 🌐 PHP | 📅 2024-11-25 - An event-driven non-blocking I/O library.
* [Ratchet](https://github.com/ratchetphp/Ratchet) ⭐ 6,436 | 🐛 9 | 🌐 PHP | 📅 2026-06-14 - A web socket library.
* [Amp](https://github.com/amphp/amp) ⭐ 4,433 | 🐛 20 | 🌐 PHP | 📅 2026-07-26 - An event-driven non-blocking I/O library.
* [RxPHP](https://github.com/ReactiveX/RxPHP) ⭐ 1,732 | 🐛 15 | 🌐 PHP | 📅 2026-04-08 - A reactive extension library.
* [Event](https://github.com/thephpleague/event) ⭐ 1,571 | 🐛 2 | 🌐 PHP | 📅 2025-03-14 - An event library with a focus on domain events.
* [Broadway](https://github.com/broadway/broadway) ⚠️ Archived - An event source and CQRS library.
* [Evenement](https://github.com/igorw/evenement) ⭐ 1,358 | 🐛 3 | 🌐 PHP | 📅 2025-12-26 - An event dispatcher library.
* [Pawl](https://github.com/ratchetphp/Pawl) ⭐ 616 | 🐛 27 | 🌐 PHP | 📅 2026-07-28 - An asynchronous web socket client.
* [Fast CGI Client](https://github.com/hollodotme/fast-cgi-client) ⭐ 564 | 🐛 14 | 🌐 PHP | 📅 2024-05-02 - A client to make synchronous/asynchronous requests through php-fpm socket.
* [Prooph Event Store](https://github.com/prooph/event-store) ⭐ 548 | 🐛 1 | 🌐 PHP | 📅 2026-05-03 - An event source component to persist event messages.
* [PHP Defer](https://github.com/php-defer/php-defer) ⭐ 309 | 🐛 0 | 🌐 PHP | 📅 2023-09-21 - Golang's defer statement for PHP.
* [Elephant.io](https://github.com/ElephantIO/elephant.io) ⭐ 138 | 🐛 2 | 🌐 PHP | 📅 2026-06-24 - Yet another web socket library.
* [CakePHP Event](https://github.com/cakephp/event) ⭐ 23 | 🐛 0 | 🌐 PHP | 📅 2026-08-24 - An event dispatcher library.
* [FrankenPHP](https://frankenphp.dev/) - A modern PHP app server written in Go.

### Logging

*Libraries for generating and working with log files.*

* [Monolog](https://github.com/Seldaek/monolog) ⭐ 21,402 | 🐛 13 | 🌐 PHP | 📅 2026-09-01 - A comprehensive logger.

### E-commerce

*Libraries and applications for taking payments and building online e-commerce stores.*

* [OmniPay](https://github.com/thephpleague/omnipay) ⭐ 6,058 | 🐛 110 | 🌐 PHP | 📅 2026-07-10 - A framework agnostic multi-gateway payment processing library.
* [Money](https://github.com/moneyphp/money) ⭐ 4,860 | 🐛 5 | 🌐 PHP | 📅 2026-07-07 - A PHP implementation of Fowler's money pattern.
* [Shopware](https://github.com/shopware/shopware) ⭐ 3,415 | 🐛 1,315 | 🌐 PHP | 📅 2026-09-01 - Highly customizable e-commerce software.
* [Brick Money](https://github.com/brick/money) ⭐ 1,924 | 🐛 5 | 🌐 PHP | 📅 2026-08-28 - A money library for PHP, with support for contexts, cash roundings, currency conversion.
* [Payum](https://github.com/payum/payum) ⭐ 1,924 | 🐛 100 | 🌐 PHP | 📅 2026-08-30 - A payment abstraction library.
* [Swap](https://github.com/florianv/swap) ⭐ 1,339 | 🐛 0 | 🌐 PHP | 📅 2026-06-17 - An exchange rates library.
* [Shopsys Framework](https://github.com/shopsys/shopsys/) ⭐ 349 | 🐛 121 | 🌐 PHP | 📅 2026-09-01 - An open source e-commerce platform for in-house development teams.
* [Sylius](https://sylius.com/) - An open source e-commerce solution.

### PDF

*Libraries and software for working with PDF files.*

* [Dompdf](https://github.com/dompdf/dompdf) ⭐ 11,178 | 🐛 539 | 🌐 PHP | 📅 2026-08-02 - A HTML to PDF converter.
* [Browsershot](https://github.com/spatie/browsershot) ⭐ 5,242 | 🐛 0 | 🌐 PHP | 📅 2026-07-09 - Convert HTML to an image, PDF or string.
* [Snappy](https://github.com/KnpLabs/snappy) ⭐ 4,474 | 🐛 17 | 🌐 PHP | 📅 2026-07-29 - A PDF and image generation library.
* [Gotenberg](https://github.com/gotenberg/gotenberg-php) ⭐ 394 | 🐛 0 | 🌐 PHP | 📅 2026-08-14 - A PHP client for interacting with Gotenberg.
* [TCPDF](https://tcpdf.org/) - An open source PHP class for generating PDF documents.

### Office

*Libraries for working with office suite documents.*

* [PHPSpreadsheet](https://github.com/PHPOffice/PhpSpreadsheet) ⭐ 13,983 | 🐛 101 | 🌐 PHP | 📅 2026-08-22 - A pure PHP library for reading and writing spreadsheet files (successor of PHPExcel).
* [PHPWord](https://github.com/PHPOffice/PHPWord) ⭐ 7,585 | 🐛 1,240 | 🌐 PHP | 📅 2026-09-01 - A library for working with Microsoft Word documents.
* [PHPPowerPoint](https://github.com/PHPOffice/PHPPresentation) ⭐ 1,373 | 🐛 246 | 🌐 PHP | 📅 2026-08-31 - A library for working with Microsoft PowerPoint Presentations.
* [OpenSpout](https://github.com/openspout/openspout) ⭐ 1,229 | 🐛 10 | 🌐 PHP | 📅 2026-09-01 - A community driven fork of `box/spout`, a PHP library to read and write spreadsheet files (CSV, XLSX and ODS), in a fast and scalable way.

### Database

*Libraries for interacting with databases using object-relational mapping (ORM) or datamapping techniques.*

* [ProxyManager](https://github.com/Ocramius/ProxyManager) ⭐ 4,943 | 🐛 55 | 🌐 PHP | 📅 2026-08-31 - A set of utilities to generate proxy objects for data mappers.
* [Doctrine Extensions](https://github.com/doctrine-extensions/DoctrineExtensions) ⭐ 4,139 | 🐛 56 | 🌐 PHP | 📅 2026-08-31 - A collection of Doctrine behavioural extensions.
* [Laravel Eloquent](https://github.com/illuminate/database) ⭐ 2,772 | 🐛 7 | 🌐 PHP | 📅 2026-09-01 - A simple ORM.
* [Baum](https://github.com/etrepat/baum) ⭐ 2,223 | 🐛 161 | 🌐 PHP | 📅 2024-06-11 - A nested set implementation for Eloquent.
* [Cycle ORM](https://github.com/cycle/orm) ⭐ 1,328 | 🐛 84 | 🌐 PHP | 📅 2026-08-09 - PHP DataMapper, ORM.
* [Spot2](https://github.com/spotorm/spot2) ⭐ 597 | 🐛 64 | 🌐 PHP | 📅 2026-03-19 - A MySQL datamapper ORM.
* [Aura.Sql](https://github.com/auraphp/Aura.Sql) ⭐ 566 | 🐛 2 | 🌐 PHP | 📅 2026-07-25 - Provides an extension to the native PDO along with a profiler and connection locator.
* [Aura.SqlQuery](https://github.com/auraphp/Aura.SqlQuery) ⭐ 456 | 🐛 3 | 🌐 PHP | 📅 2026-08-25 - Independent query builders for MySQL, PostgreSQL, SQLite, and Microsoft SQL Server.
* [Atlas.Orm](https://github.com/atlasphp/Atlas.Orm) ⭐ 429 | 🐛 10 | 🌐 PHP | 📅 2021-05-30 - A data mapper implementation for your persistence model in PHP.
* [Slimdump](https://github.com/webfactory/slimdump) ⭐ 194 | 🐛 15 | 🌐 PHP | 📅 2026-03-17 - An easy dumper tool for MySQL.
* [CakePHP ORM](https://github.com/cakephp/orm) ⭐ 150 | 🐛 1 | 🌐 PHP | 📅 2026-08-28 - Object-Relational Mapper, implemented using the DataMapper pattern.
* [Doctrine](https://www.doctrine-project.org/) - A comprehensive DBAL and ORM.
* [RedBean](https://redbeanphp.com/index.php) - A lightweight, configuration-less ORM.

### Migrations

*Libraries to help manage database schemas and migrations.*

* [Phinx](https://github.com/cakephp/phinx) ⭐ 4,539 | 🐛 147 | 🌐 PHP | 📅 2026-07-21 - Another database migration library.
* [PHPMig](https://github.com/davedevelopment/phpmig) ⭐ 565 | 🐛 29 | 🌐 PHP | 📅 2025-04-29 - Another migration management library.
* [Ruckusing](https://github.com/ruckus/ruckusing-migrations) ⭐ 499 | 🐛 34 | 🌐 PHP | 📅 2025-01-08 - Database migrations for PHP ala ActiveRecord Migrations with support for MySQL, Postgres, SQLite.
* [Doctrine Migrations](https://www.doctrine-project.org/projects/migrations.html) - A migration library for Doctrine.

### NoSQL

*Libraries for working with "NoSQL" backends.*

* [Predis](https://github.com/predis/predis) ⭐ 7,779 | 🐛 27 | 🌐 PHP | 📅 2026-09-01 - A feature-complete Redis library.
* [MongoDB PHP Library](https://github.com/mongodb/mongo-php-library) ⭐ 1,611 | 🐛 1 | 🌐 PHP | 📅 2026-08-31 - The official high-level MongoDB PHP library built on top of the MongoDB PHP Driver.
* [MongoDB](https://github.com/mongodb/mongo-php-driver) ⭐ 923 | 🐛 5 | 🌐 PHP | 📅 2026-08-28 - MongoDB PHP Driver.

### Queue

*Libraries for working with event and task queues.*

* [PHP AMQP](https://github.com/php-amqplib/php-amqplib) ⭐ 4,604 | 🐛 26 | 🌐 PHP | 📅 2026-01-06 - A pure PHP AMQP library.
* [Enqueue](https://github.com/php-enqueue/enqueue-dev) ⭐ 2,220 | 🐛 62 | 🌐 PHP | 📅 2026-08-30 - A message queue package for PHP that supports RabbitMQ, AMQP, STOMP, Amazon SQS, Redis and Doctrine transports.
* [Pheanstalk](https://github.com/pheanstalk/pheanstalk) ⭐ 1,922 | 🐛 7 | 🌐 PHP | 📅 2026-03-06 - A Beanstalkd client library.
* [BunnyPHP](https://github.com/jakubkulhan/bunny) ⭐ 748 | 🐛 43 | 🌐 PHP | 📅 2026-08-08 - A performant pure-PHP AMQP (RabbitMQ) sync and also async (ReactPHP) library.
* [Thumper](https://github.com/php-amqplib/Thumper) ⭐ 277 | 🐛 8 | 🌐 PHP | 📅 2021-12-21 - A RabbitMQ pattern library.
* [Tarantool Queue](https://github.com/tarantool-php/queue) ⭐ 65 | 🐛 2 | 🌐 PHP | 📅 2025-03-08 - PHP bindings for Tarantool Queue.

### Search

*Libraries and software for indexing and performing search queries on data.*

* [ElasticSearch PHP](https://github.com/elastic/elasticsearch-php) ⭐ 5,337 | 🐛 18 | 🌐 PHP | 📅 2026-08-31 - The official client library for [ElasticSearch](https://www.elastic.co/).
* [Elastica](https://github.com/ruflin/Elastica) ⭐ 2,269 | 🐛 104 | 🌐 PHP | 📅 2026-07-28 - A client library for ElasticSearch.
* [Solarium](https://www.solarium-project.org/) - A client library for [Solr](https://solr.apache.org/).
* [SphinxQL Query Builder](https://foolcode.github.io/SphinxQL-Query-Builder/) - A query library for the [Sphinx](https://sphinxsearch.com/) and [Manticore](https://manticoresearch.com/) search engines.

### Command Line

*Libraries related to the command line.*

* [PsySH](https://github.com/bobthecow/psysh) ⭐ 9,831 | 🐛 11 | 🌐 PHP | 📅 2026-08-26 - Another PHP REPL.
* [Cron Expression](https://github.com/mtdowling/cron-expression) ⭐ 4,860 | 🐛 11 | 🌐 PHP | 📅 2024-04-19 - A library to calculate cron run dates.
* [CLI Menu](https://github.com/php-school/cli-menu) ⭐ 1,943 | 🐛 9 | 🌐 PHP | 📅 2025-08-11 - A library for building CLI menus.
* [CLImate](https://github.com/thephpleague/climate) ⭐ 1,896 | 🐛 12 | 🌐 PHP | 📅 2026-08-27 - A library for outputting colors and special formatting.
* [Commando](https://github.com/nategood/commando) ⭐ 801 | 🐛 34 | 🌐 PHP | 📅 2024-05-07 - Another simple command line opt parser.
* [ShellWrap](https://github.com/MrRio/shellwrap) ⭐ 739 | 🐛 9 | 🌐 PHP | 📅 2025-11-10 - A simple command line wrapper library.
* [CLIFramework](https://github.com/c9s/CLIFramework) ⭐ 435 | 🐛 44 | 🌐 PHP | 📅 2023-04-20 - A command-line framework that supports zsh/bash completion generation, subcommands and option constraints. It also powers phpbrew.
* [GetOpt](https://github.com/getopt-php/getopt-php) ⭐ 344 | 🐛 3 | 🌐 PHP | 📅 2026-04-02 - A command line opt parser.
* [GetOptionKit](https://github.com/c9s/GetOptionKit) ⭐ 148 | 🐛 9 | 🌐 PHP | 📅 2025-01-04 - Another command line opt parser.
* [Aura.Cli](https://github.com/auraphp/Aura.Cli) ⭐ 102 | 🐛 2 | 🌐 PHP | 📅 2024-06-07 - Provides the equivalent of request ( Context ) and response ( Stdio ) objects for the command line interface, including Getopt support, and an independent Help object for describing commands.

### Authentication and Authorization

*Libraries for implementing user authentication and authorization.*

* [Json Web Token](https://github.com/lcobucci/jwt) ⭐ 7,480 | 🐛 9 | 🌐 PHP | 📅 2026-09-01 - Json Tokens to authenticate and transmit information.
* [TwitterOAuth](https://github.com/abraham/twitteroauth) ⭐ 4,303 | 🐛 11 | 🌐 PHP | 📅 2026-08-31 - A Twitter OAuth library.
* [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client) ⭐ 3,817 | 🐛 63 | 🌐 PHP | 📅 2026-08-10 - An OAuth 2.0 client library.
* [Paseto](https://github.com/paragonie/paseto) ⭐ 3,398 | 🐛 2 | 🌐 PHP | 📅 2025-07-19 - Platform-Agnostic Security Tokens.
* [PHP oAuthLib](https://github.com/daviddesberg/PHPoAuthLib) ⭐ 1,077 | 🐛 167 | 🌐 PHP | 📅 2024-01-08 - Another OAuth library.
* [OAuth 1.0 Client](https://github.com/thephpleague/oauth1-client) ⭐ 995 | 🐛 10 | 🌐 PHP | 📅 2024-12-10 - An OAuth 1.0 client library.
* [SocialConnect Auth](https://github.com/socialConnect/auth) ⭐ 564 | 🐛 37 | 🌐 PHP | 📅 2026-06-23 - An open source social sign (OAuth1\OAuth2\OpenID\OpenIDConnect).
* [Aura.Auth](https://github.com/auraphp/Aura.Auth) ⭐ 135 | 🐛 0 | 🌐 PHP | 📅 2026-08-15 - Provides authentication functionality and session tracking using various adapters.
* [OAuth2 Server](https://bshaffer.github.io/oauth2-server-php-docs/) - Another OAuth2 server implementation.
* [OAuth2 Server](https://oauth2.thephpleague.com/) - An OAuth2 authentication server, resource server and client library.

### Markup and CSS

*Libraries for working with markup and CSS formats.*

* [Parsedown](https://github.com/erusev/parsedown) ⭐ 15,060 | 🐛 180 | 🌐 PHP | 📅 2026-02-18 - Another Markdown parser.
* [PHP Markdown](https://github.com/michelf/php-markdown) ⭐ 3,462 | 🐛 98 | 🌐 PHP | 📅 2025-06-17 - A Markdown parser.
* [CommonMark PHP](https://github.com/thephpleague/commonmark) ⭐ 2,972 | 🐛 20 | 🌐 PHP | 📅 2026-09-01 - Highly-extensible Markdown parser which fully supports the [CommonMark spec](https://spec.commonmark.org/).
* [HTML to Markdown](https://github.com/thephpleague/html-to-markdown) ⭐ 1,905 | 🐛 21 | 🌐 PHP | 📅 2026-08-10 - Converts HTML into Markdown.
* [PHP CSS Parser](https://github.com/MyIntervals/PHP-CSS-Parser) ⭐ 1,826 | 🐛 158 | 🌐 PHP | 📅 2026-09-01 - A Parser for CSS Files written in PHP.
* [HTML5 PHP](https://github.com/Masterminds/html5-php) ⭐ 1,782 | 🐛 36 | 🌐 HTML | 📅 2026-08-18 - An HTML5 parser and serializer library.
* [Cebe Markdown](https://github.com/cebe/markdown) ⭐ 1,012 | 🐛 45 | 🌐 HTML | 📅 2022-10-04 - A fast and extensible Markdown parser.
* [Essence](https://github.com/essence/essence) ⭐ 769 | 🐛 24 | 🌐 PHP | 📅 2023-03-29 - A library for extracting web media.
* [VObject](https://github.com/sabre-io/vobject) ⭐ 603 | 🐛 102 | 🌐 PHP | 📅 2026-08-02 - A library for parsing VCard and iCalendar objects.
* [Embera](https://github.com/mpratt/Embera) ⭐ 355 | 🐛 6 | 🌐 PHP | 📅 2025-10-07 - An Oembed consumer library.
* [Shiki PHP](https://github.com/spatie/shiki-php) ⭐ 312 | 🐛 0 | 🌐 JavaScript | 📅 2026-04-27 - A [Shiki](https://github.com/shikijs/shiki) ⭐ 13,764 | 🐛 115 | 🌐 TypeScript | 📅 2026-08-10 code highlighting package in PHP.
* [Decoda](https://github.com/milesj/decoda) ⭐ 192 | 🐛 9 | 🌐 PHP | 📅 2022-11-10 - A lightweight markup parser library.
* [Djot](https://github.com/php-collective/djot-php) ⭐ 25 | 🐛 1 | 🌐 PHP | 📅 2026-08-23 - A PHP parser for [Djot](https://djot.net/), a modern light markup language (successor of Markdown).

### JSON

*Libraries for working with JSON.*

* [JSON Lint](https://github.com/Seldaek/jsonlint) ⭐ 1,325 | 🐛 2 | 🌐 PHP | 📅 2026-09-01 - A JSON lint utility.
* [Lazy JSON](https://github.com/cerbero90/lazy-json) ⭐ 254 | 🐛 0 | 🌐 PHP | 📅 2023-11-29 - A memory-efficient lazy parser for large JSON files.
* [JSONMapper](https://github.com/JsonMapper/JsonMapper) ⭐ 221 | 🐛 15 | 🌐 PHP | 📅 2026-08-31 - A library for mapping JSON to PHP objects.

### Strings

*Libraries for parsing and manipulating strings.*

* [UUID](https://github.com/ramsey/uuid) ⭐ 12,630 | 🐛 23 | 🌐 PHP | 📅 2026-07-04 - A library for generating UUIDs.
* [Mobile-Detect](https://github.com/serbanghita/Mobile-Detect) ⭐ 10,679 | 🐛 18 | 🌐 PHP | 📅 2026-08-11 - A lightweight PHP class for detecting mobile devices (including tablets).
* [Agent](https://github.com/jenssegers/agent) ⭐ 4,850 | 🐛 87 | 🌐 PHP | 📅 2024-08-05 - A PHP desktop/mobile user agent parser, based on Mobiledetect.
* [SQL Formatter](https://github.com/jdorn/sql-formatter/) ⭐ 3,846 | 🐛 36 | 🌐 HTML | 📅 2023-05-26 - A library for formatting SQL statements.
* [Device Detector](https://github.com/matomo-org/device-detector) ⭐ 3,522 | 🐛 77 | 🌐 PHP | 📅 2026-08-30 - Another library for parsing user agent strings.
* [Slugify](https://github.com/cocur/slugify) ⭐ 2,898 | 🐛 32 | 🌐 PHP | 📅 2025-11-27 - A library to convert strings to slugs.
* [Jieba-PHP](https://github.com/fukuball/jieba-php) ⭐ 1,377 | 🐛 4 | 🌐 PHP | 📅 2025-12-16 - A PHP port of Python's jieba. Chinese text segmentation for natural language processing.
* [URLify](https://github.com/jbroadway/urlify) ⭐ 674 | 🐛 6 | 🌐 PHP | 📅 2025-04-03 - A PHP port of Django's URLify.js.
* [Portable ASCII](https://github.com/voku/portable-ascii) ⭐ 577 | 🐛 24 | 🌐 PHP | 📅 2026-08-14 - A library to convert strings to ASCII.
* [Portable UTF-8](https://github.com/voku/portable-utf8) ⭐ 518 | 🐛 4 | 🌐 PHP | 📅 2026-07-06 - A string manipulation library with UTF-8 safe replacement methods.
* [Color Jizz](https://github.com/mikeemoo/ColorJizz-PHP) ⭐ 285 | 🐛 7 | 🌐 PHP | 📅 2024-11-22 - A library for manipulating and converting colors.
* [ANSI to HTML5](https://github.com/sensiolabs/ansi-to-html) ⭐ 253 | 🐛 12 | 🌐 PHP | 📅 2025-05-02 - An ANSI to HTML5 converter library.
* [Stringy](https://github.com/voku/Stringy) ⭐ 180 | 🐛 1 | 🌐 PHP | 📅 2026-08-13 - A string manipulation library with multibyte support.
* [Url highlight](https://github.com/vstelmakh/url-highlight) ⭐ 103 | 🐛 1 | 🌐 PHP | 📅 2026-08-31 - A library for parsing URLs from text and converting them into clickable links.
* [Patchwork UTF-8](https://github.com/nicolas-grekas/Patchwork-UTF8) ⭐ 79 | 🐛 1 | 🌐 PHP | 📅 2022-07-12 - A portable library for working with UTF-8 strings.
* [Hyphenation](https://github.com/heiglandreas/Org_Heigl_Hyphenator) ⭐ 54 | 🐛 5 | 🌐 PHP | 📅 2026-08-01 - Text hyphenation based on the TeX hyphenation algorithm.

### Numbers

*Libraries for working with numbers.*

* [MathPHP](https://github.com/markrogoyski/math-php) ⭐ 2,410 | 🐛 58 | 🌐 PHP | 📅 2026-03-09 - A math library for PHP.
* [Brick Math](https://github.com/brick/math) ⭐ 2,163 | 🐛 0 | 🌐 PHP | 📅 2026-08-31 - A library providing large number support: `BigInteger`, `BigDecimal` and `BigRational`.
* [IP](https://github.com/darsyn/ip) ⭐ 257 | 🐛 2 | 🌐 PHP | 📅 2026-07-03 - An immutable value object for working with IPv4 and IPv6 addresses.
* [ByteUnits](https://github.com/gabrielelana/byte-units) ⭐ 168 | 🐛 6 | 🌐 PHP | 📅 2021-01-16 - A library to parse, format and convert byte units in binary and metric systems.
* [PHP Conversion](https://github.com/cniska/php-conversion) ⭐ 132 | 🐛 5 | 🌐 PHP | 📅 2022-06-15 - Another library for converting between units of measure.
* [DecimalObject](https://github.com/php-collective/decimal-object) ⭐ 26 | 🐛 1 | 🌐 PHP | 📅 2026-03-08 - A value object to handle decimals/floats easily and more precisely.
* [PHP Units of Measure](https://github.com/triplepoint/php-units-of-measure) ⭐ 22 | 🐛 0 | 🌐 PHP | 📅 2025-05-01 - A library for converting between units of measure.

### Filtering, Sanitizing and Validation

*Libraries for filtering, sanitizing and validating data.*

* [Respect Validation](https://github.com/Respect/Validation) ⭐ 6,028 | 🐛 12 | 🌐 PHP | 📅 2026-09-01 - A simple validation library.
* [LibPhoneNumber for PHP](https://github.com/giggsey/libphonenumber-for-php) ⭐ 5,051 | 🐛 3 | 🌐 PHP | 📅 2026-08-15 - A PHP implementation of Google's phone number handling library.
* [JSON Schema](https://github.com/jsonrainbow/json-schema) ⭐ 3,632 | 🐛 24 | 🌐 PHP | 📅 2026-08-21 - A [JSON Schema](https://json-schema.org/) validation library.
* [HTML Purifier](https://github.com/ezyang/htmlpurifier) ⭐ 3,351 | 🐛 134 | 🌐 PHP | 📅 2026-08-12 - A standards compliant HTML filter.
* [Assert](https://github.com/beberlei/assert) ⭐ 2,432 | 🐛 49 | 🌐 PHP | 📅 2026-06-10 - A validation library with a rich set of assertions. Supports assertion chaining and lazy assertions.
* [Valitron](https://github.com/vlucas/valitron) ⭐ 1,603 | 🐛 56 | 🌐 PHP | 📅 2024-04-16 - Another validation library.
* [Valinor](https://github.com/CuyZ/Valinor) ⭐ 1,527 | 🐛 31 | 🌐 PHP | 📅 2026-08-11 - A library for mapping to strongly typed value objects.
* [ISO-codes](https://github.com/ronanguilloux/IsoCodes) ⭐ 803 | 🐛 2 | 🌐 PHP | 📅 2026-03-20 - A library for validating inputs according to standards from ISO, International Finance, Public Administrations, GS1, Book Industry, Phone numbers & Zipcodes for many countries.
* [Filterus](https://github.com/ircmaxell/filterus) ⭐ 442 | 🐛 8 | 🌐 PHP | 📅 2018-11-21 - A simple PHP filtering library.
* [Symfony HTML Sanitizer](https://github.com/symfony/html-sanitizer) ⭐ 281 | 🐛 0 | 🌐 PHP | 📅 2026-08-30 - An HTML sanitizer library.
* [Aura.Filter](https://github.com/auraphp/Aura.Filter) ⭐ 157 | 🐛 3 | 🌐 PHP | 📅 2026-05-28 - Provides tools to validate and sanitize objects and arrays.
* [MetaYaml](https://github.com/romaricdrigon/MetaYaml) ⭐ 103 | 🐛 8 | 🌐 PHP | 📅 2019-03-16 - A schema validation library that supports YAML, JSON and XML.
* [Volan](https://github.com/serkin/Volan) ⭐ 44 | 🐛 0 | 🌐 PHP | 📅 2018-06-19 - Another simplified validation library.
* [CakePHP Validation](https://github.com/cakephp/validation) ⭐ 43 | 🐛 0 | 🌐 PHP | 📅 2026-08-24 - Another validation library.

### API

*Libraries and web tools for developing APIs.*

* [Negotiation](https://github.com/willdurand/Negotiation) ⭐ 1,419 | 🐛 11 | 🌐 PHP | 📅 2023-08-03 - A content negotiation library.
* [Restler](https://github.com/Luracast/Restler) ⭐ 1,382 | 🐛 33 | 🌐 PHP | 📅 2026-08-22 - A lightweight framework to expose PHP methods as RESTful web API.
* [Hateoas](https://github.com/willdurand/Hateoas) ⭐ 1,042 | 🐛 33 | 🌐 PHP | 📅 2026-01-10 - A HATEOAS REST web service library.
* [Jane](https://github.com/janephp/janephp/) ⭐ 689 | 🐛 18 | 🌐 PHP | 📅 2026-09-01 - An OpenApi client generator with validation support.
* [PackageGenerator](https://github.com/WsdlToPhp/PackageGenerator) ⭐ 434 | 🐛 26 | 🌐 PHP | 📅 2026-06-30 - Package Generator generates a PHP SDK from any WSDL.
* [HAL](https://github.com/blongden/hal) ⭐ 202 | 🐛 2 | 🌐 PHP | 📅 2026-01-05 - A Hypertext Application Language (HAL) builder library.
* [Laminas API Tool Skeleton](https://github.com/laminas-api-tools/api-tools-skeleton) ⭐ 53 | 🐛 28 | 🌐 PHP | 📅 2024-04-18 - An API builder built with the Laminas Framework.
* [API Platform](https://api-platform.com) - Expose in minutes a hypermedia REST API that embraces JSON-LD, Hydra format.

### Caching and Locking

*Libraries for caching data and acquiring locks.*

* [Doctrine Cache](https://github.com/doctrine/cache) ⭐ 7,855 | 🐛 2 | 🌐 PHP | 📅 2025-10-08 - A caching library.
* [CacheTool](https://github.com/gordalina/cachetool) ⭐ 1,827 | 🐛 18 | 🌐 PHP | 📅 2026-01-28 - A tool to clear APC/opcode caches from the command line.
* [Stash](https://github.com/tedious/Stash) ⭐ 962 | 🐛 34 | 🌐 PHP | 📅 2025-12-27 - Another library for caching.
* [Lock](https://github.com/php-lock/lock) ⭐ 948 | 🐛 3 | 🌐 PHP | 📅 2026-02-19 - A lock library to provide exclusive execution.
* [APIx Cache](https://github.com/apix/cache) ⭐ 114 | 🐛 4 | 🌐 PHP | 📅 2022-07-26 - A thin PSR-6 cache wrapper to various caching backends emphasizing cache tagging and indexing.
* [Laminas Cache](https://github.com/laminas/laminas-cache) ⭐ 107 | 🐛 15 | 🌐 PHP | 📅 2026-08-31 - Another caching library.
* [Metaphore](https://github.com/sobstel/metaphore) ⭐ 99 | 🐛 2 | 🌐 PHP | 📅 2024-02-24 - Cache slam defense using a semaphore to prevent dogpile effect.
* [CakePHP Cache](https://github.com/cakephp/cache) ⭐ 50 | 🐛 0 | 🌐 PHP | 📅 2026-08-24 - A caching library.

### Data Structure and Storage

*Libraries that implement data structure or storage techniques.*

* [Fractal](https://github.com/thephpleague/fractal) ⭐ 3,544 | 🐛 54 | 🌐 PHP | 📅 2025-12-16 - A library for converting complex data structures to JSON output.
* [Serializer](https://github.com/schmittjoh/serializer) ⭐ 2,343 | 🐛 172 | 🌐 PHP | 📅 2026-08-31 - A library for serializing and de-serializing data.
* [JsonMapper](https://github.com/cweiske/jsonmapper) ⭐ 1,573 | 🐛 2 | 🌐 PHP | 📅 2026-06-30 - A library that maps nested JSON structures onto PHP classes.
* [JSON Machine](https://github.com/halaxa/json-machine) ⭐ 1,327 | 🐛 5 | 🌐 PHP | 📅 2026-04-03 - Provides iteration over huge JSONs using simple `foreach`.
* [YaLinqo](https://github.com/Athari/YaLinqo) ⭐ 453 | 🐛 13 | 🌐 PHP | 📅 2025-10-19 - Yet Another LINQ to Objects for PHP.
* [msgpack.php](https://github.com/rybakit/msgpack.php) ⭐ 408 | 🐛 0 | 🌐 PHP | 📅 2026-04-25 - A pure PHP implementation of the [MessagePack](https://msgpack.org/) serialization format.
* [CakePHP Collection](https://github.com/cakephp/collection) ⭐ 91 | 🐛 0 | 🌐 PHP | 📅 2026-08-02 - A simple collections library.
* [Laminas Serializer](https://github.com/laminas/laminas-serializer) ⭐ 36 | 🐛 7 | 🌐 PHP | 📅 2026-08-31 - Another library for serialising and de-serialising data.

### Notifications

*Libraries for working with notification software.*

* [JoliNotif](https://github.com/jolicode/JoliNotif) ⭐ 1,443 | 🐛 1 | 🌐 PHP | 📅 2026-09-01 - A cross-platform library for desktop notification (support for Growl, notify-send, toaster, etc).

### Deployment

*Libraries for project deployment.*

* [Deployer](https://github.com/deployphp/deployer) ⭐ 11,103 | 🐛 18 | 🌐 PHP | 📅 2026-08-26 - A deployment tool.
* [Envoy](https://github.com/laravel/envoy) ⭐ 1,615 | 🐛 2 | 🌐 PHP | 📅 2026-08-20 - A tool to run SSH tasks with PHP.

### Internationalisation and Localisation

*Libraries for Internationalization (I18n) and Localization (L10n).*

* [Aura.Intl](https://github.com/auraphp/Aura.Intl) ⭐ 90 | 🐛 0 | 🌐 PHP | 📅 2022-12-12 - Provides internationalization (I18N) tools, specifically package-oriented per-locale message translation.
* [CakePHP I18n](https://github.com/cakephp/i18n) ⭐ 29 | 🐛 0 | 🌐 PHP | 📅 2026-08-24 - Message translation and localization for dates and numbers.

### Serverless

*Libraries and tools to help build serverless web applications.*

* [Bref](https://bref.sh/) - Serverless PHP on AWS Lambda.
* [OpenWhisk](https://openwhisk.apache.org/) - An open-source serverless cloud platform.
* [Serverless Framework](https://www.serverless.com/framework) - An open-source framework for building serverless applications.
* [Laravel Vapor](https://vapor.laravel.com/) - A serverless deployment platform for Laravel, powered by AWS.

### Configuration

*Libraries and tools for configuration.*

* [PHP Dotenv](https://github.com/vlucas/phpdotenv) ⭐ 13,550 | 🐛 2 | 🌐 PHP | 📅 2026-08-24 - Parse and load environment variables from `.env` files.
* [Symfony Dotenv](https://github.com/symfony/dotenv) ⭐ 3,788 | 🐛 0 | 🌐 PHP | 📅 2026-08-30 - Parse and load environment variables from `.env` files.
* [Toml](https://github.com/php-collective/toml) ⭐ 16 | 🐛 2 | 🌐 PHP | 📅 2026-05-31 - A TOML parser and encoder with AST access and error recovery.

### LLMs

*Libraries for working with Large Language Models.*

* [OpenAI Client](https://github.com/openai-php/client) ⭐ 5,828 | 🐛 27 | 🌐 PHP | 📅 2026-08-18 - OpenAI PHP is a supercharged community-maintained PHP API client that allows you to interact with OpenAI API.
* [OpenAI Client for Laravel](https://github.com/openai-php/laravel) ⭐ 3,751 | 🐛 13 | 🌐 PHP | 📅 2026-07-27 - OpenAI PHP for Laravel is a supercharged PHP API client that allows you to interact with OpenAI API.
* [LLPhant](https://github.com/LLPhant/LLPhant) ⭐ 1,707 | 🐛 36 | 🌐 PHP | 📅 2026-07-26 - A comprehensive PHP Generative AI Framework using OpenAI GPT 4. Inspired by Langchain.
* [Instructor for PHP](https://github.com/cognesy/instructor-php) ⭐ 326 | 🐛 3 | 🌐 PHP | 📅 2026-08-30 - Structured data outputs with LLMs, in PHP.
* [Anthropic for Laravel](https://github.com/mozex/anthropic-laravel) ⭐ 74 | 🐛 1 | 🌐 PHP | 📅 2026-08-28 - A Laravel wrapper for the Anthropic PHP client with Facades, config publishing, and testing fakes.
* [Anthropic](https://github.com/mozex/anthropic-php) ⭐ 48 | 🐛 1 | 🌐 PHP | 📅 2026-08-21 - A PHP client for the Anthropic API, supporting messages, streaming, tool use, and batch processing.
* [PHP Mistral AI SDK](https://github.com/SoftCreatR/php-mistral-ai-sdk) ⭐ 18 | 🐛 0 | 🌐 PHP | 📅 2025-11-21 - A powerful and easy-to-use PHP SDK for the Mistral AI API, allowing seamless integration of advanced AI-powered features into your PHP projects.

### Third Party APIs

*Libraries for accessing third party APIs.*

* [Amazon Web Service SDK](https://github.com/aws/aws-sdk-php) ⭐ 6,202 | 🐛 19 | 🌐 PHP | 📅 2026-08-31 - The official PHP AWS SDK library.
* [Stripe](https://github.com/stripe/stripe-php) ⭐ 4,018 | 🐛 14 | 🌐 PHP | 📅 2026-08-31 - The official Stripe PHP library.
* [Github](https://github.com/KnpLabs/php-github-api) ⭐ 2,206 | 🐛 52 | 🌐 PHP | 📅 2026-08-18 - A library to interface with the Github API.
* [Twilio](https://github.com/twilio/twilio-php) ⭐ 1,635 | 🐛 58 | 🌐 PHP | 📅 2026-09-01 - The official Twilio PHP REST API.
* [Mailgun](https://github.com/mailgun/mailgun-php) ⭐ 1,138 | 🐛 0 | 🌐 PHP | 📅 2026-06-23 - The official Mailgun PHP API.
* [AsyncAWS](https://async-aws.com/) - An unofficial asynchronous PHP AWS SDK.
* [Campaign Monitor](https://campaignmonitor.github.io/createsend-php/) - The official Campaign Monitor PHP library.

### Extensions

*Libraries to help build PHP extensions.*

* [Zephir](https://github.com/zephir-lang/zephir) ⭐ 3,386 | 🐛 48 | 🌐 PHP | 📅 2026-09-01 - A compiled language between PHP and C++ for developing PHP extensions.
* [PHP CPP](https://www.php-cpp.com/) - A C++ library for developing PHP extensions.

### Miscellaneous

*Useful libraries or utilities that don't fit into the categories above.*

* [Annotations](https://github.com/doctrine/annotations) ⭐ 6,730 | 🐛 26 | 🌐 PHP | 📅 2025-12-11 - An annotation library (part of Doctrine).
* [BotMan](https://github.com/botman/botman) ⭐ 6,161 | 🐛 10 | 🌐 PHP | 📅 2026-04-03 - A framework agnostic PHP library to build cross-platform chatbots.
* [Safe](https://github.com/thecodingmachine/safe) ⭐ 2,496 | 🐛 36 | 🌐 PHP | 📅 2026-08-17 - All PHP functions, rewritten to throw exceptions instead of returning false.
* [Hprose-PHP](https://github.com/hprose/hprose-php) ⭐ 1,981 | 🐛 42 | 🌐 PHP | 📅 2024-02-06 - A cross-language RPC.
* [Pagerfanta](https://github.com/whiteoctober/Pagerfanta) ⭐ 1,572 | 🐛 35 | 🌐 PHP | 📅 2020-06-09 - A pagination library.
* [Ganesha](https://github.com/ackintosh/ganesha) ⭐ 670 | 🐛 15 | 🌐 PHP | 📅 2026-06-20 - A PHP implementation of Circuit Breaker pattern.
* [Laravel Serializable Closure](https://github.com/laravel/serializable-closure) ⭐ 608 | 🐛 2 | 🌐 PHP | 📅 2026-08-25 - A library that allows Closures to be serialized.
* [ClassPreloader](https://github.com/ClassPreloader/ClassPreloader) ⭐ 376 | 🐛 1 | 🌐 PHP | 📅 2025-01-13 - A library for optimizing autoloading.
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) ⭐ 364 | 🐛 5 | 🌐 PHP | 📅 2024-04-13 - Helper for Google's noCAPTCHA (reCAPTCHA).

# Software

*Software for creating a development environment.*

### PHP Installation

*Tools to help install and manage PHP on your computer.*

* [PHP Brew](https://github.com/phpbrew/phpbrew) ⭐ 5,526 | 🐛 100 | 🌐 Makefile | 📅 2026-01-28 - A PHP version manager and installer.
* [Static PHP CLI](https://github.com/crazywhalecc/static-php-cli) ⭐ 1,928 | 🐛 38 | 🌐 PHP | 📅 2026-08-22 - Build or [download](https://dl.static-php.dev/static-php-cli/) static versions of PHP CLI and FPM.
* [PHP Build](https://github.com/php-build/php-build) ⭐ 1,049 | 🐛 32 | 🌐 Shell | 📅 2026-08-28 - Another PHP version installer.
* [Brew PHP Switcher](https://github.com/philcook/brew-php-switcher) ⭐ 1,007 | 🐛 18 | 🌐 Shell | 📅 2026-07-15 - Brew PHP switcher.
* [Homebrew](https://brew.sh/) - A package manager for macOS.

### Development Environment

*Software and tools for creating and sharing a development environment.*

* [Docker PHP Extension Installer](https://github.com/mlocati/docker-php-extension-installer) ⭐ 4,965 | 🐛 13 | 🌐 Shell | 📅 2026-08-31 - Easily install PHP extensions in Docker containers.
* [Expose](https://github.com/exposedev/expose) ⭐ 4,570 | 🐛 28 | 🌐 PHP | 📅 2026-07-09 - An open-source PHP tunneling service.
* [DDEV](https://github.com/ddev/ddev) ⭐ 3,824 | 🐛 161 | 🌐 Go | 📅 2026-09-01 - A local web development environment system for PHP.
* [Takeout](https://github.com/tighten/takeout) ⭐ 1,653 | 🐛 5 | 🌐 PHP | 📅 2026-04-09 - A Docker-based development-only dependency manager.
* [Solo](https://github.com/soloterm/solo) ⭐ 1,286 | 🐛 27 | 🌐 PHP | 📅 2026-03-17 - A terminal application to manage processes for a Laravel application.
* [Docksal](https://github.com/docksal/docksal) ⭐ 719 | 🐛 178 | 🌐 Shell | 📅 2025-12-19 - Unified, Docker :whale: powered web development environments for macOS, Windows, and Linux.
* [Ansible](https://www.redhat.com/en/ansible-collaborative) - A radically simple orchestration framework.
* [Docker](https://www.docker.com/) - A containerization platform.
* [Lando](https://lando.dev/) - Push-button development environments.
* [Laravel Homestead](https://laravel.com/docs/master/homestead) - A local development environment for Laravel.
* [Laravel Herd](https://herd.laravel.com/windows) - A one click PHP development environment for macOS and Windows.
* [Laradock](https://laradock.io/) - A full PHP development environment based on Docker.
* [PHPMon](https://phpmon.app/) - A macOS menu bar app for managing PHP installations (works with [Laravel Valet](https://laravel.com/docs/master/valet)).
* [Puppet](https://www.puppet.com) - A server automation framework and application.
* [Vagrant](https://developer.hashicorp.com/vagrant) - A portable development environment utility.

### Virtual Machines

*Alternative PHP virtual machines.*

* [HHVM](https://github.com/facebook/hhvm) ⭐ 18,658 | 🐛 547 | 🌐 C++ | 📅 2026-09-01 - A Virtual Machine, Runtime and JIT for PHP by Facebook.
* [PeachPie](https://github.com/peachpiecompiler/peachpie) ⭐ 2,488 | 🐛 90 | 🌐 C# | 📅 2026-06-09 - PHP compiler and runtime for .NET and .NET Core.
* [Hack](https://hacklang.org/) - A programming language for HHVM.

### Text Editors and IDEs

*Text Editors and Integrated Development Environments (IDE) with support for PHP.*

* [Eclipse for PHP Developers](https://www.eclipse.org/downloads/) - A PHP IDE based on the Eclipse platform.
* [Apache NetBeans](https://netbeans.apache.org/front/main/index.html) - An IDE with support for PHP and HTML5.
* [PhpEd](https://www.nusphere.com/products/phped.htm) - An IDE with professional commercial debugger.
* [PhpStorm](https://www.jetbrains.com/phpstorm/) - A commercial PHP IDE.
* [VS Code](https://code.visualstudio.com/) - An open source code editor.

### Web Applications

*Web-based applications and tools.*

* [Cachet](https://github.com/cachethq/cachet) ⭐ 15,232 | 🐛 6 | 🌐 PHP | 📅 2026-08-31 - The open source status page system.
* [Mailpit](https://github.com/axllent/mailpit) ⭐ 10,242 | 🐛 0 | 🌐 Go | 📅 2026-08-29 - An email and SMTP testing tool for developers.
* [phpMyAdmin](https://github.com/phpmyadmin/phpmyadmin) ⭐ 7,922 | 🐛 939 | 🌐 PHP | 📅 2026-08-31 - A web interface for MySQL/MariaDB.
* [MailCatcher](https://github.com/sj26/mailcatcher) ⭐ 6,778 | 🐛 43 | 🌐 Ruby | 📅 2026-08-29 - A web tool for capturing and viewing emails.
* [Lychee](https://github.com/electerious/Lychee) ⭐ 6,358 | 🐛 0 | 🌐 PHP | 📅 2022-01-08 - An easy to use and great looking photo-management-system.
* [phpRedisAdmin](https://github.com/ErikDubbelboer/phpRedisAdmin) ⭐ 3,180 | 🐛 12 | 🌐 PHP | 📅 2025-12-22 - A simple web interface to manage [Redis](https://redis.io/) databases.
* [PHP Queue](https://github.com/CoderKungfu/php-queue) ⭐ 664 | 🐛 5 | 🌐 PHP | 📅 2026-05-06 - An application for managing queueing backends.
* [3V4L](https://3v4l.org/) - An online PHP & HHVM shell.
* [Adminer](https://www.adminer.org/en/) - Database management in a single PHP file.
* [Leantime](https://leantime.io) - Strategic project management system for the non project manager.
* [PHPSandbox](https://phpsandbox.io) - An online IDE for PHP in the browser.

### Infrastructure

*Infrastructure for providing PHP applications and services.*

* [RoadRunner](https://github.com/roadrunner-server/roadrunner) ⭐ 8,501 | 🐛 54 | 🌐 Go | 📅 2026-08-31 - High-performance PHP application server, load-balancer and process manager.
* [php-pm](https://github.com/php-pm/php-pm) ⭐ 6,547 | 🐛 33 | 🌐 PHP | 📅 2023-12-08 - A process manager, supercharger and load balancer for PHP applications.
* [appserver.io](https://github.com/appserver-io/appserver) ⭐ 960 | 🐛 90 | 🌐 JavaScript | 📅 2023-04-15 - A multithreaded application server for PHP, written in PHP.

# Resources

Various resources, such as books, websites and articles, for improving your PHP development skills and knowledge.

### PHP Websites

*Useful PHP-related websites.*

* [Nomad PHP](https://nomadphp.com/) - A online PHP learning resource.
* [Laravel News](https://laravel-news.com/) - The official Laravel blog.
* [PHP Annotated Monthly](https://blog.jetbrains.com/phpstorm/tag/php-annotated-monthly/) - A monthly digest of PHP news.
* [PHP FIG](https://www.php-fig.org/) - The PHP Framework Interoperability Group.
* [PHP Package Development Standards](https://php-pds.com/) - Package development standards for PHP.
* [PHP School](https://www.phpschool.io/) - Open Source Learning for PHP.
* [PHP The Right Way](https://phptherightway.com/) - A PHP best practice quick reference guide.
* [PHP UG](https://php.ug) - A website to help people locate their nearest PHP user group (UG).
* [PHP Watch](https://php.watch/) - PHP articles, news, upcoming changes, RFCs and more.
* [Unit Testing Tips](https://testing-tips.sarvendev.com/) - Unit Testing Tips by examples in PHP.

### PHP Books

*Fantastic PHP-related books.*

* [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles.
* [Functional Programming in PHP](https://www.functionalphp.com/) - A book on applying functional programming principles and techniques in PHP.
* [Mastering Object-Orientated PHP](https://masteringobjectorientedphp.com/) - A book about object-orientated PHP by Brandon Savage.
* [PHP Cookbook](https://www.oreilly.com/library/view/php-cookbook/9781098121310/) - This cookbook provides code recipes to help you resolve a variety of coding issues.
* [Modernizing Legacy Applications in PHP](https://leanpub.com/mlaphp) - A book about modernizing legacy PHP applications by Paul M. Jones.
* [Scaling PHP Applications](https://www.scalingphpbook.com) - An ebook about scaling PHP applications by Steve Corona.
* [Securing PHP: Core Concepts](https://leanpub.com/securingphp-coreconcepts) - A book about common security terms and practices for PHP by Chris Cornutt.
* [Signaling PHP](https://leanpub.com/signalingphp) - A book about catching PCNTL signals in CLI scripts by Cal Evans.
* [XML Parsing with PHP](https://www.phparch.com/books/xml-parsing-with-php/) - This book covers parsing and validating XML documents, leveraging XPath expressions, and working with namespaces as well as how to create and modify XML files programmatically.

### PHP Videos

*Fantastic PHP-related videos.*

* [Laracasts](https://laracasts.com) - Screencasts about Laravel, Vue JS and more.
* [Laravel YouTube Channel](https://www.youtube.com/channel/UCfO2GiQwb-cwJTb1CuRSkwg) - The official Laravel YouTube channel.
* [Program With Gio](https://www.youtube.com/playlist?list=PLr3d3QYzkw2xabQRUpcZ_IBk9W50M9pe-) - PHP 8 course by Gio.
* [Programming with Anthony](https://www.youtube.com/playlist?list=PLM-218uGSX3DQ3KsB5NJnuOqPqc5CW2kW) - A video series by Anthony Ferrara.
* [SymfonyCasts](https://symfonycasts.com/) - Screencasts and tutorials about PHP and Symfony.

### PHP Conferences

*PHP conferences.*

* [Laracon EU](https://www.youtube.com/@LaraconEU) - Laracon EU is a 2-day event for people who are interested in learning Laravel and related technologies, or who want to share their knowledge with others.
* [PHP\[TEK\]](https://phptek.io/) - The longest-running web developer conference in the United States that has a focus on the PHP programming language.
* [PHP UK Conference](https://www.youtube.com/user/phpukconference/videos) - A collection of videos from the PHP UK Conference.

### PHP Podcasts

*Podcasts with a focus on PHP topics.*

* [Laravel News Podcast](https://podcast.laravel-news.com/) - The Laravel News Podcast brings you all the latest news and events related to the Laravel PHP Framework.
* [Mostly Technical](https://mostlytechnical.com/) - Hosted by Ian Landsman and Aaron Francis, Mostly Technical is a lively discussion on Laravel, business, and an eclectic mix of related topics.
* [No Compromises](https://show.nocompromises.io/) - Two seasoned salty programming veterans talk best practices based on years of working with Laravel SaaS teams.
* [North Meets South Web Podcast](https://www.northmeetssouth.audio/) - Jacob Bennett and Michael Dyrynda conquer a 14.5 hour time difference to talk about life as web developers.
* [Over Engineered](https://overengineered.fm/) - A podcast in mini-series where we explore unimportant programming questions in extreme detail.
* [PHP Internals News](https://phpinternals.news) - A podcast about PHP internals.
* [PHP Town Hall](https://phptownhall.com/) - A casual PHP podcast by Ben Edmunds and Phil Sturgeon.
* [php\[podcast\] episodes from php\[architect\]](https://www.phparch.com/podcast/) - The official podcast of php\[architect] the industry's leading tech magazine and publisher focused on PHP and web development.
* [PHPUgly](https://www.phpugly.com/) - The ramblings of a few overworked PHP Developers.
* [The Laracasts Snippet](https://laracasts.simplecast.com) - The Laracasts snippet, each episode, offers a single thought on some aspect of web development.
* [The Laravel Podcast](https://laravelpodcast.com/) - Laravel and PHP development news and discussion.
* [The PHP Roundtable](https://phproundtable.com/) - The PHP Roundtable is a casual gathering of developers discussing topics that PHP nerds care about.

### PHP Newsletters

*PHP-related news directly to your inbox.*

* [PHP Weekly](https://www.phpweekly.com/) - A weekly newsletter about PHP.

### PHP Reading

*PHP-related reading materials.*

* [php\[architect\]](https://www.phparch.com/magazine/) - A monthly magazine dedicated to PHP.

### PHP Internals Reading

*Reading materials related to the PHP internals or performance.*

* [PHP RFCs](https://wiki.php.net/rfc) - The home of PHP RFCs (Request for Comments).
* [Externals](https://externals.io/) - PHP internal discussions.
* [PHP RFC Watch](https://github.com/beberlei/php-rfc-watch) ⭐ 128 | 🐛 18 | 🌐 HTML | 📅 2026-05-20 - Watch the latest PHP [RFCs](https://wiki.php.net/rfc).
* [PHP Internals Book](https://www.phpinternalsbook.com/) - An online book about PHP internals, written by three core developers.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-01._
