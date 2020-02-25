# Mage2 Module Kodhub DarkMode

    ``kodhub/module-darkmode``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities
Magento2 Dark Mode for AdminUI

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Kodhub`
 - Enable the module by running `php bin/magento module:enable Kodhub_DarkMode`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require kodhub/module-darkmode`
 - enable the module by running `php bin/magento module:enable Kodhub_DarkMode`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration

 - is_enabled (darkmodeadmin/general/is_enabled)


## Specifications

 - Helper
	- Kodhub\DarkMode\Helper\Config

 - Helper
	- Kodhub\DarkMode\Helper\Helper


## Attributes



