# PHPCS Config

My configuration files for PHP Codesniffer (PHPCS), which are designed to play nice with Mago for formatting.

Clone this repository to `~/.config/phpcs`

Requires PHPCS to be installed globally using Composer:

```bash
# base PHPCS + Slevomat
composer global require squizlabs/php_codesniffer
composer global require slevomat/coding-standard
# for WordPress development, also include their coding standards
composer global require-dev wp-coding-standards/wpcs
```

For more information:

- [My Mago configuration](https://github.com/richmilns/Mago-Config)
- [Slevomat coding standard](https://github.com/slevomat/coding-standard)
