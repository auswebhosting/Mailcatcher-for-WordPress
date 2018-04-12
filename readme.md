## Mailcatcher for WordPress
Tags: mailcatcher, developer, wordpress, wp, mail, email, smtp
Requires at least: 3.0.1
Tested up to: 3.8.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin re-routes all WordPress emails to [Mailcatcher](http://mailcatcher.me/), which is super handy if you need to inspect outgoing emails from your plugin. Simply `define(WP_MAILCATCHER, true);` in your `wp-config.php` to get started.

## Description

This plugin routes WordPress emails to [Mailcatcher](http://mailcatcher.me/). This is super handy tool to add to your WordPress development environment if you're working with emails. Simply `define(WP_MAILCATCHER, true);` in your `wp-config.php` to get started.

See the FAQ for more information on enabling and configuring Mailcatcher for WordPress.

## Installation

Mailcatcher for WordPress is trivial to install:

1. Upload the plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

## Frequently Asked Questions

### How do I enable Mailcatcher for WordPress? =

Mailcatcher can be enabled by adding the following line to your `wp-config.php` file:

    define(WP_MAILCATCHER, true);

### Changelog

#### 1.0
* Initial Commit
