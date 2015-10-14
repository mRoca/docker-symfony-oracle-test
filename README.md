# docker-symfony-oracle-test

Docker image for Symfony2 app testing, containing git, nginx, php-fpm, Oracle SQL*Plus, [php-oci8](http://php.net/manual/oci8.requirements.php), apc, [composer](https://getcomposer.org/) & [php-cs-fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).

## Licence

**Caution** : you must accept the
[Oracle instant-client](http://www.oracle.com/technetwork/database/features/instant-client/index-097480.html)
[licence agreement](http://www.oracle.com/technetwork/licenses/instant-client-lic-152016.html)
in order to use this tool.

## Usage

See [The parent docker-symfony-test image](https://github.com/mRoca/docker-symfony-test) for usage and documentation.

This image adds the `oci8` Oracle support for php and the `SQL*Plus` command line in containers.
