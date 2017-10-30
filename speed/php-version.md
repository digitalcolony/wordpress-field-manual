# Update PHP version to 7.x

PHP is the programming language that Wordpress runs on. Over the years, newer faster versions of PHP have been released. However, many web hosts still default to older slower versions.

The reason they default to the older version is because code that has not been updated to run on the latest version can break. It is better to have working code than fast code that breaks.

Our goal is have working code on a fast server.

## Confirm Your Host Has PHP 7.x

PHP 7.x is faster than previous versions. Make sure your host offers PHP 7.x. This is also a good time to confirm what version of PHP is running currently. Many hosts default to older versions, but if you are already up and running fine on PHP 7.x, then you're done. Go to the next tip.

## PHP 7.x is Faster

How much faster is PHP 7.x? Geekflare did tests that showed running Wordpress on PHP 7 [decreased web load times by 50%](https://geekflare.com/wordpress-php-fpm7/) over PHP 5.6! That is massive.

On my site INeedCoffee.com, I was able to shave .2 to .5 seconds off each page load by upgrading my PHP version from 5.6 to 7.1. That may not seem like a lot, but my site was fast when I started. Plus if you multiply that saving across 150,000 monthly page views, my users collectively will spent 8 to 20 hours less waiting for those pages to load.

## Test Plugins and Themes Before Upgrading

But before you upgrade, test that the themes and plugins you are using are compatible with the [PHP Compatibility Checker plugin](https://wordpress.org/plugins/php-compatibility-checker/). If you find any plugins you have are not PHP 7 compatible, there are three options.

1. It is possible that the test was flawed and generated a false positive. You can read or post to the support forum to find out. Note that if it has been more than a year since an update and you can see the developer is not responding to questions, move onto #2.

1. Find an alternative. A different plugin that does the task you need or new theme.

1. If you can't find a replacement for your needs, you may be stuck with the older version of PHP until the old code is updated or someone else steps up to contribute a viable replacement that is compatible with PHP 7.x.

## Upgrade PHP Version

Many webhosts offer a way for customers to change their PHP versions without contacting support. If your host offers cPanel, select To upgrade to a higher version, go to cPanel and select Manage PHP Versions. There you can adjust the PHP version for your website.

[//]: <> (@todo ScreenShot)
[//]: <> (@body Make screenshot of cPanel instructions)

After upgrading the site, test several pages on both the main website and the WordPress Admin. If you get any 500 Server Errors, rollback to the previous working version. Either your theme or one of your plugins is causing issues. More troubleshooting will be required.
