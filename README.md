# PHPCS ruleset for BerlinDB development

- [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
- [PSR-12](https://www.php-fig.org/psr/psr-12/)
- [Neutron PHP Ruleset by Automattic](https://github.com/Automattic/phpcs-neutron-ruleset)
- [Hybrid by Szepeviktor](https://github.com/szepeviktor/phpcs-psr-12-neutron-hybrid-ruleset)

### Features

- PSR-12 Extended Coding Style as starting point
- All [WPCS](https://github.com/WordPress/WordPress-Coding-Standards) features through Neutron
- File permission bits
- Strict types
- File, class and method comments
- Handpicked [Slevomat](https://github.com/slevomat/coding-standard) rules

### Usage

```bash
composer require --dev berlindb/phpcs

./vendor/bin/phpcs --standard=berlindb src/
```
