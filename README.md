# AimaneCouissi_CatalogProductListingStockStatus

Adds a **Stock Status** column to the Admin **Catalog → Products** grid.
## Installation
```bash
composer require aimanecouissi/module-catalog-product-listing-stock-status
bin/magento module:enable AimaneCouissi_CatalogProductListingStockStatus
bin/magento setup:upgrade
bin/magento cache:flush
```

## Usage
Open **Admin → Catalog → Products** and you’ll see **Stock Status** in the grid by default. You can sort or filter by status for quick segmentation.

## Uninstall
```bash
bin/magento module:disable AimaneCouissi_CatalogProductListingStockStatus
composer remove aimanecouissi/module-catalog-product-listing-stock-status
bin/magento setup:upgrade
bin/magento cache:flush
```

## License
[MIT](LICENSE)
