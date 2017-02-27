<p align="center">
    <a href="https://packagist.org/packages/matthijs110/wordpress-downloader"><img src="https://poser.pugx.org/matthijs110/wordpress-downloader/d/total.svg" alt="Total Downloads"></a>
    <a href="https://packagist.org/packages/matthijs110/wordpress-downloader"><img src="https://poser.pugx.org/matthijs110/wordpress-downloader/v/stable.svg" alt="Latest Stable Version"></a>
    <a href="https://packagist.org/packages/matthijs110/wordpress-downloader"><img src="https://poser.pugx.org/matthijs110/wordpress-downloader/license.svg" alt="License"></a>
</p>
# WordPress Downloader (Console)
Symfony console application that will serve a fresh [WordPress](https://wordpress.org/) installation.
```sh
$ php wordpress install [options]
```

### Requirements
* PHP 7
* [Composer](https://getcomposer.org/)
* [cURL](https://curl.haxx.se/docs/manpage.html)
* macOS or Ubuntu

### Installation
Install this package globally
```sh
$ composer global require matthijs110/wordpress-downloader
```

### Usage
Download the latest version
```sh
$ wordpress install
```

Specify a specific version
```sh
$ wordpress install --release=4.7
```

#### Windows users
Prepend PHP before each command
```sh
$ php wordpress
```
