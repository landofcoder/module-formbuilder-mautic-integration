# MAGENTO 2 FORM BUILDER MAUtIC INTEGRATION

    ``landofcoder/module-formbuilder-mautic``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)

The module require 2 modules:

1. [Module Formbuilder Magento 2](https://landofcoder.com/magento-2-form-builder.html)
2. [Module Mautic Magento 2](https://github.com/landofcoder/module-magento2-mautic-integration)

## Main Functionalities

- Send thanks you email to customer via Mautic, after submit form
- Sync contact information on formbuilder submission to Mautic

## Installation
\* = in production please use the `--keep-generated` option

### 1. The module require setup Mautic via composer:
Run commands to setup libs:
```
composer require landofcoder/module-mautic
```

### 2. Setup Formbuilder Magento 2 (Commerce Version) Upload Zip file via FTP to server then run magento 2 commands:

 - Unzip the zip file in `app/code/Lof`
 - Enable the module by running `php bin/magento module:enable Lof_Formbuilder`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`
