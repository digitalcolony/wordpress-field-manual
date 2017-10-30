# Update PHP version to 7.x

PHP 7.x is faster than previous versions. Make sure your host offers PHP 7.x. Not every plugin will work on PHP 7.x, but there is likely an alternative that does the task that does work with PHP 7.x.

Geekflare did tests that showed running Wordpress on PHP 7 [decreased web load times by 50%](https://geekflare.com/wordpress-php-fpm7/) over PHP 5.6! That is massive.

Many webhosts will default to PHP 5.x versions. To upgrade to a higher version, go to cPanel and select Manage PHP Versions. There you can adjust the PHP version for your website.

But before you upgrade, test that the themes and plugins you are using are compatible with the [PHP Compatibility Checker plugin](https://wordpress.org/plugins/php-compatibility-checker/). If you find any plugins you have are not PHP 7 compatible, seek out a replacement or reach out to the developer.