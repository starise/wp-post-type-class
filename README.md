# WordPress Post Type Class

A single class to help you build more advanced custom post types quickly.

## Requirements

* PHP >= 5.4
* WordPress >= 3.5

## Installation

You can install this plugin via command-line or using the WordPress admin panel.

### via Command-line

Using [Composer](https://getcomposer.org/), add Post Type Class to your project's dependencies.

```sh
composer require starise/wp-post-type-class
```

Then activate the plugin via [wp-cli](http://wp-cli.org/commands/plugin/activate/).

```sh
wp plugin activate wp-post-type-class
```

### via WordPress Admin Panel

1. Download the [latest zip](https://github.com/starise/wp-post-type-class/archive/master.zip) of this repo.
2. In your WordPress admin panel, navigate to Plugins->Add New
3. Click Upload Plugin
4. Upload the zip file that you downloaded.

## Quick Start

Download and declare the use of the class in `functions.php`, then register a new post type:

```php
use Starise\WordPress\PostType as PostType;

new PostType('book');
```

For more details please [check out the wiki](https://github.com/starise/wp-post-type-class/wiki)
