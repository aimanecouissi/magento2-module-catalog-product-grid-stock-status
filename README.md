# AimaneCouissi_CatalogProductGridStockStatus

[![Latest Stable Version](http://poser.pugx.org/aimanecouissi/module-catalog-product-grid-stock-status/v)](https://packagist.org/packages/aimanecouissi/module-catalog-product-grid-stock-status) [![Total Downloads](http://poser.pugx.org/aimanecouissi/module-catalog-product-grid-stock-status/downloads)](https://packagist.org/packages/aimanecouissi/module-catalog-product-grid-stock-status) [![Magento Version Require](https://img.shields.io/badge/magento-2.4.x-E68718)](https://packagist.org/packages/aimanecouissi/module-catalog-product-grid-stock-status) [![License](http://poser.pugx.org/aimanecouissi/module-catalog-product-grid-stock-status/license)](https://packagist.org/packages/aimanecouissi/module-catalog-product-grid-stock-status) [![PHP Version Require](http://poser.pugx.org/aimanecouissi/module-catalog-product-grid-stock-status/require/php)](https://packagist.org/packages/aimanecouissi/module-catalog-product-grid-stock-status)

Adds a **Stock Status** column to the **Admin → Catalog → Products** grid.

## Installation
```bash
composer require aimanecouissi/module-catalog-product-grid-stock-status
bin/magento module:enable AimaneCouissi_CatalogProductGridStockStatus
bin/magento setup:upgrade
bin/magento cache:flush
```

## Usage

Open **Admin → Catalog → Products**. The **Stock Status** column is visible by default and supports both sorting and filtering for quick product segmentation.

## Uninstall
```bash
bin/magento module:disable AimaneCouissi_CatalogProductGridStockStatus
composer remove aimanecouissi/module-catalog-product-grid-stock-status
bin/magento setup:upgrade
bin/magento cache:flush
```

## License

[MIT](LICENSE)
