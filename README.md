# Mage2 Module Igorm MessangerNotificator

    ``igorm/module-messangernotificator``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities
Notifacotar Magento 2

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Igorm`
 - Enable the module by running `php bin/magento module:enable Igorm_MessangerNotificator`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require igorm/module-messangernotificator`
 - enable the module by running `php bin/magento module:enable Igorm_MessangerNotificator`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration

 - enable (mf_notuficator_general/mf_messenger_notificator_enable/enable)


## Specifications

 - Controller
	- frontend > test/index/index


## Attributes



